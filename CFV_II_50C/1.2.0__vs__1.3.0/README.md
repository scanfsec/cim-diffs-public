# CFV II 50C: 1.2.0 ➜ 1.3.0

> 生成时间: 2026-10-07T05:24:24 · CIM 日期: 2020-05-29 ➜ 2020-07-15 · 条目: 4 ➜ 4 · 源: `CFV_II_50C_v1_2_0.cim` ➜ `CFV_II_50C_v1_3_0.cim`

## Summary

文件树 +2/-2/~177；CIM 条目 +0/-0/~2；OTA 镜像 ~5 变更 / 0 未变；符号 +186/-68 funcs, +649/-597 objs；新增字符串 740 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `hbmanual.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 64.0 MB | 64.0 MB | +0 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 148.9 MB | 149.0 MB | +93.3 KB |
| `hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 2 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 2

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 MB | 7.3 MB | +0 B |
| `recovery.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.2 MB | 22.2 MB | +192 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 229.9 MB | 230.2 MB | +236.0 KB |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.7 MB | 22.7 MB | -8.0 KB |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 5 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `lib` | 0 | 0 | 66 | 139 | 0 |
| `bin` | 0 | 0 | 41 | 372 | 0 |
| `firmware` | 0 | 0 | 37 | 0 | 0 |
| `etc` | 2 | 2 | 16 | 142 | 0 |
| `ta` | 0 | 0 | 15 | 0 | 0 |
| `(root)` | 0 | 0 | 2 | 0 | 0 |
| `usr` | 0 | 0 | 0 | 29 | 0 |
| `xbin` | 0 | 0 | 0 | 38 | 0 |

明细 901 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+186 / −68** functions, **+649 / −597** objects（50 个变更 ELF, 另有 56 个未列出）。

### `/bin/camservice`

+58 / −32 functions · +17 / −7 objects

**New functions (58)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNKSt3__121__basic_string_commonILb1EE20__throw_length_errorEv.isra.597` | 0x18a18 | 96 |
| `_ZNKSt3__18functionIFvN5rxcpp10subscriberINS_10shared_ptrIN3dji6camera11FrameBufferEEENS1_8observerIS7_vvvvEEEEEEclESA_.isra.1000.part.1001` | 0x18a78 | 60 |
| `ionhelper_get_heap_id` | 0x197f8 | 16 |
| `_ZN3C2d8InstanceC1Ev` | 0x2a244 | 836 |
| `_ZN3C2d8InstanceC2Ev` | 0x2a244 | 836 |
| `_ZN3C2d8InstanceD1Ev` | 0x2a588 | 140 |
| `_ZN3C2d8InstanceD2Ev` | 0x2a588 | 140 |
| `_ZN3C2d8Instance4drawER19duss_hal_2d_param_t` | 0x2a614 | 612 |
| `_ZN16CamserviceObject13capture_imageEjRK12QDBusMessage` | 0x2b764 | 12 |
| `_ZN14CamserviceImpl16zoomPointChangedEj` | 0x33b90 | 12 |
| `_ZN14CamserviceImpl22videoStreamModeChangedEN9HblmTypes13E_VideoStreamE` | 0x33b9c | 24 |
| `_ZL7capturejNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEE` | 0x33bd0 | 52 |
| `_ZL13getOutputTypeN9HblmTypes13E_ImageFormatE` | 0x34568 | 988 |
| `_ZL11frameFormatRNSt3__110shared_ptrIN3dji6camera11FrameBufferEEE.part.514` | 0x34c80 | 272 |
| `_ZN9QtPrivate8RefCount5derefEv.part.545` | 0x34df8 | 32 |
| `_ZN7QStringD2Ev.part.546` | 0x34e18 | 24 |
| `_ZNKSt3__18functionIFvRKN5rxcpp10schedulers11schedulableEEEclES5_.isra.564` | 0x34e30 | 80 |
| `_ZN5QListINSt3__15tupleIJjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.661` | 0x34e80 | 68 |
| `_ZN5QListINSt3__15tupleIJN9HblmTypes14E_VideoControlEjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.665` | 0x34ec4 | 68 |
| `_ZN14CamserviceImpl9setStatusEN9HblmTypes21E_CameraServiceStatusE.part.479` | 0x351ac | 388 |
| `_ZN14CamserviceImpl13wbTintChangedEi.part.584` | 0x356c0 | 768 |
| `_ZN14CamserviceImpl13wbTempChangedEi.part.583` | 0x359fc | 772 |
| `_ZL13setOutputTypeNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS2_10OutputTypeE` | 0x361fc | 476 |
| `_ZZN14CamserviceImpl20onPreviewFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.547` | 0x36e50 | 764 |
| `_ZZN14CamserviceImpl17onFullFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.548` | 0x37198 | 780 |
| `_ZZN14CamserviceImpl17onJpegFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.549` | 0x374f8 | 764 |
| `_ZN8QMapNodeIj5QPairIi10QByteArrayEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.752` | 0x37840 | 2528 |
| `_ZNK14CamserviceImpl12video_statusEv.localalias.1880` | 0x3b12c | 156 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN14CamserviceImpl18imageFormatChangedEN9HblmTypes13E_ImageFormatEEUlvE_Li0ENS_4ListIJEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x3b298 | 656 |
| `_ZN14CamserviceImpl18imageFormatChangedEN9HblmTypes13E_ImageFormatE` | 0x3b528 | 928 |
| `_ZN5QListI4QMapI7QString8QVariantEE7deallocEPN9QListData4DataE.isra.719` | 0x3df1c | 180 |
| `_ZN14CamserviceImpl15doCapture_imageEjRK12QDBusMessage` | 0x40d80 | 1256 |
| `_ZNK5rxcpp10schedulers6worker8scheduleIRNS_6detail15safe_subscriberINS_9operators6detail13lift_operatorINSt3__110shared_ptrIN3dji6camera11FrameBufferEEENS_18dynamic_observableISD_EENS6_10observe_onISD_NS_21observe_on_one_workerEEEEENS_10subscriberISD_NS_8observerISD_NS3_22stateless_observer_tagEZN14CamserviceImplC4EP7QObjectRSH_OK7QStringEUlSD_E6_vvEEEEEEJEEENS8_9enable_ifIXaaoosrNS0_6detail18is_action_functionIT_EE5valuesrNS_15is_subscriptionIS12_EE5valuentsrNS_14is_schedulableIS12_EE5valueEvE4typeEOS12_DpOT0_` | 0x469b8 | 692 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlbE12_clEb.isra.1874` | 0x526d8 | 3144 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEE6_clESD_.isra.1877` | 0x53330 | 360 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_VideoStreamELb1EE8DestructEPv` | 0x537f8 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_VideoStreamELb1EE9ConstructEPvPKv` | 0x537fc | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_ImageFormatELb1EE8DestructEPv` | 0x53810 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_ImageFormatELb1EE9ConstructEPvPKv` | 0x53814 | 20 |
| `_ZN9QtPrivate11QSlotObjectIM14CamserviceImplFvN9HblmTypes13E_ImageFormatEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x546f8 | 160 |
| `_ZN9QtPrivate11QSlotObjectIM14CamserviceImplFvjENS_4ListIJjEEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x54798 | 160 |
| `_ZN9QtPrivate11QSlotObjectIM14CamserviceImplFvN9HblmTypes13E_VideoStreamEENS_4ListIJS3_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x54838 | 160 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEE10runFunctorEv` | 0x55fa4 | 192 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_E10runFunctorEv` | 0x56064 | 188 |
| `_Z17qRegisterMetaTypeIN9HblmTypes13E_VideoStreamEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x59e50 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes13E_ImageFormatEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x59f88 | 312 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_ED1Ev` | 0x5bd10 | 264 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_ED2Ev` | 0x5bd10 | 264 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_ED1Ev` | 0x5be18 | 8 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEED1Ev` | 0x5bf30 | 264 |

<details><summary>… 另 8 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEED2Ev` | 0x5bf30 | 264 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEED1Ev` | 0x5c038 | 8 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEED0Ev` | 0x5c158 | 272 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEED0Ev` | 0x5c268 | 8 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_ED0Ev` | 0x5c270 | 272 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_ED0Ev` | 0x5c380 | 8 |
| `_ZN5rxcpp4util6detail8unwinderIZNKS_9operators6detail10observe_onIN3dji6camera15RecordingStatusENS_21observe_on_one_workerEE19observe_on_observerINS_10subscriberIS8_NS_8observerIS8_vvvvEEEEE16observe_on_state17ensure_processingERNSt3__111unique_lockINSI_5mutexEEEEUlvE1_ED1Ev` | 0x61fec | 44 |
| `_ZN5rxcpp4util6detail8unwinderIZNKS_9operators6detail10observe_onIN3dji6camera15RecordingStatusENS_21observe_on_one_workerEE19observe_on_observerINS_10subscriberIS8_NS_8observerIS8_vvvvEEEEE16observe_on_state17ensure_processingERNSt3__111unique_lockINSI_5mutexEEEEUlvE1_ED2Ev` | 0x61fec | 44 |

</details>

**Removed functions (32)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNKSt3__121__basic_string_commonILb1EE20__throw_length_errorEv.isra.595` | 0x184d0 | 96 |
| `_ZNKSt3__18functionIFvN5rxcpp10subscriberINS_10shared_ptrIN3dji6camera11FrameBufferEEENS1_8observerIS7_vvvvEEEEEEclESA_.isra.983.part.984` | 0x18530 | 60 |
| `_ZN3C2d3c2dEv` | 0x2935c | 708 |
| `_ZN3C2dC1EP7QObject` | 0x2ac98 | 588 |
| `_ZN3C2dC2EP7QObject` | 0x2ac98 | 588 |
| `_ZN16CamserviceObject13capture_imageEijRK12QDBusMessage` | 0x2b01c | 16 |
| `_ZL7captureNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatE` | 0x33fec | 1032 |
| `_ZL11frameFormatRNSt3__110shared_ptrIN3dji6camera11FrameBufferEEE.part.512` | 0x34474 | 276 |
| `_ZN9QtPrivate8RefCount5derefEv.part.543` | 0x345f0 | 32 |
| `_ZN7QStringD2Ev.part.544` | 0x34610 | 24 |
| `_ZNKSt3__18functionIFvRKN5rxcpp10schedulers11schedulableEEEclES5_.isra.562` | 0x34628 | 80 |
| `_ZN5QListINSt3__15tupleIJjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.647` | 0x34678 | 68 |
| `_ZN5QListINSt3__15tupleIJN9HblmTypes14E_VideoControlEjP12QDBusMessageEEEE7deallocEPN9QListData4DataE.isra.651` | 0x346bc | 68 |
| `_ZN14CamserviceImpl9setStatusEN9HblmTypes21E_CameraServiceStatusE.part.477` | 0x349a8 | 392 |
| `_ZN14CamserviceImpl13wbTintChangedEi.part.582` | 0x34f64 | 776 |
| `_ZN14CamserviceImpl13wbTempChangedEi.part.581` | 0x352a8 | 780 |
| `_ZZN14CamserviceImpl20onPreviewFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.545` | 0x36534 | 764 |
| `_ZZN14CamserviceImpl17onFullFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.546` | 0x3687c | 780 |
| `_ZZN14CamserviceImpl17onJpegFrameBufferERNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEENKUlP18PendingCallWatcherE_clES8_.isra.547` | 0x36bdc | 764 |
| `_ZN8QMapNodeIj5QPairIi10QByteArrayEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.738` | 0x36f24 | 2528 |
| `_ZNK14CamserviceImpl12video_statusEv.localalias.1860` | 0x3a750 | 156 |
| `_ZN5QListI4QMapI7QString8QVariantEE7deallocEPN9QListData4DataE.isra.705` | 0x3cf10 | 180 |
| `_ZN14CamserviceImpl15doCapture_imageEN9HblmTypes13E_ImageFormatEjRK12QDBusMessage` | 0x3fd74 | 1408 |
| `_ZNK5rxcpp10schedulers6worker8scheduleIRNS_6detail15safe_subscriberINS_9operators6detail13lift_operatorINSt3__110shared_ptrIN3dji6camera11FrameBufferEEENS_18dynamic_observableISD_EENS6_6filterISD_ZN14CamserviceImplC4EP7QObjectRNS_21observe_on_one_workerEOK7QStringEUlSD_E4_EEEENS_10subscriberISD_NS_8observerISD_NS3_22stateless_observer_tagEZNSH_C4ESJ_SL_SO_EUlSD_E5_vvEEEEEEJEEENS8_9enable_ifIXaaoosrNS0_6detail18is_action_functionIT_EE5valuesrNS_15is_subscriptionIS13_EE5valuentsrNS_14is_schedulableIS13_EE5valueEvE4typeEOS13_DpOT0_` | 0x45a68 | 692 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlbE12_clEb.isra.1854` | 0x517f4 | 2532 |
| `_ZZN14CamserviceImplC4EP7QObjectRN5rxcpp21observe_on_one_workerEOK7QStringENKUlNSt3__110shared_ptrIN3dji6camera11FrameBufferEEEE6_clESD_.isra.1857` | 0x521e8 | 360 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_E10runFunctorEv` | 0x54c4c | 188 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_ED1Ev` | 0x5a4bc | 264 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_ED2Ev` | 0x5a4bc | 264 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_ED1Ev` | 0x5a5c4 | 8 |
| `_ZN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_ED0Ev` | 0x5a8fc | 272 |
| `_ZThn8_N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_ED0Ev` | 0x5aa0c | 8 |

**New objects (17)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTSN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_EE` | 0x86278 | 151 |
| `_ZTSN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEEE` | 0x86768 | 133 |
| `_ZZL13getOutputTypeN9HblmTypes13E_ImageFormatEE12__FUNCTION__` | 0x89c70 | 14 |
| `_ZZZL13setOutputTypeNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS2_10OutputTypeEENKUlvE_clEvE15qstring_literal` | 0x89d8c | 72 |
| `CSWTCH.1477` | 0x89dd8 | 16 |
| `CSWTCH.1479` | 0x8a210 | 32 |
| `_ZTIN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_EE` | 0x90e80 | 12 |
| `_ZTIN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEEE` | 0x90f0c | 12 |
| `_ZTVN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_EE` | 0x913f0 | 44 |
| `_ZTVN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEEE` | 0x915d0 | 44 |
| `_ZN3C2d7m_mutexE` | 0x930a8 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes13E_VideoStreamEE14qt_metatype_idEvE11metatype_id` | 0x93128 | 4 |
| `_ZZN9QtPrivate15ConnectionTypesINS_4ListIJN9HblmTypes13E_VideoStreamEEEELb1EE5typesEvE1t` | 0x93130 | 8 |
| `_ZZN11QMetaTypeIdIN9HblmTypes13E_ImageFormatEE14qt_metatype_idEvE11metatype_id` | 0x93138 | 4 |
| `_ZZN9QtPrivate15ConnectionTypesINS_4ListIJN9HblmTypes13E_ImageFormatEEEELb1EE5typesEvE1t` | 0x93140 | 8 |
| `_ZGVZN9QtPrivate15ConnectionTypesINS_4ListIJN9HblmTypes13E_VideoStreamEEEELb1EE5typesEvE1t` | 0x93164 | 4 |
| `_ZGVZN9QtPrivate15ConnectionTypesINS_4ListIJN9HblmTypes13E_ImageFormatEEEELb1EE5typesEvE1t` | 0x93168 | 4 |

