# Linux Fundamentals – Parte 1 (TryHackMe)

## Objetivo
Practicar los conceptos básicos de Linux necesarios para moverse con soltura en una terminal: conexión remota, navegación del sistema de archivos, comandos esenciales y ayuda integrada del sistema.

## Herramientas usadas
- Terminal Linux (conexión SSH a la máquina de la sala)
- Comandos nativos de Linux (sin herramientas externas)

## Qué hice
- Me conecté a la máquina de la sala vía **SSH** desde la terminal, usando las credenciales provistas por el laboratorio.
- Practiqué navegación por el sistema de archivos con comandos como `pwd`, `ls`, `cd` y `cat`, entendiendo la diferencia entre rutas absolutas y relativas.
- Usé comandos de ayuda integrados (`man`, `--help`) para investigar opciones de comandos que no conocía, en lugar de memorizarlos de antemano.
- Exploré la estructura estándar de directorios de Linux (`/home`, `/etc`, `/var`, `/usr`, entre otros) y para qué se usa cada uno.
- Practiqué redirección de salida y encadenado de comandos con `>`, `>>` y `|` para combinar herramientas simples y obtener resultados más específicos.
- Esto lo uso después todo el tiempo — para leer logs, ver qué procesos corren o revisar archivos raros cuando algo falla.

## Conceptos clave aprendidos
- La filosofía de Linux de "todo es un archivo" y por qué eso simplifica la administración del sistema.
- La importancia de saber leer documentación de comandos (`man`) en vez de depender de recordar sintaxis exacta.
- Diferencias entre permisos, usuarios y rutas que sientan la base para temas más avanzados (permisos de archivos, gestión de usuarios) que se ven en la Parte 2.

---
*Nota: este writeup no incluye flags ni respuestas exactas de la sala, respetando las reglas de TryHackMe.*
