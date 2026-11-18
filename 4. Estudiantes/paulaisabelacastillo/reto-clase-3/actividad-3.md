
# Reto de clase #3 · Mi primera página web en 20 minutos

**Estudiante:** Paula Castillo  
**Curso:** Activadores de Comunidades de Práctica · SENACYT / CENFOTEC  
**Proyecto:** Mi primera página web  
**Área:** Educación STEAM, programación y tecnología  
**Público:** Niñas, jóvenes, docentes y personas sin experiencia en programación  
**Duración estimada:** 20–30 minutos  
**Modalidad:** Trabajo individual  
**Versión:** 1.0 · Guía inicial, pendiente de prueba con participantes

---

## 1. Para qué sirve

Esta actividad busca demostrar que cualquier persona puede comenzar a aprender programación, incluso si nunca ha escrito una línea de código.

A través de una experiencia sencilla, los participantes aprenderán a crear su primera página web utilizando HTML y podrán personalizarla con su nombre, intereses y actividades favoritas.

La idea nace de mi experiencia enseñando tecnología a niñas a través de Teen4STEAM, una comunidad que fundé para motivar a más niñas y jóvenes a explorar el mundo STEAM.

Muchas veces, las personas creen que programar es demasiado complicado o que necesitan conocimientos avanzados para comenzar. Sin embargo, considero que la mejor manera de aprender tecnología es experimentando y creando algo propio.

**Objetivo principal:** Que una persona sin conocimientos previos pueda crear, abrir y personalizar una página web sencilla siguiendo únicamente esta guía.

Al finalizar, tendrá una página que podrá modificar, compartir y utilizar como punto de partida para continuar aprendiendo programación.

---

## 2. Qué necesitas

Para realizar esta actividad se necesitan:

- Una computadora con Windows, macOS o Linux.
- Un navegador web, como Google Chrome, Safari o Microsoft Edge.
- Un editor de texto, como Visual Studio Code, Bloc de notas o TextEdit.
- Conocimientos básicos para crear y guardar archivos.
- Aproximadamente 20–30 minutos.

**No necesitas:**

- Saber programar previamente.
- Comprar programas.
- Tener conocimientos avanzados de tecnología.
- Crear una cuenta en una plataforma.

La actividad puede realizarse sin conexión a internet una vez que se dispone de un editor de texto.

### ¿Qué es HTML?

HTML significa *HyperText Markup Language*.

Es un lenguaje de marcado que permite organizar el contenido de una página web mediante elementos como títulos, párrafos, imágenes y enlaces.

En esta actividad utilizaremos HTML para construir una página personal.

---

## 3. Cómo hacerlo

### Paso 1. Preparar el espacio de trabajo

1. Abre el editor de texto de tu computadora.
2. Crea un documento nuevo.
3. Guárdalo con el nombre `index.html`.
4. Asegúrate de que el archivo termine en `.html` y no en `.txt`.

Si utilizas TextEdit en Mac, selecciona **Formato → Convertir en texto sin formato** antes de pegar el código.

Guarda el archivo como `index.html`, desactivando la opción de agregar `.txt` cuando aparezca.

### Paso 2. Escribir el código

