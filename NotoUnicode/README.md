# Noto Unicode
这是个工具字体，意思是**不负责排版**仅负责显示，类似Unifont字体。

补字原则是“宛如原生”，与Noto同类字形放在一起应难以区分，如：占星术 ⯓🝻、音标 u1E030ᵃ𞁊……尽量覆盖罕用和一般人不太在乎排版的SMP平面。

制作该字体的急迫性在于，我用一般软件如BabelMap时，点字体菜单总是因为Noto系列字体太多影响到选取。

![Noto太多了](/NotoUnicode/Notoomany.png)

而装这些我不了解的文字的字体，也只为BabelMap、浏览器等显示不缺字，实际上我并不迫切需要准确地排版这么多文种，只要看得见字就行，如果遇到需要准确排版的情况还可单独另装。

于是将100+个字体合并为一：「Noto Unicode<sup> 不妨简称为NotoUni</sup>」，删除所有OT特性和不在统一码表里的字符（合字、异体等等），由此体积压缩了一半。特别是针对BabelMap每个区段只能用一个字体的设定，画了些Noto缺的字符把整个区段填满——毕竟某些区段如“表意符号及标点”性质上就不太可能只用一个字体显示完。

如果系统默认字体已经存在能填满某区段的就不加，避免字体体积过大或装不下——字体包含字形上限为65536。NotoUni支持的统一码区段列表太长这儿放不下，记录在[sysBlocks.txt（截至第五版）](/NotoUnicode/sysBlocks.txt)

## 更新
2.003 第一版，初次发布，总字数11270+(计算方法差异，此字数忽略部分控制字，下同)

