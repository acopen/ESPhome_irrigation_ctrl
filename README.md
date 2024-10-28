# ESPhome_irrigation_ctrl
ESPhome irrigation controler for 9v impulse valve

There are situations where standard irrigation valves (like zigbee Giex valves) have insuficient water flow to operate some sprinklers.
For these cases, you can use large valves (1") but there are 2 types of valves in the market:
  - 24v AC controled valves. Open when 24v/AC is aplied to coil
  - 9v pulse controled valves. Open by aplying a short pulse of 9v to the valve and closes by aplying reversed polarity pulse.
For a battery operated controler for this valve, the pulse valve is the right choice.

This controler uses:
  - ESP32_devkit_V4 as procesor (ESP32U vith connector for external antena)
      https://www.aliexpress.com/item/4000471022528.html
  - Wifi external antena with cable:
      https://www.aliexpress.com/item/1005003062675298.html
  - ESPhome as firmware
      https://esphome.io/index.html
  - 9v 1" impulse valve
      https://www.leroymerlin.es/productos/jardin-y-terraza/riego/electrovalvulas/electrovalvula-para-riego-9v-rosca-hembra-1-jardibric-19453462.html
  - Water Flow Sensor 3/4" male-male YF-B5
      https://www.aliexpress.com/item/1005007078140299.html
  - A dual 18650 battery, 5V UPS module
      https://www.aliexpress.com/item/1005005788389538.html
  - An adjustable boost module for 5v to 9v 2A
      https://www.aliexpress.com/item/1005006365958087.html
  - A DRV8833 module as dual mosfet H bridge
      https://www.aliexpress.com/item/1005006282457232.html
  - A ADS1155 4 chanels A/D I2C module to monitor battery
      https://www.aliexpress.com/item/1005005343202454.html
  - A 5v solar panel to charge batteries
      https://www.aliexpress.com/item/1005005758954904.html

