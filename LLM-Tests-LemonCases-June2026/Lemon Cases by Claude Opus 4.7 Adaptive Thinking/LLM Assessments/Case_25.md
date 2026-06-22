# Case 25 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Lemon Card (tarjeta prepaga VISA) — desconocimiento de transacción no autorizada en Xsolla
**Amount in dispute:** USDC 60.116205 (~ARS 74.050,54 / ~USD 60) — cargo de Xsolla *Eft del 03/02/2024
**Question:** ¿Debe Lemon reintegrar al usuario el importe de una transacción que éste denuncia como no autorizada, habiendo bloqueado la tarjeta inmediatamente y siendo la tarjeta de uso inactivo desde 2022?

## Options
- Favor User
- Favor Lemon
- Refuse to Arbitrate

## Governing rules
1. **Política A.1 Protección** — Lemon debe proteger fondos y datos del usuario.
2. **Política A.2 Información** y **A.3 Transparencia** — la oferta y los procesos de reclamo deben ser claros para el usuario.
3. **Política A.4 Buena fe** — ambas partes deben actuar de buena fe.
4. **Política A.5 In dubio pro consumidor** — sólo desempate.
5. **Política B — compatibilidad de TyC con Sección A** — cláusulas que pretendan eximir a Lemon en casos de **operatorias fraudulentas** no pueden anular el deber de protección.
6. **TyC 5.1 y 5.2** — el reclamo directo al proveedor sólo aplica a **transacciones NO fraudulentas** (controversias comerciales). Las transacciones fraudulentas están expresamente excluidas del alcance de 5.1.
7. Marco regulatorio argentino (Ley 24.240 y normativa BCRA sobre transacciones no reconocidas) como contexto interpretativo.

## Burden of proof
El usuario debe acreditar prima facie el desconocimiento y la diligencia (bloqueo inmediato, contacto con soporte). Una vez establecido el prima facie, Lemon debe acreditar que la operación fue autorizada o que el usuario incumplió obligaciones que justifiquen rechazar el reclamo.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| User | Captura del cargo Xsolla *Eft 73.680,29 ARS / 60,11 USDC del 03/02/2024 11:46 | App screenshot | No | High |
| User | Email "Denuncia exitosa de Lemon Card" 04/02/2024 21:13 — bloqueo de tarjeta terminada en 4081 | Email screenshot | No | High — prueba diligencia inmediata |
| User | Historial de movimientos: última compra propia fue Microsoft Store, 12/07/2022 ARS 64,74 — tarjeta inactiva ~18 meses | App screenshot | No | High |
| User | Comprobante Xsolla 2020 — compra cancelada por USD 4,47 (Fall Guys, 08/06/2020); el medio de pago no fue la Lemon Card (cuenta creada en 04/2022) | Receipt screenshot | No | High — demuestra que Xsolla NUNCA recibió los datos de la Lemon Card del usuario |
| User | Apertura de cuenta Lemon 17/04/2022 — recompensa de bienvenida | App screenshot | No | High |
| User | Chats con soporte (Meli/Vero/Beto) — preguntas y respuestas, escalamiento del reclamo por "desconocimiento de compra" | Chat screenshots | No | High |
| Lemon | Captura de la misma transacción denunciada | Screenshot | — | Low — sólo confirma el hecho |
| Lemon | Cita de TyC 5.1 y 5.2 | Contractual | — | Medium — pero las propias cláusulas excluyen operatorias fraudulentas |
| Lemon | Afirmación: "el propio User reconoce que ya ha operado con dicho comercio… entregó oportunamente sus datos a dicho proveedor" | Assertion | Refutada por usuario + comprobante 2020 con otro medio de pago | Low |

Immaterial:
- Mención al caso BBVA: comparativo, no vinculante.
- Discusión sobre denuncia policial: Lemon no la exigió como condición ni demostró que su ausencia condicione el reclamo.

