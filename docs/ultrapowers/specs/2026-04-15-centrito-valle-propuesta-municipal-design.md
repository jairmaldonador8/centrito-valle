# DISEÑO: Centrito Valle - Propuesta Web Municipal

**Fecha**: 15 de abril de 2026  
**Objetivo**: Transformar el sitio en una propuesta impecable, funcional y profesional para que el municipio de San Pedro Garza García la adopte como sitio oficial del Centrito Valle.  
**Timeline**: Hoy (completar para presentación mañana)  
**Propietario**: Jair Maldonador + equipo

---

## 📋 RESUMEN EJECUTIVO

Enriquecer la página actual de Centrito Valle con:
- Contenido real basado en investigación (San Pedro, Centrito, noticias)
- Imágenes auténticas antes/después del barrio mostrando transformación
- Negocios reales extraídos de Google Maps (15-20 establecimientos)
- Noticias municipales relevantes
- **Amplificación del Mundial 2026**: Partidos, venues, eventos, watch parties
- Polish visual: Loading con logo, animaciones suaves, diseño elegante & alternativo

---

## 🎯 OBJETIVOS PRINCIPALES

1. **Impacto Visual**: Que se vea profesional, elegante, alternativo pero corporativo
2. **Funcionalidad**: Todo debe trabajar fluidamente sin errores
3. **Contenido Auténtico**: Datos reales de Google Maps, noticias verificadas, imágenes legítimas
4. **Viralidad**: El Mundial 2026 como gancho principal para atraer gente a la zona
5. **Escalabilidad**: Estructura que permita agregar datos municipales confidenciales mañana

---

## 📊 FASES DE IMPLEMENTACIÓN

### FASE 1: INVESTIGACIÓN & ENRIQUECIMIENTO DE CONTENIDO

#### 1.1 San Pedro Garza García + Centrito Valle (Research)
- **Historia del municipio**: Datos relevantes, importancia económica, demografía
- **Qué es Centrito Valle**: Definición, ubicación, historia, transformación reciente
- **Revitalización**: Datos de mejoras de infraestructura, impacto comunitario
- **Deliverable**: Snippets de texto para actualizar hero, footer, secciones clave

#### 1.2 Imágenes Antes/Después (Google Street View + Redes Sociales)
- **Cantidad**: 8-12 imágenes reales del barrio
- **Antes**: Estado previo (2020-2022)
- **Después**: Estado actual con mejoras (2024-2026)
- **Enfoque**: Infraestructura, espacios públicos, fachadas de negocios, iluminación
- **Formato**: JPG/PNG optimizado (max 300KB cada una)
- **Ubicación en página**: Sección "Antes/Después" (reemplaza slider actual)
- **Deliverable**: 2 sets de imágenes + captions explicativos

#### 1.3 Negocios Reales (Google Maps + Verificación)
- **Cantidad**: 15-20 establecimientos del Centrito
- **Datos por negocio**: 
  - Nombre
  - Categoría (Café, Restaurante, Bar, Tienda, Arte, Parque)
  - Descripción (2-3 líneas)
  - Teléfono
  - Horarios
  - Ubicación (lat/lng)
  - Foto (si está disponible)
- **Verificación**: Que existan actualmente en Google Maps
- **Deliverable**: Array JavaScript actualizado o JSON con datos reales

#### 1.4 Noticias Municipales Relevantes (Web Search)
- **Cantidad**: 4-6 noticias relevantes
- **Temas**: Eventos municipales, inauguraciones, proyectos Centrito, cultura San Pedro
- **Fuentes**: Noticias municipales, periódicos locales, redes sociales oficiales
- **Datos por noticia**: Título, excerpt, fecha, categoría, enlace
- **Deliverable**: Array JavaScript o JSON actualizado

#### 1.5 🔴 MUNDIAL 2026 - LA ARMA GANADORA

**Context**: El Mundial 2026 es el gancho principal para atraer gente a Centrito Valle.

**Sub-secciones a expandir:**

**A. Partidos de México - 2026**
- Fechas exactas de partidos de México en junio 2026
- Horarios en zona horaria de México
- Grupos, fases (Grupo/Octavos/Cuartos)
- Próximos 2-3 partidos con countdown dinámico

**B. Venues en San Pedro**
- Cafés/restaurantes/bares del Centrito donde se verá el torneo
- Capacidad, ambiente (deportivo, casual, familiar, alternativo)
- Promotions especiales durante partidos
- Contacto para reservaciones

**C. Watch Parties & Eventos**
- Eventos públicos en el Centrito durante el Mundial
- Street parties, proyecciones en espacios públicos
- Horarios de los eventos
- Qué esperar (música, comida, atmósfera)

**D. Sección "Vive el Mundial en Centrito"**
- Destacar que Centrito es "la zona" para ver el torneo en San Pedro
- Promos de negocios durante partidos
- Fotos/videos de atmosphera durante eventos previousos (si existen)

**Deliverable**: Contenido expandido, imágenes, datos de partidos y eventos

---

### FASE 2: MEJORAS UI/UX & POLISH

#### 2.1 Loading Screen Mejorado
- **Logo de Centrito** animado en el centro
- **Spinner elegante** rotando alrededor del logo
- **Duración**: 1-2 segundos máximo
- **Fade**: Transición suave a página completamente cargada
- **Implementación**: CSS animations + JavaScript

#### 2.2 Sección Antes/Después Mejorada
- **Slider interactivo** con imágenes reales
- **Drag de mouse + touch support** (ya existe)
- **Captions dinámicas** explicando transformación
- **Transiciones suaves** entre imágenes
- **Responsive**: Funciona perfecto en móvil

