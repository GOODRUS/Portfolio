# Портфолио "Тестировщик ПО" #

В портфолио представлен [дипломный проект](https://github.com/GOODRUS/diplom2023) выполненный по завершению курса “Тестировщик ПО” Нетологии.

Основной [задачей](https://github.com/GOODRUS/diplom2023/blob/main/docs/Task.md#задача) проекта является автоматизация позитивных и негативных сценариев веб-сервиса по покупке тура, где оплата тура возможна по дебетовой карте или в кредит. Также необходимо проверка работы приложения с СУБД: [SQL и PostgreSQL](https://github.com/GOODRUS/diplom2023/blob/main/docs/Task.md#субд).

На [этапе планирования](https://github.com/GOODRUS/diplom2023/blob/main/docs/Plan.md) было разработаны 88 [тестовых сценариев](https://github.com/GOODRUS/diplom2023/blob/main/docs/Plan.md#перечень-автоматизируемых-сценариев), из которых 72 относятся к [UI-тестированию](https://github.com/GOODRUS/diplom2023/blob/main/docs/Plan.md#frontend-сценарии#L3) и 16 к [API-тестированию](https://github.com/GOODRUS/diplom2023/blob/main/docs/Plan.md#backend-сценарии).

Для достижения результатов поставленной задачи были использованы [инструменты:](https://github.com/GOODRUS/diplom2023/blob/main/docs/Plan.md#перечень-используемых-инструментов-с-обоснованием-выбора) _IntelliJ IDEA, Selenide, JUnit5, JUnit Jupiter, Allure, Lombok, REST Assured, JavaFaker, DBUtils, Gson_.

В процессе работы над проектом:
- была настроена SUT;
- проверена возможность подключения к заявленным в задании СУБД;
- реализована система [page objects](https://github.com/GOODRUS/diplom2023/tree/main/src/test/java/ru/netology/page) для взаимодействия с элементами веб-сервиса;
- реализована система [Data-helpers](https://github.com/GOODRUS/diplom2023/tree/main/src/test/java/ru/netology/data) для управления тестовыми данными;
- проведена автоматизация [Backend](https://github.com/GOODRUS/diplom2023/tree/main/src/test/java/ru/netology/test/Backend) и [Frontend](https://github.com/GOODRUS/diplom2023/tree/main/src/test/java/ru/netology/test/Frontend) сценариев;
- настроена непрерывная интеграция([CI](https://ci.appveyor.com/project/GOODRUS/diplom2023)) с возможностью запуска авто-тестов в БД SQL и PostgreSQL;
- сформирован отчёт с использование [Allure report](https://github.com/GOODRUS/diplom2023/blob/main/docs/Report.md#отчёт-по-итогам-тестирования);
- заведены 15 [баг-репорта](https://github.com/GOODRUS/diplom2023/issues) по найденным дефектам. 
