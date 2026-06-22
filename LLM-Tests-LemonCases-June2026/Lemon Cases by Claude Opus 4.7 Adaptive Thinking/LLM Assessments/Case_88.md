# Case 88 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Transferencias ARS — (a) retiro saliente de $35.000 y (b) supuesto ingreso de $16.000 desde una plataforma externa (Naranja X)
**Amount in dispute:** ARS 51.000 total ($35.000 + $16.000)
**Question:** ¿Debe Lemon acreditar / reembolsar al usuario los $35.000 supuestamente no recibidos por el destinatario y los $16.000 supuestamente no acreditados en su cuenta Lemon?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política Sección A — Protección al consumidor:** Lemon debe resguardar los fondos del usuario y garantizar la correcta ejecución de las operaciones que ofrece.
2. **Información / Transparencia:** la oferta tal como se presenta gobierna; el usuario tiene derecho a información clara sobre el estado de sus operaciones.
3. **Buena fe:** ambas partes deben actuar de buena fe; no se puede trasladar al usuario la consecuencia de una falla operativa de Lemon.
4. **In dubio pro consumidor (TIE-BREAKER):** sólo aplica si la prueba queda en empate genuino.
5. **No discriminación / Educación:** no relevantes aquí.
6. **Sección B — Compatibilidad con T&Cs:** las transferencias ejecutadas correctamente son irreversibles por diseño del sistema de pagos argentino (red COELSA); Lemon no controla la acreditación final en la entidad destino ni los envíos originados en plataformas externas a la cuenta destino.

## Burden of proof
El usuario, como reclamante que busca apartarse del estado por defecto (operación marcada "Completa" por Lemon y ausencia de registro de un ingreso externo), tiene la carga inicial de probar que (a) la transferencia saliente nunca llegó al CBU destino y (b) el envío externo de $16.000 sí ingresó al sistema de Lemon. La prueba inrebatida se presume genuina.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura de "Actividad" mostrando Retiro de $35.000 el 11-mar-2025 marcado como **Completo**, con CBU destino `0110478730047839338583` (banco Santander), destinatario "Bustos Romina Eugenia", COELSA ID `XJ8G7V95E67QKD7L2EMPYR` | Secondary (screenshot — pero coincide con registros de Lemon) | No (corroborado por Lemon) | Media — prueba que la operación se ejecutó, no que no llegó |
| Usuario | Comprobante Naranja X mostrando envío de $16.000 el 16-mar-2025 de "Felix Gaston Barroso" a "**Daniel Alberto Segura**" al CBU/CVU `0000016830000017014207` | Secondary (screenshot externo) | Parcialmente (Lemon dice no hay registro) | Baja — el CBU/CVU destino **no es un CVU de Lemon** (Lemon opera bajo prefijo BIND 00002090 / 0000058); no consta que "Segura" sea el usuario reclamante |
| Lemon | Captura de back-office interno: VIRTUAL_WITHDRAWAL CREATED, COELSA ID `XJ6GVW6E7QKDYL2ENPYR` (mismo identificador OCR-variante), operación ejecutada correctamente | Primary (registro técnico interno) | No | Alta |
| Lemon | Afirmación de que no existe registro de ingreso de $16.000 en la cuenta del usuario | Negative-fact assertion + ausencia de CVU de Lemon en el comprobante | No rebatido | Alta |

Immaterial:
- "Tuve que cubrir el monto en efectivo" — afirmación sin prueba; no acredita falla de Lemon.
- Saldo final de $326,40 — irrelevante para la cuestión.

## Application
- **Protección:** Lemon ejecutó la operación de $35.000 conforme a las instrucciones del usuario; los fondos salieron al CBU indicado por el propio usuario. La protección no exige que Lemon garantice acreditación en una entidad bancaria de tercera parte (Santander, en este caso). El usuario no aporta prueba (rechazo de COELSA, certificado del banco destino, conversación con la destinataria) de que el dinero no haya llegado.
- **Información / Transparencia:** la oferta (envío vía CBU) se presenta como irreversible una vez ejecutada; Lemon facilitó al usuario el COELSA ID para reclamar al banco destino — eso satisface el deber de información.
- **Buena fe:** el usuario actúa de buena fe, pero el comprobante de los $16.000 muestra un CVU destino que **no pertenece a Lemon** y un beneficiario nominado "Daniel Alberto Segura" — sin evidencia de que ese sea el usuario. Pretender que Lemon acredite un envío que nunca ingresó a su sistema (ni siquiera estaba dirigido a un CVU de Lemon) excede su esfera de control.
- **In dubio:** no hay empate probatorio — Lemon presenta registro técnico primario inrebatido para los $35.000, y para los $16.000 el propio comprobante del usuario muestra que el envío fue a un CVU/CBU ajeno a Lemon. No se activa el tiebreaker.
- **Educación / No discriminación:** N/A.
- **T&C vs Sección A:** la irreversibilidad de transferencias COELSA y la falta de responsabilidad por errores de entidades externas es compatible con Sección A — no es una cláusula de inmunidad genérica, es la realidad operativa del sistema de pagos.

## Jurisdiction / Morality / Validity
Pasa — subcourt correcto (Blockchain No Técnica, Lemon), cuestión bien formada, sin indicios de inmoralidad.

## Schelling-Point check
Un panel diligente leerá: (i) operación de $35.000 ejecutada y confirmada por registro primario de Lemon = no hay falla atribuible a Lemon, el usuario debe reclamar al banco destino con el COELSA ID; (ii) los $16.000 fueron enviados a un CVU que no es de Lemon, por lo tanto Lemon no puede acreditar fondos que nunca recibió. Lectura literal de la política favorece a Lemon en ambos puntos.

## Bias audit
El monto reclamado es real y el usuario relata una situación de emergencia, lo que invita simpatía. Apartando eso, la prueba documental aportada por el propio usuario contradice sus afirmaciones (el comprobante de Naranja X muestra un CVU destino que no es de Lemon, lo que confirma la versión de Lemon de que no hay registro). No hay sesgo identitario operando en la decisión.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user claims two failed credits. For the ARS 35,000 outbound transfer, Lemon's primary back-office record (COELSA ID matching the user's own receipt) shows the operation was executed successfully and the funds left Lemon's perimeter via the Argentine inter-bank rail to the CBU the user himself instructed. Once executed, COELSA transfers are irreversible and Lemon's duty under Sección A (Protección, Información, Buena fe) extends only to correct execution of the offer as presented — not to guaranteeing crediting at a third-party bank. Lemon supplied the COELSA ID precisely so the user can pursue the destination bank, satisfying the Información / Transparencia duty.

For the ARS 16,000 inbound from Naranja X, the user's own evidence is dispositive against him: the destination CBU/CVU `0000016830000017014207` and beneficiary name "Daniel Alberto Segura" on the Naranja X receipt do not correspond to a Lemon CVU, and there is no evidence linking that beneficiary to the user. Lemon's unrebutted statement that no such credit exists in its system is consistent with the user's own document. Lemon cannot be required to credit funds that were never sent into its system.

No genuine evidentiary doubt exists, so the in dubio pro consumidor tiebreaker does not engage. The T&C provisions on irreversibility and on disclaiming responsibility for external-platform operations are compatible with Sección A — they describe the technical reality of the COELSA system, not a catch-all immunity. Vote: Favor Lemon.

---

Case 88 | VOTE: Favor Lemon | CONFIDENCE: high | Lemon's primary record shows $35K executed correctly; the $16K user receipt names a non-Lemon CVU and beneficiary, so no Lemon failure exists.
