# Command

Ссылки кликабельные!<br>
<a href = "#osn">Основные теги</a><br>
<a href = "#meta">Метатеги</a><br>
<a href = "#txt">Текстовые теги</a><br>
<a href = "#spis">Теги списков</a><br>
<a href = "#atrib">Атрибуты тегов</a><br>
<a href = "#table">Теги таблиц</a><br>
<a href = "#mnemonik">Мнемоники</a><br>
<a href = "#ssilki">Ссылки</a><br>
<a href = "#image">Картинки</a><br>
<a href = "#media">Медиа</a><br>
<a href = "#form">Формы</a><br>
<a href = "#seman">Семантические теги</a><br>
<a href = "#all">Все остальные</a><br>

### Основные <ul id = "osn">
<li> < !DOCTYPE html> Первая строка, показывает браузеру что страница размечена по стандарту HTML5</li>
<li> < html lang="ru"> Всё что находится внутри этих тегов, является веб-страницей формата HTML. Атрибут lang указывает на каком языке написана веб-страница, так как в каждом языке есть свои нюансы при отображении текста < /html></li>
<li>< head> Обьявляется после предыдущего тега html. Содержит метоинформацию о сайте, а также служит для ее описания и подключения стилей и скриптов < /head></li>
<li>< body> Обьявляется после head. Основное тело любой страницы, всё что находится в это разделе будет выведено в браузер< /body></li>
</ul>

### Метатеги <ul id = "meta">
<li> < title> Здесь мы указываем название страницы которую создаем. Рекомендуемый размер 50-80 символов < /title></li>
<li> < meta charset="utf-8"> Указывает кодировку страницы </li>
<li> < meta name="description" content="Описание контента"> Информация которая отображается в поиске, под ссылкой на сайт и title </li>
<li> < meta name="keywords" content="ключевые слова"> Указывает ключевые слова, содержащиеся на странице. Тем самым помогая роботам корректнее индексировать сайт </li>
<li> < meta name = "viewport"> позволяет указывать параметры отображения сайта на разных устройствах, в разделе content через запятую<br>
     < meta name = "viewport" content = "width=800"> фиксированная ширина<br> 
     < meta name = "viewport" content = "width = device-width"> по ширине устройства<br>
     < meta name = "viewport" content = "height=800"> фиксированная высота<br>
     < meta name = "viewport" content = "height = device-height"> по высоте устройства<br> 
     < meta name = "viewport" content = "initial-scale"> эффект масштабирования от 0.1 до 10<br>
     < meta name = "viewport" content = "user-scalable"> указывает может ли пользователь масштабировать страницу, с помощью жестов, yes или no</li>
<li>< link rel = "icon" href = "/favicon.png" type="image/png" sizes="64x64"> добавить на страницу favicon</li>
<li>< link rel = "stylesheet" href = "style.css"> подключает таблицу стилей к файлу HTML</li>
</ul>

### Текст <ul id = "txt">
<li>< p> Параграф < /p></li>
<li>< b> Делает текст жирным, используют для визуального выделения < /b><br>
< strong> Делает текст жирным, используют для смыслового выделения < /strong></li>
<li>< i> Делает текст курсивным, используют для визуального выделения < /i><br>
< em> Делает текст курсивным, используют для смыслового выделения < /em></li>
<li>< h1, h2, h3, h4, h5, h6> Заголовки разных уровней < /h1, h2, h3, h4, h5, h6></li>
<li>< pre> Выводит внутри себя текст с сохранением всех пробельных символов < /pre></li>
<li> < code> Позволяет вставлять код в HTML < /code></li>
<li> < abbr> Показывает аббривиатуру < /abbr></li>
<li> < blockquote> - Выделяет текст как цитату. Блочный</li>
<li> < q> - Выделяет текст как цитату. Строчный</li>
<li> < br> - Перенос текста на новую строку</li>
<li> < code> - Представляет фрагмент кода</li>
<li> < del> < s> - Перечеркивает текст</li>
<li> < ins> - Выделяет текст подчёркиванием</li>
<li> < mark> - HTML5. Выделяет фрагменты текста жёлтым фоном</li>
<li> < sub> - Подстрочное написание</li>
<li> < sup> - Надстрочное написание</li>
</ul>

