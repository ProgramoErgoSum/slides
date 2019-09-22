# WikiTIC Slides by @ProgramoErgoSum

Generador web de diapositivas programado en Ruby con **Jekyll** sobre GitHub Pages utilizando el framework **Reveal.js** para utilizar en presentaciones.

> Puedes ver la demo [aquí](https://wikitic.github.io/slides/).

[![](https://www.paypalobjects.com/es_ES/ES/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7N56RY2QKJJDS&source=url)

<hr />

## Instalación sobre GitHub Pages

1. Haz un fork de este [repositorio](https://github.com/wikitic/slides).
2. Modifica los contenidos según tus necesidades.
   - `_layouts/default.html` aparece los enlaces de portada y diapositivas.
   - `_includes/cover.html` portada en html.
   - `_includes/diapositivas_x.html` diapositivas en html.
3. Habilita GH-Pages sobre el repositorio de GitHub
4. Accede a la url https://[username].github.io/slides

## Instalación sobre local

1. Clona este repositiorio

```sh
$ git clone git@github.com:wikitic/slides.git
```

2. Instala docker y docker-compose en tu máquina y lanza el siguiente docker-compose

```sh
$ docker-compose build
$ docker-compose up
```



<br />



## Licencia

MIT License (MIT)

Maintaned Asociación Programo Ergo Sum
- [@migueabellan](https://github.com/migueabellan)

### Jekyll.rb

[Jekyll.rb](https://jekyllrb.com/) es un generador de páginas estáticas para la construcción de webs, principalmente utilizado como el motor de creación de todas las páginas que se sirven en [GitHub Pages](https://pages.github.com/).

### Reveal.js

[Reveal.JS](https://revealjs.com/#/) es un framework que permite crear presentaciones interactivas utilizando estándares Web y se puede utilizar libremente código HTML, CSS y JavaScript. Las presentaciones se adaptan al dispositivo en el que se visualicen.