#### 2.3 Sección Mundial Expandida
- **Layout mejorado**: Próximos partidos destacados
- **Countdown dinámico** a próximo partido
- **Grid de venues**: Dónde ver en Centrito
- **Promo codes**: Descuentos de negocios durante torneo
- **Visual storytelling**: Vibes de celebración

#### 2.4 Navbar & Footer Actualizados
- **Links a redes sociales** del Centrito (Instagram, TikTok si existen)
- **Info de contacto** actualisada
- **Links a Google Maps** del Centrito
- **Badges**: "Sitio Oficial del Centrito Valle"

#### 2.5 Micro-animaciones & Transiciones
- **Hover effects**: Suave, coherente, no distraído
- **Scroll reveals**: Elementos que animan al scrollear
- **Page transitions**: Fade suave entre secciones
- **Loading states**: Visual feedback en formularios (newsletter)
- **Velocidad**: Todo debe ser rápido, sin lag

---

### FASE 3: VALIDACIÓN & DEPLOYMENT

#### 3.1 Testing & QA
- **Navegación**: Todos los links funcionan
- **Responsive**: Desktop, tablet, móvil
- **Performance**: Imágenes optimizadas, carga rápida
- **Formularios**: Newsletter funciona (visual al menos)
- **Datos**: Todos los contenidos actualizados y verificados
- **Animaciones**: Suaves, sin glitches, a 60fps

#### 3.2 Optimizaciones
- **Imágenes**: Compresión sin perder calidad (WEBP si es posible)
- **Lazy loading**: Si hay muchas imágenes
- **Cache**: Headers de navegador optimizados
- **SEO**: Meta tags actualizados con contenido real

#### 3.3 Deployment
- **Local server** activo para presentación
- **Backup de código**: Commit limpio
- **Testing final**: Presentación simulada

---

## 🏗️ ARQUITECTURA DE CONTENIDO

```
index.html (mejorado)
├── HEAD: Meta tags actualizados
├── HERO: "Vive el Centrito, vive San Pedro"
├── TICKER: Noticias municipales en tiempo real
├── CATEGORIES: Sin cambios (6 categorías)
├── STATS: Datos actualizados de San Pedro/Centrito
├── EVENTS: Noticias municipales reales
├── MUNDIAL: 🔴 SECCIÓN EXPANDIDA (Partidos, Venues, Watch Parties)
├── PLACES: Negocios reales (15-20 establecimientos)
├── PROMOS: Descuentos especiales (algunos para Mundial)
├── ANTES/DESPUÉS: Imágenes reales del barrio
├── RUTA CAFÉ: Cafés reales del Centrito (actualizar)
├── NOTICIAS: Noticias municipales verificadas
├── PATROCINADORES: Logos actuales (sin cambios mayor)
├── NEWSLETTER: Sin cambios funcionales
└── FOOTER: Contactos actualizados, redes sociales
```

---

## ⚙️ DATOS A ACTUALIZAR

| Sección | Tipo de Dato | Fuente | Estado |
|---------|-------------|--------|--------|
| Hero | Descripción | Manual research | Pending |
| Stats | Números San Pedro | Google, Inegi | Pending |
| Lugares | Negocios (15-20) | Google Maps | Pending |
| Noticias | Articles (4-6) | Web search | Pending |
| Mundial | Partidos, venues | FIFA.com, local | Pending |
| Antes/Después | Imágenes (8-12) | Street View, social | Pending |
| Cafés | 5 cafeterías reales | Google Maps | Pending |
| Eventos | Eventos municipales | Web search | Pending |

---

## 🎨 DISEÑO VISUAL

**No hay cambios en la paleta de colores o tipografía** (mantener lo existente):
- **Colores**: Oro (#C9A84C), Terra (#C1440E), Verde (#2D5016), Cream, Black
- **Tipografía**: Fraunces (headers), DM Sans (body)
- **Estilo**: Elegante, alternativo, profesional, minimalista

**Cambios en:**
- **Animaciones**: Polish, transiciones suaves, micro-interactions
- **Loading**: Logo de Centrito animado
- **Imágenes**: Reemplazo de gradientes con fotos reales
- **Layout**: Mejor jerarquía en sección Mundial

---

## 📱 RESPONSIVENESS

- **Desktop**: Sin cambios (ya funciona bien)
- **Tablet (768px-1024px)**: Verificar grid, imágenes
- **Mobile (<768px)**: Slider antes/después debe ser smooth, touch-friendly

---

## 🚀 CRITERIOS DE ÉXITO

✅ La página se ve professional, elegante, alternativa pero corporativa  
✅ Todos los datos son reales y verificables  
✅ Animaciones son suaves y no distraen  
✅ Loading screen es impactante con logo de Centrito  
✅ Sección Mundial es la estrella (vibes de celebración)  
✅ Responsivo y rápido en todos los dispositivos  
✅ Listo para presentar al municipio mañana  
✅ Escalable para agregar datos confidenciales después  

---

## 📅 TIMELINE

- **Hoy**: Investigación + enriquecimiento (4-5 horas)
- **Hoy tarde**: Testing + optimizaciones (1-2 horas)
- **Mañana**: Presentación al municipio

---

## 📝 NOTAS

- Este es un MVP profesional (mínimo viable pero impactante)
- Mañana si sale todo bien, tendrán acceso a datos más confidenciales para mejorar aún más
- La clave es que **se vea como una propuesta terminada**, no como un proyecto en desarrollo
- El Mundial 2026 es el gancho principal: usémoslo bien
