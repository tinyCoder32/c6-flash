# ESP32 Screen Designer — installer

Firmware for small ESP32 panels, ready to flash from the browser.

**→ [Install it](https://tinycoder32.github.io/c6-flash/)** — Chrome or Edge on a
desktop, plug the board in, pick your board, press the button.

| Board | Panel | Also on board |
| --- | --- | --- |
| Waveshare **ESP32-C6-LCD-1.47** | 1.47" 172x320 | RGB LED, microSD |
| LilyGO **T-Display-S3** | 1.9" 170x320 | battery connector, second button |

Picking the wrong one is safe — the flasher checks the chip it is talking to and
refuses a mismatch.

The board joins your Wi-Fi and serves its own screen designer, where you lay out
text, icons, images, emoji, animated eyes and live widgets — weather, headlines,
GitHub profiles, share prices, currency rates, prayer times, charts — and the
panel keeps drawing them with no computer attached.

After flashing, the panel shows a **C6-Setup** hotspot. Join it from a phone, pick
your network, and the board reboots and shows its address.

| | |
| --- | --- |
| `c6-lcd-147.bin`, `tdisplay-s3.bin` | whole images: bootloader, partitions and app, flashed at offset 0 |
| `index.html` | the installer page, using [ESP Web Tools](https://esphome.github.io/esp-web-tools/) |
| `manifest-*.json` | tells the flasher which chip and which file |

Nothing here is personal — Wi-Fi credentials and API keys are typed into the
board and kept in its own storage, so these images suit anybody.
