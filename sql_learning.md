# SQL Learning

1️⃣ [SQL Basics](#sql-basics)

2️⃣ [SQL Advanced](#sql-advanced)


![SQL Page Image](images/sql/sql.webp)

# SQL Basics

1. Wyświetl z tabeli customers kraje bez duplikatów, uporządkuj w kolejności alfabetycznej malejaco, wyświetl tylko 6 pierwszych wyników. 

```sql
SELECT DISTINCT country FROM `customers` ORDER BY Country DESC LIMIT 6; 
```
![SQL Page Image](images/sql/sql1.png)

2. Wyświetl z tabeli Customers takie kontakty, których ContactName zaczyna się od dowolnej literki, druga to "a", trzecia "r"i ma kończyć się na "s". Wyswietl tylko nazwisko i Id klienta. 

```sql
SELECT ContactName, CustomerID FROM customers WHERE ContactName LIKE '_ar%s'; 
```
![SQL Page Image](images/sql/sql2.png)

 3. Dla tabeli customers stwórz zapytanie, które wyświetli wszystkie osoby mieszkające w Madrycie lub we Francji. 

```sql
SELECT * FROM `customers` WHERE City = "Madrid" OR Country = "France"; 
```
![SQL Page Image](images/sql/sql3.png)

4. Dla tabeli Orders zrób zapytanie, które wyświietli tylko 2 pierwsze rekordy należące do przedziału dat: 
od 1996-07-15 do 1996-07-30. Posortuj wyniki rosnąco po kolumnie ShipperId i malejąco po OrderId. 

```sql
SELECT * FROM `orders`WHERE OrderDate BETWEEN '1996-07-15' AND '1996-07-30' ORDER BY ShipperID ASC, OrderID DESC LIMIT 2; 
```
![SQL Page Image](images/sql/sql4.png)

5. Dla klienta o Id=5 zaktualizuj miasto i kraj na odpowiednio Warszawa, Polska. 

```sql
UPDATE customers SET City = "Warsaw", Country = "Poland"
WHERE CustomerID = 5;
```
![SQL Page Image](images/sql/sql5a.png)
![SQL Page Image](images/sql/sql5b.png)

6.  Zrób zestawienie łącznej ilości osób dla konkretnej narodowości. Wyświetl tylko te rekordy gdzie łączna ilość osób w kraju > 2. Możesz wyświetlić rekordy malejąco. 

```sql
SELECT CustomerID, COUNT(CustomerName) AS IloscOsob, Country  FROM customers
GROUP By Country
HAVING COUNT(CustomerName)>2
ORDER BY COUNT(CustomerName) DESC;
```
![SQL Page Image](images/sql/sql6.png)


7. Dla tabeli Suppliers przygotuj zestawienie, które pogrupuje łączną ilość osób należących do konkretnego Country. Uporządkuj malejąco. 

```sql
SELECT COUNT(SupplierID) AS LacznailoscOsob, Country, SupplierName
FROM `suppliers`
GROUP BY Country
ORDER By COUNT(SupplierID) DESC;
```
![SQL Page Image](images/sql/sql7.png)
 

# SQL Advanced


fa sg
fsd
fdf 
sd
fasd
fdf
sad
f