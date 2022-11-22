---
layout: post
title:  ¿Cómo eliminar un virus de mi computador?
date:   2022-11-21 09:20:35 +0300
image:  malware.jpg
tags:   Tutorial
---
Con la proliferación de sitios web engañosos que, ofrecen contenido gratuito que al final no lo es, ha incrementado la cantidad de equipos infectados con diversos tipos de malware, los cuales producen diferentes síntomas.

## __¿Cómo reconocer si mi computadora está infectada?__
No todas las infecciones de malware producen síntomas que permitan al usuario final reconocer que ha sido infectado. Todo depente del propósito de la infección. En los casos en los que el atacante tiene como objeto el robo de información, se hace dificil su detección.

Como regla general, se analizan los siguientes síntomas para infecciones:

* Sin motivo aparente, la computadora está lenta
* Aparición de ventanas emergentes con publicidad
* El acceso al disco duro es recurrente aún sin estar ejecutando programas
* La presencia de archivos desconocidos 
* La asusencia de archivos personales

Si estos extraños síntomas se presentan y tu solución de protección no detectó la amenaza, puedes recurrir a herramientas alternativas con las que, puedes corregir el problema.

## Hacer un scan
Algunos fabricantes de antimalware ofrecen la opción de descargar herramientas gratuitas para la ejecución de exámenes. De todos los fabricantes que ofrecen esta opción recomendamos usar [Microsoft Safety Scan](https://learn.microsoft.com/es-mx/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide)

Si deseas una alternativa, puedes usar [Kaspersky Removal Tool](https://www.kaspersky.com/downloads/free-virus-removal-tool)

## Revisar procesos extraños
Si el computador muestra frecuentemente ventanas emergentes con publicidad o si luego de una infección recibe una notificación de que alguna aplicación no pudo ser cargada, puede usar la herramienta Autoruns de la suite Microsoft Sysinternals para verificar los procesos que son cargados durante el inicio del sistema operativo. Puede descargar la herramienta desde el siguiente [enlace](https://docs.microsoft.com/es-mx/sysinternals/downloads/autoruns)

![]({{ site.baseurl }}/images/autoruns.png)

Al ejecutar el programa, se genera una lista de todos los procesos involucrados en el Inicio de Windows. Para identificar los procesos dañidos, se pueden tomar diversos criterios, entre ellos:

* Usted reconoce que el nombre de la carpeta donde está el ejecutable no corresponde al sistema operativo o alguna aplicación que haya instalado 
* Si el proceso tiene firma digital
* Se puede hacer una evaluación del proceso usando Virustotal desde la herramienta
* Una tarea de Windows se utiliza para ejecutar un archivo desconocido


Existen algunos casos que es requerido la asistencia de un experto. Para eliminación efectiva de virus y otros malware,
 estamos a tu orden: [Beltpich Servicios y Consultorías](https://www.beltpich.com).