# **Инструкция по  работе с _Git_**

## Основные команды

* git status
* git init
* git add
* git commit
* git log
* git checkout
* git diff
* git branch
* git branch branch_name
* git checkout branch_name
* git log --graph
* git branch -d branch_name
* git branch -D branch_name

### Подробно о командах

*git status* - получить информацию от gitо его текущем состоянии

*git init* - инициализация локального репозитория (**Репозиторий - это хранилище файлов, поддерживающее версионность**)

*git add*- добавить файл или файлы к следующему коммиту

*git commid -m "сообщение*- создание коммита

*git log*- вывод на экран истории всех коммитов с их хэш-кодами

*git checkout*- переход от одного коммита к другому

*git diff*- позволяет увидеть разницу между текущим файлом и закоммиченным файлом

*git branch*- отображает список всех имеющихся веток



## Работас ветками

При работе с ветками используем следующие команды:

* git branch
* git branch branch_name
* git checkout branch_name
* git log --graph
* git branch -d branch_name
* git branch -D branch_name

## Работа с изображениями в Git

Для работы с изображениями в файлах с языком разметки Markdown использовать следующую конструкцию:

![lion.jpg](lion.jpg)

# Добавили скриншот

![screenshot.JPG](screenshot.JPG)

На этом скриншоте изображен конфликт при слиянии веток

В файл  .gitignore это изображение не добавляли т.к. файлы с таким расширением уже добавлены, что говорит о том что эти файлы игнорируются 
