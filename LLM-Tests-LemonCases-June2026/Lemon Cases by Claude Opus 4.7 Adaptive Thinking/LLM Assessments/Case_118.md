# Case 118 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (physical VISA) — failed/cancelled card purchase
**Amount in dispute:** ARS 9.291
**Question:** Did Lemon wrongfully retain ARS 9.291 from a cancelled card payment to MERPAGO*TOMASSO on 29 October 2025, or was the amount properly refunded?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Protección al Consumidor (A.1):** Lemon must ensure card payments are processed correctly or refunded if they fail.
2. **Información (A.2):** Lemon must provide clear information about transaction status.
3. **Transparencia (A.3):** Status of operations and remedies must be visible/auditable to the user.
4. **Buena fe (A.4):** Both parties must act in good faith; Lemon must remediate failed payments diligently.
5. **In dubio pro consumidor (A.5):** Tiebreaker — only applies if genuine doubt remains after evidence assessment.
6. **Educación / No discriminación (A.6/A.7):** Not engaged.
7. **Section B:** Section A principles prevail over conflicting T&Cs.

## Burden of proof
User must show a debit without corresponding service/refund. Lemon must rebut with evidence of refund or successful settlement.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon app screenshot of Trx 1c0d757c… showing "Cancelado — Hubo un error con el pago. **Los fondos están disponibles en tu billetera**", 9.291 ARS, 29 Oct 2025 11:27 | Primary (in-app record) | No — corroborates Lemon | High |
| Lemon | Internal ops panel (LEMON_CARD_PAYMENT, Rechazada) showing same Trx ID, with Devoluciones row: Estado "Devuelto", Monto 9.291, Motivo "cancellation", Fecha 2025-10-29 15:24:58 | Primary (system of record) | No | High |

Immaterial:
- General appeals to consumer-protection rhetoric without substantiating any unrecovered debit.

## Application
- **Protección (A.1):** Satisfied — the failed payment was reversed automatically the same business day (~4 hours after attempt). No loss of funds.
- **Información (A.2):** Satisfied — the app explicitly stated the transaction was cancelled and the funds were available in the wallet; the user's own screenshot proves this.
- **Transparencia (A.3):** Satisfied — both the user-facing movements screen and Lemon's internal panel show matching transaction ID, status (Cancelado/Rechazada) and refund record.
- **Buena fe (A.4):** Lemon acted diligently with same-day auto-reversal via standard processor flow. No bad faith shown by either side; the user appears to have misread her own evidence.
- **In dubio (A.5):** Not engaged — there is no genuine doubt. Both parties' primary records align: the funds were returned.
- **Educación / No discriminación:** Not engaged.
- **T&C compatibility (Section B):** Not in conflict; no T&C clause is being invoked against the user.

## Jurisdiction / Morality / Validity
Pass — straightforward consumer-protection card-payment dispute in the correct subcourt; no morality concerns; question is well-formed.

## Schelling-Point check
Strong convergence. The user's own submitted screenshot says verbatim "Los fondos están disponibles en tu billetera", and Lemon's internal panel shows the refund at 15:24:58 on the same day. A diligent panel will all read the same two records and reach the same conclusion: there is no outstanding debit.

## Bias audit
Checked: no anchoring on Lemon's framing — the decisive document is actually the user's own evidence. No sympathy bias overriding the documentary record. In dubio is not engaged because there is no doubt — the records agree.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The dispute concerns a card purchase of ARS 9.291 to MERPAGO*TOMASSO on 29 October 2025 (Trx ID 1c0d757c-fee3-487d-adc3-f82b161e27d4). The user claims the amount was debited and never returned. However, the user's own primary evidence — a screenshot of the Lemon app "Movimientos" screen for that exact transaction — labels it "Cancelado" and explicitly states "Hubo un error con el pago. **Los fondos están disponibles en tu billetera**". Lemon's internal operations panel for the same transaction ID corroborates this, recording the operation as "Rechazada" (motive: cancellation) with a "Devuelto" entry of ARS 9.291 timestamped 2025-10-29 15:24:58 — i.e. an automatic same-day refund roughly four hours after the failed attempt.

Applying Política Section A: Lemon satisfied Protección al Consumidor (A.1) by reversing the failed charge through its standard processor flow on the same business day; Información (A.2) and Transparencia (A.3) are satisfied because the status and remedy were clearly displayed to the user in the app at the time of the event; Buena fe (A.4) is satisfied by Lemon's diligent automatic remediation. The In dubio pro consumidor tiebreaker (A.5) does not engage because the two primary records — the user's screenshot and Lemon's panel — agree on the material fact that the funds were returned. There is no retention indebida and therefore no actionable harm.

For these reasons, the policy applied to the unrebutted documentary evidence points unambiguously to Favor Lemon.

---

Case 118 | VOTE: Favor Lemon | CONFIDENCE: high | User's own app screenshot states "Los fondos están disponibles en tu billetera"; Lemon panel confirms same-day automatic refund. No outstanding debit.
