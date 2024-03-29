# Требования по направлению `Android-разработка`

## Цель
Разработать криптовалютное offline-first приложение для поиска, изучения и просмотра исторических данных курса криптовалют.

## Требования
*   Просмотр информации о конкретной криптовалюте (инструменте)
*   Просмотр графиков курса криптовалюты по отношению к рублю или доллару
*   Добавление инструмента в избранное
*   Поиск криптовалюты по названию и [тикеру](https://currency.com/ru/what-is-ticker)
*   Обеспечить работу всех функций приложения без подключения к интернету на основе полученных ранее данных
*   Возможность попасть на некоторые страницы приложения с помощью скана QR-кода

    Тут могут быть различные варианты реализации:
    *   можно сканировать QR-код в стороннем приложении;
    *   а можно в дополнение к предыдущему встроить сканер в ваше собственное.
    
    Мы [подготовили](qr) несколько QR-кодов в удобном формате.

*   Подписка на уведомления о курсе выбранной криптовалюты в выбранное время дня

    Если у пользователя будет отсутствовать соединение, отправить после его появления.

    Реализация собственных идей, не описанных в задании, поощряется. Но помните о том, что качество в данном случае важнее количества.

## Источники данных
Существует множество открытых API, посвящённых криптовалютным инструментам. Вы можете обращаться за данными в сервис [Coinpaprika API](https://api.coinpaprika.com/#section/Introduction), а можете выбрать любой другой. В поисках вам может помочь [открытый список публичных API](https://github.com/public-apis/public-apis#cryptocurrency).

## Критерии

*   Архитектура

    Важно обратить внимание на архитектуру разработываемого мобильного приложения, т.е. на набор правил кодовой базы, которые обеспечат максимальную [связность](https://ru.wikipedia.org/wiki/Связность_(программирование)) и минимальное [зацепление](https://ru.wikipedia.org/wiki/Зацепление_(программирование)) частей приложения. Важно придерживаться какой-то одной архитектуры приложения, выбор которой стоит обосновать в `README.md` репозитория с кодом.

*   Дизайн

    Используйте существующие гайдлайны дизайн-системы Android-приложений (Material Design). Если Вы решаете пользоваться другой дизайн-системой, она должна быть выверена и оптимизирована под использование на мобильном устройстве, а в `README.md` репозитория должна содержаться ссылка на её документацию.

*   Функциональность

    Ожидается наличие функций, дополняющих представленные в требованиях к выполнению заданий. \
    _**Важно.** Приложение не должно нарушать законодательство РФ, а значит сегодня постараемся обойтись без механизмов купли-продажи и обмена криптовалют._ 

*   Внимание к деталям

    Разработка качественного приложения - это забота и о пользователе, и о разработчике. Первому должно быть очевидно, как пользоваться приложением, а у второго не должно возникнуть вопросов, как поддерживать приложение.
