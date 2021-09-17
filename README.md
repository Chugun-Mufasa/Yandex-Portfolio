## Проекты yandex практикума 2020-2021 г.

Название | Описание | Выводы | Библиотеки 
--- | --- | --- | --- 
[1.2 Анализ стоимости жилья](https://github.com/Chularev/yandex_practice/tree/master/1_2_research_of_apartments_for_sale) | По объявлениям о продаже квартир в Санкт-Петербурге и соседних населённых пунктов, определить рыночную стоимость объектов недвижимости. | В ходе работы выяснено, что квартиры в Питере востребованы, так как объявление «висят» в среднем не более 410 дней. На цену за квадратный метры существенное влияние оказывает удаленность квартиры от центра. | pandas, matplotlib, warnings
[1.3 Определение перспективного тарифа](https://github.com/Chularev/yandex_practice/blob/master/1_3_determination_of_promising_tariff4telecom_company) | Определить наиболее перспективный тариф для рекламной компании. | Не смотря на огромную популярность тарифа «Смарт», тариф «Ультра» приносит существенно больше прибыли. Доходность в Москве такая же как в других регионах. | pandas, math, seaborn, matplotlib, numpy, scipy
[1.4 Анализ рынка игр для интернет магазина](https://github.com/Chularev/yandex_practice/blob/master/1_4_%20stream_online_store) | Нужно выявить определяющие успешность игры закономерности. | Общие рекомендации В 2017 году самыми перспективными, по нашему мнению, считаются платформы XOne и PS4. | pandas, numpy, seaborn, matplotlib
[2.1 Рекомендация тарифов](https://github.com/Chularev/yandex_practice/tree/master/2_1_maximization_accuracy) | Нужно построить модель для задачи классификации, которая выберет подходящий тариф. | Лучшие предсказания дал случайный лес. | pandas, numpy, seaborn, matplotlib, imblearn, sklearn
[2.2 Отток клиентов](https://github.com/Chularev/yandex_practice/tree/master/2_2_outflow_of_bank_clients) | Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. | Лучшие предсказания дал случайный лес. | pandas, numpy, pylab, seaborn, matplotlib, imblearn, scipy, sklearn
[2.3 Поиск места бурение скважины.](https://github.com/Chularev/yandex_practice/tree/master/2_3_where_to_drill_a_new_well) | Нужно решить, где бурить новую скважину. | Предварительный анализ не дал результата, так как доход скважины, необходимый для покрытия затрат, больше среднего дохода с одной скважины в регионе. Для более точных оценок был применен мед бустреп, который показал, что несмотря на привлекательность первого и третьего региона, бурение следует провести во втором. | pandas, seaborn, matplotlib, numpy, sklearn
[2.4 Предсказания коэффициент восстановления золота из золотосодержащей руды.](https://github.com/Chularev/yandex_practice/tree/master/2_4_recovery_of_gold_from_gold_ore) | Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. | Была разработана модель, для предсказания эффективности переработки руды. Ошибка модели весьма стабильна. | pandas, seaborn, matplotlib, numpy, scipy, sklearn
[3.1 Шифрование персональных данных.](https://github.com/Chularev/yandex_practice/tree/master/3_1_encrypting_client_data) | Нужно защитить данные так, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.| Качество предсказания на зашифрованных данных не упало, что свидетельствует о правильности разработанного алгоритма. | pandas, seaborn, matplotlib, numpy, sklearn
[3.2 Сервис по продаже автомобилей с пробегом.](https://github.com/Chularev/yandex_practice/tree/master/3_2_service_by_buy_cars) | В проекте по историческим данным предсказывается стоимость подержанного автомобиля. | Как на тестовой выборки так и по кросс-валидация победил градиентный бустинг. Однако, эта модель учиться и предсказывает медленней всех. | pandas, time, seaborn, matplotlib, numpy, datetime, sklearn, lightgbm
[3.3 Прогноз заказов такси.](https://github.com/Chularev/yandex_practice/tree/master/3_3_taxi_orders_forecast) | Прогноз заказов такси на следующий час.| Поток заявок максимален в ночные часы, а его минимум достигается к 6 часам утра. | pandas, statsmodels, warnings, matplotlib, sklearn, lightgbm
[3.4 Классификатор комментариев.](https://github.com/Chularev/yandex_practice/tree/master/3_4_comments_classification) | Обучите модель классифицировать комментарии на позитивные и негативные.| В ходе данного проекта была разработана модель для предсказания токсичных комментариев.  | pandas, nltk, re, warnings, pymystem3, seaborn, matplotlib, sklearn
[4.1 Анализ спроса пассажиров на рейсы.](https://github.com/Chularev/yandex_practice/tree/master/4_1_small_project) | Изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие культурные фестивали. | С точи зрения авиа билетов, пользователи больше всего предпочитают города-мегаполисы, а также курортные города.  | pandas, seaborn, matplotlib, numpy
[4.2 Определение возраста покупателей.](https://github.com/Chularev/yandex_practice/tree/master/4_2_CV) | Определить возраст покупателей по фотографии. | Входе данной работы была написана нейронная сеть по определению возраста человека. | tensorflow.keras, numpy, pandas, seaborn, matplotlib
