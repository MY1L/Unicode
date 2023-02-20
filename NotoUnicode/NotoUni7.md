# Noto Unicode 7.x
从七版起更新幅度巨大，名称[拟译][fallback]「无缺通天」

目前是单色字体，第7版之后与Noto不同，我的设计以文字缩写标明字形的颜色，如心形“💙💚💛💜🖤🤍🤎🧡🩵🩶🩷”和肤色“🏻🏼🏽🏾🏿”。彩色字体的需求可用[Ctrl Zsye](https://github.com/MY1L/Ctrl#zsye)解决。

|缩写|R|G|B|C|M|Y|K|W|A|O|P|S|T|V|Pl|Br|Gy|Pk|Og|
| -: |-|-|-|-|-|-|-|-|-|-|-|-|-|-|- |- |- |- |- |
|颜色| |绿|蓝|青| |黄|黑| | |橙|||||紫|褐|灰|粉||
|预留未用|红||||粉| | |白|透||紫|灰|茶|堇|||||橙|<!-- www.docin.com/p-447661016.html -->

下文凡`uXXXX`是具体码位，而`XXXX..`是区段，相关对应[首页都有](https://github.com/MY1L/Unicode)。

## 简要回顾
第一至五版略，见[自述文件](/NotoUnicode)。

v5→6.9 细节详见：[Release Noto Unicode v5.9~6.9 · MY1L/Unicode](https://github.com/MY1L/Unicode/releases/tag/NotoUni6)

- v5.901
  - 自Noto补充10个区段字形
  - 自制以补全统一码14版区段：`0600..`、`1DC0..`、`1F100..`、`1F780..`
  - 自制全部埃及控制符替代字形`13430..`，甚至支持部分[统一码15版将加入的](https://unicode.org/charts/PDF/Unicode-15.0/U150-13430.pdf)
  - 自制十眼 ꙮ`uA66E`，将在统一码15版修正
  - 自创更易理解的区域指示符替代字形、修正NotoSansSymbols错误 🄌`u1F10C`
  - 自制和借用煮豆以补全`1F200..`：🉠🉡🉢🉣🉤🉥
  - 自制以支持私用区增甲的安卓绘文字：󾠬󾠮󾠯󾠰󾠱󾠲󾠳󾠴󾠵󾠶󾠷 󾓥󾓦󾓧󾓨󾓩󾓪󾓫󾓬󾓭󾓮
  - 其它更新…

- v6β
  - 自Noto补充约14个区段字形
  - 自[Mezenets Unicode](https://github.com/slavonic/fonts-znam)(OFL1.1)1.100补充兹纳缅内音符`1CF00..`
  - 更新若干区段字形，尤其契丹小字替换为Noto仿宋KSSVertical 1.000，[如图](https://user-images.githubusercontent.com/58043328/213433845-ae5f042c-8f00-4922-911c-f35bd473daa9.png)

  > 已知问题：若干区段字形画风未统一。

  > 非问题
  > 1. 本字体如预想那样相比Noto系列全装总体积要小不少，唯Noto西夏宋缺乏可压缩空间（除非搞类似有损曲线之类我不愿做的事）字多、体积又大，不如单独安装，所以未合并它。
  > 2. [如我之前展示的](https://www.bilibili.com/read/cv9204898)，契丹小字有不同于汉字、契丹大字…的“拼字”性质，让它呈现为非黑体有利于上下文区分。

- v6.9
  - 从[Monu Hani 9](https://github.com/MY1L/Unicode/releases/tag/Hani9)迁来我做的画正字，改善若干字形
  - 考虑到Noto女书[有多余汉字](https://github.com/notofonts/nushu/issues/7)影响[fallback]，添加`1B170..`，采用2.003版已修正的传统字形，并替换原有的女书重复号
  - 我补完的`31A0..`整个区段字形现在移给[Monu Hani 9.x](https://github.com/MY1L/Unicode/blob/main/Hani)
  - 其它更新…

  > 已知问题：若干区段字形画风仍未统一。

## 更新

### 2023-2-12 v7

#### 添加或替换
从 [Ctrl Ctrl 1].1 迁来部分替换原有字形：
- ` 0000..`Latn.+33控制字图符
- ` 0080..`Latn1.+32控制字图符
- ` 0870..`ArabExtB.+2
- ` FE00..`VS.+16，补全
- `13430..`EgypFC.+38，补全
- `1D100..`Music.+9，具体见下
- `E0000..`Tags.+97，补全
- `E0100..`VsSup.+240，补全

从 NotoSans 2.010 补充和刷新大量字形（不完全列举，其中字形不佳的排除，仍用自制）：
- ` 1AB0..`DiacExt. +9，未补全(26/31)
- ` 2E00..`SupPunc. +11，补全，替代我自制的那些（`u2E55~2E58` `u2E5D`）
- ` A720..`LatnExtD.+13，补全
- `10780..`LatnExtF.+57，补全
- `1DF00..`LatnExtG.+31，未补全(31/37)

从NotoEmoji-Bold 2.001补充大量字形，由于其upm为2048与Noto自家upm1000不兼容，我有意将字形折半(1024)upm改1000以减小曲线损失，同时1024的NotoEmoji相比1000的NotoSym.字形会大一点。此外的曲线问题为原字形自带、或合并、或2转3次曲线时产生。手动合并48个，修正52个(问题多在轮廓反向，谷歌应加强下质检…)
- `1F300..`MiscPic.  +549
  - 修正或自制`u1F311~1F318`（月球加上月兔环形山方便与黑白圆区分） `u1F31A` `u1F322` `u1F323` `u1F385` `u1F394` `u1F3F6` `u1F3FB~1F3FF` `u1F46C~1F46D` `u1F478` `u1F483` `u1F499~u1F49C` `u1F4B9` `u1F50E` `u1F534~1F535` `u1F57A` `u1F5A4`
- `1F680..`TransMap.  +91
  - 修正或自制`u1F6AB` `u1F6AC` `u1F6BB` `u1F6C7` `u1F6D1` `u1F6D5`
- `1F900..`SupSymPic.+236
  - 自制或修改`u1F90E` `u1F930` `u1F934` `u1F936` `u1F9E1` `u1F9E7`（我觉得没有黑体福字的红包）
- `1FA70..`SymPicExtA.+66
  - 自制或修改`u1FA75~1FA77` `u1FA84` `u1FAC3`
- 自制私用区`uFE82B`以兼容NotoEmoji(SVG)2.100

#### 自制以补全
- 自制`u1AC1~1AC4` `u1AC6`补全`1AB0..`DiacExt.区段
- 自制`u23B7~23BD` `u23F0`补全`2300..`MiscTech.区段
- 自制`u2C2F` `u2C5F`补全`2C00..`Glag.区段
- 自制`u110C2`补全`11080..`Kthi.区段
- 自制`u1123F~11241`补全`11200..`Khoj.区段
- 自制`u116B9`补全`11680..`Takr.区段
- 自制`u11740~11746`补全`11700..`Ahom.区段
- ~~自制`u1F6DC`🛜无线标志 补全`1F680..`TransMap.区段~~

#### 自制和追加
- 自制整个`1D2C0..`Kaktovik Numerals区段：𝋀𝋁𝋂𝋃𝋄𝋅𝋆𝋇𝋈𝋉𝋊𝋋𝋌𝋍𝋎𝋏𝋐𝋑𝋒𝋓，Ctrl Math 0.9
- 自制`u0B55`补全`0B00..`Orya.区段，NotoSansOriya 2.003
- 自制`u0C3C` `u0C5D`补全`0C00..`Telu.区段，NotoSansTelugu 2.003
- 自制`u0CDD` `u0CF3`补全`0C80..`Knda.区段，NotoSansKannada 2.003
- 补全`0D00..`Mlym.区段，NotoSansMalayalam 2.103
- 自制`u0ECE`补全`0E80..`Lao.区段，NotoSansLaoLooped 1.001
- 补全和刷新`1700..`Tglg.区段，NotoSansTagalog 2.001
- 补全和刷新`1B00..`Bali.区段，NotoSansBalinese 2.004
- 自制`u11070~11075`补全`11000..`Brah.区段，NotoSansBrahmi 2.003
- 自制 𓐯`u1342F`补全`13000..`Egyp.区段，NotoSansEgyptianHieroglyphs 2.001
- 自制[Ctrl Ctrl 1].1 `u1D159` `u1D173~1D17A`补全`1D100..`Music.区段，NotoMusic 2.002
- 自制`u1F774~1F77F`补全`1F700..`Alch.区段，NotoSansSymbols 2.002
- 私用区放了个统一码UNi连字标志备用 `uE00F`

#### 修改
- 改善自制的阿拉伯 ؝`u061D`字形
- NotoSym.2的电源符号难看，替换为我画的：⏻⏼⏽`u23FB~23FD`
- 重画钟表符号 ⌚`u231A` ⏰⏱⏲`u23F0~23F2`
- 修改Noto婆罗米`u11000` `u11044` `u11045`
- 修正Noto埃及圣书体 𓍹𓍺𓍻`u13379~1337B`，未查是否还有其它问题
- 改善契丹小字`u18B0D`字形
- NotoSym.的炼金术符比较难看，先改了 🜁`u1F701` 🜃`u1F703` 🜍`u1F70D` 🜿`u1F73F`

#### 移除
- ` 10A0..`Geor.-88　 ：Calibri等系统字体已覆盖
- ` 1C90..`GeorExt.-46：Calibri等系统字体已覆盖
- ` 2D00..`GeorSup.-40：Calibri等系统字体已覆盖
- ` 2400..`CtrlPict.-33：NotoUni不全，且系统字体Segoe UI Symbol已覆盖
- ` 27C0..`MiscMathA.-48：Segoe UI Symbol等系统字体已覆盖
- ` A700..`ModToneLttr.-32：系统字体Segoe UI已覆盖
- `1E900..`Adlm.-88　：系统字体Ebrima已覆盖

### 2023-2-14 v7.01
- 尝试改善OTF压缩方式，容量不变的情况下减少近1MB。
- 字体字系分类改为2-0-5-3-0-0-0-0-0-0，但这局限于拉丁的狭隘分类早过时了没什么影响，感觉本字体可以全归零的。
- 给上万个字形填名称。
- 改善 🝼`u1F77C` 🝽`u1F77D` 🤰`u1F930` 🫃`u1FAC3`等字形。
- 改善全部有色心形（除粗黑“红”心❤、白心🤍）

### 2023-2-15 v7.02
- 据 Ctrl Math 1 修正卡克托维克数字：4𝋄 9𝋉 14𝋎 19𝋓
- 改善.notdef字形
- 其它更新…

### 2023-2-17~18 v7.1
当前总字形21536个，对应21534+32个码位
#### 自制
- `0870..`ArabExtB.，Noto全无，[Ctrl Ctrl 1] 有2个
  - 我之前补了11个，尚缺30，补了26个 ࡲ ‎ࡳ ‎ࡶ ‎ࡷ ‎ࡸ ‎ࡹ ‎ࡺ ‎ࡻ ‎ࡼ ‎ࡽ ‎ࡾ ‎ࡿ ‎ࢀ ‎ࢁ ‎ࢂ ‎ࢃ ‎ࢄ ‎ࢅ ‎ࢆ ‎ࢇ ‎࢈ ‎ࢎ　 ࢜　 ࢝　 ࢞　 ࢟
  - 从SIL字体[Scheherazade]New(OFL1.1)3.300补充4个　 ࢘　 ࢙　 ࢚　 ࢛\
    |
    - 由于该字体是upm2048的ttf，因此采取同对[NotoEmoji](#添加或替换)的特殊处理，仔细地将曲线二转三合并。
    - 附注：统一码pdf似乎不准确，`u0886`是`u064A`的薄版，不一定是`uFEF3`的小型，不过按统一码的来。

- `08A0..`ArabExtA.，Noto缺21字
  - 我之前补了5个，尚缺16，补全 ࣃ ‎ࣄ ‎ࣅ ‎ࣆ ‎ࣇ ‎ࣈ　 ‎ࣉ　 ࣊　 ࣋　 ࣌　 ࣍　 ࣎　 ࣏　 ࣐　 ࣑　 ࣒
    - 附注：`u08C4`与`u06A8`的默认形态一致。

- `FB50..`ArabPFA.，Noto缺20字
  - 补了 ﯂`uFBC2`
  - 从[Scheherazade]New 3.300补充19个[敬语连字｜Honorific ligatures](https://software.sil.org/scheherazade/honorifics/) ‎﵀﵁﵂﵃﵄﵅﵆﵇﵈﵉﵊﵋﵌﵍﵎﵏﷏﷾﷿ 的[.smpl版](https://software.sil.org/scheherazade/features/)。

- `1DF00..`LatnExtG.，Noto2.010缺6字
  - 补了 𝼥𝼦𝼧𝼨𝼩𝼪

- `1E030..`CyrlExtD.，Noto全无(缺63字)
  - 补全！𞀰𞀱𞀲𞀳𞀴𞀵𞀶𞀷𞀸𞀹𞀺𞀻𞀼𞀽𞀾𞀿𞁀𞁁𞁂𞁃𞁄𞁅𞁆𞁇𞁈𞁉𞁊𞁋𞁌𞁍𞁎𞁏𞁐𞁑𞁒𞁓𞁔𞁕𞁖𞁗𞁘𞁙𞁚𞁛𞁜𞁝𞁞𞁟𞁠𞁡𞁢𞁣𞁤𞁥𞁦𞁧𞁨𞁩𞁪𞁫𞁬𞁭 𞂏
    - 可见[Cyrillic Ext-D与Noto原有音标混排的截屏](https://www.bilibili.com/read/cv21785991)

#### 修改
- 调整阿拉伯字形名称：`0600..` `0750..` `0870..` `08A0..` `FB50..` `FE70..`
- 又又改善 ؝`u061D`字形
- 将`1D800..`萨顿手语字形改为明确的 [Ctrl Ctrl 1].1

[Scheherazade]: https://software.sil.org/scheherazade/
[Ctrl Ctrl 1]: https://github.com/MY1L/Ctrl/releases/tag/Ctr1
[fallback]: https://github.com/MY1L/Unicode/tree/main/FontList#列表说明 "FontList"

### 2023-\*-\* v7.1+ 进行中
拟移除：`0B80..`Tamil：系统字体Nirmala UI已覆盖

性别相关绘文字调整：💃🕺🤰🫃👸🤴👬👭🎅🤶

质检发现了若干小问题。修正这些字形（不完全列举）：`u0B1B` `u0B28` `u0B61` `u0B63` `u0D40` `u0D47` `u0D4B` `u0D56` `u0D59` `u0D5E` `u0D62` `u0D72` `u0D77` `u0D79` `u0E97` `u0E9A` `u0E9B` `u0E9C` `u0E9E` `u0E9F` `u0EA8` `u0EA9` `u0EAB` `u0EB0` `u0EB1` `u0EB2` `u0EB3` `u0EB5` `u0EB7` `u0EBB` `u0EC9` `u0EDC` `u0EDD` `u0EDE` `u0EDF` `u170D` `u1B1B` `u1B28` `u2139` `u23F2` `u2E3F` `uA755` `uA7A1` `uA7AF` `uFD4B` `u1104D` `u13014` `u13015` `u13018` `u1302C` `u13030` `u13031` `u13048` `u13077` `u13089` `u130D4` `u130D5` `u130D6` `u130D9` `u130DA` `u130DC` `u130E5` `u130EA` `u130F0` `u130F1` `u130F3` `u130F4` `u130F8` `u130F9` `u13101` `u13108` `u13116` `u13128` `u13140` `u13142` `u13146` `u13149` `u1314B` `u13155` `u13156` `u1315A` `u1315F` `u1316D` `u13171` `u13172` `u1317A` `u1317C` `u1318B` `u13197` `u131A3` `u131A7` `u131A8` `u131B0` `u1322C` `u1322E` `u1322F` `u13233` `u13234` `u13236` `u13247` `u13264` `u1329C` `u1329E` `u132C6` `u132C8` `u132E7` `u13309` `u1330B` `u1330C` `u1330D` `u13314` `u13344` `u13383` `u1B1B7` `u1B1BB` `u1B1C3` `u1B1C9` `u1B1F9` `u1B1FB` `u1B207` `u1B20A` `u1B226` `u1B248` `u1B24E` `u1B258` `u1B273` `u1B275` `u1B27A` `u1B281` `u1B29A` `u1B2C6` `u1B2C8` `u1B2ED` `u1B2FB` `u1CF07` `u1CF08` `u1CF0A` `u1CF0B` `u1CF13` `u1CF14` `u1CF16` `u1CF17` `u1CF1B` `u1CF1D` `u1CF1F` `u1CF45` `u1CF60~1CF6A` `u1CF63~1CF69` `u1CF78` `u1CFC3` `u1F15C` `u1F15D` `u1F17C` `u1F17D` `u1F18E` `u1F216` `u1F220` `u1F227` `u1F22B` `u1F22F` `u1F23B` `u1F251` `u1F3DF` `u1F408` `u1F74F` `u1FAB2` `u1FB91`……

## 已知问题
舞者💃🕺只有男女，中性无单独编码，也没有Emoji Sequences|绘文字序列，原因在 💃`u1F483` Unicode Name “DANCER”本就是中性词，而CLDR Name是“woman dancing”，🕺`u1F57A`的两个都是“man dancing”。我是否应该在下一版把舞女改成舞者？

Noto婆罗米(笈多？)字形与统一码 [U11000.pdf](http://www.unicode.org/charts/PDF/U11000.pdf) 范例不同。\
Noto 𞊜`u1E29C`字形与统一码 [U1E290.pdf](http://www.unicode.org/charts/PDF/U1E290.pdf) 范例不同。

截至2023-2-21，\
https://github.com/notofonts/kawi “Noto Sans Kawi”、\
https://github.com/notofonts/nag-mundari “Noto Sans Nag Mundari”、\
https://github.com/notofonts/ottoman-siyaq-numbers “Noto Sans Ottoman Siyaq Numbers”\
仍然是空的。