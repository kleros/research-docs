# Case 63 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Spanish-language consumer-protection layer, Lemon Cash policy)
**Promo / product at issue:** ARS peer-to-peer transfer via Lemon (Digifin fiat rails) — alias/CBU mis-typing leading to transfer to wrong recipient
**Amount in dispute:** ARS 29,600 (transferred 2 September 2024, 17:35)
**Question:** Should Lemon refund / redirect ARS 29,600 that the user sent to "Fiorella Marianel Alvarez" (Mercado Pago) when they intended to send it to "Fiorella Adriana Carrasco", a confusion they attribute to one letter in the alias?

## Options
- Favor User — order Lemon to refund / redirect the ARS 29,600
- Favor Lemon — claim rejected; Lemon executed lawful instruction it cannot reverse
- Refuse to Arbitrate — claim malformed / outside court scope

## Governing rules
1. **Política de Lemon — Sección A (overrides T&Cs where in conflict):**
   - A1 Protección del usuario
   - A2 Información (clear, accurate disclosures)
   - A3 Transparencia (no hidden limits)
   - A4 Buena fe (good faith on both sides)
   - A5 In dubio pro usuario — **tiebreaker only**
   - A6 Educación
   - A7 No discriminación
2. **Sección B** — T&Cs apply where compatible with Section A.
3. **T&C 3(e) (Digifin operatoria fiat):** the accuracy and veracity of transaction information (alias, CBU, destinatario) is the **exclusive responsibility of the user**, who must verify before confirming.
4. **Operational reality:** SPEI/CBU bank-rail transfers are irreversible once executed; the receiving institution (here Mercado Pago) is the only party with the recipient relationship to attempt recovery.

## Burden of proof
On the user, who seeks to overturn the default state (transfer executed as instructed). The user must show Lemon breached Section A or otherwise failed to deliver the service "as presented".

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon transfer receipt: ARS 29,600 to "Fiorella Marianel Alvarez", CUIT 27370689992, CBU 0000003100076092888343, Banco destino Mercado Pago, COELSA ID 1LMP68NK61YL5LZRNR7OEV, 02/09/2024 17:35 | Primary (Lemon-issued receipt) | No — Lemon's admin record matches | High — confirms the destination the user actually instructed |
| User | Narrative: intended recipient was "Fiorella Adriana Carrasco"; mistake caused by "una sola letra en el alias" | Secondary (uncorroborated self-statement) | Implicitly — no proof of the intended alias or that Lemon ever showed it | Low (goes to user's intent, not to Lemon's conduct) |
| Lemon | Admin panel record (VIRTUAL_WITHDRAWAL Completada, Trx ID matches, same CBU, same COELSA ID, ARS −29,600 from user's account) | Primary | No | High — confirms execution exactly per user instruction |
| Lemon | Two app-flow screenshots showing the "Enviar ARS" form (Nombre / Banco / Motivo) followed by the "Confirmá tu envío" modal listing Nombre, Banco, CBU with a "Deslizá para confirmar" gesture | Primary (product UI) | No | High — shows the confirmation step the user passed through |
| Lemon | Citation of T&C 3(e) placing verification duty on user | Policy text | No | High — directly applicable rule |

**Immaterial:**
- The exact letter that differed between the two aliases — not produced, and the dispute does not turn on which letter; what matters is that the **user, not Lemon, entered/selected the destination**, and Lemon then displayed the resolved recipient details for confirmation.

## Application
- **Protección (A1):** Lemon's flow already builds in a confirmation step displaying the recipient's name, bank and CBU before the irreversible swipe-to-confirm. That is a reasonable protective design for an irreversible bank rail; no concealed risk.
- **Información (A2):** The pre-confirmation modal disclosed the destinatario's Nombre, Banco and CBU. The user's own receipt shows that the displayed name ("Fiorella Marianel Alvarez") was not their intended recipient — they had the information needed to detect the error before confirming.
- **Transparencia (A3):** No hidden limit, fee or carve-out is in play. The irreversibility of CBU transfers is an inherent property of Argentine bank rails, not a hidden Lemon term.
- **Buena fe (A4):** Lemon executed the precise instruction the user authorised and offered the standard next step (contact the receiving institution, Mercado Pago). Nothing in the record suggests bad faith. The user candidly admits the mistake was their own.
- **In dubio pro usuario (A5):** Tiebreaker only. There is no genuine doubt here — the chain of events is documented by primary evidence from both sides and is consistent. A5 does not engage.
- **Educación (A6):** Not at issue; the user understood the transfer mechanism and confirmed it.
- **No discriminación (A7):** Not at issue.
- **T&C compatibility (Section B):** T&C 3(e) (user bears responsibility for accuracy of transaction data) is fully compatible with Section A because Lemon discharged its own A2/A3 duties by surfacing the recipient details on a dedicated confirmation screen. The T&C is therefore enforceable on these facts.

## Jurisdiction / Morality / Validity
Pass on all three. Spanish-language Lemon consumer dispute, properly in this court. No morality clause engaged. Question is well-formed and answerable.

## Schelling-Point check
A panel of diligent jurors will converge on Favor Lemon: irreversible bank-rail transfer, user-entered destination, on-screen confirmation of the resolved recipient, and a T&C clause that is squarely compatible with Section A. The user explicitly attributes the error to their own confusion. Recovery, if any, lies with Mercado Pago and the receiving account holder, not with Lemon.

## Bias audit
Sympathy for a user who lost ARS 29,600 to a typo is natural but cannot override clear policy application. No reliance on party identity, polish, or rhetorical style. Decision rests on primary evidence and the literal Section A / T&C 3(e) reading.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

The user acknowledges that the loss was caused by their own confusion between two similar aliases when initiating an ARS 29,600 transfer from Lemon to a Mercado Pago account on 2 September 2024. Lemon's primary evidence — the internal admin record and the two app screenshots — shows that the platform's send-flow requires the user to review a confirmation modal listing the resolved recipient's Nombre, Banco and CBU, and to perform an explicit swipe to confirm before the transfer is dispatched. The user's own receipt confirms the recipient name that was displayed ("Fiorella Marianel Alvarez"), which is not the person they say they intended to pay. Lemon therefore executed the instruction it was given, exactly as authorised, on an irreversible bank rail.

Applying Lemon's Policy Section A: Información (A2) and Transparencia (A3) were satisfied because the recipient details were surfaced before confirmation; Protección (A1) was satisfied by the design of the confirmation step itself, which is the appropriate protective layer for an irreversible CBU transfer; Buena fe (A4) is unimpeached and Lemon offered the only feasible next step — contacting the receiving institution. In dubio pro usuario (A5) is a tiebreaker only, and the facts here are not in genuine doubt. T&C 3(e), which places the duty to verify alias/CBU/recipient on the user, is fully compatible with Section A on these facts and is therefore enforceable under Section B.

The vote is to favour Lemon. Once funds have moved over the bank rail to Mercado Pago, the platform that received and credited them is the only party with the relationship needed to attempt recovery from the unintended beneficiary. Confidence is high.
