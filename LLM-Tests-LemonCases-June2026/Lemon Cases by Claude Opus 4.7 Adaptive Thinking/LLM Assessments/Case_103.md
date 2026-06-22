# Case 103 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** ETH withdrawal (network selection) on Lemon Cash platform
**Amount in dispute:** 0.01034325 ETH + 0.02560952 ETH = 0.03595277 ETH (≈ two withdrawals on Arbitrum, recipient expected Ethereum mainnet / ERC-20)
**Question:** Should Lemon refund / reverse two ETH withdrawals that the user sent over Arbitrum to a destination whose owner was watching the Ethereum mainnet?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Sección A — Principios rectores** (in order: Protección, Información, Transparencia, Buena fe, In dubio pro consumidor as tiebreaker, Educación, No discriminación).
2. **Política Sección B** — T&Cs are evaluated against Section A; a catch-all clause cannot override Section A principles.
3. **Operational guidance** — the "Offer As Presented" (what the user actually saw on screen at the moment of acting) governs whether Información / Transparencia were satisfied. Hidden limits = violation. Clearly displayed information + user error = claim fails.
4. **Lemon T&Cs Clause 6** — "La Empresa no se responsabiliza por el envío a través de redes incorrectas… el Usuario reconoce que dicha operatoria podrá ocasionar que los Activos Digitales no lleguen a destino."
5. **Lemon T&Cs Clause 3.3** — once executed, instructions are irreversible.
6. **Blockchain technical fact** — Arbitrum and Ethereum L1 share the same EVM address format. Funds sent via Arbitrum to a 0x… address technically arrived at that address *on Arbitrum*; they are not destroyed in transit, but the recipient must control the private key on Arbitrum to access them.

## Burden of proof
On the user (claimant). Default state is that completed, on-chain confirmed transactions stand; user must show a platform failure under Section A to obtain reversal/refund.

## Material evidence

| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of Lemon withdrawal #1 (0.01034325 ETH, 22 Apr 2025 17:31, Red: **Arbitrum**, tx hash 0x57bd06…) | Primary (own screenshot) | No | High |
| User | Screenshot of Lemon withdrawal #2 (0.02560952 ETH, 23 Apr 2025 04:06, Red: **Arbitrum**, same destination address, tx hash 0xbc6758…) | Primary | No | High |
| User | Assertion that platform "did not warn" about network incompatibility | Statement | Rebutted by user's own screenshots showing "Red: Arbitrum" displayed prominently | Low |
| Lemon | Statement that Arbitrum txs executed correctly, hashes confirm on-chain | Primary (matches user hashes) | No | High |
| Lemon | T&C Clause 6 (no liability for wrong-network sends) and Clause 3.3 (irreversibility) | Contractual | Not rebutted | High |
| Lemon | Screenshot of "Enviar BTC" destination-address screen showing network options for BTC | Secondary (wrong asset — BTC not ETH) | Partially weakened by being BTC flow not ETH flow | Low–Medium |

Immaterial:
- User's appeals to "good faith" and "no fraudulent intent" — Lemon does not allege fraud; this does not bear on whether Lemon breached a duty.
- The exact identity of the recipient and their wallet configuration — not in dispute and not Lemon's responsibility.

