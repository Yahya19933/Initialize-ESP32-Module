# Initialize-ESP32-Module
Initialize ESP32 Module

## Installation
To use ESP32 device using Arduino IDE there are few steps before we can start upload code to ESP32.

1. Make sure you have [Arduino IDE](https://www.arduino.cc/en/software) installed
2. In Arduino IDE go to *File>Preferences>Settings* , **in Additional Boards Manager URLs**, past this URL
```
https://dl.espressif.com/dl/package_esp32_index.json
```

3. In your IDE go to *Tools>Board>Board Manager*, in the search field type ESP32, then install **esp32** by **Espressif Systems**

![1](https://user-images.githubusercontent.com/90250848/186612252-547375d7-800f-4de7-8081-d8f403058573.PNG)

4. In menu bar go to *Tools>Board*: you will see different ESP32 boards selct what is appropriate for your ESP32

![2](https://user-images.githubusercontent.com/90250848/186613546-68eb4b6d-dada-4513-bcdf-5b7de5d633eb.PNG)

5. Plug in the esp32 module to your computer then navigate to Tools>Port then select the ESP32 port

After installation of the ESP32. Need to test  ESP32 module, from installing the library to upload code to the ESP32 module, then can control the on board LED using the Serial Monitor window:

**Command**            **Result**

    off                turn off LED
    
    on                 turn on LED
    
delay 100          LED blink every 100ms
