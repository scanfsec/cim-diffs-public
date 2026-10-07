# X2D 100C: 3.2.0 ➜ 3.2.1

> 生成时间: 2026-10-07T06:08:47 · CIM 日期: 2024-05-25 ➜ 2024-06-18 · 条目: 8 ➜ 8 · 源: `X2D_100C_v3_2_0.cim` ➜ `X2D_100C_v3_2_1.cim`

## Summary

文件树 +0/-0/~139；CIM 条目 +0/-0/~5；OTA 镜像 ~7 变更 / 0 未变；符号 +217/-59 funcs, +60/-3 objs；新增字符串 407 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B |
| `exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 413.6 KB | 413.6 KB | +0 B |
| `exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +0 B |
| `exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 162.3 MB | 162.1 MB | -210.2 KB |
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
| `lib` | 0 | 0 | 74 | 0 | 0 |
| `model` | 0 | 0 | 23 | 0 | 0 |
| `etc` | 0 | 0 | 14 | 165 | 0 |
| `bin` | 0 | 0 | 11 | 333 | 0 |
| `lib64` | 0 | 0 | 9 | 279 | 0 |
| `(root)` | 0 | 0 | 3 | 2 | 0 |
| `firmware` | 0 | 0 | 3 | 11 | 0 |
| `ta` | 0 | 0 | 2 | 0 | 0 |
| `product` | 0 | 0 | 0 | 1 | 0 |
| `usr` | 0 | 0 | 0 | 14 | 0 |
| `xbin` | 0 | 0 | 0 | 10 | 0 |

明细 954 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+217 / −59** functions, **+60 / −3** objects（50 个变更 ELF, 另有 44 个未列出）。

### `/bin/camera-gui`

+59 / −59 functions · +0 / −0 objects

**New functions (59)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3ebb90 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3ecc20 | 240 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_components_PageListView_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x40d9d8 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x414138 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x414a20 | 244 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_components_TemperatureStatus_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x428750 | 296 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_components_TextCheckbox_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42a8d0 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_TextCheckboxRow_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42c128 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_TextCheckboxRow_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x42d828 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_TimerIndicator_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x43b0e0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_TimerIndicator_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x43c868 | 244 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x445b08 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x445b38 | 252 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x445e20 | 236 |
| `_ZN21QmlCacheGeneratedCode54_app_qml_components_buttons_BracketedCameraControl_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x446f00 | 240 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x44b050 | 256 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_controlscreen_ExposureAdjustIndicator_qml4$_178__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x463f00 | 256 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x469558 | 44 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x469588 | 244 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x469b58 | 484 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedControl_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x46c128 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedControl_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x46c708 | 236 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_error_ErrorNonAck_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x471ac0 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_error_ErrorUsbConnected_qml4$_588__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x476590 | 264 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeIconText_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x47df48 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeIconText_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x47e920 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_ApertureIndicator_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x487d50 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_ApertureIndicator_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x488bb8 | 260 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x496720 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x498930 | 260 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_liveview_FocusIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49b088 | 240 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_IsoWBSelector_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4a2e20 | 256 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_MFAssistDistanceScale_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4c96b8 | 240 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_OverlayListView_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4ce4f0 | 244 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2a40 | 44 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2aa0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d2ec0 | 236 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d30b0 | 236 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d5bd8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d6490 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d83b8 | 256 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_168__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d87d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d9a48 | 256 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_liveview_SubFaceIndicator_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dd630 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_liveview_SubFaceIndicator_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4dd690 | 240 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_ZoomIndicator_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4de3f8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_liveview_ZoomIndicator_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4de9a0 | 244 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e2878 | 44 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4e4e90 | 228 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SliderDelegate_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x510810 | 44 |

