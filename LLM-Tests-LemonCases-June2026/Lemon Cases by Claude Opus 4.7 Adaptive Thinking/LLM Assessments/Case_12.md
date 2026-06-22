# Case 12 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash prepaid card — disputed/unauthorized transactions following alleged card loss
**Amount in dispute:** ARS 40,000 (three transactions at MERPAGO*TICKETPASS on 13/10/2023)
**Question:** Must Lemon reimburse the user ARS 40,000 for transactions the user labels fraudulent after losing the card?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política de Interpretación de Disputas, Section A — seven principles (Protección, Información, Transparencia, Buena fe, In dubio pro consumidor, Educación, No discriminación).
2. Section B — T&C compatibility check (not central here; no specific T&C clause cited).
3. Burden allocation: user must offer a credible factual basis that the claimed transactions were unauthorized; Lemon's back-office records, if unrebutted, are presumed genuine.
4. Buena fe applies to BOTH parties — a consumer alleging fraud must act consistently with that allegation.

## Burden of proof
User must establish a plausible case of unauthorized use; Lemon's documentary records rebut that case if they show conduct inconsistent with the fraud narrative.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of "last legitimate transaction" (small ARS amounts at MERPAGO*TICKETPASS on 13/10/2023 ~05:10–06:41) | App screenshot | Partially — same merchant as disputed txns | Low |
| User | Narrative: lost card, dead phone, face ID failed, emailed Lemon, made police report | Self-report | Police report not attached to file | Low–Medium |
| Lemon | Back-office table: 14 transactions at MERPAGO*TICKETPASS for owner_id 1,025,399 spanning 24/06/2023 → 28/10/2023 | Internal record | Not rebutted by user | High |
| Lemon | One transaction at MERPAGO*TICKETPASS on **28/10/2023** — AFTER the alleged fraud / card-loss report | Internal record | Not rebutted | High |
| Lemon | 10 prior transactions at the same merchant before 13/10/2023 (June, July, September) | Internal record | Not rebutted | High |

Immaterial:
- User's complaint about delayed email response from Lemon — does not change whether the underlying transactions were authorized.
- Face-ID/dead-phone narrative — relevant to mitigation, not to authorship of the disputed charges.

## Application
- **Protección:** Consumer protection covers genuine unauthorized use, not chargeback opportunism. Lemon's evidence severely undermines the unauthorized-use claim.
- **Información:** No information defect by Lemon is identified; no misleading promo is at issue.
- **Transparencia:** No misleading advertising at issue.
- **Buena fe:** Cuts AGAINST the user. A user who genuinely lost their card and considers transactions at a specific merchant fraudulent would not continue transacting with that same merchant 15 days later (28/10/2023). The 10 prior transactions with the identical merchant also undercut the "stranger used my card" theory — the disputed merchant is a habitual one for this account.
- **In dubio:** Not invoked. The evidentiary picture is one-sided in Lemon's favour; there is no genuine tie to break.
- **Educación / No discriminación:** N/A.
- **T&C compatibility:** Not engaged — Lemon does not rely on a T&C carve-out; it relies on factual records.

## Jurisdiction / Morality / Validity
Case is properly within the Blockchain No Técnica subcourt. No morality/validity reason to RtA.

## Schelling-Point check
A diligent juror reading both files focuses on one decisive fact: the user transacted at the very same merchant **after** filing the fraud claim, and has a months-long history with that merchant. The Schelling answer is Favor Lemon.

## Bias audit
The pro-consumer tilt of Section A is real but conditional on a credible consumer claim. Awarding here would reward apparent chargeback abuse and harm the protection regime's credibility. No anti-user bias is operating; the evidence simply doesn't support the user.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Under Section A of the Política, consumer protection (Principle 1) and good faith (Principle 4) apply to both sides of the dispute. The user alleges that ARS 40,000 in transactions at MERPAGO*TICKETPASS on 13/10/2023 were the product of fraudulent use of a lost card. However, Lemon's unrebutted back-office record shows the same account transacted with the identical merchant on ten prior occasions across June, July and September 2023, and — most decisively — once more on 28/10/2023, fifteen days **after** the alleged loss and fraud report. A genuinely defrauded user who had cancelled the card would not be transacting at the same merchant two weeks later.

The user's own evidence (screenshots of small "last legitimate" payments at MERPAGO*TICKETPASS minutes before the disputed charges) is consistent with a continuous personal usage pattern at that merchant, not with a third-party intruder. The dead-phone / face-ID narrative speaks only to mitigation timing and does not address authorship of the disputed charges.

Principles 2 (Información) and 3 (Transparencia) are not engaged — no misleading offer or information defect by Lemon is alleged. Principle 5 (in dubio pro consumidor) is a tiebreaker and is not reached because the evidentiary record is not in equipoise; it weighs clearly against the fraud allegation. Applying Principles 1 and 4 to the unrebutted record, the claim fails. Vote: Favor Lemon.
