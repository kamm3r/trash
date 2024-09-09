# Relaatiotietokanta Tehtävät

## 1 Relaatiotietokannan peruskäsitteiden harjoitukset

### 1.1
```
Kuinka monta taulua alla olevan relaatiomallin mukaisessa tietokannassa on?

vastaus: 5
```
![sql kommennon vastaus](kuva.png)

### 1.2
```
Katso alla olevaa relaatio-mallia. Kuinka monta saraketta taulussa country on?

vastaus: 5
```
![sql kommennon vastaus](kuva.png)

### 1.3
```
Katso alla olevaa relaatio-mallia. Mikä on taulun airport pääavainkentän nimi?

vastaus: ident
```
![sql kommennon vastaus](kuva.png)

### 1.4
```
Avaa Moodlesta (Viikko 1 kohdalla) löytyvä airports.csv-tiedosto Notepad++:lla
(älä avaa Excelillä, Excel saattaa tehdä muutoksia, jotka haittaavat
seuraavissa työvaiheissa). Mikä tietotyyppi sopisi
airport-taulun pääavainkenttään?

vastaus: id
```
![sql kommennon vastaus](kuva.png)

### 1.5
```
Katso alla olevaa relaatio-mallia. Minkä niminen vierasavainkenttä
airport-taulussa on?

vastaus: iso_country
```
![sql kommennon vastaus](kuva.png)

### 1.6
```
Katso alla olevaa relaatiomallia. Minkä nimiseen tauluun airport-taulun
vierasavainkenttä osoittaa?

vastaus: country
```
![sql kommennon vastaus](kuva.png)

### 1.7
```
Katso alla olevaa relaatiomallia. Minkä nimiseen kenttään airport-taulun
vierasavainkenttä osoittaa?

vastaus: country
```
![sql kommennon vastaus](kuva.png)

### 1.8
```
Kurkista taas airports.csv-tiedostoon. Mikä tietotyyppi sopisi
airport-taulun vierasavainkenttään?

vastaus: ei mikään, koska siinä on vain yksi taulu, mutta edellisen
tehtävän diagram perustella iso_country
```
![sql kommennon vastaus](kuva.png)

### 1.9
```
Airport-tauluun tullaan myöhemmin importoimaan data airports.csv-tiedostosta.
Kurkista taas airports.csv-tiedostoon. Kuinka monta tietuetta eli riviä
dataa meillä tulee olemaan airport-taulussa?

vastaus: 18
```
![sql kommennon vastaus](kuva.png)

### 1.10
```
Katso alla olevaa relaatiomallia. Mikä on taulun country pääavain kentän nimi?

vastaus: ident
```
![sql kommennon vastaus](kuva.png)

### 1.11
```
Tehtävissä 6 ja 7 kerroit, että airport-taulun vierasavain osoittaa
country-taulun pääavaimeen. Tehtävässä 8 päättelit csv-tiedoston perusteella
airport-taulun vierasavainkentän tietotyypin. Edeltävän perusteella tiedät
country-taulun pääavainkentän tietotyypin. Mikä se on?

vastaus: varchar jokun pituinen 255, mutta yleiseti ottaen kannataisi
mielummin olla CUID, UUID tai pelkä autoincrement id(0,1,...)
```
![sql kommennon vastaus](kuva.png)

### 1.12
```
Avaa Moodlesta löytyvä countries.csv-tiedosto Notepad++:lla (älä avaa
Excelillä, Excel saattaa tehdä muutoksia, jotka haittaavat seuraavissa
työvaiheissa). Kuinka monta tietutetta eli riviä dataa
meillä tulee olemaan country-taulussa?

vastaus: 6
```
![sql kommennon vastaus](kuva.png)

### 1.13
```
Katso alla olevaa taulun goal data-sisältö kuvaa ja relaatiomallia.
Minkä nimisessä taulussa on kuvaus eri säätiloista?

vastaus: goal
```
![sql kommennon vastaus](kuva.png)

### 1.14
```
Katso alla olevaa kuvaa taulun goal data-sisällöstä. Minkä niminen on säätila,
jonka kuvauksessa sanotaan, että sää on tasan 0-asetta.

vastaus: 0DEG
```
![sql kommennon vastaus](kuva.png)

### 1.15
```
Katso alla olevaa relaatiomallia. Minkä niminen on goal-taulun pääavainkenttä?

vastaus: id
```
![sql kommennon vastaus](kuva.png)

### 1.16
```
Katso alla olevaa relaatio-mallia. Onko goal-taulussa vierasavainta?

vastaus: epätosi
```
![sql kommennon vastaus](kuva.png)

### 1.17
```
Katso alla olevaa relaatio-mallia. Minkä nimisessä taulussa
pidetään yllä pelaajan nimimerkkiä?

vastaus: game
```
![sql kommennon vastaus](kuva.png)

