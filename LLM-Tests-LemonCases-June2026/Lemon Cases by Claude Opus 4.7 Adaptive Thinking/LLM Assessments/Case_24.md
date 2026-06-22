# Case 24 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (VISA prepaid card *7151) — disputed/unauthorised PedidosYa transaction
**Amount in dispute:** ARS 20,359.00 (PedidosYa charge, 09/02/2024 20:51hs)
**Question:** Must Lemon refund a PedidosYa card charge the user claims was unauthorised because his card had been "reported stolen and blocked"?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Section A.1 Protección — users must be protected from genuine fraud and unauthorised charges.
2. Política Section A.2 Información / A.3 Transparencia — the relevant facts (timing of card cancellation, funding of the card) must be accurately disclosed.
3. Política Section A.4 Buena fe — both parties must act in good faith; misrepresentation of facts weighs heavily.
4. Política Section A.5 In dubio pro consumidor — tiebreaker only.
5. Política Section B — T&Cs valid where compatible with Section A. Card T&C §5.1/5.2 require non-fraudulent merchant disputes to be raised first with the merchant; only fraudulent transactions trigger an issuer chargeback duty.

## Burden of proof
User must make a prima facie case that the transaction was unauthorised/fraudulent. Lemon must then rebut with verifiable card and account data. Unrebutted documentary evidence (admin/back-office records) is presumed genuine.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | App screenshot showing PedidosYa charge of ARS 20,359 on 09/02/2024 20:51 via VISA *7151 | Screenshot | No | Medium — confirms charge occurred |
| User | App screenshot showing card *7151 status "Tu tarjeta fue dada de baja" (timestamp 17:34) | Screenshot | Yes — Lemon shows the cancellation happened on 13/02/2024 17:20, after the disputed charge | Low — does not establish card was blocked at time of charge |
| User | Assertion that card had been "denounced for theft and blocked" before the charge | Allegation | Yes — contradicted by Lemon's back-office record | Low |
| Lemon | Back-office record: card *7151 state REPORTED, "último_cambio_estado" 13/02/2024 17:20 | Internal admin screenshot | Not rebutted | High — card was active on 09/02/2024 |
| Lemon | Back-office record: VIRTUAL_DEPOSIT of ARS 30,000 into user's account at 9/2/2024 20:38:40 (≈13 minutes before the PedidosYa charge at 20:51) from an account of the same titular (CUIT/Tax ID match) | Internal admin screenshot | Not rebutted | High — user funded the card immediately before the "unauthorised" charge |
| Lemon | Card T&Cs §5.1, §5.2 — non-fraudulent merchant disputes to be addressed to provider then escalated via VISA chargeback | T&C text | Not rebutted | Medium |

Immaterial:
- Cashback / retiro line items in the app screenshots — unrelated.
- Generic UI elements and promotional banners.

## Application
- **Protección:** Engaged only where the operation is genuinely fraudulent. The objective evidence (card not blocked until four days later; self-funded just before the charge from the user's own bank account) is inconsistent with third-party fraud.
- **Información:** The user materially mis-stated two facts — (a) that the card was blocked at the time of the charge, and (b) omitted the self-deposit of ARS 30,000 minutes earlier. These are not minor omissions.
- **Transparencia:** Lemon disclosed verifiable timestamps and account identifiers; the user's submission was selectively framed.
- **Buena fe:** Tilts against the user — the screenshot of the deactivated card is dated to the user's later visit and presented as if contemporaneous with the charge.
- **In dubio pro consumidor:** Not triggered — facts are not in equipoise; Lemon's documentary record clearly rebuts the user's account.
- **Educación:** Not centrally engaged.
- **No discriminación:** Not engaged.
- **T&C compatibility:** §5.1/5.2 (route non-fraud merchant disputes through the merchant and VISA chargeback) are compatible with Section A. Because the transaction is not shown to be fraudulent, the proper channel is PedidosYa / VISA chargeback, not an issuer refund.

## Jurisdiction / Morality / Validity
Within scope: a consumer-protection dispute over an alleged unauthorised card charge. No morality or validity issues.

## Schelling-Point check
A diligent juror reading both submissions will conclude that the user's "blocked card" claim is contradicted by Lemon's unrebutted internal record and that a same-day self-deposit funded the very charge complained of. The convergent vote is Favor Lemon.

## Bias audit
No identifiable bias. Section A.1 Protección instinctively favours consumers, but Protección does not extend to refunding genuine merchant charges the user funded themselves. No anti-corporate or pro-corporate tilt applied.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user alleges an unauthorised PedidosYa charge of ARS 20,359 on 09/02/2024 and argues the card had already been reported stolen and blocked. Lemon's unrebutted back-office record shows the card *7151 was first set to REPORTED on 13/02/2024 17:20 — four days after the disputed charge — and that ARS 30,000 was credited to the user's Lemon account from a bank account of the same titular (matching CUIT) at 20:38:40, only thirteen minutes before the PedidosYa charge at 20:51. These two documentary facts directly contradict the user's framing and were not rebutted.

Under Política Section A, Protección protects against genuine unauthorised use, not against merchant charges the cardholder funded themselves and challenges after the fact. Información and Buena fe weigh against the user, who selectively presented a "card blocked" screenshot taken after he later cancelled the card. In dubio pro consumidor is a tiebreaker only and is not engaged where the evidence clearly favours one side. Card T&C §5.1/5.2 — compatible with Section A — direct non-fraudulent merchant disputes to be resolved with the merchant and, where appropriate, escalated via VISA chargeback; that, not an issuer refund, is the correct path here.

Accordingly the vote is Favor Lemon with high confidence.
