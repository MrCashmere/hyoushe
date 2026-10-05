# 致谢

**本项目向以下开源项目致以诚挚感谢。它们在功能设计上为本项目提供了重要的参考。**

## 直接使用 / 复用代码的项目（代码级复用）

- [NTE-Auto-Sign](https://github.com/MF-Dust/NTE-Auto-Sign) — MIT — 整个检入工作区，Python 签到工具
- [skyland-auto-sign](https://github.com/skyland-auto-sign) — MIT — `SmDevice.ets` 逐位移植了 `SecuritySm.py`

## 数据 / 文档级使用（API对照用）

- [https://github.com/UIGF-org/mihoyo-api-sdk](https://github.com/UIGF-org/mihoyo-api-sdk) — MIT — 对照接口文档

## 运行时下载数据集

- [BTMuli/TeyvatGuide](https://github.com/BTMuli/TeyvatGuide) — MIT — 历史卡池数据集（通过 jsDelivr 下载 `gacha.json`）
- [UIGF 公开字典接口](https://api.uigf.org/dict/genshin/chs.json)  — MIT — UIGF 项目的一部分

注意：历史卡池数据集并不依赖以上项目，我们使用了其标准并基于官方wiki建立了自己的内置数据集。**非原神部分**使用的是我们的自建数据集。

## 对照实现（对照文档+参考文档，未使用其源码）

- [enpitsulin/skland-daily-attendance](https://github.com/enpitsulin/skland-daily-attendance) — MIT
- [AEtherside/skland-kit](https://github.com/AEtherside/skland-kit) — MIT
- [GuGuMur/nonebot-plugin-skland-arksign](https://github.com/GuGuMur/nonebot-plugin-skland-arksign) — MIT
- [TomyJan/Kuro-API-Collection](https://github.com/TomyJan/Kuro-API-Collection) — MPL-2.0
- [mxyooR/Kuro_login](https://github.com/mxyooR/Kuro_login) — MIT
- [MF-Dust/NTE-Auto-Sign](https://github.com/MF-Dust/NTE-Auto-Sign) — MIT

## 生态索引（功能对照参考，未使用其源码）

- [biuuu/genshin-wish-export](https://github.com/biuuu/genshin-wish-export) - MIT
- [biuuu/star-rail-warp-export](https://github.com/biuuu/star-rail-warp-export) - MIT
- [voderl/genshin-gacha-analyzer](https://github.com/voderl/genshin-gacha-analyzer) - 未列出
- [YuehaiTeam/cocogoat](https://github.com/YuehaiTeam/cocogoat) - BSD-v3
- [yoimiya-kokomi/Miao-Yunzai](https://github.com/yoimiya-kokomi/Miao-Yunzai) - GPL-v3

本项目的功能实现均为独立开发。在功能完成后，曾通过双方共同调用的独立于上述所有项目的API，以黑盒方式对本节列出的开源项目所声明的调用功能进行完整性对照参考。该过程不涉及查看、复制或借鉴其源代码、内部结构或实现逻辑。仅获取**用户可见的输出**。本项目与本节列出的开源项目之间**不存在代码层面的衍生或链接关系**。
