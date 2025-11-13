# Carbon-Dioxide-Sensor
**The CO₂ Sensor** uses advanced Photoacoustic Sensing Technology to directly measure carbon dioxide concentration. Unlike some sensors that estimate CO₂ levels indirectly via VOC readings, this sensor provides precise and reliable measurements.

CO₂ is a key indicator of indoor air quality. High CO₂ levels can impair human cognitive function, reduce focus and alertness, and may lead to long-term health risks.

## **This sensor is suitable for:**
- Indoor air quality monitoring
- Smart ventilation systems
- Environmental science projects and education
- Development of IoT devices focused on health and the environment

## **Specifications**
|Parameter|Value|
|-|-|
|**Model**|SCD41|
|**Measurement Range (CO₂)**| 400 – 5000 ppm|
|**Operating Temperature**|–10 °C to +60 °C|
|**Operating Humidity**|0–100 % RH|
|**Accuracy**|±40 ppm + 5%|
|**Supply Voltage**|2.4 – 5.5 VDC|
|**Interface**|Digital I²C (address 0x62)|


![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/Example%20code.png?raw=true){{{width="250" height="auto"}}} 
[**Download the working code here**](https://code.gogoboard.org/#/program/653028f0-be50-48a5-a414-d75a3b65f184)

## Block Code Reference
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%204.png?raw=true){{{width="230" height="auto"}}}| Use this block to read the carbon dioxide (CO₂) level from the sensor in parts per million (ppm).|
|-|-|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%205.png?raw=true){{{width="200" height="auto"}}}|**Use this block to read the dew point from the sensor in degrees Celsius (°C).**|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%206.png?raw=true){{{width="160" height="auto"}}}|**Use this block to read the eCO₂ (equivalent CO₂) value from the sensor in parts per million (ppm).**|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%207.png?raw=true){{{width="200" height="auto"}}}|**Use this block to read the temperature from the sensor in degrees Celsius (°C).**|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%208.png?raw=true){{{width="190" height="auto"}}}|**Use this block to read the humidity from the sensor in percent (%).**|

## **Required Equipment**
|CO₂ Sensor with built-in Grove connector|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/co2%20sensor.png?raw=true){{{width="200" height="auto"}}}|
|-|-|
|**Grove cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/only%20grove%20(test).png?raw=true){{{width="200" height="auto"}}}|
|**Computer or Tablet**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/computer%20or%20tablet.png?raw=true){{{width="200" height="auto"}}}|
|**GoGo Board and USB-C cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/gogoboard%20and%20usb.png?raw=true){{{width="200" height="auto"}}}|

## **How to use**
**1. Connect the GoGo Board**
- Connect the GoGo Board to your computer or tablet via USB-C cable or Wi-Fi
![](https://github.com/thegogoboard/gogodoc/blob/main/Automation/Image%20(91).jpg?raw=true){{{width="500" height="auto"}}}

**2. Connect the  Sensor**
There are two ways to connect the CO₂ sensor:
**Option 1:** Using a Grove Connector
- Connect the CO₂ Sensor to a Grove cable, then plug the cable into the purple Multi Port on the GoGo Board.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon.gif?raw=true){{{width="500" height="auto"}}}

**Option 2:** Using Jumper Wires (Dupont Wires)
- If you don’t have a Grove connector, you can use jumper wires to connect the sensor directly to the pins on the GoGo Board.
![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/co2%20with%20adapter.png?raw=true){{{width="500" height="auto"}}} ![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/co2%20with%20board.png?raw=true){{{width="500" height="auto"}}} 

## Getting Started with the CO₂ Sensor on GoGo Code 

**1. Visit the GoGo Code website:**
- Go to [GoGo Code](https://code.gogoboard.org/#/program) to start programming and controlling your device.

**2. Add the CO₂ Sensor extension:**
- Click on the **Add Extension** category
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%201.gif?raw=true){{{width="1000" height="auto"}}}

- Select **Official**, then click the **[ Multi ] - Carbon Dioxide Sensor** card. The system will automatically return to the main page.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%202.gif?raw=true){{{width="1000" height="auto"}}}ฃ

**3. Add sensor command blocks:**
- Click on the **[ Multi ] - Carbon Dioxide Sensor** category. You will see five available blocks:
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%203.gif?raw=true){{{width="1000" height="auto"}}}

**4. Write a simple program to display sensor data:**
- Use the **“show number”** block from the **Built-in Display** category to display the value on the GoGo Board screen.
- Insert the **"Carbon dioxide of CO₂ Sensor (ppm)"** block into the show number block
- To display the value continuously, place everything inside the **“forever do each time wait…”** block from the **Loops** category. You can also set how often the value should be updated (e.g., every 1 second).

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%209.png?raw=true){{{width="500" height="auto"}}}

**5. Download and test your code:**
- Click **Download**, then click **Run Code** to start running your program.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/CO2/Carbon%20code%2010.gif?raw=true){{{width="1000" height="auto"}}}

::: details Additional information
  **Buy online:** [CO₂ Sensor](https://th.shp.ee/j57aQyi)
  
  **Cautions**
- Avoid modifying wires or connecting them incorrectly, as this may damage the device.
- Do not touch the sensor head while it is operating, as it may affect detection accuracy.
- If the sensor does not work, check the voltage and wiring connections.
:::
