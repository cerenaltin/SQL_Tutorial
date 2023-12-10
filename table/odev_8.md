- Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee (
    id INTEGER PRIMARY KEY,
    name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)   
);
```
- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, birthday, email) values (1, 'Otho Bungey', '1989-12-09', 'obungey0@gravatar.com');
insert into employee (id, name, birthday, email) values (2, 'Susi Muscott', '1986-09-04', 'smuscott1@hugedomains.com');
insert into employee (id, name, birthday, email) values (3, 'Sissy Belison', '1987-01-08', 'sbelison2@dell.com');
insert into employee (id, name, birthday, email) values (4, 'Mateo Menis', '1989-05-31', 'mmenis3@addthis.com');
insert into employee (id, name, birthday, email) values (5, 'Patience Chillingsworth', '1987-04-26', 'pchillingsworth4@vinaora.com');
insert into employee (id, name, birthday, email) values (6, 'Nichol Mowling', '1988-06-23', 'nmowling5@privacy.gov.au');
insert into employee (id, name, birthday, email) values (7, 'Arielle Dolton', '1987-02-19', 'adolton6@webeden.co.uk');
insert into employee (id, name, birthday, email) values (8, 'Aldous Trewartha', '1985-07-26', 'atrewartha7@skype.com');
insert into employee (id, name, birthday, email) values (9, 'Phaedra Douty', '1996-03-02', 'pdouty8@usatoday.com');
insert into employee (id, name, birthday, email) values (10, 'Gav Ginty', '1999-09-08', 'gginty9@intel.com');
insert into employee (id, name, birthday, email) values (11, 'Niko Heyburn', '1989-10-03', 'nheyburna@parallels.com');
insert into employee (id, name, birthday, email) values (12, 'Maudie Quartley', '1998-04-27', 'mquartleyb@jiathis.com');
insert into employee (id, name, birthday, email) values (13, 'Engracia Ferriby', '1982-08-01', 'eferribyc@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (14, 'Anya Grigolashvill', '1991-05-12', 'agrigolashvilld@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (15, 'Audy Barkly', '1998-08-29', 'abarklye@livejournal.com');
insert into employee (id, name, birthday, email) values (16, 'Izzy Ledwith', '1998-08-19', 'iledwithf@unc.edu');
insert into employee (id, name, birthday, email) values (17, 'Dur Eary', '1998-05-15', 'dearyg@ustream.tv');
insert into employee (id, name, birthday, email) values (18, 'Roby Born', '1995-11-29', 'rbornh@nih.gov');
insert into employee (id, name, birthday, email) values (19, 'Sallyann Campana', '1986-04-24', 'scampanai@answers.com');
insert into employee (id, name, birthday, email) values (20, 'Allie Pepper', '1991-08-11', 'apepperj@scribd.com');
insert into employee (id, name, birthday, email) values (21, 'Arne Ickovitz', '1987-03-29', 'aickovitzk@mit.edu');
insert into employee (id, name, birthday, email) values (22, 'Rutherford Laws', '1996-04-28', 'rlawsl@admin.ch');
insert into employee (id, name, birthday, email) values (23, 'Anna-diane Jurczik', '1989-04-19', 'ajurczikm@google.it');
insert into employee (id, name, birthday, email) values (24, 'Sergei Mulvenna', '2000-05-10', 'smulvennan@bizjournals.com');
insert into employee (id, name, birthday, email) values (25, 'Lynette Yeaman', '1997-11-03', 'lyeamano@census.gov');
insert into employee (id, name, birthday, email) values (26, 'Natal Grafhom', '1984-06-25', 'ngrafhomp@icio.us');
insert into employee (id, name, birthday, email) values (27, 'Laney Vanyashin', '1991-09-04', 'lvanyashinq@phpbb.com');
insert into employee (id, name, birthday, email) values (28, 'Waldemar Delafont', '1986-12-10', 'wdelafontr@github.io');
insert into employee (id, name, birthday, email) values (29, 'Nichol Mowlam', '1995-01-31', 'nmowlams@accuweather.com');
insert into employee (id, name, birthday, email) values (30, 'Mamie Toomey', '1988-06-03', 'mtoomeyt@buzzfeed.com');
insert into employee (id, name, birthday, email) values (31, 'Nigel Warner', '1990-02-24', 'nwarneru@stumbleupon.com');
insert into employee (id, name, birthday, email) values (32, 'Lauree Wem', '2000-05-21', 'lwemv@discuz.net');
insert into employee (id, name, birthday, email) values (33, 'Dulcie Franses', '1989-01-31', 'dfransesw@hexun.com');
insert into employee (id, name, birthday, email) values (34, 'Shep Fieldhouse', '1987-12-31', 'sfieldhousex@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (35, 'Husein Sheldrake', '1992-03-13', 'hsheldrakey@lulu.com');
insert into employee (id, name, birthday, email) values (36, 'Tierney Hillitt', '2000-01-03', 'thillittz@cbsnews.com');
insert into employee (id, name, birthday, email) values (37, 'Garvin Brownsworth', '1983-11-29', 'gbrownsworth10@reuters.com');
insert into employee (id, name, birthday, email) values (38, 'Xavier Birdseye', '1984-08-23', 'xbirdseye11@webs.com');
insert into employee (id, name, birthday, email) values (39, 'Cloe Hibbart', '1991-02-22', 'chibbart12@nps.gov');
insert into employee (id, name, birthday, email) values (40, 'Corinna Ryal', '1983-08-04', 'cryal13@php.net');
insert into employee (id, name, birthday, email) values (41, 'Alys Bassindale', '1984-01-24', 'abassindale14@nsw.gov.au');
insert into employee (id, name, birthday, email) values (42, 'Brnaby Callander', '1997-09-25', 'bcallander15@simplemachines.org');
insert into employee (id, name, birthday, email) values (43, 'Ruy Dowe', '1996-09-19', 'rdowe16@tuttocitta.it');
insert into employee (id, name, birthday, email) values (44, 'Cindy Wollard', '1998-08-01', 'cwollard17@wiley.com');
insert into employee (id, name, birthday, email) values (45, 'Dorelia Marsland', '1986-09-06', 'dmarsland18@wikipedia.org');
insert into employee (id, name, birthday, email) values (46, 'Joanne Poynzer', '1981-05-06', 'jpoynzer19@yandex.ru');
insert into employee (id, name, birthday, email) values (47, 'Lyle Look', '1982-11-16', 'llook1a@businessweek.com');
insert into employee (id, name, birthday, email) values (48, 'Stace Grim', '1990-05-03', 'sgrim1b@theguardian.com');
insert into employee (id, name, birthday, email) values (49, 'Jed Piel', '1998-07-24', 'jpiel1c@yahoo.com');
insert into employee (id, name, birthday, email) values (50, 'Stavros Jephcott', '1999-10-23', 'sjephcott1d@list-manage.com');

```
- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'xxx'  
WHERE id <=5;
```
- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE id <=5;
```
