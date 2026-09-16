2026-09-01

normálformák

egyed / entitás
rekord - sor
mező - oszlop

WHERE - egyetlen feltétel alapján keresés
WHERE IN - csoportos keresésnél

grant all privileges on `magyar\_%`.* to 'magyar'@'localhost' identified  by 'mark';

-user -host -password
mysql -u magyar -h 172.16.16.148 -p

adatbázis lekérdezések:
show databases;
use magyar_tesztauzem;

tesztauzem kategoriak szerkesztése

megoldas.sql


TRUNCATE TABLE táblanév;  --  törli a tábla tartalmát - nem jegyzi meg az id-ket

export  --  mysqldump -u <felhasználónév> -p <database neve> > <új file név + formátum>
import  --  mysql -u magyar -p magyar_pasta_company < magyar_pasta_company.sql


2026-09-15

magyar_education_te

50-60 megfelelt
60-80 átlagos
80- kiváló

Triggerek
before - after

show triggers;

