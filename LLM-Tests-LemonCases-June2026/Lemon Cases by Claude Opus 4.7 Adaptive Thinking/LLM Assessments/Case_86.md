# Case 86 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Tecnica"
**Promo / product at issue:** Retiro (withdrawal) de 20.33 WLD desde Lemon a billetera externa (Trust Wallet), enviado por la red Worldchain.
**Amount in dispute:** 20.33 WLD (neto), aprox. USD 24.80 (segun explorer)
**Question:** Es Lemon responsable de los fondos perdidos porque (segun el usuario) la app "no permitio seleccionar explicitamente la red" Ethereum y los WLD se enviaron por Worldchain a una direccion Trust Wallet que no recibe Worldchain?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Politica de Defensa al Consumidor de Lemon — Seccion A** (orden no jerarquico, salvo "in dubio" como tiebreaker):
   1. Proteccion del consumidor
   2. Informacion adecuada y veraz
   3. Transparencia
   4. Buena fe
   5. In dubio pro consumidor (TIEBREAKER unicamente)
   6. Educacion del consumidor
   7. No discriminacion
2. **Seccion B**: ante conflicto entre Terminos y Condiciones y Seccion A, prevalece Seccion A.
3. **T&C clausula 13.7 (citada por Lemon)**: si el usuario envia Activos Digitales por una red no listada, los mismos no podran reflejarse; la empresa solo presta servicio por Activos Digitales Listados. (Esta clausula puede invocarse en tanto sea compatible con Seccion A.)
4. **GUIDANCE**: "Offer as presented" rige Informacion/Transparencia. Limites ocultos = probable violacion; limites claros + falla del usuario = el reclamo cae. In dubio es solo tiebreaker.

## Burden of proof
El usuario es el reclamante y busca apartarse del estado por defecto (transaccion on-chain irrevocable, confirmada por el propio usuario). Le corresponde demostrar que Lemon oculto, tergiverso o no comunico la red en el flujo de envio.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura del explorer mostrando tx 0x9e1e...79c "Exito", token WLD, hace 8 hs del 09-feb-2025 | Primary (on-chain) | No | High — confirma que la transferencia se ejecuto y se confirmo on-chain en Worldchain (token contract `0x2cFc85...3003` es WLD en Worldchain) |
| Usuario | Captura Lemon "Retiro de WLD 20,63 WLD … Red: **Worldchain** … Hash 0x9e1e…" | Primary (app UI) | No | High — la propia captura del usuario muestra que Lemon mostro "Red: Worldchain" en el detalle del retiro |
| Usuario | Captura Trust Wallet con WLD listado en "Ethereum" y "OP Mainnet" (no Worldchain) | Primary | No | Medium — explica por que no impactaron los fondos: el destino no tiene cuenta Worldchain configurada |
| Usuario | Afirmacion: "la aplicacion de Lemon no me permitio seleccionar explicitamente la red" | Secondary (claim) | Rebutted por capturas de Lemon | Low — la pretension de "ocultamiento" es contradicha por las capturas del propio flujo |
| Lemon | Capturas del flujo "Enviar WLD": campo "Direccion de destino 0x77f…4SC1 **Worldchain**", texto guia "Puedes enviar a direcciones de billeteras que pertenezcan a la red, **Worldchain**", costo de red en WLD | Primary (app UI) | No | High — demuestra que la red unica admitida (Worldchain) se exhibe explicitamente al menos dos veces en el flujo previo a la confirmacion |
| Lemon | T&C clausula 13.7 aceptada al alta | Primary (contrato) | No | Medium — apoya la postura de irreversibilidad y de no obligacion de operar redes no listadas |

Immaterial:
- Pedido del usuario de "revision del sistema de envios" — politica de producto, no objeto arbitrable.
- Comparacion con otras exchanges (Lemon la descarta) — irrelevante para evaluar Lemon contra su propia politica.

