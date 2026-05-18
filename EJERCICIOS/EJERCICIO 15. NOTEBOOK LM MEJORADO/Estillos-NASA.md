# 🚀 Guía de Estilo Visual NASA — Para Presentaciones NotebookLM

> Este documento define el sistema de diseño visual basado en **NASA.gov** para que todas las presentaciones generadas mantengan una identidad consistente, científica, y visualmente impactante. Úsalo como referencia de estilo al crear diapositivas, informes y contenido.

---

## 1. IDENTIDAD VISUAL Y FILOSOFÍA DE DISEÑO

El estilo NASA se caracteriza por:

- **Autoridad científica**: diseño limpio y estructurado que transmite rigor y confianza.
- **Épica espacial**: imágenes de gran impacto visual del cosmos, la Tierra desde el espacio, cohetes y astronautas.
- **Contraste dramático**: fondos oscuros (negro espacial, azul noche) con texto blanco luminoso y acentos en azul eléctrico o rojo NASA.
- **Minimalismo funcional**: nunca recargado, cada elemento tiene un propósito.
- **Escala y grandiosidad**: las imágenes ocupan toda la diapositiva cuando es posible (full-bleed).

---

## 2. PALETA DE COLORES OFICIAL

### Colores primarios

| Nombre           | Código HEX | Uso principal                          |
|------------------|------------|----------------------------------------|
| Negro Espacial   | `#000000`  | Fondo principal de diapositivas        |
| Azul Profundo    | `#0B1628`  | Fondo alternativo, headers             |
| Azul NASA        | `#105BD8`  | Acentos, botones, destacados           |
| Azul Cielo       | `#4B9CD3`  | Subtítulos, líneas decorativas         |
| Blanco Puro      | `#FFFFFF`  | Texto principal sobre fondos oscuros   |
| Gris Plata       | `#A8B2C1`  | Texto secundario, pies de foto         |

### Colores de acento

| Nombre           | Código HEX | Uso                                    |
|------------------|------------|----------------------------------------|
| Rojo NASA        | `#FC3D21`  | Logo NASA, alertas, énfasis crítico    |
| Naranja Despegue | `#FF6B35`  | Estadísticas clave, cifras destacadas  |
| Dorado Estrella  | `#FFD700`  | Datos muy importantes, citas           |

### Regla de uso de color

> **Fondo oscuro + texto blanco** es la combinación estándar.
> Reserva los fondos blancos o claros únicamente para diapositivas de datos/tablas donde la legibilidad sea prioritaria.
> Nunca uses más de 3 colores activos en una misma diapositiva.

---

## 3. TIPOGRAFÍA

### Fuentes recomendadas

| Rol               | Fuente preferida          | Alternativa                  |
|-------------------|--------------------------|------------------------------|
| Título principal  | **Barlow Condensed Bold** | **Oswald Bold**              |
| Subtítulo         | **Barlow SemiBold**       | **Roboto Medium**            |
| Cuerpo de texto   | **Source Sans Pro**       | **Open Sans Regular**        |
| Datos/Estadísticas| **Barlow Condensed**      | **Orbitron** (para datos)    |
| Pies de foto      | **Source Sans Pro Light** | **Roboto Light**             |

> 💡 Todas disponibles gratis en Google Fonts: https://fonts.google.com

### Tamaños orientativos (presentación 16:9)

| Elemento              | Tamaño sugerido |
|-----------------------|-----------------|
| Título de diapositiva | 48–64 pt        |
| Subtítulo             | 28–36 pt        |
| Texto de cuerpo       | 20–24 pt        |
| Pie de foto / nota    | 14–16 pt        |
| Estadística destacada | 72–96 pt        |

### Reglas tipográficas

- Los títulos van siempre en **MAYÚSCULAS** o con cada palabra en Mayúscula.
- Usa **kerning amplio** (espaciado entre letras +5 a +10%) en títulos cortos.
- El cuerpo de texto alineado a la izquierda; los títulos pueden centrarse en portadas.
- Evita mezclar más de 2 familias tipográficas.

