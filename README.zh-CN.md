<div align="center">

![Kling AI 视频提示词库封面](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts｜可灵 AI 视频提示词库

### 52 条原创生产级视频提示词 · 13 个制作专题 · 15 种语言项目指南

[![License: MIT](https://img.shields.io/badge/License-MIT-5b8cff.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/原创提示词-52-ff9f43.svg)](prompts/README.md)
[![Languages](https://img.shields.io/badge/项目语言-15-38c172.svg)](docs/LANGUAGES.md)
[![Status](https://img.shields.io/badge/Kling_4.0_Flash-抢先体验-f5c542.svg)](#模型版本与兼容性)
[![PRs Welcome](https://img.shields.io/badge/欢迎-提交_PR-brightgreen.svg)](https://github.com/flaqai/awesome-kling-4-0/pulls)

[English](README.md) · **简体中文** · [繁體中文](README.zh-TW.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Español](README.es-ES.md) · [全部 15 种语言](docs/LANGUAGES.md)

| [浏览 52 条提示词](prompts/README.md) | [提交原创提示词](https://github.com/flaqai/awesome-kling-4-0/issues/new?template=prompt.yml) | [提出缺失场景](https://github.com/flaqai/awesome-kling-4-0/issues/new?template=request.yml) | [贡献指南](CONTRIBUTING.md) | [使用 FLAQ.AI](#关于-flaqai) |
|---|---|---|---|---|

</div>

> [!IMPORTANT]
> **版本状态（2026-09-29）：** **Kling 4.0 Flash 已于 9 月 28 日向可灵 Ultra／黑金年卡会员开放抢先体验。**官方宣布更完整的 **Kling 4.0 及 API 接入计划于 2026 年 10 月推出**，尚未公布具体日期。完整 4.0 宣布支持**单次原生生成最长 30 秒**；这一数字不能直接视为当前 Flash 模式已开放的时长上限。依据：[可灵官方公告](https://sg.linkedin.com/company/kling-ai-api)及[4.0 更新说明](https://kling.ai/release-note/release-notes/Kling_4?type=dialog)。

这是一个面向真实创作流程的可灵 AI 视频提示词库，覆盖文生视频、图生视频、首尾帧、主体/元素参考、多镜头调度和原生音频。内容不是简单的画面形容词，而是包含角色一致性、空间位置、逐秒动作、摄影机路径、表演、物理反馈、声音和失败约束的完整导演简报。

## 一分钟找到合适的提示词

| 你想制作… | 从这里开始 |
|---|---|
| 直接复制一条完整提示词 | [52 条提示词总目录](prompts/README.md) |
| 剧情短片、双人或多人对白 | [电影与对白](prompts/cinematic-and-dialogue.md) |
| 产品广告、电商演示、UGC、本地商家内容 | [商业与 UGC](prompts/commercial-and-ugc.md) |
| 追逐、运动、变形或 VFX | [动作与特效](prompts/action-and-vfx.md) |
| 动画、时尚、音乐或舞蹈 | [风格与表演](prompts/style-and-performance.md) |
| 美食、旅行、建筑空间或工艺 | [美食、旅行与空间](prompts/food-travel-spaces.md) |
| 科普、纪录片、循环梗或公益内容 | [教育、纪录片与社交](prompts/education-documentary-social.md) |
| 匹配剪辑、多参考、动作迁移或视频修订 | [参考、编辑与控制](prompts/reference-editing-and-control.md) |
| 直播、数码、汽车或制造业内容 | [商业、科技、出行与工业](prompts/commerce-tech-mobility-industrial.md) |
| 讲解人、数字人、宠物或儿童科普 | [人物、宠物、学习与文化](prompts/people-pets-learning-culture.md) |
| 游戏、天文、绿幕素材或白模预演 | [游戏、自然与制作工具](prompts/gaming-nature-and-production-tools.md) |
| 竖屏短剧、对白喜剧或社交传播钩子 | [短剧与病毒式社交内容](prompts/short-drama-and-viral-social.md) |
| 动态图形、多图转场、材质匹配或尺度揭示 | [动态图形与转场](prompts/motion-graphics-and-transitions.md) |
| 封闭赛道、机械动画或声音驱动剪辑 | [类型动作与声音同步](prompts/genre-action-and-sound.md) |
| 改善镜头、动作、声音和连续性 | [提示词工程指南](docs/PROMPT-GUIDE.md) |
| 编写中文、外语或混合语言对白 | [多语言音频指南](docs/MULTILINGUAL-AUDIO.md) |
| 查看其他语言的使用说明 | [15 种语言目录](docs/LANGUAGES.md) |
| 查看 X 上最新的 Kling 4.0 Flash 视频和提示词 | [Flash 案例与写法](#kling-40-flash-x-视频与提示词实测) |
| 在网页中测试或接入 API | [FLAQ.AI 工作流](docs/FLAQ-AI.md) |

## 项目包含什么

- **52 条完整原创提示词：** 每条都有适用模式、连续性锚点、空间、逐秒镜头、声音、约束、替换思路和失败检查。
- **13 个制作专题：** 在参考控制、视频编辑、直播电商、汽车、工业、数字人、宠物、儿童科普、游戏和制作工具之外，新增竖屏连续短剧、病毒式社交内容、动态图形、多图转场、尺度揭示、类型动作和声音同步。
- **四种控制策略：** 文本探索、图生视频、首尾帧转场、主体/元素参考一致性。
- **五种已记录的 Kling 3.0 原生对白语言：** 中文、英文、日文、韩文、西班牙文，并包含混合语言写法；完整 4.0 宣布扩展语言支持。
- **15 种项目语言：** 提供本地化导航与快速模板，并明确区分“文档语言”和“模型原生语音能力”。
- **五张原创视觉素材：** 全部为本项目重新生成，并在[图片素材清单](assets/images/README.md)记录生成意图和提示词。
- **生产检查体系：** 画幅、摄影机、人物与产品一致性、声音时间轴、迭代记录、版权和发布前检查。
- **Flash 创作者观察清单：** 六条 X 原帖及其实用写法，加一条本项目原创的入门练习。
- **FLAQ.AI 使用说明：** 面向当前 Kling 3.0 文生视频、图生视频网页测试与 API 工作流。

## 模型版本与兼容性

| 项目 | 已确认状态 | 本仓库的处理 |
|---|---|---|
| Kling 4.0 Flash | **2026-09-28 开放抢先体验**，面向 Ultra／黑金年卡会员 | 以账户中实际开放的模式和设置为准，不套用完整 4.0 的全部参数 |
| 完整版 Kling 4.0 | **计划 2026 年 10 月推出**，未公布具体日期 | 已公布能力仍需在正式版本上线后验证 |
| 单次原生生成时长 | Video 3.0 最长 **15 秒**；完整 4.0 宣布最长 **30 秒** | 现有 52 条配方仍为 5–15 秒，使用更长时间轴前先确认所选模式支持 |
| 关键帧与多模态参考 | 完整 4.0 宣布最多 **10 张关键帧**、**15 项多模态参考** | 给每项参考明确职责，并检查实际开放的输入上限 |
| 完整 4.0 视听能力 | 宣布最高 **4K／10-bit HDR**、立体声及更精准口型同步 | 分辨率和音频选项以实际开放模式为准 |
| Kling 3.0 视频输出 | 使用指南列出 720p/1080p；快手 2026-08-19 披露原生 4K 已推出 | 记录实际模型、平台、模式和日期；不同入口可用性可能不同 |
| 多镜头 | 支持自动和自定义多镜头 | 为每镜明确时间、景别、动作与运镜 |
| 主体一致性 | 支持首帧 + 主体/元素参考 | 为人物、产品和道具重复命名锚点 |
| 原生音频 | 对白、环境声和效果声 | 按角色和时间节点分配声音 |
| Kling 3.0 已核验的对白语言 | 中、英、日、韩、西 | 完整 4.0 宣布扩展多语言、口音和方言支持；以实际所选模式为准 |
| 三人及以上对白 | 官方文档描述了多人指代能力 | 固定姓名、座位、服装颜色和发言顺序 |
| 可灵官方 API | 官方表示 **4.0 API 接入计划于 10 月推出** | 不预填未发布的模型 ID、价格或请求参数 |
| FLAQ.AI 当前状态 | Kling 3.0 工作流可用；4.0 文生视频与图生视频页面标为**即将推出** | 页面上线不等于 4.0 生成接口已开放 |

资料核验于 2026-09-29：[可灵官方 4.0 公告](https://sg.linkedin.com/company/kling-ai-api)、[4.0 更新说明](https://kling.ai/release-note/release-notes/Kling_4?type=dialog)、[可灵 Video 3.0 使用指南](https://app.klingai.com/cn/quickstart/klingai-video-3-model-user-guide)、[快手 3.0 原生 4K 公告](https://ir.kuaishou.com/news-releases/news-release-details/kuaishou-technology-announces-second-quarter-and-interim-2026)，以及 [FLAQ.AI 工作流说明](docs/FLAQ-AI.md)。

## Kling 4.0 Flash X 视频与提示词实测

**更新于 2026-09-29。**[可灵官方 X 发布视频](https://x.com/Kling_ai/status/2104596718067257458)展示 4.0 系列并说明 Flash 已开放抢先体验；宣传片长约 1 分 54 秒，**不能**据此推断 Flash 能单次生成同等长度。下列内容均为创作者自述的 Flash 测试，不是官方基准或本项目独立复测结果。请通过原帖观看视频并为作者署名；本仓库不搬运视频或照抄完整提示词。

| X 原帖 | 分享内容 | 可复用的提示词思路 |
|---|---|---|
| [Umesh：夜间猫咪跟拍](https://x.com/umesh_ai/status/2104595267794460949) · [原提示词](https://x.com/umesh_ai/status/2104595270671724936) | 作者标注为 20 秒的连续手持跟拍，跨多个相连空间 | 先锁定单一主体、连续路线和每个地点的一件物理事件，再规定摄影机始终跟随，不写成互不相干的场景。 |
| [OscarAI：动画演唱会](https://x.com/Artedeingenio/status/2104829034299351079) | 20 秒视频和原提示词；作者表示初步测试中简短、直接的写法效果更好，但也提到执行并不完全准确 | 先测试“主体 → 变化 → 运镜 → 结尾”的短链条，再逐步增加细节。 |
| [とすくん：天气突变短片](https://x.com/tokyo_Valentine/status/2104810060811833710) · [原提示词](https://x.com/tokyo_Valentine/status/2104810064750239987) | 15 秒角色参考视频及逐镜头提示词 | 明确角色图只控制身份与服装；另写天气、光线、动作何时改变，避免把参考图背景带入成片。 |
| [Alexandra Dekimpe：制作流程实测](https://x.com/HadesDesign/status/2104878440889417957) | 文章内含表演、动作、多镜头和参考素材的 Flash 片段 | 用可见的微表情代替抽象情绪；用“完成之后才……”固定因果顺序；对白写精确台词，或明确要求无对白。这些是作者的经验，不保证每次复现。 |
| [Aswin Aji Raj：印地语护肤 UGC](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | 作者标注的 20 秒印地语对白视频；帖子没有公开完整提示词 | 多语言测试要写明说话人和准确台词，并单独检查发音、口型与产品宣称。 |
| [@plasm0：3.0 与 Flash 对照](https://x.com/plasm0/status/2104597949485629557) | 作者称两条 10 秒视频使用了同一提示词 | 用相同提示词和参考素材做 A/B，记录模式与设置，再比较动作、阴影、身份和指令遵循；单组对照不能当作正式性能结论。 |

**本项目原创的 Flash 入门提示词（15 秒，9:16）：** 这是根据上述*测试方法*重新设计的未实测练习，不计入 52 条正式配方，也并非照搬 X 原帖。请以账户中实际开放的 Flash 控制项为准。

```text
[主体与参考]
一盏无品牌的可充电自行车灯放在修车铺工作台上。如提供参考图，该图只固定车灯形状、哑光石墨色外壳和唯一一枚琥珀色开关。全片始终只有这一盏灯。

[场景与摄影机]
黄昏的安静修车铺。摄影机用一个连续近距离跟随镜头，从修车师傅双手移动到车灯，再到自行车把手。窗外自然光；不切镜、不瞬移。

[时间轴]
0–4 秒：师傅把尚未点亮的车灯放在把手旁；画面同时交代双手和固定卡座。
4–8 秒：她把车灯卡入支架。只有在卡扣发出清晰的“咔哒”声并固定后，拇指才按下琥珀色开关。
8–12 秒：灯只亮一次，照亮前轮和地面的一小片区域。摄影机缓慢侧移，展示光束方向。
12–15 秒：她松开把手，车灯仍牢固固定。以自行车和灯光的稳定画面结束。

[声音与约束]
修车铺环境底噪、一次卡扣声、一次开关声；无对白、无音乐。保持车灯结构、手部数量、安装位置和光线方向一致。不出现品牌文字、多余车灯或无缘由的跳切。
```

Flash 值得分别测试**简短直接**和**较长但结构清晰**的提示词：关键在于每句话是否约束了可见或可听的决定。记录所选模式、时长、参考素材和实际结果后，再把配方标为“已测试”。

## 高质量可灵视频提示词的结构

```text
[输出]
时长、画幅、单镜头或多镜头、目标质感。

[参考素材职责]
图片 1 只锁定人物身份；图片 2 只锁定产品结构；动作参考只提供运动路径。

[连续性锚点]
命名人物 + 固定脸型/发型/轮廓/服装；产品或道具的固定形状/材质/颜色。

[空间与环境]
地点、时间、天气、真实光源、人物和物体的初始位置。

[逐秒镜头]
0–{x} 秒：景别、角度、摄影机路径；一个主要动作；物理反馈。
{x}–{y} 秒：下一节拍；一个主要动作；视觉回报和明确尾帧。

[表演与物理]
视线、呼吸、手部接触、重量、惯性、布料、液体和环境反应。

[声音]
角色名（语言、语气、语速）：“简短准确的台词”
环境底噪、同步拟音、音乐进入与停止时间。

[连续性与避免项]
明确绝不能改变的内容；避免脸部漂移、多余物体、假文字、标志和水印。
```

完整方法见[可灵视频提示词工程指南](docs/PROMPT-GUIDE.md)。

## 四个精选原创场景

| 场景 | 核心控制 | 完整提示词 |
|---|---|---|
| 植物气泡饮产品揭示 | 产品结构、微距、蒸汽、环绕和拟音 | [复制](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal) |
| 早晨护肤 UGC | 手机手持、自然皮肤、产品接触和合规口播 | [复制](prompts/commercial-and-ugc.md#3-morning-skincare-ugc-one-take) |
| 韩语 × 西语车站重逢 | 双人参考、多语对白、正反打和连续雨声 | [复制](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven) |
| 盐峡谷追逐 | 载具、摄影机、尘土和生物的独立轨迹 | [复制](prompts/action-and-vfx.md#1-the-glass-manta-pursuit) |

完整分类：

| 提示词集合 | 场景 | 数量 |
|---|---|---:|
| [电影与对白](prompts/cinematic-and-dialogue.md) | 微剧情、多语重逢、微表演、三人喜剧 | 4 |
| [商业与 UGC](prompts/commercial-and-ugc.md) | 饮品、功能演示、护肤 UGC、本地商家 | 4 |
| [动作与 VFX](prompts/action-and-vfx.md) | 追逐、攀岩、材质变形、微缩天气 | 4 |
| [风格与表演](prompts/style-and-performance.md) | 原创动画、时尚、音乐、舞蹈 | 4 |
| [美食、旅行与空间](prompts/food-travel-spaces.md) | ASMR、目的地、酒店/地产、工艺 | 4 |
| [教育、纪录片与社交](prompts/education-documentary-social.md) | 科普、自然、无缝循环、公益故事 | 4 |
| [参考、编辑与控制](prompts/reference-editing-and-control.md) | 匹配剪辑、多图连续性、动作迁移、视频修订 | 4 |
| [商业、科技、出行与工业](prompts/commerce-tech-mobility-industrial.md) | 直播、数码组装、汽车、制造业 | 4 |
| [人物、宠物、学习与文化](prompts/people-pets-learning-culture.md) | 讲解、数字人、动物档案、监督式科普 | 4 |
| [游戏、自然与制作工具](prompts/gaming-nature-and-production-tools.md) | 游戏、天文、绿幕素材、白模预演 | 4 |
| [短剧与病毒式社交内容](prompts/short-drama-and-viral-social.md) | 连续剧悬念、对白喜剧、伪纪录片、超现实循环 | 4 |
| [动态图形与转场](prompts/motion-graphics-and-transitions.md) | 脚本驱动 MG、多图过程、材质匹配、尺度揭示 | 4 |
| [类型动作与声音同步](prompts/genre-action-and-sound.md) | 封闭赛道、机械动画、工艺声音、轨道物理 | 4 |

## 多语言支持

项目现提供 15 种语言指南：

- 英语、简体中文、繁体中文、日语、韩语；
- 西班牙语、法语、德语、巴西葡萄牙语、意大利语；
- 阿拉伯语、俄语、印度尼西亚语、泰语、越南语。

52 条复杂提示词继续以英语文件作为稳定技术源，避免多版本的时间码、机位和声音约束发生无声偏移。其他语言页面提供本地化快速模板、版本警告、FLAQ.AI 简介和稳定的提示词 ID 链接。详细覆盖范围、标签翻译和本地化规则见[语言矩阵](docs/LANGUAGES.md)。

> 文档语言不等于原生语音能力。官方确认的可灵 3.0 原生对白语言为中文、英文、日文、韩文和西班牙文。可灵已宣布完整 4.0 将扩展多语言、口音与方言支持；实际使用前仍需检查所选模式并校对生成语音。

## 图生视频检查清单

- 固定人物身份、服装、产品形状、物体数量、构图和主光方向。
- 每个参考素材只承担一个任务，不让所有参考同时控制所有内容。
- 分开描述主体动作、环境动作与摄影机动作。
- 明确摄影机起点、路径、速度和停止位置。
- 保持手部接触、重量、惯性、倒影和阴影可信。
- 为减速和可用尾帧保留最后 1–2 秒。
- 将对白、环境、拟音和音乐拆成不同音频层。
- 只使用原创或已经授权的人物、产品、音乐、影像和地点。

## 常见问题

### 文生视频和图生视频怎么选？

从概念、脚本或氛围探索时使用文生视频；产品、人物、插画或首帧必须保持可识别时使用图生视频；转场终点也很重要时使用首尾帧。

### 如何保持人物或产品一致？

先建立一个主锚点，在描述动作前列出不变量；支持时绑定对应参考主体；明确排除重设计、零件数量变化、标签漂移和身份漂移。先验证锚点，再增加复杂特效。

### 提示词可以使用不同语言吗？

可以。项目提供 15 种语言的快速说明。对白需要明确角色、语言、语气和归属，并对发音、数字、专有名词与字幕进行独立检查。

### Kling 4.0 已经上线了吗？最长能生成 30 秒吗？

**Kling 4.0 Flash 已开放限定抢先体验**；完整 4.0 与 API 接入计划于 2026 年 10 月推出，具体日期未公布。**30 秒是官方宣布的完整 4.0 单次原生生成上限**，不能推断 Flash 或所有第三方平台目前均支持 30 秒。现有 52 条配方时长为 5–15 秒，完整模型上线后可按实际控制项扩展镜头节拍。

## 原创性与负责任使用

版本来源：[可灵官方 4.0 公告](https://sg.linkedin.com/company/kling-ai-api) · [4.0 更新说明](https://kling.ai/release-note/release-notes/Kling_4?type=dialog)。

所有提示词、场景、说明和本地图片均为这个项目重新创作，不复制第三方条目、作者信息或图库缩略图。外部项目只作为公开分类覆盖审计；两轮扩充的 28 条配方，其标题、人物、产品、镜头、对白和约束均从零编写。详细方法与参考记录见[策展、灵感与原创性政策](docs/CURATION.md)。商业发布前应检查版权、肖像、商标、音乐、产品宣称、安全、事实准确性、无障碍和平台政策。

## 关于 FLAQ.AI

[FLAQ.AI](https://flaq.ai/) 是一个面向图像、视频和语言模型工作流的网页平台与统一 API 层。创作者可以在浏览器中发现和测试模型，开发者也可以把已经验证的创意流程接入 API 生产环境。

| 你已有的素材 | FLAQ.AI 入口 | 适用场景 |
|---|---|---|
| 概念、脚本或镜头清单 | [Kling 3.0 Standard 文生视频](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) | 概念短片、社交开场、剧情镜头、预演 |
| 产品图、人物图、插画或首帧 | [Kling 3.0 Standard 图生视频](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/) | 产品动画、人物一致性、受控构图 |
| 提前规划 4.0 工作流 | [Kling 4.0 文生视频](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) · [图生视频](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) | 页面标注“即将推出”，不是已开放的生成或 API 接口 |
| 批量或应用集成 | [FLAQ.AI API 文档](https://flaq.ai/docs/) | 创意工具、批处理、自动化与产品接入 |

FLAQ.AI 已建立 Kling 4.0 文生视频和图生视频介绍页面，但均标为**即将推出**。可灵官方 Flash 抢先体验不代表 FLAQ.AI 的 4.0 API 已开放。生产前应查看实时模型页面与实际可用参数，详细步骤见[使用 FLAQ.AI 创建 Kling 视频](docs/FLAQ-AI.md)。

## 贡献与许可证

欢迎提交原创提示词、可复现测试、无障碍改进、严谨翻译和官方能力更新：

1. 有完整配方：直接[提交原创提示词](https://github.com/flaqai/awesome-kling-4-0/issues/new?template=prompt.yml)。
2. 只有真实需求：先[提出缺失场景](https://github.com/flaqai/awesome-kling-4-0/issues/new?template=request.yml)。
3. 已经完成测试或翻译：按 [CONTRIBUTING.md](CONTRIBUTING.md) 发起聚焦的 Pull Request。

投稿会区分“仅配方”“社区已测试”和“官方来源已核验”。预览图或视频不是必需项；如提交媒体，必须拥有兼容授权。仓库代码、文档和原创提示词文本采用 [MIT License](LICENSE)。“Kling / 可灵”与“FLAQ.AI”商标归各自权利人所有，本项目仅作描述性使用。

---

**SEO 主题：** Kling 4.0 提示词、可灵 4.0 prompt、Kling AI 视频提示词、Kling API、FLAQ.AI、可灵图生视频、参考生视频、视频编辑与续写、AI 短剧提示词、病毒视频提示词、动态图形、图片转场、声音同步、AI 视频广告提示词、直播电商视频、汽车视频、工业视频、绿幕素材、白模预演、UGC 提示词、多语言 AI 视频、电影分镜提示词。
