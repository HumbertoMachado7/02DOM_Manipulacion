# 02 - Proyecto: Manipulación del DOM

Este proyecto práctico es una demostración de las técnicas fundamentales para manipular el DOM (Document Object Model) utilizando JavaScript puro. A través de la construcción de una calculadora simple, se exploran los conceptos clave que permiten a una página web ser interactiva.

El objetivo es aplicar la teoría para conectar una interfaz de usuario HTML con la lógica de programación en JavaScript, una habilidad esencial para cualquier desarrollador web.

---

## Conceptos Clave Demostrados

Este ejercicio pone en práctica los conocimientos adquiridos en los siguientes temas:

*   **Conexión entre HTML y JavaScript:**
    Se establece el vínculo entre los archivos usando la etiqueta `<script>`, permitiendo que el código JavaScript pueda "ver" y controlar la estructura HTML.

*   **Lectura de Elementos del DOM:**
    Se utiliza `document.querySelector()` para seleccionar y obtener nodos específicos del HTML (inputs, botones, párrafos) y almacenarlos en variables para su uso posterior.

*   **Escritura y Modificación del DOM:**
    Se altera el contenido de un elemento HTML de forma dinámica, actualizando el texto del párrafo de resultados (`<p>`) con la propiedad `.innerText`.

*   **Manejo de Eventos del Usuario:**
    Se implementa el método `addEventListener('click', miFuncion)` para "escuchar" la interacción del usuario con el botón de calcular. Este enfoque es la práctica moderna y preferida sobre el uso de atributos `onclick` en el HTML, ya que promueve una mejor separación de la estructura (HTML) y el comportamiento (JS).

*   **Resolución de Problemas Comunes:**
    Se aborda y soluciona el error típico de la concatenación de strings al leer valores de inputs, aplicando la función `Number()` para asegurar que la operación sea una suma matemática y no una unión de texto.

---

### [⬅️ Volver al repositorio principal: javascript-advanced-concepts](https://github.com/HumbertoMachado7/javascript-advanced-concepts)
