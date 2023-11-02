# Проекты в рамках karpov.courses
## [Исследование данных с применением когортного анализа и RFM-сегментации](https://github.com/KonstantinBykov/karpov.courses-projects/blob/master/cohort%20analysis%20and%20RFM-segmentation.ipynb)
**Описание проекта:**

В данном проекте я:

- Нашел количество пользователей, которые совершили покупку только один раз.
- Нашел среднее количество заказов в месяц, которые не доставляются по разным причинам.
- Определил по каждому товару, в какой день недели товар чаще всего покупается.
- Нашел среднее количество покупок в неделю у каждого из пользователей(по месяцам).
- Провел когортный анализа пользователей. В период с января по декабрь выявил когорту с самым высоким retention на 3й месяц.
- Построил RFM-сегментацию пользователей, чтобы качественно оценить свою аудиторию.

Результат исследования:'/n'
  Подавляющее большинство клиентов совершают покупки не очень часто (99% клиентов имеют частоту 1 или 2).
У нас много клиентов, которые не часто покупают (58 % находятся в сегментах : 'hibernating' и 'about to sleep').
36% наших клиентов являются либо новыми клиентами, либо многообещающими.
Всего около 2% клиентов являються лояльными

**Библиотеки:** pandas, pandasql, seaborn, matplotlib

## [Анализ взаимодействия с рекламными объявлениями](https://github.com/KonstantinBykov/karpov.courses-projects/blob/master/analysis%20of%20advertisements.ipynb)
**Описание проекта:**

В данном проекте я:

- Посчитал скользящее среднее показов с окном 2.
- Нанес на один график значения арифметического среднего по дням и скользящего среднего количества показов.
- Написал функцию, которая ищет проблемные(аномальные) объявления в день.
- Нашел среднее количество дней от даты создания рекламного объявления и первым запуском рекламного объявления этим клиентом.
- Вычислил конверсию из создания рекламного клиента в запуск первой рекламы в течение не более года.
- Определил, сколько уникальных клиентов запустили свое первое объявление в первый месяц своего существования, за три месяца, за пол года, за год.
- Вывел на интерактивный график эти категории с количеством уникальных клиентов в них.

**Библиотеки:** pandas, numpy, matplotlib, seaborn, plotly.express

## [Анализ работы службы доставки](https://github.com/KonstantinBykov/karpov.courses-projects/blob/master/delivery%20analysis.ipynb)
**Описание проекта:**

В данном проекте я:

- Посчитал MAU.
- Нашел количество установок в январе.
- Присвоил пользователям когорты по дню установки приложения и посчитал для них конверсию из установки в покупку в течение 7 дней.
- Определил, с какого платного маркетингового канала пришло больше всего новых пользователей.
- Определил с каких каналов пользователи, показали самую низкую конверсию в первую покупку.
- Нашел с какого канала пользователи, имеют медианный первый чек выше?
- Нашел платный канал привлечения (среди рекламных) с самымм высоким ROMI?

**Библиотеки:** pandas, numpy, matplotlib, seaborn
