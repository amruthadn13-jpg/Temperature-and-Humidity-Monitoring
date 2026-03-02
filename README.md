# Temperature-and-Humidity-Monitoring

**🌡️ ESP32 Temperature & Humidity Monitor with OLED Display (DHT22)**

This project uses an ESP32, DHT22 sensor, and OLED display (SSD1306) to measure temperature and humidity and display the values on a small OLED screen.

The project is created and tested using Wokwi simulator.

**📌 Project Features**

Reads temperature and humidity using DHT22 sensor

Displays the values on a 0.96 inch OLED (128×64) display

Uses I2C communication for OLED

Prints sensor values in the Serial Monitor

**🧰 Components Used**

ESP32 Development Board

DHT22 Temperature & Humidity Sensor

SSD1306 OLED Display (128×64, I2C)

Connecting wires

**🔌 Pin Connections**
✅ DHT22 Sensor
DHT22 Pin	ESP32 Pin
VCC	3.3V
GND	GND
DATA	GPIO 12
✅ OLED Display (I2C)
OLED Pin	ESP32 Pin
VCC	3.3V
GND	GND
SDA	GPIO 21
SCL	GPIO 22

**⚙️ Libraries Required**

Install the following libraries:

Adafruit GFX Library

Adafruit SSD1306

DHT sensor library

**🧠 Working Principle**

The DHT22 sensor measures temperature and humidity.

ESP32 reads the data using the DHT library.

The measured values are sent to:

OLED display

Serial Monitor

OLED shows:

Temperature in °C

Humidity in %

**🧪 Output Example**
Temp: 24.00 C | Humidity: 40.00 %

**▶️ How to Run**

Open the project in Wokwi or Arduino IDE.

Install all required libraries.

Connect the components as shown in the wiring section.

Upload the code to ESP32.

Open Serial Monitor (baud rate: 9600).

Observe temperature and humidity on the OLED display.

**🛠️ Configuration Used**

OLED Resolution: 128 × 64

OLED I2C Address: 0x3C

DHT Sensor Type: DHT22

Serial baud rate: 9600

**👩‍💻 Author**

Amrutha D N

**📷 Simulation**

This project is simulated and verified using Wokwi with ESP32, DHT22 and SSD1306 OLED display
