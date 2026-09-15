# 貨架 A0-5-1
盤點時間：2026/09/11-10:33

下次盤點時間：2026/09/18

## 8ARMS_RGT_E2U_F405

零件編號：1-ZD-FR-E2U-F405

| 項目 | 規格 |
| --- | --- |
| MCU | STM32F405RGT6（M4、168 MHz、1 MB Flash） |
| 陀螺儀 | ICM-42605（部分版可能為 BMI270） |
| 氣壓計 | SPL06 / SPL06-001 |
| OSD | **僅 HD OSD**（DJI HD、Snail HD、OpenIPC 等），**不支援類比 OSD** |
| UART | 約 3～3.5 組（SBUS 僅 RX，常計半組） |
| SBUS | 1（RX only） |
| PWM | 6 路 + 1（S12 常用作 LED） |
| I²C | 1（外接電流計／氣速等） |
| 電流計 | **無板載類比電流計**；支援外接 I²C 電流計 |
| 電壓量測 | 標稱 2.5–30 V（1–6S）；實際需注意板上僅雙 LDO |
| 飛控供電 | **5 V 輸入**（獨立 BEC） |
| USB | Type-C（可直插；雙 Type-C 線可連手機地面站） |
| 圖傳 | SH1.0 6P 直插 HD VTX |
| 接收機 | SBUS / CRSF；可直插 ELRS 接收機 |
| 尺寸 | 27.9 × 20.3 × 11.2 mm |
| 重量 | 2.8 g（不含排針）；焊排針約 5.3 g |
| PCB | 黑油、沉金、樹脂塞孔、四層板 |

> 注意：這不是一體式 wing 飛控。板上沒有舵機供電軌，舵機必須用外接 BEC。體積雖小，完整系統仍需獨立電源模組。


![8ARMS_RGT_E2U_F405_尺寸圖](../assets/images/1-ZD-FR-E2U-F405/zsHlx.jpg)
![8ARMS_RGT_E2U_F405_接線圖](../assets/images/1-ZD-FR-E2U-F405/A0T4m.jpg)
---

## 8ARMS_RGT_2VU_F405

零件編號：1-ZD-FR-2VU-F405

| 項目 | 規格 |
| --- | --- |
| 型號 | FlyingRC F4D MK1 |
| 尺寸 | 36.6 × 36.6 × 8.0 mm；剪斷安裝耳後 28.1 × 31.1 × 8.0 mm |
| 孔距 | 30.5 mm／20 mm（內孔 Φ4 mm） |
| 質量 | 6.3 g |
| 主控 | STM32F405RGT6，168 MHz，Flash 1 MB，RAM 192 KB |
| IMU | Invensense 第三代 ICM-42688-P |
| 氣壓計 | Goertek SPA06／SPA06-003 |
| 磁力計 | 無板載 |
| 類比 OSD | AT7456E |
| BEC | MP9943 + MP9943：設備 **5V／3A**，圖傳 **9V／2A** |
| UART | 6 組（UART3 僅引出 RX） |
| PWM | 5 個（4 ESC + 1 LED） |
| I2C | 1 |
| 電流 ADC | 支援（板載電流計取樣） |
| SWD | 無 |
| 蜂鳴器 | 參數表標示無 |
| LED | 支援 WS2812 |
| USB | Type-C 板載直插 |
| 黑盒子 | 板載 NOR Flash 16 MB（128 Mbit） |
| SBUS | 參數表標示不支援（接收機多用 CRSF／ELRS UART） |
| VBAT | 7–28 V DC IN，2–6S LiPo |
| 工作溫度 | −10–100 °C |
| 儲存溫度 | 0–40 °C |

![8ARMS_RGT_2VU_F405_尺寸圖](../assets/images/1-ZD-FR-2VU-F405/mqddy.jpg)
![8ARMS_RGT_2VU_F405_尺寸圖](../assets/images/1-ZD-FR-2VU-F405/wiring-full.jpg)
---

## aaa
bbbbbbbbbbbbbbbbbbbbbb
ccccccccccccccccccccccccccccccccc

