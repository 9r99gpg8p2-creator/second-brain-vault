---
type: concept
id: 58886b24-5ddd-4db3-9112-e13d99ccc7b7
title: Causatie & Contrafactuele Redenering
summary: Causatie is de filosofische relatie waarbij een oorzaak een gevolg voortbrengt; contrafactuele redenering analyseert wat er zou zijn gebeurd als de oorzaak anders was geweest.
category: Filosofie
tags: [concept, filosofie, metafysica, causaliteit, contrafactueel, logica, epistemologie, wetenschapsfilosofie]
aliases: [Causaliteit, Causale Redenering, Counterfactual Reasoning, Lewis causation]
sources:
  - url: https://doi.org/10.2307/2025310
    title: "Lewis (1973) — Causation"
    trust_level: 10
    publication_date: 1973
  - url: https://archive.org/details/atreatiseofhuman00hume
    title: "Hume (1739) — A Treatise of Human Nature"
    trust_level: 10
    publication_date: 1739
  - url: https://doi.org/10.1017/CBO9780511803161
    title: "Pearl (2000) — Causality: Models, Reasoning, and Inference"
    trust_level: 10
    publication_date: 2000
  - url: https://global.oup.com/academic/product/making-things-happen-9780195189537
    title: "Woodward (2003) — Making Things Happen"
    trust_level: 9
    publication_date: 2003
  - url: https://doi.org/10.2307/20009229
    title: "Mackie (1965) — Causes and Conditions"
    trust_level: 9
    publication_date: 1965
confidence_score: 0.88
quality_score: 0.88
freshness_score: 0.80
importance_score: 0.92
novelty_score: 1.0
knowledge_score: 0.88
usage_score: 0.0
related_nodes: []
revision_history:
  - version: 1
    date: 2026-07-06
    author: Knowledge-Synthesizer
    change: initial creation
---

# Causatie & Contrafactuele Redenering

**Kern:** Causatie is de metafysische relatie waarbij een oorzaak een gevolg voortbrengt of daartoe bijdraagt — de centrale vraag is of deze relatie in de wereld bestaat of een projectie van de menselijke geest is.

## Inhoud

### FEIT: Het Kernprobleem

Filosofen analyseren causaliteit op twee niveaus: (1) *metaphysisch* — wat is causatie als relatie in de werkelijkheid? en (2) *epistemisch* — hoe kennen we causale verbanden? Het onderscheid is niet triviaal: een causale relatie zien is niet hetzelfde als correlatie observeren.

### FEIT: Hume's Regulariteitstheorie (1739)

David Hume stelt dat wij causale noodzaak niet direct waarnemen. Bij observatie van biljardballen zien we enkel: (1) ruimtelijke en temporele aaneensluiting, (2) opeenvolging in tijd (A vóór B), en (3) *constant conjunction* (telkens wanneer A, ook B). De mentale verwachting van B na A is een gewoonte (*custom*), geen logische noodzaak. Causale noodzaak zit in de geest, niet in de wereld.

**Regulariteitstheorie:** C veroorzaakt E als en slechts als alle gevallen van C gevolgd worden door E.
**Fundamenteel probleem:** dag volgt altijd op nacht, maar dag *veroorzaakt* niet nacht. Correlatie is geen causaliteit — de regulariteitstheorie is onvoldoende.

### FEIT: INUS-conditie (Mackie, 1965)

Mackie verfijnt Hume via de INUS-conditie: een oorzaak is een **I**nsufficiënte maar **N**iet-redundante component van een **O**nnodig maar **V**oldoende complex van condities. Voorbeeld: kortsluiting is op zichzelf onvoldoende om brand te veroorzaken (droog hout is ook nodig), maar is niet-redundant (zonder kortsluiting geen brand in dit geval), en de gehele combinatie is voldoende maar niet noodzakelijk (er bestaan andere brandoorzaken). Dit legt de veelzijdigheid van causatie bloot: meervoudige oorzaakspaden zijn mogelijk.

### FEIT: Lewis' Contrafactuele Theorie (1973)

