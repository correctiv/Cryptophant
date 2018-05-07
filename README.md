# Cryptophant

This repository contains following presentations:

* mailophant: A mail ecryption crash course for journalists
* secuphant: A more general (IT) security crash course for journalists

## to view the presentations

* checkout this repo
* change directory to the one where you checked the repo out and then to one of
  the presentation subdirectories
* checkout [revealjs](https://github.com/hakimel/reveal.js) in the same directory under the name `reveal.js`
* open the `slides.html` file in your browser

## to build the slides

* checkout this repo
* change directory to the one where you checked the repo out
* checkout [revealjs](https://github.com/hakimel/reveal.js) in the same directory under the name `reveal.js`
* edit the source of the slides: the `slides.md` file

* install [pandoc](https://github.com/jgm/pandoc/releases/)

### html slides

use `pandoc -s --mathjax -i -t revealjs slides.md -o slides.html` to convert the slides to a html presentation

### latex slides

use `pandoc -t beamer slides.md -o slides.pdf` to convert the slides to a latex beamer presentation


## color palette for the headers

[http://paletton.com/#uid=15a0u0ki9qZ86I9dcvQmFmRr6hK](http://paletton.com/#uid=15a0u0ki9qZ86I9dcvQmFmRr6hK)


## license

The slides in this repo are licensed under the Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0) License. For more detailed information, visit [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)

