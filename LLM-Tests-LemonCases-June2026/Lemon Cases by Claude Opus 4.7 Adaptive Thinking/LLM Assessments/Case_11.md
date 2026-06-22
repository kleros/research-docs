# Case 11 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash debit-card transaction / chargeback (compra desconocida)
**Amount in dispute:** ARS 15,493.67 (user states ARS 15,500) — card purchase to "Dlocal *Hostinger Com" on 06 Oct 2023
**Question:** Must Lemon refund a card transaction the user claims was unauthorized, when Hostinger/dLocal say they have no record of the payment but Lemon points to prior consumption history at that merchant and normal cashback conversion?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Principle 1 — Protección del consumidor.
2. Principle 2 — Información (clara, veraz, completa).
3. Principle 3 — Transparencia (no inducir a error).
4. Principle 4 — Buena fe.
5. Principle 5 — In dubio pro consumidor (tiebreaker).
6. Section B — T&C clauses must be compatible with Section A; non-compatible clauses do not control.
7. Burden allocation under consumer-protection logic: once user evidences a debit they did not authorise AND merchant/processor denies receipt of funds, operator must produce concrete substantiation for refusing the chargeback.

## Burden of proof
User must show the disputed debit and a reasonable basis to question authorisation. Lemon, as the operator denying a chargeback, must show with concrete evidence that the transaction was genuinely authorised by the user or that the chargeback rules (clearly communicated) were not met.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon transaction screenshot showing ARS 15,493.67 debit to "Dlocal *Hostinger Com" 06/10/2023 | Screenshot | Not rebutted | High — establishes the debit |
| User | Email from "Justin" (Hostinger/dLocal customer service): "Este pago no ha sido recibido por las cuentas de dLocal... no hay ninguna transacción en dlocal asociada a ese pago" | Screenshot of email | Not rebutted | High — third-party processor denies receipt |
| User | Second email from "Fabricio" (Hostinger CS) confirming "No existe ninguna transacción en dLocal asociada con ese pago" | Screenshot of email | Not rebutted | High — corroborates |
| User | Lemon's denial email from "Meli" citing T&C chargeback conditions without specifics | Screenshot | Not rebutted | Medium — shows reasoning offered |
| Lemon | Bare assertion: user had prior consumption at the merchant; no later rejections; BTC cashback was converted same day in line with platform procedures | Narrative only | No documentary support | Low — unsubstantiated |

Immaterial:
- General reference to "right of direct action against any insurer" — not developed and not necessary to resolve the dispute.

## Application
- **Protección:** User produced concrete third-party evidence that the supposed beneficiary (dLocal/Hostinger) never received the funds. A consumer-protective reading places the onus on Lemon to substantiate authorisation, which it has not done.
- **Información:** Lemon's denial email points the user to T&Cs in the app but does not state which specific chargeback condition failed, nor does it engage with the dLocal denial. Information provided is not clear or complete.
- **Transparencia:** The denial communication is generic; it does not transparently explain the factual basis (e.g., device, IP, 3DS authentication, merchant settlement evidence). The descargo merely invokes "previous consumptions" and "cashback conversion" as proxies for legitimacy without supporting documents.
- **Buena fe:** Lemon's reliance on indirect behavioural proxies, while ignoring an explicit denial from the named merchant/processor, is not a good-faith resolution of a chargeback claim.
- **In dubio:** Not required as tiebreaker — the evidentiary balance already favours the user. If invoked, it would reinforce the same outcome.
- **Educación / No discriminación:** N/A.
- **T&C compatibility (Section B):** Lemon never quotes the specific chargeback clause relied upon. A blanket "no cumple con nuestras condiciones de contracargo," used to defeat a documented unauthorised-debit claim where the merchant denies receipt, would be incompatible with Principles 1–4 and would not control.

## Jurisdiction / Morality / Validity
Properly before Kleros "Blockchain No Técnica"; well-formed consumer dispute; sufficient evidence to decide.

## Schelling-Point check
A reasonable juror would note that (a) the debit is documented, (b) the named merchant and its payment processor both deny receipt of the funds, and (c) Lemon's response offers only unsubstantiated behavioural inferences. The convergent answer is to favour the user.

## Bias audit
Checked for over-crediting consumer narrative: the user's claim is corroborated by two independent emails from Hostinger CS, not just self-assertion. Checked for under-crediting Lemon: even granting their behavioural inferences, they fail to address why dLocal has no record of the payment, which is the central fact. No bias adjustment needed.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

The user documented an ARS 15,493.67 debit on his Lemon card to "Dlocal *Hostinger Com" on 06/10/2023 and produced two unrebutted emails from Hostinger's customer service stating that dLocal has no transaction record matching that payment. Under Principles 1 (Protección) and 2 (Información), this third-party denial shifts the evidentiary burden to Lemon to substantiate that the charge was genuinely authorised and properly settled. Lemon's descargo offers only behavioural proxies — prior consumption at the merchant and same-day cashback conversion — without any settlement record, authentication log, or specific T&C clause. That is not concrete substantiation.

Lemon's denial email (Principle 3 — Transparencia) points the user to T&Cs in the app but does not identify which chargeback condition was unmet or address the dLocal denial. A generic "no cumple con nuestras condiciones de contracargo" used to defeat a documented unauthorised-debit claim, without compatibility analysis against Section A, cannot control under Section B. Principle 4 (Buena fe) is also strained when an operator ignores the merchant's own statement that it never received the money.

In dubio pro consumidor (Principle 5) is not needed as a tiebreaker — the evidence already preponderates for the user — but it would reinforce the same outcome. Vote: Favor User.
