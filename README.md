![ESP32Peacock_PLUS_Logo](https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ESP32Peacock_Plus.png?raw=true)

# Esp32Peacock_PLUS
# non computer Python coding system
Project ESP32Peacock_PLUS is extended version of the development kit for Micropython on ESP32. It allows for users to write code through the webserver on the ESP board.

It is a binary one time upload type that allows for writing MicroPython code through the web without using USB connections. In addition, the display for terminal print and error code can be shown on the web as well.

The whole operation relies on javascript interval web load for running code. While running code in the loop section, in intervals, the program will check for return values of the print terminal or different error messages.

# Limits
- Limit of each code length (setup/loop/web1/web2) is 2000 characters  
- After pressing Factory Reset button, reloading the page is required
- Limit of displaying 1 chart
- chart_value is a constant name of chart value
- item is a constant name description value of chart
- Pin ON/OFF button are instant JavaScript functions on_click="pin(pin_number,state 0/1)"
- Html on web1 web2 tab are materialized by Css with 12 columns

# ip 
- SSID name is locked to ESP32Peacock 192.168.4.1:8081 to setup Wi-Fi Setup
- Switch AP mode to off and set your home SSID name and password then click on Save and Reset
- Before saving you can click on OPEN IP SCAN CODE to use Scan Page search ip (or see on OLED) 
- Use ip with :8081 to reach Peacock
- Beware do not press ip_Scan button on Scan Page before saving on Wi-Fi Setup page
- Suggested ip is 192.168.1.1 but if your home wifi base is on another ip then put that ip in the text box
- Scan code will only scan on 192.168.1.(1-254) if text box set to 192.168.1.1

# Usage
<a href='https://materializecss.com/'><img src='https://camo.githubusercontent.com/226e0b50bb6083d78ceffd4d03be2ad4d49757b7/68747470733a2f2f6a6f6e617468616e6b61626c616e2e6769746875622e696f2f696d616765732f6d6174657269616c697a652e706e67' width='100px'></a>
<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Blank_button.svg/1200px-Blank_button.svg.png' width='50px'>
<a href='https://bernii.github.io/gauge.js/'><img src='http://webdesignledger.com/wp-content/uploads/2015/06/40-gauge-coffee-javascript-open-source.jpg' width='100px'></a>
<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Blank_button.svg/1200px-Blank_button.svg.png' width='50px'>
<a href='https://www.espressif.com/en/support/download/other-tools'><img src='http://domoticx.com/wp-content/uploads/2016/01/esp-flash-download-tool-v1.2-screen.png' width='100px'></a>

# License
<a href="https://creativecommons.org/licenses/by-nc/3.0/th/deed.en"><img src="https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/cc_sign.jpg?raw=true" width="200px"></a>

<a href="https://creativecommons.org/licenses/by-nc/3.0/th/deed.en">Creative Common by Non Commercial nd,sa</a>

Copyright (c) 2020 Bunnavit Sawangpiriyakij

brunswick.99999@gmail.com

# ScreenShots
<img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-33-31-98.jpg?raw=true' width='200px'><img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-34-29-01.jpg?raw=true' width='200px'><img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-36-18-93.jpg?raw=true' width='200px'><img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-36-24-07.jpg?raw=true' width='200px'>

# How to Install
Click <a href='https://www.espressif.com/en/support/download/other-tools'>https://www.espressif.com/en/support/download/other-tools</a> to download ESpressIF Flash Download Tool

Download bin on this Git and Flash to ESP32 address 0x0000

* There are 2 types of binary in this Git 1 for non OLED ESP32 and 1 for OLED ESP32 (TTGO T) 
