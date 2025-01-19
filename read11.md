'''
### 1. ¿Qué es el DOM?
El DOM (Document Object Model) es una representación estructurada de un documento HTML o XML en forma de un árbol jerárquico. Cada parte del documento, como etiquetas, atributos o texto, se representa como nodos y objetos que se pueden manipular programáticamente. Es una interfaz que permite a los lenguajes de programación, como JavaScript, acceder y modificar la estructura, estilo y contenido de una página web en tiempo de ejecución.

### 2. Relación entre el DOM y JavaScript
El DOM y JavaScript están estrechamente relacionados porque JavaScript utiliza el DOM para interactuar con las páginas web. A través del DOM, JavaScript puede seleccionar elementos específicos, modificar su contenido, estilo, estructura, e incluso agregar o eliminar elementos dinámicamente. Sin el DOM, JavaScript no podría realizar manipulaciones directas en la página web.

### 3. Método para seleccionar un elemento del DOM por su ID y cómo se utiliza
El método para seleccionar un elemento del DOM por su ID es document.getElementById(). Se utiliza proporcionando el ID del elemento como argumento. Por ejemplo:
const elemento = document.getElementById('miElemento');
console.log(elemento); // Muestra el elemento con ID "miElemento" en la consola

### 4. Método para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría
Para cambiar el color de fondo de un elemento, puedes usar la propiedad style.backgroundColor. Primero seleccionas el elemento y luego modificas esta propiedad. Ejemplo:
const elemento = document.getElementById('miElemento');
elemento.style.backgroundColor = 'blue'; // Cambia el color de fondo a azul
Con este método, puedes modificar dinámicamente el estilo del elemento seleccionado.

'''
