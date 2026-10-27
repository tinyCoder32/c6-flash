# C6 Screen Designer — installer

Firmware for the Waveshare **ESP32-C6-LCD-1.47** (1.47" 172x320 panel), ready to
flash from the browser.

**→ [Install it](https://tinycoder32.github.io/c6-flash/)** — Chrome or Edge on a
desktop, plug the board in, press the button.

The board joins your Wi-Fi and serves its own screen designer, where you lay out
text, icons, images, emoji, animated eyes and live widgets — weather, headlines,
GitHub profiles, share prices, currency rates, prayer times, charts — and the
panel keeps drawing them with no computer attached.

After flashing, the panel shows a **C6-Setup** hotspot. Join it from a phone, pick
your network, and the board reboots and shows its address.

| | |
| --- | --- |
| `c6-screen-designer.bin` | the whole image: bootloader, partitions and app, flashed at offset 0 |
| `index.html` | the installer page, using [ESP Web Tools](https://esphome.github.io/esp-web-tools/) |
| `manifest.json` | tells the flasher which chip and which file |

Nothing here is personal — Wi-Fi credentials and API keys are typed into the
board and kept in its own storage, so this image suits anybody.
