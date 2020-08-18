# ECOMMERCE_ ENTRAGOS
## Propósito del Proyecto
El presente proyecto tiene como propósito definir las tecnicas y herramientas de desarrollo de software y demás detalles relevantes para el desarrollo de un sistema web de venta de licores para
usuarios mayores de 18 años1
, mostrara información del producto, métodos de envió y pago proporcionado por terceros, esto proporcionara una mayor fluidez en el mercado de licores, proporcionando
la facilidad al consumidor de comprar productos en múltiples contextos, y facilidad a la empresa
proveedora de evitar gastos que involucraría una comercio físico.
## Funcionalidades
Se quiere realizar un sistema para una empresa especializada en la comercialización de licor. Este
sistema estará compuesto por módulos independientes; ventas, compras, inventario y seguridad,
también se requiere registrar al cliente para que este acceda al sistema, asimismo almacenar datos
que se consideren necesarios.
## Práctica de código legible aplicadas
* Comentarios en las funciones mas robustas.
* Identación consistente.
* Evitar comentarios obvios.
* Agrupación de los códigos mediante varias lineas de separación.
* Esquema de nomenclatura Coherente : funcionToDeleteMess..
* Limitar el ancho de la linea de codigo continuandola en la siguiente linea.
* Organización de las carpetas y archivos.
* Separación de código y datos.

## Estilos de Programación aplicados
### Tantrum
* Cada uno de los procedimientos y funciones verifica la cordura de sus argumentos y se niegaa continuar cuando los argumentos no son razonables.
* Todos los bloques de código comprueban todos los errores posibles, posiblemente imprimen mensajes específicos del contexto cuando ocurren errores, y pasan los errores a la cadena de llamadas de función.

### Passive-Aggressive
* Al llamar a otras funciones, las funciones del programa solo verifican errores si están enposición de reaccionar significativamente.
* El manejo de errores se produce en los niveles más altos de las cadenas de llamadas defunciones, dondequiera que sea significativo hacerlo.

### Declared-Intentions
* Los procedimientos y funciones declaran qué tipos de argumentos esperan.
* Si las personas que envían argumentos de tipos que no se esperan, los procedimientos /funciones no se ejecutan.

### Things
* El problema mayor se descompone en çosas"que tienen sentido para el dominio del problema.
* Cada cosa es una cápsula de datos que expone los procedimientos al resto del mundo.
* Los datos nunca son accedidos directamente, solo a través de estos procedimientos.

### Introspective
* El problema se descompone utilizando alguna forma de abstracción (procedimientos, funcio-nes, objetos, etc.
* Las abstracciones tienen acceso a la información sobre sí mismos, aunque no pueden modificaresa información.

### Cook Book
* Las abstracciones tienen acceso a la información sobre sí mismos, aunque no pueden modificaresa información.
* Pueden compartir variables publicas entre las funciones,es decir pueden usar variables queesten fuera de la función.

### Pipeline
* Pueden compartir variables publicas entre las funciones,es decir pueden usar variables queesten fuera de la función.
* No comparten variables publicas entre las funciones,es decir solo usan variables que estendeclaras dentro de la misma función.


## Principios SOLID aplicados
### SRP
Este primer principio dice que "una clase debe tener una sola razón para cambiar", es decir , debe tener una responsabilidad única. Básicamente, este principio se refiere específicamente a la cohesión

### SLP
Este principio fue descrito por el investigador Barbara Liskov , en su artículo de 1988, explica que antes de optar por herencia, tenemos que pensar en las condiciones previas y post-condiciones de su clase. La herencia debe ser utilizada de forma contextualizada y moderada, evitando los casos de clases ser extendidas sólo por poseer algo en común.

## Conceptos DDD aplicados
* Lenguaje Ubicuo: Ubiquitous Language
* Capas de la arquitectura
* Módulos (Modules).