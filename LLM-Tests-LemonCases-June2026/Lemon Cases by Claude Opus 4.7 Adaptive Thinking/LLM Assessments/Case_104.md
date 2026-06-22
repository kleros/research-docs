# Case 104 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (VISA Física *4811) — débitos disputados por la usuaria
**Amount in dispute:** $2.981,81 ARS (18/03/2025) + 22,44 DAI ≈ $28.359,78 ARS (21/03/2025) en el comercio v*cs-kabudget.com
**Question:** ¿Debe Lemon reembolsar a la usuaria los dos consumos con tarjeta hechos en v*cs-kabudget.com, alegados como uso no autorizado?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. Política Sección A.1 — Protección al Consumidor.
2. A.2 — Información y A.3 — Transparencia (la oferta tal cual fue presentada gobierna).
3. A.4 — Buena fe.
4. A.5 — In dubio pro consumidor (sólo desempate).
5. A.6 — Educación financiera; A.7 — No discriminación.
6. Sección B — T&Cs subordinados a la Sección A.
7. Carga de prueba: la parte que pide modificar el estado por defecto debe probarlo; la evidencia no refutada se presume genuina.

## Burden of proof
La usuaria afirma "uso no autorizado" y solicita reembolso → debe acreditarlo con un mínimo de indicios (acceso indebido, suplantación, falla de seguridad). Lemon, como proveedor del servicio financiero, debe demostrar trazabilidad y autenticación de la operación.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuaria | Capturas de los dos consumos en app, comercio v*cs-kabudget.com | Secundaria (consistente con registro Lemon) | No | Media |
| Usuaria | Alegato de phishing previo en otra entidad | Secundaria, contextual | Sí (Lemon: no vinculante) | Baja |
| Usuaria | Alegato de no haber recibido notificación del primer consumo | Afirmación de parte | Implícitamente rebatida por capturas del propio movimiento | Baja |
| Lemon | Back-office: dos depósitos VIRTUAL_DEPOSIT de $2.000 a las 13:05:14 y 13:05:51, justo antes del débito de $2.981,81 a las 13:07:03 | Primaria (registro interno) | No | Alta |
| Lemon | Retiro VIRTUAL_WITHDRAWAL de $1.018,19 a las 13:12:56 (saldo remanente) por la propia usuaria minutos después del débito | Primaria | No | Alta |
| Lemon | Detalle de transacción: tarjeta física *4811, comercio v*cs-kabudget.com, entorno autenticado, sin acceso no autorizado detectado | Primaria | No | Alta |
| Lemon | Segundo consumo (21/03/2025) descripto como renovación del mismo servicio/comercio | Primaria + caracterización | No (la usuaria no contradice que se trate del mismo comercio recurrente) | Alta |

Immaterial:
- Solicitud de compensación por "earn"/rendimiento perdido — accesoria, condicionada al reembolso principal.
- Antecedente de phishing en otra plataforma — no vinculado por evidencia al hecho concreto.

## Application
- **Protección (A.1):** El régimen protege ante fraude real. Aquí los registros muestran depósitos manuales que calzan al céntimo con el débito impugnado y un retiro inmediato del remanente: patrón incompatible con suplantación; un atacante no fondea la cuenta de la víctima ni le deja el vuelto.
- **Información / Transparencia (A.2–A.3):** La operación quedó registrada y notificada en la app de la usuaria (las propias capturas que aporta provienen de su feed de movimientos). No hay "oferta oculta" relevante: es un cargo de tarjeta a un comercio, con todos los datos visibles.
- **Buena fe (A.4):** La conducta de fondear la cuenta dos minutos antes del cargo y retirar el saldo sobrante seis minutos después indica conciencia y planificación del débito. La alegación de desconocimiento es difícilmente compatible con esa secuencia.
- **In dubio (A.5):** No se activa: la evidencia primaria de Lemon (timestamps consecutivos, autenticación, mismo dispositivo/credenciales) no está empatada con la prueba de la usuaria, que se limita a afirmaciones y a capturas que confirman —no contradicen— los registros de Lemon.
- **Educación / No discriminación (A.6–A.7):** No invocados materialmente.
- **Compatibilidad T&C (Sección B):** Lemon no se ampara en cláusulas catch-all sino en evidencia operativa; no hay conflicto Sección A vs. B.

## Jurisdiction / Morality / Validity
Pasa los tres filtros: subcourt correcto (Blockchain No Técnica, consumo fintech), sin actos inmorales del catálogo de la General Court, pregunta bien formulada y respondible.

## Schelling-Point check
Un panel diligente leerá el back-office: dos depósitos del usuario justo antes del débito y retiro inmediato del remanente sobrante. Es el patrón típico de operación consentida, no de fraude. Convergencia clara hacia Lemon.

## Bias audit
La usuaria es la parte más vulnerable y su relato es coherente, pero la decisión no debe apoyarse en simpatía: los timestamps son neutros y determinantes. La invocación genérica de phishing no sustituye prueba del hecho. Se descartan anclajes en identidad.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
Applying Política Sección A, the consumer-protection principle protects against actual unauthorised use, not against buyer's remorse. Lemon's back-office records — unrebutted and primary — show two consecutive VIRTUAL_DEPOSITs of $2,000 each at 13:05:14 and 13:05:51, the disputed LEMON_CARD_PAYMENT of $2,981.81 at 13:07:03, and a VIRTUAL_WITHDRAWAL of the $1,018.19 remainder at 13:12:56, all from an authenticated session on the user's own card *4811. That sequence is structurally inconsistent with third-party fraud: an attacker does not top up the victim's account to the exact amount needed and then leave the remaining balance for the victim to withdraw.

Under A.2 Información and A.3 Transparencia, the operation was visible in the user's own activity feed (the very screenshots she submits), so no "hidden limit" or undisclosed term is engaged. The second debit on 21/03/2025 is identified as a recurring charge from the same merchant; the user provides no evidence rebutting the renewal characterisation. The phishing-precedent argument is unsupported by any link to this specific transaction and cannot substitute for proof of unauthorised access. A.4 Buena fe in fact cuts the other way: the funding pattern indicates conscious anticipation of the debit.

A.5 In dubio is a tiebreaker and is not triggered, because the evidence is not balanced — Lemon's primary, timestamped operational record outweighs the user's unsupported assertions. No Sección A principle is violated by Lemon's conduct, and no Sección B clause is invoked to override Sección A. The correct vote is **Favor Lemon**.

---

Case 104 | VOTE: Favor Lemon | CONFIDENCE: high | Funded account precisely seconds before debit and withdrew remainder minutes after; authenticated session; recurring merchant; phishing claim unsupported.
