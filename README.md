MalaIB 1.1 based o TinyIB
=================

Преимущества
-------------
-Однофайловость. Полная
-Не нужно прикручивать БД
-Простота настройки
-Кнопка [Открыть форму постинга]
-WebM и SWF
-Простая форма постинга (можно поменять, введите в поиске ``// html.php`` для этого)
-Быстрота и стабильность
-Темный стильчик
-Все другие преимущества TinyIB

Как установить?
-----------------
Открой imgboard.php в текстовом редакторе, можно в консольном (например ``nano``)
Измени ``MALAIB_ADMINPASS`` и ``MALAIB_TRIPSEED`` и некоторые другие настройки по усмотрению
Если не нужно WebM поменяй ``MALAIB_WEBM`` на ``false`` (аналогично с swf)
Создай каталоги ``src/`` ``res/`` ``thumb/`` и ``flatfile/`` и дай им права 777, собственно как и imgboard.php
Запусти imgboard.php в браузере

Если нужно Webm
----------------
Короче, для тогочтобы работал webm, нужен сервер на линуксе и доступ к терминалу, если
у тебя убунту/дебиан, напиши в консоли:
``sudo apt-get install mediainfo ffmpegthumbnailer``
