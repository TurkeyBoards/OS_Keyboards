# Open Source Keyboard Firmware Repository

Welcome to the official files repository for the open source keyboards sold by TurkeyBoards. This repository contains the firmware, configuration files, STL 3D Printable Case files, and any additional resources for each keyboard we support.

## Contents

- [Supported Keyboards](#supported-keyboards)
- [Case](#case)
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

## Case
We have the STL files available for you to print your own keyboard case. All our cases are designed for use with Heat press insert threads. If you need some they are easy to purchase off of:
- Amazon - https://amzn.to/4ov1lON

---

## Firmware

Precompiled `.uf2` firmware files and source code can be found in the appropriate subfolders:


Each folder typically contains:

- `case` – STL file to 3D print your own keyboad case
- `firmware` – Precompiled firmware ready to flash in .uf2 format
- `Layout` – Optional ZMK/QMK/Vial build files and metadata
- `readme.md` – Notes specific to that keyboard’s configuration and usage
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
- [Discord](https://discord.gg/N8YrUdvYMN)
- [/r/Turkeyboards](https://www.youtube.com/@turkeyboards)
- [Youtube](https://www.youtube.com/@turkeyboards)

🔗 **Need help or have questions?**  
Check out our [Docs site](https://docs.turkeyboards.com/) & reach out in our discord or subreddit for help!
