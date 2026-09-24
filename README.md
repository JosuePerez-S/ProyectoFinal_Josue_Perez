# Actividad-Final-De-Unidad-Josue-Perez
# Glosario Integrado de Fundamentos de Programación, Desarrollo y Control de Versiones

Este documento integra las **40 definiciones clave** trabajadas en las Actividades #2 y #4. Presenta una guía fundamental sobre lógica de programación, herramientas de desarrollo y sistemas de control de versiones.

---

## Parte 1: Fundamentos de Programación (Actividad #2)

### 1. Algoritmo
* **Definición:** Secuencia ordenada, finita y precisa de pasos lógicos que se siguen para resolver un problema o realizar una tarea específica.
* **Ejemplo:** Una receta para preparar café: 1. Hervir agua, 2. Colocar café en la taza, 3. Servir el agua caliente, 4. Endulzar al gusto.

### 2. Programa
* **Definición:** Conjunto de instrucciones ordenadas en un lenguaje comprensible para la computadora, diseñadas para ejecutar una función concreta.
* **Ejemplo:** La aplicación de la calculadora en el teléfono celular que procesa operaciones matemáticas.

### 3. Código fuente
* **Definición:** El texto escrito por un programador utilizando un lenguaje de programación específico, el cual contiene la lógica y las reglas del software antes de ser traducido a lenguaje máquina.
* **Ejemplo:** Un archivo `index.js` que contiene instrucciones escritas en JavaScript.

### 4. Lenguaje de programación
* **Definición:** Idioma formal con reglas gramaticales e instrucciones estandarizadas que permite al desarrollador comunicarse con el hardware de la computadora.
* **Ejemplo:** Python, C++, JavaScript o Java.

### 5. Sintaxis
* **Definición:** Conjunto de reglas estrictas que definen el orden y la combinación correcta de los símbolos y palabras clave en un lenguaje de programación.
* **Ejemplo:** En JavaScript, definir una función respetando sus paréntesis y llaves: `function miFuncion() {}`.

### 6. Variable
* **Definición:** Espacio en la memoria de la computadora reservado para almacenar un dato cuyo valor puede modificarse durante la ejecución del programa.
* **Ejemplo:** `let puntos = 10;`, donde `puntos` cambia a `15` al ganar un nivel.

### 7. Constante
* **Definición:** Valor almacenado en memoria que permanece fijo y no puede ser alterado una vez definido durante toda la ejecución del software.
* **Ejemplo:** `const PI = 3.1416;`.

### 8. Tipo de dato
* **Definición:** Clasificación que se le otorga a un valor para indicarle al sistema qué clase de operaciones se pueden realizar con él y cuánto espacio requiere en memoria.
* **Ejemplo:** Número entero (`int`), texto (`String`), o valor lógico (`Boolean`).

### 9. Operador
* **Definición:** Símbolo reservado que realiza una acción matemática, lógica o de comparación sobre uno o más datos (operandos).
* **Ejemplo:** El símbolo `+` para sumar o `==` para comparar si dos valores son iguales.

### 10. Expresión
* **Definición:** Combinación de variables, constantes, operadores y funciones que el sistema evalúa para producir un único resultado final.
* **Ejemplo:** `let total = (precio * cantidad) - descuento;`.

### 11. Condicional
* **Definición:** Estructura de control que permite al programa tomar decisiones y ejecutar un bloque de código u otro dependiendo de si una condición es verdadera o falsa.
* **Ejemplo:** Un `if (edad >= 18)` que permite el acceso a un sitio web solo si la condición se cumple.

### 12. Bucle
* **Definición:** Estructura que repite un bloque de código varias veces de manera continua hasta que se cumpla o deje de cumplirse una condición específica.
* **Ejemplo:** Un ciclo `while` o `for` que imprime los números del 1 al 10 en pantalla.

### 13. Función
* **Definición:** Bloque de código reutilizable diseñado para realizar una tarea específica cuando es invocado por su nombre.
* **Ejemplo:** `function saludar() { console.log("¡Hola!"); }`.

