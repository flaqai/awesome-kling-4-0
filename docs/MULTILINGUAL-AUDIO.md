# Multilingual Audio & Dialogue for Kling Video

[Home](../README.md) · [Prompt catalog](../prompts/README.md) · [15-language directory](LANGUAGES.md) · [Prompting guide](PROMPT-GUIDE.md) · [FLAQ.AI workflow](FLAQ-AI.md)

Kling Video 3.0’s official documentation lists native dialogue support for **Chinese, English, Japanese, Korean and Spanish**, including mixed-language scenes. This guide shows a compact, speaker-safe way to write those prompts. Treat pronunciation and exact wording as output to verify, especially for names, numbers and regulated claims.

## Speaker-safe syntax

```text
[SPEAKER MAP]
Mina = adult Korean woman in rust raincoat, low warm voice.
Álex = adult Spanish man in navy work jacket, soft tenor voice.

[DIALOGUE ORDER]
Mina (Korean, quiet, one-second pause before speaking): “늦었네.”
Álex (Spanish, relieved, almost whispering): “Pero llegué.”

[AUDIO CONSTRAINTS]
Only Mina’s mouth moves during Mina’s line. Only Álex’s mouth moves during Álex’s line.
Keep each line in its written language. No automatic translation, subtitles or extra speech.
Rain and train hum continue underneath both lines at low volume.
```

## Five-language micro-scene

Use this to test language switching without changing the visual setup.

```text
10-second single-take scene in a quiet community radio booth. Five adult hosts sit around one round table, each with a distinct wardrobe color and fixed seat. The camera makes one slow clockwise arc and stops on each active speaker. Only the named speaker moves their mouth; everyone else listens naturally.

Li (Mandarin Chinese, bright and concise): “准备好了吗？”
Emma (English, smiling): “Ready when you are.”
Haru (Japanese, calm): “始めましょう。”
Sora (Korean, playful): “좋아요, 시작해요.”
Lucía (Spanish, warm): “Vamos allá.”

Audio: steady quiet studio room tone, one soft button click at the beginning, no music, no overlap, no translation, no subtitles. Preserve every speaker’s face, seat, wardrobe and voice character throughout.
```

## Language-specific examples

### 中文

```text
阿岚（普通话，语速偏慢，克制但高兴）：“你真的把那盏灯修好了。”
阿哲（四川口音，轻声笑）：“说过要让它再亮一次。”
```

写法提示：标明“普通话 / 方言、语速、情绪、音量”；对白尽量短；人名、数字和专业名词必须复核。

### English

```text
Nora (English, soft London accent, measured pace): “You kept the blue thread.”
Sam (English, quiet Canadian accent): “It was how I knew it was yours.”
```

Prompting note: describe an accent only when it matters, and avoid caricature. Use short contractions and natural pauses rather than long written prose.

### 日本語

```text
美咲（日本語、静かで少しためらう）：「まだ、覚えてたんだ。」
蓮（日本語、安心した小声）：「忘れるわけないよ。」
```

書き方：話者名・言語・声量・間を明記します。漢字の読みが重要な固有名詞は、必要に応じて読み方も指定して出力を確認してください。

### 한국어

```text
민아 (한국어, 낮고 차분한 목소리): “종이학을 아직도 가지고 있었어?”
준 (한국어, 짧게 숨을 고른 뒤): “버릴 수가 없었어.”
```

작성 팁: 화자별 대사를 분리하고, 속도와 감정은 짧게 지정합니다. 고유명사와 숫자는 결과에서 반드시 확인하세요.

### Español

```text
Lucía (español de México, tono sereno): «Pensé que no vendrías.»
Mateo (español de España, voz baja): «Yo también.»
```

Consejo: indica la variante regional solo si aporta algo a la escena. Evita mezclar instrucciones de acento con imitaciones de personas reales.

## Mixed-language scene rules

1. Give every character a unique name, visual anchor and seat or screen position.
2. Put each line on its own line and include the language inside the speaker parenthesis.
3. Keep lines brief enough for the assigned shot duration.
4. State whether the other character understands, asks for repetition or responds nonverbally.
5. Ask the model to keep each line in the written language and not add a translation.
6. Use continuous ambience to bind the language switch into one world.
7. If lip sync matters more than camera complexity, use a stable medium close-up and reduce head turns.
8. Verify wording, pronunciation, speaker identity and unintended extra speech before publishing.

## Voice-over pattern

```text
Narrator (Spanish, warm documentary voice, 105 words per minute): “A esa hora, la ciudad todavía escucha al mar.”
The narrator is off-screen. No visible character moves their mouth.
Ambient waves remain natural and lower than the narration. No background song.
```

## Dialogue over a cut

```text
Mara begins the line on camera: “I thought the room would feel smaller—”
Cut on the dash to an empty wide shot while her same voice continues off-screen: “—but it remembered us.”
Keep voice identity, volume and room reverb continuous across the cut. Her mouth is not visible in the second shot.
```

## When to add captions later

Generated in-frame captions can mutate across frames. For accessible or legally required subtitles, a safer workflow is to generate clean dialogue without captions, transcribe and verify it, then add timed captions in an editor. If packaging or signage must remain exact, provide it in an approved reference image and inspect every frame.
