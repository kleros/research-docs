# Case 108 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto deposit (WLD from World App to Lemon)
**Amount in dispute:** ~S/ 108.32 (29.99908 WLD)
**Question:** Is Lemon liable for funds the user sent from World App to an external address that is not controlled by Lemon, where the user alleges the pasted address mysteriously differed from the Lemon deposit address they had copied?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Protección al Consumidor** — duty of care toward retail users.
2. **Información** — clear, sufficient information about how to operate.
3. **Transparencia** — operations and addresses must be displayed unambiguously.
4. **Buena fe** — both parties act in good faith.
5. **In dubio pro consumidor** — tiebreaker only when genuine doubt remains after evidence.
6. **Educación** — duty to educate the user about risks.
7. **No discriminación** — not engaged here.
8. **T&C subordinate to Section A** — catch-all disclaimers cannot override consumer-protection duties.

## Burden of proof
The user bears the burden of showing that Lemon caused or could have prevented the loss. Lemon need only show that the transaction never touched its infrastructure and that it provided adequate warnings on the deposit screen.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Screenshot: "Dirección de WLD … 0xc133F3dCc76bD4c563C3eBe421844720e1A39F91" with World Chain network and warning "Asegurate de depositar WLD desde la red World Chain. De lo contrario, perderás tus fondos." | Primary (in-app screenshot) | No | High |
| User | Screenshot: "Enviaste Worldcoin … a 0xde52c3dc9bd45068f08b0686873ad118e5b6f0d3" — funds sent to a completely different address | Primary | No | High |
| User | Assertion that he copied the Lemon address and "the pasted address did not match" — no screenshot of the actual paste step in World App | Secondary (uncorroborated allegation) | Disputed by Lemon | Low |
| Lemon | Statement that destination `0xde…f0d3` is not associated with Lemon nor with its custody/infrastructure provider | Primary (operator knowledge) | Not rebutted by user | High |
| Lemon | Statement that the transaction was completed entirely inside World App, outside Lemon's ecosystem | Primary | Not rebutted | High |
| Lemon | Deposit screen displays the address, the network, and a warning — visible in user's own screenshot | Corroborated by user's own evidence | Not rebutted | High |

Immaterial:
- User's subjective "uncertainty about the security of the copy process in the application" — does not identify any specific Lemon failure.
- Generic appeal to "transparency" — Lemon's deposit screen is itself transparent (address, network, warning all shown).

## Application
- **Protección:** Lemon's protection duty extends to operations within its platform. The send transaction was executed inside World App; the destination is a third-party address. Lemon has no operational ability to reverse on-chain transactions to non-Lemon addresses. The Lemon deposit screen itself shows a clear warning about loss of funds — consistent with the protection duty.
- **Información:** The Lemon deposit screen ("Dirección de WLD") clearly shows the address, the network (World Chain), and a loss-of-funds warning. Information duty satisfied.
- **Transparencia:** The address as displayed by Lemon is visible in the user's own screenshot. No hidden limitation; no ambiguous text.
- **Buena fe:** No bad faith by either party. The user appears genuinely mistaken about how the wrong address ended up in the paste buffer. Lemon's explanation is coherent and consistent with on-chain reality.
- **In dubio:** Reachable only as a tiebreaker. Here there is no real tie — the on-chain evidence is unambiguous that funds went to an address Lemon does not control, and the copy/paste step occurred entirely outside Lemon. No genuine doubt to break.
- **Educación:** Lemon's deposit flow includes the standard warning. The address-and-network education is present on the very screen the user submitted.
- **No discriminación:** Not at issue.
- **T&C compatibility:** Lemon does not invoke a catch-all clause; it relies on the factual point that the funds never reached its infrastructure. No conflict with Section A.

The decisive fact is plainly on-chain: the destination address `0xde52c3dc9bd45068f08b0686873ad118e5b6f0d3` is not the Lemon deposit address `0xc133F3dCc76bD4c563C3eBe421844720e1A39F91`. These addresses share no common prefix and cannot be the result of a Lemon-side substitution. The error necessarily occurred (a) in World App, (b) in the device clipboard, or (c) in user verification — none of which is inside Lemon's control plane. Address-poisoning, clipboard malware, and similar third-party attacks are well-known risks the user must manage; Lemon cannot detect or prevent them for an inbound deposit that it never receives.

## Jurisdiction / Morality / Validity
Pass. Correct subcourt (Blockchain No Técnica, Lemon policy). No morality issues. Question is well-formed.

## Schelling-Point check
A panel of policy-literate jurors will converge on Favor Lemon: the loss occurred entirely outside Lemon's infrastructure, the address that received the funds is demonstrably not Lemon's, and Lemon's deposit screen carried the required information and warnings. The Schelling answer is the simple, literal one — Lemon cannot be held responsible for a paste-step error that occurred in a third-party app and resulted in a transfer to a third-party address.

## Bias audit
Sympathy for a real financial loss noted and set aside. The user's allegation of a "mysterious modification of the pasted address" is unsupported by any screenshot or technical evidence and, even if accepted at face value, points to a clipboard or World-App issue rather than a Lemon failure. No party-identity or rhetorical-style influence detected.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user sent 29.99908 WLD from World App to address `0xde52c3dc9bd45068f08b0686873ad118e5b6f0d3`, which is not the Lemon deposit address shown in his own screenshot (`0xc133F3dCc76bD4c563C3eBe421844720e1A39F91`). The send transaction was constructed, signed and broadcast entirely inside World App; Lemon's systems were never the originator and never the recipient. Lemon's unrebutted statement that the destination is not associated with its custody or infrastructure provider, combined with the on-chain evidence supplied by the user himself, establishes that the funds never entered Lemon's perimeter. There is therefore no operation by Lemon to which the principles of Protección, Información or Transparencia can attach a violation.

Lemon's deposit screen — visible in the user's own evidence — displays the address, the network (World Chain), and an explicit warning that depositing on the wrong network will cause loss of funds. The Información, Transparencia and Educación duties under Section A are satisfied. The user's allegation that the pasted address "did not match" the copied address is uncorroborated and, even taken as true, points to a clipboard, device or World-App issue outside Lemon's control. The "In dubio pro consumidor" tiebreaker is not engaged because there is no genuine evidentiary tie: the on-chain destination is unambiguously a third-party address.

For these reasons, applying the Lemon policy and the Section A consumer-protection principles literally, the correct vote is Favor Lemon.

---

Case 108 | VOTE: Favor Lemon | CONFIDENCE: high | Funds sent from World App to non-Lemon address 0xde...f0d3; Lemon never received them and provided clear deposit-screen warnings — no Lemon-side fault.
