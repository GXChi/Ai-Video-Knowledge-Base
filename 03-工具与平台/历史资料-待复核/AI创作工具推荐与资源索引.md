# AI 创作工具推荐与资源索引

> 定位：这是一个“去哪找工具、教程、Skills 和参考资料”的导航页，不是完整教程，也不替代《AI视频创作路线图与工具选型指南》《端到端工作流》《剧本与创意》《提示词与分镜》等知识文档。
>
> 适用对象：个人创作者 / 一人工作室；既可以手动使用网页工具，也可以让 Codex、Claude Code 或本地 Agent 通过 Skills、API、MCP 和工作流调用工具。
>
> 维护原则：优先官方入口和可验证的项目主页；价格、模型名称、API 能力和服务可用地区变化较快，使用前以官网为准。这里的推荐是“值得了解/试用”，不代表每项都已实测。

## 0. 先按任务找资源

| 我现在要做什么 | 先看哪里 |
|---|---|
| 想法变成剧本、角色和分镜 | 02 文本、剧本与分镜工具；10 编剧与导演学习资源 |
| 生成角色图、场景图、道具和风格参考 | 03 图片、角色与场景资产工具 |
| 把图片/提示词变成视频片段 | 04 AI 视频生成工具 |
| 生成配音、角色对白、音乐、音效 | 05 音频与声音设计工具 |
| 剪辑、字幕、调色、合成和导出 | 06 剪辑与后期工具 |
| 让 Agent 自动生成剧本、分镜、提示词并调用 API | 07 Skills、Agent、API 与自动化 |
| 想跟着教程实际操作 | 08 官方教程与教学视频 |
| 想系统补电影/短剧创作基础 | 10 编剧、导演、摄影、剪辑与声音学习资源 |
| 想记录测试结果、费用和踩坑 | 11 评测与实战记录 |

## 1. 一站式 AI 视频创作平台

适合：快速试创意、短视频、营销内容、初步验证想法。缺点是自动化程度高不代表创作质量高，复杂剧情仍应检查剧本、镜头衔接和声音。

