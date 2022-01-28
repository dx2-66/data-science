# Определение перспективного тарифа для телеком-компании

Оператор сотовой связи предлагает клиентам два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать маркетинговый бюджет, коммерческому департаменту нужно выяснить, какой тариф приносит больше дохода.

Нам предстоит провести предварительный анализ тарифов на небольшой выборке. В нашем распоряжении данные 500 пользователей: кто они, откуда, каким тарифом пользуются, какими услугами оператора поьзовались в 2018 году. Нужно изучить поведение клиентов и прийти к выводу — какой из тарифов лучше.

**Предоставленные данные:**
- выборка данных по звонкам, интернет-трафику и сообщениям за 2018 год;
- информация о тарифах;
- информация о пользователях, участвующих в выборке.

**Этапы работы:**
1. Обзор предоставленных данных.
2. Подготовка данных: исправление ошибок и приведение типов.
3. Расчетная часть: для каждого пользователя должны быть вычислены
    - количество сделанных звонков и израсходованных минут разговора по месяцам;
    - количество отправленных сообщений по месяцам;
    - объем израсходованного интернет-трафика по месяцам;
    - помесячная выручка.
4. Аналитическая часть: анализ поведения клиентов оператора, исходя из выборки.
    - Сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц?
    - Расчет среднего, дисперсии и стандартного отклонения. Построение гистограмм и описание распределения.
5. Проверка гипотез:
    - гипотеза: средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются;
    - гипотеза: средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.
6. Общий вывод.

**Цель работы:**

Определение более доходного тарифа для корректировки рекламного бюджета оператора.

**Описание тарифов:**

**Тариф «Смарт»:**

Ежемесячная плата: 550 рублей
Включено 500 минут разговора, 50 сообщений и 15 Гб интернет-трафика
Стоимость услуг сверх тарифного пакета: 1. минута разговора: 3 рубля («Мегалайн» всегда округляет вверх значения минут и мегабайтов. Если пользователь проговорил всего 1 секунду, в тарифе засчитывается целая минута); 2. сообщение: 3 рубля; 3. 1 Гб интернет-трафика: 200 рублей.

**Тариф «Ультра»:**

Ежемесячная плата: 1950 рублей
Включено 3000 минут разговора, 1000 сообщений и 30 Гб интернет-трафика
Стоимость услуг сверх тарифного пакета: 1. минута разговора: 1 рубль; 2. сообщение: 1 рубль; 3. 1 Гб интернет-трафика: 150 рублей.

**Используемые библиотеки:**

- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy