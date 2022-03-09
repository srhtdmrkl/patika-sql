1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
> CREATE TABLE employee (
>   id INTEGER,
>   name VARCHAR(50),
>   birthday DATE,
>   email VARCHAR(100)
> );
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
> insert into employee (id, name, birthday, email) values (1, 'Irwin Shellard', '09/01/1982', 'ishellard0@java.com');
> insert into employee (id, name, birthday, email) values (2, 'Yolanda Cramer', '16/11/1995', 'ycramer1@ox.ac.uk');
> insert into employee (id, name, birthday, email) values (3, 'Burnaby Montgomery', '24/11/1980', 'bmontgomery2@gravatar.com');
> insert into employee (id, name, birthday, email) values (4, 'Caterina Clawe', '01/03/1993', 'cclawe3@behance.net');
> insert into employee (id, name, birthday, email) values (5, 'Zared Clench', '02/03/1989', 'zclench4@booking.com');
> insert into employee (id, name, birthday, email) values (6, 'Georas Twiddle', '15/07/1987', 'gtwiddle5@spiegel.de');
> insert into employee (id, name, birthday, email) values (7, 'Mabel Sutty', '02/05/1996', 'msutty6@miibeian.gov.cn');
> insert into employee (id, name, birthday, email) values (8, 'Rosalinda Paolinelli', '18/02/1983', 'rpaolinelli7@washington.edu');
> insert into employee (id, name, birthday, email) values (9, 'Meridith Isacsson', '24/11/1984', 'misacsson8@adobe.com');
> insert into employee (id, name, birthday, email) values (10, 'Quinn Woolens', '11/07/1981', 'qwoolens9@sitemeter.com');
> insert into employee (id, name, birthday, email) values (11, 'Netta Besnard', '04/11/1998', 'nbesnarda@fastcompany.com');
> insert into employee (id, name, birthday, email) values (12, 'Conny Sweeting', '07/02/2000', 'csweetingb@usda.gov');
> insert into employee (id, name, birthday, email) values (13, 'Lesley Seaking', '22/10/1989', 'lseakingc@dot.gov');
> insert into employee (id, name, birthday, email) values (14, 'Cort Jurek', '05/09/1991', 'cjurekd@1688.com');
> insert into employee (id, name, birthday, email) values (15, 'Mellie Shekle', '29/10/1981', 'msheklee@twitter.com');
> insert into employee (id, name, birthday, email) values (16, 'Micky Stonnell', '20/07/1998', 'mstonnellf@youtube.com');
> insert into employee (id, name, birthday, email) values (17, 'Inger Jeannard', '15/10/1985', 'ijeannardg@addtoany.com');
> insert into employee (id, name, birthday, email) values (18, 'Lizbeth Bredbury', '21/08/1985', 'lbredburyh@alexa.com');
> insert into employee (id, name, birthday, email) values (19, 'Gweneth Bentham3', '16/11/1995', 'gbenthami@deliciousdays.com');
> insert into employee (id, name, birthday, email) values (20, 'Mead Bohills', '27/12/1994', 'mbohillsj@nsw.gov.au');
> insert into employee (id, name, birthday, email) values (21, 'Alon Itzkovwitch', '30/01/1990', 'aitzkovwitchk@timesonline.co.uk');
> insert into employee (id, name, birthday, email) values (22, 'Garek Lehrian', '04/04/1990', 'glehrianl@loc.gov');
> insert into employee (id, name, birthday, email) values (23, 'Lotta Bruneau', '05/11/1985', 'lbruneaum@netvibes.com');
> insert into employee (id, name, birthday, email) values (24, 'Conn Burd', '03/01/1992', 'cburdn@digg.com');
> insert into employee (id, name, birthday, email) values (25, 'Edy Paff', '14/10/1996', 'epaffo@illinois.edu');
> insert into employee (id, name, birthday, email) values (26, 'Laureen Clear', '26/10/1991', 'lclearp@google.co.uk');
> insert into employee (id, name, birthday, email) values (27, 'Wendeline Ouldred', '23/07/1987', 'wouldredq@nytimes.com');
> insert into employee (id, name, birthday, email) values (28, 'Isabel Kirkebye', '10/03/1989', 'ikirkebyer@canalblog.com');
> insert into employee (id, name, birthday, email) values (29, 'Skyler Mioni', '23/06/1980', 'smionis@jimdo.com');
> insert into employee (id, name, birthday, email) values (30, 'Therine Blenkinsopp', '24/10/1991', 'tblenkinsoppt@drupal.org');
> insert into employee (id, name, birthday, email) values (31, 'Sandy Graddell', '03/10/1985', 'sgraddellu@instagram.com');
> insert into employee (id, name, birthday, email) values (32, 'Piper Schiell', '26/06/1982', 'pschiellv@columbia.edu');
> insert into employee (id, name, birthday, email) values (33, 'Staci Taylerson', '04/12/1996', 'staylersonw@opera.com');
> insert into employee (id, name, birthday, email) values (34, 'Curt Clemendot', '23/07/1997', 'cclemendotx@princeton.edu');
> insert into employee (id, name, birthday, email) values (35, 'Marty Goodlip', '10/05/1982', 'mgoodlipy@wikipedia.org');
> insert into employee (id, name, birthday, email) values (36, 'Jamill Risbridge', '02/06/1998', 'jrisbridgez@chronoengine.com');
> insert into employee (id, name, birthday, email) values (37, 'Elfrieda Gibard', '01/04/1995', 'egibard10@yahoo.co.jp');
> insert into employee (id, name, birthday, email) values (38, 'Rosella Vannah', '07/05/1984', 'rvannah11@sun.com');
> insert into employee (id, name, birthday, email) values (39, 'Lorette Lyes', '24/02/1992', 'llyes12@discovery.com');
> insert into employee (id, name, birthday, email) values (40, 'Michale Doward', '03/12/1985', 'mdoward13@dell.com');
> insert into employee (id, name, birthday, email) values (41, 'Rina Noad', '14/07/1980', 'rnoad14@zdnet.com');
> insert into employee (id, name, birthday, email) values (42, 'Lara Blackwell', '26/06/1981', 'lblackwell15@state.tx.us');
> insert into employee (id, name, birthday, email) values (43, 'Dorisa Ferreli', '21/12/1982', 'dferreli16@networksolutions.com');
> insert into employee (id, name, birthday, email) values (44, 'Leland Paaso', '16/09/1981', 'lpaaso17@google.pl');
> insert into employee (id, name, birthday, email) values (45, 'Jarid Gillopp', '07/05/1984', 'jgillopp18@ucsd.edu');
> insert into employee (id, name, birthday, email) values (46, 'Barnabas McAlindon', '24/01/1992', 'bmcalindon19@omniture.com');
> insert into employee (id, name, birthday, email) values (47, 'Gerhard Orwin', '09/08/1983', 'gorwin1a@unblog.fr');
> insert into employee (id, name, birthday, email) values (48, 'Mattie Gillingwater', '12/03/1989', 'mgillingwater1b@intel.com');
> insert into employee (id, name, birthday, email) values (49, 'Rog Daltry', '01/10/1986', 'rdaltry1c@bloomberg.com');
> insert into employee (id, name, birthday, email) values (50, 'Violet Grishukhin', '18/12/1996', 'vgrishukhin1d@barnesandnoble.com');

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
> UPDATE employee 
> SET name = 'Menekşe Grishukhin',
> SET birthday = '18/12/1995',
> SET email = 'menekse@barnesandnoble.com'
> WHERE id = 50;

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
> DELETE FROM employee
> WHERE name LIKE 'L%';
