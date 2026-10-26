# Panel FDV · Terapias de Marca (Octubre 2026)

Dashboard autocontenido (`index.html`) para el seguimiento de capacitaciones Kahoot, el portafolio de productos por línea y el fichero médico de la Fuerza de Ventas con la nueva estructura promocional de octubre 2026.

- `index.html` es la portada: lleva al panel compartido (guarda en la nube) y explica cómo dar acceso de editor.
- `copia-local.html` es la copia sin conexión: guarda solo en el navegador donde se abre.
- Abrir `copia-local.html` en el navegador. Funciona sin conexión; para leer archivos Excel (.xlsx) de Kahoot necesita internet (librería SheetJS desde cdnjs).
- Inasistencias por evaluación (en "Ranking de notas"): cada evaluación tiene las líneas que deben presentarla (detectadas por producto o por quiénes la presentaron, o definidas a mano); muestra por región o por línea quién no la presentó.
- Fuerzas de ventas: Visita Médica Pharmetique, FDV OTC y FDV La Santé Genéricos (se pueden agregar más). Filtro global por FDV y carga de representantes desde Excel/CSV (lista o estructura por regiones).
- Portafolio: búsqueda de productos por nombre, principio activo u otros nombres, con las líneas que los llevan; edición y cambio de nombre de productos; líneas nuevas por FDV.
- Pestaña "Cargar notas": acepta reportes de Kahoot y planillas de Moodle, Genially o cualquier Excel/CSV (una columna por evaluación, con conversión de escala a /20).
- Línea "GERENTES DE DISTRITO": lleva todo el portafolio; filtro por región y tortas por región o por línea en el ranking.
- Pestaña "Cronograma": calendario de capacitaciones con períodos de estudio (desde/hasta) y exámenes; se eligen representantes (por línea) y productos de su portafolio. El cronograma se exporta como imagen PNG o se copia como texto (WhatsApp, correo) o tabla (Excel). La imagen necesita internet (html2canvas desde cdnjs).
- Pestaña "Ranking de notas": estudiantes ordenados por promedio acumulado, torta de distribución y notas por evaluación. Filtros por línea, visitador y evaluación.
- Los cambios hechos en este archivo se guardan solo en el navegador donde se abre (localStorage).
- La versión compartida con base de datos en vivo está publicada en https://claude.ai/artifact/22pVMwsTEmSbJE51rPGWc7

Fuentes: `NUEVA ESTRUCTURA FDV PHQ (OCTUBRE 2026).pdf`, `ESTRUCTURA PRIMARY CARE ACT 9 FEB 2026.xlsx`, `RESUMEN NOTAS.xlsx`, `FICHERO MEDICO OCTUBRE 2026.xlsx`.
