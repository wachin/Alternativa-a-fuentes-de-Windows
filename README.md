
![](vx_images/Front_Page.jpg)
# Alternative to proprietary Microsoft fonts

This tutorial explains how to install free fonts on Linux that can be used as alternatives to proprietary Microsoft fonts. Some of them can be found in Linux repositories, Google Fonts, and other sources.

The following table lists typical document uses for free alternatives to proprietary Microsoft fonts:

   
|  **Windows Font**        |                                             **Non-Proprietary Alternatives**                                             |                    **Common Use in Documents**                     |                                      **Notes**                                       |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| **Arial**                | **Free Sans** / **Liberation Sans** / **Nimbus Sans** / **IBM Plex Sans** / **Ubuntu Sans**                             | Body text, headings, subheadings                                   | Standard and versatile sans-serif font.                                              |
| **Times New Roman**      | **Free Serif / Liberation Serif / Nimbus Roman / IBM Plex Serif**                                                       | Body text, formal reports, books                                   | Classic serif font for professional documents.                                       |
| **Courier New**          | **FreeMono / Liberation Mono**                                                                                          | Code, technical documents, monospaced text                         | Monospaced font used in programming and tabular text.                                 |
| **Calibri**              | **Carlito** / **Lato**                                                                                                  | Body text, presentations                                           | Modern and readable font.                                                            |
| **Cambria**              | **Caladea / Cambo**                                                                                                     | Body text, formal reports                                          | Similar to Times New Roman, with better on-screen readability.                       |
| **Comic Sans MS**        | **Comic Neue**                                                                                                          | Informal, educational, and children's presentation text             | Comic Neue is more refined.                                                          |
| **Verdana**              | **DejaVu Sans**                                                                                                         | Body text, web pages, graphical interfaces                         | Excellent screen readability.                                                        |
| **Georgia**              | **Gelasio**                                                                                                             | Body text, document headings                                       | Serif font with good screen readability.                                             |
| **Trebuchet MS**         | **Fira Sans**                                                                                                           | Headings, subheadings, presentations                               | Alternative with a clean, modern design.                                             |
| **Impact**               | **Anton** / **Oswald**                                                                                                  | Eye-catching headings                                              | Anton is an alternative with strong visual impact.                                   |
| **Tahoma**               | **Signika**                                                                                                             | Body text in graphical interfaces and business documents            | Similar spacing and clarity.                                                         |
| **Palatino Linotype**    | **Source Serif 4**                                                                                                      | Books, essays, academic texts                                      | Based on the Palatino design.                                                        |
| **Book Antiqua**         | **P052 / C059**                                                                                                         | Body text in elegant or classic documents                          | Classic alternatives with a refined style.                                           |
| **Franklin Gothic Book** | **Libre Franklin**                                                                                                      | Headings, posters, headers                                         | Heavy sans-serif font with a strong style.                                           |
| **Century Gothic**       | **URW Gothic**                                                                                                          | Modern headings, graphic design                                    | Clean and futuristic design.                                                         |
| **Rockwell**             | **Arvo**                                                                                                                | Headings with visual impact                                        | Slab-serif style alternatives.                                                       |
| **Baskerville**          | **Goudy Bookletter 1911**                                                                                               | Body text in classic and elegant documents                         | Font with excellent print readability.                                               |
| **Consolas**             | **JetBrains Mono** / **DejaVu Sans Mono** / **Fira Code** / **Hack** / **Iosevka** / **Victor Mono** / **Fragment Mono** | Programming code, terminals, technical documents                   | Consolas is monospaced; its alternatives support code ligatures.                     |

## Installing free fonts from Linux repositories (Debian/MX Linux/Ubuntu, etc.)

Install the free fonts directly from the repositories with this command:

```bash
sudo apt install fonts-liberation fonts-freefont-ttf fonts-crosextra-carlito \
    fonts-crosextra-caladea fonts-dejavu fonts-cantarell fonts-firacode \
    fonts-jetbrains-mono fonts-ebgaramond fonts-ebgaramond-extra \
    fonts-hack fonts-inconsolata fonts-uralic \
    fonts-urw-base35 fonts-bpg-georgian fonts-comic-neue \
    fonts-goudybookletter fonts-ibm-plex
```

