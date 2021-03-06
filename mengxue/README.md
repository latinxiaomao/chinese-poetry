蒙學
====

蒙學，是對我國傳統的幼兒啟蒙教育的一個統稱。與小學、大學並列，是我國傳統教育中的一個重要階段。

中國古代兒童啟蒙讀物最著名的就是“三百千”:

- [x] 《三字經》
- [x] 《百家姓》
- [x] 《千字文》

一般私塾“開蒙”則必先學這三種。另外再學便是一些初級讀物，如下:

- [x] 《弟子規》
- [x] 《幼學瓊林》
- [x] 《朱子家訓》
- [ ] 《千家詩》
- [ ] 《古文觀止》
- [ ] 《唐詩三百首》
- [x] 《聲律啟蒙》
- [ ] 《文字蒙求》
- [x] 《增廣賢文》

以上所列皆屬兒童啟蒙讀物。每個私塾所授各不相同，但“三百千”卻是幾乎所有的私塾開蒙的必讀物。

## 三字經

中國的傳統啟蒙教材，在中國古代經典當中，是最為淺顯易懂的讀本之一。

其取材典範，包括中國傳統文化的文學、歷史、哲學、天文地理、人倫義理、忠孝節義等等，而核心思想又包括了“仁、義、誠、敬、孝”。背誦《三字經》的同時，就能夠了解常識、傳統國學及歷史故事，以及故事內涵中為人處事的道理。

《三字經》大體分為 **傳統版** 和 **新版** 兩大類。傳統版比較廣泛，相對正宗。

傳統《三字經》最初由宋代 **王應麟** 所作，所以最初的本子“史”的部分到宋代結束，因此就是“**十七史，全在茲**”。本次收錄在此的為常見的 **清代版本** 。其中“**十七史，全在茲**”被修改為“**廿一史，全在茲**”。

**關於作者在學術界說法不一，在此新舊版本作者皆為王應麟。**

### 數據格式

[sanzijing-traditional.json](./sanzijing-traditional.json)與[sanzijing-new.json](./sanzijing-new.json)

```json
{
  "title": "三字經",
  "author": "王應麟",
  "tags": "傳統版",
  "paragraphs": [
    "人之初，性本善，性相近，習相遠。",
    "茍不教，性乃遷，教之道，貴以專。",
    "昔孟母，擇鄰處，子不學，斷機杼。",
  ]
}
```

## 百家姓

《百家姓》是一部關於中文姓氏的作品。按文獻記載，成文於 **北宋初** 。原收集姓氏411個，後增補到504個，其中單姓444個，復姓60個。

《百家姓》采用四言體例，對姓氏進行了排列，而且句句押韻，雖然它的內容沒有文理，但對於中國姓氏文化的傳承、中國文字的認識等方面都起了巨大作用，這也是能夠流傳千百年的一個重要因素。

### 數據格式

[baijiaxing.json](./baijiaxing.json)，其中含有郡望的姓氏緊438個。

```json
{
  "title": "百家姓",
  "author": "佚名",
  "tags": "北宋",
  "paragraphs": [
    "趙錢孫李，周吳鄭王。",
    "馮陳褚衛，蔣沈韓楊。",
    "朱秦尤許，何呂施張。",
  ],
  "origin": [
    { "surname": "趙", "place": "天水" },
    { "surname": "錢", "place": "彭城" },
    { "surname": "孫", "place": "樂安" },
  ]
}

```

### 數據比對