---

## 4. IMÁGENES DE FONDO Y FOTOGRAFÍA

### Fuentes oficiales y gratuitas de imágenes NASA

- **NASA Image and Video Library**: https://images.nasa.gov
- **Hubble Site Gallery**: https://hubblesite.org/images/gallery
- **JWST Image Gallery (Webb Telescope)**: https://webbtelescope.org/images
- **NASA Earth Observatory**: https://earthobservatory.nasa.gov/images
- **Flickr NASA oficial**: https://www.flickr.com/photos/nasa2explore/

> Todas las imágenes de la NASA son de **dominio público** y pueden usarse libremente.

### Tipos de imágenes para cada sección

| Tipo de diapositiva       | Imagen recomendada                                              |
|---------------------------|-----------------------------------------------------------------|
| Portada / Título          | Galaxias, nebulosas coloridas, lanzamiento de cohete           |
| Introducción              | Tierra desde el espacio (vista orbital)                        |
| Datos / Estadísticas      | Fondo estrellado oscuro con partículas                         |
| Exploración / Misiones    | Superficie de Marte, rover, astronauta en EVA                  |
| Tecnología / Innovación   | Centro de control de misión, sala limpia, telescopio           |
| Conclusión / Cierre       | Salida del sol sobre la Tierra, horizonte espacial             |
| Agradecimientos           | Logo NASA sobre fondo negro o imagen del Sistema Solar         |

### Técnica de uso de imágenes

- Las imágenes deben cubrir **toda la diapositiva** (full-bleed, sin márgenes blancos).
- Aplica una **superposición oscura** (overlay negro al 40–60% de opacidad) sobre la imagen de fondo para garantizar legibilidad del texto.
- Usa **gradiente linear** de negro en la parte inferior para que el texto aparezca sobre un área más oscura.
- Evita imágenes borrosas o de baja resolución: mínimo 1920×1080 px.

---

## 5. ESTRUCTURA Y LAYOUT DE DIAPOSITIVAS

### Plantilla de portada

```
┌─────────────────────────────────────────────┐
│  [IMAGEN ESPACIAL FULL-BLEED + overlay 50%] │
│                                              │
│   ● Logo NASA (esquina superior izquierda)  │
│                                              │
│                                              │
│   TÍTULO PRINCIPAL EN MAYÚSCULAS             │
│   Subtítulo descriptivo                      │
│   ─────────────────────                      │
│   Nombre del presentador | Fecha | Misión    │
└─────────────────────────────────────────────┘
```

### Plantilla de diapositiva de contenido

```
┌─────────────────────────────────────────────┐
│  TÍTULO DE SECCIÓN                          │
│  ════════════════                           │
│                                              │
│  • Punto clave 1                            │
│  • Punto clave 2                            │
│  • Punto clave 3                            │
│                                  [IMAGEN    │
│                                   LATERAL]  │
│                                              │
│  ─────────────────────────────────────────  │
│  NASA | Misión X | Año                      │
└─────────────────────────────────────────────┘
```

### Plantilla de estadísticas clave

```
┌─────────────────────────────────────────────┐
│  [FONDO OSCURO ESTRELLADO]                  │
│                                              │
│     384.400 km          13.800 M años       │
│  distancia a la Luna    edad del universo   │
│                                              │
│     1.392.000 km            8 min           │
│   diámetro del Sol      luz del Sol a Tierra│
└─────────────────────────────────────────────┘
```

---

## 6. ELEMENTOS GRÁFICOS Y DECORATIVOS

