# <ruby><rb>典迹末境</rb><rt>Monu Last</rt></ruby>
这是一个用于显示统一码现在及未来全部111万4112个码位的系统垫底（Last Resort）字体。\
先前有过多次介绍，除了 [B站视频](https://www.bilibili.com/video/BV1XT4y1N7TG/)，还有专栏：
- [未来统一码字体前瞻及考据：MonuLast][futu]
- [吐谷渾、pIqaD、水书…“最大”字体「典迹末境」Next：超统一码；⋯][next]
- [争战统一码第十平面・字体｢典迹末境｣v8.10发布][gb22]
- ⋯⋯

作为工具字体，亦可用于区分同形异码，和将字形赋予不可见的特殊字符。\
主要包含两种字形：**样字**（标本）和**例字**，此外就是组成样字的零件。通常，每区段取一例字作为代表，只有**例字**的字符呈现为自身字形，其它字符都加上模仿｢｣号的收容框、在左侧标注代码呈现为**样字**字形，方便进入文档查询字符。
> 用法：`www.unicode.org/charts/PDF/U【代码】.pdf`

也有些区段或保留码位不存在例字，这种情况下只有圆角矩形状的样字。同时，为了区分：
- 统一码规划中的预留区段，其例字收容框右上角是“**？**”
- 非统一码方案被分配到私用区的，其例字收容框左下角是篆书的“**厶**(私)”
- 非统一码亦无分配的放到私用区增乙，其例字收容框左上角是“✖(叉)＼**X**(未知)”
- GB18030-2022 公安人口信息专用字库补充汉字“第十平面”，其例字收容框右下角是“**十**”

[Cher]: https://www.bilibili.com/read/cv7803547 "切罗基文"
[ktxx]: https://www.bilibili.com/read/cv9204898 "契丹西夏"
[futu]: https://www.bilibili.com/read/cv11030010 "未来考据"
[hmos]: https://www.bilibili.com/read/cv11653743 "鸿蒙优缺"
[next]: https://www.bilibili.com/read/cv22807456 "超统一码"
[gb22]: https://www.bilibili.com/read/cv23078044 "第十平面"
[UcB2]: https://github.com/MY1L/Unicode/tree/main/Blocks#双标 "Blocks#双标"
[ISO 15924]: https://github.com/MY1L/Unicode/tree/main/abbr "abbr"
[pic]: https://github.com/MY1L/Unicode/issues/12 "🖻"
[v815]: https://t.bilibili.com/857896296924577829 "B站动态：8.15版更新"

## 更新
2021-1-16 [v6.0](https://github.com/MY1L/Unicode/releases/tag/v6.0)：初发布，含彩色字体，1-20更新[v6.1](https://github.com/MY1L/Unicode/releases/tag/v6.1)。

2021-9-17 [v7.12](https://github.com/MY1L/Unicode/releases/tag/v7.12)：覆盖统一码14.0版。

2023全年：详见 [v8.x](https://github.com/MY1L/Unicode/releases/tag/Last8) 更新记录。

2024-… v8.20：
- 继续补充、修改路线图区段：`Tutg.11380`、`u113BA`◌𑎺
- 改善字形：于阗
- 新增鸟甲

## 一览
下表展示每个例字的来源。出典[插图🖻一览][pic]，例字要求兼顾 知名度（**著名**、更眼熟的）和 **区分**度（最特别、不易混淆的）\
如果对典迹末境的例字有什么意见建议⸺尤其是标为“待替”的⸺可在上一行的链接里回复。

**理论范围**指[统一码该区段码位范围](https://github.com/MY1L/Unicode/tree/main/Blocks "Blocks")，具体到字形则不一定，例如`Latn.`实际`20`为始`7E`为终，其中的控制字见[#特殊](#特殊)。这一列大多链接到[统一码码表 (Unicode Character Code Charts)](https://www.unicode.org/charts/)
> **注意**：汉字 PDF 体积很大 (Han.:38MB，HanExtA.:7.6MB，HanExtB.:31MB)；规划区段的 PDF⚠只是占位，**打不开**的。

**样字名**以`.`结尾的省略理论范围始码，例如`Latn.`实为`Latn0000`；以`!`结尾是我诌的仿 [ISO 15924] 缩写，缩略可能冲突。\
**例字名､义**以`~`结尾的省略码位，例如`thai~`实为`thai0E05`。

### 标注
- ⚠：截至统一码15.1此区段尚为规划，码位可能冲突
  - 🛑：此区段有意外用途，未来码位或有冲突
  - 🩲：码位在私用区里
  - 👻：无预留区段
  - ◌：此区段字符需挂(Combining)在别的字符上，因此例字多了个◌以便复制
  - ⬚：此区段字符通常零宽不可见(invisible)，有些用｢｣号夹起以便复制
  - ⬅：此区段排版方向主要是从左往右
  - ⤵：样字内的例字经过旋转
- 备注⸺
  - **(已正式被 UTC 或 WG2 接受的)**
  - (已正式向 UTC 或 WG2 提案的)
  - ¿尚未编写详细提案的?
  - ¿¿¿欠规划的???
  - ≈：其它可能冲突的缩略
  - =：不冲突的更短缩略

理论范围|⚠|样字名|例字及码|例字名､义|出典或备注
|-:|:-:|-|-|-|-|
[`0000~007F`](https://www.unicode.org/charts/PDF/U0000.pdf)|	|Latn.			|`0061`a|`latn.a`拉丁“a”小写|
[`0080~00FF`](https://www.unicode.org/charts/PDF/U0080.pdf)|	|Latn1_.		|`00F8`ø|`latn.oslash`	|样字曾用名`Latn1Sup.0080`
[`0100~017F`](https://www.unicode.org/charts/PDF/U0100.pdf)|	|LatnExtA.		|`017A`ź|`latn.zacute`	|
[`0180~024F`](https://www.unicode.org/charts/PDF/U0180.pdf)|	|LatnExtB.		|`0237`ȷ|`latn~`	|例字曾用名`latn.dotlessj`
[`0250~02AF`](https://www.unicode.org/charts/PDF/U0250.pdf)|	|IPAExt.		|`029E`ʞ|`latn.kturn`	|
[`02B0~02FF`](https://www.unicode.org/charts/PDF/U02B0.pdf)|	|ModLttr.		|`02C7`ˇ|`caron`抑扬符|非结合变音标记
[`0300~036F`](https://www.unicode.org/charts/PDF/U0300.pdf)|◌|Diac.			|`0338`◌̸|`comb~`	|
[`0370~03FF`](https://www.unicode.org/charts/PDF/U0370.pdf)|	|Grek.			|`03C0`π|`grek.pi`希腊“pi”小写|
[`0400~04FF`](https://www.unicode.org/charts/PDF/U0400.pdf)|	|Cyrl.			|`0438`и|`cyrl.i`西里尔“i”小写|
[`0500~052F`](https://www.unicode.org/charts/PDF/U0500.pdf)|	|CyrlSup.		|`052F`ԯ|`cyrl~`	|
[`0530~058F`](https://www.unicode.org/charts/PDF/U0530.pdf)|	|Armn.			|`053E`Ծ|`armn.Ca`	|
[`0590~05FF`](https://www.unicode.org/charts/PDF/U0590.pdf)|⬅|Hebr.			|`05D0`א|`hebr~`希伯来“alef”|
[`0600~06FF`](https://www.unicode.org/charts/PDF/U0600.pdf)|⬅|Arab.			|`06A1`ڡ|`arab~`	|和`08BB`ࢻ字形重复，待替
[`0700~074F`](https://www.unicode.org/charts/PDF/U0700.pdf)|⬅|Syrc.			|`072B`ܫ|`syrc~`叙利亚“shin”|著名：颜文字“兽嘴”
[`0750~077F`](https://www.unicode.org/charts/PDF/U0750.pdf)|⬅|ArabSup.		|`-`|`~`	|待替
[`0780~07BF`](https://www.unicode.org/charts/PDF/U0780.pdf)|⬅|Thaa.			|`0793`ޓ|`thaa~`	|著名：颜文字，字形待重绘
[`07C0~07FF`](https://www.unicode.org/charts/PDF/U07C0.pdf)|⬅|Nkoo.			|`07D2`ߒ|`nko.n`恩科“n”|
[`0800~083F`](https://www.unicode.org/charts/PDF/U0800.pdf)|⬅|Samr.			|`0800`ࠀ|`samr~`	|
[`0840~085F`](https://www.unicode.org/charts/PDF/U0840.pdf)|⬅|Mand.			|`0848`ࡈ|`mand.att`曼德恩“att”|
[`0860~086F`](https://www.unicode.org/charts/PDF/U0860.pdf)|⬅|SyrcSup.		|`0860`ࡠ|`syrc~`	|
[`0870~089F`](https://www.unicode.org/charts/PDF/U0870.pdf)|⬅|ArabExtB.		|`088B`ࢋ|`arab~`阿拉伯“tah”下点|字形自制（见B站动态）
[`08A0~08FF`](https://www.unicode.org/charts/PDF/U08A0.pdf)|⬅|ArabExtA.		|`-`|`~`	|待替
[`0900~097F`](https://www.unicode.org/charts/PDF/U0900.pdf)|	|Deva.			|`0915`क|`deva.ka`天城体“ka”|
[`0980~09FF`](https://www.unicode.org/charts/PDF/U0980.pdf)|	|Beng.			|`0995`ক|`beng.ka`孟加拉“ka”|
[`0A00~0A7F`](https://www.unicode.org/charts/PDF/U0A00.pdf)|	|Guru.			|`0A73`ੳ|`guru.ura`	|著名：颜文字
[`0A80~0AFF`](https://www.unicode.org/charts/PDF/U0A80.pdf)|	|Gujr.			|`0A85`અ|`gujr.a`	|
[`0B00~0B7F`](https://www.unicode.org/charts/PDF/U0B00.pdf)|	|Orya.			|`0B18`ଘ|`orya.gha`奥里亚“gha”|著名：颜文字“翅膀”
[`0B80~0BFF`](https://www.unicode.org/charts/PDF/U0B80.pdf)|	|Taml.			|`0BE7`௧|`taml.1`泰米尔“1”|
[`0C00~0C7F`](https://www.unicode.org/charts/PDF/U0C00.pdf)|	|Telu.			|`0C6A`౪|`telu.4`泰卢固“4”|著名：颜文字“口型”
[`0C80~0CFF`](https://www.unicode.org/charts/PDF/U0C80.pdf)|	|Knda.			|`0CA0`ಠ|`knda~`卡纳达“ttha”|著名：颜文字
[`0D00~0D7F`](https://www.unicode.org/charts/PDF/U0D00.pdf)|	|Mlym.			|`0D15`ക|`mlym.ka`	|
[`0D80~0DFF`](https://www.unicode.org/charts/PDF/U0D80.pdf)|	|Sinh.			|`0D9A`ක|`sinh~`僧伽罗“ka”|例字或改名`sinh.ka`
[`0E00~0E7F`](https://www.unicode.org/charts/PDF/U0E00.pdf)|	|Thai.			|`0E05`ฅ|`thai~`	|著名：颜文字“猫爪”，[v8.15更新][v815]
[`0E80~0EFF`](https://www.unicode.org/charts/PDF/U0E80.pdf)|	|Laoo.			|`0EA5`ລ|`lao~`	|
[`0F00~0FFF`](https://www.unicode.org/charts/PDF/U0F00.pdf)|	|Tibt.			|`0F40`ཀ|`tibt.ka`藏文“ka”|著名：颜文字“吐血”
[`1000~109F`](https://www.unicode.org/charts/PDF/U1000.pdf)|	|Mymr.			|`1000`က|`mymr.ka`缅文“ka”|
[`10A0~10FF`](https://www.unicode.org/charts/PDF/U10A0.pdf)|	|Geor.			|`10DA`ლ|`geor~`	|著名：颜文字“抬手”
[`1100~11FF`](https://www.unicode.org/charts/PDF/U1100.pdf)|	|Jamo.			|`1112`ᄒ|`hang~`	|
[`1200~137F`](https://www.unicode.org/charts/PDF/U1200.pdf)|	|Ethi.			|`129B`ኛ|`ethi~`埃塞“nyaa”|待替
[`1380~139F`](https://www.unicode.org/charts/PDF/U1380.pdf)|	|EthiSup.		|`138F`ᎏ|`ethi.pwe`埃塞“pwe”|待替
[`13A0~13FF`](https://www.unicode.org/charts/PDF/U13A0.pdf)|	|Cher.			|`13F1`Ᏹ|`cher.Yi`切罗基“yi”|[切罗基文创制者塞阔雅“ᏍᏏᏆ**Ᏹ**”][Cher]
[`1400~167F`](https://www.unicode.org/charts/PDF/U1400.pdf)|	|Cans.			|`141B`ᐛ|`cans~`	|著名：颜文字
[`1680~169F`](https://www.unicode.org/charts/PDF/U1680.pdf)|	|Ogam.			|`1698`ᚘ|`ogam~`欧甘“ifin”|
[`16A0~16FF`](https://www.unicode.org/charts/PDF/U16A0.pdf)|	|Runr.			|`16D2`ᛒ|`runr~`	|
[`1700~171F`](https://www.unicode.org/charts/PDF/U1700.pdf)|	|Tglg.			|`1703`ᜃ|`tglg.ka`他加禄“ka”|
[`1720~173F`](https://www.unicode.org/charts/PDF/U1720.pdf)|	|Hano.			|`1727`ᜧ|`hano.da`	|
[`1740~175F`](https://www.unicode.org/charts/PDF/U1740.pdf)|	|Buhd.			|`1740`ᝀ|`buhd.a`布希德“a”|
[`1760~177F`](https://www.unicode.org/charts/PDF/U1760.pdf)|	|Tagb.			|`1770`ᝰ|`tagb.sa`	|著名：颜文字
[`1780~17FF`](https://www.unicode.org/charts/PDF/U1780.pdf)|	|Khmr.			|`17E7`៧|`khmr.7`高棉“7”|
[`1800~18AF`](https://www.unicode.org/charts/PDF/U1800.pdf)|⤵|Mong.			|`1824`ᠤ|`mong.u`蒙文“u”|
[`18B0~18FF`](https://www.unicode.org/charts/PDF/U18B0.pdf)|	|CansExt.		|`18B2`ᢲ|`cans.aay`	|不著名颜文字
[`1900~194F`](https://www.unicode.org/charts/PDF/U1900.pdf)|	|Limb.			|`190F`ᤏ|`limb~`林布“na”|例字或改名`limb.na`，待替
[`1950~197F`](https://www.unicode.org/charts/PDF/U1950.pdf)|	|Tale.			|`196C`ᥬ|`tale.aue`傣㐻“aue”|不太著名颜文字“左肩”
[`1980~19DF`](https://www.unicode.org/charts/PDF/U1980.pdf)|	|Talu.			|`1982`ᦂ|`talu~`新傣仂“高ka”|待替
[`19E0~19FF`](https://www.unicode.org/charts/PDF/U19E0.pdf)|	|KhmrSym.		|`19E7`᧧|`khmr~`	|
[`1A00~1A1F`](https://www.unicode.org/charts/PDF/U1A00.pdf)|	|Bugi.			|`1A01`ᨁ|`bugi.ga`布吉“ga”|
[`1A20~1AAF`](https://www.unicode.org/charts/PDF/U1A20.pdf)|	|Lana.			|`1A43`ᩃ|`lana.la`傣昙“la”|
[`1AB0~1AFF`](https://www.unicode.org/charts/PDF/U1AB0.pdf)|◌|DiacExt.		|`1AB6`◌᪶|`comb~`	|魏安当作下划波浪线
[`1B00~1B7F`](https://www.unicode.org/charts/PDF/U1B00.pdf)|	|Bali.			|`1B44`◌᭄|`bali~`	|著名：颜文字“右臂”，例字多了◌
[`1B80~1BBF`](https://www.unicode.org/charts/PDF/U1B80.pdf)|	|Sund.			|`1B8D`ᮍ|`sund.nga`巽他“nga”|
[`1BC0~1BFF`](https://www.unicode.org/charts/PDF/U1BC0.pdf)|	|Batk.			|`1BC5`ᯅ|`batk.ba`巴塔克“ba”|著名：颜文字“口型”
[`1C00~1C4F`](https://www.unicode.org/charts/PDF/U1C00.pdf)|	|Lepc.			|`1C29`◌ᰩ|`lepc~`	|著名：颜文字“左肩”，例字多了◌
[`1C50~1C7F`](https://www.unicode.org/charts/PDF/U1C50.pdf)|	|Olck.			|`1C5A`ᱚ|`olck.la`	|
[`1C80~1C8F`](https://www.unicode.org/charts/PDF/U1C80.pdf)|	|CyrlExtC.		|`1C81`ᲁ|`cyrl~`	|
[`1C90~1CBF`](https://www.unicode.org/charts/PDF/U1C90.pdf)|	|GeorExt.		|`1CA6`Ღ|`geor~`	|不著名颜文字“比心”
[`1CC0~1CCF`](https://www.unicode.org/charts/PDF/U1CC0.pdf)|	|SundSup.		|`1CC5`᳅|`sund~`	|
[`1CD0~1CFF`](https://www.unicode.org/charts/PDF/U1CD0.pdf)|	|VedicExt.		|`1CE9`ᳩ|`u~`	|
[`1D00~1D7F`](https://www.unicode.org/charts/PDF/U1D00.pdf)|	|PhonExt.		|`1D5C`ᵜ|`phon~`	|著名：颜文字“兽嘴”
[`1D80~1DBF`](https://www.unicode.org/charts/PDF/U1D80.pdf)|	|PhonExtSup.		|`1D87`ᶇ|`phon~`	|待替
[`1DC0~1DFF`](https://www.unicode.org/charts/PDF/U1DC0.pdf)|◌|DiacSup.		|`1DC1`◌᷁|`comb~`	|
[`1E00~1EFF`](https://www.unicode.org/charts/PDF/U1E00.pdf)|	|LatnExtAdd.		|`1E69`ṩ|`latn~`	|
[`1F00~1FFF`](https://www.unicode.org/charts/PDF/U1F00.pdf)|	|GrekExt.		|`1F10`ἐ|`grek~`	|
[`2000~206F`](https://www.unicode.org/charts/PDF/U2000.pdf)|	|Punc.			|`2019`’|`punc~`右单弯引号|
[`2070~209F`](https://www.unicode.org/charts/PDF/U2070.pdf)|	|SupSub.		|`2077`⁷|`sups7`上标“7”|
[`20A0~20CF`](https://www.unicode.org/charts/PDF/U20A0.pdf)|	|Currency.		|`20AC`€|`euro`欧元|
[`20D0~20FF`](https://www.unicode.org/charts/PDF/U20D0.pdf)|◌|DiacSym.		|`20E3`◌⃣|`comb~`按键外框|
[`2100~214F`](https://www.unicode.org/charts/PDF/U2100.pdf)|	|Lttrlike.		|`2113`ℓ|`u~`	|
[`2150~218F`](https://www.unicode.org/charts/PDF/U2150.pdf)|	|NumForm.		|`215F`⅟|`onef`	|
[`2190~21FF`](https://www.unicode.org/charts/PDF/U2190.pdf)|	|Arow.			|`2197`↗|`arow~`	|
[`2200~22FF`](https://www.unicode.org/charts/PDF/U2200.pdf)|	|MathOpor.		|`22EF`⋯|`math~`	|
[`2300~23FF`](https://www.unicode.org/charts/PDF/U2300.pdf)|	|MiscTech.		|`23E9`⏩|`u~`快进标志|
[`2400~243F`](https://www.unicode.org/charts/PDF/U2400.pdf)|	|CtrlPict.		|`2421`␡|`pic~`	|
[`2440~245F`](https://www.unicode.org/charts/PDF/U2440.pdf)|	|OCR.			|`2447`⑇|`pic~`	|
[`2460~24FF`](https://www.unicode.org/charts/PDF/U2460.pdf)|	|EncAaNum.		|`2460`①|`u~`带圈1|
[`2500~257F`](https://www.unicode.org/charts/PDF/U2500.pdf)|	|BoxDraw.		|`251E`┞|`u~`	|
[`2580~259F`](https://www.unicode.org/charts/PDF/U2580.pdf)|	|Blocks.		|`259C`▜|`u~`	|
[`25A0~25FF`](https://www.unicode.org/charts/PDF/U25A0.pdf)|	|GeoShape.		|`25CC`◌|`u~`虚线圈|例字就是“◌”
[`2600~26FF`](https://www.unicode.org/charts/PDF/U2600.pdf)|	|MiscSym.		|`2618`☘|`shamrock`三叶草|
[`2700~27BF`](https://www.unicode.org/charts/PDF/U2700.pdf)|	|Ding.			|`2764`❤|`HBheart`实心大心形|
[`27C0~27EF`](https://www.unicode.org/charts/PDF/U27C0.pdf)|	|MiscMathA.		|`27E8`⟨|`math~`	|和〈类似，待替
[`27F0~27FF`](https://www.unicode.org/charts/PDF/U27F0.pdf)|	|SupArowA.		|`27F3`⟳|`arow~`	|
[`2800~28FF`](https://www.unicode.org/charts/PDF/U2800.pdf)|	|Brai.			|`285D`⡝|`brai~`	|
[`2900~297F`](https://www.unicode.org/charts/PDF/U2900.pdf)|	|SupArowB.		|`296F`⥯|`arow~`	|
[`2980~29FF`](https://www.unicode.org/charts/PDF/U2980.pdf)|	|MiscMathB.		|`299C`⦜|`math~`	|
[`2A00~2AFF`](https://www.unicode.org/charts/PDF/U2A00.pdf)|	|SupMathOpor.		|`2A16`⨖|`math~`	|
[`2B00~2BFF`](https://www.unicode.org/charts/PDF/U2B00.pdf)|	|MiscArow.		|`2BEA`⯪|`WstarLhB`左半实心星|
[`2C00~2C5F`](https://www.unicode.org/charts/PDF/U2C00.pdf)|	|Glag.			|`2C33`ⰳ|`glag~`	|
[`2C60~2C7F`](https://www.unicode.org/charts/PDF/U2C60.pdf)|	|LatnExtC.		|`2C6F`Ɐ|`latnAturn`	|和ᗄ∀类似，待替
[`2C80~2CFF`](https://www.unicode.org/charts/PDF/U2C80.pdf)|	|Copt.			|`2C81`ⲁ|`copt~`科普特“alfa”|
[`2D00~2D2F`](https://www.unicode.org/charts/PDF/U2D00.pdf)|	|GeorSup.		|`2D03`ⴃ|`geor~`	|待替
[`2D30~2D7F`](https://www.unicode.org/charts/PDF/U2D30.pdf)|	|Tfng.			|`2D34`ⴴ|`tfng~`提非纳“yaghh”|待替
[`2D80~2DDF`](https://www.unicode.org/charts/PDF/U2D80.pdf)|	|EthiExt.		|`2DA8`ⶨ|`ethi.cca`埃塞“cca”|待替
[`2DE0~2DFF`](https://www.unicode.org/charts/PDF/U2DE0.pdf)|◌|CyrlExtA.		|`2DE3`◌ⷣ|`cyrl~`	|
[`2E00~2E7F`](https://www.unicode.org/charts/PDF/U2E00.pdf)|	|SupPunc.		|`2E2E`⸮|`punc~`	|和阿拉伯`061F`؟类似，待替
[`2E80~2EFF`](https://www.unicode.org/charts/PDF/U2E80.pdf)|	|HanRadSup.		|`2ECF`⻏|`hani~`部首｢邑｣|区分：[汉字｢阝｣仅居左的｢阜\|⻖｣][futu]
[`2F00~2FDF`](https://www.unicode.org/charts/PDF/U2F00.pdf)|	|Kgxi.			|`248E5`𤣥|`hani~`避讳｢玄｣|康熙字典特有❗｢⽞｣例字不在Kgxi.
[`2FF0~2FFF`](https://www.unicode.org/charts/PDF/U2FF0.pdf)|	|IDC.			|`2FF1`⿱|`u~`	|
[`3000~303F`](https://www.unicode.org/charts/PDF/U3000.pdf)|	|HanSym.		|`3001`、|`punc~`顿号|和丶︑﹑､类似，待替
[`3040~309F`](https://www.unicode.org/charts/PDF/U3040.pdf)|	|Hira.			|`3086`ゆ|`hira.yu`平假名“yu”|ゆり\ユリ的｢ゆ｣
[`30A0~30FF`](https://www.unicode.org/charts/PDF/U30A0.pdf)|	|Kana.			|`30B5`サ|`kana.sa`片假名“sa”|区分：汉字，待替
[`3100~312F`](https://www.unicode.org/charts/PDF/U3100.pdf)|	|Bopo.			|`3113`ㄓ|`bopo.zh`注音“zh”|区分：[婆罗米系⋯][futu] 著名：[｢注｣的注音][futu]
[`3130~318F`](https://www.unicode.org/charts/PDF/U3130.pdf)|	|ComJamo.		|`3189`ㆉ|`hang~`	|待替
[`3190~319F`](https://www.unicode.org/charts/PDF/U3190.pdf)|	|Kbn.			|`319D`㆝|`ideo~`	|
[`31A0~31BF`](https://www.unicode.org/charts/PDF/U31A0.pdf)|	|BopoExt.		|`31A1`ㆡ|`bopo.zi`注音“zi”|区分：[婆罗米系文字][futu]
[`31C0~31EF`](https://www.unicode.org/charts/PDF/U31C0.pdf)|	|HanStrokes.		|`31CA`㇊|`strokehzt`｢横折提｣|区分：[一笔画汉字][futu]
[`31F0~31FF`](https://www.unicode.org/charts/PDF/U31F0.pdf)|	|KanaExt.		|`31FD`ㇽ|`kana~`	|
[`3200~32FF`](https://www.unicode.org/charts/PDF/U3200.pdf)|	|EncHan.		|`32C0`㋀|`ideo~`电报用“1月”|
[`3300~33FF`](https://www.unicode.org/charts/PDF/U3300.pdf)|	|HanCom.		|`33A1`㎡|`m2`平方米(全角)|
[`3400~4DBF`](https://www.unicode.org/charts/PDF/U3400.pdf)|	|HanExtA.		|`3514`㔔|`hani~`译音字｢⿱加ᆼ｣|
[`4DC0~4DFF`](https://www.unicode.org/charts/PDF/U4DC0.pdf)|	|Yijing.		|`4DCC`䷌|`u~`[易經“同人”](https://ctext.org/book-of-changes/tong-ren/zhs "中國哲學書電子化計劃")|
[`4E00~9FFF`](https://www.unicode.org/charts/PDF/U4E00.pdf)|	|Han.			|`4E2D`中|`hani~`中文的｢中｣|
[`A000~A48F`](https://www.unicode.org/charts/PDF/UA000.pdf)|	|Yiii.			|`A320`ꌠ|`yi.su`凉山规范彝“人”|[凉山当地彝族自称“ꆈ**ꌠ**”][UcB2]
[`A490~A4CF`](https://www.unicode.org/charts/PDF/UA490.pdf)|	|YiRad.			|`A4AD`꒭|`yi~`彝文部首“hmo”|[据说泛彝语族自称为“ꆀ”][UcB2]
[`A4D0~A4FF`](https://www.unicode.org/charts/PDF/UA4D0.pdf)|	|Lisu.			|`A4ED`ꓭ|`lisu.gha`傈僳“gha”|
[`A500~A63F`](https://www.unicode.org/charts/PDF/UA500.pdf)|	|Vaii.			|`A522`ꔢ|`vai.nee`瓦伊“nee”|待替
[`A640~A69F`](https://www.unicode.org/charts/PDF/UA640.pdf)|	|CyrlExtB.		|`A663`ꙣ|`cyrl~`	|
[`A6A0~A6FF`](https://www.unicode.org/charts/PDF/UA6A0.pdf)|	|Bamu.			|`A6A3`ꚣ|`bamu.ku`巴默姆“ku”|
[`A700~A71F`](https://www.unicode.org/charts/PDF/UA700.pdf)|	|ModToneLttr.		|`A704`꜄|`u~`	|
[`A720~A7FF`](https://www.unicode.org/charts/PDF/UA720.pdf)|	|LatnExtD.		|`A730`ꜰ|`F.sc`	|待替
[`A800~A82F`](https://www.unicode.org/charts/PDF/UA800.pdf)|	|Sylo.			|`A808`ꠈ|`sylo.kho`	|
[`A830~A83F`](https://www.unicode.org/charts/PDF/UA830.pdf)|	|IndiNumForm.		|`A835`꠵|`u~`	|
[`A840~A87F`](https://www.unicode.org/charts/PDF/UA840.pdf)|⤵|Phag.			|`A84E`ꡎ|`phag.ba`八思巴“ba”|例字不是“ꡍ(八)”也不是“ꡌ(巴)”
[`A880~A8DF`](https://www.unicode.org/charts/PDF/UA880.pdf)|	|Saur.			|`A892`ꢒ|`saur.ka`	|
[`A8E0~A8FF`](https://www.unicode.org/charts/PDF/UA8E0.pdf)|◌|DevaExt.		|`A8EC`◌꣬|`deva~`	|例字多了◌
[`A900~A92F`](https://www.unicode.org/charts/PDF/UA900.pdf)|	|Kali.			|`A90A`ꤊ|`kali.ka`克耶利“ka”|
[`A930~A95F`](https://www.unicode.org/charts/PDF/UA930.pdf)|	|Rjng.			|`A932`ꤲ|`rjng.nga`雷姜“nga”|
[`A960~A97F`](https://www.unicode.org/charts/PDF/UA960.pdf)|	|JamoExtA.		|`A961`ꥡ|`hang~`	|
[`A980~A9DF`](https://www.unicode.org/charts/PDF/UA980.pdf)|	|Java.			|`A9C2`꧂|`java~`	|
[`A9E0~A9FF`](https://www.unicode.org/charts/PDF/UA9E0.pdf)|	|MymrExtB.		|`A9F3`꧳|`mymr~`	|
[`AA00~AA5F`](https://www.unicode.org/charts/PDF/UAA00.pdf)|	|Cham.			|`AA00`ꨀ|`cham.a`占文“a”|
[`AA60~AA7F`](https://www.unicode.org/charts/PDF/UAA60.pdf)|	|MymrExtA.		|`AA61`ꩡ|`mymr~`	|
[`AA80~AADF`](https://www.unicode.org/charts/PDF/UAA80.pdf)|	|Tavt.			|`AADB`ꫛ|`tavt~`	|著名：颜文字代“N”
[`AAE0~AAFF`](https://www.unicode.org/charts/PDF/UAAE0.pdf)|	|MteiExt.		|`AAE2`ꫢ|`mtei.cha`米代文“cha”|
[`AB00~AB2F`](https://www.unicode.org/charts/PDF/UAB00.pdf)|	|EthiExtA.		|`AB2E`ꬮ|`ethi.bbo`埃塞“bbo”|待替
[`AB30~AB6F`](https://www.unicode.org/charts/PDF/UAB30.pdf)|	|LatnExtE.		|`AB62`ꭢ|`latn~`	|
[`AB70~ABBF`](https://www.unicode.org/charts/PDF/UAB70.pdf)|	|CherSup.		|`AB9D`ꮝ|`cher.s`切罗基“s”小写|[切罗基文创制者塞阔雅“**Ꮝ**ᏏᏆᏱ”][Cher]
[`ABC0~ABFF`](https://www.unicode.org/charts/PDF/UABC0.pdf)|	|Mtei.			|`ABDE`ꯞ|`mtei~`	|
[`AC00~D7AF`](https://www.unicode.org/charts/PDF/UAC00.pdf)|	|Hang.			|`AC00`가|`hang~`	|
[`D7B0~D7FF`](https://www.unicode.org/charts/PDF/UD7B0.pdf)|	|JamoExtB.		|`D7BA`ힺ|`hang~`	|待替
[`D800~DB7F`](https://www.unicode.org/charts/PDF/UD800.pdf)|⬚|HighSrgs.		|❌|未设字形|[UTF-16代理编码对][futu]（“半”个字）
`DB80~DBFF`|⬚|HighPUSrgs.		|❌|未设字形|注：PDF 包含于 HighSrgs.
[`DC00~DFFF`](https://www.unicode.org/charts/PDF/UDC00.pdf)|⬚|LowSrgs.		|❌|未设字形|[UTF-16代理编码对][futu]（“半”个字）
[`E000~F8FF`](https://www.unicode.org/charts/PDF/UE000.pdf)|	|PUA.			|`F8FF`|`DISU`綿雲飴里标志|私用区，[放私货的地方][futu]
[`F900~FAFF`](https://www.unicode.org/charts/PDF/UF900.pdf)|	|HanComIdeo.		|`FA11`﨑|`hani~`汉字｢⿰山竒｣|兼容区段里的非兼容汉字
[`FB00~FB4F`](https://www.unicode.org/charts/PDF/UFB00.pdf)|	|AlbtPF.		|`FB01`ﬁ|`latn.fi`连字“fi”|
[`FB50~FDFF`](https://www.unicode.org/charts/PDF/UFB50.pdf)|⬅|ArabPFA.		|`FDFC`﷼|`arab~`过时货币待替|例字曾用`FB6A`ﭪ 和`06A4`ڤ形重复
[`FE00~FE0F`](https://www.unicode.org/charts/PDF/UFE00.pdf)|⬚|VS.			|`FE06`｢︆｣|未设字形|前面｢｣号内的就是变体选择符№7
[`FE10~FE1F`](https://www.unicode.org/charts/PDF/UFE10.pdf)|	|Vert.			|`FE19`︙|`punc~`	|
[`FE20~FE2F`](https://www.unicode.org/charts/PDF/UFE20.pdf)|◌|Half.			|`FE22`◌︢|`comb~`	|
[`FE30~FE4F`](https://www.unicode.org/charts/PDF/UFE30.pdf)|	|HanComForm.		|`FE3B`︻|`punc~`	|例字误用名`punc3010`(【)
[`FE50~FE6F`](https://www.unicode.org/charts/PDF/UFE50.pdf)|	|SmlForm.		|`FE56`﹖|`punc~`小型“？”|
[`FE70~FEFF`](https://www.unicode.org/charts/PDF/UFE70.pdf)|⬅|ArabPFB.		|`FEC4`ﻄ|`arab~`	|例字曾用`..FED6`，待替
[`FF00~FFEF`](https://www.unicode.org/charts/PDF/UFF00.pdf)|	|HalfFull.		|`FF79`ｹ|`kana~`半角“ケ”|没半角平假名
[`FFF0~FFFF`](https://www.unicode.org/charts/PDF/UFFF0.pdf)|⬚|Spec.			|`FFFD`�|`u~`替换字符|
[`10000~1007F`](https://www.unicode.org/charts/PDF/U10000.pdf)|	|Linb.			|`10000`𐀀|`linb~`	|
[`10080~100FF`](https://www.unicode.org/charts/PDF/U10080.pdf)|	|LinbIdeo.		|`10082`𐂂|`linb.deer`	|
[`10100~1013F`](https://www.unicode.org/charts/PDF/U10100.pdf)|	|AegeanNum.		|`10137`𐄷|`u~`	|
[`10140~1018F`](https://www.unicode.org/charts/PDF/U10140.pdf)|	|AncGrekNum.		|`10167`𐅧|`grek~`	|
[`10190~101CF`](https://www.unicode.org/charts/PDF/U10190.pdf)|	|AncSym.		|`1019C`𐆜|`u~`	|
[`101D0~101FF`](https://www.unicode.org/charts/PDF/U101D0.pdf)|	|Phaistos.		|`101F6`𐇶|`u~`	|待替
[`10200~1023F`](https://www.unicode.org/charts/PDF/U10200.pdf)|⚠|🚧			|`-`|`~`	|(Northern Palaeohispanic)
[`10240~1027F`](https://www.unicode.org/charts/PDF/U10240.pdf)|⚠|🚧			|`-`|`~`	|(Southern Palaeohispanic)
[`10280~1029F`](https://www.unicode.org/charts/PDF/U10280.pdf)|	|Lyci.			|`10280`𐊀|`lyci.a`吕基亚“a”|
[`102A0~102DF`](https://www.unicode.org/charts/PDF/U102A0.pdf)|	|Cari.			|`102C6`𐋆|`cari.c39`	|
[`102E0~102FF`](https://www.unicode.org/charts/PDF/U102E0.pdf)|	|CoptNum.		|`102E6`𐋦|`copt.e6`	|
[`10300~1032F`](https://www.unicode.org/charts/PDF/U10300.pdf)|	|Ital.			|`10300`𐌀|`ital.a`	|
[`10330~1034F`](https://www.unicode.org/charts/PDF/U10330.pdf)|	|Goth.			|`1033E`𐌾|`goth.jer`哥特“jer”|
[`10350~1037F`](https://www.unicode.org/charts/PDF/U10350.pdf)|	|Perm.			|`10350`𐍐|`perm.an`	|
[`10380~1039F`](https://www.unicode.org/charts/PDF/U10380.pdf)|	|Ugar.			|`1039C`𐎜|`ugar.u`	|
[`103A0~103DF`](https://www.unicode.org/charts/PDF/U103A0.pdf)|	|Xpeo.			|`103A0`𐎠|`xpeo~`|例字曾用名`xpeo.signa`
[`103E0~103FF`](https://www.unicode.org/charts/PDF/U103E0.pdf)|⚠|ShawQS.		|`-`|`~`	|
[`10400~1044F`](https://www.unicode.org/charts/PDF/U10400.pdf)|	|Dsrt.			|`10414`𐐔|`dsrt.Dee`	|德撒律“Dee”大写
[`10450~1047F`](https://www.unicode.org/charts/PDF/U10450.pdf)|	|Shaw.			|`10457`𐑗|`shaw~`萧伯纳“church”|
[`10480~104AF`](https://www.unicode.org/charts/PDF/U10480.pdf)|	|Osma.			|`1048E`𐒎|`osma.qaaf`	|
[`104B0~104FF`](https://www.unicode.org/charts/PDF/U104B0.pdf)|	|Osge.			|`104CA`𐓊|`osge.Tsa`奥色治“Tsa”|
[`10500~1052F`](https://www.unicode.org/charts/PDF/U10500.pdf)|	|Elba.			|`10500`𐔀|`elba.a`	|
[`10530~1056F`](https://www.unicode.org/charts/PDF/U10530.pdf)|	|Aghb.			|`10530`𐔰|`aghb.alt`	|
[`10570~105BF`](https://www.unicode.org/charts/PDF/U10570.pdf)|	|Vith.			|`10570`𐕰|`vith.A`	|例字曾用名`vith10570`（见B动态）
[`105C0~105FF`](https://www.unicode.org/charts/PDF/U105C0.pdf)|⚠|Todr.			|`105E2`𐗢|`todr.ta`托兹里“ta”|
[`10600~1077F`](https://www.unicode.org/charts/PDF/U10600.pdf)|	|Lina.			|`10610`𐘐|`lina~`	|
[`10780~107BF`](https://www.unicode.org/charts/PDF/U10780.pdf)|	|LatnExtF.		|`10780`𐞀|`latn~`	|修饰字小型大写“AA”（见B动态）
[`10800~1083F`](https://www.unicode.org/charts/PDF/U10800.pdf)|⬅|Cprt.			|`10801`𐠁|`cprt.e`	|
[`10840~1085F`](https://www.unicode.org/charts/PDF/U10840.pdf)|⬅|Armi.			|`10857`𐡗|`armi~`	|
[`10860~1087F`](https://www.unicode.org/charts/PDF/U10860.pdf)|⬅|Palm.			|`10878`𐡸|`palm~`	|待替
[`10880~108AF`](https://www.unicode.org/charts/PDF/U10880.pdf)|⬅|Nbat.			|`10880`𐢀|`nbat~`	|
[`108B0~108DF`](https://www.unicode.org/charts/PDF/U108B0.pdf)|⚠⬅|Psin.		|`-`|`~`	|
[`108E0~108FF`](https://www.unicode.org/charts/PDF/U108E0.pdf)|⬅|Hatr.			|`108E4`𐣤|`hatr.he`哈特拉“he”|
[`10900~1091F`](https://www.unicode.org/charts/PDF/U10900.pdf)|⬅|Phnx.			|`10900`𐤀|`phnx.alf`腓尼基“alf”|
[`10920~1093F`](https://www.unicode.org/charts/PDF/U10920.pdf)|⬅|Lydi.			|`10920`𐤠|`lydi.a`吕底亚“a”|
[`10940~1095F`](https://www.unicode.org/charts/PDF/U10940.pdf)|⚠⬅|Sidt.		|`10941`𐥁|`sidt.N2`塞德N2|[v8.15更新][v815]
[`10960~1097F`](https://www.unicode.org/charts/PDF/U10960.pdf)|⚠⬅|🚧			|`-`|`~`	|¿Numidian?
[`10980~1099F`](https://www.unicode.org/charts/PDF/U10980.pdf)|⬅|Mero.			|`1099D`𐦝|`mero.da`	|
[`109A0~109FF`](https://www.unicode.org/charts/PDF/U109A0.pdf)|⬅|Merc.			|`109A0`𐦠|`merc.a`	|
[`10A00~10A5F`](https://www.unicode.org/charts/PDF/U10A00.pdf)|⬅|Khar.			|`10A10`𐨐|`khar.ka`佉卢“ka”|
[`10A60~10A7F`](https://www.unicode.org/charts/PDF/U10A60.pdf)|⬅|Sarb.			|`10A71`𐩱|`sarb.alef`	|
[`10A80~10A9F`](https://www.unicode.org/charts/PDF/U10A80.pdf)|⬅|Narb.			|`10A91`𐪑|`narb.alef`	|
[`10AA0~10ABF`](https://www.unicode.org/charts/PDF/U10AA0.pdf)|⚠⬅|🚧			|`-`|`~`	|(Balti)
[`10AC0~10AFF`](https://www.unicode.org/charts/PDF/U10AC0.pdf)|⬅|Mani.			|`10AC2`𐫂|`mani~`摩尼“bheth”|
[`10B00~10B3F`](https://www.unicode.org/charts/PDF/U10B00.pdf)|⬅|Avst.			|`10B00`𐬀|`avst.a`	|
[`10B40~10B5F`](https://www.unicode.org/charts/PDF/U10B40.pdf)|⬅|Prti.			|`10B40`𐭀|`prti~`=“aleph.prti”|
[`10B60~10B7F`](https://www.unicode.org/charts/PDF/U10B60.pdf)|⬅|Phli.			|`10B60`𐭠|`phli~`=“aleph.phli”|
[`10B80~10BAF`](https://www.unicode.org/charts/PDF/U10B80.pdf)|⬅|Phlp.			|`10B80`𐮀|`phlp~`=“aleph.phlp”|
[`10BB0~10BDF`](https://www.unicode.org/charts/PDF/U10BB0.pdf)|⚠⬅|Phlv.		|`-`|`~`	|
[`10BE0~10BFF`](https://www.unicode.org/charts/PDF/U10BE0.pdf)|⚠⬅|🚧			|`-`|`~`	|(Baburi)
[`10C00~10C4F`](https://www.unicode.org/charts/PDF/U10C00.pdf)|⬅|Orkh.			|`10C22`𐰢|`orkh~`	|
[`10C80~10CFF`](https://www.unicode.org/charts/PDF/U10C80.pdf)|⬅|Hung.			|`10CC3`𐳃|`hung.amb`	|
[`10D00~10D3F`](https://www.unicode.org/charts/PDF/U10D00.pdf)|⬅|Rohg.			|`10D09`𐴉|`rohg.fa`	|
[`10D40~10D8F`](https://www.unicode.org/charts/PDF/U10D40.pdf)|⚠⬅|Gara.			|`10D59`𐵙|`gara.Ga`	|加拉伊“Ga”大写
[`10D90~10E5F`](https://www.unicode.org/charts/PDF/U10D90.pdf)|⚠⬅|ArabExtD.		|`-`|`~`	|
[`10E60~10E7F`](https://www.unicode.org/charts/PDF/U10E60.pdf)|⬅|Rumi.			|`10E70`𐹰|`u~`	|
[`10E80~10EBF`](https://www.unicode.org/charts/PDF/U10E80.pdf)|⬅|Yezi.			|`10EA8`𐺨|`yezi.yot`耶西迪“yot”|
[`10EC0~10EFF`](https://www.unicode.org/charts/PDF/U10EC0.pdf)|⬅◌|ArabExtC.		|`10EFD`◌𐻽|`arab~`	|
[`10F00~10F2F`](https://www.unicode.org/charts/PDF/U10F00.pdf)|⬅|Sogo.			|`10F27`𐼧|`sogo~`	|待替
[`10F30~10F6F`](https://www.unicode.org/charts/PDF/U10F30.pdf)|⬅|Sogd.			|`10F42`𐽂|`sogd.taw`粟特“taw”|
[`10F70~10FAF`](https://www.unicode.org/charts/PDF/U10F70.pdf)|⬅⤵|Ougr.			|`10F78`𐽸|`ougr~`回鹘“lamedh”|（见B站动态）
[`10FB0~10FDF`](https://www.unicode.org/charts/PDF/U10FB0.pdf)|⬅|Chrs.			|`10FBF`𐾿|`chrs~`	|
[`10FE0~10FFF`](https://www.unicode.org/charts/PDF/U10FE0.pdf)|⬅|Elym.			|`10FE0`𐿠|`elym~`以利买“aleph”|
[`11000~1107F`](https://www.unicode.org/charts/PDF/U11000.pdf)|	|Brah.			|`11006`𑀆|`brah.aa`婆罗米“aa”|
[`11080~110CF`](https://www.unicode.org/charts/PDF/U11080.pdf)|	|Kthi.			|`1108D`𑂍|`kthi.ka`开梯“ka”|
[`110D0~110FF`](https://www.unicode.org/charts/PDF/U110D0.pdf)|	|Sora.			|`110D0`𑃐|`sora.sah`	|
[`11100~1114F`](https://www.unicode.org/charts/PDF/U11100.pdf)|	|Cakm.			|`11111`𑄑|`cakm.ttaa`	|查克马“ttaa”，码位连号😏
[`11150~1117F`](https://www.unicode.org/charts/PDF/U11150.pdf)|	|Mahj.			|`1115D`𑅝|`mahj.nya`	|
[`11180~111DF`](https://www.unicode.org/charts/PDF/U11180.pdf)|	|Shrd.			|`11191`𑆑|`shrd.ka`沙勒德“ka”|
[`111E0~111FF`](https://www.unicode.org/charts/PDF/U111E0.pdf)|	|SinhArchNum.		|`111E1`𑇡|`sinh.arc1`	|
[`11200~1124F`](https://www.unicode.org/charts/PDF/U11200.pdf)|	|Khoj.			|`11208`𑈈|`khoj.ka`科杰基“ka”|
[`11250~1127F`](https://www.unicode.org/charts/PDF/U11250.pdf)|⚠|🚧			|`-`|`~`	|(Landa)
[`11280~112AF`](https://www.unicode.org/charts/PDF/U11280.pdf)|	|Mult.			|`11280`𑊀|`mult.a`木尔坦“a”|[v8.15更新][v815]
[`112B0~112FF`](https://www.unicode.org/charts/PDF/U112B0.pdf)|	|Sind.			|`112BB`𑊻|`sind.kha`	|
[`11300~1137F`](https://www.unicode.org/charts/PDF/U11300.pdf)|	|Gran.			|`11305`𑌅|`gran.a`格兰他“a”|
[`11380~113FF`](https://www.unicode.org/charts/PDF/U11380.pdf)|⚠|Tutg.			|`113BA`◌𑎺|`tutg~`	|例字多了◌，待替
[`11400~1147F`](https://www.unicode.org/charts/PDF/U11400.pdf)|	|Newa.			|`1140E`𑐎|`newa.ka`内瓦“ka”|
[`11480~114DF`](https://www.unicode.org/charts/PDF/U11480.pdf)|	|Tirh.			|`114AF`𑒯|`tirh.ha`	|区分：`tirh.ka`“𑒏”与`beng..`ক太像
[`114E0~114FF`](https://www.unicode.org/charts/PDF/U114E0.pdf)|⚠|Tani!			|`-`|`~`	|
[`11500~1157F`](https://www.unicode.org/charts/PDF/U11500.pdf)|⚠|Ranj.			|`-`|`~`	|
[`11580~115FF`](https://www.unicode.org/charts/PDF/U11580.pdf)|	|Sidd.			|`115D9`𑗙|`sidd~`	|待替
[`11600~1165F`](https://www.unicode.org/charts/PDF/U11600.pdf)|	|Modi.			|`1160E`𑘎|`modi.ka`莫迪“ka”|
[`11660~1167F`](https://www.unicode.org/charts/PDF/U11660.pdf)|⤵|MongSup.		|`11662`𑙢|`mong~`	|
[`11680~116CF`](https://www.unicode.org/charts/PDF/U11680.pdf)|	|Takr.			|`11680`𑚀|`takr.a`塔克里“a”|
[`116D0~116FF`](https://www.unicode.org/charts/PDF/U116D0.pdf)|⚠|MymrExtC.		|`116E3`𑛣|`mymr.pwo9`	|
[`11700~1174F`](https://www.unicode.org/charts/PDF/U11700.pdf)|	|Ahom.			|`11712`𑜒|`ahom.a`阿含“a”|
[`11750~117AF`](https://www.unicode.org/charts/PDF/U11750.pdf)|⚠|Zouu!			|`-`|`~`	|= Zou.
[`117B0~117FF`](https://www.unicode.org/charts/PDF/U117B0.pdf)|⚠|Pyuu!			|`-`|`~`	|= Pyu.
[`11800~1184F`](https://www.unicode.org/charts/PDF/U11800.pdf)|	|Dogr.			|`1180A`𑠊|`dogr.ka`道格拉“ka”|
[`11850~1188F`](https://www.unicode.org/charts/PDF/U11850.pdf)|⚠|🚧			|`-`|`~`	|(Sirmauri)
[`118A0~118FF`](https://www.unicode.org/charts/PDF/U118A0.pdf)|	|Wara.			|`118FF`𑣿|`wara.om`	|
[`11900~1195F`](https://www.unicode.org/charts/PDF/U11900.pdf)|	|Diak.			|`11900`𑤀|`diak.a`	|
[`11960~1199F`](https://www.unicode.org/charts/PDF/U11960.pdf)|⚠|🚧			|`-`|`~`	|(Vatteluttu)
[`119A0~119FF`](https://www.unicode.org/charts/PDF/U119A0.pdf)|	|Nand.			|`119C1`𑧁|`nand.na`	|
[`11A00~11A4F`](https://www.unicode.org/charts/PDF/U11A00.pdf)|	|Zanb.			|`11A26`𑨦|`zanb.dzha`	|
[`11A50~11AAF`](https://www.unicode.org/charts/PDF/U11A50.pdf)|	|Soyo.			|`11A5C`𑩜|`soyo.ka`索永布“ka”|
[`11AB0~11ABF`](https://www.unicode.org/charts/PDF/U11AB0.pdf)|	|CansExtA.		|`11AB3`𑪳|`cans~`	|（见B站动态）
[`11AC0~11AFF`](https://www.unicode.org/charts/PDF/U11AC0.pdf)|	|Pauc.			|`11AC0`𑫀|`pauc.pa`包钦豪“pa”|
[`11B00~11B5F`](https://www.unicode.org/charts/PDF/U11B00.pdf)|	|DevaExtA.		|`11B07`𑬇|`deva~`	|
[`11B60~11B7F`](https://www.unicode.org/charts/PDF/U11B60.pdf)|⚠◌|ShrdSup.		|`11B67`◌𑭧|`shrd~`	|例字多了◌，[v8.15更新][v815]
[`11B80~11BBF`](https://www.unicode.org/charts/PDF/U11B80.pdf)|⚠|Leke.			|`-`|`~`	|
[`11BC0~11BFF`](https://www.unicode.org/charts/PDF/U11BC0.pdf)|⚠|Sunu.			|`11BE1`𑯡|`sunu.pvo`	|（苏努瓦尔，见B站专栏）
[`11C00~11C6F`](https://www.unicode.org/charts/PDF/U11C00.pdf)|	|Bhks.			|`11C0B`𑰋|`bhks.ai`	|
[`11C70~11CBF`](https://www.unicode.org/charts/PDF/U11C70.pdf)|	|Marc.			|`11C79`𑱹|`marc.nya`	|
[`11CC0~11CFF`](https://www.unicode.org/charts/PDF/U11CC0.pdf)|⚠|🚧			|`-`|`~`	|(Balti-B)
[`11D00~11D5F`](https://www.unicode.org/charts/PDF/U11D00.pdf)|	|Gonm.			|`11D24`𑴤|`gonm.ma`	|
[`11D60~11DAF`](https://www.unicode.org/charts/PDF/U11D60.pdf)|	|Gong.			|`11D76`𑵶|`gong.ga`	|
[`11DB0~11DEF`](https://www.unicode.org/charts/PDF/U11DB0.pdf)|⚠|Tols.			|`11DC1`𑷁|`tols.ttha`	|托隆西基“ttha”
[`11E00~11E6F`](https://www.unicode.org/charts/PDF/U11E00.pdf)|⚠|🚧			|`-`|`~`	|(Tocharian)
[`11E70~11ECF`](https://www.unicode.org/charts/PDF/U11E70.pdf)|⚠|Khotan!		|`10FF81`􏾁|`Khotanese`于阗[“a”](http://www.unicode.org/L2/L2015/15022-khotanese.pdf)|❗例字在PUAB.
[`11EE0~11EFF`](https://www.unicode.org/charts/PDF/U11EE0.pdf)|	|Maka.			|`11EE5`𑻥|`maka.ma`望加锡“ma”|
[`11F00~11F5F`](https://www.unicode.org/charts/PDF/U11F00.pdf)|	|Kawi.			|`11F4F`𑽏|`kawi~`	|和𑑛类似，待替
[`11F60~11FAF`](https://www.unicode.org/charts/PDF/U11F60.pdf)|⚠|🚧			|`-`|`~`	|(Pallava)
[`11FB0~11FBF`](https://www.unicode.org/charts/PDF/U11FB0.pdf)|	|LisuSup.		|`11FB0`𑾰|`lisu.yha`傈僳倒“ꓬ”|和⅄类似，不能替，只因此乃1字区段
[`11FC0~11FFF`](https://www.unicode.org/charts/PDF/U11FC0.pdf)|	|TamlSup.		|`11FD4`𑿔|`taml~`	|
[`12000~123FF`](https://www.unicode.org/charts/PDF/U12000.pdf)|	|Xsux.			|`12000`𒀀|`xsux.a`	|
[`12400~1247F`](https://www.unicode.org/charts/PDF/U12400.pdf)|	|XsuxNum.		|`1245D`𒑝|`xsux~`	|
[`12480~1254F`](https://www.unicode.org/charts/PDF/U12480.pdf)|	|EyDyXsux.		|`124F8`𒓸|`xsux~`	|待替
[`12580~12ECF`](https://www.unicode.org/charts/PDF/U12580.pdf)|⚠|Pcun.			|`-`|`~`	|
[`12F90~12FFF`](https://www.unicode.org/charts/PDF/U12F90.pdf)|	|Cpmn.			|`12FCC`𒿌|`cpmn~`	|（见B站动态）
[`13000~1342F`](https://www.unicode.org/charts/PDF/U13000.pdf)|	|Egyp.			|`13080`𓂀|`egyp.d010`	|
[`13430~1345F`](https://www.unicode.org/charts/PDF/U13430.pdf)|⬚|EgypFC.			|`1343E`｢𓐾｣|`u~`	|
[`13460~143FF`](https://www.unicode.org/charts/PDF/U13460.pdf)|⚠|EgypExtA.		|`13F19`𓼙|`egyp~`	|[v8.15更新][v815]
[`14400~1467F`](https://www.unicode.org/charts/PDF/U14400.pdf)|	|Hluw.			|`1440A`𔐊|`hluw~`	|
[`14680~151FF`](https://www.unicode.org/charts/PDF/U14680.pdf)|⚠|EgypExtB.		|`-`|`~`	|
[`15500~15AFF`](https://www.unicode.org/charts/PDF/U15500.pdf)|⚠|Maya.			|`-`|`~`	|
[`15B80~15FFF`](https://www.unicode.org/charts/PDF/U15B80.pdf)|⚠|🚧			|`-`|`~`	|(Mandombe)
[`16000~1607F`](https://www.unicode.org/charts/PDF/U16000.pdf)|⚠|Cirt.			|`1602E`𖀮|`Cirth`	|
[`16080~160FF`](https://www.unicode.org/charts/PDF/U16080.pdf)|⚠|Teng.			|`16085`𖂅|`Tengwar`	|
[`16100~1613F`](https://www.unicode.org/charts/PDF/U16100.pdf)|⚠|Gukh.			|`16102`𖄂|`gukh.kha`	|古隆凯玛“kha”
[`16140~1618F`](https://www.unicode.org/charts/PDF/U16140.pdf)|⚠|🚧			|`-`|`~`	|(Kurux Banna)
[`161A0~161FF`](https://www.unicode.org/charts/PDF/U161A0.pdf)|⚠|Moon.			|`161A7`𖆧|`moon.H`穆恩盲文“H”|
[`16200~1677F`](https://www.unicode.org/charts/PDF/U16200.pdf)|⚠|Blis.			|`-`|`~`	|
[`16800~16A3F`](https://www.unicode.org/charts/PDF/U16800.pdf)|	|BamuSup.		|`16855`𖡕|`bamu~`	|
[`16A40~16A6F`](https://www.unicode.org/charts/PDF/U16A40.pdf)|	|Mroo.			|`16A53`𖩓|`mro.ro`姆鲁“ro”|[v8.15更新][v815]
[`16A70~16ACF`](https://www.unicode.org/charts/PDF/U16A70.pdf)|	|Tnsa.			|`16AB9`𖪹|`tnsa.tha`通萨“tha”|例字曾用名`tnsa16AB9`（见B动态）
[`16AD0~16AFF`](https://www.unicode.org/charts/PDF/U16AD0.pdf)|	|Bass.			|`16AE1`𖫡|`bass.to`	|
[`16B00~16B8F`](https://www.unicode.org/charts/PDF/U16B00.pdf)|	|Hmng.			|`16B45`𖭅|`hmng~`	|
[`16B90~16BFF`](https://www.unicode.org/charts/PDF/U16B90.pdf)|⚠|Wole.			|`-`|`~`	|
[`16C00~16C7F`](https://www.unicode.org/charts/PDF/U16C00.pdf)|⚠|Kpel.			|`-`|`~`	|
[`16C80~16CCF`](https://www.unicode.org/charts/PDF/U16C80.pdf)|⚠|Afak.			|`-`|`~`	|
[`16CD0~16CFF`](https://www.unicode.org/charts/PDF/U16CD0.pdf)|⚠|TnsaK!			|`-`|`~`	|
[`16D00~16D3F`](https://www.unicode.org/charts/PDF/U16D00.pdf)|⚠|🚧			|`-`|`~`	|(Tikamuli)
[`16D40~16D7F`](https://www.unicode.org/charts/PDF/U16D40.pdf)|⚠|Krai.			|`16D44`𖵄|`krai.ka`基勒特赖“ka”|
[`16D80~16DAF`](https://www.unicode.org/charts/PDF/U16D80.pdf)|⚠|Chis.			|`16D87`𖶇|`chis.sa`奇索伊“sa”|[v8.15更新][v815]
[`16DD0~16DFF`](https://www.unicode.org/charts/PDF/U16DD0.pdf)|⚠|🚧			|`-`|`~`	|(Kulitan)
[`16E00~16E3F`](https://www.unicode.org/charts/PDF/U16E00.pdf)|⚠|🚧			|`-`|`~`	|(Mwangwego)
[`16E40~16E9F`](https://www.unicode.org/charts/PDF/U16E40.pdf)|	|Medf.			|`16E5A`𖹚|`medf.Oe`	|
[`16EA0~16EDF`](https://www.unicode.org/charts/PDF/U16EA0.pdf)|⚠|🚧			|`16EBE`𖺾|`~`𖺡𖺾𖻍𖻂(Beri)的“e”|[**(Beria Erfe)**](https://www.unicode.org/L2/L2024/24004r-zaghawa-proposal.pdf)
[`16F00~16F9F`](https://www.unicode.org/charts/PDF/U16F00.pdf)|	|Plrd.			|`16F01`𖼁|`plrd.ba`老苗“ba”|Miao 也称 Pollard
[`16FA0~16FAF`](https://www.unicode.org/charts/PDF/U16FA0.pdf)|⚠|BopoExtA.		|`-`|`~`	|
[`16FB0~16FDF`](https://www.unicode.org/charts/PDF/U16FB0.pdf)|⚠|KbnExtA.		|`-`|`~`	|
[`16FE0~16FFF`](https://www.unicode.org/charts/PDF/U16FE0.pdf)|	|IdeoSym.		|`31CB`㇋|`strokehzzp`｢横折折撇｣|❗｢𖿠｣例字不在IdeoSym.，待替
[`17000~187FF`](https://www.unicode.org/charts/PDF/U17000.pdf)|	|Tang.			|`17F07`𗼇|`tang~`	|[西夏人的自称“番”][ktxx]
[`18800~18AFF`](https://www.unicode.org/charts/PDF/U18800.pdf)|	|TangComp.		|`1888C`𘢌|`tang~`	|[西夏偏旁类似“亻”][ktxx]
[`18B00~18CFF`](https://www.unicode.org/charts/PDF/U18B00.pdf)|	|Kits.			|`18BBE`𘮾|`kits~`	|[一个契丹小字黑体字形](https://t.bilibili.com/468124265307197745)
[`18D00~18D7F`](https://www.unicode.org/charts/PDF/U18D00.pdf)|	|TangSup.		|`18D00`𘴀|`tang~`	|[西夏补充第一个字][ktxx]
[`18D80~18DFF`](https://www.unicode.org/charts/PDF/U18D80.pdf)|⚠|TangCompSup.		|`10FF83`􏾃|`tang_817`西夏偏旁817|“𘔹”的右半❗例字在PUAB.
[`18E00~195FF`](https://www.unicode.org/charts/PDF/U18E00.pdf)|⚠|Kitl.			|`10FF8C`􏾌|`khita`契丹大字[“契丹”?][futu]|❗例字在PUAB.
[`19600~19B9F`](https://www.unicode.org/charts/PDF/U19600.pdf)|⚠|Jurc.			|`10FF8D`􏾍|`jurchen`女真文[“女”?](https://t.bilibili.com/500574143384114159)|❗例字在PUAB.
[`19E00~1A2FF`](https://www.unicode.org/charts/PDF/U19E00.pdf)|⚠|PaucSyll.		|`-`|`~`	|
[`1A300~1A75F`](https://www.unicode.org/charts/PDF/U1A300.pdf)|⚠|🚧			|`-`|`~`	|(Eskaya)
[`1A760~1A77F`](https://www.unicode.org/charts/PDF/U1A760.pdf)|⚠|RjngExt.		|`-`|`~`	|
[`1A780~1A7FF`](https://www.unicode.org/charts/PDF/U1A780.pdf)|⚠|🚧			|`-`|`~`	|¿Kaida?
[`1A800~1ACFF`](https://www.unicode.org/charts/PDF/U1A800.pdf)|⚠|Nkdb.			|`-`|`~`	|(Naxi Dongba)也称 Nakhi Tomba
[`1AD00~1AFCF`](https://www.unicode.org/charts/PDF/U1AD00.pdf)|⚠|Nkgb.			|`-`|`~`	|¿Naxi Geba?也称 Nakhi Geba
[`1AFD0~1AFEF`](https://www.unicode.org/charts/PDF/U1AFD0.pdf)|⚠|KanaExtC.		|`-`|`~`	|
[`1AFF0~1AFFF`](https://www.unicode.org/charts/PDF/U1AFF0.pdf)|	|KanaExtB.		|`1AFFB`𚿻|`kana~`	|片假名闽南鼻音阳平（见B动态）
[`1B000~1B0FF`](https://www.unicode.org/charts/PDF/U1B000.pdf)|	|KanaSup.		|`1B000`𛀀|`kana~`	|
[`1B100~1B12F`](https://www.unicode.org/charts/PDF/U1B100.pdf)|	|KanaExtA.		|`1B108`𛄈|`kana.wa1`	|
[`1B130~1B16F`](https://www.unicode.org/charts/PDF/U1B130.pdf)|	|SmlKanaExt.		|`1B165`𛅥|`kana~`	|
[`1B170~1B2FF`](https://www.unicode.org/charts/PDF/U1B170.pdf)|	|Nshu.			|`1B181`𛆁|`nshu~`女书“女”|
[`1B300~1B5FF`](https://www.unicode.org/charts/PDF/U1B300.pdf)|⚠|Shui.			|`1B384`𛎄|`shui~`水书“水”|
[`1B600~1B9FF`](https://www.unicode.org/charts/PDF/U1B600.pdf)|⚠|LisuSyll.		|`-`|`~`	|
[`1BA00~1BB8F`](https://www.unicode.org/charts/PDF/U1BA00.pdf)|⚠|Inds.			|`-`|`~`	|
[`1BC00~1BC9F`](https://www.unicode.org/charts/PDF/U1BC00.pdf)|	|Dupl.			|`1BC40`𛱀|`dupl.skr`杜普雷“s k r”|
[`1BCA0~1BCAF`](https://www.unicode.org/charts/PDF/U1BCA0.pdf)|⬚|ShFC.			|`1BCA1`｢𛲡｣|`u~`	|
[`1BCB0~1BCFF`](https://www.unicode.org/charts/PDF/U1BCB0.pdf)|⚠|PitmanSh.		|`-`|`~`	|
[`1BD00~1C37F`](https://www.unicode.org/charts/PDF/U1BD00.pdf)|⚠|Pelm.			|`-`|`~`	|
[`1C380~1C4FF`](https://www.unicode.org/charts/PDF/U1C380.pdf)|⚠|LinElm!		|`-`|`~`	|
[`1CA80~1CBFF`](https://www.unicode.org/charts/PDF/U1CA80.pdf)|⚠|Roro.			|`-`|`~`	|
[`1CC00~1CEBF`](https://www.unicode.org/charts/PDF/U1CC00.pdf)|⚠|SymfLCSup.		|`1CC72`𜱲|`sym~`右向贪吃蛇头|
[`1CEC0~1CEFF`](https://www.unicode.org/charts/PDF/U1CEC0.pdf)|⚠|MiscSymSup.		|`-`|`~`	|
[`1CF00~1CFCF`](https://www.unicode.org/charts/PDF/U1CF00.pdf)|	|ZnaMu.			|`1CF68`𜽨|`znamu~`	|（见B站动态）
[`1D000~1D0FF`](https://www.unicode.org/charts/PDF/U1D000.pdf)|	|ByzMu.			|`1D037`𝀷|`byzmu~`	|
[`1D100~1D1FF`](https://www.unicode.org/charts/PDF/U1D100.pdf)|	|Music.			|`1D122`𝄢|`mu~`	|
[`1D200~1D24F`](https://www.unicode.org/charts/PDF/U1D200.pdf)|	|AncGrekMu.		|`1D200`𝈀|`grek~`	|
[`1D250~1D26F`](https://www.unicode.org/charts/PDF/U1D250.pdf)|⚠|Flute.			|`-`|`~`	|
[`1D280~1D2AF`](https://www.unicode.org/charts/PDF/U1D280.pdf)|⚠|Pipa!			|`-`|`~`	|
[`1D2C0~1D2DF`](https://www.unicode.org/charts/PDF/U1D2C0.pdf)|	|KakkNum.		|`1D2D2`𝋒|`kakknum18`	|
[`1D2E0~1D2FF`](https://www.unicode.org/charts/PDF/U1D2E0.pdf)|	|MayaNum.		|`1D2E0`𝋠|`maya.0`玛雅数字“0”|比本尊先收录，只因已出现于货币上
[`1D300~1D35F`](https://www.unicode.org/charts/PDF/U1D300.pdf)|	|TXjing.		|`1D311`𝌑|`u~`[太玄经“童”](https://ctext.org/taixuanjing/tong/zhs "中國哲學書電子化計劃")|
[`1D360~1D37F`](https://www.unicode.org/charts/PDF/U1D360.pdf)|	|RodNum.		|`1D375`𝍵|`ideotally4`画正字“4”|（见B站动态）
[`1D380~1D3FF`](https://www.unicode.org/charts/PDF/U1D380.pdf)|⚠|MathAaNumSup.		|`-`|`~`	|
[`1D400~1D7FF`](https://www.unicode.org/charts/PDF/U1D400.pdf)|	|MathAaNum.		|`1D574`𝕴|`math~`	|和𝕵类似，待替
[`1D800~1DAAF`](https://www.unicode.org/charts/PDF/U1D800.pdf)|	|Sgnw.			|`1D81E`𝠞|`sgnw~`	|
[`1DAE0~1DAFF`](https://www.unicode.org/charts/PDF/U1DAE0.pdf)|⚠⬚|JanzFC!		|`-`|`~`	|
[`1DB00~1DC8F`](https://www.unicode.org/charts/PDF/U1DB00.pdf)|⚠|Janz!			|`10FFA5`􏾥|`Jianzi`减字谱｢⿱冂勹｣|“剔”[v8.15更新][v815]❗例字在PUAB.
[`1DF00~1DFFF`](https://www.unicode.org/charts/PDF/U1DF00.pdf)|	|LatnExtG.		|`1DF02`𝼂|`latn~`	|拉丁小型大写倒转“G”（见B动态）
[`1E000~1E02F`](https://www.unicode.org/charts/PDF/U1E000.pdf)|◌|GlagSup.		|`1E003`◌𞀃|`glag~`	|
[`1E030~1E08F`](https://www.unicode.org/charts/PDF/U1E030.pdf)|	|CyrlExtD.		|`1E034`𞀴|未设字形|字形复用“◌ⷣ”但不带◌
[`1E100~1E14F`](https://www.unicode.org/charts/PDF/U1E100.pdf)|	|Hmnp.			|`1E108`𞄈|`hmnp.ca`创世苗“ca”|
[`1E150~1E1FF`](https://www.unicode.org/charts/PDF/U1E150.pdf)|⚠|🚧			|`-`|`~`	|(Eebee Hmong)
[`1E200~1E26F`](https://www.unicode.org/charts/PDF/U1E200.pdf)|⚠|WestCham!		|`-`|`~`	|
[`1E290~1E2BF`](https://www.unicode.org/charts/PDF/U1E290.pdf)|	|Toto.			|`1E290`𞊐|`toto.pa`托托“pa”|例字曾用名`toto1E290`（见B动态）
[`1E2C0~1E2FF`](https://www.unicode.org/charts/PDF/U1E2C0.pdf)|	|Wcho.			|`1E2FF`𞋿|`wcho~`	|
[`1E300~1E41F`](https://www.unicode.org/charts/PDF/U1E300.pdf)|⚠|Loma.			|`-`|`~`	|
[`1E420~1E4CF`](https://www.unicode.org/charts/PDF/U1E420.pdf)|⚠|🚧			|`-`|`~`	|(Bagam)
[`1E4D0~1E4FF`](https://www.unicode.org/charts/PDF/U1E4D0.pdf)|	|Nagm.			|`1E4E7`𞓧|`nagm.em`	|
[`1E500~1E52F`](https://www.unicode.org/charts/PDF/U1E500.pdf)|⚠|🚧			|`-`|`~`	|(Pungchen)
[`1E530~1E55F`](https://www.unicode.org/charts/PDF/U1E530.pdf)|⚠|🚧			|`-`|`~`	|¿Pungchung?
[`1E560~1E59F`](https://www.unicode.org/charts/PDF/U1E560.pdf)|⚠|🚧			|`-`|`~`	|¿Marchung?
[`1E5A0~1E5CF`](https://www.unicode.org/charts/PDF/U1E5A0.pdf)|⚠|🚧			|`-`|`~`	|(Brusha)
[`1E5D0~1E5FF`](https://www.unicode.org/charts/PDF/U1E5D0.pdf)|⚠|Onao.			|`1E5D0`𞗐|`onao.o`	|
[`1E600~1E65F`](https://www.unicode.org/charts/PDF/U1E600.pdf)|⚠|🚧			|`-`|`~`	|¿Chola?
[`1E660~1E6BF`](https://www.unicode.org/charts/PDF/U1E660.pdf)|⚠|🚧			|`-`|`~`	|¿Chalukya (Box-Headed)?
[`1E6C0~1E6FF`](https://www.unicode.org/charts/PDF/U1E6C0.pdf)|⚠⤵|Tayo.			|`1E6CD`𞛍|`tayo~`傣侥“高to”|[v8.15更新][v815]
[`1E700~1E73F`](https://www.unicode.org/charts/PDF/U1E700.pdf)|⚠|🚧			|`-`|`~`	|(Lampung)
[`1E740~1E76F`](https://www.unicode.org/charts/PDF/U1E740.pdf)|⚠|🚧			|`-`|`~`	|(Kerinci)
[`1E770~1E7BF`](https://www.unicode.org/charts/PDF/U1E770.pdf)|⚠|BugiSup.		|`-`|`~`	|
[`1E7C0~1E7DF`](https://www.unicode.org/charts/PDF/U1E7C0.pdf)|⚠|🚧			|`-`|`~`	|¿Lontara bilang-bilang?
[`1E7E0~1E7FF`](https://www.unicode.org/charts/PDF/U1E7E0.pdf)|	|EthiExtB.		|`1E7E0`𞟠|`ethi.hhya`埃塞“hhya”|待替（见B站动态）
[`1E800~1E8DF`](https://www.unicode.org/charts/PDF/U1E800.pdf)|⬅|Mend.			|`1E801`𞠁|`mend.ka`	|
[`1E900~1E95F`](https://www.unicode.org/charts/PDF/U1E900.pdf)|⬅|Adlm.			|`1E900`𞤀|`adlm.Alif`	|
[`1EB90~1EBFF`](https://www.unicode.org/charts/PDF/U1EB90.pdf)|⚠⬅|🚧			|`-`|`~`	|¿Byblos?
[`1EC00~1EC6F`](https://www.unicode.org/charts/PDF/U1EC00.pdf)|⚠⬅|PersSiyaqNum!		|`-`|`~`	|≈ PsyqNum.
[`1EC70~1ECBF`](https://www.unicode.org/charts/PDF/U1EC70.pdf)|⬅|IndiSiyaqNum.		|`1EC87`𞲇|`indis.500`	|≈ IsyqNum.
[`1ECC0~1ECFF`](https://www.unicode.org/charts/PDF/U1ECC0.pdf)|⚠⬅|DwniSiyaqNum!		|`-`|`~`	|≈ DsyqNum.
[`1ED00~1ED4F`](https://www.unicode.org/charts/PDF/U1ED00.pdf)|⬅|OttoSiyaqNum.		|`1ED1B`𞴛|`otto.900`	|≈ OsyqNum.
[`1EE00~1EEFF`](https://www.unicode.org/charts/PDF/U1EE00.pdf)|⬅|ArabMath.		|`1EEB5`𞺵|`math~`	|待替
[`1EF00~1EF3F`](https://www.unicode.org/charts/PDF/U1EF00.pdf)|⚠⬅|ArabSupSym.		|`-`|`~`	|
[`1F000~1F02F`](https://www.unicode.org/charts/PDF/U1F000.pdf)|	|Majg.			|`1F004`🀄|`u~`	|
[`1F030~1F09F`](https://www.unicode.org/charts/PDF/U1F030.pdf)|	|Domino.		|`1F033`🀳|`u~`	|待替
[`1F0A0~1F0FF`](https://www.unicode.org/charts/PDF/U1F0A0.pdf)|	|PlayCard.		|`1F0A1`🂡|`u~`	|
[`1F100~1F1FF`](https://www.unicode.org/charts/PDF/U1F100.pdf)|	|EncAaNumSup.		|`1F10C`🄌|`u~`	|
[`1F200~1F2FF`](https://www.unicode.org/charts/PDF/U1F200.pdf)|	|EncIdeoSup.		|`1F264`🉤|`dblXi`圆形囍|[某动画截屏中有出现][pic]
[`1F300~1F5FF`](https://www.unicode.org/charts/PDF/U1F300.pdf)|	|MiscPic.		|`1F494`💔|`u~`心碎|
[`1F600~1F64F`](https://www.unicode.org/charts/PDF/U1F600.pdf)|	|Emos.			|`1F643`🙃|`u~`倒脸|
[`1F650~1F67F`](https://www.unicode.org/charts/PDF/U1F650.pdf)|	|OrnaDing.		|`1F658`🙘|`u~`	|
[`1F680~1F6FF`](https://www.unicode.org/charts/PDF/U1F680.pdf)|	|TransMap.		|`1F6D1`🛑|`u~`	|例字曾用名`sym.hani505C`（见专栏）
[`1F700~1F77F`](https://www.unicode.org/charts/PDF/U1F700.pdf)|	|Alch.			|`1F70D`🜍|`sulfur`炼金术硫符|例字曾用名`alch1F70D`（见动态）
[`1F780~1F7FF`](https://www.unicode.org/charts/PDF/U1F780.pdf)|	|GeoShapeExt.		|`1F7E5`🟥|`LRdSquare`大红方块|待替
[`1F800~1F8FF`](https://www.unicode.org/charts/PDF/U1F800.pdf)|	|SupArowC.		|`1F8A9`🢩|`u~`	|
[`1F900~1F9FF`](https://www.unicode.org/charts/PDF/U1F900.pdf)|	|SupSymPic.		|`1F914`🤔|`u~`托腮思索脸|例字曾用名`thinkingface`
[`1FA00~1FA6F`](https://www.unicode.org/charts/PDF/U1FA00.pdf)|	|ChessSym.		|`1FA6B`🩫|`u~`象棋黑车|
[`1FA70~1FAFF`](https://www.unicode.org/charts/PDF/U1FA70.pdf)|	|SymPicExtA.		|`1FA90`🪐|`u~`有环行星|
[`1FB00~1FBFF`](https://www.unicode.org/charts/PDF/U1FB00.pdf)|	|SymfLC.		|`1FBF5`🯵|`u~`段码字“5”|
[`1FC00~1FFFF`](https://www.unicode.org/charts/PDF/U1FC00.pdf)|⚠|ExtPictCharE!		|`-`|`~`	|= Zsye.
[`20000~2A6DF`](https://www.unicode.org/charts/PDF/U20000.pdf)|	|HanExtB.		|`29F7E`𩽾|`hani~`汉字｢⿰鱼安｣|著名：[鮟鱇鱼的｢鮟｣简化][hmos]
[`2A700~2B73F`](https://www.unicode.org/charts/PDF/U2A700.pdf)|	|HanExtC.		|`2B45B`𫑛|`hani~`汉字｢⿰戉⻏｣|著名：[戉王鳩淺劍的｢越｣][hmos]
[`2B740~2B81F`](https://www.unicode.org/charts/PDF/U2B740.pdf)|	|HanExtD.		|`2B7F7`𫟷|`hani~`汉字｢⿰钅立｣|著名：[116号化学元素“Lv”][hmos]
[`2B820~2CEAF`](https://www.unicode.org/charts/PDF/U2B820.pdf)|	|HanExtE.		|`2CC56`𬱖|`hani~`汉字｢⿰由页｣|著名：[人名用字｢頔｣简化][hmos]
[`2CEB0~2EBEF`](https://www.unicode.org/charts/PDF/U2CEB0.pdf)|	|HanExtF.		|`2E9F5`𮧵|`hani~`汉字｢⿰韦华｣|著名：[人名用字｢韡｣简化][hmos]
[`2EBF0~2EE5F`](https://www.unicode.org/charts/PDF/U2EBF0.pdf)|	|HanExtI.		|`2EDCC`𮷌|`hani~`汉字｢⿰贝亅｣|著名：[地名、姓氏“zhī”][gb22]
[`2F800~2FA1F`](https://www.unicode.org/charts/PDF/U2F800.pdf)|	|HanComIdeoSup.		|`2F817`冗|`hani~`兼容汉字|冗余的，待替
[`30000~3134F`](https://www.unicode.org/charts/PDF/U30000.pdf)|	|HanExtG.		|`30EDD`𰻝|`hani~`biáng々麺用字|著名：字形见[此文配图][hmos]
[`31350~323AF`](https://www.unicode.org/charts/PDF/U31350.pdf)|	|HanExtH.		|`3176B`𱝫|`hani~`工尺谱｢⿰彳上｣|不满意思源黑偏旁，重画
`35400~36BFF`|⚠|Orcl!			|`10FF7F`􏽿|`oracle`甲骨｢文｣|[後2.14.13合4834][futu]❗例字在PUAB.
[`38000~3AB9F`](https://www.unicode.org/charts/PDF/U38000.pdf)|⚠|Seal!			|`10FF80`􏾀|`seal`小篆｢㣇\彖｣|[缪篆字典 徐三庚][futu]❗例字在PUAB.
`A0000~A027B`|🛑|GB18030		|`10FF82`􏾂|`hania`简体的｢[𪀋](https://zi.tools/zi/𪀋 "字統网")｣|[02582](https://hc.jsecs.org/irg/ws2021/app/?id=02582 "02582｜⿹&P4-05;甲｜WS2021v6.0")\|[身份证🖻](https://github.com/MY1L/Unicode/assets/58043328/669faf5b-cad1-40b2-aa4c-4deeb823d9c5 "求个字，鸟甲怎么打？")❗例字在PUAB.
[`E0000~E007F`](https://www.unicode.org/charts/PDF/UE0000.pdf)|⬚|Tags.			|❌|未设字形|举例：此｢󠀁｣内的就是“语言标签”
[`E0100~E01EF`](https://www.unicode.org/charts/PDF/UE0100.pdf)|⬚|VsSup.			|`E013C`｢󠄼｣|未设字形|前面｢｣号内的就是变体选择符№77
[`F0000~FFFFF`](https://www.unicode.org/charts/PDF/UF0000.pdf)|	|PUAA.			|`E00F`|`UNi`统一码标志|私货区⋯❗例字不在PUAA.
[`100000~10FFFF`](https://www.unicode.org/charts/PDF/U100000.pdf)|	|PUAB.		|`10FFFD`􏿽|`HWJY`[胡万进印](https://t.bilibili.com/507643109798038510)|私用区，[放私货的地方][futu]

### 特殊
控制符往往在排版渲染中被忽略，即便字体有字形也不可见。上表的选择符、替代字也是。\
每平面末尾的[2个非字符下表从略][v815]，[我也加了字形使之可见](https://t.bilibili.com/808178636233375814)。
实际范围|样字名|举例及码|出典或备注
|-:|-|-|-|
  `0001~001F`|Latn_Ctrl.0000	|`0007`|给4个控制符加了字形
  `0080~009F`|Latn1_Ctrl.0080	|`0080`|皆控制符
  `2FE0~2FEF`|0BMP.rsvd		|`2FEC`⿬|
  `FDD0~FDEF`|nonArab		|`FDD0`﷐|皆非字符
`1xxx0~1xxxx`|1SMP.rsvd		|`1C888`𜢈|找个远期未预留的码位好难⋯
`2xxx0~2xxxx`|2SIP.rsvd		|`2FFFD`𯿽|
`3xxx0~3xxxx`|3TIP.rsvd		|`3FFFD`𿿽|
`40000~4FFFD`|4.rsvd		|`40000`񀀀|
`50000~5FFFD`|5.rsvd		|`50000`񐀀|
`60000~6FFFD`|6.rsvd		|`60000`񠀀|
`70000~7FFFD`|7.rsvd		|`70000`񰀀|
`80000~8FFFD`|8.rsvd		|`80000`򀀀|
`90000~9FFFD`|9.rsvd		|`90000`򐀀|
`A0000~AFFFD`|10.rsvd		|`AFFFD`򯿽|
`B0000~BFFFD`|11.rsvd		|`B0000`򰀀|
`C0000~CFFFD`|12.rsvd		|`C0000`󀀀|
`D0000~DFFFD`|13.rsvd		|`D0000`󐀀|
`Exxx0~Exxxx`|14SSP.rsvd	|`EFFFD`󯿽|

\
以下除 Powerline 外，尚有提案或 [CSUR](http://www.evertype.com/standards/csur/) 分配了大致范围，但统一码未预留区段。
> 私用区额外支持叶密豪维护的 CSUR 中有 [ISO 15924] 代码的2种文字：Visp.、Piqd. 和常见的 Powerline 符号“…”，其它没代码的忽略。

大致范围|⚠|样字名|例字及码|例字名|出典或备注
|-:|-|-|-|-|-|
  `E0?0~E0?3`|🩲|PUA.Powerline	|`E0A0`|`branch~`	|
  `??80~??FF`|🩲|PUA.Visp	|`E79C`|`visp~`	|
  `??D0~??FF`|🩲|PUA.Piqd	|`F8E4`|`piqd.tlh`	|
`?6140~?617F`|👻|🚧		|`-`	|`~`		|¿¿¿Khe Prih???

\
以下样字名以`.`结尾的不是省略。统一码未预留区段，字形全在私用区增乙。

[Yi]: https://github.com/MY1L/Unicode/discussions/6
样字及码|⚠|样字名|例字及码|例字名､义|出典或备注
|-:|-|-|-|-|-|
`10FF90`􏾐|👻|Bronze	|`10FFA0`􏾠|`bronze`金文｢鼎｣|[先獸鼎](https://t.bilibili.com/480890780719677279) [西周早期 集成2655][futu]
`10FF91`􏾑|👻|Yue	|`10FFA1`􏾡|`yue`鸟虫书｢𫑛｣|越王勾践剑铭
`10FF92`􏾒|👻|Chu	|`10FFA2`􏾢|`chu`战国文字｢楚｣|[楚简][futu]
`10FF93`􏾓|👻|Oracle	|`10FF7F`􏽿|`oracle`，同上上上表|样字不同于`Orcl.35400`
`10FF95`􏾕|⚠|Janz.	|`10FFA5`􏾥|`Jianzi`，同上上上表|样字不同于`Janz.1DB00`，[v8.15更新][v815]
`10FF9A`􏾚|👻|OldYi	|`10FFAA`􏾪|`oldYi`[彝文(滇南古体)“彝”][Yi]	|Yi, S.Yunnan?
`10FF9B`􏾛|👻|Ideo.Yi	|`10FFAB`􏾫|`ideoYi`[彝文(云南体)“彝”][Yi]	|Yi Ideographs
`10FF9C`􏾜|👻|UnifiedYi	|`10FFAC`􏾬|`unifiedYi`[彝文(通用体)“彝”][Yi]	|Yi, Unified
`10FF9D`􏾝|👻|Sara.	|`10FFAD`􏾭|`sara.s`萨拉提[“s”][next]|有 ISO 代码，但连 [UCSUR](https://www.kreativekorp.com/ucsur/) 都没分配
`10FF9E`􏾞|👻|Tuyuhun	|`10FFAE`􏾮|`tuyuhun`吐谷浑[“样本1”][next]|
`10FF9F`􏾟|🩲|PUAA.xdi8	|`10FFAF`􏾯|`xdi8.aho`｢⿰纟火｣|只因别人的造字难看⋯