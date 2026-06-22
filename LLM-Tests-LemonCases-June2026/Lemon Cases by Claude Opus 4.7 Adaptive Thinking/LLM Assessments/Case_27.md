# Case 27 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Tarjeta Prepaga Lemon — disputed card transaction ("Inmobiliario ABL", Buenos Aires city property tax)
**Amount in dispute:** 7.172,07 ARS
**Question:** Must Lemon reimburse a card charge the user claims he never authorised, where the user resides in another province and Lemon offers no positive evidence the user authorised the transaction?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Section A.1 Protección — Lemon must protect users against losses arising from system/fraud risk it is best placed to manage.
2. A.2 Información and A.3 Transparencia — duties on Lemon to clearly inform users of how disputed/fraud claims will be handled.
3. A.4 Buena fe — both parties must act in good faith; bare denial without corroboration is weak.
4. A.5 In dubio pro consumidor — tiebreaker if evidence is in equipoise.
5. Section B — T&Cs cannot override Section A. T&C clauses 5.1/5.2 govern non-fraudulent merchant disputes; they expressly carve out fraudulent transactions ("transacciones NO fraudulentas").
6. Burden allocation: user must give a coherent, plausible account of the fraud (consumer-friendly threshold); Lemon must show some objective indicator of authorisation to defeat a fraud claim once a coherent denial is given.

## Burden of proof
User bears initial burden of articulating a plausible non-authorisation; Lemon, as system operator with access to device, IP, 3DS / OTP and geolocation logs, must produce objective indicators of authorisation to rebut. Unrebutted documentary evidence is presumed genuine.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of Lemon "Movimientos" showing "Inmobiliario Abl - 7.172,07 ARS" on 08 March | Screenshot | No | High (establishes the charge) |
| User | Tuya/Nuevo Banco del Chaco credit-card statement in user's name at Resistencia, Chaco address | Document | No | Medium (corroborates residence outside CABA) |
| User | Narrative: card still in possession; prior failed "patente" attempt suggests data compromise | Statement | Not directly rebutted | Medium |
| Lemon | Internal ledger table showing deposit day before, the LEMON_CARD_PAYMENT of -7.172,07 ARS at 19:03:16, cashback at 19:03:17, then VIRTUAL_WITHDRAWAL of -30.828,00 ARS at 19:15:54 | Internal log | Partly: timing is consistent with either authorised or unauthorised use | Medium |
| Lemon | T&C clauses 5.1 and 5.2 | Contractual | N/A | Low — clauses expressly exclude fraudulent transactions |

Immaterial:
- KLEROS logos / Lemon logo banners.
- Generic Tuya statement transaction lines (only the address/identity field is probative).

## Application
- **Protección:** Lemon is the issuer of the prepaid card and the operator best placed to access device/IP/3DS/geolocation/merchant token data. It produced no such evidence — only a generic timing table that is at best neutral.
- **Información:** Lemon's only positional disclosure is the T&C carve-out, which actually points users back to the merchant for *non-fraudulent* disputes — by Lemon's own contract, fraud claims fall outside 5.1/5.2.
- **Transparencia:** Lemon does not disclose any internal anti-fraud verification step nor explain why it concluded the transaction was authentic. The "as presented" offer (a card with system-level protection against unauthorised use) is undermined by silence.
- **Buena fe:** User's account is internally consistent — he is in Chaco, the charge is a CABA municipal tax, he flags an earlier failed fraudulent attempt. Lemon's "timing" argument (deposit then withdrawal) is circumstantial: a victim who notices funds being drained typically withdraws what remains to stop further loss; the timing is at least as consistent with the user reacting to the fraud as with self-dealing.
- **In dubio:** Even if the picture were genuinely balanced, tiebreaker favours the consumer. Here the picture leans pro-user, so the tiebreaker is reinforcing rather than determinative.
- **Educación:** Not centrally engaged.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Lemon invokes 5.1/5.2 but these clauses, on their face, exclude fraudulent transactions and so cannot be the operative rule here. Section B bars using a contractual catch-all to evade Section A duties.

## Jurisdiction / Morality / Validity
Within scope: consumer-protection dispute about a transaction on a Lemon-issued card. No morality or validity concerns.

## Schelling-Point check
A diligent juror reading both filings sees: (i) a coherent, document-supported denial by a Chaco resident of a Buenos Aires municipal-tax charge; (ii) a Lemon submission that produces no positive proof of authentication, leaning entirely on a T&C clause that by its own wording does not cover fraud. The convergent answer is to favour the user.

## Bias audit
I have weighed Lemon's strongest point — the same-day deposit and post-charge withdrawal — and find it neutral rather than incriminating. I have not penalised Lemon for evidentiary absences it could not control, only for absences within its exclusive control (3DS/OTP/IP/device logs). No identity-based assumptions.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

The user gives a coherent, document-supported account that the 7.172,07 ARS "Inmobiliario ABL" charge of 08 March 2024 was not authorised by him: he is a resident of Resistencia, Chaco (corroborated by a third-party bank statement), the charge is a Buenos Aires city municipal property tax, and he reports a prior failed unauthorised use of his card. The card itself remains in his possession, which is consistent with data compromise rather than physical theft. Under Política Section A.1 (Protección) and A.3 (Transparencia), the offer "as presented" of a regulated prepaid card carries an expectation that the issuer either prevents unauthorised use or, when challenged, produces objective indicators of authentication.

Lemon's submission produces no such indicators. The transaction-ledger table shows only the charge, a small cashback, and a subsequent withdrawal — nothing about device fingerprint, IP, 3DS/OTP verification, or merchant-token data, all of which are within Lemon's exclusive control. The timing argument cuts both ways: a user who has just discovered an unrecognised debit would rationally withdraw remaining funds to stop further loss. Lemon's reliance on T&C 5.1/5.2 is misplaced because those clauses, by their own terms, govern *non-fraudulent* merchant disputes ("transacciones NO fraudulentas"); they cannot, under Política Section B, displace Section A in a fraud claim.

Applying A.1 Protección and A.4 Buena fe, with A.5 in dubio as a reinforcing tiebreaker, the case resolves in the user's favour. Lemon should refund 7.172,07 ARS.
