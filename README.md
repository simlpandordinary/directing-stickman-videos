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
['SKILL.md', 'agents/openai.yaml', 'assets/b1/ATTRIBUTION.md', 'assets/b1/LUCIDE-LICENSE.txt', 'assets/b1/approved-2026-10-23-contact-sheet.png', 'assets/b1/approved-2026-10-23-motion-sheet.png', 'assets/b1/approved-2026-10-23.mp4', 'assets/b1/approved-2026-10-24-longform-contact-sheet.jpg', 'assets/b1/approved-baseline.json', 'assets/b1/approved-production-standard.json', 'assets/b1/calendar-crayon.png', 'assets/b1/camera-handdrawn.png', 'assets/b1/character-acting-reference.png', 'assets/b1/character-pose-sheet-v6.png', 'assets/b1/clapper-crayon.png', 'assets/b1/idea-bulb-crayon.png', 'assets/b1/idea-note-crayon.png', 'assets/b1/open-source-crayon.png', 'assets/b1/script-page-crayon.png', 'assets/b1/youtube-crayon.png', 'assets/b2/approved-style-board.jpg', 'assets/b2/approved-style-board.json', 'assets/b3/accepted-chair-motion.mp4', 'assets/b3/accepted-chair.png', 'assets/b3/accepted-dog-motion.mp4', 'assets/b3/accepted-dog.png', 'assets/b3/accepted-implementation-board.jpg', 'assets/b3/reference-manifest.json', 'assets/fonts/Caveat.ttf', 'assets/fonts/NotoSans.ttf', 'assets/fonts/OFL-Caveat.txt', 'assets/fonts/OFL-NotoSans.txt', 'examples/b1/narration.m4a', 'examples/b1/project.json', 'package-lock.json', 'package.json', 'references/a6-finishing.md', 'references/amber-noir.md', 'references/autopilot-production-qa.md', 'references/autopilot-runtime.md', 'references/autopilot.md', 'references/b1-minimal-handdrawn.md', 'references/b1-production-qa.md', 'references/b2-colorful-handdrawn.md', 'references/b3-television.md', 'references/cozy-storytelling.md', 'references/examples.md', 'references/getting-started.md', 'references/historical-cartoon.md', 'references/omni-flash-prompt-contract.md', 'references/prehistoric-dark-comedy.md', 'references/storyboard-template.md', 'references/style-catalog.md', 'references/thumbnail-publishing-kit.md', 'references/voice-continuity.md', 'scripts/a6_finish.py', 'scripts/align_captions.py', 'scripts/autopilot-core.mjs', 'scripts/autopilot-render.mjs', 'scripts/autopilot.mjs', 'scripts/b3-graphics.mjs', 'scripts/gemini-media.mjs', 'tests/b3-reference-pack.test.mjs', 'tests/b3-runtime.test.mjs', 'tests/runtime.test.mjs', 'LICENSE', 'README.upstream.md', 'CHANGELOG.upstream.md']
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原文。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/directing-stickman-videos/`：

```bash
git clone https://github.com/simlpandordinary/directing-stickman-videos.git ~/.workbuddy/skills/directing-stickman-videos
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/directing-stickman-videos> 装成 Skill」。

安装后用自然语言触发，例如「火柴人解说 stickman-video-director」「用 directing-stickman-videos 帮我处理这个任务」。



## 版权

原始作者与版权归上游仓库 `kaomei/stickman-video-director` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
