# X2D 100C: 3.2.1 ➜ 3.2.2

> 生成时间: 2026-10-07T06:09:07 · CIM 日期: 2024-06-18 ➜ 2024-08-22 · 条目: 8 ➜ 8 · 源: `X2D_100C_v3_2_1.cim` ➜ `X2D_100C_v3_2_2.cim`

## Summary

文件树 +0/-0/~73；CIM 条目 +0/-0/~5；OTA 镜像 ~7 变更 / 0 未变；符号 +317/-107 funcs, +50/-8 objs；新增字符串 156 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B |
| `exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 413.6 KB | 413.6 KB | +0 B |
| `exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +8 B |
| `exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 162.1 MB | 161.9 MB | -187.8 KB |
| `ec2107_cpld.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B |
| `hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.5 KB | 13.5 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.1 KB | 7.1 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 5 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 3

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 544.0 KB | 544.0 KB | +0 B |
| `gimbal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 355.3 KB | 355.3 KB | +0 B |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 19.0 MB | 19.0 MB | +0 B |
| `scp.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.4 KB | 89.4 KB | +0 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 512.0 MB | 512.0 MB | +0 B |
| `tos.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 449.7 KB | 449.7 KB | +0 B |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.3 MB | 45.3 MB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 7 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `model` | 0 | 0 | 23 | 0 | 0 |
| `bin` | 0 | 0 | 19 | 325 | 0 |
| `etc` | 0 | 0 | 14 | 165 | 0 |
| `lib64` | 0 | 0 | 9 | 279 | 0 |
| `(root)` | 0 | 0 | 3 | 2 | 0 |
| `firmware` | 0 | 0 | 3 | 11 | 0 |
| `ta` | 0 | 0 | 2 | 0 | 0 |
| `lib` | 0 | 0 | 0 | 74 | 0 |
| `product` | 0 | 0 | 0 | 1 | 0 |
| `usr` | 0 | 0 | 0 | 14 | 0 |
| `xbin` | 0 | 0 | 0 | 10 | 0 |

明细 954 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+317 / −107** functions, **+50 / −8** objects（28 个变更 ELF）。

### `/bin/camera-gui`

+92 / −64 functions · +3 / −0 objects

**New functions (92)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x32d618 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x32d978 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x32d980 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x32d980 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x32d990 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x32d9a8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x32da58 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x32da68 | 12 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_browseview_ColorPickerMetadataOverlay_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x37ec38 | 132 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_browseview_ColorPickerMetadataOverlay_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x382288 | 388 |
| `_ZN21QmlCacheGeneratedCode32_app_qml_components_Checkbox_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3bac38 | 44 |
| `_ZZNK21QmlCacheGeneratedCode32_app_qml_components_Checkbox_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3baef8 | 236 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_components_PageIndicator_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x409af0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_components_PageIndicator_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x40aa40 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x414560 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x415008 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_components_StatusRow_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x424008 | 256 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_components_TemperatureStatus_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x428da0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_components_TemperatureStatus_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x429520 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_components_TextValueRow_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x439c78 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_components_TextValueRow_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x43a1f0 | 236 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_WifiStatus_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4458b0 | 300 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x446128 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x446340 | 236 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_buttons_Button_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x448520 | 412 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_buttons_Button_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4487e0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_buttons_Button_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x449ea8 | 244 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml4$_208__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x44c5b0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x44de78 | 244 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_IconButton_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x451318 | 44 |
| `_ZZNK21QmlCacheGeneratedCode42_app_qml_components_buttons_IconButton_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4520e0 | 244 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_controlscreen_ExposureAdjustIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x464540 | 44 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_controlscreen_ExposureAdjustIndicator_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x464dd0 | 240 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_error_ErrorNonAck_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x471fe8 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_error_ErrorUsbConnected_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x475da8 | 256 |
| `_ZN21QmlCacheGeneratedCode45_app_qml_exposescreen_IntervalTimerScreen_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x486f20 | 252 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_AFIndicator_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48a6c0 | 264 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_EvfBrightnessSelector_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x490148 | 44 |
| `_ZZNK21QmlCacheGeneratedCode43_app_qml_liveview_EvfBrightnessSelector_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4904e0 | 232 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_348__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x496d28 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x499748 | 260 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_liveview_FocusIndicator_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49b218 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_liveview_FocusIndicator_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x49b5e8 | 244 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_liveview_FocusPointTapHandler_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49c758 | 240 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml4$_188__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b3e80 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4bc148 | 260 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_MFAssistDistanceScale_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4c9db0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode43_app_qml_liveview_MFAssistDistanceScale_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4ca9d0 | 240 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_OverlayListView_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d0020 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d33c0 | 44 |

<details><summary>… 另 42 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml4$_13clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d4990 | 244 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d5de0 | 44 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d5ea0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d6ee8 | 256 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d7698 | 240 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_mainmenu_LicenseView_qml4$_178__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ede88 | 256 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_mainmenu_MenuBoolSelector_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f31e0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_mainmenu_MenuBoolSelector_qml4$_13clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4f3998 | 228 |
| `_ZN21QmlCacheGeneratedCode55_app_qml_mainmenu_delegates_ListValueSwitchDelegate_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x50f348 | 240 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_StorageInfoDelegate_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x514490 | 44 |
| `_ZZNK21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_StorageInfoDelegate_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x515528 | 236 |
| `_ZZNK21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_StorageInfoDelegate_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x516518 | 224 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SwitchDelegate_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x518bd8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SwitchDelegate_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x519a20 | 244 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextActionDelegate_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51a178 | 44 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextActionDelegate_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x51aa20 | 224 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextButtonDelegate_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51b4e8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextButtonDelegate_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x51bd58 | 232 |
| `_ZZNK21QmlCacheGeneratedCode44_app_qml_mainmenu_delegates_TextDelegate_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x51d250 | 232 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_ValueSwitchDelegate_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51d980 | 256 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_ValueSwitchDelegate_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51dc00 | 256 |
| `_ZN21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5219d8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5229c8 | 244 |
| `_ZN21QmlCacheGeneratedCode22_app_qml_MainModel_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52b790 | 252 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x537f58 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x53a4a0 | 388 |
| `_ZN21QmlCacheGeneratedCode27_app_qml_popups_Popover_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x53ff90 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x548b00 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54ad60 | 236 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_popups_PopoverExposureAdjust_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x54ee90 | 320 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x558580 | 256 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_788__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55ade8 | 264 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5625c8 | 44 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x562c18 | 44 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_368__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x562e88 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x563fa8 | 244 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x565ce0 | 244 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_36clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x566d00 | 260 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x10d7910 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x10d79a8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x10d79b0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x10d7b30 | 200 |

</details>

**Removed functions (64)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3ebb90 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3ecc20 | 240 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_components_PageListView_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x40d9d8 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_components_Scrollbar_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x41e5d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_components_Scrollbar_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x41fab8 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_components_TextValueRow_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4397d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_components_TextValueRow_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x43a550 | 232 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_TimerIndicator_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x43b110 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x445b08 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x445b38 | 252 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x445e20 | 236 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_controlscreen_ExposureAdjustIndicator_qml4$_178__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x463f00 | 256 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x469558 | 44 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x469588 | 244 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x469b58 | 484 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x46cf00 | 96 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x46d918 | 500 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_error_ErrorNonAck_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x471ac0 | 256 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_error_ErrorNonAck_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4720c8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_error_ErrorNonAck_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x474100 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_error_ErrorUsbConnected_qml4$_588__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x476590 | 264 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeIconText_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x47df48 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeIconText_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x47e920 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_exposescreen_ExposeScreen_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x47f6b0 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x496278 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x496720 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_14clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x497ed0 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x498930 | 260 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_MFAssistDistanceScale_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4c96b8 | 240 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_OverlayListView_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4ce4f0 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2a40 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d2ec0 | 236 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d4ea8 | 468 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d5080 | 1064 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d5bd8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d6490 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_liveview_SubFaceIndicator_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dd630 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_liveview_SubFaceIndicator_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4dd690 | 240 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_ZoomIndicator_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4de3f8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_liveview_ZoomIndicator_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4de9a0 | 244 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e30a8 | 256 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_mainmenu_ListSelectorSettings_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ef470 | 264 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SliderDelegate_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x510810 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SliderDelegate_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5125a8 | 232 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SwitchDelegate_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x518df0 | 256 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_popups_PopoverCombinationLock_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x524b68 | 44 |
| `_ZZNK21QmlCacheGeneratedCode51_app_qml_mainmenu_popups_PopoverCombinationLock_qml4$_14clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x525a48 | 260 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52f470 | 44 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml4$_398__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x530448 | 132 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x531988 | 244 |

<details><summary>… 另 14 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml4$_39clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x533fb0 | 396 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_upgrade_UpgradeConfirm_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x535d20 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_upgrade_UpgradeConfirm_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x536908 | 240 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_168__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x537dd8 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x53a918 | 388 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_popups_PopoverBusy_qml4$_358__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x544010 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_popups_PopoverBusy_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x546e50 | 240 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_328__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x548fc0 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_448__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x549a00 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_32clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54c788 | 244 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54db50 | 260 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x567890 | 252 |
| `_ZN21QmlCacheGeneratedCode37_confirmtest_qml_confirmtest_main_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xacfc48 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_confirmtest_qml_confirmtest_main_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0xad06b8 | 240 |

</details>

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x1d1fc77 | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x21a06d0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x21cbd00 | 4 |

### `/bin/odindb-send`

+48 / −27 functions · +5 / −2 objects

**New functions (48)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x44920 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x44928 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x44928 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x44938 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x44950 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x44968 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x44978 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x729a8 | 12 |
| `_ZN19StorageProxyWrapper22format_extendedWrapperERK5QListI7QStringE` | 0xa7ea8 | 1212 |
| `_ZN15OdinDbSendUtils21convertStringToBitsetIN9HblmTypes15E_FormatOptionsELm2EEEbRK7QStringRT_` | 0xaf670 | 1876 |
| `_ZN15OdinDbSendUtils19convertStringToEnumIN9HblmTypes15E_FormatOptionsEEEbRK7QStringRT_` | 0xb3100 | 492 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper22format_extendedWrapperERK5QListI7QStringEE3$_3Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb32f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper31notify_new_exposure_itemWrapperERK5QListI7QStringEE3$_4Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb3320 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper13removeWrapperERK5QListI7QStringEE3$_5Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb3350 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper22remove_extendedWrapperERK5QListI7QStringEE3$_6Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb3380 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper19set_metadataWrapperERK5QListI7QStringEE3$_7Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb36d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb3700 | 504 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE3$_9Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb38f8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_12Li3ENS_4ListIJS4_RK4QMapIS2_8QVariantEN9HblmTypes21E_StorageUpdateReasonEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb50a8 | 2156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_13Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb5918 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_15Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb60c0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_16Li1ENS_4ListIJN9HblmTypes20E_CaptureStorageModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb64a8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_17Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb6888 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_19Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb7030 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_20Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb7418 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_22Li1ENS_4ListIJN9HblmTypes13E_MediaStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb7f68 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_25Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8bd0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_26Li1ENS_4ListIJN9HblmTypes15E_StorageDeviceEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9298 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_27Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9740 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_28Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9b00 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_29Li1ENS_4ListIJN9HblmTypes13E_StorageModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xba1c8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_30Li1ENS_4ListIJN9HblmTypes15E_StorageStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xba670 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_31Li1ENS_4ListIJPK15VariantMapModelEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbaa50 | 960 |
| `_ZN12StorageProxy29format_extended_activeChangedEb` | 0x19df00 | 100 |
| `_ZNK16StorageProxyDbus22format_extended_activeEv` | 0x1a7de8 | 20 |
| `_ZN16StorageProxyDbus17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsE` | 0x1a7ed8 | 20 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1abf40 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x1abfd8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x1abfe0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x1ac160 | 200 |
| `_ZN16StorageProxyDbus15format_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsEiP7QObject` | 0x1d3af0 | 788 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15format_extendedEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0x1d8e98 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12get_metadataERK7QStringN9HblmTypes17E_MetadataOptionsEiP7QObjectE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0x1d8ed8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus24notify_new_exposure_itemERK4QMapI7QString8QVariantEjN9HblmTypes14E_ExposureItemES7_iP7QObjectE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0x1d8f18 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus6removeERK7QStringiP7QObjectE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0x1d8f58 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15remove_extendedERK5QListI7QStringEiP7QObjectE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0x1d8f98 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus22reset_image_seq_numberEiP7QObjectE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1d8fd8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12set_metadataERK7QStringRK4QMapIS2_8QVariantEiP7QObjectE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0x1d9018 | 64 |

