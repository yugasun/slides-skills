# slides-skills

[English](README.md) | 中文版

使用精美模板生成高质量 HTML 幻灯片演示文稿。

## 在线演示

👉 **[主演示](https://yugasun.github.io/slides-skills/)** — 14 页幻灯片，展示 8-bit-orbit 模板（霓虹像素风格），讲解技能全部能力。使用方向键或滑动导航。

👉 **[Creative Mode 演示](https://yugasun.github.io/slides-skills/creative.html)** — 14 页 Creative Mode 模板风格幻灯片，展示 Workflow A 模板的丰富布局可能性。

## 安装

### 通过自然语言（最简单）

直接告诉 Claude Code/Codex 你想做什么：

```plaintext
帮我安装 slides skill https://github.com/yugasun/slides-skills
```

### 通过 CLI

```bash
npx skills add yugasun/slides-skills
```

## 特性

- **32 个精美模板** — 专业设计的 HTML 幻灯片模板
- **4 个内置主题** — 赛博朋克、企业、极简、自然，快速输出
- **交互式导航** — 键盘/点击导航，进度条
- **单文件输出** — 所有 CSS、JS、HTML 打包成一个文件

## 使用方法

安装后，直接描述你的需求：

```plaintext
/创建一个产品发布会演示文稿
/制作一个关于 AI 趋势的技术演讲
/用赛博朋克主题生成团队评审
```

技能会询问你的**场合**和**氛围**，展示 3 个模板候选和实时预览，然后构建最终的幻灯片。

## 模板工作流程

1. **明确品味** — 代理询问场合和氛围
2. **筛选 3 个候选** — 从 32 个模板中匹配
3. **预览** — 构建标题幻灯片预览并在浏览器中打开
4. **构建** — 从选定的模板创建完整幻灯片
5. **交付** — 在浏览器中打开最终的 HTML 幻灯片

## 主题工作流程（快速）

适用于快速、自包含的输出，无需模板：

| 主题   | 风格     |
|--------|----------|
| **赛博朋克** | 深色、霓虹、未来主义 |
| **企业** | 浅色、专业、蓝灰色 |
| **极简** | 黑白色、瑞士风格 |
| **自然** | 奶油色/绿色、优雅衬线 |

## 仓库布局

```plaintext
slides-skills/
├── demo/                          # 在线演示（Studio 模板）
├── skills/slides/                # 技能源
│   ├── SKILL.md                  # 主技能定义
│   ├── beautiful-html-templates/  # 32 个精选 HTML 模板
│   ├── templates/                # 基础模板（主题工作流）
│   └── themes/                   # CSS 主题
├── README.md
└── README_zh.md
```

## 参考

- [beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates)

## 许可证

MIT
