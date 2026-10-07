# X2D 100C: 1.0.5 ➜ 1.1.0

> 生成时间: 2026-10-07T06:06:59 · CIM 日期: 2022-12-01 ➜ 2022-12-21 · 条目: 6 ➜ 6 · 源: `X2D_100C_v1_0_5.cim` ➜ `X2D_100C_v1_1_0.cim`

## Summary

文件树 +1/-0/~120；CIM 条目 +0/-0/~4；OTA 镜像 ~7 变更 / 0 未变；符号 +99/-3260 funcs, +238/-987 objs；新增字符串 3519 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B |
| `exMCU.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B |
| `exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B |
| `ota.zip` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 131.8 MB | 131.4 MB | -387.2 KB |
| `hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 4 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 2

## OTA Images

| Image | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `bootarea.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 544.0 KB | 544.0 KB | +0 B |
| `gimbal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 353.0 KB | 353.0 KB | +0 B |
| `normal.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.9 MB | 17.9 MB | -1.0 KB |
| `scp.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 89.5 KB | 89.5 KB | +0 B |
| `system.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 512.0 MB | 512.0 MB | +0 B |
| `tos.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 425.0 KB | 425.0 KB | +0 B |
| `vendor.img` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 24.6 MB | 24.6 MB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 7 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 0

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `lib` | 0 | 0 | 70 | 0 | 0 |
| `bin` | 0 | 0 | 16 | 292 | 0 |
| `etc` | 1 | 0 | 14 | 142 | 0 |
| `lib64` | 0 | 0 | 7 | 268 | 0 |
| `firmware` | 0 | 0 | 4 | 8 | 0 |
| `model` | 0 | 0 | 4 | 0 | 0 |
| `(root)` | 0 | 0 | 3 | 2 | 0 |
| `ta` | 0 | 0 | 2 | 0 | 0 |
| `product` | 0 | 0 | 0 | 1 | 0 |
| `usr` | 0 | 0 | 0 | 12 | 0 |
| `xbin` | 0 | 0 | 0 | 10 | 0 |

明细 856 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+99 / −3260** functions, **+238 / −987** objects（50 个变更 ELF, 另有 41 个未列出）。

### `/bin/wl`

+0 / −3259 functions · +0 / −749 objects

**Removed functions (3259)**

| Symbol | Addr | Size |
|---|---|---|
| `__grow_type_table` | 0x80f9 | 128 |
| `__find_arguments` | 0x8179 | 1684 |
| `exit` | 0x880d | 16 |
| `_ZL30__bionic_tls_strerror_key_initv` | 0x881d | 20 |
| `_ZL31__bionic_tls_uselocale_key_initv` | 0x8831 | 16 |
| `jemalloc_constructor` | 0x8841 | 176 |
| `__atexit_handler_wrapper` | 0x88f0 | 20 |
| `_start` | 0x8904 | 124 |
| `atexit` | 0x8980 | 32 |
| `cca_per_chan_summary` | 0x89b4 | 820 |
| `cca_info` | 0x8ce8 | 200 |
| `spec_to_chan` | 0x8db0 | 168 |
| `cca_analyze` | 0x8e58 | 1956 |
| `wl_copy_wlccnt` | 0x95fc | 652 |
| `wl_copy_macstat_upto_ver10` | 0x9888 | 580 |
| `wl_copy_macstat_ver11` | 0x9acc | 168 |
| `wl_cntbuf_to_xtlv_format` | 0x9b74 | 740 |
| `math_nbits_32` | 0x9e58 | 96 |
| `math_gcd_32` | 0x9eb8 | 92 |
| `math_sqrt_int_32` | 0x9f14 | 232 |
| `math_fp_calc_head_room_32` | 0x9ffc | 236 |
| `math_qdiv_32` | 0xa0e8 | 268 |
| `math_qdiv_roundup_32` | 0xa1f4 | 68 |
| `math_fp_floor_32` | 0xa238 | 52 |
| `math_fp_round_32` | 0xa26c | 116 |
| `math_add_64` | 0xa2e0 | 112 |
| `math_sub_64` | 0xa350 | 112 |
| `math_uint64_multiple_add` | 0xa3c0 | 676 |
| `math_uint64_divide` | 0xa664 | 308 |
| `math_div_64` | 0xa798 | 440 |
| `math_uint64_right_shift` | 0xa950 | 244 |
| `math_shl_64` | 0xaa44 | 288 |
| `math_shr_64` | 0xab64 | 288 |
| `math_fp_mult_64` | 0xac84 | 216 |
| `math_fp_div_64` | 0xad5c | 236 |
| `math_fp_calc_head_room_64` | 0xae48 | 332 |
| `math_fp_floor_64` | 0xaf94 | 72 |
| `math_fp_round_64` | 0xafdc | 156 |
| `math_fp_ceil_64` | 0xb078 | 132 |
| `math_cmplx_add_cint32` | 0xb0fc | 92 |
| `math_cmplx_power_cint32` | 0xb158 | 96 |
| `math_cmplx_mult_cint32_cfixed` | 0xb1b8 | 252 |
| `math_cmplx_power_cint32_arr` | 0xb2b4 | 184 |
| `math_cmplx_cordic` | 0xb36c | 752 |
| `math_cmplx_invcordic` | 0xb65c | 316 |
| `math_cmplx_computedB` | 0xb798 | 384 |
| `math_cmplx_angle_to_phasor_lut` | 0xb918 | 892 |
| `math_mat_rho` | 0xbc94 | 428 |
| `math_mat_transpose` | 0xbe40 | 200 |
| `math_mat_mult` | 0xbf08 | 400 |

<details><summary>… 另 3209 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `math_mat_inv_prod_det` | 0xc098 | 1180 |
| `math_mat_det` | 0xc534 | 700 |
| `math_fft_cos_seq20` | 0xc7f0 | 280 |
| `math_fft_cos_128` | 0xc908 | 264 |
| `math_fft_sin_seq20` | 0xca10 | 284 |
| `math_fft_sin_128` | 0xcb2c | 268 |
| `math_fft_cos` | 0xcc38 | 264 |
| `math_fft_sin` | 0xcd40 | 268 |
| `math_cordic` | 0xce4c | 584 |
| `math_cordic_ptr` | 0xd094 | 60 |
| `math_theta_to_idx` | 0xd0d0 | 160 |
| `math_cos_tbl` | 0xd170 | 52 |
| `math_sin_tbl` | 0xd1a4 | 60 |
| `bcm_bloom_create` | 0xd1e0 | 440 |
| `bcm_bloom_destroy` | 0xd398 | 236 |
| `bcm_bloom_add_hash` | 0xd484 | 236 |
| `bcm_bloom_remove_hash` | 0xd570 | 116 |
| `bcm_bloom_is_member` | 0xd5e4 | 392 |
| `bcm_bloom_add_member` | 0xd76c | 380 |
| `bcm_bloom_get_filter_data` | 0xd8e8 | 184 |
| `memmove_s` | 0xd9a0 | 248 |
| `memcpy_s` | 0xda98 | 340 |
| `memset_s` | 0xdbec | 184 |
| `strlcpy` | 0xdca4 | 296 |
| `strlcat_s` | 0xddcc | 412 |
| `bcm_addrmask_set` | 0xdf7c | 36 |
| `bcm_addrmask_get` | 0xdfa0 | 36 |
| `bcm_find_fsb` | 0xe0b0 | 112 |
| `bcm_ip_ntoa` | 0xe120 | 112 |
| `bcm_ipv6_ntoa` | 0xe190 | 792 |
| `bcm_strtoull` | 0xe4a8 | 860 |
| `bcm_strtoul` | 0xe804 | 64 |
| `bcm_atoi` | 0xe844 | 48 |
| `bcmstrstr` | 0xe874 | 236 |
| `bcmstrnstr` | 0xe960 | 124 |
| `bcmstrcat` | 0xe9dc | 108 |
| `bcmstrncat` | 0xea48 | 140 |
| `bcmstrtok` | 0xead4 | 612 |
| `bcmstricmp` | 0xed38 | 356 |
| `bcmstrnicmp` | 0xee9c | 404 |
| `bcm_ether_atoe` | 0xf030 | 156 |
| `bcm_atoipv4` | 0xf0cc | 156 |
| `bcm_write_tlv` | 0xf168 | 196 |
| `bcm_write_tlv_ext` | 0xf22c | 220 |
| `bcm_write_tlv_safe` | 0xf308 | 108 |
| `bcm_copy_tlv` | 0xf374 | 124 |
| `bcm_copy_tlv_safe` | 0xf3f0 | 120 |
| `hndcrc8` | 0xf468 | 120 |
| `hndcrc16` | 0xf4e0 | 148 |
| `hndcrc32` | 0xf574 | 144 |
| `bcm_next_tlv` | 0xf604 | 228 |
| `bcm_tlv_buffer_advance_to` | 0xf6e8 | 300 |
| `bcm_tlv_buffer_advance_past` | 0xf814 | 112 |
| `bcm_parse_tlvs` | 0xf884 | 204 |
| `bcm_parse_tlvs_advance` | 0xf950 | 200 |
| `bcm_parse_tlvs_dot11` | 0xfa18 | 268 |
| `bcm_parse_tlvs_min_bodylen` | 0xfb24 | 108 |
| `bcm_parse_tlvs_minmax_len` | 0xfb90 | 172 |
| `bcm_parse_ordered_tlvs` | 0xfc3c | 212 |
| `bcm_format_field` | 0xfd10 | 288 |
| `bcm_format_flags` | 0xfe30 | 572 |
| `bcm_format_octets` | 0x1006c | 452 |
| `bcmhex2bin` | 0x10230 | 440 |
| `bcm_format_hex` | 0x103e8 | 164 |
| `prhex` | 0x1048c | 384 |
| `bcm_crypto_algo_name` | 0x1060c | 80 |
| `deadbeef` | 0x1065c | 100 |
| `bcm_chipname` | 0x106c0 | 116 |
| `bcm_brev_str` | 0x10734 | 176 |
| `printbig` | 0x107e4 | 192 |
| `bcmdumpfields` | 0x108a4 | 252 |
| `bcm_mkiovar` | 0x109a0 | 180 |
| `bcm_qdbm_to_mw` | 0x10a54 | 196 |
| `bcm_mw_to_qdbm` | 0x10b18 | 332 |
| `bcm_bitcount` | 0x10c64 | 168 |
| `process_nvram_vars` | 0x10d0c | 492 |
| `set_bitrange` | 0x10ef8 | 564 |
| `bcm_bitprint32` | 0x1112c | 144 |
| `bcm_ip_cksum` | 0x111bc | 232 |
| `bcm_add_64` | 0x112a4 | 112 |
| `bcm_sub_64` | 0x11314 | 112 |
| `valid_bcmerror` | 0x11384 | 68 |
| `ip_cksum_partial` | 0x113c8 | 132 |
| `ip_cksum` | 0x1144c | 208 |
| `ipv4_hdr_cksum` | 0x1151c | 128 |
| `tcp_hdr_chksum` | 0x1159c | 108 |
| `ipv4_tcp_hdr_cksum` | 0x11608 | 280 |
| `ipv6_tcp_hdr_cksum` | 0x11720 | 232 |
| `sqrt_int` | 0x11808 | 232 |
| `setbits` | 0x118f0 | 744 |
| `getbits` | 0x11bd8 | 568 |
| `array_value_mismatch_count` | 0x11e10 | 164 |
| `array_nonzero_count` | 0x11eb4 | 52 |
| `array_nonzero_count_int16` | 0x11ee8 | 128 |
| `array_zero_count` | 0x11f68 | 124 |
| `verify_ordered_array` | 0x11fe4 | 352 |
| `verify_ordered_array_uint8` | 0x12144 | 88 |
| `verify_ordered_array_int16` | 0x1219c | 88 |
| `verify_array_values` | 0x121f4 | 204 |
| `replace_nvram_variable` | 0x122c0 | 448 |
| `wf_bw_chspec_to_mhz` | 0x12494 | 96 |
| `center_chan_to_edge` | 0x124f4 | 116 |
| `channel_low_edge` | 0x12568 | 60 |
| `channel_to_sb` | 0x125a4 | 236 |
| `channel_to_primary20_chan` | 0x12690 | 72 |
| `channel_80mhz_to_id` | 0x126d8 | 120 |
| `channel_6g_80mhz_to_id` | 0x12750 | 96 |
| `wf_chspec_5G_id80_to_ch` | 0x127b0 | 76 |
| `wf_chspec_6G_id80_to_ch` | 0x127fc | 80 |
| `wf_chspec_ntoa_ex` | 0x1284c | 96 |
| `wf_chspec_ntoa` | 0x128ac | 784 |
| `read_uint` | 0x12bbc | 128 |
| `wf_chspec_aton` | 0x12c3c | 1292 |
| `wf_chspec_malformed` | 0x13148 | 512 |
| `wf_chspec_valid` | 0x13348 | 504 |
| `wf_valid_20MHz_chan` | 0x13540 | 488 |
| `wf_valid_40MHz_center_chan` | 0x13728 | 264 |
| `wf_valid_80MHz_center_chan` | 0x13830 | 140 |
| `wf_valid_160MHz_center_chan` | 0x138bc | 228 |
| `wf_chspec_coexist` | 0x139a0 | 196 |
| `wf_create_20MHz_chspec` | 0x13a64 | 172 |
| `wf_create_40MHz_chspec` | 0x13b10 | 184 |
| `wf_create_40MHz_chspec_primary_sb` | 0x13bc8 | 128 |
| `wf_create_80MHz_chspec` | 0x13c48 | 184 |
| `wf_create_8080MHz_chspec` | 0x13d00 | 492 |
| `wf_create_chspec` | 0x13eec | 280 |
| `wf_create_chspec_from_primary` | 0x14004 | 552 |
| `wf_chspec_primary20_chan` | 0x1422c | 276 |
| `wf_chspec_to_bw_str` | 0x14340 | 64 |
| `wf_chspec_primary20_chspec` | 0x14380 | 132 |
| `wf_channel2chspec` | 0x14404 | 488 |
| `wf_chspec_primary40_chspec` | 0x145ec | 264 |
| `wf_mhz2channel` | 0x146f4 | 476 |
| `wf_channel2mhz` | 0x148d0 | 256 |
| `wf_chspec_80` | 0x149d0 | 192 |
| `wf_chspec_get8080_chspec` | 0x14a90 | 360 |
| `wf_chspec_primary80_channel` | 0x14bf8 | 88 |
| `wf_chspec_secondary80_channel` | 0x14c50 | 88 |
| `wf_chspec_primary80_chspec` | 0x14ca8 | 464 |
| `wf_chspec_secondary80_chspec` | 0x14e78 | 356 |
| `wf_chspec_get_80p80_channels` | 0x14fdc | 388 |
| `wf_get_all_ext` | 0x15160 | 1076 |
| `wf_chspec_overlap` | 0x15594 | 764 |
| `channel_bw_to_width` | 0x15890 | 132 |
| `bcm_xtlv_hdr_size` | 0x15914 | 104 |
| `bcm_valid_xtlv` | 0x1597c | 128 |
| `bcm_xtlv_size_for_data` | 0x159fc | 104 |
| `bcm_xtlv_size` | 0x15a64 | 80 |
| `bcm_xtlv_len` | 0x15ab4 | 256 |
| `bcm_xtlv_id` | 0x15bb4 | 224 |
| `bcm_next_xtlv` | 0x15c94 | 200 |
| `bcm_xtlv_buf_init` | 0x15d5c | 140 |
| `bcm_xtlv_buf_len` | 0x15de8 | 88 |
| `bcm_xtlv_buf_rlen` | 0x15e40 | 84 |
| `bcm_xtlv_buf` | 0x15e94 | 60 |
| `bcm_xtlv_head` | 0x15ed0 | 60 |
| `bcm_xtlv_pack_xtlv` | 0x15f0c | 664 |
| `bcm_xtlv_unpack_xtlv` | 0x161a4 | 176 |
| `bcm_xtlv_put_data` | 0x16254 | 208 |
| `bcm_xtlv_put_int` | 0x16324 | 1072 |
| `bcm_xtlv_put16` | 0x16754 | 76 |
| `bcm_xtlv_put32` | 0x167a0 | 76 |
| `bcm_xtlv_put64` | 0x167ec | 76 |
| `bcm_unpack_xtlv_entry` | 0x16838 | 224 |
| `bcm_pack_xtlv_entry` | 0x16918 | 212 |
| `bcm_unpack_xtlv_buf` | 0x169ec | 252 |
| `bcm_pack_xtlv_buf` | 0x16ae8 | 368 |
| `bcm_pack_xtlv_buf_from_mem` | 0x16c58 | 212 |
| `bcm_unpack_xtlv_buf_to_mem` | 0x16d2c | 392 |
| `bcm_get_data_from_xtlv_buf` | 0x16eb4 | 292 |
| `bcm_xtlv_bcopy` | 0x16fd8 | 252 |
| `MD5Init` | 0x170d4 | 120 |
| `MD5Update` | 0x1714c | 496 |
| `MD5Final` | 0x1733c | 660 |
| `Transform` | 0x175d0 | 6264 |
| `miniopt_init` | 0x18e48 | 128 |
| `miniopt` | 0x18ec8 | 1212 |
| `sha1_transform` | 0x19384 | 1688 |
| `sha256_transform` | 0x19a1c | 1608 |
| `sha2l_u32tou8` | 0x1a064 | 348 |
| `sha2l_update` | 0x1a1c0 | 476 |
| `sha2l_final` | 0x1a39c | 460 |
| `sha2l_init` | 0x1a568 | 232 |
| `get_sha2_hash_impl_entries` | 0x1a650 | 36 |
| `sha2_init` | 0x1a674 | 304 |
| `sha2_update` | 0x1a7a4 | 84 |
| `sha2_final` | 0x1a7f8 | 84 |
| `sha2_update_with_prefixes` | 0x1a84c | 212 |
| `sha2` | 0x1a920 | 132 |
| `sha2_digest_len` | 0x1a9a4 | 180 |
| `sha2_block_size` | 0x1aa58 | 120 |
| `hmac_sha2_update_with_prefixes` | 0x1aad0 | 212 |
| `hmac_sha2` | 0x1aba4 | 140 |
| `hmac_sha2_init` | 0x1ac30 | 476 |
| `hmac_sha2_update` | 0x1ae0c | 68 |
| `hmac_sha2_final` | 0x1ae50 | 244 |
| `hmac_sha2_n` | 0x1af44 | 592 |
| `sha2_md5_init` | 0x1b194 | 52 |
| `sha2_md5_update` | 0x1b1c8 | 56 |
| `sha2_md5_final` | 0x1b200 | 96 |
| `kdf5295` | 0x1b260 | 924 |
| `sha2x_txfm_iter0to15` | 0x1b5fc | 1084 |
| `sha2x_txfm_iter16to80` | 0x1ba38 | 1040 |
| `sha2x_transform` | 0x1be48 | 540 |
| `sha2x_u64tou8` | 0x1c064 | 964 |
| `sha2x_update` | 0x1c428 | 480 |
| `sha2x_final` | 0x1c608 | 460 |
| `sha2x_init` | 0x1c7d4 | 252 |
| `ppr_get_cur_bw` | 0x1c8e4 | 80 |
| `ppr_get_flag` | 0x1c934 | 52 |
| `ppr_ser_size_per_band` | 0x1c968 | 132 |
| `ppr_bands_by_bw` | 0x1c9ec | 140 |
| `ppr_ser_size_by_flag` | 0x1ca78 | 64 |
| `ppr_serialize_block` | 0x1cab8 | 344 |
| `ppr_serialize_data` | 0x1cc10 | 492 |
| `ppr_copy_serdata` | 0x1cdfc | 376 |
| `ppr_deser_cpy` | 0x1cf74 | 148 |
| `ppr_get_bw_powers_20` | 0x1d008 | 72 |
| `ppr_get_bw_powers_40` | 0x1d050 | 112 |
| `ppr_get_bw_powers_80` | 0x1d0c0 | 144 |
| `ppr_get_bw_powers_160` | 0x1d150 | 184 |
| `ppr_get_bw_powers_8080` | 0x1d208 | 220 |
| `get_ppr_get_bw_pwrs_fn` | 0x1d2e4 | 36 |
| `ppr_get_bw_powers` | 0x1d308 | 180 |
| `ppr_get_ru_powers` | 0x1d3bc | 188 |
| `ppr_get_dsss_group` | 0x1d478 | 148 |
| `ppr_get_ofdm_group` | 0x1d50c | 240 |
| `ppr_get_nss1_mcs_group` | 0x1d5fc | 80 |
| `ppr_get_he_nss1_mcs_group` | 0x1d64c | 80 |
| `ppr_get_he_ru_nss1_mcs_group` | 0x1d69c | 80 |
| `ppr_get_nss2_mcs_group` | 0x1d6ec | 80 |
| `ppr_get_he_nss2_mcs_group` | 0x1d73c | 92 |
| `ppr_get_he_ru_nss2_mcs_group` | 0x1d798 | 80 |
| `ppr_get_nss3_mcs_group` | 0x1d7e8 | 80 |
| `ppr_get_he_nss3_mcs_group` | 0x1d838 | 80 |
| `ppr_get_he_ru_nss3_mcs_group` | 0x1d888 | 80 |
| `ppr_get_nss4_mcs_group` | 0x1d8d8 | 108 |
| `ppr_get_he_nss4_mcs_group` | 0x1d944 | 108 |
| `ppr_get_he_ru_nss4_mcs_group` | 0x1d9b0 | 108 |
| `ppr_get_mcs_nss_grp_fn` | 0x1da1c | 36 |
| `ppr_get_ru_mcs_nss_grp_fn` | 0x1da40 | 36 |
| `ppr_get_mcs_nss_grp_pwr` | 0x1da64 | 180 |
| `ppr_get_ru_mcs_nss_grp_pwr` | 0x1db18 | 92 |
| `ppr_get_mcs_group` | 0x1db74 | 136 |
| `ppr_ru_get_mcs_group` | 0x1dbfc | 152 |
| `ppr_pwrs_size` | 0x1dc94 | 128 |
| `ppr_init` | 0x1dd14 | 372 |
| `ppr_clear` | 0x1de88 | 104 |
| `ppr_ru_clear` | 0x1def0 | 56 |
| `ppr_size` | 0x1df28 | 52 |
| `ppr_ser_size` | 0x1df5c | 88 |
| `ppr_ser_size_by_bw` | 0x1dfb4 | 44 |
| `ppr_create` | 0x1dfe0 | 128 |
| `ppr_create_prealloc` | 0x1e060 | 260 |
| `ppr_ru_create` | 0x1e164 | 100 |
| `ppr_ru_create_prealloc` | 0x1e1c8 | 136 |
| `ppr_ru_delete` | 0x1e250 | 56 |
| `ppr_init_ser_mem_by_bw` | 0x1e288 | 336 |
| `ppr_init_ser_mem` | 0x1e3d8 | 100 |
| `ppr_delete` | 0x1e43c | 92 |
| `ppr_set_ch_bw` | 0x1e498 | 292 |
| `ppr_get_ch_bw` | 0x1e5bc | 40 |
| `ppr_get_max_bw` | 0x1e5e4 | 28 |
| `ppr_get_dsss` | 0x1e600 | 208 |
| `ppr_get_ofdm` | 0x1e6d0 | 220 |
| `ppr_get_ht_mcs` | 0x1e7ac | 240 |
| `ppr_get_mcs` | 0x1e89c | 240 |
| `ppr_get_vht_mcs` | 0x1e98c | 88 |
| `ppr_get_he_mcs` | 0x1e9e4 | 88 |
| `ppr_get_he_ru_mcs` | 0x1ea3c | 232 |
| `ppr_get_vht_mcs_min` | 0x1eb24 | 280 |
| `ppr_set_dsss` | 0x1ec3c | 188 |
| `ppr_set_ofdm` | 0x1ecf8 | 200 |
| `ppr_set_ht_mcs` | 0x1edc0 | 220 |
| `ppr_set_mcs` | 0x1ee9c | 220 |
| `ppr_set_vht_mcs` | 0x1ef78 | 88 |
| `ppr_set_he_mcs` | 0x1efd0 | 88 |
| `ppr_set_he_ru_mcs` | 0x1f028 | 212 |
| `ppr_set_he_ru_mcs_allmode` | 0x1f0fc | 216 |
| `ppr_set_same_dsss` | 0x1f1d4 | 228 |
| `ppr_set_same_ofdm` | 0x1f2b8 | 240 |
| `ppr_set_same_ht_mcs` | 0x1f3a8 | 260 |
| `ppr_set_same_mcs` | 0x1f4ac | 260 |
| `ppr_set_same_vht_mcs` | 0x1f5b0 | 88 |
| `ppr_set_same_he_mcs` | 0x1f608 | 88 |
| `ppr_set_same_he_ru_mcs` | 0x1f660 | 252 |
| `ppr_apply_max` | 0x1f75c | 196 |
| `ppr_force_disabled_group` | 0x1f820 | 280 |
| `ppr_force_disabled` | 0x1f938 | 1208 |
| `ppr_apply_constraint_to_block` | 0x1fdf0 | 404 |
| `ppr_apply_constraint_total_tx` | 0x1ff84 | 388 |
| `ppr_apply_min` | 0x20108 | 196 |
| `ppr_apply_vector_ceiling` | 0x201cc | 268 |
| `ppr_apply_vector_floor` | 0x202d8 | 264 |
| `ppr_get_max` | 0x203e0 | 208 |
| `ppr_get_dsss_max` | 0x204b0 | 168 |
| `ppr_get_min` | 0x20558 | 392 |
| `ppr_get_max_for_bw` | 0x206e0 | 192 |
| `ppr_get_min_for_bw` | 0x207a0 | 192 |
| `ppr_map_vec_dsss` | 0x20860 | 228 |
| `ppr_map_vec_ofdm` | 0x20944 | 236 |
| `ppr_map_vec_ht_mcs` | 0x20a30 | 260 |
| `ppr_map_vec_vht_mcs` | 0x20b34 | 260 |
| `ppr_map_vec_per_bw` | 0x20c38 | 240 |
| `ppr_map_vec_all` | 0x20d28 | 504 |
| `ppr_set_cmn_val` | 0x20f20 | 116 |
| `ppr_copy_struct` | 0x20f94 | 1240 |
| `ppr_cmn_val_minus` | 0x2146c | 208 |
| `ppr_minus_cmn_val` | 0x2153c | 208 |
| `ppr_plus_cmn_val` | 0x2160c | 208 |
| `ppr_multiply_percentage` | 0x216dc | 232 |
| `ppr_compare_min` | 0x217c4 | 280 |
| `ppr_compare_max` | 0x218dc | 280 |
| `ppr_serialize` | 0x219f4 | 616 |
| `ppr_deserialize_create` | 0x21c5c | 660 |
| `ppr_deserialize` | 0x21ef0 | 580 |
| `ppr_chanspec_bw` | 0x22134 | 180 |
| `ppr_to_dssstlv_per_band` | 0x221e8 | 344 |
| `ppr_to_ofdmtlv_per_band` | 0x22340 | 400 |
| `ppr_to_mcstlv_per_band` | 0x224d0 | 472 |
| `ppr_convert_to_tlv` | 0x226a8 | 1116 |
| `ppr_convert_from_tlv` | 0x22b04 | 688 |
| `ppr_ru_convert_from_tlv` | 0x22db4 | 312 |
| `ppr_get_tlv_size_dsss` | 0x22eec | 96 |
| `ppr_get_ofdmmcs_size` | 0x22f4c | 292 |
| `ppr_ru_get_size` | 0x23070 | 304 |
| `ppr_get_tlv_size` | 0x231a0 | 328 |
| `ppr_get_tlv_ver` | 0x232e8 | 28 |
| `wl_module_cmds_register` | 0x23318 | 192 |
| `wlu_find_cmd` | 0x233d8 | 228 |
| `wl_get_ioctl_version` | 0x234bc | 40 |
| `wl_get_buf` | 0x234e4 | 40 |
| `wl_cmd_init` | 0x2350c | 92 |
| `wlu_init` | 0x23568 | 432 |
| `wlc_ver_major` | 0x23718 | 112 |
| `wl_check` | 0x23788 | 548 |
| `ARGCNT` | 0x239ac | 88 |
| `wl_option` | 0x23a04 | 1120 |
| `wl_cmd_usage` | 0x23e64 | 132 |
| `wl_print_deprecate` | 0x23ee8 | 76 |
| `wl_list` | 0x23f34 | 1064 |
| `wl_cmds_usage` | 0x2435c | 392 |
| `wl_usage` | 0x244e4 | 344 |
| `wl_printint` | 0x2463c | 144 |
| `wl_cfg_option` | 0x246cc | 416 |
| `wl_void` | 0x2486c | 92 |
| `wl_int` | 0x248c8 | 604 |
| `wl_buf` | 0x24b24 | 740 |
| `wl_chspec_from_legacy` | 0x24e08 | 240 |
| `wl_chspec_to_legacy` | 0x24ef8 | 364 |
| `wl_chspec_to_driver` | 0x25064 | 244 |
| `wl_chspec32_to_driver` | 0x25158 | 208 |
| `wl_chspec_from_driver` | 0x25228 | 224 |
| `wl_chspec32_from_driver` | 0x25308 | 200 |
| `download2dongle` | 0x253d0 | 336 |
| `dload_clm` | 0x25520 | 668 |
| `dload_blob` | 0x257bc | 384 |
| `dload_clm_blob` | 0x2593c | 392 |
| `process_clm_data` | 0x25ac4 | 976 |
| `wl_clmload` | 0x25e94 | 304 |
| `process_sflash_data` | 0x25fc4 | 908 |
| `wl_sflashread` | 0x26350 | 500 |
| `wl_sflashdump` | 0x26544 | 800 |
| `wl_sflashload` | 0x26864 | 164 |
| `wl_sflasherase` | 0x26908 | 76 |
| `process_cal_data` | 0x26954 | 1004 |
| `wl_calload` | 0x26d40 | 112 |
| `wl_sflashwrite` | 0x26db0 | 420 |
| `process_cal_dump` | 0x26f54 | 1208 |
| `wl_caldump` | 0x2740c | 196 |
| `wl_bsscfg_int` | 0x274d0 | 620 |
| `wl_gmode` | 0x2773c | 1028 |
| `wl_reg` | 0x27b40 | 3696 |
| `wl_macreg` | 0x289b0 | 1520 |
| `wl_macregx` | 0x28fa0 | 1108 |
| `wl_band_elm` | 0x293f4 | 1256 |
| `wl_rssi` | 0x298dc | 476 |
| `wl_macaddr` | 0x29ab8 | 232 |
| `wl_iov_mac` | 0x29ba0 | 412 |
| `wl_txq_prec_dump` | 0x29d3c | 3928 |
| `wl_scb_bs_data` | 0x2ac94 | 4284 |
| `wl_iov_pktqlog_params` | 0x2bd50 | 3816 |
| `wlu_dump_phytbls` | 0x2cc38 | 580 |
| `wlu_dump` | 0x2ce7c | 832 |
| `wlu_dump_clr` | 0x2d1bc | 280 |
| `wl_staprio` | 0x2d2d4 | 480 |
| `wl_aibss_bcn_force_config` | 0x2d4b4 | 488 |
| `wlu_fixrate` | 0x2d69c | 548 |
| `wlu_ratedump` | 0x2d8c0 | 876 |
| `find_pattern` | 0x2dc2c | 352 |
| `find_pattern2` | 0x2dd8c | 396 |
| `wl_msglevel_usage` | 0x2df18 | 456 |
| `wl_msglevel_print` | 0x2e0e0 | 392 |
| `_wl_msglevel_upd` | 0x2e268 | 136 |
| `wl_msglevel_upd` | 0x2e2f0 | 1272 |
| `_wl_msglevel` | 0x2e7e8 | 624 |
| `wl_msglevel_v1` | 0x2ea58 | 812 |
| `wl_msglevel` | 0x2ed84 | 560 |
| `wl_mcs2rate` | 0x2efb4 | 504 |
| `wl_ratespec2rate` | 0x2f1ac | 488 |
| `wl_printrate` | 0x2f394 | 52 |
| `rate_string2int` | 0x2f3c8 | 132 |
| `rate_int2string` | 0x2f44c | 192 |
| `wl_rate_print` | 0x2f50c | 1280 |
| `wl_rate_mrate` | 0x2fa0c | 1572 |
| `wl_parse_he_vht_spec` | 0x30030 | 392 |
| `wl_rate` | 0x301b8 | 5820 |
| `wl_print_trig_rssi` | 0x31874 | 344 |
| `wl_mpu_read_test` | 0x319cc | 1048 |
| `wl_mpu_write_test` | 0x31de4 | 1888 |
| `wl_mpu_execute_test` | 0x32544 | 644 |
| `wl_bss_max` | 0x327c8 | 356 |
| `wl_phy_rate` | 0x3292c | 640 |
| `wl_assoc_info` | 0x32bac | 1436 |
| `wl_etd_info` | 0x33148 | 1284 |
| `wl_pmkid_info` | 0x3364c | 580 |
| `wl_get_rateset_args_info` | 0x33890 | 348 |
| `wl_rateset_get_fields` | 0x339ec | 356 |
| `wl_rateset_init_fields` | 0x33b50 | 84 |
| `wl_rateset` | 0x33ba4 | 1624 |
| `wl_default_rateset` | 0x341fc | 2804 |
| `wl_txbf_rateset` | 0x34cf0 | 808 |
| `wl_sup_rateset` | 0x35018 | 924 |
| `wl_parse_rateset` | 0x353b4 | 2424 |
| `wl_parse_txbf_rateset` | 0x35d2c | 2380 |
| `wl_power_sel_params` | 0x36678 | 1372 |
| `wl_channel` | 0x36bd4 | 748 |
| `wl_chanspec` | 0x36ec0 | 1812 |
| `wl_sc_chan` | 0x375d4 | 1772 |
| `wl_phy_vcore` | 0x37cc0 | 1248 |
| `wl_dfs_ap_move` | 0x381a0 | 2392 |
| `wl_dfs_max_safe_tx` | 0x38af8 | 1336 |
| `wl_rclass` | 0x39030 | 240 |
| `wl_ether_atoe` | 0x39120 | 180 |
| `wl_ether_etoa` | 0x391d4 | 184 |
| `wl_atoip` | 0x3928c | 164 |
| `wl_ipv6_colon` | 0x39330 | 596 |
| `wl_atoipv6` | 0x39584 | 304 |
| `wl_ipv6toa` | 0x396b4 | 876 |
| `wl_iptoa` | 0x39a20 | 120 |
| `wl_format_ssid` | 0x39a98 | 304 |
| `wl_hexdump` | 0x39bc8 | 296 |
| `wl_plcphdr` | 0x39cf0 | 676 |
| `wl_radio` | 0x39f94 | 660 |
| `ver2str` | 0x3a228 | 276 |
| `wl_version` | 0x3a33c | 440 |
| `wl_rateparam` | 0x3a4f4 | 408 |
| `wl_parse_ssid_list` | 0x3a68c | 396 |
| `wl_scan_prep` | 0x3a818 | 4232 |
| `wl_sendprb` | 0x3b8a0 | 1876 |
| `wl_send_frame` | 0x3bff4 | 112 |
| `wl_roamparms` | 0x3c064 | 1552 |
| `wl_roamchannels` | 0x3c674 | 776 |
| `wl_prio_roam` | 0x3c97c | 532 |
| `wl_roam_prof` | 0x3cb90 | 9784 |
| `wl_silent_roam` | 0x3f1c8 | 2040 |
| `wl_roamstats` | 0x3f9c0 | 332 |
| `wl_roamstats_reset_cnt` | 0x3fb0c | 272 |
| `wl_roamstats_version_get` | 0x3fc1c | 840 |
| `wl_roamstats_status_get` | 0x3ff64 | 948 |
| `wl_roamstats_print_counter_info` | 0x40318 | 240 |
| `wl_roamstats_print_prev_roam_events` | 0x40408 | 272 |
| `wl_roamstats_print_reason_cnt` | 0x40518 | 248 |
| `wl_scan` | 0x40610 | 268 |
| `wl_escan` | 0x4071c | 820 |
| `wl_iscan` | 0x40a50 | 1112 |
| `wl_parse_assoc_params` | 0x40ea8 | 1448 |
| `wl_reassoc` | 0x41450 | 600 |
| `wl_parse_channel_list` | 0x416a8 | 356 |
| `wl_parse_chanspec_list` | 0x4180c | 580 |
| `bcm_print_vs_ie` | 0x41a50 | 276 |
| `dump_rateset` | 0x41b64 | 456 |
| `capmode2str` | 0x41d2c | 116 |
| `wlu_parse_tlvs` | 0x41da0 | 192 |
| `wlu_bcmp` | 0x41e60 | 60 |
| `wlu_is_wpa_ie` | 0x41e9c | 208 |
| `wl_dump_wpa_rsn_ies` | 0x41f6c | 208 |
| `wl_rsn_ie_dump` | 0x4203c | 2776 |
| `wl_rsn_ie_parse_info` | 0x42b14 | 556 |
| `wl_rsn_ie_decode_cntrs` | 0x42d40 | 128 |
| `wl_dump_raw_ie` | 0x42dc0 | 416 |
| `dump_networks` | 0x42f60 | 344 |
| `bcm_wps_version` | 0x430b8 | 428 |
| `bcm_is_wps_configured` | 0x43264 | 208 |
| `bcm_is_wps_ie` | 0x43334 | 204 |
| `wl_dump_wps` | 0x43400 | 164 |
| `bcm_vs_ie_match` | 0x434a4 | 152 |
| `bcm_find_vs_ie` | 0x4353c | 200 |
| `wl_dump_ext_cap` | 0x43604 | 112 |
| `wl_ext_cap_ie_dump` | 0x43674 | 368 |
| `dump_bss_info` | 0x437e4 | 7764 |
| `wl_bcnlenhist` | 0x45638 | 644 |
| `wl_dump_networks` | 0x458bc | 672 |
| `wl_dump_chanlist` | 0x45b5c | 516 |
| `wl_get_frameburst_cot` | 0x45d60 | 264 |
| `wl_dump_chanspecs_defset` | 0x45e68 | 1128 |
| `wl_dump_chanspecs` | 0x462d0 | 2200 |
| `wl_rmc_report_version_get` | 0x46b68 | 840 |
| `wl_rmc_report_data_get` | 0x46eb0 | 1464 |
| `wl_roam_cache` | 0x47468 | 272 |
| `wl_channels_in_country` | 0x47578 | 1208 |
| `wl_get_scan` | 0x47a30 | 696 |
| `wl_get_iscan` | 0x47ce8 | 764 |
| `wl_spect` | 0x47fe4 | 656 |
| `wl_status` | 0x48274 | 928 |
| `wl_deauth_rc` | 0x48614 | 500 |
| `wl_wpa_auth` | 0x48808 | 1524 |
| `wl_set_pmk` | 0x48dfc | 852 |
| `wl_wsec` | 0x49150 | 652 |
| `parse_wep` | 0x493dc | 1292 |
| `wl_get_chanspec_txpwr_max` | 0x498e8 | 1516 |
| `wl_get_txpwr_target_max` | 0x49ed4 | 464 |
| `wl_join_prescanned` | 0x4a0a4 | 1548 |
| `wl_join` | 0x4a6b0 | 5444 |
| `wl_bssid` | 0x4bbf4 | 408 |
| `wl_ssid` | 0x4bd8c | 1220 |
| `wl_smfs_map_type` | 0x4c250 | 180 |
| `wl_disp_smfs` | 0x4c304 | 1048 |
| `wl_smfs_option` | 0x4c71c | 308 |
| `wl_smfstats` | 0x4c850 | 904 |
| `wl_qdbm_to_mw` | 0x4cbd8 | 196 |
| `wl_mw_to_qdbm` | 0x4cc9c | 340 |
| `wl_txpwr1` | 0x4cdf0 | 1344 |
| `wl_txpwr` | 0x4d330 | 560 |
| `wl_get_txpwr_limit` | 0x4d560 | 212 |
| `wl_maclist` | 0x4d634 | 1976 |
| `wl_echo` | 0x4ddec | 584 |
| `wl_out` | 0x4e034 | 60 |
| `wl_ifband` | 0x4e070 | 724 |
| `wl_band` | 0x4e344 | 708 |
| `wl_bandlist` | 0x4e608 | 608 |
| `wl_phylist` | 0x4e868 | 188 |
| `wl_upgrade` | 0x4e924 | 952 |
| `wl_get_pktcnt` | 0x4ecdc | 628 |
| `wlc_cntry_name_to_country` | 0x4ef50 | 148 |
| `wlc_cntry_abbrev_to_country` | 0x4efe4 | 228 |
| `wl_parse_country_spec` | 0x4f0c8 | 360 |
| `wl_country` | 0x4f230 | 2904 |
| `wl_country_ie_override` | 0x4fd88 | 840 |
| `wl_actframe` | 0x500d0 | 1312 |
| `wl_dfs_status` | 0x505f0 | 116 |
| `wl_print_dfs_status` | 0x50664 | 508 |
| `wl_dfs_status_all` | 0x50860 | 116 |
| `wl_print_dfs_sub_status` | 0x508d4 | 788 |
| `wl_print_dfs_status_all` | 0x50be8 | 532 |
| `wl_radar_status` | 0x50dfc | 1088 |
| `wl_radar_sc_status` | 0x5123c | 1140 |
| `wl_clear_radar_status` | 0x516b0 | 100 |
| `wl_radar_subband_status` | 0x51714 | 320 |
| `wlu_reg2args` | 0x51854 | 756 |
| `wl_measure_req` | 0x51b48 | 728 |
| `wl_send_quiet` | 0x51e20 | 556 |
| `wl_pm_mute_tx` | 0x5204c | 532 |
| `wl_send_csa` | 0x52260 | 568 |
| `wl_var_setint` | 0x52498 | 272 |
| `wl_var_get` | 0x525a8 | 312 |
| `wl_var_getint` | 0x526e0 | 228 |
| `wl_var_getandprintstr` | 0x527c4 | 104 |
| `wl_varint` | 0x5282c | 100 |
| `wlu_var_getbuf_param_len` | 0x52890 | 260 |
| `wlu_var_getbuf` | 0x52994 | 244 |
| `wlu_var_getbuf_sm` | 0x52a88 | 244 |
| `wlu_var_getbuf_minimal` | 0x52b7c | 260 |
| `wlu_var_getbuf_med` | 0x52c80 | 248 |
| `wlu_var_setbuf` | 0x52d78 | 236 |
| `wlu_var_setbuf_sm` | 0x52e64 | 236 |
| `wlu_var_setbuf_med` | 0x52f50 | 240 |
| `wl_var_void` | 0x53040 | 92 |
| `wl_prefixiovar_mkbuf` | 0x5309c | 408 |
| `wl_bssiovar_mkbuf` | 0x53234 | 112 |
| `wlu_bssiovar_setbuf` | 0x532a4 | 136 |
| `wl_bssiovar_getbuf` | 0x5332c | 132 |
| `wlu_bssiovar_get` | 0x533b0 | 212 |
| `wl_bssiovar_set` | 0x53484 | 108 |
| `wl_bssiovar_getint` | 0x534f0 | 208 |
| `wl_bssiovar_setint` | 0x535c0 | 180 |
| `wl_chan_info` | 0x53674 | 588 |
| `wl_chan_info_channel` | 0x538c0 | 884 |
| `wl_sta_info` | 0x53c34 | 11528 |
| `wl_revinfo` | 0x5693c | 3056 |
| `wl_rm_request` | 0x5752c | 2740 |
| `wl_rm_report` | 0x57fe0 | 2920 |
| `wl_join_pref` | 0x58b48 | 848 |
| `wl_join_pref_print_ie` | 0x58e98 | 1504 |
| `wl_join_pref_print_akm` | 0x59478 | 404 |
| `wl_join_pref_print_cipher_suite` | 0x5960c | 484 |
| `wl_assoc_pref` | 0x597f0 | 832 |
| `wme_tx_params` | 0x59b30 | 1784 |
| `wl_wme_ac_req` | 0x5a228 | 2520 |
| `wl_wme_apsd_sta` | 0x5ac00 | 1232 |
| `wl_wme_dp` | 0x5b0d0 | 1036 |
| `wl_lifetime` | 0x5b4dc | 1048 |
| `wl_add_ie` | 0x5b8f4 | 76 |
| `wl_del_ie` | 0x5b940 | 76 |
| `wl_mk_ie_setbuf` | 0x5b98c | 1456 |
| `wl_vndr_ie` | 0x5bf3c | 344 |
| `wl_list_ie` | 0x5c094 | 180 |
| `_wl_list_ie` | 0x5c148 | 104 |
| `wl_dump_ie_buf` | 0x5c1b0 | 756 |
| `wl_rand` | 0x5c4a4 | 156 |
| `wl_struct_ver` | 0x5c540 | 228 |
| `wl_wlc_ver` | 0x5c624 | 336 |
| `wl_wme_counters` | 0x5c774 | 2584 |
| `get_oui_bytes` | 0x5d18c | 228 |
| `get_ie_data` | 0x5d270 | 192 |
| `hexstrtobitvec` | 0x5d330 | 624 |
| `wl_bitvecext` | 0x5d5a0 | 1248 |
| `wl_eventbitvec` | 0x5da80 | 448 |
| `wl_auto_channel_sel` | 0x5dc40 | 616 |
| `wl_varstr` | 0x5dea8 | 204 |
| `wc_cmd_check` | 0x5df74 | 36 |
| `wme_maxbw_params` | 0x5df98 | 1036 |
| `wl_antsel` | 0x5e3a4 | 1284 |
| `wl_txfifo_sz` | 0x5e8a8 | 376 |
| `wl_escan_event_check` | 0x5ea20 | 2304 |
| `wl_escanresults` | 0x5f320 | 3076 |
| `wl_event_check` | 0x5ff24 | 5080 |
| `hexstr2hex` | 0x612fc | 188 |
| `prhexstr` | 0x613b8 | 136 |
| `wl_hs20_ie` | 0x61440 | 872 |
| `wl_offload_cmpnt` | 0x617a8 | 1432 |
| `wl_hostipv6_extended` | 0x61d40 | 1100 |
| `wl_hostipv6` | 0x6218c | 504 |
| `wl_hostip` | 0x62384 | 360 |
| `wl_mcast_ar` | 0x624ec | 544 |
| `wl_rate_histo_print` | 0x6270c | 628 |
| `wl_rate_histo` | 0x62980 | 124 |
| `wl_mac_rate_histo` | 0x629fc | 764 |
| `wl_sarlimit` | 0x62cf8 | 912 |
| `wl_dump_pmu` | 0x63088 | 956 |
| `wl_antgain` | 0x63444 | 512 |
| `wl_pattern_atoh` | 0x63644 | 348 |
| `wl_send_wpa_m1` | 0x637a0 | 544 |
| `wl_wakeup_data` | 0x639c0 | 556 |
| `wl_memuse` | 0x63bec | 788 |
| `wl_seq_batch_in_client` | 0x63f00 | 60 |
| `wl_seq_start` | 0x63f3c | 288 |
| `wl_seq_stop` | 0x6405c | 884 |
| `wl_mkeep_alive` | 0x643d0 | 1612 |
| `wl_srchmem` | 0x64a1c | 884 |
| `wl_ptk_start` | 0x64d90 | 608 |
| `wl_print_mcsset` | 0x64ff0 | 200 |
| `wl_print_vhtmcsset` | 0x650b8 | 276 |
| `wl_print_hemcsset` | 0x651cc | 276 |
| `wl_print_txbf_mcsset` | 0x652e0 | 208 |
| `wl_print_txbf_vhtmcsset` | 0x653b0 | 284 |
| `wl_assertlog` | 0x654cc | 464 |
| `cca_level` | 0x6569c | 156 |
| `free_cca_array` | 0x65738 | 192 |
| `wl_cca_print_measurement` | 0x657f8 | 472 |
| `wl_cca_get_stats_ext` | 0x659d0 | 3888 |
| `wl_cca_get_stats` | 0x66900 | 2512 |
| `wl_txdelay_params` | 0x672d0 | 536 |
| `dlystat_dump` | 0x674e8 | 1280 |
| `wl_dlystats` | 0x679e8 | 368 |
| `wl_dlystats_clear` | 0x67b58 | 96 |
| `wl_rpmt` | 0x67bb8 | 620 |
| `wl_tsf` | 0x67e24 | 888 |
| `wl_event_log_set_init` | 0x6819c | 356 |
| `wl_event_log_set_expand` | 0x68300 | 356 |
| `wl_event_log_set_shrink` | 0x68464 | 380 |
| `wl_event_log_tag_control` | 0x685e0 | 620 |
| `wl_event_log_get` | 0x6884c | 424 |
| `wl_event_log_set_type` | 0x689f4 | 988 |
| `wl_event_log_flush_prsrv` | 0x68dd0 | 1032 |
| `wlu_mempool` | 0x691d8 | 372 |
| `wl_rxfifo_counters` | 0x6934c | 516 |
| `wl_ie` | 0x69550 | 1592 |
| `wl_nwoe_ifconfig` | 0x69b88 | 488 |
| `wl_sleep_ret_ext` | 0x69d70 | 1880 |
| `wl_stamon_sta_config` | 0x6a4c8 | 1856 |
| `wl_monitor_promisc_level` | 0x6ac08 | 1384 |
| `wl_bss_peer_info` | 0x6b170 | 2296 |
| `wl_aibss_txfail_config` | 0x6ba68 | 532 |
| `get_config_iovar_entry` | 0x6bc7c | 184 |
| `wl_bcm_config_print` | 0x6bd34 | 296 |
| `wl_bcm_config` | 0x6be5c | 856 |
| `wl_desired_bssid` | 0x6c1b4 | 232 |
| `wl_dump_modesw_dyn_bwsw` | 0x6c29c | 220 |
| `wl_dfs_channel_forced` | 0x6c378 | 1800 |
| `wl_setiproute` | 0x6ca80 | 1292 |
| `wl_modesw_timecal` | 0x6cf8c | 436 |
| `wl_pcie_bus_throughput_params` | 0x6d140 | 916 |
| `wl_interface_create_action_v3` | 0x6d4d4 | 1440 |
| `wl_interface_create_action_v2` | 0x6da74 | 1176 |
| `wl_interface_create_action` | 0x6df0c | 324 |
| `wl_interface_remove_action` | 0x6e050 | 228 |
| `wl_phy_txpwrcap_tbl` | 0x6e134 | 5904 |
| `wl_mac_captr` | 0x6f844 | 4052 |
| `wl_macdbg_pmac` | 0x70818 | 1032 |
| `wl_mu_rate` | 0x70c20 | 836 |
| `wl_mu_group` | 0x70f64 | 2472 |
| `wl_mu_policy` | 0x7190c | 1540 |
| `wl_svmp_mem` | 0x71f10 | 868 |
| `wl_svmp_sampcol_printf_configs` | 0x72274 | 936 |
| `wl_svmp_sampcol` | 0x7261c | 2360 |
| `wl_winver` | 0x73914 | 272 |
| `wl_get_tcmstbl_entry` | 0x73a24 | 1096 |
| `wl_nd_ra_limit_intv` | 0x73e6c | 1276 |
| `wl_ccode_info` | 0x74368 | 1088 |
| `wl_wait_for_event` | 0x747a8 | 1408 |
| `wl_sim_pm` | 0x74d28 | 1212 |
| `wl_idauth` | 0x751e4 | 492 |
| `wl_idauth_config_set` | 0x753d0 | 1524 |
| `wl_idauth_config_get` | 0x759c4 | 1164 |
| `wl_idauth_dump_counters` | 0x75e50 | 820 |
| `wl_idauth_dump_peer_info` | 0x76184 | 1148 |
| `fsize` | 0x76600 | 348 |
| `wl_wake_timer` | 0x7675c | 1660 |
| `wl_utrace_capture` | 0x76dd8 | 828 |
| `wl_sdc_trigger` | 0x77114 | 540 |
| `wl_eventaggr` | 0x77330 | 1584 |
| `wl_block_channel` | 0x77960 | 1780 |
| `wl_avsdump` | 0x78054 | 1188 |
| `rwl_serial_fragmented_response_fe` | 0x7850c | 1132 |
| `rwl_information_dongle` | 0x78978 | 612 |
| `ctrlc_handler` | 0x78bdc | 60 |
| `rwl_shell_information_fe` | 0x78c18 | 900 |
| `rwl_shell_cmd_proc` | 0x78f9c | 536 |
| `rwl_queryinformation_fe` | 0x791b4 | 276 |
| `rwl_setinformation_fe` | 0x792c8 | 276 |
| `rwl_usage` | 0x793dc | 1216 |
| `rwl_dongle_shellresp` | 0x7989c | 668 |
| `rwl_detect` | 0x79b38 | 268 |
| `rwl_check_port_number` | 0x79c44 | 116 |
| `cmd_cat_get` | 0x79ccc | 272 |
| `wl_iov_usage` | 0x79ddc | 584 |
| `iov_parse_args_alloc` | 0x7a024 | 1848 |
| `wl_iov_cleanup` | 0x7a75c | 124 |
| `wl_iov_find` | 0x7a7d8 | 168 |
| `wl_iov_var_match` | 0x7a880 | 324 |
| `wl_iov_qualify` | 0x7a9c4 | 328 |
| `show_header` | 0x7ab0c | 668 |
| `wl_iov_check_show` | 0x7ada8 | 880 |
| `wl_iov_check_ui_not_driver` | 0x7b118 | 468 |
| `wl_iov_names` | 0x7b2ec | 668 |
| `wl_help_usage` | 0x7b588 | 232 |
| `cat_str_to_flag` | 0x7b670 | 308 |
| `wl_cmd_count` | 0x7b7a4 | 216 |
| `print_cmds` | 0x7b87c | 384 |
| `wl_cmd_help` | 0x7b9fc | 556 |
| `wl_iovar_mkbuf` | 0x7bc3c | 252 |
| `init_cmd_batchingmode` | 0x7bd38 | 72 |
| `clean_up_cmd_list` | 0x7bd80 | 180 |
| `add_one_batched_cmd` | 0x7be34 | 516 |
| `wlu_get_req_buflen` | 0x7c038 | 140 |
| `wlu_sc_wrapper` | 0x7c0c4 | 752 |
| `wlu_wlc_wrapper` | 0x7c3b4 | 828 |
| `wlu_get` | 0x7c6f0 | 448 |
| `wlu_set` | 0x7c8b0 | 400 |
| `wlu_iovar_getbuf` | 0x7ca40 | 128 |
| `wlu_iovar_setbuf` | 0x7cac0 | 136 |
| `wlu_iovar_get` | 0x7cb48 | 196 |
| `wlu_iovar_set` | 0x7cc0c | 100 |
| `wlu_iovar_getint` | 0x7cc70 | 196 |
| `wlu_iovar_setint` | 0x7cd34 | 172 |
| `wlu_lookup_name` | 0x7cde0 | 168 |
| `syserr` | 0x7ceb0 | 108 |
| `wl_driver_nl80211` | 0x7cf1c | 40 |
| `wl_driver_ioctl` | 0x7cf44 | 140 |
| `wl_ioctl` | 0x7cfd0 | 260 |
| `wl_get_dev_type` | 0x7d0d4 | 308 |
| `wl_find` | 0x7d208 | 712 |
| `ioctl_queryinformation_fe` | 0x7d4d0 | 168 |
| `ioctl_setinformation_fe` | 0x7d578 | 168 |
| `wl_get` | 0x7d620 | 244 |
| `wl_set` | 0x7d714 | 244 |
| `main` | 0x7d808 | 2388 |
| `process_args` | 0x7e15c | 1612 |
| `do_interactive` | 0x7e7a8 | 920 |
| `wl_do_cmd` | 0x7eb40 | 724 |
| `wl_find_cmd` | 0x7ee14 | 40 |
| `def_handler` | 0x7ee3c | 84 |
| `rwl_shell_createproc` | 0x7ee90 | 116 |
| `rwl_shell_killproc` | 0x7ef04 | 56 |
| `remote_CDC_tx` | 0x7ef50 | 300 |
| `remote_CDC_rx_hdr` | 0x7f07c | 156 |
| `remote_CDC_rx` | 0x7f118 | 180 |
| `rwl_swap_header` | 0x7f1cc | 116 |
| `rwl_sleep` | 0x7f254 | 44 |
| `get_clm_rate_group_label` | 0x7f294 | 64 |
| `get_reg_rate_string_from_ratespec` | 0x7f2d4 | 100 |
| `get_reg_rate_index_from_ratespec` | 0x7f338 | 484 |
| `get_legacy_reg_rate_index` | 0x7f51c | 204 |
| `get_legacy_rate_identifier` | 0x7f5e8 | 228 |
| `get_legacy_mode_identifier` | 0x7f6cc | 480 |
| `get_ht_reg_rate_index` | 0x7f8ac | 196 |
| `get_vht_reg_rate_index` | 0x7f970 | 344 |
| `get_he_reg_rate_index` | 0x7fac8 | 268 |
| `get_vht_rate_identifier` | 0x7fbd4 | 128 |
| `get_vht_ss1_mode_identifier` | 0x7fc54 | 612 |
| `get_vht_ss2_mode_identifier` | 0x7feb8 | 456 |
| `get_vht_ss3_mode_identifier` | 0x80080 | 340 |
| `get_vht_ss4_mode_identifier` | 0x801d4 | 224 |
| `get_he_ss1_mode_identifier` | 0x802b4 | 432 |
| `get_he_ss2_mode_identifier` | 0x80464 | 340 |
| `get_he_ss3_mode_identifier` | 0x805b8 | 224 |
| `get_mode_name` | 0x80698 | 92 |
| `cntr_ver_to_tbl_info` | 0x80708 | 192 |
| `wlu_get_cntr_xtlv_info` | 0x807c8 | 2316 |
| `get_counter_offset_xtlv` | 0x810d4 | 988 |
| `get_counter_offset` | 0x814b0 | 420 |
| `print_counter_help` | 0x81654 | 288 |
| `wl_is_legacyfw` | 0x81774 | 240 |
| `wl_subcounters` | 0x81864 | 2204 |
| `prcnt_init` | 0x82100 | 40 |
| `prcnt_filter1` | 0x82128 | 272 |
| `prcnt_filter` | 0x82238 | 88 |
| `prcnt_prnl1` | 0x82290 | 92 |
| `wl_get_he_cnt_info` | 0x822ec | 352 |
| `wl_get_he_omi_cnt_info` | 0x8244c | 324 |
| `wl_counters_cbfn` | 0x82590 | 133840 |
| `wl_counters` | 0xa3060 | 2132 |
| `wl_if_counters_cbfn` | 0xa38b4 | 10256 |
| `wl_ifstats_counters` | 0xa60c4 | 1072 |
| `wl_if_counters_before_ifstats` | 0xa64f4 | 5324 |
| `wl_if_counters` | 0xa79c0 | 236 |
| `wl_delta_stats` | 0xa7aac | 4984 |
| `wl_swdiv_stats` | 0xa8e24 | 10548 |
| `wl_clear_counters` | 0xab758 | 332 |
| `wl_chanctxt_stats` | 0xab8a4 | 1216 |
| `wluc_ampdu_module_init` | 0xabd78 | 56 |
| `wl_ampdu_tid` | 0xabdb0 | 356 |
| `wl_ampdu_aggr` | 0xabf14 | 860 |
| `wl_ampdu_retry_limit_tid` | 0xac270 | 344 |
| `wl_ampdu_rr_retry_limit_tid` | 0xac3c8 | 344 |
| `wl_ampdu_send_addba` | 0xac520 | 300 |
| `wl_ampdu_send_delba` | 0xac64c | 368 |
| `wluc_ampdu_cmn_module_init` | 0xac7d0 | 56 |
| `wl_ampdu_activate_test` | 0xac808 | 252 |
| `wluc_ap_module_init` | 0xac918 | 56 |
| `wl_radar` | 0xac950 | 648 |
| `wl_apiov` | 0xacbd8 | 76 |
| `wl_bsscfg_enable` | 0xacc24 | 1140 |
| `dump_management_fields` | 0xad098 | 2708 |
| `dump_management_info` | 0xadb2c | 544 |
| `wl_management_info` | 0xadd4c | 876 |
| `wl_maclist_1` | 0xae0b8 | 384 |
| `wluc_arpoe_module_init` | 0xae24c | 56 |
| `wl_arp_stats` | 0xae284 | 1744 |
| `wluc_bmac_module_init` | 0xae968 | 56 |
| `wl_gpioout` | 0xae9a0 | 1112 |
| `wl_nvsource` | 0xaedf8 | 348 |
| `wlu_srwrite_data` | 0xaef54 | 2388 |
| `wlu_ccreg` | 0xaf8a8 | 756 |
| `wlu_pmuchipctrlreg` | 0xafb9c | 756 |
| `wlu_gcichipctrlreg` | 0xafe90 | 756 |
| `wlu_reg3args` | 0xb0184 | 692 |
| `wlu_reg1or3args` | 0xb0438 | 720 |
| `wlu_ctmode` | 0xb0708 | 1716 |
| `wl_coma` | 0xb0dbc | 480 |
| `wl_var_getinthex` | 0xb0f9c | 244 |
| `wl_printlasterror` | 0xb1090 | 188 |
| `wl_devpath` | 0xb114c | 256 |
| `wl_diag` | 0xb124c | 732 |
| `wl_country_sku_override` | 0xb1528 | 352 |
| `wl_clmflags` | 0xb1688 | 576 |
| `wluc_bssload_module_init` | 0xb18dc | 56 |
| `wl_bssload_static` | 0xb1914 | 1016 |
| `wl_bssload_report` | 0xb1d0c | 556 |
| `wl_bssload_report_event` | 0xb1f38 | 924 |
| `wl_bssload_event_cb` | 0xb22d4 | 556 |
| `wl_bssload_event_check` | 0xb2500 | 164 |
| `wluc_btcx_module_init` | 0xb25b8 | 56 |
| `wl_btc_print_profile` | 0xb25f0 | 712 |
| `wl_btc_profile` | 0xb28b8 | 2800 |
| `wl_btc_2g_shchain_disable` | 0xb33a8 | 636 |
| `wl_btc_wifi_prot` | 0xb3624 | 3012 |
| `wl_btc_ulmu_config` | 0xb41e8 | 1792 |
| `wluc_cac_module_init` | 0xb48fc | 56 |
| `wl_cac_format_tspec_htod` | 0xb4934 | 1964 |
| `wl_cac_format_tspec_dtoh` | 0xb50e0 | 1964 |
| `wl_cac_addts_usage` | 0xb588c | 908 |
| `wl_cac_delts_usage` | 0xb5c18 | 268 |
| `wl_cac` | 0xb5d24 | 2964 |
| `wl_tslist` | 0xb68b8 | 856 |
| `wl_tspec` | 0xb6c10 | 880 |
| `wl_tslist_ea` | 0xb6f80 | 716 |
| `wl_tspec_ea` | 0xb724c | 844 |
| `wl_print_tspec` | 0xb7598 | 1244 |
| `wl_cac_delts_ea` | 0xb7a74 | 968 |
| `wluc_hc_module_init` | 0xb7e50 | 56 |
| `wl_hc` | 0xb7e88 | 1104 |
| `wl_hc_int` | 0xb82d8 | 132 |
| `wl_hc_exclude_bitmap` | 0xb835c | 132 |
| `wl_hc_setints` | 0xb83e0 | 588 |
| `wl_hc_getints` | 0xb862c | 896 |
| `wl_hc_cmd_lookup` | 0xb89ac | 136 |
| `wl_hc_subcommand_list_dump` | 0xb8a34 | 132 |
| `wluc_he_module_init` | 0xb8acc | 32 |
| `wl_he_cmd` | 0xb8aec | 476 |
| `wl_he_iovt2len` | 0xb8cc8 | 108 |
| `wl_he_get_uint_cb` | 0xb8d34 | 84 |
| `wl_he_pack_uint_cb` | 0xb8d88 | 412 |
| `wl_he_cmd_uint` | 0xb8f24 | 792 |
| `wl_he_cmd_muedca` | 0xb923c | 1112 |
| `wl_omi_config_dump` | 0xb9694 | 396 |
| `wl_he_cmd_omi_config` | 0xb9820 | 2560 |
| `wl_omi_ulmu_dis_status_dump` | 0xba220 | 300 |
| `wl_he_cmd_omi_status` | 0xba34c | 692 |
| `wluc_heb_module_init` | 0xba614 | 32 |
| `wl_heb_cmd` | 0xba634 | 336 |
| `wl_heb_cmd_enab` | 0xba784 | 356 |
| `wl_heb_cmd_num_heb` | 0xba8e8 | 356 |
| `wl_heb_cmd_counters` | 0xbaa4c | 1148 |
| `wl_heb_cmd_clear_counters` | 0xbaec8 | 232 |
| `wl_heb_cmd_config` | 0xbafb0 | 1836 |
| `wl_heb_cmd_status` | 0xbb6dc | 2620 |
| `wluc_hmaptest_module_init` | 0xbc12c | 56 |
| `wl_hmaptest` | 0xbc164 | 1292 |
| `wl_hmap` | 0xbc670 | 876 |
| `wluc_ht_module_init` | 0xbc9f0 | 56 |
| `wl_nrate_print` | 0xbca28 | 1616 |
| `wl_nrate` | 0xbd078 | 1668 |
| `wl_bw_cap` | 0xbd6fc | 828 |
| `wl_cur_mcsset` | 0xbda38 | 168 |
| `wl_txmcsset` | 0xbdae0 | 104 |
| `wl_rxmcsset` | 0xbdb48 | 104 |
| `wluc_interfere_module_init` | 0xbdbc4 | 56 |
| `wl_itfr_get_stats` | 0xbdbfc | 368 |
| `wluc_keep_alive_module_init` | 0xbdd80 | 56 |
| `wl_keep_alive` | 0xbddb8 | 1080 |
| `wluc_keymgmt_module_init` | 0xbe204 | 56 |
| `wl_wepstatus` | 0xbe23c | 316 |
| `wl_primary_key` | 0xbe378 | 616 |
| `wl_addwep` | 0xbe5e0 | 820 |
| `wl_rmwep` | 0xbe914 | 488 |
| `wl_wsec_test` | 0xbeafc | 1348 |
| `wl_wsec_info_tlv_cb` | 0xbf040 | 268 |
| `wl_wsec_info_usage` | 0xbf14c | 344 |
| `wl_wsec_info` | 0xbf2a4 | 1008 |
| `wl_keys` | 0xbf694 | 2100 |
| `wl_tsc` | 0xbfec8 | 448 |
| `wluc_led_module_init` | 0xc009c | 56 |
| `wl_ledbh` | 0xc00d4 | 552 |
| `wl_led_blink_sync` | 0xc02fc | 824 |
| `wluc_lq_module_init` | 0xc0648 | 56 |
| `wl_chan_qual_event` | 0xc0680 | 2348 |
| `wl_rssi_event` | 0xc0fac | 812 |
| `wl_chanim_state` | 0xc12d8 | 436 |
| `wl_chanim_mode` | 0xc148c | 568 |
| `wl_chanim_acs_record` | 0xc16c4 | 516 |
| `wl_chanim_stats` | 0xc18c8 | 2572 |
| `wl_lqcm` | 0xc22d4 | 680 |
| `wluc_ltecx_module_init` | 0xc2590 | 56 |
| `wl_wci2_config` | 0xc25c8 | 2768 |
| `wl_mws_params` | 0xc3098 | 1368 |
| `wl_mws_wci2_msg` | 0xc35f0 | 1056 |
| `wl_mws_frame_config` | 0xc3a10 | 1744 |
| `wl_mws_antmap` | 0xc40e0 | 1368 |
| `wl_mws_antmap_2nd` | 0xc4638 | 860 |
| `wl_mws_oclmap` | 0xc4994 | 1168 |
| `wl_mws_scanreq_bm` | 0xc4e24 | 928 |
| `wluc_macsmpl_module_init` | 0xc51d8 | 56 |
| `wl_macsmpl` | 0xc5210 | 1188 |
| `wl_macsmpl_status_dump` | 0xc56b4 | 328 |
| `wluc_mfp_module_init` | 0xc5810 | 56 |
| `wl_mfp_config` | 0xc5848 | 368 |
| `wl_mfp_sha256` | 0xc59b8 | 436 |
| `wl_mfp_sa_query` | 0xc5b6c | 760 |
| `wl_mfp_disassoc` | 0xc5e64 | 528 |
| `wl_mfp_deauth` | 0xc6074 | 528 |
| `wl_mfp_assoc` | 0xc6284 | 528 |
| `wl_mfp_auth` | 0xc6494 | 528 |
| `wl_mfp_reassoc` | 0xc66a4 | 528 |
| `wl_mfp_bip_test` | 0xc68b4 | 348 |
| `wluc_obss_module_init` | 0xc6a24 | 56 |
| `wl_obss_scan_params_range_chk` | 0xc6a5c | 992 |
| `wl_obss_scan` | 0xc6e3c | 2728 |
| `wl_obss_coex_action` | 0xc78e4 | 1164 |
| `wluc_offloads_module_init` | 0xc7d84 | 56 |
| `wlu_offloads_stats` | 0xc7dbc | 616 |
| `wl_ol_notify_bcn_ie` | 0xc8024 | 1048 |
| `wluc_ota_module_init` | 0xc8450 | 56 |
| `wl_ota_display_test_init_info` | 0xc8488 | 356 |
| `wl_ota_display_rt_info` | 0xc85ec | 228 |
| `wl_ota_display_test_option` | 0xc86d0 | 668 |
| `wl_ota_validate_string` | 0xc896c | 280 |
| `wl_ota_pwrinfo_parse` | 0xc8a84 | 312 |
| `wl_ota_parse_test_init` | 0xc8bbc | 552 |
| `wl_ota_test_parse_test_option` | 0xc8de4 | 1424 |
| `wl_ota_test_parse_rate_string` | 0xc9374 | 616 |
| `wl_ota_test_parse_arg` | 0xc95dc | 912 |
| `wl_load_cmd_stream` | 0xc996c | 1196 |
| `ota_loadtest` | 0xc9e18 | 952 |
| `wl_ota_loadtest` | 0xca1d0 | 80 |
| `wl_otatest_display_skip_test_reason` | 0xca220 | 264 |
| `wl_otatest_status` | 0xca328 | 808 |
| `wl_otatest_rssi` | 0xca650 | 660 |
| `wl_ota_teststop` | 0xca8e4 | 64 |
| `otp_crc8` | 0xca938 | 120 |
| `wluc_otp_module_init` | 0xca9b0 | 56 |
| `wlu_get_otp_read_buf` | 0xca9e8 | 244 |
| `wlu_read_otp_data` | 0xcaadc | 236 |
| `wlu_get_crc_config` | 0xcabc8 | 964 |
| `wlu_get_last_crc` | 0xcaf8c | 236 |
| `wlu_is_crc_mem_avail` | 0xcb078 | 172 |
| `wlu_update_crc` | 0xcb124 | 1160 |
| `wlu_check_otp_integrity` | 0xcb5ac | 176 |
| `wlu_otpcrc_validate_otp` | 0xcb65c | 368 |
| `otpread_and_compare` | 0xcb7cc | 360 |
| `wlu_ciswrite` | 0xcb934 | 1740 |
| `wlu_cisupdate` | 0xcc000 | 2700 |
| `wlu_otpcrc` | 0xcca8c | 728 |
| `wlu_otpcrcconfig` | 0xccd64 | 2624 |
| `wlu_cisdump` | 0xcd7a4 | 1740 |
| `wl_otpraw` | 0xcde70 | 2312 |
| `wl_otpw` | 0xce778 | 1444 |
| `wl_otpdump_iter` | 0xced1c | 708 |
| `wl_otpecc_rows` | 0xcefe0 | 356 |
| `wl_otpecc_rowslock` | 0xcf144 | 508 |
| `wl_otpecc_rowsdump` | 0xcf340 | 1592 |
| `wl_var_setintandprintstr` | 0xcf978 | 444 |
| `wluc_phy_module_init` | 0xcfb48 | 56 |
| `wl_phy_rssi_ant` | 0xcfb80 | 1140 |
| `wl_phy_snr_ant` | 0xcfff4 | 680 |
| `wl_phy_bsscolor` | 0xd029c | 864 |
| `wl_phymsglevel` | 0xd05fc | 1316 |
| `wl_get_instant_power` | 0xd0b20 | 828 |
| `wl_evm` | 0xd0e5c | 592 |
| `wl_tssi` | 0xd10ac | 276 |
| `wl_atten` | 0xd11c0 | 1732 |
| `wl_interfere` | 0xd1884 | 1552 |
| `wl_interfere_override` | 0xd1e94 | 1628 |
| `wl_aci_args` | 0xd24f0 | 10164 |
| `wl_do_samplecollect_lcn40` | 0xd4ca4 | 460 |
| `wl_do_samplecollect_n` | 0xd4e70 | 372 |
| `wl_do_samplecollect` | 0xd4fe4 | 1316 |
| `phy_macfifo_play_usage` | 0xd5508 | 32 |
| `wl_phy_macfifo_play_args_parse` | 0xd5528 | 648 |
| `wl_phy_macfifo_play_print_status` | 0xd57b0 | 528 |
| `wl_phy_macfifo_play_file_sanity_check` | 0xd59c0 | 532 |
| `wl_phy_macfifo_play_upload_file` | 0xd5bd4 | 468 |
| `wl_phy_macfifo_play` | 0xd5da8 | 1028 |
| `wl_sample_collect` | 0xd61ac | 2916 |
| `wl_test_tssi` | 0xd6d10 | 524 |
| `wl_test_tssi_offs` | 0xd6f1c | 524 |
| `wl_test_idletssi` | 0xd7128 | 516 |
| `wl_tempsense` | 0xd732c | 792 |
| `wl_tx_tone_tssi` | 0xd7644 | 848 |
| `wl_phy_rssiant` | 0xd7994 | 724 |
| `wl_pkteng_sweep_counters` | 0xd7c68 | 240 |
| `wl_pkteng_rx_pkt` | 0xd7d58 | 588 |
| `wl_pkteng_stats` | 0xd7fa4 | 2344 |
| `wl_pkteng_status` | 0xd88cc | 132 |
| `wl_phy_papdepstbl` | 0xd8950 | 288 |
| `wl_phy_txiqcc` | 0xd8a70 | 1104 |
| `wl_phy_txlocc` | 0xd8ec0 | 1488 |
| `wl_rssi_cal_freq_grp_2g` | 0xd9490 | 676 |
| `wl_phy_rssi_gain_delta_2g_sub` | 0xd9734 | 1304 |
| `wl_phy_rssi_gain_delta_2g` | 0xd9c4c | 1264 |
| `wl_phy_rssi_gain_delta_5g` | 0xda13c | 1484 |
| `wl_phy_rxgainerr_2g` | 0xda708 | 792 |
| `wl_phy_rxgainerr_5g` | 0xdaa20 | 800 |
| `wl_phytable` | 0xdad40 | 904 |
| `wl_phy_force_crsmin` | 0xdb0c8 | 608 |
| `wl_phy_bbmult` | 0xdb328 | 708 |
| `wl_phy_txpwrindex` | 0xdb5ec | 972 |
| `wl_phy_forcecal` | 0xdb9b8 | 732 |
| `wl_phy_force_vsdb_chans` | 0xdbc94 | 572 |
| `wl_phy_pavars` | 0xdbed0 | 2832 |
| `wl_phy_povars` | 0xdc9e0 | 1672 |
| `wl_phy_rpcalvars` | 0xdd068 | 1716 |
| `wl_phy_rpcalphasevars` | 0xdd71c | 1016 |
| `wl_phy_fem` | 0xddb14 | 1368 |
| `wl_phy_maxpower` | 0xde06c | 1192 |
| `wl_pkteng` | 0xde514 | 2792 |
| `wl_get_trig_info` | 0xdeffc | 1028 |
| `wl_pkteng_trig_fill` | 0xdf400 | 2544 |
| `wl_rxiq_prepare` | 0xdfdf0 | 2216 |
| `wl_rxiq_print` | 0xe0698 | 1300 |
| `wl_rxiq` | 0xe0bac | 308 |
| `wl_rxiq_sweep` | 0xe0ce0 | 2060 |
| `wl_phy_debug_cmd` | 0xe14ec | 164 |
| `wl_rifs` | 0xe1590 | 360 |
| `wl_rifs_advert` | 0xe16f8 | 360 |
| `wlu_afeoverride` | 0xe1860 | 624 |
| `wl_radar_args` | 0xe1ad0 | 1772 |
| `wl_radar_thrs` | 0xe21bc | 560 |
| `wl_radar_thrs2` | 0xe23ec | 1596 |
| `wl_phy_dyn_switch_th` | 0xe2a28 | 964 |
| `wl_phy_tpc_av` | 0xe2dec | 500 |
| `wl_phy_tpc_vmid` | 0xe2fe0 | 500 |
| `wl_patrim` | 0xe31d4 | 228 |
| `dump_unit_txbfgain` | 0xe32b8 | 216 |
| `dump_txbfgain` | 0xe3390 | 316 |
| `wl_txbf_expgain` | 0xe34cc | 1372 |
| `wl_txcal_gainsweep_meas` | 0xe3a28 | 2120 |
| `wl_txcal_gainsweep_range` | 0xe4270 | 1772 |
| `wl_txcal_gainsweep` | 0xe495c | 2544 |
| `wl_txcal_mode` | 0xe534c | 272 |
| `wl_txcal_pwr_tssi_tbl` | 0xe545c | 4156 |
| `wl_olpc_anchoridx` | 0xe6498 | 1672 |
| `wl_read_estpwrlut` | 0xe6b20 | 500 |
| `wl_olpc_offset` | 0xe6d14 | 516 |
| `wl_txcal_temp` | 0xe6f18 | 3220 |
| `wl_btcoex_desense_rxgain` | 0xe7bac | 920 |
| `wl_rssilog` | 0xe7f44 | 708 |
| `wl_dbg_regval` | 0xe8208 | 1208 |
| `wluc_pkt_filter_module_init` | 0xe86d4 | 56 |
| `wl_pkt_filter_base_list` | 0xe870c | 120 |
| `wl_pkt_filter_base_parse` | 0xe8784 | 276 |
| `wl_pkt_filter_base_show` | 0xe8898 | 196 |
| `wl_pkt_filter_enable` | 0xe895c | 476 |
| `wl_pkt_filter_add` | 0xe8b38 | 5708 |
| `wl_pkt_filter_list_mask_pat` | 0xea184 | 256 |
| `wl_pkt_filter_list` | 0xea284 | 4352 |
| `wl_pkt_filter_stats` | 0xeb384 | 652 |
| `wl_pkt_filter_ports` | 0xeb610 | 1396 |
| `wluc_prot_obss_module_init` | 0xebb98 | 56 |
| `wl_ccastats` | 0xebbd0 | 848 |
| `dynbwsw_config_params` | 0xebf20 | 104 |
| `wl_dyn_bwsw_params` | 0xebf88 | 1444 |
| `wluc_rmc_module_init` | 0xec540 | 56 |
| `wl_mcast_ackmac` | 0xec578 | 1432 |
| `wl_mcast_ackreq` | 0xecb10 | 1056 |
| `wl_mcast_status` | 0xecf30 | 636 |
| `wl_mcast_actf_time` | 0xed1ac | 292 |
| `wl_mcast_ar_timeout` | 0xed2d0 | 304 |
| `wl_mcast_rssi_thresh` | 0xed400 | 232 |
| `wl_mcast_stats` | 0xed4e8 | 3928 |
| `wl_mcast_rssi_delta` | 0xee440 | 264 |
| `wl_mcast_vsie` | 0xee548 | 684 |
| `wluc_rrm_module_init` | 0xee808 | 56 |
| `rrm_input_validation` | 0xee840 | 364 |
| `wl_rrm` | 0xee9ac | 2304 |
| `wl_rrm_stat_req` | 0xef2ac | 1020 |
| `wl_rrm_stat_rpt` | 0xef6a8 | 1056 |
| `wl_rrm_frame_req` | 0xefac8 | 1192 |
| `wl_rrm_chload_req` | 0xeff70 | 1100 |
| `wl_rrm_noise_req` | 0xf03bc | 1120 |
| `wl_rrm_bcn_req` | 0xf081c | 1344 |
| `wl_rrm_lm_req` | 0xf0d5c | 180 |
| `wl_rrm_nbr_req` | 0xf0e10 | 352 |
| `wl_rrm_nbr_list` | 0xf0f70 | 872 |
| `wl_rrm_nbr_del_nbr` | 0xf12d8 | 212 |
| `wl_rrm_nbr_add_nbr` | 0xf13ac | 888 |
| `wl_rrm_parse_location` | 0xf1724 | 420 |
| `wl_rrm_self_lci_civic` | 0xf18c8 | 604 |
| `wl_rrm_config` | 0xf1b24 | 452 |
| `wl_bcn_report_version_get` | 0xf1ce8 | 700 |
| `wl_bcn_report_config_get` | 0xf1fa4 | 476 |
| `wl_bcn_report_vndr_ie_get` | 0xf2180 | 568 |
| `wl_bcn_report_config_set` | 0xf23b8 | 1084 |
| `wl_bcn_report_vndr_ie_set` | 0xf27f4 | 360 |
| `wl_bcn_report` | 0xf295c | 816 |
| `wluc_rxsig_module_init` | 0xf2ca0 | 32 |
| `wl_rxsig_help_all` | 0xf2cc0 | 400 |
| `wl_rxsig_main` | 0xf2e50 | 320 |
| `wl_rxsig_sub_cmd_rssi_help` | 0xf2f90 | 276 |
| `wl_rxsig_sub_cmd_snr_help` | 0xf30a4 | 276 |
| `wl_rxsig_sub_cmd_rssi_ant_help` | 0xf31b8 | 276 |
| `wl_rxsig_sub_cmd_snr_ant_help` | 0xf32cc | 276 |
| `wl_rxsig_sub_cmd_smpl_win_help` | 0xf33e0 | 252 |
| `wl_rxsig_sub_cmd_pkttype_help` | 0xf34dc | 456 |
| `wl_rxsig_sub_cmd_sta_mode_help` | 0xf36a4 | 252 |
| `wl_rxsig_sub_cmd_ma_div_help` | 0xf37a0 | 292 |
| `wl_rxsig_sub_cmd_get_report` | 0xf38c4 | 652 |
| `wl_rxsig_print_rssi_report` | 0xf3b50 | 232 |
| `wl_rxsig_print_snr_report` | 0xf3c38 | 152 |
| `wl_rxsig_print_rssi_ant_report` | 0xf3cd0 | 344 |
| `wl_rxsig_print_snr_ant_report` | 0xf3e28 | 344 |
| `wl_rxsig_sub_cmd_combined_req` | 0xf3f80 | 568 |
| `wl_rxsig_sub_cmd_cmn_val` | 0xf41b8 | 736 |
| `wl_rxsig_sub_cmd_rssi` | 0xf4498 | 72 |
| `wl_rxsig_sub_cmd_snr` | 0xf44e0 | 72 |
| `wl_rxsig_sub_cmd_rssi_ant` | 0xf4528 | 72 |
| `wl_rxsig_sub_cmd_snr_ant` | 0xf4570 | 72 |
| `wl_rxsig_sub_cmd_smpl_win` | 0xf45b8 | 68 |
| `wl_rxsig_sub_cmd_pkttype` | 0xf45fc | 68 |
| `wl_rxsig_sub_cmd_sta_mode` | 0xf4640 | 68 |
| `wl_rxsig_sub_cmd_ma_div` | 0xf4684 | 68 |
| `wluc_sc_module_init` | 0xf46dc | 32 |
| `wl_sc_cmd` | 0xf46fc | 312 |
| `wl_sc_iovt2len` | 0xf4834 | 108 |
| `wl_sc_get_uint_cb` | 0xf48a0 | 84 |
| `wl_sc_pack_uint_cb` | 0xf48f4 | 412 |
| `wl_sc_cmd_uint` | 0xf4a90 | 756 |
| `wluc_scan_module_init` | 0xf4d98 | 56 |
| `wl_parse_scan_event` | 0xf4dd0 | 1200 |
| `wl_scanmac` | 0xf5280 | 2496 |
| `wluc_seq_cmds_module_init` | 0xf5c54 | 56 |
| `wluc_srom_module_init` | 0xf5ca0 | 68 |
| `wlu_get_srom_size` | 0xf5ce4 | 932 |
| `wlu_srread` | 0xf6088 | 624 |
| `wlu_srdump` | 0xf62f8 | 672 |
| `wlu_srwrite` | 0xf6598 | 2784 |
| `newtuple` | 0xf7078 | 160 |
| `parsecis` | 0xf7118 | 13368 |
| `srvlookup` | 0xfa550 | 204 |
| `wlu_srvar` | 0xfa61c | 6780 |
| `wl_nvdump` | 0xfc098 | 300 |
| `wl_nvget` | 0xfc1c4 | 356 |
| `wl_nvset` | 0xfc328 | 416 |
| `wluc_stf_module_init` | 0xfc4dc | 56 |
| `wl_txppr_print` | 0xfc514 | 736 |
| `wl_txppr_print_bw` | 0xfc7f4 | 2384 |
| `wl_get_current_txppr` | 0xfd144 | 1000 |
| `wl_txcore_pwr_offset` | 0xfd52c | 432 |
| `wl_txcore` | 0xfd6dc | 1556 |
| `wl_mimo_stf` | 0xfdcf0 | 1212 |
| `wl_spatial_policy` | 0xfe1ac | 832 |
| `wl_ratetbl_ppr` | 0xfe4ec | 420 |
| `wl_mimo_ps_learning_cfg` | 0xfe690 | 444 |
| `wl_mimo_ps_learning_cfg_get_status` | 0xfe84c | 548 |
| `wl_mimo_ps_cfg` | 0xfea70 | 468 |
| `wl_mimo_ps_status` | 0xfec44 | 196 |
| `wl_mimo_ps_status_dump` | 0xfed08 | 1480 |
| `wl_mimo_ps_status_hw_state_dump` | 0xff2d0 | 236 |
| `wl_mimo_ps_status_assoc_status_dump` | 0xff3bc | 188 |
| `wl_temp_throttle_control` | 0xff478 | 448 |
| `wl_ocl_status` | 0xff638 | 312 |
| `wl_ocl_status_fw_dump` | 0xff770 | 300 |
| `wl_ocl_status_hw_dump` | 0xff89c | 276 |
| `wluc_toe_module_init` | 0xff9c4 | 56 |
| `wl_toe_stats` | 0xff9fc | 2464 |
| `wluc_tpc_module_init` | 0x1003b0 | 56 |
| `wl_tpc_lm` | 0x1003e8 | 156 |
| `wl_tpc_rpt_override` | 0x100484 | 560 |
| `wl_get_curpower_tlv_ver` | 0x1006b4 | 320 |
| `print_pwr` | 0x1007f4 | 216 |
| `check_mfgtest` | 0x1008cc | 256 |
| `wl_read_non_legacy_curpower` | 0x1009cc | 952 |
| `wl_get_legacy_curpower_mode` | 0x100d84 | 376 |
| `wl_get_curpower_tvpm_backoff` | 0x100efc | 500 |
| `wl_txpwr_print_summary` | 0x1010f0 | 2444 |
| `wl_get_current_power` | 0x101a7c | 8872 |
| `wl_txpwr_print_row` | 0x103d24 | 4460 |
| `wl_txpwr_array_row_print` | 0x104e90 | 732 |
| `wl_txpwr_print_header` | 0x10516c | 288 |
| `wl_txpwr_array_print` | 0x10528c | 268 |
| `wl_txpwr_ppr_print` | 0x105398 | 3444 |
| `wl_txpwr_assign_ru_pwr` | 0x10610c | 224 |
| `wl_txpwr_ppr_print_row` | 0x1061ec | 820 |
| `wl_txpwr_ppr_ru_get_rateset` | 0x106520 | 220 |
| `wl_txpwr_ppr_get_rateset` | 0x1065fc | 344 |
| `wl_array_check_val` | 0x106754 | 132 |
| `wl_ppr_get_pwr` | 0x1067d8 | 1324 |
| `wluc_twt_module_init` | 0x106d18 | 32 |
| `wl_twt_cmd` | 0x106d38 | 476 |
| `wl_twt_iovt2len` | 0x106f14 | 108 |
| `wl_twt_get_uint_cb` | 0x106f80 | 84 |
| `wl_twt_pack_uint_cb` | 0x106fd4 | 412 |
| `wl_twt_cmd_uint` | 0x107170 | 744 |
| `wl_twt_cmd2val` | 0x107458 | 152 |
| `wl_twt_type2val` | 0x1074f0 | 152 |
| `wl_twt_cmd_setup` | 0x107588 | 2804 |
| `wl_twt_cmd_teardown` | 0x10807c | 1220 |
| `wl_twt_cmd_info` | 0x108540 | 1128 |
| `wl_twt_flow_flag_val2name` | 0x1089a8 | 180 |
| `wl_twt_cmd_stats_display_v1` | 0x108a5c | 1808 |
| `wl_twt_cmd_stats` | 0x10916c | 1576 |
| `wl_twt_cmd_resp_cfg` | 0x109794 | 920 |
| `wluc_txcap_module_init` | 0x109b40 | 56 |
| `process_txcap_data` | 0x109b78 | 840 |
| `wl_txcapload` | 0x109ec0 | 152 |
| `wl_txcapctl` | 0x109f58 | 1180 |
| `wl_print_txpwrcapv4` | 0x10a3f4 | 1020 |
| `wl_print_txpwrcapv2` | 0x10a7f0 | 1216 |
| `wl_txcapinfo_v1` | 0x10acb0 | 332 |
| `wl_txcapinfo` | 0x10adfc | 196 |
| `wl_txcapdump` | 0x10aec0 | 308 |
| `txcapdump_v2` | 0x10aff4 | 880 |
| `txcapdump_v3` | 0x10b364 | 1476 |
| `txcapdump_v4` | 0x10b928 | 372 |
| `txcapdump_v5` | 0x10ba9c | 336 |
| `txcapdump_v6` | 0x10bbec | 468 |
| `wluc_wds_module_init` | 0x10bdd4 | 56 |
| `wl_wds_wpa_role_old` | 0x10be0c | 404 |
| `wl_wds_wpa_role` | 0x10bfa0 | 560 |
| `wl_get_wdslist` | 0x10c1d0 | 656 |
| `wl_wds_ap_ifname` | 0x10c460 | 192 |
| `wluc_wnm_module_init` | 0x10c534 | 56 |
| `wl_wnm_bsstrans_roamthrottle` | 0x10c56c | 620 |
| `wl_wnm_bsstrans_rssi_rate_map` | 0x10c7d8 | 7868 |
| `wl_wnm` | 0x10e694 | 760 |
| `wl_wnm_bsstq` | 0x10e98c | 1008 |
| `wl_wnm_btq_add_nbr` | 0x10ed7c | 904 |
| `wl_wnm_btq_del_nbr` | 0x10f104 | 344 |
| `wl_wnm_btq_list_nbr` | 0x10f25c | 904 |
| `wl_tclas_add` | 0x10f5e4 | 3700 |
| `wl_tclas_del` | 0x110458 | 540 |
| `wl_tclas_dump` | 0x110674 | 2028 |
| `wl_tclas_list_parse` | 0x110e60 | 188 |
| `wl_tclas_list` | 0x110f1c | 220 |
| `wl_wnm_tfsreq_add` | 0x110ff8 | 824 |
| `wl_wnm_dms_set` | 0x111330 | 508 |
| `wl_wnm_dms_status` | 0x11152c | 708 |
| `wl_wnm_dms_term` | 0x1117f0 | 424 |
| `wl_wnm_service_term` | 0x111998 | 520 |
| `wl_wnm_timbc_offset` | 0x111ba0 | 668 |
| `wl_wnm_timbc_set` | 0x111e3c | 816 |
| `wl_wnm_timbc_status` | 0x11216c | 308 |
| `wl_wnm_maxidle` | 0x1122a0 | 504 |
| `wl_wnm_bsstrans_req` | 0x112498 | 856 |
| `wl_wnm_keepalives_max_idle` | 0x1127f0 | 464 |
| `wl_wnm_url` | 0x1129c0 | 780 |
| `wl_wnm_bss_select_table` | 0x112ccc | 2024 |
| `wl_wnm_bss_select_weight` | 0x1134b4 | 1192 |
| `wl_wnm_btm_default_score` | 0x11395c | 744 |
| `wluc_wowl_module_init` | 0x113c58 | 56 |
| `wl_nshostip` | 0x113c90 | 512 |
| `wl_wowl_status` | 0x113e90 | 388 |
| `wl_wowl_wakeind` | 0x114014 | 988 |
| `wl_wowl_pkt` | 0x1143f0 | 2192 |
| `wl_wowl_pattern` | 0x114c80 | 1868 |
| `wl_wowl_radio_duty_cycle` | 0x1153cc | 736 |
| `wl_wowl_extended_magic` | 0x1156ac | 460 |
| `wluc_btcdyn_module_init` | 0x11588c | 56 |
| `fill_thd_row` | 0x1158c4 | 840 |
| `wl_btcoex_dynctl` | 0x115c0c | 2776 |
| `wl_btcoex_dynctl_status` | 0x1166e4 | 640 |
| `wl_btcoex_dynctl_sim` | 0x116964 | 1040 |
| `wluc_nan_module_init` | 0x116d88 | 56 |
| `wl_nan_resolution_timeunit` | 0x116dc0 | 92 |
| `wl_nan_resolution_string_to_num` | 0x116e1c | 180 |
| `wl_nan_is_instance_valid` | 0x116ed0 | 80 |
| `wl_nan_help_cfg_enable` | 0x116f20 | 52 |
| `wl_nan_help_cfg_init` | 0x116f54 | 52 |
| `wl_nan_help_cfg_ctrl` | 0x116f88 | 512 |
| `wl_nan_help_cfg_ctrl2` | 0x117188 | 132 |
| `wl_nan_help_sd_transmit` | 0x11720c | 32 |
| `wl_nan_help_sd_publish` | 0x11722c | 32 |
| `wl_nan_help_sd_cancel_publish` | 0x11724c | 32 |
| `wl_nan_help_sd_publish_list` | 0x11726c | 32 |
| `wl_nan_help_sd_subscribe` | 0x11728c | 32 |
| `wl_nan_help_sd_cancel_subscribe` | 0x1172ac | 32 |
| `wl_nan_help_sd_subscribe_list` | 0x1172cc | 32 |
| `wl_nan_help_cfg_avail` | 0x1172ec | 432 |
| `wl_nan_help_dp_req` | 0x11749c | 72 |
| `wl_nan_help_dp_resp` | 0x1174e4 | 72 |
| `wl_nan_help_dp_conf` | 0x11752c | 32 |
| `wl_nan_help_dp_end` | 0x11754c | 92 |
| `wl_nan_help_dp_schedupd` | 0x1175a8 | 32 |
| `wl_nan_help_cfg_wfa_testmode` | 0x1175c8 | 472 |
| `wl_nan_help_cfg_ulw` | 0x1177a0 | 232 |
| `wl_nan_help_cfg_vndr_payload` | 0x117888 | 72 |
| `wl_nan_help_dev_cap` | 0x1178d0 | 172 |
| `wl_nan_help_cfg_scan_params` | 0x11797c | 32 |
| `wl_nan_help_dp_idle_period` | 0x11799c | 52 |
| `wl_nan_help_dp_hb_duration` | 0x1179d0 | 52 |
| `wl_nan_help_cfg_fastdisc` | 0x117a04 | 32 |
| `wl_nan_help_dp_opaque_info` | 0x117a24 | 32 |
| `wl_nan_help_nsr` | 0x117a44 | 32 |
| `wl_nan_help_range_idle_count` | 0x117a64 | 52 |
| `wl_nan_help_disc_cache_timeout` | 0x117a98 | 52 |
| `wl_nan_help_disc_cache_clear` | 0x117acc | 52 |
| `bcm_ether_ntoa` | 0x117b00 | 236 |
| `print_nan_role` | 0x117bec | 244 |
| `get_nan_cmd_name` | 0x117ce0 | 120 |
| `wl_nan_print_status` | 0x117d58 | 532 |
| `wlu_nan_print_wl_avail` | 0x117f6c | 576 |
| `wlu_nan_print_wl_avail_entry` | 0x1181ac | 1600 |
| `wl_nan_get_avail` | 0x1187ec | 424 |
| `wl_nan_print_advertisers` | 0x118994 | 780 |
| `wl_nan_print_stats_tlvs` | 0x118ca0 | 4152 |
| `wl_nan_print_sched_stats` | 0x119cd8 | 696 |
| `wl_nan_print_peer_stats` | 0x119f90 | 4172 |
| `wl_nan_print_ndp_stats` | 0x11afdc | 876 |
| `wl_nan_print_avail_stats` | 0x11b348 | 288 |
| `wl_nan_print_fw_cap_xtlv_v2` | 0x11b468 | 1276 |
| `wl_nan_print_fw_cap_xtlv` | 0x11b964 | 1828 |
| `wl_nan_print_hexbytes` | 0x11c088 | 180 |
| `wl_nan_print_nsr_peer_info` | 0x11c13c | 1220 |
| `wl_nan_print_nsr_ndp_info` | 0x11c600 | 604 |
| `wl_nan_print_nsr_xtlvs` | 0x11c85c | 180 |
| `wl_nan_print_cfg_ctrl2` | 0x11c910 | 548 |
| `wl_nan_print_wfa_tm_flags` | 0x11cb34 | 804 |
| `wlu_nan_resp_iovars_cbfn` | 0x11ce58 | 22660 |
| `wl_nan_print_event_data_tlvs` | 0x1226dc | 1580 |
| `wl_nan_print_event_data` | 0x122d08 | 5688 |
| `wl_nan_subcmd_event_check` | 0x124340 | 3996 |
| `wl_nan_process_resp_buf` | 0x1252dc | 328 |
| `wl_nan_do_ioctl` | 0x125424 | 396 |
| `wl_nan_subcmd_event_msgs` | 0x1255b0 | 1092 |
| `wl_nan_subcmd_disc_results` | 0x1259f4 | 124 |
| `wl_nan_subcmd_dbg_rssi` | 0x125a70 | 56 |
| `wl_nan_help_usage` | 0x125aa8 | 32 |
| `wl_nan_help` | 0x125ac8 | 168 |
| `wl_nan_subcmd_cfg_enable` | 0x125b70 | 272 |
| `wl_nan_subcmd_cfg_role` | 0x125c80 | 980 |
| `wl_nan_subcmd_cfg_ctrl` | 0x126054 | 384 |
| `wl_nan_subcmd_cfg_ctrl2` | 0x1261d4 | 536 |
| `wl_nan_subcmd_cfg_init` | 0x1263ec | 368 |
| `wl_nan_subcmd_cfg_hop_count` | 0x12655c | 264 |
| `wl_nan_subcmd_cfg_hop_limit` | 0x126664 | 264 |
| `wl_nan_subcmd_cfg_warmup_time` | 0x12676c | 268 |
| `wl_nan_subcmd_cfg_count` | 0x126878 | 120 |
| `wl_nan_subcmd_cfg_clearcount` | 0x1268f0 | 124 |
| `wl_nan_subcmd_cfg_channel` | 0x12696c | 256 |
| `wl_nan_subcmd_cfg_cid` | 0x126a6c | 320 |
| `wl_nan_subcmd_cfg_if_addr` | 0x126bac | 356 |
| `wl_nan_subcmd_cfg_bcn_interval` | 0x126d10 | 436 |
| `wl_nan_subcmd_cfg_sdf_txtime` | 0x126ec4 | 436 |
| `wl_nan_subcmd_cfg_sid_beacon` | 0x127078 | 512 |
| `wl_nan_subcmd_cfg_vndr_payload` | 0x127278 | 864 |
| `wl_nan_subcmd_dp_idle_period` | 0x1275d8 | 276 |
| `wl_nan_subcmd_dp_hb_duration` | 0x1276ec | 276 |
| `wl_nan_subcmd_cfg_min_tx_rate` | 0x127800 | 264 |
| `wl_nan_subcmd_fw_cap` | 0x127908 | 112 |
| `wl_nan_help_stats` | 0x127978 | 132 |
| `wl_nan_help_cfg_role` | 0x1279fc | 132 |
| `wl_nan_subcmd_stats` | 0x127a80 | 636 |
| `nan_lookup_awake_dw_config_param` | 0x127cfc | 144 |
| `wl_nan_subcmd_election_host_enable` | 0x127d8c | 264 |
| `wl_nan_subcmd_election_metrics_config` | 0x127e94 | 332 |
| `wl_nan_subcmd_election_metrics_state` | 0x127fe0 | 120 |
| `wl_nan_subcmd_cfg_status` | 0x128058 | 120 |
| `wl_nan_subcmd_leave` | 0x1280d0 | 328 |
| `wl_nan_service_name_to_hash` | 0x128218 | 196 |
| `nan_lookup_sd_config_param` | 0x1282dc | 144 |
| `wl_nan_subcmd_svc` | 0x12836c | 6968 |
| `wl_nan_bloom_create` | 0x129ea4 | 216 |
| `wl_nan_bloom_alloc` | 0x129f7c | 96 |
| `wl_nan_bloom_free` | 0x129fdc | 40 |
| `wl_nan_hash` | 0x12a004 | 156 |
| `wl_nan_subcmd_publish` | 0x12a0a0 | 428 |
| `wl_nan_subcmd_publish_list` | 0x12a24c | 140 |
| `wl_nan_subcmd_subscribe` | 0x12a2d8 | 440 |
| `wl_nan_subcmd_subscribe_list` | 0x12a490 | 140 |
| `wl_nan_subcmd_cancel` | 0x12a51c | 312 |
| `wl_nan_subcmd_cancel_publish` | 0x12a654 | 88 |
| `wl_nan_subcmd_cancel_subscribe` | 0x12a6ac | 88 |
| `wl_nan_subcmd_sd_transmit` | 0x12a704 | 2168 |
| `wl_nan_subcmd_sd_vendor_info` | 0x12af7c | 56 |
| `wl_nan_subcmd_sd_statistics` | 0x12afb4 | 56 |
| `wl_nan_subcmd_sd_connection` | 0x12afec | 56 |
| `wl_nan_subcmd_sd_show` | 0x12b024 | 56 |
| `bcm_pack_xtlv_entry_from_hex_string` | 0x12b05c | 344 |
| `wl_nan_subcmd_merge` | 0x12b1b4 | 264 |
| `nan_get_subcmd_info` | 0x12b2bc | 132 |
| `wl_nan_subcmd_disc_cache_timeout` | 0x12b340 | 292 |
| `wl_nan_subcmd_disc_cache_clear` | 0x12b464 | 296 |
| `nan_get_arg_count` | 0x12b58c | 132 |
| `wl_nan_control` | 0x12b610 | 1176 |
| `wl_nan_subcmd_election_advertisers` | 0x12baa8 | 120 |
| `wl_nan_set_avail` | 0x12bb20 | 108 |
| `wl_nan_subcmd_cfg_oui` | 0x12bb8c | 412 |
| `print_peer_rssi` | 0x12bd28 | 852 |
| `wl_nan_subcmd_dump` | 0x12c07c | 412 |
| `wl_nan_subcmd_dbg_level` | 0x12c218 | 436 |
| `wl_nan_subcmd_clear` | 0x12c3cc | 412 |
| `wl_nan_subcmd_dp_cap` | 0x12c568 | 56 |
| `wl_nan_subcmd_dp_status` | 0x12c5a0 | 296 |
| `wl_nan_subcmd_dp_stats` | 0x12c6c8 | 56 |
| `nan_lookup_dp_config_param` | 0x12c700 | 144 |
| `wl_nan_get_qos_params` | 0x12c790 | 384 |
| `wl_nan_subcmd_dp_req` | 0x12c910 | 2888 |
| `wl_nan_subcmd_dp_resp` | 0x12d458 | 2948 |
| `wl_nan_subcmd_dp_conf` | 0x12dfdc | 336 |
| `wl_nan_subcmd_dp_dataend` | 0x12e12c | 992 |
| `wl_nan_subcmd_dp_show` | 0x12e50c | 104 |
| `wl_nan_subcmd_dp_schedupd` | 0x12e574 | 1400 |
| `wl_nan_subcmd_cfg_avail` | 0x12eaec | 4888 |
| `wl_nan_get_avail_params` | 0x12fe04 | 864 |
| `wl_nan_set_avail_entry_optional` | 0x130164 | 3476 |
| `nan_lookup_rng_config_param` | 0x130ef8 | 144 |
| `wl_nan_subcmd_range_req` | 0x130f88 | 852 |
| `wl_nan_subcmd_range_auto` | 0x1312dc | 216 |
| `wl_nan_subcmd_range_resp` | 0x1313b4 | 848 |
| `wl_nan_subcmd_range_cancel` | 0x131704 | 216 |
| `wl_nan_subcmd_range_idle_count` | 0x1317dc | 276 |
| `wl_nan_subcmd_soc_chans` | 0x1318f0 | 312 |
| `wl_nan_subcmd_awake_dws` | 0x131a28 | 312 |
| `wl_nan_subcmd_sbcn_rssi_notif_thld` | 0x131b60 | 312 |
| `wl_nan_subcmd_sbcn_rssi_thld` | 0x131c98 | 392 |
| `wl_nan_subcmd_max_peers` | 0x131e20 | 328 |
| `wl_nan_subcmd_cfg_wfa_testmode` | 0x131f68 | 360 |
| `wl_nan_subcmd_cfg_ulw` | 0x1320d0 | 1588 |
| `wl_nan_subcmd_dev_cap` | 0x132704 | 1700 |
| `wl_nan_subcmd_cfg_scan_params` | 0x132da8 | 528 |
| `wl_nan_subcmd_fastdisc` | 0x132fb8 | 1304 |
| `wl_nan_subcmd_dp_opaque_info` | 0x1334d0 | 900 |
| `wl_nan_subcmd_nsr` | 0x133854 | 408 |
| `wl_nan_get_ifname_by_ndi` | 0x1339ec | 496 |
| `wl_nan_get_ndpe_ipv6_tlv` | 0x133bdc | 652 |
| `wl_nan_add_ipv6_neighbor` | 0x133e68 | 772 |
| `wl_nan_run_host_assist_script` | 0x13416c | 176 |
| `is_hex` | 0x13421c | 124 |
| `wl_nan_help_nanho` | 0x134298 | 72 |
| `wl_nan_subcmd_nanho` | 0x1342e0 | 452 |
| `wl_nan_print_nanho_peer_entry` | 0x1344a4 | 280 |
| `wl_nan_print_nanho_dcaplist` | 0x1345bc | 1532 |
| `wl_nan_print_nanho_peer_ndi` | 0x134bb8 | 440 |
| `wl_nan_print_nanho_dcslist` | 0x134d70 | 1080 |
| `wl_nan_print_nanho_blob` | 0x1351a8 | 1308 |
| `wl_nan_print_nanho_xtlvs` | 0x1356c4 | 256 |
| `wl_nan_help_nanho_logctrl` | 0x1357c4 | 412 |
| `wl_nan_subcmd_nanho_logctrl` | 0x135960 | 396 |
| `wl_nan_print_nanho_logctrl_xtlvs` | 0x135aec | 1364 |
| `wl_nan_subcmd_nanho_ver` | 0x136040 | 112 |
| `wluc_rsdb_module_init` | 0x1360c4 | 56 |
| `wlc_sdb_op_mode_name` | 0x1360fc | 188 |
| `wlc_rsdb_band_name` | 0x1361b8 | 188 |
| `wl_rsdb_caps` | 0x136274 | 520 |
| `wl_rsdb_bands` | 0x13647c | 416 |
| `wl_rsdb_config` | 0x13661c | 1216 |
| `wl_parse_infra_mode_list` | 0x136adc | 348 |
| `wl_parse_SIB_param_list` | 0x136c38 | 356 |
| `get_rsdb_cmd_name` | 0x136d9c | 120 |
| `rsdb_get_subcmd_info` | 0x136e14 | 132 |
| `rsdb_get_arg_count` | 0x136e98 | 132 |
| `wlu_rsdb_resp_iovars_cbfn` | 0x136f1c | 1632 |
| `wl_rsdb_process_resp_buf` | 0x13757c | 328 |
| `wl_rsdb_do_ioctl` | 0x1376c4 | 332 |
| `wl_rsdb_control` | 0x137810 | 972 |
| `wl_rsdb_subcmd_get` | 0x137bdc | 104 |
| `wl_rsdb_subcmd_config` | 0x137c44 | 672 |
| `wluc_slot_bss_module_init` | 0x137ef8 | 56 |
| `get_slot_bss_cmd_name` | 0x137f30 | 120 |
| `slot_bss_get_subcmd_info` | 0x137fa8 | 132 |
| `slot_bss_get_arg_count` | 0x13802c | 132 |
| `wlu_slot_bss_chanseq_tlv_cbfn` | 0x1380b0 | 588 |
| `wlu_slot_bss_resp_iovars_cbfn` | 0x1382fc | 752 |
| `wl_slot_bss_process_resp_buf` | 0x1385ec | 328 |
| `wl_slot_bss_do_ioctl` | 0x138734 | 332 |
| `wl_slot_bss_control` | 0x138880 | 972 |
| `wl_slot_bss_subcmd_get` | 0x138c4c | 104 |
| `wl_slot_bss_counters` | 0x138cb4 | 2360 |
| `wl_slot_bss_nac_counters` | 0x1395ec | 456 |
| `wl_slot_bss_subcmd_chanseq` | 0x1397b4 | 2236 |
| `wl_slot_bss_subcmd_critslots` | 0x13a070 | 760 |
| `wluc_hp2p_module_init` | 0x13a37c | 32 |
| `get_hp2p_cmd_name` | 0x13a39c | 120 |
| `hp2p_get_subcmd_info` | 0x13a414 | 132 |
| `hp2p_get_arg_count` | 0x13a498 | 132 |
| `wlu_hp2p_tx_config_print` | 0x13a51c | 844 |
| `wlu_hp2p_rx_config_print` | 0x13a868 | 304 |
| `wlu_hp2p_resp_iovars_cbfn` | 0x13a998 | 888 |
| `wl_hp2p_process_resp_buf` | 0x13ad10 | 328 |
| `wl_hp2p_do_ioctl` | 0x13ae58 | 332 |
| `wl_hp2p_control` | 0x13afa4 | 992 |
| `wl_hp2p_subcmd_enable` | 0x13b384 | 520 |
| `wl_hp2p_subcmd_counters` | 0x13b58c | 612 |
| `wl_hp2p_subcmd_tx_config` | 0x13b7f0 | 3180 |
| `wl_hp2p_subcmd_rx_config` | 0x13c45c | 1664 |
| `wluc_sdio_module_init` | 0x13caf0 | 56 |
| `wl_sd_msglevel` | 0x13cb28 | 1076 |
| `wl_sd_blocksize` | 0x13cf5c | 892 |
| `wl_sd_mode` | 0x13d2d8 | 768 |
| `wl_sd_reg` | 0x13d5d8 | 1212 |
| `wluc_ndoe_module_init` | 0x13daa8 | 56 |
| `wl_print_ipv6_addr` | 0x13dae0 | 244 |
| `wl_nd_hostip_extended` | 0x13dbd4 | 3756 |
| `wl_ndstatus` | 0x13ea80 | 368 |
| `wl_solicitipv6` | 0x13ebf0 | 504 |
| `wl_remoteipv6` | 0x13ede8 | 504 |
| `wluc_p2po_module_init` | 0x13eff4 | 56 |
| `wl_p2po_listen` | 0x13f02c | 664 |
| `wl_p2po_addsvc` | 0x13f2c4 | 920 |
| `wl_p2po_delsvc` | 0x13f65c | 760 |
| `wl_p2po_sd_reqresp` | 0x13f954 | 836 |
| `wl_p2po_listen_channel` | 0x13fc98 | 316 |
| `wl_p2po_find_config` | 0x13fdd4 | 1376 |
| `wl_p2po_results` | 0x140334 | 2100 |
| `wl_p2po_gas_config` | 0x140b68 | 1488 |
| `wl_p2po_print_name` | 0x141138 | 132 |
| `wl_p2po_wfds_seek_get` | 0x1411bc | 604 |
| `wl_p2po_wfds_seek_add` | 0x141418 | 1408 |
| `wl_p2po_wfds_seek_del` | 0x141998 | 300 |
| `wl_p2po_wfds_advertise_get` | 0x141ac4 | 840 |
| `wl_p2po_wfds_advertise_add` | 0x141e0c | 2064 |
| `wl_p2po_wfds_advertise_del` | 0x14261c | 316 |
| `wluc_anqpo_module_init` | 0x14276c | 56 |
| `wl_anqpo_set` | 0x1427a4 | 1944 |
| `wl_anqpo_stop_query` | 0x142f3c | 68 |
| `wl_anqpo_start_query` | 0x142f80 | 1968 |
| `wl_anqpo_ignore_ssid_list` | 0x143730 | 1616 |
| `wl_anqpo_ignore_bssid_list` | 0x143d80 | 1368 |
| `wl_anqpo_results` | 0x1442d8 | 2588 |
| `wluc_bdo_module_init` | 0x144d08 | 56 |
| `wl_bdo_download_database` | 0x144d40 | 992 |
| `read_file` | 0x145120 | 552 |
| `hex2bin` | 0x145348 | 340 |
| `wl_bdo_download_file` | 0x14549c | 304 |
| `wl_bdo` | 0x1455cc | 1724 |
| `wluc_tko_module_init` | 0x145c9c | 56 |
| `wl_ipv6_tcp_keepalive_pkt` | 0x145cd4 | 1236 |
| `wl_tcp_keepalive_pkt` | 0x1461a8 | 1436 |
| `wl_tko_connect_init` | 0x146744 | 1264 |
| `wl_tko` | 0x146c34 | 5432 |
| `wl_tko_auto_config` | 0x14816c | 5244 |
| `wl_tko_event_cb` | 0x1495e8 | 184 |
| `wl_tko_event_check` | 0x1496a0 | 164 |
| `wluc_pfn_module_init` | 0x149758 | 56 |
| `wl_pfn_set` | 0x149790 | 4168 |
| `validate_hex` | 0x14a7d8 | 120 |
| `char2hex` | 0x14a850 | 212 |
| `wl_pfn_add` | 0x14a924 | 6168 |
| `wl_pfn_ssid_param` | 0x14c13c | 3504 |
| `wl_pfn_add_bssid` | 0x14ceec | 2272 |
| `wl_pfn_cfg` | 0x14d7cc | 1472 |
| `wl_pfn` | 0x14dd8c | 208 |
| `wl_pfnbest` | 0x14de5c | 1276 |
| `wl_pfnlbest` | 0x14e358 | 1412 |
| `wl_pfnbest_bssid` | 0x14e8dc | 540 |
| `wl_pfn_suspend` | 0x14eaf8 | 208 |
| `wl_pfn_mem` | 0x14ebc8 | 484 |
| `wl_pfn_printnet` | 0x14edac | 956 |
| `wl_pfn_event_check` | 0x14f168 | 3992 |
| `wl_event_filter` | 0x150100 | 364 |
| `wl_pfn_roam_alert_thresh` | 0x15026c | 592 |
| `wl_pfn_override` | 0x1504bc | 4848 |
| `wl_pfn_macaddr` | 0x1517ac | 340 |
| `wl_pfn_mpfset` | 0x151900 | 5064 |
| `wl_mpf_map` | 0x152cc8 | 3672 |
| `wl_mpf_state` | 0x153b20 | 1880 |
| `wluc_tbow_module_init` | 0x15428c | 56 |
| `wl_tbow_doho` | 0x1542c4 | 1128 |
| `wluc_p2p_module_init` | 0x154740 | 56 |
| `wl_p2p_state` | 0x154778 | 388 |
| `wl_p2p_scan` | 0x1548fc | 1052 |
| `wl_p2p_ifadd` | 0x154d18 | 544 |
| `wl_p2p_ifdel` | 0x154f38 | 160 |
| `wl_p2p_ifupd` | 0x154fd8 | 480 |
| `wl_p2p_if` | 0x1551b8 | 328 |
| `wl_p2p_ops` | 0x155300 | 416 |
| `wl_p2p_noa` | 0x1554a0 | 2692 |
| `wl_p2p_conf` | 0x155f24 | 496 |
| `wluc_tdls_module_init` | 0x156128 | 56 |
| `wl_tdls_endpoint` | 0x156160 | 1032 |
| `wl_tdls_wfd_ie` | 0x156568 | 5332 |
| `proxd_tune_ver_get` | 0x157a50 | 112 |
| `wluc_proxd_module_init` | 0x157ac0 | 56 |
| `wl_proxd` | 0x157af8 | 1376 |
| `wl_proxd_get_debug_data` | 0x158058 | 884 |
| `wlc_proxd_collec_header_dump` | 0x1583cc | 2592 |
| `wlc_proxd_collect_data_check_ver_len` | 0x158dec | 160 |
| `wlc_proxd_collec_data_dump` | 0x158e8c | 2008 |
| `wl_proxd_get_collect_data` | 0x159664 | 308 |
| `wl_proxd_collect` | 0x159798 | 2100 |
| `proxd_method_set_vht_rate` | 0x159fcc | 1652 |
| `proxd_method_set_common_param_from_opt` | 0x15a640 | 476 |
| `proxd_method_tof_set_param_from_opt` | 0x15a81c | 1072 |
| `proxd_method_rssi_set_param_from_opt` | 0x15ac4c | 1412 |
| `wl_proxd_params` | 0x15b1d0 | 3132 |
| `proxd_method_tof_parse_mixed_param` | 0x15be0c | 216 |
| `proxd_tune_set_params_from_opt_v1` | 0x15bee4 | 10864 |
| `proxd_tune_set_params_from_opt_v2` | 0x15e954 | 11468 |
| `proxd_tune_set_params_from_opt_v3` | 0x161620 | 9420 |
| `proxd_tune_set_param_from_opt` | 0x163aec | 224 |
| `proxd_tune_ver_get_size` | 0x163bcc | 120 |
| `wl_proxd_tune` | 0x163c44 | 952 |
| `wl_proxd_mode_str` | 0x163ffc | 76 |
| `wl_proxd_state_str` | 0x164048 | 300 |
| `wl_proxd_tof_state_str` | 0x164174 | 248 |
| `wl_proxd_tof_reason_str` | 0x16426c | 76 |
| `wl_proxd_reason_str` | 0x1642b8 | 76 |
| `wl_proxd_status` | 0x164304 | 1396 |
| `wl_proxd_payload` | 0x164878 | 992 |
| `wl_proxd_report` | 0x164c58 | 748 |
| `wl_proxd_tof_host_calc` | 0x164f44 | 2256 |
| `wl_proxd_nan_status_str` | 0x165814 | 76 |
| `wl_proxd_nan_host_calc` | 0x165860 | 856 |
| `wl_proxd_tof_ts_results` | 0x165bb8 | 932 |
| `wl_proxd_event_check` | 0x165f5c | 2516 |
| `wl_nan_ranging_config` | 0x166930 | 1232 |
| `wl_nan_ranging_start` | 0x166e00 | 2192 |
| `wl_nan_ranging_results_host` | 0x167690 | 808 |
| `ftm_get_subcmd_info` | 0x1679b8 | 136 |
| `wl_proxd_cmd_method_handler` | 0x167a40 | 716 |
| `ftm_get_strmap_info` | 0x167d0c | 132 |
| `ftm_get_strmap_info_strkey` | 0x167d90 | 140 |
| `ftm_map_id_to_str` | 0x167e1c | 92 |
| `ftm_tlvid_to_logstr` | 0x167e78 | 68 |
| `ftm_method_value_to_logstr` | 0x167ebc | 68 |
| `ftm_tmu_value_to_logstr` | 0x167f00 | 68 |
| `ftm_caps_value_to_logstr` | 0x167f44 | 68 |
| `ftm_status_value_to_logstr` | 0x167f88 | 224 |
| `ftm_session_state_value_to_logstr` | 0x168068 | 68 |
| `ftm_ranging_state_value_to_logstr` | 0x1680ac | 68 |
| `ftm_ranging_flags_value_to_logstr` | 0x1680f0 | 68 |
| `ftm_avail_flags_value_to_logstr` | 0x168134 | 68 |
| `ftm_avail_timeref_value_to_logstr` | 0x168178 | 68 |
| `ftm_alloc_getset_buf` | 0x1681bc | 256 |
| `ftm_unpack_and_display_rtt_result_v1` | 0x1682bc | 3536 |
| `ftm_unpack_and_display_rtt_result_v2` | 0x16908c | 3876 |
| `ftm_unpack_and_display_session_info` | 0x169fb0 | 596 |
| `ftm_unpack_and_display_session_status` | 0x16a204 | 368 |
| `ftm_unpack_and_display_counters` | 0x16a374 | 2456 |
| `ftm_unpack_and_display_session_idlist` | 0x16ad0c | 264 |
| `ftm_unpack_and_display_avail` | 0x16ae14 | 1280 |
| `ftm_unpack_and_display_ranging_info` | 0x16b314 | 460 |
| `ftm_unpack_xtlv_cbfn` | 0x16b4e0 | 3056 |
| `ftm_pack_tlv_id_support` | 0x16c0d0 | 244 |
| `ftm_is_tlv_id_supported` | 0x16c1c4 | 252 |
| `ftm_do_get_ioctl` | 0x16c2c0 | 300 |
| `ftm_common_getcmd_handler` | 0x16c3ec | 232 |
| `ftm_subcmd_get_version` | 0x16c4d4 | 72 |
| `ftm_subcmd_get_result` | 0x16c51c | 72 |
| `ftm_subcmd_get_info` | 0x16c564 | 72 |
| `ftm_subcmd_get_status` | 0x16c5ac | 72 |
| `ftm_subcmd_get_sessions` | 0x16c5f4 | 72 |
| `ftm_subcmd_get_counters` | 0x16c63c | 72 |
| `ftm_subcmd_get_ranging_info` | 0x16c684 | 72 |
| `ftm_subcmd_dump` | 0x16c6cc | 72 |
| `ftm_subcmd_setiov_no_tlv` | 0x16c714 | 264 |
| `ftm_subcmd_enable` | 0x16c81c | 72 |
| `ftm_subcmd_disable` | 0x16c864 | 72 |
| `ftm_subcmd_start_session` | 0x16c8ac | 72 |
| `ftm_subcmd_stop_session` | 0x16c8f4 | 72 |
| `ftm_subcmd_burst_request` | 0x16c93c | 72 |
| `ftm_subcmd_delete_session` | 0x16c984 | 72 |
| `ftm_subcmd_clear_counters` | 0x16c9cc | 72 |
| `ftm_get_tmu_from_str` | 0x16ca14 | 356 |
| `ftm_get_config_param_info` | 0x16cb78 | 204 |
| `ftm_cmn_display_config_options_value` | 0x16cc44 | 216 |
| `ftm_unpack_and_display_session_flags` | 0x16cd1c | 188 |
| `ftm_unpack_and_display_config_flags` | 0x16cdd8 | 192 |
| `ftm_get_config_options_info` | 0x16ce98 | 196 |
| `ftm_handle_config_options` | 0x16cf5c | 616 |
| `ftm_validate_num_burst` | 0x16d1c4 | 272 |
| `ftm_config_parse_ul` | 0x16d2d4 | 244 |
| `ftm_config_parse_channel` | 0x16d3c8 | 132 |
| `ftm_config_parse_intvl` | 0x16d44c | 352 |
| `ftm_config_parse_tpk_peer` | 0x16d5ac | 244 |
| `ftm_config_avail_parse_slot` | 0x16d6a0 | 532 |
| `ftm_config_avail_parse_tref` | 0x16d8b4 | 172 |
| `ftm_config_avail_parse_all_slots` | 0x16d960 | 280 |
| `ftm_config_avail_alloc` | 0x16da78 | 208 |
| `ftm_config_avail_to_avail24` | 0x16db48 | 336 |
| `ftm_pack_config_avail_from_cmdarg` | 0x16dc98 | 740 |
| `ftm_do_config_avail_iovar` | 0x16df7c | 268 |
| `ftm_handle_config_avail` | 0x16e088 | 392 |
| `ftm_parse_config_category` | 0x16e210 | 164 |
| `ftm_handle_config_general` | 0x16e2b4 | 1116 |
| `ftm_subcmd_config` | 0x16e710 | 640 |
| `ftm_display_cmd_help` | 0x16e990 | 268 |
| `ftm_pack_sids_from_cmdarg` | 0x16ea9c | 480 |
| `ftm_pack_ranging_config_from_cmdarg` | 0x16ec7c | 428 |
| `ftm_subcmd_start_ranging` | 0x16ee28 | 420 |
| `ftm_subcmd_stop_ranging` | 0x16efcc | 136 |
| `ftm_display_method_help` | 0x16f054 | 336 |
| `ftm_display_config_help` | 0x16f1a4 | 252 |
| `ftm_display_config_options_help` | 0x16f2a0 | 464 |
| `ftm_display_config_avail_help` | 0x16f470 | 496 |
| `ftm_handle_help` | 0x16f660 | 392 |
| `ftm_get_event_type_loginfo` | 0x16f7e8 | 68 |
| `ftm_event_check` | 0x16f82c | 380 |
| `ftm_handle_tune_options` | 0x16f9a8 | 344 |
| `ftm_tune_cbfn` | 0x16fb00 | 76 |
| `ftm_subcmd_tune` | 0x16fb4c | 1020 |
| `proxd_tune_display_v1` | 0x16ff48 | 6436 |
| `proxd_tune_display_v2` | 0x17186c | 6700 |
| `proxd_tune_display_v3` | 0x173298 | 5032 |
| `proxd_tune_display` | 0x174640 | 176 |
| `wluc_randmac_module_init` | 0x174704 | 56 |
| `wl_randmac` | 0x17473c | 312 |
| `randmac_get_subcmd_info` | 0x174874 | 136 |
| `randmac_subcmd_get_version` | 0x1748fc | 56 |
| `wl_randmac_subcmd_method_handler` | 0x174934 | 256 |
| `randmac_display_method_help` | 0x174a34 | 276 |
| `randmac_display_config_help` | 0x174b48 | 212 |
| `randmac_handle_help` | 0x174c1c | 152 |
| `randmac_parse_config_category` | 0x174cb4 | 36 |
| `randmac_get_config_param_info` | 0x174cd8 | 136 |
| `randmac_parse_method` | 0x174d60 | 140 |
| `randmac_handle_config_general` | 0x174dec | 724 |
| `randmac_subcmd_disable` | 0x1750c0 | 56 |
| `randmac_subcmd_enable` | 0x1750f8 | 328 |
| `randmac_subcmd_config` | 0x175240 | 348 |
| `randmac_subcmd_getstats` | 0x17539c | 56 |
| `randmac_subcmd_clearstats` | 0x1753d4 | 208 |
| `randmac_alloc_getset_buf` | 0x1754a4 | 172 |
| `randmac_common_getcmd_handler` | 0x175550 | 312 |
| `randmac_do_get_ioctl` | 0x175688 | 1124 |
| `wluc_natoe_module_init` | 0x175b00 | 32 |
| `wl_natoe_bus_frwdpkt_stats` | 0x175b20 | 2180 |
| `wlu_natoe_set_vars_cbfn` | 0x1763a4 | 8156 |
| `wl_natoe_get_stats` | 0x178380 | 236 |
| `wl_natoe_get_ioctl` | 0x17846c | 176 |
| `wl_natoe_subcmd_ver` | 0x17851c | 512 |
| `wl_natoe_subcmd_enable` | 0x17871c | 736 |
| `wl_natoe_subcmd_config_ips` | 0x1789fc | 1308 |
| `wl_natoe_subcmd_config_ports` | 0x178f18 | 1116 |
| `wl_natoe_subcmd_dbg_stats` | 0x179374 | 1256 |
| `wl_natoe_subcmd_tbl_cnt` | 0x17985c | 732 |
| `wl_natoe_subcmd_dstnat_config` | 0x179b38 | 1324 |
| `wl_natoe_subcmd_ctrl` | 0x17a064 | 732 |
| `wl_natoe_control` | 0x17a340 | 472 |
| `wluc_msch_module_init` | 0x17a52c | 92 |
| `wl_parse_msch_chanspec_list` | 0x17a588 | 572 |
| `wl_parse_msch_bf_param` | 0x17a7c4 | 428 |
| `wl_msch_request` | 0x17a970 | 4040 |
| `wl_msch_collect` | 0x17b938 | 2800 |
| `wl_read_map` | 0x17c428 | 1040 |
| `wl_init_static_strs_array` | 0x17c838 | 1208 |
| `wl_init_logstrs_array` | 0x17ccf0 | 1336 |
| `wl_init_frm_array` | 0x17d228 | 1688 |
| `wl_msch_display_time` | 0x17d8c0 | 400 |
| `wl_msch_chanspec_list` | 0x17da50 | 1076 |
| `wl_msch_elem_list` | 0x17de84 | 1028 |
| `wl_msch_req_param_profiler_data` | 0x17e288 | 4572 |
| `wl_msch_timeslot_profiler_data` | 0x17f464 | 2656 |
| `wl_msch_req_timing_profiler_data` | 0x17fec4 | 4624 |
| `wl_msch_chan_ctxt_profiler_data` | 0x1810d4 | 3092 |
| `wl_msch_req_entity_profiler_data` | 0x181ce8 | 6740 |
| `wl_msch_req_handle_profiler_data` | 0x18373c | 3448 |
| `wl_msch_profiler_profiler_data` | 0x1844b4 | 4796 |
| `check_valid_string_format` | 0x185770 | 192 |
| `wl_msch_profiler_event_log_data` | 0x185830 | 2264 |
| `wl_msch_dump_data` | 0x186108 | 8600 |
| `wl_msch_dump` | 0x1882a0 | 1172 |
| `wl_msch_event_check` | 0x188734 | 4800 |
| `wl_msch_profiler` | 0x1899f4 | 2628 |
| `wluc_awdl_module_init` | 0x18a44c | 56 |
| `wl_awdl_counters` | 0x18a484 | 20548 |
| `wl_awdl_uct_counters` | 0x18f4c8 | 1944 |
| `wl_awdl_wowl_sleeper_addr` | 0x18fc60 | 176 |
| `wl_parse_awseq_list` | 0x18fd10 | 356 |
| `wl_awdl_pscan_prep` | 0x18fe74 | 3268 |
| `wl_awdl_pscan` | 0x190b38 | 2948 |
| `wl_awdl_sync_params` | 0x1916bc | 2064 |
| `wl_awdl_af_hdr` | 0x191ecc | 700 |
| `wl_awdl_ext_counts` | 0x192188 | 656 |
| `wl_awdl_opmode` | 0x192418 | 832 |
| `wl_awdl_election_tree` | 0x192758 | 2128 |
| `wl_awdl_payload` | 0x192fa8 | 712 |
| `wl_awdl_cap` | 0x193270 | 324 |
| `wl_awdl_afs_pload` | 0x1933b4 | 1524 |
| `wl_awdl_long_payload` | 0x1939a8 | 852 |
| `wl_awdl_chan_seq` | 0x193cfc | 948 |
| `wl_bsscfg_awdl_enable` | 0x1940b0 | 1076 |
| `wl_awdl_mon_bssid` | 0x1944e4 | 132 |
| `wl_awdl_advertisers` | 0x194568 | 2044 |
| `wl_awdl_peer_op` | 0x194d64 | 1272 |
| `wl_awdl_oob_af_cmn` | 0x19525c | 2000 |
| `wl_awdl_oob_af` | 0x195a2c | 780 |
| `wl_awdl_oob_af_async` | 0x195d38 | 1548 |
| `wl_awdl_oob_af_auto` | 0x196344 | 1348 |
| `wl_awdl_uct_test` | 0x196888 | 176 |
| `wl_awdl_ftm_ranging_config` | 0x196938 | 608 |
| `wl_awdl_ftm_ranging_start` | 0x196b98 | 420 |
| `wl_awdl_dfsp_cfg` | 0x196d3c | 1248 |
| `wl_awdl_dfsp_ucsa` | 0x19721c | 1128 |
| `wluc_mbo_module_init` | 0x197698 | 32 |
| `wl_mbo_usage` | 0x1976b8 | 156 |
| `wl_mbo_main` | 0x197754 | 352 |
| `wl_mbo_sub_cmd_add_chan_pref` | 0x1978b4 | 1288 |
| `wl_mbo_add_chan_pref_help_fn` | 0x197dbc | 172 |
| `wl_mbo_sub_cmd_del_chan_pref` | 0x197e68 | 860 |
| `wl_mbo_del_chan_pref_help_fn` | 0x1981c4 | 72 |
| `wl_mbo_process_iov_resp_buf` | 0x19820c | 292 |
| `wl_mbo_get_iov_resp` | 0x198330 | 324 |
| `wl_mbo_list_chan_pref_cbfn` | 0x198474 | 324 |
| `wl_mbo_sub_cmd_list_chan_pref` | 0x1985b8 | 112 |
| `wl_mbo_list_chan_pref_help_fn` | 0x198628 | 32 |
| `wl_mbo_cell_data_cap_cbfn` | 0x198648 | 232 |
| `wl_mbo_sub_cmd_cell_data_cap` | 0x198730 | 728 |
| `wl_mbo_cell_data_cap_help_fn` | 0x198a08 | 112 |
| `wl_mbo_dump_counters_cbfn` | 0x198a78 | 688 |
| `wl_mbo_sub_cmd_dump_counters` | 0x198d28 | 112 |
| `wl_mbo_counters_help_fn` | 0x198d98 | 32 |
| `wl_mbo_sub_cmd_clear_counters` | 0x198db8 | 256 |
| `wl_mbo_clear_counters_help_fn` | 0x198eb8 | 32 |
| `wl_mbo_force_assoc_cbfn` | 0x198ed8 | 228 |
| `wl_mbo_sub_cmd_force_assoc` | 0x198fbc | 728 |
| `wl_mbo_force_assoc_help_fn` | 0x199294 | 92 |
| `wl_mbo_bsstrans_reject_cbfn` | 0x1992f0 | 272 |
| `wl_mbo_sub_cmd_bsstrans_reject` | 0x199400 | 1052 |
| `wl_mbo_bsstrans_reject_help_fn` | 0x19981c | 252 |
| `wl_mbo_sub_cmd_send_notif` | 0x199918 | 708 |
| `wl_mbo_send_notif_help_fn` | 0x199bdc | 92 |
| `wl_mbo_nbr_info_cbfn` | 0x199c38 | 316 |
| `wl_mbo_sub_cmd_nbr_info_cache` | 0x199d74 | 1036 |
| `wl_mbo_nbr_info_cache_help_fn` | 0x19a180 | 132 |
| `wl_mbo_anqpo_support_cbfn` | 0x19a204 | 312 |
| `wl_mbo_sub_cmd_anqpo_support` | 0x19a33c | 992 |
| `wl_mbo_anqpo_support_help_fn` | 0x19a71c | 152 |
| `wl_mbo_sub_cmd_event_check` | 0x19a7b4 | 1388 |
| `wl_mbo_event_check_help_fn` | 0x19ad20 | 52 |
| `wl_mbo_event_mask_cbfn` | 0x19ad54 | 232 |
| `wl_mbo_sub_cmd_event_mask` | 0x19ae3c | 744 |
| `wl_mbo_event_mask_help_fn` | 0x19b124 | 92 |
| `wluc_oce_module_init` | 0x19b194 | 32 |
| `wl_oce_usage` | 0x19b1b4 | 156 |
| `wl_oce_main` | 0x19b250 | 352 |
| `wl_oce_enable_help_fn` | 0x19b3b0 | 72 |
| `wl_oce_probe_def_time_help_fn` | 0x19b3f8 | 72 |
| `wl_oce_fd_tx_period_help_fn` | 0x19b440 | 72 |
| `wl_oce_fd_tx_duration_help_fn` | 0x19b488 | 72 |
| `wl_oce_rssi_th_help_fn` | 0x19b4d0 | 72 |
| `wl_oce_rwan_links_help_fn` | 0x19b518 | 72 |
| `wl_oce_enable_cbfn` | 0x19b560 | 192 |
| `wl_oce_probe_def_time_cbfn` | 0x19b620 | 192 |
| `wl_oce_fd_tx_period_cbfn` | 0x19b6e0 | 192 |
| `wl_oce_fd_tx_duration_cbfn` | 0x19b7a0 | 192 |
| `wl_oce_rssi_th_cbfn` | 0x19b860 | 204 |
| `wl_oce_rwan_links_cbfn` | 0x19b92c | 220 |
| `wl_oce_process_iov_resp_buf` | 0x19ba08 | 292 |
| `wl_oce_get_iov_resp` | 0x19bb2c | 324 |
| `wl_oce_sub_cmd_enable` | 0x19bc70 | 472 |
| `wl_oce_sub_cmd_probe_def_time` | 0x19be48 | 472 |
| `wl_oce_sub_cmd_fd_tx_period` | 0x19c020 | 472 |
| `wl_oce_sub_cmd_fd_tx_duration` | 0x19c1f8 | 472 |
| `wl_oce_sub_cmd_rssi_th` | 0x19c3d0 | 472 |
| `wl_oce_sub_cmd_rwan_links` | 0x19c5a8 | 472 |
| `wluc_esp_module_init` | 0x19c794 | 32 |
| `wl_esp_usage` | 0x19c7b4 | 156 |
| `wl_esp_main` | 0x19c850 | 352 |
| `wl_esp_enable_help_fn` | 0x19c9b0 | 72 |
| `wl_esp_static_help_fn` | 0x19c9f8 | 272 |
| `wl_esp_enable_cbfn` | 0x19cb08 | 192 |
| `wl_esp_prespss_iov_resp_buf` | 0x19cbc8 | 292 |
| `wl_esp_get_iov_resp` | 0x19ccec | 324 |
| `wl_esp_sub_cmd_enable` | 0x19ce30 | 472 |
| `wl_esp_sub_cmd_static` | 0x19d008 | 1020 |
| `wl_ecounters_config_v1` | 0x19d418 | 980 |
| `wl_ecountersv2_xtlv_for_param_create` | 0x19d7ec | 1768 |
| `wl_ecounters_config_v2` | 0x19ded4 | 1956 |
| `wl_event_ecounters_config_v1` | 0x19e678 | 1852 |
| `wl_event_ecounters_config_v2` | 0x19edb4 | 1940 |
| `wl_ecounters_config` | 0x19f548 | 168 |
| `wl_event_ecounters_config` | 0x19f5f0 | 168 |
| `wl_ecounters_suspend` | 0x19f698 | 1496 |
| `wluc_ecounters_module_init` | 0x19fc70 | 32 |
| `wlc_band_name` | 0x19fca4 | 172 |
| `wl_pwrstats` | 0x19fd50 | 21068 |
| `wluc_pwrstats_module_init` | 0x1a4f9c | 32 |
| `wluc_adps_module_init` | 0x1a4fd0 | 56 |
| `wl_adps_help_all` | 0x1a5008 | 112 |
| `wl_adps_help` | 0x1a5078 | 180 |
| `wl_adps_validate_bcm_iov_buf` | 0x1a512c | 164 |
| `wl_adps_sub_cmd_mode` | 0x1a51d0 | 976 |
| `wl_adps_sub_cmd_params` | 0x1a55a0 | 2132 |
| `wl_adps_sub_cmd_start_count` | 0x1a5df4 | 664 |
| `wl_adps_sub_cmd_rssi` | 0x1a608c | 1136 |
| `wl_adps_sub_cmd_suspend` | 0x1a64fc | 404 |
| `_print_summary` | 0x1a6690 | 208 |
| `wl_adps_dump_print_summary` | 0x1a6760 | 380 |
| `wl_adps_dump_print_flag` | 0x1a68dc | 232 |
| `_print_general` | 0x1a69c4 | 112 |
| `wl_adps_dump_print_general` | 0x1a6a34 | 344 |
| `wl_adps_dump_print` | 0x1a6b8c | 1168 |
| `wl_adps_sub_cmd_dump` | 0x1a701c | 856 |
| `wl_adps_sub_cmd_dump_clear` | 0x1a7374 | 260 |
| `wl_adps_sub_cmd_help_mode_fn` | 0x1a7478 | 152 |
| `wl_adps_sub_cmd_help_dump_fn` | 0x1a7510 | 172 |
| `wl_adps_sub_cmd_help_dump_clear_fn` | 0x1a75bc | 52 |
| `wl_adps_sub_cmd_help_rssi_fn` | 0x1a75f0 | 112 |
| `wl_adps_sub_cmd_help_suspend_fn` | 0x1a7660 | 72 |
| `wl_adps_sub_cmd_help_params_fn` | 0x1a76a8 | 272 |
| `wl_adps_sub_cmd_help_start_count_fn` | 0x1a77b8 | 72 |
| `wl_adps_get_sub_cmd_info` | 0x1a7800 | 132 |
| `wl_adps_main` | 0x1a7884 | 284 |
| `wluc_leakyapstats_module_init` | 0x1a79b4 | 32 |
| `wluc_rpsnoa_module_init` | 0x1a79e8 | 32 |
| `wl_rpsnoa_usage` | 0x1a7a08 | 156 |
| `wl_rpsnoa_main` | 0x1a7aa4 | 372 |
| `wl_rpsnoa_sub_cmd_enable` | 0x1a7c18 | 1004 |
| `wl_rpsnoa_sub_cmd_status` | 0x1a8004 | 968 |
| `wl_rpsnoa_sub_cmd_params` | 0x1a83cc | 1440 |
| `wl_rpsnoa_enable_help_fn` | 0x1a896c | 268 |
| `wl_rpsnoa_status_help_fn` | 0x1a8a78 | 148 |
| `wl_rpsnoa_params_help_fn` | 0x1a8b0c | 268 |
| `wluc_pwropt_module_init` | 0x1a8c2c | 56 |
| `wl_bcntrim_stats` | 0x1a8c64 | 1388 |
| `wl_bcntrim_cfg` | 0x1a91d0 | 3016 |
| `wl_bcntrim_status_fw_disable_dump` | 0x1a9d98 | 300 |
| `wl_bcntrim_status` | 0x1a9ec4 | 2476 |
| `wl_ops_cfg` | 0x1aa870 | 3004 |
| `wl_ops_status_fw_disable_dump` | 0x1ab42c | 300 |
| `wl_ops_status` | 0x1ab558 | 3168 |
| `wl_nap_status_fw_status_dump` | 0x1ac1b8 | 300 |
| `wl_nap_status_hw_status_dump` | 0x1ac2e4 | 276 |
| `wl_nap_status` | 0x1ac3f8 | 1060 |
| `wl_psbw_cfg` | 0x1ac81c | 2760 |
| `wl_psbw_status_fw_disable_dump` | 0x1ad2e4 | 300 |
| `wl_psbw_fw_state_dump` | 0x1ad410 | 300 |
| `wl_psbw_status` | 0x1ad53c | 1952 |
| `wluc_btl_module_init` | 0x1adcf0 | 56 |
| `wl_btl` | 0x1add28 | 2396 |
| `wluc_tvpm_module_init` | 0x1ae698 | 32 |
| `wluc_tvpm_tvpm` | 0x1ae6b8 | 1832 |
| `wluc_bam_module_init` | 0x1aedf4 | 32 |
| `wl_bam_help_all` | 0x1aee14 | 400 |
| `wl_bam_main` | 0x1aefa4 | 320 |
| `wl_bam_sub_cmd_enable_help` | 0x1af0e4 | 372 |
| `wl_bam_sub_cmd_enable_get` | 0x1af258 | 660 |
| `wl_bam_sub_cmd_enable` | 0x1af4ec | 672 |
| `wl_bam_sub_cmd_disable_help` | 0x1af78c | 348 |
| `wl_bam_sub_cmd_disable` | 0x1af8e8 | 692 |
| `wl_bam_sub_cmd_config_bcn_help` | 0x1afb9c | 360 |
| `wl_bam_sub_cmd_config_help` | 0x1afd04 | 348 |
| `wl_bam_bcn_config_set` | 0x1afe60 | 840 |
| `wl_bam_bcn_config_print` | 0x1b01a8 | 408 |
| `wl_bam_sub_cmd_config` | 0x1b0340 | 888 |
| `wl_bam_sub_cmd_dump_help` | 0x1b06b8 | 348 |
| `wl_bam_bcn_dump` | 0x1b0814 | 412 |
| `wl_bam_sub_cmd_dump` | 0x1b09b0 | 776 |
| `alignment_test` | 0x1b0cb8 | 20 |
| `wluc_tdmtx_module_init` | 0x1b0ccc | 56 |
| `wl_tdmtx` | 0x1b0d04 | 3320 |
| `wl_tdmtx_print_status` | 0x1b19fc | 4636 |
| `__aeabi_uidiv` | 0x1b2c18 | 0 |
| `__udivsi3` | 0x1b2c18 | 168 |
| `__aeabi_uidivmod` | 0x1b2cc0 | 32 |
| `__aeabi_idiv` | 0x1b2ce0 | 0 |
| `__divsi3` | 0x1b2ce0 | 220 |
| `__aeabi_idivmod` | 0x1b2dbc | 32 |
| `__aeabi_drsub` | 0x1b2ddc | 0 |
| `__aeabi_dsub` | 0x1b2de4 | 688 |
| `__subdf3` | 0x1b2de4 | 688 |
| `__adddf3` | 0x1b2de8 | 684 |
| `__aeabi_dadd` | 0x1b2de8 | 684 |
| `__aeabi_ui2d` | 0x1b3094 | 36 |
| `__floatunsidf` | 0x1b3094 | 36 |
| `__aeabi_i2d` | 0x1b30b8 | 40 |
| `__floatsidf` | 0x1b30b8 | 40 |
| `__aeabi_f2d` | 0x1b30e0 | 64 |
| `__extendsfdf2` | 0x1b30e0 | 64 |
| `__aeabi_ul2d` | 0x1b3120 | 116 |
| `__floatundidf` | 0x1b3120 | 116 |
| `__aeabi_l2d` | 0x1b3134 | 96 |
| `__floatdidf` | 0x1b3134 | 96 |
| `__aeabi_dmul` | 0x1b3194 | 620 |
| `__muldf3` | 0x1b3194 | 620 |
| `__aeabi_ddiv` | 0x1b3400 | 516 |
| `__divdf3` | 0x1b3400 | 516 |
| `__aeabi_d2f` | 0x1b3604 | 160 |
| `__truncdfsf2` | 0x1b3604 | 160 |
| `__aeabi_frsub` | 0x1b36a4 | 412 |
| `__aeabi_fsub` | 0x1b36ac | 404 |
| `__subsf3` | 0x1b36ac | 404 |
| `__addsf3` | 0x1b36b0 | 400 |
| `__aeabi_fadd` | 0x1b36b0 | 400 |
| `__aeabi_ui2f` | 0x1b3840 | 40 |
| `__floatunsisf` | 0x1b3840 | 40 |
| `__aeabi_i2f` | 0x1b3848 | 32 |
| `__floatsisf` | 0x1b3848 | 32 |
| `__aeabi_ul2f` | 0x1b3868 | 140 |
| `__floatundisf` | 0x1b3868 | 140 |
| `__aeabi_l2f` | 0x1b3878 | 124 |
| `__floatdisf` | 0x1b3878 | 124 |
| `__aeabi_fmul` | 0x1b38f4 | 408 |
| `__mulsf3` | 0x1b38f4 | 408 |
| `__aeabi_fdiv` | 0x1b3a8c | 352 |
| `__divsf3` | 0x1b3a8c | 352 |
| `__gesf2` | 0x1b3bec | 116 |
| `__gtsf2` | 0x1b3bec | 116 |
| `__lesf2` | 0x1b3bf4 | 108 |
| `__ltsf2` | 0x1b3bf4 | 108 |
| `__cmpsf2` | 0x1b3bfc | 100 |
| `__eqsf2` | 0x1b3bfc | 100 |
| `__nesf2` | 0x1b3bfc | 100 |
| `__aeabi_cfrcmple` | 0x1b3c60 | 36 |
| `__aeabi_cfcmpeq` | 0x1b3c70 | 20 |
| `__aeabi_cfcmple` | 0x1b3c70 | 20 |
| `__aeabi_fcmpeq` | 0x1b3c84 | 20 |
| `__aeabi_fcmplt` | 0x1b3c98 | 20 |
| `__aeabi_fcmple` | 0x1b3cac | 20 |
| `__aeabi_fcmpge` | 0x1b3cc0 | 20 |
| `__aeabi_fcmpgt` | 0x1b3cd4 | 20 |
| `__aeabi_f2uiz` | 0x1b3ce8 | 84 |
| `__fixunssfsi` | 0x1b3ce8 | 84 |
| `__aeabi_uldivmod` | 0x1b3d3c | 0 |
| `__aeabi_idiv0` | 0x1b3d78 | 16 |
| `__aeabi_ldiv0` | 0x1b3d78 | 16 |
| `__gnu_ldivmod_helper` | 0x1b3d88 | 60 |
| `__gnu_uldivmod_helper` | 0x1b3dc4 | 60 |
| `selfrel_offset31` | 0x1b3e00 | 24 |
| `search_EIT_table` | 0x1b3e18 | 172 |
| `__gnu_unwind_get_pr_addr` | 0x1b3ec4 | 80 |
| `get_eit_entry` | 0x1b3f14 | 272 |
| `restore_non_core_regs` | 0x1b4024 | 108 |
| `_Unwind_decode_typeinfo_ptr.isra.0` | 0x1b4090 | 20 |
| `__gnu_unwind_24bit.isra.1` | 0x1b40a4 | 8 |
| `_Unwind_DebugHook` | 0x1b40ac | 4 |
| `unwind_phase2` | 0x1b40b0 | 100 |
| `unwind_phase2_forced` | 0x1b4114 | 292 |
| `_Unwind_GetCFA` | 0x1b4238 | 8 |
| `__gnu_Unwind_RaiseException` | 0x1b4240 | 164 |
| `__gnu_Unwind_ForcedUnwind` | 0x1b42e4 | 28 |
| `__gnu_Unwind_Resume` | 0x1b4300 | 116 |
| `__gnu_Unwind_Resume_or_Rethrow` | 0x1b4374 | 32 |
| `_Unwind_Complete` | 0x1b4394 | 4 |
| `_Unwind_DeleteException` | 0x1b4398 | 32 |
| `_Unwind_VRS_Get` | 0x1b43b8 | 92 |
| `_Unwind_GetGR` | 0x1b4414 | 40 |
| `_Unwind_VRS_Set` | 0x1b443c | 92 |
| `_Unwind_SetGR` | 0x1b4498 | 44 |
| `__gnu_Unwind_Backtrace` | 0x1b44c4 | 196 |
| `__gnu_unwind_pr_common` | 0x1b4588 | 1012 |
| `__aeabi_unwind_cpp_pr0` | 0x1b497c | 8 |
| `__aeabi_unwind_cpp_pr1` | 0x1b4984 | 8 |
| `__aeabi_unwind_cpp_pr2` | 0x1b498c | 8 |
| `_Unwind_VRS_Pop` | 0x1b4994 | 856 |
| `__restore_core_regs` | 0x1b4cec | 20 |
| `restore_core_regs` | 0x1b4cec | 20 |
| `__gnu_Unwind_Restore_VFP` | 0x1b4d00 | 0 |
| `__gnu_Unwind_Save_VFP` | 0x1b4d08 | 0 |
| `__gnu_Unwind_Restore_VFP_D` | 0x1b4d10 | 0 |
| `__gnu_Unwind_Save_VFP_D` | 0x1b4d18 | 0 |
| `__gnu_Unwind_Restore_VFP_D_16_to_31` | 0x1b4d20 | 0 |
| `__gnu_Unwind_Save_VFP_D_16_to_31` | 0x1b4d28 | 0 |
| `__gnu_Unwind_Restore_WMMXD` | 0x1b4d30 | 0 |
| `__gnu_Unwind_Save_WMMXD` | 0x1b4d74 | 0 |
| `__gnu_Unwind_Restore_WMMXC` | 0x1b4db8 | 0 |
| `__gnu_Unwind_Save_WMMXC` | 0x1b4dcc | 0 |
| `_Unwind_RaiseException` | 0x1b4de0 | 36 |
| `___Unwind_RaiseException` | 0x1b4de0 | 36 |
| `_Unwind_Resume` | 0x1b4e04 | 36 |
| `___Unwind_Resume` | 0x1b4e04 | 36 |
| `_Unwind_Resume_or_Rethrow` | 0x1b4e28 | 36 |
| `___Unwind_Resume_or_Rethrow` | 0x1b4e28 | 36 |
| `_Unwind_ForcedUnwind` | 0x1b4e4c | 36 |
| `___Unwind_ForcedUnwind` | 0x1b4e4c | 36 |
| `_Unwind_Backtrace` | 0x1b4e70 | 36 |
| `___Unwind_Backtrace` | 0x1b4e70 | 36 |
| `next_unwind_byte` | 0x1b4e94 | 96 |
| `_Unwind_GetGR.constprop.0` | 0x1b4ef4 | 40 |
| `unwind_UCB_from_context` | 0x1b4f1c | 4 |
| `__gnu_unwind_execute` | 0x1b4f20 | 892 |
| `__gnu_unwind_frame` | 0x1b529c | 64 |
| `_Unwind_GetRegionStart` | 0x1b52dc | 16 |
| `_Unwind_GetLanguageSpecificData` | 0x1b52ec | 28 |
| `_Unwind_GetDataRelBase` | 0x1b5308 | 8 |
| `_Unwind_GetTextRelBase` | 0x1b5310 | 8 |
| `__divdi3` | 0x1b5318 | 1176 |
| `__udivdi3` | 0x1b57b0 | 1028 |
| `abort` | 0x1b5bb4 | 8 |
| `memcmp` | 0x1b5bbc | 652 |
| `__memcpy_chk` | 0x1b5e48 | 8 |
| `memcpy` | 0x1b5e50 | 828 |
| `__memset_chk` | 0x1b618c | 32 |
| `bzero` | 0x1b61ac | 8 |
| `memset` | 0x1b61b4 | 200 |
| `strcmp` | 0x1b627c | 576 |
| `strcpy` | 0x1b64bc | 248 |
| `__libc_android_abort` | 0x1b65b5 | 86 |
| `__errno` | 0x1b660b | 8 |
| `ffs` | 0x1b6613 | 20 |
| `fork` | 0x1b6629 | 68 |
| `getpid` | 0x1b666d | 20 |
| `gettid` | 0x1b6681 | 10 |
| `_ZL13parse_decimalPKcPi` | 0x1b668b | 36 |
| `_ZL14format_integerPcjyc` | 0x1b66af | 258 |
| `_ZL22__libc_open_log_socketv` | 0x1b67b1 | 180 |
| `_ZL16__libc_write_logiPKcS0_` | 0x1b6865 | 284 |
| `_ZN18BufferOutputStream4SendEPKci` | 0x1b6981 | 74 |
| `_Z10SendRepeatI18BufferOutputStreamEvRT_ci` | 0x1b69cd | 84 |
| `_Z11out_vformatI18BufferOutputStreamEvRT_PKcSt9__va_list` | 0x1b6a21 | 768 |
| `_ZN14FdOutputStream4SendEPKci` | 0x1b6d21 | 60 |
| `_Z10SendRepeatI14FdOutputStreamEvRT_ci` | 0x1b6d5d | 84 |
| `__libc_format_buffer` | 0x1b6db1 | 50 |
| `__libc_format_fd` | 0x1b6de5 | 796 |
| `__libc_format_log_va_list` | 0x1b7101 | 96 |
| `__libc_format_log` | 0x1b7161 | 26 |
| `__libc_android_log_event_int` | 0x1b717b | 134 |
| `__libc_android_log_event_uid` | 0x1b7201 | 20 |
| `android_set_abort_message` | 0x1b7215 | 132 |
| `_ZL12__libc_fatalPKcSt9__va_list` | 0x1b7299 | 152 |
| `__libc_fatal_no_abort` | 0x1b7331 | 26 |
| `__libc_fatal` | 0x1b734b | 20 |
| `__fortify_chk_fail` | 0x1b7361 | 28 |
| `open` | 0x1b737d | 44 |
| `open64` | 0x1b737d | 44 |
| `openat` | 0x1b73a9 | 38 |
| `openat64` | 0x1b73a9 | 38 |
| `creat` | 0x1b73cf | 10 |
| `creat64` | 0x1b73cf | 10 |
| `__open_2` | 0x1b73d9 | 44 |
| `__openat_2` | 0x1b7405 | 36 |
| `poll` | 0x1b7429 | 40 |
| `ppoll` | 0x1b7451 | 50 |
| `select` | 0x1b7483 | 84 |
| `pselect` | 0x1b74d7 | 62 |
| `_Z27__bionic_atfork_run_preparev` | 0x1b7515 | 40 |
| `_Z25__bionic_atfork_run_childv` | 0x1b753d | 40 |
| `_Z26__bionic_atfork_run_parentv` | 0x1b7565 | 40 |
| `pthread_atfork` | 0x1b758d | 100 |
| `_Z31_pthread_internal_remove_lockedP18pthread_internal_t` | 0x1b75f1 | 36 |
| `_Z21_pthread_internal_addP18pthread_internal_t` | 0x1b7615 | 64 |
| `__get_thread` | 0x1b7655 | 8 |
| `_Z24__timespec_from_absoluteP8timespecPKS_i` | 0x1b765d | 68 |
| `__futex_wait_ex` | 0x1b76a1 | 62 |
| `_ZL25__pthread_mutex_timedlockP15pthread_mutex_tPK8timespeci` | 0x1b76df | 388 |
| `__futex_wake_ex.constprop.0` | 0x1b7863 | 50 |
| `pthread_mutexattr_init` | 0x1b7895 | 8 |
| `pthread_mutexattr_destroy` | 0x1b789d | 10 |
| `pthread_mutexattr_gettype` | 0x1b78a7 | 20 |
| `pthread_mutexattr_settype` | 0x1b78bb | 22 |
| `pthread_mutexattr_setpshared` | 0x1b78d1 | 30 |
| `pthread_mutexattr_getpshared` | 0x1b78ef | 12 |
| `pthread_mutex_init` | 0x1b78fb | 56 |
| `pthread_mutex_lock` | 0x1b7933 | 324 |
| `pthread_mutex_unlock` | 0x1b7a77 | 158 |
| `pthread_mutex_trylock` | 0x1b7b15 | 168 |
| `pthread_mutex_lock_timeout_np` | 0x1b7bbd | 100 |
| `pthread_mutex_timedlock` | 0x1b7c21 | 6 |
| `pthread_mutex_destroy` | 0x1b7c29 | 20 |
| `raise` | 0x1b7c3d | 32 |
| `rand` | 0x1b7c5d | 4 |
| `srand` | 0x1b7c61 | 4 |
| `recv` | 0x1b7c65 | 16 |
| `sigaction` | 0x1b7c75 | 4 |
| `sigdelset` | 0x1b7c79 | 46 |
| `sigemptyset` | 0x1b7ca7 | 30 |
| `sigfillset` | 0x1b7cc5 | 32 |
| `_Z7_signaliPFviEi` | 0x1b7ce5 | 40 |
| `signal` | 0x1b7d0d | 8 |
| `sigprocmask` | 0x1b7d15 | 54 |
| `socket` | 0x1b7d4d | 16 |
| `_ZL33__bionic_tls_strerror_key_destroyPv` | 0x1b7d5d | 4 |
| `strerror` | 0x1b7d61 | 60 |
| `__strerror_lookup` | 0x1b7d9d | 36 |
| `__strsignal_lookup` | 0x1b7dc1 | 36 |
| `strerror_r` | 0x1b7de5 | 76 |
| `__strsignal` | 0x1b7e31 | 88 |
| `wait` | 0x1b7e89 | 14 |
| `waitpid` | 0x1b7e97 | 6 |
| `waitid` | 0x1b7e9d | 14 |
| `mmap64` | 0x1b7ead | 136 |
| `mmap` | 0x1b7f35 | 24 |
| `strlen` | 0x1b7f4d | 98 |
| `memmove` | 0x1b7faf | 250 |
| `strcat` | 0x1b80a9 | 26 |
| `usleep` | 0x1b80c5 | 48 |
| `fclose` | 0x1b80f5 | 136 |
| `fopen` | 0x1b817d | 144 |
| `random_unlocked` | 0x1b820d | 148 |
| `srandom_unlocked.part.1` | 0x1b82a1 | 160 |
| `srandom` | 0x1b8341 | 64 |
| `initstate` | 0x1b8381 | 424 |
| `setstate` | 0x1b8529 | 288 |
| `random` | 0x1b8649 | 32 |
| `isalnum` | 0x1b8669 | 40 |
| `isalpha` | 0x1b8691 | 40 |
| `isblank` | 0x1b86b9 | 18 |
| `iscntrl` | 0x1b86cd | 40 |
| `isdigit` | 0x1b86f5 | 40 |
| `isgraph` | 0x1b871d | 40 |
| `islower` | 0x1b8745 | 40 |
| `isprint` | 0x1b876d | 40 |
| `ispunct` | 0x1b8795 | 40 |
| `isspace` | 0x1b87bd | 40 |
| `isupper` | 0x1b87e5 | 40 |
| `isxdigit` | 0x1b880d | 40 |
| `isascii` | 0x1b8835 | 10 |
| `toascii` | 0x1b883f | 6 |
| `_toupper` | 0x1b8845 | 4 |
| `_tolower` | 0x1b8849 | 4 |
| `time` | 0x1b884d | 32 |
| `tolower` | 0x1b886d | 32 |
| `toupper` | 0x1b888d | 32 |
| `feof` | 0x1b88ad | 24 |
| `ferror` | 0x1b88c5 | 24 |
| `__sflush` | 0x1b88dd | 76 |
| `fflush` | 0x1b8929 | 68 |
| `__sflush_locked` | 0x1b896d | 26 |
| `fgets` | 0x1b8987 | 184 |
| `fileno` | 0x1b8a3f | 22 |
| `_cleanup` | 0x1b8a55 | 12 |
| `__sinit` | 0x1b8a61 | 140 |
| `__sfp` | 0x1b8aed | 304 |
| `fprintf` | 0x1b8c1d | 26 |
| `fputc` | 0x1b8c37 | 4 |
| `fputs` | 0x1b8c3b | 66 |
| `fread` | 0x1b8c7d | 192 |
| `fseeko` | 0x1b8d3d | 640 |
| `fseek` | 0x1b8fbd | 4 |
| `ftello` | 0x1b8fc1 | 114 |
| `ftell` | 0x1b9033 | 4 |
| `__sfvwrite` | 0x1b9037 | 598 |
| `_fwalk` | 0x1b928d | 56 |
| `fwrite` | 0x1b92c5 | 146 |
| `__swhatbuf` | 0x1b9359 | 108 |
| `__smakebuf` | 0x1b93c5 | 108 |
| `perror` | 0x1b9431 | 140 |
| `printf` | 0x1b94bd | 48 |
| `putc_unlocked` | 0x1b94ed | 98 |
| `putc` | 0x1b954f | 32 |
| `putchar_unlocked` | 0x1b9571 | 24 |
| `putchar` | 0x1b9589 | 24 |
| `puts` | 0x1b95a1 | 112 |
| `lflush` | 0x1b9611 | 18 |
| `__srefill` | 0x1b9625 | 260 |
| `eofread` | 0x1b9729 | 4 |
| `sscanf` | 0x1b972d | 96 |
| `__sread` | 0x1b978d | 34 |
| `__swrite` | 0x1b97af | 50 |
| `__sseek` | 0x1b97e1 | 36 |
| `__sclose` | 0x1b9805 | 8 |
| `__sprint` | 0x1b980d | 28 |
| `__vfprintf` | 0x1b9829 | 5636 |
| `vfprintf` | 0x1bae2d | 34 |
| `__svfscanf` | 0x1bae51 | 2696 |
| `vfscanf` | 0x1bb8d9 | 34 |
| `__swbuf` | 0x1bb8fb | 132 |
| `__swsetup` | 0x1bb981 | 148 |
| `__cxa_atexit` | 0x1bba15 | 220 |
| `__cxa_finalize` | 0x1bbaf1 | 236 |
| `__atexit_register_cleanup` | 0x1bbbdd | 152 |
| `atoi` | 0x1bbc75 | 8 |
| `strtoimax` | 0x1bbc7d | 444 |
| `strtol` | 0x1bbe39 | 342 |
| `strtoul` | 0x1bbf8f | 268 |
| `strtoull` | 0x1bc09b | 330 |
| `strtouq` | 0x1bc09b | 330 |
| `strtoumax` | 0x1bc1e5 | 330 |
| `system` | 0x1bc331 | 208 |
| `strcasecmp` | 0x1bc401 | 44 |
| `strncasecmp` | 0x1bc42d | 56 |
| `strcspn` | 0x1bc465 | 32 |
| `strdup` | 0x1bc485 | 32 |
| `strsep` | 0x1bc4a5 | 50 |
| `strspn` | 0x1bc4d7 | 30 |
| `strstr` | 0x1bc4f5 | 62 |
| `strtok_r` | 0x1bc533 | 78 |
| `strtok` | 0x1bc581 | 12 |
| `__stack_chk_fail` | 0x1bc58d | 16 |
| `kill` | 0x1bc59c | 32 |
| `_Exit` | 0x1bc5bc | 32 |
| `_exit` | 0x1bc5bc | 32 |
| `sched_get_priority_max` | 0x1bc5dc | 32 |
| `lseek` | 0x1bc5fc | 32 |
| `__ppoll` | 0x1bc61c | 40 |
| `__openat` | 0x1bc644 | 32 |
| `sched_setscheduler` | 0x1bc668 | 32 |
| `bind` | 0x1bc688 | 32 |
| `gettimeofday` | 0x1bc6ac | 32 |
| `__rt_sigprocmask` | 0x1bc6cc | 32 |
| `clock_gettime` | 0x1bc6ec | 32 |
| `wait4` | 0x1bc710 | 32 |
| `sched_getscheduler` | 0x1bc730 | 32 |
| `close` | 0x1bc750 | 32 |
| `vfork` | 0x1bc770 | 32 |
| `getuid` | 0x1bc790 | 32 |
| `madvise` | 0x1bc7b0 | 32 |
| `__pselect6` | 0x1bc7d0 | 40 |
| `write` | 0x1bc7fc | 32 |
| `writev` | 0x1bc81c | 32 |
| `recvfrom` | 0x1bc83c | 40 |
| `mprotect` | 0x1bc864 | 32 |
| `__getpid` | 0x1bc884 | 32 |
| `fstat` | 0x1bc8a4 | 32 |
| `fstat64` | 0x1bc8a4 | 32 |
| `read` | 0x1bc8c4 | 32 |
| `__waitid` | 0x1bc8e4 | 40 |
| `sched_setparam` | 0x1bc90c | 32 |
| `__mmap2` | 0x1bc92c | 40 |
| `execve` | 0x1bc954 | 32 |
| `munmap` | 0x1bc974 | 32 |
| `nanosleep` | 0x1bc994 | 32 |
| `__sigaction` | 0x1bc9b4 | 32 |
| `_add` | 0x1bc9d5 | 152 |
| `_conv` | 0x1bca6d | 72 |
| `getformat.constprop.0` | 0x1bcab5 | 36 |
| `_yconv` | 0x1bcad9 | 240 |
| `_fmt` | 0x1bcbc9 | 1860 |
| `strftime` | 0x1bd30d | 60 |
| `detzcode` | 0x1bd349 | 24 |
| `getzname` | 0x1bd361 | 32 |
| `getnum` | 0x1bd381 | 58 |
| `getoffset` | 0x1bd3bb | 130 |
| `getrule` | 0x1bd43d | 152 |
| `transtime` | 0x1bd4d5 | 328 |
| `increment_overflow` | 0x1bd61d | 50 |
| `increment_overflow32` | 0x1bd64f | 50 |
| `increment_overflow_time` | 0x1bd681 | 42 |
| `normalize_overflow` | 0x1bd6ab | 52 |
| `leapcorr` | 0x1bd6e1 | 56 |
| `settzname` | 0x1bd719 | 328 |
| `_tzLock` | 0x1bd861 | 12 |
| `_tzUnlock` | 0x1bd86d | 12 |
| `tmcomp` | 0x1bd879 | 72 |
| `__bionic_open_tzdata_path` | 0x1bd8c1 | 808 |
| `time2sub` | 0x1bdbe9 | 976 |
| `time2` | 0x1bdfb9 | 56 |
| `time1` | 0x1bdff1 | 400 |
| `leaps_thru_end_of` | 0x1be181 | 42 |
| `timesub.isra.2` | 0x1be1ad | 916 |
| `tzparse` | 0x1be541 | 1092 |
| `tzload` | 0x1be985 | 1276 |
| `gmtload` | 0x1bee81 | 40 |
| `gmtsub` | 0x1beea9 | 112 |
| `localsub` | 0x1bef19 | 280 |
| `tzsetwall` | 0x1bf031 | 88 |
| `tzset_locked` | 0x1bf089 | 276 |
| `tzset` | 0x1bf19d | 18 |
| `localtime_r` | 0x1bf1af | 36 |
| `localtime` | 0x1bf1d5 | 12 |
| `gmtime_r` | 0x1bf1e1 | 32 |
| `gmtime` | 0x1bf201 | 12 |
| `offtime` | 0x1bf20d | 16 |
| `ctime` | 0x1bf21d | 14 |
| `ctime_r` | 0x1bf22b | 22 |
| `mktime` | 0x1bf241 | 40 |
| `timelocal` | 0x1bf269 | 12 |
| `timegm` | 0x1bf275 | 44 |
| `timeoff` | 0x1bf2a1 | 24 |
| `time2posix` | 0x1bf2b9 | 26 |
| `posix2time` | 0x1bf2d3 | 94 |
| `mktime_tz` | 0x1bf331 | 172 |
| `__strlen_chk` | 0x1bf3dd | 28 |
| `__strncpy_chk` | 0x1bf3f9 | 32 |
| `__strncpy_chk2` | 0x1bf419 | 84 |
| `fcntl` | 0x1bf46d | 28 |
| `fstatfs` | 0x1bf489 | 8 |
| `fstatfs64` | 0x1bf489 | 8 |
| `statfs` | 0x1bf491 | 8 |
| `statfs64` | 0x1bf491 | 8 |
| `lseek64` | 0x1bf499 | 36 |
| `pread` | 0x1bf4bd | 18 |
| `pwrite` | 0x1bf4cf | 18 |
| `fallocate` | 0x1bf4e1 | 20 |
| `getrlimit64` | 0x1bf4f5 | 14 |
| `setrlimit64` | 0x1bf503 | 14 |
| `strchr` | 0x1bf511 | 8 |
| `ioctl` | 0x1bf519 | 28 |
| `isatty` | 0x1bf535 | 56 |
| `snprintf` | 0x1bf56d | 104 |
| `sprintf` | 0x1bf5d5 | 94 |
| `safe_year.part.0` | 0x1bf635 | 312 |
| `timegm64` | 0x1bf76d | 552 |
| `fake_localtime_r` | 0x1bf995 | 48 |
| `fake_gmtime_r` | 0x1bf9c5 | 48 |
| `mktime64` | 0x1bf9f5 | 472 |
| `timelocal64` | 0x1bfbcd | 4 |
| `gmtime64_r` | 0x1bfbd1 | 872 |
| `localtime64_r` | 0x1bff39 | 296 |
| `asctime64_r` | 0x1c0061 | 96 |
| `ctime64_r` | 0x1c00c1 | 26 |
| `localtime64` | 0x1c00dd | 12 |
| `gmtime64` | 0x1c00e9 | 12 |
| `asctime64` | 0x1c00f5 | 12 |
| `ctime64` | 0x1c0101 | 14 |
| `memchr` | 0x1c010f | 76 |
| `strncat` | 0x1c015b | 46 |
| `strncmp` | 0x1c0189 | 38 |
| `strncpy` | 0x1c01af | 38 |
| `_ZL18hash_entry_comparePKvS0_` | 0x1c01d5 | 70 |
| `get_malloc_leak_info` | 0x1c021d | 324 |
| `free_malloc_leak_info` | 0x1c0361 | 4 |
| `calloc` | 0x1c0365 | 4 |
| `free` | 0x1c0369 | 4 |
| `mallinfo` | 0x1c036d | 12 |
| `malloc` | 0x1c0379 | 4 |
| `malloc_usable_size` | 0x1c037d | 4 |
| `memalign` | 0x1c0381 | 4 |
| `posix_memalign` | 0x1c0385 | 4 |
| `pvalloc` | 0x1c0389 | 4 |
| `realloc` | 0x1c038d | 4 |
| `valloc` | 0x1c0391 | 4 |
| `malloc_debug_init` | 0x1c0395 | 2 |
| `malloc_debug_fini` | 0x1c0397 | 2 |
| `__libc_init` | 0x1c0399 | 180 |
| `syscall` | 0x1c044c | 52 |
| `__assert` | 0x1c0481 | 24 |
| `__assert2` | 0x1c0499 | 28 |
| `longjmperror` | 0x1c04b5 | 16 |
| `timespec_from_timeval` | 0x1c04c5 | 32 |
| `timespec_from_ms` | 0x1c04e5 | 40 |
| `timeval_from_timespec` | 0x1c050d | 22 |
| `connect` | 0x1c0525 | 16 |
| `flockfile` | 0x1c0535 | 12 |
| `ftrylockfile` | 0x1c0541 | 14 |
| `funlockfile` | 0x1c054f | 12 |
| `getauxval` | 0x1c055d | 32 |
| `__libc_current_sigrtmax` | 0x1c057d | 4 |
| `__libc_current_sigrtmin` | 0x1c0581 | 4 |
| `_Z15__libc_init_tlsR19KernelArgumentBlock` | 0x1c0585 | 108 |
| `_Z18__libc_init_commonR19KernelArgumentBlock` | 0x1c05f1 | 128 |
| `__libc_fini` | 0x1c0671 | 84 |
| `_ZL13__locale_initv` | 0x1c06c5 | 104 |
| `_ZL21__is_supported_localePKc` | 0x1c072d | 84 |
| `__ctype_get_mb_cur_max` | 0x1c0781 | 48 |
| `localeconv` | 0x1c07b1 | 32 |
| `duplocale` | 0x1c07d1 | 40 |
| `freelocale` | 0x1c07f9 | 4 |
| `newlocale` | 0x1c07fd | 80 |
| `setlocale` | 0x1c084d | 100 |
| `uselocale` | 0x1c08b1 | 44 |
| `_ZL22fallBackNetIdForResolvj` | 0x1c08dd | 2 |
| `_ZL35__pthread_attr_getstack_main_threadPPvPj` | 0x1c08e1 | 256 |
| `pthread_attr_init` | 0x1c09e1 | 26 |
| `pthread_attr_destroy` | 0x1c09fb | 14 |
| `pthread_attr_setdetachstate` | 0x1c0a09 | 30 |
| `pthread_attr_getdetachstate` | 0x1c0a27 | 12 |
| `pthread_attr_setschedpolicy` | 0x1c0a33 | 6 |
| `pthread_attr_getschedpolicy` | 0x1c0a39 | 8 |
| `pthread_attr_setschedparam` | 0x1c0a41 | 8 |
| `pthread_attr_getschedparam` | 0x1c0a49 | 8 |
| `pthread_attr_setstacksize` | 0x1c0a51 | 16 |
| `pthread_attr_setstack` | 0x1c0a61 | 30 |
| `pthread_attr_getstack` | 0x1c0a7f | 26 |
| `pthread_attr_getstacksize` | 0x1c0a99 | 16 |
| `pthread_attr_setguardsize` | 0x1c0aa9 | 6 |
| `pthread_attr_getguardsize` | 0x1c0aaf | 8 |
| `pthread_getattr_np` | 0x1c0ab7 | 24 |
| `pthread_attr_setscope` | 0x1c0acf | 16 |
| `pthread_attr_getscope` | 0x1c0adf | 6 |
| `_ZL12__do_nothingPv` | 0x1c0ae5 | 4 |
| `_Z10__init_tlsP18pthread_internal_t` | 0x1c0ae9 | 56 |
| `_Z29__init_alternate_signal_stackP18pthread_internal_t` | 0x1c0b21 | 60 |
| `_ZL15__pthread_startPv` | 0x1c0b5d | 36 |
| `_Z13__init_threadP18pthread_internal_tb` | 0x1c0b81 | 80 |
| `pthread_create` | 0x1c0bd1 | 488 |
| `__pthread_cleanup_push` | 0x1c0db9 | 24 |
| `__pthread_cleanup_pop` | 0x1c0dd1 | 24 |
| `pthread_exit` | 0x1c0de9 | 168 |
| `_ZN18ScopedTlsMapAccess7IsInUseEi.isra.1` | 0x1c0e91 | 40 |
| `_ZN18ScopedTlsMapAccessC1Ev` | 0x1c0eb9 | 64 |
| `_ZN18ScopedTlsMapAccessC2Ev` | 0x1c0eb9 | 64 |
| `_Z21pthread_key_clean_allv` | 0x1c0ef9 | 128 |
| `pthread_key_create` | 0x1c0f79 | 96 |
| `pthread_key_delete` | 0x1c0fd9 | 140 |
| `pthread_getspecific` | 0x1c1065 | 20 |
| `pthread_setspecific` | 0x1c1079 | 60 |
| `pthread_kill` | 0x1c10b5 | 100 |
| `pthread_once` | 0x1c1119 | 148 |
| `pthread_self` | 0x1c11ad | 4 |
| `__set_errno_internal` | 0x1c11b1 | 16 |
| `__set_errno` | 0x1c11c1 | 16 |
| `sigaddset` | 0x1c11d1 | 46 |
| `strtold` | 0x1c11ff | 4 |
| `_ZL23android_iinfo_to_passwdP13stubs_state_tPK15android_id_info` | 0x1c1205 | 64 |
| `_ZL16__stubs_key_initv` | 0x1c1245 | 20 |
| `_ZL16stubs_state_freePv` | 0x1c1259 | 4 |
| `_ZL18unimplemented_stubPKc` | 0x1c125d | 60 |
| `_ZL13__stubs_statev` | 0x1c1299 | 100 |
| `_ZL16app_id_from_namePKc` | 0x1c12fd | 228 |
| `_ZL32print_app_name_from_appid_useridjjPci.constprop.5` | 0x1c13e1 | 160 |
| `_ZL15app_id_to_groupjP13stubs_state_t` | 0x1c1481 | 80 |
| `_ZL16app_id_to_passwdjP13stubs_state_t` | 0x1c14d1 | 132 |
| `getpwuid` | 0x1c1555 | 64 |
| `getpwnam` | 0x1c1595 | 80 |
| `_ZL10do_getpw_riPKcjP6passwdPcjPS2_` | 0x1c15e5 | 192 |
| `getpwnam_r` | 0x1c16a5 | 34 |
| `getpwuid_r` | 0x1c16c7 | 30 |
| `getgrouplist` | 0x1c16e5 | 24 |
| `getlogin` | 0x1c16fd | 16 |
| `getgrgid` | 0x1c170d | 76 |
| `getgrnam` | 0x1c1759 | 100 |
| `getnetbyname` | 0x1c17bd | 4 |
| `getnetbyaddr` | 0x1c17c1 | 4 |
| `getprotobyname` | 0x1c17c5 | 4 |
| `getprotobynumber` | 0x1c17c9 | 4 |
| `endpwent` | 0x1c17cd | 12 |
| `getusershell` | 0x1c17d9 | 20 |
| `setusershell` | 0x1c17ed | 12 |
| `endusershell` | 0x1c17f9 | 12 |
| `getpagesize` | 0x1c1805 | 6 |
| `_ZL11to_prop_objj` | 0x1c180d | 52 |
| `_ZL11find_nth_fnPK9prop_infoPv` | 0x1c1841 | 16 |
| `_ZL16foreach_propertyjPFvPK9prop_infoPvES2_` | 0x1c1851 | 100 |
| `__futex_wait.constprop.1` | 0x1c18b5 | 42 |
| `__futex_wake.constprop.2` | 0x1c18df | 44 |
| `_ZL11new_prop_btPKchPj` | 0x1c190d | 100 |
| `_ZL13find_propertyP7prop_btPKchS2_hb` | 0x1c1971 | 372 |
| `__system_properties_init` | 0x1c1ae5 | 280 |
| `__system_property_set_filename` | 0x1c1bfd | 44 |
| `__system_property_area_init` | 0x1c1c29 | 208 |
| `__system_property_find` | 0x1c1cf9 | 60 |
| `__system_property_set` | 0x1c1d35 | 316 |
| `__system_property_update` | 0x1c1e71 | 100 |
| `__system_property_add` | 0x1c1ed5 | 96 |
| `__system_property_serial` | 0x1c1f35 | 22 |
| `__system_property_read` | 0x1c1f4d | 84 |
| `__system_property_get` | 0x1c1fa1 | 26 |
| `__system_property_wait_any` | 0x1c1fbd | 44 |
| `__system_property_foreach` | 0x1c1fe9 | 40 |
| `__system_property_find_nth` | 0x1c2011 | 36 |
| `cfgetispeed` | 0x1c2035 | 10 |
| `cfgetospeed` | 0x1c203f | 10 |
| `cfmakeraw` | 0x1c2049 | 46 |
| `cfsetspeed` | 0x1c2077 | 26 |
| `cfsetispeed` | 0x1c2091 | 4 |
| `cfsetospeed` | 0x1c2095 | 4 |
| `tcdrain` | 0x1c2099 | 10 |
| `tcflow` | 0x1c20a3 | 10 |
| `tcflush` | 0x1c20ad | 10 |
| `tcgetattr` | 0x1c20b7 | 10 |
| `tcgetsid` | 0x1c20c1 | 24 |
| `tcsendbreak` | 0x1c20d9 | 10 |
| `tcsetattr` | 0x1c20e3 | 50 |
| `tcgetpgrp` | 0x1c2115 | 24 |
| `tcsetpgrp` | 0x1c212d | 22 |
| `_thread_atexit_lock` | 0x1c2145 | 12 |
| `_thread_atexit_unlock` | 0x1c2151 | 12 |
| `_thread_arc4_lock` | 0x1c215d | 12 |
| `_thread_arc4_unlock` | 0x1c2169 | 12 |
| `_Z16__libc_init_vdsov` | 0x1c2175 | 2 |
| `mbsinit` | 0x1c2177 | 18 |
| `mbrtowc` | 0x1c2189 | 16 |
| `mbsnrtowcs` | 0x1c2199 | 264 |
| `mbsrtowcs` | 0x1c22a1 | 20 |
| `wcrtomb` | 0x1c22b5 | 16 |
| `wcsnrtombs` | 0x1c22c5 | 256 |
| `wcsrtombs` | 0x1c23c5 | 20 |
| `wcscoll_l` | 0x1c23d9 | 4 |
| `wcsxfrm_l` | 0x1c23dd | 4 |
| `wcstoll_l` | 0x1c23e1 | 4 |
| `wcstoull_l` | 0x1c23e5 | 4 |
| `wcstold_l` | 0x1c23e9 | 4 |
| `iswalnum` | 0x1c23ed | 4 |
| `iswalpha` | 0x1c23f1 | 4 |
| `iswblank` | 0x1c23f5 | 4 |
| `iswcntrl` | 0x1c23f9 | 4 |
| `iswdigit` | 0x1c23fd | 12 |
| `iswgraph` | 0x1c2409 | 4 |
| `iswlower` | 0x1c240d | 4 |
| `iswprint` | 0x1c2411 | 4 |
| `iswpunct` | 0x1c2415 | 4 |
| `iswspace` | 0x1c2419 | 4 |
| `iswupper` | 0x1c241d | 4 |
| `iswxdigit` | 0x1c2421 | 4 |
| `iswalnum_l` | 0x1c2425 | 4 |
| `iswalpha_l` | 0x1c2429 | 4 |
| `iswblank_l` | 0x1c242d | 4 |
| `iswcntrl_l` | 0x1c2431 | 4 |
| `iswdigit_l` | 0x1c2435 | 4 |
| `iswgraph_l` | 0x1c2439 | 4 |
| `iswlower_l` | 0x1c243d | 4 |
| `iswprint_l` | 0x1c2441 | 4 |
| `iswpunct_l` | 0x1c2445 | 4 |
| `iswspace_l` | 0x1c2449 | 4 |
| `iswupper_l` | 0x1c244d | 4 |
| `iswxdigit_l` | 0x1c2451 | 4 |
| `iswctype` | 0x1c2455 | 74 |
| `iswctype_l` | 0x1c249f | 4 |
| `towlower` | 0x1c24a3 | 4 |
| `towupper` | 0x1c24a7 | 4 |
| `towupper_l` | 0x1c24ab | 4 |
| `towlower_l` | 0x1c24af | 4 |
| `wctype` | 0x1c24b5 | 40 |
| `wctype_l` | 0x1c24dd | 4 |
| `wcwidth` | 0x1c24e1 | 8 |
| `__strcpy_chk` | 0x1c24e9 | 52 |
| `_Znwj` | 0x1c251d | 36 |
| `_Znaj` | 0x1c2541 | 36 |
| `_ZdlPv` | 0x1c2565 | 4 |
| `_ZdaPv` | 0x1c2569 | 4 |
| `_ZnwjRKSt9nothrow_t` | 0x1c256d | 4 |
| `_ZnajRKSt9nothrow_t` | 0x1c2571 | 4 |
| `_ZdlPvRKSt9nothrow_t` | 0x1c2575 | 4 |
| `_ZdaPvRKSt9nothrow_t` | 0x1c2579 | 4 |
| `__sflags` | 0x1c257d | 114 |
| `swapfunc` | 0x1c25ef | 48 |
| `med3.isra.1` | 0x1c261f | 68 |
| `qsort` | 0x1c2663 | 624 |
| `__rv_alloc_D2A` | 0x1c28d3 | 34 |
| `__nrv_alloc_D2A` | 0x1c28f5 | 36 |
| `__freedtoa` | 0x1c2919 | 20 |
| `__quorem_D2A` | 0x1c292d | 330 |
| `__dtoa` | 0x1c2a79 | 2616 |
| `__hdtoa` | 0x1c34b1 | 420 |
| `__hldtoa` | 0x1c3659 | 10 |
| `__ldtoa` | 0x1c3663 | 52 |
| `__Balloc_D2A` | 0x1c3699 | 148 |
| `__Bfree_D2A` | 0x1c372d | 76 |
| `__lo0bits_D2A` | 0x1c3779 | 90 |
| `__multadd_D2A` | 0x1c37d3 | 134 |
| `__hi0bits_D2A` | 0x1c3859 | 64 |
| `__i2b_D2A` | 0x1c3899 | 20 |
| `__mult_D2A` | 0x1c38ad | 216 |
| `__pow5mult_D2A` | 0x1c3985 | 216 |
| `__lshift_D2A` | 0x1c3a5d | 162 |
| `__cmp_D2A` | 0x1c3aff | 62 |
| `__diff_D2A` | 0x1c3b3d | 216 |
| `__b2d_D2A` | 0x1c3c15 | 170 |
| `__d2b_D2A` | 0x1c3cbf | 164 |
| `strcp_D2A` | 0x1c3d63 | 18 |
| `__sulp_D2A` | 0x1c3d75 | 52 |
| `strtod` | 0x1c3da9 | 2876 |
| `strtof` | 0x1c48e9 | 104 |
| `__ULtod_D2A` | 0x1c4951 | 108 |
| `__strtord` | 0x1c49bd | 84 |
| `__ulp_D2A` | 0x1c4a11 | 64 |
| `je_memalign_round_up_boundary` | 0x1c4a51 | 32 |
| `je_pvalloc` | 0x1c4a71 | 34 |
| `wcscoll` | 0x1c4a93 | 4 |
| `wcstold` | 0x1c4a99 | 456 |
| `wcstoll` | 0x1c4c61 | 484 |
| `wcstoull` | 0x1c4e45 | 372 |
| `wcsxfrm` | 0x1c4fb9 | 12 |
| `wctob` | 0x1c4fc5 | 40 |
| `ungetc` | 0x1c4fed | 324 |
| `__findenv` | 0x1c5131 | 108 |
| `getenv` | 0x1c519d | 36 |
| `wcslcpy` | 0x1c51c1 | 42 |
| `__set_tls` | 0x1c51ec | 32 |
| `prlimit64` | 0x1c5210 | 32 |
| `sigaltstack` | 0x1c5234 | 32 |
| `pread64` | 0x1c5254 | 40 |
| `__ioctl` | 0x1c527c | 32 |
| `__fcntl64` | 0x1c529c | 32 |
| `tgkill` | 0x1c52bc | 32 |
| `__connect` | 0x1c52dc | 32 |
| `__llseek` | 0x1c5300 | 40 |
| `__accept4` | 0x1c5328 | 32 |
| `getrlimit` | 0x1c534c | 32 |
| `ftruncate` | 0x1c536c | 32 |
| `pwrite64` | 0x1c538c | 40 |
| `__fstatfs64` | 0x1c53b4 | 32 |
| `fallocate64` | 0x1c53d8 | 40 |
| `__socket` | 0x1c5400 | 32 |
| `__set_tid_address` | 0x1c5424 | 32 |
| `__statfs64` | 0x1c5444 | 32 |
| `__exit` | 0x1c5468 | 32 |
| `asctime_r` | 0x1c5489 | 292 |
| `asctime` | 0x1c55ad | 12 |
| `je_arenas_tsd_cleanup_wrapper` | 0x1c55b9 | 112 |
| `je_thread_allocated_tsd_cleanup_wrapper` | 0x1c5629 | 4 |
| `je_arenas_cleanup` | 0x1c562d | 36 |
| `malloc_conf_error` | 0x1c5651 | 32 |
| `je_set_errno` | 0x1c5671 | 12 |
| `stats_print_atexit` | 0x1c56b9 | 120 |
| `je_jemalloc_prefork` | 0x1c5731 | 80 |
| `je_jemalloc_postfork_parent` | 0x1c5781 | 80 |
| `je_jemalloc_postfork_child` | 0x1c57d1 | 80 |
| `ifree` | 0x1c5821 | 796 |
| `malloc_conf_init` | 0x1c5b3d | 1620 |
| `je_arenas_extend` | 0x1c6191 | 84 |
| `malloc_init_hard` | 0x1c61e5 | 656 |
| `je_choose_arena_hard` | 0x1c6475 | 316 |
| `imemalign` | 0x1c6635 | 1264 |
| `a0alloc` | 0x1c6b25 | 260 |
| `je_malloc` | 0x1c6c29 | 1124 |
| `je_posix_memalign` | 0x1c708d | 6 |
| `je_aligned_alloc` | 0x1c7093 | 34 |
| `je_calloc` | 0x1c70b5 | 1092 |
| `je_realloc` | 0x1c74f9 | 1556 |
| `je_free` | 0x1c7b0d | 8 |
| `je_memalign` | 0x1c7b15 | 28 |
| `je_valloc` | 0x1c7b31 | 30 |
| `je_mallocx` | 0x1c7b51 | 2588 |
| `je_rallocx` | 0x1c856d | 2360 |
| `je_xallocx` | 0x1c8ea5 | 660 |
| `je_sallocx` | 0x1c9139 | 236 |
| `je_dallocx` | 0x1c9225 | 876 |
| `je_nallocx` | 0x1c9591 | 412 |
| `je_mallctl` | 0x1c972d | 200 |
| `je_mallctlnametomib` | 0x1c97f5 | 196 |
| `je_mallctlbymib` | 0x1c98b9 | 204 |
| `je_malloc_stats_print` | 0x1c9985 | 4 |
| `je_malloc_usable_size` | 0x1c9989 | 244 |
| `je_a0malloc` | 0x1c9a7d | 6 |
| `je_a0calloc` | 0x1c9a83 | 8 |
| `je_a0free` | 0x1c9a8d | 100 |
| `je_malloc_mutex_init` | 0x1c9af1 | 56 |
| `je_malloc_mutex_prefork` | 0x1c9b29 | 4 |
| `je_malloc_mutex_postfork_parent` | 0x1c9b2d | 4 |
| `je_malloc_mutex_postfork_child` | 0x1c9b31 | 48 |
| `je_mutex_boot` | 0x1c9b61 | 4 |
| `prof_dump_filename` | 0x1c9b89 | 156 |
| `prof_dump_flush` | 0x1c9c25 | 100 |
| `prof_dump_write` | 0x1c9c89 | 140 |
| `prof_dump_printf` | 0x1c9d15 | 76 |
| `prof_dump_maps` | 0x1c9d61 | 224 |
| `prof_bt_keycomp` | 0x1c9e41 | 34 |
| `je_prof_tdata_tsd_get_wrapper` | 0x1c9e65 | 116 |
| `je_prof_tdata_tsd_set` | 0x1c9ed9 | 48 |
| `prof_bt_hash` | 0x1c9f09 | 628 |
| `je_choose_arena.constprop.10` | 0x1ca17d | 136 |
| `je_bt_init` | 0x1ca205 | 8 |
| `je_prof_backtrace` | 0x1ca20d | 2 |
| `je_prof_sample_threshold_update` | 0x1ca20f | 2 |
| `je_prof_tdata_init` | 0x1ca211 | 1832 |
| `prof_dump` | 0x1ca939 | 1116 |
| `je_prof_gdump` | 0x1cad95 | 180 |
| `je_prof_idump` | 0x1cae49 | 180 |
| `prof_leave` | 0x1caefd | 56 |
| `prof_ctx_destroy` | 0x1caf35 | 1220 |
| `prof_ctx_merge` | 0x1cb3f9 | 184 |
| `je_prof_tdata_cleanup` | 0x1cb4b1 | 1784 |
| `je_prof_tdata_tsd_cleanup_wrapper` | 0x1cbba9 | 112 |
| `je_prof_mdump` | 0x1cbc19 | 172 |
| `prof_fdump.part.6` | 0x1cbcc5 | 144 |
| `prof_fdump` | 0x1cbd55 | 20 |
| `je_prof_lookup` | 0x1cbd69 | 4092 |
| `je_prof_boot0` | 0x1ccd65 | 16 |
| `je_prof_boot1` | 0x1ccd75 | 92 |
| `je_prof_boot2` | 0x1ccdd1 | 260 |
| `je_prof_prefork` | 0x1cced5 | 68 |
| `je_prof_postfork_parent` | 0x1ccf19 | 72 |
| `je_prof_postfork_child` | 0x1ccf61 | 72 |
| `je_quarantine_tsd_cleanup_wrapper` | 0x1ccfa9 | 112 |
| `quarantine_drain_one` | 0x1cd019 | 664 |
| `je_choose_arena.constprop.5` | 0x1cd2b1 | 136 |
| `je_quarantine_cleanup` | 0x1cd339 | 864 |
| `je_quarantine_init` | 0x1cd699 | 840 |
| `je_quarantine` | 0x1cd9e1 | 1948 |
| `je_quarantine_boot` | 0x1ce17d | 44 |
| `stats_arena_print` | 0x1ce1a9 | 4452 |
| `je_stats_print` | 0x1cf30d | 3508 |
| `je_tcache_tsd_cleanup_wrapper` | 0x1d00c1 | 112 |
| `je_tcache_enabled_tsd_cleanup_wrapper` | 0x1d0131 | 4 |
| `je_tcache_salloc` | 0x1d01c1 | 88 |
| `je_tcache_alloc_small_hard` | 0x1d0219 | 52 |
| `je_tcache_bin_flush_small` | 0x1d024d | 408 |
| `je_tcache_bin_flush_large` | 0x1d03e5 | 328 |
| `je_tcache_event_hard` | 0x1d052d | 128 |
| `je_tcache_arena_associate` | 0x1d05ad | 52 |
| `je_tcache_create` | 0x1d05e1 | 348 |
| `je_tcache_stats_merge` | 0x1d073d | 168 |
| `je_tcache_arena_dissociate` | 0x1d07e5 | 76 |
| `je_tcache_destroy` | 0x1d0831 | 400 |
| `je_tcache_thread_cleanup` | 0x1d09c1 | 292 |
| `je_tcache_get_hard` | 0x1d0ae5 | 732 |
| `je_tcache_boot0` | 0x1d0dc1 | 296 |
| `je_tcache_boot1` | 0x1d0ee9 | 76 |
| `je_malloc_tsd_dalloc` | 0x1d0f35 | 96 |
| `je_malloc_tsd_no_cleanup` | 0x1d0f95 | 2 |
| `je_malloc_tsd_cleanup_register` | 0x1d0f99 | 28 |
| `je_malloc_tsd_boot` | 0x1d0fb5 | 16 |
| `je_tsd_init_check_recursion` | 0x1d0fc5 | 94 |
| `je_tsd_init_finish` | 0x1d1023 | 62 |
| `je_malloc_tsd_malloc` | 0x1d10ed | 64 |
| `u2s` | 0x1d112d | 244 |
| `wrtmessage` | 0x1d1221 | 26 |
| `je_malloc_write` | 0x1d123d | 32 |
| `je_buferror` | 0x1d125d | 4 |
| `je_malloc_strtoumax` | 0x1d1261 | 414 |
| `je_malloc_vsnprintf` | 0x1d1401 | 1778 |
| `je_malloc_snprintf` | 0x1d1af5 | 26 |
| `je_malloc_vcprintf` | 0x1d1b11 | 112 |
| `je_malloc_cprintf` | 0x1d1b81 | 26 |
| `je_malloc_printf` | 0x1d1b9b | 30 |
| `je_mallinfo` | 0x1d1bb9 | 240 |
| `__strchr_chk` | 0x1d1ca9 | 48 |
| `__vsprintf_chk` | 0x1d1cd9 | 36 |
| `__sprintf_chk` | 0x1d1cfd | 30 |
| `__system_property_find_compat` | 0x1d1d1d | 88 |
| `__system_property_read_compat` | 0x1d1d75 | 100 |
| `__system_property_foreach_compat` | 0x1d1dd9 | 56 |
| `wcschr` | 0x1d1e11 | 26 |
| `wcscmp` | 0x1d1e2b | 26 |
| `wcslen` | 0x1d1e45 | 18 |
| `_exit_with_stack_teardown` | 0x1d1e58 | 20 |
| `c32rtomb` | 0x1d1e6d | 160 |
| `__start_thread` | 0x1d1f0d | 12 |
| `clone` | 0x1d1f19 | 108 |
| `__fpclassify` | 0x1d1f85 | 62 |
| `__fpclassifyd` | 0x1d1f85 | 62 |
| `__fpclassifyl` | 0x1d1f85 | 62 |
| `__fpclassifyf` | 0x1d1fc3 | 48 |
| `__isinf` | 0x1d1ff3 | 14 |
| `__isinfl` | 0x1d1ff3 | 14 |
| `isinf` | 0x1d1ff3 | 14 |
| `isinfl` | 0x1d1ff3 | 14 |
| `__isinff` | 0x1d2001 | 14 |
| `isinff` | 0x1d2001 | 14 |
| `__isnan` | 0x1d200f | 14 |
| `__isnanl` | 0x1d200f | 14 |
| `isnan` | 0x1d200f | 14 |
| `isnanl` | 0x1d200f | 14 |
| `__isnanf` | 0x1d201d | 20 |
| `isnanf` | 0x1d201d | 20 |
| `__isfinite` | 0x1d2031 | 18 |
| `__isfinitel` | 0x1d2031 | 18 |
| `isfinite` | 0x1d2031 | 18 |
| `isfinitel` | 0x1d2031 | 18 |
| `__isfinitef` | 0x1d2043 | 18 |
| `isfinitef` | 0x1d2043 | 18 |
| `__isnormal` | 0x1d2055 | 14 |
| `__isnormall` | 0x1d2055 | 14 |
| `isnormal` | 0x1d2055 | 14 |
| `isnormall` | 0x1d2055 | 14 |
| `__isnormalf` | 0x1d2063 | 14 |
| `isnormalf` | 0x1d2063 | 14 |
| `mbrtoc32` | 0x1d2071 | 372 |
| `mbstate_bytes_so_far` | 0x1d21e5 | 26 |
| `mbstate_set_byte` | 0x1d21ff | 4 |
| `mbstate_get_byte` | 0x1d2203 | 4 |
| `reset_and_return_illegal` | 0x1d2207 | 22 |
| `reset_and_return` | 0x1d221d | 6 |
| `send` | 0x1d2223 | 16 |
| `_ZL13__get_meminfoPKc` | 0x1d2235 | 136 |
| `_ZL26__sysconf_nprocessors_onlnv` | 0x1d22bd | 152 |
| `sysconf` | 0x1d2355 | 376 |
| `wcsncasecmp` | 0x1d24cd | 66 |
| `wcsspn` | 0x1d250f | 34 |
| `__gethex_D2A` | 0x1d2531 | 1216 |
| `__rshift_D2A` | 0x1d29f1 | 108 |
| `__trailz_D2A` | 0x1d2a5d | 46 |
| `htinit.constprop.0` | 0x1d2a8d | 28 |
| `hexdig_init_D2A` | 0x1d2aa9 | 48 |
| `L_shift` | 0x1d2ad9 | 44 |
| `__hexnan_D2A` | 0x1d2b05 | 416 |
| `__s2b_D2A` | 0x1d2ca5 | 144 |
| `__ratio_D2A` | 0x1d2d35 | 88 |
| `__match_D2A` | 0x1d2d8d | 44 |
| `__copybits_D2A` | 0x1d2db9 | 50 |
| `__any_on_D2A` | 0x1d2deb | 72 |
| `__increment_D2A` | 0x1d2e33 | 106 |
| `rvOK` | 0x1d2e9d | 478 |
| `__decrement_D2A` | 0x1d307b | 40 |
| `__set_ones_D2A` | 0x1d30a3 | 88 |
| `__strtodg` | 0x1d3101 | 3784 |
| `__sum_D2A` | 0x1d3fc9 | 218 |
| `vsnprintf` | 0x1d40a3 | 100 |
| `sendto` | 0x1d4108 | 40 |
| `clock_getres` | 0x1d4134 | 32 |
| `arena_mapelm_to_pageind` | 0x1d4155 | 48 |
| `arena_run_tree_insert` | 0x1d4185 | 286 |
| `arena_run_tree_remove` | 0x1d42a3 | 944 |
| `arena_avail_comp` | 0x1d4653 | 64 |
| `arena_avail_tree_nsearch` | 0x1d4693 | 58 |
| `arena_avail_tree_insert` | 0x1d46cd | 286 |
| `arena_avail_tree_remove` | 0x1d47eb | 908 |
| `arena_chunk_dirty_comp` | 0x1d4b77 | 62 |
| `arena_chunk_dirty_insert` | 0x1d4bb5 | 290 |
| `arena_chunk_dirty_remove` | 0x1d4cd7 | 872 |
| `arena_avail_adjac_pred` | 0x1d5041 | 52 |
| `arena_bin_runs_first` | 0x1d5075 | 88 |
| `arena_bin_runs_insert` | 0x1d50cd | 64 |
| `arena_bin_runs_remove` | 0x1d510d | 64 |
| `arena_run_reg_alloc` | 0x1d514d | 208 |
| `bin_info_run_size_calc` | 0x1d5259 | 292 |
| `arena_bin_lower_run.isra.7` | 0x1d537d | 52 |
| `je_choose_arena` | 0x1d53b1 | 140 |
| `je_arena_alloc_junk_small.part.10` | 0x1d543d | 34 |
| `arena_cactive_update` | 0x1d5461 | 84 |
| `arena_avail_insert` | 0x1d54b5 | 200 |
| `arena_chunk_alloc` | 0x1d557d | 288 |
| `arena_avail_remove` | 0x1d569d | 204 |
| `arena_run_split_remove` | 0x1d5769 | 232 |
| `arena_run_split_large_helper` | 0x1d5851 | 224 |
| `arena_run_split_small` | 0x1d5931 | 208 |
| `arena_run_alloc_small_helper` | 0x1d5a01 | 72 |
| `arena_run_alloc_large_helper` | 0x1d5a49 | 80 |
| `arena_run_alloc_large.part.8` | 0x1d5a99 | 80 |
| `arena_purge` | 0x1d5ae9 | 700 |
| `arena_run_dalloc` | 0x1d5da5 | 756 |
| `arena_run_trim_tail` | 0x1d6099 | 168 |
| `arena_dalloc_bin_run` | 0x1d6141 | 300 |
| `arena_redzones_validate` | 0x1d626d | 256 |
| `arena_bin_malloc_hard` | 0x1d636d | 364 |
| `je_arena_chunk_alloc_huge` | 0x1d64d9 | 212 |
| `je_arena_chunk_dalloc_huge` | 0x1d65ad | 124 |
| `je_arena_purge_all` | 0x1d6629 | 32 |
| `je_arena_tcache_fill_small` | 0x1d6649 | 268 |
| `je_arena_alloc_junk_small` | 0x1d6755 | 32 |
| `je_arena_dalloc_junk_small` | 0x1d6775 | 28 |
| `je_arena_quarantine_junk_small` | 0x1d6791 | 60 |
| `je_arena_malloc_small` | 0x1d67cd | 272 |
| `je_arena_malloc_large` | 0x1d68dd | 236 |
| `je_arena_palloc` | 0x1d69c9 | 484 |
| `je_arena_prof_promoted` | 0x1d6bad | 96 |
| `je_arena_dalloc_bin_locked` | 0x1d6c0d | 460 |
| `je_arena_dalloc_bin` | 0x1d6dd9 | 80 |
| `je_arena_dalloc_small` | 0x1d6e29 | 44 |
| `je_arena_dalloc_large_locked` | 0x1d6e55 | 148 |
| `je_arena_dalloc_large` | 0x1d6ee9 | 38 |
| `je_arena_ralloc_no_move` | 0x1d6f11 | 984 |
| `je_arena_ralloc` | 0x1d72e9 | 3684 |
| `je_arena_dss_prec_get` | 0x1d814d | 28 |
| `je_arena_dss_prec_set` | 0x1d8169 | 30 |
| `je_arena_stats_merge` | 0x1d8189 | 600 |
| `je_arena_new` | 0x1d83e1 | 264 |
| `je_arena_boot` | 0x1d84e9 | 1064 |
| `je_arena_prefork` | 0x1d8911 | 30 |
| `je_arena_postfork_parent` | 0x1d892f | 36 |
| `je_arena_postfork_child` | 0x1d8953 | 36 |
| `je_base_alloc` | 0x1d8979 | 144 |
| `je_base_calloc` | 0x1d8a09 | 28 |
| `je_base_node_alloc` | 0x1d8a25 | 60 |
| `je_base_node_dalloc` | 0x1d8a61 | 44 |
| `je_base_boot` | 0x1d8a8d | 24 |
| `je_base_prefork` | 0x1d8aa5 | 12 |
| `je_base_postfork_parent` | 0x1d8ab1 | 12 |
| `je_base_postfork_child` | 0x1d8abd | 12 |
| `je_bitmap_info_init` | 0x1d8ac9 | 80 |
| `je_bitmap_info_ngroups` | 0x1d8b19 | 12 |
| `je_bitmap_size` | 0x1d8b25 | 32 |
| `je_bitmap_init` | 0x1d8b45 | 106 |
| `chunk_record` | 0x1d8bb1 | 288 |
| `chunk_register.isra.0` | 0x1d8cd1 | 84 |
| `je_chunk_alloc_arena` | 0x1d8d25 | 46 |
| `je_chunk_unmap` | 0x1d8d55 | 72 |
| `chunk_dalloc_core` | 0x1d8d9d | 68 |
| `chunk_recycle` | 0x1d8de1 | 304 |
| `chunk_alloc_core` | 0x1d8f11 | 172 |
| `je_chunk_alloc_default` | 0x1d8fbd | 44 |
| `je_chunk_alloc_base` | 0x1d8fe9 | 72 |
| `je_chunk_dalloc_default` | 0x1d9031 | 10 |
| `je_chunk_boot` | 0x1d903d | 148 |
| `je_chunk_prefork` | 0x1d90d1 | 24 |
| `je_chunk_postfork_parent` | 0x1d90e9 | 24 |
| `je_chunk_postfork_child` | 0x1d9101 | 24 |
| `je_chunk_dss_prec_get` | 0x1d9119 | 36 |
| `je_chunk_dss_prec_set` | 0x1d913d | 40 |
| `je_chunk_alloc_dss` | 0x1d9165 | 248 |
| `je_chunk_in_dss` | 0x1d925d | 68 |
| `je_chunk_dss_boot` | 0x1d92a1 | 56 |
| `je_chunk_dss_prefork` | 0x1d92d9 | 12 |
| `je_chunk_dss_postfork_parent` | 0x1d92e5 | 12 |
| `je_chunk_dss_postfork_child` | 0x1d92f1 | 12 |
| `pages_map.constprop.1` | 0x1d92fd | 72 |
| `pages_unmap` | 0x1d9345 | 96 |
| `je_pages_purge` | 0x1d93a5 | 16 |
| `je_chunk_alloc_mmap` | 0x1d93b5 | 112 |
| `je_chunk_dalloc_mmap` | 0x1d9425 | 10 |
| `je_hash_fmix_32` | 0x1d9431 | 36 |
| `je_hash_x86_128` | 0x1d9455 | 624 |
| `je_ckh_bucket_search` | 0x1d96c5 | 56 |
| `je_ckh_isearch` | 0x1d96fd | 70 |
| `je_ckh_try_bucket_insert` | 0x1d9745 | 80 |
| `je_ckh_try_insert` | 0x1d9795 | 240 |
| `je_ckh_rebuild` | 0x1d9885 | 70 |
| `je_choose_arena.constprop.3` | 0x1d9909 | 136 |
| `je_ckh_new` | 0x1d9991 | 884 |
| `je_ckh_delete` | 0x1d9d05 | 568 |
| `je_ckh_count` | 0x1d9f3d | 4 |
| `je_ckh_iter` | 0x1d9f41 | 58 |
| `je_ckh_insert` | 0x1d9f7d | 1988 |
| `je_ckh_remove` | 0x1da741 | 2012 |
| `je_ckh_search` | 0x1daf1d | 46 |
| `je_ckh_string_hash` | 0x1daf4d | 40 |
| `je_ckh_string_keycomp` | 0x1daf75 | 16 |
| `je_ckh_pointer_hash` | 0x1daf85 | 40 |
| `je_ckh_pointer_keycomp` | 0x1dafad | 8 |
| `opt_utrace_ctl` | 0x1dafb5 | 4 |
| `opt_xmalloc_ctl` | 0x1dafb9 | 4 |
| `opt_prof_ctl` | 0x1dafbd | 4 |
| `opt_prof_prefix_ctl` | 0x1dafc1 | 4 |
| `opt_prof_active_ctl` | 0x1dafc5 | 4 |
| `opt_lg_prof_sample_ctl` | 0x1dafc9 | 4 |
| `opt_prof_accum_ctl` | 0x1dafcd | 4 |
| `opt_lg_prof_interval_ctl` | 0x1dafd1 | 4 |
| `opt_prof_gdump_ctl` | 0x1dafd5 | 4 |
| `opt_prof_final_ctl` | 0x1dafd9 | 4 |
| `opt_prof_leak_ctl` | 0x1dafdd | 4 |
| `arenas_bin_i_index` | 0x1dafe1 | 20 |
| `arenas_lrun_i_index` | 0x1daff5 | 52 |
| `prof_active_ctl` | 0x1db029 | 4 |
| `prof_dump_ctl` | 0x1db02d | 4 |
| `prof_interval_ctl` | 0x1db031 | 4 |
| `stats_arenas_i_bins_j_index` | 0x1db035 | 20 |
| `stats_arenas_i_lruns_j_index` | 0x1db049 | 52 |
| `ctl_arena_clear` | 0x1db07d | 120 |
| `ctl_refresh` | 0x1db0f5 | 1168 |
| `stats_arenas_i_index` | 0x1db585 | 76 |
| `stats_arenas_i_lruns_j_curruns_ctl` | 0x1db5d1 | 120 |
| `stats_arenas_i_lruns_j_nrequests_ctl` | 0x1db649 | 140 |
| `stats_arenas_i_lruns_j_ndalloc_ctl` | 0x1db6d5 | 140 |
| `stats_arenas_i_lruns_j_nmalloc_ctl` | 0x1db761 | 140 |
| `stats_arenas_i_bins_j_curruns_ctl` | 0x1db7ed | 120 |
| `stats_arenas_i_bins_j_nreruns_ctl` | 0x1db865 | 136 |
| `stats_arenas_i_bins_j_nruns_ctl` | 0x1db8ed | 136 |
| `stats_arenas_i_bins_j_nflushes_ctl` | 0x1db975 | 136 |
| `stats_arenas_i_bins_j_nfills_ctl` | 0x1db9fd | 136 |
| `stats_arenas_i_bins_j_nrequests_ctl` | 0x1dba85 | 136 |
| `stats_arenas_i_bins_j_ndalloc_ctl` | 0x1dbb0d | 136 |
| `stats_arenas_i_bins_j_nmalloc_ctl` | 0x1dbb95 | 136 |
| `stats_arenas_i_bins_j_allocated_ctl` | 0x1dbc1d | 120 |
| `stats_arenas_i_huge_nrequests_ctl` | 0x1dbc95 | 128 |
| `stats_arenas_i_huge_ndalloc_ctl` | 0x1dbd15 | 128 |
| `stats_arenas_i_huge_nmalloc_ctl` | 0x1dbd95 | 128 |
| `stats_arenas_i_huge_allocated_ctl` | 0x1dbe15 | 112 |
| `stats_arenas_i_large_nrequests_ctl` | 0x1dbe85 | 128 |
| `stats_arenas_i_large_ndalloc_ctl` | 0x1dbf05 | 128 |
| `stats_arenas_i_large_nmalloc_ctl` | 0x1dbf85 | 128 |
| `stats_arenas_i_large_allocated_ctl` | 0x1dc005 | 112 |
| `stats_arenas_i_small_nrequests_ctl` | 0x1dc075 | 128 |
| `stats_arenas_i_small_ndalloc_ctl` | 0x1dc0f5 | 128 |
| `stats_arenas_i_small_nmalloc_ctl` | 0x1dc175 | 128 |
| `stats_arenas_i_small_allocated_ctl` | 0x1dc1f5 | 112 |
| `stats_arenas_i_purged_ctl` | 0x1dc265 | 128 |
| `stats_arenas_i_nmadvise_ctl` | 0x1dc2e5 | 128 |
| `stats_arenas_i_npurge_ctl` | 0x1dc365 | 128 |
| `stats_arenas_i_mapped_ctl` | 0x1dc3e5 | 112 |
| `stats_arenas_i_pdirty_ctl` | 0x1dc455 | 112 |
| `stats_arenas_i_pactive_ctl` | 0x1dc4c5 | 112 |
| `stats_arenas_i_dss_ctl` | 0x1dc535 | 112 |
| `stats_arenas_i_nthreads_ctl` | 0x1dc5a5 | 112 |
| `stats_chunks_high_ctl` | 0x1dc615 | 96 |
| `stats_chunks_total_ctl` | 0x1dc675 | 116 |
| `stats_chunks_current_ctl` | 0x1dc6e9 | 96 |
| `stats_mapped_ctl` | 0x1dc749 | 96 |
| `stats_active_ctl` | 0x1dc7a9 | 96 |
| `stats_allocated_ctl` | 0x1dc809 | 96 |
| `stats_cactive_ctl` | 0x1dc869 | 104 |
| `arenas_initialized_ctl` | 0x1dc8d1 | 104 |
| `arenas_narenas_ctl` | 0x1dc939 | 72 |
| `arena_i_index` | 0x1dc981 | 60 |
| `arena_i_chunk_dalloc_ctl` | 0x1dc9bd | 160 |
| `arena_i_chunk_alloc_ctl` | 0x1dca5d | 160 |
| `epoch_ctl` | 0x1dcafd | 108 |
| `je_small_size2bin_compute` | 0x1dcb69 | 60 |
| `arena_i_dss_ctl` | 0x1dcba5 | 228 |
| `thread_tcache_enabled_ctl` | 0x1dcc89 | 756 |
| `ctl_lookup` | 0x1dcf7d | 312 |
| `version_ctl` | 0x1dd0b5 | 72 |
| `config_debug_ctl` | 0x1dd0fd | 66 |
| `config_fill_ctl` | 0x1dd13f | 64 |
| `config_lazy_lock_ctl` | 0x1dd17f | 66 |
| `config_munmap_ctl` | 0x1dd1c1 | 64 |
| `config_prof_ctl` | 0x1dd201 | 66 |
| `config_prof_libgcc_ctl` | 0x1dd243 | 66 |
| `config_prof_libunwind_ctl` | 0x1dd285 | 66 |
| `config_stats_ctl` | 0x1dd2c7 | 64 |
| `config_tcache_ctl` | 0x1dd307 | 64 |
| `config_tls_ctl` | 0x1dd347 | 66 |
| `config_utrace_ctl` | 0x1dd389 | 66 |
| `config_valgrind_ctl` | 0x1dd3cb | 66 |
| `config_xmalloc_ctl` | 0x1dd40d | 66 |
| `opt_abort_ctl` | 0x1dd451 | 84 |
| `opt_dss_ctl` | 0x1dd4a5 | 84 |
| `opt_lg_chunk_ctl` | 0x1dd4f9 | 84 |
| `opt_narenas_ctl` | 0x1dd54d | 84 |
| `opt_lg_dirty_mult_ctl` | 0x1dd5a1 | 84 |
| `opt_stats_print_ctl` | 0x1dd5f5 | 84 |
| `opt_junk_ctl` | 0x1dd649 | 84 |
| `opt_quarantine_ctl` | 0x1dd69d | 84 |
| `opt_redzone_ctl` | 0x1dd6f1 | 84 |
| `opt_zero_ctl` | 0x1dd745 | 84 |
| `opt_tcache_ctl` | 0x1dd799 | 84 |
| `opt_lg_tcache_max_ctl` | 0x1dd7ed | 84 |
| `thread_allocated_ctl` | 0x1dd841 | 212 |
| `thread_allocatedp_ctl` | 0x1dd915 | 208 |
| `thread_deallocated_ctl` | 0x1dd9e5 | 212 |
| `thread_deallocatedp_ctl` | 0x1ddab9 | 208 |
| `arenas_quantum_ctl` | 0x1ddb89 | 64 |
| `arenas_page_ctl` | 0x1ddbc9 | 66 |
| `arenas_tcache_max_ctl` | 0x1ddc0d | 84 |
| `arenas_nbins_ctl` | 0x1ddc61 | 64 |
| `arenas_nhbins_ctl` | 0x1ddca1 | 84 |
| `arenas_bin_i_size_ctl` | 0x1ddcf5 | 88 |
| `arenas_bin_i_nregs_ctl` | 0x1ddd4d | 92 |
| `arenas_bin_i_run_size_ctl` | 0x1ddda9 | 92 |
| `arenas_nlruns_ctl` | 0x1dde05 | 96 |
| `arenas_lrun_i_size_ctl` | 0x1dde65 | 68 |
| `ctl_arena_init.isra.43.part.44` | 0x1ddea9 | 52 |
| `arena_i_purge_ctl` | 0x1ddedd | 200 |
| `thread_tcache_flush_ctl` | 0x1ddfa5 | 272 |
| `je_choose_arena.constprop.48` | 0x1de0b5 | 136 |
| `thread_arena_ctl` | 0x1de13d | 516 |
| `ctl_grow` | 0x1de341 | 3736 |
| `arenas_extend_ctl` | 0x1df1d9 | 108 |
| `ctl_init` | 0x1df245 | 188 |
| `je_ctl_byname` | 0x1df301 | 108 |
| `je_ctl_nametomib` | 0x1df36d | 48 |
| `je_ctl_bymib` | 0x1df39d | 136 |
| `je_ctl_boot` | 0x1df425 | 28 |
| `je_ctl_prefork` | 0x1df441 | 12 |
| `je_ctl_postfork_parent` | 0x1df44d | 12 |
| `je_ctl_postfork_child` | 0x1df459 | 12 |
| `extent_szad_comp` | 0x1df465 | 38 |
| `je_extent_tree_szad_new` | 0x1df48b | 14 |
| `je_extent_tree_szad_first` | 0x1df499 | 32 |
| `je_extent_tree_szad_last` | 0x1df4b9 | 36 |
| `je_extent_tree_szad_next` | 0x1df4dd | 66 |
| `je_extent_tree_szad_prev` | 0x1df51f | 66 |
| `je_extent_tree_szad_search` | 0x1df561 | 44 |
| `je_extent_tree_szad_nsearch` | 0x1df58d | 58 |
| `je_extent_tree_szad_psearch` | 0x1df5c7 | 58 |
| `je_extent_tree_szad_insert` | 0x1df601 | 290 |
| `je_extent_tree_szad_remove` | 0x1df723 | 872 |
| `je_extent_tree_szad_iter_recurse` | 0x1dfa8b | 58 |
| `je_extent_tree_szad_iter_start` | 0x1dfac5 | 96 |
| `je_extent_tree_szad_iter` | 0x1dfb25 | 38 |
| `je_extent_tree_szad_reverse_iter_recurse` | 0x1dfb4b | 58 |
| `je_extent_tree_szad_reverse_iter_start` | 0x1dfb85 | 92 |
| `je_extent_tree_szad_reverse_iter` | 0x1dfbe1 | 38 |
| `je_extent_tree_ad_new` | 0x1dfc07 | 14 |
| `je_extent_tree_ad_first` | 0x1dfc15 | 32 |
| `je_extent_tree_ad_last` | 0x1dfc35 | 36 |
| `je_extent_tree_ad_next` | 0x1dfc59 | 76 |
| `je_extent_tree_ad_prev` | 0x1dfca5 | 76 |
| `je_extent_tree_ad_search` | 0x1dfcf1 | 50 |
| `je_extent_tree_ad_nsearch` | 0x1dfd23 | 64 |
| `je_extent_tree_ad_psearch` | 0x1dfd63 | 64 |
| `je_extent_tree_ad_insert` | 0x1dfda3 | 284 |
| `je_extent_tree_ad_remove` | 0x1dfebf | 876 |
| `je_extent_tree_ad_iter_recurse` | 0x1e022b | 58 |
| `je_extent_tree_ad_iter_start` | 0x1e0265 | 98 |
| `je_extent_tree_ad_iter` | 0x1e02c7 | 38 |
| `je_extent_tree_ad_reverse_iter_recurse` | 0x1e02ed | 58 |
| `je_extent_tree_ad_reverse_iter_start` | 0x1e0327 | 94 |
| `je_extent_tree_ad_reverse_iter` | 0x1e0385 | 38 |
| `je_huge_palloc` | 0x1e03ad | 332 |
| `je_huge_malloc` | 0x1e04f9 | 32 |
| `je_huge_ralloc_no_move` | 0x1e0519 | 76 |
| `je_huge_dalloc` | 0x1e0565 | 116 |
| `je_huge_ralloc` | 0x1e05d9 | 788 |
| `je_huge_salloc` | 0x1e08ed | 52 |
| `je_huge_prof_ctx_get` | 0x1e0921 | 52 |
| `je_huge_prof_ctx_set` | 0x1e0955 | 52 |
| `je_huge_boot` | 0x1e0989 | 36 |
| `je_huge_prefork` | 0x1e09ad | 12 |
| `je_huge_postfork_parent` | 0x1e09b9 | 12 |
| `je_huge_postfork_child` | 0x1e09c5 | 12 |
| `__bionic_clone` | 0x1e09d0 | 72 |
| `brk` | 0x1e0a19 | 48 |
| `sbrk` | 0x1e0a49 | 88 |
| `_ZL14__allocate_DIRi` | 0x1e0aa1 | 36 |
| `_ZL16__readdir_lockedP3DIR` | 0x1e0ac5 | 68 |
| `dirfd` | 0x1e0b09 | 4 |
| `fdopendir` | 0x1e0b0d | 52 |
| `opendir` | 0x1e0b41 | 26 |
| `readdir` | 0x1e0b5b | 32 |
| `readdir64` | 0x1e0b5b | 32 |
| `readdir64_r` | 0x1e0b7b | 92 |
| `readdir_r` | 0x1e0b7b | 92 |
| `closedir` | 0x1e0bd7 | 44 |
| `rewinddir` | 0x1e0c03 | 38 |
| `alphasort` | 0x1e0c29 | 12 |
| `alphasort64` | 0x1e0c29 | 12 |
| `strcoll` | 0x1e0c35 | 72 |
| `prctl` | 0x1e0c7c | 40 |
| `__brk` | 0x1e0ca4 | 32 |
| `__getdents64` | 0x1e0cc4 | 32 |
| `__aeabi_lasr` | 0x1e0ce4 | 28 |
| `__ashrdi3` | 0x1e0ce4 | 28 |
| `__aeabi_llsl` | 0x1e0d00 | 28 |
| `__ashldi3` | 0x1e0d00 | 28 |
| `__aeabi_ldivmod` | 0x1e0d1c | 0 |

</details>

**Removed objects (749)**

| Symbol | Addr | Size |
|---|---|---|
| `abitag` | 0x1e0de8 | 24 |
| `wlcntver6t_to_wlcntwlct` | 0x1e0f44 | 124 |
| `wlcntver7t_to_wlcntwlct` | 0x1e0fc0 | 149 |
| `wlcntver11t_to_wlcntwlct` | 0x1e1058 | 201 |
| `wlcntver11t_to_wlcntXX40mcstv1t` | 0x1e1124 | 64 |
| `wlcntver11t_to_wlcntvle10mcstt` | 0x1e1164 | 64 |
| `wlcntver6t_to_wlcntvle10mcstt` | 0x1e11a4 | 64 |
| `wlcntver7t_to_wlcntvle10mcstt` | 0x1e11e4 | 64 |
| `msb_table` | 0x1e131c | 256 |
| `AtanTbl` | 0x1e141c | 72 |
| `bcm_ctype` | 0x1e182c | 256 |
| `crc8_table` | 0x1e192c | 256 |
| `crc16_table` | 0x1e1a2c | 512 |
| `crc32_table` | 0x1e1c2c | 1024 |
| `hex.7500` | 0x1e2174 | 16 |
| `wf_chspec_bw_mhz` | 0x1e22c0 | 7 |
| `wf_5g_40m_chans` | 0x1e22c8 | 14 |
| `wf_5g_80m_chans` | 0x1e22d8 | 7 |
| `wf_5g_160m_chans` | 0x1e22e0 | 2 |
| `sidebands` | 0x1e2338 | 16 |
| `PADDING` | 0x1e2548 | 64 |
| `n_sha2_hash_impl_entries` | 0x1e274c | 4 |
| `sha1_Ka` | 0x1e2750 | 4 |
| `sha1_Kb` | 0x1e2754 | 4 |
| `sha1_Kc` | 0x1e2758 | 4 |
| `sha1_Kd` | 0x1e275c | 4 |
| `sha1_D` | 0x1e2760 | 20 |
| `sha256_K` | 0x1e2774 | 256 |
| `sha256_D` | 0x1e2874 | 32 |
| `kk` | 0x1e2998 | 640 |
| `sha512_224_init` | 0x1e2c18 | 64 |
| `sha512_256_init` | 0x1e2c58 | 64 |
| `sha384_init` | 0x1e2c98 | 64 |
| `sha512_init` | 0x1e2cd8 | 64 |
| `mcs_groups_nss1` | 0x1e2e18 | 64 |
| `he_mcs_groups_nss1` | 0x1e2e58 | 64 |
| `he_ru_mcs_groups_nss1` | 0x1e2e98 | 64 |
| `mcs_groups_nss1_txbf` | 0x1e2ed8 | 64 |
| `he_mcs_groups_nss1_txbf` | 0x1e2f18 | 64 |
| `he_ru_mcs_groups_nss1_txbf` | 0x1e2f58 | 64 |
| `mcs_groups_nss2` | 0x1e2f98 | 48 |
| `he_mcs_groups_nss2` | 0x1e2fc8 | 48 |
| `he_ru_mcs_groups_nss2` | 0x1e2ff8 | 48 |
| `mcs_groups_nss2_txbf` | 0x1e3028 | 48 |
| `he_mcs_groups_nss2_txbf` | 0x1e3058 | 48 |
| `he_ru_mcs_groups_nss2_txbf` | 0x1e3088 | 48 |
| `mcs_groups_nss3` | 0x1e30b8 | 32 |
| `he_mcs_groups_nss3` | 0x1e30d8 | 32 |
| `he_ru_mcs_groups_nss3` | 0x1e30f8 | 32 |
| `mcs_groups_nss3_txbf` | 0x1e3118 | 32 |

<details><summary>… 另 699 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `he_mcs_groups_nss3_txbf` | 0x1e3138 | 32 |
| `he_ru_mcs_groups_nss3_txbf` | 0x1e3158 | 32 |
| `mcs_groups_nss4` | 0x1e3178 | 16 |
| `he_mcs_groups_nss4` | 0x1e3188 | 16 |
| `he_ru_mcs_groups_nss4` | 0x1e3198 | 16 |
| `mcs_groups_nss4_txbf` | 0x1e31a8 | 16 |
| `he_mcs_groups_nss4_txbf` | 0x1e31b8 | 16 |
| `he_ru_mcs_groups_nss4_txbf` | 0x1e31c8 | 16 |
| `patrim_magic_string` | 0x1e6c64 | 4 |
| `ofdm_rates` | 0x1e6c68 | 8 |
| `wlu_mcs_info` | 0x1f9a14 | 30 |
| `nqdBm_to_mW_map` | 0x1fdc4c | 80 |
| `ac_names` | 0x1ff7b8 | 24 |
| `__FUNCTION__.26682` | 0x2044d4 | 15 |
| `__FUNCTION__.29013` | 0x204858 | 26 |
| `type_names.29150` | 0x204874 | 231 |
| `__FUNCTION__.30973` | 0x2049d4 | 21 |
| `__FUNCTION__.31958` | 0x2049ec | 30 |
| `__FUNCTION__.31977` | 0x204a0c | 30 |
| `__FUNCTION__.31996` | 0x204a2c | 30 |
| `__FUNCTION__.32372` | 0x204a4c | 20 |
| `__FUNCTION__.32424` | 0x204a60 | 18 |
| `wl_cmd_category_count` | 0x20677c | 4 |
| `__PRETTY_FUNCTION__.23553` | 0x213b48 | 17 |
| `__PRETTY_FUNCTION__.25069` | 0x213b5c | 12 |
| `__FUNCTION__.25079` | 0x213b68 | 12 |
| `__FUNCTION__.23345` | 0x21acd4 | 15 |
| `__FUNCTION__.23465` | 0x21ace4 | 19 |
| `wlu_wme_fifo2ac` | 0x21b874 | 6 |
| `wlu_prio2fifo` | 0x21b87c | 8 |
| `__FUNCTION__.23505` | 0x21cab8 | 21 |
| `__FUNCTION__.23476` | 0x21d144 | 18 |
| `__FUNCTION__.23327` | 0x21d9c0 | 12 |
| `otpcrc8_table` | 0x2292c8 | 256 |
| `MACFIFO_PLAY_DATA_CMD` | 0x231998 | 22 |
| `__FUNCTION__.23488` | 0x235894 | 19 |
| `__FUNCTION__.23615` | 0x238184 | 22 |
| `__FUNCTION__.23623` | 0x23819c | 14 |
| `ppr_group_table` | 0x242a40 | 2112 |
| `ppr_table` | 0x243280 | 13104 |
| `__FUNCTION__.23520` | 0x247f18 | 17 |
| `__FUNCTION__.23600` | 0x247f40 | 16 |
| `__FUNCTION__.23679` | 0x247f50 | 17 |
| `__FUNCTION__.23717` | 0x247f64 | 20 |
| `blob_magic_string` | 0x248378 | 4 |
| `__FUNCTION__.23496` | 0x24b838 | 13 |
| `__FUNCTION__.23514` | 0x24b848 | 19 |
| `__FUNCTION__.23730` | 0x24b85c | 20 |
| `__FUNCTION__.24536` | 0x24d138 | 17 |
| `__FUNCTION__.24568` | 0x24d14c | 21 |
| `hex.25643` | 0x257218 | 16 |
| `__FUNCTION__.26575` | 0x257228 | 23 |
| `__FUNCTION__.26626` | 0x257240 | 23 |
| `__FUNCTION__.26719` | 0x257258 | 26 |
| `__FUNCTION__.26734` | 0x257274 | 31 |
| `__FUNCTION__.26749` | 0x257294 | 29 |
| `__FUNCTION__.27077` | 0x2572b4 | 18 |
| `__FUNCTION__.27686` | 0x2572c8 | 26 |
| `__FUNCTION__.28134` | 0x2572e4 | 25 |
| `sdb_op_modes` | 0x25777c | 145 |
| `rsdb_band_names` | 0x257818 | 145 |
| `__FUNCTION__.23529` | 0x257ba4 | 13 |
| `__FUNCTION__.23541` | 0x257bb4 | 14 |
| `__FUNCTION__.23530` | 0x25815c | 30 |
| `__FUNCTION__.23522` | 0x258898 | 25 |
| `__FUNCTION__.23533` | 0x2588b4 | 25 |
| `llc_snap_hdr.24811` | 0x25c0b0 | 6 |
| `__FUNCTION__.26096` | 0x267278 | 24 |
| `__FUNCTION__.26429` | 0x267290 | 26 |
| `__FUNCTION__.26535` | 0x2672ac | 26 |
| `__FUNCTION__.26547` | 0x2672c8 | 36 |
| `__FUNCTION__.26631` | 0x2672ec | 24 |
| `__FUNCTION__.23693` | 0x268b24 | 30 |
| `__FUNCTION__.25493` | 0x26b2a4 | 12 |
| `__FUNCTION__.25510` | 0x26b2b0 | 26 |
| `__FUNCTION__.25529` | 0x26b2cc | 22 |
| `__FUNCTION__.26111` | 0x26b2e4 | 32 |
| `__FUNCTION__.24874` | 0x26ecfc | 29 |
| `__FUNCTION__.24901` | 0x26ed1c | 29 |
| `__FUNCTION__.24936` | 0x26ed3c | 27 |
| `__FUNCTION__.24958` | 0x26ed58 | 26 |
| `__FUNCTION__.24986` | 0x26ed74 | 26 |
| `__FUNCTION__.25018` | 0x26ed90 | 24 |
| `__FUNCTION__.25046` | 0x26eda8 | 28 |
| `__FUNCTION__.25066` | 0x26edc4 | 31 |
| `__FUNCTION__.25099` | 0x26ede4 | 21 |
| `__FUNCTION__.25119` | 0x26edfc | 30 |
| `__FUNCTION__.25135` | 0x26ee1c | 26 |
| `__FUNCTION__.25155` | 0x26ee38 | 29 |
| `__FUNCTION__.25200` | 0x26ee58 | 23 |
| `__FUNCTION__.23576` | 0x26f2f4 | 19 |
| `__FUNCTION__.23586` | 0x26f308 | 27 |
| `__FUNCTION__.23596` | 0x26f324 | 25 |
| `__FUNCTION__.23606` | 0x26f340 | 27 |
| `__FUNCTION__.23616` | 0x26f35c | 20 |
| `__FUNCTION__.23626` | 0x26f370 | 23 |
| `__FUNCTION__.23517` | 0x26f6e4 | 19 |
| `__FUNCTION__.23570` | 0x26f6f8 | 22 |
| `in6addr_any` | 0x27498c | 16 |
| `in6addr_loopback` | 0x27499c | 16 |
| `ether_bcast` | 0x2749ac | 6 |
| `ether_null` | 0x2749b4 | 6 |
| `ether_ipv6_mcast` | 0x2749bc | 6 |
| `all_node_ipv6_maddr` | 0x2749c4 | 16 |
| `_CSBTBL` | 0x2749d4 | 256 |
| `__func__.5457` | 0x27801d | 10 |
| `__func__.5465` | 0x278027 | 9 |
| `degrees` | 0x278030 | 20 |
| `seps` | 0x278044 | 20 |
| `_C_tolower_` | 0x278058 | 514 |
| `_C_toupper_` | 0x27825a | 514 |
| `xdigs_lower.7398` | 0x27845c | 16 |
| `xdigs_upper.7399` | 0x27846c | 16 |
| `basefix.6298` | 0x27847c | 34 |
| `charmap` | 0x27849e | 256 |
| `__FUNCTION__.7346` | 0x27859e | 26 |
| `wildabbr` | 0x2785b8 | 4 |
| `__FUNCTION__.7453` | 0x2785bc | 21 |
| `mon_lengths` | 0x2785d4 | 96 |
| `gmt` | 0x278634 | 4 |
| `year_lengths` | 0x278638 | 8 |
| `wday_name` | 0x278640 | 21 |
| `length_of_year` | 0x278658 | 8 |
| `safe_years_low` | 0x278660 | 112 |
| `julian_days_by_month` | 0x2786d0 | 96 |
| `days_in_month` | 0x278730 | 96 |
| `safe_years_high` | 0x278790 | 112 |
| `mon_name` | 0x278800 | 36 |
| `_ZZ8endpwentE19__PRETTY_FUNCTION__` | 0x278824 | 16 |
| `_ZZ12getusershellE19__PRETTY_FUNCTION__` | 0x278834 | 21 |
| `_ZZ12setusershellE19__PRETTY_FUNCTION__` | 0x278849 | 20 |
| `_ZZ12endusershellE19__PRETTY_FUNCTION__` | 0x27885d | 20 |
| `_ZL23property_service_socket` | 0x278871 | 29 |
| `_ZSt7nothrow` | 0x27888e | 1 |
| `p05.6335` | 0x278890 | 12 |
| `__tens_D2A` | 0x2788a0 | 184 |
| `__tinytens_D2A` | 0x278958 | 40 |
| `__bigtens_D2A` | 0x278980 | 40 |
| `tinytens` | 0x2789a8 | 40 |
| `_C_ctype_` | 0x2789d0 | 257 |
| `CSWTCH.9` | 0x278b50 | 75 |
| `CSWTCH.8` | 0x278b9b | 75 |
| `mon_name.5838` | 0x278be6 | 36 |
| `wday_name.5837` | 0x278c0a | 21 |
| `fivesbits` | 0x278c30 | 92 |
| `je_small_bin2size_tab` | 0x278cc0 | 124 |
| `je_small_size2bin_tab` | 0x278d40 | 512 |
| `interval_invs.8359` | 0x278f40 | 116 |
| `tsd_static_data.8684` | 0x278fb8 | 16 |
| `__func__.4431` | 0x278fc8 | 8 |
| `ppr_get_bw_pwrs_fn` | 0x27d5f0 | 40 |
| `ppr_mcs_nss_grp_fn` | 0x27d618 | 48 |
| `ppr_ru_mcs_nss_grp_fn` | 0x27d648 | 32 |
| `wlc_event_names` | 0x2819e8 | 696 |
| `aliases.27253` | 0x281ca0 | 32 |
| `radar_names.29588` | 0x281cc0 | 104 |
| `radar_names.29613` | 0x281d28 | 104 |
| `iov_unknown_info` | 0x281d90 | 20 |
| `wlu_iov_info` | 0x281da4 | 5900 |
| `cnt_props` | 0x2834b0 | 2448 |
| `fc_flags` | 0x2881c0 | 40 |
| `he_cmd_list` | 0x2881e8 | 180 |
| `heb_cmd_list` | 0x28829c | 84 |
| `pavars` | 0x2909f0 | 192 |
| `pavars_SROM12` | 0x290ab0 | 192 |
| `pavars_SROM13` | 0x290b70 | 252 |
| `pavars_bwver_1` | 0x290c6c | 84 |
| `pavars_bwver_2` | 0x290cc0 | 84 |
| `pavars_bwver_3` | 0x290d14 | 108 |
| `povars` | 0x290d80 | 40 |
| `patrims` | 0x290da8 | 96 |
| `rxsig_sub_cmd_list` | 0x290e08 | 144 |
| `sc_cmd_list` | 0x290e98 | 36 |
| `pci_sromvars` | 0x290ebc | 12112 |
| `pci_srom15vars` | 0x293e0c | 96 |
| `pci_srom16vars` | 0x293e6c | 96 |
| `pci_srom17vars` | 0x293ecc | 464 |
| `pci_srom18vars` | 0x29409c | 96 |
| `perpath_pci_sromvars` | 0x2940fc | 2432 |
| `cis_hnbuvars` | 0x294a7c | 1984 |
| `twt_cmd_list` | 0x29523c | 120 |
| `nan_cmd_list` | 0x2952b4 | 1312 |
| `nan_cmd_help_list` | 0x2957d4 | 288 |
| `nan_awake_dw_param` | 0x2958f4 | 24 |
| `nan_sd_config_param_info` | 0x29590c | 492 |
| `nan_dp_config_param_info` | 0x295af8 | 300 |
| `nan_rng_config_param_info` | 0x295c24 | 132 |
| `rsdb_subcmd_lists` | 0x295ca8 | 80 |
| `slot_bss_subcmd_lists` | 0x295cf8 | 64 |
| `hp2p_subcmd_lists` | 0x295d38 | 80 |
| `ftm_cmdlist` | 0x295d88 | 380 |
| `ftm_tlvid_loginfo` | 0x295f04 | 392 |
| `ftm_method_value_loginfo` | 0x29608c | 40 |
| `ftm_tmu_value_loginfo` | 0x2960b4 | 48 |
| `ftm_caps_value_loginfo` | 0x2960e4 | 16 |
| `ftm_status_value_loginfo` | 0x2960f4 | 264 |
| `ftm_session_state_value_loginfo` | 0x2961fc | 96 |
| `ftm_ranging_state_value_loginfo` | 0x29625c | 32 |
| `ftm_ranging_flags_value_loginfo` | 0x29627c | 24 |
| `ftm_avail_flags_value_loginfo` | 0x296294 | 24 |
| `ftm_avail_timeref_value_loginfo` | 0x2962ac | 32 |
| `ftm_config_param_info` | 0x2962cc | 400 |
| `ftm_method_options_info` | 0x29645c | 144 |
| `ftm_session_options_info` | 0x2964ec | 324 |
| `ftm_event_type_loginfo` | 0x296630 | 144 |
| `randmac_config_methods` | 0x2966c0 | 40 |
| `randmac_config_param_info` | 0x2966e8 | 36 |
| `randmac_subcmdlist` | 0x29670c | 96 |
| `natoe_cmd_list` | 0x29676c | 144 |
| `mbo_subcmd_lists` | 0x2967fc | 280 |
| `oce_subcmd_lists` | 0x296914 | 140 |
| `esp_subcmd_lists` | 0x2969a0 | 60 |
| `band_type_to_name` | 0x2969dc | 40 |
| `wl_adps_sub_cmd_list` | 0x296a04 | 160 |
| `restrict_flag_list` | 0x296aa4 | 72 |
| `rpsnoa_subcmd_lists` | 0x296aec | 80 |
| `bam_sub_cmd_list` | 0x296b3c | 80 |
| `_ZL19_sys_signal_strings` | 0x296b8c | 256 |
| `_ZL18_sys_error_strings` | 0x296c8c | 1048 |
| `C_time_locale` | 0x2970a4 | 176 |
| `_ZL11android_ids` | 0x297154 | 408 |
| `_ZZ6wctypeE10properties` | 0x2972ec | 52 |
| `stats_arenas_i_lruns_j_node` | 0x297320 | 80 |
| `stats_arenas_i_small_node` | 0x297370 | 80 |
| `stats_arenas_node` | 0x2973c0 | 8 |
| `arenas_bin_node` | 0x2973c8 | 8 |
| `stats_arenas_i_node` | 0x2973d0 | 260 |
| `super_arenas_bin_i_node` | 0x2974d4 | 20 |
| `chunk_node` | 0x2974e8 | 40 |
| `stats_node` | 0x297510 | 120 |
| `prof_node` | 0x297588 | 60 |
| `super_stats_arenas_i_lruns_j_node` | 0x2975c4 | 20 |
| `tcache_node` | 0x2975d8 | 40 |
| `super_root_node` | 0x297600 | 20 |
| `arenas_node` | 0x297614 | 220 |
| `arenas_lrun_node` | 0x2976f0 | 8 |
| `arena_i_node` | 0x2976f8 | 60 |
| `stats_arenas_i_large_node` | 0x297734 | 80 |
| `super_arena_i_node` | 0x297784 | 20 |
| `super_arenas_lrun_i_node` | 0x297798 | 20 |
| `arenas_lrun_i_node` | 0x2977ac | 20 |
| `arenas_bin_i_node` | 0x2977c0 | 60 |
| `stats_arenas_i_lruns_node` | 0x2977fc | 8 |
| `root_node` | 0x297804 | 180 |
| `stats_arenas_i_bins_node` | 0x2978b8 | 8 |
| `super_stats_arenas_i_node` | 0x2978c0 | 20 |
| `thread_node` | 0x2978d4 | 120 |
| `stats_chunks_node` | 0x29794c | 60 |
| `config_node` | 0x297988 | 260 |
| `super_stats_arenas_i_bins_j_node` | 0x297a8c | 20 |
| `stats_arenas_i_bins_j_node` | 0x297aa0 | 180 |
| `opt_node` | 0x297b54 | 460 |
| `arena_node` | 0x297d20 | 8 |
| `stats_arenas_i_huge_node` | 0x297d28 | 80 |
| `__FINI_ARRAY__` | 0x297d78 | 4 |
| `__INIT_ARRAY__` | 0x297d80 | 4 |
| `__CTOR_LIST__` | 0x297d94 | 4 |
| `__PREINIT_ARRAY__` | 0x297d9c | 4 |
| `sha2_hash_impl_entries` | 0x297da4 | 60 |
| `_GLOBAL_OFFSET_TABLE_` | 0x297ff4 | 0 |
| `atan_tbl` | 0x298000 | 68 |
| `TWDL_cos_128` | 0x298044 | 258 |
| `TWDL_cos` | 0x298148 | 130 |
| `meat.7892` | 0x2981cc | 4 |
| `crypto_algo_names` | 0x2981d0 | 84 |
| `wf_chspec_bw_str` | 0x298224 | 32 |
| `null_flags.4995` | 0x298244 | 4 |
| `scan_timeout` | 0x298248 | 4 |
| `pkt.27923` | 0x298358 | 113 |
| `cntry_names` | 0x2983d0 | 2032 |
| `wl_config_iovar_list` | 0x298bc0 | 176 |
| `dfs_cacstate_str` | 0x298c70 | 28 |
| `wl_msgs` | 0x298c8c | 280 |
| `wl_msgs2` | 0x298da4 | 224 |
| `wl_msgs3` | 0x298e84 | 16 |
| `toe_cmpnt` | 0x298e94 | 24 |
| `arpoe_cmpnt` | 0x298eac | 40 |
| `cca_errors` | 0x298ed4 | 24 |
| `wl_monpromisc_level_msgs` | 0x298eec | 32 |
| `reason_names.28766` | 0x298f0c | 96 |
| `status_names.28770` | 0x298f6c | 136 |
| `auth_mode.28908` | 0x298ff4 | 104 |
| `codename.29159` | 0x29905c | 8 |
| `wl_cmds` | 0x299064 | 7000 |
| `wl_varcmd` | 0x29abbc | 20 |
| `g_sig_ctrlc` | 0x29abd0 | 4 |
| `remote_vista_cmds` | 0x29abd4 | 36 |
| `wl_iov_type_count` | 0x29abf8 | 4 |
| `cmd2cat` | 0x29abfc | 2416 |
| `wl_iov_type_strings` | 0x29b56c | 40 |
| `wl_cmd_category_strings` | 0x29b594 | 68 |
| `wl_cmd_category_desc` | 0x29b5d8 | 68 |
| `g_wlc_idx` | 0x29b61c | 4 |
| `wlu_iov_info_count` | 0x29b620 | 4 |
| `rwl_os_type` | 0x29b624 | 4 |
| `rwl_dut_autodetect` | 0x29b628 | 1 |
| `defined_debug` | 0x29b62a | 2 |
| `g_driver_io` | 0x29b62c | 4 |
| `g_rwl_device_baud` | 0x29b630 | 4 |
| `g_rwl_device_name_serial` | 0x29b634 | 4 |
| `g_rwl_buf_mac` | 0x29b638 | 4 |
| `legacy_reg_rate_map` | 0x29b63c | 336 |
| `vht_ss1_reg_rate_map` | 0x29b78c | 480 |
| `vht_ss2_reg_rate_map` | 0x29b96c | 288 |
| `vht_ss3_reg_rate_map` | 0x29ba8c | 192 |
| `vht_ss4_reg_rate_map` | 0x29bb4c | 96 |
| `he_ss1_reg_rate_map` | 0x29bbac | 240 |
| `he_ss2_reg_rate_map` | 0x29bc9c | 192 |
| `he_ss3_reg_rate_map` | 0x29bd5c | 96 |
| `clm_rate_group_labels` | 0x29bdbc | 384 |
| `clm_rate_labels` | 0x29bf3c | 1872 |
| `exp_mode_name` | 0x29c68c | 12 |
| `cntr_offset_info_v6` | 0x29c698 | 1496 |
| `cntr_offset_info_v11` | 0x29cc70 | 1984 |
| `cntr_offset_info_v30` | 0x29d430 | 2488 |
| `wlc_he_cnt_offset_info` | 0x29dde8 | 320 |
| `wlc_he_omi_cnt_offset_info` | 0x29df28 | 136 |
| `wlc_cnt_offset_info` | 0x29dfb0 | 1560 |
| `reinitreason_offset_info` | 0x29e5c8 | 440 |
| `cntr_offset_info_v30_ge40mcst` | 0x29e780 | 520 |
| `cntr_offset_info_v30_ge64mcxst` | 0x29e988 | 56 |
| `cntr_offset_info_v30_ge80mcst` | 0x29e9c0 | 576 |
| `cntr_offset_info_v30_ge80mcst_txfunflw` | 0x29ec00 | 88 |
| `ver_to_cntr_offset_info_tbl` | 0x29ec58 | 32 |
| `wl_ampdu_cmds` | 0x29ec78 | 240 |
| `wl_ampdu_cmn_cmds` | 0x29ed68 | 60 |
| `wl_ap_cmds` | 0x29eda4 | 340 |
| `wl_arpoe_cmds` | 0x29eef8 | 160 |
| `wl_bmac_cmds` | 0x29ef98 | 500 |
| `wl_bssload_cmds` | 0x29f18c | 100 |
| `wl_btcx_cmds` | 0x29f1f0 | 140 |
| `wl_cac_cmds` | 0x29f27c | 160 |
| `wl_hc_cmds` | 0x29f31c | 40 |
| `hc_tx_cmds` | 0x29f344 | 132 |
| `hc_rx_cmds` | 0x29f3c8 | 72 |
| `hc_scan_cmds` | 0x29f410 | 24 |
| `hc_evt_cmds` | 0x29f428 | 84 |
| `wl_he_cmds` | 0x29f494 | 40 |
| `omi_ulmu_dis_status_str_tbl` | 0x29f4bc | 32 |
| `wl_heb_cmds` | 0x29f4dc | 40 |
| `wl_hmaptest_cmds` | 0x29f504 | 60 |
| `wl_ht_cmds` | 0x29f550 | 220 |
| `wl_interfere_cmds` | 0x29f654 | 80 |
| `wl_keep_alive_cmds` | 0x29f6a4 | 80 |
| `wl_keymgmt_cmds` | 0x29f6f4 | 180 |
| `wsec_test` | 0x29f7a8 | 56 |
| `wsec_info_tbl` | 0x29f7e0 | 48 |
| `wl_led_cmds` | 0x29f810 | 60 |
| `wl_lq_cmds` | 0x29f86c | 160 |
| `wl_ltecx_cmds` | 0x29f90c | 180 |
| `wl_macsmpl_cmds` | 0x29f9c0 | 40 |
| `wl_mfp_cmds` | 0x29f9e8 | 200 |
| `wl_obss_cmds` | 0x29fab0 | 60 |
| `wl_offloads_cmds` | 0x29faec | 180 |
| `wl_ota_cmds` | 0x29fba0 | 120 |
| `wl_otp_cmds` | 0x29fc18 | 240 |
| `wl_phy_cmds` | 0x29fd18 | 2020 |
| `wl_phy_msgs` | 0x2a04fc | 128 |
| `wl_pkt_filter_cmds` | 0x2a057c | 180 |
| `basenames` | 0x2a0630 | 128 |
| `wl_prot_obss_cmds` | 0x2a06b0 | 120 |
| `wl_rmc_cmds` | 0x2a0728 | 220 |
| `wl_rrm_cmds` | 0x2a0804 | 300 |
| `rrm_msgs` | 0x2a0930 | 224 |
| `wl_rxsig_cmds` | 0x2a0a10 | 40 |
| `wl_sc_cmds` | 0x2a0a38 | 40 |
| `wl_scan_cmds` | 0x2a0a60 | 220 |
| `wl_seq_cmds` | 0x2a0b3c | 100 |
| `wl_srom_cmds` | 0x2a0ba0 | 240 |
| `wl_stf_cmds` | 0x2a0c90 | 320 |
| `mimo_ps_status_state_str_tbl` | 0x2a0dd0 | 24 |
| `mimo_ps_status_bw_str_tbl` | 0x2a0de8 | 24 |
| `mimo_ps_status_hw_state_str_tbl` | 0x2a0e00 | 40 |
| `mimo_ps_status_mhf_flag` | 0x2a0e28 | 16 |
| `ocl_status_fw_state_str_tbl` | 0x2a0e38 | 28 |
| `ocl_status_hw_state_str_tbl` | 0x2a0e54 | 32 |
| `wl_toe_cmds` | 0x2a0e74 | 80 |
| `wl_tpc_cmds` | 0x2a0ec4 | 120 |
| `wl_twt_cmds` | 0x2a0f54 | 40 |
| `setup_cmd_val` | 0x2a0f7c | 48 |
| `twt_type_val` | 0x2a0fac | 24 |
| `flow_flag_val` | 0x2a0fc4 | 16 |
| `wl_txcap_cmds` | 0x2a105c | 140 |
| `wl_wds_cmds` | 0x2a10e8 | 160 |
| `wl_wnm_cmds` | 0x2a1188 | 540 |
| `wl_wnm_msgs` | 0x2a13a4 | 80 |
| `wl_wowl_cmds` | 0x2a13f4 | 220 |
| `wl_btcdyn_cmds` | 0x2a14d0 | 80 |
| `wl_nan_cmds` | 0x2a1520 | 40 |
| `wl_rsdb_cmds` | 0x2a1548 | 100 |
| `wl_slot_bss_cmds` | 0x2a15d4 | 80 |
| `wl_hp2p_cmds` | 0x2a1624 | 40 |
| `wl_sdio_cmds` | 0x2a164c | 320 |
| `wl_sd_msgs` | 0x2a178c | 40 |
| `wl_ndoe_cmds` | 0x2a17b4 | 180 |
| `wl_p2po_cmds` | 0x2a1868 | 360 |
| `wl_anqpo_cmds` | 0x2a19d0 | 180 |
| `wl_bdo_cmds` | 0x2a1a84 | 40 |
| `wl_tko_cmds` | 0x2a1aac | 80 |
| `wl_pfn_cmds` | 0x2a1afc | 420 |
| `adaptname` | 0x2a1ca0 | 16 |
| `wl_tbow_cmds` | 0x2a1cb0 | 40 |
| `wl_p2p_cmds` | 0x2a1cd8 | 240 |
| `wl_tdls_cmds` | 0x2a1dc8 | 80 |
| `wl_proxd_cmds` | 0x2a1e64 | 360 |
| `ftm_bcmerrorstrtable` | 0x2a1fcc | 292 |
| `proxd_mode.25262` | 0x2a20f0 | 20 |
| `proxd_state.25266` | 0x2a2104 | 32 |
| `tof_proxd_state.25270` | 0x2a2124 | 24 |
| `tof_proxd_reason.25274` | 0x2a213c | 20 |
| `proxd_reason.25278` | 0x2a2150 | 16 |
| `proxd_nan_status.25378` | 0x2a2160 | 20 |
| `wl_randmac_cmds` | 0x2a2174 | 40 |
| `buf_natoe` | 0x2a21b4 | 4 |
| `wl_natoe_cmds` | 0x2a21b8 | 60 |
| `wl_msch_cmds` | 0x2a221c | 180 |
| `ramstart_str` | 0x2a22d0 | 4 |
| `rodata_start_str` | 0x2a22d4 | 4 |
| `rodata_end_str` | 0x2a22d8 | 4 |
| `logstrs_path` | 0x2a22dc | 4 |
| `st_str_file_path` | 0x2a22e0 | 4 |
| `map_file_path` | 0x2a22e4 | 4 |
| `rom_st_str_file_path` | 0x2a22e8 | 4 |
| `rom_map_file_path` | 0x2a22ec | 4 |
| `ram_file_str` | 0x2a22f0 | 4 |
| `rom_file_str` | 0x2a22f4 | 4 |
| `wl_awdl_cmds` | 0x2a22f8 | 540 |
| `wl_mbo_cmds` | 0x2a2514 | 40 |
| `wl_oce_cmds` | 0x2a253c | 40 |
| `wl_esp_cmds` | 0x2a2564 | 40 |
| `wl_ecounters_cmds` | 0x2a258c | 80 |
| `wl_pwrstats_cmds` | 0x2a25dc | 40 |
| `wl_adps_cmds` | 0x2a2604 | 40 |
| `wl_leakyapstats_cmds` | 0x2a262c | 60 |
| `wl_rpsnoa_cmds` | 0x2a2668 | 40 |
| `wl_pwropt_cmds` | 0x2a2690 | 180 |
| `bcntrim_status_fw_state_str_tbl` | 0x2a2744 | 16 |
| `ops_status_fw_state_str_tbl` | 0x2a2754 | 16 |
| `nap_status_fw_state_str_tbl` | 0x2a2764 | 20 |
| `nap_status_hw_state_str_tbl` | 0x2a2778 | 32 |
| `psbw_status_disable_reasons_str_tbl` | 0x2a2798 | 40 |
| `psbw_status_fw_state_str_tbl` | 0x2a27c0 | 16 |
| `wl_btl_cmds` | 0x2a27d0 | 40 |
| `wl_tvpm_cmds` | 0x2a27f8 | 40 |
| `wl_bam_cmds` | 0x2a2820 | 40 |
| `wl_tdmtx_cmds` | 0x2a2848 | 40 |
| `_ZL19g_atfork_list_mutex` | 0x2a28c8 | 4 |
| `_ZL25kernel_has_MADV_MERGEABLE` | 0x2a28cc | 1 |
| `rand_type` | 0x2a28d0 | 4 |
| `rptr` | 0x2a28d4 | 4 |
| `randtbl` | 0x2a28d8 | 128 |
| `state` | 0x2a2958 | 4 |
| `rand_sep` | 0x2a295c | 4 |
| `fptr` | 0x2a2960 | 4 |
| `end_ptr` | 0x2a2964 | 4 |
| `rand_deg` | 0x2a2968 | 4 |
| `_tolower_tab_` | 0x2a296c | 4 |
| `_toupper_tab_` | 0x2a2970 | 4 |
| `__sF` | 0x2a2974 | 252 |
| `_thread_tagname___sfp_mutex` | 0x2a2a70 | 8 |
| `uglue` | 0x2a2a78 | 12 |
| `_thread_tagname___sinit_mutex.6505` | 0x2a2a84 | 8 |
| `__sglue` | 0x2a2a8c | 12 |
| `lastglue` | 0x2a2a98 | 4 |
| `zeroes.7397` | 0x2a2a9c | 16 |
| `blanks.7396` | 0x2a2aac | 16 |
| `tzname` | 0x2a2acc | 8 |
| `_ZL31__bionic_current_locale_is_utf8` | 0x2a2ad4 | 1 |
| `__netdClientDispatch` | 0x2a2ae0 | 16 |
| `_ZL17property_filename` | 0x2a2b00 | 4096 |
| `pmem_next` | 0x2a3b00 | 4 |
| `fpi.6359` | 0x2a3b04 | 20 |
| `fpinan.6397` | 0x2a3b18 | 20 |
| `fpi0.6262` | 0x2a3b2c | 20 |
| `fpi0.6279` | 0x2a3b40 | 20 |
| `_ctype_` | 0x2a3b54 | 4 |
| `je_opt_lg_prof_interval` | 0x2a3b58 | 4 |
| `je_opt_prof_active` | 0x2a3b5c | 1 |
| `je_opt_lg_prof_sample` | 0x2a3b60 | 4 |
| `je_opt_prof_final` | 0x2a3b64 | 1 |
| `je_opt_lg_tcache_max` | 0x2a3b68 | 4 |
| `je_opt_tcache` | 0x2a3b6c | 1 |
| `je_opt_lg_dirty_mult` | 0x2a3b70 | 4 |
| `je_opt_dss` | 0x2a3b74 | 4 |
| `je_opt_lg_chunk` | 0x2a3b78 | 4 |
| `je_dss_prec_names` | 0x2a3b7c | 16 |
| `dss_prec_default` | 0x2a3b8c | 4 |
| `__dso_handle` | 0x2a3b90 | 4 |
| `_bcmutils_dummy_fn` | 0x2a3b94 | 4 |
| `ioctl_version` | 0x2a3b98 | 4 |
| `bufstruct_wlu` | 0x2a3ba0 | 8192 |
| `int_fmt` | 0x2a5ba0 | 1 |
| `batch_in_client` | 0x2a5ba1 | 1 |
| `module_cmds` | 0x2a5ba4 | 1024 |
| `module_count` | 0x2a5fa4 | 4 |
| `etoa_buf.27693` | 0x2a5fa8 | 18 |
| `idx.27746` | 0x2a5fbc | 4 |
| `buffer.27745` | 0x2a5fc0 | 256 |
| `iptoa_buf.27764` | 0x2a60c0 | 16 |
| `verstr.27813` | 0x2a60d0 | 100 |
| `wl_iov_mod_names` | 0x2a6138 | 1024 |
| `g_swap` | 0x2a6538 | 1 |
| `g_sc` | 0x2a6539 | 1 |
| `unknown.23487` | 0x2a653c | 64 |
| `remote_type` | 0x2a657c | 4 |
| `g_rwl_servIP` | 0x2a6580 | 4 |
| `debug` | 0x2a6584 | 1 |
| `interactive_flag` | 0x2a6588 | 4 |
| `g_rwl_swap` | 0x2a658c | 1 |
| `g_rem_ifname` | 0x2a6590 | 16 |
| `rem_cdc` | 0x2a65a0 | 36 |
| `at_start_of_line` | 0x2a65c4 | 1 |
| `numeric.23350` | 0x2a662c | 6 |
| `ftm_msgbuf_status_undef.25613` | 0x2a66a4 | 32 |
| `natoe_bufstruct_wlu` | 0x2a66c8 | 8192 |
| `mschbufp` | 0x2a86c8 | 4 |
| `mschdata` | 0x2a86cc | 4 |
| `mschfp` | 0x2a86d0 | 4 |
| `solt_start_time` | 0x2a86d8 | 32 |
| `req_start_time` | 0x2a86f8 | 32 |
| `profiler_start_time` | 0x2a8718 | 32 |
| `solt_chanspec` | 0x2a8738 | 16 |
| `req_start` | 0x2a8748 | 16 |
| `lastMessages` | 0x2a8758 | 1 |
| `display_time.25560` | 0x2a875c | 32 |
| `buf` | 0x2a8790 | 4 |
| `_ZL16g_abort_msg_lock` | 0x2a8794 | 4 |
| `__abort_message_ptr` | 0x2a8798 | 4 |
| `_ZL13g_atfork_list` | 0x2a879c | 8 |
| `g_thread_list` | 0x2a87a4 | 4 |
| `g_thread_list_lock` | 0x2a87a8 | 4 |
| `_ZL25__bionic_tls_strerror_key` | 0x2a87ac | 4 |
| `random_mutex` | 0x2a87b0 | 4 |
| `usualext` | 0x2a87b4 | 544 |
| `__sFext` | 0x2a89d4 | 96 |
| `usual` | 0x2a8a34 | 1428 |
| `empty.6481` | 0x2a8fc8 | 84 |
| `restartloop` | 0x2a901c | 4 |
| `call_depth.5834` | 0x2a9020 | 4 |
| `__isthreaded` | 0x2a9024 | 4 |
| `last.4430` | 0x2a9028 | 4 |
| `gmt_is_set` | 0x2a902c | 4 |
| `timezone` | 0x2a9030 | 4 |
| `daylight` | 0x2a9034 | 4 |
| `g_cached_time_zone_name.7459` | 0x2a9038 | 4 |
| `zttinfo.6626` | 0x2a903c | 20 |
| `g_cached_time_zone.7460` | 0x2a9050 | 12464 |
| `lcl_TZname` | 0x2ac100 | 256 |
| `tmGlobal` | 0x2ac200 | 44 |
| `lcl_is_set` | 0x2ac22c | 4 |
| `buf.6687` | 0x2ac230 | 92 |
| `gmtptr` | 0x2ac28c | 4 |
| `lclptr` | 0x2ac290 | 4 |
| `_tzMutex` | 0x2ac294 | 4 |
| `Static_Return_String` | 0x2ac298 | 35 |
| `Static_Return_Date` | 0x2ac2bc | 44 |
| `gMallocLeakZygoteChild` | 0x2ac2e8 | 4 |
| `_ZL12g_hash_table` | 0x2ac2ec | 6180 |
| `__libc_auxv` | 0x2adb10 | 4 |
| `__progname` | 0x2adb14 | 4 |
| `_ZZ15__libc_init_tlsR19KernelArgumentBlockE11main_thread` | 0x2adb18 | 580 |
| `_ZZ15__libc_init_tlsR19KernelArgumentBlockE3tls` | 0x2add5c | 592 |
| `environ` | 0x2adfac | 4 |
| `__stack_chk_guard` | 0x2adfb0 | 4 |
| `_ZL8g_locale` | 0x2adfb4 | 56 |
| `_ZL15g_uselocale_key` | 0x2adfec | 4 |
| `_ZL13g_locale_once` | 0x2adff0 | 4 |
| `_ZN18ScopedTlsMapAccess10s_tls_map_E` | 0x2adff4 | 616 |
| `_ZN18ScopedTlsMapAccess15s_tls_map_lock_E` | 0x2ae25c | 4 |
| `_ZL10stubs_once` | 0x2ae260 | 4 |
| `_ZL9stubs_key` | 0x2ae264 | 4 |
| `_ZL12pa_data_size` | 0x2ae268 | 4 |
| `__system_property_area__` | 0x2ae26c | 4 |
| `_ZL11compat_mode` | 0x2ae270 | 1 |
| `_ZL7pa_size` | 0x2ae274 | 4 |
| `_ZL13g_atexit_lock` | 0x2ae278 | 4 |
| `_ZL11g_arc4_lock` | 0x2ae27c | 4 |
| `_ZZ7mbrtowcE15__private_state` | 0x2ae280 | 4 |
| `_ZZ10mbsnrtowcsE15__private_state` | 0x2ae284 | 4 |
| `_ZZ10wcsnrtombsE15__private_state` | 0x2ae288 | 4 |
| `_ZZ7wcrtombE15__private_state` | 0x2ae28c | 4 |
| `p5s` | 0x2ae290 | 4 |
| `private_mem` | 0x2ae298 | 2304 |
| `freelist` | 0x2aeb98 | 40 |
| `buf_asctime` | 0x2aebc0 | 72 |
| `init_lock` | 0x2aec08 | 4 |
| `je_opt_abort` | 0x2aec0c | 1 |
| `malloc_initialized` | 0x2aec0d | 1 |
| `je_arenas_tsd_init_head` | 0x2aec10 | 8 |
| `je_opt_junk` | 0x2aec18 | 1 |
| `je_thread_allocated_tsd_init_head` | 0x2aec1c | 8 |
| `je_opt_xmalloc` | 0x2aec24 | 1 |
| `je_opt_utrace` | 0x2aec25 | 1 |
| `je_opt_narenas` | 0x2aec28 | 4 |
| `malloc_initializer` | 0x2aec2c | 4 |
| `je_opt_quarantine` | 0x2aec30 | 4 |
| `je_opt_zero` | 0x2aec34 | 1 |
| `je_opt_redzone` | 0x2aec35 | 1 |
| `je_arenas_booted` | 0x2aec36 | 1 |
| `je_thread_allocated_booted` | 0x2aec37 | 1 |
| `prof_dump_mtx` | 0x2aec38 | 4 |
| `prof_dump_seq_mtx` | 0x2aec3c | 4 |
| `prof_dump_useq` | 0x2aec40 | 8 |
| `cum_ctxs` | 0x2aec48 | 4 |
| `je_opt_prof_leak` | 0x2aec4c | 1 |
| `je_prof_interval` | 0x2aec50 | 8 |
| `prof_dump_seq` | 0x2aec58 | 8 |
| `bt2ctx_mtx` | 0x2aec60 | 4 |
| `je_opt_prof_gdump` | 0x2aec64 | 1 |
| `prof_dump_buf_end` | 0x2aec68 | 4 |
| `bt2ctx` | 0x2aec6c | 28 |
| `je_opt_prof_accum` | 0x2aec88 | 1 |
| `prof_dump_iseq` | 0x2aec90 | 8 |
| `prof_dump_buf` | 0x2aec98 | 1 |
| `prof_booted` | 0x2aec99 | 1 |
| `prof_dump_mseq` | 0x2aeca0 | 8 |
| `je_prof_tdata_tsd_init_head` | 0x2aeca8 | 8 |
| `je_prof_tdata_booted` | 0x2aecb0 | 1 |
| `ctx_locks` | 0x2aecb4 | 4 |
| `prof_dump_fd` | 0x2aecb8 | 4 |
| `je_opt_prof` | 0x2aecbc | 1 |
| `je_quarantine_tsd_init_head` | 0x2aecc0 | 8 |
| `je_quarantine_booted` | 0x2aecc8 | 1 |
| `je_stats_cactive` | 0x2aeccc | 4 |
| `je_opt_stats_print` | 0x2aecd0 | 1 |
| `stack_nelms` | 0x2aecd4 | 4 |
| `je_tcache_tsd_init_head` | 0x2aecd8 | 8 |
| `je_tcache_enabled_booted` | 0x2aece0 | 1 |
| `je_tcache_enabled_tsd_init_head` | 0x2aece4 | 8 |
| `je_tcache_booted` | 0x2aecec | 1 |
| `ncleanups` | 0x2aecf0 | 4 |
| `cleanups` | 0x2aecf4 | 32 |
| `_ZZ8c32rtombE15__private_state` | 0x2aed14 | 4 |
| `_ZZ8mbrtoc32E15__private_state` | 0x2aed18 | 4 |
| `__dtoa_locks` | 0x2aed1c | 8 |
| `base_nodes` | 0x2aed24 | 4 |
| `base_past_addr` | 0x2aed28 | 4 |
| `base_next_addr` | 0x2aed2c | 4 |
| `base_mtx` | 0x2aed30 | 4 |
| `base_pages` | 0x2aed34 | 4 |
| `chunks_szad_mmap` | 0x2aed38 | 40 |
| `chunks_ad_dss` | 0x2aed60 | 40 |
| `chunks_szad_dss` | 0x2aed88 | 40 |
| `chunks_ad_mmap` | 0x2aedb0 | 40 |
| `dss_base` | 0x2aedd8 | 4 |
| `dss_max` | 0x2aeddc | 4 |
| `dss_mtx` | 0x2aede0 | 4 |
| `dss_prev` | 0x2aede4 | 4 |
| `ctl_mtx` | 0x2aede8 | 4 |
| `ctl_stats` | 0x2aedf0 | 48 |
| `ctl_epoch` | 0x2aee20 | 8 |
| `ctl_initialized` | 0x2aee28 | 1 |
| `huge_mtx` | 0x2aee2c | 4 |
| `huge` | 0x2aee30 | 40 |
| `__bionic_brk` | 0x2aee58 | 4 |
| `je_arena_bin_info` | 0x2aee60 | 1984 |
| `__hexdig_D2A` | 0x2af620 | 256 |
| `tlv_cntr_offset_tbl` | 0x2af720 | 144 |
| `raw_event` | 0x2af7b0 | 60 |
| `je_stats_chunks` | 0x2af7f0 | 16 |
| `bufmac_wlu` | 0x2af800 | 8 |
| `cmd_list` | 0x2af808 | 8 |
| `__atexit` | 0x2af810 | 4 |
| `__sdidinit` | 0x2af814 | 4 |
| `cmd_pkt_list_num` | 0x2af818 | 4 |
| `g_child_pid` | 0x2af81c | 4 |
| `g_irh` | 0x2af820 | 4 |
| `g_shellsync_pid` | 0x2af824 | 4 |
| `je_arena_maxclass` | 0x2af828 | 4 |
| `je_arenas` | 0x2af82c | 4 |
| `je_arenas_lock` | 0x2af830 | 4 |
| `je_arenas_tsd` | 0x2af834 | 4 |
| `je_chunk_npages` | 0x2af838 | 4 |
| `je_chunks_mtx` | 0x2af83c | 4 |
| `je_chunks_rtree` | 0x2af840 | 4 |
| `je_chunksize` | 0x2af844 | 4 |
| `je_chunksize_mask` | 0x2af848 | 4 |
| `je_malloc_conf` | 0x2af84c | 4 |
| `je_malloc_message` | 0x2af850 | 4 |
| `je_map_bias` | 0x2af854 | 4 |
| `je_narenas_auto` | 0x2af858 | 4 |
| `je_narenas_total` | 0x2af85c | 4 |
| `je_ncpus` | 0x2af860 | 4 |
| `je_nhbins` | 0x2af864 | 4 |
| `je_prof_tdata_tsd` | 0x2af868 | 4 |
| `je_quarantine_tsd` | 0x2af86c | 4 |
| `je_tcache_bin_info` | 0x2af870 | 4 |
| `je_tcache_enabled_tsd` | 0x2af874 | 4 |
| `je_tcache_maxclass` | 0x2af878 | 4 |
| `je_tcache_tsd` | 0x2af87c | 4 |
| `je_thread_allocated_tsd` | 0x2af880 | 4 |
| `need_speedy_response` | 0x2af884 | 4 |
| `vista_cmd_index` | 0x2af888 | 4 |
| `wlu_av0` | 0x2af88c | 4 |
| `g_rwl_servport` | 0x2af890 | 2 |
| `mod_ver` | 0x2af892 | 2 |
| `cmd_batching_mode` | 0x2af894 | 1 |
| `je_in_valgrind` | 0x2af895 | 1 |
| `je_opt_prof_prefix` | 0x2af896 | 1 |

</details>

### `/bin/dji_network`

+89 / −0 functions · +1 / −0 objects

**New functions (89)**

| Symbol | Addr | Size |
|---|---|---|
| `wms_cfg_get_string` | 0x59c0 | 468 |
| `wms_cfg_get_integer` | 0x5b98 | 364 |
| `wms_json_cfg_init` | 0x5d08 | 1544 |
| `_hostapd_event_handler_connected` | 0xea10 | 328 |
| `_hostapd_event_handler_disconnected` | 0xeb58 | 384 |
| `_wifi_ap_conn_state_set` | 0xecd8 | 12 |
| `_wifi_ap_conn_state_get` | 0xece8 | 12 |
| `_wifi_peer_ip_thread_set` | 0xecf8 | 16 |
| `_send_hostapd_request` | 0xed08 | 404 |
| `wifi_peer_ip_get` | 0xeea0 | 552 |
| `wifi_peer_ip_get_thread` | 0xf0c8 | 384 |
| `wifi_hostapd_update_conn_state` | 0xf248 | 308 |
| `wifi_hostapd_sta_info` | 0xf380 | 88 |
| `wifi_hostapd_monitor_init` | 0xf3d8 | 1532 |
| `_hostapd_monitor_recv_thread` | 0xf9d8 | 1116 |
| `wifi_hostapd_monitor_deinit` | 0xfe38 | 324 |
| `_bcm_init` | 0x10028 | 208 |
| `_bcm_deinit` | 0x100f8 | 68 |
| `wifi_link_quality_info_monitor` | 0x10140 | 1976 |
| `_bcm_wifi_nl80211_get_lstats` | 0x109a0 | 312 |
| `channel_to_freq` | 0x11d68 | 56 |
| `from_arp_file_get_mac` | 0x12878 | 376 |
| `_check_timeout` | 0x12aa0 | 308 |
| `os_icmp_send_packet` | 0x12bd8 | 516 |
| `os_icmp_recv_packet` | 0x12de0 | 804 |
| `os_icmp_update_dest_ip` | 0x13108 | 240 |
| `os_icmp_change_run_state` | 0x131f8 | 20 |
| `os_icmp_socket` | 0x13210 | 12 |
| `os_icmp_init` | 0x13220 | 428 |
| `os_icmp_deinit` | 0x133d0 | 180 |
| `os_nl80211_android_priv_cmd` | 0x13488 | 360 |
| `os_nl80211_send_and_recv` | 0x135f0 | 864 |
| `_os_nl80211_sock_error_handler` | 0x13950 | 16 |
| `_os_nl80211_sock_finish_handler` | 0x13960 | 12 |
| `_os_nl80211_sock_ack_handler` | 0x13970 | 12 |
| `os_nl80211_sock_deinit` | 0x13980 | 28 |
| `os_nl80211_sock_init` | 0x139a0 | 432 |
| `_ZL8snprintfPcU17pass_object_size1mPKcz` | 0x1c250 | 168 |
| `cJSON_GetErrorPtr` | 0x1f280 | 12 |
| `cJSON_InitHooks` | 0x1f290 | 88 |
| `cJSON_Delete` | 0x1f2e8 | 136 |
| `cJSON_ParseWithOpts` | 0x1f370 | 232 |
| `parse_value` | 0x1f458 | 1412 |
| `cJSON_Parse` | 0x1f9e0 | 144 |
| `cJSON_Print` | 0x1fa70 | 16 |
| `print_value` | 0x1fa80 | 772 |
| `cJSON_PrintUnformatted` | 0x1fd88 | 16 |
| `cJSON_PrintBuffered` | 0x1fd98 | 128 |
| `cJSON_GetArraySize` | 0x1fe18 | 36 |
| `cJSON_GetArrayItem` | 0x1fe40 | 40 |

<details><summary>… 另 39 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `cJSON_GetObjectItem` | 0x1fe68 | 196 |
| `cJSON_GetArrayNextItem` | 0x1ff30 | 20 |
| `cJSON_AddItemToArray` | 0x1ff48 | 44 |
| `cJSON_AddItemToObject` | 0x1ff78 | 168 |
| `cJSON_AddItemToObjectCS` | 0x20020 | 128 |
| `cJSON_AddItemReferenceToArray` | 0x200a0 | 140 |
| `cJSON_AddItemReferenceToObject` | 0x20130 | 216 |
| `cJSON_DetachItemFromArray` | 0x20208 | 136 |
| `cJSON_DeleteItemFromArray` | 0x20290 | 136 |
| `cJSON_DetachItemFromObject` | 0x20318 | 328 |
| `cJSON_DeleteItemFromObject` | 0x20460 | 20 |
| `cJSON_InsertItemInArray` | 0x20478 | 140 |
| `cJSON_ReplaceItemInArray` | 0x20508 | 116 |
| `cJSON_ReplaceItemInObject` | 0x20580 | 428 |
| `cJSON_CreateNull` | 0x20730 | 56 |
| `cJSON_CreateTrue` | 0x20768 | 56 |
| `cJSON_CreateFalse` | 0x207a0 | 48 |
| `cJSON_CreateBool` | 0x207d0 | 72 |
| `cJSON_CreateNumber` | 0x20818 | 80 |
| `cJSON_CreateString` | 0x20868 | 136 |
| `cJSON_CreateArray` | 0x208f0 | 56 |
| `cJSON_CreateObject` | 0x20928 | 56 |
| `cJSON_CreateIntArray` | 0x20960 | 212 |
| `cJSON_CreateFloatArray` | 0x20a38 | 224 |
| `cJSON_CreateDoubleArray` | 0x20b18 | 220 |
| `cJSON_CreateStringArray` | 0x20bf8 | 264 |
| `cJSON_Duplicate` | 0x20d00 | 340 |
| `cJSON_Minify` | 0x20e58 | 280 |
| `parse_string` | 0x20f70 | 1248 |
| `print_number` | 0x21450 | 876 |
| `print_array` | 0x217c0 | 1268 |
| `print_object` | 0x21cb8 | 2284 |
| `print_string_ptr` | 0x225a8 | 1032 |
| `duss_access_file` | 0x229b0 | 52 |
| `duss_get_file_size` | 0x229e8 | 288 |
| `duss_load_file` | 0x22b08 | 904 |
| `duss_mmap_file_open` | 0x22e90 | 1052 |
| `duss_mmap_file_write` | 0x232b0 | 88 |
| `duss_mmap_file_close` | 0x23308 | 288 |

</details>

**New objects (1)**

| Symbol | Addr | Size |
|---|---|---|
| `g_hostapd_event_handler` | 0x53fc8 | 48 |

### `/bin/bt_bsa_app`

+8 / −0 functions · +0 / −0 objects

**New functions (8)**

| Symbol | Addr | Size |
|---|---|---|
| `app_errno2str` | 0x4220 | 40 |
| `bt_get_default_name` | 0xf6a8 | 104 |
| `bt_get_product_id` | 0xfa08 | 84 |
| `cJSON_Delete` | 0xfec0 | 136 |
| `parse_value` | 0xff48 | 1412 |
| `cJSON_Parse` | 0x104d0 | 144 |
| `cJSON_GetObjectItem` | 0x10560 | 196 |
| `parse_string` | 0x10628 | 1248 |

### `/bin/camera-storage`

+0 / −1 functions · +0 / −0 objects

**Removed functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZZNK9CacheItem8bestFileEvENK3$_2clERK5QListI13CacheItemInfoE` | 0x80ff0 | 608 |

### `/bin/msg2dbus`

+1 / −0 functions · +0 / −0 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN15MessageIO_WlTcpD1Ev` | 0x4be80 | 228 |

### `/lib/modules/bcmdhd.ko`

+1 / −0 functions · +237 / −238 objects

**New functions (1)**

| Symbol | Addr | Size |
|---|---|---|
| `dhd_wlan_init_gpio` | 0xa2d08 | 48 |

**New objects (237)**

| Symbol | Addr | Size |
|---|---|---|
| `__UNIQUE_ID_dhd_tcm_test_enabletype88` | 0x0 | 34 |
| `__UNIQUE_ID_enable_ecountertype87` | 0x22 | 30 |
| `__UNIQUE_ID_allow_delay_fwdltype86` | 0x40 | 30 |
| `__UNIQUE_ID_dhd_pktgen_lentype85` | 0x5e | 29 |
| `__UNIQUE_ID_dhd_pktgentype84` | 0x7b | 25 |
| `__UNIQUE_ID_dhd_deferred_txtype83` | 0x94 | 30 |
| `__UNIQUE_ID_dhd_rxboundtype82` | 0xb2 | 26 |
| `__UNIQUE_ID_dhd_txboundtype81` | 0xcc | 26 |
| `__UNIQUE_ID_dhd_sdiod_drive_strengthtype80` | 0xe6 | 39 |
| `__UNIQUE_ID_dhd_intrtype79` | 0x10d | 23 |
| `__UNIQUE_ID_dhd_polltype78` | 0x124 | 23 |
| `__UNIQUE_ID_dhd_idletimetype77` | 0x13b | 26 |
| `__UNIQUE_ID_iface_nametype76` | 0x155 | 27 |
| `__UNIQUE_ID_pcie_txs_metadata_enabletype75` | 0x170 | 38 |
| `__UNIQUE_ID_instance_basetype74` | 0x196 | 27 |
| `__UNIQUE_ID_passive_channel_skiptype73` | 0x1b1 | 34 |
| `__UNIQUE_ID_dhd_dongle_ramsizetype72` | 0x1d3 | 32 |
| `__UNIQUE_ID_dhd_rxf_priotype71` | 0x1f3 | 26 |
| `__UNIQUE_ID_dhd_dpc_priotype70` | 0x20d | 26 |
| `__UNIQUE_ID_dhd_watchdog_priotype69` | 0x227 | 31 |
| `__UNIQUE_ID_dhd_master_modetype68` | 0x246 | 30 |
| `__UNIQUE_ID_dhd_pkt_filter_inittype67` | 0x264 | 34 |
| `__UNIQUE_ID_dhd_pkt_filter_enabletype66` | 0x286 | 36 |
| `__UNIQUE_ID_dhd_slpautotype65` | 0x2aa | 26 |
| `__UNIQUE_ID_dhd_console_mstype64` | 0x2c4 | 29 |
| `__UNIQUE_ID_dhd_watchdog_mstype63` | 0x2e1 | 30 |
| `__UNIQUE_ID_logtrace_pkt_senduptype62` | 0x2ff | 34 |
| `__UNIQUE_ID_wl_event_enabletype61` | 0x321 | 30 |
| `__UNIQUE_ID_config_pathtype60` | 0x33f | 28 |
| `__UNIQUE_ID_nvram_pathtype59` | 0x35b | 27 |
| `__UNIQUE_ID_firmware_pathtype58` | 0x376 | 30 |
| `__UNIQUE_ID_disable_proptxtype57` | 0x394 | 28 |
| `__UNIQUE_ID_dhd_arp_modetype56` | 0x3b0 | 27 |
| `__UNIQUE_ID_dhd_arp_enabletype55` | 0x3cb | 29 |
| `__UNIQUE_ID_config_msg_leveltype54` | 0x3e8 | 30 |
| `__UNIQUE_ID_android_msg_leveltype53` | 0x406 | 31 |
| `__UNIQUE_ID_wl_dbg_leveltype52` | 0x425 | 26 |
| `__UNIQUE_ID_iw_msg_leveltype51` | 0x43f | 26 |
| `__UNIQUE_ID_dhd_msg_leveltype50` | 0x459 | 27 |
| `__UNIQUE_ID_op_modetype49` | 0x474 | 21 |
| `__UNIQUE_ID_info_stringtype48` | 0x489 | 28 |
| `__UNIQUE_ID_clm_pathtype47` | 0x4a5 | 25 |
| `__UNIQUE_ID_license46` | 0x4be | 34 |
| `__FUNCTION__.88697` | 0xc88 | 12 |
| `__FUNCTION__.88518` | 0xca0 | 20 |
| `__FUNCTION__.88616` | 0xcb8 | 14 |
| `__FUNCTION__.89237` | 0xcc8 | 20 |
| `__FUNCTION__.88718` | 0xce0 | 36 |
| `__FUNCTION__.88246` | 0xd08 | 22 |
| `__FUNCTION__.88255` | 0xd20 | 25 |

<details><summary>… 另 187 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.88310` | 0xd40 | 12 |
| `__FUNCTION__.90016` | 0xd50 | 24 |
| `__FUNCTION__.90006` | 0xd68 | 24 |
| `__FUNCTION__.88328` | 0xd80 | 15 |
| `__FUNCTION__.88334` | 0xd90 | 11 |
| `CSWTCH.644` | 0xda0 | 10 |
| `__FUNCTION__.88527` | 0xdb8 | 18 |
| `__FUNCTION__.88850` | 0xdd0 | 16 |
| `__FUNCTION__.89097` | 0xde0 | 10 |
| `__FUNCTION__.89008` | 0xdf0 | 17 |
| `__FUNCTION__.89025` | 0xe08 | 18 |
| `__FUNCTION__.89035` | 0xe20 | 31 |
| `__FUNCTION__.89119` | 0xe40 | 15 |
| `__FUNCTION__.89129` | 0xe50 | 27 |
| `__FUNCTION__.89173` | 0xe70 | 15 |
| `__FUNCTION__.89205` | 0xe80 | 10 |
| `__FUNCTION__.89215` | 0xe90 | 19 |
| `__FUNCTION__.89229` | 0xea8 | 16 |
| `__FUNCTION__.89443` | 0xeb8 | 19 |
| `__FUNCTION__.89195` | 0xed0 | 9 |
| `__FUNCTION__.89584` | 0xee0 | 21 |
| `__FUNCTION__.89166` | 0xef8 | 16 |
| `__func__.89167` | 0xf08 | 16 |
| `__FUNCTION__.89612` | 0xf18 | 31 |
| `__FUNCTION__.89618` | 0xf38 | 27 |
| `__FUNCTION__.89626` | 0xf58 | 27 |
| `__FUNCTION__.89637` | 0xf78 | 28 |
| `__FUNCTION__.89661` | 0xf98 | 31 |
| `__FUNCTION__.89698` | 0xfb8 | 29 |
| `__FUNCTION__.89669` | 0xfd8 | 16 |
| `__FUNCTION__.89851` | 0xfe8 | 26 |
| `__FUNCTION__.89859` | 0x1008 | 25 |
| `__FUNCTION__.89868` | 0x1028 | 33 |
| `__FUNCTION__.89878` | 0x1050 | 28 |
| `__FUNCTION__.89888` | 0x1070 | 27 |
| `__FUNCTION__.89905` | 0x1090 | 29 |
| `__FUNCTION__.89912` | 0x10b0 | 32 |
| `__FUNCTION__.89919` | 0x10d0 | 25 |
| `__FUNCTION__.89927` | 0x10f0 | 21 |
| `__FUNCTION__.89949` | 0x1108 | 26 |
| `__FUNCTION__.89963` | 0x1128 | 25 |
| `__FUNCTION__.90033` | 0x1148 | 24 |
| `__FUNCTION__.90042` | 0x1160 | 24 |
| `__FUNCTION__.89990` | 0x1178 | 21 |
| `__FUNCTION__.88493` | 0x1190 | 12 |
| `__FUNCTION__.88628` | 0x11a0 | 20 |
| `__func__.90247` | 0x11b8 | 19 |
| `__FUNCTION__.88555` | 0x11d0 | 13 |
| `__FUNCTION__.88414` | 0x11e0 | 25 |
| `__FUNCTION__.88424` | 0x1200 | 27 |
| `__FUNCTION__.88357` | 0x1220 | 24 |
| `__FUNCTION__.88393` | 0x1238 | 24 |
| `__FUNCTION__.88405` | 0x1250 | 24 |
| `__FUNCTION__.88658` | 0x1268 | 15 |
| `__FUNCTION__.89435` | 0x1278 | 16 |
| `__FUNCTION__.88644` | 0x1288 | 15 |
| `__FUNCTION__.88992` | 0x1298 | 14 |
| `__FUNCTION__.90501` | 0x12a8 | 22 |
| `__FUNCTION__.90505` | 0x12c0 | 25 |
| `__FUNCTION__.88766` | 0x12e0 | 9 |
| `__FUNCTION__.88785` | 0x12f0 | 9 |
| `__FUNCTION__.88804` | 0x1300 | 19 |
| `__FUNCTION__.89182` | 0x1318 | 11 |
| `__FUNCTION__.88906` | 0x1328 | 11 |
| `__FUNCTION__.89073` | 0x1338 | 19 |
| `__FUNCTION__.90550` | 0x1350 | 16 |
| `__FUNCTION__.90585` | 0x1360 | 19 |
| `__FUNCTION__.89146` | 0x1378 | 27 |
| `__func__.89150` | 0x1398 | 27 |
| `__FUNCTION__.88281` | 0x13b8 | 16 |
| `__FUNCTION__.88139` | 0x13c8 | 16 |
| `__FUNCTION__.90089` | 0x13d8 | 25 |
| `__FUNCTION__.90095` | 0x13f8 | 25 |
| `__FUNCTION__.88506` | 0x1418 | 15 |
| `__FUNCTION__.88706` | 0x1428 | 15 |
| `__func__.88735` | 0x1438 | 18 |
| `__FUNCTION__.88736` | 0x1450 | 18 |
| `__func__.88755` | 0x1468 | 16 |
| `__FUNCTION__.88756` | 0x1478 | 16 |
| `__FUNCTION__.90522` | 0x1488 | 22 |
| `__FUNCTION__.90529` | 0x14a0 | 18 |
| `__FUNCTION__.90103` | 0x14b8 | 32 |
| `__FUNCTION__.90634` | 0x14d8 | 23 |
| `__FUNCTION__.90647` | 0x14f0 | 15 |
| `__FUNCTION__.90656` | 0x1500 | 14 |
| `__FUNCTION__.90302` | 0x1510 | 25 |
| `__FUNCTION__.90313` | 0x1530 | 19 |
| `__FUNCTION__.90683` | 0x1548 | 25 |
| `__FUNCTION__.90881` | 0x1568 | 19 |
| `__FUNCTION__.90887` | 0x1580 | 20 |
| `__FUNCTION__.90894` | 0x1598 | 22 |
| `__FUNCTION__.90901` | 0x15b0 | 23 |
| `__FUNCTION__.90908` | 0x15c8 | 22 |
| `__FUNCTION__.90915` | 0x15e0 | 23 |
| `__FUNCTION__.90922` | 0x15f8 | 18 |
| `__FUNCTION__.90929` | 0x1610 | 19 |
| `__FUNCTION__.90937` | 0x1628 | 18 |
| `__FUNCTION__.90945` | 0x1640 | 18 |
| `__FUNCTION__.90952` | 0x1658 | 22 |
| `__FUNCTION__.90960` | 0x1670 | 14 |
| `__FUNCTION__.90966` | 0x1680 | 19 |
| `__FUNCTION__.90973` | 0x1698 | 24 |
| `__FUNCTION__.90980` | 0x16b0 | 23 |
| `__FUNCTION__.90987` | 0x16c8 | 24 |
| `__FUNCTION__.90993` | 0x16e0 | 25 |
| `__FUNCTION__.90999` | 0x1700 | 20 |
| `__FUNCTION__.91005` | 0x1718 | 22 |
| `__FUNCTION__.91028` | 0x1730 | 12 |
| `__FUNCTION__.91033` | 0x1740 | 13 |
| `__FUNCTION__.91039` | 0x1750 | 24 |
| `__func__.67565` | 0x1b20 | 28 |
| `__FUNCTION__.67566` | 0x1b40 | 28 |
| `__FUNCTION__.67583` | 0x1bc0 | 23 |
| `__key.90180` | 0x3cd8 | 0 |
| `__key.90181` | 0x3cd8 | 0 |
| `__key.90204` | 0x3cd8 | 0 |
| `__key.90205` | 0x3cd8 | 0 |
| `__key.88911` | 0x3d10 | 0 |
| `__key.88912` | 0x3d10 | 0 |
| `__key.88913` | 0x3d10 | 0 |
| `__key.88914` | 0x3d10 | 0 |
| `__key.88915` | 0x3d10 | 0 |
| `__key.88916` | 0x3d10 | 0 |
| `__key.88917` | 0x3d10 | 0 |
| `__key.88918` | 0x3d10 | 0 |
| `__key.88919` | 0x3d10 | 0 |
| `__key.88920` | 0x3d10 | 0 |
| `__key.88921` | 0x3d10 | 0 |
| `__key.88922` | 0x3d10 | 0 |
| `__key.88923` | 0x3d10 | 0 |
| `__key.88924` | 0x3d10 | 0 |
| `__key.88925` | 0x3d10 | 0 |
| `__key.88926` | 0x3d10 | 0 |
| `__key.88927` | 0x3d10 | 0 |
| `__key.88928` | 0x3d10 | 0 |
| `__key.88929` | 0x3d10 | 0 |
| `__key.88930` | 0x3d10 | 0 |
| `__key.88931` | 0x3d10 | 0 |
| `__key.88932` | 0x3d10 | 0 |
| `__key.88933` | 0x3d10 | 0 |
| `__key.88934` | 0x3d10 | 0 |
| `__key.88935` | 0x3d10 | 0 |
| `__key.88936` | 0x3d10 | 0 |
| `__key.88937` | 0x3d10 | 0 |
| `__key.88938` | 0x3d10 | 0 |
| `__key.88939` | 0x3d10 | 0 |
| `__key.88940` | 0x3d10 | 0 |
| `__key.88941` | 0x3d10 | 0 |
| `__key.88942` | 0x3d10 | 0 |
| `__key.88943` | 0x3d10 | 0 |
| `__key.88944` | 0x3d10 | 0 |
| `__key.88945` | 0x3d10 | 0 |
| `__key.88946` | 0x3d10 | 0 |
| `__key.88949` | 0x3d10 | 0 |
| `__key.88950` | 0x3d10 | 0 |
| `__key.88953` | 0x3d10 | 0 |
| `__key.88954` | 0x3d10 | 0 |
| `__key.88957` | 0x3d10 | 0 |
| `__key.88958` | 0x3d10 | 0 |
| `__FUNCTION__.72822` | 0x9d70 | 11 |
| `__FUNCTION__.72750` | 0x9da0 | 24 |
| `__FUNCTION__.72446` | 0x9db8 | 13 |
| `__FUNCTION__.72452` | 0x9dc8 | 25 |
| `__FUNCTION__.72456` | 0x9de8 | 27 |
| `__FUNCTION__.72461` | 0x9e08 | 22 |
| `__FUNCTION__.72501` | 0x9e20 | 15 |
| `__FUNCTION__.72595` | 0x9f18 | 19 |
| `__FUNCTION__.72637` | 0x9f30 | 19 |
| `__FUNCTION__.72767` | 0x9f48 | 21 |
| `__FUNCTION__.72796` | 0x9f60 | 12 |
| `__FUNCTION__.72800` | 0x9f70 | 17 |
| `__FUNCTION__.72804` | 0x9f88 | 24 |
| `__FUNCTION__.72808` | 0x9fa0 | 23 |
| `__FUNCTION__.72817` | 0x9fb8 | 25 |
| `__FUNCTION__.72558` | 0x9fd8 | 24 |
| `__FUNCTION__.72430` | 0x9ff0 | 29 |
| `__FUNCTION__.72440` | 0xa010 | 13 |
| `__FUNCTION__.72572` | 0xa020 | 15 |
| `__FUNCTION__.72583` | 0xa030 | 19 |
| `__FUNCTION__.72831` | 0xa048 | 12 |
| `__FUNCTION__.72835` | 0xa058 | 11 |
| `__FUNCTION__.68429` | 0xb4a0 | 22 |
| `__FUNCTION__.68413` | 0xb4b8 | 19 |
| `__FUNCTION__.68449` | 0xb4d0 | 19 |
| `__FUNCTION__.68458` | 0xb4e8 | 24 |
| `__FUNCTION__.68462` | 0xb500 | 26 |
| `__FUNCTION__.68453` | 0xb520 | 21 |

</details>

**Removed objects (238)**

| Symbol | Addr | Size |
|---|---|---|
| `__UNIQUE_ID_dhd_tcm_test_enabletype108` | 0x0 | 34 |
| `__UNIQUE_ID_enable_ecountertype107` | 0x22 | 30 |
| `__UNIQUE_ID_allow_delay_fwdltype106` | 0x40 | 30 |
| `__UNIQUE_ID_dhd_pktgen_lentype105` | 0x5e | 29 |
| `__UNIQUE_ID_dhd_pktgentype104` | 0x7b | 25 |
| `__UNIQUE_ID_dhd_deferred_txtype103` | 0x94 | 30 |
| `__UNIQUE_ID_dhd_rxboundtype102` | 0xb2 | 26 |
| `__UNIQUE_ID_dhd_txboundtype101` | 0xcc | 26 |
| `__UNIQUE_ID_dhd_sdiod_drive_strengthtype100` | 0xe6 | 39 |
| `__UNIQUE_ID_dhd_intrtype99` | 0x10d | 23 |
| `__UNIQUE_ID_dhd_polltype98` | 0x124 | 23 |
| `__UNIQUE_ID_dhd_idletimetype97` | 0x13b | 26 |
| `__UNIQUE_ID_iface_nametype96` | 0x155 | 27 |
| `__UNIQUE_ID_pcie_txs_metadata_enabletype95` | 0x170 | 38 |
| `__UNIQUE_ID_instance_basetype94` | 0x196 | 27 |
| `__UNIQUE_ID_passive_channel_skiptype93` | 0x1b1 | 34 |
| `__UNIQUE_ID_dhd_dongle_ramsizetype92` | 0x1d3 | 32 |
| `__UNIQUE_ID_dhd_rxf_priotype91` | 0x1f3 | 26 |
| `__UNIQUE_ID_dhd_dpc_priotype90` | 0x20d | 26 |
| `__UNIQUE_ID_dhd_watchdog_priotype89` | 0x227 | 31 |
| `__UNIQUE_ID_dhd_master_modetype88` | 0x246 | 30 |
| `__UNIQUE_ID_dhd_pkt_filter_inittype87` | 0x264 | 34 |
| `__UNIQUE_ID_dhd_pkt_filter_enabletype86` | 0x286 | 36 |
| `__UNIQUE_ID_dhd_slpautotype85` | 0x2aa | 26 |
| `__UNIQUE_ID_dhd_console_mstype84` | 0x2c4 | 29 |
| `__UNIQUE_ID_dhd_watchdog_mstype83` | 0x2e1 | 30 |
| `__UNIQUE_ID_logtrace_pkt_senduptype82` | 0x2ff | 34 |
| `__UNIQUE_ID_wl_event_enabletype81` | 0x321 | 30 |
| `__UNIQUE_ID_config_pathtype80` | 0x33f | 28 |
| `__UNIQUE_ID_nvram_pathtype79` | 0x35b | 27 |
| `__UNIQUE_ID_firmware_pathtype78` | 0x376 | 30 |
| `__UNIQUE_ID_disable_proptxtype77` | 0x394 | 28 |
| `__UNIQUE_ID_dhd_arp_modetype76` | 0x3b0 | 27 |
| `__UNIQUE_ID_dhd_arp_enabletype75` | 0x3cb | 29 |
| `__UNIQUE_ID_config_msg_leveltype74` | 0x3e8 | 30 |
| `__UNIQUE_ID_android_msg_leveltype73` | 0x406 | 31 |
| `__UNIQUE_ID_wl_dbg_leveltype72` | 0x425 | 26 |
| `__UNIQUE_ID_iw_msg_leveltype71` | 0x43f | 26 |
| `__UNIQUE_ID_dhd_msg_leveltype70` | 0x459 | 27 |
| `__UNIQUE_ID_op_modetype69` | 0x474 | 21 |
| `__UNIQUE_ID_info_stringtype68` | 0x489 | 28 |
| `__UNIQUE_ID_clm_pathtype67` | 0x4a5 | 25 |
| `__UNIQUE_ID_license66` | 0x4be | 34 |
| `__FUNCTION__.94274` | 0xc88 | 12 |
| `__FUNCTION__.94095` | 0xca0 | 20 |
| `__FUNCTION__.94193` | 0xcb8 | 14 |
| `__FUNCTION__.94824` | 0xcc8 | 20 |
| `__FUNCTION__.94295` | 0xce0 | 36 |
| `__FUNCTION__.93823` | 0xd08 | 22 |
| `__FUNCTION__.93832` | 0xd20 | 25 |

<details><summary>… 另 188 个</summary>

| Symbol | Addr | Size |
|---|---|---|
| `__FUNCTION__.93887` | 0xd40 | 12 |
| `__FUNCTION__.95603` | 0xd50 | 24 |
| `__FUNCTION__.95593` | 0xd68 | 24 |
| `__FUNCTION__.93905` | 0xd80 | 15 |
| `__FUNCTION__.93911` | 0xd90 | 11 |
| `CSWTCH.649` | 0xda0 | 10 |
| `__FUNCTION__.94104` | 0xdb8 | 18 |
| `__FUNCTION__.94427` | 0xdd0 | 16 |
| `__FUNCTION__.94674` | 0xde0 | 10 |
| `__FUNCTION__.94585` | 0xdf0 | 17 |
| `__FUNCTION__.94602` | 0xe08 | 18 |
| `__FUNCTION__.94612` | 0xe20 | 31 |
| `__FUNCTION__.94696` | 0xe40 | 15 |
| `__FUNCTION__.94706` | 0xe50 | 27 |
| `__FUNCTION__.94750` | 0xe70 | 15 |
| `__FUNCTION__.94782` | 0xe80 | 10 |
| `__FUNCTION__.94802` | 0xe90 | 19 |
| `__FUNCTION__.94816` | 0xea8 | 16 |
| `__FUNCTION__.94798` | 0xeb8 | 14 |
| `__FUNCTION__.95030` | 0xec8 | 19 |
| `__FUNCTION__.94772` | 0xee0 | 9 |
| `__FUNCTION__.95171` | 0xef0 | 21 |
| `__FUNCTION__.94743` | 0xf08 | 16 |
| `__func__.94744` | 0xf18 | 16 |
| `__FUNCTION__.95199` | 0xf28 | 31 |
| `__FUNCTION__.95205` | 0xf48 | 27 |
| `__FUNCTION__.95213` | 0xf68 | 27 |
| `__FUNCTION__.95224` | 0xf88 | 28 |
| `__FUNCTION__.95248` | 0xfa8 | 31 |
| `__FUNCTION__.95285` | 0xfc8 | 29 |
| `__FUNCTION__.95256` | 0xfe8 | 16 |
| `__FUNCTION__.95438` | 0xff8 | 26 |
| `__FUNCTION__.95446` | 0x1018 | 25 |
| `__FUNCTION__.95455` | 0x1038 | 33 |
| `__FUNCTION__.95465` | 0x1060 | 28 |
| `__FUNCTION__.95475` | 0x1080 | 27 |
| `__FUNCTION__.95492` | 0x10a0 | 29 |
| `__FUNCTION__.95499` | 0x10c0 | 32 |
| `__FUNCTION__.95506` | 0x10e0 | 25 |
| `__FUNCTION__.95514` | 0x1100 | 21 |
| `__FUNCTION__.95536` | 0x1118 | 26 |
| `__FUNCTION__.95550` | 0x1138 | 25 |
| `__FUNCTION__.95620` | 0x1158 | 24 |
| `__FUNCTION__.95629` | 0x1170 | 24 |
| `__FUNCTION__.95577` | 0x1188 | 21 |
| `__FUNCTION__.94070` | 0x11a0 | 12 |
| `__FUNCTION__.94205` | 0x11b0 | 20 |
| `__func__.95834` | 0x11c8 | 19 |
| `__FUNCTION__.94132` | 0x11e0 | 13 |
| `__FUNCTION__.93991` | 0x11f0 | 25 |
| `__FUNCTION__.94001` | 0x1210 | 27 |
| `__FUNCTION__.93934` | 0x1230 | 24 |
| `__FUNCTION__.93970` | 0x1248 | 24 |
| `__FUNCTION__.93982` | 0x1260 | 24 |
| `__FUNCTION__.94235` | 0x1278 | 15 |
| `__FUNCTION__.95022` | 0x1288 | 16 |
| `__FUNCTION__.94221` | 0x1298 | 15 |
| `__FUNCTION__.94569` | 0x12a8 | 14 |
| `__FUNCTION__.96088` | 0x12b8 | 22 |
| `__FUNCTION__.96092` | 0x12d0 | 25 |
| `__FUNCTION__.94343` | 0x12f0 | 9 |
| `__FUNCTION__.94362` | 0x1300 | 9 |
| `__FUNCTION__.94381` | 0x1310 | 19 |
| `__FUNCTION__.94759` | 0x1328 | 11 |
| `__FUNCTION__.94483` | 0x1338 | 11 |
| `__FUNCTION__.94650` | 0x1348 | 19 |
| `__FUNCTION__.96137` | 0x1360 | 16 |
| `__FUNCTION__.96172` | 0x1370 | 19 |
| `__FUNCTION__.94723` | 0x1388 | 27 |
| `__func__.94727` | 0x13a8 | 27 |
| `__FUNCTION__.93858` | 0x13c8 | 16 |
| `__FUNCTION__.93716` | 0x13d8 | 16 |
| `__FUNCTION__.95676` | 0x13e8 | 25 |
| `__FUNCTION__.95682` | 0x1408 | 25 |
| `__FUNCTION__.94083` | 0x1428 | 15 |
| `__FUNCTION__.94283` | 0x1438 | 15 |
| `__func__.94312` | 0x1448 | 18 |
| `__FUNCTION__.94313` | 0x1460 | 18 |
| `__func__.94332` | 0x1478 | 16 |
| `__FUNCTION__.94333` | 0x1488 | 16 |
| `__FUNCTION__.96109` | 0x1498 | 22 |
| `__FUNCTION__.96116` | 0x14b0 | 18 |
| `__FUNCTION__.95690` | 0x14c8 | 32 |
| `__FUNCTION__.96221` | 0x14e8 | 23 |
| `__FUNCTION__.96234` | 0x1500 | 15 |
| `__FUNCTION__.96243` | 0x1510 | 14 |
| `__FUNCTION__.95889` | 0x1520 | 25 |
| `__FUNCTION__.95900` | 0x1540 | 19 |
| `__FUNCTION__.96270` | 0x1558 | 25 |
| `__FUNCTION__.96468` | 0x1578 | 19 |
| `__FUNCTION__.96474` | 0x1590 | 20 |
| `__FUNCTION__.96481` | 0x15a8 | 22 |
| `__FUNCTION__.96488` | 0x15c0 | 23 |
| `__FUNCTION__.96495` | 0x15d8 | 22 |
| `__FUNCTION__.96502` | 0x15f0 | 23 |
| `__FUNCTION__.96509` | 0x1608 | 18 |
| `__FUNCTION__.96516` | 0x1620 | 19 |
| `__FUNCTION__.96524` | 0x1638 | 18 |
| `__FUNCTION__.96532` | 0x1650 | 18 |
| `__FUNCTION__.96539` | 0x1668 | 22 |
| `__FUNCTION__.96547` | 0x1680 | 14 |
| `__FUNCTION__.96553` | 0x1690 | 19 |
| `__FUNCTION__.96560` | 0x16a8 | 24 |
| `__FUNCTION__.96567` | 0x16c0 | 23 |
| `__FUNCTION__.96574` | 0x16d8 | 24 |
| `__FUNCTION__.96580` | 0x16f0 | 25 |
| `__FUNCTION__.96586` | 0x1710 | 20 |
| `__FUNCTION__.96592` | 0x1728 | 22 |
| `__FUNCTION__.96615` | 0x1740 | 12 |
| `__FUNCTION__.96620` | 0x1750 | 13 |
| `__FUNCTION__.96626` | 0x1760 | 24 |
| `__FUNCTION__.67565` | 0x1b30 | 28 |
| `__FUNCTION__.67582` | 0x1bb0 | 23 |
| `__key.95767` | 0x3cd8 | 0 |
| `__key.95768` | 0x3cd8 | 0 |
| `__key.95791` | 0x3cd8 | 0 |
| `__key.95792` | 0x3cd8 | 0 |
| `__key.94488` | 0x3d10 | 0 |
| `__key.94489` | 0x3d10 | 0 |
| `__key.94490` | 0x3d10 | 0 |
| `__key.94491` | 0x3d10 | 0 |
| `__key.94492` | 0x3d10 | 0 |
| `__key.94493` | 0x3d10 | 0 |
| `__key.94494` | 0x3d10 | 0 |
| `__key.94495` | 0x3d10 | 0 |
| `__key.94496` | 0x3d10 | 0 |
| `__key.94497` | 0x3d10 | 0 |
| `__key.94498` | 0x3d10 | 0 |
| `__key.94499` | 0x3d10 | 0 |
| `__key.94500` | 0x3d10 | 0 |
| `__key.94501` | 0x3d10 | 0 |
| `__key.94502` | 0x3d10 | 0 |
| `__key.94503` | 0x3d10 | 0 |
| `__key.94504` | 0x3d10 | 0 |
| `__key.94505` | 0x3d10 | 0 |
| `__key.94506` | 0x3d10 | 0 |
| `__key.94507` | 0x3d10 | 0 |
| `__key.94508` | 0x3d10 | 0 |
| `__key.94509` | 0x3d10 | 0 |
| `__key.94510` | 0x3d10 | 0 |
| `__key.94511` | 0x3d10 | 0 |
| `__key.94512` | 0x3d10 | 0 |
| `__key.94513` | 0x3d10 | 0 |
| `__key.94514` | 0x3d10 | 0 |
| `__key.94515` | 0x3d10 | 0 |
| `__key.94516` | 0x3d10 | 0 |
| `__key.94517` | 0x3d10 | 0 |
| `__key.94518` | 0x3d10 | 0 |
| `__key.94519` | 0x3d10 | 0 |
| `__key.94520` | 0x3d10 | 0 |
| `__key.94521` | 0x3d10 | 0 |
| `__key.94522` | 0x3d10 | 0 |
| `__key.94523` | 0x3d10 | 0 |
| `__key.94526` | 0x3d10 | 0 |
| `__key.94527` | 0x3d10 | 0 |
| `__key.94530` | 0x3d10 | 0 |
| `__key.94531` | 0x3d10 | 0 |
| `__key.94534` | 0x3d10 | 0 |
| `__key.94535` | 0x3d10 | 0 |
| `sdio_dev_host` | 0x8718 | 8 |
| `__FUNCTION__.72824` | 0x9d60 | 11 |
| `__FUNCTION__.72688` | 0x9d70 | 27 |
| `__FUNCTION__.72752` | 0x9d90 | 24 |
| `__FUNCTION__.72448` | 0x9da8 | 13 |
| `__FUNCTION__.72454` | 0x9db8 | 25 |
| `__FUNCTION__.72458` | 0x9dd8 | 27 |
| `__FUNCTION__.72463` | 0x9df8 | 22 |
| `__FUNCTION__.72503` | 0x9e10 | 15 |
| `__FUNCTION__.72597` | 0x9f08 | 19 |
| `__FUNCTION__.72639` | 0x9f20 | 19 |
| `__FUNCTION__.72769` | 0x9f38 | 21 |
| `__FUNCTION__.72798` | 0x9f50 | 12 |
| `__FUNCTION__.72802` | 0x9f60 | 17 |
| `__FUNCTION__.72806` | 0x9f78 | 24 |
| `__FUNCTION__.72810` | 0x9f90 | 23 |
| `__FUNCTION__.72819` | 0x9fa8 | 25 |
| `__FUNCTION__.72432` | 0x9fe0 | 29 |
| `__FUNCTION__.72442` | 0xa000 | 13 |
| `__FUNCTION__.72574` | 0xa010 | 15 |
| `__FUNCTION__.72585` | 0xa020 | 19 |
| `__FUNCTION__.72833` | 0xa038 | 12 |
| `__FUNCTION__.72837` | 0xa048 | 11 |
| `__FUNCTION__.72540` | 0xb490 | 22 |
| `__FUNCTION__.72524` | 0xb4a8 | 19 |
| `__FUNCTION__.72569` | 0xb4c0 | 24 |
| `__FUNCTION__.72560` | 0xb4d8 | 19 |
| `__FUNCTION__.72573` | 0xb4f0 | 26 |
| `__FUNCTION__.72564` | 0xb510 | 21 |

</details>

### `/bin/camera-gui`

+0 / −0 functions · +0 / −0 objects

### `/bin/camera-test`

+0 / −0 functions · +0 / −0 objects

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

### `/bin/phocus`

+0 / −0 functions · +0 / −0 objects

### `/bin/prodconfig-tool`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/as7341.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/ask_dsp_driver.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/atmel_mxt_ts.ko`

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

### `/lib/modules/focaltp.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/ftdi_sio.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/gspca_main.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/hci_uart.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/himax_tp.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/icc_chnl.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/l3ej03110a.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/leds-pwm.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/mac80211.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/mmc_test.ko`

+0 / −0 functions · +0 / −0 objects

### `/lib/modules/proresenc_mod.ko`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **3519** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/bin/wl`

<details><summary>新增 3106 条字符串, 展示前 100 条</summary>

````text
                                      20in          20in   40in          20in   40in   80in         20in   40in   80in   160in          RU     RU     RU     RU     RU     RU
                               20in   40in   80in   160in
                               RU     RU     RU     RU     RU     RU
                             MCS 0-9 for 2 streams, and MCS 0-7 for 3 streams.
                            allocated      nmalloc      ndalloc    nrequests
                         [adapt (off | smart | strict | slow)] [lp_scan <cnt>]
                      : %-6s(%s)
                      : and optionally Nss S [1-16], eg. 5x2 is MCS=5, Nss=2
                      : and optionally Nss S [1-16], eg. c5s2 is MCS=5, Nss=2
                     ---
                0000000000000000
       (get) phy_bbmult, return format: core0_idx core1_idx core2_idx core3_idx
       (get) phy_txpwrindex, return format: core0_idx core1_idx core2_idx core3_idx
       (set) phy_forcecal <value>
      wl mkeep_alive_hist -r 1
      wl mkeep_alive_hist -r all
      wl mkeep_alive_hist -s 1
      wl mkeep_alive_hist -s 1 -n 6
    <lp_scan cnt> is 0-7
    e.g. Get 6 results of keep alive packet configured id-1:
    e.g. Get history of keep alive packet configured id-1:
    e.g. Reset all history buffer
    e.g. Reset the history buffer of keep alive packet configured id-1:
    example: 'rateset -e fff 3ff ff' limits HE rates to MCS 0-11 for 1 stream,
    example: 'rateset -t 3fff 3ff ff' limits EHT rates to MCS 0-13 for 1 stream,
   chanspec         = 0x%x
   frequency used in TxIQCAL is set to 8MHz instead of usual 4MHz
   otp_jtag_disable [1]
  %d(0x%X)
  0 - Minimum value in sec
  1 - Default value in sec
  30 - Minimum value in sec
  60 - Default value in sec
  AWAKE cnt: %llu
  AWAKE dur %llu
  AWAKE entry: %llu
  Current Time: %llu
  LP Scan count: %d
  PM cnt: %llu
  PM dur: %llu
  PM entry: %llu
  PMKID[%d]: %s = 
  [repeat <cnt>]
  band    - b|2g, a|5g, 6g
  country - two char country code
  opt.decay_time: %zd (arenas.decay_time: %zd)
  opt.junk: "%s"
  opt.lg_dirty_mult: %zd (arenas.lg_dirty_mult: %zd)
  opt.lg_prof_sample: %zd (prof.lg_sample: %zd)
  opt.narenas: %u
  opt.prof_active: %s (prof.active: %s)
  opt.prof_thread_active_init: %s (prof.thread_active_init: %s)
  opt.purge: "%s"
  time: %8u   old state: %s   new state: %s   reason: 0x%04x
 %4s:%4d:%4d
 %u ( 
 (no decay)
 -b: 2G band, -a 5G band
 -c : Interval to cache the OBSS stats in SW WD
 -c : WTC candidate AP RSSI threshold per band. order is 2g, 5g 
 -d : duration for OBSS sensing in msec
 -e : enable
 -e : enable/disable rcroam [0/1]
 -i : inactivity monitor period 
 -m : Mitigation mode
 -m : mode. 0 - Enabled. 1 to 255 - Disabled 
 -p : Interval between consecutive PM0 during mitigation period
 -p : periodic roam scan timeout 
 -passid : SAE password ID (optional)
 -s : roam trigger step value 
 -s : scan type. 0 - no scan. 1 - partial scan. 2 - Full scan
 -s num_seconds: Optional. Default = 10, Max = 60 (final value depends on driver)
 -ssid : optional SSID (optional)
 -t : Mitigation period
 -t : Test mode
 -t : WTC RSSI threshold per band. order is 2g, 5g 
 -t : roam scan timeout 
 0 - Cache disable
 0 - Disabled (default)
 0 - Stop test
 0 - Tx & Rx disabled
 0 - disabled (default)
 0 = Disable assoc mgmt logger
 1 - Enable
 1 - Minimum value in sec  (default)
 1 - Start trigger mode
 1 - Tx disabled; Enable Rx Filter override(Pkteng)
 1 = Enable association  mgmt logger
 10 - Max value in sec
 120 - Max value in sec
 16 for both cores (4350)
 16 for single core
 17 by specifying core_num followed by 8 arguments
 2 - Start Free-running
 2 - Tx enabled & Rx disabled
 2 - manually trigger a roam scan
 2 = Enable roaming mgmt logger
 2. wl sdtc config CB default 
 20%c%c: %d
 2G_CAP
````

</details>

> 其余 3006 条见 `result.json`。

### `/bin/dji_network`

<details><summary>新增 272 条字符串, 展示前 100 条</summary>

````text
%s load size is %d bytes
%s%02X%02X
%s/wms_hostapd_ctrl_%d-%d
/data/misc/wifi/sockets
/proc/net/arp
/system/etc/wms.json
/tmp/scan_all_info
/vendor/firmware/
192.168.2.1
AP-STA-CONNECTED
AP-STA-DISCONNECTED
ATTACH
Alloc file size is not matched with the expected_size
Alloc file size is not matched with the expected_size %s %zu %zu
CHANSPEC
Cannot get file size for %s
Cannot get file size.
Cannot open file %s
DETACH
File %s cur_size %zu expected_size %zu
GET_SNR
LIBC_O
LINKSPEED
LinkSpeed 
Lseek file %s failed
Mmap failed %s, error %d %s
POSTFIX_FROM_DEVICE_ID
POSTFIX_FROM_MAC
RSSI %s
Reading file %s failed
STOP_AP
__read_chk
__recvfrom_chk
__sendto_chk
__strlcpy_chk
__strncpy_chk
_bcm_init
_bcm_wifi_get_channel_idle_time
_bcm_wifi_get_link_info
_bcm_wifi_nl80211_get_lstats
_check_timeout
_create_hostapd_socket
_create_hostapd_timer_fd
_hostapd_event_handler_connected
_hostapd_event_handler_disconnected
_hostapd_monitor_recv_thread
_install_filter
_os_getip_by_mac
_send_hostapd_request
_unpack
acs_parse_channel_idle_time
auth_host_index
auth_host_type
bcm_bt_cfg
bcm_wifi_get_channel_idle_time
ble_product_id
busybox arp -an
busybox arp -n|awk '/^[1-9]/{system("arp -d "$1)}'
cJSON_AddItemReferenceToArray
cJSON_AddItemReferenceToObject
cJSON_AddItemToArray
cJSON_AddItemToObject
cJSON_AddItemToObjectCS
cJSON_CreateArray
cJSON_CreateBool
cJSON_CreateDoubleArray
cJSON_CreateFalse
cJSON_CreateFloatArray
cJSON_CreateIntArray
cJSON_CreateNull
cJSON_CreateNumber
cJSON_CreateObject
cJSON_CreateString
cJSON_CreateStringArray
cJSON_CreateTrue
cJSON_Delete
cJSON_DeleteItemFromArray
cJSON_DeleteItemFromObject
cJSON_DetachItemFromArray
cJSON_DetachItemFromObject
cJSON_Duplicate
cJSON_GetArrayItem
cJSON_GetArrayNextItem
cJSON_GetArraySize
cJSON_GetErrorPtr
cJSON_GetObjectItem
cJSON_InitHooks
cJSON_InsertItemInArray
cJSON_Minify
cJSON_Parse
cJSON_ParseWithOpts
cJSON_Print
cJSON_PrintBuffered
cJSON_PrintUnformatted
cJSON_ReplaceItemInArray
cJSON_ReplaceItemInObject
cat /tmp/channel_idle_time | busybox awk '{print $1,$14}'
cat /tmp/scan_all_info | grep -E 'freq:|signal:|channel utilisation:|station count'
channel 
def_bt_name
````

</details>

> 其余 172 条见 `result.json`。

### `/bin/bt_bsa_app`

<details><summary>新增 103 条字符串, 展示前 100 条</summary>

````text
    -t  bt bsa log level: MSG_TRACE
%s can not get %s
%s load size is %d bytes
%s: Enable:%d
%s: First host disabled channel:%d
%s: Last host disabled channel:%d
%s: RootPath:%s
%s: write xml config to %s
/system/etc/wms.json
ACL Connection Already Exists
Authentication Failure
BSA_BLE_SE_CONF_EVT status:%d, conn_id:0x%x
BSA_BLE_SE_WRITE_EVT status:%d, trans_id:%d, conn_id:%d, handle:%d, data len:%d
BSA_SEC_RSSI_EVT received for BdAddr: %02x:%02x:%02x:%02x:%02x:%02x  Link Quality: %d
BSA_SEC_RSSI_EVT received for BdAddr: %02x:%02x:%02x:%02x:%02x:%02x  RSSI: %d (dB)
BSA_SEC_RSSI_EVT received for BdAddr: %02x:%02x:%02x:%02x:%02x:%02x  RSSI: %d (dBm)
BSA_SEC_RSSI_EVT received for BdAddr: %02x:%02x:%02x:%02x:%02x:%02x  Raw RSSI: %d (dBm)
CLB Date Too Big
CLB Not Enabled
Cannot get file size for %s
Cannot open file %s
Channel Assessment Not Supported
Command Disallowed
Connection Failued to Establish
Connection Rejected No Suitable Channel Found
Connection Terminated By Local Host
Connection Terminated due to MIC Failure
Connection Timeout
Controller Busy
Different Transaction Collision
Directed Advertising Timeout
Encryption Mode Not Acceptable
Extended Inquiry Response too Large
Hardware Failure
Host Busy Pairing
Host Rejected Due To A Remote Device Only A Personal Device, Bad Addr
Host Rejected Due To Limited Resources
Host Rejected Due To Security Reasons
Host Timeout
Instant Passed
Insufficient Security
Invalid HCI Command Parameters
Invalid LMP Parameters
LMP Error Transaction Collision
LMP PDU Not Allowed
LMP Response Timeout
LT Addr Already In Use
LT Addr Not Allocated
Link Key Can Not Be Changed.
MAC Connection Failed
Max Number Of Connections
Max Number Of SCO Connections To A Device
Memory Full
Page Timeout
Pairing Not Allowed
Pairing With Unit Key Not Supported
Paramater out of Mandatory Range
Parse json file fail, please check your .json file!
Pin OR Key Missing
QOS Reject
QOS Unacceptable Parameter
QoS Not Supported
Reading file %s failed
Reason: %d (0x%x), %s
Remote Device End Terminated Connection: Low Resources
Remote Device End Terminated Connection: Remote Device Power Off
Remote Device End Terminated Connection: User Ended Connection
Repeated Attempts
Reserved 0x2B
Reserved 0x31
Reserved 0x33
Reserved Slot Violation
Role Change Not Allowed
Role Switch Failed
Role Switch Pending
SCO Air Mode Rejected
SCO Interval Rejected
SCO Offset Rejected
Simple Pairing Not Supported by Host
Success
Unacceptable Connection Parameters
Unknown Connection ID
Unknown HCI Command
Unknown LMP PDU
Unspecified Error
Unsupported Feature Or Parameter Value
Unsupported LMP Parameter
Unsupported Remote Feature
app_mgr_get_bt_config
app_mgr_read_config
app_mgr_set_bt_config
app_mgr_write_config
ble_product_id
bt_json_parse_general_info
cfg not available, recheck .json file
def_bt_name
file %s not exist !!!
general info: %s, %s(%u)
general_info
load file(%s) fail!
````

</details>

> 其余 3 条见 `result.json`。

### `/bin/camera-gui`

````text
96RCu~
;qJGaS|D
Gsaein
O/..guA
Pz-R)~
U7p*v3(V
[6jm)H2$@
jZSVvx4
o)>zC6}J{@i
````

### `/bin/msg2dbus`

````text
Client heartbeat interval: 
_ZN13QElapsedTimer10invalidateEv
_ZN13QElapsedTimer7restartEv
_ZNK13QElapsedTimer7isValidEv
````

### `/lib64/libduml_frwk.so`

````text
21:22:16
21:22:17
21:22:18
Dec 21 2022
````

### `/bin/phocus`

````text
_ZN11QTextStreamlsEl
data left:
failed to seek in::
````

### `/lib64/libduml_orte.so`

````text
21:24:44
Dec 21 2022
orte 0.3.4, compiled: Dec 21 2022 21:24:44
````

### `/lib64/libgip.so`

````text
?N3GIP10FilterPrivE
AB30RG16NV12NV16YU12YU24IMG4IMG3
N3GIP6FilterE
````

### `/bin/dji_amt`

````text
21:24:35
Dec 21 2022
````

### `/bin/dji_blackbox`

````text
21:24:37
Dec 21 2022
````

### `/bin/dji_sys`

````text
21:26:51
Dec 21 2022
````

### `/lib64/libdcam_pp.so`

````text
21:23:30
Dec 21 2022
````

### `/lib64/libproxy_nn_client.so`

````text
21:26:49
Dec 21 2022
````

### `/bin/prodconfig-tool`

````text
release_candidate/ec1706-v10.00.05-v10.00.05.53-20221118211851-27-g292cc9a1f
````

### `/lib64/librcam.so`

````text
292cc9a1f
````

### `/bin/camera-storage`

````text
````

### `/bin/camera-test`

````text
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

### `/lib/modules/focaltp.ko`

````text
````

### `/lib/modules/ftdi_sio.ko`

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

共 5 个脚本/配置变更, 68 行 unified diff（context=3, 预算上限 2000 行）。

### `/bin/start_blackbox_logs.sh`

20 行

````diff
--- a//bin/start_blackbox_logs.sh
+++ b//bin/start_blackbox_logs.sh
@@ -76,7 +76,7 @@
                                     DUSS48:I \
                                     DUSS51:I \
                                     DUSS70:I \
-                                    DUSS5C:F \
+                                    DUSS5C:I \
                                     vold:I \
                                     msg2dbus:D \
                                     phocus:D \
@@ -89,6 +89,8 @@
                                     camera-gui:D \
                                     weston:D \
                                     odindb-send:D \
+                                    hostapd \
+                                    bt_bsa_app \
                                     *:S
 
 # NOTE: The script must keep running for init service to work properly
````

### `/bin/wifi_bt_bss_mgmt.sh`

11 行

````diff
--- a//bin/wifi_bt_bss_mgmt.sh
+++ b//bin/wifi_bt_bss_mgmt.sh
@@ -196,7 +196,7 @@
         busybox sed -i "s/^country_code=.*/country_code=$4/" $BCM_WORK_CFG_PATH
     fi
 
-    hostapd -B $BCM_WORK_CFG_PATH
+    hostapd -B -ddd $BCM_WORK_CFG_PATH
 
     start_udhcpd
     echo "start hostapd and udhcpd finish"
````

### `/build.prop`

13 行

````diff
--- a//build.prop
+++ b//build.prop
@@ -1,7 +1,7 @@
 
-ro.vendor.build.date=Thu Dec 1 00:36:59 CST 2022
-ro.vendor.build.date.utc=1669826219
-ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/4766:userdebug/test-keys
+ro.vendor.build.date=Wed Dec 21 21:20:59 CST 2022
+ro.vendor.build.date.utc=1671628859
+ro.vendor.build.fingerprint=eagle2/eagle2_ec1706_native/eagle2_ec1706_native:9/PD1A.180720.031/5020:userdebug/test-keys
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
-ro.dji.build.version=10.00.05.57
+ro.dji.build.version=10.00.05.61
 persist.dji.storage.exportable=0
 ro.logd.kernel=false
 ro.logd.size.stats=64K
````

### `/firmware/nvram.txt`

13 行

````diff
--- a//firmware/nvram.txt
+++ b//firmware/nvram.txt
@@ -241,8 +241,8 @@
 epsilonoff_2g40_c1=1
 
 # energy detect threshold
-ed_thresh2g=-67
-ed_thresh5g=-67
+ed_thresh2g=-20
+ed_thresh5g=-20
 # energy detect threshold for EU
 eu_edthresh2g=-67
 eu_edthresh5g=-67
````

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（856 行）</summary>

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
| `/bin/boot_control` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395.2 KB | 395.2 KB | +0 B | system |
| `/bin/brdver_ddrtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_hwrev.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 337 B | 337 B | +0 B | system |
| `/bin/brdver_prodtype.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 386 B | 386 B | +0 B | system |
| `/bin/bsa_server` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.5 MB | 5.5 MB | +0 B | system |
| `/bin/bt_bsa_app` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 202.4 KB | 202.5 KB | +112 B | system |
| `/bin/btt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 952.4 KB | 952.4 KB | +0 B | system |
| `/bin/bulk` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.9 KB | 84.9 KB | +0 B | system |
| `/bin/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.2 KB | 7.2 KB | +0 B | system |
| `/bin/c2d_ut` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.5 KB | 67.5 KB | +0 B | system |
| `/bin/calib-tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/cam_dt_cmdline` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/cam_log_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | system |
| `/bin/camera-expose` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 MB | 2.1 MB | +0 B | system |
| `/bin/camera-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 36.8 MB | 36.8 MB | +0 B | system |
| `/bin/camera-service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.5 MB | 9.5 MB | +0 B | system |
| `/bin/camera-storage` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.5 MB | 3.5 MB | -168 B | system |
| `/bin/camera-system` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 MB | 7.6 MB | +0 B | system |
| `/bin/camera-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.6 MB | 2.6 MB | +0 B | system |
| `/bin/camera-upgrade` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.8 MB | 1.8 MB | +0 B | system |
| `/bin/cat_wifi_param.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/check_and_format.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 702 B | 702 B | +0 B | system |
| `/bin/check_secure_debug` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/bin/cmd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/codec_yuv_generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/collect_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 KB | 5.8 KB | +0 B | system |
| `/bin/copy_script_files` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | system |
| `/bin/copy_script_files_self_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | system |
| `/bin/coredump_monitor` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/cpu_dvfs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 KB | 5.8 KB | +0 B | system |
| `/bin/cpu_hotplug.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 844 B | 844 B | +0 B | system |
| `/bin/crash_dump64` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.3 KB | 133.3 KB | +0 B | system |
| `/bin/create_partition.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.7 KB | 4.7 KB | +0 B | system |
| `/bin/data_fsck.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/dbus-daemon` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 MB | 1.3 MB | +0 B | system |
| `/bin/dbus-send` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/debuggerd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/devpd_ctrl.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/dhd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 394.0 KB | 394.0 KB | +0 B | system |
| `/bin/dji_amt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 79.4 KB | 79.4 KB | +0 B | system |
| `/bin/dji_audio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/dji_blackbox` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 337.8 KB | 337.8 KB | +16 B | system |
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
| `/bin/dji_network` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 213.8 KB | 278.4 KB | +64.6 KB | system |
| `/bin/dji_production_check_h26x.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | system |
| `/bin/dji_sec` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 72.8 KB | 72.8 KB | +0 B | system |
| `/bin/dji_sn_ops.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 497 B | 497 B | +0 B | system |
| `/bin/dji_sw_uav` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.6 KB | 68.6 KB | +0 B | system |
| `/bin/dji_sys` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 876.8 KB | 876.8 KB | +16 B | system |
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
| `/bin/flatc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 391.9 KB | 391.9 KB | +0 B | system |
| `/bin/hex-writer` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 MB | 1.3 MB | +0 B | system |
| `/bin/hostapd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 786.2 KB | 786.2 KB | +0 B | system |
| `/bin/ibistool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 541.2 KB | 541.2 KB | +0 B | system |
| `/bin/imgtool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 319.1 KB | 319.1 KB | +0 B | system |
| `/bin/imx461_bridge_voltages.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.3 KB | 3.3 KB | +0 B | system |
| `/bin/imx461_gpio_enable.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/bin/imx461tool` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/inject-keypress` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 84.4 KB | 84.4 KB | +0 B | system |
| `/bin/input-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.5 KB | 131.5 KB | +0 B | system |
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
| `/bin/monkey-test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.5 KB | 73.5 KB | +0 B | system |
| `/bin/mount_block_ext4.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/mpstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 750.2 KB | 750.2 KB | +0 B | system |
| `/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.4 MB | 2.4 MB | +152 B | system |
| `/bin/nnf_gtest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 525.3 KB | 525.3 KB | +0 B | system |
| `/bin/odin-output` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 133.6 KB | 133.6 KB | +0 B | system |
| `/bin/odindb-send` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 MB | 3.4 MB | +0 B | system |
| `/bin/ota.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/perf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 MB | 8.3 MB | +0 B | system |
| `/bin/phocus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.1 MB | 3.1 MB | +40 B | system |
| `/bin/pidstat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 867.0 KB | 867.0 KB | +0 B | system |
| `/bin/ping` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/pinmux` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.3 KB | 131.3 KB | +0 B | system |
| `/bin/proc_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 317.9 KB | 317.9 KB | +0 B | system |
| `/bin/program_nodes.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
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
| `/bin/start_blackbox_logs.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.2 KB | 3.2 KB | +95 B | system |
| `/bin/start_dji_camera.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 80 B | 80 B | +0 B | system |
| `/bin/start_dji_system.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.5 KB | 5.5 KB | +0 B | system |
| `/bin/start_hbl_test_mode.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 655 B | 655 B | +0 B | system |
| `/bin/start_touchtest.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 362 B | 362 B | +0 B | system |
| `/bin/start_wifi.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 853 B | 853 B | +0 B | system |
| `/bin/start_wifi_factory.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 193 B | 193 B | +0 B | system |
| `/bin/storage_io` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/storage_tracing` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/store-log-encrypted` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/strace` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 MB | 1.0 MB | +0 B | system |
| `/bin/stress_test_mb_benchmark_local` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 78.8 KB | 78.8 KB | +0 B | system |
| `/bin/stress_test_mb_publish_local` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.9 KB | 72.9 KB | +0 B | system |
| `/bin/stress_test_osal_msgq` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/bin/sync_time.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 496 B | 496 B | +0 B | system |
| `/bin/sysmode_client` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/bin/sysmode_test` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/system_suspend_resume.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 341 B | 341 B | +0 B | system |
| `/bin/system_suspend_rtc_resume.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 672 B | 672 B | +0 B | system |
| `/bin/tcp_server` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/tee-supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/temperature_get_e2.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 958 B | 958 B | +0 B | system |
| `/bin/test_accelerometer_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 754 B | 754 B | +0 B | system |
| `/bin/test_ael_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 768 B | 768 B | +0 B | system |
| `/bin/test_af_mf_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 874 B | 874 B | +0 B | system |
| `/bin/test_afd_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 711 B | 711 B | +0 B | system |
| `/bin/test_apu_cap` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/test_apu_play` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/test_audio` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.9 KB | 67.9 KB | +0 B | system |
| `/bin/test_audio_client` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.6 KB | 67.6 KB | +0 B | system |
| `/bin/test_audio_service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
| `/bin/test_back_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 920 B | 920 B | +0 B | system |
| `/bin/test_back_thumbwheel_press_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 782 B | 782 B | +0 B | system |
| `/bin/test_battery_charger_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_battery_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 722 B | 722 B | +0 B | system |
| `/bin/test_blackbox_size.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_bulk_xfer.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/test_button_backlight_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/bin/test_cam` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 134.0 KB | 134.0 KB | +0 B | system |
| `/bin/test_cfexpress_card_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 622 B | 622 B | +0 B | system |
| `/bin/test_check_battery_level.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 841 B | 841 B | +0 B | system |
| `/bin/test_check_ibis_calib_status.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_check_versions.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 KB | 1.1 KB | +0 B | system |
| `/bin/test_cnn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/test_common.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | system |
| `/bin/test_common_disk.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/test_ddr_e2.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.9 KB | 5.9 KB | +0 B | system |
| `/bin/test_ddr_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 695 B | 695 B | +0 B | system |
| `/bin/test_disp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 134.2 KB | 134.2 KB | +0 B | system |
| `/bin/test_display1_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 720 B | 720 B | +0 B | system |
| `/bin/test_display2_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 720 B | 720 B | +0 B | system |
| `/bin/test_display3_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 720 B | 720 B | +0 B | system |
| `/bin/test_display4_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 720 B | 720 B | +0 B | system |
| `/bin/test_dji_cht.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 771 B | 771 B | +0 B | system |
| `/bin/test_dji_cst_perf.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 674 B | 674 B | +0 B | system |
| `/bin/test_dsp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 396.0 KB | 396.0 KB | +0 B | system |
| `/bin/test_dsp2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.9 KB | 67.9 KB | +0 B | system |
| `/bin/test_ec1706_basic_exposure.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | system |
| `/bin/test_ec1706_basic_liveview.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
| `/bin/test_ec1706_collect_logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/test_ec1706_collect_logs_nightly.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.2 KB | 5.2 KB | +0 B | system |
| `/bin/test_ec1706_common.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | system |
| `/bin/test_ec1706_f2f.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.9 KB | 12.9 KB | +0 B | system |
| `/bin/test_ec1706_frame_dump.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 KB | 5.8 KB | +0 B | system |
| `/bin/test_ec1706_interval_exposure.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/bin/test_ec1706_long_exposure.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.9 KB | 2.9 KB | +0 B | system |
| `/bin/test_ec1706_mf_zoom.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | system |
| `/bin/test_ec1706_raw_playback.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.2 KB | 3.2 KB | +0 B | system |
| `/bin/test_ec1706_reset_all_settings.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | system |
| `/bin/test_ec1706_rtc_offset.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
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
| `/bin/test_exposure_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 895 B | 895 B | +0 B | system |
| `/bin/test_flash_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 693 B | 693 B | +0 B | system |
| `/bin/test_format_ssd.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 688 B | 688 B | +0 B | system |
| `/bin/test_front_thumbwheel_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 929 B | 929 B | +0 B | system |
| `/bin/test_get_serial.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 901 B | 901 B | +0 B | system |
| `/bin/test_gpu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.1 MB | 7.1 MB | +0 B | system |
| `/bin/test_grip_down_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 729 B | 729 B | +0 B | system |
| `/bin/test_grip_up_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 727 B | 727 B | +0 B | system |
| `/bin/test_hal_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/test_hal_storage` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/test_hotshoe` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.9 KB | 131.9 KB | +0 B | system |
| `/bin/test_imu_fpc_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_iso_wb_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 715 B | 715 B | +0 B | system |
| `/bin/test_joystick_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 978 B | 978 B | +0 B | system |
| `/bin/test_lcd_backlight_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 794 B | 794 B | +0 B | system |
| `/bin/test_lcd_module_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 755 B | 755 B | +0 B | system |
| `/bin/test_lens_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | system |
| `/bin/test_light_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 940 B | 940 B | +0 B | system |
| `/bin/test_m_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 808 B | 808 B | +0 B | system |
| `/bin/test_mem` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/test_mic_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.4 KB | 2.4 KB | +0 B | system |
| `/bin/test_mipi_lvds_bridge_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/test_pm.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.2 KB | 6.2 KB | +0 B | system |
| `/bin/test_power_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 724 B | 724 B | +0 B | system |
| `/bin/test_proximity_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 KB | 2.3 KB | +0 B | system |
| `/bin/test_proximity_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 960 B | 960 B | +0 B | system |
| `/bin/test_rtc_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/bin/test_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/bin/test_set_serial.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/bin/test_sgbm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 68.5 KB | 68.5 KB | +0 B | system |
| `/bin/test_spectral_sensor_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 729 B | 729 B | +0 B | system |
| `/bin/test_spi` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/test_spk_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/bin/test_spk_mic_stop.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 955 B | 955 B | +0 B | system |
| `/bin/test_ssd_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 622 B | 622 B | +0 B | system |
| `/bin/test_stepper_motor_ctrl_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 846 B | 846 B | +0 B | system |
| `/bin/test_stop_down_button_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 729 B | 729 B | +0 B | system |
| `/bin/test_system_suspend_resume.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.6 KB | 4.6 KB | +0 B | system |
| `/bin/test_top_lcd_function.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | system |
| `/bin/test_touch_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 767 B | 767 B | +0 B | system |
| `/bin/test_usb_link.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 746 B | 746 B | +0 B | system |
| `/bin/test_vcr` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/bin/test_venc_e2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.5 KB | 67.5 KB | +0 B | system |
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
| `/bin/unrd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/usb_bulk_raw` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/usb_bulk_raw_hbl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/bin/usb_bulk_xfer_test_v2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.1 KB | 67.1 KB | +0 B | system |
| `/bin/vold` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 913.8 KB | 913.8 KB | +0 B | system |
| `/bin/vold_prepare_subdirs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.4 KB | 67.4 KB | +0 B | system |
| `/bin/vold_test.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/wait_for_keymaster` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/bin/weston` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 458.5 KB | 458.5 KB | +0 B | system |
| `/bin/wifi_bt_bss_mgmt.sh` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 29.3 KB | 29.4 KB | +5 B | system |
| `/bin/wifi_download_opt.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | system |
| `/bin/wifi_user_config.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.8 KB | 3.8 KB | +0 B | system |
| `/bin/wl` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.4 MB | 2.2 MB | -3.2 MB | system |
| `/bin/x2bursttest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/bin/x2d_cal_eng_googletest` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 265.2 KB | 265.2 KB | +0 B | system |
| `/bin/x2loopback` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.2 KB | 67.2 KB | +0 B | system |
| `/bin/x2pingpong` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/build.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 KB | 1.9 KB | +0 B | system/vendor |
| `/compatibility_matrix.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 99.7 KB | 99.7 KB | +0 B | system |
| `/default.prop` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 237 B | 237 B | +0 B | vendor |
| `/etc/NOTICE.xml.gz` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 94.3 KB | 94.3 KB | +0 B | system/vendor |
| `/etc/VERSION` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6 B | 6 B | +0 B | system |
| `/etc/ac_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 859 B | 859 B | +0 B | system |
| `/etc/adj/adj_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323 B | 323 B | +0 B | system |
| `/etc/adj/grain_param_461.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.8 KB | 2.8 KB | +0 B | system |
| `/etc/adj/rdns_param_461.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | system |
| `/etc/audio.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | system |
| `/etc/blackbox.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 590 B | 590 B | +0 B | system |
| `/etc/cam_log_format.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | system |
| `/etc/cam_log_strategy.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.6 KB | 2.6 KB | +0 B | system |
| `/etc/cht_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/etc/cht_cases_quick.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39 B | 39 B | +0 B | system |
| `/etc/copy_ci_list` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 839 B | 839 B | +0 B | system |
| `/etc/cst_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 250 B | 250 B | +0 B | system |
| `/etc/cst_cases_quick.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26 B | 26 B | +0 B | system |
| `/etc/dbus.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/dds.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 973 B | 973 B | +0 B | system |
| `/etc/device_table.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 535 B | 535 B | +0 B | system |
| `/etc/dji.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.5 KB | 53.5 KB | +0 B | system |
| `/etc/dji_camera.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.9 KB | 19.9 KB | +0 B | system |
| `/etc/dji_camera.tsf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 772 B | 772 B | +0 B | system |
| `/etc/dji_camera_imx461bqr.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 93 B | 93 B | +0 B | system |
| `/etc/dji_dc_ecc_public_key.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33 B | 33 B | +0 B | system |
| `/etc/dspf/json/dspf_icc_chnl_cfg.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.5 KB | 3.5 KB | +0 B | system |
| `/etc/event-log-tags` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/fbuf_test.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48 B | 48 B | +0 B | system |
| `/etc/file_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.6 KB | 37.6 KB | +0 B | vendor |
| `/etc/firmware/aw87519_drcv.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | system |
| `/etc/firmware/aw87519_hvload.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | system |
| `/etc/firmware/aw87519_kspk.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42 B | 42 B | +0 B | system |
| `/etc/firmware/ccg3_2.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 106.9 KB | 106.9 KB | +0 B | system |
| `/etc/firmware/exMCU.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | system |
| `/etc/firmware/exMCUloader.cont` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 14.6 KB | 14.6 KB | +0 B | system |
| `/etc/firmware/rgx.fw.24.66.54.204` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 204.0 KB | 204.0 KB | +0 B | system |
| `/etc/firmware/rgx.sh.24.66.54.204` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 162.1 KB | 162.1 KB | +0 B | system |
| `/etc/fstab.eagle2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | vendor |
| `/etc/hostapd.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 315 B | 315 B | +0 B | system |
| `/etc/hosts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 56 B | 56 B | +0 B | system |
| `/etc/imx461bqr_ec1706.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.9 KB | 48.9 KB | +0 B | system |
| `/etc/imx461bqr_ec1706.sp` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44.9 KB | 44.9 KB | +0 B | system |
| `/etc/init/camera-gui.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 881 B | 881 B | +0 B | system |
| `/etc/init/camera-service.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 126 B | 126 B | +0 B | system |
| `/etc/init/camera-storage.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 110 B | 110 B | +0 B | system |
| `/etc/init/camera-system.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 527 B | 527 B | +0 B | system |
| `/etc/init/camera-test.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 88 B | 88 B | +0 B | system |
| `/etc/init/camera-upgrade.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 126 B | 126 B | +0 B | system |
| `/etc/init/dbus.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 235 B | 235 B | +0 B | system |
| `/etc/init/dji_amt.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 190 B | 190 B | +0 B | system |
| `/etc/init/dji_audio.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 202 B | 202 B | +0 B | system |
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
| `/etc/init/phocus.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 78 B | 78 B | +0 B | system |
| `/etc/init/servicemanager.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 520 B | 520 B | +0 B | system |
| `/etc/init/test-mode.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 188 B | 188 B | +0 B | system |
| `/etc/init/tombstoned.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 399 B | 399 B | +0 B | system |
| `/etc/init/vold.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 360 B | 360 B | +0 B | system |
| `/etc/init/wait_for_keymaster.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 127 B | 127 B | +0 B | system |
| `/etc/init/weston.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 110 B | 110 B | +0 B | system |
| `/etc/iq/config.fbs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.3 KB | 276.3 KB | +0 B | system |
| `/etc/iq/dji_rcam.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 139 B | 139 B | +0 B | system |
| `/etc/iq/ec1706_config.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.3 MB | 2.3 MB | +0 B | system |
| `/etc/iq/ec1706_config.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.6 MB | 6.6 MB | +0 B | system |
| `/etc/microphone.apu` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.0 KB | 4.0 KB | +0 B | system |
| `/etc/mke2fs.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | system |
| `/etc/mkshrc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.2 KB | 2.2 KB | +0 B | system |
| `/etc/ml/afc_tracking.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.9 KB | 3.9 KB | +0 B | vendor |
| `/etc/ml/cnntk.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 KB | 1.7 KB | +0 B | vendor |
| `/etc/ml/dynamic_roi.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 832 B | 832 B | +0 B | vendor |
| `/etc/ml/e2_udp.prototxt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263 B | 263 B | +0 B | system |
| `/etc/ml/gtest_params.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 413 B | 413 B | +0 B | system |
| `/etc/ml/vpf_cfg.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.0 KB | 6.0 KB | +0 B | vendor |
| `/etc/ml/vpf_cfg_gtest.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.4 KB | 2.4 KB | +0 B | vendor |
| `/etc/ml/vpf_storage.json.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 KB | 1.6 KB | +0 B | vendor |
| `/etc/ml/wm260_master.prototxt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 273 B | 273 B | +0 B | system |
| `/etc/mount/init.mount.rc` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.5 KB | 1.5 KB | +0 B | system |
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
| `/etc/plugins.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 24.0 KB | 24.0 KB | +0 B | system |
| `/etc/powervr.ini` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41 B | 41 B | +0 B | system |
| `/etc/ppt_cases.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 187 B | 187 B | +0 B | system |
| `/etc/pre_insmod_tab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 288 B | 288 B | +0 B | system |
| `/etc/process.json` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.6 KB | 3.6 KB | +0 B | system |
| `/etc/prop.default` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 500 B | 501 B | +1 B | system |
| `/etc/recovery.fstab` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 970 B | 970 B | +0 B | system |
| `/etc/security/otacerts.zip` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 KB | 1.0 KB | +0 B | system |
| `/etc/selftests` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 839 B | 839 B | +0 B | system |
| `/etc/selinux/mapping/28.0.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 123.3 KB | 123.3 KB | +0 B | system |
| `/etc/selinux/plat_and_mapping_sepolicy.cil.sha256` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65 B | 65 B | +0 B | system |
| `/etc/selinux/plat_file_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.2 KB | 23.2 KB | +0 B | system |
| `/etc/selinux/plat_hwservice_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.0 KB | 7.0 KB | +0 B | system |
| `/etc/selinux/plat_mac_permissions.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.9 KB | 4.9 KB | +0 B | system |
| `/etc/selinux/plat_property_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | system |
| `/etc/selinux/plat_pub_versioned.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 708.7 KB | 708.7 KB | +0 B | vendor |
| `/etc/selinux/plat_seapp_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 KB | 1.3 KB | +0 B | system |
| `/etc/selinux/plat_sepolicy.cil` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/etc/selinux/plat_sepolicy_vers.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5 B | 5 B | +0 B | vendor |
| `/etc/selinux/plat_service_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.2 KB | 14.2 KB | +0 B | system |
| `/etc/selinux/precompiled_sepolicy` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 430.6 KB | 430.6 KB | +12 B | vendor |
| `/etc/selinux/precompiled_sepolicy.plat_and_mapping.sha256` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65 B | 65 B | +0 B | vendor |
| `/etc/selinux/selinux_denial_metadata` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 KB | 1.8 KB | +0 B | system |
| `/etc/selinux/vendor_file_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.8 KB | 10.8 KB | +0 B | vendor |
| `/etc/selinux/vendor_hwservice_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | vendor |
| `/etc/selinux/vendor_mac_permissions.xml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101 B | 101 B | +0 B | vendor |
| `/etc/selinux/vendor_property_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 328 B | 328 B | +0 B | vendor |
| `/etc/selinux/vendor_seapp_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | vendor |
| `/etc/selinux/vendor_sepolicy.cil` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 193.9 KB | 193.8 KB | -175 B | vendor |
| `/etc/selinux/vndservice_contexts` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65 B | 65 B | +0 B | vendor |
| `/etc/sepolicy.dbg` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 433.7 KB | 433.7 KB | +12 B | system |
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
| `/etc/wms.json` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 497 B | +497 B | system |
| `/etc/xtables.lock` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | system |
| `/firmware/43456-sdio-mfg.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 760.4 KB | 760.4 KB | +0 B | vendor |
| `/firmware/BCM43752_001.003.006.0035.0045.hcd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 73.6 KB | 73.6 KB | +0 B | vendor |
| `/firmware/clm_bcm43752a2_ag.blob` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.4 KB | 28.4 KB | +0 B | vendor |
| `/firmware/config.txt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 325 B | 325 B | +0 B | vendor |
| `/firmware/dspf/ss_dsp0.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.4 MB | 1.4 MB | +0 B | vendor |
| `/firmware/dspf/ss_dsp0.lin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 173.5 KB | 173.5 KB | +0 B | vendor |
| `/firmware/dspf/ss_dsp1.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | vendor |
| `/firmware/dspf/ss_dsp1.lin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 173.5 KB | 173.5 KB | +0 B | vendor |
| `/firmware/dspf/ss_dsp2.fw` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.2 MB | 1.2 MB | +0 B | vendor |
| `/firmware/dspf/ss_dsp2.lin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 173.5 KB | 173.5 KB | +0 B | vendor |
| `/firmware/fw_bcm43752a2_ag.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 691.4 KB | 691.4 KB | +0 B | vendor |
| `/firmware/nvram.txt` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.7 KB | 9.7 KB | +0 B | vendor |
| `/lib/modules/as7341.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 323.7 KB | 323.7 KB | +0 B | system |
| `/lib/modules/ask_dsp_driver.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 627.2 KB | 627.2 KB | +0 B | system |
| `/lib/modules/atmel_mxt_ts.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 411.9 KB | 411.9 KB | +0 B | system |
| `/lib/modules/bcmdhd.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | -2.0 KB | system |
| `/lib/modules/bluetooth.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.4 MB | 7.4 MB | +0 B | system |
| `/lib/modules/cam_vreg.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 37.5 KB | 37.5 KB | +0 B | system |
| `/lib/modules/camecg_drv.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 355.5 KB | 355.5 KB | +0 B | system |
| `/lib/modules/cfg80211.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.3 MB | 7.3 MB | +0 B | system |
| `/lib/modules/designware_i2s.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 347.1 KB | 347.1 KB | +0 B | system |
| `/lib/modules/dji-spinor.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 274.4 KB | 274.4 KB | +0 B | system |
| `/lib/modules/dji_dw_hdmi_i2s_audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 373.7 KB | 373.7 KB | +0 B | system |
| `/lib/modules/dji_j2kcodec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 619.8 KB | 619.8 KB | +0 B | system |
| `/lib/modules/dji_jpegxrcodec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 279.7 KB | 279.7 KB | +0 B | system |
| `/lib/modules/dji_ljcodec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 552.2 KB | 552.2 KB | +0 B | system |
| `/lib/modules/dji_mctf.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 125.0 KB | 125.0 KB | +0 B | system |
| `/lib/modules/dji_msdec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 410.7 KB | 410.7 KB | +0 B | system |
| `/lib/modules/dji_msenc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 279.8 KB | 279.8 KB | +0 B | system |
| `/lib/modules/dji_proresDec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 276.3 KB | 276.3 KB | +0 B | system |
| `/lib/modules/dji_proresEnc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 702.7 KB | 702.7 KB | +0 B | system |
| `/lib/modules/dji_ycc.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 65.9 KB | 65.9 KB | +0 B | system |
| `/lib/modules/dwc_eth_qos.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 540.9 KB | 540.9 KB | +0 B | system |
| `/lib/modules/dwmac-dwc-qos-eth.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 309.6 KB | 309.6 KB | +0 B | system |
| `/lib/modules/e1000e.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.9 MB | 3.9 MB | +0 B | system |
| `/lib/modules/eagle_dsp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 559.1 KB | 559.1 KB | +0 B | system |
| `/lib/modules/ecx337aa.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 272.2 KB | 272.2 KB | +0 B | system |
| `/lib/modules/focaltp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/ftdi_sio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 503.8 KB | 503.8 KB | +0 B | system |
| `/lib/modules/gspca_main.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 622.0 KB | 622.0 KB | +0 B | system |
| `/lib/modules/hci_uart.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib/modules/himax_tp.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib/modules/icc_chnl.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib/modules/l3ej03110a.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 274.9 KB | 274.9 KB | +0 B | system |
| `/lib/modules/leds-pwm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 239.1 KB | 239.1 KB | +0 B | system |
| `/lib/modules/mac80211.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.1 MB | 20.1 MB | +0 B | system |
| `/lib/modules/mmc_test.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 511.5 KB | 511.5 KB | +0 B | system |
| `/lib/modules/proresenc_mod.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 273.9 KB | 273.9 KB | +0 B | system |
| `/lib/modules/pvrsrvkm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.2 MB | 2.2 MB | +0 B | system |
| `/lib/modules/r8152.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 646.8 KB | 646.8 KB | +0 B | system |
| `/lib/modules/realtek.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 248.1 KB | 248.1 KB | +0 B | system |
| `/lib/modules/snd-hwdep.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 294.6 KB | 294.6 KB | +0 B | system |
| `/lib/modules/snd-rawmidi.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 403.9 KB | 403.9 KB | +0 B | system |
| `/lib/modules/snd-soc-ak5522.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 350.4 KB | 350.4 KB | +0 B | system |
| `/lib/modules/snd-soc-ak7755.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 525.0 KB | 525.0 KB | +0 B | system |
| `/lib/modules/snd-soc-aw87519.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 350.4 KB | 350.4 KB | +0 B | system |
| `/lib/modules/snd-soc-cs47l35.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.1 MB | 2.1 MB | +0 B | system |
| `/lib/modules/snd-soc-dji-dummy-codec.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 273.6 KB | 273.6 KB | +0 B | system |
| `/lib/modules/snd-soc-nau8821.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 428.1 KB | 428.1 KB | +0 B | system |
| `/lib/modules/snd-soc-nau8825.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 409.7 KB | 409.7 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card-utils.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 284.4 KB | 284.4 KB | +0 B | system |
| `/lib/modules/snd-soc-simple-card.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 339.0 KB | 339.0 KB | +0 B | system |
| `/lib/modules/snd-soc-tlv320aic31xx.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 380.9 KB | 380.9 KB | +0 B | system |
| `/lib/modules/snd-usb-audio.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.5 MB | 2.5 MB | +0 B | system |
| `/lib/modules/snd-usbmidi-lib.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 337.5 KB | 337.5 KB | +0 B | system |
| `/lib/modules/tc358749.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 554.6 KB | 554.6 KB | +0 B | system |
| `/lib/modules/test_bitmap.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 188.2 KB | 188.2 KB | +0 B | system |
| `/lib/modules/test_bpf.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/test_firmware.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.7 KB | 218.7 KB | +0 B | system |
| `/lib/modules/test_printf.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 193.7 KB | 193.7 KB | +0 B | system |
| `/lib/modules/test_static_key_base.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 158.8 KB | 158.8 KB | +0 B | system |
| `/lib/modules/test_static_keys.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 169.9 KB | 169.9 KB | +0 B | system |
| `/lib/modules/test_user_copy.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 184.4 KB | 184.4 KB | +0 B | system |
| `/lib/modules/vc_decoder.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 396.0 KB | 396.0 KB | +0 B | system |
| `/lib/modules/vc_encoder.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 433.9 KB | 433.9 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_h26x_core0.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 232.2 KB | 232.2 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_h26x_core1.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 232.2 KB | 232.2 KB | +0 B | system |
| `/lib/modules/vc_encoder_pm_jpeg.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 242.4 KB | 242.4 KB | +0 B | system |
| `/lib/modules/vcam_driver.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.7 MB | 1.7 MB | +0 B | system |
| `/lib/modules/vision_cnn.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 588.1 KB | 588.1 KB | +0 B | system |
| `/lib/modules/vision_sgbm.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 415.0 KB | 415.0 KB | +0 B | system |
| `/lib/modules/vision_vcr.ko` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 590.5 KB | 590.5 KB | +0 B | system |
| `/lib64/android.hardware.keymaster@3.0.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.2 KB | 198.2 KB | +0 B | system |
| `/lib64/android.hardware.keymaster@4.0.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 198.9 KB | 198.9 KB | +0 B | system |
| `/lib64/camera/plugins/2d/libdcam_2d_hw.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/2d/libdcam_null_2d.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/adj/libdcam_cp_adj.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 140.9 KB | 140.9 KB | +0 B | system |
| `/lib64/camera/plugins/dewarp/libdcam_dewarp_gdc_stitching.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 195.5 KB | 195.5 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_e2_lcdc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 135.1 KB | 135.1 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_null.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/disp/libdcam_disp_wayland.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 197.4 KB | 197.4 KB | +0 B | system |
| `/lib64/camera/plugins/hal/libdcam_cam_info_e2_ec1706_native.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 136.6 KB | 136.6 KB | +0 B | system |
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
| `/lib64/camera/plugins/stream_filter/libdcam_dsp_allocator_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.3 KB | 67.3 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_isp_statistics_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.0 KB | 67.0 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_pdaf_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_pp_algo_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_reawb_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.0 KB | 131.0 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_stats_packer_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.8 KB | 66.8 KB | +0 B | system |
| `/lib64/camera/plugins/stream_filter/libdcam_x2d_ml_stream_filter.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 67.7 KB | 67.7 KB | +0 B | system |
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
| `/lib64/libMessageTransport.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libQt6Concurrent.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libQt6Core.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.8 MB | 5.8 MB | +0 B | system |
| `/lib64/libQt6DBus.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 800.3 KB | 800.3 KB | +0 B | system |
| `/lib64/libQt6Network.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.3 MB | 1.3 MB | +0 B | system |
| `/lib64/libQt6SerialPort.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 135.5 KB | 135.5 KB | +0 B | system |
| `/lib64/libQt6StateMachine.so.6` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 333.7 KB | 333.7 KB | +0 B | system |
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
| `/lib64/libaaa.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.6 MB | 6.6 MB | +0 B | system |
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
| `/lib64/libavformat.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 464.6 KB | 464.6 KB | +0 B | system |
| `/lib64/libavutil.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 323.5 KB | 323.5 KB | +0 B | system |
| `/lib64/libbacktrace.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.5 KB | 131.5 KB | +0 B | system |
| `/lib64/libbase.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 131.8 KB | 131.8 KB | +0 B | system |
| `/lib64/libbinder.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 584.4 KB | 584.4 KB | +0 B | system |
| `/lib64/libc++.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 905.1 KB | 905.1 KB | +0 B | system |
| `/lib64/libc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.1 MB | 1.1 MB | +0 B | system |
| `/lib64/libcam_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libcap.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.9 KB | 66.9 KB | +0 B | system |
| `/lib64/libclang_rt.asan-aarch64-android.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 790.2 KB | 790.2 KB | +0 B | system |
| `/lib64/libcnntk_cbb.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 818.6 KB | 818.6 KB | +0 B | system |
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
| `/lib64/libdcam_fcali.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 643.3 KB | 643.3 KB | +0 B | system |
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
| `/lib64/libdcam_pp.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.0 MB | 2.0 MB | -8 B | system |
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
| `/lib64/libduml_hal_cam.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 740.3 KB | 740.3 KB | +0 B | system |
| `/lib64/libduml_orte.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 194.2 KB | 194.2 KB | +0 B | system |
| `/lib64/libduml_osal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.4 KB | 66.4 KB | +0 B | system |
| `/lib64/libduml_payload.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libduml_rpc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
| `/lib64/libduml_shineIO.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 130.8 KB | 130.8 KB | +0 B | system |
| `/lib64/libduml_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 517.4 KB | 517.4 KB | +0 B | system |
| `/lib64/libduml_vcodec.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 324.1 KB | 324.1 KB | +0 B | system |
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
| `/lib64/libfg_pm.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libfw_util.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libfw_util_ca.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.5 KB | 66.5 KB | +0 B | system |
| `/lib64/libgip.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 196.7 KB | 196.8 KB | +40 B | system |
| `/lib64/libglslcompiler.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 MB | 1.6 MB | +0 B | system |
| `/lib64/libhardware.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.6 KB | 66.6 KB | +0 B | system |
| `/lib64/libhardware_legacy.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 66.7 KB | 66.7 KB | +0 B | system |
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
| `/lib64/librcam.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.6 MB | 2.6 MB | -40 B | system |
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
| `/lib64/libwayland-cursor.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 80.1 KB | 80.1 KB | +0 B | system |
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
| `/model/ml/ec1706.prototxt.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.4 KB | 4.4 KB | +0 B | vendor |
| `/model/ml/faceEye.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 790.2 KB | 790.2 KB | +0 B | vendor |
| `/model/ml/search.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.1 MB | 5.1 MB | +0 B | vendor |
| `/model/ml/template.tflite.eng.enc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.9 MB | 4.9 MB | +0 B | vendor |
| `/product/build.prop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37 B | 37 B | +0 B | system |
| `/recovery-from-boot.p` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.8 MB | 2.8 MB | +222 B | system |
| `/ta/09db16c0-873b-4fed-b87ea5d2b86293a2.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 194.5 KB | 194.5 KB | +0 B | vendor |
| `/ta/e91c9402-64a0-470f-88e7bf5d3c606b6a.ta` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 229.1 KB | 229.1 KB | +0 B | vendor |
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
