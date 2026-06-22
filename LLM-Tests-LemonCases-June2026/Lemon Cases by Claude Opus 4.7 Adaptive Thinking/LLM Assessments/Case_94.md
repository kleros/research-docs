# Case 94 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (VISA Física *7998) — disputed point-of-sale purchase at "MERPAGO*RODIUM"
**Amount in dispute:** ARS 89,890 (purchase dated 5 March 2025, 20:11)
**Question:** Should Lemon reimburse the user for a card purchase the user claims was unintentional, allegedly triggered by clicking an Instagram-advertised website that auto-filled card data stored on his phone?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Section A** principles (in order of weight): Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. **Section B:** T&Cs that conflict with Section A yield to Section A. T&Cs are otherwise enforceable.
3. **Offer-as-presented:** Información / Transparencia are assessed against what Lemon promised at point of contracting; hidden limits → likely violation.
4. **Burden allocation:** the party seeking to disturb a completed transaction must show a defect (hidden term, fraud, platform failure, lack of consent attributable to provider). Unrebutted evidence is presumed genuine.
5. **General payments principle (background):** an authorised card transaction processed correctly is not, on its own, reversible merely because the cardholder regrets it.

## Burden of proof
The user is the claimant seeking reversal of a completed authorised card payment. He bears the burden of showing either (a) a Lemon-side failure (platform breach, undisclosed risk, breach of a Section A principle), or (b) an unauthorised transaction (fraud / third-party access). Lemon need only show the transaction was correctly authorised against the user's registered card.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon "Actividad" screenshot showing ARS 89,890 charged 05/03/2025 20:11 to VISA Física *7998, merchant MERPAGO*RODIUM, status "Completo / Pago realizado con éxito" | Primary (own-account screenshot) | No | High (confirms the transaction occurred and was authorised on his card) |
| User | Narrative: clicked Instagram-advertised site by mistake; card details stored on phone auto-filled; no conscious confirmation | Secondary (self-statement, no corroborating evidence — no URL, no merchant chargeback claim, no fraud report, no screenshot of the offending site) | Effectively rebutted by Lemon's back-office record showing a normal MercadoPago card-not-present transaction | Low |
| Lemon | Back-office record: TrxID 7579b3ba-8c5f-4ec2-ad65-0c91628cdc25, "LEMON_CARD_PAYMENT — Completada", -ARS 89,890, Lemon Card 7998 PHYSICAL, merchant MERPAGO*RODIUM, user Emiliano Torresi ID 729280 | Primary (internal system of record) | No | High |
| Lemon | Verified Instagram profile screenshot showing the only official Lemon account is `lemoncash.app` | Primary | No | Medium (shows the offending Instagram ad was NOT a Lemon channel — relevant to defeating any "Lemon-published advert" theory) |
| Lemon | T&C clause invoked: user is sole responsible for custody and use of his payment instruments; no prior unauthorised-use report or block request was made | Secondary (asserted, not attached) | Unrebutted | Medium |

Immaterial:
- User's invocation of "publicidad engañosa" — the allegedly deceptive ad was on a third-party Instagram account, not Lemon's. Lemon does not author third-party merchant ads and the user did not identify the merchant/site as a Lemon-controlled property.
- User's "autocompletar" argument — auto-fill is a device/OS-level feature managed by the user, not a Lemon offer or interface.

## Application
- **Protección al consumidor:** Protection covers consumers against provider-side abuse, hidden risks, and unauthorised access. Here the transaction was authorised on the user's own registered physical card via a standard MercadoPago merchant processor. No Lemon-side abuse, no third-party intrusion, no platform vulnerability alleged with evidence. Protección is not breached.
- **Información:** No Lemon information failure is alleged. The user does not point to any Lemon-published statement about Lemon Card that was misleading or omitted. The offer-as-presented (a VISA card that pays merchants when used) operated exactly as advertised.
- **Transparencia:** The transaction shows up immediately in "Actividad" with merchant, amount, card and TrxID. That is in fact a high-transparency record. The user's own screenshot is the disclosure he is complaining was missing.
- **Buena fe:** No bad faith by Lemon shown. User's good faith is accepted but irrelevant to whether Lemon must refund a correctly authorised card payment to a third-party merchant.
- **In dubio pro consumidor:** Tiebreaker only — applies when after weighing evidence the case is genuinely balanced. It is not balanced here: Lemon has primary system evidence; the user has only an unsupported self-narrative of accidental clicking. No tie to break.
- **Educación:** Not engaged.
- **No discriminación:** Not engaged.
- **T&C vs Section A:** Lemon invokes a custody-of-payment-instrument clause. That clause does not conflict with Section A — Section A does not require an issuer to refund a cardholder who voluntarily allowed his device to auto-fill card data on a third-party merchant site. The clause is compatible with Section A and operative.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (consumer claim against an Argentine crypto/fintech provider). No morality trigger. Question is well-formed and answerable on the materials.

## Schelling-Point check
A panel of diligent jurors will see: (1) primary transaction record consistent across both parties' screenshots; (2) the alleged "deceptive ad" was on a third-party Instagram, not Lemon's verified account; (3) the user describes a self-inflicted accidental click on his own device with his own stored card data; (4) no fraud, no platform failure, no Lemon misrepresentation. The convergent answer is Favor Lemon. A claim of "unintentional purchase on an external merchant" is essentially buyer's remorse vis-à-vis Lemon — chargeback remedies lie with the card network / merchant dispute mechanism, not as a Section-A reversal against the issuer.

## Bias audit
No sympathy bias: the user's narrative is plausible but unsubstantiated and, even if fully true, does not implicate Lemon. No anti-fintech bias: ruling rests on uncontested transaction facts, not on Lemon's identity. In dubio is not a thumb-on-scales tool when one side has primary records and the other has only self-assertion.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user seeks reversal of an ARS 89,890 Lemon Card purchase at merchant MERPAGO*RODIUM on 5 March 2025, alleging he reached the merchant site through a deceptive Instagram ad and that his phone's auto-fill completed the payment without conscious confirmation. Both parties' evidence agrees on the underlying facts: the transaction was correctly authorised against the user's registered VISA Física *7998, processed by MercadoPago, and recorded with a matching Trx ID on both sides. There is no allegation of platform failure, no third-party intrusion, and the Instagram source was not a Lemon-controlled channel — Lemon's only verified Instagram is `lemoncash.app`, which the user does not claim to have interacted with.

Under Política Section A, Protección al Consumidor shields users from provider abuse, undisclosed risks, and unauthorised access — none of which is present. Información and Transparencia are assessed against the offer Lemon presented; the user identifies no Lemon misrepresentation, and the in-app activity log is itself a transparent disclosure of the operation. Buena fe by the user is accepted but does not by itself entitle him to reimbursement by the issuer for a voluntary card-not-present payment to a third-party merchant. In dubio pro consumidor is a tiebreaker and does not apply: the evidentiary record is one-sided in Lemon's favour, with primary transactional records unrebutted and the user offering only an unsupported narrative.

The Lemon T&C clause placing custody of payment instruments on the user does not conflict with Section A and is therefore enforceable. The correct remedy for a cardholder claiming a misleading external merchant lies with merchant-side or card-network chargeback procedures, not with a Section-A reversal against Lemon. Accordingly the vote is Favor Lemon.

---

Case 94 | VOTE: Favor Lemon | CONFIDENCE: high | Authorised card payment to external merchant via user's own stored card; no Lemon failure, misrepresentation, or fraud — Section A not breached.