## Application
- **Protección (A.1):** Lemon falla en proteger al usuario. La tarjeta llevaba ~18 meses inactiva, el usuario reaccionó dentro de 24-48 h, bloqueó la tarjeta, y notificó soporte. El cargo presenta marcadores claros de fraude (proveedor con el que el usuario nunca usó esa tarjeta, cuenta Lemon creada **después** del único contacto con Xsolla en 2020).
- **Información (A.2) / Transparencia (A.3):** Lemon tergiversa los TyC. La cláusula 5.1 expresamente dice "todo lo que refiere a transacciones **NO fraudulentas**", reconociendo que las fraudulentas reciben otro tratamiento. Invocar 5.1/5.2 contra una operación denunciada como fraudulenta es engañoso.
- **Buena fe (A.4):** Lemon afirma que el usuario "reconoce haber operado con Xsolla y entregado sus datos" — pero el usuario probó documentalmente que la compra de 2020 fue **con otro medio de pago** (la Lemon Card no existía aún; la cuenta es de 04/2022). Esta caracterización es contraria a buena fe.
- **In dubio (A.5):** No es necesario llegar al desempate — la evidencia favorece al usuario por preponderancia. Si hubiera duda, también pro-consumidor.
- **Educación (A.6):** Lemon no orientó claramente sobre el camino (denuncia policial sí/no quedó sin respuesta).
- **No discriminación (A.7):** No aplica.
- **Compatibilidad TyC vs Sección A (B):** Aun si Lemon pretendiera leer 5.1 ampliamente, ello sería incompatible con A.1 Protección. La cláusula, leída correctamente, no cubre operaciones fraudulentas — y Lemon tampoco demostró que la operación fuera autorizada.

## Jurisdiction / Morality / Validity
Disputa válida bajo el procedimiento Kleros. No hay objeciones de jurisdicción ni de moralidad.

## Schelling-Point check
Un panel de juradas razonables observaría: (i) tarjeta inactiva durante 18 meses, (ii) bloqueo inmediato, (iii) proveedor que nunca tuvo los datos de **esa** tarjeta, (iv) Lemon citando una cláusula que se autoexcluye en supuestos fraudulentos, (v) Lemon mischaracterizando los hechos del usuario. La coordinación racional converge en Favor User.

## Bias audit
Verifiqué no sobreponderar la simpatía hacia el consumidor. La narrativa del usuario es coherente, documentada y consistente con timestamps verificables (cuenta 04/2022, última compra 07/2022, Xsolla 2020 con otro medio). Lemon no aporta prueba de autorización (PIN, 3DS, IP, geolocalización, registros antifraude). No detecto sesgo indebido.

## VOTE
**Favor User**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)

The user established a strong prima facie case of an unauthorised charge: a Lemon Card that had been inactive since July 2022 was suddenly hit with a ~USD 60 charge at "Xsolla *Eft" on 03/02/2024; the user blocked the card within hours and contacted support promptly. The 2020 Xsolla receipt the user produced shows USD 4.47 paid with a different payment method — the Lemon Card did not exist yet (account opened 17/04/2022). Lemon's central factual claim — that the user "already operated with this merchant and delivered the card data to Xsolla" — is therefore demonstrably wrong and contrary to Política A.4 (buena fe).

Lemon's legal argument rests on T&Cs 5.1 and 5.2, but those clauses by their own wording cover only "transacciones NO fraudulentas" — controversies, duplicates, automatic-debit cancellations, payment errors. They do not cover the very category the user is alleging (fraudulent / unauthorised use). Invoking them here misrepresents the contract and conflicts with Política A.2 Información and A.3 Transparencia. Under Política B, any reading of the T&Cs that would let Lemon disclaim protection in genuine fraud cases is incompatible with Política A.1 Protección and must yield.

Lemon offered no evidence of authorisation (no 3DS, no PIN log, no IP/geolocation, no antifraud trace) and no proof that the user breached any duty of custody. The user's unrebutted screenshots and timeline are presumed genuine. Applying Protección, Información, Transparencia and Buena fe — and without needing to reach In dubio as a tiebreaker — the dispute resolves in favour of the user, who is entitled to refund of USDC 60.116205 (≈ ARS 74.050,54).