<details><summary>… 另 9 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SliderDelegate_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5125a8 | 232 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SwitchDelegate_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x518df0 | 256 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x537b80 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x539fc0 | 388 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_448__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x549a00 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54db50 | 260 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x567a50 | 44 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x568930 | 244 |
| `_ZN21QmlCacheGeneratedCode37_touchtest_qml_FreeStyleTouchTest_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xab3280 | 256 |

</details>

**Removed functions (59)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_MetadataStarRow_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4053a0 | 44 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_MetadataStarRow_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4053d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_MetadataStarRow_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4056e8 | 236 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_MetadataStarRow_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4057d8 | 240 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4141b0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x414b60 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_ProgressShader_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x419680 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_ProgressShader_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x41a0f8 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_components_TextCheckbox_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42a928 | 240 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_components_TextValueRow_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x439588 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_components_TextValueRow_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x439b30 | 236 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_WifiStatus_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4452c0 | 300 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_WifiStatus_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4453f0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode34_app_qml_components_WifiStatus_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x445b68 | 236 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x445c58 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_WritingIndicator_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x445e70 | 236 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_controlscreen_ExposureAdjustIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x463998 | 44 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_controlscreen_ExposureAdjustIndicator_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x464228 | 240 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x46c9b8 | 44 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x46c9e8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x46d5c8 | 244 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x46d6c0 | 236 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_AFIndicator_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x489c80 | 264 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_348__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x496200 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x498d28 | 260 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml4$_188__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b3060 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4bb328 | 260 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2368 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_QuickAdjustSlider_qml4$_13clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d3848 | 244 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d4418 | 44 |
| `_ZZNK21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d4e68 | 260 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d53d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d64a8 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_mainmenu_LicenseView_qml4$_178__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ed110 | 256 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x503bb0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x504fa8 | 256 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextButtonDelegate_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51a350 | 44 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextButtonDelegate_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x51abc0 | 232 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_ValueSwitchDelegate_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51c700 | 256 |
| `_ZN21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x520658 | 44 |
| `_ZZNK21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x521648 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewModel_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52c8a8 | 252 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5370f0 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x539530 | 388 |
| `_ZN21QmlCacheGeneratedCode27_app_qml_popups_Popover_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x53f1a8 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x547e80 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x547ee0 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_298__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x548688 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_318__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5487b8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54a268 | 236 |

<details><summary>… 另 9 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54a4c0 | 244 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_31clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54c158 | 244 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x557c30 | 256 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x561b70 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5634e0 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x567378 | 264 |
| `_ZN21QmlCacheGeneratedCode37_touchtest_qml_FreeStyleTouchTest_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xab2d40 | 256 |
| `_ZN21QmlCacheGeneratedCode37_confirmtest_qml_confirmtest_main_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xacf7f8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_confirmtest_qml_confirmtest_main_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0xad0298 | 240 |

</details>

### `/bin/camera-system`

+45 / −0 functions · +20 / −1 objects

**New functions (45)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeI11PathWatcherE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x6a7f0 | 16 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI4UnrdE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x6a7f0 | 16 |
| `_ZN17QArrayDataPointerIP11PathWatcherE20tryReadjustFreeSpaceEN10QArrayData14GrowthPositionExPPKS1_` | 0x72230 | 292 |
| `_ZN17QArrayDataPointerIP11PathWatcherE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x72358 | 460 |
| `_ZN17QArrayDataPointerIP11PathWatcherE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0x72528 | 372 |
| `_ZN8ProdInfo12setSuVariantEj` | 0xeb8f0 | 448 |
| `_ZN11PathWatcher18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x1188c0 | 248 |
| `_ZN11PathWatcher11pathChangedERK7QString` | 0x1189b8 | 88 |
| `_ZN11PathWatcher7timeoutEv` | 0x118a10 | 20 |
| `_ZNK11PathWatcher10metaObjectEv` | 0x118a28 | 28 |
| `_ZN11PathWatcher11qt_metacastEPKc` | 0x118a48 | 84 |
| `_ZN11PathWatcher11qt_metacallEN11QMetaObject4CallEiPPv` | 0x118aa0 | 240 |
| `_ZN11PathWatcherD2Ev` | 0x118c58 | 220 |
| `_ZN11PathWatcherD0Ev` | 0x118d38 | 228 |
| `_ZN11PathWatcherC1EP7QObjectRK7QStringi` | 0x120738 | 828 |
| `_ZN11PathWatcherC2EP7QObjectRK7QStringi` | 0x120738 | 828 |
| `_ZN11PathWatcher18onWatchPathChangedEv` | 0x120a78 | 380 |
| `_ZN11PathWatcher5startEv` | 0x120bf8 | 248 |
| `_ZN11PathWatcher9watchPathE7QString` | 0x120cf0 | 1284 |
| `_ZN11PathWatcher14addToWatchListERK7QString` | 0x121350 | 452 |
| `_ZN9QtPrivate11QSlotObjectIM11PathWatcherFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x121518 | 116 |
| `_ZNK9QFileInfo6isRootEv` | 0x138190 | 68 |
| `_ZN18QFileSystemWatcher7addPathERK7QString` | 0x219790 | 732 |
| `_ZN18QFileSystemWatcher11removePathsERK5QListI7QStringE` | 0x219ba0 | 1416 |
| `_ZN4Unrd18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x28d680 | 260 |
| `_ZN4Unrd12validChangedEb` | 0x28d788 | 100 |
| `_ZN4Unrd10initFailedEv` | 0x28d7f0 | 20 |
| `_ZNK4Unrd10metaObjectEv` | 0x28d808 | 28 |
| `_ZN4Unrd11qt_metacastEPKc` | 0x28d828 | 84 |
| `_ZN4Unrd11qt_metacallEN11QMetaObject4CallEiPPv` | 0x28d880 | 252 |
| `_ZN4UnrdD2Ev` | 0x28d980 | 92 |
| `_ZN4UnrdD0Ev` | 0x28d9e0 | 100 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI4UnrdE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x28da48 | 12 |
| `_Z8set_unrdPKcS0_` | 0x28da58 | 820 |
| `_ZL11openContextR13UnrdContext_t` | 0x28dd90 | 856 |
| `_ZL14releaseContextRK13UnrdContext_t` | 0x28e0e8 | 348 |
| `_ZN4UnrdC1EP7QObject` | 0x28e248 | 792 |
| `_ZN4UnrdC2EP7QObject` | 0x28e248 | 792 |
| `_ZN4Unrd8setValidEb` | 0x28e560 | 416 |
| `_ZN4Unrd10addWatcherERK7QString` | 0x28e700 | 1056 |
| `_ZN4Unrd10checkValidEv` | 0x28eb20 | 932 |
| `_ZN4Unrd3setEPKcS1_` | 0x28eec8 | 464 |
| `_ZN9QtPrivate11QSlotObjectIM4UnrdFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x28f098 | 116 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN4Unrd10addWatcherERK7QStringE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x28f110 | 516 |
| `_ZN9QtPrivate12QPodArrayOpsIP11PathWatcherE7emplaceIJRS2_EEEvxDpOT_` | 0x28f318 | 424 |

**New objects (20)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12_GLOBAL__N_130qt_meta_stringdata_PathWatcherE` | 0x3c682c | 108 |
| `_ZL24qt_meta_data_PathWatcher` | 0x3c6898 | 152 |
| `_ZTS11PathWatcher` | 0x3c693e | 14 |
| `_ZN9QtPrivate16QMetaTypeForTypeI11PathWatcherE4nameE` | 0x3c6960 | 12 |
| `_ZN12_GLOBAL__N_123qt_meta_stringdata_UnrdE` | 0x476dfc | 96 |
| `_ZL17qt_meta_data_Unrd` | 0x476e5c | 152 |
| `_ZTS4Unrd` | 0x476ef4 | 6 |
| `_ZN9QtPrivate16QMetaTypeForTypeI4UnrdE4nameE` | 0x476efa | 5 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_ProdInfo_tEJN9QtPrivate20TypeAndForceCompleteI7QStringNSt3__117integral_constantIbLb1EEEEENS3_IhS7_EES9_NS3_IjS7_EENS3_I5QListIiES7_EES9_S9_S9_S9_S9_SD_SD_SD_SA_S9_S9_S9_S9_SA_SA_SA_SD_SD_S9_S9_NS3_ISB_I8QVariantES7_EESD_NS3_IiS7_EESD_S9_SA_NS3_I8ProdInfoS7_EEEE` | 0x55eaa8 | 256 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PathWatcher_tEJN9QtPrivate20TypeAndForceCompleteI11PathWatcherNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EESA_SA_EE` | 0x561e18 | 40 |
| `_ZN11PathWatcher16staticMetaObjectE` | 0x561e40 | 56 |
| `_ZTV11PathWatcher` | 0x561f00 | 112 |
| `_ZTI11PathWatcher` | 0x561f70 | 24 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_125qt_meta_stringdata_Unrd_tEJN9QtPrivate20TypeAndForceCompleteI4UnrdNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IbS9_EESA_SA_EE` | 0x567cf8 | 40 |
| `_ZN4Unrd16staticMetaObjectE` | 0x567d20 | 56 |
| `_ZTV4Unrd` | 0x567d58 | 112 |
| `_ZTI4Unrd` | 0x567dc8 | 24 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI11PathWatcherE8metaTypeE` | 0x574590 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI4UnrdE8metaTypeE` | 0x577c00 | 112 |
| `_ZN12_GLOBAL__N_113kSuVariantTagE` | 0x57daf0 | 24 |

**Removed objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_ProdInfo_tEJN9QtPrivate20TypeAndForceCompleteI7QStringNSt3__117integral_constantIbLb1EEEEENS3_IhS7_EES9_NS3_IjS7_EENS3_I5QListIiES7_EES9_S9_S9_S9_S9_SD_SD_SD_SA_S9_S9_S9_S9_SA_SA_SA_SD_SD_S9_S9_NS3_ISB_I8QVariantES7_EESD_NS3_IiS7_EESD_S9_NS3_I8ProdInfoS7_EEEE` | 0x55ed30 | 248 |

