# ID: MATH-007 Сложение больших чисел  
Приоритет: средний  
## Шаги: 
1. Отправить POST-запрос на URL: http://sitename/calculate  
2. В теле запроса передать JSON: {"statement": "999999+1"}  

### Ожидаемый результат:  
HTTP Status: 200 OK  
Тело ответа: {"answer": 1000000.0, "error": null}