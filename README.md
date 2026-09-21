# Industrial-Encoder-Knob-Volume-Control
just a yaml code vibe coded via claude
Yt-Video:
https://youtu.be/-hrqFqxZjb8

3dModel:
https://makerworld.com/en/models/3339580-smart-volume-knob-industrial-encorder#profileId-3793769

Parts:


Pro-Range (E38S6G5-1000B-G24F) Rotary Incremental Encoder - 38mm,Photoelectric, AB 2 Channels, 1000 PPR
https://robu.in/product/pro-range-rotary-incremental-encoder-38mm-photoelectric-ab-2-channels-1000-ppr-e38s6g5-1000b-g24f/

ESP32-WROOM-32 38Pin
https://robu.in/product/esp32-38pin-development-board-wifibluetooth-ultra-low-power-consumption-dual-core/

5V Passive Buzzer
https://robu.in/product/pcb-mounted-passive-buzzer-module/

TTP223 Touch Key Module
https://robu.in/product/ttp223-touch-key-module-2pcs/

USB Type-C Connector Breakout (Female)
https://robocraze.com/products/usb-type-c-connector-breakout-female-7semi

16Bit WS2812B 5050 RGB LED Built-in Full Color
https://robu.in/product/16bit-ws2812b-5050-rgb-led-built-in-full-color-driving-lights-circular-development-board/

GoldenMorning 0.96 Inch I2C/IIC 4pin OLED Display Module BLUE
https://robu.in/product/0-96-inch-i2c-iic-oled-lcd-module-4pin-with-vcc-gnd-blue/

instructions:

just copy the yaml from the industrial-encoder-knob.yaml and paste it after your wifi and captive portal.


Wiring:


GPIO	Connects to
GPIO13	Rotary encoder — Pin A

GPIO14	Rotary encoder — Pin B

GPIO25	Buzzer — signal

GPIO16	Touch sensor — signal

GPIO21	OLED — SDA

GPIO4	OLED — SCL

GPIO27	WS2812 LED ring — data in

GND	Shared ground — encoder, buzzer, touch sensor, OLED, LED ring

3.3V	OLED — VCC, Touch sensor — VCC

5V	WS2812 LED ring — VCC
