# Digitalizacion
**Sistemas Complejos en Inteligencia Artificial**

¿Qué es un sistema complejo?

Un sistema complejo en Inteligencia Artificial es una solución que utiliza múltiples llamadas a modelos de lenguaje (LLMs) para resolver una tarea.
En lugar de utilizar un único modelo para realizar todo el trabajo, el problema se divide en varias etapas o subtareas. Cada etapa puede utilizar el mismo LLM o diferentes modelos especializados.
El resultado de una etapa puede utilizarse como entrada para la siguiente, creando un flujo de trabajo en el que diferentes modelos colaboran para conseguir un resultado más completo.

**Idea principal**: un sistema complejo divide un problema grande en problemas más pequeños que pueden ser resueltos de forma independiente y coordinada.

**Explicación intuitiva**

Podemos imaginar un sistema complejo como una cadena de montaje. Cada trabajador tiene una función específica:

-Un trabajador realiza la primera tarea.
-El resultado pasa al siguiente trabajador.
-El segundo realiza otra tarea.
-El proceso continúa hasta obtener el producto final.

En un sistema complejo ocurre algo similar, pero los trabajadores son modelos **de Inteligencia Artificial**

Por ejemplo, para crear un artículo sobre un tema determinado:

Tema -> Crear índice -> Buscar información -> Analizar información -> Redactar contenido -> Revisar contenido -> Aplicar formato -> Artículo final

Cada etapa puede ser realizada por un LLM diferente.

Ejemplo: Un sistema complejo puede utilizarse para crear artículos detallados siguiendo diferentes etapas.

1. Crear un índice
Un LLM genera un esquema inicial para organizar el contenido.

2. Refinar el índice
Otro modelo revisa el esquema y añade información para mejorar la estructura.

3. Identificar temas relacionados
Un tercer LLM busca temas que puedan complementar el contenido.

4. Buscar información
El sistema puede utilizar herramientas externas como Wikipedia para obtener información adicional.

6. Desarrollar el contenido
Diferentes LLMs pueden encargarse de desarrollar cada sección del artículo.

7. Escribir el artículo
Un modelo recopila toda la información y genera el artículo completo.

7. Aplicar formato
Finalmente, otro modelo puede encargarse de aplicar el formato necesario.
