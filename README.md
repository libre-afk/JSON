# JSON


1. Создать внешний репозиторий с названием JSON __git checkout -b JSON__
2. Клонировать репозиторий JSON на локальный компьютер __git clone *git@github.com:libre-afk/JSON.git*__ )
3. Внутри локального JSON создать файл "new.json" __touch new.json__
4. Добавить файл под гит __git add new.json__
5. Закоммитить файл __git commit new.json__
6. Отправить файл на внешний GitHub Репозиторий __git push__
7. Отредактировать содержание файла “new.json” - написать информацию о себе
*(ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. __vim new.json__
8. Отправить изменения на внешний репозиторий __commit -am "Comment" && git push__
9. Создать файл preferences.json __touch prefences.json__
10. В файл preferences.json добавить информацию о своих предпочтениях
*(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) __vim prefences.json__
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON __cat > skills.json__
12. Сделать коммит в одну строку __git add . && git commit -am "comment"__ *(Эта строка будет добавлять все измененные и добавленные файлы в репозиторий)*
13. Отправить сразу 2 файла на внешний репозиторий __git push__
14. На веб интерфейсе создать файл bug_report.json.
В веб-интерфейсе выбираем Add file, создаем его. Файл добавляется в репозиторий
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сохраняем изменения кнопкой commit changes
16. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
Редактируем файл bug_report.json нажав на него ЛКМ и выбрав edit this file
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сохраняем изменения кнопкой commit changes
18. Синхронизировать внешний и локальный репозиторий JSON __git pull__ (*Синхронизируем локальный и внешний репозитории*) (__git diff JSON..origin/JSON__ *посмотреть изменения,которые были внесены на удаленном репозитории)*
