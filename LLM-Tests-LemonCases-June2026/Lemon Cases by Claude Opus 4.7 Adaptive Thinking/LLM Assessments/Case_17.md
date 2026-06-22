# Case 17 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Cash-In of UXD (Ripio's stablecoin) from Ripio to a Lemon USDC deposit address on Polygon network.
**Amount in dispute:** ~400 UXD (approx. USD 400)
**Question:** Must Lemon credit / refund ~400 UXD that the user deposited to a Lemon USDC-only Polygon address, where UXD is a non-listed token Lemon never advertised?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Section A.1 Protección** — protect users in clearly asymmetrical situations.
2. **A.2 Información / A.3 Transparencia** — the offer "as presented" governs; hidden limits violate, clear limits bind.
3. **A.4 Buena fe** — both parties must act in good faith.
4. **A.5 In dubio pro usuario** — tiebreaker only.
5. **A.6 Educación financiera** — user is responsible for understanding products they use.
6. **Section B compatibility** — T&Cs (cl. 13.7) cannot override Section A but, if clearly disclosed pre-transaction, are compatible.

## Burden of proof
User must show that Lemon's offer "as presented" reasonably led him to expect UXD would be credited or recoverable. Lemon must show clear pre-transaction disclosure of the network/token restriction.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Ripio screenshot showing 400 UXD sent via Polygon on 31/12/2023 to address 0x66c6...7efe | Screenshot | Not rebutted — but address does not match Lemon's deposit address shown in Lemon's screenshot (0x48ba...bcd39) | Medium — confirms transfer, but raises a destination question |
| User | Assertion that "industry standard" is to refund mis-sent funds | Bare assertion | Not substantiated | Low |
| Lemon | Lemon Cash-In screen for USDC clearly stating: "Asegurate de depositar USDC desde la red Polygon. De lo contrario, perderás tus fondos" with Polygon badge | Screenshot | Not rebutted | High — pre-transaction warning |
| Lemon | T&C cl. 13.7: non-listed tokens / wrong network → funds not reflected, no obligation to operate non-listed assets | T&C citation | Not rebutted | High |
| Lemon | "Novedades" listing of supported tokens — UXD absent; in-app token search available | Screenshot | Not rebutted | Medium-High — UXD demonstrably not listed/promoted |
| Lemon | Statement that recovery cost from provider exceeds claim amount | Assertion | Not rebutted | Low-Medium |

Immaterial:
- User's bank-analogy argument — not a legal/contractual rule, just rhetoric.
- "Industry standard refund" claim — no evidence supplied.

## Application
- **Protección:** User chose to send a Ripio-proprietary stablecoin (UXD) to a Lemon address that the deposit screen explicitly labelled as USDC-only. Protección does not extend to losses caused by ignoring an explicit pre-transaction warning.
- **Información:** Lemon's deposit screen plainly stated the asset (USDC) and network (Polygon). UXD never appeared in Lemon's listed tokens. Information requirement met.
- **Transparencia:** The "offer as presented" was "deposit USDC on Polygon" — not "deposit any Polygon token." The limit was visible, not hidden. Transparencia satisfied.
- **Buena fe:** User acted carelessly but not in bad faith; Lemon's refusal to credit a non-listed token is consistent with disclosed rules. Lemon's claim that recovery is uneconomic is plausible and unrebutted. No bad faith shown either side, though user's "stafa" framing is overstated.
- **In dubio:** Not engaged — facts are not in equipoise; the disclosure is clear.
- **Educación:** A reasonable user of crypto wallets is responsible for verifying that the destination platform supports the token being sent. The in-app token list and warning screen gave the means to verify.
- **No discriminación:** Not implicated.
- **T&C compatibility (Section B):** Cl. 13.7 is compatible with Section A because the restriction is clearly disclosed at the moment of deposit, not hidden in fine print contradicting an advertised offer.

## Jurisdiction / Morality / Validity
Standard consumer-protection / crypto-deposit dispute. Within subcourt scope. No RtA basis. Note: the destination address on the user's Ripio screenshot (0x66c6...7efe) does not match the Lemon USDC address (0x48ba...bcd39) — possible the user even sent to a different address entirely, which would further weaken his case, but I do not need to resolve this to decide.

## Schelling-Point check
Most reasonable, policy-literate jurors will see: (i) UXD is a Ripio-proprietary token never listed at Lemon; (ii) Lemon's deposit screen explicitly warned that anything other than USDC on Polygon would be lost; (iii) the T&C clause is congruent with the in-app warning. The convergent honest vote is Favor Lemon.

## Bias audit
Sympathy pull: user lost real money and the sum is modest. Counter-pull: ruling for him would create a strict-liability regime for exchanges receiving any token on a shared chain — that is not the rule. I am applying the disclosed-offer principle, not punishing the user.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Under Política Section A, the offer "as presented" governs Información and Transparencia. Lemon's Cash-In screen for USDC displayed the Polygon network badge and an explicit warning: "Asegurate de depositar USDC desde la red Polygon. De lo contrario, perderás tus fondos." UXD never appeared in Lemon's published list of supported tokens, and an in-app token search was available. The limit on what Lemon would credit was therefore clearly disclosed pre-transaction, not hidden. T&C cl. 13.7 mirrors that on-screen warning and is compatible with Section A under Section B.

The user's transfer of a Ripio-proprietary stablecoin (UXD) to a Lemon address advertised as USDC-only falls squarely within the disclosed exclusion. The user's "industry standard refund" argument is unsupported by evidence, and his bank-analogy ignores that Lemon's screen specifically warned this exact failure mode. Protección does not require an operator to credit a non-listed token where the user was explicitly warned. Educación financiera places the verification burden on the user, who had the listings and the warning at hand.

In dubio pro usuario is a tiebreaker only and is not engaged because the disclosure is unambiguous. Lemon's unrebutted statement that provider-side recovery would cost more than the claim is plausible and does not establish bad faith. The Schelling-convergent honest vote is Favor Lemon.