**Removed objects (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTSN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_EE` | 0x849c8 | 161 |
| `_ZZL7captureNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEE12__FUNCTION__` | 0x87f28 | 8 |
| `_ZZZL7captureNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENKUlvE_clEvE15qstring_literal` | 0x87f30 | 48 |
| `CSWTCH.1455` | 0x88038 | 16 |
| `CSWTCH.1457` | 0x88470 | 32 |
| `_ZTIN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_EE` | 0x8ef88 | 12 |
| `_ZTVN12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEN9HblmTypes13E_ImageFormatEENS3_INS5_13CameraServiceEEES9_EE` | 0x8f618 | 44 |

### `/lib/libappscommon.so`

+39 / −6 functions · +1 / −0 objects

**New functions (39)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNK11ConfigProxy25diagonal_joystick_enabledEv` | 0x90044 | 40 |
| `_ZNK11ConfigProxy30user_button_grip_menu_functionEv` | 0x90fec | 44 |
| `_ZNK11ConfigProxy30user_button_grip_play_functionEv` | 0x91018 | 44 |
| `_ZN11ConfigProxy28setDiagonal_joystick_enabledEb` | 0x95754 | 228 |
| `_ZN11ConfigProxy25setMetadata_overlay_indexEN9HblmTypes17E_MetadataOverlayE` | 0x98368 | 228 |
| `_ZN11ConfigProxy33setUser_button_grip_menu_functionEN9HblmTypes20E_UserButtonFunctionE` | 0x9aec0 | 236 |
| `_ZN11ConfigProxy33setUser_button_grip_play_functionEN9HblmTypes20E_UserButtonFunctionE` | 0x9afac | 228 |
| `_ZNK11SysmanProxy16farm_early_readyEv` | 0xada14 | 40 |
| `_ZNK11SysmanProxy21long_exposure_suspendEv` | 0xada64 | 40 |
| `_ZN11SysmanProxy16farm_early_readyEbi` | 0xaf03c | 644 |
| `_ZNK11CameraProxy7wb_tempEv` | 0xc8a9c | 40 |
| `_ZNK11CameraProxy7wb_tintEv` | 0xc8ac4 | 40 |
| `_ZN11CameraProxy10setWb_tempEi` | 0xcb274 | 164 |
| `_ZN11CameraProxy10setWb_tintEi` | 0xcb318 | 164 |
| `_ZN11CameraProxy20request_img_transferEji` | 0xccf00 | 368 |
| `_ZN11CameraProxy26reprocess_raw_frame_bufferEy4QMapI7QString8QVariantEi` | 0xcd070 | 420 |
| `_ZNK13ProfilesProxy18resetting_profilesEv` | 0xf2630 | 40 |
| `_ZN15CamserviceProxy13capture_imageEji` | 0xf9198 | 632 |
| `_ZN17DatatransferProxy16send_imageResultEPK18PendingCallWatcherRj` | 0xfd7e8 | 2356 |
| `_ZN10ErrorProxy11ack_currentEi` | 0x105b28 | 564 |
| `_ZNK8WmsProxy10wifi_powerEv` | 0x115530 | 40 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE8DestructEPv` | 0x126ab4 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE9ConstructEPvPKv` | 0x126ab8 | 20 |
| `_ZN7Version10hardwareIDEv` | 0x12e09c | 104 |
| `_ZN20ConfigProxyInterface32diagonal_joystick_enabledChangedEb` | 0x15ee1c | 60 |
| `_ZN20ConfigProxyInterface29metadata_overlay_indexChangedEN9HblmTypes17E_MetadataOverlayE` | 0x15f998 | 60 |
| `_ZN20ConfigProxyInterface37user_button_grip_menu_functionChangedEN9HblmTypes20E_UserButtonFunctionE` | 0x1604d8 | 60 |
| `_ZN20ConfigProxyInterface37user_button_grip_play_functionChangedEN9HblmTypes20E_UserButtonFunctionE` | 0x160514 | 60 |
| `_ZN20SysmanProxyInterface23farm_early_readyChangedEb` | 0x1695b8 | 60 |
| `_ZN20SysmanProxyInterface28long_exposure_suspendChangedEb` | 0x169630 | 60 |
| `_ZN20CameraProxyInterface14wb_tempChangedEi` | 0x16fdf8 | 60 |
| `_ZN20CameraProxyInterface14wb_tintChangedEi` | 0x16fe34 | 60 |
| `_ZN22ProfilesProxyInterface25resetting_profilesChangedEb` | 0x1784c4 | 60 |
| `_ZN17WmsProxyInterface17wifi_powerChangedEb` | 0x17cb70 | 60 |
| `_ZN11SysmanProxy18doFarm_early_readyEb` | 0x1813a0 | 16 |
| `_ZN11CameraProxy22doRequest_img_transferEj` | 0x1863c0 | 16 |
| `_ZN11CameraProxy28doReprocess_raw_frame_bufferEy4QMapI7QString8QVariantE` | 0x186818 | 336 |
| `_ZN15CamserviceProxy15doCapture_imageEj` | 0x1890c8 | 16 |
| `_ZN10ErrorProxy13doAck_currentEv` | 0x18a9d4 | 16 |

**Removed functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN11ConfigProxy25setMetadata_overlay_indexEt` | 0x97758 | 236 |
| `_ZN11CameraProxy20request_img_transferEN9HblmTypes13E_ImageFormatEji` | 0xcc2b4 | 420 |
| `_ZN15CamserviceProxy13capture_imageEN9HblmTypes13E_ImageFormatEji` | 0xf7ec8 | 680 |
| `_ZN20ConfigProxyInterface29metadata_overlay_indexChangedEt` | 0x15d65c | 60 |
| `_ZN11CameraProxy22doRequest_img_transferEN9HblmTypes13E_ImageFormatEj` | 0x183688 | 16 |
| `_ZN15CamserviceProxy15doCapture_imageEN9HblmTypes13E_ImageFormatEj` | 0x1862a4 | 16 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_MetadataOverlayEE14qt_metatype_idEvE11metatype_id` | 0x1eff90 | 4 |

### `/bin/storage`

+17 / −14 functions · +7 / −5 objects

**New functions (17)**

| Symbol | Addr | Size |
|---|---|---|
| `ionhelper_get_heap_id` | 0x30c4c | 16 |
| `_ZN3C2d8InstanceC1Ev` | 0x3d810 | 896 |
| `_ZN3C2d8InstanceC2Ev` | 0x3d810 | 896 |
| `_ZN3C2d8InstanceD1Ev` | 0x3db90 | 140 |
| `_ZN3C2d8InstanceD2Ev` | 0x3db90 | 140 |
| `_ZN3C2d8Instance4drawER19duss_hal_2d_param_t` | 0x3dc1c | 668 |
| `_ZN9QtPrivate8RefCount5derefEv.part.26` | 0x4ce68 | 32 |
| `_ZN9QtPrivate8RefCount3refEv.part.27` | 0x4ce88 | 28 |
| `_ZNK14QSharedPointerI11ImageMemoryE3refEv.isra.31` | 0x4cea4 | 56 |
| `_ZNK14QSharedPointerI11FileContentE3refEv.isra.33` | 0x4cedc | 56 |
| `_ZNK14QSharedPointerI9CacheItemE3refEv.isra.34` | 0x4cf14 | 56 |
| `_ZN5QListI8QVariantE7deallocEPN9QListData4DataE.isra.44` | 0x4cf4c | 84 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.42` | 0x4cfa0 | 72 |
| `_ZN16ReprocessRequestD0Ev.localalias.151` | 0x4dc98 | 28 |
| `_ZN5QListI14QSharedPointerI11FileContentEE7deallocEPN9QListData4DataE.isra.79` | 0x4dd90 | 88 |
| `_ZN8QMapNodeIj14QSharedPointerI11FileContentEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.89` | 0x4dde8 | 1632 |
| `_ZN5QListI14QSharedPointerI9CacheItemEE7deallocEPN9QListData4DataE.isra.57` | 0x4fa3c | 88 |

**Removed functions (14)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN3C2d3c2dEv` | 0x3cedc | 760 |
| `_ZN3C2dC1EP7QObject` | 0x3e900 | 616 |
| `_ZN3C2dC2EP7QObject` | 0x3e900 | 616 |
| `_ZN9QtPrivate8RefCount5derefEv.part.28` | 0x4cbd0 | 32 |
| `_ZN9QtPrivate8RefCount3refEv.part.29` | 0x4cbf0 | 28 |
| `_ZNK14QSharedPointerI11ImageMemoryE3refEv.isra.33` | 0x4cc0c | 56 |
| `_ZNK14QSharedPointerI11FileContentE3refEv.isra.35` | 0x4cc44 | 56 |
| `_ZNK14QSharedPointerI9CacheItemE3refEv.isra.36` | 0x4cc7c | 56 |
| `_ZN5QListI8QVariantE7deallocEPN9QListData4DataE.isra.46` | 0x4ccb4 | 84 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.44` | 0x4cd08 | 72 |
| `_ZN16ReprocessRequestD0Ev.localalias.153` | 0x4da00 | 28 |
| `_ZN5QListI14QSharedPointerI11FileContentEE7deallocEPN9QListData4DataE.isra.81` | 0x4daf8 | 88 |
| `_ZN8QMapNodeIj14QSharedPointerI11FileContentEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.91` | 0x4db50 | 1632 |
| `_ZN5QListI14QSharedPointerI9CacheItemEE7deallocEPN9QListData4DataE.isra.59` | 0x4f6b4 | 88 |

**New objects (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN3C2d8InstanceC4EvE12__FUNCTION__` | 0xf8a30 | 9 |
| `_ZZN3C2d8Instance4drawER19duss_hal_2d_param_tE12__FUNCTION__` | 0xf8a40 | 5 |
| `._533` | 0xf9b60 | 2 |
| `_ZZNK14StorageManager15videoSecondSizeEvE12__FUNCTION__` | 0xf9c40 | 16 |
| `._431` | 0xfd160 | 10 |
| `._436` | 0xfdc48 | 2 |
| `_ZN3C2d7m_mutexE` | 0x110ed0 | 4 |

**Removed objects (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN3C2d3c2dEvE12__FUNCTION__` | 0xf8300 | 4 |
| `_ZZN3C2dC4EP7QObjectE12__FUNCTION__` | 0xf83b0 | 4 |
| `._531` | 0xf95a0 | 2 |
| `._424` | 0xfca68 | 4 |
| `._435` | 0xfd5a0 | 2 |

### `/etc/firmware/rtnodes/cfv-control.elf`

+18 / −5 functions · +159 / −149 objects

**New functions (18)**

| Symbol | Addr | Size |
|---|---|---|
| `vIcoTimerCallback` | 0x8002e5d | 40 |
| `BATTERY_CHARGE_PreventHotplug` | 0x80039e9 | 36 |
| `BATTERY_CHARGE_DisplayInfo` | 0x8003a0d | 352 |
| `discharge_dc` | 0x80043d9 | 92 |
| `handle_emergency_conditions` | 0x80047c9 | 112 |
| `sendCDFocusRequestTimeout` | 0x8009add | 140 |
| `ADC_EnableWatchdog` | 0x8015f3d | 308 |
| `BQ25700_BlockTask` | 0x80169c5 | 148 |
| `BQ25700_ReleaseTask` | 0x8016a59 | 92 |
| `BQ28Z610_WriteCommand_AltManufacturerAccess` | 0x8017621 | 96 |
| `BQ28Z610_GetBatteryStatus` | 0x8017681 | 30 |
| `BQ28Z610_GetTemperatureDC` | 0x80176a1 | 44 |
| `BQ28Z610_GetDesignCapacity` | 0x80176cd | 40 |
| `BQ28Z610_GetCapacityRemaining` | 0x80176f5 | 32 |
| `BQ28Z610_GetCurrent` | 0x8017715 | 40 |
| `BQ28Z610_GetChargeCycleCount` | 0x801773d | 48 |
| `BQ28Z610_GetChargingCurrent` | 0x801776d | 40 |
| `POWER_VSysUndervoltageEvent` | 0x80216e5 | 72 |

**Removed functions (5)**

| Symbol | Addr | Size |
|---|---|---|
| `BATTERY_CHARGE_DiplayInfo` | 0x8003585 | 184 |
| `BATTERY_CHARGE_GetInputMinVoltage` | 0x8003761 | 12 |
| `BQ28Z610_BatteryCapacityRemaining` | 0x8016c6d | 30 |
| `BQ28Z610_BatteryCurrent` | 0x8016c8d | 40 |
| `BQ28Z610_BatteryChargeCycleCount` | 0x8016cb5 | 48 |

**New objects (159)**

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
| `__func__.15514` | 0x802c1c8 | 21 |
| `__func__.15212` | 0x802c1f0 | 17 |
| `__func__.15083` | 0x802c204 | 34 |
| `__func__.15089` | 0x802c228 | 25 |
| `__func__.14891` | 0x802c244 | 28 |
| `__func__.15101` | 0x802c260 | 20 |
| `__func__.15401` | 0x802c274 | 19 |
| `__func__.15108` | 0x802c288 | 20 |
| `__func__.15277` | 0x802c29c | 15 |
| `__func__.15280` | 0x802c2c4 | 18 |
| `__func__.14957` | 0x802c2d8 | 30 |
| `__func__.15318` | 0x802c2f8 | 10 |
| `__FUNCTION__.14899` | 0x802c304 | 31 |
| `__func__.15039` | 0x802c324 | 16 |
| `__func__.15008` | 0x802c334 | 16 |
| `__func__.15360` | 0x802c344 | 22 |
| `__func__.15354` | 0x802c35c | 14 |
| `__func__.14848` | 0x802c36c | 24 |
| `__func__.15077` | 0x802c384 | 32 |
| `__FUNCTION__.14811` | 0x802c3a4 | 20 |

<details><summary>… 另 109 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15228` | 0x802c3b8 | 29 |
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
| `__func__.14737` | 0x8030d7c | 16 |
| `__func__.13585` | 0x8031dd0 | 26 |
| `__func__.13590` | 0x8031dec | 22 |
| `__func__.13563` | 0x803208c | 31 |
| `__func__.13580` | 0x80320ac | 17 |
| `__FUNCTION__.12756` | 0x80320c0 | 29 |
| `__FUNCTION__.12768` | 0x80320f0 | 22 |
| `__FUNCTION__.12776` | 0x8032108 | 22 |
| `__FUNCTION__.12733` | 0x8032490 | 27 |
| `__func__.15585` | 0x80326ec | 21 |
| `__func__.15599` | 0x8032704 | 17 |
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
| `__func__.13615` | 0x80382d0 | 19 |
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
| `mNewPowerSource` | 0x2000001d | 1 |
| `battery_probe_counter.15987` | 0x20000020 | 4 |
| `mBq28z610Info` | 0x20000040 | 20 |
| `oldValue.15137` | 0x20000070 | 4 |
| `oldValue.15132` | 0x20000074 | 4 |
| `HW_version.14008` | 0x200002b8 | 1 |
| `enterState.15033` | 0x20000308 | 1 |
| `lastVsysImxErrorEventTime` | 0x2000030c | 4 |
| `mIcoTimerHandle` | 0x20000640 | 4 |
| `last_hvdcp.15851` | 0x20000650 | 1 |
| `mBq25700Info` | 0x20000654 | 12 |
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

</details>

**Removed objects (149)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15857` | 0x8028998 | 16 |
| `__func__.15726` | 0x80289a8 | 15 |
| `__func__.15869` | 0x80289b8 | 10 |
| `__func__.15950` | 0x80289c4 | 15 |
| `__func__.15881` | 0x80289d4 | 11 |
| `__func__.15832` | 0x8028a14 | 23 |
| `__func__.15892` | 0x8029548 | 19 |
| `__func__.15738` | 0x802955c | 33 |
| `__func__.15814` | 0x8029580 | 13 |
| `__func__.15981` | 0x8029590 | 42 |
| `__func__.14492` | 0x8029684 | 41 |
| `__func__.14496` | 0x80296b0 | 17 |
| `__func__.14499` | 0x80296c4 | 21 |
| `__func__.14523` | 0x8029870 | 29 |
| `__func__.14503` | 0x8029890 | 22 |
| `__func__.14507` | 0x80298a8 | 21 |
| `__func__.14517` | 0x80298c0 | 32 |
| `__func__.14280` | 0x80298f4 | 41 |
| `__func__.14284` | 0x8029a68 | 21 |
| `__func__.14292` | 0x8029a80 | 21 |
| `__func__.13821` | 0x802a554 | 16 |
| `__func__.15443` | 0x802af04 | 23 |
| `__func__.15477` | 0x802af1c | 13 |
| `__func__.15423` | 0x802af2c | 11 |
| `__func__.15419` | 0x802af38 | 17 |
| `__func__.15532` | 0x802af4c | 26 |
| `__func__.15489` | 0x802af68 | 25 |
| `__func__.15452` | 0x802af84 | 21 |
| `__func__.15433` | 0x802b220 | 20 |
| `__func__.15503` | 0x802b234 | 22 |
| `__func__.15460` | 0x802b24c | 22 |
| `__func__.15224` | 0x802b274 | 18 |
| `__FUNCTION__.14839` | 0x802b288 | 35 |
| `__func__.14801` | 0x802b2ac | 24 |
| `__func__.14896` | 0x802b2c4 | 22 |
| `__FUNCTION__.14843` | 0x802b2dc | 31 |
| `__func__.15321` | 0x802b2fc | 21 |
| `__func__.15298` | 0x802b314 | 14 |
| `__func__.14901` | 0x802b334 | 30 |
| `__FUNCTION__.14770` | 0x802b354 | 25 |
| `__func__.15312` | 0x802b370 | 26 |
| `__func__.15033` | 0x802b38c | 25 |
| `__func__.15052` | 0x802b3a8 | 20 |
| `__func__.15021` | 0x802b3bc | 32 |
| `__func__.15221` | 0x802b3dc | 15 |
| `__func__.15262` | 0x802b3ec | 10 |
| `__func__.15156` | 0x802b3f8 | 17 |
| `__func__.15172` | 0x802b40c | 29 |
| `__func__.15304` | 0x802b42c | 22 |
| `__FUNCTION__.14764` | 0x802b444 | 20 |

<details><summary>… 另 99 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.14983` | 0x802b458 | 16 |
| `__func__.15027` | 0x802b468 | 34 |
| `__func__.15345` | 0x802b48c | 19 |
| `__func__.15045` | 0x802b4a0 | 20 |
| `__func__.14835` | 0x802b4b4 | 28 |
| `__FUNCTION__.16871` | 0x802bd78 | 11 |
| `__FUNCTION__.15093` | 0x802c0f0 | 10 |
| `__FUNCTION__.15089` | 0x802c0fc | 27 |
| `__FUNCTION__.15072` | 0x802c1e8 | 27 |
| `__func__.14597` | 0x802c208 | 24 |
| `__func__.14666` | 0x802c220 | 11 |
| `__func__.14686` | 0x802fdf0 | 13 |
| `__func__.14692` | 0x802fe00 | 16 |
| `__func__.13531` | 0x8030e54 | 17 |
| `__func__.13536` | 0x8030ff8 | 26 |
| `__func__.13541` | 0x8031014 | 22 |
| `__func__.13514` | 0x8031124 | 31 |
| `__FUNCTION__.12706` | 0x8031144 | 29 |
| `__FUNCTION__.12718` | 0x8031174 | 22 |
| `__FUNCTION__.12726` | 0x80314fc | 22 |
| `__FUNCTION__.12683` | 0x8031514 | 27 |
| `__func__.15629` | 0x8031530 | 21 |
| `__func__.15548` | 0x8031548 | 17 |
| `__func__.15534` | 0x803155c | 21 |
| `__func__.15601` | 0x803158c | 22 |
| `__func__.15562` | 0x8031cfc | 21 |
| `__func__.14694` | 0x8032274 | 25 |
| `__func__.14698` | 0x8032290 | 25 |
| `__FUNCTION__.14672` | 0x80322ac | 13 |
| `__func__.11721` | 0x8032720 | 19 |
| `__func__.11705` | 0x8032734 | 11 |
| `__func__.11711` | 0x8032740 | 12 |
| `__func__.11716` | 0x803274c | 12 |
| `__func__.11697` | 0x80328d0 | 19 |
| `__func__.13534` | 0x8032a58 | 29 |
| `__func__.13390` | 0x8032a78 | 27 |
| `__func__.13504` | 0x803385c | 19 |
| `__func__.13411` | 0x8033870 | 13 |
| `__FUNCTION__.13118` | 0x8034548 | 40 |
| `__func__.13481` | 0x80345ec | 13 |
| `__func__.13490` | 0x80345fc | 19 |
| `__FUNCTION__.12933` | 0x8034754 | 31 |
| `__FUNCTION__.12879` | 0x8034774 | 34 |
| `__FUNCTION__.12949` | 0x8034798 | 24 |
| `__FUNCTION__.12899` | 0x8034954 | 28 |
| `__FUNCTION__.12963` | 0x8034970 | 27 |
| `__FUNCTION__.12908` | 0x803498c | 16 |
| `__func__.13913` | 0x80351d0 | 13 |
| `__func__.13909` | 0x80351e0 | 11 |
| `__func__.13923` | 0x80351ec | 14 |
| `__func__.13918` | 0x80351fc | 15 |
| `__func__.13931` | 0x803520c | 18 |
| `__func__.13927` | 0x8035220 | 12 |
| `__func__.7483` | 0x8036238 | 19 |
| `__func__.13642` | 0x8036c98 | 13 |
| `__func__.13550` | 0x8036ca8 | 18 |
| `__func__.13602` | 0x8036cbc | 10 |
| `__func__.13609` | 0x80371d4 | 9 |
| `__func__.13568` | 0x80371e0 | 19 |
| `__func__.13172` | 0x80375f0 | 23 |
| `__func__.14812` | 0x80376a8 | 27 |
| `__FUNCTION__.14896` | 0x8037d60 | 18 |
| `__FUNCTION__.12884` | 0x8037d80 | 21 |
| `__FUNCTION__.15000` | 0x8037f68 | 23 |
| `__FUNCTION__.15007` | 0x8038388 | 13 |
| `__FUNCTION__.14967` | 0x8038398 | 20 |
| `__FUNCTION__.14485` | 0x803847c | 22 |
| `__FUNCTION__.14491` | 0x8038494 | 28 |
| `__FUNCTION__.14472` | 0x8038828 | 30 |
| `__func__.14363` | 0x8038848 | 19 |
| `__func__.14290` | 0x8038a94 | 10 |
| `batteryStatus.15772` | 0x20000029 | 1 |
| `lastBatteryLevel.15771` | 0x2000002c | 1 |
| `oldValue.15084` | 0x20000050 | 4 |
| `oldValue.15079` | 0x20000054 | 4 |
| `HW_version.13963` | 0x20000298 | 1 |
| `enterState.14758` | 0x200002e8 | 1 |
| `last_hvdcp.15737` | 0x20000628 | 1 |
| `eldBtnSavedConf.14479` | 0x20000634 | 16 |
| `inputBefore.14481` | 0x20000644 | 4 |
| `triggerBefore.14480` | 0x20000648 | 1 |
| `msg_index.12277` | 0x20000708 | 4 |
| `ticks.13351` | 0x20000710 | 4 |
| `saved_lens.15334` | 0x20000ab9 | 1 |
| `is_fake.15335` | 0x20000af5 | 1 |
| `lastGpioValue.15071` | 0x20000b94 | 4 |
| `last_signal.17870` | 0x20000bde | 1 |
| `sig.12329` | 0x20002670 | 270 |
| `mutex.13971` | 0x200028e4 | 4 |
| `str.13869` | 0x200028e8 | 10 |
| `writebuffer.12315` | 0x20003208 | 5 |
| `initialized.13641` | 0x2000321a | 1 |
| `rxDmaInitialized.13076` | 0x20003248 | 1 |
| `txPoolInitialized.13060` | 0x20003249 | 1 |
| `timerInitialized.13084` | 0x200042f5 | 1 |
| `wakeUpSpecialEn.14759` | 0x2000430c | 1 |
| `earlyStartInProgress.14964` | 0x20004339 | 1 |
| `loopTestTaskHandle.14371` | 0x20004368 | 4 |
| `switch_req_origin.14288` | 0x20004377 | 1 |

</details>

### `/etc/firmware/rtnodes/xsystem-control.elf`

+18 / −4 functions · +137 / −127 objects

**New functions (18)**

| Symbol | Addr | Size |
|---|---|---|
| `vIcoTimerCallback` | 0x8002b7d | 40 |
| `updateMainPowerSource` | 0x8002bbd | 88 |
| `BATTERY_CHARGE_PreventHotplug` | 0x8003795 | 36 |
| `BATTERY_CHARGE_DisplayInfo` | 0x80037b9 | 352 |
| `handle_emergency_conditions` | 0x80045c5 | 112 |
| `sendCDFocusRequestTimeout` | 0x80081a1 | 140 |
| `ADC_EnableWatchdog` | 0x8011ced | 308 |
| `BQ25700_BlockTask` | 0x8012821 | 148 |
| `BQ25700_ReleaseTask` | 0x80128b5 | 92 |
| `BQ28Z610_WriteCommand_AltManufacturerAccess` | 0x801347d | 96 |
| `BQ28Z610_GetBatteryStatus` | 0x80134dd | 30 |
| `BQ28Z610_GetTemperatureDC` | 0x80134fd | 44 |
| `BQ28Z610_GetDesignCapacity` | 0x8013529 | 40 |
| `BQ28Z610_GetCapacityRemaining` | 0x8013551 | 32 |
| `BQ28Z610_GetCurrent` | 0x8013571 | 40 |
| `BQ28Z610_GetChargeCycleCount` | 0x8013599 | 48 |
| `BQ28Z610_GetChargingCurrent` | 0x80135c9 | 40 |
| `POWER_VSysUndervoltageEvent` | 0x801e2a5 | 72 |

**Removed functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `BATTERY_CHARGE_DiplayInfo` | 0x8003309 | 184 |
| `BQ28Z610_BatteryCapacityRemaining` | 0x8012a49 | 30 |
| `BQ28Z610_BatteryCurrent` | 0x8012a69 | 40 |
| `BQ28Z610_BatteryChargeCycleCount` | 0x8012a91 | 48 |

**New objects (137)**

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
| `__func__.15990` | 0x8026288 | 19 |
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
| `__func__.15236` | 0x80275f4 | 29 |
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
| `__func__.15288` | 0x8027784 | 18 |
| `__func__.14965` | 0x80277b0 | 30 |
| `__FUNCTION__.14825` | 0x80277d0 | 25 |
| `__func__.15326` | 0x80277ec | 10 |
| `__func__.15047` | 0x80277f8 | 16 |
| `__func__.15362` | 0x80280b8 | 14 |
| `__FUNCTION__.17100` | 0x80280c8 | 11 |
| `__FUNCTION__.15111` | 0x80283fc | 27 |
| `__FUNCTION__.15118` | 0x8028480 | 10 |

<details><summary>… 另 87 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.14467` | 0x8028490 | 16 |
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
| `__func__.13611` | 0x8032340 | 19 |
| `__func__.13652` | 0x8032354 | 9 |
| `__func__.13213` | 0x803381c | 23 |
| `__func__.15083` | 0x8033b78 | 27 |
| `__FUNCTION__.12925` | 0x8033fc4 | 21 |
| `__FUNCTION__.14921` | 0x80341ac | 20 |
| `__FUNCTION__.14954` | 0x8034608 | 23 |
| `__FUNCTION__.14961` | 0x8034620 | 13 |
| `__FUNCTION__.14878` | 0x8034700 | 30 |
| `__FUNCTION__.14891` | 0x8034720 | 22 |
| `__FUNCTION__.14897` | 0x8034a10 | 28 |
| `__func__.14321` | 0x8034a2c | 10 |
| `__func__.14394` | 0x8034c70 | 19 |
| `mBq28z610Info` | 0x20000014 | 20 |
| `battery_probe_counter.15981` | 0x2000002c | 4 |
| `mNewPowerSource` | 0x20000035 | 1 |
| `batteryStatus.15872` | 0x20000050 | 1 |
| `HW_version.13964` | 0x200002a0 | 1 |
| `flashpower.14195` | 0x200002ea | 1 |
| `lastRxData.14055` | 0x20000314 | 4 |
| `checksum.14193` | 0x20000376 | 2 |
| `enterState.15029` | 0x200003e0 | 1 |
| `lastVsysImxErrorEventTime` | 0x200003e4 | 4 |
| `mIcoTimerHandle` | 0x20000714 | 4 |
| `mBq25700Info` | 0x20000724 | 12 |
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

</details>

**Removed objects (127)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15980` | 0x80245cc | 42 |
| `__func__.15860` | 0x80245f8 | 16 |
| `__func__.15722` | 0x8024608 | 15 |
| `__func__.15872` | 0x8024618 | 10 |
| `__func__.15895` | 0x8024658 | 19 |
| `__func__.15884` | 0x802466c | 11 |
| `__func__.15953` | 0x80251f0 | 15 |
| `__func__.15835` | 0x8025200 | 23 |
| `__func__.15817` | 0x8025218 | 13 |
| `__func__.15734` | 0x80252dc | 33 |
| `__func__.13821` | 0x8025a28 | 16 |
| `__func__.15522` | 0x80261e4 | 26 |
| `__func__.15473` | 0x8026200 | 13 |
| `__func__.15419` | 0x8026210 | 11 |
| `__func__.15415` | 0x802621c | 17 |
| `__func__.15485` | 0x8026230 | 25 |
| `__func__.15439` | 0x8026368 | 23 |
| `__func__.15429` | 0x8026380 | 20 |
| `__func__.15448` | 0x80264fc | 21 |
| `__func__.15456` | 0x8026514 | 22 |
| `__func__.15499` | 0x802652c | 22 |
| `__func__.15232` | 0x8026554 | 18 |
| `__func__.15229` | 0x8026568 | 15 |
| `__func__.15270` | 0x8026578 | 10 |
| `__FUNCTION__.14847` | 0x8026584 | 35 |
| `__func__.15164` | 0x80265a8 | 17 |
| `__func__.15180` | 0x80265bc | 29 |
| `__func__.15312` | 0x80265dc | 22 |
| `__func__.14809` | 0x80265f4 | 24 |
| `__FUNCTION__.14778` | 0x802660c | 25 |
| `__func__.14991` | 0x8026628 | 16 |
| `__func__.14843` | 0x8026638 | 28 |
| `__func__.15353` | 0x8026654 | 19 |
| `__func__.15093` | 0x8026668 | 21 |
| `__func__.15035` | 0x8026680 | 34 |
| `__FUNCTION__.14851` | 0x80266a4 | 31 |
| `__func__.15053` | 0x80266c4 | 20 |
| `__func__.14904` | 0x80266d8 | 22 |
| `__func__.14909` | 0x80266f0 | 30 |
| `__func__.15329` | 0x8026710 | 21 |
| `__func__.15306` | 0x8026738 | 14 |
| `__func__.15320` | 0x8026748 | 26 |
| `__func__.15041` | 0x8026764 | 25 |
| `__func__.15029` | 0x8026780 | 32 |
| `__FUNCTION__.14772` | 0x80267a0 | 20 |
| `__func__.15060` | 0x80267b4 | 20 |
| `__FUNCTION__.17047` | 0x8027078 | 11 |
| `__FUNCTION__.15058` | 0x8027414 | 27 |
| `__FUNCTION__.15065` | 0x8027430 | 10 |
| `__func__.14416` | 0x8027440 | 13 |

<details><summary>… 另 77 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.14422` | 0x8027450 | 16 |
| `__func__.14396` | 0x802afc4 | 11 |
| `__func__.13492` | 0x802c014 | 22 |
| `__func__.13482` | 0x802c02c | 17 |
| `__func__.13487` | 0x802c1d0 | 26 |
| `__func__.13465` | 0x802c2e4 | 31 |
| `__FUNCTION__.12706` | 0x802c304 | 29 |
| `__FUNCTION__.12718` | 0x802c334 | 22 |
| `__FUNCTION__.12726` | 0x802c6bc | 22 |
| `__FUNCTION__.12683` | 0x802c6d4 | 27 |
| `__func__.15745` | 0x802c6f0 | 21 |
| `__func__.15702` | 0x802c708 | 21 |
| `__func__.13530` | 0x802cf40 | 29 |
| `__func__.13500` | 0x802cf60 | 19 |
| `__func__.13386` | 0x802cf8c | 27 |
| `__func__.13407` | 0x802dd70 | 13 |
| `__FUNCTION__.13118` | 0x802ea48 | 40 |
| `__func__.13486` | 0x802eadc | 19 |
| `__func__.13477` | 0x802eaf0 | 13 |
| `__FUNCTION__.12929` | 0x802ec44 | 31 |
| `__FUNCTION__.12945` | 0x802ec64 | 24 |
| `__FUNCTION__.12895` | 0x802ec7c | 28 |
| `__FUNCTION__.12959` | 0x802ee3c | 27 |
| `__FUNCTION__.12904` | 0x802ee58 | 16 |
| `__func__.13870` | 0x802f8ac | 13 |
| `__func__.13884` | 0x802f8c8 | 12 |
| `__func__.13888` | 0x802f8d4 | 18 |
| `__func__.13638` | 0x8031138 | 13 |
| `__func__.13598` | 0x8031148 | 10 |
| `__func__.13546` | 0x8031154 | 18 |
| `__func__.13605` | 0x8031168 | 9 |
| `__func__.13564` | 0x8031680 | 19 |
| `__func__.13168` | 0x8032648 | 23 |
| `__func__.14808` | 0x8032700 | 27 |
| `__FUNCTION__.14856` | 0x8032dd0 | 18 |
| `__FUNCTION__.12880` | 0x8032df0 | 21 |
| `__FUNCTION__.14872` | 0x8032fd8 | 20 |
| `__FUNCTION__.14912` | 0x803344c | 13 |
| `__FUNCTION__.14450` | 0x803352c | 30 |
| `__FUNCTION__.14463` | 0x8033824 | 22 |
| `__FUNCTION__.14469` | 0x803383c | 28 |
| `__func__.14276` | 0x8033858 | 10 |
| `__func__.14349` | 0x8033a9c | 19 |
| `batteryStatus.15768` | 0x20000029 | 1 |
| `lastBatteryLevel.15767` | 0x2000002c | 1 |
| `HW_version.13919` | 0x20000290 | 1 |
| `checksum.14148` | 0x2000030e | 2 |
| `lastRxData.14010` | 0x20000310 | 4 |
| `flashpower.14150` | 0x20000327 | 1 |
| `enterState.14754` | 0x200003cc | 1 |
| `last_hvdcp.15733` | 0x2000070c | 1 |
| `ticks.13596` | 0x200007d8 | 4 |
| `saved_lens.15342` | 0x20000b7e | 1 |
| `is_fake.15343` | 0x20000b99 | 1 |
| `lastGpioValue.15057` | 0x20000c5c | 4 |
| `sig.12329` | 0x2000271c | 270 |
| `mutex.13927` | 0x20002998 | 4 |
| `str.13826` | 0x2000299c | 10 |
| `writebuffer.12315` | 0x200032b8 | 5 |
| `initialized.13637` | 0x200032ca | 1 |
| `flashstatus.14149` | 0x200032d6 | 1 |
| `generateTxAckDelay.14005` | 0x200032e0 | 1 |
| `checksum.14003` | 0x200032e8 | 4 |
| `lastMode.14151` | 0x200032ec | 1 |
| `datacnt.14002` | 0x200032ed | 1 |
| `generateRxAck.14006` | 0x200032ef | 1 |
| `TxAckTimeoutCnt.14009` | 0x200032f4 | 4 |
| `longAckDelay.14008` | 0x20003300 | 1 |
| `generateRxAckDelay.14007` | 0x20003301 | 1 |
| `generateTxAck.14004` | 0x20003313 | 1 |
| `txPoolInitialized.13056` | 0x2000333c | 1 |
| `timerInitialized.13080` | 0x20003354 | 1 |
| `rxDmaInitialized.13072` | 0x200043ed | 1 |
| `wakeUpSpecialEn.14755` | 0x20004419 | 1 |
| `earlyStartInProgress.14869` | 0x20004449 | 1 |
| `loopTestTaskHandle.14357` | 0x20004468 | 4 |
| `switch_req_origin.14274` | 0x20004486 | 1 |

</details>

### `/lib/libservice.so`

+8 / −2 functions · +0 / −0 objects

**New functions (8)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN3dji6camera13CameraService13setOutputTypeENS0_10OutputTypeE` | 0x39617 | 12 |
| `_ZThn4_N3dji6camera13CameraService13setOutputTypeENS0_10OutputTypeE` | 0x39623 | 8 |
| `_ZN3dji6camera13CameraService7captureEj` | 0x39a4d | 156 |
| `_ZNK3dji6camera13CaptureEngine9zoomPointEv` | 0x486ad | 8 |
| `_ZNK3dji6camera13CaptureEngine4zoomEv` | 0x486b5 | 10 |
| `_ZN3dji6camera13CaptureEngine13setOutputTypeENS0_10OutputTypeE` | 0x4ab7d | 692 |
| `_ZN3dji6camera13CaptureEngine7captureEj` | 0x4ae31 | 496 |
| `_ZN3dji6camera15RecordingEngine10stopWorkerENS0_14RecordingStateE` | 0x561fd | 102 |

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN3dji6camera13CameraService7captureENS0_10OutputTypeE` | 0x3977d | 156 |
| `_ZN3dji6camera13CaptureEngine7captureENS0_10OutputTypeE` | 0x4a725 | 1092 |

### `/bin/odindb-send`

+7 / −2 functions · +1 / −0 objects

**New functions (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE8DestructEPv` | 0xb5348 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE9ConstructEPvPKv` | 0xb534c | 20 |
| `_ZN11SysmanProxy18doFarm_early_readyEb` | 0x153f78 | 16 |
| `_ZN11CameraProxy22doRequest_img_transferEj` | 0x1560dc | 16 |
| `_ZN11CameraProxy28doReprocess_raw_frame_bufferEy4QMapI7QString8QVariantE` | 0x1563fc | 3828 |
| `_ZN15CamserviceProxy15doCapture_imageEj` | 0x1599f0 | 16 |
| `_ZN10ErrorProxy13doAck_currentEv` | 0x15b914 | 16 |

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN11CameraProxy22doRequest_img_transferEN9HblmTypes13E_ImageFormatEj` | 0x1536a0 | 16 |
| `_ZN15CamserviceProxy15doCapture_imageEN9HblmTypes13E_ImageFormatEj` | 0x1560c0 | 16 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_MetadataOverlayEE14qt_metatype_idEvE11metatype_id` | 0x195220 | 4 |

### `/lib/modules/rcam_dji.ko`

+5 / −0 functions · +42 / −40 objects

**New functions (5)**

| Symbol | Addr | Size |
|---|---|---|
| `mipi_rx_send_stream` | 0xb0 | 388 |
| `mipi_rx_handle_error` | 0x234 | 8 |
| `smipi_register_send_frame_error_callback` | 0x212c | 4 |
| `workqueue_handle_mipi_error` | 0x2924 | 36 |
| `smipi_resource_register_error_callback` | 0x3c70 | 20 |

**New objects (42)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.23665` | 0x0 | 14 |
| `descriptor.25059` | 0x0 | 24 |
| `__func__.23628` | 0xe | 20 |
| `descriptor.27049` | 0x18 | 24 |
| `__func__.23616` | 0x22 | 17 |
| `descriptor.27051` | 0x30 | 24 |
| `__func__.23571` | 0x33 | 16 |
| `__func__.23633` | 0x43 | 24 |
| `descriptor.26860` | 0x48 | 24 |
| `__func__.23697` | 0x5b | 20 |
| `descriptor.26865` | 0x60 | 24 |
| `__func__.23707` | 0x6f | 22 |
| `descriptor.26840` | 0x78 | 24 |
| `descriptor.26842` | 0x90 | 24 |
| `workqueue` | 0xbc | 16 |
| `descriptor.26845` | 0xc0 | 24 |
| `descriptor.26869` | 0xd8 | 24 |
| `descriptor.26870` | 0xf0 | 24 |
| `descriptor.26871` | 0x108 | 24 |
| `__key.24970` | 0x208 | 0 |
| `__func__.24881` | 0x578 | 14 |
| `__func__.24922` | 0x586 | 19 |
| `__func__.24942` | 0x714 | 23 |
| `__func__.24953` | 0x72b | 23 |
| `__func__.24962` | 0x742 | 18 |
| `__func__.24983` | 0x754 | 23 |
| `__func__.25013` | 0x76b | 21 |
| `__func__.25051` | 0x780 | 19 |
| `__func__.25055` | 0x793 | 19 |
| `__func__.25060` | 0x7a6 | 20 |
| `__func__.25067` | 0x7ba | 20 |
| `__func__.25090` | 0x7ce | 19 |
| `__func__.25105` | 0x7e1 | 20 |
| `__func__.25115` | 0x7f5 | 30 |
| `__func__.26800` | 0x850 | 27 |
| `__func__.26903` | 0x898 | 20 |
| `__func__.26908` | 0x8ac | 20 |
| `__func__.26912` | 0x8c0 | 21 |
| `__func__.26916` | 0x8d5 | 21 |
| `__func__.27050` | 0x8ea | 13 |
| `__func__.26841` | 0x8f7 | 21 |
| `__func__.26861` | 0x90c | 16 |

**Removed objects (40)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.23653` | 0x0 | 14 |
| `descriptor.25045` | 0x0 | 24 |
| `__func__.23621` | 0xe | 24 |
| `descriptor.27032` | 0x18 | 24 |
| `__func__.23610` | 0x26 | 17 |
| `descriptor.27034` | 0x30 | 24 |
| `__func__.23565` | 0x37 | 16 |
| `__func__.23682` | 0x47 | 20 |
| `__func__.23692` | 0x5b | 22 |
| `descriptor.26849` | 0x60 | 24 |
| `descriptor.26824` | 0x78 | 24 |
| `descriptor.26826` | 0x90 | 24 |
| `descriptor.26828` | 0xa8 | 24 |
| `descriptor.26829` | 0xc0 | 24 |
| `descriptor.26853` | 0xd8 | 24 |
| `descriptor.26854` | 0xf0 | 24 |
| `descriptor.26855` | 0x108 | 24 |
| `__key.24960` | 0x204 | 0 |
| `__func__.24871` | 0x564 | 14 |
| `__func__.24912` | 0x572 | 19 |
| `__func__.24932` | 0x700 | 23 |
| `__func__.24943` | 0x717 | 23 |
| `__func__.24952` | 0x72e | 18 |
| `__func__.24969` | 0x740 | 23 |
| `__func__.24999` | 0x757 | 21 |
| `__func__.25037` | 0x76c | 19 |
| `__func__.25041` | 0x77f | 19 |
| `__func__.25046` | 0x792 | 20 |
| `__func__.25053` | 0x7a6 | 20 |
| `__func__.25076` | 0x7ba | 19 |
| `__func__.25091` | 0x7cd | 20 |
| `__func__.25101` | 0x7e1 | 30 |
| `__func__.26784` | 0x83c | 27 |
| `__func__.26887` | 0x884 | 20 |
| `__func__.26892` | 0x898 | 20 |
| `__func__.26896` | 0x8ac | 21 |
| `__func__.26900` | 0x8c1 | 21 |
| `__func__.27033` | 0x8d6 | 13 |
| `__func__.26825` | 0x8e3 | 21 |
| `__func__.26845` | 0x8f8 | 16 |

### `/bin/camera`

+4 / −0 functions · +1 / −0 objects

**New functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_StorageStatusELb1EE8DestructEPv` | 0x27178 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_StorageStatusELb1EE9ConstructEPvPKv` | 0x2717c | 20 |
| `_ZN4QMapI7QString8QVariantE13detach_helperEv` | 0x27e98 | 148 |
| `_ZN9QtPrivate15ConnectionTypesINS_4ListIJP18PendingCallWatcherEEELb1EE5typesEv` | 0x60520 | 468 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_StorageStatusEE14qt_metatype_idEvE11metatype_id` | 0x98194 | 4 |

### `/etc/firmware/rtnodes/app.elf`

+3 / −1 functions · +247 / −235 objects

**New functions (3)**

| Symbol | Addr | Size |
|---|---|---|
| `send_farm_early_ready_req` | 0x1e238 | 56 |
| `handle_farmus_early_ready_resp` | 0x1e270 | 20 |
| `CAMBODY_is_exposing_from_suspend_supported` | 0x26cc0 | 72 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `data_transfer_sendReq2Str` | 0xf368 | 88 |

**New objects (247)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.13020` | 0x124e60 | 19 |
| `__func__.13037` | 0x124e78 | 15 |
| `__func__.13075` | 0x124e88 | 12 |
| `__func__.13097` | 0x124e98 | 9 |
| `__func__.13112` | 0x124ea8 | 9 |
| `__func__.13130` | 0x124eb8 | 15 |
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
| `hblm_prop_camera_wb_temp` | 0x127b60 | 8 |
| `hblm_prop_camera_wb_tint` | 0x127b68 | 8 |
| `hblm_prop_config_diagonal_joystick_enabled` | 0x1281e8 | 26 |
| `hblm_prop_config_user_button_grip_menu_function` | 0x128b10 | 31 |
| `hblm_prop_config_user_button_grip_play_function` | 0x128b30 | 31 |
| `hblm_prop_profiles_resetting_profiles` | 0x129190 | 19 |
| `hblm_prop_sysman_farm_early_ready` | 0x129528 | 17 |
| `hblm_prop_sysman_long_exposure_suspend` | 0x129560 | 22 |
| `hblm_prop_wms_wifi_power` | 0x129740 | 11 |
| `__func__.13281` | 0x12bfd0 | 18 |
| `__func__.12971` | 0x12bff8 | 17 |
| `__func__.13024` | 0x12c010 | 13 |
| `__func__.12986` | 0x12c020 | 13 |
| `__func__.13396` | 0x12c030 | 16 |
| `__FUNCTION__.14278` | 0x12cbc0 | 26 |
| `__func__.14390` | 0x12cbe0 | 33 |
| `__FUNCTION__.14414` | 0x12cc08 | 28 |

<details><summary>… 另 197 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.14685` | 0x12cc28 | 30 |
| `__func__.14772` | 0x12cc48 | 34 |
| `__func__.14812` | 0x12cc70 | 28 |
| `__func__.14840` | 0x12cc90 | 32 |
| `__func__.14867` | 0x12ccb0 | 21 |
| `__func__.15013` | 0x12d358 | 29 |
| `__func__.15214` | 0x12d378 | 27 |
| `__FUNCTION__.15250` | 0x12d398 | 18 |
| `__FUNCTION__.15286` | 0x12d3b0 | 39 |
| `__func__.15313` | 0x12d3d8 | 27 |
| `__func__.12665` | 0x12d618 | 18 |
| `lensImprint.12632` | 0x12d630 | 16 |
| `__func__.12367` | 0x12d830 | 26 |
| `__func__.12212` | 0x12dab0 | 35 |
| `__func__.12682` | 0x12e100 | 22 |
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
| `__func__.12959` | 0x137608 | 26 |
| `INVALID_CHANNEL.12357` | 0x13807c | 1 |
| `__func__.12579` | 0x138710 | 17 |
| `__func__.12650` | 0x138728 | 12 |
| `__func__.12677` | 0x138738 | 16 |
| `diagonal_joystick_enabled_defval` | 0x13884a | 1 |
| `user_button_grip_menu_function_defval` | 0x1389c0 | 4 |
| `user_button_grip_play_function_defval` | 0x1389c4 | 4 |
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
| `__func__.14172` | 0x13c440 | 14 |
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
| `__func__.13419` | 0x13ef98 | 21 |
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
| `__compound_literal.150` | 0x14cbd0 | 1 |
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

**Removed objects (235)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.12975` | 0x124ce0 | 19 |
| `__func__.12992` | 0x124cf8 | 15 |
| `__func__.13030` | 0x124d08 | 12 |
| `__func__.13052` | 0x124d18 | 9 |
| `__func__.13067` | 0x124d28 | 9 |
| `__func__.13085` | 0x124d38 | 15 |
| `__func__.13118` | 0x124d48 | 20 |
| `__func__.13201` | 0x124d60 | 11 |
| `__func__.11440` | 0x124e58 | 13 |
| `__func__.11465` | 0x124e68 | 21 |
| `__func__.12587` | 0x124f88 | 13 |
| `__func__.12621` | 0x124f98 | 21 |
| `__func__.12657` | 0x124fc8 | 23 |
| `__func__.11639` | 0x125208 | 16 |
| `__func__.11723` | 0x125218 | 25 |
| `__func__.11736` | 0x125238 | 24 |
| `__func__.11733` | 0x125320 | 21 |
| `__func__.11748` | 0x125338 | 25 |
| `__func__.11762` | 0x125358 | 24 |
| `__func__.11784` | 0x125370 | 32 |
| `__func__.11541` | 0x125480 | 23 |
| `__func__.11305` | 0x126180 | 13 |
| `__func__.11339` | 0x126190 | 16 |
| `__func__.11353` | 0x1261a0 | 15 |
| `__func__.11375` | 0x1261b0 | 23 |
| `__FUNCTION__.13585` | 0x126950 | 35 |
| `__FUNCTION__.13623` | 0x126978 | 41 |
| `__func__.13725` | 0x1269a8 | 33 |
| `__func__.13738` | 0x1269d0 | 31 |
| `__FUNCTION__.12560` | 0x126b68 | 24 |
| `__FUNCTION__.12584` | 0x126b80 | 24 |
| `__FUNCTION__.14291` | 0x127340 | 23 |
| `__func__.14372` | 0x127358 | 37 |
| `__func__.13222` | 0x12bd70 | 18 |
| `__func__.12912` | 0x12bd98 | 17 |
| `__func__.12965` | 0x12bdb0 | 13 |
| `__func__.12927` | 0x12bdc0 | 13 |
| `__func__.13337` | 0x12bdd0 | 16 |
| `__FUNCTION__.14232` | 0x12c938 | 26 |
| `__func__.14345` | 0x12c958 | 33 |
| `__FUNCTION__.14369` | 0x12c980 | 28 |
| `__func__.14640` | 0x12c9a0 | 30 |
| `__func__.14727` | 0x12c9c0 | 34 |
| `__func__.14767` | 0x12c9e8 | 28 |
| `__func__.14795` | 0x12ca08 | 32 |
| `__func__.14967` | 0x12d0d0 | 29 |
| `__func__.15168` | 0x12d0f0 | 27 |
| `__FUNCTION__.15204` | 0x12d110 | 18 |
| `__FUNCTION__.15240` | 0x12d128 | 39 |
| `__func__.15267` | 0x12d150 | 27 |

<details><summary>… 另 185 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.12618` | 0x12d390 | 18 |
| `lensImprint.12585` | 0x12d3a8 | 16 |
| `__func__.12289` | 0x12d590 | 22 |
| `__func__.12321` | 0x12d5a8 | 26 |
| `__func__.12162` | 0x12d828 | 35 |
| `__func__.12635` | 0x12de78 | 22 |
| `__func__.12913` | 0x12de90 | 21 |
| `__func__.13662` | 0x12e450 | 30 |
| `__func__.11834` | 0x12e5b8 | 23 |
| `__func__.11847` | 0x12e5d0 | 22 |
| `__func__.13061` | 0x12e9f8 | 27 |
| `__FUNCTION__.13167` | 0x12ea18 | 11 |
| `LM26HSEPEN_MASK.11807` | 0x12f37f | 1 |
| `LM26HSEPEN_ADDR.11806` | 0x12f380 | 1 |
| `BLKDUMMY_LSB_ADDR.11838` | 0x12f381 | 1 |
| `BLKDUMMY_MSB_ADDR.11839` | 0x12f382 | 1 |
| `BLKLEVEL_LSB_ADDR.11843` | 0x12f383 | 1 |
| `BLKLEVEL_MSB_ADDR.11844` | 0x12f384 | 1 |
| `EXCKDLY_ADDR.11860` | 0x12f385 | 1 |
| `SPL.11682` | 0x12f58c | 4 |
| `SMD_ADDR.11701` | 0x12f590 | 1 |
| `SMD_MASK.11702` | 0x12f591 | 1 |
| `WINDOWMODE_ADDR.11709` | 0x12f592 | 1 |
| `WINDOWMODE_MASK.11710` | 0x12f593 | 1 |
| `WINDOWMODE_VAL_BDUMMY_WDUMMY_VOPB_EFFECTIVE.11712` | 0x12f594 | 1 |
| `WINDOWMODE_VAL_DISABLED.11711` | 0x12f595 | 1 |
| `ROW.11861` | 0x12f8b4 | 4 |
| `ROW.11945` | 0x12f8b8 | 4 |
| `__FUNCTION__.12384` | 0x12fa38 | 21 |
| `__FUNCTION__.12711` | 0x12fde8 | 11 |
| `__FUNCTION__.12006` | 0x12fe70 | 23 |
| `__func__.11810` | 0x131490 | 21 |
| `__func__.14547` | 0x132450 | 8 |
| `__func__.12208` | 0x132780 | 31 |
| `__func__.13018` | 0x132a10 | 19 |
| `__FUNCTION__.11765` | 0x133180 | 17 |
| `__FUNCTION__.11964` | 0x133198 | 31 |
| `__FUNCTION__.12036` | 0x1331b8 | 35 |
| `__FUNCTION__.12049` | 0x1331e0 | 46 |
| `__FUNCTION__.12065` | 0x133210 | 35 |
| `__FUNCTION__.12098` | 0x133238 | 23 |
| `AXI_HP1.11972` | 0x1336ec | 4 |
| `AXI_HP3.11973` | 0x1336f0 | 4 |
| `__func__.12826` | 0x133898 | 21 |
| `__FUNCTION__.12182` | 0x133a98 | 20 |
| `__func__.13294` | 0x133dd8 | 22 |
| `VCC_PL_INT.13019` | 0x134688 | 4 |
| `pl_por_b.13023` | 0x13468c | 4 |
| `pl_init.13024` | 0x134690 | 4 |
| `__FUNCTION__.11305` | 0x135c08 | 9 |
| `__FUNCTION__.11334` | 0x135c18 | 13 |
| `__FUNCTION__.11364` | 0x135c28 | 9 |
| `__FUNCTION__.11395` | 0x135c38 | 13 |
| `N.12148` | 0x135fbc | 4 |
| `__FUNCTION__.12420` | 0x137348 | 16 |
| `__func__.12898` | 0x137358 | 24 |
| `__func__.12914` | 0x137370 | 26 |
| `INVALID_CHANNEL.12312` | 0x137de4 | 1 |
| `__func__.12534` | 0x138478 | 17 |
| `__func__.12605` | 0x138490 | 12 |
| `__func__.12632` | 0x1384a0 | 16 |
| `__func__.14278` | 0x138bd0 | 36 |
| `__func__.13772` | 0x139168 | 33 |
| `__func__.13521` | 0x13a668 | 23 |
| `__func__.13887` | 0x13a680 | 22 |
| `__func__.14049` | 0x13a698 | 26 |
| `__func__.14071` | 0x13a6b8 | 20 |
| `__func__.14101` | 0x13a6d0 | 16 |
| `__func__.14229` | 0x13a6e0 | 29 |
| `__func__.14317` | 0x13a700 | 21 |
| `__func__.14336` | 0x13a718 | 9 |
| `__func__.12833` | 0x13b5b8 | 24 |
| `__func__.13025` | 0x13b5d0 | 27 |
| `__func__.14127` | 0x13c1a0 | 14 |
| `__func__.14220` | 0x13c1b0 | 17 |
| `max_unsynced_frames.14225` | 0x13c1c8 | 8 |
| `__func__.14250` | 0x13c1d0 | 46 |
| `__func__.14490` | 0x13c200 | 12 |
| `__func__.14665` | 0x13c210 | 15 |
| `__func__.14754` | 0x13c220 | 26 |
| `__func__.14546` | 0x13ca98 | 26 |
| `__func__.14560` | 0x13cab8 | 37 |
| `__func__.14666` | 0x13cae0 | 12 |
| `__func__.14719` | 0x13caf0 | 21 |
| `__func__.14749` | 0x13cb08 | 22 |
| `__func__.14816` | 0x13cb20 | 22 |
| `__func__.14829` | 0x13cb38 | 11 |
| `__func__.14998` | 0x13cb48 | 15 |
| `__func__.12601` | 0x13cde8 | 23 |
| `__func__.11931` | 0x13dd48 | 11 |
| `__func__.11962` | 0x13dd58 | 13 |
| `__func__.11995` | 0x13dd68 | 10 |
| `__FUNCTION__.11618` | 0x13e100 | 16 |
| `__FUNCTION__.11645` | 0x13e110 | 14 |
| `__func__.13374` | 0x13eca8 | 21 |
| `__FUNCTION__.13704` | 0x13ecc0 | 40 |
| `__FUNCTION__.13782` | 0x13ece8 | 35 |
| `__func__.12280` | 0x13ed78 | 39 |
| `__func__.13713` | 0x13f710 | 21 |
| `__func__.13719` | 0x13f728 | 22 |
| `__FUNCTION__.13728` | 0x13f740 | 22 |
| `__func__.13735` | 0x13f758 | 17 |
| `div.13744` | 0x13f76c | 4 |
| `steps.13745` | 0x13f770 | 4 |
| `dg_array.13741` | 0x13f778 | 8 |
| `ag_array.13742` | 0x13f780 | 8 |
| `ep_array.13743` | 0x13f788 | 8 |
| `__FUNCTION__.13812` | 0x13f790 | 39 |
| `__func__.13827` | 0x13f7b8 | 39 |
| `__func__.13877` | 0x13f7e0 | 25 |
| `__func__.13884` | 0x13f800 | 24 |
| `__func__.13937` | 0x13f818 | 34 |
| `__func__.13944` | 0x13f840 | 38 |
| `__func__.13948` | 0x13f868 | 34 |
| `__func__.14285` | 0x13f890 | 16 |
| `__func__.14379` | 0x13f8a0 | 25 |
| `__func__.14407` | 0x13f8c0 | 22 |
| `__func__.14460` | 0x13f8d8 | 17 |
| `__func__.14471` | 0x13f8f0 | 15 |
| `__func__.14495` | 0x13f900 | 30 |
| `__func__.14500` | 0x13f920 | 11 |
| `__func__.14508` | 0x13f930 | 19 |
| `__func__.14512` | 0x13f948 | 36 |
| `__func__.11936` | 0x13fa70 | 13 |
| `__func__.11975` | 0x13fa80 | 19 |
| `__func__.11985` | 0x13fa98 | 13 |
| `__func__.11994` | 0x13faa8 | 14 |
| `__FUNCTION__.12592` | 0x140070 | 21 |
| `__func__.12615` | 0x140088 | 17 |
| `__func__.12727` | 0x1400a0 | 26 |
| `__FUNCTION__.12226` | 0x1401b0 | 18 |
| `__FUNCTION__.15812` | 0x140760 | 17 |
| `__FUNCTION__.15997` | 0x140778 | 19 |
| `__FUNCTION__.12262` | 0x140e70 | 22 |
| `tribase.4252` | 0x141608 | 4 |
| `N.11109` | 0x141974 | 4 |
| `af_cur_pos_old.12576` | 0x14c378 | 4 |
| `oldState.14403` | 0x14c8c8 | 1 |
| `dynImprint.12586` | 0x14c8d8 | 16 |
| `md5_imx161.12509` | 0x14c8f8 | 16 |
| `md5_imx211.12510` | 0x14c908 | 16 |
| `pxVectorTable.10507` | 0x14c920 | 8 |
| `id.12802` | 0x14e014 | 4 |
| `id.12811` | 0x14e018 | 4 |
| `tmpDataBuffer.13282` | 0x15b2d8 | 257 |
| `prop_handler_msg.13187` | 0x160870 | 274 |
| `RecoveryImageNextPartition.14587` | 0x160ab0 | 2 |
| `resp.15176` | 0x160c28 | 5 |
| `old_point.15190` | 0x160c30 | 4 |
| `lastupdate.15192` | 0x160c34 | 4 |
| `gpioInit.13093` | 0x160d60 | 1 |
| `started.13610` | 0x160f12 | 1 |
| `b.14259` | 0x168cf0 | 514 |
| `msg.14501` | 0x168ef8 | 274 |
| `msg2.14502` | 0x169010 | 4 |
| `buf.14512` | 0x169018 | 256 |
| `mode.14527` | 0x169118 | 1 |
| `stopdown.14617` | 0x169119 | 1 |
| `old_checksum.13192` | 0x169208 | 4 |
| `b.12139` | 0x169cb0 | 65 |
| `FileInfo.12794` | 0x16a8a0 | 24 |
| `retry.14552` | 0x16c5bc | 2 |
| `ticks_since_last_dir_change.12532` | 0x16c7f0 | 2 |
| `lastState.12666` | 0x16c7f4 | 4 |
| `last_ts.13295` | 0x17adf0 | 8 |
| `retry_count.13082` | 0x17adfc | 4 |
| `check_id.14210` | 0x18bf2b | 1 |
| `last_id.14211` | 0x18bf2c | 1 |
| `aaa_stat.14629` | 0x18bf30 | 55616 |
| `info_update_cnt.14697` | 0x199870 | 4 |
| `ae_spi_count.13766` | 0x199874 | 4 |
| `noLensTraced.14575` | 0x1999f0 | 1 |
| `cnt.14435` | 0x1f3874 | 4 |
| `md5_digest.13555` | 0x11f3dc8 | 16 |
| `previousValue.13712` | 0x11f7db8 | 4 |
| `previousValue.13718` | 0x11f7dbc | 4 |
| `previous_value.13734` | 0x11f7dc0 | 8 |
| `count.13753` | 0x11f7dc8 | 4 |
| `index.13754` | 0x11f7dcc | 4 |
| `dgain.13746` | 0x11f7dd0 | 4 |
| `again.13747` | 0x11f7dd4 | 4 |
| `ep_ms.13748` | 0x11f7dd8 | 4 |
| `tmpDisabled.11345` | 0x11f86b8 | 1 |
| `flushType.14033` | 0x7f001d70 | 4 |
| `imageMode.14034` | 0x7f001d74 | 4 |

</details>

### `/bin/dji_wms`

+2 / −0 functions · +1 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE8DestructEPv` | 0xcf08 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE9ConstructEPvPKv` | 0xcf0c | 20 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes10E_DialModeEE14qt_metatype_idEvE11metatype_id` | 0x39c78 | 4 |

### `/bin/dji_wms-v1`

+2 / −0 functions · +1 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE8DestructEPv` | 0xbc68 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE9ConstructEPvPKv` | 0xbc6c | 20 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes10E_DialModeEE14qt_metatype_idEvE11metatype_id` | 0x24c68 | 4 |

### `/bin/phocus`

+2 / −0 functions · +1 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes16E_StopDownStatusELb1EE8DestructEPv` | 0x99894 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes16E_StopDownStatusELb1EE9ConstructEPvPKv` | 0x99898 | 20 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes16E_StopDownStatusEE14qt_metatype_idEvE11metatype_id` | 0xc3a80 | 4 |

### `/lib/libdcam_frwk.so`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `cam_cap_eng_set_capture_uid` | 0x3f891 | 212 |
| `cam_cap_eng_switch_stream_group` | 0x3f965 | 212 |

### `/lib/modules/ili2120.ko`

+0 / −2 functions · +2 / −3 objects

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `ili2120_i2c_suspend` | 0x5b0 | 56 |
| `ili2120_i2c_resume` | 0x5e8 | 56 |

**New objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `descriptor.26386` | 0x0 | 24 |
| `__func__.26387` | 0x14 | 18 |

**Removed objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `descriptor.26384` | 0x0 | 24 |
| `__func__.26385` | 0x14 | 18 |
| `ili2120_i2c_pm` | 0x58 | 92 |

### `/lib/weston/eagle-backend.so`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `ionhelper_get_heap_id` | 0xc0dd | 12 |

### `/bin/analytics`

+0 / −0 functions · +0 / −0 objects

### `/bin/audio`

+0 / −0 functions · +0 / −0 objects

### `/bin/bodystate`

+0 / −0 functions · +0 / −0 objects

### `/bin/bootlogo`

+0 / −0 functions · +0 / −0 objects

### `/bin/configstore`

+0 / −0 functions · +1 / −0 objects

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN9QtPrivate15ConnectionTypesINS_4ListIJbEEELb1EE5typesEvE1t` | 0x39a20 | 8 |

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

### `/bin/dji_iosconn`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_pbt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_ppt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_rcam`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/bin/gpsd`

+0 / −0 functions · +0 / −0 objects

### `/bin/metadata`

+0 / −0 functions · +0 / −0 objects

### `/bin/msg2dbus`

+0 / −0 functions · +0 / −0 objects

### `/bin/preview`

+0 / −0 functions · +0 / −0 objects

### `/bin/rcam_agent`

+0 / −0 functions · +0 / −0 objects

### `/bin/sutest`

+0 / −0 functions · +0 / −0 objects

### `/bin/sysman`

+0 / −0 functions · +0 / −0 objects

### `/bin/test_imgtec_venc_new`

+0 / −0 functions · +0 / −0 objects

### `/bin/test_vdev`

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

+0 / −0 functions · +31 / −31 objects

**New objects (31)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.12984` | 0x800a6a9 | 16 |
| `__FUNCTION__.12932` | 0x800a6ca | 17 |
| `__FUNCTION__.12885` | 0x800a6eb | 16 |
| `__FUNCTION__.12894` | 0x800a6fb | 17 |
| `__FUNCTION__.12943` | 0x800a70c | 17 |
| `__FUNCTION__.13002` | 0x800ac52 | 16 |
| `__FUNCTION__.12993` | 0x800ac62 | 16 |
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
| `__FUNCTION__.12790` | 0x800b204 | 14 |
| `__FUNCTION__.12730` | 0x800b212 | 14 |
| `__FUNCTION__.12825` | 0x800b220 | 22 |
| `__FUNCTION__.12798` | 0x800b236 | 15 |
| `__FUNCTION__.12738` | 0x800b245 | 15 |
| `__FUNCTION__.12747` | 0x800b254 | 13 |
| `__FUNCTION__.11983` | 0x800b48a | 13 |
| `__FUNCTION__.12012` | 0x800b497 | 27 |
| `__FUNCTION__.11994` | 0x800b4b2 | 12 |
| `__FUNCTION__.12019` | 0x800b4d5 | 14 |
| `__FUNCTION__.11961` | 0x800b678 | 22 |
| `SDO_ACT_ON.11951` | 0x800b68e | 1 |
| `__FUNCTION__.12005` | 0x800b68f | 27 |
| `__FUNCTION__.11976` | 0x800b6aa | 12 |

**Removed objects (31)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.12939` | 0x800a699 | 16 |
| `__FUNCTION__.12867` | 0x800a6b9 | 16 |
| `__FUNCTION__.12898` | 0x800a6c9 | 17 |
| `__FUNCTION__.12831` | 0x800a6fb | 17 |
| `__FUNCTION__.12930` | 0x800a70c | 16 |
| `__FUNCTION__.12840` | 0x800ac51 | 16 |
| `__FUNCTION__.12948` | 0x800ac61 | 16 |
| `__FUNCTION__.12887` | 0x800ac71 | 17 |
| `__FUNCTION__.12849` | 0x800ac92 | 17 |
| `__FUNCTION__.12858` | 0x800aca3 | 16 |
| `__func__.13271` | 0x800adb2 | 28 |
| `__func__.13260` | 0x800adce | 26 |
| `__func__.13267` | 0x800af7c | 23 |
| `__func__.13250` | 0x800af93 | 26 |
| `__FUNCTION__.12702` | 0x800b0d1 | 13 |
| `__FUNCTION__.12693` | 0x800b0f4 | 15 |
| `__FUNCTION__.12713` | 0x800b1f6 | 14 |
| `__FUNCTION__.12724` | 0x800b204 | 14 |
| `__FUNCTION__.12685` | 0x800b212 | 14 |
| `__FUNCTION__.12658` | 0x800b220 | 21 |
| `__FUNCTION__.12745` | 0x800b235 | 14 |
| `__FUNCTION__.12735` | 0x800b243 | 15 |
| `__FUNCTION__.12753` | 0x800b252 | 15 |
| `__FUNCTION__.11916` | 0x800b48a | 22 |
| `__FUNCTION__.11931` | 0x800b4a0 | 12 |
| `__FUNCTION__.11938` | 0x800b4b8 | 13 |
| `__FUNCTION__.11960` | 0x800b65a | 27 |
| `__FUNCTION__.11904` | 0x800b675 | 23 |
| `SDO_ACT_ON.11906` | 0x800b68c | 1 |
| `__FUNCTION__.11967` | 0x800b68d | 27 |
| `__FUNCTION__.11974` | 0x800b6a8 | 14 |

### `/lib/libAppsMessaging.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libLLVM.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libMessageTransport.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/lib_camcomp.so`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **740** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/victory-gui-static`

<details><summary>新增 184 条字符串, 展示前 100 条</summary>

````text
 c%3LS
"1Otrd8
#<FIGt
#M!#Ep
#TY+,k?
#Y7gpSh;
#o7!4M@
$-GI55
$BxHPY
&yxM_mR
)CH4cz
)qXvoZ
+cWTi3hu
-I0'eRX
-KF]llU|#&
-xjaWD
.[m~UB.
.n,9e!
/9u?QJ
/@>_vhE
/Custom buttons will be
/FHo;t
0MXczL
18=#JZ
2!:mV+Yi
2!CaENG
2qv3[a
3$mPOG
33f0y5
3F7i<N
3N$P. 
4shlGVJ
5-F7KY99
5_5wkO
7)1XhwR
7*qO6](
7J);`Fm
9b0CVa
:WqGsM%
<LCm9A
= 15lA
=f2Bcsh
>RUqcB
>zJ w1
BROWSE
Could not colorspace convert, no memory available!
D%zja4
DwLXIc
E /_k,
E_ErrorCode_DoExposureFailed
E_ErrorCode_UpgradeNoLensDetected
E_MetadataOverlay
E_MetadataOverlay_Base
E_MetadataOverlay_Detail
E_MetadataOverlay_HistLuminance
E_MetadataOverlay_HistSeparate
E_MetadataOverlay_Max
E_MetadataOverlay_None
E_UpgradeStatus_NoLensDetected
E_UserButtonFunction_Menu
EqMi5'
Error: No receiver
E{mFs5
F3Ax,cm
G&gY#X
HardwareID
Hardware_CFV_HighRes
Hardware_CFV_Moon
Hardware_Unknown
Hardware_X1DM2
HblmTypes::E_MetadataOverlay
I[B5_@
Ib$LRd
Instance
JL-jDj
N-(a2!M
NY`hCL!)
Nz~4pa
PqEPvm
QyiFjkA
RcHm.N
SCXg)+
Sbj9 -
Scaling failed: No c2d instance available
TY&;)mRmv
Uc59Gi
Umfcj.
WakeKeyState
WakeKeyState_Idle
WakeKeyState_LongExposureSuspend
WakeKeyState_ScreenOff
WakeKeyState_Suspend
XTQ3RDNJI5+
YC;Jzq
Z=ra5K-
ZMdva)TT
Z`4-@(
[Z1#i6j
]xFkXt
^bM2:b
````

</details>

> 其余 84 条见 `result.json`。

### `/lib/libappscommon.so`

<details><summary>新增 95 条字符串</summary>

````text
../../../../apps-messaging/proxies/datatransferproxy.cpp
E_ErrorCode_DoExposureFailed
E_ErrorCode_UpgradeNoLensDetected
E_MetadataOverlay
E_MetadataOverlay_Base
E_MetadataOverlay_Detail
E_MetadataOverlay_HistLuminance
E_MetadataOverlay_HistSeparate
E_MetadataOverlay_Max
E_MetadataOverlay_None
E_UpgradeStatus_NoLensDetected
E_UserButtonFunction_Menu
HardwareID
Hardware_CFV_HighRes
Hardware_CFV_Moon
Hardware_Unknown
Hardware_X1DM2
HblmTypes::E_MetadataOverlay
_ZN10ErrorProxy11ack_currentEi
_ZN10ErrorProxy13doAck_currentEv
_ZN11CameraProxy10setWb_tempEi
_ZN11CameraProxy10setWb_tintEi
_ZN11CameraProxy20request_img_transferEji
_ZN11CameraProxy22doRequest_img_transferEj
_ZN11CameraProxy26reprocess_raw_frame_bufferEy4QMapI7QString8QVariantEi
_ZN11CameraProxy28doReprocess_raw_frame_bufferEy4QMapI7QString8QVariantE
_ZN11ConfigProxy25setMetadata_overlay_indexEN9HblmTypes17E_MetadataOverlayE
_ZN11ConfigProxy28setDiagonal_joystick_enabledEb
_ZN11ConfigProxy33setUser_button_grip_menu_functionEN9HblmTypes20E_UserButtonFunctionE
_ZN11ConfigProxy33setUser_button_grip_play_functionEN9HblmTypes20E_UserButtonFunctionE
_ZN11SysmanProxy16farm_early_readyEbi
_ZN11SysmanProxy18doFarm_early_readyEb
_ZN15CamserviceProxy13capture_imageEji
_ZN15CamserviceProxy15doCapture_imageEj
_ZN17DatatransferProxy16send_imageResultEPK18PendingCallWatcherRj
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE9ConstructEPvPKv
_ZN17WmsProxyInterface17wifi_powerChangedEb
_ZN20CameraProxyInterface14wb_tempChangedEi
_ZN20CameraProxyInterface14wb_tintChangedEi
_ZN20ConfigProxyInterface29metadata_overlay_indexChangedEN9HblmTypes17E_MetadataOverlayE
_ZN20ConfigProxyInterface32diagonal_joystick_enabledChangedEb
_ZN20ConfigProxyInterface37user_button_grip_menu_functionChangedEN9HblmTypes20E_UserButtonFunctionE
_ZN20ConfigProxyInterface37user_button_grip_play_functionChangedEN9HblmTypes20E_UserButtonFunctionE
_ZN20SysmanProxyInterface23farm_early_readyChangedEb
_ZN20SysmanProxyInterface28long_exposure_suspendChangedEb
_ZN22ProfilesProxyInterface25resetting_profilesChangedEb
_ZN7Version10hardwareIDEv
_ZNK11CameraProxy7wb_tempEv
_ZNK11CameraProxy7wb_tintEv
_ZNK11ConfigProxy25diagonal_joystick_enabledEv
_ZNK11ConfigProxy30user_button_grip_menu_functionEv
_ZNK11ConfigProxy30user_button_grip_play_functionEv
_ZNK11SysmanProxy16farm_early_readyEv
_ZNK11SysmanProxy21long_exposure_suspendEv
_ZNK13ProfilesProxy18resetting_profilesEv
_ZNK8WmsProxy10wifi_powerEv
_ZZN11QMetaTypeIdIN9HblmTypes17E_MetadataOverlayEE14qt_metatype_idEvE11metatype_id
_in_farm_early_ready
ack_current
diagonal_joystick_enabled
diagonal_joystick_enabledChanged
doAck_current
doFarm_early_ready
farm_early_ready
farm_early_readyChanged
long_exposure_suspend
long_exposure_suspendChanged
resetting_profiles
resetting_profilesChanged
send_imageResult
user_button_grip_menu_function
user_button_grip_menu_functionChanged
user_button_grip_play_function
user_button_grip_play_functionChanged
virtual HblmTypes::E_MetadataOverlay ConfigProxy::metadata_overlay_index() const
virtual HblmTypes::E_UserButtonFunction ConfigProxy::user_button_grip_menu_function() const
virtual HblmTypes::E_UserButtonFunction ConfigProxy::user_button_grip_play_function() const
virtual PendingCallWatcher* CameraProxy::setWb_temp(int)
virtual PendingCallWatcher* CameraProxy::setWb_tint(int)
virtual PendingCallWatcher* ConfigProxy::setDiagonal_joystick_enabled(bool)
virtual PendingCallWatcher* ConfigProxy::setMetadata_overlay_index(HblmTypes::E_MetadataOverlay)
virtual PendingCallWatcher* ConfigProxy::setUser_button_grip_menu_function(HblmTypes::E_UserButtonFunction)
virtual PendingCallWatcher* ConfigProxy::setUser_button_grip_play_function(HblmTypes::E_UserButtonFunction)
virtual bool ConfigProxy::diagonal_joystick_enabled() const
virtual bool ProfilesProxy::resetting_profiles() const
virtual bool SysmanProxy::farm_early_ready() const
virtual bool SysmanProxy::long_exposure_suspend() const
virtual bool WmsProxy::wifi_power() const
virtual int CameraProxy::wb_temp() const
virtual int CameraProxy::wb_tint() const
wb_temp
wb_tempChanged
wb_tint
wb_tintChanged
````

</details>

### `/bin/camera`

<details><summary>新增 75 条字符串</summary>

````text
(%1 ms)
E_StorageStatus
ExposureResult
ExposureResult_Error
ExposureResult_None
ExposureResult_Transfer
Finishing state
HblmTypes::E_StorageStatus
Recieved message from FARM -> doRequest_img_transfer
_ZN10ErrorProxyC1EP7QObjectb
_ZN11QTextStreamlsEd
_ZN12StorageProxyC1EP7QObjectb
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_StorageStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_StorageStatusELb1EE9ConstructEPvPKv
_ZN20ConfigProxyInterface21wb_manual_tempChangedEi
_ZN20ConfigProxyInterface21wb_manual_tintChangedEi
_ZN20SysmanProxyInterface23farm_early_readyChangedEb
_ZN21StorageProxyInterface16staticMetaObjectE
_ZN21StorageProxyInterface21device0_statusChangedEN9HblmTypes15E_StorageStatusE
_ZN21StorageProxyInterface21device1_statusChangedEN9HblmTypes15E_StorageStatusE
_ZN21StorageProxyInterface27items_in_write_queueChangedEj
_ZN24CamserviceProxyInterface21wb_manual_tempChangedEi
_ZN24CamserviceProxyInterface21wb_manual_tintChangedEi
_ZN24CamserviceProxyInterface22free_buffer_numChangedEt
_ZN4QMapI7QString8QVariantE13detach_helperEv
_ZN7QObject10disconnectEPKS_PKcS1_S3_
_ZN9QDateTime15currentDateTimeEv
_ZN9QDateTimeC1ERKS_
_ZN9QDateTimeD1Ev
_ZN9QHashData8freeNodeEPv
_ZN9QtPrivate15ConnectionTypesINS_4ListIJP18PendingCallWatcherEEELb1EE5typesEv
_ZNK7QString7indexOfERKS_iN2Qt15CaseSensitivityE
_ZNK9QDateTime7msecsToERKS_
_ZTISt9bad_alloc
_ZZN11QMetaTypeIdIN9HblmTypes15E_StorageStatusEE14qt_metatype_idEvE11metatype_id
addProcessTime
camera is in session
camservice is busy
camservice status:
capture image in progress:
captureImage
captureImage: Pending call to camservice::capture_image finished
doCaptureImage
exposureCount:
exposureRequestFinished
finished exposure
frame_handle
free_buffer_num:
idleChanged
incoming image transfer count:
incomingImgTransferCountChanged
metadata_isp
microFocusAdjust:
onDevice0_statusChanged
onDevice1_statusChanged
processingCapImageCountChanged
remaining process time:
reprocess_raw_frame_buffer
sdcard0
sdcard1
start exposure
storage write count:
su_status:
system_state:
updateWbTemp
updateWbTint
void Camera::storageRemoved()
void ExposureRequest::onExposureDone()
waiting for any pending exposures to finish up
wbTempChanged
wbTintChanged
wb_temp
wb_tempChanged
wb_tint
wb_tintChanged
````

</details>

### `/bin/odindb-send`

<details><summary>新增 66 条字符串</summary>

````text
  E_ErrorCode_DoExposureFailed(85)
  E_ErrorCode_UpgradeNoLensDetected(84)
HblmTypes::E_MetadataOverlay
_ZN10ErrorProxy11ack_currentEi
_ZN10ErrorProxy13doAck_currentEv
_ZN11CameraProxy10setWb_tempEi
_ZN11CameraProxy10setWb_tintEi
_ZN11CameraProxy20request_img_transferEji
_ZN11CameraProxy22doRequest_img_transferEj
_ZN11CameraProxy26reprocess_raw_frame_bufferEy4QMapI7QString8QVariantEi
_ZN11CameraProxy28doReprocess_raw_frame_bufferEy4QMapI7QString8QVariantE
_ZN11ConfigProxy25setMetadata_overlay_indexEN9HblmTypes17E_MetadataOverlayE
_ZN11ConfigProxy28setDiagonal_joystick_enabledEb
_ZN11ConfigProxy33setUser_button_grip_menu_functionEN9HblmTypes20E_UserButtonFunctionE
_ZN11ConfigProxy33setUser_button_grip_play_functionEN9HblmTypes20E_UserButtonFunctionE
_ZN11SysmanProxy16farm_early_readyEbi
_ZN11SysmanProxy18doFarm_early_readyEb
_ZN15CamserviceProxy13capture_imageEji
_ZN15CamserviceProxy15doCapture_imageEj
_ZN17DatatransferProxy16send_imageResultEPK18PendingCallWatcherRj
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_MetadataOverlayELb1EE9ConstructEPvPKv
_ZN17WmsProxyInterface17wifi_powerChangedEb
_ZN20CameraProxyInterface14wb_tempChangedEi
_ZN20CameraProxyInterface14wb_tintChangedEi
_ZN20ConfigProxyInterface29metadata_overlay_indexChangedEN9HblmTypes17E_MetadataOverlayE
_ZN20ConfigProxyInterface32diagonal_joystick_enabledChangedEb
_ZN20ConfigProxyInterface37user_button_grip_menu_functionChangedEN9HblmTypes20E_UserButtonFunctionE
_ZN20ConfigProxyInterface37user_button_grip_play_functionChangedEN9HblmTypes20E_UserButtonFunctionE
_ZN20SysmanProxyInterface23farm_early_readyChangedEb
_ZN20SysmanProxyInterface28long_exposure_suspendChangedEb
_ZN22ProfilesProxyInterface25resetting_profilesChangedEb
_ZNK11CameraProxy7wb_tempEv
_ZNK11CameraProxy7wb_tintEv
_ZNK11ConfigProxy25diagonal_joystick_enabledEv
_ZNK11ConfigProxy30user_button_grip_menu_functionEv
_ZNK11ConfigProxy30user_button_grip_play_functionEv
_ZNK11SysmanProxy16farm_early_readyEv
_ZNK11SysmanProxy21long_exposure_suspendEv
_ZNK13ProfilesProxy18resetting_profilesEv
_ZNK8WmsProxy10wifi_powerEv
_ZZN11QMetaTypeIdIN9HblmTypes17E_MetadataOverlayEE14qt_metatype_idEvE11metatype_id
ack_current
ack_current()
bool farm_early_ready // 
capture_image(uint uid)
diagonal_joystick_enabled = %1
diagonal_joystick_enabledChanged
farm_early_ready
farm_early_ready = %1
farm_early_ready(bool farm_early_ready)
farm_early_readyChanged
long_exposure_suspend = %1
long_exposure_suspendChanged
metadata_overlay_index = %1(%2)
request_img_transfer(uint uid)
resetting_profiles = %1
resetting_profilesChanged
user_button_grip_menu_function = %1(%2)
user_button_grip_menu_functionChanged
user_button_grip_play_function = %1(%2)
user_button_grip_play_functionChanged
wb_temp = %1
wb_tempChanged
wb_tint = %1
wb_tintChanged
````

</details>

### `/bin/dji_wms`

<details><summary>新增 46 条字符串</summary>

````text
E_DialMode
Fix power status
HblmTypes::E_DialMode
Ignoring link_type changed to keep connection alive, changing to C-mode
WMS_EC1704,00.00.00.86,20200612-16:12:25
_ZN11CameraProxyC1EP7QObjectb
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE9ConstructEPvPKv
_ZN20CameraProxyInterface16staticMetaObjectE
_ZN20CameraProxyInterface24current_dial_modeChangedEN9HblmTypes10E_DialModeE
_ZN5QTime11currentTimeEv
_ZNK5QTime7isValidEv
_ZNK5QTime7msecsToERKS_
_ZZN11QMetaTypeIdIN9HblmTypes10E_DialModeEE14qt_metatype_idEvE11metatype_id
__FD_ISSET_chk
blocked to keep current connection alive, changing to C-mode
bt_loop_mtx
dialModeChanged
eventfd
hardware/dji/service/wms/build/EC1704/../../bt/qca6174a/bt_config.c
hardware/dji/service/wms/build/EC1704/../../bt/qca6174a/server/att.c
hardware/dji/service/wms/build/EC1704/../../bt/qca6174a/server/bt-whitelist.c
hardware/dji/service/wms/build/EC1704/../../bt/qca6174a/server/btgatt-server.c
hardware/dji/service/wms/build/EC1704/../../bt/qca6174a/server/gatt-server.c
hardware/dji/service/wms/build/EC1704/../../bt/qca6174a/server/mainloop.c
hardware/dji/service/wms/build/EC1704/../../device/common/simple_acs.c
hardware/dji/service/wms/build/EC1704/../../device/qca6174a/qca6174_bss_mgmt.c
hardware/dji/service/wms/build/EC1704/../../host_interface/comm_utils.c
hardware/dji/service/wms/build/EC1704/../../host_interface/eagle/plat_wifi_config.c
hardware/dji/service/wms/build/EC1704/../../lib_interface/wms_interface.c
hardware/dji/service/wms/build/EC1704/../../v1_interface/duss_ipc/wms_gpio.c
hardware/dji/service/wms/build/EC1704/../../wifi_mgmt/bss_mgmt.c
hardware/dji/service/wms/build/EC1704/../../wifi_mgmt/wifi_config.c
wifi_power
wifi_powerChanged
wms: clear exit_signal
wms: wms_bt bt exit signal filed.
wms: wms_bt bt_init exit signal eventfd created %d.
wms: wms_bt bt_init failed create exit event
wms: wms_bt bt_init failed create mutex
wms: wms_bt select fds %d & %d
wms: wms_bt select ready fds
wms: wms_run exit signal write %d
wms: wms_run kick event fd to let bt listen quit
wms: wms_run really set lpm
wms: wms_run wms_bt failed get wms_info
````

</details>

### `/bin/dji_wms-v1`

<details><summary>新增 29 条字符串</summary>

````text
E_DialMode
Fix power status
HblmTypes::E_DialMode
Ignoring link_type changed to keep connection alive, changing to C-mode
WMS_EC1704,00.00.00.86,20200612-16:12:25
_ZN11CameraProxyC1EP7QObjectb
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes10E_DialModeELb1EE9ConstructEPvPKv
_ZN20CameraProxyInterface16staticMetaObjectE
_ZN20CameraProxyInterface24current_dial_modeChangedEN9HblmTypes10E_DialModeE
_ZN5QTime11currentTimeEv
_ZNK5QTime7isValidEv
_ZNK5QTime7msecsToERKS_
_ZZN11QMetaTypeIdIN9HblmTypes10E_DialModeEE14qt_metatype_idEvE11metatype_id
blocked to keep current connection alive, changing to C-mode
dialModeChanged
hardware/dji/service/wms/build/EC1704/../../device/common/simple_acs.c
hardware/dji/service/wms/build/EC1704/../../device/qca6174a/qca6174_bss_mgmt.c
hardware/dji/service/wms/build/EC1704/../../host_interface/comm_utils.c
hardware/dji/service/wms/build/EC1704/../../host_interface/eagle/plat_wifi_config.c
hardware/dji/service/wms/build/EC1704/../../lib_interface/wms_interface.c
hardware/dji/service/wms/build/EC1704/../../v1_interface/duss_ipc/wms_gpio.c
hardware/dji/service/wms/build/EC1704/../../v1_interface/duss_ipc/wms_run.c
hardware/dji/service/wms/build/EC1704/../../v1_interface/v1_proc.c
hardware/dji/service/wms/build/EC1704/../../v1_interface/v1_wireless_test.c
hardware/dji/service/wms/build/EC1704/../../wifi_mgmt/bss_mgmt.c
hardware/dji/service/wms/build/EC1704/../../wifi_mgmt/wifi_config.c
wifi_power
wifi_powerChanged
````

</details>

### `/bin/phocus`

<details><summary>新增 26 条字符串</summary>

````text
FocusPoint
FocusPointAlignment
FocusSize
FocusSizeList
HblmTypes::E_StopDownStatus
StopDown
Stream off during tethered liveview, reset to host requested tethered mode:
Stream off notification inhibited
_ZN10ErrorProxyC1EP7QObjectb
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes16E_StopDownStatusELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes16E_StopDownStatusELb1EE9ConstructEPvPKv
_ZN17SeqProxyInterface24current_stop_downChangedEN9HblmTypes16E_StopDownStatusE
_ZN17WmsProxyInterface17wifi_powerChangedEb
_ZN20CameraProxyInterface17focus_sizeChangedEj
_ZN20CameraProxyInterface18focus_pointChangedEj
_ZZN11QMetaTypeIdIN9HblmTypes16E_StopDownStatusEE14qt_metatype_idEvE11metatype_id
failed to send shm data
focus_point
focus_size
heap id:
onFocusPointChanged
onFocusSizeChanged
onStopDownChanged
requested size:
stopDown
successfully sent shm data
````

</details>

### `/bin/camservice`

<details><summary>新增 25 条字符串</summary>

````text
Could not colorspace convert, no memory available!
HblmTypes::E_ImageFormat
HblmTypes::E_VideoStream
N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_NSt3__110shared_ptrIN3dji6camera14ICameraServiceEEENS5_10OutputTypeEENS3_INS5_13CameraServiceEEES8_EE
N12QtConcurrent18StoredFunctorCall2I7QStringPFS1_jNSt3__110shared_ptrIN3dji6camera14ICameraServiceEEEEjNS3_INS5_13CameraServiceEEEEE
Scaling failed: No c2d instance available
_Z17qRegisterMetaTypeIN9HblmTypes13E_ImageFormatEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_ImageFormatELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_ImageFormatELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_VideoStreamELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes13E_VideoStreamELb1EE9ConstructEPvPKv
_ZN20CameraProxyInterface17zoom_pointChangedEj
_ZN20CameraProxyInterface19image_formatChangedEN9HblmTypes13E_ImageFormatE
_ZN20CameraProxyInterface23videostream_modeChangedEN9HblmTypes13E_VideoStreamE
_ZZN11QMetaTypeIdIN9HblmTypes13E_ImageFormatEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes13E_VideoStreamEE14qt_metatype_idEvE11metatype_id
getOutputType
heap id:
imageFormatChanged
requested size:
uint32_t
videoStreamModeChanged
videostream
zoomPointChanged
zoompoint
````

</details>

### `/lib/libservice.so`

<details><summary>新增 24 条字符串</summary>

````text
*N5rxcpp6detail15safe_subscriberINS_18dynamic_observableIN3dji6camera15RecordingStatusEEENS_10subscriberIS5_NS_8observerIS5_NS0_22stateless_observer_tagEZNS4_13CaptureEngine4initEP17text_setting_filePNS4_16ICaptureListenerEP11usbd_clientEUlS5_E8_vvEEEEEE
*N5rxcpp6detail17specific_observerIN3dji6camera15RecordingStatusENS_8observerIS4_NS0_22stateless_observer_tagEZNS3_13CaptureEngine4initEP17text_setting_filePNS3_16ICaptureListenerEP11usbd_clientEUlS4_E8_vvEEEE
*NSt3__110__function6__funcIN5rxcpp6detail15safe_subscriberINS2_18dynamic_observableIN3dji6camera15RecordingStatusEEENS2_10subscriberIS8_NS2_8observerIS8_NS3_22stateless_observer_tagEZNS7_13CaptureEngine4initEP17text_setting_filePNS7_16ICaptureListenerEP11usbd_clientEUlS8_E8_vvEEEEEENS_9allocatorISN_EEFvRKNS2_10schedulers11schedulableEEEE
*NSt3__120__shared_ptr_emplaceIN5rxcpp6detail17specific_observerIN3dji6camera15RecordingStatusENS1_8observerIS6_NS2_22stateless_observer_tagEZNS5_13CaptureEngine4initEP17text_setting_filePNS5_16ICaptureListenerEP11usbd_clientEUlS6_E8_vvEEEENS_9allocatorISI_EEEE
Invalid output format
RetCode dji::camera::CaptureEngine::setOutputType(dji::camera::OutputType)
_ZN3dji6camera13CameraService13setOutputTypeENS0_10OutputTypeE
_ZN3dji6camera13CameraService7captureEj
_ZN3dji6camera13CaptureEngine13setOutputTypeENS0_10OutputTypeE
_ZN3dji6camera13CaptureEngine7captureEj
_ZN3dji6camera15RecordingEngine10stopWorkerENS0_14RecordingStateE
_ZNK3dji6camera13CaptureEngine4zoomEv
_ZNK3dji6camera13CaptureEngine9zoomPointEv
_ZThn4_N3dji6camera13CameraService13setOutputTypeENS0_10OutputTypeE
cam_cap_eng_set_capture_uid
cam_cap_eng_switch_stream_group
capture one frame %d
getCaptureParameter
on_captured_image jpeg[frame id: %d, uid: %d]
on_captured_image raw[frame id: %d, uid: %d]
on_free_buffer_count_changed, status:%d, free_buffer_count_: %d
recordingData
recordingData worker is not running
setOutputType
````

</details>

### `/etc/firmware/rtnodes/app.elf`

<details><summary>新增 23 条字符串</summary>

````text
 missing                       - Report calibration file missing
10.00.21.53-8aac72e
10.00.21.53-a18bfa0
23:30:10
Jul 14 2020
[%s] %s%s transfer FAILURE for uid %d!
[%s] %s%s transferred successfully for uid %d.
[%s] %sFailed to set farm early ready
[%s] %sfarm_sig_image_transfer_uid: %d
a18bfa0
calib_data
diagonal_joystick_enabled
farm_early_ready
long_exposure_suspend
missing
resetting_profiles
sysman_changed_farm_early_ready
sysman_farm_early_ready_req
sysman_farm_early_ready_resp
user_button_grip_menu_function
user_button_grip_play_function
wb_temp
wb_tint
````

</details>

### `/bin/usbd`

````text
FUNCTIONFS_BIND
FUNCTIONFS_DISABLE
FUNCTIONFS_ENABLE
FUNCTIONFS_RESUME
FUNCTIONFS_SETUP
FUNCTIONFS_SUSPEND
FUNCTIONFS_UNBIND
USBD_BUFFER_TYPE_DUSS_HANDLE
_ZN10QByteArray6resizeEi
_ZN11QTextStreamlsEl
cmd_id: USBD_CMD_ID_TRANSFER
failed to open directory
heap id:
m_usbLink:
msg_size:
requested size:
transaction_id:
transfer time:
type: USBD_BUFFER_TYPE_MEM
````

### `/lib/libdcam_frwk.so`

````text
%s: transfer time: %ld us, packets: %d, delay: %d
%s: write() failed: %d
BYR2usbd_enqueue_buffer
BufferManager: stream_group: %p stream_group:%s, new_pool_size:%d new_liveview_size: %d, pool_size:%d, free_size:%d
CamCapEng: send_and_wait(CAPENG_MSG_SET_CAPTURE_UID) failed:%d 
CamCapEng: send_and_wait(CAPENG_MSG_SWITCH_STREAM_GROUP) failed:%d
DCAM_STREAM_FLAG_LIVEVIEW_EXCLUSIVE
JpegStillHandler: current usage common (%d bytes)
JpegStillHandler: current usage panorama (%d bytes)
_on_switch_stream_group
cam_cap_eng_set_capture_uid
cam_cap_eng_switch_stream_group
max_encoded_size
max_number_in_processing
params->on_busy_buffer_count_changed
params->on_free_buffer_count_changed
````

### `/bin/storage`

````text
, active threads in pool: 
, uid:
Could not colorspace convert, no memory available!
Instance
Invalid cast! Aborting
Sanity timeout uid:
Scaling failed: No c2d instance available
Scheduling sanity timeout for uid:
Scrapping request, cancel reason:
Spawning new background thread for scale4kPreview
Unhandled bitrate
_ZNK16SnapshotMetadata3uidEv
heap id:
requested size:
videoSecondSize
````

### `/bin/configstore`

````text
_ZN12QDBusMessageC1ERKS_
_ZZN9QtPrivate15ConnectionTypesINS_4ListIJbEEELb1EE5typesEvE1t
diagonal_joystick_enabled
diagonal_joystick_enabled_maxval
diagonal_joystick_enabled_minval
resetting_profiles
resetting_profilesChanged
user_button_grip_menu_function
user_button_grip_menu_function_maxval
user_button_grip_menu_function_minval
user_button_grip_play_function
user_button_grip_play_function_maxval
user_button_grip_play_function_minval
````

### `/bin/sysman`

````text
Emit new farm_early_ready
Failed to ACK error!
Failed to read SUC state
_ZN20CameraProxyInterface27exposures_in_sessionChangedEi
ackCurrent
ack_current
farmEarlyReadyChanged
farm_early_ready
farm_early_readyChanged
longExpSuspendChanged
long_exposure_suspend
long_exposure_suspendChanged
setFarmEarlyReady
````

### `/bin/rcam_agent`

````text
calling datatransfer : %s()
calling datatransfer : send_image() transfer_type: %d
calling farmus : set_videomode() width: %d height: %d
dbus_message_iter_get_arg_type
dbus_message_iter_get_basic
dbus_message_iter_init
received error response from datatransfer : %s(), error: %s message: %s
received error response from datatransfer : send_image(), error: %s message: %s
received error response from datatransfer : set_videomode(), error: %s message: %s
received response from datatransfer : %s()
received response from datatransfer : send_image() uid: %d
received response from datatransfer : set_videomode()
````

### `/lib/weston/eagle-backend.so`

````text
%s: Disable glove detection
%s: Failed to control jdi power. Err: %d
%s: Failed to open Touch: %s, errno: %d
%s: Failed to read CPLD register 0x%x
%s: Failed to set CPLD register 0x%x, val: %d
/dev/i2c-5
Vjdi_open
bl_core_sysfs_getlcd_power
ili2120_init_touch_no_glove
ionhelper_get_heap_id
````

### `/bin/preview`

````text
Could not colorspace convert, no memory available!
Instance
Scaling failed: No c2d instance available
heap id:
requested size:
````

### `/bin/msg2dbus`

````text
_ZN20SysmanProxyInterface23farm_early_readyChangedEb
farm_early_ready
onFarm_early_readyChanged
onFarm_early_readyFinished
````

### `/lib/libAppsMessaging.so`

````text
a18bfa0
sysman_changed_farm_early_ready
sysman_farm_early_ready_req
sysman_farm_early_ready_resp
````

### `/lib/libduml_frwk.so`

````text
23:38:28
23:38:29
43c3a35bd7f610530a6d076680460cf292d18f93baada3367b6fab44c550e558
Jul 14 2020
````

### `/bin/dji_sys`

````text
23:39:36
23:39:37
Jul 14 2020
````

### `/bin/upgraded`

````text
CUpgrade::Version
_ZN7Version10hardwareIDEv
_ZNK7QString3argEyii5QChar
````

### `/bin/analytics`

````text
heap id:
requested size:
````

### `/bin/dji_amt`

````text
23:39:26
Jul 14 2020
````

### `/bin/dji_blackbox`

````text
23:39:26
Jul 14 2020
````

### `/bin/vdec_test`

````text
00:03:33
Jul 15 2020
````

### `/bin/vxe_testbench`

````text
00:03:20
Jul 15 2020
````

### `/lib/libLLVM.so`

````text
23:42:31
Jul 14 2020
````

### `/lib/libduml_hal_cam.so`

````text
CAM_HAL: capture failed with timeout
[%s:%d ERROR]: lib_vdev(%s): poll timeout error
````

### `/lib/libhelper_api_sa.so`

````text
00:01:41
Jul 15 2020
````

### `/lib/libomx_vxd.so`

````text
00:03:33
Jul 15 2020
````

### `/bin/bootlogo`

````text
ion_mem_alloc() heap_id(%d) MUST be in [0, 16)
````

### `/bin/debuggerd`

````text
debuggerd: Jul 14 2020 23:39:22
````

### `/bin/dji_cspp`

````text
DCAM_STREAM_FLAG_LIVEVIEW_EXCLUSIVE
````

### `/bin/dji_iosconn`

````text
iosc: invalid fd
````

### `/bin/test_imgtec_venc_new`

````text
ion_mem_alloc() heap_id(%d) MUST be in [0, 16)
````

### `/bin/test_vdev`

````text
[%s:%d ERROR]: lib_vdev(%s): poll timeout error
````

### `/lib/libduml_hal.so`

````text
ion_mem_alloc() heap_id(%d) MUST be in [0, 16)
````

### `/lib/modules/rcam_dji.ko`

````text
mipi_rx_send_stream
````

### `/bin/audio`

````text
````

### `/bin/bodystate`

````text
````

### `/bin/dji_cht`

````text
````

### `/bin/dji_pbt`

````text
````

### `/bin/dji_ppt`

````text
````

### `/bin/dji_rcam`

````text
````

### `/bin/gpsd`

````text
````

### `/bin/metadata`

````text
````

### `/bin/sutest`

````text
````

### `/etc/firmware/rtnodes/cfv-control.elf`

````text
````

## Scripts & Config

共 7 个脚本/配置变更, 252 行 unified diff（context=3, 预算上限 2000 行）。

### `/bin/exposure_test_function.sh`

101 行

````diff
--- a//bin/exposure_test_function.sh
+++ b//bin/exposure_test_function.sh
@@ -7,16 +7,57 @@
 #
 # 2019.10
 
+db_camera_get_string()
+{
+    echo $(odindb-send -s camera -p $1 | awk -F'[=()]' '{ gsub(/ /, "", $0); print $2 }')
+}
+
+db_camera_get_num()
+{
+    echo $(odindb-send -s camera -p $1 | tr -dc '0-9')
+}
+
+# Perform an exposure with fixed exposure settings.
+# If the camera is set to an exposure mode other than Image/Manual then CFV will sit to the desired mode
+#  and then reset it after the test while Mk2 will fail the test since its not possible to change
+#  expsure mode programatically.
+# Resulting image file is removed at the end of the test.
 test_do_exposure()
 {
     local ret_status=$RET_SUCCESS
     local raw=0
     local show_live_view_when_finished=0
-    local saved_format=$(odindb-send -s camera -p image_format | tr -dc '0-9')
+    local logstart=`date "+%m-%d %H:%M:%S.0"`
+
+    ### Store exposure settings
+    local saved_format=$(db_camera_get_num image_format)
+    local camera_type=$(db_camera_get_string camera_type)
+    local camera_mode=$(db_camera_get_string camera_mode)
+    local exp_mode=$(db_camera_get_string exp_mode)
+    local drive_mode=$(db_camera_get_string drive_mode)
+    local av_selected=$(db_camera_get_num av_selected)
+    local tv_selected=$(db_camera_get_num tv_selected)
+
+
+    ### Setup camera
     odindb-send -s camera -p image_format $raw
+    if [ $camera_type = "E_CameraType_Cfv907x" ]; then
+        # Make sure we are in Manual, Image mode
+        odindb-send -s camera -p camera_mode E_CameraMode_Image
+        odindb-send -s camera -m set_exposure_mode E_ExpMode_Manual
+    elif [ $exp_mode != "E_ExpMode_Manual" -o $camera_mode != "E_CameraMode_Image" ]; then
+        echo "Must use Image/Manual mode"
+        return $RET_ERROR
+    fi
+    # Make sure we are not in interval/bracketing modes
+    odindb-send -s camera -p drive_mode E_DriveModes_Single
+    # AV 54 = f/4.8 should exist on all lenses
+    odindb-send -s camera -p av_selected 54
+    # TV 72 = 1/60 makes it possible to setup this test for rear flash
+    odindb-send -s camera -p tv_selected 72
 
-    # clear log
-    logcat -c
+    # Make sure there is no error message displayed since this would prevent LV and exposure
+    odindb-send -s error -m ack_current > /dev/null
 
     odindb-send -s camera -m do_exposure $show_live_view_when_finished
     if [ $? != 0 ]; then
@@ -24,13 +65,14 @@
         ret_status=$RET_ERROR
     fi
 
+    ### Perform exposure
     local timeout=25
     local filename=""
     while [ $ret_status == $RET_SUCCESS ] && [ -z $filename ] && [ $timeout -gt 0 ]
     do
         echo "Waiting for file written"
         timeout=$((timeout-1))
-        filename=$(logcat -d | grep "KPI_FILE_WRITTEN" | awk '{print $12}')
+        filename=$(logcat -t "${logstart}" -d | grep "KPI_FILE_WRITTEN" | awk '{print $12}')
         sleep 1
     done
 
@@ -39,8 +81,15 @@
         ret_status=$RET_ERROR
     fi
 
-    # Restore
+    ### Restore exposure settings
     odindb-send -s camera -p image_format $saved_format
+    odindb-send -s camera -p drive_mode $drive_mode
+    odindb-send -s camera -p av_selected $av_selected
+    odindb-send -s camera -p tv_selected $tv_selected
+    if [ $camera_type = "E_CameraType_Cfv907x" ]; then
+        odindb-send -s camera -m set_exposure_mode $exp_mode
+        odindb-send -s camera -p camera_mode $camera_mode
+    fi
 
     if [ $ret_status == $RET_SUCCESS ]; then
         trimmed_filename=$(echo $filename | tr -d '"')
@@ -51,4 +100,3 @@
 
     return $ret_status
 }
-
````

### `/bin/test_lens_link.sh`

43 行

````diff
--- a//bin/test_lens_link.sh
+++ b//bin/test_lens_link.sh
@@ -20,6 +20,7 @@
 # Simple test to see if SUC has detected lens
 test_lens_hotplug()
 {
+    echo -e "\ntest_lens_hotplug()"
     local ret_status=$RET_SUCCESS
     odindb-send -s suc -m func_test E_FuncTestModule_LensIf E_FuncTestAction_Start 0 0 0
     if [ $? != $RET_SUCCESS ]; then
@@ -32,12 +33,16 @@
 # Triggers autofocus and checks at farmus that focus position is updated
 test_lens_af_ulan()
 {
+    echo -e "\ntest_lens_af_ulan()"
     local ret_status=$RET_SUCCESS
     odindb-send -s farmus -m func_test E_FuncTestModule_LensIf E_FuncTestAction_Stop 0 0 0
     odindb-send -s camera -m set_live_view_state 0
     sleep 1
 
     odindb-send -s farmus -m func_test E_FuncTestModule_LensIf E_FuncTestAction_Start 30 0 0
+
+    # Make sure there is no error message displayed since this would prevent LV and AF
+    odindb-send -s error -m ack_current > /dev/null
 
     # This starts a session and forces AF
     odindb-send -s camera -m start_session false true
@@ -60,6 +65,7 @@
 # Does an exposure, operator must detect flash
 test_lens_flash_sync_pin()
 {
+    echo -e "\ntest_lens_flash_sync_pin()"
     local ret_status=$RET_SUCCESS
     test_do_exposure
     if [ $? != 0 ]; then
@@ -74,6 +80,7 @@
 # Performs a preflash, operator must detect flash
 test_lens_hotshoe()
 {
+    echo -e "\ntest_lens_hotshoe()"
     local ret_status=$RET_SUCCESS
     odindb-send -s suc -m func_test E_FuncTestModule_HotShoe E_FuncTestAction_Start 0 0 0
     if [ $? != 0 ]; then
````

### `/bin/test_mic_function.sh`

28 行

````diff
--- a//bin/test_mic_function.sh
+++ b//bin/test_mic_function.sh
@@ -137,6 +137,12 @@
     echo "config 369 to IN1R fail"
     return 2
 fi
+# Set analog gain to 0
+tinymix -C 8 0 -C 9 0
+if [ $? != 0 ]; then
+    echo "config 8 and 9 to 0(val) fail"
+    return 3
+fi
 tinymix 17 $value
 if [ $? != 0 ]; then
     echo "config 17 to 136(val) fail"
@@ -172,6 +178,12 @@
 if [ $? != 0 ]; then
     echo "config 369 to IN1R fail"
     return 2
+fi
+# Set analog gain to 0
+tinymix -C 8 0 -C 9 0
+if [ $? != 0 ]; then
+    echo "config 8 and 9 to 0(val) fail"
+    return 3
 fi
 #set "IN1L Digital Volume" to 136
 tinymix 17 $value
````

### `/bin/test_mic_headphone_link.sh`

24 行

````diff
--- a//bin/test_mic_headphone_link.sh
+++ b//bin/test_mic_headphone_link.sh
@@ -77,6 +77,8 @@
     get_and_kill_pid "tinyplay"
     return 0
 }
+
+
 #config external analog mic
 tinymix 365 IN1L
 if [ $? != 0 ]; then
@@ -87,6 +89,12 @@
 if [ $? != 0 ]; then
     echo "config 369 to IN1R fail"
     return 2
+fi
+# Set analog gain to 0
+tinymix -C 8 0 -C 9 0
+if [ $? != 0 ]; then
+    echo "config 8 and 9 to 0(val) fail"
+    return 3
 fi
 tinymix 17 180
 if [ $? != 0 ]; then
````

### `/bin/test_mic_spk_link.sh`

24 行

````diff
--- a//bin/test_mic_spk_link.sh
+++ b//bin/test_mic_spk_link.sh
@@ -81,6 +81,8 @@
     get_and_kill_pid "tinyplay"
     return 0
 }
+
+
 #config external analog mic
 tinymix 365 IN1L
 if [ $? != 0 ]; then
@@ -91,6 +93,12 @@
 if [ $? != 0 ]; then
     echo "config 369 to IN1R fail"
     return 2
+fi
+# Set analog gain to 0
+tinymix -C 8 0 -C 9 0
+if [ $? != 0 ]; then
+    echo "config 8 and 9 to 0(val) fail"
+    return 3
 fi
 tinymix 17 136
 if [ $? != 0 ]; then
````

### `/build.prop`

10 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,4 +1,4 @@
 
-ro.vendor.build.date=Fri May 29 22:31:13 CST 2020
-ro.vendor.build.date.utc=1590762673
-ro.vendor.build.fingerprint=eagle/full_eagle_ec1704/eagle_ec1704:6.0/MDB08M/1725:userdebug/test-keys
+ro.vendor.build.date=Wed Jul 15 00:04:09 CST 2020
+ro.vendor.build.date.utc=1594742649
+ro.vendor.build.fingerprint=eagle/full_eagle_ec1704/eagle_ec1704:6.0/MDB08M/1786:userdebug/test-keys
````

### `/etc/dji_camera.conf`

22 行

````diff
--- a//etc/dji_camera.conf
+++ b//etc/dji_camera.conf
@@ -70,7 +70,7 @@
     res_1920x1080_fps_25       = 12000000, 25000000, 35000000
     res_2720x1530_fps_30       = 20000000, 35000000, 100000000
     res_1920x1080_fps_30       = 12000000, 25000000, 50000000
-    res_2756x1240_fps_30       = 5000000,  25000000, 50000000
+    res_2756x1240_fps_30       = 5000000,  15000000, 50000000
 
 [hiso:ceva]
     #option: always_yuv, always_y, always_uv, disable, auto
@@ -140,8 +140,9 @@
     dump_without_padding = true
 
 [still_handler:jpeg]
-    # 8384 * 6304 * 1.5 * 3
+    #8384 * 6304 * 1.5 * 3
     mem_pool_size = 237837312
+    max_number_in_processing = 10
 
 [video_monitor:frame_drop]
     enable = true
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（901 行）</summary>

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
| `/bin/bodystate` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 213.7 KB | 213.7 KB | +0 B | system |
| `/bin/boot_control` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 182.0 KB | 182.0 KB | +0 B | system |
| `/bin/bootlogo` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 146.0 KB | 146.0 KB | +0 B | system |
| `/bin/brdver_ddrtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_hwrev.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_prodtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 386 B | 386 B | +0 B | system |
| `/bin/btconfig` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74.6 KB | 74.6 KB | +0 B | system |
| `/bin/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.7 KB | 6.7 KB | +0 B | system |
| `/bin/c2d_ut` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.7 KB | 33.7 KB | +0 B | system |
| `/bin/cam_log_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/camera` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 569.6 KB | 605.6 KB | +36.0 KB | system |
| `/bin/camera_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/camservice` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +13.4 KB | system |
| `/bin/capture-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 153 B | 153 B | +0 B | system |
| `/bin/capture.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 363 B | 363 B | +0 B | system |
| `/bin/charge_interrupt_test_module.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 943 B | 943 B | +0 B | system |
| `/bin/check_blackbox.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 580 B | 580 B | +0 B | system |
| `/bin/check_sdcard_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 515 B | 515 B | +0 B | system |
| `/bin/check_system_status.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 706 B | 706 B | +0 B | system |
| `/bin/collect_useful_log.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | system |
| `/bin/comp_build_version.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525 B | 525 B | +0 B | system |
| `/bin/configstore` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 277.6 KB | 281.6 KB | +4.0 KB | system |
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
| `/bin/dji_cht` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 95.7 KB | 95.7 KB | +0 B | system |
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
| `/bin/dji_iosconn` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.7 KB | 37.7 KB | +0 B | system |
| `/bin/dji_kmsg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_log_encrypt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.9 KB | 21.9 KB | +0 B | system |
| `/bin/dji_mb_ctrl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_mb_parser` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/dji_monitor` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_open_suspend_powerdown.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 583 B | 583 B | +0 B | system |
| `/bin/dji_pbt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.7 KB | 41.7 KB | +0 B | system |
| `/bin/dji_ppt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 207.0 KB | 207.0 KB | +0 B | system |
| `/bin/dji_quick_charge` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_rcam` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/dji_setup_uart.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 355 B | 355 B | +0 B | system |
| `/bin/dji_sn_ops.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 479 B | 479 B | +0 B | system |
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 376.6 KB | 376.6 KB | +0 B | system |
| `/bin/dji_system_complete.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/dji_tombstone.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/dji_verify` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.4 KB | 29.4 KB | +0 B | system |
| `/bin/dji_vtwo_sdk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/dji_wms` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 224.6 KB | 228.6 KB | +4.0 KB | system |
| `/bin/dji_wms-v1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 136.6 KB | 144.6 KB | +8.0 KB | system |
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
| `/bin/exposure_test_function.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 KB | 3.5 KB | +2.1 KB | system |
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
| `/bin/gpsd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.6 KB | 49.6 KB | +0 B | system |
| `/bin/gzip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/hard_restart.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 98 B | 98 B | +0 B | system |
| `/bin/hbl-collect-logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/hbl-configure-audio-sink.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/hbl-configure-audio-source.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/hciattach` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 63.0 KB | 63.0 KB | +0 B | system |
| `/bin/hex-writer` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.6 KB | 53.6 KB | +0 B | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 535.3 KB | 535.3 KB | +0 B | system |
| `/bin/hostapd_cli` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.7 KB | 49.7 KB | +0 B | system |
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
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 665.6 KB | 669.6 KB | +4.0 KB | system |
| `/bin/msg2dbus-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/mxt-app` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.5 KB | 82.5 KB | +0 B | system |
| `/bin/myftm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 87.2 KB | 87.2 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/odindb-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +16.0 KB | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 915.2 KB | 915.2 KB | +0 B | system |
| `/bin/periodic_sync.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59 B | 59 B | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 725.7 KB | 745.7 KB | +20.0 KB | system |
| `/bin/pl_spi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/play-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165 B | 165 B | +0 B | system |
| `/bin/play-hdmi.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165 B | 165 B | +0 B | system |
| `/bin/playcap-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 242 B | 242 B | +0 B | system |
| `/bin/pngtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/preview` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 281.9 KB | 281.9 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 125.6 KB | 125.6 KB | +0 B | system |
| `/bin/prodconfig-tool.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | system |
| `/bin/productiontest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/bin/program_nodes.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/proresenc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/qcmbr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.9 KB | 29.9 KB | +0 B | system |
| `/bin/r` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/rcam_agent` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.0 KB | 22.0 KB | +0 B | system |
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
| `/bin/start_blackbox_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/start_bodystate.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/bin/start_bootlogo.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 401 B | 401 B | +0 B | system |
| `/bin/start_camera_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_compositor.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_configstore.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | system |
| `/bin/start_dji_camera.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 247 B | 247 B | +0 B | system |
| `/bin/start_dji_mount_filesystem.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/start_dji_system.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/start_ftp_server.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 430 B | 430 B | +0 B | system |
| `/bin/start_gpsd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 356 B | 356 B | +0 B | system |
| `/bin/start_gui.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66 B | 66 B | +0 B | system |
| `/bin/start_high_consump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/bin/start_metadata_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | system |
| `/bin/start_msg2dbus.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 445 B | 445 B | +0 B | system |
| `/bin/start_preview_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | system |
| `/bin/start_storage_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | system |
| `/bin/start_sutestgui.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 75 B | 75 B | +0 B | system |
| `/bin/start_sysman.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_upgrade_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/bin/stm32flash` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42.0 KB | 42.0 KB | +0 B | system |
| `/bin/stop_high_consump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 912 B | 912 B | +0 B | system |
| `/bin/storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +4.5 KB | system |
| `/bin/support_audio_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | system |
| `/bin/sutest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 429.6 KB | 429.6 KB | +0 B | system |
| `/bin/switch_autotest.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 302 B | 302 B | +0 B | system |
| `/bin/sync_time.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | system |
| `/bin/sysman` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 369.6 KB | 377.6 KB | +8.0 KB | system |
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
| `/bin/test_eagle_fpga_mipi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
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
| `/bin/test_imgtec_venc_new` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 57.8 KB | 57.8 KB | +0 B | system |
| `/bin/test_internal_speaker.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 942 B | 942 B | +0 B | system |
| `/bin/test_iso_wb_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_lcd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.1 KB | 26.1 KB | +0 B | system |
| `/bin/test_lcd_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | system |
| `/bin/test_lcd_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/test_lens_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_lens_detect.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 345 B | 345 B | +0 B | system |
| `/bin/test_lens_if_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 617 B | 617 B | +0 B | system |
| `/bin/test_lens_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.7 KB | 3.0 KB | +291 B | system |
| `/bin/test_main_board_power.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | system |
| `/bin/test_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/test_menu_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_mic_function.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.3 KB | 5.6 KB | +246 B | system |
| `/bin/test_mic_headphone_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.3 KB | 3.4 KB | +125 B | system |
| `/bin/test_mic_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_mic_spk_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.5 KB | 3.6 KB | +125 B | system |
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
| `/bin/test_vdev` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.7 KB | 39.7 KB | +0 B | system |
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
| `/bin/upgrade_fw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.6 KB | 73.6 KB | +0 B | system |
| `/bin/upgrade_gl3227.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,001 B | 1,001 B | +0 B | system |
| `/bin/upgrade_spc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | system |
| `/bin/upgrade_suc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.2 KB | 5.2 KB | +0 B | system |
| `/bin/upgrade_suc_instant_return.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117 B | 117 B | +0 B | system |
| `/bin/upgrade_tp.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/bin/upgraded` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 345.6 KB | 345.6 KB | +0 B | system |
| `/bin/usbd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 157.9 KB | 161.9 KB | +4.0 KB | system |
| `/bin/valgrind` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/vdec_test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/victory-gui-static` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.8 MB | 20.8 MB | +48.0 KB | system |
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
| `/etc/NOTICE.html.gz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 87.9 KB | 87.9 KB | +0 B | system |
| `/etc/NOTICE.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 657.9 KB | 657.9 KB | +0 B | system |
| `/etc/VERSION` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6 B | 6 B | +0 B | system |
| `/etc/cht_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 211 B | 211 B | +0 B | system |
| `/etc/dbus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/dji.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117.0 KB | 117.0 KB | +0 B | system |
| `/etc/dji_camera.conf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.6 KB | 9.6 KB | +33 B | system |
| `/etc/dji_camera.tsf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 254 B | 254 B | +0 B | system |
| `/etc/dji_rcam.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 121 B | 121 B | +0 B | system |
| `/etc/event-log-tags` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/etc/firmware/bdwlan30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.9 KB | 7.9 KB | +0 B | system |
| `/etc/firmware/cpld/display_boe_convertor.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 160.8 KB | 160.8 KB | +0 B | system |
| `/etc/firmware/cpld/display_convertor.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 160.8 KB | 160.8 KB | +0 B | system |
| `/etc/firmware/cpld/display_jdi_convertor.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159.7 KB | 159.7 KB | +0 B | system |
| `/etc/firmware/gl.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 112.0 KB | 112.0 KB | +0 B | system |
| `/etc/firmware/nvm_tlv_3.2.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/etc/firmware/otp30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.5 KB | 24.5 KB | +0 B | system |
| `/etc/firmware/qca61x430.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 933.0 KB | 933.0 KB | +0 B | system |
| `/etc/firmware/qwlan30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 507.7 KB | 507.7 KB | +0 B | system |
| `/etc/firmware/rampatch_tlv_3.2.tlv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54.6 KB | 54.6 KB | +0 B | system |
| `/etc/firmware/rtnodes/BOOT.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 129.9 KB | 129.9 KB | +0 B | system |
| `/etc/firmware/rtnodes/FARM.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/etc/firmware/rtnodes/FPGA.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 MB | 5.3 MB | +0 B | system |
| `/etc/firmware/rtnodes/app.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 MB | 8.3 MB | +17.0 KB | system |
| `/etc/firmware/rtnodes/bifrost_body.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.8 KB | 21.0 KB | +159 B | system |
| `/etc/firmware/rtnodes/bifrost_body_v1.2.3.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 20.8 KB | — | -20.8 KB | system |
| `/etc/firmware/rtnodes/bifrost_body_v1.2.7.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 21.0 KB | +21.0 KB | system |
| `/etc/firmware/rtnodes/bifrost_grip.hex` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.2 KB | 22.1 KB | -106 B | system |
| `/etc/firmware/rtnodes/bifrost_grip_v1.2.2.hex` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 22.2 KB | — | -22.2 KB | system |
| `/etc/firmware/rtnodes/bifrost_grip_v1.2.6.hex` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 22.1 KB | +22.1 KB | system |
| `/etc/firmware/rtnodes/cfv-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 259.2 KB | 263.6 KB | +4.4 KB | system |
| `/etc/firmware/rtnodes/cfv-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +12.8 KB | system |
| `/etc/firmware/rtnodes/fpga_all.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.8 MB | 6.8 MB | +0 B | system |
| `/etc/firmware/rtnodes/fsbl.elf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 597.4 KB | 597.4 KB | +0 B | system |
| `/etc/firmware/rtnodes/power-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.8 KB | 53.8 KB | +0 B | system |
| `/etc/firmware/rtnodes/power-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +1.9 KB | system |
| `/etc/firmware/rtnodes/system_wrapper.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 MB | 5.3 MB | +0 B | system |
| `/etc/firmware/rtnodes/xsystem-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 239.4 KB | 244.0 KB | +4.6 KB | system |
| `/etc/firmware/rtnodes/xsystem-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.4 MB | 2.4 MB | +13.0 KB | system |
| `/etc/firmware/tpfw.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32.0 KB | 32.0 KB | +0 B | system |
| `/etc/firmware/utf30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323.4 KB | 323.4 KB | +0 B | system |
| `/etc/firmware/wlan/cfg.dat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | system |
| `/etc/firmware/wlan/qcom_cfg.ini` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.8 KB | 15.8 KB | +0 B | system |
| `/etc/ftp.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | system |
| `/etc/hostapd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 343 B | 343 B | +0 B | system |
| `/etc/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56 B | 56 B | +0 B | system |
| `/etc/imx161f_ec1704.sp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.1 KB | 26.4 KB | +313 B | system |
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
| `/lib/lib_camcomp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/lib/lib_eigen.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.6 KB | 85.6 KB | +0 B | system |
| `/lib/lib_hal_gdc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/lib_mdev.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/lib_mediactl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libadsb_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libamt_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | system |
| `/lib/libappscommon.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +16.0 KB | system |
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
| `/lib/libdcam_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +8 B | system |
| `/lib/libdcam_metadata.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 570.7 KB | 570.7 KB | +0 B | system |
| `/lib/libdiskconfig.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libdl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.3 KB | 9.3 KB | +0 B | system |
| `/lib/libduml_audio.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.6 KB | 69.6 KB | +0 B | system |
| `/lib/libduml_ffremux.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libduml_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 523.3 KB | 523.3 KB | +0 B | system |
| `/lib/libduml_hal.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 250.0 KB | 250.0 KB | +0 B | system |
| `/lib/libduml_hal_cam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 393.6 KB | 393.6 KB | +4 B | system |
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
| `/lib/libmod_x1dm2.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
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
| `/lib/modules/ili2120.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 132.0 KB | 129.7 KB | -2.3 KB | system |
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
| `/lib/modules/rcam_dji.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 MB | 8.3 MB | +2.6 KB | system |
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
| `/lib/qt/plugins/position/libgpsplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.5 KB | 61.5 KB | +0 B | system |
| `/lib/qt/plugins/position/libqtposition_positionpoll.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.4 KB | 41.4 KB | +0 B | system |
| `/lib/qt/plugins/sqldrivers/libqsqlite.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 893.0 KB | 893.0 KB | +0 B | system |
| `/lib/weston/eagle-backend.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 402.4 KB | 402.5 KB | +8 B | system |
| `/lib/weston/eagle-shell.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.5 KB | 33.5 KB | +0 B | system |
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.6 MB | 15.6 MB | -487 B | system |
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
