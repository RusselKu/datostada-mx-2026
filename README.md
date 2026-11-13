# Datostada MX 2026

**Yucatán a través de los Datos**  
12, 13 y 14 de noviembre de 2026 · Universidad Politécnica de Yucatán

Repositorio oficial de datos y entregables de los equipos. Cada equipo investigará una pregunta relevante para Yucatán con datos públicos, analizará evidencia y construirá un dashboard en Tableau para comunicar sus hallazgos.

## Instrucciones

- Consulta los datos en `datos/yucatan-vivo/`, `datos/yucatan-productivo/` y `datos/yucatan-digital/`.
- Conserva los datos comunes sin modificaciones. Trabaja sobre copias dentro de la carpeta de tu equipo.
- Coloca las entregas en la subcarpeta correspondiente de tu equipo dentro de `equipos/`. Modifica únicamente los archivos de tu equipo.
- Usa nombres de carpeta en minúsculas y con guiones, y nombres de archivo claros.
- Incluye los datos utilizados y los archivos necesarios para verificar el análisis. Si reutilizas archivos publicados en otra fase, indica su ruta dentro de la carpeta de tu equipo.
- Comprueba que los archivos estén publicados en GitHub y que puedan descargarse y abrirse antes del plazo. Guardarlos únicamente en tu computadora no constituye una entrega.
- Este es el único README de instrucciones del repositorio.

## Retos y datos

| Reto | Fuentes | Carpeta |
| --- | --- | --- |
| **Yucatán Vivo · El agua que no vemos** | RENAMECA de CONAGUA: monitoreo de calidad del agua subterránea | `datos/yucatan-vivo/` |
| **Yucatán Productivo · El clima también produce** | SIH de CONAGUA: registros climatológicos; DGSIAP: estadísticas agrícolas | `datos/yucatan-productivo/` |
| **Yucatán Digital · Detrás de la pantalla** | MOCIBA del INEGI: microdatos sobre ciberacoso con recorte de Yucatán | `datos/yucatan-digital/` |

Varios equipos pueden elegir el mismo reto. Todos compiten con los mismos criterios. Pueden cambiar de reto hasta entregar el Data Brief; después podrán ajustar la pregunta dentro del reto elegido y explicar los cambios en las siguientes fases.

## Estructura

```text
README.md
datos/
    yucatan-vivo/
    yucatan-productivo/
    yucatan-digital/
equipos/
    sunchos-team/
    bark-d/
    hadoop/
    chiikawa/
    gaferosada/
    sapos-ai/
    los-ternurines/
    chilaqueries/
    r0dr1l0v3rs/
    mlp/
    claudia-y-asociados/
    error-404/
    datostados/
    kiin-data/
```

Cada equipo tiene las siguientes cuatro subcarpetas:

| Subcarpeta | Contenido |
| --- | --- |
| `01-data-brief/` | PDF del planteamiento |
| `02-evidence-board/` | PDF y soporte del análisis |
| `03-dashboard/` | Archivo `.twbx` y PDF de respaldo |
| `04-pitch/` | PDF de diapositivas o nota indicando que no usarán diapositivas |

Los archivos `.gitkeep` permiten conservar las carpetas vacías en Git.

## Entregables y fechas

**Todos los horarios corresponden a la hora local de Yucatán.**

| Fase | Entregable | Requisitos | Fecha límite |
| --- | --- | --- | --- |
| **DEFINE** | Data Brief | PDF de **1 a 2 páginas**: pregunta, objetivo, audiencia, relevancia, unidad de análisis, territorio, periodo, fuentes, variables, plan inicial y límites | **13 de noviembre, 2:00 p.m.** |
| **EXPLORE** | Evidence Board | Reporte visual en PDF de **2 a 3 páginas**: datos utilizados, preparación y calidad, procedimientos, resultados con gráficas o tablas, hallazgo y límites. Añadan archivos que permitan verificar el análisis | **13 de noviembre, 5:00 p.m.** |
| **DESIGN** | Dashboard en Tableau | Archivo empaquetado **`.twbx` con datos incorporados** y **PDF de respaldo**. Una vista principal, visualizaciones conectadas y al menos una interacción útil. Incluyan fuentes, unidades, periodos y límites | **14 de noviembre, 12:00 p.m.** |
| **COMMUNICATE** | Pitch final | Presentación en vivo de **hasta 5 minutos**. Si usan diapositivas, publiquen el PDF antes de su turno; si no, dejen una nota en su carpeta | **14 de noviembre, desde la 1:00 p.m.** |

