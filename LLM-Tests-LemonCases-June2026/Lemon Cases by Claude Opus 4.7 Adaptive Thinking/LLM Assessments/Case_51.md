# Case 51 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Lemon Cash consumer sub-court)
**Promo / product at issue:** Outbound ARS bank transfer (fiat off-ramp via Digifin) from Lemon to an external Mercado Pago CBU
**Amount in dispute:** ARS 10,000 (single transfer dated 26/07/2024 13:08)
**Question:** Should Lemon reimburse a user who voluntarily executed an ARS 10,000 transfer from his Lemon account to a Mercado Pago CBU and now claims he sent it to the wrong recipient?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Sección A.2 — Información:** the user must receive clear, sufficient and truthful information about the operation being performed (destination, identity of the recipient, amount, irreversibility).
2. **Política Sección A.3 — Transparencia:** what is offered / shown on the interface governs; hidden conditions or post-hoc limits favour the user.
3. **Política Sección A.1 — Protección:** the platform must take reasonable measures to protect the user (e.g. confirmation screens, visible recipient details).
4. **Política Sección A.4 — Buena fe:** both parties act in good faith; a user who self-admits the error cannot turn that admission against the counterparty without independent fault.
5. **Política Sección A.5 — In dubio pro consumidor:** TIEBREAKER only — applied if, after weighing, the case is genuinely balanced.
6. **Política Sección B — T&Cs vs Sección A:** Lemon T&C 3(e) (responsibility for accuracy of recipient data rests on the user) is enforceable to the extent it is compatible with Sección A; it cannot override A but can be applied where A is satisfied.
7. **General principle on rails:** an interbank ARS transfer via CBU, once executed and credited, is irreversible at the rail level — Lemon cannot unilaterally claw back funds from the receiving institution (Mercado Pago).

## Burden of proof
The user is the claimant seeking a change to the default state (transfer already completed). The user therefore bears the burden of proving either (a) a Lemon-side failure (mis-execution, hidden term, missing/false information, system error), or (b) that Lemon could still recover the funds and refuses to. Absent that, the default — transfer stands — prevails.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Comprobante de transferencia: ARS 10,000 on 26/07/2024 13:08 to Rodolfo Jesus Ramon El Ahmed, CUIT 20175588540, CBU 0000003100061886591905, Banco destino Mercado Pago, Motivo "Varios", COELSA ID ORD6LEN8QO37R5XO9M1Y30, tx 06b39e46-5c53-4308-a20f-6c1f0e903810 | Primary (Lemon-issued receipt) | No | High (proves the transfer happened and was credited externally) |
| User | Self-statement: "una transferencia que se envió por error a un destinatario incorrecto" — admits the error was his own | Secondary (party statement) | No | High — it is an admission against interest |
| Lemon | Admin back-office screenshot showing the withdrawal in "Completed" status, with user data (Gaston Riveros, lemontag rrgaston78, CUIT 20409303855) and matching transaction metadata | Primary | No | High — corroborates execution per instructions |
| Lemon | Two app-flow screenshots showing the "Enviar ARS" send flow and the "Confirmá tu envío" modal that displays recipient Nombre, Banco and CBU and requires a slide-to-confirm gesture before dispatch | Primary | No | High — shows the offer-as-presented contained the recipient identifiers in a confirmation step |
| Lemon | Reference to T&C clause 3(e): user is responsible for verifying alias and recipient data before confirming | Contractual | No | Medium — enforceable only insofar as compatible with Sección A |

Immaterial:
- Cosmetic differences between the user's receipt IDs and the back-office screenshot's IDs (different tx ID strings) — both parties agree a transfer was executed; identity of the specific transfer is not in dispute.

## Application
- **Protección:** Lemon provided a confirmation modal ("Confirmá tu envío") with recipient name, bank and CBU plus a deliberate slide-to-confirm gesture. That is a standard, reasonable protective measure. SATISFIED.
- **Información:** the receipt itself (issued by Lemon) lists the recipient's full name, CUIT, CBU, destination bank, and tx IDs. The confirmation screen presents Nombre, Banco, CBU before the user confirms. The user therefore had the information needed to verify the recipient. SATISFIED.
- **Transparencia:** the offer as presented matches what was executed — the funds went to the CBU the user entered, to the recipient associated with that CBU. There is no hidden limit, no surprise term, no bait-and-switch. SATISFIED.
- **Buena fe:** the user openly states this was his own error. Lemon executed faithfully. No bad faith on either side. SATISFIED.
- **In dubio pro consumidor:** not triggered — the user's own admission removes the doubt that would otherwise activate the tiebreaker.
- **Educación:** no educational failure alleged; the in-app confirmation flow itself functions as a user-facing safeguard.
- **No discriminación:** not implicated.
- **T&C compatibility:** T&C 3(e) is compatible with Sección A here because Sección A is independently satisfied — Lemon both informed and protected the user. The clause is not being used to immunise a hidden defect; it is being applied to a normal user-side input error.

## Jurisdiction / Morality / Validity
Pass. Standard Argentine fintech consumer dispute, correct sub-court, no morality clause triggered, question is well-formed and answerable.

## Schelling-Point check
Strong. A panel of diligent jurors reading the same materials sees: (i) the user self-admits the error; (ii) Lemon displayed the recipient details in a confirmation step; (iii) ARS interbank transfers via CBU are irreversible at the rail; (iv) the funds were credited to a third-party institution (Mercado Pago) — recovery, if any, lies with that institution and the recipient, not with Lemon. The literal application of Sección A produces a single obvious answer: Favor Lemon.

## Bias audit
No sympathy pull toward the larger party. The user is clearly a retail consumer who lost real money, and the instinct is to favour him — but the policy is rule-application, not advocacy, and the user has not identified any Lemon-side failure. The vote follows the evidence and the policy, not the wealth or polish of either side.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user openly admits that the ARS 10,000 transfer on 26/07/2024 was sent in error to a recipient he himself entered ("una transferencia que se envió por error a un destinatario incorrecto"). The Lemon receipt and back-office record both show that the transfer was executed exactly as instructed — to CBU 0000003100061886591905 (Banco Mercado Pago), recipient Rodolfo Jesus Ramon El Ahmed, CUIT 20175588540 — and that it settled at the rail level (COELSA ID ORD6LEN8QO37R5XO9M1Y30). Once an Argentine interbank CBU transfer settles, the funds are in the receiving institution's custody and Lemon has no unilateral power to reverse them.

Applying Sección A: Información and Transparencia were satisfied because Lemon's confirmation modal ("Confirmá tu envío") displays the recipient's name, bank and CBU before a deliberate slide-to-confirm gesture, and the post-transfer receipt repeats the same data. Protección was satisfied by that same confirmation step. Buena fe is uncontested — Lemon executed faithfully and the user does not allege otherwise. In dubio pro consumidor is the policy's tiebreaker and does not engage here because the user's own admission removes the doubt. T&C clause 3(e) (user verifies recipient data) is therefore compatible with Sección A in this case and is properly applied.

Where the user's loss is real, the policy-correct remedy lies against the recipient or, at most, against the receiving institution (Mercado Pago) — not against Lemon, which discharged its obligations under the offer as presented. The claim against Lemon is therefore rejected. VOTE: Favor Lemon.
