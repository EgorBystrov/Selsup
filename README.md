# Реализация класса для работы с API Честного знака.

_______
![Static Badge](https://img.shields.io/badge/Java-red)





### Используемые технологии:
+ *Java 11*
+ *Maven*




____
### Старт приложения

+ запустить метод main

_____
### Описание 
+ Вызывается по HTTPS метод POST следующий URL:
https://ismp.crpt.ru/api/v3/lk/documents/create

+ В теле запроса передается в формате JSON документ: {"description":
{ "participantInn": "string" }, "doc_id": "string", "doc_status": "string",
"doc_type": "LP_INTRODUCE_GOODS", 109 "importRequest": true,
"owner_inn": "string", "participant_inn": "string", "producer_inn":
"string", "production_date": "2020-01-23", "production_type": "string",
"products": [ { "certificate_document": "string",
"certificate_document_date": "2020-01-23",
"certificate_document_number": "string", "owner_inn": "string",
"producer_inn": "string", "production_date": "2020-01-23",
"tnved_code": "string", "uit_code": "string", "uitu_code": "string" } ],
"reg_date": "2020-01-23", "reg_number": "string"}
