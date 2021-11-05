
<!-- README.md is generated from README.Rmd. Please edit that file -->

# proyectosANID

<!-- badges: start -->
<!-- badges: end -->

El objetivo del paquete proyectosANID es proveer acceso a los datos y
herramientas accesorias para la exploración y visualización de los datos
históricos de adjudicación de proyectos de ANID.

## Instalación

Puedes instalar la versión de desarrollo de proyectosANID directamente
desde [GitHub](https://github.com/) con:

``` r
# install.packages("devtools")
devtools::install_github("SEREMICTCI/proyectosANID")
```

## Datos

Para acceder a los datos del paquete, solo tienes que cargar el paquete
de la siguiente forma

``` r
library(proyectosANID)
```

Y luego llamar a la base de datos de la siguiente manera:

``` r
proyectosanid
```

Para ver la documentación de los datos basta con escribir esto en tu
consola de `R`:

``` r
help(proyectosanid)
```

Para citar este paquete puedes escribir lo siguiente en tu consola de
`R`:

``` r
citation("proyectosANID")
#> 
#> To cite package 'proyectosANID' in publications use:
#> 
#>   Matías Castillo Aguilar and Carlos Morales Quiroz (2021).
#>   proyectosANID: Proyectos Histórico ANID. R package version
#>   0.0.0.9000. https://github.com/matcasti/proyectosANID
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {proyectosANID: Proyectos Histórico ANID},
#>     author = {Matías {Castillo Aguilar} and Carlos {Morales Quiroz}},
#>     year = {2021},
#>     note = {R package version 0.0.0.9000},
#>     url = {https://github.com/matcasti/proyectosANID},
#>   }
```