### 14. Parámetro
* **Definición:** Variable declarada dentro de la definición de una función que actúa como contenedor para recibir datos desde el exterior.
* **Ejemplo:** En `function sumar(a, b)`, las variables `a` y `b` son los parámetros.

### 15. Argumento
* **Definición:** El valor real y concreto que se envía a la función al momento de llamarla o ejecutarla.
* **Ejemplo:** En la llamada `sumar(5, 3)`, los números `5` y `3` son los argumentos.

### 16. Retorno
* **Definición:** El valor o resultado final que una función devuelve al lugar desde donde fue invocada mediante la instrucción correspondiente (`return`).
* **Ejemplo:** `return a + b;` dentro de una función de suma.

### 17. Arreglo (Array)
* **Definición:** Estructura de datos organizada que permite almacenar múltiples valores dentro de una sola variable bajo un mismo nombre, accesibles mediante índices numéricos.
* **Ejemplo:** `let frutas = ["manzana", "pera", "uva"];`.

### 18. Objeto
* **Definición:** Entidad que representa un elemento del mundo real dentro del código, agrupando características (propiedades) y acciones (métodos).
* **Ejemplo:** `let auto = { marca: "Toyota", modelo: 2024, encender: function() {} };`.

### 19. Método
* **Definición:** Una función declarada dentro de un objeto que define las acciones o comportamientos que dicho objeto puede realizar.
* **Ejemplo:** `auto.frenar()` que ejecuta la acción de detener el vehículo.

### 20. Evento
* **Definición:** Acción o suceso detectado por el sistema (generado por el usuario o por el entorno) que desencadena una respuesta automática dentro del programa.
* **Ejemplo:** Hacer clic con el ratón sobre un botón (`onclick`) para enviar un formulario.

---

## Parte 2: Conceptos de Desarrollo y Control de Versiones (Actividad #4)

### 21. Compilador
* **Definición:** Traduce todo el código fuente de alto nivel a lenguaje máquina de una sola vez, generando un archivo ejecutable antes de correr la aplicación.
* **Ejemplo:** El comando `g++` procesa un archivo `.cpp` y genera un ejecutable `.exe` en C++.

### 22. Intérprete
* **Definición:** Lee, traduce y ejecuta las instrucciones del código línea por línea en tiempo real sin crear un archivo ejecutable previo.
* **Ejemplo:** El entorno de Python que lee `print("Hola mundo")` y muestra el texto de inmediato en la terminal.

### 23. Depurador (Debugger)
* **Definición:** Herramienta que permite pausar la ejecución del programa en puntos específicos para inspeccionar variables y detectar errores lógicos.
* **Ejemplo:** Colocar un punto de interrupción (*breakpoint*) en VS Code para observar cómo cambia una variable dentro de un ciclo.

### 24. IDE (Entorno de Desarrollo Integrado)
* **Definición:** Software completo que integra editor de código, compilador o intérprete, depurador y gestor de proyectos en una sola interfaz.
* **Ejemplo:** IntelliJ IDEA o Eclipse utilizados para desarrollar aplicaciones complejas en Java.

### 25. Editor de código
* **Definición:** Aplicación de texto ligera optimizada para escribir código, con funciones como resaltado de sintaxis y autocompletado ampliable mediante extensiones.
* **Ejemplo:** Editar archivos HTML, CSS o JavaScript utilizando Visual Studio Code.

### 26. Biblioteca (Library)
* **Definición:** Colección de funciones y métodos preescritos que el desarrollador importa para reutilizar código sin reprogramarlo desde cero.
* **Ejemplo:** Usar el módulo `Math` en JavaScript para calcular una raíz cuadrada con `Math.sqrt(16)`.

### 27. Framework
* **Definición:** Estructura de trabajo que proporciona reglas, plantillas y la arquitectura base sobre la cual se debe construir una aplicación.
* **Ejemplo:** Crear una aplicación móvil basada en la arquitectura y componentes de React Native.

