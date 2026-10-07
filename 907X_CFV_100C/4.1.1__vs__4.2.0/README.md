# 907X & CFV 100C: 4.1.1 ➜ 4.2.0

> 生成时间: 2026-10-07T05:25:58 · CIM 日期: 2025-04-21 ➜ 2025-10-31 · 条目: 8 ➜ 8 · 源: `CFV_100C_v4_1_1.cim` ➜ `CFV_100C_v4_2_0.cim`

## Summary

文件树 +1/-0/~202；CIM 条目 +0/-0/~5；OTA 镜像 ~7 变更 / 0 未变；符号 +436/-428 funcs, +65/-65 objs；新增字符串 266 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B |
| `exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 414.8 KB | 415.2 KB | +392 B |
| `exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +672 B |
| `exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 165.2 MB | 165.2 MB | +10.1 KB |
| `ec2107_cpld.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B |
| `hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.5 KB | 13.5 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.1 KB | 7.1 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 5 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 3

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 544.0 KB | 544.0 KB | +0 B |
| `gimbal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 355.3 KB | 351.3 KB | -4.1 KB |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 18.8 MB | 18.8 MB | -96 B |
| `scp.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.4 KB | 89.4 KB | +0 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 512.0 MB | 512.0 MB | +0 B |
| `tos.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 449.7 KB | 449.7 KB | +0 B |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.3 MB | 45.3 MB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 7 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `lib` | 0 | 0 | 75 | 0 | 0 |
| `lib64` | 0 | 0 | 58 | 232 | 0 |
| `bin` | 1 | 0 | 24 | 323 | 0 |
| `model` | 0 | 0 | 23 | 0 | 0 |
| `etc` | 0 | 0 | 14 | 169 | 0 |
| `(root)` | 0 | 0 | 3 | 2 | 0 |
| `firmware` | 0 | 0 | 3 | 11 | 0 |
| `ta` | 0 | 0 | 2 | 0 | 0 |
| `product` | 0 | 0 | 0 | 1 | 0 |
| `usr` | 0 | 0 | 0 | 14 | 0 |
| `xbin` | 0 | 0 | 0 | 10 | 0 |

明细 965 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+436 / −428** functions, **+65 / −65** objects（50 个变更 ELF, 另有 105 个未列出）。

### `/bin/camera-gui`

+63 / −94 functions · +12 / −12 objects

**New functions (63)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x3305c8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x330928 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x330930 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x330930 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x330940 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x330958 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x330a08 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x330a18 | 12 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x41b988 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_PopupBackground_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x41c2a0 | 244 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_components_TemperatureStatus_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42f828 | 296 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_components_TextCheckbox_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4319b0 | 244 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_TiledImage_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x43ab40 | 44 |
| `_ZZNK21QmlCacheGeneratedCode34_app_qml_components_TiledImage_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x43b3c8 | 260 |
| `_ZN21QmlCacheGeneratedCode54_app_qml_components_buttons_BracketedCameraControl_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x44f740 | 240 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x470b50 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_controlscreen_IsoSetting_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x471058 | 484 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_FaceIndicator_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49ac40 | 256 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_IsoWBSelector_qml4$_808__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ac670 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_liveview_IsoWBSelector_qml4$_80clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4b1ff0 | 260 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dc3c8 | 44 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dc3f8 | 468 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dc5d0 | 544 |
| `_ZZNK21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4dcd00 | 256 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dd2f0 | 44 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4dd320 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_11clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4de728 | 244 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4de820 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_188__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e0380 | 44 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_278__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e05f8 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_288__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e06f0 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_308__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e08e0 | 244 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4e1ad8 | 328 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml4$_748__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ebcb8 | 264 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_mainmenu_LicenseView_qml4$_178__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f57d0 | 256 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x50c418 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x50de80 | 244 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_mainmenu_SpiritLevelView_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x50f650 | 240 |
| `_ZN21QmlCacheGeneratedCode55_app_qml_mainmenu_delegates_ListValueSwitchDelegate_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x516bb0 | 240 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextActionDelegate_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5218d8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_mainmenu_delegates_TextActionDelegate_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x522180 | 224 |
| `_ZN21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x528d60 | 44 |
| `_ZZNK21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x529660 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml4$_398__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x537780 | 132 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml4$_39clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x53b4d8 | 396 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5506d8 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_298__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x550e80 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_438__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5519c0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x552c90 | 244 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_43clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x555be8 | 260 |

<details><summary>… 另 13 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN21QmlCacheGeneratedCode41_app_qml_popups_PopoverExposureAdjust_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x556d58 | 320 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x560238 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x563b70 | 244 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_viewmodels_BrowseViewViewModel_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x57b338 | 256 |
| `_ZN11CameraProxy21ibis_supportedChangedEb` | 0xa48098 | 100 |
| `_ZN11CameraProxy22lens_propertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0xa48a08 | 96 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xa5d9f8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xa5da90 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0xa5da98 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0xa5dc18 | 200 |
| `_ZNK15CameraProxyDbus14ibis_supportedEv` | 0xa929b8 | 48 |
| `_ZNK15CameraProxyDbus15lens_propertiesEv` | 0xa92e68 | 48 |
| `_ZN21QmlCacheGeneratedCode33_imagetest_qml_imagetest_main_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xac89a0 | 256 |

</details>

**Removed functions (94)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x330580 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x3308e0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x3308e8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x3308e8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x3308f8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x330910 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x3309c0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x3309d0 | 12 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_BounceListView_qml4$_238__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3b8290 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_BounceListView_qml4$_23clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3b9608 | 260 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3f2388 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3f33f0 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_components_StatusRow_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42ab78 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42dd80 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42ddb0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x42e608 | 240 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x42e6f8 | 244 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_components_TemperatureStatus_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x42fd30 | 44 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_components_TemperatureStatus_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4304b0 | 244 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_components_TimeoutText_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x43b9e0 | 132 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_components_TimeoutText_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x43bdc0 | 388 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4536c8 | 424 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml4$_198__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4545d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x455d60 | 244 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_IconButton_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x459098 | 44 |
| `_ZZNK21QmlCacheGeneratedCode42_app_qml_components_buttons_IconButton_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x459b18 | 244 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_controlscreen_ApertureSetting_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x46d958 | 44 |
| `_ZZNK21QmlCacheGeneratedCode42_app_qml_controlscreen_ApertureSetting_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x46dd70 | 236 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x474b00 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedSetting_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x475d10 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_exposescreen_ExposeScreen_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x488588 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeProgress_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48a260 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeProgress_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48b188 | 244 |
| `_ZN21QmlCacheGeneratedCode45_app_qml_exposescreen_IntervalTimerScreen_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48f7e0 | 244 |
| `_ZN21QmlCacheGeneratedCode45_app_qml_exposescreen_IntervalTimerScreen_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48fa10 | 252 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_liveview_ApertureIndicator_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x490890 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_liveview_ApertureIndicator_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4912d0 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49e700 | 264 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_liveview_FocusPointTapHandler_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4a58f0 | 240 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_IsoWBSelector_qml4$_228__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ab968 | 256 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_MFAssistDistanceScale_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2440 | 240 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e0c68 | 44 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e0c98 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_318__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e0e88 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_328__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e0f80 | 244 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4e2740 | 696 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4e29f8 | 328 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_ZoomIndicator_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e61d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_liveview_ZoomIndicator_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4e6948 | 244 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4eb348 | 44 |

<details><summary>… 另 44 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4ee1b8 | 260 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_mainmenu_ListSelectorSettings_qml4$_198__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f78b0 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_mainmenu_MenuBoolSelector_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4fafe8 | 256 |
| `_ZN21QmlCacheGeneratedCode48_app_qml_mainmenu_delegates_DropdownDelegate_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x511858 | 44 |
| `_ZZNK21QmlCacheGeneratedCode48_app_qml_mainmenu_delegates_DropdownDelegate_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x512df0 | 244 |
| `_ZN21QmlCacheGeneratedCode55_app_qml_mainmenu_delegates_ListValueSwitchDelegate_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5174c0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode55_app_qml_mainmenu_delegates_ListValueSwitchDelegate_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x518448 | 240 |
| `_ZN21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5294d0 | 44 |
| `_ZN21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_188__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x529680 | 44 |
| `_ZZNK21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_11clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x52a180 | 244 |
| `_ZZNK21QmlCacheGeneratedCode47_app_qml_mainmenu_popups_EvfDiopterSelector_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x52aca8 | 244 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_popups_RecalibrateSensor_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x532470 | 304 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x533a08 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x53fea0 | 44 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_168__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x53fed0 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5429d8 | 232 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x542ac0 | 388 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_318__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5519f0 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_448__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x552428 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_458__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x552458 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_31clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5552d8 | 244 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x556690 | 260 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_45clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x556798 | 260 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_popups_PopoverMeterMethod_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x568900 | 320 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_168__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x56b000 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x56d6f0 | 228 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x570b60 | 44 |
| `_ZZNK21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x571700 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_popups_TransparentConfirm_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x577b70 | 44 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_popups_TransparentConfirm_qml4$_188__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x577de0 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_popups_TransparentConfirm_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5784f8 | 244 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_popups_TransparentConfirm_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x579538 | 388 |
| `_ZN21QmlCacheGeneratedCode29_app_qml_proxies_CameraUI_qml4$_208__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x57a618 | 232 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_viewmodels_BrowseViewViewModel_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x57c650 | 284 |
| `_ZN11CameraProxy25lens_is_af_allowedChangedEb` | 0xa498e0 | 100 |
| `_ZN11CameraProxy25lens_mf_ring_stateChangedEN9HblmTypes17E_LensMfRingStateE` | 0xa49a08 | 96 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xa5eb08 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xa5eba0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0xa5eba8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0xa5ed28 | 200 |
| `_ZNK15CameraProxyDbus18lens_is_af_allowedEv` | 0xa93e60 | 48 |
| `_ZNK15CameraProxyDbus18lens_mf_ring_stateEv` | 0xa93ef0 | 48 |
| `_ZN21QmlCacheGeneratedCode37_touchtest_qml_FreeStyleTouchTest_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xabc880 | 256 |
| `_ZN21QmlCacheGeneratedCode19_sutest_qml_Led_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xad50b8 | 264 |

</details>

**New objects (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x1c8811e | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESS_SS_S7_SS_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESS_NS3_INS8_12E_ExitOptionES6_EESS_SS_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES16_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESS_SS_S7_SS_S7_SS_S7_SS_SS_SS_SS_SS_NS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SS_SS_S1E_SS_NS3_INS8_9E_ExpModeES6_EES10_S7_SS_NS3_INS8_21E_ExposureControlModeES6_EES7_NS3_IyS6_EESS_S1N_NS3_INS8_16E_ExposureStatusES6_EESS_S7_S1G_S7_SH_SS_NS3_INS8_12E_FlashModesES6_EESS_SS_SS_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESH_SH_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESH_S10_NS3_INS8_11E_FocusSizeES6_EES21_NS3_INS8_17E_CameraKeyOptionES6_EESS_S7_S7_SS_SS_SS_S7_S7_NS3_INS8_10E_IbisModeES6_EES7_NS3_INS8_10E_BitDepthES6_EES1I_SS_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SS_SZ_SS_SS_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISE_S6_EESM_S7_S7_S7_SS_S10_SM_S2I_S2I_NS3_INS8_16E_LensPropertiesES6_EES7_S7_S7_SS_SS_S2I_SS_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESS_S2I_NS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EESS_S7_SS_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SS_SM_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S33_NS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESS_SS_SS_SV_SS_SS_SS_SS_S1N_SS_SV_SS_SS_S7_SS_NS3_INS8_14E_DistanceUnitES6_EES1C_SS_SS_SS_SS_NS3_INS8_12E_WhiteModesES6_EESS_SS_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3I_EES3J_NS3_IKNS8_21E_ExposureBlockReasonES3I_EES3J_NS3_IKNS8_21E_LiveviewBlockReasonES3I_EES3J_NS3_IbS3I_EES3J_S3T_S3J_NS3_IS9_S3I_EES3J_NS3_ISB_S3I_EES3J_S3T_S3J_NS3_IRKSG_S3I_EES3J_NS3_ISI_S3I_EES3J_NS3_ISK_S3I_EES3J_NS3_ItS3I_EES3J_NS3_IPKSN_S3I_EES3J_S3T_S3J_S3T_S3J_NS3_ISQ_S3I_EES3J_NS3_IiS3I_EES3J_NS3_IRKSU_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_ISW_S3I_EES3J_S46_S3J_NS3_ISY_S3I_EES3J_S46_S3J_S46_S3J_NS3_IjS3I_EES3J_NS3_IS11_S3I_EES3J_NS3_IS13_S3I_EES3J_NS3_IS15_S3I_EES3J_S4F_S3J_NS3_IS17_S3I_EES3J_NS3_IS19_S3I_EES3J_NS3_IS1B_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS1D_S3I_EES3J_S3T_S3J_S4I_S3J_NS3_IS1F_S3I_EES3J_NS3_IS1H_S3I_EES3J_S3T_S3J_S46_S3J_S46_S3J_S4J_S3J_S46_S3J_NS3_IS1J_S3I_EES3J_S4C_S3J_S3T_S3J_S46_S3J_NS3_IS1L_S3I_EES3J_S3T_S3J_NS3_IyS3I_EES3J_S46_S3J_S4O_S3J_NS3_IS1O_S3I_EES3J_S46_S3J_S3T_S3J_S4K_S3J_S3T_S3J_S3Y_S3J_S46_S3J_NS3_IS1Q_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S4G_S3J_NS3_IS1S_S3I_EES3J_S3Y_S3J_S3Y_S3J_NS3_IS1U_S3I_EES3J_NS3_IS1W_S3I_EES3J_S4C_S3J_NS3_IS1Y_S3I_EES3J_S3Y_S3J_S4C_S3J_NS3_IS20_S3I_EES3J_S4V_S3J_NS3_IS22_S3I_EES3J_S46_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_IS24_S3I_EES3J_S3T_S3J_NS3_IS26_S3I_EES3J_S4L_S3J_S46_S3J_NS3_IS28_S3I_EES3J_NS3_IS2A_S3I_EES3J_S3T_S3J_S46_S3J_S4B_S3J_S46_S3J_S46_S3J_S4C_S3J_NS3_IS2C_S3I_EES3J_NS3_IS2E_S3I_EES3J_NS3_IS2G_S3I_EES3J_NS3_IRKSE_S3I_EES3J_S41_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_S4C_S3J_S41_S3J_S56_S3J_S56_S3J_NS3_IS2J_S3I_EES3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S56_S3J_S46_S3J_S3T_S3J_NS3_IS2L_S3I_EES3J_S4C_S3J_NS3_IRKS2N_S3I_EES3J_S46_S3J_S56_S3J_NS3_IS2P_S3I_EES3J_S4C_S3J_S3T_S3J_NS3_IS2R_S3I_EES3J_NS3_IS2T_S3I_EES3J_NS3_IS2V_S3I_EES3J_S3T_S3J_NS3_IS2X_S3I_EES3J_S46_S3J_S3T_S3J_S46_S3J_S4B_S3J_NS3_IS2Z_S3I_EES3J_NS3_IS31_S3I_EES3J_S3T_S3J_S3T_S3J_S46_S3J_S41_S3J_S3T_S3J_NS3_IsS3I_EES3J_NS3_IS34_S3I_EES3J_S3T_S3J_S5J_S3J_NS3_IS36_S3I_EES3J_NS3_IS38_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S4O_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_NS3_IS3A_S3I_EES3J_S4I_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS3C_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_NS3_IS3E_S3I_EES3J_S4C_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_EE` | 0x20cebe0 | 5248 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x21874f8 | 112 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6c90 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6c98 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6ca0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6ca8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6cb0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6cb8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_22clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6cc0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_22clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6cc8 | 8 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x21ce754 | 4 |

