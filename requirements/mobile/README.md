# Требования по направлению `Android-разработка`

## Цель
Разработать приложение для взаимодействия с LLM-моделью через API, включая поддержку шаблонов RAG (Retrieval-Augmented Generation) для удобства пользователей.

## Описание
Пользователи приложения смогут взаимодействовать с LLM-моделью, отправляя запросы с контекстом, используя предустановленные шаблоны RAG. Шаблоны позволяют задавать параметры, такие как роль, цель и окружение, чтобы улучшить качество ответов модели. Приложение должно быть удобным, функциональным и поддерживать работу как онлайн, так и оффлайн.

# Функционал
* Отправка запросов к LLM-модели с возможностью ввода текста.
* Использование шаблонов RAG для автоматического заполнения контекста (роль, цель, окружение).
* Возможность создавать, редактировать и удалять шаблоны RAG.
* Просмотр истории запросов и ответов.
* Поиск по истории запросов по ключевым словам или параметрам.
* Сортировка истории запросов по дате, популярности или другим критериям.
* Уведомление пользователя зайти в приложение, чтобы спросить LLM (аля duolingo) 
* Сохранение избранных запросов и шаблонов для быстрого доступа.
* Работа с историей запросов в оффлайн-режиме (кэширование данных).

Реализация дополнительных идей, не описанных в задании, приветствуется, но важно соблюдать баланс между функциональностью и качеством реализации.

## Источники данных
Для взаимодействия с LLM-моделью используется API сервиса. Документация API доступна по ссылке: [API Documentation](http://94.126.205.209:8000/docs).

## Критерии

### Архитектура
При разработке приложения важно придерживаться выбранной архитектуры (например, MVVM, MVI или Clean Architecture), которая обеспечивает высокую связность и низкое зацепление компонентов. Выбор архитектуры должен быть обоснован в README.md репозитория.

### Дизайн
Используйте современные дизайн-системы, такие как Material Design, для создания интуитивно понятного и эстетичного интерфейса. Если вы решите использовать другую дизайн-систему, убедитесь, что она оптимизирована для мобильных устройств, и укажите ссылку на её документацию в README.md.

### Функциональность
Приложение должно включать все заявленные функции, а также может быть дополнено полезными фичами, улучшающими пользовательский опыт. Например:
* Экспорт истории запросов в файл.
* Передача шаблона через соц сети. 
* Поддержка нескольких языков интерфейса.
* Ввод запроса голосом. 

### Внимание к деталям
Уделите внимание качеству реализации: плавность анимаций, обработка ошибок, корректная работа в оффлайн-режиме, оптимизация производительности. Пользовательский опыт должен быть приоритетом.