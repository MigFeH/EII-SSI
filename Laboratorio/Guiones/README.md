# Lab 01:
	Crear usuario
	Cambiar entre usuarios
	Instalar servidor OpenSSH
	Habilitar el firewall
	Evaluar la configuración de seguridad con Lynis
	Poner una contraseña adecuada
	Habilitar el software de escaneo de malware/rootkits
	El servicio Virustotal
	Google Safe Browsing
	Comprobación de vulnerabilidades conocidas de productos mediante encabezados HTTP
	

# Lab 02:
	Fichero robots.txt
	Metadatos de documentos
	Google Hacking
	Shodan
	Censys
	The Wayback Machine
	Escaneos en LAN con nmap
	Blacklight: Inspector de privacidad de la web
	Crear un entorno de navegación seguro y verdaderamente privado en tu MV
	Have I been pwnd?
	

# Lab 03:
	No cae nada de aquí, criptografía ya está evaluado.


# Lab 04:
	No cae nada de aquí, criptografía ya está evaluado.


# Lab 05 (ES LA PRACTICA DE WebMin, CIS BENCHMARK, OpenSSH, Modulos PAM [tienes apuntes de gente pa ayudarte en la modificacion de los modulos], AppArmor, Debsums y apt-show-versions, y Wazuh):
	Instalar y ejecutar WebMin
	Comprobar el consumo de recursos del servidor
	Agregar un usuario de prueba al servidor
	Gestion de paquetesDeshabilitar algunos servicios que se ejecutan en el momento del arranque
	Seguridad adicional para OpenSSH
	Configuración segura del módulo PAM
	Antigüedad de la contraseña y cuentas inactivas
	Gestión de AppArmor
	Instalar software de seguridad de apt
	Configurar reglas de auditoría
	Inspeccionar los logs en busca de comportamientos sospechosos (en la practica del lab se hace con WebMin)
	HIDS implementado con un XDR profesional: Wazuh como herramienta de monitorización de archivos, procesos y usuarios
	

# Lab 06 (ES LA PRACTICA DEL OpenSCAP (oscap y sus scripts bash), SCC (y sus STIGs), Ubuntu Pro (incluyendo la generacion de scripts para hardening) y usar Wazuh como responsable de politicas CIS (que puedas evaluar la seguridad de un agente con wazuh usando un CIS que tiene el)):
	Instalar OpenSCAP y actualizar sus políticas de seguridad
	Evaluación de una maquina con OSCAP
	Interpretación de los informes de OpenSCAP
	Correción on OpenSCAP
	Correción on scripts de Bash
	Auditoría automatizada con SCAP Compliance Checker (SCC) y STIGs
	Ejemplo de corrección manual con SCAP Compliance Checker (SCC) y un STIG para Firefox
	La licencia de Ubuntu Pro y el endurecimiento automático oficial
	Distribución de la corrección de CIS a servidores independientes
	Wazuh como responsable de políticas CIS (Hacer una evaluación automatizada de los sistemas que monitoriza con políticas CIS)
	

# Lab 07 (ES LA PRACTICA DEL FIREWALL, PiHole, NextDNS, Fail2Ban, PortSentry, Maltrail, Wazuh para ataques de red y uso de VPNs P2P (ZeroTier)):
	Filtrado de tráfico entrante con UFW
	Filtrado de tráfico saliente con UFW
	Protección de conexiones salientes: Filtrado de DNS con PiHole
	Filtrado avanzado de conexiones salientes con PiHole
	Usar un DNS seguro para tu protección: NextDNS
	Protección de intentos de intrusión: Fail2Ban
	Protección de intentos de escaneo: PortSentry como honeypot
	Instalación y prueba del IDS Maltrail
	Wazuh y ataques de red
	ZeroTier
	

# Lab 08-09 (ES LA PRACTICA DEL NMAP):
	Una simple “puesta en marcha”
	Tratar con puertos
	Uso del motor de scripting “de usar y tirar” (escaneo con scripts por defecto)
	Entender (un poco) el protocolo TCP
	Tipos de descubrimiento de hosts avanzados de NMap
	Tipos de escaneo NMap y evasión de firewalls básica
	Ejemplos (más) avanzados de NMap
	Formatos de salida NMap
	NMap Scripting Engine (NSE)
	Técnicas de recopilación de información con NSE
	Recopilación de información HTTP con NSE
	Detección de malware y vulnerabilidades con NSE
	Anexo: Cheatsheets-resumen de NMap


# Lab 10:
	Apache 2 instalado como un proxy
inverso
	Instalación de un WAF
	WAF contra ataques web
	Herramientas de detección automatizada de vulnerabilidades en aplicaciones (SAST, SCA)
	Combinación del proxy con técnicas anteriores
	Uso de un DAST contra una aplicación
	

# Lab 11:
	Enumerar posibles archivos ocultos con información interesante (T1190. Exploit Public-Facing Application)
	Exfiltración a través de directorios compartidos por SMB (T1190. Exploit Public-Facing Application)
	Diccionarios de contraseñas de palabras comunes contra objetivos concretos (1078. Valid Accounts)	
	Fuerza bruta en línea con Nmap (1078. Valid Accounts)
	Netcat como herramienta de escucha (TA1059. Command and Scripting Interpreter)
	Bind shell con netcat (TA1059. Command and Scripting Interpreter)
	Reverse shell con netcat (TA1059. Command and Scripting Interpreter)
	Reverse shell sin netcat (TA1059. Command and Scripting Interpreter)
	Searchploit (T1203. Exploitation for Client Execution)
	GTFOBins para exfiltración de datos
	

# Lab 12-13:
	Meterpreter para explotación (T1569. System Services)
	Payloads con msfvenom y multi/handler
	Escalada de privilegios a través de trabajos cron: Exfiltración de información privada (T1053. Scheduled Task/Job)
	Escalada de privilegios mediante la sustitución de ejecutables / dependencias: Reverse shells de Msfvenom (T1053. Scheduled Task/Job)
	Escalada de privilegios mediante la sustitución de dependencias de ejecutables: Exfiltración de datos privados (T1574. Hijack Execution Flow)
	Identificación de programas sudo (T1548. Abuse Elevation Control Mechanism)
	Generar una contraseña válida para un usuario de Linux (T1078. Valid Accounts)
	Escalar privilegios a través de programas sudo (T1548. Abuse Elevation Control Mechanism)
	Identificación de programas SUID (T1548. Abuse Elevation Control Mechanism)
	Escalada de privilegios a través de programas SUID (T1548. Abuse Elevation Control Mechanism)
	Escalada de privilegios potencial a través de técnicas de inspección ejecutables (T1078. Valid Accounts)
	