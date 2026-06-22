# Case 56 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Cash crypto withdrawal flow — user sent 0.008528218682358447 WETH from Lemon to an external address using the in-app "Retiro de Ethereum" screen; funds did not arrive in their Lemon account / were lost.
**Amount in dispute:** ARS $39,612 (~0.0085 WETH, ~USD $30 at mid-2024)
**Question:** Should Lemon compensate the user for a WETH withdrawal that was executed through Lemon's own "Retiro de Ethereum" flow, given that Lemon now invokes T&C 13.7 to disclaim responsibility for unlisted assets?

## Options
- **Favor User** — Lemon must compensate / refund.
- **Favor Lemon** — Claim rejected; user bears the loss.
- **Refuse to Arbitrate** — Question malformed, immoral, or out of jurisdiction.

## Governing rules
1. **Política Sección A.1 — Protección del consumidor:** Lemon owes the user the protective standard owed by a financial-services provider to a (presumed weaker) consumer.
2. **Sección A.2 — Información:** The information actually displayed by the platform must be sufficient and accurate; the offer/UI as presented governs.
3. **Sección A.3 — Transparencia:** Material limits (e.g., that an apparently-supported operation is in fact unsupported) must be clearly disclosed at the point of transaction.
4. **Sección A.4 — Buena fe:** Both parties owe each other good faith; Lemon cannot label a flow "Retiro de Ethereum", process it, show "Con éxito" and then deny that it occurred under its remit.
5. **Sección A.5 — In dubio pro consumidor:** Tiebreaker — in genuine doubt, decide for the user.
6. **Sección A.6 — Educación:** Lemon's educational materials are relevant but do not substitute for clear, contextual disclosure inside the transaction flow itself.
7. **Sección A.7 — No discriminación:** Not engaged on these facts.
8. **Sección B — T&Cs vs Sección A:** Where a T&C clause (here, 13.7 "Activos Digitales No Listados") would defeat a Sección A right, Sección A prevails. A catch-all immunity clause does not override Información / Transparencia / Buena fe.

## Burden of proof
Lemon, as the party invoking an exclusionary T&C clause to defeat a consumer protection claim, must show (i) the limit was clearly and contextually disclosed and (ii) the user's loss is attributable to user error rather than to an apparently-supported flow inside Lemon's UI.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of Lemon app: header "Retiro de Ethereum", ETH logo, "$ 39,612", "Con éxito", destination 0xd2...30aa, "Cantidad de tokens — 0.008528218682358447 WETH", "Costo de la transacción — $0 gratis", dated jul 24 2024 12:23 | Primary (in-app artefact) | No | High |
| Lemon | Quotation of T&C 13.7 — unlisted Digital Assets sent in error cannot be reflected; company not obliged to operate unlisted assets | Primary (contractual text) | No | High |
| Lemon | Reference to Lemon EDU educational portal | Secondary | Partially — does not show contextual in-flow disclosure | Low |
| Lemon | "Novedades" screenshot listing supported tokens (BTC, ETH, ADA, AVAX, BNB, DOT, MATIC, SOL, NEAR, ALGO, FTM, DOGE, TRX, LTC, XLM, LUNA, USDC, USDT, DAI, PAXG, AAVE, UNI, ENS, OP, ARB) — WETH not present | Secondary | No, but probative weight limited | Medium |

Immaterial:
- User's appeal to long-standing customer status — emotional/identity, not material to rule application.

