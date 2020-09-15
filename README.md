# TUTORIAL PARA EL DESARROLLO DE UN CHATBOT CON IBM WATSON

****PROBLEMA:****
<p>¿Cómo es el modo de creación de un chatbot con  IBM Watson?</p>

****OBJETIVO GENERAL:****
<p>Investigar mediante la abstracción de información sobre los CHATBOT y la realizar  un ejemplo práctico de su utilización mediante la ayuda de IBM WATSON. </p>

****OBJETIVOS ESPECÍFICOS:****
<p><li>Identificar documentos recientes que tengan información acerca del desarrollo y aplicación de un chatbot con IBM Watson, para de esta manera generar un concepto básico del objeto a investigar y las distintas aplicaciones encontradas.</li></p>
<p><li>Comprender los usos y funcionalidades del chatbot, junto con  cada una de sus configuraciones.</li></p>
<p><li>Desarrollar un ejemplo básico en el que se visualice la creación de un asistente virtual.</li></p>

****ESTADO DEL ARTE****


***IBM Watson Application como asistente de preguntas frecuentes sobre Moodle***
<p>Este trabajo de investigación completo presenta el uso de chatbot en el contexto educativo para la automatización de la atención al estudiante de educación superior. Debido a la evolución de las tecnologías en contextos educativos y profesionales, nueva enseñanza / aprendizaje. Los métodos han sido una demanda emergente para la sociedad actual. La expansión de las modalidades de aprendizaje como el presencial, combinado y aprendizaje a distancia, así como la demanda en cualquier lugar, en cualquier tiempo, ha sido una premisa en estos sistemas educativos. Con el avance de entornos de aprendizaje virtual (VLE), éxito la interacción depende de soluciones que permitan una comunicación eficiente relación entre el alumno y el contexto educativo. Una manera de lograr este objetivo ha sido utilizar chatbots para responder a las preguntas en el campo educativo. Esto se ha hecho posible mediante inteligencia artificial y procesamiento del lenguaje natural encarnado en plataformas de servicios simples. El propósito de este artículo es desarrollar un chatbot que interactúe con los estudiantes a través del texto mensajes, sobre temas en un contexto cerrado, a las dudas de los estudiantes sobre el Curso de Institución de Educación Superior. Validar rendimiento del chatbot, se enviará a una serie de preguntas del mismo contexto que no fueron correctamente respondidas en el interacciones previas. Los resultados de estas interacciones serán analizados con el fin de verificar la eficiencia y contribución de un chatbot como herramienta de apoyo al alumno. Se espera que este estudio contribuye a soluciones para la automatización de la asistencia en el contexto de aprendizaje.</p>
<p>Kennedy Ralston ; Yuhao Chen ; Haruna Isah ; Farhana Zulkernine</p>

<p>2019 18a Conferencia Internacional IEEE sobre Aprendizaje Automático y Aplicaciones (ICMLA)</p>
 
***Implementación de Chatbot para la aplicación ITSM utilizando IBM Watson***
<p>En el escenario actual, la aplicación de gestión de servicios tecnológicos (ITSM) en software de las empresas deben seguir buscando la solución a los problemas que enfrenta o generar finalmente un ticket ya que no puede colaborar con el sistema haciendo preguntas y obteniendo respuestas relevantes. Como solución a esto, nuestro objetivo es diseñar un chatbot que se adaptará específicamente a los empleados de empresas de software. los El chatbot puede procesar la entrada mediante el procesamiento de lenguaje natural (PNL) y puede generar una respuesta relevante que ayude al usuario final para resolver su consulta. El chatbot toma decisiones por sí mismo para responder la consulta del usuario con la ayuda de IBM Watson API de conversación. También recordará el contexto de la conversación y realizar tareas como la creación de un ticket en nombre del usuario.</p>

<p>Neha Atul Godse ; Shaunak Deodhar ; Shubhangi Raut ; Pranjali Jagdale</p>
 
<p>2018 IV Congreso Internacional de Control y Automatización de las Comunicaciones Informáticas (ICCUBEA)</p>
 

****MARCO TEÓRICO****

***IBM WATSON*** 
<p>Watson Assistant es la tecnología de inteligencia artificial conversacional líder en la industria que impulsa los chatbots. Es una plataforma de IA de conversación que proporciona a los usuarios respuestas rápidas, directas y precisas a sus preguntas con un alto nivel de disponibilidad. </p>

