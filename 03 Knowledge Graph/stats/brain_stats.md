---
type: stats
generated: 2026-07-03
author: Brain-Guardian
run: 4
---

# Brain Statistics — 2026-07-03 (Guardian Run #4)

## Overzicht

| Metric | Waarde | Δ vs Run #3 |
|---|---|---|
| Totaal wiki-nodes | 80 | +8 |
| KG-verbindingsnodes | 40 | +9 |
| Conflictnotes | 2 | — |
| Totaal KG-bestanden | 40 | +9 |
| Gemiddelde quality_score | 0.861 | -0.001 |
| Gemiddelde confidence_score | 0.881 | — |
| Notes met quality-check-needed | 13 | +4 |
| Nieuw since vorige run | 8 | — |
| Merged duplicaten (deze run) | 0 | — |
| Schema-migraties (deze run) | 4 | nieuw veld |
| Conflicten gedetecteerd (deze run) | 0 | — |

> **Noot:** 4 nieuwe notes hadden non-standaard YAML-schema (`bronnen:` i.p.v. `sources:`). Brain-Guardian heeft ze gemigreerd naar volledig standaard schema en `quality-check-needed` toegevoegd omdat source-URLs ontbreken voor verificatie.

---

## Per Discipline

| Discipline | Nodes | Gem. kwaliteit | Gem. confidence | Nieuwste note |
|---|---|---|---|---|
| 🟢 Psychologie | 26 | 0.84 | 0.88 | Sociale Cognitie & Theory of Mind |
| 🔵 Filosofie | 19 | 0.85 | 0.85 | Nihilisme & Absurdisme |
| 🟡 Geschiedenis | 18 | 0.90 | 0.91 | De Val van het Westerse Romeinse Rijk |
| 🔴 Beleggen | 17 | 0.88 | 0.89 | Valuatie & DCF-analyse |
| **Totaal** | **80** | **0.861** | **0.881** | — |

---

## Top 10 Meest Verbonden Nodes

*(Gebaseerd op backlinks — gehele vault; usage_score = backlinks / 80)*

| Rank | Note | Backlinks | usage_score | Discipline |
|---|---|---|---|---|
| 1 | Ethiek | 31 | 0.388 | 🔵 Filosofie |
| 2 | Gedragseconomie & Cognitieve Biases | 30 | 0.375 | 🔴 Beleggen |
| 3 | Epistemologie *(deprecated redirect)* | 26 | 0.325 | 🔵 Filosofie |
| 4 | Emotieregulatie | 25 | 0.313 | 🟢 Psychologie |
| 5 | Epistemologie & Kennistheorie | 24 | 0.300 | 🔵 Filosofie |
| 6 | Falsifieerbaarheid & Wetenschapsfilosofie | 22 | 0.275 | 🔵 Filosofie |
| 7 | De Verlichting | 21 | 0.263 | 🟡 Geschiedenis |
| 8 | ADHD & Executieve Disfunctie | 21 | 0.263 | 🟢 Psychologie |
| 9 | Klinische Psychologie | 20 | 0.250 | 🟢 Psychologie |
| 10 | Sociale Psychologie | 19 | 0.238 | 🟢 Psychologie |

**Observatie:** Filosofie domineert de top met `Ethiek` als absolute knooppunt van het netwerk (31 backlinks). `Gedragseconomie & Cognitieve Biases` is de sterkste interdisciplinaire brug tussen Beleggen, Psychologie en Filosofie.

**Opmerkelijk verschil t.o.v. Run #3:** backlink-counts zijn lager dan eerder gerapporteerd — dit kan wijzen op telfouten in vorige meting of op het deprecaten van de `Epistemologie`-redirect die veel pseudo-links genereerde. Actuele telling is betrouwbaarder.

---

## Schema-migraties (deze run)

| Note | Discipline | Probleem | Actie |
|---|---|---|---|
| Deugdethiek & Aristotelische Ethiek | Filosofie | `bronnen:` i.p.v. `sources:`; geen scores | Volledig schema toegevoegd; quality-check-needed |
| Epigenetica & Gen-Omgeving Interactie | Psychologie | `bronnen:` i.p.v. `sources:`; geen scores | Volledig schema toegevoegd; quality-check-needed |
| De Griekse Oudheid | Geschiedenis | `bronnen:` i.p.v. `sources:`; geen scores | Volledig schema toegevoegd; quality-check-needed |
| Inflatie & Koopkrachtbescherming | Beleggen | `bronnen:` i.p.v. `sources:`; geen scores | Volledig schema toegevoegd; quality-check-needed |

---

## Notes met quality-check-needed (13 totaal)

Nieuw gemigreerd (4) — source-URLs ontbreken, inhoud is solide:
- `Deugdethiek & Aristotelische Ethiek`
- `Epigenetica & Gen-Omgeving Interactie`
- `De Griekse Oudheid`
- `Inflatie & Koopkrachtbescherming`

Reeds bestaand (9) — overgedragen van vorige runs.

**Actie:** bij de volgende Knowledge-Hunter run source-URLs toevoegen aan de 4 gemigreerde notes.

---

## Bestaande Conflicten

| Conflictnote | Status |
|---|---|
| `(CONFLICT) EMH vs Gedragseconomie.md` | Openstaand — verificatie nodig |
| `(CONFLICT) Verlichting vs Eugenica.md` | Openstaand — verificatie nodig |

---

## Groeisnelheid

| Run | Wiki-nodes | KG-nodes | Δ wiki |
|---|---|---|---|
| Run #1 (baseline) | ~40 | — | — |
| Run #2 | 64 | ~29 | +24 |
| Run #3 | 72 | 31 | +8 |
| Run #4 (heden) | 80 | 40 | +8 |

**Schatting:** ~8 wiki-nodes per dag (stabiele groeisnelheid).
**KG-groei:** +9 verbindingsnodes deze run — synthese houdt gelijke tred met feitencollectie.
**KG/Wiki-ratio:** 40/80 = 0.50 — voor elke 2 wiki-nodes bestaat er 1 synthese-node. Gezonde verhouding.

---

## Monitoring: Lage Connectiviteit

| Note | Backlinks | Status |
|---|---|---|
| Inflatie & Koopkrachtbescherming | 0 | Nieuw — aandacht nodig |
| Epigenetica & Gen-Omgeving Interactie | 0 | Nieuw — aandacht nodig |
| Deugdethiek & Aristotelische Ethiek | 2 | Laag — verbindingen uitbreiden |
| De Griekse Oudheid | 2 | Laag — verbindingen uitbreiden |

---

> Guardian Run #4 | 2026-07-03 | Brain-Guardian
