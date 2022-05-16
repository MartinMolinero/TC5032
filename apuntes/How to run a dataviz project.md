# Titulo
- cada proyecto de visualizacion empieza con una necesidad, problema, decision o aclaración.
- Se necesitan:
	- Obtener Datos
	- Elaborar un argumento que use esos datos para explicar, responder o transmitir un punto
	- Desarrollar un argumento
	- Establecer la audiencia.

## Intro
- No hay forma establecida para empezar un proyecto de análisis de datos.
- Ciclo con diferentes etapas:
	1. Entender el problema de negocio
		1. Comprender el alcanza del trabajo, información buscada y tipo de análisis
		2. Definir ants de comenzar el análisis.
		3. Hacer preguntas
	2. Entender los datos
		1. Recopilación inicial de datos
		2. controles de calidad de datos
		3. exploracion de datos
		4. detección de subconjuntos para formar hipótesis
			1. Identificar variables de interés
		5. 
	3. Preparar los datos
		1. Limpiar conjunto de datos, reemplazar valores o duplicados.
		2. Comprensión mayor de la estructura
	4. Análisis exploratorio (modelado)
		1. Probar los datos y buscar respuestas al objetivo
		2. Técnicas para problema de minería, regresiones lineales árboles, bosques
	5. Validación
		1. Crucial evaluar modelo y revisar pasos para construir modelo de datos.
		2. Validar pasos anteriores y la correcta ejecución de los mismos
		3. Identificar problemas, definiciones, reglas de transformación, desafiós de calidad y documentarlos.
	6. Visualización y representación
		1. Presentarse de manera útiil para el cliente
		2. Crucial para comunicar hallazgos
		3. Contar una historia para explicar brevemente.
	7. Documentación
		1. Breve descripción del proyecto
		2. Fuentes de datos
		3. Perfil y calidad de los datos
		4. Limitaciones de los datos
		5. Transformaciones y modelos clave
		6. Impacto o utilidad en mejorar la visualización.

## Requisitos previos del proyecto

### Definición del proyecto
- Necesidad organizacional: dashboard, motor, etc.
- Objetivos medibles concretos dan el marco adecuado para entregar información correcta
- Indicadores clave de rendimiento
	- Recopilar requisitos
	- Establecer procesos de diseño
	- Programar discusiones periódicas con usuarios
	- Continuar reuniones hasta el final de proyecto

- Preguntas:
	- Cuál es la necesidad
	- Principales fuentes de información
	- Datos actualizados o habrá intervalos
	- Tipo de visualización que funciona mejor
	- Objetivo medible a alcanzar
	- KPIs definidos
### Comprender a la audiencia
- Cómo se procesa información y quién la procesa.
- KPIs:
	- Cantidades
	- Tendencias
	- Proporciones
	- Lista
	- Geográfica
### Comprender los datos que trata de visualizar
- Forma, dimensión de datos, relación entre ellos y atributos categóricos
- Se deben combinar si son multifuente?

### Decidir que elemento visual es mejor
- Tablas, lineas, área, barras, scatter, circular, árbol, heatmap de acuerdo a la información que se quiere presentar.

### Elección de la herramienta para el proyecto
- Depende de la persona que realiza la visualización y la plataforma a donde se va a integrar.
- Enfoques:
	- Sin codificación
	- Un poco de codificación
	- Más codificación.

### Interacción del usuario
- Interacción con el proyecto
- Dinamismo con filtros, desglose, etc.
- Experiencia atractiva y adaptación del usuario.
- Herramientas:
	- Filtros y selectores
	- Interacción hover & drill down: Oportunidad de interacción
### Uso efectivo de colores
- Comprender impacto de colores en el gráfico
- Captar atención de las personas, estado de ánimo y percepción.
- PROS:
	- Usar color para representar datos continuos y variar saturación.
	- Usar colores contrastantes para comparaciones
	- Usar colores de la natiraleza
	- Colores de marca para mkt o presentaciones
	- Colores para resaltar información más importante

