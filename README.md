<a href="https://107-systems.org/"><img align="right" src="https://raw.githubusercontent.com/107-systems/.github/main/logo/107-systems.png" width="15%"></a>
`l3xz-hw_can_power_injector`
============================
The purpose of this board is to provide 5V DC power to all connected CAN bus devices on the L3X-Z hexapod (except the Rasperry Pi).

<p align="center">
  <a href="https://github.com/107-systems/l3xz"><img src="https://raw.githubusercontent.com/107-systems/.github/main/logo/l3xz-logo-memento-mori-github.png" width="40%"></a>
</p>

![l3xz-hw_can_power_injector rendering](docs/images/l3xz-hw_can_power_injector_rendering.png)

#### Blockdiagram
<p align="center">
  <img src="can-power-injector-block-diagram.jpg" width="50%">
</p>

#### Electrical Parameters
| Name | Value |
|-|-|
| V_IN min | 10.5 V | set by resistor devider(R7/R8) |
| V_IN max | 40.0 V | limited by TVS diode (D4) |
| V_CAN_OUT | 5.0 V to 5.5 V|
| I_CAN_OUT,CONTINOUS | 5.0 A |

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

## enclosure

There exists a 3D printable enclosure to encapsulate the PCB.

### standard

![l3xz-hw_can_power_injector enclosure](docs/images/l3xz-hw_can_power_injector_enclosure.png)

### low profile

![l3xz-hw_can_power_injector enclosure low profile](docs/images/l3xz-hw_can_power_injector_enclosure_lp.png)

## PCB

### Top

![l3xz-hw_can_power_injector PCB top](docs/images/l3xz-hw_can_power_injector_top.png)

### Bottom

![l3xz-hw_can_power_injector PCB bot](docs/images/l3xz-hw_can_power_injector_bot.png)
