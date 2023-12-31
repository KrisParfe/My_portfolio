# Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости

## Данные

Данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет

## Задача

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

## Используемые библиотеки

*pandas*, *matplotlib*, *seaborn*

## Описание проекта

На основе данных определила рыночную стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра:

- провела предобработку данных; 
- добавила новые данные;
- построила гистограммы, боксплоты, диаграммы рассеивания.

## Выводы

- портрет среднестатистичекой продаваемой квартиры: это двухкомнатная квартира в Санкт-Петербурге на 6 этаже 11-ти этажного дома с высотой потолков 2,7 м общей площадью 60 кв.м. (в т.ч. жилая площадь - 34 кв.м. + 10 кв.м. кухня), в 28 км от аэропорта и 14 км от центра города, в радиусе 3 км есть 1 водоем и 1 парк, и продается такая квартира в течение полугода. 
- в наибольшей степени на стоимость квартиры влияет её общая площадь, в меньшей степени - жилая и площадь кухни. Квартиры на первом этаже стоят дешевле остальных.  
- наибольшее число объявлений о продаже было в Санкт-Петербурге, Мурино и Кудрово, самый дорогой квадратный метр жилья - в Санкт-Петербурге - 114,3 тыс. рублей. При этом чем ближе квартира к центру, тем она дороже.
