# Case 119 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** USDT withdrawal — manual network selection (BEP20 vs ERC20)
**Amount in dispute:** 28.37 USDT (net 27.37 USDT after 1 USDT fee)
**Question:** Is Lemon liable to refund (in whole or in part) a USDT withdrawal that the user sent on BNB Chain (BEP20) instead of Ethereum (ERC20), where the destination wallet did not support BEP20?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Section A.1 — Protección:** Lemon must protect users in high-risk operational contexts, especially where errors can cause irreversible loss.
2. **Section A.2 — Información:** Material risks must be communicated clearly and as presented at point of operation.
3. **Section A.3 — Transparencia:** Critical risks (irreversibility, network incompatibility = total loss) must be disclosed visibly and unambiguously.
4. **Section A.4 — Buena fe:** Both parties must act honestly and without concealment.
5. **Section A.5 — In dubio pro usuario:** Tiebreaker — when evidence is genuinely balanced, decide for the user.
6. **Section A.6 — Educación financiera:** Lemon has duty to educate users on risks of crypto operations.
7. **Section B — T&Cs vs Section A:** Contractual clauses (e.g., clause 6 on incorrect networks, clause 3 on irreversibility) cannot override Section A consumer-protection principles.

## Burden of proof
User is the claimant seeking departure from blockchain default (irreversible loss falls on sender). User must show Lemon breached Section A obligations (e.g., failure to warn, hidden risk). Lemon must show its disclosures were clear and as-presented at the point of the USDT withdrawal.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of completed USDT withdrawal — confirms destination address, BEP20 network, hash, amount | Primary | No | High |
| User | Admission that he selected BEP20 manually, calling it his "equivocación" | Primary (admission) | No | High |
| User | Allegation that no clear warning was given about network incompatibility / total loss | Assertion | Partially addressed by Lemon | Medium |
| Lemon | Screenshot of "Enviar BTC" address-input screen listing supported networks (BEP20, Bitcoin, Lightning, Rootstock) | Secondary — and from a DIFFERENT product flow (BTC, not USDT) | Not directly relevant to USDT screen user actually saw | Low |
| Lemon | Support-chat screenshot confirming transaction executed on BEP20 and instructing user to contact receiver | Primary | No | High (on execution facts only) |
| Lemon | T&C clause 6 (Lemon not responsible for sends on incorrect networks) and clause 3.3 (instructions irreversible) | Contractual | Not denied; user disputes its effect under Section A | High (as to T&C content) |
| Lemon | Assertion that warnings appear in withdrawal interface before confirmation | Bare assertion — no screenshot of the USDT withdrawal confirmation screen produced | Not substantiated with primary evidence | Low |

Immaterial:
- User's emotional appeal ("preciso el dinero") — does not bear on Section A criteria.
- Lemon's general statement that the transaction was technically successful — undisputed; does not resolve disclosure question.

## Application
- **Protección:** User selected the network manually; the loss arises from a known, documented blockchain risk. Protection does not extend to fully reversing user-driven irreversible blockchain instructions when the operation worked exactly as instructed. Lemon cannot recover funds it never held.
- **Información / Transparencia:** Lemon asserts warnings appear "en la interfaz de retiro, previo a la confirmación", but the only screenshot submitted is from the BTC send flow (showing supported networks), not the USDT withdrawal confirmation screen the user actually navigated. This is a notable evidentiary gap. However, the user himself does not deny that the network selector required him to pick BEP20 affirmatively; he frames the complaint as the *absence of a "double-confirmation" feature activated by default*, not as a hidden network selector. The "as presented" offer here clearly required network selection by the user, and the user admits he chose BEP20. The lack of an additional optional double-confirmation toggle is not a hidden limit — it is a feature-design choice that does not, on its own, breach Información/Transparencia under Section A as long as the network selection itself was visible (which user concedes).
- **Buena fe:** No bad faith by either party. User concedes error honestly; Lemon engaged via support, gave accurate technical guidance, and pointed user to the receiver as the only realistic path to recovery.
- **In dubio:** Tiebreaker is not triggered — the user's own admission that he manually selected the wrong network resolves the operative question. The factual picture is not balanced; it tilts to Lemon on causation.
- **Educación:** A double-confirmation toggle would be best practice and Lemon should consider adopting it, but absence of best practice is not a Section A violation when the underlying choice was disclosed and user-driven.
- **No discriminación:** Not in play.
- **T&C compatibility:** Clause 6 (no responsibility for wrong-network sends) and clause 3.3 (irreversibility) align with the blockchain default and do not override Section A here because Section A is not engaged on the facts — the risk that materialised was disclosed at the moment of selection (network had to be chosen by the user) and the loss is technically irreversible.

## Jurisdiction / Morality / Validity
Pass. Properly in "Blockchain No Técnica"; no morality issue; question is well-formed.

## Schelling-Point check
A diligent panel reading the user's own admission ("fue una equivocación en la selección de red") together with the irrecoverable nature of the on-chain transaction and the absence of any hidden term would converge on Favor Lemon. The user's argument is essentially a policy proposal (default-on double confirmation), not a demonstrated breach.

## Bias audit
Sympathy for a small-amount loss (USD ~28) and the user's candour could tempt a "split the loss" outcome, but Kleros options are binary on this dispute. The decisive fact is the user's own admission of manual selection of BEP20. Lemon's BTC-flow screenshot is weak evidence of USDT-flow warnings, but it is the user — not Lemon — who carries the burden, and the user does not allege the network selector was hidden, only that an additional safeguard was absent.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
The user expressly admits that he manually selected BNB Chain (BEP20) when withdrawing USDT to an address that only supported Ethereum (ERC20). The transaction executed exactly as instructed, was confirmed on-chain (hash 0x6ef7a4b8…4edb), and left Lemon's custody. Under blockchain operating principles and Lemon's T&Cs (clauses 3.3 and 6, consistent with Section A), Lemon has no technical or legal means to reverse an executed on-chain instruction, and the loss is attributable to a user-driven operational error rather than a system failure.

On the Section A principles, the complaint does not establish a breach of Información or Transparencia. The user does not contend that the network selector was hidden; his argument is that an additional "double confirmation" feature should be enabled by default. The absence of a non-mandatory safeguard is a feature-design preference, not a concealed limitation of the offer as presented. Lemon's own evidence of warnings is thin (a screenshot from the BTC send flow rather than the USDT confirmation screen), but the burden lies with the user to show a Section A breach, and his own admission of manual, conscious network selection resolves causation against him. Buena fe is satisfied on both sides; the In dubio tiebreaker is not engaged because the facts are not balanced.

The vote is for Lemon. The recommendation to the user is to pursue the receiving party (e.g., a wallet or exchange that may be able to import a BEP20 key for the same address) via Lemon's support guidance, which was offered in good faith.
