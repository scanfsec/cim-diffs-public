# XCD 3,5/45: 0.5.6 ➜ 0.5.13

> 生成时间: 2026-10-07T06:28:27 · CIM 日期: 2017-09-07 ➜ 2017-11-30 · 条目: 6 ➜ 6 · 源: `X-Lens_v0_5_6.cim` ➜ `X-Lens_v0_5_13.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +5/-5/~1；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 5 变更 / 0 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `XCD120_1601420_20_0_12.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.8 KB | +8.8 KB |
| `XCD30_1601327_20_0_10.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.8 KB | +8.8 KB |
| `XCD45_1601209_20_0_25.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.8 KB | +8.8 KB |
| `XCD90_1601210_20_0_29.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.8 KB | +8.8 KB |
| `XCD_FW_1601245_0_5_13.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 201.1 KB | +201.1 KB |
| `XCD120_1601420_20_0_9.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.8 KB | — | -8.8 KB |
| `XCD30_1601327_20_0_9.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.8 KB | — | -8.8 KB |
| `XCD45_1601209_20_0_24.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.8 KB | — | -8.8 KB |
| `XCD90_1601210_20_0_28.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.8 KB | — | -8.8 KB |
| `XCD_FW_1601245_0_5_6.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 189.6 KB | — | -189.6 KB |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.2 KB | 12.1 KB | +867 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 5 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 5 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 1 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## OTA Images

共 0 个条目, 无增删改。

## Filesystem

文件树无增删改（system+vendor 合并视图）。

## ELF Symbols

全固件汇总: **+0 / −0** functions, **+0 / −0** objects（0 个变更 ELF）。

无变更 ELF。

## Strings

新增字符串共 **0** 条（每组截断至 ? 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

无变更 ELF。

## Scripts & Config

共 0 个脚本/配置变更, 0 行 unified diff（context=3, 预算上限 ? 行）。

无文本类变更。

## Lens Firmware

镜头固件对比: 5 变更 · 0 新增 · 0 移除 · 0 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `XCD120` | 20.0.9 → 20.0.12 | 8.8 KB → 8.8 KB | 1.13% | 3 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD30` | 20.0.9 → 20.0.10 | 8.8 KB → 8.8 KB | 0.25% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD45` | 20.0.24 → 20.0.25 | 8.8 KB → 8.8 KB | 0.28% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD90` | 20.0.28 → 20.0.29 | 8.8 KB → 8.8 KB | 0.25% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD_FW · main` | 0.5.6 → 0.5.13 | 189.6 KB → 201.1 KB | 97.58% | 8 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |

**`XCD120`** 变化区域（前 3 段）:

- off `0x1002` len `17`
- off `0x106e` len `62`
- off `0x11f5` len `1`

**`XCD30`** 变化区域（前 2 段）:

- off `0x1002` len `17`
- off `0x11f5` len `1`

**`XCD45`** 变化区域（前 2 段）:

- off `0x1002` len `17`
- off `0x11f5` len `3`

**`XCD90`** 变化区域（前 2 段）:

- off `0x1002` len `17`
- off `0x11f5` len `1`

**`XCD_FW · main`** 变化区域（前 8 段）:

- off `0x8000800` len `26`
- off `0x800082c` len `72020`
- off `0x8012198` len `6`
- off `0x80121b1` len `12`
- off `0x80121fa` len `14`
- off `0x801221a` len `1`
- off `0x8012231` len `18`
- off `0x8012265` len `891`

## Appendix

_无附录内容。_
