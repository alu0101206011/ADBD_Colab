# Práctica Modelo Objeto Relacional

## Participantes

- Anabel Díaz Labrador [alu0101206011@ull.edu.es](alu0101206011@ull.edu.es)
- Alejandro Martín de León [alu0101015941@ull.edu.es](alu0101015941@ull.edu.es)
- Jaime Pablo Pérez Moro [alu0101278919@ull.edu.es](alu0101278919@ull.edu.es)
- Andrea Calero Caro [alu0101202952@ull.edu.es](alu0101202952@ull.edu.es)
- Saúl Pérez García [alu0101129785@ull.edu.es](alu0101129785@ull.edu.es)
- Sheyla Ruiz-Gómez Ferreira  [alu0101124445@ull.edu.es](alu0101124445@ull.edu.es)


## Desarrollo de la Práctica

Una base de datos objeto-relacional es una extensión de la base de datos relacional tradicional, a la cual se le proporcionan características de la programación orientada a objetos. Para entender sus elementos y características, se nos ha propuesto un ejercicio, el cual se puede encontrar en: https://docs.google.com/presentation/d/1ANIQYZ7W94Mwvo_NXjR-I9Jrv8-uiWG2pleBZ4FZOM8/edit#slide=id.g108f71c5319_0_9.

Para la implementación de dicho ejercicio, se han seguido los siguientes pasos:

1) Generación de un diagrama de clases UML: La herramienta utilizada ha sido 'StarUML', y se han definido las distintas clases, relaciones y procesos empleados que define el enunciado de la práctica.

      Las características del objeto-relacional que podemos localizar en esta práctica son:
      
            - Asociaciones: Vínculo que existe entre clases.
            - Agregación: Indicamos que plano pertenece a Proyecto.
            - Composición: Un polígono está formado por líneas.
            - Herencia: Polígono hereda de la clase Figura.
            - Cardinalidades: Especifican la multiplicidad entre clases.
            - Atributos compuestos: Atributos que pueden ser divididos en subpartes (p.ejm: Dirección y Puntos). 

2) Creación del script: Con los conocimientos adquiridos en clase, se ha elaborado un script compatible con PostgreSQL.
3) Creación de la base de datos e insersión de datos: Con el script creado anteriormente, se forma una nueva BBDD a la que se le añaden las tablas (con diversas entradas) y las relaciones pertinentes.
4) Muestra de los datos obtenidos: Se han realizado capturas de pantallas de los resultados obtenidos.


## Pruebas de ejecución

Ejecución del programa.

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/Ejecucion1.png)
![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/Ejecucion2.png)

### Tablas:
Tabla POLIGONO

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/tabla1.png)

Tabla LINEA

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/tabla2.png)

Tabla JEFE_PROYECTO

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/tabla3.png)

Tabla PROYECTO

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/tabla4.png)

Tabla PLANO

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/tabla5.png)

Tabla FIGURA

![](https://github.com/alu0101206011/ADBD_Colab/blob/master/Modelo_Objeto_Relacional_Arquitectos/Capturas/tabla6.png)
