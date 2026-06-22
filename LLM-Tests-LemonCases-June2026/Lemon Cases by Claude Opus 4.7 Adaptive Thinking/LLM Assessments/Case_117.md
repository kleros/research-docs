# Case 117 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Spanish-language consumer subcourt, inheriting from General Court)
**Promo / product at issue:** PEN (Soles Peruanos) outbound transfer from Lemon wallet to an external Peruvian bank account (CCI)
**Amount in dispute:** PEN 50.00
**Question:** Is Lemon responsible to the user when it issued a "Constancia de envío" voucher for a PEN 50 transfer on 18-Aug-2025 but, ~2 months later, informed the user that the payment "no se realizó", leaving the recipient demanding the funds?

## Options
- **Favor User** — Lemon must compensate / make the user whole for PEN 50 and reverse the reputational harm caused by the failed-but-confirmed transfer.
- **Favor Lemon** — The complaint is rejected; the user bears the loss under the irreversibility / user-data-responsibility T&Cs.
- **Refuse to Arbitrate** — Question is malformed, out of jurisdiction, or party engaged in immoral conduct enumerated in the General Court policy.

## Governing rules
1. **Política de Defensa al Consumidor, Sección A — Principio de Protección (1):** Lemon must protect users when the system fails them; users are the structurally weaker party.
2. **Sección A — Información (2):** Information actually delivered to the user (voucher, on-screen confirmation, "Constancia de envío") governs the relationship — the offer as presented controls.
3. **Sección A — Transparencia (3):** Hidden, delayed or contradictory information about the status of an operation is a violation; the user is entitled to timely, accurate status reporting.
4. **Sección A — Buena fe (4):** Both parties must act in good faith; Lemon must not issue a success confirmation and then, two months later, retract it without explanation, remediation or proof.
5. **Sección A — In dubio pro consumidor (5):** Tiebreaker — any genuine residual ambiguity resolves in favour of the user.
6. **Sección B:** Where T&Cs conflict with Sección A, Sección A prevails. Catch-all immunity clauses do not override Sección A.
7. **Burden / evidence rule:** Unrebutted evidence is presumed genuine. Support-chat or in-app confirmations create user reliance.

