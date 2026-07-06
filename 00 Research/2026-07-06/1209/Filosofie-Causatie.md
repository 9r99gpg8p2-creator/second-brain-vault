# RAW DATA — Filosofie: Causatie & Contrafactuele Redenering

**Status:** RAW DATA — geen interpretatie, alleen bronmateriaal  
**Agent:** Agent1-KnowledgeHunter  
**Datum:** 2026-07-06  
**Databron:** Trainingskennis (Wikipedia-API geblokkeerd door egressbeleid)  
**source_score:** 8/10  
**confidence:** 0.88  
**novelty:** 1.0  
**trust_level:** hoog  

---

## Kernbronnen

- Lewis, D. (1973). Causation. *Journal of Philosophy*, 70(17), 556–567.
- Lewis, D. (1973). *Counterfactuals*. Harvard University Press.
- Hume, D. (1739). *A Treatise of Human Nature* (Book I, Part III).
- Hume, D. (1748). *An Enquiry Concerning Human Understanding* (Section VII).
- Mackie, J.L. (1965). Causes and conditions. *American Philosophical Quarterly*, 2(4), 245–264.
- Pearl, J. (2000). *Causality: Models, Reasoning, and Inference*. Cambridge University Press.
- Woodward, J. (2003). *Making Things Happen: A Theory of Causal Explanation*. Oxford University Press.

---

## Definitie & Kernprobleem

- **Causaliteit:** de relatie waarbij een oorzaak een gevolg voortbrengt of daartoe bijdraagt.
- Centraal filosofisch probleem: wat IS causatie precies? Is het een relatie in de wereld, of een begrip dat wij opleggen?
- Kernvraag: hoe onderscheiden we causale verbanden van louter correlatieve samenhang?

---

## Hume's Analyse (Regularity Theory)

- Hume: twee begrippen van causatie:
  1. **Feitelijk:** A en B zijn contiguous in ruimte/tijd; A komt voor B; A en B gaan altijd samen (constant conjunction).
  2. **Mentaal:** de geest verwacht B na A (gewoontevorming, niet logische noodzaak).
- Probleem: Hume denkt dat causale noodzakelijkheid niet in de wereld zit maar in de geest.
- Regularity Theory: C veroorzaakt E als en slechts als alle gevallen van C gevolgd worden door E.
- Kritiek: onvoldoende voor causaliteit — dag volgt altijd op nacht, maar dag veroorzaakt nacht niet; correlatie ≠ causaliteit.

---

## INUS-conditie (Mackie 1965)

- INUS: een **I**nsufficient maar **N**on-redundant onderdeel van een **U**nnecessary maar **S**ufficient condities.
- Vb.: kortsluiting is onvoldoende (ook droog hout nodig), maar niet-redundant (zonder haar geen brand) in een complex van condities dat voldoende maar niet noodzakelijk is.
- Bevat de veelzijdigheid van causatie — meerdere oorzaakspaden mogelijk.

---

## Lewis' Contrafactuele Theorie (1973)

- **Kernstelling:** C veroorzaakt E als en slechts als, **als C niet had plaatsgevonden, E ook niet had plaatsgevonden**.
- Formule: `C → E` ≡ `¬C □→ ¬E` (in de dichtstbijzijnde mogelijke wereld zonder C, ontbreekt E ook).
- Gebaseerd op semantiek van mogelijke werelden (mogelijk-wereldenlogica, Kripke/Lewis).
- **Dichtstbijzijnde mogelijke wereld:** de wereld die het meest op de echte lijkt maar waarin C niet optreedt.

### Sterke punten Lewis
- Vangt asymmetrie van causatie (C vóór E).
- Verklaart waarom nacht dag niet veroorzaakt (verwijder dag → nacht verdwijnt ook, maar dit klopt niet in alle werelden).

