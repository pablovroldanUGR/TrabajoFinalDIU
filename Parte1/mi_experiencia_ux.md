# Mi experiencia UX - Pablo de la Torre Roldán
Durante el curso de Diseño de Interfaces de Usuario he desarrollado una comprensión profunda de los principios fundamentales del área UI/UX. Gracias a las seis actividades propuestas en teoría he tenido la oportunidad de poner en práctica herramientas y metodologías que deben utilizarse en el trabajo real de un diseñador o programador de interfaces. Aquí está la descripción de cada una de estas actividades, enfocando en mis aportaciones concretas y conclusiones que saqué de ellas.

## Actividad 1 - Etnografía:
La primera actividad consistió en adoptar la perspectiva de un observador externo (el personaje GURB) para identificar situaciones reales de conflicto entre personas y sistemas informáticos. Mi observación se centró en una mujer mayor intentando validar su tarjeta de autobús al subir al mismo.
 
El conflicto observado fue el siguiente: la tarjeta no era leída de forma instantánea por el lector del autobús, pero la usuaria no recibía ningún feedback claro de si la operación había tenido éxito o no. Al no recibir confirmación visual o sonora inmediata, la persona repitió el gesto varias veces de forma insegura, bloqueando la entrada, generando una cola y haciendo que el vehículo quedara mal estacionado en la carretera, provocando un atasco.
 
La conclusión más relevante fue que el problema no era el usuario, sino el diseño del sistema de feedback. La ausencia de un indicador claro genera una sobrecarga innecesaria de la Memoria de Trabajo (STM): el usuario no puede retener simultáneamente si la acción tuvo efecto mientras gestiona el entorno (la cola, el conductor, el movimiento del autobús). Según el modelo estudiado en clase, la Memoria de Trabajo tiene una capacidad muy limitada de 7 ± 2 ítems y una decaída rápida. Cuando el diseño no proporciona feedback inmediato, el usuario consume esa capacidad tratando de descubrir el estado del sistema en lugar de avanzar en su tarea. 
 
Esta actividad me enseñó a observar sin juzgar al usuario y a cuestionar el diseño como primera hipótesis ante cualquier dificultad de interacción. La mirada etnográfica reveló información que un test de usabilidad no siempre captaría.

## Actividad 2 - Moodboard:
En esta actividad trabajamos en grupo para crear un moodboard para un proyecto de marca ficticia. El resultado fue Rocket Nation, una tienda especializada en explosivos de alta tecnología y artillería táctica, un concepto deliberadamente provocador que nos permitió explorar un lenguaje visual extremo y coherente.
 
Mi aportación se centró en la definición del sistema visual y del UX Writing. En cuanto a la paleta de color, optamos por naranja y amarillo sobre fondo negro, una combinación que transmite peligro, alerta y adrenalina. Esta decisión responde a principios de psicología del color aplicados al diseño de interfaces: el contraste y la saturación generan una respuesta emocional en el usuario que hace que la marca sea identificable antes de que el usuario haya procesado conscientemente ningún texto. La codificación visual por color es uno de los mecanismos que el sistema cognitivo aprovecha a nivel de memoria sensorial para discriminar estímulos con muy poco esfuerzo atencional.
 
Para la tipografía seleccionamos Black Ops One como fuente principal (moderna, de gran peso visual y con connotaciones militares) complementada por Space Grotesk para los textos de cuerpo. Esta combinación ilustra el principio de jerarquía tipográfica: la fuente principal captura la atención y activa el reconocimiento inmediato, mientras que la fuente de cuerpo facilita la lectura sostenida apoyándose en la memoria a largo plazo (LTM) donde el usuario ya tiene consolidados los patrones de lectura de fuentes sans-serif estándar.
 
El eslogan "Problemas grandes requieren soluciones explosivas" es un ejemplo de UX Writing orientado a la emoción: utiliza el concepto de destrucción para generar al usuario una sensación de confianza y conectar con él. Adicionalmente, definimos tres perfiles de usuario objetivo con sus motivaciones y frustraciones, introduciendo la dimensión de diseño centrado en el usuario.
 
El moodboard ha sido una experiencia valiosa para entender cómo todas las decisiones visuales deben responder a un sistema coherente y a un usuario concreto, no a preferencias estéticas personales.

## Actividad 3 - Eye tracking:
Esta actividad introdujo una técnica de investigación UX más avanzada: el eye tracking, implementado mediante la herramienta Gazemapping. En grupo analizamos el comportamiento visual de nosotros mismos como usuarios sobre las páginas web de tres cadenas de comida rápida: McDonald's, Burger King y Smash Hiro.
 
