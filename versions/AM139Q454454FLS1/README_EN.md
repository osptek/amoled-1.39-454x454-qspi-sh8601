<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.39″ AMOLED 454×454 (SH8601 · QSPI)</h1>

<p align="center"><b>Round-ready AMOLED module · QSPI · SH8601</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 1.39 inch" src="https://img.shields.io/badge/Size-1.39%22-3498DB?style=flat-square" />
  <img alt="Resolution: 454x454" src="https://img.shields.io/badge/Resolution-454%C3%97454-8E44AD?style=flat-square" />
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: SH8601" src="https://img.shields.io/badge/Driver-SH8601-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.39&quot; 454×454 AMOLED QSPI module (SH8601) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **1.39″ 454×454 AMOLED** is a **QSPI** color display module driven by **SH8601**, with touch controller **CST820**. The square resolution suits wearables and compact round HMI panels.

Spec ID (repository name): `1.39-amoled-454x454-qspi-sh8601`

Current module version: **AM139Q454454FLS1**. Electrical and mechanical details follow [`docs/AM_139_Q454454_FLS_1_b691bc4634.pdf`](./docs/AM_139_Q454454_FLS_1_b691bc4634.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.39 inch |
| Type | AMOLED (color) |
| Resolution | 454×454 |
| Interface | QSPI |
| Driver IC | SH8601 |
| Touch IC | CST820 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-S3 · SH8601 QSPI + LVGL8 (touch CST820) | [`examples/ESP32-S3-Display_SH8601-QSPI_LVGL-V8/`](./examples/ESP32-S3-Display_SH8601-QSPI_LVGL-V8/) |

## Repository layout

```text
1.39-amoled-454x454-qspi-sh8601/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── AM139Q454454FLS1/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (AM139Q454454FLS1) | [`docs/AM_139_Q454454_FLS_1_b691bc4634.pdf`](./docs/AM_139_Q454454_FLS_1_b691bc4634.pdf) |
| Driver IC datasheet (SH8601) | [`docs/SH_8601_A0_Data_Sheet_Preliminary_UCS_V0_0_191226_1_143481d321.pdf`](./docs/SH_8601_A0_Data_Sheet_Preliminary_UCS_V0_0_191226_1_143481d321.pdf) |
| Init sequence (text) | [`docs/[SH8601A]1.39_454x454_User_Initial_QSPI.txt`](./docs/[SH8601A]1.39_454x454_User_Initial_QSPI.txt) |

### Samples

- [ESP32-S3 SH8601 QSPI + LVGL8](./examples/ESP32-S3-Display_SH8601-QSPI_LVGL-V8/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
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
