# Case 49 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash wallet — display of total balance (ARS-denominated) when underlying crypto assets (BTC, ETH) appreciate
**Amount in dispute:** ~99,689.83 ARS apparent balance reduction (3,066,824.47 ARS → 2,967,134.64 ARS) over the period sampled
**Question:** Has Lemon Cash violated the consumer-protection policy because the user's total ARS balance fell from ~3.1M to <3M even though BTC and ETH spot prices rose ~6%?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección al consumidor** — duty to protect the user from harm caused by Lemon.
2. **Información** — duty to provide accurate, sufficient information about the product and its mechanics.
3. **Transparencia** — operating mechanics (especially price/conversion logic) must be transparent and accessible.
4. **Buena fe** — both parties act in good faith; obvious misunderstandings should be addressed honestly.
5. **In dubio pro consumidor** — tiebreaker only, where genuine ambiguity persists.
6. **Educación** — duty to facilitate consumer financial education.
7. **No discriminación** — not in issue.
8. **T&Cs vs Section A** — T&Cs cannot override the seven Section A principles.

## Burden of proof
User alleges a discrepancy / mis-accounting by Lemon. The burden is on the user to show that the displayed balance is wrong or that Lemon failed to disclose how the balance is computed.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot at 10:33: balance 3,066,824.47 ARS; BTC +5.28% (1,776,708.98 ARS), ETH +5.09% (1,290,115.49 ARS); holdings 0.0204004 BTC and 0.27741189 ETH | Secondary (screenshot) | No | Medium |
| User | Screenshot at 4:47: balance 2,967,134.64 ARS; BTC +6.38% (1,718,501.78 ARS), ETH +6.97% (1,248,632.86 ARS); holdings identical | Secondary (screenshot) | No | Medium |
| Lemon | Reference to public Lemon tweet (https://x.com/lemonapp_ar/status/1786757417289625840) explaining that the total ARS balance varies because crypto assets are valued in USD and then converted to ARS — so the ARS balance also reflects USD/ARS exchange-rate movement | Secondary (public communication) | No | High |
| Lemon | Argument that the user is reading USD-denominated assets through their ARS quotation, ignoring USD/ARS variation | Argument | No | High |

Immaterial:
- "Motivo del reclamo: Otros" — procedural label, no substantive content.

## Application
- **Protección:** No harm shown. Holdings of BTC and ETH are identical across the two screenshots (0.0204004 BTC, 0.27741189 ETH). Lemon has not subtracted any asset; only the ARS valuation of those unchanged crypto holdings has moved. The user's actual asset position is unchanged.
- **Información:** The app discloses the individual asset positions, their unit prices, and the ARS conversion. The percentage figures shown (e.g. BTC "+5.28%", "+6.38%") are clearly per-asset price moves, not portfolio P&L. The information necessary to understand the displayed numbers is present on-screen.
- **Transparencia:** Lemon points to a publicly available explanation (the linked tweet) clarifying that the ARS total reflects both crypto price changes and ARS/USD exchange-rate changes. In Argentina, where the peso is volatile, an appreciating peso (or a falling USD/ARS rate) will reduce the ARS valuation of an unchanged USD-equivalent portfolio even if BTC/ETH rise in USD. This is the only coherent explanation for the screenshots: BTC unit value in ARS actually fell (1,776,708.98 → 1,718,501.78) despite BTC being "up" in percentage terms — consistent with USD-to-ARS depreciation of the peso quote. The mechanic is transparent on its face.
- **Buena fe:** Lemon engaged with the technical question and pointed to its prior public explanation. The user has not alleged any specific missing transaction or any hidden deduction.
- **In dubio pro consumidor:** Not engaged. There is no genuine ambiguity — the numbers are internally consistent and the explanation (FX cross-rate) fully accounts for the apparent gap.
- **Educación:** Lemon has published explanatory material on how the total balance is computed. The user appears to be misunderstanding portfolio quotation in a fiat reference currency, which is a financial-literacy gap, not a platform fault.
- **No discriminación:** Not in issue.
- **T&C compatibility:** No T&C clause is invoked or needed; this is an arithmetic / quotation question, not a contractual carve-out.

## Jurisdiction / Morality / Validity
Pass. Consumer-protection claim against an Argentine crypto wallet — correct subcourt. No morality issues. Question is well-formed.

## Schelling-Point check
A diligent panel reading the same two screenshots will see that crypto holdings are unchanged and that the ARS quote of those holdings has fallen — clearly explainable by ARS/USD movement. The obvious reading is that there is no error, no missing balance, and no policy breach. Convergence: Favor Lemon.

## Bias audit
The user is sympathetic (perceived loss feels real) but the on-screen numbers show no asset taken. I have not weighted rhetorical framing — only the arithmetic and Lemon's unrebutted explanation.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user alleges that Lemon's ARS-denominated total balance fell from ~3.07M to ~2.97M despite BTC and ETH being up ~6%. The two screenshots the user supplied, however, show identical crypto holdings at both moments (0.0204004 BTC and 0.27741189 ETH). No asset has been removed, and no transaction has been alleged. What changed is only the ARS quotation of those unchanged holdings — notably, the per-unit BTC valuation in ARS fell from 1,776,708.98 to 1,718,501.78. This is incompatible with BTC simply having risen, and is straightforwardly explained by movement in the USD/ARS cross-rate: Lemon prices crypto in USD and then displays it in ARS, so an appreciating peso (or weaker USD against ARS) reduces the ARS total even when crypto is up in USD terms.

Under Section A of the consumer-protection policy, Información and Transparencia require that the mechanics of the displayed balance be available to the user. Lemon's app shows each asset's unit price, holding size, and percentage move, and Lemon has pointed (unrebutted) to a public explanation of how the total balance is composed (the cited tweet). The principle of Protección is not engaged because the user has not lost any asset — only the fiat quotation of an unchanged USD-equivalent portfolio has moved, which is intrinsic to holding volatile crypto in a volatile fiat reference. Buena fe and Educación support Lemon's position: Lemon has published the explanation, and the user's complaint reflects a financial-literacy gap rather than a platform malfunction.

In dubio pro consumidor is a tiebreaker and is not triggered here, because there is no genuine ambiguity once the screenshots are read against the FX-cross-rate explanation. A panel of diligent, policy-literate jurors will converge on the conclusion that no Section A principle has been breached. Vote: Favor Lemon.
