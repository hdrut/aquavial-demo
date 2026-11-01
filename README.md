# Demo de sitio web - Empresa de obras civiles

Este proyecto es un sitio estático demo para una empresa especializada en:

- Redes de agua potable
- Redes cloacales y aguas grises
- Infraestructura sanitaria e hidráulica
- Obras complementarias de zanjeo, movimiento de suelo y montaje de cañerías

## Archivos principales

- `index.html` → estructura del sitio
- `styles.css` → estilos visuales
- `app.js` → interacciones mínimas
- `assets/images/` → imágenes de obra utilizadas en el demo
- `assets/icons/favicon.svg` → favicon simple

## Cómo visualizar localmente

Abrir `index.html` en un navegador o correr un servidor estático simple:

```bash
python3 -m http.server 8000
```

Luego abrir:

```text
http://localhost:8000
```

## Publicación sugerida

### Cloudflare Pages
1. Subir esta carpeta a un repositorio GitHub.
2. Conectar el repositorio en Cloudflare Pages.
3. Build command: dejar vacío.
4. Output directory: `/`
5. Deploy.

### GitHub Pages
1. Subir el contenido del proyecto a un repositorio.
2. Activar GitHub Pages desde la rama principal.
3. Elegir carpeta raíz.

## Qué conviene personalizar para la versión real

- Nombre de la empresa
- Logotipo
- Colores corporativos
- Obras reales
- Datos de contacto reales
- WhatsApp y formulario operativo
- Ubicación y áreas de cobertura
- Certificaciones / clientes / comitentes
