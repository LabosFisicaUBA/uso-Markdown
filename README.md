# Tomar notas con Markdown

<!-- TOC -->autoauto- [Tomar notas con Markdown](#tomar-notas-con-markdown)auto    - [Qué usar](#qué-usar)auto    - [Ecuaciones](#ecuaciones)auto    - [Importar archivos](#importar-archivos)autoauto<!-- /TOC -->


## Qué usar

Esto lo hice en markdown, lo estoy probando par utilizarlo como sistema de toma de notas. Para esto simplemente se usa un editor de texto, para poder verlo derecho en el browser es necesario bajar una extensión. En el caso de firefox utilizo [Markdown Viewer Firefox](https://github.com/painyeph/GitLabMarkdownViewer)

Para el editor estoy usando el Visual Studio Code (VSC), requiere una extensión para que tome las equaciones de LaTeX directo, en particular bajé el [Markdown All in One de Yu Zhang](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one). Esta trae todo lo que se necesita para editar. Si no se quiere usar el VSC simplemente basta usar el Notepad++ y bajar extensiones para él, sin embargo encontré que el VSC tiene grandes ventajas y addons muy copados para usar. Además trae un preview incluido que permite ir viendo lo que sale directo en la pantalla.

Además le metí el [Markdown preview enhase](https://shd101wyy.github.io/markdown-preview-enhanced/#/) Mejora la salida del archivo.

Finalmente me di cuenta que el [markdown extension pack](https://marketplace.visualstudio.com/items?itemName=bat67.markdown-extension-pack#review-details) trae todo, en particular exportar a PDF, meter fácil las imágenes y demases. En particular incluye los dos packs anteriores, por lo cual instalar este directo ya mete todo. 


## Ecuaciones

Para meter ecuaciones simplemente se usa latex
`$$ \alpha = \frac{e^2}{4\pi\varepsilon_0\hbar c} = \frac{\mu_0 e^2 c}{4 \pi \hbar} = \frac{c \mu_0}{2 R_K} = \frac{1}{137} $$` :

$$ \alpha = \frac{e^2}{4\pi\varepsilon_0\hbar c} = \frac{\mu_0 e^2 c}{4 \pi \hbar} = \frac{c \mu_0}{2 R_K} = \frac{1}{137}
$$

## Importar archivos

`@import "/figures/prueba dibujo 01.jpg"`

@import "/figures/prueba dibujo 01.jpg"




