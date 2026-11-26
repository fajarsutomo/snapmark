# Guía de usuario de SnapMark

SnapMark captura la pantalla de Windows y te permite anotarla con marcas que **siguen siendo editables**: rectángulos, flechas, texto, censuras y más son objetos independientes, no píxeles pintados sobre la imagen. La imagen original nunca se modifica.

[Otros idiomas / Other languages](../README.md)

## Contenido

1. [Instalación](#instalación)
2. [Capturar la pantalla](#capturar-la-pantalla)
3. [Herramientas de anotación](#herramientas-de-anotación)
4. [Atajos de teclado](#atajos-de-teclado)
5. [Copiar y guardar](#copiar-y-guardar)
6. [Proyectos e historial](#proyectos-e-historial)
7. [Ajustes](#ajustes)
8. [Privacidad](#privacidad)
9. [Solución de problemas](#solución-de-problemas)

## Instalación

Ejecuta el instalador `SnapMark_x.y.z_x64-setup.exe`. Se instala solo para tu cuenta (no requiere permisos de administrador). Después, SnapMark se ejecuta en el **área de notificación** (la zona de iconos junto al reloj, también llamada bandeja del sistema). Si no ves el icono, haz clic en la flecha ^ para mostrar los iconos ocultos.

Haz clic derecho en el icono para abrir el menú: **Capturar**, **Historial**, **Abrir proyecto…**, **Ajustes**, **Salir**.

## Capturar la pantalla

1. Pulsa **Impr Pant** (o haz clic en el icono del área de notificación, o elige **Capturar**). La pantalla se congela un instante; con varios monitores se capturan todos.
2. **Arrastra** para elegir un área. Puedes cambiarla en cualquier momento, incluso después de añadir anotaciones: arrastra su **contorno** para moverla, arrastra un **tirador** de una esquina o lado para cambiar su tamaño, o arrastra en la zona oscura exterior para elegir de nuevo. Las flechas del teclado desplazan el área; **Ctrl + flecha** cambia su tamaño; **Mayús** hace que el paso sea de 10 píxeles.
3. Usa la barra de herramientas para añadir anotaciones.
4. Pulsa **Intro** para copiar al portapapeles o **Ctrl+S** para guardar. **Esc** cancela.

El primer Esc deselecciona objetos; el siguiente cierra SnapMark.

## Herramientas de anotación

| Herramienta | Tecla | Notas |
|---|---|---|
| Seleccionar y editar | `V` | Clic en un objeto para seleccionarlo; **Mayús+clic** añade o quita de la selección. Arrastra para mover, tira de un tirador para cambiar el tamaño. |
| Rectángulo | `R` | **Mayús** = cuadrado. Puede tener relleno. |
| Elipse | `E` | **Mayús** = círculo. |
| Línea | `L` | **Mayús** = ángulos de 45°. Estilos: continua, doble, discontinua. |
| Flecha | `A` | **Mayús** = 45°. Punta en uno o ambos extremos. |
| Lápiz libre | `P` | Dibujo a mano alzada. |
| Resaltador | `H` | Marcador translúcido. |
| Censurar | `S` | Mosaico, desenfoque o **bloque negro** (el más seguro). Forma rectangular o de pincel. |
| Número de paso | `N` | Clic para colocar 1, 2, 3… en orden. |
| Texto | `T` | Elige un fondo. **Ctrl+Intro** o **Esc** termina. |

El color, el grosor, el tamaño de fuente y la negrita se ajustan en la barra de herramientas; los cambios se aplican a los objetos seleccionados.

## Atajos de teclado

| Tecla | Acción |
|---|---|
| `Intro` / `Ctrl+C` | Copiar el resultado al portapapeles |
| `Ctrl+S` | Guardar PNG en la carpeta de guardado |
| `Ctrl+Mayús+S` | Guardar como… |
| `Ctrl+Alt+S` | Guardar un proyecto `.snapmark` |
| `Ctrl+Z` / `Ctrl+Y` (o `Ctrl+Mayús+Z`) | Deshacer / rehacer |
| `Ctrl+D` | Duplicar los objetos seleccionados |
| `Ctrl+A` | Seleccionar todos los objetos |
| `Ctrl+]` / `Ctrl+[` | Traer al frente / enviar al fondo |
| `Supr` / `Retroceso` | Eliminar los objetos seleccionados |
| Flechas (`Mayús` = 10 px) | Mover los objetos seleccionados; sin selección, mover el área (con `Ctrl`: cambiar su tamaño) |
| `Esc` | Deseleccionar y luego cerrar |

## Copiar y guardar

El resultado es siempre **solo el área seleccionada**, a la **resolución original** de la pantalla, exactamente como la ves.

- **Copiar** (Intro): va al portapapeles, listo para pegar.
- **Guardar** (Ctrl+S): directo a la carpeta de guardado como `snapmark_20261125_143005.png` (fecha_hora). Los nombres existentes nunca se sobrescriben (se añade el sufijo `_2`, `_3`, …). Carpeta predeterminada: `Imágenes\SnapMark`.
- **Guardar como** (Ctrl+Mayús+S): elige tú el nombre y la carpeta.

Tras copiar o guardar correctamente, SnapMark se cierra automáticamente.

## Proyectos e historial

Un **proyecto `.snapmark`** guarda la imagen original y cada anotación como objeto, así que puedes reabrirlo y editarlo más tarde. Guarda con **Ctrl+Alt+S**; ábrelo con doble clic en el archivo o desde el área de notificación → **Abrir proyecto…**.

> **Cuidado con las censuras.** Como el archivo de proyecto conserva la imagen *original*, quien lo abra puede ver lo que censuraste. Para compartir, usa **Copiar** o **Guardar PNG**, que solo contienen el resultado ya censurado. SnapMark te avisa antes de guardar un proyecto que contiene una censura.

**Historial**: cada Copiar/Guardar se registra automáticamente como proyecto editable (los últimos 50 por defecto, solo en este equipo). Ábrelo desde el área de notificación → **Historial** y haz clic en un elemento para editarlo de nuevo.

## Ajustes

Área de notificación → **Ajustes**.

| Ajuste | Descripción |
|---|---|
| Atajo de captura | Por defecto `Impr Pant`. Haz clic en **Cambiar…** y pulsa la nueva combinación (usa Ctrl/Alt/Win para no interferir al escribir). |
| Carpeta de guardado | Destino de Ctrl+S. |
| Idioma | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, o igual que Windows. |
| Historial | Cuántos elementos se conservan (0 = desactivado, máximo 500). |
| Iniciar con Windows | SnapMark está listo en cuanto inicias sesión. |
| Color de la ayuda | Color del texto de instrucciones al elegir un área. |
| Tema | Igual que Windows, Claro, Oscuro o Liquid Glass. |
| Actualizaciones | Buscar e instalar automáticamente cada 6 horas, o pulsar **Buscar ahora**. |

Las actualizaciones se descargan de la versión oficial, se instalan sin ventana de instalador y SnapMark se reabre solo; se conservan tus ajustes y tu historial. Una actualización espera a que termines de editar.

## Privacidad

- Las capturas y los proyectos **nunca salen de tu equipo**.
- Sin telemetría. El único acceso a la red es la búsqueda de actualizaciones.

## Solución de problemas

**Impr Pant no hace nada / el atajo no está activo.** Windows 11 puede reservar esa tecla para su propia herramienta de captura. En los Ajustes de SnapMark haz clic en **Abrir ajustes de teclado de Windows** y desactiva la opción que hace que la tecla Impr Pant abra esa herramienta (su nombre y ubicación cambian según la versión de Windows). O elige otro atajo.

**Falta el icono del área de notificación.** Haz clic en la flecha ^ de la barra de tareas; arrastra el icono de SnapMark hacia fuera para que esté siempre visible.

**Dónde están los datos.** Ajustes: `%APPDATA%\app.snapmark.desktop\settings.json`. Historial: `%LOCALAPPDATA%\app.snapmark.desktop\history`.
