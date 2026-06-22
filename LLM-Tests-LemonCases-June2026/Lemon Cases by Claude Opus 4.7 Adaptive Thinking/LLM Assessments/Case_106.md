# Case 106 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash Peru — fiat cash-out (PEN) transfers to external Yape wallets via the PHONE / interbank rails on 01 June 2025.
**Amount in dispute:** Approximately S/ 41 (PEN) across three Lemon-side cash-outs (S/ 30 + S/ 10 + S/ 1), plus a S/ 10 "Pago por QR" the user also lists as missing — claim totals roughly S/ 51 PEN.
**Question:** Must Lemon refund (or otherwise make good on) the PEN transfers debited from the user's account on 01/06/2025 that the user says never arrived at the Yape destination wallets?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Section A.1 — Protección al Consumidor:** the service must not generate undue economic loss to the user where the loss flows from the provider's controllable layer.
2. **Section A.2 — Información:** the user must receive accurate information about the operation and its outcome.
3. **Section A.3 — Transparencia:** disclosures must be clear; hidden limitations on the service are disfavoured.
4. **Section A.4 — Buena fe:** both parties must act in good faith.
5. **Section A.5 — In dubio pro consumidor:** tiebreaker only — applies when, after weighing evidence, the case is genuinely balanced.
6. **Section A.6 / A.7 — Educación / No discriminación:** not engaged on these facts.
7. **Section B — T&Cs vs Section A:** Lemon's T&Cs ("All instructions are irrevocable") apply only insofar as they do not override Section A. A catch-all T&C cannot immunise Lemon if it has, in fact, failed to execute the rail it offered.
8. **Operational rule — "Offer As Presented":** Lemon advertises a PEN cash-out to Yape that should reach the destination wallet. Lemon's duty is exhausted only when the order is correctly routed to the receiving rail; once routed, downstream settlement at the receiving institution is outside Lemon's controllable layer.

## Burden of proof
The user, as claimant seeking a refund / change to the default state (transactions stand as executed), bears the initial burden to show that Lemon's controllable layer failed. Once Lemon produces back-office completion records, the burden shifts back to the user to rebut them.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon app screenshot showing four debits on 01/06 (S/ 30, S/ 1, S/ 10 envío, S/ 10 QR) | Primary (app capture) | No (consistent with Lemon's records on three of four) | Medium — confirms debits, not non-delivery |
| User | "Reporte de Movimientos" Yape report showing no inbound entries for 01/06/2025 | Secondary (table without source URL / signed PDF / Yape header chain) | Not directly rebutted; Lemon notes user should request traceability from Yape | Medium-low — relevant but partial; covers payments **made by** the user from Yape, not necessarily inbound receipts |
| User | Three Lemon transfer constancias (S/ 30, S/ 1, S/ 10) showing destination "Yape" / "No especificado", recipient names and phone numbers | Primary | Corroborates Lemon's back-office | High (as to issuance, not delivery) |
| Lemon | Three back-office screenshots: PERUVIAN_FIAT_CASH_OUT — Completada for S/ 30 (14:12 ARG), S/ 1 (14:36 ARG), S/ 10 (22:30 ARG), each with CCI Destino, phone, "Banco destino: YAPE", and an External ID | Primary (system records) | Unrebutted | High |
| Lemon | T&Cs clause: "Todas las instrucciones son irrevocables" | Primary (contract) | Unrebutted | Medium — constrains remedies but does not override Section A if Lemon failed to deliver |
| Lemon | Statement that once routed, Lemon has no custody, control, or visibility, and that the user should approach Yape with the External ID for traceability | Argument + procedural guidance | Unrebutted | Medium |

Immaterial:
- The S/ 10 "Pago por QR" on 01/06 — the user did not provide a constancia or back-office mirror for this; it is not the same product (QR pay, not a Yape cash-out) and the user does not separately argue this entry; treated as background.
- Support-chat "48 hours" timing — referenced but no screenshot of the conversation provided; cannot be weighted as a reliance event without the chat.
- Identity details of recipients (Brayan Morales / Eloyza Villanera, etc.) — not contested.

