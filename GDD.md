# Forest Punk

Sisältö
#### 1. Konseptikuvaus
> ##### 1.2 Peli-idea
> ##### 1.3 Genre
> ##### 1.4 Tyyli & Tyylireferenssejä
> ##### 1.5 Konseptitaidetta
#### 2. Projektinhallinta
> ##### 2.2 Aikataulutus
> ##### 2.3 Riskit
#### 3. Pelikäsikirjoitus
#### 4. Pelidesign (Gameplay)
> ##### 4.2 Eteneminen
> ##### 4.3 Core-loopit
> ##### 4.4 Liikkuminen ja toiminnot
> ##### 4.5 Näkymät
> ##### 4.6 Tasot
> ##### 4.7 Kerättävät esineet
#### 5. Visuaalisuus ja käytettävyys
> ##### 5.2 Hahmot
> ##### 5.3 Ympäristöt
> ##### 5.4 Tarvittavat core - assetit
> ##### 5.5 Käyttöliittymä
#### 6. Tekninen
> ##### 6.2 Arkkitehtuuri
> ##### 6.3 SFX
> ##### 6.4 Esteettömyys
> ##### 6.5 Käyttöliittymä

## 1. Konseptikuvaus

#### Peli-idea:

> ##### Tähän kuvaus pelin ideasta

#### Genre:

> ##### Action Platformer

#### Tyyli:

> ##### Steampunk - 2D

#### Tyylireferenssejä:

> ##### Tähän kuvia pelin tyylireferensseistä

#### Konsepti:

> ##### Kuvia konseptitaiteesta

## 2. Projektinhallinta
> ##### Projektinhallinnassa käytetään Trelloa, GitHubia & Discordia. Kommunikaatiovälineenä toimii ryhmän oma Discord kanava.

### 2.1 Monetisaatio

> ##### Pelin markkinointisuunnitelma

### 2.2 Aikataulutus
> ##### - Päävaiheet
> ##### - Yksityiskohtaiset taskit per osa-alue
> ##### - Missä vaiheessa testaukset?
> ##### - esim. Versioiden buildit maanantain palaveriin mennessä, testaus toteutettuna torstain palaveriin mennessä

## Sprintti


> ##### 1-3. Suunnittelua, peli-idea (esittely) aikataulu, GDD, työnjako, Core-Extended-Wishes


> ##### 4. Prototyyppi + testaus​ Core toiminnallisuuksia, menut ja placeholder grafiikoita 


> ##### 5. Korjauksia testauksen pohjalta 


> ##### 6. Alpha + testaus​ Core ominaisuudet, ainakin lopulliset hahmografiikat ja kerättävät esineet


> ##### 7. Grafiikat valmiina​ ja viimeisten ominaisuuksien lisäys  


> ##### 8. Beta + testaus​ Kaikki ominaisuudet, toiminnallisuudet ja animaatiot pelissä​ <ins><sup>Deadline 15.04</sup></ins>


> ##### 9. Postprocessing & Fixlist, Release + testaus + viimeiset korjaukset​ Fixlist mahdollisimman tyhjäksi​ <ins><sup>Pelien testaus koululla 17.04</sup></ins>


> ##### 10. Purku​, Projektin esittely​ <ins><sup>Purku koululla 29.04</sup></ins>

## Proto-Alpha-Beta-Release-Purku

> ##### *Prototyyppi Deadline 21.03*

> ##### *Alpha Deadline 04.04*

> ##### Beta Deadline 15.04

> ##### *Release Deadline 22.04*

> ##### Peliprojektin purku 29.04

## 2.3. Riskit
> ##### - Joku tiimistä lähtee
> ##### - Aikataulusta myöhästytään
> ##### - Aikataulu on epäselvä
> ##### - Tietokone hajoaa
> ##### - Versionhallinnassa on virhe, ja viimeisin backup on liian vanha
> ##### - Osaaminen ei riitä johonkin ominaisuuteen
> ##### - Liian laaja scope
> ##### - Sairastumisia tai muita pitkäaikaisia poissaoloja
> ##### - Kommunikaatio ei toimi

## 3. Pelikäsikirjoitus
#### Tarina
> ##### - Delfiini
#### Hahmot
> ##### - Pelaaja
> ##### - Boss
#### Maailma/Tasot
> ##### - Kuvitteellinen maailma (fantasia)
> ##### - Leveleiden lukumäärä:
#### Kerättävät esineet
> ##### - Kolikot
> ##### - Sydämet

## 4. Pelidesign (Gameplay)
#### Pelimekaniikat 
> ##### - ”Siten että ohjelmoija pystyy ohjelmoimaan designin perusteella, artisti pystyy toteuttamaan artin.” 
> ##### - Laserin heijastuminen kristalleista. 
> ##### - Arkkujen aukeaminen ja kristallin palan kerääminen. 
> ##### - Arkkujen lukot sisältävät sudokumaisen puzzlen, joka pitää selvittää, ennen kuin kristallinpalan näistä 
saa. 
> ##### - Rikkinäisten kristallien korjaaminen, kun pelaaja on vuorovaikutuksessa sen kanssa. Pelaajalla pitää 
tällöin olla yksi kristallin pala. 
> ##### - Häkin avautuminen laserin osoittaessa sen lukkoon. 
> ##### - Pelaaja kuolee osuessaan laseriin. 
> ##### - Laserin säteen osuessa kristalliin, siinä on pieni viivästys ennen kuin kristalli heijastaa sen. 
> ##### - Ovet suljetuille alueille aukeavat laserin osuessa niiden lukkoon.

#### Pelin fysiikat 
> ##### - Laserin heijastuminen kristalleista. 
> ##### - Kristallin kääntäminen Q ja E näppäimistä. 
> ##### - Kameran kääntäminen hiiren oikea näppäin pohjassa, hiirtä liikuttamalla. 
> ##### - Hiiren rullalla zoomaus. 

## 4.2 Eteneminen

#### Tavoite 
> ##### - Päihittää viholliset ja boss pelin lopussa
> ##### - *Kerätä matkalla kolikeita?*


#### Esteet 
> ##### - Erityyppisiä vihollisia
> ##### - Ansoja tasoissa joista pelaaja ottaa vahinkoa


#### Mitä pelaaja tekee pelissä? 
> ##### - Etenee kentässä taistellen vihollisia vastaan päästäkseen etenemään.
> ##### - Kerää itemeitä, health itemeitä ja *kolikoita?*


#### Milloin peli tallentaa ja minkä osan? 
> ##### - Tason lopussa tallennetaan kerätyt itemit

## 4.3 Core-loopit

#### Core-loop 1.
> -
#### Core-loop 2.
> -
#### Core-loop 3.
> - 
## 4.4 Liikkuminen ja toiminnot

#### Millä eri tavoilla pelaaja liikkuu
> ##### - WASD + nuolinäppäimet?


#### Mitä toimintoja pelaajalla on?
> ##### -

## 4.5 Näkymät

### Menut
> ##### - StartMenu
> ##### - PauseMenu
> ##### - SettingsMenu
 ##### Credit page
 ##### Tasot
 ##### DeathScreen
 ##### WinScreen

## 4.6 Tasot
 > #### - Steampunk ja metsäteema.
 
## 4.7 Kerättävät esineet

> ##### - Sydämet
> ##### - *Kolikot?*