## Application
- **Proteccion:** La proteccion del consumidor presupone que el operador disponga de medios para evitar el dano. La transaccion es on-chain e irreversible una vez firmada; Lemon no tiene capacidad tecnica para revertirla. No hay un mecanismo razonable que Lemon haya omitido.
- **Informacion:** Lemon expone la red admitida ("Worldchain") en (i) el sub-encabezado del flujo de envio, (ii) junto a la direccion de destino, y (iii) en el detalle final del retiro (visible en la propia evidencia del usuario). La informacion AS PRESENTED es clara.
- **Transparencia:** La unica red habilitada se anuncia tanto en deposito como en envio. No hay limite oculto: la limitacion (solo Worldchain para WLD) esta a la vista en el flujo de la operacion.
- **Buena fe:** Lemon advierte de la red antes de confirmar y reitera en la pantalla de detalle. No hay indicios de mala fe ni de induccion a error.
- **In dubio (tiebreaker):** No se activa: la evidencia es congruente y la propia captura del usuario muestra "Red: Worldchain". No hay duda razonable que romper a favor del consumidor.
- **Educacion:** La etiqueta "Worldchain" junto a la direccion y el texto guia "Puedes enviar a direcciones de billeteras que pertenezcan a la red, Worldchain" cumplen con el deber informativo / educativo basico en el punto de decision.
- **No discriminacion:** No esta en juego.
- **Compatibilidad T&C vs Seccion A:** La clausula 13.7 (no responsabilidad por envios a redes no listadas) opera aqui en linea con Seccion A, porque la red admitida fue informada de manera visible. Lemon no invoca una clausula "catch-all" para neutralizar el deber de informar; al contrario, demuestra que informo. No hay conflicto que active la prevalencia de Seccion A sobre el T&C.

## Jurisdiction / Morality / Validity
Jurisdiccion correcta (Blockchain No Tecnica; producto cripto, exchange argentino). Sin indicios de inmoralidad (fraude, perjurio, etc.). Pregunta valida y respondible con la evidencia presentada.

## Schelling-Point check
Un panel diligente que lea ambos descargos vera que la propia evidencia del usuario incluye una pantalla de Lemon que indica "Red: Worldchain" y que Lemon documenta el doble aviso de red previo a la confirmacion. La lectura literal y obvia de la politica concluye que Informacion y Transparencia fueron satisfechas. Convergencia esperada: Favor Lemon.

## Bias audit
Verifico que no estoy castigando al usuario por error tecnico ni premiando a Lemon por ser la empresa. El analisis se sostiene incluso si invierto el orden de lectura: la captura propia del usuario muestra "Worldchain" en el detalle del retiro — es evidencia primaria autoincriminatoria del propio reclamante respecto de que la red fue exhibida. Sin sesgo de anclaje al descargo de Lemon: el resultado se sostiene solo con las pruebas del usuario.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
Under Section A of Lemon's consumer-protection policy, the principles of Informacion, Transparencia and Buena fe require Lemon to disclose, as presented in the offer, the network used to send a listed asset. The evidence shows Lemon did exactly that: the "Enviar WLD" flow displays the Worldchain label next to the destination-address field and includes the helper text "Puedes enviar a direcciones de billeteras que pertenezcan a la red, Worldchain" before the user can confirm. The user's own withdrawal-detail screenshot from the Lemon app shows "Red: Worldchain" alongside the transaction hash — primary evidence from the claimant himself that the network was disclosed in the UI. The claim that Lemon "did not allow the network to be explicitly selected" is therefore not a hidden limit; Lemon supports only Worldchain for WLD and discloses that openly at the point of decision.

The on-chain transaction (hash 0x9e1eafc2...479c, WLD token contract 0x2cFc85...3003 on Worldchain) confirms that the transfer settled successfully on Worldchain. The reason the funds do not appear in Trust Wallet is that the user's Trust Wallet only has WLD configured on Ethereum and OP Mainnet (per the user's own screenshot), not on Worldchain — a destination-side configuration issue, not a Lemon disclosure failure. Once a blockchain transaction is confirmed it is irreversible; the Proteccion principle does not impose on Lemon a duty it is technically incapable of performing.

The In dubio pro consumidor tiebreaker is not engaged because there is no genuine doubt: the user's own evidence shows the network was displayed. T&C clause 13.7 (no obligation to support unlisted networks) is invoked here consistently with — not in derogation of — Section A, because the relevant disclosure was made. Under the literal, Schelling-point reading of the policy applied to the unrebutted evidence, the correct vote is Favor Lemon.

---

Case 86 | VOTE: Favor Lemon | CONFIDENCE: high | Lemon disclosed "Worldchain" in send flow and withdrawal detail; user's own screenshot confirms; T&C 13.7 aligns with Section A; in dubio not triggered.
