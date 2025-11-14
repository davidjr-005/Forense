# Informe de Recolección y Almacenamiento de Evidencias
## Recolección de Evidencias
Se realiza la recolección en un entorno controlado, asegurando que el proceso no altere los datos originales.
Se documenta cada acción y se siguen protocolos establecidos para la obtención y registro de las evidencias digitales.
Todas las operaciones se ejecutan conforme a procedimientos verificados, manteniendo la trazabilidad y la integridad de la información.

## Descripción de la Evidencia
Se recopilan elementos digitales relevantes para el proceso de análisis forense.
Cada evidencia es identificada, clasificada y documentada según su tipo y propósito.
Se asegura la correcta gestión de la información, preservando su autenticidad y valor probatorio.

## Cadena de Custodia
Se establece una cadena de custodia que detalla cada manipulación, traslado o almacenamiento de las evidencias.
Se registran fechas, responsables y condiciones de manejo para mantener la trazabilidad de todo el proceso.
La documentación asociada garantiza la transparencia y validez legal de las actuaciones efectuadas.

##  Almacenamiento de la Evidencia
Las evidencias se almacenan en medios seguros y bajo control de acceso restringido.
Se crean copias de respaldo y se aplican medidas de protección que aseguran integridad, confidencialidad y disponibilidad.
Se realizan verificaciones periódicas para confirmar la conservación y fidelidad del material almacenado.

##  Metodología Aplicada
La metodología empleada se basa en prácticas internacionales para la gestión de evidencia digital.
Se contemplan fases de identificación, recolección, preservación y documentación sistemática.
El objetivo principal es garantizar la validez técnica y legal del proceso, así como la posibilidad de reproducirlo de manera verificable.
Marco normativo de referencia: ISO/IEC 27037 para el manejo de evidencia digital y NIST SP 800-86 para la integración del análisis forense en el ciclo de respuesta a incidentes.

---

# Cadena de CUSTODIA

| Evidencia            | Fecha y Hora         | Lugar                        | Descubrió             | Recolectó            | Custodia                   | Hash (SHA-256)                                                      | Observaciones                                        |
|----------------------|----------------------|------------------------------|----------------------|----------------------|----------------------------|--------------------------------------------------------------------|-----------------------------------------------------|
| EV1_Máquina Virtual OVA   | 2025-11-13 09:00 CET | Laboratorio de Ciberseguridad | David JR   | David JR   | Servidor de Evidencias Cifradas | DAF0EF5255D98276A6912A53611DB5C0CBF2CCCBB49A180DD7FCC0F95E14930C | Copia original exportada y asegurada en laboratorio |
| EV2_Memoria RAM (.elf)    | 2025-11-13 09:30 CET | Estación de trabajo forense   | David JR   | David JR   | Almacenamiento seguro cifrado   | 09D75F04474D628EEBDA4DEBDCA288D740647B4011CFEE6B1528C70971361B55 | Dump realizado con VBoxManage, VM pausada            |
| EV3_Disco virtual (imagen) | 2025-11-13 10:00 CET | Estación de trabajo forense   | David JR   | David JR   | Almacenamiento seguro cifrado   | FEA1215493CAB73B0B00CD9B8DE0A8371165DDA87862F22BCCBA225FF4437257 | Imagen forense íntegra, verificada con hash          |
| EV4_01_systeminfo.txt         | 2025-11-13 10:15 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 942AEF586802DBF5998FA7CF86FEB5DEFF45AF8D7FCF5C7F733D06AF2D6A41DC | Listados de procesos, conexiones y módulos extraídos |
| EV5_02_ipconfig_all.txt         | 2025-11-13 10:16 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 90D1C8D4504AB3CF6772D89A1E94A8DBD5C300A95B8601D12015DCDAC6A97EE4 | Listados de procesos, conexiones y módulos extraídos |
| EV6_03_routeprint.txt          | 2025-11-13 10:17 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 0F17C5971B809F662E48B9DFC92EFC362646D30F76AADC46111239BF70EF3758 | Listados de procesos, conexiones y módulos extraídos |
| EV7_04_arp.txt          | 2025-11-13 10:18 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | B562625BC2A7235A253BE0CE40C475FB120D008535E1D5BA96CD3DECB4AC696B | Listados de procesos, conexiones y módulos extraídos |
| EV8_05_netstat_ano.txt          | 2025-11-13 10:19 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | E8018800C036B02FBADEBB24F7D82EADDB9C353559DE8C9EB817EC5297DAF051 | Listados de procesos, conexiones y módulos extraídos |
| EV9_06_tasklist_v.txt          | 2025-11-13 10:20 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 0F6B8FD94CCC7EBC68D4D52593D9D71A13169F16DD3499519DCA91732EC9C0BA | Listados de procesos, conexiones y módulos extraídos |
| EV10_07_wmic_process_full.txt          | 2025-11-13 10:21 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 33BEE6F1959A31583E30888CB735E34B05251A10D0D467C2AE4DFE07C43948ED | Listados de procesos, conexiones y módulos extraídos |
| EV11_08_schtasks.txt          | 2025-11-13 10:22 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 5A7E0929FF1F64BC432D86F98D9DA3EE05C6A51C582A52F4C4AE2F3C208585D9 | Listados de procesos, conexiones y módulos extraídos |
| EV12_09_logger_users.txt          | 2025-11-13 10:23 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | 60B5724FB333F8B5D574A63A5162ECEBBB767669ED6C5E6509A6FC0EFC19F594 | Listados de procesos, conexiones y módulos extraídos |
| EV13_10_env_vars.txt          | 2025-11-13 10:24 CET | Estación de trabajo forense   | David JR   | David JR   | Sistema de archivos protegido    | E84786A5C2B7A306EE2192E202D55DD13915DCDB22741A3AD752B28CB9C6A905 | Listados de procesos, conexiones y módulos extraídos |

