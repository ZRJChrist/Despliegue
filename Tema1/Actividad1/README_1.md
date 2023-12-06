# Actividad 1 - Entorno de desarrollo software

## Aplicación de tres niveles en el desarrollo web

- El **servido web**  es el nivel de presentación y proporciona la interfaz de usuario. Este suele ser una página o sitio web, como un sitio de comercio electrónico en el que el usuario añade productos al carrito de compras, añade datos de pago o crea una cuenta. El contenido puede ser estático o dinámico y se suele desarrollar utilizando HTML, CSS y Javascript.

- El **servidor de aplicación**  corresponde al nivel medio, que aloja la lógica empresarial utilizada para procesar las entradas de usuario. Continuando con el ejemplo del comercio electrónico, este es el nivel que consulta la base de datos de inventario para informar la disponibilidad del producto o añadir detalles al perfil de un cliente. Esta capa a menudo se desarrolla utilizando Python, Ruby o PHP y se ejecuta en una infraestructura como Django, Rails, Symphony o ASP.NET.

- El **servidor de base de datos**  es el nivel de datos o backend de una aplicación web. Se ejecuta en un software de gestión de base de datos como MySQL, Oracle, DB2 o PostgreSQL.

## LAMP y WISA

- La plataforma **LAMP** trabaja enteramente con componentes de software libre y no están sujetas a restricciones propietarias. El nombre LAMP surge de las iniciales de los componentes de software que la integran: Linux (sistema operativo), Apache (servidor web), MySQL (manejador de bases de datos) y PHP (lenguaje interpretado, aunque a veces se sustituye por Perl o Python)

- La plataforma **WISA** por su lado está basada en tecnologías desarrolladas por la compañía Microsoft. Sus componentes son Windows (sistema operativo), Internet Information Services (servidor web), SQL Server (manejador de bases de datos) y ASP (no es un lenguaje interpretado per se, sino que sirve como un medio para trabajar con otro que sí lo es, como Visual Basic, bajo un entorno web).

-  **LAMP**, por funcionar bajo un esquema de código abierto, es de bajo costo. Es una plataforma bastante rápida y ofrece buen rendimiento sobre todo a aplicaciones web que no sean demasiado grandes o que tenga excesiva actividad. Además existe para ella una amplia gama de aplicaciones, perfectamente adaptable a las necesidades de pequeñas y medianas empresas o de aquellas que se encuentren en los primeros estadios de la gestión de información, que incluyen blogs, manejadores de contenidos, aplicaciones para trabajo en grupo, entre otras. Algunas de estas aplicaciones son pagas pero la mayoría son gratuitas.
**WISA**, es más costosa y provee mayor nivel de soporte. En general es más robusta si se tiene en mente aplicaciones web que funcionen en una intranet o que tengan un gran nivel de actividad (varios miles de transacciones electrónicas al día, por ejemplo). También existe abundancia de aplicaciones web desarrolladas por terceros, aunque la mayoría de ellas son pagas.