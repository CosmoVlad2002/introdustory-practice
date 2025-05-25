# git-notes.md
# Задать имя и адрес электронной почты: git config --global user.name "Тара Ратрей"
# Кэширование учётных данных: git config --global credential.helper cache
# Инициализация репозитория: git init
# Добавление отдельных файлов или всех файлов в область подготовленных файлов: git add somefile.js
# Проверка статуса репозитория: git status
# Внесение изменений однострочным сообщением или через редактор: git commit -m "Your short summary about the commit"
# Просмотр истории коммитов с изменениями: git log -p
# Просмотр заданного коммита: git show 1af17e73721dbe0c40011b82ed4bb1a7dbe3ce29
# Просмотр изменений до коммита: git diff
# Удаление отслеживаемых файлов из текущего рабочего дерева: git rm dirname/somefile.js
# Переименование файлов: git mv dir1/somefile.js dir2
# Отмена подготовленных и неподготовленных изменений: git checkout somefile.js
# Изменение последнего коммита: git commit --amend -m "Updated message for the previous commit"
# Откат последнего коммита: git revert HEAD
# Откат заданного коммита: git revert 1af17e
