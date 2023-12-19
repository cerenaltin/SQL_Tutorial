- actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.
```sql
(select first_name 
from customer)
UNION
(SELECT first_name 
from actor
);
```
- actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.
```sql
(select first_name 
from customer)
INTERSECT 
(SELECT first_name 
from actor
);
```
- actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
```sql
(select first_name 
from customer)
EXCEPT
(SELECT first_name 
from actor
);
```
- İlk 3 sorguyu tekrar eden veriler için de yapalım.
```sql
(select first_name 
from customer)
UNION ALL
(SELECT first_name 
from actor
);
```
```sql
(select first_name 
from customer)
INTERSECT ALL
(SELECT first_name 
from actor
);
```
```sql
(select first_name 
from customer)
EXCEPT ALL
(SELECT first_name 
from actor
);
```
