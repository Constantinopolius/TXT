# Homework GitHub_TXT
1. Создать внешний репозиторий c названием TXT.
Заходим на свой аккаунт на GitHub выбираем вкладку Repositories 
Нажимаем кнопку New в окне Repository name вводим имя репозитория
скролим вниз страницы и нажимаем кнопку Creat repository
 
2. Клонировать репозиторий TXT на локальный компьютер.
git clone и вставляем ссылку скопированую во внешнем репозитории
 
3. Внутри локального TXT создать файл “new.txt”.
cd .. ваходим из папки XML 
touch new.txt
 
4. Добавить файл под гит.
git add new.txt
 
5. Закоммитить файл.
git commit -m "add file new.txt"
 
6. Отправить файл на внешний GitHub репозиторий.
git push
 
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
vim new.txt или statrt new.txt (команда start запускает файл в формате .txt в NotePad или в любом другом редакторе который стоит по умолчанию)
Ф.И.О: Соловей Константин Сергеевич 
Возраст: 32 
Количество домашних животных: Восьмилетний британский кот по кличке Бэкингем 
Желаемая будущая зароботная плата 2500$ 
После внесения изменений нажимаем "ESC" для выхода в "командный режим", вводим ":" (двоеточие), вводим "wq" (write-quit) - для сохранения изменений и выхода; "q!" - для выхода без сохранения, и нажимаем "Enter".
Если измения вносились через Notepad нажимаем крестик и ок 
 
 8. Отправить изменения на внешний репозиторий.
 git add .
 git commit -m "add file"
 git push 
 
9. Создать файл preferences.txt
 touch preferences.txt

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
vim или statrt preferences.txt (команда start запускает файл в формате .txt в NotePad или в любом другом редакторе который стоит по умолчанию)
После внесения изменений нажимаем "ESC" для выхода в "командный режим", вводим ":" (двоеточие), вводим "wq" (write-quit) - для сохранения изменений и выхода; "q!" - для выхода без сохранения, и нажимаем "Enter".
Если измения вносились через Notepad нажимаем крестик и ок 

11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 touch skills.txt
 vim skills.txt

12. Сделать коммит в одну строку.
git commit -am "add two files"

13. Отправить сразу 2 файла на внешний репозиторий.
 git push

14. На веб интерфейсе создать файл bug_report.txt.
 
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
18. Синхронизировать внешний и локальный репозиторий TXT
