
# <center> SQL - Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта](#описание-проекта)
2. [Описание данных](#описание-данных)
3. [Зависимости](#используемые-зависимости)
4. [Использование проекта](#использование)
5. [Авторы](#авторы)
6. [Выводы](#выводы)

## Описание проекта

Наш проект состоит из четырёх частей:

**1. Предварительный анализ данных** – в данном разделе был проведен анализ следующих показателей:

* Сколько вакансий есть в базе?
* Сколько работодателей в базе?
* Сколько регионов в базе?
* Сколько сфер деятельности в базе?


**2. Детальный анализ вакансий** — в данном разделе был проведен следующий анализ:

* Сколько вакансий в каждом регионе?
* Средняя зарплата по вакансиям.
* Количество вакансий для типа рабочего графика и типа трудоустройства.
* Количество вакансий по типу требуемого опыта работы.


**3. Анализ работодателей** - в данном разделе был проведен следующий анализ:

* Определен ТОП работодателей по количеству вакансий.
* Определены регионы по количеству работодателей и вакансий в них.
* Для каждого работодателя подсчитано количество регионов, в которых он публикует свои вакансии.
* Подсчитано количество работодателей, у которых не указана сфера деятельности.
* Определены компании, у которых указано четыре сферы деятельности.
* По компании **Яндекс** проведен анализ: сколько вакансий в городах-миллионниках России у данного работодателя.


**4. Предметный анализ** - в данном разделе были исследованы требования работодателей к дата-сайентистам.

* Сколько есть подходящих вакансий для начинающего дата-сайентиста?
* Сколько есть вакансий для DS, в которых в качестве ключевого навыка указан SQL или postgres?
* Насколько популярен Python в требованиях работодателей к DS?
* Сколько ключевых навыков в среднем указывают в вакансиях для DS?
* Какую среднюю зарплату для DS указывают для каждого типа требуемого опыта?


**Данный проект** направлен на демонстрацию применения различных методов обработки данных с помощью SQL запросов.


**О структуре проекта:**


## Описание данных
В этом проекте используются данные о резюме с сайта [HeadHunter](https://hh.ru/).
Данные были заранее обработы SkillFactory и представлены в облачном виде с логином и паролем для подключения к ним.

## Используемые зависимости
* [PostgreSQL](https://www.postgresql.org/)


## Использование
Вся информация о работе представлена в [jupyter-ноутбуке](Project-1.%20Decision.ipynb).


## Авторы

**Зимин Леонид**


## Выводы
