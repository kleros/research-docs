# Case 114 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** USDT withdrawal on Polygon network (self-custody crypto withdrawal from Lemon to external wallet)
**Amount in dispute:** 134 USDT (133 USDT net + 1 USDT network fee)
**Question:** Is Lemon liable to reimburse 134 USDT when the user claims the withdrawal "never arrived" at the destination wallet, even though the on-chain Polygon transaction shows the funds were delivered to the exact address the user provided?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Protección al consumidor (A.1):** the user is entitled to have instructions executed faithfully; this guarantees correct execution, not reversal of confirmed blockchain transactions outside Lemon's control.
2. **Información (A.2):** Lemon must give clear, verifiable information about the operation.
3. **Transparencia (A.3):** the offer/operation as presented governs; Lemon must furnish objective proof of execution.
4. **Buena fe (A.4):** both parties must act in good faith and consistently with the operation as presented.
5. **In dubio pro consumidor (A.5):** tiebreaker only — applies when material facts are genuinely indeterminate.
6. **Educación (A.6) / No discriminación (A.7):** not engaged on these facts.
7. **Section B — T&Cs vs Section A:** Lemon's T&Cs (irreversibility of confirmed crypto transactions) are compatible with Section A here because they describe an inherent property of public blockchains, not a hidden carve-out from consumer rights.

## Burden of proof
The user (claimant) bears the burden of showing that Lemon failed to execute the withdrawal in accordance with the instructions given. Lemon bears the burden of showing faithful execution.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon app screenshot: 134 USDT withdrawal marked "Completo", Polygon network, destination `0xfaf72289bd563ed8...d58462c5f796430a4`, hash `0x9b4513b8c0c1562...23ba78568a9b00819` | Secondary (app screenshot) | No | High — confirms execution and destination address |
| Lemon | Polygonscan capture of the same hash showing 133 USDT0 transfer to `0xfAf72289...f796430A4` (same address) | Primary (on-chain record) | No | High — independent, public, immutable confirmation |
| Lemon | Support chat transcript: agents explain blockchain irreversibility, confirm the funds reached the address the user provided, link Polygonscan, advise contacting the destination platform | Primary (support record) | No | Medium-high — shows clear, consistent communication |
| User | Narrative claim the funds "never arrived" at destination | Secondary (assertion) | Yes — by on-chain record | Low |

Immaterial:
- User's typed address in the narrative (`0xfaf72289bd563ed8f0445fd584f2c5779643044`) is malformed/truncated, but the screenshot the user attached shows the correct full address, which matches the on-chain destination. The typo is a transcription error in the descargo, not the address actually used.

## Application
- **Protección:** Lemon executed the user's instruction faithfully — the on-chain record shows the funds reached the exact address the user entered in the app. Consumer protection does not require Lemon to reverse a confirmed blockchain transaction or to underwrite the user's ability to access funds at a self-controlled or third-party destination.
- **Información:** Lemon provided the hash, network, destination address, amounts and a Polygonscan link, both in the app and in support. The information is complete and verifiable.
- **Transparencia:** The operation as presented (a non-custodial withdrawal to a user-specified address on Polygon) was performed exactly as presented. No hidden term was relied on.
- **Buena fe:** Lemon responded substantively to the user, re-checked the system, and provided a second message confirming the address and giving the explorer link. Good faith satisfied on both sides.
- **In dubio:** Not engaged — there is no genuine doubt. The user's own screenshot and Lemon's on-chain proof corroborate each other.
- **Educación:** Support explained blockchain irreversibility and how to verify the transfer on the explorer. Educational duty met.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Lemon's clause on irreversibility of confirmed crypto transactions reflects an immutable property of public blockchains (not a hidden carve-out). Compatible with Section A.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica); no morality issues; question is well-formed and answerable from the materials.

## Schelling-Point check
A panel of diligent jurors will all see (a) the user's own screenshot confirming completed status and the destination address, and (b) the matching public Polygonscan record showing delivery to that exact address. The Schelling outcome is Favor Lemon.

## Bias audit
No reliance on party identity or rhetoric. The user's emotional framing ("perdí el dinero", "no le importa") is set aside. Decision rests on the on-chain record plus the user's own screenshot, both unrebutted.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
Under Section A of the Política, Protección al Consumidor requires that user instructions be executed faithfully; it does not extend to reversing a confirmed transaction on a public blockchain that the platform does not control. The user instructed a withdrawal of 134 USDT on Polygon to address `0xfAf72289...f796430A4`. The user's own screenshot shows the operation marked "Completo" with that destination address and hash `0x9b4513b8c0c1562...23ba78568a9b00819`. Lemon's Polygonscan capture of the same hash shows 133 USDT0 delivered to the same address. The two pieces of evidence are mutually corroborating and unrebutted.

Información and Transparencia are also satisfied: Lemon disclosed the network, fee, net amount, destination address, transaction hash and explorer link both in the app and in the support thread, and re-confirmed the destination in a follow-up support message. Buena fe and Educación are likewise satisfied — support explained the irreversible nature of confirmed blockchain transactions and directed the user to the destination platform if the receiving wallet is a centralised service. In dubio pro consumidor is a tiebreaker and is not engaged here because the material facts are not in genuine doubt.

The T&Cs clause on irreversibility of confirmed crypto transactions is compatible with Section A because it describes an inherent property of the underlying technology rather than a hidden carve-out from consumer rights. Lemon executed the instruction exactly as given; any failure to access the funds at destination is attributable to the user's control of the receiving wallet or to a third-party platform, neither of which is within Lemon's power to remedy. The claim therefore fails.

---

Case 114 | VOTE: Favor Lemon | CONFIDENCE: high | User's own screenshot and Lemon's matching on-chain Polygonscan record show 133 USDT delivered to the exact address the user provided; instruction executed faithfully.
