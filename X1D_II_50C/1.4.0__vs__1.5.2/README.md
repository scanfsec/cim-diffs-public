# X1D II 50C: 1.4.0 ➜ 1.5.2

> 生成时间: 2026-10-07T06:04:09 · CIM 日期: 2020-10-21 ➜ 2022-08-26 · 条目: 4 ➜ 4 · 源: `X1D_II_50C_v1_4_0.cim` ➜ `X1D_II_50C_v1_5_2.cim`

## Summary

文件树 +0/-0/~426；CIM 条目 +1/-1/~2；OTA 镜像 ~5 变更 / 0 未变；符号 +96/-40 funcs, +589/-560 objs；新增字符串 820 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `hbmanual_pack.tar` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 72.3 MB | +72.3 MB |
| `hbmanual.img` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 64.0 MB | — | -64.0 MB |
| `hbl-post-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.5 KB | 1.3 KB | -203 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 150.7 MB | 150.7 MB | +86.0 KB |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 1 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 1 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 2 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 1

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 MB | 7.3 MB | +0 B |
| `recovery.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.2 MB | 22.2 MB | +448 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 234.0 MB | 234.5 MB | +476.0 KB |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.7 MB | 22.7 MB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 5 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `lib` | 0 | 0 | 184 | 23 | 0 |
| `bin` | 0 | 0 | 137 | 278 | 0 |
| `firmware` | 0 | 0 | 37 | 0 | 0 |
| `xbin` | 0 | 0 | 37 | 1 | 0 |
| `ta` | 0 | 0 | 15 | 0 | 0 |
| `etc` | 0 | 0 | 14 | 146 | 0 |
| `(root)` | 0 | 0 | 2 | 0 | 0 |
| `data` | 0 | 0 | 0 | 1 | 0 |
| `usr` | 0 | 0 | 0 | 29 | 0 |

明细 904 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+96 / −40** functions, **+589 / −560** objects（50 个变更 ELF, 另有 311 个未列出）。

### `/bin/storage`

+15 / −15 functions · +7 / −8 objects

**New functions (15)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNKSt3__120__vector_base_commonILb1EE20__throw_length_errorEv.isra.99` | 0x13c44 | 96 |
| `_ZN5Cache11onFlushFileERK14QSharedPointerIN2IO4WorkEE` | 0x50fdc | 360 |
| `_ZN9QtPrivate11QSlotObjectIM5CacheFvRK14QSharedPointerIN2IO4WorkEEENS_4ListIJS7_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x56e4c | 156 |
| `_ZN9QtPrivate8RefCount3refEv.part.58` | 0x80788 | 28 |
| `_ZN9QtPrivate8RefCount5derefEv.part.59` | 0x807a4 | 32 |
| `_ZN7QStringD2Ev.part.60` | 0x807c4 | 24 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.95` | 0x807dc | 132 |
| `_ZN5QListI5QPairI7QStringiEE7deallocEPN9QListData4DataE.isra.123` | 0x80860 | 152 |
| `_ZN5QListI10QByteArrayE7deallocEPN9QListData4DataE.isra.132` | 0x808f8 | 132 |
| `_ZN5QListI5QPairI7QString10QByteArrayEE7deallocEPN9QListData4DataE.isra.134` | 0x8097c | 224 |
| `_ZN8QMapNodeIj5QPairI7QString10QByteArrayEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.161` | 0x80e68 | 1632 |
| `_ZN5QListI14QSharedPointerI16MetadataTopImageEE7deallocEPN9QListData4DataE.isra.106` | 0x81d18 | 88 |
| `_ZN5QListIN8Metadata15FileInformationEE7deallocEPN9QListData4DataE.isra.114` | 0x81d70 | 112 |
| `_ZN8QMapNodeIj5QPairI7QString14QSharedPointerI11ImageMemoryEEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.162` | 0x82c80 | 1776 |
| `_ZL13parseJpegExifR5QFileRib.constprop.215` | 0x88084 | 744 |

**Removed functions (15)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZNKSt3__120__vector_base_commonILb1EE20__throw_length_errorEv.isra.95` | 0x13be4 | 96 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Cache21onPopSnapshotFinishedEP18PendingCallWatcherEUlRK14QSharedPointerIN2IO4WorkEEE_Li1ENS_4ListIJS9_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x50e0c | 392 |
| `_ZN9QtPrivate18QFunctorSlotObjectIZN5Cache14setupCacheItemERK14QSharedPointerI9CacheItemEN9HblmTypes21E_StorageUpdateReasonEEUlRKS2_IN2IO4WorkEEE0_Li1ENS_4ListIJSD_EEEvE4implEiPNS_15QSlotObjectBaseEP7QObjectPPvPb` | 0x51114 | 396 |
| `_ZN9QtPrivate8RefCount3refEv.part.57` | 0x807a0 | 28 |
| `_ZN9QtPrivate8RefCount5derefEv.part.58` | 0x807bc | 32 |
| `_ZN7QStringD2Ev.part.59` | 0x807dc | 24 |
| `_ZN5QListI7QStringE7deallocEPN9QListData4DataE.isra.91` | 0x807f4 | 132 |
| `_ZN5QListI5QPairI7QStringiEE7deallocEPN9QListData4DataE.isra.119` | 0x80878 | 152 |
| `_ZN5QListI10QByteArrayE7deallocEPN9QListData4DataE.isra.128` | 0x80910 | 132 |
| `_ZN5QListI5QPairI7QString10QByteArrayEE7deallocEPN9QListData4DataE.isra.130` | 0x80994 | 224 |
| `_ZN8QMapNodeIj5QPairI7QString10QByteArrayEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.155` | 0x80e80 | 1632 |
| `_ZN5QListI14QSharedPointerI16MetadataTopImageEE7deallocEPN9QListData4DataE.isra.102` | 0x81d30 | 88 |
| `_ZN5QListIN8Metadata15FileInformationEE7deallocEPN9QListData4DataE.isra.110` | 0x81d88 | 112 |
| `_ZN8QMapNodeIj5QPairI7QString14QSharedPointerI11ImageMemoryEEE16doDestroySubTreeENSt3__117integral_constantIbLb1EEE.isra.156` | 0x82ca0 | 1704 |
| `_ZL13parseJpegExifR5QFileRib.constprop.205` | 0x87ef4 | 744 |

