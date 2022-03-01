# SQL-homeWork-8

## 1.) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

# solve 

CREATE TABLE author (
id INTEGER, 
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
);

## 2.) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

# solve 
50 adet veri eklendi

## 3.) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

# solve

UPDATE author 
SET name = 'Metehan',
birthday = '1999-03-23',
email = 'metehanelmas@hotmail.com'
Where id = 2;

## 4.) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

# solve 

DELETE FROM author 
WHERE id = 2;

