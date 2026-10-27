# Home Sweet Cloud: guia para la prueba

## Que necesitas

- Un telefono con Android 7 o posterior. Las pruebas iniciales cubren un Samsung
  A55; otras marcas y versiones se validaran con los participantes.
- Una computadora con Windows 10 u 11 de 64 bits, encendida y conectada a la
  misma red local que el telefono.
- Espacio disponible en el disco para tus fotos y videos.

## Instalar en Windows

1. Descarga el instalador desde la
   [version de prueba oficial](https://github.com/homesweetcloud-app/home-sweet-cloud-downloads/releases/tag/v0.1.0-rc3).
2. Si quieres comprobar el archivo, ejecuta en PowerShell
   `Get-FileHash .\HomeSweetCloud-Windows-0.1.0-rc3.exe -Algorithm SHA256`
   y compara el resultado con `SHA256SUMS.txt` del mismo paquete.
3. Ejecuta el instalador y abre Home Sweet Cloud. El instalador actual no tiene
   firma digital de editor; Windows puede mostrar una advertencia. Si tienes
   dudas sobre el origen, consulta al responsable antes de continuar.
4. La app inicia con tu sesion de Windows. Cerrar su ventana la conserva en la
   bandeja del sistema. La computadora debe permanecer encendida y activa;
   suspendida no puede recibir respaldos.

## Instalar y vincular Android

1. Cuando se habilite la prueba cerrada, acepta la invitacion con la cuenta de
   Google registrada como tester e instala desde Google Play. El enlace de
   participacion aun esta pendiente de crearse.
2. Abre Home Sweet Cloud y concede los permisos de fotos y videos que quieras
   respaldar. La seleccion limitada puede dejar otros archivos fuera.
3. En la misma red Wi-Fi, vincula la app con el codigo temporal mostrado por
   Home Sweet Cloud en la computadora.
4. Sigue las indicaciones de notificaciones y trabajo en segundo plano.

## Uso diario

Los respaldos se procesan automaticamente cuando el servidor vinculado esta
disponible y hay bateria suficiente (35% o conexion a carga). Android decide
cuando ejecutar los trabajos: la revision periodica de 15 minutos no garantiza
que empiece exactamente al cumplirse ese plazo.

No necesitas cable USB para respaldar. Espera a que el archivo aparezca
verificado en la biblioteca de la PC. Puedes conservarlo, revisarlo despues o
enviarlo a la papelera segura. Liberar espacio del telefono requiere tu accion
y la confirmacion de Android; borrar de la PC es una accion diferente.

El almacenamiento predeterminado es `%USERPROFILE%\NubeEnCasaStorage`.
Los originales verificados estan en `verified`; los clasificados para papelera
se mueven a `quarantine`. La fecha de 30 dias no ejecuta borrado automatico en
esta version. Conserva otra copia de los recuerdos importantes: la verificacion
de integridad no protege contra una averia del disco de la PC.

## Reportar un problema

Indica modelo, version de Android/Windows, hora, accion realizada y mensaje
visible. No envies fotos privadas, documentos, codigos de vinculacion ni
credenciales. El responsable puede pedir una captura con los datos personales
ocultos. No desinstales ni borres originales para intentar resolver un error de
respaldo sin comprobar antes la copia en la PC.
