# Design System

## Identidad visual
- **Personalidad de marca:** técnica, pública y cercana.
- **Principios de diseño:** claridad informativa, consistencia visual, accesibilidad desde el inicio y foco en lectura de datos.

### Preguntas orientadoras
- **¿Qué sensación debe transmitir la interfaz?** Rigor analítico con lenguaje comprensible para audiencias no técnicas.
- **¿Qué 3 adjetivos describen el estilo visual?** Sobrio, legible y confiable.

## Colores
- **Color primario:** azul profundo (institucional/confiable).
- **Color secundario:** verde cívico (evidencia/avance social).
- **Colores de estado:**
	- éxito: verde medio,
	- alerta: ámbar,
	- error: rojo,
	- info: azul claro.
- **Colores de fondo y texto:** fondo claro neutro, tarjetas blancas, texto principal gris oscuro para alto contraste.

### Preguntas orientadoras
- **¿Cuál es la paleta base?** Azules + neutros, con verde como acento y semánticos para estado.
- **¿Cómo se manejará el contraste para accesibilidad?** Contraste mínimo AA (texto normal y componentes interactivos), evitando texto claro sobre fondos claros.

## Tipografía
- **Fuente principal:** sans-serif de sistema (fallback segura para MVP).
- **Fuente secundaria:** serif opcional para citas/editoriales en fases posteriores.
- **Escala tipográfica inicial:**
	- h1: 2rem,
	- h2: 1.5rem,
	- h3: 1.25rem,
	- body: 1rem,
	- caption: 0.875rem.

### Preguntas orientadoras
- **¿Qué familias tipográficas se usarán y por qué?** Sans-serif para lectura continua y consistencia en navegadores; se prioriza disponibilidad nativa y rendimiento.
- **¿Cómo se garantiza legibilidad en móvil y desktop?** Tamaño base 16px, interlineado amplio y ancho de línea controlado en desktop.

## Espaciado y layout
- **Sistema de espaciado:** escala de 8px (4, 8, 16, 24, 32, 48, 64).
- **Breakpoints responsive:** móvil (<768px), tablet (768–1023px), desktop (>=1024px).
- **Ancho máximo de contenedor:** 1200px en desktop, con padding horizontal adaptable.

### Preguntas orientadoras
- **¿Cuál será la grilla base?** 12 columnas en desktop y 4 columnas en móvil.
- **¿Qué comportamiento tendrá cada sección en pantallas pequeñas?** Las secciones se apilan verticalmente, con navegación simplificada y prioridad al contenido esencial.

## Componentes y reglas
- **Botones:** variantes primaria, secundaria y texto; estados hover, focus visible, disabled.
- **Inputs y formularios:** labels visibles, mensajes de error claros y validación básica en cliente.
- **Tarjetas, tablas y navegación:** tarjetas para resúmenes, tablas para datos comparables y navegación superior simple (MVP).

### Preguntas orientadoras
- **¿Qué componentes son obligatorios para el MVP?** Header, bloque hero, tarjeta de hallazgo, tabla básica, botón CTA y footer.
- **¿Qué reglas de consistencia deben respetarse siempre?** Jerarquía tipográfica estable, espaciado por escala, estados interactivos visibles y lenguaje claro en UI.
