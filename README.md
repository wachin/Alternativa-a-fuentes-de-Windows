![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEirrN7IkvUf7w97QGE4geWEGLzqzw3PkuE0IohXXxqNAb3gaKltDEDdl0PMwVOC2vpXPBTCoi6NqVtHxAjNYnj-CfOx0CQuezkEu8R1k7w3QPciMGcuf8VI2hXRSg2rDC_ioPhNkKAuPgcBcVrIaXtjpGsBSEQnY39wPo7gUW9kw5n4Ef5UizAXOr9JOl4/s1536/Portada.jpg =640x)

# Alternativa a fuentes tipográficas privativas de microsoft

Este tutorial es para instalar fuentes gratuitas en Linux que sean una alternativa a las fuentes tipográficas privativas de microsoft, algunas de ellas se las puede encontrar en los repositorios de Linux o en Google Fonts y otros

La siguiente es una tabla donde están indicandos los usos típicos en documentos de fuentes tipográficas alternativas a las privativas de microsoft:

   
|  **Fuente de Windows**   |                                             **Alternativas no privativas**                                              |                    **Uso Común en Documentos**                     |                                      **Notas**                                       |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| **Arial**                | **Free Sans** / **Liberation Sans** / **Nimbus Sans** / **IBM plex Sans** / **Ubuntu Sans**                             | Cuerpo de texto, títulos, subtítulos                               | Fuente sans-serif estándar y versátil.                                               |
| **Times New Roman**      | **Free Serif / Liberation Serif / Nimbus Roman / IBM plex serif**                                                       | Cuerpo de texto, informes formales, libros                         | Fuente serif clásica para documentos profesionales.                                  |
| **Courier New**          | **FreeMono / Liberation Mono**                                                                                          | Código, documentos técnicos, textos monoespaciados                 | Fuente monoespaciada usada en programación y tabulación.                             |
| **Calibri**              | **Carlito** / **Lato**                                                                                                  | Cuerpo de texto, presentaciones                                    | Fuente moderna y legible.                                                            |
| **Cambria**              | **Caladea / Cambo**                                                                                                     | Cuerpo de texto, informes formales                                 | Similar a Times New Roman, con mejor legibilidad en pantalla.                        |
| **Comic Sans MS**        | **Comic Neue**                                                                                                          | Usada en textos informales, educativos y presentaciones infantiles | Comic Neue es más refinada.                                                          |
| **Verdana**              | **DejaVu Sans**                                                                                                         | Cuerpo de texto, páginas web, interfaces gráficas                  | Excelente legibilidad en pantallas.                                                  |
| **Georgia**              | **Gelasio**                                                                                                             | Cuerpo de texto, títulos de documentos                             | Fuente serif con buena legibilidad en pantalla.                                      |
| **Trebuchet MS**         | **Fira Sans**                                                                                                           | Títulos, subtítulos, presentaciones                                | Alternativa con un diseño limpio y moderno.                                          |
| **Impact**               | **Anton** / **Oswald**                                                                                                  | Títulos llamativos                                                 | Anton es una alternativa con un impacto visual fuerte.                               |
| **Tahoma**               | **Signika**                                                                                                             | Cuerpo de texto en interfaces gráficas y documentos empresariales  | Similar en espaciado y claridad.                                                     |
| **Palatino Linotype**    | **Source Serif 4**                                                                                                      | Libros, ensayos, textos académicos                                 | Basado en el diseño de Palatino.                                                     |
| **Book Antiqua**         | **P052 / C059**                                                                                                         | Cuerpo de texto en documentos elegantes o clásicos                 | Alternativas clásicas con estilo refinado.                                           |
| **Franklin Gothic Book** | **Libre Franklin**                                                                                                      | Títulos, carteles, encabezados                                     | Fuente sans-serif gruesa con estilo fuerte.                                          |
| **Century Gothic**       | **URW Gothic**                                                                                                          | Títulos modernos, diseño gráfico                                   | Diseño limpio y futurista.                                                           |
| **Rockwell**             | **Arvo**                                                                                                                | Títulos con impacto visual                                         | Alternativas de estilo slab-serif.                                                   |
| **Baskerville**          | **Goudy Bookletter 1911**                                                                                               | Cuerpo de texto en documentos clásicos y elegantes                 | Fuente con excelente legibilidad impresa.                                            |
| **Consolas**             | **JetBrains Mono** / **DejaVu Sans Mono** / **Fira Code** / **Hack** / **Iosevka** / **Victor Mono** /**Fragment Mono** | Código de programación, terminales, documentos técnicos            | Consolas es monoespaciada, sus alternativas tienen soporte para ligaduras de código. |

## Instalación de las fuentes libres desde repositorios Linux (Debian/MX Linux/Ubuntu, etc)

Instala las fuentes libres directamente desde los repositorios con este comando:

```bash
sudo apt install fonts-liberation fonts-freefont-ttf fonts-crosextra-carlito \
    fonts-crosextra-caladea fonts-dejavu fonts-cantarell fonts-firacode \
    fonts-jetbrains-mono fonts-ebgaramond fonts-ebgaramond-extra \
    fonts-hack fonts-inconsolata fonts-uralic \
    fonts-urw-base35 fonts-bpg-georgian fonts-comic-neue \
    fonts-goudybookletter fonts-ibm-plex
```

**Nota:** Para instalar el paquete fonts-ibm-plex debe estar el repositorio contrib el cual hay que [añadirlo en Debian](https://facilitarelsoftwarelibre.blogspot.com/search/label/Descargar%20Debian) si lo usas.

Entre las que se intalan, hay algunos paquetes que instalan varias fuentes con diferentes tipos y diferentes nombres:

**fonts-liberation =** Liberation Sans, Liberation Serif  
**fonts-freefont-ttf =** FreeMono  
**fonts-crosextra-carlito** = carlito  
**fonts-crosextra-caladea** = caladea  
**fonts-dejavu =** DejaVu Sans, DejaVu Sans Mono  
**fonts-cantarell =** Cantarell  
**fonts-ebgaramond =** EB Garamond (08, 12)  
**fonts-ebgaramond-extra =** EB Garamond SC (08, 12), EB Garamond 12 All SC  
**fonts-ibm-plex =** IBM Plex Sans, IBM plex Serif, IBM plex Mono  
**fonts-hack =** Hack  
**fonts-inconsolata =** Inconsolata  
**fonts-urw-base35 =** Nimbus Roman, Nimbus Sans, URW Gothic, URW Bookman, C059, P052  
**fonts-comic-neue =** Comic Neue  
**fonts-goudybookletter =** Goudy Bookletter 1911

* * *

## Fuentes alternativas desde Google Fonts

Algunas fuentes no están en los repositorios, están en este repositorio, pero puedes descargarlas manualmente desde [Google Fonts](https://fonts.google.com/):

Busca la fuente y descárgala (`.zip` con archivos `.ttf` o `.otf`).

**Nota:** Tengo un respaldo en: [https://github.com/wachin/Alternativa-a-fuentes-de-Windows](https://github.com/wachin/Alternativa-a-fuentes-de-Windows)  

**Slavo 27px → Alternativa a Rockwell**  
[https://fonts.google.com/specimen/Slabo+27px](https://fonts.google.com/specimen/Slabo+27px)

**EB Garamond → Alternativa a Garamond**  
https://fonts.google.com/specimen/EB+Garamond

**Libre Franklin → Alternativa a Franklin Gothic**  
[https://fonts.google.com/specimen/Libre+Franklin](https://fonts.google.com/specimen/Libre+Franklin)

**Oswald → Alternativa a Impact**  
[https://fonts.google.com/specimen/Oswald](https://fonts.google.com/specimen/Oswald)

**Anton → Alternativa a Impact**  
[https://fonts.google.com/specimen/Anton](https://fonts.google.com/specimen/Anton)

**Arvo → Alternativa a Rockwell**  
[https://fonts.google.com/specimen/Arvo](https://fonts.google.com/specimen/Arvo)

**Source Serif 4 → Alternativa a Georgia**  
[https://fonts.google.com/specimen/Source+Serif+4](https://fonts.google.com/specimen/Source+Serif+4)

**Lato → Alternativa a Calibri**  
[https://fonts.google.com/specimen/Lato](https://fonts.google.com/specimen/Lato)

**Cambo**  
[https://fonts.google.com/specimen/Cambo](https://fonts.google.com/specimen/Cambo)

**Fira Sans**  
[https://fonts.google.com/specimen/Fira+Sans](https://fonts.google.com/specimen/Fira+Sans)

**Victor Mono → Alternativa a Consolas**  
[https://fonts.google.com/specimen/Victor+Mono](https://fonts.google.com/specimen/Victor+Mono)

**Fragment Mono → Alternativa a Consolas**  
[https://fonts.google.com/specimen/Fragment+Mono](https://fonts.google.com/specimen/Fragment+Mono)

**Gelasio → Alternativa a Georgia**  
[https://fonts.google.com/specimen/Gelasio](https://fonts.google.com/specimen/Gelasio)

**Signika**  
[https://fonts.google.com/specimen/Signika](https://fonts.google.com/specimen/Signika)

**Iosevka → Alternativa a Consolas**  
[https://github.com/be5invis/Iosevka/releases](https://github.com/be5invis/Iosevka/releases)  
El siguiente enlace es un ejemplo del archivo zip que contiene las fuentes en .ttf:  
[https://github.com/be5invis/Iosevka/releases/download/v32.5.0/PkgTTF-Iosevka-32.5.0.zip](https://github.com/be5invis/Iosevka/releases/download/v32.5.0/PkgTTF-Iosevka-32.5.0.zip)

### Descargar estas fuetnes desde Google Fonts de una sola vez desde mi Repositorio

Si quieres descargar de una sola vez estas fuentes, las tengo en un repositorio, simplemente pon en a terminal:

```bash
mkdir ~/.fonts
cd ~/.fonts
git clone https://github.com/wachin/Alternativa-a-fuentes-de-Windows
rm -fr ~/.fonts/Alternativa-a-fuentes-de-Windows/.git
```

**Nota:** El ultimo comando "rm -fr ..." es para borrar el lugar donde está el duplicado del repositorio que gestiona los archivos en github, pues no tiene sentido que ocupe espacio allí por gusto

# Instalación de fuentes tipográficas en Linux

En muchas guías antiguas se recomienda copiar las fuentes de Windows a la carpeta personal `~/.fonts`.  
Esto **sigue siendo funcional en 2025**, pero el archivo de configuración de Fontconfig en Debian 12:

/etc/fonts/fonts.conf

indica claramente:

```bash
<dir prefix="xdg">fonts</dir>
<!-- the following element will be removed in the future -->
<dir>~/.fonts</dir>
```

![](https://blogger.googleusercontent.com/img/a/AVvXsEizJKqIR0EABs9Adxy82JnefqzQaC_4UfN0ymDV4Pqr4IkBVoDycNYVY14F4Z53rgbkbZhQaSLZYLHQ03JWPixHhGMy_Yj_A7l2B-VprbbkBPBRFCSrEeb6nMXyq7P8rppyg1SiAKSUZjpz7o-UROxj_fbfGCpWc3ZLDImXiMLUB2chSYIoc225HnlJohc=s16000-rw)

Esto significa que `~/.fonts` **será removida en el futuro**, y la ubicación recomendada según el estándar **XDG Base Directory** es:

```
~/.local/share/fonts
```

Por lo tanto, si instalas fuentes solo para tu usuario, es mejor usar esa ruta recomendada para ya ir acostumbrandose

## Instalar fuentes solo para tu usuario (sin tocar el sistema)

Para instalar fuentes tipográficas solo para tu cuenta de usuario, puedes guardarlas en la carpeta recomendada:

```
~/.local/share/fonts
```

> **Nota:** El símbolo `~` representa tu carpeta personal (por ejemplo: `/home/tuusuario/`).

### 1. Crear la carpeta automáticamente (método rápido)

Abre una terminal y escribe el siguiente comando:

```bash
mkdir -p ~/.local/share/fonts
```

Este comando crea toda la ruta necesaria.

-   La opción `-p` hace que **se creen las carpetas que falten** sin dar errores si ya existen.

### 2. Crear la carpeta manualmente (sin usar la terminal)

Si prefieres hacerlo de forma gráfica:

1.  Abre tu **administrador de archivos**.  
    
2.  Presiona `Ctrl + H` para mostrar las **carpetas ocultas** (en Linux las carpetas que empiezan con un punto `.` son ocultas).  
    
3.  Si no existe la carpeta `.local`, créala:
    
    -   Clic derecho → **Crear carpeta** → escribir `.local`  
        
4.  Dentro de `.local`, crea otra carpeta llamada `share`.  
    
5.  Dentro de `share`, crea otra carpeta llamada `fonts`.
    

La ruta final debe quedar así:

```
/home/tuusuario/.local/share/fonts
```

### 3. Copiar las fuentes

Copia todos los archivos de fuentes de Windows (`.ttf` o `.otf`) y pégalos en esa carpeta. Puedes crear subcarpetas dentro de `fonts` si quieres organizar tus fuentes (por ejemplo: `windows`, `personales`, etc.).

* * *

### Ventajas de este método

-   No necesitas permisos de administrador.
-   Las fuentes se aplican solo a tu usuario (otros usuarios del sistema no las verán).
-   Es la forma recomendada actualmente (la carpeta antigua `~/.fonts` sigue funcionando, pero está marcada para eliminarse en el futuro).

## Instalación de fuentes para todo el sistema

Si el equipo tiene **varios usuarios** y todos necesitan las fuentes de Windows, se deben instalar **para todo el sistema**.

### ¿Dónde van las fuentes del sistema?

Las fuentes del sistema en Linux se guardan en:

`/usr/share/fonts/truetype/`

Podemos crear una carpeta nueva, por ejemplo:

`/usr/share/fonts/truetype/windows`

y dentro de ella pegar todas las fuentes de Windows.

### ¿Cómo copiar las fuentes sin usar la terminal?

Para mover archivos a esa carpeta necesitamos permisos de administrador. Hay varias formas de hacerlo gráficamente:

#### 1. Usando **Krusader**

**a.)** Instalar Krusader (si no lo tiene):

```bash
sudo apt install krusader
```

**b.)** Ejecutar Krusader como superusuario:

```bash
sudo krusader
```

**c.)** Navegar a la carpeta donde tienes las fuentes de Windows y copiarlas.

**d.)** Abrir una pestaña con `"Ctrl + T"` e ir a `"/usr/share/fonts/truetype/"`, crear la carpeta `windows` y pegar allí las fuentes.  
*(También puedes hacerlo usando el otro panel en lugar de crear una pestaña).*

#### 2. Usando **Double Commander (GTK o QT)**

**a.)** Instalar Double Commander (si estuviera disponible en los repositorios):

```bash
sudo apt install doublecmd-gtk
```

o si usas KDE Plasma o LXQT:

```bash
sudo apt install doublecmd-qt
```

**b.)** Ejecutar Double Commander con permisos de superusuario:

```bash
sudo doublecmd-gtk
```

o:

```bash
sudo doublecmd-qt
```

**c.)** Copiar las fuentes a `/usr/share/fonts/truetype/windows`.

## Consejos para usar el administrador de archivos como superusuario

-   **Tenga mucho cuidado** de no borrar ni mover carpetas o archivos del sistema operativo. Si elimina o mueve algo crítico, el sistema puede dejar de funcionar y podría ser necesario reinstalarlo.
-   **No abra sus archivos personales (imágenes, documentos, etc.)** desde el administrador de archivos ejecutado como superusuario. Esto se debe a que el programa que abre esos archivos puede heredar permisos de superusuario y cambiar la propiedad de los mismos, provocando que luego no pueda acceder a ellos desde su usuario normal.
-   **Cierre el administrador de archivos cuando termine de usarlo como superusuario.** Dejarlo abierto puede ser peligroso porque, al volver más tarde y olvidar que sigue con permisos de administrador, podría borrar o mover algo importante sin darse cuenta.

## Actualizar el caché de fuentes (opcional)

Después de copiar las fuentes, se recomienda actualizar el caché de fuentes:

```bash
sudo fc-cache -fv
```

### Verificar la instalación

Abre un programa como LibreOffice, GIMP o Inkscape y revisa si aparecen las fuentes recién agregadas.

### ¿Cuándo sí se necesita `fc-cache -fv`?

1.  **Cuando instalas fuentes en directorios no estándar**, como uno que creaste manualmente o no es reconocido automáticamente.
2.  **Cuando haces scripts automatizados o instalaciones sin sesión gráfica activa**, por ejemplo en servidores o instalaciones masivas.
3.  **Cuando un programa específico no detecta la fuente nueva**, a pesar de reiniciarlo.
4.  **Cuando tienes problemas con fuentes corruptas, cache antigua o conflictos**, y necesitas regenerar toda la caché de fuentes.

### Un poco de historia

Durante mucho tiempo, el lugar “de facto” para instalar fuentes a nivel de usuario era:

-   `~/.fonts` (es decir, una carpeta `.fonts` en tu directorio personal)

Este método funcionaba bien y era el más documentado en distros como Debian, Ubuntu, etc., desde antes de 2010. Muchos tutoriales antiguos (y aún varios actuales 2025) siguen recomendando esta ruta.

* * *

### ¿Qué cambió?

A partir de las **especificaciones de XDG** (X Desktop Group), las distribuciones comenzaron a migrar a una estructura más estandarizada para los archivos de usuario. En esa estructura:

-   Los datos del usuario se almacenan en `~/.local/share/`
-   Por tanto, las **fuentes por usuario** se instalan en:

```
~/.local/share/fonts
```

Este cambio fue adoptado gradualmente, y **`fontconfig` desde versiones modernas (como la que trae Debian 12)** reconoce y monitorea automáticamente esa ruta como válida para fuentes.

## Opcional: Instalar una GUI para gestionar fuentes

Si quieres ver, activar o desactivar fuentes fácilmente, instala **Fontmatrix**:

```bash
sudo apt install fontmatrix
```

Luego ábrelo desde el menú y revisa tus fuentes instaladas.

Si las fuentes no se ven bien, debes configurar las fuentes visibles

Da clic en:

**Edit > Preferences**

Da clic en:

**Display > Default font size**

y pon ejemplo:

**10**

este número es un ejemplo y depende de cómo se vean las fuentes en tu monitor. Da clic en Close y además cierra Fontmatrix y vuelvelo a abrir y se verá el cambio

También puedes ver mi tutorial:

**Instalar FontMatrix y configurarlo en Debian 12**  
[https://facilitarelsoftwarelibre.blogspot.com/2025/02/instalar-fontmatrix-y-configurarlo-en-debian-12.html](https://facilitarelsoftwarelibre.blogspot.com/2025/02/instalar-fontmatrix-y-configurarlo-en-debian-12.html)

* * *

## Consejos adicionales

-   Si compartes documentos con usuarios de Windows sólo usa fuentes de Windows para asegurarte que se abran en otro ordenador, ejemplo cuando una persona está haciendo una tesis y debe compartir archivos con otros estudiantes, o cuando vas a hacer imprimir algún archivo de diseño gráfico como puede ser un .svg convertido en pdf y lo lleves a hacer imprimir a una imprenta. O cualquier archivo que lo vayas a habrir en otro ordenador cerciorate que la fuente esté allí también o llevala en un pendrive e instalalas en ese ordenador para que se puedan visualizar.

# Referencias

**Linux Font Equivalents to Popular Web Typefaces | Jon Christopher**  
[https://jonchristopher.us/blog/linux-font-equivalents-to-popular-web-typefaces/](https://jonchristopher.us/blog/linux-font-equivalents-to-popular-web-typefaces/)

**How do I install fonts?**  
[how-do-i-install-fonts](https://askubuntu.com/questions/3697/how-do-i-install-fonts)

**Añadir una tipografía adicional para usuarios individuales**  
[fonts-user.html.es](https://help.gnome.org/admin/system-admin-guide/stable/fonts-user.html.es)

**Font configuration (Español)**  
[Font\_configuration\_%28Español%29](https://wiki.archlinux.org/title/Font_configuration_%28Español%29)