David Lewis herformuleert causaliteit in termen van mogelijke werelden. **Kernstelling:** C veroorzaakt E als en slechts als: *als C niet had plaatsgevonden, had E ook niet plaatsgevonden* — formeel: `¬C □→ ¬E`.

Dit berust op de semantiek van mogelijke werelden (Kripke/Lewis): een contrafactuele bewering is waar als en slechts als in de *dichtstbijzijnde mogelijke wereld* zonder C, E ook afwezig is. De dichtstbijzijnde mogelijke wereld is de wereld die het meest op de actuele wereld lijkt maar waarin C niet optreedt.

**Voordelen:** vangt de asymmetrie van causatie (oorzaak gaat aan gevolg vooraf); contraintuïtieve cases worden correct behandeld.

**Problemen:**
1. *Preemption (voorkoming):* schutter A schiet en doodt het slachtoffer; schutter B stond klaar maar hoefde niet te schieten. Contrafactueel: als A niet had geschoten, had B geschoten → dood toch. Lewis' theorie zegt dan dat A niet de oorzaak was — maar intuïtief wel.
2. *Overdetermination:* twee onafhankelijke oorzaken produceren elk het gevolg — beide zijn causaal maar geen van beide is contrafactueel noodzakelijk.
3. *Transitiviteitsparadox:* causale ketens A→B→C geven correct A→C, maar soms leidt dit tot contra-intuïtieve conclusies.
4. *Vaagheid van gelijkenis*: welke wereld is het "dichtstbijzijnde"? De similariteitsmaatstaf is onduidelijk.

### FEIT: Pearl's Structureel Causaal Model (2000)

