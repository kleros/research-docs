# Case 42 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** USDT (TRC20) crypto deposit into Lemon account
**Amount in dispute:** Not stated (USDT amount of the alleged transfer; not specified in either submission)
**Question:** Must Lemon credit the user for a USDT transfer the user claims to have sent but which Lemon says was sent to an address not belonging to Lemon?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política de Defensa al Consumidor Lemon — Sección A: Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. Sección B: T&Cs and product rules apply where compatible with Sección A.
3. Kleros General Court morality clause and burden-of-proof default (claimant must prove the claim that displaces the default state).
4. "Unrebutted evidence presumed genuine" — Kleros evidentiary norm.
5. Operational reality of public blockchains: funds sent to an address controlled by a third party cannot be recovered by the receiving exchange.

## Burden of proof
The user (claimant) bears the burden to show that the transfer was actually sent to a Lemon-controlled deposit address and that Lemon failed to credit it. Lemon need only rebut by showing the destination address is not theirs.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of Lemon transaction list with red annotations; description that a USDT transfer "was made" but not credited | Secondary (screenshot, illegible at scale) | Yes — Lemon traced the hash and found destination ≠ Lemon | Low |
| User | Hash ID (referenced by Lemon as 14e2bd47…b244) | Primary (on-chain identifier) | Used by Lemon against user | Medium |
| Lemon | Support team's on-chain trace of the hash showing destination = TCnAZbDdmpyhGYY7iBNBzhmFV2x9D5bw7, not Lemon's address (TTzhPQwUDcXjy4lUSL8tjGmMHIDVE5pj provided to user) | Primary (blockchain explorer attestation) | Not rebutted by user | High |
| Lemon | Statement that Lemon cannot recover funds sent to addresses not under its control | Policy / operational fact | Not rebutted | High |

Immaterial:
- Emotional framing in user's submission ("Lemon should be responsible…") — does not address the factual destination of the transfer.

## Application
- **Protección:** User-protection does not extend to crediting funds an exchange never received. Protection covers Lemon-caused harm, not user-directed send-to-wrong-address errors. No violation.
- **Información:** Lemon states it provided the user with the correct TRC20 deposit address (TTzhPQwUDcXjy4lUSL8tjGmMHIDVE5pj). User does not contest having been given this address or claim it was wrong. No info-disclosure violation shown.
- **Transparencia:** Lemon transparently identifies the on-chain hash and the actual destination address. No hidden term operating against the user.
- **Buena fe:** Lemon engaged the support team, traced the hash, and explained the result. Good-faith conduct.
- **In dubio pro consumidor:** Tiebreaker only. Here the on-chain evidence is one-sided — Lemon's trace is unrebutted. No tie to break.
- **Educación / No discriminación:** Not engaged.
- **T&C compatibility:** Lemon's position (no liability for funds sent to non-Lemon addresses) is a basic operational reality of blockchain custody and is compatible with Sección A; it does not function as a "catch-all immunity" overriding consumer rights because no Lemon failure has been shown.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica, Lemon consumer disputes); no morality issue; question well-formed.

## Schelling-Point check
A panel of diligent, policy-literate jurors reading the same materials would converge on Favor Lemon: the user's only documentary evidence is an illegible screenshot, while Lemon presents a specific transaction hash trace showing the funds went to an address that is demonstrably not Lemon's deposit address. Lemon cannot credit funds it never received, and cannot recover funds sent on-chain to a third-party address. This is the obvious literal reading.

## Bias audit
Decision rests on unrebutted on-chain evidence, not on party identity or rhetoric. No sympathy bias toward user despite consumer-protection framing — protection principles require an actual failure by the provider, which is not demonstrated. Re-run with chronology: user claims missing credit → Lemon traces hash → user did not rebut. Conclusion stable.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user alleges a USDT deposit was not credited to their Lemon account. Under the Política de Defensa al Consumidor Lemon (Sección A — Protección, Información, Transparencia, Buena fe), a finding for the user requires evidence that Lemon either received the funds and failed to credit them, or caused the misdirection (e.g., by giving the user the wrong deposit address). The user submits only an illegible screenshot with red annotations and a narrative assertion that the funds were sent.

Lemon, in response, traces the transaction hash supplied by the user and shows the funds were sent on-chain to address TCnAZbDdmpyhGYY7iBNBzhmFV2x9D5bw7 — not to the TRC20 deposit address (TTzhPQwUDcXjy4lUSL8tjGmMHIDVE5pj) that Lemon assigned the user. The user has not rebutted this trace, nor disputed the deposit address Lemon provided. Under the Kleros evidentiary norm, Lemon's unrebutted primary evidence is presumed genuine. The user has therefore failed to discharge the burden of proving that Lemon received and withheld the funds.

The "in dubio pro consumidor" tiebreaker does not apply because the evidence is not in equipoise — it is one-sided in Lemon's favour. Buena fe and Transparencia are satisfied: Lemon engaged the user's claim substantively and disclosed its trace. A blockchain custodian cannot be made responsible for funds the customer directed to an address outside the custodian's control, and applying such liability would have no basis in Sección A. Vote: Favor Lemon.
