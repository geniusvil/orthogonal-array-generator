# OrthogonalArrayGenerator (OAG) #


- Simple Orthogonal Array Generator


- PICT style model file


- command line tool

- Linux and Windows binaries are available


## exmaple ##

---

```
model_file_01
------------------
ZZZ : z_1, z_2 ,z_3, z_4
AAA : a_1, a_2
BBB : b_1, b_2
CCC : c_1, c_2
DDD : d_1, a_2
EEE : e_1, e_2
FFF : f_1, f_2
GGG : g_1, g_2
HHH : h_1, b_2
III : i_1, i_2
JJJ : j_1, j_2
KKK : k_1, k_2
LLL : l_1, l_2
------------------
```


OAG.exe  model\_file\_01
```
ZZZ AAA BBB CCC DDD EEE FFF GGG HHH III JJJ KKK LLL
z_1 a_1 b_1 c_1 d_1 e_1 f_1 g_1 h_1 i_1 j_1 k_1 l_1
z_1 a_1 b_1 c_1 d_1 e_2 f_2 g_2 b_2 i_2 j_2 k_2 l_2
z_1 a_2 b_2 c_2 a_2 e_1 f_1 g_1 h_1 i_2 j_2 k_2 l_2
z_1 a_2 b_2 c_2 a_2 e_2 f_2 g_2 b_2 i_1 j_1 k_1 l_1
z_2 a_1 b_1 c_2 a_2 e_1 f_1 g_2 b_2 i_1 j_1 k_2 l_2
z_2 a_1 b_1 c_2 a_2 e_2 f_2 g_1 h_1 i_2 j_2 k_1 l_1
z_2 a_2 b_2 c_1 d_1 e_1 f_1 g_2 b_2 i_2 j_2 k_1 l_1
z_2 a_2 b_2 c_1 d_1 e_2 f_2 g_1 h_1 i_1 j_1 k_2 l_2
z_3 a_1 b_2 c_1 a_2 e_1 f_2 g_1 b_2 i_1 j_2 k_1 l_2
z_3 a_1 b_2 c_1 a_2 e_2 f_1 g_2 h_1 i_2 j_1 k_2 l_1
z_3 a_2 b_1 c_2 d_1 e_1 f_2 g_1 b_2 i_2 j_1 k_2 l_1
z_3 a_2 b_1 c_2 d_1 e_2 f_1 g_2 h_1 i_1 j_2 k_1 l_2
z_4 a_1 b_2 c_2 d_1 e_1 f_2 g_2 h_1 i_1 j_2 k_2 l_1
z_4 a_1 b_2 c_2 d_1 e_2 f_1 g_1 b_2 i_2 j_1 k_1 l_2
z_4 a_2 b_1 c_1 a_2 e_1 f_2 g_2 h_1 i_2 j_1 k_1 l_2
z_4 a_2 b_1 c_1 a_2 e_2 f_1 g_1 b_2 i_1 j_2 k_2 l_1
```




OAG.exe  model\_file\_01  -show
```
--------------------------------------------------------
## Orthogonal Array
## array data
# number of parameters = 13
# level                = 2
# test size            = 16
#--------------------------------------------------------
## 2-way coverage
# coverage rate        : 100 %
# 2-way combinations   : 360
# covered combinations : 360
## 3-way coverage
# coverage rate        : 92 %
# 3-way combinations   : 2816
# covered combinations : 2608
#--------------------------------------------------------
## Confirm Array
# J2(d) : 4056
# L(n)  : 4056
# ratio : 1
#--------------------------------------------------------
## result array
ZZZ AAA BBB CCC DDD EEE FFF GGG HHH III JJJ KKK LLL
z_1 a_1 b_1 c_1 d_1 e_1 f_1 g_1 h_1 i_1 j_1 k_1 l_1
z_1 a_1 b_1 c_1 d_1 e_2 f_2 g_2 b_2 i_2 j_2 k_2 l_2
z_1 a_2 b_2 c_2 a_2 e_1 f_1 g_1 h_1 i_2 j_2 k_2 l_2
z_1 a_2 b_2 c_2 a_2 e_2 f_2 g_2 b_2 i_1 j_1 k_1 l_1
z_2 a_1 b_1 c_2 a_2 e_1 f_1 g_2 b_2 i_1 j_1 k_2 l_2
z_2 a_1 b_1 c_2 a_2 e_2 f_2 g_1 h_1 i_2 j_2 k_1 l_1
z_2 a_2 b_2 c_1 d_1 e_1 f_1 g_2 b_2 i_2 j_2 k_1 l_1
z_2 a_2 b_2 c_1 d_1 e_2 f_2 g_1 h_1 i_1 j_1 k_2 l_2
z_3 a_1 b_2 c_1 a_2 e_1 f_2 g_1 b_2 i_1 j_2 k_1 l_2
z_3 a_1 b_2 c_1 a_2 e_2 f_1 g_2 h_1 i_2 j_1 k_2 l_1
z_3 a_2 b_1 c_2 d_1 e_1 f_2 g_1 b_2 i_2 j_1 k_2 l_1
z_3 a_2 b_1 c_2 d_1 e_2 f_1 g_2 h_1 i_1 j_2 k_1 l_2
z_4 a_1 b_2 c_2 d_1 e_1 f_2 g_2 h_1 i_1 j_2 k_2 l_1
z_4 a_1 b_2 c_2 d_1 e_2 f_1 g_1 b_2 i_2 j_1 k_1 l_2
z_4 a_2 b_1 c_1 a_2 e_1 f_2 g_2 h_1 i_2 j_1 k_1 l_2
z_4 a_2 b_1 c_1 a_2 e_2 f_1 g_1 b_2 i_1 j_2 k_2 l_1
```




---

model\_file\_04
```
#
# Machine 1
#
OS_1:   Win2000, WinXP
SKU_1:  Professional, Server, Datacenter, WinPowered
LANG_1: EN, DE
 
#
# Machine 2
#
OS_2:   Win2000, WinXP
SKU_2:  Professional, Server, Datecenter, WinPowered
LANG_2: EN, DE

#
# WinXP is always Professional in our case
#
if [OS_1] = "WinXP" then [SKU_1] = "Professional";
if [OS_2] = "WinXP" then [SKU_2] = "Professional";

#
# No German WinPowered 
#
if [SKU_1] = "WinPowered" then [LANG_1] = "EN";
```



OAG.exe  model\_file\_04

```
Win2000, Professional, EN, Win2000, Professional, EN
Win2000, Professional, EN, Win2000, Server, DE
Win2000, Server, DE, WinXP, Professional, EN
Win2000, Datacenter, DE, Win2000, Datecenter, DE
Win2000, Datacenter, DE, Win2000, WinPowered, EN
```
