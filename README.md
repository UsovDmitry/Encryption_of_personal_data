<a name= ""> </a>
## **Защита персональных данных клиентов**
___
### Содержание
___
1.  [Защита персональных данных клиентов](#0)    
	1.1 [Описание проекта](#1)  
	1.2 [Описание данных](#2)  
	1.3 [Условия задачи](#3)    
2. [Вывод](#4)    

___
<a name= "1"> </a>
### Описание проекта
Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.
___
<a name= "2"> </a>
### Описание данных

Набор данных находится в файле.

    Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
    Целевой признак: количество страховых выплат клиенту за последние 5 лет.

___
<a name= "3"> </a>
### Условия задачи

    Загрузите и изучите данные.
    Ответьте на вопрос и обоснуйте решение.
    Признаки умножают на обратимую матрицу. Изменится ли качество линейной регрессии? (Её можно обучить заново.)
    a. Изменится. Приведите примеры матриц.
    b. Не изменится. Укажите, как связаны параметры линейной регрессии в исходной задаче и в преобразованной.
    Предложите алгоритм преобразования данных для решения задачи. Обоснуйте, почему качество линейной регрессии не поменяется.
    Запрограммируйте этот алгоритм, применив матричные операции. Проверьте, что качество линейной регрессии из sklearn не отличается до и после преобразования. Примените метрику R2.
___
<a name= "4"> </a>
### Вывод
Качество прогнозироваия линейной регрессии до и после преобразовани признаков остается неизменным, это позволяет использовать данный метод шифрования в практических задачах. Я конечно не искушен в методах шифрования, но на мой взгляд, этот метод из категории "дешево и сердито".


___
