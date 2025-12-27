🎮 Taller: Desarrollo de Interfaces con Unity
Creación de Interfaces de Usuario (UI)

Este proyecto fue desarrollado como parte del Taller de Desarrollo de Interfaces con Unity, cuyo objetivo es comprender y aplicar los elementos básicos de la interfaz de usuario (UI), la interacción con scripts y principios básicos de diseño visual y usabilidad.

El proyecto consiste en un menú principal funcional desarrollado en Unity, publicado en WebGL y accesible en línea mediante Itch.io.

🧠 Objetivos de Aprendizaje

Comprender los elementos básicos de UI en Unity (Canvas, Paneles, Botones, Textos).

Manejar componentes interactivos para construir menús funcionales.

Integrar scripts simples para controlar la interacción entre la UI y la lógica del juego.

Aplicar principios básicos de diseño visual y usabilidad.

🛠️ Tecnologías Utilizadas

Unity (UI System)

C#

Build WebGL

Itch.io

YouTube (video demostrativo)

📋 Descripción del Proyecto

El proyecto implementa un menú principal con las siguientes características:

Canvas principal como contenedor de la interfaz.

Panel de fondo para organizar los elementos visuales.

Texto con el título del menú.

Botones interactivos:

Jugar

Opciones

Salir

Animaciones simples en los botones (hover y click).

Navegación entre escenas.

Sub-panel de opciones que se muestra y oculta dinámicamente.

🎯 Funcionalidades Implementadas
▶️ Botón Jugar

Carga una nueva escena llamada GameScene.

Se realiza mediante SceneManager.LoadScene().

⚙️ Botón Opciones

Muestra u oculta un sub-panel de opciones con controles ficticios.

El panel se activa o desactiva usando código C# (SetActive(true/false)).

Concepto clave:
El panel de opciones existe desde el inicio, pero comienza oculto. Al presionar el botón, su estado cambia entre visible e invisible.

Ejemplo del comportamiento:

Si el panel está oculto → se muestra.

Si el panel está visible → se oculta.

Esto permite simular un menú de configuración sin cambiar de escena.

❌ Botón Salir

Cierra la aplicación usando Application.Quit().

Funciona únicamente en la versión compilada (build), no en el editor de Unity.

🎨 Animaciones y Transiciones

Se añadieron animaciones simples a los botones:

Cambio visual al pasar el cursor (hover).

Efecto visual al hacer clic.

Esto mejora la experiencia del usuario y la sensación de interactividad (UI feedback).

🌐 Publicación en Itch.io

El proyecto fue compilado en WebGL y publicado en Itch.io, permitiendo que se ejecute directamente desde el navegador.

🔗 Link del proyecto en Itch.io:
👉 https://andrewvilcacundo.itch.io/desarrollo-de-interfaces-con-unity

🎥 Video Demostrativo

Se grabó un video corto (2–3 minutos) donde se muestra:

El menú funcionando correctamente.

Las animaciones de los botones.

La navegación hacia otra escena.

El uso del menú de opciones.

🔗 Link del video en YouTube:
👉 https://youtu.be/hS2rKeZdgU4

📦 Entregables

✅ Proyecto jugable en WebGL (Itch.io)

✅ Video demostrativo del funcionamiento

✅ Menú funcional con interacción y animaciones

⭐ Extras Implementados / Considerados

Diseño visual claro y organizado.

Transiciones simples para mejorar la experiencia de usuario.

Estructura preparada para agregar sonidos, íconos o música de fondo.

👤 Autor

Andrew Vilcacundo
Proyecto académico – Desarrollo de Interfaces con Unity
