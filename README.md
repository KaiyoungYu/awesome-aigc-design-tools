# awesome-aigc-design-tools

Collect great AIGC powered ui ux design tools.

## Create

- [Onlook](https://onlook.com/) — The Cursor for Designers
  > 推荐理由：定位清晰的「设计师版 Cursor」，把 AI 直接嵌进设计制作流程。

- [UIZard](https://uizard.io/) — Visualize, communicate, and iterate on wireframes and prototypes in minutes. Empower your product team with AI!
  > 推荐理由：把线框、沟通、迭代压到分钟级，适合产品/设计团队快速对齐界面方案。

- [Vitrum](https://usevitrum.com) — Browser-local tool that turns SVG/PNG logos into glass, metal, or colour 3D icons and exports PNG, GLB, or STL.
  > 推荐理由：轮廓自动识别且保留镂空，约 29 种材质预设，一条链路覆盖设计稿 PNG、Web 用 GLB 与打印 STL；全本地、零上手成本，补上「平面标 → 精致 3D 图标」这块空白。
  > Stack: TypeScript, Three.js · Pricing: 免费 / 开源（beta；无账号，文件不出设备）
  > 注意：复杂或低对比 logo 可能描边不稳；不是完整 3D 编辑器，也无批量。开源仓 https://github.com/volkanakyel/vitrum-3d

## Workspace

- [Breatic](https://github.com/orime-org/breatic) — Source-available collaborative creation workspace with shared documents, AI canvases, and project-aware agents.
  > 推荐理由：共享简报、参考素材和画布迭代保留在同一项目中；多人实时协作，Agent 文档改写由人审阅后采用。
  > Stack: TypeScript, React, Yjs, Hocuspocus · Pricing: Elastic-2.0（source-available）
  > 注意：是内容创作工作空间，不是 UI/UX 专用生成器；内部部署按许可允许，存储和模型服务需另行配置、成本另计。

- [Opentu](https://opentu.ai/) — Open-source canvas-first AI workspace that routes multi-model generation, tools, assets, and knowledge in one place.
  > 推荐理由：以画布把多模型生成、工具与素材收进同一工作区，符合 workspace；开源可自托管，适合需要持续执行 AI 创作任务的设计/产品流程；GitHub 仓库现为 ljquan/opentu（原 aitu）。
  > Stack: TypeScript · Pricing: 开源
  > 注意：偏通用 AI 画布工作台，不是 UI/UX 专用创作产品。

## Components

- [Animal Island UI](https://guokaigdg.github.io/animal-island-ui/) — Kawaii React + TypeScript UI kit with a cozy Animal Crossing–inspired design language.
  > 推荐理由：风格统一、组件齐全且带 AI 用法文档，适合做风格化界面练习与快速原型。
  > Stack: React, TypeScript · Pricing: 开源（MIT）
  > 注意：非任天堂官方；仓 github.com/guokaigdg/animal-island-ui。个别文档曾写非商用，以根目录 MIT LICENSE 为准。

- [Bencho](https://bencho.dev/) — Live React UI components and micro-interactions you can tune, copy as source, and pull into projects via MCP.
  > 推荐理由：约 158 个可现场调参的 live block（非录屏），免费可直接拷进项目；Pro 用 MCP 让 Cursor/Claude 按需搜块贴代码，对在乎手感的设计/前端很实用。独立作者 Lorenzo Cabra，另有 Finds 画廊、合成 UI 音效、Bench 并排调参画布。
  > Stack: React · Pricing: 部分免费（MIT）；Pro €99/年；Forever €129 买断（全量源码 + MCP）
  > 注意：Free blocks MIT；Pro 另有许可。源码 github.com/cabralorenzo/bencho；MCP 需 Pro key。

- [beUI](https://beui.dev/) — Animated components for React and Next.js (Motion + Tailwind, open source).
  > 推荐理由：动效完成度高、可复制进项目，工程友好，覆盖 Web + Native。
  > Stack: React, Next, Motion, Tailwind, RN · Pricing: MIT + Pro

- [BoardUI](https://www.boardui.com/) — React + Tailwind v4 design system for dashboards and agentic UIs; CLI/MCP installs editable source components, charts, and Pro templates.
  > 推荐理由：源码落地、shadcn 风格 registry，并专做 agent composer、token meter 与 MCP，适合后台与 AI 产品界面，而不是锁定的 npm 黑盒组件库。
  > Stack: React, Tailwind CSS v4, React Aria, Figma · Pricing: Freemium（基础 MIT 免费；图表 / agent 组件 / 整页模板 Pro）
  > 注意：约 103 组件 + 19 charts + 10 Pro templates；`npx boardui@latest`；MCP https://www.boardui.com/mcp。

- [Hugeicons](https://hugeicons.com/) — Large multi-style icon system (60k+; 6k+ free Stroke Rounded) for web, mobile, and Figma, with framework packages and MCP.
  > 推荐理由：体量大、线面与多风格齐全，适合功能图标的状态成组（开/关、展开/折叠等）；和 Lucide、Qing Icon 互补，偏产品完成度与多端交付。
  > Stack: React, Vue, Figma, MCP · Pricing: Freemium（免费 Stroke Rounded MIT；Pro 多风格按席位）
  > 注意：X @huge_icons；仓 github.com/hugeicons/hugeicons。Pro 不可作为可下载模板/开源包再分发。

- [Lucide](https://lucide.dev/) — Community-maintained open icon toolkit (1600+ SVGs), Feather fork, with official packages across major frameworks.
  > 推荐理由：轻量一致的默认功能图标底座，社区活跃、包生态全；产品里表意优先的系统图标常从 Lucide 起步，再按需换成 Remix / Hugeicons 等。
  > Stack: React, Vue, Svelte, Figma · Pricing: 开源（ISC）
  > 注意：仓 github.com/lucide-icons/lucide；不收录品牌 logo。

- [Qing Icon](https://qingicon.com/) — Free neutral UI icon library (3900+) with line/fill/sketch, React & Vue, Figma plugin, and MCP for AI tools.
  > 推荐理由：中性、光学一致、中英检索，且 MCP 方便 AI 直接找图标出码，适合 AI/云产品界面。
  > Stack: React, Vue, Figma, MCP · Pricing: 开源（Apache-2.0）
  > 注意：Fill 仍在补齐；sketch 仅官网/Figma；开源仓 github.com/asorn/qingicon-open。

- [ReactDrops](https://reactdrops.dev/) — React animation and effect components with live previews, editable source, and frequent new drops (incl. Apple Music–style effects).
  > 推荐理由：创意动效更新快，含玻璃/物理等可落地组件，适合想和「AI 同质化界面」拉开差距的站点。
  > Stack: React, TypeScript, WebGL · Pricing: 免费（自定义许可，成品可用）
  > 注意：不可再分发为组件库/模板；仓 github.com/crisjavr/reactdrops。

- [Remix Icon](https://remixicon.com/) — Open-source neutral system icons (3200+) with paired Outlined and Filled styles on a 24×24 grid.
  > 推荐理由：line/fill 成对设计，正好支撑开/关、启用/禁用等状态切换；中性一致、检索友好，也含不少 AI 相关图标。
  > Stack: SVG, React, Figma · Pricing: 免费（Remix Icon License，可商用）
  > 注意：X @remixdesigner；仓 github.com/Remix-Design/RemixIcon；亦有 @remixicon/react。

## Motion

- [Trail Cursor (Cursify)](https://cursify.ui-layouts.com/components/trail-cursor) — React trail/cursor effect component.
  > 推荐理由：轻量鼠标拖尾交互，含 reduced-motion，适合 toolsite/动效参考。

## Learn

- [KurTips (Kurt Wei)](https://kurtwei.com/) — Blender tutorial brand and personal site by Kurt Wei, a former product engineer turned 3D artist and educator.
  > 推荐理由：中国影响力最大的 Blender 教学频道之一，官网沉淀课程品牌与路径，审美与完成度高，适合作为 3D 创作学习入口。
  > Pricing: 免费
  > 注意：主业是教学而非 UI/UX 工具；经维护者批准收录在 learn。X @kurtips。
