# Bienvenidos a nuestra colección de Demos CSS

proximos: Writing-mode

Este repositorio es una colección de demostraciones de CSS que cubren características intermedias y avanzadas. Nuestro objetivo es proporcionar ejemplos claros y concisos que te ayuden a comprender y utilizar estas características en tus propios proyectos.

Te animamos a explorar las demostraciones, experimentar con el código y utilizarlo como referencia para tu propio trabajo. ¡No dudes en utilizar estos ejemplos en tus proyectos personales o profesionales!

Este repositorio se actualizará continuamente con nuevas demostraciones y ejemplos. ¡Asegúrate de visitarnos regularmente para descubrir las últimas novedades!

¡Esperamos que encuentres útiles estas demostraciones y que te ayuden a llevar tus habilidades de CSS al siguiente nivel!

## Proyectos

### 1. Subgrid

CSS Subgrid es una característica que extiende las capacidades de CSS Grid Layout, permitiendo que los elementos anidados dentro de una cuadrícula participen en la definición de tamaño y espaciado de su cuadrícula padre. Esto facilita la creación de diseños más complejos y alineados sin necesidad de cálculos manuales o trucos.

Actualmente, la demostración de Subgrid se encuentra **en construcción**. ¡Vuelve pronto para verla en acción!

### 2. Scroll Snap

CSS Scroll Snap permite controlar el comportamiento del desplazamiento (scroll) dentro de un contenedor, haciendo que se "ajuste" a posiciones específicas a medida que el usuario se desplaza. Esto es ideal para crear experiencias de desplazamiento nativas, como galerías de imágenes o carruseles, utilizando únicamente CSS.

La propiedad clave es `scroll-snap-type`, que define cómo se aplica el ajuste. En nuestra demostración, exploramos dos valores principales:
- `mandatory`: El navegador se ajustará obligatoriamente al siguiente punto de ajuste tan pronto como el usuario deje de desplazarse. Esto asegura que un elemento siempre esté centrado o en una posición definida.
- `proximity`: El ajuste solo ocurre si el usuario se detiene cerca de un punto de ajuste. Esto ofrece una experiencia de desplazamiento más suave, permitiendo que el usuario se detenga entre puntos si lo desea.

Puedes probar estas diferencias y ver Scroll Snap en acción en nuestra demostración.

- [Ver Demo](https://snap-scroll-demo.netlify.app/)

### 3. Consultas de Contenedor (Container Queries)

Las Consultas de Contenedor (Container Queries) son una característica de CSS que permite a los componentes adaptar su estilo basándose en el tamaño de su contenedor padre, en lugar de depender únicamente del tamaño del viewport (como lo hacen las Media Queries). Esto significa que un mismo componente puede tener diferentes apariencias dependiendo de dónde se coloque en el layout, sin necesidad de escribir CSS diferente para cada variante.

Nuestra demostración ilustra cómo los componentes pueden responder a las dimensiones de su contenedor, volviéndose verdaderamente modulares y reutilizables. Observa cómo los elementos cambian y se adaptan a medida que el tamaño del contenedor que los envuelve varía.

- [Ver Demo](https://harmonious-valkyrie-05aae2.netlify.app/)

### 4. Visibilidad de Contenido (Content Visibility)

La propiedad de CSS `content-visibility` permite controlar si un elemento renderiza su contenido o no, mejorando significativamente el rendimiento de la carga inicial de la página. Cuando se establece en `auto`, el navegador omite el renderizado del contenido que está fuera de la pantalla (off-screen), procesándolo solo cuando se vuelve visible para el usuario. Esto puede acelerar drásticamente la carga de páginas con mucho contenido.

Nuestra demostración utiliza `content-visibility: auto` para mostrar cómo los elementos se cargan y renderizan a medida que se desplazan hacia la vista.

- Para ver esta demostración, clona el repositorio y abre el archivo `04 content-visibility/index.html` en tu navegador.

## Uso y Contribución

### Cómo ejecutar los demos localmente

La mayoría de las demostraciones que no tienen un enlace de "Ver Demo" directo a una plataforma en línea se pueden ejecutar localmente. Para ello:

1.  **Clona este repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```
    (Por favor, reemplaza `https://github.com/tu-usuario/tu-repositorio.git` con la URL real del repositorio si es diferente).
2.  **Navega a la carpeta del proyecto:**
    Cada demostración se encuentra en su propia carpeta, por ejemplo, `02-scroll-snap/` o `04 content-visibility/`.
3.  **Abre el archivo `index.html`:**
    Dentro de la carpeta de cada demostración, encontrarás un archivo `index.html`. Ábrelo directamente en tu navegador web para ver la demo en acción.

### Reutilización y Actualizaciones

Siéntete libre de revisar, experimentar y reutilizar cualquier código que encuentres en este repositorio para tus propios proyectos, ya sean personales o profesionales.

Te invito a seguirme en mis redes sociales (encuéntrame como **@moibaldenegro**) y a mantenerte atento a este repositorio, ya que se actualizará constantemente con nuevas demostraciones y ejemplos en el futuro.

### Cómo Contribuir

¡Tus contribuciones son bienvenidas! Si encuentras algún error, tienes alguna sugerencia para mejorar una demostración existente, o te gustaría proponer una nueva demo de alguna característica CSS interesante:

-   **Reporta Issues:** Por favor, utiliza la sección de "Issues" de GitHub en este repositorio para reportar cualquier problema o error que encuentres.
-   **Sugiere Nuevas Demos:** Si tienes ideas para nuevas demostraciones que podrían ser útiles, ¡no dudes en abrir un "Issue" para discutirlas!

Agradezco tu interés y participación en hacer de esta colección de demos un recurso aún mejor para la comunidad.
