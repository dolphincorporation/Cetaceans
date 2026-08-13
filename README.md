# Supported and Tested Devices

This document tracks tested hardware platforms, SoC architectures, and kernel versions supported by **Cetaceans**.

---

## Device Support Matrix

| Model | Device | Android | Kernel | CPU | Cetaceans | Integrity | SYS SCAN | Notes | Extended Integrity |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **LG V60 ThinQ 5G** | LGE LM-V600 | 10 | 4.19.81 | Qualcomm SM8250 (Snapdragon 865 5G) | 10.52 | PASS | PASS | Fully operational (Non GKI) | PASS
| **Xiaomi Redmi Note 13 4G** | 23129RAA4G | 15 | 5.15.178 | Qualcomm Snapdragon 685 | 10.34 | PASS | PASS | Fully operational (GKI) | x
| **OnePlus Nord CE5** | OnePlus CPH2719 | 16 | 6.1.157 | MediaTek Dimensity 8350 Apex | 10.34 | PASS | PASS | Fully operational (GKI) | x
| **Samsung Galaxy A52s 5G** | Samsung SM-A528B | 14 | 5.4.256 (Ascendia KSU) | Snapdragon 778G 5G | 10.34 | PASS | PASS | Fully operational (qGKI) | x
| **Motorola Moto G34** | Motorola moto g34 5G | 15 | 5.4.284 | Qualcomm SM6375 Snapdragon 695 5G | 10.34 | PASS | PASS | Fully operational (qGKI) | x
| **Xiaomi Poco X7** | Xiaomi 24095PCADI | 16 | 6.1.138 | Mediatek Dimensity 7300 Ultra | 10.38 | PASS | PASS | Fully operational (GKI, Dual PID+MM Fix) | x
| **Motorola Moto G57 Power** | Motorola moto g57 power | 16 | 6.6.87 | Qualcomm SM6435-AA Snapdragon 6s Gen 4 | 10.38 | PASS | PASS | Fully operational (GKI) | x
| **Xiaomi Poco F6** | Xiaomi POCO 24069PC21l | 16 | 6.1.118 | Qualcomm SM8635 Snapdragon 8s Gen 3 | 10.38 | PASS | PASS | Fully operational (GKI) | x
| **Infinix Hot 70** | INFINIX infinix X6895B | 16 | 6.12.38 | Mediatek Helio G100 Ultimate | 10.38 | PASS | PASS | Fully operational (GKI) | x
| **Infinix Hot 40 Pro** | INFINIX infinix X6837 | 13 | 5.10.226 | Mediatek Helio G99 | 10.38 | PASS | PASS | Fully operational (GKI) | x
| **Xiaomi POCO F5 5G** | Xiaomi POCO 23049PCD8I | 15 | 5.10.236 | Qualcomm Snapdragon 7+ Gen 2 | 10.38 | PASS | PASS | Fully operational (GKI) | PASS
| **Infinix Note 30** | INFINIX infinix X6833B | 14 | 5.10.209 | Mediatek Helio G99 | 10.38 | PASS | PASS | Fully operational (GKI) | x
| **Infinix Note 50 Pro 4G** | INFINIX infinix X6855 | 15 | 5.10.209 | Mediatek Helio G100 Ultimate | 10.52 | PASS | PASS | Fully operational (GKI) | PASS
| **Xiaomi Redmi Note 12 5G** | Xiaomi Redmi 22101317C | 14 | 5.4.289 | Qualcomm Snapdragon 4 Gen 1 | 10.38 | PASS | PASS | Fully operational (qGKI) | x
| **Realme C55** | Realme RMX3710 | 15 | 6.6.30 | MediaTek Helio G88 | 10.38 | PASS | PASS | Fully operational (GKI) | x
| **Samsung Galaxy M14 4G** | Samsung SM-145F | 15 | 5.15.180 | Qualcomm SM6225 Snapdragon 680 4G | 10.52 | PASS | PASS | Fully operational (GKI) | PASS
| **Xiaomi Mi 11i** | Xiaomi M2012K11G | 12 | 5.4.147 | Qualcomm SM8350 Snapdragon 888 5G | 10.52 | PASS | PASS | Fully operational (GKI) | PASS
--- 

## ARMv8.5+ / ARMv9 BTI (Branch Target Identification) Compliance Note

**Cetaceans** is fully operational on ARMv9-A / Kernel 6.1+ platforms with enforced BTI (Branch Target Identification)
