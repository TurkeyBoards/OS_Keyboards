# Open Source Keyboard Firmware Repository

Welcome to the official firmware repository for the open source keyboards sold by [Your Brand Name]. This repository contains firmware, configuration files, and additional resources for each keyboard we support.

## Contents

- [Supported Keyboards](#supported-keyboards)
- [Firmware](#firmware)
- [Usage Instructions](#usage-instructions)
- [License](#license)
- [Contributing](#contributing)

---

## Supported Keyboards

This repo includes files and firmware for the following open-source keyboards each in their respective folders:

- [**Corne v4.1**]("./corne-v4_1/")
- [**Lily58 Pro**]("./lily58pro/")
- [**Sofle Choc**]("./sofle_choc/")

More keyboards may be added over time.

---

## Firmware

Precompiled `.uf2` firmware files and source code can be found in the appropriate subfolders:


Each folder typically contains:

- `firmware.uf2` – Precompiled firmware ready to flash
- `keymap.json` – Keymap file (for use with Vial)
- `readme.md` – Notes specific to that keyboard’s configuration and usage
- Optional ZMK/QMK/Vial build files and metadata

---

## Usage Instructions

Here is a general workflow for flashing your keyboard:

1. **Download the appropriate firmware** for your keyboard from the subfolder.
2. **Flash the firmware** using your preferred tool:
   - For RP2040-based boards: Drag and drop `.uf2` file onto the bootloader drive.
3. **Customize your layout** using:
   - [Vial](https://get.vial.today)
   - `keymap.c` if you prefer to build via QMK manually

More detailed flashing and configuration instructions are available on our [Docs site]("https://docs.turkeyboards.com/").

---

## License

All firmware and configuration files hosted here are open source and shared under the MIT license unless otherwise noted.

> Please check the original Keyboard repositories for their respective licenses.

---
## Contributing

Share your layout, pictures of your keyboard/setup, and more in our community on:
- [Discord]("https://discord.gg/N8YrUdvYMN")
- [/r/Turkeyboards]("https://www.youtube.com/@turkeyboards")
- [Youtube]("https://www.youtube.com/@turkeyboards")

🔗 **Need help or have questions?**  
Check out our [Docs site]("https://docs.turkeyboards.com/") & reach out in our discord or subreddit for help!
