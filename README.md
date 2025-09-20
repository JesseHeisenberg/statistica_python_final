# statistica_python_final
## Описание датасета:

- rank: Position of the YouTube channel based on the number of subscribers
- Youtuber: Name of the YouTube channel
- subscribers: Number of subscribers to the channel
- video views: Total views across all videos on the channel
- category: Category or niche of the channel
- Title: Title of the YouTube channel
- uploads: Total number of videos uploaded on the channel
- Country: Country where the YouTube channel originates
- Abbreviation: Abbreviation of the country
- channel_type: Type of the YouTube channel (e.g., individual, brand)
- video_views_rank: Ranking of the channel based on total video views
- country_rank: Ranking of the channel based on the number of subscribers within its country
- channel_type_rank: Ranking of the channel based on its type (individual or brand)
- video_views_for_the_last_30_days: Total video views in the last 30 days
- lowest_monthly_earnings: Lowest estimated monthly earnings from the channel
- highest_monthly_earnings: Highest estimated monthly earnings from the channel
- lowest_yearly_earnings: Lowest estimated yearly earnings from the channel
- highest_yearly_earnings: Highest estimated yearly earnings from the channel
- subscribers_for_last_30_days: Number of new subscribers gained in the last 30 days
- created_year: Year when the YouTube channel was created
- created_month: Month when the YouTube channel was created
- created_date: Exact date of the YouTube channel’s creation
- Gross tertiary education enrollment (%): Percentage of the population enrolled in tertiary education in the country
- Population: Total population of the country
- Unemployment rate: Unemployment rate in the country
- Urban_population: Percentage of the population living in urban areas
- Latitude: Latitude coordinate of the country’s location
- Longitude: Longitude coordinate of the country’s location

## Задание 1. EDA
Проведите разведывательный анализ данных (EDA).

Задайте не менее 6 вопросов к данным и постарайтесь ответить на них, используя визуализацию.
Изобразите матрицу корреляций для нахождения взаимосвязей.

## Задание 2. Корреляционный анализ
1. Оставьте два коррелирующих столбца: "subscribers" и"video views".
2. Отфильтруйте данные - уберите те строки, где кол-во просмотров равно нулю.
3. Рассчитайте коэффициент корреляции Пирсона.
4. Определите "video views" как признак Х, а "subscribers" - как целевую переменную.
5. Разделите выборку на тестовую и тренировочную.
6. Постройте модель линейной регрессии.
7. Рассчитайте точность модели на тестовой выборке.
8. Как изменится точность, если опустить пункт 2 и не убирать из данных нулевые просмотры?

## Задание 3. Классификация

1. Определите две самые популярные категории канала и отфильтруйте по ним набор данных.
2. В качестве признаков используйте следующие столбцы: [‘video views’, ‘subscribers’, ‘uploads’]
3. Снова отфильтруйте данные - уберите те строки, где кол-во просмотров равно нулю.
4. Для целевой переменной используйте столбец'category'. Значения по нему закодируйте с помощью LabelEncoder.
5. Разделите выборку на тестовую и тренировочную, укажите random_state=13.`
6. Постройте модель логистической регрессии.
7. Рассчитайте точность модели на тестовой выборке.
8. Изменится ли точность модели, если в качестве признаков выбрать другие столбцы?

**Требования по оформлению графиков**:
У графиков должен быть заголовок, подписи осей, легенда (опционально). Каждая визуализация должным образом оформлена и может быть интерпретирована даже в отрыве от контекста.
**Важно!**
Оставляйте свои комментарии к графикам: отвечает ли визуализация на поставленный вопрос, что вы наблюдаете в данных, какие выводы можно сделать и т.д. Ход ваших мыслей так же важен, как и написанный вами код.
