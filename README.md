# fast_food_geoanalytics
Проект анализа фастфуд рынка США с целью открытия новых точек сети нашего ресторана.

Мной предложена и реализована идея геоаналитики: рассчитываем плотность фастфуд ресторанов конкурентов с группировкой по postal code, заливкой районов города отображаем данный показатель.
Далее на карту наносим трафикообразующие объекты (заправочные станции, ТЦ, моллы, магазины, супермаркеты, аптеки, музеи, театры). Маркерами обозначаем локации конкурирующих заведений.
Для открытия ресторана выбираем предпочтительно центральные районы с высокми трафиком и плотностью конкурентов 3-7 заведений на район (меньшая плотность говорит нам об отсутствии спроса, большая плотность - слишком большая конкуренция для пробного выхода на рынок).
В результате анализа для каждого из интересующих нас городов рекомендован район, ограниченный улицами, для дальнейшего анализа по наличию коммерческих площадей.

Анализ выполнен с помощью Python.
Библиотеки: Pandas, Seaborn, Geopandas, Folium.
