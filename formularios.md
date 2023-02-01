# Etiqueta form

Para crear un formulario armamos el siguiente código 
~~~ html

  <form acction="#" method="post">
    <label for="">Nombre</label>
    <input type="text" name="nombre" placeholder="Ingrese su nombre" minlength="5">
    <label for="">Apellido</label>
    <input type="text" name="apellido" placeholder="Ingrese su apellido">
    <label for="">Email</label>
    <input type="email" name="email" placeholder="Ingrese su email">
    <label for="">Password</label>
    <input type="password" name="password" placeholder="Ingrese su contraseña">
    <input type="submit" value="enviar">
  </form>
~~~

El atributo `placeholder` sirve para ayudar al usuario para que ingrese su nombre, apellido o email.

El atributo `acction` define a qué página va a mandar la información del usuario (parte backend)

El atributo `method` es el método con el que se envia la información al servidor, son 3

Atributo `name` sirve como 'variables', facilita el trabajo para los de backend

* dialog
* get = las variables de 'name' viajan por la url
* post

**El más usado por los desarrolladores backend es post**