<p>Lo que diferencia a Watson Assistant de otros chatbots es que este sabe cuándo buscar una respuesta a partir de una base de conocimientos, cuándo debe pedir claridad y cuándo dirigir a los usuarios a un asistente humano. </p>

 
***VENTAJAS DE IBM WATSON*** 

**Se implementa en cualquier entorno**
<p>Puede ser activado en distintos entornos los cuales serán locales o en la nube, por lo que se encuentra disponible donde se necesite. </p>

<p><li>Cualquier canal.</li></p>
<p><li>Cualquier plataforma de atención al cliente.</li></p>
<p><li>Cualquier contenido.</li></p>
<p><li>Cualquier aplicación.</li></p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img1.png)


<p>Se conecta a los canales que comúnmente usan los clientes (sitio web, teléfono,  canales de mensajería como Facebook, entre otros). </p>

**Modo del chatbot**
<p>Watson permite al usuario elegir de qué modo será el chatbot, este puede ser voz o chat.</p>

<p><li>Chat web: Se puede implementar en minutos, además de incorporar un escalamiento de agentes sin problemas, un estilo personalizable y funciones de seguridad críticas.</li></p>
 
<p><li>Voz: Permite que los clientes hagan sus preguntas en un lenguaje natural, agilizando la respuesta. </li></p>
 
<p>También puede combinar mensajes de texto y voz simultáneamente para un intercambio de información instantáneo.</li></p>
 
**Mejor experiencia para los clientes**
<p>Watson Assistant ofrece a sus clientes una experiencia unificada y atractiva de resolución de problemas, a más de esto se caracteriza por no sacar conclusiones precipitadas. </p>

<p>Proporciona una respuesta eficiente ya que pide una aclaración cuando no se encuentra seguro de la pregunta con la desambiguación, cuando el usuario tiene un problema ambiguo que podría tener múltiples respuestas. También entrega al cliente a un agente humano en caso de ser necesario y es un gran multitarea.</p>

**Cualquiera puede construir**
<p>Si el usuario no sabe cómo codificar, no existe ningún inconveniente, ya que la interfaz de construcción es simple e intuitiva, permitiendo que cualquier persona cree e implemente con éxito un asistente rápidamente.</p>
 
**Acerca de los datos**
<p>El usuario mantiene el control y la propiedad de sus datos, por lo que la empresa se encuentra con un socio seguro y de confianza.</p>
 
<p>Ofrece a los clientes un aislamiento de datos completo. </p>
 
***CREACIÓN DE LA API***

<p>Como primer paso, se necesita crear una cuenta en IBM Cloud, esta brindará acceso a diversos servicios y es gratuita. </p>

<p>El segundo paso es ir al catálogo y seleccionar el servicio Watson assistant.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img2.png)

<p>Al presionar Watson Assistant se abrirá una página, en la cual se puede añadir el nombre del servicio y posteriormente crearlo.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img3.png)

<p>Después de hacer clic en Crear, se abrirá la página del asistente, la cual automáticamente se nombrará como “My first assistant”. Dentro de esta se creará una habilidad, que es donde se configurará el bot para su uso. </p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img4.png)

**Intenciones:**
<p>Se refieren a una acción que está vinculada a las preguntas que hace el usuario, sabiendo que se puede hacer las mismas preguntas de diferentes maneras, es muy complicado saber todas las opciones que se pueden ingresar. Por lo tanto en esta parte se dan ejemplos de frases y posteriormente el sistema hace generalizaciones para identificar otras intenciones comunes.</p>
<p>Es importante saber que el bot tiene intenciones ya creadas, las cuales contienen temas que pueden ser usados en el desarrollo del bot, estas son: </p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img5.png)

<p>Para crear nuestras propias intenciones, nos dirigimos a su sección y presionamos en crear intención. Para esto se requerirá del nombre de esta, con el símbolo #, y a continuación añadir las opciones que se cree que el cliente podría responder.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img6.png)

**Entidades:**
<p>Son conocidas como complementos de información, es decir las características del requerimiento.</p>
<p>Es importante saber que Watson Conversation tiene entidades del sistema listas que no necesitan ser entrenadas. Para habilitarlas dependiendo de la necesidad que tengamos basta con encenderlas.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img7.png)

<p>Para la creación de entidades, nos dirigimos a su respectivo apartado y colocamos en crear, estas se nombran con el símbolo @ en su inicio, y de igual manera se ingresa lo que el cliente podría solicitar, con los respectivos sinónimos o expresiones regulares.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img8.png)

