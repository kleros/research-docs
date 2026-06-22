# Case 100 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Envío de Soles vía Yape (cash-out PEN) desde Lemon — duplicación de transferencia tras error y reintento
**Amount in dispute:** S/ 100 (uno de dos débitos de S/ 100 por la misma operación)
**Question:** ¿Debe Lemon responder al usuario por el segundo débito de S/ 100 producido al "reintentar" un envío que la app reportó como fallido y que, según el destinatario, nunca fue recibido?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política Consumidor Sección A.1 — **Protección**: resguardar los intereses económicos del usuario frente a fallos operativos no imputables a su conducta.
2. Política Consumidor Sección A.2 — **Información**: la información provista por la plataforma debe ser veraz, oportuna y suficiente. El "offer as presented" rige (estado de la operación en pantalla = lo que se promete al usuario).
3. Política Consumidor Sección A.3 — **Transparencia**: las pantallas/estados (pendiente/completo) deben reflejar fielmente el resultado real de la operación.
4. Política Consumidor Sección A.4 — **Buena fe**: ambas partes deben actuar con diligencia; el usuario que reintenta tras un error UI obra de buena fe.
5. Política Consumidor Sección A.5 — **In dubio pro consumidor** (TIEBREAKER): en caso de duda razonable, se resuelve a favor del usuario.
6. Sección B — Cualquier cláusula de T&C ("instrucción irrevocable / fondos fuera del ecosistema") no puede usarse para anular la Sección A; las inmunidades amplias no derogan los principios.

## Burden of proof
El usuario alega un defecto de UI que provocó el doble débito. Como el reclamo busca un cambio respecto del default (Lemon ya procesó y no devolverá), el usuario carga con la prueba inicial. Una vez aportada evidencia documental coherente (timestamps, capturas, confirmación del destinatario), la carga se traslada a Lemon para rebatir punto por punto.

## Material evidence

| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Dos envíos a S/100 al mismo CCI 00257017344105904101, mismo destinatario (Dario Joel Ruiz Leyva), mismo teléfono *3289, **mismo mensaje** ("aquí comienza el camino.yo elijo creer!"), separados por ~48 s (Trx 8e69ba84… a 01:17:06 y Trx 120a3389… a 01:17:54) | Primary (capturas app + corroboradas por back-office Lemon) | No | High |
| Usuario | Captura de pantalla "Actividad" a la 1:37 AM mostrando una de las dos transacciones aún como **"Pendiente"** horas después de instruida | Primary (screenshot) | No | High |
| Usuario | Captura posterior (10:27 AM) mostrando ambas como "Completo" — el estado mutó de pendiente a completado horas más tarde | Primary | No | Medium-High |
| Usuario | Declaración: destinatario confirma haber recibido sólo UNA de las dos transferencias | Secondary (testimonio referido) | No directamente | Medium |
| Lemon | Back-office: ambas Trx en estado "Completada" desde el lado Lemon, con External IDs distintos | Primary | Parcial (no prueba acreditación en Yape) | Medium |
| Lemon | Argumento jurídico: "instrucción irrevocable / fondos fuera del ecosistema" | Secondary (alegato) | — | Low (no aborda el defecto UI) |

Immaterial:
- Tachados verdes en la captura de movimientos: irrelevantes para el doble débito.
- Movimientos previos al 13 de abril (depósitos/envíos del 9–12 abril): no atinentes.

