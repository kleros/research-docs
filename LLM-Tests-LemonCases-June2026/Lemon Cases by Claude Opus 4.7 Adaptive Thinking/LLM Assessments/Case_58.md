# Case 58 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto withdrawal / network selection (USDT transfer between platforms — Optimism vs opBNB confusion)
**Amount in dispute:** Not stated in either descargo
**Question:** Should Lemon be required to refund a user who sent USDT on the wrong network (opBNB) when intending to deposit to a Lemon Optimism address, where both networks were clearly listed and prominently labelled in the app?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Section A.2 (Información):** Lemon must provide accurate, sufficient information about products/services as offered.
2. **Política Section A.3 (Transparencia):** Material limits and conditions must be clearly visible; hidden limits = violation.
3. **Política Section A.4 (Buena fe):** Parties act honestly; representations must be backed by evidence.
4. **Política Section A.1 (Protección):** Reasonable protective measures and warnings for foreseeable user error.
5. **Política Section A.6 (Educación):** Lemon should offer educational resources to prevent costly mistakes.
6. **Política Section A.5 (In dubio pro usuario):** Tiebreaker only — applies where genuine ambiguity remains after rule application.
7. **Política Section B:** T&Cs cannot override Section A protections, but where Section A is satisfied, T&Cs govern operational limits.
8. **General principle (blockchain finality):** Cross-chain misdirected transfers to addresses on unsupported chains are technically irrecoverable absent custody of the private key on that chain.

## Burden of proof
The user is the moving party seeking reversal of a default (lost funds remain lost on blockchain). Burden lies on the user to show Lemon failed an Información, Transparencia, Protección, or Buena fe duty that caused the loss.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of Lemon "Dirección de USDT" deposit screen — shows QR with red "OP" badge, address, and field "Red: Optimism" plus explicit warning: "Asegurate de depositar USDT desde la red Optimism. De lo contrario, perderás tus fondos." | Primary (own app UI) | No | High — shows Lemon clearly disclosed network + warning |
| User | Screenshot of Lemon "Enviar USDT — Elige la red" screen listing AVAX C-Chain, Optimism, opBNB, CELO as distinct selectable options, each with separate commission and minimum, plus warning: "Asegúrate de que la red coincida con la dirección de retiro... De lo contrario, puedes perder tus activos." | Primary | No | High — undermines user's "identifiers similar" claim and contradicts Lemon's own "opBNB not listed" assertion |
| User | Narrative admission: "entendí que cada identificador era único… descubrí que diferentes blockchains pueden utilizar identificadores similares… llevó a confusión y al envío de fondos a una blockchain incorrecta." | Secondary (self-statement, admission) | No | High as admission of user-side error |
| Lemon | Statement that funds were sent on opBNB, which Lemon "does not have listed" and therefore cannot access | Secondary (statement) | Partially rebutted — user's own screenshot shows opBNB IS listed for sending; Lemon's framing inaccurate | Medium |
| Lemon | Lemon Wiki article "¿Qué red seleccionar para recibir crypto?" + Lemon Wiki landing page | Primary (educational material) | No | Medium — relevant to Educación |

Immaterial:
- User's communications with Binance — Binance is not a party; reflects only that the counterparty platform also disclaims custody, which is consistent with cross-chain mechanics.
- Lemon social-media educational claims (general) — not case-specific.

## Application
- **Protección:** Lemon provided multi-layer protective UX — explicit "Red: Optimism" label, red "OP" badge overlay on the QR, and a bold warning "perderás tus fondos" if the wrong network is used. This is reasonable protection against the very error that occurred. Satisfied.
- **Información:** The deposit address screen names the network ("Optimism") and warns of total loss for mismatch. The send screen lists each supported network as a distinct row with its own commission and minimum. Information was provided as offered. Satisfied.
- **Transparencia:** The network field and warning are not hidden — they sit alongside the QR and address. No hidden limit. The fact that opBNB has the letters "OP" in common with Optimism is a property of third-party naming conventions, not a hidden Lemon limitation. Satisfied.
- **Buena fe:** Lemon's descargo overstates its case by claiming "opBNB no está listada", which the user's own screenshot contradicts (opBNB appears as a send option). However, this misstatement does not change the operative facts — the loss occurred because the user selected a network that did not match the destination address. Minor good-faith concern noted but non-decisive.
- **In dubio:** Not triggered — the case is not in genuine equipoise. User admits the error; UI evidence corroborates Lemon's disclosures.
- **Educación:** Lemon points to its Wiki including a specific article "¿Qué red seleccionar para recibir crypto?" — directly on point. Satisfied.
- **No discriminación:** Not implicated.
- **T&C compatibility:** Lemon invokes T&Cs to disclaim recovery of funds sent on a chain it does not custody for the user's address. This is consistent with Section A — it is not a catch-all immunity but a factual statement of blockchain finality, since Lemon cannot sign transactions on a chain where it does not hold the corresponding private key for that user's deposit address.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica — crypto network selection / consumer dispute). No morality issue. Question well-formed and answerable from materials.

## Schelling-Point check
A panel of diligent jurors reading these two descargos converges on Favor Lemon: the user's own evidence shows the network was clearly identified ("Red: Optimism") with an explicit "you will lose your funds" warning; the send-side screen presents opBNB and Optimism as plainly distinct rows; and the user's narrative is an admission of self-inflicted error attributed to general "blockchains use similar identifiers" — a third-party naming reality Lemon cannot cure.

## Bias audit
Sympathy for a user who lost crypto is the relevant pull factor; it is set aside. Lemon's overstatement ("opBNB no listada") is noted but does not flip the outcome because the controlling fact — that the receive address was labelled "Optimism" with a prominent warning — is uncontested and proven by the user's own screenshot. No reliance on party identity, polish, or wealth.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

Under Política Section A, Lemon's duties of Información, Transparencia and Protección are measured against the offer as presented to the user. The user's own primary evidence — a screenshot of Lemon's "Dirección de USDT" screen — shows the destination network labelled "Red: Optimism", a red "OP" badge overlaid on the QR code, and a prominent warning that depositing from any other network would result in total loss of funds. The send-side screen, also submitted by the user, lists Optimism and opBNB as separate, clearly distinguishable selectable rows with different commissions and minimums, accompanied by the warning "Asegúrate de que la red coincida con la dirección de retiro… puedes perder tus activos." There is no hidden limit and no defective disclosure.

The user's descargo is itself an admission that the error originated in their own assumption that network identifiers are unique across chains. That assumption is contradicted by the very interface the user used, which named each network and warned of loss on mismatch. Section A.5 (In dubio pro usuario) is a tiebreaker and is not engaged where, as here, the disclosure-and-warning record is one-sided. Section A.6 (Educación) is further supported by Lemon's Wiki, which includes an article expressly on choosing the receiving network. Lemon's descargo overstates its case by asserting that opBNB is "not listed" — the user's screenshot shows it is — but this misstatement does not change the operative fact that the destination address was an Optimism address and the funds were sent on a different chain, making them technically inaccessible to Lemon.

Because Lemon discharged its Información, Transparencia, Protección and Educación duties as presented, and the loss is attributable to user-side network selection despite clear warnings, the claim under Section A fails. Section B's T&C limitation aligns with Section A here — it reflects blockchain finality, not a catch-all immunity. Vote: Favor Lemon.

---

Case 58 | VOTE: Favor Lemon | CONFIDENCE: high | User admitted wrong-network error; Lemon's deposit screen clearly labelled "Optimism" with explicit loss warning; send screen listed networks distinctly; disclosures adequate.