**Diálogo:**

<p>Para este paso el bot se encuentra completado. Posterior a esto se necesita crear las reglas de respuesta y el flujo de la conversación.</p>
<p>Al crear el diálogo, se observa que se muestran dos cajas, la de «Bienvenido» y «En otros casos».</p>
<p>Las dos variables de sistema nombradas se utilizan para la definición del mensaje enviado por el bot en los siguientes casos:</p>
<p><li>El usuario entra en la interfaz.</li></p>
<p><li>El bot no encuentra una respuesta relacionada a lo que el usuario ingresó.</li></p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img9.png)

<p>Se presiona el cuadro de añadir nodo, en el que se colocarán las entidades e intenciones. También se puede añadir un nodo albergado dentro de otro, llamado “child node” . </p>

**Configuración de los nodos**
<p>Para su configuración se abren cada uno de los nodos, donde se puede cambiar el mensaje de retorno y añadir más mensajes que se mostrarán en forma secuencial o aleatoria según escojamos.</p>
<p>A más de esto, se los puede personalizar activando ranuras o múltiples respuestas condicionadas.</p>
<p><li>Ranuras: Se ingresa la entidad, la cual creará una variables de contexto automáticamente con el signo $ en su inicio. Aquí se pondrá el mensaje que queremos que el bot muestre en caso de no encontrar respuesta a lo ingresado por el usuario(se creará un bucle). Lo mejor es que al interactuar con el bot el usuario no necesita enviar las informaciones en un orden específico ya que la ranura analiza variable por variable.</li></p>
<p><li>Múltiples respuestas condicionadas: Con esto se logra colocar diferentes respuestas según lo ingresado por el usuario. </li></p>
<p>Los nodos se encuentran formados por un if then else, por lo que si reconoce una condición responde con esa información, de lo contrario, pasa al nodo siguiente.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img10.png)

<p>Para verificar que el bot funciona correctamente se dirige a la parte derecha superior en el apartado intentar. En esta parte también nos mostrará las intenciones en las que se encuentra la respuesta.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img11.png)

<p>Para visualizar el bot en funcionamiento, se dirigirá a la parte de asistente, seguido de añadir integración.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img12.png)

<p>Con esto se redirigirá a la nueva ventana en la que se eligirá la opción de obtener link.
y listo, podemos ver nuestro chatbot en proceso.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img13.png)

****DIAGRAMAS****

<p>El diagrama del chatbot para pedir una pizza consta inicialmente de un saludo en el que se dirige al cliente mostrando su disponibilidad, posteriormente ingresa al nodo Ordenar_pizza, en el que el usuario ingresa el tipo de pizza que desea. Aquí contenemos tres opciones con sus respectivos sinónimos, los cuales pueden ser @ingredientes:hawaiana, @ingredientes:funghi, @ingredientes:pepperoni. Cada uno de estos contendrá sus respuestas configuradas. En el caso de no encontrar ninguna de estas, se dirigirá al nodo de en otras cosas, el cual imprimirá frases aleatorias, entre las que se encuentra “No le he entendido, intente reformular”. En cambio, en el caso de encontrar la respuesta, preguntará si desea algo más, si la respuesta es no, se dirigirá al nodo Despedida, pero de ser sí, se irá al nodo de Acompañantes. Dentro de este de igual manera se encuentran distintas opciones como son @acompa:ensala, @acompa: bebida, @acompa:salsa, las cuales tendrán respuestas configuradas, si no encuentra la palabra de igual forma irá al nodo de en otras cosas. De ser encontrado, se moverá al nodo de Despedida.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img14.png)



****LISTA DE COMPONENTES****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img15.png)

****MAPA DE VARIABLES****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img16.PNG)

**** ****
****EXPLICACIÓN DE CÓDIGO FUENTE****

