# Tech Stack

## Frontend
- **Lenguaje principal:** HTML5, CSS3 y JavaScript (ES6+) para MVP.
- **Framework o librería UI:** ninguno en fase inicial (arquitectura liviana y portable).
- **Estrategia de estilos:** CSS modular simple en `css/styles.css`, con convenciones de diseño definidas en `docs/design_system.md`.

### Preguntas orientadoras
- **¿Se usará HTML/CSS/JS puro o framework?** HTML/CSS/JS puro al inicio.
- **¿Qué criterio define esa decisión?** Reducir complejidad y acelerar validación del problema antes de migrar a framework.

## Backend (si aplica)
- **Runtime/plataforma:** no aplica en MVP (sitio estático).
- **Framework backend:** no aplica en MVP.
- **Patrón arquitectónico:** frontend estático orientado a contenido + datos embebidos/archivos.

### Preguntas orientadoras
- **¿La app necesita backend desde el inicio?** No; se puede validar valor con contenido y datasets estáticos.
- **¿Qué endpoints o servicios mínimos son necesarios?** Ninguno obligatorio en fase 1; opcionalmente API de datasets en fase 2.

## Base de datos (si aplica)
- **Tipo de base de datos:** no aplica en MVP.
- **Estrategia de modelado inicial:** uso de archivos CSV/JSON versionados para trazabilidad y reproducibilidad.

### Preguntas orientadoras
- **¿Qué datos deben persistirse?** Metadatos de fuentes, fechas de corte y datasets curados usados en visualizaciones.
- **¿Qué volumen esperado de datos hay en la fase inicial?** Bajo (decenas de KB a pocos MB).

## DevOps y calidad
- **Control de versiones y ramas:** Git con `main` estable + ramas cortas por feature/fix.
- **Linting/formatting:** incorporar en la siguiente iteración (ESLint + Prettier) cuando se agregue JS funcional sostenido.
- **Testing:** validación manual en MVP; pruebas automatizadas a introducir al migrar a framework o añadir lógica de datos compleja.
- **CI/CD:** despliegue manual inicial; automatización posterior con GitHub Actions.

### Preguntas orientadoras
- **¿Qué validaciones automáticas se correrán en cada PR?** En fase 2: lint + build/check + smoke test básico.
- **¿Cómo se desplegará el proyecto en cada entorno?** MVP por hosting estático; evolución a flujos dev/staging/prod al crecer complejidad.

## Dependencias clave
- **Librerías principales (MVP):** ninguna obligatoria en runtime.
- **Criterios para nuevas dependencias:** necesidad funcional clara, mantenimiento activo, tamaño razonable y compatibilidad con objetivos de rendimiento/accesibilidad.

### Preguntas orientadoras
- **¿Qué dependencias son indispensables para empezar?** Ninguna; el MVP debe funcionar solo con navegador moderno.
- **¿Cómo se evaluará el impacto de nuevas librerías?** Revisando costo en bundle, curva de aprendizaje, riesgo de lock-in y beneficio real para usuario final.
