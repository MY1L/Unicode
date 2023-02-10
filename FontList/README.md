# 字体列表
分析视窗10系统字体对统一码的覆盖情况，减轻工具字体的制作量、减少文件体积：系统字体完全覆盖的区段可以省略。

## 平面状况
以下展示所需覆盖量，统计截至统一码15.0.0版。

|#|简称|平面名|译称|字数|余数|
| -: | -: | -: | :- | -: | -: |
|0|BMP|Basic Multilingual Plane|基本多文种平面|62034|1420|
|1|SMP|Supplementary Multilingual Plane|增补多文种平面|23276|42258|
|2|SIP|Supplementary Ideographic Plane|增补表意平面|60873|4661|
|3|TIP|Tertiary Ideographic Plane|第三表意平面|9131|56403|
|…| | | | | |
|E|SSP|Supp. Special-purpose Plane|增补殊用平面|337|65197|

## 列表说明
[FontList.csv](/FontList/FontList.csv)，截止统一码15.0.0版，仅反映视窗10的字体覆盖情况。

字体名第一次出现时后方附带的是分析时的版本号。“，等”表示能完全覆盖的系统字体不只一个。

如列表所示，如需视窗10环境下几乎全覆盖统一码，~~仅~~需额外安装下列字体：
- [Noto Unicode](/NotoUnicode) 6.9（已含[Ctrl Runr](https://github.com/MY1L/Ctrl#runr) β6、[Ctrl Ctrl] 1.002）
- [Monu Hani](/Hani) 9.2
  - Monu Han2 4.393
  - Monu Han3 1.175
- Noto Serif Tangut 2.169
- [Monu Last 8](https://github.com/MY1L/Unicode/releases/tag/Last8)（非必要）

注意以上排序严格按后备（fallback）顺序从上至下，尤其Noto西夏宋包含的非西夏衬线体字符会覆盖其它字体的，所以应垫底（被其它字体覆盖非西夏区段）

[Ctrl Ctrl] 是个完全的原创工具字体，用于让那些统一码规定没有字形的 控制字、变体选择符、格式控制符、空格、标签 等尽量显示替代字形以便选择复制。其字形形如 Last 和 [Monu Hani](/Hani)的表意描述符。作为有专门用途的工具，它会干扰日常使用——你应该不会希望网页上每个空格都是可见的吧？所以NotoUni只会选择性包含它的部分字形，出于需要可以另外下载它。

[Ctrl Ctrl]: https://github.com/MY1L/Ctrl#ctrl

## 注册表与“关键”字体
如果你还了解注册表，可以安装字体后查阅`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts`，然后到
```
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontLink\SystemLink
```
给系统界面字体添加后备。

同时，你可以在`\SystemLink`中看到有几个“关键”字体在列表中频繁出现，它们分工是：
- Ebrima：非洲文种
- Gadugi：北美文种
- Leelawadee UI：东南亚文种
- Malgun Gothic：泛·谚文
- Nirmala UI：南亚文种 —— 老实说我觉得NotoUni与Nirmala重复的区段可以移除了🤔

题外话，看注册表`\CurrentVersion\FontSubstitutes`可见微软比较认同“Helvetica”简称“Helv”、“Times New Roman”简称“Tms Rmn”