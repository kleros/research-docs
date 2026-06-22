# Case 48 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Spot market ETH purchase via Lemon app (no promo invoked).
**Amount in dispute:** ~ARS 20,000 (claimed loss; user's balance moved from ARS 427,000 to ARS 407,170.32).
**Question:** Did Lemon improperly debit ~ARS 20,000 from the user's account in connection with an ETH purchase on 17 July 2024, or is the balance change a normal consequence of market/FX movement?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Información (A.2)** — user must receive clear info about the operation and how balances are displayed.
2. **Transparencia (A.3)** — no hidden fees or unexplained debits.
3. **Buena fe (A.4)** — Lemon must execute the order on the terms offered and explain abnormalities.
4. **Educación (A.6)** — user must be informed about how ARS-denominated crypto balances behave under FX volatility.
5. **In dubio pro usuario (A.5)** — applies only as tiebreaker.
6. **Offer-as-presented governs Información/Transparencia; clear product + user error → claim fails; catch-all immunity ≠ override of Section A.**

## Burden of proof
The user bears the initial burden to evidence that the ~ARS 20,000 movement is an unauthorised debit. If a plausible non-debit explanation appears (market/FX), the user must rebut it. Lemon bears the burden to evidence the actual transaction terms and that no hidden fee was charged.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of "Mercado crypto" showing ETH at USD 3,353.13 / ARS 4,811,745.68 | Screenshot | No | Low — establishes market quote at one moment, does not show a debit. |
| User | "Movimientos" screenshot: −ARS 26,905.12 / +0.00553492 ETH on 15 July | Screenshot | Partially — Lemon's back-office shows ARS 28,805.12 / 0.00553402 ETH on 17/7/2024 | Medium — confirms an ETH buy occurred; numbers don't fully match Lemon's record but order of magnitude consistent. |
| User | "Balance total" screenshot ARS 407,170.32 | Screenshot | No | Low — single snapshot, no prior balance shown for comparison. |
| User | Narrative claiming balance dropped from 427k to 407k = ARS 20k loss | Assertion | Yes — Lemon explains via FX/peso volatility | Low — no documentary proof of the 427k starting balance or of any extra debit beyond the ETH purchase. |
| Lemon | CRYPTO_PURCHASE back-office record: −ARS 28,805.12 / +0.00553402 ETH, SPOT MARKET, 17/7/2024 11:57:55 | Back-office record | No | High — authoritative transaction record; shows price/qty/timestamp. |
| Lemon | Link to public Lemon tweet (x.com/lemonapp_ar/status/1786757411726962560) explaining ARS-denominated crypto balance fluctuates with USD/ARS rate | Public communication | No | Medium — provides plausible, publicly-documented explanation for apparent balance drop. |

Immaterial:
- KLEROS letterhead/logos.
- Generic Mercado crypto price list (does not evidence the disputed debit).

## Application
- **Protección (A.1):** No evidence of any debit beyond the SPOT ETH purchase the user himself initiated. The "loss" appears to be an unrealised valuation change on the ARS-denominated crypto portfolio, not a deduction by Lemon.
- **Información (A.2):** Transaction confirmation in-app and back-office shows price, quantity, type (SPOT MARKET) — adequate information was provided about the operation itself.
- **Transparencia (A.3):** Lemon's record (28,805.12 ARS for 0.00553402 ETH) is consistent with a market-rate purchase; no hidden fee is identified. The ~ARS 1,900 difference between the user's screenshot (−26,905.12) and Lemon's record (−28,805.12) is unexplained but the user does not raise this point, and either figure alone does not produce a ~ARS 20,000 shortfall.
- **Buena fe (A.4):** Lemon offers a coherent explanation (peso/USD volatility affecting ARS display of crypto balances) and links to a public, contemporaneous educational post. No bad-faith conduct evidenced.
- **In dubio (A.5):** Tiebreaker only — does not apply where the user has failed to produce evidence of any improper debit beyond a mismatch between his subjective expectation and how ARS-denominated crypto balances actually behave.
- **Educación (A.6):** Lemon points to a published explainer of exactly this phenomenon. While the user's confusion is understandable, the educational duty appears reasonably met via public communications, and there is no allegation Lemon concealed how balances are displayed.
- **No discriminación (A.7):** Not at issue.
- **T&C compatibility (Section B):** No T&C clause invoked or in conflict with Section A.

## Jurisdiction / Morality / Validity
Within Kleros "Blockchain No Técnica" consumer-protection scope. No morality or validity defects. Not an RtA case.

## Schelling-Point check
A diligent juror reading both filings will likely conclude the user has misinterpreted ARS-denominated crypto balance fluctuation (driven by USD/ARS exchange-rate movement) as a hidden debit by Lemon. The transaction record matches a normal market-rate ETH buy. The Schelling point is Favor Lemon.

## Bias audit
No populist tilt to the user is warranted where the underlying complaint rests on a misunderstanding of FX dynamics rather than any documented misconduct. No anti-user bias either — the analysis would shift if the user had produced before/after balance evidence showing a debit that could not be explained by FX or by the ETH purchase itself. He did not.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

The user alleges a ~ARS 20,000 unexplained "descuento" after an ETH purchase, but the documentary record does not support an unauthorised debit. Lemon's back-office shows a single CRYPTO_PURCHASE on 17/7/2024 for ARS 28,805.12 / 0.00553402 ETH at market price. The user's own screenshots confirm an ETH buy of comparable magnitude. No second debit, no hidden fee, and no T&C clause are identified. The apparent drop from ARS 427,000 to ARS 407,170 is consistent with the ARS-denominated valuation of a crypto portfolio moving with the USD/ARS exchange rate — a phenomenon Lemon publicly documented in a contemporaneous post.

On Política Section A: Información and Transparencia are satisfied because the operation's price, quantity and type were disclosed in-app and corroborated by the back-office record. Buena fe is satisfied because Lemon offers a coherent, publicly-available explanation rather than stonewalling. Educación is met to a reasonable standard via Lemon's public explainer; the user's confusion, while genuine, does not by itself constitute a violation absent evidence that Lemon misrepresented how balances are displayed. In dubio pro usuario is a tiebreaker and is not engaged here because the evidentiary record is not in equipoise — it points clearly to FX/market movement, not a Lemon-side debit.

Accordingly, the user has not discharged the initial evidential burden and Lemon's account is unrebutted on the material points. Vote: Favor Lemon, medium confidence (held back from "high" only by the small unexplained ARS discrepancy between the user's "Movimientos" screenshot and Lemon's back-office figure, which neither party addresses).
