# Case 31 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Inbound ARS bank transfer (DEBIN / SNP) to Lemon account
**Amount in dispute:** ARS 50,000
**Question:** Must Lemon credit ARS 50,000 to the user's Lemon account when the user has not provided the Coelsa ID and the transfer is not visible in Lemon's records?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección** — protect users from loss when the service provider has caused or could remedy the harm.
2. **Información** — Lemon must inform users clearly about how to trace inbound transfers.
3. **Transparencia** — operational requirements (e.g. Coelsa ID) and limits must be reasonably explained.
4. **Buena fe** — both parties act in good faith; user must cooperate when reasonable info is requested.
5. **In dubio pro usuario** — tiebreaker if evidence balances.
6. **Educación** — Lemon should educate the user on interbank-rail mechanics.
7. **No discriminación** — not engaged.
**Section B:** Lemon T&Cs cannot override Section A but here align with it (cooperation needed to investigate).

## Burden of proof
User must show that ARS 50,000 actually reached Lemon (the destination entity) and was wrongly withheld. Lemon need only show a reasonable, good-faith investigation pathway (Coelsa ID) and the user's failure to supply it.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Email from "Santa Fe Soluciones" stating operation "exitosa" with internal log line containing CBU 4062900706923032, ARS 50,000, 2024-06-09 | Third-party bank confirmation | Not directly rebutted, but no Coelsa ID present | Medium — confirms debit from sender side, not credit to Lemon |
| User | Assertion no funds received in Lemon account | Statement | Not rebutted | Low (uncorroborated) |
| Lemon | Chat where agent Alan Matías Quinegro tells user to request Coelsa ID from the bank | Screenshot | Not rebutted | High — shows Lemon offered a clear remedial pathway |
| Lemon | Explanation of Coelsa role and need for Coelsa ID to trace funds not in Lemon's ledger | Operational explanation | Not rebutted | High |
| Lemon | User's failure to provide the Coelsa ID after request | Screenshot context | Not rebutted (user thanks the agent and does not follow up with the ID) | High |

Immaterial:
- Generic BCRA "Protección al Usuario Financiero" footer in the bank email.
- Kleros branding pages.

## Application
- **Protección:** Lemon is not refusing to credit funds it received — it states the transfer never arrived in its records. Protection does not require crediting unverified amounts.
- **Información:** Lemon told the user, in writing through support chat, exactly what was needed (Coelsa ID) and why. Sufficient.
- **Transparencia:** The Coelsa-ID requirement is consistent with BCRA Comunicación "A" 7175 and openly explained in the descargo.
- **Buena fe:** Lemon acted in good faith by attempting to investigate. The user, despite being asked, did not return with the Coelsa ID — instead escalating to Kleros.
- **In dubio:** No tie. The user has produced sender-side evidence (CBU 4062…, DEBIN "Aprobada") but the destination CBU shown is not demonstrated to be a Lemon CBU, and crucially no Coelsa ID has been supplied. Evidence is incomplete, not balanced.
- **Educación:** Lemon's descargo explains the SNP and Coelsa flow clearly and offered a link.
- **No discriminación:** Not engaged.
- **T&C compatibility:** No T&C clause invoked that conflicts with Section A.

## Jurisdiction / Morality / Validity
Standard consumer-protection dispute over fiat custody on a regulated payments rail. Properly arbitrable.

## Schelling-Point check
The neutral, policy-literate juror's answer: when the user has not provided the single identifier the platform needs to trace the funds, and the platform offered that pathway clearly and in writing, the claim is premature against Lemon. Most jurors converge on Favor Lemon.

## Bias audit
Resisting sympathy for a user who genuinely may have lost ARS 50,000 — but the remedy lies with the originating bank (which must provide the Coelsa ID) and/or with re-submission to Lemon support once that ID is in hand. Voting Favor Lemon does not foreclose recovery; it reflects that the user has not exhausted the cooperative step that the policy of Buena fe requires.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
Under Section A of the Política, Información and Transparencia require Lemon to tell the user clearly how an inbound interbank transfer can be traced. The descargo shows Lemon's support agent did exactly that, telling the user in writing to obtain the Coelsa ID from the originating bank — the standard identifier that lets any Argentine financial entity locate a transaction within the SNP/Coelsa clearing system (BCRA Comunicación "A" 7175). Lemon's explanation of why the Coelsa ID is necessary, and its statement that the transfer is not visible in its records without it, is unrebutted.

The user's evidence — an email from "Santa Fe Soluciones" — confirms a successful DEBIN debit on the sender's side, but contains no Coelsa ID, does not demonstrate that the destination CBU shown corresponds to a Lemon account, and does not show credit to Lemon. Under Buena fe the user was expected to return with the Coelsa ID after Lemon's request; the chat shows the user instead closed the exchange ("Alan, muchas gracias") without providing it. The Protección principle does not require Lemon to credit funds that it cannot verify ever reached its accounts.

In dubio pro usuario is a tiebreaker and is not triggered here, because the evidentiary record is not balanced — it is incomplete on the user's side in a way the user controls. The correct, Schelling-point outcome is Favor Lemon, without prejudice to the user re-opening the matter once the originating bank supplies the Coelsa ID.
