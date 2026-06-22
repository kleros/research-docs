# Case 120 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash — peer-to-peer fiat transfer to a Yape (Peru) phone number
**Amount in dispute:** PEN 65.67
**Question:** Where a user manually entered a wrong recipient phone number, confirmed the transfer, and the funds were credited to a third party at Yape, is Lemon liable to refund or recover the funds?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. Política de Protección al Consumidor — Sección A: (1) Protección, (2) Información, (3) Transparencia, (4) Buena fe, (5) In dubio pro consumidor (tiebreaker), (6) Educación, (7) No discriminación.
2. Sección B — T&Cs apply only where compatible with Sección A.
3. Offer-as-presented governs Información/Transparencia: features Lemon advertised must work; hidden limits = likely violation. Conversely, where the system worked exactly as presented and the user-error is the proximate cause, the user's claim fails.
4. Lemon T&Cs (per Lemon's descargo, unrebutted): exactness of recipient data is the user's exclusive responsibility; the user must verify the data before confirming; once executed, transfers via real-time rails (Yape) cannot be reversed unilaterally.

## Burden of proof
On the claimant (User) to show that Lemon failed a duty under Sección A or that the platform's display/confirmation process was defective.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon constancia screenshot showing PEN 65.67 sent to +51 952 887 724 / CCI 002-405-107652494079-97 / Ruth Estefany Avalos Mamani / Yape | Primary | No | High |
| User | Narrative: typed a phone number "very similar" to their own; only last digits differ; did not notice on confirmation | Secondary (self-serving) | No direct rebuttal, but doesn't dispute that confirmation was shown | Medium |
| Lemon | Back-office record (Trx b29cad9c-…) confirming PERUVIAN_FIAT_CASH_OUT Completada to the same CCI/phone/name | Primary | No | High |
| Lemon | Description of UX: number displayed, recipient name shown when available, explicit final confirmation required | Secondary (corroborated by user's own constancia which shows recipient NAME "Ruth Estefany Avalos Mamani") | No | High |
| Lemon | Argentine "Enviar ARS" screenshots — analogue, "idéntica a Perú" per Lemon | Secondary / illustrative | Not rebutted but admittedly from a different country | Low |

Immaterial:
- Argument that Lemon should have warned about "numbers similar to the user's own" — no policy/T&C clause requires this feature and none was advertised.
- "Saturday morning indebida economía y preocupación" — emotional appeal, not material to a Sección A criterion.

## Application
- **Protección:** Lemon offered the standard safeguards expected of a real-time transfer service: display of the entered number, display of the recipient's real name pulled from Yape, and an explicit final confirmation step. The user's own constancia confirms the recipient name "Ruth Estefany Avalos Mamani" was displayed — i.e. the protective check existed and operated. No protección breach shown.
- **Información:** Recipient name, phone, CCI, destination bank (Yape) were all surfaced before/at confirmation. Information duty satisfied.
- **Transparencia:** The constancia is detailed and complete; Lemon's back-office record matches it. Transparency satisfied.
- **Buena fe:** User acted in good faith (Lemon expressly concedes this). But buena fe of the user does not transmute a user-typed wrong number into a Lemon obligation, because Lemon also acted in good faith and within its disclosed process. No buena-fe breach by Lemon.
- **In dubio pro consumidor:** Tiebreaker only. No genuine tie here — the facts are agreed and the user-error is the proximate cause. In dubio does not activate.
- **Educación:** Not engaged; user was not misled about how transfers work.
- **No discriminación:** Not engaged.
- **T&C compatibility (Sección B):** Lemon's clause placing recipient-data accuracy on the user is fully compatible with Sección A: it does not strip protección/información, it simply allocates responsibility for the one input only the user controls (the recipient identifier). Compatible and enforceable.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica, consumer dispute). No morality flags. Question is well-formed and answerable.

## Schelling-Point check
A diligent juror panel will converge on Favor Lemon: the user's own evidence (the constancia) shows the recipient's real name was displayed before confirmation, the transfer executed exactly to the data the user typed and confirmed, and real-time Yape transfers are not unilaterally reversible by the sender's wallet. The Sección A principles do not impose a "warn if similar to user's own number" duty that was never advertised.

## Bias audit
Sympathy for a small-amount user-error loss noted and discounted. No party-identity weighting; decision rests on the documentary primary evidence which both parties submitted and which agrees on every material fact.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user concedes that they personally entered the recipient phone number, did not notice that the last digits differed from their own, and confirmed the transfer. Their own submitted constancia shows that Lemon, before execution, displayed the recipient's real name ("Ruth Estefany Avalos Mamani"), phone, CCI and destination bank (Yape) — i.e. exactly the protective and informational steps that Sección A (Protección, Información, Transparencia) of the Política requires. Lemon's back-office record matches the user's constancia byte-for-byte on the operative fields, and is unrebutted. Under the offer-as-presented standard, Lemon's transfer flow operated precisely as presented; there was no hidden limit and no failed safeguard.

The user invokes Protección and Buena fe to argue Lemon should have warned about numbers similar to the user's own and should now claw the funds back. Neither obligation exists. No clause of Sección A or of any feature offer made by Lemon advertises a "similar-number warning", and Yape transfers are real-time push payments that the sending wallet cannot unilaterally reverse once executed to a third-party institution. Lemon's T&C allocating recipient-data accuracy to the user is compatible with Sección A under Sección B because it leaves Protección/Información intact and only allocates the single input the user alone controls.

In dubio pro consumidor is a tiebreaker, and there is no tie: the facts are agreed and the proximate cause is the user's own typing error on an input the platform correctly displayed for verification. The appropriate remedy lies with Yape and the third-party recipient, not with Lemon. Vote: Favor Lemon.
