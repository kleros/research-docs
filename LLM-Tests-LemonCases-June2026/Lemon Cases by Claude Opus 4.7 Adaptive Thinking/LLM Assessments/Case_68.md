# Case 68 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto deposit (cash-in) of WLD (Worldcoin) from World App to Lemon wallet
**Amount in dispute:** 25 WLD (≈ S/ 213.71 PEN at the time of transfer)
**Question:** Must Lemon credit (or be deemed already to have remedied) a deposit of 25 WLD — a token not listed on Lemon's platform at the time — that the user sent from World App and that did not appear in his account, given Lemon's own evidence that the funds were subsequently credited?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política — Section A (binding hierarchy):** Protección al Consumidor, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. **Section B:** T&Cs apply only where compatible with Section A; a catch-all immunity clause cannot override Section A principles.
3. **Offer-as-presented doctrine:** The supported-tokens list and onboarding/help content govern what the user could reasonably expect to deposit.
4. **T&C 13.7 (Lemon):** Unlisted Digital Assets sent in error "may not be reflected" in the account; Lemon is not obliged to enable operation of unlisted assets — subject to Section A.
5. **Burden of proof:** Each side proves what it alleges; unrebutted documentary evidence is presumed genuine.

## Burden of proof
User must show a non-receipt of a deposit he was entitled to expect. Lemon must show either (a) the deposit was outside its listed offer (defensive) or (b) it has remedied the issue (cure). Both sides provided documentary evidence.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | World App screenshot: 25.00 WLD sent 16/10/2024, status "Con éxito", hash visible, destination 0xbb…dd28 | Mobile screenshot | Not rebutted (Lemon accepts the transfer occurred) | High — proves send & amount |
| User | Statement that two prior WLD transfers had completed successfully to his Lemon account | Assertion | Not directly rebutted by Lemon | Medium — relevant to user's reasonable expectation |
| User | Description of unanswered support queue ("more than 40 in line") | Assertion | Not rebutted | Medium — relevant to Información/Transparencia |
| Lemon | T&C 13.7 — unlisted assets clause | Contract text | Not contested | Medium — defensive, but Section A compatibility required |
| Lemon | Lemon Edu / "Novedades" screenshot listing supported tokens (WLD absent from the displayed list) | Screenshot | Not directly contested, but user notes two prior WLD transfers credited | Medium — supports "not listed at offer-level" but undercut by prior credits |
| Lemon | Internal admin panel CASH_IN_CRYPTO Trx a3986994… — +25 WLD, "Completada", user wagnercaballeropinchi (ID 2865011), created 18/10/2024 21:13 | Internal system screenshot | Not rebutted | **Decisive** — proves the 25 WLD has been credited |
| Lemon | Statement that the tech team worked to resolve the issue and acreditated the funds | Assertion + corroborating admin screenshot | Not rebutted | High |

Immaterial:
- Generic complaint about long support queues, once the underlying remedy is shown to have occurred (still relevant to Información/Transparencia but not to the remedy sought).

## Application
- **Protección al Consumidor:** The user's economic interest was 25 WLD. Lemon's evidence shows that interest has now been protected — the WLD was credited. Substantive protection achieved.
- **Información:** Lemon's "Novedades" list does identify supported tokens, but the user's evidence of two prior successful WLD transfers suggests information about WLD's status was, at minimum, ambiguous at the user level. Mild weakness on Lemon's side.
- **Transparencia:** Support response times (40+ in queue, auto-replies, no case-specific information) fall short of the Transparencia standard. This is a real failing but is largely cured once the credit was actually made.
- **Buena fe:** Lemon's tech team proactively worked to recover funds for affected users and credited them — this is good-faith conduct that goes beyond what T&C 13.7 strictly requires.
- **In dubio pro consumidor:** Tiebreaker only. Here, on the core question (recover the 25 WLD), Lemon's unrebutted admin screenshot resolves doubt — no tie remains on the principal remedy.
- **Educación:** Lemon points to Lemon Edu and the supported-tokens screen; reasonable educational provision exists, though WLD-specific clarity is questionable given prior successful deposits.
- **No discriminación:** Not engaged.
- **T&C compatibility (Section B):** T&C 13.7 would, on its face, allow Lemon to refuse the unlisted-asset deposit. Strictly applied, this would conflict with Protección when funds are recoverable. Lemon resolved the tension correctly by crediting the funds — Section A respected.

## Jurisdiction / Morality / Validity
The dispute is properly framed: a Peruvian Lemon user, a clearly identified product (cash-in of crypto), a binary remedy question. Nothing exotic, immoral or outside the court's competence. No grounds to Refuse to Arbitrate.

## Schelling-Point check
A diligent, policy-literate juror reading both descargos sees: (1) the user wants 25 WLD credited; (2) Lemon's CASH_IN_CRYPTO admin record shows exactly that — +25 WLD, "Completada", user ID 2865011 matching the case ID, dated two days after the user's send. The honest convergent answer is that the substantive remedy has been provided. Voting "Favor User" would award a duplicate remedy; voting "Refuse to Arbitrate" ignores a clean factual record. "Favor Lemon" is the Schelling point.

## Bias audit
The user's submission is sympathetic — frustrating support experience, real money, legitimate Section-A invocations. The instinct to apply in-dubio pro consumidor is tempting. But in-dubio is a tiebreaker, not a default, and Lemon's admin-panel screenshot — unrebutted, internally consistent, dated, and matching the Trx ID/user ID — is decisive evidence that the principal remedy already exists. Voting against Lemon to "punish" the support-queue failing would over-correct: the underlying claim ("transferir los 25 Worldcoin en mi cuenta") has been satisfied.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

The user sent 25 WLD from World App to his Lemon address on 16 October 2024. WLD was not on Lemon's listed-tokens display, and under T&C 13.7 Lemon was not obliged to credit unlisted assets. However, Lemon's own internal CASH_IN_CRYPTO record (Trx a3986994-d8b4-4ff4-8461-b4fbf5f97aac, user ID 2865011 — matching the case ID — country Peru, +25 WLD, status "Completada", dated 18 October 2024) shows that Lemon's tech team recovered and credited the funds. That document is unrebutted and is presumed genuine.

Section A's Protección, Buena fe and Educación principles are therefore substantively satisfied: the user has been made whole on the only remedy he asked for ("transferir los 25 Worldcoin en mi cuenta"). The user's grievances about Transparencia and Información in the support channel (40+ in queue, automated replies only) are real and would weigh against Lemon in a closer case, but they do not generate a separate monetary remedy here, and the principal claim has been cured.

In dubio pro consumidor is a tiebreaker, and on this record there is no tie: Lemon's documentary proof of crediting is decisive. T&C 13.7 is, in this instance, compatible with Section A because Lemon went beyond its strict contractual position and restored the funds. The honest Schelling-point answer is Favor Lemon.
