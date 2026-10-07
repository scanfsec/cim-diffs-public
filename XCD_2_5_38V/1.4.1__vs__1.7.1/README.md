# XCD 2,5/38V: 1.4.1 ➜ 1.7.1

> 生成时间: 2026-10-07T06:13:38 · CIM 日期: 2023-02-16 ➜ 2024-09-20 · 条目: 5 ➜ 6 · 源: `XCD38V_XCD55V_XCD28P_v1.4.1.cim` ➜ `XCD-Lens-Firmware-XCD-28P-38V-55V-75P-v1_7_1.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +1/-0/~5；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 4 变更 / 1 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `LensSpecifics_XCD75P.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 472 B | +472 B |
| `LensSpecifics_XCD28P.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 376 B | 472 B | +96 B |
| `LensSpecifics_XCD38.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 376 B | 472 B | +96 B |
| `LensSpecifics_XCD55.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 376 B | 472 B | +96 B |
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 800.9 KB | 977.0 KB | +176.1 KB |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.8 KB | 12.1 KB | +267 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 1 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 5 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

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

镜头固件对比: 4 变更 · 1 新增 · 0 移除 · 0 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `XCD75P · specifics` | — → — | — → 472 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `MAIN · main` | — → — | 800.9 KB → 977.0 KB | 96.95% | 16 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD28P · specifics` | — → — | 376 B → 472 B | 77.44% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD38 · specifics` | — → — | 376 B → 472 B | 80.49% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD55 · specifics` | — → — | 376 B → 472 B | 80.49% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |

**`MAIN · main`** 变化区域（前 10 段）:

- off `0x60014c06` len `30`
- off `0x60014c48` len `40`
- off `0x60015000` len `26`
- off `0x6001502c` len `657`
- off `0x60015400` len `412`
- off `0x6001565c` len `224`
- off `0x60015c00` len `2`
- off `0x60015c64` len `26`
- off `0x60015c9c` len `2314`
- off `0x600165b6` len `1`

**`XCD28P · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x1d` len `135`

**`XCD38 · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x1d` len `135`

**`XCD55 · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x1d` len `135`

## Appendix

_无附录内容。_
