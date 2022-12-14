# **Инструкция по работе с контролем версий Git**

![Эмблема Git](Git.JPG)

## Первоначальная настройка

Настройка информации о пользователе для всех локальных репозиториев
Устанавливает имя, которое будет отображаться в поле автора у выполняемых коммитов

    git config --global user.name "[имя]"

Устанавливает адрес электронной почты, который будет отображаться в информации о выполняемых коммитах

    git config --global user.email "[адрес электронной почты]"

## Инициализация репозитория

Чтобы инициализировать новый репозиторий нужно ввести в терминале команду:

    git init

## Проверка состояния репозитория

Основным инструментом определения состояния файлов является команда:

    git status

Перечисляет все новые или изменённые файлы, которые нуждаются в фиксации

    git diff

Показывает различия по внесённым изменениям в ещё не проиндексированных файлах

    git add

Индексирует указанный файл для последующего коммита
    

## Фиксация изменений

Флажок -m задаст commit message - комментарий разработчика. Он необходим для описания закоммиченных изменений. 

    git commit -m 'Add some code'


## Просмотр изменений

Позволяет посмотреть, что было
изменено, но пока не проиндексировано. сравнивает содержимое в рабочей папке и в области индексиро-
вания. Она выводит список изменений, которые вы внесли, но пока не проиндек-
сировали.

     git diff

Чтобы посмотреть, что из проиндексированного войдет в следующий коммит. Команда сравнивает индексированные
изменения с содержимым последней зафиксированной версии.

    git diff --staged


## Ветвления

Ветвление позволяет отклонившись от основной линии разработки продолжаеть работу независимо от неё, не вмешиваясь в основную линию.

### Просмотр существующих веток

Для просмотра всех имеющихся веток используется команда:

    git branch

## Создание новых веток

Для создания новой ветки используется команда:

    git branch имя ветки

## Переход между ветками

Для перехода между существующими ветками используется команда:

    git checkout имя ветки

## Слияние веток
Для слияния веток используется команда:

    git merge

## Разрешение конфликта

Самый простой способ разрешить конфликт — отредактировать конфликтующий файл. Просто нужно удалить все разделители конфликта.

## Удаление веток

Чтобы удалить ветку используется команда:

    git branch -d имя ветки

## Удаленные репозитории

Удаленные репозитории нужны для...


