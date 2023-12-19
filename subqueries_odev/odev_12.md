film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
```sql
select count(*) from film
where length > (select avg(length) from film);
```
film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```sql
select count(*) from film
where rental_rate = (select MAX(rental_rate) from film);
```
film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
```sql
select rental_rate, replacement_cost from film
where rental_rate = (select MIN(rental_rate) from film) and 
      replacement_cost = ( select MIN(replacement_cost) from film);
```
payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
```sql
select first_name, last_name, count(*) from customer
INNER JOIN payment ON customer.customer_id=payment.customer_id
GROUP BY first_name, last_name
ORDER BY count(*) DESC;
```
