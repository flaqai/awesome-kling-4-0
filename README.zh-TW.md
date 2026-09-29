<div align="center">

# Awesome Kling 4.0 Prompts｜繁體中文指南

52 條原創 Kling AI 影片提示詞，涵蓋電影、廣告、UGC、對話、VFX、動畫、美食、旅行、教育與社群內容。

[English](README.md) · [简体中文](README.zh-CN.md) · **繁體中文** · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [全部 15 種語言](docs/LANGUAGES.md)

[提示詞目錄](prompts/README.md) · [完整方法](docs/PROMPT-GUIDE.md) · [多語音訊](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **模型狀態（2026-09-29）：** Kling 4.0 Flash 已於 9 月 28 日向 Ultra 年卡會員開放搶先體驗。[可靈官方公告](https://sg.linkedin.com/company/kling-ai-api)表示，完整 Kling 4.0 與 API 接入計畫於 2026 年 10 月推出，尚無確切日期。完整版本宣布單次原生生成最長 **30 秒**；這不是目前 Flash 模式已驗證的片長上限。現有提示詞仍採用 5–15 秒時間軸。

## Kling 4.0 最新能力與入口

[可靈官方 X 公告](https://x.com/Kling_ai/status/2104596718067257458)確認 Flash 已開放 Ultra 年卡搶先體驗；完整 4.0 與 API 預計 2026 年 10 月推出。官方為完整版本公布單次最長 30 秒、最多 10 個關鍵影格、15 項多模態參考，以及最高 4K／10-bit HDR、立體聲與更多語言／口音。**不要將這些完整版本的數字直接當成 Flash 現有上限。**現有 52 條配方以 5–15 秒時間軸為基準。[FLAQ.AI 4.0 文生影片](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/)與[圖生影片](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/)目前均標示「Coming Soon」，並非已開放的 4.0 API。

## X 影片與提示詞觀察

**核對日期：2026-09-29。**[官方宣傳影片](https://x.com/Kling_ai/status/2104596718067257458)是 4.0 系列剪輯，不能把影片總長當成 Flash 單次生成能力。以下是創作者自述案例，不是官方基準或本專案獨立複測；影片與原提示詞請至原帖查看，本專案不轉載。

| 原帖 | 可借鑑的寫法 |
|---|---|
| [Umesh：20 秒貓咪跟拍影片](https://x.com/umesh_ai/status/2104595267794460949) · [原提示詞](https://x.com/umesh_ai/status/2104595270671724936) | 固定單一主角、連續動線與每處的一件動作；攝影機始終跟隨。 |
| [OscarAI：20 秒動畫演唱會與提示詞](https://x.com/Artedeingenio/status/2104829034299351079) | 作者初測偏好簡短直接的「主角 → 變化 → 鏡頭 → 收尾」，但也指出模型沒有完全照做。 |
| [とすくん：15 秒天氣變化影片](https://x.com/tokyo_Valentine/status/2104810060811833710) · [原提示詞](https://x.com/tokyo_Valentine/status/2104810064750239987) | 角色參考圖只負責身分與服裝；另行規定天氣、光線與表演的變化時點。 |
| [Alexandra Dekimpe：多種製作實測](https://x.com/HadesDesign/status/2104878440889417957) | 以可見的細微動作取代抽象情緒；用「完成後才」鎖定因果；明確寫出台詞或無對白。屬作者經驗。 |
| [Aswin Aji Raj：20 秒印地語 UGC](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | 作者沒有公開完整提示詞；多語測試應指定說話者與精確台詞，並檢查發音、對嘴與產品宣稱。 |
| [@plasm0：3.0／Flash 同提示詞對照](https://x.com/plasm0/status/2104597949485629557) | 固定提示詞與參考素材做 A/B，記錄設定；單組對照不是正式效能基準。 |

**本專案原創、尚未實測的 15 秒直式練習**（不計入 52 條正式配方；並非複製 X 原帖）：

~~~text
[主體與參考] 無品牌充電式自行車燈，啞光石墨色外殼、唯一一枚琥珀色開關；若上傳圖片，只用來固定車燈外形。全片只有一盞燈。
[場景與鏡頭] 黃昏的安靜修車舖；單一連續近距離跟拍，從師傅雙手移至車燈和車把；窗外自然光，不切鏡。
[0–4 秒] 將未點亮的車燈放在車把旁，同時拍到雙手與固定座。
[4–8 秒] 把車燈扣上；只有卡扣發出「喀噠」聲並固定後，拇指才按下開關。
[8–12 秒] 車燈只亮一次，照亮前輪與小片地面；鏡頭側移展示光束。
[12–15 秒] 師傅放開車把，車燈保持固定；停在穩定的完成畫面。
[聲音與限制] 環境底噪、一次卡扣聲、一次按鍵聲；無對白或音樂。保持外形、手部數量、安裝位置與光線方向；無品牌文字、額外車燈或跳切。
~~~

簡短提示詞與較長但結構清楚的提示詞都值得測試；先記錄模式、片長、參考素材與結果，再標記為「已測試」。歡迎依[貢獻指南](CONTRIBUTING.md)提交原創案例。

## 快速提示詞結構

```text
[輸出] 片長、畫面比例、單鏡頭／多鏡頭、視覺質感
[連續性錨點] 固定人物、服裝、產品與道具特徵
[空間與環境] 地點、時間、光源與起始位置
[逐秒鏡頭] 每段一個主要動作 + 一個攝影機意圖
[表演與物理] 視線、呼吸、手部接觸、重量與慣性
[聲音] 說話者、語言、語氣、環境、擬音與音樂時間點
[約束] 身分、方向、光線、文字、標誌與禁止變形
```

繁體中文屬於中文書寫本地化；官方確認的 Kling 3.0 原生對話語言包括中文、英文、日文、韓文與西班牙文。人名、數字、專有名詞、發音及字幕仍需逐一檢查。

## 建議場景

- [多語車站重逢](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [植物氣泡飲廣告](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [四季時尚轉場](prompts/style-and-performance.md#2-four-seasons-one-coat)
- [無限雨傘循環](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## 關於 FLAQ.AI

> 截至 2026-09-29，FLAQ.AI 的 [4.0 文生影片](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/)與[圖生影片](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/)頁面都標示「Coming Soon」；可靈官方 Flash 先行開放，不代表這兩個入口或 4.0 API 已可使用。

[FLAQ.AI](https://flaq.ai/) 是整合圖片、影片與語言模型的瀏覽器平台及統一 API 層。目前可使用 [Kling 3.0 Standard 文生影片](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/)與[圖生影片](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/)頁面。本專案不宣稱 FLAQ.AI 已提供 Kling 4.0；正式製作前請查看即時模型、價格、片長、解析度和 API 文件。

所有提示詞與本地圖片均為本專案重新創作。未經授權請勿使用真實人物、聲音、品牌、角色或音樂。
