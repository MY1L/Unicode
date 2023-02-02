# 区段名缩略
**abbreviate**，“缩略”，简写作abbr。

苦于名称过长，对统一码[Blocks-](https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt)[15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/Blocks.txt)文件内区段名称作缩写，且缩写具有唯一性。其实我已经在很多场合用过了，详见abbr.txt。

### 更新记录
- 2021-3-3 v1.1：修改太玄经和3个Letter相关的缩略。
- 2021-9-16 v2：修正、添加统一码14.0版新增区段缩略。
  - 2022-‎9-‎12 修正下方表格。
- 2023-1-14 v3：修正、添加统一码15.0版新增区段缩略。
- 2023-1-16 v4：追加路线图版 `abbr-roadmap.txt`。更改：FormCtrl. → FC.，MiscMathSym → MiscMath
  - v4.1：更改：CountingRod. → RodNum.

## 出典

### ISO四字代码
国际标准化组织的标准：[ISO 15924](https://www.unicode.org/iso15924/iso15924-codes.html)（[变更中](https://www.unicode.org/iso15924/codechanges.html)）为各种文字体系（scripts）定义了四字代码作区分。四字代码当缩写用的唯一问题是某些文字名称少于4字也得补长到4字。

#### 区段名没用上，但字符可以用
|缩略|原意|注释|
| -: | :- | :- |
|Hani|Han|Hanzi, Kanji, Hanja|
|Jpan|Japanese|Han + Hiragana + Katakana|
|Qaaa|Reserved for private use|私用始|
|Qabx|Reserved for private use|私用终|
|Zinh|Inherited|继承|
|Zyyy|Common|公用|
|Zzzz|Unknown|[不明](https://github.com/MY1L/unMing)|

### 统一码别名
据[PropertyValueAliases-](http://www.unicode.org/Public/UCD/latest/ucd/PropertyValueAliases.txt)[15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/PropertyValueAliases.txt)：

|缩略|简写|原文|
| -: | :- | :- |
|Char||Character(s)|
|Com|Compat|Compatibility|
|Comp||Component／Composition|
|Enc||Circle／Enclosed|
|Ext||Extended／Extension(s)|
|Ideo||Ideograph／Ideographic|
|Math||Mathematical|
|Misc||Miscellaneous|
|Mod||Modifier|
|Num||Number|
|Pict||Pictographic／Pictures|
|PUA||Private Use Area|
|Sml||Small|
|Sub||Sub|
|Sup||Super|
|Sup||Supplement／Supplemental／Supplementary|
|Sym||Symbols|
|[Vert](https://github.com/MY1L/vert)||Vertical|

#### 词组
|缩略|简写|原文|
| -: | :- | :- |
||Alchemical|Alchemical Symbols|
|ArabMath|Arabic Math|Arabic Mathematical Alphabetic Symbols|
|Brai|Braille|Braille Patterns|
|Cjk／Han|CJK|CJK Unified Ideographs|
|CjkSym／HanSym|CJK Symbols|CJK Symbols And Punctuation|
|ComJamo|Compat Jamo|Hangul Compatibility Jamo|
||Domino|Domino Tiles|
|EncCJK|Enclosed CJK|Enclosed CJK Letters And Months|
|Grek|Greek|Greek And Coptic|
||Half Marks|Combining Half Marks|
|Hang|Hangul|Hangul Syllables|
||High PU Surrogates|High Private Use Surrogates|
|IDC||Ideographic Description Characters|
|IdeoSym|Ideographic Symbols|Ideographic Symbols And Punctuation|
|IndicNumForms|Indic Number Forms|Common Indic Number Forms|
|Jamo||Hangul Jamo|
|KanaExt|Katakana Ext|Katakana Phonetic Extensions|
|Latn1|Latin 1|Latin 1 Sup|
||Math Alphanum|Mathematical Alphanumeric Symbols|
||Misc Arrows|Miscellaneous Symbols And Arrows|
||Misc Pictographs|Miscellaneous Symbols And Pictographs|
|ModLetters|Modifier Letters|Spacing Modifier Letters|
||Music|Musical Symbols／Musical Notation|
|OCR||Optical Character Recognition|
|Orna||Ornamental|
|PF||Presentation Forms|
||Phaistos|Phaistos Disc|
||Punctuation|General Punctuation|
|Rumi||Rumi Numeral Symbols|
|SmlForms|Small Forms|Small Form Variants|
|TransportMap|Transport And Map|Transport And Map Symbols|
|VS||Variation Selector(s)|
|XsuxNum|Cuneiform Numbers|Cuneiform Numbers And Punctuation|
||Yijing|Yijing Hexagram Symbols|

#### 未用
|缩略|原文|
| -: | :- |
|Diacriticals For Symbols|Combining Diacritical Marks For Symbols／Combining Marks For Symbols|
|Fra|Fraction|
|Med|Medial|
|NB|No Block|
|Nb|Nobreak|
|Pres|Presentation|
|Sqr|Square|
|Super And Sub|Superscripts And Subscripts|
|UCAS|Unified Canadian Aboriginal Syllabics／Canadian Syllabics|

### 已有实例，以及我编的
|缩略|简写|原文|注释|
| -: | :- | :- | :- |
|AaNum|Alpanum|Alphanumeric(s)|缩略存疑|
|Albt||Alphabetic|
|Alch||Alchemical|
|Anc||Ancient|如[Roadmaps]|
|Arch||Archaic|如[Roadmaps]|
|Arow||Arrows|
|Blocks|BlockEle.|Block Elements|如[Roadmaps]|
|BoxDraw||Box Drawing|
|Byz||Byzantine|同欧陆风云|
|Ctrl||Control(s)|
|comb||combining|
|Diac|Diacriticals|Combining Diacritical Marks|如[Roadmaps]|
|Ding||Dingbats|缩略存疑|
|EyDy||EarlyDynastic|缩略存疑|
|Emon||Emoticons|
|Form||Form(s)／Format|
|FC|FormCtrl.|Format Controls|如[Roadmaps]|
|GeoShape||Geometric Shapes|
|Half|HalfMarks.|Combining Half Marks|如[Roadmaps]|
|HalfFull|Half And Full Forms|Halfwidth And Fullwidth Forms|
|Horz||Horizontal|Vert反义词，这里没用上|
|Indi||Indic|
|Kbn||Kanbun|如[Roadmaps]|
|Kgxi|Kangxi|Kangxi Radicals|缩略存疑|
|Lttr||Letter(s)|
|Lttrlike||Letterlike Symbols|
|Majg|Mahjong|Mahjong Tiles|
|mirr||mirror|微软描述右到左文字的缩略，没用上|
|MiscMath||Miscellaneous Mathematical Symbols|如[Roadmaps]|
|Mu||Music|借鉴[Standard Music Font Layout (S**Mu**FL)](https://w3c.github.io/smufl/gitbook/)|
|Opor||Operators|缩略存疑|
|Otto||Ottoman|欧陆风云作`TUR`，不适合|
|Phon||Phonetic|
|Pic||Pictographs|
|PlayCard||Playing Cards|
|Punc|Punct.|Punctuation|如[Roadmaps]|
|Radi||Radicals|缩略存疑|
|RodNum.|Rod Nums|Counting Rod Numerals|如[Roadmaps]|
|Sh||Shorthand|如[Roadmaps]|
|ShawQS|ShavianQS|Shavian Quikscript Extensions|如[Roadmaps]|
|Spec||Specials|如[Roadmaps]|
|Srgs||Surrogates|缩略存疑|
|Syll||Syllabic(s)／Syllabary|如不重复可省略|
|SymfLC||Symbols for Legacy Computing|缩略存疑|
|Tech||Technical|
|Trans||Transport|
|TXjing|Tai Xuan Jing|Tai Xuan Jing Symbols|仿`Yijing`|
|Vert.|VertForm.|Vertical Forms|如[Roadmaps]|

#### 见于[Roadmaps]但未用
|简写|原文|
| -: | :- |
|Cyr-x|Cyrillic Extended|
|Eg.|Egyptian|
|Ep|Epact|
|Eth.|Ethiopic|
|Hi.|Hieroglyph|
|Hier.|Hieroglyphs|
|Ids.|Ideographs|
|Kk.|Katakana Phonetic Extensions|
|№|Numbers|
|Punct.|Punctuation|
|Supp.|Supplement|
|Symb.／Syms.／Symbs.|Symbols|
|Syr.|Syriac|
|Unif.|Unified|

[Roadmaps]: https://www.unicode.org/roadmaps/index.html