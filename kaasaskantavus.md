# Mis töötab igal pool, mis on ühe tööriista külge kinni

Su aju on sinu oma ja töötab iga AI-ga. See fail on koht, kus see väide on **kontrollitav**, mitte lihtsalt lubatud.

Reegel on kirjas `AGENTS.md`-s: **kui sa lisad midagi, mis töötab ainult ühes tööriistas, lisa siia rida samas sessioonis.** Test võtab viis sekundit — *kui ma avaksin selle repo homme teises tööriistas, kas see asi töötaks?*

---

## Töötab igal pool

| Mis | Miks |
|---|---|
| Kõik `.md` failid — kogu su aju | Tavaline tekst. Ükski tööriist ei oma seda formaati. |
| `AGENTS.md` | Enamik AI tööriistu otsib seda faili ise. |
| `skillid/` | Iga skill on tavaline tekstifail. Iga AI leiab need üles, sest `AGENTS.md` ütleb, kus nad on ja millal neid kasutada. |
| `.gitignore` | Kuulub repo juurde ja git ise järgib seda. Hoiab paroolid ja võtmed GitHubist eemal, ükskõik kes su aju avab. |
| Agendikonto Drive | Sinu failid on sinu kontol, mitte AI-tööriista sees. Uus tööriist ühendatakse sama kontoga. |

## Ainult ühes tööriistas

| # | Mis | Kus | Mis see teeb | Kui palju taastamine maksab |
|---|---|---|---|---|
| 1 | `CLAUDE.md` automaatne lugemine | `CLAUDE.md` | Claude Code loeb selle iga vestluse alguses ise | Minut. Teises tööriistas ütle esimeses lauses: *„loe AGENTS.md"*. |
| 2 | Konnektorid (Drive, GitHub) | AI-tööriista seadetes, **mitte sinu repos** | Annavad AI-le ligipääsu agendikonto Drive'ile ja su ajule | Minut tööriista kohta. Uues tööriistas ühenda sama agendikonto ja sama repo uuesti. |

**Praegu on siin kaks rida ja see ongi õige.** Sa alles alustad. Iga kord, kui sa lisad automaatika, otsetee või ühenduse, tuleb rida juurde — ja kaheksa nädala pärast tead sa täpselt, mida sa peaksid uuesti ehitama, kui sa tööriista vahetad.

---

## Kui sa ühel päeval tööriista vahetad

1. Kontrolli, kas uus tööriist loeb `AGENTS.md`. Kui ei, ütle talle igas vestluses ise, kuni ta hakkab.
2. Vaata see nimekiri läbi ja ehita uuesti ainult see, mida sa päriselt kasutad.
3. Lase üks päris töö algusest lõpuni läbi ja **kontrolli tulemust, mitte raportit.** AI, kes ei suuda juhist täita, kirjeldab vahel edu, mida tal ei olnud.
