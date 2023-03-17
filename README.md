# SQL-ODEV-1
DVDRENTAL SORGU SENARYOLARI ÇÖZÜMLERİ-
film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.
film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.
ÇÖZÜM: SELECT * FROM film WHERE length > 60 AND length < 75

![Capture1](https://user-images.githubusercontent.com/128131203/225854613-f7b1cff6-ff58-468a-a635-a71f549385b8.PNG)

film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız.
ÇÖZÜM: SELECT * FROM film WHERE (rental_rate = 0.99) AND (replacement_cost = 12.99 OR replacement_cost = 28.99)

![Capture1](https://user-images.githubusercontent.com/128131203/225855346-353c5cc7-076b-4de9-90a0-02019804cc42.PNG)



customer tablosunda bulunan first_name sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?
ÇÖZÜM:SELECT first_name, last_name FROM customer WHERE first_name = 'Mary'

![Capture3](https://user-images.githubusercontent.com/128131203/225855440-0d21d285-6a91-4b88-9bbc-52e7d42bb4b9.PNG)

film tablosundaki uzunluğu(length) 50 ten büyük OLMAYIP aynı zamanda rental_rate değeri 2.99 veya 4.99 OLMAYAN verileri sıralayınız.
ÇÖZÜM:SELECT length, rental_rate FROM film WHERE length < 50 AND (rental_rate <> 2.99 AND rental_rate <> 4.99

![Capture4](https://user-images.githubusercontent.com/128131203/225855553-3da78d96-88ff-4019-aba8-14d1d434ad6e.PNG)