Definimos los siguientes POIs: logos, llamados a la acción (CTA) (encontrar la carta, ver los locales disponibles en nuestra zona…) y redes sociales y contacto. A partir de los heatmaps generados observamos patrones claros: los usuarios fijaban la vista en imágenes de producto y CTAs bien diferenciados, mientras que elementos secundarios pasaban prácticamente desapercibidos si no estaban situados en zonas de alta atención visual.
 
La conclusión más relevante conecta directamente con el Modelo de Procesador Humano estudiado en clase: la memoria sensorial capta los estímulos visuales de forma masiva pero solo los que superan el umbral de atención acceden a la Memoria de Trabajo (STM). El diseño visual determina qué información pasa ese filtro antes de que el usuario tome ninguna decisión consciente. Esto refuerza la importancia del layout y los principios de percepción visual (agrupación, contraste, figura-fondo) en el diseño UI: no basta con incluir la información, hay que situarla donde el ojo tiende a ir naturalmente. 

## Actividad 4 - Usabilidad con Heurio:
En esta actividad aplicamos una evaluación real sobre la página web de la Universidad de Murcia, utilizando Heurio como extensión de Chrome. El objetivo era identificar, clasificar y justificar problemas de usabilidad reales.
 
El hallazgo más llamativo fue la presencia de más de 30 elementos desplegables en la barra de navegación principal. Este diseño viola la heurística de Nielsen de reconocimiento antes que recuerdo y supone una sobrecarga crítica de la memoria de trabajo: con tantas opciones disponibles simultáneamente, el usuario no puede mantenerlas activas en la memoria a corto plazo y se ve obligado a explorar repetidamente la navegación para localizar lo que busca, en lugar de reconocerlo directamente. Este fenómeno conecta con la Ley de Hick, según la cual el tiempo de decisión crece logarítmicamente con el número de opciones disponibles.
 
También detectamos problemas de consistencia entre secciones: distintas páginas dentro del mismo sitio usaban convenciones visuales diferentes, lo que desorientaba al usuario y rompía los modelos mentales que había construido al navegar las primeras páginas. Este hallazgo se relaciona con el principio de consistencia visto en el tema 1: cuando el diseño es inconsistente, el usuario no puede transferir lo aprendido de una sección a otra.
 
El uso de Heurio fue especialmente útil porque permite anclar los problemas directamente sobre el elemento visual de la página, facilitando la comunicación de los hallazgos. Esta actividad me proporcionó experiencia directa en la evaluación experta de interfaces, un método fundamental en la práctica profesional de UX cuando no es posible realizar pruebas con usuarios reales.

## Actividad 5 - Accesibilidad:
Esta actividad abordó un concepto esencial del diseño de interfaces que muchas veces se ignora: la accesibilidad. Evaluamos la web del Ayuntamiento de Granada desde dos perspectivas: la inspección técnica con herramientas automáticas y la simulación de discapacidades mediante Funkify.
 
Utilizamos WAVE para detectar errores WCAG, WebAIM Contrast Checker para evaluar el contraste y las herramientas de desarrollador del navegador para analizar el layout sin CSS. Los resultados fueron preocupantes: la web presentaba una dependencia total de los estilos visuales, de modo que sin CSS la estructura del contenido era prácticamente ilegible. Además, el único enlace de accesibilidad encontrado era un formulario de solicitudes, sin ninguna declaración de conformidad WCAG ni indicación real de qué criterios se cumplían.
 
Luego probamos la web activando distintos perfiles de discapacidad visual y motórica. La experiencia fue reveladora: con visión borrosa o baja resolución, la organización compacta de la información hacía imposible localizar contenidos básicos. Esto es un problema muy grave, ya que si la información no llega con suficiente claridad al usuario, nunca alcanza la memoria de trabajo y el usuario queda excluido del sistema por completo.
 
La valoración del grupo fue que la web requeriría una refactorización completa para alcanzar un nivel de accesibilidad aceptable. Esta conclusión pone de relieve una brecha real entre las obligaciones legales de accesibilidad de las instituciones públicas y su cumplimiento efectivo. Incorporar los principios POUR (Perceptible, Operable, Comprensible, Robusto) desde las primeras fases del diseño es mucho más eficiente que corregir los problemas a posteriori.

## Actividad 6 - Portfolio Neo Brutalista:
La última actividad fue crear un portfolio personal con estilo Neo Brutalism, aplicando de forma simultánea los conocimientos adquiridos sobre identidad visual, jerarquía, tipografía, componentes interactivos y experiencia de usuario.
 
