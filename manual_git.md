# **Инструкция по использованию системы контроля** 

![Логотип Git](logo.png)

## Программа Git - это консольная утилита для отслеживания и ведения историии изменений файлов в вашем проекте.

## Инициализация репозитория

Чтобы создать (инициализировать) новый репозиторий, нужно ввести в терминале команду:

    git init

## Проверка стостояния репозитория

Чтобы проверить состояние репозитория, надо ввести команду:

    git status

## Добавление изменений

Чтобы добавить изменения в индекс для следующего коммита, нужно ввести команду в терминале:

    git commit <file name>

## Сравнение версий коммитов

Чтобы сравнить ьекущую версию с предыдущим коммитом, нужно в терминале ввести команду:

    git diff

## Вывести список всех коммитов

Чтобы вывести список всех коммитов, нужно в терминале ввести команду:

    git log

## Перемещение между версиями

Что переместиться между разными коммитами, нужно в терминале ввести команду:

    git checkout

## Добавление изменений в файл

Чтобы добавить изменения в выбранный файл, нужно в терминале ввести команду:

    git add /filename

## Отображение названий коммитов в одну строку

Чтобы отобразить названия коммитов в одну строку, нужно в терминале ввести команду:

    git log --oneline

## Отображение все существующих коммитов и их названий в одну строку

Чтобы отобразить все существующие коммиты и их названия в одну строку, нужно в терминале ввести команду:

    git log --oneline --all

## Ветвление

Ветвление в гит нужно чтобы работать эффективно над одним проектом одновременно.


### Слияние

Чтобы слить две ветки в одну нужно ввести в терминале команду:

    git merge branch_name

### Добавление новой ветки

Чтобы добавить новую ветку нужно в терминале ввести команду:

git branch \<new branch name>

## Удаление ветки

Чтобы удалить ветку нужно в терминале ввести команду:

    git branch -d branch_name

### Визуализация ветвления 

Чтобы вывести в терминале визуальное представление всех веток и коммитов нужно ввести команду:

    git log --all --oneline --graph
   
## Удаленные репозитории

Удаленные репозитории - это очень полезная штука!
