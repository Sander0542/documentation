# Nedis VMAT3462AT

HDMI™ Matrix Switch

## About

Connect 4 sources, such as a game console or multimedia player, to this Nedis matrix switch and to 2 screens. The matrix switch enables you to play 4 source devices on 2 screens independently.

## Infrared (IR) Remote

![Nedis VMAT3462AT Remote](/assets/hardware/nedis/VMAT3462AT-remote.png){ width="200" }

### Button mapping

The IR Remote uses the NEC protocol to send IR signals to the HDMI Switch. In the following table each button is described with their corresponding Protocol, Address and Command.

!!! note
    The NEC protocol uses 8 bit signals. Some libraries (like ESPHome) require you to to write them in full.

    [Source](https://community.home-assistant.io/t/esp-home-ir-transmitter-sending-onkyo-format-instead-of-nec/478514/2)

=== "Normal"

    | Button | Protocol | Address | Command |
    | ------ | -------- | ------- | ------- |
    | Power  | `NEC`    | `0x0`   | `0x14`   |
    | A Off  | `NEC`    | `0x0`   | `0xD`   |
    | A 1    | `NEC`    | `0x0`   | `0x19`  |
    | A 2    | `NEC`    | `0x0`   | `0x15`  |
    | A 3    | `NEC`    | `0x0`   | `0x50`  |
    | A 4    | `NEC`    | `0x0`   | `0x4A`  |
    | B Off  | `NEC`    | `0x0`   | `0x2`   |
    | B 1    | `NEC`    | `0x0`   | `0x18`  |
    | B 2    | `NEC`    | `0x0`   | `0x51`  |
    | B 3    | `NEC`    | `0x0`   | `0x53`  |
    | B 4    | `NEC`    | `0x0`   | `0x45`  |

=== "8 Bit"

    | Button | Protocol | Address | Command |
    | ------ | -------- | ------- | ------- |
    | Power  | `NEC`    | `0xFF00`   | `0xEB14`   |
    | A Off  | `NEC`    | `0xFF00`   | `0xF20D`   |
    | A 1    | `NEC`    | `0xFF00`   | `0xE619`  |
    | A 2    | `NEC`    | `0xFF00`   | `0xEA15`  |
    | A 3    | `NEC`    | `0xFF00`   | `0xAF50`  |
    | A 4    | `NEC`    | `0xFF00`   | `0xB54A`  |
    | B Off  | `NEC`    | `0xFF00`   | `0xFD02`   |
    | B 1    | `NEC`    | `0xFF00`   | `0xE718`  |
    | B 2    | `NEC`    | `0xFF00`   | `0xAE51`  |
    | B 3    | `NEC`    | `0xFF00`   | `0xAC53`  |
    | B 4    | `NEC`    | `0xFF00`   | `0xBA45`  |

## Product information

[Source (nedis.com)](https://nedis.com/en-us/product/cables-and-adapters/video/hdmi-devices/550715207/hdmi-matrix-switch-4-x-2-ports-4x-hdmi-input-2x-hdmi-output-4k-at-30hz-34-gbps-remote-controlled-metal-anthracite)

-   **Brand**: Nedis
-   **Vendor Part Number**: VMAT3462AT
-   **EAN number**: 5412810319985