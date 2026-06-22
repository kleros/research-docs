# Case 93 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Receipt of an inbound European bank transfer (EUR via BBVA / SEPA) into a Lemon CVU (Argentine peso virtual account). The user invokes Lemon's "Euros — Recibí USDC" mini-app product as evidence the platform supports EUR inflows.
**Amount in dispute:** EUR 50,00 (sent 21/03/2025 from Jonathan Stiven Lemus, BBVA, account *9803, beneficiary "Kevin Damián Arancio").
**Question:** Should Lemon credit (or otherwise indemnify) a EUR 50 SEPA transfer that the sender directed to the user's ARS-only CVU, rather than to the dedicated EUR virtual account (NOAH-provided, requires onboarding and T&C acceptance) that powers Lemon's "Euros → USDC" product?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Section A — Protección al consumidor** — Lemon must avoid undue economic harm to users from foreseeable operational risks within its control.
2. **Section A — Información** — Lemon must communicate the offer "as presented"; hidden limits on a product are a likely violation.
3. **Section A — Transparencia** — Material conditions, including which account types accept which currencies, must be visible to a reasonable user.
4. **Section A — Buena fe** — Both parties must act honestly; misrepresentation by either side weighs against them.
5. **Section A — In dubio pro consumidor** — Tiebreaker only, used when application of rules 1–4 leaves genuine equipoise.
6. **Section A — Educación financiera** — Lemon must orient users about how its products work, especially those with technical preconditions.
7. **Section A — No discriminación** — Not engaged here.
8. **Section B — Compatibility** — Lemon T&Cs override only insofar as they do not contradict Section A. Catch-all immunity does not override Section A.

## Burden of proof
The user is the claimant seeking a change from the default state (no credit). The user must show that Lemon's offer, as presented, reasonably promised that the EUR 50 SEPA transfer would land in his ARS CVU and be credited, or that Lemon otherwise retained the funds.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon home-screen screenshot showing balance ARS 0,00 and "Mini Apps → Euros — Recibí USDC" tile | Primary (own app) | No | Medium — proves the EUR→USDC product exists in the app, but does not show any EUR being received to a CVU |
| User | Narrative: depósito de EUR 50 el 20/03, fondos no acreditados, soporte sin respuesta concreta | Secondary (assertion) | Partly rebutted by Lemon's technical explanation | Low–Medium |
| Lemon | BBVA transfer screenshot (21/03/2025, EUR 50,00, BIC LENAFRPPXXX, beneficiary "Kevin Damian Arancio", ordenante Jonathan Stiven Lemus) | Primary (sender's bank receipt) | No | High — establishes the transfer was a EUR SEPA wire, sent from an EU bank account |
| Lemon | App flow screenshots: "Ingresá dinero del exterior y recibí cryptodólar" → "Depositá Euros y recibí USDC" → step requiring opening a **virtual account** + T&C acceptance + NOAH provider + 4 USDC fee + 1.5% commission | Primary (own product UX) | No | High — shows EUR receipt is a separately-onboarded product, not a default CVU capability |
| Lemon | Statement that Argentine CVUs only accept ARS and that EUR SEPA into an ARS CVU is rejected/non-liquidated at the banking-system level | Secondary (explanation, consistent with public Argentine banking rules) | Not rebutted | High |

Immaterial:
- User's emotional language about distress and urgency — does not bear on whether the offer included EUR-to-CVU receipt.
- Exact date discrepancy (user says 20/03, BBVA receipt says 21/03) — immaterial; same operation.

## Application
- **Protección:** The economic loss exists, but its proximate cause is the sender directing a EUR SEPA wire to a CVU that does not accept EUR. Lemon never received nor retained the funds; the remedy lies with BBVA via sender-initiated recall.
- **Información / Transparencia:** The offer "as presented" in the app (Lemon's own screenshots, unrebutted) does **not** advertise direct EUR receipt into the CVU. It advertises a distinct "Depositá Euros y recibí USDC" product that requires (a) opening a separate virtual EUR account, (b) accepting T&Cs, (c) NOAH as provider, (d) paying a 4 USDC onboarding fee and a 1.5% commission. The user's own screenshot only shows the **tile** to that product, not an active onboarded EUR account. No hidden limit — the limit is the headline of the product.
- **Buena fe:** No bad faith on Lemon's side is shown. The user appears to have honestly misunderstood the product. Sender used an EU bank wire to a CVU — an end-user error, not a Lemon-induced one.
- **In dubio pro consumidor:** Not triggered. The rules apply cleanly; there is no genuine equipoise to break.
- **Educación financiera:** The in-app flow explicitly educates: separate account, conversion via NOAH, fees, simulate-deposit step. Lemon meets this duty on the face of its screenshots.
- **No discriminación:** Not engaged.
- **T&C compatibility:** The product T&Cs (NOAH-provided EUR account, fees, onboarding) are consistent with Section A — they are disclosed up-front in the same flow that creates the account.

Combined: The user has not shown that Lemon's offer, as presented, promised EUR receipt to an ARS CVU. The funds never entered Lemon's ecosystem. The correct remedy path — bank-level SEPA recall by the sender — is identified by Lemon. Rules 1–4 and 6 are satisfied by Lemon; rule 5 is not triggered.

## Jurisdiction / Morality / Validity
Pass. Consumer dispute over a fintech product is within "Blockchain No Técnica". No morality clause triggered. Question is well-formed and answerable on the materials.

## Schelling-Point check
A panel of diligent jurors reading the same two descargos would converge on Favor Lemon: the unrebutted BBVA receipt shows an EU-bank EUR SEPA wire to an ARS CVU; Lemon's own flow screenshots show the EUR product is a distinct onboarded service. The user provides nothing showing he ever onboarded that product, and no support-chat confirmation that the funds were on Lemon's books. Literal reading of the offer "as presented" defeats the claim.

## Bias audit
No reliance on party identity, sympathy, or rhetorical polish. The user's distress is acknowledged but immaterial. Decision rests on documentary evidence and product-flow screenshots from both sides.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
Under Section A of the Política (Información, Transparencia, Educación), the offer "as presented" governs. Lemon's own app flow — unrebutted — shows that receiving EUR from an EU bank is a separate product (NOAH-provided EUR virtual account → conversion to USDC), gated by explicit onboarding, T&C acceptance, a 4 USDC fee, and a 1.5% commission. The user's screenshot establishes only that the "Euros — Recibí USDC" mini-app tile exists; it does not show that he ever opened the EUR virtual account, accepted the T&Cs, or held a EUR receiving instrument. Without that onboarding, his CVU is an ARS-only account, as Lemon (and Argentine banking rules) state.

The BBVA receipt submitted by Lemon, also unrebutted, shows a EUR 50 SEPA wire from an EU bank to the user's ARS CVU. The Argentine banking system does not liquidate inbound foreign-currency wires into ARS CVUs, so Lemon never received or retained the funds. Protección al consumidor cannot oblige Lemon to credit money that did not enter its ecosystem, and Buena fe is satisfied by Lemon's identification of the correct remedy: a SEPA recall initiated by the sender through BBVA.

The In dubio pro consumidor tiebreaker is not engaged because Sections A and B yield a clear application. Section B T&Cs (NOAH product conditions) are compatible with Section A — they are disclosed in the same in-app flow that creates the account. Vote: Favor Lemon.

Case 93 | VOTE: Favor Lemon | CONFIDENCE: high | EUR SEPA wire sent to ARS-only CVU; Lemon never received funds; EUR→USDC product requires separate NOAH onboarding user never completed; remedy is BBVA recall.
