# smart-agricultural-system
A proteus implementation of a smart agricultural system

![Capture (1)](https://user-images.githubusercontent.com/46398353/141159883-cd5e3d42-7750-4b69-8cbd-aa41a2dbc09f.png)


## Components used

- Required Components
- Arduino Mega
- Temperature sensor
- Moisture sensor 
- Humidity sensor
- Ph meter
- Light bulbs
- Liquid Crystal Display
- Motor
- Water pump
- Water pump Controller
- 5V Battery
- Jumper Wires
- GSM


## Architecture

A crucial part of our project is taking measurements from the environment. Our projects need a total of 4 sensors connected at all times. All the sensors will be taking values and passing them to the Arduino. The Arduino will give instructions to other components accordingly to adjust the environmental parameters which are optimal for the plant growth. 

### Sensors:
- Temperature sensor - Measures temperature
- Moisture sensor - Measures Moisture content of the soil
- Humidity Sensor - Measures humidity 
- Ph Sensor - Measures acidity of the soil
- Arduino: Arduino Mega 2560 - All the sensor’s input will be fed to the Arduino


### Output Components: 
- Water Pump - When the moisture level of the soil falls below a certain level, then the water pump turns on.
- Water Spray - When the relative humidity of the air falls below 50, then the water spray turns on. The water spray also turns on when the temperature rises above 20 degrees Celsius
- Exhaust Fan -  An exhaust fan is used to increase the airflow of the greenhouse. This contributes to controlling both the temperature and humidity of the air
- Light Bulbs -  We are using light bulbs to control the temperature when the temperature falls below 15 degrees Celsius
- GSM - The users are warned through GSM when the pH and moisture content of the soil is not optimum. The users need to take action accordingly to adjust these two parameters
- LCD - This is used to show all the readings that are being taken from the sensors


### Presentation & Report Files: 
[Final Presentation.pptx](https://github.com/MustofAhmed41/smart-agricultural-system/files/7515413/Final.Presentation.pptx)

[Final Report.pdf](https://github.com/MustofAhmed41/smart-agricultural-system/files/7515414/Final.Report.pdf)


