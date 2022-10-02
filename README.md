# <code>Donkey Copilot</code>
[日本語 Japanese(Google Translate)](https://github-com.translate.goog/covao/DonkeyCopilot/blob/main/README.md?_x_tr_sl=en&_x_tr_tl=ja&_x_tr_hl=ja&_x_tr_pto=wapp)

"Donkey Copilot" is WEB controller application for DonkeyCar. 
- Browser based UI suitable for smartphone or tablet
- Easy to switch between manual and automatic driving.
- Can be operated using a gamepad. (HTML5 GamePad API)
- Easy to install with no code modifications.

# Installation
## Method 1: Copy files by manually
Copy two files into the following project.  
~/projects/donkeycar/donkeycar/parts/web_controller/templates/static
- [copilot.html](https://github.com/covao/DonkeyCopilot/blob/main/copilot.html)
- [p5.min.js](https://github.com/covao/DonkeyCopilot/blob/main/p5.min.js)

## Method 2: Command from raspberry pi terminal
```
cd ~/projects/donkeycar/donkeycar/parts/web_controller/templates/static
wget "https://raw.githubusercontent.com/covao/DonkeyCopilot/main/copilot.html"  -O "copilot.html"
wget "https://raw.githubusercontent.com/covao/DonkeyCopilot/main/p5.min.js"  -O "p5.min.js"

```


# Usage
1. Start DonkeyCar. 
参考 https://docs.donkeycar.com/guide/get_driving/

2. Enter following URL from browser.  
<your car's hostname>:8887/static/copilot.html

# Referrence 
- [p5.js library](https://p5js.org/download/)
