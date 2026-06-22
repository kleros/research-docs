# Case 65 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Cross-chain deposit / withdrawal of ETH from World App to Lemon via the Optimism network. The asset arrived in Lemon's receiving address as WETH (Wrapped ETH), which is not on Lemon's listed-asset menu.
**Amount in dispute:** 0.00392105 WETH (≈ USD 9.54 / approx. S/ 35.64) at the time of the transaction.
**Question:** Must Lemon credit / restore the user's funds when the user sent ETH from World App and the underlying transfer was delivered as WETH (an unlisted token) on Optimism?

## Options
- Favor User — Lemon must credit / return the equivalent value of the funds (or otherwise restore them).
- Favor Lemon — Reclamo rechazado; per T&C 13.7, Lemon has no obligation to credit unlisted assets.
- Refuse to Arbitrate — only if jurisdiction, morality, or validity fails.

## Governing rules
1. **Política Sección A** (overrides T&Cs where they conflict): (1) Protección del usuario, (2) Información clara y veraz, (3) Transparencia, (4) Buena fe, (5) In dubio pro usuario — TIEBREAKER ONLY, (6) Educación financiera, (7) No discriminación.
2. **Sección B**: T&Cs apply only where compatible with Sección A.
3. **Lemon T&C 13.7 — Activos Digitales No Listados**: when a user sends, by mistake, digital assets that are not listed on the platform, or via an unlisted network, those assets cannot be reflected in their account; the user understands and accepts that Lemon only provides service for Listed Digital Assets and is not obliged to permit operation of unlisted assets.
4. **Offer-as-presented governs Información/Transparencia**: hidden limitations = likely violation; clear limitations + user failure = claim fails.
5. **Unrebutted evidence is presumed genuine**; support-chat confirmations create reliance.

