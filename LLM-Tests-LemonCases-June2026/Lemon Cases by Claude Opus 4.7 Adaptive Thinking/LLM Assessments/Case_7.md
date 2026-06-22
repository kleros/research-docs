# Case 7 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Depósito accidental de USDC en la red Optimism (red no soportada por Lemon para USDC)
**Amount in dispute:** 250 USDC
**Question:** ¿Debe Lemon reintegrar al usuario los 250 USDC depositados en una red no soportada (Optimism), cuando la evidencia on-chain muestra que los fondos fueron movidos desde la dirección de Lemon hacia una dirección de Binance (proveedor custodio)?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. Política de Interpretación de Disputas — Sección A: (1) Protección, (2) Información, (3) Transparencia, (4) Buena fe, (5) In dubio pro consumidor (tiebreaker), (6) Educación, (7) No discriminación.
2. Sección B: las cláusulas de T&C que choquen con la Sección A no controlan.
3. Estándar de carga: quien afirma un hecho debe probarlo; la evidencia no rebatida se presume genuina.

## Burden of proof
Usuario debe probar que envió fondos y que Lemon (o su proveedor) tiene acceso a ellos. Lemon debe sostener su defensa (red no soportada / sin acceso a fondos) con prueba creíble que rebata la evidencia on-chain del usuario.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Diagrama del flujo de fondos: Usuario → dirección Lemon → dirección Binance | Diagrama narrativo | No rebatida; Lemon reconoce que los movimientos son "internos del proveedor" | Alta |
| Usuario | Capturas del explorador on-chain (Optimism) mostrando dos transferencias de 250 USDC, incluyendo salida desde la dirección Lemon hacia otra dirección | Screenshots blockchain explorer | No rebatida; Lemon admite los movimientos | Alta |
| Usuario | Argumento de estándar de industria (devolución de envíos a redes no soportadas) | Aserción | No rebatida directamente | Media |
| Lemon | Afirmación: "nuestro proveedor no soporta Optimism para USDC" | Aserción sin documentación | El usuario muestra que en la práctica los fondos sí fueron recibidos y movidos | Baja |
| Lemon | Afirmación: "no tenemos acceso a esos fondos" (son internos del proveedor) | Aserción sin prueba | Contradicha por la evidencia on-chain del usuario que muestra una transferencia saliente desde la dirección Lemon | Baja |
| Lemon | Afirmación: "estamos trabajando con el proveedor para reintegrar" | Aserción | Confirma que la devolución es operativamente posible | Media (en contra de Lemon) |

Immaterial:
- Disquisiciones genéricas sobre términos y condiciones de "todos los exchanges" sin texto contractual citado.

## Application
- **Protección:** El usuario es la parte débil; perdió 250 USDC que demostrablemente llegaron a una dirección controlada por Lemon/su proveedor. La protección exige al menos un esfuerzo de buena fe para devolver fondos accesibles.
- **Información:** Lemon no acredita haber informado de forma clara y prominente, al momento del depósito o en la pantalla de generación de dirección, que enviar USDC por Optimism resultaría en pérdida total. La advertencia, si existe, parecería estar enterrada en T&C.
- **Transparencia:** La defensa "no tenemos acceso" se contradice con la propia evidencia del usuario (transferencia saliente desde la dirección Lemon) y con la admisión de Lemon de que "está trabajando con el proveedor para reintegrar" — es decir, sí existe un canal de recuperación. Esto erosiona la transparencia del descargo.
- **Buena fe:** Apoyarse en un tecnicismo de T&C para retener fondos que técnicamente fueron movidos por Lemon/proveedor, sin acreditar imposibilidad técnica real, raya con la mala fe. La propia Lemon admite que la devolución es factible (está "trabajando" en ella).
- **In dubio:** No se necesita invocar como tiebreaker — la balanza ya se inclina hacia el usuario por evidencia y principios. Si hubiera empate, también favorecería al consumidor.
- **Educación / No discriminación:** No aplican directamente.
- **T&C compatibility:** Sección B — una cláusula que permita a Lemon quedarse con fondos a los que tiene acceso operativo, sin obligación de devolución, es incompatible con los principios de Protección, Información y Buena fe; por lo tanto no controla.

## Jurisdiction / Morality / Validity
Caso válido, dentro del subcourt "Blockchain No Técnica" (depósito en red equivocada en exchange centralizado), bien formado, sin defectos morales. No procede RtA.

## Schelling-Point check
Un jurado promedio, alfabetizado en política de consumidor y en práctica de industria cripto, observa: (a) evidencia on-chain no rebatida de que los fondos llegaron y se movieron desde la dirección de Lemon; (b) admisión de Lemon de que está gestionando reintegros con el proveedor; (c) defensa basada en una cláusula T&C genérica sin prueba de imposibilidad técnica. El punto de Schelling razonable es favorecer al usuario, posiblemente con margen para retención de un fee operativo, pero la pregunta binaria es a quién favorecer.

## Bias audit
Cuidado con sesgo pro-consumidor automático: verificado que la conclusión se sostiene incluso sin invocar in dubio. Cuidado con sesgo anti-empresa: examinada la defensa de Lemon en sus mejores términos (red genuinamente no soportada por proveedor) — pero esa defensa fue debilitada por la propia evidencia y por la admisión de que la devolución es viable. Conclusión robusta.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)
The user submitted unrebutted on-chain evidence (Optimism block explorer screenshots and a fund-flow diagram) showing that 250 USDC reached a Lemon-controlled deposit address and was then forwarded onward to a Binance address. Lemon does not dispute these movements; on the contrary, it characterises them as "internal movements of the provider" and confirms it is "working with the provider to refund" affected users. That admission directly contradicts the defensive claim that Lemon has no access to the funds, and it shows the refund is operationally feasible.

Under Section A of the Política de Interpretación de Disputas, Principle 2 (Información) and Principle 3 (Transparencia) require Lemon to surface a clear, prominent warning at the deposit screen that USDC over Optimism will be lost — Lemon produced no such evidence; reliance on buried T&C language is insufficient. Principle 4 (Buena fe) is breached when a custodian invokes a contractual technicality to retain assets it concedes are recoverable. Section B bars any T&C clause incompatible with these principles from controlling.

Principle 1 (Protección) tips the balance toward the user, and Principle 5 (in dubio pro consumidor) is available as a tiebreaker but is not needed here. Vote: Favor User. Confidence medium — the on-chain evidence is strong and Lemon's own admission undermines its defence; the reservation reflects the absence of a clearer accounting of the provider relationship or of any operational refund fee.
