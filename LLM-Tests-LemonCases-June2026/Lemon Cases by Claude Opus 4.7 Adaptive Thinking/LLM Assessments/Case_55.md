# Case 55 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Outgoing ARS transfer via Lemon to an external CBU (interbank transfer settled through COELSA)
**Amount in dispute:** ARS 150,909.00
**Question:** Did Lemon fail to deliver a transfer that was debited from the user's wallet, such that Lemon owes a refund or re-execution?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección del usuario** — Lemon must safeguard user funds against undue loss attributable to Lemon's operation.
2. **Información** — the offer as presented (transfer to CBU using COELSA) governs the service Lemon must deliver.
3. **Transparencia** — Lemon must give the user the means to trace/verify the transaction (e.g., COELSA ID).
4. **Buena fe** — both parties must cooperate honestly; Lemon must not stonewall a genuine claim.
5. **In dubio pro consumidor** — tiebreaker only, where evidence is genuinely balanced.
6. **Educación financiera** — Lemon should guide the user on next steps when the issue lies with another entity.
7. **No discriminación** — not at issue.
8. **T&Cs vs Section A** — Lemon's terms cannot displace Section A consumer principles, but where Section A is satisfied, Lemon's liability does not extend to acts/omissions of third-party banks.

## Burden of proof
The user, as claimant seeking a refund, bears the initial burden to show the funds did not leave Lemon's system or were misdirected by Lemon. Lemon then bears a rebuttal burden to substantiate completed dispatch.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon-issued comprobante: ARS 150,909, 29/7/2024 13:05, to "Cristina Noemi Torrales", CUIT 27274125050, CBU 0000205100272741250505, COELSA ID 3D5W612E38Q657KG2GXYVR, Trx ID 4bd3be5d-… | Primary (Lemon receipt) | No | High |
| User | Bare assertion that "the transfer did not arrive" at the destination | Secondary (self-report) | Yes — unsubstantiated by any destination-bank statement | Low |
| Lemon | Internal admin panel screenshot: same Trx ID, status "Completada", same COELSA ID, same destination CBU, same beneficiary (Cristina Noemi TORRALES, CUIT 27274125050, Lemontag cristinatorrales050) | Primary (system record) | No | High |
| Lemon | Statement that funds are no longer in Lemon's possession and recommendation to contact destination bank using COELSA ID | Secondary (party statement, but corroborated by COELSA ID issuance) | No | Medium-High |

Immaterial:
- Emotional urgency in the user's descargo — does not bear on whether Lemon performed.
- Apparent identity between sender and beneficiary (a self-transfer); not decisive but consistent with a legitimate operation Lemon completed as instructed.

## Application
- **Protección:** No evidence Lemon misappropriated or lost funds; the transaction reached the interbank clearing network (COELSA), so Lemon's custodial duty was discharged.
- **Información:** The offer presented was "send ARS to a CBU via COELSA". Both parties' records show that service was executed exactly as instructed — same amount, same CBU, same beneficiary tax ID, single matching Trx ID.
- **Transparencia:** Lemon provided a COELSA ID at the time of the transfer (on the user's own comprobante) — the canonical Argentine identifier needed to trace the transfer at the destination bank. Lemon also pointed the user to that ID and to the destination entity. This is transparent.
- **Buena fe:** Lemon did not stonewall; it produced its internal completion record and gave the user the next-step instruction (contact destination bank with COELSA ID). User produced no destination-bank statement, no failed-credit notice, no extracto showing the funds were returned/rejected.
- **In dubio:** Not triggered — the evidence is not balanced. Lemon's completion record is unrebutted and corroborates the user's own comprobante.
- **Educación:** Lemon told the user how to escalate (use COELSA ID at destination bank). Adequate.
- **No discriminación:** Not in issue.
- **T&C compatibility:** Lemon is not invoking a hidden carve-out; it is relying on the natural scope of its service (it transmits to COELSA; what the destination bank does post-COELSA is outside its operational control). Consistent with Section A.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica — fintech consumer dispute, Spanish). No morality issue. Question is well-formed and answerable.

## Schelling-Point check
A diligent panel reading both descargos will see: (i) Lemon issued a COELSA-stamped comprobante on 29/7/2024; (ii) Lemon's internal record marks the same Trx ID "Completada" to the same CBU; (iii) the user provides no evidence whatsoever that the funds were not credited at the destination — no bank statement, no rejection notice, no return-of-funds record; (iv) once a transfer carries a COELSA ID, it has left the originating PSP and any further inquiry belongs at the destination entity. Converging vote: Favor Lemon.

## Bias audit
Checked: no reliance on party size or identity; no sympathy weighting for the user; conclusion rests on the unrebutted documentary congruence between the user's own comprobante and Lemon's internal completion record, plus absence of any destination-side evidence from the user.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

Under Section A of the Política, Lemon's duties of Protección, Información and Transparencia are defined by the service as presented: transmit ARS from the user's wallet to a CBU through the Argentine interbank clearing network (COELSA). Both parties' primary documents — the user's own comprobante and Lemon's internal admin record — agree on every material field: amount (ARS 150,909), date/time (29/7/2024 13:05), destination CBU (0000205100272741250505), beneficiary tax ID (CUIT 27274125050), transaction ID (4bd3be5d-b1aa-4e95-b704-3b943de1aca7) and COELSA ID (3D5W612E38Q657KG2GXYVR). The internal record marks the operation "Completada". That is unrebutted evidence the transfer was dispatched as instructed and left Lemon's custody into the interbank system.

The user asserts the funds "did not arrive" but adduces no destination-bank statement, no rejection notice, no return-of-funds record, and no extracto from the receiving entity. Under standard Kleros evidentiary practice, unrebutted evidence is presumed genuine, and the burden of showing non-delivery falls on the party asserting it. The user has not met that burden, and Buena Fe does not allow the panel to infer Lemon's fault from silence at the destination end. Lemon, for its part, did not stonewall: it produced the completion record and directed the user to the only entity that can resolve a post-COELSA crediting issue (the destination bank), using the canonical COELSA ID — satisfying Transparencia and Educación.

In dubio pro consumidor is a tiebreaker and is not engaged because the evidence is not balanced. The catch-all consumer-protection principles in Section A cannot be stretched to make Lemon a guarantor of the destination bank's internal crediting, where Lemon's own service was demonstrably performed. Vote: **Favor Lemon**.
