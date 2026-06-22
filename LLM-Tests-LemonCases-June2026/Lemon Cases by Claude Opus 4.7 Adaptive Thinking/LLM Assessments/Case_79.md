# Case 79 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon "Programa de Referidos" (referral commission)
**Amount in dispute:** Not stated (referral commission, unspecified value)
**Question:** Is Lemon required to pay the user a referral commission for allegedly inviting "Arístides Reynoso" when Lemon's internal records show no such referral linked to the user's lemontag, and the user's only evidence is a WhatsApp invitation containing a Worldcoin link (not a Lemon link)?

## Options
- Favor User — Lemon must pay the referral commission.
- Favor Lemon — No commission owed; referral conditions not met.
- Refuse to Arbitrate — Use only on jurisdiction / morality / validity failure.

## Governing rules
1. **Política — Sección A, Principio 2 (Información):** the offer as presented governs the bargain — promotional terms must be clear and complete.
2. **Política — Sección A, Principio 3 (Transparencia):** Lemon must disclose criteria for promotional rewards clearly; hidden gating is a likely violation.
3. **Política — Sección A, Principio 4 (Buena fe):** both parties must act in good faith — the provider must honour commitments, the user must comply with stated requirements.
4. **Política — Sección A, Principio 1 (Protección):** consumer protection requires Lemon not to weaponise undisclosed criteria.
5. **Política — Sección A, Principio 5 (In dubio pro consumidor):** TIEBREAKER only when, after evidence and policy application, the case remains genuinely balanced.
6. **Política — Sección B:** T&Cs are valid only insofar as they do not contravene Sección A.
7. **General Kleros rule:** burden of proof on the claimant; unrebutted evidence is presumed genuine.

## Burden of proof
The user is the claimant — bears the burden of showing, on the balance of evidence, that the conditions of the referral promotion were satisfied (i.e., that the invited person actually onboarded onto Lemon via the user's referral code/lemontag).

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | WhatsApp screenshot showing invitation sent on 3 Oct 2024 to "Arístides Reynoso" with link `https://worldcoin.org/join/CI79EA5` | Secondary (screenshot) | Implicitly — link is to **Worldcoin**, not Lemon | High (against user) |
| User | Reference to code "CI79EA5" as a Lemon code | Assertion | Rebutted — the screenshot itself shows the code is the **Worldcoin** join code | Low |
| Lemon | Screenshot of internal admin panel confirming user's lemontag is `luiscuencacardenas` (account ID 2745961, Peru, active) | Primary (internal record) | No | High |
| Lemon | Screenshot of internal SQL query "[CX] Validación referidos Perú Version 2" filtering by Lemontag Referente = `luiscuencacardenas` returning "¡Sin resultados! / Mostrando 0 filas" | Primary (internal record) | No | High |
| Lemon | Statement that referred user "Arístides Reynoso" is not registered against the user's lemontag and T&C criteria are not met | Assertion supported by the two screenshots above | No | High |

Immaterial:
- Phone-call entries between user and Arístides Reynoso on 3 and 5 October — they evidence contact, not Lemon onboarding.

## Application
- **Protección:** No protective failure by Lemon — the rule denies a reward where the verifiable condition (referee registers under the referrer's lemontag) is not met. Withholding an unearned reward is not a protection breach.
- **Información:** The Lemon referral programme, as referenced by both parties, requires the invitee to register/onboard via the referrer's link/lemontag. The user does not allege any hidden term; he simply asserts he invited someone. No "Información" gap is shown.
- **Transparencia:** Lemon transparently produced the internal verification step (lemontag check + SQL query result). No hidden criterion is being applied — the criterion is the obvious one: the invitee must actually appear as a referido associated with the referrer's lemontag. The user has not pointed to any opaque clause.
- **Buena fe:** Lemon acted in good faith by performing and disclosing the verification. The user's own evidence undermines his case — the link in his WhatsApp screenshot points to `worldcoin.org/join/CI79EA5`, i.e., the invitation was a **Worldcoin** invitation, not a Lemon one. Whether by confusion or by deliberate framing, the user has shown no Lemon-side onboarding act by the invitee.
- **In dubio:** Does not engage. The user's own primary exhibit contradicts his claim and Lemon's internal database is unrebutted. The case is not in genuine doubt.
- **Educación:** Not engaged — user understood the concept of a referral programme.
- **No discriminación:** Not engaged — no group-based differential treatment alleged.
- **T&C compatibility (Sección B):** Lemon relies on the standard T&C requirement that the referee actually register via the referrer — a condition that is intrinsic to any referral programme and fully compatible with Sección A.

## Jurisdiction / Morality / Validity
Jurisdiction (Blockchain No Técnica / consumer promotion dispute under Lemon's Política): pass. Morality: no enumerated immoral conduct by either party. Validity: question is well-formed and answerable. No RtA trigger.

## Schelling-Point check
A panel of diligent, policy-literate jurors will notice (1) Lemon's unrebutted internal database shows zero referidos under the user's lemontag, and (2) the user's only "proof" of having invited Reynoso is a screenshot of a **Worldcoin** invitation link — a different programme entirely. The focal answer is Favor Lemon.

## Bias audit
No reliance on party identity, wealth, or rhetorical polish. The dispositive facts are the user's own screenshot (showing a Worldcoin, not Lemon, link) and Lemon's internal SQL screenshot. No sympathy-based weighting applied.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

Under Lemon's Política, the user (as claimant) carries the burden of showing that the conditions of the referral promotion were satisfied — namely, that an invitee actually onboarded to Lemon under the user's lemontag. Lemon submitted two internal records: an admin-panel screenshot confirming the user's lemontag is `luiscuencacardenas`, and a SQL validation query filtering referidos by that lemontag, which returned zero rows. Those exhibits are primary internal records, are unrebutted, and are therefore presumed genuine.

The user's own exhibit undermines his claim. The WhatsApp screenshot he relies on shows that the invitation sent to Arístides Reynoso on 3 October 2024 was to **Worldcoin** (`https://worldcoin.org/join/CI79EA5`), not to Lemon. The string "CI79EA5" is a Worldcoin join code, not a Lemon referral identifier. The user has not produced any evidence that Reynoso ever onboarded onto Lemon, let alone under his lemontag. Phone-call entries are immaterial — they show contact, not platform registration.

Applying Sección A: Información and Transparencia are not breached because Lemon is enforcing the obvious, intrinsic condition of any referral programme (the referee must actually register through the referrer). Buena fe runs against the user, whose primary exhibit contradicts the claim. In dubio pro consumidor does not engage because the case is not in genuine doubt. Sección B is satisfied because the T&C requirement is fully compatible with Sección A. The vote is **Favor Lemon**.

Case 79 | VOTE: Favor Lemon | CONFIDENCE: high | User's own WhatsApp shows a Worldcoin invite link, not Lemon; Lemon's unrebutted internal DB shows zero referidos under user's lemontag.
