# Case 32 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto-to-fiat sale (USDC/USDT → ARS) via Lemon Cash app — alleged non-credit of fiat proceeds
**Amount in dispute:** 64 USDC (≈ ARS 34,336.38 / ARS 24,028.36 net after FX & commission)
**Question:** Did Lemon fail to credit the ARS proceeds of the user's 64 USDC sale executed on 01/08/2023?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección al usuario** — protect consumer from unjust deprivation of funds.
2. **Información** — accurate transactional information.
3. **Transparencia** — clear ledger/movement disclosure.
4. **Buena fe** — both parties must act in good faith; user must not press an unfounded claim.
5. **In dubio pro usuario** — tiebreaker only.
6. **Educación financiera.**
7. **No discriminación.**
- Section B: T&C subordinate to Section A.

## Burden of proof
User must make a plausible prima facie showing the credit was missing. Lemon must show via internal ledgers that the credit posted. Where Lemon produces matched debit/credit records with identical timestamps and the user produces nothing rebutting them, presumption shifts back to user.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of "Venta de Cryptos" 64 USDC on 01/08/2023 01:11hs marked "Completa", referencia USD, monto equivalente ARS 34,336.38 | App screenshot | Not rebutted (genuine) | Medium — proves sale executed and marked complete; does NOT prove ARS credit was missing |
| User | Same screen shows visible adjacent entries: "Depósito de USDC +9 USDC" and "Retiro de ARS -3.500 ARS" same day | App screenshot | Not rebutted | High against user — demonstrates ARS account was active and being debited that day |
| Lemon | Back-office CRYPTO_SALE record "Aprobada", Trx 01/08/2023 09:30:50, − 64 USDC / + ARS 24,028.36 (paired debit+credit, same Trx ID) | Back-office screenshot | Not rebutted | High |
| Lemon | CVU statement showing CREDIT ARS 34,164.70 at 01/08/2023 01:11:00, Trx ID matching the user's sale ID (14bcc44b…23a1 ≈ 16bc4bbf…23a1 in user screenshot) | Account statement | Not rebutted | High |
| Lemon | CVU ledger showing user immediately spending the credit: ARS 1,000, 760, 3,500 (matches user's own "Retiro -3,500 ARS"), 20,957, etc., within minutes of the credit | Account statement | Not rebutted | High — user dissipated the very funds he says he never received |
| Lemon | Wallet statement showing the 64 USDC sale at 01:11 plus other sales/purchases throughout the day (DOGE, DAI, BNB) | Account statement | Not rebutted | Medium-high — shows active, complex usage |
| Lemon | Observation that claim was filed 10 months after the operation despite daily Lemon usage | Argument | Not rebutted | Low-medium |

Immaterial:
- Discrepancy between "USDT" (user's wording) and "USDC" (records): same operation; nominal error.
- Small spelling/ID typos in transcribed screenshots — IDs substantively align.

## Application
- **Protección:** No deprivation shown. Credit posted at 01:11 and was actively spent by user within 10 minutes.
- **Información:** App displayed sale "Completa" with monto equivalente — accurate.
- **Transparencia:** Lemon disclosed CVU + wallet ledgers with matching IDs and timestamps. User had access to same "Movimientos" view he screenshotted — the credit entry is in his own account history.
- **Buena fe:** User's claim is undermined by his own screenshot, which shows the ARS account in normal debit activity (−3,500 ARS retiro) on the same day. Pressing a claim for funds visibly spent risks breaching buena fe.
- **In dubio:** No genuine duda — evidence is one-sided. Tiebreaker not engaged.
- **Educación:** Lemon's hypothesis (user confusion among many same-day operations) is plausible and not disrespectful.
- **No discriminación:** N/A.
- **T&C compatibility:** No T&C conflict with Section A relevant.

## Jurisdiction / Morality / Validity
Valid consumer claim within scope. No grounds to Refuse to Arbitrate.

## Schelling-Point check
A diligent juror reading these files sees a matched debit/credit pair with same timestamp and a CVU statement showing the user spending the proceeds. The focal honest answer is Favor Lemon.

## Bias audit
Pro-consumer instinct would push toward in dubio, but in dubio is a tiebreaker and requires actual doubt. Here the documentary record is concordant and unrebutted. No bias toward Lemon either — finding rests on ledger evidence the user did not contest.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Under Sections A.1 (Protección) and A.2 (Información), the user must have suffered an actual deprivation of funds traceable to Lemon's conduct. Lemon produced (i) a back-office CRYPTO_SALE record showing a paired −64 USDC / +ARS 24,028.36 leg under a single transaction ID on 01/08/2023, (ii) a CVU statement showing a CREDIT of ARS 34,164.70 at 01:11 on 01/08/2023 with a transaction ID matching the user's own screenshot, and (iii) wallet and CVU ledgers showing the user immediately spending those ARS funds in a series of debits within minutes (−1,000, −760, −3,500, −20,957) and continuing active sales/purchases throughout the day. The user's own screenshot corroborates one of those debits (−3,500 ARS "Retiro") on the same date.

Applying Transparencia (A.3) and Buena fe (A.4): Lemon disclosed a complete, internally consistent ledger that the user has not rebutted, and the user's own evidence shows the ARS account was actively used the same day the credit allegedly never arrived. There is no duda to engage In dubio (A.5) — the documentary record points one way. The 10-month delay before complaining further weighs against the reliability of recollection, though the case is decided on the ledger evidence regardless.

Vote: Favor Lemon, high confidence.
