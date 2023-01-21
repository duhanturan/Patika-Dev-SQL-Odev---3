# Patika-Dev-SQL-Odev-3
## SQL Odev - 3

### 1- country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.

````sql
select COUNTRY from COUNTRY WHERE COUNTRY LIKE 'A%' AND LIKE '%A';
````

### 2- country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.

````SQL
SELECT COUNTRY FROM COUNTRY WHERE COUNTRY LIKE '______' AND LIKE '%n';
````

### 3- film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.

````sql 
select TITLE FROM FILM WHERE NAME LIKE '%T%';
````

### 4- film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.

````SQL
SELECT * FROM FILM WHERE TITLE LIKE 'C%' AND LENGTH >90 AND rental_rate =2.99;
````
