# Trabajo Final
## Segundo Bimestre

***

### Problemática a resolver

* Generar una solución en algoritmo/miniespecificación/diagrama

Que permita ingresar nuevas cuentas personales de diversas plataformas. Las plataformas son:

- **Whatsapp** (se necesita los siguientes datos: nombre de usuario, número de teléfono, edad, ciudad, país)
- **Telegram** (se necesita los siguientes datos: nombre de usuario, número de teléfono, ciudad, país, área de interés)
- **Signal** (se necesita los siguientes datos: nombre de usuario, número de teléfono, ciudad, país, hobby principal)
- **Instagram** (se necesita los siguientes datos: nombre de usuario, ciudad, edad, correo electrónico)
- **Facebook** (se necesita los siguientes datos: nombre de usuario, edad, ciudad, país, correo electrónico)
- **Twitter** (se necesita los siguientes datos: nombre de usuario, nombres, apellidos, edad, ciudad, país, idioma, correo electrónico)
- **Flickr** (se necesita los siguientes datos: nombre de usuario, correo electrónico)

La aplicación debe tener los siguientes procedimientos, indicar que los procedimientos no tienen parámetros y cada uno de ellos en su cuerpo pedirá la información necesaria:

- función principal
- función crearFacebook
- función crearWhatsapp
- función crearTelegram
- función crearSignal
- función crearInstagram
- función crearFlickr

En la **función principal** se presenta un ciclo repetitivo que indica un menú de opciones:

- Si se ingresa 1 se llamará a crearWhatsapp
- Si se ingresa 2 se llamará a crearTelegram
- Si se ingresa 3 se llamará a crearSignal
- Si se ingresa 4 se llamará a crearInstagram
- Si se ingresa 5 se llamará a crearFacebook
- Si se ingresa 6 se llamará a crearTwitter
- Si se ingresa 7 se llamará a crearFlickr
- Si se ingresa algo diferente de 1,2,3,4,5,6,7; se debe presentar un mensaje en pantalla: "error en opción seleccionada"

>En cada iteración del ciclo; se pregunta al usuario si se desea salir del ciclo.

Cada procedimiento debe imprimir un resumen de la cuenta creada con todos los valores ingresados

**Cuando el usuario termina el ciclo repetitivo** se debe presentar un mensaje con base al número total de cuentas creadas. Se debe usar el número total de cuentas como argumento (entero) de una función llamada obtenerInformacion.

- En la función obtenerInformacion existe un parámetro. El mensaje se forma de la siguiente manera:
```
Se usa el siguiente arreglo unidimensional:  

(mensajeFinal(3),x(300)[{a-z}, {A-Z}, {BS}])

Los datos asignados al arreglo son:

mensajeFinal <-- {"Campaña con poca afluencia", "Campaña moderada siga adelante", "Excelente campaña", "Mala campaña"}
```

a. Si el número de cuentas creadas está en el rango de 1 a 5 el mensaje será: **Campaña con poca afluencia**

b. Si el número de cuentas creadas está en el rango de 6 a 15 el mensaje será: **Campaña moderada siga adelante**

c. Si el número de cuentas creadas está en el rango de 16 en adelante, el mensaje será: **Excelente campaña**

d. Si el número de cuentas creadas es igual a 0, el mensaje será: **Mala campaña**

### Presentación del trabajo final
- En la carpeta **algoritmo**, se debe generar los posibles pasos, únicamente del procedimiento **principal**; usar un archivo llamado paso.txt
- En la carpeta **miniespecificacion**, un solo archivo llamado solucion.txt con la miniespecificación de la solución.
- En la carpeta **diagrama**, se debe generar un (solo 1) diagrama de flujo del procedimiento **principal**.


***