### `/bin/camera-test`

+44 / −0 functions · +20 / −1 objects

**New functions (44)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeI11PathWatcherE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x45f18 | 16 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI4UnrdE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x45f18 | 16 |
| `_ZN11Calibration22findHighContrastPixelsEPFP11MemoryBlockm21MemoryAllocationFlagsEPKttjjjjRNSt3__14listI17HighContrastPixelNS7_9allocatorIS9_EEEERK4CropRK9ImageMask` | 0x77e40 | 1252 |
| `_ZN17QArrayDataPointerIP11PathWatcherE20tryReadjustFreeSpaceEN10QArrayData14GrowthPositionExPPKS1_` | 0xcc268 | 292 |
| `_ZN17QArrayDataPointerIP11PathWatcherE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0xcc660 | 372 |
| `_ZN11PathWatcher18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0xebd20 | 248 |
| `_ZN11PathWatcher11pathChangedERK7QString` | 0xebe18 | 88 |
| `_ZN11PathWatcher7timeoutEv` | 0xebe70 | 20 |
| `_ZNK11PathWatcher10metaObjectEv` | 0xebe88 | 28 |
| `_ZN11PathWatcher11qt_metacastEPKc` | 0xebea8 | 84 |
| `_ZN11PathWatcher11qt_metacallEN11QMetaObject4CallEiPPv` | 0xebf00 | 240 |
| `_ZN11PathWatcherD2Ev` | 0xec068 | 220 |
| `_ZN11PathWatcherD0Ev` | 0xec148 | 228 |
| `_ZN11PathWatcherC1EP7QObjectRK7QStringi` | 0xeff28 | 828 |
| `_ZN11PathWatcherC2EP7QObjectRK7QStringi` | 0xeff28 | 828 |
| `_ZN11PathWatcher18onWatchPathChangedEv` | 0xf0268 | 380 |
| `_ZN11PathWatcher5startEv` | 0xf03e8 | 248 |
| `_ZN11PathWatcher9watchPathE7QString` | 0xf04e0 | 1284 |
| `_ZN5QListI7QStringE5clearEv` | 0xf09e8 | 340 |
| `_ZN11PathWatcher14addToWatchListERK7QString` | 0xf0b40 | 452 |
| `_ZN9QtPrivate11QSlotObjectIM11PathWatcherFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xf0d08 | 116 |
| `_ZN8ProdInfo12setSuVariantEj` | 0xf9568 | 448 |
| `_ZN4Unrd18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x129ba0 | 260 |
| `_ZN4Unrd12validChangedEb` | 0x129ca8 | 100 |
| `_ZN4Unrd10initFailedEv` | 0x129d10 | 20 |
| `_ZNK4Unrd10metaObjectEv` | 0x129d28 | 28 |
| `_ZN4Unrd11qt_metacastEPKc` | 0x129d48 | 84 |
| `_ZN4Unrd11qt_metacallEN11QMetaObject4CallEiPPv` | 0x129da0 | 252 |
| `_ZN4UnrdD2Ev` | 0x129ea0 | 92 |
| `_ZN4UnrdD0Ev` | 0x129f00 | 100 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI4UnrdE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x129f68 | 12 |
| `_Z8set_unrdPKcS0_` | 0x129f78 | 820 |
| `_ZL11openContextR13UnrdContext_t` | 0x12a2b0 | 856 |
| `_ZL14releaseContextRK13UnrdContext_t` | 0x12a608 | 348 |
| `_ZN4UnrdC1EP7QObject` | 0x12a768 | 792 |
| `_ZN4UnrdC2EP7QObject` | 0x12a768 | 792 |
| `_ZN4Unrd8setValidEb` | 0x12aa80 | 416 |
| `_ZN4Unrd10addWatcherERK7QString` | 0x12ac20 | 1056 |
| `_ZN4Unrd10checkValidEv` | 0x12b040 | 932 |
| `_ZN4Unrd3setEPKcS1_` | 0x12b3e8 | 464 |
| `_ZN9QtPrivate11QSlotObjectIM4UnrdFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x12b5b8 | 116 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN4Unrd10addWatcherERK7QStringE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x12b630 | 516 |
| `_ZN9QtPrivate12QPodArrayOpsIP11PathWatcherE7emplaceIJRS2_EEEvxDpOT_` | 0x12b838 | 424 |
| `_ZN17QArrayDataPointerIP11PathWatcherE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x12b9e0 | 460 |

**New objects (20)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12_GLOBAL__N_130qt_meta_stringdata_PathWatcherE` | 0x154ee8 | 108 |
| `_ZL24qt_meta_data_PathWatcher` | 0x154f54 | 152 |
| `_ZTS11PathWatcher` | 0x155010 | 14 |
| `_ZN9QtPrivate16QMetaTypeForTypeI11PathWatcherE4nameE` | 0x15503e | 12 |
| `_ZN12_GLOBAL__N_123qt_meta_stringdata_UnrdE` | 0x164f98 | 96 |
| `_ZL17qt_meta_data_Unrd` | 0x164ff8 | 152 |
| `_ZTS4Unrd` | 0x165090 | 6 |
| `_ZN9QtPrivate16QMetaTypeForTypeI4UnrdE4nameE` | 0x165096 | 5 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PathWatcher_tEJN9QtPrivate20TypeAndForceCompleteI11PathWatcherNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EESA_SA_EE` | 0x1bbca0 | 40 |
| `_ZN11PathWatcher16staticMetaObjectE` | 0x1bbcc8 | 56 |
| `_ZTV11PathWatcher` | 0x1bbe40 | 112 |
| `_ZTI11PathWatcher` | 0x1bbeb0 | 24 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_ProdInfo_tEJN9QtPrivate20TypeAndForceCompleteI7QStringNSt3__117integral_constantIbLb1EEEEENS3_IhS7_EES9_NS3_IjS7_EENS3_I5QListIiES7_EES9_S9_S9_S9_S9_SD_SD_SD_SA_S9_S9_S9_S9_SA_SA_SA_SD_SD_S9_S9_NS3_ISB_I8QVariantES7_EESD_NS3_IiS7_EESD_S9_SA_NS3_I8ProdInfoS7_EEEE` | 0x1bbfa0 | 256 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_125qt_meta_stringdata_Unrd_tEJN9QtPrivate20TypeAndForceCompleteI4UnrdNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IbS9_EESA_SA_EE` | 0x1bcc28 | 40 |
| `_ZN4Unrd16staticMetaObjectE` | 0x1bcc50 | 56 |
| `_ZTV4Unrd` | 0x1bcc88 | 112 |
| `_ZTI4Unrd` | 0x1bccf8 | 24 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI11PathWatcherE8metaTypeE` | 0x1c32b0 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI4UnrdE8metaTypeE` | 0x1c6d50 | 112 |
| `_ZN12_GLOBAL__N_113kSuVariantTagE` | 0x1c8240 | 24 |

