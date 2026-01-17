# Examen lab ssi mayo 2024/2025

Ejercicio 1.
a. Con una captura de pantalla de cierta vulnerabilidad, responder a qué harías con acceso a Internet con esa información.
b. Comprobar de forma offline los exploits conocidos para el programa detallado en la captura y abrir uno de ellos.

Ejercicio 2.
a. Bloquear todas las conexiones que provengan de cierta red. 
b. Comprobar el log del firewall en busca de la IP y puerto de conexiones maliciosas.
c. Bloquear conexiones con ese IP y puerto.
d. Eliminar la regla del punto a. para que solo se aplique la del c.

Ejercicio 3. Obtener la dirección IP de un contenedor, y a continuación:
a. Escanear con `nmap` las máquinas vivas de la red del contenedor
b. Hacer un escaneo detallado del contenedor, incluyendo puertos abiertos, servicios en ejecución, versión y métodos de autenticación de SSH

Ejercicio 4. Dada una cuenta ya creada con cierto hash (contraseña desconocida)
a. b. c. Modificar el archivo `/etc/login.defs` para cambiar las propiedades de mínimo y máximo de tiempo entre cambios de contraseñas, y el número de días antes del aviso de cambio de contraseña
d. Cambiar en el mismo fichero el algoritmo de encriptación a `yescrypt`
e. Bloquear cuentas inactivas por más de 30 días con `useradd -D -f 30`
f. Crear cuenta nueva para el usuario anterior y registrar el hash en el sistema. Por último comprobar que las fechas de cambio de contraseña tengan sentido, de acuerdo con lo recomendado por el CIS Benchmark

Ejercicio 5. Hacer elevación de privilegios con GTFOBins o SMB.