### 28. API (Interfaz de Programación de Aplicaciones)
* **Definición:** Conjunto de reglas y protocolos que permite a dos sistemas o aplicaciones comunicarse e intercambiar datos entre sí.
* **Ejemplo:** Una app del clima que consulta una API externa para obtener y mostrar la temperatura actual.

### 29. Repositorio
* **Definición:** Carpeta digital donde se almacenan los archivos, imágenes, historial de versiones y configuraciones de un proyecto.
* **Ejemplo:** Una carpeta rastreada con Git que contiene el código fuente de una aplicación.

### 30. Control de versiones
* **Definición:** Sistema que registra las modificaciones hechas en los archivos a lo largo del tiempo, permitiendo revisar historiales o recuperar estados anteriores.
* **Ejemplo:** Comparar el código actual con una versión anterior para identificar qué cambio provocó un fallo.

### 31. Git
* **Definición:** Sistema de control de versiones distribuido que opera localmente en el equipo para rastrear cambios de código de forma descentralizada.
* **Ejemplo:** Ejecutar en la terminal `git init` para iniciar el rastreo o `git status` para ver los cambios pendientes.

### 32. GitHub
* **Definición:** Plataforma en la nube que aloja repositorios de Git y ofrece herramientas para trabajo colaborativo y gestión de código.
* **Ejemplo:** Subir un proyecto local desde VS Code hacia una cuenta en github.com.

### 33. Rama (Branch)
* **Definición:** Línea de trabajo independiente dentro de un repositorio que permite modificar código sin alterar la versión principal.
* **Ejemplo:** Crear la rama `feature-login` para programar un inicio de sesión mientras la rama `main` se mantiene funcional.

### 34. Commit
* **Definición:** Guardado o instantánea en el historial del repositorio que confirma los cambios realizados junto con un mensaje descriptivo.
* **Ejemplo:** Confirmar cambios en la terminal ejecutando `git commit -m "Se agrega validación de formulario"`.

### 35. Merge
* **Definición:** Operación que une el historial y los cambios de una rama secundaria con la rama principal.
* **Ejemplo:** Fusionar la rama `feature-login` a la rama `main` una vez probada la función.

### 36. Callback
* **Definición:** Función que se pasa como argumento a otra función para ejecutarse automáticamente al terminar una tarea específica.
* **Ejemplo:** En JavaScript, ejecutar una función que muestre un mensaje en pantalla en cuanto termine de descargarse un archivo.

### 37. Programación síncrona
* **Definición:** Modelo de ejecución secuencial en el que cada instrucción debe terminar por completo antes de que comience la siguiente.
* **Ejemplo:** Un script que lee un archivo pesado del disco y congela el avance del programa hasta concluir la lectura.

### 38. Programación asíncrona
* **Definición:** Modelo de ejecución no bloqueante que permite iniciar tareas de larga duración mientras el resto del programa sigue ejecutándose.
* **Ejemplo:** Consultar una base de datos en línea sin impedir que el usuario continúe interactuando con la interfaz.

### 39. JavaScript
* **Definición:** Lenguaje de programación interpretado y dinámico usado principalmente para agregar interactividad a páginas web y construir aplicaciones completas.
* **Ejemplo:** Un script que valida los datos de un formulario Web antes de ser enviados.

### 40. TypeScript
* **Definición:** Superconjunto de JavaScript desarrollado por Microsoft que añade tipado estático para detectar errores durante la fase de desarrollo.
* **Ejemplo:** Definir una variable estrictamente como número mediante `let edad: number = 20;`.

---

## Referencias
* Joyanes Aguilar, L. (2020). *Fundamentos de programación: Algoritmos, estructura de datos y objetos* (5.ª ed.). McGraw-Hill Education.
* Universidad Nacional Autónoma de México. (2023). *Conceptos fundamentales de la programación estructurada y orientada a objetos*. Facultad de Ingeniería, UNAM. https://www.ingenieria.unam.mx
* MDN Web Docs. (2026). *Glosario de conceptos clave de programación y desarrollo web*. Mozilla Developer Network. https://developer.mozilla.org/es/docs/Glossary
