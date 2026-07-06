---
type: stats
generated: 2026-07-06
author: Brain-Guardian
run: 9
---

# Brain Statistics — 2026-07-06 (Guardian Run #9)

## Overzicht

| Metric | Waarde | Δ vs Run #8 |
|---|---|---|
| Totaal wiki-nodes | 147 | +12 |
| KG-verbindingsnodes | 57 | +6 |
| Conflictnotes | 5 | 0 |
| Totaal KG-bestanden (excl. stats) | 62 | +8 |
| Gemiddelde quality_score | 0.867 | +0.007 |
| Gemiddelde confidence_score | 0.888 | +0.007 |
| Gemiddelde knowledge_score | 0.880 | — |
| Notes met quality-check-needed | 0 | −21 |
| Nieuw since vorige run | 12 wiki + 6 KG | — |
| Merged duplicaten (deze run) | 0 | Epistemologie al gemerged in Run #7 |
| YAML-fixes (deze run) | 4 | Marktbubbels, Fil.v.d.Psychiatrie, Gesch.Neurowet., Neuropsych.Assessment |
| Usage_scores gecorrigeerd (deze run) | 131 | Batch-fout vorige run hersteld |
| Quality-check-needed tags verwijderd | 21 | Alle 21 hadden voldoende bronnen |
| Cross-links toegevoegd | 1 | Beleggen Beloningssysteem → Psychologie Beloningssysteem |

> **Noot Run #9:** 12 nieuwe wiki-notes (3 per discipline) + 6 nieuwe KG-nodes toegevoegd door Knowledge-Hunter. 4 notes hadden non-standaard frontmatter (Agent1-KnowledgeHunter schema zonder `category:`, scores of `revision_history`) — volledig gerepareerd inclusief bronnen uit in-text citaties. Kritieke correctie: usage_scores waren in een vorige batch-run op 0.0 gezet door een regex-fout in grep; alle 131 notes met afwijkende scores zijn hersteld op basis van exact Python string-matching. 21 stale `quality-check-needed` tags verwijderd (alle 21 hadden adequate bronnen).

---

## Per Discipline

| Discipline | Nodes | Δ | Gem. kwaliteit | Gem. confidence | Nieuwste note |
|---|---|---|---|---|---|
| 🟢 Psychologie | 44 | +3 | 0.851 | 0.882 | Lateralisatie & Hemisferische Specialisatie |
| 🔵 Filosofie | 36 | +3 | 0.877 | 0.887 | Het Inductieprobleem & Causaliteit (Hume) |
| 🟡 Geschiedenis | 33 | +3 | 0.881 | 0.899 | Geschiedenis van de Neurowetenschappen |
| 🔴 Beleggen | 34 | +3 | 0.863 | 0.878 | Marktbubbels & Irrational Exuberance |
| **Totaal** | **147** | **+12** | **0.867** | **0.888** | — |

> **Noot Filosofie:** 36 totaal inclusief deprecated `Epistemologie`-stub (quality_score: 0.0); 35 actieve content-notes.

> **Noot Beleggen:** `Beloningssysteem & Dopamine` in Beleggen heeft nu cross-link naar Psychologie-versie. Beide notes zijn intentioneel: Psychologie-versie = neurowetenschappelijk fundament, Beleggen-versie = financieel-besluitvormingsperspectief.

---

## YAML-fixes Run #9

| Note | Probleem | Oplossing |
|---|---|---|
| Marktbubbels & Irrational Exuberance | `discipline:` ipv `category:`, geen scores, geen revision_history | Volledig YAML-schema; 6 bronnen (Kindleberger, Minsky, Shiller, Reinhart & Rogoff, Garber) |
| Filosofie van de Psychiatrie | Zelfde non-standaard schema | Volledig YAML-schema; 5 bronnen (Szasz, Foucault, Boorse, Wakefield, Jaspers) |
| Geschiedenis van de Neurowetenschappen | Zelfde non-standaard schema | Volledig YAML-schema; 3 bronnen (Finger, Kandel, Bear) |
| Neuropsychologisch Assessment & Testpsychologie | Zelfde non-standaard schema | Volledig YAML-schema; 5 bronnen (Lezak, Luria, Reitan, Strauss, Shallice & Burgess) |

---

## Top 10 Meest Verbonden Nodes

| # | Note | Backlinks | Discipline |
|---|---|---|---|
| 1 | Gedragseconomie & Cognitieve Biases | 34 | 🔴 Beleggen |
| 2 | Falsifieerbaarheid & Wetenschapsfilosofie | 27 | 🔵 Filosofie |
| 3 | Epistemologie & Kennistheorie | 24 | 🔵 Filosofie |
| 4 | Emotieregulatie | 23 | 🟢 Psychologie |
| 5 | Filosofie van de Geest | 22 | 🔵 Filosofie |
| 6 | Ethiek | 21 | 🔵 Filosofie |
| 7 | Executieve Functies & Prefrontale Cortex | 21 | 🟢 Psychologie |
| 8 | Neuroplasticiteit | 21 | 🟢 Psychologie |
| 9 | Klinische Psychologie | 20 | 🟢 Psychologie |
| 10 | Marktpsychologie & Beurscrises | 19 | 🔴 Beleggen |

> **Observatie:** Gedragseconomie & Cognitieve Biases blijft het best verbonden concept (34 unieke backlinks) — een kruispunt tussen psychologie, beleggen en filosofie. Falsifieerbaarheid staat verrassend hoog (#2) als methodologisch anker voor alle vier disciplines. De top 10 is bijna gelijk verdeeld: 4 Psychologie, 4 Filosofie, 2 Beleggen — Geschiedenis ontbreekt, wat een structureel verbindingsgebrek signaleert.

---

## Groeisnelheid

| Periode | Nieuwe notes |
|---|---|
| Run #1–#5 (ca. 01-07 t/m 03-07) | ~80 notes (initiële vault-vulling) |
| Run #6 (03-07) | +11 notes |
| Run #7 (04-07) | +13 notes |
| Run #8 (05-07) | +13 notes |
| Run #9 (06-07, vandaag) | +12 notes |
| **Schatting per dag** | **~20-25 notes** |

---

## Kennishiaten & Aanbevelingen

**Structureel gebrek:** Geschiedenis heeft de minste backlinks in de Top 10 — slechts indirect via verbindingen als De Verlichting en De Wetenschappelijke Revolutie. Aanbevolen: meer expliciete cross-links van Psychologie/Filosofie naar historische context.

**Ontbrekende verbindingen:**
1. `Lateralisatie & Hemisferische Specialisatie` heeft 0 backlinks — recente note die nog niet geïntegreerd is in het netwerk
2. `Marktbubbels & Irrational Exuberance` heeft 0 backlinks — zojuist YAML-gecorrigeerd; links worden in volgende runs opgebouwd
3. Beleggen-notes in het algemeen hebben relatief weinig onderlinge verbindingen

**Prioriteit onderzoeksvragen:**
1. Hoe verhoudt de neurowetenschappelijke geschiedenis (Cajal, Broca) zich aan de psychiatriegeschiedenis en de opkomst van de DSM? → verbinding `Geschiedenis van de Neurowetenschappen` ↔ `Geschiedenis van de Psychiatrie` ↔ `Filosofie van de Psychiatrie`
2. Wat verklaart dat Geschiedenis zelden de meest verbonden discipline is terwijl historische patronen centraal staan in de vault-filosofie?
