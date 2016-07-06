# Interview-.net
Вопросы для собеседования


Протоколы

1. В чем отличие Soap и REST


.Net
1. Как работает Thread.Abort()? ThreadAbortException, safe place. Thread.BegineCriticalRegion, Thread.EndCriticalRegion
2. 

ASP.Net MVC

1. Что такое фильтры?

W

Razor

Что такое PartialView ?

WCF

Как организовать версионирование в WCF?

SQL

1. Решите задачу:

  CREATE TABLE T1 ( v int )
  CREATE TABLE T2 ( v int )

  INSERT INTO T1 VALUES ( 1 )
  INSERT INTO T1 VALUES ( 2 )
  INSERT INTO T1 VALUES ( 3 )

  INSERT INTO T2 VALUES ( 2 )
  INSERT INTO T2 VALUES ( 3 )
  INSERT INTO T2 VALUES ( 4 )
  INSERT INTO T2 VALUES ( 5 )
  
  Что вернут запросы?
  1. SELECT COUNT(*) FROM T1, T2
  2. SELECT COUNT(*) FROM T1 INNER JOIN T2 ON T1.v = T2.v
  3. SELECT COUNT(*) FROM T1 LEFT JOIN T2 ON T1.v = T2.v
  4. SELECT COUNT(*) FROM T1 RIGHT JOIN T2 ON T1.v = T2.v
  5. SELECT COUNT(*) FROM T1 FULL JOIN T2 ON T1.v = T2.v
  6. SELECT COUNT(*) FROM (SELECT  FROM T1 UNION SELECT  FROM T2) T
  7. SELECT COUNT(*) FROM (SELECT  FROM T1 UNION ALL SELECT  FROM T2) T

2. Решить задачу
Напишите запрос, который удалит дублирует Value записи?

-------
T1 (Id int, Value int)
1 1
2 2
3 1
4 1
5 4
6 2
7 3
8 2
....
---------------
1 1
2 2
5 4
7 3
....

3. Что такое CROSS APPLY? как он выполняется?
4. Какие виды join знаешь?
5. Как добавить большок количество даных в SQL? С помощью одного запроса. (Создается DataTable)
6. Какие способы оптимизации запроса?
7. Какие фичи появились в SQL Server 2016?
8. Как называется технология технология, которая позволяет напрямую выполнять web request (речь про OData)?

CSS
 1. Responsible design css tag

JavaScript 

1. Что такое замыкания?
2. Что вернет такой код?
    (window.foo || (window.foo = "bar"));



