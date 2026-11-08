# PINOTRES Constructora — sitio web

Sitio estático responsive preparado para GitHub Pages o Vercel.

## Contenido
- Inicio editorial premium, responsive.
- Información corporativa y proyecto Altezza.
- Recorrido interactivo 360° embebido desde el sitio oficial.
- Blog con artículos informativos sobre subsidios VIS, compra sobre planos e inversión.
- Cuatro videos suministrados, incluidos localmente en `assets/`.
- Comentarios/opiniones, mapa de ubicación, contacto y enlaces sociales.
- Acceso directo a WhatsApp.

## Ejecutar localmente
Abre `index.html` en el navegador. Para desarrollo local también puedes usar la extensión Live Server de VS Code.

## Publicar en GitHub y Vercel
1. Descomprime el ZIP.
2. Sube el contenido de la carpeta `pinotres-web` al repositorio `pinotres-constructorasas` (o al repositorio nuevo que elijas). `index.html` debe quedar en la raíz.
3. En Vercel selecciona **Add New → Project**, importa el repositorio y conserva la configuración por defecto. No requiere build command ni framework.
4. Pulsa **Deploy**. Para cambios futuros, sube los commits al repositorio y Vercel volverá a desplegar.

## Antes de publicar
- Revisa con el equipo comercial la vigencia de características, precios, disponibilidad, subsidios y condiciones del proyecto. El contenido evita prometer subsidios o rentabilidades.
- El mapa insertado usa el iframe proporcionado para la sala de ventas.
- El recorrido 360° se carga desde `pinotres.com`.
- Los comentarios se guardan únicamente en el almacenamiento local del navegador del visitante. No son visibles para otros usuarios ni llegan al equipo PINOTRES. Para comentarios públicos reales se debe conectar un backend/CMS y moderación.
- El formulario de contacto principal dirige a WhatsApp; no se envía a una base de datos.
- Las métricas reales de Google Analytics y redes sociales requieren configurar una propiedad GA4, insertar su ID de medición y dar acceso a los reportes de Meta. No se incluyen cifras ficticias.
- Las fotografías editoriales del hero y secciones de ambientación usan imágenes remotas de Unsplash. Para publicación definitiva, reemplázalas por fotografías autorizadas de PINOTRES y Altezza.
- El archivo del logo es el suministrado por el usuario.

## Colores de marca
- Verde profundo: `#37675F`
- Verde: `#00994A`
- Dorado: `#FAB433`
- Blanco: `#FFFFFF`
