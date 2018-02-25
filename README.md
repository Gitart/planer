# planer
### Sinchronization

Процедра опредления разницы в база данных

1. Запуск оригинальной базы и прохождение всех объектов базы данны
или тех которые только нужны т.е. записанные в таблице сканирования

## Structure table

|Id|Field|Description
|---|---|---|
|Id|Id|Уникальный номер
|Object|String|Наименование объекта базы данных
|Created|String|Дата создания
|Chaged|String|Дата изменения
|Size|String|Размер КБ оригинального объекта
|Hash|String|Hash оригинального объекта
|Sizeс|String|Размер КБ 
|Hashс|String|Hash
|Status|String|Статус сравнения 
|Develop|String|Разработчик
|Place|String|Место сравнения 






## Check table

|Id|Object type|Object name|Size|Hash|Date|Ru|Original Size|Orig Hash|Orig Date|Status|
|--|--|--|--|--|--|--|--|--|--|--|
|1|Sql|sql name1|1234|asffff2344|01-02-2018|12344|344|dhjfhrr-rjuit|02-02-2018|Dif|
|2|Sql|sql name1|1234|asffff2344|01-02-2018|12344|344|dhjfhrr-rjuit|02-02-2018|Dif|
|3|Trig|sql name1|1234|asffff2344|01-02-2018|12344|344|dhjfhrr-rjuit|02-02-2018|Dif|





