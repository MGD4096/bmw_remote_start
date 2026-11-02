
## KeyFob Wiring

**KeyFob Power**

You have to interrupt the battery positive connection, split it in 2 wires and feed them inside the relay:

![KEY_POWER wiring](images/wiring_2.jpg)


**KeyFob Lock and Unlock buttons**

You have to simulate the press of the switch using the relay. To do that, just hook to the key switches like that:

![KEY_LOCK/UNLOCK wiring](images/wiring_3.jpg)

## KCAN2

Attention: the OBD2 port doesn't have KCAN2. You can't use it. You have to take KCAN2 from the FEM

KCAN2_H: FEM A173\*8B, pin 50
KCAN2_L: FEM A173\*8B, pin 49

## 12V and GND

Attention: you can't use the 12V plug as power source, you need an always-powered 12V source. You can find it at the FEM.

12V: FEM A173\*3B, pin 33

GND: FEM A173\*3B, pin 6


## Start button

Start_1+: FEM A173\*7B, pin 45

Start_1-: FEM A173\*7B, pin 46

Start_2+: FEM A173\*7B, pin 49

Start_2-: FEM A173\*7B, pin 50

Or you can use start-stop button wiring is right behind the switch button, just pull it out.

## Brake light switch

BrakeLightSwitch+: FEM A173\*3B, pin 22

BrakeLightSwitch-: FEM A173\*3B, pin 6 its GND

Or you can use break light switch wiring is above the brake pedal.

## Some wiring diagrams
![CAR Wiring](images/wiring_1.png)