# Noto Unicode 2.003
这是个工具字体，意思是**不负责排版**仅负责显示，类似于字体「Unifont」

制作该字体的急迫性在我用一般软件如BabelMap时，点字体菜单总是因为[Noto Fonts](https://github.com/notofonts)装得太多影响到选取。

![Noto太多了](/NotoUnicode/Notoomany.png)

而装这些我不了解的文字的字体，也只是为了BabelMap和浏览器显示不缺字，实际上我并不迫切地需要正确地排版这么多语言文字，只要看得见字就行，如果以后遇到需要正确排版的情况可以单独安装。

于是我先将70+个字体合并为一：「Noto Unicode」，删除所有OT特性和不在统一码表里的字符（合字、异体等等），由此体积压缩了一半。针对BabelMap每个区段只能用一个字体的设定，画了些Noto缺的字符把整个区段填满。如果系统默认字体已经存在能填满某区段的就不加，避免字体过大或装不下，因字体包含单字上限65535——毕竟看到这的人肯定需要对东亚文字排版，要另装思源系列。Noto Unicode支持的统一码区段列表太长这儿放不下，记录在sysBlocks.txt。

没有做完，只是尽量覆盖罕用和一般人不太在乎排版的SMP区域。BMP区域下次更新。

## 更新
2.003 第一版，初次发布，总字数11270+

2.2.003 第二版，覆盖BMP区域，总字数15948+，因No tofu字体缺字而自画了些字符补全，自制了个“tofu（豆腐）”字符用于缺字提示。追加的Noto字体列表以后再写，当前sysBlocks.txt未更新。
- 按 www.unicode.org/charts/PDF/U0D80.pdf 画了U+0D81补全该区。
- 按 www.unicode.org/charts/PDF/U11180.pdf 画了U+111CE、U+111CF补全该区。
- 按 www.unicode.org/charts/PDF/U11400.pdf 画了U+1145A、U+11460、U+11461补全该区。
- 按 www.unicode.org/charts/PDF/U16FE0.pdf 造了整个区！

## 涵盖
以下为该个字体（2.003版）缝合的Noto字体列表：

> 下列依次是：文件名 版本，GitHub更新日期，厂商或作者，-损失的OT特性。
> - 如果厂商或作者后面直接是句号，表示没有损失任何特性，原字体就是光秃秃的。
> - 版本后面跟着「\」的表示大概是写错的版本。
> - 有些Monotype与他人合作的字体也记作Monotype。
> - 「Segoe UI…」指Segoe UI、Segoe UI Symbol和Segoe UI Historic。

1. NotoSans-Regular 2.003，2020-7-6，Monotype，-aalt c2sc case ccmp dnom frac kern liga lnum locl mark mkmk numr onum ordn pnum rtlm salt smcp ss03~ss04 subs sups tnum zero。
1. NotoMusic-Regular 2.000，2020-7-4，Monotype，-ccmp curs kern mark mkmk。与Segoe UI…重复的区块没有添加。
1. NotoSansArabic-Regular 2.500，2020-8-14，Mohamad Dakak，-aalt ccmp dlig fina init isol kern liga locl mark medi mkmk rlig。
1. NotoSansArmenian-Regular 2.005，2020-7-5，Monotype，-kern liga mark。
1. NotoSansBassaVah-Regular 2.000，2020-7-4，Monotype，-ccmp kern mark。
1. NotoSansBengali-Regular 2.001，2020-7-5，Monotype，-abvm abvs akhn blwf blwm blws cjct dist half init kern nukt pres pstf psts rphf vatu。
1. NotoSansBhaiksuki-Regular 2.001，2020-7-4，Monotype，-abvs ccmp dist kern mark mkmk rlig rphf ss01。
1. NotoSansCaucasianAlbanian-Regular 2.001，2020-7-4，Monotype，-ccmp kern mark mkmk。
1. NotoSansCoptic-Regular 2.000，2020-7-4，Monotype，-ccmp mark mkmk。U+2C80-U+2CFF有但未用。
1. NotoSansDevanagari-Regular 2.001，2020-7-5，Monotype，-abvm abvs akhn blwf blwm blws cjct dist half haln locl nukt pres psts rkrf rphf vatu。
1. NotoSansDuployan-Regular 2.000，2020-7-4，Monotype。
1. NotoSansElbasan-Regular 2.000，2020-7-4，Monotype，-ccmp mark。
1. NotoSansElymaic-Italic 1.000，2020-7-4，Morgane Pierson，-aalt dlig kern salt ss01~ss03。这个字体没有Regular。
1. NotoSansGeorgian-Regular 2.001，2020-7-4，Monotype，-aalt case ccmp kern mark mkmk。
1. NotoSansGrantha-Regular 2.001，2020-7-4，Monotype，-abvs blwf blws calt cjct dist haln kern mark mkmk pstf psts rlig rphf ss01~ss10。
1. NotoSansGujarati-Regular 2.001，2020-7-5，Monotype，-abvm abvs akhn blwf blwm blws cjct dist half haln nukt pres psts rkrf rphf vatu。
1. NotoSansGunjalaGondi-Regular 1.001，2020-7-4，Ek Type，-calt dist kern mark mkmk ss01 ss02。
1. NotoSansGurmukhi-Regular 2.001，2020-7-5，Monotype，-abvm abvs blwf blwm blws calt dist half haln nukt pstf。
1. NotoSansHanifiRohingya-Regular 2.100，2020-7-4，Monotype，-fina init kern mark medi mkmk ss01 ss02。
1. NotoSansHanunoo-Regular 2.000，2020-7-4，Monotype，-ccmp mark salt。
1. NotoSansHatran-Regular 2.000，2020-7-4，Monotype。
1. NotoSansHebrew-Regular 3.000，2020-7-4，Ben Nathan，-ccmp dlig kern mark。
1. NotoSansIndicSiyaqNumbers 2.000，2020-7-4，Monotype，-curs ss01。
1. NotoSansKayahLi-Regular 2.001，2020-7-4，Monotype，-aalt ccmp mark。
1. NotoSansKhojki-Regular 2.001，2020-7-4，Monotype，-blws ccmp dist kern mark mkmk psts salt。
1. NotoSansKhudawadi-Regular 2.000，2020-7-4，Monotype，-abvf abvs dist mark mkmk。
1. NotoSansLinearA-Regular 2.000，2020-7-4，Monotype。
1. NotoSansLinearB-Regular 2.001，2020-7-4，Monotype。
1. NotoSansMahajani-Regular 2.000，2020-7-4，Monotype，-mark。
1. NotoSansManichaean-Regular 2.000，2020-7-4，Monotype，-ccmp fina init mark medi rclt。
1. NotoSansMarchen-Regular 2.001\3.000，2020-7-4，Monotype，-abvs calt mark mkmk pres。
1. NotoSansMasaramGondi-Regular 1.002，2020-7-4，Ek Type，-calt dist kern mark ss01 ss02。
1. NotoSansMayanNumerals-Regular 2.000，2020-7-4，Monotype。
1. NotoSansMendeKikakui-Regular 2.000，2020-7-4，Monotype，-ccmp kern mark。
1. NotoSansMeroitic-Regular 2.000，2020-7-4，Monotype，-ccmp dist。
1. NotoSansMiao-Regular 2.001，2020-7-4，Monotype，-ccmp kern mark mkmk。
1. NotoSansMongolian-Regular 2.001，2020-7-4，Monotype，-fina init isol medi rlig vert vrt2。与Segoe UI…重复的U+2460-U+2473没有添加。
1. NotoSansMro-Regular 2.000，2020-7-4，Monotype。
1. NotoSansMultani-Regular 2.000，2020-7-4，Monotype。
1. NotoSansNabataean-Regular 2.000，2020-7-4，Monotype。
1. NotoSansNewa-Regular 2.002，2020-7-4，Monotype，-abvs akhn blws calt ccmp curs dist half kern mark mkmk pref rphf。
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
1. NotoSansRunic-Regular 2.000，2020-7-4，Monotype。
1. NotoSansSharada-Regular 2.001，2020-7-4，Monotype，-abvs akhn blws dist mark mkmk。
1. NotoSansSiddham-Regular 2.001，2020-7-4，Monotype，-ccmp dist half kern mark mkmk pref pres psts ss01~ss04。
1. NotoSansSogdian-Regular 2.000，2020-7-4，Monotype，-aalt calt fina init mark medi salt ss01～ss15 ss20~ss23。
1. NotoSansSoyombo-Regular 2.000，2020-7-4，Monotype，-ccmp dist half mark mkmk pref psts。
1. NotoSansSundanese-Regular 2.001，2020-7-4，Monotype，-ccmp mark mkmk。
1. NotoSansSymbols2-Regular 2.002，2020-7-4，Monotype，-ccmp mark mkmk。与Segoe UI…重复的区块没有添加。
1. NotoSansSymbols-Regular 2.001，2020-7-4，Monotype，-ccmp。与Segoe UI…重复的区块没有添加。
1. NotoSansSyriac-Regular 2.000，2020-7-4，Monotype，-aalt calt ccmp fin2 fin3 fina init kern locl mark med2 medi mkmk rlig salt ss01~ss03 stch。U+2670 U+2671 U+0700-U+074F有但未用。
1. NotoSansTagalog-Regular 2.000，2020-7-10，Monotype，-mark。
1. NotoSansTakri-Regular 2.002，2020-7-4，Monotype，-abvs akhn blwf dist kern mark mkmk pstf。
1. NotoSansTamilSupplement-Regular 1.001\1.002，2020-7-5，Ek Type。
1. NotoSansTirhuta-Regular 2.001，2020-7-4，Monotype，-abvf abvs blwf blws dist kern mark mkmk pstf rphf ss01~ss03。
1. NotoSansWancho-Regular 2.000，2020-7-4，Monotype，-kern locl mark。
1. NotoSansWarangCiti-Regular 3.000，2020-7-4，Mangu Purty，-ccmp kern mark。
1. NotoSansZanabazarSquare-Regular 2.002，2020-7-4，Monotype，-ccmp kern mark mkmk rclt ss01。
1. NotoSerifAhom-Regular 2.003，2020-7-5，Monotype，-ccmp dist kern mark mkmk rlig salt。这行及以下字体没有Sans。
1. NotoSerifDogra-Regular 1.002，2020-7-4，Ek Type，-aalt calt dist kern mark ss01~ss03。
1. NotoSerifNyiakengPuachueHmong-Regular 1.000，2020-7-4，Dalton Maag Ltd，-kern mark。
1. Arimo-Regular 1.330，2020-8-5，对Arial的兼容字体，虽在Noto家族无Noto之名，-ccmp dlig kern locl mark mkmk。

1. KhitanSmallLinear 13.001，2020-4-5，景永时／BabelStone，-ccmp。
1. BabelStone Han 13.0.8，2020-7-19，BabelStone，-calt ccmp。仅使用部分字符填空。
1. BabelStoneShapes 13.0.1，2020-7-6，BabelStone，-ccmp。

## 撤销
1. ~NotoSerifTangut-Regular 2.001，2020-7-4，Monotype。6890+字太多，仅用1字U+16FE0。~ 一个字我干脆自己画了，而且Serif画风也与其它字不符。