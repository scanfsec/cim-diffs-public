# XCD 2,5/38V: 1.9.7 ➜ 1.9.11

> 生成时间: 2026-10-07T06:13:38 · CIM 日期: 2025-07-03 ➜ 2025-09-15 · 条目: 10 ➜ 10 · 源: `XCD-Lens-Firmware-XCD-28P-38V-55V-75P-v1_9_7.cim` ➜ `XCD38V_v1_9_11.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +0/-0/~1；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 1 变更 / 0 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 601.6 KB | 605.6 KB | +4.0 KB |
| `LensData_XCD28P.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensData_XCD38.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensData_XCD55.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensData_XCD75P.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensSpecifics_XCD28P.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 708 B | 708 B | +0 B |
| `LensSpecifics_XCD38.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 708 B | 708 B | +0 B |
| `LensSpecifics_XCD55.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 708 B | 708 B | +0 B |
| `LensSpecifics_XCD75P.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 708 B | 708 B | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.1 KB | 15.1 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 1 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 9

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

镜头固件对比: 1 变更 · 0 新增 · 0 移除 · 8 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `MAIN · main` | — → — | 601.6 KB → 605.6 KB | 89.9% | 92 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD28P · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD28P · specifics` | — → — | 708 B → 708 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD38 · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD38 · specifics` | — → — | 708 B → 708 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD55 · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD55 · specifics` | — → — | 708 B → 708 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD75P · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD75P · specifics` | — → — | 708 B → 708 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |

**`MAIN · main`** 变化区域（前 10 段）:

- off `0x60014c05` len `31`
- off `0x60014c48` len `40`
- off `0x60015008` len `18`
- off `0x6001502c` len `146`
- off `0x600150d0` len `98`
- off `0x6001514c` len `298`
- off `0x60015420` len `78`
- off `0x60015544` len `17`
- off `0x60015578` len `30`
- off `0x6001566c` len `149`

## Appendix

_无附录内容。_