En el desarrollo del portfolio tomé decisiones de diseño concretas y justificadas. La estructura se organizó en secciones bien definidas siguiendo un flujo narrativo pensado para que el visitante comprendiera el contenido sin necesidad de leerlo todo, apoyándose en el reconocimiento visual más que en el recuerdo (reduciendo así la dependencia de la memoria a corto plazo). Los botones incorporan estados de hover y press aplicando los principios de microinteracción: el feedback visual inmediato ante la acción del usuario reduce la incertidumbre y refuerza la sensación de control, lo que conecta con la heurística de visibilidad del estado del sistema ya trabajada desde la primera actividad.
 
La elección del estilo también implicó trabajar con design tokens: reglas fijas de espaciado, tipografía y color que garantizan la coherencia visual a lo largo de todo el portfolio, evitando la inconsistencia que detectamos como problema grave en la actividad de usabilidad (Actividad 4). Sin embargo, aunque en el estilo neobrutalista predomine el negro sobre blanco, intenté innovar e hice el estilo de la página en modo oscuro.

## Trabajo de prácticas:
Para el trabajo de prácticas desarrollamos un gastrobar tematizado en el anime Doraemon llamado Dorayakiya, donde la atracción principal es un servicio de robots camareros. A lo largo de cinco fases iterativas, creé junto a mi compañero de prácticas soluciones que transformaron una idea puramente recreativa en un producto digital usable.
### Fase 1 - User Research, Modelado de Personas y Diagnóstico Competitivo:
Nuestra primera aportación fue definir un User Research Plan para mapear el ecosistema de usuarios. Esta fase consistió en el análisis comparativo de la competencia, donde evaluamos la web de Anime Ramen, detectando un problema de diseño: tenía una buena estética y funcionalidad que, sin embargo, fracasaba al sobreestimular al usuario con elementos redundantes.

Para corregir esto en nuestro proyecto, diseñamos dos usuarios con modelos mentales diametralmente opuestos:
  - Un usuario joven, nativo digital e introvertido, que no quería salir de casa.
  - Un padre de familia de 55 años, divorciado, con baja competencia digital, cuyo único objetivo era llevar a sus hijos al local, sufriendo una enorme fricción al intentar interactuar con interfaces complejas.

El diseño de los usuarios me permitió hacer un ejercicio de empatía hacia los posibles usuarios futuros del sistema y mejorar así el diseño de la web para hacerlo más universal.

### Fase 2 - Arquitectura de la Información, Ideación y Wireframing:
En la fase de ideación empleamos herramientas como el ScopeCanvas y el Feedback Capture Grid. Identificamos el principal riesgo de negocio y UX: que el restaurante fuese percibido como una atracción de una sola visita debido a la novedad de los robots.

Diseñé el Task Analysis enfocado en mitigar este riesgo, estructurando el Sitemap y el Labelling bajo la premisa de la eficiencia cognitiva (minimización de clics). Definí una barra de navegación principal con las tareas ("Pedir Online", "Carta", "Reseñas" y "Reserva"). Luego pasé al diseño en Figma, partiendo de un diseño de tres zonas claras (Header, Main, Footer), asegurando que la navegación fuese intuitiva incluso para nuestro perfil de usuario de baja competencia digital.

### Fase 3 - UI Design, Pautas de Accesibilidad y Diseño Atómico:
En la transición del wireframe a la implementación, tuvimos en cuenta ciertos aspectos para mantener la calidad de la accesibilidad y consistencia:
  - Descartamos el blanco y negro puro, que causan fatiga ocular por exceso de contraste. En su lugar, aporté la solución de sustituirlos por tonos suavizados (#FAFAFA y #181818). La paleta se construyó sobre una armonía monocromática azul (identidad de Doraemon) matizada con amarillo de alto contraste exclusivo para los llamados a la acción (CTA).
  - Tipografía: Seleccionamos Fredoka One (juguetona y de gran peso visual) para titulares y Baloo 2 para texto corrido, garantizando que la lectura fuese fluida para personas mayores o niños.
  - Se hizo uso del atomic design para permitir mantener la consistencia de la página de una forma sencilla, reutilizando componentes.

### Fase 4 - A/B testing:
En esta fase comparamos nuestro proyecto con el de otro grupo del grupo 3 de prácticas. Sometimos a ambos sistemas a un test SUS y pusimos en práctica el Gazemapping en un contexto real (algo que ya vimos por encima en la actividad 3 de teoría). Nos dimos cuenta que gracias a todas las buenas prácticas que fuimos llevando a cabo a lo largo de nuestro trabajo de prácticas tuvimos un buen resultado, afirmando la correcta ejecución del proyecto.
