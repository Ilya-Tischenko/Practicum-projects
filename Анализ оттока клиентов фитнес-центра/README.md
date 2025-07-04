# Анализ оттока клиентов фитнес-центра
[Jupyter тетрадь](https://github.com/Ilya-Tischenko/Projects/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D1%84%D0%B8%D1%82%D0%BD%D0%B5%D1%81-%D1%86%D0%B5%D0%BD%D1%82%D1%80%D0%B0/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D1%84%D0%B8%D1%82%D0%BD%D0%B5%D1%81-%D1%86%D0%B5%D0%BD%D1%82%D1%80%D0%B0.ipynb)

Фитнес-центр разрабатывает стратегию удержания клиентов. Очень часто клиенты перестают пользоваться услугами центра без очевидных признаков, например, по закрытию договора. Руководству организации нужно разработать модель для прогноза оттока клиентов по неочевидным признакам.

**Цель исследования:** провести анализ и кластеризацию клиентов, подготовить план действия по их удержанию.

**План исследования:**
1. Импорт библиотек и загрузка данных
2. Исследовательский анализ данных
3. Обучение модели прогнозирования оттока клиентов
4. Кластеризация клиентов
5. Выводы и рекомендации

## Выводы и рекоммендации
Для прогноза оттока были обучены 2 модели, которые показали высокий уровень метрик accuracy и precision.
Была проведена кластеризация клиентов с помощью иерархической кластеризации и алгоритмом K-Means.

Рекомендации: увеличить количество компаний-партнеров клуба (т.к. кластер с самым высоким уровнем оттока имел низкую долю клиентов, работающих с партнерами), разработка выгодных долгосрочных абонементов (т.к. клиенты часто не продлевают свой одномесячный абонемент), сделать выгодные предложения для молодых клиентов (например, скидка по студенческому билету), распространение промо-кодов акции "Приведи друга" (т.к. кластер 0 с низкой долей оттока попали клиенты, записавшиеся в рамках этой акции).
## Стек
Python, Scikit Learn, SciPy, Pandas, Matplotlib
