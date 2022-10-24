<a href="https://107-systems.org/"><img align="right" src="https://raw.githubusercontent.com/107-systems/.github/main/logo/107-systems.png" width="15%"></a>
`l3xz-hw_can_power_injector`
============================
The purpose of this board is to provide 5V DC power to all connected CAN bus devices on the L3X-Z hexapod (except the Rasperry Pi).

![l3xz-hw_can_power_injector rendering](docs/images/l3xz-hw_can_power_injector_rendering.png)

#### Blockdiagram
<p align="center">
  <img src="can-power-injector-block-diagram.jpg" width="50%">
</p>

#### Electrical Parameters
| Name | Value |
|-|-|
| V_BAT_IN | 13.0 - 16.8 V|
| V_CAN_OUT | 5.0 V |
| I_CAN_OUT,CONTINOUS | 3.0 A |

#### Inputs
| Name | Connector |
|-|-|
| Battery (4S / 4100 mAh LiFePo) | [Powerpole® PP15 to PP45](https://www.andersonpower.com/content/dam/app/ecommerce/product-pdfs/PP-Pak/ds-pp1545.pdf) |
| CAN | JST GH 1.25mm 4-pin. |

#### Outputs
| Name | Connector |
|-|-|
| CAN | JST GH 1.25mm 4-pin. |

## PCB

### Top

![l3xz-hw_can_power_injector PCB top](docs/images/l3xz-hw_can_power_injector_top.png)

### Bottom

![l3xz-hw_can_power_injector PCB bot](docs/images/l3xz-hw_can_power_injector_bot.png)
