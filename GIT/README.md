# GIT

# Terms
<ul>
    <li>Форк (fork) - Копия репозитория</li>
    <li>Ветка/бранч (branch) - Параллельная версия репозитория</li>
    <li>Мастер (master) - Главная ветка репозитория</li>
    <li>Коммит (commit) - Фиксация изменений при работе с репозиторием</li>
    <li>Пул (pull) - Получение последних изменений с сервера</li>
    <li>Пуш (push) - Передача последних изменений на сервер</li>
    <li>Пулл реквест (pull request) - Запрос на слияние форка с репозиторием.</li>
    <li>Мёрдж (merge) - Запрос на слияние ветки с репозиторием.</li>
    <li>Код ревью (code review) - проверка кода на соответствие требованиям.</li>
</ul>

# Commands
<ul>
    <li>git config user.name "loginGithub"  //Задаем сразу после установки git</li>
    <li>git config user.email "your@email" //Задаем сразу после установки git</li>
</ul>
<ul>
    <li>git help //Получить справку по командам</li>
    <li>git clone linksGithubRepository //Копирует репозиторий в папку локального проекта</li>
</ul>
<ul>    
    <li>cd name_folders //Переход в папку</li>
    <li>ls //Показывает содержимое локальной папки</li>
    <li>mkdir name //Создать папку в локальной папке</li>
    <li>touch name //Создать файл в локальной папке</li>
</ul>
<ul>    
    <li>git status //Показывать состояние объектов в локальной папке</li>
    <li>git add . //Проиндексировать все файлы в папке</li>
</ul>
<ul>    
    <li>git commit -m 'name_commit' //Создать коммит</li>
    <li>git reset HEAD //Отменить последний коммит</li>
</ul>
<ul>    
    <li>git checkout -b nameBranch //Создать новую ветку</li>
    <li>git push origin nameBranch //Отправляем изменения на сервер *После push ставим -u, если находимся в другой ветке</li>
</ul>
<ul>    
    <li>git pull origin master //Забираем все папки и ветки с изменениями с сервера</li>
    <li>git pull -f //Восстанавливает все связи с сервером</li>
</ul>
 
# Usefull links 
<ul>    
    <li><h3><a href = "https://uleming.github.io/gitbook/index.html">Хорошие материалы от Git-комьюнити в виде документации:</a></h3></li>
    <li><h3><a href = "https://www.evernote.com/shard/s368/client/snv?noteGuid=b1359883-2b9e-419a-b9de-dd959fc05f05&noteKey=97c0f19486d851b3&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs368%2Fsh%2Fb1359883-2b9e-419a-b9de-dd959fc05f05%2F97c0f19486d851b3&title=Git">Конспект по Git</a></h3></li>
    <li><h3><a href = "https://docs.rs.school/#/git-convention">Требования к именам коммитов</a></h3></li>
</ul>
