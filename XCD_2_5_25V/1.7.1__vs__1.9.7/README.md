# XCD 2,5/25V: 1.7.1 ➜ 1.9.7

> 生成时间: 2026-10-07T06:12:34 · CIM 日期: 2024-09-20 ➜ 2025-07-03 · 条目: 4 ➜ 6 · 源: `XCD-Lens-Firmware-XCD-25V-90V-v1_7_1.cim` ➜ `XCD-Lens-Firmware-XCD-25V-90V-v1_9_7.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +2/-0/~4；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 3 变更 / 2 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `LensData_XCD25.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 128 B | +128 B |
| `LensData_XCD90.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 128 B | +128 B |
| `LensSpecifics_XCD25.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 428 B | 568 B | +140 B |
| `LensSpecifics_XCD90.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 428 B | 568 B | +140 B |
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 982.6 KB | 604.6 KB | -378.0 KB |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.5 KB | 14.1 KB | +2.6 KB |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 2 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 4 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

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

镜头固件对比: 3 变更 · 2 新增 · 0 移除 · 0 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `XCD25 · data` | — → — | — → 128 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `XCD90 · data` | — → — | — → 128 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `MAIN · main` | — → — | 982.6 KB → 604.6 KB | 96.9% | 23 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD25 · specifics` | — → — | 428 B → 568 B | 74.48% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD90 · specifics` | — → — | 428 B → 568 B | 74.48% | 2 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |

**`MAIN · main`** 变化区域（前 10 段）:

- off `0x60014c05` len `31`
- off `0x60014c48` len `39`
- off `0x60015008` len `19`
- off `0x6001502c` len `147`
- off `0x600150d0` len `99`
- off `0x6001514c` len `299`
- off `0x60015420` len `79`
- off `0x60015544` len `18`
- off `0x60015578` len `31`
- off `0x6001566c` len `151`

**`XCD25 · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x28` len `152`

**`XCD90 · specifics`** 变化区域（前 2 段）:

- off `0x2` len `9`
- off `0x28` len `152`

## Appendix

_无附录内容。_
