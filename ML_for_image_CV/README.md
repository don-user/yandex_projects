# ML_for_image_CV

### Условия:
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:  
 - Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;  
 - Контролировать добросовестность кассиров при продаже алкоголя.  

Необходимо построить модель, которая по фотографии определит приблизительный возраст человека. 


Описание данных:  
Данные взяты с сайта ChaLearn Looking at People.  
Разметка картинок находится в файле labels.csv с двумя колонками:  
file_name - наименование файла с картинкой  
real_age - реальный возраст.  

### Ход работы:
- Исследовательский анализ набора фотографий
- Подготовка данных
- Обучение нейронной сети 
- Оценка качества результатов предсказаний нейронной сети

### Вывод:
При небольшой предобработки изображений ввиде horizontal_flip, оптимизатора Adam с learning_rate=0.0001 и функцией потерь mse, при обучении на 10 эпохах было получена метрика MAE = 5.8211.
