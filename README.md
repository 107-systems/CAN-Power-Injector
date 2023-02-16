<a href="https://107-systems.org/"><img align="right" src="https://raw.githubusercontent.com/107-systems/.github/main/logo/107-systems.png" width="15%"></a>
`CAN-Power-Injector`
====================
[![Spell Check status](https://github.com/107-systems/CAN-Power-Injector/actions/workflows/spell-check.yml/badge.svg)](https://github.com/107-systems/CAN-Power-Injector/actions/workflows/spell-check.yml)

The purpose of this board is to inject 5V DC power at up to 5A for powering CAN bus devices.

<p align="center">
  <a href="https://github.com/107-systems/l3xz"><img src="https://raw.githubusercontent.com/107-systems/.github/main/logo/l3xz-logo-memento-mori-github.png" width="40%"></a>
</p>

<p align="center">
  <img src="docs/images/CAN-Power-Injector_rendering.png" width="50%">
</p>

#### Blockdiagram
<p align="center">
  <img src="CAN-Power-Injector.jpg" width="50%">
</p>

#### Electrical Parameters
| Name | Value |
|-|-|
| V_IN min | 10.5 V | set by resistor divider(R7/R8) |
| V_IN max | 40.0 V | limited by TVS diode (D4) |
| V_CAN_OUT | 5.0 V to 5.5 V|
| I_CAN_OUT,CONTINUOUS | 5.0 A |

#### Inputs
| Designator | Name | Connector |
|-|-|-|
| CN4 | Battery (4S / 4100 mAh LiFePo) | [Powerpole® PP15 to PP45](https://www.andersonpower.com/content/dam/app/ecommerce/product-pdfs/PP-Pak/ds-pp1545.pdf) |
| CN1 | Battery | 3.5 mm screw terminal (not populated) |

#### Outputs
| Designator | Name | Connector |
|-|-|-|
| CN2 and CN3 | CAN channel 1 | JST GH 1.25mm 4-pin. |
| CN5 and CN6 | CAN channel 2 | JST GH 1.25mm 4-pin. |
| CN7 | 5V | 5V output, internal for testing (not populated) |

## Enclosure

There exists a 3D printable enclosure to encapsulate the PCB.

### Standard
<p align="center">
  <img src="docs/images/CAN-Power-Injector_enclosure.png" width="50%">
</p>

### Low profile
<p align="center">
  <img src="docs/images/CAN-Power-Injector_enclosure_lp.png" width="50%">
</p>

## PCB
### Top
<p align="center">
  <img src="docs/images/CAN-Power-Injector_top.png" width="50%">
</p>

### Bottom
<p align="center">
  <img src="docs/images/CAN-Power-Injector_bot.png" width="50%">
</p>
