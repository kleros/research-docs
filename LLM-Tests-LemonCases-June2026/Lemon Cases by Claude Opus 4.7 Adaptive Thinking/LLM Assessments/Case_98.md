# Case 98 — Kleros Juror Assessment

**Court:** Kleros "Blockchain No Técnica"
**Promo / product at issue:** Depósito a Lemon de un token enviado desde una wallet externa (UNO) identificado en la propia evidencia del usuario como "WLD Pi" (token de imitación), supuestamente como depósito de Worldcoin / WLD.
**Amount in dispute:** USD 28 (según descargo de Lemon); el usuario menciona "zll dólares" sin cifra clara y "1000 WLD Pi" en la captura.
**Question:** ¿Debe Lemon acreditar (o devolver al origen) el depósito de 1000 "WLD Pi" enviado desde UNO al address 0xB738…d46a, considerando que el token enviado no es el WLD oficial y no está listado en Lemon?

## Options
- **Favor User** — Lemon debe acreditar o devolver los fondos.
- **Favor Lemon** — No procede acreditación ni devolución porque el token enviado no está listado.
- **Refuse to Arbitrate** — Caso fuera de jurisdicción, inmoral o malformado.

## Governing rules
1. **Protección al Consumidor** — Lemon debe procurar evitar pérdidas evitables, pero no asumir responsabilidad por activos que no presta servicio sobre ellos.
2. **Información** — la oferta y los activos soportados deben presentarse de forma clara.
3. **Transparencia** — el listado de activos y redes admitidas debe ser visible y accesible; lo no listado no se soporta.
4. **Buena fe** — ambas partes deben actuar de manera honesta.
5. **In dubio pro consumidor** — TIEBREAKER cuando la evidencia queda en empate.
6. **Educación** — Lemon debe brindar materiales (Wiki, secciones de novedades) sobre activos listados y prácticas seguras.
7. **No discriminación** — no aplica.
- **T&Cs vs Sección A** — Cláusula 13.7 (activos/redes no listados no se acreditan) es consistente con Sección A cuando los activos listados están públicamente visibles.

## Burden of proof
El usuario, como reclamante que pide modificar el estado por defecto (depósito de un token no soportado no aparece), debe probar que (i) envió un activo efectivamente listado en Lemon, o (ii) que Lemon ocultó información material o prometió de manera vinculante una devolución que estaba en su poder técnico cumplir.

## Material evidence
| Submitter | Evidence | Type | Rebutted? | Weight |
|---|---|---|---|---|
| Usuario | Captura wallet UNO: "Has enviado **1000 WLD Pi** a 0xB738…d46a" | Primary (screenshot del propio usuario) | No — confirma el ticker enviado | High (contra el usuario) |
| Usuario | Alegación de plazos contradictorios de soporte (2 días, 5 días, devolución a Worldcoin) | Secondary (relato sin captura de soporte) | No corroborada por capturas de chat | Low |
| Lemon | Análisis on-chain del hash: token enviado no es WLD oficial sino un token que **simula** ser WLD ("WLD Pi"), no listado | Primary/Secondary (investigación interna consistente con la captura UNO del usuario) | No | High |
| Lemon | Cláusula 13.7 T&C: activos no listados / redes no listadas no se reflejan en cuenta | Policy/Contract | No | High |
| Lemon | Captura del catálogo Lemon "Novedades" (Blockchains/Stablecoins/dApps/L2): no aparece WLD ni "WLD Pi" | Primary | No | High |
| Lemon | Lemon Wiki como recurso educativo | Secondary | No | Medium (Educación) |

Immaterial:
- Logos de Kleros y Lemon en encabezados.
- Justificación general de Lemon sobre por qué no lista todos los tokens (técnico/financiero/regulatorio) — orientativa, no decisiva para Sección A.

