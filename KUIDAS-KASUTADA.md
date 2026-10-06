# Kuidas oma aju kasutada

Valmis laused. Kopeeri, kleebi, muuda oma sõnadega ümber. Sa ei pea neid pähe õppima — see fail on selleks, et sa ei peaks.

---

## Iga kord, kui alustad ja lõpetad

> **Lõpeta salvestamisega.**

**Alguses** ei pea midagi tegema. Brauseris alustab iga uus vestlus GitHubi viimasest versioonist.

**Lõpus:**
> *Salvesta kõik muudatused GitHubi põhiversiooni.*

Või lühemalt: *„push main'i"* või *„salvesta ajju"*. Kõik kolm tähendavad sama.

**Kui sa ei ole kindel, kas kõik on salvestatud:**
> *Kas kõik tänased muudatused on põhiversioonis (main)?*

Või ava github.com, oma aju repo, ja vaata: kas viimane muudatus on tänane?

---

## Kui alustad uues vestlusaknas

Iga vestlus algab külmalt. AI ei mäleta eelmist korda — konteksti kannab repo, mitte vestlus. Nii et kirjuta talle nagu uuele töötajale:

> *Loe mu aju läbi. Täna teeme [see, mida sa teed]. Kogu vajalik info on repos olemas.*

Ära kirjuta „nagu eelmine kord rääkisime" — seda korda tema jaoks ei olnud.

---

## Esimene lause, kui aju on veel tühi

> *Loe mu aju läbi ja ütle, mis siin on ja mis on veel tühi.*

---

## Kui sa ei tea, kuhu midagi panna

Sa ei pea teadma GitHubi ega kaustade reegleid. Kirjelda lihtsalt, mis sul on:

> *Mul on [kirjelda materjali]. Mida ma sellega teen ja kuhu see käib? Ära veel midagi liiguta. Anna esmalt turvaline soovitus, küsi ainult see, mis on puudu, ja selgita inimkeeles, miks.*

Näiteks:

> *Mul on kaust täis vanu arveid. Mida ma sellega teen ja kuhu see käib?*

Brain peaks kõigepealt ütlema, et originaalarved jäävad agendikonto Drive'i, mitte Braini. Seejärel küsib ta ainult:

1. mida sa tahad arvetest saada;
2. kas AI tohib kliendiandmeid lugeda või tuleb need enne anonümiseerida.

Lõplik vastus ütleb:

- kus hoida originaale;
- mida neist Braini õppida;
- miks;
- mis on järgmine samm.



## Aju seemendamine

Kui materjalis võib olla kliendiandmeid, paroole, panga- või terviseinfot, **ära anna kogu kausta veel AI-le lugeda**. Kirjelda materjali ilma faile lisamata:

> *Mul on [kirjelda materjali]. Seal võib olla privaatset infot. Mida ma sellega teen? Ära veel faile ava ega liiguta.*

Brain ütleb, kas originaalid võivad minna agendikonto Drive'i, kas midagi tuleb enne offline anonümiseerida ja mida tasub neist Braini õppida. Sina ei pea GitHubi ega AI-töötluse tehnilisi reegleid ise otsustama.

Kaks liigutust, ja enamik inimesi vajab mõlemat.

### 1. Näita, mis sul juba on

**Pane materjal agendikonto Drive'i ühte kausta** — näiteks `Toormaterjal`. Koduleht, vanad pakkumised, hinnakiri, ChatGPT eksport, häälmärkme transkript. Siis ütle:

> *Loe Drive'is kaust `Toormaterjal` läbi ja destilleeri see mu ajju. Toorikut ennast ajju ei kopeeri.*

**Näita kindlat kausta, mitte kogu Drive'i.** Nii teab AI täpselt, mida lugeda.

**Lühikese asja võid ka otse vestlusesse kleepida** või ekraanipildina lisada — kodulehe teksti, ühe kirja, ühe postituse.

> Drive'i võib panna PDF-i, pildi, Wordi faili või ekraanipildi **ainult siis, kui AI-pakkuja tohib selle sisu töödelda.** See, et fail GitHubi ei lähe, ei tähenda, et AI seda lugedes ei töötle.

### 2. Lase tal endalt küsida

See on see pool, mida kuskil kirjas ei ole — su hääl, miks sa mõnest kliendist ära ütled, mida sa kunagi ei teeks.

> *Sa oled lugenud, mis mul olemas on. Nüüd küsi minult see, mis puudu on — üks-kaks küsimust korraga, ja kirjuta mu vastused õigesse faili. Vaata `TEEMAD.md`, kust alustada.*

