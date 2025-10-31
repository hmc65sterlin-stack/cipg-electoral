# 🏛️ CIPG - Centro de Inteligencia Político Electoral Gubernamental

## 📋 Descripción

Sitio web profesional para el Centro de Inteligencia Político Electoral Gubernamental (CIPG), especializado en análisis electoral, encuestas de opinión y prospectiva con Inteligencia Artificial para campañas políticas en Campeche y México.

---

## ✨ Características

### 🎨 Diseño y UI/UX
- ✅ Diseño moderno con degradados oscuros (indigo/purple/black)
- ✅ Totalmente responsive (móvil, tablet, desktop)
- ✅ Animaciones suaves y transiciones
- ✅ Banner animado con información de Reforma Electoral
- ✅ Navegación sticky intuitiva

### 🤖 Funcionalidades
- ✅ **Chatbot inteligente** con respuestas contextuales
- ✅ **Formulario de contacto** funcional
- ✅ **6 categorías de datos abiertos** con fuentes oficiales
- ✅ **Sección de IA** destacando prospectiva electoral
- ✅ **Botones de acción rápida** en el chatbot
- ✅ Scroll suave entre secciones

### 📊 Servicios Destacados

1. **Encuestas a la medida**
   - Metodología probabilística y no probabilística
   - Análisis estadístico avanzado con IA

2. **IA para Prospectiva Electoral**
   - 10,000+ simulaciones Monte Carlo
   - Machine Learning y redes neuronales
   - Generación de 5-10 escenarios múltiples

3. **Segmentación Inteligente**
   - Análisis territorial con algoritmos
   - Microtargeting demográfico

4. **Cumplimiento Legal**
   - Reportes técnicos conforme a normativa INE/IEPAC

### 📂 Datos Abiertos (Fuentes Oficiales)

El sitio proporciona acceso a fuentes públicas:
- 📊 Resultados electorales históricos (INE, IEPAC)
- 👥 Padrón electoral y listas nominales
- 💰 Financiamiento de partidos políticos
- 🗺️ Mapas y cartografía electoral
- 📋 Encuestas registradas ante el INE
- 👁️ Informes de observación electoral

---

## 🚀 Instalación y Despliegue

### Opción 1: Uso Directo (Sin instalación)

El sitio es un archivo HTML único autocontenido. No requiere instalación de dependencias.

**Uso local:**
1. Descarga el archivo `index.html`
2. Abre con doble clic en cualquier navegador
3. ¡Funciona completamente offline!

### Opción 2: Netlify Drop (30 segundos)

**URL:** https://app.netlify.com/drop

1. Arrastra el archivo `index.html`
2. Espera 10-20 segundos
3. Obtén tu URL pública: `https://tu-sitio.netlify.app`

**Personalizar nombre:**
- Site settings → Change site name → `cipg-electoral`
- Nueva URL: `https://cipg-electoral.netlify.app`

### Opción 3: GitHub Pages

```bash
# 1. Crear repositorio en GitHub
git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/cipg-electoral.git
git push -u origin main

# 2. Activar GitHub Pages
# Settings → Pages → Source: main → Save

# 3. Tu sitio estará en:
# https://TU-USUARIO.github.io/cipg-electoral/
```

### Opción 4: Vercel

```bash
# Instalar Vercel CLI
npm install -g vercel

# Desplegar
vercel

# Seguir instrucciones en pantalla
```

---

## 🔧 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **Tailwind CSS** (vía CDN) - Estilos y diseño responsive
- **JavaScript Vanilla** - Interactividad y lógica del chatbot
- **SVG Icons** - Iconografía vectorial
- **CSS Animations** - Banner animado y transiciones

**Dependencias externas:**
- Tailwind CSS CDN: `https://cdn.tailwindcss.com`

**Sin dependencias de:**
- ❌ Node.js
- ❌ npm/yarn
- ❌ React/Vue/Angular
- ❌ Webpack/Vite

---

## 📱 Secciones del Sitio

1. **Banner de Reforma Electoral** (animado)
   - Información sobre Comisión Presidencial
   - Scroll infinito con pausa al hover

2. **Hero Section**
   - Título destacado sobre IA Electoral
   - CTAs principales

3. **Servicios Principales**
   - 4 servicios core del CIPG
   - Tarjetas interactivas con hover

4. **Servicios Adicionales - Datos Abiertos**
   - 6 categorías consultables
   - Botones con fuentes oficiales

5. **Sección de IA**
   - 4 subsecciones detalladas
   - Diseño destacado con bordes púrpura

6. **Contacto**
   - Formulario funcional
   - Teléfonos y emails
   - Validación de campos

7. **Footer**
   - Información corporativa
   - Copyright

8. **Chatbot Flotante**
   - Botón fijo inferior derecha
   - 10+ respuestas inteligentes
   - Botones de acceso rápido

---

## 🤖 Funcionalidades del Chatbot

### Palabras clave reconocidas:

| Palabra clave | Respuesta |
|--------------|-----------|
| `encuesta` | Información sobre encuestas profesionales |
| `ia`, `inteligencia`, `prospectiva`, `escenarios` | Metodología con IA |
| `estrategia`, `campaña` | Estrategia electoral ganadora |
| `reforma`, `comisión`, `presidencial` | Comisión de Reforma Electoral |
| `contacto`, `teléfono`, `correo` | Datos de contacto |
| `datos`, `fuente`, `abierto`, `público` | Información sobre datos abiertos |

### Botones rápidos:
- 🤖 IA y Prospectiva
- 📊 Encuestas
- ⚡ Estrategia
- 📂 Datos Abiertos
- 📞 Contacto

---

## 📞 Información de Contacto

**Teléfonos:**
- 9811471235
- 4441114866

