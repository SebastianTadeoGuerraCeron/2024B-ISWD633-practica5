# Ejercicio

Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:

- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.

# Una vez creado tu archivo .yaml realiza la respectiva prueba

# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO

![Ejecucion del nuevo compose](https://github.com/SebastianTadeoGuerraCeron/2024B-ISWD633-practica5/blob/main/imagenes/2.png?raw=true)

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube

![Acceso al Localhost](https://github.com/SebastianTadeoGuerraCeron/2024B-ISWD633-practica5/blob/main/imagenes/3.png?raw=true)
