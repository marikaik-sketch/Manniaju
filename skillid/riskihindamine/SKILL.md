---
name: riskihindamine
description: Teeb ülevaate kõigist AI-tööriistadest ja teenustest, mida ettevõte kasutab (konnektorid, AI-d, kõnede salvestajad, postkast, raamatupidamine jne), hindab iga tööriista andmekaitse riski ja kirjutab tulemuse dokumendiks — register ja iga tööriista hinnang eraldi. Kasuta, kui kasutaja ütleb «tee riskihindamine», «hinda riske», «kas seda tööriista tohib kliendiandmetega kasutada», kui võetakse kasutusele uus tööriist, konnektor või agent, kui teenusepakkuja muudab tingimusi, või kui on käes poolaasta ülevaatus.
---

# Riskihindamine

**Miks:** kui sa kasutad AI-d ja teisi teenuseid klientide või teiste inimeste andmetega, oled sina vastutav töötleja. Kirja pandud ja regulaarselt uuendatud riskihindamine näitab, et sa oled riskid läbi mõelnud.

Alus on Andmekaitse Inspektsiooni (AKI) kontrollnimekiri tehisaru kasutajale:
https://www.aki.ee/tehisaru/tehisaru-ja-andmekaitse/tehisaru-kasutusele-votjale

See on dokumentatsioon, mitte juriidiline arvamus. Kahtluse korral küsi juristilt või AKI-lt.

---

## 0. Kuhu failid lähevad

Vaata allpool jaotist **Minu valik**. Kui see on tühi, küsi enne kõike muud:

> *Kuhu ma riskihindamise failid panen?*
>
> *Minu soovitus: ajju, kausta `riskihindamine/`. Seal on ainult info tööriistade kohta, mitte klientide andmed, nii et GitHubi sobib see hästi — ja su AI näeb sealt alati, mis tööriist tohib kliendiandmeid näha. Soovi korral teen igast failist koopia ka sinu agendikonto Drive'i, näiteks kausta `Riskihindamine`.*

Kirjuta vastus jaotisse **Minu valik** ja edaspidi enam ei küsi.

**Register jääb alati ajju** (`riskihindamine/register.md`), ka siis, kui hinnangud lähevad ainult Drive'i. `AGENTS.md` vaatab sealt, mis tööriist tohib kliendiandmeid näha. Registris on ainult tööriistade nimed ja otsused, mitte kellegi isikuandmed.

## 1. Ülevaade: mis tööriistad on kasutusel

Tee see iga kord alguses.

1. **Vaata, mis on selles vestluses ühendatud.** Sa näed oma tööriistade nimekirja: konnektorid (Drive, Gmail, Kalender, GitHub jne) ja muud ühendused. Iga ühendus on tööriist, mis võib andmeid näha.
2. **Otsi ajust.** `AGENTS.md`, `kaasaskantavus.md`, kaust `skillid/` ja kõik muu, kus mõni teenus on nimega mainitud.
3. **Küsi kasutajalt see, mida sa ise ei näe.** Küsi korraga ühe rühma kaupa, mitte kõike ühe pika nimekirjana:
   - teised AI-d (ChatGPT, Gemini, Manus, Lovable jne)
   - kõnede salvestamine ja transkriptsioon (Zoom, Teams, Meet, Tactiq, Fathom jne)
   - post ja kalender (mis konto, isiklik või ettevõtte)
   - raamatupidamine, arved, pank
   - kliendihaldus, broneerimine, vormid kodulehel
   - kogukond ja sotsiaalmeedia
   - telefoni äpid ja brauseri laiendused, mis loevad teksti või kõnet
4. **Salvesta ülevaade** faili `riskihindamine/ulevaated/AAAA-KK-PP.md`: mis leiti, mis on uus võrreldes eelmise korraga, mis enam kasutusel ei ole.

## 2. Esimene sõel: kas tööriist näeb kliendiandmeid?

Iga leitud tööriista kohta küsi kasutajalt üks küsimus: **kas see tööriist näeb klientide, prospektide, töötajate või teiste inimeste andmeid?** (Nimi, kontakt, kiri, kõne, dokument, arve.)

- **Ei** → registrisse rida otsusega **«Lubatud ilma kliendiandmeteta»**. Täishinnangut ei ole vaja. Kui see kunagi muutub, tee täishinnang.
- **Jah** → läheb täishinnangusse (samm 3).
- **Ei tea** → käsitle nagu «jah».

Näita kasutajale nimekirja: need tööriistad lähevad täishinnangusse, need mitte. Alusta sellest, mis näeb kõige rohkem kliendiandmeid.

## 3. Täishinnang — üks tööriist korraga

Tee üks tööriist, näita tulemust, küsi, kas jätkata järgmisega. Ära tee kõiki korraga.

1. **Kirjelda töötlemist.** Tööriist ja pakett (näiteks tasuta, Pro, Team), milleks seda kasutatakse, kelle andmed, millised andmed. Kas on eriliiki andmeid: tervis, usk, seksuaalelu, ametiühing, biomeetria, süüteod?
2. **Käi läbi AKI 11 punkti.** Otsi vastused teenusepakkuja **ametlikest** dokumentidest (privaatsustingimused, andmetöötluse leping ehk DPA, abilehed) ja kirjuta iga vastuse juurde link ja kuupäev. Kui vastust ei leia, kirjuta **«teadmata»** ja mida selleks vaja on. **Ära arva.**
   1. **Õiguslik alus** — tavaliselt leping kliendiga või õigustatud huvi
   2. **Ainult vajalikud andmed** — kas tööriist saab rohkem, kui töö jaoks vaja?
   3. **Kui kaua andmeid hoitakse** — ka pärast kustutamist
   4. **Kus andmeid hoitakse** — EL-is või väljaspool? Kui väljaspool, mis alusel?
   5. **Kellel on ligipääs** — sh teenusepakkuja töötajad ja allhankijad
   6. **Kas on vaja mõjuhinnangut** — väikeettevõtte tavatöös enamasti mitte
   7. **Turvameetmed** — kaheastmeline sisselogimine, kes pääseb kontole ligi
   8. **Kas andmetega treenitakse AI-mudelit** — ja kus see on välja lülitatud
   9. **Kas inimesi on teavitatud** — kliendileping, privaatsusteade
   10. **Automaatsed otsused inimese kohta** ilma inimese kontrollita
   11. **Leping teenusepakkujaga (DPA) ja rollid** — kas DPA on olemas?
