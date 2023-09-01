## Display Flex
 
 Es una propiedad de CSS que se utiliza para crear un contenedor flexible (flex container) que organiza sus elementos hijos (flex items) en una disposición flexible. Esta propiedad es parte del modelo de diseño flexible (Flexbox) en CSS, que permite crear diseños complejos y ajustables de manera más sencilla que con los métodos tradicionales de diseño.

Al utilizar `display: flex`, el contenedor padre se convierte en un contenedor flexible, y los elementos hijos dentro de él se convierten en elementos flexibles. Esto permite controlar el flujo y la distribución de los elementos hijos en el contenedor de acuerdo con las propiedades flexibles definidas.

Algunas propiedades clave que se utilizan junto con `display: flex` incluyen:

1. `flex-direction`: Determina la dirección principal en la que los elementos flexibles se distribuyen en el contenedor. Puede ser "row" (fila), "column" (columna), "row-reverse" (fila inversa) o "column-reverse" (columna inversa).
    
2. `flex-wrap`: Controla si los elementos flexibles deben envolverse en múltiples líneas o no cuando no caben en una sola línea. Puede ser "nowrap" (sin envoltura), "wrap" (envoltura) o "wrap-reverse" (envoltura inversa).
    
3. `justify-content`: Alinea los elementos a lo largo del eje principal del contenedor. Puede ser "flex-start" (inicio), "flex-end" (fin), "center" (centro), "space-between" (espaciado entre), "space-around" (espaciado alrededor) o "space-evenly" (espaciado equitativo).
    
4. `align-items`: Alinea los elementos a lo largo del eje secundario del contenedor. Puede ser "flex-start", "flex-end", "center", "baseline" (línea base) o "stretch" (estirar).
    
5. `align-content`: Controla la alineación de varias líneas de elementos flexibles cuando hay espacio adicional en el eje secundario. Funciona de manera similar a `justify-content` pero en el eje secundario.
    

`display: flex` y el modelo Flexbox en general ofrecen una manera poderosa y flexible de crear diseños responsivos y complejos en CSS, ajustándose automáticamente a diferentes tamaños de pantalla y dispositivos.

## Display Grid

Es una propiedad de CSS que se utiliza para crear un sistema de diseño basado en una cuadrícula. Permite dividir un contenedor en filas y columnas, y luego colocar los elementos hijos en celdas específicas de esa cuadrícula. Esta propiedad es parte del modelo de diseño en cuadrícula (Grid Layout) en CSS, que ofrece un control más avanzado y estructurado sobre la disposición de los elementos en comparación con otros métodos de diseño.

Al utilizar display grid, puedes definir tanto las filas como las columnas de la cuadrícula utilizando las propiedades `grid-template-rows` y `grid-template-columns`. Luego, puedes ubicar elementos hijos en las celdas específicas utilizando propiedades como `grid-row` y grid-column`

Algunas propiedades clave que se utilizan junto con `display: grid` incluyen:

1. `grid-template-rows` y `grid-template-columns`: Definen el tamaño y la cantidad de filas y columnas en la cuadrícula, respectivamente.
    
2. `grid-gap` o `gap`: Define el espacio entre las filas y columnas de la cuadrícula.
    
3. `grid-row` y `grid-column`: Ubican los elementos en celdas específicas de la cuadrícula mediante números, nombres o valores de inicio y final.
    
4. `grid-area`: Combina `grid-row` y `grid-column` para especificar el área en la que un elemento debe colocarse en la cuadrícula.
    
5. `justify-items` y `align-items`: Alinean los elementos hijos dentro de sus celdas a lo largo de los ejes horizontal y vertical, respectivamente.
    
6. `justify-content` y `align-content`: Alinean las filas y columnas dentro del contenedor de la cuadrícula a lo largo de los ejes horizontal y vertical, respectivamente.
    
7. `grid-auto-rows` y `grid-auto-columns`: Definen el tamaño automático de las filas y columnas que se crean dinámicamente en la cuadrícula.
    

`display: grid` es especialmente útil para crear diseños complejos y responsivos, y es adecuado para casos en los que se requiere un control preciso sobre la disposición de los elementos. Puede usarse en combinación con otros métodos de diseño de CSS para lograr resultados aún más avanzados.