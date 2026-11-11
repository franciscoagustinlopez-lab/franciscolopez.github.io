# Bitácora de Inteligencia Artificial

## Consulta 1
- **Fecha:** 11/11/2026
- **Herramienta utilizada:** ChatGPT / Claude
- **Objetivo:** Generar una estructura CSS con variables de color y tarjetas adaptables para el portfolio.
- **Prompt completo:** 
  > "Mi portfolio tiene estilo limpio y profesional, usa colores principales en azul (#17365d) y azul secundario (#2f75b5) y debe transmitir responsabilidad y claridad. Creá un CSS inicial con variables de color, tipografía legible, espaciados y tarjetas. Usá CSS puro, sin frameworks ni animaciones complejas. Explicá cada bloque."
- **Parte utilizada:** Las variables `:root`, las reglas de reset básico `* { box-sizing: border-box; }` y la cuadrícula CSS Grid para `.contenedor-tarjetas`.
- **Cambios realizados por mí:** Ajusté los márgenes internos (`padding`) de las tarjetas y agregué la pseudoclase `:hover` para un cambio visual leve.
- **¿Qué comprendí?** Comprendí la función de las variables de CSS en `:root` para cambiar la paleta global rápidamente y cómo `grid-template-columns` distribuye las tarjetas automáticamente.
- **¿Qué descarté y por qué?** Descarté animaciones pesadas de entrada y fuentes de Google Fonts externas para mantener la carga rápida y no depender de servicios de terceros en la versión inicial.

---

## Consulta 2
- **Fecha:** 11/11/2026
- **Herramienta utilizada:** ChatGPT / Claude
- **Objetivo:** Revisar la accesibilidad y semántica de la estructura HTML.
- **Prompt completo:**
  > "Revisá este fragmento considerando orden de títulos, alt de imágenes, enlaces descriptivos, contraste y navegación con teclado. Presentá problema, importancia y corrección. [FRAGMENTO DE MI HTML]"
- **Parte utilizada:** Los textos de los atributos `alt` en las imágenes de los proyectos y las propiedades de accesibilidad en los enlaces externos (`rel="noopener"`).
- **Cambios realizados por mí:** Redacté las descripciones de las imágenes con información específica del proyecto en lugar de poner textos genéricos como "foto1".
- **¿Qué comprendí?** La importancia de la jerarquía temática (`h1`, `h2`, `h3`) y el rol del texto alternativo `alt` para la lectura por lectores de pantalla.
- **¿Qué descarté y por qué?** Descarté código JavaScript complejo para un menú desplegable accesible ya que en esta fase 0.1 se prioriza HTML/CSS nativo y simple.