### 1.18
```
Katso alla olevaa relaatiomallia. Minkä nimisessä taulussa
ylläpidetään kokonaisbudjettia CO2-päästöille?

vastaus: game
```
![sql kommennon vastaus](kuva.png)

### 1.19
```
Katso allaolevaa relaatio-mallia. Minkä nimisessä taulussa ylläpidetään
pelaajan kuluttamaa CO2 päästöä?

vastaus: game
```
![sql kommennon vastaus](kuva.png)

### 1.20
```
Katso alla olevaa relaatiomallia. Minkä nimisessä taulussa ylläpidetään
tietoa siitä missä pelaaja sijaitsee?

vastaus: airport
```
![sql kommennon vastaus](kuva.png)

### 1.21
```
Katso alla olevaa relaatio-mallia. Minkä niminen on game-taulun pääavain?

vastaus: id
```
![sql kommennon vastaus](kuva.png)

### 1.22
```
Katso alla olevaa relaatio-mallia.
Minkä niminen on game-taulun vierasavainkenttä?

vastaus: location
```
![sql kommennon vastaus](kuva.png)

### 1.23
```
Katso alla olevaa olevaa relaatio-mallia. Minkä nimisessä taulussa ylläpidetään
tietoa siitä, mitkä tavoitelluista säätiloista ovat
missäkin peli-sessiossa tavoitettu?

vastaus: goal_reached
```
![sql kommennon vastaus](kuva.png)

### 1.24
```
Katso alla olevaa relaatio-mallia. Kaksi eri kenttää yhdessä muodostavat
goal_reached-taulun pääavaimen. Mitkä nämä kentät ovat nimeltään?

Automaattitarkistuksen takia kirjoita kaaviossa oleva ensinmainittu kentän
nimi ensin vastaukseesi, sen jälkeen pilkku ja välilyönti,
lopuksi kaaviossa toisena mainittu kentän nimi.

vastaus: goal_id ja game_id
```
![sql kommennon vastaus](kuva.png)

### 1.25
```
Katso alla olevaa relaatio-mallia. Kuinka monta
vierasavainta on goal_reached-taulussa?

vastaus: 2
```
![sql kommennon vastaus](kuva.png)

## 2 Yhteen tauluun kohdistuvien kyselyiden harjoitukset

### 2.1
```sql
SELECT * FROM goal;
```
![sql kommennon vastaus](kuva.png)

### 2.2
```sql
SELECT name airport_type FROM airport WHERE iso_country='FI';
```
![sql kommennon vastaus](kuva.png)

### 2.3
```sql
SELECT name FROM airport WHERE iso_country='FI' ORDER BY name;
```
![sql kommennon vastaus](kuva.png)

### 2.4
```sql
SELECT name, type FROM airport WHERE iso_country = "FI" ORDER BY type, name;
```
![sql kommennon vastaus](kuva.png)

### 2.5
```sql
SELECT name FROM country WHERE name LIKE 'F%';
```
![sql kommennon vastaus](kuva.png)

### 2.6
```sql
SELECT name FROM country WHERE name LIKE '%F%';
```
![sql kommennon vastaus](kuva.png)

### 2.7
```sql
SELECT location FROM game WHERE screen_name='Vesa'
```
![sql kommennon vastaus](kuva.png)

### 2.8
```sql
SELECT co2_consumed FROM game WHERE screen_name='Ilkka';
```
![sql kommennon vastaus](kuva.png)

### 2.9
```sql
SELECT DISTINCT co2_budget FROM game;
```
![sql kommennon vastaus](kuva.png)

## 3 Where-osan liitosehto harjoitukset

### 3.1
```sql
SELECT country.name AS "country name", airport.name AS "airport name"
FROM airport, country
WHERE airport.iso_country = country.iso_country AND country.name = "Iceland";
```
![sql kommennon vastaus](kuva.png)

### 3.2
```sql
SELECT airport.name AS "airport name" FROM airport, country
WHERE airport.iso_country = country.iso_country
AND country.name = "France" AND airport.type = "large_airport";
```
![sql kommennon vastaus](kuva.png)

### 3.3
```sql
SELECT country.name AS country_name, airport.name AS airport_name
FROM airport, country
WHERE airport.iso_country = country.iso_country AND country.continent = "AN";
```
![sql kommennon vastaus](kuva.png)

### 3.4
```sql
SELECT elevation_ft FROM airport, game
WHERE location = ident AND screen_name = "Heini";
```
![sql kommennon vastaus](kuva.png)

### 3.5
```sql
SELECT elevation_ft * 0.3048 AS elevation_m FROM airport, game
WHERE location = ident AND screen_name = "Heini";
```
![sql kommennon vastaus](kuva.png)

### 3.6
```sql
SELECT name FROM airport, game
WHERE location = ident AND screen_name = "Ilkka";
```
![sql kommennon vastaus](kuva.png)

