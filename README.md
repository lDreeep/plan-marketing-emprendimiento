# Plan de Marketing para emprendimientos (skill para Claude)

Skill de uso libre que convierte una idea, un emprendimiento, un producto o un **servicio** (impresión 3D, diseño, reparaciones, consultoría, etc.) en un **Plan de Marketing profesional, coherente y justificado**. Pensada para trabajos académicos, proyectos emprendedores, lanzamientos y documentos internos de empresa.

No rellena teoría. Ordena la información real que tenés, detecta lo que falta, te hace preguntas por rondas, te ayuda a tomar decisiones, las justifica y arma un documento final redactado en tercera persona, con lenguaje profesional.

## Qué hace

- Recibe una descarga inicial desordenada y la clasifica en confirmado, decidido, hipótesis, falta validar y falta decidir.
- Hace preguntas por rondas, sin repetir lo que ya contaste.
- Investiga información pública (competencia, precios, sustitutos, tendencias del sector) con tu OK previo, y cita cada fuente con su fecha de consulta.
- Se adapta a servicios: calidad con especificaciones del resultado y del proceso, precio por hora, pieza o proyecto, capacidad, plazos, y las 3P extra (personas, procesos, evidencia física).
- No inventa datos: sin cifras confiables, trabaja de forma cualitativa y lo aclara.
- Cubre investigación, análisis de mercado, segmentación, mercado meta, análisis situacional (FODA, Ansoff, FCB, Porter, BCG, ciclo de vida), estrategia, posicionamiento, identidad de marca, producto, precio, distribución, comunicación y control.
- Cierra con una auditoría de coherencia antes de entregar.

## Estructura

```
plan-marketing-emprendimiento/
├── SKILL.md                         # principios, modos de trabajo y flujo de preguntas
└── references/
    ├── cuestionarios.md             # bancos de preguntas por bloque
    ├── analisis-y-estrategia.md     # mercado, matrices, estrategia, posicionamiento, marca
    ├── marketing-operativo.md       # producto, precio, distribución, comunicación, control
    ├── plan-y-auditoria.md          # estructura del plan, checklist y prompts de activación
    └── servicios-e-investigacion.md # adaptación a servicios y modo de investigación
```

`SKILL.md` es corto y se carga siempre. Los archivos de `references/` se leen solo cuando hacen falta.

## Cómo instalarla en Claude

1. Descargá este repositorio (botón **Code → Download ZIP**) o comprimí la carpeta `plan-marketing-emprendimiento` en un `.zip`. La carpeta de la skill debe quedar en la raíz del zip.
2. En Claude, andá a **Configuración → Capacidades → Skills** y subí el zip.
3. Activala y pedile, por ejemplo: *"Quiero armar el plan de marketing de mi emprendimiento"*.

## Cómo usarla

Prompt sugerido para empezar:

> Quiero desarrollar un emprendimiento y construir un Plan de Marketing profesional usando esta skill. Primero haceme una descarga inicial ordenada de toda la información que ya tengo. Después clasificá lo que está confirmado, lo que falta validar y las decisiones pendientes. Haceme preguntas por rondas, sin repetir información que ya te di. No inventes datos.

Para revisar un plan que ya existe, el prompt de revisión está en `plan-marketing-emprendimiento/references/plan-y-auditoria.md`.

## Adaptarla a tu caso

La skill está en español rioplatense y usa terminología de las cátedras de Comercialización (presión, aspiración, estrategia combinada, integración hacia adelante, etc.). Podés editar los archivos para ajustarlos al vocabulario de tu materia, a otro idioma o a otro tipo de proyecto.

## Aviso

Es una herramienta de apoyo. Los datos de mercado, costos y precios tienen que venir de tu información o de fuentes que puedas citar, y las decisiones finales son tuyas.

## Licencia

MIT. Ver [LICENSE](LICENSE). Podés usarla, copiarla y modificarla libremente.