Judea Pearl formaliseert causaliteit via **directed acyclic graphs (DAGs)**: knooppunten zijn variabelen, pijlen zijn directe causale relaties. Het cruciale onderscheid: `P(Y | X=x)` (conditionele waarschijnlijkheid — observatie) versus `P(Y | do(X=x))` (causale interventie — Pearl's *do*-calculus).

**Ladder of Causation (Pearl & Mackenzie, 2018):**
1. **Associatie** — zie en waarneem: `P(Y|X)`. Het niveau van statistiek en machine learning.
2. **Interventie** — doe en verander: `P(Y|do(X))`. Het niveau van experimenteel onderzoek.
3. **Counterfactual** — verbeeld en reflecteer: *wat als X anders was geweest?* Het niveau van retrospectief redeneren en schuld/verantwoordelijkheid.

Dit maakt Pearl's model direct relevant voor de sociale wetenschappen: een regressiecoëfficiënt beantwoordt een associatievraag, niet een interventievraag.

### FEIT: Interventionistische Theorie (Woodward, 2003)

James Woodward: C veroorzaakt E als het manipuleren van C via een interventie E verandert. Causatie is in principe manipuleerbaar. Verbinding met wetenschappelijke praktijk: randomized controlled trials (RCT's) isoleren causale effecten via randomisatie. **Kritiek:** circulair — "interventie" veronderstelt al een causale structuur.

### THEORIE: Causale Redenering in het Brein

Mensen denken van nature contrafactueel (Roese, 1997). Dit is adaptief: contrafactueel denken helpt bij leren van fouten en planning.
- *Upward counterfactuals* ("had beter kunnen zijn"): verhogen motivatie maar gaan gepaard met negatief affect.
- *Downward counterfactuals* ("had erger kunnen zijn"): verhogen tevredenheid.

Neurowetenschappelijk zijn prefrontale cortex en anterieure cingulate cortex betrokken bij contrafactueel redeneren. Spijt (Zeelenberg et al., 1998) is cognitief afhankelijk van contrafactueel denken: "als ik anders had gekozen, was het beter gegaan."

### INTERPRETATIE: Causatie in de Wetenschap

In de psychologie zijn drie causale vraagstukken centraal:
- **Mediatie vs. moderatie** (Baron & Kenny, 1986): mediatie beschrijft het mechanisme (C→M→E); moderatie beschrijft condities waaronder C E veroorzaakt.
- **Confounding**: een derde variabele verklaart het verband C→E zonder dat C E veroorzaakt.
- **Granger causaliteit** (tijdsreeksanalyse): of X de toekomst van Y beter voorspelt dan Y zichzelf — zwak causaal criterium.

## Klinische Relevantie

Causaliteitsdenken is fundamenteel voor de klinische neuropsychologie:

- **DSM-diagnostiek** hanteert impliciet causale logica: noodzakelijke en voldoende condities voor diagnoses, al wordt dit zelden expliciet gemaakt (cf. Borsboom's netwerkstheorie van psychopathologie).
- **Behandelevaluatie:** RCT's zijn de gouden standaard voor causale inferentie over behandeleffecten; quasi-experimentele designs zijn zwakkere substituten.
- **Forensische neuropsychologie:** schuld en verantwoordelijkheid veronderstellen causale toeschrijving — heeft hersenletsel geleid tot crimineel gedrag? Pearl's Ladder of Causation biedt een framework voor deze vragen.
- **Contrafactueel denken bij PTSS:** patiënten met PTSS vertonen excessief upward counterfactual denken ("als ik anders had gehandeld, was het niet gebeurd"), wat schuldgevoelens voedt.

## Verbanden

- [[02 Wiki/Filosofie/(C) Het Inductieprobleem & Causaliteit (Hume)]] — directe voorloper; Hume als grondlegger van de causatieproblematiek
- [[02 Wiki/Filosofie/(C) Epistemologie & Kennistheorie]] — causatie als kernvraag in epistemologie: hoe kennen we oorzaken?
- [[02 Wiki/Filosofie/(C) Metafysica & Ontologie]] — causatie als metafysisch principe; bestaan causale relaties in de wereld?
- [[02 Wiki/Filosofie/(C) Logica & Kritisch Denken]] — contrafactuele logica als formeel systeem (mogelijke-wereldensemantiek)
- [[02 Wiki/Filosofie/(C) Vrije Wil & Determinisme]] — causale determinisme als basis voor de vrije wil-discussie
- [[02 Wiki/Filosofie/(C) Falsifieerbaarheid & Wetenschapsfilosofie]] — Popper's visie op causaliteit en wetenschappelijke verklaring
- [[02 Wiki/Filosofie/(C) Neuro-ethiek]] — causale toeschrijving bij schuld, strafrechtelijke verantwoordelijkheid en hersenletsel
- [[02 Wiki/Psychologie/(C) Psychologie als Wetenschap]] — RCT's, mediatie/moderatie als causale inferentiemethoden
- [[02 Wiki/Geschiedenis/(C) De Opkomst van de Statistiek & Kansrekening]] — Pearl's causale grafen voortbouwen op statistische traditie
- [[02 Wiki/Psychologie/(C) Werkgeheugen & Baddeley's Model]] — contrafactueel denken vereist werkgeheugen voor het vasthouden van alternatieve scenario's

## Bronnen

1. Hume, D. (1739). *A Treatise of Human Nature* (Book I, Part III). John Noon.
2. Hume, D. (1748). *An Enquiry Concerning Human Understanding* (Section VII). A. Millar.
3. Mackie, J.L. (1965). Causes and conditions. *American Philosophical Quarterly*, 2(4), 245–264.
4. Lewis, D. (1973). Causation. *Journal of Philosophy*, 70(17), 556–567.
5. Lewis, D. (1973). *Counterfactuals*. Harvard University Press.
6. Pearl, J. (2000). *Causality: Models, Reasoning, and Inference*. Cambridge University Press.
7. Woodward, J. (2003). *Making Things Happen: A Theory of Causal Explanation*. Oxford University Press.
8. Roese, N.J. (1997). Counterfactual thinking. *Psychological Bulletin*, 121(1), 133–148.
9. Pearl, J., & Mackenzie, D. (2018). *The Book of Why*. Basic Books.

> Status: Verwerkt door Knowledge-Synthesizer | 2026-07-06
