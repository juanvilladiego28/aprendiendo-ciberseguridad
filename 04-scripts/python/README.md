# Scripts en Python

Esta carpeta contiene scripts desarrollados como parte de mi proceso de
aprendizaje en Python y ciberseguridad.

Tengo conocimientos en Python y utilizo herramientas de inteligencia artificial
como apoyo para mejorar la estructura, claridad y buenas prácticas del código,
siempre comprendiendo su funcionamiento y realizando ajustes manuales.

El objetivo es aprender a escribir código más limpio, reutilizable y orientado
a la automatización.

---

## Enfoque y propósito

Los scripts están pensados como **plantillas reutilizables**, no como herramientas
de ataque. Su finalidad es practicar:

- automatización básica
- manejo de archivos
- estructuras de control
- organización de código
- procesamiento de datos
- uso responsable de librerías

Todo el contenido se utiliza exclusivamente en entornos controlados y autorizados.

---

## Relación con la preparación para OSCP

Este trabajo forma parte de mi preparación a largo plazo para certificaciones
prácticas como **OSCP**.

La idea es entrenar habilidades clave que se evalúan en este tipo de certificaciones:

- pensamiento lógico y estructurado
- adaptación de scripts a distintos escenarios
- automatización de tareas repetitivas
- análisis de entradas y salidas
- creación de herramientas propias
- comprensión del flujo de un programa

No se incluyen exploits ni código malicioso.

---

## Cómo funciona la plantilla

El archivo `pentesting_tool_template.py` está diseñado para que solo sea necesario
modificar una parte específica del código: la función `accion()`.

El resto del programa (lectura de archivos, ejecución, guardado de resultados)
permanece igual.

Esto permite reutilizar la estructura para distintos tipos de ejercicios.

---

## Modificación de la función `accion()`

A continuación se describen los distintos usos que puede tener esta función,
según el tipo de práctica que se quiera realizar.
