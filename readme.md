# WEIKAV Stars21 QMK/VIA firmware (vendor source)

Vendor QMK/VIA source for the WEIKAV Stars21 tri-mode numpad, including the wireless driver. Build `weikav/stella21` (the vendor `stars21` folder is broken; see its readme). Prebuilt firmware: [Releases](https://github.com/UnderGate-lab/qmk_firmware_weikav_stars21/releases).

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

---

# Quantum Mechanical Keyboard Firmware

[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/Uq7gcHh)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the Clueboard product line.

## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

The docs are powered by [Docsify](https://docsify.js.org/) and hosted on [GitHub](/docs/). They are also viewable offline; see [Previewing the Documentation](https://docs.qmk.fm/#/contributing?id=previewing-the-documentation) for more details.

You can request changes by making a fork and opening a [pull request](https://github.com/qmk/qmk_firmware/pulls), or by clicking the "Edit this page" link at the bottom of any page.

## Supported Keyboards

* [Planck](/keyboards/planck/)
* [Preonic](/keyboards/preonic/)
* [ErgoDox EZ](/keyboards/ergodox_ez/)
* [Clueboard](/keyboards/clueboard/)
* [Cluepad](/keyboards/clueboard/17/)
* [Atreus](/keyboards/atreus/)

The project also includes community support for [lots of other keyboards](/keyboards/).

## Maintainers

QMK is developed and maintained by Jack Humbert of OLKB with contributions from the community, and of course, [Hasu](https://github.com/tmk). The OLKB product firmwares are maintained by [Jack Humbert](https://github.com/jackhumbert), the Ergodox EZ by [ZSA Technology Labs](https://github.com/zsa), the Clueboard by [Zach White](https://github.com/skullydazed), and the Atreus by [Phil Hagelberg](https://github.com/technomancy).

## Official Website

[qmk.fm](https://qmk.fm) is the official website of QMK, where you can find links to this page, the documentation, and the keyboards supported by QMK.
