# Проект парсинга pep
# Спринт 18 - Проект парсинга версий языка Python и PEP.

### Назначение:

-   спарсить данные обо всех документах PEP;
-   сравнить статус на странице PEP со статусом в общем списке;
-   посчитать количество PEP в каждом статусе и общее количество PEP; данные о статусе документа нужно брать со страницы каждого PEP, а не из общей таблицы;
-   сохранить результат в табличном виде в csv-файл.


## Технологии:
- attrs==21.4.0
- beautifulsoup4==4.9.3
- certifi==2021.10.8
- chardet==4.0.0
- charset-normalizer==2.0.12
- flake8==4.0.1
- idna==2.10
- importlib-metadata==4.2.0
- iniconfig==1.1.1
- itsdangerous==2.1.1
- lxml==4.6.3
- mccabe==0.6.1
- packaging==21.3
- pluggy==1.0.0
- prettytable==2.1.0
- py==1.11.0
- pycodestyle==2.8.0
- pyflakes==2.4.0
- pyparsing==3.0.7
- ytest==7.1.0
- requests==2.27.1
- requests-cache==1.0.0
- requests-mock==1.9.3
- six==1.16.0
- soupsieve==2.3.1
- tomli==2.0.1
- tqdm==4.61.0
- typing_extensions==4.1.1
- url-normalize==1.4.3
- urllib3==1.26.8
- wcwidth==0.2.5
- zipp==3.7.0

### Запуск проекта:
- Клонировать репозиторий: https://github.com/Kvot32/bs4_parser_pep
- Cоздать и активировать виртуальное окружение: python3 -m venv env 
- Обнвить pip: python3 -m pip install --upgrade pip
- Установить зависимости: pip install -r requirements.txt
- Перейти в директорию src, прочитать и действовать согласно полученной инструции по команде: python3 main.py -h