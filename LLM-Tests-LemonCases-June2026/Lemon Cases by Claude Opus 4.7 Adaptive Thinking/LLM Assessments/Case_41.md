# Case 41 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Transferencia saliente (CVU/CBU push payment) desde Lemon a una cuenta externa de titularidad del propio usuario
**Amount in dispute:** ARS 33.500,00
**Question:** ¿Debe Lemon responder al usuario por una transferencia debitada de su cuenta Lemon que él afirma no llegó al destinatario, cuando la red de pagos (COELSA) reporta la operación como "Completado"?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Protección al usuario** — Lemon, como PSP, debe responder por fallos imputables a su operatoria.
2. **Información** — Debe entregar comprobantes y trazabilidad de la operación.
3. **Transparencia** — Debe explicar el estado real de la transferencia y los pasos siguientes.
4. **Buena fe** — Ambas partes deben actuar diligentemente; el usuario debe reclamar al actor correcto.
5. **In dubio pro usuario** — tiebreaker.
6. **Educación financiera** — Lemon debe orientar al usuario sobre cómo verificar la acreditación en el banco destino.
7. **No discriminación** — N/A.
- **Sección B (T&C vs Sección A):** ninguna cláusula puede impedir el reembolso si la falla es imputable a Lemon.

## Burden of proof
Acreditado el débito por el usuario, recae sobre Lemon demostrar que cumplió su parte (ejecución correcta y entrega al circuito interbancario). Acreditada la ejecución por Lemon, recae sobre el usuario probar que la falla fue imputable a Lemon (y no al banco destinatario o al circuito posterior).

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Comprobante Lemon: ARS 33.500 enviado 04/07/2024 14:08, a CBU 0000076500000024604624 (Banco destino: CVU), CUIT 20456917896, mismo titular, COELSA ID LOEJWV9J0WZV746Z2QMD0G | Screenshot | No | Alto — prueba el débito y la generación de la orden |
| Usuario | Afirmación de que "el destinatario no recibió los fondos" | Declaración | Sin prueba documental (no hay extracto del banco destino) | Bajo |
| Lemon | Consulta interna a COELSA con el mismo COELSA ID, estado **CASHOUT [Completado]**, -33.500 ARS, fecha 4/7/2024 14:08:28, usuario origen DIGIFIN SA | Screenshot del admin tool | No rebatido por el usuario | Alto — corrobora que la transferencia salió y fue procesada por la cámara compensadora |
| Lemon | Indicación al usuario de reclamar al proveedor de la cuenta de destino si aún no se acreditó | Declaración procesal | No rebatida | Medio |

Immaterial:
- Logos y elementos de marca.
- Hora/batería de captura.

## Application
- **Protección:** Lemon ejecutó la orden y la entregó al circuito (COELSA "Completado"). La obligación de Lemon se cumple al despachar correctamente la transferencia al banco destino. No hay indicio de que el problema sea imputable a Lemon.
- **Información:** Lemon proporcionó comprobante con COELSA ID y datos completos del destinatario; ese ID permitió la verificación. Cumple.
- **Transparencia:** Lemon expuso de forma verificable el estado real ("Completado") y señaló al usuario el actor correcto al cual reclamar (banco/proveedor destino). Cumple.
- **Buena fe:** Lemon actuó diligentemente al consultar COELSA y compartir el resultado. El usuario, por su parte, no aportó ninguna evidencia de no acreditación en el banco destino (extracto, captura, ticket del banco receptor) pese a que el destinatario es él mismo y tendría acceso trivial a esa prueba. La carga de demostrar la no acreditación recae naturalmente sobre quien afirma el hecho negativo respecto de su propia cuenta.
- **In dubio pro usuario:** No aplica como regla decisoria porque la evidencia documental aportada por Lemon (COELSA Completado) no fue rebatida y resuelve la duda sustantiva. El tiebreaker solo opera ante empate probatorio real.
- **Educación:** Lemon orientó correctamente al usuario sobre dónde dirigir su reclamo (proveedor de la cuenta destino).
- **No discriminación:** N/A.
- **T&C vs Sección A:** No invocadas; sin conflicto.

## Jurisdiction / Morality / Validity
Caso válido y dentro de competencia: disputa de consumo entre usuario y Lemon, con descargos de ambas partes y evidencia identificable. No corresponde RtA.

## Schelling-Point check
Un jurado diligente, leyendo que el usuario solo afirma la no llegada sin un solo soporte del banco receptor, frente a una captura del backend que muestra "Completado" en COELSA con el mismo ID del comprobante del usuario, convergería en Favor Lemon. La responsabilidad de un PSP termina en la entrega al circuito interbancario cuando la cámara confirma la operación.

## Bias audit
Verifiqué no estar aplicando in dubio como atajo: aquí existe evidencia afirmativa, no un empate. Tampoco estoy presumiendo mala fe del usuario — simplemente no aportó la prueba mínima (extracto del banco receptor, que es él mismo) que estaría a su alcance. Si la hubiera aportado, el caso bascularía.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user proved only that ARS 33,500 was debited from his Lemon account on 04/07/2024 14:08 and that a transfer receipt with COELSA ID LOEJWV9J0WZV746Z2QMD0G was issued. Lemon produced an internal COELSA lookup using that same ID showing the cashout status as "Completado" with matching amount, date and timestamp. Under Protección and Buena fe, a PSP discharges its duty by correctly executing the order and delivering it to the interbank clearing house; once COELSA reports the cashout as completed, the funds are in the hands of the destination provider, not Lemon.

The user offered no rebuttal — no statement, screenshot or ticket from the receiving bank (whose account he owns) showing non-credit. Given that the destination account is his own, that evidence would be trivial to produce, and its absence is dispositive on burden of proof. Lemon also satisfied Información, Transparencia and Educación by providing the COELSA ID on the receipt, explaining the lookup, and directing the user to the correct counterparty (the destination provider) for any remaining non-credit issue.

In dubio pro usuario does not apply because there is no evidentiary tie: unrebutted backend evidence resolves the substantive question in Lemon's favor. No Section A principle is breached and no T&C override is invoked. Vote: Favor Lemon.
