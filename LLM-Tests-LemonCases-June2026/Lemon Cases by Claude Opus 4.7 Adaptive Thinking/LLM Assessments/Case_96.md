# Case 96 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (VISA física *6301) — pago con tarjeta a APPLE.COM/BILL
**Amount in dispute:** ARS 74.855,52 (monto 58.463,80 + impuestos 16.391,72), 30 Mar 2025 16:47
**Question:** ¿Debe Lemon reembolsar al usuario un pago con tarjeta a Apple que el usuario alega fue ejecutado accidentalmente por su hija de 5 años?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política A.1 Protección** — del consumidor frente a abusos y daños evitables.
2. **Política A.2 Información** y **A.3 Transparencia** — sobre la oferta tal como se presenta.
3. **Política A.4 Buena fe** — exigible a ambas partes.
4. **Política A.5 In dubio pro consumidor** — TIEBREAKER, sólo si la cuestión queda genuinamente empatada tras aplicar el resto.
5. **T&C Lemon cláusula 3.7** — "El Usuario será el único y exclusivo responsable por todas las operaciones efectuadas en su Cuenta", con deber de custodiar la clave de ingreso y los medios de pago, y de notificar inmediatamente cualquier uso no autorizado. Sección B exige que el T&C ceda ante la Política A; no es escudo absoluto, pero sí rige cuando no hay conflicto con A.
6. **Naturaleza de la operación** — pago con tarjeta a un comercio externo (Apple). Lemon es emisor del medio de pago; el reembolso de una compra de App Store lo gestiona el comercio (Apple), no el emisor.

## Burden of proof
El usuario, que pide alterar el estado por defecto (operación completada y fondos ya transferidos al comercio), debe acreditar (a) falta de autorización imputable a Lemon, (b) incumplimiento de Lemon de algún deber de la Política A, o (c) que existió una vía de reversión disponible para Lemon que ésta omitió.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura de la transacción en la app Lemon: ARS 74.855,52 a APPLE.COM/BILL, 30/3/2025 16:47, tarjeta VISA física *6301, "Pago realizado con éxito" | Secundario (screenshot, coincide con registro Lemon) | No | Media — confirma la operación, no la falta de autorización |
| Usuario | Relato de que la hija de 5 años pulsó "confirmar pago" al salir de App Store | Declaración de parte | No corroborada por evidencia independiente | Baja |
| Usuario | Afirmación de haber cancelado la suscripción esperando reembolso automático | Declaración de parte, sin captura ni nº de caso con Apple | Sí, implícitamente: Lemon dice no haber recibido notificación oficial del proveedor | Baja |
| Lemon | Back-office LEMON_CARD_PAYMENT: misma Trx ID 0acb6e68…, completada, fondos egresados | Primario (registro interno) | No | Alta — operación válida con credenciales del titular |
| Lemon | Cita textual cláusula 3.7 T&C (responsabilidad exclusiva del titular y deber de custodia) | Primario (documento contractual) | No | Alta |
| Lemon | Constancia de no haber recibido notificación de reembolso de Apple; compromiso de acreditar automáticamente si Apple lo procesa | Declaración de parte profesional | No | Media |

Immaterial:
- Logos y elementos de marca de ambas piezas.

## Application
- **Protección:** No se acredita daño imputable a Lemon. El riesgo proviene del entorno doméstico del titular (dispositivo accesible a una menor) y de la política de reembolsos de Apple, no de un servicio defectuoso de Lemon.
- **Información / Transparencia:** No se alega ni se acredita que la oferta de la Lemon Card o el flujo de pago hayan sido opacos o engañosos. No hay límites ocultos en juego.
- **Buena fe:** Lemon responde citando la cláusula, explica el camino correcto (gestionar el reembolso ante Apple) y se compromete a acreditar fondos automáticamente si Apple los devuelve. Conducta de buena fe.
- **In dubio (tiebreaker):** No se activa: la cuestión no está empatada. La operación fue válidamente autenticada y el reembolso depende del comercio, no del emisor.
- **Educación / No discriminación:** No están en juego.
- **T&C compatibility:** La cláusula 3.7 es consistente con A.1 y A.4 en este contexto: imputar la responsabilidad de una operación autenticada al titular del dispositivo y de la tarjeta no contradice la protección del consumidor, especialmente cuando el reclamo es contra el comercio destinatario (Apple) y no contra un fallo del emisor.

## Jurisdiction / Morality / Validity
Jurisdicción correcta (Blockchain No Técnica, fintech consumidor argentino). No hay cuestiones de moralidad ni de validez. Pregunta bien planteada.

## Schelling-Point check
Un panel diligente convergerá en Favor Lemon: pago con tarjeta autenticado, fondos ya en poder del comercio, vía de reembolso disponible (Apple), sin incumplimiento acreditado de la Política A por parte de Lemon.

## Bias audit
La narrativa del "niño pequeño" genera simpatía pero es inmaterial frente a la regla: el titular custodia el dispositivo y el medio de pago. No se ha permitido que el factor emocional reemplace evidencia material.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user seeks reimbursement of an ARS 74,855.52 card payment to APPLE.COM/BILL executed on 30 March 2025 from his Lemon Card (VISA *6301), claiming his 5-year-old daughter accidentally confirmed the purchase. Lemon's back-office record (Trx ID 0acb6e68-71b2-48db-8ab5-0504029e031e) confirms the transaction was completed with valid credentials and that funds were transferred to the merchant. The user provides no evidence of any security failure on Lemon's side, of unauthorised access to the account, or of a refund request lodged and processed with Apple.

Under Política A, no breach is shown. Información and Transparencia are not implicated — there is no hidden term or misleading offer at issue. Protección does not extend to losses caused by the cardholder's own custody of the device and card under a properly authenticated card payment to a third-party merchant. Lemon acted in Buena fe by citing the operative clause, explaining the correct channel (Apple's refund process) and committing to credit any refund the merchant remits. The In dubio tiebreaker does not apply because the question is not in genuine equipoise.

Lemon's T&C clause 3.7, placing exclusive responsibility for operations executed from the account on the holder and imposing a custody duty over access credentials and payment means, is compatible with Section A on these facts. The presence of a minor handling the device is a custody failure attributable to the holder, not to Lemon, and a card-issuer is not the proper party to reverse a completed merchant charge absent a chargeback or merchant refund. Vote: Favor Lemon.
