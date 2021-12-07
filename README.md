# Secrets-App

Aplicación centrada en la authentificacion de usuaros. La idea es registrarse y postear tus secretos, los cuales son mostrados en la pantalla principal sin dar a conocer quien los publico, basada en una aplicación movil que realiza una funcion similar. 

Estilo simple realizado con bootstrap, se uso node js y passport/OATH para el uso de google y Facebook (La aplicaciones de facebook por cuestiones de la plataforma no permite el registro actualmente, solo con las cuentas que registre en un inicio cuando cree la aplicación.)
Para el registro por correo usando el formulario de hace uso de passport. El almacenamiento de los datos de los usuarios asi como el arreglo de los secretos ingresados por cada usuariose lleva a cabo con MongoDB (mongoose). 

Pantalla de registro
![image](https://user-images.githubusercontent.com/90287359/144676811-117282e9-6286-4a38-8f2c-f780a073fb60.png)

Pantalla principal 
![image](https://user-images.githubusercontent.com/90287359/144676747-c9e59b6b-2b02-4c57-99f9-67081bdbb8ac.png)

Base de datos: 

![image](https://user-images.githubusercontent.com/90287359/144676956-e1848561-cfb5-4d4b-a250-be2fd0b7a2bf.png)


demo : https://secrets-ap.herokuapp.com/

todo: Arreglar funcionalidad que permita eliminar uno o mas de los secetos por usuario. 


