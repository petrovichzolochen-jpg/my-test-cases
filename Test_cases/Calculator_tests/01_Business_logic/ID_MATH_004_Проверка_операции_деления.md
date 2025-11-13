# ID: MATH 004 Проверка операции деления  
Приоритет: высокий
## Шаги: 
1. Отправить POST-запрос на URL: http://sitename/calculate  
2. В теле запроса передать JSON: {"statement": "15/3"}  
### Ожидаемый результат: 
HTTP Status: 200 OK  
Тело ответа: {"answer": 5.0, "error": null}