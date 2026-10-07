# H6D-50c: 1.16.0 ➜ 1.17.0

> 生成时间: 2026-10-07T23:22:46 · CIM 日期: 2017-04-12 ➜ 2017-06-29 · 条目: 4 ➜ 4 · 源: `H6D_v1_16_0.cim` ➜ `H6D_v1_17_0.cim`

## Summary

文件树 +80/-107/~372；CIM 条目 +0/-0/~2；OTA 镜像 ~0 变更 / 0 未变；符号 +156/-99 funcs, +32/-17 objs；新增字符串 4394 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `hbl-kks-revisions` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.7 KB | 6.8 KB | +66 B |
| `rootfs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 63.5 MB | 56.2 MB | -7.4 MB |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B |
| `uboot` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263.0 KB | 263.0 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 2 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 2

## OTA Images

共 0 个条目, 无增删改。

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `usr` | 0 | 27 | 262 | 1485 | 0 |
| `lib` | 79 | 78 | 63 | 189 | 0 |
| `bin` | 0 | 0 | 17 | 0 | 0 |
| `etc` | 0 | 1 | 13 | 105 | 0 |
| `sbin` | 0 | 0 | 12 | 2 | 0 |
| `boot` | 1 | 1 | 3 | 0 | 0 |
| `var` | 0 | 0 | 2 | 2 | 0 |

明细 2342 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+156 / −99** functions, **+32 / −17** objects（50 个变更 ELF, 另有 297 个未列出）。

### `/usr/lib/libappscommon.so.1.0.0`

+67 / −35 functions · +4 / −0 objects

**New functions (67)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN3Bus12rawInterfaceEv` | 0x4b441788 | 20 |
| `_ZN3Bus7rawPathEv` | 0x4b44179c | 20 |
| `_ZN8CStorage13tagWhiteLevelEv` | 0x4b44879c | 20 |
| `_ZN8CStorage16propRawImageSizeEv` | 0x4b448954 | 20 |
| `_ZN8CStorage12hasCFastSlotEv` | 0x4b4489b8 | 476 |
| `_ZN8CStorage8isSdCardE16hblm_volume_type` | 0x4b448b94 | 44 |
| `_ZN8CStorage9slotIndexE16hblm_volume_type` | 0x4b448bc0 | 900 |
| `_ZN8CStorage21slotIndexToVolumeTypeEi` | 0x4b448f44 | 1312 |
| `_ZN8CStorage9totalSizeERK4QMapI7QString8QVariantE` | 0x4b449464 | 216 |
| `_ZN8CStorage16isWriteProtectedERK4QMapI7QString8QVariantE` | 0x4b44953c | 200 |
| `_ZN8CStorage9freeSpaceERK4QMapI7QString8QVariantE` | 0x4b449604 | 204 |
| `_ZN8CStorage13writableSpaceERK4QMapI7QString8QVariantE` | 0x4b4496d0 | 40 |
| `_ZN18SystemManagerProxy11collectLogsEv` | 0x4b44da8c | 200 |
| `_ZN10VideoProxy21setVideoPlaybackStateEbRK7QStringy` | 0x4b44f350 | 552 |
| `_ZN8SucProxy19enable_exposure_seqEb` | 0x4b450f98 | 252 |
| `_ZN5MData23whiteLevelToDigitalGainEj` | 0x4b45cb0c | 52 |
| `_ZN5MData23digitalGainToWhiteLevelEj` | 0x4b45cb40 | 4 |
| `_ZN11CameraProxy18setPendingLiveViewEb` | 0x4b460180 | 16 |
| `_ZN11CameraProxy16setLiveViewStateEb` | 0x4b4608ec | 140 |
| `_ZN12CamBodyProxy6exposeEi` | 0x4b464dc4 | 420 |
| `_ZN9FarmProxy12RequestImageERK7QStringijjjijjj` | 0x4b47590c | 704 |
| `_ZN9FarmProxy14itemTransferedERK7QString` | 0x4b476338 | 248 |
| `_ZN12StorageProxy20setCurrentWorkingDirERK7QString` | 0x4b478cc8 | 84 |
| `_ZN12StorageProxy6removeERK7QString` | 0x4b47937c | 248 |
| `_ZN12StorageProxy6formatE16hblm_volume_type` | 0x4b4797d4 | 248 |
| `_ZNK12StorageProxy9totalSizeE16hblm_volume_type` | 0x4b4799a4 | 1120 |
| `_ZNK12StorageProxy12writableSizeE16hblm_volume_type` | 0x4b479e04 | 992 |
| `_ZN13MetadataProxy15requestMetadataE18hblm_metadata_type9hblm_sinktjRK21hblm_image_dimensionsRK22hblm_xyz_to_rgb_matrixRK20hblm_as_shot_neutraljjjjjjjiRK13hblm_rationalRK23hblm_metadata_rectanglejj` | 0x4b481aac | 2580 |
| `_ZN8RawProxyC1EP7QObject` | 0x4b485b2c | 56 |
| `_ZN8RawProxyC2EP7QObject` | 0x4b485b2c | 56 |
| `_ZN8RawProxy10rawMessageERK7QStringRK10QByteArray` | 0x4b485b64 | 600 |
| `_ZN18SystemManagerProxy20tethered_modeChangedE18hblm_tethered_mode` | 0x4b486c4c | 76 |
| `_ZN18SystemManagerProxy18camera_modeChangedE16hblm_camera_mode` | 0x4b486c98 | 76 |
| `_ZN18SystemManagerProxy19system_stateChangedE17hblm_system_state` | 0x4b486ce4 | 76 |
| `_ZN18SystemManagerProxy20batteryStatusChangedEi` | 0x4b486d7c | 76 |
| `_ZN18SystemManagerProxy16versionIDChangedERK7QString` | 0x4b486dc8 | 68 |
| `_ZN18SystemManagerProxy19uiPowerStateChangedE16hblm_power_state` | 0x4b486e0c | 76 |
| `_ZN18SystemManagerProxy22collecting_logsChangedEi` | 0x4b486e58 | 76 |
| `_ZN10VideoProxy17zoom_pointChangedEj` | 0x4b4874e0 | 76 |
| `_ZN10VideoProxy23videostream_modeChangedE16hblm_videostream` | 0x4b48752c | 76 |
| `_ZN10VideoProxy20pipelineStateChangedENS_13PipelineStateE` | 0x4b487610 | 76 |
| `_ZN10VideoProxy19prohibitZoomChangedEb` | 0x4b4876f4 | 76 |
| `_ZN8SucProxy13TV_minChangedEi` | 0x4b487f4c | 76 |
| `_ZN8SucProxy23global_image_seqChangedEi` | 0x4b487f98 | 76 |
| `_ZN8SucProxy23cambody_attachedChangedEb` | 0x4b487fe4 | 76 |
| `_ZN8SucProxy19flash_statusChangedE17hblm_flash_status` | 0x4b48807c | 76 |
| `_ZN8SucProxy26hotshoe_gps_presentChangedEb` | 0x4b4880c8 | 76 |
| `_ZN8SucProxy25selectable_camerasChangedEj` | 0x4b488114 | 76 |
| `_ZN8SucProxy25expose_seq_enabledChangedEb` | 0x4b488160 | 76 |
| `_ZN8SucProxy16ext_powerChangedEb` | 0x4b4881ac | 76 |

<details><summary>… 另 17 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `_ZN8SucProxy21usbChargeLevelChangedENS_14UsbChargeLevelE` | 0x4b4883e4 | 76 |
| `_ZN13ProdinfoProxy17wifiRegionChangedENS_10WifiRegionE` | 0x4b48a384 | 76 |
| `_ZN11CameraProxy18SV_auto_maxChangedEi` | 0x4b48b750 | 76 |
| `_ZN11CameraProxy18SV_auto_minChangedEi` | 0x4b48b79c | 76 |
| `_ZN11CameraProxy13wbModeChangedEi` | 0x4b48b858 | 76 |
| `_ZN11CameraProxy22pendingLiveViewChangedEj` | 0x4b48b9ac | 76 |
| `_ZN12CamBodyProxy25exposure_abortableChangedEb` | 0x4b48eb3c | 76 |
| `_ZN16ConfigstoreProxy18SV_auto_maxChangedEi` | 0x4b4916b4 | 76 |
| `_ZN16ConfigstoreProxy18SV_auto_minChangedEi` | 0x4b491700 | 76 |
| `_ZN16ConfigstoreProxy27VideoLiveViewOverlayChangedEi` | 0x4b49187c | 76 |
| `_ZN16ConfigstoreProxy15eshutterChangedEb` | 0x4b4923c4 | 76 |
| `_ZN16ConfigstoreProxy31CustomOption_ShowPreviewChangedEb` | 0x4b492410 | 76 |
| `_ZN12StorageProxy19rawImageSizeChangedEi` | 0x4b497730 | 76 |
| `_ZN12StorageProxy24currentWorkingDirChangedERK7QString` | 0x4b49777c | 68 |
| `_ZNK8RawProxy10metaObjectEv` | 0x4b49a648 | 48 |
| `_ZN8RawProxy11qt_metacastEPKc` | 0x4b49a678 | 84 |
| `_ZN8RawProxy11qt_metacallEN11QMetaObject4CallEiPPv` | 0x4b49a6cc | 4 |

</details>

**Removed functions (35)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN18SystemManagerProxy25onSetOnOffPressedFinishedEP23QDBusPendingCallWatcher` | 0x4fc7be38 | 684 |
| `_ZN18SystemManagerProxy14setcamera_modeEi` | 0x4fc7c2e0 | 196 |
| `_ZN10VideoProxy12setZoomPointEj` | 0x4fc7dd54 | 256 |
| `_ZN10VideoProxy20simpleRemoteFunctionERK7QString` | 0x4fc7dee8 | 352 |
| `_ZN10VideoProxy23setliveViewImageTimeoutEj` | 0x4fc7e210 | 76 |
| `_ZN10VideoProxy20setAllowFocusPeakingEb` | 0x4fc7e25c | 80 |
| `_ZN8SucProxy11setFhStatusE13hblm_FHStatus` | 0x4fc7ed2c | 420 |
| `_ZN8SucProxy17setGlobalImageSeqEi` | 0x4fc7eed0 | 424 |
| `_ZN12CamBodyProxy16tvToExposureTimeEii` | 0x4fc92d6c | 160 |
| `_ZN12CamBodyProxy6exposeEv` | 0x4fc92e0c | 472 |
| `_ZN13BodysyncProxy7setModeENS_14BodySyncStatesE` | 0x4fc96c68 | 28 |
| `_ZN13BodysyncProxy11setMainModeEv` | 0x4fc96c84 | 8 |
| `_ZN13BodysyncProxy11setMenuModeEv` | 0x4fc96c8c | 8 |
| `_ZN13BodysyncProxy11setPlayModeEv` | 0x4fc96c94 | 8 |
| `_ZN9FarmProxy12RequestImageERK7QStringijjjijj` | 0x4fca2a0c | 640 |
| `_ZN12StorageProxy12writableSizeE16hblm_volume_typeP7QObject` | 0x4fca67e0 | 1072 |
| `_ZN12StorageProxy9totalSizeE16hblm_volume_typeP7QObject` | 0x4fca6c10 | 1072 |
| `_ZN12StorageProxy12rawImageSizeEv` | 0x4fca7040 | 1016 |
| `_ZN13MetadataProxy15requestMetadataE18hblm_metadata_type9hblm_sinktjRK21hblm_image_dimensionsRK22hblm_xyz_to_rgb_matrixRK20hblm_as_shot_neutraljjjjjjji` | 0x4fcaf26c | 1900 |
| `_ZN18SystemManagerProxy12stateChangedE17hblm_system_state` | 0x4fcb3c5c | 76 |
| `_ZN18SystemManagerProxy18camera_modeChangedEi` | 0x4fcb3ca8 | 76 |
| `_ZN18SystemManagerProxy19tetheredModeChangedEi` | 0x4fcb3cf4 | 76 |
| `_ZN18SystemManagerProxy17isTetheredChangedEb` | 0x4fcb3d8c | 76 |
| `_ZN10VideoProxy16zoomPointChangedEj` | 0x4fcb41d4 | 76 |
| `_ZN10VideoProxy16videoModeChangedE16hblm_videostream` | 0x4fcb4220 | 76 |
| `_ZN10VideoProxy20pipelineStateChangedEi` | 0x4fcb434c | 76 |
| `_ZN8SucProxy18flashStatusChangedENS_13FlashStatusesE` | 0x4fcb4a40 | 76 |
| `_ZN8SucProxy21globalImageSeqChangedEi` | 0x4fcb4a8c | 76 |
| `_ZN8SucProxy24hotshoeGpsPresentChangedEb` | 0x4fcb4c80 | 76 |
| `_ZN13ProdinfoProxy17wifiRegionChangedEN7CConfig10WifiRegionE` | 0x4fcb69d4 | 76 |
| `_ZN12CamBodyProxy25selectable_camerasChangedEj` | 0x4fcbabc0 | 76 |
| `_ZN12CamBodyProxy23cambody_attachedChangedEb` | 0x4fcbae20 | 76 |
| `_ZN12CamBodyProxy13TV_minChangedEi` | 0x4fcbae6c | 76 |
| `_ZN9FarmProxy14usbLinkChangedEb` | 0x4fcc1aec | 76 |
| `_ZN9FarmProxy20usbSuperSpeedChangedEb` | 0x4fcc1b38 | 76 |

**New objects (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTS8RawProxy` | 0x4b4a9aec | 10 |
| `_ZTI8RawProxy` | 0x4b4c2648 | 12 |
| `_ZTV8RawProxy` | 0x4b4c2654 | 56 |
| `_ZN8RawProxy16staticMetaObjectE` | 0x4b4c268c | 24 |

### `/usr/bin/victory-gui`

+23 / −50 functions · +12 / −14 objects

**New functions (23)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN10QByteArray7reserveEi` | 0x2ccb0 | 84 |
| `_ZN12ContentModel25onBrowsingPossibleChangedEb` | 0x36880 | 412 |
| `_ZN12ContentModel19onCurrentDirChangedERK7QString` | 0x3c8c4 | 932 |
| `_ZN12ContentModel7onAddedERK7QStringiRK4QMapIS0_8QVariantEi` | 0x3d798 | 3384 |
| `_ZN12ContentModel9onChangedERK7QStringiRK4QMapIS0_8QVariantE` | 0x3e4d0 | 2180 |
| `_ZN12ContentModel9onRemovedERK7QStringiRK4QMapIS0_8QVariantEi` | 0x3ed54 | 1844 |
| `_ZN12ContentModel16onDeleteFinishedEP23QDBusPendingCallWatcher` | 0x3f5b4 | 92 |
| `_ZN12VideoProxyUI26onOverrideVideoModeTimeoutEv` | 0x58ebc | 716 |
| `_ZN12VideoProxyUI25onvideostream_modeChangedEi` | 0x59188 | 768 |
| `_ZN18SortedContentModel17sourceSizeChangedEi` | 0x63700 | 124 |
| `_ZN5QListIsED1Ev` | 0x6c380 | 80 |
| `_ZN5QListIsED2Ev` | 0x6c380 | 80 |
| `_ZN16ConfigStoreProxy15USBPowerChangedEb` | 0x72150 | 76 |
| `_ZN16ConfigStoreProxy27videoLiveViewOverlayChangedENS_15LiveViewOverlayE` | 0x73000 | 76 |
| `_ZN16ConfigStoreProxy15eshutterChangedEb` | 0x732f0 | 76 |
| `_ZN16IdleDetectFilter20notifyOnEventChangedEb` | 0x7e2d8 | 76 |
| `_ZN16IdleDetectFilter5eventEv` | 0x7e324 | 36 |
| `_ZN9GuiConfig12isA6DChangedEv` | 0x7ed28 | 36 |
| `_ZN15ProdInfoProxyUI20wifiAvailableChangedEb` | 0x82590 | 76 |
| `_ZN20SystemManagerProxyUI17isTetheredChangedEb` | 0x8280c | 76 |
| `_ZN12VideoProxyUI24previousVideoModeChangedEi` | 0x82b4c | 76 |
| `_ZN12VideoProxyUI17zoomPointFChangedERK7QPointF` | 0x82b98 | 68 |
| `_ZN12VideoProxyUI16videoModeChangedEi` | 0x82bdc | 76 |

**Removed functions (50)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN12ContentModel16onRemoveFinishedEP23QDBusPendingCallWatcher` | 0x36134 | 632 |
| `_ZN12ContentModel16onFormatFinishedEP23QDBusPendingCallWatcher` | 0x36ca8 | 560 |
| `_ZSt4swapIN8QVariant7PrivateEEvRT_S3_` | 0x3f62c | 120 |
| `_ZN18SystemManagerProxy17onCollectFinishedEP23QDBusPendingCallWatcher` | 0x501b0 | 404 |
| `_ZN18SystemManagerProxyC1EP7QObject` | 0x50344 | 812 |
| `_ZN18SystemManagerProxyC2EP7QObject` | 0x50344 | 812 |
| `_ZN18SystemManagerProxy14setcamera_modeEi` | 0x509cc | 224 |
| `_ZN18SystemManagerProxy19onPropertiesChangedERK7QStringRK4QMapIS0_8QVariantE` | 0x50b78 | 2312 |
| `_ZN12CambodyProxy15updateValidAvTvEv` | 0x51520 | 204 |
| `_ZN10VideoProxy17onSetModeFinishedEP23QDBusPendingCallWatcher` | 0x59ef4 | 684 |
| `_ZN10VideoProxy12setZoomPointEj` | 0x5a1e0 | 252 |
| `_ZN10VideoProxy32onOverrideVideoStreamModeTimeoutEv` | 0x5a388 | 712 |
| `_ZN10VideoProxy27restartLiveViewImageTimeoutEv` | 0x5b13c | 364 |
| `_ZN10VideoProxy8setStateERK7QStringbS2_` | 0x5b2a8 | 740 |
| `_ZN10VideoProxyC1EP7QObject` | 0x5bad8 | 1240 |
| `_ZN10VideoProxyC2EP7QObject` | 0x5bad8 | 1240 |
| `_ZN12ContentModel18volumeCountChangedEi` | 0x728bc | 76 |
| `_ZN16ConfigStoreProxy18SV_auto_minChangedEi` | 0x75b64 | 76 |
| `_ZN16ConfigStoreProxy18SV_auto_maxChangedEi` | 0x75bb0 | 76 |
| `_ZNK18SystemManagerProxy10metaObjectEv` | 0x80a0c | 48 |
| `_ZN18SystemManagerProxy16versionIdChangedERK7QString` | 0x80a3c | 68 |
| `_ZN18SystemManagerProxy18systemStateChangedEi` | 0x80a80 | 76 |
| `_ZN18SystemManagerProxy18camera_modeChangedEi` | 0x80acc | 76 |
| `_ZN18SystemManagerProxy19tetheredModeChangedEi` | 0x80b18 | 76 |
| `_ZN18SystemManagerProxy21collectingLogsChangedEi` | 0x80b64 | 76 |
| `_ZN18SystemManagerProxy19batteryLevelChangedEi` | 0x80bb0 | 76 |
| `_ZN18SystemManagerProxy20batteryStatusChangedENS_13BatteryStatusE` | 0x80bfc | 76 |
| `_ZN18SystemManagerProxy17isTetheredChangedEb` | 0x80c48 | 76 |
| `_ZN18SystemManagerProxy11qt_metacastEPKc` | 0x80ff4 | 84 |
| `_ZN18SystemManagerProxy11qt_metacallEN11QMetaObject4CallEiPPv` | 0x81048 | 200 |
| `_ZNK10VideoProxy10metaObjectEv` | 0x81310 | 48 |
| `_ZN10VideoProxy16zoomPointChangedEj` | 0x81340 | 76 |
| `_ZN10VideoProxy22videoStreamModeChangedEi` | 0x8138c | 76 |
| `_ZN10VideoProxy24previousVideoModeChangedEi` | 0x813d8 | 76 |
| `_ZN10VideoProxy17zoomPointFChangedERK7QPointF` | 0x81424 | 68 |
| `_ZN10VideoProxy16histogramChangedERK5QListI8QVariantE` | 0x81468 | 68 |
| `_ZN10VideoProxy15positionChangedEj` | 0x814ac | 76 |
| `_ZN10VideoProxy15durationChangedEj` | 0x814f8 | 76 |
| `_ZN10VideoProxy20pipelineStateChangedEi` | 0x81544 | 76 |
| `_ZN10VideoProxy27liveViewImageTimeoutChangedEj` | 0x81590 | 76 |
| `_ZN10VideoProxy19prohibitZoomChangedEb` | 0x815dc | 76 |
| `_ZN10VideoProxy11qt_metacastEPKc` | 0x81db0 | 84 |
| `_ZN10VideoProxy11qt_metacallEN11QMetaObject4CallEiPPv` | 0x81e04 | 200 |
| `_ZN13ProdInfoProxy17wifiRegionChangedEi` | 0x84df8 | 76 |
| `_ZN13ProdInfoProxy15SuSerialChangedE7QString` | 0x84e44 | 68 |
| `_ZN13ProdInfoProxy23wifiRegionStringChangedE7QString` | 0x84e88 | 68 |
| `_ZN13ProdInfoProxy20wifiAvailableChangedEb` | 0x84ecc | 76 |
| `_ZN13ProdInfoProxy22wifi5gAvailableChangedEb` | 0x84f18 | 76 |
| `_ZN12CambodyProxy28validToChangeApertureChangedEb` | 0x86054 | 76 |
| `_ZN12CambodyProxy32validToChangeShutterSpeedChangedEb` | 0x860a0 | 76 |

**New objects (12)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTV15ProdInfoProxyUI` | 0x1aaef0 | 64 |
| `_ZN15ProdInfoProxyUI16staticMetaObjectE` | 0x1aaf30 | 24 |
| `_ZTV20SystemManagerProxyUI` | 0x1aaf54 | 64 |
| `_ZN20SystemManagerProxyUI16staticMetaObjectE` | 0x1aaf94 | 24 |
| `_ZTV12VideoProxyUI` | 0x1aafb8 | 64 |
| `_ZN12VideoProxyUI16staticMetaObjectE` | 0x1aaff8 | 24 |
| `_ZTI13ProdinfoProxy` | 0x1ac0e0 | 12 |
| `_ZN13ProdinfoProxy16staticMetaObjectE` | 0x1ac258 | 24 |
| `_ZZN18QMetaTypeIdQObjectIP12VideoProxyUILi8EE14qt_metatype_idEvE11metatype_id` | 0x1ac2dc | 4 |
| `_ZZN18QMetaTypeIdQObjectIP20SystemManagerProxyUILi8EE14qt_metatype_idEvE11metatype_id` | 0x1ac2e0 | 4 |
| `_ZN19SettingsMiddleLayer9_sucProxyE` | 0x1ac37c | 4 |
| `_ZN15ProdInfoProxyUI14_prodInfoProxyE` | 0x1aee70 | 4 |

**Removed objects (14)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTS18SystemManagerProxy` | 0x182bdc | 21 |
| `_ZTS10VideoProxy` | 0x1835fc | 13 |
| `_ZTV18SystemManagerProxy` | 0x1a05c4 | 64 |
| `_ZTV10VideoProxy` | 0x1a0684 | 64 |
| `_ZTV13ProdInfoProxy` | 0x1a0a40 | 64 |
| `_ZN13ProdInfoProxy16staticMetaObjectE` | 0x1a0a80 | 24 |
| `_ZZN18QMetaTypeIdQObjectIP10VideoProxyLi8EE14qt_metatype_idEvE11metatype_id` | 0x1a1f24 | 4 |
| `_ZZN18QMetaTypeIdQObjectIP18SystemManagerProxyLi8EE14qt_metatype_idEvE11metatype_id` | 0x1a1f28 | 4 |
| `_ZZN18QMetaTypeIdQObjectIP23QDBusPendingCallWatcherLi8EE14qt_metatype_idEvE11metatype_id` | 0x1a1f68 | 4 |
| `_ZZN11QMetaTypeIdIN17QtMetaTypePrivate24QAssociativeIterableImplEE14qt_metatype_idEvE11metatype_id` | 0x1a1f74 | 4 |
| `_ZN19SettingsMiddleLayer19_systemManagerProxyE` | 0x1a1fcc | 4 |
| `_ZN19SettingsMiddleLayer13_cambodyProxyE` | 0x1a1fd0 | 4 |
| `_ZN10VideoProxy18mSingletonInstanceE` | 0x1a49d4 | 4 |
| `_ZN13ProdInfoProxy15m_prodInfoProxyE` | 0x1a4a0c | 4 |

### `/usr/bin/camera-daemon`

+30 / −4 functions · +6 / −0 objects

**New functions (30)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN4DBus24onPendingLiveViewChangedEv` | 0x1a8c0 | 16 |
| `_ZN11WedgeCamera20clearPendingLiveViewEv` | 0x23d0c | 112 |
| `_ZN11WedgeCamera20setIsPendingLiveViewEv` | 0x23d7c | 76 |
| `_ZN17WedgeStateMachine18onVideoModeChangedE16hblm_videostream` | 0x283e4 | 4 |
| `_ZN17SessionlessCamera24stopPendingLiveviewTimerEv` | 0x33d30 | 448 |
| `_ZN17SessionlessCamera18onVideoModeChangedE16hblm_videostream` | 0x33ef0 | 4 |
| `_ZN17SessionlessCamera22onExposureTimerTimeoutEv` | 0x34020 | 160 |
| `_ZN17SessionlessCamera18onSelfTimerTimeoutEv` | 0x34a34 | 488 |
| `_ZN17SessionlessCamera16onExposeFinishedEP23QDBusPendingCallWatcher` | 0x35350 | 784 |
| `_ZN17SessionlessCamera26onSetLiveviewStateFinishedEP23QDBusPendingCallWatcher` | 0x35660 | 772 |
| `_ZN15CFVStateMachine28onSucExposeSeqEnabledChangedEb` | 0x35d5c | 28 |
| `_ZN15CFVStateMachine27onEnableExposureSeqFinishedEP23QDBusPendingCallWatcher` | 0x35da4 | 1064 |
| `_ZN15CFVStateMachine13onProxySyncedEv` | 0x37530 | 164 |
| `_ZN15CFVStateMachine16checkSystemStateEv` | 0x375d4 | 40 |
| `_ZN15CFVStateMachine20onActivatingExposureEv` | 0x376ec | 8 |
| `_ZN15CFVStateMachine22onDeactivatingExposureEv` | 0x376f4 | 8 |
| `_ZN6Camera22pendingLiveViewChangedEb` | 0x38f04 | 76 |
| `_ZN6Camera18SV_auto_maxChangedEv` | 0x392c8 | 36 |
| `_ZN6Camera18SV_auto_minChangedEv` | 0x392ec | 36 |
| `_ZN17WedgeStateMachine16videoModeChangedEv` | 0x3a3b4 | 36 |
| `_ZN17WedgeStateMachine22pendingLiveViewStartedEv` | 0x3a3d8 | 36 |
| `_ZN17SessionlessCamera22isExposePendingChangedEb` | 0x3b2ac | 76 |
| `_ZN15CFVStateMachine16activateExposureEv` | 0x3b498 | 36 |
| `_ZN15CFVStateMachine18deactivateExposureEv` | 0x3b4bc | 36 |
| `_ZN15CFVStateMachine24exposureActivationFailedEv` | 0x3b4e0 | 36 |
| `_ZN15CFVStateMachine20sucActivatedExposureEv` | 0x3b504 | 36 |
| `_ZN15CFVStateMachine22sucDeactivatedExposureEv` | 0x3b528 | 36 |
| `_ZN15CFVStateMachine13startExposingEv` | 0x3b54c | 36 |
| `_ZN15CFVStateMachine12stopExposingEv` | 0x3b570 | 36 |
| `_ZN15CFVStateMachine15exposingChangedEb` | 0x3b594 | 76 |

**Removed functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN13VictoryCamera22onExposureTimerTimeoutEv` | 0x20f5c | 168 |
| `_ZN13VictoryCamera14onExposeFailedEv` | 0x21404 | 204 |
| `_ZN13VictoryCamera17onExposeSucceededEv` | 0x21a24 | 172 |
| `_ZN13VictoryCamera18onSetStateFinishedEP23QDBusPendingCallWatcher` | 0x21ad0 | 576 |

