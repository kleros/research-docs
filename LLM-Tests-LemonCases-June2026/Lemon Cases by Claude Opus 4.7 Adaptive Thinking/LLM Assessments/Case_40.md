# Case 40 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** USDC on-chain deposit to Lemon account (Optimism network)
**Amount in dispute:** ~7.046428 USDC (~ARS $9,970 as displayed in-app)
**Question:** Is Lemon liable to credit the USDC transfer of 03-Jul-2024 (tx hash `0x432f...17b1f`) when the user appears to have sent it to a destination address that does not match their assigned Lemon deposit address?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Section A — Protección, Información, Transparencia, Buena fe, In dubio, Educación, No discriminación.**
2. **Section B — T&Cs subordinate to Section A.**
3. **Burden:** claimant must articulate and substantiate the alleged breach; bare assertions without facts are insufficient.
4. **On-chain deposits:** the user is responsible for sending funds to the exact deposit address provided by Lemon for the correct network. Funds sent to a different address are not Lemon's custody and cannot be credited absent recovery.
5. **Unrebutted evidence** is presumed genuine.

## Burden of proof
User must show that the transfer reached the correct Lemon-assigned deposit address (or that Lemon misled them as to the address). User has produced no such proof and no substantive argument.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Boilerplate statement: "T&Cs resulted in a prejudicial situation" with no facts | Pleading | N/A | None |
| User | Screenshot of in-app send: 7.046428 USDC to `0xa3...9018` shown in app, valued $9,970, jul-03-2024 | Screenshot | Not rebutted | Low — shows the send occurred but not to which on-chain destination |
| User | Etherscan screenshot showing tx `0x432f...17b1f` Success on OP Mainnet, action involves `0x087000A3...000E5d60E` | On-chain proof | Not rebutted | Medium — confirms tx executed |
| User | Worldcoin "bono" screenshot showing "Active grant not found! 1013" | Screenshot | Not rebutted | Immaterial — unrelated promo |
| Lemon | Support-chat screenshot in which the user themselves provides their Lemon USDC deposit address: `0x087000A300DE7200382b55D40045000000005d60E2A875c0F2D8A`, Optimism, with QR | Documentary admission | Not rebutted by user | High |
| Lemon | Statement that the user's true Lemon address differs from the destination of the on-chain transfer | Argument supported by above evidence | Not rebutted | High |

Immaterial:
- Worldcoin grant screenshot (different product, different date, no nexus to the USDC deposit claim).

## Application
- **Protección:** No breach by Lemon shown. Lemon is not obliged to credit funds that did not arrive at the user's assigned address.
- **Información:** Lemon provided a clear deposit address (visible in the user-shared QR/string in the support chat); the user input or copied a different/incomplete address into the send flow.
- **Transparencia:** No hidden term invoked; the dispute turns on a factual mismatch in destination address, not on undisclosed limits.
- **Buena fe:** Lemon's response is coherent, evidenced, and consistent with the user's own screenshots in support. The user's bare-bones pleading shows no bad faith by Lemon.
- **In dubio:** Tiebreaker only. There is no genuine tie here — the user has not even articulated a coherent claim, while Lemon's defence is corroborated by the user's own admissions.
- **Educación:** Not implicated; standard on-chain UX with explicit address/network confirmation.
- **No discriminación:** Not implicated.
- **T&C compatibility:** Standard term that on-chain deposits must use the correct address is consistent with Section A and is industry-standard for self-custodial/exchange flows.

## Jurisdiction / Morality / Validity
Within the Lemon consumer-protection Kleros subcourt. No moral/illegality concerns. Claim is properly framed for arbitration (no RtA).

## Schelling-Point check
A diligent unbiased juror would observe: (i) the user supplied only boilerplate; (ii) Lemon's evidence (a screenshot from the user's own support interaction) shows the user's actual deposit address differs from the destination of the on-chain transfer; (iii) Lemon cannot credit funds that did not reach the assigned address. The convergent honest vote is Favor Lemon.

## Bias audit
Resisted the user-protective default. User did not articulate any specific T&C violation. Lemon's evidence stems from the user's own messages and is unrebutted. No sympathy override warranted.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user's pleading is a generic statement that "Lemon's T&Cs resulted in a prejudicial situation," with no identified clause, no articulated breach, and no quantified harm beyond the on-chain transfer screenshots. Under the burden of proof and the Buena-fe / Información principles, a claimant must at minimum identify what Lemon did wrong; here they have not. The Worldcoin bono screenshot is immaterial — it concerns a different product, a different date, and is not tied to the USDC deposit claim.

Lemon's defence is supported by the user's own evidence shared in support: a screenshot in which the user provides their Lemon USDC deposit address on Optimism as `0x087000A300DE7200382b55D40045000000005d60E2A875c0F2D8A`. The on-chain transaction the user relies on (`0x432f…17b1f`) does not deposit to that assigned address — it interacts with a different routing path on Optimism. Funds that do not arrive at the user's assigned deposit address are not in Lemon's custody and cannot be credited; this is consistent with Section A (Protección, Información) and is not contradicted by any term inferior to it under Section B.

In dubio pro consumidor is a tiebreaker, not a rule of decision when one side has produced no substantiated claim. Applying Protección, Información, Transparencia, and Buena fe to the evidence as presented, the honest Schelling-point outcome is **Favor Lemon**, with high confidence.
