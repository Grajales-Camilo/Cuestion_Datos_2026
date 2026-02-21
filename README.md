# Cuestión De Datos: 

Plataforma web para traducir datos públicos en análisis comprensibles sobre política pública social en Colombia.

Cuestión de Datos es periodismo de datos + ciencia política + analítica aplicada, priorizando claridad de alcance y base documental antes de escalar a una solución completa.

## Propósito del proyecto

- Convertir datos abiertos en hallazgos accionables para discusión pública.
- Facilitar diagnóstico territorial/temático con visualizaciones claras.
- Apoyar formulación y monitoreo de políticas sociales con enfoque basado en evidencia.
- Mejorar alfabetización de datos para ciudadanía, periodismo, academia y sector público.

## Alcance actual (MVP)

- Estructura inicial de sitio con `index.html` y `css/styles.css`.
- Documentación base de alcance, diseño y stack en `docs/`.
- Definición de lineamientos para evolucionar hacia módulos tipo:
	- Home / Newsroom
	- Laboratorio político-electoral (CIVITAS)
	- Recursos y guías
	- Matemáticas en Política: Uso de metodologías para análisis de datos abiertos
	- República Digital: Casos de uso de datos en el contexto digital del país

## Estructura del proyecto

- `index.html`: punto de entrada del MVP web.
- `css/styles.css`: estilos base.
- `assets/`: recursos estáticos del front.
- `docs/design_system.md`: lineamientos visuales y componentes.
- `docs/project_scope.md`: objetivo, usuarios, funcionalidades y métricas del MVP.
- `docs/tech_stack.md`: decisiones tecnológicas y plan de calidad.

## ¿Hacia dónde quieremos ir?

1. Construir landing informativa con narrativa de datos.
2. Incorporar primera visualización con dataset público en CSV/JSON.
3. Definir componentes reutilizables (tarjetas, filtros, tablas, gráficos).
4. Añadir capa de datos versionados para comparar indicadores en el tiempo.
5. Hacer primeros pilotos del uso de API públicas (como Socrata) para visualización y análisis de datos públicos. 
5. Evaluar migración a framework (p. ej. Next.js) cuando el MVP valide uso.

## Criterio de éxito inicial

El proyecto se considera útil en su primera iteración cuando una persona usuaria puede:

- entrar al sitio,
- entender el problema público abordado,
- explorar al menos una visualización,
- y extraer una conclusión accionable en menos de 5 minutos.