**Removed objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_ProdInfo_tEJN9QtPrivate20TypeAndForceCompleteI7QStringNSt3__117integral_constantIbLb1EEEEENS3_IhS7_EES9_NS3_IjS7_EENS3_I5QListIiES7_EES9_S9_S9_S9_S9_SD_SD_SD_SA_S9_S9_S9_S9_SA_SA_SA_SD_SD_S9_S9_NS3_ISB_I8QVariantES7_EESD_NS3_IiS7_EESD_S9_NS3_I8ProdInfoS7_EEEE` | 0x1ac188 | 248 |

### `/bin/prodconfig-tool`

+44 / −0 functions · +20 / −1 objects

**New functions (44)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QArrayDataPointerIP11PathWatcherE20tryReadjustFreeSpaceEN10QArrayData14GrowthPositionExPPKS1_` | 0x1b920 | 292 |
| `_ZN17QArrayDataPointerIP11PathWatcherE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x1ba48 | 460 |
| `_ZN17QArrayDataPointerIP11PathWatcherE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0x1bc18 | 372 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI11PathWatcherE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x1e0e0 | 16 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI4UnrdE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x1e0e0 | 16 |
| `_ZN8ProdInfo12setSuVariantEj` | 0x24cf0 | 448 |
| `_ZN4Unrd18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x296d8 | 260 |
| `_ZN4Unrd12validChangedEb` | 0x297e0 | 100 |
| `_ZN4Unrd10initFailedEv` | 0x29848 | 20 |
| `_ZNK4Unrd10metaObjectEv` | 0x29860 | 28 |
| `_ZN4Unrd11qt_metacastEPKc` | 0x29880 | 84 |
| `_ZN4Unrd11qt_metacallEN11QMetaObject4CallEiPPv` | 0x298d8 | 252 |
| `_ZN4UnrdD2Ev` | 0x299d8 | 92 |
| `_ZN4UnrdD0Ev` | 0x29a38 | 100 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI4UnrdE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x29aa0 | 12 |
| `_Z8set_unrdPKcS0_` | 0x29ab0 | 820 |
| `_ZL11openContextR13UnrdContext_t` | 0x29de8 | 856 |
| `_ZL14releaseContextRK13UnrdContext_t` | 0x2a140 | 348 |
| `_ZN4UnrdC1EP7QObject` | 0x2a2a0 | 792 |
| `_ZN4UnrdC2EP7QObject` | 0x2a2a0 | 792 |
| `_ZN4Unrd8setValidEb` | 0x2a5b8 | 416 |
| `_ZN4Unrd10addWatcherERK7QString` | 0x2a758 | 1056 |
| `_ZN4Unrd10checkValidEv` | 0x2ab78 | 932 |
| `_ZN4Unrd3setEPKcS1_` | 0x2af20 | 464 |
| `_ZN9QtPrivate11QSlotObjectIM4UnrdFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x2b0f0 | 116 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN4Unrd10addWatcherERK7QStringE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x2b168 | 516 |
| `_ZN9QtPrivate12QPodArrayOpsIP11PathWatcherE7emplaceIJRS2_EEEvxDpOT_` | 0x2b370 | 424 |
| `_ZN11PathWatcher18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x2b518 | 248 |
| `_ZN11PathWatcher11pathChangedERK7QString` | 0x2b610 | 88 |
| `_ZN11PathWatcher7timeoutEv` | 0x2b668 | 20 |
| `_ZNK11PathWatcher10metaObjectEv` | 0x2b680 | 28 |
| `_ZN11PathWatcher11qt_metacastEPKc` | 0x2b6a0 | 84 |
| `_ZN11PathWatcher11qt_metacallEN11QMetaObject4CallEiPPv` | 0x2b6f8 | 240 |
| `_ZN11PathWatcherD2Ev` | 0x2b7e8 | 220 |
| `_ZN11PathWatcherD0Ev` | 0x2b8c8 | 228 |
| `_ZN11PathWatcherC1EP7QObjectRK7QStringi` | 0x2ccf8 | 828 |
| `_ZN11PathWatcherC2EP7QObjectRK7QStringi` | 0x2ccf8 | 828 |
| `_ZN11PathWatcher18onWatchPathChangedEv` | 0x2d038 | 380 |
| `_ZN11PathWatcher5startEv` | 0x2d1b8 | 248 |
| `_ZN11PathWatcher9watchPathE7QString` | 0x2d2b0 | 1284 |
| `_ZN5QListI7QStringE5clearEv` | 0x2d7b8 | 340 |
| `_ZN11PathWatcher14addToWatchListERK7QString` | 0x2d910 | 452 |
| `_ZN9QtPrivate11QSlotObjectIM11PathWatcherFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x2dad8 | 116 |
| `_ZN9QtPrivate16QMovableArrayOpsI7QStringE7emplaceIJRKS1_EEEvxDpOT_` | 0x2db50 | 648 |

**New objects (20)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12_GLOBAL__N_123qt_meta_stringdata_UnrdE` | 0x3e28c | 96 |
| `_ZL17qt_meta_data_Unrd` | 0x3e2ec | 152 |
| `_ZTS4Unrd` | 0x3e384 | 6 |
| `_ZN9QtPrivate16QMetaTypeForTypeI4UnrdE4nameE` | 0x3e38a | 5 |
| `_ZN12_GLOBAL__N_130qt_meta_stringdata_PathWatcherE` | 0x3e390 | 108 |
| `_ZL24qt_meta_data_PathWatcher` | 0x3e3fc | 152 |
| `_ZTS11PathWatcher` | 0x3e494 | 14 |
| `_ZN9QtPrivate16QMetaTypeForTypeI11PathWatcherE4nameE` | 0x3e4a2 | 12 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_ProdInfo_tEJN9QtPrivate20TypeAndForceCompleteI7QStringNSt3__117integral_constantIbLb1EEEEENS3_IhS7_EES9_NS3_IjS7_EENS3_I5QListIiES7_EES9_S9_S9_S9_S9_SD_SD_SD_SA_S9_S9_S9_S9_SA_SA_SA_SD_SD_S9_S9_NS3_ISB_I8QVariantES7_EESD_NS3_IiS7_EESD_S9_SA_NS3_I8ProdInfoS7_EEEE` | 0x5e620 | 256 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_125qt_meta_stringdata_Unrd_tEJN9QtPrivate20TypeAndForceCompleteI4UnrdNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IbS9_EESA_SA_EE` | 0x5e9d8 | 40 |
| `_ZN4Unrd16staticMetaObjectE` | 0x5ea00 | 56 |
| `_ZTV4Unrd` | 0x5ea38 | 112 |
| `_ZTI4Unrd` | 0x5eaa8 | 24 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PathWatcher_tEJN9QtPrivate20TypeAndForceCompleteI11PathWatcherNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EESA_SA_EE` | 0x5eac0 | 40 |
| `_ZN11PathWatcher16staticMetaObjectE` | 0x5eae8 | 56 |
| `_ZTV11PathWatcher` | 0x5eb20 | 112 |
| `_ZTI11PathWatcher` | 0x5eb90 | 24 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI4UnrdE8metaTypeE` | 0x60160 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI11PathWatcherE8metaTypeE` | 0x601d0 | 112 |
| `_ZN12_GLOBAL__N_113kSuVariantTagE` | 0x602e0 | 24 |

