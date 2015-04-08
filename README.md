MalaIB 1.1 based o TinyIB
=================

Преимущества
-------------
-Однофайловость. Полная<br />
-Не нужно прикручивать БД<br />
-Простота настройки<br />
-Кнопка [Открыть форму постинга]<br />
-WebM и SWF<br />
-Простая форма постинга (можно поменять, введите в поиске ``// html.php`` для этого)<br />
-Быстрота и стабильность<br />
-Темный стильчик<br />
-Все другие преимущества TinyIB<br />

Как установить?
-----------------
Открой imgboard.php в текстовом редакторе, можно в консольном (например ``nano``)<br />
Измени ``MALAIB_ADMINPASS`` и ``MALAIB_TRIPSEED`` и некоторые другие настройки по усмотрению<br />
Если не нужно WebM поменяй ``MALAIB_WEBM`` на ``false`` (аналогично с swf)<br />
Создай каталоги ``src/`` ``res/`` ``thumb/`` и ``flatfile/`` и дай им права 777, собственно как и imgboard.php<br />
Запусти imgboard.php в браузере<br />

Если нужно Webm
----------------
Короче, для тогочтобы работал webm, нужен сервер на линуксе и доступ к терминалу, если
у тебя убунту/дебиан, напиши в консоли:<br />
``sudo apt-get install mediainfo ffmpegthumbnailer``
