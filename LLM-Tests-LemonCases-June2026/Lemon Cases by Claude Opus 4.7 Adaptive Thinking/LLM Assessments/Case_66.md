# Case 66 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** "Pago de Servicios" — bill payment to Camuzzi Gas Pampeana / Gas del Sur for ARS 19,479.89, executed via Lemon app on 13 Oct 2024 21:43, debited in BTC (0.00027375 BTC).
**Amount in dispute:** Value of BTC 0.00027375 (~ARS 19,577.78 including a BTC 0.00000137 / ARS 97.89 fee) that the user wants reversed/refunded.
**Question:** Did Lemon wrongfully debit the user in BTC instead of ARS for a service payment, in a way that violates Política Sección A and entitles the user to a reversal?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Sección A.1 — Protección al consumidor:** safeguards consumer economic interests; engages where there is genuine asymmetry, hidden term, or platform-side fault.
2. **Política Sección A.2 — Información:** the offer/flow as presented to the consumer governs; here the in-app currency picker is what was presented.
3. **Política Sección A.3 — Transparencia:** terms and choices must be clearly displayed and not hidden.
4. **Política Sección A.4 — Buena fe:** parties must act honestly.
5. **Política Sección A.5 — In dubio pro consumidor:** tiebreaker only.
6. **Política Sección B — T&C compatibility:** T&Cs apply insofar as they do not override Section A. Lemon cites T&C 3.3 (transactions are irreversible once executed) — admissible only if Section A is satisfied.
7. **Guidance — Offer-as-presented doctrine:** if the currency picker visibly required the user to pick a currency and clearly displayed the chosen currency before confirmation, the user's selection binds them; if the flow hid the currency or auto-routed without disclosure, A.2/A.3 would be violated.

## Burden of proof
The user, seeking reversal of an executed and irreversible on-platform transaction, bears the burden of showing that the platform either (a) failed to present the currency choice clearly, (b) auto-debited a currency contrary to a clearly-made user instruction, or (c) materially misled the user. The default state — that an executed and confirmed in-app payment stands — favors Lemon absent affirmative evidence of platform fault.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon "Movimientos" detail screenshot of the 13/10/2024 21:43 Camuzzi payment showing ARS 19,479.89 nominal, BTC 0.00027375 total debited, BTC 0.00000137 commission, BTC/ARS rate 71,515,842.11, "Estado: Aprobado" | Primary (Lemon system record) | No | High — confirms the payment was executed and debited in BTC |
| User | Rapipago-style receipt for the same operation (Cód. Op. f0308d4e…, Identificador 8441b321…, "Pagado con Lemon") | Primary | No | Medium — confirms the bill was paid successfully to the merchant; user got the service for which they paid |
| User | Narrative assertion that they intended to pay in ARS, had ARS balance, and that USDC (their "moneda de respaldo") had no balance | Secondary (party assertion) | Implicitly rebutted by Lemon's picker evidence; no screenshot of the alleged ARS balance at the moment of payment is produced | Low |
| Lemon | Screenshot of the in-app "Seleccionar moneda" picker showing all available currencies (USDC, BTC, ARS, ETH, USDT, DAI) with per-currency balances and a clear ✓ on the active selection; labelled as a representative capture of the Lemon app | Primary (UX flow as presented) | Not rebutted | High — establishes that currency selection is an affirmative, visible step before payment confirmation |
| Lemon | T&C 3.3 cited verbatim: once an Instruction is executed via the platform, the transaction is irreversible and cannot be cancelled | Primary (contract) | Not rebutted as text | High on contract effect; weight tempered by Sección B (T&Cs cannot override Section A) |

Immaterial:
- Whether the user's "moneda de respaldo" was USDC: backup currency only triggers when the chosen payment currency is insufficient; here the chosen currency (BTC) had sufficient balance, so the backup mechanism was not engaged.
- User's suspicion that being told "no reintegros" is sospechoso: the irreversibility is a stated T&C clause and a normal feature of executed payment instructions, not evidence of bad faith on its own.

