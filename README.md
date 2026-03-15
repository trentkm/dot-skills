# dot-skills

Agent skills for building terminal interfaces.

## go-tui-design

Create distinctive, production-grade Go terminal UIs with Bubbletea, Lipgloss, and Bubbles.

Covers visual design craft and architectural patterns — from color palettes and typography to Elm Architecture composition, viewport scrolling, tmux popup integration, and common pitfalls.

### Install

```bash
npx skills add trentkm/dot-skills --skill go-tui-design
```

### What's inside

- **Architecture** — Bubbletea MVU patterns, component composition, message routing, state machines
- **Layout** — Lipgloss styling, responsive sizing, `JoinHorizontal`/`JoinVertical`/`Place`
- **Components** — Viewport, list, table, text input, spinner integration patterns
- **Visual design** — Color palettes (ANSI/256/true color), typography, box drawing, Unicode symbols
- **Interaction** — Cursor vs selection, keyboard conventions, focus management, vim command mode
- **Popup/launcher pattern** — `tmux display-popup` for ephemeral UIs, two-line cards, summary bars
- **tmux integration** — Pane detection, shell wrapper pitfalls, macOS quarantine workaround
- **Testing** — Unit testing Update/View, golden files, teatest
- **Debugging** — Message logging, common pitfalls (blocking, race conditions, layout math)
