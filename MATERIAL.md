# Hardware — Bill of Materials

Custom Stream Deck PCB. 4-layer board, 77×46mm, ATmega32U4 + USB-C + I2C OLED + 3×3 button grid.

## Active Components

| Ref | Component | Value / Spec | Footprint | Qty |
|---|---|---|---|---|
| U1 | Microcontroller ATmega32U4 | TQFP-44, native USB | `Package_QFP:TQFP-44_10x10mm_P0.8mm` | 1 |
| U2 | OLED Display, I2C | 0.91", SSD1306 | `Display:ER_OLEDM0.91_1x-I2C` | 1 |
| Y1 | Crystal | 16 MHz | `Crystal:Crystal_SMD_HC49-SD` | 1 |
| J2 | USB-C Connector | Receptacle 14P/16P | `Connector_USB:USB_C_Receptacle...` | 1 |

## Resistors (0805)

| Ref | Role | Value | Footprint | Qty |
|---|---|---|---|---|
| R1 | D- series | 22 Ω | `Resistor_SMD:R_0805_2012Metric` | 1 |
| R2 | D+ series | 22 Ω | `Resistor_SMD:R_0805_2012Metric` | 1 |
| R3 | CC1 | 5.1 kΩ | `Resistor_SMD:R_0805_2012Metric` | 1 |
| R4 | CC2 | 5.1 kΩ | `Resistor_SMD:R_0805_2012Metric` | 1 |
| R5 | D+ pull-up | 1.5 kΩ | `Resistor_SMD:R_0805_2012Metric` | 1 |
| R6 | RESET pull-up | 10 kΩ | `Resistor_SMD:R_0805_2012Metric` | 1 |

## Capacitors (0805)

| Ref | Role | Value | Footprint | Qty |
|---|---|---|---|---|
| C1 | Crystal XTAL1 | 22 pF | `Capacitor_SMD:C_0805_2012Metric` | 1 |
| C2 | Crystal XTAL2 | 22 pF | `Capacitor_SMD:C_0805_2012Metric` | 1 |
| C3 | UCAP | 1 µF | `Capacitor_SMD:C_0805_2012Metric` | 1 |
| C4 | VCC decoupling | 100 nF | `Capacitor_SMD:C_0805_2012Metric` | 1 |
| C5 | UVCC decoupling | 100 nF | `Capacitor_SMD:C_0805_2012Metric` | 1 |
| C6 | AVCC decoupling | 100 nF | `Capacitor_SMD:C_0805_2012Metric` | 1 |

## Buttons

| Ref | Component | Spec | Footprint | Qty |
|---|---|---|---|---|
| SW1–SW9 | Push buttons (3×3 grid) | 6×6mm THT, 4-pin | `Button_Switch_THT:SW_PUSH_6mm` | 9 |
| SW10 | Reset button | 6×6mm THT, 4-pin | `Button_Switch_THT:SW_PUSH_6mm` | 1 |

## Misc

| Item | Spec | Qty |
|---|---|---|
| PCB (4-layer, JLCPCB) | 77×46mm, batch of 5 | 1 batch |
| Button cap | — | 1 (adjust as needed) |

## Unique Part Count

- **1×** ATmega32U4 (U1)
- **1×** SSD1306 OLED display (U2)
- **1×** 16MHz crystal (Y1)
- **1×** USB-C connector (J2)
- **6×** 0805 resistors (R1–R6, various values)
- **6×** 0805 capacitors (C1–C6, various values)
- **10×** 6×6mm THT push buttons (SW1–SW10)
- **1×** PCB (batch of 5, JLCPCB)

**Total parts to solder: 25** (excluding PCB and button cap)
