# Case 87 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Envío de soles (PEN) vía Plin desde Lemon — operación de cash-out fiat ejecutada el 13/03/2025.
**Amount in dispute:** S/ 50 PEN (el descargo de Lemon menciona erróneamente "SOLES 50.000"; la captura del usuario y el back-office de Lemon coinciden en S/ 50).
**Question:** ¿Debe Lemon responder por una transferencia P2P (Plin) que su sistema ejecutó conforme a las instrucciones del usuario y que figura como "Completo", cuando el usuario afirma que la cuenta de destino no acreditó los fondos?

## Options
- Favor User — Lemon debe reembolsar o compensar al usuario.
- Favor Lemon — el reclamo se rechaza; la gestión debe canalizarse ante Plin / banco destinatario.
- Refuse to Arbitrate — no aplica (jurisdicción y validez claras).

## Governing rules
1. **Política Sección A — Información y Transparencia:** Lemon debe informar con claridad el estado real de la operación según la oferta tal como se presenta.
2. **Política Sección A — Protección al Consumidor:** los usuarios no deben quedar indefensos ante fallas atribuibles a la plataforma.
3. **Política Sección A — Buena fe:** ambas partes deben actuar de buena fe.
4. **Política Sección A — In dubio pro consumidor:** TIEBREAKER solo si la prueba queda en empate genuino.
5. **Sección B — T&Cs vs Sección A:** los T&C de Lemon establecen que las transferencias se ejecutan conforme a las instrucciones del usuario y son irreversibles una vez enviadas; las cláusulas catch-all no anulan A, pero no son inconsistentes cuando la ejecución fue correcta.
6. **Carga de prueba:** quien alega un fallo imputable al proveedor debe probarlo; la evidencia no rebatida se presume genuina.

## Burden of proof
El usuario alega un incumplimiento de Lemon; le corresponde demostrar que Lemon ejecutó mal la orden (datos erróneos, ruteo equivocado, retención indebida). Lemon debe acreditar que ejecutó según las instrucciones.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura "Envío de Soles S/ 50 — Completo" a David Perci Torres Senmache, CCI ...9500169046, ID 20250313200848092241525422206 | Primaria (screenshot app Lemon) | No | Alta — pero prueba **ejecución exitosa**, no falla de acreditación |
| Usuario | Captura "Movimientos" mostrando débito de S/ 50 el 13/03 en su cuenta Lemon | Primaria | No | Alta — confirma que el dinero salió de Lemon |
| Usuario | Captura "Historial de movimientos" de una segunda app (aparentemente Yape/cuenta tercero) sin entrada de +S/50 el 13/03 ~20:08 | Secundaria (cuenta no identificada como del destinatario nombrado) | Parcialmente rebatida (Lemon no controla Plin) | Baja — no prueba que sea la cuenta del destinatario David P. T. Senmache; podría ser cuenta propia o de otra persona |
| Lemon | Back-office "PERUVIAN_FIAT_CASH_OUT CREATED" mostrando CCI destino terminando en 9500169046 (mismo CCI que el usuario instruyó) | Primaria | No | Alta — confirma ejecución conforme a las instrucciones |
| Lemon | T&Cs: transferencias irreversibles una vez ejecutadas; Lemon no opera Plin | Documental | No | Media — relevante para alcance de responsabilidad |
| Lemon | Indicación al usuario de iniciar reclamo ante Plin con el ID de operación | Procesal | No | Media — muestra orientación constructiva |

Immaterial:
- Mención de "SOLES 50.000" en el descargo de Lemon — error tipográfico evidente; toda la prueba primaria coincide en S/ 50.
- Capturas Yape de transacciones no relacionadas (Rosa AU, Marilen, Carmen, Erika M, Maria D) — no son del destinatario nombrado y no refutan la acreditación a la cuenta CCI específica.