## Application
- **Protección:** The user is protected from *platform* failures, not from their own operational choices on an immutable rail. The funds are not "perdidos" in the platform's custody — they left the platform on the Arbitrum rail per the user's instruction. No protección violation by Lemon.
- **Información:** The user's *own* withdrawal-confirmation screenshots show "**Red: Arbitrum**" as a labelled field, alongside destination wallet, fee, hash and identifier — i.e., the network was explicitly named on the confirmation screen the user actioned. The information needed to avoid the error was present.
- **Transparencia:** The Offer As Presented displayed network = Arbitrum clearly on each of the two confirmations the user submitted as evidence. No hidden limit. The user's assertion that "no se me advirtió" is contradicted by their own exhibits.
- **Buena fe:** Both parties appear to act in good faith. User made a genuine operational mistake; Lemon executed the instruction as given. Good faith alone does not create a reversal right against an immutable blockchain transaction.
- **In dubio pro consumidor:** Tiebreaker only. Here there is no genuine factual or interpretive tie — the user selected Arbitrum manually, the platform displayed Arbitrum, the transaction executed on Arbitrum, and the recipient simply did not look on Arbitrum. In dubio does not engage.
- **Educación:** Lemon is expected to provide enough education for an average user to operate safely. The "Red: Arbitrum" label on the confirmation screen and the user's apparent familiarity with multi-step withdrawals (two successive sends on consecutive days) indicate the educational threshold was met. The error was a recipient-side coordination failure, not an educational gap on the sender side.
- **No discriminación:** Not implicated.
- **T&C compatibility (Sección B):** Clauses 6 and 3.3 are consistent with Section A here. Clause 3.3 reflects an immutable technical reality of blockchain — it is not a "catch-all immunity" override of Section A; it accurately describes what cannot be undone. Clause 6 narrowly disclaims liability for *wrong-network* sends, which is precisely the failure mode at issue, and does not conflict with Información/Transparencia because Lemon did surface the network on the confirmation.

## Jurisdiction / Morality / Validity
Pass. The dispute is correctly in "Blockchain No Técnica" (consumer crypto-platform dispute, not a code-audit question). No morality flag. The question is well-formed and answerable from the materials.

## Schelling-Point check
A diligent panel reading the user's own screenshots — which clearly show "Red: Arbitrum" on the confirmation — will converge on Favor Lemon. The user effectively concedes the operative facts (manually selected Arbitrum) and pleads error. Under "clear info displayed + user-failed" the policy guidance is that the claim fails.

## Bias audit
No reliance on party identity, wealth, or rhetorical polish. Sympathy for an honest user error noted and set aside — Kleros adjudicates rule-application, not equitable forgiveness. Lemon's BTC-flow screenshot is weak evidence about ETH-specific warnings, and I have discounted it accordingly; the decisive evidence is the user's own ETH withdrawal screenshots, which independently establish that the network was disclosed.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user seeks reversal of two completed ETH withdrawals (0.01034325 ETH on 22 April 2025 and 0.02560952 ETH on 23 April 2025) sent from Lemon over the Arbitrum network to a destination whose owner was watching Ethereum L1. The user's own evidence — the two Lemon confirmation screenshots — displays "Red: Arbitrum" as a labelled field on the confirmation screen, alongside fee, destination wallet, transaction hash and identifier. The Offer As Presented therefore disclosed the network. Under the policy's Información and Transparencia principles, a clearly displayed parameter that the user themselves selected and confirmed cannot ground a transparency violation. The user's assertion that "no se me advirtió" is rebutted by their own exhibits.

The operative failure is a manual network selection by the user that did not match the recipient's expectation. The funds are not in Lemon's custody — they left the platform on Arbitrum per a valid, on-chain confirmed instruction (hashes 0x57bd06… and 0xbc6758…). Lemon T&C clause 3.3 (instructions are irreversible once executed) is not a "catch-all immunity" overriding Sección A; it accurately states an immutable technical fact about blockchain settlement. Clause 6 narrowly disclaims liability for wrong-network sends and is compatible with Sección A on these facts because Información and Transparencia were satisfied. The Protección principle protects users against platform failure, not against their own confirmed instructions on an immutable rail.

There is no genuine factual or interpretive tie, so the in-dubio-pro-consumidor tiebreaker does not engage. Buena fe on the user's side does not create a reversal right against an executed on-chain transaction. The diligent-juror Schelling point on these exhibits is Favor Lemon, and I vote accordingly.

---

Case 103 | VOTE: Favor Lemon | CONFIDENCE: high | User's own screenshots show "Red: Arbitrum" on each confirmation; clear info displayed + user-selected wrong network = claim fails under Sección A.
