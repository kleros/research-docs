# Case 112 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (VISA Física *7744) — disputed card payment to ROBLOX.COM
**Amount in dispute:** S/ 18.26 PEN (single charge of 12 July 2025, 10:35 hs)
**Question:** Must Lemon refund a card charge to ROBLOX.COM that the user claims is unauthorized, when Lemon's back-office records show two prior recurring charges from the same merchant on the same physical card?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Principio de Protección** — Lemon must safeguard user funds against unauthorized/fraudulent movements operationally within its control.
2. **Principio de Información** — Lemon must clearly inform the user about how operations are executed.
3. **Principio de Transparencia** — The offer "as presented" governs; hidden limits or undisclosed mechanics weigh against Lemon.
4. **Principio de Buena Fe** — Both parties must act honestly; misrepresenting facts or omitting material context defeats the principle.
5. **In dubio pro consumidor** — Tiebreaker only, applied where evidence is in genuine equipoise.
6. **T&C compatibility (Section B)** — T&Cs cannot override Section A; conversely, where T&Cs and Section A both align with the merchant facts, a clearly authorized prior pattern controls.
7. **Burden / standard** — Balance of evidence (preponderance). Party asserting a change to the default (here, the User asserting the charge was not authorized) bears the initial burden once Lemon shows the charge was executed against the user's own physical card.

## Burden of proof
Once Lemon demonstrated the transaction was completed on the user's own physical card *7744 and that two prior identical-merchant charges had been processed on the same card without challenge, the burden shifted to the user to substantiate the unauthorized nature of the disputed charge (e.g., card theft, app compromise, account takeover, denial of any Roblox account). The user provided no such substantiation.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of completed card payment S/ 18.26 to ROBLOX.COM on 12/7/2025, on the user's own VISA Física *7744 | Primary (app screen of own card) | No | High — confirms the charge occurred on user's own physical card |
| User | Bare assertion "no realicé ni autoricé" the transfer | Secondary (unsupported allegation) | Contradicted by pattern evidence | Low |
| Lemon | Back-office (BO) records of LEMON_CARD_PAYMENT to "Google Roblox" on 27/5/2025 (3.98 PEN) and 6/6/2025 (3.98 PEN), both on card *7744, with full Trx IDs and authorization IDs | Primary internal ledger | No | High — establishes a pre-existing recurring relationship with the merchant on the same card |
| Lemon | Description of confirmation flow (slide-to-confirm) for transactions | Secondary (illustrative; ARS screenshots) | No | Low-Medium — establishes general process, less probative for a card charge initiated by a merchant subscription |
| Lemon | CEE ID 20250818204222209224152768049 provided so user can pursue chargeback / refund with the merchant (Roblox) directly | Primary (operational reference) | No | Medium — shows Lemon discharged its operational duty by routing the user to the merchant who controls the subscription |

Immaterial:
- Generic invocations of "principios" without supporting facts (user descargo) — relied on rhetorically but add no evidentiary weight.
- The ARS-flow confirmation screenshot — disputed charge is a merchant-initiated card payment, not a peer-to-peer transfer, so the slide-to-confirm flow is only tangentially relevant.

## Application
- **Protección:** Lemon's protection obligation extends to operations within its control. A card charge presented to the network by a merchant with whom the user already had a documented recurring relationship is not an obvious unauthorized movement triggering a protection failure. No protection breach shown.
- **Información:** Lemon disclosed full transaction details (merchant name, date, amount, transaction ID, card used) in-app. No information deficit.
- **Transparencia:** Lemon disclosed the recurring history transparently in its descargo, including authorization IDs and creation dates. No hidden mechanic identified. Conversely, the user omitted any mention of the two earlier identical-merchant charges — that omission cuts against the user under the principle of transparency / good faith.
- **Buena fe:** User asserts no authorization but offers nothing to explain the pre-existing Roblox charge history on the same physical card. A good-faith claimant would address that pattern. Lemon's evidence is corroborated and consistent.
- **In dubio:** Tiebreaker only. The evidence is not in equipoise — Lemon's primary BO records of the pre-existing recurring relationship are unrebutted and outweigh the user's bare denial. Tiebreaker does not engage.
- **Educación:** Lemon directed the user to the correct remedy — contacting the merchant (Roblox) with the CEE ID to cancel the subscription or seek a merchant-side refund. This satisfies the educational duty.
- **No discriminación:** Not implicated.
- **T&C compatibility:** Not specifically pleaded; no T&C clause conflicts with Section A on the facts shown.

## Jurisdiction / Morality / Validity
Pass. Proper subcourt (Blockchain No Técnica, Lemon policy). No morality clause triggered. Question is well-formed and answerable on the materials.

## Schelling-Point check
A diligent panel will note: (i) the charge was executed on the user's own physical card; (ii) two unchallenged prior charges to the same merchant exist on the same card, indicating a pre-existing subscription; (iii) the user did not deny holding a Roblox account, did not allege card theft, account takeover, or app compromise, and did not address the prior charges at all; (iv) Lemon discharged its duty by giving the user the CEE ID needed to chase the merchant. The literal, obvious reading converges on Favor Lemon.

## Bias audit
No reliance on party identity, polish, or sympathy. The user's invocation of consumer-protection principles is rhetorically sympathetic but unsupported on the facts. Decision rests on the unrebutted primary-record pattern of prior authorized charges to the same merchant on the same card.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user disputes a S/ 18.26 charge to ROBLOX.COM on 12 July 2025 made via their own Lemon VISA Física *7744, asserting it was unauthorized and invoking Protección, Buena Fe and Transparencia. Lemon's descargo produces internal back-office records showing two prior LEMON_CARD_PAYMENT transactions on the same card *7744 to the same merchant ("Google Roblox") — 27/5/2025 (3.98 PEN, Trx ID 95808c01-...) and 6/6/2025 (3.98 PEN, Trx ID 22439253-...) — each with full authorization IDs. These records are primary, unrebutted, and establish a pre-existing recurring relationship with the merchant on the user's own physical card.

Under Section A, the burden of proof on a balance of evidence sits with the party asserting a change to the default state. Once Lemon demonstrated the charge ran on the user's own physical card against an established merchant relationship, the user needed to substantiate the alleged lack of authorization (e.g., card theft, app compromise, denial of any Roblox/Google account). The user did neither — they did not address the prior charges, did not deny holding a Roblox account, and offered no facts beyond a bare denial. The Buena Fe and Transparencia principles cut against a claimant who fails to engage with directly relevant facts in the counterparty's records.

Lemon also satisfied its Educación/operational duties by providing the user the CEE ID (20250818204222209224152768049) and directing them to the merchant to cancel the subscription or pursue a merchant-side refund — which is the correct path for a card-network subscription charge that the merchant, not Lemon, controls. The In dubio tiebreaker does not engage because the evidence is not in equipoise. The Schelling-point answer a diligent panel converges on is Favor Lemon.

---

Case 112 | VOTE: Favor Lemon | CONFIDENCE: high | Unrebutted BO records show two prior Roblox charges on user's own physical card; user denied authorization without addressing the established subscription pattern.
