# ID: MATH 003 Проверка операции вычитания  
Приоритет: высокий  
## Шаги:  
1. Отправить POST-запрос на URL: http://sitename/calculate  
2. В теле запроса передать JSON: {"statement": "3-4"}
### Ожидаемый результат:  
HTTP Status: 200 OK  
Тело ответа: {"answer": -1.0, "error": null}