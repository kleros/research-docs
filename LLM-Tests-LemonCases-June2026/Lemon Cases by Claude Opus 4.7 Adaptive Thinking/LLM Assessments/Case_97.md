# Case 97 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Lemon Cash subcourt, Spanish)
**Promo / product at issue:** Lemon transfer dispute — unauthorized outbound ARS transfer
**Amount in dispute:** ARS 6.000,00 (transferred 03 April 2025 18:54)
**Question:** Should Lemon refund a transfer that the user claims was unauthorized?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Sección A.2 (Información) and A.3 (Transparencia):** Lemon must inform users about how account security and unauthorized-use claims are handled. Operative limits must not be hidden.
2. **Política Sección A.4 (Buena fe):** Both parties must act in good faith. Inconsistent or shifting factual narratives by either side cut against good faith.
3. **Política Sección A.1 (Protección):** Users are protected against losses caused by Lemon's failures — but not against losses caused by user-side error or user-side custody failures.
4. **Política Sección A.5 (In dubio pro consumidor):** Tiebreaker only — applied if genuine doubt remains after policy/evidence analysis.
5. **Sección B — T&Cs vs Sección A:** T&Cs apply where compatible with Sección A. T&C clause 3.7 (user is the exclusive responsible party for operations performed in their account; user must immediately and verifiably notify any unauthorized access) is compatible with Sección A's protección/buena-fe scheme — it allocates custody risk to the user when there is no evidence of Lemon-side compromise.
6. **General Court morality clause:** Vote must not favour a party engaged in perjury, including materially inconsistent or fabricated narratives.

## Burden of proof
The user is the claimant seeking a change to the default state (the executed transfer). The user must show, to a reasonable standard, either (a) Lemon-side failure of protección/información/transparencia, or (b) facts that, under buena fe and the T&Cs as filtered by Sección A, entitle them to reversal. Unrebutted evidence is presumed genuine.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Written claim: 5-year-old daughter accidentally pressed "confirm payment" inside the App Store, causing an unintended purchase | Secondary (party assertion) | Implicitly rebutted by physical impossibility — see below | Low |
| User | Lemon transfer receipt: ARS 6.000 outbound P2P transfer to "Lucas Miguel Benitez" (CUIT 20390356308), Banco Claro Pay, motivo "Varios", with COELSA ID and transaction ID | Primary (Lemon-generated receipt) | Not rebutted | High |
| Lemon | Written response: characterises the user's claim as a "lost laptop + open session" scenario; cites T&C 3.7; states user refused to file a police/criminal report | Secondary (party assertion) | Inconsistent with user's actual claim (App Store accidental tap) — see below | Low |
| Lemon | Screenshot of support-chat with user, captioned "esta es la conversación con soporte, donde indica que no va a hacer la denuncia" | Secondary (illegible at provided resolution) | Not effectively rebutted, but content unreadable | Low |

Immaterial:
- User's emotional framing of the transaction as "no autorizada" — restates the claim, does not evidence it.
- Lemon's general assertion that no system breach was detected — boilerplate, no log excerpt attached.

## Application
- **Protección (A.1):** The receipt shows a P2P COELSA transfer to a named third-party CUIT — this is not an "App Store" purchase and cannot have been triggered by a single accidental tap on an in-app purchase confirmation. Executing a Lemon outbound transfer to a new beneficiary requires entering an alias/CBU, an amount, a motivo, and confirming — multi-step flow inconsistent with a 5-year-old's stray tap. No evidence of Lemon-side custody or system failure. Protección not engaged against Lemon.
- **Información / Transparencia (A.2, A.3):** No promotional offer is at issue; this is a standard P2P transfer. The "Offer As Presented" doctrine does not apply. T&C 3.7 (user responsibility for account operations) is a standard custody clause and is not a hidden limit. No información/transparencia violation by Lemon shown.
- **Buena fe (A.4):** The user's narrative (child accidentally pressed App Store payment button) is materially incompatible with the user's own primary evidence (a P2P bank transfer to a named beneficiary at Claro Pay). Lemon's narrative (lost laptop, open session) is also incompatible with the user's stated facts, suggesting Lemon either confused this case with another or addressed an earlier version of the user's complaint that differs from the current submission. Both sides show buena-fe weaknesses, but the user — as claimant — carries the burden. The internal inconsistency of the user's account is decisive against the user under buena fe.
- **In dubio pro consumidor (A.5):** Tiebreaker. There is no genuine tie — the user's primary evidence rebuts the user's own narrative. Tiebreaker not reached.
- **Educación / No discriminación (A.6, A.7):** Not implicated.
- **T&C compatibility (Sección B):** T&C 3.7 is compatible with Sección A in this fact-pattern. The transfer was executed from an authenticated session to a specified third-party beneficiary; the user shows no Lemon-side compromise. T&C 3.7 properly allocates responsibility to the user.

## Jurisdiction / Morality / Validity
Jurisdiction proper (Blockchain No Técnica / Lemon subcourt). Question is well-formed and answerable. The user's narrative is internally inconsistent with their own evidence, which raises a soft perjury concern but is more parsimoniously explained as a shifting or inaccurate account; not strong enough to trigger the morality clause toward RtA, but sufficient to defeat the claim on burden of proof.

## Schelling-Point check
A diligent panel reading the user's submission alongside the transfer receipt will immediately note that an outbound P2P transfer with an entered CUIT/alias/amount/motivo cannot be produced by a single accidental in-app tap by a 5-year-old. The receipt — produced by the user themselves — defeats the user's own theory of the case. The obvious, literal reading favours Lemon. This is the focal answer.

## Bias audit
Sympathy bias (child involvement) does not apply once the receipt is read against the narrative. I have not relied on Lemon's lost-laptop framing — it is responsive to a different claim and was discounted. Conclusion rests on the user's own primary evidence and the user's burden.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (English)

The user's submitted narrative is that their 5-year-old daughter accidentally pressed a payment-confirmation button inside the App Store, producing an unauthorized charge. The user's own primary evidence — the Lemon transfer receipt — shows something materially different: an ARS 6,000 outbound peer-to-peer transfer to a named third-party beneficiary ("Lucas Miguel Benitez", CUIT 20390356308) routed to Banco Claro Pay via COELSA, with a "motivo" field populated. Executing this kind of transfer in Lemon requires entering or selecting a beneficiary, inputting an amount, populating the motive, and confirming. It is not producible by a single accidental tap on an App Store purchase prompt. The user's primary evidence therefore rebuts the user's own theory of the case.

Under Política Sección A, the user bears the burden as claimant. No protección, información, or transparencia violation by Lemon is shown: no hidden limit, no failed offer, no system compromise. T&C clause 3.7 — allocating responsibility for authenticated-session operations to the user — is compatible with Sección A on these facts. Buena fe cuts against the user given the internal inconsistency between narrative and receipt. The in-dubio tiebreaker (A.5) is not reached because the inconsistency removes genuine doubt.

Lemon's own response addresses a different scenario (a lost laptop with an open session) that does not match the user's submission — likely a templated or misfiled response. That weakness in Lemon's pleading does not, however, relieve the user of the burden of proof, which the user has not met on their own materials. The vote is Favor Lemon.

---

Case 97 | VOTE: Favor Lemon | CONFIDENCE: medium | User's own transfer receipt (P2P to named CUIT via Claro Pay) is materially incompatible with their narrative of an accidental App Store tap by a 5-year-old; burden unmet.
