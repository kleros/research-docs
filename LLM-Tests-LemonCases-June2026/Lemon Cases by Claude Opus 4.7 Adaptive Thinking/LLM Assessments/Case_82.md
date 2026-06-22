# Case 82 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Standard ARS peer-to-peer transfer (CBU/Mercado Pago) via Lemon Cash app — alleged unauthorized transfer
**Amount in dispute:** ARS 70,000
**Question:** Must Lemon refund / cancel a completed ARS 70,000 transfer that the user (registered for >2 years) now claims was unauthorized, where the transfer left the user's account on 05/10/2024 14:05 to a third-party CBU at Mercado Pago, no support ticket or police report was ever filed, and Lemon detected no compromise?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Sección A — Protección al Consumidor.** Lemon must safeguard users' economic interests and provide prompt responses to potential fraud/error.
2. **Sección A — Información / Transparencia.** Clear, accessible info on transaction execution and dispute paths.
3. **Sección A — Buena fe.** Both parties must act in good faith.
4. **Sección A — In dubio pro consumidor.** Tiebreaker only when residual doubt persists.
5. **Sección B — T&Cs operative where compatible with Section A.** Digifin T&Cs clause 3(e) places responsibility for accuracy of recipient data on the user executing the transfer. Outbound CBU transfers in the Argentine banking rail are operationally irreversible once cleared via COELSA.
6. **General Court morality clause** — no ruling in favour of theft/perjury.

## Burden of proof
The user is the moving party seeking a change to the default state (refund of a completed, on-rail-settled transfer). The user bears the burden of producing at minimum a coherent, contemporaneous account of unauthorized access (support ticket, police report, device-compromise evidence, or denial of the operation at the time it occurred).

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Bare assertion that the ARS 70,000 transfer "was not made by me" | Secondary (uncorroborated statement) | Yes — by Lemon's back-office + behaviour record | Low |
| User | Lemon transfer receipt (Juan Ramon Escobar, CUIT 20227796198, CBU Mercado Pago, COELSA ID 76V4MR2Z1YZRV6EGNDEZOL, 05/10/2024 14:05) | Primary | No | High (confirms the transfer was executed as instructed from the user's authenticated session) |
| Lemon | Back-office screen showing VIRTUAL_WITHDRAWAL Completada, same Trx ID f2bfa44d-…, user Carina Catacata, ID 1359337, TaxID 27396039252, timestamp 5/10/2024 14:05:19 | Primary | No | High |
| Lemon | App-flow screenshots showing recipient name/CBU surfaced + "Confirmá tu envío" / "Deslizá para confirmar" two-step confirmation UX | Primary | No | High (demonstrates Información/Transparencia/Educación discharged at point of transaction) |
| Lemon | Statement that no support contact, no police report, and no internal indicator of account compromise exists | Secondary (negative assertion) | Not rebutted by user | Medium-High (user does not claim to have reported the incident, filed a denuncia, or contacted support contemporaneously) |
| Lemon | Citation of Digifin T&Cs clause 3(e) (user responsible for recipient data accuracy) and irreversibility of fiat rails | Policy/contract | Not rebutted | Medium |

Immaterial:
- Generic invocations of "more than 2 years as a user" / appeals to platform trust — emotional anchoring, not evidence of unauthorized access.

## Application
- **Protección:** Discharged. Lemon offers fraud channels (support, denuncia avenue) and a two-step confirm UX. User invoked none. Protección does not require reversal of properly-executed, on-rail-settled fiat transfers in the absence of any contemporaneous compromise indicator.
- **Información:** Discharged. Pre-confirmation screen displays Nombre, Banco, CBU and a modal stating "Vas a enviar 🇦🇷 X ARS".
- **Transparencia:** Discharged. Receipt with full recipient data + COELSA ID is generated; Lemon explains the irreversibility of fiat rails and clause 3(e) of the Digifin T&Cs surfaced in-app.
- **Buena fe:** Lemon's account is internally consistent (back-office record matches the user's own receipt). User's good-faith claim is undermined by the absence of any contemporaneous report — no support ticket, no denuncia, no fraud claim filed with Mercado Pago — despite the alleged sum being financially material.
- **In dubio pro consumidor:** Not engaged. There is no residual doubt to break — the operation is documented from both sides, executed through the standard authenticated flow, and the user produced no evidence of unauthorized access.
- **Educación:** Discharged. The confirmation modal and slide-to-confirm gesture educate the user at the point of risk.
- **No discriminación:** Not engaged.
- **T&C compatibility (Sección B):** Digifin clause 3(e) (user accuracy responsibility) and fiat-rail irreversibility are compatible with Section A; they do not function as a catch-all immunity but operate exactly where Section A allows — when the platform has correctly executed the user's authenticated instruction and afforded clear pre-confirmation, the consumer-protection principles do not extend to forced refunds of validly settled transfers.

## Jurisdiction / Morality / Validity
Within scope of the Blockchain No Técnica subcourt (Lemon dispute, consumer claim). No morality trigger against Lemon. The user's bare unauthorized-transfer allegation, without a contemporaneous report, would — if treated as established without proof — risk rewarding a possible perjury / unjust-enrichment claim; the morality clause weighs marginally against forcing a refund on bare assertion.

## Schelling-Point check
A diligent panel reading Section A in light of Section B will see: (i) the transfer is documented on both sides; (ii) the user never reported the alleged compromise to support, Lemon, or the police; (iii) Lemon offered a two-step confirmation flow; (iv) fiat rails are operationally irreversible after COELSA settlement. The literal, obvious reading converges on Favor Lemon.

## Bias audit
User-friendly default (in dubio) inspected and rejected — no residual doubt, because the user produced no evidence of unauthorized access and admits no contemporaneous reporting steps. No party-identity, polish, or sympathy effects detected. Two-year loyalty argument is rhetorical, not evidentiary; discounted.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user alleges an unauthorized ARS 70,000 transfer on 05/10/2024 14:05 but submits only a Lemon receipt confirming the transfer was executed (recipient Juan Ramon Escobar, CBU Mercado Pago, COELSA ID 76V4MR2Z1YZRV6EGNDEZOL). No support ticket, no police report (denuncia), no contemporaneous fraud claim, no device-compromise indicator, and no rebuttal of Lemon's statement that its systems detected no account vulneración. As the moving party seeking to overturn a completed, on-rail-settled fiat transfer, the user bears the burden of producing at minimum a coherent contemporaneous record of unauthorized access. That burden is unmet.

Under Sección A, Protección, Información, Transparencia and Educación are discharged by Lemon's two-step confirmation UX (recipient name, bank and CBU surfaced; explicit "Confirmá tu envío" modal; slide-to-confirm gesture) and by issuance of a full receipt with COELSA ID. Buena fe runs against the user, whose unauthorized-access narrative is unsupported by any of the basic steps a defrauded consumer would normally take. In dubio pro consumidor is a tiebreaker and is not engaged here, because no residual doubt survives — both sides' primary records agree the transfer was executed from the user's authenticated session through the standard flow.

Sección B applies the Digifin T&Cs (clause 3(e) — user responsibility for recipient-data accuracy) compatibly with Sección A; the irreversibility of Argentine fiat rails once settled via COELSA is a structural feature, not a hidden limit. The correct remedy path, as Lemon notes, is for the user to engage Mercado Pago (the receiving institution) and file a denuncia — neither of which the user has done. The claim against Lemon fails.

---

**Case 82 | VOTE: Favor Lemon | CONFIDENCE: high | User produced only the transfer receipt; no support ticket, no denuncia, no compromise evidence — Lemon's pre-confirmation UX and fiat-rail irreversibility govern.**
