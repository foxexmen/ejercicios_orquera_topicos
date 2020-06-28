Ejercicio14

El ejercicio 14 permite ingresar un texto a través de un multiline text y con un boton guardar
todo el texto ingresado dentro de un archivo .txt, para realizar este ejercicio se crean objetos
de tipo OutputStreamWriter para enviar los datos que se ingresen en el multiline text, a través
de la clase Toast se muestra un mensaje de que los datos fueron guardados, luego con la clase
InputStreamReder si se obtiene true en el Toast crea un objeto por donde se pasa el dato
devuelto por el método openFileInput, para imprimir la información que se ingresó dentro del 
archivo txt que se va a generar se utiliza un For.

Ejercicio25

Este ejercicio reproduce un archivo .mp3 con el nombre quemado dentro del código al darle 
clic en el boton ejecutar.

Ejercicio29

Este ejercicio consta de 3 botones, uno para grabar un audio que se almacenará en formato .3gp en
una ruta establecida, luego el audio que generemos podemos reproducirlo con otro boton y en medio
de la reproducción del audio existe otro boton para detener la reproducción, esto se lo uso con 
ayuda de MediaRecorder, y se tiene funciones para poder tener acceso al microfono, también se debe editar
activity_main.xml para dar permiso a acceso a la tarjeta sd externa y al micrófono.
