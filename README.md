# terrarium_sensor

This project will serve as a blueprint for a small terrarium environmental/controller hub.

It consists of one ESP32 (we're using https://docs.espressif.com/projects/esp-idf/en/latest/esp32s2/hw-reference/esp32s2/user-guide-devkitm-1-v1.html, flashed with Tasmota https://tasmota.github.io/docs/) as the brain and you can connect up to: <br>


- 5 DS18B20 temperature sensors (e.g. https://www.adafruit.com/product/381) <br>
- 2 SHT3x/4x temperature/humidity sensors (e.g. https://www.adafruit.com/product/4099) <br>
- 1 GUVA-S12D UV light sensor (https://www.adafruit.com/product/1918) <br>
- 1 OLED screen (e.g. https://thepihut.com/products/0-91-oled-display-module?variant=32475516141630)


We're planning to also release a GERBER file for custom PCBs.

In the future we're hoping to implement it smoothly with TerrariumPI (https://github.com/theyosh/TerrariumPI/issues/733).


-------
## To-Do
- [x] Conceptual design in fritzing 
- [x] Order parts
- [x] Flash esp32 with Tasmota
- [x] Assemble prototype in breadboard 
- [ ] Get Oled working 
- [ ] Get second i2c SHT working
- [ ] Get enclosure built for GUVA ( I was nattering with a hardware nerd friend yesterday about this and a nice USB cable with the ends snipped off + heat wrap and a dab of silicone should do it  )
- [ ] Get PCB designed 
- [ ] Print PCB's 
- [ ] Design Enclosure in CAD 
- [ ] Get it 3d printed 
- [ ] Put all the lego together 
- [ ] Write Documentation 