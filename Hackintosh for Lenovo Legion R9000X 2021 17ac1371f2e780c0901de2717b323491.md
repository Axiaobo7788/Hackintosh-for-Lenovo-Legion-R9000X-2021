# Hackintosh for Lenovo Legion R9000X 2021

# 简介

- 本仓库基于[Lenovo-R7000P-2020-Hackintosh](https://github.com/wushuo894/Lenovo-R7000P-2020-Hackintosh)修改而来

---

适用于联想拯救者R9000X（2021款）的预配置OpenCore EFI。

| 名称 | 型号 | 状态 |
| --- | --- | --- |
| Opencore 版本 | 1.0.3 |  |
| SMBIOS 仿冒机型 | MacBookPro16,3 |  |
| 最高支持macos版本 | macOS Sonoma 14.4 |  |
| 机型 | Lenovo Legion R9000X 2021 |  |
| CPU | AMD Ryzen™ 7 4800H | √可用 |
| 核显 | AMD Radeon™ Graphics 512MB | √可用 |
| 核显GPU硬件加速 |  | ×不可用(需在软件内关闭GPU硬件加速，如果软件内不可关闭，方法详见：[AMD核显系列处理器解决QQ卡顿](https://github.com/wushuo894/Lenovo-R7000P-2020-Hackintosh)) |
| 独显 | NVIDIA RTX 2060 Max-Q 6GB | ×不可用 |
| 网卡 | Intel(R) Wi-Fi 6 AX200 160MHz   | ○部分可用 |
| 硬盘 | SAMSUNG MZVLB512HBJQ-000L2  (512 GB, PCI-E 3.0 x4) | ×不可用(因此自己安装额外扩展硬盘) |
| 扩展硬盘 | Samsung SSD 980 (PCI-E 3.0 x4) | √可用 |
| 键盘、触控板 |  | √可用 |
| 声卡、音频 | Realtek ALC257 | √可用 |
| 内存 | Samsung M471A1K43DB1-CWE 8 GB DDR4-3200 DDR4 SDRAM x2 | √可用 |
| USB |  | √全部可用 |
| SD卡槽 |  | ×不可用 |
| USB-C视频输出 |  | ×不可用(独显直通，没有希望) |
| 睡眠 |  | ○有时会睡死 |

---

EFI下载：

[蓝奏云](https://github.com/W2725730722/Lenovo-R7000P-2020-Hackintosh/releases)