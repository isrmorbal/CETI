<h1 align="center">PRÁCTICA 1 UD 1 - LEYES</h1>
<p align="center"><img src="img/"></p>
<br>
<p><b>Nombre: </b>Israel Moreno Ballesta</p>
<p><b>Curso: </b>CETI</p>
<p><b>Asignatura: </b>Hacking Ético</p>

# ÍNDICE

- [Revisa los siguientes extractos legales resumidos:](#revisa-los-siguientes-extractos-legales-resumidos)
- [Responde a estas preguntas en un documento:](#responde-a-estas-preguntas-en-un-documento)
- [Ejercicio práctico: redacta un mini-contrato de autorización de pentesting (máx. media página) que incluya:](#ejercicio-práctico-redacta-un-mini-contrato-de-autorización-de-pentesting-máx-media-página-que-incluya)

## Revisa los siguientes extractos legales resumidos:

- Código Penal español: Art. 197 y 264 → Delitos de acceso indebido y daños informáticos.
- RGPD: Obligación de proteger datos personales y notificar brechas de seguridad.
- Directiva NIS2: Requisitos de seguridad para sectores esenciales (energía, finanzas, salud, digital).

El código penal castiga el acceso sin autorización a cualquier sistema vulnerando sus medidas de seguridad y los daños e interrupciones informáticas, por lo que realizar un pentest solo es legal si hay una autorización previa. El RGPD obliga a proteger los datos y a notificar las brechas a la autoridad en 72 horas y a los afectados si el riesgo es alto. La NIS2 obliga a las entidades de sectores importantes a gestionar sus riesgos, y exige que los incidentes sean notificados en 3 fases, la alerta en 24 horas, notificación en 72 horas y el informe final en un mes.

## Responde a estas preguntas en un documento:

- ¿Qué consecuencias legales tendría un acceso sin autorización a un sistema en España?

Podría ser sancionado con pena de prisión desde 6 meses hasta 2 años y podrían sumarse otros delitos si además del acceso ha obtenido, eliminado, modificado o divulgado datos.

- ¿Qué obligaciones tiene una empresa si sufre una fuga de datos personales bajo el RGPD?

Tiene la obligación de notificar el incidente a la autoridad de control en un plazo máximo de 72 horas desde el descubrimiento de la fuga, y documentar lo sucedido. Y además en caso de ser un riesgo alto debe notificar también a las personas afectadas.

- ¿Qué diferencia hay entre un test de intrusión autorizado y uno no autorizado?

La diferencia es que el test de intrusión autorizado es una simulación legal y controlada de un ciberataque que se ha pactado previamente con la empresa para encontrar vulnerabilidades y poder corregirlas, mientras que un test de intrusión no autorizado es un delito o ataque realizado sin el consentimiento de la empresa.

## Ejercicio práctico: redacta un mini-contrato de autorización de pentesting (máx. media página) que incluya:

- Alcance del test (ejemplo: los equipos de red, servidores, web, aplicación).
- Limitaciones (ejemplo: no atacar la red interna, no usar herramientas de fuerza bruta).
- Responsabilidades (ejemplo: el pentester informará de los hallazgos, ANTES DE EXPLOTARLOS).

En Valencia, a 5 de octubre de 2026.

Partes: Empresa Ejemplo S.L. (el Cliente) y Jose Martínez (el Pentester).

Mediante el presente documento el cliente autoriza al pentester a realizar pruebas de seguridad controladas sobre sus sistemas bajo los siguientes términos:
Alcance. El cliente autoriza al Pentester:
- Router y firewall de la empresa (198.51.100.1 y 198.51.100.2).
- Servidor web (203.0.113.10).
- Página web www.empresaejemplo.com y su aplicación de pedidos.

Fechas: del 6 al 12 de octubre de 2026.

Limitaciones. Para garantizar la continuidad y evitar daños, el pentester no podrá: 
- Atacar la red interna.
- Usar herramientas de fuerza bruta.
- Modificar ni borrar archivos.

Responsabilidades. El Pentester deberá:
- Informar de los hallazgos antes de explotarlos.
- Mantener la confidencialidad de la información.
- Entregar un informe final con las vulnerabilidades y recomendaciones.

Firmas:

Cliente: ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀Pentester:
