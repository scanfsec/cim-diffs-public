# X1D II 50C: 1.3.0 ➜ 1.4.0

> 生成时间: 2026-10-07T06:03:50 · CIM 日期: 2020-07-15 ➜ 2020-10-21 · 条目: 4 ➜ 4 · 源: `X1D_II_50C_v1_3_0.cim` ➜ `X1D_II_50C_v1_4_0.cim`

## Summary

文件树 +7/-2/~173；CIM 条目 +0/-0/~2；OTA 镜像 ~5 变更 / 0 未变；符号 +338/-65 funcs, +687/-583 objs；新增字符串 1609 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `hbmanual.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 64.0 MB | 64.0 MB | +0 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 149.0 MB | 150.7 MB | +1.7 MB |
| `hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 2 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 2

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 MB | 7.3 MB | +64 B |
| `recovery.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.2 MB | 22.2 MB | +0 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 230.2 MB | 234.0 MB | +3.9 MB |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.7 MB | 22.7 MB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 5 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `lib` | 2 | 0 | 64 | 141 | 0 |
| `bin` | 2 | 0 | 37 | 376 | 0 |
| `firmware` | 0 | 0 | 37 | 0 | 0 |
| `etc` | 2 | 2 | 18 | 140 | 0 |
| `ta` | 0 | 0 | 15 | 0 | 0 |
| `(root)` | 0 | 0 | 2 | 0 | 0 |
| `data` | 1 | 0 | 0 | 0 | 0 |
| `usr` | 0 | 0 | 0 | 29 | 0 |
| `xbin` | 0 | 0 | 0 | 38 | 0 |

明细 906 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+338 / −65** functions, **+687 / −583** objects（50 个变更 ELF, 另有 51 个未列出）。

### `/lib/libappscommon.so`

+96 / −11 functions · +12 / −0 objects

**New functions (96)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j` | 0x64220 | 2248 |
| `_ZNK9LensProxy16distance_scale_0Ev` | 0x84d30 | 40 |
| `_ZNK9LensProxy16distance_scale_1Ev` | 0x84d58 | 40 |
| `_ZNK9LensProxy16distance_scale_2Ev` | 0x84d80 | 40 |
| `_ZNK9LensProxy13shutter_countEv` | 0x85054 | 44 |
| `_ZNK11ConfigProxy12dump_previewEv` | 0x94918 | 40 |
| `_ZNK11ConfigProxy19interval_ae_enabledEv` | 0x94ed4 | 44 |
| `_ZNK11ConfigProxy17show_huawei_shareEv` | 0x953f8 | 40 |
| `_ZNK11ConfigProxy17wifi_power_storedEv` | 0x95c1c | 44 |
| `_ZN11ConfigProxy15setDump_previewEb` | 0x9a17c | 228 |
| `_ZN11ConfigProxy22setInterval_ae_enabledEb` | 0x9c0f4 | 236 |
| `_ZN11ConfigProxy20setShow_huawei_shareEb` | 0x9dcfc | 232 |
| `_ZN11ConfigProxy20setWifi_power_storedEb` | 0xa09f0 | 228 |
| `_ZNK11CameraProxy30can_reprocess_raw_frame_bufferEv` | 0xcd1ac | 40 |
| `_ZNK11CameraProxy16liveview_allowedEv` | 0xcd67c | 44 |
| `_ZN11CameraProxy24request_img_transfer_usbE5QListI4QMapI7QString8QVariantEEji` | 0xd24a8 | 432 |
| `_ZN7AeProxy27do_reset_ael_after_exposureEi` | 0xdff04 | 624 |
| `_ZNK11PhocusProxy10video_modeEv` | 0xee740 | 40 |
| `_ZN10ErrorProxy6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_ji` | 0x10b080 | 912 |
| `_ZNK8WmsProxy8bt_powerEv` | 0x11a7e4 | 40 |
| `_ZN8WmsProxy10wifi_powerEbi` | 0x11c984 | 644 |
| `_ZNK12HwshareProxy11can_suspendEv` | 0x124468 | 36 |
| `_ZNK12HwshareProxy11device_nameEv` | 0x12448c | 40 |
| `_ZNK12HwshareProxy11device_typeEv` | 0x1244b4 | 40 |
| `_ZNK12HwshareProxy6statusEv` | 0x1244dc | 40 |
| `_ZNK12HwshareProxy17transfer_progressEv` | 0x124504 | 40 |
| `_ZN12HwshareProxy5startEi` | 0x125c08 | 564 |
| `_ZN12HwshareProxy4stopEi` | 0x125e3c | 564 |
| `_ZN12HwshareProxy8transferERK7QString5QListI4QMapIS0_8QVariantEEi` | 0x126070 | 1356 |
| `_ZNK12HwshareProxy11device_listEv` | 0x1265bc | 180 |
| `_ZN12HwshareProxyC1EP7QObjectb` | 0x126670 | 1224 |
| `_ZN12HwshareProxyC2EP7QObjectb` | 0x126670 | 1224 |
| `_ZN12HwshareProxy19onPropertiesChangedERK7QStringRK4QMapIS0_8QVariantE` | 0x126b38 | 8908 |
| `_ZN9QtPrivate11QSlotObjectIM21HwshareProxyInterfaceFvvENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x128e04 | 148 |
| `_ZN9QtPrivate11QSlotObjectIM21HwshareProxyInterfaceFvbENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x128e98 | 160 |
| `_ZN9QtPrivate11QSlotObjectIM12HwshareProxyFvRK7QStringRK4QMapIS2_8QVariantEENS_4ListIJS4_S9_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x128f38 | 152 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE8DestructEPv` | 0x130b70 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE9ConstructEPvPKv` | 0x130b74 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE8DestructEPv` | 0x1314d0 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE9ConstructEPvPKv` | 0x1314d4 | 20 |
| `_ZN3Bus19isReturnStatusFatalEN9HblmTypes14E_ReturnStatusE` | 0x133014 | 36 |
| `_ZN11IpcMetadatalsER13QDBusArgumentRKNS_17HwshareDeviceInfoE` | 0x136bcc | 60 |
| `_ZN11IpcMetadatarsERK13QDBusArgumentRNS_17HwshareDeviceInfoE` | 0x136c08 | 60 |
| `_ZN11IpcMetadata13tagReturnViewEv` | 0x136c44 | 16 |
| `_ZN11IpcMetadata24tagFileSelectionMaxLimitEv` | 0x136c54 | 20 |
| `_ZN11IpcMetadata35tagHwshareTransferSuccessImageCountEv` | 0x136c68 | 20 |
| `_ZN11IpcMetadata35tagHwshareTransferSuccessVideoCountEv` | 0x136c7c | 20 |
| `_ZN11IpcMetadata34tagHwshareTransferFailedImageCountEv` | 0x136c90 | 20 |
| `_ZN11IpcMetadata34tagHwshareTransferFailedVideoCountEv` | 0x136ca4 | 20 |
| `_ZN5HLens15getSerialNumberEP17SucProxyInterfacePK7QObjectNSt3__18functionIFvRK7QStringEEENS6_IFvvEEE` | 0x145ad4 | 1200 |

<details><summary>… 另 46 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZNSt3__18functionIFvRK7QStringEEC1ERKS5_` | 0x14648c | 80 |
| `_ZNSt3__18functionIFvRK7QStringEEC2ERKS5_` | 0x14648c | 80 |
| `_ZNSt3__18functionIFvRK7QStringEEC1EOS5_` | 0x1465b4 | 96 |
| `_ZNSt3__18functionIFvRK7QStringEEC2EOS5_` | 0x1465b4 | 96 |
| `_ZN6CErrorC1EN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantEi` | 0x151330 | 216 |
| `_ZN6CErrorC2EN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantEi` | 0x151330 | 216 |
| `_ZN18LensProxyInterface23distance_scale_0ChangedEj` | 0x16757c | 60 |
| `_ZN18LensProxyInterface23distance_scale_1ChangedEj` | 0x1675b8 | 60 |
| `_ZN18LensProxyInterface23distance_scale_2ChangedEj` | 0x1675f4 | 60 |
| `_ZN18LensProxyInterface20shutter_countChangedEi` | 0x167a2c | 60 |
| `_ZN20ConfigProxyInterface19dump_previewChangedEb` | 0x169cf8 | 60 |
| `_ZN20ConfigProxyInterface26interval_ae_enabledChangedEb` | 0x16a52c | 60 |
| `_ZN20ConfigProxyInterface24show_huawei_shareChangedEb` | 0x16ac70 | 60 |
| `_ZN20ConfigProxyInterface24wifi_power_storedChangedEb` | 0x16b828 | 60 |
| `_ZN20CameraProxyInterface37can_reprocess_raw_frame_bufferChangedEb` | 0x17a304 | 60 |
| `_ZN20CameraProxyInterface23liveview_allowedChangedEb` | 0x17aa0c | 60 |
| `_ZN20PhocusProxyInterface17video_modeChangedEN9HblmTypes11E_VideoModeE` | 0x1818b8 | 60 |
| `_ZN17WmsProxyInterface15bt_powerChangedEb` | 0x187d20 | 60 |
| `_ZNK21HwshareProxyInterface10metaObjectEv` | 0x188ae4 | 36 |
| `_ZN21HwshareProxyInterface18can_suspendChangedEb` | 0x188b08 | 60 |
| `_ZN21HwshareProxyInterface18device_listChangedE4QMapI7QString8QVariantE` | 0x188b44 | 52 |
| `_ZN21HwshareProxyInterface18device_nameChangedERK7QString` | 0x188b78 | 52 |
| `_ZN21HwshareProxyInterface18device_typeChangedEN9HblmTypes19E_HwShareDeviceTypeE` | 0x188bac | 60 |
| `_ZN21HwshareProxyInterface13statusChangedEN9HblmTypes15E_HwShareStatusE` | 0x188be8 | 60 |
| `_ZN21HwshareProxyInterface24transfer_progressChangedEi` | 0x188c24 | 60 |
| `_ZN21HwshareProxyInterface6syncedEv` | 0x188c60 | 24 |
| `_ZN21HwshareProxyInterface16availableChangedEb` | 0x188c78 | 60 |
| `_ZN21HwshareProxyInterface11qt_metacastEPKc` | 0x189268 | 80 |
| `_ZN21HwshareProxyInterface11qt_metacallEN11QMetaObject4CallEiPPv` | 0x1892b8 | 184 |
| `_Z17qRegisterMetaTypeIN9HblmTypes15E_HwShareStatusEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x189370 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes19E_HwShareDeviceTypeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x1894a8 | 312 |
| `_ZN11CameraProxy26doRequest_img_transfer_usbE5QListI4QMapI7QString8QVariantEEj` | 0x192bf0 | 180 |
| `_ZN7AeProxy29doDo_reset_ael_after_exposureEv` | 0x193474 | 16 |
| `_ZN10ErrorProxy8doReportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_j` | 0x196fb4 | 368 |
| `_ZN8WmsProxy12doWifi_powerEb` | 0x198798 | 16 |
| `_ZNK12HwshareProxy10metaObjectEv` | 0x199170 | 36 |
| `_ZN12HwshareProxy11qt_metacastEPKc` | 0x199194 | 80 |
| `_ZN12HwshareProxy11qt_metacallEN11QMetaObject4CallEiPPv` | 0x199730 | 96 |
| `_ZN12HwshareProxy7doStartEv` | 0x199790 | 16 |
| `_ZN12HwshareProxy6doStopEv` | 0x1997a0 | 16 |
| `_ZNK12HwshareProxy8isSyncedEv` | 0x1997b0 | 12 |
| `_ZNK12HwshareProxy11isAvailableEv` | 0x1997bc | 12 |
| `_ZN12HwshareProxyD1Ev` | 0x1997c8 | 7044 |
| `_ZN12HwshareProxyD2Ev` | 0x1997c8 | 7044 |
| `_ZN12HwshareProxyD0Ev` | 0x19b34c | 7052 |
| `_ZN12HwshareProxy10doTransferERK7QString5QListI4QMapIS0_8QVariantEE` | 0x19ced8 | 184 |

</details>

**Removed functions (11)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK7QStringS6_j` | 0x61a74 | 1284 |
| `_ZNK11ConfigProxy10wifi_powerEv` | 0x912f8 | 44 |
| `_ZN11ConfigProxy13setWifi_powerEb` | 0x9bed8 | 228 |
| `_ZN10ErrorProxy6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK7QStringS6_ji` | 0x105d5c | 864 |
| `_ZN5HLens16getModuleCounterEP17SucProxyInterfacePK7QObjectNSt3__18functionIFvjEEENS6_IFvvEEE` | 0x13bb14 | 1376 |
| `_ZNSt3__18functionIFvjEED1Ev` | 0x13c204 | 68 |
| `_ZNSt3__18functionIFvjEED2Ev` | 0x13c204 | 68 |
| `_ZN6CErrorC1EN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionEi` | 0x146e00 | 28 |
| `_ZN6CErrorC2EN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionEi` | 0x146e00 | 28 |
| `_ZN20ConfigProxyInterface17wifi_powerChangedEb` | 0x160910 | 60 |
| `_ZN10ErrorProxy8doReportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK7QStringS6_j` | 0x18a9e4 | 60 |

