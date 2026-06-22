# Case 38 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** FIAT (ARS) outgoing transfers from a Lemon Cash account to another bank/wallet account allegedly belonging to the same user (self-transfer).
**Amount in dispute:** ARS 32,000 (ARS 12,000 + ARS 20,000)
**Question:** Is Lemon liable to the user for two outgoing ARS transfers (21/06/2024) that the user claims were never credited at destination, when Lemon shows COELSA confirms both transfers as "COMPLETADO = S"?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Sección A.1 – Protección del usuario** (consumer-protection lens).
2. **Sección A.2 – Información** (Lemon must give clear, accurate operational information).
3. **Sección A.3 – Transparencia** (status of transactions must be transparently disclosed).
4. **Sección A.4 – Buena fe** (good-faith conduct by both parties).
5. **Sección A.5 – In dubio pro usuario** (tiebreaker only).
6. **Sección B – T&Cs**: subordinate to Section A; payment-rail allocation of responsibility once funds leave Lemon is consistent with industry standard and not in conflict with A.

## Burden of proof
User must show, on balance, that Lemon failed in its duty (e.g. did not transmit the funds, or misled about status). Once Lemon submits documentary evidence of completion via the regulated clearing house (COELSA), the evidentiary burden shifts to the user to rebut.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon comprobante #1: ARS 12,000 to Javier Rafael Goliate Moreno, CBU 0000069700000000270599, 21/06/2024 22:54, COELSA ID XJ8G7V95J3R4X1ML9EMPYR, green check | Screenshot | No | High — but shows transfer **sent**, not non-delivery |
| User | Lemon comprobante #2: ARS 20,000 same destination, 21/06/2024 23:18, COELSA ID 86VRPQ2GD8YO8W4G2GLY0M, green check | Screenshot | No | High — same as above |
| User | Assertion that funds did not arrive at destination | Bare allegation | Yes (by Lemon's COELSA query) | Low — no statement/screenshot from destination account showing non-credit |
| Lemon | Statement that COELSA was queried and both COELSA IDs returned "COMPLETADO = S" | Narrative + screenshot of back-office table | No (table illegible but narrative unrebutted) | Medium-High — corroborates user's own green-check receipts |
| Lemon | Statement that funds have left Lemon and any non-credit issue lies with destination provider | Argument | No | Medium |

Immaterial:
- The fact that a later, separate transfer worked normally — irrelevant to whether these two specific transfers cleared.
- COELSA's regulatory pedigree (BCRA-authorised since 1997) — accepted, not contested.

## Application
- **Protección:** User is protected against Lemon's failures, not against destination-bank delays. No evidence Lemon failed.
- **Información:** Lemon explained the rail (COELSA), provided the COELSA IDs in the receipts, and gave a coherent reason for any delay. Adequate.
- **Transparencia:** The receipts themselves disclose COELSA IDs and CBU; Lemon's status check is verifiable in principle. Transparent.
- **Buena fe:** Lemon investigated rather than dismissed; user's own receipts (green check) align with Lemon's account. No bad faith evidenced.
- **In dubio:** Would only apply if the evidence were genuinely tied. Here the user has not produced any statement, screenshot or denuncia from the destination account showing non-credit — the user's case rests on assertion only, while Lemon supplies a (modestly documented) third-party clearing-house confirmation. The scale is not tied.
- **Educación:** Lemon explained where to escalate next (destination provider). Acceptable.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Section B treatment of "funds leave Lemon → claim lies with destination provider" is standard and does not conflict with Section A on these facts.

## Jurisdiction / Morality / Validity
Standard consumer-finance dispute, within subcourt scope, no morality/validity issue. No basis to Refuse to Arbitrate.

## Schelling-Point check
A reasonable, policy-literate juror confronted with: (i) user's own Lemon receipts showing successful send + green check, (ii) Lemon's unrebutted statement that COELSA confirms both COELSA IDs as completed, and (iii) no evidence at all from the destination account of non-credit, would converge on Favor Lemon. The proper recourse is a denuncia at the destination provider.

## Bias audit
Tempting to lean to the user on a "small consumer vs. exchange" instinct, but the evidence package here is genuinely thin on the user's side — they have not even attempted to show the destination account never received the funds. Bias check confirms vote.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

The user submits two Lemon transfer receipts (ARS 12,000 and ARS 20,000, both 21/06/2024) and asserts the funds never reached the destination account, which the user says belongs to themselves. The receipts each carry a green "success" check, a COELSA ID, and a destination CBU. Lemon, in turn, states that it queried COELSA — the BCRA-authorised clearing house — for both COELSA IDs and that both transfers returned status COMPLETADO = S. Although Lemon's screenshot of the back-office query is too low-resolution to read at cell level, the accompanying narrative is unrebutted and is consistent with the user's own green-check receipts. Under the Política, unrebutted evidence is presumed genuine.

On Protección, Información, Transparencia and Buena fe (Section A.1–A.4), Lemon discharged its duties: it sent the funds through the regulated rail, disclosed COELSA IDs in the receipts, investigated rather than dismissing the complaint, and directed the user to the correct next step (a denuncia at the destination provider). The user has produced no statement, screenshot or third-party report from the destination account demonstrating non-credit — only a bare assertion. With Lemon's side documented and the user's side undocumented beyond the "sent" confirmation that both parties accept, the evidence is not in equipoise, so In dubio pro usuario (A.5) does not engage as a tiebreaker.

Accordingly, on the record before the panel, Lemon's responsibility ended once the funds cleared COELSA. Any non-credit at destination is a matter for the destination provider. Vote: Favor Lemon.
