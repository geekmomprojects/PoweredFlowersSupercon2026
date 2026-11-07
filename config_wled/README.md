* Flashing WLED

To save time, the LilyGo T-OI ESP32 controllers have been pre-flashed with WLED, but if you'd ever like to re-flash them, the information is below: 

The easiest way to flash WLED to an ESP is through the official online installer at (https://install.wled.me/)[https://install.wled.me/], but I sometimes have trouble correctly flashing an ESP32-C3 with it. I have more consistent success with this online installation site (https://wled-install.github.io/)[https://wled-install.github.io/]

You can also download and flash the binary from the second site yourself. We are using the standard version audio-reactive WLED firmware from the nightlhy build, esp32-C3 with 4MB RAM<br>
<img src="images/wled_version_select.png" width="240">

Pin Assignments:
- LEDs GP8
- Push Button GP9
- Microphone: 
  -- WS GP2
  -- SCK GP4
  -- SD GP5