
#Go patikasi sql 8.odev

###SORU1 test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE TABLE employee(
id INTEGER PRIMARY KEY ,
name VARCHAR(50)	NOT NULL,
birthday DATE,
email VARCHAR(100)
);
###Soru2Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim

insert into author (id, first_name, last_name, email, birthday) values (1, 'Clarice', 'Rallin', 'crallin0@usda.gov', '1995-10-13');
insert into author (id, first_name, last_name, email, birthday) values (2, 'Bathsheba', 'Dumphry', 'bdumphry1@cyberchimps.com', '1978-08-06');
insert into author (id, first_name, last_name, email, birthday) values (3, 'Chelsae', 'Burrass', 'cburrass2@yellowbook.com', '2017-11-05');
insert into author (id, first_name, last_name, email, birthday) values (4, 'Rosemarie', 'Witchalls', 'rwitchalls3@nsw.gov.au', '1926-08-31');
insert into author (id, first_name, last_name, email, birthday) values (5, 'Adair', 'Overpool', 'aoverpool4@purevolume.com', '2018-11-04');
insert into author (id, first_name, last_name, email, birthday) values (6, 'Caril', 'Boscher', 'cboscher5@webmd.com', '1968-03-17');
insert into author (id, first_name, last_name, email, birthday) values (7, 'Fayina', 'Waistall', 'fwaistall6@usatoday.com', null);
insert into author (id, first_name, last_name, email, birthday) values (8, 'Kimberli', 'Manuele', 'kmanuele7@nasa.gov', '1946-08-23');
insert into author (id, first_name, last_name, email, birthday) values (9, 'Sibilla', 'Curnokk', 'scurnokk8@ebay.com', '1914-10-20');
insert into author (id, first_name, last_name, email, birthday) values (10, 'Tate', 'Sparsholt', 'tsparsholt9@oracle.com', '2019-03-05');
insert into author (id, first_name, last_name, email, birthday) values (11, 'Clareta', 'Snoxell', 'csnoxella@sfgate.com', '1972-06-04');
insert into author (id, first_name, last_name, email, birthday) values (12, 'Quintina', 'Glasman', 'qglasmanb@tinypic.com', null);
insert into author (id, first_name, last_name, email, birthday) values (13, 'Romain', 'Kop', 'rkopc@sohu.com', '1967-01-22');
insert into author (id, first_name, last_name, email, birthday) values (14, 'Pearla', null, 'pangroved@latimes.com', '1917-01-11');
insert into author (id, first_name, last_name, email, birthday) values (15, 'Ugo', 'Gillino', 'ugillinoe@purevolume.com', '1951-11-16');
insert into author (id, first_name, last_name, email, birthday) values (16, 'Birgitta', 'Hassall', 'bhassallf@china.com.cn', null);
insert into author (id, first_name, last_name, email, birthday) values (17, 'Francine', 'Barukh', 'fbarukhg@macromedia.com', '2016-02-07');
insert into author (id, first_name, last_name, email, birthday) values (18, 'Cort', 'Crockford', 'ccrockfordh@vk.com', '1992-03-04');
insert into author (id, first_name, last_name, email, birthday) values (19, 'Berkly', 'Chetter', 'bchetteri@google.es', '2020-06-22');
insert into author (id, first_name, last_name, email, birthday) values (20, 'Karilynn', 'Grist', 'kgristj@mayoclinic.com', '2019-09-25');
insert into author (id, first_name, last_name, email, birthday) values (21, 'Beatriz', null, 'bribyk@github.io', '1969-01-16');
insert into author (id, first_name, last_name, email, birthday) values (22, 'Yolanda', null, 'yjedrzejewskyl@ow.ly', '1941-11-08');
insert into author (id, first_name, last_name, email, birthday) values (23, 'Giorgio', 'Sans', 'gsansm@psu.edu', '1920-11-10');
insert into author (id, first_name, last_name, email, birthday) values (24, 'Tressa', 'Buscher', 'tbuschern@imdb.com', '1961-11-03');
insert into author (id, first_name, last_name, email, birthday) values (25, 'Lorry', 'Sidney', 'lsidneyo@seesaa.net', '1925-08-13');
insert into author (id, first_name, last_name, email, birthday) values (26, 'Jami', 'Giottini', 'jgiottinip@wikimedia.org', '1946-04-05');
insert into author (id, first_name, last_name, email, birthday) values (27, 'Ariadne', 'Beavan', 'abeavanq@odnoklassniki.ru', '2021-09-22');
insert into author (id, first_name, last_name, email, birthday) values (28, 'Camella', 'Luxen', 'cluxenr@china.com.cn', '1998-03-21');
insert into author (id, first_name, last_name, email, birthday) values (29, 'Bessy', null, 'bkilshaws@geocities.com', '1906-05-12');
insert into author (id, first_name, last_name, email, birthday) values (30, 'Correna', 'Dyter', 'cdytert@squarespace.com', '1991-02-06');
insert into author (id, first_name, last_name, email, birthday) values (31, 'Dex', 'Slamaker', 'dslamakeru@163.com', null);
insert into author (id, first_name, last_name, email, birthday) values (32, 'Vickie', 'Derricoat', 'vderricoatv@nytimes.com', '1923-05-07');
insert into author (id, first_name, last_name, email, birthday) values (33, 'Mirabella', null, 'mkitchinghamw@admin.ch', null);
insert into author (id, first_name, last_name, email, birthday) values (34, 'Sidoney', 'Di Pietro', 'sdipietrox@webeden.co.uk', '1943-05-07');
insert into author (id, first_name, last_name, email, birthday) values (35, 'Stacy', 'Gawkroge', 'sgawkrogey@hhs.gov', '1982-04-10');
insert into author (id, first_name, last_name, email, birthday) values (36, 'Clementina', 'Lewington', 'clewingtonz@multiply.com', '1999-11-21');
insert into author (id, first_name, last_name, email, birthday) values (37, 'Clio', null, 'ctreweke10@elpais.com', '1905-11-05');
insert into author (id, first_name, last_name, email, birthday) values (38, 'Walton', 'Cliburn', 'wcliburn11@de.vu', '1993-08-23');
insert into author (id, first_name, last_name, email, birthday) values (39, 'Melvyn', 'Creese', 'mcreese12@nps.gov', '2003-12-07');
insert into author (id, first_name, last_name, email, birthday) values (40, 'Frederic', 'Winning', 'fwinning13@sohu.com', '1972-05-07');
insert into author (id, first_name, last_name, email, birthday) values (41, 'Prentice', 'Clarkson', 'pclarkson14@wiley.com', '1916-12-28');
insert into author (id, first_name, last_name, email, birthday) values (42, 'Lauren', 'Padley', 'lpadley15@reddit.com', null);
insert into author (id, first_name, last_name, email, birthday) values (43, 'Wayland', 'MacGill', 'wmacgill16@theatlantic.com', '1990-02-10');
insert into author (id, first_name, last_name, email, birthday) values (44, 'Teddy', 'Tortoishell', 'ttortoishell17@sfgate.com', '1903-03-11');
insert into author (id, first_name, last_name, email, birthday) values (45, 'Annabela', 'Desforges', 'adesforges18@illinois.edu', '2007-11-24');
insert into author (id, first_name, last_name, email, birthday) values (46, 'Nikolai', 'Imason', 'nimason19@digg.com', '1939-07-03');
insert into author (id, first_name, last_name, email, birthday) values (47, 'Calla', 'Pegden', 'cpegden1a@vkontakte.ru', '1936-02-21');
insert into author (id, first_name, last_name, email, birthday) values (48, 'Leopold', 'Gosneye', 'lgosneye1b@psu.edu', '1900-05-27');
insert into author (id, first_name, last_name, email, birthday) values (49, 'Alane', null, 'ayerrell1c@clickbank.net', '1951-12-23');
insert into author (id, first_name, last_name, email, birthday) values (50, 'Thornie', 'Frediani', 'tfrediani1d@hud.gov', '1981-11-05');

###Soru3Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee
SET  name = 'Ebrar Altunkynk',
     birthday= '1996-09-07',
	 email = 'ebraraltunkynk@gmail.com'
	 where id=7;
###Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee
WHERE id = 7;
DELETE FROM employee
WHERE id = 8;
DELETE FROM employee
WHERE id = 9;
DELETE FROM employee
WHERE id = 1;
DELETE FROM employee
WHERE id = 13;
