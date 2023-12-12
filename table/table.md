- tablo oluşturmak
```
CREATE TABLE <tablo_adı> (
    <sütun_adı> <veri_tip> (kısıtlama_adı>,
    <sütun_adı> <veri_tip> (kısıtlama_adı>,
   ....
);
```
- update
```
UPDATE <tablo_adı>
SET <sütun_adı> = değer, 
    <sütun_adı> = değer,
    ----
WHERE <koşul_adı>;
```
- NOT NULL Kullanımı
```
CREATE TABLE Employees (     id SERIAL PRIMARY KEY,
    first_name VARCHAR(100) NOT NULL,
    last_name VARCHAR(100) NOT NULL,
    age INTEGER
);
```
- ALTER ve NOT NULL
```
ALTER TABLE <tablo_adı> ALTER COLUMN <sütun_adı>
SET NOT NULL;
```
- UNIQUE Kullanımı
```
CREATE TABLE Employees (     ---
    emaile VARCHAR(100) UNIQUE,
    ----
);
```
- ALTER ve UNIQUE
```
ALTER TABLE <tablo_adı> ADD UNIQUE <sütun_adı>
```
