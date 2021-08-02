# Ödev8
#### 1. Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee  (
id INTEGER,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
);
```
#### 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, email, birthday) values (1, 'Matthus', 'mstartin0@netlog.com', '1987-04-28');
insert into employee (id, name, email, birthday) values (2, 'Evvie', 'egerald1@sohu.com', '2000-11-02');
insert into employee (id, name, email, birthday) values (3, 'Locke', 'lhugonnet2@redcross.org', '1909-01-05');
insert into employee (id, name, email, birthday) values (4, 'Allissa', 'aeliff3@furl.net', '1930-05-31');
insert into employee (id, name, email, birthday) values (5, 'Marchall', 'mbrumpton4@cbsnews.com', '1986-08-16');
insert into employee (id, name, email, birthday) values (6, 'Frannie', 'fmccrainor5@wikia.com', '1920-08-30');
insert into employee (id, name, email, birthday) values (7, 'Stefania', 'sgreated6@pagesperso-orange.fr', '1960-12-01');
insert into employee (id, name, email, birthday) values (8, 'Teodoro', 'tbalsdone7@buzzfeed.com', '1904-06-01');
insert into employee (id, name, email, birthday) values (9, 'Scarlett', 'ssegge8@woothemes.com', '2000-02-05');
insert into employee (id, name, email, birthday) values (10, 'Maryanna', 'mfarryann9@techcrunch.com', '2014-06-18');
insert into employee (id, name, email, birthday) values (11, 'Wilmer', 'wsteffensa@is.gd', '1915-12-05');
insert into employee (id, name, email, birthday) values (12, 'Shea', 'smacguiganb@google.pl', '1994-12-19');
insert into employee (id, name, email, birthday) values (13, 'Malvin', 'mfawthorpec@uiuc.edu', '1961-07-08');
insert into employee (id, name, email, birthday) values (14, 'Ody', 'olondingd@netscape.com', '1933-09-21');
insert into employee (id, name, email, birthday) values (15, 'Lindy', 'lbollarde@wisc.edu', '1950-10-17');
insert into employee (id, name, email, birthday) values (16, 'Livy', 'lechlinf@cargocollective.com', '1979-10-17');
insert into employee (id, name, email, birthday) values (17, 'Jeane', 'jdumberellg@oracle.com', '2021-03-26');
insert into employee (id, name, email, birthday) values (18, 'Marisa', 'mpeachh@springer.com', '1905-07-12');
insert into employee (id, name, email, birthday) values (19, 'Raynor', 'rmcilvennyi@lycos.com', '2012-05-06');
insert into employee (id, name, email, birthday) values (20, 'Charley', 'cglasscooj@typepad.com', '1929-06-12');
insert into employee (id, name, email, birthday) values (21, 'Antonietta', 'ajerdonk@forbes.com', '1970-07-29');
insert into employee (id, name, email, birthday) values (22, 'Myrah', 'mbandeyl@wsj.com', '1934-02-15');
insert into employee (id, name, email, birthday) values (23, 'Drud', 'dchealesm@imageshack.us', '1989-04-18');
insert into employee (id, name, email, birthday) values (24, 'Katrinka', 'kcroncheyn@bbb.org', '1950-03-31');
insert into employee (id, name, email, birthday) values (25, 'Neale', 'nexono@hexun.com', '1972-09-13');
insert into employee (id, name, email, birthday) values (26, 'Meryl', 'mmackaigp@netvibes.com', '1945-09-09');
insert into employee (id, name, email, birthday) values (27, 'Lavina', 'lcadoreq@bizjournals.com', '1968-08-04');
insert into employee (id, name, email, birthday) values (28, 'Patti', 'pseldnerr@printfriendly.com', '2004-10-20');
insert into employee (id, name, email, birthday) values (29, 'Hadria', 'hmulmurays@yandex.ru', '1938-08-21');
insert into employee (id, name, email, birthday) values (30, 'Connie', 'cmorguet@mac.com', '1927-08-23');
insert into employee (id, name, email, birthday) values (31, 'Madlin', 'mwederellu@foxnews.com', '2012-04-09');
insert into employee (id, name, email, birthday) values (32, 'Ellwood', 'emacfadinv@chicagotribune.com', '1962-06-11');
insert into employee (id, name, email, birthday) values (33, 'Garrard', 'gradenw@wix.com', '2002-01-21');
insert into employee (id, name, email, birthday) values (34, 'Donni', 'dgodferyx@vinaora.com', '1934-03-23');
insert into employee (id, name, email, birthday) values (35, 'Michail', 'mcastelainy@walmart.com', '1928-10-24');
insert into employee (id, name, email, birthday) values (36, 'Curr', 'cfinnesz@flickr.com', '1970-04-09');
insert into employee (id, name, email, birthday) values (37, 'Julio', 'jsymmers10@pen.io', '1995-12-01');
insert into employee (id, name, email, birthday) values (38, 'Amye', 'atregidgo11@xrea.com', '2019-08-10');
insert into employee (id, name, email, birthday) values (39, 'Donielle', 'dcrocker12@slideshare.net', '1929-10-27');
insert into employee (id, name, email, birthday) values (40, 'Debera', 'dramiro13@meetup.com', '2021-01-04');
insert into employee (id, name, email, birthday) values (41, 'Pip', 'pmarcinkus14@irs.gov', '1916-06-09');
insert into employee (id, name, email, birthday) values (42, 'Dirk', 'dgadie15@msu.edu', '2014-05-02');
insert into employee (id, name, email, birthday) values (43, 'Wynn', 'wbraune16@sitemeter.com', '2004-08-25');
insert into employee (id, name, email, birthday) values (44, 'Tyrus', 'thamblington17@oaic.gov.au', '1928-03-16');
insert into employee (id, name, email, birthday) values (45, 'John', 'jlarenson18@comsenz.com', '1916-08-26');
insert into employee (id, name, email, birthday) values (46, 'Noel', 'nhallgalley19@facebook.com', '1994-08-13');
insert into employee (id, name, email, birthday) values (47, 'Jacquenetta', 'jkynoch1a@github.io', '1919-10-19');
insert into employee (id, name, email, birthday) values (48, 'Meggie', 'mkrahl1b@feedburner.com', '1939-03-17');
insert into employee (id, name, email, birthday) values (49, 'Randall', 'rbigrigg1c@trellian.com', '1924-05-07');
insert into employee (id, name, email, birthday) values (50, 'Minnnie', 'mbrose1d@chronoengine.com', '2013-10-18');
```
#### 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
SET name = 'Ahmet',
	birthday = '1990-01-01',
	email = 'ahmet@gmail.com'
WHERE id = 1;


UPDATE employee
SET id = '51',
	birthday = '1990-01-01',
	email = 'ahmet@gmail.com'
WHERE name = 'Evvie';

UPDATE employee
SET id = '52',
	name = 'ahmet',
	email = 'ahmet@gmail.com'
WHERE birthday = '1909-01-05';

UPDATE employee
SET id = '53',
	name = 'ahmet',
	birthday = '1990-01-01'
WHERE email = 'aeliff3@furl.net';

UPDATE employee
SET id = '54',
	name = 'ahmet',
	birthday = '1990-01-01'
WHERE email = 'mbrumpton4@cbsnews.com';
```
#### 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE id = 1;

DELETE FROM employee
WHERE name = 'ahmet'
RETURNING *;

DELETE FROM employee
WHERE birthday = '1990-01-01'
RETURNING *;

DELETE FROM employee
WHERE email LIKE 'a%' 
RETURNING *;

DELETE FROM employee
WHERE name ILIKE '%a' 
RETURNING *;

```
