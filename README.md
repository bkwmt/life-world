# 音樂工作者的音樂生命時間流：屠穎

**網址**：https://bkwmt.github.io/life-world/ （手機、平板、桌機皆可開；需要 WebGL）

這是一個「生命史播放器」：把一位幕後音樂工作者在口述歷史裡講到的事件，做成一座可以走的像素群島。
一格六角島＝一個地點（家、學校、樂團、表演場所、唱片公司、錄音室……），島群沿生命流向從左到右排；
主角沿「生命路」（相鄰兩事件地點不同就是一條路）走過橋與島，島緣的燈一事件一盞、走過才亮；
底部時間尺是**回憶時間**（軸＝口述出現的順序＋人生階段帶，不推算年份）；中介宣稱畫成中介物從來源飄到受者；
點島可看該地點跨時間的所有事件（Esc 或 ☰ 回來）。

畫面上的字分三等：**原文依據**（逐字引自逐字稿，附檔名與時間碼）、**回憶時間錨點**（原文字）、**標題與類型**（由模型寫、標「模型」）。
每一筆事件、宣稱、關係都帶原文依據，程式逐字驗過才上畫面。

## 資料來源與方法

- 口述材料：臺北流行音樂中心「臺灣流行音樂口述歷史」（pmdb.taipei）屠穎卷的逐字稿；事件、中介宣稱與關係由 Claude 三段子代理抽取（抽取 → 全文查核 → 裁決），
  屬於中研院資訊所音樂與文化科技實驗室「口述歷史結構化抽取」研究的實驗產出（ICCCM 2026 海報：Ming Cheng、Yun-En Tsai、Li Su）。
- 地點與路線是跨人物共用的登錄簿（只增不改），之後其他音樂人會走進同一座群島。
- 14 位人物的小頭像取自 pmdb.taipei 人物頁照片，縮成 24×24、16 色的像素圖；人物體型與髮型由屬性與照片判定。

## 素材與授權

- 人物圖層：[Universal LPC Spritesheet Character Generator](https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator)（CC-BY-SA 4.0 使用並釋出）。作者共 16 位：Benjamin K. Smith (BenCreating)、Durrani、Eliza Wyatt (ElizaWy)、ElizaWy、Evert、JaidynReiman、Joe White、Johannes Sjölund (wulax)、Manuel Riecke (MrBeast)、Matthew Krohn (makrohn)、MuffinElZangano、Pierre Vigier (pvigier)、Stephen Challener (Redshrike)、TheraHedwig、bluecarrot16、thecilekli
- 城市磚、樹、路燈：[Kenney Roguelike Modern City](https://opengameart.org/content/roguelike-modern-city-pack)（CC0）。
- 樂器圖示：[CC0 Music Icons](https://opengameart.org/content/cc0-music-icons)（CC0）。
- 麥克風、混音台、MIDI、卡帶、黑膠、電視、樂譜、封套、卷軸、音符、耳機圖示：本專案自繪（CC0）。
- Three.js r160（MIT）。

本頁只放打包好的單檔播放器（`index.html`），原始碼與資料在研究專案的私有 repo。
