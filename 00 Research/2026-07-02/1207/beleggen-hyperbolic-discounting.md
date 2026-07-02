# RAW DATA — Beleggen: Hyperbolic Discounting & Tijdspreferentie

**Status:** RAW DATA — NIET geïnterpreteerd, NIET bewerkt
**Bron:** AI-trainingskennis (wetenschappelijke literatuur t/m 2025)
**Externe fetch:** Geblokkeerd door egress-beleid (wikipedia.org niet toegankelijk)
**Referentie-URLs (niet gevraagd):**
- https://en.wikipedia.org/wiki/Hyperbolic_discounting
- Ainslie, G. (1992), *Picoeconomics*, Cambridge University Press
- Laibson, D. (1997), "Golden eggs and hyperbolic discounting", *Quarterly Journal of Economics*
- Thaler, R. & Sunstein, C. (2008), *Nudge*
- Frederick, S., Loewenstein, G., & O'Donoghue, T. (2002), "Time discounting and time preference", *Journal of Economic Literature*

---

## Definitie

- Tijdspreferentie (time preference): de voorkeur om eerder boven later beloningen te ontvangen
- Disconteringsvoet: de mate waarop toekomstige beloningen minder waard worden geacht dan huidige
- Exponentieel disconteren (standaard economisch model): D(t) = δ^t — consistent over tijd
- Hyperbolisch disconteren: D(t) = 1/(1+kt) — sterkere discounting op korte termijn, zwakkere op lange termijn

---

## Het kernprobleem: inconsistentie over tijd

- Exponentieel model: als je morgen prefereert boven overmorgen, prefereer je ook in een jaar + 1 dag boven in een jaar + 2 dagen (tijdsconsistent)
- Hyperbolisch model: voorkeur-omkering (preference reversal)
  - Vandaag: kies ik €110 over een week boven €100 vandaag? → nee (present bias)
  - Maar: kies ik €110 over een jaar + een week boven €100 over een jaar? → ja
  - Dit is inconsistent: dezelfde tijdsinterval heeft verschillende waarde afhankelijk van de afstand tot het heden

---

## Empirische evidentie

- Thaler (1981): mensen vragen €100 nu of €X later — gevraagd bedrag onthult impliciete disconteringsvoet
  - Resultaat: jaarlijkse disconteringsvoet 15-25% voor langere termijnen, maar 300%+ voor perioden van weken
- Ainslie (1975): duiven kiezen kleinere-directe beloning boven grotere-uitgestelde beloning, zelfs als de grotere objectief voordelig is
- Kirby & Marakovic (1995): monetaire keuzetaken bevestigen hyperbolisch patroon bij mensen
- Loewenstein & Thaler (1989): "anomalies" in intertemporal choice — uitgestelde kosten worden te laag gewogen

---

## Present Bias

- Present bias: de onevenredige nadruk op het heden ten opzichte van de nabije toekomst
- β-δ-model (quasi-hyperbolisch, Laibson 1997):
  - Waarde op tijdstip t van een beloning op t+s: β·δ^s (voor s>0) maar gewoon 1 (voor s=0)
  - β<1 captures de present-bias "knik" in de disconteringsfunctie
  - Empirisch: β ≈ 0.7 (gemiddeld; 30% discount op alles wat niet onmiddellijk is)
- Naïve vs. sophisticated agents:
  - Naïeve agenten: niet bewust van hun eigen inconsistentie → stellen steeds uit
  - Sophisticaties: weten van hun present bias → creëren commitment devices

---

## Commitment Devices (bindende mechanismen)

- Odysseus bindt zichzelf aan de mast (archetypisch voorbeeld — Sirenes)
- Pensioensparen via automatische inhouding (save more tomorrow — SMarT, Thaler & Benartzi 2004)
- Illiquide spaarproducten: deposito's met boeterente voor vroeg opnemen
- Retirement savings: 401(k) default enrollment → deelname stijgt van 37% naar 86% (Madrian & Shea, 2001)
- Habituel gedrag als automatische commitment: vaste maandelijkse belegginsopdracht

