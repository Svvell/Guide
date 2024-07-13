# Гайд для тебя, товарищ, погрузись со мной в Git
## Гайд создан на основе курса "Основы работы с Git" от Яндекс.Практикум
### Что такое Git? С чем его едят и нафига?
#### Git - это система контроля версий, которая помогает отслеживать изменения в проекте. Короче говоря, это инструмент, благодаря которому ты можешь сохранять свой проект на разных стадиях разработки и переключаться между этими версиями в любой момент, также позволяет пользоваться проектом удалённо <br>

Для работы с Git на Windows нужно установить Git for Windows с официального сайта. Основным инструментом будет консоль Git Bash.

### Основные команды Git Bash:
#### 
``` 
pwd (print working directory) - показать рабочую папку(нынешнюю)
ls (list directory contents) - показать файлы и папки в рабочей папке
ls -a () - показать все файлы и папки, даже скрытые
cd test(change directory) - перейти в папку test(только если она существует в рабочей папке иначе нужно указывать полный путь)
cd ~ - перейти в домашнюю директорию
cd .. - перейти на уровень выше(директорию, которой находится рабочая папка)
cd / - перейти в корневую директорию
touch file - создай файл file в текущей папке
mkdir name (make directory) - создай папку в текущей директории с именем name
cp file test2 (copy) - скопировать файл file в папку test2
mv file test2 (move) - переместить файл file в папку test2
cat file (concatenate and print) - распечатай содержимое файла file
rm file2 (remove) - удали файл file2
rmdir test3 (remove directory) - удали папку test3(только если папка пуста, иначе не сработает)
rm -r test3 - удали папку test3 со всем содержимым
```
### Работа с Git:
####
```
git init - инициализация рабочей папки как репозитория Git
git add file.txt - добавить в содержимое репозитория файл file.txt из рабочей папки, пометить его как файл, за которым нужно следить
git status - вывод информации о состоянии репозитория
git commit -m "first commit" - коммит с сообщением "first commit", то есть загрузка на Git
git log - история коммитов
git push - загрузить коммиты на Git
```