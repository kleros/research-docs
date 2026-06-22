# Case 111 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Wallet-to-wallet USDC transfer (Lemon platform, Peru). User error / mistaken recipient.
**Amount in dispute:** 1.39 USDC
**Question:** Must Lemon reverse and refund a USDC wallet-to-wallet transfer that the User now claims he sent "by mistake" to an unknown recipient, when the transfer was executed by the User from his own account, confirmed in the in-app double-confirmation flow, and settled on-chain?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política — Section A.1 Protección al consumidor** — Lemon must offer reasonable protection to users.
2. **Política — Section A.2 Información** — Users must be given clear info before acting (recipient, amount, irreversibility).
3. **Política — Section A.3 Transparencia** — Process and limits must be disclosed up-front; the offer as presented governs.
4. **Política — Section A.4 Buena fe** — Both parties must act in good faith.
5. **Política — Section A.5 In dubio pro consumidor** — Tiebreaker only, when genuine doubt remains.
6. **Política — Section A.6 Educación** — Lemon should educate users on irreversibility risk.
7. **Política — Section A.7 No discriminación** — Not engaged.
8. **Política — Section B** — T&Cs apply only where compatible with Section A. A catch-all irreversibility clause cannot extinguish a real Section A violation, but it is fully effective where no Section A violation exists.
9. **T&C 3.3 (cited by Lemon):** "Once executed, the instruction is irreversible and cannot be cancelled." This reflects the technical reality of an on-chain transfer.

## Burden of proof
The User is the claimant seeking to alter the default state (a completed, on-chain, user-initiated transfer). He must show either (a) the transfer was not authorised, or (b) Lemon failed a Section A duty (information, transparency, protection) such that the loss is attributable to Lemon rather than to his own input error.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot of completed USDC transfer 03/07/2025 14:31 PE, 1.39 USDC to lemontag "$4" / "Dulce Sabrina Lopez", tx ID 1b130df1… | Primary | No — Lemon confirms it | High (confirms transfer happened and was completed) |
| User | Written statement that the transfer was an "involuntary error" and he does not recognise the recipient | Secondary (self-serving narrative) | Not corroborated; contradicts his own admission he "made the transfer" | Low |
| Lemon | Backend record of WALLET_TO_WALLET transaction, same tx ID, sender = Jose Alejandro Castillo Navarro (User), destination lemontag "$4" / Dulce Sabrina Lopez (user 61907), status Completada | Primary | No | High |
| Lemon | Screenshots of the standard send flow showing amount entry + a separate "Confirmá tu envío" confirmation screen displaying recipient name and details before slide-to-confirm | Primary (UX evidence) | Not rebutted by User | High (shows double-confirmation / disclosure built into the flow) |
| Lemon | T&C clause 3.3 — accepted at account creation — instructions are irreversible once executed | Primary documentary | Not rebutted | High |
| Lemon | Statement that funds have left Lemon's custody and Lemon has no technical means to claw back funds from a third party's wallet | Secondary but uncontested and consistent with how wallet-to-wallet crypto transfers work | Not rebutted | High |

Immaterial:
- Emotional appeal that the amount "is important to my personal economy" (1.39 USDC ≈ a sub-dollar/few-dollar value). Sympathy is not a Section A criterion.
- Generic invocation of "transparencia" and "buena fe" with no specific failing identified on Lemon's side.

## Application
- **Protección:** Lemon's protective duty here is to (i) show the recipient before confirmation and (ii) warn that transfers are irreversible. Both are evidenced. Protección does not extend to clawing back funds from a third-party wallet — that is technically impossible on-chain and outside Lemon's control.
- **Información:** The send flow displays recipient name + lemontag and requires a separate confirm step (slide-to-confirm). User had the information needed to detect his own error before pressing send. No information failure by Lemon.
- **Transparencia:** Irreversibility is disclosed in T&C 3.3 (accepted at onboarding) and is consistent with the on-chain nature of USDC transfers. No hidden limit; the "offer as presented" did not promise reversibility.
- **Buena fe:** User concedes he made the transfer himself ("realice por error"). No bad faith by Lemon; it processed the instruction as given and engaged with support. No deceptive UX is alleged.
- **In dubio pro consumidor:** Tiebreaker only. There is no genuine doubt here — the User affirmatively states he executed the transfer and the only "error" was his own input. No tie to break.
- **Educación:** Irreversibility is a basic, widely-disseminated feature of crypto wallet transfers and is reinforced in T&Cs and the confirm screen. No educational failing decisive to the outcome.
- **No discriminación:** Not engaged.
- **T&C compatibility:** T&C 3.3 (irreversibility) is fully compatible with Section A because it tracks the technical reality of on-chain transfers and is paired with adequate pre-send disclosure. It is not being used as a catch-all to override a Section A violation — because none exists.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica, consumer dispute against Lemon). No morality issue (no theft / perjury alleged credibly). Question is well-formed and answerable.

## Schelling-Point check
A panel of diligent jurors reading these materials converges on Favor Lemon. The User admits he sent the funds; the platform showed a confirmation screen with the recipient before send; the transfer is on-chain and out of Lemon's custody; and the request is essentially "make Lemon take funds back from a third party's wallet", which is technically impossible and outside any duty in Section A.

## Bias audit
Small monetary amount (≈ a few dollars) and a sympathetic "I made a mistake" framing could tempt a juror toward leniency, but Section A is not a hardship fund and the User has not identified a single specific failing by Lemon. No party-identity, wealth or rhetorical bias affecting the analysis.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The User admits he executed the USDC transfer himself and characterises it as an "involuntary error". The on-chain record and Lemon's backend confirm a completed WALLET_TO_WALLET transfer of 1.39 USDC initiated from the User's account to lemontag "$4" (Dulce Sabrina Lopez), tx ID 1b130df1-a7fd-4b36-862d-0df55b19bb6e. Lemon's evidence further shows that the standard send flow requires the user to pass through a separate "Confirmá tu envío" screen displaying the recipient's name before a slide-to-confirm action. The User does not rebut that this confirmation screen was shown, and his own screenshot confirms the transaction completed with the recipient's name visible.

Under Política Section A, Lemon's duties of Protección, Información and Transparencia are satisfied when the platform discloses recipient details before execution and discloses irreversibility (T&C 3.3, accepted at onboarding). None of those duties extend to clawing back funds from a third-party wallet after the User has authorised and executed an on-chain transfer — that is technically impossible and beyond Lemon's custody. Section A.5 (in dubio pro consumidor) is a tiebreaker and is not engaged where, as here, the User's own statement establishes that the loss was caused by his own input error, not by any failing of the platform.

T&C 3.3 (irreversibility) is compatible with Section A because it tracks the technical reality of on-chain transfers and is paired with adequate pre-send disclosure; it is not being used as a catch-all to override a Section A violation, because none exists. The claim accordingly fails and the vote is Favor Lemon.
