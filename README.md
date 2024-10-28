# ESPhome_irrigation_ctrl
ESPhome irrigation controller for 9v impulse valve

There are situations where standard irrigation valves (like zigbee Giex valves) have insufficient water flow to operate some sprinklers.
For these cases, you can use large valves (1") but there are 2 types of valves in the market:
  - 24v AC controlled valves. Open when 24v/AC is applied to coil
  - 9v pulse controlled valves. Open by applying a short pulse of 9v to the valve, and closes by applying a reversed polarity pulse.
For a battery operated controller for this valve, the pulse valve is the right choice.

This controller uses:
  - ESP32_devkit_V4 as processor (ESP32U with connector for external antenna)
      https://www.aliexpress.com/item/4000471022528.html
  - WI-FI external antenna with cable:
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
  - A ADS1155 4 channels A/D I2C module to monitor battery
      https://www.aliexpress.com/item/1005005343202454.html
  - A 5v solar panel to charge batteries
      https://www.aliexpress.com/item/1005005758954904.html