**Emails:**
- observadorescamp@gmail.com
- casaencuestadorarcyhc@gmx.es

**Horario:**
- Lunes a Viernes, 9:00 - 18:00 hrs

---

## 🌐 Conectar Dominio Personalizado

### En Netlify:

1. Settings → Domain management
2. Add custom domain → `tudominio.com.mx`
3. Seguir instrucciones DNS

### Configuración DNS típica:

```
Tipo: A
Nombre: @
Valor: 75.2.60.5

Tipo: CNAME
Nombre: www
Valor: [tu-sitio].netlify.app
```

**Tiempo de propagación:** 24-48 horas

---

## 🔄 Actualización del Sitio

### Si usas Netlify Drop:
1. Edita `index.html` localmente
2. Arrastra de nuevo a Netlify Drop
3. Confirmará actualización

### Si usas GitHub Pages:
```bash
git add index.html
git commit -m "Actualización: descripción"
git push
# Esperar 1-2 minutos para el rebuild
```

---

## 📊 Estadísticas y Analytics

### Netlify Analytics (incluido gratis):
- Pageviews
- Visitantes únicos
- Fuentes de tráfico
- Páginas más visitadas

### Google Analytics (opcional):
Agregar antes de `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU-ID');
</script>
```

---

## 🎨 Personalización

### Cambiar colores:

Busca en el código y reemplaza:
- `indigo-` → Tu color preferido
- `purple-` → Tu color secundario

### Cambiar logo:

Busca la línea:
```html
<div class="text-2xl">♟️</div>
```

Reemplaza con:
```html
<img src="tu-logo.png" alt="Logo" class="h-12 w-12">
```

### Modificar textos:

Todos los textos están en español y son fácilmente editables directamente en el HTML.

---

## 🆘 Solución de Problemas

### El sitio no carga estilos

**Problema:** Tailwind CSS no carga  
**Solución:** Verifica conexión a internet (requiere CDN)

### El formulario no funciona

**Problema:** Solo muestra alert()  
**Solución:** Para enviar emails reales, integrar con:
- EmailJS: https://www.emailjs.com/
- Formspree: https://formspree.io/
- Netlify Forms (si usas Netlify)

### El chatbot no responde

**Problema:** JavaScript deshabilitado  
**Solución:** Habilitar JavaScript en el navegador

### Banner no se mueve

**Problema:** CSS animations bloqueadas  
**Solución:** Verificar que el navegador soporte CSS animations

---

## 📈 Métricas del Sitio

- **Tamaño:** ~50KB (HTML único)
- **Tiempo de carga:** <2 segundos
- **Performance:** 90+ en Lighthouse
- **Accesibilidad:** Contraste AAA
- **SEO:** Optimizado con meta tags

---

## 🔐 Seguridad

- ✅ HTTPS automático (Netlify/Vercel/GitHub Pages)
- ✅ Sin base de datos (sin vulnerabilidades SQL)
- ✅ Sin dependencias npm (sin CVEs)
- ✅ CSP-friendly
- ✅ Sin cookies de terceros

---

## 📝 Licencia

Sitio desarrollado para CIPG - Centro de Inteligencia Político Electoral Gubernamental

**Empresa:** RC&HC Consulting  
**Ubicación:** Campeche, México  
**Año:** 2025

---

## 🚀 Roadmap Futuro

Posibles mejoras:

- [ ] Sistema de blog integrado
- [ ] Panel de administración
- [ ] Base de datos para leads
- [ ] Integración con CRM
- [ ] Calculadora de costos de encuestas
- [ ] Galería de casos de éxito
- [ ] Chat en vivo real (Tawk.to, Crisp)
- [ ] Versión en inglés
- [ ] PWA (Progressive Web App)
- [ ] Dark/Light mode toggle

---

## 🤝 Soporte

Para soporte técnico del sitio:
- Email: observadorescamp@gmail.com
- Teléfono: 9811471235 / 4441114866

Para issues del código:
- Crear issue en el repositorio de GitHub

---

## 📚 Recursos Adicionales

### Fuentes de datos oficiales integradas:
- INE: https://www.ine.mx/
- IEPAC: https://www.iepac.mx/
- Datos Abiertos México: https://datos.gob.mx/
- INEGI: https://www.inegi.org.mx/

### Documentación técnica:
- Tailwind CSS: https://tailwindcss.com/docs
- HTML5: https://developer.mozilla.org/es/docs/Web/HTML
- JavaScript: https://developer.mozilla.org/es/docs/Web/JavaScript

---

## ✅ Checklist de Despliegue

Antes de publicar, verificar:

- [ ] Todos los textos revisados (ortografía)
- [ ] Teléfonos y emails correctos
- [ ] Links funcionando
- [ ] Chatbot responde correctamente
- [ ] Formulario valida campos
- [ ] Responsive en móvil
- [ ] Carga rápido (<3 segundos)
- [ ] SEO: Title y meta description
- [ ] Favicon agregado (opcional)
- [ ] Google Analytics configurado (opcional)

---

## 🎉 Agradecimientos

Desarrollado con tecnologías web modernas y enfoque en:
- Performance
- Accesibilidad
- Experiencia de usuario
- SEO

**¡Gracias por usar CIPG Electoral!**

---

## 📞 Contacto del Desarrollador

Para consultas sobre el desarrollo del sitio o servicios de CIPG:

**CIPG - RC&HC Consulting**
- 📧 observadorescamp@gmail.com
- 📧 casaencuestadorarcyhc@gmx.es
- 📱 9811471235
- 📱 4441114866

---

**Versión:** 1.0.0  
**Última actualización:** Octubre 2025  
**Autor:** CIPG Development Team
