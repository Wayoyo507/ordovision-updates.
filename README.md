# OrdoVision — descargas

**Windows 0.1.11 · Android 1.0.9 (código 10)**

- [Descargar para Windows](https://github.com/Wayoyo507/ordovision-updates%2E/releases/download/windows-0.1.11/OrdoVision-Windows-0.1.11.exe)
- [Descargar para Android](https://github.com/Wayoyo507/ordovision-updates%2E/releases/download/apps-pc-0.1.9-android-1.0.9/OrdoVision-Android-1.0.9.apk)
- [Ver detalles y hashes de la publicación](https://github.com/Wayoyo507/ordovision-updates./releases/tag/apps-pc-0.1.9-android-1.0.9)

La misma interfaz se incluye dentro de las aplicaciones. Después de iniciar sesión y cargar los datos con internet, abre automáticamente la copia local cuando falta señal. Daily Report y cenas conservan las ediciones y las sincronizan al recuperar conexión. Los conflictos se revisan antes de sustituir cambios de otro equipo.

Las lecturas guardadas de Sheets y Cloudbeds no contienen cambios nuevos que aún no hayan llegado al dispositivo. Nuevas reservas, check-in/check-out, tours, horarios y administración todavía requieren conexión para guardar. No todas las acciones admiten edición offline.

## Actualizar

- PC: menú **OrdoVision → Buscar actualizaciones**.
- Android: **OrdoVision · Opciones → Buscar actualizaciones**.
- La descarga abre el navegador; confirma la instalación sobre la versión anterior. Cierra la aplicación antes de instalar. No borres almacenamiento ni desinstales con cambios pendientes.
- Una copia antigua protegida con PIN lo solicita una sola vez para migrar; después abre automáticamente. Cerrar sesión bloquea la copia hasta volver a autenticarse con internet.

Se conserva la firma Android de distribución. Windows requiere x64, versión 2004 o posterior; el instalador no tiene certificado de editor. Se mantiene la impresión nativa y su vista previa.

## Verificación

Pruebas de interfaz de escritorio y móvil: guardados offline, recarga, reconexión, conflictos, migración de PIN, cierre de sesión y usuario recordado. Electron real: apertura en frío sin red y recuperación de la edición guardada. APK actual compilado y firmado. La versión 1.0.3 anterior abrió su inicio de sesión en un emulador Pixel 7 Pro con modo avión y Wi-Fi desactivado. Falta validar lectura y edición autenticadas offline en Android. La actualización completa entre dos instalaciones sigue pendiente de verificar en dispositivo.

Este repositorio contiene instaladores y su manifiesto de versiones. No contiene información del hotel, cuentas ni claves de firma.

## Corrección de consultas y pestañas

Esta entrega elimina el bloqueo de ADR, Gráficas y otras consultas cuando hay conexión. Un error de otra fuente o una copia guardada no impiden consultar la web. ADR y Gráficas conservan su última respuesta completa sin señal y se recargan automáticamente al recuperar conexión. Probado en escritorio y móvil, manteniendo independientes las reglas financieras y operativas.


## Revisión funcional del 11 de octubre

Mapa con dependencias indirectas, pruebas asociadas, referencias verificables y diagnóstico que conserva el historial. Correcciones de notas para gerente de salón, copia local del horario recién guardado y aviso de lectura anterior cuando falla una fuente. Interfaz offline protegida frente a descargas incompletas. 141 pruebas de lógica y servidor y 30 escenarios de interfaz aprobados. La validación nativa de Android y la impresión física siguen pendientes; no se certifica el 100 % de los escenarios.

## Avisos en la campanita · web 244

Los cambios pendientes se muestran en la campanita y suman al contador. La comparación muestra únicamente las diferencias con etiquetas comprensibles; no expone el bloque de datos técnicos. Cerrar el aviso no descarta nada. Mantiene las opciones de conservar la web o aplicar los cambios del dispositivo tras confirmación.

El instalador Windows 0.1.6 terminó correctamente en el nuevo intento, sin cambiar protecciones. Sustituye al bloqueo anterior. Ambos paquetes incluyen la misma interfaz web 244 y las mejoras de horarios ya publicadas. Se verificaron 6 escenarios de interfaz, 2 pruebas de comparación, recuperación offline en Electron, firma Android y coincidencia de los 12 recursos requeridos. Instalación completa sobre la versión anterior, Android en dispositivo y una impresora física siguen pendientes de prueba.

Windows 0.1.6 se subió correctamente y su tamaño y SHA256 coinciden con el instalador local. Buscar actualizaciones ofrece esta versión.
## Windows 0.1.11

Backend compartido Cloudflare. Datos locales anteriores conservados por origen, sin migracion entre bases. Iniciar sesion nuevamente. Pendientes: acceso con cuenta real y prueba completa de actualizacion instalada. Instalador sin certificado de editor.

[Detalles y SHA-256 de Windows 0.1.11](https://github.com/Wayoyo507/ordovision-updates./releases/tag/windows-0.1.11)
