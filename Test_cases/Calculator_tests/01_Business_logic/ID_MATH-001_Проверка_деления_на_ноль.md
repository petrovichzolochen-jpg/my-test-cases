# ID: MATH 001 Проверка деления на ноль  
Приоритет: критический  
## Шаги:  
1. Отправить POST-запрос на URL: http://sitename/calculate  
2. В теле запроса передать JSON: {"statement": "10/0"}
### Ожидаемый результат:  
HTTP Status: 422 Unprocessable Entity  
Тело ответа: {"answer": null, "error": "Деление на ноль невозможно"}