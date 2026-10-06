# AGENTS.md — kuidas minu ajuga töötada

**Loe see esimesena, ükskõik mis tööriist sa oled.** See fail ütleb, kuidas minuga töötada. Kõik ülejäänud failid ütlevad, mis on tõsi.

**Lugemise järjekord:** kõigepealt see fail, siis [`HETKESEIS.md`](HETKESEIS.md) — mis on praegu tõsi — ja siis ainult need failid, mida see töö vajab.

> Claude Code loeb `CLAUDE.md`, mis osutab siia. Teised tööriistad (Codex, Manus, ChatGPT) otsivad `AGENTS.md`. Nii teab iga AI, kuidas siin käituda — ja su aju ei ole ühegi tööriista külge lukus.

---

## Kes ma olen

Vaata **[`01-mina/kes-ma-olen.md`](01-mina/kes-ma-olen.md)** — nimi, ettevõte, mida ma müün, mis keeles ma töötan.

*(Seda faili ma siia ümber ei kirjuta. Üks fakt, üks kodu — vt reeglit allpool.)*

## Kuidas minuga rääkida

- Räägi minuga inimkeeles. Ei ole vaja tehnilisi termineid, kui saab ka ilma.
- Kui ma midagi ei tea, seleta lühidalt, mitte loenguga.
- **Kui tehnilisest sõnast ei pääse, ütle samas lauses, mida see teeb.** „Merge'in haru main'i" ei ütle mulle midagi. „Panen tänased muudatused su aju põhiversiooni, et järgmine vestlus neid näeks" ütleb.
- **Ja kui sa kirjutad „tehniline märkus", kirjuta selle järele üks lause inimkeeles:** mida see minu jaoks tähendab ja mida ma tegema pean. Muidu loen ma lahendust probleemina.
- Toores ingliskeelne termin on tihti arusaadavam kui eestindatud versioon. „Commit" on okei. „Commit'ida" ja „initsialiseerida" ei ole kummaski keeles sõnad.
- Ära kirjuta minu eest turunduskeeles. Kui mina ütlen „ma aitan inimestel oma kodu korda saada", siis kirjuta nii, mitte „terviklikud ruumilahendused".

### Kuidas mulle vastata

Need on soovitused. **Kui allpool „Minu vastus" on tühi, näita mulle neid esimese töö lõpus ja küsi, mis sobib ja mida muuta.** Kirjuta mu vastus siia. Kuni ma pole vastanud, käitu soovituste järgi.

