"# Klipper_Modular" 

Modo de activar la configuración de la impresora:

1.- El archivo printer.cfg contiene los includes a estas carpetas:

	calibration -> CALIBRACIÓN (bed_mesh, firmware_retraction, input_shaper, print_area_bed_mesh, safe_z_home, screws, z_tilt)

	devices     -> DISPOSITIVOS (adxl345, chamber, filament_sensor, gpio, htu21d, max31865, neopixel, other, poweroff)

	display     -> PANTALLAS (fysetc_mini12864, klipper-mini12864, menu, menu_calibrate, menu_fast_infill, menu_firmware_retracion, menu_print, menu_temperature_filament)

	machines    -> IMPRESORA (client, extruder, extruder_pt100, fans, heaters, machine, raspi, steppers_xy, steppers_z_belt, steppers_z_t8, uart_steppers)

	macros      -> MACROS (calibration, chamber, change_filament, client_macros, fast_infill, filament_type, leds, macros, mesh, messages, neopixel, printing, print_area_bed_mesh, prusa_slicer_compat, sounds, temperature, timelapse)

	pins        -> PINS MCUS (btt_e3_rrf_board_pins, btt_gtr1_board_pins, btt_mini_e2_v2_board_pins, btt_mot-exp, btt_optopus_board_pins, btt_skr1.4t_board_pins, btt_skr2_board_pins, fysetc_spider_board_pins, mks_genlv2.1_boards_pins, mks_gen_l_v1_board_pins, mks_sgenlv2_boards_pins)

	probe       -> SENSORES CALIBRACIÓN (bl-touch, pinda, probe)
	
	script      -> GENERADOR GRAFICAS (resonancia X e Y)

	shell_command -> COMANDOS DEL SISTEMA (shell_cmd_backup, shell_command)


2. Todos los archivos .cfg que se encuentren en dichas carpetas serán cargados en la configuración.
3. Cada carpeta tiene otra que se llama "inactive" todos los archivos que contenga está carpeta no se cargaran.
4. Modifique los archivos de configuración según las especificaciones de su impresora y muévalos a la carpeta correspondiente para que Klipper los cargue.
5. Cuando no quiera que cargue un archivo de configuración muévalo a la carpeta "inactive". (a está carpeta se le puede cambiar el nombre)
6. Acuérdate de Reiniciar para que Klipper actualice los cambios.


Cualquier aportación será bien recibida.
