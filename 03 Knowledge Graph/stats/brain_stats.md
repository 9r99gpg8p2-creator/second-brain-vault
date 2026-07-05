---
type: stats
generated: 2026-07-05
author: Brain-Guardian
run: 7
---

# Brain Statistics — 2026-07-05 (Guardian Run #7)

## Overzicht

| Metric | Waarde | Δ vs Run #6 |
|---|---|---|
| Totaal wiki-nodes | 119 | +11 |
| KG-verbindingsnodes | 45 | +6 |
| Hypotheses | 18 | +3 |
| Conflictnotes | 3 | +1 |
| Totaal KG-bestanden | 73 | +13 |
| Gemiddelde quality_score | 0.857 | −0.009 |
| Gemiddelde confidence_score | 0.884 | +0.001 |
| Notes met quality-check-needed | 21 | +8 |
| Nieuw since vorige run | 11 wiki + 6 KG + 3 HYP | — |
| Merged duplicaten (deze run) | 0 | — |
| MOC-updates (deze run) | 4 | alle 4 MOC bijgewerkt |
| YAML-fixes (deze run) | 8 | KnowledgeHunter-schema → standaard |
| Conflicten gedetecteerd (deze run) | 1 | Naturalisme vs. Fenomenologie |

> **Noot:** 11 nieuwe wiki-notes toegevoegd door Knowledge-Hunter. 8 notes hadden niet-standaard YAML (KnowledgeHunter-schema met `discipline:`, `bronnen:`, `kleur:`, `aangemaakt:`, `links:`-velden) — alle 8 geconverteerd naar standaard schema + quality-check-needed tag toegevoegd (bronnen zonder URL). 5 pre-bestaande notes (Valutamarkten, Esthetiek, Rechtsfilosofie, Slavernij, Persoonlijkheidsstoornissen) teruggevonden in filesystem maar ontbrekend in MOC-tabellen — toegevoegd. Kwaliteitsgemiddelde daalt licht door 8 nieuwe quality-check-needed notes (quality_score: 0.75).

---

## Per Discipline

| Discipline | Nodes | Δ | Gem. kwaliteit | Gem. confidence | Nieuwste note |
|---|---|---|---|---|---|
| 🟢 Psychologie | 37 | +3 | 0.850 | 0.881 | Serotoninesysteem & 5-HT Neurotransmissie |
| 🔵 Filosofie | 28 | +2 | 0.847 | 0.877 | Merleau-Ponty & Corps Propre |
| 🟡 Geschiedenis | 27 | +3 | 0.875 | 0.902 | Koloniale Psychiatrie & Pathologisering van Abnormaliteit |
| 🔴 Beleggen | 27 | +3 | 0.859 | 0.876 | Narratieve Economie & Virale Financiële Verhalen |
| **Totaal** | **119** | **+11** | **0.857** | **0.884** | — |

> **Noot Filosofie:** 28 actieve content-nodes (exclusief deprecated `Epistemologie`-stub, quality_score: 0.0). Inclusief stub: 29 totaal. Esthetiek & Filosofie van de Kunst en Rechtsfilosofie & Juridische Epistemologie waren pre-bestaande notes die ontbraken in de MOC-tabel — deze run toegevoegd.

---

## Nieuwe Notes Deze Run (#7)

| Discipline | Note | Bronnen | Opmerking |
|---|---|---|---|
| 🟢 Psychologie | Interoceptie & Lichaamsgewaarwording | 3+ bronnen | Aangemaakt 07-04; quality-check-needed |
| 🟢 Psychologie | Psychoneuro-immunologie (PNI) | 4 bronnen incl. Dantzer 2008 (trust 10) | Aangemaakt 07-05; quality-check-needed |
| 🟢 Psychologie | Serotoninesysteem & 5-HT Neurotransmissie | 4 bronnen incl. Moncrieff 2022 | Aangemaakt 07-05; quality-check-needed |
| 🔵 Filosofie | Naturalisme & Wetenschappelijk Materialisme | 5 bronnen incl. Chalmers/Nagel (trust 10) | Aangemaakt 07-05; quality-check-needed |
| 🔵 Filosofie | Merleau-Ponty & Corps Propre | 3 bronnen incl. Merleau-Ponty 1945 (trust 10) | Aangemaakt 07-05; quality-check-needed |
| 🟡 Geschiedenis | Het Mongoolse Rijk | 3+ bronnen | Aangemaakt 07-04; quality-check-needed |
| 🟡 Geschiedenis | De Dertigjarige Oorlog & Verdrag van Westfalen | 4 bronnen incl. Parker/Wilson (trust 9) | Aangemaakt 07-05; quality-check-needed |
| 🟡 Geschiedenis | Koloniale Psychiatrie & Pathologisering van Abnormaliteit | 5 bronnen incl. Fanon/Foucault | Aangemaakt 07-05; quality-check-needed |
| 🔴 Beleggen | Commodities & Grondstoffen | 3+ bronnen | Aangemaakt 07-04; quality-check-needed |
| 🔴 Beleggen | Kelly Criterium & Optimale Positiegroottes | 4 bronnen incl. Kelly 1956 (trust 10) | Aangemaakt 07-05; quality-check-needed |
| 🔴 Beleggen | Narratieve Economie & Virale Financiële Verhalen | 4 bronnen incl. Shiller 2019 (trust 9) | Aangemaakt 07-05; quality-check-needed |

