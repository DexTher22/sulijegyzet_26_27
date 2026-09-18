# Asztali és mobil alkalmazások

## 2026-09-04

mehet.jar -> mehet.exe

standard input 0  
standard output 1 -> System.out  
standard error 2 -> System.err

java -jar mehet.jar > NUL   ->   Csak a hibák

">" standard kimenet átirányítása
"NUL" kuka

java -jar mehet.jar > normal.txt 2> hibak.txt  ->  file-ba irányítás  
java -jar mehet.jar >> normal.txt 2>> hibak.txt -> Hozzáfűzés

java -jar mehet.jar > mind.txt 2>&1

2 számrendszer

```
	 0011  
vagy 0010  
---------  
	 0011  
```
```
	 0011  
és   0010  
---------  
	 0010
```
	 
	 
## 2026-09-07

abstract

	public abstract class Valami {  
		public abstract valami();
	}



interface  
public interface Valami {}

Laza függőség

### bama

No build tools  
	Külső függőség használata
	
MariaDB -> XAMPP

central.sonatype.com  
mariadb-java-client  jdbc

sql.Connection  
sql.DriverManager

```
mysql -u root  
show databases;  
create database bama;  
show databases;  
use bama;  
show tables;  
```

## 2026-09-14

### bama

create.sqlite3-query


## 2026-09-18


### Dolgozatok:
1. : 2026-10-02    
	Interface  
2. : 2026-10-19  
	állomány és adatbázis kezelés  
3. : 2026-12-04 témazáró (200%)  
	GUI?  

### Interface gyakorlás  

https://github.com/oktat/tan/blob/master/asztali_mobil/02_OOP.md#feladat-002

### telefon/

Telefon.java  
Okostelefon.java  

### Adatbázis kezelés bama/

https://github.com/DexTher22/bama_java_adatb

### bamav/

Új maven projekt

vies/  
controllers/  
models/  
 |-Employee.java  
 |-Database.java  
 |-Dataservice.java  
 |-Mariadb.java  
 |-Sqlite.java  
 
(
models/  
 |-dto/  
 |-database/  
)

https://github.com/DexTher22/bamav_java_adatb


















