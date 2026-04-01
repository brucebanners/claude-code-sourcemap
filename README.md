# claude-code-sourcemap

> [!WARNING]
> This repository is **unofficial** and was reconstructed from the publicly available npm package and its source map, **for research and educational purposes only**.
>
> It does **not** represent Anthropic's original internal repository structure or development history.

## Overview

This repository contains the TypeScript source code of **Claude Code v2.1.88**, recovered from the source map (`cli.js.map`) that was accidentally included in the official npm package `@anthropic-ai/claude-code`.

## Source Information

- **npm Package**: [@anthropic-ai/claude-code](https://www.npmjs.com/package/@anthropic-ai/claude-code)
- **Version**: `2.1.88`
- **Total recovered files**: **4756**
- **TypeScript source files**: **1884** (`.ts`/`.tsx`)
- **Recovery method**: Extracting the `sourcesContent` field from `cli.js.map`


restored-src/src/
├── main.tsx              # CLI entry point
├── tools/                # Tool implementations (Bash, FileEdit, Grep, MCP, and 30+ others)
├── commands/             # Command implementations (commit, review, config, and 40+ others)
├── services/             # Services (API, MCP, analysis, etc.)
├── utils/                # Utility functions (git, model, auth, env, etc.)
├── context/              # React Context
├── coordinator/          # Multi-agent coordination system
├── assistant/            # Assistant mode (includes KAIROS)
├── buddy/                # AI companion / pet UI
├── remote/               # Remote session handling
├── plugins/              # Plugin system
├── skills/               # Skills system
├── voice/                # Voice interaction
└── vim/                  # Vim mode
text## Disclaimer

- The original source code is copyrighted by **[Anthropic](https://www.anthropic.com)**.
- This repository is provided **solely for technical research and learning purposes**.  
  **Do not use it for any commercial purposes.**
- If you believe this infringes on any rights, please contact the repository owner for removal.

## Credits & Original Source

- **Original mirror**: [ChinaSiro/claude-code-sourcemap](https://github.com/ChinaSiro/claude-code-sourcemap)
- This repository is a fork/mirror based on the above project.
- No changes to authorship or rights are claimed.
