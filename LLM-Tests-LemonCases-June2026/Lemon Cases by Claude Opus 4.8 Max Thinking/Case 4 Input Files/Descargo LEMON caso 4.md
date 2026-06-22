# Descargo LEMON caso 4.pdf

<!-- Transcribed by pdf-to-markdown-ocr-with-assets (agent vision; no external OCR API). Page renders in Descargo LEMON caso 4.assets/page_NNNN.jpeg -->

---

## Page 1 of 4

<u>**DESCARGOS FRAUDE KLEROS**</u>

<u>**Politicas de Prevencion de Fraude Lemon Cash:**</u>

En los términos del punto 5.4 del TO "Sistema Nacional de Pagos - Servicios de pago" la empresa cuenta con un sistema de detección de actividades sospechosas o inusuales de fraude que sigue un modelo de reglas previamente establecidos en base a determinados patrones de comportamiento. Cuando una alerta es activada el equipo de prevención de fraude analiza el caso y resuelve sobre la correspondiente transacción. También se disparan acciones preventivas como el bloqueo de transferencias salientes, que es analizado por el equipo de fraude; o el bloqueo de cuenta cuando se advierte la posibilidad de que el usuario haya sido víctima de apropiación de cuenta mediante técnicas de phishing o ingeniería social. En estos casos se sigue un procedimiento para que el cliente pueda recuperar el poder de su cuenta.

Para poder enrolarse y acceder a la billetera virtual se le solicita al titular una foto del frente y otra del dorso de su documento nacional de identidad. En este punto se verifican y efectúan los siguientes controles: A. Lectura de datos del documento, extracción de campos del documento. B. Detección de caducidad. C. Detección de alteraciones. D. Face Match con la selfie solicitada en forma posterior. E. Umbral de edad. F. Restricción de copias en blanco y negro.

A su vez el proceso de enrolamiento continua con un pedido de prueba de vida para el potencial usuario que consiste en la grabación de un video selfie. Aquí se verifica la vitalidad de la persona y el face match mencionado en el punto D.

A la hora de mitigar ataques de ingeniería social y posibles scams o usuarios de la app la estrategia de la empresa es ser totalmente proactiva ante estos potenciales escenarios. Para ello se efectúan diariamente los siguientes controles:

-  Sistemas de alertas con acciones automáticas y posterior revisión manual.
-  Alarmas o reglas semiautomáticas de revisión manual.
-  Base de antecedentes de Fraude. Nutrida de datos relacionados a las reglas previas o casos consumados.
-  Controles por volúmenes a velocidades inusuales.
-  Forensic a control en pasos o caso acontecido.
-  Exhaustivo control de perfiles falsos en redes sociales. Trabajo en conjunto con META para poder dar la baja y denunciar estos perfiles.
-  Concientización y capacitación de usuarios. Comunicaciones y posteos semanales en redes sociales advirtiendo este tipo de comportamientos.

En los términos del punto 2.6 del TO Sistema Nacional de Pagos - Transferencias - normas complementarias, en base a patrones previamente establecidos se generan alertas de comportamientos inusuales o sospechosos de fraude que luego son analizadas por el equipo de prevención de fraude. En algunos casos se disparan acciones que de forma preventiva impiden operar al cliente hasta tanto se verifique que efectivamente está en control de la cuenta de su titularidad. A su vez se le informa al cliente, tanto por correo electrónico, como a través de notificaciones

1

---

## Page 2 of 4

emergentes de la aplicación las transacciones que se realizan en su cuenta, por ejemplo: aviso de transferencia realizada, aviso de transferencia recibida.

Para llevar a cabo las correspondientes medidas de mitigación de fraude se utilizan las siguientes herramientas:

