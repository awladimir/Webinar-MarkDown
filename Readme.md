# Инструкция для работы с Git и удалёнными репозиториями
# Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
# Подготовка репозитория
Для создание репозитория необходимо выполнить команду _git init_ в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

# Создание коммитов
## Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду git add напишите *git add <имя файла>*

Просмотр состояния репозитория
---
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

# Добавление картинок
## Картинка
   ![картинки](https://miro.medium.com/max/1400/1*vlDY5078rLn0dFQWbdAKUA.png)
## Гифка
   ![гиф](https://raw.githubusercontent.com/nadehi18/battery-wallpaper-windows/master/preview/charging.gif)
## Картинка из папки
   ![картинка](1_S-_fv45WT4MgqtnPVsxtHQ.jpeg)

# Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*
# Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*
# Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда _git log_. Для этого достаточно выполнить команду _git log_ в папке с репозиторием
# Ветки в Git
Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

смотрим команду git commit -am "save all"
# Основные команды Git (для работы с удалённым репозиторием)

- git clone <url-адрес репозитория> - клонирование внешнего репозитория на локальный ПК
- git pull - получение изменений и слияние с локальной версией
- git push - отправляет локальную версию репозитория на внешний
- git comit -am 