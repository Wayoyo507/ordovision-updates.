# OrdoVision — descargas

**Windows 0.1.5 · Android 1.0.4 (código 5)**

[Descargar los instaladores](https://github.com/Wayoyo507/ordovision-updates./releases/tag/apps-connectivity-2026-10-10)

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

