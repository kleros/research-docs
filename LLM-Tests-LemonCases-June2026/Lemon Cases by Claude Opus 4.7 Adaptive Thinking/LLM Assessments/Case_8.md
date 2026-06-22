# Case 8 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto deposit (Ethereum/WETH) sent over the Optimism network into Lemon Cash, allegedly not credited.
**Amount in dispute:** ~USD 72.68 (per user's app screenshot showing -$72.68 movement) — value of the ETH/WETH transferred on Optimism.
**Question:** Must Lemon credit (or otherwise compensate) the user for funds sent on the Optimism network when Lemon's custodial provider does not support Optimism deposits?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política de Interpretación de Disputas, Section A — seven principles (Protección, Información, Transparencia, Buena fe, In dubio pro consumidor, Educación, No discriminación).
2. Section B — T&C clauses must be compatible with Section A; non-compatible clauses do not control.
3. Interpretive guidance: information/transparency is judged on the offer AS PRESENTED to the consumer in-app; limits buried only in linked T&Cs presumptively violate principles 2–3. A clearly stated network/asset limit that the user nonetheless breached is generally exonerative for Lemon.

## Burden of proof
User bears initial burden to prove (a) a deposit was sent and (b) it reached a Lemon-controlled address on a network Lemon advertised as supported. Lemon then bears the burden to show that either (i) the funds never reached its custody, or (ii) the network/asset was clearly disclosed as unsupported in the deposit flow.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Optimism Etherscan tx 0x490873…b7ad, Status Success, Logs show WETH (0x4200…0006) Transfer to 0x74da…8dfe, value 0.03873 ETH | Primary (on-chain) | Not rebutted | High — proves a transfer occurred on Optimism |
| User | Lemon app screenshot "Retiro de Ethereum -$72.68 … 06:42 p.m. jul. 28, 2023 … A 0x74…8dfe … Completado" | Primary (Lemon UI) | Not rebutted | High — but ambiguous: this is labelled "Retiro" (withdrawal FROM Lemon), not a deposit. Destination 0x74…8dfe matches the Etherscan recipient. |
| User | Narrative: "envié los fondos correctamente como la plataforma así lo dispone" | Self-serving statement | Implicitly rebutted by Lemon | Low — bare assertion, no screenshot of any Lemon in-app instruction telling user to use Optimism |
| Lemon | Statement that its custodial provider does not support Optimism for the relevant token | Self-serving statement | Not corroborated with a screenshot of the deposit screen | Medium — plausible and technically consistent with the on-chain evidence, but undocumented |
| Lemon | Statement that the logs are internal-provider movements and Lemon never received the funds | Inference from user's own evidence | Not rebutted | Medium-High — consistent with on-chain data |
| Lemon | Statement that it is working with the provider on a good-faith reintegration program | Voluntary undertaking | Not rebutted | Medium — relevant to Buena fe |

Immaterial:
- User's hardship/effort arguments ("trabaje muy duro", "para mí es mucho dinero") — emotional appeal, no legal weight under Section A.
- Lemon's general T&C catch-all immunity language — under Section B such clauses cannot override Section A.

## Application
- **Protección:** The user is entitled to protection, but protection presupposes that Lemon had custody or that Lemon's representations caused the loss. The on-chain evidence the user himself supplied points to a transaction on Optimism going to an address that, per Lemon, is its provider's internal infrastructure, not a deposit address Lemon advertised for Optimism. The duty of protection does not extend to compensating user error on an unsupported network when there is no evidence Lemon represented Optimism as supported.
- **Información:** Lemon's defence is thin — it does not produce a screenshot of the deposit screen showing the supported-networks list. However, the user also produces no screenshot showing Lemon advertised Optimism as a valid deposit network for ETH. The user's only Lemon-UI screenshot is a "Retiro de Ethereum" (a withdrawal FROM Lemon), not a deposit instruction. Burden-of-proof: the user must show he followed an instruction Lemon gave him; he has not.
- **Transparencia:** No evidence of misleading advertising of Optimism-ETH deposit support. Absent such evidence, no transparency breach is established.
- **Buena fe:** Lemon expressly states it is working with the provider to try to reintegrate funds for users in this situation despite no contractual obligation — this is an act of good faith, not bad faith. There is no indication Lemon is concealing custody of the funds.
- **In dubio:** The factual record is sufficiently one-sided (user's own on-chain evidence is consistent with Lemon's story, and the user produced no evidence Lemon represented Optimism as supported) that the in-dubio tiebreaker is not triggered. It is invoked only where evidence is in genuine equipoise after all other principles are applied.
- **Educación / No discriminación:** Not implicated.
- **T&C compatibility:** Lemon invokes its T&Cs but does not quote a specific clause. No clause needs to be tested against Section B because the case is resolved on the principle that the user has not proven Lemon ever received the funds or ever advertised Optimism as supported.

## Jurisdiction / Morality / Validity
Properly within Kleros "Blockchain No Técnica" — consumer dispute against Lemon Cash. No morality issue. Pleadings are sparse but minimally formed. RtA filters do not trigger.

## Schelling-Point check
A diligent, policy-literate juror would observe: (1) the user's own Etherscan evidence shows the transfer was on Optimism, (2) sending crypto on an unsupported network to a custodian's mainnet/other-network address is a classic and well-known user error, (3) the user produced no evidence Lemon told him to use Optimism, and (4) Lemon's account is consistent with the on-chain data. The Schelling-point answer is to deny the claim while acknowledging Lemon's voluntary reintegration effort.

## Bias audit
I checked for sympathy bias toward the user's hardship narrative — set aside as legally immaterial. I checked for anti-corporate bias against Lemon — set aside; Lemon's documentary record is thin but the user bears the initial burden and has not met it. I checked whether Lemon's failure to attach a screenshot of the deposit-network list should flip the case — concluded no, because the user (who claims he followed Lemon's instructions) is the one in possession of those instructions and would have screenshot them if they said "Optimism". The asymmetry of access cuts against the user here.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (English)

The user's claim fails on the burden of proof. Under Principle 2 (Información) and Principle 3 (Transparencia), a user alleging that Lemon mis-instructed him into using the Optimism network must produce some evidence — a screenshot of the deposit screen, a support-chat confirmation, an in-app banner — that Lemon represented Optimism as a supported deposit network for ETH. The user produced none. His only Lemon-UI screenshot is labelled "Retiro de Ethereum" (a withdrawal from Lemon), not a deposit instruction, and his Etherscan logs confirm the transfer happened on Optimism to an address Lemon credibly identifies as its provider's internal infrastructure.

Under Principle 1 (Protección), consumer protection does not extend to compensating a user for funds that never entered the merchant's custody where the user has not shown the merchant caused or invited the error. Under Principle 4 (Buena fe), Lemon's voluntary commitment to work with its provider on reintegration — expressly described as beyond its contractual obligation — weighs in Lemon's favour, not against it. The in-dubio tiebreaker (Principle 5) is not invoked because the evidentiary record is not in genuine equipoise; the user's own on-chain evidence corroborates Lemon's factual account.

Accordingly, the claim is denied. This outcome does not prejudge any later voluntary refund Lemon may extend through its provider; it holds only that, on the record before this panel, Lemon has no enforceable obligation under Section A of the Política to credit the funds.
