# Case 23 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** BTC sale on Lemon Cash app — alleged interface error in price display and sale amount.
**Amount in dispute:** Approx. ARS 4,237 (difference between user's expected ARS 127,604.13 and quoted ARS 123,367.08 for 0.00227025 BTC).
**Question:** Did Lemon violate Section A duties (Información / Transparencia) by displaying a "reference price" of BTC that the user could not multiply by his balance to arrive at the actual sale proceeds, or is the bid/ask spread plus 0.5% commission adequately disclosed?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Section A.1 Protección — protect the financial user.
2. Política Section A.2 Información — adequate information about product features.
3. Política Section A.3 Transparencia — offer "as presented" governs; hidden limits = violation.
4. Política Section A.4 Buena fe — both sides act in good faith.
5. Política Section A.5 In dubio pro consumidor — tiebreaker only.
6. Política Section A.6 Educación financiera.
7. Section B — T&Cs cannot override Section A.

## Burden of proof
User must show, on preponderance, that Lemon's interface concealed a material limit or misrepresented the price at which BTC would be sold. Lemon must rebut by showing pre-trade disclosure of the actual sale figures, the exchange rate used, and the commission.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot: BTC asset screen showing 0.00227025 BTC ≈ 123,996.40 ARS, with "56.207.085,00 ARS" reference price | Screenshot | Not rebutted (Lemon submits same screen) | High — shows balance ARS equivalent already uses sell-side rate (123,996.40), not buy-side (~127,604) |
| User | Screenshot: "Quiero cambiar Bitcoin" screen showing sell quote 123,367.08 ARS for full balance | Screenshot | Not rebutted | High — pre-confirmation quote shown to user |
| User | Support chat with "Fran" explaining buy-side vs sell-side spread | Chat screenshot | Not rebutted | Medium — confirms user was educated about the spread |
| Lemon | Same two screenshots reproduced | Screenshot | — | High |
| Lemon | "Confirmá tu intercambio" confirmation screen showing exchange rate, 0.50% commission (3,500 ARS), and "Recibirás aproximadamente" amount | Screenshot | Not rebutted | High — proves explicit pre-trade disclosure of rate, fee, and net receivable |
| Lemon | Arithmetic reconciliation: 123,996.40 × (1 − 0.005) ≈ 123,376.42 ≈ 123,367.08 (rounding/timing) | Calculation | Plausible | High — explains the gap entirely |

Immaterial:
- User's prior-day purchase narrative (separate transaction, not the one screenshotted).

## Application
- **Protección:** No economic loss occurred. The user received exactly what the pre-trade quote and confirmation screen promised. No exploitative or unsafe conduct shown.
- **Información:** Lemon discloses (a) the sell-side equivalent on the BTC asset screen (123,996.40 ARS — not the "reference price" multiplied by holdings), (b) the sale quote on the exchange screen, and (c) the exchange rate plus 0.50% commission (with the peso amount of the fee) on the confirmation screen. Information is adequate.
- **Transparencia:** The headline "56.207.085,00 ARS" reference figure is, on its face, ambiguous as to whether it is buy-side or sell-side. However, the app does NOT invite the user to multiply that number by his balance — instead it shows the actual ARS equivalent (123,996.40) directly beneath the BTC balance, and shows the actual sale proceeds on the next screen. Bid/ask spreads are universal market practice; the disclosure is sufficient under an "offer as presented" reading because the offer to sell is the 123,367.08 quote, not a derived calculation from the reference price.
- **Buena fe:** Lemon's support agent ("Fran") explained the bid/ask spread to the user proactively. No evasion.
- **In dubio:** Not invoked — facts are not in equipoise; the math reconciles cleanly to within rounding.
- **Educación:** Support chat itself constitutes financial education. The user acknowledged understanding ("sisi entiendo eso").
- **No discriminación:** Not at issue.
- **T&C compatibility:** Not invoked; standard exchange terms are consistent with Section A.

## Jurisdiction / Morality / Validity
Within Kleros consumer-protection scope. No morality or validity issues.

## Schelling-Point check
A diligent juror reviewing identical evidence from both sides would conclude: the disputed ARS gap is the documented 0.5% commission plus the bid/ask spread baked into the app's already-displayed sell-side equivalent. Pre-trade confirmation screen discloses rate and fee in pesos. The convergent answer is Favor Lemon.

## Bias audit
Resisting reflexive pro-consumer pull: the user's reasoning is mathematically wrong (he applied buy-side price to a sell-side action). There is mild transparency friction — labelling the headline price as "reference" without explicit "buy-side" tagging could mislead — but it does not rise to a Section A violation given the downstream disclosures. No anti-user bias; user genuinely confused but not deceived.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

The user's claim rests on multiplying the displayed "reference price" (56,207,085 ARS/BTC) by his balance and comparing the product to the sale quote. That calculation is not what Lemon's interface invited him to do. Immediately beneath the BTC balance, the app shows the actual ARS equivalent (123,996.40) already at the sell-side rate, and the exchange screen shows the sale quote (123,367.08) which equals 123,996.40 minus the 0.50% commission. The confirmation screen explicitly itemises the exchange rate and the commission in pesos. Información and Transparencia are satisfied because the offer "as presented" — i.e., what the user is actually asked to accept — is the sale quote, not a back-of-envelope derivation from the headline reference price.

Buena fe and Educación are also satisfied: Lemon's support agent proactively explained the standard bid/ask spread, and the user acknowledged he understood. Bid/ask spreads plus a disclosed commission are universal market practice; absent an actual hidden limit or misrepresentation, this is not a Section A violation.

In dubio pro consumidor is not triggered because the evidence is not in equipoise — the arithmetic reconciles cleanly and Lemon's pre-trade disclosure is documented in the very screenshots the user submitted. Vote: Favor Lemon, medium confidence (the headline "reference price" labelling is a minor transparency friction worth flagging, but does not flip the result).
