# cursoIA

## Chat GPT
### Enlace a ChatGPT PowerIA
https://chatgpt.com/g/g-oemNGMVnI-poweria-ia-tracker


### Code interpreter
ChatGPT puede generar gráficas a partir de datos proporcionados por los usuarios.

Esto se hace mediante la codificación en Python, utilizando librerías como Matplotlib para crear visualizaciones de datos como gráficos de barras, líneas, histogramas, etc.

Esta funcionalidad es invaluable para análisis de datos, presentaciones de negocios, o simplemente para visualizar información de manera clara y comprensible.



## Make
https://www.make.com/en
Es una herramienta avanzada de automatización que permite a los usuarios conectar aplicaciones y servicios sin necesidad de escribir código.

Con Make, es posible crear flujos de trabajo automatizados llamados "scenarios" que pueden realizar tareas automáticamente, transfiriendo y transformando información entre diferentes aplicaciones y servicios web.

Se utiliza para una amplia variedad de propósitos, incluyendo la automatización de procesos empresariales, la integración de sistemas, la automatización de tareas de marketing, la gestión de redes sociales, la automatización de procesos de ventas, y mucho más. Por ejemplo, un usuario podría configurar un "scenario" para que cada vez que reciba un nuevo correo electrónico en Gmail con un archivo adjunto, Make lo guarde automáticamente en una carpeta específica de Dropbox.

### Scenarios
Un scenario está compuesto por módulos. Estos módulos se dividen en triggers y acciones.

#### Trigger
Trigger: su función es desencadenar o “avisar” sobre un proceso y ejecutar acciones.

#### Acción
Acción: la funcionalidad per se, el evento a desencadenar o disparar. Puede crear información, editarla, borrarla o consultarla.

### Problemas y errores que puede dar
https://www.make.com/en/help/connections/connecting-to-google-services-using-a-custom-oauth-client

Crear un proyecto en Google Cloud Console
- Inicia sesión en Google Cloud Console usando tus credenciales de Google.
- En el menú superior, haz clic en Seleccionar un proyecto > PROYECTO NUEVO.
- Ingresa un nombre de proyecto y selecciona la ubicación para tu proyecto (el que viene por defecto vale).
- Haz clic en Crear.
- En el menú superior, verifica si tu nuevo proyecto está seleccionado en el desplegable Seleccionar un proyecto. Si no es así, selecciona el proyecto que acabas de crear.

Pulsamos en API's y Servicios:
Entramos en el panel de Biblioteca a la izquierda
Y buscamos Gmail en la barra superior.
Y le damos a HABILITAR
Una vez lo tengamos iremos a la Pantalla de consentimiento en la barra de la izquierda nuevamente
Y donde vemos User Type tenemos que selecionar External para que pueda conectarse Make a través de nuestra cuenta.
Haz clic en Crear.
Rellena los campos requeridos con tu información.
En la sección Dominios autorizados, agrega make.com e integromat.com.
Haz clic en Guardar y continuar.


En la segunda parte de la configuracion entraremos en Permisos:
Clicamos en agregar permisos, buscamos Gmail API y seleccionamos las opciones que vayamos a utilizar en nuestra automatización. Esto se puede seleccionar según nuestras necesidades.
También podemos modificarlo posteriormente.

En la siguiente pestaña en Usuarios de Prueba añadiremos nuestro correo electrónico:
Guardamos y veremos un resumen de toda la configuración
Para terminar, entraremos en Credenciales a la izquierda:
Pulsamos en CREAR CREDENCIALES y seleccionaremos ID de cliente de 0Auth.
En tipo de aplicación elegiremos Aplicación Web, pondremos un nombre indicativo como "Make" y en la parte inferior donde indica las URL de redireccionamiento autorizados podremos insertar las siguientes direcciones provistas por Make.
Una vez tengamos creada la configuración veremos esta ventana y guardaremos el ID de cliente y Secreto de cliente para utilizarlo en Make.
Si volvemos a Make y pulsamos en Show advanced settings podremos introducir esos dos datos y ya tendremos nuestra cuenta de Gmail conectada.

Podéis seguir estos pasos o la guia oficial de Make si tenéis este mismo problema con cuentas personales de Gmail.

