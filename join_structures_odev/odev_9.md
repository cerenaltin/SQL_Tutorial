- city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```sql
select city, country from city
INNER JOIN country ON country.country_id = city.country_id;
```
- customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```sql
select first_name, last_name, payment_id from customer
INNER JOIN payment ON payment.customer_id = customer.customer_id;
```
- customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```sql
select first_name, last_name, rental_id from customer
INNER JOIN rental ON rental.customer_id = customer.customer_id;
```
