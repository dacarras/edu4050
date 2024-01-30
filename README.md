
# edu4050

- R library to share ILSA data examples, developed for edu4050 course
  work.

## Installation

To install the most udpdated version
[github](https://github.com/dacarras/edu4050) we can use the following
command

``` r

devtools::install_github('dacarras/edu4050',force = TRUE)
```

> Note: the present command requires to the `devtools` library. To
> install this library we can use the following command
> `install.packages('devtools')`.

# Development

## Some example of functions

- `c_mean()` calcula medias por grupo. Función incluida para crear
  centrado de variables.
- `get_sample()` genera una muestra aleatorio de datos, de un tamaño
  especificado, condicional al id number del usuario.
- `mean_score()` calcula promedio de respuesta, de un conjunto de
  variables. Sirve para generar puntajes basados en promedios.
- `sum_score()` calcula suma de respuesta, de un conjunto de variables.
  Sirve para generar puntajes basados en sumas.
- `z_score()` calcula puntaje zeta de un vector o variable.
- `reverse()` calcula el inverso de un puntaje.
- `remove_labels()` remueve la metada de una base de datos.

# Included data

- ERCE 2019

## Data description

To access a brief data description one can use the r command r
`? edu4050::[name_of_the_data]`, for example `? edu4050::erce_2019_qa6`.