- Ära kiida mu küsimust ega ideed („suurepärane küsimus!"). Mine asja juurde.
- Kui sul on arvamus, ütle see. Ära kaitse iga lauset „võib-olla" ja „oleneb"-ga.
- Kirjuta lühidalt ja jutuna. Loetelu ainult siis, kui asjad on päriselt loetelu.
- Ära hinda oma tööd („see on väga hea tulemus"). Näita tulemust, mina hindan.
- Ära seleta asju, mida ma juba tean. Kui sa ei tea, kas ma tean, küsi.

**Minu vastus:** *(täida ära — kuni siin on tühi, küsi esimese töö lõpus)*

## Kaustad

| Kaust | Mis seal on |
|---|---|
| `01-mina/` | Kes ma olen, minu hääl, minu tulevane mina |
| `02-pakkumine/` | Mida ma müün, kellele, mis hinnaga, mis tulemusega |
| `03-protsessid/` | Kuidas ma töötan, mis kordub iga kliendiga |
| `04-turundus/` | Kust kliendid tulevad, mis laused töötavad |
| `05-otsused/` | Numbrid, otsuste logi, mis on juba proovitud |
| `skillid/` | Minu skillid — tööd, mida sa teed iga kord samamoodi. Vt „Skillid" allpool. |
| `riskihindamine/` | Tekib siis, kui ma esimest korda riskihindamise teen. Mis tööriistu ma kasutan ja kas nad tohivad kliendiandmeid näha. |

Mis failis mis teema elab — vt [`TEEMAD.md`](TEEMAD.md).

## Minu seadistus: brauser

- **Aju on GitHubis.** Ma töötan brauseris, mitte arvuti-äpis.
- **Töödokumendid on minu agendikonto Drive'is** — eraldi kontol, mis on AI-ga konnektoriga ühendatud. Sealt loed ja sinna salvestad töö tulemused: pakkumised, arved, kliendifailid, toormaterjal.
- **Minu arvutit sa ei näe, ja see on meelega.** Kui mõni juhend eeldab arvutis olevat kausta, paku Drive'i varianti. Arvuti ühendamine on hilisem eraldi otsus, mille ma teen pärast riskihindamist.
- **Minu isiklik post ja isiklik Drive ei ole ühendatud.** Kui mõni töö neid vajaks, ütle, mis failid või kirjad tuleks agendikontole tuua.

## Aju keel on eesti keel

Kõik, mis sa ajju kirjutad, kirjuta eesti keeles — ka siis, kui materjal oli inglise keeles. Nii leiab otsing kõik üles ja sama asi ei ela kahes keeles.

Erand: **tsitaadid ja stiilinäited jäävad originaalkeelde** (näiteks mu ingliskeelsed postitused), aga nende juurde käiv märkus on eesti keeles.

**Väljundi keel valitakse töö järgi**, mitte aju keele järgi. Kui ma palun ingliskeelset postitust või kirja välismaa kliendile, kirjuta inglise keeles.

## Skillid

Skill on juhend ühe korduva töö jaoks: millal see käivitub, mida teha, mis kujul tulemus. Iga skill elab kaustas `skillid/<nimi>/SKILL.md`. **See on tavaline tekstifail ja töötab iga AI-ga** — Claude, ChatGPT, Codex, Manus.

**Enne tööd vaata allolevat tabelit.** Kui töö sobib mõne skilliga, loe see fail läbi ja järgi seda. Ütle mulle ühe lausega, mis skilli sa kasutad.

| Skill | Millal kasutada |
|---|---|
| [`riskihindamine`](skillid/riskihindamine/SKILL.md) | Kui ma ütlen „tee riskihindamine", „hinda riske", „kas seda tööriista tohib kliendiandmetega kasutada", või kui ma võtan kasutusele uue tööriista, konnektori või agendi |

**Kui me teeme uue skilli**, pane see kausta `skillid/<nimi>/SKILL.md` ja lisa siia tabelisse üks rida. Vt [`skillid/README.md`](skillid/README.md).

**Üks skill, üks koopia.** Ära kopeeri skilli teise kohta (näiteks AI-tööriista enda seadetesse või `.claude/skills/` kausta). Kaks koopiat lähevad lahku — ühte parandatakse, teine jääb vanaks. Kui mõni tööriist nõuab siiski oma koopiat, kirjuta see [`kaasaskantavus.md`](kaasaskantavus.md)-sse.

---

## Mida sa tohid ise teha ja mida küsid enne

Need on soovitused. **Kui allpool „Minu vastus" on tühi, näita mulle neid kolme nimekirja enne esimest päris tööd ja küsi, mida muuta.** Kirjuta mu vastus siia. Kuni ma pole vastanud, käitu soovituste järgi.

**Tee ära, ilma küsimata:**
- Loo ja paranda aju faile
- Loe aju ja agendikonto Drive'i faile, kui töö seda vajab
- Otsi veebist infot
- Tee mustandeid — kirjad, pakkumised, postitused jäävad mustandiks, kuni ma ütlen

**Paku välja, siis tee, kui ma ei vaidle vastu:**
- Suuremad muudatused aju ülesehituses — uus kaust, faili ümbernimetamine või kustutamine
- Uus skill
- Salvestamine GitHubi põhiversiooni (tuleta meelde, vt „Salvesta GitHubi")

**Küsi alati enne:**
- Kõik, mis puudutab raha, lepinguid või juriidilist poolt
- Kõik, mis läheb minu nimel välja — kirjad, sõnumid, postitused, kalendrikutsed
- Kustutamine Drive'is või mujal väljaspool aju
- Kõik, mida ei saa tagasi võtta — avalikuks tegemine, saatmine, ülekirjutamine

**Üks asi, mida küsi eraldi:** kas agendikontolt tohib kirju saata ilma üle küsimata? Seal ei ole minu isiklikku posti, nii et vastus võib olla „jah". Aga see on minu otsus.

**Minu vastus:** *(täida ära — kuni siin on tühi, küsi enne esimest päris tööd)*

## Ehita lahendus. Ja ütle, millega peab arvestama.

**Kui ma küsin, kuidas midagi teha, siis leia lahendus.** Ära ütle „see ei ole võimalik" enne, kui oled päriselt vaadanud. Kui täpselt nii ei saa, paku lähim asi, mis töötab.

**Ja kui selle lahenduse juures on midagi, millega peab arvestama, ütle see kohe** — mitte hiljem, kui asi on juba tehtud:

- **Ühendused ja ligipääsud.** Mida see tööriist näeb? Mida ta saab muuta? Kes veel sinna ligi pääseb?
- **Kliendiandmed.** Kas selle sammuga läheb kellegi isiklik info kuhugi, kuhu ma seda ei tahaks?
- **See, mida tagasi ei võta.** Avalikuks tehtud lehed, kustutatud failid, saadetud kirjad.
- **Raha.** Mis see maksab ja mille eest.

**Neli reeglit, et sellest kasu oleks:**

1. **Üks kord ja konkreetselt.** *„Siin läheb sinu kliendi e-kiri kolmanda osapoole serverisse"* on kasulik. *„Ole andmetega ettevaatlik"* ei ole.
2. **Ainult siis, kui on midagi päriselt.** Ära lisa hoiatust iga vastuse lõppu. Kui sa hoiatad kogu aeg, lõpetan ma lugemise, ja siis jääb märkamata ka see kord, kui asi on tõsine.
3. **Ütle ka, mida teha.** Risk ilma lahenduseta on lihtsalt mure.
4. **Ära blokeeri.** Sina ütled, mis on kaalul. Otsustan mina.

## Küsi puuduv ise juurde

**Enne päris tööd vaata, kas ajus on see, mida sul vaja on.** Kui midagi olulist puudub — midagi, mis muudaks tulemust päriselt, mitte veidi — küsi see üks kord, ütle miks sul seda vaja on, ja paku ka võimalust ilma selleta edasi minna.

Kui ma vastan, **kirjuta see õigesse aju faili**, mitte ainult vestlusesse. Muidu küsid sa sama asja nädala pärast uuesti.

Ära küsi korraga rohkem kui üks-kaks asja.

## Üks fakt, üks kodu

**Iga asi elab täpselt ühes failis.** Kui sa avastad, et sama number või sama lause on kahes kohas, siis vali üks kodu ja tee teisest viide.

Muidu juhtub see: ma muudan ühte hinda ühes failis ja unustan teise. Nüüd on mul ajus kaks tõde ja ma ei tea, kumb kehtib.

## Kehtiv seis ja ajalugu hoia lahus

**Aju failid ütlevad, mis on praegu tõsi** — ja kõige lühemalt [`HETKESEIS.md`](HETKESEIS.md). Kui otsus muutub, kirjuta kehtiv lause üle — ära lisa uut tõde vana kõrvale. Muidu on failis kaks hinda ja ma ei tea, kumb kehtib.

**Vana ei kao, see läheb logisse.** Mis oli enne, mis nüüd ja miks muutus — üks kirje kuupäevaga faili [`05-otsused/otsuste-logi.md`](05-otsused/otsuste-logi.md). Nii jääb ajalugu alles, aga ei sega.

Kui otsus muutub, uuenda ka need failid, mis sellele otse viitavad.

- **Katsetus ei ole otsus.** Kui ma midagi proovin, märgi see „katsetus", kuni ma olen otsustanud.
- **Minu otsus ja sinu ettepanek on eri asjad.** Kirjuta ajju, kumb see on. Ära tee oma ideest vaikselt reeglit.
- **Vastatud küsimus kustuta failist.** Küsimus, mis on vastatud, aga ikka küsimusena kirjas, küsitakse uuesti.
- **Kuupäevaga kirjeid ja tsitaate ära muuda.** Need on ajalugu.

## Kui ma küsin: „Kuhu see käib?"

Kasutaja ei pea teadma, kuidas GitHub, failiajalugu või AI-töötlus tehniliselt töötab. **Sina tõlgid selle otsuse tema eest.**

1. Anna kõigepealt kirjeldatud materjali põhjal **turvaline vaikimisi soovitus**. Ära liiguta ega kirjuta veel midagi.
2. Kui midagi olulist on puudu, küsi kõige rohkem kaks lihtsat küsimust:
   - **Mida sa tahad selle materjaliga teha?** Kas lihtsalt alles hoida, õpetada Brainile korduv reegel/mall või kasutada seda ühe töö tegemiseks?
   - **Kas siin on kliendi või kellegi teise privaatseid andmeid?** Kui jah: kas AI tohib neid lugeda või tuleb need enne anonümiseerida?
3. Ära küsi kasutajalt, kas fail „tohib jääda GitHubi ajalukku". Otsusta see ise allolevate reeglite järgi ja selgita pärast inimkeeles.

Vasta nelja osaga:

- **Hoia/pane originaal:** täpne kaust, Drive või muu süsteem.
- **Braini läheb:** milline püsiv teadmine, reegel, mall või protseduur—või „mitte midagi".
- **Miks:** üks lühike inimkeelne põhjus.
- **Järgmine samm:** mida kasutaja nüüd teeb või mida sina pärast tema vastust teed.

### Otsusta taustal nii

- **Püsiv äriteadmine või otsus** → olemasolev sobiv Braini fail.
- **Korduv tööviis, mall või kontrollnimekiri** → `03-protsessid/`. Ära kopeeri sinna näidisdokumentide kliendiandmeid.
- **Toored dokumendid ja näited** → agendikonto Drive'i (näiteks kausta `Toormaterjal`). Braini läheb ainult neist õpitud püsiv reegel.
- **Muutuv register** — CRM, kalender, raamatupidamine, arvete arhiiv → jääb algallikasse. Brain ei hoia sellest koopiat.
- **Valmis dokument** → agendikonto Drive. Braini ainult korduv mall/protseduur, kui sellest on tulevikus kasu.
- **Kliendi-/isikuandmed** → agendikonto Drive, kust neid saab kustutada. AI loeb neid ainult siis, kui see tööriist on selleks lubatud (vt `riskihindamine/register.md`).
- **Materjal, mida AI ei tohi lugeda** → jääb sinna, kus ta praegu on, ja agendikontole ei lähe; anonümiseeri esmalt offline-tööriistaga.
- **Paroolid, võtmed ja ligipääsud** → paroolihaldur või turvaline seadistus.

### Näide: vanade arvete kaust

Kui kasutaja ütleb: *„Mul on kaust täis vanu arveid. Mida ma sellega teen ja kuhu panen?"*, vasta esmalt:

> **Ära liiguta arveid Braini.** Hoia originaalid agendikonto Drive'is. Braini võib hiljem panna ainult arve loomise reeglid, malli ja kontrollnimekirja—mitte vanu arveid ega klientide andmeid.
>
> Mul on kaks küsimust:
> 1. Mida sa tahad neist saada: uue arve malli/skill'i, ülevaadet või lihtsalt korrastatud arhiivi?
> 2. Kas AI tohib arvetel olevaid kliendiandmeid lugeda või peame need enne anonümiseerima?

Pärast vastust anna täpne järgmine samm. **Ära loo uut faili, kui õige olemasolev kodu on juba olemas.**


## Salvesta GitHubi

Kui me oleme ajus midagi muutnud, **tuleta mulle enne lõpetamist meelde see GitHubi salvestada.**

Brauseris teed sa muudatused oma koopias (harus). **Salvestamine tähendab, et muudatus jõuab põhiversiooni (`main`).** Kui see jääb ainult harusse, ei ole see kindlalt alles — järgmine vestlus võib selle leida, aga ei pruugi. Kui salvestad, ütle mulle pärast ühe lausega, kas muudatus on nüüd põhiversioonis.

**Kui leiad vestluse alguses salvestamata haru**, ütle mulle ühe lausega, mis seal on, ja küsi, kas see põhiversiooni panna.

## Destilleeri, ära kalla

Aju ei ole prügikast. Toorest vestluslogi siia ei panda — pannakse see, mille sa sellest välja võtsid.

## Kaks eraldi otsust iga faili kohta

Enne faili lugemist või kirjutamist vasta eraldi:

1. **Kas see fail tohib jääda GitHubi ajalukku?**
2. **Kas AI-teenuse pakkuja tohib selle sisu töödelda?**

Esimesele vastab see, kus fail elab: ajus (GitHubis) või Drive'is. Teisele vastab [`riskihindamine/register.md`](riskihindamine/register.md) — seal on kirjas, mis tööriist tohib kliendiandmeid näha. Kui sa loed Drive'i faili, töötleb AI-pakkuja selle sisu ka siis, kui fail GitHubi ei lähe.

Kui registrit veel ei ole või tööriista seal ei ole, ütle seda ja paku riskihindamist.

Kui teise küsimuse vastus on “ei”, **ära ava, lisa, loetle ega ühenda seda faili AI sessioonis.** Anonümiseeri see esmalt offline-tööriistaga.

Kui fail on juba varem commit'itud, ei eemalda kustutamine ega `.gitignore` seda ajaloost.

## Mis ajju ei lähe

- **Kliendi tundlik info.** See ei lähe GitHubi. AI võib seda töödelda ainult siis, kui mul on selleks õigus ja valitud teenus sobib. Kui AI ei tohi seda töödelda, ära palu mul faili avada — anonümiseeri esmalt offline.
- **Paroolid, API võtmed, ligipääsud.** Mitte kunagi aju faili ega vestlusesse. Kui agent võtit vajab, kasuta turvalist seadistust või paroolihaldurit.

## Kliendi andmed elavad seal, kust neid saab kustutada

**Kliendi asjad — dokumendid, numbrid, isikuandmed — elavad minu agendikonto Drive'is. Mitte ajus.** Kui ma palun sul midagi sellist ajju kirjutada, tuleta see reegel meelde, enne kui teed.

See reegel otsustab, kus fail elab. Kui ma palun sul seda Drive'i faili lugeda, töötleb AI-pakkuja selle sisu. Kontrolli enne ka teist otsust.

Põhjus on üks ja seda ei saa tagantjärele parandada: **GitHub hoiab iga versiooni alles.** Tavaliselt on see hea — ma saan alati vaadata, mis eelmisel kuul otsustati. Aga see tähendab ka, et kustutatud fail ei ole kadunud, ta on ajaloos. Kui klient palub oma andmed kustutada, või leping lõpeb, või säilitustähtaeg saab täis, siis *„ma kustutasin selle faili"* ei ole aus vastus.

Drive'ist saab kustutada. Ajaloost mitte.

**Ajju läheb see, mida ma õppisin.** *„Kolm klienti küsisid sama asja"* on minu teadmine ja jääb. Kes need kolm olid, ei lähe.

### Ja mis on minu puhul „kliendi andmed" — see otsustatakse üks kord

Sest see ei ole igal alal sama. Ühel on kliendi nimi portfoolio, teisel on ta kutsesaladus.

Kui ma pole seda siia veel kirja pannud, **küsi minult ja kirjuta mu vastus siia faili.** Kolm küsimust:

1. **Kas ma paneksin selle oma kodulehele?** Kui jah, siis ei ole see konfidentsiaalne.
2. **Kas mind häiriks, kui see jääks ajalukku igaveseks?** Kui jah, siis jääb see Drive'i.
3. **Kas mu amet teeb vastuse rangemaks, kui mu enda tunne ütleb?** Raamatupidaja, jurist, tervis, personalitöö — jah.

**Minu vastus:** *(täida ära — kuni siin on tühi, küsi enne kui kirjutad)*

### Kontrolli enne kirjutamist, mitte enne salvestamist

Kui reegel on olemas, siis **rakenda seda hetkel, kui sa faili kirjutad** — mitte siis, kui ma ütlen „salvesta GitHubi". Salvestamise hetkeks on töö juba tehtud ja GitHubi ajaloost ei saa seda enam ära võtta.

Ja kui reegel on kirjas mõne teise faili sees, siis see on **reegel minu kohta, mitte fakt selle faili kohta.**

## Kui ma jään kinni

Kui failis `01-mina/tulevane-mina.md` on kirjas mustrid — laused, mida ma endale räägin — ja üks neist tuleb välja **põhjusena, miks midagi mitte teha**, siis nimeta see üks kord, ühe lausega, ja mine tööga edasi. Mitte iga kord, kui ma kahtlen: kahtlus on tihti õigustatud ja väärib otsest vastust, mitte diagnoosi.

Ja **kui midagi läks hästi, lisa see tõendite nimekirja.** Seda ei muuda vaidlus, seda muudab nimekiri.

## Hoia ülekantavuse nimekiri värske

Failis [`kaasaskantavus.md`](kaasaskantavus.md) on kirjas, mis minu ajust töötab igas tööriistas ja mis on seotud ainult ühega. **Kui sa lisad midagi, mis töötab ainult ühes tööriistas** — automaatika, otsetee, ühendus — lisa sinna rida samas sessioonis.

Test: *kui ma avaksin selle repo homme teises tööriistas, kas see asi töötaks?* Kui ei, siis läheb nimekirja.
