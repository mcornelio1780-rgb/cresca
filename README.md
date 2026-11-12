# Cresca · Web + Panel

Sitio de Cresca (venture builder y company builder de Limly LLC) con panel de administración.

## Qué hay en esta carpeta

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La web pública en ES, EN, PT y FR. Lee `content.json`. |
| `panel.html` | Tu panel: portafolio, aliados, pitches y ajustes. |
| `content.json` | Todo el contenido editable. El panel lo actualiza por ti. |
| `vercel.json` | Oculta el panel de Google y evita caché en `content.json`. |

## Puesta en marcha

Abre **GUIA_PASO_A_PASO.html** y sigue los 6 pasos: GitHub, subir archivos, Vercel, token de GitHub, conectar el panel y prueba final. Unos 15 minutos, todo gratis, sin claves de pago.

El formulario «Hablemos» abre WhatsApp con el mensaje listo para el número de Ajustes (por defecto +51 995 422 760).

## Uso diario

- **Agregar un proyecto:** Portafolio → *Agregar*. Sube el logo (ideal SVG; si no, PNG con fondo transparente), elige industria y colores, escribe en español y pulsa *Traducir con Google (gratis)* para cada idioma y pega la traducción.
- **Web del proyecto:** déjala vacía hasta que exista. Cuando pegues el enlace, aparece el botón «Conocer».
- **Aliados:** Aliados → *Agregar*. La sección «Aliados» aparece sola en la web con el primer logo.
- **Publicar:** botón **Guardar y publicar**. Vercel actualiza la web en 30–60 segundos.
- **Ver antes de publicar:** botón **Ver en la web** (muestra tus cambios sin publicarlos, solo en tu navegador).
- **Pitches:** Pitches → elige idioma (ES, EN, PT, FR) y versión (positivo o negativo) → **Descargar PDF**. En la ventana de impresión: *Guardar como PDF*, márgenes *Ninguno* y *Gráficos de fondo* activado. La diapositiva 5 se arma sola con tu portafolio y tus aliados.

## Seguridad

- El panel se abre desde el enlace **Panel** del footer y pide la contraseña **1789**. Cámbiala si la compartiste: busca `PASS_HASH` en `panel.html` (es el SHA-256 de la contraseña).
- La contraseña frena a visitantes curiosos; lo que de verdad impide publicar cambios es el token de GitHub, que solo está en tu navegador.

- El token de GitHub se guarda solo en tu navegador, nunca en el repositorio.
- Sin token nadie puede publicar cambios, aunque abra `panel.html`.
- Si cambias de computadora, vuelve a completar Ajustes.

## Entidad legal

Cresca es una marca de Limly LLC, Dover, Delaware, EE. UU. Los textos legales de la web son un borrador: conviene que un abogado los revise.
