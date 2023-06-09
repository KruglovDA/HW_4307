# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездачками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным,необходимо обрамить его двойными звездачками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужырным**._

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*). Например:
* Элемент 1
* Элемент 2
* Элемент 3

Чтобы добавить нумерованные списки, необходимо просто пронумеровать пункты. Например:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Для добавления изображения в текст: ![Привет, это птичка Элина](wallpaper.jpg)

## Работа с удаленным репозиторием

Чаще всего для работы с удаленным репозиторием используется программа GitHub.

Для работы с чужим репозиторием, с возможностью предложить автору принять внесенные изменения, необхолимо выполнить команду Fork (копия удаленного репозитория в свой аккаунт в GitHub).

Для копирования чужого репозитория без возможности предложить автору принять внесенные изменения используется команда git clone (копия файлов удаленного репозитория в локальный репозиторий).

При создании удаленного репозитория из GitHub в VS необходимо указать следующие команды:

* git remote add origin "указываем адрес ссылки"

* git branch -M main (указание какую ветку считать основной, будет считаться та в которой эта команда введена)

* git push -u origin main (копируем файлы из локального репозитория в удаленный)

* git pull (копируем из удаленного репозитория в локальный)