## Application
- **Protección:** no hay daño imputable a Lemon — el patrimonio del usuario salió por una orden que el propio usuario impartió y que se ejecutó al CCI que él indicó. La protección no abarca riesgos del rail receptor (Plin/banco) que Lemon no controla.
- **Información:** Lemon entregó constancia, ID de operación y CCI destino. La etiqueta "Completo" refleja correctamente el estado del *envío* desde Lemon (la oferta tal como se presentó es un cash-out a Plin, no una garantía de acreditación bancaria).
- **Transparencia:** la oferta de "Envío de Soles" vía Plin, según se presenta en la app, es la ejecución de la transferencia con los datos del usuario. No hay límite oculto ni cláusula escondida que entre en conflicto con la Sección A.
- **Buena fe:** Lemon respondió, identificó el ID de operación, sugirió canal correcto (Plin) y aportó back-office concordante. El usuario actuó de buena fe pero no acredita el supuesto fáctico clave (que el destinatario nombrado no recibió en la CCI indicada).
- **In dubio:** no se activa — la prueba no está en empate; la evidencia primaria de ambas partes converge en una ejecución correcta.
- **Educación:** Lemon orientó al usuario hacia el canal de reclamo correcto.
- **No discriminación:** no aplica.
- **T&C compatibility:** la cláusula de irreversibilidad y limitación de alcance fuera del rail propio es compatible con Sección A en este caso, porque no hay un fallo de Lemon que la cláusula esté siendo usada para encubrir.

## Jurisdiction / Morality / Validity
Pasa los tres filtros — subcourt Blockchain No Técnica (Lemon) es correcto; sin morality flag; pregunta bien formada y respondible.

## Schelling-Point check
Un panel diligente convergerá en Favor Lemon — la evidencia primaria muestra ejecución correcta al CCI instruido; el riesgo de no-acreditación en el rail Plin/banco destinatario escapa al control y responsabilidad razonable de Lemon, y el usuario no aporta prueba (constancia bancaria del destinatario David P. T. Senmache, gestión con su banco, etc.) que invierta esa presunción.

## Bias audit
Verificado — el resultado no depende de identidad ni retórica; la captura Yape del usuario es vívida pero inmaterial porque no se identifica como la cuenta del destinatario nombrado. Se confirmó cronología (orden → ejecución → reclamo) y se valoró la concordancia del CCI entre ambas partes.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
The user instructed a S/ 50 PEN transfer from Lemon to a Plin account (CCI ending 9500169046) on 13 March 2025. Both parties' primary evidence agrees on the operative facts: Lemon's user-facing screen shows the transfer as "Completo" with operation ID 20250313200848092241525422206, and Lemon's internal back-office record shows the same CCI as destination. The user's account history confirms the S/ 50 debit. Lemon therefore executed the order exactly as instructed.

Under Section A of the Policy, Information and Transparency are assessed against the offer as presented. Lemon's product is a cash-out instruction to the Plin rail; the "Completo" status correctly reflects that Lemon delivered the funds per the user's instructions. Protección al Consumidor does not extend to outcomes on a downstream payment rail that Lemon does not operate, especially where the user has not produced any evidence from the named recipient (David Perci Torres Senmache) or his bank showing non-credit to that specific CCI. The Yape history screenshots submitted are not identified as the named recipient's account and therefore do not rebut Lemon's evidence.

The T&C clause invoked by Lemon (irreversibility once executed; no operational control over Plin) is compatible with Section A on these facts because it is not being used to mask a Lemon failure — execution was correct. In dubio pro consumidor is a tiebreaker only and is not triggered, because the evidentiary balance is not equal: Lemon's primary execution evidence is unrebutted. The user's avenue is a claim with Plin / the destination bank using the operation ID Lemon provided. Vote: Favor Lemon.

---

Case 87 | VOTE: Favor Lemon | CONFIDENCE: medium | Lemon executed S/50 transfer to user-instructed CCI; "Completo" status accurate; non-credit on Plin rail is outside Lemon's control and user did not rebut execution.
