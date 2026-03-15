# Decisiones semánticas de mi tarjeta de presentación personal #

**Para realizar mi tarjeta de presentación personal desde un archivo html utilice las estiquetas semánticas de la siguiente manera:**

**header**

Lo utilicé para ponerle un encabezado principal a la tarjeta.

**main-article-header-section-h3**

Esta secuencia de etiquetas las utilicé para dar a conocer mi fecha de nacimiento acompañandolas de una etiqueta **time** que es una etiqueta perfecta para tiempo y fechas.

**article-header-h3-ul**

Esta otra secuencia la utilicé para dar a conocer datos sobre mi por medio de listas para que se viera mejor.

**footer**

Por último este lo utilicé para darle un pie de página para que la tarjeta se viera más "profesional" y se mantuviera más semántica.

**De una manera más específica:**

**main**

Se utiliza para el contenido principal de la página.

**article**

Se utiliza para el contenido que tiene sentido por si mismo.

**section**

Se utiliza para agrupar contenido con un tema en común.

**footer**

Es para agregar un pie de página.

# DOM visual de el archivo html de mi tarjeta personal #


-html
   
   -head
    
    -meta
      
    -title - /title
  
  -/head
  
    -body
     -header
         -h1
         -/h1
         -p
         -/p
     -/header
    -main
      -article
        -header
         -h3
         -/h3
          -time
          -/time
        -header
      -/article
      -article
       -header
         -section
          -h2
          -/h2
         -/section
          -h3
          -/h3
            -ul
              -li
              -/li
            -/ul
       -/header
      -/article
    -/main
    -footer
    -/footer
    -/body
    -/html

