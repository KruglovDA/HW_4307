## Инструкция по работе с удаленным репозиторием
1. Создать свой аккаунт на Github.com
2. Создать локальный репозиторий в VSC
3. Сконнектить локальный и удалённый репозитории
4. Отправляем локальный репозиторий в удаленный посредством команды push, при этом скорее всего программа предложит авторизоваться на удаленном репозитории
5. Если проводим изменения с другого компьютера или непосредственно в репозитории на Github.com, то выкачиваем изменения в локальный депозиторий посредством команды pull
6. Для того, чтобы сделать pull request:
* в интересующем нас репозитории на Github.com выполняем команду fork, получаем свою версию интересующего нас репозитория
* выполняем команду git clone для своей версии репозитория
* создаём ветку со своими изменениями и работаем в ней
* создаём файл со своими изменениями
* сохраняем все изменения через команду git commit
* отправляем изменения на свой аккаунт посредством команды push
* в аккаунте на Github.com появляется возможность отправить pull request,  нажав соответствующую кнопку
* выполняем pull request