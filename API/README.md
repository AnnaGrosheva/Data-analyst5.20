# Рынок заведений общественного питания Москвы
**Краткое описание проекта**

**Цели проекта:**

Необходимо изучить нынешнее положение дел на рынке общественного питания в Москве:

Вычислить самые популярные улицы, а также определить улицы с одним объектом общественного питания.
Подобрать наиболее подходящий район для открытия.
Рассмотреть распределение посадочных мест, а также найти наиболее выгодный вариант какой тип заведения следует открыть.
Рассмотреть данные конкурентов и выдвинуть свою версию возможной прибыльности запуска работов-официантов в будущем кафе.
По итогам проведенного исследования необходимо подготовить презентацию для инвесторов.

**Имеющиеся данные:**

В моем распоряжении есть данные о различных заведениях общественного питания в Москве. Имеющийся датасет содержит в себе следующую информацию:

- id — идентификатор объекта;
- object_name — название объекта общественного питания;
- chain — сетевой ресторан;
- object_type — тип объекта общественного питания;
- address — адрес;
- number — количество посадочных мест.

**План проекта**

- 1  Изучение данных из файлов
- 2  Предобработка данных
- 3  Анализ данных
- 3.1  Объекты общественного питания
- 3.2  Сетевые и несетевые заведения
- 3.3  Сетевое распространение
- 3.4  Что характерно сетевым заведениям
- 3.5  Среднее количество посадочных мест
- 3.6  Адрес
- 3.7  Топ-10 улиц
- 3.8  Один объект общественного питания
- 3.9  Распределение посадочных мест
- 4  Презентация
- 5  Вывод

**Выводы по проделанной работе**

Итоги по предобработке:

Пропусков нет.
Были обнаружены дубликаты по столбцам названия объекта, сети, типа и адреса.
Все данные представлены в правильном формате.
Обнаружено нулевое количество посадочных мест не только в закусочных и магазинах. Это может быть связано с Covid-19, в результате которого большая часть заведений стала работать на вынос.

Итоги по анализу:

Наиболее часто встречающимся объектом из сферы общественного питания является кафе. В то время как наименее распространенным в Москве объектом общественного питания является магазин с отделом кулинарии.

Гораздо чаще на улицах Москвы можно втсретить несетевые заведения - 80.6%. Сетевые заведения же составляют лишь 19.4% от общего количества.

Из вышеописанных 19.4% сетевых заведений - фастфуд составляет большую часть в своей группе.

Сетевым заведениям характерно до 4х заведений из одной сети и от 10 до 20 посадочных мест. Также выделяются сетевые заведения с количеством посадочных мест от 40 до 50. Следовательно, наиболее характерным для сетевых заведений является: мало заведений с большим количеством посадочных мест.

Если рассматривать среднее количество мест и по сетевым и несетевым заведениям, то получаем: самое большее среднее среди всего количества посадочных мест принадлежит столовым, в то время как самое меньшее принадлежит закусочным и магазинам.

Топ-10 улиц по количеству объектов общественного питания: проспект Мира, Профсоюзная улица, Ленинградский проспект, Пресненская набережная, Варшавское шоссе, Ленинский проспект, проспект Вернадского, Кутузовский проспект, Каширское шоссе, Кировоградская улица.

Что же касается районов с улицами на которых распроложен лишь один объект общественного питания, то получается что лидируют пять районой: Таганский, Хамовники, Пресненский, Басманный и Тверской район. Всего 612 улиц с одним объектом общественного питания.

Что касается распределения посадочных мест по топ-10 улиц Москвы, то получаю что среднее значение заведений на этих улицах колеблется от 24 до 45 посадочных мест. Максимальное количество посадочных мест находится на Кутузовском проспекте, а это 1700 мест. Скорее всего это какой-либо банкетный зал.

Рекомендации:

Лучшим вариантом будет открыть одно кафе, в котором количество посадочных мест не будет превышать 20. В дальнейшем можно будет создать сеть кафе, если первое заведение покажет хорошие результаты и принесет большую выручку.

Про районы:

Я бы рекомендовала открыть кафе в туристическом районе Москвы (как например Арбат с очень высокой проходимостью), так как туристов ожидаемо будут интересовать красивые и необычные заведения Москвы где можно поесть. И, как раз таки, наш новый и необычный формат обслуживания в виде роботов заинтересует гостей столицы.
Не советовала бы открывать кафе в районах с одним объектом на улице. Скорее всего это спальные районы с плохой проходимостью, либо же есть проблемы с открытием общественного заведения в данном месте, например место не попадает под нормы СП 2.3.6.1079-01.
