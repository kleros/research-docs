# Case 81 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Recuperacion de tokens no listados (GRASS sobre red Solana) bajo el procedimiento publicado en las FAQ de Lemon (comision de recuperacion del 10% + costos de red).
**Amount in dispute:** ~USD 80.05 (48.22 GRASS) menos comision de recuperacion del 10% y costos de red.
**Question:** ?Debe Lemon ejecutar el procedimiento de recuperacion publicado en su FAQ para un deposito erroneo de un token no listado (GRASS sobre Solana) por ~USD 80, o puede negarse invocando la clausula 13.7 de los T&C?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Politica Seccion A.2 - Informacion:** la oferta tal como se presenta al usuario rige; las FAQ publicas son parte de la informacion vinculante.
2. **Politica Seccion A.3 - Transparencia:** condiciones claras y accesibles; limites ocultos o no justificados pesan en contra del operador.
3. **Politica Seccion A.1 - Proteccion al consumidor:** Lemon debe resguardar los intereses economicos del usuario y ofrecer alternativas razonables cuando existen.
4. **Politica Seccion A.4 - Buena fe:** evaluacion sustantiva, no formalista.
5. **Politica Seccion A.5 - In dubio pro consumidor (TIEBREAKER):** ante duda razonable, se inclina por el usuario.
6. **Politica Seccion B - T&C vs Seccion A:** T&C catch-all (13.7 "no esta obligada") no puede anular Seccion A.
7. **T&C 13.6 / 13.7 y FAQ:** procedimiento de recuperacion discrecional, con minimos de USD 40 (ERC20) y USD 1 (otras redes), comision 10% + red.

## Burden of proof
El usuario debe probar (i) el envio erroneo y (ii) que el caso encaja en el procedimiento publicado. Lemon, al invocar una excepcion tecnica/operativa, debe sustentar por que la recuperacion concreta es imposible mas alla de la mera politica de no listado.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Solscan tx mostrando transferencia de 48.22 GRASS (~USD 80.05) sobre Solana a direccion 6LdAuv...47C4qL en 2024-11-05 | Prueba on-chain | No | Alto |
| Usuario | Cita a FAQ de Lemon sobre recuperacion de no listados con cargo del 10% | Cita politica publica | Confirmada por Lemon | Alto |
| Lemon | Captura de la FAQ propia: ERC20 minimo USD 40; otras redes minimo USD 1; comision 10% + red; "contacta a soporte... revisamos si puede recuperarse" | Politica publica | No (auto-incorporada) | Alto - corrobora al usuario |
| Lemon | Cita textual T&C 13.7 ("no esta obligada a gestionar") | Contrato | No anula Seccion A | Medio |
| Lemon | Afirmacion de que soporte explico al usuario que GRASS no era recuperable | Alegacion | Sin transcripcion ni razon tecnica especifica | Bajo |
| Lemon | Captura de listado de activos soportados (incluye BSOL = wrapped Solana) | Politica publica | No | Bajo-Medio: demuestra que Lemon opera con la red Solana |
| Lemon | Razones genericas (limitaciones tecnicas / financieras / regulatorias) para no listar | Justificacion politica | No aplicada al caso concreto | Bajo |

Immaterial:
- Comparaciones con otras plataformas (excluidas por la propia Lemon y por la politica de Kleros).
- Existencia general de la Wiki educativa de Lemon (no responde al deposito ya efectuado).

