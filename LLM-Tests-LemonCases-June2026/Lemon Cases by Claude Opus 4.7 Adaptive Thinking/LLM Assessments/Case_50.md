# Case 50 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon "Pago de Servicios" — bill payment of an external Visa credit-card statement via the Pago Mis Cuentas (PMC) / TAPI rails.
**Amount in dispute:** ARS $40,000.00 (single Visa credit-card payment, 12-Jun-2024).
**Question:** Is Lemon liable to refund / re-process a $40,000 Visa credit-card payment that the user says "never applied" to her card, when Lemon's payment-rails provider issued a complete settlement ticket (authorisation code, transaction id, control number)?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Protección** (Section A.1) — Lemon must protect consumer interests, but only within the scope of what Lemon actually offers and controls.
2. **Información** (A.2) — Truthful, sufficient, detailed information about the service "as presented".
3. **Transparencia** (A.3) — Hidden limits / undisclosed risks weigh against Lemon.
4. **Buena fe** (A.4) — Honest, non-evasive handling of the claim.
5. **In dubio pro consumidor** (A.5) — Tiebreaker ONLY when, after full evidence weighing, the case is genuinely 50/50.
6. **Educación** (A.6) — User must be informed of how the service works.
7. **No discriminación** (A.7) — Not in play here.
8. **Section B — T&C compatibility** — Lemon's T&Cs cannot override Section A; but scope-of-service definitions (what the product actually does) do govern.
9. **Operational principle:** in a bill-payment ("Pago de Servicios") product, the merchant of record for *application of funds to the cardholder's account* is the receiving entity (Visa / the card issuer), not the rails operator (Lemon/TAPI/PMC) — once the funds are settled with a valid authorisation code, Lemon's contractual obligation is discharged.

## Burden of proof
On the user (claimant seeking deviation from the default state, i.e. that a confirmed, ticket-bearing payment is final). She must show either (i) Lemon failed to actually send/settle the funds, or (ii) Lemon's app misrepresented something material about how the service works.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | In-app confirmation screen: 12/6/2024 11:57:26, VISA, $40,000, Identificador 4720390001000450, Control 2961, Trans. 820424748800 | Secondary (app screenshot) | No (matches Lemon's record) | Medium — proves the *user side* of the transaction was completed in the app |
| Lemon | TAPI/PMC settlement ticket: identical date/time, identical empresa VISA, identical importe $40,000, identical Identificador 4720390001000450, identical Control 2961, identical Transacción 820424748800, **plus** Sucursal Virtual 5892448978100200002, **Código de Autorización 59864503**, Forma de Pago "Efectivo", AGENTE OFICIAL TAPI | Primary (rails-operator settlement record) | No (user does not dispute it) | High — independent confirmation that the funds were transmitted to and accepted by the Visa rails with a valid authorisation code |
| User | Assertion that bank statement shows no payment to the card | Secondary (uncorroborated narrative) | Implicitly rebutted by Lemon (which points the user to Visa with the authorisation code) | Low — no copy of the bank/card statement is attached |

Immaterial:
- Emotional impact on user's credit history — relevant context but does not change the legal scope of Lemon's service.

## Application
- **Protección:** Lemon protected the user by routing the payment through a regulated rails (PMC/TAPI) and producing a full audit trail (control number + authorisation code). No protection failure shown.
- **Información:** "Pago de Servicios" is, on its face, a bill-payment funnel — the user pays Lemon/TAPI, who transmits to Visa. Nothing in the user's submission alleges that Lemon described this product as a direct credit-card-account credit by Lemon itself.
- **Transparencia:** No hidden limit or undisclosed risk has been pleaded. Lemon disclosed the authorisation code and pointed the user to the receiving entity — that is the opposite of hiding facts.
- **Buena fe:** Lemon investigated, produced the rails-operator ticket with auth code, and gave the user the precise mechanism (the auth code) by which Visa can locate the payment. That is good faith.
- **In dubio pro consumidor:** Not triggered — the evidence is one-sided. Lemon produced a primary settlement record; the user produced no rebuttal (no bank statement, no Visa response saying "we never received it", no proof that the auth code is fake).
- **Educación:** Lemon educates the user in its descargo about who holds responsibility after settlement (the receiving entity). No prior deception is alleged.
- **No discriminación:** Not in play.
- **T&C compatibility:** Standard Pago de Servicios scope — Lemon's responsibility ends at successful transmission to the destination entity — is compatible with Section A because it reflects the actual architecture of the service "as presented" and does not strip the user of any protection.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica — consumer-tech dispute). No morality flag. Question is well-formed and answerable from the materials.

## Schelling-Point check
A panel of diligent jurors sees: identical transaction identifiers on both sides, a valid TAPI authorisation code (59864503), no bank statement from the user, and a service that is by design a bill-payment pass-through to Visa. The obvious, literal reading is that Lemon performed its part; any non-application of funds is between the user and Visa. This is the Schelling point.

## Bias audit
Sympathy for a consumer facing credit-history damage is real but immaterial — the question is whether Lemon breached its scope. The user's brief is short and unsupported beyond a screenshot that Lemon's own evidence actually corroborates. Removing sympathy, the answer does not change.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Under Section A of the Política de Defensa al Consumidor, Lemon's obligations of Protección, Información, Transparencia and Buena fe are scoped to the service "as presented". The product at issue is "Pago de Servicios" — a bill-payment funnel routed through PMC/TAPI to the receiving entity (Visa). Lemon's duty under that product is to transmit funds and produce a verifiable settlement record; application of funds to the cardholder's internal account is the receiving entity's responsibility.

The material evidence is one-sided. Lemon produced a primary settlement ticket from its rails partner TAPI with a complete chain of identifiers — Control 2961, Transacción 820424748800, Identificador 4720390001000450, and crucially Código de Autorización 59864503 — and these identifiers match the user's own in-app confirmation screen exactly. The user's only counter-evidence is an unsupported assertion that her bank statement shows no payment; no statement, no Visa correspondence, and no rebuttal of the authorisation code is provided. Under the standard rule that unrebutted evidence is presumed genuine, the settlement is treated as effected.

In dubio pro consumidor is a tiebreaker and is not engaged here, because the evidence is not in equipoise. No hidden limit, no misrepresentation, and no bad-faith handling has been shown — on the contrary, Lemon's descargo gives the user the exact authorisation code Visa needs to trace the payment, which is the cooperative, good-faith response. The vote is **Favor Lemon**.
