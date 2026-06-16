# Práctica Formativa Obligatoria 2: Prompt Engineering en Agentes de IA
* **Institución:** Instituto de Formación Técnica Superior N.° 29 (IFTS N.°29)
* **Estudiante:** Herrera Marcela Fernanda

---

## 📄 1. Descripción del Proyecto
. Consiste en una estructura modular compuesta por una **Interfaz de Acceso (Portada Principal/Hub)** que unifica y redirige de forma centralizada a los tres componentes requeridos.
1. **Link 1:** El texto plano del prompt de alta precisión utilizado para la generación.
2. **Link 2:** Landing Page generada de manera 100% autónoma por el **Primer Agente (Claude 3.5 Sonnet)**
3. **Link 3:** Landing Page generada de manera 100% autónoma por el **Segundo Agente (OpenAI Codex)**

El núcleo temático del entorno es **BioData AI**, una solución orientada a la biotecnología y el análisis de datos moleculares. 

---

## 🛠️ 2. Arquitectura y Herramientas Utilizadas
* **IDE de Desarrollo:** Cursor
* **Tecnologías Core:** HTML5 Semántico y CSS3 Moderno (Variables globales, Flexbox y CSS Grid).
* **Agentes de IA Evaluados:**
  * **Agente 1:** Claude 3.5 Sonnet (Integrado en Cursor)
  * **Agente 2:** OpenAI Codex (Modelo GPT-4.5 Mini)
---

## 🎯 3. Especificación del Prompt Inicial (Engine Prompt)
El prompt definitivo fue estructurado siguiendo las guías y buenas prácticas oficiales de ingeniería de instrucciones de **Anthropic** y **OpenAI** (asignando rol de Ingeniero Frontend Senior, contexto técnico, restricciones y formato de salida). El prompt exigió de manera estricta los **7 requisitos mínimos de maquetación**
1. **Cabecera** con menú de navegación funcional.
2. **Hero Section** con propuesta de valor y botón de llamada a la acción (*CTA: "Solicitar Demo"*)
3. **Sobre Nosotros** con descripción institucional.
4. **Sección de Servicios** o características principales estructuradas.
5. **Testimonios** o reseñas de clientes reales del sector.
6. **Formulario de contacto** limpio (maquetado visual sin backend)
7. **Pie de página (Footer)** con enlaces a redes sociales.

*Restricción de Evaluación:* Se respetó de forma estricta la consigna de **no modificar el código de forma manual**
permitiendo evaluar la efectividad y autonomía real de cada agente basado en la instrucción inicial

## 2. Prompt Utilizado

```text
Rol: Eres un Ingeniero de Software Frontend Senior experto en UX/UI y maquetación limpia.

Contexto: Necesito crear de forma completamente autónoma una Landing Page para una plataforma de biotecnología llamada "BioData AI". El diseño debe ser moderno, con fondo oscuro profundo, tipografía clara y acentos en verde bioeléctrico o cian para los botones.

Requisitos Técnicos:
1. Usa HTML5 semántico y CSS3 moderno por separado (index.html y styles.css).
2. El diseño debe ser 100% responsivo (mobile-first), adaptándose perfectamente a celulares y computadoras.
3. No utilices texto falso de relleno como "Lorem Ipsum". Todo el contenido debe ser real, profesional y redactado en español.

Estructura Obligatoria de la Landing Page (7 Secciones):
1. Cabecera (Header): Nombre "BioData AI" and menú de navegación con scroll suave.
2. Sección Principal (Hero): Título de impacto sobre IA aplicada a la biotecnología, un subtítulo descriptivo y un botón de acción que diga "Solicitar Demo".
3. Sobre Nosotros: Descripción de cómo la plataforma optimiza investigaciones científicas y procesamiento de datos masivos. Incluye un bloque visual con métricas de impacto (ej. velocidad de procesamiento, precisión).
4. Servicios (Tarjetas): Una cuadrícula con 3 tarjetas informativas tituladas "Procesamiento Genómico Avanzado", "Modelado Predictivo de Células" y "Reportes Analíticos".
5. Testimonios: Dos opiniones breves de investigadores o directores de laboratorios ficticios.
6. Formulario de Contacto: Maquetado visual de un formulario limpio y despejado con campos para Nombre, Correo Institucional y Mensaje. Ningún otro elemento debe superponerse dentro de este contenedor.
7. Pie de Página (Footer): Estructura limpia, equilibrada y completamente alineada. Debe contener de forma organizada: Logo, sección "Síguenos" con redes sociales profesionales (LinkedIn, GitHub, Twitter), menú de navegación horizontal prolijo en una sola línea (aplicando Flexbox en escritorio) y derechos de autor 2026.

Genera el código completo de forma directa, limpio y listo para producción sin requerir intervención posterior.
```


