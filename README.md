# Инструкция по работе с Git

1. Создать новую папку home_work_1
2. Созать новые файлы в папке 
* *README.md*
* *index.html*
* *diagram.drawio.png*
3. Инициализировать папку - **git init**
4. Добавить все файлы - **git add .**
5. Внести изменения файлы, а имеено нарисовать блок-схему и написать псевдокод для нахождения максимального числа из трех чисел.
6. Сохранить изменения и добаыить - **git add [file name]**
7. Зафиксировать изменения и добавить комментарии - **git commit -m "коментарий"**
8. Периодически проверять статус проекта - **git status**


## Дополнительные команды

* git branch branch_name - создание новой ветки
* git branch - проверить на какой ветке мы находимся
* git checkout branch_name - перейти на другую ветку
* git log - посмотреть список всех коммитов
* git log --oneline - посмотреть все коммиты в собранном виде

## **Заключение** 

* Создали 4 ветки: first, second, third, develop_branch 
* Организовали конфликт между ветками second и third
* Разрешили конфликт путем ручной правки  

# Дополнения к заданию №3
1. Открыть папку с репозиторием с задания ко второму уроку
2. Создать удаленный репозиторий на сайте
3. С помощью команд "git remote add origin [ссылка на репозиторий]", "git branch -M main" и "git push -u origin main" подружить локальный репозиторий с удаленным
4. Внести изменения в файле 
5. Направить на удаленный репозиторий
6. Сделать скриншот и отправить д\з!