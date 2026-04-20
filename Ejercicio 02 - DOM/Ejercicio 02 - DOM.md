# Ejercicio 02 - DOM

## Introducción

El **DOM** (*Document Object Model*) es la interfaz que los navegadores usan para representar un documento HTML como un árbol jerárquico de nodos. Gracias a él, JavaScript puede leer y modificar el contenido, la estructura y los estilos de una página de forma dinámica.

![Árbol DOM](/Ejercicio%2002%20-%20DOM/img/DOM-model.svg)

---

## Síntesis

El DOM organiza cada elemento del documento —etiquetas, atributos y texto— como un **nodo**. La raíz siempre es `document`, del que descienden `<html>`, `<head>`, `<body>` y todos sus hijos. JavaScript interactúa con esta estructura mediante una API dividida en cinco grupos:

- **Selección:** `getElementById()`, `querySelector()`, `querySelectorAll()`
- **Modificación:** `innerHTML`, `textContent`, `setAttribute()`, `classList`
- **Creación / Eliminación:** `createElement()`, `appendChild()`, `removeChild()`
- **Eventos:** `addEventListener()`, `removeEventListener()`
- **Traversal:** `parentNode`, `childNodes`, `nextSibling`, `firstChild`

![Manipulación del DOM con JavaScript](/Ejercicio%2002%20-%20DOM/img/what-are-the-properties-of-document-object.jpg)

---

## Reflexión

Lo que encuentro más útil del DOM es que convierte el HTML estático en algo interactivo y programable. Entender que con una línea como `document.querySelector('.btn').addEventListener('click', fn)` estoy accediendo a un nodo del árbol y diciéndole que reaccione al usuario, cambió completamente mi forma de pensar al construir interfaces. El DOM es el puente real entre HTML y JavaScript.

---

## Conclusión

El DOM es la capa que transforma un documento HTML en una estructura viva y manipulable. Comprender su árbol de nodos y los métodos de su API es fundamental para cualquier desarrollador web, ya que es la base de toda interactividad en la web moderna.
