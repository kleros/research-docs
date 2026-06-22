# Case 80 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Recuperación de depósito de token NO listado (GRASS) enviado por red Solana a Lemon
**Amount in dispute:** 31.38 GRASS (~USD 31.85 al momento del depósito)
**Question:** ¿Debe Lemon acreditar / devolver los 31.38 GRASS depositados por el usuario (aplicando, en su caso, la comisión del 10 % por recuperación) o puede ampararse en la cláusula 13.7 de los T&C y la naturaleza no-listada del token para denegar la devolución?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Política Sección A.1 — Protección al Consumidor:** los intereses económicos del usuario deben salvaguardarse.
2. **Política Sección A.2 — Información:** información clara, cierta, detallada y oportuna sobre el producto/servicio.
3. **Política Sección A.3 — Transparencia:** condiciones reales y operativas comunicadas con claridad.
4. **Política Sección A.4 — Buena fe.**
5. **Política Sección A.5 — In dubio pro consumidor (tiebreaker).**
6. **Política Sección A.6 — Educación.**
7. **Política Sección B — Compatibilidad T&C / Sección A:** los T&C ceden ante la Sección A en caso de conflicto.
8. **T&C 13.6 / 13.7 (citadas por Lemon y por las FAQ):** los activos no listados "no podrán verse reflejados en su cuenta"; la empresa no está obligada a operar activos no listados.
9. **FAQ "Lemon Help" (oferta tal-cual-presentada):** "Si podemos recuperarlos y fueron enviados por ERC20, el monto mínimo recuperable es de 40 USD. **Para otras redes, debe ser al menos 1 USD.** En todos los casos, se aplicarán costos de red y una comisión de recuperación del 10 %."

## Burden of proof
El usuario reclama un cambio del default (no acreditación). Le toca probar (i) el depósito y (ii) que se cumplen las condiciones de la oferta de recuperación de la FAQ. Lemon, si invoca una excepción (irrecuperabilidad técnica), debe probarla.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Captura Solscan: transferencia confirmada de 31.38 GRASS (~USD 31.85) por red Solana a wallet de destino | Primaria (on-chain) | No | Alta |
| User | Captura FAQ Lemon: condiciones de recuperación (otras redes ≥ 1 USD, comisión 10 %) | Primaria (publicada por Lemon) | No | Alta |
| User | Captura chat soporte ("Lauty"): le indican "fondos reclamados", lo derivan a artículos y al explorador, no le ofrecen recuperación | Primaria | No | Alta |
| Lemon | Cita T&C 13.7 (activos no listados no se reflejan; empresa no obligada) | Primaria | No | Alta |
| Lemon | Captura FAQ (misma que el usuario): confirma proceso de recuperación 10 % | Primaria | — | Alta (corrobora al usuario) |
| Lemon | Captura lista de activos listados en la app (GRASS ausente) | Primaria | No | Media (no controvertido) |
| Lemon | Afirmación: "nuestro equipo de soporte ya había informado al usuario que GRASS no era recuperable por su condición de no listado" | Aserción de parte | Sí — la captura del chat aportada por el usuario no muestra esa explicación; sólo "fondos reclamados" + derivación a artículos | Baja |
| Lemon | Justificación de no-listado (impedimentos técnico/financiero/regulatorio) | Aserción genérica de política | No probada caso-a-caso para GRASS | Baja |

Immaterial:
- Existencia genérica de la Wiki educativa de Lemon — no resuelve si en este caso concreto se cumplió la oferta de recuperación.

