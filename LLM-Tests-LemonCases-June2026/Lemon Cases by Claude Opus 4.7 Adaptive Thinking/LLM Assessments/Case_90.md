# Case 90 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Retiro de USDC desde Lemon a una dirección externa (Coinify) en la red BASE en lugar de la red Ethereum solicitada por el destinatario.
**Amount in dispute:** 31.29 USDC (monto bruto; 30.29 USDC netos) — equivalente declarado ≈ 31,446.39 ARS.
**Question:** ¿Debe Lemon reintegrar al usuario los 31.29 USDC retirados a una dirección externa (Coinify) cuando el usuario seleccionó manualmente la red BASE en vez de Ethereum, y la transacción se confirmó en blockchain pero la página de pago externa expiró?

## Options
- **Favor User** — Lemon debe reintegrar los fondos.
- **Favor Lemon** — No procede el reintegro.
- **Refuse to Arbitrate** — Caso fuera de jurisdicción, inmoral o malformado.

## Governing rules
1. **Protección al Consumidor** — evitar la pérdida definitiva de fondos cuando existan soluciones técnicas razonables; no impone obligación de revertir lo técnicamente irreversible.
2. **Información** — Lemon debe presentar la oferta de retiro con la red y el destino claramente.
3. **Transparencia** — la app debe mostrar de forma clara la red elegida, el destino y las advertencias relevantes; la oferta AS PRESENTED gobierna.
4. **Buena fe** — ambas partes deben actuar con honestidad; no obliga a Lemon a asumir pérdidas por errores del usuario.
5. **In dubio pro consumidor** — TIEBREAKER cuando el resto del análisis empata.
6. **Educación** — Lemon debe facilitar materiales educativos sobre redes (centro de ayuda, Wiki).
7. **No discriminación** — no aplicable.
- **T&Cs vs Sección A** — los T&C de irreversibilidad no pueden eximir a Lemon de violaciones de la Sección A, pero sí son válidos en lo no contradicho por ella.

## Burden of proof
El usuario, como reclamante que solicita un cambio del estado por defecto (transacción on-chain ejecutada según sus instrucciones), debe probar que Lemon presentó la oferta de forma engañosa o que existe una vía técnica de recuperación accesible para Lemon.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura Lemon: "Retiro de USDC … 22 mar 2025 15:59 … Red: BASE … Completo" a dirección 0x7389…87c4 | Primary (screenshot Lemon) | No | High |
| Usuario | Captura Coinify: "Send USDC on **Ethereum** blockchain, otherwise your funds will be lost." | Primary (instrucción del receptor) | No | High |
| Usuario | Captura Coinify "Payment Expired … payments received after expiry time will be refunded" | Primary | No | Medium (refuerza que Coinify, no Lemon, controla el destino) |
| Usuario | Admisión propia: "el error fue de mi parte al seleccionar la red incorrecta" | Admission | No | High |
| Lemon | Investigación interna: transacción procesada en Base, red habilitada, ejecutada según instrucciones del usuario | Secondary (consistente con primary del usuario) | No | High |
| Lemon | T&C: criptos irreversibles, sin posibilidad técnica de recuperación | Policy/Contract | No | Medium |
| Lemon | Artículo centro de ayuda "¿Qué red seleccioné para recibir crypto?" + Lemon Wiki | Secondary | No | Medium (Educación) |

Immaterial:
- Logos de Kleros y Lemon en encabezados — decorativos.
- Sugerencia de Lemon de contactar a Coinify — orientativa, no probatoria.

## Application
- **Protección:** No exige asumir pérdidas técnicamente irrecuperables. La transacción fue confirmada on-chain a la dirección dada por el usuario; ni Lemon ni el usuario tienen claves del destino. No hay vía técnica accesible para Lemon.
- **Información:** La pantalla de Lemon muestra explícitamente "Red: BASE" antes de completarse el retiro. La oferta presentada por Lemon fue clara respecto a la red usada.
- **Transparencia:** No hay evidencia de límites ocultos. La red seleccionada (BASE) fue mostrada con normalidad, y la advertencia incompatible ("send USDC on Ethereum") provenía de Coinify, no de Lemon. AS PRESENTED por Lemon es coherente con lo ejecutado.
- **Buena fe:** El usuario admite honestamente el error; Lemon explica con honestidad los límites técnicos. Ninguna parte actúa de mala fe; el principio no obliga a Lemon a un reintegro graciable.
- **In dubio:** No procede como tiebreaker — la evidencia no está empatada: la causa de la pérdida es la elección errónea del usuario respecto a las instrucciones de Coinify, no una falla de Lemon.
- **Educación:** Lemon aporta evidencia razonable (centro de ayuda específico sobre selección de red + Wiki). Cumple.
- **No discriminación:** No aplica.
- **T&C compatibility:** La cláusula de irreversibilidad de los T&C es coherente con la realidad técnica blockchain y no contradice la Sección A en este escenario, ya que no se ocultaron condiciones materiales.

## Jurisdiction / Morality / Validity
Pasa los tres filtros: dispute de consumidor cripto retail dentro del subcourt "Blockchain No Técnica"; sin conducta inmoral; pregunta bien formada y respondible con la evidencia.

## Schelling-Point check
Un panel diligente convergería en Favor Lemon: el usuario admite el error, la pantalla de Lemon mostró la red correctamente, y la pérdida se origina en la incompatibilidad entre BASE (elegida) y la red Ethereum exigida por Coinify, no en una falla de información/transparencia de Lemon.

## Bias audit
No hay sesgo por simpatía hacia el usuario (que actúa de buena fe). La pérdida es real pero la responsabilidad recae sobre quien seleccionó la red. No se penaliza a Lemon por una limitación técnica universal de blockchain.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user openly admits selecting the wrong network (BASE instead of Ethereum) when withdrawing 31.29 USDC from Lemon to a Coinify deposit address. Lemon's own withdrawal screen, submitted by the user, clearly displayed "Red: BASE" before the transfer was completed, and the on-chain transaction settled to the address provided. The instruction to send USDC on Ethereum came from Coinify's payment page — not from Lemon — and Lemon has no custody of or technical access to assets sent to an external wallet on a different chain. Under Sección A, the Información and Transparencia principles assess the offer AS PRESENTED by Lemon, which was unambiguous.

The Protección al Consumidor principle does not require an exchange to absorb losses that are technically irrecoverable: the underlying blockchain transaction is final, and the receiving wallet is operated by a third party (Coinify), which already directs the user to contact its own support for any out-of-window deposits. Lemon's T&C clause on irreversibility is consistent with the technical reality and does not override Sección A here because no hidden limits or misleading information from Lemon caused the loss. Lemon also evidences compliance with the Educación principle through its help-centre article on network selection and the Lemon Wiki.

In dubio pro consumidor functions only as a tiebreaker, and the evidence is not in equipoise — causation traces cleanly to the user's network choice against Coinify's stated requirement. The correct Schelling-point reading is Favor Lemon.

---

Case 90 | VOTE: Favor Lemon | CONFIDENCE: high | User admits selecting BASE instead of Ethereum; Lemon's screen showed the red clearly; on-chain transfer is irreversible and outside Lemon's technical reach.
