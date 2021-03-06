# Исследование объявлений о продаже квартир в города Севастополя


### Задачи

- Собрать данные с сайта Авито.Недвижимость по г. Севастополю парсингом многостраничного сайта
- Сохранить полученные данные в таблицу для дальнейшего анализа
- Провести предобработку данных:
	* заполнить пропущенные значения
	* заполнить улицы
	* распределить по районам
- Изучить кличество агентств недвижимости в городе
- Изучить какие квартиры преобладают в агентствах по параметрам: адрес, кол-во комнат, этаж
- Изучить какие районы самые популярные в продаже недвижимости
- Изучить влияние района, площади, этажа на рыночную стоимость квартиры
...

### Результат

Данные показали, что в продаже преобладают 2к квартиры по цене в 4-5млн. Наиболее востребованный район Гагаринский с улицами ПОР, Юмашева. 
Наиболее востребованы квартиры на средних этажах. Первый этаж дороже чем последний.
В городе порядка 15 больших агентств. Малых более 40.

### Стек

*pandas*, *matplotlib*, *numpy*, *datetime*, *plotly*, *requests*, *BeautifulSoup*

### Статус проекта: В работе