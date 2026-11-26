Aqui subire todo mi proceso creativo para crear el examen ( portafolio) 
parti la clase pasada buscando referencias en pinterest y estaba un poco perdida ya que queria hacer muchas cosas y no me decidia por nada, entonces me termine decidiendo por una idea media street 

Moodboard opción 1 
### Moodboard / Referencias visuales
<img src="./figma/periferico.png" alt="Moodboard visual" width="600" />

### Boceto página completa (Diseño de productos)
<img src="./figma/MacBook%20Pro%2014_%20-%202%20(1).png" alt="Boceto diseño de productos" width="450" />
y ademas hice una estructura en figma, primera vez usando figma, lo conoci gracias a unas amigas que están en el ramo de interfaces web. 


Despues de un analisis largo me decidi por irme por algo minimalista porque no me sentia 100% convencida con la opción 1 y aqui les muestro el proceso y los detalles de todo para crear la pagina 
### Boceto portada (`ma!te`)
<img src="./figma/MacBook%20Pro%2014_%20-%203.png" alt="Boceto portada" width="600" />

### Boceto proyectos (distribución libre)
<img src="./figma/MacBook%20Pro%2014_%20-%204.png" alt="Boceto proyectos" width="600" />

Moodboard opción 2  
### Moodboard / Referencias visuales
<img src="./figma/periferico(2).png" alt="Referencias editoriales" width="600" />


## Tipografía

| Tipografía | Dónde la uso |
| :--- | :--- |
| **Inter Regular (400)** | El bloque `ma!te` de la portada: trazo fino y limpio, con tracking `-0.03em` para que se lea como una textura. |
| **Inter Black (900)** | Todos los títulos: *About me*, *Proyectos*, categorías, *pura maña*, *Contacto* y el nombre de cada proyecto (tracking `-0.02em`). |
| **Inter Medium (500)** | Textos destacados, menú y etiquetas en mayúsculas. |
| **Inter Regular (400)** | Textos de lectura, con interlineado `1.65`. |

Usé una sola familia y armé toda la jerarquía con el peso y el tamaño. Así el sitio se ve como un sistema editorial suizo y no como una mezcla de estilos.

---

## Paleta

| Color | Hex | Variable en `style.css` | Dónde lo uso |
| :--- | :--- | :--- | :--- |
| **Azul** | `#0005DC` | `--blue` | Fondo de mi retrato, títulos, letras de la portada al pasar el cursor y tarjeta activa. |
| **Negro** | `#0A0A0A` | `--ink` | Textos y bloque `ma!te`. |
| **Blanco** | `#FFFFFF` | `--bg` | Fondo de la página. |
| **Gris línea** | `#E5E5E5` | `--line` | Líneas divisorias de `1px`. |
| **Gris marco** | `#E6E6E6` | `--frame` | Marco de las fotos de los proyectos. |
| **Gris texto** | `#555555` | `--muted` | Textos secundarios. |

El azul sale de mi retrato. Lo saqué de los píxeles del fondo de mi imagen *low-poly* y es el único color de la interfaz. Lo uso solo en dos casos: **títulos** e **interacción** (cuando el cursor pasa por algo). El resto del color lo ponen los proyectos.

---

## 3. Cómo se ve y diseño

### Concepto
El sitio es editorial y minimalista: fondo blanco, una sola tipografía, mucho aire y líneas finas. Sobre esa base, cada sección tiene un gesto propio que reacciona a quien la mira, y el azul de mi retrato aparece cuando algo responde:

* **Portada:** `ma!te` repetido en filas alineadas como columnas. Las letras cercanas al cursor se encogen, se apartan y se vuelven azules.
* **About me:** mi retrato en `2.5D` se inclina hacia el cursor, y la figura sale del cuadro azul. Al pasar el cursor por encima, se deforma como un líquido.
* **Proyectos:** las tarjetas aparecen apiladas como fotos sobre una mesa y se ordenan solas en una grilla al llegar a la sección.
* **pura maña:** las piezas giran en un anillo `3D` que se puede arrastrar y lanzar.

## 01 — Diseño de Productos

| Proyecto | Materiales | Con quién lo hice | Planimetrías |
| :--- | :--- | :--- | :---: |
| **Banca Estructural** | Junquillos de madera `19 × 19 mm` | Acevedo, Lavalle y Toro | [PDF](./ruta/banca-estructural.pdf) |
| **jüko** | Junquillos de madera `19 × 19 mm`, papel de acuarela | Belén Castillo, Martina Fernández y Ma. Ignacia Zamudio | [PDF](./ruta/juko.pdf) |
| **ZETA** | Sheet metal plegado negro mate, madera | Sola | [PDF](./ruta/zeta.pdf) |
| **Golondrina Chilena** | Pino, roble, chapa de madera, impresión 3D, acrílico | Belén Castillo, Martina Fernández y Ma. Ignacia Zamudio · *convenio con Parquemet* | [PDF](./ruta/golondrina-chilena.pdf) |

## 02 — Interacción Digital

| Proyecto | Tecnologías | Demo | Código | Video |
| :--- | :--- | :---: | :---: | :---: |
| **Gestos Justin** | `Python`, `MediaPipe`, visión artificial | [ver](https://enlace-demo) | [repo](https://github.com/usuario/repo) | [sí](https://enlace-video) |
| **No solo lo intencional se nota** | `JavaScript`, `MediaPipe Hands`, `OpenCV` | [ver](https://enlace-demo) | [repo](https://github.com/usuario/repo) | [sí](https://enlace-video) |
| **Misma Tierra** | `HTML`, `CSS`, `JavaScript`, `Web Audio API` | [ver](https://enlace-demo) | [repo](https://github.com/usuario/repo) | [sí](https://enlace-video) |
| **Pesca tacto** | Sensores de movimiento, interacción táctil, `WebSockets` | [ver](https://enlace-demo) | [repo](https://github.com/usuario/repo) | [sí](https://enlace-video) |
