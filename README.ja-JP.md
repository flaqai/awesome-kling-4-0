<div align="center">

![Kling 4.0 プロンプト集](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts 日本語ガイド

映画、商品広告、UGC、会話、VFX、アニメ、料理、旅行、教育、SNS向けの実用的なAI動画プロンプト集。

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · **日本語** · [한국어](README.ko-KR.md) · [Español](README.es-ES.md) · [15言語すべて](docs/LANGUAGES.md)

[52本のプロンプト](prompts/README.md) · [詳細ガイド](docs/PROMPT-GUIDE.md) · [多言語音声](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **モデル状況（2026-09-29）:** Kling 4.0 Flash は 9 月 28 日から Ultra 年間プランの利用者向けに先行提供されています。[Kling AI の公式発表](https://sg.linkedin.com/company/kling-ai-api)によると、完全版 Kling 4.0 と API アクセスは 2026 年 10 月に提供予定で、具体的な日付は未発表です。完全版では 1 回の生成で最長 **30 秒**を予定していますが、Flash で同じ上限を利用できることは確認されていません。既存のプロンプトは 5～15 秒です。

## Kling 4.0 の新機能と提供状況

[Kling AI の公式 X 投稿](https://x.com/Kling_ai/status/2104596718067257458)によると、Flash は Ultra 年間プラン向けに先行公開され、完全版 4.0 と API は 2026 年 10 月に提供予定です。完全版には、1 回の生成で最長 30 秒、最大 10 個のキーフレームと 15 件のマルチモーダル参照、最大 4K／10-bit HDR、ステレオ音声、多言語・アクセント対応が発表されています。**これらを現在の Flash の実測上限と混同しないでください。**既存の 52 本は 5～15 秒構成です。FLAQ.AI の 4.0 [Text-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) と [Image-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) は現在「Coming Soon」で、稼働中の 4.0 API ではありません。

## X の動画とプロンプト事例

**確認日：2026-09-29。**[公式紹介動画](https://x.com/Kling_ai/status/2104596718067257458)は 4.0 シリーズのプロモーション編集であり、その総尺が Flash の単発生成尺を示すわけではありません。以下は投稿者による自己申告のテストで、公式ベンチマークでも本プロジェクトによる再現検証でもありません。動画や元の全文プロンプトは原投稿で確認してください。

| 元投稿 | プロンプト設計のヒント |
|---|---|
| [Umesh：20 秒の猫の追跡動画](https://x.com/umesh_ai/status/2104595267794460949) · [元プロンプト](https://x.com/umesh_ai/status/2104595270671724936) | 主役を一匹に固定し、つながる移動経路と各場所の動作を指定する。カメラは切らずに追う。 |
| [OscarAI：20 秒のアニメライブとプロンプト](https://x.com/Artedeingenio/status/2104829034299351079) | 投稿者は初期テストで短く直接的な指示を好む一方、完全には従わなかったとも報告。主役→変化→カメラ→結末を先に試す。 |
| [とすくん：15 秒の天候変化動画](https://x.com/tokyo_Valentine/status/2104810060811833710) · [元プロンプト](https://x.com/tokyo_Valentine/status/2104810064750239987) | キャラクターシートは容姿と衣装に限定し、天候・照明・演技の変化を別に時間指定する。 |
| [Alexandra Dekimpe：制作ワークフロー検証](https://x.com/HadesDesign/status/2104878440889417957) | 抽象的な感情より目に見える微細な動作を書く。「完了した後だけ」で因果関係を固定し、台詞または無言を明示する。投稿者個人の観察。 |
| [Aswin Aji Raj：20 秒のヒンディー語 UGC](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | 全文プロンプトは未公開。話者と正確な台詞を書き、発音・リップシンク・商品表現を確認する。 |
| [@plasm0：3.0 と Flash の同一プロンプト比較](https://x.com/plasm0/status/2104597949485629557) | プロンプトと参照素材を固定して A/B テストし、設定を記録する。1 組の比較は正式な性能評価ではない。 |

**このプロジェクト独自の未検証 15 秒・縦型練習プロンプト**（52 本の正式レシピには含まず、X の文章は転載していません）：

~~~text
[被写体と参照] 無名ブランドの充電式自転車ライト。マットなグラファイト色の本体と、琥珀色のスイッチが一つ。画像を使う場合はライトの形状だけを固定する。全編でライトは一つ。
[場所とカメラ] 夕方の静かな自転車修理店。整備士の両手からライト、ハンドルへと寄る連続ワンカット。窓からの自然光。カットや瞬間移動なし。
[0–4 秒] 消灯したライトをハンドルの横に置き、両手と取付台を見せる。
[4–8 秒] ライトを台に固定する。カチッと音がして固定された後にだけ、親指でスイッチを押す。
[8–12 秒] ライトが一度だけ点灯し、前輪と床の一部を照らす。カメラを横に緩やかに動かして光束を見せる。
[12–15 秒] 整備士はハンドルを離す。ライトは固定されたまま。安定した完成画で終える。
[音と制約] 店内の環境音、固定音一回、スイッチ音一回。台詞・音楽なし。形状、手の本数、取付位置、光の方向を維持。ロゴ、余分なライト、不自然なジャンプカットなし。
~~~

短い指示と長くても構造化された指示の両方を試し、モデルモード・尺・参照素材・結果を記録してから「テスト済み」としてください。独自の事例は[投稿ガイド](CONTRIBUTING.md)から歓迎します。

## 収録内容

- 13の制作コレクションに対応した52本のオリジナル完成プロンプト
- テキスト動画、画像動画、開始・終了フレーム、被写体参照の使い分け
- 秒単位のショット設計、カメラ、演技、物理、音響、失敗防止条件
- 日本語・中国語・英語・韓国語・スペイン語の会話パターン
- 映画、商品、UGC、アクション、アニメ、ファッション、音楽、料理、旅行、建築、教育、SNS
- このプロジェクト専用に生成した新規画像素材

## 基本フォーマット

```text
[出力] 尺、画角、単一カット／マルチショット、ルック
[連続性] 人物、衣装、商品、道具の固定特徴
[空間] 場所、時間、光源、初期位置
[時間設計] 各区間に一つの主動作 + 一つのカメラ意図
[演技] 視線、呼吸、手の接触、感情の変化、重さ
[音] 話者名（言語・声色・速度）＋環境音＋同期フォーリー
[制約] 顔、手、方向、照明、文字、ロゴ、不要な変形
```

## 日本語会話の例

```text
美咲（日本語、静かで少しためらう）：「まだ、覚えてたんだ。」
蓮（日本語、安心した小声）：「忘れるわけないよ。」
美咲の台詞中は美咲だけが口を動かし、蓮の台詞中は蓮だけが口を動かす。
翻訳、字幕、追加台詞は生成しない。駅の雨音を両方の台詞の下で連続させる。
```

固有名詞や数字の読みが重要な場合は、出力を必ず確認してください。字幕は後編集で検証済みテキストを追加する方が安全です。

## おすすめ

- [多言語の駅での再会](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [ボタニカル飲料の商品動画](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [四季をつなぐファッション映像](prompts/style-and-performance.md#2-four-seasons-one-coat)
- [ループする傘のコメディ](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

全プロンプトは [カタログ](prompts/README.md) で確認できます。

## オリジナリティと利用上の注意

本文とプロンプトは本プロジェクト向けの独自制作で、第三者のプロンプトやサムネイルを転載していません。許可のない人物・声・ブランド・キャラクター・音楽は使用しないでください。広告表現、教育内容、建築・工芸・地域文化は公開前に専門的な確認が必要です。

公式情報: [Kuaishou Kling AI 3.0 発表](https://ir.kuaishou.com/news-releases/news-release-details/kling-ai-launches-30-model-ushering-era-where-everyone-can-be) · [Kling Video 3.0 公式ガイド](https://app.klingai.com/cn/quickstart/klingai-video-3-model-user-guide)

## FLAQ.AIについて

> 2026-09-29 現在、FLAQ.AI の 4.0 [Text-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) と [Image-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) は「Coming Soon」です。Kling 公式の Flash 先行公開は、FLAQ.AI の 4.0 API 開始を意味しません。

[FLAQ.AI](https://flaq.ai/) は、画像・動画・言語モデルをブラウザで試し、統合APIを通じて制作フローへ展開できるプラットフォームです。現在は [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) と [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/) のページを提供しています。本リポジトリは、FLAQ.AIでKling 4.0が利用可能だとは主張しません。モデル名、料金、尺、解像度、API仕様は利用前にライブページで確認してください。
