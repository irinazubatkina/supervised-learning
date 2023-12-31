Проект "Отток клиентов"

Постановка задачи:

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. 

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

Эпаты исследования:

В проекте будет предложена модель, которая наиболее точно позволит предсказать вероятность потери банком клиента (метрики F1 и AUC-ROC). Для построения модели потребуется выполнить следующие шаги:

1) Изучить и подготовить данные для обучения, проверки и тестирования
2) Исследовать различные классификационные модели на основе логической регрессии, алгоритма решающего дерева и случайного леса
3) Оптимизировать обучающую выборку путем компенсации дисбаланса классов
4) Протестировать наилучшую модель на тестовой выборке

Результаты:

В проекте решалась задача построения качественной классификационной модели, которая позволила бы достаточно точно предсказать уйдет ли клиент из банка. Для решения поставленной задачи исходные данные были подготовлены для применения алгоритмов обучения и разделены на признаки и целевой признак, а также обучающую, валидационную и тестовую выборки. Были исследованы модели логической регрессии, решающего дерева и случайного леса с целью поиска оптимальной модели. Однако ни одна из моделей не достигала целевых показалей качества. Причиной недостаточного качества обучения моделей оказался дисбаланс классов целевого признака (соотношение 80:20). Были применены различные методы, позволяющие сбалансировать классы и устранить существенное преобладание одного из них. Устранение дисбаланса позволило улучшить качество моделей, а также найти оптимальную модель и ее параметры. Найлучшей оказалась модель случайного леса с количесвом деревьев 20 и максимальной глубиной 5, которая показала высокий резльтат качества работы на тестовой выборке.