### 3.7
```sql
SELECT country.name FROM airport, game, country
WHERE location = ident
AND airport.iso_country = country.iso_country AND screen_name = "Ilkka";
```
![sql kommennon vastaus](kuva.png)

### 3.8
```sql
SELECT name FROM goal, goal_reached, game
WHERE game.id = game_id AND goal.id = goal_id AND screen_name = "Heini";
```
![sql kommennon vastaus](kuva.png)

### 3.9
```sql
SELECT airport.name FROM airport, game, goal, goal_reached
WHERE ident = location AND game.id = game_id
AND goal.id = goal_id AND screen_name = "Ilkka" AND goal.name = "CLOUDS";
```
![sql kommennon vastaus](kuva.png)

### 3.10
```sql
SELECT country.name FROM country, airport, game, goal, goal_reached
WHERE airport.iso_country = country.iso_country AND ident = location
AND game.id = game_id AND goal.id = goal_id
AND screen_name = "Ilkka" AND goal.name = "CLOUDS";
```
![sql kommennon vastaus](kuva.png)

## 4 Join harjoitukset

### 4.1
```sql
SELECT country.name AS "country name", airport.name AS "airport name"
FROM country INNER JOIN airport ON airport.iso_country = country.iso_country
WHERE country.name = "Finland" AND scheduled_service = "yes";
```
![sql kommennon vastaus](kuva.png)

### 4.2
```sql
SELECT screen_name, airport.name FROM game
INNER JOIN airport ON location = ident;
```
![sql kommennon vastaus](kuva.png)

### 4.3
```sql
SELECT screen_name, country.name FROM game
INNER JOIN airport ON location = ident
INNER JOIN country ON airport.iso_country = country.iso_country;
```
![sql kommennon vastaus](kuva.png)

### 4.4
```sql
SELECT airport.name, game.screen_name FROM airport
LEFT JOIN game ON airport.ident = game.location
WHERE airport.name LIKE '%Hels%';
```
![sql kommennon vastaus](kuva.png)

### 4.5
```sql
SELECT name, screen_name FROM goal
LEFT JOIN goal_reached ON goal.id = goal_id LEFT JOIN game ON game.id = game_id;
```
![sql kommennon vastaus](kuva.png)

## 5 Sisäkysely harjoitukset

### 5.1
```sql
SELECT name FROM country WHERE iso_country IN(
SELECT iso_country FROM airport WHERE name LIKE "Satsuma%");
```
![sql kommennon vastaus](kuva.png)

### 5.2
```sql
SELECT name FROM airport WHERE iso_country
IN(SELECT iso_country FROM country WHERE name = "Monaco");
```
![sql kommennon vastaus](kuva.png)

### 5.3
```sql
SELECT screen_name FROM game WHERE id IN(
SELECT game_id FROM goal_reached
WHERE goal_id IN(SELECT id FROM goal WHERE name = "CLOUDS"));
```
![sql kommennon vastaus](kuva.png)

### 5.4
```sql
SELECT country.name FROM country
WHERE iso_country NOT IN(SELECT airport.iso_country FROM airport);
```
![sql kommennon vastaus](kuva.png)

### 5.5
```sql
SELECT name FROM goal WHERE id
NOT IN(SELECT goal.id FROM goal, goal_reached, game
WHERE game.id = game_id AND goal.id = goal_id AND screen_name = "Heini");
```
![sql kommennon vastaus](kuva.png)

## 6 Koostetieto kyselyt harjoitukset

### 6.1
```sql
SELECT elevation_ft as "max elevation_ft" FROM airport
WHERE elevation_ft IN(SELECT MAX(elevation_ft) FROM airport);
```
![sql kommennon vastaus](kuva.png)

### 6.2
```sql
SELECT continent, COUNT(*) FROM country GROUP BY continent;
```
![sql kommennon vastaus](kuva.png)

### 6.3
```sql
SELECT screen_name, COUNT(*) FROM game, goal_reached
WHERE id = game_id GROUP BY screen_name;
```
![sql kommennon vastaus](kuva.png)

### 6.4
```sql
SELECT screen_name FROM game
WHERE co2_consumed IN(SELECT MIN(co2_consumed) FROM game);
```
![sql kommennon vastaus](kuva.png)

### 6.5
```sql
SELECT country.name, COUNT(*) FROM airport, country
WHERE airport.iso_country = country.iso_country
GROUP BY country.iso_country ORDER BY COUNT(*) desc LIMIT 50;
```
![sql kommennon vastaus](kuva.png)

### 6.6
```sql
SELECT country.name FROM airport, country
WHERE airport.iso_country = country.iso_country
GROUP BY country.iso_country HAVING COUNT(*) > 1000;
```
![sql kommennon vastaus](kuva.png)