Una vez esté conectado con nuestro correo electrónico será capaz de detectar nuestras carpetas internas de la cuenta donde organizamos el correo entrante. En este caso tendremos que seleccionar qué carpeta va a vigilar para su detección.

Si seleccionamos /INBOX detectará todos los correos entrantes de nuestra cuenta.

En el apartado Criteria tendremos que seleccionar el criterio por el cuál el trigger se disparará y nos avisará. Ya puede ser Todo, Emails no leídos o Emails leídos.

Para esta prueba seleccionaremos All emails.

En las opciones a continuación también nos proporciona las opciones de elegir un emisor concreto, un receptor, un asunto, una frase interna, si queremos marcar como leído cuando el trigger recupere nuestro correo y el número máximo de resultados por petición.

Vamos a indicarle en el apartado Phrase la palabra “prueba” para ver si es capaz de detectar solamente los emails con dicho criterio.

Y a continuación seleccionaremos From now on, indicando que empiece el proceso desde ahora.


Elegid siempre las subsecciones si se encuentran y comprobad que en la esquina de cada una de las opciones indique el atributo text, ya que si no será imposible que lo refleje en el documento.

#### Enlaces
https://www.integromat.com/oauth/cb/google-restricted - para Gmail o Google Drive

https://www.integromat.com/oauth/cb/google - para otras aplicaciones de Google

https://www.integromat.com/oauth/cb/google-custom - para Google Text-to-Speech

https://www.integromat.com/oauth/cb/youtube - para YouTube

https://www.integromat.com/oauth/cb/app - para cualquier aplicación creada a través de la Plataforma de Desarrolladores de Make

https://www.integromat.com/oauth/cb/google-cloud-speech - para Google Cloud Speech



## Copilot
https://copilot.microsoft.com/


## Zapier
https://zapier.com/

Zapier es una herramienta de automatización en línea que conecta aplicaciones y servicios como Gmail, Slack, MailChimp y más de 3,000 otras aplicaciones.

Automatización de Respuestas a Emails: Utilizar servicios de IA para analizar y responder automáticamente a correos electrónicos entrantes.

Procesamiento de Lenguaje Natural (NLP): Usar herramientas de NLP para extraer información clave de textos o para automatizar la creación de contenido.

Automatización de Tareas de Marketing: Integrar con plataformas de IA que optimizan campañas de publicidad digital, realizan pruebas A/B automáticas, o generan contenido publicitario basado en el rendimiento pasado.

Gestión de Datos y Análisis Predictivo: Conectar con herramientas que pueden analizar grandes volúmenes de datos para predecir tendencias o comportamientos de clientes, lo que puede ser útil para la toma de decisiones empresariales.

Chatbots e Interfaces Conversacionales: Integrar servicios de IA que permiten la creación y gestión de chatbots para automatizar la atención al cliente o la recopilación de datos a través de interfaces conversacionales.



# Código abierto
## Stable Diffusion
## Flux


# Privados
## Dall-E
https://www.bing.com/images/create

### Fortalezas

1️⃣ Es muy accesible para todos los públicos, incluso de forma gratuita, es fácil de utilizar y genera todo tipo de imágenes de buena calidad. ✅

2️⃣ Fue el primer modelo capaz de introducir texto legible y con sentido en las imágenes. ✅

3️⃣ Es un modelo que es capaz de respetar muy bien prompts relativamente complejos, siendo capaz de introducir en la imagen conceptos complejos en muchas ocasiones. ✅

4️⃣ Es el modelo que tiene más conocimientos sobre cultura popular, lo que permite crear imágenes inspiradas en gran cantidad de personajes con relativa facilidad y fidelidad, siempre que se respeten los derechos de copyright correspondientes.. ✅

### Debilidades

1️⃣ Foto realismo: no es el mejor modelo para conseguir imágenes foto realistas, aunque no hace un mal trabajo en algunas ocasiones. ❌

2️⃣ Relación de aspecto: tiene poca variedad con únicamente 3 opciones disponibles. ❌

3️⃣ Copyright: es más precavido que otros modelos en cuanto a posibles violaciones de copyright, lo que limita algunos tipos de imágenes a generar. ❌

4️⃣ Rapidez: los tiempos de generación de imágenes son más lentos que otros modelos. ❌


## Firefly
## Midjourney
## Ideogram