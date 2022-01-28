# Исследование закономерностей успеха компьютерных игр

Из открытых источников взяты исторические данные о продажах видеоигр, оценки пользователей и экспертов, жанры и игровые платформы. Нужно выявить закономерности, определяющие успешные продажи для глобального онлайн-магазина. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

**Предоставленные данные:**
- выборка данных по продажам видеоигр до 2016 года (в том числе жанр, год выпуска, объемы продаж по регионам, рейтинги).

**Этапы работы:**
1. Обзор предоставленных данных.
2. Подготовка данных: исправление ошибок, заполнение пропусков и приведение типов.
3. Исследовательский анализ данных:
    - количество релизов в разные годы;
    - платформы с наибольшими суммарными продажами и распределение по годам;
    - за какой характерный срок появляются новые и исчезают старые платформы?
    - выделение актуального периода для построения прогноза на 2017 год;
    - определение потенциально прибыльных платформ;
    - диаграммы размаха по глобальным продажам игр в разбивке по платформам;
    - влияние на продажи оценок пользователей и критиков;
    - распределение игр по жанрам, определение самых прибыльных жанров.
4. Портрет пользователя по регионам (NA, EU, JP).
    - топ-5 популярных платформ;
    - топ-5 популярных жанров;
    - влияение рейтинга ESRB на продажи в регионе.
5. Проверка гипотез:
    - гипотеза: средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
    - гипотеза: средние пользовательские рейтинги жанров Action и Sports разные.
6. Общий вывод.

**Цель работы:**

Определение потенциально популярных продуктов для планирования рекламных кампаний на 2017 год.

**Используемые библиотеки:**

- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy