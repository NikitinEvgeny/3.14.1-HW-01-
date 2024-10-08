#### [НАЗАТ](readme.md)
## Краткий справочник git ##


### Команды работы с репозиторием: ###
**git init** — инициализация репозитория;

**git status** — просмотр актуального состояния репозитория git. Эта команда показывает, какие файлы были изменены, какие файлы находятся в индексе, а какие файлы вообще не трекаются гитом;

**git add [file name]** — добавление файла или файлов в индекс, подготовка их для коммита. Если нужно добавить все файлы из директории используется оператор точка — git add .;

**git commit -m “[ message ]"** — создать коммит и указать его описание;

**git log** — просмотреть сделанные коммиты и информацию о них;

**git checkout [commit hash ]** — перейти в нужную версию проекта или коммит по его хешу, который отражается в выводе команды git log

**git cat-file -t [hash git-object]** — посмотреть тип git-объекта по хешу;

**git cat-file -p [hash git-object]** — прочитать содержимое файлов git-объектов по хешу.

### Команды работы с ветками: ### 

**git branch [branch name]** — создать ветку;

**git branch -a —** просмотреть все доступные ветки;

**git branch -m [branch name] [branch name]** — переименовать ветку;

**git checkout [branch name ]** — перейти в другую ветку;

**git branch -b [branch name]** — создать новую ветку и переместиться в неё;

**git branch -d [branch name]** — удалить ветку по имени;

**git merge -m «commit text» [feature branch]** — слить ветки, используя 
стандартную стратегию git-слияния. 

### Команды настройки git: ### 

**git config --global init.defaultBranch [branch name]** — задать название метки по умолчанию;

**git config --global user.name [имя пользователя]** — задать имя пользователя глобально, для всех репозиториев на локальной машине;

**git config --global user.email [электронная почта пользователя]** — задать электронную почту пользователя глобально, для всех репозиториев на локальной машине.