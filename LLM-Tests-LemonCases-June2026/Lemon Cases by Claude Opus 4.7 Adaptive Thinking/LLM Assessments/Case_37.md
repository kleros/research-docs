# Case 37 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Transferencia saliente desde cuenta Lemon (ARS) a CBU/CVU externa en Banco Santander Argentina
**Amount in dispute:** ARS 100.000
**Question:** ¿Debe Lemon reintegrar al usuario una transferencia saliente de ARS 100.000 que el usuario afirma fue enviada a una cuenta de Santander cerrada, cuando la transferencia fue ejecutada y acreditada en el sistema interbancario?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Sección A (Lemon ToS) — siete principios (Protección, Información, Transparencia, Buena fe, In dubio pro consumidor [tiebreaker], Educación, No discriminación).
2. Sección B — los T&Cs ceden frente a la Sección A en caso de conflicto.
3. Normas operativas del sistema de transferencias inmediatas argentino (Coelsa / CBU-CVU): el emisor (Lemon) cumple su obligación al ejecutar la transferencia ordenada por el usuario hacia el CBU/CVU indicado; la imputación final corresponde al banco receptor. El usuario es responsable de los datos del destinatario que carga.
4. Buena fe: si la entidad receptora aceptó los fondos, el reclamo de devolución debe canalizarse contra ésta, no contra el emisor.

## Burden of proof
El usuario debe demostrar un incumplimiento atribuible a Lemon (error en la ejecución, omisión de información, mala fe). Una vez que Lemon prueba la ejecución exitosa de la orden hacia el CBU cargado por el usuario, la carga vuelve al usuario para demostrar que el incumplimiento es de Lemon y no del banco receptor.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Certificado de Banco Santander (10/06/2024) constatando cuenta Nº 254902 de Benjamin Eira dada de baja el 18/12/2023 | Primary | No | Medium — acredita que la cuenta nominal estaba cerrada, pero no que Lemon haya cometido un error |
| Usuario | Afirmación de que la transferencia no ingresó al destinatario ni regresó | Statement | No directamente | Low — sin extractos de Lemon que muestren no-reverso, sin reclamo formal documentado |
| Lemon | Captura del back-office VIRTUAL_WITHDRAWAL "Completada" por ARS 100.000 con Coelsa ID, país Argentina | Primary | No | High — prueba ejecución exitosa de la orden en el sistema interbancario |
| Lemon | Manifestación de que Santander recibió la transferencia y orientación al usuario de denunciar ante el banco | Statement | No | Medium — coherente con la captura Coelsa |

Immaterial:
- Detalles personales del titular de la cuenta destino (familiar) salvo para acreditar la baja.
- Fecha del certificado (junio 2024) frente a la fecha de la transferencia — el usuario no aporta la fecha de la operación, pero la baja es previa (18/12/2023).

## Application
- **Protección:** Lemon ejecutó la orden conforme a los datos provistos por el usuario; no hay falla de custodia ni de ejecución imputable.
- **Información:** No hay alegación de información engañosa por Lemon sobre el producto de transferencia.
- **Transparencia:** El comprobante interno (Coelsa ID, estado "Completada") es transparente y verificable.
- **Buena fe:** Lemon orientó al usuario al canal correcto (denuncia ante banco receptor). No hay conducta evasiva probada de Lemon; el usuario califica las respuestas como "evasivas" pero no aporta chats.
- **In dubio pro consumidor:** No se activa — no hay empate probatorio; la prueba de ejecución (Coelsa ID) es primaria y no rebatida.
- **Educación:** No es el eje del caso.
- **No discriminación:** No invocada.
- **Compatibilidad T&C / Sección A:** El reparto de responsabilidades entre emisor y receptor en transferencias CBU es estándar y no contradice la Sección A.

## Jurisdiction / Morality / Validity
Caso válido y arbitrable. La controversia es contractual / operativa y no presenta cuestiones de moralidad. La pretensión del usuario, si existe, recae sobre Banco Santander (que aceptó fondos a una cuenta cerrada) y no sobre Lemon.

## Schelling-Point check
Un jurado razonable y diligente seguiría la regla básica de pagos: quien ejecuta correctamente la orden hacia el CBU indicado por el cliente queda liberado; el reclamo se dirige al banco receptor. La captura Coelsa "Completada" es prueba dispositiva. Vote esperado: Favor Lemon.

## Bias audit
Tentación a aplicar in dubio pro consumidor por simpatía con un usuario que perdió dinero. Resistida: no hay duda relevante — Lemon probó ejecución, el usuario no probó error de Lemon. El daño existe pero no es atribuible al emisor.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user transferred ARS 100,000 from Lemon to a Santander account that, per a Santander certificate dated 10 June 2024, had been closed on 18 December 2023. Lemon produced a back-office screenshot showing the VIRTUAL_WITHDRAWAL as "Completada" with a Coelsa ID — primary, unrebutted evidence that Lemon executed the order to the CBU/CVU the user provided. Under standard Argentine immediate-transfer rules, the sender's obligation ends with successful execution into the interbank rail; final crediting and any reversal for an account that is closed are the receiving bank's responsibility.

Applying Sección A: Protección, Información, Transparencia and Buena fe are all satisfied — Lemon discharged the order, supplied a verifiable Coelsa identifier, and pointed the user to the correct remedy (a claim against Santander, which accepted funds despite the alleged closure). There is no evidentiary tie, so In dubio pro consumidor does not engage. The user's certificate proves the destination account was closed but does not prove any breach by Lemon; the proper defendant is Santander.

Accordingly, the claim against Lemon fails. Vote: Favor Lemon, high confidence.
