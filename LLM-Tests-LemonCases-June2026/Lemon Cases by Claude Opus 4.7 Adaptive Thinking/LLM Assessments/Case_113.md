# Case 113 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Stellar (USDC) deposit to a Lemon account
**Amount in dispute:** 50.01 USDC (~USD 50)
**Question:** Must Lemon credit a USDC deposit that the user sent over Stellar to an address that Lemon says was never assigned to her account (it was an old Binance-era address discontinued Feb 2024), when her account was only created on 14 July 2025?

## Options
- Favor User / Favor Lemon / Refuse to Arbitrate

## Governing rules
1. **Protección al Consumidor** — vulnerabilidad estructural del usuario; el proveedor debe asumir el riesgo creado por información defectuosa.
2. **Información** — Lemon debe entregar datos de depósito ciertos, claros y actuales. La oferta "tal como se presenta" gobierna.
3. **Transparencia** — Lemon debe revelar de forma clara cualquier limitación o cambio que afecte la operación.
4. **Buena fe** — ambas partes deben actuar de forma coherente con sus declaraciones; reliance del usuario sobre el dato proporcionado por la app es protegida.
5. **In dubio pro consumidor** — desempate solo si la prueba está genuinamente empatada.
6. **Educación financiera** — Lemon debe educar; usuario debe diligencia básica (verificar dirección antes de enviar).
7. **No discriminación** — no aplica.
8. **Sección B** — los T&Cs ceden ante la Sección A si entran en conflicto; cláusula de exoneración por "dirección incorrecta" no puede neutralizar la Sección A si la dirección incorrecta fue inducida por la propia plataforma.

## Burden of proof
El usuario debe acreditar que Lemon le entregó esa dirección específica (GABFQIK…/memo 3994460708) como su dirección de depósito asignada. Si lo prueba → caso suyo. Si no lo prueba → la presunción técnica (direcciones estáticas asignadas en la creación) favorece a Lemon.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Aviso de cierre de sesión por biometría (Page 3) | Secondary screenshot | No | Low (no prueba cambio de dirección) |
| User | Chat de soporte "Nick" (Page 4) — admite que la dirección perteneció al proveedor anterior (Binance) y que se descontinuó en feb 2024; sugiere que la usuaria pudo haberla tenido en agenda; menciona "avisos por app, mail y notificaciones" | Secondary | No | High — corrobora versión de Lemon sobre el origen de la dirección |
| User | "Más Detalles" modal (Page 5) con dirección GABFQIK…JNL6 y memo 3994460708 — completada 14 Jul 2025 7:57 pm | Secondary screenshot | No (parcialmente — Lemon no niega que esta pantalla exista, solo niega su interpretación) | Medium — ambiguo: parece ser registro de transacción, no pantalla de "tu dirección de depósito" |
| User | Stellar explorer (Page 6) — confirma envío de 50.01 USDC al destino etiquetado "[Binance Deposits] GABF…JNL6", memo 3994460708 | Primary on-chain | No | High — confirma que el destino es una dirección de depósito de Binance, no de Lemon |
| Lemon | Captura backoffice "cryptovaultaddresses" — única dirección Stellar asignada a la account_id de la usuaria: GB5R3CLO…, memo 3565203899, creada 14/7/2025 a las 12:06 ARG | Primary internal record | No | High |
| Lemon | Captura backoffice del perfil de la usuaria confirmando account_id | Primary internal record | No | Medium |
| Lemon | Afirmación técnica: las direcciones son estáticas, no se regeneran tras biometría | Argument | Not effectively rebutted | Medium-High |

Immaterial:
- Logos de marca en ambos descargos.

