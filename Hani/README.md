# Monu Han* 系列
「典迹汉字」，又一套负责泛汉字的显示、不太负责排版的工具字体，`Hani`是泛指汉字的[ISO 15924 四字代码](/abbr)。

包含思源黑体没有的 汉字`Hani`自制字形、表意描述字符`Zyyy`原创字形、算筹的画正字、注音`Bopo`扩充、更多假名`Hira` `Kana`，未收录古文字形，等等。

汉字`Han`定义以 [Scripts-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/Scripts.txt)、泛汉字符号`Hani`定义以 [ScriptExtensions-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/ScriptExtensions.txt) 为准。`Bopo` `Hira` `Kana`也是。

由于统一码收录汉字总量超出单字体可容字形量上限(65536)，又考虑到向后兼容，遂拆分为 Han2、Han3 等[负责对应的表意平面](/Blocks#平面)，可在[Releases](https://github.com/MY1L/Unicode/releases?q=MonuHani&expanded=true)搜索下载。

> 顺带一提，该字体系列原打算命名为 SourceHanSans<sub>XXX</sub>Plane（思源黑体<sub>某</sub>平面），其中 HanSans（汉字无衬线体）想简称4字的“Hans”，但和 <sup>ISO 15924</sup>`Hans`撞了，要改称“SrcHei<sub>XXX</sub>Plan”……但为了追加那些跟思源无关的字形，仍用我非完全原创字体“Monu「典迹」”开头。

当然不可能命名为“Gothic”的，因为是统一码已有文种（<sup>ISO 15924</sup>`Goth`，如“𐌰𐌱𐌲𐌳”）的名称。

## 规划
以下展示各个字体支持方向，和目前（截至统一码15.0版）完全覆盖的区段，选择这些区段的缘由见[FontList](/FontList)的分析。对照的是2.004版思源黑体，不过思源黑从2.002版起就没加过字。
### Hani「汉字」
用于覆盖BMP、SMP平面`Hani`字符。支持一些特殊的排版特性，且三个私用区均有若干备用字形。目前为3次曲线（.otf）版本。SMP平面已支持一些算筹、减字谱、假名。
- 2FF0..Ideographic Description Characters	；思源黑(12／12字) ← 未用，我自制了一套16字
- 3100..Bopomofo　　　	　　	　　	　　	；思源黑(43／43字)
- 31A0..Bopomofo Extended　	　　	　　	；思源黑(32／28字)
- 31C0..CJK Strokes　　	　　　	　　	　　	；思源黑(36／36字)
- 3200..Enclosed CJK Letters and Months	　	；思源黑(255／255字)
- 3400..CJK Unified Ideographs Extension A	；思源黑(6592／6582字)
- 4E00..CJK Unified Ideographs	　　	　	；思源黑(20992／20976字)
- F900..CJK Compatibility Ideographs	　	；思源黑(472／366字)
- 1AFF0..Kana Extended-B　　	　　	　　	；思源黑(13／0字)
- 1B000..Kana Supplement　　	　　	　　	；思源黑(256／0字) ← 系统字体还支持2个
- 1B100..Kana Extended-A　　	　　	　　	；思源黑(35／0字)
- 1B130..Small Kana Extension	　　	　　	；思源黑(9／0字)

### Han2「汉辅」
SIP平面目前剩余4661个码位不够挤啥区段了。目前为ttf格式，因为工作量，可能不会制作otf版。
- 20000..CJK Unified Ideographs Extension B　	；思源黑(42720／2108字)
- 2A700..CJK Unified Ideographs Extension C　	；思源黑(4154／47字)
- 2B740..CJK Unified Ideographs Extension D　	；思源黑(222／34字) ← 系统字体反而完全支持
- 2B820..CJK Unified Ideographs Extension E　	；思源黑(5762／112字)
- 2CEB0..CJK Unified Ideographs Extension F　	；思源黑(7473／5字)
- 2F800..CJK Compatibility Ideographs Supplement；思源黑(542／55字)

### Han3「汉叁」
TIP平面目前虽然还剩余5,6403个码位，但考虑到向后兼容，前途无量啊。目前为ttf格式，同上，可能不会制作otf版。
- 30000..CJK Unified Ideographs Extension G　	；思源黑(4939／4字)
- 31350..CJK Unified Ideographs Extension H　	；思源黑(4192／0字)

## Hani 更新速览
前略。第9版之后具体更新见[补字笔记](/Hani/note.md)。

### v7.x
- 2021-5-18 [v7.1](https://github.com/MY1L/Unicode/releases/tag/v6.2) 初发布
- 2021-7-5  v7.2 添加减字谱`𝬑`
- 2021-7-6  v7.21 添加传统火鸡，修改`𮧵`
- 2021-8-10 [v7.27](https://github.com/MY1L/Unicode/releases/tag/v6.21) 继续添加传统火鸡、uvs，等
- 2021-9-14 v7.28 新增“元”，忘发布

### [v8.x](https://github.com/MY1L/Unicode/releases/tag/Hani8)
- 2021-‎12-‎19 v8 新增算筹画正字，等，其中`𝍵`相比 Last7.12 有更新
- 2022-‎2-‎1 v8.1 春节，新增合字，等

### [v9.x](https://github.com/MY1L/Unicode/releases/tag/Hani9)
- 2023-1-29 v9 示亡号特性支持，尝试BMP平面`Hani`支持，修正错字，等 **← 这里开始扩展**
  - 为避让BMP平面汉字，v8.x 的一些字形移动到私用区增乙或不再支持，由我其它字体接手
- 2023-1-30 v9.001 微调、补充或替换，来自 Last8
- 2023-1-31 v9.1 硬是自己补了百余个字：全BMP平面`Hani`支持，添加原创表意描述字符，等
- 2023-2-1  v9.2 补充注音、附围中日韩字母及月份，等
- 2023-2-14 v9.… 微调，新增合字及相关特性、合略仮名，现在和未来的小型假名都填满了
- 2023-2-18 v9.5 新增汉字笔画，添加原创假名扩充乙，等