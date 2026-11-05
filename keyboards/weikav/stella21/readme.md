# STELLA 21 and STARS 21

> [!WARNING]
> **Supported hardware: only the original WEIKAV Stars21 (non-Plus) PCB shown below.**
>
> Several boards are sold under the "Stars21" name, and their PCBs differ. **Not supported:**
> - **Stars21 Plus**
> - **Stars21-S / S21-HS** (USB Product ID `0xE543`)
> - **Other PCB revisions** (e.g. with the DFU pads in a different location)
>
> Flashing this firmware on another board has been reported to leave it stuck in DFU mode or with no keys responding.
> Before flashing, compare your PCB with the photos below. If it is different, get the stock firmware for your revision from your seller or WEIKAV ([weikav.com/waikv-software](https://weikav.com/waikv-software/)).
> Background: [issue #1 in qmk_firmware_weikav_stars21](https://github.com/UnderGate-lab/qmk_firmware_weikav_stars21/issues/1#issuecomment-4713265965).
>
> 対応基板は、下の写真と同じ **WEIKAV Stars21（Plusではない無印）** のPCBだけです。Stars21 Plus、Stars21-S（PID `0xE543`）、そのほかのリビジョンには書き込まないでください。

<p>
<img src="https://github.com/user-attachments/assets/5d4c9ea0-de82-4130-9682-934a4d43d8b6" width="30%" alt="Supported Stars21 PCB (1)">
<img src="https://github.com/user-attachments/assets/fd387993-1c9a-4c5b-b201-9847eadf059d" width="30%" alt="Supported Stars21 PCB (2)">
<img src="https://github.com/user-attachments/assets/5342b88b-fd6e-46b3-94ff-fa3fad7a64cb" width="30%" alt="Supported Stars21 PCB (3)">
</p>

A Vial version for the same PCB is available at [UnderGate-lab/vial-qmk](https://github.com/UnderGate-lab/vial-qmk/tree/weikav-stella21-vial/keyboards/weikav/stella21).

[![STELLA 21](https://s21.ax1x.com/2025/02/19/pEM7NWD.jpg)](https://imgse.com/i/pEM7NWD)

* Keyboard Maintainer: [jonylee@hfd](https://github.com/jonylee1986)
* Hardware Supported: WEIKAV STELLA 21
* Hardware Availability: [WEIKAV](http://www.weikavcn.com)

Make example for this keyboard (after setting up your build environment):

    make weikav/stella21:default

Flashing example for this keyboard:

    make weikav/stella21:default:flash
    
See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the Hold down the top left key (commonly programmed as *Esc*) and plug in the keyboard
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
