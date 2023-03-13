#Тестовое задание Збродов Е.А.



Файлы: 

1) ESOFT_DATA_СONVERSION.ipynb - файл в котором содержится ход работы, показывающий предобработку данных для обучения моделей 
2) E_soft_models.ipynb - файл в котором содержится информация о моделях, которые тестировались, лучшую мы отбираем и сохраняем
3) ESOFT_System_Price.ipynb - файл содержащий систему оценивающую объекты недвижимости по их параметрам

Данные:
1) sold_flats_2020-09-30.csv - Датасет выданный при начале выполнения работы 
2) final_data.xlsx - Финальная версия датасета, которая получилась в следствии предообработки данныз. Именно его используем для обучения моделей
3) catboost_model.dump - Лучшая модель - "CatBoostRegressor", которая была сохранена для дальнейшей работы





![image](https://user-images.githubusercontent.com/89632164/224644392-49cc1dea-6b21-4625-93fc-85b37d58b333.png)


Сама задача: 

- разработать систему подготовки данных из предоставленной выборки объектов
- плюсом будет оценка важности атрибутов объекта для определения цены
- разработать на основе алгоритмов машинного обучения систему оценивающую объекты недвижимости по их параметрам
######################################################
- для обучения системы предоставляется выборка проданных объектов (около 71к)
- допускается использование любого типа моделей машинного обучения или их ансамблей

![image](https://user-images.githubusercontent.com/89632164/224654095-ffce44bf-d6c9-48f7-b056-f951619b84ab.png)
