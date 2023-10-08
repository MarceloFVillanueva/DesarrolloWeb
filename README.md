# DesarrolloWeb
Curso de HTML y CSS de Coder House


Padre - contenedor
Hijos - items dentro

display: avisa al padre que tipo es / flex (flexibles, en una dirección), grid (maquetas, en dos direcciones), ....
        
# Clase 5 - Flex

    Manipulación flexible en una dirección, fila o columna.

    * Comandos útiles:
        Propiedades del padre:
            - flex-direction: elije dirección para acomodar / row (fila), row-reverse , column (columna), column-reverse
            - flex-wrap: si llega al límite que hace? / nowrap (mantiene a todos en la misma fila), wrap (cuando los hijos comienzan a deformarse los acomoda en una nueva línea)
            - flex-flow: es flex-direction y flex-wrap en una misma fila
        
        Propiedades de los hijos:
        - justify-content: alínea los elementos en horizontal / flex-start, center, flex-end, space-between, space-around, space-evenly
        - align-items: alínea los elementos en vertical / flex-start, center, flex-end, stretch, baseline
        - align-content: lo mismo que aling-items sólo que se aplica cuando hay varias filas / stretch, flex-start, center, flex-end, space-between, space-around, space-evenly
        - order: le asigna un valor de ubicación al hijo. Todos los hijos comienzan con un orden de 0, si se pone a un hijo -1 pasa a una posición a la izquierda de los hijos 0

# Clase 6 - Grid

    Manipulación en 2 direcciones, fila y columna. Se trabaja en cuadrículas
    
    * Comandos útiles:

        Propiedades del padre:
            - grid-template-columns: tamaño de cada  columna
            - grid-template-rows: tamaño de cada fila
            - grid-template-areas: disposición de las áreas en el grid
            - column-gap: tamaño de los huecos entre columnas
            - row-gap: tamaño de los huevos entre filas
        
        Propiedades de los hijos:
            - justify-items: alínea en forma horizontal / start, end, center, stretch, space-around, space-between, space-evenly
            - align-items: alínea en forma vertical / start, end, center, stretch, space-around, space-between, space-evenly
            - justify-self: alínea específicamente la celda de forma horizontal / start, end, center, stretch
            - align-self: alínea especificamente la celda de forma vertical / star, end, center, stretch
            - grid-area: le asigna un nombre para manipularlo en grid-template-areas

    * Datos extras:
        - px: pixeles / medida fija
        - fr: fracción / del total del padre, se divide la columnas indicadas y se fracciona entre ellas la cant indicada. 3fr 1fr (2 columnas, la primera el triple de la segunda) 
        - %: porcentaje / del total del padre, un porcentaje de ese tamañano.
        - auto: automático / rellena el tamaño al tamaño total no indicado del padre
        - vh: view high / ancho de la pantalla
        - vw: view with / alto de la pantalla

# Clase 7 - RESPONSIVE, MEDIA QUERies

    * Media Queries: Es un condicional, mayormente se lo usa para condicionar con el tamaño de ancho de la pantalla, es la apertura a modelo responsive.
    Forma de usar
    
    ***************** CSS ***********************
    .miestilo{
        background-color: blue;
    }

    @media (max-width: 480px){
        .background-color: brown;
    }
    *********************************************

    * Datos extras:
        - display: none; elimina la etiqueta
        - Breakpoints de mediaQueries:
            - Móvil pequeño: 360 x 640 px.
            - Móvil medio: 375 x 667 px.
            - Smartphone grande: 720 x 1280 px.
            - Ordenador portátil medio: 1366 x 768 px.
            - Ordenador de escritorio medio: 1440 x 900 px.
            - PC de escritorio grande: 1920 x 1080 px.