**New objects (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTV9CFVCamera` | 0x53444 | 144 |
| `_ZN9CFVCamera16staticMetaObjectE` | 0x534d4 | 24 |
| `_ZTV17SessionlessCamera` | 0x534f8 | 144 |
| `_ZN17SessionlessCamera16staticMetaObjectE` | 0x53588 | 24 |
| `_ZTV15CFVStateMachine` | 0x535ac | 80 |
| `_ZN15CFVStateMachine16staticMetaObjectE` | 0x535fc | 24 |

### `/usr/bin/phocus-daemon`

+17 / −6 functions · +4 / −1 objects

**New functions (17)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN10RawHandler19tx_callback_wrapperEtP10hblm_sig_tPv` | 0x44e9c | 20 |
| `_ZN10RawHandler16sendAsyncMessageERK13PhocusMessage` | 0x45c48 | 2528 |
| `_ZN10RawHandler19rx_callback_wrapperEP22apps_messaging_packagePv` | 0x48da8 | 16 |
| `_ZN13ActionHandler16onExposeFinishedEb` | 0x5fd84 | 1056 |
| `_ZN14PhocusNotifier17onValidSvsChangedE5QListIiE` | 0x692e4 | 872 |
| `_ZN14PhocusNotifier17onValidAvsChangedE5QListIiE` | 0x6964c | 876 |
| `_ZN14PhocusNotifier17onValidTvsChangedE5QListIiE` | 0x699b8 | 876 |
| `_Z27qRegisterNormalizedMetaTypeI5QListIiEEiRK10QByteArrayPT_N9QtPrivate21MetaTypeDefinedHelperIS5_Xaasr12QMetaTypeId2IS5_E7DefinedntsrSA_9IsBuiltInEE11DefinedTypeE` | 0x73208 | 872 |
| `_ZN9QtPrivate16ConverterFunctorI5QListIiEN17QtMetaTypePrivate23QSequentialIterableImplENS3_33QSequentialIterableConvertFunctorIS2_EEED1Ev` | 0x73708 | 620 |
| `_ZN9QtPrivate16ConverterFunctorI5QListIiEN17QtMetaTypePrivate23QSequentialIterableImplENS3_33QSequentialIterableConvertFunctorIS2_EEED2Ev` | 0x73708 | 620 |
| `_ZN5QListIiEC1ERKS0_` | 0x73978 | 148 |
| `_ZN5QListIiEC2ERKS0_` | 0x73978 | 148 |
| `_ZN14PropertyFinder23onHasselbladHostChangedEb` | 0x74710 | 76 |
| `_ZN13ActionHandler12nmeaSentenceERK7QString` | 0x748ac | 68 |
| `_ZN13ActionHandler7messageERK13PhocusMessage` | 0x748f0 | 68 |
| `_ZN11FileHandler7messageERK13PhocusMessage` | 0x74b08 | 68 |
| `_ZN14PhocusNotifier7messageERK13PhocusMessage` | 0x74d2c | 68 |

**Removed functions (6)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN13ActionHandler18onFinishedExposureEP23QDBusPendingCallWatcher` | 0x66580 | 1544 |
| `_ZN4DBus25notifyNmeaSentenceChangedEv` | 0x7991c | 132 |
| `_ZN14PropertyFinder16SendAsyncMessageERK13PhocusMessage` | 0x7a940 | 68 |
| `_ZN13ActionHandler16SendAsyncMessageERK13PhocusMessage` | 0x7aad0 | 68 |
| `_ZN11FileHandler16SendAsyncMessageERK13PhocusMessage` | 0x7ae94 | 68 |
| `_ZN16PhocusProperties19nmeaSentenceChangedE7QString` | 0x7b66c | 68 |

**New objects (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZGVZN9QtPrivate19ValueTypeIsMetaTypeI5QListIiELb1EE17registerConverterEiE1f` | 0xa1144 | 4 |
| `_ZZN9QtPrivate19ValueTypeIsMetaTypeI5QListIiELb1EE17registerConverterEiE1f` | 0xa1148 | 8 |
| `_ZZN11QMetaTypeIdI5QListIiEE14qt_metatype_idEvE11metatype_id` | 0xa1150 | 4 |
| `_ZZN11QMetaTypeIdIN17QtMetaTypePrivate23QSequentialIterableImplEE14qt_metatype_idEvE11metatype_id` | 0xa1154 | 4 |

**Removed objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZN18QMetaTypeIdQObjectIP23QDBusPendingCallWatcherLi8EE14qt_metatype_idEvE11metatype_id` | 0xaca50 | 4 |

### `/usr/bin/bodystate-daemon`

+8 / −0 functions · +4 / −0 objects

**New functions (8)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN8bodysync22functionOnOffLongPressEv` | 0x18c54 | 12 |
| `_ZN11InputDevice12onInputEventEv` | 0x31e40 | 796 |
| `_ZN11InputDevice11setFilenameERK7QString` | 0x3215c | 1868 |
| `_ZN11PowerButton9onTimeoutEv` | 0x3293c | 324 |
| `_ZN11PowerButton13onInputEventsERK10QByteArray` | 0x32cdc | 104 |
| `_ZN10UdevClient21buttonDeviceAvailableERK7QString` | 0x34ad8 | 68 |
| `_ZN11InputDevice17newEventsReceivedERK10QByteArray` | 0x3573c | 68 |
| `_ZN11PowerButton8powerOffEv` | 0x359a8 | 36 |

**New objects (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTV11InputDevice` | 0x4d51c | 56 |
| `_ZN11InputDevice16staticMetaObjectE` | 0x4d554 | 24 |
| `_ZTV11PowerButton` | 0x4d578 | 56 |
| `_ZN11PowerButton16staticMetaObjectE` | 0x4d5b0 | 24 |

### `/usr/bin/system-manager`

+5 / −1 functions · +2 / −0 objects

**New functions (5)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN4DBus21onUiPowerStateChangedEv` | 0x1b700 | 16 |
| `_ZN13SystemManager21onUiPowerStateChangedEv` | 0x1b9c4 | 4 |
| `_Z17qRegisterMetaTypeI13QDBusArgumentEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS3_Xaasr12QMetaTypeId2IS3_E7DefinedntsrS8_9IsBuiltInEE11DefinedTypeE` | 0x2b890 | 364 |
| `_ZN13SystemManager19uiPowerStateChangedEv` | 0x3771c | 36 |
| `_ZN10LinkStatus13statusChangedEv` | 0x38da4 | 36 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN13SystemManager19onLinkStatusChangedEv` | 0x1f5f8 | 796 |

**New objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTV10LinkStatus` | 0x521f4 | 64 |
| `_ZN10LinkStatus16staticMetaObjectE` | 0x52234 | 24 |

### `/usr/bin/msg2dbus`

+4 / −0 functions · +0 / −2 objects

**New functions (4)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN14CamBodyHandler17onAttachedChangedEb` | 0x4622c | 12 |
| `_ZN5QListIiED1Ev` | 0x54980 | 80 |
| `_ZN5QListIiED2Ev` | 0x54980 | 80 |
| `_ZN10SucHandler22cambodyAttachedChangedEb` | 0x54ef4 | 76 |

**Removed objects (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZTV16MessageIOHandler` | 0x7b2d0 | 64 |
| `_ZN16MessageIOHandler16staticMetaObjectE` | 0x7b310 | 24 |

### `/usr/bin/network-manager`

+1 / −1 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN7Manager19onWifiRegionChangedEN13ProdinfoProxy10WifiRegionE` | 0x14a70 | 4 |

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN7Manager19onWifiRegionChangedEN7CConfig10WifiRegionE` | 0x14a70 | 4 |

### `/usr/bin/storage-daemon`

+0 / −2 functions · +0 / −0 objects

**Removed functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN7Storage19onImgPropertyChangeEv` | 0x55ed0 | 28 |
| `_ZN7Storage16onVolumesChangedEv` | 0x55ef4 | 8 |

### `/usr/bin/jpeg-daemon`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN7Encoder21onTetheredModeChangedE18hblm_tethered_mode` | 0x173b8 | 492 |

### `/bin/busybox.nosuid`

+0 / −0 functions · +0 / −0 objects

### `/bin/busybox.suid`

+0 / −0 functions · +0 / −0 objects

### `/bin/journalctl`

+0 / −0 functions · +0 / −0 objects

### `/bin/kmod`

+0 / −0 functions · +0 / −0 objects

### `/bin/login.shadow`

+0 / −0 functions · +0 / −0 objects

### `/bin/mount.util-linux`

+0 / −0 functions · +0 / −0 objects

### `/bin/networkctl`

+0 / −0 functions · +0 / −0 objects

### `/bin/su.shadow`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemctl`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-ask-password`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-escape`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-machine-id-setup`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-notify`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-sysusers`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-tmpfiles`

+0 / −0 functions · +0 / −0 objects

### `/bin/systemd-tty-ask-password-agent`

+0 / −0 functions · +0 / −0 objects

### `/bin/udevadm`

+0 / −0 functions · +0 / −0 objects

### `/lib/ld-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libblkid.so.1.1.0`

+0 / −0 functions · +0 / −0 objects

### `/lib/libc-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libcap.so.2.24`

+0 / −0 functions · +0 / −0 objects

### `/lib/libcom_err.so.2.1`

+0 / −0 functions · +0 / −0 objects

### `/lib/libcrypt-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libcrypto.so.1.0.0`

+0 / −0 functions · +0 / −0 objects

### `/lib/libdl-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libe2p.so.2.3`

+0 / −0 functions · +0 / −0 objects

### `/lib/libext2fs.so.2.4`

+0 / −0 functions · +0 / −0 objects

### `/lib/libgcc_s.so.1`

+0 / −0 functions · +0 / −0 objects

### `/lib/libm-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libmount.so.1.1.0`

+0 / −0 functions · +0 / −0 objects

### `/lib/libncursesw.so.5.9`

+0 / −0 functions · +0 / −0 objects

### `/lib/libpthread-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libresolv-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/librt-2.22.so`

+0 / −0 functions · +0 / −0 objects

### `/lib/libsysfs.so.2.0.1`

+0 / −0 functions · +0 / −0 objects

### `/lib/libtinfo.so.5.9`

+0 / −0 functions · +0 / −0 objects

### `/lib/libudev.so.1.6.4`

+0 / −0 functions · +0 / −0 objects

### `/lib/libusb-1.0.so.0.1.0`

+0 / −0 functions · +0 / −0 objects

### `/lib/libuuid.so.1.3.0`

+0 / −0 functions · +0 / −0 objects

### `/lib/libz.so.1.2.8`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **4394** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/usr/bin/victory-gui`

<details><summary>新增 559 条字符串, 展示前 100 条</summary>

````text
                               109
                    // Calculate corresponding value, correct placement of slider
                    //This should be handled by SUC, but it is not implemented there yet.
                    Camera.setLiveViewState(false)
                    event.accepted = true
                    if (VideoControl.videoMode === VideoControl.Record)
                    value = realValue
                "qrc:///icons/CardStatusOK.png"
                //  note: TMode passes on event, need to handle the stopping of ongoing T.
                GlobalStateInfo.selfTimerAborted = true
                anchors.verticalCenter: horizontalLine.verticalCenter
                axis: Drag.XAxis
                color: lineColor;
                console.log("tick: ", iTick, tick.x)
                height: 20;
                horizontalCenter: slidingMarker.horizontalCenter
                icon: "qrc:///icons/DriveMode_Cont.png"
                icon: "qrc:///icons/DriveMode_Single.png"
                iconsVisible: true
                if (!drag.active) {
                if (VideoControl.videoMode !== VideoControl.Off && configstore.CameraType === Config.CameraTypePinhole) {
                if(!cambody.isTMode)
                maximumX: horizontalLine.x + horizontalLine.width - slidingMarker.width / 2
                minimumX: horizontalLine.x - slidingMarker.width / 2
                newValue = maxValue;
                newValue = minValue;
                property int index
                target: slidingMarker
                tick.index = iTick
                var tick = Qt.createQmlObject(sc, slider, 'tick' + iTick);
                verticalCenter: slidingMarker.verticalCenter
                when: (guiconfig.isWedge || guiconfig.isA6D) && root.allowVisible && (GPS.gpsStatus === GPS.GPSStatusNoPosition)
                when: (guiconfig.isWedge || guiconfig.isA6D) && root.allowVisible && (GPS.gpsStatus === GPS.GPSStatusPositionValid)
                width: 5;
                x: horizontalLine.width / (tickCount - 1) * index - width / 2 + horizontalLine.x
            anchors.centerIn: horizontalLine
            anchors.verticalCenter: selfTimerIcon.verticalCenter
            anchors.verticalCenterOffset: isSelfTimer ? (implicitHeight - baselineOffset) * 0.5 : 0
            border.color: lineColor
            border.width: lineThickness
            color: lineColor
            color: sliderMouseArea.containsPress || sliderMouseArea.drag.active ? constants.highlightColor : markerColor
            console.log("Slider got key event")
            drag {
            drag.onActiveChanged: {
            duration: percentageAnimDelay * 1000
            easing.type: Easing.Linear;
            else {
            for (var iTick = 0; iTick < tickCount; ++iTick){
            height: lineThickness
            height: markerSize
            height: slidingMarker.height * 2.4
            height: zeroMarkerSize;
            id: horizontalLine
            id: sliderMouseArea
            id: slidingMarker
            if (Camera.selfTimerCountDown > 0) {
            if(newValue < minValue)
            if(newValue > maxValue)
            newValue = newValue + 0.5
            newValue = newValue - 0.5
            onClicked: { }
            propagateComposedEvents: false
            radius: markerSize / 2
            source: "qrc:///icons/Selftimer_Running.png"
            status === ContentModel.STORAGE_FULL ? "qrc:///icons/CardStatusFull.png" :
            status === ContentModel.STORAGE_LOCKED ? "qrc:///icons/CardStatusLocked.png" :
            value = newValue
            var start = (VideoControl.videoMode !== VideoControl.Record);
            width: height * 1.5
            width: lineThickness;
            width: markerSize
            x: horizontalLine.x - width / 2 + horizontalLine.width / (maxValue - minValue) * (value - minValue)
            z: 1
            }"
           guiconfig.isCFV   ? 109.7436 :
        // Horizontal line
        // Sliding marker
        // Ticks, variable amount. Create dynamically, since we have variable number of ticks
        // Zero marker
        <file>translations/victory_de_DE.qm</file>
        <file>translations/victory_es_ES.qm</file>
        <file>translations/victory_fr_FR.qm</file>
        <file>translations/victory_it_IT.qm</file>
        <file>translations/victory_ja_JP.qm</file>
        <file>translations/victory_ko_KR.qm</file>
        <file>translations/victory_ru_RU.qm</file>
        <file>translations/victory_zh_CN.qm</file>
        Component.onCompleted: {
        allowCross: true
        allowSquare: true
        else if(MKeys.pressedFn("NAVRIGHT", event.key))
        else if(VideoControl.videoMode === VideoControl.Record && MKeys.pressedFnAcc("MENU", event)) {
        enabled: !guiconfig.isWedge && (VideoControl.videoMode !== VideoControl.Record) && (VideoControl.videoMode !== VideoControl.Zoom) && !preventLiveViewSwipe
        enabled: progressPercent < 1
        id: slider
        if(MKeys.pressedFn("NAVLEFT", event.key)) {
        propagateComposedEvents: false //Will trigger two onClicked() in Popovers used above this item in the visual stacking order if set to true.
        property string sc: "import QtQuick 2.0; Rectangle {
        source: "qrc:///icons/FlashStatus.png"
````

</details>

> 其余 459 条见 `result.json`。

### `/usr/lib/libQt5Quick.so.5.5.1`

<details><summary>新增 531 条字符串, 展示前 100 条</summary>

````text
 OL@ OL
 bLxg^L
 hL` hL
!RLP"RLP
!hLX1hLx3hL
!hLX1hLx3hL,7hLd7hL
"SL,#SLh
"TLL#TL$'TLx&TL
"hLX2hL
#OL $OL
#OL@#OL
#cL`,cL
#iL$)iLx)iLH,iL
$LLp$LL
%fL0*fL
%gL@&gL 
%nL<3iL
%nLh@iLHBiL
&gLD/gL
&mLT4iL
'fLH,fL
'jLhZOL
'nLdDiL
(/nL`siL
(fLp/fLT
(fLp/fLd
*cLl'AK
+lL,~gL
,.nLdqiL
,cLd#cLhFcL
,jL,ymL$
,nL0eiL
,nLttcL
-RL,.RL
-RLl'AK
-jL,ymL
.`LH/`L
.gLl0gLP3gL
.gLl0gLh9WL
.jL|zmL$
.nL<QmLpQmL
/bL(/bL
/bLh0bL
/hLD0hL
/jL,wmL
/jL,{mL$
/nL<siL<viL8wiL
0fL\3fL
0jL8{mL$
1hL|3hL
1hL|3hL`5WL
1jL,wmL$
1mL@JiL
2SLT6SL 
2WL@3WL
2WL\2WL
2gLdBWL
2hLD4hL
2hLD4hL<6hLt6hL
2jL,wmL
2jL4wmL$
3RLt3RLP
3bLl'AKp
3fLPKKL
3gLH3gL
3iL09iL
4WLX5WL
4gL45gL
4jL05jL
4mL LiL
5OLP)KLT)KL$
5WL06WL
5dLl'AK
5gL|6gL
5hL46hL
6fLX7fL
6gL$7gL
6hL$7hL
73LH)KL
73LH)KLPUKL$
7NLl'AK
7aL$8aL
7gL\7gL
8WLX8WL
9`LD'WL
9iLh;iL
9mL QiL
:WL`:WL 
:_L8%_L
;hL8q_Ldr_L
;hLD>hL
;hL\1WL
< L<J L(> L@? L
<SL8TSL 7SL
<SLHISL
<WLX<WL 
>WLP>WL 
>fL ?fL
>fL ?fLd
>hL(7WLh7WL
````

</details>

> 其余 431 条见 `result.json`。

### `/lib/libcrypto.so.1.0.0`

<details><summary>新增 303 条字符串, 展示前 100 条</summary>

````text
 TkK TkK1
 XkK8XkKT
 [kK,[kKr
 ckK ckK
 dkK dkK
 jkK jkK
 lkK lkK%
 pkK pkKR
! JmKg
!,KmKh
"0wmKh
"@wmKi
"HymKr
"lumKd
"pvmKf
"xumKe
#D$mKg
$RkK$RkK
$VkK4VkKF
$^bKHlbK
$bkK(bkK
$ekK$ekK
$kkK$kkK
$skK4skKt
$wkK0wkK
$xkK@xkK
$ykK$ykK
'pymKl
(3mK8`oK
(`kK(`kK
(hkK(hkK
(jkK(jkK
({kK({kK
)dK`.dK
)dKl.dK
+aKx+aK
,WkK<WkKM
,^kK8^kK
,akK<akK
,bkK8bkK
,ikK,ikK
,lkK<lkK&
,okK,okKG
,qkK,qkK`
,vkK,vkK
,zkK,zkK
,}kK,}kK
.aK(/aK
0QkK<QkK
0UkK<UkK<
0`kK0`kK
0bKx0bK
0gkK0gkK
0jkK0jkK
0pkK0pkKS
0ykK0ykK
1mK0^oK
1mKXboK
1mKd^oK
2mK|_oK
3mKpcoK
4SkK@SkK$
4TkK4TkK2
4ckK4ckK
4dkK4dkK
4fkK4fkK
4mkK4mkK1
4smKHsmK
4tkK<tkK
4tmK<tmK
4{kK4{kK
4|kK4|kK
4~kK4~kK
5eK\3eK
7mK 7mK$7mK(7mK,7mK07mK47mK87mK<7mK
8RkK8RkK
8YkKPYkKZ
8[kKD[kKs
8\kK8\kK
8`kK8`kK
8hK0ChK
8jkK8jkK
8rkK@rkKl
8vkK8vkK
8ykK8ykK
8zkK8zkK
:dK @dK
:oK\yoK<JoK
<3mKT]oK
<kkK<kkK
<wkKHwkK
>pK,?pK
>pK@?pKl1pK
@TkK@TkK3
@\kK@\kK
@`kK@`kK
@nkK@nkK=
@okK@okKH
@pkK@pkKT
@ukK@ukK
````

</details>

> 其余 203 条见 `result.json`。

### `/usr/lib/libQt5Qml.so.5.5.1`

<details><summary>新增 209 条字符串, 展示前 100 条</summary>

````text
!6LP&(L
#6Lh%6L
#LTE L
'(LX((L 
'(Ll'AK
(L,X.LXc&L$
)LLf*L
)Ll'AK0G:L
)LxZ*L
,Ll'AKd
-&Lp75L
-/L4g LX
-1L`81L`&1L@.1L
.L4g L
.LTE L
/6L@/6L 
/L4g Lx
/LTE L
16LL16L
1Ll'AKH
36Lh36L
3Ll'AK
3Ll'AKl
56L`76L
5Ll'AK
5Ll'AKT
6LDW5L
6Ll!6L
7L({;LT
7L0A;L
7L0v;L
7Llh;L$
8/L ;/L 
86L,96L
:L 86L
:L($6L
:L(C6L
:L0A;L$
:L8@6L
:L8A;L$
:L@06L
:L@\6L
:LLQ6L
:LPT6L
:LTX6L
:LXA;L
:L`56L
:Ll'AK(
:Lx26L
:Lx=6L
;6L4<6L
;L$86LT86L
;L(Q6L
;L0z4LXz4L
;L8O6LhO6L
;L@A.L
;LD06Lh06L
;LDQ&LhQ&L
;LDx3Lxx3Lt|3L
;LP_(L
;LPl.L
;Ld-6L
;Ld56L
;LpU(L
;LxK3L
< L8I"L
< L<J L(> L
< L<J L(> L@? L
< L<J L(> L@? LT
< L<J L(> LPt"L
< L<J L(> Lt
< LDA"L
=6L =6LH=6L 
=6L >6Lt>6Lx>6L
=:L(s;L
>:L0A;L
? L@? L
?:LXA;L
@:L8A;L
A*LLf*L
A6LHB6L
AKl'AK
AKl'AK,
B L<J L
F L e"L
F LTE L
F Lps"L
F6LTG6L 
G:L0A;L$
H6L$K6L
J g7LHD;L$
J$C:LH
J$a7L0D;L$
J$c7L0D;L$
J$j7L0D;L$
J(Z7LT
J(e7L<D;L$
J,_7L8A;L$
J,l7L0D;L$
J0d7L<D;L$
````

</details>

> 其余 109 条见 `result.json`。

### `/usr/lib/liborc-0.4.so.0.23.0`

<details><summary>新增 189 条字符串, 展示前 100 条</summary>

````text
}Kabsl
}Kabsw
}Kaccl
}Kaccsadubl
}Kaccw
}Kaddb
}Kaddd
}Kaddf
}Kaddl
}Kaddq
}Kaddssb
}Kaddssl
}Kaddssw
}Kaddusb
}Kaddusl
}Kaddusw
}Kaddw
}Kandb
}Kandl
}Kandnb
}Kandnl
}Kandnq
}Kandnw
}Kandq
}Kandw
}Kavgsb
}Kavgsl
}Kavgsw
}Kavgub
}Kavgul
}Kavguw
}Kcmpeqb
}Kcmpeqd
}Kcmpeqf
}Kcmpeql
}Kcmpeqq
}Kcmpeqw
}Kcmpgtsb
}Kcmpgtsl
}Kcmpgtsq
}Kcmpgtsw
}Kcmpled
}Kcmplef
}Kcmpltd
}Kcmpltf
}Kconvdf
}Kconvdl
}Kconvfd
}Kconvfl
}Kconvhlw
}Kconvhwb
}Kconvld
}Kconvlf
}Kconvlw
}Kconvql
}Kconvsbw
}Kconvslq
}Kconvssslw
}Kconvsssql
}Kconvssswb
}Kconvsuslw
}Kconvsusql
}Kconvsuswb
}Kconvswl
}Kconvubw
}Kconvulq
}Kconvusslw
}Kconvussql
}Kconvusswb
}Kconvuuslw
}Kconvuusql
}Kconvuuswb
}Kconvuwl
}Kconvwb
}Kcopyb
}Kcopyl
}Kcopyq
}Kcopyw
}Kdiv255w
}Kdivd
}Kdivf
}Kdivluw
}Kldreslinb
}Kldreslinl
}Kldresnearb
}Kldresnearl
}Kloadb
}Kloadl
}Kloadoffb
}Kloadoffl
}Kloadoffw
}Kloadpb
}Kloadpl
}Kloadpq
}Kloadpw
}Kloadq
}Kloadupdb
}Kloadupib
}Kloadw
}Kmaxd
````

</details>

> 其余 89 条见 `result.json`。

### `/usr/lib/libappscommon.so.1.0.0`

<details><summary>新增 180 条字符串, 展示前 100 条</summary>

````text
 in volumes()
8RawProxy
Cannot find volume_type: 
CustomOption_ShowPreview
CustomOption_ShowPreviewChanged
DHKxEHK$
EKPPHK 
Failed parsing kWhiteLevelTag
IK0iHK
Invalid slot:
ItemTransfered
JK $JK
JKPoIK
Jl'AKD
Kl'AK0
Kl'AKp
LK$0JK
LKP^HK
OEK0&LK
PendNone
PendOff
PendOn
PendingLiveView
PropAV
PropSVAutoMax
PropSVAutoMin
PropTV
RawMessage
RawProxy
Remove
SV_auto_max
SV_auto_maxChanged
SV_auto_min
SV_auto_minChanged
TIKpTIK8UIKlUIK 
UIK|gIK
Unhandled product ID
UsbChargeHigh
UsbChargeLevel
UsbChargeLow
UsbChargeMid
UsbChargeOff
VideoLiveViewOverlay
VideoLiveViewOverlayChanged
WifiMode
WifiMode2G
WifiMode5G
WifiRegion2gOnly
WifiRegionEU
WifiRegionNone
WifiRegionUS
_HKH_HK 
_ZN10VideoProxy17zoom_pointChangedEj
_ZN10VideoProxy19prohibitZoomChangedEb
_ZN10VideoProxy20pipelineStateChangedENS_13PipelineStateE
_ZN10VideoProxy21setVideoPlaybackStateEbRK7QStringy
_ZN10VideoProxy23videostream_modeChangedE16hblm_videostream
_ZN11CameraProxy13wbModeChangedEi
_ZN11CameraProxy16setLiveViewStateEb
_ZN11CameraProxy18SV_auto_maxChangedEi
_ZN11CameraProxy18SV_auto_minChangedEi
_ZN11CameraProxy18setPendingLiveViewEb
_ZN11CameraProxy22pendingLiveViewChangedEj
_ZN12CamBodyProxy25exposure_abortableChangedEb
_ZN12CamBodyProxy6exposeEi
_ZN12StorageProxy19rawImageSizeChangedEi
_ZN12StorageProxy20setCurrentWorkingDirERK7QString
_ZN12StorageProxy24currentWorkingDirChangedERK7QString
_ZN12StorageProxy6formatE16hblm_volume_type
_ZN12StorageProxy6removeERK7QString
_ZN13MetadataProxy15requestMetadataE18hblm_metadata_type9hblm_sinktjRK21hblm_image_dimensionsRK22hblm_xyz_to_rgb_matrixRK20hblm_as_shot_neutraljjjjjjjiRK13hblm_rationalRK23hblm_metadata_rectanglejj
_ZN13ProdinfoProxy17wifiRegionChangedENS_10WifiRegionE
_ZN16ConfigstoreProxy15eshutterChangedEb
_ZN16ConfigstoreProxy18SV_auto_maxChangedEi
_ZN16ConfigstoreProxy18SV_auto_minChangedEi
_ZN16ConfigstoreProxy27VideoLiveViewOverlayChangedEi
_ZN16ConfigstoreProxy31CustomOption_ShowPreviewChangedEb
_ZN18SystemManagerProxy11collectLogsEv
_ZN18SystemManagerProxy16versionIDChangedERK7QString
_ZN18SystemManagerProxy18camera_modeChangedE16hblm_camera_mode
_ZN18SystemManagerProxy19system_stateChangedE17hblm_system_state
_ZN18SystemManagerProxy19uiPowerStateChangedE16hblm_power_state
_ZN18SystemManagerProxy20batteryStatusChangedEi
_ZN18SystemManagerProxy20tethered_modeChangedE18hblm_tethered_mode
_ZN18SystemManagerProxy22collecting_logsChangedEi
_ZN3Bus12rawInterfaceEv
_ZN3Bus7rawPathEv
_ZN5MData23digitalGainToWhiteLevelEj
_ZN5MData23whiteLevelToDigitalGainEj
_ZN8CStorage12hasCFastSlotEv
_ZN8CStorage13tagWhiteLevelEv
_ZN8CStorage13writableSpaceERK4QMapI7QString8QVariantE
_ZN8CStorage16isWriteProtectedERK4QMapI7QString8QVariantE
_ZN8CStorage16propRawImageSizeEv
_ZN8CStorage21slotIndexToVolumeTypeEi
_ZN8CStorage8isSdCardE16hblm_volume_type
_ZN8CStorage9freeSpaceERK4QMapI7QString8QVariantE
_ZN8CStorage9slotIndexE16hblm_volume_type
_ZN8CStorage9totalSizeERK4QMapI7QString8QVariantE
_ZN8RawProxy10rawMessageERK7QStringRK10QByteArray
````

</details>

> 其余 80 条见 `result.json`。

### `/lib/systemd/systemd`

<details><summary>新增 136 条字符串, 展示前 100 条</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/async.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/calendarspec.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cap-list.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/clock-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/env-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/exit-status.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fdset.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/ratelimit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/rm-rf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/signal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/socket-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/socket-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/automount.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/bus-policy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/busname.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/cgroup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-automount.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-busname.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-cgroup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-execute.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-job.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-kill.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-manager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-mount.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-path.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-scope.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-service.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-slice.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-snapshot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-swap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-timer.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus-unit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/dbus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/execute.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/failure-action.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/hostname-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/job.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/kill.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/killall.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/kmod-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/load-dropin.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/load-fragment.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/locale-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/loopback-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/machine-id-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/main.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/manager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/mount-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/mount.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/namespace.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/path.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/scope.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/service.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/show-status.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/slice.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/snapshot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/swap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/target.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/timer.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/transaction.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/unit-printf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/unit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
````

</details>

> 其余 36 条见 `result.json`。

### `/usr/bin/camera-daemon`

<details><summary>新增 111 条字符串, 展示前 100 条</summary>

````text
 Farm ptr: 
../git/camera.cpp
15CFVStateMachine
17SessionlessCamera
9CFVCamera
CFVCamera
CFVStateMachine
Connecting Farm
Exposure is activated
Exposure is not activated
Is activating exposure
Is de-activating exposure
Media full
Media missing
Not Exposing
Overriding forceFindFocus since eshutter is used without lens
PendingLiveView
Run in CFV mode.
SV_auto_max
SV_auto_maxChanged
SV_auto_min
SV_auto_minChanged
Selftimer aborted
SessionlessCamera
Show live view after expose is not supported on sessionless
The cambody does not support remote exposure
_ZN10VideoProxy23videostream_modeChangedE16hblm_videostream
_ZN11QTextStreamlsEm
_ZN11WedgeCamera20clearPendingLiveViewEv
_ZN11WedgeCamera20setIsPendingLiveViewEv
_ZN12CamBodyProxy6exposeEi
_ZN14QAbstractState13activeChangedEb
_ZN15CFVStateMachine12stopExposingEv
_ZN15CFVStateMachine13onProxySyncedEv
_ZN15CFVStateMachine13startExposingEv
_ZN15CFVStateMachine15exposingChangedEb
_ZN15CFVStateMachine16activateExposureEv
_ZN15CFVStateMachine16checkSystemStateEv
_ZN15CFVStateMachine16staticMetaObjectE
_ZN15CFVStateMachine18deactivateExposureEv
_ZN15CFVStateMachine20onActivatingExposureEv
_ZN15CFVStateMachine20sucActivatedExposureEv
_ZN15CFVStateMachine22onDeactivatingExposureEv
_ZN15CFVStateMachine22sucDeactivatedExposureEv
_ZN15CFVStateMachine24exposureActivationFailedEv
_ZN15CFVStateMachine27onEnableExposureSeqFinishedEP23QDBusPendingCallWatcher
_ZN15CFVStateMachine28onSucExposeSeqEnabledChangedEb
_ZN16ConfigstoreProxy15eshutterChangedEb
_ZN16ConfigstoreProxy18SV_auto_maxChangedEi
_ZN16ConfigstoreProxy18SV_auto_minChangedEi
_ZN16QLoggingCategoryC1EPKc9QtMsgType
_ZN16QLoggingCategoryD1Ev
_ZN17SessionlessCamera16onExposeFinishedEP23QDBusPendingCallWatcher
_ZN17SessionlessCamera16staticMetaObjectE
_ZN17SessionlessCamera18onSelfTimerTimeoutEv
_ZN17SessionlessCamera18onVideoModeChangedE16hblm_videostream
_ZN17SessionlessCamera22isExposePendingChangedEb
_ZN17SessionlessCamera22onExposureTimerTimeoutEv
_ZN17SessionlessCamera24stopPendingLiveviewTimerEv
_ZN17SessionlessCamera26onSetLiveviewStateFinishedEP23QDBusPendingCallWatcher
_ZN17WedgeStateMachine16videoModeChangedEv
_ZN17WedgeStateMachine18onVideoModeChangedE16hblm_videostream
_ZN17WedgeStateMachine22pendingLiveViewStartedEv
_ZN18SystemManagerProxy18camera_modeChangedE16hblm_camera_mode
_ZN18SystemManagerProxy19system_stateChangedE17hblm_system_state
_ZN18SystemManagerProxy20tethered_modeChangedE18hblm_tethered_mode
_ZN4DBus24onPendingLiveViewChangedEv
_ZN6Camera18SV_auto_maxChangedEv
_ZN6Camera18SV_auto_minChangedEv
_ZN6Camera22pendingLiveViewChangedEb
_ZN8SucProxy13TV_minChangedEi
_ZN8SucProxy19enable_exposure_seqEb
_ZN8SucProxy19flash_statusChangedE17hblm_flash_status
_ZN8SucProxy25expose_seq_enabledChangedEb
_ZN9CFVCamera16staticMetaObjectE
_ZNK14QAbstractState6activeEv
_ZNK14QMessageLogger8criticalEv
_ZTV15CFVStateMachine
_ZTV17SessionlessCamera
_ZTV9CFVCamera
__cxa_guard_abort
activateExposure
allocPendingLiveviewTimer
camera.sessionless
checkSystemState
clearPendingLiveView
deactivateExposure
doExpose
eShutter active: limiting ISO
exposureActivationFailed
inconsistency
isExposePendingChanged
onActivatingExposure
onDeactivatingExposure
onEnableExposureSeqFinished
onExposeFinished
onPendingLiveViewChanged
onProxySynced
onSetLiveviewStateFinished
onSucExposeSeqEnabledChanged
````

</details>

> 其余 11 条见 `result.json`。

### `/usr/lib/libgstreamer-1.0.so.0.405.0`

<details><summary>新增 110 条字符串, 展示前 100 条</summary>

````text
 ~iK4~iK
$kiK<kiK
(aiK<aiK
,iiK\iiK
,oiKPoiK
,piKLpiK
,}iK|EgK
0]iKX]iK
0^iK0agK
0jiKPjiK
0uiKDuiK
0|iKP,hK
4wiKPwiK
8biKTbiK
8ciKTciK
8diKPdiK
8hiKLhiK
8viKXviK
<`iKTXhK
@_iKX_iKc
@siK`siK
@~iKT~iK
CgK8DgK@DgK
DaiKTaiK
DqiKDWhK
EgK$FgK,FgK
HkiKdkiK
HniKhniK
LfKlNiK|QfKT
LliKlliK
MfK`NiK
P\iKx\iK
PmiKhmiK
PuiKluiK
XNiK`UfK
XhiKlhiK
XpiKxpiK
\K(GgK
\K,EgK
\KLDgK
\KXCgK
\KdGgK
\jiKtjiK
\tiKttiK
\wiKxwiK
\xiK|xiK
_iK4_iKP
_iK8[gK
`A_KXA_Kd@_K
`biKxbiK
`ciKxciK
ciK,ciK
diK,diK
dyiK$+hK@
eK`NiK
fK(DfK$
giK$+hK
giKDWhK
giKh\gK
hK(,hKl
hKDWhK
hKXDhK
hKh\gK
hKtfgK
hviKtjiK
hziKhlhK
iK(mgK
iK,miK
iK8cgK
iKDWhK
iKDuiK
iKLDiK
iKPdiK
iKTaiK
iK\biK
iKhlhK
iKl[gK(
iKtjiK
jiK jiK
liK8liK
liKtjiK
miK,miK
niK8niK
oiK<kiKp
q_K|p_Kpa_K
qiK4qiK
qiKx^hK
siK4siK
siKdOhK
tiK0agK
tiKtjiK
uiK viK
vgK@3fK
vgK@3fKT
viKluiK
viKtjiK
wiKH]gK
xiK4xiK
x|iK,miK
yiK@+hK
````

</details>

> 其余 10 条见 `result.json`。

### `/lib/systemd/systemd-networkd`

<details><summary>新增 103 条字符串, 展示前 100 条</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/async.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/capability.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/in-addr-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/dhcp-identifier.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/dhcp-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/dhcp-option.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/dhcp-packet.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/dhcp6-option.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/ipv4ll-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/ipv4ll-packet.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/lldp-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/lldp-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/lldp-port.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/lldp-tlv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/network-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-dhcp-client.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-dhcp-lease.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-dhcp-server.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-dhcp6-client.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-dhcp6-lease.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-icmp6-nd.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-ipv4ll.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/sd-lldp.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-monitor.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-address-pool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-address.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-dhcp4.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-dhcp6.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-fdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-ipv4ll.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-link-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-link.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-manager-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-manager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-bond.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-ipvlan.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-macvlan.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-tunnel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-tuntap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-veth.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-vlan.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev-vxlan.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-netdev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-network-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-route.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/architecture.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
````

</details>

> 其余 3 条见 `result.json`。

### `/usr/bin/phocus-daemon`

<details><summary>新增 80 条字符串</summary>

````text
%s failed to register: %s
Cannot find name for: 
ExposuresLeft
Failed to set video state
Failed to set zoom state
Failed to unlock: 
Not connected to phocus, will discard notification
Not implemented
QList<int>
QtMetaTypePrivate::QSequentialIterableImpl
Sensor unit string: 
Unknown product id:
Unlocking: 
Will send notifications to Phocus
Will stop sending notifications to Phocus
_Z27qRegisterNormalizedMetaTypeI5QListIiEEiRK10QByteArrayPT_N9QtPrivate21MetaTypeDefinedHelperIS5_Xaasr12QMetaTypeId2IS5_E7DefinedntsrSA_9IsBuiltInEE11DefinedTypeE
_ZGVZN9QtPrivate19ValueTypeIsMetaTypeI5QListIiELb1EE17registerConverterEiE1f
_ZN10QByteArray6appendEPKci
_ZN10RawHandler16sendAsyncMessageERK13PhocusMessage
_ZN10RawHandler19rx_callback_wrapperEP22apps_messaging_packagePv
_ZN10RawHandler19tx_callback_wrapperEtP10hblm_sig_tPv
_ZN10VideoProxy18RECEIPIENT_NO_PIPEE
_ZN10VideoProxy23videostream_modeChangedE16hblm_videostream
_ZN11CameraProxy14exposeFinishedEb
_ZN11CameraProxy15validAvsChangedE5QListIiE
_ZN11CameraProxy15validSvsChangedE5QListIiE
_ZN11CameraProxy15validTvsChangedE5QListIiE
_ZN11CameraProxy6exposeEb
_ZN11FileHandler7messageERK13PhocusMessage
_ZN11QMetaObject14normalizedTypeEPKc
_ZN13ActionHandler12nmeaSentenceERK7QString
_ZN13ActionHandler16onExposeFinishedEb
_ZN13ActionHandler7messageERK13PhocusMessage
_ZN14PhocusNotifier17onValidAvsChangedE5QListIiE
_ZN14PhocusNotifier17onValidSvsChangedE5QListIiE
_ZN14PhocusNotifier17onValidTvsChangedE5QListIiE
_ZN14PhocusNotifier7messageERK13PhocusMessage
_ZN14PropertyFinder23onHasselbladHostChangedEb
_ZN18SystemManagerProxy18camera_modeChangedE16hblm_camera_mode
_ZN18SystemManagerProxy19system_stateChangedE17hblm_system_state
_ZN18SystemManagerProxy20tethered_modeChangedE18hblm_tethered_mode
_ZN3Bus10sucServiceEv
_ZN3Bus7rawPathEv
_ZN5QListIiEC1ERKS0_
_ZN5QListIiEC2ERKS0_
_ZN7QString15toLatin1_helperERKS_
_ZN7Version9productIDEv
_ZN8QVariantC1Ej
_ZN8RawProxy10rawMessageERK7QStringRK10QByteArray
_ZN9FarmProxy14itemTransferedERK7QString
_ZN9QMetaType25registerConverterFunctionEPKN9QtPrivate25AbstractConverterFunctionEii
_ZN9QMetaType25registerNormalizedTypedefERK10QByteArrayi
_ZN9QMetaType27unregisterConverterFunctionEii
_ZN9QMetaType30hasRegisteredConverterFunctionEii
_ZN9QMetaType8typeNameEi
_ZN9QtPrivate16ConverterFunctorI5QListIiEN17QtMetaTypePrivate23QSequentialIterableImplENS3_33QSequentialIterableConvertFunctorIS2_EEED1Ev
_ZN9QtPrivate16ConverterFunctorI5QListIiEN17QtMetaTypePrivate23QSequentialIterableImplENS3_33QSequentialIterableConvertFunctorIS2_EEED2Ev
_ZNK10QByteArray8endsWithEc
_ZNK10QDBusError4nameEv
_ZNK12StorageProxy9totalSizeE16hblm_volume_type
_ZNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEE12_M_constructEjc
_ZSt9terminatev
_ZZN11QMetaTypeIdI5QListIiEE14qt_metatype_idEvE11metatype_id
_ZZN11QMetaTypeIdIN17QtMetaTypePrivate23QSequentialIterableImplEE14qt_metatype_idEvE11metatype_id
_ZZN9QtPrivate19ValueTypeIsMetaTypeI5QListIiELb1EE17registerConverterEiE1f
camera_mode
connectChanged
disconnectChanged
hasselbladHost
liveViewImageTimeout
message
onExposeFinished
onHasselbladHostChanged
onValidAvsChanged
onValidSvsChanged
onValidTvsChanged
sendAsyncMessage
validAvs
validSvs
validTvs
````

</details>

### `/usr/lib/libwayland-client.so.0.3.0`

<details><summary>新增 76 条字符串</summary>

````text
-WK 7WK
H{XK@pWKHpWK
LzXK8lWK
XK$mWK$pWK4
XK0mWK
XK8kWK4kWK
XK8lWK@lWK
XKDkWK
XKLmWK
XKTmWK
XKhlWK4kWK(
XKhlWKplWKX
XKhlWKplWKl
XKhmWK
XKlnWK
XKtlWKxlWK
XK|mWK
\vXKPlWKXlWK
kWK$kWK
lWK lWK
lWKxlWK
mWK oWK
mWK$pWK,
mWK$pWK0
nWK$pWK
nWK(nWK
oWKD~XK
oWK\oWK
oWK\~XK
oWKh~XK
oWKx~XK$oWK4oWK
pWK$pWK8~XK
pWK$pWK<~XK
pWK$pWK@~XK(pWK
tXKpwXKpwXKpwXKpwXK
uXK4zXK
vXKDvXK
vXK\lWK
wXK\lWK4kWK$
xXKpwXK
yXKHoWKPoWK
yXKpwXKpwXK
zXKtoWK
{XK0{XKpwXK`uXK4zXK
{XK`uXK`uXK
{XKxpWK
~XK(kWK4kWK
~XK(lWK
~XK(lWK$pWK
~XK(oWK
~XK0lWK
~XK0nWK@nWK
~XK4pWK
~XK8lWK
~XK8lWK@lWK
~XK8oWK
~XK<mWKDmWK
~XKDlWK
~XKHkWK$pWK4~XK
~XKHnWKTnWK
~XKLpWK
~XKPkWK
~XKToWK\oWK
~XK\kWK
~XK\lWK
~XK\lWKdlWK`
~XK\nWK
~XK\pWKdpWK
~XK`oWK
~XKhlWK
~XKloWK
~XKlpWK
~XKpkWK
~XKtoWK
~XKxnWK
~XK|oWK
````

</details>

### `/usr/lib/libsqlite3.so.0.8.6`

<details><summary>新增 73 条字符串</summary>

````text
$Y_K0Y_K(Y_K
$_K4V_K
%WK WXK "XK
+VKPYXK4
-XK4+XK
0_K(D_K
1XKp%VKpGYK
3_KDI_K|I_K
3_KxV_K
?_KDO^KD
B_K<B_KlB_K
C_KDC_K|C_K
E_K$E_K@E_K\E_KtE_K
E_K8F_KhF_K
F_K`G_K
H_K@H_KhH_K
IWKd(YK
I_K(J_K
KWK$)YK
KYK84XK
K_KpK_K
L_K(M_K
L_K@L_KpL_K
N^Kl?YK
O_K V_K(V_K0V_K
P_K$P_K,P_K4P_K@P_K,U_KLP_KTP_K\P_KdP_KlP_KtP_KxP_K
Q_K Q_K,Q_K<Q_KDQ_KPQ_KXQ_K`Q_KhQ_KlQ_KtQ_K0Q_K|Q_K
R_K$R_K,R_K4R_K<R_KDR_KPR_K\R_KdR_KpR_KtR_KxR_K
S_K$S_K,S_K4S_K<S_KDS_KPS_K`S_KlS_KtS_K|S_K
T_K T_K,T_K8T_KDT_KTT_K`T_KlT_KxT_K
UK bWK
UK,HVK
UK4M[K4M[KT[WK
UK8+VK
UK<3WK
UK<5XK,
UK<HVK
UK<hVK
UKH/[K\
UKL&VK
UKP/[K
UKp(YK
UKpGYK
UKp]XK
U_K(U_K4U_K<U_KHU_KPU_KXU_KdU_KlU_KtU_K|U_K
U_K`Y_K
VK( VKh
VKh6[K
V_K '_K
WK0'VK('VK
WK<2WK
WKL5[K|
W_K<W_KPW_KX
XK$GVK
XK`1WK,1WKD
X_K,X_K
\KPO[Kpa[K
\WKTFVK
\WKtFVK
\_K$#VK
\_K$(XK
]K(ZWKdL[K
]Kl9_K
]XKh^XK
^KH%_K\D_K
^KlW_K4
^XKT_XK
^XK\_XK
_KDX_KXX_K
`VKx3XK<'VK
eXKh%XK
i]K m]K
jXK jXK
````

</details>

### `/usr/bin/systemd-nspawn`

<details><summary>新增 69 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/barrier.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/copy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/env-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fdset.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/in-addr-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/in-addr-util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/lockfile-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/rm-rf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/signal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/loopback-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-enumerator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-enumerate.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/nspawn/nspawn.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/base-filesystem.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/dev-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/machine-image.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/ptyfwd.c
````

</details>

### `/bin/systemctl`

<details><summary>新增 63 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/copy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/signal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/compress.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journal-file.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/mmap-cache.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/sd-journal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-login/sd-login.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/cgroup-show.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/conf-parser.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/dropin.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/install-printf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/install.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/logs-show.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/pager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/path-lookup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/spawn-ask-password-agent.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/systemctl/systemctl.c
````

</details>

### `/bin/udevadm`

<details><summary>新增 60 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/network-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-enumerator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-hwdb/sd-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-enumerate.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-monitor.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/architecture.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/condition.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/conf-parser.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/sysctl-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/net/ethtool-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/net/link-config.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-blkid.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-firmware.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-input_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-keyboard.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-kmod.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-net_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-net_setup_link.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-path_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-usb_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-ctrl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-node.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-rules.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm-monitor.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm-settle.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm-test.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm-trigger.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevadm.c
````

</details>

### `/usr/lib/libAppsMessaging.so`

<details><summary>新增 59 条字符串</summary>

````text
 VK< VKd VK
!VK0!VKL!VKd!VK
"VK0"VKT"VKt"VK
#VK@#VK\#VK|#VK
%VK,%VKL%VKl%VK
&VK(&VK
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/apps-messaging/0.0+gitAUTOINC+b43db74a8b-r0/git/code/src/hblm_debug.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/apps-messaging/0.0+gitAUTOINC+b43db74a8b-r0/git/code/src/hblm_msgtransp.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/apps-messaging/0.0+gitAUTOINC+b43db74a8b-r0/git/code/src/port/platform_linux.c
b43db74
cambody_changed_exposure_abortable
cambody_get_exposure_abortable_req
cambody_get_exposure_abortable_resp
camera_changed_SV_auto_max
camera_changed_SV_auto_min
camera_get_SV_auto_max_req
camera_get_SV_auto_max_resp
camera_get_SV_auto_min_req
camera_get_SV_auto_min_resp
camera_set_SV_auto_max_req
camera_set_SV_auto_max_resp
camera_set_SV_auto_min_req
camera_set_SV_auto_min_resp
config_changed_VideoLiveViewOverlay
config_changed_eshutter
config_changed_power_from_usb
config_get_VideoLiveViewOverlay_req
config_get_VideoLiveViewOverlay_resp
config_get_eshutter_req
config_get_eshutter_resp
config_get_power_from_usb_req
config_get_power_from_usb_resp
config_set_VideoLiveViewOverlay_req
config_set_VideoLiveViewOverlay_resp
config_set_eshutter_req
config_set_eshutter_resp
config_set_power_from_usb_req
config_set_power_from_usb_resp
image_enter_fsync_listener_state_req
image_enter_fsync_listener_state_resp
image_sensor_eshutter_capture_req
image_sensor_eshutter_capture_resp
pwrctrl_emergency_shutdown_event
suc_changed_expose_seq_enabled
suc_changed_ext_power
suc_changed_selectable_cameras
suc_changed_usb_max_current
suc_enable_exposure_seq_req
suc_enable_exposure_seq_resp
suc_get_expose_seq_enabled_req
suc_get_expose_seq_enabled_resp
suc_get_ext_power_req
suc_get_ext_power_resp
suc_get_selectable_cameras_req
suc_get_selectable_cameras_resp
suc_get_usb_max_current_req
suc_get_usb_max_current_resp
suc_set_usb_max_current_req
suc_set_usb_max_current_resp
````

</details>

### `/lib/systemd/systemd-udevd`

<details><summary>新增 58 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd-network/network-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-enumerator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-hwdb/sd-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-enumerate.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-monitor.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/architecture.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/condition.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/conf-parser.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/dev-setup.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/sysctl-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/net/ethtool-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/net/link-config.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-blkid.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-firmware.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-input_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-keyboard.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-kmod.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-net_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-net_setup_link.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-path_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-builtin-usb_id.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-ctrl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-node.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-rules.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udev-watch.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/udev/udevd.c
````

</details>

### `/bin/journalctl`

<details><summary>新增 55 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/replace-var.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/sigbus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/catalog.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/compress.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journal-file.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journal-vacuum.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journal-verify.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journalctl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/mmap-cache.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/sd-journal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/logs-show.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/pager.c
````

</details>

### `/usr/bin/bodystate-daemon`

<details><summary>新增 45 条字符串</summary>

````text
11InputDevice
11PowerButton
ErrorCode: 
Failed to open 
Failed to open file:
Failed to write. errno: 
Ignoring change to video mode since we are in tethered mode
InputDevice
Non complete input event read, closing
Opened input device 
PowerButton
_ZN10QByteArray11fromRawDataEPKci
_ZN10UdevClient21buttonDeviceAvailableERK7QString
_ZN11CameraProxy16setLiveViewStateEb
_ZN11InputDevice11setFilenameERK7QString
_ZN11InputDevice12onInputEventEv
_ZN11InputDevice16staticMetaObjectE
_ZN11InputDevice17newEventsReceivedERK10QByteArray
_ZN11PowerButton13onInputEventsERK10QByteArray
_ZN11PowerButton16staticMetaObjectE
_ZN11PowerButton8powerOffEv
_ZN11PowerButton9onTimeoutEv
_ZN18SystemManagerProxy18camera_modeChangedE16hblm_camera_mode
_ZN18SystemManagerProxy19system_stateChangedE17hblm_system_state
_ZN18SystemManagerProxy20tethered_modeChangedE18hblm_tethered_mode
_ZN5QFileC1ERK7QStringP7QObject
_ZN6QTimer11setIntervalEi
_ZN6QTimer5startEv
_ZN8bodysync22functionOnOffLongPressEv
_ZNK9QIODevice11errorStringEv
_ZNK9QIODevice6isOpenEv
_ZTV11InputDevice
_ZTV11PowerButton
attempts left: 
buttonDeviceAvailable
camera_mode
dev_node
events
gpio_keys
newEventsReceived
onInputEvents
onTimeout
powerOff
setFilename
strncmp
````

</details>

### `/usr/bin/busctl`

<details><summary>新增 45 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/xml.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-dump.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/busctl-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/busctl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/pager.c
````

</details>

### `/lib/systemd/systemd-bus-proxyd`

<details><summary>新增 44 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/capability.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/xml.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/bus-proxyd.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/bus-xml-policy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/driver.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/proxy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/synthesize.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
````

</details>

### `/lib/systemd/systemd-journald`

<details><summary>新增 43 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fdset.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/rm-rf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/sigbus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/compress.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journal-file.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journal-vacuum.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-console.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-kmsg.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-native.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-rate-limit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-server.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-stream.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-syslog.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald-wall.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/journald.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/mmap-cache.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/journal/sd-journal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/conf-parser.c
````

</details>

### `/usr/bin/systemd-run`

<details><summary>新增 43 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/calendarspec.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/signal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/run/run.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/ptyfwd.c
````

</details>

### `/usr/bin/systemd-stdio-bridge`

<details><summary>新增 43 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/xml.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/bus-xml-policy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/driver.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/proxy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/stdio-bridge.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bus-proxyd/synthesize.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
````

</details>

### `/usr/bin/systemd-cgls`

<details><summary>新增 42 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/cgls/cgls.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/cgroup-show.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/pager.c
````

</details>

### `/usr/lib/libQt5Core.so.5.5.1`

<details><summary>新增 42 条字符串</summary>

````text
':K -:K
(:K`-:K0
2>KP4>K
93Kh@3K
@Kx13K
AK b"K8c"K
AK(M!KlM!K,M!KLM!K
AK(P?K`P?K0
AK82>Kp3>K
AKDb"K
AKX(:Kh+:KX8
AKl'AK
AKl'AKhK3K
AKtb"K
J4H3KD
J8N?KP
JH0:KT
JHP?K(
J`.:K0
Jl'AK 
Jl'AKxK?K@L?K
K?K8K?K
Kl'AKH
Kl'AKP
Kl'AKPF?K
Kl'AKhg?K
Kl'AKp
Kl'AKpi?K
Kl'AKxI3K8J3K4B
Q?K0Q?KH
R?KPS?K
S?K8T?K,
b"KLd"K
d"Kde"K
f?KHf?K
i"KXf"K 
i?Kxj?K
j?K@k?K(
l'AKpQ?K8R?Kx
o"K0t"K
x"K4y"K8
z"K0z"K
````

</details>

### `/lib/systemd/systemd-fsck`

<details><summary>新增 40 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/fsck/fsck.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
````

</details>

### `/lib/systemd/systemd-hostnamed`

<details><summary>新增 40 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/env-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/hostname/hostnamed.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
````

</details>

### `/lib/systemd/systemd-timedated`

<details><summary>新增 40 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/clock-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/timedate/timedated.c
````

</details>

### `/usr/bin/hostnamectl`

<details><summary>新增 40 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/hostname/hostnamectl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
````

</details>

### `/usr/bin/timedatectl`

<details><summary>新增 39 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/pager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/timedate/timedatectl.c
````

</details>

### `/lib/systemd/systemd-cgroups-agent`

<details><summary>新增 38 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/cgroups-agent/cgroups-agent.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
````

</details>

### `/lib/systemd/systemd-initctl`

<details><summary>新增 38 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/audit.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/bus-label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/initctl/initctl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-bloom.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-container.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-control.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-convenience.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-creds.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-error.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-gvariant.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-internal.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-introspect.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-kernel.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-match.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-objects.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-signature.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-slot.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/bus-track.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-bus/sd-bus.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-daemon/sd-daemon.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/bus-util.c
````

</details>

### `/usr/bin/system-manager`

<details><summary>新增 36 条字符串</summary>

````text
/lib/firmware/hbl/farm/bootimage_even-victory.bin
10LinkStatus
1onLinkStatusChanged()
2statusChanged()
LinkStatus
Run in CFV camera mode.
Switch%1
Temporary inhibit PL power down on CFV due to HW issues
_Z17qRegisterMetaTypeI13QDBusArgumentEiPKcPT_N9QtPrivate21MetaTypeDefinedHelperIS3_Xaasr12QMetaTypeId2IS3_E7DefinedntsrS8_9IsBuiltInEE11DefinedTypeE
_ZN10LinkStatus13statusChangedEv
_ZN10LinkStatus16staticMetaObjectE
_ZN10VideoProxy23videostream_modeChangedE16hblm_videostream
_ZN13SystemManager19uiPowerStateChangedEv
_ZN13SystemManager21onUiPowerStateChangedEv
_ZN3Bus10sucServiceEv
_ZN3Bus19linkStatusInterfaceEv
_ZN3Bus7sucPathEv
_ZN4DBus21onUiPowerStateChangedEv
_ZN6QTimer10singleShotEiPK7QObjectPKc
_ZN8SucProxy23cambody_attachedChangedEb
_ZN9DBusProxy16createMethodCallERK7QString
_ZN9QMetaType25registerNormalizedTypedefERK10QByteArrayi
_ZNK12QDBusMessage12errorMessageEv
_ZNK12QDBusMessage4typeEv
_ZNK15QDBusConnection4callERK12QDBusMessageN5QDBus8CallModeEi
_ZTV10LinkStatus
fhStatus
firmwareVersion
firmware_version
forcing to standby
in session, self timer
onUiPowerStateChanged
short exposure, no PL power down
uiPowerState
uiPowerStateChanged
umbrella-prod-test_v1.0.0-14-g71ecc5e
````

</details>

### `/bin/networkctl`

<details><summary>新增 28 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/in-addr-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/in-addr-util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/socket-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/verbs.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-hwdb/sd-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-network/sd-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkctl.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/pager.c
````

</details>

### `/lib/systemd/systemd-shutdown`

<details><summary>新增 26 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/rm-rf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/terminal-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/killall.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/shutdown.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/core/umount.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-enumerator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-enumerate.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/base-filesystem.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/switch-root.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/watchdog.c
````

</details>

### `/lib/systemd/system-generators/systemd-gpt-auto-generator`

<details><summary>新增 21 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/gpt-auto-generator/gpt-auto-generator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-enumerator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/generator.c
````

</details>

### `/lib/systemd/systemd-timesyncd`

<details><summary>新增 21 条字符串</summary>

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/capability.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/socket-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-network/sd-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-resolve/sd-resolve.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/conf-parser.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/timesync/timesyncd-conf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/timesync/timesyncd-manager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/timesync/timesyncd-server.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/timesync/timesyncd.c
````

</details>

### `/bin/systemd-tmpfiles`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/btrfs-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/copy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/rm-rf.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/specifier.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/tmpfiles/tmpfiles.c
````

### `/lib/systemd/systemd-networkd-wait-online`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-network/sd-network.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-wait-online-link.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-wait-online-manager.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/network/networkd-wait-online.c
````

### `/usr/lib/libQt5Network.so.5.5.1`

````text
:}K -}K
AKl'AK
AKl'AK$
AKl'AK8
G}KdH}K 
Jl'AK(h
K(k~K@
K(v~K@
K0)|K0
Kl'AK(
Kl'AK8
Kl'AKhw
Kl'AKt
fzK,f}Klf}K 
qzKlszK 
yKHezKTfzK
zKl'AK\G
|Kl'AKd
}Kl'AKHQ
~Klj~K k~K
````

### `/lib/systemd/systemd-bootchart`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/cgroup-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/memfd-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bootchart/bootchart.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bootchart/store.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bootchart/svg.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/conf-parser.c
/proc/vmstat
0123456789abcdefsafe_atolli
CODE_FILE=/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/bootchart/bootchart.c
access
fd_warn_permissions
````

### `/usr/bin/msg2dbus`

````text
%s: could not register object on path: /
VideoLiveViewOverlay
_ZN10SucHandler22cambodyAttachedChangedEb
_ZN13MetadataProxy15requestMetadataE18hblm_metadata_type9hblm_sinktjRK21hblm_image_dimensionsRK22hblm_xyz_to_rgb_matrixRK20hblm_as_shot_neutraljjjjjjjiRK13hblm_rationalRK23hblm_metadata_rectanglejj
_ZN14CamBodyHandler17onAttachedChangedEb
_ZN3Bus7rawPathEv
_ZN5QListIiED1Ev
_ZN5QListIiED2Ev
_ZN8RawProxy10rawMessageERK7QStringRK10QByteArray
cambodyAttachedChanged
digitalGain
enable_exposure_seq
eshutter
expose_seq_enabled
exposure_abortable
ext_power
onAttachedChanged
power_from_usb
usb_max_current
````

### `/lib/libudev.so.1.6.4`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-enumerator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/device-private.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-device/sd-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-hwdb/sd-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-device.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-enumerate.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-hwdb.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev-monitor.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libudev/libudev.c
````

### `/usr/lib/libQt5Sql.so.5.5.1`

````text
!cK`)cK
&cK|(cK
)cK`)cK
,dKD,dK 
/bKP/bK0/bK8/bK(
0bK@0bK 
8dK49dKd
DcK0GcK<RcK
bK0BcK
bK@/bKH/bKX/bK`/bK
bK\)cK
bKh/bKl/bKp/bKt/bKx/bK|/bK
bKl'AK<
bK|McKL
cK<AdK
cKD4dK
cKx)cK
dK,-dK
````

### `/bin/systemd-sysusers`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/conf-files.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/copy.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mempool.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-id128/sd-id128.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/specifier.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/uid-range.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/sysusers/sysusers.c
````

### `/lib/systemd/system-generators/systemd-fstab-generator`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/fileio.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/label.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/mkdir.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/path-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/process-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/strv.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/unit-name.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/utf8.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/fstab-generator/fstab-generator.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/dropin.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/fstab-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/fstab-util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/shared/generator.c
````

### `/usr/lib/libQt5DBus.so.5.5.1`

````text
3SK\BSK
AKl'AKX
Kl'AKP
Kl'AKp
OKl'AK
PK()PK
SK WSK
SK$WSKTWSK
SKH+SK
SKtXSK
SKxUSK
SSKLTSK0\NKd\NK 
USK(VSK
WSKL\SK
bSK`bSK
````

### `/usr/lib/libnss_myhostname.so.2`

````text
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hashmap.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/hostname-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/in-addr-util.h
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/log.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/prioq.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/time-util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/basic/util.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-event/sd-event.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/local-addresses.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-socket.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/netlink-types.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/rtnl-message.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/libsystemd/sd-netlink/sd-netlink.c
/home/jenkins/yocto/qt5/hbl_victory/build_jethro/tmp/work/cortexa9hf-vfp-neon-poky-linux-gnueabi/systemd/1_225+gitAUTOINC+e1439a1472-r0/git/src/nss-myhostname/nss-myhostname.c
````

## Scripts & Config

共 4 个脚本/配置变更, 126 行 unified diff（context=3, 预算上限 2000 行）。

### `/lib/firmware/hbl/cambody-h6/cambody_upgrade.sh`

11 行

````diff
--- a//lib/firmware/hbl/cambody-h6/cambody_upgrade.sh
+++ b//lib/firmware/hbl/cambody-h6/cambody_upgrade.sh
@@ -234,7 +234,7 @@
 }
 
 GetCambodyAttached () {
-  VAL=`busctl get-property com.hasselblad.suc /cambody com.hasselblad.cambody cambody_attached | awk '{print ($2)}'`
+  VAL=`busctl get-property com.hasselblad.suc /suc com.hasselblad.suc cambody_attached | awk '{print ($2)}'`
   if [ $? -eq 0 ] ; then
     if [ $VAL = "true" ]; then
       return 1
````

### `/usr/bin/hbl-collect-logs.sh`

13 行

````diff
--- a//usr/bin/hbl-collect-logs.sh
+++ b//usr/bin/hbl-collect-logs.sh
@@ -21,8 +21,8 @@
 dbus-send --system --print-reply --dest=com.hasselblad.config /config org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.config" > ${LOG_DIR}/configstore.properties
 dbus-send --system --print-reply --dest=com.hasselblad.systemmanager / org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.systemmanager" > ${LOG_DIR}/systemmanager-daemon.properties
 dbus-send --system --print-reply --dest=com.hasselblad.systemmanager /status org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.systemmanager" ${LOG_DIR}/systemmanager-daemon.status.properties
-dbus-send --system --print-reply --dest=com.hasselblad.farm / org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.farm" > ${LOG_DIR}/msg2dbus-farm.properties
-dbus-send --system --print-reply --dest=com.hasselblad.suc / org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.suc" > ${LOG_DIR}/msg2dbus-suc.configstore.properties
+dbus-send --system --print-reply --dest=com.hasselblad.farm /farm org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.farm" > ${LOG_DIR}/msg2dbus-farm.properties
+dbus-send --system --print-reply --dest=com.hasselblad.suc /suc org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.suc" > ${LOG_DIR}/msg2dbus-suc.configstore.properties
 dbus-send --system --print-reply --dest=com.hasselblad.farm /pwrctrl org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.pwrctrl" > ${LOG_DIR}/msg2dbus-pwrctrl.properties
 dbus-send --system --print-reply --dest=com.hasselblad.upgrade / org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.upgrade" > ${LOG_DIR}/upgrade-daemon.properties
 dbus-send --system --print-reply --dest=com.hasselblad.storage / org.freedesktop.DBus.Properties.GetAll string:"com.hasselblad.storage" > ${LOG_DIR}/storage-daemon.properties
````

### `/usr/bin/program_nodes.sh`

74 行

````diff
--- a//usr/bin/program_nodes.sh
+++ b//usr/bin/program_nodes.sh
@@ -18,12 +18,33 @@
     busctl set-property com.hasselblad.upgrade / com.hasselblad.upgrade upgradeProgress i ${1} > /dev/null 2>&1
 }
 
+check_usb_connected() {
+    USB_CONNECTED=$(busctl get-property com.hasselblad.suc /suc com.hasselblad.suc usb_vbus_present)
+    CHECK_USB=$(busctl get-property com.hasselblad.upgrade / com.hasselblad.upgrade checkUsbConnected)
+    echo "USB_CONNECTED: $USB_CONNECTED"
+    echo "CHECK_USB: $CHECK_USB"
+    if [[ "$CHECK_USB" == "b true" && "$USB_CONNECTED" == "b true" ]]; then
+        return 1
+    fi
+    return 0
+}
+
 # update SUC
 update_suc() {
-    if [ $IS_WEDGE -eq 0 ]; then
+    if [ $IS_WEDGE -eq 0 -o $IS_IDUN -eq 0 ]; then
         echo "Enable autostart before programming suc"
+        busctl set-property com.hasselblad.suc /suc com.hasselblad.suc autostart b true
+        # Before 2017-05-03 the path was just "/", to be able to upgrade from releases before this date
+        # with automatic reboot an additional command using the old path is executed.
         busctl set-property com.hasselblad.suc / com.hasselblad.suc autostart b true
         sleep 1
+    fi
+
+    check_usb_connected
+    status=$?
+    if [ $status -eq 1 ]; then
+        echo "USB must NOT be connected when flashing SUC! Aborting"
+        return 1
     fi
 
     echo "Start upgrading SUC"
@@ -132,20 +153,25 @@
 
 # update FARM
 update_farm() {
-    if [ $IS_WEDGE -eq 0 -o $IS_IDUN -eq 0 ]; then
+    if [ $IS_WEDGE -eq 0 ]; then
         echo "Start upgrading FARM (Wedge/Idun)"
         EVEN_FILE=$2${FW_DIR}/farm/bootimage_even-wedge.bin
         ODD_FILE=$2${FW_DIR}/farm/bootimage_odd-wedge.bin
-    else
-        if [ $IS_ALBATROSS -eq 0 ]; then
-            echo "Start upgrading FARM (Victory Albatross)"
-            EVEN_FILE=$2${FW_DIR}/farm/bootimage_even-albatross.bin
-            ODD_FILE=$2${FW_DIR}/farm/bootimage_odd-albatross.bin
-        else
-            echo "Start upgrading FARM (Victory)"
-            EVEN_FILE=$2${FW_DIR}/farm/bootimage_even.bin
-            ODD_FILE=$2${FW_DIR}/farm/bootimage_odd.bin
-        fi
+    elif [ $IS_ALBATROSS -eq 0 ]; then
+        echo "Start upgrading FARM (Albatross)"
+        EVEN_FILE=$2${FW_DIR}/farm/bootimage_even-albatross.bin
+        ODD_FILE=$2${FW_DIR}/farm/bootimage_odd-albatross.bin
+    elif [ $IS_IDUN -eq 0 ]; then
+        echo "Start upgrading FARM (Idun)"
+        EVEN_FILE=$2${FW_DIR}/farm/bootimage_even-idun.bin
+        ODD_FILE=$2${FW_DIR}/farm/bootimage_odd-idun.bin
+    elif [ $IS_VICTORY -eq 0 ]; then
+        echo "Start upgrading FARM (Victory)"
+        EVEN_FILE=$2${FW_DIR}/farm/bootimage_even-victory.bin
+        ODD_FILE=$2${FW_DIR}/farm/bootimage_odd-victory.bin
+    else
+	echo "Unknown FARM image"
+	exit 1
     fi
 
     ${1}usr/bin/program_farm.sh ${EVEN_FILE} ${ODD_FILE}
````

### `/usr/bin/sysmon.sh`

28 行

````diff
--- a//usr/bin/sysmon.sh
+++ b//usr/bin/sysmon.sh
@@ -10,11 +10,11 @@
 KERNEL=$(uname -a)
 RELEASE=$(cat /etc/os-release)
 
-SUC_APPMSG_VERSION="$(busctl get-property com.hasselblad.suc / com.hasselblad.linkstatus appsMessagingVersion |  awk '{ print $2 }')"
-SUC_FW_VERSION="$(busctl get-property com.hasselblad.suc / com.hasselblad.linkstatus firmwareVersion |  awk '{ print $5 }')"
-FARM_APPMSG_VERSION="$(busctl get-property com.hasselblad.farm / com.hasselblad.linkstatus appsMessagingVersion |  awk '{ print $2 }')"
-FARM_FW_VERSION="$(busctl get-property com.hasselblad.farm / com.hasselblad.linkstatus firmwareVersion |  awk '{ print $5 }')"
-FPGA_VERSION="$(busctl get-property com.hasselblad.farm / com.hasselblad.linkstatus firmwareVersion |  awk '{ print $8 }')"
+SUC_APPMSG_VERSION="$(busctl get-property com.hasselblad.suc /suc com.hasselblad.linkstatus appsMessagingVersion |  awk '{ print $2 }')"
+SUC_FW_VERSION="$(busctl get-property com.hasselblad.suc /suc com.hasselblad.linkstatus firmwareVersion |  awk '{ print $5 }')"
+FARM_APPMSG_VERSION="$(busctl get-property com.hasselblad.farm /farm com.hasselblad.linkstatus appsMessagingVersion |  awk '{ print $2 }')"
+FARM_FW_VERSION="$(busctl get-property com.hasselblad.farm /farm com.hasselblad.linkstatus firmwareVersion |  awk '{ print $5 }')"
+FPGA_VERSION="$(busctl get-property com.hasselblad.farm /farm com.hasselblad.linkstatus firmwareVersion |  awk '{ print $8 }')"
 PWC_FW_VERSION="$(busctl get-property com.hasselblad.pwrctrl /pwrctrl com.hasselblad.linkstatus firmwareVersion |  awk '{ print $2 }')"
 PWC_APPMSG_VERSION="$(busctl get-property com.hasselblad.pwrctrl /pwrctrl com.hasselblad.linkstatus appsMessagingVersion |  awk '{ print $2 }')"
 
@@ -59,7 +59,7 @@
 let USED_DATA_PERC=(100*${USED_SIZE_DATA})/${TOTAL_SIZE_DATA}
 
 let IMX_TEMPERATURE=$(cat /sys/devices/virtual/thermal/thermal_zone0/temp)/1000
-let FPGA_TEMPERATURE=$(busctl call com.hasselblad.farm / com.hasselblad.farm readAdc | awk '{ print $5 }')/1000
+let FPGA_TEMPERATURE=$(busctl call com.hasselblad.farm /farm com.hasselblad.farm readAdc | awk '{ print $5 }')/1000
 let SPC_TEMPERATURE=$(busctl call com.hasselblad.pwrctrl /pwrctrl com.hasselblad.pwrctrl readTemperature | awk '{ print $5 }')
 
 #Show system data
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（2342 行）</summary>

| Path | Status | Old Size | New Size | Δ | Tree |
|---|---|---|---|---|---|
| `/bin/busybox.nosuid` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 552.0 KB | 552.0 KB | +0 B | rootfs |
| `/bin/busybox.suid` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 52.9 KB | 52.9 KB | +0 B | rootfs |
| `/bin/journalctl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 406.3 KB | 406.3 KB | +0 B | rootfs |
| `/bin/kmod` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 109.5 KB | 109.5 KB | +0 B | rootfs |
| `/bin/login.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.7 KB | 53.7 KB | +0 B | rootfs |
| `/bin/mount.util-linux` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.4 KB | 33.4 KB | +0 B | rootfs |
| `/bin/networkctl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 377.8 KB | 377.8 KB | +0 B | rootfs |
| `/bin/su.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.5 KB | 44.5 KB | +0 B | rootfs |
| `/bin/systemctl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 542.9 KB | 542.9 KB | +0 B | rootfs |
| `/bin/systemd-ask-password` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.8 KB | 37.8 KB | +0 B | rootfs |
| `/bin/systemd-escape` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/bin/systemd-machine-id-setup` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/bin/systemd-notify` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.8 KB | 29.8 KB | +0 B | rootfs |
| `/bin/systemd-sysusers` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.8 KB | 81.8 KB | +0 B | rootfs |
| `/bin/systemd-tmpfiles` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 105.9 KB | 105.9 KB | +0 B | rootfs |
| `/bin/systemd-tty-ask-password-agent` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.8 KB | 49.8 KB | +0 B | rootfs |
| `/bin/udevadm` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 357.9 KB | 357.9 KB | +0 B | rootfs |
| `/boot/devicetree-zImage-imx6q-hbl-idun.dtb` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.5 KB | 37.2 KB | -332 B | rootfs |
| `/boot/devicetree-zImage-imx6q-hbl-victory.dtb` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.5 KB | 37.5 KB | +0 B | rootfs |
| `/boot/devicetree-zImage-imx6q-hbl-wedge.dtb` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.9 KB | 39.9 KB | +0 B | rootfs |
| `/boot/zImage-3.14.28-1.0.0_ga+yocto+g8f5ca40` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.6 MB | — | -3.6 MB | rootfs |
| `/boot/zImage-3.14.28-1.0.0_ga+yocto+g99ca806` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.6 MB | +3.6 MB | rootfs |
| `/etc/apm/apmd_proxy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/etc/asound.conf` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 2.9 KB | — | -2.9 KB | rootfs |
| `/etc/asound.state` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.7 KB | 19.7 KB | +0 B | rootfs |
| `/etc/avahi/avahi-daemon.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/etc/avahi/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/etc/build` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/etc/busybox.links.nosuid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/etc/busybox.links.suid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 91 B | 91 B | +0 B | rootfs |
| `/etc/dbus-1/session.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/etc/dbus-1/system.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/etc/dbus-1/system.d/avahi-dbus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.bodysync.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 440 B | 440 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.cambody.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 438 B | 438 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.camera.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 436 B | 436 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.config.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 436 B | 436 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.error.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 434 B | 434 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.farm.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 432 B | 432 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.image.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 434 B | 434 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.jpeg.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 432 B | 432 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.lens.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 432 B | 432 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.metadata.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 440 B | 440 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.mobile.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 435 B | 435 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.phocus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 436 B | 436 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.pwrctrl.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 438 B | 438 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.storage.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 438 B | 438 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.suc.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 430 B | 430 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.sutest.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 436 B | 436 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.sutestgui.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 442 B | 442 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.systemmanager.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 450 B | 450 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.ui.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 428 B | 428 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.upgrade.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 438 B | 438 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.usbif.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 434 B | 434 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/com.hasselblad.video.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 434 B | 434 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/dbus-wpa_supplicant.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/etc/dbus-1/system.d/org.freedesktop.hostname1.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 947 B | 947 B | +0 B | rootfs |
| `/etc/dbus-1/system.d/org.freedesktop.network1.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/etc/dbus-1/system.d/org.freedesktop.systemd1.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/etc/dbus-1/system.d/org.freedesktop.timedate1.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 947 B | 947 B | +0 B | rootfs |
| `/etc/default/apmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 216 B | 216 B | +0 B | rootfs |
| `/etc/default/postinst` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 52 B | 52 B | +0 B | rootfs |
| `/etc/default/ssh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69 B | 69 B | +0 B | rootfs |
| `/etc/default/usbd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | rootfs |
| `/etc/default/volatiles/99_dbus` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48 B | 48 B | +0 B | rootfs |
| `/etc/default/volatiles/99_sshd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 75 B | 75 B | +0 B | rootfs |
| `/etc/default/volatiles/99_wpa_supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 46 B | 46 B | +0 B | rootfs |
| `/etc/filesystems` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/etc/fonts/conf.d/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 978 B | 978 B | +0 B | rootfs |
| `/etc/fonts/fonts.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/etc/fstab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 711 B | 711 B | +0 B | rootfs |
| `/etc/fw_env.config` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 866 B | 866 B | +0 B | rootfs |
| `/etc/group` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 705 B | 705 B | +0 B | rootfs |
| `/etc/group-` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 682 B | 682 B | +0 B | rootfs |
| `/etc/gshadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 592 B | 592 B | +0 B | rootfs |
| `/etc/gshadow-` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 572 B | 572 B | +0 B | rootfs |
| `/etc/host.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26 B | 26 B | +0 B | rootfs |
| `/etc/hostapd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 288 B | 288 B | +0 B | rootfs |
| `/etc/hostapd/simple-ac.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 288 B | 288 B | +0 B | rootfs |
| `/etc/hostapd/simple-g.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 213 B | 213 B | +0 B | rootfs |
| `/etc/hostapd/simple-n.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 154 B | 154 B | +0 B | rootfs |
| `/etc/hostname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12 B | 12 B | +0 B | rootfs |
| `/etc/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44 B | 44 B | +0 B | rootfs |
| `/etc/inputrc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/etc/issue` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 87 B | 87 B | +0 B | rootfs |
| `/etc/issue.net` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/etc/ld.so.cache` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.7 KB | 9.7 KB | +0 B | rootfs |
| `/etc/ld.so.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | rootfs |
| `/etc/libnl/classid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/etc/libnl/pktloc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/etc/login.defs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.7 KB | 10.7 KB | +0 B | rootfs |
| `/etc/machine-id` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | rootfs |
| `/etc/mke2fs.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 956 B | 956 B | +0 B | rootfs |
| `/etc/modprobe.d/audio.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 175 B | 175 B | +0 B | rootfs |
| `/etc/modprobe.d/autofs.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18 B | 18 B | +0 B | rootfs |
| `/etc/modprobe.d/bodystate.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67 B | 67 B | +0 B | rootfs |
| `/etc/modprobe.d/mipi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | rootfs |
| `/etc/modprobe.d/spi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18 B | 18 B | +0 B | rootfs |
| `/etc/modprobe.d/touch.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | rootfs |
| `/etc/modprobe.d/usb.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44 B | 44 B | +0 B | rootfs |
| `/etc/modprobe.d/wifi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19 B | 19 B | +0 B | rootfs |
| `/etc/modules-load.d/galcore.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8 B | 8 B | +0 B | rootfs |
| `/etc/motd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | rootfs |
| `/etc/network/if-pre-up.d/wpa-supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/etc/nsswitch.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 465 B | 465 B | +0 B | rootfs |
| `/etc/os-release` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 96 B | 96 B | +0 B | rootfs |
| `/etc/passwd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/etc/passwd-` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/etc/profile` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 934 B | 934 B | +0 B | rootfs |
| `/etc/protocols` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/etc/rpc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 895 B | 895 B | +0 B | rootfs |
| `/etc/rpm/platform` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 543 B | 543 B | +0 B | rootfs |
| `/etc/rpm/sysinfo/Dirnames` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2 B | 2 B | +0 B | rootfs |
| `/etc/securetty` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/etc/services` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.2 KB | 19.2 KB | +0 B | rootfs |
| `/etc/shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 775 B | 775 B | +0 B | rootfs |
| `/etc/shadow-` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 639 B | 639 B | +0 B | rootfs |
| `/etc/shells` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/etc/skel/.bashrc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 410 B | 410 B | +0 B | rootfs |
| `/etc/skel/.profile` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 152 B | 152 B | +0 B | rootfs |
| `/etc/ssh/moduli` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 293.3 KB | 293.3 KB | +0 B | rootfs |
| `/etc/ssh/ssh_config` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/etc/ssh/sshd_config` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/etc/ssh/sshd_config_readonly` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/etc/systemd/bootchart.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 720 B | 720 B | +0 B | rootfs |
| `/etc/systemd/journald.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/etc/systemd/network/bridge.netdev` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30 B | 30 B | +0 B | rootfs |
| `/etc/systemd/network/bridge.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67 B | 67 B | +0 B | rootfs |
| `/etc/systemd/network/eth.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67 B | 67 B | +0 B | rootfs |
| `/etc/systemd/network/usb.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67 B | 67 B | +0 B | rootfs |
| `/etc/systemd/system.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/etc/systemd/timesyncd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 587 B | 587 B | +0 B | rootfs |
| `/etc/systemd/user.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/etc/timestamp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15 B | 15 B | +0 B | rootfs |
| `/etc/tmpfiles.d/00-create-volatile.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 225 B | 225 B | +0 B | rootfs |
| `/etc/udev/rules.d/fb.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198 B | 198 B | +0 B | rootfs |
| `/etc/udev/rules.d/touchscreen.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 855 B | 855 B | +0 B | rootfs |
| `/etc/udev/udev.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49 B | 49 B | +0 B | rootfs |
| `/etc/version` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15 B | 15 B | +0 B | rootfs |
| `/etc/wpa_supplicant.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 113 B | 113 B | +0 B | rootfs |
| `/etc/xdg/weston/weston.ini` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 537 B | 537 B | +0 B | rootfs |
| `/lib/depmod.d/search.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 71 B | 71 B | +0 B | rootfs |
| `/lib/firmware/LICENCE.broadcom_bcm43xx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/lib/firmware/brcm/brcmfmac4356-pcie.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 608.4 KB | 608.4 KB | +0 B | rootfs |
| `/lib/firmware/brcm/brcmfmac4356-pcie.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/1601253_PVF022.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/CBC_1600583_PVF-2_0_0.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 381.5 KB | 381.5 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/CBM_1601244_PVF-0_2_3.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 429.0 KB | 429.0 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/cambody_upgrade.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.8 KB | 11.8 KB | -8 B | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-albatross-v1.16.0-5531-3bcbd3c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 MB | — | -3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-albatross-v1.17.0-6994-055987e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-idun-v1.17.0-1281-38a7607.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-v1.16.0-7613-3bcbd3c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 MB | — | -3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-victory-v1.17.0-9077-055987e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-wedge-v1.16.0-5667-3bcbd3c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 MB | — | -3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-wedge-v1.17.0-7131-055987e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-albatross-v1.16.0-5531-3bcbd3c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 MB | — | -3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-albatross-v1.17.0-6994-055987e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-idun-v1.17.0-1281-38a7607.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-v1.16.0-7613-3bcbd3c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 MB | — | -3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-victory-v1.17.0-9077-055987e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-wedge-v1.16.0-5667-3bcbd3c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 MB | — | -3.7 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-wedge-v1.17.0-7131-055987e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 MB | +3.7 MB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_albatross-v0.0-6878-c5080d4.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 144.0 KB | — | -144.0 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_albatross-v0.0-8343-62f6f2c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.4 KB | +155.4 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_cfv-v0.0-6878-c5080d4.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 144.0 KB | — | -144.0 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_cfv-v0.0-8343-62f6f2c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.4 KB | +155.4 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_victory-v0.0-6878-c5080d4.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 144.0 KB | — | -144.0 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_victory-v0.0-8343-62f6f2c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.4 KB | +155.4 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_wedge-v0.0-6878-c5080d4.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 144.0 KB | — | -144.0 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_wedge-v0.0-8343-62f6f2c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.4 KB | +155.4 KB | rootfs |
| `/lib/firmware/hbl/power-control/power-control-v1.16.0-7324-ecf0ec7.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 45.9 KB | — | -45.9 KB | rootfs |
| `/lib/firmware/hbl/power-control/power-control-v1.17.0-8788-df0c369.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 46.3 KB | +46.3 KB | rootfs |
| `/lib/firmware/hbl/su-control/camera-control-v1.16.0-7495-0624783.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 208.8 KB | — | -208.8 KB | rootfs |
| `/lib/firmware/hbl/su-control/camera-control-v1.17.0-8973-54d4145.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 213.9 KB | +213.9 KB | rootfs |
| `/lib/firmware/hbl/su-control/cfv-control-v1.16.0-7495-0624783.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 185.4 KB | — | -185.4 KB | rootfs |
| `/lib/firmware/hbl/su-control/su-control-v1.16.0-7495-0624783.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 359.6 KB | — | -359.6 KB | rootfs |
| `/lib/firmware/hbl/su-control/su-control-v1.17.0-8973-54d4145.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 365.2 KB | +365.2 KB | rootfs |
| `/lib/firmware/test/brcm/brcmfmac4356-pcie.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 592.5 KB | 592.5 KB | +0 B | rootfs |
| `/lib/firmware/test/brcm/brcmfmac4356-pcie.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/lib/firmware/vpu/vpu_fw_imx6q.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 248.0 KB | 248.0 KB | +0 B | rootfs |
| `/lib/ld-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 132.4 KB | 132.4 KB | +0 B | rootfs |
| `/lib/libBrokenLocale-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/lib/libanl-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.6 KB | 9.6 KB | +0 B | rootfs |
| `/lib/libblkid.so.1.1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 210.9 KB | 210.9 KB | +0 B | rootfs |
| `/lib/libc-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/lib/libcap.so.2.24` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.3 KB | 14.3 KB | +0 B | rootfs |
| `/lib/libcom_err.so.2.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.4 KB | 10.4 KB | +0 B | rootfs |
| `/lib/libcrypt-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 31.0 KB | 31.0 KB | +0 B | rootfs |
| `/lib/libcrypto.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | rootfs |
| `/lib/libdl-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/lib/libe2p.so.2.3` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 24.2 KB | 24.2 KB | +0 B | rootfs |
| `/lib/libext2fs.so.2.4` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 222.1 KB | 222.1 KB | +0 B | rootfs |
| `/lib/libgcc_s.so.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 113.3 KB | 113.3 KB | +0 B | rootfs |
| `/lib/libm-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 423.0 KB | 423.0 KB | +0 B | rootfs |
| `/lib/libmount.so.1.1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 234.9 KB | 234.9 KB | +0 B | rootfs |
| `/lib/libncursesw.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 157.9 KB | 157.9 KB | +0 B | rootfs |
| `/lib/libnsl-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.8 KB | 69.8 KB | +0 B | rootfs |
| `/lib/libnss_compat-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/libnss_dns-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.5 KB | 17.5 KB | +0 B | rootfs |
| `/lib/libnss_files-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.6 KB | 37.6 KB | +0 B | rootfs |
| `/lib/libpthread-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 92.8 KB | 92.8 KB | +0 B | rootfs |
| `/lib/libresolv-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 72.0 KB | 72.0 KB | +0 B | rootfs |
| `/lib/librt-2.22.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 27.7 KB | 27.7 KB | +0 B | rootfs |
| `/lib/libsysfs.so.2.0.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 28.2 KB | 28.2 KB | +0 B | rootfs |
| `/lib/libtinfo.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 118.7 KB | 118.7 KB | +0 B | rootfs |
| `/lib/libudev.so.1.6.4` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 108.4 KB | 108.4 KB | +0 B | rootfs |
| `/lib/libusb-1.0.so.0.1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 76.6 KB | 76.6 KB | +0 B | rootfs |
| `/lib/libutil-2.22.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/lib/libuuid.so.1.3.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.3 KB | 13.3 KB | +0 B | rootfs |
| `/lib/libz.so.1.2.8` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 74.1 KB | 74.1 KB | +0 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/extra/galcore.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 295.8 KB | — | -295.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/extcon/extcon-class.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 19.6 KB | — | -19.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/gpio/gpio-pca953x.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 17.4 KB | — | -17.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/i2c/i2c-dev.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 15.8 KB | — | -15.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/iio/industrialio.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 55.0 KB | — | -55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/iio/light/sfh7776.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.5 KB | — | -12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/input/misc/lis3dsh_acc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 28.7 KB | — | -28.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/input/touchscreen/atmel_mxt_ts.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 37.7 KB | — | -37.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/fpga_camera_mipi.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 19.3 KB | — | -19.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/ipu_bg_overlay_sdc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.5 KB | — | -12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/ipu_csi_enc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 9.5 KB | — | -9.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/ipu_fg_overlay_sdc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 14.4 KB | — | -14.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/ipu_prp_enc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.2 KB | — | -13.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/ipu_still.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.8 KB | — | -6.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/mxc_v4l2_capture.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 70.1 KB | — | -70.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/media/platform/mxc/capture/v4l2-int-device.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.0 KB | — | -6.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/misc/eeprom/at24.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 14.0 KB | — | -14.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/mtd/devices/m25p80.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.5 KB | — | -7.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/mtd/mtd.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 72.8 KB | — | -72.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/mtd/ofpart.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.1 KB | — | -6.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/mtd/spi-nor/spi-nor.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 29.3 KB | — | -29.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/net/mii.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.2 KB | — | -8.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/net/phy/libphy.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 43.9 KB | — | -43.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/net/usb/asix.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 48.8 KB | — | -48.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/net/usb/usbnet.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 55.0 KB | — | -55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/power/bq28z610_battery.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.8 KB | — | -13.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/spi/spi-bitbang.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.9 KB | — | -8.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/spi/spi-imx.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 23.2 KB | — | -23.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/usb/chipidea/ci_hdrc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 52.2 KB | — | -52.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/usb/chipidea/ci_hdrc_imx.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 19.9 KB | — | -19.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/usb/chipidea/usbmisc_imx.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 15.9 KB | — | -15.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/usb/core/usbcore.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 288.5 KB | — | -288.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/usb/host/ehci-hcd.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 95.9 KB | — | -95.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/drivers/video/backlight/l3ej03110a.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.0 KB | — | -12.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/fs/fat/fat.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 79.2 KB | — | -79.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/fs/fat/vfat.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 18.0 KB | — | -18.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/fs/nls/nls_cp437.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.6 KB | — | -7.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/fs/nls/nls_iso8859-1.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 5.9 KB | — | -5.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/net/802/stp.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 4.9 KB | — | -4.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/net/bridge/bridge.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 130.5 KB | — | -130.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/net/llc/llc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 11.1 KB | — | -11.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/codecs/snd-soc-tfa9882.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 5.1 KB | — | -5.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/codecs/snd-soc-tlv320aic3x.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 53.3 KB | — | -53.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/fsl/imx-pcm-dma.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 4.7 KB | — | -4.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/fsl/snd-soc-fsl-sai.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 17.5 KB | — | -17.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/fsl/snd-soc-fsl-ssi.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 29.1 KB | — | -29.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/fsl/snd-soc-hbl-tfa9882.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.9 KB | — | -7.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/fsl/snd-soc-hbl-tlv320aic3x.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.8 KB | — | -12.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/kernel/sound/soc/fsl/snd-soc-imx-audmux.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 14.5 KB | — | -14.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.alias` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.0 KB | — | -7.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.alias.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 10.4 KB | — | -10.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.builtin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 4.4 KB | — | -4.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.builtin.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 5.4 KB | — | -5.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.dep` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.6 KB | — | -3.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.dep.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.5 KB | — | -6.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.devname` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 52 B | — | -52 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.order` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.1 KB | — | -6.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.softdep` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 55 B | — | -55 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.symbols` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 21.6 KB | — | -21.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/modules.symbols.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 26.5 KB | — | -26.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/updates/compat/compat.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 21.2 KB | — | -21.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/updates/drivers/net/wireless/brcm80211/brcmfmac/brcmfmac.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 219.6 KB | — | -219.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/updates/drivers/net/wireless/brcm80211/brcmutil/brcmutil.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.5 KB | — | -13.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g8f5ca40/updates/net/wireless/cfg80211.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 629.4 KB | — | -629.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/extra/galcore.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 295.8 KB | +295.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/extcon/extcon-class.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 19.6 KB | +19.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/gpio/gpio-pca953x.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 17.4 KB | +17.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/i2c/i2c-dev.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 15.8 KB | +15.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/iio/industrialio.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 55.0 KB | +55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/iio/light/sfh7776.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.5 KB | +12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/input/misc/lis3dsh_acc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 28.7 KB | +28.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/input/touchscreen/atmel_mxt_ts.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 37.7 KB | +37.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/fpga_camera_mipi.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 19.3 KB | +19.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/ipu_bg_overlay_sdc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.5 KB | +12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/ipu_csi_enc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 9.5 KB | +9.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/ipu_fg_overlay_sdc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 14.4 KB | +14.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/ipu_prp_enc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 13.2 KB | +13.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/ipu_still.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.8 KB | +6.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/mxc_v4l2_capture.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 70.1 KB | +70.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/media/platform/mxc/capture/v4l2-int-device.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.0 KB | +6.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/misc/eeprom/at24.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 14.0 KB | +14.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/mtd/devices/m25p80.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.5 KB | +7.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/mtd/mtd.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 72.8 KB | +72.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/mtd/ofpart.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.1 KB | +6.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/mtd/spi-nor/spi-nor.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 29.3 KB | +29.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/net/mii.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.2 KB | +8.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/net/phy/libphy.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 43.9 KB | +43.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/net/usb/asix.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 48.8 KB | +48.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/net/usb/usbnet.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 55.0 KB | +55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/power/bq28z610_battery.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 13.8 KB | +13.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/spi/spi-bitbang.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.9 KB | +8.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/spi/spi-imx.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 23.2 KB | +23.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/usb/chipidea/ci_hdrc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 52.2 KB | +52.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/usb/chipidea/ci_hdrc_imx.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 19.9 KB | +19.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/usb/chipidea/usbmisc_imx.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 15.9 KB | +15.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/usb/core/usbcore.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 288.5 KB | +288.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/usb/host/ehci-hcd.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 95.9 KB | +95.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/drivers/video/backlight/l3ej03110a.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.0 KB | +12.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/fs/fat/fat.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 79.2 KB | +79.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/fs/fat/vfat.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 18.0 KB | +18.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/fs/nls/nls_cp437.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.6 KB | +7.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/fs/nls/nls_iso8859-1.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 5.9 KB | +5.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/net/802/stp.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 4.9 KB | +4.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/net/bridge/bridge.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 130.5 KB | +130.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/net/llc/llc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 11.1 KB | +11.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/codecs/snd-soc-tfa9882.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 5.1 KB | +5.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/codecs/snd-soc-tlv320aic3x.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 53.3 KB | +53.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/fsl/imx-pcm-dma.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 4.7 KB | +4.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/fsl/snd-soc-fsl-sai.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 17.5 KB | +17.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/fsl/snd-soc-fsl-ssi.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 29.1 KB | +29.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/fsl/snd-soc-hbl-tfa9882.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.9 KB | +7.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/fsl/snd-soc-hbl-tlv320aic3x.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.8 KB | +12.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/kernel/sound/soc/fsl/snd-soc-imx-audmux.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 14.5 KB | +14.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.alias` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.0 KB | +7.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.alias.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 10.4 KB | +10.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.builtin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 4.4 KB | +4.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.builtin.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 5.4 KB | +5.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.dep` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.6 KB | +3.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.dep.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.5 KB | +6.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.devname` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 52 B | +52 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.order` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.1 KB | +6.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.softdep` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 55 B | +55 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.symbols` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 21.6 KB | +21.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/modules.symbols.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 26.5 KB | +26.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/updates/compat/compat.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 21.2 KB | +21.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/updates/drivers/net/wireless/brcm80211/brcmfmac/brcmfmac.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 219.6 KB | +219.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/updates/drivers/net/wireless/brcm80211/brcmutil/brcmutil.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 13.5 KB | +13.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g99ca806/updates/net/wireless/cfg80211.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 629.4 KB | +629.4 KB | rootfs |
| `/lib/systemd/network/80-container-host0.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 380 B | 380 B | +0 B | rootfs |
| `/lib/systemd/network/80-container-ve.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 482 B | 482 B | +0 B | rootfs |
| `/lib/systemd/network/99-default.link` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 80 B | 80 B | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-dbus1-generator` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.8 KB | 49.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-debug-generator` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-fstab-generator` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 65.8 KB | 65.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-getty-generator` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-gpt-auto-generator` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 101.9 KB | 101.9 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-system-update-generator` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/systemd/system-preset/90-systemd.preset` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 869 B | 869 B | +0 B | rootfs |
| `/lib/systemd/system/-.slice` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 403 B | 403 B | +0 B | rootfs |
| `/lib/systemd/system/alsa-restore.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 488 B | 488 B | +0 B | rootfs |
| `/lib/systemd/system/apmd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 175 B | 175 B | +0 B | rootfs |
| `/lib/systemd/system/audio-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 342 B | 342 B | +0 B | rootfs |
| `/lib/systemd/system/avahi-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/lib/systemd/system/avahi-daemon.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 875 B | 875 B | +0 B | rootfs |
| `/lib/systemd/system/basic.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 685 B | 685 B | +0 B | rootfs |
| `/lib/systemd/system/bluetooth.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 379 B | 379 B | +0 B | rootfs |
| `/lib/systemd/system/bodystate-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 240 B | 240 B | +0 B | rootfs |
| `/lib/systemd/system/bodystate-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 297 B | 297 B | +0 B | rootfs |
| `/lib/systemd/system/busnames.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 358 B | 358 B | +0 B | rootfs |
| `/lib/systemd/system/camera-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 208 B | 208 B | +0 B | rootfs |
| `/lib/systemd/system/configstore-datadir.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 327 B | 327 B | +0 B | rootfs |
| `/lib/systemd/system/configstore.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 308 B | 308 B | +0 B | rootfs |
| `/lib/systemd/system/console-getty.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 747 B | 747 B | +0 B | rootfs |
| `/lib/systemd/system/console-shell.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 728 B | 728 B | +0 B | rootfs |
| `/lib/systemd/system/container-getty@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 768 B | 768 B | +0 B | rootfs |
| `/lib/systemd/system/dbus.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 366 B | 366 B | +0 B | rootfs |
| `/lib/systemd/system/dbus.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 106 B | 106 B | +0 B | rootfs |
| `/lib/systemd/system/debug-shell.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,008 B | 1,008 B | +0 B | rootfs |
| `/lib/systemd/system/dev-hugepages.mount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 670 B | 670 B | +0 B | rootfs |
| `/lib/systemd/system/dev-mqueue.mount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 590 B | 590 B | +0 B | rootfs |
| `/lib/systemd/system/emergency.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 994 B | 994 B | +0 B | rootfs |
| `/lib/systemd/system/emergency.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 431 B | 431 B | +0 B | rootfs |
| `/lib/systemd/system/final.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 440 B | 440 B | +0 B | rootfs |
| `/lib/systemd/system/getty.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 460 B | 460 B | +0 B | rootfs |
| `/lib/systemd/system/getty@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/lib/systemd/system/graphical.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 558 B | 558 B | +0 B | rootfs |
| `/lib/systemd/system/gui-visible.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 90 B | 90 B | +0 B | rootfs |
| `/lib/systemd/system/halt.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 487 B | 487 B | +0 B | rootfs |
| `/lib/systemd/system/hostapd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 266 B | 266 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-cleanup.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 630 B | 630 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-fs.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 553 B | 553 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-parse-etc.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 790 B | 790 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-root-fs.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 526 B | 526 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-switch-root.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 640 B | 640 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-switch-root.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 691 B | 691 B | +0 B | rootfs |
| `/lib/systemd/system/initrd-udevadm-cleanup-db.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 664 B | 664 B | +0 B | rootfs |
| `/lib/systemd/system/initrd.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 671 B | 671 B | +0 B | rootfs |
| `/lib/systemd/system/irq-affinity-setup.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 185 B | 185 B | +0 B | rootfs |
| `/lib/systemd/system/jpeg-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 235 B | 235 B | +0 B | rootfs |
| `/lib/systemd/system/kexec.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 501 B | 501 B | +0 B | rootfs |
| `/lib/systemd/system/kmod-static-nodes.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 675 B | 675 B | +0 B | rootfs |
| `/lib/systemd/system/late.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55 B | 55 B | +0 B | rootfs |
| `/lib/systemd/system/late.timer` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 114 B | 114 B | +0 B | rootfs |
| `/lib/systemd/system/local-fs-pre.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395 B | 395 B | +0 B | rootfs |
| `/lib/systemd/system/local-fs.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 507 B | 507 B | +0 B | rootfs |
| `/lib/systemd/system/machines.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 531 B | 531 B | +0 B | rootfs |
| `/lib/systemd/system/media-data.mount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198 B | 198 B | +0 B | rootfs |
| `/lib/systemd/system/metadata-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 248 B | 248 B | +0 B | rootfs |
| `/lib/systemd/system/mipi-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 240 B | 240 B | +0 B | rootfs |
| `/lib/systemd/system/msg2dbus-farm.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 302 B | 302 B | +0 B | rootfs |
| `/lib/systemd/system/msg2dbus-suc.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 300 B | 300 B | +0 B | rootfs |
| `/lib/systemd/system/multi-user.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 492 B | 492 B | +0 B | rootfs |
| `/lib/systemd/system/network-manager.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263 B | 263 B | +0 B | rootfs |
| `/lib/systemd/system/network-online.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 464 B | 464 B | +0 B | rootfs |
| `/lib/systemd/system/network-pre.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 461 B | 461 B | +0 B | rootfs |
| `/lib/systemd/system/network.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 480 B | 480 B | +0 B | rootfs |
| `/lib/systemd/system/nss-lookup.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 514 B | 514 B | +0 B | rootfs |
| `/lib/systemd/system/nss-user-lookup.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 473 B | 473 B | +0 B | rootfs |
| `/lib/systemd/system/org.freedesktop.hostname1.busname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 554 B | 554 B | +0 B | rootfs |
| `/lib/systemd/system/org.freedesktop.network1.busname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 675 B | 675 B | +0 B | rootfs |
| `/lib/systemd/system/org.freedesktop.systemd1.busname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 480 B | 480 B | +0 B | rootfs |
| `/lib/systemd/system/org.freedesktop.timedate1.busname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 538 B | 538 B | +0 B | rootfs |
| `/lib/systemd/system/paths.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 354 B | 354 B | +0 B | rootfs |
| `/lib/systemd/system/phocus-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 232 B | 232 B | +0 B | rootfs |
| `/lib/systemd/system/phocus-mobile-server.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 295 B | 295 B | +0 B | rootfs |
| `/lib/systemd/system/poweroff.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 552 B | 552 B | +0 B | rootfs |
| `/lib/systemd/system/printer.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 377 B | 377 B | +0 B | rootfs |
| `/lib/systemd/system/quotaon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 576 B | 576 B | +0 B | rootfs |
| `/lib/systemd/system/reboot.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 543 B | 543 B | +0 B | rootfs |
| `/lib/systemd/system/remote-fs-pre.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 396 B | 396 B | +0 B | rootfs |
| `/lib/systemd/system/remote-fs.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 482 B | 482 B | +0 B | rootfs |
| `/lib/systemd/system/rescue.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 990 B | 990 B | +0 B | rootfs |
| `/lib/systemd/system/rescue.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 486 B | 486 B | +0 B | rootfs |
| `/lib/systemd/system/rpcbind.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 500 B | 500 B | +0 B | rootfs |
| `/lib/systemd/system/serial-getty@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/lib/systemd/system/shutdown.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 402 B | 402 B | +0 B | rootfs |
| `/lib/systemd/system/sigpwr.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 362 B | 362 B | +0 B | rootfs |
| `/lib/systemd/system/sleep.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 420 B | 420 B | +0 B | rootfs |
| `/lib/systemd/system/slices.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 409 B | 409 B | +0 B | rootfs |
| `/lib/systemd/system/smartcard.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 380 B | 380 B | +0 B | rootfs |
| `/lib/systemd/system/sockets.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 356 B | 356 B | +0 B | rootfs |
| `/lib/systemd/system/sound.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 380 B | 380 B | +0 B | rootfs |
| `/lib/systemd/system/spi-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 186 B | 186 B | +0 B | rootfs |
| `/lib/systemd/system/sshd.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 144 B | 144 B | +0 B | rootfs |
| `/lib/systemd/system/sshd@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 256 B | 256 B | +0 B | rootfs |
| `/lib/systemd/system/sshdgenkeys.service` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 446 B | 513 B | +67 B | rootfs |
| `/lib/systemd/system/storage-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237 B | 237 B | +0 B | rootfs |
| `/lib/systemd/system/suspend.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 441 B | 441 B | +0 B | rootfs |
| `/lib/systemd/system/sutest-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 179 B | 179 B | +0 B | rootfs |
| `/lib/systemd/system/sutest-gui.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 390 B | 390 B | +0 B | rootfs |
| `/lib/systemd/system/sutest-headphone.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 98 B | 98 B | +0 B | rootfs |
| `/lib/systemd/system/sutest-speaker.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 98 B | 98 B | +0 B | rootfs |
| `/lib/systemd/system/sys-kernel-debug.mount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 662 B | 662 B | +0 B | rootfs |
| `/lib/systemd/system/sysinit.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | rootfs |
| `/lib/systemd/system/syslog.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/lib/systemd/system/system-manager.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 301 B | 301 B | +0 B | rootfs |
| `/lib/systemd/system/system-update.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 585 B | 585 B | +0 B | rootfs |
| `/lib/systemd/system/system.slice` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 433 B | 433 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-bootchart.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 650 B | 650 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-bus-proxyd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 790 B | 790 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-bus-proxyd.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 409 B | 409 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-fsck-root.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 574 B | 574 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-fsck@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 600 B | 600 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-halt.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 544 B | 544 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-hostnamed.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 710 B | 710 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-hwdb-update.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 778 B | 778 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-initctl.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 480 B | 480 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-initctl.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 524 B | 524 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-journal-catalog-update.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 667 B | 667 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-journald-audit.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 607 B | 607 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-journald-dev-log.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/lib/systemd/system/systemd-journald.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/lib/systemd/system/systemd-journald.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 842 B | 842 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-kexec.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 557 B | 557 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-machine-id-commit.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 693 B | 693 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-modules-load.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 967 B | 967 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-networkd-wait-online.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 685 B | 685 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-networkd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/lib/systemd/system/systemd-networkd.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 587 B | 587 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-nspawn@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/lib/systemd/system/systemd-poweroff.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 553 B | 553 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-reboot.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 548 B | 548 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-remount-fs.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 757 B | 757 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-rfkill@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 753 B | 753 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-suspend.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 497 B | 497 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-sysctl.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 649 B | 649 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-sysusers.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 660 B | 660 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-timedated.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 655 B | 655 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-timesyncd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/lib/systemd/system/systemd-tmpfiles-setup-dev.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 703 B | 703 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-tmpfiles-setup.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 683 B | 683 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-udev-settle.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 823 B | 823 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-udev-trigger.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 743 B | 743 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-udevd-control.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 578 B | 578 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-udevd-kernel.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 570 B | 570 B | +0 B | rootfs |
| `/lib/systemd/system/systemd-udevd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 842 B | 842 B | +0 B | rootfs |
| `/lib/systemd/system/time-sync.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395 B | 395 B | +0 B | rootfs |
| `/lib/systemd/system/timers.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 405 B | 405 B | +0 B | rootfs |
| `/lib/systemd/system/tmp.mount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 625 B | 625 B | +0 B | rootfs |
| `/lib/systemd/system/touch-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 180 B | 180 B | +0 B | rootfs |
| `/lib/systemd/system/umount.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 417 B | 417 B | +0 B | rootfs |
| `/lib/systemd/system/upgrade-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 427 B | 427 B | +0 B | rootfs |
| `/lib/systemd/system/usb-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 170 B | 170 B | +0 B | rootfs |
| `/lib/systemd/system/user@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 510 B | 510 B | +0 B | rootfs |
| `/lib/systemd/system/var-volatile-lib.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | rootfs |
| `/lib/systemd/system/verylate.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 60 B | 60 B | +0 B | rootfs |
| `/lib/systemd/system/verylate.timer` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124 B | 124 B | +0 B | rootfs |
| `/lib/systemd/system/victory-gui.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 449 B | 449 B | +0 B | rootfs |
| `/lib/systemd/system/video-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 304 B | 304 B | +0 B | rootfs |
| `/lib/systemd/system/weston.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 234 B | 234 B | +0 B | rootfs |
| `/lib/systemd/system/wpa_supplicant-nl80211@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 447 B | 447 B | +0 B | rootfs |
| `/lib/systemd/system/wpa_supplicant-wired@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 439 B | 439 B | +0 B | rootfs |
| `/lib/systemd/system/wpa_supplicant.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 222 B | 222 B | +0 B | rootfs |
| `/lib/systemd/system/wpa_supplicant@.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 401 B | 401 B | +0 B | rootfs |
| `/lib/systemd/systemd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/lib/systemd/systemd-ac-power` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.6 KB | 9.6 KB | +0 B | rootfs |
| `/lib/systemd/systemd-activate` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.8 KB | 41.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-bootchart` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.8 KB | 89.8 KB | +4 B | rootfs |
| `/lib/systemd/systemd-bus-proxyd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 318.4 KB | 318.4 KB | +0 B | rootfs |
| `/lib/systemd/systemd-cgroups-agent` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 234.3 KB | 234.3 KB | +0 B | rootfs |
| `/lib/systemd/systemd-fsck` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 262.6 KB | 262.6 KB | +0 B | rootfs |
| `/lib/systemd/systemd-hostnamed` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 286.3 KB | 286.3 KB | +0 B | rootfs |
| `/lib/systemd/systemd-initctl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 242.3 KB | 242.3 KB | +0 B | rootfs |
| `/lib/systemd/systemd-journald` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 253.8 KB | 253.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-machine-id-commit` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-modules-load` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-networkd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 666.4 KB | 666.4 KB | +0 B | rootfs |
| `/lib/systemd/systemd-networkd-wait-online` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 101.9 KB | 101.9 KB | +0 B | rootfs |
| `/lib/systemd/systemd-random-seed` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-remount-fs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.8 KB | 41.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-reply-password` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-rfkill` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-shutdown` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 121.9 KB | 121.9 KB | +0 B | rootfs |
| `/lib/systemd/systemd-sleep` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-socket-proxyd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.8 KB | 81.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-sysctl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-sysv-install` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/lib/systemd/systemd-timedated` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 286.7 KB | 286.7 KB | +0 B | rootfs |
| `/lib/systemd/systemd-timesyncd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 121.8 KB | 121.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-udevd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 365.9 KB | 361.9 KB | -4.0 KB | rootfs |
| `/lib/systemd/systemd-update-done` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/udev/ata_id` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/udev/cdrom_id` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/lib/udev/collect` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/lib/udev/mtd_probe` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/lib/udev/rules.d/50-firmware.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 121 B | 121 B | +0 B | rootfs |
| `/lib/udev/rules.d/50-udev-default.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/lib/udev/rules.d/60-block.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 606 B | 606 B | +0 B | rootfs |
| `/lib/udev/rules.d/60-persistent-alsa.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 616 B | 616 B | +0 B | rootfs |
| `/lib/udev/rules.d/60-persistent-input.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/lib/udev/rules.d/75-net-description.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 452 B | 452 B | +0 B | rootfs |
| `/lib/udev/rules.d/75-probe_mtd.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 174 B | 174 B | +0 B | rootfs |
| `/lib/udev/rules.d/80-drivers.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 618 B | 618 B | +0 B | rootfs |
| `/lib/udev/rules.d/80-net-setup-link.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 292 B | 292 B | +0 B | rootfs |
| `/lib/udev/rules.d/85-regulatory.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 225 B | 225 B | +0 B | rootfs |
| `/lib/udev/rules.d/90-alsa-restore.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 420 B | 420 B | +0 B | rootfs |
| `/lib/udev/rules.d/99-systemd.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/lib/udev/scsi_id` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 42.3 KB | 42.3 KB | +0 B | rootfs |
| `/lib/udev/v4l_id` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.7 KB | 9.7 KB | +0 B | rootfs |
| `/sbin/agetty` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.5 KB | 33.5 KB | +0 B | rootfs |
| `/sbin/e2label` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 60.9 KB | 60.9 KB | +0 B | rootfs |
| `/sbin/fw_printenv` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 28.9 KB | 28.9 KB | +0 B | rootfs |
| `/sbin/fw_setenv` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 28.9 KB | 28.9 KB | +0 B | rootfs |
| `/sbin/iwconfig` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.1 KB | 67.1 KB | +0 B | rootfs |
| `/sbin/ldconfig` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 589.9 KB | 589.9 KB | +0 B | rootfs |
| `/sbin/mke2fs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.7 KB | 88.7 KB | +0 B | rootfs |
| `/sbin/mkfs.ext2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.7 KB | 88.7 KB | +0 B | rootfs |
| `/sbin/mkfs.ext3` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.7 KB | 88.7 KB | +0 B | rootfs |
| `/sbin/mkfs.ext4` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.7 KB | 88.7 KB | +0 B | rootfs |
| `/sbin/mkfs.ext4dev` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.7 KB | 88.7 KB | +0 B | rootfs |
| `/sbin/mount-copybind` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 649 B | 649 B | +0 B | rootfs |
| `/sbin/sulogin.util-linux` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 34.2 KB | 34.2 KB | +0 B | rootfs |
| `/sbin/tune2fs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 60.9 KB | 60.9 KB | +0 B | rootfs |
| `/usr/bin/alsamixer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 56.4 KB | 56.4 KB | +0 B | rootfs |
| `/usr/bin/apm` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/bin/avahi-browse` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.9 KB | 20.9 KB | +0 B | rootfs |
| `/usr/bin/avahi-publish` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 16.9 KB | 16.9 KB | +0 B | rootfs |
| `/usr/bin/avahi-resolve` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.8 KB | 13.8 KB | +0 B | rootfs |
| `/usr/bin/avahi-set-host-name` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.2 KB | 11.2 KB | +0 B | rootfs |
| `/usr/bin/bodystate-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 204.4 KB | 217.4 KB | +12.9 KB | rootfs |
| `/usr/bin/busctl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 326.3 KB | 326.3 KB | +0 B | rootfs |
| `/usr/bin/camera-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 216.0 KB | 246.9 KB | +30.9 KB | rootfs |
| `/usr/bin/configstore` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 155.7 KB | 156.7 KB | +984 B | rootfs |
| `/usr/bin/dbus-cleanup-sockets` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.2 KB | 9.2 KB | +0 B | rootfs |
| `/usr/bin/dbus-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 328.4 KB | 328.4 KB | +0 B | rootfs |
| `/usr/bin/dbus-launch` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.4 KB | 14.4 KB | +0 B | rootfs |
| `/usr/bin/dbus-monitor` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.9 KB | 13.9 KB | +0 B | rootfs |
| `/usr/bin/dbus-run-session` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.2 KB | 10.2 KB | +0 B | rootfs |
| `/usr/bin/dbus-send` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/bin/dbus-uuidgen` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 KB | 7.6 KB | +0 B | rootfs |
| `/usr/bin/dlist_test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.4 KB | 9.4 KB | +0 B | rootfs |
| `/usr/bin/erase_configstore.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 113 B | 113 B | +0 B | rootfs |
| `/usr/bin/erase_suc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 418 B | 418 B | +0 B | rootfs |
| `/usr/bin/fc-cache` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 12.9 KB | 12.9 KB | +0 B | rootfs |
| `/usr/bin/fc-cat` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.3 KB | 11.3 KB | +0 B | rootfs |
| `/usr/bin/fc-list` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.3 KB | 9.3 KB | +0 B | rootfs |
| `/usr/bin/fc-match` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/bin/fc-pattern` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.0 KB | 9.0 KB | +0 B | rootfs |
| `/usr/bin/fc-query` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.6 KB | 8.6 KB | +0 B | rootfs |
| `/usr/bin/fc-scan` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.0 KB | 9.0 KB | +0 B | rootfs |
| `/usr/bin/fc-validate` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.8 KB | 9.8 KB | +0 B | rootfs |
| `/usr/bin/get_device` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/bin/get_driver` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/bin/get_module` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.6 KB | 6.6 KB | +0 B | rootfs |
| `/usr/bin/groups.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.9 KB | 8.9 KB | +0 B | rootfs |
| `/usr/bin/gst-inspect-1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.9 KB | 37.9 KB | +0 B | rootfs |
| `/usr/bin/gst-launch-1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.2 KB | 29.2 KB | +0 B | rootfs |
| `/usr/bin/gst-typefind-1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.8 KB | 10.8 KB | +0 B | rootfs |
| `/usr/bin/hbl-collect-logs.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.4 KB | 3.4 KB | +7 B | rootfs |
| `/usr/bin/hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 881 B | 881 B | +0 B | rootfs |
| `/usr/bin/hbl-save-error-logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 472 B | 472 B | +0 B | rootfs |
| `/usr/bin/hbl-speaker-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.3 KB | 21.3 KB | +0 B | rootfs |
| `/usr/bin/hex-writer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.8 KB | 67.9 KB | +120 B | rootfs |
| `/usr/bin/hostnamectl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 246.3 KB | 246.3 KB | +0 B | rootfs |
| `/usr/bin/irq-affinity-setup.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 560 B | 560 B | +0 B | rootfs |
| `/usr/bin/is_albatross` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 190 B | 190 B | +0 B | rootfs |
| `/usr/bin/is_idun` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395 B | 395 B | +0 B | rootfs |
| `/usr/bin/is_victory` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 187 B | 187 B | +0 B | rootfs |
| `/usr/bin/is_wedge` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 409 B | 409 B | +0 B | rootfs |
| `/usr/bin/jpeg-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 150.7 KB | 151.3 KB | +608 B | rootfs |
| `/usr/bin/libevdev-tweak-device` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.5 KB | 8.5 KB | +0 B | rootfs |
| `/usr/bin/libinput-debug-events` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.1 KB | 26.1 KB | +0 B | rootfs |
| `/usr/bin/libinput-list-devices` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.3 KB | 21.3 KB | +0 B | rootfs |
| `/usr/bin/load_wifi_test_fw.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 119 B | 119 B | +0 B | rootfs |
| `/usr/bin/lttng` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 200.0 KB | 200.0 KB | +0 B | rootfs |
| `/usr/bin/lttng-relayd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 187.9 KB | 187.9 KB | +0 B | rootfs |
| `/usr/bin/lttng-sessiond` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 457.0 KB | 457.0 KB | +0 B | rootfs |
| `/usr/bin/metadata-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 191.9 KB | 196.2 KB | +4.3 KB | rootfs |
| `/usr/bin/mouse-dpi-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/bin/mpicalc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.2 KB | 15.2 KB | +0 B | rootfs |
| `/usr/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 415.0 KB | 416.6 KB | +1.6 KB | rootfs |
| `/usr/bin/msg2dbus-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 55.3 KB | 55.4 KB | +120 B | rootfs |
| `/usr/bin/mtdev-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.8 KB | 7.8 KB | +0 B | rootfs |
| `/usr/bin/mxt-app` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 93.6 KB | 93.6 KB | +0 B | rootfs |
| `/usr/bin/nettle-hash` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.2 KB | 9.2 KB | +0 B | rootfs |
| `/usr/bin/nettle-lfib-stream` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.8 KB | 5.8 KB | +0 B | rootfs |
| `/usr/bin/nettle-pbkdf2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.6 KB | 8.6 KB | +0 B | rootfs |
| `/usr/bin/network-manager` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.6 KB | 53.8 KB | +128 B | rootfs |
| `/usr/bin/newgrp.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.1 KB | 26.1 KB | +0 B | rootfs |
| `/usr/bin/phocus-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 504.3 KB | 481.6 KB | -22.7 KB | rootfs |
| `/usr/bin/phocus-mobile-server` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 395.3 KB | 396.7 KB | +1.3 KB | rootfs |
| `/usr/bin/pkcs1-conv` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.4 KB | 13.4 KB | +0 B | rootfs |
| `/usr/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 101.3 KB | 101.4 KB | +176 B | rootfs |
| `/usr/bin/program_farm.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/bin/program_fx3.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/bin/program_nodes.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.8 KB | 5.8 KB | +1.1 KB | rootfs |
| `/usr/bin/program_spc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | rootfs |
| `/usr/bin/program_suc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/bin/program_touch.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 482 B | 482 B | +0 B | rootfs |
| `/usr/bin/scp.openssh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 65.6 KB | 65.6 KB | +0 B | rootfs |
| `/usr/bin/sexp-conv` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/bin/ssh-keygen` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 405.6 KB | 405.6 KB | +0 B | rootfs |
| `/usr/bin/ssh.openssh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 645.8 KB | 645.8 KB | +0 B | rootfs |
| `/usr/bin/storage-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 401.3 KB | 399.9 KB | -1.4 KB | rootfs |
| `/usr/bin/sutest-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 453.2 KB | 454.2 KB | +1.0 KB | rootfs |
| `/usr/bin/sutest-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 137.5 KB | 137.6 KB | +120 B | rootfs |
| `/usr/bin/sysmon.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.9 KB | 3.9 KB | +22 B | rootfs |
| `/usr/bin/system-manager` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 216.5 KB | 224.9 KB | +8.4 KB | rootfs |
| `/usr/bin/systemd-cat` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-cgls` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 250.3 KB | 250.3 KB | +0 B | rootfs |
| `/usr/bin/systemd-cgtop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-delta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.8 KB | 53.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-detect-virt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.8 KB | 29.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-nspawn` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 478.5 KB | 478.5 KB | +0 B | rootfs |
| `/usr/bin/systemd-path` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-run` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 314.4 KB | 314.4 KB | +0 B | rootfs |
| `/usr/bin/systemd-stdio-bridge` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 310.4 KB | 310.4 KB | +0 B | rootfs |
| `/usr/bin/systool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.8 KB | 20.8 KB | +0 B | rootfs |
| `/usr/bin/timedatectl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 254.3 KB | 254.3 KB | +0 B | rootfs |
| `/usr/bin/touchpad-edge-detector` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 KB | 8.3 KB | +0 B | rootfs |
| `/usr/bin/update-alternatives` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/bin/upgrade-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 379.7 KB | 380.1 KB | +376 B | rootfs |
| `/usr/bin/upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 442 B | 442 B | +0 B | rootfs |
| `/usr/bin/upgrade_from_slot.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 262 B | 262 B | +0 B | rootfs |
| `/usr/bin/victory-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.7 MB | +40.1 KB | rootfs |
| `/usr/bin/video-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 305.8 KB | 306.0 KB | +144 B | rootfs |
| `/usr/bin/weston` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.2 KB | 125.2 KB | +0 B | rootfs |
| `/usr/bin/weston-info` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.3 KB | 13.3 KB | +0 B | rootfs |
| `/usr/bin/weston.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 270 B | 270 B | +0 B | rootfs |
| `/usr/bin/wl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | rootfs |
| `/usr/bin/xmlcatalog` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.9 KB | 14.9 KB | +0 B | rootfs |
| `/usr/bin/xmllint` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 57.2 KB | 57.2 KB | +0 B | rootfs |
| `/usr/bin/zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 179.4 KB | 179.4 KB | +0 B | rootfs |
| `/usr/bin/zipcloak` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.9 KB | 77.9 KB | +0 B | rootfs |
| `/usr/bin/zipnote` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 73.6 KB | 73.6 KB | +0 B | rootfs |
| `/usr/bin/zipsplit` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 77.0 KB | 77.0 KB | +0 B | rootfs |
| `/usr/lib/crda/libreg.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 16.2 KB | 16.2 KB | +0 B | rootfs |
| `/usr/lib/crda/regulatory.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/lib/dbus/dbus-daemon-launch-helper` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 231.8 KB | 231.8 KB | +0 B | rootfs |
| `/usr/lib/e2initrd_helper` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.8 KB | 10.8 KB | +0 B | rootfs |
| `/usr/lib/fonts/HelveticaNeueLTStd-Bd_1.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.4 KB | 28.4 KB | +0 B | rootfs |
| `/usr/lib/fonts/HelveticaNeueLTStd-Lt_1.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.3 KB | 28.3 KB | +0 B | rootfs |
| `/usr/lib/fonts/ITCFranklinGothicStd-Med.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30.8 KB | 30.8 KB | +0 B | rootfs |
| `/usr/lib/fonts/TeeFranklin-Thin.otf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.8 KB | 17.8 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstalsa.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 64.5 KB | 64.5 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstapp.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstcoreelements.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 288.9 KB | 288.9 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstfaad.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 18.8 KB | 18.8 KB | -4 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstimxv4l2videosrc-userptr.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.4 KB | 26.7 KB | +212 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstimxvpu.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.6 KB | 72.6 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstisomp4.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 356.1 KB | 356.1 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstvideoparsersbad.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 155.5 KB | 155.5 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstvoaacenc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.3 KB | 14.3 KB | -4 B | rootfs |
| `/usr/lib/gstreamer1.0/gstreamer-1.0/gst-plugin-scanner` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/lib/libAppsMessaging.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 80.6 KB | 84.3 KB | +3.7 KB | rootfs |
| `/usr/lib/libEGL.so.1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 601.3 KB | 601.3 KB | +0 B | rootfs |
| `/usr/lib/libGAL.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.7 MB | 4.7 MB | +0 B | rootfs |
| `/usr/lib/libGLESv2.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.4 MB | 4.4 MB | +0 B | rootfs |
| `/usr/lib/libGLSLC.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 MB | 1.8 MB | +0 B | rootfs |
| `/usr/lib/libQt5Compositor.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 524.8 KB | 524.8 KB | +0 B | rootfs |
| `/usr/lib/libQt5Concurrent.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 16.3 KB | 16.3 KB | +0 B | rootfs |
| `/usr/lib/libQt5Core.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.0 MB | 5.0 MB | +0 B | rootfs |
| `/usr/lib/libQt5DBus.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 439.0 KB | 439.0 KB | +0 B | rootfs |
| `/usr/lib/libQt5EglDeviceIntegration.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 733.1 KB | 733.1 KB | +0 B | rootfs |
| `/usr/lib/libQt5Gui.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.2 MB | 4.2 MB | +0 B | rootfs |
| `/usr/lib/libQt5Location.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 416.4 KB | 416.4 KB | +0 B | rootfs |
| `/usr/lib/libQt5Network.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | rootfs |
| `/usr/lib/libQt5Positioning.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 204.7 KB | 204.7 KB | +0 B | rootfs |
| `/usr/lib/libQt5Qml.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.4 MB | 3.4 MB | +0 B | rootfs |
| `/usr/lib/libQt5Quick.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.9 MB | 2.9 MB | +0 B | rootfs |
| `/usr/lib/libQt5QuickParticles.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 451.6 KB | 451.6 KB | +0 B | rootfs |
| `/usr/lib/libQt5QuickTest.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 95.9 KB | 95.9 KB | +0 B | rootfs |
| `/usr/lib/libQt5SerialPort.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.6 KB | 81.6 KB | +0 B | rootfs |
| `/usr/lib/libQt5Sql.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 244.4 KB | 244.4 KB | +0 B | rootfs |
| `/usr/lib/libQt5Test.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 176.1 KB | 176.1 KB | +0 B | rootfs |
| `/usr/lib/libQt5WaylandClient.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.0 MB | 1.0 MB | +0 B | rootfs |
| `/usr/lib/libQt5Xml.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 189.1 KB | 189.1 KB | +0 B | rootfs |
| `/usr/lib/libVSC.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.0 MB | 2.0 MB | +0 B | rootfs |
| `/usr/lib/libapm.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/lib/libappscommon.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 573.8 KB | 594.4 KB | +20.6 KB | rootfs |
| `/usr/lib/libasound.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 786.2 KB | 786.2 KB | +0 B | rootfs |
| `/usr/lib/libavahi-client.so.3.2.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 56.1 KB | 56.1 KB | +0 B | rootfs |
| `/usr/lib/libavahi-common.so.3.5.3` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.1 KB | 41.1 KB | +0 B | rootfs |
| `/usr/lib/libavahi-core.so.7.0.2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 192.6 KB | 192.6 KB | +0 B | rootfs |
| `/usr/lib/libcec.so.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.3 KB | 6.3 KB | +0 B | rootfs |
| `/usr/lib/libdaemon.so.0.5.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.1 KB | 20.1 KB | +0 B | rootfs |
| `/usr/lib/libdbus-1.so.3.8.13` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 228.7 KB | 228.7 KB | +0 B | rootfs |
| `/usr/lib/libdrm.so.2.4.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.4 KB | 39.4 KB | +0 B | rootfs |
| `/usr/lib/libevdev.so.2.1.8` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 62.9 KB | 62.9 KB | +0 B | rootfs |
| `/usr/lib/libexpat.so.1.6.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 130.3 KB | 130.3 KB | +0 B | rootfs |
| `/usr/lib/libfaad.so.2.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 235.0 KB | 235.0 KB | +0 B | rootfs |
| `/usr/lib/libffi.so.6.0.4` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 27.5 KB | 27.5 KB | +0 B | rootfs |
| `/usr/lib/libfontconfig.so.1.9.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.3 KB | 218.3 KB | +0 B | rootfs |
| `/usr/lib/libformw.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 52.7 KB | 52.7 KB | +0 B | rootfs |
| `/usr/lib/libfreetype.so.6.12.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 486.1 KB | 486.1 KB | +0 B | rootfs |
| `/usr/lib/libgc_wayland_protocol.so.0.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/usr/lib/libgcrypt.so.20.0.3` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 610.1 KB | 610.1 KB | +0 B | rootfs |
| `/usr/lib/libgio-2.0.so.0.4400.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/usr/lib/libglib-2.0.so.0.4400.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | rootfs |
| `/usr/lib/libgmodule-2.0.so.0.4400.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.2 KB | 11.2 KB | +0 B | rootfs |
| `/usr/lib/libgmp.so.10.2.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 373.6 KB | 373.6 KB | +0 B | rootfs |
| `/usr/lib/libgnutls.so.28.41.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 970.9 KB | 970.9 KB | +0 B | rootfs |
| `/usr/lib/libgobject-2.0.so.0.4400.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 293.6 KB | 293.6 KB | +0 B | rootfs |
| `/usr/lib/libgpg-error.so.0.15.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 55.6 KB | 55.6 KB | +0 B | rootfs |
| `/usr/lib/libgstapp-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.1 KB | 44.1 KB | +0 B | rootfs |
| `/usr/lib/libgstaudio-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.8 KB | 276.8 KB | +0 B | rootfs |
| `/usr/lib/libgstbase-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 346.9 KB | 346.9 KB | +0 B | rootfs |
| `/usr/lib/libgstcodecparsers-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 254.2 KB | 254.2 KB | -20 B | rootfs |
| `/usr/lib/libgstcontroller-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 46.2 KB | 46.2 KB | +0 B | rootfs |
| `/usr/lib/libgstimxcommon.so.0.12.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 27.8 KB | 27.8 KB | +0 B | rootfs |
| `/usr/lib/libgstnet-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.5 KB | 27.5 KB | +0 B | rootfs |
| `/usr/lib/libgstpbutils-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 136.3 KB | 136.3 KB | +0 B | rootfs |
| `/usr/lib/libgstreamer-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 963.3 KB | 963.3 KB | +0 B | rootfs |
| `/usr/lib/libgstriff-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55.3 KB | 55.3 KB | +0 B | rootfs |
| `/usr/lib/libgstrtp-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.1 KB | 85.1 KB | +0 B | rootfs |
| `/usr/lib/libgsttag-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 205.1 KB | 205.1 KB | +0 B | rootfs |
| `/usr/lib/libgstvideo-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 249.6 KB | 249.6 KB | +0 B | rootfs |
| `/usr/lib/libgthread-2.0.so.0.4400.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/lib/libhogweed.so.4.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 174.4 KB | 174.4 KB | +0 B | rootfs |
| `/usr/lib/libimxvpuapi.so.0.10.2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59.1 KB | 59.1 KB | +0 B | rootfs |
| `/usr/lib/libinput.so.10.5.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 102.9 KB | 102.9 KB | -16 B | rootfs |
| `/usr/lib/libipu.so.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/lib/libjpeg.so.8.0.2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 203.8 KB | 203.8 KB | +0 B | rootfs |
| `/usr/lib/libkmod.so.2.2.11` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 58.2 KB | 58.2 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ctl.so.0.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 196.9 KB | 196.9 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-ctl.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.0 KB | 218.0 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-cyg-profile-fast.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.4 KB | 8.4 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-cyg-profile.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.4 KB | 11.4 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-dl.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.7 KB | 11.7 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-fork.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-libc-wrapper.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.5 KB | 23.5 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-pthread-wrapper.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.6 KB | 16.6 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-tracepoint.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.9 KB | 33.9 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 335.6 KB | 335.6 KB | +0 B | rootfs |
| `/usr/lib/liblzma.so.5.2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124.9 KB | 124.9 KB | +0 B | rootfs |
| `/usr/lib/libmenuw.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.1 KB | 25.1 KB | +0 B | rootfs |
| `/usr/lib/libmtdev.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 16.7 KB | 16.7 KB | +0 B | rootfs |
| `/usr/lib/libnettle.so.6.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.6 KB | 218.6 KB | +0 B | rootfs |
| `/usr/lib/libnl-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 94.2 KB | 94.2 KB | +0 B | rootfs |
| `/usr/lib/libnl-cli-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 32.1 KB | 32.1 KB | +0 B | rootfs |
| `/usr/lib/libnl-genl-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/lib/libnl-nf-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.6 KB | 67.6 KB | +0 B | rootfs |
| `/usr/lib/libnl-route-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 293.2 KB | 293.2 KB | +0 B | rootfs |
| `/usr/lib/libnss_myhostname.so.2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 49.6 KB | 49.6 KB | +0 B | rootfs |
| `/usr/lib/liborc-0.4.so.0.23.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 410.5 KB | 410.5 KB | +0 B | rootfs |
| `/usr/lib/libpanelw.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/lib/libpixman-1.so.0.32.6` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 564.9 KB | 564.9 KB | +0 B | rootfs |
| `/usr/lib/libpng16.so.16.17.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 162.5 KB | 162.5 KB | +0 B | rootfs |
| `/usr/lib/libpopt.so.0.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.8 KB | 39.8 KB | +0 B | rootfs |
| `/usr/lib/libpxp.so.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/lib/libsqlite3.so.0.8.6` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 675.2 KB | 675.2 KB | +0 B | rootfs |
| `/usr/lib/libssl.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 305.6 KB | 305.6 KB | +0 B | rootfs |
| `/usr/lib/libstdc++.so.6.0.21` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/usr/lib/libturbojpeg.so.0.1.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 234.8 KB | 234.8 KB | +0 B | rootfs |
| `/usr/lib/liburcu-bp.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 23.8 KB | 23.8 KB | +0 B | rootfs |
| `/usr/lib/liburcu-cds.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 24.9 KB | 24.9 KB | +0 B | rootfs |
| `/usr/lib/liburcu-common.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 12.4 KB | 12.4 KB | +0 B | rootfs |
| `/usr/lib/liburcu-mb.so.2.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.1 KB | 20.1 KB | +0 B | rootfs |
| `/usr/lib/liburcu-qsbr.so.2.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.8 KB | 20.8 KB | +0 B | rootfs |
| `/usr/lib/liburcu-signal.so.2.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.8 KB | 20.8 KB | +0 B | rootfs |
| `/usr/lib/liburcu.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/lib/libvo-aacenc.so.0.0.4` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 99.6 KB | 99.6 KB | +0 B | rootfs |
| `/usr/lib/libvpu.so.4` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.8 KB | 89.8 KB | +0 B | rootfs |
| `/usr/lib/libwayland-client.so.0.3.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/lib/libwayland-cursor.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.3 KB | 24.3 KB | +0 B | rootfs |
| `/usr/lib/libwayland-server.so.0.1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/usr/lib/libxkbcommon.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 219.9 KB | 219.9 KB | +0 B | rootfs |
| `/usr/lib/libxml2.so.2.9.2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_ADDRESS` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 146 B | 146 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_COLLATE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_CTYPE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 271.8 KB | 271.8 KB | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_IDENTIFICATION` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 376 B | 376 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_MEASUREMENT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_MESSAGES/SYS_LC_MESSAGES` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 52 B | 52 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_MONETARY` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 290 B | 290 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_NAME` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 77 B | 77 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_NUMERIC` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_PAPER` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_TELEPHONE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56 B | 56 B | +0 B | rootfs |
| `/usr/lib/locale/en_GB/LC_TIME` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_ADDRESS` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 155 B | 155 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_COLLATE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_CTYPE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 271.8 KB | 271.8 KB | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_IDENTIFICATION` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 361 B | 361 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_MEASUREMENT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_MESSAGES/SYS_LC_MESSAGES` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 57 B | 57 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_MONETARY` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 286 B | 286 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_NAME` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 77 B | 77 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_NUMERIC` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_PAPER` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_TELEPHONE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59 B | 59 B | +0 B | rootfs |
| `/usr/lib/locale/en_US/LC_TIME` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/lib/lttng/libexec/lttng-consumerd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 224.1 KB | 224.1 KB | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/[[` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/addgroup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/adduser` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ar` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ash` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/awk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/basename` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/bin-lsmod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 30 B | 30 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/blkid` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/bunzip2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/bzcat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/cat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chattr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chgrp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chmod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chown` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chroot` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chrt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/chvt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/clear` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/cmp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/cp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/cpio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/cut` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/date` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/deallocvt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/delgroup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/deluser` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/depmod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 57 B | 57 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/df` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/diff` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dirname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dmesg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dnsdomainname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/du` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dumpkmap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/dumpleases` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 43 B | 43 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/echo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/egrep` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/env` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/expr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/false` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/fbset` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/fdisk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/fgrep` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/find` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/flock` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/free` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/fsck` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/fstrim` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/fuser` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/getopt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/getty` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 52 B | 52 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/grep` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/groups` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66 B | 66 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/gunzip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/gzip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/halt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53 B | 53 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/head` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/hexdump` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/hostname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/hwclock` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/id` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ifconfig` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ifdown` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ifup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/imx6q-hbl-idun.dtb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68 B | 68 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/imx6q-hbl-victory.dtb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74 B | 74 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/imx6q-hbl-wedge.dtb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70 B | 70 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/init` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/insmod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 57 B | 57 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/kill` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/killall` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/klogd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/lbracket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/less` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ln` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/loadfont` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/loadkmap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/logger` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/login` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/logname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/logread` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/losetup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ls` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/lsmod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 54 B | 54 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/lsof` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/md5sum` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mesg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/microcom` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mkdir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mkdosfs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mkfifo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mkfs.vfat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mknod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mkswap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mktemp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/modinfo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/modprobe` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61 B | 61 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/more` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 60 B | 60 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/mv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/nc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/netstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/newgrp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 43 B | 43 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/nohup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/nslookup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/od` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/openvt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/passwd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/patch` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/pidof` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ping6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/pivot_root` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/poweroff` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 57 B | 57 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/printf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ps` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/pwd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/rdate` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/readlink` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/realpath` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/reboot` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55 B | 55 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/renice` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/reset` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/rfkill` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/rm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/rmdir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/rmmod` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55 B | 55 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/route` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/run-parts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/runlevel` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/scp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sed` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/seq` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/setconsole` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sha1sum` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sha256sum` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/shuf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/shutdown` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sleep` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sort` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/ssh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/start-stop-daemon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 47 B | 47 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/stat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/strings` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/stty` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/su` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48 B | 48 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sulogin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66 B | 66 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/swapoff` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/swapon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/switch_root` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sync` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/sysctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/syslogd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/tail` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/tar` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32 B | 32 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/taskset` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/tee` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/telnet` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/tftp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/time` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/top` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/touch` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/tr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/traceroute` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/true` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/tty` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/udhcpc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/udhcpd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40 B | 40 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/umount` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/uname` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/uniq` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/unlink` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/unzip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/uptime` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/users` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/usleep` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/vi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31 B | 31 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/vlock` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/watch` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34 B | 34 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/wc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35 B | 35 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/wget` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/which` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/who` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/whoami` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/xargs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38 B | 38 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/yes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36 B | 36 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/zImage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 64 B | 64 B | +0 B | rootfs |
| `/usr/lib/opkg/alternatives/zcat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | rootfs |
| `/usr/lib/qt5/plugins/bearer/libqconnmanbearer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 172.4 KB | 172.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/bearer/libqgenericbearer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.7 KB | 44.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/bearer/libqnmbearer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 205.1 KB | 205.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/egldeviceintegrations/libqeglfs-viv-integration.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevkeyboardplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 51.0 KB | 51.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevmouseplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 36.9 KB | 36.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevtabletplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 28.0 KB | 28.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevtouchplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 51.1 KB | 51.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqtuiotouchplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 42.6 KB | 42.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/imageformats/libqgif.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 19.2 KB | 19.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/imageformats/libqico.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 19.5 KB | 19.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/imageformats/libqjpeg.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 32.2 KB | 32.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforminputcontexts/libibusplatforminputcontextplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 71.4 KB | 71.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqeglfs.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqminimal.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 27.5 KB | 27.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqminimalegl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 573.2 KB | 573.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqoffscreen.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 560.7 KB | 560.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqwayland-egl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqwayland-generic.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/position/libqtposition_phocus.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.7 KB | 22.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/position/libqtposition_suc.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.3 KB | 44.4 KB | +4 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-decoration-client/libbradient.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.8 KB | 22.8 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-client/libdrm-egl-server.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 12.6 KB | 12.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-client/libwayland-egl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 43.7 KB | 43.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-server/libdrm-egl-server.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 18.6 KB | 18.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-server/libwayland-egl.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.7 KB | 10.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/folderlistmodel/libqmlfolderlistmodelplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 47.4 KB | 47.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/folderlistmodel/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/folderlistmodel/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124 B | 124 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/settings/libqmlsettingsplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.5 KB | 17.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/settings/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 479 B | 479 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/settings/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 103 B | 103 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/Blend.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.5 KB | 18.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/BrightnessContrast.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.8 KB | 6.8 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/ColorOverlay.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/Colorize.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.4 KB | 9.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/ConicalGradient.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.8 KB | 10.8 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/Desaturate.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/DirectionalBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.2 KB | 10.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/Displace.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/DropShadow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.2 KB | 13.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/FastBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.2 KB | 15.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/GammaAdjust.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/GaussianBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/Glow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.2 KB | 10.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/HueSaturation.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.7 KB | 9.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/InnerShadow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.1 KB | 12.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/LevelAdjust.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.7 KB | 16.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/LinearGradient.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.5 KB | 11.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/MaskedBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/OpacityMask.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/RadialBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.5 KB | 11.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/RadialGradient.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.6 KB | 14.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/RectangularGlow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/RecursiveBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.7 KB | 11.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/ThresholdMask.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/ZoomBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.9 KB | 10.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/FastGlow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.9 KB | 11.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/FastInnerShadow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.7 KB | 12.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/FastMaskedBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/GaussianDirectionalBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.9 KB | 11.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/GaussianGlow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/GaussianInnerShadow.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/GaussianMaskedBlur.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/private/SourceProxy.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtGraphicalEffects/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 826 B | 826 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/Models.2/libmodelsplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/Models.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.4 KB | 19.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/Models.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 86 B | 86 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/StateMachine/libqtqmlstatemachine.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 47.9 KB | 47.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/StateMachine/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/StateMachine/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 111 B | 111 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick.2/libqtquick2plugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.0 KB | 7.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 215.4 KB | 215.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 106 B | 106 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/LocalStorage/libqmllocalstorageplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 43.3 KB | 43.3 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/LocalStorage/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 640 B | 640 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/LocalStorage/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 116 B | 116 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Particles.2/libparticlesplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Particles.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.4 KB | 39.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Particles.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 108 B | 108 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Window.2/libwindowplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Window.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Window.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117 B | 117 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/SignalSpy.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.7 KB | 7.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/TestCase.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.9 KB | 53.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/libqmltestplugin.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.2 KB | 20.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 140 B | 140 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/testlogger.js` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/lib/sysctl.d/50-default.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.be.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.1 KB | 11.1 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.be@latin.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.0 KB | 9.0 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.6 KB | 9.6 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.fr.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.9 KB | 9.9 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.it.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.2 KB | 9.2 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.pl.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.3 KB | 9.3 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.pt_BR.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.ru.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.8 KB | 13.8 KB | +0 B | rootfs |
| `/usr/lib/systemd/catalog/systemd.zh_TW.catalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.5 KB | 8.5 KB | +0 B | rootfs |
| `/usr/lib/systemd/user/basic.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 457 B | 457 B | +0 B | rootfs |
| `/usr/lib/systemd/user/default.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 414 B | 414 B | +0 B | rootfs |
| `/usr/lib/systemd/user/exit.target` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 499 B | 499 B | +0 B | rootfs |
| `/usr/lib/systemd/user/systemd-bus-proxyd.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 619 B | 619 B | +0 B | rootfs |
| `/usr/lib/systemd/user/systemd-bus-proxyd.socket` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 384 B | 384 B | +0 B | rootfs |
| `/usr/lib/systemd/user/systemd-exit.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 497 B | 497 B | +0 B | rootfs |
| `/usr/lib/sysusers.d/basic.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/lib/sysusers.d/systemd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 462 B | 462 B | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/journal-nocow.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/legacy.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/systemd-nologin.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/systemd-nspawn.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 981 B | 981 B | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/systemd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/tmp.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 638 B | 638 B | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/var.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 532 B | 532 B | +0 B | rootfs |
| `/usr/lib/tmpfiles.d/x11.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 623 B | 623 B | +0 B | rootfs |
| `/usr/lib/udev/hwdb.d/90-libinput-model-quirks.hwdb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | rootfs |
| `/usr/lib/udev/libinput-device-group` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 KB | 7.3 KB | +0 B | rootfs |
| `/usr/lib/udev/libinput-model-quirks` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.4 KB | 7.4 KB | +0 B | rootfs |
| `/usr/lib/udev/rules.d/80-libinput-device-groups.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 242 B | 242 B | +0 B | rootfs |
| `/usr/lib/udev/rules.d/90-libinput-model-quirks.rules` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/lib/weston/fbdev-backend.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 35.7 KB | 35.7 KB | -4 B | rootfs |
| `/usr/lib/weston/gal2d-renderer.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 22.0 KB | 22.0 KB | +0 B | rootfs |
| `/usr/lib/weston/victory-shell.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/lib/weston/weston-victory-hdmi` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.2 KB | 15.2 KB | +0 B | rootfs |
| `/usr/lib/weston/weston-victory-shell` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.5 KB | 25.5 KB | +0 B | rootfs |
| `/usr/lib/weston/weston-victory-shell-shm` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 19.5 KB | 19.5 KB | +0 B | rootfs |
| `/usr/local/bin/stm32flash` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 36.1 KB | 36.1 KB | +0 B | rootfs |
| `/usr/sbin/alsactl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 87.6 KB | 87.6 KB | +0 B | rootfs |
| `/usr/sbin/apmd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 19.3 KB | 19.3 KB | +0 B | rootfs |
| `/usr/sbin/avahi-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 115.1 KB | 115.1 KB | +0 B | rootfs |
| `/usr/sbin/crda` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.2 KB | 10.2 KB | +0 B | rootfs |
| `/usr/sbin/flash_erase` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 32.0 KB | 32.0 KB | +0 B | rootfs |
| `/usr/sbin/flash_eraseall` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 150 B | 150 B | +0 B | rootfs |
| `/usr/sbin/flash_lock` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/sbin/flash_otp_dump` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/sbin/flash_otp_info` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/sbin/flash_otp_lock` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/sbin/flash_otp_write` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.8 KB | 6.8 KB | +0 B | rootfs |
| `/usr/sbin/flash_unlock` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/sbin/flashcp` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.6 KB | 10.6 KB | +0 B | rootfs |
| `/usr/sbin/genl-ctrl-list` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.6 KB | 7.6 KB | +0 B | rootfs |
| `/usr/sbin/hostapd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 649.1 KB | 649.1 KB | +0 B | rootfs |
| `/usr/sbin/hostapd_cli` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.1 KB | 37.1 KB | +0 B | rootfs |
| `/usr/sbin/iw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 127.2 KB | 127.2 KB | +0 B | rootfs |
| `/usr/sbin/mtd_debug` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/sbin/mtdinfo` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 39.2 KB | 39.2 KB | +0 B | rootfs |
| `/usr/sbin/nanddump` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.6 KB | 33.6 KB | +0 B | rootfs |
| `/usr/sbin/nandtest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/sbin/nandwrite` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 34.5 KB | 34.5 KB | +0 B | rootfs |
| `/usr/sbin/nl-class-add` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.8 KB | 10.8 KB | +0 B | rootfs |
| `/usr/sbin/nl-class-delete` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.6 KB | 9.6 KB | +0 B | rootfs |
| `/usr/sbin/nl-class-list` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.8 KB | 8.8 KB | +0 B | rootfs |
| `/usr/sbin/nl-classid-lookup` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/sbin/nl-cls-add` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 11.2 KB | 11.2 KB | +0 B | rootfs |
| `/usr/sbin/nl-cls-delete` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.5 KB | 10.5 KB | +0 B | rootfs |
| `/usr/sbin/nl-cls-list` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/sbin/nl-link-list` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.8 KB | 8.8 KB | +0 B | rootfs |
| `/usr/sbin/nl-pktloc-lookup` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.6 KB | 8.6 KB | +0 B | rootfs |
| `/usr/sbin/nl-qdisc-add` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/sbin/nl-qdisc-delete` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.7 KB | 9.7 KB | +0 B | rootfs |
| `/usr/sbin/nl-qdisc-list` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.9 KB | 9.9 KB | +0 B | rootfs |
| `/usr/sbin/regdbdump` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/sbin/sshd` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 690.5 KB | 690.5 KB | +0 B | rootfs |
| `/usr/sbin/wpa_supplicant` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 911.7 KB | 911.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/accessx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/basic` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/caps` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 507 B | 507 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/complete` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 228 B | 228 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/iso9995` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/japan` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 986 B | 986 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/ledcaps` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 469 B | 469 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/lednum` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 466 B | 466 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/ledscroll` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 486 B | 486 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/level5` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/misc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/mousekeys` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/olpc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 340 B | 340 B | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/pc98` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/xfree86` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/compat/xtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 461 B | 461 B | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/amiga` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/ataritt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/chicony` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/dell` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.8 KB | 19.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/digital_vndr/lk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.2 KB | 20.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/digital_vndr/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/digital_vndr/unix` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.0 KB | 7.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/everex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/fujitsu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/hhk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/hp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.9 KB | 16.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/keytronic` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.3 KB | 6.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/kinesis` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/macintosh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40.1 KB | 40.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/microsoft` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.3 KB | 12.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/nec` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/nokia` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/northgate` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.6 KB | 39.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/sanwa` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/sgi_vndr/O2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.0 KB | 15.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/sgi_vndr/indigo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.2 KB | 10.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/sgi_vndr/indy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.6 KB | 14.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/sony` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/sun` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.4 KB | 19.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/thinkpad` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.9 KB | 11.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/typematrix` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.7 KB | 20.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/geometry/winbook` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 416 B | 416 B | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/aliases` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/amiga` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/ataritt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/digital_vndr/lk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.0 KB | 6.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/digital_vndr/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.0 KB | 6.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/empty` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68 B | 68 B | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/evdev` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.5 KB | 8.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/fujitsu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/hp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/ibm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/macintosh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/olpc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 762 B | 762 B | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/sgi_vndr/indigo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/sgi_vndr/indy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/sgi_vndr/iris` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 260 B | 260 B | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/sony` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/sun` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/xfree86` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.4 KB | 8.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/keycodes/xfree98` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 91 B | 91 B | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/base` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44.0 KB | 44.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/base.extras.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/base.lst` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.7 KB | 41.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/base.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 199.4 KB | 199.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/evdev` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.2 KB | 39.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/evdev.extras.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/evdev.lst` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.7 KB | 41.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/evdev.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 199.4 KB | 199.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/xfree98` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 743 B | 743 B | +0 B | rootfs |
| `/usr/share/X11/xkb/rules/xkb.dtd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/af` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.8 KB | 22.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/al` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/altwin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/am` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.2 KB | 9.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/apl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 46.7 KB | 46.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ara` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.0 KB | 16.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/at` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 566 B | 566 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/az` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ba` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 707 B | 707 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/bd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/be` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.5 KB | 12.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/bg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/br` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.4 KB | 16.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/brai` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/bt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/bw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 981 B | 981 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/by` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ca` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.0 KB | 21.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/capslock` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/cd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ch` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.1 KB | 8.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/cm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.7 KB | 31.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/cn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.9 KB | 10.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/compose` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ctrl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/cz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.9 KB | 7.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/de` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55.8 KB | 55.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/digital_vndr/lk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/digital_vndr/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/digital_vndr/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.8 KB | 7.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/digital_vndr/vt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 KB | 5.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/dk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ee` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/empty` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101 B | 101 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/epo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/es` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/et` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/eu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/eurosign` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 629 B | 629 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/fi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.9 KB | 12.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/fo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/fr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.7 KB | 70.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/fujitsu_vndr/jp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/fujitsu_vndr/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/gb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.4 KB | 7.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ge` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.7 KB | 11.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/gh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.4 KB | 6.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/gn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/gr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/group` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.2 KB | 11.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/hp_vndr/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/hr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/hu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.4 KB | 14.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ie` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.8 KB | 19.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/il` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.9 KB | 15.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.3 KB | 84.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/inet` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/iq` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 642 B | 642 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.1 KB | 12.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/is` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.2 KB | 14.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/it` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.5 KB | 12.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/jp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 KB | 8.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ke` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/keypad` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.2 KB | 23.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/kg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/kh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/kpdl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/kr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/kz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.5 KB | 11.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/la` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.5 KB | 5.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/latam` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/latin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.3 KB | 14.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/level3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/level5` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/lk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/lt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.5 KB | 16.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/lv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.6 KB | 18.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ma` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.2 KB | 12.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/apple` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/ch` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/de` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/dk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/fi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/fr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/gb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 557 B | 557 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/is` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/it` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/jp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/latam` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/nl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 156 B | 156 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/no` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/pt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/se` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/macintosh_vndr/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/mao` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 594 B | 594 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/md` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/me` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/mk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/mm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/mn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/mt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/mv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/nbsp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/nec_vndr/jp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ng` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/nl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.7 KB | 6.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/no` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.5 KB | 11.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/nokia_vndr/rx-44` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.8 KB | 14.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/nokia_vndr/rx-51` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 70.4 KB | 70.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/nokia_vndr/su-8w` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.3 KB | 27.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/np` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.6 KB | 6.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/olpc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 930 B | 930 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ph` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 74.2 KB | 74.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/pk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.2 KB | 20.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.0 KB | 23.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/pt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.3 KB | 10.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ro` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/rs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ru` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.2 KB | 34.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/rupeesign` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131 B | 131 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/se` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.9 KB | 14.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sgi_vndr/jp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sharp_vndr/sl-c3x00` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sharp_vndr/ws003sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sharp_vndr/ws007sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sharp_vndr/ws011sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sharp_vndr/ws020sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/shift` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/si` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 634 B | 634 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sony_vndr/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/srvr_ctrl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ara` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/be` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/br` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.2 KB | 5.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ca` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ch` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/cz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/de` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/dk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ee` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/es` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/fi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/fr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 KB | 5.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/gb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/gr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.2 KB | 5.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/it` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/jp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/kr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/lt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/lv` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.6 KB | 6.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/nl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/no` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/pt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ro` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ru` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/se` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/sk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/solaris` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/tr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/tw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/ua` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.5 KB | 5.5 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sun_vndr/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/sy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/terminate` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 200 B | 200 B | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/th` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.2 KB | 10.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/tj` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/tm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/tr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.6 KB | 16.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/tw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/typo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/tz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/ua` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.0 KB | 15.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/us` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/uz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/vn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/xfree68_vndr/amiga` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/xfree68_vndr/ataritt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/symbols/za` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/types/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 246 B | 246 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/basic` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 607 B | 607 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/cancel` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 231 B | 231 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/caps` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/types/complete` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 179 B | 179 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/default` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 178 B | 178 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/extra` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.3 KB | 5.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/types/iso9995` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 429 B | 429 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/level5` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 KB | 8.3 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/types/mousekeys` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 214 B | 214 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/nokia` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 302 B | 302 B | +0 B | rootfs |
| `/usr/share/X11/xkb/types/numpad` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/X11/xkb/types/pc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/alsa/alsa.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.1 KB | 9.1 KB | +0 B | rootfs |
| `/usr/share/alsa/alsa.conf.d/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 103 B | 103 B | +0 B | rootfs |
| `/usr/share/alsa/cards/AACI.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 669 B | 669 B | +0 B | rootfs |
| `/usr/share/alsa/cards/ATIIXP-MODEM.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 302 B | 302 B | +0 B | rootfs |
| `/usr/share/alsa/cards/ATIIXP-SPDMA.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ATIIXP.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/AU8810.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 437 B | 437 B | +0 B | rootfs |
| `/usr/share/alsa/cards/AU8820.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 159 B | 159 B | +0 B | rootfs |
| `/usr/share/alsa/cards/AU8830.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 520 B | 520 B | +0 B | rootfs |
| `/usr/share/alsa/cards/Audigy.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 KB | 5.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/Audigy2.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/Aureon51.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/Aureon71.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CA0106.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CMI8338-SWIEC.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CMI8338.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CMI8738-MC6.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CMI8738-MC8.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CMI8788.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CS42888.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/CS46xx.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/EMU10K1.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.5 KB | 5.5 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/EMU10K1X.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ENS1370.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ENS1371.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ES1968.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 152 B | 152 B | +0 B | rootfs |
| `/usr/share/alsa/cards/Echo_Echo3G.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/FM801.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/FWSpeakers.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 333 B | 333 B | +0 B | rootfs |
| `/usr/share/alsa/cards/FireWave.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 702 B | 702 B | +0 B | rootfs |
| `/usr/share/alsa/cards/GUS.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 217 B | 217 B | +0 B | rootfs |
| `/usr/share/alsa/cards/HDA-Intel.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.6 KB | 6.6 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ICE1712.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ICE1724.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ICH-MODEM.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 192 B | 192 B | +0 B | rootfs |
| `/usr/share/alsa/cards/ICH.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/ICH4.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/IMX-HDMI.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 884 B | 884 B | +0 B | rootfs |
| `/usr/share/alsa/cards/Loopback.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/Maestro3.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 558 B | 558 B | +0 B | rootfs |
| `/usr/share/alsa/cards/NFORCE.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.7 KB | 4.7 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/PC-Speaker.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 657 B | 657 B | +0 B | rootfs |
| `/usr/share/alsa/cards/PMac.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 486 B | 486 B | +0 B | rootfs |
| `/usr/share/alsa/cards/PMacToonie.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 705 B | 705 B | +0 B | rootfs |
| `/usr/share/alsa/cards/PS3.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/RME9636.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 780 B | 780 B | +0 B | rootfs |
| `/usr/share/alsa/cards/RME9652.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 780 B | 780 B | +0 B | rootfs |
| `/usr/share/alsa/cards/SB-XFi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/SI7018.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/SI7018/sndoc-mixer.alisp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 251 B | 251 B | +0 B | rootfs |
| `/usr/share/alsa/cards/SI7018/sndop-mixer.alisp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 251 B | 251 B | +0 B | rootfs |
| `/usr/share/alsa/cards/TRID4DWAVENX.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/USB-Audio.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.8 KB | 8.8 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/VIA686A.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/VIA8233.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/VIA8233A.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/VIA8237.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/VX222.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 830 B | 830 B | +0 B | rootfs |
| `/usr/share/alsa/cards/VXPocket.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 839 B | 839 B | +0 B | rootfs |
| `/usr/share/alsa/cards/VXPocket440.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/YMF744.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/alsa/cards/aliases.alisp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 687 B | 687 B | +0 B | rootfs |
| `/usr/share/alsa/cards/aliases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/alsa/init/00main` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/alsa/init/ca0106` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/alsa/init/default` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | rootfs |
| `/usr/share/alsa/init/hda` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/alsa/init/help` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 391 B | 391 B | +0 B | rootfs |
| `/usr/share/alsa/init/info` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 932 B | 932 B | +0 B | rootfs |
| `/usr/share/alsa/init/test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.4 KB | 10.4 KB | +0 B | rootfs |
| `/usr/share/alsa/pcm/center_lfe.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 805 B | 805 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/default.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 762 B | 762 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/dmix.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/alsa/pcm/dpl.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 645 B | 645 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/dsnoop.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/alsa/pcm/front.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 752 B | 752 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/hdmi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/pcm/iec958.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/pcm/modem.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/alsa/pcm/rear.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 744 B | 744 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/side.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 744 B | 744 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/surround21.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 899 B | 899 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/surround40.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 877 B | 877 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/surround41.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 992 B | 992 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/surround50.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 992 B | 992 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/surround51.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 930 B | 930 B | +0 B | rootfs |
| `/usr/share/alsa/pcm/surround71.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 978 B | 978 B | +0 B | rootfs |
| `/usr/share/alsa/smixer.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 155 B | 155 B | +0 B | rootfs |
| `/usr/share/alsa/sndo-mixer.alisp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/DAISY-I2S/DAISY-I2S.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 94 B | 94 B | +0 B | rootfs |
| `/usr/share/alsa/ucm/DAISY-I2S/HiFi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/GoogleNyan/GoogleNyan.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 92 B | 92 B | +0 B | rootfs |
| `/usr/share/alsa/ucm/GoogleNyan/HiFi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PAZ00/HiFi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PAZ00/PAZ00.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PAZ00/Record.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/FMAnalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/PandaBoard.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 881 B | 881 B | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/hifi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/hifiLP` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/record` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/voice` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoard/voiceCall` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/FMAnalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/PandaBoardES.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 898 B | 898 B | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/hifi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/hifiLP` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/record` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/voice` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/PandaBoardES/voiceCall` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/FMAnalog` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/SDP4430.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 875 B | 875 B | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/hifi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/hifiLP` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/record` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/voice` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/SDP4430/voiceCall` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/alsa/ucm/tegraalc5632/tegraalc5632.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/apmd/apmd_proxy.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 830 B | 830 B | +0 B | rootfs |
| `/usr/share/avahi/avahi-service.dtd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 560 B | 560 B | +0 B | rootfs |
| `/usr/share/avahi/service-types` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/hostnamectl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/journalctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/kernel-install` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.6 KB | 11.6 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-analyze` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-cat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-cgls` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-cgtop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-delta` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-detect-virt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-nspawn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/systemd-run` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/timedatectl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/bash-completion/completions/udevadm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-conf-base/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-conf-base/socket.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-conf/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-conf/socket.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-state/COPYING.MIT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-utils-alsactl/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-utils-alsactl/utils.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-utils-alsamixer/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/alsa-utils-alsamixer/utils.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/apm/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/apm/apm.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/apmd/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/apmd/apm.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-daemon/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-daemon/address.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-daemon/client.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-daemon/dns.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-daemon/main.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-locale-en-gb/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-locale-en-gb/address.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-locale-en-gb/client.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-locale-en-gb/dns.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-locale-en-gb/main.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-utils/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-utils/address.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-utils/client.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-utils/dns.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/avahi-utils/main.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/base-files/GPL-2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/base-passwd/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/busybox/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.9 KB | 17.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/crda/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 880 B | 880 B | +0 B | rootfs |
| `/usr/share/common-licenses/crda/copyleft-next-0.3.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.3 KB | 10.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/dbus-lib/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.5 KB | 28.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/dbus-lib/dbus.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/dbus/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.5 KB | 28.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/dbus/dbus.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-mke2fs/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-mke2fs/e2p.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-mke2fs/et_name.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-mke2fs/ext2fs.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.2 KB | 56.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-mke2fs/ss.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-mke2fs/uuid.h.in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-tune2fs/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-tune2fs/e2p.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-tune2fs/et_name.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-tune2fs/ext2fs.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.2 KB | 56.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-tune2fs/ss.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/e2fsprogs-tune2fs/uuid.h.in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/expat/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/firmware-imx-vpu-imx6q/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/firmware-imx-vpu-imx6q/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/fontconfig-utils/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/fontconfig-utils/fccache.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36.6 KB | 36.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/fontconfig-utils/fcfreetype.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.4 KB | 82.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/fontconfig/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/fontconfig/fccache.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36.6 KB | 36.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/fontconfig/fcfreetype.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 82.4 KB | 82.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/freetype/FTL.TXT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.6 KB | 6.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/freetype/GPLv2.TXT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/freetype/LICENSE.TXT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_AFL-2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.8 KB | 8.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Apache-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.1 KB | 11.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Artistic-1.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.7 KB | 4.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_BSD` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_BSD-2-Clause` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_BSD-3-Clause` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-Abilis` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-IntcSST2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-Marvell` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-OLPC` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-agere` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-amd-ucode` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-atheros_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-broadcom_bcm43xx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ca0132` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-chelsio_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-cw1200` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-dib0700` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ene_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 738 B | 738 B | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-fw_sst_0f28` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-go7007` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.7 KB | 19.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-i2400m` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ibt_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-it913x` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 851 B | 851 B | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-iwlwifi_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-mwl8335` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-myri10ge_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-phanfw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-qat_dh895xcc_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-qla2xxx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-r8a779x_usb3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-radeon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ralink-firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ralink_a_mediatek_company_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-rtlwifi_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-siano` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-tda7706-firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ti-connectivity` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-ueagle-atm4-firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-via_vt6656` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-wl1251` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-xc4000` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-xc5000` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Firmware-xc5000c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_FreeType` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.6 KB | 6.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_GFDL-1.3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_GPL-3.0-with-GCC-exception` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_GPL-3.0-with-autoconf-exception` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.9 KB | 33.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_ISC` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 831 B | 831 B | +0 B | rootfs |
| `/usr/share/common-licenses/generic_LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_LGPL-3.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.3 KB | 7.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_LGPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.3 KB | 24.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.3 KB | 7.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Libpng` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_MIT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_MIT-X` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_MIT-style` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_MPL-1.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.8 KB | 22.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_PD` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 52 B | 52 B | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Proprietary` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21 B | 21 B | +0 B | rootfs |
| `/usr/share/common-licenses/generic_The-Qt-Company-Qt-LGPL-Exception-1.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_Zlib` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 863 B | 863 B | +0 B | rootfs |
| `/usr/share/common-licenses/generic_bzip2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_copyleft-next-0.3.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.3 KB | 10.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/generic_openssl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0-locale-en-gb/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0-locale-en-gb/glib.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0-locale-en-gb/gmodule.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0-locale-en-gb/pcre.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.8 KB | 22.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0/glib.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0/gmodule.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glib-2.0/pcre.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.8 KB | 22.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc-binary-localedata-en-gb/GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc-binary-localedata-en-gb/LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc-binary-localedata-en-us/GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc-binary-localedata-en-us/LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc-locale-en-gb/GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc-locale-en-gb/LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/glibc/COPYRIGHT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 956 B | 956 B | +0 B | rootfs |
| `/usr/share/common-licenses/glibc/LICENSES` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 21.8 KB | 21.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gmp/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.3 KB | 34.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gmp/COPYING.LESSERv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gmp/COPYINGv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gnutls/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.3 KB | 34.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gnutls/COPYING.LESSER` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-locale-en-gb/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-locale-en-gb/gst.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-faad/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-faad/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-faad/crc32.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-faad/filters.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-locale-en-gb/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-locale-en-gb/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-locale-en-gb/crc32.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-locale-en-gb/filters.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-videoparsersbad/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-videoparsersbad/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-videoparsersbad/crc32.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-videoparsersbad/filters.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-voaacenc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-voaacenc/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-voaacenc/crc32.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-bad-voaacenc/filters.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-alsa/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-alsa/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-alsa/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-app/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-app/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-app/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-locale-en-gb/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-locale-en-gb/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-base-locale-en-gb/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-good-isomp4/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-good-isomp4/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-good-isomp4/rganalysis.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.0 KB | 26.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-good-locale-en-gb/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-good-locale-en-gb/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-good-locale-en-gb/rganalysis.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.0 KB | 26.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-imx-imxv4l2videosrc-userptr/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0-plugins-imx-imxvpu/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/gstreamer1.0/gst.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/hostapd/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.4 KB | 16.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/imx-lib/COPYING-LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/imx-vpu/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/imx-vpu/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/iw/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 849 B | 849 B | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-base/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-devicetree/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-image/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-asix/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-at24/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-atmel-mxt-ts/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-bq28z610-battery/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-brcmfmac/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-brcmutil/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-bridge/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-cfg80211/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ci-hdrc-imx/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ci-hdrc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-compat/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ehci-hcd/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-extcon-class/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-fat/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-fpga-camera-mipi/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-galcore/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-gpio-pca953x/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-i2c-dev/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-imx-gpu-viv/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-imx-pcm-dma/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-industrialio/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ipu-bg-overlay-sdc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ipu-csi-enc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ipu-fg-overlay-sdc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ipu-prp-enc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ipu-still/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-l3ej03110a/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-libphy/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-lis3dsh-acc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-llc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-m25p80/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-mii/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-mtd/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-mxc-v4l2-capture/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-nls-cp437/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-nls-iso8859-1/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-ofpart/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-sfh7776/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-fsl-sai/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-fsl-ssi/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-hbl-tfa9882/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-hbl-tlv320aic3x/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-imx-audmux/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-tfa9882/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-snd-soc-tlv320aic3x/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-spi-bitbang/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-spi-imx/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-spi-nor/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-stp/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-usbcore/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-usbmisc-imx/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-usbnet/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-v4l2-int-device/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-vfat/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kmod/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libapm/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libapm/apm.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.0 KB | 3.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libasound/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libasound/socket.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-client/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-client/address.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-client/client.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-client/dns.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-client/main.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-common/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-common/address.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-common/client.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-common/dns.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-common/main.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-core/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-core/address.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-core/client.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-core/dns.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.4 KB | 4.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libavahi-core/main.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcap/License` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.8 KB | 19.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcomerr/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcomerr/e2p.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcomerr/et_name.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcomerr/ext2fs.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.2 KB | 56.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcomerr/ss.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcomerr/uuid.h.in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libcrypto/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libdaemon/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libdaemon/daemon.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libdrm/xf86drm.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 64.4 KB | 64.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libe2p/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libe2p/e2p.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libe2p/et_name.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libe2p/ext2fs.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.2 KB | 56.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libe2p/ss.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libe2p/uuid.h.in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libegl-mx6/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libegl-mx6/gc_vdk.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libevdev/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libevdev/libevdev.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 78.5 KB | 78.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libext2fs/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libext2fs/e2p.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libext2fs/et_name.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libext2fs/ext2fs.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56.2 KB | 56.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libext2fs/ss.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libext2fs/uuid.h.in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libfaad/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.8 KB | 17.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libffi/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgal-mx6/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgal-mx6/gc_vdk.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgc-wayland-protocol-mx6/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgc-wayland-protocol-mx6/gc_vdk.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcc/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcc/COPYING.RUNTIME` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcc/COPYING3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.3 KB | 34.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcc/COPYING3.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcrypt/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgcrypt/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgles2-mx6/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgles2-mx6/gc_vdk.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libglslc-mx6/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libglslc-mx6/gc_vdk.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgpg-error/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgpg-error/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgpg-error/gpg-error.h.in` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.4 KB | 25.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgpg-error/init.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.6 KB | 10.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstapp-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstapp-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstapp-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstaudio-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstaudio-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstaudio-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstcodecparsers-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstcodecparsers-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstcodecparsers-1.0/crc32.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstcodecparsers-1.0/filters.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstimxcommon/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstpbutils-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstpbutils-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstpbutils-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstriff-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstriff-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstriff-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstrtp-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstrtp-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstrtp-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgsttag-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgsttag-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgsttag-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstvideo-1.0/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstvideo-1.0/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.7 KB | 24.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libgstvideo-1.0/coverage-report.pl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libimxvpuapi/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libinput/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libjpeg-turbo/cdjpeg.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.0 KB | 5.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libjpeg-turbo/djpeg.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.0 KB | 22.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libjpeg-turbo/jpeglib.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.4 KB | 48.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libkmod/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liblzma/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.7 KB | 2.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liblzma/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liblzma/COPYING.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.3 KB | 34.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liblzma/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liblzma/getopt.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.6 KB | 31.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libnl-cli/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libnl-genl/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libnl-nf/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libnl-route/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libnl/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liborc-0.4/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.1 KB | 3.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libpng/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libpng/png.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 143.3 KB | 143.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libsqlite3/sqlite3.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 369.8 KB | 369.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libssl/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.1 KB | 6.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libstdc++/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libstdc++/COPYING.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libstdc++/COPYING.RUNTIME` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libstdc++/COPYING3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.3 KB | 34.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libstdc++/COPYING3.LIB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libsysfs/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 359 B | 359 B | +0 B | rootfs |
| `/usr/share/common-licenses/libsysfs/GPL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.1 KB | 16.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libsysfs/LGPL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.0 KB | 26.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libudev/LICENSE.GPL2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libudev/LICENSE.LGPL2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liburcu/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liburcu/urcu.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/liburcu/x86.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.5 KB | 13.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libusb1/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libvsc-mx6/EULA` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.9 KB | 31.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libvsc-mx6/gc_vdk.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libxkbcommon/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.9 KB | 9.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libxml2/Copyright` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libxml2/hash.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.0 KB | 29.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libxml2/list.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.9 KB | 15.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/libxml2/trio.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 156.8 KB | 156.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/license.manifest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 30.8 KB | 30.8 KB | -6 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.Abilis` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.IntcSST2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.Marvell` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.OLPC` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.agere` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.atheros_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.broadcom_bcm43xx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ca0132` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.chelsio_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.cw1200` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ene_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 738 B | 738 B | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.fw_sst_0f28` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.go7007` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.7 KB | 19.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.i2400m` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ibt_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.it913x` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 851 B | 851 B | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.iwlwifi_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.mwl8335` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.myri10ge_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.phanfw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.qat_dh895xcc_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.qla2xxx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.r8a779x_usb3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ralink-firmware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ralink_a_mediatek_company_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.rtlwifi_firmware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.siano` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.tda7706-firmware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ti-connectivity` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.ueagle-atm4-firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.via_vt6656` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.wl1251` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.xc4000` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.xc5000` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENCE.xc5000c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENSE.amd-ucode` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENSE.dib0700` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-bcm4356/LICENSE.radeon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.Abilis` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.IntcSST2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.Marvell` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.OLPC` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.agere` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.atheros_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.broadcom_bcm43xx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.1 KB | 4.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ca0132` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.chelsio_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.cw1200` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ene_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 738 B | 738 B | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.fw_sst_0f28` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.go7007` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.7 KB | 19.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.i2400m` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ibt_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.it913x` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 851 B | 851 B | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.iwlwifi_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.mwl8335` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.myri10ge_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.phanfw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.qat_dh895xcc_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.qla2xxx` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.r8a779x_usb3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ralink-firmware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ralink_a_mediatek_company_firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.rtlwifi_firmware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.siano` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.tda7706-firmware.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ti-connectivity` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.ueagle-atm4-firmware` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.via_vt6656` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.wl1251` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.xc4000` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.xc5000` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENCE.xc5000c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENSE.amd-ucode` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENSE.dib0700` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/linux-firmware-broadcom-license/LICENSE.radeon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/locale-base-en-gb/GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/locale-base-en-gb/LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/locale-base-en-us/GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/locale-base-en-us/LGPL-2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.3 KB | 25.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/lttng-tools/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 734 B | 734 B | +0 B | rootfs |
| `/usr/share/common-licenses/lttng-tools/gpl-2.0.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/lttng-tools/lgpl-2.1.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/lttng-ust/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/lttng-ust/snprintf.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/lttng-ust/various.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/mtd-utils/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/mtd-utils/common.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.4 KB | 5.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/mtdev/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/mxt-app/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/ncurses-libformw/version.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/ncurses-libmenuw/version.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/ncurses-libncursesw/version.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/ncurses-libpanelw/version.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/ncurses-libtinfo/version.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.5 KB | 2.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/netbase/copyright` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 535 B | 535 B | +0 B | rootfs |
| `/usr/share/common-licenses/nettle/COPYING.LESSERv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.5 KB | 7.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/nettle/COPYINGv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/nettle/serpent-decrypt.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/nettle/serpent-set-key.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/openssh-keygen/LICENCE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/openssh-scp/LICENCE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/openssh-ssh/LICENCE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/openssh-sshd/LICENCE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/openssh/LICENCE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.7 KB | 15.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/os-release/COPYING.MIT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/pixman/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/pixman/pixman-arm-neon-asm.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.1 KB | 39.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/pixman/pixman-matrix.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.2 KB | 28.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/popt/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase-plugins/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase-plugins/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase-plugins/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase-plugins/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase-plugins/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtbase/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative-qmlplugins/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative-qmlplugins/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative-qmlplugins/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative-qmlplugins/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative-qmlplugins/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtdeclarative/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtgraphicaleffects-qmlplugins/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtgraphicaleffects-qmlplugins/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtgraphicaleffects-qmlplugins/LICENSE.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.0 KB | 15.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtgraphicaleffects-qmlplugins/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtgraphicaleffects-qmlplugins/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtgraphicaleffects-qmlplugins/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtlocation/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtlocation/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtlocation/LICENSE.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.0 KB | 15.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtlocation/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtlocation/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtlocation/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtserialport/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtserialport/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.3 KB | 22.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtserialport/LICENSE.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 15.0 KB | 15.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtserialport/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtserialport/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtserialport/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland-plugins/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland-plugins/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland-plugins/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland-plugins/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland-plugins/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland/LGPL_EXCEPTION.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland/LICENSE.FDL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.4 KB | 22.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland/LICENSE.GPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 34.8 KB | 34.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland/LICENSE.LGPLv21` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/qtwayland/LICENSE.LGPLv3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.0 KB | 8.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/run-postinsts/COPYING.MIT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/run-postinsts/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 515 B | 515 B | +0 B | rootfs |
| `/usr/share/common-licenses/shadow-base/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/shadow-base/passwd.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.4 KB | 31.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/shadow-securetty/COPYING.MIT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/shadow/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/shadow/passwd.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 31.4 KB | 31.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/stm32flash/gpl-2.0.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/sysfsutils/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 359 B | 359 B | +0 B | rootfs |
| `/usr/share/common-licenses/sysfsutils/GPL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.1 KB | 16.1 KB | +0 B | rootfs |
| `/usr/share/common-licenses/sysfsutils/LGPL` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.0 KB | 26.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/systemd-compat-units/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 515 B | 515 B | +0 B | rootfs |
| `/usr/share/common-licenses/systemd-serialgetty/GPL-2.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.2 KB | 17.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/systemd/LICENSE.GPL2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/systemd/LICENSE.LGPL2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/ttf-droid-sans-fallback/README.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 692 B | 692 B | +0 B | rootfs |
| `/usr/share/common-licenses/ttf-droid-sans-japanese/README.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 692 B | 692 B | +0 B | rootfs |
| `/usr/share/common-licenses/u-boot-fw-utils/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/udev/LICENSE.GPL2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/udev/LICENSE.LGPL2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/update-alternatives-opkg/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/update-alternatives-opkg/opkg.py` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.4 KB | 19.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/update-rc.d/update-rc.d` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.7 KB | 4.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-agetty/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 352 B | 352 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-agetty/COPYING.BSD-3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-agetty/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-agetty/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-agetty/COPYING.UCB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-agetty/README.licensing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libblkid/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 352 B | 352 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libblkid/COPYING.BSD-3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libblkid/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libblkid/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libblkid/COPYING.UCB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libblkid/README.licensing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libmount/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 352 B | 352 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libmount/COPYING.BSD-3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libmount/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libmount/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libmount/COPYING.UCB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libmount/README.licensing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libuuid/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 352 B | 352 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libuuid/COPYING.BSD-3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libuuid/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libuuid/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libuuid/COPYING.UCB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-libuuid/README.licensing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-mount/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 352 B | 352 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-mount/COPYING.BSD-3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-mount/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-mount/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-mount/COPYING.UCB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-mount/README.licensing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-sulogin/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 352 B | 352 B | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-sulogin/COPYING.BSD-3` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-sulogin/COPYING.GPLv2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-sulogin/COPYING.LGPLv2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.9 KB | 25.9 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-sulogin/COPYING.UCB` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/common-licenses/util-linux-sulogin/README.licensing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 555 B | 555 B | +0 B | rootfs |
| `/usr/share/common-licenses/vo-aacenc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/volatile-binds/COPYING.MIT` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,023 B | 1,023 B | +0 B | rootfs |
| `/usr/share/common-licenses/wayland/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wayland/wayland-server.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36.4 KB | 36.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/weston/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | rootfs |
| `/usr/share/common-licenses/weston/compositor.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 141.5 KB | 141.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wireless-tools/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wireless-tools/iwconfig.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 46.5 KB | 46.5 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wireless-tools/iwevent.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.0 KB | 20.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wireless-tools/sample_enc.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.3 KB | 4.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wpa-supplicant/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 965 B | 965 B | +0 B | rootfs |
| `/usr/share/common-licenses/wpa-supplicant/README` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/wpa-supplicant/wpa_supplicant.c` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 152.2 KB | 152.2 KB | +0 B | rootfs |
| `/usr/share/common-licenses/xkeyboard-config-locale-en-gb/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.0 KB | 9.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/xkeyboard-config/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.0 KB | 9.0 KB | +0 B | rootfs |
| `/usr/share/common-licenses/zip/LICENSE` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/zlib/zlib.h` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.8 KB | 85.8 KB | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.bodysync.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 116 B | 116 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.camera.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 108 B | 108 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.config.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 104 B | 104 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.jpeg.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 102 B | 102 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.metadata.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 114 B | 114 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.phocus.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 108 B | 108 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.storage.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 111 B | 111 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.sutest.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 108 B | 108 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.sutestgui.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 105 B | 105 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/com.hasselblad.video.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 105 B | 105 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/fi.epitest.hostap.WPASupplicant.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 134 B | 134 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/fi.w1.wpa_supplicant1.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124 B | 124 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/org.freedesktop.Avahi.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 971 B | 971 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/org.freedesktop.hostname1.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 419 B | 419 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/org.freedesktop.network1.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 417 B | 417 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/org.freedesktop.systemd1.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 364 B | 364 B | +0 B | rootfs |
| `/usr/share/dbus-1/system-services/org.freedesktop.timedate1.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 419 B | 419 B | +0 B | rootfs |
| `/usr/share/factory/etc/nsswitch.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 119 B | 119 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-autohint.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 484 B | 484 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-no-sub-pixel.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 491 B | 491 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-scale-bitmap-fonts.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-sub-pixel-bgr.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 489 B | 489 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-sub-pixel-rgb.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 489 B | 489 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-sub-pixel-vbgr.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 490 B | 490 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-sub-pixel-vrgb.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 490 B | 490 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/10-unhinted.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 481 B | 481 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/11-lcdfilter-default.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 526 B | 526 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/11-lcdfilter-legacy.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 524 B | 524 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/11-lcdfilter-light.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 522 B | 522 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/20-unhint-small-vera.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/25-unhint-nonlatin.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/30-metric-aliases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.5 KB | 12.5 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/30-urw-aliases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 701 B | 701 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/40-nonlatin.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.1 KB | 5.1 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/45-latin.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/49-sansserif.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 545 B | 545 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/50-user.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 673 B | 673 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/51-local.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 189 B | 189 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/60-latin.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/65-fonts-persian.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.9 KB | 9.9 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/65-khmer.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 289 B | 289 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/65-nonlatin.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.8 KB | 7.8 KB | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/69-unifont.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 672 B | 672 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/70-no-bitmaps.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263 B | 263 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/70-yes-bitmaps.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263 B | 263 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/80-delicious.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 422 B | 422 B | +0 B | rootfs |
| `/usr/share/fontconfig/conf.avail/90-synthetic.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/share/fonts/truetype/DroidSansFallback.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 MB | 3.6 MB | +0 B | rootfs |
| `/usr/share/fonts/truetype/DroidSansJapanese.ttf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | rootfs |
| `/usr/share/glib-2.0/schemas/gschema.dtd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | rootfs |
| `/usr/share/gst-plugins-base/1.0/license-translations.dict` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 43.6 KB | 43.6 KB | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/avahi.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 13.9 KB | 13.9 KB | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/glib20.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 86.7 KB | 86.7 KB | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/gst-plugins-bad-1.0.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 693 B | 693 B | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/gst-plugins-base-1.0.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 559 B | 559 B | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/gst-plugins-good-1.0.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 671 B | 671 B | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/gstreamer-1.0.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.8 KB | 10.8 KB | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/libc.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/share/locale/en_GB/LC_MESSAGES/xkeyboard-config.mo` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.7 KB | 22.7 KB | +0 B | rootfs |
| `/usr/share/test-images/Face1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 349.8 KB | — | -349.8 KB | rootfs |
| `/usr/share/test-images/Landscape1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 515.0 KB | — | -515.0 KB | rootfs |
| `/usr/share/test-images/Landscape2_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 382.2 KB | — | -382.2 KB | rootfs |
| `/usr/share/test-images/Landscape3_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 498.4 KB | — | -498.4 KB | rootfs |
| `/usr/share/test-images/Landscape5_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 609.0 KB | — | -609.0 KB | rootfs |
| `/usr/share/test-images/Landscape6_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 216.2 KB | — | -216.2 KB | rootfs |
| `/usr/share/test-images/Model1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 340.8 KB | — | -340.8 KB | rootfs |
| `/usr/share/test-images/Space1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 492.8 KB | — | -492.8 KB | rootfs |
| `/usr/share/test-images/bild 1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 460.1 KB | — | -460.1 KB | rootfs |
| `/usr/share/test-images/bild 2_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 419.0 KB | — | -419.0 KB | rootfs |
| `/usr/share/test-images/bild 3_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 482.5 KB | — | -482.5 KB | rootfs |
| `/usr/share/test-images/bild 4_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 525.8 KB | — | -525.8 KB | rootfs |
| `/usr/share/test-images/bild 5_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 233.2 KB | — | -233.2 KB | rootfs |
| `/usr/share/test-images/bild 6_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 348.9 KB | — | -348.9 KB | rootfs |
| `/usr/share/test-images/bild 7_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 339.9 KB | — | -339.9 KB | rootfs |
| `/usr/share/test-images/iStock1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 758.3 KB | — | -758.3 KB | rootfs |
| `/usr/share/test-images/iStock2_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 379.2 KB | — | -379.2 KB | rootfs |
| `/usr/share/test-images/iStock3_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 453.1 KB | — | -453.1 KB | rootfs |
| `/usr/share/test-images/iStock4_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 475.8 KB | — | -475.8 KB | rootfs |
| `/usr/share/test-images/iStock5_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 508.8 KB | — | -508.8 KB | rootfs |
| `/usr/share/test-images/iStock6_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 643.1 KB | — | -643.1 KB | rootfs |
| `/usr/share/test-images/ratt1_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 744.1 KB | — | -744.1 KB | rootfs |
| `/usr/share/test-images/test2 25 Gamma 1168_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.1 KB | — | -3.1 KB | rootfs |
| `/usr/share/test-images/test2 48 Gamma 1168_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.1 KB | — | -3.1 KB | rootfs |
| `/usr/share/test-images/test2 Blacktest 1168_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.4 KB | — | -13.4 KB | rootfs |
| `/usr/share/test-images/test2 Colour bars.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 2.0 KB | — | -2.0 KB | rootfs |
| `/usr/share/test-images/test2 Whitetest 1168_640x480.png` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.5 KB | — | -6.5 KB | rootfs |
| `/usr/share/wayland-sessions/weston.desktop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 126 B | 126 B | +0 B | rootfs |
| `/usr/share/weston/background.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 239.8 KB | 239.8 KB | +0 B | rootfs |
| `/usr/share/weston/border.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/usr/share/weston/fullscreen.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | rootfs |
| `/usr/share/weston/home.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.5 KB | 4.5 KB | +0 B | rootfs |
| `/usr/share/weston/icon_ivi_clickdot.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 38.6 KB | 38.6 KB | +0 B | rootfs |
| `/usr/share/weston/icon_ivi_flower.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.9 KB | 23.9 KB | +0 B | rootfs |
| `/usr/share/weston/icon_ivi_simple-egl.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.6 KB | 28.6 KB | +0 B | rootfs |
| `/usr/share/weston/icon_ivi_simple-shm.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 69.5 KB | 69.5 KB | +0 B | rootfs |
| `/usr/share/weston/icon_ivi_smoke.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.5 KB | 45.5 KB | +0 B | rootfs |
| `/usr/share/weston/icon_window.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 161 B | 161 B | +0 B | rootfs |
| `/usr/share/weston/logo.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | rootfs |
| `/usr/share/weston/panel.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.0 KB | 41.0 KB | +0 B | rootfs |
| `/usr/share/weston/pattern.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | rootfs |
| `/usr/share/weston/random.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | rootfs |
| `/usr/share/weston/sidebyside.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | rootfs |
| `/usr/share/weston/sign_close.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 235 B | 235 B | +0 B | rootfs |
| `/usr/share/weston/sign_maximize.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 204 B | 204 B | +0 B | rootfs |
| `/usr/share/weston/sign_minimize.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 191 B | 191 B | +0 B | rootfs |
| `/usr/share/weston/terminal.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1,005 B | 1,005 B | +0 B | rootfs |
| `/usr/share/weston/tiling.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.5 KB | 5.5 KB | +0 B | rootfs |
| `/usr/share/weston/wayland.png` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | rootfs |
| `/usr/share/weston/wayland.svg` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/share/xml/fontconfig/fonts.dtd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.1 KB | 7.1 KB | +0 B | rootfs |
| `/usr/share/xml/lttng/session.xsd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/var/cache/fontconfig/3830d5c3ddfd5cd38a049b759396e72e-le32d8.cache-6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 112 B | 112 B | +0 B | rootfs |
| `/var/cache/fontconfig/7ef2298fde41cc6eeb7af42e48b7d293-le32d8.cache-6` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 KB | 7.3 KB | +0 B | rootfs |
| `/var/cache/fontconfig/CACHEDIR.TAG` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 200 B | 200 B | +0 B | rootfs |
| `/var/cache/ldconfig/aux-cache` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.2 KB | 9.2 KB | +0 B | rootfs |
</details>
