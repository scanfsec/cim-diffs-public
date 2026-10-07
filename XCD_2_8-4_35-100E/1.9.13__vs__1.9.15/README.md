# XCD 2,8-4/35-100E: 1.9.13 ➜ 1.9.15

> 生成时间: 2026-10-07T06:17:10 · CIM 日期: 2025-11-14 ➜ 2025-12-05 · 条目: 4 ➜ 4 · 源: `XCD35-100E_v1_9_13.cim` ➜ `XCD35-100E_v1_9_15.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +0/-0/~1；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 1 变更 / 0 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 678.0 KB | 675.7 KB | -2.4 KB |
| `LensData_XCD35-100.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 128 B | 128 B | +0 B |
| `LensSpecifics_XCD35-100.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.0 KB | 6.0 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 1 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 3

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

镜头固件对比: 1 变更 · 0 新增 · 0 移除 · 2 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `MAIN · main` | — → — | 678.0 KB → 675.7 KB | 87.99% | 141 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |
| `XCD35-100 · data` | — → — | 128 B → 128 B | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |
| `XCD35-100 · specifics` | — → — | 6.0 KB → 6.0 KB | 0.0% | 0 | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) |

**`MAIN · main`** 变化区域（前 10 段）:

- off `0x60015005` len `31`
- off `0x60015048` len `39`
- off `0x60015408` len `18`
- off `0x6001542c` len `146`
- off `0x600154d0` len `98`
- off `0x6001554c` len `298`
- off `0x60015820` len `78`
- off `0x60015944` len `2`
- off `0x60015978` len `30`
- off `0x60015a6c` len `150`

## Appendix

_无附录内容。_
