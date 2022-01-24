### CENTRAR TEXTO Markdown
En realidad, puede usar el modo de reducción para la celda y usar el código HTML normal.

<h1><center>Centered text!</center></h1>

no directamente con Markdown, pero puede ingresar HTML en las celdas de Markdown

<h3 align="center">This is a centered header</h3> 

Sabiendo que en las celdas de marcado del cuaderno jupyter (ipython) el nivel del título se identifica por el número de # (# para encabezados de nivel superior o h1, ## para h2, ....), uso la siguiente combinación de HTML y markdown:

# <center>Your centered level h1 title

## <center>Your centered level h2 title


### INSERTAR IMAGEN en JupyterNotebook

IMAGEN INSERTAR HTML mode:
  ![Imagen] (link)
INSERTAR IMAGEN local mode:
  ![title](direccion/picture.png)