**Removed functions (27)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper31notify_new_exposure_itemWrapperERK5QListI7QStringEE3$_3Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb1ab0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper13removeWrapperERK5QListI7QStringEE3$_4Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb1ae0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper22remove_extendedWrapperERK5QListI7QStringEE3$_5Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb1b10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper19set_metadataWrapperERK5QListI7QStringEE3$_6Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb1e60 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb1e90 | 504 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE3$_8Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb2088 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE3$_9Li3ENS_4ListIJS4_RK4QMapIS2_8QVariantEN9HblmTypes21E_StorageUpdateReasonEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb2758 | 2156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_12Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb40a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_13Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb4468 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_15Li1ENS_4ListIJN9HblmTypes20E_CaptureStorageModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb4c38 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_16Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb5018 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_17Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb53d8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_19Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb5ba8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_20Li1ENS_4ListIJN9HblmTypes13E_MediaStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb6250 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_22Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb6ba0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_25Li1ENS_4ListIJN9HblmTypes15E_StorageDeviceEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb7a28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_26Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb7ed0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_27Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8290 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_28Li1ENS_4ListIJN9HblmTypes13E_StorageModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8958 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_29Li1ENS_4ListIJN9HblmTypes15E_StorageStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8e00 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN19StorageProxyWrapper24registerSignalSubscriberERK7QStringE4$_30Li1ENS_4ListIJPK15VariantMapModelEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb91e0 | 960 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12get_metadataERK7QStringN9HblmTypes17E_MetadataOptionsEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0x1d6f08 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus24notify_new_exposure_itemERK4QMapI7QString8QVariantEjN9HblmTypes14E_ExposureItemES7_iP7QObjectE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0x1d6f48 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus6removeERK7QStringiP7QObjectE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0x1d6f88 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15remove_extendedERK5QListI7QStringEiP7QObjectE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0x1d6fc8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus22reset_image_seq_numberEiP7QObjectE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1d7008 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12set_metadataERK7QStringRK4QMapIS2_8QVariantEiP7QObjectE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0x1d7048 | 64 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x275e87 | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IRK4QMapISB_8QVariantES9_EENS3_IKiS9_EESA_SE_SK_SM_SA_SE_SK_SM_SA_SE_NS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_SE_SQ_SK_SA_SA_NS3_IKNSN_15E_StorageDeviceES9_EESA_ST_NS3_IKNSN_15E_FormatOptionsES9_EESA_SE_SQ_SA_SK_NS3_IKjS9_EENS3_IKNSN_14E_ExposureItemES9_EESK_SA_SE_SA_NS3_IRK5QListISB_ES9_EESA_SA_SE_SK_EE` | 0x2f2358 | 336 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IbS6_EES8_NS3_IN9HblmTypes20E_CaptureStorageModeES6_EENS3_IjS6_EES8_S8_SC_NS3_INS9_13E_MediaStatusES6_EESE_NS3_I7QStringS6_EESG_SG_NS3_INS9_15E_StorageDeviceES6_EESC_SG_NS3_INS9_13E_StorageModeES6_EENS3_INS9_15E_StorageStatusES6_EENS3_IP15VariantMapModelS6_EES8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_NS3_I12StorageProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IRKSF_SS_EENS3_IRK4QMapISF_8QVariantESS_EENS3_IKNS9_21E_StorageUpdateReasonESS_EEST_SW_S12_S15_ST_SW_S12_S15_ST_NS3_IiSS_EEST_NS3_IbSS_EEST_S17_ST_NS3_ISA_SS_EEST_NS3_IjSS_EEST_S17_ST_S17_ST_S19_ST_NS3_ISD_SS_EEST_S1A_ST_SW_ST_SW_ST_SW_ST_NS3_ISH_SS_EEST_S19_ST_SW_ST_NS3_ISJ_SS_EEST_NS3_ISL_SS_EEST_NS3_IPKSN_SS_EEST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_EE` | 0x2f53a8 | 832 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x303ab0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x3075ec | 4 |

**Removed objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IRK4QMapISB_8QVariantES9_EENS3_IKiS9_EESA_SE_SK_SM_SA_SE_SK_SM_SA_SE_NS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_SE_SQ_SK_SA_SA_NS3_IKNSN_15E_StorageDeviceES9_EESA_SE_SQ_SA_SK_NS3_IKjS9_EENS3_IKNSN_14E_ExposureItemES9_EESK_SA_SE_SA_NS3_IRK5QListISB_ES9_EESA_SA_SE_SK_EE` | 0x2f23c8 | 312 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IbS6_EES8_NS3_IN9HblmTypes20E_CaptureStorageModeES6_EENS3_IjS6_EES8_S8_SC_NS3_INS9_13E_MediaStatusES6_EESE_NS3_I7QStringS6_EESG_SG_NS3_INS9_15E_StorageDeviceES6_EESC_SG_NS3_INS9_13E_StorageModeES6_EENS3_INS9_15E_StorageStatusES6_EENS3_IP15VariantMapModelS6_EES8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_NS3_I12StorageProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IRKSF_SS_EENS3_IRK4QMapISF_8QVariantESS_EENS3_IKNS9_21E_StorageUpdateReasonESS_EEST_SW_S12_S15_ST_SW_S12_S15_ST_NS3_IiSS_EEST_NS3_IbSS_EEST_S17_ST_NS3_ISA_SS_EEST_NS3_IjSS_EEST_S17_ST_S17_ST_S19_ST_NS3_ISD_SS_EEST_S1A_ST_SW_ST_SW_ST_SW_ST_NS3_ISH_SS_EEST_S19_ST_SW_ST_NS3_ISJ_SS_EEST_NS3_ISL_SS_EEST_NS3_IPKSN_SS_EEST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_EE` | 0x2f5400 | 808 |

### `/bin/camera-storage`

+28 / −9 functions · +5 / −2 objects

**New functions (28)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x57050 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x58178 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x58180 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x58180 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x58190 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x581a8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x58258 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x58268 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x590c0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x59158 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x59160 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x592e0 | 200 |
| `_ZN14StorageService17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsERK12QDBusMessage` | 0xb4860 | 3568 |
| `_ZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsERK14QSharedPointerI19MessageNotificationE` | 0xb5650 | 1788 |
| `_ZN14StorageService22onFormatDeviceFinishedEN9HblmTypes14E_ReturnStatusENS0_15E_FormatOptionsE` | 0xb5d50 | 516 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK12QDBusMessageE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbaa10 | 168 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK12QDBusMessageE4$_12Li1ENS_4ListIJNS2_14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbaab8 | 188 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK12QDBusMessageE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbab78 | 544 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK14QSharedPointerI19MessageNotificationEE4$_14Li1ENS_4ListIJNS2_14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbad98 | 52 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK14QSharedPointerI19MessageNotificationEE4$_15Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbadd0 | 312 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK14QSharedPointerI19MessageNotificationEENK4$_15clEvEUlNS2_14E_ReturnStatusEE_Li1ENS_4ListIJSB_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbaf08 | 52 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK14QSharedPointerI19MessageNotificationEE4$_16Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbaf40 | 36 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsERK14QSharedPointerI19MessageNotificationEE4$_17Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xbaf68 | 132 |
| `_ZN13StorageObject15format_extendedEiiRK12QDBusMessage` | 0xdfb38 | 12 |
| `_ZN7DcfMain19resetImageSeqNumberEv` | 0xe1d98 | 120 |
| `_ZN7DcfMain15resetSeqNumbersEv` | 0xe1e10 | 136 |
| `_ZN3Dcf14resetFileIndexEv` | 0xe8398 | 924 |
| `_ZN3Dcf12resetIndexesEv` | 0xe8738 | 248 |

