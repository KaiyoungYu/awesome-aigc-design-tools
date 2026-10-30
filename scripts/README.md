# Generate the list

`README.md` is generated from one YAML file per entry in [`data/entries/`](../data/entries/). Edit those files, then run:

```bash
python3 scripts/generate_readme.py
```

Requires Python 3 and [PyYAML](https://pypi.org/project/PyYAML/) (`pip install pyyaml`).

Published entries are grouped by category. Each item shows the English blurb and a `推荐理由` line from `reason`. `stack`, `pricing`, and `notes` are included when set.

## Categories

Categories are job/intent based, not packaging. The generator accepts only these seven values. `design-tool`, `toolsite`, and `designer-site` are not valid and are not aliases.

| `category` | README heading | Intent |
| --- | --- | --- |
| `create` | Create | Products you open to make or iterate UI and prototypes (wireframe, hi-fi, edit). 创作工具. |
| `workspace` | Workspace | Canvas-first AI workspaces that route generation, tools, assets, and tasks. Not UI-specific design products. 画布工作台. |
| `components` | Components | Shippable kits or parts for a project or design file. 可交付组件. Static shippable parts belong here. |
| `motion` | Motion | Cursor, scroll, transition, and micro-interaction. 动效与交互. |
| `inspiration` | Inspiration | Portfolios, galleries, and reference sites. 灵感与参考. |
| `learn` | Learn | Teaching sites and tutorial brands that systematically teach software or creative craft. 教学与课程. |
| `plugin` | Plugins | Figma, Framer, and Sketch host extensions. 宿主插件. |

`create` is for making or iterating UI and prototypes. `workspace` is for canvas-first AI workspaces that route generation, tools, assets, and tasks, and is not a UI-specific design product. Pure chat apps and one-shot image sites stay out of both.

`learn` is for teaching hubs and tutorial brands. `inspiration` stays portfolios, galleries, and aesthetic reference — not teaching channels. One-off blog posts and bare docs sites are not `learn`.

A collection expands to individual entries. Showcase sites are usually not entries unless they are inspiration sources.

## Fields

| Field | Required | Notes |
| --- | --- | --- |
| `name` | yes | Display name |
| `url` | yes | Canonical `https` URL |
| `type` | yes | `single`, `component`, or `collection` |
| `category` | yes | `create`, `workspace`, `components`, `motion`, `inspiration`, `learn`, or `plugin` |
| `blurb` | yes | Short English one-liner |
| `stack` | no | List of strings |
| `pricing` | no | Short note |
| `reason` | yes | Recommendation reason (Chinese or English) |
| `notes` | no | Risks or caveats |
| `status` | yes | `published` |
| `updated` | yes | ISO date (`YYYY-MM-DD`) |
