# Case 102 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Retiro de ARS (transferencia saliente) vía Lemon / Digifin — destino externo (Banco Galicia)
**Amount in dispute:** ARS 5.000,00 (transferencia del 30/04/2025, 11:03 hs)
**Question:** ¿Debe Lemon reembolsar / responder por una transferencia saliente de ARS 5.000 ordenada por el usuario, correctamente ejecutada hacia un CBU de un tercero (Banco Galicia) y con COELSA ID asignado, pero que el usuario dice que "nunca llegó al destinatario"?

## Options
- **Favor User** — Lemon debe reembolsar / compensar.
- **Favor Lemon** — Lemon cumplió y no debe restituir fondos.
- **Refuse to Arbitrate** — caso fuera de jurisdicción / inmoral / inválido.

## Governing rules
1. **Política Sección A — Protección al consumidor.** Los fondos del usuario deben resguardarse; retención injustificada viola este principio.
2. **Información** — Lemon debe informar con precisión sobre el estado de la operación.
3. **Transparencia** — la oferta y los hechos relevantes deben presentarse claramente.
4. **Buena fe** — ambas partes deben actuar de buena fe; el usuario debe usar los canales habilitados, Lemon ejecutar instrucciones según lo prometido.
5. **In dubio pro consumidor** — sólo como criterio de desempate cuando, agotado el análisis, persiste duda razonable.
6. **Educación financiera / 7. No discriminación** — no aplicables aquí.
7. **Sección B — Compatibilidad T&Cs.** La cláusula 3.7 de los T&Cs (mandato irrevocable para ejecutar retiros) sólo prevalece si no contradice la Sección A. Una vez ejecutada conforme a las instrucciones del usuario y enviada al sistema interbancario (con COELSA ID), la operación está fuera del control de Lemon.

## Burden of proof
La carga inicial recae en el usuario, que pretende modificar el estado por defecto (fondos ya enviados al CBU indicado). Debe acreditar que (a) los datos del destinatario fueron mal procesados por Lemon, (b) los fondos siguen en poder de Lemon, o (c) hubo falla imputable a Lemon. Sólo entonces se desplaza la carga a Lemon.

## Material evidence

| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura de "Actividad" mostrando retiros ARS y conversación con Lemmy (222 en fila) | Secundaria (screenshot) | No | Media — confirma que la operación se generó y que hubo demora en atención humana |
| Usuario | Comprobante Lemon/Digifin: ARS 5.000 a Sergio Gabriel Mantegazza, CUIT 20231195018, CBU 0070002330004202488887, Banco Galicia, COELSA ID D4RO172VEVKJ7MQ0NKJ3QE, Trx dc77ecd0… | Primaria (comprobante propio) | No | Alta — prueba que la transferencia se ejecutó con datos del destinatario provistos por el usuario |
| Lemon | Back-office: VIRTUAL_WITHDRAWAL, estado "Completada", mismo Trx ID, mismo COELSA ID, misma cuenta de destino | Primaria (registro interno) | No | Alta — confirma ejecución completada del lado de Lemon |
| Lemon | Cláusula 3.7 T&Cs — mandato irrevocable al confirmar el retiro | Documental | No | Alta |

**Immaterial:**
- Capturas de otros retiros y rendimientos del mismo día — no relacionados con la operación en disputa.
- Queja sobre "222 personas en la fila" — relevante a calidad de servicio pero no decisiva para revertir una transferencia ya liquidada vía COELSA.

## Application
- **Protección:** Los fondos no están "retenidos" por Lemon; el registro y el comprobante coinciden en que salieron del ecosistema Lemon al CBU del destinatario provisto por el propio usuario. No se acredita retención.
- **Información:** Lemon entregó comprobante completo con COELSA ID y Trx ID; sugiere al usuario contactar a la entidad receptora con el COELSA. La información existe y es trazable.
- **Transparencia:** El comprobante presentado por el propio usuario expone destinatario, CUIT, CBU, banco y COELSA ID — operación transparente. La oferta "as presented" (retiro a CBU externo) coincide con lo ejecutado.
- **Buena fe:** El usuario confirmó la operación y proporcionó los datos del destinatario; Lemon ejecutó conforme. No hay evidencia de mala fe de ninguna parte. La demora del soporte humano (222 en fila) es un punto débil de Lemon pero no convierte una transferencia ejecutada en una obligación de reembolso.
- **In dubio:** No se llega a empate — los hechos materiales son concordantes entre ambas partes (misma Trx ID, mismo COELSA, monto y destinatario coincidentes). No procede el desempate pro consumidor.
- **Educación / No discriminación:** no aplican.
- **T&C compatibility:** La cláusula 3.7 (mandato irrevocable post-confirmación) es compatible con la Sección A porque sólo opera tras instrucción y confirmación del usuario, y porque el COELSA ID acredita que los fondos abandonaron el sistema Lemon. No es una "immunity catch-all" — encaja con la realidad técnica del clearing interbancario argentino.

## Jurisdiction / Morality / Validity
Pasa los tres filtros. Sub-corte correcta (Blockchain No Técnica / consumidor fintech), sin conducta inmoral, pregunta bien formada y respondible con los materiales.

## Schelling-Point check
Un panel diligente convergería en Favor Lemon: la propia prueba primaria del usuario (su comprobante) demuestra que Lemon ejecutó la orden hacia el CBU y COELSA correctos. El reclamo es contra la entidad receptora o el destinatario, no contra Lemon.

## Bias audit
La narrativa emocional del usuario ("222 personas en la fila", "inadmisible") no debe inclinar el voto. La calidad del soporte es criticable pero no es la cuestión patrimonial planteada. Sin sesgo por identidad o retórica.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (English)

The user's own primary evidence — a Lemon/Digifin transfer receipt — shows that ARS 5,000 was sent on 30/04/2025 at 11:03 to a third-party CBU at Banco Galicia (Sergio Gabriel Mantegazza, CUIT 20231195018, CBU 0070002330004202488887), with a valid COELSA ID (D4RO172VEVKJ7MQ0NKJ3QE) and transaction ID dc77ecd0-28c8-4dee-970d-e2de7b55cd98. Lemon's back-office record matches exactly: same Trx ID, same COELSA ID, same destination account, status "Completada". The funds left Lemon's ecosystem into the interbank clearing system based on data the user himself provided and confirmed.

Under Sección A, Protección requires safeguarding user funds against unjustified retention — but no retention by Lemon is shown; the funds were dispatched. Información and Transparencia are satisfied by the issued receipt with COELSA ID and Lemon's explicit suggestion that the user contact the receiving institution with that identifier. Buena fe runs both ways: the user provided the destination data and confirmed; Lemon executed faithfully. The slow support queue is a service-quality concern but does not reverse a completed interbank transfer or shift liability for credit on the receiving side.

Sección B is compatible with Sección A here: clause 3.7 (irrevocable mandate upon user confirmation) reflects the technical reality that once an ARS withdrawal crosses into the COELSA network it can no longer be unilaterally recalled by the originator. There is no genuine factual doubt — both parties' primary evidence agrees — so the in-dubio tiebreaker does not apply. Vote: Favor Lemon.

---

Case 102 | VOTE: Favor Lemon | CONFIDENCE: high | User's own receipt shows ARS 5,000 sent to third-party CBU with valid COELSA ID; Lemon executed the user-confirmed instruction correctly.
