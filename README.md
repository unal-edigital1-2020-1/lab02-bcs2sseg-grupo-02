# lab01- BCD2SSEG
Laboratorio 02 simulación

En esta plantilla debe adicionar la documentación del laboratorio

* Andres Felipe Beltrán
* Julian Andres Castro
* Edwar Andres Jimenez

# Descripción   <h2>
  Para el desarrollo de este laboratorio se hizo uso de los archivos de la carpeta src: BCDtoSSeg.v y BCDtoSSeg_TB.v, para los cuales, se realizaron comentarios en el código acerca del funcionamiento.


  ## Introducción

  La intención de este laboratorio en primera instancia es describir e implementar hardware sencillo que permita validar visualmente las respuestas de un determinado diseño, por ejemplo os resultados de una suma en un display de 7 segmentos.

  Observando la parte física de un display, para mostrar los resultados de forma visual de un determinado diseño digital se necesita activar 7 conexiones de Leds que se combinan para formar la imagen en el display de un determinado dígito, entonces la propuesta  de esta práctica fue diseñar, sintentizar e implementar un BDC (Binary-Coded Decimal) para un Display de 7 sergmentos (este último de manera virtual), el cual permite visualizar números en representación hexadecimal (0x0 a 0xF) y decimal.

  ![Display 7 segmentos](/images/7_segment_display_animated.gif)

  Imagen tomada de [Guam + Various](https://commons.wikimedia.org/wiki/File:Seven_segment_display-animated.gif)


  ## Desarrollo

  ### Caja funcional del BCD:

  ### Descripción Funcional del BCD:
  
  A  | B  | Cin | Out | Cout
  -- | -- | --  | --  |  --
  0| 0 | 0 |0 | 0
  0| 0 | 1 | 1| 0
  0| 1 | 0 | 1| 0
  0| 1 | 1 | 0| 1
  1| 0 | 0 | 1| 0
  1| 0 | 1 | 0| 1
  1| 1 | 0 | 0| 1
  1| 1 | 1 | 1| 1



  ### Simulación para el BCD-7seg y análisis de resultados.



  ### Visualización Dinámica de 4 Display, tomando como base los archivos dados.
  <!-- Crear el archivo testbench.v -->

  #### Simulación, Revise que el sistema funciona como usted lo esperaba. Realice lo comentarios necesarios en el archivo README.md.

  <!--Modificar o Añadir los bloques necesarios para que la visualización sea en representación Decimal y no Hexadecimal.-->

  #### Visualización en representación Decimal y no Hexadecimal.

  <!-- Realice la respectiva publicación del repositorio antes de la fecha dada con todo el código fuente -->
