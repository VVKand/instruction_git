# **Инструкция по работе Git**

Для начала работы необходимо задать имя пользователя и адрес электронной почты.

    git config --global user.name "user.name"

    git config --global user.email "email@email.com"

Для создание репозитория используется команда

    git init

Для начала отслеживания изменений нужно указать какие файлы необходимо отслеживать

    git add filename

Так же можно добавить все файлы в репозитории

    git add .

Для того чтобы зафиксировать версию используется команда 

    git commit -m "Коментарий"

Посмотреть внесенные изменения после коммита

    git diff

посмотреть журнал изменений

    git log

Чтобы открыть файл с другой версией

    git checkout 
