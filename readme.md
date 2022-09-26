# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. 

## Подготовка репозитория
Репозиторий Git — это папка, в которой в Git отслеживаются изменения. На компьютере может быть любое количество репозиториев, каждый из которых хранится в собственной папке. Каждый репозиторий Git в системе не зависит, поэтому изменения, сохраненные в одном репозитории Git, не влияют на содержимое другого. Репозиторий Git содержит каждую версию каждого файла, сохраненного в репозитории.

### Создание репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

### Создание коммитов

### Git commit
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение о изменениях>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.


### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория

### Git status
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Перемещение между сохранениями

### Git checkout
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений

### Git log
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git
Ветки в Git - это элемент повседневного процесса разработки. По сути ветки в Git представляют собой указатель на снимок изменений. Если нужно добавить новую возможность или исправить ошибку (незначительную или серьезную), вы создаете новую ветку, в которой будут размещаться эти изменения.

### Создание ветки

### Git branch
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием вводится команда: *git branch <название новой ветки>*

## Слияние веток

### Git merge
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <Наименование ветки>*
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <наименование ветки>*

## Удаление веток
### Git branch -d

Для удаления ветки ввести команду "git branch -d 'наименование ветки'"

## Удаленные репозитории
Удалённые репозитории — это модификации проекта, которые хранятся в интернете или ещё где-то в сети.
jjЧтобы иметь возможность совместной работы над каким-либо Git-проектом, необходимо знать как управлять удалёнными репозиториям

## Добавление удаленных репозиториев
### Git remote add

Чтобы добавить новый удалённый Git-репозиторий под именем-сокращением, к которому будет проще обращаться, необходимо выполнить следующую команду: git remote add [сокращение] [url]

## Копирование удаленных репозиториев
### Git clone
Для копирования уже существующего репозитория необходимо выполнить следующую команду git clone [ссылка на удаленный репозиторий]

### Git push
Данная команда позволяет поделится своими наработками для какого-либо проекта.
То есть, чтобы отправить свои наработки в главный репозиторий необходимо выполнить следующую команду: git push [удал. сервер] [ветка]

КОНЕЦ
