# [Проверка гипотез по увеличению выручки и оценка результатов A/B-теста](https://nbviewer.jupyter.org/github/Nanobelka/online_shop_AB_test/blob/main/online_shop.ipynb)
## Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем выполнен анализ результатов A/B-теста, построены графики кумулятивной выручки, среднего чека, конверсии по группам, посчитаны статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа было принято решение о нецелесообразности продолжения тестирования.

**Заказчик:** некий интернет-магазин.

**Данные:**
- список гипотез, предоставленный отделом маркетинга;
- данные о заказах за период с 01.08.2019 по 31.08.2019;
- данные о посетителях за период с 01.08.2019 по 31.08.2019.

**Цель:** подготовить рекомендации по результатам анализа А/В-теста.

**Задачи:**

- приоритизировать гипотезы, подготовленные отделом маркетинга;
- проанализировать полученные результаты А/В-теста:
    - оценить качество предоставленных данных;
    - провести подготовку данных к анализу;
    - проанализировать по группам: конверсию, выручку, среднюю сумму заказа;
    - проанализировать распределение: количества заказов на одного покупателя, стоимость заказов;
    - попробовать найти различие между группами А и В с помощью статистических методов;
    - определить аномалии в данных, подготовить очищенные от аномалий данные;
    - при необходимости повторить анализ на основании очищенных данных;
- дать рекомендации заказчику по результатам исследования;
- определить потенциальные риски данного исследования, возможности их устранения;  
- дать рекомендации по дальнейшему развитию данного исследования.