2.2.003 第二版，覆盖BMP平面，总字数15948+，因No tofu字体缺字而自画了些字符补全，自制了个“TOFU（豆腐）”字符用于缺字提示
- 按 [U11180.pdf](http://www.unicode.org/charts/PDF/U11180.pdf) 画了U+111CE、U+111CF补全该区
- 按 [U11400.pdf](http://www.unicode.org/charts/PDF/U11400.pdf) 画了U+1145A、U+11460、U+11461补全该区
- 按 [U16FE0.pdf](http://www.unicode.org/charts/PDF/U16FE0.pdf) 造了U+16FE0~16FFF整个区！大多改自Noto Sans CJK，U+16FE0用的㇋改，U+16FF0用的“饣+忄”，U+16FF1用的“巡”右笔

3.2.03 第三版，填满了更多区段，总字数16208+
- [100+字体合一：工具字体Noto Unicode初发布v3 - 哔哩哔哩](https://www.bilibili.com/read/cv8805564)
- 尤其在2020-11-18：自制阿拉伯「ALM」U+061C，自制蒙文「FVS」U+180B~180D
- 注音扩充U+31A0～31BF，除了U+31BF~~改了思源的ハ~~，其它制作都很麻烦……

4 第四版，添加和补充区段，总字数16976+
- 自制蒙古「MVS」U+180E
- 2021-1-20~21：添加萨顿手语（填满672个）、符号及象形扩甲（填满57个），添加阿拉伯扩甲2个、交通及地图符号4个
- 用Noto Sans Symbols2新版2.003替换BabelStone字体：各式符号及箭头（U+2B97）、古代符号（U+1019C）、增补箭头丙（U+1F8B0 U+1F8B1）、传统电脑符号（全部）
- 刷新5个阿拉伯区段，除了U+FDFD这一字符，因为变化过大
- 添加33个控制字图符，但大多不计总字数内

5 第五版，添加和补充区段，修改若干自制字符，总字数17205+
- 2021-‎10-‎5：自制「FVS4」U+180F、「С̲」U+20C0，从而补全 蒙文、货币 2个区段
- 改善虚线圈相关自制字符、注音扩充U+31BC～31BF（ㆼㆽㆾㆿ）、蒙文（FVS2 FVS3）
- 替换卢恩区段为自制字体[Ctrl Runr][r]
- 添加 藏文、统一加拿大土著音节扩充甲 2个区段

**之后更新请移步[NotoUni7.md](/NotoUnicode/NotoUni7.md)**

## 涵盖：截至第五版
以下为该个字体缝合的Noto字体列表。

> 下列依次是：文件名 版本，GitHub更新日期，厂商或作者，-损失的OT特性。
> - 如果厂商或作者后面直接是句号，表示没有损失任何特性，原字体就是光秃秃的。
> - 版本后面跟着「\」的表示大概是写错的版本。
> - 有些Monotype与他人合作的字体也记作Monotype。
> - 「Segoe UI…」指Segoe UI、Segoe UI Symbol或Segoe UI Historic。

<details><summary><strong>——列表很长，点此展开\折叠——</strong></summary>

1. NotoSans-Regular 2.003，2020-7-6，Monotype，-aalt c2sc case ccmp dnom frac kern liga lnum locl mark mkmk numr onum ordn pnum rtlm salt smcp ss03～ss04 subs sups tnum zero。
1. NotoMusic-Regular 2.000，2020-7-4，Monotype，-ccmp curs kern mark mkmk。与Segoe UI…重复的区段没有添加。
1. NotoSansAdlam-Regular 3.000，2020-7-4，JamraPatel LLC，-aalt case ccmp fina init kern mark medi。
1. NotoSansAnatolianHieroglyphs-Regular 2.000，2020-7-4，Monotype。
1. NotoSansArabicUI-Regular 2.007，2021-1-13，Monotype，-aalt ccmp dlig fina init isol kern locl mark medi mkmk rlig。
1. NotoSansArmenian-Regular 2.005，2020-7-5，Monotype，-kern liga mark。
1. NotoSansAvestan-Regular 2.001，2020-7-4，Monotype，-liga。
1. NotoSansBamum-Regular 2.000，2020-7-4，Monotype。
1. NotoSansBassaVah-Regular 2.000，2020-7-4，Monotype，-ccmp kern mark。
1. NotoSansBatak-Regular 2.000，2020-7-4，Monotype，-ccmp mark mkmk。
1. NotoSansBengali-Regular 2.001，2020-7-5，Monotype，-abvm abvs akhn blwf blwm blws cjct dist half init kern nukt pres pstf psts rphf vatu。
1. NotoSansBhaiksuki-Regular 2.001，2020-7-4，Monotype，-abvs ccmp dist kern mark mkmk rlig rphf ss01。
1. NotoSansBuhid-Regular 2.000，2020-7-4，Monotype，-ccmp mark。
1. NotoSansCanadianAboriginal-Regular 2.001，2021-10-2，Monotype，-salt。与Gadugi重复的区段没有添加。
1. NotoSansCaucasianAlbanian-Regular 2.001，2020-7-4，Monotype，-ccmp kern mark mkmk。
1. NotoSansChakma-Regular 2.001，2020-9-18，Monotype，-abvs blwf blws dist liga mark mkmk pres pstf ss01～ss03。
1. NotoSansCham-Regular 2.000，2020-7-4，Monotype，-calt ccmp clig dist kern liga locl mark mkmk pref pres。
1. NotoSansCoptic-Regular 2.000，2020-7-4，Monotype，-ccmp mark mkmk。U+2C80-U+2CFF有但未用。
1. NotoSansCuneiform-Regular 2.000，2020-7-4，Monotype。与Segoe UI…重复的区段没有添加。
1. NotoSansDevanagari-Regular 2.001，2020-9-18，Monotype，-abvm abvs akhn blwf blwm blws cjct dist half haln locl nukt pres psts rkrf rphf vatu。
1. NotoSansDevanagariUI-Regular 2.001，2020-9-18，Monotype，-同上。个别字符有差异，所以混合使用。
1. NotoSansDuployan-Regular 2.000，2020-7-4，Monotype。
1. NotoSansElbasan-Regular 2.000，2020-7-4，Monotype，-ccmp mark。
1. NotoSansElymaic-Italic 1.000，2020-7-4，Morgane Pierson，-aalt dlig kern salt ss01～ss03。貌似该字体无Regular。
1. NotoSansGeorgian-Regular 2.001，2020-7-4，Monotype，-aalt case ccmp kern mark mkmk。
1. NotoSansGlagolitic-Regular 2.000，2020-7-4，Monotype，-mark mkmk。
1. NotoSansGrantha-Regular 2.001，2020-7-4，Monotype，-abvs blwf blws calt cjct dist haln kern mark mkmk pstf psts rlig rphf ss01～ss10。
1. NotoSansGujarati-Regular 2.001，2020-7-5，Monotype，-abvm abvs akhn blwf blwm blws cjct dist half haln nukt pres psts rkrf rphf vatu。
1. NotoSansGunjalaGondi-Regular 1.001，2020-7-4，Ek Type，-calt dist kern mark mkmk ss01 ss02。
1. NotoSansGurmukhi-Regular 2.001，2020-7-5，Monotype，-abvm abvs blwf blwm blws calt dist half haln nukt pstf。
1. NotoSansHanifiRohingya-Regular 2.100，2020-7-4，Monotype，-fina init kern mark medi mkmk ss01 ss02。
1. NotoSansHanunoo-Regular 2.000，2020-7-4，Monotype，-ccmp mark salt。
1. NotoSansHatran-Regular 2.000，2020-7-4，Monotype。
1. NotoSansHebrew-Regular 3.000，2020-9-18，Ben Nathan，-ccmp dlig kern mark。
1. NotoSansIndicSiyaqNumbers 2.000，2020-7-4，Monotype，-curs ss01。
1. NotoSansKaithi-Regular 2.001，2020-7-4，Monotype，-abvs akhn cjct half kern mark mkmk psts rclt rphf ss01～ss03。
1. NotoSansKayahLi-Regular 2.001，2020-7-4，Monotype，-aalt ccmp mark。
1. NotoSansKharoshthi-Regular 2.001，2020-7-4，Monotype，-abvs blws cjct dist kern mark mkmk psts rclt ss01。
1. NotoSansKhojki-Regular 2.001，2020-7-4，Monotype，-blws ccmp dist kern mark mkmk psts salt。
1. NotoSansKhudawadi-Regular 2.000，2020-7-4，Monotype，-abvf abvs dist mark mkmk。
1. NotoSansLepcha-Regular 2.000，2020-7-4，Monotype，-abvs ccmp dist kern mark mkmk。
1. NotoSansLimbu-Regular 2.000，2020-7-4，Monotype，-ccmp mark mkmk。
1. NotoSansLinearA-Regular 2.000，2020-7-4，Monotype。
1. NotoSansLinearB-Regular 2.001，2020-7-4，Monotype。
1. NotoSansMahajani-Regular 2.000，2020-7-4，Monotype，-mark。
1. NotoSansMandaic-Regular 2.001，2020-7-4，Monotype，-aalt calt fina init isol mark medi。
1. NotoSansManichaean-Regular 2.000，2020-7-4，Monotype，-ccmp fina init mark medi rclt。
1. NotoSansMarchen-Regular 2.001\3.000，2020-7-4，Monotype，-abvs calt mark mkmk pres。
1. NotoSansMasaramGondi-Regular 1.002，2020-7-4，Ek Type，-calt dist kern mark ss01 ss02。
1. NotoSansMath-Regular 2.001，2020-7-4，Monotype，-aalt fwid mark mkmk rtlm。与Segoe UI…重复的区段没有添加。花体与Noto默认不同。
1. NotoSansMayanNumerals-Regular 2.000，2020-7-4，Monotype。
1. NotoSansMedefaidrin-Regular 1.001，2020-10-27，Dalton Maag Ltd，-kern。
1. NotoSansMeeteiMayek-Regular 2.001，2020-7-4，Monotype，-blws mark。
1. NotoSansMendeKikakui-Regular 2.000，2020-7-4，Monotype，-ccmp kern mark。
1. NotoSansMeroitic-Regular 2.000，2020-7-4，Monotype，-ccmp dist。
1. NotoSansMiao-Regular 2.001，2020-7-4，Monotype，-ccmp kern mark mkmk。
1. NotoSansModi-Regular 2.000，2020-9-18，Monotype，-calt half kern mark mkmk pres rphf。
1. NotoSansMongolian-Regular 2.001，2020-7-4，Monotype，-fina init isol medi rlig vert vrt2。与Segoe UI…重复的U+2460-U+2473没有添加。
1. NotoSansMro-Regular 2.000，2020-7-4，Monotype。
1. NotoSansMultani-Regular 2.000，2020-7-4，Monotype。
1. NotoSansNabataean-Regular 2.000，2020-7-4，Monotype。
1. NotoSansNewa-Regular 2.002，2020-9-18，Monotype，-abvs akhn blws calt ccmp curs dist half kern mark mkmk pref rphf。
1. NotoSansOldHungarian-Regular 2.001，2020-7-4，Monotype，-dlig kern liga ltrm。
1. NotoSansOldItalic-Regular 2.002，2020-7-4，Monotype，-rtlm。
1. NotoSansOldNorthArabian-Regular 2.000，2020-7-4，Monotype。
1. NotoSansOldPermic-Regular 2.000，2020-7-4，Monotype，-kern mark mkmk。
1. NotoSansOldSogdian-Regular 2.000，2020-7-4，Monotype，-aalt calt kern salt。
1. NotoSansOsage-Regular 2.000，2020-7-4，Monotype，-kern mark。
1. NotoSansPahawhHmong-Regular 2.000，2020-7-4，Monotype，-kern mark。
1. NotoSansPalmyrene-Regular 2.000，2020-7-4，Monotype，-dlig。
1. NotoSansPauCinHau-Regular 2.000，2020-7-4，Monotype，-kern。
1. NotoSansPsalterPahlavi-Regular 2.000，2020-7-4，Monotype，-calt ccmp fina init kern medi rclt。
1. NotoSansRejang-Regular 2.000，2020-7-4，Monotype，-mark。
1. NotoSansSamaritan-Regular 2.000，2020-7-4，Monotype，-calt dist mark mkmk。
1. NotoSansSaurashtra-Regular 2.000，2020-7-4，Monotype，-ccmp dist mark。
1. NotoSansSharada-Regular 2.001，2020-9-18，Monotype，-abvs akhn blws dist mark mkmk。
1. NotoSansSiddham-Regular 2.001，2020-7-4，Monotype，-ccmp dist half kern mark mkmk pref pres psts ss01～ss04。
1. NotoSansSignWriting-Regular 2.001，2020-12-25，Monotype，-calt ccmp mark mkmk。
1. NotoSansSinhala-Regular 2.001，2020-9-18，Monotype，-abvs akhn blwm blws dist dlig pres pstf psts rphf vatu。
1. NotoSansSogdian-Regular 2.000，2020-7-4，Monotype，-aalt calt fina init mark medi salt ss01～ss15 ss20～ss23。
1. NotoSansSoyombo-Regular 2.000，2020-7-4，Monotype，-ccmp dist half mark mkmk pref psts。
1. NotoSansSundanese-Regular 2.001，2020-7-4，Monotype，-ccmp mark mkmk。
1. NotoSansSylotiNagri-Regular 2.000，2020-9-18，Monotype，-ccmp dlig mark mkmk。字体的U+2055是特别设计的。
1. NotoSansSymbols-Regular 2.001，2020-7-4，Monotype，-ccmp。与Segoe UI…重复的区段没有添加。
1. NotoSansSymbols2-Regular 2.003，2020-12-25，Monotype，-ccmp mark mkmk。与Segoe UI…重复的区段没有添加。
1. NotoSansSyriac-Regular 2.000，2020-9-18，Monotype，-aalt calt ccmp fin2 fin3 fina init kern locl mark med2 medi mkmk rlig salt ss01～ss03 stch。U+2670 U+2671 U+0700-U+074F有但未用
1. NotoSansTagalog-Regular 2.000，2020-7-10，Monotype，-mark。
1. NotoSansTagbanwa-Regular 2.000，2020-7-4，Monotype。
1. NotoSansTaiTham-Regular 2.001，2020-7-4，Monotype，-ccmp liga mark。
1. NotoSansTaiViet-Regular 2.000，2020-7-4，Monotype，-mark。
1. NotoSansTakri-Regular 2.002，2020-7-4，Monotype，-abvs akhn blwf dist kern mark mkmk pstf。
1. NotoSansTamilSupplement-Regular 1.001\1.002，2020-7-5，Ek Type。
1. NotoSansTirhuta-Regular 2.001，2020-7-4，Monotype，-abvf abvs blwf blws dist kern mark mkmk pstf rphf ss01～ss03。
1. NotoSansWancho-Regular 2.000，2020-7-4，Monotype，-kern locl mark。
1. NotoSansWarangCiti-Regular 3.000，2020-7-4，Mangu Purty，-ccmp kern mark。
1. NotoSansZanabazarSquare-Regular 2.002，2020-7-4，Monotype，-ccmp kern mark mkmk rclt ss01。
1. NotoSerifAhom-Regular 2.003，2020-7-5，Monotype，-ccmp dist kern mark mkmk rlig salt。这行及以下字体没有Sans。
1. NotoSerifBalinese-Regular 2.000，2020-7-4，Monotype，-blwf ccmp dist liga mark mkmk。
1. NotoSerifDogra-Regular 1.002，2020-7-4，Ek Type，-aalt calt dist kern mark ss01～ss03。
1. NotoSerifNyiakengPuachueHmong-Regular 1.000，2020-7-4，Dalton Maag Ltd，-kern mark。
1. NotoSerifTibetan-Regular 2.001，2021-10-5，Monotype，-abvs blws calt ccmp kern mark mkmk。
1. NotoSerifYezidi-Regular 1.000，2020-10-27，Dalton Maag Ltd，-kern mark。
1. Arimo-Regular 1.330，2020-8-5，对Arial的兼容字体，虽在Noto家族无Noto之名，-ccmp dlig kern locl mark mkmk。

1. [CtrlRunr][r] β6，2021-8-31，綿雲飴里，-aalt ccmp kern mark。
1. KhitanSmallLinear 13.001，2020-4-5，景永时／BabelStone，-ccmp。

</details>

## 撤销：截至第五版
1. ~NotoSerifTangut-Regular 2.001，2020-7-4=2020-9-18，Monotype。6890+字太多仅用1字U+16FE0。~ 一个字索性自己画了，而且Serif画风也与同区段其它字不符。
1. ~BabelStone Han 13.0.8，2020-7-19，BabelStone，-calt ccmp。仅部分新字符。~ 被Noto Sans Symbols2 2.003替代。
1. ~BabelStoneShapes 13.0.1，2020-7-6，BabelStone，-ccmp。~ 被Noto Sans Symbols2 2.003替代。
1. ~NotoSansRunic-Regular 2.000，2020-7-4，Monotype。~ 丑，被我的自制字体[Ctrl Runr][r]替代。

[r]: https://github.com/MY1L/Ctrl#runr