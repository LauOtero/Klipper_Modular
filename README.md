"# Klipper_Modular" 

Modo de activar la configuración de la impresora:

1.- El archivo printer.cfg contiene los includes a estas carpetas:

calibration
devices
display
machines
macros
pins
probe
shell_command

2. Todos los archivos .cfg que se encuentren en dicha carpeta serán cargados en la configuración.
3. Cada carpeta tiene otra que se llama "inactive" todos los archivos que contenga está carpeta no se cargan.
4. Modifique los archivos de configuración según las especificaciones de su impresora y muévalos a la carpeta correspondiente para que Klipper los cargue.
5. Para que no cargue cualquier archivo de configuración muévalo a la carpeta "inactive". (a está carpeta se le puede cambiar el nombre)
6. Acuérdate de Reiniciar para que Klipper actualice los cambios.


Cualquier aportación será bien recibida.
