---
type: stats
generated: 2026-07-04
author: Brain-Guardian
run: 6
---

# Brain Statistics — 2026-07-04 (Guardian Run #6)

## Overzicht

| Metric | Waarde | Δ vs Run #5 |
|---|---|---|
| Totaal wiki-nodes | 108 | +12 |
| KG-verbindingsnodes | 39 | +6 |
| Hypotheses | 15 | +3 |
| Conflictnotes | 2 | — |
| Totaal KG-bestanden | 60 | +8 |
| Gemiddelde quality_score | 0.866 | +0.003 |
| Gemiddelde confidence_score | 0.883 | +0.002 |
| Notes met quality-check-needed | 13 | — |
| Nieuw since vorige run | 12 wiki + 6 KG + 3 HYP | — |
| Merged duplicaten (deze run) | 0 | — |
| MOC-updates (deze run) | 4 | alle 4 MOC bijgewerkt |
| YAML-fixes (deze run) | 4 | related_nodes gevuld |
| Conflicten gedetecteerd (deze run) | 0 | — |

> **Noot:** 12 nieuwe wiki-notes toegevoegd door kennisagenten (Knowledge-Synthesizer/Hunter). 4 MOC-bestanden bijgewerkt met alle nieuwe notes. 4 notes hadden leeg related_nodes YAML ondanks body wikilinks — gecorrigeerd. 2 openstaande kennishiaten uit pending events: **Interoceptie** en **Serotonine & 5-HT systeem** (beide als knowledge_gap gepubliceerd, nog geen wiki-note aangemaakt).

---

## Per Discipline

| Discipline | Nodes | Δ | Gem. kwaliteit | Gem. confidence | Nieuwste note |
|---|---|---|---|---|---|
| 🟢 Psychologie | 34 | +3 | 0.852 | 0.884 | Alexithymia & Emotieblindheid |
| 🔵 Filosofie | 26 | +3 | 0.855 | 0.879 | Hermeneutiek |
| 🟡 Geschiedenis | 24 | +3 | 0.891 | 0.910 | De Opkomst van het Neoliberalisme |
| 🔴 Beleggen | 24 | +3 | 0.873 | 0.882 | Market Microstructure & Liquiditeit |
| **Totaal** | **108** | **+12** | **0.866** | **0.883** | — |

> **Noot Filosofie:** Gemiddelde inclusief deprecated `Epistemologie`-stub (quality_score: 0.0). Exclusief stub: **0.889**.

---

## Nieuwe Notes Deze Run (#6)

| Discipline | Note | Bronnen | Woorden |
|---|---|---|---|
| 🟢 Psychologie | Alexithymia & Emotieblindheid | 5 PMC/PubMed | ~970 |
| 🟢 Psychologie | Glymfatisch Systeem | 5 incl. Cell 2025 | ~1080 |
| 🟢 Psychologie | Somatische Markerstheorie (Damasio) | 5 incl. PNAS | ~1150 |
| 🔵 Filosofie | Hermeneutiek | 4 URL + 2 boeken | ~1390 |
| 🔵 Filosofie | Kritische Theorie & Frankfurt School | 3 incl. SEP | ~1145 |
| 🔵 Filosofie | Postmodernisme & De Ontbinding van Grote Narratieven | 5 incl. SEP | ~1249 |
| 🟡 Geschiedenis | De Zwarte Dood | 5 incl. PMC | ~1282 |
| 🟡 Geschiedenis | De Opkomst van het Neoliberalisme | 4 incl. Tandfonline | ~1065 |
| 🟡 Geschiedenis | Totalitarisme als Politiek Systeem | 5 incl. Library of Congress | ~1276 |
| 🔴 Beleggen | Technische Analyse | 4 | ~1275 |
| 🔴 Beleggen | Market Microstructure & Liquiditeit | 4 incl. BIS | ~1206 |
| 🔴 Beleggen | Risico vs. Onzekerheid — Knight's Onderscheid | 5 incl. MIT/SSRN | ~1254 |

**Kwaliteitsoordeel nieuwe notes:** Allen ≥968 woorden, ≥4 bronnen, wikilinks aanwezig. Geen nieuwe quality-check-needed flags.

---

## Top 10 Meest Verbonden Nodes

*(Gebaseerd op wikilink-backlinks — gehele vault inclusief KG-bestanden)*

| Rank | Note | Backlinks (vault-breed) | Discipline |
|---|---|---|---|
| 1 | Gedragseconomie & Cognitieve Biases | 69 | 🔴 Beleggen |
| 2 | Emotieregulatie | 57 | 🟢 Psychologie |
| 3 | Epistemologie & Kennistheorie | 56 | 🔵 Filosofie |
| 4 | Filosofie van de Geest | 53 | 🔵 Filosofie |
| 5 | Falsifieerbaarheid & Wetenschapsfilosofie | 53 | 🔵 Filosofie |
| 6 | Ethiek | 52 | 🔵 Filosofie |
| 7 | Sociale Psychologie | 50 | 🟢 Psychologie |
| 8 | Executieve Functies & Prefrontale Cortex | 50 | 🟢 Psychologie |
| 9 | ADHD & Executieve Disfunctie | 44 | 🟢 Psychologie |
| 10 | Efficiënte Markt Hypothese | 41 | 🔴 Beleggen |

