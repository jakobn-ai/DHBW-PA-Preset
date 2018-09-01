# DHBW-PA-Preset

A LaTeX preset for the "Praxisarbeit" at the Duale Hochschule Baden-Württemberg Mannheim, with my interpretation of the guidelines of the Technical Committee, 2016.

## Compiling

```sh
$ latexmk PA.tex
```

with XeLaTeX (already specified in the `.latexmkrc`). Target document is `PA.pdf`.

## Content

### Images

You will have to fill in the logo of the DHBW (link in document or [here](http://www.presse.dhbw-mannheim.de/fileadmin/_processed_/f/f/csm_DHBW_d_MA_46mm_RGB_300dpi_d692b56209.jpg)), the logo of your cooperating employer, and your signature; all in the `bilder` folder.

### Settings

You will have to fill in title, author, time range you worked on it, "Matrikelnummer" and course you're attending (comma in between), date you are turning it in, location, employer, mentor, and DHBW reviewer if applicable (in this case you must uncomment the line in `hilfe/Deckblatt.tex`); in `hilfe/Einstellungen.tex`.

### Restriction

If your thesis must contain a "Sperrvermerk", you have to uncomment the line in `PA.tex`.

### Registration

Save your registration (the sheet you turned in where you stated what your Praxisarbeit would contain) as `pdfs/anmeldung.pdf`.

### Abbrevations, bibliography, and glossary

Examples provided (please remove before turning in) in `inhalt/Abkuerzungen.tex`, `PA.bib`, and `inhalt/Glossar.tex`, respectively.

### Abstract

Abstract is `inhalt/Abstract.tex`.

### Main content

Some more usage examples are in `inhalt/1.tex`. You are advised to split your content into `inhalt/1.tex`, `inhalt/2.tex`, etc., and `\include` it respectively.