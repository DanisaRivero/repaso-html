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

* dialog =
* get = cuando envia la información al servidor, envía las variables por medio de la url y provoca un recargo de la página.
* post =

**El más usado por los desarrolladores backend es post**


> ## **Tarea**
* Crear un formulario


Los requerimientos faltantes para un formulario son los siguientes:
* maxlength = indica la cantidad máxima de carácteres por escribir.
* minlength = indica la cantidad mínima de carácteres a escribir.
* required = es la válidación de los inputs, hace que sea obligatorio llenarlo.