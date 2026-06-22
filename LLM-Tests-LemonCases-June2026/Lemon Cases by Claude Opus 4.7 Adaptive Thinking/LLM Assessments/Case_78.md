# Case 78 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica" (Lemon Cash policy, Sección A principles + Sección B T&C compatibility)
**Promo / product at issue:** Outbound ARS transfer from Lemon to a third-party Mercado Pago account via alias.
**Amount in dispute:** ARS 50,000
**Question:** Should Lemon reimburse ARS 50,000 that the user voluntarily transferred to an alias he now says was wrong, when Lemon executed the transfer exactly as instructed?

## Options
- Favor User — Lemon must refund / facilitate recovery of ARS 50,000.
- Favor Lemon — Claim rejected; no refund obligation.
- Refuse to Arbitrate — Question malformed, out of jurisdiction, or morality failure.

## Governing rules
1. **Sección A — Protección al Consumidor.** User must be shielded from disproportionate or hidden harms, but not from harms entirely of the user's own making where the provider acted correctly.
2. **Sección A — Información / Transparencia.** Offer-as-presented governs. Lemon must clearly display destination data before confirmation. Hidden limits = likely violation; clear display + user failure = claim fails.
3. **Sección A — Buena Fe.** Both sides must act in good faith; Lemon cannot weaponise irreversibility to evade clear duties, but is not required to undo a correctly executed, user-instructed transaction.
4. **Sección A — In dubio pro consumidor.** Tiebreaker only — applies when evidence/policy are genuinely balanced.
5. **Sección A — Educación / No discriminación.** Not at issue here.
6. **Sección B — T&Cs.** Digifin T&C cl. 3(e) places responsibility for accuracy of destination data on the user. Enforceable to the extent compatible with Sección A; a catch-all T&C cannot override Sección A but here it codifies the same ordinary-care principle.

## Burden of proof
User is the claimant seeking a change to the default state (Lemon retains no funds; funds are with the receiving bank/holder). Burden is on the user to show Lemon violated a Sección A principle or its own offer-as-presented.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon transfer receipt: ARS 50,000 to "Carlos Sebastian Ernesto Del Bianco", CUIT 20288461873, CBU at Mercado Pago, 24/10/2024 19:03 | Primary | No | High — confirms transfer happened as user instructed |
| User | Narrative that alias "seba.la13" was wrong and was entered by mistake | Secondary (party claim) | Implicitly rebutted by Lemon (no oversight obligation) | Low — self-serving, no evidence the alias was anyone other than what user typed |
| Lemon | Internal Digifin VIRTUAL_WITHDRAWAL record confirming the transaction matches the user's receipt | Primary | No | High — corroborates execution |
| Lemon | Screenshots of the "Enviar ARS" send flow showing destination Nombre / Banco / CBU and a "Confirmá tu envío" slide-to-confirm step | Primary (UI capture) | No | High — establishes offer-as-presented: destination data is shown before confirmation |
| Lemon | Reference to Digifin T&C cl. 3(e): user is responsible for accuracy of destination data | Documentary (T&C cited, not attached) | No | Medium — consistent with industry norm and with the displayed UI |

Immaterial:
- User's appeal to "personal finances" and urgency — emotive, does not bear on rule application.

## Application
- **Protección:** Protección does not extend to indemnifying users for self-inflicted typos when the provider correctly executed the instruction. No disproportionate harm imposed by Lemon.
- **Información:** Lemon's UI screenshots show Nombre / Banco / CBU prior to the slide-to-confirm step — information was presented.
- **Transparencia (offer-as-presented):** No hidden limit or surprise clause is invoked against the user. The irreversibility of bank-rail ARS transfers is a property of the underlying CBU/Mercado Pago rails, not a covert Lemon term.
- **Buena fe:** Lemon advised the user to contact the receiving platform (Mercado Pago) — a reasonable, good-faith next step. Lemon did not pocket the funds; they reached the named third party.
- **In dubio:** Not triggered — the evidence is one-sided. The user does not even allege Lemon misrouted the funds; he admits he entered the wrong alias.
- **Educación / No discriminación:** Not engaged.
- **T&C compatibility:** Cl. 3(e) (user accuracy responsibility) is compatible with Sección A in this fact pattern; it is not being used as a catch-all to override consumer protection — it aligns with the displayed UI flow.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica / Lemon). No morality issue. Question is well-formed and answerable from the materials.

## Schelling-Point check
A diligent panel will converge on Favor Lemon. The user-error transfer with a correctly executed, confirmed-before-send flow is the textbook example where Sección A consumer protection does not displace user responsibility under cl. 3(e). Contrarian readings require either inventing a duty to reverse third-party-rail transfers or treating Protección as strict liability — neither survives the literal policy.

## Bias audit
Sympathy for the user's loss is real but immaterial. Decision rests on (a) Lemon executed the instruction as shown, (b) destination data was displayed pre-confirmation, (c) funds left Lemon's control to a named third party at Mercado Pago. No reliance on party identity, polish, or wealth.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

The user admits he entered the wrong alias and authorised a transfer of ARS 50,000 to a named third party at Mercado Pago. Lemon's evidence — the matching internal Digifin record and the "Enviar ARS" UI showing Nombre, Banco and CBU above a slide-to-confirm step — establishes that the destination was presented to the user as offered and that the transfer was executed exactly as instructed. The user's own receipt corroborates this. No evidence suggests Lemon misrouted funds, concealed the destination data, or imposed a hidden limit.

Under Sección A, Protección al Consumidor shields users from disproportionate provider conduct, not from self-inflicted typing errors when the provider acted correctly and transparently. Información and Transparencia are satisfied — the offer as presented displayed the destination clearly before final confirmation. Buena fe is satisfied — Lemon directed the user toward the appropriate next step (contacting Mercado Pago / the receiving party). The irreversibility of the transfer is a property of the ARS bank rails reaching a third-party CBU, not a hidden Lemon term being weaponised. Digifin T&C cl. 3(e), which places destination-data accuracy on the user, is compatible with Sección A on these facts and is not invoked as a catch-all override.

In dubio pro consumidor is a tiebreaker and is not triggered here — the evidentiary record is one-sided in Lemon's favour. The claim is therefore rejected and the vote is Favor Lemon.

---

Case 78 | VOTE: Favor Lemon | CONFIDENCE: high | User-instructed transfer to a named third party; Lemon displayed destination data pre-confirmation and executed correctly; Sección A not breached.
