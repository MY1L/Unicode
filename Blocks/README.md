# 统一码区段汉化
苦于译名混乱，对统一码[Blocks-15.0.0.txt](https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt)文件内区段名称作汉化。

## 更新
- 第2版：和英文一样不区分“某”文\字、“某”字母、“某”语的文字。据[Unicode Standard 译介尝试（一）・文种名、符号名与块名](https://zhuanlan.zhihu.com/p/240087278)（下略称“尝试”）修正大量译名，少量参考《GB/T 34836-2017 信息与文献　文字名称表示代码》（下略称“GB/T”）。更新对译表，改动之处见注释。
  - 2.1版，2021-1-5，更正：“阿拉伯数学字母符号”
- 第3版：就[cv8280047 - 哔哩哔哩](https://www.bilibili.com/read/cv8280047#reply3919855387)评论区讨论结果修改存疑部分。
  - 3.1版，更正：“图符”
- 第4版：添加统一码14.0新增区段，及改动区段范围：阿含扩到..1174F，西夏补充..18D8F修正为..18D7F（[13.0.0勘误：2020-3-11](https://www.unicode.org/versions/Unicode14.0.0/erratafixed.html)，该错误导致字体Last发布延迟）。略译文件开头注释。
  - 4.1版：就[Kushim-Jiang/Zhuanlan-Zhihu/006](https://github.com/Kushim-Jiang/Zhuanlan-Zhihu/tree/master/006)更新内容修改。
  - 4.2版：就[有哪些语言学术语翻译得并不恰当？ - 知乎](https://www.zhihu.com/answer/2076356395)内容修改。
- 第5版：添加统一码15.0新增区段，改动部分区段范围，修改译名：那巴泰 → 奈伯特、王朝阿拉姆 → 帝国阿拉姆、…象形文字 → …意音文字，等。
- 第6版，2023-1-15：改善和添加示例。此页补充平面翻译。追加路线图版 `Blocks-roadmap.txt`
  - 6.1版：修正路线图版区段范围。补充有 ISO 15924 代码的路线图外译名。

## 对译表
我推敲统一码取名不一定用英文原本含义，因此下列词组优先于词，已用 *着重样式* 标出。

|原文|译文|注释|
| -: | :- | - |
|Additional|追加||
|Alphabetic|字母||
|Alphanumerics|字母数字||
|*Ancient* Greek|古希腊||
|Ancient|古代|实际多为古罗马……|
|and|及||
|Arrows|箭头||
|Block Elements|方块构素|Block作区段名不译“区段”|
|Box Drawing|制表符||
|Character(s)|字符||
|CJK|中日韩||
|CodePoint|码位||
|Combining|结合|曾译“组合”|
|Common／General|通用|General曾译“常用”|
|Compatibility|兼容||
|Components|偏旁||
|Control|控制||
|Controls|控制符||
|Cuneiform|楔形／楔形文字||
|Cursive|草书体|不译“世俗体”(Demotic)|
|Description|描述||
|Diacritical|变音||
|Dingbats|什锦||
|Enclosed|附围|带圈或围括号或附标……|
|Extended／Extensions|扩充|曾译“扩展”|
|Form(s)|形式||
|Format|格式|见cv8280047评论区|
|Hieroglyph(s)|圣书体／意音文字|不译“象形文字”：[黑之圣雷](https://www.zhihu.com/question/480891401)反对|
|Ideograms／Ideographic|表意／表意文字||
|Legacy Computing|遗留电脑|Legacy曾译“传统”，Computing不译“计算”|
|Letters|字／字母||
|Linear|线形／线形文字|不译“线性文字”|
|Marks|标记||
|Mathematical|数学||
|Miscellaneous|各式|曾译“杂项”|
|Modifier Tone Letters|声调修饰字|语序调整|
|Modifier|修饰||
|Musical Notation|音符|Note“音符”，Notation“谱”|
|Musical Symbols|乐符||
|Counting Rod *Numerals*|算筹|“算筹”已含数字涵义|
|Number(s)／Numeral(s)|数字||
|Old Turkic|突厥|没有“(今)突厥”了|
|Operators|运算符||
|Patterns|点字|仅限描述盲文|
|Phonetic|音标||
|Playing Cards|扑克|亦译“纸牌”，但语感似泛指纸质牌|
|Pictographs|象形|这才是“象形文字”吧……|
|Pictographic|图形||
|Pictures|图符|曾译“图形”|
|Presentation|表现|曾译“表达”，“尝试”译“显现”|
|Proto-|原始||
|Punctuation|标点||
|Radicals|部首||
|Selectors|选择符||
|Shorthand|速记||
|SignWriting|手语|“GB/T”|
|Spacing|有距|直译“间距”，指字符相对同形结合标记而言左右有间距|
|Strokes|笔画||
|Extensions *Supplement*|扩充增补|只是“扩充补充”比较傻，曾译“补遗”|
|Supplement|补充|后置|
|Supplemental／Supplementary|增补|前置|
|Surrogates|替代|或译“代理(对)”（Surrogate Pair）|
|Syllabics|音节|音节文字|
|*Marks* for *Symbols*|记号||
|Hexagram *Symbols*|六十四卦|“卦”已含符号涵义|
|Tai Xuan Jing *Symbols*|太玄经卦爻|存在此称谓|
|Symbols|符／符号||
|Technical|技术符|不完全是“工业”|
|Tiles|牌|牌面和牌背都有|
|Unified|统一||
|Variants／Variation|变体||

## 双标
这些译法例外。

|原称|译称|注释|
| -: | :- | - |
|Duployan|杜普雷速记|字客网译“杜洛耶速记”，“尝试”按法语Duployé译“迪普卢瓦耶”|
|Ethiopic|埃塞|直译“埃塞俄比亚”，但区段收的是ግዕዝ([格厄兹字母](https://www.zhihu.com/topic/21821106/hot))|
|Hangul Jamo|谚文字母|直译“韩文字母”，但有朝鲜|
|Lisu|傈僳(老)|直译“傈僳”，但区段收的是传教士SaraBaThaw创制的老傈僳文，又称“富能仁文”(Fraser)|
|Miao|苗(老)|直译“苗”，但区段收的是传教士柏格理(Pollard，ISO 15924：Plrd)等人创制的滇东北**老苗文**|
|Pahawh Hmong|帕皓苗|直译“字母表苗”，“尝试”译“帕皓苗”，“GB/T”译“苗文”，异名“救世苗文”|
|Nyiakeng Puachue Hmong|苗(创世)|直译“创世完成苗\创世纪苗文”（[Hmnp.該怎麼翻譯？](https://www.ubuntu-tw.org/modules/newbb/viewtopic.php?post_id=361148)），“尝试”译“涅该布瓦启苗”，“GB/T”2017无|
|New Tai Lue|新傣仂|“尝试”曾译“新傣泐”，[我们的文字](http://www.nlc.cn/cmptest/wmdwz/ssmz/index_11.htm)：古代傣族称西双版纳为“泐”|
|Tai Le|傣㐻|又译“德宏傣文”|
|Tai Tham|傣昙|即 老傣文、(老)傣泐文|

## 平面
~~或译“飞机”~~。统计截至统一码15.0.0版：

|#|简称|原称|译称|区数|字数|余数|
| -: | -: | -: | :- | -: | -: | -: |
|0|BMP|Basic Multilingual Plane|基本多文种平面|161|62034|1420|
|1|SMP|Supplementary Multilingual Plane|增补多文种平面|151|23276|42258|
|2|SIP|Supplementary Ideographic Plane|增补表意平面|6|60873|4661|
|3|TIP|Tertiary Ideographic Plane|第三表意平面|2|9131|56403|
|4~13|-|-|-|0|0|65534|
|14|SSP|Supplementary Special-purpose Plane|增补殊用平面|2|337|65197|
|15|PUA-A|Supplementary Private Use Area-A|增补私用区甲|1|65534|0|
|16|PUA-B|Supplementary Private Use Area-B|增补私用区乙|1|65534|0|

## 图外
- Visible Speech：钟雨柔：“**可视语音**”:汉字革命与字母普遍主义在中国
  - 这是类似音标的非语言，且没有主流语言用它作为文字。
  - ISO 15924	Visp	280	Visible Speech
- KLI：[Klingon Language Institute](http://klingon.wiki/En/KlingonLanguageInstitute)（克林贡语言学院）的缩写，可简称“克语”
  - ISO 15924	Piqd	293	Klingon (KLI pIqaD)
- Sarati：https://lotr.huijiwiki.com/wiki/**萨拉提**
  - ISO 15924	Sara	292	Sarati