**Note:** To install the `fonts-ibm-plex` package, the `contrib` repository must be enabled. If you use Debian, you need to [add it](https://facilitarelsoftwarelibre.blogspot.com/search/label/Descargar%20Debian).

Among the installed packages, some install several fonts with different types and names:

**fonts-liberation =** Liberation Sans, Liberation Serif  
**fonts-freefont-ttf =** FreeMono  
**fonts-crosextra-carlito** = Carlito  
**fonts-crosextra-caladea** = Caladea  
**fonts-dejavu =** DejaVu Sans, DejaVu Sans Mono  
**fonts-cantarell =** Cantarell  
**fonts-ebgaramond =** EB Garamond (08, 12)  
**fonts-ebgaramond-extra =** EB Garamond SC (08, 12), EB Garamond 12 All SC  
**fonts-ibm-plex =** IBM Plex Sans, IBM Plex Serif, IBM Plex Mono  
**fonts-hack =** Hack  
**fonts-inconsolata =** Inconsolata  
**fonts-urw-base35 =** Nimbus Roman, Nimbus Sans, URW Gothic, URW Bookman, C059, P052  
**fonts-comic-neue =** Comic Neue  
**fonts-goudybookletter =** Goudy Bookletter 1911

* * *

## Alternative fonts from Google Fonts

Some fonts are not in the repositories. They are in this repository, but you can also download them manually from [Google Fonts](https://fonts.google.com/):

Search for the font and download it (`.zip` with `.ttf` or `.otf` files).

**Note:** I have a backup at: [https://github.com/wachin/Alternativa-a-fuentes-de-Windows](https://github.com/wachin/Alternativa-a-fuentes-de-Windows)  

**Slabo 27px -> Alternative to Rockwell**  
[https://fonts.google.com/specimen/Slabo+27px](https://fonts.google.com/specimen/Slabo+27px)

**EB Garamond -> Alternative to Garamond**  
https://fonts.google.com/specimen/EB+Garamond

**Libre Franklin -> Alternative to Franklin Gothic**  
[https://fonts.google.com/specimen/Libre+Franklin](https://fonts.google.com/specimen/Libre+Franklin)

**Oswald -> Alternative to Impact**  
[https://fonts.google.com/specimen/Oswald](https://fonts.google.com/specimen/Oswald)

**Anton -> Alternative to Impact**  
[https://fonts.google.com/specimen/Anton](https://fonts.google.com/specimen/Anton)

**Arvo -> Alternative to Rockwell**  
[https://fonts.google.com/specimen/Arvo](https://fonts.google.com/specimen/Arvo)

**Source Serif 4 -> Alternative to Georgia**  
[https://fonts.google.com/specimen/Source+Serif+4](https://fonts.google.com/specimen/Source+Serif+4)

**Lato -> Alternative to Calibri**  
[https://fonts.google.com/specimen/Lato](https://fonts.google.com/specimen/Lato)

**Cambo**  
[https://fonts.google.com/specimen/Cambo](https://fonts.google.com/specimen/Cambo)

**Fira Sans**  
[https://fonts.google.com/specimen/Fira+Sans](https://fonts.google.com/specimen/Fira+Sans)

**Victor Mono -> Alternative to Consolas**  
[https://fonts.google.com/specimen/Victor+Mono](https://fonts.google.com/specimen/Victor+Mono)

**Fragment Mono -> Alternative to Consolas**  
[https://fonts.google.com/specimen/Fragment+Mono](https://fonts.google.com/specimen/Fragment+Mono)

**Gelasio -> Alternative to Georgia**  
[https://fonts.google.com/specimen/Gelasio](https://fonts.google.com/specimen/Gelasio)

**Signika**  
[https://fonts.google.com/specimen/Signika](https://fonts.google.com/specimen/Signika)

**Iosevka -> Alternative to Consolas**  
[https://github.com/be5invis/Iosevka/releases](https://github.com/be5invis/Iosevka/releases)  
The following link is an example of a zip file that contains the fonts in `.ttf` format:  
[https://github.com/be5invis/Iosevka/releases/download/v32.5.0/PkgTTF-Iosevka-32.5.0.zip](https://github.com/be5invis/Iosevka/releases/download/v32.5.0/PkgTTF-Iosevka-32.5.0.zip)

### Download these fonts from Google Fonts all at once from my repository

If you want to download all these fonts at once, I have them in a repository. Just enter this in the terminal:

```bash
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts
git clone https://github.com/wachin/Alternativa-a-fuentes-de-Windows
rm -fr ~/.local/share/fonts/Alternativa-a-fuentes-de-Windows/.git
```

**Note:** The last command, `rm -fr ...`, deletes the duplicated repository metadata that manages the files on GitHub, because there is no point in wasting space there unnecessarily.

# Installing fonts in Linux

Many old guides recommend copying Windows fonts to the personal `~/.fonts` folder.  
This **still works in 2025**, but the Fontconfig configuration file in Debian 12:

/etc/fonts/fonts.conf

clearly states:

```bash
<dir prefix="xdg">fonts</dir>
<!-- the following element will be removed in the future -->
<dir>~/.fonts</dir>
```

![](https://blogger.googleusercontent.com/img/a/AVvXsEizJKqIR0EABs9Adxy82JnefqzQaC_4UfN0ymDV4Pqr4IkBVoDycNYVY14F4Z53rgbkbZhQaSLZYLHQ03JWPixHhGMy_Yj_A7l2B-VprbbkBPBRFCSrEeb6nMXyq7P8rppyg1SiAKSUZjpz7o-UROxj_fbfGCpWc3ZLDImXiMLUB2chSYIoc225HnlJohc=s16000-rw)

This means that `~/.fonts` **will be removed in the future**, and the recommended location according to the **XDG Base Directory** standard is:

```
~/.local/share/fonts
```

Therefore, if you install fonts only for your user, it is better to use that recommended path and start getting used to it.

## Install fonts only for your user (without touching the system)

To install fonts only for your user account, you can save them in the recommended folder:

```
~/.local/share/fonts
```

> **Note:** The `~` symbol represents your home folder, for example: `/home/youruser/`.

### 1. Create the folder automatically (quick method)

Open a terminal and type the following command:

```bash
mkdir -p ~/.local/share/fonts
```

This command creates the entire required path.

-   The `-p` option makes it **create any missing folders** without throwing errors if they already exist.

### 2. Create the folder manually (without using the terminal)

If you prefer to do it graphically:

1.  Open your **file manager**.  
    
2.  Press `Ctrl + H` to show **hidden folders** (in Linux, folders that start with a dot `.` are hidden).  
    
3.  If the `.local` folder does not exist, create it:
    
    -   Right click -> **Create Folder** -> type `.local`  
        
4.  Inside `.local`, create another folder called `share`.  
    
5.  Inside `share`, create another folder called `fonts`.
    

The final path should look like this:

```
/home/youruser/.local/share/fonts
```

### 3. Copy the fonts

Copy all Windows font files (`.ttf` or `.otf`) and paste them into that folder. You can create subfolders inside `fonts` if you want to organize your fonts, for example: `windows`, `personal`, etc.

* * *

### Advantages of this method

-   You do not need administrator permissions.
-   The fonts apply only to your user (other system users will not see them).
-   It is the currently recommended method (the old `~/.fonts` folder still works, but it is marked for removal in the future).

## System-wide font installation

If the computer has **several users** and everyone needs the Windows fonts, they should be installed **system-wide**.

### Where do system fonts go?

System fonts in Linux are stored in:

`/usr/share/fonts/truetype/`

We can create a new folder, for example:

`/usr/share/fonts/truetype/windows`

and paste all Windows fonts inside it.

### How to copy fonts without using the terminal

To move files into that folder, we need administrator permissions. There are several ways to do it graphically:

#### 1. Using **Krusader**

**a.)** Install Krusader (if you do not have it):

```bash
sudo apt install krusader
```

**b.)** Run Krusader as superuser:

```bash
sudo krusader
```

**c.)** Go to the folder where you have the Windows fonts and copy them.

**d.)** Open a tab with `"Ctrl + T"` and go to `"/usr/share/fonts/truetype/"`, create the `windows` folder, and paste the fonts there.  
*(You can also do this using the other panel instead of creating a tab.)*

#### 2. Using **Double Commander (GTK or QT)**

**a.)** Install Double Commander (if it is available in the repositories):

```bash
sudo apt install doublecmd-gtk
```

or if you use KDE Plasma or LXQT:

```bash
sudo apt install doublecmd-qt
```

**b.)** Run Double Commander with superuser permissions:

```bash
sudo doublecmd-gtk
```

or:

```bash
sudo doublecmd-qt
```

**c.)** Copy the fonts to `/usr/share/fonts/truetype/windows`.

## Tips for using the file manager as superuser

-   **Be very careful** not to delete or move operating system folders or files. If you delete or move something critical, the system may stop working and you may need to reinstall it.
-   **Do not open your personal files (images, documents, etc.)** from the file manager running as superuser. This is because the program that opens those files may inherit superuser permissions and change their ownership, causing you to lose access to them from your normal user.
-   **Close the file manager when you finish using it as superuser.** Leaving it open can be dangerous because, if you come back later and forget that it still has administrator permissions, you could delete or move something important without realizing it.

## Update the font cache (optional)

After copying the fonts, it is recommended to update the font cache:

```bash
sudo fc-cache -fv
```

### Verify the installation

Open a program such as LibreOffice, GIMP, or Inkscape and check whether the newly added fonts appear.

### When is `fc-cache -fv` actually needed?

1.  **When you install fonts in non-standard directories**, such as one you created manually or one that is not detected automatically.
2.  **When you use automated scripts or installations without an active graphical session**, for example on servers or mass installations.
3.  **When a specific program does not detect the new font**, even after restarting it.
4.  **When you have problems with corrupt fonts, an old cache, or conflicts**, and need to regenerate the entire font cache.

### A bit of history

For a long time, the de facto location for installing fonts at the user level was:

-   `~/.fonts` (that is, a `.fonts` folder in your home directory)

This method worked well and was the most documented one in distributions such as Debian, Ubuntu, etc., since before 2010. Many old tutorials (and even several current ones in 2025) still recommend this path.

* * *

### What changed?

Starting with the **XDG specifications** (X Desktop Group), distributions began migrating to a more standardized structure for user files. In that structure:

-   User data is stored in `~/.local/share/`
-   Therefore, **per-user fonts** are installed in:

```
~/.local/share/fonts
```

This change was adopted gradually, and **`fontconfig` in modern versions (such as the one included with Debian 12)** automatically recognizes and monitors that path as valid for fonts.

## Optional: Install a GUI to manage fonts

If you want to view, enable, or disable fonts easily, install **Fontmatrix**:

```bash
sudo apt install fontmatrix
```

**Note:** I am trying to improve this program at [fontmatrix](https://github.com/wachin/fontmatrix)

Then open it from the menu and check your installed fonts.

If the fonts do not look right, you need to configure the visible fonts.

Click:

**Edit > Preferences**

Click:

**Display > Default font size**

and set, for example:

**10**

This number is only an example and depends on how the fonts look on your monitor. Click Close, then close Fontmatrix and open it again so the change takes effect.

You can also see my tutorial:

**Install FontMatrix and configure it on Debian 12**  
[https://facilitarelsoftwarelibre.blogspot.com/2025/02/instalar-fontmatrix-y-configurarlo-en-debian-12.html](https://facilitarelsoftwarelibre.blogspot.com/2025/02/instalar-fontmatrix-y-configurarlo-en-debian-12.html)

* * *

## Additional tips

-   If you share documents with Windows users, use only Windows fonts to make sure they open correctly on another computer. For example, this matters when someone is writing a thesis and needs to share files with other students, or when you are going to print a graphic design file, such as an `.svg` converted to PDF, at a print shop. For any file that you are going to open on another computer, make sure the font is there too, or take it on a USB flash drive and install it on that computer so it can be displayed.

# References

**Linux Font Equivalents to Popular Web Typefaces | Jon Christopher**  
[https://jonchristopher.us/blog/linux-font-equivalents-to-popular-web-typefaces/](https://jonchristopher.us/blog/linux-font-equivalents-to-popular-web-typefaces/)

**How do I install fonts?**  
[how-do-i-install-fonts](https://askubuntu.com/questions/3697/how-do-i-install-fonts)

**Add an extra font for individual users**  
[fonts-user.html](https://help.gnome.org/admin/system-admin-guide/stable/fonts-user.html)

**Font configuration**  
[Font_configuration](https://wiki.archlinux.org/title/Font_configuration)