## Application
- **Protección (A.1):** El usuario perdió USD 31.85 reales. Lemon no demuestra haber ofrecido la vía de recuperación que su propia FAQ promete para depósitos en "otras redes" ≥ USD 1. El interés económico no se ha salvaguardado.
- **Información (A.2):** La FAQ pública crea una expectativa concreta: para redes no-ERC20, recuperación posible desde 1 USD con 10 % de comisión. El depósito (USD 31.85, red Solana) cae claramente dentro del supuesto. El usuario actuó informado por esa oferta.
- **Transparencia (A.3):** La oferta tal-como-presentada en la FAQ es la que gobierna. Lemon no exhibe ninguna comunicación al usuario explicando por qué este token en particular no es técnicamente recuperable. Su descargo se limita a afirmar genéricamente que "soporte ya le informó", pero la propia captura aportada por el usuario contradice ese punto: el agente "Lauty" dice "fondos reclamados" y deriva a artículos genéricos, sin explicar la imposibilidad ni ofrecer la ruta del 10 %.
- **Buena fe (A.4):** La FAQ promete una vía de recuperación; cerrar la puerta de plano, sin probar la imposibilidad técnica específica para GRASS-Solana (un token SPL estándar, recibido en una cuenta de token asociada efectivamente creada según Solscan), tensiona el deber de buena fe.
- **In dubio (A.5):** Si quedara duda residual entre "la FAQ promete recuperación de redes no-ERC20 ≥ 1 USD" y "T&C 13.7 dice que no está obligada", el tiebreaker juega a favor del consumidor.
- **Educación (A.6):** Lemon invoca la Wiki, pero educación post-hoc no purga el incumplimiento de la oferta concreta.
- **No discriminación (A.7):** No aplica.
- **Compatibilidad T&C / Sección A (B):** T&C 13.7 es una cláusula catch-all de inmunidad ("no obligada a operar no-listados"); leída en absoluto, anularía la oferta pública de la FAQ. Per la guidance: catch-all immunity ≠ override Sección A. La lectura armónica es: 13.7 libera a Lemon de listar/operar el activo, pero la FAQ — emitida por la propia Lemon, citando 13.6/13.7 — establece la modalidad operativa de recuperación que sí ofrece, y esa oferta tal-cual-presentada gobierna Información y Transparencia.

## Jurisdiction / Morality / Validity
Pasa los tres filtros. Subcourt correcto (Blockchain No Técnica, Lemon). Sin cuestiones morales. Pregunta bien formada y respondible.

## Schelling-Point check
Un panel diligente leerá: (i) FAQ pública de Lemon promete recuperación para otras redes desde 1 USD; (ii) el depósito está claramente dentro del supuesto; (iii) Lemon no prueba imposibilidad técnica específica ni comunicación clara al usuario; (iv) la cláusula 13.7 no puede leerse como inmunidad absoluta cuando la propia empresa publica condiciones de recuperación que la presuponen. Convergencia razonable: Favor User.

## Bias audit
Verificado: la decisión se sostiene aun ignorando la simpatía hacia el usuario minorista. Se basa en la oferta tal-como-presentada por Lemon (FAQ) y en la ausencia de prueba de imposibilidad técnica caso-específica.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification

La FAQ pública de Lemon ("Envié una moneda que no está listada y/o por medio de una red no disponible. ¿Qué hago?"), aportada por ambas partes, establece como oferta tal-cual-presentada que para depósitos por redes distintas de ERC20 el monto mínimo recuperable es **1 USD**, con costos de red más comisión de recuperación del **10 %**, citando expresamente los arts. 13.6 y 13.7 de los T&C. El depósito del usuario — 31.38 GRASS (~USD 31.85) por red Solana, acreditado en blockchain mediante captura de Solscan no rebatida — cae inequívocamente dentro de ese supuesto.

Bajo los Principios de **Información** y **Transparencia** (Sección A.2 y A.3 de la Política), la oferta tal-como-presentada gobierna lo que el consumidor puede legítimamente esperar. Lemon, en su descargo, se limita a invocar la cláusula 13.7 ("la empresa no se encuentra obligada a permitir la operación de Activos Digitales que no estén listados") y a afirmar que soporte ya informó al usuario la irrecuperabilidad. Sin embargo: (i) la propia captura del chat con el agente "Lauty" aportada por el usuario no contiene tal explicación — sólo deriva a artículos genéricos y al explorador; (ii) Lemon no aporta evidencia técnica específica de por qué GRASS-Solana (token SPL estándar, depositado en una cuenta de token asociada efectivamente creada on-chain) sería irrecuperable, mientras su FAQ promete recuperación para "otras redes" sin distinguir. La cláusula 13.7 funciona aquí como inmunidad catch-all que, conforme la Sección B de la Política, no puede prevalecer sobre los principios de Sección A.

Bajo **Protección al Consumidor** (A.1) y **Buena Fe** (A.4), y en último término el tiebreaker **in dubio pro consumidor** (A.5), corresponde resolver a favor del usuario: Lemon debe procesar la recuperación del depósito conforme su propia oferta publicada (devolución neta de costos de red y comisión del 10 %), o bien acreditar caso-específicamente la imposibilidad técnica que justifique apartarse de esa oferta.
