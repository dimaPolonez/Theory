# GIT

# Terms
Форк (fork) - Копия репозитория.<br>
Ветка/бранч (branch) - Параллельная версия репозитория.<br>
Мастер (master) - Главная ветка репозитория.<br>
Коммит (commit) - Фиксация изменений при работе с репозиторием.<br>
Пул (pull) - Получение последних изменений с сервера.<br>
Пуш (push) - Передача последних изменений на сервер.<br>
Пулл реквест (pull request) - Запрос на слияние форка с репозиторием.<br>
Мёрдж (merge) - Запрос на слияние ветки с репозиторием.<br>
Код ревью (code review) - проверка кода на соответствие требованиям.<br>

# Commands

git config user.name "loginGithub" //Задаем сразу после установки git<br>
git config user.email "your@email" //Задаем сразу после установки git
help //Получить справку по командам<br>
<br>
git clone linksGithubRepository //Копирует репозиторий в папку локального проекта<br>
<br>
cd name_folders //Переход в папку<br>
ls //Показывает содержимое локальной папки<br>
touch *.* //Создать файл в локальной папке<br>
mkdir name //Создать папку в локальной папке<br>
<br>
git status //Показывать состояние объектов в локальной папке<br>
git add . //Проиндексировать все файлы в папке<br>
<br>
git commit -m 'name_commit' //Создать коммит<br>
git reset HEAD //Отменить последний коммит<br>
<br>
git checkout -b nameBranch //Создать новую ветку<br>
<br>
git push origin nameBranch //Отправляем изменения на сервер *После push ставим -u, если находимся в другой ветке<br>
<br>
git pull origin master //Забираем все папки и ветки с изменениями с сервера<br>
git pull -f //Восстанавливает все связи с сервером<br>

# Usefull links 

<h3><a href = "https://uleming.github.io/gitbook/index.html">Хорошие материалы от Git-комьюнити в виде документации:</a></h3>

<h3><a href = "https://www.evernote.com/shard/s368/client/snv?noteGuid=b1359883-2b9e-419a-b9de-dd959fc05f05&noteKey=97c0f19486d851b3&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs368%2Fsh%2Fb1359883-2b9e-419a-b9de-dd959fc05f05%2F97c0f19486d851b3&title=Git">Конспект по Git</a></h3>

<h3><a href = "https://docs.rs.school/#/git-convention">Требования к именам коммитов</a></h3>
