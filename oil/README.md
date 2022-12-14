
## Выбор локации для скважины

Шаги для выбора локации обычно такие:
<br/>В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
<br/>Строят модель для предсказания объёма запасов в новых скважинах;
<br/>Выбирают скважины с самыми высокими оценками значений;
<br/>Определяют регион с максимальной суммарной прибылью отобранных скважин.

Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Требуется построить модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.


## План работы
1. Загрузка и подготовка данных;
2. Обучение и проверка модели для каждого региона;
3. Подготовка и расчет прибыли и рисков для каждого региона.

## Используемые библиотеки и инструменты
- pandas
- scikit-learn
- matplotlib
- numpy
- техника bootstrap

## Выводы
На основании предсказанных объемов запасов нефти в новых скважинах методом бутстреп определены значения ожидаемой прибыли и рисков убытков по каждому из регионов.
