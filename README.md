# SQL-ODEV3
Like, Ilike Operatörü
##
1) SELECT country FROM country
   WHERE country LIKE 'A%a';
2) SELECT country FROM country
   WHERE length(country)>=6 AND country LIKE '%n';
3) SELECT title FROM film
   WHERE title ILIKE '%T%T%T%T';
4) SELECT * FROM film
   WHERE title LIKE 'C%' AND length(title)>90 AND rental_rate=2.99 ; 
   
