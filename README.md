![ESP32Peacock_PLUS_Logo](https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ESP32Peacock_Plus.png?raw=true)

# Esp32Peacock_PLUS
Project ESP32Peacock_PLUS is extend version development kit for Micropython on ESP32. It allows for users to write code through the webserver on the ESP board.

It is a binary one time upload type that allows for writing MicroPython code through the web without using USB connections. In addition, the display for terminal print and error code can be shown on the web as well.

The whole operation relies on javascript interval web load for running code. While running code in the loop section, in intervals, the program will check for return values of the print terminal or different error messages.

# Limits
- Limit of each code length (setup/loop/web1/web2) is 2000 characters  
- After press Factory Reset button you need to reload page
- There is only 1 chart allow in this kit
- chart_value is constant name of chart value
- item is constant name of description value of chart
- Pin ON/OFF button are instant function on_click="pin(pin_number,state 0/1)"

# Usage
<a href='https://materializecss.com/'><img src='https://camo.githubusercontent.com/226e0b50bb6083d78ceffd4d03be2ad4d49757b7/68747470733a2f2f6a6f6e617468616e6b61626c616e2e6769746875622e696f2f696d616765732f6d6174657269616c697a652e706e67' width='100px'></a>
<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Blank_button.svg/1200px-Blank_button.svg.png' width='50px'>
<a href='https://bernii.github.io/gauge.js/'><img src='http://webdesignledger.com/wp-content/uploads/2015/06/40-gauge-coffee-javascript-open-source.jpg' width='100px'></a>
<a href='https://www.espressif.com/en/support/download/other-tools'><img src='http://domoticx.com/wp-content/uploads/2016/01/esp-flash-download-tool-v1.2-screen.png' width='100px'></a>

# License
<a href="https://creativecommons.org/licenses/by-nc/3.0/th/deed.en"><img src="https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/cc_sign.jpg?raw=true" width="200px"></a>

<a href="https://creativecommons.org/licenses/by-nc/3.0/th/deed.en">Creative Common by Non Commercial nd,sa</a>

Copyright (c) 2020 Bunnavit Sawangpiriyakij

brunswick99999@gmail.com

# ScreenShots
<img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-33-31-98.jpg?raw=true' width='200px'><img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-34-29-01.jpg?raw=true' width='200px'><img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-36-18-93.jpg?raw=true' width='200px'><img src='https://github.com/esp32peacock/Esp32Peacock_PLUS/blob/master/ScreenShots/Screenshot_2019-12-20-23-36-24-07.jpg?raw=true' width='200px'>