**Removed objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_ProdInfo_tEJN9QtPrivate20TypeAndForceCompleteI7QStringNSt3__117integral_constantIbLb1EEEEENS3_IhS7_EES9_NS3_IjS7_EENS3_I5QListIiES7_EES9_S9_S9_S9_S9_SD_SD_SD_SA_S9_S9_S9_S9_SA_SA_SA_SD_SD_S9_S9_NS3_ISB_I8QVariantES7_EESD_NS3_IiS7_EESD_S9_NS3_I8ProdInfoS7_EEEE` | 0x5e970 | 248 |

### `/lib64/weston/eagle-backend.so`

+23 / −0 functions · +0 / −0 objects

**New functions (23)**

| Symbol | Addr | Size |
|---|---|---|
| `eagle_renderer_get_su_variant` | 0x953c0 | 392 |
| `unrd_open` | 0xa7838 | 16 |
| `unrd_close` | 0xa7848 | 32 |
| `unrd_alloc_handle` | 0xa7868 | 152 |
| `unrd_release_handle` | 0xa7900 | 108 |
| `unrd_get_version` | 0xa7970 | 164 |
| `unrd_set_version` | 0xa7a18 | 140 |
| `unrd_set_int32` | 0xa7aa8 | 360 |
| `unrd_get_int32` | 0xa7c10 | 360 |
| `unrd_set_int64` | 0xa7d78 | 348 |
| `unrd_get_int64` | 0xa7ed8 | 356 |
| `unrd_set_float32` | 0xa8040 | 336 |
| `unrd_get_float32` | 0xa8190 | 360 |
| `unrd_set_float64` | 0xa82f8 | 336 |
| `unrd_get_float64` | 0xa8448 | 356 |
| `unrd_set_string` | 0xa85b0 | 352 |
| `unrd_get_string` | 0xa8710 | 328 |
| `unrd_set_binary` | 0xa8858 | 340 |
| `unrd_get_binary` | 0xa89b0 | 372 |
| `unrd_get_length` | 0xa8b28 | 304 |
| `unrd_flush` | 0xa8c58 | 108 |
| `unrd_delete` | 0xa8cc8 | 204 |
| `unrd_clear` | 0xa8d98 | 108 |

### `/bin/camera-service`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZlsIiiENSt3__19enable_ifIXsr3stdE13conjunction_vIN11QTypeTraits20has_ostream_operatorI6QDebugT_vEENS3_IS4_T0_vEEEES4_E4typeES4_RKNS0_4pairIS5_S7_EE` | 0x218ee8 | 300 |

### `/bin/phocus`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN8V1Client24deviceIdDirectoryChangedEv` | 0xe1ba0 | 1248 |

### `/bin/camera-upgrade`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_amt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_blackbox`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sec`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/as7341.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/ask_dsp_driver.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/atmel_mxt_ts.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/bcmdhd.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/bluetooth.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/cam_vreg.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/camecg_drv.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/cfg80211.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/designware_i2s.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji-spinor.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_dw_hdmi_i2s_audio.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_j2kcodec.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_jpegxrcodec.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_ljcodec.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_mctf.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_msdec.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_msenc.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_proresDec.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_proresEnc.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dji_ycc.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dwc_eth_qos.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/dwmac-dwc-qos-eth.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/e1000e.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/eagle_dsp.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/ecx337aa.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/focaltech_tp.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/focaltp.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/ftdi_sio.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/goodix_core.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/gspca_main.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/hci_uart.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/himax_tp.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/icc_chnl.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/ili2120.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/l3ej03110a.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/leds-pwm.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/mac80211.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/mmc_test.ko`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **407** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/camera-gui`

<details><summary>新增 117 条字符串, 展示前 100 条</summary>