**Kwaliteitsoordeel nieuwe notes:** Inhoudelijk sterk (min. ~1000 woorden, goede structuur, wikilinks aanwezig, gerenommeerde bronnen). Allen kwaliteitsvlag vanwege ontbrekende bron-URLs — geen DOI/URL maar volledig geciteerde titels. Knowledge-Synthesizer moet URL/DOI toevoegen om kwaliteitsvlag te verwijderen.

---

## YAML-Fixes Deze Run (#7)

Acht notes hadden het niet-standaard KnowledgeHunter-schema. Alle 8 geconverteerd:

| Note | Discipline |
|---|---|
| Narratieve Economie & Virale Financiële Verhalen | 🔴 Beleggen |
| Kelly Criterium & Optimale Positiegroottes | 🔴 Beleggen |
| De Dertigjarige Oorlog & Verdrag van Westfalen | 🟡 Geschiedenis |
| Koloniale Psychiatrie & Pathologisering van Abnormaliteit | 🟡 Geschiedenis |
| Naturalisme & Wetenschappelijk Materialisme | 🔵 Filosofie |
| Merleau-Ponty & Corps Propre | 🔵 Filosofie |
| Serotoninesysteem & 5-HT Neurotransmissie | 🟢 Psychologie |
| Psychoneuro-immunologie (PNI) | 🟢 Psychologie |

---

## Top 10 Meest Verbonden Nodes

*(Gebaseerd op wikilink-backlinks — gehele vault inclusief KG-bestanden)*

| Rank | Note | Backlinks (vault-breed) | Discipline |
|---|---|---|---|
| 1 | Gedragseconomie & Cognitieve Biases | 89 | 🔴 Beleggen |
| 2 | Epistemologie & Kennistheorie | 59 | 🔵 Filosofie |
| 3 | Emotieregulatie | 60 | 🟢 Psychologie |
| 4 | Neuroplasticiteit | 59 | 🟢 Psychologie |
| 5 | Filosofie van de Geest | 58 | 🔵 Filosofie |
| 6 | Falsifieerbaarheid & Wetenschapsfilosofie | 57 | 🔵 Filosofie |
| 7 | Executieve Functies & Prefrontale Cortex | 55 | 🟢 Psychologie |
| 8 | Sociale Psychologie | 53 | 🟢 Psychologie |
| 9 | Ethiek | 52 | 🔵 Filosofie |
| 10 | Merleau-Ponty & Corps Propre | 15 | 🔵 Filosofie |

**Observatie Run #7:** `Gedragseconomie & Cognitieve Biases` stijgt van 69 naar 89 backlinks — de meest geciteerde note in de vault. `Emotieregulatie` stijgt naar 60 (was 57 in run #6). Opvallend: `Merleau-Ponty & Corps Propre` is een *nieuwe* note (aangemaakt 07-05) maar heeft direct al 15 backlinks — een teken dat dit concept in meerdere bestaande KG-nodes impliciet aanwezig was.

---

## Kwaliteitsaandachtspunten