### Líneas y separadores
- Usa líneas horizontales delgadas (1–2px) en color **Azul NASA (#105BD8)** o **Azul Cielo (#4B9CD3)** para separar secciones.
- Evita bordes gruesos o decoraciones ornamentales.

### Iconografía
- Íconos de estilo **outline** (trazo fino) en blanco o azul claro.
- Pueden usarse los íconos de la familia **Material Symbols** o **Font Awesome** (cohete, satélite, planeta, telescopio, átomo).
- Nunca uses emojis como elemento gráfico principal en diapositivas formales.

### Gráficos y datos
- Usa **gráficos de líneas o barras** sobre fondo oscuro con líneas en azul eléctrico o blanco.
- Resalta el dato más importante con una tipografía grande y color dorado o naranja.
- Incluye siempre la fuente del dato (NASA, JPL, ESA…).

### Logo NASA
- Usa siempre el **logotipo oficial "NASA Meatball"** (círculo rojo con letras blancas y vector azul).
- Descárgalo en: https://www.nasa.gov/nasa-brand-center/images-and-media/
- Posición: esquina superior izquierda o inferior derecha de cada diapositiva.
- Nunca lo deformes, cambies de color o pongas sobre fondos que dificulten su lectura.

---

## 7. VOZ Y TONO DEL CONTENIDO

- **Científico pero accesible**: preciso sin ser hermético.
- **Épico e inspirador**: recuerda que NASA representa la exploración del futuro.
- **Conciso**: máximo 5–6 líneas de texto por diapositiva.
- **Activo**: usa verbos de acción ("Descubrimos", "Lanzamos", "Exploramos").
- Incluye siempre **cifras concretas** que den escala al contenido.
- Termina las presentaciones con una **cita inspiradora** de un astronauta o científico NASA.

### Ejemplos de citas NASA para cierre

> *"That's one small step for man, one giant leap for mankind."*
> — Neil Armstrong, Apolo 11, 1969

> *"Earth is the cradle of humanity, but one cannot live in a cradle forever."*
> — Konstantin Tsiolkovsky

> *"The important achievement of Apollo was demonstrating that humanity is not forever chained to this planet."*
> — Neil Armstrong

---

## 8. APLICACIÓN EN NOTEBOOKLM

Al generar presentaciones desde NotebookLM, indica las siguientes instrucciones:

1. **Fondo**: Usa imágenes espaciales de alta resolución (nebulosas, galaxias, Tierra orbital) con overlay oscuro.
2. **Colores**: Negro (`#000000`) o Azul Profundo (`#0B1628`) de fondo; texto blanco (`#FFFFFF`); acentos en Azul NASA (`#105BD8`).
3. **Tipografía**: Barlow Condensed para títulos en MAYÚSCULAS; Source Sans Pro para cuerpo de texto.
4. **Estructura**: Portada épica + máx. 5–6 bullets por diapositiva + diapositiva de estadísticas + cierre con cita.
5. **Logo**: Incluir logotipo NASA en cada diapositiva.
6. **Imágenes**: Extraer de NASA Image Library (images.nasa.gov) o Hubble Gallery.
7. **Tono**: Científico, épico, conciso. Números concretos. Verbos de acción.

---

## 9. CHECKLIST ANTES DE PRESENTAR

- [ ] ¿El fondo es oscuro con overlay para garantizar legibilidad?
- [ ] ¿Los títulos están en Barlow Condensed Bold o similar, en MAYÚSCULAS?
- [ ] ¿La paleta se limita a negro/azul profundo + blanco + 1–2 acentos?
- [ ] ¿Hay máximo 6 líneas de texto por diapositiva?
- [ ] ¿Las imágenes son de alta resolución y de fuente NASA oficial?
- [ ] ¿Aparece el logo NASA en todas las diapositivas?
- [ ] ¿Los datos tienen fuente citada?
- [ ] ¿La última diapositiva incluye una cita inspiradora?

---

*Guía de estilo basada en el diseño visual de NASA.gov — Elaborada para uso en NotebookLM*
*Fuentes: nasa.gov · images.nasa.gov · hubblesite.org · webbtelescope.org*