## Burden of proof
The user is seeking a change to the default state (recovery of an unlisted asset deposit) and therefore bears the burden of showing that Lemon's published offer / asset list misled them, or that the loss was within Lemon's control. Lemon, in turn, bears the burden of showing that its listed-asset menu and supported-networks information were clearly published before the transaction.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | World App "Retiraste Ethereum" confirmation screen — shows ETH withdrawal labelled as "Ethereum" but with the asset row reading "WETH 0.00392105" | Primary (screenshot, on-chain matched) | No | High — shows asset actually delivered was WETH |
| User | On-chain explorer (Optimism): tx 0x7a25...8733, ERC-20 transfer of 0.003921049614480952 WETH (contract 0x4200...0006, Optimism canonical WETH) to user's Lemon-controlled address 0x2C4D...a189 | Primary (on-chain) | No | High — confirms WETH, not ETH, was the asset delivered |
| User | Support chat with "Iván" (Lemon) — Lemon staff confirms WETH is not listed and that Lemon cannot recover the funds | Secondary (screenshot, but matched by Lemon's own copy) | No (Lemon submits same chat) | High |
| User | Argument: WETH conversion was automatic, outside user's control, and a common cross-chain interoperability behaviour | Argumentative | Not directly rebutted by Lemon but contradicted by Lemon's T&C 13.7 | Medium |
| Lemon | T&C 13.7 — unlisted-asset clause | Primary (contractual) | No | High |
| Lemon | Screenshot of Lemon "Novedades" supported-tokens panel showing listed Blockchains, Stablecoins, dApps and Capa 2 de Ethereum (OP, ARB) — WETH is NOT listed; the asset "ETH" is listed | Primary (offer-as-presented) | No | High |
| Lemon | Lemon Wiki page on cryptocurrency education ("APRENDE TODO SOBRE CRIPTOMONEDAS") | Secondary (educational resource) | No | Low–medium — relevant to Educación but generic |

Immaterial:
- World App's behaviour wrapping ETH into WETH on Optimism is a third-party app design choice; not under Lemon's control and not promised away by Lemon.
- Total fiat value (S/ 35.64) — not decisive; rules turn on the asset/token type, not the amount.

## Application
- **Protección:** The user did suffer a loss, but the loss arose from a third-party (World App) wrapping ETH to WETH on send. Lemon's protection duty does not extend to receiving assets it has never offered to support. Lemon's published list does not include WETH.
- **Información:** Lemon's "Novedades" panel (offer-as-presented) clearly lists which tokens are supported — ETH is listed, WETH is not. Capa 2 de Ethereum support is shown only for OP and ARB tokens, not for arbitrary tokens on Optimism. The published offer is not silent on this point.
- **Transparencia:** T&C 13.7 is explicit, public, and on-topic for exactly this fact pattern. It is not a hidden catch-all; it is a specific clause about unlisted assets. Combined with the public token list, the limitation was disclosed up-front.
- **Buena fe:** Lemon responded promptly through support, explained why recovery was not possible, and provided educational links. No evidence of bad-faith conduct, evasion, or after-the-fact rule changes.
- **In dubio pro usuario:** TIEBREAKER ONLY. There is no real interpretive tie here — both the published asset list and T&C 13.7 squarely cover the scenario. In dubio does not fire.
- **Educación:** Lemon points to its Wiki and help-centre articles on deposits, networks, and risks; the user is expected to verify the receiving asset type before sending, especially when bridging from World App to Optimism.
- **No discriminación:** Not engaged.
- **T&C compatibility with Sección A:** T&C 13.7 is compatible with Sección A. It is not a catch-all immunity; it addresses a narrowly defined operational reality (Lemon cannot custody an asset whose contract it has not integrated). Holding Lemon liable for any token a user might accidentally bridge to its address would amount to mandating unlimited custody of unknown contracts — which is operationally impossible and not required by any Sección A principle.

## Jurisdiction / Morality / Validity
Pass. Standard "Blockchain No Técnica" Lemon dispute. No morality issue. Question is well-formed and answerable.

## Schelling-Point check
A panel of diligent, policy-literate jurors would converge on Favor Lemon: the asset received (WETH) is genuinely not on Lemon's published supported list; T&C 13.7 addresses this exact scenario; the cause of the wrapping was World App's behaviour on Optimism, which is outside Lemon's offer. The user's "automatic conversion was outside my control" argument is sympathetic but does not put the obligation on Lemon — it puts it on the sending wallet (World App). The offer-as-presented (token list + 13.7) was clear and the user-side step (verifying the receiving asset) failed.

## Bias audit
Sympathy bias toward the user (small amount, unfamiliar wrapping behaviour) was considered and set aside. The decision rests on the published supported-asset list, T&C 13.7's direct on-point coverage, and the absence of any concealed or contradictory term. No reliance on party identity or polish.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user withdrew funds from World App to a Lemon-controlled address on Optimism. The on-chain explorer and the user's own World App screen both confirm the asset actually delivered was WETH (Wrapped Ethereum, Optimism canonical contract 0x4200…0006), not native ETH. WETH does not appear on Lemon's published list of supported assets ("Novedades" panel), and Lemon's Terms and Conditions clause 13.7 ("Activos Digitales No Listados") directly addresses this scenario: where a user sends a non-listed asset, Lemon is not obliged to reflect it in the user's account and cannot operate on it. The clause is specific, on-point, and disclosed in advance — not a hidden catch-all.

Under Sección A, Información and Transparencia turn on the offer as presented. Lemon's supported-token list and T&C 13.7 together disclosed the limitation clearly before the transaction; the user-side step that failed was verifying which asset would arrive when bridging from World App on Optimism (a third-party wrapping behaviour outside Lemon's control). Buena fe is satisfied — Lemon's support engaged promptly, explained the constraint, and provided educational resources. Protección does not require Lemon to custody arbitrary tokens it has not integrated; that would be operationally impossible and goes beyond the offer the user accepted.

In dubio pro usuario is a tiebreaker and does not fire here: there is no genuine interpretive ambiguity. The published offer, the asset list, and clause 13.7 all converge. Vote: Favor Lemon.

Case 65 | VOTE: Favor Lemon | CONFIDENCE: high | WETH is unlisted; T&C 13.7 and published token list disclosed this clearly; wrapping caused by third-party World App, outside Lemon's offer.