- Contras:
	- Elegir colores difíciles de distinguir
	- Usar muchos colores

#### Requisitos previos
- Simbolismos: colores simbolicos según la cultura
- Valores emocionales: pequeños más brillantes
- Experiencias históricas: amenaza
- Convenciones sociales de señalización.

## Descripcion general del proceso para visualización
- Involucrar a actores adecuados: partes clave interesadas que usarán la visualización.
- Representantes comerciales son críticos para identificar la necesidad del proyecto.
- Participación aumenta considerablemente la probabilidad de que la visualización cubra las necesidades.

## Planificación de un proyecto de viz
- Fase esencial para garantizar que el producto sea efectivo, facil de entender, dé información y llame a la acción.
- Refuce número de iteraciones
- Cada conjunto de datos tiene sus necesidades propias

### Puntos importantes
1. Demasiada información: No hay que presentar demasiada información, mantener sencilla
2. Recopilación de datos: Datos obtenidos sean de una fuente confiable y que la profundidad establezca creencia en la historia.
3. Cuál es la pregunta: Por qué? Para qué? Qué tienen de interesante, ser conciso con las preguntas, éxito definido por capacidad para captar información,.
	- Etapas de la viz
	1. Adquirir: Obtener los datos de fuente
	2. Analizar: Diseñar estructura para significar y categorizar datos.
	3. Filtrar: Reducir a datos de interés
	4. Minar: Aplicar métodos estadísticos para encontrar patrones.
	5. Representar: Elegir modelo visual básico.
	6. Refinar: Mejorar la representación básica para que sea más clara y atractiva.
	7. Interactuar: Métodos para manipular datos o controlar la visibilidad.

## Búsqueda de información desde la viz
- Descubrimiento de patrones y conocimiento.
- Ideas que cuenten historias por sí mismas.
- Pasos para enconrar un enfoque efectivo:
	1. Visualizar
		1. Visión única del conjunto de datos.
		2. No solo transmite información procesable, también ayuda a ver cosas que otros no puedan ver.
	2. Analizar e interpretar
		1. Qué se puede ver en la imagen?
		2. Era esperado?
		3. Hay algún patrón?
		4. Qué significa esto en el contexto?
	No solo le da signifiicado a la visualización, puede mostrar relevancia de la información.
	3. Documentar conocimiento y pasos
		1. Comenzar antes de dar vistazo a datos
		2. Docimentar pensamientos para identificar idea preconcebida y reducir el riesgo de una mala interpretación de los datos.
	4. Transformar conjuntos de datos
		1. Permite explorar más patrones y hallazgos
		2. Más preguntas al respecto de datos o hallazgos
		3. Favorece análisis adicionales

## Cómo estructurar proyecto de viz
1. Enganchar audiencia con el mensaje clave
	1. Atraer al lector: sorprendent, inusual, controversial.
	2. Cuál es la conclusión más importante?
	3. Argumento principal del proyecto
2. Antecedentes y contexto
	1. Contexo es apreciado cuando se presenta información nueva.
	2. Viz necesario para comprensión como para interpretación adecuada.
	3. Antecedentes: Qué impulsó a usar este tema. Historia detrás de los datos. Camino para comprender objetivo.
	4. Fondo: Creación del proecto de historia en sí y contexto da estado de ánimo.
3. Hallazgos clave
	1. Estructuración de un proyecto de viz se reduce a esto.
	2. Cuál es el mensaje más importante que se quiere presentar a la audiencia.
	3. Representarse visualmente junto al gancho, contexto, antecedentes y flujo
	4. Visualización memorable para la audiencia
		1. Eficientes, puntuales, informativas, de interés y adaptadas.
	5. Destacar atributos más importantes y minimizar basura.
	6. Simple, digerible y adaptado a la audiencia.
	Cómo hacer un gráfico memorable?
 1. Hacer que el título cuente: mayor parte del tiempo en encabezado
 2. Imagen > palabras: minimizar texto, maximizar efectividad de visualizacion
 3. Repetición: Habilita memoria a largo plazo

