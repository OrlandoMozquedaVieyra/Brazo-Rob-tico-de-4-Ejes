# Brazo Robotico de 4 Ejes.
El propósito de esta práctica es desarrollar paso a paso un proyecto para controlar y programar un Brazo Robot, simulando las funciones básicas de un robot industrial.

# El robot debe tener dos funciones básicas:

# Programar: 
Registrar las posiciones de los brazos en tres dimensiones (cada registro es un "paso", un programa consiste en una serie de pasos).

# Ejecutar: 
Realice en secuencia las posiciones registradas en el "Programa". El robot ejecutará el programa hasta que se use el comando "ABORTAR".

# Características principales:

El proyecto se usa para controlar robots con  4 DOF ("Grados de libertad").
    El robot se debe controlar en modo "REMOTO" (a través de una programa en java por medio del puerto serial).
    La información para el usuario se podrá proporcionar a través de LEDS de colores, una pantalla LCD de 2 líneas y/ó sonido (un zumbador).
    Debe de contener un botón de paro de emergencia (Físico).
    Si existe un fallo y/o corte de energía, después de restablecerse la corriente el robot debe de continuar el programa (aunque este no se encuentre conectado a la aplicación).
    Los brazos robóticos se pueden clasificar de acuerdo con el número de "articulaciones" o "Grados de libertad" (DOF) que tienen. La "Base", o "Cintura", por lo general puede girar el brazo 180o o 360o, dependiendo del   tipo de Servo utilizado (aquí en este proyecto, se debe utilizar un motor a pasos para girar 360o). El "Hombro" es el responsable de "levantar o bajar" el brazo verticalmente. El "codo" hará que el brazo "avance o retroceda". La "Garra" o "Pinza" funciona abriendo o cerrándose para "agarrar cosas".

# Diagrama del brazo robótico:
![diagrama del brazo robotico](https://user-images.githubusercontent.com/22648194/40197564-66515490-59d9-11e8-8a2c-09ff35d4bb61.png)

# Interfaz de comunicación desarrollada en Java.
Se muestra la interfaz desarrollada en java para poder hacer la comunicación y poder programar el brazo robotico. En cada imagen que se muestra podemos ver como hace la comunicacion primero hacia el arduino, despues se programa con los botones que tiene el programa. Despues va mandar lo que se programo para que lo realice hasta que se precione el boton de abortar.
![captura de pantalla 4](https://user-images.githubusercontent.com/22648194/40204125-0f06a172-59ed-11e8-924c-2bc08cfbac62.png)
![captura de pantalla 5](https://user-images.githubusercontent.com/22648194/40204126-0f27e8a0-59ed-11e8-8c26-c166fa0298bf.png)
![captura de pantalla 6](https://user-images.githubusercontent.com/22648194/40204127-0f495f4e-59ed-11e8-818e-4df3fd2d4793.png)
![captura de pantalla 7](https://user-images.githubusercontent.com/22648194/40204128-0f64cee6-59ed-11e8-8d17-df285c25ae13.png)
![captura de pantalla 8](https://user-images.githubusercontent.com/22648194/40204131-0f81442c-59ed-11e8-951f-d2f4d17ed334.png)
![captura de pantalla 9](https://user-images.githubusercontent.com/22648194/40204132-0f9e7e84-59ed-11e8-9a0f-7ccdbd344536.png)
