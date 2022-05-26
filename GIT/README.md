# GIT

# Terms
Форк (fork) - Копия репозитория.
Ветка/бранч (branch) - Параллельная версия репозитория.
Мастер (master) - Главная ветка репозитория.
Коммит (commit) - Фиксация изменений при работе с репозиторием.
Пул (pull) - Получение последних изменений с сервера.
Пуш (push) - Передача последних изменений на сервер.
Пулл реквест (pull request) - Запрос на слияние форка с репозиторием.
Мёрдж (merge) - Запрос на слияние ветки с репозиторием.
Код ревью (code review) - проверка кода на соответствие требованиям.

# Commands

git config user.name "loginGithub" //Задаем сразу после установки git
git config user.email "your@email" //Задаем сразу после установки git
help //Получить справку по командам

git clone linksGithubRepository //Копирует репозиторий в папку локального проекта

cd name_folders //Переход в папку
ls //Показывает содержимое локальной папки
touch *.* //Создать файл в локальной папке
mkdir name //Создать папку в локальной папке

git status //Показыват состояние объектов в локальной папке
git add . //Проиндексировать все файлы в папке

git commit -m 'name_commit' //Создать коммит
git reset HEAD //Отменить последний коммит

git checkout -b nameBranch //Создать новую ветку

git push origin nameBranch //Отправляем изменения на сервер *После push ставим -u, если находимся в другой ветке

git pull origin master //Забираем все папки и ветки с изменениями с сервера
git pull -f //Восстанавливает все связи с сервером

# Usefull links 

<h3 href = "https://uleming.github.io/gitbook/index.html">Хорошие материалы от Git-комьюнити в виде документации:</h3>

<h3 href = "https://www.evernote.com/shard/s368/client/snv?noteGuid=b1359883-2b9e-419a-b9de-dd959fc05f05&noteKey=97c0f19486d851b3&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs368%2Fsh%2Fb1359883-2b9e-419a-b9de-dd959fc05f05%2F97c0f19486d851b3&title=Git">Конспект по Git</h3>

<h3 href = "https://docs.rs.school/#/git-convention">Требования к именам коммитов</h3>
