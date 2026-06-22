# Case 4 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Lemon Cash consumer-protection subcourt)
**Promo / product at issue:** Account security / unauthorised transfers following phone theft
**Amount in dispute:** USD 218 (converted to ARS 104,781) — transferred to third-party CVU after device theft
**Question:** Is Lemon liable to refund USD 218 / ARS 104,781 transferred from the user's account by a third party after her iPhone was stolen, where Lemon's logs show login with valid credentials from the same (stolen) device?

## Options
- **Favor User** — uphold and compensate.
- **Favor Lemon** — reject claim.
- **Refuse to Arbitrate** — only if RtA trigger fires.

## Governing rules
1. **Protección** — consumer is vulnerable party; tilt toward protection (Section A.1).
2. **Información** — provider must give clear, complete information on security features and how to use them (A.2).
3. **Transparencia** — no misleading practices regarding the security perimeter (A.3).
4. **Buena fe** — both parties act honestly (A.4).
5. **In dubio pro consumidor** — tiebreaker only (A.5).
6. Provider must operate a fraud-prevention system per BCRA "Sistema Nacional de Pagos" 5.4 / 2.6, including detection of unusual transfers and preventive blocks (cited by Lemon).
7. Provider not liable where loss is attributable to the consumer's own credential compromise outside the provider's security perimeter, provided the provider made adequate security tools available.

## Burden of proof
User must show, on balance, that the loss was caused by a failure of Lemon's security perimeter (not by her own compromised credentials/device). Lemon must show its security perimeter was not breached and that reasonable security features were made available.

## Material evidence

| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Police "Certificado de Actuaciones" #308135/2023, Comisaría 2A CABA, 2 Jun 2023 — robbery of iPhone 13 Pro Max on Av. Callao 17:00, identifies recipient CVU 0000053600000011872216, CUIL 20-42921207-8, alias of recipient | Primary (official document) | No | High — corroborates theft + identifies destination account |
| User | Narrative: phone stolen ~17:00; unauthorised transfer ~30 min later; pattern of behaviour inconsistent with her own transfer history | Secondary | Partly — Lemon's log shows ~38 min gap, consistent with user's account | Medium |
| Lemon | Amplitude/login log: last genuine login from device 9FE8743C... at 29/5/2023 22:47; fraudulent login at 2/6/2023 17:39 (≈3-day gap) | Primary (system log) | No (unrebutted) | High |
| Lemon | view_withdraw event 2 Jun 2023 17:38 local from same Device ID 9fe8743c... (iOS, v2.6.70) — i.e. from the stolen physical device | Primary (system log) | No | High |
| Lemon | Description of fraud-prevention infrastructure (Metamap, DataDog, Amplitude, Metabase, Neo4j) and available 2FA / session-timeout settings | Secondary (policy description, not case-specific) | No | Low-medium |

Immaterial / discarded:
- Lemon's generic recitation of BCRA compliance — describes capability, not what was actually done in this case.
- Police-report typo about "$105,000 pesos" — user already explained this is the ARS equivalent of USD 200; not load-bearing.

## Application (principle-by-principle)
- **Protección:** User is the vulnerable party, suffered violent theft (robo per Art. 164), and lost real savings as an intern. The principle pulls toward protection, but cannot override clear evidence on causation.
- **Información:** No evidence Lemon failed to inform the user about available security features (2FA via SMS/Google Authenticator, session-timeout config, login-session registry). Lemon's pleadings show these tools exist and are offered in-app. No evidence the user was misled about the security perimeter.
- **Transparencia:** No misleading advertising or hidden term is at issue. The dispute is causation, not disclosure. Satisfied.
- **Buena fe:** Both parties' accounts are broadly consistent: a real theft occurred and the fraudster used the physical device. Lemon's reply is reasoned and supported by logs rather than a boilerplate denial. The user acted in good faith reporting promptly.
- **In dubio pro consumidor:** Not invoked — the evidence on causation is not genuinely ambiguous. Logs show same device ID, ~38 minutes after the theft, with valid credentials entered (>5-minute inactivity timeout had elapsed, so the passcode/credentials had to be re-entered). This places the breach point at the user's own credentials/device passcode, not at Lemon's perimeter.
- **Educación / No discriminación:** Not directly relevant.
- **T&C compatibility (Section B):** Lemon does not invoke a catch-all "decisions definitive and unappealable" clause; it relies on BCRA-aligned fraud-prevention rules and on causal evidence. No clause requiring Section B override.

## Jurisdiction / Morality / Validity check
Pass. Consumer-protection dispute within scope; no morality trigger (theft was by an off-platform third party, not by Lemon); question well-formed; materials sufficient.

## Schelling-Point check
A diligent panel would likely reach the same conclusion: payment processors and wallets are not generally liable for losses that occur after a user's device and credentials are simultaneously compromised by a third party, provided the platform offered reasonable security (2FA, session timeout) and acted on its own logs. Sympathy for the victim is high but does not change the causation finding.

## Bias audit
Sympathy is strong — young intern, violent street robbery, modest savings. Stripping that out: the dispositive facts are (i) same Device ID, (ii) credentials successfully entered after >5-min inactivity, (iii) no evidence Lemon's perimeter was breached, (iv) no evidence 2FA was enabled by the user or that Lemon should have triggered an automatic block on a transfer of this size from a known device. Decision must rest on evidence, not on the user's hardship.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

Under Section A principles, the user bears the initial burden of showing that her loss resulted from a failure of Lemon's security perimeter rather than from compromise of her own device and credentials. The police certificate (primary evidence) establishes that the phone was stolen, but Lemon's unrebutted Amplitude logs establish that the unauthorised withdrawal originated from the same physical Device ID, ~38 minutes after the theft, and required valid credential entry because the 5-minute in-app inactivity timeout had elapsed. That places the breach at the user's credential/passcode layer — outside the perimeter Lemon controls.

Principle A.2 (Información) and A.3 (Transparencia) are satisfied: Lemon documents the availability of 2FA (SMS / Google Authenticator), session-timeout configuration, and a login-session registry. There is no evidence these were misrepresented or hidden, nor any allegation by the user that Lemon's advertising induced her into a false sense of security. Principle A.1 (Protección) pulls toward the consumer but cannot, on its own, reallocate a loss caused by off-platform credential compromise. Principle A.5 (in dubio pro consumidor) is not engaged because the causation evidence is not genuinely ambiguous.

I therefore vote **Favor Lemon**. Confidence is medium rather than high because Lemon's pleading is largely a generic policy recital and does not specifically address whether the transfer ought to have tripped a velocity/value alert given the user's prior transaction history (the user credibly asserts she never makes transfers of that size to third-party accounts). A panel that weighed that omission more heavily could plausibly reach the opposite result, which is why this is not a high-confidence vote.
