# 补字笔记
下列区段字数统计截至统一码15.1版，选择这些区段的缘由见 [FontList](/FontList) 的分析。

## 参考
偏旁部首 见 等值汉字：[EquivalentUnifiedIdeograph-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/EquivalentUnifiedIdeograph.txt)

兼容汉字 见 标准变体：[StandardizedVariants-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/StandardizedVariants.txt)

也可翻阅 [USourceData-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/USourceData.txt)，文件内容互有交叉。

## BMP,SMP,PUAA
### Hani
用于覆盖 BMP、SMP平面`Hani` `Bopo` `Hira` `Kana`字符。[支持一些别致的排版特性](https://github.com/MY1L/Unicode/releases/tag/Hani9)，且 SIP、TIP、私用区 均有若干备用字形。目前为3次曲线（.otf）版本。SMP平面 除了支持全部小型假名，还有少量算筹。
- 2023-2-22\~-11-22 调整水平布局度量，与 Ctrl Kana 1.001 同步。
- 2023-11-22 v9.6：全局质检发现思源黑2.004版至少有13+24+13137个字形存在问题，修正之。

#### BMP
- 2E80..CJK Radicals Supplement　 　 　　	；思源黑(115∕115字)
  - 2023-11-24 v9.6：为了区分思源黑混淆的`⺫`(≈罒)、`⺲`(≈𦉰)，[将后者改为封闭𦉰形](https://www.unicode.org/charts/PDF/U2E80.pdf "2EB2")。
- 2F00..Kangxi Radicals　 　 　 　　　　　	；思源黑(214∕214字，没用上)
  - 2023-11-23 v9.6：为了与汉字区分，暂从 思源宋 Medium 取来符合康熙字典体的字形，准备之后重做一份“康熙黑体”。｢⽞｣字不避讳。
    - 许多人觉得思源宋韩标即康熙字典体，但至少｢⼎⼜⼪⼬⽂⽆⽎⽓⽗⽠⽰⽳⽻⾆⾑⾗⾣⾱⾳⾵⾷⿆⿇⿌⿍⿐⿓⿔｣不是。
    - 我还编辑了｢⼇⼧⽙｣等字形，[左边和上面提及的一些字形为我自制](https://github.com/ichitenfont/I.Ming/issues/111)，思源宋里不存在的。<!-- ｢⽛⽿⽨⽡⾲｣可能还要调整。 -->
- 2FF0..Ideographic Description Characters	；思源黑(12∕16字，没用上)
  - 2023-1-31：全部16个原创字形，包括[统一码15.1版用的] ⿼⿽⿾⿿`u2FFC~2FFF`(自[CtrlCtrl]1.1)
    - 内外不对称的旋转箭头`↷`是我考虑视觉效果专门绘制的。感觉原`↔`或引发误解，改为较明确的“左边到右、右边到左”左右翻转箭头`⇌`
    - 从而支持反思特性：⿿思
  - 2023-11-25 v9.6：⿿的箭头旋转90°(自[CtrlCtrl]1.2)
- 3000..CJK Symbols and Punctuation 　 　	；思源黑(64∕64字)
  - 2023-11-24 v9.6：参照[苏码字形修改提案](https://www.unicode.org/L2/L2023/23227-suzhou-nine-feedback.pdf)，改变了｢〢〥〦〧〨〩｣、自制了各种东亚标点和〾(自[CtrlCtrl]1.2)
- 3100..Bopomofo　 　 　　　　　　	　　	；思源黑(43∕43字)
- 31A0..Bopomofo Extended　　　　	　　	；思源黑(28∕32字)
  - 思源缺的｢ㆼㆽㆾㆿ｣移自我补的 [Noto Unicode](/NotoUnicode) 2.03
- 31C0..CJK Strokes　 　　　　　　　　　	；思源黑(36∕37字)
  - 2023-2-18 v9.5：新增[统一码15.1版用的] ㇯`u31EF`(自[CtrlCtrl]1.11)
  - 2023-11-24 v9.6：参照[㇒`u31D2`字形修改提案](https://www.unicode.org/L2/L2023/23221-update-cjk-stroke-p.pdf)，改变了撇笔。
- 3200..Enclosed CJK Letters and Months　	；思源黑(255∕255字)
- 3400..CJK Unified Ideographs Extension A	；思源黑(6582∕6592字)
  - 2023-1-29 v9：补充思源没有的｢䶶䶷䶸䶹䶺䶻䶼䶽䶾䶿｣
- 4E00..CJK Unified Ideographs　 　　　　	；思源黑(20976∕20992字)
  - 2023-1-29 v9：补充思源没有的｢鿰鿱鿲鿳鿴鿵鿶鿷鿸鿹鿺鿻鿼鿽鿾鿿｣
  - 2023-2-3~14 v9.3\~5：微调｢鿾鿿｣
- F900..CJK Compatibility Ideographs 　 　	；思源黑(366∕472字)
  - 2023-1-29 v9：补充思源没有的｢𢡊𢡄𣏕𥉉𥳐𧻓｣
  - 2023-1-30：微调 喝`uFA36`
  - 2023-1-31：硬是补完了思源和遍黑都没有的`uFA70~FAD9`内剩余的100个字！
  - 2023-11-25 v9.6：[重新检查兼容汉字映射](https://www.unicode.org/charts/PDF/UF900.pdf "F900汉字兼容表意")，如｢䀹䀹鿃䀹｣……对128多个与汉字同形的兼容字如｢樂樂樂樂｣附标小🅒以便区分。
    - 已知问题：｢塚憎贈響 華齃龎龜𣏕 並侀瘝摒｣等字形局部不符，｢懲練難頻 况望歹窱｣等字形稍差一笔，以后重绘。
    - 问题大多出在朝鲜兼容字，已经做了若干。尚有对应这些汉字——\
｢啕喙墳奄奔婢嬨廙彩徭惘戴杖滛滋瀞瞧爵犯瑱甆盛睊絛缾荒諭變輸遲鉶頋｣\
——的下列兼容字未处理，仅附标小🅒：\
｢啕喙墳奄奔婢嬨廙彩徭惘戴杖滛滋瀞瞧爵犯瑱甆盛睊絛缾荒諭變輸遲鉶頋｣

#### SMP,SIP
- 1AFF0..Kana Extended-B　　　　　	　　	；思源黑(0∕13字)
  - 2023-2-18 v9.5：原创以补全｢𚿰𚿱𚿲𚿳𚿵𚿶𚿷𚿸𚿹𚿺𚿻𚿽𚿾｣
  - 2023-11-25 v9.6：微调几个字(自[CtrlKana](https://github.com/MY1L/Ctrl/releases/tag/Kana)1.1)
- 1B000..Kana Supplement　 　 　 　	　　	；思源黑(0∕256字)\
1B100..Kana Extended-A　 　 　 　	　　	；思源黑(0∕35字)
  - 有，但欠很多字，见下。
- 1B130..Small Kana Extension　 　　　　	；思源黑(0∕9字)
  - 2023-2-3~14 v9.3\~5：添加我以前给Monu 12补画的假名：`u1AFFB` `u1B000` `u1B001` `u1B108` `u1B11F` `u1B120` `u1B121` `u1B122` ~`u2A708` `u2CF00`~、\
`u1B130` `u1B131` `u1B132` `u1B133` `u1B134` `u1B135` `u1B136` `u1B137` `u1B138` `u1B139` `u1B13A` `u1B13B` `u1B13C` `u1B13D` `u1B13E` `u1B13F` `u1B140` `u1B141` `u1B142` `u1B143` `u1B144` `u1B145` `u1B146` `u1B147` `u1B148` `u1B149` `u1B14A` `u1B14B` `u1B14C` `u1B14D` `u1B14E` `u1B14F` `u1B150` `u1B151` `u1B152` `u1B153` `u1B154` `u1B155` `u1B156` `u1B157` `u1B158` `u1B159` `u1B15A` `u1B15B` `u1B15C` `u1B15D` `u1B15E` `u1B15F` `u1B160` `u1B161` `u1B162` `u1B163` `u1B164` `u1B165` `u1B166` `u1B167`——即除了｢𛄲𛅐𛅑𛅒𛅕𛅤𛅥𛅦𛅧｣，把未来（如有）的小型假名也填了，它们全都不是由对应“大型”假名缩小而来的，那样字重会变细。

**注意**2个 SIP 汉字｢𪜈𬼀(不是ソ)｣，其实是合略仮名｢ゟ(より) ヿ(コト) 𪜈(トモ) 𬼀(シテ)｣后2个 ~，所以[它们都是比例宽度](https://www.bilibili.com/read/cv5457108)~。

- 1F200..Enclosed Ideographic Supplement	；思源黑(58∕64字)
  - v9.6：思源缺的6字移自我补的 [Noto Unicode](/NotoUnicode)

- **SIP** 的其它汉字：
  - 2023-11-7：自制或修改｢𠆭𠪳𢀓𬻷𬻿𬼂𭅃𭍻𭑊𭚥𭤪𭥟𮓠𮥹𮷌｣
  - 2023-11-10~22：试作｢𠇇𭁇｣，微调｢𠆭𠪳𭤪𭥟｣，附源文件 [MonuHan<ruby><rb>S.otf</rb><rt>Src＼kStrange＼…</rt></ruby>](MonuHanS.otf)，添加思源的 SIP 汉字
  - 2023-11-23 v9.6：自制思源黑风格的全角合略仮名｢𪜈𬼀｣，更新源文件

[统一码15.1版用的]: https://www.unicode.org/L2/L2022/22191-five-new-idc-chars.pdf
[CtrlCtrl]: https://github.com/MY1L/Ctrl/releases/tag/Ctr1
#### TIP
- 2023-1-29 v9
  - 添加 𱝫`u3176B`
  - 修正8.1版 U+3205D → 𲁓`u32053`
- 2023-11-22 v9.6
  - 添加思源的4个扩庚汉字
#### E000..私用区
v9 之前的私用字形｢<!--  -->｣介绍暂略，不妨查阅[之前每版发布的说明图文](/Hani#更新)。
- 2023-1-29 v9
  - B站特色示亡号支持，暂放在私用区，码位不保证永久：示亡号开 `uE000`、示亡号闭 `uE00F`（虽不支持三字名，不表示OT特性做不到）
- 2023-2-1 v9.2
  - 添加若干某类人本来只能用图片表达的字形：`uE01C`、`uE01D`
  - 港漫拟声词：呱！吔！㗅！咈！𠹳(⿰口桀)！𰇛(⿰口伏)统一码都有的，但目前缺一个“熊熊大火”的⿰口熊，暂放 `uE01E`
- 2023-2-3~14 v9.3\~5
  - 微调 `uE01D`、`uE01E`
  - 添加“只因”合字 `uE01F`及相关特性：为避免随便合字引发误解使用的严格匹配，必须完整的“只因你太美”才会合字。
- 2023-11-7\~22 v9.6
  - 添加[儿化用的小<sub>儿</sub>字](https://www.zhihu.com/question/28466594 "eisoch曾提案过") `uE07F`，支持下标`subs`特性
  - 删除2个没人用的废稿[钅鸡](https://github.com/MY1L/Unicode/releases/tag/v6.21 "v7.27")：`uE007``uE008`，仅保留1个[如图](https://github.com/MY1L/Unicode/releases/tag/v6.2 "v7.1")
  - 从 私用区增乙 移来：元 `uE080`、甲 `uE081`、冎|骨 `uE082`、篆 `uE083`
  - 从 SMP平面 移来：减字谱⿸十一 `uE007`<sub>(废稿码位回收)</sub>
  - 示亡号微调

#### F0000..私用区增甲
2023-1-29 v9
- 没别的意思，单纯觉得网上那些`xdi8.aho`拼字都……有点儿业余。按 UCSUR 2022-6-5版，发配到 󱰰`uF1C30`
#### ~100000..私用区增乙~
- 2023-1-29 v9
  - 为避让 BMP平面 汉字，将8.1版存在的一些古文迁到 私用区增乙，与 [典迹末境8版](https://github.com/MY1L/Unicode/releases/tag/Last8) 重复的字形删除，具体如下：
    - ~迁至：元􏾇`u10FF87`、冎|骨􏾈`u10FF88`、甲􏾉`u10FF89`、篆􏾊`u10FF8A`~
    - 删除：㣇|彖、契、文、楚、越、鼎
- 2023-11-7 v9.6：此处字形为避让 典迹末境8.x版、典迹无印12.x版，移到`E080..E08F`区间。

#### 加了特技
##### `calt` 语境替换
① 合字`只因你太美`严格匹配，见上文。

② 作为工具字体，可以对b站 [三体 (艺画开天) _ 国创](https://www.bilibili.com/bangumi/media/md4315402/) 页面上特有示亡号`总策划：【林奇】`作处理，详见 [尝试解决B站不显示【示亡号】的问题 - 哔哩哔哩](https://www.bilibili.com/read/cv21481556)

编写 OpenType`calt`特性，伪代码如下（.fea语法）……嘛，反正这是开源的，直接打开字体抄就行了。
```
lookup 示殁 { # GSUB lookup type 单字替换
    sub 【 by MIDo; # 示亡号开
    sub 】 by MIDc; # 示亡号闭
} 示殁;

lookup calt { # GSUB lookup type 上下文替换
    sub 【' lookup 示殁 林 奇 】;
    sub MIDo 林 奇 】' lookup 示殁;
} calt;
```

字体安装后可使用如下样式调用：
```CSS
@-moz-document url-prefix("https://www.bilibili.com/bangumi/media/md4315402/") {
* {
font-family:"随便一个不含汉字的字体",Monu Hani,Microsoft YaHei UI,Monu Last,sans-serif!important
	}
}
```

实际浏览器渲染如图（b站审核认为此图不适宜）\
![【林奇】](https://user-images.githubusercontent.com/58043328/215335730-ad4dcf43-aa94-463d-9ff2-94597240ef3f.png)<br/>
不用说我这字体肯定还有点彩蛋的。

##### `ccmp` 字形重组
一般可自动将`⿸十一`呈现为减字谱“⿸十一”、`⿰月宅`呈现为“⿰月宅”、`⿰口熊`呈现为拟声词“⿰口熊”、`⿿思`呈现为反思、`⿰火鸡`呈现为“⿰火鸡”、`⿱鸡灬`呈现为“⿱鸡灬”、`⿱鸡火`呈现为“⿱鸡火”，以及合字`⿻辶福`

##### `dlig` 自选连字
与`ccmp`不同在必须手动开启。开启后，`令和`呈现为“㋿”(思源自带)、`钅鸡`呈现为“⿰钅鸡”、`火鸡`呈现为“⿰火鸡”、`只因`强制呈现为“⿰只因”\
也支持[这些合字](https://github.com/MY1L/Unicode/releases/tag/Hani8)：`不想` `工作` `苦苦苦苦` `五福临门` `共合` `八大山人` `感恩` `纟火`

##### `hist` 历史形式
须手动开启。开启后，`甲`、`冎`\\`骨`会转为甲骨字形，`篆`会转为小篆字形。

##### `salt` 风格替换
须手动开启。开启后，`元`会转为假设的人民币符号｢π̅｣

##### `subs` 下标字形
可将`<sub>儿</sub>`转为儿化专用的小<sub>儿</sub>字，避免文字作下标缩小导致笔画变细。

## SIP,TIP
为防止转换格式有损曲线——3次转2次必然有损，2转3则可能有重叠问题，源自遍黑体的部分只有ttf版本。

### Han2
覆盖 SIP平面 用。目前为ttf格式，因为工作量，可能不会制作otf版。当前与 遍黑体P1 对齐，裁剪非汉字的区段。所有宋体字形是遍黑体就有的（咦）

- v4.393，2023-1-27：与遍黑体P1 4.393版对齐，`.notdef`字形略挤，微调。理论总字数60873，实际因为某些兼容字或偏旁部首的字形完全一致(173个多重映射)，合并至60831个字形+1个`.notdef`
- v6.399，2023-11-5：跟进统一码15.1版，共61473个字形(166个多重映射)。\
基于 遍黑P1 6.398版，修正 遍黑P1 至少47+4186个字形。\
自制或修改了｢𠆭𠪳𢀓𬻷𬻿𬼂𭅃𭍻𭑊𭚥𭤪𭥟𮓠𮥹𮧵𮷌｣，附源文件 [MonuHanS.otf](MonuHanS.otf)，调整水平布局度量，对32个<!-- 共计170个 -->兼容字附标小🅒以便区分，又见 [统一码C类奇葩汉字绘制 - 哔哩哔哩](https://www.bilibili.com/read/cv27511908)

### Han3
覆盖 TIP平面 用。目前为ttf格式，同上，可能不会制作otf版。当前与 遍黑体P2 1.175版对齐，裁剪非汉字的区段。共计9131个字形+1个`.notdef`，有4个字形与其它区段重复。

- v1.175，2023-1-27：`.notdef`字形…(同上)