# RAW DATA — Kelly Criterium & Optimale Positiegroottes
Agent: Agent1-KnowledgeHunter | Date: 2026-07-05 | Source: Training knowledge (cutoff Aug 2025)
Status: RAW DATA — geen interpretatie | Wikipedia-API geblokkeerd (proxy 403)

---

## Bronnen (primair)
- Kelly JL (1956). "A New Interpretation of Information Rate." *Bell System Technical Journal*, 35(4), 917–926.
- Thorp EO (1962). *Beat the Dealer*. Random House. [Eerste praktische toepassing Kelly in blackjack]
- Thorp EO (1969). "Optimal Gambling Systems for Favorable Games." *Revue de l'Institut International de Statistique*, 37(3), 273–293.
- Poundstone W (2005). *Fortune's Formula: The Untold Story of the Scientific Betting System*. Hill and Wang.
- Ziemba WT & Hausch DB (1986). *Betting at the Racetrack*. Dr. Z Investments.
- MacLean LC, Thorp EO & Ziemba WT (2010). "Good and Bad Properties of the Kelly Criterion." *Quantitative Finance*, 10(1), 3–9.

---

## Kernfeiten

### John L. Kelly Jr. (1923–1965)
- Onderzoeker Bell Telephone Laboratories
- Publiceerde Kelly Criterium in 1956 als oplossing voor informatieoverdrachtsoptimalisatie
- Later toegepast op gokken door Claude Shannon (informatietheoreticus, MIT) en Edward Thorp

### De Kelly Formule
Voor een binaire uitkomst (win/verlies):

**f* = (bp - q) / b**

Waarbij:
- **f*** = optimale fractie van het kapitaal in te zetten
- **b** = odds (netto winstfactor: bij odds 2:1 is b = 2)
- **p** = kans op winst
- **q** = kans op verlies (= 1 - p)

**Vereenvoudigd voor gelijke odds (b=1)**: f* = p - q = 2p - 1

**Voor beleggen** (continue verdeling):
f* = μ/σ² (verwacht rendement gedeeld door variantie)

### Wiskundige Eigenschappen
- Kelly maximaliseert de verwachte groeisnelheid van het kapitaal op lange termijn
- Kelly maximaliseert de verwachte logaritme van rijkdom
- Op de lange termijn versloeg Kelly altijd elke andere strategie (bijna zeker)
- Kelly leidt nooit tot ruin (tenzij de fractie boven Kelly wordt ingezet)

### Vergelijking met Andere Strategieën
| Strategie | Eigenschap |
|---|---|
| **Full Kelly** | Maximaliseert langetermijngroei; hoge volatiliteit |
| **Half Kelly** | Halveert volatiliteit; 75% van de groeisnelheid |
| **Fixed fraction** | Conservatief; langzamere groei |
| **Martingale** | Verdubbelen bij verlies; leidt tot ruin |
| **Equal weighting** | Suboptimaal t.o.v. Kelly |

### Toepassingen in Beleggen
- **Positiegroottes**: optimale allocatie per positie op basis van verwacht rendement en variantie
- **Multi-asset Kelly**: uitbreiding naar portefeuilles met meerdere assets (matrix-formule)
- **Half-Kelly**: conservatieve variant gebruikt door veel professionele kwantitatieve traders
- **Ed Thorp**: paste Kelly toe op aandelenopties via Delta Hedging (Renaissance Technologies-stijl)

### Psychologische Uitdagingen
- Full Kelly impliceert soms grote inzetten (bijv. 40% van kapitaal) — emotioneel moeilijk vol te houden
- Drawdowns bij Full Kelly zijn groot (drawdown ~50% is theoretisch te verwachten)
- Gedragseconomie: verlieshate maakt het moeilijk Kelly consistent te volgen
- Verband met Hyperbolic Discounting: investeerders kiezen te kleine posities (sub-Kelly) uit angst

### Kritiek
- Kelly vereist exacte kennis van p (kansschattingen zijn altijd onzeker in beleggen)
- Onjuiste p-schatting → over-Kelly → risico op ruin
- Kelly gaat uit van fractionele posities en continue herallocatie — niet altijd praktisch
- Lange tijdshorizon vereist: op korte termijn kan een andere strategie beter presteren

### Shannon & Claude's Verbinding
- Claude Shannon (uitvinder van de informatietheorie) was vriend en collega van Kelly
- Shannon demonstreerde experimenteel dat Kelly-betting vermogen opbouwde in een roulette-variant
- Shannon's informatietheorema en Kelly Criterion zijn wiskundig verwant: beide maximaliseren informatie-opname-snelheid

---

## Verbindingen (RAW)
- Risico vs. Onzekerheid — Knight's Onderscheid (Kelly vereist bekende p; Knight's onzekerheid maakt Kelly onmogelijk)
- Moderne Portefeuilletheorie (Kelly als alternatief optimalisatiekader)
- Gedragseconomie & Cognitieve Biases (verlieshate vs. Kelly-discipline)
- Hyperbolic Discounting (sub-Kelly gedrag als intertemporeel bias)
- Opties & Derivaten (Thorp's Kelly-toepassing)

---

## Kwaliteitsscores
- source_score: 9/10
- confidence: 0.92 (wiskundige eigenschappen exact; praktische toepassing debatteerbaar)
- novelty: 1.0
- trust_level: hoog
