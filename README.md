# Analytics-camp
Дан датасет некой интернет-компании. Цель ответить на следующие вопросы:
a. Какой рекламный канал принёс больше всего дохода за всё время?
b. Как изменился средний чек транзакции после введения коронавирусных ограничений?
Как он изменился для пользователей, покупающих с промокодом и без? (параметр
«promo_activated»)
c. Можно ли с уверенностью в 95% сказать, что CR (коэффициент конверсии в
транзакцию) в выходные дни отличается от CR в будние дни?
d. Вам необходимо спрогнозировать объем дохода, полученного с пользователей,
приведенных на сайт контекстной рекламой (medium = cpc) на полгода вперед. 

### Коротко о результатах(не коротко в файле ТЗ_Сергеев.ipynb): 
1. больше всего дохода принёс yandex - 467299300.
2. Средний чек после ограничений снизился примерно на 7%. Средний чек с промокодом снизился на 2.88% , а средний чек без промокода снизился на 11.34%.
3. Не смотря на то, что визуально конверсия в выходные действительно отличается, статестический тест с 95% точностью говорит нам о том что разницы в конверсии нет.
4. с помощью модели SARIMAX построен предективный временой ряд на пол года вперёд.