### Списки <ul id = "spis"> 
<li>< ul><br>
< li> маркированый список < /li><br>
< /ul></li>
<li>< ol reversed> можно сделать реверс<br>
< li value="1"> нумерованый список, можно настроить с помощью value в обратном порядке< /li><br>
< /ol></li>
</ul>
<li>< dl> Список описаний<br>
< dt> Первый термин< /dt><br>
     < dd> Описание первого термина< /dd><br>
< dt> Второй термин< /dt><br>
     < dd> Описание второго термина< /dd><br>
< /dl></li>
</ul>

### Атрибуты <ul id = "atrib">
<li> атрибут title = "Всплывающая подсказка" </li>
<li> атрибут class = "Задает класс элемента" </li>
</ul>

### Таблицы <ul id = "table">
<li>< table> Область таблицы < /table></li>
<li>< caption> Заголовок таблицы, всегда после < table> < /caption></li>
<li>< tr> Строка таблицы < /tr></li>
<li>< thead> Шапка таблицы < /thead></li>
<li>< th> Ячейка шапки < /th></li>
<li>< tbody> Тело таблицы, если не указать тег добавиться автоматически < /tbody</li>
<li>< td> Ячейка таблицы < /td></li>
<li> td атрибут colspan = "Обьединяет n количество ячеек справа по горизонтали" //удаляем лишние ячейки из строки </li>
<li> td атрибут rowspan = "Обьединяет n количество ячеек справа по вертикали" //удаляем лишние ячейки из соседних строк </li>
</ul>

### Топографические мнемоники <ul id = "mnemonik">
<li>& nbsp; Неразрывный пробел</li>
<li>& laquo; и & raquo; Ковычки << елочки >></li>
<li>& mdash; Длинное тире</li>
<li>& lt; и & gt; Скобки тегов</li>
<li><a href = "https://ru.wikipedia.org/wiki/%D0%9C%D0%BD%D0%B5%D0%BC%D0%BE%D0%BD%D0%B8%D0%BA%D0%B8_%D0%B2_HTML" target = "_blank">Мнемоники в HTML Wiki</a></li>
</ul>

### Ссылки <ul id = "ssilki">
<li>< a href = "/vnutri/doc"> к ссылке внутри сайта < /a></li>
<li>< a href = "https://github.com/dimaPolonez/Theory"> на другой сайт < /a></li>
<li>< a href = "#ssilki"> к якорю в документе < /a></li>
<li>< a href = "Ссылка" target = "_blank"> открыть сайт в новой вкладке < /a></li>
<li>< a href = "Ссылка.doc" target = "_blank" download> Скачать файл < /a></li>
</ul>

### Картинки <ul id = "image">
<li>< img src = "https://github.com/dimaPolonez/Theory.jpg" alt = "является обязательным"> Ссыль на картинку в интернете </li>
<li>< img src = "project/html/main.jpg" alt = ""> Ссыль на картинку в папке </li>
<li>< img src = "ссылка" alt = "Текстовая информация о картинке"> атрибут alt если картинка не загрузилась </li>
<li>< img src = "ссылка" alt = "чего то там" width = "200" height = "100"> устанавливаем размер картинки для отображения на сайте, размер оригинальной картинки при этом не меняется </li>
</ul>

### Аудио <ul id = "media">
<li>< audio src="путь_к_аудио-файлу" controls> реализует воспроизведение песни на сайте, в данном случае если песня одна, в атрибут controls в зависимости от браузера, можно добавить интерфейс плеера< /audio></li>
<li>< audio controls><br>
< source src = "https://example.com/audio.mp3"><br>
< source src = "https://example.com/audio.ogg"><br>
< /audio> если песен много, нужно указывать таким образом. Также если будем указывать другие форматы, одинаковых песен, браузер сможет выбрать ту что поддерживается</li>
</ul>

### Видео <ul>
<li>< video src = "путь_к_видео-файлу" controls>
 реализует воспроизведение видео на сайте, в данном случае если видео одно, в атрибут controls в зависимости от браузера, можно добавить интерфейс плеера</ video></li>
<li>< video width = "500" height = "500" autoplay="autoplay" controls><br>
< source src = "https://example.com/our-video.mp4" type = "video/mp4"><br>
< source src = "https://example.com/our-video.webm" type = "video/webm"><br>
< source src = "https://example.com/our-video.ogg" type = "video/ogg"><br>
< /video> если видосов много, нужно указывать таким образом. Также если будем указывать другие форматы, одинаковых видосов, браузер сможет выбрать тот что поддерживается, атрибут type является обязательным. Атрибуты width и height указывают размер видео. Атрибут autoplay по умолчанию отключен, если мы его задаем, то видео запуститься автоматически сразу после загрузки страницы</li>
</ul>

