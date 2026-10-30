# Reporte-Ciberseguridad
Reporte Técnico de Configuración de Laboratorio

# Mi primer laboratorio seguro de ciberseguridad

## Descripción

Este proyecto consiste en la creación y configuración de un laboratorio virtual de ciberseguridad utilizando Oracle VirtualBox.

El objetivo fue construir un entorno controlado para practicar conceptos básicos de seguridad informática, virtualización, administración de sistemas y configuración de redes.

## Tecnologías utilizadas

- Oracle VirtualBox
- Windows 10 (sistema anfitrión)
- Windows 11 (máquina virtual)
- Ubuntu Linux (máquina virtual)

## Configuración del laboratorio

Se crearon dos máquinas virtuales con los siguientes recursos:

| Máquina virtual | RAM | CPU |
|-----------------|----:|---:|
| Windows 11      | 8 GB | 2 |
| Ubuntu Linux    | 4 GB | 2 |

## Actividades realizadas

- Configuración de redes virtuales mediante NAT y Red Interna.
- Creación de un usuario estándar en Windows 11.
- Verificación de actualizaciones del sistema operativo.
- Actualización de repositorios en Ubuntu mediante `sudo apt update`.
- Creación de archivos y revisión de permisos mediante `ls -l`.
- Creación de una instantánea (*snapshot*) para recuperar el estado de la máquina virtual.

## Objetivos de seguridad aplicados

**Aislamiento:** controlar la comunicación de las máquinas virtuales mediante redes virtuales.

**Mínimo privilegio:** utilizar cuentas estándar para las tareas que no requieren permisos administrativos.

**Recuperabilidad:** conservar un punto de restauración mediante instantáneas de VirtualBox.

## Documentación

El proyecto incluye un reporte técnico en formato PDF con el procedimiento realizado y las evidencias de configuración.



# Autor

Geronimo Bondesio

Proyecto realizado como parte de mi formación inicial en ciberseguridad.