**New objects (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTS21HwshareProxyInterface` | 0x1d9070 | 24 |
| `_ZTS12HwshareProxy` | 0x1e00b8 | 15 |
| `_ZTI21HwshareProxyInterface` | 0x1f4838 | 12 |
| `_ZTV21HwshareProxyInterface` | 0x1f4848 | 112 |
| `_ZN21HwshareProxyInterface16staticMetaObjectE` | 0x1f48b8 | 24 |
| `_ZTI12HwshareProxy` | 0x1f6930 | 12 |
| `_ZTV12HwshareProxy` | 0x1f6940 | 116 |
| `_ZN12HwshareProxy16staticMetaObjectE` | 0x1f69b4 | 24 |
| `_ZZN11QMetaTypeIdIN9HblmTypes19E_HwShareDeviceTypeEE14qt_metatype_idEvE11metatype_id` | 0x201e90 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_HwShareStatusEE14qt_metatype_idEvE11metatype_id` | 0x202020 | 4 |
| `_ZN6CError12TAG_METADATAE` | 0x2022f4 | 4 |
| `_ZN6CError11TAG_TIMEOUTE` | 0x2022f8 | 4 |

### `/bin/storage`

+69 / −26 functions · +43 / −14 objects

**New functions (69)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate8RefCount5derefEv.part.35` | 0x138f0 | 32 |
| `_ZN7QStringD2Ev.part.36` | 0x13910 | 24 |
| `_ZN7QStringD2Ev.part.25` | 0x14178 | 24 |
| `_ZN9QtPrivate8RefCount5derefEv.part.28` | 0x4d5f0 | 32 |
| `_ZN9QtPrivate8RefCount3refEv.part.29` | 0x4d610 | 28 |
| `_ZNK14QSharedPointerI11FileContentE3refEv.isra.35` | 0x4d62c | 56 |
| `_ZNK14QSharedPointerI9CacheItemE3refEv.isra.36` | 0x4d664 | 56 |
| `_ZN5QListI8QVariantE7deallocEPN9QListData4DataE.isra.45` | 0x4d69c | 84 |
| `_ZN13ReprocessTask18setCanReprocessRawEb` | 0x4d758 | 20 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEEUlbE_Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x4d76c | 48 |
| `_ZN13ReprocessTask9setResultEN9HblmTypes14E_ReturnStatusERK7QString` | 0x4d79c | 56 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEENKUlRK7QStringy4QMapIS7_8QVariantEE0_clES9_ySC_EUlP18PendingCallWatcherE_Li1ENS_4ListIJSF_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x4d7d4 | 348 |
| `_ZN13ReprocessTask3runER11TaskControl` | 0x4e608 | 984 |
| `_ZThn8_N13ReprocessTask3runER11TaskControl` | 0x4e9e0 | 8 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEEUlRK7QStringy4QMapIS7_8QVariantEE0_Li3ENS_4ListIJS9_ySC_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x4e9e8 | 684 |
| `_ZN13ReprocessTaskC1ERK7QStringRK14QSharedPointerI11ImageMemoryE4QMapIS0_8QVariantEb` | 0x4ec94 | 324 |
| `_ZN13ReprocessTaskC2ERK7QStringRK14QSharedPointerI11ImageMemoryE4QMapIS0_8QVariantEb` | 0x4ec94 | 324 |
| `_ZN13ReprocessTaskD1Ev` | 0x4edd8 | 308 |
| `_ZN13ReprocessTaskD2Ev` | 0x4edd8 | 308 |
| `_ZThn8_N13ReprocessTaskD1Ev` | 0x4ef0c | 8 |
| `_ZN13ReprocessTaskD0Ev` | 0x4ef14 | 28 |
| `_ZThn8_N13ReprocessTaskD0Ev` | 0x4ef30 | 8 |
| `_ZN5QListI14QSharedPointerI11FileContentEE7deallocEPN9QListData4DataE.isra.83` | 0x5029c | 88 |
| `_ZN8QMapNodeIj14QSharedPointerI11FileContentEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.93` | 0x502f4 | 1632 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEEUlRK7QStringN9HblmTypes14E_ReturnStatusES9_E1_Li3ENS_4ListIJS9_SB_S9_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x512a0 | 788 |
| `_ZN5QListI14QSharedPointerI9CacheItemEE7deallocEPN9QListData4DataE.isra.64` | 0x51e70 | 88 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE8DestructEPv` | 0x56e14 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE9ConstructEPvPKv` | 0x56e18 | 20 |
| `_ZN19RunControllableTaskIbE3runEv` | 0x57128 | 344 |
| `_ZThn8_N19RunControllableTaskIbE3runEv` | 0x57280 | 8 |
| `_Z17qRegisterMetaTypeIN9HblmTypes14E_ReturnStatusEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x572f0 | 296 |
| `_ZN9QtPrivate15ResultStoreBase5clearIbEEvv` | 0x574d4 | 340 |
| `_ZN16QFutureInterfaceIbED1Ev` | 0x57628 | 68 |
| `_ZN16QFutureInterfaceIbED2Ev` | 0x57628 | 68 |
| `_ZN16QFutureInterfaceIbED0Ev` | 0x5766c | 76 |
| `_ZN19RunControllableTaskIbED1Ev` | 0x576b8 | 132 |
| `_ZN19RunControllableTaskIbED2Ev` | 0x576b8 | 132 |
| `_ZThn8_N19RunControllableTaskIbED1Ev` | 0x5773c | 8 |
| `_ZN19RunControllableTaskIbED0Ev` | 0x57744 | 140 |
| `_ZThn8_N19RunControllableTaskIbED0Ev` | 0x577d0 | 8 |
| `_ZN5QListI8QVariantE7deallocEPN9QListData4DataE.isra.34` | 0x6a4f4 | 84 |
| `_ZN11FileContent11dump4kImageE7QString` | 0x6ea74 | 372 |
| `_ZN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_E10runFunctorEv` | 0x6ec18 | 20 |
| `_ZN12QtConcurrent19RunFunctionTaskBaseIvE3runEv` | 0x6ec2c | 4 |
| `_ZThn8_N12QtConcurrent19RunFunctionTaskBaseIvE3runEv` | 0x6ec30 | 8 |
| `_ZN16QFutureInterfaceIvED1Ev` | 0x6ec58 | 40 |
| `_ZN16QFutureInterfaceIvED2Ev` | 0x6ec58 | 40 |
| `_ZN16QFutureInterfaceIvED0Ev` | 0x6ec80 | 48 |
| `_ZN12QtConcurrent15RunFunctionTaskIvE3runEv` | 0x6edd8 | 220 |
| `_ZThn8_N12QtConcurrent15RunFunctionTaskIvE3runEv` | 0x6eeb4 | 8 |

<details><summary>… 另 19 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_ED1Ev` | 0x6f3d8 | 276 |
| `_ZN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_ED2Ev` | 0x6f3d8 | 276 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_ED1Ev` | 0x6f4ec | 8 |
| `_ZN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_ED0Ev` | 0x6f4f4 | 284 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_ED0Ev` | 0x6f610 | 8 |
| `_ZN5Tasks11dump4kImageERK14QSharedPointerI11ImageMemoryERK7QString` | 0x70f14 | 8 |
| `_ZN5QListI14QSharedPointerI12DussMemShareEE7deallocEPN9QListData4DataE.isra.37` | 0x7cb64 | 176 |
| `_ZN5QListI14QSharedPointerI11ImageMemoryEE7deallocEPN9QListData4DataE.isra.31` | 0x7cc14 | 176 |
| `_ZN5QListI4QMapI7QString8QVariantEE7deallocEPN9QListData4DataE.isra.43` | 0x7cd40 | 144 |
| `_ZN5QListI7QStringEC2ERKS1_.part.29` | 0xd30a4 | 152 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.33` | 0xd313c | 132 |
| `_ZNK3Dcf20storeOnSDAndTetheredEv` | 0xd3604 | 24 |
| `_ZN5QListI7QStringEpLERKS1_` | 0xd8348 | 376 |
| `_ZNK13ReprocessTask10metaObjectEv` | 0xe1d9c | 36 |
| `_ZN13ReprocessTask9reprocessERK7QStringy4QMapIS0_8QVariantE` | 0xe1de4 | 68 |
| `_ZN13ReprocessTask14reprocessErrorERK7QStringN9HblmTypes14E_ReturnStatusES2_` | 0xe1e28 | 68 |
| `_ZN13ReprocessTask18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0xe2464 | 4092 |
| `_ZN13ReprocessTask11qt_metacastEPKc` | 0xe3460 | 120 |
| `_ZN13ReprocessTask11qt_metacallEN11QMetaObject4CallEiPPv` | 0xe3550 | 96 |

</details>

**Removed functions (26)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate8RefCount5derefEv.part.26` | 0x4ce68 | 32 |
| `_ZN9QtPrivate8RefCount3refEv.part.27` | 0x4ce88 | 28 |
| `_ZNK14QSharedPointerI11ImageMemoryE3refEv.isra.31` | 0x4cea4 | 56 |
| `_ZNK14QSharedPointerI11FileContentE3refEv.isra.33` | 0x4cedc | 56 |
| `_ZNK14QSharedPointerI9CacheItemE3refEv.isra.34` | 0x4cf14 | 56 |
| `_ZN5QListI8QVariantE7deallocEPN9QListData4DataE.isra.44` | 0x4cf4c | 84 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.42` | 0x4cfa0 | 72 |
| `_ZN16ReprocessRequestC1ERK7QStringRK4QMapIS0_8QVariantERK14QSharedPointerI11ImageMemoryERK10QByteArray` | 0x4d140 | 372 |
| `_ZN16ReprocessRequestC2ERK7QStringRK4QMapIS0_8QVariantERK14QSharedPointerI11ImageMemoryERK10QByteArray` | 0x4d140 | 372 |
| `_ZN16ReprocessRequestD1Ev` | 0x4db70 | 296 |
| `_ZN16ReprocessRequestD2Ev` | 0x4db70 | 296 |
| `_ZN16ReprocessRequestD0Ev` | 0x4dc98 | 28 |
| `_ZN16ReprocessRequestD0Ev.localalias.151` | 0x4dc98 | 28 |
| `_ZN5QListI14QSharedPointerI11FileContentEE7deallocEPN9QListData4DataE.isra.79` | 0x4dd90 | 88 |
| `_ZN8QMapNodeIj14QSharedPointerI11FileContentEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.89` | 0x4dde8 | 1632 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Cache18handleReprocessRawEvEUlP18PendingCallWatcherE_Li1ENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x4e900 | 1004 |
| `_ZN5QListI14QSharedPointerI9CacheItemEE7deallocEPN9QListData4DataE.isra.57` | 0x4fa3c | 88 |
| `_ZN5Cache18handleReprocessRawEv` | 0x4fd28 | 3540 |
| `_ZN5QListI8QVariantE9takeFirstEv` | 0x56368 | 312 |
| `_ZN15QtSharedPointer33ExternalRefCountWithCustomDeleterI16ReprocessRequestNS_13NormalDeleterEE7deleterEPNS_20ExternalRefCountDataE` | 0x566d0 | 72 |
| `_ZN14QSharedPointerI16ReprocessRequestE5derefEPN15QtSharedPointer20ExternalRefCountDataE` | 0x56d80 | 96 |
| `_ZN5QListI8QVariantE7deallocEPN9QListData4DataE.isra.33` | 0x68814 | 84 |
| `_ZN5QListI14QSharedPointerI12DussMemShareEE7deallocEPN9QListData4DataE.isra.36` | 0x7a5d4 | 176 |
| `_ZN5QListI14QSharedPointerI11ImageMemoryEE7deallocEPN9QListData4DataE.isra.30` | 0x7a684 | 176 |
| `_ZN5QListI4QMapI7QString8QVariantEE7deallocEPN9QListData4DataE.isra.42` | 0x7a7b0 | 144 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.34` | 0xd088c | 132 |

**New objects (43)**

| Symbol | Addr | Size |
|---|---|---|
| `CSWTCH.148` | 0xfc5e8 | 48 |
| `_ZZN9QtPrivate15ConnectionTypesINS_4ListIJRK7QStringy4QMapIS2_8QVariantEEEELb1EE5typesEvE1t` | 0xfcbe0 | 16 |
| `_ZTS16ControllableTaskIbE` | 0xfcc10 | 22 |
| `_ZTS16QFutureInterfaceIbE` | 0xfcc28 | 22 |
| `_ZTS19RunControllableTaskIbE` | 0xfcc40 | 25 |
| `_ZZZZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEENKUlRK7QStringy4QMapIS5_8QVariantEE0_clES7_ySA_ENKUlP18PendingCallWatcherE_clESD_E12__FUNCTION__` | 0xfcc60 | 11 |
| `_ZZN13ReprocessTask3runER11TaskControlE12__FUNCTION__` | 0xfcd00 | 4 |
| `_ZZZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEENKUlRK7QStringy4QMapIS5_8QVariantEE0_clES7_ySA_E12__FUNCTION__` | 0xfcd08 | 11 |
| `_ZZN13ReprocessTaskD4EvE12__FUNCTION__` | 0xfcd18 | 15 |
| `_ZZZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEENKUlRK7QStringN9HblmTypes14E_ReturnStatusES7_E1_clES7_S9_S7_E12__FUNCTION__` | 0xfcd88 | 11 |
| `_ZZZN5Cache21onRequestReprocessRawERK14QSharedPointerI11ImageMemoryEENKUlRK7QStringN9HblmTypes14E_ReturnStatusES7_E1_clES7_S9_S7_E19__PRETTY_FUNCTION__` | 0xfcd98 | 134 |
| `_ZTS16QFutureInterfaceIvE` | 0xfd208 | 22 |
| `_ZTSN12QtConcurrent19RunFunctionTaskBaseIvEE` | 0xfd2d8 | 41 |
| `_ZTSN12QtConcurrent15RunFunctionTaskIvEE` | 0xfd308 | 37 |
| `_ZTSN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_EE` | 0xfd330 | 93 |
| `._535` | 0xfdaf0 | 2 |
| `._534` | 0xfdb60 | 2 |
| `._432` | 0x1010e0 | 14 |
| `._433` | 0x1010f0 | 10 |
| `._438` | 0x101bd8 | 2 |
| `_ZL32qt_meta_stringdata_ReprocessTask` | 0x103578 | 276 |
| `_ZL26qt_meta_data_ReprocessTask` | 0x103ce8 | 156 |
| `_ZTS13ReprocessTask` | 0x103d88 | 16 |
| `_ZTI16ControllableTaskIbE` | 0x1086b0 | 8 |
| `_ZTI16QFutureInterfaceIbE` | 0x1086b8 | 12 |
| `_ZTI19RunControllableTaskIbE` | 0x1086c4 | 32 |
| `_ZTV16ControllableTaskIbE` | 0x1086f8 | 20 |
| `_ZTV16QFutureInterfaceIbE` | 0x108710 | 16 |
| `_ZTV19RunControllableTaskIbE` | 0x108720 | 40 |
| `_ZTI16QFutureInterfaceIvE` | 0x108798 | 12 |
| `_ZTIN12QtConcurrent19RunFunctionTaskBaseIvEE` | 0x1087d4 | 32 |
| `_ZTIN12QtConcurrent15RunFunctionTaskIvEE` | 0x1087f4 | 12 |
| `_ZTIN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_EE` | 0x108800 | 12 |
| `_ZTV16QFutureInterfaceIvE` | 0x108898 | 16 |
| `_ZTVN12QtConcurrent19RunFunctionTaskBaseIvEE` | 0x108948 | 44 |
| `_ZTVN12QtConcurrent15RunFunctionTaskIvEE` | 0x108978 | 44 |
| `_ZTVN12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_EE` | 0x1089a8 | 44 |
| `_ZTI13ReprocessTask` | 0x10a128 | 32 |
| `_ZTV13ReprocessTask` | 0x10a168 | 80 |
| `_ZN13ReprocessTask16staticMetaObjectE` | 0x10a218 | 24 |
| `_ZZN9QtPrivate15ConnectionTypesINS_4ListIJRK7QStringN9HblmTypes14E_ReturnStatusES4_EEELb1EE5typesEvE1t` | 0x10c070 | 16 |
| `_ZZN11QMetaTypeIdIN9HblmTypes14E_ReturnStatusEE14qt_metatype_idEvE11metatype_id` | 0x114f40 | 4 |
| `_ZGVZN9QtPrivate15ConnectionTypesINS_4ListIJRK7QStringN9HblmTypes14E_ReturnStatusES4_EEELb1EE5typesEvE1t` | 0x114f70 | 4 |

**Removed objects (14)**

| Symbol | Addr | Size |
|---|---|---|
| `CSWTCH.149` | 0xf87a0 | 48 |
| `_ZZN16ReprocessRequestD4EvE12__FUNCTION__` | 0xf8e48 | 18 |
| `_ZZZN5Cache18handleReprocessRawEvENKUlP18PendingCallWatcherE_clES1_E12__FUNCTION__` | 0xf8e78 | 11 |
| `_ZZZN5Cache18handleReprocessRawEvENKUlP18PendingCallWatcherE_clES1_E19__PRETTY_FUNCTION__` | 0xf8e88 | 59 |
| `_ZZN5Cache25cancelPendingReprocessRawEvE12__FUNCTION__` | 0xf8f58 | 26 |
| `_ZZN5Cache18handleReprocessRawEvE12__FUNCTION__` | 0xf8f78 | 19 |
| `_ZTS16ReprocessRequest` | 0xf90b0 | 19 |
| `._533` | 0xf9b60 | 2 |
| `._532` | 0xf9c38 | 2 |
| `._425` | 0xfd110 | 4 |
| `._426` | 0xfd118 | 4 |
| `._436` | 0xfdc48 | 2 |
| `_ZTI16ReprocessRequest` | 0x1048c0 | 12 |
| `_ZTV16ReprocessRequest` | 0x1048d0 | 56 |

### `/bin/camservice`

+26 / −20 functions · +4 / −3 objects

**New functions (26)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate8RefCount5derefEv.part.35` | 0x18800 | 32 |
| `_ZN7QStringD2Ev.part.36` | 0x18820 | 24 |
| `_ZNKSt3__121__basic_string_commonILb1EE20__throw_length_errorEv.isra.601` | 0x18ae8 | 96 |
| `_ZNKSt3__18functionIFvN5rxcpp10subscriberINS_10shared_ptrIN3dji6camera11FrameBufferEEENS1_8observerIS7_vvvvEEEEEEclESA_.isra.1005.part.1006` | 0x18b48 | 60 |
| `_ZN14CamserviceImpl20onDumpPreviewChangedEb` | 0x33c3c | 16 |
| `_ZL11frameFormatRNSt3__110shared_ptrIN3dji6camera11FrameBufferEEE.part.517` | 0x34cd8 | 272 |
| `_ZN9QtPrivate8RefCount5derefEv.part.549` | 0x34e50 | 32 |
| `_ZN7QStringD2Ev.part.550` | 0x34e70 | 24 |
| `_ZNKSt3__18functionIFvRKN5rxcpp10schedulers11schedulableEEEclES5_.isra.568` | 0x34e88 | 80 |
| `_ZN5QListINSt3__15tupleIJjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.665` | 0x34ed8 | 68 |
| `_ZN5QListINSt3__15tupleIJN9HblmTypes14E_VideoControlEjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.669` | 0x34f1c | 68 |
| `_ZN14CamserviceImpl9setStatusEN9HblmTypes21E_CameraServiceStatusE.part.482` | 0x35204 | 388 |
| `_ZN14CamserviceImpl13wbTintChangedEi.part.596` | 0x35758 | 768 |
| `_ZN14CamserviceImpl13wbTempChangedEi.part.595` | 0x35a94 | 772 |
| `_ZZN14CamserviceImpl20onPreviewFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.551` | 0x36ee8 | 764 |
| `_ZZN14CamserviceImpl17onFullFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.552` | 0x37230 | 780 |
| `_ZZN14CamserviceImpl17onJpegFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.553` | 0x37590 | 764 |
| `_ZN8QMapNodeIj5QPairIi10QByteArrayEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.756` | 0x378d8 | 2528 |
| `_ZN14CamserviceImpl19onSaveFolderChangedERK7QString` | 0x3a8fc | 208 |
| `_ZNK14CamserviceImpl12video_statusEv.localalias.1885` | 0x3b1d0 | 156 |
| `_ZN5QListI4QMapI7QString8QVariantEE7deallocEPN9QListData4DataE.isra.723` | 0x3e038 | 180 |
| `_ZNK5rxcpp10schedulers6worker8scheduleIRNS_6detail15safe_subscriberINS_9operators6detail13lift_operatorINSt3__110shared_ptrIN3dji6camera11FrameBufferEEENS_18dynamic_observableISD_EENS6_6filterISD_ZN14CamserviceImplC4EP7QObjectRNS_21observe_on_one_workerEOK7QStringEUlSD_E4_EEEENS_10subscriberISD_NS_8observerISD_NS3_22stateless_observer_tagEZNSH_C4ESJ_SL_SO_EUlSD_E5_vvEEEEEEJEEENS8_9enable_ifIXaaoosrNS0_6detail18is_action_functionIT_EE5valuesrNS_15is_subscriptionIS13_EE5valuentsrNS_14is_schedulableIS13_EE5valueEvE4typeEOS13_DpOT0_` | 0x46814 | 692 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlbE12_clEb.isra.1879` | 0x527dc | 3728 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEE6_clESD_.isra.1882` | 0x5367c | 364 |
| `_ZN9QtPrivate11QSlotObjectIM14CamserviceImplFvRK7QStringENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x54d68 | 156 |
| `_ZN7QObject7connectIM18PendingCallWatcherFvPS1_EM14CamserviceImplFvvEEEN11QMetaObject10ConnectionEPKN9QtPrivate15FunctionPointerIT_E6ObjectESC_PKNSB_IT0_E6ObjectESH_N2Qt14ConnectionTypeE` | 0x5a5fc | 560 |

**Removed functions (20)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNKSt3__121__basic_string_commonILb1EE20__throw_length_errorEv.isra.597` | 0x18a18 | 96 |
| `_ZNKSt3__18functionIFvN5rxcpp10subscriberINS_10shared_ptrIN3dji6camera11FrameBufferEEENS1_8observerIS7_vvvvEEEEEEclESA_.isra.1000.part.1001` | 0x18a78 | 60 |
| `_ZL11frameFormatRNSt3__110shared_ptrIN3dji6camera11FrameBufferEEE.part.514` | 0x34c80 | 272 |
| `_ZN9QtPrivate8RefCount5derefEv.part.545` | 0x34df8 | 32 |
| `_ZN7QStringD2Ev.part.546` | 0x34e18 | 24 |
| `_ZNKSt3__18functionIFvRKN5rxcpp10schedulers11schedulableEEEclES5_.isra.564` | 0x34e30 | 80 |
| `_ZN5QListINSt3__15tupleIJjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.661` | 0x34e80 | 68 |
| `_ZN5QListINSt3__15tupleIJN9HblmTypes14E_VideoControlEjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.665` | 0x34ec4 | 68 |
| `_ZN14CamserviceImpl9setStatusEN9HblmTypes21E_CameraServiceStatusE.part.479` | 0x351ac | 388 |
| `_ZN14CamserviceImpl13wbTintChangedEi.part.584` | 0x356c0 | 768 |
| `_ZN14CamserviceImpl13wbTempChangedEi.part.583` | 0x359fc | 772 |
| `_ZZN14CamserviceImpl20onPreviewFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.547` | 0x36e50 | 764 |
| `_ZZN14CamserviceImpl17onFullFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.548` | 0x37198 | 780 |
| `_ZZN14CamserviceImpl17onJpegFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.549` | 0x374f8 | 764 |
| `_ZN8QMapNodeIj5QPairIi10QByteArrayEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.752` | 0x37840 | 2528 |
| `_ZNK14CamserviceImpl12video_statusEv.localalias.1880` | 0x3b12c | 156 |
| `_ZN5QListI4QMapI7QString8QVariantEE7deallocEPN9QListData4DataE.isra.719` | 0x3df1c | 180 |
| `_ZNK5rxcpp10schedulers6worker8scheduleIRNS_6detail15safe_subscriberINS_9operators6detail13lift_operatorINSt3__110shared_ptrIN3dji6camera11FrameBufferEEENS_18dynamic_observableISD_EENS6_10observe_onISD_NS_21observe_on_one_workerEEEEENS_10subscriberISD_NS_8observerISD_NS3_22stateless_observer_tagEZN14CamserviceImplC4EP7QObjectRSH_OK7QStringEUlSD_E2_vvEEEEEEJEEENS8_9enable_ifIXaaoosrNS0_6detail18is_action_functionIT_EE5valuesrNS_15is_subscriptionIS12_EE5valuentsrNS_14is_schedulableIS12_EE5valueEvE4typeEOS12_DpOT0_` | 0x4644c | 692 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlbE12_clEb.isra.1874` | 0x526d8 | 3144 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEE6_clESD_.isra.1877` | 0x53330 | 360 |

**New objects (4)**

| Symbol | Addr | Size |
|---|---|---|
| `CSWTCH.148` | 0x81cd0 | 48 |
| `_ZZN9QtPrivate15ConnectionTypesINS_4ListIJRK7QStringEEELb1EE5typesEvE1t` | 0x827e8 | 8 |
| `CSWTCH.1480` | 0x8a4e0 | 16 |
| `CSWTCH.1482` | 0x8a918 | 40 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `CSWTCH.149` | 0x815d0 | 48 |
| `CSWTCH.1477` | 0x89dd8 | 16 |
| `CSWTCH.1479` | 0x8a210 | 32 |

### `/bin/phocus`

+27 / −0 functions · +10 / −0 objects

**New functions (27)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes11E_VideoModeELb1EE8DestructEPv` | 0x82c20 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes11E_VideoModeELb1EE9ConstructEPvPKv` | 0x82c24 | 20 |
| `_Z17qRegisterMetaTypeIN9HblmTypes11E_VideoModeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x82e20 | 312 |
| `_ZNSt3__18functionIFvRK7QStringEED1Ev` | 0xb2f34 | 100 |
| `_ZNSt3__18functionIFvRK7QStringEED2Ev` | 0xb2f34 | 100 |
| `_ZNSt3__18functionIFvvEED1Ev` | 0xb2f98 | 100 |
| `_ZNSt3__18functionIFvvEED2Ev` | 0xb2f98 | 100 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_SystemStateELb1EE8DestructEPv` | 0xc2bd0 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_SystemStateELb1EE9ConstructEPvPKv` | 0xc2bd4 | 20 |
| `_Z17qRegisterMetaTypeIN9HblmTypes13E_SystemStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0xc2be8 | 312 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_WhiteModesELb1EE8DestructEPv` | 0xd087c | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_WhiteModesELb1EE9ConstructEPvPKv` | 0xd0880 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes26E_FocusBracketingStepSizesELb1EE8DestructEPv` | 0xd08c4 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes26E_FocusBracketingStepSizesELb1EE9ConstructEPvPKv` | 0xd08c8 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes27E_FocusBracketingStrategiesELb1EE8DestructEPv` | 0xd0924 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes27E_FocusBracketingStrategiesELb1EE9ConstructEPvPKv` | 0xd0928 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_StorageDeviceELb1EE8DestructEPv` | 0xd093c | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_StorageDeviceELb1EE9ConstructEPvPKv` | 0xd0940 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_DriveModesELb1EE8DestructEPv` | 0xd099c | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_DriveModesELb1EE9ConstructEPvPKv` | 0xd09a0 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_ExitOptionELb1EE8DestructEPv` | 0xd09b4 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_ExitOptionELb1EE9ConstructEPvPKv` | 0xd09b8 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_StorageModeELb1EE8DestructEPv` | 0xd09cc | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_StorageModeELb1EE9ConstructEPvPKv` | 0xd09d0 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_DistanceUnitELb1EE8DestructEPv` | 0xd09e4 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_DistanceUnitELb1EE9ConstructEPvPKv` | 0xd09e8 | 20 |
| `_ZNK4QMapI7QString8QVariantEixERKS0_` | 0xda548 | 116 |

**New objects (10)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes11E_VideoModeEE14qt_metatype_idEvE11metatype_id` | 0x100054 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes13E_SystemStateEE14qt_metatype_idEvE11metatype_id` | 0x109194 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes14E_DistanceUnitEE14qt_metatype_idEvE11metatype_id` | 0x10a670 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_StorageDeviceEE14qt_metatype_idEvE11metatype_id` | 0x10a680 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes12E_ExitOptionEE14qt_metatype_idEvE11metatype_id` | 0x10a690 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes27E_FocusBracketingStrategiesEE14qt_metatype_idEvE11metatype_id` | 0x10a6a0 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes26E_FocusBracketingStepSizesEE14qt_metatype_idEvE11metatype_id` | 0x10a6b0 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes12E_DriveModesEE14qt_metatype_idEvE11metatype_id` | 0x10a6c0 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes13E_StorageModeEE14qt_metatype_idEvE11metatype_id` | 0x10a6e0 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes12E_WhiteModesEE14qt_metatype_idEvE11metatype_id` | 0x10a738 | 4 |

### `/etc/firmware/rtnodes/cfv-control.elf`

+26 / −1 functions · +157 / −153 objects

**New functions (26)**

| Symbol | Addr | Size |
|---|---|---|
| `CACHE_GetDistanceScale0` | 0x80063b1 | 12 |
| `CACHE_SetDistanceScale0` | 0x80063bd | 32 |
| `CACHE_GetDistanceScale1` | 0x80063dd | 12 |
| `CACHE_SetDistanceScale1` | 0x80063e9 | 32 |
| `CACHE_GetDistanceScale2` | 0x8006409 | 12 |
| `CACHE_SetDistanceScale2` | 0x8006415 | 32 |
| `CACHE_SetSysmanState` | 0x8006435 | 32 |
| `CACHE_GetSysmanState` | 0x8006455 | 12 |
| `CACHE_SetShutterCount` | 0x8006461 | 32 |
| `CACHE_GetShutterCount` | 0x8006481 | 12 |
| `isHC50_110` | 0x80096e5 | 60 |
| `isHCD35_90` | 0x8009721 | 56 |
| `needConverterWorkaround` | 0x8009759 | 52 |
| `getShutterCount` | 0x8009da1 | 78 |
| `getDistanceScale` | 0x800a4f1 | 214 |
| `LENS_GetProperties` | 0x800adfd | 28 |
| `LENS_ChangedUnitOfDistance` | 0x800c16d | 8 |
| `MSGHANDLER_lens_changed_distance_scale_0` | 0x800f1bd | 42 |
| `MSGHANDLER_lens_changed_distance_scale_1` | 0x800f1e9 | 42 |
| `MSGHANDLER_lens_changed_distance_scale_2` | 0x800f215 | 42 |
| `MSGHANDLER_lens_changed_shutter_count` | 0x800f59d | 42 |
| `MSGHANDLER_suc_changed_sys_state` | 0x800f871 | 44 |
| `PROP_ChangedSystemState` | 0x8011cc5 | 18 |
| `PWRSTATE_IsStatePowerUp` | 0x8022c45 | 20 |
| `pspwr_coldBootTimeoutCb` | 0x8023d69 | 28 |
| `PSPRW_PowerStateChanged` | 0x8024031 | 68 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `LENS_GetMinimumObjectDistance` | 0x800ab09 | 28 |

**New objects (157)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16120` | 0x8029b28 | 13 |
| `__func__.16177` | 0x8029b38 | 11 |
| `__func__.16084` | 0x8029b44 | 28 |
| `__func__.16132` | 0x8029b60 | 23 |
| `__func__.16281` | 0x8029b78 | 42 |
| `__func__.16045` | 0x8029ba4 | 33 |
| `__func__.16153` | 0x8029bfc | 16 |
| `__func__.16165` | 0x8029c0c | 10 |
| `__func__.16247` | 0x802ab7c | 15 |
| `__func__.16033` | 0x802ab8c | 15 |
| `__func__.16189` | 0x802ab9c | 19 |
| `__func__.14755` | 0x802ac7c | 32 |
| `__func__.14761` | 0x802ae30 | 29 |
| `__func__.14730` | 0x802ae50 | 41 |
| `__func__.14745` | 0x802ae7c | 21 |
| `__func__.14734` | 0x802ae94 | 17 |
| `__func__.14741` | 0x802aec0 | 22 |
| `__func__.14528` | 0x802aef0 | 21 |
| `__func__.14520` | 0x802b050 | 21 |
| `__func__.14516` | 0x802b068 | 41 |
| `__func__.14057` | 0x802c058 | 16 |
| `__func__.15744` | 0x802c500 | 25 |
| `__func__.15678` | 0x802c51c | 11 |
| `__func__.15698` | 0x802c528 | 23 |
| `__func__.15758` | 0x802c540 | 22 |
| `__func__.15707` | 0x802c558 | 21 |
| `__func__.15674` | 0x802c7f4 | 17 |
| `__func__.15787` | 0x802c808 | 26 |
| `__func__.15732` | 0x802c824 | 13 |
| `__func__.15715` | 0x802c834 | 22 |
| `__func__.15688` | 0x802c84c | 20 |
| `__FUNCTION__.15033` | 0x802c870 | 25 |
| `__func__.15516` | 0x802c88c | 15 |
| `__func__.15519` | 0x802c89c | 18 |
| `__func__.15303` | 0x802c8b0 | 34 |
| `__FUNCTION__.15027` | 0x802c8d4 | 20 |
| `__func__.15107` | 0x802c8e8 | 28 |
| `__func__.15297` | 0x802d1ac | 32 |
| `__func__.15593` | 0x802d1cc | 14 |
| `__func__.15259` | 0x802d1dc | 16 |
| `__FUNCTION__.15115` | 0x802d210 | 31 |
| `__func__.15168` | 0x802d230 | 22 |
| `__func__.15616` | 0x802d260 | 21 |
| `__func__.15451` | 0x802d288 | 17 |
| `__func__.15173` | 0x802d29c | 19 |
| `__func__.15467` | 0x802d2b0 | 29 |
| `__func__.15557` | 0x802d2d0 | 10 |
| `__func__.15321` | 0x802d2dc | 20 |
| `__func__.15309` | 0x802d2f0 | 25 |
| `__func__.15607` | 0x802d30c | 26 |

<details><summary>… 另 107 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15328` | 0x802d328 | 20 |
| `__func__.15640` | 0x802d33c | 19 |
| `__func__.15064` | 0x802d350 | 24 |
| `__FUNCTION__.17119` | 0x802d524 | 11 |
| `__FUNCTION__.15316` | 0x802d6e0 | 27 |
| `__FUNCTION__.15333` | 0x802d6fc | 27 |
| `__FUNCTION__.15337` | 0x802d7e8 | 10 |
| `__func__.14924` | 0x802d7f8 | 13 |
| `__func__.14930` | 0x802d808 | 16 |
| `__func__.14835` | 0x8031040 | 24 |
| `__func__.14904` | 0x80313f4 | 11 |
| `__func__.13784` | 0x8032608 | 26 |
| `__func__.13779` | 0x803271c | 17 |
| `__func__.13789` | 0x8032730 | 22 |
| `__FUNCTION__.12930` | 0x8032748 | 29 |
| `__FUNCTION__.12942` | 0x8032778 | 22 |
| `__FUNCTION__.12950` | 0x8032790 | 22 |
| `__FUNCTION__.12907` | 0x8032b18 | 27 |
| `__func__.15807` | 0x8032b34 | 21 |
| `__func__.15874` | 0x8032b4c | 21 |
| `__func__.15779` | 0x80332bc | 21 |
| `__func__.15740` | 0x8033514 | 24 |
| `__func__.15793` | 0x803352c | 17 |
| `__func__.15846` | 0x8033540 | 22 |
| `__FUNCTION__.14909` | 0x8033878 | 13 |
| `__func__.14931` | 0x8033888 | 25 |
| `__func__.14935` | 0x80338a4 | 25 |
| `__func__.11927` | 0x8033d24 | 12 |
| `__func__.11921` | 0x8033d30 | 11 |
| `__func__.11937` | 0x8033d3c | 19 |
| `__func__.11932` | 0x8033ec8 | 12 |
| `__func__.11913` | 0x8033ed4 | 19 |
| `__func__.13748` | 0x8034044 | 28 |
| `__func__.13754` | 0x8034060 | 29 |
| `__func__.13762` | 0x8034080 | 20 |
| `__func__.13758` | 0x8034094 | 18 |
| `__func__.13724` | 0x8034e74 | 19 |
| `__func__.13631` | 0x8034ea4 | 13 |
| `__FUNCTION__.13345` | 0x8035ca8 | 40 |
| `__FUNCTION__.13359` | 0x8035cd0 | 44 |
| `__func__.13697` | 0x8035d78 | 13 |
| `__func__.13706` | 0x8035d88 | 19 |
| `__FUNCTION__.13095` | 0x8035ee0 | 34 |
| `__FUNCTION__.13149` | 0x8035f04 | 31 |
| `__FUNCTION__.13165` | 0x8035f24 | 24 |
| `__FUNCTION__.13115` | 0x80360e0 | 28 |
| `__FUNCTION__.13179` | 0x80360fc | 27 |
| `__FUNCTION__.13124` | 0x8036118 | 16 |
| `__func__.14143` | 0x803695c | 12 |
| `__func__.14139` | 0x8036968 | 14 |
| `__func__.14147` | 0x8036978 | 18 |
| `__func__.14125` | 0x803698c | 11 |
| `__func__.14129` | 0x8037464 | 13 |
| `__func__.14134` | 0x8037474 | 15 |
| `__func__.7526` | 0x80379c4 | 19 |
| `__func__.13806` | 0x8038438 | 19 |
| `__func__.13880` | 0x803844c | 13 |
| `__func__.13840` | 0x8038950 | 10 |
| `__func__.13788` | 0x803895c | 18 |
| `__func__.13847` | 0x8038970 | 9 |
| `__func__.13388` | 0x8038d78 | 23 |
| `__func__.15292` | 0x80390dc | 27 |
| `__FUNCTION__.15139` | 0x80390f8 | 18 |
| `__FUNCTION__.13100` | 0x8039528 | 21 |
| `__FUNCTION__.15210` | 0x8039710 | 20 |
| `__FUNCTION__.15243` | 0x8039b40 | 23 |
| `__FUNCTION__.15250` | 0x8039b58 | 13 |
| `__FUNCTION__.15092` | 0x8039c38 | 30 |
| `__FUNCTION__.15105` | 0x8039c58 | 22 |
| `__FUNCTION__.15111` | 0x8039c70 | 28 |
| `__func__.14599` | 0x803a004 | 19 |
| `__func__.14514` | 0x803a2bc | 10 |
| `batteryStatus.16078` | 0x2000004e | 1 |
| `battery_probe_counter.16180` | 0x20000050 | 4 |
| `oldValue.15323` | 0x20000064 | 4 |
| `oldValue.15328` | 0x20000068 | 4 |
| `HW_version.14179` | 0x200002ac | 1 |
| `enterState.15238` | 0x200002f6 | 1 |
| `last_hvdcp.16044` | 0x20000656 | 1 |
| `inputBefore.14719` | 0x20000658 | 4 |
| `triggerBefore.14718` | 0x2000065c | 1 |
| `eldBtnSavedConf.14717` | 0x20000660 | 16 |
| `mDistanceScale2` | 0x20000670 | 4 |
| `mSysmanState` | 0x200006a5 | 1 |
| `mShutterCount` | 0x200006a8 | 4 |
| `mDistanceScale0` | 0x200006cc | 4 |
| `mDistanceScale1` | 0x200006d0 | 4 |
| `msg_index.12493` | 0x20000748 | 4 |
| `ticks.13567` | 0x20000750 | 4 |
| `mAvAdjustedForConverter` | 0x20000b24 | 1 |
| `saved_lens.15629` | 0x20000b38 | 1 |
| `is_fake.15630` | 0x20000bd0 | 1 |
| `lastGpioValue.15315` | 0x20000c10 | 4 |
| `last_signal.18146` | 0x20000c22 | 1 |
| `sig.12545` | 0x20002590 | 270 |
| `mutex.14187` | 0x2000292c | 4 |
| `str.14085` | 0x20002930 | 10 |
| `writebuffer.12531` | 0x20003250 | 5 |
| `initialized.13879` | 0x20003262 | 1 |
| `txPoolInitialized.13276` | 0x20003290 | 1 |
| `timerInitialized.13300` | 0x200032a8 | 1 |
| `rxDmaInitialized.13292` | 0x20004341 | 1 |
| `wakeUpSpecialEn.15239` | 0x20004350 | 1 |
| `earlyStartInProgress.15207` | 0x20004385 | 1 |
| `loopTestTaskHandle.14607` | 0x200043c0 | 4 |
| `switch_req_origin.14512` | 0x200043c5 | 1 |
| `pspwr_coldBootTimer` | 0x200043c8 | 4 |

</details>

**Removed objects (153)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15972` | 0x80294a8 | 10 |
| `__func__.16088` | 0x80294b4 | 42 |
| `__func__.15960` | 0x80294e0 | 16 |
| `__func__.15927` | 0x80294f0 | 13 |
| `__func__.15891` | 0x8029500 | 28 |
| `__func__.15939` | 0x8029550 | 23 |
| `__func__.15996` | 0x802a4cc | 19 |
| `__func__.16054` | 0x802a4e0 | 15 |
| `__func__.15840` | 0x802a4f0 | 15 |
| `__func__.15984` | 0x802a500 | 11 |
| `__func__.15852` | 0x802a5c0 | 33 |
| `__func__.14541` | 0x802a5fc | 17 |
| `__func__.14537` | 0x802a610 | 41 |
| `__func__.14544` | 0x802a63c | 21 |
| `__func__.14552` | 0x802a654 | 21 |
| `__func__.14548` | 0x802a66c | 22 |
| `__func__.14562` | 0x802a818 | 32 |
| `__func__.14568` | 0x802a838 | 29 |
| `__func__.14325` | 0x802a870 | 41 |
| `__func__.14329` | 0x802a9e4 | 21 |
| `__func__.14337` | 0x802a9fc | 21 |
| `__func__.13866` | 0x802b4d0 | 16 |
| `__func__.15522` | 0x802be80 | 22 |
| `__func__.15594` | 0x802be98 | 26 |
| `__func__.15481` | 0x802beb4 | 17 |
| `__func__.15485` | 0x802bec8 | 11 |
| `__func__.15551` | 0x802bed4 | 25 |
| `__func__.15539` | 0x802c174 | 13 |
| `__func__.15565` | 0x802c184 | 22 |
| `__func__.15505` | 0x802c19c | 23 |
| `__func__.15495` | 0x802c1b4 | 20 |
| `__func__.15514` | 0x802c1c8 | 21 |
| `__func__.15212` | 0x802c1f0 | 17 |
| `__func__.15083` | 0x802c204 | 34 |
| `__func__.15089` | 0x802c228 | 25 |
| `__func__.14891` | 0x802c244 | 28 |
| `__func__.15101` | 0x802c260 | 20 |
| `__func__.15401` | 0x802c274 | 19 |
| `__func__.15108` | 0x802c288 | 20 |
| `__func__.15277` | 0x802c29c | 15 |
| `__func__.14952` | 0x802c2ac | 22 |
| `__func__.15280` | 0x802c2c4 | 18 |
| `__func__.14957` | 0x802c2d8 | 30 |
| `__func__.15318` | 0x802c2f8 | 10 |
| `__FUNCTION__.14899` | 0x802c304 | 31 |
| `__func__.15039` | 0x802c324 | 16 |
| `__func__.15008` | 0x802c334 | 16 |
| `__func__.15360` | 0x802c344 | 22 |
| `__func__.15354` | 0x802c35c | 14 |
| `__func__.14848` | 0x802c36c | 24 |

<details><summary>… 另 103 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15077` | 0x802c384 | 32 |
| `__FUNCTION__.14811` | 0x802c3a4 | 20 |
| `__func__.15368` | 0x802c3d8 | 26 |
| `__func__.15377` | 0x802c3f4 | 21 |
| `__FUNCTION__.14895` | 0x802c40c | 35 |
| `__FUNCTION__.14817` | 0x802c430 | 25 |
| `__FUNCTION__.16924` | 0x802ccf4 | 11 |
| `__FUNCTION__.15142` | 0x802d06c | 27 |
| `__FUNCTION__.15146` | 0x802d088 | 10 |
| `__FUNCTION__.15125` | 0x802d164 | 27 |
| `__func__.14642` | 0x802d184 | 24 |
| `__func__.14731` | 0x802d19c | 13 |
| `__func__.14711` | 0x802d1ac | 11 |
| `__func__.13585` | 0x8031dd0 | 26 |
| `__func__.13590` | 0x8031dec | 22 |
| `__func__.13563` | 0x803208c | 31 |
| `__func__.13580` | 0x80320ac | 17 |
| `__FUNCTION__.12756` | 0x80320c0 | 29 |
| `__FUNCTION__.12768` | 0x80320f0 | 22 |
| `__FUNCTION__.12776` | 0x8032108 | 22 |
| `__FUNCTION__.12733` | 0x8032490 | 27 |
| `__func__.15585` | 0x80326ec | 21 |
| `__func__.15546` | 0x8032718 | 24 |
| `__func__.15613` | 0x8032e88 | 21 |
| `__func__.15680` | 0x8032ea0 | 21 |
| `__func__.15652` | 0x8032eb8 | 22 |
| `__func__.14739` | 0x80331f0 | 25 |
| `__func__.14743` | 0x803320c | 25 |
| `__FUNCTION__.14717` | 0x8033228 | 13 |
| `__func__.11761` | 0x803369c | 12 |
| `__func__.11756` | 0x80336a8 | 12 |
| `__func__.11766` | 0x80336b4 | 19 |
| `__func__.11742` | 0x8033840 | 19 |
| `__func__.11750` | 0x8033854 | 11 |
| `__func__.13591` | 0x80339bc | 20 |
| `__func__.13587` | 0x80339d0 | 18 |
| `__func__.13553` | 0x80339fc | 19 |
| `__func__.13444` | 0x8033a10 | 27 |
| `__func__.13460` | 0x80347e0 | 13 |
| `__func__.13577` | 0x80347f0 | 28 |
| `__func__.13583` | 0x803480c | 29 |
| `__FUNCTION__.13174` | 0x8034848 | 40 |
| `__FUNCTION__.13188` | 0x8035648 | 44 |
| `__func__.13526` | 0x80356f0 | 13 |
| `__func__.13535` | 0x8035700 | 19 |
| `__FUNCTION__.12978` | 0x8035858 | 31 |
| `__FUNCTION__.12924` | 0x8035878 | 34 |
| `__FUNCTION__.12994` | 0x803589c | 24 |
| `__FUNCTION__.12944` | 0x80358b4 | 28 |
| `__FUNCTION__.12953` | 0x8035a74 | 16 |
| `__FUNCTION__.13008` | 0x8035a84 | 27 |
| `__func__.13968` | 0x80362d4 | 14 |
| `__func__.13972` | 0x80362e4 | 12 |
| `__func__.13976` | 0x80362f0 | 18 |
| `__func__.13963` | 0x8036304 | 15 |
| `__func__.13958` | 0x8036c60 | 13 |
| `__func__.13954` | 0x8036c70 | 11 |
| `__func__.7495` | 0x80372a4 | 19 |
| `__func__.13597` | 0x8037d9c | 18 |
| `__func__.13649` | 0x8037db0 | 10 |
| `__func__.13656` | 0x8037dbc | 9 |
| `__func__.13689` | 0x80382e4 | 13 |
| `__func__.13217` | 0x80386f0 | 23 |
| `__func__.15087` | 0x80387a8 | 27 |
| `__FUNCTION__.14945` | 0x8038e60 | 18 |
| `__FUNCTION__.12929` | 0x8038e80 | 21 |
| `__FUNCTION__.15049` | 0x8039068 | 23 |
| `__FUNCTION__.15056` | 0x8039080 | 13 |
| `__FUNCTION__.15016` | 0x8039498 | 20 |
| `__FUNCTION__.14913` | 0x803957c | 22 |
| `__FUNCTION__.14919` | 0x8039594 | 28 |
| `__FUNCTION__.14900` | 0x8039928 | 30 |
| `__func__.14408` | 0x8039948 | 19 |
| `__func__.14335` | 0x8039b94 | 10 |
| `batteryStatus.15885` | 0x20000014 | 1 |
| `battery_probe_counter.15987` | 0x20000020 | 4 |
| `oldValue.15137` | 0x20000070 | 4 |
| `oldValue.15132` | 0x20000074 | 4 |
| `HW_version.14008` | 0x200002b8 | 1 |
| `enterState.15033` | 0x20000308 | 1 |
| `last_hvdcp.15851` | 0x20000650 | 1 |
| `eldBtnSavedConf.14524` | 0x2000066c | 16 |
| `inputBefore.14526` | 0x20000680 | 4 |
| `triggerBefore.14525` | 0x20000684 | 1 |
| `msg_index.12322` | 0x20000744 | 4 |
| `ticks.13396` | 0x2000074c | 4 |
| `saved_lens.15390` | 0x20000bc1 | 1 |
| `is_fake.15391` | 0x20000bc9 | 1 |
| `lastGpioValue.15124` | 0x20000be8 | 4 |
| `last_signal.17932` | 0x20000c1e | 1 |
| `sig.12374` | 0x20002588 | 270 |
| `mutex.14016` | 0x20002924 | 4 |
| `str.13914` | 0x20002928 | 10 |
| `writebuffer.12360` | 0x20003248 | 5 |
| `initialized.13688` | 0x20003260 | 1 |
| `txPoolInitialized.13105` | 0x2000328c | 1 |
| `timerInitialized.13129` | 0x2000328d | 1 |
| `rxDmaInitialized.13121` | 0x20004339 | 1 |
| `wakeUpSpecialEn.15034` | 0x2000434e | 1 |
| `earlyStartInProgress.15013` | 0x2000437d | 1 |
| `loopTestTaskHandle.14416` | 0x200043ac | 4 |
| `switch_req_origin.14333` | 0x200043bb | 1 |
| `mLensStatus` | 0x200044fc | 3 |

</details>

### `/etc/firmware/rtnodes/xsystem-control.elf`

+26 / −1 functions · +139 / −132 objects

**New functions (26)**

| Symbol | Addr | Size |
|---|---|---|
| `CACHE_GetDistanceScale0` | 0x80053c9 | 12 |
| `CACHE_SetDistanceScale0` | 0x80053d5 | 32 |
| `CACHE_GetDistanceScale1` | 0x80053f5 | 12 |
| `CACHE_SetDistanceScale1` | 0x8005401 | 32 |
| `CACHE_GetDistanceScale2` | 0x8005421 | 12 |
| `CACHE_SetDistanceScale2` | 0x800542d | 32 |
| `CACHE_SetSysmanState` | 0x800544d | 32 |
| `CACHE_GetSysmanState` | 0x800546d | 12 |
| `CACHE_SetShutterCount` | 0x8005479 | 32 |
| `CACHE_GetShutterCount` | 0x8005499 | 12 |
| `isHC50_110` | 0x8007da9 | 60 |
| `isHCD35_90` | 0x8007de5 | 56 |
| `needConverterWorkaround` | 0x8007e1d | 52 |
| `getShutterCount` | 0x8008465 | 78 |
| `getDistanceScale` | 0x8008bb5 | 214 |
| `LENS_GetProperties` | 0x80094d1 | 28 |
| `LENS_ChangedUnitOfDistance` | 0x800a855 | 8 |
| `MSGHANDLER_lens_changed_distance_scale_0` | 0x800d5c9 | 42 |
| `MSGHANDLER_lens_changed_distance_scale_1` | 0x800d5f5 | 42 |
| `MSGHANDLER_lens_changed_distance_scale_2` | 0x800d621 | 42 |
| `MSGHANDLER_lens_changed_shutter_count` | 0x800d9a9 | 42 |
| `MSGHANDLER_suc_changed_sys_state` | 0x800dc8d | 44 |
| `PROP_ChangedSystemState` | 0x800fe45 | 18 |
| `PWRSTATE_IsStatePowerUp` | 0x801f7c1 | 20 |
| `pspwr_coldBootTimeoutCb` | 0x80207d5 | 28 |
| `PSPRW_PowerStateChanged` | 0x8020a9d | 68 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `LENS_GetMinimumObjectDistance` | 0x80091dd | 28 |

**New objects (139)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16262` | 0x80257dc | 22 |
| `__func__.16126` | 0x80257f4 | 23 |
| `__func__.16114` | 0x802580c | 13 |
| `__func__.16159` | 0x8025850 | 10 |
| `__func__.16032` | 0x802585c | 33 |
| `__func__.16020` | 0x8025880 | 15 |
| `__func__.16171` | 0x802688c | 11 |
| `__func__.16272` | 0x8026898 | 42 |
| `__func__.16183` | 0x80268c4 | 19 |
| `__func__.16147` | 0x80268d8 | 16 |
| `__func__.16241` | 0x80268e8 | 15 |
| `__func__.16071` | 0x80269ac | 28 |
| `__func__.14057` | 0x80275a8 | 16 |
| `__func__.15694` | 0x80278ac | 23 |
| `__func__.15703` | 0x80278c4 | 21 |
| `__func__.15754` | 0x80278dc | 22 |
| `__func__.15711` | 0x80278f4 | 22 |
| `__func__.15670` | 0x8027a28 | 17 |
| `__func__.15674` | 0x8027ba4 | 11 |
| `__func__.15777` | 0x8027bb0 | 26 |
| `__func__.15728` | 0x8027bcc | 13 |
| `__func__.15684` | 0x8027bdc | 20 |
| `__func__.15740` | 0x8027bf0 | 25 |
| `__func__.15648` | 0x8027c1c | 19 |
| `__func__.15369` | 0x8027c30 | 21 |
| `__FUNCTION__.15035` | 0x8027c48 | 20 |
| `__func__.15565` | 0x8027c5c | 10 |
| `__func__.15311` | 0x8027c78 | 34 |
| `__func__.15624` | 0x8027c9c | 21 |
| `__func__.15267` | 0x8027cb4 | 16 |
| `__func__.15181` | 0x8027cc4 | 19 |
| `__FUNCTION__.15119` | 0x8027cd8 | 35 |
| `__func__.15317` | 0x8027cfc | 25 |
| `__FUNCTION__.15123` | 0x8027d18 | 31 |
| `__func__.15615` | 0x8027d38 | 26 |
| `__func__.15336` | 0x8027d54 | 20 |
| `__func__.15072` | 0x8027d68 | 24 |
| `__FUNCTION__.15041` | 0x8027d80 | 25 |
| `__func__.15524` | 0x8027d9c | 15 |
| `__func__.15527` | 0x8027dac | 18 |
| `__func__.15115` | 0x8027dc0 | 28 |
| `__func__.15305` | 0x8027ddc | 32 |
| `__func__.15176` | 0x8027dfc | 22 |
| `__func__.15459` | 0x8027e14 | 17 |
| `__func__.15475` | 0x8027e28 | 29 |
| `__func__.15607` | 0x8027e48 | 22 |
| `__func__.15601` | 0x8027e60 | 14 |
| `__func__.15329` | 0x8027e70 | 20 |
| `__FUNCTION__.17295` | 0x80288dc | 11 |
| `__FUNCTION__.15302` | 0x8028a68 | 27 |

<details><summary>… 另 89 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.15309` | 0x8028a84 | 10 |
| `__func__.14640` | 0x8028afc | 16 |
| `__func__.14634` | 0x8028b0c | 13 |
| `__func__.14614` | 0x802c344 | 11 |
| `__func__.13735` | 0x802d874 | 26 |
| `__func__.13740` | 0x802d890 | 22 |
| `__func__.13713` | 0x802d9a0 | 31 |
| `__func__.13730` | 0x802d9c0 | 17 |
| `__FUNCTION__.12930` | 0x802d9d4 | 29 |
| `__FUNCTION__.12942` | 0x802da04 | 22 |
| `__FUNCTION__.12950` | 0x802da1c | 22 |
| `__FUNCTION__.12907` | 0x802dda4 | 27 |
| `__func__.15947` | 0x802df2c | 21 |
| `__func__.13754` | 0x802e610 | 18 |
| `__func__.13758` | 0x802e624 | 20 |
| `__func__.13720` | 0x802e66c | 19 |
| `__func__.13750` | 0x802f434 | 29 |
| `__func__.13627` | 0x802f454 | 13 |
| `__func__.13744` | 0x802f464 | 28 |
| `__FUNCTION__.13345` | 0x8030274 | 40 |
| `__FUNCTION__.13359` | 0x803029c | 44 |
| `__func__.13702` | 0x8030334 | 19 |
| `__func__.13693` | 0x803047c | 13 |
| `__FUNCTION__.13145` | 0x803049c | 31 |
| `__FUNCTION__.13161` | 0x80304bc | 24 |
| `__FUNCTION__.13111` | 0x80304d4 | 28 |
| `__FUNCTION__.13120` | 0x8030694 | 16 |
| `__FUNCTION__.13175` | 0x80306a4 | 27 |
| `__func__.14086` | 0x8031104 | 13 |
| `__func__.14100` | 0x8031114 | 12 |
| `__func__.14104` | 0x8031120 | 18 |
| `__func__.14082` | 0x8031acc | 11 |
| `__func__.13802` | 0x8032990 | 19 |
| `__func__.13876` | 0x80329a4 | 13 |
| `__func__.13784` | 0x8032ea8 | 18 |
| `__func__.13836` | 0x8032ed0 | 10 |
| `__func__.13843` | 0x8032edc | 9 |
| `__func__.13384` | 0x8033e9c | 23 |
| `__FUNCTION__.15099` | 0x8034234 | 18 |
| `__FUNCTION__.13096` | 0x8034664 | 21 |
| `__FUNCTION__.15148` | 0x803484c | 23 |
| `__FUNCTION__.15155` | 0x8034864 | 13 |
| `__FUNCTION__.15115` | 0x8034cd0 | 20 |
| `__FUNCTION__.15050` | 0x8034db4 | 30 |
| `__FUNCTION__.15063` | 0x80350ac | 22 |
| `__FUNCTION__.15069` | 0x80350c4 | 28 |
| `__func__.14585` | 0x80350e0 | 19 |
| `__func__.14500` | 0x8035398 | 10 |
| `battery_probe_counter.16174` | 0x2000002c | 4 |
| `batteryStatus.16065` | 0x2000004d | 1 |
| `HW_version.14135` | 0x200000c8 | 1 |
| `lastRxData.14246` | 0x200002bc | 4 |
| `checksum.14384` | 0x200002c0 | 2 |
| `flashpower.14386` | 0x2000036d | 1 |
| `enterState.15234` | 0x200003ee | 1 |
| `last_hvdcp.16031` | 0x20000731 | 1 |
| `mDistanceScale2` | 0x20000748 | 4 |
| `mSysmanState` | 0x2000077d | 1 |
| `mShutterCount` | 0x20000780 | 4 |
| `mDistanceScale0` | 0x200007a4 | 4 |
| `mDistanceScale1` | 0x200007a8 | 4 |
| `ticks.13812` | 0x20000824 | 4 |
| `mAvAdjustedForConverter` | 0x20000be2 | 1 |
| `is_fake.15638` | 0x20000c00 | 1 |
| `saved_lens.15637` | 0x20000c9d | 1 |
| `lastGpioValue.15301` | 0x20000cb8 | 4 |
| `sig.12545` | 0x20002640 | 270 |
| `mutex.14143` | 0x200029e4 | 4 |
| `str.14042` | 0x200029e8 | 10 |
| `writebuffer.12531` | 0x20003304 | 5 |
| `initialized.13875` | 0x20003316 | 1 |
| `longAckDelay.14244` | 0x20003327 | 1 |
| `generateRxAck.14242` | 0x2000332a | 1 |
| `TxAckTimeoutCnt.14245` | 0x2000332c | 4 |
| `generateRxAckDelay.14243` | 0x20003330 | 1 |
| `checksum.14239` | 0x20003334 | 4 |
| `lastMode.14387` | 0x20003348 | 1 |
| `datacnt.14238` | 0x20003349 | 1 |
| `generateTxAck.14240` | 0x2000334b | 1 |
| `generateTxAckDelay.14241` | 0x2000334e | 1 |
| `flashstatus.14385` | 0x20003358 | 1 |
| `timerInitialized.13296` | 0x2000339c | 1 |
| `rxDmaInitialized.13288` | 0x20004435 | 1 |
| `txPoolInitialized.13272` | 0x20004436 | 1 |
| `wakeUpSpecialEn.15235` | 0x20004461 | 1 |
| `earlyStartInProgress.15112` | 0x20004494 | 1 |
| `loopTestTaskHandle.14593` | 0x200044c4 | 4 |
| `switch_req_origin.14498` | 0x200044d2 | 1 |
| `pspwr_coldBootTimer` | 0x200044d4 | 4 |

</details>

**Removed objects (132)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16069` | 0x8025164 | 22 |
| `__func__.15921` | 0x802517c | 13 |
| `__func__.15878` | 0x802518c | 28 |
| `__func__.16079` | 0x80251a8 | 42 |
| `__func__.15933` | 0x8025208 | 23 |
| `__func__.15954` | 0x8025220 | 16 |
| `__func__.15839` | 0x8025230 | 33 |
| `__func__.16048` | 0x8025254 | 15 |
| `__func__.15966` | 0x8026260 | 10 |
| `__func__.15827` | 0x802626c | 15 |
| `__func__.15978` | 0x802627c | 11 |
| `__func__.13866` | 0x8026a78 | 16 |
| `__func__.15518` | 0x8027234 | 22 |
| `__func__.15481` | 0x802724c | 11 |
| `__func__.15477` | 0x8027258 | 17 |
| `__func__.15535` | 0x802726c | 13 |
| `__func__.15491` | 0x802727c | 20 |
| `__func__.15547` | 0x8027290 | 25 |
| `__func__.15561` | 0x80273c8 | 22 |
| `__func__.15584` | 0x8027548 | 26 |
| `__func__.15501` | 0x8027564 | 23 |
| `__func__.15510` | 0x802757c | 21 |
| `__func__.14856` | 0x80275a4 | 24 |
| `__func__.15085` | 0x80275bc | 32 |
| `__func__.15385` | 0x80275dc | 21 |
| `__func__.14899` | 0x8027614 | 28 |
| `__func__.15368` | 0x8027630 | 22 |
| `__func__.15109` | 0x8027648 | 20 |
| `__func__.15409` | 0x802765c | 19 |
| `__func__.15149` | 0x8027670 | 21 |
| `__FUNCTION__.14903` | 0x8027688 | 35 |
| `__FUNCTION__.14907` | 0x80276ac | 31 |
| `__func__.15016` | 0x80276cc | 16 |
| `__func__.15220` | 0x80276dc | 17 |
| `__func__.15091` | 0x80276f0 | 34 |
| `__func__.15097` | 0x8027714 | 25 |
| `__FUNCTION__.14819` | 0x8027730 | 20 |
| `__func__.15376` | 0x8027744 | 26 |
| `__func__.15116` | 0x8027760 | 20 |
| `__func__.15285` | 0x8027774 | 15 |
| `__func__.14960` | 0x8027798 | 22 |
| `__func__.14965` | 0x80277b0 | 30 |
| `__FUNCTION__.14825` | 0x80277d0 | 25 |
| `__func__.15326` | 0x80277ec | 10 |
| `__func__.15047` | 0x80277f8 | 16 |
| `__func__.15362` | 0x80280b8 | 14 |
| `__FUNCTION__.17100` | 0x80280c8 | 11 |
| `__FUNCTION__.15111` | 0x80283fc | 27 |
| `__FUNCTION__.15118` | 0x8028480 | 10 |
| `__func__.14467` | 0x8028490 | 16 |

<details><summary>… 另 82 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.14441` | 0x80284a0 | 11 |
| `__func__.14461` | 0x802c010 | 13 |
| `__func__.13536` | 0x802d208 | 26 |
| `__func__.13541` | 0x802d224 | 22 |
| `__func__.13514` | 0x802d334 | 31 |
| `__FUNCTION__.12756` | 0x802d354 | 29 |
| `__FUNCTION__.12768` | 0x802d384 | 22 |
| `__FUNCTION__.12776` | 0x802d39c | 22 |
| `__FUNCTION__.12733` | 0x802d724 | 27 |
| `__func__.15753` | 0x802d740 | 21 |
| `__func__.15796` | 0x802d8ac | 21 |
| `__func__.13587` | 0x802dfa8 | 20 |
| `__func__.13579` | 0x802dfbc | 29 |
| `__func__.13440` | 0x802dfdc | 27 |
| `__func__.13549` | 0x802dff8 | 19 |
| `__func__.13456` | 0x802edc0 | 13 |
| `__func__.13573` | 0x802edd0 | 28 |
| `__func__.13583` | 0x802edec | 18 |
| `__FUNCTION__.13174` | 0x802ee1c | 40 |
| `__FUNCTION__.13188` | 0x802fc1c | 44 |
| `__func__.13531` | 0x802fcb4 | 19 |
| `__func__.13522` | 0x802fdfc | 13 |
| `__FUNCTION__.12990` | 0x802fe1c | 24 |
| `__FUNCTION__.12940` | 0x802fe34 | 28 |
| `__FUNCTION__.13004` | 0x802fff4 | 27 |
| `__FUNCTION__.12949` | 0x8030010 | 16 |
| `__FUNCTION__.12974` | 0x8030020 | 31 |
| `__func__.13915` | 0x8030a84 | 13 |
| `__func__.13929` | 0x8030a94 | 12 |
| `__func__.13911` | 0x8030aa0 | 11 |
| `__func__.13933` | 0x8030aac | 18 |
| `__func__.13685` | 0x8032310 | 13 |
| `__func__.13593` | 0x8032320 | 18 |
| `__func__.13645` | 0x8032334 | 10 |
| `__func__.13652` | 0x8032354 | 9 |
| `__func__.13213` | 0x803381c | 23 |
| `__func__.15083` | 0x8033b78 | 27 |
| `__FUNCTION__.14905` | 0x8033fa4 | 18 |
| `__FUNCTION__.12925` | 0x8033fc4 | 21 |
| `__FUNCTION__.14921` | 0x80341ac | 20 |
| `__FUNCTION__.14954` | 0x8034608 | 23 |
| `__FUNCTION__.14961` | 0x8034620 | 13 |
| `__FUNCTION__.14878` | 0x8034700 | 30 |
| `__FUNCTION__.14891` | 0x8034720 | 22 |
| `__FUNCTION__.14897` | 0x8034a10 | 28 |
| `__func__.14321` | 0x8034a2c | 10 |
| `__func__.14394` | 0x8034c70 | 19 |
| `battery_probe_counter.15981` | 0x2000002c | 4 |
| `batteryStatus.15872` | 0x20000050 | 1 |
| `HW_version.13964` | 0x200002a0 | 1 |
| `flashpower.14195` | 0x200002ea | 1 |
| `lastRxData.14055` | 0x20000314 | 4 |
| `checksum.14193` | 0x20000376 | 2 |
| `enterState.15029` | 0x200003e0 | 1 |
| `last_hvdcp.15838` | 0x20000730 | 1 |
| `ticks.13641` | 0x200007fc | 4 |
| `is_fake.15399` | 0x20000ba0 | 1 |
| `saved_lens.15398` | 0x20000ba1 | 1 |
| `lastGpioValue.15110` | 0x20000c7c | 4 |
| `sig.12374` | 0x20002614 | 270 |
| `mutex.13972` | 0x200029b8 | 4 |
| `str.13871` | 0x200029bc | 10 |
| `writebuffer.12360` | 0x200032d8 | 5 |
| `initialized.13684` | 0x200032ea | 1 |
| `generateRxAck.14051` | 0x200032f6 | 1 |
| `TxAckTimeoutCnt.14054` | 0x200032fc | 4 |
| `generateRxAckDelay.14052` | 0x20003301 | 1 |
| `longAckDelay.14053` | 0x20003302 | 1 |
| `checksum.14048` | 0x20003308 | 4 |
| `lastMode.14196` | 0x20003311 | 1 |
| `datacnt.14047` | 0x20003312 | 1 |
| `generateTxAck.14049` | 0x20003313 | 1 |
| `generateTxAckDelay.14050` | 0x20003318 | 1 |
| `flashstatus.14194` | 0x20003321 | 1 |
| `txPoolInitialized.13101` | 0x20003333 | 1 |
| `timerInitialized.13125` | 0x20003370 | 1 |
| `rxDmaInitialized.13117` | 0x20004409 | 1 |
| `wakeUpSpecialEn.15030` | 0x20004428 | 1 |
| `earlyStartInProgress.14918` | 0x20004461 | 1 |
| `switch_req_origin.14319` | 0x2000449a | 1 |
| `loopTestTaskHandle.14402` | 0x2000449c | 4 |
| `mLensStatus` | 0x200045c8 | 3 |

</details>

### `/bin/camera`

+20 / −1 functions · +4 / −0 objects

**New functions (20)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN5QListI4QMapI7QString8QVariantEEC1ERKS4_` | 0x1abec | 460 |
| `_ZN5QListI4QMapI7QString8QVariantEEC2ERKS4_` | 0x1abec | 460 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_StreamTypeELb1EE8DestructEPv` | 0x72428 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_StreamTypeELb1EE9ConstructEPvPKv` | 0x7242c | 20 |
| `_Z17qRegisterMetaTypeIN9HblmTypes12E_StreamTypeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x729bc | 312 |
| `_ZN9QtPrivate16ConverterFunctorI5QListI4QMapI7QString8QVariantEEN17QtMetaTypePrivate23QSequentialIterableImplENS7_33QSequentialIterableConvertFunctorIS6_EEE7convertEPKNS_25AbstractConverterFunctionEPKvPv` | 0x7fd60 | 200 |
| `_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE5equalEPKPvSB_` | 0x7fe28 | 32 |
| `_ZN17QtMetaTypePrivate23QSequentialIterableImpl8sizeImplI5QListI4QMapI7QString8QVariantEEEEiPKv` | 0x7fe48 | 20 |
| `_ZN17QtMetaTypePrivate23QSequentialIterableImpl7getImplI5QListI4QMapI7QString8QVariantEEEENS_11VariantDataEPKPvij` | 0x7fe5c | 24 |
| `_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE7advanceEPPvi` | 0x7fe74 | 20 |
| `_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE6assignEPPvPKS9_` | 0x7fe88 | 40 |
| `_ZN17QtMetaTypePrivate23QSequentialIterableImpl13moveToEndImplI5QListI4QMapI7QString8QVariantEEEEvPKvPPv` | 0x7feb0 | 44 |
| `_ZN17QtMetaTypePrivate23QSequentialIterableImpl15moveToBeginImplI5QListI4QMapI7QString8QVariantEEEEvPKvPPv` | 0x7fedc | 44 |
| `_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE7destroyEPPv` | 0x7ff08 | 8 |
| `_ZN17QtMetaTypePrivate23QSequentialIterableImpl6atImplI5QListI4QMapI7QString8QVariantEEEEPKvS9_i` | 0x7ff10 | 24 |
| `_ZN9QtPrivate16ConverterFunctorI5QListI4QMapI7QString8QVariantEEN17QtMetaTypePrivate23QSequentialIterableImplENS7_33QSequentialIterableConvertFunctorIS6_EEED1Ev` | 0x7ff28 | 1012 |
| `_ZN9QtPrivate16ConverterFunctorI5QListI4QMapI7QString8QVariantEEN17QtMetaTypePrivate23QSequentialIterableImplENS7_33QSequentialIterableConvertFunctorIS6_EEED2Ev` | 0x7ff28 | 1012 |
| `_ZN11QMetaTypeIdI5QListI4QMapI7QString8QVariantEEE14qt_metatype_idEv` | 0x8031c | 808 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperI5QListI4QMapI7QString8QVariantEELb1EE9ConstructEPvPKv` | 0x80760 | 68 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperI5QListI4QMapI7QString8QVariantEELb1EE8DestructEPv` | 0x807a4 | 200 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate15ConnectionTypesINS_4ListIJP18PendingCallWatcherEEELb1EE5typesEv` | 0x60520 | 468 |

**New objects (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes12E_StreamTypeEE14qt_metatype_idEvE11metatype_id` | 0xa62cc | 4 |
| `_ZZN9QtPrivate19ValueTypeIsMetaTypeI5QListI4QMapI7QString8QVariantEELb1EE17registerConverterEiE1f` | 0xa62dc | 8 |
| `_ZZN11QMetaTypeIdI5QListI4QMapI7QString8QVariantEEE14qt_metatype_idEvE11metatype_id` | 0xa62e4 | 4 |
| `_ZGVZN9QtPrivate19ValueTypeIsMetaTypeI5QListI4QMapI7QString8QVariantEELb1EE17registerConverterEiE1f` | 0xa62e8 | 4 |

### `/bin/odindb-send`

+15 / −1 functions · +2 / −0 objects

**New functions (15)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE8DestructEPv` | 0x14f2c4 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE9ConstructEPvPKv` | 0x14f2c8 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE8DestructEPv` | 0x14f2dc | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE9ConstructEPvPKv` | 0x14f2e0 | 20 |
| `_Z17qRegisterMetaTypeIN9HblmTypes15E_HwShareStatusEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x14f2f4 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes19E_HwShareDeviceTypeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x14f42c | 312 |
| `_ZN11CameraProxy26doRequest_img_transfer_usbE5QListI4QMapI7QString8QVariantEEj` | 0x15ce40 | 196 |
| `_ZN7AeProxy29doDo_reset_ael_after_exposureEv` | 0x15d6bc | 16 |
| `_ZN10ErrorProxy8doReportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_j` | 0x1616b0 | 368 |
| `_ZN8WmsProxy12doWifi_powerEb` | 0x16480c | 16 |
| `_ZN12HwshareProxy7doStartEv` | 0x1654a0 | 16 |
| `_ZN12HwshareProxy6doStopEv` | 0x1654b0 | 16 |
| `_ZNK12HwshareProxy8isSyncedEv` | 0x1654c0 | 12 |
| `_ZNK12HwshareProxy11isAvailableEv` | 0x1654cc | 12 |
| `_ZN12HwshareProxy10doTransferERK7QString5QListI4QMapIS0_8QVariantEE` | 0x168be8 | 656 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN10ErrorProxy8doReportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK7QStringS6_j` | 0x15b924 | 60 |

**New objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_HwShareStatusEE14qt_metatype_idEvE11metatype_id` | 0x1a26ec | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes19E_HwShareDeviceTypeEE14qt_metatype_idEvE11metatype_id` | 0x1a26f8 | 4 |

### `/bin/dji_wms`

+6 / −0 functions · +1 / −0 objects

**New functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNK8QMapNodeI7QString8QVariantE4copyEP8QMapDataIS0_S1_E` | 0xa950 | 304 |
| `_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv` | 0xaa80 | 3360 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE8DestructEPv` | 0x11778 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE9ConstructEPvPKv` | 0x1177c | 20 |
| `_ZN8QMapDataI7QString8QVariantE7destroyEv` | 0x11d3c | 6856 |
| `_ZN6QDebuglsEPKc` | 0x19e38 | 188 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes14E_ReturnStatusEE14qt_metatype_idEvE11metatype_id` | 0x4dc48 | 4 |

### `/bin/dji_wms-v1`

+6 / −0 functions · +1 / −0 objects

**New functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNK8QMapNodeI7QString8QVariantE4copyEP8QMapDataIS0_S1_E` | 0x97b8 | 304 |
| `_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv` | 0x98e8 | 3360 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE8DestructEPv` | 0x105e0 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE9ConstructEPvPKv` | 0x105e4 | 20 |
| `_ZN8QMapDataI7QString8QVariantE7destroyEv` | 0x10ba4 | 6856 |
| `_ZN6QDebuglsEPKc` | 0x18ca0 | 188 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes14E_ReturnStatusEE14qt_metatype_idEvE11metatype_id` | 0x37c38 | 4 |

### `/etc/firmware/rtnodes/app.elf`

+4 / −2 functions · +266 / −235 objects

**New functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `nodes_def_property_value` | 0x18474 | 56 |
| `CAMU_InitBool` | 0x28c50 | 20 |
| `ae_do_reset_ael_after_exposure_handler` | 0xabe58 | 84 |
| `e843419@00f4_00004a2f_434` | 0xfda10 | 8 |

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `camx_BracketingNumberOfFrames` | 0x28f5c | 124 |
| `camx_isLastImageInSeq` | 0x28fd8 | 152 |

**New objects (266)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.13193` | 0x1261e0 | 19 |
| `__func__.13210` | 0x1261f8 | 15 |
| `__func__.13248` | 0x126208 | 12 |
| `__func__.13270` | 0x126218 | 9 |
| `__func__.13285` | 0x126228 | 9 |
| `__func__.13303` | 0x126238 | 15 |
| `__func__.13336` | 0x126248 | 20 |
| `__func__.11655` | 0x126358 | 13 |
| `__func__.11680` | 0x126368 | 21 |
| `__func__.12802` | 0x126488 | 13 |
| `__func__.12836` | 0x126498 | 21 |
| `__func__.12850` | 0x1264b0 | 20 |
| `__func__.12872` | 0x1264c8 | 23 |
| `__func__.11856` | 0x126708 | 16 |
| `__func__.11940` | 0x126718 | 25 |
| `__func__.11953` | 0x126738 | 24 |
| `__func__.11951` | 0x126820 | 21 |
| `__func__.11966` | 0x126838 | 25 |
| `__func__.11980` | 0x126858 | 24 |
| `__func__.12002` | 0x126870 | 32 |
| `__func__.11756` | 0x126980 | 23 |
| `__func__.11521` | 0x127680 | 13 |
| `__func__.11555` | 0x127690 | 16 |
| `__func__.11569` | 0x1276a0 | 15 |
| `__func__.11591` | 0x1276b0 | 23 |
| `__FUNCTION__.13787` | 0x127e28 | 35 |
| `__FUNCTION__.13825` | 0x127e50 | 41 |
| `__func__.13927` | 0x127e80 | 33 |
| `__func__.13940` | 0x127ea8 | 31 |
| `__FUNCTION__.12778` | 0x128040 | 24 |
| `__FUNCTION__.12802` | 0x128058 | 24 |
| `__FUNCTION__.14508` | 0x128818 | 23 |
| `__func__.14589` | 0x128830 | 37 |
| `hblm_prop_camera_can_reprocess_raw_frame_buffer` | 0x128b48 | 31 |
| `hblm_prop_camera_liveview_allowed` | 0x128d80 | 17 |
| `hblm_prop_config_dump_preview` | 0x1295d0 | 13 |
| `hblm_prop_config_interval_ae_enabled` | 0x129918 | 20 |
| `hblm_prop_config_show_huawei_share` | 0x129bb0 | 18 |
| `hblm_prop_config_wifi_power_stored` | 0x12a0c0 | 18 |
| `hblm_prop_hwshare_can_suspend` | 0x12a1d8 | 12 |
| `hblm_prop_hwshare_device_list` | 0x12a1e8 | 12 |
| `hblm_prop_hwshare_device_name` | 0x12a1f8 | 12 |
| `hblm_prop_hwshare_device_type` | 0x12a208 | 12 |
| `hblm_prop_hwshare_status` | 0x12a218 | 7 |
| `hblm_prop_hwshare_transfer_progress` | 0x12a220 | 18 |
| `hblm_prop_lens_distance_scale_0` | 0x12a260 | 17 |
| `hblm_prop_lens_distance_scale_1` | 0x12a278 | 17 |
| `hblm_prop_lens_distance_scale_2` | 0x12a290 | 17 |
| `hblm_prop_lens_shutter_count` | 0x12a418 | 14 |
| `hblm_prop_phocus_video_mode` | 0x12a4a0 | 11 |

<details><summary>… 另 216 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `hblm_prop_suc_sys_state` | 0x12a980 | 10 |
| `hblm_prop_wms_bt_power` | 0x12abd8 | 9 |
| `__func__.13493` | 0x12d680 | 18 |
| `__func__.13207` | 0x12d698 | 15 |
| `__func__.13229` | 0x12d6c0 | 13 |
| `__func__.13191` | 0x12d6d0 | 13 |
| `__func__.13608` | 0x12d6e0 | 16 |
| `__FUNCTION__.14454` | 0x12e270 | 26 |
| `__func__.14566` | 0x12e290 | 33 |
| `__FUNCTION__.14590` | 0x12e2b8 | 28 |
| `__func__.14861` | 0x12e2d8 | 30 |
| `__func__.14948` | 0x12e2f8 | 34 |
| `__func__.14988` | 0x12e320 | 28 |
| `__func__.15016` | 0x12e340 | 32 |
| `__func__.15187` | 0x12ea08 | 29 |
| `__func__.15449` | 0x12ea28 | 27 |
| `__FUNCTION__.15490` | 0x12ea48 | 18 |
| `__FUNCTION__.15538` | 0x12ea60 | 39 |
| `__func__.15565` | 0x12ea88 | 27 |
| `__func__.12842` | 0x12ecc8 | 18 |
| `lensImprint.12809` | 0x12ece0 | 16 |
| `__func__.12511` | 0x12eec8 | 22 |
| `__func__.12543` | 0x12eee0 | 26 |
| `__func__.12390` | 0x12f160 | 35 |
| `__func__.12852` | 0x12f7b0 | 22 |
| `__func__.13129` | 0x12f7c8 | 21 |
| `__func__.12557` | 0x12fa70 | 24 |
| `__func__.13881` | 0x12fd88 | 30 |
| `__func__.12051` | 0x12fef0 | 23 |
| `__func__.12064` | 0x12ff08 | 22 |
| `__func__.13176` | 0x130318 | 24 |
| `__func__.13277` | 0x130330 | 27 |
| `__FUNCTION__.13383` | 0x130350 | 11 |
| `LM26HSEPEN_MASK.12025` | 0x130cb7 | 1 |
| `LM26HSEPEN_ADDR.12024` | 0x130cb8 | 1 |
| `BLKDUMMY_LSB_ADDR.12056` | 0x130cb9 | 1 |
| `BLKDUMMY_MSB_ADDR.12057` | 0x130cba | 1 |
| `BLKLEVEL_LSB_ADDR.12061` | 0x130cbb | 1 |
| `BLKLEVEL_MSB_ADDR.12062` | 0x130cbc | 1 |
| `EXCKDLY_ADDR.12078` | 0x130cbd | 1 |
| `SPL.11900` | 0x130ec4 | 4 |
| `SMD_ADDR.11919` | 0x130ec8 | 1 |
| `SMD_MASK.11920` | 0x130ec9 | 1 |
| `WINDOWMODE_ADDR.11927` | 0x130eca | 1 |
| `WINDOWMODE_MASK.11928` | 0x130ecb | 1 |
| `WINDOWMODE_VAL_BDUMMY_WDUMMY_VOPB_EFFECTIVE.11930` | 0x130ecc | 1 |
| `WINDOWMODE_VAL_DISABLED.11929` | 0x130ecd | 1 |
| `ROW.12079` | 0x1311ec | 4 |
| `ROW.12163` | 0x1311f0 | 4 |
| `__FUNCTION__.12602` | 0x131370 | 21 |
| `__FUNCTION__.12934` | 0x131720 | 11 |
| `__FUNCTION__.12222` | 0x1317a8 | 23 |
| `__func__.12026` | 0x132dc8 | 21 |
| `__func__.14765` | 0x133d98 | 8 |
| `__func__.12426` | 0x1340c8 | 31 |
| `__func__.13236` | 0x134358 | 19 |
| `__FUNCTION__.11983` | 0x134ac8 | 17 |
| `__FUNCTION__.12182` | 0x134ae0 | 31 |
| `__FUNCTION__.12254` | 0x134b00 | 35 |
| `__FUNCTION__.12267` | 0x134b28 | 46 |
| `__FUNCTION__.12283` | 0x134b58 | 35 |
| `__FUNCTION__.12316` | 0x134b80 | 23 |
| `AXI_HP1.12188` | 0x135034 | 4 |
| `AXI_HP3.12189` | 0x135038 | 4 |
| `__func__.13044` | 0x1351e0 | 21 |
| `__FUNCTION__.12400` | 0x1353e0 | 20 |
| `__func__.13512` | 0x135720 | 22 |
| `VCC_PL_INT.13235` | 0x135fd0 | 4 |
| `pl_por_b.13239` | 0x135fd4 | 4 |
| `pl_init.13240` | 0x135fd8 | 4 |
| `__FUNCTION__.11521` | 0x137550 | 9 |
| `__FUNCTION__.11550` | 0x137560 | 13 |
| `__FUNCTION__.11580` | 0x137570 | 9 |
| `__FUNCTION__.11611` | 0x137580 | 13 |
| `N.12364` | 0x137904 | 4 |
| `__FUNCTION__.12636` | 0x138c90 | 16 |
| `__func__.13114` | 0x138ca0 | 24 |
| `INVALID_CHANNEL.12528` | 0x13972c | 1 |
| `__func__.12750` | 0x139dc0 | 17 |
| `__func__.12821` | 0x139dd8 | 12 |
| `__func__.12848` | 0x139de8 | 16 |
| `dump_preview_defval` | 0x139f00 | 1 |
| `interval_ae_enabled_defval` | 0x139f84 | 1 |
| `show_huawei_share_defval` | 0x139fed | 1 |
| `wifi_power_stored_defval` | 0x13a0bc | 1 |
| `__func__.14502` | 0x13a528 | 36 |
| `__func__.13990` | 0x13aac0 | 33 |
| `__func__.13739` | 0x13bf80 | 23 |
| `__func__.14106` | 0x13bf98 | 22 |
| `__func__.14268` | 0x13bfb0 | 26 |
| `__func__.14290` | 0x13bfd0 | 20 |
| `__func__.14320` | 0x13bfe8 | 16 |
| `__func__.14448` | 0x13bff8 | 29 |
| `__func__.14536` | 0x13c018 | 21 |
| `__func__.14555` | 0x13c030 | 9 |
| `__func__.13049` | 0x13ced0 | 24 |
| `__func__.13241` | 0x13cee8 | 27 |
| `__func__.14345` | 0x13dab8 | 14 |
| `__func__.14438` | 0x13dac8 | 17 |
| `max_unsynced_frames.14443` | 0x13dae0 | 8 |
| `__func__.14468` | 0x13dae8 | 46 |
| `__func__.14708` | 0x13db18 | 12 |
| `__func__.14883` | 0x13db28 | 15 |
| `__func__.14972` | 0x13db38 | 26 |
| `__func__.14767` | 0x13e3c0 | 26 |
| `__func__.14781` | 0x13e3e0 | 37 |
| `__func__.14892` | 0x13e408 | 12 |
| `__func__.14946` | 0x13e418 | 21 |
| `__func__.14976` | 0x13e430 | 22 |
| `__func__.15043` | 0x13e448 | 22 |
| `__func__.15056` | 0x13e460 | 11 |
| `__func__.15226` | 0x13e470 | 15 |
| `__func__.12879` | 0x13e710 | 23 |
| `__func__.12147` | 0x13f670 | 11 |
| `__func__.12178` | 0x13f680 | 13 |
| `__func__.12211` | 0x13f690 | 10 |
| `__FUNCTION__.11834` | 0x13fa28 | 16 |
| `__FUNCTION__.11861` | 0x13fa38 | 14 |
| `__func__.13592` | 0x140620 | 21 |
| `__FUNCTION__.13922` | 0x140638 | 40 |
| `__FUNCTION__.14000` | 0x140660 | 35 |
| `__func__.12498` | 0x1406f0 | 39 |
| `__func__.13930` | 0x1410d0 | 21 |
| `__func__.13936` | 0x1410e8 | 22 |
| `__FUNCTION__.13945` | 0x141100 | 22 |
| `__func__.13952` | 0x141118 | 17 |
| `div.13961` | 0x14112c | 4 |
| `steps.13962` | 0x141130 | 4 |
| `dg_array.13958` | 0x141138 | 8 |
| `ag_array.13959` | 0x141140 | 8 |
| `ep_array.13960` | 0x141148 | 8 |
| `__FUNCTION__.14029` | 0x141150 | 39 |
| `__func__.14053` | 0x141178 | 39 |
| `__func__.14105` | 0x1411a0 | 25 |
| `__func__.14112` | 0x1411c0 | 24 |
| `__func__.14165` | 0x1411d8 | 34 |
| `__func__.14176` | 0x141228 | 34 |
| `__func__.14513` | 0x141250 | 16 |
| `__func__.14607` | 0x141260 | 25 |
| `__func__.14635` | 0x141280 | 22 |
| `__func__.14688` | 0x141298 | 17 |
| `__func__.14699` | 0x1412b0 | 15 |
| `__func__.14723` | 0x1412c0 | 30 |
| `__func__.14728` | 0x1412e0 | 11 |
| `__func__.14736` | 0x1412f0 | 19 |
| `__func__.14740` | 0x141308 | 36 |
| `__func__.12154` | 0x141430 | 13 |
| `__func__.12193` | 0x141440 | 19 |
| `__func__.12203` | 0x141458 | 13 |
| `__FUNCTION__.12810` | 0x141a60 | 21 |
| `__func__.12833` | 0x141a78 | 17 |
| `__func__.12945` | 0x141a90 | 26 |
| `__FUNCTION__.12444` | 0x141ba0 | 18 |
| `__FUNCTION__.16034` | 0x142150 | 17 |
| `__FUNCTION__.16219` | 0x142168 | 19 |
| `__FUNCTION__.12480` | 0x142860 | 22 |
| `tribase.4297` | 0x143018 | 4 |
| `N.11325` | 0x143384 | 4 |
| `af_cur_pos_old.12791` | 0x14e078 | 4 |
| `__compound_literal.151` | 0x14e558 | 1 |
| `__compound_literal.152` | 0x14e560 | 1 |
| `__compound_literal.153` | 0x14e568 | 2 |
| `__compound_literal.154` | 0x14e570 | 2 |
| `__compound_literal.155` | 0x14e578 | 3 |
| `__compound_literal.156` | 0x14e580 | 3 |
| `__compound_literal.157` | 0x14e588 | 2 |
| `__compound_literal.158` | 0x14e590 | 1 |
| `oldState.14624` | 0x14e610 | 1 |
| `dynImprint.12810` | 0x14e620 | 16 |
| `md5_imx161.12727` | 0x14e640 | 16 |
| `md5_imx211.12728` | 0x14e650 | 16 |
| `pxVectorTable.10723` | 0x14e668 | 8 |
| `id.13032` | 0x14fd5c | 4 |
| `id.13041` | 0x14fd60 | 4 |
| `tmpDataBuffer.13500` | 0x15d2d8 | 257 |
| `prop_handler_msg.13458` | 0x162d30 | 274 |
| `RecoveryImageNextPartition.14808` | 0x162f70 | 2 |
| `resp.15457` | 0x1630e8 | 5 |
| `old_point.15476` | 0x1630f0 | 4 |
| `lastupdate.15478` | 0x1630f4 | 4 |
| `gpioInit.13316` | 0x163220 | 1 |
| `started.13829` | 0x1633d2 | 1 |
| `b.14477` | 0x16b1b0 | 514 |
| `msg.14719` | 0x16b3b8 | 274 |
| `msg2.14720` | 0x16b4d0 | 4 |
| `buf.14730` | 0x16b4d8 | 256 |
| `mode.14745` | 0x16b5d8 | 1 |
| `stopdown.14835` | 0x16b5d9 | 1 |
| `old_checksum.13410` | 0x16b6c8 | 4 |
| `b.12355` | 0x16c170 | 65 |
| `FileInfo.13010` | 0x16cd60 | 24 |
| `retry.14771` | 0x16ea7c | 2 |
| `ticks_since_last_dir_change.12748` | 0x16ecb0 | 2 |
| `lastState.12882` | 0x16ecb4 | 4 |
| `last_ts.13511` | 0x17d2b0 | 8 |
| `retry_count.13298` | 0x17d2bc | 4 |
| `check_id.14428` | 0x18e3eb | 1 |
| `last_id.14429` | 0x18e3ec | 1 |
| `aaa_stat.14847` | 0x18e3f0 | 55616 |
| `info_update_cnt.14915` | 0x19bd30 | 4 |
| `ae_spi_count.13984` | 0x19bd34 | 4 |
| `noLensTraced.14800` | 0x19beb0 | 1 |
| `cnt.14653` | 0x1f5d34 | 4 |
| `md5_digest.13773` | 0x11f6288 | 16 |
| `previousValue.13929` | 0x11fa278 | 4 |
| `previousValue.13935` | 0x11fa27c | 4 |
| `previous_value.13951` | 0x11fa280 | 8 |
| `count.13970` | 0x11fa288 | 4 |
| `index.13971` | 0x11fa28c | 4 |
| `dgain.13963` | 0x11fa290 | 4 |
| `again.13964` | 0x11fa294 | 4 |
| `ep_ms.13965` | 0x11fa298 | 4 |
| `tmpDisabled.11561` | 0x11fab78 | 1 |
| `mSystemState` | 0x7f00057a | 1 |
| `flushType.14261` | 0x7f002048 | 4 |
| `imageMode.14262` | 0x7f00204c | 4 |

</details>

**Removed objects (235)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.13020` | 0x124e60 | 19 |
| `__func__.13037` | 0x124e78 | 15 |
| `__func__.13075` | 0x124e88 | 12 |
| `__func__.13097` | 0x124e98 | 9 |
| `__func__.13112` | 0x124ea8 | 9 |
| `__func__.13163` | 0x124ec8 | 20 |
| `__func__.13246` | 0x124ee0 | 11 |
| `__func__.11484` | 0x124fd8 | 13 |
| `__func__.11509` | 0x124fe8 | 21 |
| `__func__.12631` | 0x125108 | 13 |
| `__func__.12679` | 0x125130 | 20 |
| `__func__.12701` | 0x125148 | 23 |
| `__func__.11683` | 0x125388 | 16 |
| `__func__.11767` | 0x125398 | 25 |
| `__func__.11780` | 0x1253b8 | 24 |
| `__func__.11778` | 0x1254a0 | 21 |
| `__func__.11793` | 0x1254b8 | 25 |
| `__func__.11807` | 0x1254d8 | 24 |
| `__func__.11829` | 0x1254f0 | 32 |
| `__func__.11585` | 0x125600 | 23 |
| `__func__.11350` | 0x126300 | 13 |
| `__func__.11384` | 0x126310 | 16 |
| `__func__.11398` | 0x126320 | 15 |
| `__func__.11420` | 0x126330 | 23 |
| `__FUNCTION__.13614` | 0x126aa8 | 35 |
| `__FUNCTION__.13652` | 0x126ad0 | 41 |
| `__func__.13754` | 0x126b00 | 33 |
| `__func__.13767` | 0x126b28 | 31 |
| `__FUNCTION__.12604` | 0x126cc0 | 24 |
| `__FUNCTION__.12628` | 0x126cd8 | 24 |
| `__FUNCTION__.14335` | 0x127498 | 23 |
| `__func__.14416` | 0x1274b0 | 37 |
| `hblm_prop_config_wifi_power` | 0x128cc8 | 11 |
| `__func__.13281` | 0x12bfd0 | 18 |
| `__func__.12971` | 0x12bff8 | 17 |
| `__func__.13024` | 0x12c010 | 13 |
| `__func__.12986` | 0x12c020 | 13 |
| `__func__.13396` | 0x12c030 | 16 |
| `__FUNCTION__.14278` | 0x12cbc0 | 26 |
| `__func__.14390` | 0x12cbe0 | 33 |
| `__FUNCTION__.14414` | 0x12cc08 | 28 |
| `__func__.14685` | 0x12cc28 | 30 |
| `__func__.14772` | 0x12cc48 | 34 |
| `__func__.14812` | 0x12cc70 | 28 |
| `__func__.14840` | 0x12cc90 | 32 |
| `__func__.14867` | 0x12ccb0 | 21 |
| `__func__.15013` | 0x12d358 | 29 |
| `__func__.15214` | 0x12d378 | 27 |
| `__FUNCTION__.15250` | 0x12d398 | 18 |
| `__FUNCTION__.15286` | 0x12d3b0 | 39 |

<details><summary>… 另 185 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15313` | 0x12d3d8 | 27 |
| `__func__.12665` | 0x12d618 | 18 |
| `lensImprint.12632` | 0x12d630 | 16 |
| `__func__.12335` | 0x12d818 | 22 |
| `__func__.12367` | 0x12d830 | 26 |
| `__func__.12682` | 0x12e100 | 22 |
| `__func__.12960` | 0x12e118 | 21 |
| `__func__.12381` | 0x12e3c0 | 24 |
| `__func__.13707` | 0x12e6d8 | 30 |
| `__func__.11878` | 0x12e840 | 23 |
| `__func__.11891` | 0x12e858 | 22 |
| `__func__.13002` | 0x12ec68 | 24 |
| `__func__.13103` | 0x12ec80 | 27 |
| `__FUNCTION__.13209` | 0x12eca0 | 11 |
| `LM26HSEPEN_MASK.11852` | 0x12f607 | 1 |
| `LM26HSEPEN_ADDR.11851` | 0x12f608 | 1 |
| `BLKDUMMY_LSB_ADDR.11883` | 0x12f609 | 1 |
| `BLKDUMMY_MSB_ADDR.11884` | 0x12f60a | 1 |
| `BLKLEVEL_LSB_ADDR.11888` | 0x12f60b | 1 |
| `BLKLEVEL_MSB_ADDR.11889` | 0x12f60c | 1 |
| `EXCKDLY_ADDR.11905` | 0x12f60d | 1 |
| `SPL.11727` | 0x12f814 | 4 |
| `SMD_ADDR.11746` | 0x12f818 | 1 |
| `SMD_MASK.11747` | 0x12f819 | 1 |
| `WINDOWMODE_ADDR.11754` | 0x12f81a | 1 |
| `WINDOWMODE_MASK.11755` | 0x12f81b | 1 |
| `WINDOWMODE_VAL_BDUMMY_WDUMMY_VOPB_EFFECTIVE.11757` | 0x12f81c | 1 |
| `WINDOWMODE_VAL_DISABLED.11756` | 0x12f81d | 1 |
| `ROW.11906` | 0x12fb3c | 4 |
| `ROW.11990` | 0x12fb40 | 4 |
| `__FUNCTION__.12429` | 0x12fcc0 | 21 |
| `__FUNCTION__.12758` | 0x130070 | 11 |
| `__FUNCTION__.12051` | 0x1300f8 | 23 |
| `__func__.11855` | 0x131718 | 21 |
| `__func__.14591` | 0x1326e8 | 8 |
| `__func__.12253` | 0x132a18 | 31 |
| `__func__.13063` | 0x132ca8 | 19 |
| `__FUNCTION__.11810` | 0x133418 | 17 |
| `__FUNCTION__.12009` | 0x133430 | 31 |
| `__FUNCTION__.12081` | 0x133450 | 35 |
| `__FUNCTION__.12094` | 0x133478 | 46 |
| `__FUNCTION__.12110` | 0x1334a8 | 35 |
| `__FUNCTION__.12143` | 0x1334d0 | 23 |
| `AXI_HP1.12017` | 0x133984 | 4 |
| `AXI_HP3.12018` | 0x133988 | 4 |
| `__func__.12871` | 0x133b30 | 21 |
| `__FUNCTION__.12227` | 0x133d30 | 20 |
| `__func__.13339` | 0x134070 | 22 |
| `VCC_PL_INT.13064` | 0x134920 | 4 |
| `pl_por_b.13068` | 0x134924 | 4 |
| `pl_init.13069` | 0x134928 | 4 |
| `__FUNCTION__.11350` | 0x135ea0 | 9 |
| `__FUNCTION__.11379` | 0x135eb0 | 13 |
| `__FUNCTION__.11409` | 0x135ec0 | 9 |
| `__FUNCTION__.11440` | 0x135ed0 | 13 |
| `N.12193` | 0x136254 | 4 |
| `__FUNCTION__.12465` | 0x1375e0 | 16 |
| `__func__.12943` | 0x1375f0 | 24 |
| `__func__.12959` | 0x137608 | 26 |
| `INVALID_CHANNEL.12357` | 0x13807c | 1 |
| `__func__.12579` | 0x138710 | 17 |
| `__func__.12650` | 0x138728 | 12 |
| `__func__.12677` | 0x138738 | 16 |
| `wifi_power_defval` | 0x138a08 | 1 |
| `__func__.14326` | 0x138e70 | 36 |
| `__func__.13817` | 0x139408 | 33 |
| `__func__.13566` | 0x13a908 | 23 |
| `__func__.13932` | 0x13a920 | 22 |
| `__func__.14094` | 0x13a938 | 26 |
| `__func__.14116` | 0x13a958 | 20 |
| `__func__.14146` | 0x13a970 | 16 |
| `__func__.14274` | 0x13a980 | 29 |
| `__func__.14362` | 0x13a9a0 | 21 |
| `__func__.14381` | 0x13a9b8 | 9 |
| `__func__.12878` | 0x13b858 | 24 |
| `__func__.13070` | 0x13b870 | 27 |
| `__func__.14265` | 0x13c450 | 17 |
| `max_unsynced_frames.14270` | 0x13c468 | 8 |
| `__func__.14295` | 0x13c470 | 46 |
| `__func__.14535` | 0x13c4a0 | 12 |
| `__func__.14799` | 0x13c4c0 | 26 |
| `__func__.14590` | 0x13cd38 | 26 |
| `__func__.14604` | 0x13cd58 | 37 |
| `__func__.14710` | 0x13cd80 | 12 |
| `__func__.14763` | 0x13cd90 | 21 |
| `__func__.14793` | 0x13cda8 | 22 |
| `__func__.14860` | 0x13cdc0 | 22 |
| `__func__.14873` | 0x13cdd8 | 11 |
| `__func__.15042` | 0x13cde8 | 15 |
| `__func__.12708` | 0x13d088 | 23 |
| `__func__.11976` | 0x13dfe8 | 11 |
| `__func__.12007` | 0x13dff8 | 13 |
| `__func__.12040` | 0x13e008 | 10 |
| `__FUNCTION__.11663` | 0x13e3a0 | 16 |
| `__FUNCTION__.11690` | 0x13e3b0 | 14 |
| `__FUNCTION__.13749` | 0x13efb0 | 40 |
| `__FUNCTION__.13827` | 0x13efd8 | 35 |
| `__func__.12325` | 0x13f068 | 39 |
| `__func__.13757` | 0x13fa00 | 21 |
| `__func__.13763` | 0x13fa18 | 22 |
| `__FUNCTION__.13772` | 0x13fa30 | 22 |
| `__func__.13779` | 0x13fa48 | 17 |
| `div.13788` | 0x13fa5c | 4 |
| `steps.13789` | 0x13fa60 | 4 |
| `dg_array.13785` | 0x13fa68 | 8 |
| `ag_array.13786` | 0x13fa70 | 8 |
| `ep_array.13787` | 0x13fa78 | 8 |
| `__FUNCTION__.13856` | 0x13fa80 | 39 |
| `__func__.13871` | 0x13faa8 | 39 |
| `__func__.13921` | 0x13fad0 | 25 |
| `__func__.13928` | 0x13faf0 | 24 |
| `__func__.13981` | 0x13fb08 | 34 |
| `__func__.13988` | 0x13fb30 | 38 |
| `__func__.13992` | 0x13fb58 | 34 |
| `__func__.14329` | 0x13fb80 | 16 |
| `__func__.14423` | 0x13fb90 | 25 |
| `__func__.14451` | 0x13fbb0 | 22 |
| `__func__.14504` | 0x13fbc8 | 17 |
| `__func__.14515` | 0x13fbe0 | 15 |
| `__func__.14539` | 0x13fbf0 | 30 |
| `__func__.14544` | 0x13fc10 | 11 |
| `__func__.14552` | 0x13fc20 | 19 |
| `__func__.14556` | 0x13fc38 | 36 |
| `__func__.11981` | 0x13fd60 | 13 |
| `__func__.12020` | 0x13fd70 | 19 |
| `__func__.12030` | 0x13fd88 | 13 |
| `__func__.12039` | 0x13fd98 | 14 |
| `__FUNCTION__.12637` | 0x140360 | 21 |
| `__func__.12660` | 0x140378 | 17 |
| `__func__.12772` | 0x140390 | 26 |
| `__FUNCTION__.12271` | 0x1404a0 | 18 |
| `__FUNCTION__.15858` | 0x140a50 | 17 |
| `__FUNCTION__.16043` | 0x140a68 | 19 |
| `__FUNCTION__.12307` | 0x141160 | 22 |
| `tribase.4264` | 0x1418f8 | 4 |
| `N.11154` | 0x141c64 | 4 |
| `af_cur_pos_old.12620` | 0x14c6f8 | 4 |
| `oldState.14448` | 0x14cc50 | 1 |
| `dynImprint.12633` | 0x14cc60 | 16 |
| `md5_imx161.12554` | 0x14cc80 | 16 |
| `md5_imx211.12555` | 0x14cc90 | 16 |
| `pxVectorTable.10552` | 0x14cca8 | 8 |
| `id.12847` | 0x14e39c | 4 |
| `id.12856` | 0x14e3a0 | 4 |
| `tmpDataBuffer.13327` | 0x15b2d8 | 257 |
| `prop_handler_msg.13246` | 0x1608f0 | 274 |
| `RecoveryImageNextPartition.14632` | 0x160b30 | 2 |
| `resp.15222` | 0x160ca8 | 5 |
| `old_point.15236` | 0x160cb0 | 4 |
| `lastupdate.15238` | 0x160cb4 | 4 |
| `gpioInit.13140` | 0x160de0 | 1 |
| `started.13655` | 0x160f92 | 1 |
| `b.14303` | 0x168d70 | 514 |
| `msg.14545` | 0x168f78 | 274 |
| `msg2.14546` | 0x169090 | 4 |
| `buf.14556` | 0x169098 | 256 |
| `mode.14571` | 0x169198 | 1 |
| `stopdown.14661` | 0x169199 | 1 |
| `old_checksum.13237` | 0x169288 | 4 |
| `b.12184` | 0x169d30 | 65 |
| `FileInfo.12839` | 0x16a920 | 24 |
| `retry.14597` | 0x16c63c | 2 |
| `ticks_since_last_dir_change.12577` | 0x16c870 | 2 |
| `lastState.12711` | 0x16c874 | 4 |
| `last_ts.13340` | 0x17ae70 | 8 |
| `retry_count.13127` | 0x17ae7c | 4 |
| `check_id.14255` | 0x18bfab | 1 |
| `last_id.14256` | 0x18bfac | 1 |
| `aaa_stat.14674` | 0x18bfb0 | 55616 |
| `info_update_cnt.14742` | 0x1998f0 | 4 |
| `ae_spi_count.13811` | 0x1998f4 | 4 |
| `noLensTraced.14619` | 0x199a70 | 1 |
| `cnt.14480` | 0x1f38f4 | 4 |
| `md5_digest.13600` | 0x11f3e48 | 16 |
| `previousValue.13756` | 0x11f7e38 | 4 |
| `previousValue.13762` | 0x11f7e3c | 4 |
| `previous_value.13778` | 0x11f7e40 | 8 |
| `count.13797` | 0x11f7e48 | 4 |
| `index.13798` | 0x11f7e4c | 4 |
| `dgain.13790` | 0x11f7e50 | 4 |
| `again.13791` | 0x11f7e54 | 4 |
| `ep_ms.13792` | 0x11f7e58 | 4 |
| `tmpDisabled.11390` | 0x11f8738 | 1 |
| `flushType.14077` | 0x7f001d78 | 4 |
| `imageMode.14078` | 0x7f001d7c | 4 |

</details>

### `/bin/analytics`

+2 / −2 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN4QMapI7QString8QVariantED1Ev` | 0x1016c | 120 |
| `_ZN4QMapI7QString8QVariantED2Ev` | 0x1016c | 120 |

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNSt3__18functionIFvjEED1Ev` | 0x10624 | 120 |
| `_ZNSt3__18functionIFvjEED2Ev` | 0x10624 | 120 |

### `/bin/msg2dbus`

+4 / −0 functions · +2 / −0 objects

**New functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes27E_FocusBracketingStrategiesELb1EE8DestructEPv` | 0x38988 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes27E_FocusBracketingStrategiesELb1EE9ConstructEPvPKv` | 0x3898c | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_DistanceUnitELb1EE8DestructEPv` | 0x389d0 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_DistanceUnitELb1EE9ConstructEPvPKv` | 0x389d4 | 20 |

**New objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes14E_DistanceUnitEE14qt_metatype_idEvE11metatype_id` | 0xab160 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes27E_FocusBracketingStrategiesEE14qt_metatype_idEvE11metatype_id` | 0xab1a0 | 4 |

### `/lib/libservice.so`

+4 / −0 functions · +0 / −0 objects

**New functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN3dji6camera13CameraService14setDumpPreviewEb` | 0x393e5 | 8 |
| `_ZThn4_N3dji6camera13CameraService14setDumpPreviewEb` | 0x393ed | 8 |
| `_ZN3dji6camera13CameraService13setSaveFolderERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE` | 0x39b45 | 256 |
| `_ZThn4_N3dji6camera13CameraService13setSaveFolderERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE` | 0x39c45 | 8 |

### `/bin/bodystate`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN4QMapI7QString8QVariantED1Ev` | 0x24d00 | 120 |
| `_ZN4QMapI7QString8QVariantED2Ev` | 0x24d00 | 120 |

### `/bin/configstore`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv` | 0x28104 | 3360 |
| `_ZN8QMapDataI7QString8QVariantE7destroyEv` | 0x28e24 | 6856 |

### `/bin/gpsd`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv` | 0x78c8 | 3360 |
| `_ZN8QMapDataI7QString8QVariantE7destroyEv` | 0x85e8 | 6856 |

### `/lib/libdcam_frwk.so`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `cam_cap_eng_set_capture_dump_path` | 0x3f98d | 212 |

### `/bin/audio`

+0 / −0 functions · +0 / −0 objects

### `/bin/debuggerd`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_amt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_blackbox`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_cht`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_cspp`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_rcam`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/bin/hex-writer`

+0 / −0 functions · +0 / −0 objects

### `/bin/metadata`

+0 / −0 functions · +0 / −0 objects

### `/bin/msg2dbus-test`

+0 / −0 functions · +0 / −0 objects

### `/bin/preview`

+0 / −0 functions · +0 / −0 objects

### `/bin/prodconfig-tool`

+0 / −0 functions · +0 / −0 objects

### `/bin/sutest`

+0 / −0 functions · +0 / −0 objects

### `/bin/sysman`

+0 / −0 functions · +0 / −0 objects

### `/bin/upgrade_fw`

+0 / −0 functions · +0 / −0 objects

### `/bin/upgraded`

+0 / −0 functions · +0 / −0 objects

### `/bin/usbd`

+0 / −0 functions · +0 / −0 objects

### `/bin/vdec_test`

+0 / −0 functions · +0 / −0 objects

### `/bin/victory-gui-static`

+0 / −0 functions · +0 / −0 objects

### `/bin/vxe_testbench`

+0 / −0 functions · +0 / −0 objects

### `/etc/firmware/rtnodes/power-control.elf`

+0 / −0 functions · +37 / −37 objects

**New objects (37)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.13173` | 0x800a69d | 16 |
| `__FUNCTION__.13114` | 0x800a6ad | 17 |
| `__FUNCTION__.13155` | 0x800a6be | 16 |
| `__FUNCTION__.13137` | 0x800a6ce | 16 |
| `__FUNCTION__.13047` | 0x800a6de | 17 |
| `__FUNCTION__.13103` | 0x800a6ef | 17 |
| `__FUNCTION__.13164` | 0x800ac35 | 16 |
| `__FUNCTION__.13056` | 0x800ac45 | 16 |
| `__FUNCTION__.13146` | 0x800ac55 | 16 |
| `__FUNCTION__.13074` | 0x800ac65 | 16 |
| `__FUNCTION__.13083` | 0x800ac75 | 16 |
| `__FUNCTION__.13128` | 0x800ac85 | 17 |
| `__FUNCTION__.13065` | 0x800ac96 | 17 |
| `__FUNCTION__.13092` | 0x800aca7 | 16 |
| `__func__.13476` | 0x800adb6 | 26 |
| `__func__.13483` | 0x800add0 | 23 |
| `__func__.13487` | 0x800ade7 | 28 |
| `__func__.13466` | 0x800af97 | 26 |
| `__FUNCTION__.12918` | 0x800b0d5 | 13 |
| `__FUNCTION__.12874` | 0x800b0e2 | 21 |
| `__FUNCTION__.12929` | 0x800b0f7 | 14 |
| `__FUNCTION__.12951` | 0x800b1f8 | 15 |
| `__FUNCTION__.12996` | 0x800b207 | 22 |
| `__FUNCTION__.12961` | 0x800b21d | 14 |
| `__FUNCTION__.12901` | 0x800b22b | 14 |
| `__FUNCTION__.12940` | 0x800b239 | 14 |
| `__FUNCTION__.12969` | 0x800b247 | 15 |
| `__FUNCTION__.12909` | 0x800b256 | 15 |
| `__FUNCTION__.12147` | 0x800b48e | 12 |
| `__FUNCTION__.12154` | 0x800b49a | 13 |
| `__FUNCTION__.12165` | 0x800b4a7 | 12 |
| `__FUNCTION__.12120` | 0x800b648 | 23 |
| `__FUNCTION__.12183` | 0x800b65f | 27 |
| `__FUNCTION__.12190` | 0x800b67a | 14 |
| `__FUNCTION__.12132` | 0x800b688 | 22 |
| `SDO_ACT_ON.12122` | 0x800b69e | 1 |
| `__FUNCTION__.12176` | 0x800b69f | 27 |

**Removed objects (37)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.12921` | 0x800a699 | 16 |
| `__FUNCTION__.12984` | 0x800a6a9 | 16 |
| `__FUNCTION__.12876` | 0x800a6b9 | 17 |
| `__FUNCTION__.12932` | 0x800a6ca | 17 |
| `__FUNCTION__.12912` | 0x800a6db | 16 |
| `__FUNCTION__.12885` | 0x800a6eb | 16 |
| `__FUNCTION__.12894` | 0x800a6fb | 17 |
| `__FUNCTION__.12943` | 0x800a70c | 17 |
| `__FUNCTION__.13002` | 0x800ac52 | 16 |
| `__FUNCTION__.12993` | 0x800ac62 | 16 |
| `__FUNCTION__.12957` | 0x800ac72 | 17 |
| `__FUNCTION__.12903` | 0x800ac83 | 16 |
| `__FUNCTION__.12966` | 0x800ac93 | 16 |
| `__FUNCTION__.12975` | 0x800aca3 | 16 |
| `__func__.13312` | 0x800adb2 | 23 |
| `__func__.13316` | 0x800adc9 | 28 |
| `__func__.13295` | 0x800af79 | 26 |
| `__func__.13305` | 0x800af93 | 26 |
| `__FUNCTION__.12758` | 0x800b0d1 | 14 |
| `__FUNCTION__.12703` | 0x800b0df | 21 |
| `__FUNCTION__.12769` | 0x800b0f4 | 14 |
| `__FUNCTION__.12780` | 0x800b102 | 15 |
| `__FUNCTION__.12790` | 0x800b204 | 14 |
| `__FUNCTION__.12730` | 0x800b212 | 14 |
| `__FUNCTION__.12825` | 0x800b220 | 22 |
| `__FUNCTION__.12798` | 0x800b236 | 15 |
| `__FUNCTION__.12738` | 0x800b245 | 15 |
| `__FUNCTION__.12747` | 0x800b254 | 13 |
| `__FUNCTION__.11983` | 0x800b48a | 13 |
| `__FUNCTION__.12012` | 0x800b497 | 27 |
| `__FUNCTION__.11994` | 0x800b4b2 | 12 |
| `__FUNCTION__.11949` | 0x800b4be | 23 |
| `__FUNCTION__.12019` | 0x800b4d5 | 14 |
| `__FUNCTION__.11961` | 0x800b678 | 22 |
| `SDO_ACT_ON.11951` | 0x800b68e | 1 |
| `__FUNCTION__.12005` | 0x800b68f | 27 |
| `__FUNCTION__.11976` | 0x800b6aa | 12 |

### `/lib/libAppsMessaging.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libLLVM.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libMessageTransport.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libduml_ffremux.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libduml_frwk.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libduml_hal_cam.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libhblupgrade.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libhelper_api_sa.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libmod_x1dm2.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libomx_vxd.so`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **1609** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/victory-gui-static`

<details><summary>新增 354 条字符串, 展示前 100 条</summary>

````text
                <line x1="-5.16972568e-14" y1="6.16465402e-14" x2="25.342707" y2="25.342707" id="
                <line x1="5.97158441e-14" y1="2.1856147e-14" x2="25.342707" y2="25.342707" id="
                <use xlink:href="#path-1"></use>
            </mask>
            <g id="
            <mask id="mask-2" fill="white">
            <path d="M12.2350469,6.38513064 C10.3001069,8.31949944 9.10287168,10.9921442 9.10287168,13.9443914 C9.10287168,16.8954962 10.2992501,19.5675698 12.2333333,21.501653" id="Stroke-5" stroke="#808080" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M12.2350469,6.38513064 C10.3001069,8.31949944 9.10287168,10.9921442 9.10287168,13.9443914 C9.10287168,16.8954962 10.2992501,19.5675698 12.2333333,21.501653" id="Stroke-5" stroke="#FFFFFF" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M27.3501127,21.5029668 C29.2844815,19.568598 30.4811455,16.8962388 30.4811455,13.9445628 C30.4811455,10.9928868 29.2844815,8.3205276 27.3501127,6.3864444" id="Stroke-7" stroke="#808080" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M27.3501127,21.5029668 C29.2844815,19.568598 30.4811455,16.8962388 30.4811455,13.9445628 C30.4811455,10.9928868 29.2844815,8.3205276 27.3501127,6.3864444" id="Stroke-7" stroke="#FFFFFF" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M33.6486494,0.08799336 C37.1949446,3.63428856 39.3883526,8.53318536 39.3883526,13.9444486 C39.3883526,19.3559974 37.1943734,24.2548942 33.6483638,27.8011894" id="Stroke-9" stroke="#808080" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M33.6486494,0.08799336 C37.1949446,3.63428856 39.3883526,8.53318536 39.3883526,13.9444486 C39.3883526,19.3559974 37.1943734,24.2548942 33.6483638,27.8011894" id="Stroke-9" stroke="#FFFFFF" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M5.93485368,27.8003897 C2.38912968,24.2543801 0.19572168,19.3554833 0.19572168,13.9445057 C0.19572168,8.53267128 2.38970088,3.63348888 5.93628168,0.08719368" id="Stroke-3" stroke="#808080" stroke-width="2.64" stroke-linecap="square"></path>
            <path d="M5.93485368,27.8003897 C2.38912968,24.2543801 0.19572168,19.3554833 0.19572168,13.9445057 C0.19572168,8.53267128 2.38970088,3.63348888 5.93628168,0.08719368" id="Stroke-3" stroke="#FFFFFF" stroke-width="2.64" stroke-linecap="square"></path>
            <use id="Clip-2" fill="#808080" xlink:href="#path-1"></use>
            <use id="Clip-2" fill="#FFFFFF" xlink:href="#path-1"></use>
        <g id="ic/huawei-book">
        <path d="M16.5850776,13.94442 C16.5850776,15.7154256 18.02136,17.1511368 19.7917944,17.1511368 L19.7917944,17.1511368 C21.5628,17.1511368 22.9985112,15.7154256 22.9985112,13.94442 L22.9985112,13.94442 C22.9985112,12.1734144 21.5628,10.7377032 19.7917944,10.7377032 L19.7917944,10.7377032 C18.02136,10.7377032 16.5850776,12.1734144 16.5850776,13.94442 L16.5850776,13.94442 Z" id="path-1"></path>
    <g id="ic_cancel" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" stroke-linecap="square">
    <g id="ic_huawei-book" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
    <g id="ic_huawei-pad" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
    <g id="ic_huawei-phone" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
    <g id="ic_huawei-screen" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
    <g id="ic_huawei-share" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
    <g id="ic_huawei-share_inactive" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
    <title>ic_cancel</title>
    <title>ic_huawei book</title>
    <title>ic_huawei pad</title>
    <title>ic_huawei phone</title>
    <title>ic_huawei screen</title>
    <title>ic_huawei share</title>
    <title>ic_huawei share_inactive</title>
 "M_=YO-
" fill="#FFFFFF" x="11.44" y="33" width="21.12" height="3.96"></rect>
" fill="#FFFFFF" x="13.64" y="32.56" width="16.72" height="3.96"></rect>
" fill="#FFFFFF" x="15.4" y="31.68" width="13.64" height="2.2"></rect>
" fill="#FFFFFF" x="8.36" y="31.68" width="27.72" height="2.2"></rect>
" stroke="#FFFFFF" stroke-width="1.76" x="12.32" y="8.36" width="19.36" height="27.72"></rect>
" stroke="#FFFFFF" stroke-width="1.76" x="14.52" y="8.36" width="14.96" height="27.28"></rect>
" stroke="#FFFFFF" stroke-width="1.76" x="9.24" y="11" width="25.96" height="18.04"></rect>
" stroke="#FFFFFF" stroke-width="2.64">
" transform="translate(12.671354, 12.671354) scale(-1, 1) translate(-12.671354, -12.671354) "></line>
" transform="translate(15.120000, 15.120000)">
" transform="translate(8.400000, 14.000000)">
"ESRR>2
"sVCMo,
#M&#Ep
#[bTik
#nHj>B2x
$PS<NUL
$jCR)r^
)L S w
,_sDP_
-A]:b7
-iU20u;
.Vb.Z@
/Hx:st2
/ZgYK+
/h=/QhP
/hwshare
0F+y9m
0IrC/u
0J\MkH6
0O0nj_Vh0
0c0f0D0~0Y
0hSXOM
0k0g0M0~0[0
0k0j0c0f0D0
0l4-n)[
0nSXOM
12HwshareProxy
14HwshareProxyUI
17HuaweiDeviceModel
1<?xml version="1.0" encoding="UTF-8"?>
1L6!ce@
21HwshareProxyInterface
28Ua~-~
2Us4|@)
4Huawei Share must be enabled on the receiving device
4Xcs.3b\>
5a2&q7
7#ROS_
8=8QA=e
8Y1eW0
8}Bkb0
:?f3m/~
:c}i55
;IiH5xf
<Lens failed to power off correctly. Please reattach battery.
>c hUD
?Bhr7m
@_cs)Xa
@bRJ&ZgJ
Accept on device
Address
Browse was empty
C#|7o*m
C,&a=F-
CMtxCK:
CW6HW;/
````

