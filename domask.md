# Работа с Git 

## Git что это такое?
Git - это реализаций распределённых систем контроля версий, имеющий локальные и удалённые репотизории.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у вас появиться репозиторий 

## Создания коммитов

### Git add
Для добавления измений в коммит используется команда 
*git add*. Чтобы использовать команду *git add* напишите 
*git add <имя файла>*

### Просмотр состояния репозитория 
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и вы увидите были ли изменения в файлах, или их не было.

### Добавления картинки
Чтобы добавить картинку нужно в папку с файломи добавить картинку, потом проверить статус, команда *git status* увидеть изменилось ли что то, после этого написать следующее:
![Горы](Gora.jpg)

### Выделения текста 

Текст можно сделать полужирным или курсивным знаками звёздочка (*) или знаком нижнего подчёркивания (_) вот пример:

*курсив* 
__полужирным__

### Конфликт
Разрешения конфликта 
пример:
![конфликт](conf.png)
Чтобы разрешить конфликт нужно сделать слияние конфликта пример:
![разрешения конфликта](conf1.png)
