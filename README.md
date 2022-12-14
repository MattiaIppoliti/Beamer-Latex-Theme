# Beamer-LaTeX-Theme

Hi👋

Here are some beamer templates which are secondary creations of [SINTEF Presentation](https://www.overleaf.com/latex/templates/sintef-presentation/jhbhdffczpnx) template. Thanks [Federico Zenith](federico.zenith@sintef.no) for creating such tasted and well-designed works. To use it in my and my friends' schools/organizations, I rewrote and added some icons and features to adapt to specific surroundings✨.

All templates have been submitted to [Gallery - Overleaf](https://cs.overleaf.com/gallery), please check them here👇

- [Politecnico di Torino - Beamer Latex Presentation](https://www.overleaf.com/latex/templates/politecnico-di-torino-presentation/cnypkdbdyqky)

> Noted that if you'd like to include Chinese text, please use XeLaTeX for typesetting.

Below shows some examples:

## Title Pages for Schools/Organizations
- Politecnico di Torino 
![Politecnico di Torino](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_main.jpg)

- Master School - Politecnico di Torino
![Master Politecnico di Torino](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_master.jpg)

## Page Elements

- Table of Contents

  At the beginning of each section, the table of contents will be shown with the current chapter highlighted.
![toc](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_index.jpg)
- Sub-section page
![ssec](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_two_sides.jpg)
- Math equation
![math](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_math.jpg)
- Code block
![code](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_code.jpg)
- End page
![end](https://github.com/MattiaIppoliti/Beamer-Latex-Theme/blob/main/img/screen_last.jpg)

## Make Your Own Theme?

Would like to make your own theme on top of these themes? It's quite easy, only a few steps are needed:

### Step 1: Get the files

To get the files, you can fork & clone the repository to your computer.

Alternatively, you can open the templates' Overleaf webpages and click `Open as Template`.

### Step 2: Replace icon pictures

The `assets/` folder stores the icon pictures.  The `logo_RGB.png` is the icon picture shown on the contents pages & end page, both on the left-top corner.

You can replace them with your own icons, noted that the pictures' file names should be the same as the original ones, otherwise the theme doesn't know how to find your icons.

For those who open the template on Overleaf, please click the `Upload` button on the top-left corner to upload your icon pictures, and replace the original icon files in the `images/` folder.

### Step 3: Replace background picture

The `images/` folder also stores the background picture, which is `background.png`. You can fell free to replace it in the same way as Step 2.

### Step 4: Change the main colour

To optimize the visual appearance, it's recommended to change the main colour, which will be used as the colour of titles and backgrounds. The 7-th line of `sintefcolor.sty` file defines the main colour:
```
\definecolor{maincolor}{RGB/cmyk}{0,53,118/100,55,0,54}
```
Assuming that the RGB value of the new main colour is `(0,53,118)` and the cmyk is ``(0,53,118/100,55,0,54)`, just rewrite the last 3 values in the code as:
```
\definecolor{maincolor}{RGB/cmyk}{0,53,118/100,55,0,54}
```
Moreover, if you want to change the size and the logo of the assets, you can use the Figma file `Polito_figma.png`!

Now you have your brand new template 👏🎉

## Issues & Suggestions

If you have any revision suggestions, please create an issue in this repository. Thanks indeed🤝
