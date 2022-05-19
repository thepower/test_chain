# thepower_test

Тестовый шард для ознакомления и тестирования возможностей [ThePower](https://thepower.io)

## Необходимые компоненты:
* git
* docker-compose

## Установка
Из рабочей директории выполнить:

    git clone https://github.com/giDai7ja/thepower_test.git

## Перейти в папку с проектом:

    cd thepower_test

## Запустить шард:

    docker-compose up -d

После запуска API нод доступно по адресам:

    http://localhost:44001
    http://localhost:44002
    http://localhost:44003

## Остановка шарды
По окончании тестирования остановить шард командой

    docker-compose down


