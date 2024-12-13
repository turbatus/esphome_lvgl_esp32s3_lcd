# esphome_lvgl_esp32s3_lcd
Esphome powered 7inch LCD dev board (ESP32S3)  
Inspiration sources are mentioned in comments inside the yaml files

### This repo only hosts the relevant hardware yaml files for the 7" ESP32S3 LCD screen
Everything else is just common Homeasisstant stuff, sensors, switches, etc.

### I have modded the LCD a little, to add PWM capabilities to the backlight 
The LCD can only turn the backlight on and off. If you need to adjust the brightness, you need to modify the hardware. There is a reserved pad, next to the ESP32S3 module (picture 1).
You can control the backlight with a 1khz pwm signal applied on that pad.
I connected it to the ADC pin, as it has a dedicated header on the back of the LCD. (picture 2)

![image](https://github.com/user-attachments/assets/af2bb7c0-7ee2-4a6a-874d-4451b36c0ad6)


![IMG20241213085419](https://github.com/user-attachments/assets/81657d15-0701-412f-b8a7-78dac5aeb99e)

