# X1D-50c: 1.20.0 ➜ 1.20.1

> 生成时间: 2026-10-07T06:05:53 · CIM 日期: 2017-12-13 ➜ 2018-01-17 · 条目: 4 ➜ 4 · 源: `X1D_v1_20_0.cim` ➜ `X1D_v1_20_1.cim`

## Summary

文件树 +82/-82/~245；CIM 条目 +0/-0/~1；OTA 镜像 ~0 变更 / 0 未变；符号 +2/-0 funcs, +0/-0 objs；新增字符串 1727 条。

## CIM Items

| Name | Status | Old Size | New Size | Δ |
|---|---|---|---|---|
| `rootfs` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 56.4 MB | 56.3 MB | -22.9 KB |
| `hbl-kks-revisions` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B |
| `hbl-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.6 KB | 7.6 KB | +0 B |
| `uboot` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 263.0 KB | 263.0 KB | +0 B |

> ![ADDED](https://img.shields.io/badge/-ADDED-green) 0 · ![REMOVED](https://img.shields.io/badge/-REMOVED-red) 0 · ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) 1 · ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) 3

## OTA Images

共 0 个条目, 无增删改。

## Filesystem

按顶层目录聚合：

| Top Dir | ADDED | REMOVED | CHANGED | UNCHANGED | SUSPECT |
|---|---|---|---|---|---|
| `usr` | 0 | 0 | 189 | 1564 | 0 |
| `lib` | 81 | 81 | 23 | 234 | 0 |
| `etc` | 0 | 0 | 13 | 106 | 0 |
| `sbin` | 0 | 0 | 12 | 2 | 0 |
| `bin` | 0 | 0 | 6 | 11 | 0 |
| `boot` | 1 | 1 | 0 | 3 | 0 |
| `var` | 0 | 0 | 2 | 2 | 0 |

明细 2331 行超过 200 行上限, 已挪至 [Appendix](#appendix)。

## ELF Symbols

全固件汇总: **+2 / −0** functions, **+0 / −0** objects（50 个变更 ELF, 另有 178 个未列出）。

### `/usr/bin/sutest-daemon`

+2 / −0 functions · +0 / −0 objects

**New functions (2)**

| Symbol | Addr | Size |
|---|---|---|
| `_ZN9MultiShot14onTimeoutEventEv` | 0x62aa0 | 3064 |
| `_ZN9MultiShot10onEndEventEv` | 0x63698 | 716 |

### `/bin/busybox.nosuid`

+0 / −0 functions · +0 / −0 objects

### `/bin/busybox.suid`

+0 / −0 functions · +0 / −0 objects

### `/bin/kmod`

+0 / −0 functions · +0 / −0 objects

### `/bin/login.shadow`

+0 / −0 functions · +0 / −0 objects

### `/bin/mount.util-linux`

+0 / −0 functions · +0 / −0 objects

### `/bin/su.shadow`

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

### `/sbin/agetty`

+0 / −0 functions · +0 / −0 objects

### `/sbin/e2label`

+0 / −0 functions · +0 / −0 objects

### `/sbin/fw_printenv`

+0 / −0 functions · +0 / −0 objects

### `/sbin/fw_setenv`

+0 / −0 functions · +0 / −0 objects

### `/sbin/iwconfig`

+0 / −0 functions · +0 / −0 objects

### `/sbin/mke2fs`

+0 / −0 functions · +0 / −0 objects

### `/sbin/mkfs.ext2`

+0 / −0 functions · +0 / −0 objects

### `/sbin/mkfs.ext3`

+0 / −0 functions · +0 / −0 objects

### `/sbin/mkfs.ext4`

+0 / −0 functions · +0 / −0 objects

### `/sbin/mkfs.ext4dev`

+0 / −0 functions · +0 / −0 objects

### `/sbin/sulogin.util-linux`

+0 / −0 functions · +0 / −0 objects

### `/sbin/tune2fs`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/alsamixer`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/apm`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/avahi-browse`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/avahi-publish`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/avahi-resolve`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/avahi-set-host-name`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/bodystate-daemon`

+0 / −0 functions · +0 / −0 objects

### `/usr/bin/camera-daemon`

+0 / −0 functions · +0 / −0 objects

## Strings

新增字符串共 **1727** 条（每组截断至 100 条, 已滤除长度<6 / 纯数字 / UUID 样式噪音）。

### `/usr/lib/libQt5Quick.so.5.5.1`

<details><summary>新增 540 条字符串, 展示前 100 条</summary>

