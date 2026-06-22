# Case 99 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** ARS withdrawal (transferencia bancaria saliente) via Lemon / Digifin
**Amount in dispute:** ARS 50,000
**Question:** Is Lemon liable to credit / refund the user for a 50,000 ARS withdrawal that the user says did not arrive at the destination bank account after 14 days, when Lemon's records show the transfer was completed and a Coelsa ID was generated?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Sección A — Principio de Protección al Consumidor.** Lemon must safeguard users' economic interests in operations performed on its platform.
2. **Sección A — Información.** Information about the transaction (status, identifiers, destination) must be clear, timely and accessible.
3. **Sección A — Transparencia.** The platform must transparently disclose how the operation was executed.
4. **Sección A — Buena Fe.** Both parties must act in good faith.
5. **Sección A — In dubio pro consumidor.** Tiebreaker only — applies when, after weighing evidence, real residual doubt remains.
6. **Sección B — T&Cs vs Sección A.** T&Cs apply where not in conflict with Sección A. Clause 3.7 T&C (cited by Lemon): once a withdrawal is confirmed, the user grants Lemon (acting as payment-service provider via Digifin) an irrevocable mandate to execute the instruction; outbound transfers leaving the Lemon ecosystem cannot be reversed.
7. **Burden of proof.** The party seeking to alter the default state (here: the user, who wants Lemon to be liable for a completed external transfer) bears the burden of showing Lemon's execution or disclosure was defective.

## Burden of proof
On the user to show that (a) Lemon failed to execute according to the instructions given, or (b) Lemon misled the user about transaction status, or (c) Lemon hid material limits. The default — once a confirmed irrevocable mandate has been executed correctly, the platform is not responsible for downstream credit by the receiving bank — favours Lemon.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | App screenshot of the withdrawal marked "Completo" with CBU 0110314230031419691151, recipient "Cordoba Hector Enrique", Coelsa ID 46YGOW9M8PO74J1M9EXD8J, Trx ID c0753cc8-ec6a-428c-9783-7197cd370109, dated 25/03/2025 19:54 | Primary (own app screenshot) | No | High — but proves Lemon executed, not that it failed |
| User | Assertion that funds did not arrive at destination after 14 days | Secondary (uncorroborated statement) | Not directly rebutted, but irrelevant to Lemon's liability if execution was correct | Low |
| User | Assertion that support did not reply on Hotmail/Gmail | Secondary (no screenshots / no email chain attached) | Unsubstantiated | Low |
| Lemon | Back-office VIRTUAL_WITHDRAWAL panel: status "Completada", same Trx ID, same Coelsa ID, same destination CBU, same date/time, user data (Hugo Fernando Quiroga, CUIT 20422217860, ID 2180383) | Primary | No | High |
| Lemon | Invocation of cláusula 3.7 T&C — irrevocable mandate, outbound transfers cannot be reverted | Policy citation | No | High |
| Lemon | Recommendation that user contact receiving bank with the Coelsa ID to trace the credit | Procedural advice | No | Medium |

Immaterial:
- Minor typo in user's narrative (Coelsa ID starts "4S..." in text but "46..." in the screenshot and in Lemon's back office) — both party screenshots align on 46YGOW9M8PO74J1M9EXD8J, so this is a transcription slip, not a discrepancy.
- Emotional framing about "concern" and "more than two weeks" — emotional, not probative.

## Application
- **Protección:** Lemon's economic safeguarding duty does not extend to compensating users for funds correctly transferred to a CBU the user themselves instructed. Lemon executed; the destination CBU is not a Lemon-controlled account. No protección breach.
- **Información:** Lemon discloses the Coelsa ID, transaction ID, exact date/time, destination CBU and recipient name in the user-facing app, and provides the same data in the back office. Information criterion satisfied.
- **Transparencia:** Lemon's response transparently explains the execution flow, cites the operative T&C clause, and points the user to the next step (receiving bank with the Coelsa ID). Transparencia satisfied.
- **Buena fe:** No evidence Lemon misled or delayed in bad faith. User's bare assertion that support did not respond is unsupported by any email screenshots. Buena fe not breached.
- **In dubio:** Tiebreaker — does not apply. The evidence preponderates clearly: Lemon's primary back-office record matches the user's own primary app screenshot; the operation was executed correctly to the instructed CBU. There is no residual doubt of the kind in dubio resolves.
- **Educación / No discriminación:** Not at issue.
- **T&C compatibility:** Clause 3.7 (irrevocable mandate for outbound transfers) is operational, addresses a real characteristic of bank-rail transfers (Coelsa-cleared interbank settlement is final on Lemon's side), and is not in conflict with Sección A — it does not deny Protección, only allocates responsibility once execution is correct. Compatible with Sección A.

## Jurisdiction / Morality / Validity
Subcourt correct (Blockchain No Técnica — consumer crypto-app dispute under Lemon's policy). No morality flag. Question well-formed and answerable. Pass.

## Schelling-Point check
A panel of diligent jurors reading the same materials sees: (i) two independent primary records (user's app + Lemon's back office) agreeing the transfer was executed to a user-instructed CBU, (ii) a Coelsa ID confirming the funds left Lemon's ecosystem via the interbank rail, (iii) a recognised T&C clause that aligns with the irreversible nature of bank transfers once cleared, and (iv) no evidence of a Lemon-side defect. The obvious, defensible reading is Favor Lemon. Voting otherwise would require speculating that Lemon's back office is fabricated, which is not alleged and not supported.

## Bias audit
No reliance on party identity or sympathy. The user's frustration is understandable but does not substitute for evidence that Lemon's execution or disclosure was defective. The unsubstantiated support-unresponsiveness claim was given low weight precisely because no email screenshots were produced — applying the same evidentiary standard to both sides.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Both parties produced primary evidence — the user's Lemon app screenshot and Lemon's back-office record — and the two agree on every material data point: a 50,000 ARS virtual withdrawal on 25/03/2025 at 19:54, status "Completada / Completo", Coelsa ID 46YGOW9M8PO74J1M9EXD8J, transaction ID c0753cc8-ec6a-428c-9783-7197cd370109, destined to CBU 0110314230031419691151 (recipient "Cordoba Hector Enrique"). The CBU was supplied by the user. The Coelsa ID confirms the funds entered the Argentine interbank clearing rail and left Lemon's ecosystem. Under Sección B and clause 3.7 of the T&Cs, once the user confirms a withdrawal Lemon executes an irrevocable mandate via Digifin, and this clause is compatible with Sección A because it does not negate consumer protection — it simply allocates downstream credit risk to the receiving bank, which is the technical reality of Coelsa-cleared transfers.

Measured against Sección A: Información and Transparencia are satisfied — Lemon disclosed every identifier (Coelsa ID, Trx ID, CBU, date/time, recipient) both in-app and in its response. Buena fe is not breached — the user's claim that support did not respond on Hotmail / Gmail is bare assertion, unsupported by any email or chat screenshot, so it carries low evidentiary weight under the equal-treatment standard. Protección does not require Lemon to underwrite credit failures at a destination bank when Lemon's own execution was demonstrably correct. The in-dubio tiebreaker does not engage because the record is not in equipoise — it preponderates clearly for Lemon.

The correct procedural remedy — which Lemon itself flagged — is for the user to contact the receiving bank (Banco de la Nación Argentina, per the CBU prefix 011) with the Coelsa ID to trace the credit. Vote: Favor Lemon.
