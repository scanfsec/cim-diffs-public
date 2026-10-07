# XCD 3,4/75P: 1.7.1 ➜ 1.9.7

> 生成时间: 2026-10-07T06:22:41 · CIM 日期: 2024-09-20 ➜ 2025-07-03 · 条目: 6 ➜ 10 · 源: `XCD-Lens-Firmware-XCD-28P-38V-55V-75P-v1_7_1.cim` ➜ `XCD-Lens-Firmware-XCD-28P-38V-55V-75P-v1_9_7.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +4/-0/~6；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 5 变更 / 4 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `LensData_XCD28P.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 128 B | +128 B |
| `LensData_XCD38.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 128 B | +128 B |
| `LensData_XCD55.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 128 B | +128 B |
| `LensData_XCD75P.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 128 B | +128 B |
| `LensSpecifics_XCD28P.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 472 B | 708 B | +236 B |
| `LensSpecifics_XCD38.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 472 B | 708 B | +236 B |
| `LensSpecifics_XCD55.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 472 B | 708 B | +236 B |
| `LensSpecifics_XCD75P.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 472 B | 708 B | +236 B |
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 977.0 KB | 601.6 KB | -375.4 KB |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 12.1 KB | 15.1 KB | +3.0 KB |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 4 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 6 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

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

镜头固件对比: 5 变更 · 4 新增 · 0 移除 · 0 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `XCD28P · data` | — → — | — → 128 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `XCD38 · data` | — → — | — → 128 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `XCD55 · data` | — → — | — → 128 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `XCD75P · data` | — → — | — → 128 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `MAIN · main` | — → — | 977.0 KB → 601.6 KB | 96.91% | 23 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD28P · specifics` | — → — | 472 B → 708 B | 76.23% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD38 · specifics` | — → — | 472 B → 708 B | 77.05% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD55 · specifics` | — → — | 472 B → 708 B | 81.97% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD75P · specifics` | — → — | 472 B → 708 B | 75.82% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |

**`MAIN · main`** 变化区域（前 10 段）:

- off `0x60014c05` len `31`
- off `0x60014c48` len `39`
- off `0x60015008` len `19`
- off `0x6001502c` len `147`
- off `0x600150d1` len `98`
- off `0x6001514c` len `299`
- off `0x60015420` len `79`
- off `0x60015545` len `17`
- off `0x60015578` len `31`
- off `0x6001566c` len `151`

**`XCD28P · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x28` len `204`

**`XCD38 · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x28` len `204`

**`XCD55 · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x28` len `204`

**`XCD75P · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x28` len `204`

## Appendix

_无附录内容。_
