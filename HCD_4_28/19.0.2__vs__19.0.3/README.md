# HCD 4/28: 19.0.2 ➜ 19.0.3

> 生成时间: 2026-10-07T06:01:05 · CIM 日期: 2017-12-14 ➜ 2018-04-09 · 条目: 2 ➜ 2 · 源: `HC-Lens_v19_0_2.cim` ➜ `HC-Lens_v19_0_3.cim`

## Summary

文件树 +0/-0/~0；CIM 条目 +1/-1/~1；OTA 镜像 ~0 变更 / 0 未变；符号 +0/-0 funcs, +0/-0 objs；新增字符串 0 条；镜头固件 1 变更 / 0 新增 / 0 移除。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `HC_FW_1600414_19_0_3.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 204.2 KB | +204.2 KB |
| `HC_FW_1600414_19_0_2.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 204.8 KB | — | -204.8 KB |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.6 KB | 9.9 KB | +296 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 1 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 1 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 1 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

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

镜头固件对比: 1 变更 · 0 新增 · 0 移除 · 0 未变。

| Model | FW Old→New | Size | %Bytes Changed | Regions | Status |
|---|---|---|---|---|---|
| `HC_FW · main` | 19.0.2 → 19.0.3 | 204.8 KB → 204.2 KB | 95.49% | 14 | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) |

**`HC_FW · main`** 变化区域（前 10 段）:

- off `0x8000840` len `42`
- off `0x8000888` len `2`
- off `0x800089c` len `146`
- off `0x80009f7` len `31`
- off `0x8000a26` len `4`
- off `0x8000a40` len `4`
- off `0x8000a54` len `2`
- off `0x8000a78` len `18`
- off `0x8000b0c` len `30`
- off `0x8000bde` len `44998`

## Appendix

_无附录内容。_
