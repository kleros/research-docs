# Case 30 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Deposit of USDC (Bridged) on Polygon — token delisting / 10% recovery commission
**Amount in dispute:** USD 200 (user accepts ~USD 50 as reasonable conversion cost; disputes USD 250 fee)
**Question:** Was Lemon's 10% (USD 250) recovery commission on a 2,500 USDC-Bridged Polygon deposit a legitimate application of T&C cl. 13.7, or an excessive/under-notified charge that violates the Política's Información, Transparencia and Protección principles?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Section A.2 (Información) — Lemon must inform users clearly about which tokens / networks are supported and the cost of recovering non-listed assets.
2. Política Section A.3 (Transparencia) — fees, especially a 10% recovery fee, must be transparent and prominent at the point of relevance.
3. Política Section A.1 (Protección) — user must be protected from foreseeable losses where Lemon controls the information flow.
4. Política Section A.4 (Buena fe) — both parties act in good faith; Lemon must honour its own published terms.
5. Política Section B — if T&Cs conflict with Section A, Section A prevails; T&Cs that have been duly notified and are not excessive operate normally.
6. Política Section A.5 (In dubio pro consumidor) — tiebreaker only.

## Burden of proof
User must establish that the fee was hidden, mis-communicated, or excessive enough to override the T&C; Lemon must establish (a) the existence of the published rule, (b) effective communication, and (c) reasonableness of the 10% figure.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Polygonscan tx hash 0xf5c9…bed8 showing 2,500 USDC-Bridged sent | On-chain | No | High — proves the transfer |
| User | Lemon support chats (Seba, Valen, Melincué, Claris) acknowledging 2,250 USDC credited and confirming the 25-Jan email | Screenshots | No | High — confirms credit, fee, and Lemon's own factual position |
| User | Statement that the 25-Jan email was the only notification he received; address-change notices were in-app whereas this delisting was not | Testimonial | Partially rebutted by Lemon's assertion of push + banner, but Lemon provides no screenshot of those | Medium |
| Lemon | T&C cl. 13.7 quoting "10% recovery commission" for non-listed assets | Contractual | Not rebutted as text; user challenges enforceability/excess | High on existence, contested on application |
| Lemon | Screenshot of the in-app "Novedades" list showing listed tokens (USDC appears generically, with no network/contract distinction) | Screenshot | The screenshot actually supports the user — USDC is listed with no indication that the Polygon-bridged variant is excluded | Medium — cuts against Lemon |
| Lemon | Assertion that user received email + push + in-app banner | Bare assertion | User concedes one January email after searching; Lemon supplies NO evidence of push or banner | Low — unsubstantiated for push/banner |

Immaterial:
- User's comparison with competitor Belo's UX (suggestion, not a legal standard).
- User's frustration about chatbot responses.

## Application
- **Protección:** Partially engaged — user lost 10% of a substantial transfer because the Lemon UI listed "USDC" generically without disclosing which contract/network variant was accepted. A protective platform would surface contract-address detail at the deposit screen.
- **Información:** Lemon DID send a notification email on 25 January (user located it himself), and the token is generically listed. However, the screen at the moment of deposit does not distinguish between bridged and native USDC — a gap that the user reasonably flagged. The communication was minimally adequate but not optimal.
- **Transparencia:** The 10% recovery fee is published in cl. 13.7 of the T&Cs. It is not hidden; the user does not deny knowing the rule once pointed to it. The fee is a flat published rate, not an opaque charge.
- **Buena fe:** Lemon acted in good faith — it actually recovered and credited the asset (2,250 USDC), which it was under no obligation to do under cl. 13.7 first sentence. The user also acted in good faith (legitimate confusion). No bad-faith conduct on either side.
- **In dubio:** Not triggered — the position is not genuinely tied; Lemon has a published rule, prior email notice, and a contractual basis. The user's "should have been more visible" argument is a quality-of-UX complaint, not a violation of a binding principle.
- **Educación:** Lemon's January email is exactly the educational outreach contemplated; the user admitted to overlooking it.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Cl. 13.7's 10% recovery fee is uniformly applied, published, and corresponds to genuine operational cost/risk of recovering unsupported tokens. It does not conflict with Section A — it is a legitimate fee for an optional service (recovery of an asset the user was not supposed to send). The fee is high but it is the published, ex-ante rate, not a hidden surcharge.

## Jurisdiction / Morality / Validity
Standard consumer-protection scope; case is in-scope for the subcourt. No morality / illegality concerns.

## Schelling-Point check
The honest-juror focal point: Lemon published a 10% recovery fee in its T&Cs, sent a prior email about the delisting which the user himself eventually located, and went beyond strict cl. 13.7 by actually recovering the funds. The user's loss arises from sending a non-listed token variant despite available notice. Most diligent jurors will find that the published fee was duly disclosed and that "I would have preferred more prominent in-app notice" does not rise to a Política violation.

## Bias audit
The 10% on USD 2,500 feels emotionally steep, and there is some sympathy in that the in-app deposit screen could have been clearer about contract addresses. Set against that, the rule is openly written, the user got an email, and Lemon delivered the recovery service the fee pays for. Discounting emotional bias toward "the small user," the legal/policy answer falls with Lemon.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
Lemon's 10% recovery commission for assets sent to an unsupported network is set out in clause 13.7 of its T&Cs and is therefore not a hidden charge under the Transparencia principle. Lemon also sent a prior email notification (25 January) about the delisting, which the user himself confirmed in the support chat after searching his inbox. The token list within the app shows which tickers are supported, and cl. 13.7's first sentence in fact permits Lemon to refuse to credit unsupported transfers at all — Lemon went further and recovered/credited 2,250 USDC. That conduct is consistent with Buena fe and Educación rather than in conflict with them.

The user's strongest argument is under Información / Protección: the in-app deposit screen lists "USDC" generically without explicit contract-address or network-variant warnings, and the delisting was communicated by a single email rather than via the more visible in-app banners used for address changes. That is a legitimate UX critique, but Lemon's notice met the minimum standard required by Section A — it was timely, in writing, and the user concedes he received it. A preference for more prominent notice does not, on these facts, override a duly published and uniformly applied contractual fee.

Applying the Política's tiebreaker (In dubio pro consumidor) does not change the outcome because the matter is not genuinely tied: Lemon has the published rule, prior written notice the user accepts receiving, and a recovery actually performed. The 10% figure, while high in absolute terms, is the ex-ante published rate for an optional recovery service for a non-listed asset and is not in conflict with Section A. Vote: Favor Lemon, medium confidence — medium rather than high because the in-app deposit screen could reasonably be clearer about supported contract addresses, and a different juror could weigh Información more heavily.
