# TUTORIAL PARA EL DESARROLLO DE UN CHATBOT CON IBM WATSON

****PROBLEMA:****
<p>¿Como es el modo de creación de un chatbot con  IBM Watson?</p>

****OBJETIVO GENERAL:****
<p>Investigar mediante la abstracción de información sobre los CHATBOT y la realizar  un ejemplo práctico de su utilización mediante la ayuda de IBM WATSON. </p>

****OBJETIVOS ESPECÍFICOS:****
<p><li>Identificar documentos recientes que tengan información acerca del desarrollo y aplicación de un chatbot con IBM Watson, para de esta manera generar un concepto básico del objeto a investigar y las distintas aplicaciones encontradas.</li></p>
<p><li>Comprender los usos y funcionalidades del chatbot, junto con  cada una de sus configuraciones.</li></p>
<p><li>Desarrollar un ejemplo básico en el que se visualice la creación de un asistente virtual, explicando de manera clara y concisa el modo de su creación. </li></p>

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

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img14.png)



****LISTA DE COMPONENTES****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img15.png)

****MAPA DE VARIABLES****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img16.PNG)

****EXPLICACIÓN DE CÓDIGO FUENTE****

<script>
  window.watsonAssistantChatOptions = {
      integrationID: "f024d62e-e24b-49f8-aa25-b9e69ad0cf6c", // The ID of this integration.
      region: "us-south", // The region your integration is hosted in.
      serviceInstanceID: "49a96bb5-d833-46bb-83b6-923b2ae8933e", // The ID of your service instance.
      onLoad: function(instance) { instance.render(); }
    };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
    document.head.appendChild(t);
  });
</script>

****DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img17.PNG)

****APORTACIONES****

****CONCLUSIONES****

****RECOMENDACIONES****

****CRONOGRAMA****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img21.PNG)

****ANEXOS****

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img19.png)

![](https://github.com/mariajosevizuete2/TUTORIAL-PARA-EL-DESARROLLO-DE-UN-CHATBOT/blob/master/IMG/img20.png)
