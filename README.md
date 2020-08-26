# DHBW-PA-Preset

A LaTeX preset for the "Praxisarbeit" at the Duale Hochschule Baden-Württemberg Mannheim, with my interpretation of the guidelines of the Technical Committee, 2016.

## Compiling

```sh
$ latexmk PA.tex
```

with XeLaTeX (already specified in the `.latexmkrc`). Target document is `PA.pdf`.

## Content

### Images

You will have to fill in the logo of the DHBW (link in document or [here](https://upload.wikimedia.org/wikipedia/commons/0/01/DHBW_MA_Logo.jpg)), the logo of your cooperating employer, and your signature; all in the `img` folder.

### Settings

You will have to fill in title, author, time range you worked on it, "Matrikelnummer", course you're attending, date you are turning it in, location, employer, supervisor, and DHBW evaluator; in `aux/settings.tex`.

### Restriction

If your thesis must contain a "Sperrvermerk", you have to uncomment the line in `PA.tex`.

### Registration

Save your registration (the sheet you turned in where you stated what your Praxisarbeit would contain) as `pdfs/registration.pdf`.

### Abbrevations, bibliography, and glossary

Examples provided (please remove before turning in) in `contents/abbrevs.tex`, `PA.bib`, and `contents/glossary.tex`, respectively.

### Abstract

Abstract is `contents/abstracts.tex`.

### Main content

Some more usage examples are in `contents/1.tex`. You are advised to split your content into `contents/1.tex`, `contents/2.tex`, etc., and `\include` it respectively.