**Removed functions (9)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceERK14QSharedPointerI19MessageNotificationE` | 0xb4da8 | 1272 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9cd0 | 168 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_12Li1ENS_4ListIJNS2_14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9d78 | 184 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9e30 | 544 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceERK14QSharedPointerI19MessageNotificationEE4$_14Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xba050 | 164 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceERK14QSharedPointerI19MessageNotificationEE4$_15Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xba0f8 | 36 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceERK14QSharedPointerI19MessageNotificationEE4$_16Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xba120 | 132 |
| `_ZN7DcfMain19resetImageSeqNumberER7QString` | 0xe0f28 | 64 |
| `_ZN3Dcf12resetIndexesER7QString` | 0xe7468 | 848 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x1c67ae | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_135qt_meta_stringdata_StorageService_tEJN9QtPrivate20TypeAndForceCompleteI14StorageServiceNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IRK7QStringS9_EESE_SE_NS3_IyS9_EESA_NS3_IN9HblmTypes14E_ReturnStatusES9_EENS3_INSG_15E_FormatOptionsES9_EESA_SE_NS3_INSG_13E_ResolutionsES9_EENS3_IRK5QRectS9_EENS3_IP11LocalSocketS9_EESA_SA_EE` | 0x238700 | 136 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_134qt_meta_stringdata_StorageObject_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IbS6_EES8_S7_NS3_IjS6_EES8_S8_S9_S7_S7_NS3_I7QStringS6_EESB_SB_S7_S9_SB_S7_S7_NS3_I5QListI4QMapISA_8QVariantEES6_EENS3_I13StorageObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IRKSA_SK_EENS3_IRKSF_SK_EENS3_IKiSK_EESL_SO_SR_ST_SL_SO_SR_ST_SL_ST_SL_NS3_IKbSK_EESL_SV_SL_NS3_IKN9HblmTypes20E_CaptureStorageModeESK_EESL_NS3_IKjSK_EESL_SV_SL_SV_SL_S11_SL_NS3_IKNSW_13E_MediaStatusESK_EESL_S14_SL_SO_SL_SO_SL_SO_SL_NS3_IKNSW_15E_StorageDeviceESK_EESL_S11_SL_SO_SL_NS3_IKNSW_13E_StorageModeESK_EESL_NS3_IKNSW_15E_StorageStatusESK_EESL_NS3_IKSG_SK_EESL_SO_SR_NS3_IKNSW_21E_StorageUpdateReasonESK_EESL_SO_SR_S1I_SL_SO_SR_S1I_NS3_ISG_SK_EESO_ST_NS3_IRK12QDBusMessageSK_EESL_SO_ST_SR_S1N_SL_S1N_SL_ST_S1N_SL_ST_ST_S1N_NS3_ISF_SK_EESO_ST_S1N_SL_SR_S11_ST_SR_S1N_SL_SO_S1N_SL_NS3_IRKSC_ISA_ESK_EES1N_NS3_ISA_SK_EES1N_SL_SO_SR_S1N_EE` | 0x23a880 | 976 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x250cb8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x256b74 | 4 |

**Removed objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_135qt_meta_stringdata_StorageService_tEJN9QtPrivate20TypeAndForceCompleteI14StorageServiceNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IRK7QStringS9_EESE_SE_NS3_IyS9_EESA_SE_NS3_IN9HblmTypes13E_ResolutionsES9_EENS3_IRK5QRectS9_EENS3_IP11LocalSocketS9_EESA_SA_EE` | 0x238758 | 112 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_134qt_meta_stringdata_StorageObject_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IbS6_EES8_S7_NS3_IjS6_EES8_S8_S9_S7_S7_NS3_I7QStringS6_EESB_SB_S7_S9_SB_S7_S7_NS3_I5QListI4QMapISA_8QVariantEES6_EENS3_I13StorageObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IRKSA_SK_EENS3_IRKSF_SK_EENS3_IKiSK_EESL_SO_SR_ST_SL_SO_SR_ST_SL_ST_SL_NS3_IKbSK_EESL_SV_SL_NS3_IKN9HblmTypes20E_CaptureStorageModeESK_EESL_NS3_IKjSK_EESL_SV_SL_SV_SL_S11_SL_NS3_IKNSW_13E_MediaStatusESK_EESL_S14_SL_SO_SL_SO_SL_SO_SL_NS3_IKNSW_15E_StorageDeviceESK_EESL_S11_SL_SO_SL_NS3_IKNSW_13E_StorageModeESK_EESL_NS3_IKNSW_15E_StorageStatusESK_EESL_NS3_IKSG_SK_EESL_SO_SR_NS3_IKNSW_21E_StorageUpdateReasonESK_EESL_SO_SR_S1I_SL_SO_SR_S1I_NS3_ISG_SK_EESO_ST_NS3_IRK12QDBusMessageSK_EESL_SO_ST_SR_S1N_SL_S1N_SL_ST_S1N_NS3_ISF_SK_EESO_ST_S1N_SL_SR_S11_ST_SR_S1N_SL_SO_S1N_SL_NS3_IRKSC_ISA_ESK_EES1N_NS3_ISA_SK_EES1N_SL_SO_SR_S1N_EE` | 0x23a8b0 | 944 |

### `/bin/msg2dbus`

+23 / −6 functions · +5 / −2 objects

**New functions (23)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x3f1f0 | 12 |
| `_ZN12StorageProxy29format_extended_activeChangedEb` | 0x88970 | 100 |
| `_ZNK16StorageProxyDbus22format_extended_activeEv` | 0x8e530 | 20 |
| `_ZN16StorageProxyDbus17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsE` | 0x8e638 | 20 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x90650 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x90658 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x90658 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x90668 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x90680 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x90730 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x90740 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x94aa8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x94b40 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x94b48 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x94cc8 | 200 |
| `_ZN16StorageProxyDbus15format_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsEiP7QObject` | 0xb47f8 | 788 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15format_extendedEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0xba388 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12get_metadataERK7QStringN9HblmTypes17E_MetadataOptionsEiP7QObjectE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0xba3c8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus24notify_new_exposure_itemERK4QMapI7QString8QVariantEjN9HblmTypes14E_ExposureItemES7_iP7QObjectE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0xba740 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus6removeERK7QStringiP7QObjectE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0xba780 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15remove_extendedERK5QListI7QStringEiP7QObjectE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0xba7c0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus22reset_image_seq_numberEiP7QObjectE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xba800 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12set_metadataERK7QStringRK4QMapIS2_8QVariantEiP7QObjectE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0xbab60 | 64 |

**Removed functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12get_metadataERK7QStringN9HblmTypes17E_MetadataOptionsEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0xb9a88 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus24notify_new_exposure_itemERK4QMapI7QString8QVariantEjN9HblmTypes14E_ExposureItemES7_iP7QObjectE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0xb9e00 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus6removeERK7QStringiP7QObjectE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0xb9e40 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15remove_extendedERK5QListI7QStringEiP7QObjectE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0xb9e80 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus22reset_image_seq_numberEiP7QObjectE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xb9ec0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12set_metadataERK7QStringRK4QMapIS2_8QVariantEiP7QObjectE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0xba220 | 64 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x16c9b7 | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IRK4QMapISB_8QVariantES9_EENS3_IKiS9_EESA_SE_SK_SM_SA_SE_SK_SM_SA_SE_NS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_SE_SQ_SK_SA_SA_NS3_IKNSN_15E_StorageDeviceES9_EESA_ST_NS3_IKNSN_15E_FormatOptionsES9_EESA_SE_SQ_SA_SK_NS3_IKjS9_EENS3_IKNSN_14E_ExposureItemES9_EESK_SA_SE_SA_NS3_IRK5QListISB_ES9_EESA_SA_SE_SK_EE` | 0x1d4670 | 336 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IbS6_EES8_NS3_IN9HblmTypes20E_CaptureStorageModeES6_EENS3_IjS6_EES8_S8_SC_NS3_INS9_13E_MediaStatusES6_EESE_NS3_I7QStringS6_EESG_SG_NS3_INS9_15E_StorageDeviceES6_EESC_SG_NS3_INS9_13E_StorageModeES6_EENS3_INS9_15E_StorageStatusES6_EENS3_IP15VariantMapModelS6_EES8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_NS3_I12StorageProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IRKSF_SS_EENS3_IRK4QMapISF_8QVariantESS_EENS3_IKNS9_21E_StorageUpdateReasonESS_EEST_SW_S12_S15_ST_SW_S12_S15_ST_NS3_IiSS_EEST_NS3_IbSS_EEST_S17_ST_NS3_ISA_SS_EEST_NS3_IjSS_EEST_S17_ST_S17_ST_S19_ST_NS3_ISD_SS_EEST_S1A_ST_SW_ST_SW_ST_SW_ST_NS3_ISH_SS_EEST_S19_ST_SW_ST_NS3_ISJ_SS_EEST_NS3_ISL_SS_EEST_NS3_IPKSN_SS_EEST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_EE` | 0x1d7700 | 832 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x1e1478 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x1e652c | 4 |

**Removed objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IRK4QMapISB_8QVariantES9_EENS3_IKiS9_EESA_SE_SK_SM_SA_SE_SK_SM_SA_SE_NS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_SE_SQ_SK_SA_SA_NS3_IKNSN_15E_StorageDeviceES9_EESA_SE_SQ_SA_SK_NS3_IKjS9_EENS3_IKNSN_14E_ExposureItemES9_EESK_SA_SE_SA_NS3_IRK5QListISB_ES9_EESA_SA_SE_SK_EE` | 0x1d46c8 | 312 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IbS6_EES8_NS3_IN9HblmTypes20E_CaptureStorageModeES6_EENS3_IjS6_EES8_S8_SC_NS3_INS9_13E_MediaStatusES6_EESE_NS3_I7QStringS6_EESG_SG_NS3_INS9_15E_StorageDeviceES6_EESC_SG_NS3_INS9_13E_StorageModeES6_EENS3_INS9_15E_StorageStatusES6_EENS3_IP15VariantMapModelS6_EES8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_NS3_I12StorageProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IRKSF_SS_EENS3_IRK4QMapISF_8QVariantESS_EENS3_IKNS9_21E_StorageUpdateReasonESS_EEST_SW_S12_S15_ST_SW_S12_S15_ST_NS3_IiSS_EEST_NS3_IbSS_EEST_S17_ST_NS3_ISA_SS_EEST_NS3_IjSS_EEST_S17_ST_S17_ST_S19_ST_NS3_ISD_SS_EEST_S1A_ST_SW_ST_SW_ST_SW_ST_NS3_ISH_SS_EEST_S19_ST_SW_ST_NS3_ISJ_SS_EEST_NS3_ISL_SS_EEST_NS3_IPKSN_SS_EEST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_ST_S17_EE` | 0x1d7740 | 808 |

### `/bin/camera-test`

+18 / −1 functions · +5 / −2 objects

**New functions (18)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x46108 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x46c40 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x46c48 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x46c48 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x46c58 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x46c70 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x46d20 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x46d30 | 12 |
| `_ZN12StorageProxy29format_extended_activeChangedEb` | 0xc7290 | 100 |
| `_ZNK16StorageProxyDbus22format_extended_activeEv` | 0xc8ee0 | 20 |
| `_ZN16StorageProxyDbus17doFormat_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsE` | 0xc9280 | 20 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xce408 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xce4a0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0xce4a8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0xce628 | 200 |
| `_ZN16StorageProxyDbus15format_extendedEN9HblmTypes15E_StorageDeviceENS0_15E_FormatOptionsEiP7QObject` | 0xdc6d8 | 788 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15format_extendedEN9HblmTypes15E_StorageDeviceENS2_15E_FormatOptionsEiP7QObjectE3$_1Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES6_PPvPb` | 0xdd980 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus22reset_image_seq_numberEiP7QObjectE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xdd9c0 | 64 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus22reset_image_seq_numberEiP7QObjectE3$_1Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xdcd58 | 64 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x1553df | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_NS3_IKNSF_15E_StorageDeviceES9_EENS3_IKNSF_15E_FormatOptionsES9_EESA_EE` | 0x1b9fd0 | 64 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IN9HblmTypes13E_MediaStatusES6_EENS3_IbS6_EESB_SB_SB_NS3_I12StorageProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IiSE_EESF_NS3_IS9_SE_EESF_NS3_IbSE_EESF_SI_SF_SI_EE` | 0x1ba8f8 | 136 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x1c23d0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x1c7d0c | 4 |

**Removed objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_EE` | 0x1ba030 | 40 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IN9HblmTypes13E_MediaStatusES6_EENS3_IbS6_EESB_SB_NS3_I12StorageProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IiSE_EESF_NS3_IS9_SE_EESF_NS3_IbSE_EESF_SI_EE` | 0x1ba940 | 112 |

### `/bin/camera-expose`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x42a28 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x72108 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x72110 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x72110 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x72120 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x72138 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x721e8 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x721f8 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc5438 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc54d0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0xc54d8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0xc5658 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x15dbea | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x1a3158 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x1a5bb4 | 4 |

### `/bin/camera-service`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0xb7a68 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xb8038 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0xb8040 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0xb8040 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb8050 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb8068 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0xb8118 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0xb8128 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x493878 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x493910 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x493918 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x493a98 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x6c6c38 | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x7cc8b0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x7d5b74 | 4 |

### `/bin/camera-system`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x6a958 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x6a960 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x6a960 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x6a970 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x6a988 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x6a9e0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x6a9f0 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x6aa00 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x2c5390 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x2c5428 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x2c5430 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x2c55b0 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x4866dd | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x5786f0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x580278 | 4 |

### `/bin/camera-upgrade`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2f9a8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x33310 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x33318 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x33318 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33328 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33340 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x333f0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x33400 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xbbfb8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xbc050 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0xbc058 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0xbc1d8 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0xf0c07 | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x132438 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x1364ec | 4 |

### `/bin/hex-writer`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2a758 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x30928 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x30930 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x30930 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x30940 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x30958 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x30a08 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x30a18 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x519b8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x51a50 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x51a58 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x51bd8 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x89389 | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0xe2f50 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0xe55c4 | 4 |

### `/bin/ibistool`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x25898 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x258a0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x258a0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x258b0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x258c8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x25978 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x25988 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x4fb48 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x51ae0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x51b78 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x51b80 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x51d00 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x8f7ae | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0xc0e80 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0xc57c4 | 4 |

### `/bin/imgtool`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x29418 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x2b138 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x2b140 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x2b140 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2b150 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2b168 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x2b218 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x2b228 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x2b770 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x2b808 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x2b810 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x2b990 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x5bc8a | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x802b0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x848f4 | 4 |

### `/bin/phocus`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x59b98 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x5eaa8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x5eab0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x5eab0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x5eac0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x5ead8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x5eb88 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x5eb98 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x156bb0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x156c48 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x156c50 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x156dd0 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x1b59f0 | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0x223da8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0x22ad2c | 4 |

### `/bin/wmstool`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_FormatOptionsEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x27688 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x33b90 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x33b98 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x33b98 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33ba8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33bc0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x33c70 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x33c80 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_FormatOptionsELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x43c30 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x43cc8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEv` | 0x43cd0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_FormatOptionsEEiRK10QByteArray` | 0x43e50 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_FormatOptionsEE4nameE` | 0x71eca | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_FormatOptionsEE8metaTypeE` | 0xa0c50 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_FormatOptionsEE14qt_metatype_idEvE11metatype_id` | 0xa52a4 | 4 |

### `/bin/dji_amt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_blackbox`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sec`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/bin/prodconfig-tool`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libMessageTransport.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libaaa.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libdcam_pp.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libdji_codec_heif.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libduml_frwk.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libduml_orte.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libgip.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/libproxy_nn_client.so`

+0 / −0 functions · +0 / −0 objects

### `/lib64/librcam.so`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **156** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/camera-gui`

````text
*RRi^Hj
?QAbstractListModel*
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
GD8]kf
HblmTypes::E_FormatOptions
LensData*
Ok[JwB4
T! AUh
_%)9hj4
c667c86
ffvKiK
hOJ1Rg
n#hs"K
pLXm5t%
````

### `/bin/camera-storage`

````text
DCIM reset is only supported on internal storage
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
Failed to reset sequence number
HblmTypes::E_FormatOptions
auto StorageService::doFormat_extended(const HblmTypes::E_StorageDevice, const HblmTypes::E_FormatOptions, const QDBusMessage &)::(anonymous class)::operator()() const
c667c86
format_extended
format_options
onFormatDeviceFinished
options
std::optional<QString> Dcf::resetFileIndex()
virtual void StorageService::doFormat_extended(const HblmTypes::E_StorageDevice, const HblmTypes::E_FormatOptions, const QDBusMessage &)
void StorageService::formatDevice(const HblmTypes::E_StorageDevice, const HblmTypes::E_FormatOptions, const QSharedPointer<MessageNotification> &)
void StorageService::onFormatDeviceFinished(HblmTypes::E_ReturnStatus, HblmTypes::E_FormatOptions)
````

### `/bin/odindb-send`

````text
  E_FormatOptions_Max(0x7FFFFFFF)
  E_FormatOptions_None(0x00000000)
  E_FormatOptions_ResetDCIM(0x00000001)
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
HblmTypes::E_FormatOptions format_options // Options of formatting
_in_format_options
c667c86
doFormat_extended
format_extended
format_extended(HblmTypes::E_StorageDevice storage_device, HblmTypes::E_FormatOptions format_options)
format_extended_active
format_extended_activeChanged
````

### `/bin/camera-expose`

````text
  E_FormatOptions_Max(0x7FFFFFFF)
  E_FormatOptions_None(0x00000000)
  E_FormatOptions_ResetDCIM(0x00000001)
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
HblmTypes::E_FormatOptions format_options // Options of formatting
c667c86
format_extended
format_extended(HblmTypes::E_StorageDevice storage_device, HblmTypes::E_FormatOptions format_options)
format_extended_activeChanged
````

### `/bin/hex-writer`

````text
  E_FormatOptions_Max(0x7FFFFFFF)
  E_FormatOptions_None(0x00000000)
  E_FormatOptions_ResetDCIM(0x00000001)
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
HblmTypes::E_FormatOptions format_options // Options of formatting
c667c86
format_extended
format_extended(HblmTypes::E_StorageDevice storage_device, HblmTypes::E_FormatOptions format_options)
format_extended_activeChanged
````

### `/bin/camera-test`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
_in_format_options
_in_storage_device
c667c86
doFormat_extended
format_extended_active
format_extended_activeChanged
````

### `/bin/msg2dbus`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
_in_format_options
c667c86
doFormat_extended
format_extended_active
format_extended_activeChanged
````

### `/bin/camera-service`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
c667c86
````

### `/bin/camera-system`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
c667c86
````

### `/bin/camera-upgrade`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
c667c86
````

### `/bin/phocus`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
c667c86
````

### `/bin/ibistool`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
````

### `/bin/imgtool`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
````

### `/bin/wmstool`

