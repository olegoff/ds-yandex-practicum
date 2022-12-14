# 14. Компьютерное зрение

### Цели проекта

- Используя размеченный набор фотографий людей с указанием их возраста, построить модель, которая по фотографии определит приблизительный возраст человека.  
- По условию задачи необходимо получить значения *MAE* на тестовой выборке не больше `8`, то есть средняя ошибка определения возраста должна быть меньше `8 лет`.  

### Задачи проекта

- Провести исследовательский анализ набора фотографий  
- Подготовить данные к обучению  
- Обучить нейронную сеть и определить качество её работы  

### Итоги

- Выполнено обучение модели на основе свёрточной нейронной сети ResNet50.  
- Для обучения моделей исходные данные разделены на обучающий и тестовый наборы в соотношении `3:1`.  
- По результатам обучения нейронной сети ResNet50 получили на тестовой выборке метрику *MAE*, равную `5.98`, что удовлетворяет условию задания `< 8.0`.  
- Проведено сопоставление реальных и предсказанных значений возраста покупателей с их фотографиям и установлена достаточно адекватная работа модели по определению возраста, и отмечено что чаще и сильнее модель ошибается в предсказаниях людей старшего возраста.  
- Анализ графика распределения разностей предсказанных моделью и реальных значений возраста покупателей показал, что до возраста покупателей, равного `29` годам, модель преимущественно демонстрирует завышение предсказанных значения возраста по отношению к реальным, а после - к занижению, а сама величина ошибки предсказания имеет тенденцию к увеличению с ростом реального возраста покупателей, что может свидетельствовать о недостаточном количестве соотвествующих обучающих данных.  

### Используемый стек инструментов

- pandas
- numpy
- sklearn
- pickle
- matplotlib
- seaborn
- PIL
- keras
- tensorflow
