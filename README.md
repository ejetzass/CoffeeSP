# CoffeeSP ("cof-ESP")
Espresso brew script for ESPHome and ESP32, using SSR relays for pump, 3-way solenoid valve and boiler PID control, xs5871 TSIC integration and SH1106 128x64 (ssd1306_i2c) display. I use the CleverCoffee v1.6 PCB (https://clevercoffee.de/) to connect my relays, temperature sensor, buttons and display. 

# About
This is my personal ESPHome code for my 17+ year old (rusty) Rancilio Silvia V2. I used the AuberIns PID for years, but I wanted more control over the brewing process. After trying CleverCoffee's PCB with their firmware (https://github.com/rancilio-pid/clevercoffee) I was not satisfied with the complex coding and the VSCode and platformio platform. Since I use Home Assistant (https://www.home-assistant.io/) I was aware of the ESPHome platform and it's wide range of possibilities, and CoffeeSP was born. 

# Features
- Control of brew and steam temperatures using a PID
- Pressurized pre-infusion brew
- Straight brew (without any pre-infusion)
- Soft brew with only the 3-way valve open (without pump pressure)
- Backflush automization
- Customizable times and pauses for all brew variants
- SH1106 display with current settings and status information
- ESPHome webserver for full control via webpage
- Home Assistant integration (with ESPHome)
- Auto-sleep timer when on for a predetermined time
- Overrides for pump and/or 3-way valve

# Support
This is a personal project that I use for my machine. Code is provided "as-is". Adapt the code for your own personal needs. No support is given, nor advice. It's your equipment so using this script is your responsibility. 
