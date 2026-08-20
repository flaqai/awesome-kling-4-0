<div align="center">

![Kling 4.0 プロンプト集](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts 日本語ガイド

映画、商品広告、UGC、会話、VFX、アニメ、料理、旅行、教育、SNS向けの実用的なAI動画プロンプト集。

[English](README.md) · [简体中文](README.zh-CN.md) · **日本語** · [한국어](README.ko-KR.md) · [Español](README.es-ES.md)

[24本のプロンプト](prompts/README.md) · [詳細ガイド](docs/PROMPT-GUIDE.md) · [多言語音声](docs/MULTILINGUAL-AUDIO.md)

</div>

> **モデル状況（2026-08-20）:** Kling 4.0 は公式発表されていません。確認できる最新メジャー版は 2026年2月5日公開の Kling AI 3.0 です。本リポジトリは、公式3.0の機能を基準にした独立の「4.0-ready」コミュニティプレビューです。未確認の4K動画、価格、API、尺を公式仕様として掲載しません。

## 収録内容

- 12の実用シナリオに対応した24本のオリジナル完成プロンプト
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