[族譜錄](http://wiki.zupulu.com/doc.php?action=view&docid=1016)可查詢姓氏來源及郡望

| [百度百科](https://baike.baidu.com/item/百家姓/194637?fr=aladdin) | [Amazon](https://www.amazon.cn/dp/B00AA7KIRI/ref=sr_1_1?__mk_zh_CN=%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BD%91%E7%AB%99&keywords=%E7%99%BE%E5%AE%B6%E5%A7%93&qid=1559799462&s=gateway&sr=8-1) | 輯錄 | 說明 |
| --- | --- | --- | --- |
| 孟〔平陆〕 | 孟〔平陵〕 | 孟〔平陆〕 | 郡望皆對 |
| 談〔广平〕 | 谈〔文平〕 | 谈〔广平〕 | 文平未能查到 |
| 袭〔渤海〕 | 裘〔渤海〕 | 裘〔渤海〕 | 記錄有誤 |
| 陆〔吴郡〕 | 陆〔河南〕 | 陆〔吴郡〕 | 郡望皆對 |
| 逢〔谯郡〕 | 逄〔谯郡〕 | 逢〔谯郡〕 | 記錄有誤 |
| 谷〔济阳〕璩〔豫章〕桑〔黎阳〕桂〔天水〕 | 郤〔济阴〕璩〔豫章〕桑〔黎阳〕桂〔天水〕 | 郤〔济阳〕璩〔豫章〕桑〔黎阳〕桂〔天水〕 | 記錄有誤,郡望皆對 |
| 盖〔汝南〕后〔冯翊〕桓〔谯郡〕公〔括苍〕 | 盖〔汝南〕益〔冯翊〕桓〔谯郡〕公〔括苍〕 | 盖〔汝南〕益〔冯翊〕桓〔谯郡〕公〔括苍〕 | 記錄有誤 |

### 存疑:

- `于`--`於`
- `谷`--`穀`
- `鬱`--`郁` [鬱姓与郁姓不同](https://zhidao.baidu.com/question/1513419599752509300.html)

## 千字文

《千字文》，由南北朝時期梁朝散騎侍郎、給事中 **周興嗣** 編纂、一千個漢字組成的韻文（在隋唐之前，不押韻、不對仗的文字，被稱為“筆”，而非“文”）。梁武帝（502—549年）命人從王羲之書法作品中選取1000個不重復漢字，命員外散騎侍郎周興嗣編纂成文。

全文為四字句，對仗工整，條理清晰，文采斐然。《千字文》語句平白如話，易誦易記，並譯有英文版、法文版、拉丁文版、意大利文版，是中國影響很大的兒童啟蒙讀物。

關於千字文中重複字: https://www.douban.com/group/topic/107163124/

關於避諱: https://xw.qq.com/ru/20141103029354/RU2014110302935400/

### 數據格式

[qianziwen.json](./qianziwen.json)

```json
{
  "title": "千字文",
  "author": "周興嗣",
  "tags": "南北朝",
  "paragraphs": [
    "天地玄黃",
    "宇宙洪荒",
    "日月盈昃",
    "辰宿列張",
  ],
  "spells": [
    "tiān dì xuán huáng",
    "yǔ zhòu hóng huāng",
    "rì yuè yíng zè",
    "chén xiù liè zhāng",
  ]
}
```

## 弟子規

《弟子規》原名《訓蒙文》，為清朝康熙年間秀才[李毓秀](https://baike.baidu.com/item/李毓秀/10781913)所著。其內容採用《論語》“學而篇”第六條：“弟子入則孝，出則弟，謹而信，泛愛眾而親仁。行有余力，則以學文”的文義，以三字一句、兩句一韻編纂而成。全文共360句、1080字。詳述了為人子弟在家、出外、待人接物、求學應有的禮儀與規範，是啟蒙養正，教育子弟養成忠厚仁愛道德風尚的經典教材。

### 數據格式

[dizigui.json](./dizigui.json)

```json
{
  "title": "弟子規",
  "author": "李毓秀",
  "content": [
    {
    	"chapter": "總敘",
    	"paragraphs": [
          "弟子規 聖人訓 首孝弟 次謹信",
          "泛愛眾 而親仁 有餘力 則學文"
    	]
    },
    {
    	"chapter": "入則孝",
    	"paragraphs": [
          "父母呼 應勿緩 父母命 行勿懶",
          "父母教 須敬聽 父母責 須順承",
          "冬則溫 夏則凊 晨則省 昏則定",
          "出必告 反必面 居有常 業無變",
    	]
    },
  ]
}
```

## 幼學瓊林

《幼學瓊林》是中國古代兒童的啓蒙讀物，作者程允升。《幼學瓊林》初爲明代西昌人程登吉（字允升）編著，本名《幼學須知》，又稱《成語考》、《故事尋源》，清人鄒聖脈作了增補，改名爲《幼學瓊林》，也叫《幼學故事瓊林》。

### 數據格式

[youxueqionglin.json](./youxueqionglin.json)

```json
{
  "title": "幼學瓊林",
  "author": "程登吉",
  "abstract": "《幼學瓊林》是中國古代兒童的啓蒙讀物，作者程允升。...",
  "content": [
    {
      "title": "卷一",
      "content": [
        {
          "chapter": "天文",
          "paragraphs": [
            "混沌初開，乾坤始奠。氣之輕清上浮者爲天，氣之重濁下凝者爲地。...",
          ]
        },
        {
          "chapter": "地輿",
          "paragraphs": [
            "黃帝畫野，始分都邑；夏禹治水，初奠山川。...",
          ]
        },
      ]
    },
    {
      "title": "卷二",
      "content": [
        {
          "chapter": "祖孫父子",
          "paragraphs": [
            "何謂五倫？君臣、父子、兄弟、夫婦、朋友；何謂九族？...",
          ]
        },
        {
          "chapter": "兄弟",
          "paragraphs": [
            "天下無不是底父母，世間最難得者兄弟。..."
          ]
        },
      ]
    },
  ]
}
```

## 朱子家訓

《朱子家訓》又名《朱子治家格言》、《朱柏廬治家格言》，是以家庭道德為主的啟蒙教材。《朱子家訓》僅524字，精闢地闡明了修身治家之道，是一篇家教名著。其中，許多內容繼承了中國傳統文化的優秀特點，比如尊敬師長，勤儉持家，鄰里和睦等，在今天仍然有現實意義。

### 數據格式

[zhuzijiaxun.json](./zhuzijiaxun.json)

```json
{
  "title": "朱子家訓",
  "author": "朱柏廬",
  "paragraphs": [
    "黎明即起，灑掃庭除，要內外整潔；",
    "既昏便息，關鎖門戶，必親自檢點。",
    "一粥一飯，當思來處不易；",
    "半絲半縷，恆念物力維艱。",
  ]
}
```

## 千家詩

TODO

## 古文觀止

TODO

## 唐詩三百首

TODO

## 聲律啟蒙

《聲律啓蒙》是訓練兒童應對，掌握聲韻格律的啓蒙讀物。按韻分編，包羅天文、地理、花木、鳥獸、人物、器物等的虛實應對。從單字對到雙字對，三字對、五字對、七字對到十一字對，聲韻協調，琅琅上口，從中得到語音、詞彙、修辭的訓練。從單字到多字的層層屬對，讀起來，如唱歌般。較之其它全用三言、四言句式更見韻味。這類讀物，在啓蒙讀物中獨具一格，經久不衰。明清以來，如《訓蒙駢句》、《笠翁對韻》等書，都是採用這種方式編寫，並得以廣泛流傳。

### 數據格式

[shenglvqimeng.json](./shenglvqimeng.json)

```json
{
  "title": "聲律啓蒙",
  "author": "車萬育",
  "abstract": "《聲律啓蒙》是訓練兒童應對，掌握聲韻格律的啓蒙讀物。...",
  "content": [
    {
      "title": "上卷",
      "content": [
        {
          "chapter": "一 東",
          "paragraphs": [
            "雲對雨，雪對風，晚照對晴空。來鴻對去燕，宿鳥對鳴蟲。..."
          ]
        },
      ]
    },
    {
      "title": "下卷",
      "content": [
        {
          "chapter": "一 先",
          "paragraphs": [
            "晴對雨，地對天，天地對山川。山川對草木，赤壁對青田。...",
          ]
        },
      ]
    }
  ]
}
```

## 文字蒙求

TODO

## 增廣賢文

《增廣賢文》爲中國古代兒童啓蒙書目。又名《昔時賢文》、《古今賢文》。書名最早見之於明代萬曆年間的戲曲《牡丹亭》，據此可推知此書最遲寫成於萬曆年間。後來，經過明、清兩代文人的不斷增補，才改成現在這個模樣，稱《增廣昔時賢文》，通稱《增廣賢文》。作者一直未見任何書載，只知道清代同治年間儒生周希陶曾進行過重訂，很可能是民間創作的結晶。

### 數據格式

[zengguangxianwen.json](./zengguangxianwen.json)

```json
{
  "title": "增廣賢文",
  "author": "佚名",
  "abstract": "《增廣賢文》爲中國古代兒童啓蒙書目。又名《昔時賢文》、《古今賢文》。...",
  "content": [
    {
      "chapter": "上集",
      "paragraphs": [
        "昔時賢文，誨汝諄諄。",
        "集韻增廣，多見多聞。",
        "觀今宜鑑古，無古不成今。",
        "知己知彼，將心比心。",
      ]
    },
    {
      "chapter": "下集",
      "paragraphs": [
        "前人俗語，言淺理深。",
        "補遺增廣，集成書文。",
        "世上無難事，只怕不專心。",
        "成人不自在，自在不成人；",
      ]
    }
  ]
}
```
