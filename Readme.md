### Quinto Programa Mi RED
Hora ya conocemos cómo utilizar listas y, por tanto, podemos agregar una funcionalidad mucho más interesante a nuestra red social y que, claramente, nos hacía falta. La nueva función nos permitirá administrar listas de amigos y de mensajes. Veamos cómo lo hacemos. Para empezar, descarga los archivos "S6Red.py" y "MiRedS6-Listas.py". Partamos de estos para empezar a programar sobre la misma base. 


En estos archivos encontrarás un programa que extiende los que se han hecho en las semanas anteriores añadiendo nuevos valores para el perfil del usuario: una lista de amigos, y una lista de mensajes que se llama "muro". La lista de amigos reemplaza a nuestro antiguo valor "num_amigos". Al conocer la lista de amigos, también conoceremos la cantidad de amigos. Observa en el código cómo leemos la lista de amigos de la función "obtener_lista_amigos". Observa también cómo se han modificado las funciones "leer_archivo()" y "escribir_archivo()" para que concuerden con la nueva estructura de archivos de extensión ".user". Recuerda que las funciones las encontrarás en el archivo "S6Red.py".

Para hacer el "muro" hemos hecho lo siguiente. En el archivo de cada usuario, tras escribir su estado actual, hemos agregado una lista de los mensajes que han sido publicados por sus amigos, de manera que estamos formando una lista de mensaje que es lo que hemos denominado "muro", o "timeline", presente en casi todas las redes sociales. Fíjate en los archivos "S6Red.py" y el "MiREdS6-Listas.py" para entender los cambios que hemos realizado en el código para esto. 

EJECUTA EL CÓDIGO

Ejecuta el código "MiREdS6-Listas.py" y prueba las nuevas funciones de lista de amigos y muro para entender bien cómo funcionan. Revisa y examina el código con atención para que no se te escape nada y trata de extenderlo con los ejercicios 1 y 2 que te planteamos a continuación y responde al cuestionario de evaluación. 

**EJERCICIO 1**

Agrega una opción que permita agregar un nuevo amigo a tu lista. Esta funcionalidad solamente agregará al usuario, sin pedir autorización y aceptación por parte del destinatario como hace Facebook. Es decir, que la relación de amistad solamente existe en un sentido. 

**EJERCICIO 2**

Agrega una opción que permita mostrar los últimos estados de todos los amigos de un usuario. Ten en cuenta que esto no es equivalente a publicar los mensajes de su muro, sino que necesitarás leer una línea particular de los archivos de cada usuario en su lista de amigos. 