## Application
- **Protección:** The user is a retail consumer and Lemon a regulated-style platform — protective standard applies.
- **Información:** The user's screenshot shows Lemon's own UI labelled the operation "Retiro de **Ethereum**" while the underlying token field reads "WETH". This is an internally inconsistent representation by Lemon's platform. An average user reading "Retiro de Ethereum" with the ETH octahedron icon and a "Con éxito" green tick would reasonably believe they had withdrawn ETH on a supported flow. Information actually presented was misleading.
- **Transparencia:** Lemon points to a generic "Novedades" listing showing ETH but not WETH. However, the in-flow UI did not contextually warn the user that WETH is distinct from ETH or that proceeding would result in irrecoverable loss. The limit (no support for WETH) was not transparently disclosed at the decisive moment — it was hidden behind a flow that displays Ethereum branding.
- **Buena fe:** Lemon's defence ("the user sent an unlisted token to a non-Lemon address") is in tension with its own screenshot evidence. If WETH were truly unsupported, the platform should not have produced a confirmation screen titled "Retiro de Ethereum" displaying a WETH token quantity with "$0 gratis" gas. Good faith requires reconciling that contradiction; Lemon does not.
- **In dubio:** Even if the factual picture were genuinely balanced, the consumer tiebreaker would apply. Here it is not strictly needed — the imbalance already favours the user.
- **Educación:** A general EDU portal does not satisfy point-of-transaction disclosure obligations under Información/Transparencia. Lemon cannot displace its contextual disclosure duty onto a separate educational site.
- **No discriminación:** Not engaged.
- **T&C compatibility (Sección B):** T&C 13.7 is a catch-all immunity for unlisted-asset errors. Per Sección B, such a clause cannot override Sección A's Información, Transparencia and Buena fe duties. The clause is also conditioned on the premise that the user committed the error unaided — that premise is not made out where Lemon's own UI labelled and processed the operation as a successful Ethereum withdrawal.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica, consumer/exchange dispute). No morality concerns. Question is well-formed and answerable.

## Schelling-Point check
A diligent panel reading these two short descargos will notice the same anomaly: Lemon's own screenshot caption "Retiro de Ethereum" displaying a WETH quantity with a green success tick. The Schelling-focal reading is that the platform itself blurred the ETH/WETH boundary in the very flow now disclaimed. Combined with the Sección B rule that T&Cs cannot defeat Sección A, this points to Favor User. It is the simpler, more literal reading.

## Bias audit
I deliberately set aside (i) the small absolute amount, (ii) the user's "long-time customer" appeal, and (iii) any sympathy for either party. The decisive lever is documentary: Lemon's own UI screenshot, unrebutted, contradicts Lemon's "unlisted asset, nothing we can do" framing. The decision would be the same at any monetary amount.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification (English)

The decisive evidence is Lemon's own in-app screenshot submitted by the user: a withdrawal screen titled "Retiro de Ethereum", branded with the ETH icon, showing "Con éxito" and a token-quantity field reading "0.008528218682358447 WETH" — produced and processed by Lemon's platform on 24 July 2024. Lemon's descargo does not rebut, explain, or even acknowledge this internal inconsistency; under standard Kleros practice unrebutted documentary evidence is presumed genuine. A reasonable consumer reading "Retiro de Ethereum" with a green success tick would believe they had executed a supported Ethereum withdrawal, not an irrecoverable transfer of an unlisted token.

Under Sección A of the Política de Resolución de Disputas, Información (A.2) and Transparencia (A.3) require that material limits — here, that WETH is unsupported and that proceeding would result in total loss — be disclosed clearly at the point of transaction, not solely via a separate "Novedades" or "Lemon EDU" page. Buena fe (A.4) forbids invoking those limits ex post when the platform's own UI presented the operation as a supported Ethereum withdrawal. Sección B is explicit that a T&C clause cannot override Sección A; T&C 13.7's catch-all immunity for unlisted-asset errors therefore cannot defeat the consumer's Información/Transparencia claim on these facts. Even disregarding Sección B, the in dubio pro consumidor tiebreaker (A.5) would resolve any remaining doubt for the user.

I vote **Favor User** with medium confidence. Confidence is not high because the policy text on the user side is more applicable than the contractual immunity, but the dispute is small in value and a panel could plausibly weight the "Novedades" list more heavily than I have; nonetheless, the Schelling-point reading turns on Lemon's own screenshot, and that points one way.

---

**Case 56 | VOTE: Favor User | CONFIDENCE: medium | Lemon's own UI labelled the flow "Retiro de Ethereum" with success tick while processing WETH; Sección A (Información/Transparencia/Buena fe) overrides T&C 13.7.**
