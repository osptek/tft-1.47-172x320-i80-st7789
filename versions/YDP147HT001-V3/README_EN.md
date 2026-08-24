<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.47″ TFT 172×320 (ST7789 · I80)</h1>

<p align="center"><b>Touch TFT module · I80 (8-bit 8080) · ST7789</b></p>

<p align="center">English | <a href="./README.md">简体中文</a> · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 1.47 inch" src="https://img.shields.io/badge/Size-1.47%22-3498DB?style=flat-square" />
  <img alt="Resolution: 172x320" src="https://img.shields.io/badge/Resolution-172%C3%97320-8E44AD?style=flat-square" />
  <img alt="Interface: I80" src="https://img.shields.io/badge/Interface-I80-27AE60?style=flat-square" />
  <img alt="Driver: ST7789" src="https://img.shields.io/badge/Driver-ST7789-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.47″ 172×320 TFT I80 module (ST7789) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **1.47″ 172×320 TFT** is a color display module with an **I80 (8-bit 8080 MCU)** parallel interface, driven by the **ST7789** family, with touch controller **CST816D**. It suits compact HMI, handheld devices, and IoT user interfaces.

Spec ID (repository name): `1.47-tft-172x320-i80-st7789`

Current module version: **YDP147HT001-V3**. Electrical and mechanical details follow [`docs/YDP147HT001-V3.pdf`](./docs/YDP147HT001-V3.pdf).

> **Driver silicon:** This part uses **ST7789V3** (also known later as **ST7789P3**). The repository name and public label stay **ST7789**; see the datasheet and init file below.

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.47 inch |
| Type | TFT (normally black) |
| Resolution | 172×320 |
| Interface | I80 (8-bit 8080 MCU) |
| Driver IC | ST7789 (silicon ST7789V3 / ST7789P3) |
| Touch IC | CST816D |

> Full outline, FPC pinout, power, and timing follow the product datasheet / driver manual.

## Repository layout

```text
1.47-tft-172x320-i80-st7789/           # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP147HT001-V3/                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        └── docs/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP147HT001-V3) | [`docs/YDP147HT001-V3.pdf`](./docs/YDP147HT001-V3.pdf) |
| Driver IC datasheet (ST7789V3, also ST7789P3) | [`docs/ST_7789_V3_SPEC_Preliminary_V0_0_200102_8f4b7f4d5d.pdf`](./docs/ST_7789_V3_SPEC_Preliminary_V0_0_200102_8f4b7f4d5d.pdf) |
| Touch IC datasheet (CST816D) | [`docs/CST_816_D_V1_0_2_1b06dfb078.pdf`](./docs/CST_816_D_V1_0_2_1b06dfb078.pdf) |
| Init parameters (INI) | [`docs/ST7789V3A-1.47IPS-2.2gamma-20210818.INI`](./docs/ST7789V3A-1.47IPS-2.2gamma-20210818.INI) |

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-E62E04?style=for-the-badge&logo=aliexpress&logoColor=white" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group (China): **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository if you have any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