</details>

> 其余 254 条见 `result.json`。

### `/bin/phocus`

<details><summary>新增 280 条字符串, 展示前 100 条</summary>

````text
*NSt3__110__function6__funcIZN13ReadParameter15OnPhocusMessageERK14QSharedPointerI13PhocusMessageEEUlRK7QStringE2_NS_9allocatorISB_EEFvSA_EEE
*NSt3__110__function6__funcIZN13ReadParameter15OnPhocusMessageERK14QSharedPointerI13PhocusMessageEEUlvE3_NS_9allocatorIS8_EEFvvEEE
*NSt3__110__function6__funcIZN14PhocusNotifier19onLensFamilyChangedEiEUlRK7QStringE1_NS_9allocatorIS6_EEFvS5_EEE
*NSt3__110__function6__funcIZN14PhocusNotifier19onLensFamilyChangedEiEUlRK7QStringE_NS_9allocatorIS6_EEFvS5_EEE
*NSt3__110__function6__funcIZN14PhocusNotifier19onLensFamilyChangedEiEUlvE0_NS_9allocatorIS3_EEFvvEEE
*NSt3__110__function6__funcIZN14PhocusNotifier19onLensFamilyChangedEiEUlvE2_NS_9allocatorIS3_EEFvvEEE
*ZN13ReadParameter15OnPhocusMessageERK14QSharedPointerI13PhocusMessageEEUlRK7QStringE2_
*ZN13ReadParameter15OnPhocusMessageERK14QSharedPointerI13PhocusMessageEEUlvE3_
*ZN14PhocusNotifier19onLensFamilyChangedEiEUlRK7QStringE1_
*ZN14PhocusNotifier19onLensFamilyChangedEiEUlRK7QStringE_
*ZN14PhocusNotifier19onLensFamilyChangedEiEUlvE0_
*ZN14PhocusNotifier19onLensFamilyChangedEiEUlvE2_
../../../helpers/gpsclient/gpsclient.cpp
../app/src/autofocusstatemachine.cpp
../app/src/liveviewstatemachine.cpp
15LiveViewRequest
16AutoFocusRequest
20LiveViewStateMachine
21AutoFocusStateMachine
9GpsClient
AutoFocusRequest
AutoFocusStateMachine
Available position sources
Created source
DriveModeExpBracketingAmount
DriveModeExpBracketingFrames
DriveModeExpBracketingInititalDelay
DriveModeExpBracketingParamInM
DriveModeExpBracketingSequence
DriveModeExpBracketingWhenFinished
DriveModeFocusBracketingExposureDelay
DriveModeFocusBracketingFrames
DriveModeFocusBracketingInititalDelay
DriveModeFocusBracketingSequence
DriveModeFocusBracketingStepSize
DriveModeFocusBracketingWhenFinished
DriveModeIntervalFrames
DriveModeIntervalInititalDelay
DriveModeIntervalWhenFinished
DriveModeSelfTimerLEDBlink
DriveModeSelfTimerTime
DriveModeSelfTimerWhenFinished
EShutter
E_StorageMode
E_VideoMode
Failed to request lens fw version number
Failed to request lens serial number
Failed to set live view state
FlasjEvAdjust
FocusDistanceScale
FocusPositionPercent
GPSStatusNotAvailable
GPSStatusPositionValid
GPSStatusSearching
GpsClient
GpsClient::GPSStatus
GpsStatus
HblmTypes::E_DistanceUnit
HblmTypes::E_DriveModes
HblmTypes::E_ExitOption
HblmTypes::E_FocusBracketingStepSizes
HblmTypes::E_FocusBracketingStrategies
HblmTypes::E_StorageDevice
HblmTypes::E_StorageMode
HblmTypes::E_SystemState
HblmTypes::E_VideoMode
HblmTypes::E_WhiteModes
Invalid sender object. Expected QGeoPositionInfoSource
Invalid source
Invalid system state
LensSerialNumber
LensShutterCount
LiveViewRequest
LiveViewStateMachine
MinimumObjectDistanceScale
NSt3__110__function6__baseIFvRK7QStringEEE
NSt3__110__function6__baseIFvvEEE
No Gps updates available. Gps status:
No exposure control mode requested
No zoom point requested
PrimaryDeviceImageRaw
QGeoPositionInfo
QGeoPositionInfoSource::Error
QuickExposureAdjust
Send valid iso values after full auto mode
Start using source
Stop using source
StorageMode
Unable to create source named
UnitOfDistance
Update started  @
WifiSsidName
_Z17qRegisterMetaTypeIN9HblmTypes11E_VideoModeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_Z17qRegisterMetaTypeIN9HblmTypes13E_SystemStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_ZN11QMetaMethod14fromSignalImplEPK11QMetaObjectPPv
_ZN13HblFinalStateC1ERK7QStringP6QState
_ZN13QStateMachine5startEv
_ZN13QStateMachine8addStateEP14QAbstractState
_ZN13QStateMachineC1EP7QObject
_ZN14QAbstractState16staticMetaObjectE
````