## Burden of proof
On the party seeking to depart from the default state shown to the user. Lemon issued an in-app "Constancia de envío" — that is the default state. To displace it, Lemon must prove (a) what actually went wrong, (b) that the failure is attributable to user input error, and (c) that it gave timely notice. Lemon has not discharged any of these.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon-app screenshot: green tick, "PEN 50.00 — 18 agosto 2025 - 20:42 hs", sender Noelia Karina Lopez Mendoza, recipient Yesica Rosmery Huarcaya De La Cruz, CCI 002-191-191084366008-54, N° operación 2025081820422209224152768049, ID tx 915bd881-08c3-43e0-afd3-c1d1dd3c9e43, branded "Constancia de envío" | Primary (Lemon's own generated voucher) | No | High |
| User | Statement that ~2 months later Lemon notified the payment "no se realizó", and the recipient is now demanding the money | Secondary (party statement) | Not rebutted by Lemon | Medium-High |
| Lemon | T&C citations on irreversibility and user responsibility for entered data | Secondary (legal boilerplate) | n/a — not on point | Low (irrelevant to the complaint actually filed) |
| Lemon | Side-by-side screenshots of the **ARS** (Argentinian pesos) send-flow, with a footnote "se ve captura de ARS pero es lo mismo en PER" | Secondary (wrong product flow) | n/a | Very low |
| Lemon | Reference to "CEE ID 20250818204222209224152768049" (28 digits) vs user voucher "N° de operación 2025081820422209224152768049" (27 digits) | Primary (internal reference) | Discrepancy unaddressed | Medium — actively undermines Lemon |

Immaterial:
- Lemon's irreversibility argument: the user is not asking Lemon to reverse a completed transfer; the user is saying Lemon told them the transfer was completed when it was not. Irreversibility is the wrong rule for the wrong question.
- The ARS-flow screenshots: do not depict the PEN flow at issue and prove nothing about what the user saw on 18-Aug-2025.

## Application
- **Protección:** Lemon delivered a "Constancia de envío" — a constancia is, by its plain Spanish meaning, a formal certification of a completed act. The user relied on it for ~2 months. Lemon's later retraction without remediation leaves the user owing PEN 50 to a third party for a failure inside Lemon's system. Protection principle squarely engaged in favour of the user.
- **Información:** The information actually presented to the user was a success voucher. The offer-as-presented rule means that controls. Lemon did not show any contemporaneous warning, pending state, or error message.
- **Transparencia:** A ~2-month delay in informing the user that an operation marked successful in fact failed is a textbook transparency violation. Lemon offers no explanation, no timeline, no system-log, no proof of attempted notification.
- **Buena fe:** Lemon's descargo does not engage with the core complaint at all. It recites generic irreversibility T&Cs and attaches a screenshot of the wrong currency/country flow. That is not good-faith engagement with the dispute presented.
- **In dubio pro consumidor:** Not strictly needed — the evidence already favours the user — but to the extent any residual doubt exists about what happened, the tiebreaker resolves in the user's favour.
- **Educación / No discriminación:** Not engaged.
- **T&C compatibility (Sección B):** Lemon's reliance on irreversibility / user-data-responsibility clauses is misplaced because there is no allegation that the user mistyped the CCI — the recipient is correctly identified and is in fact chasing the money. Even if a T&C said "Lemon is not liable for any failed transfer ever", such a catch-all would not override Sección A's protection, information and transparency duties.

## Jurisdiction / Morality / Validity
Pass. Spanish-language Lemon consumer dispute in the Blockchain No Técnica subcourt is correctly venued. No party-immorality flags under the General Court policy. Question is well-formed and answerable from the materials.

## Schelling-Point check
A diligent panel reading Sección A and looking at the two descargos converges on Favor User. The user's voucher is unrebutted primary evidence, Lemon's descargo answers a different question (irreversibility of a successful transfer) rather than the question asked (responsibility for a falsely confirmed transfer), and Lemon even cites a different operation number than the one on the user's voucher. The simple, literal reading is that Lemon failed in Información, Transparencia and Buena fe.

## Bias audit
Conclusion does not depend on party identity, sympathy or rhetorical polish — the user's prose is emotional but the decisive items are the unrebutted Lemon-branded voucher and Lemon's own failure to address the actual complaint. No anchoring on first evidence: reviewed Lemon's descargo in full, including its T&C citations, and found them off-point. No assumption of "good side / bad side"; the result follows from the policy applied to the evidence.

## VOTE
**Favor User**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user produced a Lemon-generated "Constancia de envío" voucher for a PEN 50.00 transfer made on 18 August 2025 at 20:42, identifying sender, recipient, CCI and a unique transaction ID. Under the Política de Defensa al Consumidor, Sección A, the information actually delivered by Lemon to the user — the voucher and the in-app success state — governs the relationship (Principio de Información). The user relied on that constancia for approximately two months. Lemon's eventual notification that the payment "no se realizó", without explanation, without contemporaneous warning, and without any remediation, is a direct breach of the Principio de Transparencia, and the resulting exposure to a third-party creditor engages the Principio de Protección al Consumidor.

Lemon's descargo does not engage with the dispute as presented. Its argument that operations are irreversible once validated is irrelevant: the user is not asking for a reversal of a completed transfer; the user is asking why Lemon issued a success constancia for a transfer Lemon now says never completed. The T&C citations on user responsibility for entered data are equally off-point — the recipient is correctly identified and is actively demanding the funds, so there is no allegation of mistyped CCI. The supporting screenshot Lemon attached is from the ARS (Argentinian) send-flow, expressly footnoted as such, and proves nothing about what the user saw on the PEN flow on the date in question. Lemon's own response also cites a CEE ID one digit longer than the operation number on the user's voucher, a discrepancy that is left wholly unexplained and that, if anything, supports the user's account of an internal routing failure. Under Sección B, the catch-all T&C immunities Lemon invokes cannot override the Sección A duties of Información, Transparencia and Buena fe.

For these reasons, the rules of decision point the same way and the in dubio pro consumidor tiebreaker is not needed. The Schelling-point answer a diligent panel converges on is Favor User: Lemon must make the user whole for PEN 50 and the consequential reputational exposure to the recipient.

---

Case 117 | VOTE: Favor User | CONFIDENCE: high | Lemon issued a "Constancia de envío" then retracted it two months later without explanation; descargo cites irrelevant irreversibility T&Cs and wrong-currency screenshot.