# Nota sobre el Proceso de Recolección y Adquisición de Evidencias Digitales

Durante todo el proceso de recolección, adquisición y almacenamiento de evidencias digitales, se calcularon los valores hash utilizando los algoritmos SHA256, SHA1 y MD5 para cada elemento evidencial.

---

## Proceso de adquisición de Evidencias

- **EV1_Maquina Virtual OVA:** Esta copia OVA fue importada en un entorno de máquina virtual controlado, donde se recreó exactamente el escenario original de la máquina comprometida. Además, se mantuvo la red activa en esta VM para poder monitorizar y analizar en tiempo real los procesos de red, conexiones y comportamientos que la máquina exhibía.

- **EV2_Memoria RAM:** La captura de la memoria RAM se realizó mediante la herramienta VBoxManage incluidas en VirtualBox, ejecutando el comando dumpvmcore mientras la máquina virtual estaba en estado pausado. Esta técnica permite obtener un volcado completo y coherente de la memoria física de la VM en formato ELF (Executable and Linkable Format), que incluye no solo la RAM sino también metadatos del estado del sistema virtualizado.

- **EV3_Disco Virtual:** La adquisición del disco virtual se realizó utilizando la herramienta FTK Imager, ampliamente reconocida en el ámbito forense para la creación de imágenes forenses bit a bit. Este proceso garantiza una copia exacta e íntegra del disco virtual, incluyendo todas las particiones, el registro de arranque (MBR), el espacio libre y los archivos eliminados, sin alterar en ningún momento el disco original.

- **EV4_01_systeminfo.txt:** En la máquina virtual, se ejecutó el comando systeminfo desde la línea de comandos de Windows. Este comando permitió obtener un informe detallado sobre la configuración del sistema operativo, incluyendo información relevante sobre la versión de Windows instalada, tipo y cantidad de memoria RAM, arquitectura del sistema, detalles del procesador, información del BIOS, y datos sobre la red y actualizaciones instaladas.

- **EV5_02_ipconfig_all.txt:** En la máquina virtual se ejecutó el comando ipconfig /all desde la consola de Windows para obtener un informe completo de la configuración de red TCP/IP de todos los adaptadores presentes. Este comando proporciona información detallada como las direcciones IPv4 e IPv6, máscaras de subred, puertas de enlace predeterminadas, servidores DHCP, servidores DNS, estado de la conexión y dirección MAC, entre otros datos relevantes para el análisis forense de red.

- **EV6_03_routeprint.txt:** En la máquina virtual se ejecutó el comando route print desde la consola de Windows para obtener la tabla de enrutamiento IP completa del sistema. Este comando muestra todas las rutas configuradas en el equipo, incluyendo destinos, máscaras de subred, puertas de enlace, interfaces, métricas y tipos de rutas (como rutas estáticas y dinámicas). La información obtenida permite entender cómo el sistema enruta el tráfico de red hacia diferentes redes o máquinas, clave para analizar la configuración y comportamiento de la red de la máquina víctima.

