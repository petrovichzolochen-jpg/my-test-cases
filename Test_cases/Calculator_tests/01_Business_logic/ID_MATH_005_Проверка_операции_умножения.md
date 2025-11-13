# ID: MATH 005 Проверка операции умножения  
Приоритет: высокий  
## Шаги:  
1. Отправить POST-запрос на URL: http://sitename/calculate  
2. В теле запроса передать JSON: {"statement": "20*2"}  
### Ожидаемый результат:
HTTP Status: 200 OK  
Тело ответа: {"answer": 40.0, "error": null}