## Application
- **Protección:** El usuario sufrió un débito duplicado por una operación que en su intención era única (mismo destinatario, mismo CCI, mismo mensaje, 48 segundos entre intentos). El principio exige a Lemon resguardar sus intereses económicos cuando el fallo no es imputable al usuario. **Favor User.**
- **Información:** La app mostró un error en el primer intento, induciendo al usuario a reintentar. La misma app mostró luego una operación como "Pendiente" y horas después como "Completo". La información no fue veraz, oportuna ni consistente. **Favor User.**
- **Transparencia:** Los estados en pantalla ("Completo / Tu envío ya fue realizado") contradicen lo que el destinatario reporta haber recibido. La trazabilidad ofrecida al usuario es opaca respecto del resultado real en Yape. **Favor User.**
- **Buena fe:** El usuario actuó diligentemente (reintentó sólo tras ver un error) y aportó pruebas detalladas. Lemon contestó genéricamente sin abordar (a) si en el primer intento la UI efectivamente mostró un error, (b) por qué una transacción figuró "Pendiente" horas después, (c) qué evidencia tiene de acreditación en Yape de ambos envíos. **Favor User.**
- **In dubio:** Aun si quedara duda residual sobre la causa exacta del doble débito, el tiebreaker resuelve a favor del consumidor.
- **Educación:** No relevante de modo decisivo.
- **No discriminación:** No relevante.
- **Compatibilidad con T&C (Sección B):** Lemon invoca la irrevocabilidad de la instrucción y la salida de fondos del ecosistema. Esa cláusula no puede operar como inmunidad catch-all frente a un defecto propio de la plataforma (UI engañosa que indujo el reintento). Sección B subordina los T&C a los principios de Sección A. **Favor User.**

## Jurisdiction / Morality / Validity
Subcourt "Blockchain No Técnica" (Lemon) — correcto. Cuestión bien formulada y resoluble. Sin elementos morales agravantes. Pasa los tres filtros.

## Schelling-Point check
Un panel de jurados diligentes, leyendo (i) dos transacciones con metadatos idénticos a 48 s de distancia, (ii) un screenshot que muestra una transacción aún "Pendiente" horas después y luego virada a "Completo", (iii) la afirmación no rebatida de que el destinatario recibió sólo un pago, y (iv) una respuesta de Lemon que no aborda específicamente el error UI ni provee evidencia de acreditación en Yape — converge en Favor User. La lectura literal de Información + Transparencia + Buena fe es directa.

## Bias audit
La conclusión no depende de identidad ni de retórica. Se basa en: identidad de metadatos entre ambas Trx, brecha temporal de 48 s, mutación del estado "Pendiente → Completo", y silencio de Lemon sobre los puntos críticos. La sympathy hacia el usuario individual no fue el factor decisivo; el factor decisivo es la falla probatoria de Lemon en rebatir el patrón de defecto de UI.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification (English)

The user's evidence shows two PEN 100 cash-outs to the same recipient, same CCI, same phone, and—critically—the **same free-text message** ("aquí comienza el camino.yo elijo creer!"), issued 48 seconds apart. That signature is consistent with a single intended transfer that was retried after the app reported an error, not with two distinct payments. A subsequent screenshot shows one of the operations still flagged "Pendiente" hours after instruction, only later flipping to "Completo". The user also states the recipient received only one of the two transfers — a claim Lemon does not rebut.

Lemon's defence is limited to (a) back-office screenshots confirming both transactions left its platform as "Completada", and (b) the legal argument that an authorised instruction is irrevocable once funds exit the Lemon ecosystem. Neither point engages the user's specific allegations: it does not address whether the first attempt displayed an error message that induced the retry, does not explain why one transaction was visible as "Pendiente" hours later, and offers no Yape-side acknowledgement that both 100 PEN credits actually reached the destination account. Under Sección B, that irrevocability clause cannot operate as a catch-all immunity that overrides the Sección A principles.

Applying the Política: **Información** and **Transparencia** are violated when the UI signals an error on a transaction that is in fact being processed, and when on-screen status ("Completo / Tu envío ya fue realizado") does not match reality at the destination. **Protección** and **Buena fe** require Lemon to absorb the loss caused by its own UI defect when the user acted diligently. To the extent any residual doubt remains, **In dubio pro consumidor** resolves it in the user's favour. The vote is **Favor User**.
