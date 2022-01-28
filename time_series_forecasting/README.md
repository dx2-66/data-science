#  Прогнозирование заказов такси

Такси-агрегатор собрал исторические данные о заказах такси в аэропортах. Чтобы эффективно распланировать график водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Наша задача - построить модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке не должно превышать 48.

**Предоставленные данные:**

- Исторические данные о заказах такси в аэропортах.

**Этапы работы:**

1. Обзор и подготовка данных, ресемплирование по периоду 1 ч.
2. Анализ временного ряда.
3. Выделение тестовой выборки в размере 10% от датасета.
3. Обучение моделей с различными гиперпараметрами.
4. Проверка моделей на тестовой выборке (целевая метрика RMSE).
5. Общий вывод.

**Цель работы**

Построение модели машинного обучения, способной спрогнозировать количество заказов такси на следующий час исходя из исторических данных.

**Используемые библиотеки:**

- Pandas
- Scikit-learn
- statsmodels
- XGBoost
- Plotly