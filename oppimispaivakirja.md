# git-oppimispaivakirja

# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Olin aiemmilla kursseilla perehtynyt toki gittiin, mutta moni asia oli jäänyt oppimatta. Esim. en ollut juurikaan perehtynyt tuohon miten liikkua committeissa vanhempaan. En myöskään tuota restore komentoa ollut käyttänyt aiemmin. Haarojen olemassaolosta tiesin, mutta tämä osio selkeytti niiden tarkoitusta aika paljon.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git switch master | Siirrytään master haaraan
| git merge develop | Yhdistetään develop-haara nykyiseen haaraan
| git add * | Otetaan tiedosto mukaan mukaan seuraavaan talletukseen tai kaikki muutetut jos git add .
| git rm * | Poistaa tiedoston työhakemistosta ja Git-hallinasta.
| git commit -m " " | Tallettaa tehdyt muutokset ja nimeää ne käyttäjän haluamalla commitilla
| git log | Tulostaa kaikki tehdyt muutokset

# Oppimispäiväkirja: Hajautettu git

Tämän osioin tehtävät oli ehkä helpompia, koska näitä komentoja on väkisin tullut käytettyä jo aikaisemmillla tunneilla. Hyvää oli, että vähän tuon git fetch, git merge ja git pull komentojen logiikka tuli selkämmäksi.

Kirjoita tähän vastauksesi

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git fetch | Lataa muutokset etärepositoriosta, mutta ei vielä yhdistä niitä.
| git pull origin | Lataa muutokset ja yhdistää ne automaattisesti. Sama kuin git fetch ja git merge.
| git clone | Kloonaa omalle koneelle repositorioin halutusta Github-osoitteesta.
| git push | Puskee paikalliset muutokset Githubin etärepositorioon.
| git pull | Hakee etärepositoriosta muutokset ja tallentaa ne paikallisesti.

# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Ainakin voi palata aikaisempiin muutoksiin. Lisäksi voi tehdä eri haaroja, missä voi olla eri versioita. Kuvittelisin, että jos jostain sovelluksesta tehdään vaikka eri versioita useille asiakkaalle ja jokainen kaipaa jotain itselleen tehtyä räätälöintiä, niin silloin varmaan on hyvä kehittää näitä eri asiakkaiden versioita omissa haaroissaan.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Useamman ihmisen on helpompi kehittää, kun voi tehdä omia muutoksiaan ja sitten yhdistää ne. Lisäksi projektia on helpompi suunnitella kun voi lisätä tehtäviä projektin Backlogiin ja voidaan sopia kuka kehittää mitä ominaisuutta ja kun on saanut valmiiksi sen, niin siitä jää jälki mitä on saatu valmiiksi ja mitä on tekemättä.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Jokainen kehittäköön muutokset omassa haarassaan ja sitten vasta yhdistää ne ja ratkaisee mahdolliset konfliktit. Lisäksi on syytä käyttää Githubin backlog-ominaisuuksia ja luoda sinne userstoreja ja github-issueita. On hyvä jakaa tehtävät sprintteihin ja sopia, mitä jokainen tekee kunkin sprintin aikana ja laittaa ne Backlogissa tehdyiksi kun ovat valmiita.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso oli hyödyllinen. Nyt on tullut opittua asioita muiden kurssien ohessa. Tällainen kurssi olisi olla hyvä heti opintojen alussa. Työmäärä oli aika sopiva. Ehkä pientä selventämistä voisi materiaalissa olla, nyt aloin pushaamaan heti alusta alkaen noita tehtäviä, mutta ehkä vika oli myös omassa päässä. Perustoiminnot oli jo ennestään jokseenkin hallinnassa, mutta tällä kurssilla oppi paljon uutta, joista olisi ollut varmasti hyötyä jo aimmilla kursseilla. Jostain syystä tuo kello rikkoutui minulla jossain vaiheessa, kun se muutettiin analogikseksi, en oikein tiedä miksi. Se vilahtaa kyllä kunnolisena kun sivun lataa, mutta sitten se häviää. Aiemmin se näytti ajan kyllä hyvin.