**Removed objects (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x1c8886e | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESS_SS_S7_SS_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESS_NS3_INS8_12E_ExitOptionES6_EESS_SS_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES16_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESS_SS_S7_SS_S7_SS_S7_SS_SS_SS_SS_SS_NS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SS_SS_S1E_SS_NS3_INS8_9E_ExpModeES6_EES10_S7_SS_NS3_INS8_21E_ExposureControlModeES6_EES7_NS3_IyS6_EESS_S1N_NS3_INS8_16E_ExposureStatusES6_EESS_S7_S1G_S7_SH_SS_NS3_INS8_12E_FlashModesES6_EESS_SS_SS_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESH_SH_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESH_S10_NS3_INS8_11E_FocusSizeES6_EES21_NS3_INS8_17E_CameraKeyOptionES6_EESS_S7_S7_SS_SS_SS_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1I_SS_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SS_SZ_SS_SS_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISE_S6_EESM_S7_S7_S7_S7_SS_S10_NS3_INS8_17E_LensMfRingStateES6_EESM_S2I_S2I_S7_S7_S7_SS_SS_S2I_SS_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESS_S2I_NS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EESS_S7_SS_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SS_SM_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S33_NS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESS_SS_SS_SV_SS_SS_SS_SS_S1N_SS_SV_SS_SS_S7_SS_NS3_INS8_14E_DistanceUnitES6_EES1C_SS_SS_SS_SS_NS3_INS8_12E_WhiteModesES6_EESS_SS_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3I_EES3J_NS3_IKNS8_21E_ExposureBlockReasonES3I_EES3J_NS3_IKNS8_21E_LiveviewBlockReasonES3I_EES3J_NS3_IbS3I_EES3J_S3T_S3J_NS3_IS9_S3I_EES3J_NS3_ISB_S3I_EES3J_S3T_S3J_NS3_IRKSG_S3I_EES3J_NS3_ISI_S3I_EES3J_NS3_ISK_S3I_EES3J_NS3_ItS3I_EES3J_NS3_IPKSN_S3I_EES3J_S3T_S3J_S3T_S3J_NS3_ISQ_S3I_EES3J_NS3_IiS3I_EES3J_NS3_IRKSU_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_ISW_S3I_EES3J_S46_S3J_NS3_ISY_S3I_EES3J_S46_S3J_S46_S3J_NS3_IjS3I_EES3J_NS3_IS11_S3I_EES3J_NS3_IS13_S3I_EES3J_NS3_IS15_S3I_EES3J_S4F_S3J_NS3_IS17_S3I_EES3J_NS3_IS19_S3I_EES3J_NS3_IS1B_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS1D_S3I_EES3J_S3T_S3J_S4I_S3J_NS3_IS1F_S3I_EES3J_NS3_IS1H_S3I_EES3J_S3T_S3J_S46_S3J_S46_S3J_S4J_S3J_S46_S3J_NS3_IS1J_S3I_EES3J_S4C_S3J_S3T_S3J_S46_S3J_NS3_IS1L_S3I_EES3J_S3T_S3J_NS3_IyS3I_EES3J_S46_S3J_S4O_S3J_NS3_IS1O_S3I_EES3J_S46_S3J_S3T_S3J_S4K_S3J_S3T_S3J_S3Y_S3J_S46_S3J_NS3_IS1Q_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S4G_S3J_NS3_IS1S_S3I_EES3J_S3Y_S3J_S3Y_S3J_NS3_IS1U_S3I_EES3J_NS3_IS1W_S3I_EES3J_S4C_S3J_NS3_IS1Y_S3I_EES3J_S3Y_S3J_S4C_S3J_NS3_IS20_S3I_EES3J_S4V_S3J_NS3_IS22_S3I_EES3J_S46_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_IS24_S3I_EES3J_NS3_IS26_S3I_EES3J_S4L_S3J_S46_S3J_NS3_IS28_S3I_EES3J_NS3_IS2A_S3I_EES3J_S3T_S3J_S46_S3J_S4B_S3J_S46_S3J_S46_S3J_S4C_S3J_NS3_IS2C_S3I_EES3J_NS3_IS2E_S3I_EES3J_NS3_IS2G_S3I_EES3J_NS3_IRKSE_S3I_EES3J_S41_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_S4C_S3J_NS3_IS2J_S3I_EES3J_S41_S3J_S56_S3J_S56_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S56_S3J_S46_S3J_S3T_S3J_NS3_IS2L_S3I_EES3J_S4C_S3J_NS3_IRKS2N_S3I_EES3J_S46_S3J_S56_S3J_NS3_IS2P_S3I_EES3J_S4C_S3J_S3T_S3J_NS3_IS2R_S3I_EES3J_NS3_IS2T_S3I_EES3J_NS3_IS2V_S3I_EES3J_S3T_S3J_NS3_IS2X_S3I_EES3J_S46_S3J_S3T_S3J_S46_S3J_S4B_S3J_NS3_IS2Z_S3I_EES3J_NS3_IS31_S3I_EES3J_S3T_S3J_S3T_S3J_S46_S3J_S41_S3J_S3T_S3J_NS3_IsS3I_EES3J_NS3_IS34_S3I_EES3J_S3T_S3J_S5J_S3J_NS3_IS36_S3I_EES3J_NS3_IS38_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S4O_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_NS3_IS3A_S3I_EES3J_S4I_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS3C_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_NS3_IS3E_S3I_EES3J_S4C_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_EE` | 0x20cebe0 | 5248 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x2187558 | 112 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_17clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6cd0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_17clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6cd8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6ce0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6ce8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6d00 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6d08 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6d10 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode33_app_qml_liveview_SpiritLevel_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21c6d18 | 8 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x21ce794 | 4 |

### `/bin/camera-expose`

+72 / −64 functions · +5 / −5 objects

**New functions (72)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x43108 | 12 |
| `_ZN18CameraProxyWrapper24request_acc_stateWrapperERK5QListI7QStringE` | 0x518c0 | 724 |
| `_ZN18CameraProxyWrapper31onrequest_acc_stateMethodResultEP18PendingCallWatcher` | 0x69048 | 3896 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x73cf0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x73cf8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x73cf8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x73d08 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x73d20 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x73dd0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x73de0 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96b38 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97208 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x976b0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97b58 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97f18 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_165Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x985e0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98a88 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98e70 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99230 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99a98 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99e58 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a500 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ac90 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b420 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b8c8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9bca8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c428 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9db20 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_185Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9dee0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e2a0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJN9HblmTypes16E_LensPropertiesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ea60 | 988 |
| `_ZN11CameraProxy21ibis_supportedChangedEb` | 0xbfc40 | 100 |
| `_ZN11CameraProxy22lens_propertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0xc06d0 | 96 |
| `_ZN11CameraProxy31request_acc_state_activeChangedEb` | 0xc2d50 | 100 |
| `_ZNK15CameraProxyDbus24request_acc_state_activeEv` | 0xc3b20 | 20 |
| `_ZN15CameraProxyDbus19doRequest_acc_stateEv` | 0xc3fe8 | 20 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc9f38 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc9fd0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0xc9fd8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0xca158 | 200 |
| `_ZN15CameraProxyDbus17request_acc_stateEiP7QObject` | 0xd50b0 | 688 |
| `_ZN15CameraProxyDbus23request_acc_stateResultEPK18PendingCallWatcherRN9HblmTypes14hblm_acc_stateE` | 0xd5360 | 2708 |
| `_ZNK15CameraProxyDbus14ibis_supportedEv` | 0xe5110 | 48 |
| `_ZNK15CameraProxyDbus15lens_propertiesEv` | 0xe5650 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17request_acc_stateEiP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe398 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus33restart_live_view_full_zoom_timerEiP7QObjectE4$_24Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe3d8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus27set_dcam_ready_for_exposureEbiP7QObjectE4$_25Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe418 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE4$_26Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe458 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_face_targetEiiP7QObjectE4$_27Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe498 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_hts_pollingEbiP7QObjectE4$_28Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe4d8 | 64 |

<details><summary>… 另 22 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_ibis_modeEN9HblmTypes10E_IbisModeEiP7QObjectE4$_29Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe518 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_live_viewEbiP7QObjectE4$_30Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe558 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22set_live_view_extendedEbN9HblmTypes23E_LiveviewTransportModeEiP7QObjectE4$_31Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe598 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_stop_downEbiP7QObjectE4$_32Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe5d8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus8set_zoomEbiP7QObjectE4$_33Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe618 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus23setup_dcam_stream_groupEN9HblmTypes13E_StreamGroupEiP7QObjectE4$_34Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe658 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe698 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14start_exposingEiP7QObjectE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe6d8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15start_recordingEiP7QObjectE4$_37Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe718 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13start_sessionEbiP7QObjectE4$_38Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe758 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE4$_39Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe798 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_uml_sessionEiP7QObjectE4$_40Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe7d8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe818 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13stop_exposingEiP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe858 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_find_focusEiP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe898 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus19stop_interval_timerEiP7QObjectE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe8d8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14stop_recordingEiP7QObjectE4$_45Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe918 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_self_timerEiP7QObjectE4$_46Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe958 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE4$_47Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe998 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_uml_sessionEiP7QObjectE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe9d8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus34teardown_current_dcam_stream_groupEiP7QObjectE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfea18 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus10toggle_aelEiP7QObjectE4$_50Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfea58 | 64 |

</details>

**Removed functions (64)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x42fe8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x727e0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x727e8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x727e8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x727f8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x72810 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x728c0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x728d0 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95910 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95db8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96260 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96620 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96ce8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_165Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97190 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97578 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97938 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97de0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98560 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98c08 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99398 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99b28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99fd0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a3b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a770 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9aef0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c610 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_185Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c9f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9cdb0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d550 | 992 |
| `_ZN11CameraProxy25lens_is_af_allowedChangedEb` | 0xbeec8 | 100 |
| `_ZN11CameraProxy25lens_mf_ring_stateChangedEN9HblmTypes17E_LensMfRingStateE` | 0xbeff0 | 96 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc8930 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc89c8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0xc89d0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0xc8b50 | 200 |
| `_ZNK15CameraProxyDbus18lens_is_af_allowedEv` | 0xe3190 | 48 |
| `_ZNK15CameraProxyDbus18lens_mf_ring_stateEv` | 0xe3220 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus33restart_live_view_full_zoom_timerEiP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc028 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus27set_dcam_ready_for_exposureEbiP7QObjectE4$_24Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc068 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE4$_25Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc0a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_face_targetEiiP7QObjectE4$_26Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc0e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_hts_pollingEbiP7QObjectE4$_27Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc128 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_ibis_modeEN9HblmTypes10E_IbisModeEiP7QObjectE4$_28Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfc168 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_live_viewEbiP7QObjectE4$_29Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc1a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22set_live_view_extendedEbN9HblmTypes23E_LiveviewTransportModeEiP7QObjectE4$_30Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfc1e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_stop_downEbiP7QObjectE4$_31Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc228 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus8set_zoomEbiP7QObjectE4$_32Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc268 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus23setup_dcam_stream_groupEN9HblmTypes13E_StreamGroupEiP7QObjectE4$_33Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfc2a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_34Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfc2e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14start_exposingEiP7QObjectE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc328 | 64 |

<details><summary>… 另 14 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15start_recordingEiP7QObjectE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc368 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13start_sessionEbiP7QObjectE4$_37Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc3a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE4$_38Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfc3e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_uml_sessionEiP7QObjectE4$_39Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc428 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_40Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfc468 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13stop_exposingEiP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc4a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_find_focusEiP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc4e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus19stop_interval_timerEiP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc528 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14stop_recordingEiP7QObjectE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc568 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_self_timerEiP7QObjectE4$_45Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc5a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE4$_46Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc5e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_uml_sessionEiP7QObjectE4$_47Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc628 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus34teardown_current_dcam_stream_groupEiP7QObjectE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc668 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus10toggle_aelEiP7QObjectE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfc6a8 | 64 |

</details>

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x1621e1 | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S7_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EES7_NS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_SD_S10_SN_S10_S2K_S2K_NS3_INS8_16E_LensPropertiesES6_EES7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_S43_S3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_S4M_S3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_NS3_IS2L_S3S_EES3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x1a9ae8 | 6472 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKiS9_EESA_SC_SA_SC_SA_NS3_IKsS9_EESA_SC_SA_SA_SA_SA_NS3_IKbS9_EESA_NS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESR_SR_SA_SG_NS3_IKNSH_16E_SessionOptionsES9_EESC_SA_NS3_IKNSH_19E_SpiritLevelActionES9_EESG_SA_SA_NS3_IKNSH_13E_StreamGroupES9_EENS3_IRKSM_S9_EES13_SA_SA_SA_SU_SA_SA_SA_SA_SA_NS3_IKNSH_19E_LensDriveEndpointES9_EESA_S13_S13_SA_SR_SR_SR_SA_S10_SA_SA_SA_SA_SG_SA_SA_SC_SA_SG_SA_NS3_IKNSH_10E_IbisModeES9_EESA_SG_SA_SG_NS3_IKNSH_23E_LiveviewTransportModeES9_EESA_SG_SA_SG_SA_S10_SA_NS3_IKNSH_12E_DCAMStreamES9_EESA_SA_SA_SG_SA_NS3_IKNSH_13E_SessionTypeES9_EESA_SA_S1F_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x1ad4f8 | 760 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x1b3708 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x1b5c58 | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x15fab5 | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S7_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_S10_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_S4M_S3T_NS3_IS2L_S3S_EES3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x199b58 | 6448 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKiS9_EESA_SC_SA_SC_SA_NS3_IKsS9_EESA_SC_SA_SA_SA_SA_NS3_IKbS9_EESA_NS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESR_SR_SA_SG_NS3_IKNSH_16E_SessionOptionsES9_EESC_SA_NS3_IKNSH_19E_SpiritLevelActionES9_EESG_SA_SA_NS3_IKNSH_13E_StreamGroupES9_EENS3_IRKSM_S9_EES13_SA_SA_SA_SU_SA_SA_SA_SA_SA_NS3_IKNSH_19E_LensDriveEndpointES9_EESA_S13_S13_SA_SR_SR_SR_SA_S10_SA_SA_SA_SG_SA_SA_SC_SA_SG_SA_NS3_IKNSH_10E_IbisModeES9_EESA_SG_SA_SG_NS3_IKNSH_23E_LiveviewTransportModeES9_EESA_SG_SA_SG_SA_S10_SA_NS3_IKNSH_12E_DCAMStreamES9_EESA_SA_SA_SG_SA_NS3_IKNSH_13E_SessionTypeES9_EESA_SA_S1F_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x19d510 | 752 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x1a3708 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x1a5c58 | 4 |

### `/bin/odindb-send`

+72 / −64 functions · +5 / −5 objects

**New functions (72)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x44ce0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x44ce8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x44ce8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x44cf8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x44d10 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x44d28 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x44d38 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x72d68 | 12 |
| `_ZN18CameraProxyWrapper24request_acc_stateWrapperERK5QListI7QStringE` | 0xca1c0 | 724 |
| `_ZN18CameraProxyWrapper31onrequest_acc_stateMethodResultEP18PendingCallWatcher` | 0xe1948 | 3896 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10f3d0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10faa0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10ff48 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1103f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1107b0 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_165Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110e78 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111320 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111708 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111ac8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112330 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1126f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112d98 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113528 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113cb8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114160 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114540 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114cc0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1163b8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_185Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116778 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116b38 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJN9HblmTypes16E_LensPropertiesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1172f8 | 988 |
| `_ZN11CameraProxy21ibis_supportedChangedEb` | 0x196358 | 100 |
| `_ZN11CameraProxy22lens_propertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0x196de8 | 96 |
| `_ZN11CameraProxy31request_acc_state_activeChangedEb` | 0x199468 | 100 |
| `_ZNK15CameraProxyDbus24request_acc_state_activeEv` | 0x1a9550 | 20 |
| `_ZN15CameraProxyDbus19doRequest_acc_stateEv` | 0x1a9a18 | 20 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1b1100 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x1b1198 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x1b11a0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x1b1320 | 200 |
| `_ZN15CameraProxyDbus17request_acc_stateEiP7QObject` | 0x1f8988 | 688 |
| `_ZN15CameraProxyDbus23request_acc_stateResultEPK18PendingCallWatcherRN9HblmTypes14hblm_acc_stateE` | 0x1f8c38 | 2708 |
| `_ZNK15CameraProxyDbus14ibis_supportedEv` | 0x2089e8 | 48 |
| `_ZNK15CameraProxyDbus15lens_propertiesEv` | 0x208f28 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17request_acc_stateEiP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221c70 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus33restart_live_view_full_zoom_timerEiP7QObjectE4$_24Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221cb0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus27set_dcam_ready_for_exposureEbiP7QObjectE4$_25Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221cf0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE4$_26Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221d30 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_face_targetEiiP7QObjectE4$_27Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221d70 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_hts_pollingEbiP7QObjectE4$_28Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221db0 | 64 |

<details><summary>… 另 22 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_ibis_modeEN9HblmTypes10E_IbisModeEiP7QObjectE4$_29Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x221df0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_live_viewEbiP7QObjectE4$_30Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221e30 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22set_live_view_extendedEbN9HblmTypes23E_LiveviewTransportModeEiP7QObjectE4$_31Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x221e70 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_stop_downEbiP7QObjectE4$_32Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221eb0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus8set_zoomEbiP7QObjectE4$_33Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221ef0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus23setup_dcam_stream_groupEN9HblmTypes13E_StreamGroupEiP7QObjectE4$_34Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x221f30 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x221f70 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14start_exposingEiP7QObjectE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221fb0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15start_recordingEiP7QObjectE4$_37Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x221ff0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13start_sessionEbiP7QObjectE4$_38Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x222030 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE4$_39Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x222070 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_uml_sessionEiP7QObjectE4$_40Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2220b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x2220f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13stop_exposingEiP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x222130 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_find_focusEiP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x222170 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus19stop_interval_timerEiP7QObjectE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2221b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14stop_recordingEiP7QObjectE4$_45Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2221f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_self_timerEiP7QObjectE4$_46Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x222230 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE4$_47Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x222270 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_uml_sessionEiP7QObjectE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2222b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus34teardown_current_dcam_stream_groupEiP7QObjectE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2222f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus10toggle_aelEiP7QObjectE4$_50Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x222330 | 64 |

</details>

**Removed functions (64)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x44bc0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x44bc8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x44bc8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x44bd8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x44bf0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x44c08 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x44c18 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x72c48 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e1a8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e650 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10eaf8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10eeb8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10f580 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_165Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10fa28 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10fe10 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1101d0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110678 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110df8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1114a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111c30 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1123c0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112868 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112c48 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113008 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113788 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114ea8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_185Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115288 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115648 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115de8 | 992 |
| `_ZN11CameraProxy25lens_is_af_allowedChangedEb` | 0x1955e0 | 100 |
| `_ZN11CameraProxy25lens_mf_ring_stateChangedEN9HblmTypes17E_LensMfRingStateE` | 0x195708 | 96 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1afae0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x1afb78 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x1afb80 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x1afd00 | 200 |
| `_ZNK15CameraProxyDbus18lens_is_af_allowedEv` | 0x206a50 | 48 |
| `_ZNK15CameraProxyDbus18lens_mf_ring_stateEv` | 0x206ae0 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus33restart_live_view_full_zoom_timerEiP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21f8e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus27set_dcam_ready_for_exposureEbiP7QObjectE4$_24Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21f928 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE4$_25Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21f968 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_face_targetEiiP7QObjectE4$_26Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21f9a8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_hts_pollingEbiP7QObjectE4$_27Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21f9e8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_ibis_modeEN9HblmTypes10E_IbisModeEiP7QObjectE4$_28Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x21fa28 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_live_viewEbiP7QObjectE4$_29Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fa68 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22set_live_view_extendedEbN9HblmTypes23E_LiveviewTransportModeEiP7QObjectE4$_30Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x21faa8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_stop_downEbiP7QObjectE4$_31Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fae8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus8set_zoomEbiP7QObjectE4$_32Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fb28 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus23setup_dcam_stream_groupEN9HblmTypes13E_StreamGroupEiP7QObjectE4$_33Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x21fb68 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_34Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x21fba8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14start_exposingEiP7QObjectE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fbe8 | 64 |

<details><summary>… 另 14 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15start_recordingEiP7QObjectE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fc28 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13start_sessionEbiP7QObjectE4$_37Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fc68 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE4$_38Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x21fca8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_uml_sessionEiP7QObjectE4$_39Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fce8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_40Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0x21fd28 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13stop_exposingEiP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fd68 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_find_focusEiP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fda8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus19stop_interval_timerEiP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fde8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14stop_recordingEiP7QObjectE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fe28 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_self_timerEiP7QObjectE4$_45Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fe68 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE4$_46Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fea8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_uml_sessionEiP7QObjectE4$_47Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21fee8 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus34teardown_current_dcam_stream_groupEiP7QObjectE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21ff28 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus10toggle_aelEiP7QObjectE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x21ff68 | 64 |

</details>

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x27acae | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S7_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EES7_NS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_SD_S10_SN_S10_S2K_S2K_NS3_INS8_16E_LensPropertiesES6_EES7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_S43_S3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_S4M_S3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_NS3_IS2L_S3S_EES3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x2f2f38 | 6472 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKiS9_EESA_SC_SA_SC_SA_NS3_IKsS9_EESA_SC_SA_SA_SA_SA_NS3_IKbS9_EESA_NS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESR_SR_SA_SG_NS3_IKNSH_16E_SessionOptionsES9_EESC_SA_NS3_IKNSH_19E_SpiritLevelActionES9_EESG_SA_SA_NS3_IKNSH_13E_StreamGroupES9_EENS3_IRKSM_S9_EES13_SA_SA_SA_SU_SA_SA_SA_SA_SA_NS3_IKNSH_19E_LensDriveEndpointES9_EESA_S13_S13_SA_SR_SR_SR_SA_S10_SA_SA_SA_SA_SG_SA_SA_SC_SA_SG_SA_NS3_IKNSH_10E_IbisModeES9_EESA_SG_SA_SG_NS3_IKNSH_23E_LiveviewTransportModeES9_EESA_SG_SA_SG_SA_S10_SA_NS3_IKNSH_12E_DCAMStreamES9_EESA_SA_SA_SG_SA_NS3_IKNSH_13E_SessionTypeES9_EESA_SA_S1F_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x2fc1d0 | 760 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x3045a0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x30768c | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x2787c2 | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S7_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_S10_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_S4M_S3T_NS3_IS2L_S3S_EES3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x2f2fa8 | 6448 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKiS9_EESA_SC_SA_SC_SA_NS3_IKsS9_EESA_SC_SA_SA_SA_SA_NS3_IKbS9_EESA_NS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESR_SR_SA_SG_NS3_IKNSH_16E_SessionOptionsES9_EESC_SA_NS3_IKNSH_19E_SpiritLevelActionES9_EESG_SA_SA_NS3_IKNSH_13E_StreamGroupES9_EENS3_IRKSM_S9_EES13_SA_SA_SA_SU_SA_SA_SA_SA_SA_NS3_IKNSH_19E_LensDriveEndpointES9_EESA_S13_S13_SA_SR_SR_SR_SA_S10_SA_SA_SA_SG_SA_SA_SC_SA_SG_SA_NS3_IKNSH_10E_IbisModeES9_EESA_SG_SA_SG_NS3_IKNSH_23E_LiveviewTransportModeES9_EESA_SG_SA_SG_SA_S10_SA_NS3_IKNSH_12E_DCAMStreamES9_EESA_SA_SA_SG_SA_NS3_IKNSH_13E_SessionTypeES9_EESA_SA_S1F_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x2fc1e8 | 752 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x3045a0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x30768c | 4 |

### `/bin/camera-service`

+49 / −48 functions · +7 / −7 objects

**New functions (49)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN24DCAMCaptureEnginePrivate25hasLensControlRingChangedEb` | 0xa7ab0 | 100 |
| `_ZN20LensControlInterface21lensPropertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0xb00f8 | 96 |
| `_ZNK21CfvCameraStateMachine13ibisSupportedEv` | 0xb60a8 | 8 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0xb8430 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xb8a00 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0xb8a08 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0xb8a08 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb8a18 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb8a30 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0xb8ae0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0xb8af0 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc8df8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc8e90 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0xc8e98 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0xc9018 | 200 |
| `_ZNK18StateLensDriveInit29distanceScaleUpdateIsFinishedEv` | 0xe4140 | 708 |
| `_ZNK21X2DCameraStateMachine13ibisSupportedEv` | 0x10e508 | 8 |
| `_ZN22IbisSpiritLevelHandler15requestAccStateERN9HblmTypes14hblm_acc_stateE` | 0x1512c0 | 48 |
| `_ZNK16CameraObjectImpl15lens_propertiesEv` | 0x18f7b8 | 240 |
| `_ZNK16CameraObjectImpl14ibis_supportedEv` | 0x193c68 | 156 |
| `_ZN16CameraObjectImpl19doRequest_acc_stateERN9HblmTypes14hblm_acc_stateERK12QDBusMessage` | 0x197c08 | 296 |
| `_ZN9QtPrivate11QSlotObjectIM12CameraObjectFvN9HblmTypes16E_LensPropertiesEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a07f0 | 124 |
| `_ZNK20LensControlInterface14lensPropertiesEv` | 0x1b7d68 | 8 |
| `_ZN11LensControl20onHasLensControlRingEb` | 0x233bd8 | 132 |
| `_ZN12CameraObject21ibis_supportedChangedEb` | 0x291db8 | 100 |
| `_ZN12CameraObject22lens_propertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0x2928c0 | 96 |
| `_ZNK12CameraObject16_lens_propertiesEv` | 0x2c2ff8 | 12 |
| `_ZN12CameraObject17request_acc_stateERK12QDBusMessage` | 0x2c4378 | 1104 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_137Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c65c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_138Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c65f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_139Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6620 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_140Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6650 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_141Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6680 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_143Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c66e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_145Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6740 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_147Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c67a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_149Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6800 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_153Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c68c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_155Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6920 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_157Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6980 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_158Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c69b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_159Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c69e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_160Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6a10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_161Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6a40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_163Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6aa0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_169Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6bc0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_170Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6bf0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_171Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6c20 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_173Li1ENS_4ListIJN9HblmTypes16E_LensPropertiesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6c80 | 44 |

**Removed functions (48)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN20LensControlInterface22lensMfRingStateChangedEN9HblmTypes17E_LensMfRingStateE` | 0xafe98 | 96 |
| `_ZN22IbisSpiritLevelHandlerD2Ev` | 0xb6928 | 92 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0xb8298 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xb8868 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0xb8870 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0xb8870 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb8880 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb8898 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0xb8948 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0xb8958 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc8c60 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc8cf8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0xc8d00 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0xc8e80 | 200 |
| `_ZN17QArrayDataPointerIN22IbisSpiritLevelHandler6SampleEE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x150ce8 | 496 |
| `_ZN17QArrayDataPointerIN22IbisSpiritLevelHandler6SampleEE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0x150ed8 | 412 |
| `_ZN9QtPrivate16QGenericArrayOpsIN22IbisSpiritLevelHandler6SampleEE7emplaceIJRKS2_EEEvxDpOT_` | 0x151078 | 780 |
| `_ZN9QtPrivate20q_relocate_overlap_nIN22IbisSpiritLevelHandler6SampleExEEvPT_T0_S4_` | 0x151388 | 308 |
| `_ZN9QtPrivate30q_relocate_overlap_n_left_moveINSt3__116reverse_iteratorIPN22IbisSpiritLevelHandler6SampleEEExEEvT_T0_S7_` | 0x1514c0 | 332 |
| `_ZNK16CameraObjectImpl18lens_is_af_allowedEv` | 0x18fae0 | 240 |
| `_ZNK16CameraObjectImpl18lens_mf_ring_stateEv` | 0x18fbd0 | 240 |
| `_ZN9QtPrivate11QSlotObjectIM12CameraObjectFvN9HblmTypes17E_LensMfRingStateEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a0ac0 | 124 |
| `_ZNK20LensControlInterface15lensMfRingStateEv` | 0x1b7fb8 | 8 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZL16queueWavCallback20_AudioFilePlayInfo_tPvE3$_1Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPS2_Pb` | 0x237320 | 388 |
| `_ZN12CameraObject25lens_is_af_allowedChangedEb` | 0x292630 | 100 |
| `_ZN12CameraObject25lens_mf_ring_stateChangedEN9HblmTypes17E_LensMfRingStateE` | 0x292758 | 96 |
| `_ZNK12CameraObject19_lens_mf_ring_stateEv` | 0x2c3000 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_137Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6178 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_138Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c61a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_139Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c61d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_140Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6208 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_141Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6238 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_143Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6298 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_145Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c62f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_147Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6358 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_149Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c63b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_153Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6478 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_155Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c64d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_157Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6538 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_158Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6568 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_159Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6598 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_160Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c65c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_161Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c65f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_163Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6658 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_169Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6778 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_170Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c67a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_171Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c67d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_173Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c6838 | 44 |

**New objects (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x5eb3ff | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_145qt_meta_stringdata_DCAMCaptureEnginePrivate_tEJN9QtPrivate20TypeAndForceCompleteI24DCAMCaptureEnginePrivateNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IN9HblmTypes13E_StreamGroupES9_EESA_NS3_INSB_12E_DCAMStreamES9_EENS3_IbS9_EESA_SA_NS3_IKiS9_EESA_SI_SA_SI_SA_SI_SA_NS3_IKsS9_EESA_SK_SA_SK_SA_NS3_IKNSB_17E_AutoFocusStatusES9_EESA_NS3_IKNSB_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_NS3_IKNSB_10E_AeStatusES9_EESA_NS3_IKbS9_EESA_NS3_IiS9_EES11_SA_NS3_INSB_14E_ReturnStatusES9_EESA_NS3_IRK17FocusDistanceInfoS9_EESA_SI_SA_SI_SA_SI_SA_NS3_IKNSB_10E_LensTypeES9_EESA_SA_S11_SA_S11_SA_S11_SA_SG_SA_NS3_IKNSB_13E_FlashStatusES9_EESA_SA_SG_SA_SG_SA_SG_SA_SG_SA_SG_SA_NS3_IRK7QStringS9_EESA_S1H_SA_SG_SA_NS3_IjS9_EESA_S1I_SA_S1I_SA_S1I_SA_S11_SA_NS3_I23dcam_focus_motor_resultS9_EESA_NS3_IRK21dcam_still_expo_stateS9_EESA_SG_SA_SG_SA_NS3_ItS9_EESA_S1I_SA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_SG_SA_NS3_INSB_16E_StopDownStatusES9_EESA_SG_SA_SG_SA_S11_SA_S11_SA_SG_SA_SG_SA_NS3_I6QPointS9_EESA_NS3_INS4_19LensControlRingModeES9_EENS3_INS4_24LensControlRingDirectionES9_EESA_S1H_SA_S1H_SA_S1H_SA_NS3_INSB_12E_LensStatusES9_EENS3_INSB_16E_LensPowerStateES9_EESA_S13_SA_NS3_IRK10QByteArrayS9_EESA_SG_SA_SG_SA_SG_SA_NS3_INSB_23E_LiveviewTransportModeES9_EESA_S1I_SA_SG_SA_SG_SA_NS3_IRK5QListI14QSharedPointerI12DussMemShareEES9_EESA_SA_NS3_INSB_11E_ErrorCodeES9_EENS3_INSB_15E_ErrorCategoryES9_EENS3_INSB_13E_ErrorActionES9_EENS3_IK4QMapIS1E_8QVariantES9_EESA_S20_S22_SA_SG_SA_EE` | 0x79ac48 | 1280 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_LensControl_tEJN9QtPrivate20TypeAndForceCompleteI11LensControlNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_SG_SA_SA_NS3_IjS9_EESA_SA_NS3_IiS9_EESA_SH_SA_NS3_IbS9_EESA_SI_SA_SH_SA_NS3_IRK7QStringS9_EESA_SN_SA_SJ_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_SJ_SA_SJ_SA_NS3_IRK17FocusDistanceInfoS9_EESA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_NS3_IKtS9_EESA_SH_SA_SH_SA_NS3_I23dcam_focus_motor_resultS9_EESA_NS3_IN9HblmTypes10E_LensTypeES9_EESA_SI_SA_SH_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_SJ_SA_NS3_INS11_17E_AutoFocusStatusES9_EESA_NS3_INS11_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_SI_SA_SI_SA_SI_SA_NS3_INS11_12E_LensStatusES9_EENS3_INS11_16E_LensPowerStateES9_EESA_SH_SA_SN_SA_SN_SA_SN_SA_SW_EE` | 0x79bcf0 | 728 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_141qt_meta_stringdata_LensControlInterface_tEJN9QtPrivate20TypeAndForceCompleteI20LensControlInterfaceNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_SA_NS3_IKN9HblmTypes10E_LensTypeES9_EESA_NS3_INSB_12E_LensStatusES9_EESA_NS3_IKNSB_17E_AutoFocusStatusES9_EESA_NS3_IKNSB_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_NS3_IKiS9_EESA_NS3_IiS9_EESA_NS3_IbS9_EESA_SV_SA_NS3_IRK7QStringS9_EESA_SZ_SA_NS3_INSB_16E_LensPowerStateES9_EESA_NS3_IjS9_EESA_S12_SA_S12_SA_S12_SA_SU_SA_SV_SA_SV_SA_NS3_ItS9_EESA_S12_SA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_S18_SA_NS3_INSB_18E_FocusMotorResultES9_EESA_NS3_IRK17FocusDistanceInfoS9_EESA_SV_SA_SU_SA_SV_SA_SV_SA_SV_SA_SU_SA_NS3_INSB_16E_LensPropertiesES9_EESA_SV_SA_SU_SA_SU_SA_ST_SA_ST_SA_ST_SA_ST_SA_NS3_IKNSB_19E_LensDriveEndpointES9_EESA_NS3_IKNSB_17E_LensDriveStatusES9_EESA_SZ_SA_SZ_SA_SZ_SA_SV_SA_SA_SA_SA_SA_SA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_S1S_EE` | 0x79c000 | 816 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_CameraObject_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IiS6_EES8_S8_S7_NS3_I4QMapI7QString8QVariantES6_EES8_S8_NS3_ItS6_EENS3_I5QListISC_ES6_EES7_S7_S8_S8_NS3_ISF_IiES6_EES8_S8_S7_S8_S7_S7_S7_S8_S8_S8_S8_S8_NS3_IjS6_EES8_S8_S8_S7_S8_S7_S7_S8_S8_S8_S8_S8_S7_S8_S7_S8_S7_S8_S8_S8_S8_S8_S7_S8_S8_S7_S8_S8_S8_S7_S8_S8_S8_S8_S8_SK_S7_S8_S8_S7_S8_NS3_IyS6_EES8_SL_S8_S8_S8_S7_S8_S7_SD_S8_S8_S8_S8_S8_S8_S8_S8_S8_SD_SD_S8_S8_SK_S8_SD_SK_S8_S8_S8_S8_S7_S7_S8_S8_S8_S7_S7_S7_S8_S7_S8_S8_S8_S8_S8_S7_S8_S8_S8_S8_SK_S8_S8_S8_NS3_ISA_S6_EESE_SK_SK_S7_S7_S7_S8_SK_SE_SK_SM_SM_S8_S7_SM_S7_S7_S8_S8_SM_S8_S7_S7_S8_SK_NS3_I10QByteArrayS6_EES8_SM_SK_S8_S8_SK_S7_S8_S8_S8_S8_S7_S8_SK_S8_S7_SK_S8_S8_S8_S8_S7_S7_S8_S7_SE_S7_NS3_IsS6_EES8_S7_SP_S8_S8_S8_S8_S8_S8_S8_SJ_S8_S8_S8_S8_SL_S8_S8_SJ_S8_S8_S7_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S7_S8_SK_NS3_I12CameraObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKiSS_EEST_SV_ST_SV_ST_NS3_IKbSS_EEST_SX_ST_SX_ST_NS3_IKN9HblmTypes17E_AfAlgorithmModeESS_EEST_NS3_IKNSY_21E_AfFaceDetectionModeESS_EEST_SV_ST_SX_ST_NS3_IRKSC_SS_EEST_NS3_IKNSY_17E_AutoFocusResultESS_EEST_NS3_IKNSY_17E_AutoFocusStatusESS_EEST_NS3_IKtSS_EEST_NS3_IKSG_SS_EEST_SX_ST_SX_ST_NS3_IKNSY_10E_LensTypeESS_EEST_SV_ST_NS3_IRKSI_SS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_20E_ExpBracketingParamESS_EEST_SV_ST_NS3_IKNSY_12E_ExitOptionESS_EEST_SV_ST_SV_ST_NS3_IKjSS_EEST_NS3_IKNSY_12E_CameraModeESS_EEST_NS3_IKNSY_12E_CameraTypeESS_EEST_NS3_IKNSY_18E_CameraPropertiesESS_EEST_SX_ST_S24_ST_SX_ST_SX_ST_NS3_IKNSY_26E_FocusBracketingStepSizesESS_EEST_NS3_IKNSY_14E_ColorProfileESS_EEST_NS3_IKNSY_10E_CropModeESS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SV_ST_SV_ST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_12E_TraceLevelESS_EEST_NS3_IKNSY_12E_DriveModesESS_EEST_SX_ST_S2D_ST_NS3_IKNSY_15E_FaceDetectionESS_EEST_NS3_IKNSY_13E_ImageFormatESS_EEST_SX_ST_SV_ST_SV_ST_S2J_ST_SV_ST_NS3_IKNSY_9E_ExpModeESS_EEST_S1V_ST_SX_ST_SV_ST_NS3_IKNSY_21E_ExposureControlModeESS_EEST_SX_ST_S2V_ST_NS3_IKySS_EEST_SV_ST_S2X_ST_NS3_IKNSY_16E_ExposureStatusESS_EEST_SV_ST_SV_ST_SX_ST_S2M_ST_SX_ST_S17_ST_SV_ST_SV_ST_NS3_IKNSY_12E_FlashModesESS_EEST_SV_ST_SV_ST_SV_ST_SV_ST_S27_ST_NS3_IKNSY_27E_FocusBracketingStrategiesESS_EEST_S17_ST_S17_ST_NS3_IKNSY_12E_FocusModesESS_EEST_NS3_IKNSY_19E_FocusPeakingColorESS_EEST_S1V_ST_NS3_IKNSY_21E_FocusPointResetModeESS_EEST_S17_ST_S1V_ST_NS3_IKNSY_11E_FocusSizeESS_EEST_S3I_ST_NS3_IKNSY_17E_CameraKeyOptionESS_EEST_SV_ST_SX_ST_SX_ST_SV_ST_SV_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_10E_IbisModeESS_EEST_SX_ST_NS3_IKNSY_10E_BitDepthESS_EEST_S2P_ST_SV_ST_NS3_IKNSY_21E_ImagePostProcessingESS_EEST_NS3_IKNSY_17E_IbisControlModeESS_EEST_SX_ST_SV_ST_S1T_ST_SV_ST_SV_ST_S1V_ST_NS3_IKNSY_13E_ResolutionsESS_EEST_NS3_IKNSY_19E_LensDriveEndpointESS_EEST_NS3_IKNSY_17E_LensDriveStatusESS_EEST_NS3_IRKSA_SS_EEST_S1F_ST_S1V_ST_S1V_ST_SX_ST_SX_ST_SX_ST_SV_ST_S1V_ST_S1F_ST_S1V_ST_S49_ST_S49_ST_NS3_IKNSY_16E_LensPropertiesESS_EEST_SX_ST_S49_ST_SX_ST_SX_ST_SV_ST_SV_ST_S49_ST_SV_ST_SX_ST_SX_ST_NS3_IKNSY_15E_LiveViewStateESS_EEST_S1V_ST_NS3_IRKSN_SS_EEST_SV_ST_S49_ST_S1V_ST_NS3_IKNSY_23E_LiveviewTransportModeESS_EEST_NS3_IKNSY_9E_LmModesESS_EEST_S1V_ST_SX_ST_NS3_IKNSY_19E_ManualFocusAssistESS_EEST_NS3_IKNSY_13E_MaxApertureESS_EEST_NS3_IKNSY_15E_MultiShotModeESS_EEST_NS3_IKNSY_13E_FlashStatusESS_EEST_SX_ST_NS3_IKNSY_16E_OptionOverrideESS_EEST_S1V_ST_SV_ST_SX_ST_S1V_ST_SV_ST_S1T_ST_NS3_IKNSY_12E_SoundLevelESS_EEST_NS3_IKNSY_14E_SequenceModeESS_EEST_SX_ST_SX_ST_SV_ST_SX_ST_S1F_ST_SX_ST_NS3_IKsSS_EEST_NS3_IKNSY_24E_SpiritLevelOrientationESS_EEST_SX_ST_S5B_ST_NS3_IKNSY_14E_CameraStatusESS_EEST_NS3_IKNSY_16E_StopDownStatusESS_EEST_NS3_IKNSY_13E_StreamGroupESS_EEST_NS3_IKNSY_18E_SensorUnitStatusESS_EEST_SV_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SV_ST_SV_ST_S2X_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SX_ST_SV_ST_NS3_IKNSY_14E_DistanceUnitESS_EEST_S2D_ST_SV_ST_SV_ST_SV_ST_SV_ST_NS3_IKNSY_12E_WhiteModesESS_EEST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_11E_ZoomLevelESS_EEST_S1V_ST_NS3_IKNSY_15E_AfBlockReasonESS_EEST_NS3_IKNSY_21E_ExposureBlockReasonESS_EEST_NS3_IKNSY_21E_LiveviewBlockReasonESS_EEST_S5B_NS3_IRK12QDBusMessageSS_EENS3_IiSS_EESV_S6C_ST_S6C_ST_S6C_ST_S6C_ST_SX_S6C_NS3_IjSS_EESV_S17_S17_S17_S6C_ST_SX_SV_SV_S6C_ST_SV_SX_S6C_ST_S6C_ST_SV_S49_S49_S6C_ST_S6C_S6D_S6C_S6D_SV_S6C_ST_S6C_S6E_S6C_NS3_ISC_SS_EES6C_ST_S6C_ST_SV_S6C_ST_S49_S49_S6C_ST_S17_S17_S17_S6C_ST_SV_S6C_ST_S6C_S6F_S6C_ST_S6C_ST_SX_S6C_ST_S6C_ST_SV_S6C_ST_SX_S6C_ST_SV_S6C_ST_SX_S6C_ST_SX_SV_S6C_ST_SX_S6C_ST_SX_S6C_ST_SV_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_SX_S6C_ST_SV_S6C_ST_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_EE` | 0x7ac900 | 6400 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x7c41a8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x7cfcd4 | 4 |

**Removed objects (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x5eac43 | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_145qt_meta_stringdata_DCAMCaptureEnginePrivate_tEJN9QtPrivate20TypeAndForceCompleteI24DCAMCaptureEnginePrivateNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IN9HblmTypes13E_StreamGroupES9_EESA_NS3_INSB_12E_DCAMStreamES9_EENS3_IbS9_EESA_SA_NS3_IKiS9_EESA_SI_SA_SI_SA_SI_SA_NS3_IKsS9_EESA_SK_SA_SK_SA_NS3_IKNSB_17E_AutoFocusStatusES9_EESA_NS3_IKNSB_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_NS3_IKNSB_10E_AeStatusES9_EESA_NS3_IKbS9_EESA_NS3_IiS9_EES11_SA_NS3_INSB_14E_ReturnStatusES9_EESA_NS3_IRK17FocusDistanceInfoS9_EESA_SI_SA_SI_SA_SI_SA_NS3_IKNSB_10E_LensTypeES9_EESA_SA_S11_SA_S11_SA_S11_SA_SG_SA_NS3_IKNSB_13E_FlashStatusES9_EESA_SA_SG_SA_SG_SA_SG_SA_SG_SA_NS3_IRK7QStringS9_EESA_S1H_SA_SG_SA_NS3_IjS9_EESA_S1I_SA_S1I_SA_S1I_SA_S11_SA_NS3_I23dcam_focus_motor_resultS9_EESA_NS3_IRK21dcam_still_expo_stateS9_EESA_SG_SA_SG_SA_NS3_ItS9_EESA_S1I_SA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_SG_SA_NS3_INSB_16E_StopDownStatusES9_EESA_SG_SA_SG_SA_S11_SA_S11_SA_SG_SA_SG_SA_NS3_I6QPointS9_EESA_NS3_INS4_19LensControlRingModeES9_EENS3_INS4_24LensControlRingDirectionES9_EESA_S1H_SA_S1H_SA_S1H_SA_NS3_INSB_12E_LensStatusES9_EENS3_INSB_16E_LensPowerStateES9_EESA_S13_SA_NS3_IRK10QByteArrayS9_EESA_SG_SA_SG_SA_SG_SA_NS3_INSB_23E_LiveviewTransportModeES9_EESA_S1I_SA_SG_SA_SG_SA_NS3_IRK5QListI14QSharedPointerI12DussMemShareEES9_EESA_SA_NS3_INSB_11E_ErrorCodeES9_EENS3_INSB_15E_ErrorCategoryES9_EENS3_INSB_13E_ErrorActionES9_EENS3_IK4QMapIS1E_8QVariantES9_EESA_S20_S22_SA_SG_SA_EE` | 0x79acb0 | 1264 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_LensControl_tEJN9QtPrivate20TypeAndForceCompleteI11LensControlNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_SG_SA_SA_NS3_IjS9_EESA_SA_NS3_IiS9_EESA_SH_SA_NS3_IbS9_EESA_SI_SA_SH_SA_NS3_IRK7QStringS9_EESA_SN_SA_SJ_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_SJ_SA_SJ_SA_NS3_IRK17FocusDistanceInfoS9_EESA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_NS3_IKtS9_EESA_SH_SA_SH_SA_NS3_I23dcam_focus_motor_resultS9_EESA_NS3_IN9HblmTypes10E_LensTypeES9_EESA_SI_SA_SH_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_NS3_INS11_17E_AutoFocusStatusES9_EESA_NS3_INS11_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_SI_SA_SI_SA_SI_SA_NS3_INS11_12E_LensStatusES9_EENS3_INS11_16E_LensPowerStateES9_EESA_SH_SA_SN_SA_SN_SA_SN_SA_SW_EE` | 0x79bd48 | 712 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_141qt_meta_stringdata_LensControlInterface_tEJN9QtPrivate20TypeAndForceCompleteI20LensControlInterfaceNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_SA_NS3_IKN9HblmTypes10E_LensTypeES9_EESA_NS3_INSB_12E_LensStatusES9_EESA_NS3_IKNSB_17E_AutoFocusStatusES9_EESA_NS3_IKNSB_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_NS3_IKiS9_EESA_NS3_IiS9_EESA_NS3_IbS9_EESA_SV_SA_NS3_IRK7QStringS9_EESA_SZ_SA_NS3_INSB_16E_LensPowerStateES9_EESA_NS3_IjS9_EESA_S12_SA_S12_SA_S12_SA_SU_SA_SV_SA_SV_SA_NS3_ItS9_EESA_S12_SA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_S18_SA_NS3_INSB_18E_FocusMotorResultES9_EESA_NS3_IRK17FocusDistanceInfoS9_EESA_SV_SA_SU_SA_SV_SA_SV_SA_SV_SA_SU_SA_NS3_INSB_17E_LensMfRingStateES9_EESA_SV_SA_SU_SA_SU_SA_ST_SA_ST_SA_ST_SA_ST_SA_NS3_IKNSB_19E_LensDriveEndpointES9_EESA_NS3_IKNSB_17E_LensDriveStatusES9_EESA_SZ_SA_SZ_SA_SZ_SA_SV_SA_SA_SA_SA_SA_SA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_S1S_EE` | 0x79c048 | 816 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_CameraObject_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IiS6_EES8_S8_S7_NS3_I4QMapI7QString8QVariantES6_EES8_S8_NS3_ItS6_EENS3_I5QListISC_ES6_EES7_S7_S8_S8_NS3_ISF_IiES6_EES8_S8_S7_S8_S7_S7_S7_S8_S8_S8_S8_S8_NS3_IjS6_EES8_S8_S8_S7_S8_S7_S7_S8_S8_S8_S8_S8_S7_S8_S7_S8_S7_S8_S8_S8_S8_S8_S7_S8_S8_S7_S8_S8_S8_S7_S8_S8_S8_S8_S8_SK_S7_S8_S8_S7_S8_NS3_IyS6_EES8_SL_S8_S8_S8_S7_S8_S7_SD_S8_S8_S8_S8_S8_S8_S8_S8_S8_SD_SD_S8_S8_SK_S8_SD_SK_S8_S8_S8_S8_S7_S7_S8_S8_S8_S7_S7_S7_S8_S8_S8_S8_S8_S8_S7_S8_S8_S8_S8_SK_S8_S8_S8_NS3_ISA_S6_EESE_SK_SK_S7_S7_S7_S7_S8_SK_S8_SE_SK_SM_SM_S7_SM_S7_S7_S8_S8_SM_S8_S7_S7_S8_SK_NS3_I10QByteArrayS6_EES8_SM_SK_S8_S8_SK_S7_S8_S8_S8_S8_S7_S8_SK_S8_S7_SK_S8_S8_S8_S8_S7_S7_S8_S7_SE_S7_NS3_IsS6_EES8_S7_SP_S8_S8_S8_S8_S8_S8_S8_SJ_S8_S8_S8_S8_SL_S8_S8_SJ_S8_S8_S7_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S7_S8_SK_NS3_I12CameraObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKiSS_EEST_SV_ST_SV_ST_NS3_IKbSS_EEST_SX_ST_SX_ST_NS3_IKN9HblmTypes17E_AfAlgorithmModeESS_EEST_NS3_IKNSY_21E_AfFaceDetectionModeESS_EEST_SV_ST_SX_ST_NS3_IRKSC_SS_EEST_NS3_IKNSY_17E_AutoFocusResultESS_EEST_NS3_IKNSY_17E_AutoFocusStatusESS_EEST_NS3_IKtSS_EEST_NS3_IKSG_SS_EEST_SX_ST_SX_ST_NS3_IKNSY_10E_LensTypeESS_EEST_SV_ST_NS3_IRKSI_SS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_20E_ExpBracketingParamESS_EEST_SV_ST_NS3_IKNSY_12E_ExitOptionESS_EEST_SV_ST_SV_ST_NS3_IKjSS_EEST_NS3_IKNSY_12E_CameraModeESS_EEST_NS3_IKNSY_12E_CameraTypeESS_EEST_NS3_IKNSY_18E_CameraPropertiesESS_EEST_SX_ST_S24_ST_SX_ST_SX_ST_NS3_IKNSY_26E_FocusBracketingStepSizesESS_EEST_NS3_IKNSY_14E_ColorProfileESS_EEST_NS3_IKNSY_10E_CropModeESS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SV_ST_SV_ST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_12E_TraceLevelESS_EEST_NS3_IKNSY_12E_DriveModesESS_EEST_SX_ST_S2D_ST_NS3_IKNSY_15E_FaceDetectionESS_EEST_NS3_IKNSY_13E_ImageFormatESS_EEST_SX_ST_SV_ST_SV_ST_S2J_ST_SV_ST_NS3_IKNSY_9E_ExpModeESS_EEST_S1V_ST_SX_ST_SV_ST_NS3_IKNSY_21E_ExposureControlModeESS_EEST_SX_ST_S2V_ST_NS3_IKySS_EEST_SV_ST_S2X_ST_NS3_IKNSY_16E_ExposureStatusESS_EEST_SV_ST_SV_ST_SX_ST_S2M_ST_SX_ST_S17_ST_SV_ST_SV_ST_NS3_IKNSY_12E_FlashModesESS_EEST_SV_ST_SV_ST_SV_ST_SV_ST_S27_ST_NS3_IKNSY_27E_FocusBracketingStrategiesESS_EEST_S17_ST_S17_ST_NS3_IKNSY_12E_FocusModesESS_EEST_NS3_IKNSY_19E_FocusPeakingColorESS_EEST_S1V_ST_NS3_IKNSY_21E_FocusPointResetModeESS_EEST_S17_ST_S1V_ST_NS3_IKNSY_11E_FocusSizeESS_EEST_S3I_ST_NS3_IKNSY_17E_CameraKeyOptionESS_EEST_SV_ST_SX_ST_SX_ST_SV_ST_SV_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_10E_IbisModeESS_EEST_NS3_IKNSY_10E_BitDepthESS_EEST_S2P_ST_SV_ST_NS3_IKNSY_21E_ImagePostProcessingESS_EEST_NS3_IKNSY_17E_IbisControlModeESS_EEST_SX_ST_SV_ST_S1T_ST_SV_ST_SV_ST_S1V_ST_NS3_IKNSY_13E_ResolutionsESS_EEST_NS3_IKNSY_19E_LensDriveEndpointESS_EEST_NS3_IKNSY_17E_LensDriveStatusESS_EEST_NS3_IRKSA_SS_EEST_S1F_ST_S1V_ST_S1V_ST_SX_ST_SX_ST_SX_ST_SX_ST_SV_ST_S1V_ST_NS3_IKNSY_17E_LensMfRingStateESS_EEST_S1F_ST_S1V_ST_S49_ST_S49_ST_SX_ST_S49_ST_SX_ST_SX_ST_SV_ST_SV_ST_S49_ST_SV_ST_SX_ST_SX_ST_NS3_IKNSY_15E_LiveViewStateESS_EEST_S1V_ST_NS3_IRKSN_SS_EEST_SV_ST_S49_ST_S1V_ST_NS3_IKNSY_23E_LiveviewTransportModeESS_EEST_NS3_IKNSY_9E_LmModesESS_EEST_S1V_ST_SX_ST_NS3_IKNSY_19E_ManualFocusAssistESS_EEST_NS3_IKNSY_13E_MaxApertureESS_EEST_NS3_IKNSY_15E_MultiShotModeESS_EEST_NS3_IKNSY_13E_FlashStatusESS_EEST_SX_ST_NS3_IKNSY_16E_OptionOverrideESS_EEST_S1V_ST_SV_ST_SX_ST_S1V_ST_SV_ST_S1T_ST_NS3_IKNSY_12E_SoundLevelESS_EEST_NS3_IKNSY_14E_SequenceModeESS_EEST_SX_ST_SX_ST_SV_ST_SX_ST_S1F_ST_SX_ST_NS3_IKsSS_EEST_NS3_IKNSY_24E_SpiritLevelOrientationESS_EEST_SX_ST_S5B_ST_NS3_IKNSY_14E_CameraStatusESS_EEST_NS3_IKNSY_16E_StopDownStatusESS_EEST_NS3_IKNSY_13E_StreamGroupESS_EEST_NS3_IKNSY_18E_SensorUnitStatusESS_EEST_SV_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SV_ST_SV_ST_S2X_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SX_ST_SV_ST_NS3_IKNSY_14E_DistanceUnitESS_EEST_S2D_ST_SV_ST_SV_ST_SV_ST_SV_ST_NS3_IKNSY_12E_WhiteModesESS_EEST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_11E_ZoomLevelESS_EEST_S1V_ST_NS3_IKNSY_15E_AfBlockReasonESS_EEST_NS3_IKNSY_21E_ExposureBlockReasonESS_EEST_NS3_IKNSY_21E_LiveviewBlockReasonESS_EEST_S5B_NS3_IRK12QDBusMessageSS_EENS3_IiSS_EESV_S6C_ST_S6C_ST_S6C_ST_S6C_ST_SX_S6C_NS3_IjSS_EESV_S17_S17_S17_S6C_ST_SX_SV_SV_S6C_ST_SV_SX_S6C_ST_S6C_ST_SV_S49_S49_S6C_ST_S6C_S6D_S6C_S6D_SV_S6C_ST_S6C_S6E_S6C_NS3_ISC_SS_EES6C_ST_S6C_ST_SV_S6C_ST_S49_S49_S6C_ST_S17_S17_S17_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_SX_S6C_ST_S6C_ST_SV_S6C_ST_SX_S6C_ST_SV_S6C_ST_SX_S6C_ST_SX_SV_S6C_ST_SX_S6C_ST_SX_S6C_ST_SV_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_SX_S6C_ST_SV_S6C_ST_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_EE` | 0x7ac928 | 6384 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x7c41a8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x7cfcd4 | 4 |

### `/bin/msg2dbus`

+49 / −43 functions · +5 / −5 objects

**New functions (49)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x3f4f0 | 12 |
| `_ZN11CameraProxy21ibis_supportedChangedEb` | 0x80ba8 | 100 |
| `_ZN11CameraProxy22lens_propertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0x81638 | 96 |
| `_ZN11CameraProxy31request_acc_state_activeChangedEb` | 0x83cb8 | 100 |
| `_ZNK15CameraProxyDbus24request_acc_state_activeEv` | 0x8dd48 | 20 |
| `_ZN15CameraProxyDbus19doRequest_acc_stateEv` | 0x8e210 | 20 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x90c90 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x90c98 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x90c98 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x90ca8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x90cc0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x90d70 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x90d80 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xa01e8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xa0280 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0xa0288 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0xa0408 | 200 |
| `_ZN15CameraProxyDbus17request_acc_stateEiP7QObject` | 0xd5908 | 688 |
| `_ZN15CameraProxyDbus23request_acc_stateResultEPK18PendingCallWatcherRN9HblmTypes14hblm_acc_stateE` | 0xd5bb8 | 2708 |
| `_ZNK15CameraProxyDbus14ibis_supportedEv` | 0xe5968 | 48 |
| `_ZNK15CameraProxyDbus15lens_propertiesEv` | 0xe5ea8 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17request_acc_stateEiP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfed90 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus33restart_live_view_full_zoom_timerEiP7QObjectE4$_24Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfedd0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus27set_dcam_ready_for_exposureEbiP7QObjectE4$_25Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfee10 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE4$_26Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfee50 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_face_targetEiiP7QObjectE4$_27Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfee90 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_hts_pollingEbiP7QObjectE4$_28Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfeed0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_ibis_modeEN9HblmTypes10E_IbisModeEiP7QObjectE4$_29Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfef10 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_live_viewEbiP7QObjectE4$_30Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfef50 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22set_live_view_extendedEbN9HblmTypes23E_LiveviewTransportModeEiP7QObjectE4$_31Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfef90 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_stop_downEbiP7QObjectE4$_32Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfefd0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus8set_zoomEbiP7QObjectE4$_33Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff010 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus23setup_dcam_stream_groupEN9HblmTypes13E_StreamGroupEiP7QObjectE4$_34Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xff050 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xff090 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14start_exposingEiP7QObjectE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff0d0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15start_recordingEiP7QObjectE4$_37Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff110 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13start_sessionEbiP7QObjectE4$_38Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff150 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE4$_39Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xff190 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_uml_sessionEiP7QObjectE4$_40Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff1d0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xff210 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13stop_exposingEiP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff250 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_find_focusEiP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff290 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus19stop_interval_timerEiP7QObjectE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff2d0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14stop_recordingEiP7QObjectE4$_45Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff310 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_self_timerEiP7QObjectE4$_46Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff350 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE4$_47Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff390 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_uml_sessionEiP7QObjectE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff3d0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus34teardown_current_dcam_stream_groupEiP7QObjectE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff410 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus10toggle_aelEiP7QObjectE4$_50Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xff450 | 64 |

**Removed functions (43)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x3f448 | 12 |
| `_ZN11CameraProxy25lens_is_af_allowedChangedEb` | 0x81298 | 100 |
| `_ZN11CameraProxy25lens_mf_ring_stateChangedEN9HblmTypes17E_LensMfRingStateE` | 0x813c0 | 96 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x90ad8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x90ae0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x90ae0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x90af0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x90b08 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x90bb8 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x90bc8 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xa0030 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xa00c8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0xa00d0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0xa0250 | 200 |
| `_ZNK15CameraProxyDbus18lens_is_af_allowedEv` | 0xe4e38 | 48 |
| `_ZNK15CameraProxyDbus18lens_mf_ring_stateEv` | 0xe4ec8 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus33restart_live_view_full_zoom_timerEiP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfde70 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus27set_dcam_ready_for_exposureEbiP7QObjectE4$_24Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfdeb0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE4$_25Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfdef0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_face_targetEiiP7QObjectE4$_26Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfdf30 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15set_hts_pollingEbiP7QObjectE4$_27Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfdf70 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_ibis_modeEN9HblmTypes10E_IbisModeEiP7QObjectE4$_28Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfdfb0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_live_viewEbiP7QObjectE4$_29Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfdff0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22set_live_view_extendedEbN9HblmTypes23E_LiveviewTransportModeEiP7QObjectE4$_30Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe030 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13set_stop_downEbiP7QObjectE4$_31Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe070 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus8set_zoomEbiP7QObjectE4$_32Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe0b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus23setup_dcam_stream_groupEN9HblmTypes13E_StreamGroupEiP7QObjectE4$_33Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe0f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_34Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe130 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14start_exposingEiP7QObjectE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe170 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15start_recordingEiP7QObjectE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe1b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13start_sessionEbiP7QObjectE4$_37Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe1f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE4$_38Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe230 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17start_uml_sessionEiP7QObjectE4$_39Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe270 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_dcam_streamEN9HblmTypes12E_DCAMStreamEiP7QObjectE4$_40Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xfe2b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus13stop_exposingEiP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe2f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_find_focusEiP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe330 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus19stop_interval_timerEiP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe370 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14stop_recordingEiP7QObjectE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe3b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus15stop_self_timerEiP7QObjectE4$_45Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe3f0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE4$_46Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe430 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus16stop_uml_sessionEiP7QObjectE4$_47Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe470 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus34teardown_current_dcam_stream_groupEiP7QObjectE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe4b0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus10toggle_aelEiP7QObjectE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xfe4f0 | 64 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x16fa6d | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S7_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EES7_NS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_SD_S10_SN_S10_S2K_S2K_NS3_INS8_16E_LensPropertiesES6_EES7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_S43_S3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_S4M_S3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_NS3_IS2L_S3S_EES3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x1d5738 | 6472 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKiS9_EESA_SC_SA_SC_SA_NS3_IKsS9_EESA_SC_SA_SA_SA_SA_NS3_IKbS9_EESA_NS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESR_SR_SA_SG_NS3_IKNSH_16E_SessionOptionsES9_EESC_SA_NS3_IKNSH_19E_SpiritLevelActionES9_EESG_SA_SA_NS3_IKNSH_13E_StreamGroupES9_EENS3_IRKSM_S9_EES13_SA_SA_SA_SU_SA_SA_SA_SA_SA_NS3_IKNSH_19E_LensDriveEndpointES9_EESA_S13_S13_SA_SR_SR_SR_SA_S10_SA_SA_SA_SA_SG_SA_SA_SC_SA_SG_SA_NS3_IKNSH_10E_IbisModeES9_EESA_SG_SA_SG_NS3_IKNSH_23E_LiveviewTransportModeES9_EESA_SG_SA_SG_SA_S10_SA_NS3_IKNSH_12E_DCAMStreamES9_EESA_SA_SA_SG_SA_NS3_IKNSH_13E_SessionTypeES9_EESA_SA_S1F_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x1db200 | 760 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x1e3388 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x1e66b4 | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x16e9e1 | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S7_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_S10_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_S4M_S3T_NS3_IS2L_S3S_EES3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x1d5780 | 6448 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKiS9_EESA_SC_SA_SC_SA_NS3_IKsS9_EESA_SC_SA_SA_SA_SA_NS3_IKbS9_EESA_NS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESR_SR_SA_SG_NS3_IKNSH_16E_SessionOptionsES9_EESC_SA_NS3_IKNSH_19E_SpiritLevelActionES9_EESG_SA_SA_NS3_IKNSH_13E_StreamGroupES9_EENS3_IRKSM_S9_EES13_SA_SA_SA_SU_SA_SA_SA_SA_SA_NS3_IKNSH_19E_LensDriveEndpointES9_EESA_S13_S13_SA_SR_SR_SR_SA_S10_SA_SA_SA_SG_SA_SA_SC_SA_SG_SA_NS3_IKNSH_10E_IbisModeES9_EESA_SG_SA_SG_NS3_IKNSH_23E_LiveviewTransportModeES9_EESA_SG_SA_SG_SA_S10_SA_NS3_IKNSH_12E_DCAMStreamES9_EESA_SA_SA_SG_SA_NS3_IKNSH_13E_SessionTypeES9_EESA_SA_S1F_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x1db210 | 752 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x1e3388 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x1e66b4 | 4 |

### `/bin/camera-test`

+24 / −15 functions · +5 / −5 objects

**New functions (24)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x46478 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x46fb0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x46fb8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x46fb8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x46fc8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x46fe0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x47090 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x470a0 | 12 |
| `_ZN15AccelCalibCycle23requestSpiritLevelStartEv` | 0x6a9a0 | 268 |
| `_ZN11CameraProxy21ibis_supportedChangedEb` | 0xc5ca8 | 100 |
| `_ZN11CameraProxy31request_acc_state_activeChangedEb` | 0xc6140 | 100 |
| `_ZNK15CameraProxyDbus24request_acc_state_activeEv` | 0xc9540 | 20 |
| `_ZN15CameraProxyDbus19doRequest_acc_stateEv` | 0xc95d0 | 20 |
| `_ZN15CameraProxyDbus17request_acc_stateEiP7QObject` | 0xe5138 | 688 |
| `_ZN15CameraProxyDbus23request_acc_stateResultEPK18PendingCallWatcherRN9HblmTypes14hblm_acc_stateE` | 0xe53e8 | 2708 |
| `_ZNK15CameraProxyDbus14ibis_supportedEv` | 0xe7cb8 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus17request_acc_stateEiP7QObjectE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xea9e0 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE3$_3Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xeaa20 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xeaa60 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xeaaa0 | 64 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1218c0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x121958 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x121960 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x121ae0 | 200 |

**Removed functions (15)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x462c8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x46e00 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x46e08 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x46e08 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x46e18 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x46e30 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x46ee0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x46ef0 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus14set_debug_lensEiP7QObjectE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xe9820 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus22start_session_extendedEN9HblmTypes13E_SessionTypeEiP7QObjectE3$_3Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xe9860 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15CameraProxyDbus12stop_sessionEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xe98a0 | 64 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1169e8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x116a80 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x116a88 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x116c08 | 200 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x166f4e | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESL_SL_SA_NS3_IKNSB_19E_SpiritLevelActionES9_EENS3_IKbS9_EESA_SA_SA_NS3_IKNSB_13E_SessionTypeES9_EESA_EE` | 0x1b9af8 | 112 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes10E_LensTypeES6_EENS3_IiS6_EESB_S7_NS3_INS8_12E_CameraTypeES6_EENS3_INS8_12E_DriveModesES6_EES7_NS3_INS8_9E_ExpModeES6_EES7_NS3_INS8_16E_ExposureStatusES6_EESB_S7_NS3_INS8_10E_BitDepthES6_EENS3_INS8_13E_ImageFormatES6_EENS3_I7QStringS6_EES7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EESQ_SB_SB_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbSV_EESW_SX_SW_NS3_IS9_SV_EESW_NS3_IiSV_EESW_SZ_SW_SX_SW_NS3_ISC_SV_EESW_NS3_ISE_SV_EESW_SX_SW_NS3_ISG_SV_EESW_SX_SW_NS3_ISI_SV_EESW_SZ_SW_SX_SW_NS3_ISK_SV_EESW_NS3_ISM_SV_EESW_NS3_IRKSO_SV_EESW_SX_SW_NS3_IsSV_EESW_NS3_ISR_SV_EESW_S19_SW_SZ_SW_SZ_SW_SX_SW_SX_SW_SX_SW_SX_SW_SX_SW_SX_EE` | 0x1ba370 | 712 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x1c54d0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x1c859c | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x164f38 | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CameraProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15CameraProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IKN9HblmTypes14E_ExposureTypeES9_EENS3_IRK4QMapI7QString8QVariantES9_EESL_SL_SA_NS3_IKNSB_19E_SpiritLevelActionES9_EENS3_IKbS9_EESA_SA_NS3_IKNSB_13E_SessionTypeES9_EESA_EE` | 0x1b9b68 | 104 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes10E_LensTypeES6_EENS3_IiS6_EESB_S7_NS3_INS8_12E_CameraTypeES6_EENS3_INS8_12E_DriveModesES6_EES7_NS3_INS8_9E_ExpModeES6_EES7_NS3_INS8_16E_ExposureStatusES6_EESB_NS3_INS8_10E_BitDepthES6_EENS3_INS8_13E_ImageFormatES6_EENS3_I7QStringS6_EES7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EESQ_SB_SB_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbSV_EESW_SX_SW_NS3_IS9_SV_EESW_NS3_IiSV_EESW_SZ_SW_SX_SW_NS3_ISC_SV_EESW_NS3_ISE_SV_EESW_SX_SW_NS3_ISG_SV_EESW_SX_SW_NS3_ISI_SV_EESW_SZ_SW_NS3_ISK_SV_EESW_NS3_ISM_SV_EESW_NS3_IRKSO_SV_EESW_SX_SW_NS3_IsSV_EESW_NS3_ISR_SV_EESW_S19_SW_SZ_SW_SZ_SW_SX_SW_SX_SW_SX_SW_SX_SW_SX_EE` | 0x1ba3d8 | 664 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x1c3d30 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x1c84c4 | 4 |

### `/bin/phocus`

+21 / −16 functions · +5 / −5 objects

**New functions (21)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x5a328 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x5f238 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x5f240 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x5f240 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x5f250 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x5f268 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x5f318 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x5f328 | 12 |
| `_ZN14PhocusNotifier18updateExpSimStatusEv` | 0xaabe0 | 72 |
| `_ZN11CameraProxy35exposure_control_mode_manualChangedEb` | 0xef5e0 | 100 |
| `_ZN11CameraProxy21ibis_supportedChangedEb` | 0xefd60 | 100 |
| `_ZN11CameraProxy22lens_propertiesChangedEN9HblmTypes16E_LensPropertiesE` | 0xf03c0 | 96 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xfb218 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xfb2b0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0xfb2b8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0xfb438 | 200 |
| `_ZN15CameraProxyDbus31setExposure_control_mode_manualEb` | 0x114028 | 308 |
| `_ZNK15CameraProxyDbus28exposure_control_mode_manualEv` | 0x117af0 | 48 |
| `_ZNK15CameraProxyDbus14ibis_supportedEv` | 0x117eb0 | 48 |
| `_ZNK15CameraProxyDbus15lens_propertiesEv` | 0x1181e0 | 48 |
| `_ZN8CStorage18tagCameraModelNameEv` | 0x170890 | 92 |

**Removed functions (16)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x5a160 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x5f070 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x5f078 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x5f078 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x5f088 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x5f0a0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x5f150 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x5f160 | 12 |
| `_ZN11CameraProxy25lens_is_af_allowedChangedEb` | 0xef768 | 100 |
| `_ZNK15CameraProxyDbus18lens_is_af_allowedEv` | 0x117190 | 48 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1561d0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x156268 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x156270 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x1563f0 | 200 |
| `_ZN6Common18cameraTypeAsStringEN9HblmTypes12E_CameraTypeE` | 0x16da90 | 580 |
| `_ZN8CStorage13tagCameraTypeEv` | 0x16f0f8 | 92 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x1a0afc | 28 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_135qt_meta_stringdata_PhocusNotifier_tEJN9QtPrivate20TypeAndForceCompleteI14PhocusNotifierNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK13PhocusMessageS9_EESA_NS3_IiS9_EESA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_NS3_IN9HblmTypes9E_LmModesES9_EESA_NS3_INSG_9E_ExpModeES9_EESA_SF_SA_NS3_IPK15VariantMapModelS9_EESA_SF_SA_SF_SA_NS3_INSG_13E_MediaStatusES9_EESA_SQ_SA_SF_SA_NS3_IRK7QStringS9_EESA_SU_SA_SU_SA_SU_SA_SU_SA_NS3_ItS9_EESA_NS3_IRK4QMapISR_8QVariantES9_EESA_SV_SA_NS3_INSG_12E_CameraModeES9_EESA_NS3_I5QListIiES9_EESA_S16_SA_S16_SA_SA_SA_NS3_IjS9_EESA_S17_SA_SA_NS3_INSG_16E_StopDownStatusES9_EESA_SF_SA_NS3_INSG_12E_WhiteModesES9_EESA_SF_SA_SF_SA_SA_SA_SF_SA_NS3_INSG_12E_ExitOptionES9_EESA_SF_SA_SF_SA_SF_SA_S1D_SA_SF_SA_SF_SA_NS3_INSG_20E_ExpBracketingParamES9_EESA_SF_SA_SF_SA_S1D_SA_NS3_INSG_26E_FocusBracketingStepSizesES9_EESA_SF_SA_SF_SA_SF_SA_NS3_INSG_27E_FocusBracketingStrategiesES9_EESA_S1D_SA_SF_SA_NS3_INSG_15E_StorageDeviceES9_EESA_NS3_INSG_13E_StorageModeES9_EESA_NS3_IbS9_EESA_NS3_INSG_14E_TetheredModeES9_EESA_NS3_INSG_14E_DistanceUnitES9_EESA_NS3_INSG_12E_CameraTypeES9_EESA_SA_SF_SA_SF_SA_SA_SA_SA_SA_SA_SA_S1O_SA_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x214320 | 1208 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESB_SB_S7_SB_NS3_INS8_20E_ExpBracketingParamES6_EESB_NS3_INS8_12E_ExitOptionES6_EESB_SB_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EESP_NS3_INS8_10E_CropModeES6_EESB_S7_NS3_INS8_12E_DriveModesES6_EESR_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SB_SB_NS3_INS8_9E_ExpModeES6_EESJ_S7_SB_NS3_INS8_21E_ExposureControlModeES6_EES7_S11_SB_NS3_INS8_16E_ExposureStatusES6_EESB_SV_S7_SB_SB_SB_SB_SB_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_27E_FocusBracketingStrategiesES6_EENS3_I4QMapI7QString8QVariantES6_EENS3_INS8_12E_FocusModesES6_EESJ_S1C_SJ_NS3_INS8_11E_FocusSizeES6_EES7_SX_SB_SB_SI_SB_SB_NS3_IS19_S6_EENS3_ItS6_EESJ_SJ_S7_S7_S1I_SJ_S1H_S1H_NS3_INS8_16E_LensPropertiesES6_EES1H_S7_S1H_SB_S7_NS3_INS8_15E_LiveViewStateES6_EENS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EESJ_NS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EESB_SB_SI_SB_S1I_NS3_INS8_24E_SpiritLevelOrientationES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESB_SB_SB_SE_SB_SB_SB_SE_SB_SB_S7_SB_NS3_INS8_14E_DistanceUnitES6_EESR_SB_SB_SB_NS3_INS8_12E_WhiteModesES6_EESB_SB_S7_SJ_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbS29_EES2A_S2B_S2A_NS3_IS9_S29_EES2A_NS3_IiS29_EES2A_NS3_IRKSD_S29_EES2A_S2D_S2A_S2D_S2A_S2B_S2A_S2D_S2A_NS3_ISF_S29_EES2A_S2D_S2A_NS3_ISH_S29_EES2A_S2D_S2A_S2D_S2A_NS3_IjS29_EES2A_NS3_ISK_S29_EES2A_NS3_ISM_S29_EES2A_NS3_ISO_S29_EES2A_S2M_S2A_NS3_ISQ_S29_EES2A_S2D_S2A_S2B_S2A_NS3_ISS_S29_EES2A_S2N_S2A_NS3_ISU_S29_EES2A_NS3_ISW_S29_EES2A_S2B_S2A_S2D_S2A_S2D_S2A_NS3_ISY_S29_EES2A_S2J_S2A_S2B_S2A_S2D_S2A_NS3_IS10_S29_EES2A_S2B_S2A_S2S_S2A_S2D_S2A_NS3_IS12_S29_EES2A_S2D_S2A_S2P_S2A_S2B_S2A_S2D_S2A_S2D_S2A_S2D_S2A_S2D_S2A_S2D_S2A_NS3_IS14_S29_EES2A_NS3_IS16_S29_EES2A_NS3_IRKS1B_S29_EES2A_NS3_IS1D_S29_EES2A_S2J_S2A_S2Y_S2A_S2J_S2A_NS3_IS1F_S29_EES2A_S2B_S2A_S2Q_S2A_S2D_S2A_S2D_S2A_S2I_S2A_S2D_S2A_S2D_S2A_NS3_IRKS19_S29_EES2A_NS3_ItS29_EES2A_S2J_S2A_S2J_S2A_S2B_S2A_S2B_S2A_S34_S2A_S2J_S2A_S33_S2A_S33_S2A_NS3_IS1J_S29_EES2A_S33_S2A_S2B_S2A_S33_S2A_S2D_S2A_S2B_S2A_NS3_IS1L_S29_EES2A_NS3_IS1N_S29_EES2A_NS3_IS1P_S29_EES2A_S2J_S2A_NS3_IS1R_S29_EES2A_NS3_IS1T_S29_EES2A_NS3_IS1V_S29_EES2A_S2D_S2A_S2D_S2A_S2I_S2A_S2D_S2A_S34_S2A_NS3_IS1X_S29_EES2A_NS3_IS1Z_S29_EES2A_NS3_IS21_S29_EES2A_S2D_S2A_S2D_S2A_S2D_S2A_S2G_S2A_S2D_S2A_S2D_S2A_S2D_S2A_S2G_S2A_S2D_S2A_S2D_S2A_S2B_S2A_S2D_S2A_NS3_IS23_S29_EES2A_S2N_S2A_S2D_S2A_S2D_S2A_S2D_S2A_NS3_IS25_S29_EES2A_S2D_S2A_S2D_S2A_S2B_S2A_S2J_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_S2A_S2B_EE` | 0x218478 | 3064 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x2226e8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x22a74c | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x1b62c8 | 29 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_135qt_meta_stringdata_PhocusNotifier_tEJN9QtPrivate20TypeAndForceCompleteI14PhocusNotifierNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK13PhocusMessageS9_EESA_NS3_IiS9_EESA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_NS3_IN9HblmTypes9E_LmModesES9_EESA_NS3_INSG_9E_ExpModeES9_EESA_SF_SA_NS3_IPK15VariantMapModelS9_EESA_SF_SA_SF_SA_NS3_INSG_13E_MediaStatusES9_EESA_SQ_SA_SF_SA_NS3_IRK7QStringS9_EESA_SU_SA_SU_SA_SU_SA_SU_SA_NS3_ItS9_EESA_NS3_IRK4QMapISR_8QVariantES9_EESA_SV_SA_NS3_INSG_12E_CameraModeES9_EESA_NS3_I5QListIiES9_EESA_S16_SA_S16_SA_SA_SA_NS3_IjS9_EESA_S17_SA_SA_NS3_INSG_16E_StopDownStatusES9_EESA_SF_SA_NS3_INSG_12E_WhiteModesES9_EESA_SF_SA_SF_SA_SA_SA_SF_SA_NS3_INSG_12E_ExitOptionES9_EESA_SF_SA_SF_SA_SF_SA_S1D_SA_SF_SA_SF_SA_NS3_INSG_20E_ExpBracketingParamES9_EESA_SF_SA_SF_SA_S1D_SA_NS3_INSG_26E_FocusBracketingStepSizesES9_EESA_SF_SA_SF_SA_SF_SA_NS3_INSG_27E_FocusBracketingStrategiesES9_EESA_S1D_SA_SF_SA_NS3_INSG_15E_StorageDeviceES9_EESA_NS3_INSG_13E_StorageModeES9_EESA_NS3_IbS9_EESA_NS3_INSG_14E_TetheredModeES9_EESA_NS3_INSG_14E_DistanceUnitES9_EESA_NS3_INSG_12E_CameraTypeES9_EESA_SA_SF_SA_SF_SA_SA_SA_SA_SA_SA_SA_S1O_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x214390 | 1200 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESB_SB_S7_SB_NS3_INS8_20E_ExpBracketingParamES6_EESB_NS3_INS8_12E_ExitOptionES6_EESB_SB_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EESP_NS3_INS8_10E_CropModeES6_EESB_S7_NS3_INS8_12E_DriveModesES6_EESR_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SB_SB_NS3_INS8_9E_ExpModeES6_EESJ_S7_SB_NS3_INS8_21E_ExposureControlModeES6_EES11_SB_NS3_INS8_16E_ExposureStatusES6_EESB_SV_S7_SB_SB_SB_SB_SB_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_27E_FocusBracketingStrategiesES6_EENS3_I4QMapI7QString8QVariantES6_EENS3_INS8_12E_FocusModesES6_EESJ_S1C_SJ_NS3_INS8_11E_FocusSizeES6_EESX_SB_SB_SI_SB_SB_NS3_IS19_S6_EENS3_ItS6_EESJ_SJ_S7_S7_S7_S1I_SJ_S1H_S1H_S1H_S7_S1H_SB_S7_NS3_INS8_15E_LiveViewStateES6_EENS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EESJ_NS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EESB_SB_SI_SB_S1I_NS3_INS8_24E_SpiritLevelOrientationES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESB_SB_SB_SE_SB_SB_SB_SE_SB_SB_S7_SB_NS3_INS8_14E_DistanceUnitES6_EESR_SB_SB_SB_NS3_INS8_12E_WhiteModesES6_EESB_SB_S7_SJ_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbS27_EES28_S29_S28_NS3_IS9_S27_EES28_NS3_IiS27_EES28_NS3_IRKSD_S27_EES28_S2B_S28_S2B_S28_S29_S28_S2B_S28_NS3_ISF_S27_EES28_S2B_S28_NS3_ISH_S27_EES28_S2B_S28_S2B_S28_NS3_IjS27_EES28_NS3_ISK_S27_EES28_NS3_ISM_S27_EES28_NS3_ISO_S27_EES28_S2K_S28_NS3_ISQ_S27_EES28_S2B_S28_S29_S28_NS3_ISS_S27_EES28_S2L_S28_NS3_ISU_S27_EES28_NS3_ISW_S27_EES28_S29_S28_S2B_S28_S2B_S28_NS3_ISY_S27_EES28_S2H_S28_S29_S28_S2B_S28_NS3_IS10_S27_EES28_S2Q_S28_S2B_S28_NS3_IS12_S27_EES28_S2B_S28_S2N_S28_S29_S28_S2B_S28_S2B_S28_S2B_S28_S2B_S28_S2B_S28_NS3_IS14_S27_EES28_NS3_IS16_S27_EES28_NS3_IRKS1B_S27_EES28_NS3_IS1D_S27_EES28_S2H_S28_S2W_S28_S2H_S28_NS3_IS1F_S27_EES28_S2O_S28_S2B_S28_S2B_S28_S2G_S28_S2B_S28_S2B_S28_NS3_IRKS19_S27_EES28_NS3_ItS27_EES28_S2H_S28_S2H_S28_S29_S28_S29_S28_S29_S28_S32_S28_S2H_S28_S31_S28_S31_S28_S31_S28_S29_S28_S31_S28_S2B_S28_S29_S28_NS3_IS1J_S27_EES28_NS3_IS1L_S27_EES28_NS3_IS1N_S27_EES28_S2H_S28_NS3_IS1P_S27_EES28_NS3_IS1R_S27_EES28_NS3_IS1T_S27_EES28_S2B_S28_S2B_S28_S2G_S28_S2B_S28_S32_S28_NS3_IS1V_S27_EES28_NS3_IS1X_S27_EES28_NS3_IS1Z_S27_EES28_S2B_S28_S2B_S28_S2B_S28_S2E_S28_S2B_S28_S2B_S28_S2B_S28_S2E_S28_S2B_S28_S2B_S28_S29_S28_S2B_S28_NS3_IS21_S27_EES28_S2L_S28_S2B_S28_S2B_S28_S2B_S28_NS3_IS23_S27_EES28_S2B_S28_S2B_S28_S29_S28_S2H_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_EE` | 0x2184e0 | 3016 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x223d38 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x22af64 | 4 |

### `/bin/camera-storage`

+13 / −12 functions · +3 / −3 objects

**New functions (13)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x57998 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x58ac0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x58ac8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x58ac8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x58ad8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x58af0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x58ba0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x58bb0 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x180158 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x1801f0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x1801f8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x180378 | 200 |
| `_ZN8CStorage18tagCameraModelNameEv` | 0x19c368 | 92 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x578d8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x58a00 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x58a08 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x58a08 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x58a18 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x58a30 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x58ae0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x58af0 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x175210 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x1752a8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x1752b0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x175430 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x1e552e | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x264b38 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x26870c | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x1e4170 | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x2631d8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x268624 | 4 |

### `/bin/camera-system`

+12 / −12 functions · +3 / −3 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x6abe0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x6abe8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x6abe8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x6abf8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x6ac10 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x6ac68 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x6ac78 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x6ac88 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x2cf098 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x2cf130 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x2cf138 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x2cf2b8 | 200 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x6abe0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x6abe8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x6abe8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x6abf8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x6ac10 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x6ac68 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x6ac78 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x6ac88 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x2c5f58 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x2c5ff0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x2c5ff8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x2c6178 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x4886d3 | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x579c60 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x5803bc | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x487bff | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x578680 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x5802f4 | 4 |

### `/bin/camera-upgrade`

+12 / −12 functions · +3 / −3 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2fc10 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x33578 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x33580 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x33580 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33590 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x335a8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x33658 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x33668 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc7410 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc74a8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0xc74b0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0xc7630 | 200 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2fb68 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x334d0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x334d8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x334d8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x334e8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33500 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x335b0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x335c0 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xbbc60 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xbbcf8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0xbbd00 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0xbbe80 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0xf218b | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x133ee8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x136650 | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0xf12df | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x132358 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x136554 | 4 |

### `/bin/hex-writer`

+12 / −12 functions · +3 / −3 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2a878 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x30a48 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x30a50 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x30a50 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x30a60 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x30a78 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x30b28 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x30b38 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x53db8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x53e50 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x53e58 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x53fd8 | 200 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2a878 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x30a48 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x30a50 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x30a50 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x30a60 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x30a78 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x30b28 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x30b38 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x53db8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x53e50 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x53e58 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x53fd8 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x89c04 | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0xe3500 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0xe5664 | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x89c14 | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0xe3500 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0xe5664 | 4 |

### `/bin/ibistool`

+12 / −12 functions · +3 / −3 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x259b8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x259c0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x259c0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x259d0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x259e8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x25a98 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x25aa8 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x4fc68 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x5dbd8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x5dc70 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x5dc78 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x5ddf8 | 200 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x259b8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x259c0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x259c0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x259d0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x259e8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x25a98 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x25aa8 | 12 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x4fc68 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x51648 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x516e0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x516e8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x51868 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x90bae | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0xc2b60 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0xc593c | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x8fcb6 | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0xc0da0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0xc582c | 4 |

### `/bin/imgtool`

+12 / −12 functions · +3 / −3 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x297d8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x2b7f8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x2b800 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x2b800 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2b810 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2b828 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x2b8d8 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x2b8e8 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x37b08 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x37ba0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x37ba8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x37d28 | 200 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x297d8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x2b510 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x2b518 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x2b518 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2b528 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2b540 | 20 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x2b558 | 152 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x2b5f0 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x2b600 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x2b610 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x2b618 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x2b798 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x5d30a | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0x81f90 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0x84a6c | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x5c402 | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0x801d0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0x8495c | 4 |

### `/bin/wmstool`

+12 / −12 functions · +3 / −3 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes16E_LensPropertiesEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x277a8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x33cb0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x33cb8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x33cb8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33cc8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33ce0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x33d90 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x33da0 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes16E_LensPropertiesELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x4fa40 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x4fad8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEv` | 0x4fae0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes16E_LensPropertiesEEiRK10QByteArray` | 0x4fc60 | 200 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes17E_LensMfRingStateEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x277a8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x33cb0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x33cb8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x33cb8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33cc8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x33ce0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x33d90 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x33da0 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes17E_LensMfRingStateELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x43798 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x43830 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEv` | 0x43838 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes17E_LensMfRingStateEEiRK10QByteArray` | 0x439b8 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes16E_LensPropertiesEE4nameE` | 0x7327a | 28 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes16E_LensPropertiesEE8metaTypeE` | 0xa28c0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_LensPropertiesEE14qt_metatype_idEvE11metatype_id` | 0xa5418 | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes17E_LensMfRingStateEE4nameE` | 0x723a2 | 29 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes17E_LensMfRingStateEE8metaTypeE` | 0xa0b70 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_LensMfRingStateEE14qt_metatype_idEvE11metatype_id` | 0xa530c | 4 |

### `/lib64/librcam.so`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_HBMount_set_long_exposure_ongoing` | 0xd70d8 | 132 |

### `/bin/dji_amt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_blackbox`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_cht`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sec`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/bin/phocusv1tool`

+0 / −0 functions · +0 / −0 objects

### `/bin/prodconfig-tool`

+0 / −0 functions · +0 / −0 objects

### `/bin/x2d_cal_eng_googletest`

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

### `/lib/modules/focaltech_tp_3383.ko`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **266** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/camera-gui`

<details><summary>新增 59 条字符串</summary>

````text
!`1N5gX
'@oKjz
(-<(IQ
)]|/DTp
5)I&aj
:UP\vI
=Ywv.U
C!PeQq
ENrhQ,
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
F"[J6M4y0x0 
F#yh~;R
G:qSQ\
HblmTypes::E_LensProperties
H|Qd+cw
Jz@IoS
KML.y"
KVf#$it
MYE+EY
N(L(/7
OJKP9v#
Og5q{uA
O{.@YI 
Pwzj>h
Skq0;z
UU6Cy+
Uc*5ui
WpcF8F?
X)r7<lR
]FteI.
`^o _K(o7
a6,84(
cpGg;WK
d1e2fef
d5=Z\mV
do7a_Q
hAFaIj
ibis_supported
ibis_supportedChanged
lens_properties
lens_propertiesChanged
lilgnc
mkf*Mf
n)!sK{:
raD<H3N
sj9T?N
tagCameraModelName
u1^WWo
uL,XHa
vw]:Ao
wr3&Fe
xx4&JJsd
yC^LVz$
|z%FlA3a
````

</details>

### `/bin/camera-service`

<details><summary>新增 30 条字符串</summary>

````text
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/daemons/camera/src/cpp/ibisspiritlevelhandler.cpp
::::::: (::::0::::
Close audio client player took
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
Unsupported setting
calib:
d1e2fef
hasLensControlRing
hasLensControlRingChanged
haslensControlRing
ibis_supported
ibis_supportedChanged
lensPropertiesChanged
lens_properties
lens_propertiesChanged
onHasLensControlRing
request_acc_state
tagCameraModelName
virtual void CameraObjectImpl::doRequest_acc_state(HblmTypes::hblm_acc_state &, const QDBusMessage &)
void CameraObjectImpl::updateExpoSim()
void IbisSpiritLevelHandler::do_spiritlevel(const HblmTypes::E_SpiritLevelAction, const bool)
x_axis
y_axis
z_axis
````

</details>

### `/bin/camera-expose`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
NNNNNNN=NENN
d1e2fef
doRequest_acc_state
ibis_supported
ibis_supported = %1
ibis_supportedChanged
lens_properties
lens_properties = %1
lens_propertiesChanged
request_acc_state_active
virtual bool CameraProxyDbus::request_acc_stateResult(const PendingCallWatcher *, HblmTypes::hblm_acc_state &)
````

### `/bin/phocus`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
d1e2fef
exposure_control_mode_manual
exposure_control_mode_manualChanged
ibis_supported
ibis_supportedChanged
kExpSimStatusCamParam
lens_properties
lens_propertiesChanged
setExposure_control_mode_manual
tagCameraModelName
updateExpSimStatus
````

### `/bin/odindb-send`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
NNNNNNN=NENN
d1e2fef
ibis_supported
ibis_supported = %1
ibis_supportedChanged
lens_properties
lens_properties = %1
lens_propertiesChanged
virtual bool CameraProxyDbus::request_acc_stateResult(const PendingCallWatcher *, HblmTypes::hblm_acc_state &)
````

### `/bin/msg2dbus`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
NNNNNNN=NENN
d1e2fef
ibis_supported
ibis_supportedChanged
lens_properties
lens_propertiesChanged
virtual bool CameraProxyDbus::request_acc_stateResult(const PendingCallWatcher *, HblmTypes::hblm_acc_state &)
````

### `/bin/camera-test`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
SSSVbSeShSSY\SSS_
d1e2fef
ibis_supported
ibis_supportedChanged
tagCameraModelName
virtual bool CameraProxyDbus::request_acc_stateResult(const PendingCallWatcher *, HblmTypes::hblm_acc_state &)
````

### `/bin/hex-writer`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
d1e2fef
ibis_supported = %1
ibis_supportedChanged
lens_properties = %1
lens_propertiesChanged
````

### `/bin/camera-storage`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
XCD 65E
d1e2fef
tagCameraModelName
````

### `/lib64/libaaa.so`

````text
!q@oG8-x
5741c8f
HtdI.@d
P@$`tys
Qs/@kb
Sg ?N@
[yT@-SY5D
jn\1)@
m@A+0du
qJH=gX@s
````

### `/bin/camera-upgrade`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
d1e2fef
tagCameraModelName
````

### `/bin/camera-system`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
d1e2fef
````

### `/bin/ibistool`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
````

### `/bin/imgtool`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
````

### `/bin/wmstool`

````text
E_LensProperties
E_LensProperties_HasControlRing
E_LensProperties_HasMfRing
E_LensProperties_Max
E_LensProperties_None
E_LensProperties_SupportAf
HblmTypes::E_LensProperties
````

### `/lib64/lib_vc_encoder.so`

````text
Error: hardware/dji/common/codec/verisilicon/encoder/source/hevc/hevcencapi.c, line 7542: 
Error: hardware/dji/common/codec/verisilicon/encoder/source/hevc/hevcencapi.c, line 7569: 
Error: hardware/dji/common/codec/verisilicon/encoder/source/hevc/hevcencapi.c, line 7588: 
Error: hardware/dji/common/codec/verisilicon/encoder/source/hevc/hevcencapi.c, line 7601: 
````

### `/lib64/librcam.so`

````text
1f8422c
[rcam]: [%s][%s:%d]Fetching %d capabilities in %d messages
[rcam]: [%s][%s:%d]NET_HAS_LENS_CONTROL_RING: %d, NET_HAS_AF_DISABLE: %d, NET_HAS_MF_ASSIST: %d, NET_HAS_DEEP_SLEEP_MODE:%d
b831ce9
````

### `/bin/dji_sys`

````text
13:33:19
13:33:20
Oct 31 2025
````

### `/lib64/libduml_frwk.so`

````text
13:29:52
13:29:54
Oct 31 2025
````

### `/lib64/libduml_orte.so`

````text
13:31:31
Oct 31 2025
orte 0.3.4, compiled: Oct 31 2025 13:31:31
````

### `/bin/dji_amt`

````text
13:31:26
Oct 31 2025
````

### `/bin/dji_blackbox`

````text
13:31:26
Oct 31 2025
````

### `/lib64/libdcam_pp.so`

````text
13:30:42
Oct 31 2025
````

### `/lib64/libproxy_nn_client.so`

````text
13:33:18
Oct 31 2025
````

### `/bin/phocusv1tool`

````text
kExpSimStatusCamParam
````

### `/bin/prodconfig-tool`

````text
b831ce9
````

### `/lib64/libgip.so`

````text
AB30RG16NV12NV16YU12YU24IMG4IMG3N3GIP10EGLContextE
````

### `/bin/dji_cht`

````text
````

### `/bin/dji_sec`

````text
````

### `/bin/x2d_cal_eng_googletest`

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

## Scripts & Config

共 5 个脚本/配置变更, 237 行 unified diff（context=3, 预算上限 2000 行）。

### `/bin/setup_usb.sh`

12 行

````diff
--- a//bin/setup_usb.sh
+++ b//bin/setup_usb.sh
@@ -110,6 +110,9 @@
 	ser_setting
 fi
 
+# modfiy sn to string descriptor product
+modify_product_sn.sh &
+
 # mpstate=0: pro; mpstate!=0: eng or factory
 product_state
 mpstate=$?
````

### `/bin/test_audio_pa_link.sh`

26 行

````diff
--- a//bin/test_audio_pa_link.sh
+++ b//bin/test_audio_pa_link.sh
@@ -15,9 +15,19 @@
 
 source test_common.sh
 
-DATA_BUS=1
-DATA_ADDRESS=0x34
-WHO_AM_I_REGISTER=0x00
-WHO_AM_I_VALUE=0x03 # First half of 16-bit ID value 0x0310
+product=$(product_detect)
+hw_revision=$(product_hwrev)
+
+if [ "$product" == "EC2107" ] && [ hw_revision -gt 4 ]; then
+    DATA_BUS=1
+    DATA_ADDRESS=0x34
+    WHO_AM_I_REGISTER=0x00
+    WHO_AM_I_VALUE=0x20
+else
+    DATA_BUS=1
+    DATA_ADDRESS=0x34
+    WHO_AM_I_REGISTER=0x00
+    WHO_AM_I_VALUE=0x03 # First half of 16-bit ID value 0x0310
+fi
 
 i2c_test $DATA_BUS $DATA_ADDRESS $WHO_AM_I_REGISTER $WHO_AM_I_VALUE "audio pa"
````

### `/build.prop`

13 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,7 +1,7 @@
 
-ro.vendor.build.date=Mon Apr 21 10:20:17 CST 2025
-ro.vendor.build.date.utc=1745202017
-ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/20201:userdebug/test-keys
+ro.vendor.build.date=Fri Oct 31 13:28:24 CST 2025
+ro.vendor.build.date.utc=1761888504
+ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/24849:userdebug/test-keys
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
-ro.dji.build.version=10.00.22.46
+ro.dji.build.version=10.00.25.21
 persist.dji.storage.exportable=0
 ro.logd.kernel=false
 ro.logd.size.stats=64K
````

### `/etc/lens_config.json`

175 行

````diff
--- a//etc/lens_config.json
+++ b//etc/lens_config.json
@@ -1482,6 +1482,13 @@
         "focal_length_val": [ 234.1562 , -16.2600 , 0.3720 ],
         "magnification_val": [ 0.0000 , 0.1095 , -0.0036 ],
         "nodal_distance_val": [ 212.5498 , 16.2000 , -0.6393 ]
+        },
+        {
+        "converter": "H Converter 1,7",
+        "total_conv_factor":  18,
+        "focal_length_val": [ 487.471 , -242.8083 , 75.3603 ],
+        "magnification_val": [ 0.0000 , 0.2288 , -0.0071 ],
+        "nodal_distance_val": [ 1028.67 , -328.6396 , 101.6971 ]
         }
         ]
       },
@@ -2619,93 +2626,93 @@
         {
         "zoom_segment": 1,
         "total_conv_factor": 0,
-        "focal_length_val": [ 38.3898 , -2.2090 , 0.0462 ],
-        "magnification_val": [ 0.0000 , 0.1344 , -0.0048 ],
-        "nodal_distance_val": [ 89.3686 , 2.1510 , -0.0637 ]
+        "focal_length_val": [ 38.8489 , -2.3002 , 0.0608 ],
+        "magnification_val": [ 0.0000 , 0.1352 , -0.0051 ],
+        "nodal_distance_val": [ 88.6777 , 2.2210 , -0.0521 ]
         },
         {
         "zoom_segment": 2,
         "total_conv_factor": 0,
-        "focal_length_val": [ 41.2771 , -2.5080 , 0.0609 ],
-        "magnification_val": [ 0.0000 , 0.1404 , -0.0052 ],
-        "nodal_distance_val": [ 87.3965 , 2.4410 , -0.0722 ]
+        "focal_length_val": [ 41.8049 , -2.6188 , 0.0696 ],
+        "magnification_val": [ 0.0000 , 0.1418 , -0.0053 ],
+        "nodal_distance_val": [ 86.6404 , 2.5340 , -0.0798 ]
         },
         {
         "zoom_segment": 3,
         "total_conv_factor": 0,
-        "focal_length_val": [ 44.3911 , -2.8880 , 0.0751 ],
-        "magnification_val": [ 0.0000 , 0.1455 , -0.0054 ],
-        "nodal_distance_val": [ 85.0029 , 2.8080 , -0.1045 ]
+        "focal_length_val": [ 44.9746 , -2.9895 , 0.0788 ],
+        "magnification_val": [ 0.0000 , 0.1488 , -0.0056 ],
+        "nodal_distance_val": [ 84.6789 , 2.9040 , -0.1024 ]
         },
         {
         "zoom_segment": 4,
         "total_conv_factor": 0,
-        "focal_length_val": [ 47.7693 , -3.3390 , 0.0923 ],
-        "magnification_val": [ 0.0000 , 0.1518 , -0.0057 ],
-        "nodal_distance_val": [ 82.7227 , 3.2200 , -0.1088 ]
+        "focal_length_val": [ 48.4005 , -3.4307 , 0.0914 ],
+        "magnification_val": [ 0.0000 , 0.1561 , -0.0059 ],
+        "nodal_distance_val": [ 82.7729 , 3.3449 , -0.1257 ]
         },
         {
         "zoom_segment": 5,
         "total_conv_factor": 0,
-        "focal_length_val": [ 51.3787 , -3.8410 , 0.1091 ],
-        "magnification_val": [ 0.0000 , 0.1601 , -0.0060 ],
-        "nodal_distance_val": [ 80.9245 , 3.7370 , -0.1442 ]
+        "focal_length_val": [ 52.1128 , -3.9554 , 0.1090 ],
+        "magnification_val": [ 0.0000 , 0.1638 , -0.0063 ],
+        "nodal_distance_val": [ 80.8989 , 3.8704 , -0.1541 ]
         },
         {
         "zoom_segment": 6,
         "total_conv_factor": 0,
-        "focal_length_val": [ 55.2696 , -4.4030 , 0.1242 ],
-        "magnification_val": [ 0.0000 , 0.1705 , -0.0067 ],
-        "nodal_distance_val": [ 79.5415 , 4.3300 , -0.1666 ]
+        "focal_length_val": [ 56.1284 , -4.5711 , 0.1318 ],
+        "magnification_val": [ 0.0000 , 0.1718 , -0.0068 ],
+        "nodal_distance_val": [ 79.0297 , 4.4932 , -0.1907 ]
         },
         {
         "zoom_segment": 7,
         "total_conv_factor": 0,
-        "focal_length_val": [ 59.4424 , -5.0680 , 0.1434 ],
-        "magnification_val": [ 0.0000 , 0.1805 , -0.0072 ],
-        "nodal_distance_val": [ 77.9944 , 5.0480 , -0.2138 ]
+        "focal_length_val": [ 60.4518 , -5.2798 , 0.1583 ],
+        "magnification_val": [ 0.0000 , 0.1803 , -0.0073 ],
+        "nodal_distance_val": [ 77.1354 , 5.2258 , -0.2375 ]
         },
         {
         "zoom_segment": 8,
         "total_conv_factor": 0,
-        "focal_length_val": [ 63.2658 , -5.7690 , 0.1715 ],
-        "magnification_val": [ 0.0000 , 0.1875 , -0.0078 ],
-        "nodal_distance_val": [ 76.1727 , 5.7540 , -0.2530 ]
+        "focal_length_val": [ 65.0743 , -6.0783 , 0.1859 ],
+        "magnification_val": [ 0.0000 , 0.1891 , -0.0078 ],
+        "nodal_distance_val": [ 75.1823 , 6.0796 , -0.2949 ]
         },
         {
         "zoom_segment": 9,
         "total_conv_factor": 0,
-        "focal_length_val": [ 68.0753 , -6.7090 , 0.2098 ],
-        "magnification_val": [ 0.0000 , 0.1962 , -0.0085 ],
-        "nodal_distance_val": [ 73.9450 , 6.7270 , -0.3337 ]
+        "focal_length_val": [ 69.9747 , -6.9580 , 0.2103 ],
+        "magnification_val": [ 0.0000 , 0.1986 , -0.0085 ],
+        "nodal_distance_val": [ 73.1337 , 7.0657 , -0.3623 ]
         },
         {
         "zoom_segment": 10,
         "total_conv_factor": 0,
-        "focal_length_val": [ 73.2273 , -7.7040 , 0.2356 ],
-        "magnification_val": [ 0.0000 , 0.2075 , -0.0092 ],
-        "nodal_distance_val": [ 71.8494 , 7.8740 , -0.4202 ]
+        "focal_length_val": [ 75.1189 , -7.9048 , 0.2258 ],
+        "magnification_val": [ 0.0000 , 0.2089 , -0.0092 ],
+        "nodal_distance_val": [ 70.9494 , 8.1944 , -0.4376 ]
         },
         {
         "zoom_segment": 11,
         "total_conv_factor": 0,
-        "focal_length_val": [ 78.7493 , -8.7370 , 0.2392 ],
-        "magnification_val": [ 0.0000 , 0.2203 , -0.0103 ],
-        "nodal_distance_val": [ 69.3568 , 9.2170 , -0.5176 ]
+        "focal_length_val": [ 80.4599 , -8.8992 , 0.2255 ],
+        "magnification_val": [ 0.0000 , 0.2203 , -0.0101 ],
+        "nodal_distance_val": [ 68.5860 , 9.4755 , -0.5174 ]
         },
         {
         "zoom_segment": 12,
         "total_conv_factor": 0,
-        "focal_length_val": [ 84.7125 , -9.8090 , 0.2112 ],
-        "magnification_val": [ 0.0000 , 0.2343 , -0.0115 ],
-        "nodal_distance_val": [ 66.3043 , 10.7500 , -0.5862 ]
+        "focal_length_val": [ 85.9379 , -9.9164 , 0.2007 ],
+        "magnification_val": [ 0.0000 , 0.2329 , -0.0112 ],
+        "nodal_distance_val": [ 65.9968 , 10.9181 , -0.5971 ]
         },
         {
         "zoom_segment": 13,
         "total_conv_factor": 0,
-        "focal_length_val": [ 91.1278 , -10.9200 , 0.1410 ],
-        "magnification_val": [ 0.0000 , 0.2495 , -0.0128 ],
-        "nodal_distance_val": [ 63.0088 , 12.5700 , -0.6822 ]
+        "focal_length_val": [ 91.4803 , -10.9260 , 0.1415 ],
+        "magnification_val": [ 0.0000 , 0.2471 , -0.0124 ],
+        "nodal_distance_val": [ 63.1319 , 12.5306 , -0.6707 ]
         },
         {
         "zoom_segment": 14,
@@ -2715,7 +2722,24 @@
         "nodal_distance_val": [ 59.9534 , 14.3200 , -0.7303 ]
         }
         ]
-      }
+      },
+      {
+        "focal_length": 65000,
+        "id": 2018,
+        "lens_make": "Hasselblad",
+        "lens_version": 2,
+        "meta_name": "XCD 65E",
+        "mount_type": "X",
+        "name": "XCD 65E",
+        "ibis_constants": [
+        {
+        "total_conv_factor": 0,
+        "focal_length_val": [ 63.0507 , -8.1160 , 0.5931 ],
+        "magnification_val": [ 0.0000 , 0.1188 , 0.0131 ],
+        "nodal_distance_val": [ 77.8800 , 5.9500 , -0.1789 ]
+        }
+        ]
+      }        
     ],
     "optics_groups": [
       {
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（965 行）</summary>

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
| `/bin/camera-expose` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.4 MB | +64.7 KB | system |
| `/bin/camera-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.4 MB | 45.4 MB | -5.7 KB | system |
| `/bin/camera-service` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.8 MB | 10.8 MB | -72 B | system |
| `/bin/camera-storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.4 MB | 3.4 MB | +96 B | system |
| `/bin/camera-system` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 MB | 7.6 MB | -32 B | system |
| `/bin/camera-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.6 MB | 2.6 MB | +1,016 B | system |
| `/bin/camera-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +8 B | system |
| `/bin/cat_wifi_param.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/check_and_format.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 702 B | 702 B | +0 B | system |
| `/bin/check_secure_debug` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/bin/cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/codec_yuv_generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/collect_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/copy_3dluts_files` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.0 KB | 12.0 KB | +0 B | system |
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
| `/bin/dji_amt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 79.4 KB | 79.4 KB | -8 B | system |
| `/bin/dji_audio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_blackbox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 337.8 KB | 337.8 KB | +0 B | system |
| `/bin/dji_cht` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.0 MB | 1.0 MB | +16 B | system |
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
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 876.8 KB | 876.8 KB | -8 B | system |
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
| `/bin/gip_tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.2 KB | 68.2 KB | +0 B | system |
| `/bin/hex-writer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | -296 B | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 786.2 KB | 786.2 KB | +0 B | system |
| `/bin/ibistool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | -16 B | system |
| `/bin/imgtool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 884.1 KB | 884.1 KB | -16 B | system |
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
| `/bin/modify_product_sn.sh` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 852 B | +852 B | system |
| `/bin/monkey-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 78.3 KB | 78.3 KB | +0 B | system |
| `/bin/mount_block_ext4.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/mpstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 750.2 KB | 750.2 KB | +0 B | system |
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | +520 B | system |
| `/bin/nnf_gtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525.3 KB | 525.3 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.6 KB | 133.6 KB | +0 B | system |
| `/bin/odindb-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.0 MB | 4.0 MB | +736 B | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 MB | 8.3 MB | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.1 MB | 3.1 MB | +208 B | system |
| `/bin/phocusv1tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 341.3 KB | 341.3 KB | +0 B | system |
| `/bin/pidstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 867.0 KB | 867.0 KB | +0 B | system |
| `/bin/ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/pinmux` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/bin/proc_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 416.2 KB | 416.2 KB | +0 B | system |
| `/bin/product_info` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | system |
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
| `/bin/setup_usb.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.6 KB | 2.7 KB | +65 B | system |
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
| `/bin/test_audio_pa_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 779 B | 1,008 B | +229 B | system |
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
| `/bin/test_lcd_backlight_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
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
| `/bin/test_recalibration.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
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
| `/bin/test_touch_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
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
| `/bin/wmstool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | -16 B | system |
| `/bin/x2bursttest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/x2d_cal_eng_googletest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 265.3 KB | 265.3 KB | +0 B | system |
| `/bin/x2loopback` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/x2pingpong` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/x2pingrecv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/build.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 KB | 1.9 KB | +0 B | system/vendor |
| `/compatibility_matrix.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 99.7 KB | 99.7 KB | +0 B | system |
| `/default.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 237 B | 237 B | +0 B | vendor |
| `/etc/80percent.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.0 KB | 12.0 KB | +0 B | system |
| `/etc/NOTICE.xml.gz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 94.3 KB | 94.3 KB | +0 B | system/vendor |
| `/etc/VERSION` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6 B | 6 B | +0 B | system |
| `/etc/ac_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 859 B | 859 B | +0 B | system |
| `/etc/adj/adj_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 335 B | 335 B | +0 B | system |
| `/etc/adj/grain_param_461.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | system |
| `/etc/adj/raw_proc_param_461.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 103.0 KB | 103.0 KB | +0 B | system |
| `/etc/audio.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/etc/audio_ec2107.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/etc/audio_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 601 B | 601 B | +0 B | system |
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
| `/etc/firmware/aw88166_acf.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.7 KB | 70.7 KB | +0 B | system |
| `/etc/firmware/aw8896_cfg.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124 B | 124 B | +0 B | system |
| `/etc/firmware/aw8896_fw_d.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 368 B | 368 B | +0 B | system |
| `/etc/firmware/aw8896_fw_e.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 412 B | 412 B | +0 B | system |
| `/etc/firmware/aw8896_reg.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 76 B | 76 B | +0 B | system |
| `/etc/firmware/bifrost_body_v1.3.3.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.9 KB | 23.9 KB | +0 B | system |
| `/etc/firmware/bifrost_grip_v1.3.3.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.5 KB | 22.5 KB | +0 B | system |
| `/etc/firmware/ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B | system |
| `/etc/firmware/ec2107_cpld.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B | system |
| `/etc/firmware/exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 414.8 KB | 415.2 KB | +392 B | system |
| `/etc/firmware/exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +672 B | system |
| `/etc/firmware/exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B | system |
| `/etc/firmware/goodix_cfg_group.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 790 B | 790 B | +0 B | system |
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
| `/etc/iq/config.fbs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.6 KB | 276.6 KB | +0 B | system |
| `/etc/iq/dji_rcam.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 139 B | 139 B | +0 B | system |
| `/etc/iq/ec1706_config.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.4 MB | 6.4 MB | +0 B | system |
| `/etc/iq/ec1706_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.9 MB | 18.9 MB | +0 B | system |
| `/etc/lens_config.json` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 158.6 KB | 159.4 KB | +777 B | system |
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
| `/etc/rm692e5.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.0 KB | 12.0 KB | +0 B | system |
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
| `/etc/vx050u0p.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.0 KB | 12.0 KB | +0 B | system |
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
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 374.0 KB | 374.0 KB | +0 B | system |
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
| `/lib/modules/focaltech_tp_3383.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.6 MB | 3.6 MB | +0 B | system |
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
| `/lib/modules/snd-soc-aw883xx.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.1 MB | 3.1 MB | +0 B | system |
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
| `/lib/modules/vc_decoder.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 405.0 KB | 404.5 KB | -568 B | system |
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
| `/lib64/camera/plugins/adj/libdcam_cp_adj.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 140.9 KB | 140.9 KB | +0 B | system |
| `/lib64/camera/plugins/dewarp/libdcam_dewarp_gdc_stitching.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 195.5 KB | 195.5 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_e2_lcdc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 135.1 KB | 135.1 KB | -8 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_null.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.7 KB | 197.7 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland_gfx.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.3 KB | 197.2 KB | -24 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland_preview.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.5 KB | 197.5 KB | +0 B | system |
| `/lib64/camera/plugins/hal/libdcam_cam_info_e2_ec1706_native.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 142.2 KB | 142.2 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_hevc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_jpeg.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_sw.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/lib_frog_e2_ec1706_native.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.7 KB | 84.7 KB | +0 B | system |
| `/lib64/camera/plugins/libdcam_x2d_cal_eng.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/link_node/libdcam_container_cache_link_node.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/mctf/libdcam_mctf.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.0 KB | 67.0 KB | -8 B | system |
| `/lib64/camera/plugins/pp_algo/libdcam_pp_e2_hiso.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.1 KB | 131.1 KB | +0 B | system |
| `/lib64/camera/plugins/pp_algo/libdcam_pp_rdns_grain.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_raw_reprocess.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_common.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 195.8 KB | 195.8 KB | -8 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_general.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_x2d.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_yuvraw_zsl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_video_single.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.6 KB | 131.6 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_async_deconv_blend_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_async_mctf_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_common_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 388.7 KB | 388.7 KB | -8 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_dsp_allocator_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_frame_adjust_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_isp_statistics_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_pdaf_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_pp_algo_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_reawb_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.0 KB | 131.0 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_rtp_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_stats_packer_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_x2d_histogram_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_x2d_ml_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.8 KB | 67.8 KB | +0 B | system |
| `/lib64/camera/plugins/venc/libdcam_venc_h26x.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/camera/plugins/venc/libdcam_venc_prores.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/venc/libdcam_venc_proresraw.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.2 KB | 131.2 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_dng_file_writer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 142.4 KB | 142.4 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_jpeg_file_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74.2 KB | 74.2 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_mp4_stream_async_writer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_mp4_stream_writer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_raw_stream_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_splitter_stream_av_sync_writer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/writer/libdcam_srt_rec_stream_writer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/ld-android.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.4 KB | 65.4 KB | +0 B | system |
| `/lib64/libAACdec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 452.1 KB | 452.1 KB | +0 B | system |
| `/lib64/libAACenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 516.1 KB | 516.1 KB | +0 B | system |
| `/lib64/libEGL_POWERVR_ROGUE.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.1 KB | 66.1 KB | +0 B | system |
| `/lib64/libGLESv2_POWERVR_ROGUE.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 MB | 3.2 MB | +0 B | system |
| `/lib64/libIMGegl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 514.8 KB | 514.8 KB | +0 B | system |
| `/lib64/libMessageTransport.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
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
| `/lib64/lib_vc_encoder.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 584.5 KB | 584.5 KB | +0 B | system |
| `/lib64/libaaa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 MB | 10.1 MB | +0 B | system |
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
| `/lib64/libdcam_capture_strategy.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libdcam_chip_port.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.1 KB | 72.1 KB | +0 B | system |
| `/lib64/libdcam_dump_frame.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/libdcam_e2_idm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_extention_node_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libdcam_fcali.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 644.4 KB | 644.4 KB | +0 B | system |
| `/lib64/libdcam_fnm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_fnm_dcf.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.6 KB | 195.6 KB | +0 B | system |
| `/lib64/libdcam_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | system |
| `/lib64/libdcam_image_file_writer_base.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 130.8 KB | 130.8 KB | +0 B | system |
| `/lib64/libdcam_iq_module.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.5 KB | 69.5 KB | +0 B | system |
| `/lib64/libdcam_iq_tplgy_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_media.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcam_media_file_mgr.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.7 KB | 131.7 KB | +0 B | system |
| `/lib64/libdcam_media_file_mgr_service.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.9 KB | 195.9 KB | +0 B | system |
| `/lib64/libdcam_meta_convert.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libdcam_metadata_util.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libdcam_muxer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 406.5 KB | 406.5 KB | +0 B | system |
| `/lib64/libdcam_muxer_engine.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libdcam_pdmonitor.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.3 MB | +0 B | system |
| `/lib64/libdcam_protobuf_dbginfo.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libdcam_protobuf_metadata.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 132.1 KB | 132.1 KB | +0 B | system |
| `/lib64/libdcam_shooter_base_still.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.8 KB | 131.8 KB | +0 B | system |
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
| `/lib64/libduml_hal_cam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 741.5 KB | 741.5 KB | +0 B | system |
| `/lib64/libduml_mux_databuffer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_orte.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 194.2 KB | 194.2 KB | +0 B | system |
| `/lib64/libduml_osal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.4 KB | 66.4 KB | +0 B | system |
| `/lib64/libduml_payload.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_rpc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_shineIO.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.8 KB | 130.8 KB | +0 B | system |
| `/lib64/libduml_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 517.4 KB | 517.4 KB | +0 B | system |
| `/lib64/libduml_vcodec.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 324.3 KB | 324.3 KB | +0 B | system |
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
| `/lib64/libgip.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 196.9 KB | 196.9 KB | +16 B | system |
| `/lib64/libgip_duss.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libgip_filter_lab.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.2 KB | 131.2 KB | -16 B | system |
| `/lib64/libgip_filter_statistics.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
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
| `/lib64/librcam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | -8 B | system |
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
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | -17 B | system |
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
