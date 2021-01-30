# 区段名缩略
abbreviate，“缩略”，简写作abbr。

苦于名称过长，对统一码[Blocks-13.0.0.txt](https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt)文件内区段名称作缩写。其实我已经在很多场合用过了，详见abbr.txt。

## 出典

### ISO四字代码
国际标准化组织的标准：ISO 15924（[变更中](https://www.unicode.org/iso15924/codechanges.html)）为各种文字体系（scripts）定义了四字代码作区分。四字代码当缩写用的唯一问题是某些文字名称少于4字也得补长到4字。

#### 区段名没用上，但字符可以用
- Hani	Han (Hanzi, Kanji, Hanja)
- Jpan	Japanese (Han + Hiragana + Katakana)
- Qaaa	Reserved for private use (始)
- Qabx	Reserved for private use (终)
- Zinh	Inherited	继承
- Zyyy	Common	公用
- Zzzz	Unknown

### 统一码别名
据[PropertyValueAliases-13.0.0.txt](http://www.unicode.org/Public/UCD/latest/ucd/PropertyValueAliases.txt)：

- Char	Character(s)
- Com	Compat	Compatibility
- Comp	Component/Composition
- Enc	Circle/Enclosed
- Ext	Extended/Extension(s)
- Ideo	Ideograph/Ideographic
- Math	Mathematical
- Misc	Miscellaneous
- Mod	Modifier
- Num	Number
- Pict	Pictographic/Pictures
- PUA	Private Use Area
- Sml	Small
- Sub	Sub
- Sup	Super
- Sup	Supplement/Supplemental/Supplementary
- Sym	Symbols
- Vert	Vertical

#### 词组
- Alchemical	Alchemical Symbols
- ArabMath	Arabic Math	Arabic Mathematical Alphabetic Symbols
- Brai	Braille	Braille Patterns
- Cjk	CJK	CJK Unified Ideographs
- CjkSym	CJK Symbols	CJK Symbols And Punctuation
- ComJamo	Compat Jamo	Hangul Compatibility Jamo
- Counting Rod	Counting Rod Numerals
- Domino	Domino Tiles
- EncCJK	Enclosed CJK	Enclosed CJK Letters And Months
- Grek	Greek	Greek And Coptic
- Half Marks	Combining Half Marks
- Hang	Hangul	Hangul Syllables
- High PU Surrogates	High Private Use Surrogates
- IDC	Ideographic Description Characters
- IdeoSym	Ideographic Symbols	Ideographic Symbols And Punctuation
- IndicNumForms	Indic Number Forms	Common Indic Number Forms
- Jamo	Hangul Jamo
- KanaExt	Katakana Ext	Katakana Phonetic Extensions
- Latn1	Latin 1	Latin 1 Sup
- Math Alphanum	Mathematical Alphanumeric Symbols
- Misc Arrows	Miscellaneous Symbols And Arrows
- Misc Pictographs	Miscellaneous Symbols And Pictographs
- ModLetters	Modifier Letters	Spacing Modifier Letters
- Music	Musical Symbols/Musical Notation
- OCR		Optical Character Recognition
- Orna	Ornamental
- PF	Presentation Forms
- Phaistos	Phaistos Disc
- Punctuation	General Punctuation
- Rumi	Rumi Numeral Symbols
- SmlForms	Small Forms	Small Form Variants
- TransportMap	Transport And Map	Transport And Map Symbols
- VS	Variation Selector(s)
- XsuxNum	Cuneiform Numbers	Cuneiform Numbers And Punctuation
- Yijing	Yijing Hexagram Symbols

#### 暂时没用上
- Diacriticals For Symbols	Combining Diacritical Marks For Symbols/Combining Marks For Symbols
- Fra	Fraction
- Med	Medial
- NB	No Block
- Nb	Nobreak
- Pres	Presentation
- Sqr	Square
- Super And Sub	Superscripts And Subscripts
- UCAS	Unified Canadian Aboriginal Syllabics/Canadian Syllabics

### 有abbr实例，以及我编的
- AaNum	Alpanum	Alphanumeric(s)
- Albt	Alphabetic
- Alch	Alchemical
- Anc	Ancient
- Arch	Archaic
- Arow	Arrows
- BlockEle	Block Elements，缩写方式存疑
- BoxDraw	Box Drawing
- Byz	Byzantine
- Ctrl	Control(s)
- comb	combining
- Diac	Diacriticals	Combining Diacritical Marks，缩写方式存疑
- Ding	Dingbats，缩写方式存疑
- DuplFormCtrl	Shorthand Format Controls
- EyDy	EarlyDynastic，缩写方式存疑
- Emon	Emoticons
- Form	Form(s)/Format
- GeoShape	Geometric Shapes
- HalfFull	Half And Full Forms	Halfwidth And Fullwidth Forms
- Indi	Indic
- Kgxi	Kangxi	Kangxi Radicals，缩写方式存疑
- Ler	Letter(s)，缩写方式存疑
- Lerlike	Letterlike Symbols，同上
- Majg	Mahjong	Mahjong Tiles
- Mu	Music，借鉴[Standard Music Font Layout (S**Mu**FL)](https://w3c.github.io/smufl/gitbook/)
- Opor	Operators，缩写方式存疑
- Otto	Ottoman
- Phon	Phonetic
- Pic	Pictographs
- PlayCard	Playing Cards
- Punc	Punctuation
- Radi	Radicals，缩写方式存疑
- Spec	Specials
- Srgs	Surrogates，缩写方式存疑
- Syll	Syllabics/Syllabary，但如不重复可以省略，没用上。
- SymfLC	Symbols for Legacy Computing
- Tech	Technical
- Trans	Transport
- TXJing	Tai Xuan Jing	Tai Xuan Jing Symbols