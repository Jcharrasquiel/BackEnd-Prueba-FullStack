# BackEnd-Prueba-FullStack

Proyecto Prueba Técnica Full Stack
Prueba Java con Spring Boot, Servicios REST


SRPING BOOT - BACKEND

Cree los package inicialmente para luego crear las clases e interfaz de cada uno quedando así.
![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/d8b88646-824c-42dc-b9e6-48c9de6faaee)

Para crear las entidades y tablas no lo realice por medio de un script SQL si no de la siguiente manera:
![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/34dcb319-5f96-4748-9e8d-87d5c3520eef)

Y este me las crea en la tabla que le indico en resource application.properties 

![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/358c5b24-bb2a-4c6d-85fd-635a897de449)

Este mismo nombre debo tener en donde crear mi base de datos en este caso MySQL

![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/d4a28c21-7423-4b05-8cb6-031b2f75d4c7)
--

![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/2cd47fd2-edd6-4892-84e2-5cdb5ee310bf)

Donde evidenciamos la correcta creacion de la tabla y sus campos, lo mismo se hizo para pedidos.

Para ahorrar lineas de codigo utilice la dependencia @Data de Lombok que al colocarla nos evita colocar los Getter y Setter.
![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/111c2e95-03c3-47dc-b172-f6410ecdc0b3)

En la linea 15 hago referencia y es para que el que ID sea autoincremental.
("@GeneratedValue(strategy = GenerationType.IDENTITY").

El resto de alguno de los requerimientos se encuentran en el codigo, en alchivo comprimido.

NOTA: el postman para probar la API mi antivirus no me permite ejecutarlo, intente por Insomnia, THUNDER CLIENT y Rapidapi Client pero no se usarlas de un todo (en teoria deberia funcionar "lo siento").
![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/60c0232e-f9e5-4776-b202-da283aa349f9)



ANGULAR - FRONTEND

El frontend lo cree en angular con Type Script, no esta completo, pero espero puedan revisar me hubiese gustado terminarlo, pero no pude por varios inconvenientes, me gustaria hacer parte de su equipo aprendo de manera rapida espero me den la oportunidad, mil gracias.

En frutas.services.ts creo todas las opciones del crud (get, post, put, delete)
Donde tambien anexo al final lo de los pedidos, esta comentado porque no logre terminar las vistas.

![image](https://github.com/Jcharrasquiel/BackEnd-Prueba-FullStack/assets/88496196/29e4c057-96b1-4411-9c58-696be212a2f5)

Adjunto deja el proyecto del FrontEnd, espero que me den la oportunidad, espero su cominicado gracias.



