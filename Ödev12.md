# Ödev12
#### 1. Film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
```sql
SELECT COUNT (*) FROM film
WHERE length >
(
  SELECT AVG (length) FROM film
);
```
cevap:489

#### 2. Film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```sql
SELECT COUNT (*) FROM film
WHERE rental_rate =
(
  SELECT MAX (rental_rate) FROM film
);
```
cevap:336

#### 3. Film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
```sql
SELECT title FROM film
WHERE title = ANY
(
SELECT title FROM film
	WHERE rental_rate = (SELECT MIN(rental_rate) FROM film) AND
		replacement_cost = (SELECT MIN (replacement_cost) FROM film)
)


```
#### 4. Payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
```sql
SELECT customer.customer_id, first_name, last_name, COUNT(payment_id) FROM payment
JOIN customer ON customer.customer_id = payment.customer_id
GROUP BY customer.customer_id 
ORDER BY COUNT(payment_id) DESC;
```
