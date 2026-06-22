# Case 101 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card payment to APPLE.COM/BILL for an EPIK PRO 1-year subscription (USD 29.99 / ARS 49,344.05), allegedly made by a minor without the cardholder's authorisation; Apple has reportedly approved a refund that has not been credited back to the user's Lemon account.
**Amount in dispute:** USD 29.99 (Apple charge) / ARS 49,344.05 (amount debited from Lemon account, incl. taxes/perceptions, on 15/4/2025).
**Question:** Must Lemon refund a card transaction that was completed with valid credentials, used by a minor in the cardholder's household, and for which Apple says it has issued a refund that Lemon has not yet received?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. Política de Lemon, Sección A — Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. T&C cláusula 3.7 — the user is the sole responsible party for all operations carried out on their account and must safeguard their access credentials and the Lemon card; any unauthorised use must be reported immediately.
3. Lemon Card is personal and non-transferable; custody of the physical/virtual instrument is the cardholder's responsibility.
4. Card-network mechanics — once a card payment is completed and funds have left the issuer, a refund can only be credited back when the merchant (Apple) actually settles it through the card scheme.
5. "Offer as presented" — the card service is offered with standard custody obligations on the user and no Lemon-side guarantee against family/household misuse.

## Burden of proof
The claimant (user) bears the burden of showing either (a) a platform failure by Lemon, (b) a Lemon-side breach of Sección A principles, or (c) that Lemon has actually received the Apple refund and is withholding it. None of those is shown.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Apple "Reportar un problema" screenshot dated 15/4/2025 showing "Reembolsado — Se te aplicó un reembolso por esta compra" for EPIK PRO USD 29.99, on Apple ID morenaibanez3407@gmail.com | Screenshot | Not rebutted as a screenshot, but it is from a different Apple ID than the Lemon account holder | Medium — proves Apple approved a refund on its side; does not prove the refund reached Lemon |
| User | Narrative that the purchase was made by a minor without consent | Statement | Effectively confirmed by Lemon (no fraud / valid credentials used) | High as to facts: a household minor used the card — i.e., custody failure, not platform failure |
| Lemon | Back-office screenshot: LEMON_CARD_PAYMENT trx 907d9c38…, "Completada", -ARS 49,344.05, VIRTUAL card 8981, merchant APPLE.COM/BILL, 15/4/2025 07:56 | System record | Not rebutted | High — shows operation processed normally and funds left Lemon |
| Lemon | Statement that no refund has been received from Apple in its systems | Statement | Not rebutted with any evidence that Lemon did receive the funds | High — user produced no proof that the refund reached Lemon |
| Lemon | Citation of T&C 3.7 (sole responsibility for account operations; duty to safeguard credentials and card) | Contractual clause | Not challenged | High — directly on point |

Immaterial:
- Apple's internal categorisation of the refund — relevant only to Apple, not dispositive of Lemon's obligation.
- The mismatch between the Apple ID (morenaibanez3407@gmail.com) and the Lemon account holder (jeremiasib76@gmail.com / Jesus Alberto Ezequiel Ibañez) — consistent with a household-minor narrative but not load-bearing.

## Application
- **Protección:** Lemon is not the source of harm. The harm originates in a third party (a minor in the user's household) using the card; remediation lies with Apple, which already approved the refund on its side. Protección does not require Lemon to advance funds it has not received from the merchant.
- **Información:** No claim that Lemon misinformed the user about card custody or refund mechanics. The standard "card is personal and non-transferable, holder is responsible" is the offer as presented.
- **Transparencia:** Lemon's back-office record is shared and consistent with the user's account of when and where the charge occurred. No hidden limits or surprise terms are at issue.
- **Buena fe:** Lemon's position — "we will pass on the refund when Apple actually credits us" — is the standard, good-faith card-issuer position. The user does not allege Lemon has actually received and is withholding the refund.
- **In dubio pro consumidor:** Tiebreaker only. There is no genuine tie: the user's own account places the wrongful act inside their household, and the user produced no evidence that Lemon received the refund. In dubio does not require Lemon to pay out of its own funds for an Apple-side refund that has not yet been routed.
- **Educación:** Not engaged — no asymmetric-knowledge issue beyond ordinary card mechanics.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Clause 3.7 (sole responsibility for account operations; duty to safeguard the card) is fully compatible with Sección A on these facts. It is not being used as a catch-all immunity against a platform failure; there is no platform failure to immunise against.

## Jurisdiction / Morality / Validity
Within scope of the Blockchain No Técnica court. No morality flag. The dispute is a routine card-refund-routing question, properly arbitrable.

## Schelling-Point check
A diligent juror reading both descargos converges on: the charge was a real card payment using valid credentials, made by someone inside the user's household; the merchant (Apple) — not Lemon — is the party that issued the refund; Lemon cannot credit funds it has not received and the user has produced no evidence that Lemon has received them. The Schelling vote is Favor Lemon.

## Bias audit
Sympathy for a parent whose child made an unauthorised in-app purchase is set aside. The legal question is narrow — has the user shown that Lemon (not Apple, not the user's household) owes a refund right now? The answer is no. No anti-consumer bias is being applied: if the user later shows Lemon has actually received the Apple refund and is withholding it, that would be a different case.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user's own descargo concedes that the disputed Lemon Card payment to APPLE.COM/BILL for the EPIK PRO subscription was made by a minor in their household, not by a third-party attacker or as a result of any platform failure. Lemon's back-office record corroborates that the transaction was authorised with valid credentials and processed normally on 15/4/2025. Under T&C 3.7 — which is fully compatible with Sección A on these facts — custody of the Lemon Card is the cardholder's exclusive responsibility, and household misuse does not shift that responsibility to Lemon. The principle of Protección does not require Lemon to act as guarantor against the user's own household.

The Apple screenshot is taken at face value: Apple, on its own side, marked the purchase as "Reembolsado". But that screenshot speaks only to Apple's decision; it does not show that the refund has actually been routed back through the card network and credited to Lemon. Lemon affirms it has not received the funds, and the user produced no evidence (e.g., a card-statement credit, a chargeback confirmation from the network, or a Lemon support-chat acknowledgement of receipt) to rebut that. Información, Transparencia and Buena fe are all satisfied — Lemon's position is the standard card-issuer position: when Apple actually settles the refund, it will land in the user's Lemon account.

In dubio pro consumidor is a tiebreaker and there is no genuine tie here. The proper remedy for the user is to pursue Apple to push the refund through the card scheme, after which Lemon will reflect it automatically; it is not for Lemon to advance funds out of its own balance sheet for a household misuse the user does not deny. Vote: Favor Lemon.

Case 101 | VOTE: Favor Lemon | CONFIDENCE: high | User's own household minor used card with valid credentials; Apple refund not yet routed to Lemon; no platform failure or Sección A breach.