**New objects (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN5Cache11onFlushFileERK14QSharedPointerIN2IO4WorkEEE12__FUNCTION__` | 0xfcef0 | 12 |
| `._538` | 0xfdc68 | 2 |
| `._537` | 0xfdcd8 | 2 |
| `._434` | 0x101250 | 8 |
| `._435` | 0x101258 | 14 |
| `._436` | 0x101268 | 10 |
| `._441` | 0x101d50 | 2 |

**Removed objects (8)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZZN5Cache21onPopSnapshotFinishedEP18PendingCallWatcherENKUlRK14QSharedPointerIN2IO4WorkEEE_clES7_E12__FUNCTION__` | 0xfcd58 | 11 |
| `_ZZZN5Cache14setupCacheItemERK14QSharedPointerI9CacheItemEN9HblmTypes21E_StorageUpdateReasonEENKUlRKS0_IN2IO4WorkEEE0_clESB_E12__FUNCTION__` | 0xfcd78 | 11 |
| `._535` | 0xfdaf0 | 2 |
| `._534` | 0xfdb60 | 2 |
| `._427` | 0x1010a0 | 4 |
| `._428` | 0x1010a8 | 4 |
| `._429` | 0x101100 | 4 |
| `._438` | 0x101bd8 | 2 |

### `/etc/firmware/rtnodes/xsystem-control.elf`

+28 / −2 functions · +142 / −134 objects

**New functions (28)**

| Symbol | Addr | Size |
|---|---|---|
| `is_probing` | 0x8002b7d | 12 |
| `set_probing` | 0x8002b89 | 12 |
| `vProbeTimerCallback` | 0x8002b95 | 28 |
| `CACHE_GetSelectableCameras` | 0x8004ef9 | 12 |
| `CACHE_SetIsAfAllowed` | 0x80052c9 | 32 |
| `CACHE_GetIsAfAllowed` | 0x80052e9 | 12 |
| `CACHE_SetLensInputCapabilities` | 0x80052f5 | 32 |
| `CACHE_GetLensInputCapabilities` | 0x8005315 | 12 |
| `CACHE_GetLensProductName` | 0x8005321 | 8 |
| `CACHE_SetLensProductName` | 0x8005329 | 68 |
| `ExtCapabilityReplyCallback` | 0x8006255 | 32 |
| `EXTCAPABILITIES_numCapabilities_blocking` | 0x8006275 | 192 |
| `EXTCAPABILITIES_getCapabilities_blocking` | 0x8006335 | 224 |
| `EXTCAPABILITIES_matchCapabilities_blocking` | 0x8006415 | 108 |
| `EXTCAPABILITIES_enableCapabilities_blocking` | 0x8006481 | 204 |
| `I2CADD_SuSignal_received` | 0x80075f5 | 144 |
| `updateUserInputCapabilities` | 0x80087a9 | 56 |
| `getProductName` | 0x8008919 | 164 |
| `getExtendedCapabilities` | 0x8008cb1 | 516 |
| `LENS_ExtStatusHandler` | 0x8009f59 | 128 |
| `get_source` | 0x800c50d | 30 |
| `MSGHANDLER_lens_changed_is_af_allowed` | 0x800e1f9 | 44 |
| `MSGHANDLER_lens_changed_lens_product_name` | 0x800e261 | 50 |
| `MSGHANDLER_lens_changed_user_input_capabilities` | 0x800e3b9 | 42 |
| `MSGHANDLER_SignalControlRing` | 0x800f041 | 96 |
| `strncmp` | 0x8024c0d | 50 |
| `strncpy` | 0x8024c3f | 36 |
| `strnlen` | 0x8024c63 | 24 |

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `CACHE_GetSelecableCameras` | 0x8004e1d | 12 |
| `isZoom` | 0x8007f89 | 36 |

**New objects (142)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16267` | 0x80262f4 | 10 |
| `__func__.16128` | 0x8026300 | 15 |
| `__func__.16140` | 0x8026310 | 33 |
| `__func__.16349` | 0x8026334 | 15 |
| `__func__.16291` | 0x8026344 | 19 |
| `__func__.16279` | 0x80273a8 | 11 |
| `__func__.16222` | 0x80273b4 | 13 |
| `__func__.16179` | 0x80273c4 | 28 |
| `__func__.16370` | 0x80273e0 | 22 |
| `__func__.16234` | 0x80273f8 | 23 |
| `__func__.16383` | 0x8027410 | 42 |
| `__func__.16255` | 0x802743c | 16 |
| `__func__.14149` | 0x8027d90 | 16 |
| `__func__.15832` | 0x8028664 | 25 |
| `__func__.15766` | 0x8028680 | 11 |
| `__func__.15803` | 0x802868c | 22 |
| `__func__.15762` | 0x80286a4 | 17 |
| `__func__.15869` | 0x80286b8 | 26 |
| `__func__.15820` | 0x80286d4 | 13 |
| `__func__.15776` | 0x802880c | 20 |
| `__func__.15786` | 0x8028988 | 23 |
| `__func__.15795` | 0x80289a0 | 21 |
| `__func__.15846` | 0x80289b8 | 22 |
| `__func__.16589` | 0x80289e0 | 19 |
| `__func__.16176` | 0x80289f4 | 16 |
| `__func__.15975` | 0x8028a04 | 24 |
| `__func__.16465` | 0x8028a1c | 15 |
| `__func__.16084` | 0x8028a2c | 19 |
| `__func__.16220` | 0x8028a40 | 34 |
| `__func__.16214` | 0x8028a64 | 32 |
| `__func__.16238` | 0x8028a84 | 20 |
| `__func__.16400` | 0x8028a98 | 17 |
| `__func__.16556` | 0x8028aac | 26 |
| `__func__.16278` | 0x8028ac8 | 21 |
| `__func__.16145` | 0x8028ae0 | 16 |
| `__func__.16018` | 0x8028af0 | 28 |
| `__FUNCTION__.15944` | 0x8028b0c | 25 |
| `__FUNCTION__.15938` | 0x8028b28 | 20 |
| `__func__.16468` | 0x8028b3c | 18 |
| `__FUNCTION__.16022` | 0x8028b50 | 35 |
| `mExtCapabilitiesSupported` | 0x8028b74 | 4 |
| `__func__.16079` | 0x8028b78 | 22 |
| `__FUNCTION__.16026` | 0x8028b90 | 31 |
| `__func__.16506` | 0x8028bb0 | 10 |
| `__func__.16226` | 0x8028bbc | 25 |
| `__func__.16245` | 0x8028bd8 | 20 |
| `__func__.16542` | 0x8028bec | 14 |
| `__func__.16548` | 0x8028bfc | 22 |
| `__func__.16565` | 0x8028c14 | 21 |
| `__func__.16416` | 0x8028c2c | 29 |

<details><summary>… 另 92 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.17391` | 0x80296f0 | 11 |
| `__FUNCTION__.15398` | 0x8029aa8 | 27 |
| `__FUNCTION__.15405` | 0x8029ac4 | 10 |
| `__func__.14698` | 0x802d2fc | 11 |
| `__func__.14724` | 0x802d308 | 16 |
| `__func__.14718` | 0x802d664 | 13 |
| `__func__.13809` | 0x802e89c | 31 |
| `__func__.13831` | 0x802e9d8 | 26 |
| `__FUNCTION__.12995` | 0x802ea1c | 29 |
| `__FUNCTION__.13007` | 0x802edbc | 22 |
| `__FUNCTION__.13015` | 0x802edd4 | 22 |
| `__FUNCTION__.12972` | 0x802edec | 27 |
| `__func__.16086` | 0x802ee08 | 21 |
| `__func__.16043` | 0x802ee20 | 21 |
| `__func__.13812` | 0x802f690 | 28 |
| `__func__.13822` | 0x802f6ac | 18 |
| `__func__.13818` | 0x802f6c0 | 29 |
| `__func__.13826` | 0x802f6e0 | 20 |
| `__func__.13788` | 0x80304b4 | 19 |
| `__func__.13679` | 0x80304c8 | 27 |
| `__func__.13695` | 0x80304e4 | 13 |
| `__FUNCTION__.13423` | 0x80304f4 | 44 |
| `__FUNCTION__.13409` | 0x8031324 | 40 |
| `__func__.13757` | 0x80313c8 | 13 |
| `__func__.13766` | 0x80313d8 | 19 |
| `__FUNCTION__.13209` | 0x8031540 | 31 |
| `__FUNCTION__.13184` | 0x803172c | 16 |
| `__FUNCTION__.13239` | 0x803173c | 27 |
| `__FUNCTION__.13225` | 0x8031758 | 24 |
| `__func__.14146` | 0x80321d0 | 11 |
| `__func__.14150` | 0x80321dc | 13 |
| `__func__.14168` | 0x8032b94 | 18 |
| `__func__.14164` | 0x8032ba8 | 12 |
| `__func__.13882` | 0x8033aa4 | 19 |
| `__func__.13864` | 0x8033ab8 | 18 |
| `__func__.13916` | 0x8033acc | 10 |
| `__func__.13923` | 0x8033ad8 | 9 |
| `__func__.13956` | 0x8033ff8 | 13 |
| `__func__.13452` | 0x8035098 | 23 |
| `__func__.15384` | 0x80350b0 | 27 |
| `__FUNCTION__.15195` | 0x80357bc | 18 |
| `__FUNCTION__.13160` | 0x80357dc | 21 |
| `__FUNCTION__.15211` | 0x80359d4 | 20 |
| `__FUNCTION__.15244` | 0x8035e50 | 23 |
| `__FUNCTION__.15251` | 0x8035e68 | 13 |
| `__FUNCTION__.15375` | 0x8035f58 | 22 |
| `__FUNCTION__.15381` | 0x8035f70 | 28 |
| `__FUNCTION__.15362` | 0x8036274 | 30 |
| `__func__.14584` | 0x8036294 | 10 |
| `__func__.14669` | 0x8036554 | 19 |
| `batteryStatus.16173` | 0x2000002e | 1 |
| `battery_probe_counter.16282` | 0x20000054 | 4 |
| `HW_version.14199` | 0x200002a8 | 1 |
| `checksum.14460` | 0x20000326 | 2 |
| `flashpower.14462` | 0x20000368 | 1 |
| `lastRxData.14322` | 0x20000398 | 4 |
| `enterState.15330` | 0x200003e6 | 1 |
| `mProbing` | 0x2000071c | 1 |
| `mProbeTimerHandle` | 0x2000072c | 4 |
| `last_hvdcp.16139` | 0x20000744 | 1 |
| `mIsAfAllowed` | 0x2000077a | 1 |
| `mLensInputCapabilities` | 0x20000780 | 4 |
| `mLensProductName` | 0x200007a4 | 20 |
| `msg_index.12630` | 0x20000838 | 4 |
| `ticks.13876` | 0x20000840 | 4 |
| `mHasControlRing` | 0x20000ca2 | 1 |
| `is_fake.16579` | 0x20000cbc | 1 |
| `saved_lens.16578` | 0x20000cbe | 1 |
| `mHasAfDisableSwitch` | 0x20000cc4 | 1 |
| `lastGpioValue.15397` | 0x20000cc8 | 4 |
| `sig.12609` | 0x200026f8 | 270 |
| `mutex.14207` | 0x20002a04 | 4 |
| `str.14106` | 0x20002a08 | 10 |
| `writebuffer.12595` | 0x20003324 | 5 |
| `initialized.13955` | 0x2000333c | 1 |
| `generateRxAck.14318` | 0x20003346 | 1 |
| `flashstatus.14461` | 0x20003349 | 1 |
| `generateTxAck.14316` | 0x20003355 | 1 |
| `TxAckTimeoutCnt.14321` | 0x20003358 | 4 |
| `generateTxAckDelay.14317` | 0x2000335e | 1 |
| `generateRxAckDelay.14319` | 0x2000335f | 1 |
| `longAckDelay.14320` | 0x20003365 | 1 |
| `checksum.14315` | 0x20003374 | 4 |
| `lastMode.14463` | 0x2000337a | 1 |
| `datacnt.14314` | 0x2000337c | 1 |
| `rxDmaInitialized.13356` | 0x200033a8 | 1 |
| `txPoolInitialized.13340` | 0x200033a9 | 1 |
| `timerInitialized.13364` | 0x20004455 | 1 |
| `wakeUpSpecialEn.15331` | 0x20004475 | 1 |
| `earlyStartInProgress.15208` | 0x200044b1 | 1 |
| `switch_req_origin.14582` | 0x200044d0 | 1 |
| `loopTestTaskHandle.14677` | 0x200044f0 | 4 |

</details>

**Removed objects (134)**

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
| `__func__.15236` | 0x8027c68 | 16 |
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

<details><summary>… 另 84 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.15302` | 0x8028a68 | 27 |
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
| `__func__.15990` | 0x802ddc0 | 21 |
| `__func__.15947` | 0x802df2c | 21 |
| `__func__.13754` | 0x802e610 | 18 |
| `__func__.13758` | 0x802e624 | 20 |
| `__func__.13611` | 0x802e650 | 27 |
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
| `__func__.14086` | 0x8031104 | 13 |
| `__func__.14100` | 0x8031114 | 12 |
| `__func__.14104` | 0x8031120 | 18 |
| `__func__.14082` | 0x8031acc | 11 |
| `__func__.13802` | 0x8032990 | 19 |
| `__func__.13876` | 0x80329a4 | 13 |
| `__func__.13784` | 0x8032ea8 | 18 |
| `__func__.13843` | 0x8032edc | 9 |
| `__func__.13384` | 0x8033e9c | 23 |
| `__func__.15288` | 0x8034218 | 27 |
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
| `ticks.13812` | 0x20000824 | 4 |
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

</details>

### `/etc/firmware/rtnodes/cfv-control.elf`

+25 / −3 functions · +156 / −149 objects

**New functions (25)**

| Symbol | Addr | Size |
|---|---|---|
| `is_probing` | 0x8002e59 | 12 |
| `set_probing` | 0x8002e65 | 12 |
| `vProbeTimerCallback` | 0x8002e75 | 28 |
| `CACHE_GetSelectableCameras` | 0x8005edd | 12 |
| `CACHE_SetIsAfAllowed` | 0x80062a5 | 32 |
| `CACHE_GetIsAfAllowed` | 0x80062c5 | 12 |
| `CACHE_SetLensInputCapabilities` | 0x80062d1 | 32 |
| `CACHE_GetLensInputCapabilities` | 0x80062f1 | 12 |
| `CACHE_GetLensProductName` | 0x80062fd | 8 |
| `CACHE_SetLensProductName` | 0x8006305 | 68 |
| `EXTCAPABILITIES_numCapabilities_blocking` | 0x8007275 | 192 |
| `EXTCAPABILITIES_getCapabilities_blocking` | 0x8007335 | 224 |
| `EXTCAPABILITIES_matchCapabilities_blocking` | 0x8007415 | 108 |
| `updateUserInputCapabilities` | 0x8009f19 | 56 |
| `getProductName` | 0x800a089 | 164 |
| `getExtendedCapabilities` | 0x800a421 | 516 |
| `LENS_ExtStatusHandler` | 0x800b6b9 | 128 |
| `MSGHANDLER_lens_changed_is_af_allowed` | 0x800fc09 | 44 |
| `MSGHANDLER_lens_changed_lens_product_name` | 0x800fc71 | 50 |
| `MSGHANDLER_lens_changed_user_input_capabilities` | 0x800fdc9 | 42 |
| `MSGHANDLER_SignalWheel` | 0x8010b8d | 96 |
| `MSGHANDLER_SignalControlRing` | 0x8010bed | 96 |
| `strncmp` | 0x8028b7d | 50 |
| `strncpy` | 0x8028baf | 36 |
| `strnlen` | 0x8028bd3 | 24 |

**Removed functions (3)**

| Symbol | Addr | Size |
|---|---|---|
| `CACHE_GetSelecableCameras` | 0x8005e0d | 12 |
| `isZoom` | 0x80098c5 | 36 |
| `MSGHANDLER_Signalwheel` | 0x8010395 | 96 |

**New objects (156)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16261` | 0x802a458 | 16 |
| `__func__.16192` | 0x802a468 | 28 |
| `__func__.16273` | 0x802a484 | 10 |
| `__func__.16141` | 0x802a490 | 15 |
| `__func__.16228` | 0x802a4a0 | 13 |
| `__func__.16297` | 0x802a510 | 19 |
| `__func__.16355` | 0x802b4cc | 15 |
| `__func__.16240` | 0x802b4dc | 23 |
| `__func__.16285` | 0x802b5a8 | 11 |
| `__func__.14864` | 0x802b5cc | 32 |
| `__func__.14870` | 0x802b790 | 29 |
| `__func__.14843` | 0x802b7b0 | 17 |
| `__func__.14839` | 0x802b7c4 | 41 |
| `__func__.14850` | 0x802b7f0 | 22 |
| `__func__.14846` | 0x802b808 | 21 |
| `__func__.14854` | 0x802b820 | 21 |
| `__func__.14629` | 0x802b838 | 21 |
| `__func__.14625` | 0x802b9c0 | 41 |
| `__func__.14637` | 0x802b9ec | 21 |
| `__func__.14149` | 0x802c5a4 | 16 |
| `__func__.15766` | 0x802cf74 | 17 |
| `__func__.15770` | 0x802cfa0 | 11 |
| `__func__.15879` | 0x802cfac | 26 |
| `__func__.15824` | 0x802cfc8 | 13 |
| `__func__.15780` | 0x802cfd8 | 20 |
| `__func__.15790` | 0x802d27c | 23 |
| `__func__.15850` | 0x802d2b0 | 22 |
| `__func__.15799` | 0x802d2c8 | 21 |
| `__func__.16460` | 0x802d2f0 | 18 |
| `__func__.16457` | 0x802d304 | 15 |
| `__func__.16071` | 0x802d314 | 22 |
| `__func__.15967` | 0x802d32c | 24 |
| `__FUNCTION__.15930` | 0x802d344 | 20 |
| `__func__.16498` | 0x802d358 | 10 |
| `__FUNCTION__.15936` | 0x802d364 | 25 |
| `__FUNCTION__.16014` | 0x802d380 | 35 |
| `__func__.16212` | 0x802d3a4 | 34 |
| `__func__.16206` | 0x802d3c8 | 32 |
| `__func__.16218` | 0x802d3e8 | 25 |
| `__func__.16237` | 0x802d404 | 20 |
| `__func__.16534` | 0x802d418 | 14 |
| `__func__.16230` | 0x802d428 | 20 |
| `__func__.16168` | 0x802d43c | 16 |
| `__func__.16557` | 0x802d44c | 21 |
| `__func__.16408` | 0x802d464 | 29 |
| `__func__.16010` | 0x802df1c | 28 |
| `__FUNCTION__.16018` | 0x802df38 | 31 |
| `__func__.16076` | 0x802df58 | 19 |
| `mExtCapabilitiesSupported` | 0x802df6c | 4 |
| `__func__.16392` | 0x802df70 | 17 |

<details><summary>… 另 106 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16548` | 0x802df84 | 26 |
| `__func__.16540` | 0x802dfa0 | 22 |
| `__func__.16581` | 0x802dfb8 | 19 |
| `__func__.16137` | 0x802dfcc | 16 |
| `__FUNCTION__.17215` | 0x802dfe0 | 11 |
| `__FUNCTION__.15433` | 0x802e380 | 10 |
| `__FUNCTION__.15412` | 0x802e46c | 27 |
| `__func__.15026` | 0x802e4a4 | 16 |
| `__func__.15000` | 0x8031cdc | 11 |
| `__func__.15020` | 0x8032094 | 13 |
| `__func__.13858` | 0x8033128 | 31 |
| `__func__.13885` | 0x80332ec | 22 |
| `__func__.13875` | 0x8033304 | 17 |
| `__FUNCTION__.12995` | 0x803344c | 29 |
| `__FUNCTION__.13007` | 0x80337ec | 22 |
| `__FUNCTION__.13015` | 0x8033804 | 22 |
| `__FUNCTION__.12972` | 0x803381c | 27 |
| `__func__.15942` | 0x8033838 | 22 |
| `__func__.15970` | 0x8033850 | 21 |
| `__func__.15889` | 0x8033fd0 | 17 |
| `__func__.15836` | 0x8034224 | 24 |
| `__func__.15875` | 0x803423c | 21 |
| `__func__.15903` | 0x8034254 | 21 |
| `__func__.15027` | 0x803459c | 25 |
| `__FUNCTION__.15005` | 0x80345b8 | 13 |
| `__func__.15031` | 0x80345c8 | 25 |
| `__func__.11981` | 0x8034a54 | 19 |
| `__func__.11989` | 0x8034a68 | 11 |
| `__func__.12000` | 0x8034a74 | 12 |
| `__func__.12005` | 0x8034c08 | 19 |
| `__func__.11995` | 0x8034c1c | 12 |
| `__func__.13699` | 0x8034d84 | 13 |
| `__func__.13816` | 0x8034d94 | 28 |
| `__func__.13822` | 0x8034db0 | 29 |
| `__func__.13830` | 0x8034de8 | 20 |
| `__func__.13826` | 0x8034dfc | 18 |
| `__func__.13792` | 0x8035bd0 | 19 |
| `__func__.13683` | 0x8035be4 | 27 |
| `__FUNCTION__.13423` | 0x8035c00 | 44 |
| `__FUNCTION__.13409` | 0x8036a30 | 40 |
| `__func__.13761` | 0x8036ae4 | 13 |
| `__func__.13770` | 0x8036af4 | 19 |
| `__FUNCTION__.13243` | 0x8036c5c | 27 |
| `__FUNCTION__.13213` | 0x8036c78 | 31 |
| `__FUNCTION__.13159` | 0x8036c98 | 34 |
| `__FUNCTION__.13229` | 0x8036cbc | 24 |
| `__FUNCTION__.13188` | 0x8036ea0 | 16 |
| `__func__.14198` | 0x80376f4 | 15 |
| `__func__.14203` | 0x8037704 | 14 |
| `__func__.14211` | 0x8037714 | 18 |
| `__func__.14207` | 0x8037728 | 12 |
| `__func__.14193` | 0x8038210 | 13 |
| `__func__.14189` | 0x8038220 | 11 |
| `__func__.7549` | 0x80386f0 | 19 |
| `__func__.13920` | 0x8039214 | 10 |
| `__func__.13868` | 0x8039220 | 18 |
| `__func__.13927` | 0x8039234 | 9 |
| `__func__.13886` | 0x8039240 | 19 |
| `__func__.13960` | 0x8039768 | 13 |
| `__func__.13456` | 0x8039c40 | 23 |
| `__func__.15388` | 0x8039f14 | 27 |
| `__FUNCTION__.15235` | 0x803a34c | 18 |
| `__FUNCTION__.13164` | 0x803a36c | 21 |
| `__FUNCTION__.15306` | 0x803a564 | 20 |
| `__FUNCTION__.15339` | 0x803a9a0 | 23 |
| `__FUNCTION__.15346` | 0x803a9b8 | 13 |
| `__FUNCTION__.15416` | 0x803aaa8 | 30 |
| `__FUNCTION__.15429` | 0x803aac8 | 22 |
| `__FUNCTION__.15435` | 0x803aae0 | 28 |
| `__func__.14598` | 0x803ae84 | 10 |
| `__func__.14683` | 0x803b144 | 19 |
| `batteryStatus.16186` | 0x2000002e | 1 |
| `battery_probe_counter.16288` | 0x20000054 | 4 |
| `oldValue.15424` | 0x2000006c | 4 |
| `oldValue.15419` | 0x20000070 | 4 |
| `HW_version.14243` | 0x200000d4 | 1 |
| `enterState.15334` | 0x2000030a | 1 |
| `mProbing` | 0x20000644 | 1 |
| `mProbeTimerHandle` | 0x20000660 | 4 |
| `last_hvdcp.16152` | 0x2000066c | 1 |
| `inputBefore.14828` | 0x20000670 | 4 |
| `triggerBefore.14827` | 0x20000674 | 1 |
| `eldBtnSavedConf.14826` | 0x20000678 | 16 |
| `mIsAfAllowed` | 0x200006ba | 1 |
| `mLensInputCapabilities` | 0x200006c0 | 4 |
| `mLensProductName` | 0x200006e4 | 20 |
| `msg_index.12630` | 0x20000778 | 4 |
| `ticks.13631` | 0x20000780 | 4 |
| `mHasControlRing` | 0x20000b4f | 1 |
| `is_fake.16571` | 0x20000bf8 | 1 |
| `saved_lens.16570` | 0x20000bf9 | 1 |
| `mHasAfDisableSwitch` | 0x20000c00 | 1 |
| `lastGpioValue.15411` | 0x20000c14 | 4 |
| `last_signal.18269` | 0x20000c4e | 1 |
| `sig.12609` | 0x20002654 | 270 |
| `mutex.14251` | 0x20002958 | 4 |
| `str.14149` | 0x2000295c | 10 |
| `writebuffer.12595` | 0x2000327c | 5 |
| `initialized.13959` | 0x2000328d | 1 |
| `rxDmaInitialized.13360` | 0x200032bc | 1 |
| `txPoolInitialized.13344` | 0x200032bd | 1 |
| `timerInitialized.13368` | 0x20004369 | 1 |
| `wakeUpSpecialEn.15335` | 0x20004378 | 1 |
| `earlyStartInProgress.15303` | 0x200043ad | 1 |
| `loopTestTaskHandle.14691` | 0x200043cc | 4 |
| `switch_req_origin.14596` | 0x200043eb | 1 |

</details>

**Removed objects (149)**

| Symbol | Addr | Size |
|---|---|---|
| `__func__.16120` | 0x8029b28 | 13 |
| `__func__.16177` | 0x8029b38 | 11 |
| `__func__.16084` | 0x8029b44 | 28 |
| `__func__.16132` | 0x8029b60 | 23 |
| `__func__.16281` | 0x8029b78 | 42 |
| `__func__.16045` | 0x8029ba4 | 33 |
| `__func__.16165` | 0x8029c0c | 10 |
| `__func__.16247` | 0x802ab7c | 15 |
| `__func__.16033` | 0x802ab8c | 15 |
| `__func__.16189` | 0x802ab9c | 19 |
| `__func__.14755` | 0x802ac7c | 32 |
| `__func__.14761` | 0x802ae30 | 29 |
| `__func__.14730` | 0x802ae50 | 41 |
| `__func__.14745` | 0x802ae7c | 21 |
| `__func__.14734` | 0x802ae94 | 17 |
| `__func__.14737` | 0x802aea8 | 21 |
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
| `__func__.15599` | 0x802d248 | 22 |
| `__func__.15616` | 0x802d260 | 21 |
| `__func__.15228` | 0x802d278 | 16 |
| `__func__.15451` | 0x802d288 | 17 |
| `__func__.15173` | 0x802d29c | 19 |
| `__func__.15467` | 0x802d2b0 | 29 |
| `__func__.15557` | 0x802d2d0 | 10 |
| `__func__.15321` | 0x802d2dc | 20 |

<details><summary>… 另 99 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15309` | 0x802d2f0 | 25 |
| `__func__.15607` | 0x802d30c | 26 |
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
| `__func__.15874` | 0x8032b4c | 21 |
| `__func__.15779` | 0x80332bc | 21 |
| `__func__.15740` | 0x8033514 | 24 |
| `__func__.15793` | 0x803352c | 17 |
| `__func__.15846` | 0x8033540 | 22 |
| `__FUNCTION__.14909` | 0x8033878 | 13 |
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
| `__func__.13615` | 0x8034e88 | 27 |
| `__func__.13631` | 0x8034ea4 | 13 |
| `__FUNCTION__.13345` | 0x8035ca8 | 40 |
| `__FUNCTION__.13359` | 0x8035cd0 | 44 |
| `__func__.13697` | 0x8035d78 | 13 |
| `__func__.13706` | 0x8035d88 | 19 |
| `__FUNCTION__.13095` | 0x8035ee0 | 34 |
| `__FUNCTION__.13149` | 0x8035f04 | 31 |
| `__FUNCTION__.13165` | 0x8035f24 | 24 |
| `__FUNCTION__.13115` | 0x80360e0 | 28 |
| `__FUNCTION__.13124` | 0x8036118 | 16 |
| `__func__.14143` | 0x803695c | 12 |
| `__func__.14139` | 0x8036968 | 14 |
| `__func__.14147` | 0x8036978 | 18 |
| `__func__.14125` | 0x803698c | 11 |
| `__func__.14129` | 0x8037464 | 13 |
| `__func__.14134` | 0x8037474 | 15 |
| `__func__.7526` | 0x80379c4 | 19 |
| `__func__.13806` | 0x8038438 | 19 |
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
| `msg_index.12493` | 0x20000748 | 4 |
| `ticks.13567` | 0x20000750 | 4 |
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

</details>

### `/lib/libappscommon.so`

+20 / −6 functions · +3 / −0 objects

**New functions (20)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12CambodyProxy19connectControl_ringEv` | 0x6913c | 164 |
| `_ZN12CambodyProxy22disconnectControl_ringEv` | 0x691e0 | 164 |
| `_ZNK9LensProxy13is_af_allowedEv` | 0x855d0 | 40 |
| `_ZNK9LensProxy17lens_product_nameEv` | 0x85620 | 44 |
| `_ZNK9LensProxy23user_input_capabilitiesEv` | 0x85748 | 40 |
| `_ZNK11ConfigProxy32user_wheel_control_ring_functionEv` | 0x96160 | 44 |
| `_ZN11ConfigProxy35setUser_wheel_control_ring_functionEN9HblmTypes19E_UserWheelFunctionE` | 0xa0538 | 228 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_LensUserInputELb1EE8DestructEPv` | 0x131970 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_LensUserInputELb1EE9ConstructEPvPKv` | 0x131974 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE8DestructEPv` | 0x131988 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE9ConstructEPvPKv` | 0x13198c | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE8DestructEPv` | 0x131be0 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE9ConstructEPvPKv` | 0x131be4 | 20 |
| `_ZN16SnapshotMetadata18setLensProductNameERK7QString` | 0x155de8 | 8 |
| `_ZNK16SnapshotMetadata18getLensProductNameEv` | 0x155df0 | 8 |
| `_ZN21CambodyProxyInterface12control_ringEN9HblmTypes17E_ControlRingTypeENS0_12E_WheelStateENS0_13E_EventSourceE` | 0x164f28 | 84 |
| `_ZN18LensProxyInterface20is_af_allowedChangedEb` | 0x1687bc | 60 |
| `_ZN18LensProxyInterface24lens_product_nameChangedERK7QString` | 0x168834 | 52 |
| `_ZN18LensProxyInterface30user_input_capabilitiesChangedEj` | 0x1689d0 | 60 |
| `_ZN20ConfigProxyInterface39user_wheel_control_ring_functionChangedEN9HblmTypes19E_UserWheelFunctionE` | 0x16c548 | 60 |

**Removed functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z17qRegisterMetaTypeIN9HblmTypes20E_UserButtonFunctionEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x165154 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes14E_JoystickNameEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x16528c | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes19E_JoystickDirectionEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x1654fc | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes12E_WheelStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x165634 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes11E_WheelNameEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x16576c | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes15E_JoystickStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x1658a4 | 312 |

**New objects (3)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_ControlRingTypeEE14qt_metatype_idEvE11metatype_id` | 0x203f94 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes19E_UserWheelFunctionEE14qt_metatype_idEvE11metatype_id` | 0x203ff8 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes15E_LensUserInputEE14qt_metatype_idEvE11metatype_id` | 0x203ffc | 4 |

### `/bin/odindb-send`

+4 / −6 functions · +2 / −0 objects

**New functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE8DestructEPv` | 0x5e12c | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE9ConstructEPvPKv` | 0x5e130 | 20 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE8DestructEPv` | 0xb8bf0 | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE9ConstructEPvPKv` | 0xb8bf4 | 20 |

**Removed functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z17qRegisterMetaTypeIN9HblmTypes20E_UserButtonFunctionEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x5d3bc | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes14E_JoystickNameEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x5d4f4 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes19E_JoystickDirectionEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x5d764 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes12E_WheelStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x5d89c | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes11E_WheelNameEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x5d9d4 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes15E_JoystickStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x5db0c | 312 |

**New objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_ControlRingTypeEE14qt_metatype_idEvE11metatype_id` | 0x1a4098 | 4 |
| `_ZZN11QMetaTypeIdIN9HblmTypes19E_UserWheelFunctionEE14qt_metatype_idEvE11metatype_id` | 0x1a41a8 | 4 |

### `/bin/msg2dbus`

+2 / −7 functions · +1 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE8DestructEPv` | 0x75d9c | 4 |
| `_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE9ConstructEPvPKv` | 0x75da0 | 20 |

**Removed functions (7)**

| Symbol | Addr | Size |
|---|---|---|
| `_Z17qRegisterMetaTypeIN9HblmTypes20E_UserButtonFunctionEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x75470 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes14E_JoystickNameEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x755a8 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes13E_EventSourceEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x756e0 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes19E_JoystickDirectionEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x75818 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes12E_WheelStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x75950 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes11E_WheelNameEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x75a88 | 312 |
| `_Z17qRegisterMetaTypeIN9HblmTypes15E_JoystickStateEEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS4_Xaasr12QMetaTypeId2IS4_E7DefinedntsrS9_9IsBuiltInEE11DefinedTypeE` | 0x75bc0 | 312 |

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN11QMetaTypeIdIN9HblmTypes17E_ControlRingTypeEE14qt_metatype_idEvE11metatype_id` | 0xab4e8 | 4 |

### `/lib/weston/eagle-backend.so`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `unrd_read_string` | 0xb6b9 | 228 |
| `unrd_read_int` | 0xb79d | 64 |

### `/etc/firmware/rtnodes/app.elf`

+0 / −1 functions · +241 / −232 objects

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `e843419@00f4_00004a2f_434` | 0xfda10 | 8 |

**New objects (241)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.13257` | 0x1253e0 | 19 |
| `__func__.13274` | 0x1253f8 | 15 |
| `__func__.13312` | 0x125408 | 12 |
| `__func__.13334` | 0x125418 | 9 |
| `__func__.13349` | 0x125428 | 9 |
| `__func__.13367` | 0x125438 | 15 |
| `__func__.13400` | 0x125448 | 20 |
| `__func__.13483` | 0x125460 | 11 |
| `__func__.11719` | 0x125558 | 13 |
| `__func__.11744` | 0x125568 | 21 |
| `__func__.12866` | 0x125688 | 13 |
| `__func__.12900` | 0x125698 | 21 |
| `__func__.12914` | 0x1256b0 | 20 |
| `__func__.12936` | 0x1256c8 | 23 |
| `__func__.11920` | 0x125908 | 16 |
| `__func__.12004` | 0x125918 | 25 |
| `__func__.12017` | 0x125938 | 24 |
| `__func__.12015` | 0x125a20 | 21 |
| `__func__.12030` | 0x125a38 | 25 |
| `__func__.12044` | 0x125a58 | 24 |
| `__func__.12066` | 0x125a70 | 32 |
| `__func__.11820` | 0x125b80 | 23 |
| `__func__.11585` | 0x126880 | 13 |
| `__func__.11619` | 0x126890 | 16 |
| `__func__.11633` | 0x1268a0 | 15 |
| `__FUNCTION__.13851` | 0x127038 | 35 |
| `__FUNCTION__.13889` | 0x127060 | 41 |
| `__func__.13991` | 0x127090 | 33 |
| `__func__.14004` | 0x1270b8 | 31 |
| `__FUNCTION__.12842` | 0x127260 | 24 |
| `__FUNCTION__.12866` | 0x127278 | 24 |
| `__FUNCTION__.14572` | 0x127a38 | 23 |
| `__func__.14653` | 0x127a50 | 37 |
| `hblm_prop_config_user_wheel_control_ring_function` | 0x1291a8 | 33 |
| `hblm_prop_lens_is_af_allowed` | 0x1295e8 | 14 |
| `hblm_prop_lens_lens_product_name` | 0x129608 | 18 |
| `hblm_prop_lens_user_input_capabilities` | 0x1296e0 | 24 |
| `__func__.13565` | 0x12c9b8 | 18 |
| `__func__.13279` | 0x12c9d0 | 15 |
| `__func__.13301` | 0x12c9f8 | 13 |
| `__func__.13263` | 0x12ca08 | 13 |
| `__func__.13680` | 0x12ca18 | 16 |
| `__FUNCTION__.14518` | 0x12d5b8 | 26 |
| `__func__.14630` | 0x12d5d8 | 33 |
| `__FUNCTION__.14654` | 0x12d600 | 28 |
| `__func__.14925` | 0x12d620 | 30 |
| `__func__.15012` | 0x12d640 | 34 |
| `__func__.15052` | 0x12d668 | 28 |
| `__func__.15080` | 0x12d688 | 32 |
| `__func__.15251` | 0x12dd50 | 29 |

<details><summary>… 另 191 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__func__.15513` | 0x12dd70 | 27 |
| `__FUNCTION__.15554` | 0x12dd90 | 18 |
| `__FUNCTION__.15602` | 0x12dda8 | 39 |
| `__func__.15629` | 0x12ddd0 | 27 |
| `__func__.12906` | 0x12e010 | 18 |
| `lensImprint.12873` | 0x12e028 | 16 |
| `__func__.12575` | 0x12e220 | 22 |
| `__func__.12607` | 0x12e238 | 26 |
| `__func__.12454` | 0x12e4b8 | 35 |
| `__func__.12916` | 0x12eb08 | 22 |
| `__func__.13193` | 0x12eb20 | 21 |
| `__func__.12621` | 0x12edc8 | 24 |
| `__func__.13945` | 0x12f0e0 | 30 |
| `__func__.12115` | 0x12f248 | 23 |
| `__func__.12128` | 0x12f260 | 22 |
| `__func__.13240` | 0x12f670 | 24 |
| `__func__.13341` | 0x12f688 | 27 |
| `__FUNCTION__.13465` | 0x12f6a8 | 11 |
| `LM26HSEPEN_MASK.12089` | 0x13000f | 1 |
| `LM26HSEPEN_ADDR.12088` | 0x130010 | 1 |
| `BLKDUMMY_LSB_ADDR.12120` | 0x130011 | 1 |
| `BLKDUMMY_MSB_ADDR.12121` | 0x130012 | 1 |
| `BLKLEVEL_LSB_ADDR.12125` | 0x130013 | 1 |
| `BLKLEVEL_MSB_ADDR.12126` | 0x130014 | 1 |
| `EXCKDLY_ADDR.12142` | 0x130015 | 1 |
| `SPL.11964` | 0x13022c | 4 |
| `SMD_ADDR.11983` | 0x130230 | 1 |
| `SMD_MASK.11984` | 0x130231 | 1 |
| `WINDOWMODE_ADDR.11991` | 0x130232 | 1 |
| `WINDOWMODE_MASK.11992` | 0x130233 | 1 |
| `WINDOWMODE_VAL_BDUMMY_WDUMMY_VOPB_EFFECTIVE.11994` | 0x130234 | 1 |
| `WINDOWMODE_VAL_DISABLED.11993` | 0x130235 | 1 |
| `ROW.12143` | 0x130554 | 4 |
| `ROW.12227` | 0x130558 | 4 |
| `__FUNCTION__.12666` | 0x1306d8 | 21 |
| `__FUNCTION__.12998` | 0x130a88 | 11 |
| `__FUNCTION__.12286` | 0x130b10 | 23 |
| `__func__.12090` | 0x132140 | 21 |
| `__func__.14829` | 0x133120 | 8 |
| `__func__.12490` | 0x133450 | 31 |
| `__func__.13300` | 0x1336e0 | 19 |
| `__FUNCTION__.12047` | 0x133e50 | 17 |
| `__FUNCTION__.12246` | 0x133e68 | 31 |
| `__FUNCTION__.12318` | 0x133e88 | 35 |
| `__FUNCTION__.12331` | 0x133eb0 | 46 |
| `__FUNCTION__.12347` | 0x133ee0 | 35 |
| `__FUNCTION__.12380` | 0x133f08 | 23 |
| `AXI_HP1.12252` | 0x1343bc | 4 |
| `AXI_HP3.12253` | 0x1343c0 | 4 |
| `__func__.13108` | 0x134568 | 21 |
| `__FUNCTION__.12464` | 0x134768 | 20 |
| `__func__.13576` | 0x134aa8 | 22 |
| `VCC_PL_INT.13299` | 0x135358 | 4 |
| `pl_por_b.13303` | 0x13535c | 4 |
| `pl_init.13304` | 0x135360 | 4 |
| `__FUNCTION__.11585` | 0x1368d8 | 9 |
| `__FUNCTION__.11614` | 0x1368e8 | 13 |
| `__FUNCTION__.11644` | 0x1368f8 | 9 |
| `__FUNCTION__.11675` | 0x136908 | 13 |
| `N.12428` | 0x136c8c | 4 |
| `__FUNCTION__.12700` | 0x138018 | 16 |
| `__func__.13178` | 0x138028 | 24 |
| `__func__.13194` | 0x138040 | 26 |
| `INVALID_CHANNEL.12592` | 0x138ab4 | 1 |
| `__func__.12814` | 0x139148 | 17 |
| `__func__.12885` | 0x139160 | 12 |
| `__func__.12912` | 0x139170 | 16 |
| `user_wheel_control_ring_function_defval` | 0x13940c | 4 |
| `__func__.14567` | 0x1398b0 | 36 |
| `__func__.14054` | 0x139e48 | 33 |
| `__func__.13803` | 0x13b308 | 23 |
| `__func__.14170` | 0x13b320 | 22 |
| `__func__.14332` | 0x13b338 | 26 |
| `__func__.14354` | 0x13b358 | 20 |
| `__func__.14384` | 0x13b370 | 16 |
| `__func__.14512` | 0x13b380 | 29 |
| `__func__.14600` | 0x13b3a0 | 21 |
| `__func__.14619` | 0x13b3b8 | 9 |
| `__func__.13113` | 0x13c258 | 24 |
| `__func__.13305` | 0x13c270 | 27 |
| `__func__.14409` | 0x13ce40 | 14 |
| `max_unsynced_frames.14507` | 0x13ce68 | 8 |
| `__func__.14532` | 0x13ce70 | 46 |
| `__func__.14772` | 0x13cea0 | 12 |
| `__func__.14947` | 0x13ceb0 | 15 |
| `__func__.15036` | 0x13cec0 | 26 |
| `__func__.14831` | 0x13d748 | 26 |
| `__func__.14845` | 0x13d768 | 37 |
| `__func__.14956` | 0x13d790 | 12 |
| `__func__.15010` | 0x13d7a0 | 21 |
| `__func__.15040` | 0x13d7b8 | 22 |
| `__func__.15107` | 0x13d7d0 | 22 |
| `__func__.15120` | 0x13d7e8 | 11 |
| `__func__.15290` | 0x13d7f8 | 15 |
| `__func__.12943` | 0x13da98 | 23 |
| `__func__.12242` | 0x13ea08 | 13 |
| `__func__.12275` | 0x13ea18 | 10 |
| `__FUNCTION__.11898` | 0x13ee08 | 16 |
| `__FUNCTION__.11925` | 0x13ee18 | 14 |
| `__func__.13656` | 0x13fa00 | 21 |
| `__FUNCTION__.13986` | 0x13fa18 | 40 |
| `__FUNCTION__.14064` | 0x13fa40 | 35 |
| `__func__.12562` | 0x13fad0 | 39 |
| `__func__.13994` | 0x1404b0 | 21 |
| `__func__.14000` | 0x1404c8 | 22 |
| `__FUNCTION__.14009` | 0x1404e0 | 22 |
| `__func__.14016` | 0x1404f8 | 17 |
| `div.14025` | 0x14050c | 4 |
| `steps.14026` | 0x140510 | 4 |
| `dg_array.14022` | 0x140518 | 8 |
| `ag_array.14023` | 0x140520 | 8 |
| `ep_array.14024` | 0x140528 | 8 |
| `__FUNCTION__.14093` | 0x140530 | 39 |
| `__func__.14117` | 0x140558 | 39 |
| `__func__.14169` | 0x140580 | 25 |
| `__func__.14229` | 0x1405b8 | 34 |
| `__func__.14236` | 0x1405e0 | 38 |
| `__func__.14240` | 0x140608 | 34 |
| `__func__.14577` | 0x140630 | 16 |
| `__func__.14671` | 0x140640 | 25 |
| `__func__.14752` | 0x140678 | 17 |
| `__func__.14763` | 0x140690 | 15 |
| `__func__.14787` | 0x1406a0 | 30 |
| `__func__.14792` | 0x1406c0 | 11 |
| `__func__.14800` | 0x1406d0 | 19 |
| `__func__.14804` | 0x1406e8 | 36 |
| `__func__.12218` | 0x140810 | 13 |
| `__func__.12257` | 0x140820 | 19 |
| `__func__.12267` | 0x140838 | 13 |
| `__func__.12276` | 0x140848 | 14 |
| `__FUNCTION__.12874` | 0x140e40 | 21 |
| `__func__.12897` | 0x140e58 | 17 |
| `__func__.13009` | 0x140e70 | 26 |
| `__FUNCTION__.12508` | 0x140f80 | 18 |
| `__FUNCTION__.16098` | 0x141530 | 17 |
| `__FUNCTION__.16283` | 0x141548 | 19 |
| `__FUNCTION__.12544` | 0x141c40 | 22 |
| `tribase.4320` | 0x142408 | 4 |
| `N.11389` | 0x142794 | 4 |
| `af_cur_pos_old.12855` | 0x14d538 | 4 |
| `__compound_literal.159` | 0x14da58 | 3 |
| `__compound_literal.160` | 0x14da60 | 2 |
| `__compound_literal.161` | 0x14da68 | 1 |
| `oldState.14688` | 0x14dae8 | 1 |
| `dynImprint.12874` | 0x14daf8 | 16 |
| `md5_imx161.12791` | 0x14db18 | 16 |
| `md5_imx211.12792` | 0x14db28 | 16 |
| `pxVectorTable.10787` | 0x14db40 | 8 |
| `id.13096` | 0x14f234 | 4 |
| `id.13105` | 0x14f238 | 4 |
| `tmpDataBuffer.13564` | 0x15c2d8 | 257 |
| `prop_handler_msg.13530` | 0x161ec8 | 274 |
| `RecoveryImageNextPartition.14872` | 0x162108 | 2 |
| `resp.15521` | 0x162280 | 5 |
| `old_point.15540` | 0x162288 | 4 |
| `lastupdate.15542` | 0x16228c | 4 |
| `gpioInit.13380` | 0x1623b8 | 1 |
| `started.13893` | 0x16256a | 1 |
| `b.14541` | 0x16a348 | 514 |
| `msg.14783` | 0x16a550 | 274 |
| `msg2.14784` | 0x16a668 | 4 |
| `buf.14794` | 0x16a670 | 256 |
| `mode.14809` | 0x16a770 | 1 |
| `stopdown.14899` | 0x16a771 | 1 |
| `old_checksum.13474` | 0x16a860 | 4 |
| `b.12419` | 0x16b310 | 65 |
| `FileInfo.13074` | 0x16bf00 | 24 |
| `retry.14835` | 0x16dc1c | 2 |
| `ticks_since_last_dir_change.12812` | 0x16de50 | 2 |
| `lastState.12946` | 0x16de54 | 4 |
| `last_ts.13575` | 0x17c450 | 8 |
| `retry_count.13362` | 0x17c45c | 4 |
| `check_id.14492` | 0x18d58b | 1 |
| `last_id.14493` | 0x18d58c | 1 |
| `aaa_stat.14911` | 0x18d590 | 55616 |
| `info_update_cnt.14979` | 0x19aed0 | 4 |
| `ae_spi_count.14048` | 0x19aed4 | 4 |
| `noLensTraced.14864` | 0x19b050 | 1 |
| `cnt.14717` | 0x1f4ed4 | 4 |
| `md5_digest.13837` | 0x11f5428 | 16 |
| `previousValue.13993` | 0x11f9418 | 4 |
| `previousValue.13999` | 0x11f941c | 4 |
| `previous_value.14015` | 0x11f9420 | 8 |
| `count.14034` | 0x11f9428 | 4 |
| `index.14035` | 0x11f942c | 4 |
| `dgain.14027` | 0x11f9430 | 4 |
| `again.14028` | 0x11f9434 | 4 |
| `ep_ms.14029` | 0x11f9438 | 4 |
| `tmpDisabled.11625` | 0x11f9d18 | 1 |
| `flushType.14325` | 0x7f002060 | 4 |
| `imageMode.14326` | 0x7f002064 | 4 |

</details>

**Removed objects (232)**

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.13193` | 0x1261e0 | 19 |
| `__func__.13210` | 0x1261f8 | 15 |
| `__func__.13270` | 0x126218 | 9 |
| `__func__.13285` | 0x126228 | 9 |
| `__func__.13303` | 0x126238 | 15 |
| `__func__.13336` | 0x126248 | 20 |
| `__func__.13419` | 0x126260 | 11 |
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

<details><summary>… 另 182 个</summary>

| Symbol | Addr | Size |
|---|---|---|
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
| `__func__.13130` | 0x138cb8 | 26 |
| `INVALID_CHANNEL.12528` | 0x13972c | 1 |
| `__func__.12750` | 0x139dc0 | 17 |
| `__func__.12821` | 0x139dd8 | 12 |
| `__func__.12848` | 0x139de8 | 16 |
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
| `__func__.14172` | 0x141200 | 38 |
| `__func__.14513` | 0x141250 | 16 |
| `__func__.14607` | 0x141260 | 25 |
| `__func__.14635` | 0x141280 | 22 |
| `__func__.14688` | 0x141298 | 17 |
| `__func__.14723` | 0x1412c0 | 30 |
| `__func__.14728` | 0x1412e0 | 11 |
| `__func__.14736` | 0x1412f0 | 19 |
| `__func__.14740` | 0x141308 | 36 |
| `__func__.12154` | 0x141430 | 13 |
| `__func__.12193` | 0x141440 | 19 |
| `__func__.12203` | 0x141458 | 13 |
| `__func__.12212` | 0x141468 | 14 |
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
| `flushType.14261` | 0x7f002048 | 4 |
| `imageMode.14262` | 0x7f00204c | 4 |

</details>

### `/bin/amt_test_cmd`

+0 / −0 functions · +0 / −0 objects

### `/bin/analytics`

+0 / −0 functions · +0 / −0 objects

### `/bin/atrace`

+0 / −0 functions · +0 / −0 objects

### `/bin/audio`

+0 / −0 functions · +0 / −0 objects

### `/bin/blkid`

+0 / −0 functions · +0 / −0 objects

### `/bin/bodystate`

+0 / −0 functions · +0 / −0 objects

### `/bin/boot_control`

+0 / −0 functions · +0 / −0 objects

### `/bin/bootlogo`

+0 / −0 functions · +0 / −0 objects

### `/bin/c2d_ut`

+0 / −0 functions · +0 / −0 objects

### `/bin/camera`

+0 / −0 functions · +0 / −0 objects

### `/bin/camservice`

+0 / −0 functions · +0 / −0 objects

### `/bin/configstore`

+0 / −0 functions · +0 / −0 objects

### `/bin/coremark`

+0 / −0 functions · +0 / −0 objects

### `/bin/dbus-daemon`

+0 / −0 functions · +0 / −0 objects

### `/bin/dbus-send`

+0 / −0 functions · +0 / −0 objects

### `/bin/dbus-watcher`

+0 / −0 functions · +0 / −0 objects

### `/bin/debuggerd`

+0 / −0 functions · +0 / −0 objects

### `/bin/dhcpcd`

+0 / −0 functions · +0 / −0 objects

### `/bin/dhcptool`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_amt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_bb_spliter`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_blackbox`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_cht`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_cspp`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_dsp_load`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_ftpd`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_fw_load`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_fw_verify`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_gdc_test`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_iosconn`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_kmsg`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_log_encrypt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_mb_ctrl`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_mb_parser`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_monitor`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_pbt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_ppt`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_quick_charge`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_rcam`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_sys`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_wms`

+0 / −0 functions · +0 / −0 objects

### `/bin/dji_wms-v1`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **820** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/victory-gui-static`

<details><summary>新增 346 条字符串, 展示前 100 条</summary>

````text
         d="m 130.39722,114.59755 h 13.4656 v 13.46561 h -13.4656 z"
         d="m 141.11928,117.51348 1.11523,1.12696 -6.68945,6.76953 -3.31641,-3.35547 1.12109,-1.12695 2.19532,2.22265 z"
         d="m 143.86282,114.59755 h 13.4656 v 13.46561 h -13.4656 z"
         d="m 154.58488,117.51348 1.11523,1.12696 -6.68945,6.76953 -3.31641,-3.35547 1.12109,-1.12695 2.19532,2.22265 z"
         d="m 158.01112,137.55293 h 13.49319 v 13.4932 h -13.49319 z"
         d="m 159.2451,138.78691 h 11.02523 v 11.02524 H 159.2451 Z"
         height="12.170834"
         id="
         id="line5"
         id="line831" />
         id="line833"
         id="path1071" />
         id="path1073"
         id="path1102" />
         id="path1108"
         id="path1136" />
         id="path1138"
         id="rect1034" />
         stroke-width="1.05833"
         stroke="#808080"
         style="color:#000000;font-style:normal;font-variant:normal;font-weight:normal;font-stretch:normal;font-size:medium;line-height:normal;font-family:sans-serif;font-variant-ligatures:normal;font-variant-position:normal;font-variant-caps:normal;font-variant-numeric:normal;font-variant-alternates:normal;font-variant-east-asian:normal;font-feature-settings:normal;font-variation-settings:normal;text-indent:0;text-align:start;text-decoration:none;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000000;letter-spacing:normal;word-spacing:normal;text-transform:none;writing-mode:lr-tb;direction:ltr;text-orientation:mixed;dominant-baseline:auto;baseline-shift:baseline;text-anchor:start;white-space:normal;shape-padding:0;shape-margin:0;inline-size:0;clip-rule:nonzero;display:inline;overflow:visible;visibility:visible;isolation:auto;mix-blend-mode:normal;color-interpolation:sRGB;color-interpolation-filters:linearRGB;solid-color:#000000;solid-opacity:1;vector-effect:none;fill:#000000;fill-opacity:1;fill-rule:evenodd;stroke:#000000;stroke-width:0.265;stroke-linecap:butt;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1;color-rendering:auto;image-rendering:auto;shape-rendering:auto;text-rendering:auto;enable-background:accumulate;stop-color:#000000" />
         style="color:#000000;font-style:normal;font-variant:normal;font-weight:normal;font-stretch:normal;font-size:medium;line-height:normal;font-family:sans-serif;font-variant-ligatures:normal;font-variant-position:normal;font-variant-caps:normal;font-variant-numeric:normal;font-variant-alternates:normal;font-variant-east-asian:normal;font-feature-settings:normal;font-variation-settings:normal;text-indent:0;text-align:start;text-decoration:none;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000000;letter-spacing:normal;word-spacing:normal;text-transform:none;writing-mode:lr-tb;direction:ltr;text-orientation:mixed;dominant-baseline:auto;baseline-shift:baseline;text-anchor:start;white-space:normal;shape-padding:0;shape-margin:0;inline-size:0;clip-rule:nonzero;display:inline;overflow:visible;visibility:visible;isolation:auto;mix-blend-mode:normal;color-interpolation:sRGB;color-interpolation-filters:linearRGB;solid-color:#000000;solid-opacity:1;vector-effect:none;fill:#010101;fill-opacity:1;fill-rule:evenodd;stroke:#000000;stroke-width:0.265;stroke-linecap:butt;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1;color-rendering:auto;image-rendering:auto;shape-rendering:auto;text-rendering:auto;enable-background:accumulate;stop-color:#000000"
         style="fill:#828282;fill-opacity:1;fill-rule:evenodd;stroke:#000000;stroke-width:0.292731;stroke-miterlimit:4;stroke-dasharray:none"
         style="fill:#ffffff;fill-rule:evenodd;stroke:#000000;stroke-width:0.292731;stroke-miterlimit:4;stroke-dasharray:none" />
         style="fill:none;fill-rule:evenodd"
         style="fill:none;fill-rule:evenodd;stroke:#000000;stroke-width:0.264583;stroke-miterlimit:4;stroke-dasharray:none"
         style="fill:none;fill-rule:evenodd;stroke:#000000;stroke-width:0.264583;stroke-miterlimit:4;stroke-dasharray:none" />
         style="stroke-width:2.6400001;stroke-miterlimit:4;stroke-dasharray:none"
         style="stroke:#000000;stroke-width:3.6400001;stroke-miterlimit:4;stroke-dasharray:none"
         style="stroke:#000000;stroke-width:3.6400001;stroke-miterlimit:4;stroke-dasharray:none" />
         transform="matrix(-1,0,0,1,25.342708,0)"
         width="12.170834"
         x1="-5.1697257e-14"
         x1="-5.1697257e-14" />
         x1="5.9715843e-14"
         x1="5.9715843e-14" />
         x2="25.342707"
         x="158.6723"
         y1="2.1856147e-14"
         y1="6.1646543e-14"
         y2="25.342707"
         y="138.21411"
        <dc:title>ic_cancel</dc:title>
       d="m 158.01112,137.55294 h 13.49374 v 13.49374 h -13.49374 z"
       d="m 159.24515,138.78697 h 11.02568 v 11.02568 h -11.02568 z"
       height="12.171326"
       id="g1086">
       id="g1134">
       id="g1146">
       id="g839">
       id="path1071" />
       id="path1073"
       id="rect1034" />
       style="fill:none;fill-rule:evenodd;stroke:#000000;stroke-width:0.26459399;stroke-miterlimit:4;stroke-dasharray:none"
       style="fill:none;fill-rule:evenodd;stroke:#000000;stroke-width:0.26459399;stroke-miterlimit:4;stroke-dasharray:none" />
       style="fill:none;fill-rule:evenodd;stroke:#ffffff;stroke-width:1.05836999"
       transform="matrix(1.0000407,0,0,1.0000404,-0.00643078,-0.00555164)"
       transform="translate(14.162374)"
       transform="translate(5.0273704)"
       width="12.171329"
       x="158.67233"
       y="138.21414"
      <line
     id="
     id="base" />
     id="defs15" />
     id="metadata17">
     id="namedview13"
     id="title2">ic_cancel</title>
     inkscape:cx="-34.230671"
     inkscape:cx="-483.44384"
     inkscape:cx="27.050847"
     inkscape:cx="43.581678"
     inkscape:cx="56.160632"
     inkscape:cy="-413.08834"
     inkscape:cy="17.283761"
     inkscape:cy="28.355932"
     inkscape:cy="63.075699"
     inkscape:cy="79.765246"
     inkscape:document-rotation="0"
     inkscape:label="Layer 1">
     inkscape:window-height="859"
     inkscape:zoom="0.67097561"
     inkscape:zoom="2.6839024"
     inkscape:zoom="3.7956112"
     inkscape:zoom="4.2142857"
     inkscape:zoom="7.2764644"
     style="fill:none;fill-rule:evenodd;stroke:#ffffff;stroke-width:2.6400001;stroke-linecap:square"
     transform="translate(-135.27822,-114.45118)"
     transform="translate(-157.87882,-137.42064)"
     transform="translate(-157.87882,-137.42064)">
     transform="translate(-157.87883,-114.45118)"
     transform="translate(15.12,15.12)">
   height="13.758339mm"
   height="13.758341mm"
   height="56px"
   id="svg11"
   inkscape:version="1.0 (4035a4fb49, 2020-05-01)"
   sodipodi:docname="CancelButtonCross_outline.svg"
   sodipodi:docname="checkbox_unselected_outline.svg"
````

</details>

> 其余 246 条见 `result.json`。

### `/bin/vdec_test`

<details><summary>新增 64 条字符串</summary>

````text
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/libraries/vdec_api/code/vdec_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/h264_nalparse.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/hevc_nalparse.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/mmf.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/picdelimit_comp.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/reader_comp.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/render_comp.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/vdec_test.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/vdect.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_test/code/vdectfs.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_verif/code/BadBlockDetector.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_verif/code/CrcGenerator.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_verif/code/ovmod.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/vdec_verif/code/verif_mod.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/image_transform/code/transform_tiling.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/dbgopt_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/dbgopt_api_km.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/devif/sysos_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/idgen_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/init.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/pool_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/rman_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/user/dbgopt_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/addr_alloc1.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/hash.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/pool.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/ra.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/talmmu_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/avs_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/bspp.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/bspp_bool_reader.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/h264_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/h264_secure_sei_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/hevc_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/mpeg2_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/mpeg4_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/real_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/vc1_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/vp6_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/vp8_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/core_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/dec_resources.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/decoder.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/hwctrl_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/plant.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/resource.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/scaler_setup.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/scheduler.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/translation_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vdec2plus_msgint.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vdecdd_mmu.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vxd_int.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vxd_uapi.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/vdecdd_utils/code/vdecdd_utils.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/vdecdd_utils/code/vdecdd_utils_buf.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/videolib/libraries/swsr/code/swsr.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/imglib/libraries/cmd/code/cmd_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/imglib/libraries/gzip_fileio/code/gzip_fileio.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/imglib/libraries/pixelapi/code/pixel_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/imglib/libraries/pixelapi/code/pixel_api_internals.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/list_utils/src/dq/dq.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/linux/linosa.c
17:26:20
Aug 26 2022
````

</details>

### `/lib/libappscommon.so`

<details><summary>新增 64 条字符串</summary>

````text
1control_ringWrapper(const int, const int, const int)
E_ControlRingType
E_ControlRingType_Click
E_ControlRingType_Fine
E_ControlRingType_Max
E_ErrorCode_VideoPlaybackStopFailed
E_EventSource_Lens
E_LensUserInput
E_LensUserInput_AfDisableSwitch
E_LensUserInput_ControlRing
E_LensUserInput_Max
E_LensUserInput_None
E_LensUserInput_ZoomAdjust
E_UserWheelFunction
E_UserWheelFunction_Av
E_UserWheelFunction_Iso
E_UserWheelFunction_Max
E_UserWheelFunction_None
E_UserWheelFunction_ProgramShift
E_UserWheelFunction_QuickAdj
E_UserWheelFunction_Tv
HblmTypes::E_ControlRingType
HblmTypes::E_LensUserInput
HblmTypes::E_UserWheelFunction
_ZN11ConfigProxy35setUser_wheel_control_ring_functionEN9HblmTypes19E_UserWheelFunctionE
_ZN12CambodyProxy19connectControl_ringEv
_ZN12CambodyProxy22disconnectControl_ringEv
_ZN16SnapshotMetadata18setLensProductNameERK7QString
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_LensUserInputELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes15E_LensUserInputELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE9ConstructEPvPKv
_ZN18LensProxyInterface20is_af_allowedChangedEb
_ZN18LensProxyInterface24lens_product_nameChangedERK7QString
_ZN18LensProxyInterface30user_input_capabilitiesChangedEj
_ZN20ConfigProxyInterface39user_wheel_control_ring_functionChangedEN9HblmTypes19E_UserWheelFunctionE
_ZN21CambodyProxyInterface12control_ringEN9HblmTypes17E_ControlRingTypeENS0_12E_WheelStateENS0_13E_EventSourceE
_ZNK11ConfigProxy32user_wheel_control_ring_functionEv
_ZNK16SnapshotMetadata18getLensProductNameEv
_ZNK9LensProxy13is_af_allowedEv
_ZNK9LensProxy17lens_product_nameEv
_ZNK9LensProxy23user_input_capabilitiesEv
_ZZN11QMetaTypeIdIN9HblmTypes15E_LensUserInputEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes17E_ControlRingTypeEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes19E_UserWheelFunctionEE14qt_metatype_idEvE11metatype_id
control_ring
control_ringWrapper
control_ring_type
is_af_allowed
is_af_allowedChanged
lensProductName
lens_product_name
lens_product_nameChanged
user_input_capabilities
user_input_capabilitiesChanged
user_wheel_control_ring_function
user_wheel_control_ring_functionChanged
virtual HblmTypes::E_UserWheelFunction ConfigProxy::user_wheel_control_ring_function() const
virtual PendingCallWatcher* ConfigProxy::setUser_wheel_control_ring_function(HblmTypes::E_UserWheelFunction)
virtual bool LensProxy::is_af_allowed() const
virtual const QString& LensProxy::lens_product_name() const
virtual uint LensProxy::user_input_capabilities() const
````

</details>

### `/bin/phocus`

<details><summary>新增 62 条字符串</summary>

````text
 payload.length:
 result:
27FocusPositionUpdateObserver
Disable focus position updates
DriveModeIntervalTime
Enable focus position updates
FocusPositionUpdateObserver
Language
LensProductName
No longer tethered so disable focus position updates.
Re-enable focus position updates since phocus still requests them
_ZN11QTextStreamC1EP7QString6QFlagsIN9QIODevice12OpenModeFlagEE
_ZN11QTextStreamD1Ev
_ZN18LensProxyInterface24lens_product_nameChangedERK7QString
_ZN18LensProxyInterface35focus_position_update_activeChangedEb
_ZN20ConfigProxyInterface20languageIndexChangedEt
_ZTV9LensProxy
activate
camErrActionNotSupported
camErrAdjustFocus
camErrBodyMode
camErrBurstMemFull
camErrCambody
camErrCanExpose
camErrDbusCallFailure
camErrDoExposure
camErrFindFocus
camErrInvalidAction
camErrInvalidIndex
camErrInvalidTetheringMode
camErrLiveView
camErrNoImages
camErrNoTethering
camErrParamCheck
camErrParamNotFound
camErrParamNotSupported
camErrRequestFile
camErrSystemState
camErrTetheredRequest
camErrUndefined
camErrUnlockImage
deactivate
kAdjustFocusCameraAction
kAutoFocusCameraAction
kDeleteCameraAction
kFocusPositionUpdateAction
kLiveVideoCameraAction
kLiveVideoModeCamParam
kNoCameraAction
kRebootCameraAction
kSendNmeaAction
kSetHasselbladHostAction
kSetTetheredCameraAction
kStopCameraAction
kTakePictureCameraAction
kUnlockCameraAction
kUpdateImageCameraAction
kVideoRecordAction
languageIndex
onLanguageIndexChanged
onLensProductNameChanged
productName
````

</details>

### `/lib/libomx_vxd.so`

<details><summary>新增 59 条字符串</summary>

````text
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/apis/vdec/libraries/vdec_api/code/vdec_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/dbgopt_api_km.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/devif/sysos_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/idgen_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/init.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/pool_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/port_fwrk/kernel/rman_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/addr_alloc1.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/hash.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/pool.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/ra.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/imgvideo/talmmu_api/code/talmmu_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/avs_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/bspp.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/bspp_bool_reader.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/h264_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/h264_secure_sei_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/hevc_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/mpeg2_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/mpeg4_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/real_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/vc1_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/vp6_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/bspp/code/vp8_secure_parser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/core_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/dec_resources.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/decoder.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/hwctrl_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/plant.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/resource.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/scaler_setup.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/scheduler.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/translation_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vdec2plus_msgint.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vdecdd_mmu.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vxd_int.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/decoder/code/vxd_uapi.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/vdecdd_utils/code/vdecdd_utils.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/kernel_device/libraries/vdecdd_utils/code/vdecdd_utils_buf.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_component/code/img_omd_comp.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_component/code/img_omd_msg_mon.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_component/code/img_omd_ports.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_component/code/img_omd_states.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_component/code/img_omd_utils.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_component/code/img_omd_vdec_task.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/omx/omx_core/src/img_omx_core.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/videolib/libraries/swsr/code/swsr.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/imglib/libraries/pixelapi/code/pixel_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/imglib/libraries/pixelapi/code/pixel_api_internals.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/list_utils/src/dq/dq.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/linux/linosa.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/utils/osa_idgen.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/utils/osa_rman.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/utils/osa_utils.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/dbgopt_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/linux/sysbrg_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/page_alloc.c
17:26:20
Aug 26 2022
````

</details>

### `/bin/odindb-send`

<details><summary>新增 33 条字符串</summary>

````text
  E_ErrorCode_VideoPlaybackStopFailed(93)
  E_EventSource_Lens(2)
HblmTypes::E_ControlRingType
HblmTypes::E_UserWheelFunction
_ZN11ConfigProxy35setUser_wheel_control_ring_functionEN9HblmTypes19E_UserWheelFunctionE
_ZN12CambodyProxy19connectControl_ringEv
_ZN12CambodyProxy22disconnectControl_ringEv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE9ConstructEPvPKv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes19E_UserWheelFunctionELb1EE9ConstructEPvPKv
_ZN18LensProxyInterface20is_af_allowedChangedEb
_ZN18LensProxyInterface24lens_product_nameChangedERK7QString
_ZN18LensProxyInterface30user_input_capabilitiesChangedEj
_ZN20ConfigProxyInterface39user_wheel_control_ring_functionChangedEN9HblmTypes19E_UserWheelFunctionE
_ZN21CambodyProxyInterface12control_ringEN9HblmTypes17E_ControlRingTypeENS0_12E_WheelStateENS0_13E_EventSourceE
_ZNK11ConfigProxy32user_wheel_control_ring_functionEv
_ZNK9LensProxy13is_af_allowedEv
_ZNK9LensProxy17lens_product_nameEv
_ZNK9LensProxy23user_input_capabilitiesEv
_ZTV9LensProxy
_ZZN11QMetaTypeIdIN9HblmTypes17E_ControlRingTypeEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN9HblmTypes19E_UserWheelFunctionEE14qt_metatype_idEvE11metatype_id
control_ring
control_ring_type = %1(%2)
is_af_allowed = %1
is_af_allowedChanged
lens_product_name = %1
lens_product_nameChanged
user_input_capabilities = %1
user_input_capabilitiesChanged
user_wheel_control_ring_function = %1(%2)
user_wheel_control_ring_functionChanged
````

</details>

### `/etc/firmware/rtnodes/app.elf`

<details><summary>新增 24 条字符串</summary>

````text
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/apps-messaging/code/include/hblm_farmus_properties.inc
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/FreeRTOS_9_0_0_0/event_groups.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/FreeRTOS_9_0_0_0/portable/GCC/ARM_CA53_64_BIT/port.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/FreeRTOS_9_0_0_0/portable/MemMang/heap_4.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/FreeRTOS_9_0_0_0/queue.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/FreeRTOS_9_0_0_0/tasks.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/FreeRTOS_9_0_0_0/timers.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/rtnodes/farmus/app/src/msgrouter/msgutil.h
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/systemcommon/msgtransp/code/src/hblm_debug.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/systemcommon/msgtransp/code/src/hblm_msgtransp.c
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/systemcommon/msgtransp/code/src/port/platform_freertos.c
10.00.29.07-8aac72e
10.00.29.07-b3ccef4
16:52:09
Aug 26 2022
b3ccef4
cambody_control_ring_event
is_af_allowed
lens_changed_is_af_allowed
lens_changed_lens_product_name
lens_changed_user_input_capabilities
lens_product_name
user_input_capabilities
user_wheel_control_ring_function
````

</details>

### `/bin/vxe_testbench`

<details><summary>新增 21 条字符串</summary>

````text
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api_internal_FWRegisters.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api_internal_headers_h264.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api_internal_headers_h265.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/gop_helper.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_GOP.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_GOP_generic.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_params.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_recon.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/kernel/code/memmgr/memmgr_um.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/test_apps/shared/code/wrap_buffer_allocate.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/test_apps/vxe_testbench/code/CommandlineParser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/test_apps/vxe_testbench/code/ControlThread.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/test_apps/vxe_testbench/code/EncoderThread.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/list_utils/src/dq/dq.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/linux/linosa.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/linux/sysbrg_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/page_alloc.c
17:26:07
Aug 26 2022
````

</details>

### `/lib/libQt5Core.so`

<details><summary>新增 21 条字符串</summary>

````text
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/bignum-dtoa.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/bignum.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/cached-powers.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/diy-fp.h
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/double-conversion.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/fast-dtoa.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/fixed-dtoa.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/ieee.h
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/include/double-conversion/utils.h
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/double-conversion/strtod.cc
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-arabic.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-greek.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-hangul.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-hebrew.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-indic.cpp
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-khmer.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-myanmar.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-shaper.cpp
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-thai.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/3rdparty/harfbuzz/src/harfbuzz-tibetan.c
/data/android6_maintance/daily_build/external/qt/qtbase/src/corelib/io/qloggingregistry.cpp
````

</details>

### `/lib/libhelper_api_sa.so`

<details><summary>新增 21 条字符串</summary>

````text
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api_internal_FWRegisters.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api_internal_headers_h264.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/encode_api/code/vxe_api_internal_headers_h265.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/gop_helper.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_GOP.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_GOP_generic.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_params.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/helper/code/vxe_api_helper_recon.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/encoder/quartz/driver/kernel/code/memmgr/memmgr_um.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/list_utils/src/dq/dq.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/linux/linosa.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/utils/osa_idgen.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/utils/osa_rman.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/osa/src/utils/osa_utils.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/dbgopt_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/linux/sysbrg_api.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/imgvideo/port_fwrk/user/page_alloc.c
17:24:28
Aug 26 2022
````

</details>

### `/bin/msg2dbus`

````text
HblmTypes::E_ControlRingType
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE8DestructEPv
_ZN17QtMetaTypePrivate23QMetaTypeFunctionHelperIN9HblmTypes17E_ControlRingTypeELb1EE9ConstructEPvPKv
_ZZN11QMetaTypeIdIN9HblmTypes17E_ControlRingTypeEE14qt_metatype_idEvE11metatype_id
control_ring
control_ring_type
emitControl_ring
is_af_allowed
is_af_allowedChanged
lens_product_name
lens_product_nameChanged
user_input_capabilities
user_input_capabilitiesChanged
````

### `/bin/prodconfig-tool`

````text
/data/android6_maintance/daily_build/hardware/hbl/hbl-fw/linux/helpers/prodinfo/prodinfo.cpp
Identity/SuVariant
Set SU variant
SuVariant
SuVariant:                      
_ZN4Unrd3setEPKcS1_
_ZNK7QString6toUIntEPbi
_ZNSt3__19to_stringEj
su-variant
su_variant
variant
````

### `/lib/weston/eagle-backend.so`

````text
%s: Unrd error, returned %d => SuVariant=%d
%s: Unrd read done: SuVariant=%d
'7GXjv
/dev/block/platform/soc/f0000000.ahb/f0400000.dwmmc0/by-name/env
/dev/unrd
posix_memalign
strncpy
su_variant
unrd_read_int
unrd_read_string
````

### `/bin/camera`

````text
AF is disabled by lens switch
AF is not allowed by the lens
CfvStateMachine::doCaptureImage(quint32)::<lambda()>
Overriding forceFindFocus since eshutter is used without lens, exp_mode is MQ or lens has disabled AF
_ZN18LensProxyInterface20is_af_allowedChangedEb
active screen allow live view:
afAllowed
onLensIsAfAllowedChanged
set liveview at finish: %1
````

### `/bin/configstore`

````text
Identity/SuVariant
SuVariant
SuVariant:                      
_ZN4Unrd3setEPKcS1_
_ZNSt3__19to_stringEj
su_variant
user_wheel_control_ring_function
user_wheel_control_ring_function_maxval
user_wheel_control_ring_function_minval
````

### `/lib/libVdecAppGST.so`

````text
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/asfpacket.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/gqueue.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/gstasfdemux.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/gstavidemux.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/gstivfparse.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/gstparser.c
/home/build/android6_maintance/daily_build/hardware/dji/common/codec/imgtec/userbuild/img/decoder/vdec/gstreamer/vdec_gst/webpparse.c
````

### `/bin/sutest`

````text
Identity/SuVariant
SuVariant
SuVariant:                      
_ZN4Unrd3setEPKcS1_
_ZNSt3__19to_stringEj
su_variant
````

### `/lib/libAppsMessaging.so`

````text
b3ccef4
cambody_control_ring_event
lens_changed_is_af_allowed
lens_changed_lens_product_name
lens_changed_user_input_capabilities
````

### `/lib/libQt5Positioning.so`

````text
/data/android6_maintance/daily_build/external/libcxx/include/vector
/data/android6_maintance/daily_build/external/qt/qtlocation/src/3rdparty/poly2tri/common/shapes.cpp
/data/android6_maintance/daily_build/external/qt/qtlocation/src/3rdparty/poly2tri/sweep/../common/shapes.h
/data/android6_maintance/daily_build/external/qt/qtlocation/src/3rdparty/poly2tri/sweep/advancing_front.cpp
/data/android6_maintance/daily_build/external/qt/qtlocation/src/3rdparty/poly2tri/sweep/sweep.cpp
````

### `/bin/dji_sys`

````text
17:01:33
17:01:35
Aug 26 2022
````

### `/lib/libduml_frwk.so`

````text
17:00:26
17:00:27
Aug 26 2022
````

### `/bin/dji_amt`

````text
17:01:23
Aug 26 2022
````

### `/bin/dji_blackbox`

````text
17:01:23
Aug 26 2022
````

### `/bin/metadata`

````text
_ZN16SnapshotMetadata18setLensProductNameERK7QString
_ZN9LensProxyC1EP7QObjectb
````

### `/bin/storage`

````text
_ZNK16SnapshotMetadata18getLensProductNameEv
onFlushFile
````

### `/lib/libLLVM.so`

````text
17:04:27
Aug 26 2022
````

### `/lib/libavcodec.so`

````text
--prefix=/home/build/android6_maintance/daily_build/external/ffmpeg/prefix --arch=arm --target-os=linux --enable-cross-compile --cross-prefix=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi- --cc=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-gcc --sysroot=/home/build/android6_maintance/daily_build/prebuilts/ndk/current/platforms/android-18/arch-arm --enable-gpl --enable-shared --disable-static --extra-cflags='-mtune=cortex-a7 -march=armv7-a -mfloat-abi=softfp -mfpu=neon -D_GNU_SOURCE -fno-builtin-sin -fno-builtin-cos -std=c99 -D_USE_ANDROID_LOGGER' --extra-ldflags='-Wl,--fix-cortex-a8 -llog' --disable-everything --disable-doc --enable-decoder=h264 --enable-decoder=hevc --enable-parser=h264 --enable-decoder=hevc --enable-parser=hevc --enable-decoder=aac --enable-muxer=mpeg2video --enable-encoder=mpeg2video --enable-muxer=mp4 --enable-muxer=mov --enable-demuxer=mov --enable-demuxer=prores --enable-demuxer=aac --enable-muxer=mjpeg --enable-encoder=mjpeg --enable-muxer=mpegts --enable-demuxer=mpegts --disable-demuxer=asf --enable-demuxer=h264 --enable-muxer=h264 --enable-demuxer=hevc --enable-muxer=hevc --disable-muxer=adts --disable-muxer=latm --disable-protocol=rtp --enable-protocol=file --enable-protocol=djiin2 --disable-devices --disable-swscale --disable-symver --enable-bsfs --enable-filter=amix --enable-filter=volume --enable-filter=aformat --enable-filter=aresample --disable-asm --enable-pic
FFmpeg version db/eagle_ec1704-v10.00.24.00-20201227023203
````

### `/lib/libavfilter.so`

````text
--prefix=/home/build/android6_maintance/daily_build/external/ffmpeg/prefix --arch=arm --target-os=linux --enable-cross-compile --cross-prefix=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi- --cc=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-gcc --sysroot=/home/build/android6_maintance/daily_build/prebuilts/ndk/current/platforms/android-18/arch-arm --enable-gpl --enable-shared --disable-static --extra-cflags='-mtune=cortex-a7 -march=armv7-a -mfloat-abi=softfp -mfpu=neon -D_GNU_SOURCE -fno-builtin-sin -fno-builtin-cos -std=c99 -D_USE_ANDROID_LOGGER' --extra-ldflags='-Wl,--fix-cortex-a8 -llog' --disable-everything --disable-doc --enable-decoder=h264 --enable-decoder=hevc --enable-parser=h264 --enable-decoder=hevc --enable-parser=hevc --enable-decoder=aac --enable-muxer=mpeg2video --enable-encoder=mpeg2video --enable-muxer=mp4 --enable-muxer=mov --enable-demuxer=mov --enable-demuxer=prores --enable-demuxer=aac --enable-muxer=mjpeg --enable-encoder=mjpeg --enable-muxer=mpegts --enable-demuxer=mpegts --disable-demuxer=asf --enable-demuxer=h264 --enable-muxer=h264 --enable-demuxer=hevc --enable-muxer=hevc --disable-muxer=adts --disable-muxer=latm --disable-protocol=rtp --enable-protocol=file --enable-protocol=djiin2 --disable-devices --disable-swscale --disable-symver --enable-bsfs --enable-filter=amix --enable-filter=volume --enable-filter=aformat --enable-filter=aresample --disable-asm --enable-pic
FFmpeg version db/eagle_ec1704-v10.00.24.00-20201227023203
````

### `/lib/libavformat.so`

````text
--prefix=/home/build/android6_maintance/daily_build/external/ffmpeg/prefix --arch=arm --target-os=linux --enable-cross-compile --cross-prefix=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi- --cc=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-gcc --sysroot=/home/build/android6_maintance/daily_build/prebuilts/ndk/current/platforms/android-18/arch-arm --enable-gpl --enable-shared --disable-static --extra-cflags='-mtune=cortex-a7 -march=armv7-a -mfloat-abi=softfp -mfpu=neon -D_GNU_SOURCE -fno-builtin-sin -fno-builtin-cos -std=c99 -D_USE_ANDROID_LOGGER' --extra-ldflags='-Wl,--fix-cortex-a8 -llog' --disable-everything --disable-doc --enable-decoder=h264 --enable-decoder=hevc --enable-parser=h264 --enable-decoder=hevc --enable-parser=hevc --enable-decoder=aac --enable-muxer=mpeg2video --enable-encoder=mpeg2video --enable-muxer=mp4 --enable-muxer=mov --enable-demuxer=mov --enable-demuxer=prores --enable-demuxer=aac --enable-muxer=mjpeg --enable-encoder=mjpeg --enable-muxer=mpegts --enable-demuxer=mpegts --disable-demuxer=asf --enable-demuxer=h264 --enable-muxer=h264 --enable-demuxer=hevc --enable-muxer=hevc --disable-muxer=adts --disable-muxer=latm --disable-protocol=rtp --enable-protocol=file --enable-protocol=djiin2 --disable-devices --disable-swscale --disable-symver --enable-bsfs --enable-filter=amix --enable-filter=volume --enable-filter=aformat --enable-filter=aresample --disable-asm --enable-pic
FFmpeg version db/eagle_ec1704-v10.00.24.00-20201227023203
````

### `/lib/libavutil.so`

````text
--prefix=/home/build/android6_maintance/daily_build/external/ffmpeg/prefix --arch=arm --target-os=linux --enable-cross-compile --cross-prefix=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi- --cc=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-gcc --sysroot=/home/build/android6_maintance/daily_build/prebuilts/ndk/current/platforms/android-18/arch-arm --enable-gpl --enable-shared --disable-static --extra-cflags='-mtune=cortex-a7 -march=armv7-a -mfloat-abi=softfp -mfpu=neon -D_GNU_SOURCE -fno-builtin-sin -fno-builtin-cos -std=c99 -D_USE_ANDROID_LOGGER' --extra-ldflags='-Wl,--fix-cortex-a8 -llog' --disable-everything --disable-doc --enable-decoder=h264 --enable-decoder=hevc --enable-parser=h264 --enable-decoder=hevc --enable-parser=hevc --enable-decoder=aac --enable-muxer=mpeg2video --enable-encoder=mpeg2video --enable-muxer=mp4 --enable-muxer=mov --enable-demuxer=mov --enable-demuxer=prores --enable-demuxer=aac --enable-muxer=mjpeg --enable-encoder=mjpeg --enable-muxer=mpegts --enable-demuxer=mpegts --disable-demuxer=asf --enable-demuxer=h264 --enable-muxer=h264 --enable-demuxer=hevc --enable-muxer=hevc --disable-muxer=adts --disable-muxer=latm --disable-protocol=rtp --enable-protocol=file --enable-protocol=djiin2 --disable-devices --disable-swscale --disable-symver --enable-bsfs --enable-filter=amix --enable-filter=volume --enable-filter=aformat --enable-filter=aresample --disable-asm --enable-pic
FFmpeg version db/eagle_ec1704-v10.00.24.00-20201227023203
````

### `/lib/libdjishare.so`

````text
busybox killall -15  wpa_supplicant
hciconfig hci0 leadv
````

### `/lib/libswresample.so`

````text
--prefix=/home/build/android6_maintance/daily_build/external/ffmpeg/prefix --arch=arm --target-os=linux --enable-cross-compile --cross-prefix=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi- --cc=/home/build/android6_maintance/daily_build/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-gcc --sysroot=/home/build/android6_maintance/daily_build/prebuilts/ndk/current/platforms/android-18/arch-arm --enable-gpl --enable-shared --disable-static --extra-cflags='-mtune=cortex-a7 -march=armv7-a -mfloat-abi=softfp -mfpu=neon -D_GNU_SOURCE -fno-builtin-sin -fno-builtin-cos -std=c99 -D_USE_ANDROID_LOGGER' --extra-ldflags='-Wl,--fix-cortex-a8 -llog' --disable-everything --disable-doc --enable-decoder=h264 --enable-decoder=hevc --enable-parser=h264 --enable-decoder=hevc --enable-parser=hevc --enable-decoder=aac --enable-muxer=mpeg2video --enable-encoder=mpeg2video --enable-muxer=mp4 --enable-muxer=mov --enable-demuxer=mov --enable-demuxer=prores --enable-demuxer=aac --enable-muxer=mjpeg --enable-encoder=mjpeg --enable-muxer=mpegts --enable-demuxer=mpegts --disable-demuxer=asf --enable-demuxer=h264 --enable-muxer=h264 --enable-demuxer=hevc --enable-muxer=hevc --disable-muxer=adts --disable-muxer=latm --disable-protocol=rtp --enable-protocol=file --enable-protocol=djiin2 --disable-devices --disable-swscale --disable-symver --enable-bsfs --enable-filter=amix --enable-filter=volume --enable-filter=aformat --enable-filter=aresample --disable-asm --enable-pic
?FFmpeg version db/eagle_ec1704-v10.00.24.00-20201227023203
````

### `/bin/debuggerd`

````text
debuggerd: Aug 26 2022 17:01:20
````

### `/bin/mxt-app`

````text
db/eagle_ec1704-v10.00.24.17-20210909165207
````

### `/bin/amt_test_cmd`

````text
````

### `/bin/analytics`

````text
````

### `/bin/atrace`

````text
````

### `/bin/audio`

````text
````

### `/bin/blkid`

````text
````

### `/bin/bodystate`

````text
````

### `/bin/boot_control`

````text
````

### `/bin/bootlogo`

````text
````

### `/bin/c2d_ut`

````text
````

### `/bin/camservice`

````text
````

### `/bin/coremark`

````text
````

### `/bin/dbus-daemon`

````text
````

### `/bin/dbus-send`

````text
````

### `/bin/dbus-watcher`

````text
````

### `/bin/dhcpcd`

````text
````

### `/bin/dhcptool`

````text
````

## Scripts & Config

共 3 个脚本/配置变更, 158 行 unified diff（context=3, 预算上限 2000 行）。

### `/bin/fixup_hbmanual_partition.sh`

80 行

````diff
--- a//bin/fixup_hbmanual_partition.sh
+++ b//bin/fixup_hbmanual_partition.sh
@@ -7,30 +7,46 @@
 PROD_TYPE_CFV=14
 PROD_TYPE=`getprop dji.prod_type`
 
-function remove_non_matched_manuals()
+function install_manuals()
 {
     local DIR=$1
+    local PACK=$2
 
-    #Remove all PDF that does not match the expression
+    if [ ! -f $PACK ]; then
+        echo "Manual pack $PACK not found. Aborting update of hbmanual partition."
+        return 1
+    fi
+
+    # Get camera type. The resulting string must match the directory structure of hbmanual_pack.tar
     if [ $PROD_TYPE = $PROD_TYPE_X1DM2 ]; then
-        find $DIR -type f -not -name "X1D*.pdf" -print0 | xargs -0 rm -f
+        CAMERA="X1DII"
     elif [ $PROD_TYPE = $PROD_TYPE_CFV ]; then
-        find $DIR -type f -not -name "CFV*.pdf" -not -name "907X*.pdf" -print0 | xargs -0 rm -f
+        SU_VARIANT=$(unrd su_variant)
+        if [ $SU_VARIANT = "1" ]; then
+            CAMERA="907XAE80"
+        else
+            CAMERA="907X"
+        fi
     else
         echo "unknown product type ${PROD_TYPE}"
         return 1
     fi
 
-    return 0
+    # Replace manuals
+    rm -f $DIR/*.pdf
+    tar xvf $PACK -C $DIR ./$CAMERA
+    mv $DIR/$CAMERA/* $DIR
+    rmdir "$DIR/$CAMERA"
 }
 
 function fixup_hbmanual()
 {
+    HBMANUAL_PACK="$1"
     MOUNT_HB_MANUAL=$(mount | grep hbmanual | awk '{print $2}')
 
     if [ -d "$MOUNT_HB_MANUAL" ]; then
         mount -o remount,rw $MOUNT_HB_MANUAL
-        remove_non_matched_manuals $MOUNT_HB_MANUAL
+        install_manuals $MOUNT_HB_MANUAL $HBMANUAL_PACK
         mount -o remount,ro $MOUNT_HB_MANUAL
         return $?
     fi
@@ -49,7 +65,7 @@
         return 1
     fi
 
-    remove_non_matched_manuals $MOUNT_HB_MANUAL
+    install_manuals $MOUNT_HB_MANUAL $HBMANUAL_PACK
     RET=$?
 
     umount $MOUNT_HB_MANUAL
@@ -58,8 +74,14 @@
     return $RET
 }
 
+echo "args: $#"
+if [ $# -lt 1 ]; then
+    echo "usage: $(basename $0) <path/to/hbmanual_pack.tar>"
+    exit 1
+fi
+
 for retry in $(seq 5); do
-    fixup_hbmanual
+    fixup_hbmanual "$1"
     RET=$?
     if [ $RET == 0 ]; then
         break
````

### `/bin/test_eagle_fpga_mipi_link.sh`

68 行

````diff
--- a//bin/test_eagle_fpga_mipi_link.sh
+++ b//bin/test_eagle_fpga_mipi_link.sh
@@ -7,13 +7,6 @@
 #!/bin/bash
 prepare()
 {
-	# Use e-shutter to avoid any lens dependencies
-	odindb-send -s camera -p eshutter_current true
-	if [ $? != 0 ]; then
-		echo "Enable e-shutter failed"
-		return 3
-	fi
-
 	#stop gui
 	setprop ctl.stop gui
 	if [ $? != 0 ]; then
@@ -21,27 +14,19 @@
 		return 1
 	fi
 
-	#stop camera daemon
-	setprop ctl.stop camera_daemon
-	if [ $? != 0 ]; then
-		echo "stop camera_daemon fail"
-		return 2
-	fi
-
-	#stop storage daemon
-	setprop ctl.stop storage_daemon
-	if [ $? != 0 ]; then
-		echo "stop storage_daemon fail"
-		return 2
-	fi
-
-	#stop dji_camera2 (camera service)
+	#stop dji_camera2
 	setprop ctl.stop dji_camera2
 	if [ $? != 0 ]; then
 		echo "stop dji_camera2 fail"
 		return 2
 	fi
 
+	# Use e-shutter to avoid any lens dependencies
+	odindb-send -s camera -p eshutter_current true
+	if [ $? != 0 ]; then
+		echo "Enable e-shutter failed"
+		return 3
+	fi
 }
 
 restore()
@@ -50,16 +35,6 @@
 	if [ $? != 0 ]; then
 		echo "start dji_camera2 fail"
 		return 3
-	fi
-	setprop ctl.start storage_daemon
-	if [ $? != 0 ]; then
-		echo "start storage_daemon fail"
-		return 4
-	fi
-	setprop ctl.start camera_daemon
-	if [ $? != 0 ]; then
-		echo "start camera_daemon fail"
-		return 4
 	fi
 	setprop ctl.start gui
 	if [ $? != 0 ]; then
````

### `/build.prop`

10 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,4 +1,4 @@
 
-ro.vendor.build.date=Wed Oct 21 21:54:03 CST 2020
-ro.vendor.build.date.utc=1603288443
-ro.vendor.build.fingerprint=eagle/full_eagle_ec1704/eagle_ec1704:6.0/MDB08M/1925:userdebug/test-keys
+ro.vendor.build.date=Fri Aug 26 17:26:57 CST 2022
+ro.vendor.build.date.utc=1661506017
+ro.vendor.build.fingerprint=eagle/full_eagle_ec1704/eagle_ec1704:6.0/MDB08M/2111:userdebug/test-keys
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（904 行）</summary>

| Path | Status | Old Size | New Size | Δ | Tree |
|---|---|---|---|---|---|
| `/bin/Btdiag` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54.2 KB | 54.2 KB | +0 B | system |
| `/bin/adb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 419.6 KB | 419.6 KB | +0 B | system |
| `/bin/af.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 296 B | 296 B | +0 B | system |
| `/bin/aging_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.5 KB | 27.5 KB | +0 B | system |
| `/bin/amt_test_cmd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/analytics` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.6 KB | 81.6 KB | +0 B | system |
| `/bin/atrace` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.7 KB | 29.7 KB | +0 B | system |
| `/bin/audio` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.6 KB | 61.6 KB | +0 B | system |
| `/bin/blkid` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/bodystate` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 217.7 KB | 217.7 KB | +0 B | system |
| `/bin/boot_control` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 182.0 KB | 182.0 KB | +0 B | system |
| `/bin/bootlogo` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 146.0 KB | 146.0 KB | +0 B | system |
| `/bin/brdver_ddrtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_hwrev.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_prodtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 386 B | 386 B | +0 B | system |
| `/bin/btconfig` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74.6 KB | 74.6 KB | +0 B | system |
| `/bin/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.7 KB | 6.7 KB | +0 B | system |
| `/bin/c2d_ut` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.7 KB | 33.7 KB | +0 B | system |
| `/bin/cam_log_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/camera` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 661.6 KB | 661.6 KB | +0 B | system |
| `/bin/camera_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/camservice` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | system |
| `/bin/capture-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 153 B | 153 B | +0 B | system |
| `/bin/capture.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 363 B | 363 B | +0 B | system |
| `/bin/charge_interrupt_test_module.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 943 B | 943 B | +0 B | system |
| `/bin/check_blackbox.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 580 B | 580 B | +0 B | system |
| `/bin/check_sdcard_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 515 B | 515 B | +0 B | system |
| `/bin/check_system_status.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 706 B | 706 B | +0 B | system |
| `/bin/collect_useful_log.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | system |
| `/bin/comp_build_version.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525 B | 525 B | +0 B | system |
| `/bin/configstore` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 293.6 KB | 297.6 KB | +4.0 KB | system |
| `/bin/coremark` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/cs47l35-dmic-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 363 B | 363 B | +0 B | system |
| `/bin/cs47l35-hpout-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93 B | 93 B | +0 B | system |
| `/bin/cs47l35-mic-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 111 B | 111 B | +0 B | system |
| `/bin/cs47l35-spk-config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 76 B | 76 B | +0 B | system |
| `/bin/cs_check_system_state.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | system |
| `/bin/dbus-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 157.7 KB | 157.7 KB | +0 B | system |
| `/bin/dbus-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/dbus-watcher` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/debuggerd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/dhcpcd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 73.7 KB | 73.7 KB | +0 B | system |
| `/bin/dhcptool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_amt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.2 KB | 39.2 KB | +0 B | system |
| `/bin/dji_bb_spliter` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_blackbox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 35.0 KB | 35.0 KB | +0 B | system |
| `/bin/dji_cam_f2f.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.0 KB | 7.0 KB | +0 B | system |
| `/bin/dji_cht` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 95.7 KB | 95.7 KB | +0 B | system |
| `/bin/dji_close_suspend_powerdown.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 585 B | 585 B | +0 B | system |
| `/bin/dji_codec_aging.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/dji_crashdump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | system |
| `/bin/dji_cspp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 57.8 KB | 57.8 KB | +0 B | system |
| `/bin/dji_dsp_load` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.7 KB | 17.7 KB | +0 B | system |
| `/bin/dji_ec1704_camera_aging_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.5 KB | 13.5 KB | +0 B | system |
| `/bin/dji_ftpd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 38.1 KB | 38.1 KB | +0 B | system |
| `/bin/dji_fw_load` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_fw_verify` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_gdc_test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/dji_iosconn` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.7 KB | 37.7 KB | +0 B | system |
| `/bin/dji_kmsg` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_log_encrypt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.9 KB | 21.9 KB | +0 B | system |
| `/bin/dji_mb_ctrl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_mb_parser` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/dji_monitor` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/dji_open_suspend_powerdown.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 583 B | 583 B | +0 B | system |
| `/bin/dji_pbt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.7 KB | 41.7 KB | +0 B | system |
| `/bin/dji_ppt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 207.0 KB | 207.0 KB | +0 B | system |
| `/bin/dji_quick_charge` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/dji_rcam` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/dji_setup_uart.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 355 B | 355 B | +0 B | system |
| `/bin/dji_sn_ops.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 479 B | 479 B | +0 B | system |
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 376.6 KB | 376.6 KB | +0 B | system |
| `/bin/dji_system_complete.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/dji_tombstone.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/dji_verify` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.4 KB | 29.4 KB | +0 B | system |
| `/bin/dji_vtwo_sdk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/dji_wms` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 308.6 KB | 308.6 KB | +0 B | system |
| `/bin/dji_wms-v1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 220.6 KB | 220.6 KB | +0 B | system |
| `/bin/dumpstate` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.6 KB | 53.6 KB | +0 B | system |
| `/bin/dvfs-capture-freq.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 479 B | 479 B | +0 B | system |
| `/bin/dvfs-userspace-random.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/dvfs-userspace-switch.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/e2fsck` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 159.2 KB | 159.2 KB | +0 B | system |
| `/bin/eagle_ddr_stress_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/eagle_rpmb_inject.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45 B | 45 B | +0 B | system |
| `/bin/eagle_state_pro.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,003 B | 1,003 B | +0 B | system |
| `/bin/ec1702_configure_touch.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/eeprom_rw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/encrypt_and_export_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/erase_bootloader.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 151.2 KB | 151.2 KB | +0 B | system |
| `/bin/exposure_test_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/bin/fixup_hbmanual_partition.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 KB | 2.1 KB | +467 B | system |
| `/bin/flash_erase` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 198.0 KB | 198.0 KB | +0 B | system |
| `/bin/fpga_ddr_stress_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/frame_cap` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.7 KB | 25.7 KB | +0 B | system |
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
| `/bin/gpsd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.6 KB | 61.6 KB | +0 B | system |
| `/bin/gzip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/hard_restart.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 98 B | 98 B | +0 B | system |
| `/bin/hbl-collect-logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/hbl-configure-audio-sink.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/hbl-configure-audio-source.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/hciattach` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 63.0 KB | 63.0 KB | +0 B | system |
| `/bin/hex-writer` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.6 KB | 53.6 KB | +0 B | system |
| `/bin/hostapd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 535.3 KB | 535.3 KB | +0 B | system |
| `/bin/hostapd_cli` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.7 KB | 49.7 KB | +0 B | system |
| `/bin/hwshare` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 153.6 KB | 153.6 KB | +0 B | system |
| `/bin/i2cget` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.3 KB | 13.3 KB | +0 B | system |
| `/bin/i2cset` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.3 KB | 13.3 KB | +0 B | system |
| `/bin/imgjpegenc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/insert_tp_mod.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 817 B | 817 B | +0 B | system |
| `/bin/insmod_ko.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 193 B | 193 B | +0 B | system |
| `/bin/ion_falloc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/iozone` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 290.9 KB | 290.9 KB | +0 B | system |
| `/bin/ip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 169.9 KB | 169.9 KB | +0 B | system |
| `/bin/iperf3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.3 KB | 70.3 KB | +0 B | system |
| `/bin/iw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 157.1 KB | 157.1 KB | +0 B | system |
| `/bin/keystore_cli` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/lib_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.8 KB | 7.8 KB | +0 B | system |
| `/bin/lib_test_cases.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.5 KB | 8.5 KB | +0 B | system |
| `/bin/lib_test_stress.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/lib_test_utils.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/linker` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 184.5 KB | 184.5 KB | +0 B | system |
| `/bin/logcat` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/logd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.7 KB | 49.7 KB | +0 B | system |
| `/bin/logpersist.start` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 898 B | 898 B | +0 B | system |
| `/bin/logwrapper` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/lv_dump_disable.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/lv_dump_enable.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/metadata` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.6 KB | 81.6 KB | +0 B | system |
| `/bin/mkexfat` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 27.3 KB | 27.3 KB | +0 B | system |
| `/bin/mmc_utils` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.8 KB | 29.8 KB | +0 B | system |
| `/bin/monkey_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 681.6 KB | 681.6 KB | +0 B | system |
| `/bin/msg2dbus-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/mxt-app` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 82.5 KB | 82.5 KB | +0 B | system |
| `/bin/myftm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 87.2 KB | 87.2 KB | +0 B | system |
| `/bin/odin-output` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/odindb-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +8.0 KB | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 915.2 KB | 915.2 KB | +0 B | system |
| `/bin/periodic_sync.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59 B | 59 B | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1,021.7 KB | 1.0 MB | +48.0 KB | system |
| `/bin/pl_spi` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/play-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165 B | 165 B | +0 B | system |
| `/bin/play-hdmi.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 165 B | 165 B | +0 B | system |
| `/bin/playcap-cs47l35.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 242 B | 242 B | +0 B | system |
| `/bin/pngtest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/bin/preview` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 281.9 KB | 281.9 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.6 KB | 125.6 KB | +0 B | system |
| `/bin/prodconfig-tool.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | system |
| `/bin/productiontest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/bin/program_nodes.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/proresenc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/qcmbr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.9 KB | 29.9 KB | +0 B | system |
| `/bin/r` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/rcam_agent` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.0 KB | 22.0 KB | +0 B | system |
| `/bin/reboot` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/recovery_update.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | system |
| `/bin/returnstatus_defines.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 739 B | 739 B | +0 B | system |
| `/bin/returnstatus_suc_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 614 B | 614 B | +0 B | system |
| `/bin/returnstatus_to_string.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 987 B | 987 B | +0 B | system |
| `/bin/sd_helpers.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/send_fw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/service` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/servicemanager` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.7 KB | 17.7 KB | +0 B | system |
| `/bin/set_sd_autosuspend.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 869 B | 869 B | +0 B | system |
| `/bin/set_test_result.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237 B | 237 B | +0 B | system |
| `/bin/setup_aging_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 723 B | 723 B | +0 B | system |
| `/bin/setup_cam_env.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 319 B | 319 B | +0 B | system |
| `/bin/setup_factory_rw.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 578 B | 578 B | +0 B | system |
| `/bin/setup_product_props.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 778 B | 778 B | +0 B | system |
| `/bin/setup_usb.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 343 B | 343 B | +0 B | system |
| `/bin/setup_usb_serial.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 544 B | 544 B | +0 B | system |
| `/bin/sgdisk` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 109.7 KB | 109.7 KB | +0 B | system |
| `/bin/sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 166.0 KB | 166.0 KB | +0 B | system |
| `/bin/showlease` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/start_audio_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | system |
| `/bin/start_blackbox_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/start_bodystate.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/bin/start_bootlogo.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 401 B | 401 B | +0 B | system |
| `/bin/start_camera_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_compositor.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_configstore.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | system |
| `/bin/start_dji_camera.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 247 B | 247 B | +0 B | system |
| `/bin/start_dji_mount_filesystem.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/start_dji_system.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/start_ftp_server.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 430 B | 430 B | +0 B | system |
| `/bin/start_gpsd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 356 B | 356 B | +0 B | system |
| `/bin/start_gui.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66 B | 66 B | +0 B | system |
| `/bin/start_high_consump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/bin/start_hwshare.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48 B | 48 B | +0 B | system |
| `/bin/start_metadata_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | system |
| `/bin/start_msg2dbus.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 445 B | 445 B | +0 B | system |
| `/bin/start_preview_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | system |
| `/bin/start_storage_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | system |
| `/bin/start_sutestgui.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 75 B | 75 B | +0 B | system |
| `/bin/start_sysman.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | system |
| `/bin/start_upgrade_daemon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/bin/stm32flash` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 42.0 KB | 42.0 KB | +0 B | system |
| `/bin/stop_high_consump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 912 B | 912 B | +0 B | system |
| `/bin/storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | -372 B | system |
| `/bin/support_audio_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | system |
| `/bin/sutest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 429.6 KB | 429.6 KB | +0 B | system |
| `/bin/switch_autotest.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 302 B | 302 B | +0 B | system |
| `/bin/sync_time.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | system |
| `/bin/sysman` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 377.6 KB | 377.6 KB | +0 B | system |
| `/bin/tee-supplicant` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/bin/tee_helloworld` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/bin/test_STMems_sensors` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.7 KB | 13.7 KB | +0 B | system |
| `/bin/test_acce_gyro_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 699 B | 699 B | +0 B | system |
| `/bin/test_ae_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_af_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_af_led_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 672 B | 672 B | +0 B | system |
| `/bin/test_af_mf_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_ambient_light_sensor.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_audio` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 30.0 KB | 30.0 KB | +0 B | system |
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
| `/bin/test_c2d` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.8 KB | 25.8 KB | +0 B | system |
| `/bin/test_camera_setting_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_charge_or_interrupt_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 662 B | 662 B | +0 B | system |
| `/bin/test_charge_or_interrupt_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_cpld_flash_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/bin/test_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 568 B | 568 B | +0 B | system |
| `/bin/test_delete_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_disp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 42.4 KB | 42.4 KB | +0 B | system |
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
| `/bin/test_dsp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 186.9 KB | 186.9 KB | +0 B | system |
| `/bin/test_dsp_load.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 746 B | 746 B | +0 B | system |
| `/bin/test_eagle_bt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 471 B | 471 B | +0 B | system |
| `/bin/test_eagle_fpga_mipi_link.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 KB | 1.2 KB | -479 B | system |
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
| `/bin/test_flight_lite` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.7 KB | 17.7 KB | +0 B | system |
| `/bin/test_fpga_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_fpga_emmc_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 870 B | 870 B | +0 B | system |
| `/bin/test_front_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | system |
| `/bin/test_gps` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/test_gps.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/test_gps_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_hal_plenc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/test_hal_storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/test_hdmi_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_headphone_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_hotshoe_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 521 B | 521 B | +0 B | system |
| `/bin/test_i2c` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/test_imgtec_ienc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/test_imgtec_vdec` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.7 KB | 25.7 KB | +0 B | system |
| `/bin/test_imgtec_venc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.8 KB | 45.8 KB | +0 B | system |
| `/bin/test_imgtec_venc_new` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 57.8 KB | 57.8 KB | +0 B | system |
| `/bin/test_internal_speaker.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 942 B | 942 B | +0 B | system |
| `/bin/test_iso_wb_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_lcd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.1 KB | 26.1 KB | +0 B | system |
| `/bin/test_lcd_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | system |
| `/bin/test_lcd_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/test_lens_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_lens_detect.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 345 B | 345 B | +0 B | system |
| `/bin/test_lens_if_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 617 B | 617 B | +0 B | system |
| `/bin/test_lens_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | system |
| `/bin/test_main_board_power.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | system |
| `/bin/test_mem` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
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
| `/bin/test_playback` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/test_pmic_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 926 B | 926 B | +0 B | system |
| `/bin/test_power_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/bin/test_proximity_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/test_qc_flow_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/bin/test_releasebar_calibrate_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 299 B | 299 B | +0 B | system |
| `/bin/test_releasebar_calibrate_stop.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 298 B | 298 B | +0 B | system |
| `/bin/test_releasebar_check.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 578 B | 578 B | +0 B | system |
| `/bin/test_releasebar_start.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 375 B | 375 B | +0 B | system |
| `/bin/test_rtc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
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
| `/bin/test_spi` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
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
| `/bin/test_v2d` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.8 KB | 21.8 KB | +0 B | system |
| `/bin/test_vdev` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.7 KB | 39.7 KB | +0 B | system |
| `/bin/test_video_setting_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | system |
| `/bin/test_voltage_level.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | system |
| `/bin/test_wl_venc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.8 KB | 17.8 KB | +0 B | system |
| `/bin/time_elapsed_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 319 B | 319 B | +0 B | system |
| `/bin/tinycap` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tinymix` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tinypcminfo` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tinyplay` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/toolbox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 95.1 KB | 95.1 KB | +0 B | system |
| `/bin/toybox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 248.4 KB | 248.4 KB | +0 B | system |
| `/bin/tracepath` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/tracepath6` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/traceroute6` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/bin/unrd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/update_engine` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 523.4 KB | 523.4 KB | +0 B | system |
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
| `/bin/upgraded` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 345.6 KB | 345.6 KB | +0 B | system |
| `/bin/usbd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 161.9 KB | 161.9 KB | +0 B | system |
| `/bin/valgrind` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/bin/vdec_test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/bin/victory-gui-static` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.2 MB | 21.2 MB | +60.0 KB | system |
| `/bin/vinput` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/bin/vinput2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/vinput_daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 18.0 KB | 18.0 KB | +0 B | system |
| `/bin/vinput_monkey_lib.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.3 KB | 22.3 KB | +0 B | system |
| `/bin/vinput_monkey_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 KB | 5.3 KB | +0 B | system |
| `/bin/vold` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 370.0 KB | 370.0 KB | +0 B | system |
| `/bin/vold-uhs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/vxe_testbench` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 745.0 KB | 749.0 KB | +4.0 KB | system |
| `/bin/wait_for_key.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/weston` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/bin/wifi_bt_init_env.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/wifi_bt_test_cmd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.7 KB | 14.7 KB | +0 B | system |
| `/bin/wifi_profiled_debug.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | system |
| `/bin/wpa_cli` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 82.6 KB | 82.6 KB | +0 B | system |
| `/bin/wpa_supplicant` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | system |
| `/bin/write_udc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/bin/xtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/build.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 KB | 1.8 KB | +0 B | system/vendor |
| `/data/misc/wifi/wpa_p2p_supplicant.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/etc/NOTICE.html.gz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 87.9 KB | 87.9 KB | +0 B | system |
| `/etc/NOTICE.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 657.9 KB | 657.9 KB | +0 B | system |
| `/etc/VERSION` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6 B | 6 B | +0 B | system |
| `/etc/cht_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 211 B | 211 B | +0 B | system |
| `/etc/dbus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/dji.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117.0 KB | 117.0 KB | +0 B | system |
| `/etc/dji_camera.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.7 KB | 9.7 KB | +0 B | system |
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
| `/etc/firmware/rtnodes/BOOT.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 129.9 KB | 129.9 KB | +0 B | system |
| `/etc/firmware/rtnodes/FARM.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | -4.0 KB | system |
| `/etc/firmware/rtnodes/FPGA.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 MB | 5.3 MB | +0 B | system |
| `/etc/firmware/rtnodes/app.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 MB | 8.4 MB | +31.8 KB | system |
| `/etc/firmware/rtnodes/bifrost_body.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.0 KB | 21.0 KB | +0 B | system |
| `/etc/firmware/rtnodes/bifrost_body_v1.2.8.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.0 KB | 21.0 KB | +0 B | system |
| `/etc/firmware/rtnodes/bifrost_grip.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.1 KB | 22.1 KB | +0 B | system |
| `/etc/firmware/rtnodes/bifrost_grip_v1.2.7.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.1 KB | 22.1 KB | +0 B | system |
| `/etc/firmware/rtnodes/cfv-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 266.0 KB | 269.8 KB | +3.8 KB | system |
| `/etc/firmware/rtnodes/cfv-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.6 MB | +29.3 KB | system |
| `/etc/firmware/rtnodes/fpga_all.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.8 MB | 6.8 MB | -4.0 KB | system |
| `/etc/firmware/rtnodes/fsbl.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 597.4 KB | 595.9 KB | -1.5 KB | system |
| `/etc/firmware/rtnodes/power-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.8 KB | 54.0 KB | +180 B | system |
| `/etc/firmware/rtnodes/power-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.3 MB | 1.3 MB | +7.0 KB | system |
| `/etc/firmware/rtnodes/system_wrapper.bit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 MB | 5.3 MB | +0 B | system |
| `/etc/firmware/rtnodes/xsystem-control.bin` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 246.4 KB | 251.0 KB | +4.6 KB | system |
| `/etc/firmware/rtnodes/xsystem-control.elf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.4 MB | 2.5 MB | +39.4 KB | system |
| `/etc/firmware/tpfw.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32.0 KB | 32.0 KB | +0 B | system |
| `/etc/firmware/utf30.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323.4 KB | 323.4 KB | +0 B | system |
| `/etc/firmware/wlan/cfg.dat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | system |
| `/etc/firmware/wlan/qcom_cfg.ini` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.8 KB | 15.8 KB | +0 B | system |
| `/etc/ftp.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | system |
| `/etc/hostapd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 343 B | 343 B | +0 B | system |
| `/etc/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56 B | 56 B | +0 B | system |
| `/etc/imx161f_ec1704.sp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.9 KB | 28.9 KB | +0 B | system |
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
| `/lib/hw/sensors.eagle.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | vendor |
| `/lib/libAACdec.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 245.9 KB | 245.9 KB | +0 B | system |
| `/lib/libAACenc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 285.6 KB | 285.6 KB | +0 B | system |
| `/lib/libAppsMessaging.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libLLVM.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.4 MB | 10.4 MB | +0 B | system |
| `/lib/libMessageTransport.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libQt5Concurrent.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.4 KB | 21.4 KB | +0 B | system |
| `/lib/libQt5Core.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.4 MB | 3.4 MB | +4.0 KB | system |
| `/lib/libQt5DBus.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 529.4 KB | 529.4 KB | +0 B | system |
| `/lib/libQt5Network.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 433.4 KB | 433.4 KB | +0 B | system |
| `/lib/libQt5Positioning.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 485.5 KB | 485.5 KB | +0 B | system |
| `/lib/libQt5SerialPort.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 81.3 KB | 81.3 KB | +0 B | system |
| `/lib/libQt5Sql.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237.4 KB | 237.4 KB | +0 B | system |
| `/lib/libQt5Xml.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 109.4 KB | 109.4 KB | +0 B | system |
| `/lib/libSystemCommon.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libVdecAppGST.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 109.3 KB | 109.3 KB | +0 B | system |
| `/lib/lib_camcomp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/lib/lib_eigen.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 85.6 KB | 85.6 KB | +0 B | system |
| `/lib/lib_hal_gdc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/lib_mdev.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/lib_mediactl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libadsb_util.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libamt_util.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.4 KB | 22.4 KB | +0 B | system |
| `/lib/libappscommon.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.0 MB | 2.0 MB | +8.0 KB | system |
| `/lib/libaudioutils.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libavcodec.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +0 B | system |
| `/lib/libavfilter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 130.5 KB | 130.5 KB | +0 B | system |
| `/lib/libavformat.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 358.8 KB | 358.8 KB | +0 B | system |
| `/lib/libavutil.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 297.4 KB | 297.4 KB | +0 B | system |
| `/lib/libbacktrace.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.6 KB | 37.6 KB | +0 B | system |
| `/lib/libbacktrace_test.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libbase.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.7 KB | 37.7 KB | +0 B | system |
| `/lib/libbinder.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 177.7 KB | 177.7 KB | +0 B | system |
| `/lib/libc++.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 561.7 KB | 561.7 KB | +0 B | system |
| `/lib/libc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 665.9 KB | 665.9 KB | +0 B | system |
| `/lib/libc_malloc_debug_leak.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 145.7 KB | 145.7 KB | +0 B | system |
| `/lib/libc_malloc_debug_qemu.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.5 KB | 25.5 KB | +0 B | system |
| `/lib/libcrypto.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 622.1 KB | 622.1 KB | +0 B | system |
| `/lib/libcutils.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.8 KB | 61.8 KB | +0 B | system |
| `/lib/libdbus.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 365.8 KB | 365.8 KB | +0 B | system |
| `/lib/libdcam_fcali.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 163.6 KB | 163.6 KB | +0 B | system |
| `/lib/libdcam_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +0 B | system |
| `/lib/libdcam_metadata.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 570.7 KB | 570.7 KB | +0 B | system |
| `/lib/libdiskconfig.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libdjishare.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 265.5 KB | 265.5 KB | +0 B | system |
| `/lib/libdl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.3 KB | 9.3 KB | +0 B | system |
| `/lib/libduml_audio.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 69.6 KB | 69.6 KB | +0 B | system |
| `/lib/libduml_ffremux.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libduml_frwk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 523.3 KB | 523.3 KB | +0 B | system |
| `/lib/libduml_hal.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 250.0 KB | 250.0 KB | +0 B | system |
| `/lib/libduml_hal_cam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 394.4 KB | 394.4 KB | +0 B | system |
| `/lib/libduml_media.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 94.1 KB | 94.1 KB | +0 B | system |
| `/lib/libduml_osal.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libduml_util.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.8 KB | 45.8 KB | +0 B | system |
| `/lib/libduml_watermark.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libevdev.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.5 KB | 49.5 KB | +0 B | system |
| `/lib/libewgfx.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.6 KB | 125.6 KB | +0 B | system |
| `/lib/libewgfx_watermark.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 165.6 KB | 165.6 KB | +0 B | system |
| `/lib/libewnativeadapter.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.7 KB | 29.7 KB | +0 B | system |
| `/lib/libewnativebackend_mb.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 85.7 KB | 85.7 KB | +0 B | system |
| `/lib/libewplatform.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 76.1 KB | 76.1 KB | +0 B | system |
| `/lib/libewrte.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.6 KB | 53.6 KB | +0 B | system |
| `/lib/libexfat.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libexpat.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 85.4 KB | 85.4 KB | +0 B | system |
| `/lib/libext2_blkid.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.9 KB | 39.9 KB | +0 B | system |
| `/lib/libext2_com_err.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libext2_e2p.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 30.4 KB | 30.4 KB | +0 B | system |
| `/lib/libext2_profile.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libext2_quota.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libext2_uuid.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libext2fs.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 170.1 KB | 170.1 KB | +0 B | system |
| `/lib/libext4_utils.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 73.6 KB | 73.6 KB | +0 B | system |
| `/lib/libf2fs_sparseblock.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libft2.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 377.6 KB | 377.6 KB | +0 B | system |
| `/lib/libfw_util.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libfw_util_ca.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libglib.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 590.3 KB | 590.3 KB | +0 B | system |
| `/lib/libhardware.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libhardware_legacy.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/lib/libhblupgrade.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libhelper_api_sa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 616.7 KB | 616.7 KB | +0 B | system |
| `/lib/libhyperlapse_eis.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 288.5 KB | 288.5 KB | +0 B | system |
| `/lib/libiconv.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 869.6 KB | 869.6 KB | +0 B | system |
| `/lib/libicui18n.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | system |
| `/lib/libicuuc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/libimgjpegenc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 35.6 KB | 35.6 KB | +0 B | system |
| `/lib/libion.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libiprouteutil.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 35.6 KB | 35.6 KB | +0 B | system |
| `/lib/libjnigraphics.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/lib/libjpeg.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 217.6 KB | 217.6 KB | +0 B | system |
| `/lib/libkeymaster1.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 101.8 KB | 101.8 KB | +0 B | system |
| `/lib/libkeymaster_messages.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.6 KB | 37.6 KB | +0 B | system |
| `/lib/libkeystore-engine.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libkeystore_binder.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.7 KB | 49.7 KB | +0 B | system |
| `/lib/liblog.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.7 KB | 33.7 KB | +0 B | system |
| `/lib/liblogwrap.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libm.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 129.8 KB | 129.8 KB | +0 B | system |
| `/lib/libmod_dji.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 514.2 KB | 514.2 KB | +0 B | system |
| `/lib/libmod_x1dm2.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/libnetlink.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libnetutils.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libnl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 75.7 KB | 75.7 KB | +0 B | system |
| `/lib/libomx_vxd.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +4.0 KB | system |
| `/lib/libopencv_java3.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.2 MB | 8.2 MB | +0 B | system |
| `/lib/libpagemap.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libpcre.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 73.6 KB | 73.6 KB | +0 B | system |
| `/lib/libplist.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 347.7 KB | 347.7 KB | +0 B | system |
| `/lib/libpng.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 157.6 KB | 157.6 KB | +0 B | system |
| `/lib/libpower.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.6 KB | 13.6 KB | +0 B | system |
| `/lib/libproresenc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 36.3 KB | 36.3 KB | +0 B | system |
| `/lib/libprotobuf-cpp-lite.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 97.7 KB | 97.7 KB | +0 B | system |
| `/lib/libreg_dump_api.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libselinux.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.7 KB | 61.7 KB | +0 B | system |
| `/lib/libservice.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 422.2 KB | 422.2 KB | +0 B | system |
| `/lib/libsharekit.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 MB | 2.2 MB | +0 B | system |
| `/lib/libsoftkeymaster.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/lib/libsoftkeymasterdevice.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 85.8 KB | 85.8 KB | +0 B | system |
| `/lib/libsparse.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.7 KB | 29.7 KB | +0 B | system |
| `/lib/libspeexresampler.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 31.0 KB | 31.0 KB | +0 B | system |
| `/lib/libsqlite.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 401.2 KB | 401.2 KB | +0 B | system |
| `/lib/libssl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 145.5 KB | 145.5 KB | +0 B | system |
| `/lib/libstdc++.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.5 KB | 21.5 KB | +0 B | system |
| `/lib/libstlport.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 237.7 KB | 237.7 KB | +0 B | system |
| `/lib/libswresample.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 69.4 KB | 69.4 KB | +0 B | system |
| `/lib/libsysutils.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libteec.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/lib/libtinyalsa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | system |
| `/lib/libunrd.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libunwind.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 65.6 KB | 65.6 KB | +0 B | system |
| `/lib/libusb.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.6 KB | 41.6 KB | +0 B | system |
| `/lib/libusbmuxd.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.6 KB | 29.6 KB | +0 B | system |
| `/lib/libutils.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 101.7 KB | 101.7 KB | +0 B | system |
| `/lib/libv2_sdk.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.7 KB | 81.7 KB | +0 B | system |
| `/lib/libwayland-client.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.9 KB | 41.9 KB | +0 B | system |
| `/lib/libwayland-cursor.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | system |
| `/lib/libwayland-server.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 54.0 KB | 54.0 KB | +0 B | system |
| `/lib/libweston.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 858.5 KB | 858.5 KB | +0 B | system |
| `/lib/libwm_blender_256x64.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 97.6 KB | 97.6 KB | +0 B | system |
| `/lib/libwpa_client.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/lib/libxkbcommon.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 197.6 KB | 197.6 KB | +0 B | system |
| `/lib/libxml2.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 872.2 KB | 872.2 KB | +0 B | system |
| `/lib/libz.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 105.7 KB | 105.7 KB | +0 B | system |
| `/lib/modules/atmel_mxt_ts.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 195.6 KB | 195.6 KB | +32 B | system |
| `/lib/modules/designware_i2s.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 186.7 KB | 186.7 KB | +28 B | system |
| `/lib/modules/dji-spinor.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 136.3 KB | 136.3 KB | +32 B | system |
| `/lib/modules/dji_csi_host.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 266.0 KB | 266.1 KB | +180 B | system |
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 210.1 KB | 210.2 KB | +28 B | system |
| `/lib/modules/dji_v2d.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 150.8 KB | 150.8 KB | +32 B | system |
| `/lib/modules/e1000e.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +180 B | system |
| `/lib/modules/e5010_mod.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 143.7 KB | 143.7 KB | +32 B | system |
| `/lib/modules/eagle_dsp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 290.8 KB | 290.9 KB | +76 B | system |
| `/lib/modules/echainiv.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 128.6 KB | 128.6 KB | +28 B | system |
| `/lib/modules/ecx337aa.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 143.1 KB | 143.1 KB | +28 B | system |
| `/lib/modules/gdc_eagle.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 154.9 KB | 155.0 KB | +88 B | system |
| `/lib/modules/gpio_keys.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 147.1 KB | 147.1 KB | +32 B | system |
| `/lib/modules/gspca_main.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 370.7 KB | 370.8 KB | +48 B | system |
| `/lib/modules/himax_tp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 684.3 KB | 684.4 KB | +76 B | system |
| `/lib/modules/icc_chnl.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 386.0 KB | 386.6 KB | +648 B | system |
| `/lib/modules/ili2120.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 130.0 KB | 130.0 KB | +32 B | system |
| `/lib/modules/imgtec/encoder_fw.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93.2 KB | 93.2 KB | +0 B | system |
| `/lib/modules/imgtec/img_mem.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 737.5 KB | 738.3 KB | +780 B | system |
| `/lib/modules/imgtec/imgvideo.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +5.5 KB | system |
| `/lib/modules/imgtec/pvdec_full_bin.fw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 244.2 KB | 244.2 KB | +0 B | system |
| `/lib/modules/imgtec/vxd.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 792.5 KB | 793.0 KB | +528 B | system |
| `/lib/modules/imgtec/vxekm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 836.5 KB | 837.9 KB | +1.4 KB | system |
| `/lib/modules/irq-madera-cs47l35.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 38.8 KB | 38.9 KB | +28 B | system |
| `/lib/modules/irq-madera.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 116.5 KB | 116.5 KB | +32 B | system |
| `/lib/modules/l3ej03110a.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 144.0 KB | 144.1 KB | +32 B | system |
| `/lib/modules/leds-pca963x.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.8 KB | 125.8 KB | +28 B | system |
| `/lib/modules/ledtrig-oneshot.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.4 KB | 89.4 KB | +32 B | system |
| `/lib/modules/madera-i2c.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 119.0 KB | 119.0 KB | +32 B | system |
| `/lib/modules/mmc_test.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 238.8 KB | 238.8 KB | +28 B | system |
| `/lib/modules/proresenc_mod.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 152.2 KB | 152.3 KB | +28 B | system |
| `/lib/modules/rcam_dji.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 MB | 8.3 MB | +9.7 KB | system |
| `/lib/modules/regmap-spi.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 124.6 KB | 124.6 KB | +32 B | system |
| `/lib/modules/sfh7776.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 145.3 KB | 145.3 KB | +32 B | system |
| `/lib/modules/snd-compress.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 166.2 KB | 166.2 KB | +28 B | system |
| `/lib/modules/snd-pcm-dmaengine.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 145.0 KB | 145.0 KB | +32 B | system |
| `/lib/modules/snd-pcm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +148 B | system |
| `/lib/modules/snd-soc-core.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +192 B | system |
| `/lib/modules/snd-soc-cs47l35.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 967.0 KB | 967.0 KB | +32 B | system |
| `/lib/modules/snd-soc-ics43434.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 147.8 KB | 147.9 KB | +32 B | system |
| `/lib/modules/snd-soc-madera.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 318.5 KB | 318.6 KB | +32 B | system |
| `/lib/modules/snd-soc-simple-card.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 185.8 KB | 185.9 KB | +32 B | system |
| `/lib/modules/snd-soc-tfa9890.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 180.7 KB | 180.7 KB | +28 B | system |
| `/lib/modules/snd-soc-tlv320aic31xx.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 209.8 KB | 209.8 KB | +32 B | system |
| `/lib/modules/snd-soc-wm-adsp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 260.7 KB | 260.7 KB | +28 B | system |
| `/lib/modules/snd.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 844.8 KB | 844.9 KB | +136 B | system |
| `/lib/modules/soundcore.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 105.2 KB | 105.2 KB | +32 B | system |
| `/lib/modules/tc358749.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 289.5 KB | 289.6 KB | +32 B | system |
| `/lib/modules/uinput.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 154.4 KB | 154.4 KB | +28 B | system |
| `/lib/modules/vision_acc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 952.1 KB | 952.3 KB | +168 B | system |
| `/lib/modules/wlan.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.1 MB | 4.1 MB | +1.2 KB | system |
| `/lib/qt/lib/fonts/DroidSansFallback.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 MB | 2.9 MB | +0 B | system |
| `/lib/qt/lib/fonts/DroidSansJapanese.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue-Bold.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 470.2 KB | 470.2 KB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue-Light.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 208.8 KB | 208.8 KB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue-Medium.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 185.7 KB | 185.7 KB | +0 B | system |
| `/lib/qt/lib/fonts/HelveticaNeue.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 464.3 KB | 464.3 KB | +0 B | system |
| `/lib/qt/plugins/position/libgpsplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.5 KB | 61.5 KB | +0 B | system |
| `/lib/qt/plugins/position/libqtposition_positionpoll.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.4 KB | 41.4 KB | +0 B | system |
| `/lib/qt/plugins/sqldrivers/libqsqlite.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 893.0 KB | 893.0 KB | +0 B | system |
| `/lib/weston/eagle-backend.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 402.5 KB | 600.3 KB | +197.9 KB | system |
| `/lib/weston/eagle-shell.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.5 KB | 33.5 KB | +0 B | system |
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.6 MB | 15.6 MB | +1.0 KB | system |
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
| `/xbin/add-property-tag` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 182.0 KB | 182.0 KB | +0 B | system |
| `/xbin/avdtptest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 66.3 KB | 66.3 KB | +0 B | system |
| `/xbin/avinfo` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/xbin/avtest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.8 KB | 21.8 KB | +0 B | system |
| `/xbin/bneptest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 50.0 KB | 50.0 KB | +0 B | system |
| `/xbin/btmgmt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 111.9 KB | 111.9 KB | +0 B | system |
| `/xbin/btmon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 361.7 KB | 361.7 KB | +0 B | system |
| `/xbin/btproxy` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.7 KB | 25.7 KB | +0 B | system |
| `/xbin/busybox` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 MB | 1.9 MB | +0 B | system |
| `/xbin/check-lost+found` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 194.0 KB | 194.0 KB | +0 B | system |
| `/xbin/cpustats` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/dbus-monitor` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.6 KB | 21.6 KB | +0 B | system |
| `/xbin/haltest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 129.2 KB | 129.2 KB | +0 B | system |
| `/xbin/hciconfig` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 120.6 KB | 120.6 KB | +0 B | system |
| `/xbin/hcitool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.3 KB | 88.3 KB | +0 B | system |
| `/xbin/ksminfo` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/l2ping` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | system |
| `/xbin/l2test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.7 KB | 45.7 KB | +0 B | system |
| `/xbin/latencytop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/librank` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.8 KB | 17.8 KB | +0 B | system |
| `/xbin/mcaptest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 62.2 KB | 62.2 KB | +0 B | system |
| `/xbin/micro_bench` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | system |
| `/xbin/micro_bench_static` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 194.2 KB | 194.2 KB | +0 B | system |
| `/xbin/perfprofd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 105.7 KB | 105.7 KB | +0 B | system |
| `/xbin/procmem` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/procrank` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/puncture_fs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/rawbu` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.6 KB | 25.6 KB | +0 B | system |
| `/xbin/rctest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.6 KB | 45.6 KB | +0 B | system |
| `/xbin/sane_schedstat` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/showmap` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/showslab` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/simpleperf` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.6 KB | 125.6 KB | +0 B | system |
| `/xbin/sqlite3` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 65.3 KB | 65.3 KB | +0 B | system |
| `/xbin/strace` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 277.8 KB | 277.8 KB | +0 B | system |
| `/xbin/su` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | system |
| `/xbin/taskstats` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.7 KB | 21.7 KB | +0 B | system |
| `/xbin/tcpdump` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 810.6 KB | 810.6 KB | +0 B | system |
</details>
