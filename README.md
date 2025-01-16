#test
1. git clone [url] - клонирование репозитория на пк
2. git remote -v - проверка, привязан ли репозиторий
3. git remote add [url] - привязка папки к репозиторию

///////////////////////////////////////

1. git status
2. git add [files] или git add . - добавляет файлы в stage
3. git commit -m "coment" - запись
4. git log / git log --oneline - показывает информацию о коммитах
5. git push [rep_link] [branch-name]
   git push origin master <===

///////////////////////////////////////

1. git reset [file] - убирает файл из stage
2. git diff / git diff [file] - показывает изменения в файлах
3. git reset --hard возвращает изменения в файлах

4. .gitignore - скрывает файлы и папки в репозитории (например папку build, node_modules, файлы например .env )