Notes met `quality-check-needed` tag (21 stuks — +8 t.o.v. run #6):

**Originele 13 (ongewijzigd):**

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

**Nieuw getagd deze run (#8):**

| Note | Discipline | Reden |
|---|---|---|
| Narratieve Economie & Virale Financiële Verhalen | Beleggen | YAML-fix — bronnen zonder URL |
| Kelly Criterium & Optimale Positiegroottes | Beleggen | YAML-fix — bronnen zonder URL |
| De Dertigjarige Oorlog & Verdrag van Westfalen | Geschiedenis | YAML-fix — bronnen zonder URL |
| Koloniale Psychiatrie & Pathologisering van Abnormaliteit | Geschiedenis | YAML-fix — bronnen zonder URL |
| Naturalisme & Wetenschappelijk Materialisme | Filosofie | YAML-fix — bronnen zonder URL |
| Merleau-Ponty & Corps Propre | Filosofie | YAML-fix — bronnen zonder URL |
| Serotoninesysteem & 5-HT Neurotransmissie | Psychologie | YAML-fix — bronnen zonder URL |
| Psychoneuro-immunologie (PNI) | Psychologie | YAML-fix — bronnen zonder URL |

**Prioriteit voor Knowledge-Synthesizer:** (1) De 5 Psychologie-basisvakken met quality_score 0.70–0.75 — voeg DOI/URL-bronnen toe. (2) De 8 nieuw getagde notes — alle bronnen zijn volledig geciteerd maar missen een DOI/URL; een enkele toevoeging per bron volstaat om de tag te verwijderen.

---

## Conflicten

| Conflict | Status | Betrokken Disciplines |
|---|---|---|
| (CONFLICT) EMH vs Gedragseconomie | Open | Beleggen / Filosofie |
| (CONFLICT) Verlichting vs Eugenica | Open | Geschiedenis / Filosofie |
| (CONFLICT) Naturalisme vs Fenomenologie | Open — nieuw | Filosofie |

**Nieuw conflict Run #7:** `Naturalisme vs Fenomenologie` — Naturalisme/Dennett stelt dat qualia niet bestaan of reduceerbaar zijn tot fysische processen; Merleau-Ponty stelt dat het corps propre en eerste-persoonservaring irreducibel zijn. Conceptueel verbonden met Chalmers' hard problem. Synthese-kandidaat: neurophenomenology (Varela et al.).

---

## Vault-Integriteit

- Duplicaten gedetecteerd: 0 (de twee `Beloningssysteem & Dopamine` notes zijn disciplinespecifiek ✓)
- Conflicten gevonden: 1 nieuw (3 bestaande CONFLICT-bestanden totaal)
- Deprecated stubs: 1 (`Epistemologie.md` — correct gemarkeerd ✓)
- YAML-fixes: 8 notes (KnowledgeHunter-schema → standaard schema)
- MOC-updates: alle 4 MOC-bestanden bijgewerkt met 14 nieuwe/teruggevonden entries ✓
- MOC cleanup: 5 pre-bestaande notes teruggevonden in filesystem maar ontbrekend in MOC-tabellen ✓
- usage_score updates: 7 van de 8 YAML-fixes hadden bestaande backlinks ≥1 — scores bijgewerkt ✓
- Processed events: 48 (< 50 drempel; geen archivering vereist)

---

## Groeisnelheid

- Wiki-nodes totaal run #1 → #7: van ~60 naar 119 in ~6 dagen (~9.8 nodes/dag gemiddeld)
- KG-bestanden: 60 → 73 (+13 deze cyclus: 6 KG + 3 HYP + 1 CONFLICT + 3 stats-bestanden)
- Run #6 → #7: 11 wiki + 6 KG + 3 HYP + 1 CONFLICT in één cyclus

---

## MOC-Updates Deze Run

| MOC | Toegevoegde links |
|---|---|
| MOC - Beleggen | Commodities & Grondstoffen, Valutamarkten & Wisselkoersen, Kelly Criterium, Narratieve Economie |
| MOC - Filosofie | Naturalisme & Wetenschappelijk Materialisme, Merleau-Ponty & Corps Propre, Esthetiek & Filosofie van de Kunst *(cleanup)*, Rechtsfilosofie & Juridische Epistemologie *(cleanup)* |
| MOC - Geschiedenis | Het Mongoolse Rijk, De Dertigjarige Oorlog & Verdrag van Westfalen, De Slavernij & Transatlantische Slavenhandel *(cleanup)*, Koloniale Psychiatrie & Pathologisering van Abnormaliteit |
| MOC - Psychologie BSc Jaar 1 | Interoceptie & Lichaamsgewaarwording, Persoonlijkheidsstoornissen & Cluster B *(cleanup)*, Psychoneuro-immunologie (PNI), Serotoninesysteem & 5-HT Neurotransmissie |

*(cleanup) = pre-bestaande note die ontbrak in de MOC-tabel*

---

## Openstaande Kennishiaten

Geresolveerde kennishiaten (wiki-notes aangemaakt):

| Kennishiaat | Gepubliceerd event | Status |
|---|---|---|
| Interoceptie | knowledge_gap_Interoceptie_0704.json | ✅ Opgelost — wiki-note aanwezig |
| Serotonine & 5-HT systeem | knowledge_gap_Serotonine5HT_0704.json | ✅ Opgelost — wiki-note aanwezig |
| Merleau-Ponty | knowledge_gap_MerleauPonty_1142.json | ✅ Opgelost — wiki-note aanwezig |
| Koloniale Psychiatrie | knowledge_gap_KolonialePsychiatrie_1142.json | ✅ Opgelost — wiki-note aanwezig |
| Narratieve Economie | knowledge_gap_NarratieveEconomie_1142.json | ✅ Opgelost — wiki-note aanwezig |

**Geen nieuwe kennishiaten geïdentificeerd.** Het kennisnetwerk toont goede dekking over alle vier kerndisciplines. Potentieel onderbelichte gebieden voor toekomstige uitbreiding: Statistiek & Methodologie (diepgang van TOE-Statistiek uitbreiden), Cognitieve Revalidatie (bridge tussen Neuroplasticiteit en Klinische Psychologie), Islamitische Filosofie (aanvulling op Islamitische Gouden Eeuw).
