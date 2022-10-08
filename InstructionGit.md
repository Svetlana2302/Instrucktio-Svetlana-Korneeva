# Команды Git #
## 1. Git init ##

Фраза инициализации локального репозитория. Данная команда добавляет созданную папка в отслежтваие git. Это команда с которой начинается рабоат с git.
![тут должна быть картинка](gitinit.png)
## 2. Git status ##
команда используется для получения информации от git о его  состоянии. Подробнее с данной командой можно ознакомиться [в справочнике](https://git-scm.com/docs/git-status).

## 3. Git add ##
Команда, которая добавляет файл или файлы к следующему сохранению. Вы можете проверить есть файлы для сохранения или нет, запросив перед этим команду- git status. 
![картинка add](gitadd.png)
*Красным цветом выделены файлы, которые требуют сохранения.* 
## 4. Git commit -m "message" ## 
Использая эту команду Вы создаете коммит. Тоесть добавляете сохранение с комментарий к нему. ***Комментарий пишеться в кавычках и на английском языке, как правило.***

## 5. Git log ##
Данная команда выводит на экран историю всех коммитов с их хеш-кодами. *В полученной информации можно также увидеть данные человека, который делал изменения*. [Подробнее в справочнике git](https://git-scm.com/docs/git-log)

## 6. Git checkout ##

Команда перехода от одного коммита к другому. 
>You could omit <branch>, in which case the command degenerates to "check out the current branch", which is a glorified no-op with rather expensive side-effects to show only the tracking information, if exists, for the current branch. 
Git checkout -b|-B <new-branch> [<start-point>]
Specifying -b causes a new branch to be created as if git-branch[1] were called and then checked out. In this case you can use the --track or --no-track options, which will be passed to git branch. As a convenience, --track without -b implies branch creation; see the description of --track below.
If -B is given, <new-branch> is created if it doesn’t exist; otherwise, it is reset. This is the transactional equivalent of
## 7. Git checkout master ##
Команду стоит использовать, если Вы хотите вернуться к актуальному состоянию  и продолжить работу. 
## 8. Git diff ##
Сокращенно от difference. Команда, которая позволит узнать разницу между текущим файлом и закоммиченным файлом. 
![скрин примера](gitdiff.png)