Copia el siguiente código completo y pégalo en tu archivo `index.html`.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>Mi primera página web</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            text-align: center;
            margin: 0;
            padding: 40px 20px;
        }

        .contenedor {
            background-color: white;
            max-width: 600px;
            margin: auto;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        h1 {
            color: #6345b8;
        }

        h2 {
            color: #287eaa;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        button {
            background-color: #6345b8;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #49318b;
        }
    </style>
</head>

<body>

    <div class="contenedor">

        <h1>¡Hola, mundo!</h1>

        <h2>Bienvenidos a mi primera página web</h2>

        <p>
            Mi nombre es Paula y estoy aprendiendo
            a crear páginas web con HTML.
        </p>

        <p>
            Me gusta la tecnología, la robótica
            y aprender cosas nuevas.
        </p>

        <button onclick="mostrarMensaje()">
            Haz clic aquí
        </button>

        <p id="mensaje"></p>

    </div>

    <script>
        function mostrarMensaje() {
            document.getElementById("mensaje").textContent =
                "¡Felicidades! Tu primera página funciona.";
        }
    </script>

</body>
</html>
```

### Paso 3. Abrir la página

1. Guarda los cambios.
2. Busca el archivo `index.html` en tu computadora.
3. Haz doble clic sobre el archivo.
4. Se abrirá en tu navegador.

Deberías visualizar una página con fondo celeste claro, un recuadro blanco, títulos, párrafos y un botón morado.

**Importante:** No necesitas subir el archivo a internet para visualizarlo.

### Paso 4. Probar la interacción

Haz clic en el botón que dice **Haz clic aquí**.

Debajo del botón debería aparecer el mensaje:

**¡Felicidades! Tu primera página funciona.**

Este botón utiliza JavaScript, un lenguaje de programación que permite agregar interactividad a las páginas web.

### Paso 5. Personalizar la página

Ahora modifica tres elementos:

**Reto 1: Cambia el nombre.**

Busca:

```html
Mi nombre es Paula
```

Reemplázalo por tu propio nombre.

**Reto 2: Cambia el color.**

Busca:

```css
background-color: #f0f8ff;
```

Prueba reemplazar el código de color por:

```css
background-color: #fff0f5;
```

**Reto 3: Cambia el mensaje del botón.**

Busca:

```javascript
"¡Felicidades! Tu primera página funciona."
```

Escribe un mensaje diferente.

Guarda el archivo y actualiza el navegador después de cada modificación.

---

## 4. Cómo comprobar que funcionó

La actividad se considera completada cuando la persona logra realizar las siguientes acciones:

| Prueba | Resultado esperado |
|---|---|
| Abrir `index.html` | La página aparece en el navegador. |
| Visualizar el título | Se muestra "¡Hola, mundo!". |
| Visualizar los párrafos | Aparecen los textos de presentación. |
| Presionar el botón | Aparece el mensaje de felicitación. |
| Cambiar el nombre | Se muestra el nuevo nombre. |
| Cambiar el color | El fondo cambia después de actualizar. |
| Modificar el mensaje | El botón muestra el texto personalizado. |

### Criterio de éxito

La actividad funciona correctamente si la persona puede abrir su página, observar su contenido, utilizar el botón y realizar al menos una modificación sin recibir ayuda directa.

### Prueba con participantes

Se propone invitar a tres personas que nunca hayan programado.

Cada participante recibirá únicamente esta guía y deberá intentar completar la actividad.

Se observará:

- Si comprende las instrucciones.
- Si puede crear y guardar el archivo.
- Si logra abrirlo en el navegador.
- Si consigue modificar algún elemento.
- Cuánto tiempo necesita.
- En qué paso requiere ayuda.

**Estado actual:** La prueba con participantes está pendiente. No se han registrado resultados de usuarios.

---

## 5. Qué aprendimos y qué falta resolver

### Conocimientos que permite desarrollar

Esta actividad introduce conceptos fundamentales del desarrollo web:

**HTML:** Organiza el contenido de la página.

**CSS:** Permite modificar colores, tamaños, fuentes y apariencia visual.

**JavaScript:** Permite agregar interacciones, como mostrar un mensaje al presionar un botón.

También fomenta habilidades importantes como:

- Pensamiento lógico.
- Creatividad.
- Resolución de problemas.
- Experimentación.
- Aprendizaje autónomo.

### Errores frecuentes

| Problema | Posible solución |
|---|---|
| La página muestra el código en lugar del diseño. | Verificar que el archivo termine en `.html` y no en `.txt`. |
| El botón no funciona. | Revisar que el código JavaScript esté completo. |
| El color no cambia. | Guardar el archivo y actualizar el navegador. |
| No aparece el título. | Revisar que el código HTML se haya copiado completo. |
| El navegador no abre el archivo. | Buscar `index.html` y abrirlo con un navegador. |

### Aspectos pendientes

- Realizar la actividad con personas principiantes.
- Evaluar si las instrucciones son suficientemente claras.
- Registrar dificultades reales.
- Incorporar capturas de pantalla.
- Crear una segunda actividad con imágenes y enlaces.
- Mejorar la guía según la retroalimentación recibida.

---

## 6. Cómo puedes contribuir

Una comunidad de práctica crece cuando sus integrantes no solamente utilizan los recursos, sino que también los mejoran y comparten lo aprendido.

Por eso, esta guía está diseñada para que cualquier persona pueda realizar una pequeña contribución.

### Invitación: ¡Crea tu propia versión!

Te invito a utilizar esta guía para crear tu primera página web y personalizarla según tus intereses.

Puedes contribuir de diferentes maneras:

1. Cambiar los colores y compartir tu combinación favorita.
2. Agregar una nueva sección a la página.
3. Identificar una instrucción que resulte confusa.
4. Proponer una mejora al código.
5. Compartir una captura de tu página terminada.
6. Ayudar a otra persona a realizar la actividad.

### ¿Cómo compartir tu contribución?

Si tienes una cuenta de GitHub:

1. Ingresa al repositorio donde está publicada la actividad.
2. Abre la sección **Issues**.
3. Selecciona **New issue**.
4. Escribe como título: `Mi experiencia creando una página web`.
5. Describe qué lograste, qué dificultad encontraste y qué mejorarías.

También puedes proponer cambios directamente mediante un pull request.

Si no tienes GitHub, puedes compartir tus comentarios a través del facilitador de la actividad.

No necesitas saber programar para contribuir. Una pregunta o una sugerencia también puede ayudar a mejorar el recurso.

---

## 7. Autoría y fuentes

**Autora:** Paula Castillo.

**Modalidad:** Desarrollo individual.

**Origen de la experiencia:**

La propuesta se inspira en mi experiencia con Teen4STEAM, una comunidad que fundé para acercar la ciencia, tecnología, ingeniería, arte y matemáticas a más niñas y jóvenes.

A través de talleres y actividades educativas he aprendido la importancia de explicar conceptos tecnológicos de manera sencilla y permitir que las personas aprendan creando.

Esta guía adapta ese enfoque a una actividad introductoria de desarrollo web.

### Fuentes de consulta

- [MDN Web Docs: Introducción a HTML](https://developer.mozilla.org/es/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content)
- [MDN Web Docs: CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [MDN Web Docs: JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [W3Schools: HTML Tutorial](https://www.w3schools.com/html/)

### Condiciones de reutilización

Se propone compartir el contenido original de esta guía bajo la licencia Creative Commons Attribution 4.0 (CC BY 4.0).

Esto permitiría reutilizar, adaptar y compartir el material, reconociendo la autoría e indicando las modificaciones realizadas.

La elección de licencia deberá confirmarse al publicar el recurso. Las fuentes externas mantienen sus propias condiciones de uso.

---

## 8. Revisión durante la clase

### Revisión con inteligencia artificial

Se utilizó inteligencia artificial como apoyo para estructurar la guía, explicar los conceptos de manera sencilla, identificar posibles errores y proponer criterios de evaluación.

La revisión permitió identificar elementos que una persona principiante podría necesitar:

- Explicación de qué es HTML.
- Instrucciones para guardar el archivo.
- Código completo.
- Pasos para abrir la página.
- Explicación del funcionamiento del botón.
- Posibles errores y soluciones.
- Criterios para comprobar el resultado.

**Importante:** La revisión documental no reemplaza una prueba real con participantes.

### Revisión por otra persona

Como esta actividad se desarrolla individualmente, se propone solicitar a otra persona que lea la guía sin recibir explicaciones adicionales.

La persona revisora deberá responder:

| Pregunta | Estado |
|---|---|
| ¿Qué puedes hacer con este recurso? | Pendiente de revisión externa. |
| ¿Qué necesitas para comenzar? | Pendiente de revisión externa. |
| ¿Cuál sería el primer paso? | Pendiente de revisión externa. |
| ¿Cómo sabrías que funcionó? | Pendiente de revisión externa. |
| ¿Dónde necesitarías pedir ayuda? | Pendiente de revisión externa. |

**Persona revisora:** Por definir.  
**Fecha de revisión:** Por definir.  
**Tipo de revisión:** Comprensión de instrucciones y prueba práctica.  
**Cambios realizados después de la revisión:** Pendientes.

---

## 9. Continuidad de la comunidad

El propósito de este recurso no es solamente enseñar a crear una página web, sino demostrar cómo un conocimiento puede documentarse para que otras personas lo reutilicen.

### ¿Cómo podría crecer esta experiencia?

**Primera etapa: Aprender**

Una persona sigue las instrucciones y crea su primera página web.

**Segunda etapa: Experimentar**

Personaliza los colores, textos y elementos de su página.

**Tercera etapa: Compartir**

Publica su resultado y explica qué cambios realizó.

**Cuarta etapa: Acompañar**

Ayuda a otra persona que está comenzando.

**Quinta etapa: Mejorar**

Propone nuevas actividades o modificaciones para que el recurso continúe creciendo.

### Próximos pasos

- Realizar una prueba con tres participantes.
- Documentar los resultados.
- Incorporar mejoras a la guía.
- Crear una segunda actividad con HTML y CSS.
- Invitar a otros participantes a compartir sus versiones.
- Construir una pequeña colección de recursos educativos reutilizables.

**Responsable:** Paula Castillo.  
**Fecha de la próxima prueba:** Por definir.

---

## 10. Reflexión final

Considero que una de las mejores formas de aprender tecnología es creando algo propio.

Muchas personas no se acercan a la programación porque creen que es demasiado difícil, pero una experiencia sencilla puede cambiar esa percepción.

A través de Teen4STEAM he buscado que más niñas descubran que también pueden crear tecnología y no solamente utilizarla.

Con este recurso quiero compartir esa misma idea: **no necesitas ser experta para comenzar, solamente necesitas curiosidad y la oportunidad de intentarlo.**

Además, documentar una actividad permite que el conocimiento no dependa únicamente de quien lo enseña.

Otra persona puede utilizar la guía, adaptarla, compartirla y mejorarla.

De esta manera, una experiencia individual puede convertirse en un recurso compartido que contribuya al crecimiento de una comunidad de práctica.

**El conocimiento crece cuando lo compartimos y permitimos que otras personas construyan a partir de él.**

---

**Proyecto:** Mi primera página web en 20 minutos  
**Autora:** Paula Castillo  
**Curso:** Activadores de Comunidades de Práctica · SENACYT / CENFOTEC  
**País:** Panamá  
**Estado:** Primera versión documentada; pruebas externas pendientes.
