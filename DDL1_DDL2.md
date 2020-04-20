# DDL1 Proxectos de investigación

Antes de crear as táboas que forman a base de datos, temos que creala. Simplemente utilizamos os seguintes comandos:

```SQL
CREATE DATABASE proxectos_de_investigacion; 
USE proxectos_de_investigacion;
```

Agora pódese comezar a crear as táboas dentro da BD que acabamos de crear. 

Esta BD ten **9 táboas: Sede, Departamento, Ubicacion, Grupo, Profesor, Programa, Proxecto, Participa e Financia**. Temos que usar o comando `CREATE TABLE` para cada táboa, sempre indicando o seu nome, os atributos que forman a táboa, o tipo de dato de ditos atributos, a clave primaria e as posibles claves foráneas. Nalgunha das táboas engadiremos as claves foráneas mediante `ALTER TABLE`.

*ddl1_1.PNG USE, Sede , Departamento*

*ddl1_2.PNG Ubicacion , Grupo*

*ddl1_3.PNG Profesor*

*ddl1_4.PNG ALTER TABLE Departamento+Grupo, Programa*

*ddl1_5.PNG ALTER TABLE Profesor (2) , comando describe nome-taboa=mostra a estructura completa da táboa.*

*ddl1_6.PNG Proxecto, ALTER TABLE Proxecto (2)*

*ddl1_7.PNG Participa, Financia, ALTER TABLE Financia (2)*

# DDL2 Naves espaciais

Do mesmo modo que na base de datos anterior, utilizamos os comandos `CREATE DATABASE nome-taboa` e `USE nome-taboa`.

Esta BD ten **8 táboas: Servizo, Dependencia, Camara, Tripulacion, Planeta, Visita, Habita e Raza.**


*ddl2_1.PNG Servizo, Dependencia*

*ddl2_2.PNG Camara, Tripulacion, ALTER TABLE Tripulacion*

*ddl2_3.PNG Planeta, Visita*

*ddl2_4.PNG Habita, Raza, ALTER TABLE Habita, ALTER TABLE Camara*
