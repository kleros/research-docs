# Case 34 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Inbound CVU bank transfer (Brubank → Lemon) of ARS 15,200 dated 14/06/2024.
**Amount in dispute:** ARS 15,200.00
**Question:** Must Lemon credit a transfer it claims never arrived from Brubank, when the user has supplied only the Brubank sending receipt and not the Coelsa ID that Lemon repeatedly requested?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Section A.1 Protección — Lemon must protect user funds it actually holds.
2. Política Section A.2 Información & A.3 Transparencia — Lemon must give clear, actionable information about how to resolve interbank transfer issues.
3. Política Section A.4 Buena fe — both sides must cooperate honestly.
4. Política Section A.5 In dubio pro usuario — tiebreaker only.
5. Burden allocation: claimant must prove the transferred funds actually reached Lemon's institution; Lemon must prove it gave fair guidance for resolution.

## Burden of proof
User must show the funds were received by Lemon (or at minimum trace-evidence consistent with Lemon receipt). A Brubank "Transferencia enviada" screenshot proves dispatch, not arrival at destination; the Coelsa ID is the standard interbank trace artefact and was requested by Lemon.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Brubank screenshot 14/06/2024 17:36, ARS 15,200, CBU 0000168300000014753071 (Lemon), CUIL 20-33289697-1, "Transferencia enviada", op. ID 2406180000157403390549 | Sender-side proof of dispatch | Not rebutted as authentic; Lemon disputes only that funds were received | Medium — proves outflow from Brubank, not credit at Lemon |
| Lemon | Support-chat screenshot from agent "Frank": explains 48-business-hour window, requests Coelsa ID, links explanatory article | Conduct/diligence evidence | Not rebutted | High — shows clear, prompt, on-policy guidance |
| Lemon | Statement that internal team verified no incoming transfer from Brubank was received | Assertion | Unrebutted but uncorroborated | Medium |
| Lemon | Statement that user never replied with Coelsa ID | Conduct evidence | Unrebutted | Medium-High |

Immaterial:
- Decorative Kleros/Lemon banners.

## Application
- **Protección:** No evidence Lemon ever held these funds; protection duty does not extend to crediting transfers not received from the sending institution.
- **Información:** Lemon's support clearly explained the 48-hour window, the Coelsa ID mechanism, and provided a help-centre link — fully informative.
- **Transparencia:** The Coelsa procedure is the industry-standard, BCRA-authorised trace path; pointing to it is transparent, not evasive.
- **Buena fe:** Lemon acted in good faith (prompt, polite, on-policy reply). The user did not engage with the reasonable request for the Coelsa ID, which suggests a failure of cooperative good faith on the user's side.
- **In dubio pro usuario:** Tiebreaker only. The evidentiary picture is not in true balance — the user has not even attempted to obtain the trace artefact that would resolve the doubt, so the tiebreaker does not trigger.
- **Educación:** Lemon delivered an educational explanation of Coelsa with a linked article — meets the duty.
- **No discriminación:** Not at issue.
- **T&C compatibility:** No Section-B conflict; Lemon's position is consistent with Section A.

## Jurisdiction / Morality / Validity
Standard consumer-protection dispute over a fiat interbank transfer involving a regulated Argentine clearing house (Coelsa). Within subcourt scope; no morality/validity issue. No basis to Refuse to Arbitrate.

## Schelling-Point check
A diligent juror reading the file would observe: (a) the user only proved the money left Brubank; (b) Lemon gave standard, correct, well-explained guidance; (c) the user did not produce the Coelsa ID that would either prove arrival at Lemon or pin liability on Brubank. Most reasonable jurors converge on Favor Lemon, with the user invited to obtain the Coelsa ID and pursue Brubank if the funds were intercepted in transit.

## Bias audit
No sympathy bias toward Lemon as a corporate party; user appears genuine and inconvenienced but objectively under-evidenced. No anti-user bias — outcome would flip immediately if a Coelsa ID showed funds delivered to Lemon's CVU.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
Under Política Section A, Lemon's duties of Información, Transparencia and Educación require it to explain promptly how an apparently-stuck interbank transfer can be traced. The unrebutted support-chat screenshot shows Lemon's agent "Frank" doing exactly this on the same day: setting expectations (up to 48 business hours), identifying the correct trace artefact (the Coelsa ID, issued by the sending bank), and linking the relevant help-centre article. That is good-faith, transparent, educational conduct.

The user's only evidence is a Brubank "Transferencia enviada" confirmation. That proves the funds left Brubank but does not prove they arrived at Lemon — interbank transfers can fail, be rejected, or be queued by the originating bank or by Coelsa without ever reaching the destination institution. Lemon's Protección duty attaches to funds it actually holds; without proof of receipt, that duty is not triggered. The Coelsa ID is the standard, BCRA-recognised way to settle this factual question, and the user neither produced it nor explained why not.

In dubio pro usuario is a tiebreaker, not a default. Here the doubt is squarely resolvable by the user obtaining the Coelsa ID from Brubank; refusing to do so cannot shift the loss onto Lemon when Lemon's evidence (an internal check finding no inbound credit) is unrebutted. The case fails on burden of proof. The user retains the right to re-claim against Lemon if a Coelsa trace later shows the funds were credited to Lemon's CVU, or against Brubank if the trace shows the funds never left.
