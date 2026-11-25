---
title: Política de privacidad — GN-Slicer
---

# Política de privacidad — GN-Slicer

**Responsable:** GN-Labs · **Contacto:** [gn.labs24@gmail.com](mailto:gn.labs24@gmail.com) · **Vigente desde:** 25 de noviembre de 2026

[English version below](#privacy-policy--gn-slicer)

## Para qué usamos los datos

GN-Slicer prepara modelos para impresión 3D y los lamina en el dispositivo. No crea cuentas de usuario, no incorpora publicidad ni analítica de uso y no envía automáticamente informes de errores al desarrollador. No vendemos los datos tratados por la app ni los usamos para publicidad.

## Datos que quedan en el dispositivo

La app guarda copias de los modelos y proyectos abiertos, su lista de recientes y nombres visibles, perfiles y ajustes, preferencias de interfaz y resultados del laminado. También utiliza archivos temporales para editar y laminar. Esos datos permiten retomar el trabajo y generar los archivos de impresión sin un servicio de laminado remoto.

Las conexiones de impresora incluyen dirección, perfil asociado, número de serie cuando corresponde y código LAN o clave de acceso. La app cifra esos registros con AES-GCM y una clave de Android Keystore; conserva un índice de identificadores locales. El cifrado adicional de conexiones no significa que todos los modelos o archivos exportados estén cifrados por GN-Slicer. La app deshabilita su copia de seguridad estándar de Android y guarda las conexiones en el directorio excluido de copias.

## Datos que pueden salir del dispositivo

Cuando eliges Enviar, el destino que configuraste recibe el archivo laminado y su nombre, los datos necesarios para autenticar la conexión y las órdenes que confirmas. La comunicación de estado utiliza identificadores del protocolo y, en Bambu LAN, el número de serie. El destinatario puede conservar el archivo en su almacenamiento; la app no lo borra remotamente al cerrar la conexión.

Bambu LAN se limita a direcciones locales y usa TLS. Moonraker admite HTTP en direcciones locales y HTTPS también en destinos públicos configurados por el usuario. Por eso **no afirmamos que toda comunicación sea exclusivamente local ni que todo envío esté cifrado**: HTTP no cifra el archivo ni la clave de acceso en tránsito. Utiliza únicamente destinos y redes de confianza; para Moonraker, prefiere HTTPS.

Al abrir o guardar mediante el selector de Android, eliges el proveedor de documentos. Si es un servicio de nube, ese proveedor puede transferir o almacenar el archivo según su propia política. Los enlaces de código fuente se abren, si los pulsas, en una aplicación externa. Estos destinos no son un servicio de almacenamiento o analítica del desarrollador de GN-Slicer.

## Diagnóstico

La app permite ver y copiar al portapapeles un diagnóstico local con versiones, tiempos y memoria utilizada; no incluye modelos, rutas, credenciales ni identificadores de trabajos. Copiarlo no lo envía al equipo. Si decides pegarlo en otra app para pedir ayuda, revisa el contenido y las condiciones de ese destino antes de compartirlo.

## Compra en Google Play

GN-Slicer se compra en Google Play. El pago lo procesa Google según sus propias condiciones y política de privacidad; la app no recibe ni guarda datos de pago.

## Conservación y eliminación

Los datos locales permanecen mientras sean necesarios para el trabajo o hasta su limpieza o eliminación. La app retira determinadas copias que dejan de figurar en recientes y usa cachés, pero no promete un plazo fijo para todos los archivos. Puedes eliminar los datos privados desde los ajustes de almacenamiento de la app en Android o al desinstalarla: esa acción pierde el trabajo local, por lo que conviene exportar antes lo que quieras conservar.

Los originales y archivos exportados en carpetas o proveedores externos, las copias enviadas a impresoras y los textos pegados en otras apps no se eliminan al borrar GN-Slicer. Debes gestionarlos en cada destino. No hay una cuenta de GN-Slicer ni un servidor propio de modelos que permitan recuperar o borrar esas copias a distancia.

## Contacto y cambios

Para consultas, correcciones o solicitudes sobre datos enviados voluntariamente al equipo, escribe a [gn.labs24@gmail.com](mailto:gn.labs24@gmail.com). No envíes claves, códigos LAN ni modelos privados. Si cambia el tratamiento de datos, se actualizarán esta política y la declaración de la tienda antes de distribuir esa funcionalidad.

---

# Privacy policy — GN-Slicer

**Data controller:** GN-Labs · **Contact:** [gn.labs24@gmail.com](mailto:gn.labs24@gmail.com) · **Effective date:** 25 November 2026

## Why we use data

GN-Slicer prepares models for 3D printing and slices them on your device. It does not create user accounts, include advertising or usage analytics, or automatically send error reports to the developer. We do not sell data handled by the app or use it for advertising.

## Data kept on your device

The app keeps copies of opened models and projects, the recent-files list and display names, profiles and settings, interface preferences and slicing results. It also uses temporary files for editing and slicing. These records let you resume your work and generate print files without a remote slicing service.

Printer connections include the address, associated profile, serial number where applicable, and LAN code or access key. The app encrypts these records with AES-GCM using an Android Keystore key and keeps an index of local identifiers. This additional protection for connections does not mean GN-Slicer encrypts every model or exported file. The app disables standard Android backup and stores connections in the directory excluded from backups.

## Data that may leave your device

When you choose Send, your configured destination receives the sliced file and its name, the information needed to authenticate the connection, and commands you confirm. Status communication uses protocol identifiers and, for Bambu LAN, the printer serial number. The recipient may retain the file in its storage; the app does not remotely delete it when closing the connection.

Bambu LAN is restricted to local addresses and uses TLS. Moonraker allows HTTP on local addresses and HTTPS also to public destinations configured by the user. We therefore **do not claim that all communication is local or that every transfer is encrypted**: HTTP does not encrypt the file or access key in transit. Use only destinations and networks you trust; prefer HTTPS for Moonraker.

When opening or saving through Android's file picker, you choose the document provider. A cloud provider may transfer or store the file under its own policy. Source-code links, if you tap them, open in an external application. These destinations are not a storage or analytics service operated by the GN-Slicer developer.

## Diagnostics

The app lets you view and copy local diagnostics to the clipboard, including versions, timings and memory use. These diagnostics exclude models, paths, credentials and job identifiers. Copying does not send them to the team. If you choose to paste them into another app to request help, review the contents and that destination's terms before sharing.

## Purchase on Google Play

GN-Slicer is purchased on Google Play. Payment is processed by Google under its own terms and privacy policy; the app does not receive or store payment data.

## Retention and deletion

Local data remains while needed for your work or until it is cleaned up or deleted. The app removes certain copies no longer referenced in recent files and uses caches, but does not promise a fixed retention period for every file. You can remove private app data through Android's app storage settings or by uninstalling. This loses local work, so export anything you want to keep first.

Originals and exports in external folders or providers, copies sent to printers and text pasted into other apps are not deleted when you remove GN-Slicer. Manage those copies at each destination. There is no GN-Slicer account or developer-operated model server that can recover or delete them remotely.

## Contact and changes

For questions, corrections or requests concerning information voluntarily sent to the team, write to [gn.labs24@gmail.com](mailto:gn.labs24@gmail.com). Do not send passwords, LAN codes or private models. If data handling changes, this policy and the store declaration will be updated before distributing that functionality.
