# XCD 2,5/90V: 1.9.7 ➜ 1.9.12

> 生成时间: 2026-10-07T06:19:23 · CIM 日期: 2025-07-03 ➜ 2025-11-12 · 条目: 6 ➜ 6 · 源: `XCD-Lens-Firmware-XCD-25V-90V-v1_9_7.cim` ➜ `XCD90V_v1_9_12.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +0/-0/~1；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 1 变更 / 0 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 604.6 KB | 609.2 KB | +4.6 KB |
| `LensData_XCD25.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensData_XCD90.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensSpecifics_XCD25.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 568 B | 568 B | +0 B |
| `LensSpecifics_XCD90.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 568 B | 568 B | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.1 KB | 14.1 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 1 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 5

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

镜头固件对比: 1 变更 · 0 新增 · 0 移除 · 4 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `MAIN · main` | — → — | 604.6 KB → 609.2 KB | 90.59% | 100 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD25 · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD25 · specifics` | — → — | 568 B → 568 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD90 · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD90 · specifics` | — → — | 568 B → 568 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |

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
- off `0x6001566c` len `150`

## Appendix

_无附录内容。_
