## Actividad 3: Identificación de direcciones MAC y dire
![Captura desde 2024-05-03 22-49-13](https://github.com/noemiAC/CDR/assets/168385917/79c72fd0-4732-44c0-bae9-b67c4cee6148)
cciones IP ##

![Captura desde 2024-05-02 20-17-54](https://github.com/noemiAC/CDR/assets/168385917/e407c70b-7743-4f57-a9d7-9700e092a459)

![Captura desde 2024-05-02 20-18-13](https://github.com/noemiAC/CDR/assets/168385917/14445150-657a-438a-bcba-a8f5b464787c)

![Captura desde 2024-05-02 20-18-26](https://github.com/noemiAC/CDR/assets/168385917/bf39afa3-1c93-4128-bf02-94a99cbedd8a)

![Captura desde 2024-05-02 20-18-43](https://github.com/noemiAC/CDR/assets/168385917/f001495a-0b96-479d-a8b6-06d30f3eb823)

**¿Qué dispositivo tiene el MAC de destino que se muestra?**
el dispositivo 172.16.31.5

![Captura desde 2024-05-02 20-18-56](https://github.com/noemiAC/CDR/assets/168385917/18693eca-72b6-401f-8126-992a52dfd76f)
![Captura desde 2024-05-02 20-19-10](https://github.com/noemiAC/CDR/assets/168385917/e3026dfb-87eb-4a31-bb14-de5cf6663977)




## Preguntas

**Responde las siguientes preguntas relacionadas con los datos capturados:**
**1. ¿Se utilizaron diferentes tipos de cables / medios para conectar dispositivos?**
se utilizaron cables de cobre

**2. ¿Los cables cambiaron el manejo de la PDU de alguna manera?**
No, los cables no cambian  el manejo del PDU

**3. ¿El hub perdió parte de la información que recibió?**
el hub al ejecutar por primera vez se perdio 25 % de información. pero luego ya no se perdió información

**4. ¿Qué hace el hub con las direcciones MAC y las direcciones IP?**
El hub no realiza procesamientos o cambios en las direcciones MAC y IP, Solo envia datos a los dispositivos conectados.

**5. ¿El punto de acceso inalámbrico hizo algo con la información que se le entregó?**
Sí, lo empaqueta el mensaje enviado por la instalación.

**6. ¿Se perdió alguna dirección MAC o IP durante la transferencia inalámbrica?**
No se perdió ninguna dirección Mac y tampoco IP

**7. ¿Cuál fue la capa OSI más alta que utilizaron el hub y el punto de acceso?**
La capa mas alta que eutilizaron fue la capa 1, en el caso de hub y punto de acceso.

**8. ¿El hub o el punto de acceso reprodujeron en algún momento una PDU rechazada con una “X”
de color rojo?**
Si, ya que al enviar todos los puertos solo uno es el destino. por lo cual a los demás puertos son rechazados.
**9. Al examinar la ficha PDU Details (Detalles de PDU), ¿qué dirección MAC aparecía primero, la
de origen o la de destino?**
primero se aprecia la de destino

**10. ¿Por qué las direcciones MAC aparecen en este orden?**
Porque primmero conoce la dirección MAC, de esa manera envía mas rápido el destino

**11. ¿Había un patrón para el direccionamiento MAC en la simulación?**
No

**12. ¿Los switches reprodujeron en algún momento una PDU rechazada con una “X” de color rojo?**
No, porque los switches pueden leer las direcciones MAC 

**13. Cada vez que se enviaba la PDU entre las redes 10 y 172, había un punto donde las direcciones
MAC cambiaban repentinamente. ¿Dónde ocurrió eso?**
Sí, esto ocurrio en el router

**14. ¿Qué dispositivo usa direcciones MAC que comienzan con 00D0: BA?**
Router

**15. ¿A qué dispositivos pertenecían las otras direcciones MAC?**
A las computadoras, switchs, hub y punto de acceso.

**16. ¿Las direcciones IPv4 de envío y recepción cambiaron los campos en alguna de las PDU?**
No

**17. Cuando sigue la respuesta a un ping, a veces llamado pong, ¿ve el cambio de envío y recepción
de direcciones IPv4?**
Si se ve el cambio

**18. ¿Cuál es el patrón para el direccionamiento IPv4 utilizado en esta simulación?**
Cada puerto del router maneja las direcciones ip

**19. ¿Por qué es necesario asignar diferentes redes IP a los diferentes puertos de un router?**
Para poder interconectar y facilitar la cominicacion entre redes separadas.

**20. Si esta simulación se configura con IPv6 en lugar de IPv4, ¿cuál sería la diferencia?**
El formato ya seria en hexadecimal 





