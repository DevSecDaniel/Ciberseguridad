# Ciberseguridad
Laboratorio Oski:
El contable de la empresa recibió un correo electrónico de un cliente a última hora de la tarde con el asunto "Nuevo pedido urgente". Al intentar acceder a la factura adjunta, descubrió que contenía información de pedido falsa. Posteriormente, la solución SIEM generó una alerta sobre la descarga de un archivo potencialmente malicioso. Tras una investigación inicial, se determinó que el archivo PPT podría ser el responsable de esta descarga. ¿Podría realizar un análisis detallado de este archivo?

Determinar la hora de creación del malware puede proporcionar información sobre su origen. ¿A qué hora se creó el malware?

2022-09-28 17:40

Identificar el servidor de comando y control (C2) con el que se comunica el malware puede ayudar a rastrear al atacante. ¿Con qué servidor C2 se comunica el malware del archivo PPT?

http://171.22.28.221/5c06c05b7b34e8e6.php

Identificar las acciones iniciales del malware tras la infección puede brindar información sobre sus objetivos principales. ¿Cuál es la primera biblioteca que solicita el malware después de la infección?

sqlite3.dll

Al examinar el informe Any.run proporcionado , ¿qué clave RC4 utiliza el malware para descifrar su cadena codificada en base64?

5329514621441247975720749009

Al examinar las técnicas MITRE ATT&CK que se muestran en el informe de Any.run sandbox , identifique la técnica MITRE principal (no las subtécnicas) que utiliza el malware para robar la contraseña del usuario.

T1555

Al examinar los procesos secundarios que se muestran en el informe de la zona de pruebas Any.run , ¿a qué directorio apunta el malware para eliminar todos los archivos DLL ?

C:\ProgramData

Comprender el comportamiento del malware tras la exfiltración de datos puede revelar sus técnicas de evasión. Analizando los procesos secundarios, ¿ cuántos segundos tarda el malware en autoeliminarse tras exfiltrar con éxito los datos del usuario ?

5
