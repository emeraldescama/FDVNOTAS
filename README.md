# Panel FDV · Terapias de Marca (Octubre 2026)

Dashboard autocontenido (`index.html`) para el seguimiento de capacitaciones Kahoot, el portafolio de productos por línea y el fichero médico de la Fuerza de Ventas con la nueva estructura promocional de octubre 2026.

- Abrir `index.html` en el navegador. Funciona sin conexión; para leer archivos Excel (.xlsx) de Kahoot necesita internet (librería SheetJS desde cdnjs).
- Pestaña "Cargar notas": acepta reportes de Kahoot y planillas de Moodle, Genially o cualquier Excel/CSV (una columna por evaluación, con conversión de escala a /20).
- Línea "GERENTES DE DISTRITO": lleva todo el portafolio; filtro por región y tortas por región o por línea en el ranking.
- Pestaña "Cronograma": calendario de capacitaciones con períodos de estudio (desde/hasta) y exámenes; se eligen representantes (por línea) y productos de su portafolio. El cronograma se exporta como imagen PNG o se copia como texto (WhatsApp, correo) o tabla (Excel). La imagen necesita internet (html2canvas desde cdnjs).
- Pestaña "Ranking de notas": estudiantes ordenados por promedio acumulado, torta de distribución y notas por evaluación. Filtros por línea, visitador y evaluación.
- Los cambios hechos en este archivo se guardan solo en el navegador donde se abre (localStorage).
- La versión compartida con base de datos en vivo está publicada en https://claude.ai/artifact/22pVMwsTEmSbJE51rPGWc7

Fuentes: `NUEVA ESTRUCTURA FDV PHQ (OCTUBRE 2026).pdf`, `ESTRUCTURA PRIMARY CARE ACT 9 FEB 2026.xlsx`, `RESUMEN NOTAS.xlsx`, `FICHERO MEDICO OCTUBRE 2026.xlsx`.