### Problemen
1. **Preemption (voorkoming):** twee oorzaken A en B; A treft het doel, B was ook aanwezig maar niet actief. Contrafactueel: als A niet had geschoten, had B geschoten → gevolg is hetzelfde → A veroorzaakte het niet via Lewis? Maar intuïtief wél.
2. **Overdetermination:** twee onafhankelijke oorzaken produceren elk het gevolg — beide causaal maar geen van beide contrafactueel noodzakelijk.
3. **Transitivity-paradox:** als C→E→F, en contrafactueel C→F, maar intuitief C veroorzaakt F niet.
4. **Late preemption vs. early preemption:** subtiele varianten die het model belasten.

---

## Pearl's Struktureel Causaal Model (SCM)

- Pearl, J. (2000): mathematische formalisering via **directed acyclic graphs (DAGs)**.
- Variabelen als knooppunten; pijlen stellen directe causale relaties voor.
- **do-calculus:** P(Y | do(X=x)) vs. P(Y | X=x) — causale interventie vs. observatie.
- Ladder of Causation (Pearl & Mackenzie, 2018):
  1. **Associatie:** zie, waarneem (P(Y|X)).
  2. **Interventie:** doe, verander (P(Y|do(X))).
  3. **Counterfactual:** verbeeld, reflecteer (wat als X anders was geweest?).
- Cruciaal voor onderscheid between prediction en causal inference.

---

## Contrafactuele Logica

- **Contrafactueel:** een conditioneel waarvan de antecedent feitelijk onwaar is. "Als Caesar niet gekruist had…"
- Stalnaker (1968) en Lewis (1973) formaliseren via mogelijke-wereldensemantiek.
- **Similarity ordering:** werelden geordend naar gelijkenis met de actuele wereld.
- `φ □→ ψ` is waar als en slechts als in de dichtstbijzijnde φ-wereld ook ψ waar is.
- Problemen: vagueness van "similarity"; welke aspecten bepalen nabijheid?

---

## Interventionistische Theorie (Woodward 2003)

- C veroorzaakt E als het manipuleren van C (via interventie) E verandert.
- Gebaseerd op het idee dat causatie *in principe* manipuleerbaar is.
- Verbinding met wetenschappelijke praktijk: RCT's isoleren causale effecten via randomisatie.
- Kritiek: circulariteit — 'interventie' veronderstelt al causatie.

---

## Causatie in de Wetenschap & Psychologie

- Experimenteel onderzoek: randomized controlled trials (RCT's) als gouden standaard voor causale inferentie.
- Confounding: derde variabele verklaart verband A→B.
- Mediatie vs. moderatie: Baron & Kenny (1986).
- Granger causality (tijdsreeksen): of X de toekomst van Y beter voorspelt dan Y zichzelf.
- Necessary vs. Sufficient conditions: relevant voor diagnostiek (DSM-criteria).

---

## Causale Redenering in het Brein

- Studies tonen dat mensen van nature contrafactueel denken (Roese, 1997).
- **Upward counterfactuals:** als X anders was geweest, had het beter kunnen gaan → motivatie maar negatief affect.
- **Downward counterfactuals:** had erger kunnen zijn → positief affect.
- Neurowetenschappen: prefrontale cortex, anterieure cingulate cortex betrokken bij contrafactueel denken.
- Verbinding met spijt (Zeelenberg et al., 1998): spijt vereist contrafactueel denken ("als ik anders had gekozen…").

---

## Verbindingspunten (voor Knowledge Graph)

- → Epistemologie & Kennistheorie (Hume, inductieprobleem)
- → Het Inductieprobleem & Causaliteit (Hume) — BESTAAND
- → Falsifieerbaarheid & Wetenschapsfilosofie (Popper's view op causaliteit)
- → Logica & Kritisch Denken (contrafactuele logica)
- → Metafysica & Ontologie (causatie als metafysisch principe)
- → Filosofie van de Psychiatrie (DSM-causaliteitsvragen)
- → Psychologie als Wetenschap (RCT's, mediatie, moderatie)
- → Vrije Wil & Determinisme (causatie als basis voor determinisme)
- → Neuro-ethiek (causale toeschrijving bij schuld en verantwoordelijkheid)
- → Spijt & Emotieregulatie (contrafactueel denken)
