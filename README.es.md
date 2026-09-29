# WorldView

**Visor de imágenes gratuito para Windows que permite ver imágenes, archivos comprimidos y documentos PDF de forma rápida y cómoda.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.3-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/worldview?lang=es)

![Pantalla de WorldView](images/worldview-ko.webp)

## Descripción general

WorldView permite hojear carpetas llenas de fotos, leer cómics comprimidos a doble página sin descomprimirlos y recorrer webtoons como una sola tira continua. Los documentos PDF se abren de la misma manera, página a página.

Arrastre una imagen a la ventana y se abrirá al instante, con las demás imágenes de la misma carpeta a continuación. En pantalla solo se ve la imagen; los botones aparecen únicamente cuando acerca el ratón al borde superior o inferior de la ventana.

La tarjeta gráfica se encarga del dibujo, así que incluso las fotos grandes se amplían con suavidad, y las páginas anterior y siguiente se leen por adelantado para que pasar de página casi nunca haga esperar.

## Funciones principales

- **Muchos formatos de imagen** — JPEG, PNG, GIF, WebP, TIFF, BMP, SVG, JPEG XL, HEIC, AVIF, PSD, RAW de cámara y más.
- **Archivos comprimidos sin descomprimir** — Pase una a una las imágenes de archivos ZIP, RAR, 7Z, CBZ, CBR, EGG, ALZ, etc.
- **Documentos PDF** — Cada página es una imagen; al ampliar, la página se vuelve a dibujar a ese tamaño para que el texto se vea nítido.
- **Cuatro modos de vista** — Una página, dos páginas (izq.→der. / der.→izq.), primera página como portada y webtoon continuo.
- **Imágenes animadas** — Reproduce GIF, APNG y WebP animados.
- **Giro automático y corrección de color** — Las fotos tomadas en vertical se abren derechas, y las que tienen perfil de color se ven con sus colores reales.
- **Zoom y navegador** — Amplía alrededor del cursor; cuando la imagen no cabe, el navegador de la esquina inferior derecha le lleva a cualquier punto.
- **Información de la imagen y EXIF** — Pulse `Tab` una vez para ver los datos del archivo y la fecha de toma, la cámara, el objetivo y la exposición.
- **Funciones prácticas** — Asociaciones de archivos, pantalla completa, siempre visible, archivos recientes, continuar donde lo dejó, eliminar a la Papelera y atajos personalizables.
- **8 idiomas** — Coreano · inglés · japonés · chino · ruso · italiano · francés · español.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/worldview?lang=es) |
| Portátil (ZIP) | [Descargar](https://down.kilho.net/worldview?lang=es&nosetup) |

El instalador abre WorldView en cuanto termina la instalación. Para la versión portátil, descomprima el ZIP y ejecute `WorldView.exe` — la carpeta `vendor` debe quedar junto al ejecutable. La configuración se guarda en la carpeta del programa, así que si lleva la versión portátil en una memoria USB, su configuración viaja con ella.

Ninguna de las dos versiones crea asociaciones de archivos por sí sola. Para abrir las imágenes en WorldView con doble clic, actívelas en **Configuración → Asociaciones** (vea «Qué hacer cuando…» más abajo).

## Uso

### Primeros pasos

1. Ejecute WorldView y arrastre a la ventana un archivo de imagen, una carpeta, un archivo comprimido o un PDF. También puede elegir un archivo con el botón de carpeta de la barra inferior o con la tecla `O`.
2. La imagen se abre ajustada a la ventana, y las demás imágenes de la misma carpeta forman una lista por orden de nombre. El título superior muestra dónde está, por ejemplo `Carpeta > Nombre de archivo [69/308]`.
3. Gire la rueda del ratón o pulse `←` `→` · `PageUp` `PageDown` para ir a la página anterior o siguiente. También puede hacer clic en los botones de flecha que aparecen al acercar el ratón a los lados izquierdo y derecho de la ventana.
4. Acerque el ratón al borde inferior para mostrar la barra inferior. Tiene botones de zoom, giro y página, y una barra de navegación: arrástrela para ir directamente a cualquier página.
5. Con el botón **Ver** a la derecha de la barra inferior elija el zoom (ajustar a la ventana, tamaño original, ancho, alto) y el modo de vista (una página, dos páginas, webtoon). Su elección se recuerda para la página siguiente y el próximo inicio.
6. Haga **clic derecho** en cualquier parte de la ventana para ver el menú: Abrir archivo, Archivos recientes, Mostrar en el Explorador, Eliminar archivo y Configuración.

### Distribución de la pantalla

**Barra superior** (aparece al acercar el ratón al borde superior)

| Elemento | Función |
|---|---|
| Icono de la aplicación | Abre el mismo menú que el clic derecho |
| Título | Carpeta > nombre de archivo [página actual/total]. Se añade `Cargando` en las páginas que tardan |
| Chincheta | Activa o desactiva **Siempre visible** |
| Minimizar · `[]` · Cerrar | `[]` alterna la pantalla completa |

**Barra inferior** (aparece al acercar el ratón al borde inferior)

| Botón | Función |
|---|---|
| Carpeta | Abrir un archivo |
| `+` · `−` | Acercar · alejar |
| Girar | Girar 90 grados a la derecha |
| `‹` · `›` | Página anterior · página siguiente |
| Barra de navegación | Arrastrar o hacer clic para ir a cualquier página |
| Ver | El menú Ver — zoom, dos páginas, portada, webtoon |
| Engranaje | Configuración |

**Menú del clic derecho**

| Elemento | Función |
|---|---|
| **Abrir archivo** · **Abrir carpeta** | Elegir un archivo o una carpeta para abrir |
| **Archivos recientes** | Los 5 últimos elementos abiertos |
| **Mostrar en el Explorador** | Abre el Explorador con el archivo actual seleccionado |
| **Ver** | El mismo menú que el botón Ver de la barra inferior |
| **Eliminar archivo** | Envía el archivo actual a la Papelera |
| **Acerca de WorldView** · **Configuración** · **Salir** | Página del programa · ventana de configuración · salir |

**Configuración** — Los cambios se aplican al instante; no hay botón `Aceptar`. **Restablecer**, abajo a la izquierda, devuelve todos los ajustes a sus valores predeterminados y quita también las asociaciones de archivos.

| Página | Elementos |
|---|---|
| **General** | Salir con la tecla Esc · Confirmar antes de eliminar · Reabrir el último archivo al iniciar · Siempre visible · Registro · Idioma |
| **Vista** | Zoom · Modo de vista · Primera página como portada · Páginas anchas solas · Barras de desplazamiento · EXIF en la info · Mostrar navegador · Botones de flecha laterales · En el primer/último archivo |
| **Asociaciones** | Extensiones que se abren en WorldView con doble clic |
| **Atajos** | Cambiar la tecla de cada acción |

### Qué hacer cuando…

**Quiere pasar las fotos de una carpeta**
Arrastre o haga doble clic en una foto y las imágenes de esa carpeta formarán una lista por orden de nombre. Los números se ordenan como números, así que `foto2.jpg` va antes que `foto10.jpg`. Pase páginas con la rueda · `←` `→` · `PageUp` `PageDown` · `Space`, y vaya a la primera y a la última con `Home` `End`.

**Quiere leer un cómic comprimido sin descomprimirlo**
Arrastre tal cual un archivo ZIP · RAR · 7Z · CBZ · CBR y las imágenes que contiene se pasan una a una. Sin descomprimir y sin carpetas temporales. Las carpetas internas del archivo se muestran seguidas, por orden de nombre.

**Quiere leer toda una carpeta de biblioteca**
Arrastre una carpeta: WorldView recorre todas las subcarpetas, despliega página a página los archivos comprimidos y PDF que contienen y forma una sola lista. Puede leer de principio a fin sin abrir cada tomo por separado.

**Quiere elegir varios elementos y ver solo esos**
Seleccione varios archivos, carpetas o archivos comprimidos en el Explorador y arrástrelos juntos: solo su selección forma la lista. Los archivos vecinos que no eligió quedan fuera.

**Quiere leer cómics a doble página**
Elija **Ver** → **Dos páginas (izq.→der.)** para mostrar dos páginas juntas como un libro. Para el manga japonés, que se lee de derecha a izquierda, elija **Dos páginas (der.→izq.)**. Aunque el número de páginas sea impar, la última conserva su mitad en lugar de agrandarse de repente.

**La portada descuadra los pares**
Si la página 1 es una portada y cada doble página aparece desplazada una página, active **1.ª página como portada**. La portada queda sola y luego las páginas se emparejan como 2-3, 4-5, etc.

**Cómics con ilustraciones a doble página**
Active **Páginas anchas solas**: una imagen ancha escaneada como dos páginas se muestra sola y en grande, mientras el resto sigue emparejándose de dos en dos.

**Quiere leer un webtoon como una tira continua**
Active **Ver** → **Webtoon (continuo)** y todas las páginas se unen en vertical al ancho de la ventana, así que solo tiene que seguir desplazándose. Arrastre la barra de desplazamiento de la derecha para saltar a cualquier punto de toda la tira.

**Una sola imagen muy alta**
Una imagen más de tres veces más alta que ancha se abre ajustada al ancho, **empezando por arriba**. Baje con la rueda · `↑` `↓` · `Space`; al llegar al final no salta a la página siguiente, así que nunca pierde el punto de lectura. Pase a la página siguiente con `PageDown` o con el botón de flecha. `Ctrl`+`Home` / `Ctrl`+`End` van directamente al principio o al final de esa imagen.

**Quiere leer un PDF página a página**
Arrastre un PDF y cada página se pasa como una imagen. También puede abrirlo como un libro con la vista de dos páginas o recorrerlo con la vista webtoon. Al ampliar o agrandar la ventana, la página se vuelve a dibujar a ese tamaño, por lo que la letra pequeña se ve nítida, y el fondo blanco la mantiene legible incluso con un tema oscuro.

**Quiere ampliar una foto grande para ver los detalles**
`Ctrl`+rueda acerca y aleja **alrededor del cursor**. También sirven las teclas `+` `-` y los botones inferiores. Arrastre la imagen ampliada para moverla y use `Shift`+rueda para moverla en horizontal. Cuando la imagen es mayor que la ventana, aparece el **navegador** en la esquina inferior derecha, que marca con un rectángulo la parte que está viendo; haga clic o arrástrelo para ir allí directamente. Al ampliar se vuelve a leer el original, así que los detalles finos se mantienen nítidos.

**Quiere ocultar el navegador**
Pase el ratón sobre el navegador y haga clic en la X que aparece. Para volver a mostrarlo, active **Configuración → Vista → Mostrar navegador**.

**Quiere cambiar el zoom rápidamente**
`1` ajustar a la ventana, `2` tamaño original, `3` ajustar al ancho, `4` ajustar a la altura. El zoom elegido se mantiene en la página siguiente y en el próximo inicio: elíjalo una vez para leer siempre los escaneos anchos ajustados al ancho, o para ver siempre las fotos a tamaño original.

**Quiere ver los datos de la toma de una foto**
Pulse `Tab` para mostrar arriba a la izquierda el nombre de archivo · el tamaño de archivo · la fecha de modificación · los datos de la imagen. Si la foto tiene datos EXIF, también aparecen la fecha de toma · la cámara · el objetivo · la exposición · la distancia focal · el flash · la ubicación (GPS), solo las líneas que tienen valor. En la vista de dos páginas, cada página muestra su información en su mitad. Pulse `Tab` de nuevo para ocultarla.

**Quiere abrir fotos de iPhone (HEIC), RAW de cámara o archivos de Photoshop**
HEIC · AVIF · JPEG XL, los RAW de Canon · Nikon · Sony · Olympus · Pentax · Panasonic y los archivos PSD de Photoshop se abren como cualquier otra imagen al arrastrarlos. Las fotos se abren en la orientación en que se tomaron, y se aplican los perfiles de color incrustados para mostrar sus colores reales.

**Quiere ver GIF y WebP animados**
Abra un GIF · APNG · WebP animado en la vista de una página y se reproducirá. Las vistas de dos páginas y webtoon muestran solo el primer fotograma.

**Quiere ordenar sus fotos mientras las ve**
Pulse `Delete` en una foto que no quiera; aparece una confirmación y **Sí** la envía a la Papelera. No se borra para siempre: puede recuperarla desde la Papelera. Si la confirmación le estorba, desactive **Configuración → General → Confirmar antes de eliminar**. Solo funciona con archivos de carpetas; las imágenes dentro de archivos comprimidos no se tocan.

**Quiere seguir donde lo dejó**
Solo tiene que ejecutar WorldView y se vuelven a abrir la lista y la página que estaba viendo la última vez; un cómic sin terminar continúa desde esa página. Los 5 últimos elementos abiertos están en clic derecho → **Archivos recientes**. Si prefiere empezar con una ventana vacía, desactive **Reabrir el último archivo al iniciar**.

**Quiere disfrutar a pantalla completa**
Pulse `Enter` o haga clic en `[]` en la barra de título para una pantalla completa que cubre también la barra de tareas. Pulse `Esc` o `Enter` para volver. En pantalla completa, `Esc` nunca cierra el programa: solo sale de la pantalla completa.

**Quiere tenerlo encima como referencia**
Haga clic en la chincheta de la barra de título para activar **Siempre visible**, y WorldView seguirá a la vista mientras trabaja en otros programas: útil para dibujar a partir de una referencia o tener un documento junto a su trabajo.

**Quiere comparar dos imágenes lado a lado**
Ejecute otro WorldView y la nueva ventana se abrirá ligeramente desplazada para no tapar la primera. Coloque las ventanas una junto a otra para comparar.

**Quiere volver al principio tras la última página**
De forma predeterminada, al pasar de la última página se detiene y muestra `Esta es la última imagen`. Para recorrerlas en bucle como una presentación, cambie **Configuración → Vista → En el primer/último archivo** a **Volver al inicio**.

**Quiere que las imágenes se abran en WorldView con doble clic**
En **Configuración → Asociaciones**, marque las extensiones que quiere abrir con WorldView (también hay **Seleccionar todo**). Puede elegir JPG · PNG · GIF · WebP · TIFF · BMP · TGA · PSD · JPEG 2000 · DDS · PCX · PDF · CBZ · CBR, y las extensiones del mismo formato (`.jpg` `.jpeg` `.jfif`) comparten una casilla. Si aparece **Sin aplicar** junto a una casilla, Windows está dando prioridad a otro programa: haga clic en esa etiqueta para abrir la selección de app predeterminada de esa extensión y elija WorldView. Al desinstalar WorldView, las asociaciones vuelven a su estado original.

**Quiere adaptar los atajos a su gusto**
En **Configuración → Atajos**, haga clic en la casilla de tecla de una acción y pulse la tecla nueva. Funcionan las combinaciones con `Ctrl` · `Shift` · `Alt`. `Backspace` restablece el valor predeterminado y `Esc` cancela. Una tecla que ya usa otra acción se rechaza, y se indica qué acción la usa.

| Acción | Tecla predeterminada |
|---|---|
| Ajustar a la ventana · Tamaño original · Ajustar al ancho · Ajustar a la altura | `1` · `2` · `3` · `4` |
| Girar 90 grados a la derecha | `R` |
| Mostrar/ocultar la información de la imagen | `Tab` |
| Alternar pantalla completa | `Enter` |
| Abrir un archivo · Abrir una carpeta | `O` · `Ctrl`+`O` |

Página anterior/siguiente (`PageUp` `PageDown`), primera/última página (`Home` `End`), acercar/alejar (`+` `-`), Papelera (`Delete`) y las teclas de flecha · `Space` · `Esc` son fijas.

**Quiere mover la ventana o cambiar su tamaño**
Arrastre una zona vacía fuera de la imagen, o una imagen ajustada a la ventana, para mover la ventana; arrastre un borde para cambiar su tamaño. Arrastrar con el botón central del ratón también mueve la ventana. La posición y el tamaño de la ventana se recuerdan, y se abre en el mismo sitio la próxima vez.

**Quiere saber dónde está el archivo actual**
Clic derecho → **Mostrar en el Explorador** abre el Explorador con ese archivo seleccionado, útil para cambiarle el nombre o copiarlo.

**Quiere una pantalla más limpia**
En **Configuración → Vista**, desactive **Barras de desplazamiento** y **Botones de flecha laterales** para reducir lo que aparece sobre la imagen. Seguirá pudiendo moverse y pasar páginas igual con la rueda · las flechas · arrastrando.

## Configuración

Los cambios hechos en **Configuración**, y el zoom y el modo de vista elegidos en el menú Ver, se guardan automáticamente y se usan de nuevo en el próximo inicio.

| Elemento | Valor predeterminado |
|---|---|
| Zoom | Ventana |
| Modo de vista | Una página |
| Primera página como portada · Páginas anchas solas | Inactivo |
| Barras de desplazamiento · Navegador · Botones de flecha laterales · EXIF en la info | Activo |
| En el primer/último archivo | Detenerse |
| Salir con la tecla Esc · Confirmar antes de eliminar | Activo |
| Reabrir el último archivo al iniciar | Activo |
| Siempre visible · Registro | Inactivo |
| Idioma | Sistema (sigue la configuración regional de Windows; inglés si el idioma no está disponible) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Incluye todo lo necesario para abrir las imágenes; no hay que instalar nada más. No necesita permisos de administrador para ejecutarse.
- La conexión a Internet solo se usa para avisar de nuevas versiones. Todas las imágenes se abren en su PC.

## Actualizaciones

WorldView **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al hacer clic en **[Sí]** abre la página de descarga y cierra el programa. Las versiones nuevas se publican manualmente tras pruebas internas y se anuncian en la [página de WorldView](https://kilho.net/worldview). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

**Historial de versiones**

| Versión | Fecha | Cambios |
|---|---|---|
| 0.9.3 | 2026-09-24 | Configuración rehecha con un motor de interfaz propio, entrada de atajos y pantalla de configuración más ágiles, navegador añadido, información EXIF, zoom y modo de vista recordados, mejor vista a tamaño original, varias ventanas ya no se tapan entre sí, abrir PDF directamente con WorldView |
| 0.9.2 | 2026-09-18 | Modo de vista y zoom guardados automáticamente, ajuste de una página/dos páginas/webtoon y portada en Configuración, menú Ver mejorado, Ver añadido al menú del clic derecho, asociaciones de PDF · TIFF ampliadas y formatos iguales agrupados |
| 0.9.1 | 2026-09-14 | Compatibilidad con imágenes JFIF, ventanas de selección de archivo y de confirmación de borrado mejoradas |
| 0.9.0 | 2026-09-12 | Primera versión |

## Licencia

WorldView es **freeware**. Puede usarlo gratis y sin restricciones en cualquier lugar —en la empresa, en casa, en organismos públicos o en centros educativos— y redistribuirlo libremente.

## Enlaces

- Sitio web: <https://kilho.net/worldview>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