## Application
- **Protección (A.1):** Engaged in principle (consumer paid in an unintended currency), but engagement does not automatically mean violation. The picker evidence shows the user had the means to choose, and the user did not rebut that the picker functions as shown.
- **Información (A.2):** The flow "as presented" includes an explicit currency-selection step listing each currency, its balance, and the chosen one. No evidence the picker was hidden, mistranslated, or defaulted silently to BTC. A.2 is satisfied by Lemon.
- **Transparencia (A.3):** The picker shows balances per currency, marks insufficient balances, and requires an affirmative selection before payment. Transparent. A.3 is satisfied by Lemon.
- **Buena fe (A.4):** No evidence of bad faith — the bill was paid in full to the merchant, the receipt and ledger entry are produced, and the irreversibility of executed payments is disclosed in the T&Cs and is consistent with the underlying service-payment rail (Rapipago-style). A.4 is satisfied.
- **In dubio pro consumidor (A.5):** Tiebreaker only. Engaged only if the analysis ends in genuine equipoise. Here it does not — the user produced no screenshot of the actual selection step, no error message, no support-chat confirmation of platform malfunction, and no contemporaneous proof of an ARS balance sufficient to cover the ARS 19,479.89 bill. The case is not in equipoise; A.5 does not flip it.
- **Educación (A.6):** Not in dispute.
- **No discriminación (A.7):** Not in dispute.
- **T&C compatibility (Section B):** T&C 3.3 (irreversibility of executed Instructions) does not override Section A here because Section A is independently satisfied: the user was informed and had a transparent choice. T&C 3.3 then governs the consequence — the executed payment stands.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Argentine consumer / blockchain non-technical). No morality issue. Question is well-formed; the record (two primary system documents from Lemon plus the user's own ledger screenshots) is sufficient to decide.

## Schelling-Point check
A diligent panel reading the same record sees: (i) a payment executed and confirmed; (ii) a documented currency picker requiring an affirmative selection; (iii) no rebuttal of the picker's accuracy; (iv) no documentary support for the user's claim that ARS could have covered the bill; (v) an irreversibility T&C consistent with executed bill-payment rails. The literal, obvious reading is that the user selected — or at minimum confirmed — BTC, and the platform performed as instructed. Convergence is on Favor Lemon.

## Bias audit
No reliance on party identity, wealth, or polish. The user's narrative is sympathetic (most users would prefer ARS over BTC for a peso-denominated utility bill) but sympathy is not material evidence. The finding rests on (a) Lemon's unrebutted picker screenshot and (b) the absence of any user-side documentation that the selection step malfunctioned or that an ARS balance sufficient to cover the bill existed at 21:43 on 13/10/2024.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
Under Política Sección A.2 (Información) and A.3 (Transparencia), the in-app flow "as presented" governs. Lemon's unrebutted screenshot of the "Seleccionar moneda" picker shows that currency selection is an affirmative, clearly displayed step, listing each currency with its balance and marking insufficient ones — there is no hidden term, no silent default, and no evidence the picker malfunctioned on 13 October 2024 21:43. The user produced the platform's own ledger detail and the Rapipago-style receipt, both of which confirm that the bill was paid in full to Camuzzi and that the debit was in BTC; neither rebuts the picker evidence nor documents an ARS balance sufficient to cover the ARS 19,479.89 invoice at the time of payment.

Sección A.1 (Protección) is engaged in principle but is not violated where the consumer had a transparent, presented choice. Sección A.4 (Buena fe) is satisfied: the merchant was paid, the ledger is produced, and the irreversibility of executed payment Instructions (T&C 3.3) is disclosed and consistent with bill-payment rails — irreversibility is the property of the payment, not a catch-all immunity, and is therefore compatible with Sección A under Sección B.

Sección A.5 (In dubio pro consumidor) is a tiebreaker and is not engaged here because the case is not in equipoise: the user, as the party seeking to reverse an executed and confirmed on-platform payment, has not carried the burden of showing platform-side fault. Vote: Favor Lemon.

Case 66 | VOTE: Favor Lemon | CONFIDENCE: medium | Picker screenshot unrebutted shows affirmative currency selection; user produced no proof of ARS balance sufficient for the bill or of a UX malfunction; executed payment stands.
