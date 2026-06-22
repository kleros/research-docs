# Case 36 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (VISA Física *3809) — disputed/unrecognised charge on Google Play Store
**Amount in dispute:** ARS 45.876,30
**Question:** Must Lemon refund the user for an alleged unauthorised Google Play Store debit on the Lemon Card, or is the user responsible because the operation does not present fraud patterns and the user has prior consumption history with the same merchant?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección** — Section A.1.
2. **Información / Transparencia** — Section A.2 & A.3 (offer as presented).
3. **Buena fe** — Section A.4.
4. **In dubio pro usuario** — Section A.5 (tiebreaker only).
5. Section B: T&Cs subordinate to Section A; catch-all immunity ≠ override.
6. Card-network chargeback rules (governing card-not-present disputes via Visa) form the operational backdrop, but Section A governs Lemon's duty toward its user.

## Burden of proof
The user must establish prima facie that the charge was not authorised. Once asserted with corroborating circumstances, Lemon — as the issuer holding the transactional evidence — bears the burden to show either (a) the user authorised the charge, (b) clear policy basis for refusing the chargeback, and (c) that it discharged its duty of información/transparencia in handling the dispute.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Movimientos screenshot showing ARS 45.876,30 charge to GOOGLE *PlayStore on 04/06/2024 09:25 | Screenshot | No | Confirms transaction occurred; neutral as to authorisation |
| User | Statement that Google cannot locate purchase because not linked to user's email; Visa says card not registered | Assertion | Not rebutted by Lemon | Medium — supports unauthorised-charge narrative |
| User | Lemon initially "resolved" reclamo but reversed after 10 days citing prior similar incident | Assertion | Not directly rebutted | Medium — suggests inconsistent handling |
| Lemon | Fraude team analysis: no fraud patterns, no multiplicity of suspicious consumption, card in user's possession | Internal analysis | Partially — user disputes the conclusion | Medium |
| Lemon | SQL table showing one prior PlayStore charge on 31/05/2023 (ARS 13.414,68) | Database extract | Not rebutted | Medium — user has prior consumption on same platform |
| Lemon | Second SQL table showing recurring YouTube Premium charges + goodnovel via Google | Database extract | Not rebutted | High — clear pattern of established Google billing relationship on this card |

Immaterial:
- User's suggestion that Lemon implement opt-in/opt-out per purchase — policy proposal, not adjudicative.
- Generic complaint about being "embarrassing" — emotional, not probative.

## Application
- **Protección:** Lemon has a duty to protect users from unauthorised charges, but protection is not absolute — it must be calibrated to actual evidence of fraud. Here the operational indicators (card in possession, no multiplicity of disputed charges, no rejection cluster) cut against a fraud finding.
- **Información:** Lemon explained its reasoning to the user (referred to merchant/Visa; cited prior similar incident; provided fraud-analysis conclusion). The explanation is not opaque.
- **Transparencia:** Lemon disclosed why it reversed the initial resolution. The "incidente similar el año pasado" reference is somewhat oblique but is consistent with the SQL evidence showing prior Google billing on the same card.
- **Buena fe:** Lemon's process — fraude review, referral to merchant for what is properly a merchant dispute — is consistent with good faith. The user has an active, ongoing Google billing relationship on this card (recurring YouTube Premium for ~12 months, plus prior PlayStore charge), which makes a pure card-data-theft narrative implausible without further evidence.
- **In dubio:** Tiebreaker only. The evidence here is not in equipoise — Lemon's evidence (recurring Google charges on the same card, no fraud markers, card in user's possession) materially outweighs the user's bare assertion that Google cannot find the purchase. The user offers no evidence of compromised credentials, no police report, no IP/device anomaly, no contemporaneous fraud-alert evidence.
- **Educación:** Lemon's response correctly identifies this as a merchant dispute (not a card-fraud dispute) and directs the user to the appropriate channel.
- **No discriminación:** Not implicated.
- **T&C compatibility:** Standard card-issuer terms allocating merchant disputes to the merchant are compatible with Section A where, as here, the evidence does not support unauthorised use.

## Jurisdiction / Morality / Validity
Valid consumer-protection dispute. No grounds to RtA.

## Schelling-Point check
A diligent juror would observe: (i) recurring Google billing relationship over 12+ months on this card; (ii) no fraud patterns; (iii) card never lost; (iv) user offers no evidence beyond "Google can't find it on my email" — but Google billing can be tied to a different Google account using the same card. The Schelling outcome is that this is a merchant dispute, not a fraud chargeback, and Lemon's refusal is reasonable.

## Bias audit
Resisted the pro-user pull from "small consumer vs. big fintech" framing. The user's narrative has surface appeal (sudden large charge, support runaround) but does not survive the unrebutted database evidence of an ongoing Google billing relationship on the disputed card. In dubio does not rescue a claim where the evidence is asymmetric against the user.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
The user alleges an unauthorised ARS 45.876,30 debit to Google Play Store on 04/06/2024 and seeks reversal. Lemon's unrebutted database evidence shows the same Lemon Card has been billing Google services for over a year — recurring monthly YouTube Premium charges from June 2023 through May 2024, plus a prior PlayStore charge in May 2023 and a goodnovel charge in June 2023. The disputed charge fits within an established, ongoing merchant relationship, not a fraud pattern. The user offers no evidence of credential compromise, device anomaly, lost card, or contemporaneous fraud alerts; only a bare assertion that Google cannot locate the purchase on his email — which is consistent with the purchase having been made via a different Google account billed to the same card.

Under Section A.1 (Protección) and A.4 (Buena fe), Lemon must protect users from genuine unauthorised use, but protection is calibrated to evidence. Lemon performed a fraude review, found no fraud markers (card in possession, no multiplicity, no rejection cluster), and correctly characterised this as a merchant dispute properly directed to Google. Información (A.2) and Transparencia (A.3) were satisfied: Lemon explained its reasoning, including the reference to prior similar consumption on the same platform. In dubio (A.5) is a tiebreaker and does not apply where the evidentiary balance is materially asymmetric against the user.

Vote: Favor Lemon, confidence medium. Medium rather than high because Lemon's first-pass "resolved" then reversed handling is procedurally suboptimal and the merchant-dispute referral could have been more clearly documented to the user — but the substantive outcome is correct on the record.
