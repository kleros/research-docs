# Case 62 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** ARS outbound transfer (Retiro de ARS) from Lemon (Digifin fiat rail) to an external Mercado Pago account / CBU
**Amount in dispute:** ARS 12,490
**Question:** Should Lemon be ordered to compensate the user for an ARS 12,490 transfer the user himself instructed to a Mercado Pago CBU that he now says was incorrect and to which he has lost access?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Section A.2 — Información** and **A.3 — Transparencia.** Lemon must disclose, before confirmation, the destination of the transfer in a way the user can verify.
2. **Política Section A.4 — Buena fe.** Both parties must act in good faith.
3. **Política Section A.1 — Protección al usuario.** Protect users from harms attributable to the platform.
4. **Política Section A.5 — In dubio pro usuario.** Tiebreaker only.
5. **Section B — T&Cs vs Section A.** T&Cs apply where compatible. Lemon (Digifin) T&Cs clause 3(e) places responsibility for the accuracy of the destination data on the user who instructs the transaction; this is compatible with Section A because it tracks the underlying nature of an irreversible CBU/CVU transfer that has actually been delivered to the instructed account.
6. **General principle:** A platform that executes correctly the instruction it was given is not liable for the user's data-entry error; reversal of a settled CBU transfer is not within Lemon's power.

## Burden of proof
On the user (claimant) to show that Lemon failed a duty (Información, Transparencia, Buena fe or Protección) that caused the loss. Default state if claim not proven: Lemon prevails.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | App screenshot of the completed Retiro de ARS 12,490 dated 20/08/2024 16:58, showing destination CBU `0000003100085284200171`, recipient "Denise Maria Cornet D'Hunval", COELSA ID and transaction ID | Primary (in-app comprobante) | No | High — confirms the transfer was executed exactly as the user instructed and that the recipient name was displayed |
| User | Statement that the destination Mercado Pago account "is no longer active" and he cannot access it or contact the holder | Self-serving assertion | Not corroborated | Low |
| Lemon | Internal Digifin admin panel (TX ID matches user's), confirming same amount, same CBU, same recipient name, status Completada on 20/08/2024 16:58:03 | Primary | No | High |
| Lemon | Screenshots of the "Enviar ARS" send flow showing the in-app confirmation overlay ("Confirmá tu envío") with Nombre / Banco / CBU displayed and a slide-to-confirm gesture | Primary (UX evidence) | No | High — establishes that the destination details were shown for verification before confirmation |
| Lemon | Reference to Digifin T&Cs clause 3(e) allocating responsibility for accuracy of destination data to the user | Documentary (T&C cited, not attached) | Not rebutted | Medium |

Immaterial:
- The user's hardship narrative about not being able to recover the funds — sympathetic but not a legal ground against Lemon.
- Whether the recipient account is "still active" at Mercado Pago — that is a matter between the user and Mercado Pago, not Lemon.

## Application
- **Protección:** Lemon offered the standard protections of an Argentine fiat-rail withdrawal: pre-confirmation summary with recipient name, bank and CBU, plus a slide-to-confirm gesture. No platform-side failure is alleged.
- **Información:** The destination CBU and recipient name were displayed in the confirmation overlay before the user authorised the transfer (Lemon's UX screenshots, unrebutted). The user's own comprobante shows the same data post-execution. The information duty was met.
- **Transparencia:** The amount, recipient name, CBU, COELSA ID and TX ID were all surfaced in the comprobante and matched Lemon's internal record. No hidden fees, no hidden limits, no surprise behaviour.
- **Buena fe:** Lemon executed the instruction as given and provided a documented audit trail. No bad-faith conduct is alleged or evidenced. The user does not allege Lemon altered or misrouted the transfer — he concedes he typed the wrong destination.
- **In dubio pro usuario:** Not triggered. The facts are not in equipoise; the user himself admits the error was his.
- **Educación:** Not engaged.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Digifin clause 3(e) (user-borne accuracy duty) is compatible with Section A because it reflects the technical reality of an executed, settled interbank/CVU transfer; it is not a hidden carve-out used to deny a service that was offered.

## Jurisdiction / Morality / Validity
Correct subcourt (Blockchain No Técnica — Lemon consumer dispute). No morality flag. Question well-formed.

## Schelling-Point check
A diligent panel will see: (i) the user concedes the error was his own; (ii) Lemon's UX showed the destination data for confirmation; (iii) a completed CBU transfer cannot be unilaterally reversed by the sending platform. The obvious, defensible reading is Favor Lemon.

## Bias audit
Sympathy bias checked — losing ARS 12,490 to one's own typo is genuinely painful, but sympathy is not a Section A principle. Removing it does not change the outcome: no platform duty was breached.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user candidly states that he himself instructed a transfer of ARS 12,490 to a Mercado Pago CBU that turned out to be wrong, and that he no longer has access to the destination account. The on-chain-style record he submits (the in-app comprobante) and Lemon's internal Digifin record agree on every material field — amount, CBU `0000003100085284200171`, recipient "Denise Maria Cornet D'Hunval", date/time 20/08/2024 16:58 and the same COELSA / transaction identifiers. Lemon executed the instruction exactly as given.

Under Política Section A, the duties of Información and Transparencia are tested by the offer "as presented" to the user before confirmation. Lemon's unrebutted UX screenshots show the "Confirmá tu envío" overlay surfacing Nombre, Banco and CBU plus a slide-to-confirm gesture; the destination data was visible for verification. There is no hidden limit, no misleading copy, and no allegation that Lemon misrouted the funds. Buena fe and Protección are likewise satisfied — Lemon performed the service it offered. Digifin T&C clause 3(e), which places accuracy of destination data on the instructing user, is compatible with Section A because it tracks the irreversible nature of a settled CBU transfer rather than operating as a hidden disclaimer.

In dubio pro usuario is a tiebreaker, and the facts here are not tied: the user concedes the data-entry error and identifies no failure attributable to Lemon. The correct recourse is with the receiving institution (Mercado Pago) and, if applicable, the named recipient — not the sending platform that delivered the funds to the instructed account. Vote: Favor Lemon.

Case 62 | VOTE: Favor Lemon | CONFIDENCE: high | User admits he typed the wrong CBU; Lemon's UX showed recipient name and CBU pre-confirmation and executed the instruction exactly as given — no Section A breach.