### Формы <ul id = "form">
<li>< form action="/search"> форма, данные из которой уйдут на страницу search, если action не указан, то данные уйдут на ту же самую страницу с которой вызывается form < /form></li>
<li>< form><br>
< label for="name"> Здесь можно описать назначение поля формы. for позволяет связаться с полем input. Или можно использовать вложенность</ label><br>
< input type="text" id="name" placeholder="Какой то текст"> id помогает связаться с полем label. placeholder выводит внутри поля информацию в каком формате надо его заполнять<br>
< input type="text"> Текстовое поле.<a href="https://webref.ru/course/html5-form/text">По атрибутам</a><br>
< input type="button"> Кнопка.<a href="https://webref.ru/course/html5-form/button">По атрибутам</a><br>
< input type="checkbox" name="Группа с ответами" value="Вариант ответа"> Флажки, для выбора нескольких вариантов.<a href="https://webref.ru/course/html5-form/checkbox">По атрибутам</a><br>
< input type="image"> Поле с рисунком<br>
< input type="file"> Поле для загрузки файлов. <a href="https://webref.ru/course/html5-form/file">По атрибутам</a><br>
< input type="password"> Поле для ввода пароля, со звездочками.<a href="https://webref.ru/course/html5-form/password">По атрибутам</a><br>
< input type="radio" name="Группа" value="Вариант ответа"> Переключатели, для выбора одного варианта. <a href="https://webref.ru/course/html5-form/radio">По атрибутам</a><br>
< input type="reset"> Поле для обнулениях данных в форме<br>
< input type="hiden"> Скрытое поле<br>
< input type="submit"> Поле для отправки данных на сервер<br>
< input type="number"> HTML5. Поле для ввода чисел<br>
< input type="search"> HTML5. Поле для поиска<br>
< input type="url"> HTML5. Поле для веб-адресов<br>
< input type="email"> HTML5. Поле для адресов электронной почты<br>
< input type="tel"> HTML5. Поле для телефонных номеров<br>
< /form></li>
<li>< textarea rows="4" cols="40"> Элемент который позволяет пользователю вводить несколько строк текста. <a href="https://webref.ru/course/html5-form/textarea">По атрибутам</a>< /textarea></li>
<li>< form><br>
< select><a href="https://webref.ru/course/html5-form/select">По атрибутам</a><br>
< option disabled> Закрепить заголовок выпадающего списка и заблокировать его для выбора< /option><br>
< option>Пункт 1</ option><br>
< option>Пункт 2</ option><br>
< option>Пункт 3</ option><br>
< /select><br>
< select multiple> Создаем выпадающий список с множественным выбором<br>
< option>Пункт 1</ option><br>
< option>Пункт 2</ option><br>
< option>Пункт 3</ option><br>
< /select><br>
< /form>
</li>
<li>< button> Используется для добавления кнопки< /button></li>
</ul>

### Семантические теги <ul id="seman">
<li>< article> Самостоятельная часть страницы, для независимого использования (статья, запись). Может существовать отдельно от контекста. Внутри себя должен содержать заголовок< /article></li>
<li>< aside> Часть документа, содержмое которого косвенно связано с основным содержимым (боковая панель, сноска, метка). Пишеться вне тега main, но если надо на каждой странице сделать уникальную боковую панель(дополняющая область), то запихиваем в main< /aside></li>
<li>< footer> Нижний колонтитул документа< /footer></li>
<li>< header> Верхний колонтитул документа. Не уникальный< /header></li>
<li>< main> Предназначен для основного контента. Уникальный.< /main></li>
<li>< nav> Отдельная секция документа, для навигации. В основном используется для разметки основного меню. Не уникальный< /nav></li>
<li>< section> Автономный раздел, как правило с заголовком. Дополняет основной контент, не может существовать отдельно от контекста< /section></li>
</ul>

### Все остальные <ul id="all">
<li> < !--  Комментарий -- ></li>
<li> < div> - Блочный элемент контейнер< /div></li>
<li> < span> - Контейнер для строчных элементов< /span></li>
<li> < hr> - Горизонтальная линия</li>
<li> < iframe> - Создает встроенный фрейм, в который можно загружать другой HTML документ< /iframe></li>
<li> < output> - Поле для вывода результатов вычислений</li>
<li> < progress> - HTML5. Индикатор выполнения любого рода задач</li>
</ul>