````text
E_FormatOptions
E_FormatOptions_Max
E_FormatOptions_None
E_FormatOptions_ResetDCIM
HblmTypes::E_FormatOptions
````

### `/lib64/libduml_frwk.so`

````text
20:37:40
20:37:42
Aug 22 2024
````

### `/lib64/libduml_orte.so`

````text
20:39:21
Aug 22 2024
orte 0.3.4, compiled: Aug 22 2024 20:39:21
````

### `/bin/dji_amt`

````text
20:39:16
Aug 22 2024
````

### `/bin/dji_blackbox`

````text
20:39:16
Aug 22 2024
````

### `/bin/dji_sys`

````text
20:41:08
Aug 22 2024
````

### `/lib64/libdcam_pp.so`

````text
20:38:32
Aug 22 2024
````

### `/lib64/libgip.so`

````text
AB30RG16NV12NV16YU12YU24IMG4IMG3/system/etc/firmware/
N3GIP10FilterPrivE
````

### `/lib64/libproxy_nn_client.so`

````text
20:41:06
Aug 22 2024
````

### `/bin/prodconfig-tool`

````text
4b00fa84
````

### `/lib64/librcam.so`

````text
4b00fa84
````

### `/bin/dji_sec`

````text
````

### `/lib64/libMessageTransport.so`

````text
````

### `/lib64/libaaa.so`

````text
````

### `/lib64/libdji_codec_heif.so`

````text
````

## Scripts & Config

共 2 个脚本/配置变更, 24 行 unified diff（context=3, 预算上限 2000 行）。

### `/build.prop`

13 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,7 +1,7 @@
 
-ro.vendor.build.date=Tue Jun 18 20:03:50 CST 2024
-ro.vendor.build.date.utc=1718712230
-ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/14160:userdebug/test-keys
+ro.vendor.build.date=Thu Aug 22 20:36:16 CST 2024
+ro.vendor.build.date.utc=1724330176
+ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/15532:userdebug/test-keys
 ro.vendor.build.security_patch=
 ro.vendor.product.cpu.abilist=arm64-v8a
 ro.vendor.product.cpu.abilist32=
````

### `/default.prop`

11 行

````diff
--- a//default.prop
+++ b//default.prop
@@ -4,7 +4,7 @@
 ro.vndk.version=28
 ro.vndk.lite=true
 persist.coredump.enabled=1
-ro.dji.build.version=10.00.19.07
+ro.dji.build.version=10.00.19.10
 persist.dji.storage.exportable=0
 ro.logd.kernel=false
 ro.logd.size.stats=64K
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（954 行）</summary>

