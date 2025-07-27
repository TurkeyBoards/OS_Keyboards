## 🔧 Flashing Firmware on RP2040 Keyboards (with Vial Backup & Restore)

Follow these steps to safely update your firmware and keep your custom settings intact.

---

### Step 1: Back Up Your Configuration (Vial)

Before flashing new firmware, back up your current keymap and settings.

1. **Open Vial**:  
   Download from [https://get.vial.today](https://get.vial.today) if not already installed.

2. **Connect your keyboard** and make sure it appears in Vial.

3. **Export Settings**:
   - Click the ☰ menu (three bars) in the upper left.
   - Choose **"Backup Settings"**.
   - Save the `.json` file to a safe location.  
     This includes your keymap, lighting, encoder behavior, and other settings.

---

### Step 2: Enter Bootloader Mode

To flash new firmware, you need to enter bootloader mode:

> NOTE: Unplug your TRRS Cable & follow this process for each half of your keyboard one at a time.

1. **Unplug the keyboard**.
2. **Hold the boot button** on the RP2040 controller (usually labeled `BOOTSEL`).
3. **While holding**, plug the keyboard back in via USB.
4. A new USB drive (e.g. `RPI-RP2`) will appear on your computer.

>  If your keyboard has a reset or boot key combo, you can also use that instead.

---

### Step 3: Flash the Firmware

1. **Download the new `.uf2` firmware file** from this repository.
2. **Drag and drop** the `.uf2` file onto the `RPI-RP2` drive.
3. The drive will eject, and the keyboard will reboot automatically.

---

### Step 4: Restore Your Vial Settings

1. **Open Vial** again after your keyboard reboots.
2. From the ☰ menu, choose **"Restore Settings"**.
3. Select your previously saved `.json` file.

Your keyboard will immediately update with your saved keymap and preferences.

---

### Done!

You’ve successfully updated your firmware and restored your configuration.

Need help? Open an issue or check out [vial.today](https://get.vial.today).
