<div align="center">

![Kling 4.0 프롬프트 라이브러리](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts 한국어 가이드

영화, 제품 광고, UGC, 대화, VFX, 애니메이션, 음식, 여행, 교육 및 소셜 영상용 실전 AI 비디오 프롬프트 모음입니다.

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja-JP.md) · **한국어** · [Español](README.es-ES.md) · [15개 언어](docs/LANGUAGES.md)

[52개 프롬프트](prompts/README.md) · [프롬프트 가이드](docs/PROMPT-GUIDE.md) · [다국어 오디오](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **모델 상태(2026-09-29):** Kling 4.0 Flash가 9월 28일 Ultra 연간 구독자를 대상으로 조기 제공되기 시작했습니다. [Kling AI 공식 발표](https://sg.linkedin.com/company/kling-ai-api)에 따르면 정식 Kling 4.0과 API 접속은 2026년 10월 출시 예정이며 정확한 날짜는 아직 없습니다. 정식 버전은 한 번에 최대 **30초** 생성할 수 있다고 발표했지만, 현재 Flash에도 같은 제한이 적용되는지는 확인되지 않았습니다. 기존 프롬프트는 5~15초로 작성되어 있습니다.

## Kling 4.0 새 기능과 이용 상태

[Kling AI 공식 X 게시물](https://x.com/Kling_ai/status/2104596718067257458)에 따르면 Flash는 Ultra 연간 구독자에게 먼저 제공되며, 정식 4.0과 API는 2026년 10월 출시 예정입니다. 정식 버전에는 단일 생성 최대 30초, 키프레임 최대 10개, 멀티모달 참조 최대 15개, 최대 4K/10-bit HDR, 스테레오 오디오와 더 폭넓은 언어·억양 지원이 발표되었습니다. **이 수치를 현재 Flash에서 검증된 한도로 해석하면 안 됩니다.** 기존 52개 프롬프트는 5~15초 기준입니다. FLAQ.AI의 4.0 [텍스트→비디오](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/)와 [이미지→비디오](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) 페이지는 아직 ‘Coming Soon’이며 실행 가능한 4.0 API가 아닙니다.

## X 동영상과 프롬프트 사례

**확인일: 2026-09-29.** [공식 소개 영상](https://x.com/Kling_ai/status/2104596718067257458)은 4.0 제품군의 편집 영상이며 전체 재생 시간이 Flash의 한 번 생성 길이를 증명하지 않습니다. 아래는 제작자가 직접 밝힌 테스트로, 공식 벤치마크나 이 저장소의 재현 검증이 아닙니다. 영상과 원문 프롬프트는 원본 게시물에서 확인하세요.

| 원본 게시물 | 적용해 볼 프롬프트 방식 |
|---|---|
| [Umesh: 20초 야간 고양이 추적 영상](https://x.com/umesh_ai/status/2104595267794460949) · [원문 프롬프트](https://x.com/umesh_ai/status/2104595270671724936) | 하나의 주인공, 이어지는 동선, 장소마다 한 가지 물리적 사건을 지정하고 카메라가 끊김 없이 따라가게 한다. |
| [OscarAI: 20초 애니메이션 공연과 프롬프트](https://x.com/Artedeingenio/status/2104829034299351079) | 제작자는 초기 실험에서 간결한 지시가 낫다고 보고했지만 완전한 준수는 아니었다. 주체→변화→카메라→결말 순서부터 실험한다. |
| [とすくん: 15초 날씨 변화 영상](https://x.com/tokyo_Valentine/status/2104810060811833710) · [원문 프롬프트](https://x.com/tokyo_Valentine/status/2104810064750239987) | 캐릭터 시트는 외모와 의상만 고정하고, 날씨·조명·연기의 변화 시점은 별도로 적는다. |
| [Alexandra Dekimpe: 제작 워크플로 테스트](https://x.com/HadesDesign/status/2104878440889417957) | 추상적 감정보다 눈에 보이는 미세 행동을 쓴다. ‘완료된 후에만’으로 인과를 고정하고 정확한 대사 또는 무대사를 지정한다. 개인 관찰이다. |
| [Aswin Aji Raj: 20초 힌디어 UGC](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | 전문 프롬프트는 공개되지 않았다. 화자와 정확한 문장을 지정하고 발음·립싱크·제품 주장을 검토한다. |
| [@plasm0: 3.0과 Flash 동일 프롬프트 비교](https://x.com/plasm0/status/2104597949485629557) | 같은 문장과 참조를 유지한 A/B 테스트를 하고 설정을 기록한다. 한 쌍의 결과를 정식 성능 평가로 일반화하지 않는다. |

**이 프로젝트가 새로 작성한 미검증 15초 세로 영상 연습 프롬프트**(공식 52개 레시피에는 포함되지 않으며 X 문구를 복사하지 않음):

~~~text
[주체/참조] 브랜드 없는 충전식 자전거 전조등 한 개. 무광 흑연색 본체와 호박색 스위치 하나. 이미지를 쓰면 전조등 형태만 고정한다. 영상 내내 전조등은 하나만 유지한다.
[장소/카메라] 해 질 무렵 조용한 자전거 수리점. 정비사의 두 손에서 전조등과 핸들바로 이어지는 단일 근접 추적 숏. 창문 자연광. 컷이나 순간이동 없음.
[0–4초] 꺼진 전조등을 핸들바 옆에 놓고 양손과 장착 브래킷을 함께 보여 준다.
[4–8초] 전조등을 브래킷에 끼운다. 딸깍 소리와 함께 완전히 고정된 후에만 엄지로 호박색 스위치를 누른다.
[8–12초] 불이 딱 한 번 켜져 앞바퀴와 작은 바닥 면을 비춘다. 카메라가 천천히 옆으로 움직여 빛줄기를 보여 준다.
[12–15초] 정비사는 핸들바에서 손을 뗀다. 전조등은 고정된 채로 남는다. 안정된 마지막 프레임을 유지한다.
[오디오/제약] 수리점 실내 소리, 장착 소리 한 번, 스위치 소리 한 번. 대사·음악 없음. 형태, 손의 수, 장착 위치와 조명 방향 유지. 브랜드 글자, 추가 전조등, 불필요한 점프컷 없음.
~~~

짧은 지시와 길지만 구조화된 지시를 모두 시험하고, 사용 모드·길이·참조·결과를 기록한 뒤에만 ‘테스트 완료’로 표시하세요. 독창적인 사례는 [기여 가이드](CONTRIBUTING.md)를 통해 제출할 수 있습니다.

## 포함된 내용

- 13개 제작 컬렉션, 52개의 새로 작성된 완성형 프롬프트
- 텍스트-투-비디오, 이미지-투-비디오, 시작/종료 프레임, 피사체 참조 전략
- 초 단위 샷, 카메라, 연기, 물리, 오디오 및 오류 방지 조건
- 한국어, 중국어, 영어, 일본어, 스페인어 대화 패턴
- 영화, 제품, UGC, 액션, 애니메이션, 패션, 음악, 음식, 여행, 공간, 교육, 소셜 콘텐츠
- 이 프로젝트만을 위해 새로 생성한 이미지 자산

## 기본 구조

```text
[출력] 길이, 화면비, 싱글 테이크/멀티샷, 시각적 톤
[연속성] 인물, 의상, 제품, 소품의 고정 특징
[공간] 장소, 시간, 광원, 시작 위치
[타임라인] 구간마다 하나의 주요 동작 + 하나의 카메라 의도
[연기] 시선, 호흡, 손 접촉, 감정 변화, 무게와 속도
[오디오] 화자(언어·톤·속도) + 환경음 + 동기화된 효과음
[제약] 얼굴, 손, 진행 방향, 조명, 텍스트, 로고, 원치 않는 변형
```

## 한국어 대화 예시

```text
민아 (한국어, 낮고 차분한 목소리): “종이학을 아직도 가지고 있었어?”
준 (한국어, 짧게 숨을 고른 뒤): “버릴 수가 없었어.”
민아의 대사 중에는 민아만 입을 움직이고, 준의 대사 중에는 준만 입을 움직인다.
번역, 자막, 추가 대사를 만들지 않는다. 빗소리는 두 대사 아래에서 끊기지 않는다.
```

이름, 숫자, 전문 용어의 발음과 정확한 문구는 반드시 결과에서 확인하세요. 자막은 검수 후 편집 단계에서 추가하는 편이 안전합니다.

## 추천 프롬프트

- [한국어×스페인어 기차역 재회](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [보태니컬 음료 제품 공개](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [루프형 우산 코미디](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)
- [새벽 루프탑 타악 연주](prompts/style-and-performance.md#3-rooftop-percussion-at-dawn)

전체 목록은 [프롬프트 카탈로그](prompts/README.md)를 확인하세요.

## 독창성과 책임 있는 사용

모든 설명과 프롬프트는 이 프로젝트를 위해 새로 작성되었으며, 타사 프롬프트나 썸네일을 복제하지 않습니다. 허가 없는 인물의 얼굴·목소리, 브랜드, 캐릭터, 음악을 사용하지 마세요. 광고 문구, 교육 정보, 건축·공예·지역 문화는 게시 전에 전문가 검토가 필요합니다.

공식 근거: [Kuaishou Kling AI 3.0 발표](https://ir.kuaishou.com/news-releases/news-release-details/kling-ai-launches-30-model-ushering-era-where-everyone-can-be) · [Kling Video 3.0 공식 가이드](https://app.klingai.com/cn/quickstart/klingai-video-3-model-user-guide)

## FLAQ.AI 소개

> 2026-09-29 기준 FLAQ.AI의 4.0 [텍스트→비디오](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/)와 [이미지→비디오](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) 페이지는 ‘Coming Soon’입니다. Kling 공식 Flash 조기 제공이 FLAQ.AI의 4.0 API 개방을 뜻하지는 않습니다.

[FLAQ.AI](https://flaq.ai/)는 이미지·비디오·언어 모델을 브라우저에서 시험하고 통합 API를 통해 제작 시스템에 연결할 수 있는 플랫폼입니다. 현재 [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/)와 [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/) 페이지를 제공합니다. 이 저장소는 FLAQ.AI에서 Kling 4.0을 사용할 수 있다고 주장하지 않습니다. 모델명, 가격, 길이, 해상도와 API 스키마는 사용 전에 실시간 페이지에서 확인하세요.
