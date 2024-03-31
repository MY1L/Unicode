# 统一码名词缩略
**abbreviate**，“缩略”，简写作abbr。

苦于名称过长，对统一码[Blocks-](https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt)[15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/Blocks.txt)文件内区段名称等作缩写，且缩写具有唯一性。其实我已经在很多场合用过了，详见[abbr.txt](/abbr/abbr.txt)。

## 更新
- 第1.1版，2021-3-3：修改太玄经和3个Letter相关的缩略。
- 第2版，2021-9-16：修正、添加统一码14.0版新增区段缩略。
  - 2022-‎9-‎12 修正下方表格。
- 第3版，2023-1-14：修正、添加统一码15.0版新增区段缩略。
- 第4版，2023-1-16：追加规划版[abbr-roadmap.txt](/abbr/abbr-roadmap.txt)，注意标注在文本底部。更改：FormCtrl. → FC.，MiscMathSym → MiscMath
  - 4.1版：更改：CountingRod. → RodNum.
  - 4.2版：修正遗漏缩略，补充底部标注。
  - 4.3版：略改，添加备注。
  - 4.4版：更新实例，更改：Radi → Rad，Emon. → Emos.，补充“第十平面”🥴
  - 4.5版：补充实例。
- 第5版，2023-4-12：据[SMP规划15.0.2](https://www.unicode.org/roadmaps/smp/smp-15-0-2.html)更新规划版.txt。
  - 5.1版：略修规划版。
- 第6版，2023-5-20：更新SIP、TIP平面规划版区段。
- 第7版，2023-10-1：更新至统一码15.1版、更新ISO四字代码、据[SMP规划15.0.3](https://www.unicode.org/roadmaps/smp/smp-15-0-3.html)更新规划版.txt，等。
  - 7.1版：几处小更正。
  - 7.2、.3版：几处补充，以利于理解ISO代码。
  - 7.4版：更新SMP平面规划版区段（v15.1.1）
  - 7.5版：更新SMP平面规划版区段（v15.1.2）

## 出典

### ISO四字代码
国际标准化组织的 [ISO 15924](https://www.unicode.org/iso15924/iso15924-codes.html)（[变更中](https://www.unicode.org/iso15924/codechanges.html)）对各种 scripts 规定了四字代码作区分。该代码当缩写用的唯一问题是某些文字名称少于4字也得补长到4字。

#### 区段名不用，字符名或可用
下表略去[文件](https://www.unicode.org/iso15924/iso15924.txt)中的法文名。`Geor`区段名在用，`Zsye`规划版区段名或可用。
|缩略|英文|注释|
| -: | - | :- |
|Aran|Arabic (Nastaliq variant)|阿拉伯（波斯体）|
|Cyrs|Cyrillic (Old Church Slavonic variant)|西里尔（古教会斯拉夫语）|
|Egyd|Egyptian demotic|埃及世俗体|
|Egyh|Egyptian hieratic|埃及僧侣体|
|Geok|Khutsuri (Asomtavruli and Nuskhuri)|格鲁吉亚僧侣体（大写体、草写体）|
|~Geor~|Georgian (Mkhedruli and Mtavruli)|格鲁吉亚（骑士体）|
|Hanb|Han + Bopomofo|`Hani`+`Bopo`|
|Hani|Han (Hanzi, Kanji, Hanja)|汉字|
|Hans|Han (Simplified variant)|简化字|
|Hant|Han (Traditional variant)|傳承字|
|Hrkt|Japanese syllabaries|`Hira`+`Kana`|
|Jamo|[Jamo](https://www.unicode.org/glossary/#jamo) (subset of Hangul)|字母（组成谚文的）|
|Jpan|Japanese|`Hani`+`Hrkt`|
|Kore|Korean|`Hang`+`Hani`|
|[Latf](https://github.com/MY1L/Ctrl#latf)|Latin (Fraktur variant)|拉丁（德文尖角体）|
|Latg|Latin ([Gaelic](https://omniglot.com/writing/clogaelach.htm) variant)|拉丁（盖尔语）|
|Syre|Syriac (Estrangelo variant)|叙利亚（经典）|
|Syrj|Syriac (Western variant)|叙利亚（西部）|
|Syrn|Syriac (Eastern variant)|叙利亚（东部）<!--景教-->|
|Qaaa|Reserved for private use (start)|私用（始）|
|Qabx|Reserved for private use (end)|私用（终）|
|Zinh|Code for inherited script; Inherited|自形位簇继承的文种〔如：结合标记〕；继承|
|Zmth|Mathematical notation|数学符号|
|[Zsye](https://github.com/MY1L/Ctrl#zsye)|Symbols (Emoji variant)|符号（绘文字）|
|Zsym|Symbols|符号|
|Zxxx|Code for unwritten documents|非书面能指系统〔如：手语〕|
|Zyyy|Code for undetermined script; Common|跨文种〔标点､货币符号､阿拉伯数字〕；通用|
|Zzzz|Code for uncoded script; Unknown|未编码文种；[不明](https://github.com/MY1L/unMing)|

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
|Han|CJK|CJK Unified Ideographs|
|HanSym|CJK Symbols|CJK Symbols And Punctuation|
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
|AaNum|Alpanum|Alphanumeric(s)|缩略自撰；[allacronyms]是`A/N`等|
|Albt||Alphabetic|缩略自撰|
|Alch||Alchemical|常见缩略|
|Anc||Ancient|如[Roadmaps]|
|Arch||Archaic|如[Roadmaps]|
|Arow||Arrows|缩略自撰|
|Blocks|BlockEle.|Block Elements|如[Roadmaps]|
|BoxDraw||Box Drawing|
|Byz||Byzantine|同欧陆风云|
|Ctrl||Control(s)|常见于键盘|
|comb||combining|常见缩略；[allacronyms]有|
|Diac|Diacriticals|Combining Diacritical Marks|如[Roadmaps]|
|Ding||Dingbats|缩略自撰|
|EyDy||Early Dynastic|缩略自撰；[allacronyms]是`ED`|
|Emos||Emoticons|缩略自撰|
|Form||Form(s)／Format|
|FC|FormCtrl.|Format Controls|如[Roadmaps]|
|GeoShape||Geometric Shapes|[allacronyms]是`Geom ~`等|
|Half|HalfMarks.|Combining Half Marks|如[Roadmaps]|
|HalfFull|Half And Full Forms|Halfwidth And Fullwidth Forms|
|Horz||Horizontal|`Vert`反义词，常见缩略；[allacronyms]有|
|Indi||Indic|
|Janz||Jianzi|缩略自撰|
|Kakk||Kaktovik|缩略自撰|
|Kbn||Kanbun|如[Roadmaps]|
|Kgxi|Kangxi|Kangxi Radicals|缩略自撰|
|Lttr||Letter(s)|已有实例|
|Lttrlike||Letterlike Symbols|
|Majg|Mahjong|Mahjong Tiles|微软Bing认同，搜索缩略“微软麻将”在前|
|mir||mirror|Noto Math描述镜像字符的缩略，没用上|
|mirr||mirror|微软描述右到左文字的缩略，没用上|
|MiscMath||Miscellaneous Mathematical Symbols|如[Roadmaps]|
|Mu||Music|借鉴[Standard Music Font Layout (S`Mu`FL)](https://w3c.github.io/smufl/gitbook/)|
|Opor||Operators|缩略自撰；[allacronyms]是`Ops`|
|Orcl|Oracle|Oracle Bone Script|甲骨文公司的纳斯达克股票代码缩写|
|Otto||Ottoman|欧陆风云作`TUR`，不适合；[allacronyms]是`Ott`|
|Phon||Phonetic|[allacronyms]有|
|Pic||Pictographs|常见缩略|
|PlayCard||Playing Cards|
|Punc|Punct.|Punctuation|如[Roadmaps]|
|Rad||Radicals|[allacronyms]有|
|RodNum.|Rod Nums|Counting Rod Numerals|如[Roadmaps]|
|Rot|Rotat|Rotation|描述字形顺时针旋转90°，没用上；[allacronyms]有|
|Sh||Shorthand|如[Roadmaps]|
|ShawQS|ShavianQS|Shavian Quikscript Extensions|如[Roadmaps]|
|~syqNum|~SiyaqNum.|~ Siyaq Numbers|老外缩略
|Spec||Specials|如[Roadmaps]|
|SP|SPUA-|Supplementary Private Use Area-|[n3412-last-resort](https://unicode.org/wg2/docs/n3412.pdf)|
|Srgs||Surrogates|缩略自撰；[allacronyms]是`Surr`等|
|Syll||Syllabic(s)／Syllabary|如不重复可省略|
|SymfLC||Symbols for Legacy Computing|缩略自撰|
|Tech||Technical|常见缩略；[allacronyms]有|
|Trans||Transport|常见缩略；[allacronyms]有|
|TXjing|Tai Xuan Jing|Tai Xuan Jing Symbols|自撰，仿`Yijing`|
|Vert.|VertForm.|Vertical Forms|如[Roadmaps]|
|Zna||Znamenny|缩略自撰|

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
[allacronyms]: https://www.allacronyms.com