# Uputstva

Sadržaj:
- [Uputstvo za kreiranje kursa](#uputstvo-za-kreiranje-kursa)
- [Ažuriranje spiska kurseva](#ažuriranje-spiska-kurseva)

## Uputstvo za kreiranje kursa

1. [Započnite kreiranje projekta][new]
2. Izaberite opcije sa slike
![Prikaz izbora u wizard-u za kreiranje projekta][new opcije]
3. Izmenite sadržaj fajla `_config.yaml` kako bi bio prikazan odgovarajući naziv kursa
![Prikaz sadržaja config.yaml fajla][promena naslova]
4. Kreirajte sajt za dati projekat 
![Kreiranje sajta po koracima][kreiranje sajta]
5. Sačekajte da se sajt postavi od strane GitHub-a. Kada se proces završi, žuti indikator će se promeniti i biće zelene boje. 
![Indikator za status deploy-a][status]
6. Postavite link repozitorijuma tako da posetiocima bude lakše da dođu do postavljenog sajta.
![Promena podešavanja repoa][repo conf]
7. Nakon kreiranja kursa [dodajte kurs na spisak kurseva](#ažuriranje-spiska-kurseva)

## Ažuriranje spiska kurseva

Spisak kurseva predstavlja `README.md` fajl projekta: https://github.com/imioer/imioer.github.io.

Ukoliko kreirati novi kurs, možete ga kreirati po uzoru na ostale linkove. Obratite pažnju na to
da sam link do kursa predstavlja samo skraćenicu za naziv kursa i da mora da se poklapa sa nazivom
projekta. Na primer, ako se projekat za Osnove programiranja zove `op` onda i link u ovom fajlu treba 
da ima tu vrednost. Sam link neće biti validan kada se na njega klikne na GitHub-u, ali radiće kada se
na njega klikne na glavnom sajtu (imioer.github.io).

U suštini, naziv projekta (repozitorijuma) treba da se navede u linku. Taj naziv će biti prikazan kao
ruta u okviru glavnom projekta, zbog čega se i koriste skraćenice kao nazivi projekta.

Primer za dodavanje predmeta Osnovi programiranja za koji je napravljen repozitorijum `op`:
```Markdown
- [**Osnovi programiranja**](op)
```

[new]: https://github.com/organizations/imioer/repositories/new
[new opcije]: ./resursi/slike/kreiranje_projekta.png
[promena naslova]: ./resursi/slike/promena_naslova.png
[kreiranje sajta]: ./resursi/slike/deploy.png
[status]: ./resursi/slike/deploy_status.png
[repo conf]: ./resursi/slike/podesavanja_repoa.png
