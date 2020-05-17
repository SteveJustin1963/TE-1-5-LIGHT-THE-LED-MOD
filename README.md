# TE-1-LIGHT-THE-LED-MOD

After a couple of requests for help with LIGHT THE LED, we found the de-bounce circuit comprising the two electrolytics at the input of CD 4017, was not good enough. Some brands of IC's were more sensitive and had a tendency to clock two or even three outputs on a single pulse of the switch. No matter how we altered the 2-capacitor de-bounce network, it was not satisfactory. So we designed a different arrangement. This time we employed a transistor to change the state of the input gate from HIGH to LOW. As the 4.7mfd cap charges, the base voltage rises, turning on and saturating the transistor. The voltage at the collector changes from rail voltage to about one volt. This clocks the IC. This circuit works with any CD 4017 and enables the led to light correctly every time. All the parts can be mounted on the PC board without cutting any copper tracks.  

![](https://github.com/SteveJustin1963/TE-1-5-LIGHT-THE-LED-MOD/blob/master/CCT.png)

https://easyeda.com/editor#id=1489d2a1d726442892ff16bf925481ef

![](https://github.com/SteveJustin1963/TE-1-5-LIGHT-THE-LED-MOD/blob/master/LAY.png)

## Parts List:
* 2 - 22k 1/4 w  
* 2 - 2k2 
* 1 - 1k 
* 1 - BC 547
* 1 - 4.7uF 10v
* 6 - 1N 4148
* 1 - Red 5mm LED
* 1 - CD 4017 IC
* 1 - Battery clip
* 1 - Springy brass strip 
