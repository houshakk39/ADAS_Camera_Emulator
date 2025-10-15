# Reference Datasheets & Technical Documentation

This folder collects **key component datasheets** and **reference links** used in the design and study of the HDMI → FPD-Link III / GMSL2 ADAS camera emulator.

---

## HDMI Interface
| Component / Topic | Description | Link |
|-------------------|--------------|------|
| **ADV7611 (Analog Devices)** | HDMI receiver with parallel RGB output | [Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/ADV7611.pdf) |
| **TFP401A (Texas Instruments)** | DVI/HDMI receiver, 165 MHz | [Datasheet](https://www.ti.com/lit/ds/symlink/tfp401a.pdf) |
| **HDMI Basics (Analog Devices)** | Article explaining TMDS, DDC, and CEC | [HDMI Fundamentals](https://www.analog.com/en/analog-dialogue/articles/hdmi-basics.html) |

---

## FPD-Link III / GMSL2 Interfaces
| Component / Topic | Description | Link |
|-------------------|--------------|------|
| **DS90UB953-Q1 (TI)** | FPD-Link III serializer (camera to ECU) | [Datasheet](https://www.ti.com/product/DS90UB953-Q1) |
| **DS90UB954-Q1 (TI)** | FPD-Link III deserializer (ECU side) | [Datasheet](https://www.ti.com/product/DS90UB954-Q1) |
| **MAX96705 / MAX96706 (Analog Devices)** | GMSL2 serializer/deserializer pair | [Datasheet](https://www.analog.com/en/products/max96705.html) |

---

## MCU & Supporting Components
| Component | Description | Link |
|------------|--------------|------|
| **STM32L476RG (STMicroelectronics)** | Main MCU (NUCLEO board) | [Reference Manual](https://www.st.com/resource/en/reference_manual/dm00083560.pdf) |
| **LM1117-3.3** | LDO 5 V → 3.3 V regulator (for simulation) | [Datasheet](https://www.ti.com/lit/ds/symlink/lm1117.pdf) |

---

