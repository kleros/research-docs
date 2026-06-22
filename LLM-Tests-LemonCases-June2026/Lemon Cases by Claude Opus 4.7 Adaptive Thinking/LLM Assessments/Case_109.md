# Case 109 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto deposit — USDT transfer from Binance to Lemon via opBNB network
**Amount in dispute:** 100 USDT
**Question:** Must Lemon credit / reimburse the 100 USDT the user sent from Binance via the opBNB network to a Lemon-issued deposit address?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Section A – Información (2) & Transparencia (3):** the platform must clearly inform users which networks/assets are available; the offer "as presented" governs.
2. **Política Section A – Protección (1) & Buena fe (4):** Lemon must protect users acting in reliance on the platform's published information; both parties owe good faith.
3. **Política Section A – In dubio pro consumidor (5):** tiebreaker only.
4. **Política Section B:** T&Cs cannot override Section A principles; catch-all immunity clauses do not displace consumer-protection duties.
5. **Lemon T&C 13.7 (Activos Digitales No Listados):** assets sent via a non-listed network/token cannot be reflected in the account; Lemon is not obliged to support non-listed assets/networks.
6. **Blockchain technical reality:** once a transaction is broadcast on one chain (opBNB), Lemon — operating only on the listed networks — cannot retrieve assets on chains it does not integrate.

## Burden of proof
The user is the claimant seeking reimbursement; the burden lies on the user to show Lemon presented opBNB as an enabled network or otherwise breached Section A. Lemon must rebut by showing it disclosed the supported list and that opBNB was not on it.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Binance withdrawal screenshot: 100 USDT, network **OPBNB**, txid 0x42ff…, completed 2025-05-25 | Primary | No | High (confirms send via opBNB) |
| User | Binance support chat saying Lemon should have a way to recover and asking Lemon what they need | Secondary | Partial — it is a third-party's opinion, not a Lemon commitment | Low |
| User | Mercado Pago screenshot (ARS 5,000 transfer to "Alexis Sandoval") | Secondary | N/A | Immaterial (unrelated) |
| Lemon | Help-centre screenshots and in-app "Redes de depósito" list: Arbitrum, Avalanche, BNB Chain (BEP20), Celo, Ethereum (ERC20), Optimism, Polygon, Tron (TRC20) — **opBNB not listed** | Primary | No | High |
| Lemon | T&C clause 13.7 expressly stating non-listed networks/assets cannot be credited | Primary | No | High |
| Lemon | In-app "Ingresar USDT" screen showing supported networks pre-deposit | Primary | No | High |

Immaterial:
- Mercado Pago ARS transfer screenshot — unrelated to the USDT/opBNB dispute.
- User's invocation of "principio de diligencia" against Lemon — not supported by any Lemon representation that opBNB was enabled.

## Application
- **Protección:** Lemon's offer ("as presented") clearly excluded opBNB; user's loss flows from sending to a network the platform never offered. No protection failure shown.
- **Información:** Lemon disclosed the supported deposit networks in-app, in help-centre articles, and in T&C 13.7. opBNB never appears on any list. Information duty satisfied.
- **Transparencia:** The offer as presented is unambiguous — BNB Chain (BEP20) is supported; opBNB (a distinct L2) is not. No hidden limit.
- **Buena fe:** User did not verify the network in the Lemon app (which displays it pre-deposit). Lemon's posture is consistent and technically accurate — opBNB and BEP20 are different chains; cross-chain recovery is not technically possible for Lemon.
- **In dubio:** Not engaged — the record is clear, not doubtful.
- **Educación:** Lemon publishes a dedicated help article ("¿Qué red selecciono para recibir crypto?") and an in-app network selector. Educational duty met.
- **No discriminación:** Not in issue.
- **T&C compatibility:** Clause 13.7 aligns with Section A here — it is not a catch-all immunity but an accurate statement of technical reality regarding non-listed networks, consistent with the disclosed offer.

## Jurisdiction / Morality / Validity
Pass. Proper subcourt (Blockchain No Técnica, Lemon policy). No morality issue. Question is well-formed.

## Schelling-Point check
A diligent panel reading the Lemon T&Cs, the app screenshots and the user's own Binance receipt (which plainly says "OPBNB") will converge on Favor Lemon: the user sent funds via a network never offered by Lemon; Lemon disclosed the supported list; recovery is technically impossible for Lemon on a non-integrated chain.

## Bias audit
Sympathy for a user losing 100 USDT is set aside. Decision rests on the offer-as-presented and the user's own primary evidence showing opBNB — a network absent from every Lemon list.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
Under Política Section A, the controlling principles are Información and Transparencia: the platform's offer as presented governs. Lemon's evidence — the in-app "Redes de depósito" selector, the help-centre article, and T&C clause 13.7 — shows that the supported USDT deposit networks are Arbitrum, Avalanche C-Chain, BNB Chain (BEP20), Celo, Ethereum (ERC20), Optimism, Polygon and Tron (TRC20). opBNB is not, and has never been, on that list. The user's own primary evidence (the Binance withdrawal receipt) confirms the transfer was executed on the opBNB network. There is no "hidden limit" — the limit is the disclosed list itself.

The user's reliance argument fails because Lemon never represented opBNB as enabled; the contrary information was visible in-app before the deposit was initiated. The Binance support chat is a third party's opinion and does not bind Lemon, and BEP20 and opBNB are distinct chains — a Lemon address on BEP20 cannot receive or be swept on opBNB. Clause 13.7 is therefore not a catch-all immunity overriding Section A; it accurately describes the technical and contractual position, and it is compatible with Información, Transparencia and Buena fe.

In dubio pro consumidor is not engaged because the record is unambiguous. The Schelling-point reading is Favor Lemon: the user, having selected a non-supported network, bears the consequence of an irreversible on-chain action that the custodian cannot technically reverse.

---

Case 109 | VOTE: Favor Lemon | CONFIDENCE: high | User sent USDT via opBNB, a network never listed by Lemon; offer-as-presented and T&C 13.7 align; recovery technically impossible.
