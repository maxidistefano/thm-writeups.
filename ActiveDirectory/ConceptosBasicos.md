# Conceptos Básicos de Active Directory (TryHackMe)

## Objetivo
Entender qué es Active Directory, cómo se organiza y por qué es un componente tan central (y tan atacado) en redes corporativas.

## Herramientas usadas
- Máquina Windows Server de la sala (entorno provisto por TryHackMe)
- Interfaz de administración de Active Directory (consolas nativas de Windows)

## Qué hice
- Repasé la estructura jerárquica de AD: dominio, árbol y bosque, y cómo se relacionan entre sí.
- Exploré Unidades Organizativas (OU) y cómo se usan para agrupar usuarios, equipos y grupos según criterios lógicos (por área, sucursal, etc.).
- Vi la diferencia entre distintos tipos de objetos de AD: usuarios, grupos, equipos y Group Policy Objects (GPO).
- Repasé cómo funciona la autenticación en un dominio con Kerberos y NTLM, y por qué Kerberos es el protocolo preferido hoy en día.
- Entendí el rol del Controlador de Dominio (Domain Controller) como el servidor central que valida identidades y aplica políticas.
- Esto me sirvió para entender por qué tantos ataques reales apuntan justo a AD: si comprometés el dominio, tenés acceso a prácticamente toda la red de una empresa.

## Conceptos clave aprendidos
- Por qué las GPO son la forma en que una empresa aplica configuraciones y restricciones a muchos equipos/usuarios a la vez, sin tocar cada máquina a mano.
- La diferencia entre autenticación (verificar quién sos) y autorización (qué tenés permitido hacer) dentro del modelo de AD.
- Por qué AD es un objetivo tan atractivo en ciberseguridad: centraliza identidades y permisos de toda una organización en un solo lugar.

---
*Nota: este writeup no incluye flags ni respuestas exactas de la sala, respetando las reglas de TryHackMe.*
