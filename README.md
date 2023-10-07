# DesarrolloWeb
Curso de HTML y CSS de Coder House

# Clase 5 - Flex

    Padre - contenedor
    Hijos - items dentro

    comandos útiles:
        - display: avisa al padre que tipo es / flex (flexibles, en una dirección), grid (maquetas, en dos direcciones), ....
        - flex-direction: elije dirección para acomodar / row (fila), row-reverse , column (columna), column-reverse
        - flex-wrap: si llega al límite que hace? / nowrap (mantiene a todos en la misma fila), wrap (cuando los hijos comienzan a deformarse los acomoda en una nueva línea)
        - flex-flow: es flex-direction y flex-wrap en una misma fila

        - justify-content: alinea los elementos en horizontal / flex-start, center, flex-end, space-between, space-around, space-evenly
        - aling-items: alínea los elementos en vertical / flex-start, center, flex-end, stretch, baseline
        - aling-content: lo mismo que aling-items sólo que se aplica cuando hay varias filas / stretch, flex-start, center, flex-end, space-between, space-around, space-evenly
        - order: le asigna un valor de ubicación al hijo. Todos los hijos comienzan con un orden de 0, si se pone a un hijo -1 pasa a una posición a la izquierda de los hijos 0