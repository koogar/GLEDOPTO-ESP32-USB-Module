# GLEDOPTO GL-C-0115WL WLED GPIO Infrared (IR) Remote Mod

![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/Infrared%20Mod/IR_Mod/images/TML_GLEDOPTO_GPIO_IR_MOD%20(4).jpg)


## GLEDOPTO GL-C-0115WL Module Pinout
![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/images/TML_GLEDOPTO%20GL-C-0115WL-D%20Pinout-03%20(Medium).jpg)


## Extending the unused GPIO Pins (04, 18, 19)
![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/Infrared%20Mod/IR_Mod/images/TML_GLEDOPTO_GPIO_IR_MOD%20(1).jpg)

## Cut a slot in the casing
![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/Infrared%20Mod/IR_Mod/images/TML_GLEDOPTO_GPIO_IR_MOD%20(2).jpg)


## Ready for action
![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/Infrared%20Mod/IR_Mod/images/TML_GLEDOPTO_GPIO_IR_MOD%20(6).jpg)

## Only one GPIO pin is required for Infrared leaving 2 spare
![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/Infrared%20Mod/IR_Mod/images/TML_GLEDOPTO_GPIO_IR_MOD%20(8).jpg)

## WLED Recommended Infrared Receiver (TSOP3820 based)

![](https://github.com/koogar/GLEDOPTO-ESP32-USB-Module/blob/main/Infrared%20Mod/IR_Mod/images/KY-022.png)


## WLED_Apple-v1-A1156_IR.json example
```
{
  "desc": "Apple V1 Remote Presets",
  "0x77E1A06D": {
    "label": "play",
    "cmnt": "Play/Pause",
    "cmd": { "ps": "1~9~r" }
  },
  "0x77E1C06D": {
    "label": "menu",
    "cmnt": "On/Off",
    "cmd": { "on": "t" }    
  },
  "0x77E1306D": {
    "label": "down",
    "cmnt": "Brightness -",
    "cmd": { "bri": "~-8" }
  },
  "0x77E1506D": {
    "label": "up",
    "cmnt": "Brightness +",
    "cmd": { "bri": "~+8" }
  },
  "0x77E1906D": {
    "label": "left",
    "cmnt": "Effect -",
    "cmd": { "seg": { "fx": "~-" } }
  },
  "0x77E1606D": {
    "label": "right",
    "cmnt": "Effect +",
    "cmd": { "seg": { "fx": "~+" } }
  }

}

```








