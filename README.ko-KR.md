<div align="center">

![Kling 4.0 프롬프트 라이브러리](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts 한국어 가이드

영화, 제품 광고, UGC, 대화, VFX, 애니메이션, 음식, 여행, 교육 및 소셜 영상용 실전 AI 비디오 프롬프트 모음입니다.

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja-JP.md) · **한국어** · [Español](README.es-ES.md) · [15개 언어](docs/LANGUAGES.md)

[24개 프롬프트](prompts/README.md) · [프롬프트 가이드](docs/PROMPT-GUIDE.md) · [다국어 오디오](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **모델 상태(2026-08-20):** Kling 4.0은 공식 발표되지 않았습니다. 확인 가능한 최신 메이저 버전은 2026년 2월 5일 공개된 Kling AI 3.0입니다. 이 저장소는 공식 3.0 기능을 기준으로 만든 독립적인 “4.0-ready” 커뮤니티 프리뷰이며, 확인되지 않은 4K 비디오·가격·API·길이를 공식 사양처럼 주장하지 않습니다.

## 포함된 내용

- 12가지 실무 시나리오, 24개의 새로 작성된 완성형 프롬프트
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

[FLAQ.AI](https://flaq.ai/)는 이미지·비디오·언어 모델을 브라우저에서 시험하고 통합 API를 통해 제작 시스템에 연결할 수 있는 플랫폼입니다. 현재 [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/)와 [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/) 페이지를 제공합니다. 이 저장소는 FLAQ.AI에서 Kling 4.0을 사용할 수 있다고 주장하지 않습니다. 모델명, 가격, 길이, 해상도와 API 스키마는 사용 전에 실시간 페이지에서 확인하세요.
