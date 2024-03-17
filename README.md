# sql_odev3
<br></br><b> Soru 1 </b> 
<code>SELECT country FROM country
WHERE country LIKE ('A%a'); </code>
<br></br><b> Soru 2 </b> 
<code>SELECT country FROM country
WHERE country LIKE ('_____%n')</code>
<br></br><b> Soru 3 </b> 
<code>SELECT title FROM film 
WHERE title ILIKE ('%t%') OR title ILIKE ('t%') OR title ILIKE ('%t');</code>
<br></br><b> Soru 4 </b> 
<code> SELECT * FROM film 
WHERE title LIKE ('C%') AND length > 90 AND rental_rate = 2.99; </code>
