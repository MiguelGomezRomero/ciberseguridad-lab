# Laboratorio de ciberseguridad

Laboratorio personal para aprender ciberseguridad desde los fundamentos: primero Linux, redes y programación, y después seguridad ofensiva y defensiva. Lo voy completando a medida que avanzo.

**Estado:** Fase 1 (fundamentos) en curso.

## Entorno

- **VirtualBox** con máquinas virtuales aisladas del equipo anfitrión.
- **Debian 13** sin entorno gráfico, instalado a mano, con snapshots para volver a un estado limpio.
- Red NAT con reenvío de puertos y **acceso por SSH** desde el anfitrión.
- **Kali Linux** como máquina para las prácticas ofensivas.

## Lo que he practicado

- **Shell de Linux:** cómo ejecuta los comandos, `PATH`, redirecciones, tuberías y cómo consultar `man` y `--help`.
- **Usuarios y permisos:** `/etc/passwd` y `/etc/shadow`, permisos en octal, `sudo` y el principio de mínimo privilegio.
- **Hashes de contraseñas:** por qué un hash no es cifrado y para qué sirve la sal.
- **SUID:** cómo funciona, por qué es un vector habitual de escalada de privilegios y cómo localizar los binarios SUID de un sistema.

## Hoja de ruta

1. **Fundamentos** (en curso): Linux, redes TCP/IP con Wireshark y Python aplicado a seguridad. Retos de OverTheWire Bandit.
2. **Seguridad ofensiva:** seguridad web (OWASP Top 10), metodología de pentesting y Active Directory.
3. **Defensa:** registros, SIEM, detección de ataques y respuesta a incidentes.
4. **Especialización** en el área que más me interese después de lo anterior.

## Próximos pasos

- Procesos, servicios y `systemd`.
- Resolver OverTheWire Bandit y documentar aquí cada nivel.
