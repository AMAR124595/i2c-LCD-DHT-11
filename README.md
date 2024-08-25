# I2c-LCD-DHT-11
This project involves connecting an I2C LCD display and a DHT11 temperature and humidity sensor to an ESP8266 microcontroller. The setup allows the ESP8266 to read data from the DHT11 sensor and display temperature and humidity values on the I2C LCD screen.
# Aim 
To interface an I2C LCD and a DHT11 sensor with an ESP8266 microcontroller to create a system that continuously monitors and displays real-time temperature and humidity data
# Components
1. Esp8266
2. DHT 11
3. I2C 16x2 LCD display
# Connetion 
![esp8266_LCD](https://github.com/user-attachments/assets/3b40e17b-8f19-4ea8-88a0-64f0b9ece837)
* D1  ---->SLC
* D2  ---->SDL
* VCC ---->5V
* GND ---->GND
![1](https://github.com/user-attachments/assets/c81440ad-0b56-486f-9bf5-205bfa18688e)
* D6  ---->DATA
* VCC ---->5V
* GND ---->GND
#  Procedure
1. Arduino IDE ----> File ----> Preferences ----> Paste ULR
   * ( http://arduino.esp8266.com/stable/package_esp8266com_index.json )
2. Interface ESP 8266 with DHT 11 Sensor and display the value on the Serial Monitor.
   *  Library ----> ( https://github.com/adafruit/Adafruit_Sensor.git )
3. Interface ESP 8266 With I2C 16x2 LCD display and display the value on the LCD.
  *  Library ----> [https://github.com/adafruit/Adafruit_Sensor.git ](https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library.git)
4. Interface Both LCD and DHT11 with ESP 8266 ,display the value parameters and value of dht 11 on display
  


    
