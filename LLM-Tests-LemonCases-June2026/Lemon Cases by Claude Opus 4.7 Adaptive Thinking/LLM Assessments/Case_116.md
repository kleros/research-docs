# Case 116 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (virtual) — recurring debit to SPOTIFY
**Amount in dispute:** ARS 5,278.40 (Tx ID `fabaaa37-1520-4...e00b`, 25/9/2025)
**Question:** Was the automatic debit to Spotify on 25/9/2025 an unauthorised charge that Lemon must reverse, or a legitimate recurring subscription renewal billed against the user's active virtual card?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. Protección al consumidor — fondos no pueden ser debitados sin consentimiento verificable.
2. Información — el usuario debe ser informado de cobros relevantes.
3. Transparencia — condiciones y mecanismos de cobro deben ser claros.
4. Buena fe — ambas partes deben actuar de forma leal.
5. In dubio pro consumidor — TIEBREAKER cuando la evidencia está empatada.
6. Educación financiera.
7. No discriminación.
8. T&Cs ceden ante Sección A en caso de conflicto.

Card-issuer norm: a virtual card legitimately authorised by the holder for a merchant-initiated recurring charge is an authorised debit; cancelling the subscription is the cardholder's responsibility with the merchant.

## Burden of proof
User must show the charge was unauthorised; Lemon must show the operation was executed from an authenticated environment against the user's active card and is consistent with a pre-existing pattern.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Lemon | Back-office detail of disputed Tx `faba...e00b` — Spotify, ARS 5,278.40, user's virtual card 9849, completed 25/9/2025 19:40 | Primary (internal ledger) | No | High |
| Lemon | Activity table showing three monthly Spotify charges to same card 9849: 25/7 (679.50, refunded provider_request), 25/8 (3,998.40), 25/9 (5,278.40) — same day-of-month, same merchant, same card | Primary | No | High |
| Lemon | Statement that operation came from authenticated environment, valid credentials, no security incident | Secondary (assertion) | No | Medium |
| User | Allegation that the debit was never authorised and never notified | Secondary (assertion) | Yes (by Lemon's pattern evidence) | Low |
| User | Screenshot of "Retirar" screen with VISA **5488 withdrawals and Skrill — unrelated card/flow | Secondary | n/a | None (immaterial) |
| User | Allegation that physical card never arrived despite multiple email claims | Secondary | Unrebutted but immaterial to this dispute (disputed charge was on VIRTUAL card 9849) | Low / immaterial |

Immaterial:
- Physical-card non-delivery complaint — separate grievance; the disputed transaction was executed on the user's active virtual card, so non-receipt of a physical card neither caused nor prevented the charge.
- "Retirar" screenshot — shows a different card (**5488) and withdrawal flow, not Spotify subscription billing.

## Application
- **Protección:** The debit was charged to a virtual card actively provisioned to the user, in a 3-month pattern matching a typical Spotify subscription cycle (same day of month, same merchant, same card). Protection does not extend to reversing legitimate merchant-initiated recurring charges against a card the user provisioned.
- **Información:** Lemon's evidence shows prior identical-pattern charges (July and August 2025) — the user had functional notice of the recurring relationship. The user offers no evidence of having queried or disputed the earlier charges at the time.
- **Transparencia:** Card transactions appear in the user's activity ledger. The merchant relationship (Spotify) is identifiable on the transaction. Lemon's stated position — cancellation must be handled with Spotify — is the standard card-network rule and was communicated via support.
- **Buena fe:** User frames the charge as totally unauthorised while omitting the existence of two prior monthly Spotify charges on the same virtual card. That omission undermines the good-faith characterisation of "nunca autorice."
- **In dubio:** Not triggered — the evidence is not in equipoise. Lemon's primary back-office records of an authenticated transaction on the user's own card, plus a clean monthly recurrence pattern, materially outweigh the user's bare assertion.
- **Educación:** Lemon's support response (cancel directly with Spotify) is correct consumer guidance for recurring card subscriptions.
- **No discriminación:** Not engaged.
- **T&C compatibility:** No conflict — recurring card charges initiated by an authorised merchant against an active virtual card are standard and consistent with Sección A.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt; no morality clause triggered; question is well-formed and answerable.

## Schelling-Point check
A diligent panel reading these materials would converge on Lemon: three consecutive monthly charges to Spotify on the same virtual card, executed from an authenticated environment, with the user silent on the prior two months, is the textbook fingerprint of an authorised recurring subscription — not an unauthorised debit.

## Bias audit
Resisted sympathy for the user's separate physical-card complaint, which is a real grievance but immaterial to this dispute. Weighed only evidence speaking to whether the 25/9/2025 Spotify charge was authorised. No reliance on party identity or rhetorical polish.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user claims an unauthorised automatic debit for transaction `fabaaa37-1520-4a8e-b8f1-fb00eb30e00b` (ARS 5,278.40 to Spotify, 25/9/2025). Lemon's unrebutted back-office evidence shows the charge was executed against the user's own active virtual card (Lemon Card 9849) from an authenticated session, and forms part of a clean monthly pattern of Spotify charges on the same card (25/7/2025 ARS 679.50; 25/8/2025 ARS 3,998.40; 25/9/2025 ARS 5,278.40) — the signature of an authorised recurring subscription. The user does not address, dispute or even acknowledge the two earlier charges, which materially undermines the assertion that the recurrence was unknown or unauthorised.

Applying Sección A of the Lemon policy: Protección al consumidor does not require an issuer to reverse legitimate merchant-initiated recurring charges against a card the cardholder authorised and continues to hold. Información and Transparencia are satisfied because the charges appear in the user's activity ledger under the merchant's name and have done so for three consecutive months. Lemon's support guidance — that cancellation of the subscription must be transacted with Spotify directly — is correct under standard card-network rules and is not in conflict with Sección A. Buena fe weighs against the user, who omitted the prior charges from the narrative. In dubio pro consumidor is a tiebreaker only and is not triggered, because the primary documentary evidence is materially one-sided.

The separate complaint about non-delivery of a physical card is immaterial to this dispute: the disputed transaction was executed on the user's active virtual card, so the physical card's status neither enabled nor prevented the charge. That grievance, if real, is a distinct matter for Lemon support. On the dispute presented, the correct vote is Favor Lemon.
