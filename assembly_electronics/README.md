# Assembly
The processes of soldering and attaching LEDs to diffusers can be done in either order. Due to limited quantities of hot glue guns, half of the workshop participants should start with each assembly step, then swap when finished.

## Electronics Soldering

### Electronic Components
- [LilyGo T-OI Plus ESP32 C3 Controller](https://lilygo.cc/en-us/products/t-oi-plus)<br>
<img src="images/toi.png" width="240">
- IMNP441 Microphone<br>
<img src="images/mic.png" width="150">
- Screw Terminal Connector<br>
<img src="images/screw_term.png" width="100">
- WLED Breakout board <br>
<img src="images/breakout.png" width="240">

### Steps
Differing component heights make it easiest to solder the components in the order below.<br>
- Solder headers to microphone as shown in images below. Be careful to solder the headers to the correct side. **The header legs sit on the same side of the microphone PCB as the microphone components:**<br>
<img src="images/mic_headers1.png" height=100>&nbsp;&nbsp;<img src="images/mic_headers2.png" height=100><br><br>
- Solder the microphone to the top of the breakout (the side with components). **Be sure to match the corresponding pins on the breakout and microphone**<br>
<img src="images/mic_breakout1.png" height=150>&nbsp;&nbsp;<img src="images/mic_breakout2.png" height=150><br><br>
- Solder the screw terminal to the breakout ***with the terminal openings facing the edge of the PCB***<br>
<img src="images/screw_term2.png" height=150>&nbsp;&nbsp;<img src="images/screw_terminal_down.png" height=150><br><br>
- Solder header pins to the T-OI controller with **pin legs on the same sides as the components as shown**:<br>
<img src="images/toi_headers1.png" height=150>&nbsp;&nbsp;<img src="images/toi_headers2.png" height=150><br><br>
- Solder T-OI controller to same side of breakout as microphone and screw terminal<br>
<img src="images/toi_breakout1.png" height=150>&nbsp;&nbsp;<img src="images/toi_breakout2.png" height=150>&nbsp;&nbsp;<br>
<img src="images/toi_breakout3.png" height=150>&nbsp;&nbsp;<img src="images/toi_breakout5.png" height=150><br>

<br><br>
