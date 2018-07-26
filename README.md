# LoRA ToF sensor
This is an example for using MKR WAN 1300 with the ToF sensor VL53L0X and sending the values through LoRa to TTN.

## Links
### [MKR WAN 1300](https://store.arduino.cc/mkr-wan-1300)
### [VL53L0X](https://www.st.com/en/evaluation-tools/53l0-satel-i1.html)

## Wiring
| MKR WAN 1300 | VL53L0X |
|----------------|-------|
| VCC | VDD   (5) |
| GND | GND   (6) |
| SDA | SDA_I (4) |
| SCL | SCL_I (2) |

### ![VL53L0X pinout](https://cei-lab.github.io/ece3400/tutorials/sensors/images/Pinout.svg)
https://cei-lab.github.io/ece3400/tutorials/sensors/images/Pinout.svg

## Variables
##### appEui      - this is where you paste your APP EUI 
##### appKey      - this is where you paste your APP KEY
##### delay_value - this is on default 30 second, but you can change it to have it send more frequently

---

### License

All our projects are as usefully open-source as possible.

Hardware including documentation is licensed under [CERN OHL v.1.2. license](http://www.ohwr.org/licenses/cern-ohl/v1.2)

Firmware and software originating from the project is licensed under [GNU GENERAL PUBLIC LICENSE v3](http://www.gnu.org/licenses/gpl-3.0.en.html).

Open data generated by our projects is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

All our websites and additional documentation are licensed under [Creative Commons Attribution-ShareAlike 4 .0 Unported License] (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

What this means is that you can use hardware, firmware, software and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

Koruza, GoodEnoughCNC and IRNAS are all names and marks of Institut IRNAS Rače. 
You may use these names and terms only to attribute the appropriate entity as required by the Open Licences referred to above. You may not use them in any other way and in particular you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.
