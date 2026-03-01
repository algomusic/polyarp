# PolyArp
DIY polyphonic synthesizer and sequencer

The PolyArp is a simple four-voice polyphonic synthesizer using subtractive synthesis. It includes an arpeggiator with extended features. It is a handmade synth using digital fabrication for hardware and software built on the M16 audio library.

# Firmware Update
Prerequisites
• Computer with Chromium web browser and internet access
• PolyArp device and USB cable
• Firmware file: PolyArp_Code.ino.bin

Steps
1. Open a Chromium browser on your computer and visit the ESPConnect site: https://thelastoutpostworkshop.github.io/microcontroller_devkit/espconnect/
2. Connect the PolyArp to the computer via USB. USB C -> C seems to work best.
3. In ESPConnect tick the ‘Connect’ button and select the port for the PolyArp and click ‘connect’ in the popup dialog. ESPConnect should display info about the ESP32 chip.
4. On the left of the ESPConnect site, click ‘Flash Tools’. Scroll down to the ‘Flash Firmware’ section of the page.
5. Drag the PolyArp_Code.ino.bin from your computer onto the Firmware Binary area of the site.
6. From the ‘Recommended OXsets’ menu select ‘app0 - 0X10000’
7. Click the ‘Flash Firmware’ button, confirm if required, then wait for the firmware to be uploaded.
8. The PolyArp should restart.
9. Close the Browser.