| Path | Status | Old Size | New Size | Δ | Tree |
|---|---|---|---|---|---|
| `/bin/adb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 MB | 1.3 MB | +0 B | system |
| `/bin/adbd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 MB | 1.7 MB | +0 B | system |
| `/bin/amt_test_cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/bin/amt_util_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/as7341_link_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/bin/as7341_spectrum_calibrate` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/bin/binderDriverInterfaceTest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 264.5 KB | 264.5 KB | +0 B | system |
| `/bin/binderLibTest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 329.2 KB | 329.2 KB | +0 B | system |
| `/bin/blkid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/blkparse` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 220.0 KB | 220.0 KB | +0 B | system |
| `/bin/blktrace` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 271.2 KB | 271.2 KB | +0 B | system |
| `/bin/boot_control` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395.9 KB | 395.9 KB | +0 B | system |
| `/bin/brdver_ddrtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_hwrev.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_prodtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 386 B | 386 B | +0 B | system |
| `/bin/bsa_server` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 MB | 4.2 MB | +0 B | system |
| `/bin/bt_bsa_app` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 202.5 KB | 202.5 KB | +0 B | system |
| `/bin/btt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 952.4 KB | 952.4 KB | +0 B | system |
| `/bin/bulk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.9 KB | 84.9 KB | +0 B | system |
| `/bin/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.2 KB | 7.2 KB | +0 B | system |
| `/bin/c2d_ut` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.5 KB | 67.5 KB | +0 B | system |
| `/bin/calib-tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/cam_dt_cmdline` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/cam_log_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/camera-expose` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.3 MB | +2.9 KB | system |
| `/bin/camera-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.3 MB | 45.3 MB | +5.4 KB | system |
| `/bin/camera-service` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.8 MB | 10.8 MB | +2.3 KB | system |
| `/bin/camera-storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.3 MB | 3.3 MB | +4.1 KB | system |
| `/bin/camera-system` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 MB | 7.6 MB | +2.4 KB | system |
| `/bin/camera-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.6 MB | 2.6 MB | +3.5 KB | system |
| `/bin/camera-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +2.4 KB | system |
| `/bin/cat_wifi_param.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/check_and_format.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 702 B | 702 B | +0 B | system |
| `/bin/check_secure_debug` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/bin/cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/codec_yuv_generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/collect_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/copy_script_files` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | system |
| `/bin/copy_script_files_self_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.2 KB | 9.2 KB | +0 B | system |
| `/bin/coredump_monitor` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/cpu_dvfs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 KB | 5.8 KB | +0 B | system |
| `/bin/cpu_hotplug.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 844 B | 844 B | +0 B | system |
| `/bin/crash_dump64` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.3 KB | 133.3 KB | +0 B | system |
| `/bin/create_partition.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.7 KB | 4.7 KB | +0 B | system |
| `/bin/data_fsck.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/dbus-daemon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 MB | 1.3 MB | +0 B | system |
| `/bin/dbus-send` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/debug_gui_input.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/debuggerd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/devpd_ctrl.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/dhd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 394.0 KB | 394.0 KB | +0 B | system |
| `/bin/dji_amt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 79.4 KB | 79.4 KB | +0 B | system |
| `/bin/dji_audio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_blackbox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 337.8 KB | 337.8 KB | +0 B | system |
| `/bin/dji_cht` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 MB | 1.0 MB | +0 B | system |
| `/bin/dji_config_dhcp.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/dji_config_net_route.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/bin/dji_config_store` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 391.7 KB | 391.7 KB | +0 B | system |
| `/bin/dji_crashdump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | system |
| `/bin/dji_dcs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_dsp_load` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/dji_fulldump` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_fw_load` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/dji_fw_verify` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/dji_kmsg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_mb_ctrl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_mb_parser` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/dji_ml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 MB | 4.3 MB | +0 B | system |
| `/bin/dji_ml_gtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 MB | 11.0 MB | +0 B | system |
| `/bin/dji_network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 278.5 KB | 278.5 KB | +0 B | system |
| `/bin/dji_production_check_h26x.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | system |
| `/bin/dji_sec` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 72.8 KB | 72.8 KB | +0 B | system |
| `/bin/dji_sn_ops.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 497 B | 497 B | +0 B | system |
| `/bin/dji_sw_uav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.6 KB | 68.6 KB | +0 B | system |
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 876.8 KB | 876.8 KB | +24 B | system |
| `/bin/dji_tombstone.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/dsp_frwk_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 460.8 KB | 460.8 KB | +0 B | system |
| `/bin/duml_googletest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 789.9 KB | 789.9 KB | +0 B | system |
| `/bin/dump_reg.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 718 B | 718 B | +0 B | system |
| `/bin/dumpsys` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
| `/bin/duss_shell` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.1 KB | 68.1 KB | +0 B | system |
| `/bin/e2fsck` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.0 KB | 276.0 KB | +0 B | system |
| `/bin/e2fsdroid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/eagle2_rpmb_inject.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 196 B | 196 B | +0 B | system |
| `/bin/eagle2_state_pro.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 407 B | 407 B | +0 B | system |
| `/bin/evf-diopter` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/exfatfsck` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
| `/bin/fg_pm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/flash_erase` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395.4 KB | 395.4 KB | +0 B | system |
| `/bin/flatc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 391.9 KB | 391.9 KB | +0 B | system |
| `/bin/hex-writer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +2.9 KB | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 786.2 KB | 786.2 KB | +0 B | system |
| `/bin/ibistool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +2.4 KB | system |
| `/bin/imgtool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 879.2 KB | 881.7 KB | +2.4 KB | system |
| `/bin/imx461_bridge_voltages.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | system |
| `/bin/imx461_gpio_enable.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/bin/imx461tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/inject-keypress` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.7 KB | 84.7 KB | +0 B | system |
| `/bin/input-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.6 KB | 131.6 KB | +0 B | system |
| `/bin/iostat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 768.0 KB | 768.0 KB | +0 B | system |
| `/bin/iotop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 625.5 KB | 625.5 KB | +0 B | system |
| `/bin/ip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 326.0 KB | 326.0 KB | +0 B | system |
| `/bin/ip6tables` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 488.8 KB | 488.8 KB | +0 B | system |
| `/bin/iperf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 476.2 KB | 476.2 KB | +0 B | system |
| `/bin/iptables` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 423.7 KB | 423.7 KB | +0 B | system |
| `/bin/iw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273.3 KB | 273.3 KB | +0 B | system |
| `/bin/keyrepo_upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 769 B | 769 B | +0 B | system |
| `/bin/linker64` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 MB | 1.5 MB | +0 B | system |
| `/bin/lmkd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/log_config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 526 B | 526 B | +0 B | system |
| `/bin/logcat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/bin/logd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.3 KB | 198.3 KB | +0 B | system |
| `/bin/logwrapper` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/make_f2fs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.5 KB | 67.5 KB | +0 B | system |
| `/bin/mke2fs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/mkexfatfs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.3 KB | 73.3 KB | +0 B | system |
| `/bin/mmc_stress_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/monkey-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 78.3 KB | 78.3 KB | +0 B | system |
| `/bin/mount_block_ext4.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/mpstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 750.2 KB | 750.2 KB | +0 B | system |
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.7 MB | 2.7 MB | +2.6 KB | system |
| `/bin/nnf_gtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525.3 KB | 525.3 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.6 KB | 133.6 KB | +0 B | system |
| `/bin/odindb-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.0 MB | 4.0 MB | +4.3 KB | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 MB | 8.3 MB | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.1 MB | 3.1 MB | +2.4 KB | system |
| `/bin/phocusv1tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 341.3 KB | 341.3 KB | +0 B | system |
| `/bin/pidstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 867.0 KB | 867.0 KB | +0 B | system |
| `/bin/ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/pinmux` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/bin/proc_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 416.2 KB | 416.2 KB | +0 B | system |
| `/bin/program_nodes.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/bin/reboot` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/returnstatus_defines.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 825 B | 825 B | +0 B | system |
| `/bin/returnstatus_to_string.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 874 B | 874 B | +0 B | system |
| `/bin/rt_tasks_priority_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.3 KB | 9.3 KB | +0 B | system |
| `/bin/rtos_debug` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/sadc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 813.2 KB | 813.2 KB | +0 B | system |
| `/bin/sadf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/sar` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 953.5 KB | 953.5 KB | +0 B | system |
| `/bin/save_lk_log.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/schd-dbg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/schedtool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 186.0 KB | 186.0 KB | +0 B | system |
| `/bin/scp_log.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/secilc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 332.3 KB | 332.3 KB | +0 B | system |
| `/bin/send_fw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.5 KB | 67.5 KB | +0 B | system |
| `/bin/service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/servicemanager` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/setup_product_props.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 805 B | 805 B | +0 B | system |
| `/bin/setup_usb.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/sgdisk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.3 KB | 198.3 KB | +0 B | system |
| `/bin/sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 327.8 KB | 327.8 KB | +0 B | system |
| `/bin/simple_app` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 270.2 KB | 270.2 KB | +0 B | system |
| `/bin/simpleperf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 MB | 3.3 MB | +0 B | system |
| `/bin/sload_f2fs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.2 KB | 133.2 KB | +0 B | system |
| `/bin/sqlite3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 201.8 KB | 201.8 KB | +0 B | system |
| `/bin/ss` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/ss_dsp_manager` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 265.3 KB | 265.3 KB | +0 B | system |
| `/bin/start_blackbox_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | system |
| `/bin/start_dji_camera.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 80 B | 80 B | +0 B | system |
| `/bin/start_dji_system.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/start_hbl_test_mode.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 655 B | 655 B | +0 B | system |
| `/bin/start_touchtest.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 636 B | 636 B | +0 B | system |
| `/bin/start_wifi.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 853 B | 853 B | +0 B | system |
| `/bin/start_wifi_factory.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 196 B | 196 B | +0 B | system |
| `/bin/storage_io` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/storage_tracing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/store-log-encrypted` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/strace` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 MB | 1.0 MB | +0 B | system |
| `/bin/stress_test_mb_benchmark_local` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 78.8 KB | 78.8 KB | +0 B | system |
| `/bin/stress_test_mb_publish_local` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.9 KB | 72.9 KB | +0 B | system |
| `/bin/stress_test_osal_msgq` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/suspend_resume_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | system |
| `/bin/sync_time.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | system |
| `/bin/sysmode_client` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/bin/sysmode_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/system_suspend_resume.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 341 B | 341 B | +0 B | system |
| `/bin/system_suspend_rtc_resume.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 672 B | 672 B | +0 B | system |
| `/bin/tcp_server` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/tee-supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/temperature_get_e2.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 958 B | 958 B | +0 B | system |
| `/bin/test_accelerometer_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/test_ael_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 768 B | 768 B | +0 B | system |
| `/bin/test_af_mf_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 874 B | 874 B | +0 B | system |
| `/bin/test_afd_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 711 B | 711 B | +0 B | system |
| `/bin/test_apu_cap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/test_apu_play` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/test_audio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.9 KB | 67.9 KB | +0 B | system |
| `/bin/test_audio_client` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/test_audio_pa_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 779 B | 779 B | +0 B | system |
| `/bin/test_audio_service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
| `/bin/test_back_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 920 B | 920 B | +0 B | system |
| `/bin/test_back_thumbwheel_press_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 782 B | 782 B | +0 B | system |
| `/bin/test_battery_charger_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_battery_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 722 B | 722 B | +0 B | system |
| `/bin/test_blackbox_size.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_bt_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 984 B | 984 B | +0 B | system |
| `/bin/test_bulk_xfer.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/test_button_backlight_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_cam` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 134.0 KB | 134.0 KB | +0 B | system |
| `/bin/test_cfexpress_card_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 622 B | 622 B | +0 B | system |
| `/bin/test_check_battery_level.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 841 B | 841 B | +0 B | system |
| `/bin/test_check_cpld_version.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/bin/test_check_ibis_calib_status.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_check_versions.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_cnn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/test_common.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | system |
| `/bin/test_common_disk.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/test_cpld_flash_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/test_ddr_e2.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/test_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 695 B | 695 B | +0 B | system |
| `/bin/test_disp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 265.8 KB | 265.8 KB | +0 B | system |
| `/bin/test_display1_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870 B | 870 B | +0 B | system |
| `/bin/test_display2_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870 B | 870 B | +0 B | system |
| `/bin/test_display3_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870 B | 870 B | +0 B | system |
| `/bin/test_display4_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870 B | 870 B | +0 B | system |
| `/bin/test_display_led_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_dji_cht.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 771 B | 771 B | +0 B | system |
| `/bin/test_dji_cst_perf.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 674 B | 674 B | +0 B | system |
| `/bin/test_djidss_close_user_app.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/test_dsp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 396.0 KB | 396.0 KB | +0 B | system |
| `/bin/test_dsp2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.9 KB | 67.9 KB | +0 B | system |
| `/bin/test_ec1706_aperture_control.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/test_ec1706_basic_exposure.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/test_ec1706_basic_liveview.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_ec1706_collect_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/test_ec1706_collect_logs_nightly.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.2 KB | 5.2 KB | +0 B | system |
| `/bin/test_ec1706_common.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.2 KB | 9.2 KB | +0 B | system |
| `/bin/test_ec1706_f2f.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.3 KB | 13.3 KB | +0 B | system |
| `/bin/test_ec1706_frame_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/test_ec1706_interval_exposure.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/bin/test_ec1706_long_exposure.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | system |
| `/bin/test_ec1706_mf_zoom.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | system |
| `/bin/test_ec1706_raw_playback.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | system |
| `/bin/test_ec1706_reset_all_settings.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_ec1706_rtc_offset.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_ec1706_temp_sensors.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/bin/test_ec2107_bifrost_attach.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_ec2107_bifrost_detach.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_ec2107_bifrost_upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 KB | 5.8 KB | +0 B | system |
| `/bin/test_ec2107_suspend_resume_on_spi_irq.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | system |
| `/bin/test_ec2107_vcamera_expose.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_eld_ports.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.6 KB | 9.6 KB | +0 B | system |
| `/bin/test_enter_testing_state.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 737 B | 737 B | +0 B | system |
| `/bin/test_evf_diopter_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_evf_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/test_evf_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 991 B | 991 B | +0 B | system |
| `/bin/test_evf_optics_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/test_exit_testing_state.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 732 B | 732 B | +0 B | system |
| `/bin/test_exmcu_back_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 730 B | 730 B | +0 B | system |
| `/bin/test_exmcu_back_thumbwheel_press_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 728 B | 728 B | +0 B | system |
| `/bin/test_exmcu_front_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 732 B | 732 B | +0 B | system |
| `/bin/test_exmcu_iso_wb_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 725 B | 725 B | +0 B | system |
| `/bin/test_exmcu_m_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 716 B | 716 B | +0 B | system |
| `/bin/test_exposure_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_flash_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 693 B | 693 B | +0 B | system |
| `/bin/test_flashin_flashout_elx_ports.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/test_format_ssd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 688 B | 688 B | +0 B | system |
| `/bin/test_front_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 929 B | 929 B | +0 B | system |
| `/bin/test_get_serial.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 901 B | 901 B | +0 B | system |
| `/bin/test_gpu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.1 MB | 7.1 MB | +0 B | system |
| `/bin/test_grip_down_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 729 B | 729 B | +0 B | system |
| `/bin/test_grip_up_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 727 B | 727 B | +0 B | system |
| `/bin/test_hal_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/test_hal_storage` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/test_hotshoe` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.9 KB | 131.9 KB | +0 B | system |
| `/bin/test_i2c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/test_imu_fpc_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_iso_wb_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 715 B | 715 B | +0 B | system |
| `/bin/test_joystick_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 978 B | 978 B | +0 B | system |
| `/bin/test_lcd_backlight_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 794 B | 794 B | +0 B | system |
| `/bin/test_lcd_module_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 755 B | 755 B | +0 B | system |
| `/bin/test_lens_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.0 KB | 9.0 KB | +0 B | system |
| `/bin/test_light_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 940 B | 940 B | +0 B | system |
| `/bin/test_m_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 808 B | 808 B | +0 B | system |
| `/bin/test_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/test_mfi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/bin/test_mic_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_mipi_lvds_bridge_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/test_pm.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/test_power_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 724 B | 724 B | +0 B | system |
| `/bin/test_proximity_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/test_proximity_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 960 B | 960 B | +0 B | system |
| `/bin/test_recalibration.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/test_release_cord_plug_detect.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/bin/test_releasebar_calibrate_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 751 B | 751 B | +0 B | system |
| `/bin/test_releasebar_calibrate_stop.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 749 B | 749 B | +0 B | system |
| `/bin/test_releasebar_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | system |
| `/bin/test_rtc_charge_voltage.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/test_rtc_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/test_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_set_serial.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/test_sgbm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.5 KB | 68.5 KB | +0 B | system |
| `/bin/test_speaker_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_spectral_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 729 B | 729 B | +0 B | system |
| `/bin/test_spi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/test_spk_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_spk_mic_stop.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 955 B | 955 B | +0 B | system |
| `/bin/test_ssd_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 622 B | 622 B | +0 B | system |
| `/bin/test_stepper_motor_ctrl_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 846 B | 846 B | +0 B | system |
| `/bin/test_stop_down_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 729 B | 729 B | +0 B | system |
| `/bin/test_system_suspend_resume.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | system |
| `/bin/test_temp_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 760 B | 760 B | +0 B | system |
| `/bin/test_top_lcd_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/bin/test_touch_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_usb_device_enumeration.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.2 KB | 7.2 KB | +0 B | system |
| `/bin/test_usb_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 746 B | 746 B | +0 B | system |
| `/bin/test_vcr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/bin/test_venc_e2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.5 KB | 67.5 KB | +0 B | system |
| `/bin/test_wifi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/tinycap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/tinymix` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/tinypcminfo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/tinyplay` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/tombstoned` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 199.7 KB | 199.7 KB | +0 B | system |
| `/bin/toolbox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.9 KB | 131.9 KB | +0 B | system |
| `/bin/toybox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 462.6 KB | 462.6 KB | +0 B | system |
| `/bin/trace-cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 MB | 1.6 MB | +0 B | system |
| `/bin/trace_mmc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 633 B | 633 B | +0 B | system |
| `/bin/tree` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132.7 KB | 132.7 KB | +0 B | system |
| `/bin/tune2fs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/unrd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/upgrade_cpld.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | system |
| `/bin/upgrade_peripheral.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/usb_bulk_raw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/usb_bulk_raw_hbl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/usb_bulk_xfer_test_v2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/vold` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 913.8 KB | 913.8 KB | +0 B | system |
| `/bin/vold_prepare_subdirs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/vold_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/wait_for_keymaster` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/bin/weston` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 458.5 KB | 458.5 KB | +0 B | system |
| `/bin/wifi_bt_bss_mgmt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.8 KB | 29.8 KB | +0 B | system |
| `/bin/wifi_download_opt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/wifi_user_config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/wl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 MB | 2.2 MB | +0 B | system |
| `/bin/wmstool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +2.4 KB | system |
| `/bin/x2bursttest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/x2d_cal_eng_googletest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 265.3 KB | 265.3 KB | +0 B | system |
| `/bin/x2loopback` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/x2pingpong` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/x2pingrecv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/build.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 KB | 1.9 KB | +0 B | system/vendor |
| `/compatibility_matrix.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 99.7 KB | 99.7 KB | +0 B | system |
| `/default.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 237 B | 237 B | +0 B | vendor |
| `/etc/NOTICE.xml.gz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 94.3 KB | 94.3 KB | +0 B | system/vendor |
| `/etc/VERSION` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6 B | 6 B | +0 B | system |
| `/etc/ac_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 859 B | 859 B | +0 B | system |
| `/etc/adj/adj_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 335 B | 335 B | +0 B | system |
| `/etc/adj/grain_param_461.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | system |
| `/etc/adj/raw_proc_param_461.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 103.0 KB | 103.0 KB | +0 B | system |
| `/etc/audio.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/etc/audio_ec2107.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/etc/audio_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | system |
| `/etc/blackbox.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 590 B | 590 B | +0 B | system |
| `/etc/blackbox_ec2107.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 590 B | 590 B | +0 B | system |
| `/etc/cam_log_format.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/etc/cam_log_strategy.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/etc/cht_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/etc/cht_cases_quick.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/etc/copy_ci_list` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 839 B | 839 B | +0 B | system |
| `/etc/copy_json_files` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/etc/cst_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 250 B | 250 B | +0 B | system |
| `/etc/cst_cases_quick.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26 B | 26 B | +0 B | system |
| `/etc/dbus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/dds.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 973 B | 973 B | +0 B | system |
| `/etc/device_table.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 696 B | 696 B | +0 B | system |
| `/etc/disp_auto_test.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/etc/dji.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.1 KB | 56.1 KB | +0 B | system |
| `/etc/dji_camera.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.9 KB | 19.9 KB | +0 B | system |
| `/etc/dji_camera.tsf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 772 B | 772 B | +0 B | system |
| `/etc/dji_camera_imx461bqr.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93 B | 93 B | +0 B | system |
| `/etc/dji_dc_ecc_public_key.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | system |
| `/etc/dspf/json/dspf_icc_chnl_cfg.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/etc/event-log-tags` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/fbuf_test.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48 B | 48 B | +0 B | system |
| `/etc/file_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.7 KB | 37.7 KB | +0 B | vendor |
| `/etc/firmware/aw87519_drcv.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | system |
| `/etc/firmware/aw87519_hvload.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | system |
| `/etc/firmware/aw87519_kspk.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | system |
| `/etc/firmware/aw8896_cfg.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124 B | 124 B | +0 B | system |
| `/etc/firmware/aw8896_fw_d.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 368 B | 368 B | +0 B | system |
| `/etc/firmware/aw8896_fw_e.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 412 B | 412 B | +0 B | system |
| `/etc/firmware/aw8896_reg.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 76 B | 76 B | +0 B | system |
| `/etc/firmware/bifrost_body_v1.3.3.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.9 KB | 23.9 KB | +0 B | system |
| `/etc/firmware/bifrost_grip_v1.3.3.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.5 KB | 22.5 KB | +0 B | system |
| `/etc/firmware/ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B | system |
| `/etc/firmware/ec2107_cpld.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B | system |
| `/etc/firmware/exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 413.6 KB | 413.6 KB | +0 B | system |
| `/etc/firmware/exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +8 B | system |
| `/etc/firmware/exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B | system |
| `/etc/firmware/goodix_cfg_group.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 930 B | 790 B | -140 B | system |
| `/etc/firmware/goodix_firmware.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.2 KB | 70.2 KB | +0 B | system |
| `/etc/firmware/rgx.fw.24.66.54.204` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 204.0 KB | 204.0 KB | +0 B | system |
| `/etc/firmware/rgx.sh.24.66.54.204` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 162.1 KB | 162.1 KB | +0 B | system |
| `/etc/fstab.eagle2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | vendor |
| `/etc/hostapd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 315 B | 315 B | +0 B | system |
| `/etc/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56 B | 56 B | +0 B | system |
| `/etc/imx461bqr_ec1706.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 57.2 KB | 57.2 KB | +0 B | system |
| `/etc/imx461bqr_ec1706.sp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54.9 KB | 54.9 KB | +0 B | system |
| `/etc/init/camera-gui.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/init/camera-service.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 126 B | 126 B | +0 B | system |
| `/etc/init/camera-storage.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 110 B | 110 B | +0 B | system |
| `/etc/init/camera-system.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 549 B | 549 B | +0 B | system |
| `/etc/init/camera-test.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93 B | 93 B | +0 B | system |
| `/etc/init/camera-upgrade.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131 B | 131 B | +0 B | system |
| `/etc/init/dbus.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 235 B | 235 B | +0 B | system |
| `/etc/init/dji_amt.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 190 B | 190 B | +0 B | system |
| `/etc/init/dji_audio.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 207 B | 207 B | +0 B | system |
| `/etc/init/dji_blackbox.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 461 B | 461 B | +0 B | system |
| `/etc/init/dji_sec.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 190 B | 190 B | +0 B | system |
| `/etc/init/dji_system.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 196 B | 196 B | +0 B | system |
| `/etc/init/djiconfigstore.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 226 B | 226 B | +0 B | system |
| `/etc/init/init.coredump.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 615 B | 615 B | +0 B | system |
| `/etc/init/init.eagle2.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | vendor |
| `/etc/init/init.eagle2.usb.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | vendor |
| `/etc/init/init.log.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 169 B | 169 B | +0 B | system |
| `/etc/init/lmkd.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 176 B | 176 B | +0 B | system |
| `/etc/init/logd.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 596 B | 596 B | +0 B | system |
| `/etc/init/logtagd.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 291 B | 291 B | +0 B | system |
| `/etc/init/msg2dbus.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 139 B | 139 B | +0 B | system |
| `/etc/init/phocus.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 83 B | 83 B | +0 B | system |
| `/etc/init/servicemanager.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 520 B | 520 B | +0 B | system |
| `/etc/init/test-mode.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 188 B | 188 B | +0 B | system |
| `/etc/init/tombstoned.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 399 B | 399 B | +0 B | system |
| `/etc/init/vold.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 360 B | 360 B | +0 B | system |
| `/etc/init/wait_for_keymaster.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 127 B | 127 B | +0 B | system |
| `/etc/init/weston.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132 B | 132 B | +0 B | system |
| `/etc/iq/config.fbs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.5 KB | 276.5 KB | +0 B | system |
| `/etc/iq/dji_rcam.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 139 B | 139 B | +0 B | system |
| `/etc/iq/ec1706_config.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 MB | 2.2 MB | +0 B | system |
| `/etc/iq/ec1706_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.5 MB | 6.5 MB | +0 B | system |
| `/etc/lens_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 154.5 KB | 154.5 KB | +0 B | system |
| `/etc/microphone.apu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/mke2fs.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/etc/mkshrc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/etc/ml/afc_tracking.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.1 KB | 4.1 KB | +0 B | vendor |
| `/etc/ml/cnntk.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 KB | 1.7 KB | +0 B | vendor |
| `/etc/ml/dynamic_roi.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 832 B | 832 B | +0 B | vendor |
| `/etc/ml/e2_udp.prototxt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263 B | 263 B | +0 B | system |
| `/etc/ml/fdc.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 768 B | 768 B | +0 B | vendor |
| `/etc/ml/gtest_params.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 413 B | 413 B | +0 B | system |
| `/etc/ml/vpf_cfg.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.0 KB | 6.0 KB | +0 B | vendor |
| `/etc/ml/vpf_cfg_gtest.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.4 KB | 2.4 KB | +0 B | vendor |
| `/etc/ml/vpf_storage.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 KB | 1.6 KB | +0 B | vendor |
| `/etc/ml/wm260_master.prototxt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273 B | 273 B | +0 B | system |
| `/etc/ml_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 164 B | 164 B | +0 B | system |
| `/etc/module_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 449 B | 449 B | +0 B | system |
| `/etc/mount/init.mount.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/network_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 250 B | 250 B | +0 B | system |
| `/etc/perception/json/acc_topic.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | system |
| `/etc/perception/json/cis_load_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.0 KB | 18.0 KB | +0 B | system |
| `/etc/perception/json/cnn_stereo_refine_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68 B | 68 B | +0 B | system |
| `/etc/perception/json/dbus_to_storage.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 KB | 5.3 KB | +0 B | system |
| `/etc/perception/json/dsp_load_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/etc/perception/json/dsp_param_loaded_by_mgr.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70 B | 70 B | +0 B | system |
| `/etc/perception/json/dspf/dspf_icc_chnl_cfg.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/etc/perception/json/freertos_monitor_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 169 B | 169 B | +0 B | system |
| `/etc/perception/json/func_ap_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 223 B | 223 B | +0 B | system |
| `/etc/perception/json/prores_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/etc/perception/json/ss_dbus_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 968 B | 968 B | +0 B | system |
| `/etc/perception/json/vacc_debug_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/etc/perception/json/vacc_reconfig_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.1 KB | 8.1 KB | +0 B | system |
| `/etc/perception/json/vio.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | system |
| `/etc/perception/json/vp_app_init_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 648 B | 648 B | +0 B | system |
| `/etc/perception/json/vp_base_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 533 B | 533 B | +0 B | system |
| `/etc/perception/json/vp_cnn_framework_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 927 B | 927 B | +0 B | system |
| `/etc/perception/json/vp_dpp_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.7 KB | 6.7 KB | +0 B | system |
| `/etc/perception/json/vp_dsp_func_route_table.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | system |
| `/etc/perception/json/vp_message_param_linux.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 861 B | 861 B | +0 B | system |
| `/etc/perception/json/vps_tof_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 826 B | 826 B | +0 B | system |
| `/etc/perception/json/xx_param.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 424 B | 424 B | +0 B | system |
| `/etc/perf_cst_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30 B | 30 B | +0 B | system |
| `/etc/plugins.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.7 KB | 25.7 KB | +0 B | system |
| `/etc/powervr.ini` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | system |
| `/etc/ppt_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 187 B | 187 B | +0 B | system |
| `/etc/pre_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 251 B | 251 B | +0 B | system |
| `/etc/process.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/etc/prop.default` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 502 B | 502 B | +0 B | system |
| `/etc/recovery.fstab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 970 B | 970 B | +0 B | system |
| `/etc/security/otacerts.zip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/etc/selftests` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 839 B | 839 B | +0 B | system |
| `/etc/selinux/mapping/28.0.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 123.4 KB | 123.4 KB | +0 B | system |
| `/etc/selinux/plat_and_mapping_sepolicy.cil.sha256` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65 B | 65 B | +0 B | system |
| `/etc/selinux/plat_file_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.2 KB | 23.2 KB | +0 B | system |
| `/etc/selinux/plat_hwservice_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.0 KB | 7.0 KB | +0 B | system |
| `/etc/selinux/plat_mac_permissions.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | system |
| `/etc/selinux/plat_property_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | system |
| `/etc/selinux/plat_pub_versioned.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 709.1 KB | 709.1 KB | +0 B | vendor |
| `/etc/selinux/plat_seapp_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/etc/selinux/plat_sepolicy.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/etc/selinux/plat_sepolicy_vers.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5 B | 5 B | +0 B | vendor |
| `/etc/selinux/plat_service_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.2 KB | 14.2 KB | +0 B | system |
| `/etc/selinux/precompiled_sepolicy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 431.1 KB | 431.1 KB | +0 B | vendor |
| `/etc/selinux/precompiled_sepolicy.plat_and_mapping.sha256` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65 B | 65 B | +0 B | vendor |
| `/etc/selinux/selinux_denial_metadata` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/selinux/vendor_file_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.8 KB | 10.8 KB | +0 B | vendor |
| `/etc/selinux/vendor_hwservice_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | vendor |
| `/etc/selinux/vendor_mac_permissions.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101 B | 101 B | +0 B | vendor |
| `/etc/selinux/vendor_property_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 328 B | 328 B | +0 B | vendor |
| `/etc/selinux/vendor_seapp_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | vendor |
| `/etc/selinux/vendor_sepolicy.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.1 KB | 195.1 KB | +0 B | vendor |
| `/etc/selinux/vndservice_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65 B | 65 B | +0 B | vendor |
| `/etc/sepolicy.dbg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 437.5 KB | 437.5 KB | +0 B | system |
| `/etc/sepolicy_tests` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/etc/speaker.apu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/sysctl.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 637 B | 637 B | +0 B | system |
| `/etc/sysmode_param_manager.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 745 B | 745 B | +0 B | system |
| `/etc/test_rtos/param_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/etc/test_rtos/param_manager.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 792 B | 792 B | +0 B | system |
| `/etc/test_rtos/test_pm.py` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | system |
| `/etc/udhcpd_rndis.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/udhcpd_wlan0.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/vintf/compatibility_matrix.1.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.1 KB | 70.1 KB | +0 B | system |
| `/etc/vintf/compatibility_matrix.2.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.3 KB | 72.3 KB | +0 B | system |
| `/etc/vintf/compatibility_matrix.3.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 86.6 KB | 86.6 KB | +0 B | system |
| `/etc/vintf/compatibility_matrix.device.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 380 B | 380 B | +0 B | system |
| `/etc/vintf/compatibility_matrix.legacy.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.1 KB | 70.1 KB | +0 B | system |
| `/etc/vintf/compatibility_matrix.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | vendor |
| `/etc/vintf/manifest.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system/vendor |
| `/etc/wms_ec1706.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 531 B | 531 B | +0 B | system |
| `/etc/wms_ec2107.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 531 B | 531 B | +0 B | system |
| `/etc/xcd20_35.cali` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.5 MB | 23.5 MB | +0 B | system |
| `/etc/xtables.lock` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/firmware/BCM43752_001.003.006.0035.0045.hcd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.6 KB | 73.6 KB | +0 B | vendor |
| `/firmware/clm_bcm43752a2_ag_ec1706.blob` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.5 KB | 28.5 KB | +0 B | vendor |
| `/firmware/clm_bcm43752a2_ag_ec2107.blob` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.5 KB | 28.5 KB | +0 B | vendor |
| `/firmware/config.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 325 B | 325 B | +0 B | vendor |
| `/firmware/dspf/ss_dsp0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | vendor |
| `/firmware/dspf/ss_dsp0.lin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 228.9 KB | 228.9 KB | +0 B | vendor |
| `/firmware/dspf/ss_dsp1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 MB | 1.5 MB | +0 B | vendor |
| `/firmware/dspf/ss_dsp1.lin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 229.0 KB | 229.0 KB | +0 B | vendor |
| `/firmware/dspf/ss_dsp2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 MB | 1.5 MB | +0 B | vendor |
| `/firmware/dspf/ss_dsp2.lin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 229.0 KB | 229.0 KB | +0 B | vendor |
| `/firmware/fw_bcm43752a2_ag.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 700.4 KB | 700.4 KB | +0 B | vendor |
| `/firmware/fw_bcm43752a2_ag_mfg.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 760.4 KB | 760.4 KB | +0 B | vendor |
| `/firmware/nvram_ec1706.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.7 KB | 9.7 KB | +0 B | vendor |
| `/firmware/nvram_ec2107.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.7 KB | 9.7 KB | +0 B | vendor |
| `/lib/modules/as7341.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323.7 KB | 323.7 KB | +0 B | system |
| `/lib/modules/ask_dsp_driver.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 627.2 KB | 627.2 KB | +0 B | system |
| `/lib/modules/atmel_mxt_ts.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 411.7 KB | 411.7 KB | +0 B | system |
| `/lib/modules/bcmdhd.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 MB | 1.9 MB | +0 B | system |
| `/lib/modules/bluetooth.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.4 MB | 7.4 MB | +0 B | system |
| `/lib/modules/cam_vreg.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.5 KB | 37.5 KB | +0 B | system |
| `/lib/modules/camecg_drv.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 355.5 KB | 355.5 KB | +0 B | system |
| `/lib/modules/cfg80211.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.3 MB | 7.3 MB | +0 B | system |
| `/lib/modules/designware_i2s.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 347.0 KB | 347.0 KB | +0 B | system |
| `/lib/modules/dji-spinor.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 274.3 KB | 274.3 KB | +0 B | system |
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 373.9 KB | 373.9 KB | +0 B | system |
| `/lib/modules/dji_j2kcodec.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 619.8 KB | 619.8 KB | +0 B | system |
| `/lib/modules/dji_jpegxrcodec.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 279.7 KB | 279.7 KB | +0 B | system |
| `/lib/modules/dji_ljcodec.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 552.2 KB | 552.2 KB | +0 B | system |
| `/lib/modules/dji_mctf.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 125.4 KB | 125.4 KB | +0 B | system |
| `/lib/modules/dji_msdec.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 410.7 KB | 410.7 KB | +0 B | system |
| `/lib/modules/dji_msenc.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 279.8 KB | 279.8 KB | +0 B | system |
| `/lib/modules/dji_proresDec.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.3 KB | 276.3 KB | +0 B | system |
| `/lib/modules/dji_proresEnc.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 702.7 KB | 702.7 KB | +0 B | system |
| `/lib/modules/dji_ycc.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib/modules/dwc_eth_qos.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 540.9 KB | 540.9 KB | +0 B | system |
| `/lib/modules/dwmac-dwc-qos-eth.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 309.6 KB | 309.6 KB | +0 B | system |
| `/lib/modules/e1000e.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 MB | 3.9 MB | +0 B | system |
| `/lib/modules/eagle_dsp.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 559.1 KB | 559.1 KB | +0 B | system |
| `/lib/modules/ecx337aa.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 272.2 KB | 272.2 KB | +0 B | system |
| `/lib/modules/focaltech_tp.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 MB | 2.7 MB | +0 B | system |
| `/lib/modules/focaltp.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/ftdi_sio.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 503.8 KB | 503.8 KB | +0 B | system |
| `/lib/modules/goodix_core.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 MB | 1.4 MB | +0 B | system |
| `/lib/modules/gspca_main.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 622.0 KB | 622.0 KB | +0 B | system |
| `/lib/modules/hci_uart.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib/modules/himax_tp.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/modules/icc_chnl.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib/modules/ili2120.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263.1 KB | 263.1 KB | +0 B | system |
| `/lib/modules/l3ej03110a.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 274.9 KB | 274.9 KB | +0 B | system |
| `/lib/modules/leds-pwm.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 239.1 KB | 239.1 KB | +0 B | system |
| `/lib/modules/mac80211.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.1 MB | 20.1 MB | +0 B | system |
| `/lib/modules/mmc_test.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 511.5 KB | 511.5 KB | +0 B | system |
| `/lib/modules/proresenc_mod.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273.9 KB | 273.9 KB | +0 B | system |
| `/lib/modules/pvrsrvkm.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 MB | 2.2 MB | +0 B | system |
| `/lib/modules/r8152.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 646.7 KB | 646.7 KB | +0 B | system |
| `/lib/modules/realtek.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 248.1 KB | 248.1 KB | +0 B | system |
| `/lib/modules/snd-hwdep.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 294.5 KB | 294.5 KB | +0 B | system |
| `/lib/modules/snd-rawmidi.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 403.8 KB | 403.8 KB | +0 B | system |
| `/lib/modules/snd-soc-ak5522.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 350.4 KB | 350.4 KB | +0 B | system |
| `/lib/modules/snd-soc-ak7755.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525.0 KB | 525.0 KB | +0 B | system |
| `/lib/modules/snd-soc-aw87519.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 350.4 KB | 350.4 KB | +0 B | system |
| `/lib/modules/snd-soc-aw8896.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 694.5 KB | 694.5 KB | +0 B | system |
| `/lib/modules/snd-soc-cs47l35.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 MB | 2.1 MB | +0 B | system |
| `/lib/modules/snd-soc-dji-dummy-codec.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273.6 KB | 273.6 KB | +0 B | system |
| `/lib/modules/snd-soc-nau8821.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 428.1 KB | 428.1 KB | +0 B | system |
| `/lib/modules/snd-soc-nau8825.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 459.1 KB | 459.1 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card-utils.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 284.4 KB | 284.4 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 339.0 KB | 339.0 KB | +0 B | system |
| `/lib/modules/snd-soc-tlv320aic31xx.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 380.9 KB | 380.9 KB | +0 B | system |
| `/lib/modules/snd-usb-audio.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 MB | 2.5 MB | +0 B | system |
| `/lib/modules/snd-usbmidi-lib.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337.5 KB | 337.5 KB | +0 B | system |
| `/lib/modules/tc358749.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 554.5 KB | 554.5 KB | +0 B | system |
| `/lib/modules/test_bitmap.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 188.2 KB | 188.2 KB | +0 B | system |
| `/lib/modules/test_bpf.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/test_firmware.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 218.7 KB | 218.7 KB | +0 B | system |
| `/lib/modules/test_printf.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 193.7 KB | 193.7 KB | +0 B | system |
| `/lib/modules/test_static_key_base.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 158.7 KB | 158.7 KB | +0 B | system |
| `/lib/modules/test_static_keys.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 169.9 KB | 169.9 KB | +0 B | system |
| `/lib/modules/test_user_copy.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 184.3 KB | 184.3 KB | +0 B | system |
| `/lib/modules/vc_decoder.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 405.9 KB | 405.9 KB | +0 B | system |
| `/lib/modules/vc_encoder.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 434.8 KB | 434.8 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_h26x_core0.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 232.6 KB | 232.6 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_h26x_core1.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 232.6 KB | 232.6 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_jpeg.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 242.7 KB | 242.7 KB | +0 B | system |
| `/lib/modules/vcam_driver.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 MB | 1.8 MB | +0 B | system |
| `/lib/modules/vision_cnn.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 588.0 KB | 588.0 KB | +0 B | system |
| `/lib/modules/vision_sgbm.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 414.9 KB | 414.9 KB | +0 B | system |
| `/lib/modules/vision_vcr.ko` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 590.1 KB | 590.1 KB | +0 B | system |
| `/lib64/android.hardware.keymaster@3.0.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.2 KB | 198.2 KB | +0 B | system |
| `/lib64/android.hardware.keymaster@4.0.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.9 KB | 198.9 KB | +0 B | system |
| `/lib64/camera/plugins/2d/libdcam_2d_hw.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/2d/libdcam_null_2d.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/adj/libdcam_cp_adj.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 140.9 KB | 140.9 KB | +0 B | system |
| `/lib64/camera/plugins/dewarp/libdcam_dewarp_gdc_stitching.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.5 KB | 195.5 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_e2_lcdc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 135.1 KB | 135.1 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_null.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 197.7 KB | 197.7 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland_gfx.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 197.2 KB | 197.2 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland_preview.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 197.5 KB | 197.5 KB | +0 B | system |
| `/lib64/camera/plugins/hal/libdcam_cam_info_e2_ec1706_native.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 142.2 KB | 142.2 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_hevc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_jpeg.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_sw.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/lib_frog_e2_ec1706_native.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.7 KB | 84.7 KB | +0 B | system |
| `/lib64/camera/plugins/libdcam_x2d_cal_eng.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/link_node/libdcam_container_cache_link_node.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/mctf/libdcam_mctf.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/pp_algo/libdcam_pp_e2_hiso.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.1 KB | 131.1 KB | +0 B | system |
| `/lib64/camera/plugins/pp_algo/libdcam_pp_rdns_grain.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_raw_reprocess.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_common.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.8 KB | 195.8 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_general.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_x2d.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_yuvraw_zsl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_video_single.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.6 KB | 131.6 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_async_deconv_blend_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_async_mctf_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_common_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 388.7 KB | 388.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_dsp_allocator_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_frame_adjust_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_isp_statistics_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_pdaf_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_pp_algo_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_reawb_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.0 KB | 131.0 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_rtp_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_stats_packer_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_x2d_histogram_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_x2d_ml_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.8 KB | 67.8 KB | +0 B | system |
| `/lib64/camera/plugins/venc/libdcam_venc_h26x.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/camera/plugins/venc/libdcam_venc_prores.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/venc/libdcam_venc_proresraw.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.2 KB | 131.2 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_dng_file_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 142.4 KB | 142.4 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_jpeg_file_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74.2 KB | 74.2 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_mp4_stream_async_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_mp4_stream_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_raw_stream_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_splitter_stream_av_sync_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_srt_rec_stream_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/ld-android.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.4 KB | 65.4 KB | +0 B | system |
| `/lib64/libAACdec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 452.1 KB | 452.1 KB | +0 B | system |
| `/lib64/libAACenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 516.1 KB | 516.1 KB | +0 B | system |
| `/lib64/libEGL_POWERVR_ROGUE.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.1 KB | 66.1 KB | +0 B | system |
| `/lib64/libGLESv2_POWERVR_ROGUE.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 MB | 3.2 MB | +0 B | system |
| `/lib64/libIMGegl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 514.8 KB | 514.8 KB | +0 B | system |
| `/lib64/libMessageTransport.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libQt6Concurrent.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libQt6Core.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.0 MB | 6.0 MB | +0 B | system |
| `/lib64/libQt6DBus.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 731.6 KB | 731.6 KB | +0 B | system |
| `/lib64/libQt6HttpServer.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 134.6 KB | 134.6 KB | +0 B | system |
| `/lib64/libQt6Network.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | system |
| `/lib64/libQt6SerialPort.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 135.2 KB | 135.2 KB | +0 B | system |
| `/lib64/libQt6StateMachine.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 332.8 KB | 332.8 KB | +0 B | system |
| `/lib64/libQt6WebSockets.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 200.6 KB | 200.6 KB | +0 B | system |
| `/lib64/lib_cam_acc_base.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/lib_eigen.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 196.4 KB | 196.4 KB | +0 B | system |
| `/lib64/lib_frog_hal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 201.0 KB | 201.0 KB | +0 B | system |
| `/lib64/lib_gdc_creategrid.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/lib_hal_dji_gdc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.0 KB | 73.0 KB | +0 B | system |
| `/lib64/lib_hal_dji_ycc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/lib_hal_gdc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/lib_hal_hardlink.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/lib_hal_mctf.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/lib_hal_stitch.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/lib_j2kenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.6 KB | 68.6 KB | +0 B | system |
| `/lib64/lib_ljcodec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/lib_mdev.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/lib_mediactl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/lib_msdec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.7 KB | 68.7 KB | +0 B | system |
| `/lib64/lib_msenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.8 KB | 69.8 KB | +0 B | system |
| `/lib64/lib_prores_enc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.4 KB | 69.4 KB | +0 B | system |
| `/lib64/lib_usb_transfer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.8 KB | 130.8 KB | +0 B | system |
| `/lib64/lib_vc_decoder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 526.7 KB | 526.7 KB | +0 B | system |
| `/lib64/lib_vc_encoder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 584.5 KB | 584.5 KB | +0 B | system |
| `/lib64/libaaa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 MB | 10.1 MB | -8 B | system |
| `/lib64/libadj_base.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libadsb_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libaio.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libamt_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/libapu.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.6 KB | 130.6 KB | +0 B | system |
| `/lib64/libapuapi.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libaudioclient.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libaudioservice.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 324.4 KB | 324.4 KB | +0 B | system |
| `/lib64/libavcodec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 MB | 2.3 MB | +0 B | system |
| `/lib64/libavfilter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.1 KB | 198.1 KB | +0 B | system |
| `/lib64/libavformat.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 464.8 KB | 464.8 KB | +0 B | system |
| `/lib64/libavutil.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323.5 KB | 323.5 KB | +0 B | system |
| `/lib64/libbacktrace.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.5 KB | 131.5 KB | +0 B | system |
| `/lib64/libbase.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libbinder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 584.4 KB | 584.4 KB | +0 B | system |
| `/lib64/libc++.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 905.1 KB | 905.1 KB | +0 B | system |
| `/lib64/libc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib64/libcam_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libcap.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libclang_rt.asan-aarch64-android.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 790.2 KB | 790.2 KB | +0 B | system |
| `/lib64/libcnntk_cbb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 822.6 KB | 822.6 KB | +0 B | system |
| `/lib64/libcrypto.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib64/libcrypto_utils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.4 KB | 66.4 KB | +0 B | system |
| `/lib64/libcurl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 388.5 KB | 388.5 KB | +0 B | system |
| `/lib64/libcutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libdbus.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 517.2 KB | 517.2 KB | +0 B | system |
| `/lib64/libdcam_audio_frwk.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.2 KB | 195.2 KB | +0 B | system |
| `/lib64/libdcam_base.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 709.7 KB | 709.7 KB | +0 B | system |
| `/lib64/libdcam_capture_strategy.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libdcam_chip_port.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.1 KB | 72.1 KB | +0 B | system |
| `/lib64/libdcam_dump_frame.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libdcam_e2_idm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_extention_node_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libdcam_fcali.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 644.4 KB | 644.4 KB | +0 B | system |
| `/lib64/libdcam_fnm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_fnm_dcf.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.6 KB | 195.6 KB | +0 B | system |
| `/lib64/libdcam_frwk.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | system |
| `/lib64/libdcam_image_file_writer_base.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.8 KB | 130.8 KB | +0 B | system |
| `/lib64/libdcam_iq_module.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.5 KB | 69.5 KB | +0 B | system |
| `/lib64/libdcam_iq_tplgy_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_media.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_media_file_mgr.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.7 KB | 131.7 KB | +0 B | system |
| `/lib64/libdcam_media_file_mgr_service.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.9 KB | 195.9 KB | +0 B | system |
| `/lib64/libdcam_meta_convert.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libdcam_metadata_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libdcam_muxer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 406.5 KB | 406.5 KB | +0 B | system |
| `/lib64/libdcam_muxer_engine.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libdcam_pdmonitor.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.3 MB | +0 B | system |
| `/lib64/libdcam_protobuf_dbginfo.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libdcam_protobuf_metadata.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132.1 KB | 132.1 KB | +0 B | system |
| `/lib64/libdcam_shooter_base_still.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libdcam_storage.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/lib64/libdcam_video_bps_parser.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcamecg_process.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libdcs.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.5 KB | 131.5 KB | +0 B | system |
| `/lib64/libdebuggerd_client.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdiskconfig.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libdisplay-server.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.9 KB | 195.9 KB | +0 B | system |
| `/lib64/libdji_codec_heif.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libdji_secure.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 388.5 KB | 388.5 KB | +0 B | system |
| `/lib64/libdl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.9 KB | 65.9 KB | +0 B | system |
| `/lib64/libdsp_frwk.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.8 KB | 133.8 KB | +0 B | system |
| `/lib64/libduml_async_remux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.2 KB | 131.2 KB | +0 B | system |
| `/lib64/libduml_audio.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.6 KB | 198.6 KB | +0 B | system |
| `/lib64/libduml_databuffer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.7 KB | 130.7 KB | +0 B | system |
| `/lib64/libduml_dn.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_dsocket.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_f2d.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libduml_fastrtps.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 MB | 4.9 MB | +0 B | system |
| `/lib64/libduml_fb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_ffremux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 MB | 1.5 MB | +0 B | system |
| `/lib64/libduml_hal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 578.9 KB | 578.9 KB | +0 B | system |
| `/lib64/libduml_hal_cam.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 741.5 KB | 741.5 KB | +0 B | system |
| `/lib64/libduml_mux_databuffer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_orte.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 194.2 KB | 194.2 KB | +0 B | system |
| `/lib64/libduml_osal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.4 KB | 66.4 KB | +0 B | system |
| `/lib64/libduml_payload.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_rpc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_shineIO.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.8 KB | 130.8 KB | +0 B | system |
| `/lib64/libduml_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 517.4 KB | 517.4 KB | +0 B | system |
| `/lib64/libduml_vcodec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 324.3 KB | 324.3 KB | +0 B | system |
| `/lib64/libdynamic_roi_cbb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | system |
| `/lib64/libevdev.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.9 KB | 130.9 KB | +0 B | system |
| `/lib64/libext2_blkid.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 71.1 KB | 71.1 KB | +0 B | system |
| `/lib64/libext2_com_err.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libext2_e2p.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libext2_misc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libext2_quota.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/lib64/libext2_uuid.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libext2fs.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 326.1 KB | 326.1 KB | +0 B | system |
| `/lib64/libext4_utils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libf2fs_sparseblock.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libfast2d.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libfast2d_utils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libfdc_cbb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870.5 KB | 870.5 KB | +0 B | system |
| `/lib64/libfg_pm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libfw_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libfw_util_ca.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libgip.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 196.9 KB | 196.9 KB | +0 B | system |
| `/lib64/libgip_duss.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libglslcompiler.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib64/libhardware.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libhardware_legacy.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libheif.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 646.6 KB | 646.6 KB | +0 B | system |
| `/lib64/libhidlbase.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 196.3 KB | 196.3 KB | +0 B | system |
| `/lib64/libhidltransport.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 457.4 KB | 457.4 KB | +0 B | system |
| `/lib64/libhwbinder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 196.7 KB | 196.7 KB | +0 B | system |
| `/lib64/libimu_cali_fusion.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libion.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libiprouteutil.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 149.1 KB | 149.1 KB | +0 B | system |
| `/lib64/libjnigraphics.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.7 KB | 4.7 KB | +0 B | system |
| `/lib64/libjpeg.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 260.7 KB | 260.7 KB | +0 B | system |
| `/lib64/libjxr.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 77.8 KB | 77.8 KB | +0 B | system |
| `/lib64/libjxr_container.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.8 KB | 67.8 KB | +0 B | system |
| `/lib64/libkeymaster4support.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.2 KB | 198.2 KB | +0 B | system |
| `/lib64/libkeyutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.4 KB | 66.4 KB | +0 B | system |
| `/lib64/liblog.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.6 KB | 133.6 KB | +0 B | system |
| `/lib64/liblog_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/liblogcat.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/liblogwrap.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/liblzma.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.6 KB | 195.6 KB | +0 B | system |
| `/lib64/libm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 259.2 KB | 259.2 KB | +0 B | system |
| `/lib64/libmctf_comm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libmemunreachable.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 197.3 KB | 197.3 KB | +0 B | system |
| `/lib64/libml_vcr_acc_drv.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 122.0 KB | 122.0 KB | +0 B | system |
| `/lib64/libmot_cbb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 MB | 3.4 MB | +0 B | system |
| `/lib64/libnanopb-proto3-32bit.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libnetlink.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libnl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132.7 KB | 132.7 KB | +0 B | system |
| `/lib64/libnn_framework.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 MB | 3.7 MB | +0 B | system |
| `/lib64/libopencv_java3.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.9 MB | 17.9 MB | +0 B | system |
| `/lib64/libpackagelistparser.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libpagemap.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libpcre2.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.9 KB | 130.9 KB | +0 B | system |
| `/lib64/libpcrecpp.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libperfmgr.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.3 KB | 195.3 KB | +0 B | system |
| `/lib64/libplist.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/lib64/libprocinfo.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libproxy_nn_client.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.8 KB | 67.8 KB | +0 B | system |
| `/lib64/libpyrd_gen_comm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libquicklz.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/librcam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | +80 B | system |
| `/lib64/libreg_dump_api.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libreid_cbb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 MB | 1.3 MB | +0 B | system |
| `/lib64/librtos.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libsec_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libselinux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132.6 KB | 132.6 KB | +0 B | system |
| `/lib64/libsensor_imx686.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263.2 KB | 263.2 KB | +0 B | system |
| `/lib64/libsepol.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 776.4 KB | 776.4 KB | +0 B | system |
| `/lib64/libsparse.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libsqlite.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib64/libsqlite3pp.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.7 KB | 131.7 KB | +0 B | system |
| `/lib64/libsrv_um.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 706.4 KB | 706.4 KB | +0 B | system |
| `/lib64/libssl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 330.1 KB | 330.1 KB | +0 B | system |
| `/lib64/libsuspend.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libswresample.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/lib64/libsync.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libsysmode_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libsysutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libteec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libtinyalsa.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/libunrd.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libunwind.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132.0 KB | 132.0 KB | +0 B | system |
| `/lib64/libunwindstack.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 324.2 KB | 324.2 KB | +0 B | system |
| `/lib64/liburing.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.4 KB | 66.4 KB | +0 B | system |
| `/lib64/libusb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.5 KB | 131.5 KB | +0 B | system |
| `/lib64/libusbmuxd.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libusc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 MB | 3.1 MB | +0 B | system |
| `/lib64/libutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libutilscallstack.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/lib64/libv2_sdk.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 149.2 KB | 149.2 KB | +0 B | system |
| `/lib64/libvndksupport.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libwayland-client.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.1 KB | 68.1 KB | +0 B | system |
| `/lib64/libwayland-egl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 132.7 KB | 132.7 KB | +0 B | system |
| `/lib64/libweston.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib64/libwlm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 261.7 KB | 261.7 KB | +0 B | system |
| `/lib64/libxkbcommon.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 259.7 KB | 259.7 KB | +0 B | system |
| `/lib64/libz.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.9 KB | 130.9 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-Bold-01.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 319.4 KB | 319.4 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-BoldItalic-02.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 310.2 KB | 310.2 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-DemiBold-03.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 258.3 KB | 258.3 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-DemiBoldItalic-04.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 321.2 KB | 321.2 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-Heavy-09.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 145.4 KB | 145.4 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-HeavyItalic-10.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 142.8 KB | 142.8 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-Italic-05.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 402.8 KB | 402.8 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-Medium-06.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 271.4 KB | 271.4 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-MediumItalic-07.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 342.0 KB | 342.0 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-Regular-08.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 411.2 KB | 411.2 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-UltraLight-11.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 360.6 KB | 360.6 KB | +0 B | system |
| `/lib64/qt/lib/fonts/AvenirNext-UltraLightItalic-12.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 384.2 KB | 384.2 KB | +0 B | system |
| `/lib64/qt/lib/fonts/DroidSansFallback.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 MB | 2.9 MB | +0 B | system |
| `/lib64/qt/lib/fonts/DroidSansJapanese.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib64/qt/lib/fonts/HelveticaNeue-Bold.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 470.2 KB | 470.2 KB | +0 B | system |
| `/lib64/qt/lib/fonts/HelveticaNeue-Light.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 208.8 KB | 208.8 KB | +0 B | system |
| `/lib64/qt/lib/fonts/HelveticaNeue-Medium.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 185.7 KB | 185.7 KB | +0 B | system |
| `/lib64/qt/lib/fonts/HelveticaNeue.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 464.3 KB | 464.3 KB | +0 B | system |
| `/lib64/qt/lib/fonts/copy_font_files` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/lib64/weston/eagle-backend.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 MB | 2.0 MB | +0 B | system |
| `/lib64/weston/eagle-shell.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.0 KB | 133.0 KB | +0 B | system |
| `/lib64/wms_ipc_dsock.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/model/ml/assets/J_regressor_beta.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.4 KB | 9.4 KB | +0 B | vendor |
| `/model/ml/assets/J_template.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 672 B | 672 B | +0 B | vendor |
| `/model/ml/assets/bs_mean.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 KB | 1.5 KB | +0 B | vendor |
| `/model/ml/assets/bs_std.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 KB | 1.5 KB | +0 B | vendor |
| `/model/ml/assets/mesh_25/lbs_weights.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 KB | 1.1 KB | +0 B | vendor |
| `/model/ml/assets/mesh_25/posedirs.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.2 KB | 11.2 KB | +0 B | vendor |
| `/model/ml/assets/mesh_25/shapedirs.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.6 KB | 44.6 KB | +0 B | vendor |
| `/model/ml/assets/mesh_25/v_template.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 928 B | 928 B | +0 B | vendor |
| `/model/ml/assets/mesh_500/lbs_weights.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.4 KB | 10.4 KB | +0 B | vendor |
| `/model/ml/assets/mesh_500/posedirs.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 211.5 KB | 211.5 KB | +0 B | vendor |
| `/model/ml/assets/mesh_500/shapedirs.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 879.5 KB | 879.5 KB | +0 B | vendor |
| `/model/ml/assets/mesh_500/v_template.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.5 KB | 6.5 KB | +0 B | vendor |
| `/model/ml/assets/mesh_5023/lbs_weights.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 98.7 KB | 98.7 KB | +0 B | vendor |
| `/model/ml/assets/mesh_5023/n_template.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 59.5 KB | 59.5 KB | +0 B | vendor |
| `/model/ml/assets/mesh_5023/posedirs.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.1 MB | 2.1 MB | +0 B | vendor |
| `/model/ml/assets/mesh_5023/shapedirs.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.6 MB | 8.6 MB | +0 B | vendor |
| `/model/ml/assets/mesh_5023/v_template.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 59.5 KB | 59.5 KB | +0 B | vendor |
| `/model/ml/assets/parents.bin.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 640 B | 640 B | +0 B | vendor |
| `/model/ml/ec1706.prototxt.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.6 KB | 6.6 KB | +0 B | vendor |
| `/model/ml/faceEye.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 728.7 KB | 728.7 KB | +0 B | vendor |
| `/model/ml/fdc.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 MB | 7.6 MB | +0 B | vendor |
| `/model/ml/search.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.1 MB | 5.1 MB | +0 B | vendor |
| `/model/ml/template.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.9 MB | 4.9 MB | +0 B | vendor |
| `/product/build.prop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | system |
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | +126 B | system |
| `/ta/09db16c0-873b-4fed-b87ea5d2b86293a2.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 198.5 KB | 198.5 KB | +0 B | vendor |
| `/ta/e91c9402-64a0-470f-88e7bf5d3c606b6a.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 249.1 KB | 249.1 KB | +0 B | vendor |
| `/ueventd.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 687 B | 687 B | +0 B | vendor |
| `/usr/share/X11/xkb/compat/basic` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 914 B | 914 B | +0 B | system |
| `/usr/share/X11/xkb/keycodes/evdev` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/usr/share/X11/xkb/libxkbcommon-keycodes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 914 B | 914 B | +0 B | system |
| `/usr/share/X11/xkb/rules/evdev` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 205 B | 205 B | +0 B | system |
| `/usr/share/X11/xkb/symbols/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 973 B | 973 B | +0 B | system |
| `/usr/share/X11/xkb/symbols/srvr_ctrl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/usr/share/X11/xkb/symbols/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/usr/share/X11/xkb/types/basic` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 607 B | 607 B | +0 B | system |
| `/usr/share/system-sound/af_focus_found.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40.9 KB | 40.9 KB | +0 B | system |
| `/usr/share/system-sound/af_focus_not_found.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.5 KB | 61.5 KB | +0 B | system |
| `/usr/share/system-sound/copy_audio_files` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/usr/share/system-sound/selftimer_long_beep.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 112.6 KB | 112.6 KB | +0 B | system |
| `/usr/share/system-sound/selftimer_short_beep.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.1 KB | 45.1 KB | +0 B | system |
| `/usr/share/zoneinfo/tzdata` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 488.8 KB | 488.8 KB | +0 B | system |
| `/xbin/busybox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 MB | 1.9 MB | +0 B | system |
| `/xbin/dji_update_engine` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 MB | 1.8 MB | +0 B | system |
| `/xbin/latencytop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/xbin/librank` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/xbin/mmc_utils` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.1 KB | 69.1 KB | +0 B | system |
| `/xbin/procmem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/xbin/procrank` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/xbin/showmap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/xbin/showslab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/xbin/su` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
</details>