<p>Como primer paso, se buscó en el catálogo de contenido la categoría general y se la añadió a la habilidad, con esto se puede tener más variedad de entradas generales, en el caso mostrado, se usarán las intenciones de #General_Greetings y #General_Ending.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img23.PNG)
<p>Después de esto se crea el resto de las intenciones y entidades a ser utilizadas.</p>
<p>Como intenciones creadas se encuentran #acompañantes y #ordenar_pizza y como entidades están @ingredientes y @acompañantes.</p>
<p>Posterior a esto, en el primer nodo “Bienvenido” se coloca la frase con la que se iniciará la conversación.</p>
<p>Bajo el nodo nombrado, se añade el nodo “Saludo”. En esta parte se llamará a la intención #General_Greetings y se colocarán las respuestas del bot.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img24.PNG)
<p>En el siguiente nodo se llamará a la intención #ordenar_pizza y  se activará la rejilla y múltiples respuestas condicionadas. En la rejilla se coloca la entidad @ingredientes, la variable que se crea automáticamente y el texto a mostrar en caso de no encontrar lo ingresado por el cliente. En múltiples respuestas condicionadas, se coloca de igual manera la entidad seguido de cada una de las posibles respuestas escritas por el cliente, y en el cuadro a la derecha de estas se escribe la respuesta para cada condición.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img25.PNG)
<p>En el nodo child nombrado “Acompañantes”, se llama a la intención #acompañantes y se repite el proceso anterior, configurando las múltiples respuestas para la entidad @acompañantes.</p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img26.PNG)
<p>En el nodo “Despedida”, se llama a la intención #General_Ending, para las múltiples respuestas que tendrá el usuario al momento de concluir lo solicitado.</p>
<p>Y por último, se encuentra el nodo “En otras cosas”, este servirá en el caso de que el usuario ingrese una palabra o frase que no se entienda o que no forme parte 
de los ejemplos colocados en las intenciones y entidades. </p>

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img27.PNG)

**** ****
****DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img17.PNG)

****APORTACIONES****

<p>Como aportaciones al trabajo se tiene que se personalizaron los nodos para una mejor experiencia con el chatbot. Con esto se crearon respuestas para cada condición ingresada a más de un bucle para repetir el enunciado en caso de no encontrar la respuesta.</p>
<p>También cada uno de los mensajes del chatbot fue colocado en modo randómico para que cada vez que se desee probarlo aparezcan respuestas distintas.</p>
<p>Como último punto se usó una categoría del contenido general para con esta lograr entender de manera más amplia los distintos saludos y despedidas del usuario y brindar una respuesta.</p>

****CONCLUSIONES****
<p>La plataforma de IBM aporta una facilidad al momento generar un chatbot pues esta es flexible y no necesitas conocimientos de programación para poder mostrar buenos resultados, al ser gratuita cualquier persona natural o jurídica puede incursionar en el ámbito de los chatbots y mejorar su empresa mediante este ingenioso software que mejorará significativamente la atención al usuario. 
Del mismo modo, mediante la abstracción de información se obtuvo el conocimiento para generar un ejemplo práctico acerca de una pequeña empresa centralizada en la venta de comestibles. </p>

****RECOMENDACIONES****
<p><li>Se recomienda tener un conocimiento amplio sobre la empresa y sus requerimientos, para no olvidar detalles al momento de añadir posibles preguntas realizadas por los usuarios.</li></p>
<p><li>Manejar un buen trato con los clientes, respondiendo de manera acertiva y clara para evitar confusiones.</li></p>
<p><li>Realizar varias veces una prueba acerca de cómo funciona el chatbot, ya que posiblemente se esté ignorando algún detalle.</li></p>
<p><li>Colocar correctamente las intenciones y entidades sin confundir los conceptos ya que en esos casos no funcionará.</li></p>


****CRONOGRAMA****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img21.PNG)

****BIBLIOGRAFÍA:****
<p>IBM Corp. Released 2017. IBM SPSS Statistics for Windows, Version 25.0. Armonk, NY: IBM Corp.</p>
<p>Alto, R. (2012). La era de los sistemas cognitivos: una mirada al interior de IBM Watson y cómo funciona. IBM Corporation, Redbooks , 1-16.</p>
<p>Strickland, E. (2019). IBM Watson, cúrate a ti mismo: cómo IBM se comprometió en exceso y no se entregó a la atención médica de IA. Espectro IEEE, 56 (4), 24-31.</p>
<p>Rahman, AM, Al Mamun, A. e Islam, A. (2017, diciembre). Desafíos de programación del chatbot: prospectiva actual y futura. En 2017, IEEE Region 10 Humanitarian Technology Conference (R10-HTC) (págs. 75-78). IEEE.</p>
<p>Cahn, J. (2017). CHATBOT: Arquitectura, diseño y desarrollo. Facultad de Ingeniería y Ciencias Aplicadas de la Universidad de Pensilvania Departamento de Informática y Ciencias de la Información.</p>



****ANEXOS****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img19.png)

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img22.PNG)
