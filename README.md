# 火柴人解说 stickman-video-director

> **[directing-stickman-videos](https://github.com/simlpandordinary/directing-stickman-videos)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/kaomei/stickman-video-director> |
| 上游路径 | `skills/directing-stickman-videos` |
| 上游协议 | MIT |
| 上游 Star | 4k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

Turn topics, requirements, articles or scripts into stickman videos. Director mode creates approved storyboards and standalone video prompts; Autopilot mode produces narrated, captioned illustration-and-micro-animation videos through configured generation tools and a local renderer. Also guide installation handoff, first use and setup of this specific Skill.

## 目录结构

```
├── CHANGELOG.upstream.md
├── LICENSE
├── README.upstream.md
├── SKILL.md
├── package-lock.json
├── package.json
├── tests/
│   ├── b3-reference-pack.test.mjs
│   ├── b3-runtime.test.mjs
│   └── runtime.test.mjs
├── scripts/
│   ├── a6_finish.py
│   ├── align_captions.py
│   ├── autopilot-core.mjs
│   ├── autopilot-render.mjs
│   ├── autopilot.mjs
│   ├── b3-graphics.mjs
│   └── gemini-media.mjs
├── references/
│   ├── a6-finishing.md
│   ├── amber-noir.md
│   ├── autopilot-production-qa.md
│   ├── autopilot-runtime.md
│   ├── autopilot.md
│   ├── b1-minimal-handdrawn.md
│   ├── b1-production-qa.md
│   ├── b2-colorful-handdrawn.md
│   ├── b3-television.md
│   ├── cozy-storytelling.md
│   ├── examples.md
│   ├── getting-started.md
│   ├── historical-cartoon.md
│   ├── omni-flash-prompt-contract.md
│   ├── prehistoric-dark-comedy.md
│   ├── storyboard-template.md
│   ├── style-catalog.md
│   ├── thumbnail-publishing-kit.md
│   └── voice-continuity.md
├── examples/
│   └── b1/
│       ├── narration.m4a
│       └── project.json
├── assets/
│   ├── fonts/
│   │   ├── Caveat.ttf
│   │   ├── NotoSans.ttf
│   │   ├── OFL-Caveat.txt
│   │   └── OFL-NotoSans.txt
│   ├── b3/
│   │   ├── accepted-chair-motion.mp4
│   │   ├── accepted-chair.png
│   │   ├── accepted-dog-motion.mp4
│   │   ├── accepted-dog.png
│   │   ├── accepted-implementation-board.jpg
│   │   └── reference-manifest.json
│   ├── b2/
│   │   ├── approved-style-board.jpg
│   │   └── approved-style-board.json
│   └── b1/
│       ├── ATTRIBUTION.md
│       ├── LUCIDE-LICENSE.txt
│       ├── approved-2026-10-23-contact-sheet.png
│       ├── approved-2026-10-23-motion-sheet.png
│       ├── approved-2026-10-23.mp4
│       ├── approved-2026-10-24-longform-contact-sheet.jpg
│       ├── approved-baseline.json
│       ├── approved-production-standard.json
│       ├── calendar-crayon.png
│       ├── camera-handdrawn.png
│       ├── character-acting-reference.png
│       ├── character-pose-sheet-v6.png
│       ├── clapper-crayon.png
│       ├── idea-bulb-crayon.png
│       ├── idea-note-crayon.png
│       ├── open-source-crayon.png
│       ├── script-page-crayon.png
│       └── youtube-crayon.png
└── agents/
    └── openai.yaml
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原件。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/directing-stickman-videos/`：

```bash
git clone https://github.com/simlpandordinary/directing-stickman-videos.git ~/.workbuddy/skills/directing-stickman-videos
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/directing-stickman-videos> 装成 Skill」。

安装后用自然语言触发，例如「火柴人解说 stickman-video-director」「用 directing-stickman-videos 帮我处理这个任务」。

## 版权

原始作者与版权归上游仓库 `kaomei/stickman-video-director` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