````text
"@jK99
"t2BO)4
"y@6tp
#AqI!1
#DCc7t.?f
#DCyc$/#c
#|aQGA/
$xdN NO
%dhZAB
&DqYUG
'Es#sp
'Ic#sp
'd=1Vqm7
)_kmu=
+so2 ?x
+u/Kv/K~
,mll.krZC\l
-Fi%+r/
-o:cb2
.Pmxx-u
/KK :2
0b,M{85
1(A_M))
159KDWr
33Njfu
457)mB&
5Q&avPux^
6?5c95;
74NCmAM
8!,v.8
9#35[AaC
9vj;,U
:'EGTDSl
:VnTB)T!D
;BLll(
=cJ=cNG
?LensData*
@K3"NM
@p_);7
A)O&2/
BJSra/
DS2O%d
Ee(b<ny`
F}iI|mQ
HX1J+9
HcD+!t:
IhaEjp
JR.K^\/
J{0XVv
Ke4c@j
Kfy/,n
L1_,K:
L2y/Q^'
M,D;WJ
M9fCr-
MHJ'i)30
MbTHVQ
Mj@w0O
N-x\GK
NwCnc[c0
OYTqp^}
P0`fp7
QAbstractListModel*
QS$EEq
S2pE-PR
TM&@,B
UqjEeY
V048jy
VWwg,Vq
WI[faB/
WZ<.1%b)
X~Bq,Q
[MyD93H
\L]H-gdEg
]#4zPaUE
^wH/yu
cMc/<2u
d3 Wqf\L
dS.ZBe>
d`vf3G
dexT3T-
eo1TH8
gNDxc6
gUmA5!
h4pFJ<
jmIW{b3
kZe+(q
kqk;[/iM
lnjL3>"5
lnv|:olT
nbj!!m1
n{sA,c
oo9DmlL
p8gv5Uf
q(D"vZe
qI;)iZ
qZC5>C
r&x;489
rJ:O>Z
rWB<_N
````

</details>

> 其余 17 条见 `result.json`。

### `/bin/prodconfig-tool`

<details><summary>新增 72 条字符串</summary>

````text
/dev/block/by-name/env
/dev/unrd
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/helpers/unrd/unrd.cpp
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/libs/appscommon/pathwatcher.cpp
11PathWatcher
<empty>
<exists>
<failed to get value>
<not set>
Failed to add path
Failed waiting for unrd path
Identity/SuVariant
No root path found:
PathWatcher
Set SU variant
SuVariant:                      
Unrd is valid
Unrd still not valid
Wait for unrd path
_ZN11QTextStreamlsEPKc
_ZNSt3__19to_stringEj
auto Unrd::addWatcher(const QString &)::(anonymous class)::operator()() const
b12bdc09
bool openContext(UnrdContext &)
checkValid
exit, ret:
failed
initFailed
int Unrd::clear(const char *)
int Unrd::getClear(const char *, char *, int)
int Unrd::set(const char *, const char *)
int clear_unrd(const char *)
int read_unrd(const char *, char *, size_t)
int set_unrd(const char *, const char *)
len to value not valid
libunrd.so
libunrd_v_lz
onWatchPathChanged
open()
pathChanged
result:
return set_unrd
su-variant
suVariant
su_variant
tag  NULL
tag NULL
tag or value NULL
timeout
unrd_alloc_handle
unrd_alloc_handle failed
unrd_close
unrd_delete
unrd_delete failed
unrd_flush
unrd_flush failed
unrd_get_length
unrd_get_string
unrd_open
unrd_release_handle
unrd_release_handle failed
unrd_set_string
unrd_set_string failed
validChanged
value:
variant
void PathWatcher::addToWatchList(const QString &)
void PathWatcher::watchPath(QString)
void Unrd::addWatcher(const QString &)
void Unrd::checkValid()
void Unrd::setValid(bool)
void releaseContext(const UnrdContext &)
````

</details>

### `/bin/camera-test`

<details><summary>新增 65 条字符串</summary>

````text
/dev/block/by-name/env
/dev/unrd
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/helpers/unrd/unrd.cpp
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/libs/appscommon/pathwatcher.cpp
11PathWatcher
<empty>
<exists>
<failed to get value>
<not set>
Dropping pixel out of geomoetry
Failed to add path
Failed waiting for unrd path
ISCToolStatus Calibration::findHighContrastPixels(memory_allocator_callback *, const uint16_t *, const uint16_t, const unsigned int, const unsigned int, const unsigned int, const unsigned int, std::list<HighContrastPixel> &, const Crop &, const ImageMask &)
Identity/SuVariant
No root path found:
PathWatcher
SuVariant:                      
Unrd is valid
Unrd still not valid
Wait for unrd path
auto Unrd::addWatcher(const QString &)::(anonymous class)::operator()() const
bool openContext(UnrdContext &)
checkValid
exit, ret:
initFailed
int Unrd::clear(const char *)
int Unrd::getClear(const char *, char *, int)
int Unrd::set(const char *, const char *)
int clear_unrd(const char *)
int read_unrd(const char *, char *, size_t)
int set_unrd(const char *, const char *)
len to value not valid
libunrd.so
libunrd_v_lz
onWatchPathChanged
open()
pathChanged
result:
return set_unrd
suVariant
su_variant
tag  NULL
tag NULL
tag or value NULL
unrd_alloc_handle
unrd_alloc_handle failed
unrd_close
unrd_delete
unrd_delete failed
unrd_flush
unrd_flush failed
unrd_get_length
unrd_get_string
unrd_open
unrd_release_handle
unrd_release_handle failed
unrd_set_string
unrd_set_string failed
value:
void PathWatcher::addToWatchList(const QString &)
void PathWatcher::watchPath(QString)
void Unrd::addWatcher(const QString &)
void Unrd::checkValid()
void Unrd::setValid(bool)
void releaseContext(const UnrdContext &)
````

</details>

### `/bin/camera-system`

<details><summary>新增 63 条字符串</summary>

````text
/dev/block/by-name/env
/dev/unrd
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/helpers/unrd/unrd.cpp
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/libs/appscommon/pathwatcher.cpp
11PathWatcher
<exists>
<failed to get value>
<not set>
Failed to add path
Failed waiting for unrd path
Identity/SuVariant
No root path found:
PathWatcher
SuVariant:                      
Unrd is valid
Unrd still not valid
Wait for unrd path
_ZNSt3__19to_stringEj
auto Unrd::addWatcher(const QString &)::(anonymous class)::operator()() const
bool openContext(UnrdContext &)
checkValid
exit, ret:
failed
initFailed
int Unrd::clear(const char *)
int Unrd::getClear(const char *, char *, int)
int Unrd::set(const char *, const char *)
int clear_unrd(const char *)
int read_unrd(const char *, char *, size_t)
int set_unrd(const char *, const char *)
len to value not valid
libunrd.so
libunrd_v_lz
onWatchPathChanged
open()
pathChanged
return set_unrd
suVariant
su_variant
tag  NULL
tag NULL
tag or value NULL
unrd_alloc_handle
unrd_alloc_handle failed
unrd_close
unrd_delete
unrd_delete failed
unrd_flush
unrd_flush failed
unrd_get_length
unrd_get_string
unrd_open
unrd_release_handle
unrd_release_handle failed
unrd_set_string
unrd_set_string failed
validChanged
void PathWatcher::addToWatchList(const QString &)
void PathWatcher::watchPath(QString)
void Unrd::addWatcher(const QString &)
void Unrd::checkValid()
void Unrd::setValid(bool)
void releaseContext(const UnrdContext &)
````

</details>

### `/lib64/weston/eagle-backend.so`

<details><summary>新增 62 条字符串</summary>

````text
 "#$&'(*+,-.012356789:<=>?@ABDEFGHIJKMNOPQRSTUVWXZ[\]^_`abcdefghijklmnoprstuvwxyz{|}~
