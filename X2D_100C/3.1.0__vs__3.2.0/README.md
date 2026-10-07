# X2D 100C: 3.1.0 ➜ 3.2.0

> 生成时间: 2026-10-07T06:08:26 · CIM 日期: 2023-11-25 ➜ 2024-05-25 · 条目: 8 ➜ 8 · 源: `X2D_100C_v3_1_0.cim` ➜ `X2D_100C_v3_2_0.cim`

## Summary

文件树 +4/-0/~215；CIM 条目 +0/-0/~7；OTA 镜像 ~7 变更 / 0 未变；符号 +1641/-964 funcs, +455/-828 objs；新增字符串 1190 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B |
| `exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 412.5 KB | 413.6 KB | +1.0 KB |
| `exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +1.0 KB |
| `exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B |
| `hbl-post-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 12.8 KB | 13.5 KB | +715 B |
| `hbl-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.4 KB | 7.1 KB | +728 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 160.4 MB | 162.3 MB | +1.9 MB |
| `ec2107_cpld.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 7 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 1

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 544.0 KB | 544.0 KB | +0 B |
| `gimbal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 355.3 KB | 355.3 KB | +0 B |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 18.6 MB | 19.0 MB | +400.5 KB |
| `scp.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.4 KB | 89.4 KB | +0 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 512.0 MB | 512.0 MB | +0 B |
| `tos.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 449.1 KB | 449.7 KB | +672 B |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.2 MB | 45.3 MB | +96.0 KB |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 7 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `lib` | 2 | 0 | 72 | 0 | 0 |
| `lib64` | 0 | 0 | 62 | 226 | 0 |
| `bin` | 0 | 0 | 32 | 312 | 0 |
| `model` | 0 | 0 | 23 | 0 | 0 |
| `etc` | 2 | 0 | 15 | 162 | 0 |
| `firmware` | 0 | 0 | 6 | 8 | 0 |
| `(root)` | 0 | 0 | 3 | 2 | 0 |
| `ta` | 0 | 0 | 2 | 0 | 0 |
| `product` | 0 | 0 | 0 | 1 | 0 |
| `usr` | 0 | 0 | 0 | 14 | 0 |
| `xbin` | 0 | 0 | 0 | 10 | 0 |

明细 954 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+1641 / −964** functions, **+455 / −828** objects（50 个变更 ELF, 另有 109 个未列出）。

### `/bin/camera-service`

+380 / −255 functions · +93 / −126 objects

**New functions (380)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN3x2d22StateExposureMultiShot18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x9f6b0 | 4 |
| `_ZN3x2d29StateCaptureMultiShotExposure18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x9f6b0 | 4 |
| `_ZN28LiveviewCalibrationDataAsync18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x9fcf8 | 336 |
| `_ZN28LiveviewCalibrationDataAsync10dataLoadedENSt3__110shared_ptrI12DussMemShareEE` | 0x9fe48 | 88 |
| `_ZNK28LiveviewCalibrationDataAsync10metaObjectEv` | 0x9fea0 | 28 |
| `_ZN28LiveviewCalibrationDataAsync11qt_metacastEPKc` | 0x9fec0 | 84 |
| `_ZN28LiveviewCalibrationDataAsync11qt_metacallEN11QMetaObject4CallEiPPv` | 0x9ff18 | 124 |
| `_ZN29LiveviewCalibrationDataLoader18qt_static_metacallEP7QObjectN11QMetaObject4CallEiPPv` | 0x9ff98 | 336 |
| `_ZN29LiveviewCalibrationDataLoader12workerResultENSt3__110shared_ptrI12DussMemShareEE` | 0xa00e8 | 88 |
| `_ZNK29LiveviewCalibrationDataLoader10metaObjectEv` | 0xa0140 | 28 |
| `_ZN29LiveviewCalibrationDataLoader11qt_metacastEPKc` | 0xa0160 | 84 |
| `_ZN29LiveviewCalibrationDataLoader11qt_metacallEN11QMetaObject4CallEiPPv` | 0xa01b8 | 124 |
| `_ZN3x2d22StateExposureMultiShot11qt_metacallEN11QMetaObject4CallEiPPv` | 0xa2870 | 4 |
| `_ZN3x2d29StateCaptureMultiShotExposure11qt_metacallEN11QMetaObject4CallEiPPv` | 0xa2870 | 4 |
| `_ZN20LensControlInterface28extensionTubeDetectedChangedEb` | 0xaf3b8 | 100 |
| `_ZNK3x2d29StateCaptureMultiShotExposure10metaObjectEv` | 0xb2308 | 28 |
| `_ZN3x2d29StateCaptureMultiShotExposure11qt_metacastEPKc` | 0xb2328 | 104 |
| `_ZNK3x2d22StateExposureMultiShot10metaObjectEv` | 0xb2d18 | 28 |
| `_ZN3x2d22StateExposureMultiShot11qt_metacastEPKc` | 0xb2d38 | 84 |
| `_ZN29LiveviewCalibrationDataLoaderD2Ev` | 0xb3bd0 | 104 |
| `_ZN29LiveviewCalibrationDataLoaderD0Ev` | 0xb3c38 | 112 |
| `_ZN3x2d22StateExposureMultiShotD0Ev` | 0xb4458 | 36 |
| `_ZN3x2d29StateCaptureMultiShotExposureD2Ev` | 0xb6cc0 | 80 |
| `_ZN3x2d29StateCaptureMultiShotExposureD0Ev` | 0xb6d10 | 88 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI28LiveviewCalibrationDataAsyncE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0xb78b0 | 16 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI29LiveviewCalibrationDataLoaderE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0xb78b0 | 16 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN3x2d22StateExposureMultiShotEE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xb78b0 | 16 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN3x2d29StateCaptureMultiShotExposureEE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xb78b0 | 16 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0xb7948 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xb7958 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0xb7960 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0xb7960 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb7970 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0xb7988 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0xb7a38 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0xb7a48 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI28LiveviewCalibrationDataAsyncE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0xb7d18 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI29LiveviewCalibrationDataLoaderE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0xb7e00 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN3x2d22StateExposureMultiShotEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0xca6d8 | 60 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0xcb5d8 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0xcb5d8 | 452 |
| `_ZN28LiveviewCalibrationDataAsyncC1EP7QObject` | 0xd0018 | 84 |
| `_ZN28LiveviewCalibrationDataAsyncC2EP7QObject` | 0xd0018 | 84 |
| `_ZN28LiveviewCalibrationDataAsync4initEv` | 0xd0070 | 496 |
| `_ZN28LiveviewCalibrationDataAsyncD1Ev` | 0xd0260 | 728 |
| `_ZN28LiveviewCalibrationDataAsyncD2Ev` | 0xd0260 | 728 |
| `_ZN28LiveviewCalibrationDataAsyncD0Ev` | 0xd0538 | 36 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN28LiveviewCalibrationDataAsync4initEvE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xd0560 | 36 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN28LiveviewCalibrationDataAsync4initEvE3$_1Li1ENS_4ListIJNSt3__110shared_ptrI12DussMemShareEEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xd0588 | 516 |
| `_ZN29LiveviewCalibrationDataLoaderC1EP7QObject` | 0xd0790 | 52 |

<details><summary>… 另 330 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN29LiveviewCalibrationDataLoaderC2EP7QObject` | 0xd0790 | 52 |
| `_ZN29LiveviewCalibrationDataLoader5startEv` | 0xd07c8 | 840 |
| `_ZN29LiveviewCalibrationDataLoader4loadERK7QString` | 0xd0b10 | 1200 |
| `_ZN29LiveviewCalibrationDataLoader17allocateIonBufferEj` | 0xd0fc0 | 408 |
| `_ZN5QHashIN9HblmTypes15E_MultiShotModeEiED2Ev` | 0x119d58 | 176 |
| `_ZN3x2d29StateCaptureMultiShotExposureC1EP6QState` | 0x12a3d8 | 2120 |
| `_ZN3x2d29StateCaptureMultiShotExposureC2EP6QState` | 0x12a3d8 | 2120 |
| `_ZN3x2d29StateCaptureMultiShotExposure10onHblEntryEP6QEvent` | 0x12c668 | 44 |
| `_ZN3x2d29StateCaptureMultiShotExposure9onHblExitEP6QEvent` | 0x12c698 | 420 |
| `_ZN3x2d29StateCaptureMultiShotExposure17exposureMultiShotEv` | 0x12c840 | 488 |
| `_ZN3x2d22StateExposureMultiShot10onHblEntryEP6QEvent` | 0x137fe8 | 232 |
| `_ZN5QHashIN9HblmTypes15E_MultiShotModeEiE7emplaceIJRKiEEENS2_8iteratorEOS1_DpOT_` | 0x13d058 | 720 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_MultiShotModeEiEEE12findOrInsertERKS3_` | 0x13d328 | 604 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_MultiShotModeEiEEE6rehashEm` | 0x13d588 | 724 |
| `_ZN12QHashPrivate4SpanINS_4NodeIN9HblmTypes15E_MultiShotModeEiEEE10addStorageEv` | 0x13d860 | 248 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_MultiShotModeEiEEE8detachedEPS5_` | 0x13d958 | 308 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_MultiShotModeEiEEEC2ERKS5_` | 0x13da90 | 424 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13e2e0 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13e308 | 16 |
| `_ZNSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEclESD_` | 0x13e318 | 504 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13e510 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13e530 | 12 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13ed38 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13ed60 | 16 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13ed70 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13ed90 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d29StateCaptureMultiShotExposureC1EP6QStateE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13f270 | 240 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d17StateExposureInit23onCheckReadyForExposureEvE3$_6Li1ENS_4ListIJN9HblmTypes14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13f3d8 | 644 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d17StateExposureInit10onHblEntryEP6QEventE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13f660 | 356 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13f7c8 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13f7f0 | 16 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13f800 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13f820 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d20StateExposurePrepareC1EP6QStateE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13f9b8 | 1496 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d11StateAfIdleC1EPNS1_15StateSequenceAFEE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x140730 | 676 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d11StateAfBaseC1EPNS1_15StateSequenceAFEE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x140c40 | 1176 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d23StateGroupIntervalDelay10onHblEntryEP6QEventE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1418a0 | 608 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d20StateFocusBracketingC1EP6QStateE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x141bf8 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x141e10 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x141e38 | 16 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x141e48 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x141e68 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d22StateGroupInitialDelayC1EP6QStateE4$_14Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x141fe8 | 40 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d18StateLightmeteringC1EP6QStateE4$_15Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x142180 | 400 |
| `_ZNK16CameraObjectImpl15isMultiShotModeEv` | 0x188788 | 204 |
| `_ZN16CameraObjectImpl31setEnabled_face_detection_modesEN9HblmTypes15E_FaceDetectionE` | 0x18a020 | 1268 |
| `_ZNK16CameraObjectImpl28enabled_face_detection_modesEv` | 0x18a518 | 8 |
| `_ZNK16CameraObjectImpl34sessionMultiShotBlackshotRequestedEv` | 0x18aa38 | 140 |
| `_ZN16CameraObjectImpl25setMultishot_control_modeEN9HblmTypes15E_MultiShotModeE` | 0x18b540 | 96 |
| `_ZNK16CameraObjectImpl22multishot_control_modeEv` | 0x18b5a0 | 8 |
| `_ZN16CameraObjectImpl23setFlash_recharge_delayEi` | 0x18b5a8 | 92 |
| `_ZNK16CameraObjectImpl20flash_recharge_delayEv` | 0x18b608 | 8 |
| `_ZN16CameraObjectImpl33setExposures_in_multishot_sessionEi` | 0x18b660 | 68 |
| `_ZNK16CameraObjectImpl30exposures_in_multishot_sessionEv` | 0x18b6a8 | 8 |
| `_ZNK16CameraObjectImpl30allSupportedFaceDetectionModesEv` | 0x18be08 | 320 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_121Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19f728 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_122Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19fe68 | 52 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_123Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19ff20 | 148 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_124Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a0128 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_127Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a02e0 | 200 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_128Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a0428 | 108 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_129Li2ENS_4ListIJN9HblmTypes12E_DCAMStreamEbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a0518 | 84 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_130Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a05f0 | 88 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_131Li2ENS_4ListIJjRK5QListI8FaceInfoEEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a06c8 | 224 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_135Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a0aa8 | 96 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_136Li1ENS_4ListIJN9HblmTypes14E_CameraModuleEEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a0b08 | 156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_137Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x1a0ba8 | 256 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_138Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a0d20 | 56 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_139Li1ENS_4ListIJRKN16IbisMessageTypes7ImuDataEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a0d58 | 156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_140Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a0ff8 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_141Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1048 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_144Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1450 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_145Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1520 | 96 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_146Li1ENS_4ListIJN9HblmTypes21E_ExposureBlockReasonEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1600 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_147Li1ENS_4ListIJN9HblmTypes15E_AfBlockReasonEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1630 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_153Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1a58 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_154Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1d68 | 864 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl30updateFaceDetectionFocusRegionEvE5$_155Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a20c8 | 248 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEE5$_165Li1ENS_4ListIJNS2_14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a2958 | 1472 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEENK5$_165clENS2_14E_ReturnStatusEEUlSD_E_Li1ENS_4ListIJSD_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a2f18 | 896 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEE5$_166Li1ENS_4ListIJNS2_14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a3298 | 2352 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEENK5$_166clENS2_14E_ReturnStatusEEUlSD_E_Li1ENS_4ListIJSD_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a3bc8 | 828 |
| `_ZNSt3__16__sortIRZN16CameraObjectImpl33loadCalibrationLiveviewSpotPixelsEvE5$_167PZNS1_33loadCalibrationLiveviewSpotPixelsEvE17HighContrastPixelEEvT0_S6_T_` | 0x1a40a8 | 2756 |
| `_ZNSt3__17__sort4IRZN16CameraObjectImpl33loadCalibrationLiveviewSpotPixelsEvE5$_167PZNS1_33loadCalibrationLiveviewSpotPixelsEvE17HighContrastPixelEEjT0_S6_S6_S6_T_` | 0x1a4b70 | 544 |
| `_ZNSt3__127__insertion_sort_incompleteIRZN16CameraObjectImpl33loadCalibrationLiveviewSpotPixelsEvE5$_167PZNS1_33loadCalibrationLiveviewSpotPixelsEvE17HighContrastPixelEEbT0_S6_T_` | 0x1a4d90 | 1252 |
| `_ZN9QtPrivate24printSequentialContainerI5QListIN9HblmTypes15E_FaceDetectionEEEE6QDebugS5_PKcRKT_` | 0x1a56f0 | 492 |
| `_ZN17QArrayDataPointerIN9HblmTypes15E_FaceDetectionEE20tryReadjustFreeSpaceEN10QArrayData14GrowthPositionExPPKS1_` | 0x1a6260 | 292 |
| `_ZN17QArrayDataPointerIN9HblmTypes15E_FaceDetectionEE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x1a6388 | 456 |
| `_ZN17QArrayDataPointerIN9HblmTypes15E_FaceDetectionEE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0x1a6550 | 368 |
| `_ZN9QtPrivate12QPodArrayOpsIN9HblmTypes15E_FaceDetectionEE7emplaceIJRS2_EEEvxDpOT_` | 0x1a66c0 | 420 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl23doDo_exposure_extended2EbN9HblmTypes16E_SessionOptionsEiRK12QDBusMessageE5$_172Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a6868 | 604 |
| `_ZNK20LensControlInterface21extensionTubeDetectedEv` | 0x1b6ed8 | 8 |
| `_ZN11IbisControl20setMultiShotPositionEN9HblmTypes15E_MultiShotModeEj` | 0x1bcb70 | 336 |
| `_ZN11IbisControl15setMovePositionEif` | 0x1bccc0 | 1116 |
| `_ZN11IbisControl20readIbisDisplacementEv` | 0x1c2788 | 632 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl15setMovePositionEifE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c4090 | 664 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl6resumeEvE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c4328 | 1300 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl7suspendEvE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c4840 | 900 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl17setImuStreamStateEbiE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c4bc8 | 700 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl21startIbisStatusStreamERK14QSharedPointerI19MessageNotificationEE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c4e88 | 1072 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl20stopIbisStatusStreamEvE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c52b8 | 656 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl15prepareIbisModeEvE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c5940 | 740 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl25prepareIbisBeforeExposureEvE4$_14Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c5c28 | 572 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl28requestIbisCalibrationStatusEvE4$_15Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c5e68 | 2664 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl20readIbisDisplacementEvE4$_17Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c68d0 | 1780 |
| `_ZN17DCAMCaptureEngine31reloadLiveviewZoomSpotPixelDataEv` | 0x1e5518 | 16 |
| `_ZN24DCAMCaptureEnginePrivate28_initLiveviewCalibrationDataEv` | 0x1f5888 | 284 |
| `_ZN24DCAMCaptureEnginePrivate18waitUntilZoomReadyEi` | 0x1fb260 | 628 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringED2Ev` | 0x216a50 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringED2Ev` | 0x216a50 | 88 |
| `_ZN24DCAMCaptureEnginePrivate31reloadLiveviewZoomSpotPixelDataEv` | 0x218c18 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate11_initCapEngEvEN3$_38__invokeEP14looper_handlermmm` | 0x218e38 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate11_initCapEngEvEN4$_338__invokeEPvjPKvj` | 0x219aa8 | 144 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_35JEE10runFunctorEv` | 0x219b38 | 980 |
| `_ZZN24DCAMCaptureEnginePrivate8_initEcgEvEN4$_578__invokeEPvP19cam_ecg_status_info` | 0x219f10 | 24 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_388__invokeEP19cam_stream_consumerPvP16cam_frame_buffer` | 0x219f28 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_398__invokeEP19cam_stream_consumerP14dcam_containerS6_Pv` | 0x219f38 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_408__invokeEP19cam_stream_consumerPv` | 0x219f48 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_418__invokeEP19cam_stream_consumerPvP16cam_frame_buffer` | 0x219f50 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_428__invokeEP19cam_stream_consumerPvP16cam_frame_buffer` | 0x219f60 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_438__invokeEPv` | 0x219f70 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_448__invokeEPv14cam_cap_result` | 0x219f78 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_458__invokeEPvP40capeng_capture_result_metadata_collector` | 0x219f80 | 24 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_468__invokeEPv` | 0x219f98 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_478__invokeEPvP21capeng_captured_image` | 0x219fa0 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate23doStartReprocessSessionEN9HblmTypes13E_StreamGroupEEN4$_488__invokeEPvP16cam_frame_bufferh` | 0x21a380 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate23doStartReprocessSessionEN9HblmTypes13E_StreamGroupEEN4$_498__invokeEPvP21capeng_captured_image` | 0x21a388 | 8 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x21a650 | 108 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x21a650 | 108 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate28_initLiveviewCalibrationDataEvE3$_2Li1ENS_4ListIJNSt3__110shared_ptrI12DussMemShareEEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x21b3e0 | 348 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE7__cloneEv` | 0x21b640 | 36 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE7__cloneEPNS0_6__baseISC_EE` | 0x21b668 | 16 |
| `_ZNSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEclEOS6_SB_` | 0x21b678 | 12 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE6targetERKSt9type_info` | 0x21b688 | 28 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE11target_typeEv` | 0x21b6a8 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_36Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x21b6b8 | 564 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate18initUserspaceInputEvE4$_50Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x21cdf0 | 528 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate27createEncodedLiveviewHeaderERKNSt3__110shared_ptrI6BufferEEE4$_51Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x21d000 | 580 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x21e478 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x21e478 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x21e570 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x21e570 | 248 |
| `_ZNSt3__16__sortIRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_56PS4_EEvT0_SB_T_` | 0x21e9b0 | 1568 |
| `_ZNSt3__17__sort3IRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_56PS4_EEjT0_SB_SB_T_` | 0x21efd0 | 420 |
| `_ZNSt3__17__sort4IRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_56PS4_EEjT0_SB_SB_SB_T_` | 0x21f178 | 308 |
| `_ZNSt3__17__sort5IRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_56PS4_EEjT0_SB_SB_SB_SB_T_` | 0x21f2b0 | 400 |
| `_ZNSt3__127__insertion_sort_incompleteIRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_56PS4_EEbT0_SB_T_` | 0x21f440 | 516 |
| `_ZN11LensControl21onExtensionTubeStatusEi` | 0x2325a0 | 84 |
| `_ZN4Ibis20readIbisDisplacementEv` | 0x24de40 | 212 |
| `_ZN4Ibis17setMoveParametersERK18IbisMoveParameters` | 0x24e4a8 | 216 |
| `_ZN15IbisMoveMessageC1ERK18IbisMoveParameters` | 0x253b40 | 400 |
| `_ZN15IbisMoveMessageC2ERK18IbisMoveParameters` | 0x253b40 | 400 |
| `_ZN15IbisMoveMessageD0Ev` | 0x253fb8 | 152 |
| `_ZN18IbisResponseParser26parseMoveParameterResponseERK14QSharedPointerI11IbisRequestERb` | 0x254608 | 268 |
| `_ZN18IbisResponseParser23parseSensorDisplacementERK14QSharedPointerI11IbisRequestERN16IbisMessageTypes20displacementResponseE` | 0x254718 | 1076 |
| `_ZN13CalibSbpcZoom19readZoomBinFromDiskERK7QStringPcj` | 0x266440 | 1356 |
| `_ZN9DussEvent6handleEv` | 0x269ff0 | 64 |
| `_ZN9DussEvent6msgBufEv` | 0x26a050 | 68 |
| `_ZN12CameraObject35enabled_face_detection_modesChangedEN9HblmTypes15E_FaceDetectionE` | 0x28ef98 | 96 |
| `_ZN12CameraObject37exposures_in_multishot_sessionChangedEi` | 0x28f680 | 96 |
| `_ZN12CameraObject27flash_recharge_delayChangedEi` | 0x28f990 | 96 |
| `_ZN12CameraObject29multishot_control_modeChangedEN9HblmTypes15E_MultiShotModeE` | 0x2917b8 | 96 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x29e2a8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x29e340 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x29e348 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x29e4c8 | 200 |
| `_ZN12CameraObject32_setEnabled_face_detection_modesEi` | 0x2c0c28 | 12 |
| `_ZNK12CameraObject29_enabled_face_detection_modesEv` | 0x2c0c38 | 32 |
| `_ZN12CameraObject26_setMultishot_control_modeEi` | 0x2c12e8 | 12 |
| `_ZNK12CameraObject23_multishot_control_modeEv` | 0x2c12f8 | 32 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_73Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3790 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_74Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c37c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_75Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c37f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_77Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3850 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_78Li1ENS_4ListIJN9HblmTypes12E_DriveModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3880 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_79Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c38b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_80Li1ENS_4ListIJN9HblmTypes9E_ExpModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c38e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_81Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3910 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_82Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3940 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_83Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3970 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_85Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c39d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_86Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3a00 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_87Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3a30 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_88Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3a60 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_89Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3a90 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_90Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3ac0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_91Li1ENS_4ListIJN9HblmTypes16E_ExposureStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3af0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_92Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3b20 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_93Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3b50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_94Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3b80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_95Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3bb0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_96Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3be0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_98Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3c40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_100Li1ENS_4ListIJN9HblmTypes12E_FlashModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3ca0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_105Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3d90 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_106Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3dc0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_107Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3df0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_108Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3e20 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_109Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3e50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_110Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3e80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_111Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3eb0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_112Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3ee0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_113Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3f10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_114Li1ENS_4ListIJN9HblmTypes12E_FocusModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3f40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_115Li1ENS_4ListIJN9HblmTypes19E_FocusPeakingColorEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3f70 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_117Li1ENS_4ListIJN9HblmTypes21E_FocusPointResetModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c3fd0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_118Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4000 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_119Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4030 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_120Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4060 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_121Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4090 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_122Li1ENS_4ListIJN9HblmTypes17E_CameraKeyOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c40c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_123Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c40f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_125Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4150 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_126Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4180 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_127Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c41b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_128Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c41e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_129Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4210 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_132Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c42a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_133Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c42d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_134Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4300 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_135Li1ENS_4ListIJN9HblmTypes10E_IbisModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4330 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_136Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4360 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_137Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4390 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_138Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c43c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_139Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c43f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_140Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4420 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_141Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4450 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_142Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4480 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_143Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c44b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_144Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c44e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_146Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4540 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_147Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4570 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_149Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c45d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_150Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4600 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_151Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4630 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_152Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4660 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_153Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4690 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_154Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c46c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_155Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c46f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_156Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4720 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_157Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4750 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_158Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4780 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_159Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c47b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_160Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c47e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_161Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4810 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_163Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4870 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_164Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c48a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_165Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c48d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_166Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4900 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_167Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4930 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_168Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4960 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_169Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4990 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_171Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c49f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_173Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4a50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_174Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4a80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_175Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4ab0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_177Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4b10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_178Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4b40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_179Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4b70 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_180Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4ba0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_181Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4bd0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_182Li1ENS_4ListIJN9HblmTypes15E_LiveViewStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4c00 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_183Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4c30 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_184Li1ENS_4ListIJRK10QByteArrayEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4c60 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_185Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4c90 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_186Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4cc0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_187Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4cf0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_188Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4d20 | 40 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_189Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4d48 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_191Li1ENS_4ListIJN9HblmTypes23E_LiveviewTransportModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4da8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_192Li1ENS_4ListIJN9HblmTypes9E_LmModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4dd8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_193Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4e08 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_194Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4e38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_195Li1ENS_4ListIJN9HblmTypes19E_ManualFocusAssistEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4e68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_196Li1ENS_4ListIJN9HblmTypes13E_MaxApertureEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4e98 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_197Li1ENS_4ListIJN9HblmTypes15E_MultiShotModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4ec8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_198Li1ENS_4ListIJN9HblmTypes13E_FlashStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4ef8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_199Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4f28 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_200Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4f58 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_201Li1ENS_4ListIJN9HblmTypes16E_OptionOverrideEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c4f88 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_205Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5048 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_206Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5078 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_207Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c50a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_208Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c50d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_209Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5108 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_210Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5138 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_211Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5168 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_212Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5198 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_213Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c51c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_215Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5228 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_217Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5288 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_218Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c52b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_219Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c52e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_222Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5378 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_223Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c53a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_224Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c53d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_225Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5408 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_226Li1ENS_4ListIJN9HblmTypes14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5438 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_227Li1ENS_4ListIJN9HblmTypes16E_StopDownStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5468 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_228Li1ENS_4ListIJN9HblmTypes13E_StreamGroupEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5498 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_229Li1ENS_4ListIJN9HblmTypes18E_SensorUnitStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c54c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_233Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5588 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_234Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c55b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_237Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5648 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_238Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5678 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_240Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c56d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_241Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5708 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_242Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5738 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_243Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5768 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_244Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5798 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_245Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c57c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_246Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c57f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_247Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5828 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_248Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5858 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_249Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5888 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_252Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5918 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_255Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c59a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_256Li1ENS_4ListIJN9HblmTypes12E_WhiteModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c59d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_257Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5a08 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_258Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5a38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_259Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5a68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_260Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5a98 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_261Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5ac8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_262Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2c5af8 | 44 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringE6insertERKS1_RKS2_` | 0x2c8ba0 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage7MetaTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x2c8d28 | 392 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringE6insertERKS1_RKS2_` | 0x2c8eb0 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage10StorageTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x2c9038 | 392 |
| `_ZN16SnapshotMetadata18setMultiShotImagesEi` | 0x2ccef8 | 8 |
| `_ZN16SnapshotMetadata20setMultiShotSequenceEi` | 0x2ccf00 | 8 |

</details>

**Removed functions (255)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QSignalTransitionC2IM12CameraObjectFvN9HblmTypes13E_ImageFormatEEEEPKN9QtPrivate15FunctionPointerIT_E6ObjectES8_P6QState` | 0xd6598 | 256 |
| `_ZN18StateGroupLiveview21onEnabledImageFormatsEv` | 0xd6698 | 944 |
| `_ZNK19ICameraStateMachine24isEncodedLiveviewAllowedEv` | 0x102120 | 764 |
| `_ZN5QHashIN9HblmTypes13E_ImageFormatE15QHashDummyValueE7emplaceIJRKS2_EEENS3_8iteratorEOS1_DpOT_` | 0x10ab10 | 564 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes13E_ImageFormatE15QHashDummyValueEEE12findOrInsertERKS3_` | 0x10ad48 | 592 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes13E_ImageFormatE15QHashDummyValueEEE6rehashEm` | 0x10af98 | 716 |
| `_ZN12QHashPrivate4SpanINS_4NodeIN9HblmTypes13E_ImageFormatE15QHashDummyValueEEE10addStorageEv` | 0x10b268 | 428 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes13E_ImageFormatE15QHashDummyValueEEE8detachedEPS6_` | 0x10b418 | 308 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes13E_ImageFormatE15QHashDummyValueEEEC2ERKS6_` | 0x10b550 | 420 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13aec0 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13aee8 | 16 |
| `_ZNSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEclESD_` | 0x13aef8 | 504 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13b0f0 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13b110 | 12 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13b918 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13b940 | 16 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13b950 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13b970 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d17StateExposureInit23onCheckReadyForExposureEvE3$_5Li1ENS_4ListIJN9HblmTypes14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13bec8 | 644 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d17StateExposureInit10onHblEntryEP6QEventE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13c150 | 356 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13c2b8 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13c2e0 | 16 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13c2f0 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13c310 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d20StateExposurePrepareC1EP6QStateE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13c320 | 388 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d11StateAfIdleC1EPNS1_15StateSequenceAFEE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13d220 | 676 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d11StateAfBaseC1EPNS1_15StateSequenceAFEE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13d730 | 1176 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d23StateGroupIntervalDelay10onHblEntryEP6QEventE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13e390 | 608 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d20StateFocusBracketingC1EP6QStateE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13e6e8 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEv` | 0x13e900 | 36 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE7__cloneEPNS0_6__baseISE_EE` | 0x13e928 | 16 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE6targetERKSt9type_info` | 0x13e938 | 28 |
| `_ZNKSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEE11target_typeEv` | 0x13e958 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d22StateGroupInitialDelayC1EP6QStateE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13ead8 | 40 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN3x2d18StateLightmeteringC1EP6QStateE4$_14Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13ec70 | 400 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_121Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19b8b8 | 52 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_122Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19b970 | 148 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_123Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19bb78 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_124Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19bba8 | 200 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_127Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19be78 | 108 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_128Li2ENS_4ListIJN9HblmTypes12E_DCAMStreamEbEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19bf68 | 84 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_129Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19c040 | 88 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_130Li2ENS_4ListIJjRK5QListI8FaceInfoEEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19c118 | 224 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_131Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19c378 | 92 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImplC1ERKNSt3__110shared_ptrI18IDCAMCaptureEngineEERKNS3_I21InputControlInterfaceEERKNS3_I11IbisControlEERKNS3_I28VBodyCaptureServiceInterfaceEERKNS3_I21AudioControlInterfaceEENS3_I10IMLControlEEbP7QObjectE5$_135Li1ENS_4ListIJN9HblmTypes14E_CameraModuleEEEEvE4implEiPNS_15QSlotObjectBaseESR_PPvPb` | 0x19c558 | 156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_136Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19c670 | 56 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_137Li1ENS_4ListIJRKN16IbisMessageTypes7ImuDataEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19c6a8 | 156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_138Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19c948 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl11connectIbisEvE5$_139Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19c998 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_141Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19ca60 | 700 |

<details><summary>… 另 205 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_142Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19cda0 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_144Li1ENS_4ListIJN9HblmTypes21E_ExposureBlockReasonEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19cf50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_145Li1ENS_4ListIJN9HblmTypes15E_AfBlockReasonEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19cf80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_146Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19cfb0 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl9assignFsmENSt3__110unique_ptrI19ICameraStateMachineNS2_14default_deleteIS4_EEEEE5$_147Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19d000 | 180 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl30updateFaceDetectionFocusRegionEvE5$_153Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19da18 | 248 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEE5$_163Li1ENS_4ListIJNS2_14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19e2a8 | 1472 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEENK5$_163clENS2_14E_ReturnStatusEEUlSD_E_Li1ENS_4ListIJSD_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19e868 | 896 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEE5$_164Li1ENS_4ListIJNS2_14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19ebe8 | 2352 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN16CameraObjectImpl18captureStreamFrameEN9HblmTypes13E_StreamGroupENS2_12E_DCAMStreamEj14QSharedPointerI11ImageMemoryERKS5_I19MessageNotificationEENK5$_164clENS2_14E_ReturnStatusEEUlSD_E_Li1ENS_4ListIJSD_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x19f518 | 828 |
| `_ZNSt3__16__sortIRZN16CameraObjectImpl33loadCalibrationLiveviewSpotPixelsEvE5$_165PZNS1_33loadCalibrationLiveviewSpotPixelsEvE17HighContrastPixelEEvT0_S6_T_` | 0x19f9f8 | 2756 |
| `_ZNSt3__17__sort4IRZN16CameraObjectImpl33loadCalibrationLiveviewSpotPixelsEvE5$_165PZNS1_33loadCalibrationLiveviewSpotPixelsEvE17HighContrastPixelEEjT0_S6_S6_S6_T_` | 0x1a04c0 | 544 |
| `_ZNSt3__127__insertion_sort_incompleteIRZN16CameraObjectImpl33loadCalibrationLiveviewSpotPixelsEvE5$_165PZNS1_33loadCalibrationLiveviewSpotPixelsEvE17HighContrastPixelEEbT0_S6_T_` | 0x1a06e0 | 1252 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16CameraObjectImpl23doDo_exposure_extended2EbN9HblmTypes16E_SessionOptionsEiRK12QDBusMessageE5$_170Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1a1e20 | 604 |
| `_ZN11IbisControl19setShadingCorrectedEv` | 0x1b5f60 | 888 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl6resumeEvE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1bf178 | 1300 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl7suspendEvE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1bf690 | 900 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl17setImuStreamStateEbiE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1bfa18 | 700 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl21startIbisStatusStreamERK14QSharedPointerI19MessageNotificationEE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1bfcd8 | 1072 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl20stopIbisStatusStreamEvE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c0108 | 656 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl15prepareIbisModeEvE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c0790 | 740 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl25prepareIbisBeforeExposureEvE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c0a78 | 572 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11IbisControl28requestIbisCalibrationStatusEvE4$_14Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1c0cb8 | 2664 |
| `_ZN5QHashIN9HblmTypes13E_StreamGroupEN12_GLOBAL__N_117FrogReprocessInfoEED2Ev` | 0x1edfc0 | 176 |
| `_ZZN24DCAMCaptureEnginePrivate11_initCapEngEvEN3$_28__invokeEP14looper_handlermmm` | 0x212ea8 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate11_initCapEngEvEN3$_38__invokeEPvjPKvj` | 0x212eb0 | 8 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_34JEE10runFunctorEv` | 0x213ba8 | 980 |
| `_ZZN24DCAMCaptureEnginePrivate8_initEcgEvEN4$_558__invokeEPvP19cam_ecg_status_info` | 0x213f80 | 24 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_368__invokeEP19cam_stream_consumerPvP16cam_frame_buffer` | 0x213f98 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_378__invokeEP19cam_stream_consumerP14dcam_containerS6_Pv` | 0x213fa8 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_388__invokeEP19cam_stream_consumerPv` | 0x213fb8 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_398__invokeEP19cam_stream_consumerPvP16cam_frame_buffer` | 0x213fc0 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate18doSetupStreamGroupEN9HblmTypes13E_StreamGroupEEN4$_408__invokeEP19cam_stream_consumerPvP16cam_frame_buffer` | 0x213fd0 | 12 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_418__invokeEPv` | 0x213fe0 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_428__invokeEPv14cam_cap_result` | 0x213fe8 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_438__invokeEPvP40capeng_capture_result_metadata_collector` | 0x213ff0 | 24 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_448__invokeEPv` | 0x214008 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate21doUpdateCaptureParamsEN9HblmTypes13E_ImageFormatEEN4$_458__invokeEPvP21capeng_captured_image` | 0x214010 | 4 |
| `_ZZN24DCAMCaptureEnginePrivate23doStartReprocessSessionEN9HblmTypes13E_StreamGroupEEN4$_468__invokeEPvP16cam_frame_bufferh` | 0x2143f0 | 8 |
| `_ZZN24DCAMCaptureEnginePrivate23doStartReprocessSessionEN9HblmTypes13E_StreamGroupEEN4$_478__invokeEPvP21capeng_captured_image` | 0x2143f8 | 8 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE7__cloneEv` | 0x215550 | 36 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE7__cloneEPNS0_6__baseISC_EE` | 0x215578 | 16 |
| `_ZNSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEclEOS6_SB_` | 0x215588 | 12 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE6targetERKSt9type_info` | 0x215598 | 28 |
| `_ZNKSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEE11target_typeEv` | 0x2155b8 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_35Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x2155c8 | 564 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate18initUserspaceInputEvE4$_48Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x216d00 | 528 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN24DCAMCaptureEnginePrivate27createEncodedLiveviewHeaderERKNSt3__110shared_ptrI6BufferEEE4$_49Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x216f10 | 580 |
| `_ZNSt3__16__sortIRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_54PS4_EEvT0_SB_T_` | 0x2188c0 | 1568 |
| `_ZNSt3__17__sort3IRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_54PS4_EEjT0_SB_SB_T_` | 0x218ee0 | 420 |
| `_ZNSt3__17__sort4IRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_54PS4_EEjT0_SB_SB_SB_T_` | 0x219088 | 308 |
| `_ZNSt3__17__sort5IRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_54PS4_EEjT0_SB_SB_SB_SB_T_` | 0x2191c0 | 400 |
| `_ZNSt3__127__insertion_sort_incompleteIRZN24DCAMCaptureEnginePrivate27setCalibrationSpotPixelDataENS_6vectorINS_4pairIiiEENS_9allocatorIS4_EEEEE4$_54PS4_EEbT0_SB_T_` | 0x219350 | 516 |
| `_ZNK22LensConstantsInterface17shadingCorrectionEi` | 0x2550c0 | 20 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_73Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc198 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_74Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc1c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_75Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc1f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_77Li1ENS_4ListIJN9HblmTypes12E_DriveModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc258 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_78Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc288 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_79Li1ENS_4ListIJN9HblmTypes9E_ExpModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc2b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_80Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc2e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_81Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc318 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_82Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc348 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_83Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc378 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_85Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc3d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_86Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc408 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_87Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc438 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_88Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc468 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_89Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc498 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_90Li1ENS_4ListIJN9HblmTypes16E_ExposureStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc4c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_91Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc4f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_92Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc528 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_93Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc558 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_94Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc588 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_95Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc5b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_96Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc5e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE4$_98Li1ENS_4ListIJN9HblmTypes12E_FlashModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc648 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_100Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc6a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_105Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc798 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_106Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc7c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_107Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc7f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_108Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc828 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_109Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc858 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_110Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc888 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_111Li1ENS_4ListIJN9HblmTypes12E_FocusModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc8b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_112Li1ENS_4ListIJN9HblmTypes19E_FocusPeakingColorEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc8e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_113Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc918 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_114Li1ENS_4ListIJN9HblmTypes21E_FocusPointResetModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc948 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_115Li1ENS_4ListIJRK4QMapI7QString8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc978 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_117Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bc9d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_118Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bca08 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_119Li1ENS_4ListIJN9HblmTypes17E_CameraKeyOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bca38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_120Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bca68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_121Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bca98 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_122Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcac8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_123Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcaf8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_125Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcb58 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_126Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcb88 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_127Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcbb8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_128Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcbe8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_129Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcc18 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_132Li1ENS_4ListIJN9HblmTypes10E_IbisModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcca8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_133Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bccd8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_134Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcd08 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_135Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcd38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_136Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcd68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_137Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcd98 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_138Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcdc8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_139Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcdf8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_140Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bce28 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_141Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bce58 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_142Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bce88 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_143Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bceb8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_144Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcee8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_146Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcf48 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_147Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcf78 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_149Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bcfd8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_150Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd008 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_151Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd038 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_152Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd068 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_153Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd098 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_154Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd0c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_155Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd0f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_156Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd128 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_157Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd158 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_158Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd188 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_159Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd1b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_160Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd1e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_161Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd218 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_163Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd278 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_164Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd2a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_165Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd2d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_166Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd308 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_167Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd338 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_168Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd368 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_169Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd398 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_171Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd3f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_173Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd458 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_174Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd488 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_175Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd4b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_177Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd518 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_178Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd548 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_179Li1ENS_4ListIJN9HblmTypes15E_LiveViewStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd578 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_180Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd5a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_181Li1ENS_4ListIJRK10QByteArrayEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd5d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_182Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd608 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_183Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd638 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_184Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd668 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_185Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd698 | 40 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_186Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd6c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_187Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd6f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_188Li1ENS_4ListIJN9HblmTypes23E_LiveviewTransportModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd720 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_189Li1ENS_4ListIJN9HblmTypes9E_LmModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd750 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_191Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd7b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_192Li1ENS_4ListIJN9HblmTypes19E_ManualFocusAssistEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd7e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_193Li1ENS_4ListIJN9HblmTypes13E_MaxApertureEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd810 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_194Li1ENS_4ListIJN9HblmTypes13E_FlashStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd840 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_195Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd870 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_196Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd8a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_197Li1ENS_4ListIJN9HblmTypes16E_OptionOverrideEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd8d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_198Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd900 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_199Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd930 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_200Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd960 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_201Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bd990 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_205Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bda50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_206Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bda80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_207Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdab0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_208Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdae0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_209Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdb10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_210Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdb40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_211Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdb70 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_212Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdba0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_213Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdbd0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_215Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdc30 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_217Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdc90 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_218Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdcc0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_219Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdcf0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_222Li1ENS_4ListIJN9HblmTypes14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdd80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_223Li1ENS_4ListIJN9HblmTypes16E_StopDownStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bddb0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_224Li1ENS_4ListIJN9HblmTypes13E_StreamGroupEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdde0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_225Li1ENS_4ListIJN9HblmTypes18E_SensorUnitStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bde10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_226Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bde40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_227Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bde70 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_228Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdea0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_229Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bded0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_233Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdf90 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_234Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2bdfc0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_237Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be050 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_238Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be080 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_240Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be0e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_241Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be110 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_242Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be140 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_243Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be170 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_244Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be1a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_245Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be1d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_246Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be200 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_247Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be230 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_248Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be260 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_249Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be290 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_252Li1ENS_4ListIJN9HblmTypes12E_WhiteModesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be320 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_255Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be3b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_256Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be3e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_257Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be410 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12CameraObjectC1EP7QObjectbE5$_258Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x2be440 | 44 |
| `_ZN16SnapshotMetadata19setShadingCorrectedEi` | 0x2c50a0 | 8 |

</details>

**New objects (93)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12_GLOBAL__N_147qt_meta_stringdata_LiveviewCalibrationDataAsyncE` | 0x5d7380 | 104 |
| `_ZL41qt_meta_data_LiveviewCalibrationDataAsync` | 0x5d73e8 | 96 |
| `_ZN12_GLOBAL__N_148qt_meta_stringdata_LiveviewCalibrationDataLoaderE` | 0x5d7448 | 108 |
| `_ZL42qt_meta_data_LiveviewCalibrationDataLoader` | 0x5d74b4 | 96 |
| `_ZN12_GLOBAL__N_153qt_meta_stringdata_x2d__StateCaptureMultiShotExposureE` | 0x5e42b0 | 44 |
| `_ZN12_GLOBAL__N_146qt_meta_stringdata_x2d__StateExposureMultiShotE` | 0x5e45b0 | 36 |
| `_ZTS28LiveviewCalibrationDataAsync` | 0x5e4c23 | 31 |
| `_ZTS29LiveviewCalibrationDataLoader` | 0x5e4c42 | 32 |
| `_ZTSN3x2d29StateCaptureMultiShotExposureE` | 0x5e55c2 | 38 |
| `_ZTSN3x2d22StateExposureMultiShotE` | 0x5e57de | 31 |
| `_ZN9QtPrivate16QMetaTypeForTypeI28LiveviewCalibrationDataAsyncE4nameE` | 0x5e5acf | 29 |
| `_ZN9QtPrivate16QMetaTypeForTypeI29LiveviewCalibrationDataLoaderE4nameE` | 0x5e5b0f | 30 |
| `_ZL47qt_meta_data_x2d__StateCaptureMultiShotExposure` | 0x5e8a3c | 60 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN3x2d29StateCaptureMultiShotExposureEE4nameE` | 0x5e8a78 | 35 |
| `_ZL40qt_meta_data_x2d__StateExposureMultiShot` | 0x5e9034 | 60 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN3x2d22StateExposureMultiShotEE4nameE` | 0x5e9070 | 28 |
| `_ZTSNSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x5ec7f6 | 123 |
| `_ZTSZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16` | 0x5ec871 | 53 |
| `_ZTSNSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x5ec8a6 | 121 |
| `_ZTSZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17` | 0x5ec91f | 51 |
| `_ZTSNSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x5ec952 | 116 |
| `_ZTSZN3x2d20StateExposurePrepareC1EP6QStateE4$_18` | 0x5ec9c6 | 46 |
| `_ZTSNSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x5ecb30 | 117 |
| `_ZTSZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19` | 0x5ecba5 | 47 |
| `_ZN12_GLOBAL__N_113kOffsets4shotE` | 0x5ee6f8 | 32 |
| `_ZN12_GLOBAL__N_113kOffsets6shotE` | 0x5ee758 | 48 |
| `_ZN12_GLOBAL__N_114kOffsets16shotE` | 0x5ee788 | 128 |
| `_ZN12_GLOBAL__N_118kOffsets4shotblackE` | 0x5ee808 | 40 |
| `_ZN12_GLOBAL__N_118kOffsets6shotblackE` | 0x5ee830 | 56 |
| `_ZN12_GLOBAL__N_119kOffsets16shotblackE` | 0x5ee868 | 136 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_35JEEE` | 0x5effbe | 86 |
| `_ZTSNSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE` | 0x5f0057 | 126 |
| `_ZTSZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34` | 0x5f0113 | 46 |
| `_ZTS15IbisMoveMessage` | 0x5f10c2 | 18 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x606071 | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_149qt_meta_stringdata_LiveviewCalibrationDataAsync_tEJN9QtPrivate20TypeAndForceCompleteI28LiveviewCalibrationDataAsyncNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_INS5_10shared_ptrI12DussMemShareEES9_EEEE` | 0x7996c8 | 24 |
| `_ZN28LiveviewCalibrationDataAsync16staticMetaObjectE` | 0x7996e0 | 56 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_150qt_meta_stringdata_LiveviewCalibrationDataLoader_tEJN9QtPrivate20TypeAndForceCompleteI29LiveviewCalibrationDataLoaderNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_INS5_10shared_ptrI12DussMemShareEES9_EEEE` | 0x799718 | 24 |
| `_ZN29LiveviewCalibrationDataLoader16staticMetaObjectE` | 0x799730 | 56 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_LensControl_tEJN9QtPrivate20TypeAndForceCompleteI11LensControlNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_SG_SA_SA_NS3_IjS9_EESA_SA_NS3_IiS9_EESA_SH_SA_NS3_IbS9_EESA_SI_SA_NS3_IRK7QStringS9_EESA_SN_SA_SJ_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_SJ_SA_SJ_SA_NS3_IRK17FocusDistanceInfoS9_EESA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_NS3_IKtS9_EESA_SH_SA_SH_SA_NS3_I23dcam_focus_motor_resultS9_EESA_NS3_IN9HblmTypes10E_LensTypeES9_EESA_SI_SA_SH_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_NS3_INS11_17E_AutoFocusStatusES9_EESA_NS3_INS11_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_SI_SA_SI_SA_SI_SA_NS3_INS11_12E_LensStatusES9_EENS3_INS11_16E_LensPowerStateES9_EESA_SH_SA_SN_SA_SN_SA_SN_SA_SW_EE` | 0x79bf48 | 696 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_141qt_meta_stringdata_LensControlInterface_tEJN9QtPrivate20TypeAndForceCompleteI20LensControlInterfaceNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_SA_NS3_IKN9HblmTypes10E_LensTypeES9_EESA_NS3_INSB_12E_LensStatusES9_EESA_NS3_IKNSB_17E_AutoFocusStatusES9_EESA_NS3_IKNSB_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_NS3_IKiS9_EESA_NS3_IiS9_EESA_NS3_IbS9_EESA_SV_SA_NS3_IRK7QStringS9_EESA_SZ_SA_NS3_INSB_16E_LensPowerStateES9_EESA_NS3_IjS9_EESA_S12_SA_S12_SA_S12_SA_SU_SA_SV_SA_SV_SA_NS3_ItS9_EESA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_S18_SA_NS3_INSB_18E_FocusMotorResultES9_EESA_NS3_IRK17FocusDistanceInfoS9_EESA_SV_SA_SU_SA_SV_SA_SV_SA_SV_SA_SU_SA_NS3_INSB_17E_LensMfRingStateES9_EESA_SV_SA_SU_SA_SU_SA_ST_SA_ST_SA_ST_SA_ST_SA_NS3_IKNSB_19E_LensDriveEndpointES9_EESA_NS3_IKNSB_17E_LensDriveStatusES9_EESA_SZ_SA_SZ_SA_SZ_SA_SV_SA_SA_SA_SA_SA_SA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_S1S_EE` | 0x79c238 | 800 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_155qt_meta_stringdata_x2d__StateCaptureMultiShotExposure_tEJN9QtPrivate20TypeAndForceCompleteIN3x2d29StateCaptureMultiShotExposureENSt3__117integral_constantIbLb1EEEEEEE` | 0x79cf30 | 8 |
| `_ZN3x2d29StateCaptureMultiShotExposure16staticMetaObjectE` | 0x79cf38 | 56 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_148qt_meta_stringdata_x2d__StateExposureMultiShot_tEJN9QtPrivate20TypeAndForceCompleteIN3x2d22StateExposureMultiShotENSt3__117integral_constantIbLb1EEEEEEE` | 0x79d3b8 | 8 |
| `_ZN3x2d22StateExposureMultiShot16staticMetaObjectE` | 0x79d3c0 | 56 |
| `_ZTV28LiveviewCalibrationDataAsync` | 0x79db38 | 112 |
| `_ZTI28LiveviewCalibrationDataAsync` | 0x79dba8 | 24 |
| `_ZTV29LiveviewCalibrationDataLoader` | 0x79dbc0 | 112 |
| `_ZTI29LiveviewCalibrationDataLoader` | 0x79dc30 | 24 |
| `_ZTVN3x2d29StateCaptureMultiShotExposureE` | 0x7a31a8 | 144 |

<details><summary>… 另 43 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZTIN3x2d29StateCaptureMultiShotExposureE` | 0x7a3238 | 24 |
| `_ZTVN3x2d22StateExposureMultiShotE` | 0x7a3d78 | 144 |
| `_ZTIN3x2d22StateExposureMultiShotE` | 0x7a3e08 | 24 |
| `_ZTVNSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a5958 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a59b0 | 24 |
| `_ZTIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16` | 0x7a59c8 | 16 |
| `_ZTVNSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a59d8 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a5a30 | 24 |
| `_ZTIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17` | 0x7a5a48 | 16 |
| `_ZTVNSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a5a58 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a5ab0 | 24 |
| `_ZTIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18` | 0x7a5ac8 | 16 |
| `_ZTVNSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a5b58 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x7a5bb0 | 24 |
| `_ZTIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19` | 0x7a5bc8 | 16 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_35JEEE` | 0x7a86f8 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_35JEEE` | 0x7a8728 | 24 |
| `_ZTVNSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE` | 0x7a8790 | 88 |
| `_ZTINSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE` | 0x7a87f8 | 24 |
| `_ZTIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34` | 0x7a8810 | 16 |
| `_ZTV15IbisMoveMessage` | 0x7a9630 | 64 |
| `_ZTI15IbisMoveMessage` | 0x7a97b8 | 24 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_CameraObject_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IiS6_EES8_S8_S7_NS3_I4QMapI7QString8QVariantES6_EES8_S8_NS3_ItS6_EENS3_I5QListISC_ES6_EES7_S7_S8_S8_NS3_ISF_IiES6_EES8_S8_S7_S8_S7_S7_S7_S8_S8_S8_S8_S8_NS3_IjS6_EES8_S8_S8_S7_S8_S7_S7_S8_S8_S8_S8_S8_S7_S8_S7_S8_S7_S8_S8_S8_S8_S8_S7_S8_S8_S7_S8_S8_S8_S7_S8_S8_S8_S8_S8_SK_S7_S8_S8_S7_S8_NS3_IyS6_EES8_SL_S8_S8_S8_S8_S7_SD_S8_S8_S8_S8_S8_S8_S8_S8_S8_SD_SD_S8_S8_SK_S8_SD_SK_S8_S8_S8_S8_S7_S7_S8_S8_S8_S7_S7_S7_S8_S8_S8_S8_S8_S8_S7_S8_S8_S8_S8_SK_S8_S8_S8_NS3_ISA_S6_EESE_SK_SK_S7_S7_S7_S7_S8_S8_SE_SK_SM_SM_S7_SM_S7_S7_S8_S8_SM_S8_S7_S7_S8_SK_NS3_I10QByteArrayS6_EES8_SM_SK_S8_S8_SK_S7_S8_S8_S8_S8_S7_S8_SK_S8_S7_SK_S8_S8_S8_S8_S7_S7_S8_S7_SE_S7_NS3_IsS6_EES8_S7_SP_S8_S8_S8_S8_S8_S8_S8_SJ_S8_S8_S8_S8_SL_S8_S8_SJ_S8_S8_S7_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S7_S8_SK_NS3_I12CameraObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKiSS_EEST_SV_ST_SV_ST_NS3_IKbSS_EEST_SX_ST_SX_ST_NS3_IKN9HblmTypes17E_AfAlgorithmModeESS_EEST_NS3_IKNSY_21E_AfFaceDetectionModeESS_EEST_SV_ST_SX_ST_NS3_IRKSC_SS_EEST_NS3_IKNSY_17E_AutoFocusResultESS_EEST_NS3_IKNSY_17E_AutoFocusStatusESS_EEST_NS3_IKtSS_EEST_NS3_IKSG_SS_EEST_SX_ST_SX_ST_NS3_IKNSY_10E_LensTypeESS_EEST_SV_ST_NS3_IRKSI_SS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_20E_ExpBracketingParamESS_EEST_SV_ST_NS3_IKNSY_12E_ExitOptionESS_EEST_SV_ST_SV_ST_NS3_IKjSS_EEST_NS3_IKNSY_12E_CameraModeESS_EEST_NS3_IKNSY_12E_CameraTypeESS_EEST_NS3_IKNSY_18E_CameraPropertiesESS_EEST_SX_ST_S24_ST_SX_ST_SX_ST_NS3_IKNSY_26E_FocusBracketingStepSizesESS_EEST_NS3_IKNSY_14E_ColorProfileESS_EEST_NS3_IKNSY_10E_CropModeESS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SV_ST_SV_ST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_12E_TraceLevelESS_EEST_NS3_IKNSY_12E_DriveModesESS_EEST_SX_ST_S2D_ST_NS3_IKNSY_15E_FaceDetectionESS_EEST_NS3_IKNSY_13E_ImageFormatESS_EEST_SX_ST_SV_ST_SV_ST_S2J_ST_SV_ST_NS3_IKNSY_9E_ExpModeESS_EEST_S1V_ST_SX_ST_SV_ST_NS3_IKNSY_21E_ExposureControlModeESS_EEST_SX_ST_S2V_ST_NS3_IKySS_EEST_SV_ST_S2X_ST_NS3_IKNSY_16E_ExposureStatusESS_EEST_SV_ST_SV_ST_S2M_ST_SX_ST_S17_ST_SV_ST_SV_ST_NS3_IKNSY_12E_FlashModesESS_EEST_SV_ST_SV_ST_SV_ST_SV_ST_S27_ST_NS3_IKNSY_27E_FocusBracketingStrategiesESS_EEST_S17_ST_S17_ST_NS3_IKNSY_12E_FocusModesESS_EEST_NS3_IKNSY_19E_FocusPeakingColorESS_EEST_S1V_ST_NS3_IKNSY_21E_FocusPointResetModeESS_EEST_S17_ST_S1V_ST_NS3_IKNSY_11E_FocusSizeESS_EEST_S3I_ST_NS3_IKNSY_17E_CameraKeyOptionESS_EEST_SV_ST_SX_ST_SX_ST_SV_ST_SV_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_10E_IbisModeESS_EEST_NS3_IKNSY_10E_BitDepthESS_EEST_S2P_ST_SV_ST_NS3_IKNSY_21E_ImagePostProcessingESS_EEST_NS3_IKNSY_17E_IbisControlModeESS_EEST_SX_ST_SV_ST_S1T_ST_SV_ST_SV_ST_S1V_ST_NS3_IKNSY_13E_ResolutionsESS_EEST_NS3_IKNSY_19E_LensDriveEndpointESS_EEST_NS3_IKNSY_17E_LensDriveStatusESS_EEST_NS3_IRKSA_SS_EEST_S1F_ST_S1V_ST_S1V_ST_SX_ST_SX_ST_SX_ST_SX_ST_SV_ST_NS3_IKNSY_17E_LensMfRingStateESS_EEST_S1F_ST_S1V_ST_S49_ST_S49_ST_SX_ST_S49_ST_SX_ST_SX_ST_SV_ST_SV_ST_S49_ST_SV_ST_SX_ST_SX_ST_NS3_IKNSY_15E_LiveViewStateESS_EEST_S1V_ST_NS3_IRKSN_SS_EEST_SV_ST_S49_ST_S1V_ST_NS3_IKNSY_23E_LiveviewTransportModeESS_EEST_NS3_IKNSY_9E_LmModesESS_EEST_S1V_ST_SX_ST_NS3_IKNSY_19E_ManualFocusAssistESS_EEST_NS3_IKNSY_13E_MaxApertureESS_EEST_NS3_IKNSY_15E_MultiShotModeESS_EEST_NS3_IKNSY_13E_FlashStatusESS_EEST_SX_ST_NS3_IKNSY_16E_OptionOverrideESS_EEST_S1V_ST_SV_ST_SX_ST_S1V_ST_SV_ST_S1T_ST_NS3_IKNSY_12E_SoundLevelESS_EEST_NS3_IKNSY_14E_SequenceModeESS_EEST_SX_ST_SX_ST_SV_ST_SX_ST_S1F_ST_SX_ST_NS3_IKsSS_EEST_NS3_IKNSY_24E_SpiritLevelOrientationESS_EEST_SX_ST_S5B_ST_NS3_IKNSY_14E_CameraStatusESS_EEST_NS3_IKNSY_16E_StopDownStatusESS_EEST_NS3_IKNSY_13E_StreamGroupESS_EEST_NS3_IKNSY_18E_SensorUnitStatusESS_EEST_SV_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SV_ST_SV_ST_S2X_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SX_ST_SV_ST_NS3_IKNSY_14E_DistanceUnitESS_EEST_S2D_ST_SV_ST_SV_ST_SV_ST_SV_ST_NS3_IKNSY_12E_WhiteModesESS_EEST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_11E_ZoomLevelESS_EEST_S1V_ST_NS3_IKNSY_15E_AfBlockReasonESS_EEST_NS3_IKNSY_21E_ExposureBlockReasonESS_EEST_NS3_IKNSY_21E_LiveviewBlockReasonESS_EEST_S5B_NS3_IRK12QDBusMessageSS_EENS3_IiSS_EESV_S6C_ST_S6C_ST_S6C_ST_S6C_ST_SX_S6C_NS3_IjSS_EESV_S17_S17_S17_S6C_ST_SX_SV_SV_S6C_ST_SV_SX_S6C_ST_S6C_ST_SV_S49_S49_S6C_ST_S6C_S6D_S6C_S6D_SV_S6C_ST_S6C_S6E_S6C_NS3_ISC_SS_EES6C_ST_S6C_ST_SV_S6C_ST_S49_S49_S6C_ST_S17_S17_S17_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_SX_S6C_ST_S6C_ST_SV_S6C_ST_SX_S6C_ST_SV_S6C_ST_SX_S6C_ST_SX_SV_S6C_ST_SX_S6C_ST_SX_S6C_ST_SV_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_SX_S6C_ST_SV_S6C_ST_S6C_ST_SV_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_ST_S6C_EE` | 0x7ac9d0 | 6336 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI28LiveviewCalibrationDataAsyncE8metaTypeE` | 0x7c02a8 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI29LiveviewCalibrationDataLoaderE8metaTypeE` | 0x7c0388 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN3x2d29StateCaptureMultiShotExposureEE8metaTypeE` | 0x7c5248 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN3x2d22StateExposureMultiShotEE8metaTypeE` | 0x7c5a28 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x7c8048 | 112 |
| `_ZN12_GLOBAL__N_125kMultiShotExposuresLookUpE` | 0x7cff40 | 8 |
| `_ZZ18ibisResponseParservE8category` | 0x7d18c0 | 24 |
| `_ZGVZ18ibisResponseParservE8category` | 0x7d18d8 | 8 |
| `_ZN12_GLOBAL__N_121kTagSbpcCalibInfoRootE` | 0x7d2150 | 24 |
| `_ZN12_GLOBAL__N_130kTagSbpcCalibInfoSensorModeNumE` | 0x7d2190 | 24 |
| `_ZN12_GLOBAL__N_121kTagSbpcCalibInfoUnitE` | 0x7d21b0 | 24 |
| `_ZN12_GLOBAL__N_122kTagSbpcCalibUnitValidE` | 0x7d21d0 | 24 |
| `_ZN12_GLOBAL__N_127kTagSbpcCalibUnitSensorModeE` | 0x7d21f0 | 24 |
| `_ZN12_GLOBAL__N_125kTagSbpcCalibUnitRawWidthE` | 0x7d2210 | 24 |
| `_ZN12_GLOBAL__N_126kTagSbpcCalibUnitRawHeightE` | 0x7d2230 | 24 |
| `_ZN12_GLOBAL__N_128kTagSbpcCalibUnitMapArrayLenE` | 0x7d2250 | 24 |
| `_ZN12_GLOBAL__N_126kTagSbpcCalibUnitMapObjectE` | 0x7d2270 | 24 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x7d3688 | 4 |
| `_ZN12_GLOBAL__N_111kMetaTagMapE` | 0x7d37f0 | 8 |
| `_ZN12_GLOBAL__N_114kStorageTagMapE` | 0x7d37f8 | 8 |

</details>

**Removed objects (126)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTSNSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x59ad86 | 123 |
| `_ZTSZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15` | 0x59ae01 | 53 |
| `_ZTSNSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x59ae36 | 121 |
| `_ZTSZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16` | 0x59aeaf | 51 |
| `_ZTSNSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x59aee2 | 116 |
| `_ZTSZN3x2d20StateExposurePrepareC1EP6QStateE4$_17` | 0x59af56 | 46 |
| `_ZTSNSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x59b0c0 | 117 |
| `_ZTSZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18` | 0x59b135 | 47 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_34JEEE` | 0x59e38e | 86 |
| `_ZTSNSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE` | 0x59e427 | 126 |
| `_ZTSZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33` | 0x59e4e3 | 46 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_LensControl_tEJN9QtPrivate20TypeAndForceCompleteI11LensControlNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_SG_SA_SA_NS3_IjS9_EESA_SA_NS3_IiS9_EESA_SH_SA_NS3_IbS9_EESA_SI_SA_NS3_IRK7QStringS9_EESA_SN_SA_SJ_SA_SI_SA_SJ_SA_SJ_SA_SJ_SA_SJ_SA_NS3_IRK17FocusDistanceInfoS9_EESA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_NS3_IKtS9_EESA_SH_SA_SH_SA_NS3_I23dcam_focus_motor_resultS9_EESA_NS3_IN9HblmTypes10E_LensTypeES9_EESA_SI_SA_SH_SA_SI_SA_SI_SA_SJ_SA_SJ_SA_NS3_INS11_17E_AutoFocusStatusES9_EESA_NS3_INS11_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_SI_SA_SI_SA_SI_SA_NS3_INS11_12E_LensStatusES9_EENS3_INS11_16E_LensPowerStateES9_EESA_SH_SA_SN_SA_SN_SA_SN_SA_SW_EE` | 0x78c440 | 680 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_141qt_meta_stringdata_LensControlInterface_tEJN9QtPrivate20TypeAndForceCompleteI20LensControlInterfaceNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_SA_NS3_IKN9HblmTypes10E_LensTypeES9_EESA_NS3_INSB_12E_LensStatusES9_EESA_NS3_IKNSB_17E_AutoFocusStatusES9_EESA_NS3_IKNSB_17E_AutoFocusResultES9_EESA_NS3_IRKN6Common5AfRoiES9_EESA_NS3_IKiS9_EESA_NS3_IiS9_EESA_NS3_IbS9_EESA_SV_SA_NS3_IRK7QStringS9_EESA_SZ_SA_NS3_INSB_16E_LensPowerStateES9_EESA_NS3_IjS9_EESA_S12_SA_S12_SA_S12_SA_SU_SA_SV_SA_SV_SA_NS3_ItS9_EESA_NS3_IRKN5CLens22FocusDistanceScaleInfoES9_EESA_S18_SA_NS3_INSB_18E_FocusMotorResultES9_EESA_NS3_IRK17FocusDistanceInfoS9_EESA_SV_SA_SU_SA_SV_SA_SV_SA_SU_SA_NS3_INSB_17E_LensMfRingStateES9_EESA_SV_SA_SU_SA_SU_SA_ST_SA_ST_SA_ST_SA_ST_SA_NS3_IKNSB_19E_LensDriveEndpointES9_EESA_NS3_IKNSB_17E_LensDriveStatusES9_EESA_SZ_SA_SZ_SA_SZ_SA_SV_SA_SA_SA_SA_SA_SA_NS3_IRK14QSharedPointerI19MessageNotificationES9_EESA_S1S_EE` | 0x78c720 | 784 |
| `_ZTVNSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795aa8 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795b00 | 24 |
| `_ZTIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_15` | 0x795b18 | 16 |
| `_ZTVNSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795b28 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795b80 | 24 |
| `_ZTIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_16` | 0x795b98 | 16 |
| `_ZTVNSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795ba8 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795c00 | 24 |
| `_ZTIZN3x2d20StateExposurePrepareC1EP6QStateE4$_17` | 0x795c18 | 16 |
| `_ZTVNSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795ca8 | 88 |
| `_ZTINSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE` | 0x795d00 | 24 |
| `_ZTIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_18` | 0x795d18 | 16 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_34JEEE` | 0x798848 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_34JEEE` | 0x798878 | 24 |
| `_ZTVNSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE` | 0x7988e0 | 88 |
| `_ZTINSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE` | 0x798948 | 24 |
| `_ZTIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_33` | 0x798960 | 16 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_CameraObject_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IiS6_EES8_S8_S7_NS3_I4QMapI7QString8QVariantES6_EES8_S8_NS3_ItS6_EENS3_I5QListISC_ES6_EES7_S7_S8_S8_NS3_ISF_IiES6_EES8_S8_S7_S8_S7_S7_S7_S8_S8_S8_S8_S8_NS3_IjS6_EES8_S8_S8_S7_S8_S7_S7_S8_S8_S8_S8_S8_S7_S8_S7_S8_S7_S8_S8_S8_S8_S8_S7_S8_S8_S7_S8_S8_S7_S8_S8_S8_S8_S8_SK_S7_S8_S8_S7_S8_NS3_IyS6_EES8_SL_S8_S8_S8_S7_SD_S8_S8_S8_S8_S8_S8_S8_S8_SD_SD_S8_S8_SK_S8_SD_SK_S8_S8_S8_S8_S7_S7_S8_S8_S8_S7_S7_S7_S8_S8_S8_S8_S8_S8_S7_S8_S8_S8_S8_SK_S8_S8_S8_NS3_ISA_S6_EESE_SK_SK_S7_S7_S7_S7_S8_S8_SE_SK_SM_SM_S7_SM_S7_S7_S8_S8_SM_S8_S7_S7_S8_SK_NS3_I10QByteArrayS6_EES8_SM_SK_S8_S8_SK_S7_S8_S8_S8_S7_S8_SK_S8_S7_SK_S8_S8_S8_S8_S7_S7_S8_S7_SE_S7_NS3_IsS6_EES8_S7_SP_S8_S8_S8_S8_S8_S8_S8_SJ_S8_S8_S8_S8_SL_S8_S8_SJ_S8_S8_S7_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S7_S8_SK_NS3_I12CameraObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKiSS_EEST_SV_ST_SV_ST_NS3_IKbSS_EEST_SX_ST_SX_ST_NS3_IKN9HblmTypes17E_AfAlgorithmModeESS_EEST_NS3_IKNSY_21E_AfFaceDetectionModeESS_EEST_SV_ST_SX_ST_NS3_IRKSC_SS_EEST_NS3_IKNSY_17E_AutoFocusResultESS_EEST_NS3_IKNSY_17E_AutoFocusStatusESS_EEST_NS3_IKtSS_EEST_NS3_IKSG_SS_EEST_SX_ST_SX_ST_NS3_IKNSY_10E_LensTypeESS_EEST_SV_ST_NS3_IRKSI_SS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_20E_ExpBracketingParamESS_EEST_SV_ST_NS3_IKNSY_12E_ExitOptionESS_EEST_SV_ST_SV_ST_NS3_IKjSS_EEST_NS3_IKNSY_12E_CameraModeESS_EEST_NS3_IKNSY_12E_CameraTypeESS_EEST_NS3_IKNSY_18E_CameraPropertiesESS_EEST_SX_ST_S24_ST_SX_ST_SX_ST_NS3_IKNSY_26E_FocusBracketingStepSizesESS_EEST_NS3_IKNSY_14E_ColorProfileESS_EEST_NS3_IKNSY_10E_CropModeESS_EEST_SV_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SX_ST_SV_ST_SV_ST_SV_ST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_12E_TraceLevelESS_EEST_NS3_IKNSY_12E_DriveModesESS_EEST_SX_ST_S2D_ST_NS3_IKNSY_13E_ImageFormatESS_EEST_SX_ST_SV_ST_SV_ST_S2J_ST_SV_ST_NS3_IKNSY_9E_ExpModeESS_EEST_S1V_ST_SX_ST_SV_ST_NS3_IKNSY_21E_ExposureControlModeESS_EEST_SX_ST_S2S_ST_NS3_IKySS_EEST_SV_ST_S2U_ST_NS3_IKNSY_16E_ExposureStatusESS_EEST_SV_ST_NS3_IKNSY_15E_FaceDetectionESS_EEST_SX_ST_S17_ST_SV_ST_SV_ST_NS3_IKNSY_12E_FlashModesESS_EEST_SV_ST_SV_ST_SV_ST_S27_ST_NS3_IKNSY_27E_FocusBracketingStrategiesESS_EEST_S17_ST_S17_ST_NS3_IKNSY_12E_FocusModesESS_EEST_NS3_IKNSY_19E_FocusPeakingColorESS_EEST_S1V_ST_NS3_IKNSY_21E_FocusPointResetModeESS_EEST_S17_ST_S1V_ST_NS3_IKNSY_11E_FocusSizeESS_EEST_S3I_ST_NS3_IKNSY_17E_CameraKeyOptionESS_EEST_SV_ST_SX_ST_SX_ST_SV_ST_SV_ST_SV_ST_SX_ST_SX_ST_SX_ST_NS3_IKNSY_10E_IbisModeESS_EEST_NS3_IKNSY_10E_BitDepthESS_EEST_S2M_ST_SV_ST_NS3_IKNSY_21E_ImagePostProcessingESS_EEST_NS3_IKNSY_17E_IbisControlModeESS_EEST_SX_ST_SV_ST_S1T_ST_SV_ST_SV_ST_S1V_ST_NS3_IKNSY_13E_ResolutionsESS_EEST_NS3_IKNSY_19E_LensDriveEndpointESS_EEST_NS3_IKNSY_17E_LensDriveStatusESS_EEST_NS3_IRKSA_SS_EEST_S1F_ST_S1V_ST_S1V_ST_SX_ST_SX_ST_SX_ST_SX_ST_SV_ST_NS3_IKNSY_17E_LensMfRingStateESS_EEST_S1F_ST_S1V_ST_S49_ST_S49_ST_SX_ST_S49_ST_SX_ST_SX_ST_SV_ST_SV_ST_S49_ST_SV_ST_SX_ST_SX_ST_NS3_IKNSY_15E_LiveViewStateESS_EEST_S1V_ST_NS3_IRKSN_SS_EEST_SV_ST_S49_ST_S1V_ST_NS3_IKNSY_23E_LiveviewTransportModeESS_EEST_NS3_IKNSY_9E_LmModesESS_EEST_S1V_ST_SX_ST_NS3_IKNSY_19E_ManualFocusAssistESS_EEST_NS3_IKNSY_13E_MaxApertureESS_EEST_NS3_IKNSY_13E_FlashStatusESS_EEST_SX_ST_NS3_IKNSY_16E_OptionOverrideESS_EEST_S1V_ST_SV_ST_SX_ST_S1V_ST_SV_ST_S1T_ST_NS3_IKNSY_12E_SoundLevelESS_EEST_NS3_IKNSY_14E_SequenceModeESS_EEST_SX_ST_SX_ST_SV_ST_SX_ST_S1F_ST_SX_ST_NS3_IKsSS_EEST_NS3_IKNSY_24E_SpiritLevelOrientationESS_EEST_SX_ST_S58_ST_NS3_IKNSY_14E_CameraStatusESS_EEST_NS3_IKNSY_16E_StopDownStatusESS_EEST_NS3_IKNSY_13E_StreamGroupESS_EEST_NS3_IKNSY_18E_SensorUnitStatusESS_EEST_SV_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SV_ST_SV_ST_S2U_ST_SV_ST_SV_ST_S1N_ST_SV_ST_SV_ST_SX_ST_SV_ST_NS3_IKNSY_14E_DistanceUnitESS_EEST_S2D_ST_SV_ST_SV_ST_SV_ST_SV_ST_NS3_IKNSY_12E_WhiteModesESS_EEST_SV_ST_SV_ST_SX_ST_NS3_IKNSY_11E_ZoomLevelESS_EEST_S1V_ST_NS3_IKNSY_15E_AfBlockReasonESS_EEST_NS3_IKNSY_21E_ExposureBlockReasonESS_EEST_NS3_IKNSY_21E_LiveviewBlockReasonESS_EEST_S58_NS3_IRK12QDBusMessageSS_EENS3_IiSS_EESV_S69_ST_S69_ST_S69_ST_S69_ST_SX_S69_NS3_IjSS_EESV_S17_S17_S17_S69_ST_SX_SV_SV_S69_ST_SV_SX_S69_ST_S69_ST_SV_S49_S49_S69_ST_S69_S6A_S69_S6A_SV_S69_ST_S69_S6B_S69_NS3_ISC_SS_EES69_ST_S69_ST_SV_S69_ST_S49_S49_S69_ST_S17_S17_S17_S69_ST_SV_S69_ST_S69_ST_S69_ST_SX_S69_ST_S69_ST_SV_S69_ST_SX_S69_ST_SV_S69_ST_SX_S69_ST_SX_SV_S69_ST_SX_S69_ST_SX_S69_ST_SV_S69_ST_SV_S69_ST_S69_ST_S69_ST_SX_S69_ST_SV_S69_ST_S69_ST_SV_S69_ST_S69_ST_S69_ST_S69_ST_S69_ST_S69_ST_S69_ST_S69_ST_S69_ST_S69_EE` | 0x79cb08 | 6240 |
| `_ZN5CJson4LensL25kJsonTagShadingCorrectionE` | 0x7c1900 | 24 |
| `_ZL11TAG_MOUNTED` | 0x7c34c0 | 24 |
| `_ZL8TAG_TYPE` | 0x7c34e0 | 24 |
| `_ZL8TAG_NAME` | 0x7c3500 | 24 |
| `_ZL8TAG_UUID` | 0x7c3520 | 24 |
| `_ZL15TAG_EXPOSURE_ID` | 0x7c3540 | 24 |
| `_ZL8TAG_SIZE` | 0x7c3560 | 24 |
| `_ZL10TAG_OFFSET` | 0x7c3580 | 24 |
| `_ZL10TAG_HANDLE` | 0x7c35a0 | 24 |
| `_ZL15TAG_DEVICE_TYPE` | 0x7c35c0 | 24 |
| `_ZL13TAG_SIZECHILD` | 0x7c35e0 | 24 |
| `_ZL13TAG_FULL_PATH` | 0x7c3600 | 24 |
| `_ZL16TAG_DISPLAY_PATH` | 0x7c3620 | 24 |
| `_ZL28TAG_DISPLAY_PATH_WITH_SUFFIX` | 0x7c3640 | 24 |
| `_ZL12TAG_METADATA` | 0x7c3660 | 24 |
| `_ZL15TAG_LORES_IMAGE` | 0x7c3680 | 24 |
| `_ZL15TAG_THUMB_IMAGE` | 0x7c36a0 | 24 |
| `_ZL14TAG_TILE_IMAGE` | 0x7c36c0 | 24 |
| `_ZL14TAG_FREE_SPACE` | 0x7c36e0 | 24 |

<details><summary>… 另 76 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZL16TAG_WRITEPROTECT` | 0x7c3700 | 24 |
| `_ZL10TAG_STATUS` | 0x7c3720 | 24 |
| `_ZL6TAG_WP` | 0x7c3740 | 24 |
| `_ZL14TAG_SLOW_SPEED` | 0x7c3760 | 24 |
| `_ZL17TAG_AVERAGE_SPEED` | 0x7c3780 | 24 |
| `_ZL13TAG_DATE_TIME` | 0x7c37a0 | 24 |
| `_ZL6TAG_SV` | 0x7c37c0 | 24 |
| `_ZL6TAG_AV` | 0x7c37e0 | 24 |
| `_ZL21TAG_FNUMBER_NUMERATOR` | 0x7c3800 | 24 |
| `_ZL23TAG_FNUMBER_DENOMINATOR` | 0x7c3820 | 24 |
| `_ZL10TAG_AV_MIN` | 0x7c3840 | 24 |
| `_ZL6TAG_TV` | 0x7c3860 | 24 |
| `_ZL13TAG_FOCAL_LEN` | 0x7c3880 | 24 |
| `_ZL17TAG_EXPOSURE_MODE` | 0x7c38a0 | 24 |
| `_ZL27TAG_EXPOSURE_TIME_NUMERATOR` | 0x7c38c0 | 24 |
| `_ZL29TAG_EXPOSURE_TIME_DENOMINATOR` | 0x7c38e0 | 24 |
| `_ZL11TAG_LM_MODE` | 0x7c3900 | 24 |
| `_ZL6TAG_WB` | 0x7c3920 | 24 |
| `_ZL10TAG_EV_ADJ` | 0x7c3940 | 24 |
| `_ZL17TAG_EXPOSURE_BIAS` | 0x7c3960 | 24 |
| `_ZL14TAG_LENS_SHIFT` | 0x7c3980 | 24 |
| `_ZL16TAG_LENS_VERSION` | 0x7c39a0 | 24 |
| `_ZL27TAG_LENS_SHADING_CORRECTION` | 0x7c39c0 | 24 |
| `_ZL21TAG_LENS_FOCAL_MINMAX` | 0x7c39e0 | 24 |
| `_ZL13TAG_LENS_TYPE` | 0x7c3a00 | 24 |
| `_ZL13TAG_HISTOGRAM` | 0x7c3a20 | 24 |
| `_ZL16TAG_FS_TIMESTAMP` | 0x7c3a40 | 24 |
| `_ZL8TAG_PATH` | 0x7c3a60 | 24 |
| `_ZL14TAG_PERSISTENT` | 0x7c3a80 | 24 |
| `_ZL15TAG_R_NUMERATOR` | 0x7c3aa0 | 24 |
| `_ZL17TAG_R_DENOMINATOR` | 0x7c3ac0 | 24 |
| `_ZL15TAG_G_NUMERATOR` | 0x7c3ae0 | 24 |
| `_ZL17TAG_G_DENOMINATOR` | 0x7c3b00 | 24 |
| `_ZL15TAG_B_NUMERATOR` | 0x7c3b20 | 24 |
| `_ZL17TAG_B_DENOMINATOR` | 0x7c3b40 | 24 |
| `_ZL22TAG_BLACK_LEVEL_OFFSET` | 0x7c3b60 | 24 |
| `_ZL15TAG_WHITE_LEVEL` | 0x7c3b80 | 24 |
| `_ZL20TAG_SENSITIVITY_GAIN` | 0x7c3ba0 | 24 |
| `_ZL18TAG_R_NEUTRAL_GAIN` | 0x7c3bc0 | 24 |
| `_ZL18TAG_G_NEUTRAL_GAIN` | 0x7c3be0 | 24 |
| `_ZL18TAG_B_NEUTRAL_GAIN` | 0x7c3c00 | 24 |
| `_ZL21TAG_NEUTRAL_PRECISION` | 0x7c3c20 | 24 |
| `_ZL16TAG_IMAGE_RATING` | 0x7c3c40 | 24 |
| `_ZL18TAG_IMAGE_ROTATION` | 0x7c3c60 | 24 |
| `_ZL15TAG_CAMERA_TYPE` | 0x7c3c80 | 24 |
| `_ZL15TAG_FOCUS_POINT` | 0x7c3ca0 | 24 |
| `_ZL20TAG_SUBJECT_DISTANCE` | 0x7c3cc0 | 24 |
| `_ZL14TAG_LENS_MODEL` | 0x7c3ce0 | 24 |
| `_ZL13TAG_LENS_MAKE` | 0x7c3d00 | 24 |
| `_ZL17TAG_FOCUS_SEGMENT` | 0x7c3d20 | 24 |
| `_ZL17TAG_LENS_MODEL_ID` | 0x7c3d40 | 24 |
| `_ZL9TAG_FILES` | 0x7c3d60 | 24 |
| `_ZL14IMAGE_TAG_DATA` | 0x7c3d80 | 24 |
| `_ZL16IMAGE_TAG_FORMAT` | 0x7c3da0 | 24 |
| `_ZL15IMAGE_TAG_WIDTH` | 0x7c3dc0 | 24 |
| `_ZL16IMAGE_TAG_HEIGHT` | 0x7c3de0 | 24 |
| `_ZL11IMAGE_TAG_X` | 0x7c3e00 | 24 |
| `_ZL11IMAGE_TAG_Y` | 0x7c3e20 | 24 |
| `_ZL19IMAGE_TAG_BUFFER_ID` | 0x7c3e40 | 24 |
| `_ZL17IMAGE_FORMAT_RGBA` | 0x7c3e60 | 24 |
| `_ZL17IMAGE_FORMAT_UYVY` | 0x7c3e80 | 24 |
| `_ZL17IMAGE_FORMAT_NV12` | 0x7c3ea0 | 24 |
| `_ZL17IMAGE_FORMAT_422P` | 0x7c3ec0 | 24 |
| `_ZL17IMAGE_FORMAT_JPEG` | 0x7c3ee0 | 24 |
| `_ZL12STORAGE_ROOT` | 0x7c3f00 | 24 |
| `_ZL13TETHERED_ROOT` | 0x7c3f20 | 24 |
| `_ZL17STORAGE_MOUNT_SSD` | 0x7c3f40 | 24 |
| `_ZL20STORAGE_MOUNT_CFCARD` | 0x7c3f60 | 24 |
| `_ZL17HASBL_FOLDER_NAME` | 0x7c3f80 | 24 |
| `_ZL9NAME_ROOT` | 0x7c3fa0 | 24 |
| `_ZL9NAME_DCIM` | 0x7c3fc0 | 24 |
| `_ZL11SOCKET_NAME` | 0x7c3fe0 | 24 |
| `_ZL11EXPOSURE_ID` | 0x7c4000 | 24 |
| `_ZL14DCAM_CONTAINER` | 0x7c4020 | 24 |
| `_ZL10FRAME_INFO` | 0x7c4040 | 24 |
| `_ZL18EXPOSURE_ITEM_TYPE` | 0x7c4060 | 24 |

</details>

### `/bin/odindb-send`

+249 / −210 functions · +8 / −5 objects

**New functions (249)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_2Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x6fad0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_3Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x6feb8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_4Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x70298 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_6Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x70a38 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_9Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x715e8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_10Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x719d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_11Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x71d90 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_12Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x72178 | 956 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x72780 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x72790 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x72798 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x72798 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x727a8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x727c0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x72870 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x72880 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_13Li1ENS_4ListIJN9HblmTypes16E_FocusScanRangeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x72898 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_17Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x738f8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_18Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x73ce0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_19Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x740a0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_20Li1ENS_4ListIJN9HblmTypes17E_MetadataOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x74748 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_21Li1ENS_4ListIJN9HblmTypes10E_OSDClockEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x74ed8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_22Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x75380 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_23Li1ENS_4ListIJN9HblmTypes15E_GuiPopupStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x75a28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_24Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x75ed0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_25Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x76290 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_27Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x76a38 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_28Li1ENS_4ListIJN9HblmTypes14E_TouchpadAreaEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x77108 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_29Li1ENS_4ListIJN9HblmTypes21E_TouchpadSensitivityEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x77898 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_30Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x77d40 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_38Li1ENS_4ListIJN9HblmTypes20E_UserButtonFunctionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7a4a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_42Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7b488 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_43Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7b848 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_45Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7bfe8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_46Li1ENS_4ListIJN9HblmTypes19E_UserWheelFunctionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7c690 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_47Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7cb38 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_25Li1ENS_4ListIJN9HblmTypes15E_BatteryStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x90ba0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_29Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91be8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_30Li1ENS_4ListIJN9HblmTypes16E_BtAssistStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x922b0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_31Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92758 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_32Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92b38 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_33Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92f20 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_34Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x932e0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_35Li1ENS_4ListIJPK15VariantMapModelEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x936c8 | 960 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_36Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93f98 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_37Li1ENS_4ListIJN9HblmTypes13E_DebugOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94380 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_39Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94b20 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_40Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94ee0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_41Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x952c8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_42Li1ENS_4ListIJN9HblmTypes20E_EyesensorDistancesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95968 | 1192 |

<details><summary>… 另 199 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_43Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95e10 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_44Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x961d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_45Li1ENS_4ListIJN9HblmTypes17E_MaintenanceTypeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96878 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_46Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96d20 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_48Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x974c8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_49Li1ENS_4ListIJN9HblmTypes10E_ProfilesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97b70 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_50Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98018 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_51Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98400 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_52Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x987e0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_53Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98ba0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_54Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98f88 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_56Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99730 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_57Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99b18 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_58Li1ENS_4ListIJN9HblmTypes14E_ScreenStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a1c0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_61Li1ENS_4ListIJN9HblmTypes9E_ScreensEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ae28 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_62Li1ENS_4ListIJN9HblmTypes15E_SoundSettingsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b208 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_63Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b5e8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_64Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b9d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_65Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c078 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_66Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c520 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_67Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c908 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_68Li1ENS_4ListIJN9HblmTypes21E_SuspendWakeupSourceEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9cfb0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_70Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d818 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_71Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9dec0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_72Li1ENS_4ListIJN9HblmTypes13E_SystemStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e650 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_73Li1ENS_4ListIJN9HblmTypes19E_TemperatureStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ede0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_74Li1ENS_4ListIJN9HblmTypes14E_TetheredModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f570 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_75Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9fa18 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_77Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa01c0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_78Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa05a8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_80Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa0d48 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_81Li1ENS_4ListIJN9HblmTypes10E_WifiModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa13f0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_82Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa1898 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_83Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa1c78 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_84Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2060 | 992 |
| `_ZN15OdinDbSendUtils21convertStringToBitsetIN9HblmTypes16E_SessionOptionsELm7EEEbRK7QStringRT_` | 0xdc4e0 | 1876 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_106Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfbc68 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_107Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfc3f8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_108Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfc8a0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_110Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfd048 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_111Li1ENS_4ListIJN9HblmTypes12E_DriveModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfd408 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_112Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfd8b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_113Li1ENS_4ListIJN9HblmTypes9E_ExpModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfdf58 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_114Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfe400 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_115Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfe7c0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_116Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfeba8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_117Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xff250 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_118Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xff6f8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_119Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xffae0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_120Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfff88 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_121Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x100348 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_122Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x100708 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_123Li1ENS_4ListIJN9HblmTypes16E_ExposureStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x100ac8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_124Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x100ea8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_125Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x101268 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_126Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x101628 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_127Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x101ad0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_128Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x101eb8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_129Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x102278 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_131Li1ENS_4ListIJN9HblmTypes12E_FlashModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x102ce0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_133Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x103548 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_134Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x103908 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_135Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x103cc8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_136Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x104088 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_137Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x104818 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_138Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x104cc0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_139Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x105080 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_140Li1ENS_4ListIJN9HblmTypes12E_FocusModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x105728 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_141Li1ENS_4ListIJN9HblmTypes19E_FocusPeakingColorEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x105eb8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_143Li1ENS_4ListIJN9HblmTypes21E_FocusPointResetModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x106a08 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_144Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x106eb0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_145Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x107270 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_146Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x107918 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_147Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x107dc0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_148Li1ENS_4ListIJN9HblmTypes17E_CameraKeyOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x108550 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_150Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x108db8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_151Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1091a0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_152Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x109588 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_153Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x109948 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_154Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x109d08 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_155Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10a0c8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_156Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10a4b0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_157Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10a898 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_158Li1ENS_4ListIJN9HblmTypes10E_IbisModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10af68 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_159Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10b6f8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10bba0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10c048 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10c408 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10cad0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10cf78 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10d720 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10dbc8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10df88 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_169Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e348 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e9f0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10f180 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10f910 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10fdb8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110198 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110558 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110918 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1110c0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_179Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1114a8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_180Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111890 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_181Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111c78 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_182Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112038 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_183Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112418 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1127d8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112f78 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113740 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_189Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113b20 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_190Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113f08 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_192Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1146b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_193Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114a70 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_194Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114e50 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_195Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115210 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_196Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1155f8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_197Li1ENS_4ListIJN9HblmTypes15E_LiveViewStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115cc8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_198Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116170 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_199Li1ENS_4ListIJRK10QByteArrayEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116530 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_200Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1168f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_201Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116cb0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_203Li1ENS_4ListIJN9HblmTypes23E_LiveviewTransportModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x117450 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_204Li1ENS_4ListIJN9HblmTypes9E_LmModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x117b18 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_205Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x117fc0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_206Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x118380 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_207Li1ENS_4ListIJN9HblmTypes19E_ManualFocusAssistEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x118a50 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_208Li1ENS_4ListIJN9HblmTypes13E_MaxApertureEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1191e0 | 1192 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x119688 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x119808 | 200 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x1198d0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x119968 | 4 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_209Li1ENS_4ListIJN9HblmTypes15E_MultiShotModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x119970 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_210Li1ENS_4ListIJN9HblmTypes13E_FlashStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11a100 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_212Li1ENS_4ListIJN9HblmTypes16E_OptionOverrideEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11a990 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_213Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11ad70 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_214Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11b130 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_215Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11b4f0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_216Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11b8d8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_217Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11bc98 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_218Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11c058 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_219Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11c500 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_220Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11cc90 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_221Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11d138 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_223Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11d908 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_224Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11dcc8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_225Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11e0b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_226Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11e470 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_227Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11e858 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_228Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11ec18 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_229Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11f0c0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_230Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11f4a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_231Li1ENS_4ListIJN9HblmTypes14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11f868 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_232Li1ENS_4ListIJN9HblmTypes16E_StopDownStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11ff30 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_233Li1ENS_4ListIJN9HblmTypes13E_StreamGroupEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1206c0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_234Li1ENS_4ListIJN9HblmTypes18E_SensorUnitStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x120e50 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_238Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x121e38 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_239Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x122218 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_242Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x122d58 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_243Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x123118 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_245Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x123898 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_246Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x123c58 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_247Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x124038 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_248Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1243f8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_249Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1247b8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_251Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x125248 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_252Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1256f0 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_253Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x125ad0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_256Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x126610 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_257Li1ENS_4ListIJN9HblmTypes12E_WhiteModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x126cb8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_258Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x127160 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_259Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x127520 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_260Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1278e0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_261Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x127fb0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_262Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x128458 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18PhocusProxyWrapper24registerSignalSubscriberERK7QStringE3$_6Li1ENS_4ListIJN9HblmTypes7E_HostsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x13db38 | 988 |
| `_ZN11PhocusProxy11qt_metacallEN11QMetaObject4CallEiPPv` | 0x186558 | 212 |
| `_ZN11CameraProxy35enabled_face_detection_modesChangedEN9HblmTypes15E_FaceDetectionE` | 0x190a00 | 96 |
| `_ZN11CameraProxy37exposures_in_multishot_sessionChangedEi` | 0x1910d8 | 96 |
| `_ZN11CameraProxy27flash_recharge_delayChangedEi` | 0x1913d8 | 96 |
| `_ZN11CameraProxy29multishot_control_modeChangedEN9HblmTypes15E_MultiShotModeE` | 0x1930e8 | 96 |
| `_ZN8GuiProxy20ae_lock_touchChangedEb` | 0x198400 | 100 |
| `_ZN11PhocusProxy31tethered_capture_clientsChangedEN9HblmTypes7E_HostsE` | 0x19a0b0 | 96 |
| `_ZN11SystemProxy21battery_statusChangedEN9HblmTypes15E_BatteryStatusE` | 0x19efe0 | 96 |
| `_ZN15PhocusProxyDbus24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeE` | 0x1a60d8 | 404 |
| `_ZN12GuiProxyDbus16setAe_lock_touchEb` | 0x1c4550 | 308 |
| `_ZNK12GuiProxyDbus13ae_lock_touchEv` | 0x1c79c0 | 48 |
| `_ZNK15SystemProxyDbus14battery_statusEv` | 0x1df1b0 | 48 |
| `_ZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeEiP7QObject` | 0x1e9a20 | 848 |
| `_ZNK15PhocusProxyDbus24tethered_capture_clientsEv` | 0x1ea200 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeEiP7QObjectE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0x1ea8a8 | 64 |
| `_ZN15CameraProxyDbus31setEnabled_face_detection_modesEN9HblmTypes15E_FaceDetectionE` | 0x1faec8 | 308 |
| `_ZN15CameraProxyDbus33setExposures_in_multishot_sessionEi` | 0x1fbd68 | 308 |
| `_ZN15CameraProxyDbus23setFlash_recharge_delayEi` | 0x1fc4b8 | 308 |
| `_ZN15CameraProxyDbus25setMultishot_control_modeEN9HblmTypes15E_MultiShotModeE` | 0x1fef60 | 308 |
| `_ZNK15CameraProxyDbus28enabled_face_detection_modesEv` | 0x201ea0 | 48 |
| `_ZNK15CameraProxyDbus30exposures_in_multishot_sessionEv` | 0x202200 | 48 |
| `_ZNK15CameraProxyDbus20flash_recharge_delayEv` | 0x202380 | 48 |
| `_ZNK15CameraProxyDbus22multishot_control_modeEv` | 0x2031f0 | 48 |

</details>

**Removed functions (210)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_2Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x6f4d8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_3Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x6f8b8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_4Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x6fc78 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_6Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x70438 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE3$_9Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x70ff0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_10Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x713b0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_11Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x71798 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_12Li1ENS_4ListIJN9HblmTypes16E_FocusScanRangeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x71eb8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_13Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x72360 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_17Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x73300 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_18Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x736c0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_19Li1ENS_4ListIJN9HblmTypes17E_MetadataOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x73d68 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_20Li1ENS_4ListIJN9HblmTypes10E_OSDClockEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x744f8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_21Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x749a0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_22Li1ENS_4ListIJN9HblmTypes15E_GuiPopupStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x75048 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_23Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x754f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_24Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x758b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_25Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x75c70 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_27Li1ENS_4ListIJN9HblmTypes14E_TouchpadAreaEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x76728 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_28Li1ENS_4ListIJN9HblmTypes21E_TouchpadSensitivityEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x76eb8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_29Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x77360 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_30Li1ENS_4ListIJN9HblmTypes20E_UserButtonFunctionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x77a28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_38Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x79f68 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_42Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7ae68 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_43Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7b248 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_45Li1ENS_4ListIJN9HblmTypes19E_UserWheelFunctionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7bcb0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15GuiProxyWrapper24registerSignalSubscriberERK7QStringE4$_46Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7c158 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_25Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8fe48 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_29Li1ENS_4ListIJN9HblmTypes16E_BtAssistStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x910b0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_30Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91558 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_31Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91938 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_32Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91d20 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_33Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x920e0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_34Li1ENS_4ListIJPK15VariantMapModelEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x924c8 | 960 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_35Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92d98 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_36Li1ENS_4ListIJN9HblmTypes13E_DebugOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93180 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_37Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93560 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_39Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93ce0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_40Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x940c8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_41Li1ENS_4ListIJN9HblmTypes20E_EyesensorDistancesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94768 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_42Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94c10 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_43Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94fd0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_44Li1ENS_4ListIJN9HblmTypes17E_MaintenanceTypeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95678 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_45Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95b20 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_46Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95f08 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_48Li1ENS_4ListIJN9HblmTypes10E_ProfilesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96970 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_49Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96e18 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_50Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97200 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_51Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x975e0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_52Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x979a0 | 1000 |

<details><summary>… 另 160 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_53Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97d88 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_54Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98148 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_56Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98918 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_57Li1ENS_4ListIJN9HblmTypes14E_ScreenStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98fc0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_58Li1ENS_4ListIJN9HblmTypes9E_ScreensEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99468 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_61Li1ENS_4ListIJN9HblmTypes15E_SoundSettingsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a008 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_62Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a3e8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_63Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a7d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_64Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ae78 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_65Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b320 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_66Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b708 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_67Li1ENS_4ListIJN9HblmTypes21E_SuspendWakeupSourceEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9bdb0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_68Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c258 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_70Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ccc0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_71Li1ENS_4ListIJN9HblmTypes13E_SystemStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d450 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_72Li1ENS_4ListIJN9HblmTypes19E_TemperatureStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9dbe0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_73Li1ENS_4ListIJN9HblmTypes14E_TetheredModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e370 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_74Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e818 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_75Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ebd8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_77Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f3a8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_78Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f788 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_80Li1ENS_4ListIJN9HblmTypes10E_WifiModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa01f0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_81Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa0698 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_82Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa0a78 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18SystemProxyWrapper24registerSignalSubscriberERK7QStringE4$_83Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa0e60 | 992 |
| `_ZN15OdinDbSendUtils21convertStringToBitsetIN9HblmTypes16E_SessionOptionsELm5EEEbRK7QStringRT_` | 0xdb030 | 1876 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_106Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfa588 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_107Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfaa30 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_108Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfae18 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_110Li1ENS_4ListIJN9HblmTypes12E_DriveModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfb598 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_111Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfba40 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_112Li1ENS_4ListIJN9HblmTypes9E_ExpModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfc0e8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_113Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfc590 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_114Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfc950 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_115Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfcd38 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_116Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfd3e0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_117Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfd888 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_118Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfdc70 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_119Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfe118 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_120Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfe4d8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_121Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfe898 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_122Li1ENS_4ListIJN9HblmTypes16E_ExposureStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfec58 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_123Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xff038 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_124Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xff6e0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_125Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xffb88 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_126Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xfff70 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_127Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x100330 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_128Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1006f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_129Li1ENS_4ListIJN9HblmTypes12E_FlashModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x100d98 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_131Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x101600 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_133Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x101d80 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_134Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x102510 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_135Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1029b8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_136Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x102d78 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_137Li1ENS_4ListIJN9HblmTypes12E_FocusModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x103420 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_138Li1ENS_4ListIJN9HblmTypes19E_FocusPeakingColorEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x103bb0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_139Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x104058 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_140Li1ENS_4ListIJN9HblmTypes21E_FocusPointResetModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x104700 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_141Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x104ba8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_143Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x105610 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_144Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x105ab8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_145Li1ENS_4ListIJN9HblmTypes17E_CameraKeyOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x106248 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_146Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1066f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_147Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x106ab0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_148Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x106e98 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_150Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x107640 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_151Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x107a00 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_152Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x107dc0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_153Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1081a8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_154Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x108590 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_155Li1ENS_4ListIJN9HblmTypes10E_IbisModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x108c60 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_156Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1093f0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_157Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x109898 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_158Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x109d40 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_159Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10a100 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10a7c8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10ac70 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10b058 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10b418 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10b8c0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10c040 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10c6e8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10ce78 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_169Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10d608 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10dab0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10de90 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e250 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e610 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10e9d0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10edb8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10f1a0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10f970 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_179Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x10fd30 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_180Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110110 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_181Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1104d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_182Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110890 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_183Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x110c70 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111050 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111818 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x111fe8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_189Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1123a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_190Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112768 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_192Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x112f08 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_193Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1132f0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_194Li1ENS_4ListIJN9HblmTypes15E_LiveViewStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1139c0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_195Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x113e68 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_196Li1ENS_4ListIJRK10QByteArrayEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114228 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_197Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1145e8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_198Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1149a8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_199Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x114d88 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_200Li1ENS_4ListIJN9HblmTypes23E_LiveviewTransportModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115148 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_201Li1ENS_4ListIJN9HblmTypes9E_LmModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x115810 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_203Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116078 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_204Li1ENS_4ListIJN9HblmTypes19E_ManualFocusAssistEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116748 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_205Li1ENS_4ListIJN9HblmTypes13E_MaxApertureEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x116ed8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_206Li1ENS_4ListIJN9HblmTypes13E_FlashStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x117668 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_207Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x117b10 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_208Li1ENS_4ListIJN9HblmTypes16E_OptionOverrideEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x117ef8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_209Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1182d8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_210Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x118698 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_212Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x118e40 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_213Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x119200 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_214Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1195c0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_215Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x119a68 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_216Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11a1f8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_217Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11a6a0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_218Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11aa88 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_219Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11ae70 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_220Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11b230 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_221Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11b618 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_223Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11bdc0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_224Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11c180 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_225Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11c628 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_226Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11ca10 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_227Li1ENS_4ListIJN9HblmTypes14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11cdd0 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_228Li1ENS_4ListIJN9HblmTypes16E_StopDownStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11d498 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_229Li1ENS_4ListIJN9HblmTypes13E_StreamGroupEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11dc28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_230Li1ENS_4ListIJN9HblmTypes18E_SensorUnitStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11e3b8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_231Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11e860 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_232Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11ec20 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_233Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11efe0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_234Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x11f3a0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_238Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1202c0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_239Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x120680 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_242Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1211c0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_243Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1215a0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_245Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x121d20 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_246Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x122108 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_247Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1227b0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_248Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x122c58 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_249Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x123038 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_251Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1237b8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_252Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x123b78 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_253Li1ENS_4ListIJN9HblmTypes12E_WhiteModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x124220 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_256Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x124e48 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_257Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x125518 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_258Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x1259c0 | 956 |
| `_ZN15PhocusProxyDbus24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEj` | 0x1a29a0 | 404 |
| `_ZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiP7QObject` | 0x1e5b10 | 804 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiP7QObjectE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES9_PPvPb` | 0x1e67c8 | 64 |

</details>

**New objects (8)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x25a6dd | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_PhocusProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15PhocusProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IK5QListI4QMapI7QString8QVariantEES9_EENS3_IKjS9_EENS3_IKN9HblmTypes10E_FileTypeES9_EESA_NS3_IKhS9_EENS3_IRK10QByteArrayS9_EEEE` | 0x2f2208 | 64 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_NS3_IS2L_S3S_EES3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x2f3098 | 6400 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_GuiProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEENS3_IN9HblmTypes17E_LiveViewOverlayES6_EENS3_IiS6_EESA_SA_S7_S7_S7_NS3_IjS6_EES7_SC_NS3_INS8_16E_FocusScanRangeES6_EES7_S7_S7_S7_NS3_ItS6_EESC_NS3_INS8_17E_MetadataOverlayES6_EENS3_INS8_10E_OSDClockES6_EESB_NS3_INS8_15E_GuiPopupStateES6_EESC_SB_S7_S7_NS3_INS8_14E_TouchpadAreaES6_EENS3_INS8_21E_TouchpadSensitivityES6_EES7_NS3_INS8_20E_UserButtonFunctionES6_EESR_SR_SR_SR_SR_SR_SR_SB_SB_SB_SB_NS3_I5QListIiES6_EESB_SB_NS3_INS8_19E_UserWheelFunctionES6_EESA_S7_NS3_I8GuiProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbSZ_EES10_NS3_IS9_SZ_EES10_NS3_IiSZ_EES10_S12_S10_S12_S10_S11_S10_S11_S10_S11_S10_NS3_IjSZ_EES10_S11_S10_S14_S10_NS3_ISD_SZ_EES10_S11_S10_S11_S10_S11_S10_S11_S10_NS3_ItSZ_EES10_S14_S10_NS3_ISG_SZ_EES10_NS3_ISI_SZ_EES10_S13_S10_NS3_ISK_SZ_EES10_S14_S10_S13_S10_S11_S10_S11_S10_NS3_ISM_SZ_EES10_NS3_ISO_SZ_EES10_S11_S10_NS3_ISQ_SZ_EES10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S13_S10_S13_S10_S13_S10_S13_S10_NS3_IRKST_SZ_EES10_S13_S10_S13_S10_NS3_ISV_SZ_EES10_S12_EE` | 0x2f4c80 | 1120 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEENS3_IjS8_EES9_NS3_IbS8_EESB_SB_NS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IKhSE_EENS3_IRK10QByteArraySE_EESF_NS3_IS5_SE_EESF_NS3_IjSE_EESF_SM_SF_NS3_IbSE_EESF_SO_EE` | 0x2f51b8 | 160 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_IN9HblmTypes15E_BatteryStatusES6_EENS3_I7QStringS6_EESE_SE_SE_NS3_INSA_16E_BtAssistStatusES6_EESE_S9_S8_S9_NS3_IP15VariantMapModelS6_EES9_NS3_INSA_13E_DebugOptionES6_EES8_S8_S9_S7_NS3_INSA_20E_EyesensorDistancesES6_EES8_NS3_ItS6_EENS3_INSA_17E_MaintenanceTypeES6_EES9_SO_SO_NS3_INSA_10E_ProfilesES6_EES9_SE_S7_S9_S7_S9_S9_S8_NS3_INSA_14E_ScreenStatusES6_EENS3_INSA_9E_ScreensES6_EESW_SW_NS3_INSA_15E_SoundSettingsES6_EES9_NS3_IsS6_EENS3_INSA_24E_SpiritLevelOrientationES6_EES9_SZ_NS3_INSA_21E_SuspendWakeupSourceES6_EES8_S8_NS3_INSA_12E_SoundLevelES6_EENS3_INSA_13E_SystemStateES6_EENS3_INSA_19E_TemperatureStatusES6_EENS3_INSA_14E_TetheredModeES6_EES7_S9_S9_SE_S8_S8_NS3_INSA_10E_WifiModeES6_EESE_S9_SE_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_NS3_I11SystemProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKxS1G_EES1H_NS3_IjS1G_EES1H_NS3_IiS1G_EES1H_S1L_S1H_NS3_IbS1G_EES1H_NS3_ISB_S1G_EES1H_NS3_IRKSD_S1G_EES1H_S1Q_S1H_S1Q_S1H_S1Q_S1H_NS3_ISF_S1G_EES1H_S1Q_S1H_S1M_S1H_S1L_S1H_S1M_S1H_NS3_IPKSH_S1G_EES1H_S1M_S1H_NS3_ISK_S1G_EES1H_S1L_S1H_S1L_S1H_S1M_S1H_S1K_S1H_NS3_ISM_S1G_EES1H_S1L_S1H_NS3_ItS1G_EES1H_NS3_ISP_S1G_EES1H_S1M_S1H_S1X_S1H_S1X_S1H_NS3_ISR_S1G_EES1H_S1M_S1H_S1Q_S1H_S1K_S1H_S1M_S1H_S1K_S1H_S1M_S1H_S1M_S1H_S1L_S1H_NS3_IST_S1G_EES1H_NS3_ISV_S1G_EES1H_S21_S1H_S21_S1H_NS3_ISX_S1G_EES1H_S1M_S1H_NS3_IsS1G_EES1H_NS3_IS10_S1G_EES1H_S1M_S1H_S23_S1H_NS3_IS12_S1G_EES1H_S1L_S1H_S1L_S1H_NS3_IS14_S1G_EES1H_NS3_IS16_S1G_EES1H_NS3_IS18_S1G_EES1H_NS3_IS1A_S1G_EES1H_S1K_S1H_S1M_S1H_S1M_S1H_S1Q_S1H_S1L_S1H_S1L_S1H_NS3_IS1C_S1G_EES1H_S1Q_S1H_S1M_S1H_S1Q_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_EE` | 0x2f5838 | 2072 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x3023f0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x306e28 | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_PhocusProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15PhocusProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IK5QListI4QMapI7QString8QVariantEES9_EENS3_IKjS9_EESA_NS3_IKhS9_EENS3_IRK10QByteArrayS9_EEEE` | 0x2e23b8 | 56 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1M_NS3_IyS6_EESD_S1N_NS3_INS8_16E_ExposureStatusES6_EESD_NS3_INS8_15E_FaceDetectionES6_EES7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1I_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S37_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1N_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3Q_EES3R_NS3_IKNS8_21E_ExposureBlockReasonES3Q_EES3R_NS3_IKNS8_21E_LiveviewBlockReasonES3Q_EES3R_NS3_IbS3Q_EES3R_S41_S3R_S41_S3R_NS3_IS9_S3Q_EES3R_NS3_ISB_S3Q_EES3R_NS3_IiS3Q_EES3R_S41_S3R_NS3_IRKSH_S3Q_EES3R_NS3_ISJ_S3Q_EES3R_NS3_ISL_S3Q_EES3R_NS3_ItS3Q_EES3R_NS3_IPKSO_S3Q_EES3R_S41_S3R_S41_S3R_NS3_ISR_S3Q_EES3R_S44_S3R_NS3_IRKSU_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S41_S3R_S41_S3R_NS3_ISW_S3Q_EES3R_S44_S3R_NS3_ISY_S3Q_EES3R_S44_S3R_S44_S3R_NS3_IjS3Q_EES3R_NS3_IS11_S3Q_EES3R_NS3_IS13_S3Q_EES3R_NS3_IS15_S3Q_EES3R_S41_S3R_S4N_S3R_S41_S3R_S41_S3R_NS3_IS17_S3Q_EES3R_NS3_IS19_S3Q_EES3R_NS3_IS1B_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S41_S3R_NS3_IS1D_S3Q_EES3R_NS3_IS1F_S3Q_EES3R_S41_S3R_S4Q_S3R_NS3_IS1H_S3Q_EES3R_S41_S3R_S44_S3R_S44_S3R_S4S_S3R_S44_S3R_NS3_IS1J_S3Q_EES3R_S4K_S3R_S41_S3R_S44_S3R_NS3_IS1L_S3Q_EES3R_S41_S3R_S4V_S3R_NS3_IyS3Q_EES3R_S44_S3R_S4W_S3R_NS3_IS1O_S3Q_EES3R_S44_S3R_NS3_IS1Q_S3Q_EES3R_S41_S3R_S47_S3R_S44_S3R_S44_S3R_NS3_IS1S_S3Q_EES3R_S44_S3R_S44_S3R_S44_S3R_S4O_S3R_NS3_IS1U_S3Q_EES3R_S47_S3R_S47_S3R_NS3_IS1W_S3Q_EES3R_NS3_IS1Y_S3Q_EES3R_S4K_S3R_NS3_IS20_S3Q_EES3R_S47_S3R_S4K_S3R_NS3_IS22_S3Q_EES3R_S54_S3R_NS3_IS24_S3Q_EES3R_S44_S3R_S41_S3R_S41_S3R_S44_S3R_S44_S3R_S44_S3R_S41_S3R_S41_S3R_S41_S3R_NS3_IS26_S3Q_EES3R_NS3_IS28_S3Q_EES3R_S4T_S3R_S44_S3R_NS3_IS2A_S3Q_EES3R_NS3_IS2C_S3Q_EES3R_S41_S3R_S44_S3R_S4J_S3R_S44_S3R_S44_S3R_S4K_S3R_NS3_IS2E_S3Q_EES3R_NS3_IS2G_S3Q_EES3R_NS3_IS2I_S3Q_EES3R_NS3_IRKSF_S3Q_EES3R_S4A_S3R_S4K_S3R_S4K_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S44_S3R_NS3_IS2L_S3Q_EES3R_S4A_S3R_S4K_S3R_S5F_S3R_S5F_S3R_S41_S3R_S5F_S3R_S41_S3R_S41_S3R_S44_S3R_S44_S3R_S5F_S3R_S44_S3R_S41_S3R_S41_S3R_NS3_IS2N_S3Q_EES3R_S4K_S3R_NS3_IRKS2P_S3Q_EES3R_S44_S3R_S5F_S3R_S4K_S3R_NS3_IS2R_S3Q_EES3R_NS3_IS2T_S3Q_EES3R_S4K_S3R_S41_S3R_NS3_IS2V_S3Q_EES3R_NS3_IS2X_S3Q_EES3R_NS3_IS2Z_S3Q_EES3R_S41_S3R_NS3_IS31_S3Q_EES3R_S4K_S3R_S44_S3R_S41_S3R_S4K_S3R_S44_S3R_S4J_S3R_NS3_IS33_S3Q_EES3R_NS3_IS35_S3Q_EES3R_S41_S3R_S41_S3R_S44_S3R_S41_S3R_S4A_S3R_S41_S3R_NS3_IsS3Q_EES3R_NS3_IS38_S3Q_EES3R_S41_S3R_S5T_S3R_NS3_IS3A_S3Q_EES3R_NS3_IS3C_S3Q_EES3R_NS3_IS3E_S3Q_EES3R_NS3_IS3G_S3Q_EES3R_S44_S3R_S44_S3R_S44_S3R_S4H_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S4W_S3R_S44_S3R_S44_S3R_S4H_S3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_NS3_IS3I_S3Q_EES3R_S4Q_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_NS3_IS3K_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_NS3_IS3M_S3Q_EES3R_S4K_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_EE` | 0x2e3240 | 6304 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_GuiProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes17E_LiveViewOverlayENSt3__117integral_constantIbLb1EEEEENS3_IiS8_EES9_S9_NS3_IbS8_EESB_SB_NS3_IjS8_EESB_SC_NS3_INS4_16E_FocusScanRangeES8_EESB_SB_SB_SB_NS3_ItS8_EESC_NS3_INS4_17E_MetadataOverlayES8_EENS3_INS4_10E_OSDClockES8_EESA_NS3_INS4_15E_GuiPopupStateES8_EESC_SA_SB_SB_NS3_INS4_14E_TouchpadAreaES8_EENS3_INS4_21E_TouchpadSensitivityES8_EESB_NS3_INS4_20E_UserButtonFunctionES8_EESR_SR_SR_SR_SR_SR_SR_SA_SA_SA_SA_NS3_I5QListIiES8_EESA_SA_NS3_INS4_19E_UserWheelFunctionES8_EES9_SB_NS3_I8GuiProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SZ_EES10_NS3_IiSZ_EES10_S11_S10_S11_S10_NS3_IbSZ_EES10_S13_S10_S13_S10_NS3_IjSZ_EES10_S13_S10_S14_S10_NS3_ISD_SZ_EES10_S13_S10_S13_S10_S13_S10_S13_S10_NS3_ItSZ_EES10_S14_S10_NS3_ISG_SZ_EES10_NS3_ISI_SZ_EES10_S12_S10_NS3_ISK_SZ_EES10_S14_S10_S12_S10_S13_S10_S13_S10_NS3_ISM_SZ_EES10_NS3_ISO_SZ_EES10_S13_S10_NS3_ISQ_SZ_EES10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S12_S10_S12_S10_S12_S10_S12_S10_NS3_IRKST_SZ_EES10_S12_S10_S12_S10_NS3_ISV_SZ_EES10_S11_EE` | 0x2e4dc8 | 1096 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEENS3_IjS8_EENS3_IbS8_EESB_SB_NS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IKhSE_EENS3_IRK10QByteArraySE_EESF_NS3_IS5_SE_EESF_NS3_IjSE_EESF_NS3_IbSE_EESF_SO_EE` | 0x2e52e8 | 136 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_I7QStringS6_EESB_SB_SB_NS3_IN9HblmTypes16E_BtAssistStatusES6_EESB_S9_S8_S9_NS3_IP15VariantMapModelS6_EES9_NS3_INSC_13E_DebugOptionES6_EES8_S8_S9_S7_NS3_INSC_20E_EyesensorDistancesES6_EES8_NS3_ItS6_EENS3_INSC_17E_MaintenanceTypeES6_EES9_SM_SM_NS3_INSC_10E_ProfilesES6_EES9_SB_S7_S9_S7_S9_S9_S8_NS3_INSC_14E_ScreenStatusES6_EENS3_INSC_9E_ScreensES6_EESU_SU_NS3_INSC_15E_SoundSettingsES6_EES9_NS3_IsS6_EENS3_INSC_24E_SpiritLevelOrientationES6_EES9_SX_NS3_INSC_21E_SuspendWakeupSourceES6_EES8_S8_NS3_INSC_12E_SoundLevelES6_EENS3_INSC_13E_SystemStateES6_EENS3_INSC_19E_TemperatureStatusES6_EENS3_INSC_14E_TetheredModeES6_EES7_S9_S9_SB_S8_S8_NS3_INSC_10E_WifiModeES6_EESB_S9_SB_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_NS3_I11SystemProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKxS1E_EES1F_NS3_IjS1E_EES1F_NS3_IiS1E_EES1F_S1J_S1F_NS3_IbS1E_EES1F_NS3_IRKSA_S1E_EES1F_S1N_S1F_S1N_S1F_S1N_S1F_NS3_ISD_S1E_EES1F_S1N_S1F_S1K_S1F_S1J_S1F_S1K_S1F_NS3_IPKSF_S1E_EES1F_S1K_S1F_NS3_ISI_S1E_EES1F_S1J_S1F_S1J_S1F_S1K_S1F_S1I_S1F_NS3_ISK_S1E_EES1F_S1J_S1F_NS3_ItS1E_EES1F_NS3_ISN_S1E_EES1F_S1K_S1F_S1U_S1F_S1U_S1F_NS3_ISP_S1E_EES1F_S1K_S1F_S1N_S1F_S1I_S1F_S1K_S1F_S1I_S1F_S1K_S1F_S1K_S1F_S1J_S1F_NS3_ISR_S1E_EES1F_NS3_IST_S1E_EES1F_S1Y_S1F_S1Y_S1F_NS3_ISV_S1E_EES1F_S1K_S1F_NS3_IsS1E_EES1F_NS3_ISY_S1E_EES1F_S1K_S1F_S20_S1F_NS3_IS10_S1E_EES1F_S1J_S1F_S1J_S1F_NS3_IS12_S1E_EES1F_NS3_IS14_S1E_EES1F_NS3_IS16_S1E_EES1F_NS3_IS18_S1E_EES1F_S1I_S1F_S1K_S1F_S1K_S1F_S1N_S1F_S1J_S1F_S1J_S1F_NS3_IS1A_S1E_EES1F_S1N_S1F_S1K_S1F_S1N_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_EE` | 0x2e5950 | 2048 |

### `/bin/camera-gui`

+240 / −179 functions · +92 / −162 objects

**New functions (240)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x32d4f8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x32d508 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x32d510 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x32d510 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x32d520 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x32d538 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x32d5e8 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x32d5f8 | 12 |
| `_ZNK15CommonConstants26numFaceDetectionEnumValuesEv` | 0x333f28 | 116 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x334ff0 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x334ff0 | 452 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_browseview_BrowseListView_qml4$_338__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x36faa0 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_browseview_BrowseListView_qml4$_378__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x36fde8 | 244 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_browseview_BrowseStateMachine_qml4$_288__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x376930 | 244 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_CardStatus_qml4$_448__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3b55a0 | 244 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_components_LinkIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3e9680 | 256 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_ProgressShader_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x419680 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_ProgressShader_qml3$_7clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x41a0f8 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_components_StatusRow_qml4$_218__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x424368 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x426980 | 228 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x426a98 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x426e18 | 228 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x426f00 | 132 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4272f0 | 240 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x428730 | 304 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_WifiStatus_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4452c0 | 300 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x44aa98 | 172 |
| `_ZN21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml4$_198__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x44bbf8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode42_app_qml_components_buttons_FramedItem_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x44d3d8 | 240 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_exposescreen_Exposing_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4851e0 | 228 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_AFIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x489b88 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_liveview_AFIndicator_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x489f30 | 264 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_248__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48ced8 | 96 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48e3d0 | 1204 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48e888 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_27clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48eb08 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_30clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48ed88 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_33clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48f008 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_36clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48f288 | 260 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_FaceIndicator_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x492a60 | 232 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4958f8 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_528__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x496a78 | 96 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x496ad8 | 580 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x496d20 | 332 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4973f0 | 328 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x497b58 | 328 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x497db0 | 272 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x498e30 | 328 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_39clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x499480 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_41clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x499588 | 700 |

<details><summary>… 另 190 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_42clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x499848 | 588 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_45clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x499ce8 | 588 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_49clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x49a040 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_52clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x49a398 | 588 |
| `_ZN21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_288__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49cb58 | 96 |
| `_ZN21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_328__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49cc48 | 96 |
| `_ZN21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_338__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49cca8 | 96 |
| `_ZN21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_418__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49cf80 | 244 |
| `_ZZNK21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_28clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4a0078 | 580 |
| `_ZZNK21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_32clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4a0698 | 580 |
| `_ZZNK21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_33clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4a08e0 | 540 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_IsoWBSelector_qml4$_168__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4a2658 | 228 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1858__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b90c0 | 260 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1868__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b91c8 | 96 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1878__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b9228 | 96 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1988__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b95c8 | 44 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1998__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b95f8 | 44 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_2008__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b9628 | 44 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_2018__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b9658 | 244 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_2028__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b9750 | 716 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_135clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c5ba0 | 696 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_139clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c61b0 | 588 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_141clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c66b8 | 260 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_143clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c67c0 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_151clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c6af0 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_153clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c6c00 | 360 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_163clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c6d68 | 472 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_186clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c77f0 | 588 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_187clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c7a40 | 588 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_191clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c7c90 | 396 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_197clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c7e20 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_198clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c7f30 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_199clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c8040 | 248 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_200clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c8138 | 272 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d4418 | 44 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d4448 | 468 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d4620 | 1064 |
| `_ZZNK21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d4e68 | 260 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d53d0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d64a8 | 244 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_ZoomFlick_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ded08 | 264 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_DateTime_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4e22b0 | 256 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_mainmenu_LicenseView_qml4$_178__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4ed110 | 256 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_mainmenu_MenuBoolSelector_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f2370 | 252 |
| `_ZN21QmlCacheGeneratedCode32_app_qml_mainmenu_MenuHeader_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f4008 | 44 |
| `_ZZNK21QmlCacheGeneratedCode32_app_qml_mainmenu_MenuHeader_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4f47a8 | 244 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_MyLenses_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f7a58 | 264 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x503bb0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x504fa8 | 256 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_mainmenu_SpiritLevelView_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x506630 | 240 |
| `_ZN21QmlCacheGeneratedCode55_app_qml_mainmenu_delegates_ListValueSwitchDelegate_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x50dff8 | 240 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_popups_PopoverCombinationLock_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x523f70 | 44 |
| `_ZZNK21QmlCacheGeneratedCode51_app_qml_mainmenu_popups_PopoverCombinationLock_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x524b10 | 260 |
| `_ZN21QmlCacheGeneratedCode22_app_qml_MainModel_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52a860 | 220 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52abe8 | 228 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52b3f0 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_358__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52c018 | 232 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_368__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52c100 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_378__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52c1f8 | 232 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_408__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52c2e0 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_418__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52c3d8 | 232 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_upgrade_UpgradeViewModel_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52db20 | 264 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml4$_688__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x530558 | 244 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_168__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x537348 | 132 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_upgrade_UpgradePeripheral_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x539e88 | 388 |
| `_ZN21QmlCacheGeneratedCode27_app_qml_popups_Popover_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x53f1a8 | 256 |
| `_ZN21QmlCacheGeneratedCode27_app_qml_popups_Popover_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x53f428 | 44 |
| `_ZZNK21QmlCacheGeneratedCode27_app_qml_popups_Popover_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x540770 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x547e80 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_88__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x547ee0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54a268 | 236 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54a4c0 | 244 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_208__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x553ee8 | 96 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_218__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x553f48 | 96 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_17clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x555030 | 368 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5551a0 | 696 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x555458 | 696 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_208__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x557f00 | 44 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_568__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5590c8 | 224 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_578__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5591a8 | 188 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_588__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x559268 | 44 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_598__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x559298 | 44 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_778__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55a410 | 132 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_798__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55a498 | 132 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_808__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55a520 | 540 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_818__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55a740 | 2332 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_14clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55c0d0 | 232 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55c1b8 | 688 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_17clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55c468 | 368 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55c6c0 | 328 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_33clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55d508 | 696 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55d7c0 | 696 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55da78 | 328 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55de78 | 692 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_41clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55e130 | 272 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_51clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55e620 | 436 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_55clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55e8e8 | 248 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_58clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55e9e0 | 272 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_59clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55eaf0 | 248 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_68clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55ebe8 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_71clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55ed78 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_75clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55f040 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_77clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55f1d0 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_79clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55f360 | 396 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_popups_PopupIconText_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x567570 | 252 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_popups_PopupInform_qml4$_248__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x56a0a8 | 96 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_popups_PopupInform_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x56cea8 | 576 |
| `_ZN21QmlCacheGeneratedCode29_app_qml_proxies_CameraUI_qml4$_208__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x571568 | 232 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x577518 | 288 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_348__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5781e8 | 96 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_358__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x578248 | 96 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_368__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5782a8 | 460 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_408__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x578478 | 88 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_418__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5784d0 | 44 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_428__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x578500 | 44 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_11clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5793b8 | 332 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x579508 | 588 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x579758 | 588 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_41clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5799a8 | 248 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_42clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x579aa0 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x908708 | 108 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x908708 | 108 |
| `_ZN11GuiSettings20ae_lock_touchChangedEb` | 0xa35278 | 100 |
| `_ZN9GuiObject20ae_lock_touchChangedEb` | 0xa37760 | 100 |
| `_ZN11CameraProxy35enabled_face_detection_modesChangedEN9HblmTypes15E_FaceDetectionE` | 0xa3ed98 | 96 |
| `_ZN11PhocusProxy31tethered_capture_clientsChangedEN9HblmTypes7E_HostsE` | 0xa43c70 | 96 |
| `_ZN11SystemProxy21battery_statusChangedEN9HblmTypes15E_BatteryStatusE` | 0xa47328 | 96 |
| `_ZNK15SystemProxyDbus14battery_statusEv` | 0xa72810 | 48 |
| `_ZNK15PhocusProxyDbus24tethered_capture_clientsEv` | 0xa7a2a8 | 48 |
| `_ZN15CameraProxyDbus31setEnabled_face_detection_modesEN9HblmTypes15E_FaceDetectionE` | 0xa839f8 | 308 |
| `_ZNK15CameraProxyDbus28enabled_face_detection_modesEv` | 0xa89c20 | 48 |
| `_ZNK11GuiSettings13ae_lock_touchEv` | 0xaa6148 | 8 |
| `_ZN11GuiSettings16setAe_lock_touchEbb` | 0xaa6150 | 328 |
| `_ZN11GuiSettings18resetAe_lock_touchEv` | 0xaa6298 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_0Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaad988 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_1Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaad9b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_3Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaada18 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_6Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadaa8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_11Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadb98 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_13Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadbf8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_15Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadc58 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_17Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadcb8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_18Li1ENS_4ListIJN9HblmTypes16E_FocusScanRangeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadce8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_25Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaade38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_27Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaade98 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_29Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadef8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_31Li1ENS_4ListIJN9HblmTypes17E_MetadataOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadf58 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_32Li1ENS_4ListIJN9HblmTypes10E_OSDClockEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadf88 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_34Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaadfe8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_35Li1ENS_4ListIJN9HblmTypes15E_GuiPopupStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae018 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_37Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae078 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_38Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae0a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_41Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae138 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_43Li1ENS_4ListIJN9HblmTypes14E_TouchpadAreaEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae198 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_45Li1ENS_4ListIJN9HblmTypes21E_TouchpadSensitivityEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae1f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_46Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae228 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_55Li1ENS_4ListIJN9HblmTypes20E_UserButtonFunctionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae3d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_63Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae558 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_65Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae5b8 | 40 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_69Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae670 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_70Li1ENS_4ListIJN9HblmTypes19E_UserWheelFunctionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae6a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_72Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaae700 | 44 |
| `_ZN21QmlCacheGeneratedCode37_touchtest_qml_FreeStyleTouchTest_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xab2d40 | 256 |
| `_ZN21QmlCacheGeneratedCode19_sutest_qml_Led_qml3$_18__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xacb5d0 | 264 |
| `_ZN13GuiObjectImpl16setAe_lock_touchEb` | 0xadc730 | 16 |
| `_ZNK13GuiObjectImpl13ae_lock_touchEv` | 0xadc740 | 120 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13GuiObjectImplC1EP7QObjectE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xadda98 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13GuiObjectImplC1EP7QObjectE4$_42Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaddae8 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13GuiObjectImplC1EP7QObjectE4$_43Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaddb38 | 80 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13GuiObjectImpl22initExportedStateTimerEvE4$_44Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaddb88 | 196 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0xae0630 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0xae0630 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0xae0728 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0xae0728 | 248 |
| `_ZNK17QSGMaterialShader13versionSuffixEv` | 0xf858e0 | 3840 |
| `_ZNSt3__124__optional_destruct_baseI7QStringLb0EED2Ev` | 0xf867e0 | 56 |
| `_ZNSt3__17__stateIcEC2ERKS1_` | 0xf8b238 | 288 |
| `_ZNK8LensData12usePrefilledEv` | 0x1047fa8 | 312 |
| `_ZN8LensData19usePrefilledChangedEb` | 0x1061a90 | 100 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringED2Ev` | 0x1084f28 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringED2Ev` | 0x1084f28 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringE6insertERKS1_RKS2_` | 0x10bbba8 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage7MetaTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x10bbd30 | 392 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringE6insertERKS1_RKS2_` | 0x10bbeb8 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage10StorageTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x10bc040 | 392 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x10da0b0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x10da148 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x10da150 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x10da2d0 | 200 |
| `_ZL31hb_font_get_glyph_v_advance_nilP9hb_font_tPvjS1_` | 0x11d2c88 | 8 |

</details>

**Removed functions (179)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN21QmlCacheGeneratedCode38_app_qml_browseview_BrowseListView_qml4$_398__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x36d5e0 | 244 |
| `_ZN21QmlCacheGeneratedCode50_app_qml_browseview_ColorPickerMetadataOverlay_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x37c128 | 132 |
| `_ZZNK21QmlCacheGeneratedCode50_app_qml_browseview_ColorPickerMetadataOverlay_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x37f778 | 388 |
| `_ZN21QmlCacheGeneratedCode34_app_qml_components_CardStatus_qml4$_418__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3b2bc8 | 244 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_components_ControlScreenSwipeArea_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3c7608 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_components_ControlScreenSwipeArea_qml4$_14clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3c7be8 | 236 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_ExposureButton_qml4$_198__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3d0ec8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_ExposureButton_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3d3418 | 244 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x3e9420 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_MetadataLensData_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x3ea4b8 | 240 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_components_PageListView_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x40b4e0 | 244 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_components_Scrollbar_qml3$_38__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x41bc40 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4242b8 | 172 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4243f8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x424a50 | 244 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_components_StorageIndicator_qml4$_13clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x425e98 | 304 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_components_TextCheckboxRow_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4298e0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_components_TextCheckboxRow_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x42afe8 | 244 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_components_TimeoutText_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x431688 | 132 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_components_TimeoutText_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x431a78 | 388 |
| `_ZN21QmlCacheGeneratedCode54_app_qml_components_buttons_BracketedCameraControl_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4448c0 | 240 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_components_buttons_Button_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x445ae0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode38_app_qml_components_buttons_Button_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4471b8 | 244 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedControl_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x469670 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_controlscreen_ShutterSpeedControl_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x469c50 | 236 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_error_ErrorNonAck_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x46f250 | 256 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_error_ErrorUsbConnected_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x473198 | 256 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeProgress_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x47f2c0 | 44 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_exposescreen_ExposeProgress_qml3$_6clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4801b8 | 244 |
| `_ZN21QmlCacheGeneratedCode45_app_qml_exposescreen_IntervalTimerScreen_qml3$_48__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x484450 | 252 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_238__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48ab30 | 264 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_378__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48ba00 | 96 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48c130 | 1204 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48c5e8 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_28clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48c868 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_31clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48cae8 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48cd68 | 636 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_liveview_AfSymbol_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48cfe8 | 260 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_EvfBrightnessSelector_qml3$_58__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x48d468 | 44 |
| `_ZZNK21QmlCacheGeneratedCode43_app_qml_liveview_EvfBrightnessSelector_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x48d800 | 232 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x493280 | 96 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_138__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4936c0 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_228__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x493b38 | 96 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x493c28 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x493c58 | 44 |
| `_ZN21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_468__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4944b8 | 244 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4947d8 | 580 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_2clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x494a20 | 576 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x494c60 | 316 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x495108 | 372 |

<details><summary>… 另 129 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_13clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x495620 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x495ac0 | 272 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x495ce0 | 588 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_22clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x495f30 | 588 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x496520 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x496628 | 328 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_36clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x497340 | 696 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_40clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x497950 | 700 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_47clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x497e60 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_50clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x498070 | 588 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_liveview_FocusIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4988e0 | 240 |
| `_ZN21QmlCacheGeneratedCode25_app_qml_liveview_HTS_qml4$_458__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49af70 | 244 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_liveview_IsoWBSelector_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x49fea0 | 256 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_LensDriveStateMachine_qml4$_148__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4a95b8 | 244 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml4$_488__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b1fc0 | 244 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1898__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b6ad8 | 264 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1908__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b6be0 | 188 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1928__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b6d60 | 44 |
| `_ZN21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_1938__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4b6d90 | 44 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_119clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c14e8 | 696 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_138clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c3bf0 | 260 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_142clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c3e08 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_150clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c4138 | 360 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_160clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c42a0 | 472 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_177clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c4478 | 1004 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_178clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c4868 | 360 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_192clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c51c8 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_193clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c52d8 | 272 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_194clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c53e8 | 248 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_195clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4c54e0 | 272 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_MFAssistDistanceScale_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4c62d0 | 240 |
| `_ZZNK21QmlCacheGeneratedCode37_app_qml_liveview_OverlayListView_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4cb100 | 244 |
| `_ZN21QmlCacheGeneratedCode43_app_qml_liveview_ShutterSpeedIndicator_qml3$_68__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d19a8 | 544 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2448 | 44 |
| `_ZN21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_118__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4d2478 | 44 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_10clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d3550 | 256 |
| `_ZZNK21QmlCacheGeneratedCode31_app_qml_liveview_SliderBar_qml4$_11clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4d3650 | 244 |
| `_ZN21QmlCacheGeneratedCode30_app_qml_mainmenu_MyLenses_qml4$_388__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x4f4c48 | 44 |
| `_ZZNK21QmlCacheGeneratedCode30_app_qml_mainmenu_MyLenses_qml4$_38clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x4f8d98 | 248 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x500890 | 44 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_mainmenu_SettingSlider_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x501d50 | 244 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SliderDelegate_qml4$_158__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x50c618 | 44 |
| `_ZZNK21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SliderDelegate_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x50e3b0 | 232 |
| `_ZZNK21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_StorageInfoDelegate_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x512278 | 224 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SwitchDelegate_qml3$_08__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5147e8 | 240 |
| `_ZN21QmlCacheGeneratedCode46_app_qml_mainmenu_delegates_SwitchDelegate_qml4$_128__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x514dc8 | 256 |
| `_ZZNK21QmlCacheGeneratedCode44_app_qml_mainmenu_delegates_TextDelegate_qml3$_3clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x518f68 | 232 |
| `_ZN21QmlCacheGeneratedCode51_app_qml_mainmenu_delegates_ValueSwitchDelegate_qml3$_78__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x519918 | 256 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_mainmenu_popups_DiskFormat_qml3$_98__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x51c180 | 220 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_208__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x528540 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_218__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x528638 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_228__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x528730 | 232 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_238__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x528818 | 244 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_308__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x528eb0 | 232 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_328__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x529080 | 232 |
| `_ZN21QmlCacheGeneratedCode26_app_qml_MainViewState_qml4$_388__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x529348 | 232 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52b750 | 228 |
| `_ZN21QmlCacheGeneratedCode33_app_qml_upgrade_UpgradeCheck_qml4$_658__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x52d2b8 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_448__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x545ca0 | 44 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_638__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5466d0 | 244 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_658__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5468d0 | 244 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_14clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x547998 | 232 |
| `_ZZNK21QmlCacheGeneratedCode36_app_qml_popups_PopoverDriveMode_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x54a1c0 | 260 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x551a38 | 356 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x551ba0 | 696 |
| `_ZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_19clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x551e58 | 696 |
| `_ZN21QmlCacheGeneratedCode36_app_qml_popups_PopoverFocusMode_qml4$_108__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x552370 | 152 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_258__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x554c58 | 44 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_468__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x5557c8 | 44 |
| `_ZN21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_628__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x555ea8 | 244 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x558668 | 316 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5588a8 | 332 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_22clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5589f8 | 332 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x558e00 | 696 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x5590b8 | 328 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_40clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55a1d8 | 272 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55a2e8 | 272 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_46clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55a5b8 | 436 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_53clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55a978 | 272 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_63clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55ab80 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_66clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55ad10 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_67clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55aea0 | 308 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_70clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55afd8 | 396 |
| `_ZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_74clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x55b2f8 | 396 |
| `_ZN21QmlCacheGeneratedCode38_app_qml_popups_PopoverMeterMethod_qml3$_28__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55b810 | 320 |
| `_ZN21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_368__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x55e4d8 | 44 |
| `_ZZNK21QmlCacheGeneratedCode39_app_qml_popups_PopoverWhiteBalance_qml4$_36clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x562258 | 260 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_268__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x573348 | 520 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_378__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x573dd8 | 44 |
| `_ZN21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_388__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0x573e08 | 44 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_31clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x574cc0 | 588 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_32clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x574f10 | 588 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x575160 | 248 |
| `_ZZNK21QmlCacheGeneratedCode41_app_qml_viewmodels_LiveviewViewModel_qml4$_38clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_` | 0x575258 | 248 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_0Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8460 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_1Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8490 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_3Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa84f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE3$_6Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8580 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_11Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8670 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_13Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa86d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_15Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8730 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_17Li1ENS_4ListIJN9HblmTypes16E_FocusScanRangeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8790 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_18Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa87c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_25Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8910 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_27Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8970 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_29Li1ENS_4ListIJN9HblmTypes17E_MetadataOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa89d0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_31Li1ENS_4ListIJN9HblmTypes10E_OSDClockEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8a30 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_32Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8a60 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_34Li1ENS_4ListIJN9HblmTypes15E_GuiPopupStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8ac0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_35Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8af0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_37Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8b50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_38Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8b80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_41Li1ENS_4ListIJN9HblmTypes14E_TouchpadAreaEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8c10 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_43Li1ENS_4ListIJN9HblmTypes21E_TouchpadSensitivityEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8c70 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_45Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8cd0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_46Li1ENS_4ListIJN9HblmTypes20E_UserButtonFunctionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8d00 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_55Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa8eb0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_63Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa9030 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_65Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa9088 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_69Li1ENS_4ListIJN9HblmTypes19E_UserWheelFunctionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa9148 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN9GuiObjectC1EP7QObjectbE4$_70Li1ENS_4ListIJN9HblmTypes17E_LiveViewOverlayEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0xaa9178 | 44 |
| `_ZN21QmlCacheGeneratedCode27_sutest_qml_displaytest_qml4$_198__invokeEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_` | 0xac1708 | 228 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13GuiObjectImpl22initExportedStateTimerEvE4$_41Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xad7ea8 | 196 |
| `_ZNSt3__16vectorINS_9sub_matchIPKcEENS_9allocatorIS4_EEEC2ERKS7_` | 0x10b0dc8 | 204 |
| `_ZNSt3__16vectorINS_4pairImPKcEENS_9allocatorIS4_EEEC2ERKS7_` | 0x10b0e98 | 164 |
| `_ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE19__parse_atom_escapeIPKcEET_S7_S7_` | 0x10b0f40 | 220 |
| `_ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE11__push_loopEmmPNS_16__owns_one_stateIcEEmmb` | 0x10b5790 | 360 |
| `_ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE17__parse_DUP_COUNTIPKcEET_S7_S7_Ri` | 0x10b58f8 | 240 |
| `_ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE18__parse_ERE_branchIPKcEET_S7_S7_` | 0x10b6390 | 152 |

</details>

**New objects (92)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZL27hblm_prop_gui_ae_lock_touch` | 0x15393df | 14 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x1d1f1c5 | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CommonConstants_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEES7_S7_S7_S7_NS3_I7QPointFS6_EES7_S7_S7_S7_S7_S7_S7_S7_NS3_I5QSizeS6_EESB_SB_SB_SB_SB_SB_SB_SB_SB_NS3_I6QSizeFS6_EESD_SD_SD_NS3_IjS6_EESE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_NS3_I7QStringS6_EESG_SG_SG_SG_SG_SE_SG_SG_SG_SG_NS3_IfS6_EESG_SG_SG_SG_SG_SG_SG_S7_NS3_I15CommonConstantsS6_EENS3_IS8_NS5_IbLb0EEEEENS3_IKS8_SK_EENS3_IN9HblmTypes11E_FocusSizeESK_EENS3_INSO_10E_CropModeESK_EENS3_IKiSK_EESU_SL_SN_SQ_SS_SL_SL_NS3_INSO_11E_ZoomLevelESK_EESS_SL_SQ_SS_NS3_IiSK_EESX_NS3_ISF_SK_EENS3_INSO_12E_CameraTypeESK_EENS3_IbSK_EENS3_IRKSA_SK_EES14_NS3_ISC_SK_EESS_SL_SX_SX_NS3_IRSM_SK_EES11_NS3_IRKSF_SK_EEEE` | 0x2099178 | 792 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_GuiSettings_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEENS3_IN9HblmTypes17E_LiveViewOverlayES6_EENS3_IiS6_EESA_SA_S7_S7_S7_NS3_IjS6_EES7_SC_NS3_INS8_16E_FocusScanRangeES6_EES7_S7_S7_S7_NS3_ItS6_EESC_NS3_INS8_17E_MetadataOverlayES6_EESB_SC_S7_S7_NS3_INS8_14E_TouchpadAreaES6_EENS3_INS8_21E_TouchpadSensitivityES6_EES7_NS3_INS8_20E_UserButtonFunctionES6_EESN_SN_SN_SN_SN_SN_SN_SB_SB_SB_SB_NS3_I5QListIiES6_EESB_SB_NS3_INS8_19E_UserWheelFunctionES6_EESA_NS3_I11GuiSettingsS6_EENS3_IvNS5_IbLb0EEEEENS3_IjSV_EESW_SX_SW_NS3_INS8_10E_ProfilesESV_EESW_NS3_I7QStringSV_EENS3_I8QVariantSV_EENS3_IbSV_EESW_NS3_IKbSV_EESW_NS3_IKS9_SV_EESW_NS3_IKiSV_EESW_S18_SW_S18_SW_S16_SW_S16_SW_S16_SW_NS3_IKjSV_EESW_S16_SW_S1C_SW_NS3_IKSD_SV_EESW_S16_SW_S16_SW_S16_SW_S16_SW_NS3_IKtSV_EESW_S1C_SW_NS3_IKSG_SV_EESW_S1A_SW_S1C_SW_S16_SW_S16_SW_NS3_IKSI_SV_EESW_NS3_IKSK_SV_EESW_S16_SW_NS3_IKSM_SV_EESW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1A_SW_S1A_SW_S1A_SW_S1A_SW_NS3_IRKSP_SV_EESW_S1A_SW_S1A_SW_NS3_IKSR_SV_EESW_S18_SW_S16_S14_SW_S16_SW_SW_S18_S14_SW_S18_SW_SW_S1A_S14_SW_S1A_SW_SW_S18_S14_SW_S18_SW_SW_S18_S14_SW_S18_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S1C_S14_SW_S1C_SW_SW_S16_S14_SW_S16_SW_SW_S1C_S14_SW_S1C_SW_SW_S1E_S14_SW_S1E_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S1G_S14_SW_S1G_SW_SW_S1C_S14_SW_S1C_SW_SW_S1I_S14_SW_S1I_SW_SW_S1A_S14_SW_S1A_SW_SW_S1C_S14_SW_S1C_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S1K_S14_SW_S1K_SW_SW_S1M_S14_SW_S1M_SW_SW_S16_S14_SW_S16_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1R_S14_SW_S1R_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1T_S14_SW_S1T_SW_SW_S18_S14_SW_S18_SW_SW_SZ_SW_SZ_EE` | 0x20bdb30 | 3216 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_130qt_meta_stringdata_GuiObject_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_S8_S8_S7_S7_S7_NS3_IjS6_EES7_S9_S8_S7_S7_S7_S7_NS3_ItS6_EES9_S8_S8_S8_S8_S9_S8_S7_S7_S8_S8_S7_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_S8_NS3_I5QListIiES6_EES8_S8_S8_S8_NS3_I9GuiObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKbSG_EESH_NS3_IKN9HblmTypes17E_LiveViewOverlayESG_EESH_NS3_IKiSG_EESH_SN_SH_SN_SH_SJ_SH_SJ_SH_SJ_SH_NS3_IKjSG_EESH_SJ_SH_SR_SH_NS3_IKNSK_16E_FocusScanRangeESG_EESH_SJ_SH_SJ_SH_SJ_SH_SJ_SH_NS3_IKtSG_EESH_SR_SH_NS3_IKNSK_17E_MetadataOverlayESG_EESH_NS3_IKNSK_10E_OSDClockESG_EESH_SP_SH_NS3_IKNSK_15E_GuiPopupStateESG_EESH_SR_SH_SP_SH_SJ_SH_SJ_SH_NS3_IKNSK_14E_TouchpadAreaESG_EESH_NS3_IKNSK_21E_TouchpadSensitivityESG_EESH_SJ_SH_NS3_IKNSK_20E_UserButtonFunctionESG_EESH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_SP_SH_SP_SH_SP_SH_SP_SH_NS3_IRKSC_SG_EESH_SP_SH_SP_SH_NS3_IKNSK_19E_UserWheelFunctionESG_EESH_SN_EE` | 0x20be7f8 | 1112 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESS_SS_S7_SS_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESS_NS3_INS8_12E_ExitOptionES6_EESS_SS_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES16_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESS_SS_S7_SS_S7_SS_S7_SS_SS_SS_SS_SS_NS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SS_SS_S1E_SS_NS3_INS8_9E_ExpModeES6_EES10_S7_SS_NS3_INS8_21E_ExposureControlModeES6_EES7_NS3_IyS6_EESS_S1N_NS3_INS8_16E_ExposureStatusES6_EESS_S1G_S7_SH_SS_NS3_INS8_12E_FlashModesES6_EESS_SS_SS_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESH_SH_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESH_S10_NS3_INS8_11E_FocusSizeES6_EES21_NS3_INS8_17E_CameraKeyOptionES6_EESS_S7_S7_SS_SS_SS_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1I_SS_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SS_SZ_SS_SS_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISE_S6_EESM_S7_S7_S7_S7_SS_NS3_INS8_17E_LensMfRingStateES6_EESM_S2I_S2I_S7_S7_S7_SS_SS_S2I_SS_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESS_S2I_NS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EESS_S7_SS_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SS_SM_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S33_NS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESS_SS_SS_SV_SS_SS_SS_SS_S1N_SS_SV_SS_SS_S7_SS_NS3_INS8_14E_DistanceUnitES6_EES1C_SS_SS_SS_SS_NS3_INS8_12E_WhiteModesES6_EESS_SS_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3I_EES3J_NS3_IKNS8_21E_ExposureBlockReasonES3I_EES3J_NS3_IKNS8_21E_LiveviewBlockReasonES3I_EES3J_NS3_IbS3I_EES3J_S3T_S3J_NS3_IS9_S3I_EES3J_NS3_ISB_S3I_EES3J_S3T_S3J_NS3_IRKSG_S3I_EES3J_NS3_ISI_S3I_EES3J_NS3_ISK_S3I_EES3J_NS3_ItS3I_EES3J_NS3_IPKSN_S3I_EES3J_S3T_S3J_S3T_S3J_NS3_ISQ_S3I_EES3J_NS3_IiS3I_EES3J_NS3_IRKSU_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_ISW_S3I_EES3J_S46_S3J_NS3_ISY_S3I_EES3J_S46_S3J_S46_S3J_NS3_IjS3I_EES3J_NS3_IS11_S3I_EES3J_NS3_IS13_S3I_EES3J_NS3_IS15_S3I_EES3J_S4F_S3J_NS3_IS17_S3I_EES3J_NS3_IS19_S3I_EES3J_NS3_IS1B_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS1D_S3I_EES3J_S3T_S3J_S4I_S3J_NS3_IS1F_S3I_EES3J_NS3_IS1H_S3I_EES3J_S3T_S3J_S46_S3J_S46_S3J_S4J_S3J_S46_S3J_NS3_IS1J_S3I_EES3J_S4C_S3J_S3T_S3J_S46_S3J_NS3_IS1L_S3I_EES3J_S3T_S3J_NS3_IyS3I_EES3J_S46_S3J_S4O_S3J_NS3_IS1O_S3I_EES3J_S46_S3J_S4K_S3J_S3T_S3J_S3Y_S3J_S46_S3J_NS3_IS1Q_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S4G_S3J_NS3_IS1S_S3I_EES3J_S3Y_S3J_S3Y_S3J_NS3_IS1U_S3I_EES3J_NS3_IS1W_S3I_EES3J_S4C_S3J_NS3_IS1Y_S3I_EES3J_S3Y_S3J_S4C_S3J_NS3_IS20_S3I_EES3J_S4V_S3J_NS3_IS22_S3I_EES3J_S46_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_IS24_S3I_EES3J_NS3_IS26_S3I_EES3J_S4L_S3J_S46_S3J_NS3_IS28_S3I_EES3J_NS3_IS2A_S3I_EES3J_S3T_S3J_S46_S3J_S4B_S3J_S46_S3J_S46_S3J_S4C_S3J_NS3_IS2C_S3I_EES3J_NS3_IS2E_S3I_EES3J_NS3_IS2G_S3I_EES3J_NS3_IRKSE_S3I_EES3J_S41_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_NS3_IS2J_S3I_EES3J_S41_S3J_S56_S3J_S56_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S56_S3J_S46_S3J_S3T_S3J_NS3_IS2L_S3I_EES3J_S4C_S3J_NS3_IRKS2N_S3I_EES3J_S46_S3J_S56_S3J_NS3_IS2P_S3I_EES3J_S4C_S3J_S3T_S3J_NS3_IS2R_S3I_EES3J_NS3_IS2T_S3I_EES3J_NS3_IS2V_S3I_EES3J_S3T_S3J_NS3_IS2X_S3I_EES3J_S46_S3J_S3T_S3J_S46_S3J_S4B_S3J_NS3_IS2Z_S3I_EES3J_NS3_IS31_S3I_EES3J_S3T_S3J_S3T_S3J_S46_S3J_S41_S3J_S3T_S3J_NS3_IsS3I_EES3J_NS3_IS34_S3I_EES3J_S3T_S3J_S5J_S3J_NS3_IS36_S3I_EES3J_NS3_IS38_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S4O_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_NS3_IS3A_S3I_EES3J_S4I_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS3C_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_NS3_IS3E_S3I_EES3J_S4C_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_EE` | 0x20bec98 | 5200 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEES9_NS3_IbS8_EENS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SD_EESE_SF_EE` | 0x20c0280 | 64 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_IN9HblmTypes15E_BatteryStatusES6_EENS3_I7QStringS6_EESE_NS3_INSA_16E_BtAssistStatusES6_EESE_S8_S9_NS3_IP15VariantMapModelS6_EES9_NS3_INSA_13E_DebugOptionES6_EES8_S8_S9_S7_NS3_INSA_20E_EyesensorDistancesES6_EES8_NS3_ItS6_EENS3_INSA_17E_MaintenanceTypeES6_EES9_SO_SO_NS3_INSA_10E_ProfilesES6_EESE_S9_S9_S9_S8_NS3_INSA_14E_ScreenStatusES6_EENS3_INSA_9E_ScreensES6_EESW_SW_NS3_INSA_15E_SoundSettingsES6_EES9_NS3_IsS6_EENS3_INSA_24E_SpiritLevelOrientationES6_EES9_SZ_S8_S8_NS3_INSA_12E_SoundLevelES6_EENS3_INSA_13E_SystemStateES6_EENS3_INSA_19E_TemperatureStatusES6_EENS3_INSA_14E_TetheredModeES6_EES7_S9_S9_SE_S8_S8_NS3_INSA_10E_WifiModeES6_EESE_S9_SE_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_NS3_I11SystemProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IjS1E_EES1F_NS3_IiS1E_EES1F_S1H_S1F_NS3_IbS1E_EES1F_NS3_ISB_S1E_EES1F_NS3_IRKSD_S1E_EES1F_S1M_S1F_NS3_ISF_S1E_EES1F_S1M_S1F_S1H_S1F_S1I_S1F_NS3_IPKSH_S1E_EES1F_S1I_S1F_NS3_ISK_S1E_EES1F_S1H_S1F_S1H_S1F_S1I_S1F_S1G_S1F_NS3_ISM_S1E_EES1F_S1H_S1F_NS3_ItS1E_EES1F_NS3_ISP_S1E_EES1F_S1I_S1F_S1T_S1F_S1T_S1F_NS3_ISR_S1E_EES1F_S1M_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1H_S1F_NS3_IST_S1E_EES1F_NS3_ISV_S1E_EES1F_S1X_S1F_S1X_S1F_NS3_ISX_S1E_EES1F_S1I_S1F_NS3_IsS1E_EES1F_NS3_IS10_S1E_EES1F_S1I_S1F_S1Z_S1F_S1H_S1F_S1H_S1F_NS3_IS12_S1E_EES1F_NS3_IS14_S1E_EES1F_NS3_IS16_S1E_EES1F_NS3_IS18_S1E_EES1F_S1G_S1F_S1I_S1F_S1I_S1F_S1M_S1F_S1H_S1F_S1H_S1F_NS3_IS1A_S1E_EES1F_S1M_S1F_S1I_S1F_S1M_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_S1F_S1I_EE` | 0x20c0638 | 1768 |
| `_Z16qt_metaTypeArrayIJ7QStringS0_S0_S0_S0_iS0_S0_S0_S0_5QListIS0_ES2_S2_S2_S2_bibbb8LensDatavS0_vS0_vS0_vS0_vS0_vS0_vS0_vS0_vS0_vS2_vS2_vS2_vS2_vS2_vivivbvbvbvbvvvS0_iS0_iiiibEE` | 0x2102170 | 576 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x21a0e40 | 112 |
| `_ZN10MenuCommonL23kAeLockTouchDescriptionE` | 0x21af1c0 | 24 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d50 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_1clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d58 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d60 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_5clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d68 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d70 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_9clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d78 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d80 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d88 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d90 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4d98 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4da0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4da8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_28clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4dc0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_28clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4dc8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_32clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4de0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_32clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4de8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4df0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4df8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4e00 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b4e08 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_129clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b57b0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_129clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b57b8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_133clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b57e0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_133clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b57e8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_134clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b57f0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_134clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b57f8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_135clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5800 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_135clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5808 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_143clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5820 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_143clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5828 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_151clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5850 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_151clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5858 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_153clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5860 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_153clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5868 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_181clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5880 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_181clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5888 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_182clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5890 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_182clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b5898 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_183clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58a0 | 8 |

<details><summary>… 另 42 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_183clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58a8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_191clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58b0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_191clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58b8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_197clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58c0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_197clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58c8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_198clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58d0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_198clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58d8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_200clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58e0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_200clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b58e8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8b18 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8b20 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8b28 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8b30 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8c48 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_12clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8c50 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8c58 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8c60 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8c68 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_20clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8c70 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_33clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8cf8 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_33clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d00 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d08 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d10 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d18 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_35clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d20 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d38 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_37clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d40 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_41clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d48 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_41clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d50 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_45clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d58 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_45clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d60 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_54clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d78 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_54clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d80 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_58clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d88 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_58clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21b8d90 | 8 |
| `_ZN12_GLOBAL__N_110kTouchRuleE` | 0x21bef20 | 24 |
| `_ZN12_GLOBAL__N_120kPointerHandlerRulesE` | 0x21bef38 | 24 |
| `_ZZNK17QSGMaterialShader13versionSuffixEvE6suffix` | 0x21c9550 | 32 |
| `_ZGVZNK17QSGMaterialShader13versionSuffixEvE6suffix` | 0x21c9570 | 8 |
| `_ZN12_GLOBAL__N_111kMetaTagMapE` | 0x21cb4e0 | 8 |
| `_ZN12_GLOBAL__N_114kStorageTagMapE` | 0x21cb4e8 | 8 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x21cbcc4 | 4 |

</details>

**Removed objects (162)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_CommonConstants_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEES7_S7_S7_S7_NS3_I7QPointFS6_EES7_S7_S7_S7_S7_S7_S7_NS3_I5QSizeS6_EESB_SB_SB_SB_SB_SB_SB_SB_SB_NS3_I6QSizeFS6_EESD_SD_SD_NS3_IjS6_EESE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_SE_NS3_I7QStringS6_EESG_SG_SG_SG_SG_SE_SG_SG_SG_SG_NS3_IfS6_EESG_SG_SG_SG_SG_SG_SG_S7_NS3_I15CommonConstantsS6_EENS3_IS8_NS5_IbLb0EEEEENS3_IKS8_SK_EENS3_IN9HblmTypes11E_FocusSizeESK_EENS3_INSO_10E_CropModeESK_EENS3_IKiSK_EESU_SL_SN_SQ_SS_SL_SL_NS3_INSO_11E_ZoomLevelESK_EESS_SL_SQ_SS_NS3_IiSK_EESX_NS3_ISF_SK_EENS3_INSO_12E_CameraTypeESK_EENS3_IbSK_EENS3_IRKSA_SK_EES14_NS3_ISC_SK_EESS_SL_SX_SX_NS3_IRSM_SK_EES11_NS3_IRKSF_SK_EEEE` | 0x20891d0 | 784 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_GuiSettings_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes17E_LiveViewOverlayENSt3__117integral_constantIbLb1EEEEENS3_IiS8_EES9_S9_NS3_IbS8_EESB_SB_NS3_IjS8_EESB_SC_NS3_INS4_16E_FocusScanRangeES8_EESB_SB_SB_SB_NS3_ItS8_EESC_NS3_INS4_17E_MetadataOverlayES8_EESA_SC_SB_SB_NS3_INS4_14E_TouchpadAreaES8_EENS3_INS4_21E_TouchpadSensitivityES8_EESB_NS3_INS4_20E_UserButtonFunctionES8_EESN_SN_SN_SN_SN_SN_SN_SA_SA_SA_SA_NS3_I5QListIiES8_EESA_SA_NS3_INS4_19E_UserWheelFunctionES8_EES9_NS3_I11GuiSettingsS8_EENS3_IvNS7_IbLb0EEEEENS3_IjSV_EESW_SX_SW_NS3_INS4_10E_ProfilesESV_EESW_NS3_I7QStringSV_EENS3_I8QVariantSV_EENS3_IbSV_EESW_NS3_IKS5_SV_EESW_NS3_IKiSV_EESW_S16_SW_S16_SW_NS3_IKbSV_EESW_S1A_SW_S1A_SW_NS3_IKjSV_EESW_S1A_SW_S1C_SW_NS3_IKSD_SV_EESW_S1A_SW_S1A_SW_S1A_SW_S1A_SW_NS3_IKtSV_EESW_S1C_SW_NS3_IKSG_SV_EESW_S18_SW_S1C_SW_S1A_SW_S1A_SW_NS3_IKSI_SV_EESW_NS3_IKSK_SV_EESW_S1A_SW_NS3_IKSM_SV_EESW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S1O_SW_S18_SW_S18_SW_S18_SW_S18_SW_NS3_IRKSP_SV_EESW_S18_SW_S18_SW_NS3_IKSR_SV_EESW_S16_SW_S16_S14_SW_S16_SW_SW_S18_S14_SW_S18_SW_SW_S16_S14_SW_S16_SW_SW_S16_S14_SW_S16_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1C_S14_SW_S1C_SW_SW_S1A_S14_SW_S1A_SW_SW_S1C_S14_SW_S1C_SW_SW_S1E_S14_SW_S1E_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1G_S14_SW_S1G_SW_SW_S1C_S14_SW_S1C_SW_SW_S1I_S14_SW_S1I_SW_SW_S18_S14_SW_S18_SW_SW_S1C_S14_SW_S1C_SW_SW_S1A_S14_SW_S1A_SW_SW_S1A_S14_SW_S1A_SW_SW_S1K_S14_SW_S1K_SW_SW_S1M_S14_SW_S1M_SW_SW_S1A_S14_SW_S1A_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S1O_S14_SW_S1O_SW_SW_S18_S14_SW_S18_SW_SW_S18_S14_SW_S18_SW_SW_S18_S14_SW_S18_SW_SW_S18_S14_SW_S18_SW_SW_S1R_S14_SW_S1R_SW_SW_S18_S14_SW_S18_SW_SW_S18_S14_SW_S18_SW_SW_S1T_S14_SW_S1T_SW_SW_S16_S14_SW_S16_SW_SW_SZ_SW_SZ_EE` | 0x20adb80 | 3144 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_130qt_meta_stringdata_GuiObject_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEES7_S7_S7_NS3_IbS6_EES8_S8_NS3_IjS6_EES8_S9_S7_S8_S8_S8_S8_NS3_ItS6_EES9_S7_S7_S7_S7_S9_S7_S8_S8_S7_S7_S8_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I5QListIiES6_EES7_S7_S7_S7_NS3_I9GuiObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKN9HblmTypes17E_LiveViewOverlayESG_EESH_NS3_IKiSG_EESH_SL_SH_SL_SH_NS3_IKbSG_EESH_SP_SH_SP_SH_NS3_IKjSG_EESH_SP_SH_SR_SH_NS3_IKNSI_16E_FocusScanRangeESG_EESH_SP_SH_SP_SH_SP_SH_SP_SH_NS3_IKtSG_EESH_SR_SH_NS3_IKNSI_17E_MetadataOverlayESG_EESH_NS3_IKNSI_10E_OSDClockESG_EESH_SN_SH_NS3_IKNSI_15E_GuiPopupStateESG_EESH_SR_SH_SN_SH_SP_SH_SP_SH_NS3_IKNSI_14E_TouchpadAreaESG_EESH_NS3_IKNSI_21E_TouchpadSensitivityESG_EESH_SP_SH_NS3_IKNSI_20E_UserButtonFunctionESG_EESH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_S1E_SH_SN_SH_SN_SH_SN_SH_SN_SH_NS3_IRKSC_SG_EESH_SN_SH_SN_SH_NS3_IKNSI_19E_UserWheelFunctionESG_EESH_SL_EE` | 0x20ae800 | 1088 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESS_SS_S7_SS_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESS_NS3_INS8_12E_ExitOptionES6_EESS_SS_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES16_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESS_SS_S7_SS_S7_SS_S7_SS_SS_SS_SS_SS_NS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_13E_ImageFormatES6_EES7_SS_SS_S1E_SS_NS3_INS8_9E_ExpModeES6_EES10_S7_SS_NS3_INS8_21E_ExposureControlModeES6_EES7_NS3_IyS6_EESS_S1L_NS3_INS8_16E_ExposureStatusES6_EESS_NS3_INS8_15E_FaceDetectionES6_EES7_SH_SS_NS3_INS8_12E_FlashModesES6_EESS_SS_SS_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESH_SH_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESH_S10_NS3_INS8_11E_FocusSizeES6_EES21_NS3_INS8_17E_CameraKeyOptionES6_EESS_S7_S7_SS_SS_SS_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1G_SS_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SS_SZ_SS_SS_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISE_S6_EESM_S7_S7_S7_S7_SS_NS3_INS8_17E_LensMfRingStateES6_EESM_S2I_S2I_S7_S7_S7_SS_SS_S2I_SS_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESS_S2I_NS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EESS_S7_SS_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SS_SM_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S33_NS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESS_SS_SS_SV_SS_SS_SS_SS_S1L_SS_SV_SS_SS_S7_SS_NS3_INS8_14E_DistanceUnitES6_EES1C_SS_SS_SS_SS_NS3_INS8_12E_WhiteModesES6_EESS_SS_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3I_EES3J_NS3_IKNS8_21E_ExposureBlockReasonES3I_EES3J_NS3_IKNS8_21E_LiveviewBlockReasonES3I_EES3J_NS3_IbS3I_EES3J_S3T_S3J_NS3_IS9_S3I_EES3J_NS3_ISB_S3I_EES3J_S3T_S3J_NS3_IRKSG_S3I_EES3J_NS3_ISI_S3I_EES3J_NS3_ISK_S3I_EES3J_NS3_ItS3I_EES3J_NS3_IPKSN_S3I_EES3J_S3T_S3J_S3T_S3J_NS3_ISQ_S3I_EES3J_NS3_IiS3I_EES3J_NS3_IRKSU_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_ISW_S3I_EES3J_S46_S3J_NS3_ISY_S3I_EES3J_S46_S3J_S46_S3J_NS3_IjS3I_EES3J_NS3_IS11_S3I_EES3J_NS3_IS13_S3I_EES3J_NS3_IS15_S3I_EES3J_S4F_S3J_NS3_IS17_S3I_EES3J_NS3_IS19_S3I_EES3J_NS3_IS1B_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS1D_S3I_EES3J_S3T_S3J_S4I_S3J_NS3_IS1F_S3I_EES3J_S3T_S3J_S46_S3J_S46_S3J_S4J_S3J_S46_S3J_NS3_IS1H_S3I_EES3J_S4C_S3J_S3T_S3J_S46_S3J_NS3_IS1J_S3I_EES3J_S3T_S3J_NS3_IyS3I_EES3J_S46_S3J_S4N_S3J_NS3_IS1M_S3I_EES3J_S46_S3J_NS3_IS1O_S3I_EES3J_S3T_S3J_S3Y_S3J_S46_S3J_NS3_IS1Q_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S4G_S3J_NS3_IS1S_S3I_EES3J_S3Y_S3J_S3Y_S3J_NS3_IS1U_S3I_EES3J_NS3_IS1W_S3I_EES3J_S4C_S3J_NS3_IS1Y_S3I_EES3J_S3Y_S3J_S4C_S3J_NS3_IS20_S3I_EES3J_S4V_S3J_NS3_IS22_S3I_EES3J_S46_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S46_S3J_S3T_S3J_S3T_S3J_NS3_IS24_S3I_EES3J_NS3_IS26_S3I_EES3J_S4K_S3J_S46_S3J_NS3_IS28_S3I_EES3J_NS3_IS2A_S3I_EES3J_S3T_S3J_S46_S3J_S4B_S3J_S46_S3J_S46_S3J_S4C_S3J_NS3_IS2C_S3I_EES3J_NS3_IS2E_S3I_EES3J_NS3_IS2G_S3I_EES3J_NS3_IRKSE_S3I_EES3J_S41_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_NS3_IS2J_S3I_EES3J_S41_S3J_S56_S3J_S56_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S46_S3J_S46_S3J_S56_S3J_S46_S3J_S3T_S3J_NS3_IS2L_S3I_EES3J_S4C_S3J_NS3_IRKS2N_S3I_EES3J_S46_S3J_S56_S3J_NS3_IS2P_S3I_EES3J_S4C_S3J_S3T_S3J_NS3_IS2R_S3I_EES3J_NS3_IS2T_S3I_EES3J_NS3_IS2V_S3I_EES3J_S3T_S3J_NS3_IS2X_S3I_EES3J_S46_S3J_S3T_S3J_S46_S3J_S4B_S3J_NS3_IS2Z_S3I_EES3J_NS3_IS31_S3I_EES3J_S3T_S3J_S3T_S3J_S46_S3J_S41_S3J_S3T_S3J_NS3_IsS3I_EES3J_NS3_IS34_S3I_EES3J_S3T_S3J_S5J_S3J_NS3_IS36_S3I_EES3J_NS3_IS38_S3I_EES3J_S46_S3J_S46_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_S4N_S3J_S46_S3J_S49_S3J_S46_S3J_S46_S3J_S3T_S3J_S46_S3J_NS3_IS3A_S3I_EES3J_S4I_S3J_S46_S3J_S46_S3J_S46_S3J_S46_S3J_NS3_IS3C_S3I_EES3J_S46_S3J_S46_S3J_S3T_S3J_NS3_IS3E_S3I_EES3J_S4C_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_S3J_S3T_EE` | 0x20aec88 | 5176 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEENS3_IbS8_EENS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SD_EEEE` | 0x20b0258 | 40 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_I7QStringS6_EESB_NS3_IN9HblmTypes16E_BtAssistStatusES6_EESB_S8_S9_NS3_IP15VariantMapModelS6_EES9_NS3_INSC_13E_DebugOptionES6_EES8_S8_S9_S7_NS3_INSC_20E_EyesensorDistancesES6_EES8_NS3_ItS6_EENS3_INSC_17E_MaintenanceTypeES6_EES9_SM_SM_NS3_INSC_10E_ProfilesES6_EESB_S9_S9_S9_S8_NS3_INSC_14E_ScreenStatusES6_EENS3_INSC_9E_ScreensES6_EESU_SU_NS3_INSC_15E_SoundSettingsES6_EES9_NS3_IsS6_EENS3_INSC_24E_SpiritLevelOrientationES6_EES9_SX_S8_S8_NS3_INSC_12E_SoundLevelES6_EENS3_INSC_13E_SystemStateES6_EENS3_INSC_19E_TemperatureStatusES6_EENS3_INSC_14E_TetheredModeES6_EES7_S9_S9_SB_S8_S8_NS3_INSC_10E_WifiModeES6_EESB_S9_SB_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_NS3_I11SystemProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IjS1C_EES1D_NS3_IiS1C_EES1D_S1F_S1D_NS3_IbS1C_EES1D_NS3_IRKSA_S1C_EES1D_S1J_S1D_NS3_ISD_S1C_EES1D_S1J_S1D_S1F_S1D_S1G_S1D_NS3_IPKSF_S1C_EES1D_S1G_S1D_NS3_ISI_S1C_EES1D_S1F_S1D_S1F_S1D_S1G_S1D_S1E_S1D_NS3_ISK_S1C_EES1D_S1F_S1D_NS3_ItS1C_EES1D_NS3_ISN_S1C_EES1D_S1G_S1D_S1Q_S1D_S1Q_S1D_NS3_ISP_S1C_EES1D_S1J_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1F_S1D_NS3_ISR_S1C_EES1D_NS3_IST_S1C_EES1D_S1U_S1D_S1U_S1D_NS3_ISV_S1C_EES1D_S1G_S1D_NS3_IsS1C_EES1D_NS3_ISY_S1C_EES1D_S1G_S1D_S1W_S1D_S1F_S1D_S1F_S1D_NS3_IS10_S1C_EES1D_NS3_IS12_S1C_EES1D_NS3_IS14_S1C_EES1D_NS3_IS16_S1C_EES1D_S1E_S1D_S1G_S1D_S1G_S1D_S1J_S1D_S1F_S1D_S1F_S1D_NS3_IS18_S1C_EES1D_S1J_S1D_S1G_S1D_S1J_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_S1D_S1G_EE` | 0x20b05f8 | 1744 |
| `_Z16qt_metaTypeArrayIJ7QStringS0_S0_S0_S0_iS0_S0_S0_S0_5QListIS0_ES2_S2_S2_S2_bibb8LensDatavS0_vS0_vS0_vS0_vS0_vS0_vS0_vS0_vS0_vS2_vS2_vS2_vS2_vS2_vivivbvbvbvvvS0_iS0_iiiibEE` | 0x20f4910 | 552 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48b0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_0clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48b8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48c0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_4clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48c8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48d0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml3$_8clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48d8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_11clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48e0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_11clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48e8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48f0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a48f8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_23clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4900 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_23clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4908 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4910 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_26clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4918 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_30clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4930 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_30clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4938 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4950 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_34clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4958 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_36clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4960 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_liveview_FocusDistanceScale_qml4$_36clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a4968 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_132clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5330 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_132clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5338 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_137clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5340 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_137clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5348 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_142clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5360 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_142clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5368 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_150clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5390 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_150clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5398 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_177clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53a0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_177clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53a8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_178clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53b0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_178clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53b8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_179clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53c0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_179clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53c8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_192clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53e0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_192clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53e8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_193clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53f0 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_193clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a53f8 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_195clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5400 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode37_app_qml_liveview_LiveViewOverlay_qml5$_195clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a5408 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8608 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode40_app_qml_popups_PopoverFaceDetection_qml4$_16clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8610 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8758 | 8 |

<details><summary>… 另 112 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_15clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8760 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8768 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_18clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8770 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8778 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_21clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8780 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_22clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8788 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_22clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8790 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a87a8 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_24clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a87b0 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a87b8 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_25clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a87c0 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_40clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8848 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_40clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8850 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8858 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_44clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8860 | 8 |
| `_ZZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_53clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8878 | 8 |
| `_ZGVZZZNK21QmlCacheGeneratedCode35_app_qml_popups_PopoverLensData_qml4$_53clEPKN11QQmlPrivate18AOTCompiledContextEPvPS6_ENKUlS5_S7_E_clES5_S7_ENKUlvE_clEvE1t` | 0x21a8880 | 8 |
| `_ZN5CJson4LensL25kJsonTagShadingCorrectionE` | 0x21ba670 | 24 |
| `_ZL11TAG_MOUNTED` | 0x21baf90 | 24 |
| `_ZL8TAG_TYPE` | 0x21bafb0 | 24 |
| `_ZL8TAG_NAME` | 0x21bafd0 | 24 |
| `_ZL8TAG_UUID` | 0x21baff0 | 24 |
| `_ZL15TAG_EXPOSURE_ID` | 0x21bb010 | 24 |
| `_ZL8TAG_SIZE` | 0x21bb030 | 24 |
| `_ZL10TAG_OFFSET` | 0x21bb050 | 24 |
| `_ZL10TAG_HANDLE` | 0x21bb070 | 24 |
| `_ZL15TAG_DEVICE_TYPE` | 0x21bb090 | 24 |
| `_ZL13TAG_SIZECHILD` | 0x21bb0b0 | 24 |
| `_ZL13TAG_FULL_PATH` | 0x21bb0d0 | 24 |
| `_ZL16TAG_DISPLAY_PATH` | 0x21bb0f0 | 24 |
| `_ZL28TAG_DISPLAY_PATH_WITH_SUFFIX` | 0x21bb110 | 24 |
| `_ZL12TAG_METADATA` | 0x21bb130 | 24 |
| `_ZL15TAG_LORES_IMAGE` | 0x21bb150 | 24 |
| `_ZL15TAG_THUMB_IMAGE` | 0x21bb170 | 24 |
| `_ZL14TAG_TILE_IMAGE` | 0x21bb190 | 24 |
| `_ZL14TAG_FREE_SPACE` | 0x21bb1b0 | 24 |
| `_ZL16TAG_WRITEPROTECT` | 0x21bb1d0 | 24 |
| `_ZL10TAG_STATUS` | 0x21bb1f0 | 24 |
| `_ZL6TAG_WP` | 0x21bb210 | 24 |
| `_ZL14TAG_SLOW_SPEED` | 0x21bb230 | 24 |
| `_ZL17TAG_AVERAGE_SPEED` | 0x21bb250 | 24 |
| `_ZL13TAG_DATE_TIME` | 0x21bb270 | 24 |
| `_ZL6TAG_SV` | 0x21bb290 | 24 |
| `_ZL6TAG_AV` | 0x21bb2b0 | 24 |
| `_ZL21TAG_FNUMBER_NUMERATOR` | 0x21bb2d0 | 24 |
| `_ZL23TAG_FNUMBER_DENOMINATOR` | 0x21bb2f0 | 24 |
| `_ZL10TAG_AV_MIN` | 0x21bb310 | 24 |
| `_ZL6TAG_TV` | 0x21bb330 | 24 |
| `_ZL13TAG_FOCAL_LEN` | 0x21bb350 | 24 |
| `_ZL17TAG_EXPOSURE_MODE` | 0x21bb370 | 24 |
| `_ZL27TAG_EXPOSURE_TIME_NUMERATOR` | 0x21bb390 | 24 |
| `_ZL29TAG_EXPOSURE_TIME_DENOMINATOR` | 0x21bb3b0 | 24 |
| `_ZL11TAG_LM_MODE` | 0x21bb3d0 | 24 |
| `_ZL6TAG_WB` | 0x21bb3f0 | 24 |
| `_ZL10TAG_EV_ADJ` | 0x21bb410 | 24 |
| `_ZL17TAG_EXPOSURE_BIAS` | 0x21bb430 | 24 |
| `_ZL14TAG_LENS_SHIFT` | 0x21bb450 | 24 |
| `_ZL16TAG_LENS_VERSION` | 0x21bb470 | 24 |
| `_ZL27TAG_LENS_SHADING_CORRECTION` | 0x21bb490 | 24 |
| `_ZL21TAG_LENS_FOCAL_MINMAX` | 0x21bb4b0 | 24 |
| `_ZL13TAG_LENS_TYPE` | 0x21bb4d0 | 24 |
| `_ZL13TAG_HISTOGRAM` | 0x21bb4f0 | 24 |
| `_ZL16TAG_FS_TIMESTAMP` | 0x21bb510 | 24 |
| `_ZL8TAG_PATH` | 0x21bb530 | 24 |
| `_ZL14TAG_PERSISTENT` | 0x21bb550 | 24 |
| `_ZL15TAG_R_NUMERATOR` | 0x21bb570 | 24 |
| `_ZL17TAG_R_DENOMINATOR` | 0x21bb590 | 24 |
| `_ZL15TAG_G_NUMERATOR` | 0x21bb5b0 | 24 |
| `_ZL17TAG_G_DENOMINATOR` | 0x21bb5d0 | 24 |
| `_ZL15TAG_B_NUMERATOR` | 0x21bb5f0 | 24 |
| `_ZL17TAG_B_DENOMINATOR` | 0x21bb610 | 24 |
| `_ZL22TAG_BLACK_LEVEL_OFFSET` | 0x21bb630 | 24 |
| `_ZL15TAG_WHITE_LEVEL` | 0x21bb650 | 24 |
| `_ZL20TAG_SENSITIVITY_GAIN` | 0x21bb670 | 24 |
| `_ZL18TAG_R_NEUTRAL_GAIN` | 0x21bb690 | 24 |
| `_ZL18TAG_G_NEUTRAL_GAIN` | 0x21bb6b0 | 24 |
| `_ZL18TAG_B_NEUTRAL_GAIN` | 0x21bb6d0 | 24 |
| `_ZL21TAG_NEUTRAL_PRECISION` | 0x21bb6f0 | 24 |
| `_ZL16TAG_IMAGE_RATING` | 0x21bb710 | 24 |
| `_ZL18TAG_IMAGE_ROTATION` | 0x21bb730 | 24 |
| `_ZL15TAG_CAMERA_TYPE` | 0x21bb750 | 24 |
| `_ZL15TAG_FOCUS_POINT` | 0x21bb770 | 24 |
| `_ZL20TAG_SUBJECT_DISTANCE` | 0x21bb790 | 24 |
| `_ZL14TAG_LENS_MODEL` | 0x21bb7b0 | 24 |
| `_ZL13TAG_LENS_MAKE` | 0x21bb7d0 | 24 |
| `_ZL17TAG_FOCUS_SEGMENT` | 0x21bb7f0 | 24 |
| `_ZL17TAG_LENS_MODEL_ID` | 0x21bb810 | 24 |
| `_ZL9TAG_FILES` | 0x21bb830 | 24 |
| `_ZL14IMAGE_TAG_DATA` | 0x21bb850 | 24 |
| `_ZL16IMAGE_TAG_FORMAT` | 0x21bb870 | 24 |
| `_ZL15IMAGE_TAG_WIDTH` | 0x21bb890 | 24 |
| `_ZL16IMAGE_TAG_HEIGHT` | 0x21bb8b0 | 24 |
| `_ZL11IMAGE_TAG_X` | 0x21bb8d0 | 24 |
| `_ZL11IMAGE_TAG_Y` | 0x21bb8f0 | 24 |
| `_ZL19IMAGE_TAG_BUFFER_ID` | 0x21bb910 | 24 |
| `_ZL17IMAGE_FORMAT_RGBA` | 0x21bb930 | 24 |
| `_ZL17IMAGE_FORMAT_UYVY` | 0x21bb950 | 24 |
| `_ZL17IMAGE_FORMAT_NV12` | 0x21bb970 | 24 |
| `_ZL17IMAGE_FORMAT_422P` | 0x21bb990 | 24 |
| `_ZL17IMAGE_FORMAT_JPEG` | 0x21bb9b0 | 24 |
| `_ZL12STORAGE_ROOT` | 0x21bb9d0 | 24 |
| `_ZL13TETHERED_ROOT` | 0x21bb9f0 | 24 |
| `_ZL17STORAGE_MOUNT_SSD` | 0x21bba10 | 24 |
| `_ZL20STORAGE_MOUNT_CFCARD` | 0x21bba30 | 24 |
| `_ZL17HASBL_FOLDER_NAME` | 0x21bba50 | 24 |
| `_ZL9NAME_ROOT` | 0x21bba70 | 24 |
| `_ZL9NAME_DCIM` | 0x21bba90 | 24 |
| `_ZL11SOCKET_NAME` | 0x21bbab0 | 24 |
| `_ZL11EXPOSURE_ID` | 0x21bbad0 | 24 |
| `_ZL14DCAM_CONTAINER` | 0x21bbaf0 | 24 |
| `_ZL10FRAME_INFO` | 0x21bbb10 | 24 |
| `_ZL18EXPOSURE_ITEM_TYPE` | 0x21bbb30 | 24 |

</details>

### `/bin/phocus`

+283 / −95 functions · +120 / −167 objects

**New functions (283)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EE7destroyEv` | 0x56508 | 4 |
| `_ZNSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EE7destroyEv` | 0x56508 | 4 |
| `_ZN7PhocusD19tetheredModeChangedEN9HblmTypes14E_TetheredModeE` | 0x57de0 | 96 |
| `_ZN7PhocusD48tetheredClientSupportedFaceDetectionModesChangedEN13PhocusMessage11DestinationERK5QListIN9HblmTypes15E_FaceDetectionEE` | 0x57f00 | 100 |
| `_ZN7PhocusD29tetheredCaptureClientsChangedEN9HblmTypes7E_HostsE` | 0x58038 | 96 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x59938 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x59948 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x59950 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x59950 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x59960 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x59978 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x59a28 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x59a38 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI5QListIN9HblmTypes15E_FaceDetectionEEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES8_S9_` | 0x5aa90 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI5QListIN9HblmTypes15E_FaceDetectionEEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES8_S9_SB_` | 0x5aaa0 | 48 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI5QListIN9HblmTypes15E_FaceDetectionEEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS9_E_8__invokeES8_S9_S9_` | 0x5aad0 | 36 |
| `_ZN17QArrayDataPointerIN14PhocusProtocol18eFaceDetectionModeEE20tryReadjustFreeSpaceEN10QArrayData14GrowthPositionExPPKS1_` | 0x5b3b0 | 292 |
| `_ZN17QArrayDataPointerIN14PhocusProtocol18eFaceDetectionModeEE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x5b4d8 | 460 |
| `_ZN17QArrayDataPointerIN14PhocusProtocol18eFaceDetectionModeEE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0x5b6a8 | 372 |
| `_ZN11QScopeGuardIZN9QMetaType21registerConverterImplI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEEEbNSt3__18functionIFbPKvPvEEES0_S0_EUlvE_ED2Ev` | 0x5bc30 | 40 |
| `_ZNSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EE18destroy_deallocateEv` | 0x5bc58 | 4 |
| `_ZNSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EED0Ev` | 0x5bc58 | 4 |
| `_ZNSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EE18destroy_deallocateEv` | 0x5bc58 | 4 |
| `_ZNSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EED0Ev` | 0x5bc58 | 4 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE9getSizeFnEvENUlPKvE_8__invokeES7_` | 0x5bd10 | 8 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE20getDestroyIteratorFnEvENUlPKvE_8__invokeES7_` | 0x5bde8 | 12 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE25getDestroyConstIteratorFnEvENUlPKvE_8__invokeES7_` | 0x5bde8 | 12 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE20getCompareIteratorFnEvENUlPKvS7_E_8__invokeES7_S7_` | 0x5bdf8 | 20 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE25getCompareConstIteratorFnEvENUlPKvS7_E_8__invokeES7_S7_` | 0x5bdf8 | 20 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE17getCopyIteratorFnEvENUlPvPKvE_8__invokeES6_S8_` | 0x5be10 | 12 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE22getCopyConstIteratorFnEvENUlPvPKvE_8__invokeES6_S8_` | 0x5be10 | 12 |
| `_ZN11QScopeGuardIZN9QMetaType23registerMutableViewImplI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEEEbNSt3__18functionIFbPvSB_EEES0_S0_EUlvE_ED2Ev` | 0x5c5f0 | 40 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI5QListIN9HblmTypes15E_FaceDetectionEEE7getDtorEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES8_S9_` | 0x5ec10 | 48 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeI5QListIN9HblmTypes15E_FaceDetectionEELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvSA_` | 0x5ec40 | 80 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeI5QListIN9HblmTypes15E_FaceDetectionEELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvSA_` | 0x5ec90 | 88 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeI5QListIN9HblmTypes15E_FaceDetectionEELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x5ed88 | 88 |
| `_ZN5QListIN9HblmTypes15E_FaceDetectionEE7reserveEx` | 0x5f240 | 300 |
| `_ZN17QArrayDataPointerIN9HblmTypes15E_FaceDetectionEE20tryReadjustFreeSpaceEN10QArrayData14GrowthPositionExPPKS1_` | 0x5f518 | 292 |
| `_ZN17QArrayDataPointerIN9HblmTypes15E_FaceDetectionEE17reallocateAndGrowEN10QArrayData14GrowthPositionExPS2_` | 0x5f640 | 456 |
| `_ZN17QArrayDataPointerIN9HblmTypes15E_FaceDetectionEE12allocateGrowERKS2_xN10QArrayData14GrowthPositionE` | 0x5f808 | 368 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE10getClearFnEvENUlPvE_8__invokeES6_` | 0x60100 | 192 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE20getAdvanceIteratorFnEvENUlPvxE_8__invokeES6_x` | 0x601d0 | 16 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE25getAdvanceConstIteratorFnEvENUlPvxE_8__invokeES6_x` | 0x601d0 | 16 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE17getDiffIteratorFnEvENUlPKvS7_E_8__invokeES7_S7_` | 0x601e0 | 16 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE22getDiffConstIteratorFnEvENUlPKvS7_E_8__invokeES7_S7_` | 0x601e0 | 16 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE24getCreateConstIteratorFnEvENUlPKvNS_23QMetaContainerInterface8PositionEE_8__invokeES7_S9_` | 0x601f0 | 112 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE17getValueAtIndexFnEvENUlPKvxPvE_8__invokeES7_xS8_` | 0x60260 | 16 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE20getSetValueAtIndexFnEvENUlPvxPKvE_8__invokeES6_xS8_` | 0x60270 | 132 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE16getRemoveValueFnEvENUlPvNS_23QMetaContainerInterface8PositionEE_8__invokeES6_S8_` | 0x603b0 | 164 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE20getValueAtIteratorFnEvENUlPKvPvE_8__invokeES7_S8_` | 0x60458 | 16 |

<details><summary>… 另 233 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE25getValueAtConstIteratorFnEvENUlPKvPvE_8__invokeES7_S8_` | 0x60458 | 16 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE23getSetValueAtIteratorFnEvENUlPKvS7_E_8__invokeES7_S7_` | 0x60468 | 16 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE19getCreateIteratorFnEvENKUlPvNS_23QMetaContainerInterface8PositionEE_clES6_S8_` | 0x604b0 | 236 |
| `_ZN5QListIN9HblmTypes15E_FaceDetectionEE6insertExxS1_` | 0x605a0 | 364 |
| `_ZN5QListIN9HblmTypes15E_FaceDetectionEE5eraseENS2_14const_iteratorES3_` | 0x60710 | 208 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeI5QListIN9HblmTypes15E_FaceDetectionEELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x609f8 | 160 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeI5QListIN9HblmTypes15E_FaceDetectionEELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x60a98 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI5QListIN9HblmTypes15E_FaceDetectionEEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x60aa8 | 4 |
| `_ZN9QtPrivate24printSequentialContainerI5QListIN9HblmTypes15E_FaceDetectionEEEE6QDebugS5_PKcRKT_` | 0x60ab0 | 492 |
| `_ZN9QtPrivate23readArrayBasedContainerI5QListIN9HblmTypes15E_FaceDetectionEEEER11QDataStreamS6_RT_` | 0x60ca0 | 596 |
| `_ZN9QtPrivate12QPodArrayOpsIN9HblmTypes15E_FaceDetectionEE7emplaceIJRS2_EEEvxDpOT_` | 0x60ef8 | 420 |
| `_ZN11QMetaTypeIdI5QListIN9HblmTypes15E_FaceDetectionEEE14qt_metatype_idEv` | 0x610a0 | 400 |
| `_Z41qRegisterNormalizedMetaTypeImplementationI5QListIN9HblmTypes15E_FaceDetectionEEEiRK10QByteArray` | 0x61518 | 256 |
| `_ZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS4_EEEEbT1_` | 0x61618 | 348 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EE7__cloneEv` | 0x61778 | 60 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EE7__cloneEPNS0_6__baseISL_EE` | 0x617b8 | 28 |
| `_ZNSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EEclEOSG_OSH_` | 0x617d8 | 32 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EE6targetERKSt9type_info` | 0x617f8 | 28 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EE11target_typeEv` | 0x61818 | 12 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE19getCreateIteratorFnEvENUlPvNS_23QMetaContainerInterface8PositionEE_8__invokeES6_S8_` | 0x61828 | 12 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE13getAddValueFnEvENUlPvPKvNS_23QMetaContainerInterface8PositionEE_8__invokeES6_S8_SA_` | 0x61838 | 180 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE26getInsertValueAtIteratorFnEvENUlPvPKvS8_E_8__invokeES6_S8_S8_` | 0x618f0 | 24 |
| `_ZZN22QtMetaContainerPrivate26QMetaContainerForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE20getEraseAtIteratorFnIPFvPvPKvEEET_vENUlS7_S9_E_8__invokeES7_S9_` | 0x61908 | 12 |
| `_ZZN22QtMetaContainerPrivate25QMetaSequenceForContainerI5QListIN9HblmTypes15E_FaceDetectionEEE25getEraseRangeAtIteratorFnEvENUlPvPKvS8_E_8__invokeES6_S8_S8_` | 0x61918 | 12 |
| `_ZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS4_EEEEbT1_` | 0x61928 | 348 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EE7__cloneEv` | 0x61a88 | 60 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EE7__cloneEPNS0_6__baseISJ_EE` | 0x61ac8 | 28 |
| `_ZNSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EEclEOSF_SL_` | 0x61ae8 | 36 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EE6targetERKSt9type_info` | 0x61b10 | 28 |
| `_ZNKSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EE11target_typeEv` | 0x61b30 | 12 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x64678 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x64678 | 452 |
| `_ZN7PhocusD31updateEnabledFaceDetectionModesEv` | 0x672b0 | 2060 |
| `_ZN7PhocusD15updateDebugModeEv` | 0x68da0 | 64 |
| `_ZN7PhocusD20removeTetheredClientEN13PhocusMessage11DestinationERK14QSharedPointerI19MessageNotificationE` | 0x740e8 | 2416 |
| `_ZN7PhocusD20updateTetheredClientEN13PhocusMessage11DestinationEN9HblmTypes14E_TetheredModeEbRK14QSharedPointerI19MessageNotificationE` | 0x77248 | 2016 |
| `_ZN7PhocusD15setTetheredModeEN9HblmTypes14E_TetheredModeERK14QSharedPointerI19MessageNotificationEb` | 0x77d58 | 2960 |
| `_ZN7PhocusD28updateTetheredCaptureClientsEv` | 0x788e8 | 956 |
| `_ZN7PhocusD36setClientSupportedFaceDetectionModesERK5QListIN9HblmTypes15E_FaceDetectionEEN13PhocusMessage11DestinationE` | 0x79770 | 1844 |
| `_ZNK7PhocusD33clientSupportedFaceDetectionModesEN13PhocusMessage11DestinationE` | 0x79ea8 | 328 |
| `_ZN13phocus_clientaSEOS_` | 0x7aa00 | 312 |
| `_ZNK7PhocusD21clientsAllowPowerSaveEv` | 0x7adf8 | 384 |
| `_ZN7PhocusD24removeAllTetheredClientsEv` | 0x7b908 | 560 |
| `_ZNK7PhocusD20clientCaptureAllowedEN13PhocusMessage11DestinationE` | 0x7bb38 | 364 |
| `_ZNK7PhocusD22isMultiShotModeAllowedEv` | 0x7bca8 | 8 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EED2Ev` | 0x7c908 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EED0Ev` | 0x7c978 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EE10runFunctorEv` | 0x7c9f0 | 2448 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE6rehashEm` | 0x7df78 | 716 |
| `_ZN12QHashPrivate4SpanINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE10addStorageEv` | 0x7e330 | 428 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEEC2Em` | 0x7e4e0 | 260 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEEC2ERKS6_m` | 0x7e5e8 | 288 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE18reallocationHelperERKS6_mb` | 0x7e708 | 424 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE12findOrInsertERKS3_` | 0x7eae8 | 592 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE8detachedEPS6_` | 0x7ed38 | 308 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEEC2ERKS6_` | 0x7ee70 | 420 |
| `_ZN5QHashIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEaSERKS3_` | 0x7f310 | 228 |
| `_ZN5QHashIN9HblmTypes15E_FaceDetectionE15QHashDummyValueE6removeERKS1_` | 0x7f3f8 | 344 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE5eraseENS6_6BucketE` | 0x7f550 | 500 |
| `_ZN4QSetIN9HblmTypes15E_FaceDetectionEEC2IN5QListIS1_E14const_iteratorELb1EEET_S7_` | 0x7f748 | 296 |
| `_ZN4QSetIN9HblmTypes15E_FaceDetectionEE9intersectERKS2_` | 0x7f870 | 1120 |
| `_ZNK4QSetIN9HblmTypes15E_FaceDetectionEE6valuesEv` | 0x7fcd0 | 480 |
| `_ZN12QHashPrivate4DataINS_4NodeIN9HblmTypes15E_FaceDetectionE15QHashDummyValueEEE8detachedEPS6_m` | 0x7feb0 | 228 |
| `_ZN5QHashIN9HblmTypes15E_FaceDetectionE15QHashDummyValueE7emplaceIJRKS2_EEENS3_8iteratorEOS1_DpOT_` | 0x7ff98 | 564 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusDC1EP8V1ClientP21PhocusUinputInterfaceP7QObjectE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES7_PPvPb` | 0x82738 | 184 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN7PhocusDC1EP8V1ClientP21PhocusUinputInterfaceP7QObjectENK4$_10clEvEUlvE_Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES7_PPvPb` | 0x82b30 | 36 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusDC1EP8V1ClientP21PhocusUinputInterfaceP7QObjectE4$_11Li1ENS_4ListIJxEEEvE4implEiPNS_15QSlotObjectBaseES7_PPvPb` | 0x82b58 | 88 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusDC1EP8V1ClientP21PhocusUinputInterfaceP7QObjectE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES7_PPvPb` | 0x82bb0 | 140 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD37ImageMemoryCameraDeviceData_TestImageERK14QSharedPointerI13PhocusMessageEiR9QFileInfoE4$_13Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x834f8 | 1576 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD19sendImageDataToHostERK14QSharedPointerI13PhocusMessageERKS2_I12phocus_imageEE4$_14Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x84280 | 3272 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD18sendBulkDataToHostERK14QSharedPointerI13PhocusMessageERK5QListI4QMapI7QString8QVariantEEyRKS9_N9HblmTypes13E_SendOptionsEE4$_15Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x85780 | 136 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD14completeBrowseEP14browse_contextE4$_16Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x85808 | 128 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEE7__cloneEv` | 0x85aa0 | 56 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEE7__cloneEPNS0_6__baseISE_EE` | 0x85ad8 | 24 |
| `_ZNSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEEclEOSD_` | 0x85af0 | 2896 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEE6targetERKSt9type_info` | 0x86640 | 28 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEE11target_typeEv` | 0x86660 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD20FileCameraDeviceDataERK14QSharedPointerI13PhocusMessageEE4$_18Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86798 | 1104 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_20Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86ea8 | 2804 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_ENK4$_20clEvEUlP18PendingCallWatcherE_Li1ENS_4ListIJSJ_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87c28 | 128 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD14onGetFullImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmE4$_21Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87ca8 | 128 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD15setTetheredModeEN9HblmTypes14E_TetheredModeERK14QSharedPointerI19MessageNotificationEbE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x88f20 | 364 |
| `_ZN9QtPrivate24printSequentialContainerI5QListIN13PhocusMessage11DestinationEEEE6QDebugS5_PKcRKT_` | 0x892d0 | 492 |
| `_ZNK16PhocusObjectImpl24tethered_capture_clientsEv` | 0x89df0 | 12 |
| `_ZN16PhocusObjectImpl24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeERK12QDBusMessage` | 0x89e00 | 1888 |
| `_ZN9QtPrivate11QSlotObjectIM12PhocusObjectFvN9HblmTypes7E_HostsEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a6d8 | 124 |
| `_ZNK14PhocusProtocol16sCameraParameter8ToStringEm` | 0x93c38 | 840 |
| `_ZN9QtPrivate12QPodArrayOpsIN14PhocusProtocol18eFaceDetectionModeEE7emplaceIJRS2_EEEvxDpOT_` | 0x9bd00 | 424 |
| `_ZN14PhocusNotifier26onExpAdjustStepSizeChangedEi` | 0xa8f08 | 360 |
| `_ZN14PhocusNotifier21onTetheredModeChangedEN9HblmTypes14E_TetheredModeE` | 0xaac28 | 2544 |
| `_ZN14PhocusNotifier23updateFaceDetectionModeEv` | 0xadb78 | 296 |
| `_ZN14PhocusNotifier39updateClientSupportedFaceDetectionModesEv` | 0xadca0 | 1668 |
| `_ZN9QtPrivate11QSlotObjectIM14PhocusNotifierFvN9HblmTypes14E_TetheredModeEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8588 | 124 |
| `_ZN16ConvertParameter22Phocus2Cam_DestinationEi` | 0xb9760 | 32 |
| `_ZN16ConvertParameter28Cam2Phocus_FaceDetectionModeEN9HblmTypes15E_FaceDetectionE` | 0xb9f20 | 28 |
| `_ZN16ConvertParameter28Phocus2Cam_FaceDetectionModeEN14PhocusProtocol18eFaceDetectionModeE` | 0xb9f40 | 24 |
| `_ZN5Httpd11setMetadataERK7QStringS2_S2_RK18QHttpServerRequest` | 0xc4508 | 2664 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EED2Ev` | 0xc8a70 | 156 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EED0Ev` | 0xc8b10 | 164 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EE10runFunctorEv` | 0xc8bb8 | 4012 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EED2Ev` | 0xcdc08 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EED0Ev` | 0xcdc78 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EE10runFunctorEv` | 0xcdcf0 | 528 |
| `_ZZN5Httpd8sendFileERK7QStringjiNS_13HeaderContentEO20QHttpServerResponderEN4$_10clES2_jiS3_` | 0xce4f8 | 8044 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EED2Ev` | 0xd0e78 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EED0Ev` | 0xd0ee8 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EE10runFunctorEv` | 0xd0f60 | 5452 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EED2Ev` | 0xd26f8 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EED0Ev` | 0xd2768 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EE10runFunctorEv` | 0xd27e0 | 1756 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JEED0Ev` | 0xd33a8 | 60 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JEE10runFunctorEv` | 0xd33e8 | 124 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EED2Ev` | 0xd3468 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EED0Ev` | 0xd34d8 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EE10runFunctorEv` | 0xd3550 | 816 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEED2Ev` | 0xd3880 | 156 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEED0Ev` | 0xd3920 | 164 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEE10runFunctorEv` | 0xd39c8 | 3688 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEED2Ev` | 0xd49d0 | 156 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEED0Ev` | 0xd4a70 | 164 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEE10runFunctorEv` | 0xd4b18 | 3280 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xd6648 | 56 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xd6680 | 24 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xd6698 | 288 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xd67b8 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xd67d8 | 12 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEv` | 0xd67e8 | 56 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEPNS0_6__baseISP_EE` | 0xd6820 | 24 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEclESO_` | 0xd6838 | 8 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE6targetERKSt9type_info` | 0xd6840 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE11target_typeEv` | 0xd6860 | 12 |
| `_ZZN5HttpdC1EjP7PhocusDENK3$_6clERK18QHttpServerRequest` | 0xd6870 | 1724 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xd8b40 | 56 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xd8b78 | 24 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xd8b90 | 1340 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xd90d0 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xd90f0 | 12 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEED2Ev` | 0xd9100 | 180 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEED0Ev` | 0xd91b8 | 176 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE7__cloneEv` | 0xd9268 | 172 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE7__cloneEPNS0_6__baseISR_EE` | 0xd9318 | 156 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE7destroyEv` | 0xd93b8 | 168 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE18destroy_deallocateEv` | 0xd9460 | 164 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEclESN_SQ_` | 0xd9508 | 6780 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE6targetERKSt9type_info` | 0xdaf88 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE11target_typeEv` | 0xdafa8 | 12 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xdc338 | 56 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xdc370 | 24 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xdc388 | 1356 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xdc8d8 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xdc8f8 | 12 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEED2Ev` | 0xdc908 | 180 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEED0Ev` | 0xdc9c0 | 176 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEE7__cloneEv` | 0xdca70 | 172 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEE7__cloneEPNS0_6__baseISS_EE` | 0xdcb20 | 156 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEEclESR_` | 0xdcbc0 | 940 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEE6targetERKSt9type_info` | 0xdcf70 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEE11target_typeEv` | 0xdcf90 | 12 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xdcfa0 | 64 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xdcfe0 | 32 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xdd000 | 300 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xdd130 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xdd150 | 12 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEv` | 0xdd160 | 64 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEPNS0_6__baseISP_EE` | 0xdd1a0 | 32 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEclESO_` | 0xdd1c0 | 8 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE6targetERKSt9type_info` | 0xdd1c8 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE11target_typeEv` | 0xdd1e8 | 12 |
| `_ZZN5HttpdC1EjP7PhocusDENK3$_8clERK18QHttpServerRequest` | 0xdd1f8 | 2944 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xddeb8 | 1668 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xde680 | 1668 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_15Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xdedd0 | 1112 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd18checkFileReadCacheEbE4$_22Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xdf340 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13HttpResponderC1EO20QHttpServerResponderP7QObjectE4$_23Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xdf4c8 | 40 |
| `_ZN12PhocusObject31tethered_capture_clientsChangedEN9HblmTypes7E_HostsE` | 0xec3b8 | 96 |
| `_ZN11CameraProxy35enabled_face_detection_modesChangedEN9HblmTypes15E_FaceDetectionE` | 0xefb88 | 96 |
| `_ZN11CameraProxy37exposures_in_multishot_sessionChangedEi` | 0xf0078 | 96 |
| `_ZN11CameraProxy28face_detection_pausedChangedEb` | 0xf0138 | 100 |
| `_ZN11CameraProxy27flash_recharge_delayChangedEi` | 0xf0200 | 96 |
| `_ZN11CameraProxy29multishot_control_modeChangedEN9HblmTypes15E_MultiShotModeE` | 0xf1090 | 96 |
| `_ZN12StorageProxy29remove_extended_activeChangedEb` | 0xf44a0 | 100 |
| `_ZN12StorageProxy26set_metadata_activeChangedEb` | 0xf4508 | 100 |
| `_ZN11SystemProxy20debug_optionsChangedEN9HblmTypes13E_DebugOptionE` | 0xf4f38 | 96 |
| `_ZN16StorageProxyDbus17doRemove_extendedERK5QListI7QStringE` | 0xf61c8 | 20 |
| `_ZNK16StorageProxyDbus22remove_extended_activeEv` | 0xf6950 | 20 |
| `_ZNK16StorageProxyDbus19set_metadata_activeEv` | 0xf6968 | 20 |
| `_ZN16StorageProxyDbus14doSet_metadataERK7QStringRK4QMapIS0_8QVariantE` | 0xf69e0 | 20 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xfbdb0 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xfbe48 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0xfbe50 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0xfbfd0 | 200 |
| `_ZN16StorageProxyDbus15remove_extendedERK5QListI7QStringEiP7QObject` | 0x1065b8 | 752 |
| `_ZN16StorageProxyDbus12set_metadataERK7QStringRK4QMapIS0_8QVariantEiP7QObject` | 0x1068a8 | 804 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus15remove_extendedERK5QListI7QStringEiP7QObjectE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES8_PPvPb` | 0x108968 | 64 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN16StorageProxyDbus12set_metadataERK7QStringRK4QMapIS2_8QVariantEiP7QObjectE3$_5Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0x1089a8 | 64 |
| `_ZN15SystemProxyDbus16setDebug_optionsEN9HblmTypes13E_DebugOptionE` | 0x10a908 | 308 |
| `_ZNK15SystemProxyDbus13debug_optionsEv` | 0x10ae78 | 48 |
| `_ZN15CameraProxyDbus31setEnabled_face_detection_modesEN9HblmTypes15E_FaceDetectionE` | 0x1138e8 | 308 |
| `_ZN15CameraProxyDbus33setExposures_in_multishot_sessionEi` | 0x114518 | 308 |
| `_ZN15CameraProxyDbus24setFace_detection_pausedEb` | 0x114788 | 308 |
| `_ZN15CameraProxyDbus23setFlash_recharge_delayEi` | 0x1149f8 | 308 |
| `_ZN15CameraProxyDbus25setMultishot_control_modeEN9HblmTypes15E_MultiShotModeE` | 0x115eb0 | 308 |
| `_ZNK15CameraProxyDbus28enabled_face_detection_modesEv` | 0x117a58 | 48 |
| `_ZNK15CameraProxyDbus30exposures_in_multishot_sessionEv` | 0x117cc8 | 48 |
| `_ZNK15CameraProxyDbus21face_detection_pausedEv` | 0x117d28 | 48 |
| `_ZNK15CameraProxyDbus20flash_recharge_delayEv` | 0x117d88 | 48 |
| `_ZNK15CameraProxyDbus22multishot_control_modeEv` | 0x1184d8 | 48 |
| `_ZNK12PhocusObject25_tethered_capture_clientsEv` | 0x1288e0 | 12 |
| `_ZN12PhocusObject22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiRK12QDBusMessage` | 0x128a80 | 668 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12PhocusObjectC1EP7QObjectE3$_2Li1ENS_4ListIJN9HblmTypes7E_HostsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x128d90 | 44 |
| `_ZN9DussEvent6handleEv` | 0x12db60 | 64 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringED2Ev` | 0x16c888 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringED2Ev` | 0x16c888 | 88 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x16d560 | 108 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x16d560 | 108 |
| `_ZN8CStorage14tagFocalLengthEv` | 0x16e2d8 | 92 |
| `_ZN8CStorage14tagImageRatingEv` | 0x16e518 | 92 |
| `_ZN8CStorage16tagImageUniqueIdEv` | 0x16e5d8 | 92 |
| `_ZN8CStorage15tagCameraSerialEv` | 0x16e698 | 92 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringE6insertERKS1_RKS2_` | 0x16eb18 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage7MetaTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x16eca0 | 392 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x16ee28 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x16ee28 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x16ef20 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x16ef20 | 248 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringE6insertERKS1_RKS2_` | 0x16f018 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage10StorageTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x16f1a0 | 392 |
| `_ZN7Version11readCmdlineEv` | 0x16f328 | 860 |
| `_ZN7Version10hardwareIDEv` | 0x16f8c0 | 252 |
| `_ZN7Version14hblProductInfoC1Ev` | 0x16fbf0 | 12 |
| `_ZN7Version14hblProductInfoC2Ev` | 0x16fbf0 | 12 |
| `_ZNK7Version14hblProductInfo19cfvHiresBackDisplayEv` | 0x16fc00 | 1148 |
| `_ZNK7Version14hblProductInfo7hasIbisEv` | 0x170080 | 140 |

</details>

**Removed functions (95)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN7PhocusD19tetheredModeChangedERK20phocus_tethered_mode` | 0x55eb0 | 88 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI20phocus_tethered_modeE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES5_S6_S8_` | 0x582f8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI20phocus_tethered_modeE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS6_E_8__invokeES5_S6_S6_` | 0x582f8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeI20phocus_tethered_modeE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES5_S6_` | 0x5be80 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeI20phocus_tethered_modeLb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS7_` | 0x5be90 | 68 |
| `_ZN7PhocusD20removeTetheredClientEN13PhocusMessage11DestinationE` | 0x6f5c0 | 1752 |
| `_ZNK7PhocusD12tetheredModeEv` | 0x717b0 | 8 |
| `_ZN7PhocusD15setTetheredModeERK20phocus_tethered_modeRK14QSharedPointerI19MessageNotificationE` | 0x72060 | 1048 |
| `_ZN7PhocusD18updateTetheredModeERK20phocus_tethered_modeRK14QSharedPointerI19MessageNotificationE` | 0x72738 | 4616 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_17JS8_SE_EED2Ev` | 0x76590 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_17JS8_SE_EED0Ev` | 0x76600 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_17JS8_SE_EE10runFunctorEv` | 0x76678 | 2448 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN7PhocusDC1EP8V1ClientP21PhocusUinputInterfaceP7QObjectENK3$_8clEvEUlvE_Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES7_PPvPb` | 0x7b9c0 | 36 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusDC1EP8V1ClientP21PhocusUinputInterfaceP7QObjectE3$_9Li1ENS_4ListIJxEEEvE4implEiPNS_15QSlotObjectBaseES7_PPvPb` | 0x7b9e8 | 88 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD37ImageMemoryCameraDeviceData_TestImageERK14QSharedPointerI13PhocusMessageEiR9QFileInfoE4$_11Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7c388 | 1576 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD19sendImageDataToHostERK14QSharedPointerI13PhocusMessageERKS2_I12phocus_imageEE4$_12Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7d110 | 3272 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD18sendBulkDataToHostERK14QSharedPointerI13PhocusMessageERK5QListI4QMapI7QString8QVariantEEyRKS9_N9HblmTypes13E_SendOptionsEE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7e610 | 136 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD14completeBrowseEP14browse_contextE4$_14Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7e698 | 128 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEE7__cloneEv` | 0x7e930 | 56 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEE7__cloneEPNS0_6__baseISE_EE` | 0x7e968 | 24 |
| `_ZNSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEEclEOSD_` | 0x7e980 | 2396 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEE6targetERKSt9type_info` | 0x7f2e0 | 28 |
| `_ZNKSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEE11target_typeEv` | 0x7f300 | 12 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD20FileCameraDeviceDataERK14QSharedPointerI13PhocusMessageEE4$_16Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7f310 | 1104 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_18Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x7fa20 | 2804 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_ENK4$_18clEvEUlP18PendingCallWatcherE_Li1ENS_4ListIJSJ_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x807a0 | 128 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD14onGetFullImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmE4$_19Li1ENS_4ListIJP18PendingCallWatcherEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x80820 | 128 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN7PhocusD18updateTetheredModeERK20phocus_tethered_modeRK14QSharedPointerI19MessageNotificationEE4$_21Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x81a80 | 364 |
| `_ZN16PhocusObjectImpl24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEjRK12QDBusMessage` | 0x82650 | 1868 |
| `_ZN14PhocusProtocol16sCameraParameter8ToStringEm` | 0x8bf68 | 840 |
| `_ZN14PhocusNotifier21onTetheredModeChangedERK20phocus_tethered_mode` | 0xa1820 | 636 |
| `_ZN9QtPrivate11QSlotObjectIM14PhocusNotifierFvRK20phocus_tethered_modeENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xadff8 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_8JS2_S2_iiS6_EED2Ev` | 0xbd8b8 | 156 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_8JS2_S2_iiS6_EED0Ev` | 0xbd958 | 164 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_8JS2_S2_iiS6_EE10runFunctorEv` | 0xbda00 | 4012 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE3$_9JS2_jiS5_EED2Ev` | 0xc2740 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE3$_9JS2_jiS5_EED0Ev` | 0xc27b0 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE3$_9JS2_jiS5_EE10runFunctorEv` | 0xc2828 | 528 |
| `_ZZN5Httpd8sendFileERK7QStringjiNS_13HeaderContentEO20QHttpServerResponderEN3$_9clES2_jiS3_` | 0xc3030 | 8044 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_11JS2_S6_S7_EED2Ev` | 0xc59b0 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_11JS2_S6_S7_EED0Ev` | 0xc5a20 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_11JS2_S6_S7_EE10runFunctorEv` | 0xc5a98 | 5452 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_13JS2_S6_EED2Ev` | 0xc7230 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_13JS2_S6_EED0Ev` | 0xc72a0 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_13JS2_S6_EE10runFunctorEv` | 0xc7318 | 1756 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_15JEED0Ev` | 0xc7ee0 | 60 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_15JEE10runFunctorEv` | 0xc7f20 | 124 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JS2_EED2Ev` | 0xc7fa0 | 112 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JS2_EED0Ev` | 0xc8010 | 120 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JS2_EE10runFunctorEv` | 0xc8088 | 816 |

<details><summary>… 另 45 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JS2_10QByteArrayEED2Ev` | 0xc83b8 | 156 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JS2_10QByteArrayEED0Ev` | 0xc8458 | 164 |
| `_ZN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JS2_10QByteArrayEE10runFunctorEv` | 0xc8500 | 3396 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xc9cb8 | 56 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xc9cf0 | 24 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xc9d08 | 288 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xc9e28 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xc9e48 | 12 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEv` | 0xc9e58 | 56 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEPNS0_6__baseISP_EE` | 0xc9e90 | 24 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEclESO_` | 0xc9ea8 | 8 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE6targetERKSt9type_info` | 0xc9eb0 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE11target_typeEv` | 0xc9ed0 | 12 |
| `_ZZN5HttpdC1EjP7PhocusDENK3$_5clERK18QHttpServerRequest` | 0xc9ee0 | 1724 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xcc1b0 | 56 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xcc1e8 | 24 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xcc200 | 1340 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xcc740 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xcc760 | 12 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEED2Ev` | 0xcc770 | 180 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEED0Ev` | 0xcc828 | 176 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE7__cloneEv` | 0xcc8d8 | 172 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE7__cloneEPNS0_6__baseISR_EE` | 0xcc988 | 156 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE7destroyEv` | 0xcca28 | 168 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE18destroy_deallocateEv` | 0xccad0 | 164 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEclESN_SQ_` | 0xccb78 | 6780 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE6targetERKSt9type_info` | 0xce5f8 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEE11target_typeEv` | 0xce618 | 12 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEv` | 0xcf9a8 | 64 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE7__cloneEPNS0_6__baseISV_EE` | 0xcf9e8 | 32 |
| `_ZNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEclESN_SP_OSR_` | 0xcfa08 | 300 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE6targetERKSt9type_info` | 0xcfb38 | 28 |
| `_ZNKSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EE11target_typeEv` | 0xcfb58 | 12 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEv` | 0xcfb68 | 64 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE7__cloneEPNS0_6__baseISP_EE` | 0xcfba8 | 32 |
| `_ZNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEclESO_` | 0xcfbc8 | 8 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE6targetERKSt9type_info` | 0xcfbd0 | 28 |
| `_ZNKSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEE11target_typeEv` | 0xcfbf0 | 12 |
| `_ZZN5HttpdC1EjP7PhocusDENK3$_7clERK18QHttpServerRequest` | 0xcfc00 | 2944 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xd08c0 | 1668 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xd1088 | 1668 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xd17d8 | 1112 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Httpd18checkFileReadCacheEbE4$_19Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xd1d48 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN13HttpResponderC1EO20QHttpServerResponderP7QObjectE4$_20Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES5_PPvPb` | 0xd1ed0 | 40 |
| `_ZN12PhocusObject22notify_image_availableE5QListI4QMapI7QString8QVariantEEjRK12QDBusMessage` | 0x1193d8 | 668 |

</details>

**New objects (120)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeI5QListIN9HblmTypes15E_FaceDetectionEEE4nameE` | 0x190eb9 | 34 |
| `_ZTSNSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EEE` | 0x190f11 | 222 |
| `_ZTSZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS4_EEEEbT1_EUlPKvPvE_` | 0x190fef | 165 |
| `_ZTSNSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EEE` | 0x191094 | 228 |
| `_ZTSZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS4_EEEEbT1_EUlPvSC_E_` | 0x191178 | 171 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EEE` | 0x192a58 | 175 |
| `_ZTSNSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE` | 0x192bc1 | 185 |
| `_ZTSZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS_21FileAllocationVersionEE4$_17` | 0x192cb0 | 112 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EEE` | 0x193bc8 | 119 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EEE` | 0x193ca6 | 128 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EEE` | 0x193d8f | 159 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EEE` | 0x193e2e | 143 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JEEE` | 0x193fa2 | 84 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EEE` | 0x193ff6 | 87 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JEEE` | 0x19404d | 101 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEEE` | 0x1940b2 | 116 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_20JEEE` | 0x194126 | 107 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEEE` | 0x194191 | 122 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x19420b | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x19437d | 182 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x19447e | 89 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS5_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x1944d7 | 215 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x194d10 | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE` | 0x194e23 | 199 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_` | 0x194f38 | 103 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x194f9f | 215 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x19578c | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEEE` | 0x19589f | 206 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZZN5HttpdC1EjP7PhocusDENK3$_5clERK7QStringS7_S7_RK18QHttpServerRequestEUlvE_JEEE` | 0x19596d | 117 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_` | 0x1959e2 | 103 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x195a49 | 215 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x195b20 | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x195c33 | 182 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x195ce9 | 89 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS5_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x195d42 | 215 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x19e83c | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_128qt_meta_stringdata_PhocusD_tEJN9QtPrivate20TypeAndForceCompleteI7PhocusDNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IbS9_EESA_NS3_IN9HblmTypes14E_TetheredModeES9_EESA_NS3_IRK4QMapIN13PhocusMessage11DestinationE13phocus_clientES9_EESA_NS3_ISH_S9_EENS3_IRK5QListINSC_13E_ImageFormatEES9_EESA_SN_NS3_IRKSO_INSC_15E_FaceDetectionEES9_EESA_SN_NS3_IRKSO_INSC_10E_CropModeEES9_EESA_SN_NS3_IiS9_EESA_NS3_INSC_7E_HostsES9_EESA_SN_NS3_IRK10QByteArrayS9_EESA_NS3_IKS15_S9_EESA_SA_SB_SA_EE` | 0x203cb0 | 240 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_135qt_meta_stringdata_PhocusNotifier_tEJN9QtPrivate20TypeAndForceCompleteI14PhocusNotifierNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK13PhocusMessageS9_EESA_NS3_IiS9_EESA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_NS3_IN9HblmTypes9E_LmModesES9_EESA_NS3_INSG_9E_ExpModeES9_EESA_SF_SA_NS3_IPK15VariantMapModelS9_EESA_SF_SA_SF_SA_NS3_INSG_13E_MediaStatusES9_EESA_SQ_SA_SF_SA_NS3_IRK7QStringS9_EESA_SU_SA_SU_SA_SU_SA_SU_SA_NS3_ItS9_EESA_NS3_IRK4QMapISR_8QVariantES9_EESA_SV_SA_NS3_INSG_12E_CameraModeES9_EESA_NS3_I5QListIiES9_EESA_S16_SA_S16_SA_SA_SA_NS3_IjS9_EESA_S17_SA_SA_NS3_INSG_16E_StopDownStatusES9_EESA_SF_SA_NS3_INSG_12E_WhiteModesES9_EESA_SF_SA_SF_SA_SA_SA_SF_SA_NS3_INSG_12E_ExitOptionES9_EESA_SF_SA_SF_SA_SF_SA_S1D_SA_SF_SA_SF_SA_NS3_INSG_20E_ExpBracketingParamES9_EESA_SF_SA_SF_SA_S1D_SA_NS3_INSG_26E_FocusBracketingStepSizesES9_EESA_SF_SA_SF_SA_SF_SA_NS3_INSG_27E_FocusBracketingStrategiesES9_EESA_S1D_SA_SF_SA_NS3_INSG_15E_StorageDeviceES9_EESA_NS3_INSG_13E_StorageModeES9_EESA_NS3_IbS9_EESA_NS3_INSG_14E_TetheredModeES9_EESA_NS3_INSG_14E_DistanceUnitES9_EESA_NS3_INSG_12E_CameraTypeES9_EESA_SA_SF_SA_SF_SA_SA_SA_SA_SA_SA_SA_S1O_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x204b40 | 1200 |
| `_ZTVNSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EEE` | 0x2053c0 | 88 |
| `_ZTINSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EEE` | 0x205418 | 24 |
| `_ZN13QMetaSequence12MetaSequenceI5QListIN9HblmTypes15E_FaceDetectionEEE5valueE` | 0x205430 | 216 |
| `_ZTIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS4_EEEEbT1_EUlPKvPvE_` | 0x205508 | 16 |
| `_ZTVNSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EEE` | 0x205518 | 88 |
| `_ZTINSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EEE` | 0x205570 | 24 |
| `_ZTIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS4_EEEEbT1_EUlPvSC_E_` | 0x205588 | 16 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EEE` | 0x205988 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EEE` | 0x2059d0 | 24 |
| `_ZTVNSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE` | 0x205a50 | 88 |
| `_ZTINSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE` | 0x205ab8 | 24 |
| `_ZTIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS_21FileAllocationVersionEE4$_17` | 0x205ad0 | 16 |

<details><summary>… 另 70 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EEE` | 0x206830 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EEE` | 0x206878 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EEE` | 0x2068f8 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EEE` | 0x206940 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EEE` | 0x2069c0 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EEE` | 0x2069f0 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EEE` | 0x206a08 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EEE` | 0x206a50 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JEEE` | 0x206ad0 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JEEE` | 0x206b00 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EEE` | 0x206b18 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EEE` | 0x206b48 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JEEE` | 0x206b60 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JEEE` | 0x206b90 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEEE` | 0x206ba8 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEEE` | 0x206bd8 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_20JEEE` | 0x206bf0 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_20JEEE` | 0x206c20 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEEE` | 0x206c38 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEEE` | 0x206c68 | 24 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x206c80 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x206ce8 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x206d00 | 88 |
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x206d68 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x206d80 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS5_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x206d90 | 16 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x207058 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x2070b0 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE` | 0x2070c8 | 88 |
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE` | 0x207130 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_` | 0x207148 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x207158 | 16 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x207420 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x207478 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEEE` | 0x207490 | 88 |
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEEE` | 0x2074e8 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZZN5HttpdC1EjP7PhocusDENK3$_5clERK7QStringS7_S7_RK18QHttpServerRequestEUlvE_JEEE` | 0x207500 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZZN5HttpdC1EjP7PhocusDENK3$_5clERK7QStringS7_S7_RK18QHttpServerRequestEUlvE_JEEE` | 0x207530 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_` | 0x207548 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x207558 | 16 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x207588 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x2075e0 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x2075f8 | 88 |
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x207650 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x207668 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS5_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x207678 | 16 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IRK4QMapISB_8QVariantES9_EENS3_IKiS9_EESA_SE_SK_SM_SA_SE_SK_SM_SA_SE_NS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_SE_SQ_SK_SA_SE_SQ_SA_SE_SA_NS3_IRK5QListISB_ES9_EESA_SE_SK_EE` | 0x2080d0 | 240 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_PhocusObject_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IjS6_EES7_NS3_I12PhocusObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKhSB_EENS3_IRK10QByteArraySB_EESC_NS3_IKN9HblmTypes7E_HostsESB_EESC_NS3_IKjSB_EESC_SM_SC_SE_SI_SC_NS3_IK5QListI4QMapI7QString8QVariantEESB_EESO_NS3_IKiSB_EENS3_IRK12QDBusMessageSB_EESC_SE_SI_S12_EE` | 0x2083f8 | 200 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESB_SB_S7_SB_NS3_INS8_20E_ExpBracketingParamES6_EESB_NS3_INS8_12E_ExitOptionES6_EESB_SB_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EESP_NS3_INS8_10E_CropModeES6_EESB_S7_NS3_INS8_12E_DriveModesES6_EESR_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SB_SB_NS3_INS8_9E_ExpModeES6_EESJ_S7_SB_NS3_INS8_21E_ExposureControlModeES6_EES11_SB_NS3_INS8_16E_ExposureStatusES6_EESB_SV_S7_SB_SB_SB_SB_SB_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_27E_FocusBracketingStrategiesES6_EENS3_I4QMapI7QString8QVariantES6_EENS3_INS8_12E_FocusModesES6_EESJ_S1C_SJ_NS3_INS8_11E_FocusSizeES6_EESX_SB_SB_SI_SB_SB_NS3_IS19_S6_EENS3_ItS6_EESJ_SJ_S7_S7_S7_S1I_SJ_S1H_S1H_S1H_S7_S1H_SB_S7_NS3_INS8_15E_LiveViewStateES6_EENS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EESJ_NS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EESB_SB_SI_SB_S1I_NS3_INS8_24E_SpiritLevelOrientationES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESB_SB_SB_SE_SB_SB_SB_SE_SB_SB_S7_SB_NS3_INS8_14E_DistanceUnitES6_EESR_SB_SB_SB_NS3_INS8_12E_WhiteModesES6_EESB_SB_S7_SJ_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbS27_EES28_S29_S28_NS3_IS9_S27_EES28_NS3_IiS27_EES28_NS3_IRKSD_S27_EES28_S2B_S28_S2B_S28_S29_S28_S2B_S28_NS3_ISF_S27_EES28_S2B_S28_NS3_ISH_S27_EES28_S2B_S28_S2B_S28_NS3_IjS27_EES28_NS3_ISK_S27_EES28_NS3_ISM_S27_EES28_NS3_ISO_S27_EES28_S2K_S28_NS3_ISQ_S27_EES28_S2B_S28_S29_S28_NS3_ISS_S27_EES28_S2L_S28_NS3_ISU_S27_EES28_NS3_ISW_S27_EES28_S29_S28_S2B_S28_S2B_S28_NS3_ISY_S27_EES28_S2H_S28_S29_S28_S2B_S28_NS3_IS10_S27_EES28_S2Q_S28_S2B_S28_NS3_IS12_S27_EES28_S2B_S28_S2N_S28_S29_S28_S2B_S28_S2B_S28_S2B_S28_S2B_S28_S2B_S28_NS3_IS14_S27_EES28_NS3_IS16_S27_EES28_NS3_IRKS1B_S27_EES28_NS3_IS1D_S27_EES28_S2H_S28_S2W_S28_S2H_S28_NS3_IS1F_S27_EES28_S2O_S28_S2B_S28_S2B_S28_S2G_S28_S2B_S28_S2B_S28_NS3_IRKS19_S27_EES28_NS3_ItS27_EES28_S2H_S28_S2H_S28_S29_S28_S29_S28_S29_S28_S32_S28_S2H_S28_S31_S28_S31_S28_S31_S28_S29_S28_S31_S28_S2B_S28_S29_S28_NS3_IS1J_S27_EES28_NS3_IS1L_S27_EES28_NS3_IS1N_S27_EES28_S2H_S28_NS3_IS1P_S27_EES28_NS3_IS1R_S27_EES28_NS3_IS1T_S27_EES28_S2B_S28_S2B_S28_S2G_S28_S2B_S28_S32_S28_NS3_IS1V_S27_EES28_NS3_IS1X_S27_EES28_NS3_IS1Z_S27_EES28_S2B_S28_S2B_S28_S2B_S28_S2E_S28_S2B_S28_S2B_S28_S2B_S28_S2E_S28_S2B_S28_S2B_S28_S29_S28_S2B_S28_NS3_IS21_S27_EES28_S2L_S28_S2B_S28_S2B_S28_S2B_S28_NS3_IS23_S27_EES28_S2B_S28_S2B_S28_S29_S28_S2H_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_S28_S29_EE` | 0x208508 | 3016 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes20E_CaptureStorageModeENSt3__117integral_constantIbLb1EEEEENS3_IbS8_EENS3_IjS8_EENS3_INS4_13E_MediaStatusES8_EESD_NS3_INS4_15E_StorageDeviceES8_EENS3_INS4_13E_StorageModeES8_EENS3_INS4_15E_StorageStatusES8_EENS3_IP15VariantMapModelS8_EESA_SA_SA_SA_SA_SA_SA_NS3_I12StorageProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IRK7QStringSP_EENS3_IRK4QMapISR_8QVariantESP_EENS3_IKNS4_21E_StorageUpdateReasonESP_EESQ_SU_S10_S13_SQ_SU_S10_S13_SQ_NS3_IS5_SP_EESQ_NS3_IbSP_EESQ_NS3_IjSP_EESQ_NS3_ISC_SP_EESQ_S17_SQ_NS3_ISE_SP_EESQ_NS3_ISG_SP_EESQ_NS3_ISI_SP_EESQ_NS3_IPKSK_SP_EESQ_S15_SQ_S15_SQ_S15_SQ_S15_SQ_S15_SQ_S15_EE` | 0x209338 | 472 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes16E_BtAssistStatusENSt3__117integral_constantIbLb1EEEEENS3_IbS8_EESA_NS3_INS4_13E_DebugOptionES8_EENS3_ItS8_EENS3_INS4_9E_ScreensES8_EESF_NS3_INS4_24E_SpiritLevelOrientationES8_EENS3_INS4_13E_SystemStateES8_EENS3_INS4_14E_TetheredModeES8_EESA_NS3_I7QStringS8_EESA_SN_SA_SA_SA_SA_SA_SA_SA_NS3_I11SystemProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SQ_EESR_NS3_IbSQ_EESR_ST_SR_NS3_ISB_SQ_EESR_NS3_ItSQ_EESR_NS3_ISE_SQ_EESR_SW_SR_NS3_ISG_SQ_EESR_NS3_ISI_SQ_EESR_NS3_ISK_SQ_EESR_ST_SR_NS3_IRKSM_SQ_EESR_ST_SR_S12_SR_ST_SR_ST_SR_ST_SR_ST_SR_ST_SR_ST_EE` | 0x209520 | 496 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI5QListIN9HblmTypes15E_FaceDetectionEEE8metaTypeE` | 0x210e78 | 112 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x212758 | 112 |
| `_ZZN11QMetaTypeIdI5QListIN9HblmTypes15E_FaceDetectionEEE14qt_metatype_idEvE11metatype_id` | 0x217140 | 4 |
| `_ZZN9QMetaType21registerConverterImplI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEEEbNSt3__18functionIFbPKvPvEEES_S_E10unregister` | 0x217148 | 24 |
| `_ZGVZN9QMetaType21registerConverterImplI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEEEbNSt3__18functionIFbPKvPvEEES_S_E10unregister` | 0x217160 | 8 |
| `_ZZN9QMetaType23registerMutableViewImplI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEEEbNSt3__18functionIFbPvSA_EEES_S_E10unregister` | 0x217168 | 24 |
| `_ZGVZN9QMetaType23registerMutableViewImplI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEEEbNSt3__18functionIFbPvSA_EEES_S_E10unregister` | 0x217180 | 8 |
| `_ZN4Json7Content3KeyL11kCameraBodyE` | 0x219c60 | 24 |
| `_ZN4Json7Content3KeyL7kRatingE` | 0x219e00 | 24 |
| `_ZN4Json7Content3KeyL12kFocalLengthE` | 0x219e20 | 24 |
| `_ZN4Json7Content3KeyL13kCameraSerialE` | 0x219e40 | 24 |
| `_ZN4Json7Content3KeyL14kImageUniqueIdE` | 0x219e60 | 24 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x21a6d0 | 4 |
| `_ZN14PhocusProtocolL15kVolumeLabelSsdE` | 0x21a970 | 24 |
| `_ZN14PhocusProtocolL15kVolumeLabelCfeE` | 0x21a990 | 24 |
| `_ZN12_GLOBAL__N_111kMetaTagMapE` | 0x21b0c0 | 8 |
| `_ZN12_GLOBAL__N_114kStorageTagMapE` | 0x21b0c8 | 8 |
| `_ZZN7Version11readCmdlineEvE13cachedCmdline` | 0x21b1a0 | 24 |
| `_ZGVZN7Version11readCmdlineEvE13cachedCmdline` | 0x21b1b8 | 8 |

</details>

**Removed objects (167)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeI20phocus_tethered_modeE4nameE` | 0x17f2df | 21 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_17JS8_SE_EEE` | 0x180e60 | 175 |
| `_ZTSNSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE` | 0x180fc9 | 185 |
| `_ZTSZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS_21FileAllocationVersionEE4$_15` | 0x1810b8 | 112 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_8JS2_S2_iiS6_EEE` | 0x181f78 | 119 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE3$_9JS2_jiS5_EEE` | 0x182056 | 127 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_11JS2_S6_S7_EEE` | 0x18213e | 159 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_13JS2_S6_EEE` | 0x1821dd | 143 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_15JEEE` | 0x182351 | 84 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JS2_EEE` | 0x1823a5 | 87 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_17JEEE` | 0x1823fc | 101 |
| `_ZTSN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JS2_10QByteArrayEEE` | 0x182461 | 116 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1824d5 | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x182647 | 182 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x182748 | 89 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS5_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x1827a1 | 215 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x182fda | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE` | 0x1830ed | 199 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_` | 0x183202 | 103 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x183269 | 215 |
| `_ZTSNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x183a56 | 275 |
| `_ZTSNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x183b69 | 182 |
| `_ZTSZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x183c1f | 89 |
| `_ZTSZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS5_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x183c78 | 215 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_128qt_meta_stringdata_PhocusD_tEJN9QtPrivate20TypeAndForceCompleteI7PhocusDNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IbS9_EESA_NS3_IRK20phocus_tethered_modeS9_EESA_NS3_IRK4QMapIN13PhocusMessage11DestinationE13phocus_clientES9_EESA_NS3_ISI_S9_EENS3_IRK5QListIN9HblmTypes13E_ImageFormatEES9_EESA_SO_NS3_IRKSP_INSQ_10E_CropModeEES9_EESA_SO_NS3_IiS9_EESA_SO_NS3_IRK10QByteArrayS9_EESA_NS3_IKNSQ_7E_HostsES9_EESA_SA_SB_SA_EE` | 0x1f43b8 | 200 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_135qt_meta_stringdata_PhocusNotifier_tEJN9QtPrivate20TypeAndForceCompleteI14PhocusNotifierNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK13PhocusMessageS9_EESA_NS3_IiS9_EESA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_SF_SA_NS3_IN9HblmTypes9E_LmModesES9_EESA_NS3_INSG_9E_ExpModeES9_EESA_SF_SA_NS3_IPK15VariantMapModelS9_EESA_SF_SA_SF_SA_NS3_INSG_13E_MediaStatusES9_EESA_SQ_SA_SF_SA_NS3_IRK7QStringS9_EESA_SU_SA_SU_SA_SU_SA_SU_SA_NS3_ItS9_EESA_NS3_IRK4QMapISR_8QVariantES9_EESA_SV_SA_NS3_INSG_12E_CameraModeES9_EESA_NS3_I5QListIiES9_EESA_S16_SA_S16_SA_SA_SA_NS3_IjS9_EESA_S17_SA_SA_NS3_INSG_16E_StopDownStatusES9_EESA_SF_SA_NS3_INSG_12E_WhiteModesES9_EESA_SF_SA_SF_SA_SA_SA_SF_SA_NS3_INSG_12E_ExitOptionES9_EESA_SF_SA_SF_SA_SF_SA_S1D_SA_SF_SA_SF_SA_NS3_INSG_20E_ExpBracketingParamES9_EESA_SF_SA_SF_SA_S1D_SA_NS3_INSG_26E_FocusBracketingStepSizesES9_EESA_SF_SA_SF_SA_SF_SA_NS3_INSG_27E_FocusBracketingStrategiesES9_EESA_S1D_SA_SF_SA_NS3_INSG_15E_StorageDeviceES9_EESA_NS3_INSG_13E_StorageModeES9_EESA_NS3_IbS9_EESA_NS3_IRK20phocus_tethered_modeS9_EESA_NS3_INSG_14E_DistanceUnitES9_EESA_NS3_INSG_12E_CameraTypeES9_EESA_SA_SF_SA_SA_SA_SA_SA_S1O_SA_SA_SA_SA_SA_SA_SA_SA_SA_EE` | 0x1f5218 | 1168 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_17JS8_SE_EEE` | 0x1f5e68 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_17JS8_SE_EEE` | 0x1f5eb0 | 24 |
| `_ZTVNSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE` | 0x1f5f30 | 88 |
| `_ZTINSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_15NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE` | 0x1f5f98 | 24 |
| `_ZTIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS_21FileAllocationVersionEE4$_15` | 0x1f5fb0 | 16 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_8JS2_S2_iiS6_EEE` | 0x1f6d10 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_8JS2_S2_iiS6_EEE` | 0x1f6d58 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE3$_9JS2_jiS5_EEE` | 0x1f6dd8 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE3$_9JS2_jiS5_EEE` | 0x1f6e20 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_11JS2_S6_S7_EEE` | 0x1f6ea0 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_11JS2_S6_S7_EEE` | 0x1f6ed0 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_13JS2_S6_EEE` | 0x1f6ee8 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_13JS2_S6_EEE` | 0x1f6f30 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_15JEEE` | 0x1f6fb0 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_15JEEE` | 0x1f6fe0 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JS2_EEE` | 0x1f6ff8 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JS2_EEE` | 0x1f7028 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_17JEEE` | 0x1f7040 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_17JEEE` | 0x1f7070 | 24 |
| `_ZTVN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JS2_10QByteArrayEEE` | 0x1f7088 | 48 |
| `_ZTIN12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JS2_10QByteArrayEEE` | 0x1f70b8 | 24 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1f70d0 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1f7138 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x1f7150 | 88 |

<details><summary>… 另 117 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x1f71b8 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x1f71d0 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS5_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x1f71e0 | 16 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1f74a8 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1f7500 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE` | 0x1f7518 | 88 |
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE` | 0x1f7580 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_` | 0x1f7598 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x1f75a8 | 16 |
| `_ZTVNSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1f7890 | 88 |
| `_ZTINSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE` | 0x1f78e8 | 24 |
| `_ZTVNSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x1f7900 | 88 |
| `_ZTINSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE` | 0x1f7958 | 24 |
| `_ZTIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7JEEEDaOT_DpOT0_EUlDpOT_E_` | 0x1f7970 | 16 |
| `_ZTIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS5_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_` | 0x1f7980 | 16 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_137qt_meta_stringdata_StorageProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI16StorageProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IRK7QStringS9_EENS3_IRK4QMapISB_8QVariantES9_EENS3_IKiS9_EESA_SE_SK_SM_SA_SE_SK_SM_SA_SE_NS3_IKN9HblmTypes17E_MetadataOptionsES9_EESA_SE_SQ_SK_SA_SE_SQ_SA_SE_EE` | 0x1f83d8 | 200 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_PhocusObject_tEJN9QtPrivate20TypeAndForceCompleteIiNSt3__117integral_constantIbLb1EEEEENS3_IjS6_EENS3_I12PhocusObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKhSB_EENS3_IRK10QByteArraySB_EESC_NS3_IKN9HblmTypes7E_HostsESB_EESC_NS3_IKjSB_EESC_SE_SI_SC_NS3_IK5QListI4QMapI7QString8QVariantEESB_EESO_NS3_IRK12QDBusMessageSB_EESC_SE_SI_S10_EE` | 0x1f86d8 | 168 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_NS3_IN9HblmTypes10E_LensTypeES6_EENS3_IiS6_EENS3_I5QListIiES6_EESB_SB_S7_SB_NS3_INS8_20E_ExpBracketingParamES6_EESB_NS3_INS8_12E_ExitOptionES6_EESB_SB_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EESP_NS3_INS8_10E_CropModeES6_EESB_S7_NS3_INS8_12E_DriveModesES6_EESR_NS3_INS8_13E_ImageFormatES6_EES7_SB_SB_NS3_INS8_9E_ExpModeES6_EESJ_S7_SB_NS3_INS8_21E_ExposureControlModeES6_EESZ_SB_NS3_INS8_16E_ExposureStatusES6_EENS3_INS8_15E_FaceDetectionES6_EESB_SB_SB_SB_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_27E_FocusBracketingStrategiesES6_EENS3_I4QMapI7QString8QVariantES6_EENS3_INS8_12E_FocusModesES6_EESJ_S1C_SJ_NS3_INS8_11E_FocusSizeES6_EESV_SB_SB_SI_SB_SB_NS3_IS19_S6_EENS3_ItS6_EESJ_SJ_S7_S7_S7_S1I_SJ_S1H_S1H_S1H_S7_S1H_SB_S7_NS3_INS8_15E_LiveViewStateES6_EENS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EESJ_NS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EESB_SB_SI_SB_S1I_NS3_INS8_24E_SpiritLevelOrientationES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EESB_SB_SB_SE_SB_SB_SB_SE_SB_SB_S7_SB_NS3_INS8_14E_DistanceUnitES6_EESR_SB_SB_SB_NS3_INS8_12E_WhiteModesES6_EESB_SB_S7_SJ_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbS25_EES26_S27_S26_NS3_IS9_S25_EES26_NS3_IiS25_EES26_NS3_IRKSD_S25_EES26_S29_S26_S29_S26_S27_S26_S29_S26_NS3_ISF_S25_EES26_S29_S26_NS3_ISH_S25_EES26_S29_S26_S29_S26_NS3_IjS25_EES26_NS3_ISK_S25_EES26_NS3_ISM_S25_EES26_NS3_ISO_S25_EES26_S2I_S26_NS3_ISQ_S25_EES26_S29_S26_S27_S26_NS3_ISS_S25_EES26_S2J_S26_NS3_ISU_S25_EES26_S27_S26_S29_S26_S29_S26_NS3_ISW_S25_EES26_S2F_S26_S27_S26_S29_S26_NS3_ISY_S25_EES26_S2N_S26_S29_S26_NS3_IS10_S25_EES26_NS3_IS12_S25_EES26_S29_S26_S29_S26_S29_S26_S29_S26_NS3_IS14_S25_EES26_NS3_IS16_S25_EES26_NS3_IRKS1B_S25_EES26_NS3_IS1D_S25_EES26_S2F_S26_S2U_S26_S2F_S26_NS3_IS1F_S25_EES26_S2L_S26_S29_S26_S29_S26_S2E_S26_S29_S26_S29_S26_NS3_IRKS19_S25_EES26_NS3_ItS25_EES26_S2F_S26_S2F_S26_S27_S26_S27_S26_S27_S26_S30_S26_S2F_S26_S2Z_S26_S2Z_S26_S2Z_S26_S27_S26_S2Z_S26_S29_S26_S27_S26_NS3_IS1J_S25_EES26_NS3_IS1L_S25_EES26_NS3_IS1N_S25_EES26_S2F_S26_NS3_IS1P_S25_EES26_NS3_IS1R_S25_EES26_S29_S26_S29_S26_S2E_S26_S29_S26_S30_S26_NS3_IS1T_S25_EES26_NS3_IS1V_S25_EES26_NS3_IS1X_S25_EES26_S29_S26_S29_S26_S29_S26_S2C_S26_S29_S26_S29_S26_S29_S26_S2C_S26_S29_S26_S29_S26_S27_S26_S29_S26_NS3_IS1Z_S25_EES26_S2J_S26_S29_S26_S29_S26_S29_S26_NS3_IS21_S25_EES26_S29_S26_S29_S26_S27_S26_S2F_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_S26_S27_EE` | 0x1f87c8 | 2896 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_StorageProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes20E_CaptureStorageModeENSt3__117integral_constantIbLb1EEEEENS3_IbS8_EENS3_IjS8_EENS3_INS4_13E_MediaStatusES8_EESD_NS3_INS4_15E_StorageDeviceES8_EENS3_INS4_13E_StorageModeES8_EENS3_INS4_15E_StorageStatusES8_EENS3_IP15VariantMapModelS8_EESA_SA_SA_SA_SA_NS3_I12StorageProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IRK7QStringSP_EENS3_IRK4QMapISR_8QVariantESP_EENS3_IKNS4_21E_StorageUpdateReasonESP_EESQ_SU_S10_S13_SQ_SU_S10_S13_SQ_NS3_IS5_SP_EESQ_NS3_IbSP_EESQ_NS3_IjSP_EESQ_NS3_ISC_SP_EESQ_S17_SQ_NS3_ISE_SP_EESQ_NS3_ISG_SP_EESQ_NS3_ISI_SP_EESQ_NS3_IPKSK_SP_EESQ_S15_SQ_S15_SQ_S15_SQ_S15_EE` | 0x1f9580 | 424 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes16E_BtAssistStatusENSt3__117integral_constantIbLb1EEEEENS3_IbS8_EESA_NS3_ItS8_EENS3_INS4_9E_ScreensES8_EESD_NS3_INS4_24E_SpiritLevelOrientationES8_EENS3_INS4_13E_SystemStateES8_EENS3_INS4_14E_TetheredModeES8_EESA_NS3_I7QStringS8_EESA_SL_SA_SA_SA_SA_SA_SA_SA_NS3_I11SystemProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SO_EESP_NS3_IbSO_EESP_SR_SP_NS3_ItSO_EESP_NS3_ISC_SO_EESP_ST_SP_NS3_ISE_SO_EESP_NS3_ISG_SO_EESP_NS3_ISI_SO_EESP_SR_SP_NS3_IRKSK_SO_EESP_SR_SP_SZ_SP_SR_SP_SR_SP_SR_SP_SR_SP_SR_SP_SR_EE` | 0x1f9738 | 472 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperI20phocus_tethered_modeE8metaTypeE` | 0x200af8 | 112 |
| `_ZN12_GLOBAL__N_115kVolumeLabelSsdE` | 0x207e00 | 24 |
| `_ZN12_GLOBAL__N_115kVolumeLabelCfeE` | 0x207e20 | 24 |
| `_ZL11TAG_MOUNTED` | 0x20aa40 | 24 |
| `_ZL8TAG_TYPE` | 0x20aa60 | 24 |
| `_ZL8TAG_NAME` | 0x20aa80 | 24 |
| `_ZL8TAG_UUID` | 0x20aaa0 | 24 |
| `_ZL15TAG_EXPOSURE_ID` | 0x20aac0 | 24 |
| `_ZL8TAG_SIZE` | 0x20aae0 | 24 |
| `_ZL10TAG_OFFSET` | 0x20ab00 | 24 |
| `_ZL10TAG_HANDLE` | 0x20ab20 | 24 |
| `_ZL15TAG_DEVICE_TYPE` | 0x20ab40 | 24 |
| `_ZL13TAG_SIZECHILD` | 0x20ab60 | 24 |
| `_ZL13TAG_FULL_PATH` | 0x20ab80 | 24 |
| `_ZL16TAG_DISPLAY_PATH` | 0x20aba0 | 24 |
| `_ZL28TAG_DISPLAY_PATH_WITH_SUFFIX` | 0x20abc0 | 24 |
| `_ZL12TAG_METADATA` | 0x20abe0 | 24 |
| `_ZL15TAG_LORES_IMAGE` | 0x20ac00 | 24 |
| `_ZL15TAG_THUMB_IMAGE` | 0x20ac20 | 24 |
| `_ZL14TAG_TILE_IMAGE` | 0x20ac40 | 24 |
| `_ZL14TAG_FREE_SPACE` | 0x20ac60 | 24 |
| `_ZL16TAG_WRITEPROTECT` | 0x20ac80 | 24 |
| `_ZL10TAG_STATUS` | 0x20aca0 | 24 |
| `_ZL6TAG_WP` | 0x20acc0 | 24 |
| `_ZL14TAG_SLOW_SPEED` | 0x20ace0 | 24 |
| `_ZL17TAG_AVERAGE_SPEED` | 0x20ad00 | 24 |
| `_ZL13TAG_DATE_TIME` | 0x20ad20 | 24 |
| `_ZL6TAG_SV` | 0x20ad40 | 24 |
| `_ZL6TAG_AV` | 0x20ad60 | 24 |
| `_ZL21TAG_FNUMBER_NUMERATOR` | 0x20ad80 | 24 |
| `_ZL23TAG_FNUMBER_DENOMINATOR` | 0x20ada0 | 24 |
| `_ZL10TAG_AV_MIN` | 0x20adc0 | 24 |
| `_ZL6TAG_TV` | 0x20ade0 | 24 |
| `_ZL13TAG_FOCAL_LEN` | 0x20ae00 | 24 |
| `_ZL17TAG_EXPOSURE_MODE` | 0x20ae20 | 24 |
| `_ZL27TAG_EXPOSURE_TIME_NUMERATOR` | 0x20ae40 | 24 |
| `_ZL29TAG_EXPOSURE_TIME_DENOMINATOR` | 0x20ae60 | 24 |
| `_ZL11TAG_LM_MODE` | 0x20ae80 | 24 |
| `_ZL6TAG_WB` | 0x20aea0 | 24 |
| `_ZL10TAG_EV_ADJ` | 0x20aec0 | 24 |
| `_ZL17TAG_EXPOSURE_BIAS` | 0x20aee0 | 24 |
| `_ZL14TAG_LENS_SHIFT` | 0x20af00 | 24 |
| `_ZL16TAG_LENS_VERSION` | 0x20af20 | 24 |
| `_ZL27TAG_LENS_SHADING_CORRECTION` | 0x20af40 | 24 |
| `_ZL21TAG_LENS_FOCAL_MINMAX` | 0x20af60 | 24 |
| `_ZL13TAG_LENS_TYPE` | 0x20af80 | 24 |
| `_ZL13TAG_HISTOGRAM` | 0x20afa0 | 24 |
| `_ZL16TAG_FS_TIMESTAMP` | 0x20afc0 | 24 |
| `_ZL8TAG_PATH` | 0x20afe0 | 24 |
| `_ZL14TAG_PERSISTENT` | 0x20b000 | 24 |
| `_ZL15TAG_R_NUMERATOR` | 0x20b020 | 24 |
| `_ZL17TAG_R_DENOMINATOR` | 0x20b040 | 24 |
| `_ZL15TAG_G_NUMERATOR` | 0x20b060 | 24 |
| `_ZL17TAG_G_DENOMINATOR` | 0x20b080 | 24 |
| `_ZL15TAG_B_NUMERATOR` | 0x20b0a0 | 24 |
| `_ZL17TAG_B_DENOMINATOR` | 0x20b0c0 | 24 |
| `_ZL22TAG_BLACK_LEVEL_OFFSET` | 0x20b0e0 | 24 |
| `_ZL15TAG_WHITE_LEVEL` | 0x20b100 | 24 |
| `_ZL20TAG_SENSITIVITY_GAIN` | 0x20b120 | 24 |
| `_ZL18TAG_R_NEUTRAL_GAIN` | 0x20b140 | 24 |
| `_ZL18TAG_G_NEUTRAL_GAIN` | 0x20b160 | 24 |
| `_ZL18TAG_B_NEUTRAL_GAIN` | 0x20b180 | 24 |
| `_ZL21TAG_NEUTRAL_PRECISION` | 0x20b1a0 | 24 |
| `_ZL16TAG_IMAGE_RATING` | 0x20b1c0 | 24 |
| `_ZL18TAG_IMAGE_ROTATION` | 0x20b1e0 | 24 |
| `_ZL15TAG_CAMERA_TYPE` | 0x20b200 | 24 |
| `_ZL15TAG_FOCUS_POINT` | 0x20b220 | 24 |
| `_ZL20TAG_SUBJECT_DISTANCE` | 0x20b240 | 24 |
| `_ZL14TAG_LENS_MODEL` | 0x20b260 | 24 |
| `_ZL13TAG_LENS_MAKE` | 0x20b280 | 24 |
| `_ZL17TAG_FOCUS_SEGMENT` | 0x20b2a0 | 24 |
| `_ZL17TAG_LENS_MODEL_ID` | 0x20b2c0 | 24 |
| `_ZL9TAG_FILES` | 0x20b2e0 | 24 |
| `_ZL14IMAGE_TAG_DATA` | 0x20b300 | 24 |
| `_ZL16IMAGE_TAG_FORMAT` | 0x20b320 | 24 |
| `_ZL15IMAGE_TAG_WIDTH` | 0x20b340 | 24 |
| `_ZL16IMAGE_TAG_HEIGHT` | 0x20b360 | 24 |
| `_ZL11IMAGE_TAG_X` | 0x20b380 | 24 |
| `_ZL11IMAGE_TAG_Y` | 0x20b3a0 | 24 |
| `_ZL19IMAGE_TAG_BUFFER_ID` | 0x20b3c0 | 24 |
| `_ZL17IMAGE_FORMAT_RGBA` | 0x20b3e0 | 24 |
| `_ZL17IMAGE_FORMAT_UYVY` | 0x20b400 | 24 |
| `_ZL17IMAGE_FORMAT_NV12` | 0x20b420 | 24 |
| `_ZL17IMAGE_FORMAT_422P` | 0x20b440 | 24 |
| `_ZL17IMAGE_FORMAT_JPEG` | 0x20b460 | 24 |
| `_ZL12STORAGE_ROOT` | 0x20b480 | 24 |
| `_ZL13TETHERED_ROOT` | 0x20b4a0 | 24 |
| `_ZL17STORAGE_MOUNT_SSD` | 0x20b4c0 | 24 |
| `_ZL20STORAGE_MOUNT_CFCARD` | 0x20b4e0 | 24 |
| `_ZL17HASBL_FOLDER_NAME` | 0x20b500 | 24 |
| `_ZL9NAME_ROOT` | 0x20b520 | 24 |
| `_ZL9NAME_DCIM` | 0x20b540 | 24 |
| `_ZL11SOCKET_NAME` | 0x20b560 | 24 |
| `_ZL11EXPOSURE_ID` | 0x20b580 | 24 |
| `_ZL14DCAM_CONTAINER` | 0x20b5a0 | 24 |
| `_ZL10FRAME_INFO` | 0x20b5c0 | 24 |
| `_ZL18EXPOSURE_ITEM_TYPE` | 0x20b5e0 | 24 |

</details>

### `/bin/camera-expose`

+160 / −132 functions · +4 / −1 objects

**New functions (160)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x42908 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x42918 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x42920 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x42920 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x42930 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x42948 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x429f8 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x42a08 | 12 |
| `_ZN15OdinDbSendUtils21convertStringToBitsetIN9HblmTypes16E_SessionOptionsELm7EEEbRK7QStringRT_` | 0x65ab0 | 1876 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_106Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x852a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_107Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x85a30 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_108Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x85ed8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_110Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86680 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_111Li1ENS_4ListIJN9HblmTypes12E_DriveModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86a40 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_112Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86ee8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_113Li1ENS_4ListIJN9HblmTypes9E_ExpModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87590 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_114Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87a38 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_115Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87df8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_116Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x881e0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_117Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x88888 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_118Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x88d30 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_119Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x89118 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_120Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x895c0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_121Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x89980 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_122Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x89d40 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_123Li1ENS_4ListIJN9HblmTypes16E_ExposureStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a100 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_124Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a4e0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_125Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a8a0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_126Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8ac60 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_127Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8b108 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_128Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8b4f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_129Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8b8b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_131Li1ENS_4ListIJN9HblmTypes12E_FlashModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8c318 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_133Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8cb80 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_134Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8cf40 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_135Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8d300 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_136Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8d6c0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_137Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8de50 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_138Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8e2f8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_139Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8e6b8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_140Li1ENS_4ListIJN9HblmTypes12E_FocusModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8ed60 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_141Li1ENS_4ListIJN9HblmTypes19E_FocusPeakingColorEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8f4f0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_143Li1ENS_4ListIJN9HblmTypes21E_FocusPointResetModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x90040 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_144Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x904e8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_145Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x908a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_146Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x90f50 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_147Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x913f8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_148Li1ENS_4ListIJN9HblmTypes17E_CameraKeyOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91b88 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_150Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x923f0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_151Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x927d8 | 1000 |

<details><summary>… 另 110 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_152Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92bc0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_153Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92f80 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_154Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93340 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_155Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93700 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_156Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93ae8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_157Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93ed0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_158Li1ENS_4ListIJN9HblmTypes10E_IbisModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x945a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_159Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94d30 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x951d8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95680 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95a40 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96108 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x965b0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96d58 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97200 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x975c0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_169Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97980 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98028 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x987b8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98f48 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x993f0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x997d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99b90 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99f50 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a6f8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_179Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9aae0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_180Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9aec8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_181Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b2b0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_182Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b670 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_183Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ba50 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9be10 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c5b0 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9cd78 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_189Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d158 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_190Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d540 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_192Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9dce8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_193Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e0a8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_194Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e488 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_195Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e848 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_196Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ec30 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_197Li1ENS_4ListIJN9HblmTypes15E_LiveViewStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f300 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_198Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f7a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_199Li1ENS_4ListIJRK10QByteArrayEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9fb68 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_200Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ff28 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_201Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa02e8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_203Li1ENS_4ListIJN9HblmTypes23E_LiveviewTransportModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa0a88 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_204Li1ENS_4ListIJN9HblmTypes9E_LmModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa1150 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_205Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa15f8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_206Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa19b8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_207Li1ENS_4ListIJN9HblmTypes19E_ManualFocusAssistEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2088 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_208Li1ENS_4ListIJN9HblmTypes13E_MaxApertureEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2818 | 1192 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0xa2cc0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0xa2e40 | 200 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xa2f08 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xa2fa0 | 4 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_209Li1ENS_4ListIJN9HblmTypes15E_MultiShotModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2fa8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_210Li1ENS_4ListIJN9HblmTypes13E_FlashStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa3738 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_212Li1ENS_4ListIJN9HblmTypes16E_OptionOverrideEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa3fc8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_213Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa43a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_214Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa4768 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_215Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa4b28 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_216Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa4f10 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_217Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa52d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_218Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa5690 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_219Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa5b38 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_220Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa62c8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_221Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa6770 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_223Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa6f40 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_224Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa7300 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_225Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa76e8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_226Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa7aa8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_227Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa7e90 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_228Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8250 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_229Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa86f8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_230Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8ae0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_231Li1ENS_4ListIJN9HblmTypes14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8ea0 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_232Li1ENS_4ListIJN9HblmTypes16E_StopDownStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa9568 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_233Li1ENS_4ListIJN9HblmTypes13E_StreamGroupEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa9cf8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_234Li1ENS_4ListIJN9HblmTypes18E_SensorUnitStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaa488 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_238Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xab470 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_239Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xab850 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_242Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xac390 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_243Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xac750 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_245Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaced0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_246Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xad290 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_247Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xad670 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_248Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xada30 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_249Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaddf0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_251Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xae880 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_252Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaed28 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_253Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaf108 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_256Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xafc48 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_257Li1ENS_4ListIJN9HblmTypes12E_WhiteModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb02f0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_258Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb0798 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_259Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb0b58 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_260Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb0f18 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_261Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb15e8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_262Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb1a90 | 956 |
| `_ZN11CameraProxy35enabled_face_detection_modesChangedEN9HblmTypes15E_FaceDetectionE` | 0xbc230 | 96 |
| `_ZN11CameraProxy37exposures_in_multishot_sessionChangedEi` | 0xbc908 | 96 |
| `_ZN11CameraProxy27flash_recharge_delayChangedEi` | 0xbcc08 | 96 |
| `_ZN11CameraProxy29multishot_control_modeChangedEN9HblmTypes15E_MultiShotModeE` | 0xbe918 | 96 |
| `_ZN15CameraProxyDbus31setEnabled_face_detection_modesEN9HblmTypes15E_FaceDetectionE` | 0xd9d00 | 308 |
| `_ZN15CameraProxyDbus33setExposures_in_multishot_sessionEi` | 0xdaba0 | 308 |
| `_ZN15CameraProxyDbus23setFlash_recharge_delayEi` | 0xdb2f0 | 308 |
| `_ZN15CameraProxyDbus25setMultishot_control_modeEN9HblmTypes15E_MultiShotModeE` | 0xddd98 | 308 |
| `_ZNK15CameraProxyDbus28enabled_face_detection_modesEv` | 0xe0cd8 | 48 |
| `_ZNK15CameraProxyDbus30exposures_in_multishot_sessionEv` | 0xe1038 | 48 |
| `_ZNK15CameraProxyDbus20flash_recharge_delayEv` | 0xe11b8 | 48 |
| `_ZNK15CameraProxyDbus22multishot_control_modeEv` | 0xe2028 | 48 |

</details>

**Removed functions (132)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN15OdinDbSendUtils21convertStringToBitsetIN9HblmTypes16E_SessionOptionsELm5EEEbRK7QStringRT_` | 0x65158 | 1876 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_106Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x84718 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_107Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x84bc0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_108Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x84fa8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_110Li1ENS_4ListIJN9HblmTypes12E_DriveModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x85728 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_111Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x85bd0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_112Li1ENS_4ListIJN9HblmTypes9E_ExpModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86278 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_113Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86720 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_114Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86ae0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_115Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x86ec8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_116Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87570 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_117Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87a18 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_118Li1ENS_4ListIJN9HblmTypes21E_ExposureControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x87e00 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_119Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x882a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_120Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x88668 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_121Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x88a28 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_122Li1ENS_4ListIJN9HblmTypes16E_ExposureStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x88de8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_123Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x891c8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_124Li1ENS_4ListIJN9HblmTypes15E_FaceDetectionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x89870 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_125Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x89d18 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_126Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a100 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_127Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a4c0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_128Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8a880 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_129Li1ENS_4ListIJN9HblmTypes12E_FlashModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8af28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_131Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8b790 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_133Li1ENS_4ListIJN9HblmTypes26E_FocusBracketingStepSizesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8bf10 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_134Li1ENS_4ListIJN9HblmTypes27E_FocusBracketingStrategiesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8c6a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_135Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8cb48 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_136Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8cf08 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_137Li1ENS_4ListIJN9HblmTypes12E_FocusModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8d5b0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_138Li1ENS_4ListIJN9HblmTypes19E_FocusPeakingColorEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8dd40 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_139Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8e1e8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_140Li1ENS_4ListIJN9HblmTypes21E_FocusPointResetModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8e890 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_141Li1ENS_4ListIJRK4QMapIS2_8QVariantEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8ed38 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_143Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8f7a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_144Li1ENS_4ListIJN9HblmTypes11E_FocusSizeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8fc48 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_145Li1ENS_4ListIJN9HblmTypes17E_CameraKeyOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x903d8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_146Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x90880 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_147Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x90c40 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_148Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91028 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_150Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x917d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_151Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91b90 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_152Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x91f50 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_153Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92338 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_154Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92720 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_155Li1ENS_4ListIJN9HblmTypes10E_IbisModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x92df0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_156Li1ENS_4ListIJN9HblmTypes10E_BitDepthEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93580 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_157Li1ENS_4ListIJN9HblmTypes13E_ImageFormatEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93a28 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_158Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x93ed0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_159Li1ENS_4ListIJN9HblmTypes21E_ImagePostProcessingEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94290 | 988 |

<details><summary>… 另 82 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_160Li1ENS_4ListIJN9HblmTypes17E_IbisControlModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94958 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_161Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x94e00 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_162Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x951e8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_163Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x955a8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_164Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x95a50 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_166Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x961d0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_167Li1ENS_4ListIJN9HblmTypes13E_ResolutionsEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x96878 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_168Li1ENS_4ListIJN9HblmTypes19E_LensDriveEndpointEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97008 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_169Li1ENS_4ListIJN9HblmTypes17E_LensDriveStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97798 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_170Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x97c40 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_171Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98020 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_172Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x983e0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_173Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x987a0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_174Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98b60 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_175Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x98f48 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_176Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99330 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_178Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99b00 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_179Li1ENS_4ListIJN9HblmTypes17E_LensMfRingStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x99ec0 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_180Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a2a0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_181Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9a660 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_182Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9aa20 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_183Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ae00 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_184Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b1e0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_186Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9b9a8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_188Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c178 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_189Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c538 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_190Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9c8f8 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_192Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d098 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_193Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9d480 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_194Li1ENS_4ListIJN9HblmTypes15E_LiveViewStateEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9db50 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_195Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9dff8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_196Li1ENS_4ListIJRK10QByteArrayEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e3b8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_197Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9e778 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_198Li1ENS_4ListIJS4_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9eb38 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_199Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9ef18 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_200Li1ENS_4ListIJN9HblmTypes23E_LiveviewTransportModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f2d8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_201Li1ENS_4ListIJN9HblmTypes9E_LmModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x9f9a0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_203Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa0208 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_204Li1ENS_4ListIJN9HblmTypes19E_ManualFocusAssistEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa08d8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_205Li1ENS_4ListIJN9HblmTypes13E_MaxApertureEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa1068 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_206Li1ENS_4ListIJN9HblmTypes13E_FlashStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa17f8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_207Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa1ca0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_208Li1ENS_4ListIJN9HblmTypes16E_OptionOverrideEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2088 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_209Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2468 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_210Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2828 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_212Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa2fd0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_213Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa3390 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_214Li1ENS_4ListIJN9HblmTypes12E_ExitOptionEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa3750 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_215Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa3bf8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_216Li1ENS_4ListIJN9HblmTypes14E_SequenceModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa4388 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_217Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa4830 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_218Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa4c18 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_219Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa5000 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_220Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa53c0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_221Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa57a8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_223Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa5f50 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_224Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa6310 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_225Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa67b8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_226Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa6ba0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_227Li1ENS_4ListIJN9HblmTypes14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa6f60 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_228Li1ENS_4ListIJN9HblmTypes16E_StopDownStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa7628 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_229Li1ENS_4ListIJN9HblmTypes13E_StreamGroupEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa7db8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_230Li1ENS_4ListIJN9HblmTypes18E_SensorUnitStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8548 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_231Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa89f0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_232Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8db0 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_233Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa9170 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_234Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa9530 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_238Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaa450 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_239Li1ENS_4ListIJyEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaa810 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_242Li1ENS_4ListIJRK5QListIiEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xab350 | 992 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_243Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xab730 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_245Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xabeb0 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_246Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xac298 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_247Li1ENS_4ListIJN9HblmTypes14E_DistanceUnitEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xac940 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_248Li1ENS_4ListIJN9HblmTypes10E_CropModeEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xacde8 | 988 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_249Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xad1c8 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_251Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xad948 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_252Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xadd08 | 956 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_253Li1ENS_4ListIJN9HblmTypes12E_WhiteModesEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xae3b0 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_256Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaefd8 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_257Li1ENS_4ListIJN9HblmTypes11E_ZoomLevelEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xaf6a8 | 1192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN18CameraProxyWrapper24registerSignalSubscriberERK7QStringE5$_258Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xafb50 | 956 |

</details>

**New objects (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x152605 | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_NS3_IS2L_S3S_EES3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x199bc8 | 6400 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x1a1e88 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x1a5468 | 4 |

**Removed objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1M_NS3_IyS6_EESD_S1N_NS3_INS8_16E_ExposureStatusES6_EESD_NS3_INS8_15E_FaceDetectionES6_EES7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1I_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S37_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1N_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3Q_EES3R_NS3_IKNS8_21E_ExposureBlockReasonES3Q_EES3R_NS3_IKNS8_21E_LiveviewBlockReasonES3Q_EES3R_NS3_IbS3Q_EES3R_S41_S3R_S41_S3R_NS3_IS9_S3Q_EES3R_NS3_ISB_S3Q_EES3R_NS3_IiS3Q_EES3R_S41_S3R_NS3_IRKSH_S3Q_EES3R_NS3_ISJ_S3Q_EES3R_NS3_ISL_S3Q_EES3R_NS3_ItS3Q_EES3R_NS3_IPKSO_S3Q_EES3R_S41_S3R_S41_S3R_NS3_ISR_S3Q_EES3R_S44_S3R_NS3_IRKSU_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S41_S3R_S41_S3R_NS3_ISW_S3Q_EES3R_S44_S3R_NS3_ISY_S3Q_EES3R_S44_S3R_S44_S3R_NS3_IjS3Q_EES3R_NS3_IS11_S3Q_EES3R_NS3_IS13_S3Q_EES3R_NS3_IS15_S3Q_EES3R_S41_S3R_S4N_S3R_S41_S3R_S41_S3R_NS3_IS17_S3Q_EES3R_NS3_IS19_S3Q_EES3R_NS3_IS1B_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S41_S3R_NS3_IS1D_S3Q_EES3R_NS3_IS1F_S3Q_EES3R_S41_S3R_S4Q_S3R_NS3_IS1H_S3Q_EES3R_S41_S3R_S44_S3R_S44_S3R_S4S_S3R_S44_S3R_NS3_IS1J_S3Q_EES3R_S4K_S3R_S41_S3R_S44_S3R_NS3_IS1L_S3Q_EES3R_S41_S3R_S4V_S3R_NS3_IyS3Q_EES3R_S44_S3R_S4W_S3R_NS3_IS1O_S3Q_EES3R_S44_S3R_NS3_IS1Q_S3Q_EES3R_S41_S3R_S47_S3R_S44_S3R_S44_S3R_NS3_IS1S_S3Q_EES3R_S44_S3R_S44_S3R_S44_S3R_S4O_S3R_NS3_IS1U_S3Q_EES3R_S47_S3R_S47_S3R_NS3_IS1W_S3Q_EES3R_NS3_IS1Y_S3Q_EES3R_S4K_S3R_NS3_IS20_S3Q_EES3R_S47_S3R_S4K_S3R_NS3_IS22_S3Q_EES3R_S54_S3R_NS3_IS24_S3Q_EES3R_S44_S3R_S41_S3R_S41_S3R_S44_S3R_S44_S3R_S44_S3R_S41_S3R_S41_S3R_S41_S3R_NS3_IS26_S3Q_EES3R_NS3_IS28_S3Q_EES3R_S4T_S3R_S44_S3R_NS3_IS2A_S3Q_EES3R_NS3_IS2C_S3Q_EES3R_S41_S3R_S44_S3R_S4J_S3R_S44_S3R_S44_S3R_S4K_S3R_NS3_IS2E_S3Q_EES3R_NS3_IS2G_S3Q_EES3R_NS3_IS2I_S3Q_EES3R_NS3_IRKSF_S3Q_EES3R_S4A_S3R_S4K_S3R_S4K_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S44_S3R_NS3_IS2L_S3Q_EES3R_S4A_S3R_S4K_S3R_S5F_S3R_S5F_S3R_S41_S3R_S5F_S3R_S41_S3R_S41_S3R_S44_S3R_S44_S3R_S5F_S3R_S44_S3R_S41_S3R_S41_S3R_NS3_IS2N_S3Q_EES3R_S4K_S3R_NS3_IRKS2P_S3Q_EES3R_S44_S3R_S5F_S3R_S4K_S3R_NS3_IS2R_S3Q_EES3R_NS3_IS2T_S3Q_EES3R_S4K_S3R_S41_S3R_NS3_IS2V_S3Q_EES3R_NS3_IS2X_S3Q_EES3R_NS3_IS2Z_S3Q_EES3R_S41_S3R_NS3_IS31_S3Q_EES3R_S4K_S3R_S44_S3R_S41_S3R_S4K_S3R_S44_S3R_S4J_S3R_NS3_IS33_S3Q_EES3R_NS3_IS35_S3Q_EES3R_S41_S3R_S41_S3R_S44_S3R_S41_S3R_S4A_S3R_S41_S3R_NS3_IsS3Q_EES3R_NS3_IS38_S3Q_EES3R_S41_S3R_S5T_S3R_NS3_IS3A_S3Q_EES3R_NS3_IS3C_S3Q_EES3R_NS3_IS3E_S3Q_EES3R_NS3_IS3G_S3Q_EES3R_S44_S3R_S44_S3R_S44_S3R_S4H_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S4W_S3R_S44_S3R_S44_S3R_S4H_S3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_NS3_IS3I_S3Q_EES3R_S4Q_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_NS3_IS3K_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_NS3_IS3M_S3Q_EES3R_S4K_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_EE` | 0x199cd0 | 6304 |

### `/bin/camera-system`

+78 / −54 functions · +8 / −3 objects

**New functions (78)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN13SystemMonitor20batteryStatusChangedEN9HblmTypes15E_BatteryStatusE` | 0x66690 | 96 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x69fa0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x69fb0 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x69fb8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x69fb8 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x69fc8 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x69fe0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x6a090 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x6a0a0 | 12 |
| `_ZNK16SystemObjectImpl14battery_statusEv` | 0x7d020 | 12 |
| `_ZN9QtPrivate11QSlotObjectIM12SystemObjectFvN9HblmTypes15E_BatteryStatusEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x80990 | 124 |
| `_ZN18SystemStateMachine31onTetheredCaptureClientsChangedEN9HblmTypes7E_HostsE` | 0x97d70 | 312 |
| `_ZN8HblState12connectEventI17StateUsbConnectedN11SystemEvent9EventTypeEMS1_FvP6QEventEEEN11QMetaObject10ConnectionEPKT_T1_PKcT0_RK8QVariant` | 0xa1570 | 312 |
| `_ZN17StateUsbConnected20onMassStorageAllowedEP6QEvent` | 0xa16a8 | 612 |
| `_ZN9QtPrivate11QSlotObjectIM17StateUsbConnectedFvP6QEventENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8f60 | 124 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN20StateSuspendWaitIdleC1EP6QStateE3$_1Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa9750 | 632 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN20StateSuspendWaitIdle10onHblEntryEP6QEventE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa9a48 | 192 |
| `_ZN18TouchScreenHandler17updateDeviceReadyEv` | 0xc6bb0 | 388 |
| `_ZN9DussEvent6handleEv` | 0xde540 | 64 |
| `_ZN12SystemObject21battery_statusChangedEN9HblmTypes15E_BatteryStatusE` | 0xf3fa8 | 96 |
| `_ZN11PhocusProxy31tethered_capture_clientsChangedEN9HblmTypes7E_HostsE` | 0xf7370 | 96 |
| `_ZNK15PhocusProxyDbus24tethered_capture_clientsEv` | 0x10aa78 | 48 |
| `_ZNK12SystemObject15_battery_statusEv` | 0x115790 | 32 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE3$_7Li1ENS_4ListIJN9HblmTypes15E_BatteryStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1167a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_11Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116860 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_12Li1ENS_4ListIJN9HblmTypes16E_BtAssistStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116890 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_13Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1168c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_14Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1168f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_15Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116920 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_16Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116950 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_17Li1ENS_4ListIJ5QListI4QMapI7QString8QVariantEEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116980 | 388 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_19Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116b38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_20Li1ENS_4ListIJN9HblmTypes13E_DebugOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116b68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_24Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116c28 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_26Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116c88 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_28Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116ce8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_30Li1ENS_4ListIJN9HblmTypes20E_EyesensorDistancesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116d48 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_32Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116da8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_34Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116e08 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_35Li1ENS_4ListIJN9HblmTypes17E_MaintenanceTypeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116e38 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_36Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116e68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_40Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116f28 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_41Li1ENS_4ListIJN9HblmTypes10E_ProfilesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116f58 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_42Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116f88 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_43Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116fb8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_45Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117018 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_46Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117048 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_48Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1170a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_51Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117138 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_53Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117198 | 44 |

<details><summary>… 另 28 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_54Li1ENS_4ListIJN9HblmTypes14E_ScreenStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1171c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_58Li1ENS_4ListIJN9HblmTypes9E_ScreensEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117288 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_60Li1ENS_4ListIJN9HblmTypes15E_SoundSettingsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1172e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_61Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117318 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_62Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117348 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_63Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117378 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_65Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1173d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_66Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117408 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_67Li1ENS_4ListIJN9HblmTypes21E_SuspendWakeupSourceEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117438 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_70Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1174c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_71Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1174f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_72Li1ENS_4ListIJN9HblmTypes13E_SystemStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117528 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_73Li1ENS_4ListIJN9HblmTypes19E_TemperatureStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117558 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_74Li1ENS_4ListIJN9HblmTypes14E_TetheredModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117588 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_76Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1175e8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_78Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117648 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_79Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117678 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_83Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117738 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_85Li1ENS_4ListIJN9HblmTypes10E_WifiModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117798 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_86Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1177c8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_87Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1177f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_88Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x117828 | 44 |
| `_ZNK7Version14hblProductInfo7hasCpldEv` | 0x11a5a8 | 164 |
| `_ZL11parseStringmPKhmmR7QString` | 0x29aad0 | 536 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x2c7ca8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x2c7d40 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x2c7d48 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x2c7ec8 | 200 |

</details>

**Removed functions (54)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN18SystemStateMachine22onConnectedHostChangedEN9HblmTypes7E_HostsE` | 0x97778 | 316 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN17StateUsbConnectedC1EP6QStateE3$_1Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa8780 | 364 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN17StateUsbConnectedC1EP6QStateE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa88f0 | 392 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN20StateSuspendWaitIdleC1EP6QStateE3$_3Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa91e8 | 632 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN20StateSuspendWaitIdle10onHblEntryEP6QEventE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xa94e0 | 192 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE3$_7Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1157b8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_11Li1ENS_4ListIJN9HblmTypes16E_BtAssistStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115878 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_12Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1158a8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_13Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1158d8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_14Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115908 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_15Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115938 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_16Li1ENS_4ListIJ5QListI4QMapI7QString8QVariantEEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115968 | 388 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_17Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115af0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_19Li1ENS_4ListIJN9HblmTypes13E_DebugOptionEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115b50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_20Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115b80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_24Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115c40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_26Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115ca0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_28Li1ENS_4ListIJN9HblmTypes20E_EyesensorDistancesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115d00 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_30Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115d60 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_32Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115dc0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_34Li1ENS_4ListIJN9HblmTypes17E_MaintenanceTypeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115e20 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_35Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115e50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_36Li1ENS_4ListIJtEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115e80 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_40Li1ENS_4ListIJN9HblmTypes10E_ProfilesEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115f40 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_41Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115f70 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_42Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115fa0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_43Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x115fd0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_45Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116030 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_46Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116060 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_48Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1160c0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_51Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116150 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_53Li1ENS_4ListIJN9HblmTypes14E_ScreenStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1161b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_54Li1ENS_4ListIJN9HblmTypes9E_ScreensEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1161e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_58Li1ENS_4ListIJN9HblmTypes15E_SoundSettingsEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1162a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_60Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116300 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_61Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116330 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_62Li1ENS_4ListIJN9HblmTypes24E_SpiritLevelOrientationEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116360 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_63Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116390 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_65Li1ENS_4ListIJsEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1163f0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_66Li1ENS_4ListIJN9HblmTypes21E_SuspendWakeupSourceEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116420 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_67Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116450 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_70Li1ENS_4ListIJN9HblmTypes12E_SoundLevelEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1164e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_71Li1ENS_4ListIJN9HblmTypes13E_SystemStateEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116510 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_72Li1ENS_4ListIJN9HblmTypes19E_TemperatureStatusEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116540 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_73Li1ENS_4ListIJN9HblmTypes14E_TetheredModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116570 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_74Li1ENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1165a0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_76Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116600 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_78Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116660 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_79Li1ENS_4ListIJiEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116690 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_83Li1ENS_4ListIJN9HblmTypes10E_WifiModeEEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116750 | 44 |

<details><summary>… 另 4 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_85Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1167b0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_86Li1ENS_4ListIJbEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x1167e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN12SystemObjectC1EP7QObjectE4$_87Li1ENS_4ListIJRK7QStringEEEvE4implEiPNS_15QSlotObjectBaseES3_PPvPb` | 0x116810 | 44 |
| `_ZL11parseStringmPhmmR7QString` | 0x299a10 | 536 |

</details>

**New objects (8)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x481f3b | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_134qt_meta_stringdata_SystemMonitor_tEJN9QtPrivate20TypeAndForceCompleteI13SystemMonitorNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IN9HblmTypes11E_ErrorCodeES9_EENS3_INSB_15E_ErrorCategoryES9_EENS3_INSB_13E_ErrorActionES9_EESA_SD_SA_NS3_INSB_19E_TemperatureStatusES9_EESA_NS3_INSB_15E_BatteryStatusES9_EESA_NS3_INSB_13E_SystemStateES9_EESA_SD_SA_NS3_INSB_21E_SuspendWakeupSourceES9_EESA_SA_SJ_EE` | 0x559648 | 168 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_SystemObject_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EES8_NS3_I7QStringS6_EESB_SB_SB_S8_SB_S9_S8_S9_NS3_I5QListI4QMapISA_8QVariantEES6_EES9_S8_S8_S8_S9_S7_S8_S8_NS3_ItS6_EES8_S9_SI_SI_S8_S9_SB_S7_S9_S7_S9_S9_S8_S8_S8_S8_S8_S8_S9_NS3_IsS6_EES8_S9_SJ_S8_S8_S8_S8_S8_S8_S8_S7_S9_S9_SB_S8_S8_S8_SB_S9_SB_NS3_I12SystemObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKxSM_EESN_NS3_IKjSM_EESN_NS3_IKiSM_EESN_ST_SN_NS3_IKbSM_EESN_NS3_IKN9HblmTypes15E_BatteryStatusESM_EESN_NS3_IRKSA_SM_EESN_S12_SN_S12_SN_S12_SN_NS3_IKNSW_16E_BtAssistStatusESM_EESN_S12_SN_SV_SN_ST_SN_SV_SN_NS3_IKSG_SM_EESN_SV_SN_NS3_IKNSW_13E_DebugOptionESM_EESN_ST_SN_ST_SN_SV_SN_SR_SN_NS3_IKNSW_20E_EyesensorDistancesESM_EESN_ST_SN_NS3_IKtSM_EESN_NS3_IKNSW_17E_MaintenanceTypeESM_EESN_SV_SN_S1F_SN_S1F_SN_NS3_IKNSW_10E_ProfilesESM_EESN_SV_SN_S12_SN_SR_SN_SV_SN_SR_SN_SV_SN_SV_SN_ST_SN_NS3_IKNSW_14E_ScreenStatusESM_EESN_NS3_IKNSW_9E_ScreensESM_EESN_S1R_SN_S1R_SN_NS3_IKNSW_15E_SoundSettingsESM_EESN_SV_SN_NS3_IKsSM_EESN_NS3_IKNSW_24E_SpiritLevelOrientationESM_EESN_SV_SN_S1W_SN_NS3_IKNSW_21E_SuspendWakeupSourceESM_EESN_ST_SN_ST_SN_NS3_IKNSW_12E_SoundLevelESM_EESN_NS3_IKNSW_13E_SystemStateESM_EESN_NS3_IKNSW_19E_TemperatureStatusESM_EESN_NS3_IKNSW_14E_TetheredModeESM_EESN_SR_SN_SV_SN_SV_SN_S12_SN_ST_SN_ST_SN_NS3_IKNSW_10E_WifiModeESM_EESN_S12_SN_SV_SN_S12_SN_SP_SN_S12_NS3_IRK12QDBusMessageSM_EESN_SV_S2L_SN_S2L_SN_S2L_SN_ST_S2L_SN_ST_SV_S2L_SN_SP_ST_S2L_NS3_IiSM_EES2L_SN_S2L_SN_S12_S2L_SN_S2L_NS3_ISF_SM_EES2L_NS3_IbSM_EES12_S2L_SN_SV_S2L_SN_S2L_SN_ST_S2L_SN_ST_S2L_SN_SV_S2L_SN_ST_S2L_SN_ST_S2L_SN_S2L_EE` | 0x55fa10 | 2032 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEES9_NS3_IbS8_EENS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SD_EESE_SF_EE` | 0x560508 | 64 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x5796b0 | 112 |
| `_ZN12_GLOBAL__N_116kNodeIdCfvGoodixE` | 0x57d660 | 24 |
| `_ZN12_GLOBAL__N_119kNodeIdCfvFocaltechE` | 0x57d680 | 24 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x580190 | 4 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_134qt_meta_stringdata_SystemMonitor_tEJN9QtPrivate20TypeAndForceCompleteI13SystemMonitorNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEESA_NS3_IN9HblmTypes11E_ErrorCodeES9_EENS3_INSB_15E_ErrorCategoryES9_EENS3_INSB_13E_ErrorActionES9_EESA_SD_SA_NS3_INSB_19E_TemperatureStatusES9_EESA_NS3_INSB_13E_SystemStateES9_EESA_SD_SA_NS3_INSB_21E_SuspendWakeupSourceES9_EESA_SA_SJ_EE` | 0x5596d0 | 152 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_133qt_meta_stringdata_SystemObject_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_I7QStringS6_EESB_SB_SB_S8_SB_S9_S8_S9_NS3_I5QListI4QMapISA_8QVariantEES6_EES9_S8_S8_S8_S9_S7_S8_S8_NS3_ItS6_EES8_S9_SI_SI_S8_S9_SB_S7_S9_S7_S9_S9_S8_S8_S8_S8_S8_S8_S9_NS3_IsS6_EES8_S9_SJ_S8_S8_S8_S8_S8_S8_S8_S7_S9_S9_SB_S8_S8_S8_SB_S9_SB_NS3_I12SystemObjectS6_EENS3_IvNS5_IbLb0EEEEENS3_IKxSM_EESN_NS3_IKjSM_EESN_NS3_IKiSM_EESN_ST_SN_NS3_IKbSM_EESN_NS3_IRKSA_SM_EESN_SY_SN_SY_SN_SY_SN_NS3_IKN9HblmTypes16E_BtAssistStatusESM_EESN_SY_SN_SV_SN_ST_SN_SV_SN_NS3_IKSG_SM_EESN_SV_SN_NS3_IKNSZ_13E_DebugOptionESM_EESN_ST_SN_ST_SN_SV_SN_SR_SN_NS3_IKNSZ_20E_EyesensorDistancesESM_EESN_ST_SN_NS3_IKtSM_EESN_NS3_IKNSZ_17E_MaintenanceTypeESM_EESN_SV_SN_S1C_SN_S1C_SN_NS3_IKNSZ_10E_ProfilesESM_EESN_SV_SN_SY_SN_SR_SN_SV_SN_SR_SN_SV_SN_SV_SN_ST_SN_NS3_IKNSZ_14E_ScreenStatusESM_EESN_NS3_IKNSZ_9E_ScreensESM_EESN_S1O_SN_S1O_SN_NS3_IKNSZ_15E_SoundSettingsESM_EESN_SV_SN_NS3_IKsSM_EESN_NS3_IKNSZ_24E_SpiritLevelOrientationESM_EESN_SV_SN_S1T_SN_NS3_IKNSZ_21E_SuspendWakeupSourceESM_EESN_ST_SN_ST_SN_NS3_IKNSZ_12E_SoundLevelESM_EESN_NS3_IKNSZ_13E_SystemStateESM_EESN_NS3_IKNSZ_19E_TemperatureStatusESM_EESN_NS3_IKNSZ_14E_TetheredModeESM_EESN_SR_SN_SV_SN_SV_SN_SY_SN_ST_SN_ST_SN_NS3_IKNSZ_10E_WifiModeESM_EESN_SY_SN_SV_SN_SY_SN_SP_SN_SY_NS3_IRK12QDBusMessageSM_EESN_SV_S2I_SN_S2I_SN_S2I_SN_ST_S2I_SN_ST_SV_S2I_SN_SP_ST_S2I_NS3_IiSM_EES2I_SN_S2I_SN_SY_S2I_SN_S2I_NS3_ISF_SM_EES2I_NS3_IbSM_EESY_S2I_SN_SV_S2I_SN_S2I_SN_ST_S2I_SN_ST_S2I_SN_SV_S2I_SN_ST_S2I_SN_ST_S2I_SN_S2I_EE` | 0x55fa80 | 2008 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEENS3_IbS8_EENS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SD_EEEE` | 0x560560 | 40 |

### `/bin/camera-storage`

+46 / −16 functions · +6 / −95 objects

**New functions (46)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x56dc8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x56dd8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x56de0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x56de0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x56df0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x56e08 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x56eb8 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x56ec8 | 12 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x592a0 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x592a0 | 452 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService6browseERK7QStringN9HblmTypes17E_MetadataOptionsERK14QSharedPointerI12DussMemShareERK12QDBusMessageE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8258 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doRemoveERK7QStringRK12QDBusMessageE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8e50 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doRemoveERK7QStringRK12QDBusMessageE3$_8Li1ENS_4ListIJN9HblmTypes14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8e80 | 1396 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doRemove_extendedERK5QListI7QStringERK12QDBusMessageE3$_9Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb96e0 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doRemove_extendedERK5QListI7QStringERK12QDBusMessageE4$_10Li1ENS_4ListIJN9HblmTypes14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9740 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9cd0 | 168 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_12Li1ENS_4ListIJNS2_14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9d78 | 184 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9e30 | 544 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceERK14QSharedPointerI19MessageNotificationEE4$_16Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xba120 | 132 |
| `_ZN15PhocusProxyDbus24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeE` | 0xceb48 | 404 |
| `_ZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeEiP7QObject` | 0xd7410 | 848 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeEiP7QObjectE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0xd7760 | 64 |
| `_ZN5QListI14QSharedPointerI16MetadataTopImageEE7replaceExRKS2_` | 0x114328 | 572 |
| `_ZN16MetadataTopImage15setLscCorrectedEb` | 0x127cc0 | 164 |
| `_ZN16MetadataTopImage21setMultiShotMakerDataEii` | 0x129ee0 | 216 |
| `_ZNK11MetadataIFD5valueINSt3__16vectorIiNS1_9allocatorIiEEEEEERT_N5MData9MdataTagsE` | 0x12a618 | 684 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x178d28 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x178dc0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x178dc8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x178f48 | 200 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringED2Ev` | 0x1918b0 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringED2Ev` | 0x1918b0 | 88 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x1931c8 | 108 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x1931c8 | 108 |
| `_ZN8CStorage16tagImageUniqueIdEv` | 0x194a38 | 92 |
| `_ZN8CStorage15tagCameraSerialEv` | 0x194af8 | 92 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringE6insertERKS1_RKS2_` | 0x195490 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage7MetaTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x195618 | 392 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x1957a0 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x1957a0 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x195898 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x195898 | 248 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringE6insertERKS1_RKS2_` | 0x195990 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage10StorageTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x195b18 | 392 |
| `_ZNK16SnapshotMetadata15multiShotImagesEv` | 0x19bb00 | 8 |
| `_ZNK16SnapshotMetadata17multiShotSequenceEv` | 0x19bb08 | 8 |

**Removed functions (16)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doRemoveERK7QStringRK12QDBusMessageE3$_6Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8d68 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doRemoveERK7QStringRK12QDBusMessageE3$_7Li1ENS_4ListIJN9HblmTypes14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb8d98 | 1396 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doRemove_extendedERK5QListI7QStringERK12QDBusMessageE3$_8Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb95f8 | 44 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService17doRemove_extendedERK5QListI7QStringERK12QDBusMessageE3$_9Li1ENS_4ListIJN9HblmTypes14E_ReturnStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9658 | 1000 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_10Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9be8 | 168 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_11Li1ENS_4ListIJNS2_14E_CameraStatusEEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9c90 | 184 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService8doFormatEN9HblmTypes15E_StorageDeviceERK12QDBusMessageE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9d48 | 544 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14StorageService12formatDeviceEN9HblmTypes15E_StorageDeviceERK14QSharedPointerI19MessageNotificationEE4$_13Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0xb9f68 | 164 |
| `_ZN15PhocusProxyDbus24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEj` | 0xcea28 | 404 |
| `_ZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiP7QObject` | 0xd72f0 | 804 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiP7QObjectE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES9_PPvPb` | 0xd7618 | 64 |
| `_ZN23MetadataIFDMakerNote3FR20setMultishotMetadataERKNSt3__16vectorIiNS0_9allocatorIiEEEE` | 0x11fe90 | 96 |
| `_ZN14MetadataTop3fr16setMultishotDataERKNSt3__16vectorIiNS0_9allocatorIiEEEE` | 0x1239d0 | 1196 |
| `_ZN18MetadataTopEncoded19setShadingCorrectedEi` | 0x12ef88 | 232 |
| `_ZNSt3__16vectorIjNS_9allocatorIjEEE6assignIPjEENS_9enable_ifIXaasr21__is_forward_iteratorIT_EE5valuesr16is_constructibleIjNS_15iterator_traitsIS7_E9referenceEEE5valueEvE4typeES7_S7_` | 0x12f0b0 | 336 |
| `_ZNK16SnapshotMetadata16shadingCorrectedEv` | 0x1990f8 | 8 |

**New objects (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x1de7d2 | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_PhocusProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15PhocusProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IK5QListI4QMapI7QString8QVariantEES9_EENS3_IKjS9_EENS3_IKN9HblmTypes10E_FileTypeES9_EEEE` | 0x23a690 | 40 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x2545f8 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x2584f0 | 4 |
| `_ZN12_GLOBAL__N_111kMetaTagMapE` | 0x2588c0 | 8 |
| `_ZN12_GLOBAL__N_114kStorageTagMapE` | 0x2588c8 | 8 |

**Removed objects (95)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_PhocusProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15PhocusProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IK5QListI4QMapI7QString8QVariantEES9_EENS3_IKjS9_EEEE` | 0x23a6b8 | 32 |
| `_ZL11TAG_MOUNTED` | 0x258840 | 24 |
| `_ZL8TAG_TYPE` | 0x258860 | 24 |
| `_ZL8TAG_NAME` | 0x258880 | 24 |
| `_ZL8TAG_UUID` | 0x2588a0 | 24 |
| `_ZL15TAG_EXPOSURE_ID` | 0x2588c0 | 24 |
| `_ZL8TAG_SIZE` | 0x2588e0 | 24 |
| `_ZL10TAG_OFFSET` | 0x258900 | 24 |
| `_ZL10TAG_HANDLE` | 0x258920 | 24 |
| `_ZL15TAG_DEVICE_TYPE` | 0x258940 | 24 |
| `_ZL13TAG_SIZECHILD` | 0x258960 | 24 |
| `_ZL13TAG_FULL_PATH` | 0x258980 | 24 |
| `_ZL16TAG_DISPLAY_PATH` | 0x2589a0 | 24 |
| `_ZL28TAG_DISPLAY_PATH_WITH_SUFFIX` | 0x2589c0 | 24 |
| `_ZL12TAG_METADATA` | 0x2589e0 | 24 |
| `_ZL15TAG_LORES_IMAGE` | 0x258a00 | 24 |
| `_ZL15TAG_THUMB_IMAGE` | 0x258a20 | 24 |
| `_ZL14TAG_TILE_IMAGE` | 0x258a40 | 24 |
| `_ZL14TAG_FREE_SPACE` | 0x258a60 | 24 |
| `_ZL16TAG_WRITEPROTECT` | 0x258a80 | 24 |
| `_ZL10TAG_STATUS` | 0x258aa0 | 24 |
| `_ZL6TAG_WP` | 0x258ac0 | 24 |
| `_ZL14TAG_SLOW_SPEED` | 0x258ae0 | 24 |
| `_ZL17TAG_AVERAGE_SPEED` | 0x258b00 | 24 |
| `_ZL13TAG_DATE_TIME` | 0x258b20 | 24 |
| `_ZL6TAG_SV` | 0x258b40 | 24 |
| `_ZL6TAG_AV` | 0x258b60 | 24 |
| `_ZL21TAG_FNUMBER_NUMERATOR` | 0x258b80 | 24 |
| `_ZL23TAG_FNUMBER_DENOMINATOR` | 0x258ba0 | 24 |
| `_ZL10TAG_AV_MIN` | 0x258bc0 | 24 |
| `_ZL6TAG_TV` | 0x258be0 | 24 |
| `_ZL13TAG_FOCAL_LEN` | 0x258c00 | 24 |
| `_ZL17TAG_EXPOSURE_MODE` | 0x258c20 | 24 |
| `_ZL27TAG_EXPOSURE_TIME_NUMERATOR` | 0x258c40 | 24 |
| `_ZL29TAG_EXPOSURE_TIME_DENOMINATOR` | 0x258c60 | 24 |
| `_ZL11TAG_LM_MODE` | 0x258c80 | 24 |
| `_ZL6TAG_WB` | 0x258ca0 | 24 |
| `_ZL10TAG_EV_ADJ` | 0x258cc0 | 24 |
| `_ZL17TAG_EXPOSURE_BIAS` | 0x258ce0 | 24 |
| `_ZL14TAG_LENS_SHIFT` | 0x258d00 | 24 |
| `_ZL16TAG_LENS_VERSION` | 0x258d20 | 24 |
| `_ZL27TAG_LENS_SHADING_CORRECTION` | 0x258d40 | 24 |
| `_ZL21TAG_LENS_FOCAL_MINMAX` | 0x258d60 | 24 |
| `_ZL13TAG_LENS_TYPE` | 0x258d80 | 24 |
| `_ZL13TAG_HISTOGRAM` | 0x258da0 | 24 |
| `_ZL16TAG_FS_TIMESTAMP` | 0x258dc0 | 24 |
| `_ZL8TAG_PATH` | 0x258de0 | 24 |
| `_ZL14TAG_PERSISTENT` | 0x258e00 | 24 |
| `_ZL15TAG_R_NUMERATOR` | 0x258e20 | 24 |
| `_ZL17TAG_R_DENOMINATOR` | 0x258e40 | 24 |

<details><summary>… 另 45 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZL15TAG_G_NUMERATOR` | 0x258e60 | 24 |
| `_ZL17TAG_G_DENOMINATOR` | 0x258e80 | 24 |
| `_ZL15TAG_B_NUMERATOR` | 0x258ea0 | 24 |
| `_ZL17TAG_B_DENOMINATOR` | 0x258ec0 | 24 |
| `_ZL22TAG_BLACK_LEVEL_OFFSET` | 0x258ee0 | 24 |
| `_ZL15TAG_WHITE_LEVEL` | 0x258f00 | 24 |
| `_ZL20TAG_SENSITIVITY_GAIN` | 0x258f20 | 24 |
| `_ZL18TAG_R_NEUTRAL_GAIN` | 0x258f40 | 24 |
| `_ZL18TAG_G_NEUTRAL_GAIN` | 0x258f60 | 24 |
| `_ZL18TAG_B_NEUTRAL_GAIN` | 0x258f80 | 24 |
| `_ZL21TAG_NEUTRAL_PRECISION` | 0x258fa0 | 24 |
| `_ZL16TAG_IMAGE_RATING` | 0x258fc0 | 24 |
| `_ZL18TAG_IMAGE_ROTATION` | 0x258fe0 | 24 |
| `_ZL15TAG_CAMERA_TYPE` | 0x259000 | 24 |
| `_ZL15TAG_FOCUS_POINT` | 0x259020 | 24 |
| `_ZL20TAG_SUBJECT_DISTANCE` | 0x259040 | 24 |
| `_ZL14TAG_LENS_MODEL` | 0x259060 | 24 |
| `_ZL13TAG_LENS_MAKE` | 0x259080 | 24 |
| `_ZL17TAG_FOCUS_SEGMENT` | 0x2590a0 | 24 |
| `_ZL17TAG_LENS_MODEL_ID` | 0x2590c0 | 24 |
| `_ZL9TAG_FILES` | 0x2590e0 | 24 |
| `_ZL14IMAGE_TAG_DATA` | 0x259100 | 24 |
| `_ZL16IMAGE_TAG_FORMAT` | 0x259120 | 24 |
| `_ZL15IMAGE_TAG_WIDTH` | 0x259140 | 24 |
| `_ZL16IMAGE_TAG_HEIGHT` | 0x259160 | 24 |
| `_ZL11IMAGE_TAG_X` | 0x259180 | 24 |
| `_ZL11IMAGE_TAG_Y` | 0x2591a0 | 24 |
| `_ZL19IMAGE_TAG_BUFFER_ID` | 0x2591c0 | 24 |
| `_ZL17IMAGE_FORMAT_RGBA` | 0x2591e0 | 24 |
| `_ZL17IMAGE_FORMAT_UYVY` | 0x259200 | 24 |
| `_ZL17IMAGE_FORMAT_NV12` | 0x259220 | 24 |
| `_ZL17IMAGE_FORMAT_422P` | 0x259240 | 24 |
| `_ZL17IMAGE_FORMAT_JPEG` | 0x259260 | 24 |
| `_ZL12STORAGE_ROOT` | 0x259280 | 24 |
| `_ZL13TETHERED_ROOT` | 0x2592a0 | 24 |
| `_ZL17STORAGE_MOUNT_SSD` | 0x2592c0 | 24 |
| `_ZL20STORAGE_MOUNT_CFCARD` | 0x2592e0 | 24 |
| `_ZL17HASBL_FOLDER_NAME` | 0x259300 | 24 |
| `_ZL9NAME_ROOT` | 0x259320 | 24 |
| `_ZL9NAME_DCIM` | 0x259340 | 24 |
| `_ZL11SOCKET_NAME` | 0x259360 | 24 |
| `_ZL11EXPOSURE_ID` | 0x259380 | 24 |
| `_ZL14DCAM_CONTAINER` | 0x2593a0 | 24 |
| `_ZL10FRAME_INFO` | 0x2593c0 | 24 |
| `_ZL18EXPOSURE_ITEM_TYPE` | 0x2593e0 | 24 |

</details>

### `/bin/camera-test`

+44 / −7 functions · +18 / −94 objects

**New functions (44)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x45498 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x454a8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x454b0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x454b0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x454c0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x454d8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x45588 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x45598 | 12 |
| `_ZNSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEE21__on_zero_shared_weakEv` | 0x4a068 | 4 |
| `_ZN11Calibration13lensInitDelayEv` | 0x78a88 | 272 |
| `_ZN11Calibration21writeZoomLiveviewJsonENSt3__14listI17HighContrastPixelNS0_9allocatorIS2_EEEERK5QSize` | 0x7d6e8 | 3116 |
| `_ZN11Calibration40doManualZoomLiveviewSpotPixelCalibrationER11sutest_body` | 0x7e318 | 7316 |
| `_ZZN11Calibration28doManualSpotPixelCalibrationER11sutest_bodyR5QListI7QStringEENK3$_7clERNSt3__14listI17HighContrastPixelNS7_9allocatorIS9_EEEE` | 0x835b0 | 1168 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZL18startOrExitSessionbE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8d948 | 76 |
| `_ZNSt3__14listI17HighContrastPixelNS_9allocatorIS1_EEE6__sortIZZN11Calibration28doManualSpotPixelCalibrationER11sutest_bodyR5QListI7QStringEENK3$_7clERS4_EUlRKS1_SG_E_EENS_15__list_iteratorIS1_PvEESK_SK_mRT_` | 0x8d998 | 528 |
| `_ZNSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEED0Ev` | 0x8dc38 | 36 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x8e2e8 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x8e2e8 | 452 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11Calibration13lensInitDelayEvE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8eb58 | 40 |
| `_ZNSt3__14listI17HighContrastPixelNS_9allocatorIS1_EEE6__sortIZN11Calibration7executeEvE4$_10EENS_15__list_iteratorIS1_PvEESA_SA_mRT_` | 0x8f830 | 620 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11Calibration14sendDataToHostERKNSt3__110shared_ptrI11MemoryBlockEEmR7QStringE4$_11Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8faa0 | 324 |
| `_ZL14createInfoRootR11QJsonObjectRK7QStringjjj` | 0xbf9b0 | 1980 |
| `_ZL11writeToFileRK13QJsonDocumentRK7QString` | 0xc0170 | 1052 |
| `_ZN12CalibJsonGen12generateZoomERK7QStringS2_jjjiiRKNSt3__14listINS_13ContrastPixelENS3_9allocatorIS5_EEEE` | 0xc0590 | 1744 |
| `_ZN13CalibSbpcZoom18writeZoomBinToDiskERK7QStringRKNSt3__110shared_ptrI20ZoomLiveviewSbpcDataEE` | 0xc0c60 | 916 |
| `_ZN13CalibSbpcZoom20ZoomSbpcListToBinaryERKNSt3__14listI17HighContrastPixelNS0_9allocatorIS2_EEEE` | 0xc0ff8 | 1680 |
| `_ZNSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEE16__on_zero_sharedEv` | 0xc1688 | 16 |
| `_ZNKSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEE13__get_deleterERKSt9type_info` | 0xc1698 | 28 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringED2Ev` | 0xeb5b0 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringED2Ev` | 0xeb5b0 | 88 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0xeb618 | 108 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0xeb618 | 108 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringE6insertERKS1_RKS2_` | 0xebed0 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage7MetaTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0xec058 | 392 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0xec1e0 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0xec1e0 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0xec2d8 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0xec2d8 | 248 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringE6insertERKS1_RKS2_` | 0xec3d0 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage10StorageTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0xec558 | 392 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x11ba70 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x11bb08 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x11bb10 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x11bc90 | 200 |

**Removed functions (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11Calibration28doManualSpotPixelCalibrationER11sutest_bodyR5QListI7QStringEENK3$_8clERNSt3__14listI17HighContrastPixelNS7_9allocatorIS9_EEEE` | 0x80910 | 1168 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZL18startOrExitSessionbE3$_2Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8abf8 | 76 |
| `_ZNSt3__14listI17HighContrastPixelNS_9allocatorIS1_EEE6__sortIZZN11Calibration28doManualSpotPixelCalibrationER11sutest_bodyR5QListI7QStringEENK3$_8clERS4_EUlRKS1_SG_E_EENS_15__list_iteratorIS1_PvEESK_SK_mRT_` | 0x8ac98 | 528 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11Calibration29doStillSpotpixelRecalibrationER11sutest_bodyE3$_4Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8be58 | 40 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11Calibration28doManualSpotPixelCalibrationER11sutest_bodyR5QListI7QStringEE3$_7Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8c140 | 40 |
| `_ZNSt3__14listI17HighContrastPixelNS_9allocatorIS1_EEE6__sortIZN11Calibration7executeEvE4$_11EENS_15__list_iteratorIS1_PvEESA_SA_mRT_` | 0x8cb58 | 620 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN11Calibration14sendDataToHostERKNSt3__110shared_ptrI11MemoryBlockEEmR7QStringE4$_12Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x8cdc8 | 324 |

**New objects (18)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTSNSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE` | 0x14baf0 | 100 |
| `_ZTSNSt3__114default_deleteI20ZoomLiveviewSbpcDataEE` | 0x14bb54 | 49 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x15fba8 | 27 |
| `_ZTVNSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE` | 0x1a9e10 | 56 |
| `_ZTINSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE` | 0x1a9e48 | 24 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x1b4f90 | 112 |
| `_ZN12_GLOBAL__N_121kTagSbpcCalibInfoRootE` | 0x1b7a00 | 24 |
| `_ZN12_GLOBAL__N_130kTagSbpcCalibInfoSensorModeNumE` | 0x1b7a40 | 24 |
| `_ZN12_GLOBAL__N_121kTagSbpcCalibInfoUnitE` | 0x1b7a60 | 24 |
| `_ZN12_GLOBAL__N_122kTagSbpcCalibUnitValidE` | 0x1b7a80 | 24 |
| `_ZN12_GLOBAL__N_127kTagSbpcCalibUnitSensorModeE` | 0x1b7aa0 | 24 |
| `_ZN12_GLOBAL__N_125kTagSbpcCalibUnitRawWidthE` | 0x1b7ac0 | 24 |
| `_ZN12_GLOBAL__N_126kTagSbpcCalibUnitRawHeightE` | 0x1b7ae0 | 24 |
| `_ZN12_GLOBAL__N_128kTagSbpcCalibUnitMapArrayLenE` | 0x1b7b00 | 24 |
| `_ZN12_GLOBAL__N_126kTagSbpcCalibUnitMapObjectE` | 0x1b7b20 | 24 |
| `_ZN12_GLOBAL__N_111kMetaTagMapE` | 0x1b7d10 | 8 |
| `_ZN12_GLOBAL__N_114kStorageTagMapE` | 0x1b7d18 | 8 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x1b8398 | 4 |

**Removed objects (94)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZL11TAG_MOUNTED` | 0x1b7b80 | 24 |
| `_ZL8TAG_TYPE` | 0x1b7ba0 | 24 |
| `_ZL8TAG_NAME` | 0x1b7bc0 | 24 |
| `_ZL8TAG_UUID` | 0x1b7be0 | 24 |
| `_ZL15TAG_EXPOSURE_ID` | 0x1b7c00 | 24 |
| `_ZL8TAG_SIZE` | 0x1b7c20 | 24 |
| `_ZL10TAG_OFFSET` | 0x1b7c40 | 24 |
| `_ZL10TAG_HANDLE` | 0x1b7c60 | 24 |
| `_ZL15TAG_DEVICE_TYPE` | 0x1b7c80 | 24 |
| `_ZL13TAG_SIZECHILD` | 0x1b7ca0 | 24 |
| `_ZL13TAG_FULL_PATH` | 0x1b7cc0 | 24 |
| `_ZL16TAG_DISPLAY_PATH` | 0x1b7ce0 | 24 |
| `_ZL28TAG_DISPLAY_PATH_WITH_SUFFIX` | 0x1b7d00 | 24 |
| `_ZL12TAG_METADATA` | 0x1b7d20 | 24 |
| `_ZL15TAG_LORES_IMAGE` | 0x1b7d40 | 24 |
| `_ZL15TAG_THUMB_IMAGE` | 0x1b7d60 | 24 |
| `_ZL14TAG_TILE_IMAGE` | 0x1b7d80 | 24 |
| `_ZL14TAG_FREE_SPACE` | 0x1b7da0 | 24 |
| `_ZL16TAG_WRITEPROTECT` | 0x1b7dc0 | 24 |
| `_ZL10TAG_STATUS` | 0x1b7de0 | 24 |
| `_ZL6TAG_WP` | 0x1b7e00 | 24 |
| `_ZL14TAG_SLOW_SPEED` | 0x1b7e20 | 24 |
| `_ZL17TAG_AVERAGE_SPEED` | 0x1b7e40 | 24 |
| `_ZL13TAG_DATE_TIME` | 0x1b7e60 | 24 |
| `_ZL6TAG_SV` | 0x1b7e80 | 24 |
| `_ZL6TAG_AV` | 0x1b7ea0 | 24 |
| `_ZL21TAG_FNUMBER_NUMERATOR` | 0x1b7ec0 | 24 |
| `_ZL23TAG_FNUMBER_DENOMINATOR` | 0x1b7ee0 | 24 |
| `_ZL10TAG_AV_MIN` | 0x1b7f00 | 24 |
| `_ZL6TAG_TV` | 0x1b7f20 | 24 |
| `_ZL13TAG_FOCAL_LEN` | 0x1b7f40 | 24 |
| `_ZL17TAG_EXPOSURE_MODE` | 0x1b7f60 | 24 |
| `_ZL27TAG_EXPOSURE_TIME_NUMERATOR` | 0x1b7f80 | 24 |
| `_ZL29TAG_EXPOSURE_TIME_DENOMINATOR` | 0x1b7fa0 | 24 |
| `_ZL11TAG_LM_MODE` | 0x1b7fc0 | 24 |
| `_ZL6TAG_WB` | 0x1b7fe0 | 24 |
| `_ZL10TAG_EV_ADJ` | 0x1b8000 | 24 |
| `_ZL17TAG_EXPOSURE_BIAS` | 0x1b8020 | 24 |
| `_ZL14TAG_LENS_SHIFT` | 0x1b8040 | 24 |
| `_ZL16TAG_LENS_VERSION` | 0x1b8060 | 24 |
| `_ZL27TAG_LENS_SHADING_CORRECTION` | 0x1b8080 | 24 |
| `_ZL21TAG_LENS_FOCAL_MINMAX` | 0x1b80a0 | 24 |
| `_ZL13TAG_LENS_TYPE` | 0x1b80c0 | 24 |
| `_ZL13TAG_HISTOGRAM` | 0x1b80e0 | 24 |
| `_ZL16TAG_FS_TIMESTAMP` | 0x1b8100 | 24 |
| `_ZL8TAG_PATH` | 0x1b8120 | 24 |
| `_ZL14TAG_PERSISTENT` | 0x1b8140 | 24 |
| `_ZL15TAG_R_NUMERATOR` | 0x1b8160 | 24 |
| `_ZL17TAG_R_DENOMINATOR` | 0x1b8180 | 24 |
| `_ZL15TAG_G_NUMERATOR` | 0x1b81a0 | 24 |

<details><summary>… 另 44 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZL17TAG_G_DENOMINATOR` | 0x1b81c0 | 24 |
| `_ZL15TAG_B_NUMERATOR` | 0x1b81e0 | 24 |
| `_ZL17TAG_B_DENOMINATOR` | 0x1b8200 | 24 |
| `_ZL22TAG_BLACK_LEVEL_OFFSET` | 0x1b8220 | 24 |
| `_ZL15TAG_WHITE_LEVEL` | 0x1b8240 | 24 |
| `_ZL20TAG_SENSITIVITY_GAIN` | 0x1b8260 | 24 |
| `_ZL18TAG_R_NEUTRAL_GAIN` | 0x1b8280 | 24 |
| `_ZL18TAG_G_NEUTRAL_GAIN` | 0x1b82a0 | 24 |
| `_ZL18TAG_B_NEUTRAL_GAIN` | 0x1b82c0 | 24 |
| `_ZL21TAG_NEUTRAL_PRECISION` | 0x1b82e0 | 24 |
| `_ZL16TAG_IMAGE_RATING` | 0x1b8300 | 24 |
| `_ZL18TAG_IMAGE_ROTATION` | 0x1b8320 | 24 |
| `_ZL15TAG_CAMERA_TYPE` | 0x1b8340 | 24 |
| `_ZL15TAG_FOCUS_POINT` | 0x1b8360 | 24 |
| `_ZL20TAG_SUBJECT_DISTANCE` | 0x1b8380 | 24 |
| `_ZL14TAG_LENS_MODEL` | 0x1b83a0 | 24 |
| `_ZL13TAG_LENS_MAKE` | 0x1b83c0 | 24 |
| `_ZL17TAG_FOCUS_SEGMENT` | 0x1b83e0 | 24 |
| `_ZL17TAG_LENS_MODEL_ID` | 0x1b8400 | 24 |
| `_ZL9TAG_FILES` | 0x1b8420 | 24 |
| `_ZL14IMAGE_TAG_DATA` | 0x1b8440 | 24 |
| `_ZL16IMAGE_TAG_FORMAT` | 0x1b8460 | 24 |
| `_ZL15IMAGE_TAG_WIDTH` | 0x1b8480 | 24 |
| `_ZL16IMAGE_TAG_HEIGHT` | 0x1b84a0 | 24 |
| `_ZL11IMAGE_TAG_X` | 0x1b84c0 | 24 |
| `_ZL11IMAGE_TAG_Y` | 0x1b84e0 | 24 |
| `_ZL19IMAGE_TAG_BUFFER_ID` | 0x1b8500 | 24 |
| `_ZL17IMAGE_FORMAT_RGBA` | 0x1b8520 | 24 |
| `_ZL17IMAGE_FORMAT_UYVY` | 0x1b8540 | 24 |
| `_ZL17IMAGE_FORMAT_NV12` | 0x1b8560 | 24 |
| `_ZL17IMAGE_FORMAT_422P` | 0x1b8580 | 24 |
| `_ZL17IMAGE_FORMAT_JPEG` | 0x1b85a0 | 24 |
| `_ZL12STORAGE_ROOT` | 0x1b85c0 | 24 |
| `_ZL13TETHERED_ROOT` | 0x1b85e0 | 24 |
| `_ZL17STORAGE_MOUNT_SSD` | 0x1b8600 | 24 |
| `_ZL20STORAGE_MOUNT_CFCARD` | 0x1b8620 | 24 |
| `_ZL17HASBL_FOLDER_NAME` | 0x1b8640 | 24 |
| `_ZL9NAME_ROOT` | 0x1b8660 | 24 |
| `_ZL9NAME_DCIM` | 0x1b8680 | 24 |
| `_ZL11SOCKET_NAME` | 0x1b86a0 | 24 |
| `_ZL11EXPOSURE_ID` | 0x1b86c0 | 24 |
| `_ZL14DCAM_CONTAINER` | 0x1b86e0 | 24 |
| `_ZL10FRAME_INFO` | 0x1b8700 | 24 |
| `_ZL18EXPOSURE_ITEM_TYPE` | 0x1b8720 | 24 |

</details>

### `/bin/msg2dbus`

+35 / −3 functions · +8 / −5 objects

**New functions (35)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x3f010 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x3f020 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x3f028 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x3f028 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x3f038 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x3f050 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x3f100 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x3f110 | 12 |
| `_ZN11PhocusProxy11qt_metacallEN11QMetaObject4CallEiPPv` | 0x74068 | 212 |
| `_ZN11CameraProxy35enabled_face_detection_modesChangedEN9HblmTypes15E_FaceDetectionE` | 0x7f0f0 | 96 |
| `_ZN11CameraProxy37exposures_in_multishot_sessionChangedEi` | 0x7f7c8 | 96 |
| `_ZN11CameraProxy27flash_recharge_delayChangedEi` | 0x7fac8 | 96 |
| `_ZN11CameraProxy29multishot_control_modeChangedEN9HblmTypes15E_MultiShotModeE` | 0x817d8 | 96 |
| `_ZN8GuiProxy20ae_lock_touchChangedEb` | 0x85a18 | 100 |
| `_ZN11PhocusProxy31tethered_capture_clientsChangedEN9HblmTypes7E_HostsE` | 0x87030 | 96 |
| `_ZN11SystemProxy21battery_statusChangedEN9HblmTypes15E_BatteryStatusE` | 0x8a900 | 96 |
| `_ZN15PhocusProxyDbus24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeE` | 0x8df20 | 404 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x9fe78 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x9ff10 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x9ff18 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0xa0098 | 200 |
| `_ZN12GuiProxyDbus16setAe_lock_touchEb` | 0xa7f00 | 308 |
| `_ZNK12GuiProxyDbus13ae_lock_touchEv` | 0xab370 | 48 |
| `_ZNK15SystemProxyDbus14battery_statusEv` | 0xc2388 | 48 |
| `_ZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeEiP7QObject` | 0xcb220 | 848 |
| `_ZNK15PhocusProxyDbus24tethered_capture_clientsEv` | 0xcba30 | 48 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjN9HblmTypes10E_FileTypeEiP7QObjectE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseESB_PPvPb` | 0xcc0d8 | 64 |
| `_ZN15CameraProxyDbus31setEnabled_face_detection_modesEN9HblmTypes15E_FaceDetectionE` | 0xdbce8 | 308 |
| `_ZN15CameraProxyDbus33setExposures_in_multishot_sessionEi` | 0xdcb88 | 308 |
| `_ZN15CameraProxyDbus23setFlash_recharge_delayEi` | 0xdd2d8 | 308 |
| `_ZN15CameraProxyDbus25setMultishot_control_modeEN9HblmTypes15E_MultiShotModeE` | 0xdfd80 | 308 |
| `_ZNK15CameraProxyDbus28enabled_face_detection_modesEv` | 0xe2cc0 | 48 |
| `_ZNK15CameraProxyDbus30exposures_in_multishot_sessionEv` | 0xe3020 | 48 |
| `_ZNK15CameraProxyDbus20flash_recharge_delayEv` | 0xe31a0 | 48 |
| `_ZNK15CameraProxyDbus22multishot_control_modeEv` | 0xe4010 | 48 |

**Removed functions (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN15PhocusProxyDbus24doNotify_image_availableE5QListI4QMapI7QString8QVariantEEj` | 0x8da88 | 404 |
| `_ZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiP7QObject` | 0xca2c8 | 804 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN15PhocusProxyDbus22notify_image_availableE5QListI4QMapI7QString8QVariantEEjiP7QObjectE3$_0Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseES9_PPvPb` | 0xcaf80 | 64 |

**New objects (8)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x16cf5d | 27 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_PhocusProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15PhocusProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IK5QListI4QMapI7QString8QVariantEES9_EENS3_IKjS9_EENS3_IKN9HblmTypes10E_FileTypeES9_EESA_NS3_IKhS9_EENS3_IRK10QByteArrayS9_EEEE` | 0x1d4618 | 64 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_15E_FaceDetectionES6_EENS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1O_NS3_IyS6_EESD_S1P_NS3_INS8_16E_ExposureStatusES6_EESD_SD_S1I_S7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1K_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_15E_MultiShotModeES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S39_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1P_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3S_EES3T_NS3_IKNS8_21E_ExposureBlockReasonES3S_EES3T_NS3_IKNS8_21E_LiveviewBlockReasonES3S_EES3T_NS3_IbS3S_EES3T_S43_S3T_S43_S3T_NS3_IS9_S3S_EES3T_NS3_ISB_S3S_EES3T_NS3_IiS3S_EES3T_S43_S3T_NS3_IRKSH_S3S_EES3T_NS3_ISJ_S3S_EES3T_NS3_ISL_S3S_EES3T_NS3_ItS3S_EES3T_NS3_IPKSO_S3S_EES3T_S43_S3T_S43_S3T_NS3_ISR_S3S_EES3T_S46_S3T_NS3_IRKSU_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_ISW_S3S_EES3T_S46_S3T_NS3_ISY_S3S_EES3T_S46_S3T_S46_S3T_NS3_IjS3S_EES3T_NS3_IS11_S3S_EES3T_NS3_IS13_S3S_EES3T_NS3_IS15_S3S_EES3T_S43_S3T_S4P_S3T_S43_S3T_S43_S3T_NS3_IS17_S3S_EES3T_NS3_IS19_S3S_EES3T_NS3_IS1B_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS1D_S3S_EES3T_NS3_IS1F_S3S_EES3T_S43_S3T_S4S_S3T_NS3_IS1H_S3S_EES3T_NS3_IS1J_S3S_EES3T_S43_S3T_S46_S3T_S46_S3T_S4U_S3T_S46_S3T_NS3_IS1L_S3S_EES3T_S4M_S3T_S43_S3T_S46_S3T_NS3_IS1N_S3S_EES3T_S43_S3T_S4Y_S3T_NS3_IyS3S_EES3T_S46_S3T_S4Z_S3T_NS3_IS1Q_S3S_EES3T_S46_S3T_S46_S3T_S4V_S3T_S43_S3T_S49_S3T_S46_S3T_S46_S3T_NS3_IS1S_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Q_S3T_NS3_IS1U_S3S_EES3T_S49_S3T_S49_S3T_NS3_IS1W_S3S_EES3T_NS3_IS1Y_S3S_EES3T_S4M_S3T_NS3_IS20_S3S_EES3T_S49_S3T_S4M_S3T_NS3_IS22_S3S_EES3T_S56_S3T_NS3_IS24_S3S_EES3T_S46_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S46_S3T_S43_S3T_S43_S3T_S43_S3T_NS3_IS26_S3S_EES3T_NS3_IS28_S3S_EES3T_S4W_S3T_S46_S3T_NS3_IS2A_S3S_EES3T_NS3_IS2C_S3S_EES3T_S43_S3T_S46_S3T_S4L_S3T_S46_S3T_S46_S3T_S4M_S3T_NS3_IS2E_S3S_EES3T_NS3_IS2G_S3S_EES3T_NS3_IS2I_S3S_EES3T_NS3_IRKSF_S3S_EES3T_S4C_S3T_S4M_S3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S46_S3T_NS3_IS2L_S3S_EES3T_S4C_S3T_S4M_S3T_S5H_S3T_S5H_S3T_S43_S3T_S5H_S3T_S43_S3T_S43_S3T_S46_S3T_S46_S3T_S5H_S3T_S46_S3T_S43_S3T_S43_S3T_NS3_IS2N_S3S_EES3T_S4M_S3T_NS3_IRKS2P_S3S_EES3T_S46_S3T_S5H_S3T_S4M_S3T_NS3_IS2R_S3S_EES3T_NS3_IS2T_S3S_EES3T_S4M_S3T_S43_S3T_NS3_IS2V_S3S_EES3T_NS3_IS2X_S3S_EES3T_NS3_IS2Z_S3S_EES3T_NS3_IS31_S3S_EES3T_S43_S3T_NS3_IS33_S3S_EES3T_S4M_S3T_S46_S3T_S43_S3T_S4M_S3T_S46_S3T_S4L_S3T_NS3_IS35_S3S_EES3T_NS3_IS37_S3S_EES3T_S43_S3T_S43_S3T_S46_S3T_S43_S3T_S4C_S3T_S43_S3T_NS3_IsS3S_EES3T_NS3_IS3A_S3S_EES3T_S43_S3T_S5W_S3T_NS3_IS3C_S3S_EES3T_NS3_IS3E_S3S_EES3T_NS3_IS3G_S3S_EES3T_NS3_IS3I_S3S_EES3T_S46_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_S4Z_S3T_S46_S3T_S46_S3T_S4J_S3T_S46_S3T_S46_S3T_S43_S3T_S46_S3T_NS3_IS3K_S3S_EES3T_S4S_S3T_S46_S3T_S46_S3T_S46_S3T_S46_S3T_NS3_IS3M_S3S_EES3T_S46_S3T_S46_S3T_S43_S3T_NS3_IS3O_S3S_EES3T_S4M_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_S3T_S43_EE` | 0x1d5840 | 6400 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_GuiProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEENS3_IN9HblmTypes17E_LiveViewOverlayES6_EENS3_IiS6_EESA_SA_S7_S7_S7_NS3_IjS6_EES7_SC_NS3_INS8_16E_FocusScanRangeES6_EES7_S7_S7_S7_NS3_ItS6_EESC_NS3_INS8_17E_MetadataOverlayES6_EENS3_INS8_10E_OSDClockES6_EESB_NS3_INS8_15E_GuiPopupStateES6_EESC_SB_S7_S7_NS3_INS8_14E_TouchpadAreaES6_EENS3_INS8_21E_TouchpadSensitivityES6_EES7_NS3_INS8_20E_UserButtonFunctionES6_EESR_SR_SR_SR_SR_SR_SR_SB_SB_SB_SB_NS3_I5QListIiES6_EESB_SB_NS3_INS8_19E_UserWheelFunctionES6_EESA_S7_NS3_I8GuiProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IbSZ_EES10_NS3_IS9_SZ_EES10_NS3_IiSZ_EES10_S12_S10_S12_S10_S11_S10_S11_S10_S11_S10_NS3_IjSZ_EES10_S11_S10_S14_S10_NS3_ISD_SZ_EES10_S11_S10_S11_S10_S11_S10_S11_S10_NS3_ItSZ_EES10_S14_S10_NS3_ISG_SZ_EES10_NS3_ISI_SZ_EES10_S13_S10_NS3_ISK_SZ_EES10_S14_S10_S13_S10_S11_S10_S11_S10_NS3_ISM_SZ_EES10_NS3_ISO_SZ_EES10_S11_S10_NS3_ISQ_SZ_EES10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S13_S10_S13_S10_S13_S10_S13_S10_NS3_IRKST_SZ_EES10_S13_S10_S13_S10_NS3_ISV_SZ_EES10_S12_EE` | 0x1d7220 | 1120 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEENS3_IjS8_EES9_NS3_IbS8_EESB_SB_NS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IKhSE_EENS3_IRK10QByteArraySE_EESF_NS3_IS5_SE_EESF_NS3_IjSE_EESF_SM_SF_NS3_IbSE_EESF_SO_EE` | 0x1d7690 | 160 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_IN9HblmTypes15E_BatteryStatusES6_EENS3_I7QStringS6_EESE_SE_SE_NS3_INSA_16E_BtAssistStatusES6_EESE_S9_S8_S9_NS3_IP15VariantMapModelS6_EES9_NS3_INSA_13E_DebugOptionES6_EES8_S8_S9_S7_NS3_INSA_20E_EyesensorDistancesES6_EES8_NS3_ItS6_EENS3_INSA_17E_MaintenanceTypeES6_EES9_SO_SO_NS3_INSA_10E_ProfilesES6_EES9_SE_S7_S9_S7_S9_S9_S8_NS3_INSA_14E_ScreenStatusES6_EENS3_INSA_9E_ScreensES6_EESW_SW_NS3_INSA_15E_SoundSettingsES6_EES9_NS3_IsS6_EENS3_INSA_24E_SpiritLevelOrientationES6_EES9_SZ_NS3_INSA_21E_SuspendWakeupSourceES6_EES8_S8_NS3_INSA_12E_SoundLevelES6_EENS3_INSA_13E_SystemStateES6_EENS3_INSA_19E_TemperatureStatusES6_EENS3_INSA_14E_TetheredModeES6_EES7_S9_S9_SE_S8_S8_NS3_INSA_10E_WifiModeES6_EESE_S9_SE_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_NS3_I11SystemProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKxS1G_EES1H_NS3_IjS1G_EES1H_NS3_IiS1G_EES1H_S1L_S1H_NS3_IbS1G_EES1H_NS3_ISB_S1G_EES1H_NS3_IRKSD_S1G_EES1H_S1Q_S1H_S1Q_S1H_S1Q_S1H_NS3_ISF_S1G_EES1H_S1Q_S1H_S1M_S1H_S1L_S1H_S1M_S1H_NS3_IPKSH_S1G_EES1H_S1M_S1H_NS3_ISK_S1G_EES1H_S1L_S1H_S1L_S1H_S1M_S1H_S1K_S1H_NS3_ISM_S1G_EES1H_S1L_S1H_NS3_ItS1G_EES1H_NS3_ISP_S1G_EES1H_S1M_S1H_S1X_S1H_S1X_S1H_NS3_ISR_S1G_EES1H_S1M_S1H_S1Q_S1H_S1K_S1H_S1M_S1H_S1K_S1H_S1M_S1H_S1M_S1H_S1L_S1H_NS3_IST_S1G_EES1H_NS3_ISV_S1G_EES1H_S21_S1H_S21_S1H_NS3_ISX_S1G_EES1H_S1M_S1H_NS3_IsS1G_EES1H_NS3_IS10_S1G_EES1H_S1M_S1H_S23_S1H_NS3_IS12_S1G_EES1H_S1L_S1H_S1L_S1H_NS3_IS14_S1G_EES1H_NS3_IS16_S1G_EES1H_NS3_IS18_S1G_EES1H_NS3_IS1A_S1G_EES1H_S1K_S1H_S1M_S1H_S1M_S1H_S1Q_S1H_S1L_S1H_S1L_S1H_NS3_IS1C_S1G_EES1H_S1Q_S1H_S1M_S1H_S1Q_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_S1H_S1M_EE` | 0x1d7a78 | 2072 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x1e3468 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x1e65dc | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_136qt_meta_stringdata_PhocusProxyDbus_tEJN9QtPrivate20TypeAndForceCompleteI15PhocusProxyDbusNSt3__117integral_constantIbLb1EEEEENS3_IvNS6_IbLb0EEEEENS3_IK5QListI4QMapI7QString8QVariantEES9_EENS3_IKjS9_EESA_NS3_IKhS9_EENS3_IRK10QByteArrayS9_EEEE` | 0x1d4768 | 56 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_CameraProxy_tEJN9QtPrivate20TypeAndForceCompleteIbNSt3__117integral_constantIbLb1EEEEES7_S7_NS3_IN9HblmTypes17E_AfAlgorithmModeES6_EENS3_INS8_21E_AfFaceDetectionModeES6_EENS3_IiS6_EES7_NS3_I4QMapI7QString8QVariantES6_EENS3_INS8_17E_AutoFocusResultES6_EENS3_INS8_17E_AutoFocusStatusES6_EENS3_ItS6_EENS3_IP15VariantMapModelS6_EES7_S7_NS3_INS8_10E_LensTypeES6_EESD_NS3_I5QListIiES6_EESD_SD_S7_SD_S7_S7_S7_NS3_INS8_20E_ExpBracketingParamES6_EESD_NS3_INS8_12E_ExitOptionES6_EESD_SD_NS3_IjS6_EENS3_INS8_12E_CameraModeES6_EENS3_INS8_12E_CameraTypeES6_EENS3_INS8_18E_CameraPropertiesES6_EES7_S16_S7_S7_NS3_INS8_26E_FocusBracketingStepSizesES6_EENS3_INS8_14E_ColorProfileES6_EENS3_INS8_10E_CropModeES6_EESD_SD_S7_SD_S7_SD_S7_SD_SD_SD_SD_SD_S7_NS3_INS8_12E_TraceLevelES6_EENS3_INS8_12E_DriveModesES6_EES7_S1C_NS3_INS8_13E_ImageFormatES6_EES7_SD_SD_S1G_SD_NS3_INS8_9E_ExpModeES6_EES10_S7_SD_NS3_INS8_21E_ExposureControlModeES6_EES7_S1M_NS3_IyS6_EESD_S1N_NS3_INS8_16E_ExposureStatusES6_EESD_NS3_INS8_15E_FaceDetectionES6_EES7_SI_SD_SD_NS3_INS8_12E_FlashModesES6_EESD_SD_SD_S18_NS3_INS8_27E_FocusBracketingStrategiesES6_EESI_SI_NS3_INS8_12E_FocusModesES6_EENS3_INS8_19E_FocusPeakingColorES6_EES10_NS3_INS8_21E_FocusPointResetModeES6_EESI_S10_NS3_INS8_11E_FocusSizeES6_EES23_NS3_INS8_17E_CameraKeyOptionES6_EESD_S7_S7_SD_SD_SD_S7_S7_S7_NS3_INS8_10E_IbisModeES6_EENS3_INS8_10E_BitDepthES6_EES1I_SD_NS3_INS8_21E_ImagePostProcessingES6_EENS3_INS8_17E_IbisControlModeES6_EES7_SD_SZ_SD_SD_S10_NS3_INS8_13E_ResolutionsES6_EENS3_INS8_19E_LensDriveEndpointES6_EENS3_INS8_17E_LensDriveStatusES6_EENS3_ISF_S6_EESN_S10_S10_S7_S7_S7_S7_SD_NS3_INS8_17E_LensMfRingStateES6_EESN_S10_S2K_S2K_S7_S2K_S7_S7_SD_SD_S2K_SD_S7_S7_NS3_INS8_15E_LiveViewStateES6_EES10_NS3_I10QByteArrayS6_EESD_S2K_S10_NS3_INS8_23E_LiveviewTransportModeES6_EENS3_INS8_9E_LmModesES6_EES10_S7_NS3_INS8_19E_ManualFocusAssistES6_EENS3_INS8_13E_MaxApertureES6_EENS3_INS8_13E_FlashStatusES6_EES7_NS3_INS8_16E_OptionOverrideES6_EES10_SD_S7_S10_SD_SZ_NS3_INS8_12E_SoundLevelES6_EENS3_INS8_14E_SequenceModeES6_EES7_S7_SD_S7_SN_S7_NS3_IsS6_EENS3_INS8_24E_SpiritLevelOrientationES6_EES7_S37_NS3_INS8_14E_CameraStatusES6_EENS3_INS8_16E_StopDownStatusES6_EENS3_INS8_13E_StreamGroupES6_EENS3_INS8_18E_SensorUnitStatusES6_EESD_SD_SD_SV_SD_SD_SD_SD_S1N_SD_SD_SV_SD_SD_S7_SD_NS3_INS8_14E_DistanceUnitES6_EES1C_SD_SD_SD_SD_NS3_INS8_12E_WhiteModesES6_EESD_SD_S7_NS3_INS8_11E_ZoomLevelES6_EES10_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_S7_NS3_I11CameraProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKNS8_15E_AfBlockReasonES3Q_EES3R_NS3_IKNS8_21E_ExposureBlockReasonES3Q_EES3R_NS3_IKNS8_21E_LiveviewBlockReasonES3Q_EES3R_NS3_IbS3Q_EES3R_S41_S3R_S41_S3R_NS3_IS9_S3Q_EES3R_NS3_ISB_S3Q_EES3R_NS3_IiS3Q_EES3R_S41_S3R_NS3_IRKSH_S3Q_EES3R_NS3_ISJ_S3Q_EES3R_NS3_ISL_S3Q_EES3R_NS3_ItS3Q_EES3R_NS3_IPKSO_S3Q_EES3R_S41_S3R_S41_S3R_NS3_ISR_S3Q_EES3R_S44_S3R_NS3_IRKSU_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S41_S3R_S41_S3R_NS3_ISW_S3Q_EES3R_S44_S3R_NS3_ISY_S3Q_EES3R_S44_S3R_S44_S3R_NS3_IjS3Q_EES3R_NS3_IS11_S3Q_EES3R_NS3_IS13_S3Q_EES3R_NS3_IS15_S3Q_EES3R_S41_S3R_S4N_S3R_S41_S3R_S41_S3R_NS3_IS17_S3Q_EES3R_NS3_IS19_S3Q_EES3R_NS3_IS1B_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S44_S3R_S41_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S41_S3R_NS3_IS1D_S3Q_EES3R_NS3_IS1F_S3Q_EES3R_S41_S3R_S4Q_S3R_NS3_IS1H_S3Q_EES3R_S41_S3R_S44_S3R_S44_S3R_S4S_S3R_S44_S3R_NS3_IS1J_S3Q_EES3R_S4K_S3R_S41_S3R_S44_S3R_NS3_IS1L_S3Q_EES3R_S41_S3R_S4V_S3R_NS3_IyS3Q_EES3R_S44_S3R_S4W_S3R_NS3_IS1O_S3Q_EES3R_S44_S3R_NS3_IS1Q_S3Q_EES3R_S41_S3R_S47_S3R_S44_S3R_S44_S3R_NS3_IS1S_S3Q_EES3R_S44_S3R_S44_S3R_S44_S3R_S4O_S3R_NS3_IS1U_S3Q_EES3R_S47_S3R_S47_S3R_NS3_IS1W_S3Q_EES3R_NS3_IS1Y_S3Q_EES3R_S4K_S3R_NS3_IS20_S3Q_EES3R_S47_S3R_S4K_S3R_NS3_IS22_S3Q_EES3R_S54_S3R_NS3_IS24_S3Q_EES3R_S44_S3R_S41_S3R_S41_S3R_S44_S3R_S44_S3R_S44_S3R_S41_S3R_S41_S3R_S41_S3R_NS3_IS26_S3Q_EES3R_NS3_IS28_S3Q_EES3R_S4T_S3R_S44_S3R_NS3_IS2A_S3Q_EES3R_NS3_IS2C_S3Q_EES3R_S41_S3R_S44_S3R_S4J_S3R_S44_S3R_S44_S3R_S4K_S3R_NS3_IS2E_S3Q_EES3R_NS3_IS2G_S3Q_EES3R_NS3_IS2I_S3Q_EES3R_NS3_IRKSF_S3Q_EES3R_S4A_S3R_S4K_S3R_S4K_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S44_S3R_NS3_IS2L_S3Q_EES3R_S4A_S3R_S4K_S3R_S5F_S3R_S5F_S3R_S41_S3R_S5F_S3R_S41_S3R_S41_S3R_S44_S3R_S44_S3R_S5F_S3R_S44_S3R_S41_S3R_S41_S3R_NS3_IS2N_S3Q_EES3R_S4K_S3R_NS3_IRKS2P_S3Q_EES3R_S44_S3R_S5F_S3R_S4K_S3R_NS3_IS2R_S3Q_EES3R_NS3_IS2T_S3Q_EES3R_S4K_S3R_S41_S3R_NS3_IS2V_S3Q_EES3R_NS3_IS2X_S3Q_EES3R_NS3_IS2Z_S3Q_EES3R_S41_S3R_NS3_IS31_S3Q_EES3R_S4K_S3R_S44_S3R_S41_S3R_S4K_S3R_S44_S3R_S4J_S3R_NS3_IS33_S3Q_EES3R_NS3_IS35_S3Q_EES3R_S41_S3R_S41_S3R_S44_S3R_S41_S3R_S4A_S3R_S41_S3R_NS3_IsS3Q_EES3R_NS3_IS38_S3Q_EES3R_S41_S3R_S5T_S3R_NS3_IS3A_S3Q_EES3R_NS3_IS3C_S3Q_EES3R_NS3_IS3E_S3Q_EES3R_NS3_IS3G_S3Q_EES3R_S44_S3R_S44_S3R_S44_S3R_S4H_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_S4W_S3R_S44_S3R_S44_S3R_S4H_S3R_S44_S3R_S44_S3R_S41_S3R_S44_S3R_NS3_IS3I_S3Q_EES3R_S4Q_S3R_S44_S3R_S44_S3R_S44_S3R_S44_S3R_NS3_IS3K_S3Q_EES3R_S44_S3R_S44_S3R_S41_S3R_NS3_IS3M_S3Q_EES3R_S4K_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_S3R_S41_EE` | 0x1d5988 | 6304 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_129qt_meta_stringdata_GuiProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes17E_LiveViewOverlayENSt3__117integral_constantIbLb1EEEEENS3_IiS8_EES9_S9_NS3_IbS8_EESB_SB_NS3_IjS8_EESB_SC_NS3_INS4_16E_FocusScanRangeES8_EESB_SB_SB_SB_NS3_ItS8_EESC_NS3_INS4_17E_MetadataOverlayES8_EENS3_INS4_10E_OSDClockES8_EESA_NS3_INS4_15E_GuiPopupStateES8_EESC_SA_SB_SB_NS3_INS4_14E_TouchpadAreaES8_EENS3_INS4_21E_TouchpadSensitivityES8_EESB_NS3_INS4_20E_UserButtonFunctionES8_EESR_SR_SR_SR_SR_SR_SR_SA_SA_SA_SA_NS3_I5QListIiES8_EESA_SA_NS3_INS4_19E_UserWheelFunctionES8_EES9_SB_NS3_I8GuiProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IS5_SZ_EES10_NS3_IiSZ_EES10_S11_S10_S11_S10_NS3_IbSZ_EES10_S13_S10_S13_S10_NS3_IjSZ_EES10_S13_S10_S14_S10_NS3_ISD_SZ_EES10_S13_S10_S13_S10_S13_S10_S13_S10_NS3_ItSZ_EES10_S14_S10_NS3_ISG_SZ_EES10_NS3_ISI_SZ_EES10_S12_S10_NS3_ISK_SZ_EES10_S14_S10_S12_S10_S13_S10_S13_S10_NS3_ISM_SZ_EES10_NS3_ISO_SZ_EES10_S13_S10_NS3_ISQ_SZ_EES10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S1C_S10_S12_S10_S12_S10_S12_S10_S12_S10_NS3_IRKST_SZ_EES10_S12_S10_S12_S10_NS3_ISV_SZ_EES10_S11_EE` | 0x1d7308 | 1096 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_PhocusProxy_tEJN9QtPrivate20TypeAndForceCompleteIN9HblmTypes7E_HostsENSt3__117integral_constantIbLb1EEEEENS3_IjS8_EENS3_IbS8_EESB_SB_NS3_I11PhocusProxyS8_EENS3_IvNS7_IbLb0EEEEENS3_IKhSE_EENS3_IRK10QByteArraySE_EESF_NS3_IS5_SE_EESF_NS3_IjSE_EESF_NS3_IbSE_EESF_SO_EE` | 0x1d7760 | 136 |
| `_Z27qt_incomplete_metaTypeArrayIN12_GLOBAL__N_132qt_meta_stringdata_SystemProxy_tEJN9QtPrivate20TypeAndForceCompleteIjNSt3__117integral_constantIbLb1EEEEENS3_IiS6_EES8_NS3_IbS6_EENS3_I7QStringS6_EESB_SB_SB_NS3_IN9HblmTypes16E_BtAssistStatusES6_EESB_S9_S8_S9_NS3_IP15VariantMapModelS6_EES9_NS3_INSC_13E_DebugOptionES6_EES8_S8_S9_S7_NS3_INSC_20E_EyesensorDistancesES6_EES8_NS3_ItS6_EENS3_INSC_17E_MaintenanceTypeES6_EES9_SM_SM_NS3_INSC_10E_ProfilesES6_EES9_SB_S7_S9_S7_S9_S9_S8_NS3_INSC_14E_ScreenStatusES6_EENS3_INSC_9E_ScreensES6_EESU_SU_NS3_INSC_15E_SoundSettingsES6_EES9_NS3_IsS6_EENS3_INSC_24E_SpiritLevelOrientationES6_EES9_SX_NS3_INSC_21E_SuspendWakeupSourceES6_EES8_S8_NS3_INSC_12E_SoundLevelES6_EENS3_INSC_13E_SystemStateES6_EENS3_INSC_19E_TemperatureStatusES6_EENS3_INSC_14E_TetheredModeES6_EES7_S9_S9_SB_S8_S8_NS3_INSC_10E_WifiModeES6_EESB_S9_SB_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_S9_NS3_I11SystemProxyS6_EENS3_IvNS5_IbLb0EEEEENS3_IKxS1E_EES1F_NS3_IjS1E_EES1F_NS3_IiS1E_EES1F_S1J_S1F_NS3_IbS1E_EES1F_NS3_IRKSA_S1E_EES1F_S1N_S1F_S1N_S1F_S1N_S1F_NS3_ISD_S1E_EES1F_S1N_S1F_S1K_S1F_S1J_S1F_S1K_S1F_NS3_IPKSF_S1E_EES1F_S1K_S1F_NS3_ISI_S1E_EES1F_S1J_S1F_S1J_S1F_S1K_S1F_S1I_S1F_NS3_ISK_S1E_EES1F_S1J_S1F_NS3_ItS1E_EES1F_NS3_ISN_S1E_EES1F_S1K_S1F_S1U_S1F_S1U_S1F_NS3_ISP_S1E_EES1F_S1K_S1F_S1N_S1F_S1I_S1F_S1K_S1F_S1I_S1F_S1K_S1F_S1K_S1F_S1J_S1F_NS3_ISR_S1E_EES1F_NS3_IST_S1E_EES1F_S1Y_S1F_S1Y_S1F_NS3_ISV_S1E_EES1F_S1K_S1F_NS3_IsS1E_EES1F_NS3_ISY_S1E_EES1F_S1K_S1F_S20_S1F_NS3_IS10_S1E_EES1F_S1J_S1F_S1J_S1F_NS3_IS12_S1E_EES1F_NS3_IS14_S1E_EES1F_NS3_IS16_S1E_EES1F_NS3_IS18_S1E_EES1F_S1I_S1F_S1K_S1F_S1K_S1F_S1N_S1F_S1J_S1F_S1J_S1F_NS3_IS1A_S1E_EES1F_S1N_S1F_S1K_S1F_S1N_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_S1F_S1K_EE` | 0x1d7b30 | 2048 |

### `/lib64/weston/eagle-backend.so`

+23 / −12 functions · +0 / −0 objects

**New functions (23)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNSt3__110__list_impI17EagleOutputConfigNS_9allocatorIS1_EEE5clearEv` | 0x84368 | 216 |
| `_ZN14EagleVopConfigD2Ev` | 0x84440 | 252 |
| `_ZNK11EagleOutput16findModeByTimingERK18duss_disp_timing_t` | 0x84dc8 | 104 |
| `_ZN11EagleOutput10readPixelsEP12duss_hal_obj20pixman_format_code_tPvjjjj` | 0x896d8 | 956 |
| `_ZN11EagleOutput24eagle_output_read_pixelsEP13weston_outputP12duss_hal_obj20pixman_format_code_tPvjjjj` | 0x89a98 | 4 |
| `_ZNSt3__16__sortIRZN11EagleOutput11setupPlanesEvE3$_4PNS_10shared_ptrI13EagleVopPlaneEEEEvT0_S8_T_` | 0x8db40 | 1388 |
| `_ZZN11EagleOutput11setupPlanesEvENK3$_4clERKNSt3__110shared_ptrI13EagleVopPlaneEES6_` | 0x8e0b0 | 544 |
| `_ZNSt3__17__sort3IRZN11EagleOutput11setupPlanesEvE3$_4PNS_10shared_ptrI13EagleVopPlaneEEEEjT0_S8_S8_T_` | 0x8e2d0 | 304 |
| `_ZNSt3__17__sort4IRZN11EagleOutput11setupPlanesEvE3$_4PNS_10shared_ptrI13EagleVopPlaneEEEEjT0_S8_S8_S8_T_` | 0x8e400 | 232 |
| `_ZNSt3__17__sort5IRZN11EagleOutput11setupPlanesEvE3$_4PNS_10shared_ptrI13EagleVopPlaneEEEEjT0_S8_S8_S8_S8_T_` | 0x8e4e8 | 292 |
| `_ZNSt3__127__insertion_sort_incompleteIRZN11EagleOutput11setupPlanesEvE3$_4PNS_10shared_ptrI13EagleVopPlaneEEEEbT0_S8_T_` | 0x8e610 | 612 |
| `_ZNSt3__114__thread_proxyINS_5tupleIJNS_10unique_ptrINS_15__thread_structENS_14default_deleteIS3_EEEEZN11EagleOutput9hpdEnableEvE3$_5PS7_EEEEEPvSB_` | 0x8ea38 | 100 |
| `_ZNKSt3__110__function6__funcIZN11EagleOutput10readPixelsEP12duss_hal_obj20pixman_format_code_tPvjjjjE3$_6NS_9allocatorIS7_EEFiP17duss_frame_bufferS6_EE7__cloneEv` | 0x8eaa0 | 60 |
| `_ZNKSt3__110__function6__funcIZN11EagleOutput10readPixelsEP12duss_hal_obj20pixman_format_code_tPvjjjjE3$_6NS_9allocatorIS7_EEFiP17duss_frame_bufferS6_EE7__cloneEPNS0_6__baseISC_EE` | 0x8eae0 | 28 |
| `_ZNSt3__110__function6__funcIZN11EagleOutput10readPixelsEP12duss_hal_obj20pixman_format_code_tPvjjjjE3$_6NS_9allocatorIS7_EEFiP17duss_frame_bufferS6_EEclEOSB_OS6_` | 0x8eb00 | 60 |
| `_ZN14EagleVopConfigC2EaRKNSt3__14listI16EaglePanelConfigNS0_9allocatorIS2_EEEERKNS1_I9EagleModeNS3_IS8_EEEERKNS1_I16EaglePlaneConfigNS3_ISD_EEEE` | 0x92b78 | 368 |
| `_ZN14EagleVopConfigC2ERKS_` | 0x92de8 | 368 |
| `_ZNSt3__14listI17EagleOutputConfigNS_9allocatorIS1_EEE9push_backERKS1_` | 0x92f58 | 212 |
| `__letf2` | 0x1688d4 | 316 |
| `__lttf2` | 0x1688d4 | 316 |
| `__multf3` | 0x168a10 | 1756 |
| `__floatditf` | 0x1690ec | 140 |
| `__sfp_handle_exceptions` | 0x16c924 | 96 |

**Removed functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNSt3__110__list_impI14EagleVopConfigNS_9allocatorIS1_EEE5clearEv` | 0x840c8 | 260 |
| `_ZNK11EagleOutput16findModeByTimingEPK18duss_disp_timing_t` | 0x84a50 | 108 |
| `_ZN11EagleOutput10readPixelsE20pixman_format_code_tPvjjjj` | 0x89268 | 492 |
| `_ZN11EagleOutput24eagle_output_read_pixelsEP13weston_output20pixman_format_code_tPvjjjj` | 0x89458 | 4 |
| `_ZNSt3__16__sortIRZN11EagleOutput11setupPlanesEvE3$_3PNS_10shared_ptrI13EagleVopPlaneEEEEvT0_S8_T_` | 0x8d4e8 | 1388 |
| `_ZZN11EagleOutput11setupPlanesEvENK3$_3clERKNSt3__110shared_ptrI13EagleVopPlaneEES6_` | 0x8da58 | 544 |
| `_ZNSt3__17__sort3IRZN11EagleOutput11setupPlanesEvE3$_3PNS_10shared_ptrI13EagleVopPlaneEEEEjT0_S8_S8_T_` | 0x8dc78 | 304 |
| `_ZNSt3__17__sort4IRZN11EagleOutput11setupPlanesEvE3$_3PNS_10shared_ptrI13EagleVopPlaneEEEEjT0_S8_S8_S8_T_` | 0x8dda8 | 232 |
| `_ZNSt3__17__sort5IRZN11EagleOutput11setupPlanesEvE3$_3PNS_10shared_ptrI13EagleVopPlaneEEEEjT0_S8_S8_S8_S8_T_` | 0x8de90 | 292 |
| `_ZNSt3__127__insertion_sort_incompleteIRZN11EagleOutput11setupPlanesEvE3$_3PNS_10shared_ptrI13EagleVopPlaneEEEEbT0_S8_T_` | 0x8dfb8 | 612 |
| `_ZNSt3__114__thread_proxyINS_5tupleIJNS_10unique_ptrINS_15__thread_structENS_14default_deleteIS3_EEEEZN11EagleOutput9hpdEnableEvE3$_4PS7_EEEEEPvSB_` | 0x8e3e0 | 100 |
| `_ZNSt3__14listI14EagleVopConfigNS_9allocatorIS1_EEE9push_backERKS1_` | 0x92448 | 332 |

### `/bin/camera-upgrade`

+29 / −0 functions · +5 / −94 objects

**New functions (29)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2f888 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x2f898 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x2f8a0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x2f8a0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2f8b0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2f8c8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x2f978 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x2f988 | 12 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringED2Ev` | 0x8d120 | 88 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringED2Ev` | 0x8d120 | 88 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x8d3a0 | 108 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE7destroyEPNS_11__tree_nodeIS5_PvEE` | 0x8d3a0 | 108 |
| `_ZN4QMapIN8CStorage7MetaTagE7QStringE6insertERKS1_RKS2_` | 0x8d410 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage7MetaTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x8d598 | 392 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x8d720 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKNS_4pairIKS3_S4_EEEEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SN_lEERKT_DpOT0_` | 0x8d720 | 244 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x8d818 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE12__find_equalIS3_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS5_PNS_11__tree_nodeIS5_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_` | 0x8d818 | 452 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage10StorageTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x8d9e0 | 248 |
| `_ZNSt3__16__treeINS_12__value_typeIN8CStorage7MetaTagE7QStringEENS_19__map_value_compareIS3_S5_NS_4lessIS3_EELb1EEENS_9allocatorIS5_EEE30__emplace_hint_unique_key_argsIS3_JRKS3_RKS4_EEENS_15__tree_iteratorIS5_PNS_11__tree_nodeIS5_PvEElEENS_21__tree_const_iteratorIS5_SM_lEERKT_DpOT0_` | 0x8d9e0 | 248 |
| `_ZN4QMapIN8CStorage10StorageTagE7QStringE6insertERKS1_RKS2_` | 0x8dad8 | 392 |
| `_ZN9QtPrivate30QExplicitlySharedDataPointerV2I8QMapDataINSt3__13mapIN8CStorage10StorageTagE7QStringNS2_4lessIS5_EENS2_9allocatorINS2_4pairIKS5_S6_EEEEEEEE6detachEv` | 0x8dc60 | 392 |
| `_ZN7Version14hblProductInfoC1Ev` | 0x8e830 | 12 |
| `_ZN7Version14hblProductInfoC2Ev` | 0x8e830 | 12 |
| `_ZNK7Version14hblProductInfo18supportsCimVersionEiiii` | 0x8e840 | 240 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0xc49e8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0xc4a80 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0xc4a88 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0xc4c08 | 200 |

**New objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0xf119b | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x133938 | 112 |
| `_ZN12_GLOBAL__N_111kMetaTagMapE` | 0x135dd0 | 8 |
| `_ZN12_GLOBAL__N_114kStorageTagMapE` | 0x135dd8 | 8 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x13653c | 4 |

**Removed objects (94)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZL11TAG_MOUNTED` | 0x135d60 | 24 |
| `_ZL8TAG_TYPE` | 0x135d80 | 24 |
| `_ZL8TAG_NAME` | 0x135da0 | 24 |
| `_ZL8TAG_UUID` | 0x135dc0 | 24 |
| `_ZL15TAG_EXPOSURE_ID` | 0x135de0 | 24 |
| `_ZL8TAG_SIZE` | 0x135e00 | 24 |
| `_ZL10TAG_OFFSET` | 0x135e20 | 24 |
| `_ZL10TAG_HANDLE` | 0x135e40 | 24 |
| `_ZL15TAG_DEVICE_TYPE` | 0x135e60 | 24 |
| `_ZL13TAG_SIZECHILD` | 0x135e80 | 24 |
| `_ZL13TAG_FULL_PATH` | 0x135ea0 | 24 |
| `_ZL16TAG_DISPLAY_PATH` | 0x135ec0 | 24 |
| `_ZL28TAG_DISPLAY_PATH_WITH_SUFFIX` | 0x135ee0 | 24 |
| `_ZL12TAG_METADATA` | 0x135f00 | 24 |
| `_ZL15TAG_LORES_IMAGE` | 0x135f20 | 24 |
| `_ZL15TAG_THUMB_IMAGE` | 0x135f40 | 24 |
| `_ZL14TAG_TILE_IMAGE` | 0x135f60 | 24 |
| `_ZL14TAG_FREE_SPACE` | 0x135f80 | 24 |
| `_ZL16TAG_WRITEPROTECT` | 0x135fa0 | 24 |
| `_ZL10TAG_STATUS` | 0x135fc0 | 24 |
| `_ZL6TAG_WP` | 0x135fe0 | 24 |
| `_ZL14TAG_SLOW_SPEED` | 0x136000 | 24 |
| `_ZL17TAG_AVERAGE_SPEED` | 0x136020 | 24 |
| `_ZL13TAG_DATE_TIME` | 0x136040 | 24 |
| `_ZL6TAG_SV` | 0x136060 | 24 |
| `_ZL6TAG_AV` | 0x136080 | 24 |
| `_ZL21TAG_FNUMBER_NUMERATOR` | 0x1360a0 | 24 |
| `_ZL23TAG_FNUMBER_DENOMINATOR` | 0x1360c0 | 24 |
| `_ZL10TAG_AV_MIN` | 0x1360e0 | 24 |
| `_ZL6TAG_TV` | 0x136100 | 24 |
| `_ZL13TAG_FOCAL_LEN` | 0x136120 | 24 |
| `_ZL17TAG_EXPOSURE_MODE` | 0x136140 | 24 |
| `_ZL27TAG_EXPOSURE_TIME_NUMERATOR` | 0x136160 | 24 |
| `_ZL29TAG_EXPOSURE_TIME_DENOMINATOR` | 0x136180 | 24 |
| `_ZL11TAG_LM_MODE` | 0x1361a0 | 24 |
| `_ZL6TAG_WB` | 0x1361c0 | 24 |
| `_ZL10TAG_EV_ADJ` | 0x1361e0 | 24 |
| `_ZL17TAG_EXPOSURE_BIAS` | 0x136200 | 24 |
| `_ZL14TAG_LENS_SHIFT` | 0x136220 | 24 |
| `_ZL16TAG_LENS_VERSION` | 0x136240 | 24 |
| `_ZL27TAG_LENS_SHADING_CORRECTION` | 0x136260 | 24 |
| `_ZL21TAG_LENS_FOCAL_MINMAX` | 0x136280 | 24 |
| `_ZL13TAG_LENS_TYPE` | 0x1362a0 | 24 |
| `_ZL13TAG_HISTOGRAM` | 0x1362c0 | 24 |
| `_ZL16TAG_FS_TIMESTAMP` | 0x1362e0 | 24 |
| `_ZL8TAG_PATH` | 0x136300 | 24 |
| `_ZL14TAG_PERSISTENT` | 0x136320 | 24 |
| `_ZL15TAG_R_NUMERATOR` | 0x136340 | 24 |
| `_ZL17TAG_R_DENOMINATOR` | 0x136360 | 24 |
| `_ZL15TAG_G_NUMERATOR` | 0x136380 | 24 |

<details><summary>… 另 44 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZL17TAG_G_DENOMINATOR` | 0x1363a0 | 24 |
| `_ZL15TAG_B_NUMERATOR` | 0x1363c0 | 24 |
| `_ZL17TAG_B_DENOMINATOR` | 0x1363e0 | 24 |
| `_ZL22TAG_BLACK_LEVEL_OFFSET` | 0x136400 | 24 |
| `_ZL15TAG_WHITE_LEVEL` | 0x136420 | 24 |
| `_ZL20TAG_SENSITIVITY_GAIN` | 0x136440 | 24 |
| `_ZL18TAG_R_NEUTRAL_GAIN` | 0x136460 | 24 |
| `_ZL18TAG_G_NEUTRAL_GAIN` | 0x136480 | 24 |
| `_ZL18TAG_B_NEUTRAL_GAIN` | 0x1364a0 | 24 |
| `_ZL21TAG_NEUTRAL_PRECISION` | 0x1364c0 | 24 |
| `_ZL16TAG_IMAGE_RATING` | 0x1364e0 | 24 |
| `_ZL18TAG_IMAGE_ROTATION` | 0x136500 | 24 |
| `_ZL15TAG_CAMERA_TYPE` | 0x136520 | 24 |
| `_ZL15TAG_FOCUS_POINT` | 0x136540 | 24 |
| `_ZL20TAG_SUBJECT_DISTANCE` | 0x136560 | 24 |
| `_ZL14TAG_LENS_MODEL` | 0x136580 | 24 |
| `_ZL13TAG_LENS_MAKE` | 0x1365a0 | 24 |
| `_ZL17TAG_FOCUS_SEGMENT` | 0x1365c0 | 24 |
| `_ZL17TAG_LENS_MODEL_ID` | 0x1365e0 | 24 |
| `_ZL9TAG_FILES` | 0x136600 | 24 |
| `_ZL14IMAGE_TAG_DATA` | 0x136620 | 24 |
| `_ZL16IMAGE_TAG_FORMAT` | 0x136640 | 24 |
| `_ZL15IMAGE_TAG_WIDTH` | 0x136660 | 24 |
| `_ZL16IMAGE_TAG_HEIGHT` | 0x136680 | 24 |
| `_ZL11IMAGE_TAG_X` | 0x1366a0 | 24 |
| `_ZL11IMAGE_TAG_Y` | 0x1366c0 | 24 |
| `_ZL19IMAGE_TAG_BUFFER_ID` | 0x1366e0 | 24 |
| `_ZL17IMAGE_FORMAT_RGBA` | 0x136700 | 24 |
| `_ZL17IMAGE_FORMAT_UYVY` | 0x136720 | 24 |
| `_ZL17IMAGE_FORMAT_NV12` | 0x136740 | 24 |
| `_ZL17IMAGE_FORMAT_422P` | 0x136760 | 24 |
| `_ZL17IMAGE_FORMAT_JPEG` | 0x136780 | 24 |
| `_ZL12STORAGE_ROOT` | 0x1367a0 | 24 |
| `_ZL13TETHERED_ROOT` | 0x1367c0 | 24 |
| `_ZL17STORAGE_MOUNT_SSD` | 0x1367e0 | 24 |
| `_ZL20STORAGE_MOUNT_CFCARD` | 0x136800 | 24 |
| `_ZL17HASBL_FOLDER_NAME` | 0x136820 | 24 |
| `_ZL9NAME_ROOT` | 0x136840 | 24 |
| `_ZL9NAME_DCIM` | 0x136860 | 24 |
| `_ZL11SOCKET_NAME` | 0x136880 | 24 |
| `_ZL11EXPOSURE_ID` | 0x1368a0 | 24 |
| `_ZL14DCAM_CONTAINER` | 0x1368c0 | 24 |
| `_ZL10FRAME_INFO` | 0x1368e0 | 24 |
| `_ZL18EXPOSURE_ITEM_TYPE` | 0x136900 | 24 |

</details>

### `/bin/ibistool`

+19 / −0 functions · +6 / −1 objects

**New functions (19)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN4Ibis20readIbisDisplacementEv` | 0x23170 | 212 |
| `_ZN4Ibis17setMoveParametersERK18IbisMoveParameters` | 0x237d8 | 216 |
| `_ZN15IbisMoveMessageC1ERK18IbisMoveParameters` | 0x29558 | 400 |
| `_ZN15IbisMoveMessageC2ERK18IbisMoveParameters` | 0x29558 | 400 |
| `_ZN15IbisMoveMessageD0Ev` | 0x299d0 | 152 |
| `_ZN9DussEvent6handleEv` | 0x41d58 | 64 |
| `_ZN9DussEvent6msgBufEv` | 0x41db8 | 68 |
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x4fa28 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x51080 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x51088 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x51088 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x51098 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x510b0 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x51160 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x51170 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x5adc8 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x5ae60 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x5ae68 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x5afe8 | 200 |

**New objects (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTS15IbisMoveMessage` | 0x802d4 | 18 |
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x8fdf0 | 27 |
| `_ZTV15IbisMoveMessage` | 0xbc798 | 64 |
| `_ZTI15IbisMoveMessage` | 0xbc920 | 24 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0xc24d0 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0xc5820 | 4 |

**Removed objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN5CJson4LensL25kJsonTagShadingCorrectionE` | 0xc5120 | 24 |

### `/bin/wmstool`

+14 / −1 functions · +3 / −0 objects

**New functions (14)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x27568 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x27578 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x27580 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x27580 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x27590 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x275a8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x27658 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x27668 | 12 |
| `_ZL11parseStringmPKhmmR7QString` | 0x2f7d8 | 536 |
| `_ZN9DussEvent6handleEv` | 0x341b8 | 64 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x4cc30 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x4ccc8 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x4ccd0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x4ce50 | 200 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZL11parseStringmPhmmR7QString` | 0x2f690 | 536 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x724ec | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0xa2230 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0xa52fc | 4 |

### `/bin/hex-writer`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x2a638 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x2a648 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x2a650 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x2a650 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2a660 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2a678 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x2a728 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x2a738 | 12 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x373f0 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x37570 | 200 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x37638 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x376d0 | 4 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x8747d | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0xe1d60 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0xe4e68 | 4 |

### `/bin/imgtool`

+12 / −0 functions · +3 / −0 objects

**New functions (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate17MetaObjectForTypeIN9HblmTypes15E_MultiShotModeEvE18metaObjectFunctionEPKNS_18QMetaTypeInterfaceE` | 0x292f8 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE13getDefaultCtrEvENUlPKNS_18QMetaTypeInterfaceEPvE_8__invokeES6_S7_` | 0x2aca8 | 8 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getCopyCtrEvENUlPKNS_18QMetaTypeInterfaceEPvPKvE_8__invokeES6_S7_S9_` | 0x2acb0 | 12 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE10getMoveCtrEvENUlPKNS_18QMetaTypeInterfaceEPvS7_E_8__invokeES6_S7_S7_` | 0x2acb0 | 12 |
| `_ZN9QtPrivate24QEqualityOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE6equalsEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2acc0 | 20 |
| `_ZN9QtPrivate24QLessThanOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE8lessThanEPKNS_18QMetaTypeInterfaceEPKvS8_` | 0x2acd8 | 20 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE13dataStreamOutEPKNS_18QMetaTypeInterfaceER11QDataStreamPKv` | 0x2ad88 | 12 |
| `_ZN9QtPrivate26QDataStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE12dataStreamInEPKNS_18QMetaTypeInterfaceER11QDataStreamPv` | 0x2ad98 | 12 |
| `_ZN9QtPrivate27QDebugStreamOperatorForTypeIN9HblmTypes15E_MultiShotModeELb1EE11debugStreamEPKNS_18QMetaTypeInterfaceER6QDebugPKv` | 0x34a58 | 152 |
| `_ZZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE17getLegacyRegisterEvENUlvE_8__invokeEv` | 0x34af0 | 4 |
| `_ZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEv` | 0x34af8 | 380 |
| `_Z41qRegisterNormalizedMetaTypeImplementationIN9HblmTypes15E_MultiShotModeEEiRK10QByteArray` | 0x34c78 | 200 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9QtPrivate16QMetaTypeForTypeIN9HblmTypes15E_MultiShotModeEE4nameE` | 0x5c2cc | 27 |
| `_ZN9QtPrivate25QMetaTypeInterfaceWrapperIN9HblmTypes15E_MultiShotModeEE8metaTypeE` | 0x81900 | 112 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_MultiShotModeEE14qt_metatype_idEvE11metatype_id` | 0x84950 | 4 |

### `/lib64/camera/plugins/hal/libdcam_cam_info_e2_ec1706_native.so`

+5 / −0 functions · +0 / −0 objects

**New functions (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_update_crop_strategy` | 0x4070 | 128 |
| `_set_crop_info` | 0x40f0 | 820 |
| `_on_switch_segment_success` | 0x4428 | 992 |
| `_allocate_dsp_resource` | 0x4a98 | 428 |
| `_free_dsp_resource` | 0x4c48 | 428 |

### `/lib64/libaaa.so`

+3 / −0 functions · +0 / −0 objects

**New functions (3)**

| Symbol | Addr | Size |
|---|---|---|
| `af_get_total_conversion_factor` | 0x35510 | 20 |
| `af_set_roi_cmd_frame` | 0xba1b8 | 48 |
| `af_get_roi_cmd_frame` | 0xba1e8 | 20 |

### `/lib64/libdcam_pp.so`

+3 / −0 functions · +1 / −0 objects

**New functions (3)**

| Symbol | Addr | Size |
|---|---|---|
| `set_liveview_mode_buf_trans` | 0x1a2c28 | 324 |
| `proc_set_sbpc_param` | 0x1a30b0 | 556 |
| `set_liveview_sbpc_param` | 0x1a3f88 | 632 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `set_liveview_mode_buf_trans_cb` | 0x256940 | 40 |

### `/lib64/librcam.so`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_Imx461BQR_ImgSysResetSensorPriv` | 0xec9f0 | 904 |
| `_Imx461BQR_SetFps` | 0xede70 | 164 |

### `/bin/dji_sec`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `sec_optee_log_saving_entry` | 0x1b20 | 804 |

### `/bin/phocusv1tool`

+1 / −0 functions · +2 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9DussEvent6handleEv` | 0x17510 | 64 |

**New objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN14PhocusProtocolL15kVolumeLabelSsdE` | 0x50e80 | 24 |
| `_ZN14PhocusProtocolL15kVolumeLabelCfeE` | 0x50ea0 | 24 |

### `/lib64/camera/plugins/disp/libdcam_disp_wayland.so`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN14WorkerThreadLV11_handleStopEv` | 0x19410 | 236 |

### `/lib64/camera/plugins/stream_filter/libdcam_dsp_allocator_stream_filter.so`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZL27updateLiveviewSpotpixelDataPK13SbpcCaliState` | 0x2d78 | 1404 |

### `/bin/dji_amt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_blackbox`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_cht`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_network`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/bin/prodconfig-tool`

+0 / −0 functions · +0 / −0 objects

### `/bin/ss_dsp_manager`

+0 / −0 functions · +0 / −0 objects

### `/bin/test_disp`

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

+0 / −0 functions · +3 / −3 objects

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `__key.37535` | 0x0 | 0 |
| `__key.37536` | 0x0 | 0 |
| `__func__.37525` | 0x50 | 18 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `__key.37533` | 0x0 | 0 |
| `__key.37534` | 0x0 | 0 |
| `__func__.37523` | 0x50 | 18 |

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

## Strings

新增字符串共 **1190** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/camera-gui`

<details><summary>新增 409 条字符串, 展示前 100 条</summary>

````text
                diskBusyTimer.restart()
                when: viewModel.diskBusy || diskBusyTimer.running
            diskBusyTimer.restart()
            if (viewModel.diskBusy) {
            when: !root.tetheredLocalStorage
            when: root.tetheredLocalStorage
        function onDiskBusyChanged() {
        id: diskBusyTimer
        if (viewModel.diskBusy) {
        root.checkSelection()
    property alias afSuccessTimerActive: af_symbol.afSuccessTimerActive
    property bool canSelect: false // Item can be selected
    property bool tetheredLocalStorage: true
    readonly property bool batteryLevelCritical: System.battery_status === HblmTypes.E_BatteryStatus_Critical
    readonly property bool batteryLevelCritical: main.batteryLevelCritical
    readonly property bool batteryStatusValid: System.battery_status !== HblmTypes.E_BatteryStatus_Max
    readonly property bool batteryStatusValid: main.batteryStatusValid
    readonly property bool batteryWarning: System.battery_status !== HblmTypes.E_BatteryStatus_Normal
    readonly property bool batteryWarning: main.batteryWarning
 @PZGI8Z
!8YZJCJQ
!RZ-JfM
!o1CFe2%,
!sZ)eLI
"14B+Ja
"@Drf8
"t2BO2
#&c7Ey?
#0Qd1r
#lnT5t[
$(^I)K6
$m:fjF\
%Cr L2c
%FMli4
&T7UtI
&ic-r#
'UboUr
('a:]-hR
(2d1P#\"@
(SsfB_qP
(yIQ?U
)7V?t2
)AKoKQ3
)rEFt:
*B/,A/
*an)s-
,k1I[E\ 
-(/z>j
----------------------------------------------
-1f7{H
-7E-Wh
-=Wl<G,
-a4l}8
-w*w.)
.-<.</l
.2<3<4l
.?kO8-
.K@UO*
.a<b<cl
.l<m<nl
.m<Co3
/=1wo.
/Zak=jT
/ggfs\~R
02Zr&J
04M@u.
0<xiX@>
0VT@>6[d
0_SuGU^"
0asIRU
0bYbl6
0nTK%,
0oZK1Y
0rZQ3p
1$3ojXO
1<E0(&Y
1GKZR,
2A(V&5_
2M(6EC_
3A clickable AE-L button will be shown in Live View.
3BjN`m
3C}.p}H=Gy
3\GO8wFQO
3ajF+Z
3hee,t
4-sg1W
42b)w{
4a[Ar@
4sU!Vs
5:OeO'Y:
5lGz+5&
5qRqSf8
5|(Rq@
6Face Detection is not supported by tethered client(s).
6O*CbY
6`(/61
6c8Dzi?
6qcjc@
7C'ty-
7[159d
````

</details>

> 其余 309 条见 `result.json`。

### `/bin/phocus`

<details><summary>新增 150 条字符串, 展示前 100 条</summary>

````text
&38DJ?O
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/daemons/phocus/src/cpp/messagehandler.cpp
/v1/metadata/<arg>/<arg>/<arg>
92b1f76
?Device
?N12QtConcurrent18StoredFunctionCallIZN5Httpd6browseERK7QStringS4_iiN9HblmTypes17E_MetadataOptionsEE3$_9JS2_S2_iiS6_EEE
Blocking capture. Not allowed
Browse
BrowseList size too large:
Client not in list
Client to remove not found in list
Destination node not found in client list
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
Failed to add client
Failed to delete files:
Failed to set metadata:
Forcing new tethered mode. Storage is busy:
HblmTypes::E_MultiShotMode
Invalid PendingCallWatcher for
Invalid offset:
N12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_16JEEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd10deleteFileERK7QStringS4_S4_E4$_17JS2_EEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_18JEEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd11deleteFilesERK7QStringRK18QHttpServerRequestE4$_19JS2_10QByteArrayEEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_20JEEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd11setMetadataERK7QStringS4_S4_RK18QHttpServerRequestE4$_21JS2_10QByteArrayEEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd12requestImageERK7QStringN9HblmTypes13E_ResolutionsENS1_13HeaderContentEO20QHttpServerResponderE4$_12JS2_S6_S7_EEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd15requestMetadataERK7QStringN9HblmTypes17E_MetadataOptionsEO20QHttpServerResponderE4$_14JS2_S6_EEE
N12QtConcurrent18StoredFunctionCallIZN5Httpd8sendFileERK7QStringjiNS1_13HeaderContentEO20QHttpServerResponderE4$_10JS2_jiS5_EEE
N12QtConcurrent18StoredFunctionCallIZN7PhocusD14onRequestImageERK14QSharedPointerI13PhocusMessageERK4QMapI7QString8QVariantEjmN9HblmTypes13E_ResolutionsERKS8_E4$_19JS8_SE_EEE
N12QtConcurrent18StoredFunctionCallIZZN5HttpdC1EjP7PhocusDENK3$_5clERK7QStringS7_S7_RK18QHttpServerRequestEUlvE_JEEE
NSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE
NSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS8_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE
NSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS8_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE
NSt3__110__function6__funcIZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS8_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSE_P10QTcpSocketE_NS_9allocatorISS_EEFvSN_SP_SR_EEE
NSt3__110__function6__funcIZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS2_21FileAllocationVersionEE4$_17NS_9allocatorIS9_EEFvP18PendingCallWatcherEEE
NSt3__110__function6__funcIZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS7_EEEEbT1_EUlPKvPvE_NS_9allocatorISI_EEFbSG_SH_EEE
NSt3__110__function6__funcIZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS7_EEEEbT1_EUlPvSF_E_NS_9allocatorISG_EEFbSF_SF_EEE
NSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEF7QFutureI19QHttpServerResponseERK18QHttpServerRequestEEE
NSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE
NSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringSA_SA_EEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISJ_EEFvO20QHttpServerResponderRK18QHttpServerRequestEEE
NSt3__110__function6__funcIZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_NS_9allocatorISI_EEF19QHttpServerResponseRK18QHttpServerRequestEEE
QFuture<QHttpServerResponse> Httpd::setMetadata(const QString &, const QString &, const QString &, const QHttpServerRequest &)
QList<HblmTypes::E_FaceDetection>
QSharedPointer(
Send image:
Set wifi:
Tethered clients:
Unsupported file type
Unsupported metadata tag
Unsupported type
Write failed
ZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_527QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_
ZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_627QHttpServerRouterViewTraitsIS5_Lb0EEJRA11_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_
ZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_727QHttpServerRouterViewTraitsIS5_Lb0EEJRA31_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_
ZN11QHttpServer9routeImplI21QHttpServerRouterRuleZN5HttpdC1EjP7PhocusDE3$_827QHttpServerRouterViewTraitsIS5_Lb0EEJRA15_KcN18QHttpServerRequest6MethodEEEEbDpOT2_OT0_EUlRK23QRegularExpressionMatchRKSB_P10QTcpSocketE_
ZN7PhocusD30FileAllocationCameraDeviceDataERK14QSharedPointerI13PhocusMessageENS_21FileAllocationVersionEE4$_17
ZN9QMetaType17registerConverterI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate33QSequentialIterableConvertFunctorIS4_EEEEbT1_EUlPKvPvE_
ZN9QMetaType19registerMutableViewI5QListIN9HblmTypes15E_FaceDetectionEE9QIterableI13QMetaSequenceEN9QtPrivate37QSequentialIterableMutableViewFunctorIS4_EEEEbT1_EUlPvSC_E_
ZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_5J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_
ZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_6JEEEDaOT_DpOT0_EUlDpOT_E_
ZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_7J7QStringS7_S7_EEEDaOT_DpOT0_EUlDpOT_E_
ZNK17QHttpServerRouter10bind_frontIRKZN5HttpdC1EjP7PhocusDE3$_8JEEEDaOT_DpOT0_EUlDpOT_E_
_ZN11QTextStreamlsEPKv
_ZN18QJsonValueConstRef9objectKeyES_
_ZNK11QJsonObject4sizeEv
_ZNK13QJsonDocument6objectEv
_ZNK13QJsonDocument8isObjectEv
_in_file_names
_in_metadata_tag
auto Httpd::setMetadata(const QString &, const QString &, const QString &, const QHttpServerRequest &)::(anonymous class)::operator()(const QString &, const QByteArray &) const
bool (anonymous namespace)::readJsonMetadata(const QJsonObject &, QVariantMap &)
bool PhocusD::addTetheredClient(PhocusMessage::Destination)
cQfWzz_z
cameraSerial
debug_options
debug_optionsChanged
disabled
disabled:
doRemove_extended
doSet_metadata
eFaceDetectionMode
enabled_face_detection_modes
enabled_face_detection_modesChanged
exposures_in_multishot_session
````

</details>

> 其余 50 条见 `result.json`。

### `/bin/camera-service`

<details><summary>新增 117 条字符串, 展示前 100 条</summary>

````text
/cali/camera/imx461lvbpc_zoom.bin
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/daemons/camera/src/cpp/calibrationdata/liveviewcalibrationdataasync.cpp
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/daemons/camera/src/cpp/calibrationdata/liveviewcalibrationdataloader.cpp
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/helpers/calibsbpc/calibsbpczoom.cpp
15IbisMoveMessage
28LiveviewCalibrationDataAsync
29LiveviewCalibrationDataLoader
92b1f76
::::::::::::::::
?34CameraPwrBtnStreamingOffTransition
?N12QtConcurrent18StoredFunctionCallIZN17DCAMCaptureEngine16setupStreamGroupEN9HblmTypes13E_StreamGroupERK14QSharedPointerI19MessageNotificationEE3$_2JS3_EEE
Accelerometer: 
Can't open json-file
Cannot allocate buffer of size:
Cannot read file into buffer
CaptureModeMultiShot
Current face detection mode is not among supported modes.
Destroying LiveviewCalibrationDataAsync
Different size in tag and array
Displacement: 
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
Failed to load zoom sbpc-data, maybe not calibrated
Failed to request IMU data isError:
Failed to request displacement isError:
Failed to set move displacement
Gyroscope:     
HblmTypes::E_MultiShotMode
Invalid MultiShot mode requested
Invalid displacement data
LiveviewCalibrationData
LiveviewCalibrationDataAsync
LiveviewCalibrationDataAsync did not quit in time.
LiveviewCalibrationDataLoader
Lowest contrast pixels will be cut:
Mismatch in file vs bufSize, need to parse or regen from json
Mismatch in version, update code, expect:
MultiShot
MultiShotBlackshot
N12QtConcurrent18StoredFunctionCallIZN24DCAMCaptureEnginePrivate8_initEcgEvE4$_35JEEE
N3x2d22StateExposureMultiShotE
N3x2d29StateCaptureMultiShotExposureE
NSt3__110__function6__funcIZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34NS_9allocatorIS3_EEFvPvRKNS_10shared_ptrI6BufferEEEEE
NSt3__110__function6__funcIZN3x2d20StateExposurePrepareC1EP6QStateE4$_18NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE
NSt3__110__function6__funcIZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE
NSt3__110__function6__funcIZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE
NSt3__110__function6__funcIZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16NS_9allocatorIS6_EEFbRK5QListI8QVariantEEEE
NSt3__110__function6__funcIZN8V1ClientC1ERK14QSharedPointerI15DussEventClientEP7QObjectE3$_0NS_9allocatorISA_EEFbRK9DussEventEEE
Number of sensor modes is not 1. num: 
Set move displacement
Supported
Temperature:   
Timed out waiting for liveview calibration data.
Total size of Zoom SBPC binary-struct:
Version mismatch, update code to parse
ZN24DCAMCaptureEnginePrivate8_initRtpEvE4$_34
ZN3x2d20StateExposurePrepareC1EP6QStateE4$_18
ZN3x2d21StateInitialDelayWaitC1EP6QStateE4$_19
ZN3x2d25StateStartExposureSessionC1EP6QStateE4$_17
ZN3x2d27StateSessionReadyForCaptureC1EP6QStateE4$_16
Zoom SBPC loaded to RAM
auto IbisControl::dumpIbisImuData()::(anonymous class)::operator()()
auto IbisControl::readIbisDisplacement()::(anonymous class)::operator()()
auto IbisControl::setMovePosition(int, float)::(anonymous class)::operator()()
bool DCAMCaptureEnginePrivate::waitUntilZoomReady(int)
bool IbisControl::setMovePosition(int, float)
bool LiveviewCalibrationDataLoader::load(const QString &)
cameraSerial
dataLoaded
enabled_face_detection_modes
enabled_face_detection_modesChanged
euxxxxxxmxxxxxxx-Exxxxxxxxx
exposures_in_multishot_session
exposures_in_multishot_sessionChanged
extensionTubeDetectedChanged
failed, errno: 
flash_recharge_delay
flash_recharge_delayChanged
imageUniqueId
is not among the supported face detection modes:
multiShotImages
multiShotSequence
multishot_control_mode
multishot_control_modeChanged
onExtensionTubeStatus
qint64 getFileSize(const QString &)
````

</details>

> 其余 17 条见 `result.json`。

### `/bin/camera-test`

<details><summary>新增 56 条字符串</summary>

````text
, Channel average:
/cali/camera/imx461lvbpc_zoom.bin
/cali/camera/imx461lvbpc_zoom.json
/home/build/jenkins/default/hardware/hbl/cam_fw/linux/helpers/calibsbpc/calibsbpczoom.cpp
92b1f76
Analysis-stage, img:
Can't open json-file
Different size in tag and array
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
Generate JSON for
HblmTypes::E_MultiShotMode
Lowest contrast pixels will be cut:
Mismatch in file vs bufSize, need to parse or regen from json
Mismatch in version, update code, expect:
NSt3__114default_deleteI20ZoomLiveviewSbpcDataEE
NSt3__120__shared_ptr_pointerIP20ZoomLiveviewSbpcDataNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE
Number of sensor modes is not 1. num: 
Result after merge:
Total size of Zoom SBPC binary-struct:
Version mismatch, update code to parse
Warmup-stage, img:
_ZNK10QJsonArray2atEx
_ZNK10QJsonArray5firstEv
_ZNK10QJsonValue5toIntEi
_ZNK10QJsonValue7toArrayEv
_ZNK11QJsonObject7isEmptyEv
_ZNK11QJsonObjectixERK7QString
bool Calibration::writeZoomLiveviewJson(const std::list<HighContrastPixel>, const QSize &)
cameraSerial
failed, errno: 
imageUniqueId
multiShotImages
multiShotSequence
static bool CalibJsonGen::generateZoom(const QString &, const QString &, uint32_t, uint32_t, uint32_t, int, int, const std::list<ContrastPixel> &)
static bool CalibJsonGen::readZoomJson(const QString &, std::list<ContrastPixel> &)
static bool CalibSbpcZoom::readZoomBinFromDisk(const QString &, char *, uint32_t)
static bool CalibSbpcZoom::writeZoomBinToDisk(const QString &, const std::shared_ptr<ZoomLiveviewSbpcData> &)
static std::shared_ptr<ZoomLiveviewSbpcData> CalibSbpcZoom::ZoomSbpcListToBinary(const std::list<HighContrastPixel> &)
static std::shared_ptr<ZoomLiveviewSbpcData> CalibSbpcZoom::readZoomBinFromDisk(const QString &)
totalRead:
void Calibration::doManualZoomLiveviewSpotPixelCalibration(sutest_body &)
````

</details>

### `/bin/odindb-send`

<details><summary>新增 55 条字符串</summary>

````text
  E_FileType_Dir(0)
  E_FileType_Image(1)
  E_FileType_ImageHeif(6)
  E_FileType_ImageJpeg(4)
  E_FileType_Max(255)
  E_FileType_Video(2)
  E_FileType_VideoRaw(3)
  E_FileType_Volume(5)
  E_SessionOptions_MultiShotBlackShot(0x00000020)
  E_SessionOptions_MultiShotExposure(0x00000010)
92b1f76
?HblmTypes::E_BatteryStatus
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_FileType file_type // 
HblmTypes::E_MultiShotMode
_in_file_type
ae_lock_touch
ae_lock_touch = %1
ae_lock_touchChanged
enabled_face_detection_modes
enabled_face_detection_modes = %1(%2)
enabled_face_detection_modesChanged
exposures_in_multishot_session
exposures_in_multishot_session = %1
exposures_in_multishot_sessionChanged
flash_recharge_delay
flash_recharge_delay = %1
flash_recharge_delayChanged
multishot_control_mode
multishot_control_mode = %1(%2)
multishot_control_modeChanged
notify_image_available(QList<QVariantMap> list_frame_info, uint exposure_id, HblmTypes::E_FileType file_type)
setAe_lock_touch
setEnabled_face_detection_modes
setExposures_in_multishot_session
setFlash_recharge_delay
setMultishot_control_mode
tethered_capture_clients
tethered_capture_clients = %1
tethered_capture_clientsChanged
````

</details>

### `/bin/camera-expose`

<details><summary>新增 41 条字符串</summary>

````text
  E_SessionOptions_MultiShotBlackShot(0x00000020)
  E_SessionOptions_MultiShotExposure(0x00000010)
92b1f76
?HblmTypes::E_BatteryStatus
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_MultiShotMode
ae_lock_touch
ae_lock_touch = %1
ae_lock_touchChanged
enabled_face_detection_modes
enabled_face_detection_modes = %1(%2)
enabled_face_detection_modesChanged
exposures_in_multishot_session
exposures_in_multishot_session = %1
exposures_in_multishot_sessionChanged
flash_recharge_delay
flash_recharge_delay = %1
flash_recharge_delayChanged
multishot_control_mode
multishot_control_mode = %1(%2)
multishot_control_modeChanged
setAe_lock_touch
setEnabled_face_detection_modes
setExposures_in_multishot_session
setFlash_recharge_delay
setMultishot_control_mode
````

</details>

### `/bin/msg2dbus`

<details><summary>新增 36 条字符串</summary>

````text
92b1f76
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_MultiShotMode
_in_file_type
ae_lock_touch
ae_lock_touchChanged
enabled_face_detection_modes
enabled_face_detection_modesChanged
exposures_in_multishot_session
exposures_in_multishot_sessionChanged
flash_recharge_delay
flash_recharge_delayChanged
multishot_control_mode
multishot_control_modeChanged
setAe_lock_touch
setEnabled_face_detection_modes
setExposures_in_multishot_session
setFlash_recharge_delay
setMultishot_control_mode
tethered_capture_clients
tethered_capture_clientsChanged
````

</details>

### `/bin/camera-system`

<details><summary>新增 33 条字符串</summary>

````text
&StateUsbConnected::onMassStorageAllowed
92b1f76
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
Error: Expected argument
HblmTypes::E_MultiShotMode
MassStorageAllowed
QList<QPair<Sysfs::SysFsItem, QString> > TouchScreenHandler::bindUnbindSysfsItem(bool) const
batteryStatusChanged
bool parseBtAuthRequest(const uint8_t *, int, QString &, QString &)
clients
filtered
int parseString(size_t, const uint8_t *, size_t, size_t, QString &)
multiShotImages
multiShotSequence
onTetheredCaptureClientsChanged
tethered_capture_clients
tethered_capture_clientsChanged
void StateUsbConnected::onMassStorageAllowed(QEvent *)
````

</details>

### `/bin/hex-writer`

<details><summary>新增 31 条字符串</summary>

````text
  E_SessionOptions_MultiShotBlackShot(0x00000020)
  E_SessionOptions_MultiShotExposure(0x00000010)
92b1f76
?HblmTypes::E_BatteryStatus
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_MultiShotMode
ae_lock_touch = %1
ae_lock_touchChanged
enabled_face_detection_modes = %1(%2)
enabled_face_detection_modesChanged
exposures_in_multishot_session = %1
exposures_in_multishot_sessionChanged
flash_recharge_delay = %1
flash_recharge_delayChanged
multishot_control_mode = %1(%2)
multishot_control_modeChanged
````

</details>

### `/lib64/camera/plugins/hal/libdcam_cam_info_e2_ec1706_native.so`

<details><summary>新增 27 条字符串</summary>

````text
CAM_HAL:DSP allocated successfully core mask:[%d], used time=[%d]us
CAM_HAL:DSP released successfully core mask:[%d], used time=[%d]us
CAM_HAL:deactivated_segment_id=[%d:%s] activated_segment_id=[%d:%s]
CAM_HAL:enter zoom-in MF mode
CAM_HAL:exit zoom-in MF mode
CAM_HAL:set DSP sbpc param, mode=[%d] offset_x=[%d] offset_y=[%d] width=[%d] height=[%d]
Comment: DSP errorflag:[%d] severity:[%d] mod_id:[%d] status_id:[%d]
Comment: set sbpc param failed, rlt=[%d] mode=[%d] offset_x=[%d] offset_y=[%d] width=[%d] height=[%d]
STATUS_OK == status
SUCCESS == rlt
_allocate_dsp_resource
_exit_zoom_in_MF_mode
_free_dsp_resource
_on_switch_segment_success
_set_crop_info
duss_osal_get_boot_time
libdcam_pp.so
libdcam_pp_v_lz
libdsp_frwk.so
libdsp_frwk_v_lz
libduml_osal.so
libduml_osal_v_lz
pd_remove_deinit
pd_remove_init
set_liveview_sbpc_param
ss_dsp_res_alloc
ss_dsp_res_free
````

</details>

### `/bin/camera-storage`

<details><summary>新增 26 条字符串</summary>

````text
92b1f76
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
Error: Ifd0 missing
HblmTypes::E_MultiShotMode
Invalid rating
T &MetadataIFD::value(MData::MdataTags) const [T = std::__1::vector<int, std::__1::allocator<int> >]
_in_file_type
cameraSerial
imageUniqueId
multiShotImages
multiShotSequence
````

</details>

### `/bin/camera-upgrade`

<details><summary>新增 24 条字符串</summary>

````text
92b1f76
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
Firmware is not supported on this hardware revision
HblmTypes::E_MultiShotMode
cameraSerial
hw rev:
imageUniqueId
multiShotImages
multiShotSequence
````

</details>

### `/lib64/weston/eagle-backend.so`

<details><summary>新增 21 条字符串</summary>

````text
%s: %d: Failed to get panel info: %d
%s: %d: Found panel connected (%dx%d)
%s: %d: No matching panel info found
%s: %s, Will find current mode: %d %d %d
%s: Done copying pixels
%s: Failed pushing to the writeback plane
%s: Failed to acquire the writeback plane
%s: Failed to allocate buffer
%s: Pushed write back frame %ux%u@%u,%u
%s: Timeout waiting for write back
_ZN11EagleOutput10readPixelsEP12duss_hal_obj20pixman_format_code_tPvjjjj
_ZN11EagleOutput24eagle_output_read_pixelsEP13weston_outputP12duss_hal_obj20pixman_format_code_tPvjjjj
_ZNK11EagleOutput16findModeByTimingERK18duss_disp_timing_t
_ZNSt3__110__list_impI17EagleOutputConfigNS_9allocatorIS1_EEE5clearEv
_ZNSt3__14listI17EagleOutputConfigNS_9allocatorIS1_EEE9push_backERKS1_
__floatditf
__letf2
__lttf2
__multf3
__sfp_handle_exceptions
usleep
````

</details>

### `/bin/ibistool`

````text
15IbisMoveMessage
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_MultiShotMode
Invalid displacement data
static bool IbisResponseParser::parseSensorDisplacement(const QSharedPointer<IbisRequest> &, IbisMessageTypes::displacementResponse &)
````

### `/bin/wmstool`

````text
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_MultiShotMode
bool parseBtAuthRequest(const uint8_t *, int, QString &, QString &)
int parseString(size_t, const uint8_t *, size_t, size_t, QString &)
````

### `/bin/dji_sec`

````text
/dev/tzlog
[SYS common] debug is turned off, bypass log saving!
[SYS common] init bb failed %d
[SYS common] open /dev/tzlog failed %d
[SYS common] open bb failed %d
[SYS common] out of memory
[SYS common] read tzlog failed %d
[SYS common] record bb failed %d
__open_2
__read_chk
dev_info_is_secure_debug
dji_sec_optee_log
duss_bb_channel_open
duss_bb_deinitialize
duss_bb_initialize
duss_bb_record_raw
optee_log_chn
sec_optee_log_saving_entry
````

### `/bin/imgtool`

````text
E_DebugOption_MultiShot
E_DebugOption_TouchPointerHandlers
E_DriveModes_MultiShot
E_ExposureStatus_MultiShotActive
E_MultiShotMode
E_MultiShotMode_Auto16
E_MultiShotMode_Auto16B
E_MultiShotMode_Auto4
E_MultiShotMode_Auto4B
E_MultiShotMode_Auto6
E_MultiShotMode_Auto6B
E_MultiShotMode_Max
E_MultiShotMode_SingleShot
E_SessionOptions_MultiShotBlackShot
E_SessionOptions_MultiShotExposure
E_StorageStatus_Browsing
HblmTypes::E_MultiShotMode
````

### `/lib64/libdcam_pp.so`

````text
00:17:10
CP_PD_REMOVE_ERROR: %s pd_remove async_wait failed
CP_PD_REMOVE_ERROR: %s set_liveview_mode process failed
CP_PD_REMOVE_ERROR: proc_set_liveview_mode() failed: %d 
CP_PD_REMOVE_ERROR: proc_set_liveview_mode: active_dev_num must be 1  
CP_PD_REMOVE_INFO: dsp_id = %d, liveview_mode = %d
CP_PD_REMOVE_INFO: dsp_id = %d, zoom_spot_pixel_size = %d, zoom_spot_pixel_buf = %p
CP_PD_REMOVE_INFO: proc_set_liveview_mode start! 
CP_PD_REMOVE_INFO: proc_set_liveview_mode total time: %lu us   ----------
CP_PD_REMOVE_INFO: roi = %d %d %d %d
May 25 2024
proc_set_sbpc_param
set_liveview_mode_buf_trans
set_liveview_mode_buf_trans_cb
set_liveview_sbpc_param
````

### `/lib64/camera/plugins/stream_filter/libdcam_dsp_allocator_stream_filter.so`

````text
DSPAllocator: : lv normal bad pixels: %d
DSPAllocator: : pd_remove_init, failed: %d
DSPAllocator: : pd_remove_set_spot_pixel, failed: %d
DSPAllocator: : zoom sbpc: ver:%u, WxH: %u x %u, ROI WxH: %u x %u, StepX: %u, StepY: %u
STATUS_OK == status
SUCCESS == result
dspf_virt_addr
duss_hal_mem_get_phys_addr
duss_hal_mem_map
duss_hal_mem_unmap
libduml_hal.so
libduml_hal_v_lz
updateLiveviewSpotpixelData
````

### `/lib64/libduml_hal_cam.so`

````text
(isp_crop_params.left + isp_crop_params.width) <= (active_size->origin_x + active_size->width)
(isp_crop_params.top + isp_crop_params.height) <= (active_size->origin_y + active_size->height)
CAM_HAL:set crop info success, total use [%lu]us
CAM_HAL:set product crop info: start_x[%d] start_y[%d] width[%d] height[%d]
CAM_HAL:set sensor crop info: crop_x[%d] crop_y[%d]
CAM_HAL:set subdev[%s] crop info: left[%d] top[%d] width[%d] height[%d]
CAM_HAL:update crop strategy by product: old_params:[start_x:%d start_y:%d width:%d height:%d] new_params:[start_x:%d start_y:%d width:%d height:%d]
Comment: set subdev[%s] crop info failed, rlt=[%d]
crop_offset
isp_crop_params.height
isp_crop_params.width
````

### `/bin/phocusv1tool`

````text
_ZN10QByteArray11reallocDataExN10QArrayData16AllocationOptionE
eFaceDetectionMode
kClientSupportedFaceDetectionCamParam
kDriveModeMultiShot
kExpAdjustStepSizeCamParam
kFaceDetectionAuto
kFaceDetectionCamParam
kFaceDetectionManual
kFaceDetectionOff
````

### `/bin/dji_network`

````text
ec1706,00.00.07.72,20240508164605
str_char_check
wms: invalid char:%c, should limit to:[0~9 a~z A~Z _ -]
wms: wifi password check fail!
wms: wifi ssid check fail!
````

### `/lib64/libaaa.so`

````text
af_get_roi_cmd_frame
af_get_total_conversion_factor
af_set_roi_cmd_frame
e2d8d74
````

### `/lib64/libgip.so`

````text
?zebra
AB30RG16NV12NV16YU12YU24IMG4IMG3N3GIP19GammaEncodeDLogBaseE
MbP?.N
N3GIP10FilterPrivE
````

### `/lib64/libduml_frwk.so`

````text
00:16:20
00:16:21
May 25 2024
````

### `/lib64/libduml_orte.so`

````text
00:17:58
May 25 2024
orte 0.3.4, compiled: May 25 2024 00:17:58
````

### `/lib64/librcam.so`

````text
5c0df5bb
5c7a7c84
_Imx461BQR_ImgSysResetSensorPriv
````

### `/lib64/libweston.so`

````text
-0038/input/
0000111122223333444455556666777788889999::::;;;;<<<<====>>>>da
l)*d8hi,.*)8ef1$*0u*081i*1fP
````

### `/bin/dji_amt`

````text
00:17:53
May 25 2024
````

### `/bin/dji_blackbox`

````text
00:17:54
May 25 2024
````

### `/bin/dji_sys`

````text
00:19:43
May 25 2024
````

### `/bin/ss_dsp_manager`

````text
10:21:11
Mar 30 2024
````

### `/lib64/camera/plugins/disp/libdcam_disp_wayland.so`

````text
WAYLAND_DISP_LV_WORKER: %s
_ZN14WorkerThreadLV11_handleStopEv
````

### `/lib64/libdsp_frwk.so`

````text
10:12:38
Mar 30 2024
````

### `/lib64/libproxy_nn_client.so`

````text
00:19:42
May 25 2024
````

### `/bin/prodconfig-tool`

````text
5c7a7c84
````

### `/lib64/camera/plugins/stream_filter/libdcam_common_filter.so`

````text
STILL_REPROCESS_FILTER: LSC is corrected
````

### `/lib64/libdcam_metadata_util.so`

````text
DCAM_STATUS_LENS_LSC_CORRECTED
````

### `/bin/dji_cht`

````text
````

### `/bin/test_disp`

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

## Scripts & Config

共 10 个脚本/配置变更, 267 行 unified diff（context=3, 预算上限 2000 行）。

### `/bin/collect_logs.sh`

12 行

````diff
--- a//bin/collect_logs.sh
+++ b//bin/collect_logs.sh
@@ -78,6 +78,9 @@
 
     header "top"
     top -H -n1
+
+    header "wifi whitelist"
+    cat /data/misc/wifi/whitelist.conf
 
     header "prodconfig"
     # prodconfig output is not sent to stdout so add workaround here
````

### `/bin/program_nodes.sh`

55 行

````diff
--- a//bin/program_nodes.sh
+++ b//bin/program_nodes.sh
@@ -26,6 +26,10 @@
 X2D_100C_PRODUCT_TYPE_NUM=4
 # Product type number for CFV 100C
 CFV_100C_PRODUCT_TYPE_NUM=5
+# CFV 100C HW revision 4
+CFV_100C_HW_REV_NUM_V4=3
+# CFV 100C HW revision 5
+CFV_100C_HW_REV_NUM_V5=4
 
 # Function: product_version
 # ==================================
@@ -39,6 +43,20 @@
     PRODUCT_TYPE_NUM=$(($PRODUCT_TYPE))
 
     echo $PRODUCT_TYPE_NUM
+}
+
+# Function: hardware_revision
+# ==================================
+# This function returns the hardware revision number
+hardware_revision()
+{
+    # Get the hardware version
+    #  - Format 04.04.01.04 (Product type, PCB/Hw type, ddr type, YY)
+    HW_INFO=$(getprop ro.boot.hw_version)
+    HW_REV=${HW_INFO:3:2}
+    HW_REV_NUM=$(($HW_REV))
+
+    echo $HW_REV_NUM
 }
 
 # Function: wait_for_exmcu_to_become_active
@@ -87,11 +105,16 @@
 /system/bin/send_fw --partition BootUpgrade --file /etc/firmware/exMCUloader.cont
 
 product=$(product_version)
+hw_revision=$(hardware_revision)
 if [ $product -eq $CFV_100C_PRODUCT_TYPE_NUM ]; then
-    if [ -f /system/bin/upgrade_cpld.sh ]; then
-        cpld_fw="/etc/firmware/ec2107_cpld.bit"
-        NODE="CPLD"
-        /system/bin/upgrade_cpld.sh ${cpld_fw}
+    if [ $hw_revision -eq $CFV_100C_HW_REV_NUM_V4 ] || [ $hw_revision -gt $CFV_100C_HW_REV_NUM_V5 ]; then
+        echo "Skip upgrade CPLD for CFV 100C, HW revision: $hw_revision"
+    else
+        if [ -f /system/bin/upgrade_cpld.sh ]; then
+            cpld_fw="/etc/firmware/ec2107_cpld.bit"
+            NODE="CPLD"
+            /system/bin/upgrade_cpld.sh ${cpld_fw}
+        fi
     fi
 fi
 
````

### `/bin/start_blackbox_logs.sh`

11 行

````diff
--- a//bin/start_blackbox_logs.sh
+++ b//bin/start_blackbox_logs.sh
@@ -63,7 +63,7 @@
 /system/bin/dji_kmsg -l 10M -d $BB_SYS_DIR/ -n 8 &
 
 # Fatal errors, up to 32MB
-logcat -v time -f $BB_SYS_DIR/fatal.log -r32768 -n2 *:E hostapd bt_bsa_app &
+logcat -v time -f $BB_SYS_DIR/fatal.log -r32768 -n2 *:E &
 
 # Upgrade log, up to 2MB
 logcat -v time -f $BB_UPGRADE_DIR/cim_upgrade.log -r2048 -n6 camera-upgrade:D camera-gui:D *:S &
````

### `/bin/test_check_versions.sh`

26 行

````diff
--- a//bin/test_check_versions.sh
+++ b//bin/test_check_versions.sh
@@ -16,6 +16,14 @@
 source test_common.sh
 
 product=$(product_detect)
+hw_revision=$(product_hwrev)
+
+EC2107_JDI_VERSIONS="00 01 02 04"
+if echo $EC2107_JDI_VERSIONS | grep -q $hw_revision; then
+    EC2107_HAS_CPLD=true
+else
+    EC2107_HAS_CPLD=false
+fi
 
 E2_VERSION=`odindb-send -a 2>&1 | grep "version:" | cut -f 4 -d ' '`
 if [ $? -ne 0 ]; then
@@ -29,7 +37,7 @@
     log_result $RET_ERROR
 fi
 
-if [ "$product" == "EC2107" ]; then
+if [ "$product" == "EC2107" ] && $EC2107_HAS_CPLD ; then
     test_check_cpld_version.sh > /dev/null
     if [ $? -ne 0 ]; then
         echo "CPLD version mismatch!"
````

### `/bin/test_common.sh`

21 行

````diff
--- a//bin/test_common.sh
+++ b//bin/test_common.sh
@@ -78,6 +78,18 @@
     echo $product_name
 }
 
+# Function to detect the HV version
+function product_hwrev()
+{
+    local hw_rev
+    if ! hw_rev=$(unrd HW_VER); then
+        echo "Unknown"
+    fi
+
+    # Extract hw_rev from version string
+    echo "${hw_rev}" | cut -d. -f2
+}
+
 # Function to export GPIO and return its directory
 # Args:
 # * $1: GPIO number
````

### `/bin/test_touch_link.sh`

69 行

````diff
--- a//bin/test_touch_link.sh
+++ b//bin/test_touch_link.sh
@@ -11,22 +11,64 @@
 # be held in confidence and will not be reproduced in whole or in part without
 # written permission from Victor Hasselblad AB.
 #
-#HX8527 touch controller link test
+# touch controller link test for various I2C touch controllers
 
 source test_common.sh
 
 product=$(product_detect)
+hw_revision=$(product_hwrev)
+
+EC2107_JDI_VERSIONS="00 01 02 04"
+if echo $EC2107_JDI_VERSIONS | grep -q $hw_revision; then
+    EC2107_HAS_JDI=true
+else
+    EC2107_HAS_JDI=false
+fi
 
 if [ "$product" == "EC1706" ]; then
     DATA_BUS=7
     DATA_ADDRESS=0x48
     IC_PART_NUM_REGISTER=0xd1
     IC_PART_NUM_VALUE=0x05
-elif [ "$product" == "EC2107" ]; then
+elif [ "$product" == "EC2107" ] && [ "$EC2107_HAS_JDI" == "true" ]; then
     DATA_BUS=7
     DATA_ADDRESS=0x55
     IC_PART_NUM_REGISTER=0x20
     IC_PART_NUM_VALUE=0x00
+elif [ "$product" == "EC2107" ]; then
+    # We have a tricky case where two different touches might be in use
+    DATA_BUS=7
+    DATA_ADDRESS=0x38
+    IC_CHIP_ID_REGISTER=0xA3
+    IC_PART_NUM_VALUE=0x52
+    TEXT_NAME="focal tech touch controller"
+
+    val=$(busybox i2cget -f -y $DATA_BUS $DATA_ADDRESS $IC_CHIP_ID_REGISTER)
+    if [ $? -eq 0 ]; then
+        if [ "$val" == "$IC_PART_NUM_VALUE" ]; then
+            echo "Detected $TEXT_NAME"
+            log_result $RET_SUCCESS
+        else
+            echo "Failed to detect $TEXT_NAME"
+            log_result $RET_ERROR
+        fi
+    fi
+
+    echo "No response for Focal tech will test goodix"
+    DATA_ADDRESS=0x5D
+    PID_NUM_VALUE=0x35
+    TEXT_NAME="goodix touch controller"
+
+    # goodix uses 16 bit addressing, so do some trick with i2cset first
+    busybox i2cset -f -y $DATA_BUS $DATA_ADDRESS 0x45 0x35
+    val=$(busybox i2cget -f -y $DATA_BUS $DATA_ADDRESS)
+    if [ "$val" == "$PID_NUM_VALUE" ]; then
+        echo "Detected $TEXT_NAME"
+        log_result $RET_SUCCESS
+    else
+        echo "Failed to detect $TEXT_NAME"
+        log_result $RET_ERROR
+    fi
 elif [ "$product" == "EC2108" ]; then
     echo "Not support EC2108 yet!!!"
     log_result $RET_ERROR
````

### `/build.prop`

13 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,7 +1,7 @@
 
-ro.vendor.build.date=Sat Nov 25 03:18:48 CST 2023
-ro.vendor.build.date.utc=1700853528
-ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/10331:userdebug/test-keys
+ro.vendor.build.date=Sat May 25 00:14:56 CST 2024
+ro.vendor.build.date.utc=1716567296
+ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/13682:userdebug/test-keys
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
-ro.dji.build.version=10.00.16.39
+ro.dji.build.version=10.00.19.05
 persist.dji.storage.exportable=0
 ro.logd.kernel=false
 ro.logd.size.stats=64K
````

### `/etc/dji.json`

31 行

````diff
--- a//etc/dji.json
+++ b//etc/dji.json
@@ -44,16 +44,27 @@
                   {"name":"ros_log",     "id":7,        "active":1,"max_flow":8000,"input":"","output":["ros_log"]}
             ]
         },
+        "dji_sec_optee_log":{
+            "channels":[
+                {"name":"optee_log_chn", "id":1, "active":1, "max_flow":1000, "input":"", "output":["optee_log"]}
+            ]
+        },
         "storage":{
             "dir_layout":"by_flight",
             "prefix_name":"flight",
             "flight_limit":9999,
             "partitions":[
-                {"name":"blackbox", "id":1, "root_dir":"/blackbox",   "space_limit":4500},
+                {"name":"blackbox", "id":1, "root_dir":"/blackbox",   "space_limit":4500,
+                    "mod_dir":[
+                        {"name":"optee_log", "active":1, "space_limit":10}
+                    ]
+                },
                 {"name":"usb-ssd",  "id":2, "root_dir":"/tmp/exfat",  "space_limit":21200}
             ]
         },
         "output_info": [
+            {"name": "optee_log",  "active": 1, "type":"file",
+                     "file":{"storage":"blackbox", "mod_dir":"optee_log", "prefix": "optee", "dio" : 0, "encrypt":0, "file_num_limit":3, "file_max_size": 3, "space_limit": 10, "cache_size": 0, "burst_size": 0}},
             {"name": "nn_server", "active": 1, "type":"file",
                      "file":{"storage":"blackbox", "mod_dir":"dji_nn_server",   "prefix": "server", "muxed" : 1, "file_num_limit":100, "file_max_size": 50,  "space_limit": 2200, "cache_size": 512}},
             {"name": "nnf_log", "active": 1, "type":"file",
````

### `/etc/lens_config.json`

18 行

````diff
--- a//etc/lens_config.json
+++ b//etc/lens_config.json
@@ -22,7 +22,6 @@
       "- lens_version: Version of lens (defined in lensspecs.h).",
       "- lens_type: The lens type of the CV lenses, the bit fields is described in 1000465_KSD.",
       "- optics_group: Name of optics group containing distance marks etc",
-      "- shading_correction: image data for some lenses are in-camera shading corrected, this proporty is used to signal that.",
       "- supported_cameras: Some lenses can only be used with specific cameras.",
       "- default_fixed_lens: Fixed lens camera name which this lens is the default lens for in GUI.",
       "- fixed_lens_camera: The fixed lens camera model used for this lens.",
@@ -2153,7 +2152,6 @@
         "lens_version": 1,
         "meta_name": "XCD 20-35V",
         "mount_type": "X",
-        "shading_correction": 1,
         "name": "XCD 20-35V",
         "ibis_constants": [
         {
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
| `/bin/camera-expose` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.3 MB | +5.5 KB | system |
| `/bin/camera-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.2 MB | 45.3 MB | +73.2 KB | system |
| `/bin/camera-service` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.7 MB | 10.8 MB | +82.3 KB | system |
| `/bin/camera-storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.3 MB | 3.3 MB | +96 B | system |
| `/bin/camera-system` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 MB | 7.6 MB | +4.4 KB | system |
| `/bin/camera-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +2.9 KB | system |
| `/bin/camera-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | -416 B | system |
| `/bin/cat_wifi_param.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/check_and_format.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 702 B | 702 B | +0 B | system |
| `/bin/check_secure_debug` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/bin/cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/codec_yuv_generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/collect_logs.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.8 KB | 5.9 KB | +68 B | system |
| `/bin/copy_script_files` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.4 KB | 7.6 KB | +227 B | system |
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
| `/bin/dji_network` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 278.5 KB | 278.5 KB | +8 B | system |
| `/bin/dji_production_check_h26x.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | system |
| `/bin/dji_sec` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 72.8 KB | 72.8 KB | +16 B | system |
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
| `/bin/hex-writer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +3.1 KB | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 786.2 KB | 786.2 KB | +0 B | system |
| `/bin/ibistool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +3.3 KB | system |
| `/bin/imgtool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 876.8 KB | 879.2 KB | +2.4 KB | system |
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
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.7 MB | 2.7 MB | +5.7 KB | system |
| `/bin/nnf_gtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525.3 KB | 525.3 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.6 KB | 133.6 KB | +0 B | system |
| `/bin/odindb-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.0 MB | 4.0 MB | +71.0 KB | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 MB | 8.3 MB | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.0 MB | 3.1 MB | +104.1 KB | system |
| `/bin/phocusv1tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 340.4 KB | 341.3 KB | +936 B | system |
| `/bin/pidstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 867.0 KB | 867.0 KB | +0 B | system |
| `/bin/ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/pinmux` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/bin/proc_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 409.2 KB | 409.1 KB | -56 B | system |
| `/bin/program_nodes.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.3 KB | 4.0 KB | +712 B | system |
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
| `/bin/ss_dsp_manager` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 265.3 KB | 265.3 KB | -8 B | system |
| `/bin/start_blackbox_logs.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.5 KB | 3.4 KB | -19 B | system |
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
| `/bin/test_check_versions.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 KB | 1.5 KB | +202 B | system |
| `/bin/test_cnn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/test_common.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.4 KB | 7.6 KB | +227 B | system |
| `/bin/test_common_disk.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/test_cpld_flash_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/test_ddr_e2.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/test_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 695 B | 695 B | +0 B | system |
| `/bin/test_disp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 265.8 KB | 265.8 KB | +0 B | system |
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
| `/bin/test_touch_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 KB | 2.4 KB | +1.3 KB | system |
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
| `/bin/wmstool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.0 MB | 1.1 MB | +2.5 KB | system |
| `/bin/x2bursttest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/x2d_cal_eng_googletest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 265.3 KB | 265.3 KB | -8 B | system |
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
| `/etc/dji.json` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 55.5 KB | 56.1 KB | +616 B | system |
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
| `/etc/firmware/exMCU_cfv.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 412.5 KB | 413.6 KB | +1.0 KB | system |
| `/etc/firmware/exMCU_x2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +1.0 KB | system |
| `/etc/firmware/exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B | system |
| `/etc/firmware/goodix_cfg_group.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 930 B | +930 B | system |
| `/etc/firmware/goodix_firmware.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 70.2 KB | +70.2 KB | system |
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
| `/etc/lens_config.json` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 154.6 KB | 154.5 KB | -162 B | system |
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
| `/firmware/dspf/ss_dsp0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +34.0 KB | vendor |
| `/firmware/dspf/ss_dsp0.lin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 228.7 KB | 228.9 KB | +203 B | vendor |
| `/firmware/dspf/ss_dsp1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.5 MB | +34.0 KB | vendor |
| `/firmware/dspf/ss_dsp1.lin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 228.8 KB | 229.0 KB | +203 B | vendor |
| `/firmware/dspf/ss_dsp2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.5 MB | +34.0 KB | vendor |
| `/firmware/dspf/ss_dsp2.lin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 228.8 KB | 229.0 KB | +203 B | vendor |
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
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 373.8 KB | 373.9 KB | +56 B | system |
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
| `/lib/modules/focaltech_tp.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 2.7 MB | +2.7 MB | system |
| `/lib/modules/focaltp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/ftdi_sio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 503.8 KB | 503.8 KB | +0 B | system |
| `/lib/modules/goodix_core.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 1.4 MB | +1.4 MB | system |
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
| `/lib/modules/vc_decoder.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 405.5 KB | 405.9 KB | +344 B | system |
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
| `/lib64/camera/plugins/disp/libdcam_disp_e2_lcdc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 135.1 KB | 135.1 KB | +8 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_null.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.8 KB | 197.7 KB | -16 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland_gfx.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.2 KB | 197.2 KB | +8 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland_preview.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.5 KB | 197.5 KB | +0 B | system |
| `/lib64/camera/plugins/hal/libdcam_cam_info_e2_ec1706_native.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 142.1 KB | 142.2 KB | +104 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_hevc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_jpeg.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/lib64/camera/plugins/ienc/libdcam_ienc_sw.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/lib_frog_e2_ec1706_native.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.7 KB | 84.7 KB | +0 B | system |
| `/lib64/camera/plugins/libdcam_x2d_cal_eng.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.4 KB | 67.4 KB | +0 B | system |
| `/lib64/camera/plugins/link_node/libdcam_container_cache_link_node.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/mctf/libdcam_mctf.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/pp_algo/libdcam_pp_e2_hiso.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.1 KB | 131.1 KB | +8 B | system |
| `/lib64/camera/plugins/pp_algo/libdcam_pp_rdns_grain.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +8 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_raw_reprocess.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_common.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 195.8 KB | 195.8 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_general.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_x2d.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_still_yuvraw_zsl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/shooter/libdcam_shooter_video_single.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.6 KB | 131.6 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_async_deconv_blend_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_async_mctf_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_common_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 388.7 KB | 388.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_dsp_allocator_stream_filter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.3 KB | 67.4 KB | +48 B | system |
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
| `/lib64/libMessageTransport.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.9 KB | 66.8 KB | -8 B | system |
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
| `/lib64/lib_vc_encoder.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 584.5 KB | 584.5 KB | -8 B | system |
| `/lib64/libaaa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 MB | 10.1 MB | -48 B | system |
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
| `/lib64/libdcam_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | -24 B | system |
| `/lib64/libdcam_image_file_writer_base.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 130.8 KB | 130.8 KB | -8 B | system |
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
| `/lib64/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.3 MB | 2.3 MB | +64 B | system |
| `/lib64/libdcam_protobuf_dbginfo.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | system |
| `/lib64/libdcam_protobuf_metadata.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 132.1 KB | 132.1 KB | +0 B | system |
| `/lib64/libdcam_shooter_base_still.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libdcam_storage.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/lib64/libdcam_video_bps_parser.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdcamecg_process.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libdcs.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.5 KB | 131.5 KB | +0 B | system |
| `/lib64/libdebuggerd_client.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libdiskconfig.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libdisplay-server.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 195.9 KB | 195.9 KB | +0 B | system |
| `/lib64/libdji_codec_heif.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.7 KB | 131.7 KB | +0 B | system |
| `/lib64/libdji_secure.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 388.5 KB | 388.5 KB | +0 B | system |
| `/lib64/libdl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.9 KB | 65.9 KB | +0 B | system |
| `/lib64/libdsp_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 133.8 KB | 133.8 KB | +0 B | system |
| `/lib64/libduml_async_remux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.2 KB | 131.2 KB | +0 B | system |
| `/lib64/libduml_audio.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.6 KB | 198.6 KB | +0 B | system |
| `/lib64/libduml_databuffer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.7 KB | 130.7 KB | +0 B | system |
| `/lib64/libduml_dn.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_dsocket.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_f2d.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libduml_fastrtps.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 MB | 4.9 MB | +0 B | system |
| `/lib64/libduml_fb.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_ffremux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 MB | 1.5 MB | +0 B | system |
| `/lib64/libduml_hal.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 578.9 KB | 578.9 KB | +0 B | system |
| `/lib64/libduml_hal_cam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 741.5 KB | 741.5 KB | -24 B | system |
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
| `/lib64/libgip.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 196.9 KB | 196.9 KB | -8 B | system |
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
| `/lib64/librcam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | +152 B | system |
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
| `/lib64/libweston.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | -16 B | system |
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
| `/lib64/weston/eagle-backend.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +136 B | system |
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
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | -46 B | system |
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
