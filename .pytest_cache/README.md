# pytest cache directory #

This directory contains data from the pytest's cache plugin,
which provides the `--lf` and `--ff` options, as well as the `cache` fixture.

**Do not** commit this to version control.

See [the docs](https://docs.pytest.org/en/stable/how-to/cache.html) for more information.
Тесты на проверку создания заказа в Яндекс Самокат с помощью API Яндекс Самокат. Чтобы запустить тесты нужно обновить url на сервере. Выполнила запрос на создание заказа. Сохранила номер трека заказа. Выполнила запрос на получения заказа по треку заказа. Проверила, что код ответа равен 200.

Для запуска тестов должны быть установлены пакеты pytest и requests.
Запуск всех тестов выполянется командой pytest и выбираем файл test_get_order.py#pythonProject4