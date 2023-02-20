# 我的补字笔记
下列区段截至统一码15.0版均完全覆盖，选择这些区段的缘由见[FontList](/FontList)的分析。

## 参考
偏旁部首 见 等值汉字：[EquivalentUnifiedIdeograph-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/EquivalentUnifiedIdeograph.txt)

兼容汉字 见 标准变体：[StandardizedVariants-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/StandardizedVariants.txt)

也可以翻翻 [USourceData-15.0.0.txt](https://www.unicode.org/Public/15.0.0/ucd/USourceData.txt) 文件内容互有交叉。

## BMP,SMP,PUA*
### Hani v9.5
用于覆盖BMP、SMP平面`Hani` `Bopo` `Hira` `Kana`字符。[支持一些别致的排版特性](https://github.com/MY1L/Unicode/releases/tag/Hani9)，且SIP、TIP、三个私用区均有若干备用字形。目前为3次曲线（.otf）版本。SMP平面除了支持全部小型假名，还有少量算筹、减字谱。
对照的思源黑体为2.004版。

#### BMP
- 2FF0..Ideographic Description Characters	；思源黑(12／12字，没用上)
  - 2023-1-31：全部16个原创字形，包括[未来可能用到的][idc5] ⿼⿽⿾⿿`u2FFC~2FFF`（自[CtrlCtrl]1.1）
    - 内外不对称的旋转箭头`↷`是我考虑视觉效果专门绘制的。感觉原`↔`或引发误解，改为较明确的“左边到右、右边到左”左右翻转箭头`⇌`
    - 从而支持反思特性：⿿思
- 3100..Bopomofo　　	　　	　	　	；思源黑(43／43字)
- 31A0..Bopomofo Extended	　	　	；思源黑(32／28字)
  - 思源缺的 ㆼㆽㆾㆿ 来自我补的 [Noto Unicode](/NotoUnicode) 2.03
- 31C0..CJK Strokes　	　　	　	　	；思源黑(36／36字)
  - 2023-2-18 v9.5：新增并包含[未来可能用到的][idc5] ㇯`u31EF`（自[CtrlCtrl]1.11）
- 3400..CJK Unified Ideographs Extension A	；思源黑(6592／6582字)
  - 2023-1-29 v9：补充思源没有的 䶶䶷䶸䶹䶺䶻䶼䶽䶾䶿
- 4E00..CJK Unified Ideographs	　	　	；思源黑(20992／20976字)
  - 2023-1-29 v9：补充思源没有的 鿰鿱鿲鿳鿴鿵鿶鿷鿸鿹鿺鿻鿼鿽鿾鿿
  - 2023-2-3~14：微调 鿾`u9FFE`、鿿`u9FFF`
- F900..CJK Compatibility Ideographs		；思源黑(472／366字)
  - 2023-1-29 v9：补充思源没有的 𢡊𢡄𣏕𥉉𥳐𧻓
  - 2023-1-30：微调 喝`uFA36`
  - 2023-1-31：硬是补完了思源和遍黑都没有的`uFA70~FAD9`内剩余的100个字！
    - 其中有这么些尚需检查的奇怪映射（不完全列举）
<details><summary>——点此展开\折叠——</summary>

- 喝喝喝
- 塚塚塚
- 憎憎憎
- 懲懲懲
- 晴(狀)晴晴
- 朗朗朗
- 樂樂樂樂
- 殺殺殺
- 流流流
- 漢漢漢
- 煮煮煮
- 猪猪猪
- 率率率
- 益益益
- 節節節
- 練練練練
- 者者者
- 視視視
- 說說說
- 諸諸諸
- 諾諾諾
- 謁謁謁
- 謹謹謹
- 贈贈贈
- 路(虜)路
- 難難難
- 靖靖靖
- 響響響
- 頻頻頻
- 鷺(濫)鷺
- 龜龜龜
- 䀹䀹䀹

</details>

#### SMP,SIP
- 1AFF0..Kana Extended-B	；思源黑(13／0字)
  - 2023-2-18 v9.5：原创以补全：𚿰𚿱𚿲𚿳𚿵𚿶𚿷𚿸𚿹𚿺𚿻𚿽𚿾
- 1B000..Kana Supplement	；思源黑(256／0字)
  - 有，但欠很多字，见下。
- 1B100..Kana Extended-A	；思源黑(35／0字)
  - 有，但欠很多字，见下。
- 1B130..Small Kana Extension	；思源黑(9／0字)
  - 2023-2-3~14：添加我以前给Monu 12补画的假名：`u1AFFB` `u1B000` `u1B001` `u1B108` `u1B11F` `u1B120` `u1B121` `u1B122` `u2A708` `u2CF00`、\
`u1B130` `u1B131` `u1B132` `u1B133` `u1B134` `u1B135` `u1B136` `u1B137` `u1B138` `u1B139` `u1B13A` `u1B13B` `u1B13C` `u1B13D` `u1B13E` `u1B13F` `u1B140` `u1B141` `u1B142` `u1B143` `u1B144` `u1B145` `u1B146` `u1B147` `u1B148` `u1B149` `u1B14A` `u1B14B` `u1B14C` `u1B14D` `u1B14E` `u1B14F` `u1B150` `u1B151` `u1B152` `u1B153` `u1B154` `u1B155` `u1B156` `u1B157` `u1B158` `u1B159` `u1B15A` `u1B15B` `u1B15C` `u1B15D` `u1B15E` `u1B15F` `u1B160` `u1B161` `u1B162` `u1B163` `u1B164` `u1B165` `u1B166` `u1B167`——即除了 𛄲𛅐𛅑𛅒𛅕𛅤𛅥𛅦𛅧，把未来（如有）的小型假名也填了，它们全都不是由对应“大型”假名缩小而来的，那样字重会变细。其中2个SIP汉字 𪜈𬼀，其实是合略仮名“ゟ(より) ヿ(コト) 𪜈(トモ) 𬼀(シテ)”后2个，所以[它们都是比例宽度](https://www.bilibili.com/read/cv5457108)。

[idc5]: https://www.unicode.org/L2/L2022/22191-five-new-idc-chars.pdf
[CtrlCtrl]: https://github.com/MY1L/Ctrl/releases/tag/Ctr1
#### TIP
- 2023-1-29 v9
  - 添加 𱝫`u3176B`
  - 修正8.1版 U+3205D → 𲁓`u32053`
#### E000..私用区
v9 之前的私用字形暂略，不妨查阅[之前每版发布的说明图文](/Hani#更新)。
- 2023-1-29 v9
  - B站特色示亡号支持，暂放在私用区，码位不保证永久：示亡号开`uE000`、示亡号闭`uE00F`（虽不支持三字名，不表示OT特性做不到）
- 2023-2-1 v9.2
  - 添加若干某类人本来只能用图片表达的字形：`uE01C`、`uE01D`
  - 港漫拟声词：呱！吔！㗅！咈！𠹳(⿰口桀)！𰇛(⿰口伏)统一码都有的，但目前缺一个“熊熊大火”的⿰口熊，暂放 `uE01E`
- 2023-2-3~14
  - 微调 `uE01D`、`uE01E`
  - 添加“只因”合字 `uE01F`及相关特性：为避免随便合字引发误解使用的严格匹配，必须完整的“只因你太美”才会合字。
#### F0000..私用区增甲
2023-1-29 v9
- 没别的意思，单纯觉得网上那些`xdi8.aho`拼字都……有点儿业余。按 UCSUR 2022-6-5版，发配到 󱰰`uF1C30`
#### 100000..私用区增乙
2023-1-29 v9
- 为避让BMP平面汉字，将8.1版存在的一些古文迁到私用区增乙，与 [Last 8](https://github.com/MY1L/Unicode/releases/tag/Last8) 重复的字形删除，具体如下：
  - 迁至：元􏾇`u10FF87`、冎|骨􏾈`u10FF88`、甲􏾉`u10FF89`、篆􏾊`u10FF8A`
  - 删除：㣇|彖、契、文、楚、越、鼎

#### 加了特技
作为工具字体，可以对b站 [三体 (艺画开天) _ 国创](https://www.bilibili.com/bangumi/media/md4315402/) 页面上特有示亡号`总策划：【林奇】`作处理，详见 [尝试解决B站不显示【示亡号】的问题 - 哔哩哔哩](https://www.bilibili.com/read/cv21481556)

利用OpenType特性`calt`，伪代码修正如下（.fea语法）……嘛，反正这是开源的，直接打开字体抄就行了。
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

## SIP,TIP
为防止转换格式有损曲线——3次转2次必然有损，2转3则可能有重叠问题，源自遍黑体的部分只有TTF版本。

### Han2 v4.393
目前为ttf格式，因为工作量，可能不会制作otf版。当前与遍黑体 P1 4.393版对齐，裁剪非汉字的区段。所有宋体字形是遍黑体就有的（咦）

理论总字数6,0873，实际因为某些兼容字或偏旁部首的字形完全一致(173个重复字形)，合并至60831个字形+1个`.notdef`

- 2023-1-27：`.notdef`字形略挤，微调。

### Han3 v1.175
目前为ttf格式，同上，可能不会制作otf版。当前与遍黑体 P2 1.175版对齐，裁剪非汉字的区段。共计9131个字形+1个`.notdef`，有4个字形与其它区段重复。

- 2023-1-27：`.notdef`字形…(同上)