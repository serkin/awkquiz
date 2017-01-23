



- In which cities customers spent more money on `Beauty` in January than in February

<details>
  <summary>Answer</summary>

```sql
    SELECT cities.name,
         t1.m AS j,
         t2.m AS f
    FROM   cities
         LEFT JOIN (SELECT Sum(products.price) AS m,
                         cities.id_city
                  FROM   cities
                         LEFT JOIN users
                                ON users.id_city = cities.id_city
                         LEFT JOIN orders
                                ON users.id_user = orders.id_user
                         LEFT JOIN order_products
                                ON order_products.id_order = orders.id_order
                         LEFT JOIN products
                                ON products.id_product =
                                   order_products.id_product
                         LEFT JOIN categories
                                ON categories.id_category = products.id_category
                  WHERE  categories.name = 'Beauty'
                         AND Monthname (orders.date) = 'January'
                  GROUP  BY cities.id_city) AS t1
              ON cities.id_city = t1.id_city
       LEFT JOIN (SELECT Sum(products.price) AS m,
                         cities.id_city
                  FROM   cities
                         LEFT JOIN users
                                ON users.id_city = cities.id_city
                         LEFT JOIN orders
                                ON users.id_user = orders.id_user
                         LEFT JOIN order_products
                                ON order_products.id_order = orders.id_order
                         LEFT JOIN products
                                ON products.id_product =
                                   order_products.id_product
                         LEFT JOIN categories
                                ON categories.id_category = products.id_category
                  WHERE  categories.name = 'Beauty'
                         AND Monthname (orders.date) = 'February'
                  GROUP  BY cities.id_city) AS t2
              ON cities.id_city = t2.id_city
    WHERE  t2.m > t1.m
```


</details>

<hr>







http://superuser.com/questions/288621/create-mysql-database-with-one-line-in-bash

cross join
natural join
outer join


Показать клиентов потративших больше $200 в разделе Books но не потративших больше $100 в разделе Beaty
Показать страну клиенты из которой совершают покупки в разделе Books
Показать товары которые чаще всего покупают клиенты со средним чеком больше $200
Показать клиентов которые заказали eye set но не заказавших Book
Показать клиентов с одинаковыми именами не купивших eye set
Показать заказы содержащие eye set но не содержащие Book
Показать страны, в которыех жители тратят столько же на Books  сколько и на Beauty
Показать клиентов которые в марте купили на такую же сумму как и в январе
В каких городах люди больше тратили на Beaty в январе чем в феврале

Показать всех клиентов и товары которые они не купили
