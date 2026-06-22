# Case 39 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto deposit (USDT/TRX) to Lemon wallet — alleged non-credit of inbound transfer
**Amount in dispute:** 55 USDT (TRC20)
**Question:** Should Lemon credit the user 55 USDT for a withdrawal allegedly sent from an exchange to the user's Lemon account when the user has not provided the transaction hash needed to verify the on-chain delivery?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección al consumidor** — duty to assist the vulnerable user when the failure originates in the platform.
2. **Información** — both parties have a duty to provide what is required for the matter to be resolved.
3. **Transparencia** — Lemon must explain what is needed and why.
4. **Buena fe** — both sides must act in good faith and cooperate.
5. **In dubio pro consumidor** — tiebreaker only.
6. **Educación financiera** — Lemon must educate the user about how to identify a transaction (hash, network, token).
7. **T&Cs compatibility** — Section A principles override T&Cs where conflict exists.

## Burden of proof
The user, as claimant alleging that a deposit failed to credit, must produce minimally sufficient evidence of an on-chain transfer to his Lemon address (transaction hash / network / receiving address). Without that, Lemon cannot be expected to credit funds it cannot verify ever reached it.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of "Detalhes do Saque" from a Binance-style exchange showing 55 USDT withdrawal on TRX network, status "Concluído", recipient address `TWZKjR...55UpAL`, marked **Off-chain**, internal Note `178907567905` | Screenshot | Not rebutted as image, but its probative value is contested — the "Off-chain" tag and internal note (not a blockchain hash) indicate this was an internal/off-chain transfer within the exchange, not a TRX on-chain send to Lemon | Low–Medium |
| Lemon | Support-chat screenshot (agent "Lauty") requesting Hash/ID, Red and Token from the user, with example hash format | Screenshot | Not rebutted | High |
| Lemon | Statement that user never provided the hash to support or in this proceeding | Statement | Confirmed by absence in user's submission | High |

Immaterial:
- The exact identity of the employer; the user's allegation that the sender was his employer does not change the technical/identification requirement.

## Application
- **Protección:** Lemon's request for a hash is not an obstacle to protection — it is the minimum needed to investigate. Refusing to credit unidentified funds protects all users (and Lemon's reserves) from unsubstantiated claims.
- **Información:** Lemon clearly informed the user what data was needed (hash, network, token) with an example. The user failed to supply it.
- **Transparencia:** Lemon's process was transparent — the support request explains why each item is needed ("Con estos datos, puedo ver el movimiento en la red y revisar el estado").
- **Buena fe:** Lemon acted in good faith by opening a ticket and asking precise, reasonable questions. The user did not cooperate.
- **In dubio pro consumidor:** Not triggered — there is no genuine evidentiary tie. The evidence affirmatively suggests the transfer may have been an **off-chain** internal exchange transfer (note "Off-chain", internal numeric note instead of an alphanumeric hash), which would never reach Lemon at all. At minimum, the user has not met the threshold to shift the burden.
- **Educación financiera:** Lemon educated the user (explained what a hash is, gave an example). Duty met.
- **No discriminación:** Not at issue.
- **T&C compatibility:** No T&C invoked; resolution rests on Section A principles, which Lemon has satisfied.

## Jurisdiction / Morality / Validity
Standard consumer-protection dispute within the subcourt's scope; no jurisdictional or morality issues. RtA not warranted.

## Schelling-Point check
Most reasonable jurors will not order a platform to credit 55 USDT to a user who refuses to provide a transaction hash and whose only evidence is a screenshot flagged "Off-chain" — i.e., a transfer that, by its own face, may not have left the exchange's internal ledger. The Schelling-point answer favours Lemon.

## Bias audit
No pro-platform bias: Lemon's request is objectively minimal and standard. No anti-user bias: the user simply has not met the threshold to substantiate his claim. Off-chain marker on his own evidence undermines the premise of the claim.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user alleges a 55 USDT transfer from his employer failed to credit to his Lemon account, but his single piece of evidence is a withdrawal detail screen from an exchange that explicitly marks the transfer as **Off-chain** and shows an internal numeric note (`178907567905`) rather than a TRX blockchain transaction hash. An off-chain transfer is an internal ledger movement within the sending exchange and would not be visible on the TRX network or to Lemon at all. On its face the user's own evidence is consistent with a transfer that never reached Lemon.

Lemon discharged its Sección A duties of **Información, Transparencia, Buena fe y Educación**: support agent Lauty opened a ticket, explained precisely what data was required (hash, red, token), provided an example of an alphanumeric hash, and explained why each datum was needed to trace the movement. The user never provided that data — neither to support nor in this Kleros proceeding. Without a hash or destination address linkable to Lemon, the platform cannot verify any inbound transfer, and ordering credit of 55 USDT on this record would amount to crediting unverifiable funds.

**In dubio pro consumidor** is a tiebreaker, not a substitute for the user's threshold burden. Here the evidence is not in equipoise — it leans against the user. Vote: **Favor Lemon**.
