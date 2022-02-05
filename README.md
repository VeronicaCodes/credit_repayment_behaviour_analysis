# Research of sales advertising in the housing market 

**Goal:** 
Our main goal was to find the parameters that will help us determine the market value of real estate properties. 

**Tools used:** 
Pandas, pymystem3, NumPy, matplotlib, collections

**Conclusion:** 
* The main parameter is 'total_area' - it has the strongest positive Pearson correlation coefficient (~0.29). Therefore, 'total_area' has the biggest influence on an apartment’s price. 
* Floor level of the apartment in the building impacts the price significantly as well (0.130251) but its effects are weaker. 
* The distance from the downtown area has a negative correlation effect, meaning if the distance to the city center increases, the price of the apartment drops (-0.25).

||price_sq_m	|total_area	|km_to_cityCenters	|floor|
|---|---|---|---|--|
|price_sq_m	|1.000000	|0.298829	|-0.251029	|0.130251|

We also selected several other parameters that affect prices of the real estate:
1. 'last_price' is in the range of 1 to 12 million rubles.<br>
2. 'total_area' is in the range of 20 to 150 $m^2$.<br>
3. 'rooms' is in the range of 1 to 5.<br>
4. 'ceiling_height' is 2.2 m and 4 m.<br>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Исследование объявлений о продаже недвижимости

**Цель:**
Определить параметры, имеющие наиболее сильное влияние на рыночную стоимость недвижимости. Это позволит построить автоматизированную систему, способную обнаруживать аномалии и мошенническую деятельность.

**Инструменты:**
Pandas, pymystem3, NumPy, matplotlib, collections

**Вывод:** 
* Основным параметром является total_area — он имеет самый сильный положительный коэффициент корреляции Пирсона (~0,29). Поэтому наибольшее влияние на цену квартиры оказывает именно этот параметр. 
* Этаж продабщегося помещения также существенно влияет на цену (0,130251), но его влияние слабее. 
* Удаленность от центра города имеет отрицательный корреляционный эффект: если расстояние до центра города увеличивается, цена квартиры падает (-0,25).

||цена кв.м. |общая площадь |км до центра |этаж|
|---|---|---|---|--|
|price_sq_m |1.000000 |0.298829 |-0.251029 |0.130251|

Мы также выбрали несколько других параметров, влияющих на стоимость недвижимости:
1. 'last_price' находится в диапазоне от 1 до 12 миллионов рублей.<br>
2. 'total_area' находится в диапазоне от 20 до 150 $м^2$.<br>
3. 'rooms' находятся в диапазоне от 1 до 5.<br>
4. 'ceiling_height' находятся в диапазоне  2,2 м и 4 м.<br>