## Application
- **Proteccion:** Lemon es un canal de entrada de fondos; bloquear ~USD 80 sin ofrecer ninguna alternativa concreta cuando su propia FAQ contempla recuperacion para "otras redes" desde USD 1 perjudica el interes economico del usuario. Falla parcial.
- **Informacion:** La FAQ tal como se presenta promete revision por soporte y, si es recuperable, devolucion con 10% + red. La oferta-tal-como-se-presenta es vinculante a efectos informativos. Falla en cabeza de Lemon por no aplicar el procedimiento publicado o no justificar por que GRASS sobre Solana queda fuera.
- **Transparencia:** La FAQ es clara sobre minimos (USD 1 para "otras redes"); USD 80 los supera holgadamente. La negativa categorica por "no listado" no esta sustentada en una razon tecnica especifica para GRASS sobre Solana, red que Lemon ya opera (BSOL). Falla en cabeza de Lemon.
- **Buena fe:** Lemon invoca 13.7 ("no obligada") sin presentar transcripcion de soporte, sin razon tecnica concreta y sin distinguir entre tokens irrecuperables (red sin soporte) y tokens recuperables-pero-no-listados. Marginal.
- **In dubio pro consumidor:** Aunque queda duda sobre si tecnicamente Lemon puede mover un SPL token arbitrario en Solana, la duda se resuelve a favor del usuario, sobre todo porque Lemon controla la informacion tecnica y no la presento.
- **Educacion:** No determinante; el deposito ya esta hecho.
- **No discriminacion:** No invocado.
- **Compatibilidad T&C vs Seccion A:** 13.7 ("no esta obligada") es una clausula catch-all de inmunidad que no puede vaciar de contenido las obligaciones de informacion, transparencia y proteccion de Seccion A, especialmente cuando la propia Lemon publica un procedimiento de recuperacion en su FAQ. Prevalece Seccion A.

## Jurisdiction / Morality / Validity
Disputa contractual ordinaria entre exchange y usuario. Sin cuestiones morales ni de jurisdiccion. Step 0 - RtA: no aplica.

## Schelling-Point check
Un jurado razonable y politica-literato observara que: (a) la FAQ publicada por Lemon promete revision y, si es factible, recuperacion al 10%; (b) el monto supera el minimo de USD 1 para "otras redes"; (c) Lemon opera con Solana; (d) Lemon no aporta evidencia del intercambio de soporte ni razon tecnica especifica. El punto focal apunta a Favor User, condicionando la devolucion a la aplicacion del procedimiento publicado (10% + red) - no a una devolucion integra.

## Bias audit
Hay un atractivo a "el usuario fue descuidado y los T&C son claros". Se corrige: los T&C no son ambiguos en cuanto a la falta de obligacion, pero la FAQ - tambien publicada por Lemon - crea una expectativa concreta de recuperacion sujeta a revision. Negarla en bloque sin justificacion especifica es lo que activa Seccion A. No se favorece al usuario por simpatia, sino porque Lemon no llevo la carga de probar imposibilidad real.

## VOTE
**Favor User**

**Confidence:** medium

## On-chain justification (2-3 short paragraphs, English)

The user provided on-chain proof of an erroneous deposit of 48.22 GRASS (~USD 80) on the Solana network to a Lemon-controlled address. Lemon's own FAQ, reproduced in its descargo, states that for non-listed tokens on "otras redes" (i.e. non-ERC20) the minimum recoverable amount is USD 1, subject to a 10% recovery fee plus network costs and a case-by-case review by support. The deposit easily exceeds that threshold, and Lemon already operates with the Solana network (BSOL appears in its supported-assets screen). Under Section A.2 (Informacion) and A.3 (Transparencia), this FAQ is the offer-as-presented and binds Lemon to apply the published procedure or explain in specific terms why this particular token cannot be moved on a network Lemon already supports.

Lemon's defense rests on T&C clause 13.7, which says it is "not obligated" to manage non-listed assets, plus a bare assertion that support told the user GRASS was unrecoverable. No support transcript, no technical reason specific to GRASS on Solana, and no distinction between technically-irrecoverable assets and merely-non-listed assets is offered. Under Section B, a catch-all immunity in the T&C cannot override Section A obligations of information, transparency and consumer protection, especially when Lemon's own public FAQ contemplates exactly the relief the user requests.

Applying Proteccion, Informacion and Transparencia, and using In Dubio Pro Consumidor as the tiebreaker on the remaining technical uncertainty (which Lemon controls and chose not to address), the vote is for the user, on the basis that Lemon should execute its published recovery procedure (10% commission plus network costs) rather than retain the funds outright. Confidence is medium because the procedure is conditional on technical feasibility, which has not been definitively established either way.
