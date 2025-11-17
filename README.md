# Gummy Supplements Landing Page

Landing page profesional para venta de suplementos nutricionales en gomitas en Venezuela.

## 🎯 Productos

1. **Slim Gummy** - Pérdida de peso con L-Carnitina y Café Verde
2. **Immuno Defence Gummy** - Fortalecimiento del sistema inmunológico

## 🚀 Despliegue en Netlify

### Opción 1: Drag & Drop (Más Fácil)

1. Ve a [netlify.com](https://www.netlify.com)
2. Crea una cuenta gratis
3. Arrastra la carpeta completa del proyecto a la zona de despliegue
4. ¡Listo! Obtendrás una URL como: `https://tu-sitio.netlify.app`

### Opción 2: Netlify CLI

```bash
# Instalar Netlify CLI
npm install -g netlify-cli

# Ir a la carpeta del proyecto
cd gummy-landing

# Iniciar sesión en Netlify
netlify login

# Desplegar
netlify deploy --prod
```

## 📝 Personalización Necesaria

### IMPORTANTE: Actualizar Número de WhatsApp

Busca y reemplaza `584241234567` con tu número real de WhatsApp en:
- `index.html` (aparece múltiples veces)

Formato correcto: `58` + código de área + número (sin espacios ni guiones)
Ejemplo: `584241234567` para +58 424-123-4567

### Actualizar Información de Contacto

En `index.html`, busca la sección de contacto y actualiza:
```html
<!-- Línea ~450 -->
<a href="https://wa.me/TU_NUMERO">+58 XXX-XXX-XXXX</a>
<a href="mailto:TU_EMAIL">tu@email.com</a>
```

### Agregar Enlaces de Redes Sociales

En `index.html`, busca:
```html
<!-- Línea ~470 -->
<a href="TU_INSTAGRAM" target="_blank">Instagram</a>
<a href="TU_FACEBOOK" target="_blank">Facebook</a>
<a href="TU_TIKTOK" target="_blank">TikTok</a>
```

## 🎨 Estructura de Archivos

```
gummy-landing/
├── index.html          # Página principal
├── styles.css          # Estilos
├── script.js           # Funcionalidad JavaScript
├── netlify.toml        # Configuración de Netlify
└── README.md           # Este archivo
```

## 🌟 Características

- ✅ Diseño responsive (móvil, tablet, desktop)
- ✅ Integración con WhatsApp
- ✅ Animaciones suaves
- ✅ SEO optimizado
- ✅ Carga rápida
- ✅ Botón flotante de WhatsApp
- ✅ Sección de productos detallada
- ✅ Información de permisos sanitarios
- ✅ Sección de beneficios
- ✅ Proceso de compra claro
- ✅ Footer con información legal

## 📱 Métodos de Pago Mencionados

La landing page está diseñada para mencionar:
- Pago móvil
- Zelle
- Transferencias bancarias locales
- Binance P2P

## 🔧 Personalización Avanzada

### Cambiar Colores

En `styles.css`, líneas 10-20:
```css
:root {
    --primary-color: #FF6B9D;      /* Color principal */
    --secondary-color: #6B5FFF;    /* Color secundario */
    --accent-orange: #FF8C42;      /* Naranja de acento */
    --accent-purple: #9B5DE5;      /* Morado de acento */
}
```

### Agregar Google Analytics

Antes de `</head>` en `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU_ID');
</script>
```

### Agregar Facebook Pixel

Antes de `</head>` en `index.html`:
```html
<!-- Facebook Pixel -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', 'TU_PIXEL_ID');
  fbq('track', 'PageView');
</script>
```

## 🔒 Seguridad y Privacidad

- No se almacenan datos de usuarios
- No se requiere backend
- Todas las transacciones se manejan vía WhatsApp
- HTTPS automático con Netlify

## 📊 Optimización SEO

La página incluye:
- Meta tags descriptivos
- Estructura HTML semántica
- Velocidad de carga optimizada
- Responsive design
- URLs amigables

## 🆘 Soporte

Si necesitas ayuda con:
- Personalización del diseño
- Agregar nuevas secciones
- Integración con otras plataformas
- Configuración de dominio personalizado

Contacta por WhatsApp usando el número configurado en el sitio.

## 📄 Licencia

Este proyecto es de uso exclusivo para Gummy Supplements Venezuela.

---

Desarrollado con ❤️ para el mercado venezolano
