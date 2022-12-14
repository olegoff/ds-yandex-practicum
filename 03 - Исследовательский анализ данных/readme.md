# 3. Исследовательский анализ данных

### Цели проекта

- Научиться определять рыночную стоимость объектов недвижимости.
- Установить параметры для построения автоматизированной системы отслеживания аномалий и мошеннической деятельности:
	- время, за которое происходит продажа квартир
	- фактор, оказывающие наибольшее влияние на стоимость квартир
	- выяснить, какая область входит в центр Санкт-Петербурга
	- выделить сегмент квартир в центре и проанализировать эту территорию

### Задачи проекта

- Предобработка данных (пропуски, дубликаты, выбросы)
- Анализ аномальных данных
- Расчёт дополнительных признаков для анализа стоимости квадратного метра
- Анализ факторов, влияющих на стоимость квартир
- Изучение сегмента квартир в центре и сравнение его со всей базой

### Итоги

- На стоимость квартиры больше всего влияют следующие параметры: общая площадь, количество комнат и удалённость от центра. 
- Отмечен полуторакратный спад цен на недвижимость в 2014-2015 гг., который завершился их стабилизацией в 2016-2017 гг. и дальнейшим ростом после 2018 г. 
- Проанализирована стоимость квадратного метра в различных районах. Самым дорогим оказался Санкт-Петербург (114833.58 р/м²), самая дешёвая стоимость квадратного метра в Выборге (58141.49 р/м²).  
- Выделен район, который можно отнести к центру. Его граница установлена значением в 4 км. 
- Для сегмента кварти в центре наибольшее влияние оказывают те же параметры, которые характерны для всей базы объявлений. При этом для сегмента квартир в центре отмечено более значительное падение стоимости квартир в 2014-2015 гг. 

### Используемый стек инструментов

- python
- pandas
- numpy
- matplotlib
