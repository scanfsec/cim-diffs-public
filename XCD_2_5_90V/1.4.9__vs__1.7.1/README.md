# XCD 2,5/90V: 1.4.9 ➜ 1.7.1

> 生成时间: 2026-10-07T06:19:22 · CIM 日期: 2023-11-10 ➜ 2024-09-20 · 条目: 3 ➜ 4 · 源: `XCD90V_v1.4.9.cim` ➜ `XCD-Lens-Firmware-XCD-25V-90V-v1_7_1.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +2/-1/~2；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 1 变更 / 2 新增 / 1 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `LensSpecifics_XCD25.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 428 B | +428 B |
| `LensSpecifics_XCD90.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 428 B | +428 B |
| `LensSpecifics_XCD90_II.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 106 B | — | -106 B |
| `artifact.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 796.1 KB | 982.6 KB | +186.5 KB |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.3 KB | 11.5 KB | +205 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 2 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 1 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 2 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

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

镜头固件对比: 1 变更 · 2 新增 · 1 移除 · 0 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `XCD25 · specifics` | — → — | — → 428 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `XCD90 · specifics` | — → — | — → 428 B | — | — | ![NEW](https://img.shields.io/badge/-NEW-green) |
| `XCD90_II · specifics` | — → — | 106 B → — | — | — | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) |
| `MAIN · main` | — → — | 796.1 KB → 982.6 KB | 96.92% | 16 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |

**`MAIN · main`** 变化区域（前 10 段）:

- off `0x60014c05` len `31`
- off `0x60014c48` len `40`
- off `0x60015000` len `26`
- off `0x6001502c` len `657`
- off `0x60015400` len `412`
- off `0x6001565c` len `224`
- off `0x60015c00` len `2`
- off `0x60015c64` len `26`
- off `0x60015c9c` len `2314`
- off `0x600165b6` len `1`

## Appendix

_无附录内容。_
