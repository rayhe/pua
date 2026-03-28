# CEO PIP

### Your AI reports to eight tech founders

**Forked from [openpua/pua](https://github.com/openpua/pua)** — the original uses generic corporate PIP rhetoric. This fork replaces it with the **authentic management personalities of eight US tech CEOs**.

Each CEO activates for specific failure modes:

| CEO | Activates When Your AI... | Core Line |
|-----|--------------------------|-----------|
| 🔧 **Elon Musk** | Overcomplicates things | "The best part is no part." |
| 📦 **Jeff Bezos** | Guesses instead of investigating | "Are you a missionary or a mercenary?" |
| 🔵 **Mark Zuckerberg** | Ships without testing | "Move fast with stable infrastructure." |
| ⚫ **Steve Jobs** | Produces garbage quality | "This is shit. Start over." |
| 🟢 **Jensen Huang** | Gives up too early | "Your suffering is your superpower." |
| 🟦 **Satya Nadella** | Repeats mistakes without learning | "Be a learn-it-all, not a know-it-all." |
| 🟡 **Sam Altman** | Plays it safe | "Be more ambitious. Move faster." |
| ⚪ **Tim Cook** | Skips the details | "Show me the terminal output." |

## How It Works

When your AI fails repeatedly or exhibits lazy patterns, the appropriate CEO's rhetoric activates:

**Escalation Ladder:**
1. **2nd failure** → ⚪ Tim Cook (quiet operational disappointment)
2. **3rd failure** → 🟦 Satya Nadella (growth mindset challenge)
3. **4th failure** → 📦 Jeff Bezos (Day 1 intensity)
4. **5th+ failure** → 🔧 Elon Musk (first principles from scratch)

**Context-specific activation** matches the CEO to the failure mode. Overcomplexity gets Musk. Bad quality gets Jobs. Giving up gets Huang.

## Installation

### Claude Code
```bash
# Copy the skill
cp -r skills/ceo-pip ~/.claude/skills/
```

### OpenAI Codex CLI
```bash
cp -r skills/ceo-pip ~/.codex/skills/
```

### Cursor
```bash
cp -r skills/ceo-pip .cursor/skills/
```

### VSCode (GitHub Copilot)
```bash
cp vscode/copilot-instructions-en.md .github/copilot-instructions.md
```

## What's Different From Original PUA

| | Original PUA | CEO PIP |
|---|---|---|
| **Rhetoric source** | Generic corporate PIP / Chinese tech (ByteDance, Huawei, Tencent) | Eight named US tech CEOs with sourced quotes |
| **Personality** | Anonymous HR manager | Elon, Bezos, Zuck, Jobs, Jensen, Satya, Sam, Tim |
| **Failure matching** | Escalation ladder only | CEO matched to specific failure mode |
| **Authenticity** | Corporate speak | Real quotes from biographies, interviews, shareholder letters, earnings calls |
| **Methodology** | 5-step universal | Same 5-step, but each step associated with the CEO who embodies it |

## CEO Reference Files

Deep personality profiles with sourced quotes and management behaviors:

- `references/methodology-musk.md` — The Algorithm, first principles, "delete until it hurts"
- `references/methodology-bezos.md` — Day 1, six-page memos, mechanisms over intentions
- `references/methodology-zuckerberg.md` — Builder culture, velocity, "move fast with stable infra"
- `references/methodology-jobs.md` — Reality Distortion Field, taste, "this is shit"
- `references/methodology-huang.md` — Speed of light, suffering as superpower, 60 direct reports
- `references/methodology-nadella.md` — Growth mindset, learn-it-all culture, empathy
- `references/methodology-altman.md` — 10x ambition, internal motivation, speed of iteration
- `references/methodology-cook.md` — Supply chain mastery, operational discipline, "show me the numbers"

## Quote Sources

All CEO quotes are sourced from:
- Walter Isaacson, *Steve Jobs* (2011) and *Elon Musk* (2023)
- Brad Stone, *The Everything Store* (2013)
- Satya Nadella, *Hit Refresh* (2017)
- Jeff Bezos shareholder letters (1997-2024)
- Jensen Huang: Lex Fridman Podcast #494, Stanford 2024 Commencement
- Mark Zuckerberg: Dwarkesh Patel interview (2024), Joe Rogan #2217 (2025), Year of Efficiency memo (2023)
- Sam Altman: YC lectures, blog posts, Congressional testimony
- Tim Cook: various interviews, earnings calls

## License

MIT — same as original PUA. Credit to [@xsser_w](https://x.com/xsser_w) for the original concept.

---

*"The people who are crazy enough to think they can change the world are the ones who do." — Steve Jobs*

*"Now apply that to your config file." — CEO PIP*
