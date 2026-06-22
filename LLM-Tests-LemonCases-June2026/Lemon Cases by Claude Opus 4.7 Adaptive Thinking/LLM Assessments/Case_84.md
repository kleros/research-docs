# Case 84 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** ARS peer-to-peer withdrawal (CBU transfer) from Lemon Cash, 18 Dec 2024
**Amount in dispute:** ARS 20,000
**Question:** Must Lemon refund ARS 20,000 that the user sent to a CBU whose account holder turned out not to be the intended recipient (correct first name, wrong surname)?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. Sección A — Política de Defensa del Consumidor of Lemon: Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. Sección B — Lemon T&Cs / Digifin T&Cs §3(e): the user is exclusively responsible for the accuracy of recipient data (alias / CBU / name) before confirming a transfer.
3. Operational fact: bank/CBU transfers executed on Argentine rails (COELSA) are irreversible by the sending institution once credited.
4. Burden of proof: on the user, who is asserting a platform failure that would justify a refund.

## Burden of proof
On the User. They must show that Lemon — not the user — caused the funds to go to the wrong account, or that Lemon's interface concealed information that would have let them catch the error.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of completed ARS 20,000 withdrawal, status "Completo", recipient "Haydee Silva", CBU 0070012230004021399377, Trx ID 18ddcbb3-fba5-462a-8ca1-594aa11738fe, 18/12/2024 13:51 | Primary (own app) | No | High |
| User | Assertion that intended recipient confirmed they did not receive the funds and the surname is not theirs | Secondary (uncorroborated party statement) | Implicitly disputed | Low |
| Lemon | Back-office record of same Trx ID showing the transfer was user-initiated and completed | Primary | No | High |
| Lemon | Composite screenshot of Lemon's "Enviar ARS" flow showing a two-step confirmation modal ("Confirmá tu envío") displaying recipient name, bank and CBU before "Deslizá para confirmar" | Primary (UI evidence) | No | High |
| Lemon | Reference to Digifin T&Cs §3(e) — user responsibility for recipient data | Documentary | No | Medium |

Immaterial:
- User's appeal to "Principio de Protección al Consumidor" and "Principio de Buena Fe" as freestanding entitlements to a refund — rhetorical, no evidence of platform error attached.

## Application
- **Protección:** The screenshot shows Lemon executed exactly the CBU the user supplied. The economic loss flowed from the user's own input, not from a Lemon-side error or omission. No protection failure.
- **Información:** Lemon's confirmation modal displays recipient name, bank and CBU prior to confirmation. The user had the recipient surname ("Haydee Silva") visible on screen before sliding to confirm. The duty to disclose was met.
- **Transparencia:** The two-step "Enviar ARS" → "Confirmá tu envío" flow is transparent. The receipt also discloses recipient name, CBU, COELSA ID and Trx ID.
- **Buena fe:** Lemon acted on the user's own instruction and now correctly states the CBU rail does not allow it to unilaterally reverse a completed inter-bank transfer. No bad faith.
- **In dubio pro consumidor:** Tiebreaker only. Here the evidence is one-sided — the user supplied the CBU, the confirmation screen displayed the recipient name and bank, the transfer completed to that CBU. No genuine doubt to break.
- **Educación:** Not engaged.
- **No discriminación:** Not engaged.
- **T&C compatibility with Sección A:** Digifin §3(e) (user responsibility for recipient data) is compatible with Información and Transparencia because Lemon does display the recipient name in the confirmation modal — the user is given the chance to catch a name mismatch before confirming. The T&C is not used as a catch-all immunity; it is being applied consistently with the information actually shown.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt; no morality flag; question is well-formed.

## Schelling-Point check
This is the recurring "wrong-CBU, user-entered, irreversible bank-rail transfer" pattern in the Lemon docket. A diligent panel converges on Favor Lemon: the user controls the CBU input, the confirmation screen shows the recipient name, and the rail does not permit unilateral reversal by the sending PSP. The user's recourse is the receiving bank, not Lemon.

## Bias audit
The user is sympathetic — ARS 20,000 lost in good faith and an inability to contact the unintended recipient. Sympathy is not a Sección A principle. Removing the sympathy lens does not change the outcome: no evidence of platform-side error, and the irreversibility of the CBU transfer is a feature of the Argentine banking rail, not a Lemon design choice that could be overridden by arbitration.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2-3 short paragraphs, English)

The user initiated an ARS 20,000 withdrawal on 18 December 2024 to CBU 0070012230004021399377, account holder "Haydee Silva", and the transfer settled successfully (Trx ID 18ddcbb3-fba5-462a-8ca1-594aa11738fe). The user now says the surname is not that of the person they meant to pay and asks Lemon to refund. The user's evidence is a single receipt showing the transfer was completed exactly as instructed. There is no evidence of any error by Lemon, of a hidden field, of a UI bug, or of an account compromise.

Lemon shows that the standard "Enviar ARS" flow displays the recipient's name, bank and CBU inside a "Confirmá tu envío" modal before the user slides to confirm. Under Sección A, the duties of Información and Transparencia were met — the recipient surname "Haydee Silva" was visible to the user prior to confirmation. Digifin T&Cs §3(e), placing responsibility for the accuracy of recipient data on the user, is compatible with Sección A in this fact pattern because the platform did surface the very information the user needed to catch the mismatch. CBU transfers on the COELSA rail are irreversible by the sending PSP once credited; Lemon cannot claw back funds sitting in another bank's customer account. The In dubio pro consumidor principle is a tiebreaker, and there is no genuine tie here — the evidence runs one way.

For these reasons, the vote is Favor Lemon. The user's recourse, as Lemon notes, is with the receiving bank or directly with the unintended recipient, not with the sending platform.