````text
 [A@ [A
 nAxgjA
 tA` tA
!hAD!hA
!tAX1tAx3tA
!tAX1tAx3tA,7tAd7tA
"_A,#_Ah
"gA #gA
"tAX2tA
#[A@#[A
#oA`,oA
#uA$)uAx)uAH,uA
$XAp$XA
%rA0*rA
%sA@&sA 
%zA<3uA
%zAh@uAHBuA
&sAD/sA
&yAT4uA
'lA((lA
'rAH,rA
'vAhZ[A
'zAdDuA
(.Ox".O$
(/zA`suA
(rAp/rAT
(rAp/rAd
*oAl'UO
+xA,~sA
,.zAdquA
,oAd#oAhFoA
,vA,yyA$
,zA0euA
,zAttoA
-^A,.^A
-^Al'UO
-vA,yyA
.lAH/lA
.sAl0sAP3sA
.sAl0sAh9cA
.vA|zyA$
.zA<QyApQyA
/O$&_AL&_A@'_A
/nA(/nA
/nAh0nA
/tAD0tA
/vA,wyA
/vA,{yA$
/zA<suA<vuA8wuA
0rA\3rA
0vA8{yA$
1lAX.lAx?lAh.lA
1lA`.lA
1tA|3tA
1tA|3tA`5cA
1vA,wyA$
1yA@JuA
2_AT6_A 
2cA@3cA
2cA\2cA
2sAdBcA
2tAD4tA
2tAD4tA<6tAt6tA
2vA,wyA
2vA4wyA$
3^At3^AP
3nAl'UOp
3rAPKWA
3sAH3sA
3uA09uA
4cAX5cA
4sA45sA
4vA05vA
4yA LuA
5[AP)WAT)WA$
5cA06cA
5pAl'UO
5sA|6sA
5tA46tA
6rAX7rA
6sA$7sA
6tA$7tA
7?AH)WA
7?AH)WAPUWA$
7ZAl'UO
7mA$8mA
7sA\7sA
8cAX8cA
9lAD'cA
9uAh;uA
9yA QuA
:cA`:cA 
:kA8%kA
:lAL'cA\
;tA8qkAdrkA
;tAD>tA
;tA\1cA
<,A<J,A(>,A@?,A
<_A8T_A 7_A
<_AHI_A
````

</details>

> 其余 440 条见 `result.json`。

### `/lib/libcrypto.so.1.0.0`

<details><summary>新增 287 条字符串, 展示前 100 条</summary>

````text
 TwO TwO1
 XwO8XwOT
 [wO,[wOr
 cwO cwO
 dwO dwO
 jwO jwO
 lwO lwO%
 pwO pwOR
! JyOg
!,KyOh
"0wyOh
"@wyOi
"HyyOr
"luyOd
"pvyOf
"xuyOe
#D$yOg
$RwO$RwO
$VwO4VwOF
$^nOHlnO
$bwO(bwO
$ewO$ewO
$kwO$kwO
$swO4swOt
$wwO0wwO
$xwO@xwO
$ywO$ywO
'pyyOl
(3yO8`{O
(`wO(`wO
(hwO(hwO
(jwO(jwO
({wO({wO
)pO`.pO
)pOl.pO
+mOx+mO
,WwO<WwOM
,^wO8^wO
,awO<awO
,bwO8bwO
,iwO,iwO
,lwO<lwO&
,owO,owOG
,qwO,qwO`
,vwO,vwO
,zwO,zwO
,}wO,}wO
.mO(/mO
0QwO<QwO
0UwO<UwO<
0`wO0`wO
0gwO0gwO
0jwO0jwO
0nOx0nO
0pwO0pwOS
0ywO0ywO
1yO0^{O
1yOXb{O
1yOd^{O
2yO|_{O
3yOpc{O
4SwO@SwO$
4TwO4TwO2
4cwO4cwO
4dwO4dwO
4fwO4fwO
4mwO4mwO1
4syOHsyO
4twO<twO
4tyO<tyO
4{wO4{wO
4|wO4|wO
4~wO4~wO
5qO\3qO
7yO 7yO$7yO(7yO,7yO07yO47yO87yO<7yO
8RwO8RwO
8YwOPYwOZ
8[wOD[wOs
8\wO8\wO
8`wO8`wO
8jwO8jwO
8rwO@rwOl
8tO0CtO
8vwO8vwO
8ywO8ywO
8zwO8zwO
:pO @pO
<kwO<kwO
<wwOHwwO
@TwO@TwO3
@\wO@\wO
@`wO@`wO
@nwO@nwO=
@owO@owOH
@pwO@pwOT
@uwO@uwO
@zwO@zwO
@{wO@{wO
@|wO@|wO
AyO8DyOLDyOXDyO
````

</details>

> 其余 187 条见 `result.json`。

### `/usr/lib/libQt5Qml.so.5.5.1`

<details><summary>新增 260 条字符串, 展示前 100 条</summary>

````text
!BAP&4A
#Al:#A
#BAh%BA
%7AL%7A
&O v'Otv'O
'4AX(4A 
'4Al'UO
)A(z+A
)AD3*A80*A`^,A
)At *A
)GAx)GAp)GAh)GA`)GAX)GAP)GAD)GA<)GA4)GA,)GA$)GA
*3A<(3A
,#AT/#A
-2Ap7AA
-;A4g,AX
/ATE,A
/BA@/BA 
1BAL1BA
3BAh3BA
4A,X:AXc2A$
5ALf6A
5Al'UOPGFA
5AxZ6A
5BA`7BA
8Al'UO
8BA,9BA
:A4g,A
:ATE,A
:FA0AGA
:FAXAGA$
;#AT*#A
;A4g,Ax
;ATE,A
;BA4<BA
<,A8I.A
<,A<?,At)0A
<,A<J,A(>,A
<,A<J,A(>,A@?,A
<,A<J,A(>,A@?,AT
<,A<J,A(>,APt.A
<,A<J,A(>,A`a.A
<,A<J,A(>,At
<,ADA.A
<,A`B.A
=Al'UOh
=BA =BAH=BA 
=BA >BAt>BAx>BA
=FAHsGA
>FAPAGA
?,A@?,A
?FAxAGA
@FA0AGAT
A6ALf6A
AAl'UO
AAl'UOt
ABAHBBA
AdH"AxG
Al'UOd
B,A<J,A
BADWAA
BAl!BA
CA,fGA
CA<gGA
CAH{GAT
CAPAGA
CAPvGA
CAP{GA
CA\YGA$
D#AL@#A
EAL|GA$
F,A e.A
F,ATE,A
F,Aps.A
FA 8BA
FA($BA
FA(CBA
FA8@BA
FA<sGA
FA@0BA
FA@\BA
FAD|GA$
FALQBA
FAPAGA$
FAPTBA
FATXBA
FAXAGA$
FA`5BA
FAl'UOH
FAx2BA
FAx=BA
FAxAGA
FBATGBA 
GA$8BAT8BA
GA$HBA
GA(QBA
GA0z@AXz@A
GA8OBAhOBA
GA@A:A
GAD0BAh0BA
GADQ2AhQ2A
````

</details>

> 其余 160 条见 `result.json`。

### `/usr/lib/liborc-0.4.so.0.23.0`

<details><summary>新增 153 条字符串, 展示前 100 条</summary>

````text
Oaccsadubl
Oaddssb
Oaddssl
Oaddssw
Oaddusb
Oaddusl
Oaddusw
Oandnb
Oandnl
Oandnq
Oandnw
Oavgsb
Oavgsl
Oavgsw
Oavgub
Oavgul
Oavguw
Ocmpeqb
Ocmpeqd
Ocmpeqf
Ocmpeql
Ocmpeqq
Ocmpeqw
Ocmpgtsb
Ocmpgtsl
Ocmpgtsq
Ocmpgtsw
Ocmpled
Ocmplef
Ocmpltd
Ocmpltf
Oconvdf
Oconvdl
Oconvfd
Oconvfl
Oconvhlw
Oconvhwb
Oconvld
Oconvlf
Oconvlw
Oconvql
Oconvsbw
Oconvslq
Oconvssslw
Oconvsssql
Oconvssswb
Oconvsuslw
Oconvsusql
Oconvsuswb
Oconvswl
Oconvubw
Oconvulq
Oconvusslw
Oconvussql
Oconvusswb
Oconvuuslw
Oconvuusql
Oconvuuswb
Oconvuwl
Oconvwb
Ocopyb
Ocopyl
Ocopyq
Ocopyw
Odiv255w
Odivluw
Oldreslinb
Oldreslinl
Oldresnearb
Oldresnearl
Oloadb
Oloadl
Oloadoffb
Oloadoffl
Oloadoffw
Oloadpb
Oloadpl
Oloadpq
Oloadpw
Oloadq
Oloadupdb
Oloadupib
Oloadw
Omaxsb
Omaxsl
Omaxsw
Omaxub
Omaxul
Omaxuw
Omergebw
Omergelq
Omergewl
Ominsb
Ominsl
Ominsw
Ominub
Ominul
Ominuw
Omulhsb
Omulhsl
````

</details>

> 其余 53 条见 `result.json`。

### `/usr/lib/libgstreamer-1.0.so.0.405.0`

<details><summary>新增 119 条字符串, 展示前 100 条</summary>

````text
 ]sOD]sO
 fsO8fsO
 isOTisO
 osO,QrO
 tsO,QrO
 ~sO8~sO
$bsO<bsO
,ssOLssO
,xsOLxsO
0^sOH^sO
0|sOH|sO
4lsOLlsO
4tsO4QrO
4}sOP}sO
8msOPmsO
8osO4QrO
8psO\psO
8vsO`vsO
<_sOT_sO2
@csOXbsO
@gsO<+rO
@hsO\hsO
@jsO`jsO
CqO<DqODDqO
DbsOXbsO
DfsO\fsO
D~sOX~sO
EqO(FqO0FqO
NsO`UpO
NsO|QpOT
PosO|ksOp
PqsOtqsO
TcsOlcsO
TdsOldsO
TnsOxnsO
TxsOtxsO
T|sOX,rO
XlsOxlsO
XmsOlmsO
XtsO4aqO
XwsOL]qO
\_sOt_sOP
\ssOtssO
`AiOXAiOd@iO
`sO4`sO
csO4csO
dksO|ksO
dtsO ]qO
esO4esO
fO,GqO
fO0EqO
fO@FqO
fOPDqO
fO\CqO
fOhGqO
fsO kqO
gsOdWrO
gsOl\qO
hOh7hOT!hO
hasO|asO
hsO4hsO
jsO0jsO
ksO0ksO 
lesO0FsO
lsO(lsO
msO OrO 
nsO@nsO
pO(DpO$
p^sO4aqO
psO$psO
p|sOh,rO
qiO|piOpaiO
qsO(qsO
qsOdWrO
rO kqO
rO,,rOx
rO0-rO
rO4+rO
rO@,rO|
rOdWrO
rOl\qO
rOtDrO4
rOxfqO
sO ]qO@
sO kqO
sO$lrO
sO$ysO
sO,mqO@
sO4+rO
sO4hsO
sO<cqO
sOL3sO
sOXbsO
sO\hsO
sOdWrO
sOlmsO
sOp[qOp
usO$usO
vqO@3pO
vqO@3pOT
````

</details>

> 其余 19 条见 `result.json`。

### `/usr/lib/libQt5Core.so.5.5.1`

<details><summary>新增 88 条字符串</summary>

````text
 O( !O
!(Ol!(O
"&O|Z)O@U)O
"O0M#O
%GO@,GO
&O v'Otv'O
'NOH-NO
(.Ox".Ol'UO
(O0A(O
(OD@(OHv(O 
+NOX83O
51Ot71O<51Od51O$
6OP$.O
=(O,6(Ot8(O
B(O\@(O
C(O|D(O
C/O4)/Oh)/O 
GOTG$O
IGO`JGO4B/O
J(O8K(O 
K!OpM!O4L!O
KSOhLSO
L/O W/OtW/OLN/O
N(HGOT
N2OHN2O
N2Ox?3O
N4HGO$
N83RO<
N8NSOP
N\HGOD
N`NSOP
Nl'UOH
Np0NOT
NpPSO(
Nt45Ox45O|45O$
Ol'UO 
Ol'UOxFSO(ISO
P!OPO!O
Q1O(51O
QSO`RSOx
ROHm6O
ROpk6O
ROpq6O
RSOxSSO
S2OdT2O
SSO`TSO,
TO(c$O
TO46(OH
TO@((O
UO b6O8c6O
UO$O2OdN2O
UO(M5OlM5O,M5OLM5O
UO0KSO`KSO
UO8fSOpfSO
UO<i2O4m2O
UODb6O
UOLO2OL=3O
UOPPSO
UO`2RO
UOh~-Ol
UOl'UO
UOl'UO0(NO
UOtb6O
W!O4S!OxX
\SOh]SO
^.O(M/O
^.OdP/O
^.Oh>3O
^.Ol'UO
^.Ol'UO0QSOXQSOH
^.Ol'UOp
^.Ol'UOx
^.Op<3O
a*O4b*O 
b6OLd6O
d6Ode6O
f/Olh/Ol'UO
fSO8gSO 
g/OPh/O 
i6OXf6O 
j6O\l6O
kSOhkSO(
l'UO82ROx4RO
o6O0t6O
x+Ol'UO
x6O4y6O8
z6O0z6O
}6OT}6O
````

</details>

### `/usr/lib/libwayland-client.so.0.3.0`

<details><summary>新增 77 条字符串</summary>

````text
-cO 7cO
P{dODpcOLpcO
TzdO<lcO
dO(mcO(pcO<
dO4mcO
dO<kcO8kcO
dO<lcODlcO
dOHkcO
dOPmcO
dOXmcO
dOllcO8kcO0
dOllcOtlcO`
dOllcOtlcOt
dOlmcO
dOpncO
dOxlcO|lcO
dvdOTlcO\lcO
kcO(kcO
lcO$lcO
lcO|lcO
mcO$ocO
mcO(pcO4
mcO(pcO8
ncO(pcO
ncO,ncO
ocO ocO
ocOL~dO
ocO`ocO
ocOd~dO
ocOp~dO
pcO(pcO@~dO
pcO(pcOD~dO
pcO(pcOH~dO,pcO
tdOxwdOxwdOxwdOxwdO
udO$wdO
udO<zdO
vdOLvdO
vdO`lcO
wdO`lcO8kcO,
xdOxwdO$wdO
ydO$wdO
ydOLocOTocO
ydOxwdOxwdO
zdOxocO
{dO8{dOxwdOhudO<zdO
{dOhudOhudO
{dO|pcO
~dO(ocO8ocO
~dO,kcO8kcO
~dO,lcO
~dO,lcO(pcO 
~dO,ocO
~dO4lcO
~dO4ncODncO
~dO8pcO
~dO<lcO
~dO<lcODlcO
~dO<ocO
~dO@mcOHmcO
~dOHlcO
~dOLkcO(pcO<~dO
~dOLncOXncO
~dOPpcO
~dOTkcO
~dOXocO`ocO
~dO`kcO
~dO`lcO
~dO`lcOhlcOh
~dO`ncO
~dO`pcOhpcO
~dOdocO
~dOllcO
~dOpocO
~dOppcO
~dOtkcO
~dOxocO
~dO|ncO
````

</details>

### `/usr/lib/libsqlite3.so.0.8.6`

<details><summary>新增 75 条字符串</summary>

````text
$YkO0YkO(YkO
$kO4VkO
%cO WdO "dO
+bOPYdO4
-dO4+dO
0kO(DkO
1dOp%bOpGeO
3kODIkO|IkO
3kOxVkO
?kODOjOD
BkO<BkOlBkO
CkODCkO|CkO
EkO$EkO@EkO\EkOtEkO
EkO8FkOhFkO
FkO`GkO
HkO@HkOhHkO
IcOd(eO
IkO(JkO
KcO$)eO
KeO84dO
KkOpKkO
LkO(MkO
LkO@LkOpLkO
NjOl?eO
OkO VkO(VkO0VkO
PkO$PkO,PkO4PkO@PkO,UkOLPkOTPkO\PkOdPkOlPkOtPkOxPkO
QkO QkO,QkO<QkODQkOPQkOXQkO`QkOhQkOlQkOtQkO0QkO|QkO
RkO$RkO,RkO4RkO<RkODRkOPRkO\RkOdRkOpRkOtRkOxRkO
SkO$SkO,SkO4SkO<SkODSkOPSkO`SkOlSkOtSkO|SkO
TkO TkO,TkO8TkODTkOTTkO`TkOlTkOxTkO
UkO(UkO4UkO<UkOHUkOPUkOXUkOdUkOlUkOtUkO|UkO
UkO`YkO
VkO 'kO
WkO<WkOPWkOX
XkO,XkO
\cOTFbO
\cOtFbO
\kO$#bO
\kO$(dO
]dOh^dO
^dOT_dO
^dO\_dO
`bOx3dO<'bO
aO bcO
aO,HbO
aO4MgO4MgOT[cO
aO8+bO
aO<3cO
aO<5dO,
aO<HbO
aO<hbO
aOH/gO\
aOL&bO
aOP/gO
aOp(eO
aOpGeO
aOp]dO
aO|FgO
bO( bOh
bOh6gO
cO0'bO('bO
cO<2cO
cOL5gO|
dO$GbO
dO`1cO,1cOD
edOh%dO
hOPOgOpagO
iO(ZcOdLgO
iOl9kO
iiO miO
jOH%kO\DkO
jOH&bO
jOlWkO4
jdO jdO
kODXkOXXkO
````

</details>

### `/usr/lib/libAppsMessaging.so`

<details><summary>新增 25 条字符串</summary>

````text
 bO  bO8 bOP bOh bO
!bO,!bOH!bOd!bO
"bO("bO@"bOX"bOp"bO
#bO$$bOH$bOd$bO
#bO8#bOX#bOx#bO
%bO4%bOP%bOl%bO
(bO4(bOT(bOt(bO
)bO<)bOX)bOx)bO
*bO *bOD*bOh*bO
+bO,+bOH+bOd+bO
,bO<,bOX,bOx,bO
-bO,-bOT-bO|-bO
.bO4.bOP.bOl.bO
/bO4/bOd/bO
0bO 0bO80bOP0bOh0bO
1bO81bOX1bOt1bO
2bO$2bO@2bO`2bO
3bO<3bOd3bO
4bO04bO\4bO
5bO45bO`5bO
6bO86bO\6bO
7bO 7bO@7bO\7bO
8bO(8bOD8bO\8bO
9bO49bOX9bO|9bO
:bO0:bOT:bOx:bO
````

</details>

### `/usr/lib/libQt5Sql.so.5.5.1`

````text
!&OTxpO
!oO`)oO
&oO|(oO
)oO`)oO
,pOD,pO 
/nOP/nO0/nO8/nO(
0nO@0nO 
8pO49pOd
DoO0GoO<RoO
nO0BoO
nO@/nOH/nOX/nO`/nO
nO\)oO
nOh/nOl/nOp/nOt/nOx/nO|/nO
nOl'UO<
nO|MoOL
oO<ApO
oOD4pO
oOx)oO
pO,-pO
````

### `/usr/bin/sutest-daemon`

````text
Could not enable MS high voltage.
Ready.
Running Burn-in...
Time remaining:
_ZN6QTimer5startEi
_ZN9MultiShot10onEndEventEv
_ZN9MultiShot14onTimeoutEventEv
delay:
iteration:
multishot_dac_enable set failed!
multishot_dac_enable set failed! (set to
multishot_dac_enable set success!
onEndEvent
onTimeoutEvent
position:
````

### `/lib/libc-2.22.so`

````text
Naliases
Nethers
Ngroup
Ngshadow
Nhosts
Ninitgroups
Nnetgroup
Nnetworks
Npasswd
Nprotocols
Npublickey
Nservices
Nshadow
````

### `/usr/lib/libQt5Network.so.5.5.1`

````text
Nl'UO(h
Ol'UO(
Ol'UO8
Ol'UOHQ
Ol'UO\G
Ol'UOd
Ol'UOt
UOl'UO
UOl'UO$
UOl'UO8
^.Ol'UO
^.Ol'UOhw
````

### `/usr/lib/libappscommon.so.1.0.0`

````text
6]O 7]O 
Nlk^O@
YO$DZO|
^.O8_\O
^.Ol'UO
^.Ol'UO@U^O0W^O
^.Ol'UOPs^O
^.Ol'UOlt^Ohv^O
`Opn]OP
b^Oxk^OP
````

### `/usr/lib/libQt5Gui.so.5.5.1`

````text
Nl'UO(
Nl'UO0
Nl'UOH
Nl'UOh
Ol'UOP
Pl'UOH
^.Ol'UO
^.Ol'UOP
^.Ol'UOx
````

### `/usr/lib/libQt5Positioning.so.5.5.1`

````text
(LA\WKALhKA
KALZKA
LA()LA
LA4(LA$
LAl'UO
Nl'UO 
^.OPWKA
^.Ol'UO
^.Ol'UO,
````

### `/usr/lib/libQt5DBus.so.5.5.1`

````text
UOl'UOX
^.Ol'UO
^.Ol'UOP
^.Ol'UOp
````

### `/usr/lib/libgobject-2.0.so.0.4400.1`

````text
#yO@#yO
LF|OTF|O
XF|OdF|O
hF|OtF|O
````

### `/usr/bin/camera-daemon`

````text
Unable to set (0,0) DAC voltage
end piezo warmup
start piezo warmup
````

### `/usr/lib/libffi.so.6.0.4`

````text
 aO4\aO
aO \aO
aO,\aO
````

### `/usr/lib/libfreetype.so.6.12.0`

````text
Nltuo<J
````

### `/usr/lib/liblttng-ust-ctl.so.2.0.0`

````text
N                0000000000000000
````

### `/bin/busybox.nosuid`

````text
````

### `/bin/busybox.suid`

````text
````

### `/bin/kmod`

````text
````

### `/bin/login.shadow`

````text
````

### `/bin/mount.util-linux`

````text
````

### `/bin/su.shadow`

````text
````

### `/lib/ld-2.22.so`

````text
````

### `/lib/libblkid.so.1.1.0`

````text
````

### `/lib/libcap.so.2.24`

````text
````

### `/lib/libcom_err.so.2.1`

````text
````

### `/lib/libcrypt-2.22.so`

````text
````

### `/lib/libdl-2.22.so`

````text
````

### `/lib/libe2p.so.2.3`

````text
````

### `/lib/libext2fs.so.2.4`

````text
````

### `/lib/libgcc_s.so.1`

````text
````

### `/lib/libm-2.22.so`

````text
````

### `/lib/libmount.so.1.1.0`

````text
````

### `/lib/libncursesw.so.5.9`

````text
````

### `/lib/libpthread-2.22.so`

````text
````

### `/lib/libresolv-2.22.so`

````text
````

### `/lib/librt-2.22.so`

````text
````

### `/lib/libsysfs.so.2.0.1`

````text
````

### `/lib/libtinfo.so.5.9`

````text
````

### `/lib/libudev.so.1.6.4`

````text
````

### `/lib/libusb-1.0.so.0.1.0`

````text
````

### `/lib/libuuid.so.1.3.0`

````text
````

### `/lib/libz.so.1.2.8`

````text
````

### `/sbin/agetty`

````text
````

## Scripts & Config

共 0 个脚本/配置变更, 0 行 unified diff（context=3, 预算上限 ? 行）。

无文本类变更。

## Lens Firmware

> 已跳过: 非 lens 固件（kind != lens）

## Appendix

<details><summary>Filesystem 详表（2331 行）</summary>

| Path | Status | Old Size | New Size | Δ | Tree |
|---|---|---|---|---|---|
| `/bin/busybox.nosuid` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 552.0 KB | 552.0 KB | +0 B | rootfs |
| `/bin/busybox.suid` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 52.9 KB | 52.9 KB | +0 B | rootfs |
| `/bin/journalctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 406.3 KB | 406.3 KB | +0 B | rootfs |
| `/bin/kmod` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 109.5 KB | 109.5 KB | +0 B | rootfs |
| `/bin/login.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.7 KB | 53.7 KB | +0 B | rootfs |
| `/bin/mount.util-linux` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 33.4 KB | 33.4 KB | +0 B | rootfs |
| `/bin/networkctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 377.8 KB | 377.8 KB | +0 B | rootfs |
| `/bin/su.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.5 KB | 44.5 KB | +0 B | rootfs |
| `/bin/systemctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 542.9 KB | 542.9 KB | +0 B | rootfs |
| `/bin/systemd-ask-password` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.8 KB | 37.8 KB | +0 B | rootfs |
| `/bin/systemd-escape` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/bin/systemd-machine-id-setup` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/bin/systemd-notify` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.8 KB | 29.8 KB | +0 B | rootfs |
| `/bin/systemd-sysusers` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 81.8 KB | 81.8 KB | +0 B | rootfs |
| `/bin/systemd-tmpfiles` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 105.9 KB | 105.9 KB | +0 B | rootfs |
| `/bin/systemd-tty-ask-password-agent` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.8 KB | 49.8 KB | +0 B | rootfs |
| `/bin/udevadm` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 357.9 KB | 357.9 KB | +0 B | rootfs |
| `/boot/devicetree-zImage-imx6q-hbl-idun.dtb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.3 KB | 37.3 KB | +0 B | rootfs |
| `/boot/devicetree-zImage-imx6q-hbl-victory.dtb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 37.7 KB | 37.7 KB | +0 B | rootfs |
| `/boot/devicetree-zImage-imx6q-hbl-wedge.dtb` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 40.0 KB | 40.0 KB | +0 B | rootfs |
| `/boot/zImage-3.14.28-1.0.0_ga+yocto+g1b67c6d` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.6 MB | — | -3.6 MB | rootfs |
| `/boot/zImage-3.14.28-1.0.0_ga+yocto+gd7b0c67` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.6 MB | +3.6 MB | rootfs |
| `/etc/apm/apmd_proxy` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
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
| `/etc/issue` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 85 B | 85 B | +0 B | rootfs |
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
| `/etc/modprobe.d/suc2farm.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20 B | 20 B | +0 B | rootfs |
| `/etc/modprobe.d/touch.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23 B | 23 B | +0 B | rootfs |
| `/etc/modprobe.d/usb.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44 B | 44 B | +0 B | rootfs |
| `/etc/modprobe.d/wifi.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19 B | 19 B | +0 B | rootfs |
| `/etc/modules-load.d/galcore.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8 B | 8 B | +0 B | rootfs |
| `/etc/motd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 0 B | 0 B | +0 B | rootfs |
| `/etc/network/if-pre-up.d/wpa-supplicant` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.9 KB | 1.9 KB | +0 B | rootfs |
| `/etc/nsswitch.conf` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 465 B | 465 B | +0 B | rootfs |
| `/etc/os-release` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 94 B | 94 B | +0 B | rootfs |
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
| `/lib/firmware/hbl/cambody-h6/CBC_1600583_PVF-2_1_0.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 392.1 KB | 392.1 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/CBM_1601244_PVF-0_2_4.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 434.3 KB | 434.3 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/CBM_1601450_PVF-10.1.25.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 245.9 KB | 245.9 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/EPP_1601450_PFV002.hex` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/lib/firmware/hbl/cambody-h6/cambody_upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.8 KB | 18.8 KB | +0 B | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-albatross-v1.20.0-10213-5d8dfe8.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.8 MB | — | -3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-albatross-v1.20.1-10879-5d8dfe8.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.8 MB | +3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-idun-v1.18-1285-3e7cd2b.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 MB | 3.7 MB | +0 B | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-victory-v1.20.0-12294-5d8dfe8.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.8 MB | — | -3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-victory-v1.20.1-12960-5d8dfe8.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.8 MB | +3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-wedge-v1.20.0-10362-5d8dfe8.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.8 MB | — | -3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_even-wedge-v1.20.1-11028-5d8dfe8.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.8 MB | +3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-albatross-v1.20.0-10213-5d8dfe8.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.8 MB | — | -3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-albatross-v1.20.1-10879-5d8dfe8.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.8 MB | +3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-idun-v1.18-1285-3e7cd2b.bin` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 MB | 3.7 MB | +0 B | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-victory-v1.20.0-12294-5d8dfe8.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.8 MB | — | -3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-victory-v1.20.1-12960-5d8dfe8.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.8 MB | +3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-wedge-v1.20.0-10362-5d8dfe8.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.8 MB | — | -3.8 MB | rootfs |
| `/lib/firmware/hbl/farm/bootimage_odd-wedge-v1.20.1-11028-5d8dfe8.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.8 MB | +3.8 MB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_a6d100-v0.0-11564-c9b598c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 155.9 KB | — | -155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_a6d100-v0.0-12230-c9b598c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.9 KB | +155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_a6d50-v0.0-11564-c9b598c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 155.9 KB | — | -155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_a6d50-v0.0-12230-c9b598c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.9 KB | +155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_albatross-v0.0-11564-c9b598c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 155.9 KB | — | -155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_albatross-v0.0-12230-c9b598c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.9 KB | +155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_cfv-v0.0-11564-c9b598c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 155.9 KB | — | -155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_cfv-v0.0-12230-c9b598c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.9 KB | +155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_victory-v0.0-11564-c9b598c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 155.9 KB | — | -155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_victory-v0.0-12230-c9b598c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.9 KB | +155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_wedge-v0.0-11564-c9b598c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 155.9 KB | — | -155.9 KB | rootfs |
| `/lib/firmware/hbl/fx3/fx3_wedge-v0.0-12230-c9b598c.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 155.9 KB | +155.9 KB | rootfs |
| `/lib/firmware/hbl/power-control/power-control-v1.20.0-12005-dfa6068.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 46.8 KB | — | -46.8 KB | rootfs |
| `/lib/firmware/hbl/power-control/power-control-v1.20.1-12671-dfa6068.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 46.8 KB | +46.8 KB | rootfs |
| `/lib/firmware/hbl/su-control/camera-control-v1.20.0-12199-1a36e7c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 224.6 KB | — | -224.6 KB | rootfs |
| `/lib/firmware/hbl/su-control/camera-control-v1.20.1-12866-cb6bc7e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 224.6 KB | +224.6 KB | rootfs |
| `/lib/firmware/hbl/su-control/su-control-v1.20.0-12199-1a36e7c.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 383.1 KB | — | -383.1 KB | rootfs |
| `/lib/firmware/hbl/su-control/su-control-v1.20.1-12866-cb6bc7e.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 383.1 KB | +383.1 KB | rootfs |
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
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/extra/galcore.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 295.8 KB | — | -295.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/extcon/extcon-class.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 19.6 KB | — | -19.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/gpio/gpio-pca953x.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 17.5 KB | — | -17.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/i2c/i2c-dev.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 15.8 KB | — | -15.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/iio/dac/max5842.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.0 KB | — | -8.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/iio/industrialio.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 55.0 KB | — | -55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/iio/light/sfh7776.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.5 KB | — | -12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/input/misc/lis3dsh_acc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 28.7 KB | — | -28.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/input/touchscreen/atmel_mxt_ts.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 37.7 KB | — | -37.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/leds/leds-gpio.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.8 KB | — | -8.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/fpga_camera_mipi.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 19.3 KB | — | -19.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/ipu_bg_overlay_sdc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.5 KB | — | -12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/ipu_csi_enc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 9.5 KB | — | -9.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/ipu_fg_overlay_sdc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 14.4 KB | — | -14.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/ipu_prp_enc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.2 KB | — | -13.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/ipu_still.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.8 KB | — | -6.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/mxc_v4l2_capture.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 70.1 KB | — | -70.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/media/platform/mxc/capture/v4l2-int-device.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.0 KB | — | -6.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/misc/eeprom/at24.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 14.0 KB | — | -14.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/mtd/devices/m25p80.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.5 KB | — | -7.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/mtd/mtd.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 72.8 KB | — | -72.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/mtd/ofpart.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.1 KB | — | -6.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/mtd/spi-nor/spi-nor.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 29.3 KB | — | -29.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/net/mii.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.2 KB | — | -8.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/net/phy/libphy.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 43.9 KB | — | -43.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/net/usb/asix.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 48.8 KB | — | -48.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/net/usb/usbnet.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 55.0 KB | — | -55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/power/bq28z610_battery.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.8 KB | — | -13.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/spi/spi-bitbang.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 8.9 KB | — | -8.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/spi/spi-imx.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 23.2 KB | — | -23.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/usb/chipidea/ci_hdrc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 52.2 KB | — | -52.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/usb/chipidea/ci_hdrc_imx.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 19.9 KB | — | -19.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/usb/chipidea/usbmisc_imx.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 15.9 KB | — | -15.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/usb/core/usbcore.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 288.6 KB | — | -288.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/usb/host/ehci-hcd.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 95.9 KB | — | -95.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/drivers/video/backlight/l3ej03110a.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.2 KB | — | -12.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/fs/fat/fat.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 79.2 KB | — | -79.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/fs/fat/vfat.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 18.0 KB | — | -18.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/fs/nls/nls_cp437.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.6 KB | — | -7.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/fs/nls/nls_iso8859-1.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 5.9 KB | — | -5.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/net/802/stp.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 4.9 KB | — | -4.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/net/bridge/bridge.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 130.5 KB | — | -130.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/net/llc/llc.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 11.1 KB | — | -11.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/codecs/snd-soc-tfa9882.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 5.1 KB | — | -5.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/codecs/snd-soc-tlv320aic3x.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 54.2 KB | — | -54.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/fsl/imx-pcm-dma.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 4.7 KB | — | -4.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/fsl/snd-soc-fsl-sai.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 17.5 KB | — | -17.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/fsl/snd-soc-fsl-ssi.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 29.1 KB | — | -29.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/fsl/snd-soc-hbl-tfa9882.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.9 KB | — | -7.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/fsl/snd-soc-hbl-tlv320aic3x.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 12.8 KB | — | -12.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/kernel/sound/soc/fsl/snd-soc-imx-audmux.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 14.5 KB | — | -14.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.alias` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 7.1 KB | — | -7.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.alias.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 10.5 KB | — | -10.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.builtin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 4.4 KB | — | -4.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.builtin.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 5.4 KB | — | -5.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.dep` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 3.7 KB | — | -3.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.dep.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.7 KB | — | -6.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.devname` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 52 B | — | -52 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.order` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 6.2 KB | — | -6.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.softdep` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 55 B | — | -55 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.symbols` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 21.6 KB | — | -21.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/modules.symbols.bin` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 26.5 KB | — | -26.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/updates/compat/compat.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 21.2 KB | — | -21.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/updates/drivers/net/wireless/brcm80211/brcmfmac/brcmfmac.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 219.7 KB | — | -219.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/updates/drivers/net/wireless/brcm80211/brcmutil/brcmutil.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 13.5 KB | — | -13.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+g1b67c6d/updates/net/wireless/cfg80211.ko` | ![REMOVED](https://img.shields.io/badge/-REMOVED-red) | 629.5 KB | — | -629.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/extra/galcore.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 295.8 KB | +295.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/extcon/extcon-class.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 19.6 KB | +19.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/gpio/gpio-pca953x.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 17.5 KB | +17.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/i2c/i2c-dev.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 15.8 KB | +15.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/iio/dac/max5842.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.0 KB | +8.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/iio/industrialio.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 55.0 KB | +55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/iio/light/sfh7776.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.5 KB | +12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/input/misc/lis3dsh_acc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 28.7 KB | +28.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/input/touchscreen/atmel_mxt_ts.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 37.7 KB | +37.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/leds/leds-gpio.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.8 KB | +8.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/fpga_camera_mipi.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 19.3 KB | +19.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/ipu_bg_overlay_sdc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.5 KB | +12.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/ipu_csi_enc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 9.5 KB | +9.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/ipu_fg_overlay_sdc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 14.4 KB | +14.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/ipu_prp_enc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 13.2 KB | +13.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/ipu_still.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.8 KB | +6.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/mxc_v4l2_capture.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 70.1 KB | +70.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/media/platform/mxc/capture/v4l2-int-device.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.0 KB | +6.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/misc/eeprom/at24.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 14.0 KB | +14.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/mtd/devices/m25p80.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.5 KB | +7.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/mtd/mtd.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 72.8 KB | +72.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/mtd/ofpart.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.1 KB | +6.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/mtd/spi-nor/spi-nor.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 29.3 KB | +29.3 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/net/mii.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.2 KB | +8.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/net/phy/libphy.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 43.9 KB | +43.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/net/usb/asix.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 48.8 KB | +48.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/net/usb/usbnet.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 55.0 KB | +55.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/power/bq28z610_battery.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 13.8 KB | +13.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/spi/spi-bitbang.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 8.9 KB | +8.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/spi/spi-imx.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 23.2 KB | +23.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/usb/chipidea/ci_hdrc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 52.2 KB | +52.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/usb/chipidea/ci_hdrc_imx.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 19.9 KB | +19.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/usb/chipidea/usbmisc_imx.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 15.9 KB | +15.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/usb/core/usbcore.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 288.6 KB | +288.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/usb/host/ehci-hcd.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 95.9 KB | +95.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/drivers/video/backlight/l3ej03110a.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.2 KB | +12.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/fs/fat/fat.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 79.2 KB | +79.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/fs/fat/vfat.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 18.0 KB | +18.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/fs/nls/nls_cp437.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.6 KB | +7.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/fs/nls/nls_iso8859-1.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 5.9 KB | +5.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/net/802/stp.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 4.9 KB | +4.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/net/bridge/bridge.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 130.5 KB | +130.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/net/llc/llc.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 11.1 KB | +11.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/codecs/snd-soc-tfa9882.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 5.1 KB | +5.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/codecs/snd-soc-tlv320aic3x.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 54.0 KB | +54.0 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/fsl/imx-pcm-dma.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 4.7 KB | +4.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/fsl/snd-soc-fsl-sai.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 17.5 KB | +17.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/fsl/snd-soc-fsl-ssi.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 29.1 KB | +29.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/fsl/snd-soc-hbl-tfa9882.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.9 KB | +7.9 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/fsl/snd-soc-hbl-tlv320aic3x.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 12.8 KB | +12.8 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/kernel/sound/soc/fsl/snd-soc-imx-audmux.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 14.5 KB | +14.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.alias` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 7.1 KB | +7.1 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.alias.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 10.5 KB | +10.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.builtin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 4.4 KB | +4.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.builtin.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 5.4 KB | +5.4 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.dep` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 3.7 KB | +3.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.dep.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.7 KB | +6.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.devname` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 52 B | +52 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.order` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 6.2 KB | +6.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.softdep` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 55 B | +55 B | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.symbols` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 21.6 KB | +21.6 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/modules.symbols.bin` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 26.5 KB | +26.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/updates/compat/compat.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 21.2 KB | +21.2 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/updates/drivers/net/wireless/brcm80211/brcmfmac/brcmfmac.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 219.7 KB | +219.7 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/updates/drivers/net/wireless/brcm80211/brcmutil/brcmutil.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 13.5 KB | +13.5 KB | rootfs |
| `/lib/modules/3.14.28-1.0.0_ga+yocto+gd7b0c67/updates/net/wireless/cfg80211.ko` | ![ADDED](https://img.shields.io/badge/-ADDED-green) | — | 629.5 KB | +629.5 KB | rootfs |
| `/lib/systemd/network/80-container-host0.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 380 B | 380 B | +0 B | rootfs |
| `/lib/systemd/network/80-container-ve.network` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 482 B | 482 B | +0 B | rootfs |
| `/lib/systemd/network/99-default.link` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 80 B | 80 B | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-dbus1-generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.8 KB | 49.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-debug-generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-fstab-generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.8 KB | 65.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-getty-generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-gpt-auto-generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101.9 KB | 101.9 KB | +0 B | rootfs |
| `/lib/systemd/system-generators/systemd-system-update-generator` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
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
| `/lib/systemd/system/sshdgenkeys.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 513 B | 513 B | +0 B | rootfs |
| `/lib/systemd/system/storage-daemon.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 237 B | 237 B | +0 B | rootfs |
| `/lib/systemd/system/suc2farm-modules.service` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 241 B | 241 B | +0 B | rootfs |
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
| `/lib/systemd/systemd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 MB | 1.2 MB | +0 B | rootfs |
| `/lib/systemd/systemd-ac-power` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.6 KB | 9.6 KB | +0 B | rootfs |
| `/lib/systemd/systemd-activate` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.8 KB | 41.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-bootchart` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 89.8 KB | 89.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-bus-proxyd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 318.4 KB | 318.4 KB | +0 B | rootfs |
| `/lib/systemd/systemd-cgroups-agent` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 234.3 KB | 234.3 KB | +0 B | rootfs |
| `/lib/systemd/systemd-fsck` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 262.6 KB | 262.6 KB | +0 B | rootfs |
| `/lib/systemd/systemd-hostnamed` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 286.3 KB | 286.3 KB | +0 B | rootfs |
| `/lib/systemd/systemd-initctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 242.3 KB | 242.3 KB | +0 B | rootfs |
| `/lib/systemd/systemd-journald` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 253.8 KB | 253.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-machine-id-commit` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-modules-load` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-networkd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 666.4 KB | 666.4 KB | +0 B | rootfs |
| `/lib/systemd/systemd-networkd-wait-online` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 101.9 KB | 101.9 KB | +0 B | rootfs |
| `/lib/systemd/systemd-random-seed` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-remount-fs` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 41.8 KB | 41.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-reply-password` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-rfkill` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-shutdown` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 121.9 KB | 121.9 KB | +0 B | rootfs |
| `/lib/systemd/systemd-sleep` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-socket-proxyd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 81.8 KB | 81.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-sysctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-sysv-install` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.2 KB | 1.2 KB | +0 B | rootfs |
| `/lib/systemd/systemd-timedated` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 286.7 KB | 286.7 KB | +0 B | rootfs |
| `/lib/systemd/systemd-timesyncd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 121.8 KB | 121.8 KB | +0 B | rootfs |
| `/lib/systemd/systemd-udevd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 365.9 KB | 365.9 KB | +0 B | rootfs |
| `/lib/systemd/systemd-update-done` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/lib/udev/ata_id` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/lib/udev/cdrom_id` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 45.8 KB | 45.8 KB | +0 B | rootfs |
| `/lib/udev/collect` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.7 KB | 17.7 KB | +0 B | rootfs |
| `/lib/udev/mtd_probe` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
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
| `/lib/udev/scsi_id` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42.3 KB | 42.3 KB | +0 B | rootfs |
| `/lib/udev/v4l_id` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 9.7 KB | 9.7 KB | +0 B | rootfs |
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
| `/usr/bin/bodystate-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 234.5 KB | 234.5 KB | +0 B | rootfs |
| `/usr/bin/busctl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 326.3 KB | 326.3 KB | +0 B | rootfs |
| `/usr/bin/camera-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 297.7 KB | 299.6 KB | +1.9 KB | rootfs |
| `/usr/bin/configstore` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 172.1 KB | 172.1 KB | +0 B | rootfs |
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
| `/usr/bin/hbl-collect-logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.4 KB | 3.4 KB | +0 B | rootfs |
| `/usr/bin/hbl-post-upgrade` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 881 B | 881 B | +0 B | rootfs |
| `/usr/bin/hbl-save-error-logs.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 472 B | 472 B | +0 B | rootfs |
| `/usr/bin/hbl-speaker-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.3 KB | 21.3 KB | +0 B | rootfs |
| `/usr/bin/hex-writer` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.9 KB | 67.9 KB | +0 B | rootfs |
| `/usr/bin/hostnamectl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 246.3 KB | 246.3 KB | +0 B | rootfs |
| `/usr/bin/irq-affinity-setup.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 560 B | 560 B | +0 B | rootfs |
| `/usr/bin/is_a6d` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 275 B | 275 B | +0 B | rootfs |
| `/usr/bin/is_a6d100` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 103 B | 103 B | +0 B | rootfs |
| `/usr/bin/is_a6d50` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 102 B | 102 B | +0 B | rootfs |
| `/usr/bin/is_albatross` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 190 B | 190 B | +0 B | rootfs |
| `/usr/bin/is_idun` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 395 B | 395 B | +0 B | rootfs |
| `/usr/bin/is_victory` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 187 B | 187 B | +0 B | rootfs |
| `/usr/bin/is_wedge` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 409 B | 409 B | +0 B | rootfs |
| `/usr/bin/jpeg-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 150.9 KB | 150.9 KB | +0 B | rootfs |
| `/usr/bin/libevdev-tweak-device` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.5 KB | 8.5 KB | +0 B | rootfs |
| `/usr/bin/libinput-debug-events` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.1 KB | 26.1 KB | +0 B | rootfs |
| `/usr/bin/libinput-list-devices` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 21.3 KB | 21.3 KB | +0 B | rootfs |
| `/usr/bin/load_wifi_test_fw.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 119 B | 119 B | +0 B | rootfs |
| `/usr/bin/lttng` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 200.0 KB | 200.0 KB | +0 B | rootfs |
| `/usr/bin/lttng-relayd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 187.9 KB | 187.9 KB | +0 B | rootfs |
| `/usr/bin/lttng-sessiond` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 457.0 KB | 457.0 KB | +0 B | rootfs |
| `/usr/bin/metadata-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 265.8 KB | 265.8 KB | +0 B | rootfs |
| `/usr/bin/mouse-dpi-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.5 KB | 9.5 KB | +0 B | rootfs |
| `/usr/bin/mpicalc` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 15.2 KB | 15.2 KB | +0 B | rootfs |
| `/usr/bin/msg2dbus` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 421.3 KB | 421.3 KB | +0 B | rootfs |
| `/usr/bin/msg2dbus-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 55.4 KB | 55.4 KB | +0 B | rootfs |
| `/usr/bin/mtdev-test` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 7.8 KB | 7.8 KB | +0 B | rootfs |
| `/usr/bin/mxt-app` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 93.6 KB | 93.6 KB | +0 B | rootfs |
| `/usr/bin/nettle-hash` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 9.2 KB | 9.2 KB | +0 B | rootfs |
| `/usr/bin/nettle-lfib-stream` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.8 KB | 5.8 KB | +0 B | rootfs |
| `/usr/bin/nettle-pbkdf2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.6 KB | 8.6 KB | +0 B | rootfs |
| `/usr/bin/network-manager` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 53.8 KB | 53.8 KB | +0 B | rootfs |
| `/usr/bin/newgrp.shadow` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 26.1 KB | 26.1 KB | +0 B | rootfs |
| `/usr/bin/phocus-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 492.4 KB | 492.4 KB | +0 B | rootfs |
| `/usr/bin/phocus-mobile-server` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 399.8 KB | 399.8 KB | +0 B | rootfs |
| `/usr/bin/pkcs1-conv` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 13.4 KB | 13.4 KB | +0 B | rootfs |
| `/usr/bin/prodconfig-tool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 111.5 KB | 111.5 KB | +0 B | rootfs |
| `/usr/bin/program_farm.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.1 KB | 2.1 KB | +0 B | rootfs |
| `/usr/bin/program_fx3.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.7 KB | 1.7 KB | +0 B | rootfs |
| `/usr/bin/program_nodes.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.3 KB | 8.3 KB | +0 B | rootfs |
| `/usr/bin/program_spc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.6 KB | 5.6 KB | +0 B | rootfs |
| `/usr/bin/program_suc.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.4 KB | 1.4 KB | +0 B | rootfs |
| `/usr/bin/program_touch.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 482 B | 482 B | +0 B | rootfs |
| `/usr/bin/scp.openssh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 65.6 KB | 65.6 KB | +0 B | rootfs |
| `/usr/bin/sexp-conv` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/bin/ssh-keygen` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 405.6 KB | 405.6 KB | +0 B | rootfs |
| `/usr/bin/ssh.openssh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 645.8 KB | 645.8 KB | +0 B | rootfs |
| `/usr/bin/storage-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 402.9 KB | 402.9 KB | +0 B | rootfs |
| `/usr/bin/suc2farm-setup.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 507 B | 507 B | +0 B | rootfs |
| `/usr/bin/sutest-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 480.4 KB | 488.7 KB | +8.3 KB | rootfs |
| `/usr/bin/sutest-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 137.6 KB | 137.6 KB | +0 B | rootfs |
| `/usr/bin/sysmon.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.9 KB | 3.9 KB | +0 B | rootfs |
| `/usr/bin/system-manager` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 225.1 KB | 225.1 KB | +0 B | rootfs |
| `/usr/bin/systemd-cat` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 25.8 KB | 25.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-cgls` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 250.3 KB | 250.3 KB | +0 B | rootfs |
| `/usr/bin/systemd-cgtop` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 61.8 KB | 61.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-delta` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.8 KB | 53.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-detect-virt` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 29.8 KB | 29.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-nspawn` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 478.5 KB | 478.5 KB | +0 B | rootfs |
| `/usr/bin/systemd-path` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.8 KB | 33.8 KB | +0 B | rootfs |
| `/usr/bin/systemd-run` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 314.4 KB | 314.4 KB | +0 B | rootfs |
| `/usr/bin/systemd-stdio-bridge` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 310.4 KB | 310.4 KB | +0 B | rootfs |
| `/usr/bin/systool` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.8 KB | 20.8 KB | +0 B | rootfs |
| `/usr/bin/timedatectl` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 254.3 KB | 254.3 KB | +0 B | rootfs |
| `/usr/bin/touchpad-edge-detector` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 8.3 KB | 8.3 KB | +0 B | rootfs |
| `/usr/bin/update-alternatives` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.2 KB | 4.2 KB | +0 B | rootfs |
| `/usr/bin/upgrade-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 381.9 KB | 381.9 KB | +0 B | rootfs |
| `/usr/bin/upgrade.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 442 B | 442 B | +0 B | rootfs |
| `/usr/bin/upgrade_from_slot.sh` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 262 B | 262 B | +0 B | rootfs |
| `/usr/bin/victory-gui` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.9 MB | 1.9 MB | +0 B | rootfs |
| `/usr/bin/video-daemon` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 307.9 KB | 307.9 KB | +0 B | rootfs |
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
| `/usr/lib/gstreamer-1.0/libgstfaad.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.8 KB | 18.8 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstimxv4l2videosrc-userptr.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.7 KB | 26.7 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstimxvpu.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 72.6 KB | 72.6 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstisomp4.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 356.1 KB | 356.1 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstvideoparsersbad.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 155.5 KB | 155.5 KB | +0 B | rootfs |
| `/usr/lib/gstreamer-1.0/libgstvoaacenc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 14.3 KB | 14.3 KB | +0 B | rootfs |
| `/usr/lib/gstreamer1.0/gstreamer-1.0/gst-plugin-scanner` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 6.5 KB | 6.5 KB | +0 B | rootfs |
| `/usr/lib/libAppsMessaging.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 88.8 KB | 88.8 KB | +0 B | rootfs |
| `/usr/lib/libEGL.so.1.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 601.3 KB | 601.3 KB | +0 B | rootfs |
| `/usr/lib/libGAL.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.7 MB | 4.7 MB | +0 B | rootfs |
| `/usr/lib/libGLESv2.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.4 MB | 4.4 MB | +0 B | rootfs |
| `/usr/lib/libGLSLC.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.8 MB | 1.8 MB | +0 B | rootfs |
| `/usr/lib/libQt5Compositor.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 524.8 KB | 524.8 KB | +0 B | rootfs |
| `/usr/lib/libQt5Concurrent.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.3 KB | 16.3 KB | +0 B | rootfs |
| `/usr/lib/libQt5Core.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 5.0 MB | 5.0 MB | +0 B | rootfs |
| `/usr/lib/libQt5DBus.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 439.0 KB | 439.0 KB | +0 B | rootfs |
| `/usr/lib/libQt5EglDeviceIntegration.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 733.1 KB | 733.1 KB | +0 B | rootfs |
| `/usr/lib/libQt5Gui.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 4.2 MB | 4.2 MB | +0 B | rootfs |
| `/usr/lib/libQt5Location.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 416.4 KB | 416.4 KB | +0 B | rootfs |
| `/usr/lib/libQt5Network.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 1.1 MB | 1.1 MB | +0 B | rootfs |
| `/usr/lib/libQt5Positioning.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 204.7 KB | 204.7 KB | +0 B | rootfs |
| `/usr/lib/libQt5Qml.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 3.4 MB | 3.4 MB | +0 B | rootfs |
| `/usr/lib/libQt5Quick.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.9 MB | 2.9 MB | +0 B | rootfs |
| `/usr/lib/libQt5QuickParticles.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 451.6 KB | 451.6 KB | +0 B | rootfs |
| `/usr/lib/libQt5QuickTest.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 95.9 KB | 95.9 KB | +0 B | rootfs |
| `/usr/lib/libQt5SerialPort.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 81.6 KB | 81.6 KB | +0 B | rootfs |
| `/usr/lib/libQt5Sql.so.5.5.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 244.4 KB | 244.4 KB | +0 B | rootfs |
| `/usr/lib/libQt5Test.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 176.1 KB | 176.1 KB | +0 B | rootfs |
| `/usr/lib/libQt5WaylandClient.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.0 MB | 1.0 MB | +0 B | rootfs |
| `/usr/lib/libQt5Xml.so.5.5.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 189.1 KB | 189.1 KB | +0 B | rootfs |
| `/usr/lib/libVSC.so` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 2.0 MB | 2.0 MB | +0 B | rootfs |
| `/usr/lib/libapm.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/lib/libappscommon.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 628.5 KB | 628.5 KB | +0 B | rootfs |
| `/usr/lib/libasound.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 786.2 KB | 786.2 KB | +0 B | rootfs |
| `/usr/lib/libavahi-client.so.3.2.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 56.1 KB | 56.1 KB | +0 B | rootfs |
| `/usr/lib/libavahi-common.so.3.5.3` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 41.2 KB | 41.2 KB | +0 B | rootfs |
| `/usr/lib/libavahi-core.so.7.0.2` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 192.6 KB | 192.6 KB | +0 B | rootfs |
| `/usr/lib/libcec.so.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.3 KB | 6.3 KB | +0 B | rootfs |
| `/usr/lib/libdaemon.so.0.5.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 20.1 KB | 20.1 KB | +0 B | rootfs |
| `/usr/lib/libdbus-1.so.3.8.13` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 228.7 KB | 228.7 KB | +0 B | rootfs |
| `/usr/lib/libdrm.so.2.4.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.4 KB | 39.4 KB | +0 B | rootfs |
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
| `/usr/lib/libgnutls.so.28.41.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 971.0 KB | 971.0 KB | +0 B | rootfs |
| `/usr/lib/libgobject-2.0.so.0.4400.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 293.8 KB | 293.8 KB | +0 B | rootfs |
| `/usr/lib/libgpg-error.so.0.15.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 55.6 KB | 55.6 KB | +0 B | rootfs |
| `/usr/lib/libgstapp-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 44.1 KB | 44.1 KB | +0 B | rootfs |
| `/usr/lib/libgstaudio-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 276.8 KB | 276.8 KB | +0 B | rootfs |
| `/usr/lib/libgstbase-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 346.9 KB | 346.9 KB | +0 B | rootfs |
| `/usr/lib/libgstcodecparsers-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 254.2 KB | 254.2 KB | +0 B | rootfs |
| `/usr/lib/libgstcontroller-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 46.2 KB | 46.2 KB | +0 B | rootfs |
| `/usr/lib/libgstimxcommon.so.0.12.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 27.8 KB | 27.8 KB | +0 B | rootfs |
| `/usr/lib/libgstnet-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.5 KB | 27.5 KB | +0 B | rootfs |
| `/usr/lib/libgstpbutils-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 136.3 KB | 136.3 KB | +0 B | rootfs |
| `/usr/lib/libgstreamer-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 963.4 KB | 963.4 KB | +0 B | rootfs |
| `/usr/lib/libgstriff-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 55.3 KB | 55.3 KB | +0 B | rootfs |
| `/usr/lib/libgstrtp-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 85.1 KB | 85.1 KB | +0 B | rootfs |
| `/usr/lib/libgsttag-1.0.so.0.405.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 205.1 KB | 205.1 KB | +0 B | rootfs |
| `/usr/lib/libgstvideo-1.0.so.0.405.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 249.6 KB | 249.6 KB | +0 B | rootfs |
| `/usr/lib/libgthread-2.0.so.0.4400.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 3.7 KB | 3.7 KB | +0 B | rootfs |
| `/usr/lib/libhogweed.so.4.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 174.4 KB | 174.4 KB | +0 B | rootfs |
| `/usr/lib/libimxvpuapi.so.0.10.2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 59.1 KB | 59.1 KB | +0 B | rootfs |
| `/usr/lib/libinput.so.10.5.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 102.9 KB | 102.9 KB | +0 B | rootfs |
| `/usr/lib/libipu.so.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 1.6 KB | 1.6 KB | +0 B | rootfs |
| `/usr/lib/libjpeg.so.8.0.2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 203.8 KB | 203.8 KB | +0 B | rootfs |
| `/usr/lib/libkmod.so.2.2.11` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 58.2 KB | 58.2 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ctl.so.0.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 196.9 KB | 196.9 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-ctl.so.2.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.1 KB | 218.1 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-cyg-profile-fast.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 8.4 KB | 8.4 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-cyg-profile.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.4 KB | 11.4 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-dl.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.7 KB | 11.7 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-fork.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 4.8 KB | 4.8 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-libc-wrapper.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 23.5 KB | 23.5 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-pthread-wrapper.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 16.6 KB | 16.6 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust-tracepoint.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 33.9 KB | 33.9 KB | +0 B | rootfs |
| `/usr/lib/liblttng-ust.so.0.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 335.9 KB | 335.9 KB | +0 B | rootfs |
| `/usr/lib/liblzma.so.5.2.1` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124.9 KB | 124.9 KB | +0 B | rootfs |
| `/usr/lib/libmenuw.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 25.1 KB | 25.1 KB | +0 B | rootfs |
| `/usr/lib/libmtdev.so.1.0.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 16.7 KB | 16.7 KB | +0 B | rootfs |
| `/usr/lib/libnettle.so.6.1` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 218.6 KB | 218.6 KB | +0 B | rootfs |
| `/usr/lib/libnl-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 94.2 KB | 94.2 KB | +0 B | rootfs |
| `/usr/lib/libnl-cli-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 32.1 KB | 32.1 KB | +0 B | rootfs |
| `/usr/lib/libnl-genl-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 17.6 KB | 17.6 KB | +0 B | rootfs |
| `/usr/lib/libnl-nf-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 67.6 KB | 67.6 KB | +0 B | rootfs |
| `/usr/lib/libnl-route-3.so.200.20.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 293.2 KB | 293.2 KB | +0 B | rootfs |
| `/usr/lib/libnss_myhostname.so.2` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 49.6 KB | 49.6 KB | +0 B | rootfs |
| `/usr/lib/liborc-0.4.so.0.23.0` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 410.6 KB | 410.6 KB | +0 B | rootfs |
| `/usr/lib/libpanelw.so.5.9` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 10.1 KB | 10.1 KB | +0 B | rootfs |
| `/usr/lib/libpixman-1.so.0.32.6` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 565.0 KB | 565.0 KB | +0 B | rootfs |
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
| `/usr/lib/liburcu-mb.so.2.0.0` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.2 KB | 20.2 KB | +0 B | rootfs |
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
| `/usr/lib/qt5/plugins/bearer/libqconnmanbearer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 172.4 KB | 172.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/bearer/libqgenericbearer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44.7 KB | 44.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/bearer/libqnmbearer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 205.1 KB | 205.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/egldeviceintegrations/libqeglfs-viv-integration.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 11.0 KB | 11.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevkeyboardplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 51.0 KB | 51.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevmouseplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 36.9 KB | 36.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevtabletplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 28.0 KB | 28.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqevdevtouchplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 51.1 KB | 51.1 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/generic/libqtuiotouchplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 42.6 KB | 42.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/imageformats/libqgif.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.2 KB | 19.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/imageformats/libqico.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.5 KB | 19.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/imageformats/libqjpeg.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 32.2 KB | 32.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforminputcontexts/libibusplatforminputcontextplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 71.4 KB | 71.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqeglfs.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqminimal.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 27.5 KB | 27.5 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqminimalegl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 573.2 KB | 573.2 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqoffscreen.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 560.7 KB | 560.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqwayland-egl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 48.0 KB | 48.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/platforms/libqwayland-generic.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/position/libqtposition_phocus.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.7 KB | 22.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/position/libqtposition_suc.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 44.4 KB | 44.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-decoration-client/libbradient.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.8 KB | 22.8 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-client/libdrm-egl-server.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 12.6 KB | 12.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-client/libwayland-egl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 43.7 KB | 43.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-server/libdrm-egl-server.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.6 KB | 18.6 KB | +0 B | rootfs |
| `/usr/lib/qt5/plugins/wayland-graphics-integration-server/libwayland-egl.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.7 KB | 10.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/folderlistmodel/libqmlfolderlistmodelplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 47.4 KB | 47.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/folderlistmodel/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 2.0 KB | 2.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/folderlistmodel/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 124 B | 124 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/Qt/labs/settings/libqmlsettingsplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 17.5 KB | 17.5 KB | +0 B | rootfs |
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
| `/usr/lib/qt5/qml/QtQml/Models.2/libmodelsplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/Models.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 19.4 KB | 19.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/Models.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 86 B | 86 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/StateMachine/libqtqmlstatemachine.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 47.9 KB | 47.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/StateMachine/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 5.7 KB | 5.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQml/StateMachine/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 111 B | 111 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick.2/libqtquick2plugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.0 KB | 7.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 215.4 KB | 215.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 106 B | 106 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/LocalStorage/libqmllocalstorageplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 43.3 KB | 43.3 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/LocalStorage/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 640 B | 640 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/LocalStorage/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 116 B | 116 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Particles.2/libparticlesplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Particles.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 39.4 KB | 39.4 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Particles.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 108 B | 108 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Window.2/libwindowplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 6.9 KB | 6.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Window.2/plugins.qmltypes` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 10.0 KB | 10.0 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtQuick/Window.2/qmldir` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 117 B | 117 B | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/SignalSpy.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 7.7 KB | 7.7 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/TestCase.qml` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 53.9 KB | 53.9 KB | +0 B | rootfs |
| `/usr/lib/qt5/qml/QtTest/libqmltestplugin.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 20.2 KB | 20.2 KB | +0 B | rootfs |
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
| `/usr/lib/weston/fbdev-backend.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 35.7 KB | 35.7 KB | +0 B | rootfs |
| `/usr/lib/weston/gal2d-renderer.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 22.0 KB | 22.0 KB | +0 B | rootfs |
| `/usr/lib/weston/victory-shell.so` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 26.2 KB | 26.2 KB | +0 B | rootfs |
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
| `/usr/sbin/sshd` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 690.5 KB | 690.5 KB | +0 B | rootfs |
| `/usr/sbin/wpa_supplicant` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 912.2 KB | 912.2 KB | +0 B | rootfs |
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
| `/usr/share/common-licenses/kernel-module-leds-gpio/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-libphy/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-lis3dsh-acc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-llc/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-m25p80/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
| `/usr/share/common-licenses/kernel-module-max5842/COPYING` | ![UNCHANGED](https://img.shields.io/badge/-UNCHANGED-lightgrey) | 18.3 KB | 18.3 KB | +0 B | rootfs |
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
| `/usr/share/common-licenses/license.manifest` | ![CHANGED](https://img.shields.io/badge/-CHANGED-yellow) | 31.0 KB | 31.0 KB | +0 B | rootfs |
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
