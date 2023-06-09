# Git. Руководство пользователя.
## Локальный репозиторий.
Создаем папку GitFolder - это и есть локальный репозиторий!

## Основные команды.

![Небольшая инструкция](12.jpg)

* **git config --global user.name "Martynkin Slavamir"** - задает имя пользователя

* **git config --global user.email "sss_mmm86@mail.ru"** - задает почтовый адрес пользователя

* **git init** - инициализирует локальный репозиторий

* **git add .\manual.md** - начинаем следить за изменениями файла manual.md

* **git status** - проверка статуса репозитория

* **git commit -m "описаине изменения"** - сохранение изменения с описанием

* **git log** - журнал изменений

* **git diff** - просмотр изменений

* **git checkout 34fb** - возврашение к коммиту начинающемуся на 34fb

* **git checkout master** - возвращение к исходному состоянию


### Ветки
* **git branch branch_name** - создает ветку с именем branch_name

* **git branch** - показывает список веток

* **git checkout -b branch_name** - создание ветки и перемещение в нее

* **git branch -d branch_name** - удаление ветки branch_name

* **git merge branch_name** - выполняет слияния ветки branch_name в текущую ветку

### Работа с Git Hub

* **git clone адрес_из_git_hub** - копирует удаленный репозиторий из Git Hub на ПК

* **Fork** - это кнопка на Git Hub, которая позволяет копировать чей-то удаленный репозиторий на свой аккаунт

* **git pull** - команда притянуть и слить изменения из удаленного репозитория

* **git push** - команда отправить изменения на удаленный репозиторий 

* **pull request** - кнопка позволяющая предложить свою ветку автору репозитория, который мы _"форкнули"_