### 6.7
```sql
SELECT name FROM airport
WHERE elevation_ft = (SELECT MAX(elevation_ft) FROM airport);
```
![sql kommennon vastaus](kuva.png)

### 6.8
```sql
SELECT name FROM country WHERE iso_country IN(
SELECT iso_country FROM airport WHERE elevation_ft
IN(SELECT MAX(elevation_ft) FROM airport));
```
![sql kommennon vastaus](kuva.png)

### 6.9
```sql
SELECT COUNT(*) FROM game, goal_reached
WHERE id = game_id AND screen_name = "Vesa" GROUP BY screen_name;
```
![sql kommennon vastaus](kuva.png)

### 6.10
```sql
SELECT name FROM airport ORDER BY ABS(latitude_deg) DESC LIMIT 1;
```
![sql kommennon vastaus](kuva.png)

## 7 Päivityskyselyt harjoitukset

### 7.1
```sql
UPDATE game
SET location = (SELECT ident FROM airport WHERE name = "Nottingham Airport"), co2_consumed = co2_consumed+500
WHERE screen_name = "Vesa";

SELECT * FROM game;
```
![sql kommennon vastaus](kuva.png)

### 7.2
```txt
b. game
```
![sql kommennon vastaus](kuva.png)

### 7.3
```sql
DELETE FROM goal_reached;
```
![sql kommennon vastaus](kuva.png)

### 7.4
```sql
DELETE FROM game;
```
![sql kommennon vastaus](kuva.png)

## 8 Tietokannan suunnittelu harjoitukset

### 8.1
```
Katso alla olevaa ER-mallia. Mikä on airport yksilötyypin tunnistava ominaisuus?

vastaus: ident
```
![sql kommennon vastaus](kuva.png)

### 8.2
```
Katso alla olevaa ER-mallia. Kuvassa on yhteys airport ja country
yksilötyyppien välillä. Yhteydellä on lukumäärärajoite yhden suhde moneen.
Kumpi yksilötyypeistä on ns. moneen pää?

vastaus: country
```
![sql kommennon vastaus](kuva.png)

### 8.3
```
Katso alla olevaa ER-mallia. Kuvassa on yhteys airport ja country
yksilötyyppien välillä. Yhteydellä on lukumäärärajoite yhden suhde moneen.
Tarkoittaako tämä:

vastaus: b. Maassa voi olla monta lentokenttää
```
![sql kommennon vastaus](kuva.png)

### 8.4
```
Jokaisesta ER-kaavion yksilötyypistä syntyy relaatiomallin taulu

vastaus: tosi
```
![sql kommennon vastaus](kuva.png)

### 8.5
```
Jokaisesta ER-kaavion yhteydestä syntyy relaatiomallin taulu

vastaus: epätosi
```
![sql kommennon vastaus](kuva.png)

### 8.6
```
Katso alla olevaa ER-mallia. Kuvassa on yhteys airport ja country
yksilötyyppien välillä. Yhteydellä on lukumäärärajoite yhden suhde moneen.
Kun tämä kohta muutetaan relaatiomalliksi, tarkoittaako tämä:

vastaus: b. airport-tauluun tulee viiteavain country-tauluun
```
![sql kommennon vastaus](kuva.png)

### 8.7
```
Katso alla olevaa ER-mallia. Kuvassa on yhteys airport ja game yksilötyyppien
välillä. Yhteydellä on lukumäärärajoite yhden suhde moneen. Kun tämä kohta
muutetaan relaatiomalliksi, tarkoittaako tämä:

vastaus: a. game-tauluun tulee viiteavain airport-tauluun
```
![sql kommennon vastaus](kuva.png)

### 8.8
```
Katso alla olevaa ER-mallia. Kuvassa on yhteys game ja goal yksilötyyppien
välillä. Yhteydellä on lukumäärärajoite monen suhde moneen. Tarkoittaako tämä:
Pelissä voi olla monta tavoitetta ja tavoite voi olla monessa pelissä

vastaus: tosi
```
![sql kommennon vastaus](kuva.png)

### 8.9
```
Katso alla olevaa ER-mallia. Kuvassa on yhteys game ja goal yksilötyyppien
välillä. Yhteydellä on lukumäärärajoite monen suhde moneen. Kun tämä kohta
muutetaan relaatiomalliksi, tarkoittaako tämä:

vastaus: b. Yhteyden salmiakista tulee oma taulunsa
```
![sql kommennon vastaus](kuva.png)

### 8.10
```
Katso alla olevaa ER-mallia. Jos sinulla on goal_reached yhteyden salmiakista
syntynyt taulu relaatiomallissa. Siihen tulee viiteavaimet seuraavasti:

vastaus: a. Viiteavain sekä goal-tauluun että game-tauluun
```
![sql kommennon vastaus](kuva.png)
