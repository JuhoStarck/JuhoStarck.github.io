# JuhoStarck.github.io
---

# Learning diary
---

## **Week1**

### Fly.io assignment:
Do a hands-on tutorial and install that ready docker container provided.

Asensin ja kirjauduin sisään fly.io onnistuneesti, jonka jälkeen käynnistin demo sovelluksen. Käynnistin sen suositelluilla default-asetuksilla.

<img src="/Pictures/flyio1.png">

Kesti hetken aikaa, kunnes se käynnistyi ja alkoi pyörittää haluttua imagea serverillä.

<img src="/Pictures/flyio2.png">

<img src="/Pictures/flyio3.png">

Tuhosin tämän jälkeen demo sovelluksen, ettei se jää turhaan pyörimään testauksen jälkeen.

---

## **Week2**
AWS serverless tutorial

Harjoituksen tarkoituksena on rakentaa serverless web applikaatio, joka käyttää Amazonin generatiivisia AI malleja.
Aluksi piti tehdä React applikaatio tutoriaalissa annetuilla komennoilla (korostettu keltaisella).

<img src="/Pictures/AWS1.png">

<img src="/Pictures/AWS2.png">

Tämän jälkeen piti tehdä GitHub repo ja puskea sinne juuri tehty applikaatio ja tiedoston juureen ladattu AWS Amplify paketti.
Otin käyttöön applikaation AWS Amplifyllä Githubista

<img src="/Pictures/AWS3.png">

Tein email kirjautumis toiminnon Amplifyn tiedostoihin, sitten hain hyväksyntää että pääsen käyttämään Claude 3 modelia.

<img src="/Pictures/AWS4.png">

Tein bedrock.js tiedoston, johon lisäsin annetun lambda funktion koodin

<img src="/Pictures/AWS5.png">

Muokkasin backend.ts tiedostoa annetulla koodilla, joka lisää Amazon Bedrockin datan lähteeksi

<img src="/Pictures/AWS6.png">

Lisäsin resource.ts tiedostoon annetun koodin, joka ottaa hoitaa Blackrockille tarkoitetut kyselyt.

<img src="/Pictures/AWS7.png">

Muokkasin .css tiedostoja annetuilla koodeilla, jotka muotoilee pää UI elementtejä ja syöte formin elementtejä. 
Muokkasin typescript tiedostoja annetuilla koodeilla myös.

Näkymä tyylitiedostojen muokkaamisen jälkeen:

<img src="/Pictures/AWS8.png">

Tein uuden käyttäjän ja aikaisemmin tehty email hyväksyntä viesti näytti toimivan.

<img src="/Pictures/AWS9.png">

Ja ohjelma lähti toimimaan onnistuneesti ja antoi syötetyn promptin perusteella reseptin:

<img src="/Pictures/AWS10.png">

---