**Observatie Run #6:** `Gedragseconomie & Cognitieve Biases` behoudt de #1 positie met 69 vault-brede backlinks. `Emotieregulatie` stijgt naar #2 (was #5 in run#5) — de 12 nieuwe notes linken er vrijwel allemaal naar. `Filosofie van de Geest` en `Executieve Functies` stijgen sterk door cross-disciplinaire verbindingen in nieuwe Filosofie- en Psychologie-notes. `Efficiënte Markt Hypothese` nieuw in top 10 (#10) door sterke verankering in de 3 nieuwe Beleggen-notes.

---

## Kwaliteitsaandachtspunten

Notes met `quality-check-needed` tag (13 stuks — ongewijzigd t.o.v. run #5):

| Note | Discipline | Reden |
|---|---|---|
| Cognitie & Gedrag | Psychologie | quality_score: 0.70 — bronnen aanwezig maar geen URL |
| Sociale Psychologie | Psychologie | quality_score: 0.70 — bronnen aanwezig maar geen URL |
| TOE - Statistiek | Psychologie | quality_score: 0.70 — bronnen aanwezig maar geen URL |
| Hersen & Gedrag | Psychologie | quality_score: 0.75 — gedeeltelijke bronnen |
| Klinische Psychologie | Psychologie | quality_score: 0.75 — gedeeltelijke bronnen |
| Ontwikkelingspsychologie | Psychologie | quality_score: 0.75 — gedeeltelijke bronnen |
| Psychologie als Wetenschap | Psychologie | quality_score: 0.75 — gedeeltelijke bronnen |
| Neuroplasticiteit | Psychologie | quality_score: 0.82 — bronnen zonder URL |
| Epigenetica & Gen-Omgeving Interactie | Psychologie | quality_score: 0.80 — bronnen zonder URL |
| Inflatie & Koopkrachtbescherming | Beleggen | quality_score: 0.82 — bronnen gedeeltelijk |
| Moderne Portefeuilletheorie | Beleggen | quality_score: 0.85 — bronnen gedeeltelijk |
| Deugdethiek & Aristotelische Ethiek | Filosofie | quality_score: 0.78 — bronnen aanwezig |
| De Griekse Oudheid | Geschiedenis | quality_score: 0.82 — bronnen aanwezig maar geen URL |

**Prioriteit voor Knowledge-Synthesizer:** Focus op de 5 Psychologie-notes met quality_score 0.70–0.75. Voeg DOI/URL-bronnen toe (bijv. Stroop 1935, Milgram 1963, Piaget).

---

## Openstaande Kennishiaten

Twee pending knowledge_gap events zijn nog niet omgezet naar wiki-notes:

| Kennishiaat | Pending event | Prioriteit | Reden |
|---|---|---|---|
| **Interoceptie** | knowledge_gap_Interoceptie_0704.json | Hoog | Cross-link met Alexithymia, HPA-as, Somatische Markerstheorie — 3 recent toegevoegde notes verwijzen indirect naar dit concept |
| **Serotonine & 5-HT systeem** | knowledge_gap_Serotonine5HT_0704.json | Hoog | Neurobiologisch tegenwicht voor dopamine; cruciaal voor depressie, angst, CGT-farmacologie |

**Aanbeveling:** Deze twee notes moeten als volgende prioriteit aangemaakt worden door Knowledge-Synthesizer.

---

## Vault-Integriteit

- Duplicaten gedetecteerd: 0 (de twee `Beloningssysteem & Dopamine` notes zijn disciplinespecifiek ✓)
- Conflicten gevonden: 0 nieuw (2 bestaande CONFLICT-bestanden open: EMH vs Gedragseconomie, Verlichting vs Eugenica)
- Deprecated stubs: 1 (`Epistemologie.md` — correct gemarkeerd ✓)
- YAML-fixes: 4 notes hadden leeg `related_nodes: []` ondanks body wikilinks — gecorrigeerd ✓
- MOC-updates: alle 4 MOC-bestanden bijgewerkt met de 12 nieuwe notes ✓
- Processed events: 22 (< 50 drempel; geen archivering vereist)

---

## Groeisnelheid

- Wiki-nodes totaal run #1 → #6: van ~60 naar 108 in ~5 dagen (~9.6 nodes/dag gemiddeld)
- KG-nodes: van 0 naar 60 totale bestanden (39 KG + 15 HYP + 2 CONFLICT + 4 stats)
- Run #5 → #6: 12 wiki + 6 KG + 3 HYP in één cyclus — bovengemiddelde groei

---

## MOC-Updates Deze Run

| MOC | Toegevoegde links |
|---|---|
| MOC - Filosofie | Hermeneutiek, Kritische Theorie & Frankfurt School, Postmodernisme & De Ontbinding van Grote Narratieven |
| MOC - Psychologie BSc Jaar 1 | Alexithymia & Emotieblindheid, Glymfatisch Systeem, Somatische Markerstheorie (Damasio) |
| MOC - Geschiedenis | De Zwarte Dood, De Opkomst van het Neoliberalisme, Totalitarisme als Politiek Systeem |
| MOC - Beleggen | Technische Analyse, Market Microstructure & Liquiditeit, Risico vs. Onzekerheid — Knight's Onderscheid |
