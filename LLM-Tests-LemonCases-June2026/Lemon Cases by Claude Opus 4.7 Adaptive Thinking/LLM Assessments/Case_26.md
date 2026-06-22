# Case 26 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash prepaid debit card (Visa) — disputed card transactions at Betsson2 / Astropay
**Amount in dispute:** Approximately ARS 25,818 across ~12 transactions between 11 and 21 February 2024 (Betsson2 Prov + Astropay)
**Question:** Should Lemon Cash reimburse the user for the Betsson2 / Astropay card transactions of 11–21 February 2024 as unauthorised, given Lemon's back-office records show the user personally pre-funded the wallet from their own external bank account minutes before each disputed charge?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Section A.1 — Protección al consumidor:** legitimate consumers must be protected from fraud and unauthorised debits.
2. **Política Section A.2 — Información** and **A.3 — Transparencia:** the offer/relationship "as presented" governs; hidden limits = violation.
3. **Política Section A.4 — Buena fe:** both parties must act in good faith; bad-faith claims (including fabricated fraud reports) are not protected.
4. **Política Section A.5 — In dubio pro consumidor:** tiebreaker only — applied where evidence is genuinely balanced.
5. **Política Section B — T&Cs vs Section A:** Lemon's T&C clause 5.1/5.2 (disputes with merchants are between user and merchant) can govern non-fraudulent disputes but does NOT immunise Lemon from a genuine fraud claim; conversely, where a transaction is clearly not fraudulent, clause 5.1 is consistent with rejecting the claim against Lemon.
6. Unrebutted evidence is presumed genuine.

## Burden of proof
The user, having alleged unauthorised use after a temporary loss of the card, bears the initial burden of giving a credible, internally consistent account of the fraud. Lemon, in turn, must rebut with operational evidence. Once Lemon produces objective back-office records, the user must explain or rebut them.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Narrative: card temporarily lost at workplace ~13–14 Feb, later "found on desk"; claims never used Astropay/Betsson | Self-statement | Inconsistent with timeline (charges start 11 Feb, before claimed loss) | Low |
| User | App "Movimientos" screenshots listing Betsson2 Prov and Astropay debits 11–21 Feb | Screenshot | Not disputed — confirms the debits occurred | Medium (confirms charges, not fraud) |
| User | Support-chat screenshots with "Frank": user admits no police report, no missing-card notifications enabled, denies inputting card details on new pages | Screenshot of Lemon chat | Genuine; reliance under support-chat doctrine | Medium |
| Lemon | Back-office record of VIRTUAL_DEPOSIT +1812.53 ARS on 11/2/2024 21:57 from user's own bank account (CUIT 20363767703, same name) | Back-office screenshot | Unrebutted | High |
| Lemon | Back-office record of LEMON_CARD_PAYMENT -1800 ARS to Betsson2 Prov at 22:01:19 (≈4 minutes after the deposit) | Back-office screenshot | Unrebutted | High |
| Lemon | Back-office VIRTUAL_DEPOSIT +2000 ARS on 14/2/2024 21:14:59 + matching -2000 ARS Betsson2 charge at 21:17:09 (~2 min later) | Back-office screenshots | Unrebutted | High |
| Lemon | Back-office VIRTUAL_DEPOSIT +3500 ARS on 21/2/2024 23:15:46 + matching -3500 ARS Astropay charge at 23:54:59 | Back-office screenshots | Unrebutted | High |
| Lemon | Citation of T&C clauses 5.1 and 5.2 (merchant-dispute pass-through) | Contract text | Not rebutted | Medium |

Immaterial:
- KLEROS logos and decorative elements.

## Application
- **Protección:** Genuine fraud victims must be protected, but protection does not extend to false fraud claims. The pre-funding pattern shows the user knowingly loaded the wallet to fund each disputed charge.
- **Información / Transparencia:** Lemon clearly responded via chat with a fraud-investigation checklist (5 questions). The "offer as presented" includes a fraud-investigation step that depends on consistent user statements; the user's statements are inconsistent with the on-record bank flow.
- **Buena fe:** The pre-funding from the user's own external bank account, repeatedly and minutes before each disputed transaction, is incompatible with the user's narrative (a thief would not top up the victim's Lemon wallet from the victim's own bank). Also, the disputed charges start on 11 February — before the user's claimed loss date of "13 or 14". This is a strong indicator that the claim is not made in good faith.
- **In dubio (tiebreaker):** Not engaged — Lemon's evidence is uncontradicted and decisive; the situation is not genuinely doubtful.
- **Educación:** Lemon's chat walks the user through the standard fraud-claim procedure (block card, file police report, denounce in-app); no educational failure.
- **No discriminación:** Not at issue.
- **T&C compatibility:** Clause 5.1 distinguishes fraudulent from non-fraudulent disputes; only the former trigger Lemon refunds. Here the evidence shows non-fraudulent, self-funded transactions, which under clause 5.1/5.2 are the user's matter with Betsson/Astropay — consistent with Section A because no genuine fraud is present.

## Jurisdiction / Morality / Validity
Standard Kleros consumer-protection scope. No morality/illegality issue defeating arbitrability. Dispute is justiciable; both parties submitted descargos.

## Schelling-Point check
A diligent juror reviewing this file sees: (i) the user's own bank account (same CUIT, same name) credits the wallet minutes before each disputed charge; (ii) the user offered no police report and no rebuttal to Lemon's back-office evidence; (iii) the timeline of disputed charges (from 11 Feb) precedes the user's own claimed loss date. The Schelling-point answer is to reject the claim.

## Bias audit
I am applying the consumer-protection bias correctly: Sections A.1 and A.5 protect honest consumers and resolve genuine doubt in their favour, but they do not require Lemon to refund self-initiated transactions. No identity-based bias. The user's "lost card" framing is unsympathetic only because it is contradicted by their own bank's records, not by inference. Lemon's evidence is unrebutted.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Under Política Section A, consumer protection (A.1) and in dubio pro consumidor (A.5) apply to genuine consumer claims. Here, Lemon produced unrebutted back-office records demonstrating that minutes before each disputed Betsson2 / Astropay charge, the user's own external bank account (same name, same CUIT 20363767703) made a virtual deposit into the user's Lemon wallet for a matching amount (e.g. +1812.53 ARS at 21:57 followed by -1800 ARS to Betsson2 at 22:01; +2000 ARS at 21:14:59 followed by -2000 ARS to Betsson2 at 21:17:09; +3500 ARS at 23:15:46 followed by -3500 ARS to Astropay at 23:54:59). This pre-funding pattern is inconsistent with third-party fraud — a thief would not top up the victim's wallet from the victim's own bank.

The user's narrative is further undermined by (a) disputed charges beginning 11 February, two-to-three days before the user's claimed card-loss date; (b) the absence of any police report; (c) the user's admission in the Lemon support chat that no notifications were enabled and that the card was simply mislaid on a desk. The user did not rebut Lemon's back-office evidence. Under the rule that unrebutted evidence is presumed genuine, the fraud claim fails on its face.

The buena fe principle (A.4) is decisive: protección (A.1) shields honest consumers, not contrived fraud claims. In dubio (A.5) is a tiebreaker that does not engage when the evidence is one-sided. T&C clauses 5.1–5.2 correctly route non-fraudulent merchant disputes back to the merchant, and that is compatible with Section A on these facts. Vote: Favor Lemon.
