# sql queries

Given four tables
*  movies
*  concessions
*  showtimes
*  promotions

SELECT title  
FROM movies;

SELECT title, genre  
FROM movies;

This is an example of selection and projection:

SELECT title  
FROM movies  
WHERE id = 2;  

SELECT *
FROM movies
WHERE title = 'The Kid';

SELECT *  
FROM movies  
ORDER BY id DESC;


WHERE qualifiers  
<= Less than or equal
>= Greater than or equal
<> Not equal

select item, price, size  
from concessions  
where item='Popcorn'  
order by price DESC;  

INSERT INTO movies (id, title, genre, duration)  
VALUES (5,'The Circus', 'Comedy', 71);  

can do partial updates of rows.


INSERT INTO movies (title, duration)  
VALUES ('The Circus',  71);  



