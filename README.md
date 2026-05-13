# slides-skills

[中文版](README_zh.md) | English

Generate high-quality HTML slide presentations with beautiful templates.

## Live Demos

👉 **[Main Demo](https://yugasun.github.io/slides-skills/)** — 14-slide showcase of the 8-bit-orbit template, explaining the skill's full capabilities. Use arrow keys or swipe to navigate.

👉 **[Creative Mode Demo](https://yugasun.github.io/slides-skills/creative.html)** — 14-slide showcase of the Creative Mode template style, showcasing the diverse layout possibilities of Workflow A templates.

## Install

### Via natural language (easiest)

Just tell Claude Code/Codex what you want:

```
Install the slides skill https://github.com/yugasun/slides-skills
```

### Via CLI

```bash
npx skills add yugasun/slides-skills
```

## Features

- **32 Beautiful Templates** — Professionally-designed HTML slide templates
- **4 Built-in Themes** — Cyberpunk, Corporate, Minimal, Nature for fast output
- **Interactive** — Keyboard/click navigation, progress bar
- **Single-file Output** — All CSS, JS, HTML bundled into one file

## Usage

Once installed, just describe what you want:

```
/create slides for a product launch
/make a tech talk about AI trends
/generate a team review with cyberpunk theme
```

The skill will ask about your **occasion** and **mood**, present 3 template candidates with live previews, then build the final deck.

## Template Workflow

1. **Clarify taste** — Agent asks about occasion and mood
2. **Shortlist 3 candidates** — Match against 32 templates
3. **Preview** — Build title-slide previews and open in browser
4. **Build** — Create the full deck from the chosen template
5. **Deliver** — Open the final HTML deck

## Theme Workflow (Fast)

For quick, self-contained output without templates:

| Theme | Style |
|-------|-------|
| **Cyberpunk** | Dark, neon, futuristic |
| **Corporate** | Light, professional, blue/slate |
| **Minimal** | Black & white, Swiss style |
| **Nature** | Cream/green, elegant serif |

## Repository Layout

```
slides-skills/
├── demo/                          # Live demo (Studio template)
├── skills/slides/                 # Skill source
│   ├── SKILL.md                   # Main skill definition
│   ├── beautiful-html-templates/   # 32 curated HTML templates
│   ├── templates/                 # Base templates (theme workflow)
│   └── themes/                    # CSS themes
├── README.md
└── README_zh.md
```

## References

- [beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates)

## License

MIT
