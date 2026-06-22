# Case 110 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Retiro ARS a CBU/alias externo (transferencia bancaria saliente vía COELSA)
**Amount in dispute:** ARS 10,000
**Question:** ¿Debe Lemon responder por una transferencia de ARS 10,000 que el propio usuario instruyó hacia un alias equivocado y que fue ejecutada irrevocablemente por el sistema interbancario?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. Política Sección A — Protección al Consumidor (Art. 42 CN, Ley 24.240).
2. Información clara, cierta y detallada (Art. 4 LDC).
3. Transparencia en la oferta y en el proceso operativo.
4. Buena fe en la ejecución (Art. 961 CCCN).
5. In dubio pro consumidor (Art. 3 LDC) — únicamente tiebreaker.
6. Deber de educación financiera.
7. No discriminación.
8. Sección B — los T&C ceden si contradicen la Sección A. La irreversibilidad por COELSA es una característica del sistema bancario, no una cláusula abusiva.

## Burden of proof
El usuario reclama una devolución contra el estado de hecho por defecto (la transferencia ya está ejecutada). Debe acreditar (i) un incumplimiento de Lemon o (ii) una falla del sistema que lo indujo al error.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Comprobante de retiro ARS 10.000 a CBU 0000003100053699935698 — destinataria "Ana Maria Beltran Aspi", 20/06/2025 00:53, estado "Completo", COELSA ID presente | Primaria | No | Alta — confirma ejecución irrevocable vía COELSA |
| Usuario | Manifestación de que ingresó un alias equivocado por error humano | Secundaria (declaración de parte, autoincriminatoria) | No | Alta — admisión expresa de error propio |
| Lemon | Capturas del flujo de envío ARS con pantalla "Confirmá tu envío" mostrando Nombre, Banco, CBU y el monto, con confirmación por deslizamiento | Primaria (UI del producto) | No | Alta — acredita cumplimiento del deber de información previo a la ejecución |
| Lemon | Explicación técnica: COELSA procesa de forma inmediata y definitiva; Lemon es intermediario sin injerencia post-envío | Secundaria pero notoria | No | Alta — acorde a la operativa bancaria argentina |

Immaterial:
- Necesidad económica del usuario (alimentos, gastos esenciales) — emotivo, no acredita incumplimiento de Lemon.
- Referencia genérica a soporte sin "no recibí solución" — no se aporta transcripción ni promesa de devolución por parte de Lemon.

## Application
- **Protección:** El régimen protege al consumidor frente al proveedor, no frente a errores propios cuando el proveedor cumplió. No hay defecto del servicio que proteger.
- **Información:** Lemon mostró Nombre, Banco, CBU y monto en pantalla de confirmación antes de ejecutar. Deber de información cumplido.
- **Transparencia:** El flujo es transparente y exige confirmación activa (deslizar). No hay límites ocultos ni asimetrías informativas.
- **Buena fe:** Lemon ejecutó la orden del usuario tal como fue confirmada; sugiere reclamo al destinatario / denuncia policial. Conducta de buena fe.
- **In dubio:** No procede — no hay duda razonable; el usuario admite el error propio y Lemon documenta el flujo de confirmación.
- **Educación:** El flujo educa al usuario al exigir verificación previa del destinatario. Cumplido.
- **No discriminación:** No invocado ni relevante.
- **T&C vs Sección A:** Los T&C que reconocen la irreversibilidad post-COELSA describen una realidad técnica del sistema bancario argentino; no son una cláusula abusiva que ceda ante la Sección A.

## Jurisdiction / Morality / Validity
Pasa. Disputa de consumo financiero argentino, dentro del alcance del subcourt "Blockchain No Técnica" para Lemon.

## Schelling-Point check
Un panel diligente convergerá en Favor Lemon: el usuario admite expresamente el error de ingreso del alias, Lemon acredita pantalla de confirmación previa, y la irreversibilidad COELSA es un hecho técnico no controlable por Lemon. El reclamo correcto es contra el destinatario indebido.

## Bias audit
La situación económica del usuario genera simpatía, pero no es prueba de incumplimiento. Removiendo el sesgo emocional, el caso es claro: error confeso del usuario sobre un sistema que funcionó como debía.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The User expressly admits that the loss arose from his own input error when entering the destination alias for an ARS 10,000 transfer. Lemon's submitted screenshots of the "Send ARS" flow show a confirmation screen that displays Name, Bank, CBU and amount and requires an active slide-to-confirm gesture before execution. This satisfies the duties of Information and Transparency under Section A of the Policy (Art. 4 LDC). The transaction receipt shows a completed transfer with a COELSA ID, confirming that funds left Lemon's perimeter through the Argentine interbank rail and became operationally irreversible — a characteristic of the system, not an abusive T&C clause under Section B.

With the service performing as offered and the user-side error conceded, the Buena Fe and Protección al Consumidor principles do not entitle the User to a refund from Lemon. Lemon is an instruction intermediary; it has no legal or operational power to claw back funds already settled by COELSA, and the proper avenues are a private claim against the unintended recipient or a police report, as Lemon correctly noted. The In Dubio Pro Consumidor tiebreaker does not engage because there is no genuine doubt — the user's own statement closes the factual question.

For these reasons, and consistent with the Schelling-point reading that diligent jurors will converge on for self-inflicted misdirected-transfer claims where the platform's confirmation UI was complete, the appropriate vote is Favor Lemon.