</details>

> 其余 180 条见 `result.json`。

### `/lib/libappscommon.so`

<details><summary>新增 228 条字符串, 展示前 100 条</summary>

````text
/hwshare
12HwshareProxy
21HwshareProxyInterface
E_CameraProperties_EShutter
E_ErrorCode_HwShareTransferCancelled
E_ErrorCode_HwShareTransferComplete
E_ErrorCode_HwShareTransferFailed
E_ErrorCode_HwShareTransferPartialComplete
E_ErrorCode_HwShareTransferRejected
E_ErrorCode_LensPowerOffFailed
E_ErrorCode_MaxFileSelectionReached
E_HwShareDeviceType
E_HwShareDeviceType_Book
E_HwShareDeviceType_Max
E_HwShareDeviceType_PC
E_HwShareDeviceType_Phone
E_HwShareDeviceType_Phone1
E_HwShareStatus
E_HwShareStatus_Cancelled
E_HwShareStatus_Idle
E_HwShareStatus_Init
E_HwShareStatus_Max
E_HwShareStatus_Rejected
E_HwShareStatus_Started
E_HwShareStatus_TransferComplete
E_HwShareStatus_TransferError
E_HwShareStatus_TransferFailed
E_HwShareStatus_TransferPartialComplete
E_HwShareStatus_Transferring
E_HwShareStatus_Waiting
E_StreamType_AE
E_TetheredMode_UsbImageToSDAndTetheredMode
E_VideoMode_FullZoom2K
E_VideoMode_ImageLiveview2K
HblmTypes::E_HwShareDeviceType
HblmTypes::E_HwShareStatus
HwshareProxy
HwshareProxyInterface
METADATA
TIMEOUT
_Z17qRegisterMetaTypeIN9HblmTypes15E_HwShareStatusEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_Z17qRegisterMetaTypeIN9HblmTypes19E_HwShareDeviceTypeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_ZN10ErrorProxy6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_ji
_ZN10ErrorProxy8doReportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_j
_ZN11CameraProxy24request_img_transfer_usbE5QListI4QMapI7QString8QVariantEEji
_ZN11CameraProxy26doRequest_img_transfer_usbE5QListI4QMapI7QString8QVariantEEj
_ZN11ConfigProxy15setDump_previewEb
_ZN11ConfigProxy20setShow_huawei_shareEb
_ZN11ConfigProxy20setWifi_power_storedEb
_ZN11ConfigProxy22setInterval_ae_enabledEb
_ZN11IpcMetadata13tagReturnViewEv
_ZN11IpcMetadata24tagFileSelectionMaxLimitEv
_ZN11IpcMetadata34tagHwshareTransferFailedImageCountEv
_ZN11IpcMetadata34tagHwshareTransferFailedVideoCountEv
_ZN11IpcMetadata35tagHwshareTransferSuccessImageCountEv
_ZN11IpcMetadata35tagHwshareTransferSuccessVideoCountEv
_ZN11IpcMetadatalsER13QDBusArgumentRKNS_17HwshareDeviceInfoE
_ZN11IpcMetadatarsERK13QDBusArgumentRNS_17HwshareDeviceInfoE
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN12HwshareProxy10doTransferERK7QString5QListI4QMapIS0_8QVariantEE
_ZN12HwshareProxy11qt_metacallEN11QMetaObject4CallEiPPv
_ZN12HwshareProxy11qt_metacastEPKc
_ZN12HwshareProxy16staticMetaObjectE
_ZN12HwshareProxy19onPropertiesChangedERK7QStringRK4QMapIS0_8QVariantE
_ZN12HwshareProxy4stopEi
_ZN12HwshareProxy5startEi
_ZN12HwshareProxy6doStopEv
_ZN12HwshareProxy7doStartEv
_ZN12HwshareProxy8transferERK7QString5QListI4QMapIS0_8QVariantEEi
_ZN12HwshareProxyC1EP7QObjectb
_ZN12HwshareProxyC2EP7QObjectb
_ZN12HwshareProxyD0Ev
_ZN12HwshareProxyD1Ev
_ZN12HwshareProxyD2Ev
_ZN13QDBusArgument12endStructureEv
_ZN13QDBusArgument14beginStructureEv
_ZN13QDBusArgumentlsEi
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE9ConstructEPvPKv
_ZN17WmsProxyInterface15bt_powerChangedEb
_ZN18LensProxyInterface20shutter_countChangedEi
_ZN18LensProxyInterface23distance_scale_0ChangedEj
_ZN18LensProxyInterface23distance_scale_1ChangedEj
_ZN18LensProxyInterface23distance_scale_2ChangedEj
_ZN20CameraProxyInterface23liveview_allowedChangedEb
_ZN20CameraProxyInterface37can_reprocess_raw_frame_bufferChangedEb
_ZN20ConfigProxyInterface19dump_previewChangedEb
_ZN20ConfigProxyInterface24show_huawei_shareChangedEb
_ZN20ConfigProxyInterface24wifi_power_storedChangedEb
_ZN20ConfigProxyInterface26interval_ae_enabledChangedEb
_ZN20PhocusProxyInterface17video_modeChangedEN9HblmTypes11E_VideoModeE
_ZN21HwshareProxyInterface11qt_metacallEN11QMetaObject4CallEiPPv
_ZN21HwshareProxyInterface11qt_metacastEPKc
_ZN21HwshareProxyInterface13statusChangedEN9HblmTypes15E_HwShareStatusE
_ZN21HwshareProxyInterface16availableChangedEb
_ZN21HwshareProxyInterface16staticMetaObjectE
_ZN21HwshareProxyInterface18can_suspendChangedEb
_ZN21HwshareProxyInterface18device_listChangedE4QMapI7QString8QVariantE
````

