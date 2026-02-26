---
theme: mistica
mistica:
    skin: telefonica
    mode: light
title: Reducing AI FOMO
---

# Reducing AI FOMO

**A 10-minute honest talk**

---

# What you're feeling has a name

## AI Fear Of Missing Out

> "Every day a new model. Every week a new tool. Everyone seems to know more than you."

That feeling is real. And it's not an accident.

---

# There is big money making you feel this way

- AI companies compete for attention
- Hype cycles are a product strategy
- The noise is designed to feel urgent

*Being aware of this doesn't make you cynical. It makes you clearer.*

---

# What I'm trying to do here

This talk has a simple success metric:

| If you leave feeling... | Result |
|---|---|
| More FOMO | I failed |
| Less FOMO | I succeeded |

No pressure. Just 10 minutes.

---

# Let's be honest about where we are

<!-- TODO: 🎨 VISUAL — DnD character at lvl 1 looking up at a lvl 12 character -->

- AI has been moving fast. Some people are already **Level 12**.
- You might be at **Level 1**.
- Realizing this gap is exactly what spikes the FOMO.

---

# We're not going to Level 12 today

**And that's fine.**

The goal of these slides:

> Get you from **Level 1 → Level 2**

Concrete. Achievable. Useful.

---

# First: understand what you're actually using

<!-- TODO: 🖼️ SCREENSHOTS — Copilot, Claude Code, Cursor, Codex UI -->

| Clients (the interface) | Models (the brain) |
|---|---|
| GitHub Copilot | GPT-4o |
| Claude Code | Claude Opus/Sonnet |
| Cursor | Gemini |
| Windsurf | Mistral |
| Codex | ... |

They are **separate things**. You can mix and match.

---

# Does pairing client + model matter?

There's a debate:

**Camp A:** The specific client+model pair creates a different experience — they're tuned together.

**Camp B (my view):** The UX differs. The output quality? Not significantly. Maybe a rounding error %.

**My recommendation:**

> Use the client you're most comfortable with.
> What actually matters is the **model** and **how you talk to it**.

---

# Level 2 is about *how* you interact

The client is just a window.

The model is the engine.

**Your prompts, context, and structure** are the steering wheel.

*That's what we're going to improve.*

---

# Before we go deeper: the buzzwords

Let's name them so they stop sounding scary:

- **Agents** — AI operating in multi-step, autonomous loops
- **Skills** — reusable, scoped instructions you give the agent
- **MCPs** — Model Context Protocol; structured tools the model can call

---

# Agents: what you're already using

<!-- TODO: 🖼️ SCREENSHOT — Plan mode + Implement mode UI -->

In tools like Claude Code, you're already running **two agents**:

| Mode | What it does |
|---|---|
| **Plan mode** | Thinks, reasons, proposes steps |
| **Implement mode** | Executes, writes, runs commands |

You've been using agents. You just didn't call them that.

---

# What is `AGENTS.md`?

A file you put at the root of your project.

The model reads it automatically at the start of every session.

**It's your standing instructions.** Think of it as:

> "Here's the context you always need. Here's how I work. Here's what matters."

⚠️ Current debate: `AGENTS.md` fills the context window fast.
Is it worth it if the model could discover most of that info anyway?

---

# Skills: a better alternative

Instead of dumping everything in `AGENTS.md`:

**Skills** are modular, on-demand instruction sets.

- Loaded only when relevant
- Scoped to a specific task
- Don't pollute the context

> *AGENTS.md = always-on background noise*
>
> *Skills = called when needed, focused, efficient*

---

# MCPs: giving the model real tools

<!-- TODO: 🖼️ SCREENSHOT — GitHub MCP in action -->

**Model Context Protocol** = a standard way for models to call external tools.

Example: **GitHub MCP**

- Create issues
- Read PRs
- Search repos

The model doesn't browse GitHub. It calls a structured tool that does.

---

# Let's see a Skill in the wild

*Example: `/telefonica-slides`*

A skill that:

- Bootstraps a Slidev presentation with Telefonica/Mistica branding
- Accepts a file, URL, or inline text as input
- Generates properly structured slides automatically

```
/telefonica-slides ./docs/api.md
/telefonica-slides export pdf
```

One skill. Reusable. Consistent. No reinventing.

---

# Creating a skill: the recipe

1. Create a `SKILL.md` file
2. Add YAML frontmatter (`name`, `description`)
3. Write the procedure (what to do, in what order)
4. Keep it under ~500 lines
5. Point to reference files if needed (one level deep only)

**The description is critical** — it's how the agent decides *when* to use it.

---

# What makes a good Skill

✅ **Concise** — only include what the model doesn't already know

✅ **Specific description** — what it does AND when to use it

✅ **Progressive disclosure** — overview in SKILL.md, details in linked files

✅ **Low freedom for fragile tasks**, high freedom for judgment calls

✅ **Feedback loops** — run → validate → fix → repeat

---

# What makes a bad Skill

❌ Don't over-explain basics

❌ Don't give 5 options when one default + escape hatch works better

❌ Don't nest references more than one level deep

---

# What's happening in the wider team

**CDO level:**

- Agents and MCP sharing point (shared repo)
- Building reusable Skills across teams

**Video team:**

- Same approach, scoped to video workflows
- Specific MCPs and Skills for their context

*We're not guessing alone. We're figuring it out together.*

---

# Nothing is set in stone

- This space is 6–18 months old in practice
- Best practices are being written in real time
- Everyone is experimenting, including the people at Level 12

**That's not a warning. That's an invitation.**

---

# You made it

<!-- TODO: 🎨 VISUAL — same DnD illustration, character now at lvl 2, more confident -->

- You know what FOMO is and why it's manufactured
- You know the difference between clients and models
- You know what agents, skills, and MCPs actually are
- You know where to start

> **Level 2. Welcome.**