#5FXk}
%s: Failed to alloc handle
%s: Failed to open unrd
%s: Failed to read tag: %s
%s: Updated SU variant to: %d
+bbbbbbR
/dev/block/by-name/env
/dev/unrd
:bbbbbTC
=bbbbbSB
?QQQQQQ(
Dbbbbbb7
LLLLLLLLLL
LLLLLLLLLL5
NO tag input
No tag input
QQQQQQQ
The tag is NULL!
WLLLLLLLLL<
[YYYYYYYYYYY
bbbbbQ@
bbbbb[K4
eagle_renderer_get_su_variant
get %s value %10.8lf
get %s value %f
get %s value 0x%lx
get %s value 0x%x
malloc size %d failed(%s)
set %s to %10.8lf
set %s to %f
set %s to 0x%lx
set %s to 0x%x
set version to 0x%x
su_variant
tag  or value is NULL
tag is NULL
tag or value is NULL
tag or value is NuLL
unrd_alloc_handle
unrd_clear
unrd_close
unrd_delete
unrd_flush
unrd_get_binary
unrd_get_float32
unrd_get_float64
unrd_get_int32
unrd_get_int64
unrd_get_length
unrd_get_string
unrd_get_version
unrd_open
unrd_release_handle
unrd_set_binary
unrd_set_float32
unrd_set_float64
unrd_set_int32
unrd_set_int64
unrd_set_string
unrd_set_version
version is 0x%x
````

</details>

### `/bin/phocus`

````text
Failed to watch:
Will start watch:
_ZN18QFileSystemWatcher10removePathERK7QString
_ZNK18QFileSystemWatcher5filesEv
_ZNK4QDir4pathEv
void V1Client::deviceIdDirectoryChanged()
````

### `/lib64/libduml_frwk.so`

````text
20:05:13
20:05:14
20:05:15
Jun 18 2024
````

### `/lib64/libduml_orte.so`

````text
20:06:52
Jun 18 2024
orte 0.3.4, compiled: Jun 18 2024 20:06:52
````

### `/lib64/libgip.so`

````text
?N3GIP10FilterPrivE
AB30RG16NV12NV16YU12YU24IMG4IMG3#version 320 es
N3GIP19GammaEncodeDLogBaseE
````

### `/bin/dji_amt`

````text
20:06:46
Jun 18 2024
````

### `/bin/dji_blackbox`

````text
20:06:47
Jun 18 2024
````

### `/bin/dji_sys`

````text
20:08:37
Jun 18 2024
````

### `/lib64/libdcam_pp.so`

````text
20:06:03
Jun 18 2024
````

### `/lib64/libproxy_nn_client.so`

````text
20:08:35
Jun 18 2024
````

### `/bin/camera-service`

````text
Dropping out of geometry spot pixel:
````

### `/lib64/librcam.so`

````text
b12bdc09
````

### `/bin/camera-upgrade`

````text
````

### `/bin/dji_sec`

````text
````

### `/lib/modules/as7341.ko`

````text
````

### `/lib/modules/ask_dsp_driver.ko`

````text
````

### `/lib/modules/atmel_mxt_ts.ko`

````text
````

### `/lib/modules/bcmdhd.ko`

````text
````

### `/lib/modules/bluetooth.ko`

````text
````

### `/lib/modules/cam_vreg.ko`

````text
````

### `/lib/modules/camecg_drv.ko`

````text
````

### `/lib/modules/cfg80211.ko`

````text
````

### `/lib/modules/designware_i2s.ko`

````text
````

### `/lib/modules/dji-spinor.ko`

````text
````

### `/lib/modules/dji_dw_hdmi_i2s_audio.ko`

````text
````

### `/lib/modules/dji_j2kcodec.ko`

````text
````

### `/lib/modules/dji_jpegxrcodec.ko`

````text
````

### `/lib/modules/dji_ljcodec.ko`

````text
````

### `/lib/modules/dji_mctf.ko`

````text
````

### `/lib/modules/dji_msdec.ko`

````text
````

### `/lib/modules/dji_msenc.ko`

````text
````

### `/lib/modules/dji_proresDec.ko`

````text
````

### `/lib/modules/dji_proresEnc.ko`

````text
````

### `/lib/modules/dji_ycc.ko`

````text
````

### `/lib/modules/dwc_eth_qos.ko`

````text
````

### `/lib/modules/dwmac-dwc-qos-eth.ko`

````text
````

### `/lib/modules/e1000e.ko`

````text
````

### `/lib/modules/eagle_dsp.ko`

````text
````

### `/lib/modules/ecx337aa.ko`

````text
````

### `/lib/modules/focaltech_tp.ko`

````text
````

### `/lib/modules/focaltp.ko`

````text
````

### `/lib/modules/ftdi_sio.ko`

````text
````

### `/lib/modules/goodix_core.ko`

````text
````

### `/lib/modules/gspca_main.ko`

````text
````

### `/lib/modules/hci_uart.ko`

````text
````

### `/lib/modules/himax_tp.ko`

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
 
-ro.vendor.build.date=Sat May 25 00:14:56 CST 2024
-ro.vendor.build.date.utc=1716567296
-ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/13682:userdebug/test-keys
+ro.vendor.build.date=Tue Jun 18 20:03:50 CST 2024
+ro.vendor.build.date.utc=1718712230
+ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/14160:userdebug/test-keys
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
-ro.dji.build.version=10.00.19.05
+ro.dji.build.version=10.00.19.07
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
| `/bin/camera-expose` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 MB | 2.3 MB | +0 B | system |
| `/bin/camera-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.3 MB | 45.3 MB | -32 B | system |
| `/bin/camera-service` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.8 MB | 10.8 MB | +280 B | system |
| `/bin/camera-storage` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 MB | 3.3 MB | +0 B | system |
| `/bin/camera-system` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 MB | 7.6 MB | +7.1 KB | system |
| `/bin/camera-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.6 MB | +71.1 KB | system |
| `/bin/camera-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +0 B | system |
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
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 876.8 KB | 876.8 KB | +0 B | system |
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
| `/bin/hex-writer` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 786.2 KB | 786.2 KB | +0 B | system |
| `/bin/ibistool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | system |
| `/bin/imgtool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 879.2 KB | 879.2 KB | +0 B | system |
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
| `/bin/msg2dbus` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 MB | 2.7 MB | +0 B | system |
| `/bin/nnf_gtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525.3 KB | 525.3 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.6 KB | 133.6 KB | +0 B | system |
| `/bin/odindb-send` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 MB | 4.0 MB | +0 B | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 MB | 8.3 MB | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.1 MB | 3.1 MB | +64.3 KB | system |
| `/bin/phocusv1tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 341.3 KB | 341.3 KB | +0 B | system |
| `/bin/pidstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 867.0 KB | 867.0 KB | +0 B | system |
| `/bin/ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/pinmux` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/bin/proc_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 409.1 KB | 416.2 KB | +7.1 KB | system |
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
| `/bin/wmstool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
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
| `/etc/firmware/exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +0 B | system |
| `/etc/firmware/exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B | system |
| `/etc/firmware/goodix_cfg_group.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 930 B | 930 B | +0 B | system |
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
| `/etc/sepolicy.dbg` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 437.5 KB | 437.5 KB | +12 B | system |
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
| `/lib/modules/as7341.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 323.7 KB | 323.7 KB | +0 B | system |
| `/lib/modules/ask_dsp_driver.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 627.2 KB | 627.2 KB | +0 B | system |
| `/lib/modules/atmel_mxt_ts.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 411.7 KB | 411.7 KB | +0 B | system |
| `/lib/modules/bcmdhd.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +0 B | system |
| `/lib/modules/bluetooth.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.4 MB | 7.4 MB | +0 B | system |
| `/lib/modules/cam_vreg.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.5 KB | 37.5 KB | +0 B | system |
| `/lib/modules/camecg_drv.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 355.5 KB | 355.5 KB | +0 B | system |
| `/lib/modules/cfg80211.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 MB | 7.3 MB | +0 B | system |
| `/lib/modules/designware_i2s.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 347.0 KB | 347.0 KB | +0 B | system |
| `/lib/modules/dji-spinor.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 274.3 KB | 274.3 KB | +0 B | system |
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 373.9 KB | 373.9 KB | +0 B | system |
| `/lib/modules/dji_j2kcodec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 619.8 KB | 619.8 KB | +0 B | system |
| `/lib/modules/dji_jpegxrcodec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 279.7 KB | 279.7 KB | +0 B | system |
| `/lib/modules/dji_ljcodec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 552.2 KB | 552.2 KB | +0 B | system |
| `/lib/modules/dji_mctf.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.4 KB | 125.4 KB | +0 B | system |
| `/lib/modules/dji_msdec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 410.7 KB | 410.7 KB | +0 B | system |
| `/lib/modules/dji_msenc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 279.8 KB | 279.8 KB | +0 B | system |
| `/lib/modules/dji_proresDec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 276.3 KB | 276.3 KB | +0 B | system |
| `/lib/modules/dji_proresEnc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 702.7 KB | 702.7 KB | +0 B | system |
| `/lib/modules/dji_ycc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib/modules/dwc_eth_qos.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 540.9 KB | 540.9 KB | +0 B | system |
| `/lib/modules/dwmac-dwc-qos-eth.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 309.6 KB | 309.6 KB | +0 B | system |
| `/lib/modules/e1000e.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.9 MB | 3.9 MB | +0 B | system |
| `/lib/modules/eagle_dsp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 559.1 KB | 559.1 KB | +0 B | system |
| `/lib/modules/ecx337aa.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 272.2 KB | 272.2 KB | +0 B | system |
| `/lib/modules/focaltech_tp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.7 MB | 2.7 MB | +0 B | system |
| `/lib/modules/focaltp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/ftdi_sio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 503.8 KB | 503.8 KB | +0 B | system |
| `/lib/modules/goodix_core.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/lib/modules/gspca_main.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 622.0 KB | 622.0 KB | +0 B | system |
| `/lib/modules/hci_uart.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib/modules/himax_tp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/modules/icc_chnl.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib/modules/ili2120.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 263.1 KB | 263.1 KB | +0 B | system |
| `/lib/modules/l3ej03110a.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 274.9 KB | 274.9 KB | +0 B | system |
| `/lib/modules/leds-pwm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 239.1 KB | 239.1 KB | +0 B | system |
| `/lib/modules/mac80211.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.1 MB | 20.1 MB | +0 B | system |
| `/lib/modules/mmc_test.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 511.5 KB | 511.5 KB | +0 B | system |
| `/lib/modules/proresenc_mod.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 273.9 KB | 273.9 KB | +0 B | system |
| `/lib/modules/pvrsrvkm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.2 MB | 2.2 MB | +0 B | system |
| `/lib/modules/r8152.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 646.7 KB | 646.7 KB | +0 B | system |
| `/lib/modules/realtek.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 248.1 KB | 248.1 KB | +0 B | system |
| `/lib/modules/snd-hwdep.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 294.5 KB | 294.5 KB | +0 B | system |
| `/lib/modules/snd-rawmidi.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.8 KB | 403.8 KB | +0 B | system |
| `/lib/modules/snd-soc-ak5522.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 350.4 KB | 350.4 KB | +0 B | system |
| `/lib/modules/snd-soc-ak7755.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 525.0 KB | 525.0 KB | +0 B | system |
| `/lib/modules/snd-soc-aw87519.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 350.4 KB | 350.4 KB | +0 B | system |
| `/lib/modules/snd-soc-aw8896.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 694.5 KB | 694.5 KB | +0 B | system |
| `/lib/modules/snd-soc-cs47l35.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.1 MB | 2.1 MB | +0 B | system |
| `/lib/modules/snd-soc-dji-dummy-codec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 273.6 KB | 273.6 KB | +0 B | system |
| `/lib/modules/snd-soc-nau8821.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 428.1 KB | 428.1 KB | +0 B | system |
| `/lib/modules/snd-soc-nau8825.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 459.1 KB | 459.1 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card-utils.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 284.4 KB | 284.4 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 339.0 KB | 339.0 KB | +0 B | system |
| `/lib/modules/snd-soc-tlv320aic31xx.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.9 KB | 380.9 KB | +0 B | system |
| `/lib/modules/snd-usb-audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +0 B | system |
| `/lib/modules/snd-usbmidi-lib.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 337.5 KB | 337.5 KB | +0 B | system |
| `/lib/modules/tc358749.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 554.5 KB | 554.5 KB | +0 B | system |
| `/lib/modules/test_bitmap.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 188.2 KB | 188.2 KB | +0 B | system |
| `/lib/modules/test_bpf.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/test_firmware.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.7 KB | 218.7 KB | +0 B | system |
| `/lib/modules/test_printf.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 193.7 KB | 193.7 KB | +0 B | system |
| `/lib/modules/test_static_key_base.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 158.7 KB | 158.7 KB | +0 B | system |
| `/lib/modules/test_static_keys.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 169.9 KB | 169.9 KB | +0 B | system |
| `/lib/modules/test_user_copy.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 184.3 KB | 184.3 KB | +0 B | system |
| `/lib/modules/vc_decoder.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 405.9 KB | 405.9 KB | +0 B | system |
| `/lib/modules/vc_encoder.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 434.8 KB | 434.8 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_h26x_core0.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 232.6 KB | 232.6 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_h26x_core1.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 232.6 KB | 232.6 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_jpeg.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 242.7 KB | 242.7 KB | +0 B | system |
| `/lib/modules/vcam_driver.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +0 B | system |
| `/lib/modules/vision_cnn.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 588.0 KB | 588.0 KB | +0 B | system |
| `/lib/modules/vision_sgbm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 414.9 KB | 414.9 KB | +0 B | system |
| `/lib/modules/vision_vcr.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 590.1 KB | 590.1 KB | +0 B | system |
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
| `/lib64/libMessageTransport.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
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
| `/lib64/libaaa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 MB | 10.1 MB | +8 B | system |
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
| `/lib64/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.3 MB | -8 B | system |
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
| `/lib64/libdji_codec_heif.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.7 KB | 131.8 KB | +8 B | system |
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
| `/lib64/librcam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | -16 B | system |
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
| `/lib64/weston/eagle-backend.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 2.0 MB | +256.1 KB | system |
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
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | +13 B | system |
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
