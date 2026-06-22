# Case 67 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Lemon Cash subcourt) > General Court
**Promo / product at issue:** Worldcoin (WLD) withdrawal from World App into Lemon wallet
**Amount in dispute:** S/ 215.99 (25 WLD / ~24.998939 WLD, Oct 16, 2024)
**Question:** Should Lemon credit the User the S/ 215.99 / 25 WLD sent from Worldcoin to the Lemon wallet?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política — Section A (Lemon Consumer Policy):** Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. **Section B:** T&Cs apply where compatible with Section A.
3. **Lemon T&Cs clause 13.7 — "Activos Digitales No Listados":** Where a user erroneously sends a non-listed digital asset or uses a non-listed network, those assets may not be reflected in the account; Lemon is not obligated to support unlisted assets.
4. **Offer-as-presented principle:** Information/Transparencia is judged on what was visible to the user at the time. Hidden limits = likely violation. Clear limits + user error = claim fails.
5. **Unrebutted evidence is presumed genuine.**

## Burden of proof
User must show the operation should have been credited (or was promised) under the offer-as-presented; Lemon must show the limit was clear and that, where applicable, it nonetheless honoured the claim.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon app screenshot showing "Retiro de Worldcoin" S/ 215.99 / 24.998939 WLD, marked "Con éxito" on Oct 16, 2024 10:40, to address 0x44…3269 | Primary (in-app screenshot) | No | High |
| Lemon | T&C clause 13.7 (unlisted assets disclaimer) | Primary (contract text) | No | High |
| Lemon | Screenshot of Lemon "Novedades" / supported-tokens list — WLD not present | Primary (app content) | No | Medium |
| Lemon | Internal admin panel screenshot "CASH_IN_CRYPTO Completada", Trx ID 62d99c94-…, +25 WLD credited to user Pedro Pablo Gastelo Cecilio (ID 2862962), dated 23/10/2024 15:11:59 | Primary (internal system record) | No | **Decisive** |
| Lemon | Reference to Lemon EDU educational resources | Secondary | No | Low |

Immaterial:
- Generic appeals to "Protección / Transparencia / Buena fe" without specifics — restate principles, not facts.

## Application
- **Protección:** Satisfied. The user's economic interest in the 25 WLD was ultimately safeguarded — funds were credited (admin record dated 23/10/2024).
- **Información:** Lemon publishes a token-listing screen ("Novedades") and educational content (Lemon EDU). WLD is genuinely absent from the listed-token roster. The clear-limit prong is met.
- **Transparencia:** T&C 13.7 is express, plain-language, and on point for the exact scenario (user sends an unlisted asset). No hidden limit was applied retroactively.
- **Buena fe:** Despite no contractual obligation under 13.7, Lemon's tech team recovered and credited the unlisted-token deposit. That is good-faith conduct above the contractual floor.
- **In dubio pro consumidor:** Not engaged — the facts are not in doubt. Lemon's admin screenshot (unrebutted) shows the +25 WLD was credited. The user's complaint ("la transferencia no se ha concretado") is overtaken by that later event; the user did not submit any reply rebutting the credit.
- **Educación:** Lemon's EDU/Novedades content is in evidence and is consistent with the policy's educational duty.
- **No discriminación:** Not engaged.
- **T&C compatibility with Section A:** Clause 13.7 is compatible — it permits, but does not require, Lemon to refuse unlisted-asset operations. Here Lemon went beyond the clause and credited anyway, so no Section A friction arises.

## Jurisdiction / Morality / Validity
Correct subcourt (Blockchain No Técnica, Lemon). No morality concerns. Question is well-formed.

## Schelling-Point check
A diligent panel reading these two filings will see: (i) WLD is not a listed token, (ii) T&C 13.7 squarely covers the scenario, and (iii) Lemon's unrebutted internal record shows the 25 WLD was already credited to the user's account a week after the deposit. The simple, literal reading converges on Favor Lemon.

## Bias audit
The user's framing is sympathetic (frustration, financial planning), but sympathy is not material. No party-identity or polish bias detected. The decisive fact is documentary (the admin credit screenshot), not rhetorical.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English, for on-chain submission)

The user complained that a S/ 215.99 (≈25 WLD) Worldcoin withdrawal to Lemon was never credited. Worldcoin's WLD token is not on Lemon's listed-asset roster (visible in the in-app "Novedades" screen submitted by Lemon), and Lemon's T&C clause 13.7 expressly states that assets sent on unlisted tokens or networks are not guaranteed to be reflected in the user's account. Under the offer-as-presented principle that governs Información and Transparencia, this limit is clearly and publicly disclosed in advance — it is not a hidden carve-out — so the Section A consumer-protection principles are not breached.

More importantly, Lemon's unrebutted internal admin record (CASH_IN_CRYPTO transaction 62d99c94-19fb-413b-af91-26fd5a40c8ba, dated 23/10/2024, marked "Completada", +25 WLD to user ID 2862962, Pedro Pablo Gastelo Cecilio) shows the deposit was in fact credited approximately one week after the on-chain transfer. Per standard Kleros practice, unrebutted evidence is presumed genuine, and the user filed no reply contesting this credit. The Buena fe principle therefore points toward Lemon, which went beyond its contractual position under 13.7 to recover and credit funds it was not obligated to support. The in-dubio-pro-consumidor tiebreaker is not engaged because the operative facts are not in doubt.

Accordingly, the vote is Favor Lemon: T&C 13.7 (compatible with Section A) covers the scenario, the limit was transparently disclosed, and the disputed funds have already been delivered to the user.
