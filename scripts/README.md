# Generate the list

`README.md` is generated from one YAML file per entry in [`data/entries/`](../data/entries/). Edit those files, then run:

```bash
python3 scripts/generate_readme.py
```

Requires Python 3 and [PyYAML](https://pypi.org/project/PyYAML/) (`pip install pyyaml`).

Published entries are grouped by category. Each item shows the English blurb and a `推荐理由` line from `reason`. `stack`, `pricing`, and `notes` are included when set.

## Fields

| Field | Required | Notes |
| --- | --- | --- |
| `name` | yes | Display name |
| `url` | yes | Canonical `https` URL |
| `type` | yes | `single`, `component`, or `collection` |
| `category` | yes | `design-tool`, `components`, `toolsite`, `designer-site`, or `plugin` |
| `blurb` | yes | Short English one-liner |
| `stack` | no | List of strings |
| `pricing` | no | Short note |
| `reason` | yes | Recommendation reason (Chinese or English) |
| `notes` | no | Risks or caveats |
| `status` | yes | `published` |
| `updated` | yes | ISO date (`YYYY-MM-DD`) |