1.  Metamap: Plataforma de verificación de identidad online. Realiza una prueba biométrica de ti a partir de una selfie o video selfie, los cuales son comparados utilizando inteligencia artificial para asegurar que sea la persona titular el que está utilizando el documento que para validar su identidad. Además Mitiga el riesgo de cumplimiento abordando los requisitos de KYC y AML (sback con listas PLAFT y adverse Media).
2.  Data Dog: Plataforma de supervisión, seguridad y analíticas basada en SaaS para aplicaciones, registros e infraestructura de escala en la nube. Permite integraciones para crear alertas que visualicen comportamientos anómalos, monitorear la actividad de los usuarios y de la App a gran escala y a detalle.
3.  AMPLITUDE: Solución de analytics y optimización digital. Permite a las organizaciones trackear el comportamiento de los usuarios en todas las etapas de interacción con el producto. Monitoreo de comportamientos de usuarios, análisis forenses de casos y creación de cohorts que agrupen patrones de conducta que ameritan ser analizados por el equipo de fraude.
4.  METABASE: Herramienta de Business Intelligence que mediante una interfaz intuitiva permite el acceso a información almacenada en la base de datos. Utilizada por el área de fraude para elaborar alertas transaccionales y de comportamiento, conectada e integrada con otras herramientas para crear reglas de comportamiento.
5.  NEO4J: Software libre de Base de datos orientada a grafos, implementado en Java. Permite establecer a partir de gráficos los comportamientos de usuarios y sus interacciones entre sí y terceros. De gran utilidad para análisis forenses.

<u>**Features de seguridad dentro de la APP:**</u>

1.  Para las transacciones que impliquen retiro de activos de cualquier tipo el usuario tiene la posibilidad de activar un segundo factor de autenticación, el cual puede setear por vía de SMS o Google Authenticator.
2.  También se le facilita al usuario un registro de las sesiones e inicio de sesión abiertas y efectuadas y desde qué dispositivo se realizaron.
3.  Por último dentro de la APP el usuario tiene la opción de configurar la solicitud de clave cada vez que minimiza su APP o hasta por un máximo de 5 minutos.

2

---

## Page 3 of 4

<u>**Caso bajo análisis.**</u>

<u>Contexto</u>:

El usuario se contacta con soporte por robo de dispositivo y transferencias desconocidas.

<u>Resultado de la investigación</u>:

Se rechazó el reclamo ya que no se detectaron vulneraciones en los elementos de seguridad de la App.

En conclusión, el relato de la user tiene correlación con lo observado en la operatoria, no obstante, se determina que la intrusión de la cuenta se debe a: (i) una maniobra de phishing posterior al robo del dispositivo con el fin de hacerse del passcode de acceso a la App; o (ii) una maniobra de phishing con el fin de hacerse del passcode de acceso al teléfono robado para cambiar el face id de acceso a las diferentes apps. Es decir, no hubo vulneración en los elementos de seguridad que sean atribuibles a Lemon.

<u>Evidencia</u>:

En la siguiente captura se observa la diferencia temporal entre el último logueo genuino desde el device id denunciado como robado y el logueo efectuado por el supuesto defraudador con el device robado. Entre ambos existe una brecha temporal de aproximadamente 3 días cabe aclarar que la aplicación Lemon Cash tiene un tiempo máximo de 5 minutos de inactividad por lo tanto el inicio de sesión del defraudador se efectuó con las credenciales de acceso, lo cual refuerza nuestra teoría planteada en el apartado anterior.

[IMAGE]
Type: table
Caption: (none)
Table:

| User ID | IP | Device ID | login_time | fecha |
| --- | --- | --- | --- | --- |
| 1072423 | 181.165.62.111 | 9FE8743C-F3D5-492B-B762-E4EA30BCA1F9 | 1,685,727,585,395 | 2/6/2023, 17:39 |
| 1072423 | 181.165.62.111 | 9FE8743C-F3D5-492B-B762-E4EA30BCA1F9 | 1,685,400,446,140 | 29/5/2023, 22:47 |

[/IMAGE]

En la siguiente captura de pantalla observamos el evento asociado a la transacción desconocida, aclaramos que a diferencia de la captura anterior en este caso el horario está configurado en UTC, por lo tanto la hora local es 5:38:07.

3

---

## Page 4 of 4

[IMAGE]
Type: screenshot
Summary: Analytics (Amplitude) event-detail panel for a "view_withdraw" event, showing event metadata and user properties.
Text:
June 2, 2023
8:38:07.084 pm UTC
[Info] [Raw] [Get Link]

view_withdraw

Event ID                     679121370
Session ID                   -1

User Properties
User ID                      1072423
Device ID                    9fe8743c-f3d5-492b-b762-e4ea30bca1f9
Platform                     iOS
Device Type                  -
Version                      2.6.70
Library                      rudderstack
Country                      Argentina

••• Hide all other 66 User properties
[/IMAGE]

4
