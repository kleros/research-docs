# Case 44 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Transferencia fiat (ARS) saliente vía Lemon / Digifin a un alias de Mercado Pago
**Amount in dispute:** ARS 88.000,00 (un primer envío de prueba de ARS 2.000 más la transferencia principal de ARS 88.000 a `$malu_fernandez5` / Barbara Mercedes Mendez Navarro)
**Question:** ¿Debe Lemon reembolsar al usuario los fondos transferidos por error a un tercero, cuando el alias destinatario fue suministrado erróneamente por un tercero ajeno a Lemon?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política de Lemon, Sección A — Principios rectores: Protección, Información, Transparencia, Buena fe, In dubio pro consumidor (tiebreaker), Educación, No discriminación.
2. Política de Lemon, Sección B — Los T&C ceden frente a Sección A en caso de conflicto.
3. T&C de la operatoria fiat (Digifin), punto 3(e) invocado por Lemon: la responsabilidad por la exactitud de los datos de la transferencia (alias, CBU/CVU, destinatario) recae en el usuario que la ejecuta.
4. Naturaleza de la red de pagos minoristas argentina: las transferencias inmediatas vía CBU/CVU/alias son irrevocables una vez acreditadas en la cuenta destino (Com. BCRA "A" 7153 y conc.); el devolver requiere acción del receptor o de su banco/PSP, no del emisor.

## Burden of proof
El usuario alega un error inducido por un tercero ajeno a Lemon y solicita que Lemon recupere los fondos. La carga de demostrar (i) una falla de Lemon o (ii) que Lemon tiene la capacidad y obligación de revertir la operación recae en el usuario. Lemon, a su vez, debe demostrar que el flujo fue claro y que la confirmación final fue del usuario.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura "¡El envío se ha realizado con éxito! Enviaste ARS 2.000,00 a $malu_fernandez5" | Screenshot app | No | Media — confirma envío de prueba al mismo alias |
| Usuario | Comprobante Lemon de ARS 88.000 a Barbara Mercedes Mendez Navarro, CBU Mercado Pago, COELSA ID, ID transacción | Comprobante de transferencia | No | Alta — prueba ejecución exitosa de la transferencia principal |
| Usuario | Alegación: "error en el alias proporcionado, lo cual resultó en transferencia… error causado por información incorrecta suministrada por un tercero" | Declaración | No rebatida pero auto-incriminatoria | Alta — el propio usuario admite que el dato erróneo provino de un tercero, no de Lemon |
| Lemon | Cita de T&C Digifin punto 3(e): la verificación del alias/destinatario es responsabilidad del usuario | Cita contractual | No rebatida | Alta |
| Lemon | Declaración sobre irreversibilidad de la transferencia una vez confirmada | Declaración técnica/operativa | No rebatida; coherente con el sistema de transferencias inmediatas del BCRA | Alta |

Immaterial:
- Logos y encabezados Kleros/Lemon en los PDFs.
- Diferencia menor en el número de caso citado por Lemon ("37" vs. "44") — error material que no afecta el fondo.

## Application
- **Protección:** El principio protege al consumidor frente a fallas del proveedor, no frente a errores del propio consumidor inducidos por terceros ajenos a Lemon. El usuario reconoce que el alias erróneo provino de "un tercero", no de Lemon.
- **Información:** El comprobante muestra de forma legible alias, nombre completo del destinatario (Barbara Mercedes Mendez Navarro), CUIT, CBU y banco destino antes/después de la confirmación. La oferta "as presented" desplegó toda la información necesaria para que el usuario detectara la discrepancia entre destinatario esperado y el efectivamente listado.
- **Transparencia:** Lemon evidencia los datos del destinatario en pantalla y emite comprobante completo. No se alegan campos ocultos ni condiciones sorpresivas.
- **Buena fe:** No hay indicio de mala fe de Lemon: no participó en la generación del alias erróneo, no obtuvo beneficio y respondió por escrito al reclamo. El usuario también actúa de buena fe pero admite el error humano propio.
- **In dubio pro consumidor:** Es un tiebreaker; aquí no hay duda razonable — los hechos son admitidos por el usuario y la causa del daño es ajena a Lemon.
- **Educación:** Lemon habría podido reforzar advertencias de "verificá el destinatario", pero el propio usuario describe haber visto el nombre del destinatario en el comprobante; la información estaba a la vista.
- **No discriminación:** No aplica.
- **T&C compatibility:** El punto 3(e) de los T&C Digifin (verificación a cargo del usuario) es compatible con Sección A: no exonera a Lemon de fallas propias, sino que asigna riesgo razonable de error de tipeo/alias al ordenante, coherente con la arquitectura de pagos minoristas argentinos. No es una cláusula "catch-all" que pretenda anular protección consumeril.

## Jurisdiction / Morality / Validity
Disputa válida, dentro del alcance de la subcorte (consumer protection Lemon Cash), no inmoral ni inválida. No corresponde Refuse to Arbitrate.

## Schelling-Point check
Un panel diligente y políticamente alfabetizado convergería en Favor Lemon: (i) el usuario admite expresamente que el error provino de un tercero y de su propia confirmación; (ii) las transferencias inmediatas CBU/CVU son irreversibles por diseño regulatorio, no por capricho de Lemon; (iii) la información del destinatario (nombre real + CBU + banco) estaba visible antes y después de la operación; (iv) no se imputa a Lemon falla técnica, publicidad engañosa, ni incumplimiento. Es un escenario clásico de "user-caused mistaken payment", que en jurisprudencia comparada y en la lógica Schelling se resuelve sistemáticamente contra el ordenante.

## Bias audit
Se ha resistido el sesgo pro-consumidor automático: la simpatía por una pérdida monetaria considerable no convierte a Lemon en responsable cuando la causa es ajena. También se descartó un sesgo pro-empresa: si hubiese habido alias ocultos, ambigüedades en la pantalla o cambio de destinatario tras confirmación, el voto cambiaría. No los hay en el expediente.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user candidly states that the loss was caused by an erroneous alias supplied by a third party and confirmed by the user inside the Lemon app. The transfer receipt the user himself submitted shows the recipient's full legal name, CUIT, CBU and destination bank (Mercado Pago) — all the data needed to detect the mismatch before pressing confirm. Under Section A's Información and Transparencia principles, Lemon discharged its disclosure duty: the offer "as presented" was complete and unambiguous. There is no hidden term, no support-chat promise, and no allegation of a Lemon-side fault.

Section B's T&C/Digifin clause 3(e), which places the duty to verify recipient data on the ordering user, is compatible with Section A — it allocates a normal, foreseeable typing-error risk to the party in sole control of the input, and does not function as a catch-all immunity against consumer-protection violations. Once an immediate ARS transfer settles to a CBU at another PSP, reversal requires the recipient's or their bank's cooperation; this is a regulatory feature of the Argentine retail-payments rail, not a discretionary refusal by Lemon. Protección therefore is not engaged against Lemon.

In dubio pro consumidor is a tiebreaker and is not triggered here because the operative facts are admitted by the user and uncontested by Lemon. Buena fe, Educación and No discriminación raise no concerns. The Schelling-point answer for a diligent, policy-literate juror panel is to deny the claim against Lemon while expressing sympathy for the user's loss — the proper avenue is a civil/criminal action or a request through Mercado Pago against the unintended recipient, not a charge-back against Lemon.
