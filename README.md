# PortFolio

Здесь собраны некоторые реализованные проекты

|  #  | Наименование проекта        | Задачи проекта  | Описание проекта | Навыки и инструменты
|:----|:--------------------------- |:----------------|:-----------------|:-----------------
|  1. | [Прогнозирование цены фьючерса по историческим таймфреймам.](https://github.com/AlexandreFyodorov/PortFolio/blob/main/Price_Forecasting/Futures_stocks.ipynb) | Брокеру, использующему арсенал инструментов технического и фундаментального анализа, потребовался дополнительный наиболее качественный инструмент прогнозирования цены на фьючерсы с шагом прогноза 1 час.| Для построения модели прогнозирования цены за основу взяты математический анализ, временные ряды и регрессия. Изучены сезонные составляющие и подобраны оптимальные параметры для вхождения в точность 3-5 пунктов хождения цены от таргета. | Python, Pandas, Mathplotlob, Scikit-learn, исследовательский анализ данных, классификация.
|  2. | [Исследование надёжности заёмщиков - анализ банковских данных.](https://github.com/AlexandreFyodorov/PortFolio/tree/main/Reliability_Research) | На основе статистики о платёжеспособности клиентов исследовать, влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три. | Python, Pandas, предобработка данных, дубликатов, пропусков, категоризация и декомпозиция данных.
|  3. | [Прогнозирование оттока клиента Банка.](https://github.com/AlexandreFyodorov/PortFolio/tree/main/Outflow_forecasting) | На основе данных из банка определить клиента, который может уйти. | Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. | Python, Pandas, Mathplotlob, Scikit-learn, классификация, подбор гиперпараметров, выбор модели МО.
|  4. | [Защита данных клиентов страховых компаний.](https://github.com/AlexandreFyodorov/PortFolio/tree/main/Personal_data_protection) | Разработка модели анонимизации персональных данных. | Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработка такого метода преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснование корректности его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Без подборки наилучшей модели. | Python, Pandas, NumPy, Scikit-learn, линейная алгебра, регрессия.
