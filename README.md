# trabajoredes.github.io

En este ejercicio hemos tenido que crear 5 redes, cada una con una ip red diferente, y tendremos que añadir en RIP además de su propia ip, la ip de los servidores a los que están reñazionados
La primera formada por 3 subredes, cada una soportando distintos host. para conseguir las ips y las nuevas máscaras hacemos las operaciones necesarias 
En la segunda y tercera red creamos un servidor con una ip DHCP para más tarde crear los ordenadores y darles esa ip automáticamente
En la cuarta red, es necesario crear un punto de acceso, que tendremos que conectar al switch. a este punto de acceso. los ordenadores que queremos conectar a éste tenemos que ponerle una interfaz inalámbrica, pinchamos en desktop y en PC wireless y lo conectamos al punto de acceso que hemos creado
enla 5 red creamaos los 3 servidores dns para cada web con su nombre e ip en los servicios de DNS

Finalemnte conectaremos los routers desde la ventana CLI, usando los siguientes comandos:
  -n
  -enable
  -configurate terminal
  -interface fastethernet (posicion del router)
  -ip address (ip del router)
  
  hacemos el mismo proceso pero con el serial
