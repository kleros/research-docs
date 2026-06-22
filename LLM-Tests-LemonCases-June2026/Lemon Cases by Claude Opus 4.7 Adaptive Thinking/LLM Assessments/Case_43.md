# Case 43 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Crypto withdrawal — USDT external transfer from Lemon wallet
**Amount in dispute:** 200.00 USDT net (200.75 USDT debited)
**Question:** Is Lemon responsible for funds the user withdrew on BEP20 to an address that the receiving platform (Libertex) only supports for ERC-20?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Section A.1 Protección — protect the consumer.
2. Section A.2 Información — accurate, sufficient information by Lemon.
3. Section A.3 Transparencia — clear disclosure of relevant operational facts.
4. Section A.4 Buena fe — good faith on both sides.
5. Section A.5 In dubio pro consumidor — tiebreaker only.
6. Section A.6 Educación financiera.
7. Section A.7 No discriminación.
8. Section B — T&Cs subordinate to Section A; catch-all immunity does not override Section A.
9. Offer-as-presented governs Información / Transparencia.

## Burden of proof
User must prove Lemon failed to deliver the withdrawal as instructed or misled him on the operational parameters (network, address). Lemon must rebut with on-chain / system evidence.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Lemon app screenshot: 200.75 USDT withdrawal on BNB Chain (BEP20), status "Completo", hash 0x10e57955…1379f, dest 0xD4712…823F, 04/07/2024 10:29 | Screenshot | No | High — confirms user chose BEP20 network |
| User | Libertex deposit screen screenshot showing the SAME address 0xD4712…823F, but explicitly labelled "Esta dirección es solo para Ethereum ERC-20 USDT — Enviar cualquier otra moneda a esta dirección puede concluir en una pérdida de tu depósito" | Screenshot | No | High — destination platform warned in writing that only ERC-20 is supported |
| Lemon | Internal admin record (Trx ID 2b7cc14c…, Hash matches user's, network BEP20, status "Completada", Fireblocks YES) | Admin screenshot | No | High — confirms successful on-chain execution per user instructions |
| Lemon | Libertex support email (5 Jul) to user: "usted hizo un depósito por una red que no es compatible con nosotros. Solo aceptamos USDT vía red ERC20 y TRC20… no tenemos como reclamar esos fondos" | Third-party email | No | High — receiving platform confirms wrong-network user error and unrecoverable funds |

Immaterial:
- General blockchain immutability narrative — accepted background, not dispositive.

## Application
- **Protección:** Lemon executed the precise instruction (network + address) the user selected. No protective duty extends to second-guessing destination compatibility once user has selected a network in a wallet-to-external transfer.
- **Información:** Lemon's withdrawal flow exposes the network field; the user picked BEP20. No allegation that Lemon mislabelled networks or hid the field. Information duty met.
- **Transparencia:** Hash, Trx ID, network and amount are all openly disclosed in the receipt screenshot the user himself supplied. Transparent execution.
- **Buena fe:** Lemon delivered exactly what was requested and engaged with support when contacted. The user's own Libertex screenshot bears an unmistakable warning that the address is "solo para Ethereum ERC-20 USDT" — the loss flows from disregarding that warning, not from Lemon bad faith.
- **In dubio pro consumidor:** Tiebreaker only. No genuine ambiguity here — evidence is one-directional.
- **Educación financiera:** The selection-of-network step is a standard, well-signposted crypto operation; the receiving platform additionally warned the user in writing on its own deposit screen.
- **No discriminación:** Not engaged.
- **T&C compatibility:** Lemon's responsibility ends at correct on-chain dispatch to the user-selected address/network; this is consistent with Section A because the user retains full control of and information about the destination choice.

## Jurisdiction / Morality / Validity
Standard consumer arbitration question; valid; no morality or jurisdictional concerns.

## Schelling-Point check
A diligent unbiased juror would converge on Favor Lemon: user selected BEP20 to an address Libertex flagged as ERC-20-only on the very screen the user himself screenshotted. The error is the user's; Lemon executed correctly.

## Bias audit
No pro-corporate tilt — outcome would be identical for any custodial wallet that correctly executed a user-chosen network. No pro-user tilt warranted — "in dubio" is a tiebreaker, not a thumb on the scale where evidence is clear.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user instructed Lemon to send 200.75 USDT to address 0xD4712…823F on the BNB Chain (BEP20) network. Lemon's own and the user's screenshots, plus the matching on-chain hash 0x10e57955…1379f, show the withdrawal was executed exactly as instructed and confirmed on-chain. Under Section A.2 (Información) and A.3 (Transparencia), Lemon disclosed the network and destination in the offer-as-presented flow; under A.4 (Buena fe) it performed precisely what the user requested.

The loss arose because Libertex, the receiving platform, only credits USDT on ERC-20 (and TRC-20). The user's own deposit-screen screenshot from Libertex carries the explicit warning "Esta dirección es solo para Ethereum ERC-20 USDT — Enviar cualquier otra moneda… puede concluir en una pérdida de tu depósito", and Libertex's support email of 5 July reiterates that the funds cannot be reclaimed. That is a user-side network-selection error and a third-party recovery problem, not a Lemon execution failure.

Section A.1 (Protección) does not require a custodial sender to override a clearly-presented user choice between supported networks, and Section A.5 (in dubio pro consumidor) is a tiebreaker that does not apply where the evidence is one-directional. Lemon's catch-all-immunity language is not needed to reach this result; Section A itself supports Lemon on these facts.
