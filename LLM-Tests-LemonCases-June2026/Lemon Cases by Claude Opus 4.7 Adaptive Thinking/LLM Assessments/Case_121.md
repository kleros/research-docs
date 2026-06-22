# Case 121 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card — moneda de respaldo (ETH backup currency) auto-debit for card purchases.
**Amount in dispute:** ~$45,000 ARS (in ETH equivalent), per user. Lemon traces an ETH debit triggered by a $35,000 ARS payment to "Facturas Claro" with a $882.69 ARS shortfall on ARS balance.
**Question:** Did Lemon wrongfully cause the disappearance of the user's crypto, or did the ETH debit follow the user's own backup-currency configuration for a card purchase?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Protección al consumidor** — funds must remain in the user's account until the user disposes of them.
2. **Información** — material conditions (e.g., that backup currency will be auto-debited and for the full amount) must be communicated as presented.
3. **Transparencia** — the operative mechanic and the resulting movements must be visible/explainable.
4. **Buena fe** — both parties must act in good faith; no hidden traps.
5. **In dubio pro consumidor** — tiebreaker only.
6. **Educación financiera** — Lemon should help users understand mechanics.
7. **No discriminación** — not at issue.
8. **T&Cs** cannot override Section A; offer-as-presented governs.

## Burden of proof
On Lemon to explain the disappearance of assets the user claims were not moved by him. Lemon discharges this by tracing the operations and showing the user-configured backup-currency mechanic. Then on User to rebut.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | "Movimientos" screenshot showing ARS deposits, two crypto purchases (11/12: $27,722; 12/12: $16,100), MERPAGO COVERYOURCASE $20,882.69, FLORES SILVESTRE SA $6,500 | Primary (app) | Consistent with Lemon's trace; user's screenshot does NOT show any Claro payment or any ETH debit | High |
| User | Narrative: "I bought crypto, never sold/moved it, it's gone" | Secondary | Rebutted by Lemon's transactional trace | Low |
| Lemon | Trace: ETH purchase 0.0034169 ETH ($16,100); ARS deposit $30,000; MERPAGO $20,882.69; ARS deposit $25,000 (balance $34,117.31); then "Facturas Claro" payment $35,000 with $882.69 ARS shortfall → backup ETH debited for the shortfall | Primary (back-office records) | Not rebutted by user | High |
| Lemon | Back-office config screenshot — user designated ARS principal, ETH backup | Primary | Not rebutted | High |
| Lemon | In-app "Entendido" modal text quoted verbatim: "Cuando no tengas saldo suficiente en tu moneda principal, se usará automáticamente la de respaldo para pagar el total de tu compra…" | Primary (offer-as-presented) | Not rebutted | High |
| Lemon | Illustrative App screenshots of "Pago con" and modal (explicitly stated as illustrative, not user's account) | Secondary | n/a | Medium (supports clarity of disclosure) |

Immaterial:
- FLORES SILVESTRE SA $6,500 line — extraneous merchant payment, not the trigger event.
- MERPAGO COVERYOURCASE $20,882.69 — earlier card spend, accounted for in trace.

## Application
- **Protección:** No unauthorized seizure shown. ETH debit is the direct consequence of a user-initiated Claro payment exceeding ARS balance — i.e., user disposed of the funds via his own purchase.
- **Información:** Offer-as-presented (modal text Lemon quotes verbatim) clearly states backup currency auto-debits the **total** of the purchase when principal is insufficient. The user's account is also debited the *shortfall* per Lemon's account; the disclosed mechanic is at least as broad as what occurred.
- **Transparencia:** Lemon provides a full operation-ID trace tying ARS deposits, ETH purchase, MERPAGO, second deposit, and Claro payment with calculated shortfall. User's own screenshot is consistent with the ARS leg of this trace.
- **Buena fe:** User's "Movimientos" view does not include the Claro/ETH-debit line; the user either omitted that screen or the movement was logged under "Tarjeta"/services. The user does not deny attempting a Claro payment; he simply ignores it. Lemon's trace is unrebutted.
- **In dubio:** Not triggered — Lemon's evidence is concrete, primary, and unrebutted; user's case rests on a partial screenshot and a narrative inconsistent with Lemon's records.
- **Educación:** Backup-currency mechanic is explained in-app via "?" icon and "Entendido" confirmation step; user explicitly opted in.
- **No discriminación:** N/A.
- **T&C compatibility:** Lemon relies on the user's voluntary configuration plus the in-app disclosed mechanic — not on hidden T&C immunity. Compatible with Section A.

## Jurisdiction / Morality / Validity
Pass. Proper subcourt; no morality flag; question is well-formed.

## Schelling-Point check
A diligent panel will see: (i) a user claiming silent disappearance, (ii) a provider producing a clean ID-level trace including the user's own ARS deposits and card spends, (iii) the user's own screenshot corroborating the ARS leg, and (iv) a disclosed, opt-in backup-currency mechanic with an "Entendido" confirmation. Convergence is on Favor Lemon.

## Bias audit
No reliance on identity or sympathy. The user's loss feels real subjectively, but the policy requires evidence-grounded findings. Lemon's trace is unrebutted and the disclosure is clear and opt-in.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user alleges that ~$45,000 ARS in crypto disappeared from his Lemon account without any sale, transfer, or authorization. Lemon answers with an operation-level trace: a 12/12 ETH purchase (0.0034169 ETH for $16,100 ARS), an ARS deposit of $30,000, a card payment to MERPAGO COVERYOURCASE for $20,882.69, a further ARS deposit of $25,000 (consolidating $34,117.31 ARS), and then a Lemon Card payment to "Facturas Claro" of $35,000 ARS that exceeded the ARS balance by $882.69 ARS. The shortfall triggered the user-configured backup currency (ETH) to settle the card transaction. The user's own "Movimientos" screenshot corroborates the ARS deposits and the MERPAGO charge but contains no rebuttal of the Claro payment or the backup-currency debit.

Under Section A, **Información** and **Transparencia** are satisfied: Lemon quotes verbatim the in-app modal — "Cuando no tengas saldo suficiente en tu moneda principal, se usará automáticamente la de respaldo para pagar el total de tu compra" — and the mechanic was activated by the user via the explicit "Entendido" confirmation, with ARS as principal and ETH as backup. **Protección al consumidor** is not breached because the ETH was not seized; it was applied to a payment obligation the user himself initiated through his Lemon Card. **Buena fe** runs against the user's incomplete account: he ignores the Claro payment entirely. **In dubio pro consumidor** does not engage because Lemon's primary, ID-level evidence is unrebutted.

Accordingly, the offer-as-presented governs and is consistent with what occurred. T&C immunity is not relied upon. The vote is **Favor Lemon**.