- **EV7_04_arp.txt:** En la máquina virtual se ejecutó el comando arp -a desde la consola de Windows, que permite visualizar la tabla ARP (Address Resolution Protocol) actual. Esta tabla contiene las asociaciones entre direcciones IP y direcciones físicas MAC de los dispositivos en la red local con los que la máquina ha interactuado. El comando muestra información clave para identificar dispositivos conectados a la red y resolver direcciones, facilitando el análisis de redes y detección de posibles dispositivos no autorizados o anomalías.

- **EV8_05_netstat_ano.txt:** En la máquina virtual se ejecutó el comando netstat -ano desde la consola de Windows. Este comando muestra todas las conexiones de red activas, tanto entrantes como salientes, junto con el estado de cada conexión, las direcciones IP y puertos usados, y el identificador del proceso (PID) que mantiene cada conexión. Este nivel de detalle permite mapear procesos específicos a conexiones de red y sirve para detectar conexiones sospechosas o inusuales, muy útil en análisis e investigación forense para entender la actividad de red del sistema.

- **EV9_06_tasklist_v.txt:** En la máquina virtual se ejecutó el comando tasklist /v desde la consola de Windows. Este comando muestra un listado detallado de los procesos en ejecución, incluyendo información ampliada como el identificador de proceso (PID), uso de memoria, tiempo de CPU, el usuario que inició el proceso, estado y el título de la ventana asociado. Esta granularidad permite un análisis exhaustivo de los procesos activos en el sistema víctima, ayudando a identificar posibles aplicaciones maliciosas, procesos sospechosos o cuellos de botella en recursos.

- **EV10_07_wmic_process_full.txt:** En la máquina virtual se ejecutó el comando wmic process list full desde la consola de Windows. Este comando genera un listado completo y detallado de todos los procesos en ejecución en el sistema, incluyendo todas sus propiedades y atributos disponibles mediante Windows Management Instrumentation (WMI). La salida incluye información como el identificador de proceso (PID), estado, uso de memoria, tiempo de ejecución, nombre del ejecutable, ruta del archivo, prioridad, usuario asociado, y muchos otros detalles técnicos que permiten un análisis exhaustivo de los procesos activos en la máquina víctima.

- **EV11_08_schtasks.txt:** En la máquina virtual se ejecutó el comando SCHTASK /QUERY /FO LIST /V desde la consola de Windows para obtener una lista detallada y completa de todas las tareas programadas del sistema. Este comando proporciona una vista exhaustiva que incluye el nombre de la tarea, estado, desencadenantes, última ejecución, próxima ejecución, usuario bajo el cual corre la tarea, y otra información relevante para identificar actividades automatizadas, planificadas legítimas o potencialmente maliciosas que podrían estar presentes en el sistema.

- **EV12_09_logger_users.txt:** En la máquina virtual se ejecutó el comando query users desde la consola de Windows. Este comando recupera información sobre las sesiones de usuario activas en el sistema, mostrando datos como nombre de usuario, nombre de sesión, ID de sesión, estado (activo o desconectado), tiempo de inactividad y la hora en la que el usuario inició sesión. Este reporte es útil en análisis forense para determinar qué usuarios permanecían conectados o tenían sesiones activas en el momento del análisis, aportando evidencia sobre la actividad y acceso al sistema.

- **EV13_10_env_vars.txt:** En la máquina virtual se ejecutó el comando SET desde la consola de Windows para listar todas las variables de entorno activas en el sistema en ese momento. Este comando muestra un listado completo de las variables en formato nombre=valor, que incluyen rutas del sistema, configuraciones de usuario, variables relacionadas con software instalado, y otras configuraciones del entorno operativo que afectan el comportamiento de procesos y aplicaciones.

---

## Almacenamiento de la Evidencia

El almacenamiento de la evidencia se realizó trasladando todos los archivos obtenidos durante la investigación desde la máquina virtual a la máquina local mediante una carpeta compartida configurada entre ambas. Este método permitió copiar de manera segura y eficiente los archivos sin alterar la evidencia original. Además, se mantuvo un orden estricto en la estructuración de las carpetas locales, organizándolas de forma clara y sistemática para facilitar la gestión, identificación y acceso posterior a cada tipo de evidencia.

El orden de las evidencias se ha mantenido conforme a una metodología forense reconocida, que establece fases claras y rigurosas para garantizar la integridad, validez y trazabilidad de las pruebas digitales. Esta metodología considera etapas como la identificación, recolección, adquisición, almacenamiento, análisis y presentación de las evidencias.