## Application
- **Protección:** No obliga a Lemon a acreditar un activo que ni siquiera es el token oficial alegado por el usuario. El propio comprobante del usuario muestra que envió "WLD Pi", un token de imitación. Lemon no opera ni custodia tokens fraudulentos sobre los que no tiene servicio.
- **Información:** El listado de activos de Lemon es público y accesible (Novedades, Wiki). WLD (Worldcoin) no figura en el catálogo mostrado, y "WLD Pi" claramente no es un activo listado. Lemon no ofreció soporte para este token.
- **Transparencia:** No hay límites ocultos. El usuario eligió enviar un token a una address de Lemon sin verificar que estuviera listado. La oferta AS PRESENTED por Lemon no contempla "WLD Pi".
- **Buena fe:** Lemon explica con honestidad la naturaleza del token (imitación) y cita la cláusula aplicable. El usuario actúa de buena fe pero parece haber sido víctima de un token-trampa; eso no transfiere la pérdida a Lemon. La promesa alegada de "devolución a Worldcoin" no está documentada con captura de soporte y, en cualquier caso, devolver un token de imitación a una wallet externa no es necesariamente técnicamente viable ni obligatorio.
- **In dubio:** No procede — la propia evidencia primaria del usuario ("1000 WLD Pi") confirma la versión de Lemon. No hay empate probatorio.
- **Educación:** Lemon cumple con materiales (Wiki + Novedades) que explican qué tokens y redes están soportados.
- **No discriminación:** No aplica.
- **T&C compatibility:** Cláusula 13.7 es compatible con Sección A porque el listado de activos soportados es visible y la regla aplica a un escenario operativo legítimo (no opera como inmunidad genérica).

## Jurisdiction / Morality / Validity
Pasa los tres filtros: dispute de consumidor cripto retail en el subcourt "Blockchain No Técnica"; sin conducta inmoral; pregunta bien formada y respondible con la evidencia.

## Schelling-Point check
Un panel diligente convergería en Favor Lemon: la propia captura del usuario muestra que envió "WLD Pi" (token de imitación), Lemon no lista ese token (ni siquiera el WLD oficial figura en el catálogo mostrado), y la cláusula 13.7 cubre exactamente este escenario. La alegación de un compromiso de devolución por soporte no está corroborada con captura.

## Bias audit
La pérdida del usuario es real y comprensiblemente frustrante, pero la causa eficiente es haber enviado un token de imitación no listado. No se penaliza a Lemon por no operar tokens que nunca soportó. Sin sesgo por simpatía.

## VOTE
**Favor Lemon**

**Confidence:** high

## On-chain justification (2–3 short paragraphs, English)
The user's own primary evidence — a screenshot of the UNO wallet — explicitly shows that the token sent was "1000 WLD Pi", not the official Worldcoin (WLD) token. Lemon's on-chain investigation of the transaction hash corroborates this: the asset received is an imitation token that simulates being WLD but is not the listed asset. Lemon's clause 13.7 directly governs this scenario: digital assets that are not listed on the platform, or sent through unlisted networks, cannot be credited. The Lemon "Novedades" catalogue submitted in evidence shows the supported assets, and neither WLD nor "WLD Pi" appears among them.

Under Sección A, the Información and Transparencia principles are evaluated against the offer Lemon actually presents. Lemon publishes its supported-asset list openly (Novedades and Wiki), satisfying Educación as well. Protección al Consumidor does not extend to forcing a custodian to credit or "return" an imitation token over which it has no service relationship, no liquidity provider and no technical infrastructure. The user's allegation that support promised a refund to a Worldcoin wallet is unsupported by any chat screenshot and, even if accepted, would be operationally constrained by the same problem: the asset is a non-listed imitation token.

In dubio pro consumidor does not apply because the evidence is not in equipoise — the user's own screenshot confirms Lemon's version. T&C clause 13.7 is compatible with Sección A here because it tracks a real operational limit transparently published, not a hidden carve-out. The Schelling-point reading is Favor Lemon.

---

Case 98 | VOTE: Favor Lemon | CONFIDENCE: high | User's own screenshot shows "WLD Pi" (imitation token, not real WLD); not listed in Lemon; clause 13.7 applies; no Sección A violation.