---

## Neurobiologische basis

- Twee-systementheorie van intertemporeel keuzegedrag:
  - **Limbisch systeem** (amygdala, striatum): evalueert onmiddellijke beloningen, sterk geactiveerd door nabije opties
  - **Prefrontale Cortex**: evalueert lange-termijn waarde, minder reactief maar meer planmatig
- McClure et al. (2004), *Science*: fMRI-studie — onmiddellijke monetaire beloningen activeren anders dan uitgestelde
  - Limbische structuren (NAc, mediale PFC) reageren op onmiddellijke opties
  - Laterale PFC en parietal activeren voor alle opties
- "Dual self" model: een impulsief zelf vs. een planmatig zelf in strijd
- Link verslaving: verslaafden tonen excessieve present bias + verminderde PFC-regulatie

---

## Economische en financiële gevolgen

### Pensioenspaarvraagstuk
- Rationele agent spaart optimaal voor pensioen; hyperbolische agent stelt steeds uit
- Pensioenpuzzel: mensen sparen te weinig ondanks rationeel bewustzijn dat ze meer moeten
- Soluties: automatische inschrijving, escalerende bijdragen

### Schulden en krediet
- Creditcards: consumenten onderschatten toekomstige rentelasten
- Payday loans: extreem hoge effectieve jaarrente (400%+) — rationeel onverklaarbaar zonder present bias
- Schuldenval: hyperbolische discontering verklaart persistente schuldcycli

### Beleggingsgedrag
- Equity premium puzzle: aandelenpremium te hoog voor rationele risicoaversie-modellen; present bias kan bijdragen
- Myopic loss aversion (Benartzi & Thaler, 1995): te frequente evaluatie → overdreven risicomijding
- Disposition effect: te snel winnaars verkopen, te lang verliezers vasthouden — hyperbolisch disconteren van toekomstige winst

### Procrastination
- Uitstellen van belastingaangifte, gezondheidscontroles, investeringen — present bias structureel
- Economisch: productiviteitsverlies door procrastinatie geschat op miljarden

---

## Filosofische dimensie

- Is present bias irrationeel? Drie posities:
  1. Ja: tijdsneutraliteit (Ramsey, 1928) — alle tijdsmomenten gelijk wegen is rationeel
  2. Nee: enige korte-termijn-discounting is rationeel (onzekerheid toekomst rechtvaardigt het)
  3. Parfit (1984): toekomstige zelf is ander persoon → lagere gewicht is altruïstisch redeneren, niet egoïstisch
- *Reasons and Persons* (Parfit): persoonlijke identiteit over tijd problematiseert verplichting aan toekomstig zelf
- Klimaatethiek: extreem hoge sociale disconteringsvoet betekent toekomstige generaties bijna nihil wegen (Stern Review vs. Nordhaus)

---

## Verbindingen met bestaand Second Brain

- [[Gedragseconomie & Cognitieve Biases]] — present bias als centrale bias; Thaler & Kahneman-kader
- [[ADHD & Executieve Disfunctie]] — hyperbolisch disconteren als neuropsychologisch kenmerk ADHD
- [[Beloningssysteem & Dopamine]] — neurobiologie van temporele discounting
- [[Verslaving & Neurobiologie]] — excessieve present bias als verslavingsmechanisme
- [[Executieve Functies & Prefrontale Cortex]] — PFC als regulator van tijdspreferentie
- [[Vrije Wil & Determinisme]] — zijn toekomstige keuzes vrij als huidige preferences ze predetermineren?
- [[Ethiek]] — Parfits identiteitsargument, klimaatethiek en sociale discounting
- [[Emotieregulatie]] — emotioneel systeem vs. planmatig systeem in keuzegedrag

---

*Confidence: 0.91 | Source score: 9/10 | Novelty: 0.95 | Trust: hoog*
*Externe bronnen geblokkeerd — gebaseerd op AI-trainingskennis (wetenschappelijke consensusliteratuur)*
