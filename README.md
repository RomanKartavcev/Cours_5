Программа получает данные о компаниях и вакансиях с сайта hh.ru. Cоздает базу данных и таблицы в PostgreSQL и загружает полученные данные в созданные таблицы. Поиск вакансий происходит по ключевому слову.

main.py - файл для запуска программы hh_parser.py - класс для работы с сайтом hh.ru db_manager.py - класс для работы с базой данных config.py - функция для получения словаря с данными для подключения к базе данных requirements.txt - список необходимых пакетов для работы с программой

Перед началом работы программы необходимо:

установить виртуальное окружение установить пакеты из файла requirements.txt создать конфигурационный файл database.ini для подключения к базе данных Шаблон для создания конфигурации: [postgresql] host=localhost user=postgres password=****** port=5432