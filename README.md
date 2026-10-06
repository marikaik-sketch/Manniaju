# Minu ettevõtte aju

> Sinu aju on kaust tavalisi tekstifaile, mida su AI saab lugeda ja kirjutada. Ei rohkemat. Kogu maagia on selles, et see on ühes kohas ja alati kaasas.

See kaust on praegu peaaegu tühi. **Nii peabki olema** — see täitub siis, kui sa siin oma päris tööd teed.

---

## Alusta siit

1. **Ütle oma AI-le:** *„Loe mu aju läbi ja ütle, mis siin on ja mis on veel tühi."*
2. **Ava [`TEEMAD.md`](TEEMAD.md)** — üheksa teemat, mida su aju sinu kohta teada tahab. Alusta kahest esimesest.
3. **Ava [`KUIDAS-KASUTADA.md`](KUIDAS-KASUTADA.md)** — valmis laused, mida sa võid otse kopeerida. Sealhulgas küsimused, mida sa ise ajult küsid, kui sinna on juba midagi kogunenud.

**Üks harjumus, mis hoiab kõik koos:**

> **Lõpeta salvestamisega.**
> Kui lõpetad: *„salvesta kõik muudatused GitHubi põhiversiooni."*

Brauseris alustab iga uus vestlus GitHubi viimasest versioonist — seal ei pea midagi alla tõmbama. Aga AI teeb muudatused oma koopias ja jääb ootama. Kui sa ei ütle „salvesta", jäävad need kõrvalharusse. Järgmine vestlus leiab need tihti üles ja küsib, aga mitte alati. Kindel on ainult põhiversioon.

---

## Mis kus on

**Kaks faili ütlevad, KUIDAS käituda:**

| Fail | Mis see on |
|---|---|
| [`AGENTS.md`](AGENTS.md) | **Juhend.** Kuidas minuga töötada. Iga AI loeb selle esimesena. |
| [`CLAUDE.md`](CLAUDE.md) | Viit `AGENTS.md`-le, Claude Code'i jaoks. |

**Üks fail ütleb, mis on PRAEGU tõsi:**

| Fail | Mis see on |
|---|---|
| [`HETKESEIS.md`](HETKESEIS.md) | Eesmärk, praegune fookus, kus kinni jääb, mis on otsustatud ja mis katsetus. **AI loeb selle kohe pärast `AGENTS.md`-d.** **(1, 7)** |

**Kõik ülejäänu ütleb, MIS on tõsi.** Number sulgudes on teema number [`TEEMAD.md`](TEEMAD.md)-st:

| Fail | Mis sinna käib |
|---|---|
| `01-mina/kes-ma-olen.md` | Nimi, ettevõte, mida ma müün ühe lausega |
| `01-mina/stiil-ja-toon.md` | Kuidas ma kirjutan ja räägin **(3)** |
| `01-mina/tulevane-mina.md` | Kes ma olen, kui see kõik töötab **(9 — vabatahtlik)** |
| `02-pakkumine/ideaalklient.md` | Kellega ma tahan töötada ja kellega mitte **(2)** |
| `02-pakkumine/teenused.md` | Mida ma müün **(4)** |
| `02-pakkumine/hinnastamine.md` | Mis hinnaga **(4)** |
| `02-pakkumine/kliendi-tulemus.md` | Mis on kliendi jaoks pärast teisiti, ja mis seda tõestab **(6)** |
| `03-protsessid/kliendi-teekond.md` | Mis juhtub, kui klient ütleb jah **(5)** |
| `03-protsessid/mis-kordub.md` | Mis on iga kliendiga täpselt ühesugune **(5)** |
| `03-protsessid/pohjad.md` | Dokumendid, mida sa iga kord uuesti teed — leping, pakkumine, kokkuvõte **(5)** |
| `04-turundus/kanalid.md` | Kust kliendid tulevad **(7)** |
| `04-turundus/lood-ja-laused.md` | Laused ja lood, mis päriselt töötavad |
| `05-otsused/minu-numbrid.md` | Numbrid: käive, kliendid, mitut klienti ma jõuan **(1)** |
| `05-otsused/mis-on-proovitud.md` | Mis ei töötanud ja mille juurde ei ole vaja tagasi tulla **(8)** |
| `05-otsused/otsuste-logi.md` | Mis otsustati, millal, miks |

**Ja kaks kausta, mis täituvad töö käigus:**

| Kaust | Mis sinna käib |
|---|---|
| `skillid/` | Sinu skillid — juhendid korduvate tööde jaoks. Üks on juba sees: riskihindamine. Vt [`skillid/README.md`](skillid/README.md). |
| `riskihindamine/` | Tekib esimesel riskihindamisel: millised tööriistad sul kasutusel on ja kas nad tohivad kliendiandmeid näha. |

**Ja üks koht, mis ei ole siin üldse: agendikonto Drive.** Seal elavad sinu töödokumendid, kliendifailid ja toormaterjal. AI loeb neid konnektoriga. Ajju läheb ainult see, mida sa neist õppisid.

---

## Kaks küsimust enne iga faili

1. **Kas see fail tohib jääda GitHubi ajalukku?**
2. **Kas AI-teenuse pakkuja tohib selle sisu töödelda?**

| Materjal | GitHubi ajalukku? | Kas AI võib töödelda? | Kuhu |
|---|---|---|---|
| Destilleeritud äriteadmine ja protseduurid | Jah | Jah | Braini kaustad |
| Toormaterjal, töödokumendid, kliendifailid | Ei | Jah, kui tööriist on selleks lubatud (vt riskihindamine) | Agendikonto Drive |
| Materjal, mida AI ei tohi töödelda | Ei | Ei | Jääb sinna, kus ta on; agendikontole ei lähe |
| Paroolid, API võtmed, ligipääsud | Ei | Ei | Paroolihaldur või turvaline seadistus |

Drive'i faili avamine AI-s tähendab, et AI-pakkuja töötleb selle sisu — ka siis, kui fail GitHubi ei lähe.

**Destilleeri, ära kalla.** Aju ei ole prügikast. Toorest vestluslogi siia ei panda — pannakse see, mille AI sellest välja võttis.

---

## Kui su AI ei ole Claude

Su aju on tavalised tekstifailid, mis kuuluvad sulle. Nad töötavad iga AI-ga. Ütle uuele tööriistale: **„loe AGENTS.md"** — ja ta teab, kuidas siin käituda.

Mis töötab igal pool ja mis on ühe tööriista külge kinni, on kirjas failis [`kaasaskantavus.md`](kaasaskantavus.md).
