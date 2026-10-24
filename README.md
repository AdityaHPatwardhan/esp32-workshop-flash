# ESP32 workshop: flash files

Prebuilt binaries for the ESP32-S3 workshop at PICT, flashed from the browser with
[ESP Launchpad](https://espressif.github.io/esp-launchpad/). Use Chrome or Edge.

**Flash (any workshop board: ESP32-CAM or ESP32-S3-CAM, chip is detected):**
https://espressif.github.io/esp-launchpad/?flashConfigURL=https://adityahpatwardhan.github.io/esp32-workshop-flash/workshop.toml

ESP32-S3-CAM only:
https://espressif.github.io/esp-launchpad/?flashConfigURL=https://adityahpatwardhan.github.io/esp32-workshop-flash/s3cam.toml

ESP32-S3-EYE: https://espressif.github.io/esp-launchpad/?flashConfigURL=https://adityahpatwardhan.github.io/esp32-workshop-flash/s3eye.toml

Hello Board with a console command box:
https://espressif.github.io/esp-launchpad/minimal-launchpad/?flashConfigURL=https://adityahpatwardhan.github.io/esp32-workshop-flash/hello-board.toml

Person Detector with a console command box:
https://espressif.github.io/esp-launchpad/minimal-launchpad/?flashConfigURL=https://adityahpatwardhan.github.io/esp32-workshop-flash/person-detector.toml

`esp32_RainMaker_switch.bin` / `esp32s3_RainMaker_switch.bin` are Espressif's ESP RainMaker switch example, copied from
https://espressif.github.io/esp-rainmaker/launchpad.toml.

**ESP32-CAM (AI-Thinker) has no USB port.** Plug it into an ESP32-CAM-MB, or wire a USB-UART
(TX-RX crossed, GND, 5V). Without auto-reset: connect IO0 to GND, press RESET, flash, then
remove the IO0 wire and press RESET again.
