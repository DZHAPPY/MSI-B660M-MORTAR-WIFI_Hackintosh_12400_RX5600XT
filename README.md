# **微星 B660M 迫击炮 WiFi 黑苹果 EFI**

## **配置**

| 组件           | 型号                             |
| -------------- | -------------------------------- |
| **CPU**        | **12th-i5-12400**                |
| **主板**       | **微星 B660M 迫击炮 Wi-Fi DDR4** |
| **显卡**       | **XFX 5600XT**                   |
| **网卡**       | **AX211**                        |
| **OC 版本**    | **0.9.3**                        |
| **MacOS 版本** | **MacOS Venture 13.5**           |
| **机箱**       | **傻瓜超人 K88 青春版**          |

**根据大佬[lyq1996](https://github.com/lyq1996/MSI-B660M-MORTAR-WIFI_Hackintosh_12700_6800XT)发布的 EFI 做了稍微修改：**

- **重新定制了 USB(只适用与 K88 青春版)，前面板 usb3.0 接口、type-C 接口、后面主板四个 usb2.0 接口、USB3.0 接口、type-C 接口**
- **注入 WIFI 和蓝牙驱动**
- **由于 i5-12400 没有 E-Core,删除 CpuTopologyRebuild.kext**

## **更新日志**

### 2023-8-10

1. 更新 opencore 到 0.9.3
2. 更新 airportltlwm 到 2.2.0
3. 更新 BlueToolFixup 到 2.6.8
4. 重新定制了 USB，在 MacOS Ventura 13.5 版本测试 Wifi，蓝牙均可正常使用