## Application
- **Protección:** El usuario es la parte vulnerable, pero la protección no se extiende a errores operativos cuando la plataforma proporcionó la dirección correcta y existe evidencia documental de ello.
- **Información:** Lemon acredita haber asignado y mostrado en la app una dirección válida (GB5R3CLO…) al momento del registro. El usuario no aporta screenshot de la app de Lemon mostrando GABFQIK… como "su" dirección de depósito asignada — solo aporta el comprobante de la transferencia y un explorer que identifica el destino como "Binance Deposits".
- **Transparencia:** El soporte de Lemon ("Nick") explica con detalle qué ocurrió y por qué. El argumento del usuario de que "los datos cambiaron tras la biometría" es técnicamente inverosímil y no está documentado (no hay screenshot del antes/después).
- **Buena fe:** Ambas partes actúan de buena fe. La explicación de soporte es coherente con la evidencia on-chain (la dirección es etiquetada por Stellar.expert como "Binance Deposits"). El usuario probablemente copió la dirección de un destino externo (agenda, historial, Binance) creyendo que era de Lemon.
- **In dubio:** No procede — la balance probatoria favorece a Lemon de forma clara. La evidencia primaria (backoffice + Stellar explorer mostrando "Binance Deposits") converge.
- **Educación:** Operatoria cripto exige verificación de dirección antes de enviar. El usuario tenía la dirección correcta disponible en la app.
- **No discriminación:** N/A.
- **T&C vs Sección A:** No hay conflicto que requiera resolución — Lemon cumplió con Información y Transparencia entregando la dirección correcta; la cláusula que exime por depósitos a direcciones no asignadas es compatible con Sección A en este escenario.

## Jurisdiction / Morality / Validity
Pasa — disputa típica de la subcorte "Blockchain No Técnica" Lemon. Sin problemas morales ni de validez.

## Schelling-Point check
Un panel de jurados diligentes convergerá en Favor Lemon: (a) evidencia primaria interna muestra dirección distinta asignada; (b) el explorer de Stellar etiqueta el destino como "Binance Deposits" — exonerando a Lemon; (c) el usuario no muestra screenshot de la app de Lemon exhibiendo la dirección errónea como suya; (d) la teoría del "cambio post-biometría" es técnicamente inverosímil y no sustanciada.

## Bias audit
Hay simpatía natural por un usuario que perdió USD 50 actuando de buena fe — pero las reglas exigen prueba de que Lemon entregó la dirección incorrecta. Esa prueba no existe en el expediente. Removiendo simpatía, el resultado es claro.

## VOTE
**Favor Lemon**

**Confidence:** medium

## On-chain justification (2–3 short paragraphs, English)

The dispositive question is whether Lemon supplied the user with the destination address GABFQIK…JNL6 (memo 3994460708) as her assigned Stellar/USDC deposit address. The user bears the burden of proving that affirmative fact under the Información and Transparencia principles, because if Lemon supplied a different (correct) address her loss arises from her own copy/paste from an external source, not from any defect in Lemon's offering.

The evidentiary record favours Lemon. Lemon's primary internal record (the "cryptovaultaddresses" backoffice query, filtered by the user's account_id) shows a single Stellar address assigned to her on the same day she registered (14 Jul 2025, 12:06 ART): GB5R3CLO… with memo 3565203899 — a different address and a different memo from the one she used. The on-chain Stellar explorer screenshot the user herself submitted confirms that the actual destination of her 50.01 USDC transfer is publicly tagged "Binance Deposits", consistent with Lemon's explanation (corroborated by the support-chat screenshot from "Nick") that this is a legacy Binance-provider address discontinued in February 2024 — seventeen months before the user's account even existed. The user's "Más Detalles" modal (page 5) is a transaction-confirmation view containing the address she sent to, not a screenshot of Lemon's app presenting that address as her assigned deposit address. Her theory that the deposit data "changed" after a biometric session reset is technically implausible (assigned addresses are static) and is not documented by any before/after screenshot.

Because Lemon discharged its Información/Transparencia obligations by assigning and displaying a valid deposit address, and the user has not shown that Lemon's offer-as-presented contained the erroneous address, the In dubio tiebreaker does not engage. Educación financiera principles place a minimum verification burden on the user when transmitting irreversible crypto, and Lemon's catch-all on misdirected deposits is, on these facts, compatible with Section A rather than in conflict with it. The vote is Favor Lemon, with medium confidence (lowered only because the user-side narrative is internally consistent and a definitive screenshot of Lemon's in-app deposit screen at registration would have been the ideal disambiguator).
