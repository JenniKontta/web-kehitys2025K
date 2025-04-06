## Tehtävä 2, viikko 2

Jekyll-sivustoa voisi automatisoida GitHub Actions -toimintojen avulla esimerkiksi seuraavanlaisesti:
-	hyödyntäen workflow-menetelmää
-	asettamalla triggerit kehityshaaraan tietyillä tageilla, jolloin halutut kohteet aktivoituvat
-	ajastamalla cron-merkintä, jolla koodi suoritetaan esimerkiksi tiettyihin kellonaikoihin joka päivä

Ohjelmistojen suunnitteluun, testaukseen ja toteuttamiseen liittyy CI/CD-putkisto. Se tarkoittaa ohjelmsiton jatkuvaa integrointia (Continuous Integration) ja jatkuvaa toimittamista (Continuous Delivery). Sitä varten on olemassa erilaisia suunnittelumalleja. Esimerkiksi https://refactoring.guru/design-patterns -sivustolta löytyy paljon esimerkkejä näistä malleista. Niiden käyttäminen on suositeltavaa, koska siten kaikkea ei tarvitse keksiä alusta alkaen itse. Lisäksi niiden hyödyntäminen on alalla yleistä.

Esimerkiksi GitHub toimii CI/CD-putkistona. Siellä kaikki ohjelmiston liikkuvat palaset, eli toisin sanoen kaikki tarvittavat tiedostot ovat samassa paikassa. Tällä tavalla ne ovat myös helpommin hallittavissa, löydettävissä ja muokattavissa. 

Periaatteessa kaiken voi tehdä samassa ympäristössä alusta loppuun saakka, koska GitHubissa voi myös testata koodin toimivuutta. Lisäksi samaa ympäristöä voi hyödyntää useampi tekijä samaan aikaan.


[Linkki etusivulle](index.md)
