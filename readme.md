# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
## Подготовка репозитория
## Подготовка репозитория
## Подготовка репозитория
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

Hello world
Всем привет!
hi amigo!!!


hello everyone
good news everyone! 









git -fetch - загрузка объектов и ссылок из другого репозитория.
git -pull - извлечение и интеграция с другим репозиторием или локальной веткой.
git -push - обновление удаленных ссылок вместе со связанными объектами.

git -diff - показывает изменения между коммит, коммитом и рабочим деревом и т. Д
git -rebase - повторное применение коммитов поверх другого базового совета
git -apply -  применить исправление к файлам и / или к индексу

end

it's not end...
hello world!
good bye world!!

## **Сброс текущего HEAD в указанное состояние**
git -reset

## **Переключение ветвей**
git -switch


## **Отображение справочной информации о Git**
git -help


## **Работа с удаленным репозиторием** 


git clone - Клонирование удаленного репозитория

git fetch - Получение изменений из удаленного репозитория

git pull -  Получение изменений из удаленного репозитория

git push - Отправка изменений в удаленный репозиторий

git remote rename - Для переименования удалённого репозитория

## Несколько дополнений из лекций##

1. Делаем форк (fork) интересующего нас репозитория.
2. Мы делаем Git clone для нашей версии этого репозитория.
3. Мы создаем ветку с предлагаемыми изменениями.
4. Производим все изменения только в этой ветке.
5. Отправляем эти изменения на свой аккаунт (push)
6. В окне на Github появляется возможность отправить pull request.

1. Создали аккаунт на Github.com
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удаленный репозиторий. Github при создании нового репозитория подскажет как это можно сделать.
4. Отправить (Push) ваш локальный репозиторий в удаленный (на Github), при этом вам, возможно, нужно будет авторизироваться на удаленном репозитории.
5. Провести изменения "c другого коспьютера"
6. Выкачать (Pull) актуальное состояние из удаленного репозитория.
