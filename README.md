# <code>DonkeyCopilot</code>
[日本語 Japanese(Google Translate)](https://github-com.translate.goog/covao/DonkeyCopilot/blob/main/README.md?_x_tr_sl=en&_x_tr_tl=ja&_x_tr_hl=ja&_x_tr_pto=wapp)

"DonkeyCopilot" is controller application for DonkeyCar. 
- Browser based UI suitable for smartphones
- Easy to switch between manual and automatic driving.
- Can be operated using a gamepad.(e.g. Bluetooth gamepad)
- Easy to install with no code modifications.

# Installation
## Copy by manually
Copy two files into following project folder.  
~/donkeycar/donkeycar/parts/web_controller/templates/static
- [copilot.html](https://github.com/covao/DonkeyCopilot/blob/main/copilot.html)
- [p5.min.js](https://github.com/covao/DonkeyCopilot/blob/main/p5.min.js)

## Copy by command from raspberry pi terminal
```
cd ~/donkeycar/donkeycar/parts/web_controller/templates/static
wget "https://raw.githubusercontent.com/covao/DonkeyCopilot/main/copilot.html"  -O "copilot.html"
wget "https://raw.githubusercontent.com/covao/DonkeyCopilot/main/p5.min.js"  -O "p5.min.js"

```


# Usage
1. Start DonkeyCar.
https://docs.donkeycar.com/guide/get_driving/

2. Enter following URL from browser.  
<your car's hostname>:8887/static/copilot.html

# Referrence
- [p5.js library](https://p5js.org/download/)
