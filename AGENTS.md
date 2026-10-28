# Instrucciones para cualquier agente en Zero Blog

## Antes de trabajar
1. Leer INDEX.md y skills/zero-blog/SKILL.md. Para tareas pequeñas, abrir solo los documentos que correspondan según INDEX.
2. Leer docs/VOICE.md, docs/PEDAGOGY.md o docs/RESEARCH.md según la operación.
3. Si se trabaja un tema, revisar topics/<tema>/INDEX.md y su ficha de artículo. Consultar el Core y documentos originales de Drive cuando se necesite contenido detallado o confirmar el estado.
4. Antes de escribir en este repositorio, identificar la conexión de GitHub como **zerojsx**, confirmar permisos y leer el archivo de destino.

## Regla de conocimiento
Conservar tres niveles separados:
- **General**: criterios reutilizables entre temas → docs/ y templates/.
- **Temático**: particularidades de una materia o serie → topics/<tema>/INDEX.md.
- **Artículo**: decisiones, fuentes, límites, aprendizajes y enlaces de una pieza → topics/<tema>/<articulo>.md.
Registrar las decisiones duraderas y aceptadas en memory/DECISIONS.md. Documentar un hito concreto por línea en memory/LOG.md.

Una analogía puntual, una extensión exigida para un único encargo, una hipótesis comercial o una anécdota no se convierten automáticamente en regla general. Promover una regla al nivel general solo si se justifica su transferencia. Al revisar ejemplos, extraer la razón detrás de la elección, no repetir el ejemplo como receta.

## Protocolo autónomo de actualización
**Disparadores**: corrección aceptada del usuario; nueva regla editorial; nuevo tema o artículo; aprobación o cambio del estado de una pieza; fuente verificada relevante; aprendizaje reutilizable de una revisión.
1. Separar hecho / decisión aceptada / hipótesis / ejemplo ficticio.
2. Ubicar el archivo canónico adecuado; editarlo en lugar de duplicarlo. Si cambia una convención, revisar referencias dependientes.
3. Actualizar INDEX.md únicamente si aparece una ruta, categoría o documento nuevo; actualizar el índice temático si cambian títulos, enlaces, estado o relaciones.
4. Registrar en memory/LOG.md una sola línea: fecha | alcance | cambio | referencia. No llenar el log con cada lectura, intento o reformulación.
5. En memory/DECISIONS.md modificar la decisión vigente y dejar indicación de reemplazo si corresponde. Evitar decisiones incompatibles simultáneas.
6. Verificar diff, permisos e identidad; crear commit descriptivo y verificar los archivos afectados en GitHub. Si faltan permisos, informar y entregar patch o texto, sin fingir persistencia.

Las correcciones tentativas, gustos inferidos o datos no corroborados se anotan como pendientes en la ficha correspondiente o se dejan fuera; no reescribir políticas sobre suposiciones. Si una petición concreta contradice la regla general, manda la instrucción explícita actual para esa entrega, y se registra como nueva convención solo si fue aceptada como duradera.

## Límites
- El repositorio organiza conocimiento. No publicar blogs, alterar precios, escribir a clientes ni modificar otros repositorios sin una solicitud específica.
- Nunca almacenar tokens, datos privados de alumnos, clientes ni transcripciones sensibles.
- No fabricar estadísticas, referencias, testimonios ni fechas de publicación.
- No imponer al artículo una estructura de introducción/desarrollo/cierre con cuotas fijas salvo pedido explícito.
- No confundir un dossier de formación con un artículo listo para publicar.
- No afirmar que la automatización de futuras actualizaciones funciona sin un agente con acceso efectivo, autorización y herramientas de escritura.

## Criterio de salida
Indicar qué archivos se actualizaron, la razón, el commit verificado y cualquier fuente o paso pendiente. Evitar un reporte inflado.
