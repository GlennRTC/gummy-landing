# 🚀 GUÍA DE DESPLIEGUE PASO A PASO

## ANTES DE EMPEZAR - MUY IMPORTANTE ⚠️

### 1. Actualizar Tu Número de WhatsApp

**DEBES hacer esto ANTES de desplegar:**

1. Abre el archivo `index.html` en un editor de texto
2. Presiona Ctrl+F (o Cmd+F en Mac) para buscar
3. Busca: `584241234567`
4. Reemplaza TODAS las ocurrencias con tu número real
   - Formato: 58 + código de área + número
   - Ejemplo: `584241234567` (sin espacios, guiones ni +)
   - Si tu número es +58 424-123-4567, escribe: `584241234567`

5. Busca también: `+58 424-123-4567` 
6. Reemplázalo con tu número en formato legible
   - Ejemplo: `+58 424-123-4567`

**¿Por qué es importante?**
Todos los botones de "Ordenar" y "Contactar" llevan a este número de WhatsApp.

---

## OPCIÓN 1: DESPLIEGUE DRAG & DROP (RECOMENDADO) 🎯

### Paso 1: Preparar los Archivos

1. Descarga o copia todos los archivos del proyecto a una carpeta en tu computadora
2. Verifica que tengas estos archivos:
   - ✅ index.html
   - ✅ styles.css
   - ✅ script.js
   - ✅ netlify.toml
   - ✅ README.md

### Paso 2: Crear Cuenta en Netlify

1. Ve a: https://www.netlify.com
2. Haz clic en "Sign Up" (Registrarse)
3. Puedes registrarte con:
   - GitHub
   - GitLab
   - Bitbucket
   - O con tu email

4. Si usas email:
   - Ingresa tu email
   - Crea una contraseña
   - Confirma tu email

### Paso 3: Desplegar tu Sitio

1. Una vez dentro de Netlify, verás un área que dice:
   **"Want to deploy a new site without connecting to Git?"**
   
2. Arrastra la carpeta completa `gummy-landing` a esa área
   
   O haz clic en "Browse to upload" y selecciona todos los archivos

3. Netlify comenzará a desplegar tu sitio automáticamente

4. ¡En menos de 1 minuto, tu sitio estará VIVO! 🎉

### Paso 4: Obtener tu URL

1. Netlify te asignará una URL automática como:
   `https://random-name-123456.netlify.app`

2. Puedes cambiar este nombre:
   - Haz clic en "Site settings"
   - Luego en "Change site name"
   - Elige un nombre como: `gummy-supplements-ve`
   - Tu URL será: `https://gummy-supplements-ve.netlify.app`

### Paso 5: Compartir con Clientes

¡Ya puedes compartir tu URL con clientes! 🚀

Copia la URL y envíala por:
- WhatsApp
- Instagram
- Facebook
- Email

---

## OPCIÓN 2: USANDO NETLIFY CLI (AVANZADO) 💻

### Requisitos Previos

- Node.js instalado en tu computadora
- Terminal o línea de comandos

### Paso 1: Instalar Netlify CLI

```bash
npm install -g netlify-cli
```

### Paso 2: Navegar a tu Carpeta

```bash
cd ruta/a/tu/carpeta/gummy-landing
```

### Paso 3: Iniciar Sesión

```bash
netlify login
```

Esto abrirá tu navegador para que autorices la CLI.

### Paso 4: Desplegar

```bash
netlify deploy --prod
```

Selecciona:
- "Create & configure a new site" si es la primera vez
- Elige tu team
- Dale un nombre a tu sitio

### Paso 5: Confirmar

Tu sitio estará desplegado en la URL que te proporcione Netlify.

---

## PERSONALIZAR TU DOMINIO (OPCIONAL) 🌐

### Opción A: Usar Subdominio Personalizado de Netlify

1. En tu sitio de Netlify, ve a "Domain settings"
2. Haz clic en "Options" > "Edit site name"
3. Cambia el nombre a algo memorable
4. Tu URL será: `https://tu-nombre.netlify.app`

### Opción B: Conectar tu Propio Dominio

Si ya tienes un dominio (ejemplo: `www.gummyve.com`):

1. En Netlify, ve a "Domain settings"
2. Haz clic en "Add custom domain"
3. Ingresa tu dominio
4. Sigue las instrucciones para actualizar los DNS

**Costo:** El dominio sí tiene costo (generalmente $10-15 USD/año), pero el hosting en Netlify es GRATIS.

---

## VERIFICAR QUE TODO FUNCIONA ✅

### Checklist de Verificación:

1. ✅ La página carga correctamente
2. ✅ Todos los botones de WhatsApp funcionan
3. ✅ El botón flotante de WhatsApp funciona
4. ✅ La página se ve bien en móvil
5. ✅ El scroll suave funciona
6. ✅ Los colores y diseño se ven correctos

### Probar los Enlaces de WhatsApp:

1. Haz clic en cualquier botón "Ordenar" o "Contactar"
2. Debe abrir WhatsApp Web o la app
3. El mensaje debe estar pre-llenado
4. El número debe ser el TUYO

---

## ACTUALIZAR TU SITIO EN EL FUTURO 🔄

### Si usaste Drag & Drop:

1. Haz los cambios en tus archivos locales
2. Ve a tu sitio en Netlify
3. Haz clic en "Deploys" en el menú superior
4. Arrastra la carpeta actualizada nuevamente

### Si usaste CLI:

```bash
netlify deploy --prod
```

---

## PROBLEMAS COMUNES Y SOLUCIONES 🔧

### Problema: Los botones de WhatsApp no funcionan

**Solución:** Verifica que hayas actualizado el número en TODOS los lugares del `index.html`

### Problema: La página no se ve bien en móvil

**Solución:** Limpia el caché de tu navegador y recarga la página

### Problema: Error 404 al desplegar

**Solución:** Asegúrate de que el archivo principal se llama `index.html` (minúsculas)

### Problema: Los estilos no cargan

**Solución:** Verifica que `styles.css` esté en la misma carpeta que `index.html`

---

## PRÓXIMOS PASOS RECOMENDADOS 📈

1. **Agregar Google Analytics**
   - Para ver cuánta gente visita tu sitio
   - Es gratis

2. **Configurar Facebook Pixel**
   - Para rastrear conversiones
   - Optimizar anuncios de Facebook/Instagram

3. **Crear Enlaces Cortos**
   - Usa bit.ly o similar
   - Más fácil de compartir

4. **Promocionar en Redes Sociales**
   - Comparte tu URL en Instagram Bio
   - Crea posts con el link
   - Comparte en WhatsApp Status

---

## NECESITAS AYUDA? 💬

Si tienes problemas:

1. Revisa esta guía paso a paso
2. Verifica el archivo `README.md`
3. Consulta la documentación de Netlify: https://docs.netlify.com
4. O contáctame para asistencia adicional

---

## CHECKLIST FINAL ANTES DE COMPARTIR ✨

- [ ] Actualicé mi número de WhatsApp
- [ ] Probé todos los botones de WhatsApp
- [ ] Verifiqué que la página se ve bien en móvil
- [ ] Probé la página en diferentes navegadores
- [ ] Personalicé el nombre del sitio en Netlify
- [ ] Tengo mi URL lista para compartir
- [ ] Compartí el link en mis redes sociales

---

¡FELICIDADES! 🎉 Tu landing page está lista para recibir clientes.

**Tu URL:** https://tu-sitio.netlify.app

Compártela y comienza a recibir pedidos por WhatsApp.
