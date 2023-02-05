***This is first commit***
commit from github!
 Add request
 # Список необходимых команд GIT


## Содержание

* [Основные команды](#основные-команды)

* [Работа с историей](#работа-с-историей)

* [Работа с ветками](#работа-с-ветками)

* [Работа с удаленными репозиториями](#работа-с-удаленными-репозиториями)



- **git init** - Создает локальный репозиторий в текущей папке.

- **git add** - Добавляет указанные файлы в репозиторий/в следующий commit.

    - **git add .** - Добавить все файлы в текущей папке.

    - **git add <Название файла>** - Добавить определенный файл.

- **git commit** - Фиксирует все произведенные изменения в новый "commit".

    - **git commit -a** - Включить в commit все файлы, когда-либо ранее включенные в репозиторий.

    - **git commit -m "<Описание>"** - Добавить описание к commit-у.

- **git diff** - Отображает все произведенные изменения с момента предыдущего commit-а.

    - **git diff <commit1> <commit2>** - Отображает изменения относительно двух commit-ов.

- **git status** - Отображает текущее состояние репозитория.



## Работа с историей 

- **git log** - Посмотреть историю commit-ов текущей ветки.

    - **git log --oneline** - Одна строка = один commit.

    - **git log --graph** - Отображает историю изменений в графическом виде.

- **git reflog** - Посмотреть всю историю действий репозитория.

- **git checkout <хэшкод commit-а>** - Посмотреть состояние проекта на момент выбранного commit-а. (Устанавливает указатель Head на выбранный commit.)



## Работа с ветками

- **git branch** - Посмотреть список всех доступных веток. Текущая ветка выделена знаком *.

    - **git branch <Название>** - Создать новую ветку на основании текущей.

    - **git branch -d <Название>** - Удалить выбранную ветку. (Все commit-ы, находившиеся в данной ветке, из репозитория не удаляются и их всегда можно найти при помощи git reflog)

- **git checkout <Название>** - Сделать активной выбранную ветку.

    - **git checkout -b <Название>** - Создать новую ветку и сразу сделать ее активной.

- **git merge <Название>** - Объединить выбранную ветку с текущей активной веткой.

- **git diff <branch1> <branch2>** - Отображает изменения относительно двух веток.



---





