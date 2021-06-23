# Chicken Coop Door

### Change language to:

  * <a href='https://github.com/Qypol342/chicken-coop-door/blob/master/README.FR.md'> :fr:		<a/>


 
## Door Functionality
 * 🌅 close on sunset -> base on lux
 * ⏰ open at set time -> base on real time clock
 * 🚪 door layout -> the rope prevent the door of harming a chicken that is sitting in the way
 
 <img src="https://raw.githubusercontent.com/Qypol342/chicken-coop-door/master/coop_door_schema.png" alt="coop_door_schema" height="400">
 

## Needed Materials
 * <a href='https://fr.banggood.com/DC-3V-6V-DC-1-120-Gear-Motor-TT-Motor-for-Smart-Car-Robot-DIY-p-1260117.html?rmmds=detail-left-hotproducts&cur_warehouse=CN'>Motor (6v with gear reduction)<a/>
 * <a href='https://www.banggood.com/fr/Geekcreit-ATmega328P-Nano-V3-Module-Improved-Version-With-USB-Cable-Development-Board-Geekcreit-for-Arduino-products-that-work-with-official-Arduino-boards-p-933647.html?cur_warehouse=CN&rmmds=search'>Arduino Nano<a/>
 * <a href='https://www.banggood.com/fr/50PCS-5MM-GL5516-Light-Dependent-Resistor-Photoresistor-LDR-p-1464084.html?cur_warehouse=CN&rmmds=search'>Light Sensor (simple light resistor)</a>
 * <a href='https://www.banggood.com/fr/DS3231-AT24C32-IIC-Precision-RTC-Real-Time-Clock-Memory-Module-p-1547989.html?cur_warehouse=CN&rmmds=search'>Realy Time Clock (DS3231)</a>
 * <a href='https://www.banggood.com/fr/Wholesale-L298N-Dual-H-Bridge-Stepper-Motor-Driver-Board-p-42826.html?cur_warehouse=CN&rmmds=search'>H Bridge (L298N)</a>

 ### Total cost of 27 eur
## Wiring Diagram

 <img src="https://raw.githubusercontent.com/Qypol342/chicken-coop-door/master/wiring%20diagram.png" alt="wiring diagram" width="800">

 
## Code
  * You need to first set up your real time clock with this <a href='https://github.com/Qypol342/chicken-coop-door/blob/master/setclock.ino'>code</a>
  * Then can upload the coop door soft wear, accessible <a href='https://github.com/Qypol342/chicken-coop-door/blob/master/coop_door_code.ino'>here</a>
 

 
## Power Autonomie ( Solar Panel )
  I have set it up on Solar Panel on decembre 2020, and it has been running continuously since.
 
  I am using a 50w solar panel and an old car battery.
 
  <a href='https://www.banggood.com/fr/10-or-20-or-30A-12-or-24V-LCD-Dual-USB-Solar-Panel-Battery-Regulator-Charge-Controller-p-1766616.html?cur_warehouse=ES&ID=554059&rmmds=search'>Here</a> is the charge controller i am using, providing 12v and 5v.

 
 
## ⚠️ Disclaimer 
 
 The project was built with component i already had, it is possible to find better suited part for this project.
 
 Feel free to add pull request or to point out issue
 
 
 
 
 
 


