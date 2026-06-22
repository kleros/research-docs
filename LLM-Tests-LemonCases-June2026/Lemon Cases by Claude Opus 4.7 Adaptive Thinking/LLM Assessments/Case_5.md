# Case 5 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Lemon Cash consumer-protection subcourt)
**Promo / product at issue:** Lemon Cash prepaid VISA card — disputed Tinder charge
**Amount in dispute:** ARS 3,525.15 (Tinder charge dated 27/04/2023 01:38–01:39hs)
**Question:** Must Lemon refund a card-not-present Tinder charge the user disowns, where Lemon's transaction log shows the charge entered as "DEBITO AUTOMATICO" (recurring) on a card the user kept in his possession, with no other contested charges and continued normal use of the card by the user during the same days?

## Options
- **Favor User** — uphold and compensate.
- **Favor Lemon** — reject claim.
- **Refuse to Arbitrate** — only if RtA trigger fires.

## Governing rules
1. Section A principles 1–7 control; T&Cs only operate if Section B-compatible.
2. Consumer is the vulnerable party (Protección) but must still substantiate a fraud claim with at least minimal corroboration when objective transaction records contradict the unauthorised-use narrative.
3. Unrebutted documentary evidence (Crediware ledger) is presumed genuine; user bears the practical burden of explaining inconsistencies once the provider produces it.

## Burden of proof
User must show, on the balance of probabilities, that the charge was not authorised by him; Lemon, having alleged a registered-card debit, must produce the technical record supporting that (it did).

## Material evidence

| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of Tinder charge ARS 3,525.15 on 27/04/2023 01:39hs, VISA *4453 | Primary | No (consistent with Lemon log) | Confirms charge existed — neutral on authorisation |
| User | Support chat with "Claribel" — user states he has Tinder account unused for months, card not registered in any subscription, not in Apple Pay, was sleeping at 01:39 | Secondary (self-report) | Partially rebutted by Crediware "DEBITO AUTOMATICO" flag | Low — uncorroborated declarations |
| Lemon | Crediware ledger (10 transactions 27–30/04/2023) showing the disputed Tinder charge logged as DEBITO AUTOMATICO, modo entrada 01, APROBADA | Primary | No | High — objective system record indicating a stored/recurring credential, not a one-off CNP attack |
| Lemon | Same ledger showing user continued normal use of card on 27/04 (Pedidos Ya 18:03, 18:34, 21:37, 22:29, 22:50 Tres Calaveras) and on 28/04 (Kiosco 01:52) | Primary | No | High — undermines theft/compromise theory; user kept card and used it actively the same evening |
| Lemon | No rejected attempts elsewhere; no other fraud anywhere on the card | Primary | No | Medium — inconsistent with credential theft pattern |
| Lemon | User confirms card in his possession; no police report | Admission | No | Medium |

Immaterial / discarded:
- Battery/time-of-day of screenshot pages — irrelevant.
- User being "asleep" at 01:39 — a recurring/automatic debit does not require user presence, so this is non-probative.

## Application (principle-by-principle)
- **Protección:** Consumer is vulnerable, but protección is not a strict-liability refund rule. Where objective records show a stored-credential automatic debit and the user retained the card and continued using it, protección does not require Lemon to absorb the loss.
- **Información:** No advertising/offer is at issue; Lemon's fraud-prevention features (pause card, limits, notifications) were available and a notification was received by the user — Información satisfied.
- **Transparencia:** Lemon disclosed the investigation criteria, the security questions, and shared the Crediware ledger. No misleading practice identified.
- **Buena fe:** Lemon engaged via support, conducted a documented investigation, asked appropriate questions. User's account is plausible but contradicted by the "DEBITO AUTOMATICO" entry-mode and the absence of any other compromise indicator; on the record presented, user has not discharged the minimal corroboration expected.
- **In dubio pro consumidor:** Tiebreaker only. Here the evidence tilts toward Lemon (DEBITO AUTOMATICO flag + retained card + no other fraud + continued same-day use), so no tie to break.
- **Educación / No discriminación:** N/A.
- **T&C compatibility (Section B):** No specific T&C clause invoked; Lemon's decision rests on transactional evidence, which is Section A-compatible.

## Jurisdiction / Morality / Validity check
Pass — ordinary consumer-fraud dispute, properly within the subcourt; materials sufficient to decide.

## Schelling-Point check
A diligent panel reading "DEBITO AUTOMATICO" on the same card the user admits holding, with no other fraud and continued normal use the same evening, would likely converge on Favor Lemon.

## Bias audit
Sympathy for a consumer disputing a small charge is set aside; the technical record, not the early-hour timestamp, governs because a stored-credential recurring debit fires regardless of whether the cardholder is awake.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

Under Principle 1 (Protección) and Principle 4 (Buena fe), the consumer is vulnerable but not automatically entitled to a refund where the provider produces objective transactional evidence inconsistent with the unauthorised-use theory. Lemon's Crediware ledger records the disputed Tinder charge as "DEBITO AUTOMATICO" with online entry mode 01, indicating a stored/recurring credential rather than a one-off card-not-present attack, and shows the same card being used normally by the user later the same day (Pedidos Ya, Tres Calaveras) and the following day. The user admits the card remained in his possession, filed no police report, and has a (dormant) Tinder account — facts that, taken together, point to a previously-registered subscription credential firing automatically rather than fraud.

Principles 2 (Información) and 3 (Transparencia) are satisfied: Lemon documented its investigation, asked the standard security questions, and disclosed the underlying ledger. No misleading practice or omitted material limit in an offer is in play. Principle 5 (in dubio) is a tiebreaker and is not reached here, because the evidentiary balance favours Lemon rather than producing genuine doubt.

For these reasons the appropriate option is **Favor Lemon**. The user's narrative — being asleep at 01:39 — is non-probative against an automatic debit, and no corroborating indicator of compromise (rejected attempts elsewhere, other unrecognised charges, lost card, police report) is present.