- [剪映 / CapCut](https://www.capcut.com/) — 剪辑、字幕、模板及 AI 视频相关能力；适合快速成片和社交平台内容。
- [CapCut：从想法到视频的官方指南](https://www.capcut.com/resource/turn-ideas-into-videos) — 了解从创意、分镜到生成和剪辑的流程。
- [ElevenLabs Studio](https://elevenlabs.io/) — 语音、音频和视频项目工作区，适合了解脚本、旁白、字幕和时间线协作。
- [小云雀](https://xyunque.com/) — 可作为中文一站式创作工具候选；使用前确认当前入口、功能和套餐。
- [即梦 AI](https://jimeng.jianying.com/) — 中文图像/视频创作入口；具体能力以当前产品页面为准。
- [可灵 AI](https://klingai.com/) — 视频生成、图生视频和相关创作能力。
- [海螺 AI](https://hailuoai.video/) — 视频生成工具候选。
- [Vidu](https://www.vidu.com/) — 视频生成及参考图相关能力候选。

## 2. 文本、剧本、故事与分镜工具

这类工具负责“想清楚要拍什么”，不应只让模型直接把一句话扩写成大量镜头。建议先确定受众、类型、时长、人物目标、冲突、转折和结尾，再拆场景与镜头。

- [ChatGPT](https://chatgpt.com/) — 故事开发、剧本诊断、角色弧线、分镜表、连续性检查和不同版本比较。
- [Claude](https://claude.ai/) — 长文档、剧本和设定集分析的候选工具。
- [豆包](https://www.doubao.com/) — 中文创意讨论、故事初稿和提示词草拟。
- [Blender Story Tools](https://studio.blender.org/training/story-tools/) — 通过 2D/2.5D 分镜、空间布局和镜头运动理解视觉叙事。
- [Storyboarder（Wonder Unit）](https://wonderunit.com/storyboarder/) — 分镜草图与镜头规划工具候选；检查当前项目维护情况后再投入工作流。

**建议输出物：** 一句话概念、故事梗概、节拍表、角色小传、场景清单、正式剧本、分镜表、对白/表演说明、连续性清单。不是每个项目都要全部生成，按片长和复杂度选择。

## 3. 图片、角色、场景与视觉资产

用于建立人物外观、服装、道具、场景、色彩和风格参考。长篇连续剧应建立可复用的“视觉设定集”，不要每个镜头重新描述角色。

- [即梦 AI](https://jimeng.jianying.com/) — 中文图像创作候选。
- [Midjourney](https://www.midjourney.com/) — 风格探索、概念图与视觉参考。
- [OpenAI 图像生成](https://chatgpt.com/) — 角色概念、场景参考、道具和视觉方案草图。
- [ComfyUI 官方文档](https://docs.comfy.org/) — 节点式图像/视频工作流；适合希望控制流程和复用节点图的人。
- [Blender](https://www.blender.org/) — 3D 场景、道具、预演、构图和摄像机运动；并非每个 AI 视频项目都需要。
- [OpenArt](https://openart.ai/) — 图像/视频创作与模型工具候选；使用前确认具体功能、授权与套餐。

**角色资产建议至少包含：** 正面/侧面/背面或多角度参考、面部特征、发型、服装、身高体态、常用表情、动作习惯、不可改变特征、负面约束，以及资产版本号。

## 4. AI 视频生成工具与 API

按任务选工具，而不是认定某一个模型永远最好。先用少量镜头测试人物一致性、运动、镜头控制、声音、画幅、时长、成本和生成失败率，再决定批量生产。

### 网页端创作

- [可灵 AI](https://klingai.com/) — 视频生成及动作/参考控制方向的候选工具。
- [即梦 AI](https://jimeng.jianying.com/) — 中文创作入口。
- [海螺 AI](https://hailuoai.video/) — 文生视频/图生视频候选。
- [Vidu](https://www.vidu.com/) — 参考图和视频生成候选。
- [Runway](https://runwayml.com/) — 视频生成、编辑和创作工具。
- [Luma](https://lumalabs.ai/) — 图像/视频生成与编辑工具。
- [Pika](https://pika.art/) — 创意视频生成与效果工具候选。
- [PixVerse](https://pixverse.ai/) — 视频生成工具候选。
- [Higgsfield](https://higgsfield.ai/) — 面向视觉效果与镜头风格的创作工具候选。

### API / 开发者接入

- [Runway API 文档](https://docs.dev.runwayml.com/api/) — API、SDK、任务轮询及多镜头 Recipe；适合程序化调用。
- [Kling API 文档](https://kling.ai/document-api/quickStart/productIntroduction/overview) — 官方 API 入门、模型和计费说明。
- [Google Gemini 视频生成文档](https://ai.google.dev/gemini-api/docs/video) — 视频生成与多模态视频编辑；模型状态可能变化，部署前核对当前可用模型。
- [Luma Agents API 文档](https://docs.agents.lumalabs.ai/) — 图像/视频 API、异步任务和结果获取。
- [fal.ai](https://fal.ai/) — 多种生成模型的 API 平台，适合快速试接不同模型。
- [Replicate](https://replicate.com/) — 模型托管与 API 调用平台。
- [Vercel AI SDK 视频生成指南](https://vercel.com/kb/guide/ai-sdk-video-generation) — 用代码统一发起生成任务的示例；注意其中实验性 API 可能变化。

**API 选型检查：** 官方/第三方来源、模型版本、输入输出限制、计费单位、并发限制、异步轮询、回调、失败重试、结果保存、数据保留政策、商用许可和区域可用性。不要只比较单次生成价格。

## 5. 配音、对白、音乐与音效

AI 视频常见短板不只是画面：对白节奏、环境声、动作音效、音乐进入点和镜头之间的声音连续性，也会显著影响完成度。

- [ElevenLabs](https://elevenlabs.io/) — 配音、语音生成、声音设计及音频工作流。
- [Adobe Podcast](https://podcast.adobe.com/) — 人声清理与播客音频处理工具候选。
- [Suno](https://suno.com/) — AI 音乐创作候选；商用权利和套餐限制需查当前条款。
- [Udio](https://www.udio.com/) — AI 音乐创作候选；使用前核对当前服务和授权条件。
- [Freesound](https://freesound.org/) — 社区音效库；逐个检查素材许可证、署名和商业使用条件。
- [Pixabay 音效与音乐](https://pixabay.com/music/) — 可搜索音乐素材；逐项核对授权条款。
- [YouTube 音效库](https://www.youtube.com/audiolibrary) — 视频创作者音效/音乐资源入口；遵守具体素材的署名要求。

**每个镜头的声音设计至少考虑：** 台词、表演语气/情绪、环境底噪、动作音效、音乐、声音进入/退出点、对白清晰度，以及相邻镜头的声场连续性。

## 6. 剪辑、字幕、调色与后期

- [DaVinci Resolve 官方培训](https://www.blackmagicdesign.com/products/davinciresolve/training) — 官方教学视频、PDF 教材、练习素材；涵盖剪辑、调色、音频、Fusion 和交付。
- [剪映 / CapCut](https://www.capcut.com/) — 快速剪辑、字幕、社交平台格式和轻量成片。
- [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) — 专业时间线剪辑与后期工具。
- [Adobe After Effects](https://www.adobe.com/products/aftereffects.html) — 合成、动态图形和视觉效果。
- [Topaz Labs](https://www.topazlabs.com/) — 视频增强/放大等后期工具候选；处理前先测试伪影和时间一致性。
- [Blender Video Sequencer](https://www.blender.org/) — 可用于基础视频剪辑、预演与 3D 内容整合。

**剪辑判断清单：** 镜头是否推动剧情；动作是否接得上；视线和空间关系是否清楚；镜头长度是否拖沓；景别是否有变化；反应镜头是否缺失；声音是否连续；节奏是否服务情绪；字幕和画面是否冲突；最终画幅、帧率、码率是否符合发布要求。

## 7. Skills、Agent、工作流和自动化

这里要区分三件事：**Skill 教 Agent 如何做一项任务；API/MCP 提供调用工具的能力；工作流把多个步骤按条件串起来。** 它们不是同一种东西。

- [Runway Dev 文档与 Agent Skills 入口](https://docs.dev.runwayml.com/) — 官方 API、SDK、MCP 和 Agent Skills。
- [ComfyUI 官方文档](https://docs.comfy.org/) — 节点式图像/视频工作流，文档包含 Agent/MCP 相关方向。
- [n8n 文档](https://docs.n8n.io/) — 连接 API、应用和 AI 节点，适合任务编排与自动化。
- [GitHub：搜索 video generation agent skills](https://github.com/search?q=video+generation+agent+skills&type=repositories) — 搜索社区项目；先检查维护时间、许可证、依赖和安全性。
- [GitHub：搜索 ComfyUI video workflows](https://github.com/search?q=ComfyUI+video+workflow&type=repositories) — 查找可复用工作流；检查模型版本和节点依赖。
- [GitHub：搜索 AI filmmaking workflow](https://github.com/search?q=AI+filmmaking+workflow&type=repositories) — 搜索端到端创作项目。
- [Model Context Protocol](https://modelcontextprotocol.io/) — 了解 MCP 的概念与工具连接方式。

### 值得建立的个人 Skills

1. `video-brief-to-plan`：把一句想法整理成创作简报；明确类型、受众、时长、平台、预算、风格和限制。
2. `story-development`：生成多个故事方案，比较冲突、人物目标、转折、情绪曲线和结尾，不直接跳到分镜。
3. `script-doctor`：检查逻辑、人物动机、对白自然度、节奏、信息重复和拍摄/生成可行性。
4. `character-and-world-bible`：生成角色设定、场景设定、道具表、视觉锚点和连续性规则。
5. `storyboard-planner`：将剧本拆成场景和镜头，写明景别、角度、运动、动作、表演、时长、转场和声音。
6. `video-prompt-builder`：把镜头描述转为指定视频模型可用的提示词，并保留角色、场景、动作与摄影信息。
7. `generation-batch-runner`：按镜头清单调用 API，管理并发、轮询、重试、文件命名、成本和失败记录。
8. `clip-review`：按剧情作用、运动连续性、人物一致性、画面瑕疵、音画关系和可剪辑性评估候选片段。
9. `edit-decision-list`：输出剪辑顺序、入出点、对白/音效/音乐、转场、字幕和节奏说明。
10. `final-qc`：检查画幅、帧率、音量、字幕、黑帧、错字、闪烁、音画不同步、版权和导出规格。

先做单个 Skill 并实际测试，再决定是否串成大工作流。不要一开始就做“全自动生成电影”的巨型 Agent；每个阶段应有明确输入、输出、检查规则和人工确认点。

## 8. 官方教程与教学视频入口

- [DaVinci Resolve 官方培训与教材](https://www.blackmagicdesign.com/products/davinciresolve/training) — 优先看剪辑入门、声音设计、调色和交付。
- [Blender 官方教程入口](https://www.blender.org/support/tutorials/) — 3D、场景、摄像机与工作流。
- [Blender Studio：Story Tools](https://studio.blender.org/training/story-tools/) — 分镜、2D/2.5D 预演和镜头布局。
- [ComfyUI 官方文档](https://docs.comfy.org/) — 节点工作流与模型接入。
- [n8n 官方文档](https://docs.n8n.io/) — API 集成与自动化。
- [Runway API 文档](https://docs.dev.runwayml.com/api/) — 适合程序员了解视频生成任务、SDK 和多镜头接口。
- [Kling API 文档](https://kling.ai/document-api/quickStart/productIntroduction/overview) — 官方 API 接入。
- [Google Gemini 视频文档](https://ai.google.dev/gemini-api/docs/video) — 多模态视频生成/编辑。

### 找教学视频的搜索词

中文：`AI短剧完整制作流程`、`AI短剧剧本分镜实战`、`AI视频角色一致性`、`AI视频镜头语言`、`AI视频连续性`、`AI视频声音设计`、`剪映短剧剪辑节奏`、`ComfyUI视频工作流`、`视频生成API自动化`。

英文：`AI filmmaking workflow`、`AI video storyboard workflow`、`cinematic shot design`、`film editing continuity`、`sound design for film`、`ComfyUI video workflow`、`video generation API automation`。

教程筛选时优先选择：有完整成品、有项目文件/提示词、有失败案例和复盘、说明工具版本与成本、解释“为什么这样做”，而不仅是快速演示按钮操作的内容。

## 9. 书籍与系统学习资源

以下先列官方免费教材和学习入口，不强行堆砌大量书名。后续可以按你实际想做的类型（短剧、电影感片段、动物/萌宠、玄幻、悬疑等）补充更有针对性的书单。

- **剪辑：** [DaVinci Resolve 官方教材](https://www.blackmagicdesign.com/products/davinciresolve/training)，从镜头选择、节奏、声音和连续性入手。
- **故事板与视觉叙事：** [Blender Studio Story Tools](https://studio.blender.org/training/story-tools/)，学习如何把故事转成空间、构图和镜头运动。
- **摄影与构图：** [Blender 官方教程](https://www.blender.org/support/tutorials/) 可作为摄像机、灯光和空间关系的实践入口；AI 视频也需要理解景别、视角、主体位置、光线方向和运动逻辑。
- **编剧与导演：** 建议后续建立独立的“编剧/导演学习清单”，按故事结构、人物目标与冲突、场景设计、对白、镜头语言、表演调度、剪辑节奏逐项找课程和案例；不要把单个理论当成所有类型故事的公式。

## 10. 参考案例与素材来源

- [Blender Studio](https://studio.blender.org/) — 可观察完整动画项目、制作流程和幕后资料；部分资源需要订阅。
- [Freesound](https://freesound.org/) — 音效素材，逐项检查许可证。
- [Pixabay](https://pixabay.com/) — 图片、音乐等素材入口，使用前核对授权。
- [YouTube Audio Library](https://www.youtube.com/audiolibrary) — 音乐和音效资源入口。
- [GitHub](https://github.com/) — 搜索开源工作流、脚本、插件与 Agent Skills；优先检查许可证、活跃度和依赖风险。

使用参考视频时，拆解它的镜头、节奏、色彩、声音和叙事手法用于学习；不要直接复制他人的角色、剧情、音乐或受保护素材来冒充原创。

## 11. 个人实测记录模板

每次只测试一个明确问题，例如“同一角色在 5 个镜头中是否稳定”，不要同时换模型、提示词和工作流，否则无法判断原因。

- 日期 / 项目：
- 任务类型 / 目标片长：
- 工具 / 模型 / 版本 / API 来源：
- 输入资产与提示词版本：
- 生成参数（画幅、时长、分辨率、参考图等）：
- 生成次数 / 成功率 / 总耗时 / 总费用：
- 角色一致性（1–5）：
- 动作与镜头可控性（1–5）：
- 画面瑕疵与连续性（1–5）：
- 声音质量（1–5）：
- 是否可剪辑、需要怎样修复：
- 本次最重要的发现：
- 下次只改动的一个变量：
- 参考文件 / 成品路径：

## 12. 与知识库其他文件的分工

- 本文件：**工具、资源、Skills 和教程的导航目录**。
- `01-工具与平台.md`：工具类别、定位、选择方法与平台比较；避免重复维护同一份长链接清单。
- `02-剧本与创意.md`：故事构思、剧本结构、人物与冲突。
- `03-角色与场景资产.md`：角色、场景、道具和视觉连续性资产。
- `04-提示词与分镜.md`：镜头描述、提示词组织和分镜输出格式。
- `05-端到端工作流.md`：从创意到成片的阶段流程与检查点。
- `06-Skills与Agent资产.md`：具体 Skill 的设计、安装、输入输出和调用方式。
- `07-自制教程.md`：经过自己实践验证的操作步骤。
- `08-教程收藏.md`：外部教程的收藏、摘要、适用场景和可信度备注。
- `09-实战记录模板.md`：每次生成测试、成本、质量和失败原因的记录模板。

## 13. 维护规则

1. 新工具先放本目录并注明用途，不要马上新建一篇重复介绍。
2. 有价值的教程应记录链接、作者/来源、发布日期或更新日期、适用工具版本、核心收获和是否实际验证。
3. 对会变动的价格、模型、API 和服务地区，不抄写长期固定结论；链接到官方页面并标注最后核对日期。
4. 社区 Skills/工作流先检查代码、许可证、依赖和权限，再安装或运行；不要把 API 密钥写入提示词、仓库或公开日志。
5. 实测有效后再把步骤升级成正式工作流或 Skill；未经测试的方案标注“候选/待验证”。
6. 本目录服务于个人创作，不以“工具越多越好”为目标。优先保留能解决明确问题、可复用且维护成本合理的资源。
