---
title: "以太坊慶功宴：第零個十年"
draft: false
date: 2024-11-21T00:00:00.000Z
description: "這是一場全球以太坊成員團聚的慶功宴，集結開發者、研究員、創業家、甚至懵懂無知的以太坊小白等各路角色，一同回顧以太坊過去成就，也共同討論未來發展方向與可能性的大型平台。明明是第 8 場卻叫 Devcon7 ，是因為傲嬌的工程師們，索引起始值喜歡是 0 。"
categories:
- posts
tags:
- excursion
---

幾個月前在[東京黑客松贏得了](../tokyo-nomads/) Devcon7 的免費門票；於是這個月，飛往泰國與會 Devcon，也順道參加 ETHGlobal Bangkok 黑客松。

這次出遊，剪的不是 vlog，而是用僅 7 秒回顧 14 天行程的短影片！ 

{{< youtube id="1rBjGseEipM" title="14 days in bangkok in 7 seconds">}}
<span class='caption'>▲ 去泰國工作、與會、比賽、與旅遊踩點</span>

---

### Devcon 是什麼？

[Devcon](https://devcon.org) 是以太坊基金會 (Ethereum Foundation) 最具代表性的旗艦會議，今年是第 8 屆，正好十週年。

明明是第 8 場卻叫 Devcon7 ，是因為傲嬌的工程師們，索引起始值喜歡是 0 🤷。

這是一場全球[以太坊](https://ethereum.org)成員團聚的慶功宴，集結開發者、研究員、創業家、甚至懵懂無知的以太坊小白等各路角色，一同回顧以太坊過去成就，也共同討論未來發展方向與可能性的大型平台。今年是史上規模最大的一屆，吸引橫跨 130 個國家的超過 12,500 名參與者，超過 300 小時的內容，包括講座、座談會、工作坊等。

{{< figure src="images/devcon1.png" alt="devcon7 closing ceremony">}}

內容之豐富，同時進行的活動輕易超過 10 種，先不論社交、贊助商攤位、工作坊等，光是講座就分佈在 7 個演講聽，每個人挑選自己有興趣的主題，能實際現場參與的活動佔所有活動的一小部分。

但這也沒關係，因為並非所有主題都適合所有人，內容廣度和深度自由選擇。我覺得我很像進了以太坊大學的新生，這四天在瘋狂選課和逛社團。連趕教室的過程都很像，會場從一端走到另一端估計要十分鐘，但每場演講間隔都只有 5 分鐘，沒有小跑步就來不及點名。

其中，我有參加 [BuidlGuidl](https://buidlguidl.com/) 面向以太坊開發新手主辦的入門工作坊，還有許多圍繞 *使用者體驗設計* 和 *加密貨幣的現實應用* 主題的演講。這邊列了幾場我覺得很有趣，推薦給跟我一樣不是重度技術宅的人👇

- [Ethereum in 30 minutes](https://www.youtube.com/watch?v=ei3tDRMjw6k)
- [Who needs a wallet anyway?](https://www.youtube.com/watch?v=iNLHWc5toYo)
- [Crypto Twitter is Wrong: This is How Rollups *Really* Work](https://www.youtube.com/watch?v=c1IbglrscSU)
- [Making Sense of Stablecoins](https://www.youtube.com/live/JMZcRMy-Oow?si=7PvuhUlwjeC4nacE&t=5281)

Devcon 並不是每年都辦，主辦方在閉幕典禮提到，崇尚減法原則，每場都要讓人覺得「足夠獨特」才會舉行，因此下一場規劃是在兩年後。

就在今年，以太坊透過 L2 讓[鏈上費用從 ≈15 台幣降到低於 0.3 台幣](https://youtu.be/ei3tDRMjw6k?si=kLWC59dHGfBms5mP&t=1324)；而近五年，美元穩定幣的流通量增加了 400 倍，逐漸滿足部分社群的價值儲存與匯款需求，有些人甚至說穩定幣是加密貨幣的市場需求契合點（Product-Market Fit）。

兩年後預計舉辦 Devcon8，不知道那時候，世界又會變成怎麼樣了呢？

---

### ETHGlobal 曼谷黑客松

Devcon7 才剛落幕，同一天，在同個會場隔壁場聽，緊接著就是 EthGlobal 舉辦的黑客松。這場黑客松又是 EthGlobal 史上規模最大：場地相當氣派，包吃包喝，官方數據 1,950 名參加者，總共提交 713 件作品。

{{< figure src="images/hack1.png" alt="finding our submission out of 700+ submissions">}}
<span class='caption'>▲ 在 700+ 件繳交作品中終於找到我們的</span>

這次做的題目是一套可以把自然語言意圖轉譯為錢包操作細節的框架，理想上能做到把「**寄給我爸 200 元**」 這個意圖透過框架與語言模型自動轉譯成：「在 Arbitrum 鏈上寄給地址 0x123...456 等值 200 台幣的 USDT 幣。確認我擁有足夠的 ETH 負擔鏈上費用。」

相關連結：[簡報](https://www.figma.com/deck/yrVT8EznA7uXOvQ7oYb1PZ/WTF%3A-A-Wallet-Intent-Translation-Framework?node-id=1-568&t=WqubanyKLnwBkrhg-1)｜[作品頁面](https://ethglobal.com/showcase/wtf-ai-wallet-sjmyx)

這次競爭非常激烈，沒有得獎，簡短記錄比賽心得：

- 我對以太新技術了解有限，缺少施力點發想有趣的應用，也較難提供主觀意見，討論時感覺總是被拉著走。
- 我們作品沒有針對任一項目方整合較深入的應用或場景。如果不是對自己的主題足夠有信心，這種規模的比賽可以考慮採取其他策略。
- 團隊默契欠佳，有位新成員在現場的時間不到 1/3，與其免強合作，不如拆組嘗試做自己有興趣的主題。

明年 EthGlobal 已經宣布在世界各地舉辦共四場黑客松，而且首場不在別處，正是[舉辦在台北](https://ethglobal.com/events/taipei)！有緣的話，明年繼續參與。

---

### 曼谷：既先進又落後的城市

我到泰國的前 13 天安然無恙，最後一天猜測因為 1) 黑客松缺乏睡眠＋2) 最後一餐吃了重口味的路邊攤食物又灌了不少冰水解辣，晚上起來吐了四次，吐到懷疑人生。而且凌晨四點半又得趕回台班機，身體狀況差到差點以為無法返臺。

抵達桃園機場，我就一個想法：「回到台灣真好。」

這次在曼谷待兩個禮拜，體感上覺得這是個既先進又落後的城市，很奇妙。

舉例來說，展場所在的詩麗吉王后國家會議中心 (QSNCC)，從正面望去有座巨型噴水池、周圍是細心照顧的綠色造景、背後是燈光璀璨的大廈，非常有未來城市的感覺。

{{< figure src="images/qsncc.jpg" alt="queen sirikit national convention center">}}
<span class='caption'>▲ pc qsncc.com 官網</span>

但僅隔會議中心一條馬路的距離，就是 24 小時不打烊曼谷最大的孔提生鮮市場（Khlong Toei Market），晚上經過，一排排堆放的貨櫃裡塞滿了活生生的雞，地上的血水、沿途濕市場的腥臭味，與展場外面的樣貌形成了極大的反差。

就消費而言，在曼谷要吃飽既便宜又方便，隨意經過的街道整排連線都是米其林餐盤，一頓飯大約只要 40–80 台幣，路邊的小販和小吃攤更多到數不勝數。但膽敢像我一樣餐餐到處亂吃的估計是少數，我到最後一天才反胃或許已經算相當幸運了，因為抵達後才第三天，就聽聞有位旅伴已經吃到迷之食物而臥倒在床了。

{{< figure src="images/message.png" alt="warning message in slack to not eat random food">}}
<span class='caption'>▲ 那時候還不信邪的我</span>

另外不得不提的一點：這邊交通真的太可怕了。光是從天橋往下看車潮，我就決定這趟旅程只依靠捷運系統和雙腳。在 Devcon 開始前的六天，我每天平均步伐將近 30,000 步。

但曼谷對行人也極度不友善，人行道時常窄到甚至要側身才能前行，拖行李的話可以直接放棄人行道了；另外，不用妄想能安全過馬路，紅綠燈簡直是裝置藝術，必須有勇者上前跨到車陣前方，對後面一長排車比出「稍等，我要過」的手勢，眼前的車才會稍微有些不甘的讓行人先通過。我好幾次走在人行道上或過馬路，車都離我不到半隻手臂的距離。

順帶一提，他們的捷運系統 (MRT 和 BTS) 並不便宜，到不算遠的地點，如果要轉系統，單程常常將近 100 台幣。

有些地方很好，但小小不適應的加總，在第七天，旅伴跟我互看了一眼，得出了結論：泰國大概是「願意長期待下去的地方」的低標了吧。

當晚，我好奇查了 HDI 人類發展指數（註：Human Development Index：聯合國推出的一個綜合性指標，考慮壽命、教育、收入等因素，試圖全面反映一個國家的發展程度），發現泰國跟我近年去過的其他國家比，分數確實相對低些，落在高度發展及格邊緣的 0.8 左右。前幾個月才去過的日本得分 0.92，美國則是 0.927。

{{< figure src="images/hdi.png" alt="Human Development Index of Thailand, United States, Japan, Hong Kong, and Israel.">}}

台灣因為不被聯合國承認，所以相關數據並未編列在 HDI 官方資料庫裡，但行政院主計處依照國際定義和編算方式帶入計算後，號稱台灣的得分為 0.926，也是超高得分的前段班。

我重新意識到，生活在台灣其實真沒什麼好抱怨的。

最後一個觀察：世界平均分是 0.739，泰國雖然得分略低，也已經充分高於世界平均。

在此新增一件在不遠未來想做的事：去 HDI 得分低於世界平均的國家旅遊幾天，或許可以打破一些既定的成見，甚至找回一些過於習已為常而遺忘的知足。

[回到最上](#)