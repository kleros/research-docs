# Case 122 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** ARS withdrawal (Retiro de ARS) via Lemon — CBU transfer
**Amount in dispute:** ARS 110.000
**Question:** Should Lemon refund ARS 110.000 to a user who claims he sent the transfer by mistake to the wrong recipient (Renato Sebastian Fernandez), where the user himself confirmed and executed the transaction?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Sección A — Protección del usuario** (mitigar daño injusto).
2. **Sección A — Información**: la oferta tal como se presenta gobierna.
3. **Sección A — Transparencia**: condiciones y consecuencias deben ser claras.
4. **Sección A — Buena fe**: ambas partes deben actuar de buena fe.
5. **Sección A — In dubio pro usuario** (TIEBREAKER únicamente).
6. **Sección A — Educación financiera** del usuario.
7. **Sección A — No discriminación**.
8. **Sección B**: T&C ceden frente a Sección A si hay conflicto; en ausencia de conflicto, T&C aplican.
9. **T&C Cuenta de Pago, Cláusulas 3.b/3.c/3.e y 4.c**: las instrucciones de pago son mandato irrevocable; el usuario es exclusivamente responsable por datos de destinatario; Digifin/Lemon no responde por errores u omisiones en la cuenta indicada por el usuario.

## Burden of proof
El usuario, como parte que busca alterar el estado por defecto (transferencia ya ejecutada e irrevocable hacia un CBU bancario externo), tiene la carga de demostrar incumplimiento de Lemon o violación de la Sección A.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura app: retiro ARS 110.000 a CBU 00000031000076464379022, destinatario Renato Sebastian Fernandez, 09/04/2026 22:27, estado "Completo" | Primary (screenshot propia) | No | High — confirma que la operación se ejecutó como instruida |
| Usuario | Afirmación: contactó soporte sin respuesta | Secondary (afirmación sin prueba) | Sí (Lemon explica que la operación es irreversible una vez enviada) | Low — sin captura de chat ni ticket |
| Lemon | Back-office VIRTUAL_WITHDRAWAL: Trx ID coincidente, monto, CBU, destinatario, fecha, estado "Completada" | Primary | No | High — corrobora ejecución según instrucción del usuario |
| Lemon | Capturas del flujo "Enviar ARS" mostrando pantalla de confirmación "Confirmá tu envío" con Nombre/Banco/CBU y "Deslizá para confirmar" | Primary (UI) | No | High — demuestra que hay pantalla de confirmación previa, oferta-tal-como-presentada |
| Lemon | T&C Cláusulas 3.b, 3.c, 3.e, 4.c | Primary (contrato aceptado) | No | High — asigna responsabilidad exclusiva al usuario por datos erróneos |

Immaterial:
- "No reconozco al destinatario" — irrelevante: el usuario admite haber ordenado la transferencia; la titularidad del CBU destino no la elige Lemon.

## Application
- **Protección:** No se identifica daño causado por Lemon. El daño surge de la propia instrucción del usuario; protegerlo requeriría trasladar pérdida a Lemon sin culpa de Lemon.
- **Información:** El flujo de envío informa Nombre, Banco y CBU del destinatario antes de confirmar. Cumple.
- **Transparencia:** Pantalla "Confirmá tu envío" con datos del destinatario y gesto deliberado ("Deslizá para confirmar"). No hay límites ocultos. Cumple.
- **Buena fe:** Lemon ejecutó la instrucción tal cual; el usuario confirma haber realizado la operación y admite el error. Ambos de buena fe; el error es del usuario.
- **In dubio:** No aplica — no hay duda razonable sobre los hechos ni sobre el cumplimiento de Lemon.
- **Educación financiera:** La interfaz educa sobre el destinatario antes de confirmar (nombre legible). Cumple.
- **No discriminación:** No invocada, no aplica.
- **Compatibilidad T&C ↔ Sección A:** Las cláusulas 3.b/3.c/3.e/4.c (irrevocabilidad y responsabilidad por datos erróneos del usuario) reflejan el funcionamiento real del sistema de pagos interbancarios (CBU/COELSA) y no contradicen Sección A cuando la plataforma ya ha cumplido Información y Transparencia. No son cláusula-paraguas abusiva; describen una limitación operativa real.

## Jurisdiction / Morality / Validity
Jurisdicción correcta (disputa de producto fintech no técnica). Sin temas de moralidad. Pregunta válida y respondible.

## Schelling-Point check
Un panel diligente convergerá en Favor Lemon: el usuario admite el error propio, la UI de Lemon mostró destinatario y pidió confirmación deslizable, y la transferencia bancaria por CBU es operacionalmente irreversible. Es el resultado obvio y defendible bajo Sección A + T&C.

## Bias audit
Riesgo de simpatía hacia el usuario por la pérdida monetaria significativa (ARS 110.000). Descartado: la Sección A protege contra daño *injusto* causado por la plataforma, no contra errores propios del usuario; favorecer al usuario aquí sería trasladar arbitrariamente la pérdida a Lemon sin fundamento de incumplimiento.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user admits he himself executed an ARS 110,000 withdrawal to a CBU belonging to a recipient he did not intend to pay. Lemon's evidence shows the standard send-ARS flow displays the recipient's Name, Bank and CBU on a "Confirmá tu envío" screen requiring a deliberate slide-to-confirm gesture, and the back-office record matches the user's own screenshot down to the Trx ID. Under Sección A (Información and Transparencia), the offer as presented gave the user the information needed to verify the destination before authorising; there are no hidden terms or undisclosed limits.

The T&Cs (Clauses 3.b, 3.c, 3.e and 4.c) assign exclusive responsibility for payment-instruction data to the user and reflect the operational reality of the BCRA/COELSA interbank rail: once a CBU transfer is executed it leaves Lemon's ecosystem and cannot be unilaterally reversed by the PSPCP. These clauses are not an abusive catch-all overriding Sección A — they describe a genuine technical constraint, and Sección A is not engaged because Lemon discharged its Información, Transparencia and Buena fe duties.

There is no factual ambiguity, so the in-dubio tiebreaker does not apply. Recovery of the funds, if possible, is a matter between the user and the recipient (or the receiving bank), not Lemon. The claim is rejected.

---
Case 122 | VOTE: Favor Lemon | CONFIDENCE: high | User admits self-executed transfer; Lemon UI showed destinatario and required slide-to-confirm; CBU transfer operationally irreversible; no Sección A breach.
