## GPSStoFlow
  Доступные блоки:
- GENERATE a,b,c,d,e,f
-   - a,b,c,d,e,f - воспринимаются как единая строка  
- TERMINATE a
-   - a - необязательный параметр
- ADVANCE a,b
-   - a,b - воспринимаются как единая строка
- QUEUE a,b
- - a - название очереди
- - b - мест в очереди
- DEPART a,b
- - a - название очереди
- - b - мест в очереди
- SEIZE a
- - a - название устройства
- RELEASE a
- - a - название устройства
- ENDER a,b
- - a - название накопителя
- - b - единиц памяти
- LEAVE a,b
- - a - название накопителя
- - b - единиц памяти
- TRANSFER a,b,c
- - a - Вероятность или BOTH
- - b - блок с вероятностью перехода 1-a 
(если BOTH то транзакт, который проверяется первым)
- - c - блок с вероятностью перехода a
(если BOTH то транзакт, который проверяется в случае если в b перейти не удалось)