---

## 📸 4. Evidencia Visual y Galería Comparativa

### Interfaz de Acceso (Portada Principal - Hub)
La portada central de la aplicación distribuye las tarjetas de acceso de forma adaptabilidad responsiva según el dispositivo detectado:

<table width="100%">
  <tr>
    <td width="60%" align="center"><b>💻 Vista de Escritorio (1440px)</b></td>
    <td width="40%" align="center"><b>📲 Vista de Celular (390px)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/portadadesk.jpeg" alt="Hub Escritorio" width="100%"></td>
    <td><img src="img/portadamobile.png" alt="Hub Celular" width="100%"></td>
  </tr>
</table>

---

### Comparativa: Agente 1 (Claude 3.5) vs. Agente 2 (Codex)
Evidencia visual del comportamiento autónomo de los bloques de construcción frontend generados por cada herramienta.

#### 🏛️  Cabecera, Hero Section y Llamada a la Acción (CTA)
<table width="100%">
  <tr>
    <td width="50%" align="center"><b>🤖 Agente 1 (Claude 3.5 Sonnet)</b></td>
    <td width="50%" align="center"><b>🤖 Agente 2 (OpenAI Codex)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/agente1_1..png" width="100%"></td>
    <td><img src="img/agente2_1.png" width="100%"></td>
  </tr>
</table>

#### 🧬 Descripción / Sobre Nosotros
<table width="100%">
  <tr>
    <td width="50%" align="center"><b>🤖 Agente 1 (Claude 3.5 Sonnet)</b></td>
    <td width="50%" align="center"><b>🤖 Agente 2 (OpenAI Codex)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/agente1_2.png" width="100%"></td>
    <td><img src="img/agente2_2.png" width="100%"></td>
  </tr>
</table>

#### 📊  Sección de Servicios / Características
<table width="100%">
  <tr>
    <td width="50%" align="center"><b>🤖 Agente 1 (Claude 3.5 Sonnet)</b></td>
    <td width="50%" align="center"><b>🤖 Agente 2 (OpenAI Codex)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/agente1_3.png" width="100%"></td>
    <td><img src="img/agente2_3.png" width="100%"></td>
  </tr>
</table>

#### 👥 Testimonios / Reseñas de Clientes
<table width="100%">
  <tr>
    <td width="50%" align="center"><b>🤖 Agente 1 (Claude 3.5 Sonnet)</b></td>
    <td width="50%" align="center"><b>🤖 Agente 2 (OpenAI Codex)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/agente1_4.png" width="100%"></td>
    <td><img src="img/agente2_4.png" width="100%"></td>
  </tr>
</table>

#### 📩 Formulario de Contacto Visual
<table width="100%">
  <tr>
    <td width="50%" align="center"><b>🤖 Agente 1 (Claude 3.5 Sonnet)</b></td>
    <td width="50%" align="center"><b>🤖 Agente 2 (OpenAI Codex)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/agente1_5.png" width="100%"></td>
    <td><img src="img/agente2_5.png" width="100%"></td>
  </tr>
</table>

#### 🔗 Pie de Página (Footer) y Enlaces  a Redes Sociales
<table width="100%">
  <tr>
    <td width="50%" align="center"><b>🤖 Agente 1 (Claude 3.5 Sonnet)</b></td>
    <td width="50%" align="center"><b>🤖 Agente 2 (OpenAI Codex)</b></td>
  </tr>
  <tr valign="top">
    <td><img src="img/agente1_6.png" width="100%"></td>
    <td><img src="img/agente2_6.png" width="100%"></td>
  </tr>
</table>

---


## 🔗 6. Enlaces de Acceso al Despliegue
* **Link al Repositorio :** https://github.com/HerreraMarcela/PFO-2-Herrera-Marcela
* **Link al Deploy Unificado (Vercel):** https://pfo-2-herrera-marcela.vercel.app/
