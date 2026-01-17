# tora-skills

Custom Claude Code skills for development workflows.

## Installation

Copy desired skill folders to `~/.claude/skills/` or your project's `.claude/skills/` directory.

## Skills

| Skill | Description |
|-------|-------------|
| `brainstorm` | Structured ideation and exploration before implementation |
| `conventional-commits` | Standardized commit message format (Conventional Commits spec) |
| `coordinator` | Project context tracking, ADRs, session handoffs |
| `frontend-dev` | UI/React components with high design quality |
| `fullstack-dev` | Contract + frontend coordination for synchronized changes |
| `ponder-gen` | Generate Ponder indexer handlers from ABIs |
| `preflight` | Session startup checklist and context loading |
| `process-rules` | SOPs, lessons learned, workflow governance |
| `repo-librarian` | Repository cleanup, dead code removal, doc reorganization |
| `repo-maintenance` | Versioning, releases, deployments, changelogs |
| `research-assistant` | Technical research, DeFi analysis (read-only) |
| `solidity-dev` | Smart contracts, gas optimization, security scanning |
| `sync-github-to-obsidian` | Sync markdown docs to Obsidian vault |
| `synpress-e2e` | E2E testing with MetaMask/wallet automation |
| `ui-rules` | Opinionated UI design constraints |
| `webapp-testing` | Playwright browser testing for web apps |

## Usage

Skills activate automatically based on context, or invoke explicitly:

```
/brainstorm
/solidity-dev
/conventional-commits
```

## Structure

Each skill is a folder containing:
```
skill-name/
└── skill.md    # Skill definition with frontmatter
```

## License

MIT
