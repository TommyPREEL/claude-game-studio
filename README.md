# Claude Game Studio

A skill for [Claude Code](https://claude.com/claude-code) that turns Claude into the technical project lead of a video game (or any creative project) for a director who does not code.

It gathers working rules learned on a real indie game production:

- **Working with the director**: plain-language reports, smart questions, challenging the request.
- **Running the work**: managing agents and picking the right Claude model per task, saving tokens without losing quality.
- **Tools and checks**: setting up the tools (engine, Blender, MCP servers, tests, git), testing and verification.
- **Making the game**: balancing without a playtime target, UI/UX harmony rules, icon drawing rules, art direction, cinematics, sound, avoiding the "AI look" in favour of human-feeling design, playtesting and sharing builds.

It is generic: pair it with your project's own `CLAUDE.md`. The project file always wins.

## Install

**For one project:** copy the `game-studio` folder into your project's `.claude/skills/` folder.

```
your-project/
  .claude/
    skills/
      game-studio/
        SKILL.md
```

**For all your projects:** copy it into your personal skills folder instead:
- Windows: `C:\Users\<you>\.claude\skills\game-studio\`
- macOS / Linux: `~/.claude/skills/game-studio/`

Or clone and copy:

```
git clone https://github.com/<owner>/claude-game-studio.git
cp -r claude-game-studio/game-studio ~/.claude/skills/
```

## Use

Claude picks the skill up automatically when relevant. You can also call it directly with `/game-studio` at the start of a work session.

Adapt it freely: change the model names, add your own rules, remove what does not fit your project.

## Licence

MIT. See [LICENSE](LICENSE).