3. **Hinda riski.** Kaks küsimust: kui tõenäoline on, et midagi läheb valesti (madal / keskmine / kõrge), ja kui raske on tagajärg inimesele (madal / keskmine / kõrge). **Kõrgem kahest on riskitase.** Ütle inimkeeles, mis peaks juhtuma, et risk realiseeruks.
4. **Paku otsus välja.** Üks neist:
   - **Lubatud kliendiandmetega**
   - **Lubatud ilma kliendiandmeteta**
   - **Keelatud**
   - **Ootel** — ja mis puudub (näiteks „DPA küsitud, vastust ootan")
5. **Meetmed.** Mida teha riski vähendamiseks, kes teeb, millal. Konkreetsed sammud, mitte „ole ettevaatlik".
6. **Näita kasutajale.** Tema otsustab. Kui ta kinnitab, märgi registrisse kinnitamise kuupäev.

## 4. Salvesta

- Iga hinnang eraldi failina: `riskihindamine/hinnangud/AAAA-KK-PP-tooriist.md`
- Uuenda `riskihindamine/register.md` rida. Kui registrit veel ei ole, loo see allolevast põhjast.
- **Vana hinnangut ei kustutata.** Uus tuleb kõrvale, register osutab uuele. Ajalugu ongi tõend.
- Kui **Minu valik** ütleb, et koopia läheb ka Drive'i, salvesta sinna sama failinimega. Kui Drive'i salvestamine ei õnnestu, ütle seda ja anna fail allalaadimiseks — ära jäta hinnangut ajust välja.
- Tuleta meelde salvestada aju GitHubi põhiversiooni.

---

## Registri põhi

```markdown
# Tööriistade register ja riskihinnangud

<Ettevõte>, vastutav töötleja <nimi>. Loodud <kuupäev>.
Koopiad: <Drive'i kaust või «ei»>

**Otsused on ettepanekud; omanik kinnitab** (märgi veergu «Kinnitatud» kuupäev).

| Tööriist · pakett | Otsus | Riskitase | Hinnang | Järgmine ülevaatus | Kinnitatud |
|---|---|---|---|---|---|

## Kasutusel ilma kliendiandmeteta (täishinnangut ei tehtud)

<tööriistad, komaga eraldatud> — kui mõni neist hakkab kliendiandmeid nägema, tee täishinnang.

## Kasutusest väljas

<tööriist · kuupäev · kas konnektor on lahti ühendatud>
```

## Hinnangu põhi

```markdown
# Riskihinnang: <tööriist ja pakett> · <kuupäev>
Hindaja: <nimi>, <ettevõte> (vastutav töötleja)
Järgmine ülevaatus: <kuupäev + 6 kuud>

## Töötlemine
<milleks, kelle andmed, millised, eriliiki andmed jah/ei>

## AKI kontrollnimekiri
| # | Punkt | Vastus | Allikas (link, kuupäev) |
|---|---|---|---|
| 1 | Õiguslik alus | | |
| 2 | Ainult vajalikud andmed | | |
| 3 | Kui kaua hoitakse | | |
| 4 | Kus hoitakse | | |
| 5 | Kellel on ligipääs | | |
| 6 | Kas on vaja mõjuhinnangut | | |
| 7 | Turvameetmed | | |
| 8 | Kas treenitakse mudelit | | |
| 9 | Kas inimesi on teavitatud | | |
| 10 | Automaatsed otsused | | |
| 11 | DPA ja rollid | | |

## Riskitase
Tõenäosus: · Tagajärg: · Riskitase:
<üks-kaks lauset inimkeeles: mis peaks juhtuma>

## Otsus (ettepanek)
<Lubatud kliendiandmetega / Lubatud ilma kliendiandmeteta / Keelatud / Ootel: mis puudub>

## Meetmed
- <meede> · <kes> · <millal>
```

---

## Millal uuesti

- Uus tööriist, konnektor, agent või AI-äpp
- Teenusepakkuja muudab tingimusi — neid kirju tasub lasta AI-l läbi lugeda
- Pakett muutub (näiteks isiklik → Team, tasuta → tasuline)
- **Iga 6 kuu tagant** kõik read üle, ka siis, kui midagi ei muutunud
- Pärast turvaintsidenti või kahtlust

## Reeglid

- Faktid teenusepakkuja kohta ainult ametlikest allikatest, koos kuupäevaga. Otsi värsked tingimused iga kord uuesti — need muutuvad.
- **Omanik otsustab.** Skill pakub otsuse välja, omanik kinnitab.
- Paroole, API-võtmeid ega klientide andmeid hinnangu faili ei kirjutata.

---

## Minu valik

*(Täidetakse esimesel korral. Kuni siin on tühi, küsi enne alustamist.)*

- **Hinnangud ja ülevaated:**
- **Koopia Drive'i:**
- **Hindaja nimi ja ettevõte:**
