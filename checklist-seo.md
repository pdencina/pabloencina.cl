# Checklist SEO — pabloencina.cl

## Paso 1 — Subir los archivos

| Archivo | Dónde va |
|---|---|
| `robots.txt` | raíz del sitio |
| `sitemap.xml` | raíz del sitio |
| `cuanto-cuesta-una-pagina-web-en-chile.html` | raíz del sitio |
| `jsonld-pabloencina.html` | copiar el contenido antes de `</head>` en `index.html` |

Antes de subir el JSON-LD, reemplaza `https://www.linkedin.com/in/TU-USUARIO` por tu perfil real.

## Paso 2 — Correcciones en index.html

- **Title más corto.** El actual tiene ~75 caracteres y Google lo corta. Reemplázalo por:
  `Desarrollo Web y Sistemas a Medida en Chile | Pablo Encina` (58 caracteres)
- **Links del menú.** Cambia `href="index.html"` por `href="/"` en el logo, el menú y el footer. Tu canonical apunta a `/`, así que enlazar a `/index.html` divide la señal entre dos URLs.
- **Contadores.** Las estadísticas muestran "0+ Sistemas facturando" cuando no corre el JavaScript. Pon los números reales en el HTML y que el script solo los anime desde ahí.
- **Enlace al artículo.** Agrega un link desde la sección de preguntas frecuentes de la home hacia `/cuanto-cuesta-una-pagina-web-en-chile.html`, en la pregunta de precio. Sin ese enlace interno, Google tarda mucho más en darle valor a la página nueva.
- **Revisa los precios del artículo.** Los rangos son referenciales de mercado. Ajústalos a lo que realmente cobras antes de publicar.

## Paso 3 — Search Console

1. Entra a `search.google.com/search-console` y agrega la propiedad de dominio.
2. Verifica con un registro TXT en el DNS (cubre www y no-www de una vez).
3. En "Sitemaps", envía `sitemap.xml`.
4. En "Inspección de URLs", pega la URL del artículo y pide indexación manual.
5. Repite la propiedad en Bing Webmaster Tools, que además importa todo desde Search Console en un clic.

## Paso 4 — Perfil de Negocio de Google

Esto es lo de mayor retorno y no toca el sitio.

- Categoría principal: "Diseñador de sitios web". Secundaria: "Empresa de software".
- Marca el negocio como de servicio a domicilio y define el área: Región Metropolitana y Chile.
- Sube el logo, la imagen OG y capturas de los sistemas.
- Publica actualizaciones cada 2 semanas.
- **Pide reseñas.** Apunta a 8-10 de clientes reales en el primer mes. Es lo que decide el paquete local.

## Paso 5 — Enlaces desde tus propios sitios

Tienes 7 sitios en producción. Agrega en el footer de cada uno un enlace a pabloencina.cl, **variando el texto del enlace** (todos iguales se ve manipulado):

- VentaFlow: "Desarrollado por Pablo Encina"
- Kiva360: "Sistema desarrollado a medida"
- Re-Booking: "Desarrollo web y sistemas a medida"
- ExpertosPintura: "Diseño y desarrollo: Pablo Encina"
- GuardianTech: "Sitio desarrollado por Pablo Encina"
- TorreSecurity: "Desarrollo web profesional"
- Flexio: "Pablo Encina — Desarrollo a medida"

Suma también LinkedIn, GitHub y tu perfil en directorios de freelance, todos apuntando al dominio.

## Paso 6 — Los siguientes artículos

Publica uno cada 2 o 3 semanas. En orden de prioridad:

1. WordPress vs desarrollo a medida: cuál conviene según tu negocio
2. Sistema de gestión para pymes en Chile: cuándo dejar Excel
3. Cómo integrar boleta electrónica del SII en tu sistema
4. Software para jardines infantiles en Chile (conecta con Kiva360)
5. Sistema de reservas para barberías y peluquerías (conecta con Re-Booking)

Los dos últimos son landings por rubro, no artículos: baja competencia, intención de compra directa y llevan tráfico a productos que ya tienes.

## Qué esperar

Los cambios técnicos se ven en Search Console en 1 o 2 semanas. El Perfil de Negocio puede traer contactos en el primer mes. El contenido demora entre 3 y 6 meses en posicionar. No hay atajo en esa parte.