</details>

> 其余 128 条见 `result.json`。

### `/bin/camera`

<details><summary>新增 186 条字符串, 展示前 100 条</summary>

````text
-> added to pending.
-> replacing queue.
../../../helpers/messagequeue/messagequeue.cpp
18StreamMessageQueue
28BaseMessageQueueNotification
32InternalMessageQueueNotification
AF restore video mode
Already in requested state
BaseMessageQueueNotification
Camera is transferring image over usb, cannot start live view
CameraImpl::startRecording(const QDBusMessage&)::<lambda(HblmTypes::E_ReturnStatus)>::<lambda(HblmTypes::E_ReturnStatus)>::<lambda(HblmTypes::E_ReturnStatus)>
CameraStateFlag
E_StreamType
Error: Failed to turn off liveview, result:
Force clearing queue due to lens removal %1
Force clearing queued messages due to stop liveview due to not allowed
ForcedStopLiveviewReason
ForcedStopLiveviewReason_LensRemoved
ForcedStopLiveviewReason_NotAllowed
HblmTypes::E_StreamType
InSession
InternalMessageQueueNotification
Live view is not allowed
Liveview is not allowed
Liveview is not allowed and must be stopped
Liveview::State
MessageQueueNotification[0x%1]
Not allowed to enable liveview without lens.
Processing queued messages
QList<QVariantMap>
QPair(
QSharedPointer
QSharedPointer<InternalMessageQueueNotification>
QSharedPointer<MessageQueueNotification>
Recieved message from Storage -> doRequest_img_transfer_usb
Restore stream mode back to
Restoring showLiveViewWhenFinished to:
Running
Start liveview request finished, result:
Stop liveview due to af_debug_data_buffered disabled request finished, result:
Stop liveview due to camera body changed request finished, result:
Stop liveview due to lens removal request finished, result:
Stop liveview due to not allowed request finished, result:
Stop liveview due to preparing to expose request finished, result:
Stopping liveview due to not allowed
StreamCommon
StreamMode
StreamMode_AE
StreamMode_AF
StreamMode_FullZoom
StreamMode_ImageLiveview
StreamMode_Max
StreamMode_Off
StreamMode_Video
StreamMode_VideoLiveview
UsbTransfer
Will let the state machine flip video mode when finished to: %1
Will not change liveview mode to %1. State machine is running.
_Z17qRegisterMetaTypeIN9HblmTypes12E_StreamTypeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_ZGVZN9QtPrivate19ValueTypeIsMetaTypeI5QListI4QMapI7QString8QVariantEELb1EE17registerConverterEiE1f
_ZN11QMetaObject16invokeMethodImplEP7QObjectPN9QtPrivate15QSlotObjectBaseEN2Qt14ConnectionTypeEPv
_ZN11QMetaTypeIdI5QListI4QMapI7QString8QVariantEEE14qt_metatype_idEv
_ZN11QTextStreamC1EP7QString6QFlagsIN9QIODevice12OpenModeFlagEE
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN15QtSharedPointer20ExternalRefCountData9getAndRefEPK7QObject
_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE5equalEPKPvSB_
_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE6assignEPPvPKS9_
_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE7advanceEPPvi
_ZN17QtMetaTypePrivate19IteratorOwnerCommonIN5QListI4QMapI7QString8QVariantEE14const_iteratorEE7destroyEPPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperI5QListI4QMapI7QString8QVariantEELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperI5QListI4QMapI7QString8QVariantEELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_StreamTypeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes12E_StreamTypeELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QSequentialIterableImpl13moveToEndImplI5QListI4QMapI7QString8QVariantEEEEvPKvPPv
_ZN17QtMetaTypePrivate23QSequentialIterableImpl15moveToBeginImplI5QListI4QMapI7QString8QVariantEEEEvPKvPPv
_ZN17QtMetaTypePrivate23QSequentialIterableImpl6atImplI5QListI4QMapI7QString8QVariantEEEEPKvS9_i
_ZN17QtMetaTypePrivate23QSequentialIterableImpl7getImplI5QListI4QMapI7QString8QVariantEEEENS_11VariantDataEPKPvij
_ZN17QtMetaTypePrivate23QSequentialIterableImpl8sizeImplI5QListI4QMapI7QString8QVariantEEEEiPKv
_ZN18LensProxyInterface29has_micro_focus_adjustChangedEb
_ZN22ProfilesProxyInterface25resetting_profilesChangedEb
_ZN3Bus19isReturnStatusFatalEN9HblmTypes14E_ReturnStatusE
_ZN5QListI4QMapI7QString8QVariantEEC1ERKS4_
_ZN5QListI4QMapI7QString8QVariantEEC2ERKS4_
_ZN7QString18toLocal8Bit_helperEPK5QChari
_ZN9QListData6appendERKS_
_ZN9QtPrivate16ConverterFunctorI5QListI4QMapI7QString8QVariantEEN17QtMetaTypePrivate23QSequentialIterableImplENS7_33QSequentialIterableConvertFunctorIS6_EEE7convertEPKNS_25AbstractConverterFunctionEPKvPv
_ZN9QtPrivate16ConverterFunctorI5QListI4QMapI7QString8QVariantEEN17QtMetaTypePrivate23QSequentialIterableImplENS7_33QSequentialIterableConvertFunctorIS6_EEED1Ev
_ZN9QtPrivate16ConverterFunctorI5QListI4QMapI7QString8QVariantEEN17QtMetaTypePrivate23QSequentialIterableImplENS7_33QSequentialIterableConvertFunctorIS6_EEED2Ev
_ZN9QtPrivate16QStringList_joinEPK11QStringListPK5QChari
_ZNK12QMapNodeBase8nextNodeEv
_ZNK13QStateMachine13configurationEv
_ZNK7QString3argEyii5QChar
_ZNK9QMetaEnum10valueToKeyEi
_ZZN11QMetaTypeIdI5QListI4QMapI7QString8QVariantEEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes12E_StreamTypeEE14qt_metatype_idEvE11metatype_id
_ZZN9QtPrivate19ValueTypeIsMetaTypeI5QListI4QMapI7QString8QVariantEELb1EE17registerConverterEiE1f
_Zls6QDebugRK8QVariant
af_debug_data_buffered disabled
after stop recording set video mode
afterSession
````

</details>

> 其余 86 条见 `result.json`。

### `/bin/odindb-send`

<details><summary>新增 142 条字符串, 展示前 100 条</summary>

````text
  E_ErrorCode_HwShareTransferCancelled(88)
  E_ErrorCode_HwShareTransferComplete(91)
  E_ErrorCode_HwShareTransferFailed(89)
  E_ErrorCode_HwShareTransferPartialComplete(90)
  E_ErrorCode_HwShareTransferRejected(87)
  E_ErrorCode_LensPowerOffFailed(86)
  E_ErrorCode_MaxFileSelectionReached(92)
  E_StreamType_AE(5)
  E_StreamType_H264RTP(4)
  E_TetheredMode_UsbImageToSDAndTetheredMode(4)
  E_VideoMode_FullZoom2K(10)
  E_VideoMode_ImageLiveview2K(9)
19HwshareProxyWrapper
HblmTypes::E_HwShareDeviceType
HblmTypes::E_HwShareStatus
HwshareProxyWrapper
Monitor signals emitted from the service oneshot
No such method (%1) in service hwshare
QList<QVariantMap> transfer_filenames // Huawei Share transfer filenames
QString /* max length: 64 */ device_address // Huawei Share device address
QVariantMap error_metadata // 
_Z17qRegisterMetaTypeIN9HblmTypes15E_HwShareStatusEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_Z17qRegisterMetaTypeIN9HblmTypes19E_HwShareDeviceTypeEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_ZN10ErrorProxy6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_ji
_ZN10ErrorProxy8doReportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionE4QMapI7QString8QVariantERKS5_S9_j
_ZN11CameraProxy24request_img_transfer_usbE5QListI4QMapI7QString8QVariantEEji
_ZN11CameraProxy26doRequest_img_transfer_usbE5QListI4QMapI7QString8QVariantEEj
_ZN11ConfigProxy15setDump_previewEb
_ZN11ConfigProxy20setShow_huawei_shareEb
_ZN11ConfigProxy20setWifi_power_storedEb
_ZN11ConfigProxy22setInterval_ae_enabledEb
_ZN12HwshareProxy10doTransferERK7QString5QListI4QMapIS0_8QVariantEE
_ZN12HwshareProxy11qt_metacallEN11QMetaObject4CallEiPPv
_ZN12HwshareProxy11qt_metacastEPKc
_ZN12HwshareProxy16staticMetaObjectE
_ZN12HwshareProxy19onPropertiesChangedERK7QStringRK4QMapIS0_8QVariantE
_ZN12HwshareProxy4stopEi
_ZN12HwshareProxy5startEi
_ZN12HwshareProxy6doStopEv
_ZN12HwshareProxy7doStartEv
_ZN12HwshareProxy8transferERK7QString5QListI4QMapIS0_8QVariantEEi
_ZN12HwshareProxyC2EP7QObjectb
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_HwShareStatusELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_HwShareDeviceTypeELb1EE9ConstructEPvPKv
_ZN17WmsProxyInterface15bt_powerChangedEb
_ZN18LensProxyInterface20shutter_countChangedEi
_ZN18LensProxyInterface23distance_scale_0ChangedEj
_ZN18LensProxyInterface23distance_scale_1ChangedEj
_ZN18LensProxyInterface23distance_scale_2ChangedEj
_ZN20CameraProxyInterface23liveview_allowedChangedEb
_ZN20CameraProxyInterface37can_reprocess_raw_frame_bufferChangedEb
_ZN20ConfigProxyInterface19dump_previewChangedEb
_ZN20ConfigProxyInterface24show_huawei_shareChangedEb
_ZN20ConfigProxyInterface24wifi_power_storedChangedEb
_ZN20ConfigProxyInterface26interval_ae_enabledChangedEb
_ZN20PhocusProxyInterface17video_modeChangedEN9HblmTypes11E_VideoModeE
_ZN21HwshareProxyInterface13statusChangedEN9HblmTypes15E_HwShareStatusE
_ZN21HwshareProxyInterface16availableChangedEb
_ZN21HwshareProxyInterface16staticMetaObjectE
_ZN21HwshareProxyInterface18can_suspendChangedEb
_ZN21HwshareProxyInterface18device_listChangedE4QMapI7QString8QVariantE
_ZN21HwshareProxyInterface18device_nameChangedERK7QString
_ZN21HwshareProxyInterface18device_typeChangedEN9HblmTypes19E_HwShareDeviceTypeE
_ZN21HwshareProxyInterface24transfer_progressChangedEi
_ZN21HwshareProxyInterface6syncedEv
_ZN7AeProxy27do_reset_ael_after_exposureEi
_ZN7AeProxy29doDo_reset_ael_after_exposureEv
_ZN8WmsProxy10wifi_powerEbi
_ZN8WmsProxy12doWifi_powerEb
_ZNK11CameraProxy16liveview_allowedEv
_ZNK11CameraProxy30can_reprocess_raw_frame_bufferEv
_ZNK11ConfigProxy12dump_previewEv
_ZNK11ConfigProxy17show_huawei_shareEv
_ZNK11ConfigProxy17wifi_power_storedEv
_ZNK11ConfigProxy19interval_ae_enabledEv
_ZNK11PhocusProxy10video_modeEv
_ZNK12HwshareProxy11can_suspendEv
_ZNK12HwshareProxy11device_listEv
_ZNK12HwshareProxy11device_nameEv
_ZNK12HwshareProxy11device_typeEv
_ZNK12HwshareProxy11isAvailableEv
_ZNK12HwshareProxy17transfer_progressEv
_ZNK12HwshareProxy6statusEv
_ZNK12HwshareProxy8isSyncedEv
_ZNK8WmsProxy8bt_powerEv
_ZNK9LensProxy13shutter_countEv
_ZNK9LensProxy16distance_scale_0Ev
_ZNK9LensProxy16distance_scale_1Ev
_ZNK9LensProxy16distance_scale_2Ev
_ZTI12HwshareProxy
_ZTV12HwshareProxy
_ZTV21HwshareProxyInterface
_ZZN11QMetaTypeIdIN9HblmTypes15E_HwShareStatusEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes19E_HwShareDeviceTypeEE14qt_metatype_idEvE11metatype_id
bool wifi_power // 
bt_power = %1
bt_powerChanged
can_reprocess_raw_frame_buffer = %1
````

</details>

> 其余 42 条见 `result.json`。

### `/bin/dji_wms`

<details><summary>新增 93 条字符串</summary>

````text
, result:
-> added to pending.
-> added to queue.
../../../helpers/messagequeue/messagequeue.cpp
12MessageQueue
22WifiToggleMessageQueue
24MessageQueueNotification
28BaseMessageQueueNotification
32InternalMessageQueueNotification
Already in requested state
Already powering up
BaseMessageQueueNotification
E_ReturnStatus
Failed to set result, destroying notification
Fix power status, tethered lost
HblmTypes::E_ReturnStatus
InternalMessageQueueNotification
MessageQueue
MessageQueueNotification
MessageQueueNotification[0x%1]
PowerStatus
PowerStatus_Off
PowerStatus_On
PowerStatus_Powering
Powering up
Processing queued messages
QPair(
WifiHandlerInterface::PowerStatus
WifiToggleMessageQueue
_ZN10QByteArray11reallocDataEj6QFlagsIN10QArrayData16AllocationOptionEE
_ZN10QByteArray6appendEPKc
_ZN10QByteArray6appendEc
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN12QDBusMessageC1ERKS_
_ZN12QMapDataBase10createDataEv
_ZN12QMapDataBase10createNodeEiiP12QMapNodeBaseb
_ZN12QMapDataBase11shared_nullE
_ZN12QMapDataBase18recalcMostLeftNodeEv
_ZN12QMapDataBase20freeNodeAndRebalanceEP12QMapNodeBase
_ZN12QMapDataBase8freeDataEPS_
_ZN12QMapDataBase8freeTreeEP12QMapNodeBasei
_ZN15QtSharedPointer20ExternalRefCountData16setQObjectSharedEPK7QObjectb
_ZN16QCoreApplication13processEventsE6QFlagsIN10QEventLoop17ProcessEventsFlagEE
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE9ConstructEPvPKv
_ZN3Bus20createSendErrorReplyERK12QDBusMessageRK7QStringN9HblmTypes14E_ReturnStatusE
_ZN6QDebuglsEPKc
_ZN6QTimer14singleShotImplEiN2Qt9TimerTypeEPK7QObjectPN9QtPrivate15QSlotObjectBaseE
_ZN7QString18toLocal8Bit_helperEPK5QChari
_ZN8QMapDataI7QString8QVariantE7destroyEv
_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv
_ZN8QVariantC1ERKS_
_ZN9QListData5eraseEPPv
_ZN9QListData6appendERKS_
_ZN9QListData6detachEi
_ZN9QtPrivate16QStringList_joinEPK11QStringListPK5QChari
_ZNK11QMetaObject9classNameEv
_ZNK12QMapNodeBase8nextNodeEv
_ZNK14QMessageLogger4infoEv
_ZNK7QString3argERKS_i5QChar
_ZNK7QString3argExii5QChar
_ZNK7QString3argEyii5QChar
_ZNK8QMapNodeI7QString8QVariantE4copyEP8QMapDataIS0_S1_E
_ZZN11QMetaTypeIdIN9HblmTypes14E_ReturnStatusEE14qt_metatype_idEvE11metatype_id
_Zls6QDebugRK8QVariant
_setWifiPower
bt_power
bt_powerChanged
callSetWifiPower
changed
close wifi timer (off)
close wifi timer (on)
destructor
doWifi_power
enable:
finished
powerStatusChanged
queued messages was obsolete
restart wifi (off)
restart wifi (on)
result:
setPowerStatus
setResult
start internal request
start request
user wifi power request finished, power %1
user wifi power request power %1
virtual void WmsObjectImpl::doWifi_power(bool, const QDBusMessage&)
wait join wifi
wifi power:
wifi region change
wms_wifi_start failed with ret: %1
wms_wifi_stop failed with ret: %1
````

</details>

### `/bin/dji_wms-v1`

<details><summary>新增 93 条字符串</summary>

````text
, result:
-> added to pending.
-> added to queue.
../../../helpers/messagequeue/messagequeue.cpp
12MessageQueue
22WifiToggleMessageQueue
24MessageQueueNotification
28BaseMessageQueueNotification
32InternalMessageQueueNotification
Already in requested state
Already powering up
BaseMessageQueueNotification
E_ReturnStatus
Failed to set result, destroying notification
Fix power status, tethered lost
HblmTypes::E_ReturnStatus
InternalMessageQueueNotification
MessageQueue
MessageQueueNotification
MessageQueueNotification[0x%1]
PowerStatus
PowerStatus_Off
PowerStatus_On
PowerStatus_Powering
Powering up
Processing queued messages
QPair(
WifiHandlerInterface::PowerStatus
WifiToggleMessageQueue
_ZN10QByteArray11reallocDataEj6QFlagsIN10QArrayData16AllocationOptionEE
_ZN10QByteArray6appendEPKc
_ZN10QByteArray6appendEc
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN12QDBusMessageC1ERKS_
_ZN12QMapDataBase10createDataEv
_ZN12QMapDataBase10createNodeEiiP12QMapNodeBaseb
_ZN12QMapDataBase11shared_nullE
_ZN12QMapDataBase18recalcMostLeftNodeEv
_ZN12QMapDataBase20freeNodeAndRebalanceEP12QMapNodeBase
_ZN12QMapDataBase8freeDataEPS_
_ZN12QMapDataBase8freeTreeEP12QMapNodeBasei
_ZN15QtSharedPointer20ExternalRefCountData16setQObjectSharedEPK7QObjectb
_ZN16QCoreApplication13processEventsE6QFlagsIN10QEventLoop17ProcessEventsFlagEE
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE9ConstructEPvPKv
_ZN3Bus20createSendErrorReplyERK12QDBusMessageRK7QStringN9HblmTypes14E_ReturnStatusE
_ZN6QDebuglsEPKc
_ZN6QTimer14singleShotImplEiN2Qt9TimerTypeEPK7QObjectPN9QtPrivate15QSlotObjectBaseE
_ZN7QString18toLocal8Bit_helperEPK5QChari
_ZN8QMapDataI7QString8QVariantE7destroyEv
_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv
_ZN8QVariantC1ERKS_
_ZN9QListData5eraseEPPv
_ZN9QListData6appendERKS_
_ZN9QListData6detachEi
_ZN9QtPrivate16QStringList_joinEPK11QStringListPK5QChari
_ZNK11QMetaObject9classNameEv
_ZNK12QMapNodeBase8nextNodeEv
_ZNK14QMessageLogger4infoEv
_ZNK7QString3argERKS_i5QChar
_ZNK7QString3argExii5QChar
_ZNK7QString3argEyii5QChar
_ZNK8QMapNodeI7QString8QVariantE4copyEP8QMapDataIS0_S1_E
_ZZN11QMetaTypeIdIN9HblmTypes14E_ReturnStatusEE14qt_metatype_idEvE11metatype_id
_Zls6QDebugRK8QVariant
_setWifiPower
bt_power
bt_powerChanged
callSetWifiPower
changed
close wifi timer (off)
close wifi timer (on)
destructor
doWifi_power
enable:
finished
powerStatusChanged
queued messages was obsolete
restart wifi (off)
restart wifi (on)
result:
setPowerStatus
setResult
start internal request
start request
user wifi power request finished, power %1
user wifi power request power %1
virtual void WmsObjectImpl::doWifi_power(bool, const QDBusMessage&)
wait join wifi
wifi power:
wifi region change
wms_wifi_start failed with ret: %1
wms_wifi_stop failed with ret: %1
````

</details>

### `/etc/firmware/rtnodes/app.elf`

<details><summary>新增 45 条字符串</summary>

````text
                0000000000000000H
10.00.23.14-8aac72e
10.00.23.14-dc95da4
21:16:35
FullZoom2K
ImageLiveview2K
Oct 21 2020
[%s] %s%s() Ga: %f, EV: %f, active_AV: %f, breakp: %f, maxExpTime: %lu
[%s] %s%sLum | ExpMode: %d FrameId: %d/%d Luma: %5d LLa: %7.4f LL12: %3d Sensor: %lums/%d %s
ae_do_reset_ael_after_exposure_req
ae_do_reset_ael_after_exposure_resp
bt_power
can_reprocess_raw_frame_buffer
config_changed_focus_bracketing_number_of_frames
config_changed_focus_bracketing_strategy
config_changed_unit_of_distance
config_set_focus_bracketing_number_of_frames_req
config_set_focus_bracketing_number_of_frames_resp
config_set_focus_bracketing_strategy_req
config_set_focus_bracketing_strategy_resp
config_set_unit_of_distance_req
config_set_unit_of_distance_resp
dc95da4
device_list
device_name
device_type
distance_scale_0
distance_scale_1
distance_scale_2
dump_preview
image_fullzoom_2k
image_liveview_2k
interval_ae_enabled
lens_changed_distance_scale_0
lens_changed_distance_scale_1
lens_changed_distance_scale_2
lens_changed_shutter_count
liveview_allowed
show_huawei_share
shutter_count
suc_changed_sys_state
sys_state
transfer_progress
video_mode
wifi_power_stored
````

</details>

### `/bin/storage`

<details><summary>新增 43 条字符串</summary>

````text
13ReprocessTask
16ControllableTaskIbE
16QFutureInterfaceIbE
16QFutureInterfaceIvE
19RunControllableTaskIbE
Cache::onRequestReprocessRaw(const QSharedPointer<ImageMemory>&)::<lambda(const QString&, HblmTypes::E_ReturnStatus, const QString&)>
Cancelling...
ControllableTask<bool>
HblmTypes::E_ReturnStatus
N12QtConcurrent15RunFunctionTaskIvEE
N12QtConcurrent18StoredFunctorCall2IvPFvRK14QSharedPointerI11ImageMemoryERK7QStringES3_S6_EE
N12QtConcurrent19RunFunctionTaskBaseIvEE
Reprocess task finished
Reprocess task running
Reprocess task waiting
ReprocessTask
Unreference raw image memory:
_ZN11QThreadPool14globalInstanceEv
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN14QWaitCondition4waitEP6QMutexm
_ZN14QWaitCondition7wakeAllEv
_ZN14QWaitConditionC1Ev
_ZN14QWaitConditionD1Ev
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_ReturnStatusELb1EE9ConstructEPvPKv
_ZN20CameraProxyInterface37can_reprocess_raw_frame_bufferChangedEb
_ZN20QFutureInterfaceBase6cancelEv
_ZN20QFutureInterfaceBaseC1ERKS_
_ZN20QFutureInterfaceBaseD1Ev
_ZNK20QFutureInterfaceBase9isRunningEv
_ZNK7QString5rightEi
_ZZN11QMetaTypeIdIN9HblmTypes14E_ReturnStatusEE14qt_metatype_idEvE11metatype_id
errorMsg
image:
imagePath
ionHandle
reprocess
reprocess raw_frame buffer
reprocess raw_frame buffer finished
reprocessError
start task:
to usb
~ReprocessTask
````

</details>

### `/bin/msg2dbus`

<details><summary>新增 31 条字符串</summary>

````text
HblmTypes::E_DistanceUnit
HblmTypes::E_FocusBracketingStrategies
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_DistanceUnitELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes14E_DistanceUnitELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes27E_FocusBracketingStrategiesELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes27E_FocusBracketingStrategiesELb1EE9ConstructEPvPKv
_ZN20ConfigProxyInterface23unit_of_distanceChangedEN9HblmTypes14E_DistanceUnitE
_ZN20ConfigProxyInterface32focus_bracketing_strategyChangedEN9HblmTypes27E_FocusBracketingStrategiesE
_ZN20ConfigProxyInterface40focus_bracketing_number_of_framesChangedEi
_ZZN11QMetaTypeIdIN9HblmTypes14E_DistanceUnitEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes27E_FocusBracketingStrategiesEE14qt_metatype_idEvE11metatype_id
distance_scale_0
distance_scale_0Changed
distance_scale_1
distance_scale_1Changed
distance_scale_2
distance_scale_2Changed
doDo_reset_ael_after_exposure
do_reset_ael_after_exposure
focus_bracketing_number_of_frames
focus_bracketing_strategy
onFocus_bracketing_number_of_framesChanged
onFocus_bracketing_strategyChanged
onSet_focus_bracketing_number_of_framesFinished
onSet_focus_bracketing_strategyFinished
onSet_unit_of_distanceFinished
onUnit_of_distanceChanged
shutter_count
shutter_countChanged
unit_of_distance
````

</details>

### `/lib/libAppsMessaging.so`

````text
ae_do_reset_ael_after_exposure_req
ae_do_reset_ael_after_exposure_resp
config_changed_focus_bracketing_number_of_frames
config_changed_focus_bracketing_strategy
config_changed_unit_of_distance
config_set_focus_bracketing_number_of_frames_req
config_set_focus_bracketing_number_of_frames_resp
config_set_focus_bracketing_strategy_req
config_set_focus_bracketing_strategy_resp
config_set_unit_of_distance_req
config_set_unit_of_distance_resp
dc95da4
lens_changed_distance_scale_0
lens_changed_distance_scale_1
lens_changed_distance_scale_2
lens_changed_shutter_count
suc_changed_sys_state
````

### `/bin/configstore`

````text
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN8QMapDataI7QString8QVariantE7destroyEv
_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv
dump_preview
dump_preview_maxval
dump_preview_minval
interval_ae_enabled
interval_ae_enabled_maxval
interval_ae_enabled_minval
show_huawei_share
show_huawei_share_maxval
show_huawei_share_minval
wifi_power_stored
wifi_power_stored_maxval
wifi_power_stored_minval
````

### `/bin/sysman`

````text
NSt3__110__function6__funcINS_6__bindIM21HwshareProxyInterfaceKFbvEJPS3_EEENS_9allocatorIS7_EEFbvEEE
NSt3__114unary_functionIPK21HwshareProxyInterfacebEE
NSt3__118__weak_result_typeIM21HwshareProxyInterfaceKFbvEEE
NSt3__16__bindIM21HwshareProxyInterfaceKFbvEJPS1_EEE
SUC prepare shutdown failed
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN12HwshareProxyC1EP7QObjectb
_ZN20ConfigProxyInterface24show_huawei_shareChangedEb
_ZN21HwshareProxyInterface16staticMetaObjectE
_ZN21HwshareProxyInterface18can_suspendChangedEb
_ZN6CErrorC1EN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantEi
dji.hwshare_service
error_metadata
hwshare
````

### `/bin/camservice`

````text
E_StreamType
Recording already running
_ZN20ConfigProxyInterface19dump_previewChangedEb
_ZN21StorageProxyInterface16staticMetaObjectE
_ZN21StorageProxyInterface18save_folderChangedERK7QString
dumpPreview
onDumpPreviewChanged
onSaveFolderChanged
saveFolder
streamtype
````

### `/lib/libdcam_frwk.so`

````text
%s/uid%d_frame%04d_%dx%d.%s
BYR2_watermark_generate
CAPENG_X1DM2_CAP: dump frame to file:%s, result:%d 
CamCapEng: send_and_wait(CAPENG_MSG_SET_CAPTURE_DUMP_PATH) failed:%d 
cam_cap_eng_set_capture_dump_path
capeng_x1dm2_dump_captured_frame_on_demand
res_2756x2064_fps_30
usbd_enqueue_buffer
````

### `/bin/gpsd`

````text
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN12QMapDataBase11shared_nullE
_ZN12QMapDataBase8freeDataEPS_
_ZN12QMapDataBase8freeTreeEP12QMapNodeBasei
_ZN8QMapDataI7QString8QVariantE7destroyEv
_ZN8QMapNodeI7QString8QVariantE14destroySubTreeEv
````

### `/lib/libservice.so`

````text
_ZN3dji6camera13CameraService13setSaveFolderERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE
_ZN3dji6camera13CameraService14setDumpPreviewEb
_ZThn4_N3dji6camera13CameraService13setSaveFolderERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE
_ZThn4_N3dji6camera13CameraService14setDumpPreviewEb
cam_cap_eng_set_capture_dump_path
onFrame: Skipping first frame.. size: %dx%d
````

### `/bin/dji_cht`

````text
_on_free_buffer_count_changed
dbus_message_append_args
dbus_message_get_args
on_free_buffer_count_changed: %d
````

### `/lib/libduml_frwk.so`

````text
21:25:02
21:25:03
Oct 21 2020
b41ed181dfee6485b5718c88d97e8e0cdb3cb9e068538629c8f1bddae68be633
````

### `/bin/bodystate`

````text
_ZN12ErrorProxyIf6reportEN9HblmTypes11E_ErrorCodeENS0_15E_ErrorCategoryENS0_13E_ErrorActionERK4QMapI7QString8QVariantERKS5_SB_j
_ZN4QMapI7QString8QVariantED1Ev
_ZN4QMapI7QString8QVariantED2Ev
````

### `/bin/dji_sys`

````text
21:26:14
21:26:15
Oct 21 2020
````

### `/lib/weston/eagle-backend.so`

````text
Vecx337aa_power_ctrl
ili2120_init_touch
jdi_open
````

### `/bin/analytics`

````text
_ZN4QMapI7QString8QVariantED1Ev
_ZN4QMapI7QString8QVariantED2Ev
````

### `/bin/dji_amt`

````text
21:26:03
Oct 21 2020
````

### `/bin/dji_blackbox`

````text
21:26:03
Oct 21 2020
````

### `/bin/vdec_test`

````text
21:53:26
Oct 21 2020
````

### `/bin/vxe_testbench`

````text
21:53:13
Oct 21 2020
````

### `/lib/libLLVM.so`

````text
21:29:15
Oct 21 2020
````

### `/lib/libhelper_api_sa.so`

````text
21:51:36
Oct 21 2020
````

### `/lib/libomx_vxd.so`

````text
21:53:26
Oct 21 2020
````

### `/bin/debuggerd`

````text
debuggerd: Oct 21 2020 21:26:00
````

### `/bin/sutest`

````text
_ZN8WmsProxyC1EP7QObjectb
````

### `/lib/libduml_hal_cam.so`

````text
TPLG_EC1704_STILL_LIVEVIEW_2064
````

### `/lib/libmod_x1dm2.so`

````text
TPLG_EC1704_STILL_LIVEVIEW_2064
````

### `/lib/modules/rcam_dji.ko`

````text
MODE_2756_2064_377P_RAW12
````

### `/bin/audio`

````text
````

### `/bin/dji_cspp`

````text
````

### `/bin/dji_rcam`

````text
````

### `/bin/hex-writer`

````text
````

### `/bin/metadata`

````text
````

### `/bin/msg2dbus-test`

````text
````

### `/bin/preview`

````text
````

### `/bin/prodconfig-tool`

````text
````

### `/bin/upgrade_fw`

````text
````

### `/bin/upgraded`

````text
````

### `/bin/usbd`

````text
````

### `/etc/firmware/rtnodes/cfv-control.elf`

````text
````

### `/etc/firmware/rtnodes/power-control.elf`

````text
````

### `/etc/firmware/rtnodes/xsystem-control.elf`

````text
````

### `/lib/libMessageTransport.so`

````text
````

## Scripts & Config

共 7 个脚本/配置变更, 146 行 unified diff（context=3, 预算上限 2000 行）。

### `/bin/start_blackbox_logs.sh`

27 行

````diff
--- a//bin/start_blackbox_logs.sh
+++ b//bin/start_blackbox_logs.sh
@@ -17,7 +17,7 @@
 logcat -v time -f /blackbox/system/fatal.log -r32768 -n2 *:E &
 
 # for ec1704 upgraded log, up to 2MB
-logcat -v time -f /blackbox/system/cim_upgrade.log -r2048 -n6 upgraded:D victory-gui:D *:S &
+logcat -v time -f /blackbox/system/cim_upgrade.log -r2048 -n6 upgraded:D victory-gui-static:D *:S &
 logcat -v threadtime -f /blackbox/system/dji_upgrade.log -r2048 -n6 DUSS63:I *:S &
 
 # do kmsg collection
@@ -33,6 +33,7 @@
 logcat -f /blackbox/camera/log/cam.log -r16384 -n6 \
                                           DUSS46:I \
                                           DUSS51:I \
+                                          DUSS52:I \
                                           DUSS58:I \
                                           DUSS5C:F \
                                           hostapd:I \
@@ -50,6 +51,7 @@
                                           sutest:D \
                                           sysman:D \
                                           upgraded:D \
+                                          hwshare:D \
                                           victory-gui-static:D \
                                           weston:D \
                                           odindb-send:D \
````

### `/bin/start_dji_system.sh`

9 行

````diff
--- a//bin/start_dji_system.sh
+++ b//bin/start_dji_system.sh
@@ -150,3 +150,6 @@
         done
     fi
 fi
+
+# Helper for syncing kmsg.log to cam.log
+busybox date -I'seconds' > /dev/kmsg
````

### `/bin/test_eagle_fpga_mipi_link.sh`

68 行

````diff
--- a//bin/test_eagle_fpga_mipi_link.sh
+++ b//bin/test_eagle_fpga_mipi_link.sh
@@ -7,6 +7,13 @@
 #!/bin/bash
 prepare()
 {
+	# Use e-shutter to avoid any lens dependencies
+	odindb-send -s camera -p eshutter_current true
+	if [ $? != 0 ]; then
+		echo "Enable e-shutter failed"
+		return 3
+	fi
+
 	#stop gui
 	setprop ctl.stop gui
 	if [ $? != 0 ]; then
@@ -14,19 +21,27 @@
 		return 1
 	fi
 
-	#stop dji_camera2
+	#stop camera daemon
+	setprop ctl.stop camera_daemon
+	if [ $? != 0 ]; then
+		echo "stop camera_daemon fail"
+		return 2
+	fi
+
+	#stop storage daemon
+	setprop ctl.stop storage_daemon
+	if [ $? != 0 ]; then
+		echo "stop storage_daemon fail"
+		return 2
+	fi
+
+	#stop dji_camera2 (camera service)
 	setprop ctl.stop dji_camera2
 	if [ $? != 0 ]; then
 		echo "stop dji_camera2 fail"
 		return 2
 	fi
 
-	# Use e-shutter to avoid any lens dependencies
-	odindb-send -s camera -p eshutter_current true
-	if [ $? != 0 ]; then
-		echo "Enable e-shutter failed"
-		return 3
-	fi
 }
 
 restore()
@@ -35,6 +50,16 @@
 	if [ $? != 0 ]; then
 		echo "start dji_camera2 fail"
 		return 3
+	fi
+	setprop ctl.start storage_daemon
+	if [ $? != 0 ]; then
+		echo "start storage_daemon fail"
+		return 4
+	fi
+	setprop ctl.start camera_daemon
+	if [ $? != 0 ]; then
+		echo "start camera_daemon fail"
+		return 4
 	fi
 	setprop ctl.start gui
 	if [ $? != 0 ]; then
````

### `/bin/upgrade_gl3227.sh`

11 行

````diff
--- a//bin/upgrade_gl3227.sh
+++ b//bin/upgrade_gl3227.sh
@@ -11,7 +11,7 @@
 #       V1.0 2018/10 Original version Philip.Liu
 #       V1.1 2020/04 Check version on both controllers
 #
-VERSION=31363035
+VERSION=30303033
 echo 1 > /sys/bus/platform/drivers/sd_reset/f0a00000.apb:sd_reset/phypwr
 echo "waiting for adding hcd ..."
 sleep 10
````

### `/build.prop`

10 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,4 +1,4 @@
 
-ro.vendor.build.date=Wed Jul 15 00:04:09 CST 2020
-ro.vendor.build.date.utc=1594742649
-ro.vendor.build.fingerprint=eagle/full_eagle_ec1704/eagle_ec1704:6.0/MDB08M/1786:userdebug/test-keys
+ro.vendor.build.date=Wed Oct 21 21:54:03 CST 2020
+ro.vendor.build.date.utc=1603288443
+ro.vendor.build.fingerprint=eagle/full_eagle_ec1704/eagle_ec1704:6.0/MDB08M/1925:userdebug/test-keys
````

### `/etc/dji_camera.conf`

10 行

````diff
--- a//etc/dji_camera.conf
+++ b//etc/dji_camera.conf
@@ -71,6 +71,7 @@
     res_2720x1530_fps_30       = 20000000, 35000000, 100000000
     res_1920x1080_fps_30       = 12000000, 25000000, 50000000
     res_2756x1240_fps_30       = 5000000,  15000000, 50000000
+    res_2756x2064_fps_30       = 5000000,  15000000, 50000000
 
 [hiso:ceva]
     #option: always_yuv, always_y, always_uv, disable, auto
````

### `/etc/firmware/wlan/qcom_cfg.ini`

11 行

````diff
--- a//etc/firmware/wlan/qcom_cfg.ini
+++ b//etc/firmware/wlan/qcom_cfg.ini
@@ -445,7 +445,7 @@
 gNumChanCombinedConc=60
 
 #Enable Power Save offload
-gEnablePowerSaveOffload=0
+gEnablePowerSaveOffload=1
 
 #Enable firmware uart print
 gEnablefwprint=0
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（906 行）</summary>

| Path | Status | Old Size | New Size | Δ | Tree |
|---|---|---|---|---|---|
| `/bin/Btdiag` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54.2 KB | 54.2 KB | +0 B | system |
| `/bin/adb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 419.6 KB | 419.6 KB | +0 B | system |
| `/bin/af.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 296 B | 296 B | +0 B | system |
| `/bin/aging_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.5 KB | 27.5 KB | +0 B | system |
| `/bin/amt_test_cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/analytics` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.6 KB | 81.6 KB | +0 B | system |
| `/bin/atrace` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.7 KB | 29.7 KB | +0 B | system |
| `/bin/audio` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.6 KB | 61.6 KB | +0 B | system |
| `/bin/blkid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/bodystate` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 213.7 KB | 217.7 KB | +4.0 KB | system |
| `/bin/boot_control` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 182.0 KB | 182.0 KB | +0 B | system |
| `/bin/bootlogo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 146.0 KB | 146.0 KB | +0 B | system |
| `/bin/brdver_ddrtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_hwrev.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_prodtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 386 B | 386 B | +0 B | system |
| `/bin/btconfig` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74.6 KB | 74.6 KB | +0 B | system |
| `/bin/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.7 KB | 6.7 KB | +0 B | system |
| `/bin/c2d_ut` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.7 KB | 33.7 KB | +0 B | system |
| `/bin/cam_log_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/camera` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 605.6 KB | 661.6 KB | +56.1 KB | system |
| `/bin/camera_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/camservice` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +4.9 KB | system |
| `/bin/capture-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 153 B | 153 B | +0 B | system |
| `/bin/capture.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 363 B | 363 B | +0 B | system |
| `/bin/charge_interrupt_test_module.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 943 B | 943 B | +0 B | system |
| `/bin/check_blackbox.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 580 B | 580 B | +0 B | system |
| `/bin/check_sdcard_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 515 B | 515 B | +0 B | system |
| `/bin/check_system_status.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 706 B | 706 B | +0 B | system |
| `/bin/collect_useful_log.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | system |
| `/bin/comp_build_version.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525 B | 525 B | +0 B | system |
| `/bin/configstore` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 281.6 KB | 293.6 KB | +12.0 KB | system |
| `/bin/coremark` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/cs47l35-dmic-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 363 B | 363 B | +0 B | system |
| `/bin/cs47l35-hpout-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93 B | 93 B | +0 B | system |
| `/bin/cs47l35-mic-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 111 B | 111 B | +0 B | system |
| `/bin/cs47l35-spk-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 76 B | 76 B | +0 B | system |
| `/bin/cs_check_system_state.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | system |
| `/bin/dbus-daemon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 157.7 KB | 157.7 KB | +0 B | system |
| `/bin/dbus-send` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/dbus-watcher` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/debuggerd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/dhcpcd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.7 KB | 73.7 KB | +0 B | system |
| `/bin/dhcptool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_amt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.2 KB | 39.2 KB | +0 B | system |
| `/bin/dji_bb_spliter` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_blackbox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 35.0 KB | 35.0 KB | +0 B | system |
| `/bin/dji_cam_f2f.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.0 KB | 7.0 KB | +0 B | system |
| `/bin/dji_cht` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 95.7 KB | 95.7 KB | +8 B | system |
| `/bin/dji_close_suspend_powerdown.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 585 B | 585 B | +0 B | system |
| `/bin/dji_codec_aging.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/dji_crashdump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | system |
| `/bin/dji_cspp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 57.8 KB | 57.8 KB | +0 B | system |
| `/bin/dji_dsp_load` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | system |
| `/bin/dji_ec1704_camera_aging_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.5 KB | 13.5 KB | +0 B | system |
| `/bin/dji_ftpd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38.1 KB | 38.1 KB | +0 B | system |
| `/bin/dji_fw_load` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_fw_verify` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_gdc_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/dji_iosconn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.7 KB | 37.7 KB | +0 B | system |
| `/bin/dji_kmsg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_log_encrypt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.9 KB | 21.9 KB | +0 B | system |
| `/bin/dji_mb_ctrl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_mb_parser` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/dji_monitor` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_open_suspend_powerdown.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 583 B | 583 B | +0 B | system |
| `/bin/dji_pbt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.7 KB | 41.7 KB | +0 B | system |
| `/bin/dji_ppt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 207.0 KB | 207.0 KB | +0 B | system |
| `/bin/dji_quick_charge` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_rcam` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/dji_setup_uart.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 355 B | 355 B | +0 B | system |
| `/bin/dji_sn_ops.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 479 B | 479 B | +0 B | system |
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 376.6 KB | 376.6 KB | +0 B | system |
| `/bin/dji_system_complete.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/dji_tombstone.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/dji_verify` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.4 KB | 29.4 KB | +0 B | system |
| `/bin/dji_vtwo_sdk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/dji_wms` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 228.6 KB | 308.6 KB | +80.0 KB | system |
| `/bin/dji_wms-v1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 144.6 KB | 220.6 KB | +76.0 KB | system |
| `/bin/dumpstate` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.6 KB | 53.6 KB | +0 B | system |
| `/bin/dvfs-capture-freq.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 479 B | 479 B | +0 B | system |
| `/bin/dvfs-userspace-random.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/dvfs-userspace-switch.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/e2fsck` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.2 KB | 159.2 KB | +0 B | system |
| `/bin/eagle_ddr_stress_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/eagle_rpmb_inject.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45 B | 45 B | +0 B | system |
| `/bin/eagle_state_pro.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,003 B | 1,003 B | +0 B | system |
| `/bin/ec1702_configure_touch.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/eeprom_rw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/encrypt_and_export_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/erase_bootloader.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 151.2 KB | 151.2 KB | +0 B | system |
| `/bin/exposure_test_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/bin/fixup_hbmanual_partition.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/flash_erase` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.0 KB | 198.0 KB | +0 B | system |
| `/bin/fpga_ddr_stress_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/frame_cap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.7 KB | 25.7 KB | +0 B | system |
| `/bin/gdbserver` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 388.4 KB | 388.4 KB | +0 B | system |
| `/bin/get_tps65961_ch11.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/gimbal_log.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 553 B | 553 B | +0 B | system |
| `/bin/gl_check_01.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 587 B | 587 B | +0 B | system |
| `/bin/gl_check_version.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 531 B | 531 B | +0 B | system |
| `/bin/gl_flash` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.9 KB | 29.9 KB | +0 B | system |
| `/bin/gl_flash.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | system |
| `/bin/gl_inquiry` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.0 KB | 27.0 KB | +0 B | system |
| `/bin/gl_inquiry0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.0 KB | 27.0 KB | +0 B | system |
| `/bin/gl_inquiry1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.0 KB | 27.0 KB | +0 B | system |
| `/bin/gl_speed` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.0 KB | 28.0 KB | +0 B | system |
| `/bin/gpsd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.6 KB | 61.6 KB | +12.0 KB | system |
| `/bin/gzip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/hard_restart.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 98 B | 98 B | +0 B | system |
| `/bin/hbl-collect-logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/hbl-configure-audio-sink.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/hbl-configure-audio-source.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/hciattach` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 63.0 KB | 63.0 KB | +0 B | system |
| `/bin/hex-writer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.6 KB | 53.6 KB | +0 B | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 535.3 KB | 535.3 KB | +0 B | system |
| `/bin/hostapd_cli` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.7 KB | 49.7 KB | +0 B | system |
| `/bin/hwshare` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 153.6 KB | +153.6 KB | system |
| `/bin/i2cget` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.3 KB | 13.3 KB | +0 B | system |
| `/bin/i2cset` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.3 KB | 13.3 KB | +0 B | system |
| `/bin/imgjpegenc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/insert_tp_mod.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 817 B | 817 B | +0 B | system |
| `/bin/insmod_ko.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 193 B | 193 B | +0 B | system |
| `/bin/ion_falloc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/iozone` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 290.9 KB | 290.9 KB | +0 B | system |
| `/bin/ip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 169.9 KB | 169.9 KB | +0 B | system |
| `/bin/iperf3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.3 KB | 70.3 KB | +0 B | system |
| `/bin/iw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 157.1 KB | 157.1 KB | +0 B | system |
| `/bin/keystore_cli` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/lib_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.8 KB | 7.8 KB | +0 B | system |
| `/bin/lib_test_cases.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.5 KB | 8.5 KB | +0 B | system |
| `/bin/lib_test_stress.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/lib_test_utils.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/linker` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 184.5 KB | 184.5 KB | +0 B | system |
| `/bin/logcat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/logd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.7 KB | 49.7 KB | +0 B | system |
| `/bin/logpersist.start` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 898 B | 898 B | +0 B | system |
| `/bin/logwrapper` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/lv_dump_disable.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/lv_dump_enable.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/metadata` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.6 KB | 81.6 KB | +0 B | system |
| `/bin/mkexfat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.3 KB | 27.3 KB | +0 B | system |
| `/bin/mmc_utils` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.8 KB | 29.8 KB | +0 B | system |
| `/bin/monkey_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 669.6 KB | 681.6 KB | +12.0 KB | system |
| `/bin/msg2dbus-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/mxt-app` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.5 KB | 82.5 KB | +0 B | system |
| `/bin/myftm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 87.2 KB | 87.2 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/odindb-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +52.0 KB | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 915.2 KB | 915.2 KB | +0 B | system |
| `/bin/periodic_sync.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59 B | 59 B | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 745.7 KB | 1,021.7 KB | +276.0 KB | system |
| `/bin/pl_spi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/play-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165 B | 165 B | +0 B | system |
| `/bin/play-hdmi.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165 B | 165 B | +0 B | system |
| `/bin/playcap-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 242 B | 242 B | +0 B | system |
| `/bin/pngtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/preview` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 281.9 KB | 281.9 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.6 KB | 125.6 KB | +0 B | system |
| `/bin/prodconfig-tool.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | system |
| `/bin/productiontest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/bin/program_nodes.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/proresenc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/qcmbr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.9 KB | 29.9 KB | +0 B | system |
| `/bin/r` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/rcam_agent` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.0 KB | 22.0 KB | +0 B | system |
| `/bin/reboot` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/recovery_update.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | system |
| `/bin/returnstatus_defines.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 739 B | 739 B | +0 B | system |
| `/bin/returnstatus_suc_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 614 B | 614 B | +0 B | system |
| `/bin/returnstatus_to_string.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 987 B | 987 B | +0 B | system |
| `/bin/sd_helpers.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/send_fw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/servicemanager` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | system |
| `/bin/set_sd_autosuspend.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 869 B | 869 B | +0 B | system |
| `/bin/set_test_result.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237 B | 237 B | +0 B | system |
| `/bin/setup_aging_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 723 B | 723 B | +0 B | system |
| `/bin/setup_cam_env.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 319 B | 319 B | +0 B | system |
| `/bin/setup_factory_rw.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 578 B | 578 B | +0 B | system |
| `/bin/setup_product_props.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 778 B | 778 B | +0 B | system |
| `/bin/setup_usb.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 343 B | 343 B | +0 B | system |
| `/bin/setup_usb_serial.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 544 B | 544 B | +0 B | system |
| `/bin/sgdisk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 109.7 KB | 109.7 KB | +0 B | system |
| `/bin/sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 166.0 KB | 166.0 KB | +0 B | system |
| `/bin/showlease` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/start_audio_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | system |
| `/bin/start_blackbox_logs.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 KB | 2.4 KB | +114 B | system |
| `/bin/start_bodystate.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/bin/start_bootlogo.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 401 B | 401 B | +0 B | system |
| `/bin/start_camera_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_compositor.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_configstore.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | system |
| `/bin/start_dji_camera.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 247 B | 247 B | +0 B | system |
| `/bin/start_dji_mount_filesystem.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/start_dji_system.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.7 KB | 3.8 KB | +79 B | system |
| `/bin/start_ftp_server.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 430 B | 430 B | +0 B | system |
| `/bin/start_gpsd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 356 B | 356 B | +0 B | system |
| `/bin/start_gui.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66 B | 66 B | +0 B | system |
| `/bin/start_high_consump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/bin/start_hwshare.sh` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 48 B | +48 B | system |
| `/bin/start_metadata_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | system |
| `/bin/start_msg2dbus.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 445 B | 445 B | +0 B | system |
| `/bin/start_preview_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | system |
| `/bin/start_storage_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | system |
| `/bin/start_sutestgui.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 75 B | 75 B | +0 B | system |
| `/bin/start_sysman.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_upgrade_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/bin/stm32flash` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42.0 KB | 42.0 KB | +0 B | system |
| `/bin/stop_high_consump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 912 B | 912 B | +0 B | system |
| `/bin/storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +23.3 KB | system |
| `/bin/support_audio_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | system |
| `/bin/sutest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 429.6 KB | 429.6 KB | +0 B | system |
| `/bin/switch_autotest.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 302 B | 302 B | +0 B | system |
| `/bin/sync_time.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | system |
| `/bin/sysman` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 377.6 KB | 377.6 KB | +0 B | system |
| `/bin/tee-supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/tee_helloworld` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/bin/test_STMems_sensors` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.7 KB | 13.7 KB | +0 B | system |
| `/bin/test_acce_gyro_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 699 B | 699 B | +0 B | system |
| `/bin/test_ae_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_af_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_af_led_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 672 B | 672 B | +0 B | system |
| `/bin/test_af_mf_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_ambient_light_sensor.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_audio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30.0 KB | 30.0 KB | +0 B | system |
| `/bin/test_back_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | system |
| `/bin/test_battery_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 696 B | 696 B | +0 B | system |
| `/bin/test_bifrost_body_detect.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 368 B | 368 B | +0 B | system |
| `/bin/test_bifrost_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 812 B | 812 B | +0 B | system |
| `/bin/test_bifrost_fullpress_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 346 B | 346 B | +0 B | system |
| `/bin/test_bifrost_grip_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 400 B | 400 B | +0 B | system |
| `/bin/test_bifrost_grip_detect.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 330 B | 330 B | +0 B | system |
| `/bin/test_bifrost_grip_fullpress_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 351 B | 351 B | +0 B | system |
| `/bin/test_bifrost_grip_halfpress_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 351 B | 351 B | +0 B | system |
| `/bin/test_bifrost_grip_joystick.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_bifrost_grip_wheels.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 503 B | 503 B | +0 B | system |
| `/bin/test_bifrost_halfpress_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 346 B | 346 B | +0 B | system |
| `/bin/test_bifrost_shift_button.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/test_bifrost_wheel_left.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273 B | 273 B | +0 B | system |
| `/bin/test_bifrost_wheel_right.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273 B | 273 B | +0 B | system |
| `/bin/test_bifrost_wheels.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_c2d` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | system |
| `/bin/test_camera_setting_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_charge_or_interrupt_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 662 B | 662 B | +0 B | system |
| `/bin/test_charge_or_interrupt_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_cpld_flash_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/bin/test_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 568 B | 568 B | +0 B | system |
| `/bin/test_delete_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_disp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42.4 KB | 42.4 KB | +0 B | system |
| `/bin/test_display_led_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_dji_camera.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 599 B | 599 B | +0 B | system |
| `/bin/test_dji_cht.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 188 B | 188 B | +0 B | system |
| `/bin/test_dji_cht_quick.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 127 B | 127 B | +0 B | system |
| `/bin/test_dji_f2f.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 291 B | 291 B | +0 B | system |
| `/bin/test_dji_pbt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 94 B | 94 B | +0 B | system |
| `/bin/test_dji_ppt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 179 B | 179 B | +0 B | system |
| `/bin/test_dmic_cap.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 158 B | 158 B | +0 B | system |
| `/bin/test_dmic_headphone_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/test_dmic_spk_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | system |
| `/bin/test_dsp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 186.9 KB | 186.9 KB | +0 B | system |
| `/bin/test_dsp_load.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 746 B | 746 B | +0 B | system |
| `/bin/test_eagle_bt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 471 B | 471 B | +0 B | system |
| `/bin/test_eagle_fpga_mipi_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 KB | 1.7 KB | +479 B | system |
| `/bin/test_eagle_fpga_pl_spi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_eagle_fpga_spi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 587 B | 587 B | +0 B | system |
| `/bin/test_eagle_fpga_uart_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 995 B | 995 B | +0 B | system |
| `/bin/test_eagle_spc_uart_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 981 B | 981 B | +0 B | system |
| `/bin/test_eagle_suc_uart_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 977 B | 977 B | +0 B | system |
| `/bin/test_eagle_wifi.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,022 B | 1,022 B | +0 B | system |
| `/bin/test_eld_ports.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 865 B | 865 B | +0 B | system |
| `/bin/test_emmc_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 937 B | 937 B | +0 B | system |
| `/bin/test_evf_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/test_evf_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/test_ext_dc_interrupt_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 167 B | 167 B | +0 B | system |
| `/bin/test_ext_dc_interrupt_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 167 B | 167 B | +0 B | system |
| `/bin/test_external_mic_spk_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/bin/test_farm_recovery_mode.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/test_farm_replace_recovery_image.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 981 B | 981 B | +0 B | system |
| `/bin/test_flashin_flashout_elx_ports.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_flight_lite` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | system |
| `/bin/test_fpga_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_fpga_emmc_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870 B | 870 B | +0 B | system |
| `/bin/test_front_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | system |
| `/bin/test_gps` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/test_gps.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/test_gps_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_hal_plenc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/test_hal_storage` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/test_hdmi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_headphone_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_hotshoe_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 521 B | 521 B | +0 B | system |
| `/bin/test_i2c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/test_imgtec_ienc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/test_imgtec_vdec` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.7 KB | 25.7 KB | +0 B | system |
| `/bin/test_imgtec_venc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.8 KB | 45.8 KB | +0 B | system |
| `/bin/test_imgtec_venc_new` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 57.8 KB | 57.8 KB | +0 B | system |
| `/bin/test_internal_speaker.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 942 B | 942 B | +0 B | system |
| `/bin/test_iso_wb_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_lcd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.1 KB | 26.1 KB | +0 B | system |
| `/bin/test_lcd_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | system |
| `/bin/test_lcd_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/test_lens_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_lens_detect.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 345 B | 345 B | +0 B | system |
| `/bin/test_lens_if_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 617 B | 617 B | +0 B | system |
| `/bin/test_lens_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | system |
| `/bin/test_main_board_power.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | system |
| `/bin/test_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/test_menu_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_mic_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | system |
| `/bin/test_mic_headphone_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | system |
| `/bin/test_mic_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_mic_spk_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/bin/test_mode_dial_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_module_version.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 279 B | 279 B | +0 B | system |
| `/bin/test_mp_stage.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | system |
| `/bin/test_node_version_match.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 978 B | 978 B | +0 B | system |
| `/bin/test_otg_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 740 B | 740 B | +0 B | system |
| `/bin/test_otg_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 281 B | 281 B | +0 B | system |
| `/bin/test_photo_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | system |
| `/bin/test_play_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_playback` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/test_pmic_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 926 B | 926 B | +0 B | system |
| `/bin/test_power_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/test_proximity_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/test_qc_flow_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/bin/test_releasebar_calibrate_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 299 B | 299 B | +0 B | system |
| `/bin/test_releasebar_calibrate_stop.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 298 B | 298 B | +0 B | system |
| `/bin/test_releasebar_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 578 B | 578 B | +0 B | system |
| `/bin/test_releasebar_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 375 B | 375 B | +0 B | system |
| `/bin/test_rtc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/test_rtc_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.4 KB | 6.4 KB | +0 B | system |
| `/bin/test_rtc_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_save_perf.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_sclear_spc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 243 B | 243 B | +0 B | system |
| `/bin/test_script/linux_tests.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 331 B | 331 B | +0 B | system |
| `/bin/test_script/linux_usb_connstatus.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 390 B | 390 B | +0 B | system |
| `/bin/test_sd_performance` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/test_sd_upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 566 B | 566 B | +0 B | system |
| `/bin/test_sd_usb_controllers_pwr.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 933 B | 933 B | +0 B | system |
| `/bin/test_sdcard_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_sdcard_rw.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_sensor_config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 822 B | 822 B | +0 B | system |
| `/bin/test_spc_adc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | system |
| `/bin/test_spc_sensorpattern.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_spc_temp.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/bin/test_spi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/test_spk_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | system |
| `/bin/test_spk_mic_stop.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 952 B | 952 B | +0 B | system |
| `/bin/test_suc_bq25700_i2c.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 906 B | 906 B | +0 B | system |
| `/bin/test_suc_led_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 538 B | 538 B | +0 B | system |
| `/bin/test_suc_ps_gpio_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/test_suc_ps_uart_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 798 B | 798 B | +0 B | system |
| `/bin/test_suc_quick_charge_i2c.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 466 B | 466 B | +0 B | system |
| `/bin/test_suc_sclear_mux.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/test_suc_usb_int_pin_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/test_temperature.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/test_toggle_otg.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 700 B | 700 B | +0 B | system |
| `/bin/test_touch_panel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_usb_interrupt_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 167 B | 167 B | +0 B | system |
| `/bin/test_usb_interrupt_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 167 B | 167 B | +0 B | system |
| `/bin/test_usb_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_v2d` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.8 KB | 21.8 KB | +0 B | system |
| `/bin/test_vdev` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.7 KB | 39.7 KB | +0 B | system |
| `/bin/test_video_setting_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_voltage_level.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | system |
| `/bin/test_wl_venc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.8 KB | 17.8 KB | +0 B | system |
| `/bin/time_elapsed_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 319 B | 319 B | +0 B | system |
| `/bin/tinycap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tinymix` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tinypcminfo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tinyplay` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/toolbox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 95.1 KB | 95.1 KB | +0 B | system |
| `/bin/toybox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 248.4 KB | 248.4 KB | +0 B | system |
| `/bin/tracepath` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tracepath6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/traceroute6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/unrd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/update_engine` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 523.4 KB | 523.4 KB | +0 B | system |
| `/bin/upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | system |
| `/bin/upgrade_bifbody.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 811 B | 811 B | +0 B | system |
| `/bin/upgrade_bifgrip.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 811 B | 811 B | +0 B | system |
| `/bin/upgrade_common.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 924 B | 924 B | +0 B | system |
| `/bin/upgrade_cpld.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | system |
| `/bin/upgrade_eagle.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 150 B | 150 B | +0 B | system |
| `/bin/upgrade_fpga.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/bin/upgrade_fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 73.6 KB | 73.6 KB | +0 B | system |
| `/bin/upgrade_gl3227.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1,001 B | 1,001 B | +0 B | system |
| `/bin/upgrade_spc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | system |
| `/bin/upgrade_suc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.2 KB | 5.2 KB | +0 B | system |
| `/bin/upgrade_suc_instant_return.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117 B | 117 B | +0 B | system |
| `/bin/upgrade_tp.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/bin/upgraded` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 345.6 KB | 345.6 KB | +0 B | system |
| `/bin/usbd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 161.9 KB | 161.9 KB | +0 B | system |
| `/bin/valgrind` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/vdec_test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/victory-gui-static` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.8 MB | 21.2 MB | +344.0 KB | system |
| `/bin/vinput` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/vinput2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/vinput_daemon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.0 KB | 18.0 KB | +0 B | system |
| `/bin/vinput_monkey_lib.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.3 KB | 22.3 KB | +0 B | system |
| `/bin/vinput_monkey_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 KB | 5.3 KB | +0 B | system |
| `/bin/vold` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 370.0 KB | 370.0 KB | +0 B | system |
| `/bin/vold-uhs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/vxe_testbench` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 745.0 KB | 745.0 KB | +0 B | system |
| `/bin/wait_for_key.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/weston` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/wifi_bt_init_env.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/wifi_bt_test_cmd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.7 KB | 14.7 KB | +0 B | system |
| `/bin/wifi_profiled_debug.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/wpa_cli` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.6 KB | 82.6 KB | +0 B | system |
| `/bin/wpa_supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | system |
| `/bin/write_udc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/xtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/build.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 KB | 1.8 KB | +0 B | system/vendor |
| `/data/misc/wifi/wpa_p2p_supplicant.conf` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 67.6 KB | +67.6 KB | system |
| `/etc/NOTICE.html.gz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 87.9 KB | 87.9 KB | +0 B | system |
| `/etc/NOTICE.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 657.9 KB | 657.9 KB | +0 B | system |
| `/etc/VERSION` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6 B | 6 B | +0 B | system |
| `/etc/cht_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 211 B | 211 B | +0 B | system |
| `/etc/dbus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/dji.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117.0 KB | 117.0 KB | +0 B | system |
| `/etc/dji_camera.conf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.6 KB | 9.7 KB | +62 B | system |
| `/etc/dji_camera.tsf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 254 B | 254 B | +0 B | system |
| `/etc/dji_rcam.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 121 B | 121 B | +0 B | system |
| `/etc/event-log-tags` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/etc/firmware/bdwlan30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.9 KB | 7.9 KB | +0 B | system |
| `/etc/firmware/cpld/display_boe_convertor.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 160.8 KB | 160.8 KB | +0 B | system |
| `/etc/firmware/cpld/display_convertor.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 160.8 KB | 160.8 KB | +0 B | system |
| `/etc/firmware/cpld/display_jdi_convertor.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B | system |
| `/etc/firmware/gl.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 112.0 KB | 112.0 KB | +0 B | system |
| `/etc/firmware/nvm_tlv_3.2.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/etc/firmware/otp30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.5 KB | 24.5 KB | +0 B | system |
| `/etc/firmware/qca61x430.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 933.0 KB | 933.0 KB | +0 B | system |
| `/etc/firmware/qwlan30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 507.7 KB | 507.7 KB | +0 B | system |
| `/etc/firmware/rampatch_tlv_3.2.tlv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54.6 KB | 54.6 KB | +0 B | system |
| `/etc/firmware/rtnodes/BOOT.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 129.9 KB | 129.9 KB | +0 B | system |
| `/etc/firmware/rtnodes/FARM.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +8.0 KB | system |
| `/etc/firmware/rtnodes/FPGA.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 MB | 5.3 MB | +0 B | system |
| `/etc/firmware/rtnodes/app.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 MB | 8.3 MB | +76.3 KB | system |
| `/etc/firmware/rtnodes/bifrost_body.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.0 KB | 21.0 KB | +21 B | system |
| `/etc/firmware/rtnodes/bifrost_body_v1.2.7.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 21.0 KB | — | -21.0 KB | system |
| `/etc/firmware/rtnodes/bifrost_body_v1.2.8.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 21.0 KB | +21.0 KB | system |
| `/etc/firmware/rtnodes/bifrost_grip.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.1 KB | 22.1 KB | +16 B | system |
| `/etc/firmware/rtnodes/bifrost_grip_v1.2.6.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 22.1 KB | — | -22.1 KB | system |
| `/etc/firmware/rtnodes/bifrost_grip_v1.2.7.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 22.1 KB | +22.1 KB | system |
| `/etc/firmware/rtnodes/cfv-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 263.6 KB | 266.0 KB | +2.4 KB | system |
| `/etc/firmware/rtnodes/cfv-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +27.4 KB | system |
| `/etc/firmware/rtnodes/fpga_all.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.8 MB | 6.8 MB | +8.0 KB | system |
| `/etc/firmware/rtnodes/fsbl.elf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 597.4 KB | 597.4 KB | +0 B | system |
| `/etc/firmware/rtnodes/power-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.8 KB | 53.8 KB | +4 B | system |
| `/etc/firmware/rtnodes/power-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +10.4 KB | system |
| `/etc/firmware/rtnodes/system_wrapper.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 MB | 5.3 MB | +0 B | system |
| `/etc/firmware/rtnodes/xsystem-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 244.0 KB | 246.4 KB | +2.4 KB | system |
| `/etc/firmware/rtnodes/xsystem-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.4 MB | 2.4 MB | +27.4 KB | system |
| `/etc/firmware/tpfw.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32.0 KB | 32.0 KB | +0 B | system |
| `/etc/firmware/utf30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323.4 KB | 323.4 KB | +0 B | system |
| `/etc/firmware/wlan/cfg.dat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | system |
| `/etc/firmware/wlan/qcom_cfg.ini` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.8 KB | 15.8 KB | +0 B | system |
| `/etc/ftp.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | system |
| `/etc/hostapd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 343 B | 343 B | +0 B | system |
| `/etc/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56 B | 56 B | +0 B | system |
| `/etc/imx161f_ec1704.sp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.4 KB | 28.9 KB | +2.5 KB | system |
| `/etc/mkshrc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/adbd.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | system |
| `/etc/notices/atrace.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/debuggerd.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/dhcpcd.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/etc/notices/dhcptool.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/file_contexts.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/gzip.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/etc/notices/init.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/ip.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/etc/notices/kernel.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | system |
| `/etc/notices/ksminfo.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/latencytop.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libLLVM.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | system |
| `/etc/notices/libadbd.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | system |
| `/etc/notices/libc++abi.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/etc/notices/libc.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256.8 KB | 256.8 KB | +0 B | system |
| `/etc/notices/libc_common.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256.8 KB | 256.8 KB | +0 B | system |
| `/etc/notices/libc_malloc_debug_leak.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256.8 KB | 256.8 KB | +0 B | system |
| `/etc/notices/libc_malloc_debug_qemu.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256.8 KB | 256.8 KB | +0 B | system |
| `/etc/notices/libc_nomalloc.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256.8 KB | 256.8 KB | +0 B | system |
| `/etc/notices/libcompiler_rt-extras.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/etc/notices/libcrypto.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/etc/notices/libcutils.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libdl.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 709 B | 709 B | +0 B | system |
| `/etc/notices/libexpat.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/etc/notices/libext4_utils.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libext4_utils_static.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libf2fs_fmt.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44.4 KB | 44.4 KB | +0 B | system |
| `/etc/notices/libf2fs_sparseblock.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libft2.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.7 KB | 6.7 KB | +0 B | system |
| `/etc/notices/libfusesideload.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libhardware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libhardware_legacy.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libinit.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libiprouteutil.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/etc/notices/libjemalloc.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/etc/notices/libjpeg.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | system |
| `/etc/notices/libjpeg_static.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | system |
| `/etc/notices/liblog.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/liblogwrap.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libm.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55.3 KB | 55.3 KB | +0 B | system |
| `/etc/notices/libmincrypt.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/libnetlink.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/etc/notices/libnetutils.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libnl.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | system |
| `/etc/notices/libpagemap.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libpcap.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 935 B | 935 B | +0 B | system |
| `/etc/notices/libpng.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/etc/notices/libpower.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/librank.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libscrypt_static.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/etc/notices/libselinux.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/libspeexresampler.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | system |
| `/etc/notices/libsqlite.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 336 B | 336 B | +0 B | system |
| `/etc/notices/libsqlite3_android.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libssl.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/etc/notices/libstdc++.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256.8 KB | 256.8 KB | +0 B | system |
| `/etc/notices/libstlport.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | system |
| `/etc/notices/libtinyalsa.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/libtoolbox_dd.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 50.7 KB | 50.7 KB | +0 B | system |
| `/etc/notices/libtoolbox_du.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 50.7 KB | 50.7 KB | +0 B | system |
| `/etc/notices/libunwind.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/libunwind_llvm.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/etc/notices/libusb.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | system |
| `/etc/notices/libutils.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/libxml2.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/etc/notices/libz.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/etc/notices/linker.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.4 KB | 9.4 KB | +0 B | system |
| `/etc/notices/logcat.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/logwrapper.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/mac_permissions.xml.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/mkfs.f2fs.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44.4 KB | 44.4 KB | +0 B | system |
| `/etc/notices/mkshrc.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/pngtest.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/etc/notices/procmem.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/procrank.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/property_contexts.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/r.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 50.7 KB | 50.7 KB | +0 B | system |
| `/etc/notices/rawbu.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/recovery.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/rtnodes.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.0 KB | 20.0 KB | +0 B | system |
| `/etc/notices/seapp_contexts.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/sepolicy.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/service.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/sgdisk.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/etc/notices/sh.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/notices/showlease.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/etc/notices/showmap.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/showslab.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/sqlite3.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 336 B | 336 B | +0 B | system |
| `/etc/notices/su.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/taskstats.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/tinycap.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/tinymix.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/tinypcminfo.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/tinyplay.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/etc/notices/toolbox.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 50.7 KB | 50.7 KB | +0 B | system |
| `/etc/notices/tracepath.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/notices/tracepath6.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/notices/traceroute6.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/notices/update_engine.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.5 KB | 10.5 KB | +0 B | system |
| `/etc/notices/valgrind.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/etc/ppt_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 108 B | 108 B | +0 B | system |
| `/etc/recovery-resource.dat` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 297.7 KB | 297.7 KB | +0 B | system |
| `/etc/recovery.fstab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 935 B | 935 B | +0 B | system |
| `/etc/security/mac_permissions.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/etc/security/otacerts.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/udhcpd_rndis.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/udhcpd_wifi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/venc_test/venc_1080P_test.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/etc/venc_test/venc_1080p_liveview.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/etc/venc_test/venc_2K_2720x1530_test.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/etc/venc_test/venc_4kUHD_test.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/etc/venc_test/venc_performance_test.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/firmware/camera/exp_compress0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.3 KB | 403.3 KB | +0 B | vendor |
| `/firmware/camera/exp_compress1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.3 KB | 403.3 KB | +0 B | vendor |
| `/firmware/camera/exp_compress2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.3 KB | 403.3 KB | +0 B | vendor |
| `/firmware/camera/exp_compress3.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.3 KB | 403.3 KB | +0 B | vendor |
| `/firmware/camera/exp_compress4.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.3 KB | 403.3 KB | +0 B | vendor |
| `/firmware/camera/gaussian.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 172.2 KB | 172.2 KB | +0 B | vendor |
| `/firmware/camera/hdr.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 307.4 KB | 307.4 KB | +0 B | vendor |
| `/firmware/camera/hdr2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 463.0 KB | 463.0 KB | +0 B | vendor |
| `/firmware/camera/hiso0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 392.2 KB | 392.2 KB | +0 B | vendor |
| `/firmware/camera/hiso1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 392.2 KB | 392.2 KB | +0 B | vendor |
| `/firmware/camera/hiso2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 392.2 KB | 392.2 KB | +0 B | vendor |
| `/firmware/camera/hiso3.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 392.2 KB | 392.2 KB | +0 B | vendor |
| `/firmware/camera/hiso4.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 392.2 KB | 392.2 KB | +0 B | vendor |
| `/firmware/camera/lcdcomp.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 510.6 KB | 510.6 KB | +0 B | vendor |
| `/firmware/camera/panorama.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 490.5 KB | 490.5 KB | +0 B | vendor |
| `/firmware/camera/pfr0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 387.5 KB | 387.5 KB | +0 B | vendor |
| `/firmware/camera/pfr1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 387.5 KB | 387.5 KB | +0 B | vendor |
| `/firmware/camera/pfr2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 387.5 KB | 387.5 KB | +0 B | vendor |
| `/firmware/camera/pfr3.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 387.5 KB | 387.5 KB | +0 B | vendor |
| `/firmware/camera/pfr4.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 387.5 KB | 387.5 KB | +0 B | vendor |
| `/firmware/camera/sbpc.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 172.7 KB | 172.7 KB | +0 B | vendor |
| `/firmware/camera/xidiri.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 502.8 KB | 502.8 KB | +0 B | vendor |
| `/firmware/camera/xidiri_mcmw0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 539.3 KB | 539.3 KB | +0 B | vendor |
| `/firmware/camera/xidiri_mcmw1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 539.3 KB | 539.3 KB | +0 B | vendor |
| `/firmware/camera/xidiri_mcmw2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 539.3 KB | 539.3 KB | +0 B | vendor |
| `/firmware/camera/xidiri_mcmw3.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 539.3 KB | 539.3 KB | +0 B | vendor |
| `/firmware/camera/xidiri_mcmw4.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 539.3 KB | 539.3 KB | +0 B | vendor |
| `/firmware/camera/xidiri_sw0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 495.0 KB | 495.0 KB | +0 B | vendor |
| `/firmware/camera/xidiri_sw1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 495.0 KB | 495.0 KB | +0 B | vendor |
| `/firmware/camera/xidiri_sw2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 495.0 KB | 495.0 KB | +0 B | vendor |
| `/firmware/camera/xidiri_sw3.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 495.0 KB | 495.0 KB | +0 B | vendor |
| `/firmware/camera/xidiri_sw4.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 495.0 KB | 495.0 KB | +0 B | vendor |
| `/firmware/camera/ydns0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.1 KB | 380.1 KB | +0 B | vendor |
| `/firmware/camera/ydns1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.1 KB | 380.1 KB | +0 B | vendor |
| `/firmware/camera/ydns2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.1 KB | 380.1 KB | +0 B | vendor |
| `/firmware/camera/ydns3.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.1 KB | 380.1 KB | +0 B | vendor |
| `/firmware/camera/ydns4.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.1 KB | 380.1 KB | +0 B | vendor |
| `/lib/crtbegin_so.o` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/lib/crtend_so.o` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 620 B | 620 B | +0 B | system |
| `/lib/hw/sensors.eagle.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | vendor |
| `/lib/libAACdec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 245.9 KB | 245.9 KB | +0 B | system |
| `/lib/libAACenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 285.6 KB | 285.6 KB | +0 B | system |
| `/lib/libAppsMessaging.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libLLVM.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.4 MB | 10.4 MB | +0 B | system |
| `/lib/libMessageTransport.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libQt5Concurrent.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.4 KB | 21.4 KB | +0 B | system |
| `/lib/libQt5Core.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 MB | 3.4 MB | +0 B | system |
| `/lib/libQt5DBus.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 529.4 KB | 529.4 KB | +0 B | system |
| `/lib/libQt5Network.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 433.4 KB | 433.4 KB | +0 B | system |
| `/lib/libQt5Positioning.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 485.5 KB | 485.5 KB | +0 B | system |
| `/lib/libQt5SerialPort.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 81.3 KB | 81.3 KB | +0 B | system |
| `/lib/libQt5Sql.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237.4 KB | 237.4 KB | +0 B | system |
| `/lib/libQt5Xml.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 109.4 KB | 109.4 KB | +0 B | system |
| `/lib/libSystemCommon.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libVdecAppGST.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 109.3 KB | 109.3 KB | +0 B | system |
| `/lib/lib_camcomp.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/lib/lib_eigen.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.6 KB | 85.6 KB | +0 B | system |
| `/lib/lib_hal_gdc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/lib_mdev.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/lib_mediactl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libadsb_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libamt_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | system |
| `/lib/libappscommon.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 2.0 MB | +72.0 KB | system |
| `/lib/libaudioutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libavcodec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 MB | 2.5 MB | +0 B | system |
| `/lib/libavfilter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.5 KB | 130.5 KB | +0 B | system |
| `/lib/libavformat.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 358.8 KB | 358.8 KB | +0 B | system |
| `/lib/libavutil.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 297.4 KB | 297.4 KB | +0 B | system |
| `/lib/libbacktrace.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.6 KB | 37.6 KB | +0 B | system |
| `/lib/libbacktrace_test.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libbase.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.7 KB | 37.7 KB | +0 B | system |
| `/lib/libbinder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 177.7 KB | 177.7 KB | +0 B | system |
| `/lib/libc++.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 561.7 KB | 561.7 KB | +0 B | system |
| `/lib/libc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 665.9 KB | 665.9 KB | +0 B | system |
| `/lib/libc_malloc_debug_leak.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 145.7 KB | 145.7 KB | +0 B | system |
| `/lib/libc_malloc_debug_qemu.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.5 KB | 25.5 KB | +0 B | system |
| `/lib/libcrypto.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 622.1 KB | 622.1 KB | +0 B | system |
| `/lib/libcutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.8 KB | 61.8 KB | +0 B | system |
| `/lib/libdbus.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 365.8 KB | 365.8 KB | +0 B | system |
| `/lib/libdcam_fcali.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 163.6 KB | 163.6 KB | +0 B | system |
| `/lib/libdcam_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +24 B | system |
| `/lib/libdcam_metadata.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libdcam_pp.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 570.7 KB | 570.7 KB | +0 B | system |
| `/lib/libdiskconfig.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libdjishare.so` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 265.5 KB | +265.5 KB | system |
| `/lib/libdl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.3 KB | 9.3 KB | +0 B | system |
| `/lib/libduml_audio.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.6 KB | 69.6 KB | +0 B | system |
| `/lib/libduml_ffremux.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libduml_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 523.3 KB | 523.3 KB | +0 B | system |
| `/lib/libduml_hal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 250.0 KB | 250.0 KB | +0 B | system |
| `/lib/libduml_hal_cam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 393.6 KB | 394.4 KB | +792 B | system |
| `/lib/libduml_media.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 94.1 KB | 94.1 KB | +0 B | system |
| `/lib/libduml_osal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libduml_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.8 KB | 45.8 KB | +0 B | system |
| `/lib/libduml_watermark.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libevdev.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.5 KB | 49.5 KB | +0 B | system |
| `/lib/libewgfx.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 125.6 KB | 125.6 KB | +0 B | system |
| `/lib/libewgfx_watermark.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165.6 KB | 165.6 KB | +0 B | system |
| `/lib/libewnativeadapter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.7 KB | 29.7 KB | +0 B | system |
| `/lib/libewnativebackend_mb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.7 KB | 85.7 KB | +0 B | system |
| `/lib/libewplatform.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 76.1 KB | 76.1 KB | +0 B | system |
| `/lib/libewrte.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.6 KB | 53.6 KB | +0 B | system |
| `/lib/libexfat.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libexpat.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.4 KB | 85.4 KB | +0 B | system |
| `/lib/libext2_blkid.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.9 KB | 39.9 KB | +0 B | system |
| `/lib/libext2_com_err.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libext2_e2p.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30.4 KB | 30.4 KB | +0 B | system |
| `/lib/libext2_profile.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libext2_quota.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libext2_uuid.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libext2fs.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 170.1 KB | 170.1 KB | +0 B | system |
| `/lib/libext4_utils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.6 KB | 73.6 KB | +0 B | system |
| `/lib/libf2fs_sparseblock.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libft2.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 377.6 KB | 377.6 KB | +0 B | system |
| `/lib/libfw_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libfw_util_ca.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libglib.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 590.3 KB | 590.3 KB | +0 B | system |
| `/lib/libhardware.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libhardware_legacy.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libhblupgrade.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libhelper_api_sa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 616.7 KB | 616.7 KB | +0 B | system |
| `/lib/libhyperlapse_eis.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 288.5 KB | 288.5 KB | +0 B | system |
| `/lib/libiconv.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 869.6 KB | 869.6 KB | +0 B | system |
| `/lib/libicui18n.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 MB | 1.4 MB | +0 B | system |
| `/lib/libicuuc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/libimgjpegenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35.6 KB | 35.6 KB | +0 B | system |
| `/lib/libion.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libiprouteutil.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35.6 KB | 35.6 KB | +0 B | system |
| `/lib/libjnigraphics.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/lib/libjpeg.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 217.6 KB | 217.6 KB | +0 B | system |
| `/lib/libkeymaster1.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101.8 KB | 101.8 KB | +0 B | system |
| `/lib/libkeymaster_messages.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.6 KB | 37.6 KB | +0 B | system |
| `/lib/libkeystore-engine.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libkeystore_binder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.7 KB | 49.7 KB | +0 B | system |
| `/lib/liblog.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.7 KB | 33.7 KB | +0 B | system |
| `/lib/liblogwrap.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 129.8 KB | 129.8 KB | +0 B | system |
| `/lib/libmod_dji.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 514.2 KB | 514.2 KB | +0 B | system |
| `/lib/libmod_x1dm2.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +64 B | system |
| `/lib/libnetlink.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libnetutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libnl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 75.7 KB | 75.7 KB | +0 B | system |
| `/lib/libomx_vxd.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | system |
| `/lib/libopencv_java3.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.2 MB | 8.2 MB | +0 B | system |
| `/lib/libpagemap.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libpcre.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.6 KB | 73.6 KB | +0 B | system |
| `/lib/libplist.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 347.7 KB | 347.7 KB | +0 B | system |
| `/lib/libpng.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 157.6 KB | 157.6 KB | +0 B | system |
| `/lib/libpower.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libproresenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36.3 KB | 36.3 KB | +0 B | system |
| `/lib/libprotobuf-cpp-lite.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 97.7 KB | 97.7 KB | +0 B | system |
| `/lib/libreg_dump_api.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libselinux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.7 KB | 61.7 KB | +0 B | system |
| `/lib/libservice.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 422.2 KB | 422.2 KB | +0 B | system |
| `/lib/libsharekit.so` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 2.2 MB | +2.2 MB | system |
| `/lib/libsoftkeymaster.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/lib/libsoftkeymasterdevice.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.8 KB | 85.8 KB | +0 B | system |
| `/lib/libsparse.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.7 KB | 29.7 KB | +0 B | system |
| `/lib/libspeexresampler.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.0 KB | 31.0 KB | +0 B | system |
| `/lib/libsqlite.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 401.2 KB | 401.2 KB | +0 B | system |
| `/lib/libssl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 145.5 KB | 145.5 KB | +0 B | system |
| `/lib/libstdc++.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.5 KB | 21.5 KB | +0 B | system |
| `/lib/libstlport.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237.7 KB | 237.7 KB | +0 B | system |
| `/lib/libswresample.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.4 KB | 69.4 KB | +0 B | system |
| `/lib/libsysutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libteec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libtinyalsa.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | system |
| `/lib/libunrd.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libunwind.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.6 KB | 65.6 KB | +0 B | system |
| `/lib/libusb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libusbmuxd.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libutils.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101.7 KB | 101.7 KB | +0 B | system |
| `/lib/libv2_sdk.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 81.7 KB | 81.7 KB | +0 B | system |
| `/lib/libwayland-client.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.9 KB | 41.9 KB | +0 B | system |
| `/lib/libwayland-cursor.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libwayland-server.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54.0 KB | 54.0 KB | +0 B | system |
| `/lib/libweston.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 858.5 KB | 858.5 KB | +0 B | system |
| `/lib/libwm_blender_256x64.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 97.6 KB | 97.6 KB | +0 B | system |
| `/lib/libwpa_client.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libxkbcommon.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 197.6 KB | 197.6 KB | +0 B | system |
| `/lib/libxml2.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 872.2 KB | 872.2 KB | +0 B | system |
| `/lib/libz.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 105.7 KB | 105.7 KB | +0 B | system |
| `/lib/modules/atmel_mxt_ts.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 195.6 KB | 195.6 KB | +0 B | system |
| `/lib/modules/designware_i2s.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 186.7 KB | 186.7 KB | +0 B | system |
| `/lib/modules/dji-spinor.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 136.3 KB | 136.3 KB | +0 B | system |
| `/lib/modules/dji_csi_host.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 266.0 KB | 266.0 KB | +0 B | system |
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 210.1 KB | 210.1 KB | +0 B | system |
| `/lib/modules/dji_v2d.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 150.8 KB | 150.8 KB | +0 B | system |
| `/lib/modules/e1000e.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +0 B | system |
| `/lib/modules/e5010_mod.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 143.7 KB | 143.7 KB | +0 B | system |
| `/lib/modules/eagle_dsp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 290.8 KB | 290.8 KB | +0 B | system |
| `/lib/modules/echainiv.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 128.6 KB | 128.6 KB | +0 B | system |
| `/lib/modules/ecx337aa.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 143.1 KB | 143.1 KB | +0 B | system |
| `/lib/modules/gdc_eagle.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 154.9 KB | 154.9 KB | +0 B | system |
| `/lib/modules/gpio_keys.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 147.1 KB | 147.1 KB | +0 B | system |
| `/lib/modules/gspca_main.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 370.7 KB | 370.7 KB | +0 B | system |
| `/lib/modules/himax_tp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 684.3 KB | 684.3 KB | +0 B | system |
| `/lib/modules/icc_chnl.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 386.0 KB | 386.0 KB | +0 B | system |
| `/lib/modules/ili2120.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 129.7 KB | 130.0 KB | +299 B | system |
| `/lib/modules/imgtec/encoder_fw.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93.2 KB | 93.2 KB | +0 B | system |
| `/lib/modules/imgtec/img_mem.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 737.5 KB | 737.5 KB | +0 B | system |
| `/lib/modules/imgtec/imgvideo.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +0 B | system |
| `/lib/modules/imgtec/pvdec_full_bin.fw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 244.2 KB | 244.2 KB | +0 B | system |
| `/lib/modules/imgtec/vxd.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 792.5 KB | 792.5 KB | +0 B | system |
| `/lib/modules/imgtec/vxekm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 836.5 KB | 836.5 KB | +0 B | system |
| `/lib/modules/irq-madera-cs47l35.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 38.8 KB | 38.8 KB | +0 B | system |
| `/lib/modules/irq-madera.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 116.5 KB | 116.5 KB | +0 B | system |
| `/lib/modules/l3ej03110a.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 144.0 KB | 144.0 KB | +0 B | system |
| `/lib/modules/leds-pca963x.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.8 KB | 125.8 KB | +0 B | system |
| `/lib/modules/ledtrig-oneshot.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.4 KB | 89.4 KB | +0 B | system |
| `/lib/modules/madera-i2c.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 119.0 KB | 119.0 KB | +0 B | system |
| `/lib/modules/mmc_test.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 238.8 KB | 238.8 KB | +0 B | system |
| `/lib/modules/proresenc_mod.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 152.2 KB | 152.2 KB | +0 B | system |
| `/lib/modules/rcam_dji.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 MB | 8.3 MB | +184 B | system |
| `/lib/modules/regmap-spi.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 124.6 KB | 124.6 KB | +0 B | system |
| `/lib/modules/sfh7776.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 145.3 KB | 145.3 KB | +0 B | system |
| `/lib/modules/snd-compress.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 166.2 KB | 166.2 KB | +0 B | system |
| `/lib/modules/snd-pcm-dmaengine.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 145.0 KB | 145.0 KB | +0 B | system |
| `/lib/modules/snd-pcm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/modules/snd-soc-core.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +0 B | system |
| `/lib/modules/snd-soc-cs47l35.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 967.0 KB | 967.0 KB | +0 B | system |
| `/lib/modules/snd-soc-ics43434.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 147.8 KB | 147.8 KB | +0 B | system |
| `/lib/modules/snd-soc-madera.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 318.5 KB | 318.5 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 185.8 KB | 185.8 KB | +0 B | system |
| `/lib/modules/snd-soc-tfa9890.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 180.7 KB | 180.7 KB | +0 B | system |
| `/lib/modules/snd-soc-tlv320aic31xx.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 209.8 KB | 209.8 KB | +0 B | system |
| `/lib/modules/snd-soc-wm-adsp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 260.7 KB | 260.7 KB | +0 B | system |
| `/lib/modules/snd.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 844.8 KB | 844.8 KB | +0 B | system |
| `/lib/modules/soundcore.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 105.2 KB | 105.2 KB | +0 B | system |
| `/lib/modules/tc358749.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 289.5 KB | 289.5 KB | +0 B | system |
| `/lib/modules/uinput.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 154.4 KB | 154.4 KB | +0 B | system |
| `/lib/modules/vision_acc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 952.1 KB | 952.1 KB | +0 B | system |
| `/lib/modules/wlan.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.1 MB | 4.1 MB | +0 B | system |
| `/lib/qt/lib/fonts/DroidSansFallback.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 MB | 2.9 MB | +0 B | system |
| `/lib/qt/lib/fonts/DroidSansJapanese.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue-Bold.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 470.2 KB | 470.2 KB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue-Light.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 208.8 KB | 208.8 KB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue-Medium.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 185.7 KB | 185.7 KB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 464.3 KB | 464.3 KB | +0 B | system |
| `/lib/qt/plugins/position/libgpsplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.5 KB | 61.5 KB | +0 B | system |
| `/lib/qt/plugins/position/libqtposition_positionpoll.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.4 KB | 41.4 KB | +0 B | system |
| `/lib/qt/plugins/sqldrivers/libqsqlite.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 893.0 KB | 893.0 KB | +0 B | system |
| `/lib/weston/eagle-backend.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 402.5 KB | 402.5 KB | +0 B | system |
| `/lib/weston/eagle-shell.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.5 KB | 33.5 KB | +0 B | system |
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.6 MB | 15.6 MB | -4 B | system |
| `/ta/0388301d-7a5b-4153-968c3a668ae6cdd8.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 137.9 KB | 137.9 KB | +0 B | vendor |
| `/ta/5b9e0e40-2636-11e1-ad9e0002a5d5c51b.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 169.8 KB | 169.8 KB | +0 B | vendor |
| `/ta/5ce0c432-0ab0-40e5-a056782ca0e6aba2.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.7 KB | 77.7 KB | +0 B | vendor |
| `/ta/614789f2-39c0-4ebf-b23592b32ac107ed.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.7 KB | 77.7 KB | +0 B | vendor |
| `/ta/731e279e-aafb-4575-a77138caa6f0cca6.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.7 KB | 77.7 KB | +0 B | vendor |
| `/ta/8aaaf200-2450-11e4-abe20002a5d5c51b.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.8 KB | 61.8 KB | +0 B | vendor |
| `/ta/b689f2a7-8adf-477a-9f9932e90c0ad0a2.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.7 KB | 77.7 KB | +0 B | vendor |
| `/ta/c3f6e2c0-3548-11e1-b86c0800200c9a66.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.7 KB | 61.7 KB | +0 B | vendor |
| `/ta/cb3e5ba0-adf1-11e0-998b0002a5d5c51b.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 94.0 KB | 94.0 KB | +0 B | vendor |
| `/ta/d17f73a0-36ef-11e1-984a0002a5d5c51b.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.7 KB | 61.7 KB | +0 B | vendor |
| `/ta/e13010e0-2ae1-11e5-896a0002a5d5c51b.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.7 KB | 77.7 KB | +0 B | vendor |
| `/ta/e626662e-c0e2-485c-b8c809fbce6edf3d.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.8 KB | 77.8 KB | +0 B | vendor |
| `/ta/e6a33ed4-562b-463a-bb7eff5e15a493c8.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.7 KB | 61.7 KB | +0 B | vendor |
| `/ta/e8a03b87-cda7-4513-94facf09d2d2b78a.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.8 KB | 89.8 KB | +0 B | vendor |
| `/ta/f157cda0-550c-11e5-a6fa0002a5d5c51b.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 69.7 KB | 69.7 KB | +0 B | vendor |
| `/usr/icu/icudt55l.dat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.0 MB | 22.0 MB | +0 B | system |
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
| `/usr/share/system-sound/error.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.7 KB | 82.7 KB | +0 B | system |
| `/usr/share/system-sound/five_photos_left.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 60.1 KB | 60.1 KB | +0 B | system |
| `/usr/share/system-sound/keyclick.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38.7 KB | 38.7 KB | +0 B | system |
| `/usr/share/system-sound/low_battery.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38.7 KB | 38.7 KB | +0 B | system |
| `/usr/share/system-sound/media_full.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.2 KB | 82.2 KB | +0 B | system |
| `/usr/share/system-sound/off.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59.8 KB | 59.8 KB | +0 B | system |
| `/usr/share/system-sound/on.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40.2 KB | 40.2 KB | +0 B | system |
| `/usr/share/system-sound/one_photo_left.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 80.2 KB | 80.2 KB | +0 B | system |
| `/usr/share/system-sound/out_of_range_multi.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.4 KB | 131.4 KB | +0 B | system |
| `/usr/share/system-sound/out_of_range_single.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35.5 KB | 35.5 KB | +0 B | system |
| `/usr/share/system-sound/overexp.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 76.0 KB | 76.0 KB | +0 B | system |
| `/usr/share/system-sound/ready.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.5 KB | 49.5 KB | +0 B | system |
| `/usr/share/system-sound/selftimer_count.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40.0 KB | 40.0 KB | +0 B | system |
| `/usr/share/system-sound/tethered_connect.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.2 KB | 66.2 KB | +0 B | system |
| `/usr/share/system-sound/tethered_disconnect.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.2 KB | 56.2 KB | +0 B | system |
| `/usr/share/system-sound/transfer_complete.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30.9 KB | 30.9 KB | +0 B | system |
| `/usr/share/system-sound/underexp.wav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 77.5 KB | 77.5 KB | +0 B | system |
| `/usr/share/zoneinfo/tzdata` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 480.3 KB | 480.3 KB | +0 B | system |
| `/xbin/add-property-tag` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 182.0 KB | 182.0 KB | +0 B | system |
| `/xbin/avdtptest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.3 KB | 66.3 KB | +0 B | system |
| `/xbin/avinfo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/xbin/avtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.8 KB | 21.8 KB | +0 B | system |
| `/xbin/bneptest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 50.0 KB | 50.0 KB | +0 B | system |
| `/xbin/btmgmt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 111.9 KB | 111.9 KB | +0 B | system |
| `/xbin/btmon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 361.7 KB | 361.7 KB | +0 B | system |
| `/xbin/btproxy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.7 KB | 25.7 KB | +0 B | system |
| `/xbin/busybox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 MB | 1.9 MB | +0 B | system |
| `/xbin/check-lost+found` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 194.0 KB | 194.0 KB | +0 B | system |
| `/xbin/cpustats` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/dbus-monitor` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/xbin/haltest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 129.2 KB | 129.2 KB | +0 B | system |
| `/xbin/hciconfig` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 120.6 KB | 120.6 KB | +0 B | system |
| `/xbin/hcitool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 88.3 KB | 88.3 KB | +0 B | system |
| `/xbin/ksminfo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/l2ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.6 KB | 33.6 KB | +0 B | system |
| `/xbin/l2test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.7 KB | 45.7 KB | +0 B | system |
| `/xbin/latencytop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/librank` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.8 KB | 17.8 KB | +0 B | system |
| `/xbin/mcaptest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 62.2 KB | 62.2 KB | +0 B | system |
| `/xbin/micro_bench` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | system |
| `/xbin/micro_bench_static` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 194.2 KB | 194.2 KB | +0 B | system |
| `/xbin/perfprofd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 105.7 KB | 105.7 KB | +0 B | system |
| `/xbin/procmem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/procrank` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/puncture_fs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/rawbu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/xbin/rctest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.6 KB | 45.6 KB | +0 B | system |
| `/xbin/sane_schedstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/showmap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/showslab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/simpleperf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 125.6 KB | 125.6 KB | +0 B | system |
| `/xbin/sqlite3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.3 KB | 65.3 KB | +0 B | system |
| `/xbin/strace` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 277.8 KB | 277.8 KB | +0 B | system |
| `/xbin/su` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/taskstats` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/xbin/tcpdump` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 810.6 KB | 810.6 KB | +0 B | system |
</details>
