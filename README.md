# awesome-aigc-design-tools

Collect great AIGC powered ui ux design tools.

## Create

- [Anyway.Fonts](https://anyway.fm/fonts) — Chinese-first font preview — missing-glyph check, specimen posters, vertical layout, and plain-language OpenType feature lookup.
  > 推荐理由：更贴中文场景的字体预览：查缺字并筛选、中文样张与竖排预览、多字体对比，加上说人话的 OpenType 特性查询。Anyway.FM / JJ Ying 出品。
  > Stack: Web · Pricing: 免费（本机解析字体，不上传；建议 Chrome / Edge）
  > 注意：Safari 读本机第三方字体受限；字体文件不上传服务器。

- [Center Stage](https://reactbits.dev/tools/center-stage) — Turn screenshots or screen recordings into device-framed product shots with 3D tilt, depth of field, shadows and typography; export 4K images/video or GIF.
  > 推荐理由：把原始截图/录屏直接变成有景深、设备与光影的发布演示，补齐从界面做到产品展示的最后一步；比纯静态 mockup 更能处理视频和 GIF。
  > Stack: React · Pricing: 免费
  > 注意：ReactBits Creative Tools 的独立产品，正式名称是 Center Stage（不是 Center Satge）。

- [Onlook](https://onlook.com/) — The Cursor for Designers
  > 推荐理由：定位清晰的「设计师版 Cursor」，把 AI 直接嵌进设计制作流程。

- [Shape Magic](https://reactbits.dev/tools/shape-magic) — Logo mark editor using smart shapes, patterns, text or imported SVG with chrome, glass, neon and animated backgrounds; exports SVG, PNG, favicon, video or React.
  > 推荐理由：在浏览器里把几何标记、图案与材质串成一条视觉制作链路，导出不止位图，还有 SVG、favicon 和 React，适合快速做品牌小图形与页面视觉。
  > Stack: React · Pricing: 免费
  > 注意：ReactBits Creative Tools 的独立产品；材质和背景来自 ReactBits 生态，本条聚焦标记编辑与导出。

- [Sound Lab](https://reactbits.dev/tools/sound-lab) — Tune UI and video sounds, including taps, toggles, notifications, risers and whooshes; install via command or export WAV, MP3 or OGG.
  > 推荐理由：为 UI 微交互与演示视频补配乐之外的细节声响：音高、音色、长度和空间都可调，且能直接装进项目或下载通用音频，适合在意手感的设计/前端。
  > Pricing: 免费
  > 注意：ReactBits Creative Tools 的独立产品；不是完整 DAW 或自动配乐产品。

- [Texture Lab](https://reactbits.dev/tools/texture-lab) — Style photos, videos or camera input with 160 one-click looks and 75+ stackable animated effects, then export image, video, GIF or a shareable style.
  > 推荐理由：把 ASCII、半调、故障、玻璃等风格素材制作做成可叠加的实时编辑器，不只展示组件而是能直接产出图片/视频/GIF，做不同质感视觉很省事。
  > Stack: React, WebGL · Pricing: 免费
  > 注意：ReactBits Creative Tools 的独立产品；官方页面列有 160 一键风格与 75+ 可叠加动效。

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

- [Background Studio](https://reactbits.dev/tools/background-studio) — Browser editor for tuning ReactBits animated backgrounds, with code, high-resolution image, looping MP4/WebM and shareable-link exports.
  > 推荐理由：不用先读几十个组件文档就能实时调背景，再按需要带走代码或成品素材；做落地页氛围背景时很直接。
  > Stack: React, WebGL · Pricing: 免费
  > 注意：ReactBits Creative Tools 的独立产品；本条不重复收录其父级 ReactBits 组件库。

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

- [Liquid Glass](https://liquid-glass.glassapp.dev/) — WebGPU React/web/Electron glass surfaces and controls with live physical refraction (Clear/Regular, light/dark)—far beyond CSS blur.
  > 推荐理由：WebGPU 实时物理折射的玻璃材质，拖动时背景像凸透镜扭曲，质感吊打普通 CSS blur；Scene/Surface/Button/Toolbar/Tabs/Menu/Slider 等一整套可落地控件，演示站手感很顶。
  > Stack: React, WebGPU, TypeScript · Pricing: 免费 / 开源（MIT；npm `@glass-sdk/liquid-glass` ~0.0.2）
  > 注意：React 19+；需 HTTPS/localhost + WebGPU；Safari 有已知渲染问题。仓 https://github.com/Glass-HQ/liquid-glass；示例 https://liquid-glass.glassapp.dev/#examples。同题材另有 glassy-liquid（WebGL），本条只收录 Liquid Glass。

- [Lucide](https://lucide.dev/) — Community-maintained open icon toolkit (1600+ SVGs), Feather fork, with official packages across major frameworks.
  > 推荐理由：轻量一致的默认功能图标底座，社区活跃、包生态全；产品里表意优先的系统图标常从 Lucide 起步，再按需换成 Remix / Hugeicons 等。
  > Stack: React, Vue, Svelte, Figma · Pricing: 开源（ISC）
  > 注意：仓 github.com/lucide-icons/lucide；不收录品牌 logo。

- [Qing Icon](https://qingicon.com/) — Free neutral UI icon library (3900+) with line/fill/sketch, React & Vue, Figma plugin, and MCP for AI tools.
  > 推荐理由：中性、光学一致、中英检索，且 MCP 方便 AI 直接找图标出码，适合 AI/云产品界面。
  > Stack: React, Vue, Figma, MCP · Pricing: 开源（Apache-2.0）
  > 注意：Fill 仍在补齐；sketch 仅官网/Figma；开源仓 github.com/asorn/qingicon-open。

- [ReactBits](https://reactbits.dev/) — Animated React components, backgrounds, text and micro-interactions with editable JS/TS and CSS/Tailwind source via copy, shadcn CLI or MCP.
  > 推荐理由：老牌动效库持续上新，也能看到不少新库二次设计的原型；每个组件都提供 JS/TS 与 CSS/Tailwind 四种源码，结合 shadcn CLI/MCP 方便让 AI 按实装选组件；官网视觉也持续迭代。
  > Stack: React, TypeScript, WebGL · Pricing: 个人及商用免费（MIT + Commons Clause；组件本身不可转售或再分发）
  > 注意：Creative Tools 下五个独立产品已分别入库，本条不再重复收录；源码仓 https://github.com/DavidHDev/react-bits。

- [ReactDrops](https://reactdrops.dev/) — React animation and effect components with live previews, editable source, and frequent new drops (incl. Apple Music–style effects).
  > 推荐理由：创意动效更新快，含玻璃/物理等可落地组件，适合想和「AI 同质化界面」拉开差距的站点。
  > Stack: React, TypeScript, WebGL · Pricing: 免费（自定义许可，成品可用）
  > 注意：不可再分发为组件库/模板；仓 github.com/crisjavr/reactdrops。

- [Remix Icon](https://remixicon.com/) — Open-source neutral system icons (3200+) with paired Outlined and Filled styles on a 24×24 grid.
  > 推荐理由：line/fill 成对设计，正好支撑开/关、启用/禁用等状态切换；中性一致、检索友好，也含不少 AI 相关图标。
  > Stack: SVG, React, Figma · Pricing: 免费（Remix Icon License，可商用）
  > 注意：X @remixdesigner；仓 github.com/Remix-Design/RemixIcon；亦有 @remixicon/react。

## Motion

- [Motion Reference](https://motion-reference.takayustudio.jp/) — Takayu Studio's motion and easing dictionary — look up feel by name, speed, and easing, then copy CSS, AE recipes, and minimal code.
  > 推荐理由：把大量动画缓动按名称/速度/手感拆开查，可直接拷 CSS 缓动值、AE 配方和最小实现；告别凭玄学调参。作者 Takayu（takayustudio.jp）。
  > Stack: CSS, After Effects · Pricing: 免费
  > 注意：日文站；另有 3D 缓动参考 takayustudio.jp/3d-motion-reference。

- [Shaders](https://shaders.com/) — Declarative WebGPU visual effects for React, Vue, Svelte, Solid and JS — fluid gradients, liquid metal, cursor particles, and more.
  > 推荐理由：把流体渐变、液态金属、光标粒子等难啃的 GPU 效果收成声明式组件，引进就能跑；官网可在线调参导出，AI/MCP 也能直接装进项目，适合把产品官网质感拉高。
  > Stack: WebGPU, React, Vue, Svelte, Solid · Pricing: 核心 MIT 免费（npm + 编辑器导出）；Pro $199/年（预设库 / sections / MCP）
  > 注意：GitHub shader-effects-inc/shaders；引擎与框架绑定 MIT；Pro 预设/MCP 另计。需 WebGPU 浏览器。

- [Trail Cursor (Cursify)](https://cursify.ui-layouts.com/components/trail-cursor) — React trail/cursor effect component.
  > 推荐理由：轻量鼠标拖尾交互，含 reduced-motion，适合 toolsite/动效参考。

## Inspiration

- [Designeer](https://designeer.xyz/) — Hand-curated catalogue of design inspiration, UI/motion resources, tools, and portfolios for designers and developers.
  > 推荐理由：手挑的设计工程师向目录——灵感站、UI/动效/字体资源、工具与作品集（数百条量级），缺灵感时翻一圈很管用；站内也收录 Agents/MCP 相关工具。
  > Pricing: 免费浏览
  > 注意：目录本身不是 MCP 服务；MCP/agent 是站内收录的一类资源。designeer.org 为相关内容域。

## Learn

- [KurTips (Kurt Wei)](https://kurtwei.com/) — Blender tutorial brand and personal site by Kurt Wei, a former product engineer turned 3D artist and educator.
  > 推荐理由：中国影响力最大的 Blender 教学频道之一，官网沉淀课程品牌与路径，审美与完成度高，适合作为 3D 创作学习入口。
  > Pricing: 免费
  > 注意：主业是教学而非 UI/UX 工具；经维护者批准收录在 learn。X @kurtips。
