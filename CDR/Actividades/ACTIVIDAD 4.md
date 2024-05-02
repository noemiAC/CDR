## Actividad 4: Configuración inicial de un Switch

![Captura desde 2024-05-02 03-32-43](https://github.com/noemiAC/CDR/assets/168385917/f9e28f8d-3c8c-41d3-af31-a33093732d7c)

**a) ¿Cuántas interfaces Fast Ethernet tiene el switch?**

Cuenta con 24 fast de Ethernet

**b) ¿Cuántas interfaces Gigabit Ethernet tiene el switch?**

Cuenta con 2 nterfaces Gigabit 

**c) ¿Cuál es el rango de valores que se muestra para las líneas vty?**

Nos muestran un rango de 0 4 y 5 15 esto nos indica que ambos rangos estan configuradas para permitir el inicio de sesión.

Esto significa que puedes acceder al switch de forma remota o a larga distancia a o acceder de ortro lugar través de una (red) de las líneas vty del 0 al 4 y del 5 al 15.

**d) ¿Qué comando muestra el contenido actual de la memoria de acceso aleatorio no volátil(NVRAM)? show startup-config**

Este comando muestra la configuración almacenada en la memoria NVRAM

**e) ¿Por qué el switch responde con "startup-config no está presente"?**

Porque aún no se encuentra configuraciones guardadas en la memoria de switch.
El switch falta cofigurar sus direcciones de ip.

diapo 3


¿Por qué se requiere el comando login?
Este comando se requiere para habilitar la contraseña que se cambio, en este caso la contraseña de la consola

¿Qué se muestra como contraseña de enable secret?
se muestra la siiguiente contraseña![Captura desde 2024-05-02 04-48-11](https://github.com/noemiAC/CDR/assets/168385917/ea47c36f-42b0-4b32-b4da-f3b327d53963)


**¿Por qué la contraseña de enable secret se ve diferente de lo que se configuró?**
Porque se guardo en modo enable Exec privilegiado

despues de diapo 4
**¿Cuándo se muestra este aviso?**

En este caso la configuración del aviso MOTD dice "This is a secure system. Authorized Access Only!", lo que nos indica que este sistema está destinado solo para usuarios autorizados y el acceso no autorizado está prohibido.

**¿Por qué todos los switches deben tener un aviso de MOTD?**
Configurar un aviso de MOTD  a todos los switches proporciona seguridad y protección acerca de la red. Asimismo también ayuda un entorno  seguridad y cumpir con las políticas establecidas.

**¿Cuál es la versión abreviada más corta del comando copy running-config
startup-config?Examine el archivo de configuración de inicio.¿Qué comando muestra el contenido
de la NVRAM?**
copy run start

**¿Todos los cambios realizados están grabados en el archivo?**
Guarda solo los cambios realizados en la configuraci+on actual













