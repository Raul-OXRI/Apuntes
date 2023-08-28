### Datos del estudiante
Nombre: José Raúl Botzoc Mérida
Carnét: 4090-19-7994
Universidad Mariano Gálvez
Base de datos I


# Tema 1
## Explique que es una base de datos y brinde algunos ejemplos de Base de datos. 

Es un conjunto exhaustivo de datos estructurados, fiable y homogéneos, organizados, idenpendientemente de su utilización y de su implementación de su utilizacion y de su implimentacion en maquina, accesibilidad en el tiempo  real, compartibles por usuarios concurrentes que tienen necesidades de información diferentes y no predecibles en el tiempo 

ejemplo:
- un base de datos de asistencia de un colegio 
- una base de datos de de los jugadores de la liga nacional 
- una base de datos los que maneja el sistema Linux 
- una base de  datos de una clinica
## Explique que es un manejador de Base de Datos.  

es un sistema diseñado para cubrir 2 propositos los cuales son:
- Agregar, borrar y actualizar los datos en la BD
- Proveer de varaios caminos para ver los datos en la BD
Donde existe en manera fisica con el nombre Sistema Gestion Base D datos (SGBD) donde  nos proporciona que nos permite controlar el acceso y la utilidades de la bd por el usuario, para concluir, modificar informacion, incluyendo presentaciones para conseguir la idenpendemcia, la integridad y la seguridad de los datos, asi como la concurrencia de usuario 
## Explique las ventajas de utilizar base de datos.  
- Compacto - no hace falta papeles que pudieran ocupar muuho espacio
- Rapido - puede obtener y modificar datos con mucho mayor velocidad que un ser humano
- Menos laborioso - se quita la parte tediosa de mantener papeles a la mano,las tareas mecanicas siempre sera mejor realizadas por maquinas
- Actual - se dispone en cualquier momento de informacion precisa y al día 
## Explique que es una tabla y sus partes.  

Una tabla es la estructura fundamental para que los datos se almacenen por una organizacion de filas y columnas cada fila es una tabla representa un registro individual y las columnas son los diferentes tipos de datos que se almacenan en cada registro 

## Explique el nivel físico de la arquitectura de Base de Datos.  

Es el repersnetacion de nivel mas bajo de abstracion es elque describe en detalle la formacion en como se almacenan los datos en los dispositivos de almacenamineto

## Explique que es un DBA.

Es la persona especializada en genstionar, analizar y realizacion de base de datos con el cual tiene como funcionalidad:
- diseñar 
- implementar 
- mantenimiento de BD
- seguridad  a las BD
- Monitoreo
- Backup de la BD
- Planificaión 
# Tema 2

## 1 Explique como solucionar una relación varios a varios

El concepto de una relación de varios a varios es que proporcionan información importante que va de una cosa a otra, se da cuando uno o más elementos en una tabla puede tener una relación con uno o mas elementos de otra tabla. 

la solución a resolver relación de varias a varios es:
1. identificar las entidades y atributos
2. crear tablas separadas para cada una de las entidades
3. Describir los atributos  de cada identidad y desgrosarlo lo mas especifico que se pueda
4. identificar las claves primarias y foraneas "las primarias son las identifiacion de la entidad y las foraneas son las que se conecta con con la otra tabla"

## Dado el siguiente enunciado cree un diagrama entidad-relación para el diseño de la base de datos

- Un centro de atención médica requiere diseñar la base de datos que permita gestionar  
correctamente las visitas de los pacientes a cada clínica, considere que los doctores deben  
visualizar su agenda.  

![](https://i.imgur.com/1pC3s7B.png)

## Dada la siguiente tabla diseñe el modelo – entidad relación, agregue las entidades que correspondiente

Trabajadores:
- Nombre
- Apellido
- Carnet

Horas laboriadas
- Fecha
- Horas 