## Application
- **Protección:** the user alleges economic harm. But Lemon's controllable layer — instruction received, debit posted, order routed to YAPE via the interbank rail with a valid External ID and CCI — is documented as completed. Where money fails to land on the receiving wallet despite a clean send-side execution, Section A.1 does not, by itself, convert the upstream provider into the insurer of the downstream institution.
- **Información:** Lemon issued constancias with COELSA IDs, External IDs, and destination data — i.e. enough information for the user to lodge a trace with Yape. The user has not shown Lemon withheld or misstated information.
- **Transparencia:** Lemon disclosed that, post-instruction, it has no custody or reversibility. That limitation is consistent with how interbank cash-outs work and is not a "hidden limit"; it is a structural feature of any send-only rail.
- **Buena fe:** the user acted in good faith (sending test transfers to his own accounts is plausible diligence). Lemon also acted in good faith — it produced its internal records and offered the traceability route. No bad-faith signal from either party.
- **In dubio:** would apply only if evidence were genuinely balanced. Here, Lemon's primary system records show three completed cash-outs with destination identifiers; the user's main rebuttal is a Yape "Reporte de Movimientos" that reads as an outbound-payment history, not an inbound-receipts statement, and contains no entries that would even refute receipt. The case is not balanced — it tilts toward Lemon. In dubio is not engaged.
- **Educación / No discriminación:** not engaged.
- **T&C compatibility:** the "irrevocable instructions" clause is invoked appropriately; it limits Lemon's remedial capacity but does not, on these facts, conflict with Section A because no Section A breach is shown.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica); no morality clause engaged; question is well-formed and answerable.

## Schelling-Point check
A diligent panel reading both descargos would note: (i) Lemon's controllable layer is documented as completed; (ii) the user's "Yape report" does not clearly evidence non-receipt (it appears to be an outbound-payments report, and even at face value it shows no inbound history that could rebut delivery either way); (iii) the user has not shown Lemon withheld information or that there is a fault on the send side. The obvious, defensible reading is Favor Lemon, with a directive that the user pursue Yape using the External IDs.

## Bias audit
No reliance on party identity, polish, or sympathy. Small disputed amount (≈ S/ 51) does not lower Lemon's burden, but it also does not raise it. The user's claim is emotionally sympathetic but is not supported by evidence of a send-side failure.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
Under Política Section A, Lemon's duty on a fiat cash-out is to receive the instruction, debit the user, and route the funds correctly through the rail it offers (here, PEN → YAPE via the PHONE / interbank channel). Lemon's unrebutted back-office records show three PERUVIAN_FIAT_CASH_OUT operations marked **Completada** on 01/06/2025 (S/ 30, S/ 1, S/ 10), each with a destination CCI, recipient name, phone number, and External ID — exactly the data Yape needs to trace receipt. Lemon's constancias issued to the user match this. The "instructions are irrevocable" T&C is consistent with Section A here because no Section A breach by Lemon has been shown — Información and Transparencia are satisfied by the constancia data and by Lemon's disclosure of its post-routing limits.

The user's principal rebuttal — a Yape "Reporte de Movimientos" — does not establish non-receipt on the controllable side. The report reads as an outbound-payment history for the user's Yape account and does not show inbound entries for 01/06/2025 in a form that contradicts Lemon's send-side completion. The user has not produced the support-chat where the "48-hour" promise was allegedly made, has not produced a Yape ticket or denial citing the External IDs, and has not shown any send-side fault. Burden therefore rests where it started — on the user — and is not met.

Because the evidence is not genuinely balanced (Lemon's primary records are unrebutted), the *in dubio pro consumidor* tiebreaker is not triggered. The proper remedy for the user is to lodge a trace with Yape using the External IDs Lemon has already provided. Vote: **Favor Lemon**.
