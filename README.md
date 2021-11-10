Download sensors.yaml, or open its raw file view and copy into your text editor of choice, then use the find and replace function to replace:

- PRINTER_NAME with the name of the printer instance used in naming the sensors and camera,
- PRINTER_FRIENDLY_NAME with the name to be displayed in dashboard,
- PRINTER_IP with the IP address of the Moonraker and Mainsail instance,
- SCAN_FREQUENCY with the interval in seconds to update the sensors,
- SCAN_FREQUENCY_PREVIEW with the interval in seconds to update the thumbnail image.

Then copy the modified text into your Home Assistant's configuration file, or the appropriate separated .yaml file (I used sensors.yaml).