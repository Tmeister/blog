# Headless WordPress - Todo lo que necesitas saber para iniciar.

Desde hace unos años hemos venido escuchando términos como **JAMStack** o sitios **Headless** (sitios sin cabeza) y son términos que se han popularizado mas en esto dias que se refieren a `qué` usamos y `cómo` hacemos sitios web.

Lo primero que debemos entender es que al referirse a **JAMStack** o **sitios headless** estamos hablando de una arquitectura de desarrollo, en este caso, desarrollo web, dicha arquitectura sugiere un conjunto de buenas prácticas enfocadas en obtener un mejor rendimiento, una mayor seguridad, costos bajos y escalabilidad.

## ¿Qué es JAMstack?

El término de JAMStack fue concebido en el año 2015 por Mathias Biilmann, CEO de [Netlify](https://www.netlify.com/) para describir lo ya dicho, una arquitectura de desarrollo web basada en Javascript para el lado del cliente, APIs reusables y Markup.

Como puedes ver hay dos constantes, Javascript y Markup (HTML) pero en ningún momento se habla de frameworks, lenguajes de servidor o tipo de APIs, teniendo esto en cuenta las combinaciones son inmensas, podemos usar, Angular y un API REST creada en .NET, VueJS consumiendo Markdown, ReactJS consumiendo un API GraphQL creada en Laravel (PHP), ReactJS consumiendo el API REST de WordPress, o simplemente Javascript consumiendo archivos JSON.

## ¿Qué es un CMS Headless?

Básicamente, un **CMS Headless** usa la arquitectura **JAMStack** pero con la gran diferencia de que el front-end, back-end y la o las bases de datos son entidades totalmente independientes y todas funcionan sin tener conocimiento una de otra.

Algunos desarrolladores describen esto como `desacoplamiento`, es decir, separar totalmente la capa de presentación (front-end) de la capa lógica y de información (back-end y bases de datos).

Tu front-end y tu CMS ya no están unidos permanentemente pero aún pueden comunicarse entre sí y lo hacen a través de una API.

¿Qué significa esto para los desarrolladores?

**Libertad**

El desarrollador front-end ya no tiene que desarrollar el sitio usando un lenguaje que no conoce bien, o usar motores de plantillas como blade, o mezclar PHP en el HTML.

Si hablamos de WordPress el desarrollador de back-end no tendrá que preocuparse por introducir X o Y ya que mientras se siga entregando la información mediante un API al desarrollador de front-end no le importa nada.

Ahora que tenemos claro los dos conceptos es hora de contestar lo que creo son las preguntas más frecuentes sobre este tema, refiriéndose estrictamente a un headless WordPress o WordPress sin cabeza.

### ¿Qué es un WordPress sin cabeza?

Un WordPress sin cabeza o Headless WordPress es un sitio que utiliza el viejo y confiable administrador de WordPress para manejar todo el contenido del sitio y por otro lado un front-end personalizada para mostrar realmente ese contenido al visitante del sitio.

### ¿Es WordPress sin cabeza mejor que WordPress normal?

Ninguno es mejor o peor que el otro, como todo en el mundo del desarrollo, depende de las características del proyecto.

### ¿Es WordPress sin cabeza más seguro?

Si, una ventaja de tener el front-end desacoplado es que el visitante/atacante no sabe el dominio o subdominio donde esta alojado WordPress y por ello no podrá, por ejemplo, tratar de usar fuerza bruta para atacar el login de WordPress ni tener acceso al administrador.

### ¿Debería usar WordPress sin cabeza?

Un WordPress sin cabeza no es para todos, debes tener en cuenta que necesitas ser desarrollador o deberás contratar a un desarrollador que se encargue de la parte del front-end ya que es un desarrollo personalizado y externo a WordPress, si vas por un WordPress sin cabeza olvídate de plugins, constructores de páginas, opciones de temas, etc.

Por otro lado, si tienes el conocimiento o el presupuesto para migrar tu actual WordPress a un WordPress sin cabeza, la respuesta es sí, sin duda, Al usar un WordPress sin cabeza agregas muchas mejoras y beneficios a tu arquitectura.

### ¿Es WordPress un CMS desacoplado?

No por default, pero con un desarrollo a medida se puede usar WordPress como un CMS desacoplado.

### ¿Cuales son las ventajas de usar WordPress sin cabeza?

- Mejoras en el rendimiento. Al final lo que servimos solo es HTML, CSS y Javascript.
- Mejora la seguridad.
- Podemos tener el back-end en un servidor y el front-end en otro distinto, incluso usar diferentes plataformas.
- Flexibilidad y control para los desarrolladores.
- Es más fácil de construir Aplicaciones web progresiva (PWA).
- Escalabilidad a nivel de front-end.
- Reutilización de componentes web.
- Podemos desarrollar Aplicaciones móviles nativas obteniendo los datos de la misma fuente.
- Ahorro en los costos de hosting.
- Herramientas modernar.

### ¿Cuales son las desventajas de usar WordPress sin cabeza?

- Necesitas conocimientos para desarrollar el front-end
- Necesitas un presupuesto para contratar a un desarrollador de front-end
- Necesitas mantener dos proyectos, el back-end, y el front-end
- Necesitas pagar dos hostings, uno para el back-end y otro para el front-end (el costo del front-end debería ser más barato).
- No puedes usar constructores de páginas, plugins, opciones de temas.

### ¿Quién debería utilizar WordPress sin cabeza?

- Eres parte de una empresa que busca un CMS robusto que soporte la publicación multicanal.
- Eres un desarrollador que quiere experimentar con WordPress y otros lenguajes o frameworks.
- Quieres crear una aplicación y conectarla a un CMS para llenarla de contenido.
- Estás interesado en acelerar tu sitio web y mejorar la seguridad junto con estos otros beneficios.
- Estás familiarizado con WordPress y quieres seguir usándolo, pero estás listo para diversificar con otras tecnologías.

### ¿Quién no debería utilizar WordPress sin cabeza?

- No tienes experiencia en desarrollo web.
- No estas familiarizado con los CMS sin cabeza en absoluto.
- No está preparado para lidiar con la configuración requerida para optimizar la seguridad y el rendimiento.
- Deseas hacer uso de la gran variedad de plugins y temas de WordPress.
- Sólo quieres tener un blog sencillo o un sitio web para una pequeña empresa sin necesidad de publicar en varios canales.
- Quieres seguir usando un constructores de páginas.

### ¿Que APIs puedo usar para crear mi WordPress sin cabeza?

WordPress por default incorpora un REST API, pero también existe un plugin gratuito para exponer una API GraphQL.

Ahora ya conoces que es JAMStack y WordPress sin cabeza, además de saber si un WordPress sin cabeza es para ti.

Por cierto este sitio es un WordPress sin cabeza usando [GatsbyJS](https://www.gatsbyjs.com/) y el front-end esta hospedado en [Netlify](https://www.netlify.com/).

Si algo no está claro, tienes alguna pregunta, o estás listo para hacer el cambio de un WordPress tradicional a un WordPress sin cabeza, puedo ayudarte. Solo tienes que escribirme en [Twitter](https://www.netlify.com/) o enviarme un [correo electrónico](https://enriquechavez.co/contact).
