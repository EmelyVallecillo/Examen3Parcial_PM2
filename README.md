# Examen3Parcial
  Descripción del proyecto
El proyecto consiste en una app de notas, diseñada en .NET MAUI y Firebase,  con una clase   Notas con las propiedades:
ID_NOTA, DESCRIPCION, FECHA  la cual esta validada para que no sea menor a la actual, PHOTO_RECORD, AUDIO_RECORD
La interfaz principal muestra dos botones, “Agregar nota” y “ Lista de notas”

-Agregar notas
Una vez dado click en este botón nos lleva a la siguiente ventana, en la cual inf=gresamos la descripción de la nota como tal, agregamos una foto desde el botón “Tomar foto”, seleccionamos la fecha y hora desea la cual se valida con el botón “Validar fecha y hora”, una vez llenos estos campos que tienen validación de datos, desde el botón “Agregar” se crea la nota. La cual a su vez se carga en Firebase, 
-Lista de notas
Aquí esta la lista de notas creadas desde la mas reciente hasta la mas antigua, nos muestra una vista previa, de cada nota, las cuales tienen las opciones de: “Editar”, “Eliminar”, “Descripcion”, para crear cambios en las notas.

Instrucciones para ejecutarlo
Instalar los paquetes NuGet
Firebase.Database.net
FirebaseAuthentication.net
FirebaseStorage.net
Para facilitar la gestión de datos, la autenticación de usuarios y el almacenamiento de archivos.



