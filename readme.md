HEAD -- это голова.
Коммит -- это всему голова.
Статусы файлов:
<тут пустая строка!>

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  tracked    -- "Изменения"     --> modified;
  modified  -- "git add"     --> staged;

%% стрелка без текста для примера: 
  A --> B;
``` 