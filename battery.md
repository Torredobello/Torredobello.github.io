---
layout: page
title: Wind System Assessment
bigimg:
  - "/img/big-img/battery.png"
  - "/img/big-img/tesla.webp"
---

The batteries are the most widely used devices for energy storage in different applications. The stochastic nature of available energy from the wind/PV system makes it necessary to select the right size of a battery bank so that the system will satisfy the load at any hour of a typical day. The battery sizing mainly depends on the number of days that the battery bank itself can supply the load without being recharged by supply resources which is called [autonomy days](https://www.riello-ups.com/questions/17-what-does-autonomy-mean#:~:text=The%20battery%20duration%20at%20a,Diesel%20Generator%20should%20be%20considered.). Another important factor in the battery sizing procedure is the battery *depth of discharge (DOD)*.

Temperature can also affect the performance of batteries (*𝑇𝑏𝑎𝑡*). High temperature decreases the battery lifetime. The batteries are normally installed inside a building where the temperature is not expected to change drastically. It is recommended to keep the battery at 25oC. In this temperature, the derate factor (*𝐷𝑓*) is one. The required battery band capacity can be calculated as Rios Rivera (2008): 
- *𝐶𝐵𝑅= 𝐿 ×(𝐴𝑢𝑡𝑜𝑛𝑜𝑚𝑦 𝐷𝑎𝑦𝑠)/𝐷𝑂𝐷𝑚𝑎𝑥 × 𝐷𝑓    (10)*
where *𝐶𝐵𝑅* is the required battery bank capacity (*Ah*), *𝐿* is the amp-hour consumed by the load in a day (*Ah/Day*). The total number of required batteries can be expressed as:
- *𝑁𝐵= 𝐶𝐵𝑅/𝐶𝐵    (11)*
where *𝐶𝐵* is the capacity of the selected battery (𝐴ℎ).

The battery bank, with total nominal capacity 𝐶𝑛(𝐴ℎ), is permitted to discharge up to a limit defined by the maximum permissible depth of discharge DOD (%), which is specified by the system designer at the beginning of the optimal sizing process which in this case is 50%, i.e.
- *𝐶𝑚𝑖𝑛=𝐷𝑂𝐷×𝐶𝑛    (12)*
where *𝐶𝑚𝑖𝑛* is the minimum permissible battery capacity during discharging (𝐴ℎ).
- *𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝐵𝑎𝑡𝑡𝑒𝑟𝑖𝑒𝑠>=𝑟𝑒𝑞𝑢𝑖𝑟𝑒 𝑠𝑡𝑜𝑟𝑎𝑔𝑒 𝑐𝑎𝑝𝑎𝑐𝑖𝑡𝑦/𝐷0𝐷×𝑟𝑎𝑡𝑒𝑑 𝑏𝑎𝑡𝑡𝑒𝑟𝑦 𝑐𝑎𝑝𝑎𝑐𝑖𝑡𝑦    (13)*
  
The energy production and its consumption depend on the number of batteries and the state of the battery connected at any given time. When the battery is charging, power generation exceeds the load demand. For off-grid energy systems, the energy balance between production and load is considered very important and a storage bank is key in this regard. Battery bank *state of charge (SOC)* at a time (t) can be obtained as:
- *𝐸𝐵𝑎𝑡𝑡(𝑡)=𝐸𝐵𝑎𝑡𝑡(𝑡−1)(1−𝜎)− [𝐸𝑟𝑒𝑝(𝑡)𝜂𝑖𝑛𝑣−𝐸𝑔𝑒𝑛(𝑡)]×𝜂𝑑_𝑏𝑎𝑡𝑡    (14)*
- *𝐸𝐵𝑎𝑡𝑡(𝑡)=𝐸𝐵𝑎𝑡𝑡(𝑡−1)(1−𝜎)+ [𝐸𝑔𝑒𝑛(𝑡)−𝐸𝑟𝑒𝑝(𝑡)𝜂𝑖𝑛𝑣]×𝜂𝐵𝑎𝑡𝑡    (15)*

*Eq. (15)* is for the discharging process and *Eq. (16)* shows the charging process. *𝐸𝐵𝑎𝑡𝑡(𝑡)*, *𝐸𝐵𝑎𝑡𝑡(𝑡−1)* are the storage bank energy at a time *(𝑡)* and *(𝑡−1)*; 𝜎 is the self-discharge rate; *𝐸𝑟𝑒𝑝(𝑡)* is the energy required at a time *(t)*; *𝐸𝑔𝑒𝑛(𝑡)* is the energy produced by system generators; *𝜂𝑖𝑛𝑣* is inverter efficiency *𝜂𝑑_𝑏𝑎𝑡𝑡* is battery discharging efficiency which is usually 100% and 𝜂𝑏𝑎𝑡𝑡 is battery charging efficiency.
