# AI Agents Office

**A multi-agent production system built with [Claude Code](https://claude.ai/code) by Anthropic.**

> 13 autonomous AI agents organized into 6 departments — orchestrated by Claude Code, connected through MCP servers, and powered by persistent memory.

## [View Live](https://misafkdoask.github.io/ai-agents-office/)

## Architecture

```
                    +------------------+
                    |   Claude Code    |
                    |   (Central OS)   |
                    +--------+---------+
                             |
        +--------------------+--------------------+
        |          |         |         |          |
   +---------+ +--------+ +--------+ +--------+ +----------+
   |Research | |Content | |Creative| |  Ops   | |Engineering|
   +---------+ +--------+ +--------+ +--------+ +----------+
   |Analyst  | |Strategy| |Designer| |Publish | |Integrator |
   |Intel    | |Writer  | |Present | |Commun. | |Pipelines  |
   |         | |Transl. | |        | |Analyt. | |QA Auditor |
   +---------+ +--------+ +--------+ +--------+ +----------+
```

## Departments

| Dept | Agents | Role |
|------|--------|------|
| **Research** | Market Analyst, Competitive Intel | Monitor 50+ channels, track trends and competitors |
| **Content** | Strategist, Copywriter, Translator | Plan, write, and adapt content across platforms |
| **Creative** | Visual Designer, Presenter | Generate images, branded assets, and presentations |
| **Operations** | Publisher, Community Manager, Analytics | Distribute content, manage engagement, track ROI |
| **Engineering** | Integration Engineer, Pipeline Builder, QA Auditor | Build MCP integrations, automate workflows, ensure quality |
| **Management** | Project Manager, Memory Keeper | Coordinate via dashboard, maintain persistent context |

## MCP Stack

`Playwright` `Telethon` `Figma` `PowerPoint` `GitHub` `Tavily` `Fetch` `Gemini API`

## How It Works

1. **Research** agents scan channels and collect market signals
2. **Strategist** maps trends to content calendar
3. **Copywriter** produces platform-specific content in brand voice
4. **Designer** generates visuals via Gemini API with brand overlays
5. **Publisher** distributes across Telegram, Twitter, LinkedIn
6. **Analytics** tracks performance and feeds insights back to Strategy
7. **Memory Keeper** preserves all context across sessions

All orchestrated through Claude Code with MCP server integrations — no manual handoffs.

## Tech

- Pure HTML/CSS/JS — no frameworks, no dependencies
- Hosted on GitHub Pages
- Interactive visualization with particle effects and scroll animations

---

*Built with Claude Code by Anthropic*
