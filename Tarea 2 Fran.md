# Guía de Comandos Básicos de Linux

## Índice d la tarea
* [1. Introducción](#1-introducción)
* [2. Navegación por el Sistema de Archivos](#2-navegación-por-el-sistema-de-archivos)
* [3. Gestión de Archivos y Directorios](#3-gestión-de-archivos-y-directorios)
* [4. Comandos de Red e Información del Sistema](#4-comandos-de-red-e-información-del-sistema)

## 1. Introducción
Esta guía tiene como **objetivo principal** proporcionar un recurso rápido y accesible para aprender los *comandos fundamentales* de la terminal de Linux. Está diseñada tanto para principiantes que se acercan por primera vez al sistema operativo como para usuarios que necesitan un recordatorio rápido de su sintaxis.

> ⚠️ **Aviso:** La terminal de Linux distingue estrictamente entre mayúsculas y minúsculas. Asegúrate de escribir los comandos exactamente como se especifican.

---

## 2. Navegación por el Sistema de Archivos

### 2.1 Moverse entre carpetas
Para desplazarte por las rutas del sistema de archivos, los comandos más comunes son:

* `pwd`: Muestra de forma exacta la ruta del directorio actual donde te encuentras trabajando.
* `cd`: Cambia el directorio de trabajo actual a la ruta especificada (por ejemplo, `cd /var/log`).
* `ls`: Lista los archivos y carpetas contenidos en el directorio actual.

---

## 3. Gestión de Archivos y Directorios

### 3.1 Operaciones comunes con archivos
La siguiente tabla muestra herramientas fundamentales para administrar tus elementos dentro del sistema operativo.

| Comando | Descripción | Ejemplo de Uso |
| :--- | :--- | :--- |
| `mkdir` | Crea un nuevo directorio o carpeta vacía | `mkdir mi_proyecto` |
| `rm` | Elimina archivos o directorios permanentemente | `rm notas.txt` |
| `cp` | Copia archivos o directorios a otra ubicación | `cp foto.png /respaldo/` |

### 3.2 Pasos para crear un script ejecutable sencillo
1. Crea un archivo de texto vacío con el comando `touch script.sh`.
2. Asígnale permisos de ejecución en el sistema operativo mediante el comando `chmod +x script.sh`.
3. Abre el archivo y añade código estructurado indicando el intérprete correspondiente:

```bash
#!/bin/bash
echo "¡Hola, Mundo desde la terminal de Linux!,¿Que tal?"
```

---

## 4. Comandos de Red e Información del Sistema

### 4.1 Comprobación de conectividad
Para verificar las direcciones IP de tus interfaces de red de forma rápida, puedes utilizar directamente el comando en línea `ip addr` dentro de tu consola.

Si deseas profundizar tus conocimientos en la gestión avanzada de servidores y entornos de terminal, te recomendamos visitar la [Documentación Oficial de Ubuntu](https://ubuntu.com), donde encontrarás guías detalladas paso a paso.
![imagen obuntu](https://blog.desdelinux.net/wp-content/uploads/2011/10/logo-ubuntu.png)

##Informacion del proyecto
##Proximas mejoras.
Apliacion de comandos
Profundidad en la explicacion 
ejemplos mas desarrollados
