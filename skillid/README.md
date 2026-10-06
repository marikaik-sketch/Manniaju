# Skillid

Skill on juhend ühele korduvale tööle: **millal see käivitub, mida teha ja mis kujul tulemus on.** Kui sa oled mingi töö AI-ga korra hästi läbi teinud, kirjutad selle skilliks — ja järgmine kord läheb see samamoodi, ilma et peaksid uuesti seletama.

Iga skill on siin oma kaustas:

```
skillid/
  riskihindamine/
    SKILL.md
```

`SKILL.md` on tavaline tekstifail. **See töötab iga AI-ga** — Claude, ChatGPT, Codex, Manus — sest `AGENTS.md`-s on tabel, mis ütleb igale AI-le, mis skillid sul on ja millal neid kasutada.

---

## Kuidas uus skill tekib

Tee töö kõigepealt korra AI-ga läbi, päris töö peal. Kui tulemus on hea, ütle:

> *Tee sellest, mis me just tegime, skill. Pane see kausta `skillid/` ja lisa `AGENTS.md` tabelisse.*

## Mis ühes skillis on

```markdown
---
name: skilli-nimi
description: Mida see teeb ja millal seda kasutada — sõnad, mida sa ise ütleksid.
---

# Skilli nimi

## Millal
## Mida teha, samm-sammult
## Mis kujul tulemus on
## Mida mitte teha
```

Ülemine osa (`name`, `description`) on sama kuju, mida kasutavad Claude ja teised AI-d. Nii saab skilli hiljem ka mõne tööriista enda skillide hulka panna, kui see kunagi vaja on.

## Kaks reeglit

- **Üks skill, üks koopia.** Skill elab siin. Ära kopeeri seda teistesse kohtadesse — kaks koopiat lähevad lahku.
- **Valmis skill on algus, mitte lõpp.** Kui sa kasutad kellegi teise tehtud skilli, tee esimene jooks oma päris töö peal ja lase AI-l küsida, mis sinu olukorras teisiti on. Siis paranda skill ära.
