# git status

>**git status** - показывает состояния файлов в рабочем каталоге и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. 

Синтаксис команды **git status**
```
git status [-s] [--long] [--branch] [--porcelain] [--ignore-submodules[=<when>]]
```
## Основные флаги:
* **"-s"** или **"--short"**: показывает краткую информацию о состоянии файлов в формате"git diff --shortstat".

* **"--long"**: показывает длинный формат состояния файлов, включая информацию о последнем коммите для каждого файла.

* **"--branch"**: показывает текущую ветку и ее состояние.

* **"--porcelain"**: показывает состояние файлов в машинно-читаемом формате, что полезно для автоматизации.

*  **"--ignore-submodules"**: позволяет игнорировать изменения в подмодулях.

[Вернуться назад](/readme.md)