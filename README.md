# MachineLearning_EntryLevel

Любой бизнес хочет максимизировать количество клиентов. Для достижения этой цели важно не только пытаться привлечь новых, но и удерживать уже существующих. Удержать клиента обойдется компании дешевле, чем привлечь нового. Кроме того, новый клиент может оказаться слабо заинтересованным в услугах бизнеса и с ним будет сложно работать, тогда как о старых клиентах уже есть необходимые данные по взаимодействию с сервисом. 

Соответственно, прогнозируя отток, мы можем вовремя среагировать и попытаться удержать клиента, который хочет уйти. 

В исходных данных содержится информация о почти шести тысячах пользователей телекоммуникационной компании, их демографических характеристиках, услугах, которыми они пользуются, длительности пользования услугами оператора, методе оплаты, размере оплаты. В ходе работы выполнен анализ данных и спрогнозирован отток пользователей с использованием моделей машинного обучения.


## **Данный курсовой проект имеет следующие подразделы:**
### 1. Описание данных 

Рассчет базовых статистик, общей информации по датасету, просмотр информации по группам пользователей и итоговый вывод по разделу.


### 2. Исследование зависимостей и формулирование гипотез

Подготовка данных для дальнейшей работы , кодирование признаков, изучение взаимосвязей, формулировка гипотез и их проверка.


### 3. Построение моделей для прогнозирования оттока пользователей

Разделение данных на тестовые и тренировочные, обоснование выбора моделей, обучение моделей логистической регрессии, градиентного бустинга, случайного леса и XGB. Дополнительно применялась перекрестная проверка.


### 4. Сравнение качества моделей

Качество работы моделей с применением метрик accuracy и pricision, выводы по проведенной работе.




В ходе работы были применены основные методики улучшения работы моделей, такие как, обработка пропущенных значений, отбор признаков, алгоритмы ансамблевого обучения, подбор гиперпараметров моделей, но все методики не принесли ожидаемой точности. Возможно, признаки датасета не слишком информативны для построения более точной модели, или же требуется инженерия признаков, либо экспертная оценка.
