# Kalmuri

**Herramienta de captura gratuita para Windows: captura la pantalla completa, una región, una ventana o una página web entera con una sola tecla de acceso rápido, y graba la pantalla en MP4.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kalmuri?lang=es)

![Pantalla de Kalmuri](images/kalmuri-en.webp)

## Descripción general

Con Kalmuri solo elige dos cosas —qué capturar (**Capturar**) y cómo guardarlo (**Guardar en**)— y a partir de ahí basta con pulsar `PrintScreen`. No hay que abrir ninguna ventana ni escribir un nombre de archivo cada vez: los resultados se acumulan en la carpeta de guardado como `K-001.png`, `K-002.png`, etc.

Puede capturar toda la pantalla, una región fija, una zona que arrastre con el ratón, la ventana que está usando, un solo botón dentro de una ventana o una página web entera con desplazamiento. Con el mismo atajo también puede grabar la pantalla en MP4, tomar códigos de color de la pantalla y convertir en archivo de texto el texto de una imagen.

Al cerrar la ventana, Kalmuri sigue funcionando en el área de notificación (bandeja del sistema), así que una vez abierto puede capturar en cualquier momento con el atajo.

## Funciones principales

- **7 modos de captura** — Pantalla completa, región fija, zona arrastrada, ventana activa, control de ventana, página web entera y selector de color.
- **Muchos tipos de salida** — Archivos PNG · JPG · GIF · BMP · WebP, vídeo MP4, reconocimiento de texto (TXT), portapapeles, compartir imágenes, impresora e imagen flotante en pantalla.
- **Grabación de pantalla** — Grabe la pantalla completa o una región en MP4, con el sonido que se reproduce en su PC si lo desea.
- **Captura de página web entera** — Guarde una página abierta en Edge · Chrome como una sola imagen, hasta el final del desplazamiento.
- **Reconocimiento de texto (OCR)** — Guarde el texto de la pantalla capturada en un archivo de texto.
- **Selector de color** — Copie el color bajo el cursor en formato HEX · RGB · Web · TColor.
- **Compartir capturas** — Suba una captura a la web y ábrala al momento para compartir el enlace.
- **Flotante** — Mantenga una imagen capturada encima de las demás ventanas, justo donde se capturó, como referencia.
- **Ajuste de la región con el teclado** — Ajuste la región al píxel con las flechas · `Ctrl`+flecha · `Shift`+flecha.
- **Ajustes prácticos** — Atajo personalizable, formato del nombre de archivo (numeración · fecha y hora), sonido de captura, incluir el cursor, ejecutar al iniciar el sistema.
- **8 idiomas** — Coreano · inglés · japonés · chino · ruso · italiano · francés · español.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/kalmuri?lang=es) |
| Portátil (ZIP) | [Descargar](https://down.kilho.net/kalmuri?lang=es&nosetup) |

El instalador abre Kalmuri en cuanto termina la instalación y activa **Ejecutar al iniciar el sistema**, de modo que Kalmuri se inicia en la bandeja cada vez que arranca Windows. Para la versión portátil, descomprima el ZIP y ejecute `Kalmuri.exe`.

La versión portátil solo contiene el ejecutable, por lo que **la grabación MP4 y el guardado en WebP solo están disponibles en la versión instalada**. Todo lo demás es igual en ambas.

## Uso

### Primeros pasos

1. Ejecute Kalmuri. Se abre una ventana pequeña y aparece el icono de Kalmuri en el área de notificación.
2. En **Capturar**, elija qué capturar. Por defecto es **Pantalla completa**.
3. En **Guardar en**, elija cómo guardarlo. Por defecto es **PNG**. Al elegir JPG · WebP aparece al lado una casilla de calidad; al elegir TXT, una casilla de idioma de reconocimiento.
4. Pulse `PrintScreen`. Con un sonido de obturador, la captura se guarda en la carpeta de guardado (al principio, el escritorio) como `K-001.png`.
5. Haga clic en **Abrir carpeta** para abrir la carpeta de guardado y ver el resultado.
6. Al cerrar la ventana, Kalmuri sigue activo en la bandeja. Haga clic en el icono para volver a mostrar la ventana, y haga **clic derecho** en la ventana o en el icono para el menú de ajustes.

### Distribución de la pantalla

**Ventana principal**

| Elemento | Función |
|---|---|
| **Capturar** | Elegir qué capturar (tabla de abajo) |
| **Guardar en** | Elegir cómo guardar la captura (tabla de abajo). JPG · WebP muestran una casilla de calidad (100 – 60) y TXT una de idioma de reconocimiento |
| **Abrir carpeta** | Abre la carpeta de guardado en el Explorador |
| **Creado por Kilho** | Abre la página de presentación de Kalmuri |

**Capturar**

| Elemento | Qué captura |
|---|---|
| **Pantalla completa** | Toda la pantalla |
| **Región definida** | El interior de una ventana con marco rojo — para capturar siempre el mismo lugar y tamaño |
| **Región de arrastre** | La parte que arrastre con el ratón después de pulsar el atajo |
| **Ventana activa** | La ventana que está usando |
| **Control de Ventana** | La ventana o el elemento (botón, panel…) bajo el cursor |
| **Navegador web** | Toda la página web que ve en Edge · Chrome, hasta el final del desplazamiento |
| **Selector de color** | El código de color bajo el cursor |

**Guardar en**

| Elemento | Resultado |
|---|---|
| **PNG** · **JPG** · **GIF** · **BMP** · **WebP** | Un archivo de imagen en ese formato |
| **Vídeo(MP4)** | Grabación de pantalla (solo Pantalla completa · Región definida) |
| **TXT** | Reconoce el texto de la pantalla capturada y lo guarda en un archivo de texto |
| **Portapapeles** | Copia solo al portapapeles, sin archivo |
| **Subir Imgbox** | Sube la imagen a la web y abre su página en el navegador |
| **Impresora** | Imprime al momento |
| **Flotante** | Mantiene la imagen encima de todo, donde se capturó |

**Menú del clic derecho** (ventana principal o icono de la bandeja)

| Elemento | Función |
|---|---|
| **Abrir almacén de imágenes** · **Establecer Almacén de imágenes** | Abrir o cambiar la carpeta de guardado |
| **Configuración de captura** | **Capturar sonido** (Ninguno · Antes de capturar · Después de la captura) · **Cursor del mouse** · **Con portapapeles** |
| **Configuración del grabador** | **Limitar tiempo de grabación** (Ilimitado · 30 minutos · 1 hora · 2 horas · 4 horas) · **Cursor del mouse** · **Incluir sonido** |
| **Idioma** | Idioma de la interfaz |
| **Configuración de nombre de archivo** | **Número de incremento automático #1** · **Número de incremento automático #2** · **Fecha y Hora** |
| **Configuración de teclas de acceso rápido** | Cambiar el atajo de captura |
| **Ejecutar al iniciar el sistema** | Iniciar automáticamente en la bandeja al arrancar Windows |
| **Creado por Kilho** · **Salir** | Página de presentación · cerrar el programa |

### Qué hacer cuando…

**Quiere capturar toda la pantalla de una vez**
Deje **Capturar** en **Pantalla completa** y pulse `PrintScreen`. No hace falta abrir la ventana: mientras Kalmuri esté en la bandeja, captura desde cualquier sitio.

**Quiere capturar siempre el mismo lugar y tamaño**
Elija **Región definida** y aparece una ventana con un marco rojo parpadeante. Arrastre el marco para moverlo y sus bordes para cambiar el tamaño; luego pulse `PrintScreen` para capturar solo lo que hay **dentro** del marco. El tamaño actual (p. ej. `480x360`) se muestra en la parte superior del marco, y su posición y tamaño se recuerdan para la próxima vez. La X de arriba a la derecha cierra el marco y vuelve a **Pantalla completa**.

**Quiere ajustar la región al píxel**
Haga clic en el marco de la región y use el teclado. Las flechas lo **mueven** 1 píxel; `Ctrl`+flecha **cambia su tamaño** 10 píxeles y `Shift`+flecha 1 píxel. Ajústelo a grandes rasgos con el ratón y termine con el teclado.

**Quiere guardar los tamaños que usa a menudo**
Con un clic derecho en el marco aparece una lista de tamaños como `320x240` · `640x480` · `720x480` para cambiar con un clic. Cambie esos tamaños en **Configuración** escribiendo el ancho y el alto de **Personalizado #1 – #3**. Escriba valores en **Estado actual** y pulse **Aplicar** para dar ese tamaño a la región actual. **Ocultar**, en el mismo menú, solo oculta el marco por ahora.

**Quiere elegir con el ratón solo la parte que necesita**
Elija **Región de arrastre** y pulse `PrintScreen`: la pantalla se congela y se oscurece. Arrastre sobre la parte que quiere capturar y suelte para guardar solo esa parte. `Esc` cancela. Como se captura el instante congelado, puede atrapar incluso un menú abierto o una notificación que aparece solo un momento.

**Quiere capturar solo la ventana que está usando**
Elija **Ventana activa**, haga clic en la ventana para traerla al frente y pulse `PrintScreen`. El escritorio y las demás ventanas quedan fuera; solo se guarda esa ventana.

**Quiere capturar un solo botón o panel de una ventana**
Elija **Control de Ventana** y un marco punteado sigue al elemento bajo el cursor. Coloque el cursor sobre el botón, campo o panel que quiera y pulse `PrintScreen` para guardar solo el elemento enmarcado: práctico para recortar una sola parte para un manual o una consulta de soporte.

**Quiere guardar una página web larga en una sola imagen**
Elija **Navegador web** y Kalmuri abre una ventana de Edge aparte (Chrome si no hay Edge). Abra en ella la página que quiera y pulse `PrintScreen`: toda la página, incluida la parte que habría que desplazar para ver, se guarda como una sola imagen. Con varias pestañas abiertas, se captura la pestaña que está viendo. Al cerrar esa ventana del navegador se vuelve a **Pantalla completa**. Requiere Windows 8 o posterior con Edge o Chrome instalado.

**Quiere saber el código de color de algo en pantalla**
Elija **Selector de color** y la ventana muestra en tiempo real el color y el código bajo el cursor. Coloque el cursor donde quiera y pulse `PrintScreen`: ese color se añade al principio de la lista y se copia al portapapeles. Con un clic derecho en la lista → **Formato** elija el formato de copia —**HEX** (`FF9933`) · **RGB** (`255, 153, 51`) · **Web** (`#FF9933`) · **TColor** (`$003399FF`)— y use **Copiar** · **Eliminar** del mismo menú para ordenar la lista.

**Quiere grabar la pantalla en vídeo**
Ponga **Guardar en** en **Vídeo(MP4)** y pulse `PrintScreen` para empezar a grabar; la ventana muestra **Grabando** y el tiempo transcurrido. Pulse `PrintScreen` otra vez para detener la grabación y guardar el archivo MP4. La grabación funciona con **Pantalla completa** y **Región definida**; al grabar una región, `[REC]` y el tiempo aparecen sobre el marco y la región queda fija.

**Quiere grabar también el sonido del PC**
Active **Configuración del grabador → Incluir sonido** para grabar, junto con la imagen, el sonido que se reproduce en su PC (vídeos, juegos, notificaciones). Actívelo al grabar una clase o la reproducción de un vídeo.

**Quiere dejar una grabación en marcha mientras no está**
Ponga **Configuración del grabador → Limitar tiempo de grabación** en **30 minutos** · **1 hora** · **2 horas** · **4 horas** y la grabación se detendrá sola al pasar ese tiempo: se acabó llenar el disco por olvidarse de pararla.

**Quiere quitar el cursor de las grabaciones**
Desactive **Configuración del grabador → Cursor del mouse** para ocultar el cursor en los vídeos. Es independiente de **Configuración de captura → Cursor del mouse** para las capturas, así que puede dejar el cursor fuera de las capturas y mantenerlo en las grabaciones, o al revés.

**Quiere convertir el texto de una imagen en texto**
Ponga **Guardar en** en **TXT** y aparecerá al lado una casilla de idioma de reconocimiento. Elija el idioma del texto y capture: el texto de la pantalla se lee y se guarda en un archivo de texto (`K-001.txt`). Ideal para texto en imágenes o documentos que no se pueden copiar. Combínelo con **Región de arrastre** para reconocer solo el párrafo que necesita. La lista de idiomas muestra los idiomas de reconocimiento de texto instalados en Windows.

**Quiere pegar una captura en otro sitio al momento**
Ponga **Guardar en** en **Portapapeles** para copiar la captura solo al portapapeles, sin crear un archivo, y pegarla en un chat o documento con `Ctrl`+`V`. Para guardar un archivo y además poder pegar, active **Configuración de captura → Con portapapeles**: guarde en el formato que guarde, la captura también se copia al portapapeles.

**Quiere compartir una captura con un enlace**
Ponga **Guardar en** en **Subir Imgbox** y capture: la imagen se sube a la web y su página se abre en el navegador. Copie la dirección y envíela para compartir la captura sin adjuntar archivos.

**Quiere imprimir en cuanto captura**
Ponga **Guardar en** en **Impresora** y la captura se imprime al momento en la impresora predeterminada.

**Quiere tener una captura en pantalla como referencia**
Ponga **Guardar en** en **Flotante** y capture: una imagen del mismo tamaño queda encima de las demás ventanas, justo donde capturó. Arrástrela para moverla: útil para copiar valores o comparar dos pantallas. Con un clic derecho en la imagen → **Guardar imagen** se guarda como PNG · JPG · GIF · BMP · WebP, y **Eliminar flotante** · **Eliminar todos los flotantes** la cierran.

**Quiere archivos más pequeños**
Ponga **Guardar en** en **JPG** o **WebP** y elija 100 · 90 · 80 · 70 · 60 en la casilla de calidad de al lado (90 por defecto). Cuanto menor el número, más pequeño el archivo. PNG va bien para pantallas con mucho texto; JPG · WebP para pantallas con muchas fotos.

**Quiere cambiar la regla de nombres de archivo**
Elija en **Configuración de nombre de archivo**.
- **Número de incremento automático #1** (predeterminado) — continúa a partir del número más alto de la carpeta de guardado (`K-001`, `K-002` …).
- **Número de incremento automático #2** — rellena desde el número libre más bajo. Si borró un archivo intermedio, su número se vuelve a usar.
- **Fecha y Hora** — nombra los archivos según la hora de captura (`K-20260928-153012345`). Útil para ordenar cronológicamente capturas de varios días.

Sea cual sea la regla, si ya existe un archivo con el mismo nombre, no se sobrescribe: la captura se guarda con un nombre nuevo.

**Quiere cambiar la carpeta de guardado**
Elija una carpeta con **Establecer Almacén de imágenes**. Por defecto es el escritorio. **Abrir almacén de imágenes** (o **Abrir carpeta** en la ventana) abre esa carpeta en cualquier momento.

**Quiere cambiar el atajo**
En **Configuración de teclas de acceso rápido**, marque `Ctrl` · `Alt` · `Shift`, elija una tecla y pulse **Aceptar**. Puede elegir `PrintScreen`, `A` – `Z`, `0` – `9`, `F1` – `F12` o `DEL`. Si otro programa ya usa esa combinación, se le avisará: elija otra.

**`PrintScreen` abre la Herramienta Recortes de Windows**
Windows 11 tiene un ajuste que hace que `PrintScreen` abra la Herramienta Recortes. Kalmuri desactiva ese ajuste al iniciarse para que `PrintScreen` funcione con Kalmuri.

**Quiere cambiar el sonido de captura**
En **Configuración de captura → Capturar sonido**, elija **Ninguno** · **Antes de capturar** (predeterminado) · **Después de la captura**. **Ninguno** va bien en lugares silenciosos; **Después de la captura** le indica con un sonido que el guardado ha terminado.

**Quiere incluir o quitar el cursor**
Con **Configuración de captura → Cursor del mouse** activado (predeterminado), el cursor aparece en las capturas. Déjelo activado para capturas que señalan un botón; desactívelo para una pantalla limpia.

**Quiere tenerlo listo cada vez que arranca Windows**
Con **Ejecutar al iniciar el sistema** activado, Kalmuri se inicia en la bandeja sin ventana al arrancar Windows, listo para el atajo. En la versión instalada ya viene activado.

**Quiere seguir usándolo tras cerrar la ventana, o salir del todo**
La X de la ventana no cierra Kalmuri: lo oculta en la bandeja. Para salir por completo, pulse **Salir** en el menú del clic derecho y confirme. Si hay una grabación en curso, deténgala primero y luego salga.

**Quiere cambiar el idioma de la interfaz**
Elija 한국어 · English · 日本語 · 中文 · Русский · Italiano · Français · Español en **Idioma** y cambia al instante.

### Aviso sobre derechos de autor

Las pantallas que capture o grabe con Kalmuri pueden contener textos, imágenes, vídeos o música de otras personas. Compartirlas o publicarlas más allá del archivo y la consulta personal puede requerir el permiso del titular de los derechos, así que respete las condiciones de uso de cada servicio y la ley de propiedad intelectual.

## Configuración

Cada ajuste se guarda en cuanto lo cambia y se vuelve a usar en el próximo inicio.

| Elemento | Valor predeterminado |
|---|---|
| Capturar | Pantalla completa |
| Guardar en | PNG |
| Calidad JPG · WebP | 90 |
| Carpeta de guardado | Escritorio |
| Configuración de nombre de archivo | Número de incremento automático #1 |
| Atajo | `PrintScreen` |
| Capturar sonido | Antes de capturar |
| Cursor del mouse (captura · grabación) | Activado |
| Con portapapeles | Desactivado |
| Limitar tiempo de grabación | Ilimitado |
| Incluir sonido | Desactivado |
| Ejecutar al iniciar el sistema | Activado en la versión instalada |
| Idioma | Sigue la configuración regional de Windows (inglés si el idioma no está disponible) |

## Requisitos

- Windows 10 · Windows 11
- La captura **Navegador web** necesita Microsoft Edge o Google Chrome.
- **TXT** (reconocimiento de texto) usa los idiomas de reconocimiento de texto instalados en Windows.
- La conexión a Internet solo se usa para avisar de nuevas versiones, **Subir Imgbox** y la captura **Navegador web**.

## Actualizaciones

Kalmuri **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al hacer clic en **[Sí]** abre la página de descarga y cierra el programa. Las versiones nuevas se publican manualmente tras pruebas internas y se anuncian en la [página de Kalmuri](https://kilho.net/kalmuri). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

## Licencia

Kalmuri es **freeware**. Puede usarlo gratis y sin restricciones en cualquier lugar —en la empresa, en casa, en organismos públicos o en centros educativos— y redistribuirlo libremente.

## Enlaces

- Sitio web: <https://kilho.net/kalmuri>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
