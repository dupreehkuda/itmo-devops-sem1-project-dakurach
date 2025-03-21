# Финальный проект 1 семестра

REST API сервис для загрузки и выгрузки данных о ценах.

## Требования к системе

Тестирование проводилось используя версии ПО:
- Ubuntu 24.04
- Posgresql 15
- Go 1.23

## Установка и запуск

Для установки и запуска необходимо чтобы система поддерживала ПО из предыдущего пункта \
Далее необходимо выполнить данные команды:
1. ```git clone https://github.com/dupreehkuda/itmo-devops-sem1-project-dakurach.git```
2. ```cd itmo-devops-sem1-project-dakurach```
3. ```chmod +x ./scripts/prepare.sh ./scripts/run.sh```
4. Далее в зависимости то того создана БД или нет выполнить ```./scripts/prepare.sh ``` если БД создана и если создана, то ```./scripts/prepare.sh not_create_database```. Параметры БД задаются в самом исполняемом файле
5. Для запуска приложения необходимо выполнить команду ```./scripts/run.sh```, предварительно задав параметры подключения к БД в исполняемом файле

## Тестирование

Директория `sample_data` - это пример директории, которая является разархивированной версией файла `sample_data.zip`

Задание выполнено на уровне "простой" \
Для запуска тестов выполнить команды:
1. ```chmod +x ./scripts/tests.sh```
2. ```./scripts/tests.sh```