4. Integración con el negocio
	1. Visualización de big data al frente
		1. Crear interfaces de viz que empleados pueden explorar
	2. Conectar tiempo y espacio
		1. mkt usa ubicación para conocer preferencias, comportamiento o lealtad de consumidores
		2. Mejorar experiencias, predicciones, entregas y enrutamiento.
	3. Visualizar voz del empleado
		1. Análisis de la interacción de los empleados para visualizar impulsores y satisfacción de canales
	4. Visualización de datos en mapas
		1. Representar el contenido de los datos en el habitat donde se desarrolla la información.
5. Conclusiones
	1. Componentes de la conclusión:
		1. Conclusiones: Qué conversación e interacción debe provocar la viz
		2. Evitar mensajes mixtos
		3. Construir una buena historia mediante la organización y presentación
		4. Establecer el contexto
	2. Reflexiones sobre el futuro: puede dar más significado del fenómeno a la audiencia. A dónde creemos que va el tema
	3. Cómo mejorar la presentacion enumerando datos no presentados
	4. Referencias usadas, fuentes, inspiraciones, etc.

## Cómo decidir qué tipo de visualización utilizar.
1. Negocios
	1. Tipos de datos
		1. Producto
		2. Pérdidas y ganancias
		3. Rendimiento
		4. Promociones
		5. Proveedores y clientes
	2. Tipos de visualizaciones comunes
		1. Diagramas de flujo: secuencian proceso paso a paso
		2. Gráficos de control: determinar si datos se encuentran en rango de control
		3. Gráficos bursátiles: Seguimiento de los mercados
		4. Diagramas de gantt: diagramar cronogramas
		5. Gráficos de cascada: afectación positiva/negativa de un valor
		6. Diagrama de jerarquía: orhanigrama
2. Salud
	1. Tipos de datos
		1. Registros médicos
		2. Info seguro
		3. Pruebas
		4. Encuestas
		5. Secuendicación genómica
		6. Publicaciones
	2. visualizaciones comunes
		1. Esperanza de vida
		2. Proporcion de alguna cualidad biométrica
3. Finanzas
	1. Tipos de datos
		1. Precios de acciones
		2. Datos comerciales
		3. Historial tarjetas
		4. Balances
	2. visualizaciones comunes
		1. Graficos de acciones
		2. Dashboard de rendimientos
4. Venta minoritaria
	1. Tipos de datos
		1. Cliente
		2. peidods
		3. Inventario
		4. Almacenamiento de datos
	2. visualizaciones comunes
		1. Dashboard de oportunidades
5. Gestión de proyectos

## Plataformas útiles
- Looker
- Zoho
- tableau
- chartio
- kibana
- plotly
- qlikview
- matlab
- infogram
- d3

- Non devs
	- Excel
	- Sheets
	- Google data studio
	- timeline js
	- plotly
- Complex projects
	- Tableau
	- d3
	- ggplot2
	- networkx
	- matplotlib
	- seaborn
- Interactivity
	- Dygraphs
	- Leaflet
	- ggvis
	- Bokeh
	- Basemap

### Tips
- Escoger graficas que cuenten una historia de acuerdo al mensaje que queires comunicar y audiencia
- Quitar todo lo que no abone a la historia
- Diseñar para la comprensión: qué elementos pueden agregarse, modificarse o cambiarse para hacerse más fácil de entender
- Etiquetar solo lo suficiente
- Checar que todo lo que necesite etiquetas lo tenga
- Etiquetas sean visibles
- Etiquetar los data poitns
- No etiquetar de más
- Considerar quitar etquetas en el eje que no provean de información.


- Pensar  como periodista cuando se planee la visualización de datos

## Puntos de falla en los proyectos
- Ignorar o no definir quienes son los usuarios finales
- Intentar incluir todas las cualidades
- No hacer exploración puede terminar sin patrones
- Preocuparse más por que sea satisfactorio que transmita algo la visalización
- Querer hacer todo clickeable
- Querer imponer tu gusto en colores
- 