**Järjekord loeb: kõigepealt materjal, kasvõi natuke, siis alles intervjuu.** AI, kes on su kodulehe läbi lugenud, küsib *„su kodulehel on kolm paketti, aga arvetel ainult üks — kumb on praegu tõsi?"*. Külm AI küsib *„kirjelda oma äri"*. Sama tööriist, täiesti erinev küsimus.

---

## Aju + Drive — sa ei pea kõike ajju kolima

Arved, kliendiregister, kliendikaustad, pildid — need ei ole ja ei peagi olema osa ajust. **Need elavad agendikonto Drive'is.** AI loeb neid konnektoriga, kui töö seda vajab.

> *Tee uus arve. Üldised reeglid võta ajust; kliendi andmed ja eelmised arved võta Drive'i kaustast `Arved`. Salvesta mustand samasse Drive'i kausta, mitte ajju.*

> *Lisa Drive'is kliendiregistrisse eilne uus klient — kes ta on ja mida ta tahab, vaata ajust.*

Mis siin toimub:

- **Aju annab konteksti** — kes on klient, mis on su hinnad, kuidas sa asju sõnastad.
- **Drive on töölaud** — sealt tulevad näidised, sinna läheb tulemus.
- **Drive ei muutu aju osaks.** Midagi ei kopeerita GitHubi.

Ajju läheb ainult see, mida sa ütled, et sinna läheks:

> *Neid arveid ajju ei pane. Pane ajju ainult see, et selle kliendi hind tõuseb 1. septembrist.*

**Sellepärast sa ei kaota midagi sellega, et kliendi andmed ajus ei ela.** Nad on Drive'is, ühe klõpsu kaugusel, ja aju teab neist täpselt nii palju, kui sina tahad.

> **Sinu arvutit AI ei näe.** Brauseris töötav AI näeb ainult aju (GitHub) ja seda, mis on agendikonto Drive'is. Kui mõni fail on ainult sinu arvutis, laadi see Drive'i. Arvuti enda ühendamine AI-ga on hilisem eraldi otsus — tee enne riskihindamine.

> **Kui AI ütleb, et ta ei saa faili Drive'i salvestada**, palu tal anda fail allalaadimiseks ja lohista see ise Drive'i. Tekstifaile ja Google Docse saab AI tavaliselt ise teha; suuremaid faile (PDF, slaidid) alati mitte.

---

## Skillid

Skill on juhend ühele korduvale tööle. Sinu skillid on kaustas `skillid/` ja nende nimekiri on `AGENTS.md`-s.

**Mis skillid mul on?**
> *Mis skillid mul ajus on ja millal ma neid kasutan?*

**Kasuta skilli:**
> *Tee riskihindamine.*

**Tee uus skill** — kui oled mingi töö AI-ga läbi teinud ja tahad, et järgmine kord läheks samamoodi:
> *Tee sellest, mis me just tegime, skill. Pane see kausta `skillid/` ja lisa `AGENTS.md` tabelisse.*

---

## Küsi ise ajult

**See on nädala 1 kõige tähtsam lause.** Kasuta seda siis, kui ajus on juba midagi sees.

> *Loe kogu mu aju läbi ja ole minuga aus.*
>
> *1. Mis siin on omavahel vastuolus — kus ma ütlen üht ja teen teist?*
> *2. Mis on puudu — mida peaks iga AI minu ärist teadma, aga siit ei leia?*
> *3. Millele ma pole ilmselt mõelnud?*
> *4. Mis on kolm asja, mis praegu kõige rohkem mu kasvu takistavad?*
> *5. Mis on see üks töö, mille sa minu asemel esimesena ära teeksid?*

> **See töötab siis väga hästi, kui su aju juba tunneb sind ja sinu ettevõtet.** Kui vastus tuleb lahja, ei ole see märk sellest, et asi ei tööta — see on märk, et aju on veel näljane. Sööda teda edasi ja küsi nädala pärast uuesti.

---

## Päevane rütm

**Hommikul esimese asjana:**
> *Loe mu aju läbi. Täna teen [...]. Mis sa arvad, mis on täna kõige tähtsam?*

**Päeva lõpus:**
> *Salvesta ajju oluline: [mis juhtus, mis otsustati, mis on järgmine]. Kirjuta see õigesse faili ja salvesta GitHubi põhiversiooni.*

---

## Kui midagi läks hästi

> *Lisa see mu tõendite nimekirja failis `01-mina/tulevane-mina.md`.*

---

## Ära usalda pimesi

Kui su AI midagi soovitab või küsib ja sa ei saa aru, miks:

> *Seleta mulle, miks see oluline on.*

AI võimendab tarkust ja ka rumalust. Otsustaja oled sina.