Las cuatro entregas son obligatorias. No se solicita una Data Story, paper ni informe técnico adicional.

## Publicación y cierre

Para subir archivos desde GitHub, abre la subcarpeta de tu equipo, selecciona **Add file → Upload files**, añade los archivos y confirma con **Commit changes**. Comprueba que aparezcan en la rama principal del repositorio. Si utilizas una rama y un pull request, los cambios deben quedar incorporados a la rama principal antes del cierre.

Puedes sustituir archivos hasta el plazo de cada entrega. Al vencerlo, la organización registrará la versión del repositorio correspondiente, identificada por su **commit**. Esa será la versión recibida.

Los cambios posteriores no sustituyen ni reabren entregas cerradas, aunque se publiquen en otra subcarpeta. Podrán continuar trabajando en las siguientes fases y explicar los ajustes durante la presentación sin modificar los archivos ya cerrados.

No se admiten entregas tardías ni sustituciones. Después del cierre solo se permiten correcciones de permisos o acceso, sin cambios de contenido. Un entregable obligatorio ausente o inaccesible impide competir.

Ante una falla general del canal oficial, la organización comunicará una alternativa y un plazo común para los equipos afectados.

## Presentación final

Cada equipo tendrá **hasta 5 minutos de exposición**, sin bloque de preguntas. Debe exponer al menos una persona del equipo. La organización indicará el orden de participación.

Expliquen:

- Qué investigaron y por qué importa.
- Qué datos utilizaron y cómo los analizaron.
- Qué encontraron y qué evidencia lo sustenta.
- Cómo funciona el dashboard y para quién resulta útil.
- Cuáles son los límites de sus conclusiones.

Las diapositivas son opcionales.

## Evaluación

Las entregas documentan el proceso y **no reciben calificaciones por separado**. El jurado evalúa lo demostrado en la presentación final.

| Criterio | Qué deben demostrar | Máximo |
| --- | --- | --- |
| **Planteamiento y delimitación** | Pregunta clara, pertinencia, audiencia, alcance y viabilidad | 5 puntos |
| **Sustento y evidencia** | Fuentes, preparación, procedimientos, evidencia verificable y límites | 5 puntos |
| **Diseño y utilidad del dashboard** | Claridad visual, contexto e interacción pertinente para su audiencia | 5 puntos |
| **Comunicación y defensa** | Argumento coherente, conclusiones sustentadas y decisiones justificadas | 5 puntos |
| **Total** | | **20 puntos** |

Cada juez asigna de **1 a 5 puntos por criterio**. Se promedian las tres notas de cada criterio y se suman los cuatro promedios.

En caso de empate sin redondear, se compara **Sustento y evidencia**. Si persiste, el jurado delibera con la misma rúbrica sobre lo demostrado en vivo.

Un análisis descriptivo bien sustentado puede obtener la máxima calificación. No hay puntos extra por cantidad de código, complejidad técnica o uso de IA.

## Herramientas e integridad

Pueden utilizar Python, R, Excel, SQL u otras herramientas para el análisis. **El dashboard debe construirse en Tableau.**

La IA puede apoyar el trabajo: verifiquen sus resultados y declaren las herramientas utilizadas y las tareas realizadas en el entregable correspondiente. No se solicita un registro de prompts.

Atribuyan fuentes, plantillas y materiales de terceros. No se admiten proyectos terminados previamente, resultados fabricados, trabajo ajeno ni información personal o confidencial sin autorización.

Distingan resultados observados, interpretaciones e implicaciones. Reconozcan faltantes, sesgos e incertidumbre. No presenten asociaciones como causalidad sin evidencia suficiente. Identifiquen los datos sintéticos y no los utilicen para sustituir la evidencia principal.

## Acceso a Tableau

Durante el datatón deberán utilizar la **versión de prueba de Tableau**. La organización se compromete a proporcionarles licencias en un plazo máximo de **una semana**, que podrán conservar para continuar utilizando la herramienta después del evento.

## Premio

**$3,000 MXN en efectivo para el equipo ganador del primer lugar.** Es el único premio; el equipo decide cómo repartirlo entre sus integrantes.

Cierre y premiación: **14 de noviembre, 4:00 p.m.**, en el Encuentro de Comunidades.

[Página del evento](https://luma.com/k7bbttlz)