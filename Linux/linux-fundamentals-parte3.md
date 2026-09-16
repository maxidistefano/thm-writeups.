## Objetivo
Cerrar la base de Linux con manejo de texto, edición de archivos desde terminal, compresión/archivado y nociones básicas de red y scripting.

## Herramientas usadas
- Terminal Linux (conexión SSH a la máquina de la sala)
- Comandos nativos de Linux (sin herramientas externas)

## Qué hice
- Procesé texto con `grep`, `cut` y `sed` para buscar y filtrar información dentro de archivos, algo que después se aplica directo a revisar logs.
- Edité archivos directamente en terminal con `nano`, y probé lo básico de `vim` para poder moverme si me toca un servidor sin interfaz gráfica.
- Comprimí y descomprimí archivos con `tar` y `gzip`, entendiendo la diferencia entre archivar y comprimir.
- Revisé conectividad y configuración de red con `ifconfig`/`ip` y `netstat`, viendo qué puertos y conexiones tenía activos el sistema.
- Escribí un script simple en bash para automatizar una tarea repetitiva, usando variables y un condicional básico.
- Lo de `grep` y filtrar texto es lo que más rescato de esta parte — es literalmente lo que vas a hacer todo el tiempo cuando tengas que buscar algo puntual en un log gigante.

## Conceptos clave aprendidos
- Cómo combinar comandos con pipes para ir filtrando información hasta llegar a lo que buscás, en vez de leer un archivo entero a mano.
- Diferencia entre comprimir (reducir tamaño) y archivar (empaquetar varios archivos en uno), y por qué `tar.gz` combina ambas cosas.
- Nociones básicas de qué mirar en la configuración de red de una máquina para entender cómo está conectada.
