# Case 29 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Desconocimiento de transferencias (two ARS withdrawals of 25,000 each from User's Lemon account on 02 May 2024).
**Amount in dispute:** ARS 50,000 (2 × ARS 25,000).
**Question:** Must Lemon reimburse the User for two ARS 25,000 withdrawals he claims were unauthorised, when Lemon's logs show the transfers originated from the User's habitual device and IP with no failed biometric attempts?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección** — Lemon must protect funds against actual platform vulnerabilities, but not against third-party social engineering that occurs outside the platform.
2. **Información** — Lemon must inform users; User must accurately inform Lemon of the facts when claiming.
3. **Transparencia** — As-presented mechanics govern.
4. **Buena fe** — both parties must act in good faith; misrepresenting the cause of loss breaches this.
5. **In dubio** — tiebreaker only.
6. **Educación** — Lemon must educate on phishing/scam risks, but the user remains responsible for credentials/biometrics.
7. **No discriminación** — not at issue.

## Burden of proof
The User alleges unauthorised access to his Lemon account. Once Lemon produces device/IP/biometric logs showing the disputed operations were performed from the User's habitual device with no anomalous login or biometric prompts, the evidentiary burden shifts back to the User to identify a credible platform vulnerability or rebut the logs. Unrebutted log evidence is presumed genuine.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Narrative: discovered zero balance, two unknown transfers when trying to pay with card | Self-report | Partly contradicted by Lemon (no rejected card attempts on 02.05.24) | Low |
| User | Screenshots of two outgoing "Retiros de ARS" of ARS 25,000 each to "Carlos Agustín Ortuay" CBU 0000139300000003213476 on 02 May 2024 (13:08 and 13:58) | Screenshots | Not rebutted — confirms transfers occurred | Medium (confirms fact, not authorship) |
| User | WhatsApp chat with "Aye" asking to borrow 25,000 ARS, with Lemon CBU exchange | Screenshot | Not rebutted | Medium — shows User received an inbound 25,000 ARS deposit from his sister after the first withdrawal, consistent with User narrative of borrowing to replace lost funds |
| User | Two inbound deposits of 25,000 ARS the same day (one from Yamila Ayelén Breitschuh, one from Brian Sebastián Medina Montalvo) | Screenshots | Not rebutted | Medium — pattern: deposit-in / withdraw-out × 2 |
| Lemon | Internal log: last device change 30/01/2022; same device_id 700B7A56-30D7-48A8-A885-E877F7490368 used throughout the 2–7 May 2024 window | Admin SQL dump | Not rebutted | High |
| Lemon | Login log: 02/05/2024 sessions at 16:07, 16:56, 19:10, 23:24 from IPs (181.9.170.210; 186.13.97.225; 181.1.45.206) that also appear before and after that date as the User's habitual IPs | Admin SQL dump | Not rebutted | High |
| Lemon | No failed biometric attempts; no new-device biometric challenge triggered on 02.05.24 | Statement supported by logs | Not rebutted | High |
| Lemon | Contradicts User: there were no rejected card-purchase attempts on 02.05.24 (User's stated trigger for discovering the loss is false) | Statement | Not rebutted | Medium |

Immaterial:
- Kleros header logos on every page.
- The User changed his password afterwards — does not bear on authorship of the disputed transfers.

## Application
- **Protección:** No platform vulnerability is alleged or shown. Lemon's biometric/device-binding controls functioned (no new-device challenge, no failed biometric, same device since Jan 2022). Protección does not extend to off-platform social engineering or to the User authorising transfers himself.
- **Información:** Lemon disclosed device/IP/biometric records. The User's account of how he discovered the loss (rejected card purchases) is contradicted by Lemon's records.
- **Transparencia:** As-presented mechanics — transfers require app access on the bound device with biometric or passcode. That mechanism worked.
- **Buena fe:** The User's narrative contains an objectively false trigger (rejected card transactions that did not exist). Combined with the same-day pattern of two inbound 25,000 ARS deposits followed by two outbound 25,000 ARS withdrawals from his habitual device/IP, the more probable explanation is that the User himself executed the transfers (possibly under instruction of a third-party scam — "triangulation" / receiver-launderer scam) rather than that Lemon's platform was breached.
- **In dubio:** Not engaged — the evidence is materially one-sided. Tiebreaker not reached.
- **Educación:** Generic; Lemon's T&Cs and onboarding materials cover phishing/scam warnings. No specific Educación failure shown.
- **No discriminación:** Not at issue.
- **T&C compatibility:** No Section-A principle is overridden; Lemon's reliance on its logs is consistent with both T&Cs and Section A.

## Jurisdiction / Morality / Validity
Standard Lemon/Kleros consumer dispute. Properly arbitrable. No invalidity or morality issues.

## Schelling-Point check
A diligent, policy-literate, unbiased juror seeing (a) unrebutted logs showing the disputed transfers were made from the User's habitual device with no biometric failure, (b) a User narrative containing a verifiable falsehood about rejected card purchases, and (c) a same-day pattern consistent with a "money-mule" / scam-victim cash-out rather than account takeover, would converge on Favor Lemon.

## Bias audit
I checked for pro-platform bias: would my answer change if Lemon had produced only a bare assertion? Yes — but Lemon produced concrete, particularised, time-stamped device and IP logs covering both before and after the disputed date, on the same device since 2022. I also checked for pro-user bias: the User's loss is real and sympathetic, but sympathy is not a legal ground when the platform's controls verifiably operated and the User's own narrative is partially false.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The User alleges two unauthorised withdrawals of ARS 25,000 each from his Lemon account on 02 May 2024. Lemon answered with internal device, IP, and biometric logs showing the disputed operations originated from the same iOS device (UUID 700B7A56-...-7F7490368) and IP ranges the User had used continuously since January 2022 and continued to use in the days after the disputed events. No new-device biometric challenge was triggered, and no failed biometric or passcode attempts were recorded on 02.05.24. Lemon also contradicts a verifiable element of the User's account: the User claimed he discovered the loss when card-purchase attempts were rejected, but Lemon's records show no rejected card attempts on that date. These logs are unrebutted and, under the unrebutted-evidence presumption, are taken as genuine.

Applying Section A: Protección covers platform-side vulnerabilities, not transfers authorised from the User's own bound device. Información and Transparencia are not breached — the as-presented authentication mechanics (device-binding plus biometric) functioned. Buena fe weighs against the User, whose own narrative includes a false trigger (the non-existent rejected card transactions) and whose movement pattern that day (two inbound 25,000 ARS deposits from third parties immediately followed by two outbound 25,000 ARS withdrawals to a single CBU belonging to "Carlos Agustín Ortuay") is more consistent with the User being recruited as a money mule, or falling for a social-engineering scam executed on his own device, than with Lemon's platform having been breached.

In dubio is not engaged because the evidence is not in equipoise. No Section-A principle requires Lemon to bear the loss of a transfer the User himself executed (or authorised by handing credentials/device to a third party) outside the platform's responsibility envelope. Vote: Favor Lemon.
