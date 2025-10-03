"Descargo de responsabilidad

Advertencia: Este documento describe técnicamente un fragmento de HTML con fines educativos y defensivos (análisis, detección y documentación). No debe usarse para engañar a personas reales ni desplegarse en entornos públicos. Trabaja siempre en un laboratorio aislado y con autorización escrita.

Estructura HTML

Documento HTML mínimo con etiquetas básicas: <html>, <head>, <body>.

El <head> contiene un <title> vacío. No hay meta tags (charset, viewport) ni recursos externos declarados.

El contenido visible se encuentra dentro de un único <div> en el <body>.

Estilos y presentación

El <div> utiliza estilos inline para controlar tipografía y diseño:

font-family: 'Segoe UI', Arial, sans-serif;

font-size: 14px; color: #333; max-width: 600px; line-height: 1.6;

El diseño emplea el color #0078D4 en varios elementos (encabezado, palabras destacadas, enlace), y la tipografía prioriza Segoe UI (asociada visualmente con Microsoft).

Contenido y jerarquía

Texto introductorio en un <p> con tamaño 16px y color gris, que incluye <strong> y <span> estilizado.

<h1> principal con texto: “Intento de inicio de sesión inusual” (tamaño 28px, color azul).

Párrafos explicativos que mencionan una fecha y recomiendan restablecer la contraseña; las partes importantes están resaltadas con <strong>.

Un enlace (<a>) estilizado como botón centrado con:

background-color: #0078D4; color: white; padding: 12px 24px; font-weight: bold; border-radius: 5px;

href del botón: {{.URL}} — indica uso de un motor de plantillas que sustituirá esa variable en tiempo de renderizado.

Firma final con <strong> y uso repetido del <span> azul para la palabra “Microsoft”.

Enlace a la «Declaración de privacidad» que apunta a https://go.microsoft.com/fwlink/?LinkId=521839.

Dirección postal en texto pequeño (12px) al final."
