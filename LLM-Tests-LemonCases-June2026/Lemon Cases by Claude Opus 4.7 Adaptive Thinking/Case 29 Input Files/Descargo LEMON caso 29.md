# Descargo LEMON caso 29.pdf

> Transcribed from PDF using agent vision
> Generated: 2026-05-15

## Page 1

[IMAGE]
Type: logo
Summary: LEMON logo (green circular icon with stylised lemon graphic and the word "LEMON" beneath) at the top right of the page.
[/IMAGE]

**DESCARGO LEMON**

**CASO: 29**
**PARTE: DESCARGO LEMON**
**DESCONOCIMIENTO DE TRANSACCIONES**

User 214376 desconoce dos operaciones realizadas dentro de su cuenta Lemon.
Las operaciones cuestionadas por el User son las siguientes:

[IMAGE]
Type: screenshot
Summary: Two side-by-side mobile screenshots from Lemon Cash showing two near-identical "Retiro de ARS" transactions of 25.000 ARS each at 12:56 on iOS, both dated 02 Mayo 2024, both to recipient Carlos Agustín Ortuay.
Text:

Left screenshot:
[Personal] [signal]    12:56    [headphones] 50% [battery]
                ─
[Argentina flag] 25.000 ARS
              Retiro de ARS
              02 Mayo 2024 - 13:58 hs.

[green check] Completo
              Tu envío ya fue realizado.

Otros detalles
CBU                  0000139300000003213476
Destinatario         Carlos Agustín Ortuay
Comisión             0,00 ARS
Monto enviado        25.000,00 ARS

COELSA ID            [copy]
JMQKYZ9Q4KOL33X82V50P3

Identificador de transacción            [copy]
cf50c53c-5050-491d-a9ec-d29b9492021d

Ver comprobante

Right screenshot:
[Personal] [signal]    12:56    [headphones] 50% [battery]
                ─
[Argentina flag] 25.000 ARS
              Retiro de ARS
              02 Mayo 2024 - 13:58 hs.

[green check] Completo
              Tu envío ya fue realizado.

Otros detalles
CBU                  0000139300000003213476
Destinatario         Carlos Agustín Ortuay
Comisión             0,00 ARS
Monto enviado        25.000,00 ARS

COELSA ID            [copy]
LMORZP90KZROZKQ49EGJ46

Identificador de transacción            [copy]
c07d9f9b-7959-47ba-8b67-2787b41b9c15

Ver comprobante
[/IMAGE]

Analisis del caso:

1. Usuario informa que NO hubo robo de dispositivo en la comunicación con soporte. En su denuncia, no indica nada al respecto.
2. El ingreso a su cuenta se dio por face id y no hubo pedido de passcode ni fallas en el ingreso.

1

## Page 2

[IMAGE]
Type: logo
Summary: LEMON logo at the top right of the page.
[/IMAGE]

3. En caso de que se haya intentado ingresar a la cuenta desde otro dispositivo (device), la app solicita una prueba de biométrica. En este caso no se registró ningún intento de biometría.
4. La última vez que cambio el device fue **30/1/2022, 04:28hs**

[IMAGE]
Type: screenshot
Summary: Internal admin dashboard table showing a SQL-style query result of devices/login_time for User ID 214376. Each row has user_id, device_id (long hex/UUID strings), login_time numeric, and a fecha (date). All rows show user_id 214376.
Text:

[Esta pregunta está escrita en SQL]            User ID
                                             214376    ✕    ↻ DEVICE ID

| user_id | device_id                              | login_time          | fecha            |
| ------- | -------------------------------------- | ------------------- | ---------------- |
| 214376  | 386.111.146.102 [?] 700B7A56-30D7-48A8-A885-E877F7490368 | 1,643,748,317,236   | 2/2/2022, 02:38  |
| 214376  | 386.111.146.102 [?] 700B7A56-30D7-48A8-A885-E877F7490368 | 1,642,745,306,015   | 1,643,765,306,015 [?]; 2/1/2022[?] |
| 214376  | 185.230.34.45                          | 1,643,627,907,623   | 1,643,627,907,623 |
| 214376  | 386.111.146.102                        | 1,643,627,139,537   | 1,643,627,139,537 |
| 214376  | 386.111.145.102                        | 1,643,553,326,328   | 1,643,553,326,328 |
| 214376  | 386.122.18.127                         | 1,643,538,904,204   | 30/1/2022, 04:28 |
| 214376  | 386.122.18.127                         | 1,643,536,900,743   | 30/1/2022, 04:28 |
| 214376  | 386.122.18.127                         | 1,643,533,911,030   | 1,643,533,911,030 |
| 214376  | 4549996b9o9oo9                         |                     |                  |

(Note: long-edge column-truncated values are reproduced as visible. Several "fecha" cells display as raw timestamps where the source did not show a human-readable date.)
[/IMAGE]

5. Todas las operaciones se realizan desde el device e ip habitual desde el que opera el user y desde el que sigue operando. El programa que utilizamos administra el horario con +3 de la hora argentina.

[IMAGE]
Type: screenshot
Summary: Continuation of the admin dashboard, now showing IP / device_id / login_time / fecha columns filtered by User ID 214376.
Text:

[escrita en SQL]            User ID
                          214376    ✕    ↻ DEVICE ID    ↻ Ip

| ip                | device_id                              | login_time          | fecha               |
| ----------------- | -------------------------------------- | ------------------- | ------------------- |
| 181.1.45.206      | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,715,110,852,497   | 7/5/2024, 19:40     |
| 181.1.45.206      | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,715,041,131,464   | 7/5/2024, 00:18     |
| 181.1.45.206      | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,715,038,128,397   | 6/5/2024, 23:28     |
| 181.199.144.232   | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,715,022,686,998   | 6/5/2024, 19:11     |
| 186.13.97.177     | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,715,017,047,197   | 6/5/2024, 17:37     |
| 181.9.171.210     | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,714,945,930,365   | 5/5/2024, 21:52     |
| 181.1.45.206      | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,714,694,996,205   | 3/5/2024, 00:09     |
| 181.1.45.206      | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,714,692,257,892   | 2/5/2024, 23:24     |
| 181.9.170.210     | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,714,677,029,191   | 2/5/2024, 19:10     |
| 186.13.97.225     | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,714,668,982,181   | 2/5/2024, 16:56     |
| 186.13.97.225     | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,714,666,030,454   | 2/5/2024, 16:07     |
| 181.199.144.105   | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,712,104,259,201   | 3/4/2024, 00:30     |
| 181.199.144.109   | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,709,758,991,616   | 6/3/2024, 21:03     |
| 186.13.97.177     | 700B7A56-30D7-48A8-A885-E877F7490368   | 1,709,580,109,528   | 4/3/2024, 19:21     |
[/IMAGE]

2

## Page 3

[IMAGE]
Type: logo
Summary: LEMON logo at the top right of the page.
[/IMAGE]

6. El user indica en el chat con el equipo de soporte que visualiza estas operaciones al intentar realizar compras con la tarjeta y salir rechazadas. Es falso, no hay intentos rechazados el 02.05.24

**Conclusión:**
No debe hacer lugar al reclamo. No se registran vulneraciones en la aplicación, es probable que haya caído una estafa e intente recuperar los fondos desconociendo la transacción que se efectuaron desde su device e IP frecuentes.

3
