# Chapter 02
En esta carpeta vamos a tener las tres formas mas normales de pasar información o configuracion a una transformación:
* simple_transformation: En esta ETL vamos a cargar un fichero csv mediante la variable **Internal.Entry.Current.Directory**, esta variable contiene el path de donde se carga la ETL y es interna a PDI.
* simple_transformation_with_named_parameters : Esta ETL carga el mismo CSV pero pasado por parametro asi como el nombre del fichero final o el path donde dejar el fichero, esta parametro se puede carga a la hora de lanzar la ETL en linea de comandos o por el menu , propiedades de la transformaciòn y pestaña parameter, en este caso es SAMPLES_DIR. [link](https://stackoverflow.com/questions/58077980/pentaho-pdi-passing-uservariable-in-command-line)
* simple_transformation_with_variables : Esta es igual que la ETL pasada pero pasando esa informacion por una variable.
