# Case 59 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** None — generic custodial-wallet outbound crypto transfer (AVAX) from user's Lemon account to an external wallet.
**Amount in dispute:** ~ARS 30,000 in AVAX (as stated by user).
**Question:** Is Lemon liable to refund a user whose crypto was transferred from her Lemon account to an unknown external wallet, where she admits she had lent her phone to a relative?

## Options
- **Favor User** — Lemon must compensate / refund the AVAX equivalent.
- **Favor Lemon** — Claim rejected; loss attributable to user's voluntary handover of the device.
- **Refuse to Arbitrate** — only if jurisdiction, morality or validity fails.

## Governing rules
1. **Política de Defensa del Consumidor Cripto — Sección A** (mandatory principles): Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. **Sección B** — T&Cs are subordinate to Sección A; catch-all immunity clauses cannot override Sección A.
3. Burden lies on the user to show that the loss stems from a Lemon failure (deficient protection, hidden information, opacity, bad faith). Custodial exchanges are not insurers against user self-inflicted loss when account holder retains uncompromised credentials and voluntarily lets a third party operate the device.
4. Unrebutted evidence presumed genuine (Kleros general).

## Burden of proof
On the user (claimant seeking change from default — i.e. she seeks compensation from Lemon). Standard: balance of probabilities under Sección A.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of an **ADA withdrawal** dated 1 Aug 2024 to an external Cardano address, marked "Completo" | Primary (Lemon-generated UI) | No | Low — concerns ADA, not the AVAX loss claimed; in fact tends to show a clean, completed user-authorised withdrawal flow |
| User | Screenshot of Lemon home screen with ARS 0,00 balance | Secondary | No | Low — only shows current empty balance |
| User | Narrative: "first time using this wallet", lost ~ARS 30,000 in AVAX to an unrecognised wallet, support didn't help | Party assertion | Partially rebutted by Lemon's account of support chat | Low |
| Lemon | Internal Fraud-team review: user funded ARS, bought crypto, transferred to external wallet within <20 minutes; no account compromise detected | Primary (internal record) | Not rebutted | Medium-High |
| Lemon | Screenshot/reference to support chat in which **user admits she had lent the phone to her nephew** and that the device was not in her possession | Primary (support transcript) | Not rebutted by user | High — dispositive |

Immaterial:
- ADA withdrawal screenshot — different asset, different date, no causal link to alleged AVAX loss; it only demonstrates that withdrawals from Lemon are normal user-initiated operations.
- Zero-balance home screen — consistent with funds having been sent out; does not show *who* sent them.

## Application
- **Protección:** Lemon's duty extends to system-side security (auth, fraud screening, segregation of funds). No evidence of a Lemon-side breach; fraud team confirmed no vulneración. Where the legitimate device-holder voluntarily transfers physical/logical control of an authenticated session to a third party, the resulting outbound transfer is a "legitimate instruction" from Lemon's perspective. Protección not breached.
- **Información:** No promo or product term is at issue; user does not allege any misleading offer. N/A / not breached.
- **Transparencia:** No hidden limit, no surprise condition invoked. Transaction details (network, fee, hash, destination address) were disclosed in-app (the ADA receipt screenshot itself evidences full disclosure). Not breached.
- **Buena fe:** Lemon engaged its fraud team, reviewed internally, and replied substantively citing the user's own support-chat admission. No bad-faith conduct shown. Not breached.
- **In dubio pro consumidor:** Tiebreaker only. Here there is no real doubt — the user's unrebutted admission that the phone was lent to a relative resolves the factual question. Tiebreaker does not engage.
- **Educación:** No claim of failure to educate raised; in any event would not cure a voluntary device handover.
- **No discriminación:** Not raised, not relevant.
- **T&C compatibility (Sección B):** No T&C clause is being weaponised here; Lemon does not rely on a catch-all immunity, but on a factual finding of user-side device loan. Compatible.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica, Lemon). No enumerated immoral conduct by either party. Question is well-formed and answerable from materials.

## Schelling-Point check
A diligent, policy-literate panel will converge on **Favor Lemon**. The decisive fact — user admitted lending her phone to her nephew — is unrebutted, comes from her own statements to support, and breaks any chain of liability between Lemon's systems and the outbound transfer. The user's own evidence (a clean prior ADA withdrawal) reinforces that Lemon's withdrawal flow is transparent and user-driven.

## Bias audit
Sympathy for a small claimant with a material loss is noted and discounted. The asymmetry of polish between the parties' submissions (user is informal, Lemon is corporate) does not affect weighing. The decision rests on the unrebutted device-loan admission, not on rhetorical style or party identity.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

Under Sección A of the Política de Defensa del Consumidor Cripto, Lemon's protective duties (Protección, Información, Transparencia, Buena fe) target system-side conduct and the integrity of the offer as presented. They do not convert a custodial exchange into an insurer against losses caused by the user's voluntary surrender of device control to a third party. Lemon's unrebutted submission — corroborated by reference to the user's own support-chat statements — is that the account was not compromised, that the transfer flow (ARS deposit → crypto purchase → outbound transfer) was operated on the user's device in a normal manner, and that the user herself acknowledged the phone had been lent to her nephew. That admission is unrebutted and is presumed genuine.

The user's evidence does not displace this finding. Her ADA withdrawal screenshot relates to a different asset on a different date and, if anything, illustrates the transparent, user-initiated nature of Lemon's outbound flow (network, fee, destination, hash and transaction ID all disclosed). The zero-balance screenshot is equally consistent with an authorised outbound transfer. She produces no evidence of a Lemon-side authentication failure, no evidence of a hidden limit or misleading term, and no evidence rebutting the device-loan admission relied on by Lemon.

The "in dubio pro consumidor" principle is a tiebreaker and does not engage where, as here, the factual record points clearly in one direction. No Sección A principle has been breached and no Sección B T&C tension arises (Lemon does not invoke any catch-all immunity). The Schelling-point reading is therefore Favor Lemon.

---

Case 59 | VOTE: Favor Lemon | CONFIDENCE: high | User admitted lending phone to relative; no Lemon-side breach of Protección/Información/Transparencia/Buena fe; in-dubio tiebreaker not engaged.
