# Принятие решений в бизнесе
Описание проекта: отдел маркетинга подготовил список гипотез для увеличения выручки, которые необходимо проверить в данной работе. Для этого были поставлены следующие:
1) приоритезировать гипотезы;

2) провести анализ A/B-теста;

3) сделать выводы на основании полученных результатов.

В проекте будут исследованы 3 датасета, структура которых представлена ниже. Концептуально проект разделен на 2 части.
<p> Структура /datasets/hypothesis.csv

*Hypothesis — краткое описание гипотезы;
*Reach — охват пользователей по 10-балльной шкале;
*Impact — влияние на пользователей по 10-балльной шкале;
*Confidence — уверенность в гипотезе по 10-балльной шкале;
*Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

Структура /datasets/orders.csv

transactionId — идентификатор заказа;
visitorId — идентификатор пользователя, совершившего заказ;
date — дата, когда был совершён заказ;
revenue — выручка заказа;
group — группа A/B-теста, в которую попал заказ
Структура /datasets/visitors.csv

date — дата;
group — группа A/B-теста;
visitors — количество пользователей в указанную дату в указанной группе A/B-теста
