
![](./images/data_cleaning.png)
# <center> Проект: Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Исследование данных](#Исследование-данных)
3. [Преобразование данных](#Преобразование-данных)
4. [Исследование зависимостей в данных](#Использование-зависимостей-в-данных)
5. [Очиства данных](#Очистка-данных)
6. [Выводы](Использование-проекта)

## Описание проекта

> В ходе работы над проектом с помощью инструментов библиотеки pandas будет проведен анализ данных, полученных с сайта  поиска вакансий hh.ru. 

Основные этапы работы над проктом:
* Исследование данных.
* Преобразование данных.
* Исследование зависимостей в данных.
* Очистка данных.
* Выводы.


**Цель проекта** — избавиться от «мусора», подготовить данные для построения модели, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.



**О структуре проекта:**
* [images](./images) - папка с изображениями, содержит материалы визуальзации решения заданий проекта
* [Project_HeadHunter.ipynb](./Project_HeadHunter.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором решения задач по анализу данных


## Описание данных
В этом проекте используется база резюме, полученных с сайта поиска вакансий hh.ru.

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, как вы знаете, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить.

Исходный датасет представляет собой набор данных из таблицы, в которой содержатся 12 признаков из резюме соискателей.
Кроме того, имеются данные о курсах валют, также представленные в виде таблицы.

Для упрощения демонстрации техники очистки данных мы будем отрабатывать на урезанном датасете. Он содержит информацию о 61 признаке, описывающих жилье. Файл с данными можно найти [здесь](./data/sber_data.csv).

## Используемые зависимости
* Python (3.9):
    * [numpy (1.20.3)](https://numpy.org)
    * [pandas (1.3.4)](https://pandas.pydata.org)
    * [matplotlib (3.4.3)](https://matplotlib.org)
    * [seaborn (0.11.2)](https://seaborn.pydata.org)

## Установка проекта

```
git clone https://github.com/SkillfactoryDS/DataCleaningProject
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке data_cleaning_example.ipynb.

## Авторы

* [Укажите свое имя](ссылка на ваши соц сети)

## Выводы

Допишите выводы по проделанной работе.