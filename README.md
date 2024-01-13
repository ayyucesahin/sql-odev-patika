1 - Arrange the data in the title and description columns of the film table.
```1 -
SELECT title, description FROM film;
```
</br>

2 - Arrange all the data in the columns of the film table with the conditions that the film length (length) is greater than 60 AND less than 75.
```2 -
SELECT * FROM film 
WHERE length > 60 AND length < 75;
```
</br>

3 - Arrange all the data in the columns of the film table with the conditions that rental_rate is 0.99 AND replacement_cost is 12.99 OR 28.99.
```3 -
SELECT * FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99;
```
</br>

4 - What is the last_name value of the customer with the first_name value 'Mary' in the customer table?
```4 -
SELECT last_name FROM customer
WHERE first_name = "Mary";
```
</br>
5- Arrange the data in the film table that is NOT greater than 50 in length and at the same time does NOT have a rental_rate value of 2.99 or 4.99.
```5 -
SELECT * FROM film
WHERE NOT length > 50 AND NOT (rental_rate = 2.99 OR rental_rate = 4.99);
```















