# Case 95 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** External deposit of CRO (Cronos) from Stake to Lemon over ERC20 network — token and network not listed on Lemon
**Amount in dispute:** 287.07856623 CRO (~USD 30.14 per user's blockchain explorer screenshot)
**Question:** Must Lemon credit / restitute the user for a CRO deposit sent over a network that Lemon does not support, when neither the asset nor the network is listed on the platform?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Section A — Protección al Consumidor:** Lemon must safeguard users' economic interests within the scope of services actually offered.
2. **Política Section A — Información:** Lemon must clearly disclose which assets and networks are supported.
3. **Política Section A — Transparencia:** Operating rules, supported assets and risks must be visible and accessible before the user operates.
4. **Política Section A — Buena fe:** Both parties must act in good faith; users are expected to verify network/token compatibility before sending external funds.
5. **Política Section A — In dubio pro consumidor:** Tiebreaker only when, after applying the other principles to the evidence, the result remains genuinely ambiguous.
6. **Política Section A — Educación financiera:** Lemon must provide educational resources to help users operate safely.
7. **Política Section B — T&C 13.7 (Activos Digitales No Listados):** "En el caso de que el Usuario por error realice el envío de Activos Digitales que no se encuentren listados en la Plataforma o a través de una Red que no se encuentre listada, los mismos no podrán verse reflejados en su cuenta. El usuario entiende y acepta que la empresa solamente presta el servicio por los Activos Digitales Listados." This T&C is consistent with — and complementary to — Section A so long as the unsupported status was transparently disclosed.

## Burden of proof
The user (claimant) seeks to alter the default state (the funds remain lost on-chain because Lemon never received the deposit on a supported rail). The user must therefore show, on a balance-of-evidence standard, that Lemon either (a) offered CRO/ERC20 as a supported deposit channel, (b) received the funds on a supported rail and failed to credit, or (c) otherwise breached Section A duties of Información/Transparencia in a way that caused the loss.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Blockchain explorer screenshot: "Withdraw 287.07856623 CRO" tx hash 0xc44b…cdcd, Status Success, Mar-25-2025 09:55:11 UTC | Primary (on-chain) | No | High — proves the outbound transfer existed, but does not prove receipt by Lemon on a supported rail |
| User | Assertion that funds "never credited" and support did not respond | Secondary (party statement) | Partially conceded by Lemon (Lemon confirms not received on its platform) | Medium |
| Lemon | Statement that CRO is not a listed asset and the ERC20 network used is not enabled on Lemon | Party statement, corroborated by app screenshot | Not rebutted by user | High |
| Lemon | App screenshot of "Novedades" listing supported Blockchains, Stablecoins, dApps and L2 — CRO absent | Secondary (documentary) | Not rebutted | High |
| Lemon | Reference to Lemon Wiki / Centro de Ayuda educational resources | Secondary | Not rebutted | Medium |
| Lemon | T&C clause 13.7 expressly governing unlisted assets / networks | Primary contractual | Not rebutted | High |

Immaterial:
- User's general invocation of Transparencia / Protección / Buena fe without identifying any specific Lemon representation that CRO was supported — argumentative rather than evidentiary.
- Strategic justifications by Lemon for why it does not list every asset (technical/financial/regulatory) — context only; not load-bearing.

## Application
- **Protección:** Protection extends to services Lemon offers. CRO over ERC20 is outside the offered service. No protection duty arises to credit funds Lemon never custodied on a supported rail.
- **Información:** Lemon's app deposit flow displays only supported tokens and networks; the "Novedades" view enumerates supported chains and CRO/Cronos is not among them. The information presented to the user before the operation was accurate and complete. No misrepresentation alleged or evidenced.
- **Transparencia:** Supported assets/networks are visible in-app and explained in the Lemon Wiki and Help Center. T&C 13.7 expressly warns that unlisted-asset/network sends will not be reflected. The risk was transparently disclosed.
- **Buena fe:** Good faith requires the user to confirm a destination supports the asset and network before initiating an external transfer. The user initiated the send from Stake without verifying that Lemon supports CRO on ERC20; nothing in the record shows Lemon induced the error.
- **In dubio pro consumidor:** Not triggered. The evidentiary picture is one-sided: Lemon's unrebutted screenshots show CRO is not listed, and the user offers no evidence that Lemon represented otherwise. There is no genuine tie to break.
- **Educación financiera:** Lemon evidences a Wiki and Help Center addressing how to operate safely and warning against sending unsupported assets. Duty satisfied.
- **No discriminación:** Not in issue.
- **T&C compatibility (Section B):** Clause 13.7 is not a "catch-all immunity" — it is a narrow, specific rule mirroring an obvious technical reality (assets/networks Lemon does not integrate cannot be credited). Because Lemon transparently published the list of supported assets/networks and the clause itself, the T&C is compatible with Section A and applies on its terms.

## Jurisdiction / Morality / Validity
Pass. Argentine consumer/crypto dispute properly seated in "Blockchain No Técnica"; no morality flag; question is well-formed.

## Schelling-Point check
A diligent panel of policy-literate jurors will converge on Favor Lemon: the user shipped an unlisted asset over an unlisted network; Lemon's unrebutted evidence shows the listing scope was transparently published; T&C 13.7 mirrors the operational reality; no Section A duty was breached.

## Bias audit
Sympathy for a user who has lost ~USD 30 on-chain is set aside. The decisive question is whether Lemon breached a Section A duty or held the funds on a supported rail — neither is shown. Vote turns on the policy text and unrebutted evidence, not on the user's financial loss.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
Under Política Section A, Lemon's duties of Información and Transparencia attach to the service it actually offers. The unrebutted evidence — Lemon's in-app "Novedades" listing, the Wiki, the Help Center, and T&C clause 13.7 — shows that Cronos (CRO) is not a listed asset on Lemon and that the ERC20 deposit rail used by the user is not an enabled network. Nothing in the record indicates Lemon ever represented to the user that CRO/ERC20 deposits would be credited. The offer as presented was clear and accurate.

The user's primary evidence (the blockchain explorer screenshot of a successful CRO withdrawal from Stake) proves only that the outbound transfer occurred; it does not show that Lemon ever received the funds on a supported rail, nor that Lemon misrepresented support for CRO. The Section A principle of Buena fe places a corresponding duty on the user to verify, before initiating an external transfer, that the destination platform supports the asset and the chosen network. That step was not taken, and the resulting loss is not attributable to a Section A breach by Lemon.

T&C clause 13.7 is not an impermissible catch-all override of Section A; it is a narrow, transparent rule mirroring the technical reality that Lemon cannot custody assets it has not integrated. Because the unsupported status was disclosed in advance, the clause is compatible with Section A and applies on its terms. The In dubio pro consumidor tiebreaker is not engaged because the evidentiary balance is not in genuine equipoise — Lemon's position is corroborated and unrebutted. Vote: **Favor Lemon**.

---

Case 95 | VOTE: Favor Lemon | CONFIDENCE: high | User sent unlisted CRO over unlisted ERC20 rail; supported assets/networks transparently published; T&C 13.7 consistent with Section A; no Lemon breach.
