---
theme: mistica
mistica:
    skin: telefonica
    mode: light
title: Reducing AI FOMO
layout: cover
---

# Reducing AI FOMO

## VIDEO Team - CafeterIA

<div style="position: absolute; bottom: 2rem; left: 50%; transform: translateX(-50%); font-size: 0.8rem; color: var(--mistica-color-textSecondary);">
27 February 2026
</div>

---
layout: brand
section: 1
---

# Fear Of Missing Out

## What you're feeling has a name


---
layout: default
---

# There is big money making you feel this way

> Every day a new model. Every week a new tool. Everyone seems to know more than you.


<div style="display: flex; flex-direction: column; gap: 1.25rem; margin-top: 1.5rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <MisticaIcon name="bar-chart" :size="28" color="var(--mistica-color-error)" />
    <span><strong>$600B+</strong> invested in AI infra this year -> they <em>need</em> you to feel behind</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <MisticaIcon name="trend-up" :size="28" color="var(--mistica-color-warning)" />
    <span>Google & Microsoft paying influencers -> <strong>$400–600K</strong> to flood your feed</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <MisticaIcon name="bell" :size="28" color="var(--mistica-color-brand)" />
    <span>The noise is designed to feel <strong>urgent</strong> — it's a product strategy</span>
  </div>
</div>

<div style="margin-top: 1.5rem; width:70%">
  <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.5rem; background: var(--mistica-color-backgroundAlternative);">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 0.75rem;">
      <MisticaIcon name="lightbulb" :size="20" color="var(--mistica-color-warning)" />
      <span style="font-weight: 600; font-size: 0.9rem;">Remember</span>
    </div>
    <p style="margin: 0; font-size: 0.85rem; color: var(--mistica-color-textSecondary); line-height: 1.6;">There are <strong>$600 billion reasons</strong> for you to feel this way. Being aware of it makes you <span style="color: var(--mistica-color-textBrand); font-weight: 600;">clearer</span>.</p>
  </div>
</div>

<div style="position: absolute; bottom: 5.5rem; font-size: 0.85rem; color: var(--mistica-color-textSecondary);">
  Source: <a href="https://www.estrategiadeproducto.com/p/negocio-crearte-ansiedad-con-la-ia" style="color: var(--mistica-color-textSecondary);">El negocio de crearte ansiedad con la IA</a> — Simón Muñoz
</div>

---

# What I'm trying to do here

This talk has a simple success metric:

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem; margin-top: 1.5rem;">
  <StatCard label="If you leave with more FOMO" value="I failed" description="Let's avoid this" :trend="-100" />
  <StatCard label="If you leave with less FOMO" value="I succeeded" description="This is the goal" :trend="100" />
</div>

<div style="text-align: center; margin-top: 2rem; color: var(--mistica-color-textSecondary); font-size: 0.95rem;">
No pressure. Just 15 minutes.
</div>

---
layout: two-col
---

# Where we are

<div style="margin-top: 2rem;">

- AI has been moving fast. Some people are already **Level 12**.
- This talk targets **Level 1**.
- Realizing this gap spikes the FOMO.
- Knowing the field reduces the FOMO.

<div div style="display: flex; flex-direction: column; align-items: center; justify-content: center; margin-top: 2em;">
GOAL: Get from Level 1 → Level 2
</div>

</div>

::right::

<div style="display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100%; gap: 1.5rem;">
  <div style="text-align: center;">
    <div style="display: flex; align-items: center; justify-content: center; gap: 0.5rem; margin-bottom: 0.5rem;">
      <MisticaIcon name="trophy" :size="40" color="var(--mistica-color-warning)" />
    </div>
    <span style="font-size: 2rem; font-weight: 700; color: var(--mistica-color-textBrand);">Lvl 10</span>
    <p style="margin: 0.25rem 0 0; font-size: 0.75rem; color: var(--mistica-color-textSecondary);">Some people</p>
  </div>
  <div style="width: 2px; height: 40px; background: var(--mistica-color-divider);"></div>
  <div style="text-align: center;">
    <div style="display: flex; align-items: center; justify-content: center; gap: 0.5rem; margin-bottom: 0.5rem;">
      <MisticaIcon name="person" :size="40" color="var(--mistica-color-neutralMedium)" />
    </div>
    <span style="font-size: 2rem; font-weight: 700; color: var(--mistica-color-textSecondary);">Lvl 1</span>
    <p style="margin: 0.25rem 0 0; font-size: 0.75rem; color: var(--mistica-color-textSecondary);">We</p>
  </div>
</div>

---
layout: brand
section: 2
---

# Understanding the tools

Models, clients, and how they fit together

---
layout: two-col
---

# Models and clients are separate things

<div style="margin-top: 1rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem; margin-bottom: 1rem;">
    <MisticaIcon name="presentation" :size="24" color="var(--mistica-color-brand)" />
    <span><strong>Client</strong> = the interface you see</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; margin-bottom: 1rem;">
    <MisticaIcon name="lightbulb" :size="24" color="var(--mistica-color-warning)" />
    <span><strong>Model</strong> = the brain doing the work</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <MisticaIcon name="refresh" :size="20" color="var(--mistica-color-success)" />
    <span style="font-size: 0.85rem; color: var(--mistica-color-textSecondary);">You can <strong>mix and match</strong>.</span>
  </div>
</div>

<img src="/screenshots/lang-models-copilot.png" style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); width: 100%; margin-top:1em;" />

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; gap: 1rem; padding: 0.5rem;">
  <img src="/screenshots/claude-code-models.png" style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); width: 100%;" />
</div>

---

# The clients

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem; margin-top: 1rem;">
  <div>
    <div style="display: flex; flex-direction: column; gap: 0.75rem;">
      <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
        <MisticaIcon name="code" :size="20" color="var(--mistica-color-brand)" />
        <span style="font-size: 0.9rem; font-weight: 600;">GitHub Copilot</span>
      </div>
      <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
        <MisticaIcon name="lightning" :size="20" color="var(--mistica-color-brand)" />
        <span style="font-size: 0.9rem; font-weight: 600;">Claude Code</span>
      </div>
      <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
        <MisticaIcon name="edit-pencil" :size="20" color="var(--mistica-color-brand)" />
        <span style="font-size: 0.9rem; font-weight: 600;">Cursor</span>
      </div>
      <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
        <MisticaIcon name="cloud" :size="20" color="var(--mistica-color-brand)" />
        <span style="font-size: 0.9rem; font-weight: 600;">Windsurf</span>
      </div>
      <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
        <MisticaIcon name="settings" :size="20" color="var(--mistica-color-brand)" />
        <span style="font-size: 0.9rem; font-weight: 600;">Codex</span>
      </div>
      <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
        <MisticaIcon name="rocket" :size="20" color="var(--mistica-color-brand)" />
        <span style="font-size: 0.9rem; font-weight: 600;">OpenCode</span>
      </div>
    </div>
  </div>
  <div style="display: flex; align-items: center; justify-content: center;">
    <img src="/screenshots/opencode.png" style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); max-width: 100%; max-height: 320px;" />
  </div>
</div>

---

# Does pairing client + model matter?

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1.25rem; margin-top: 1.5rem;">
  <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem;">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 0.75rem;">
      <span style="font-weight: 600; font-size: 0.9rem;">Opinion A</span>
    </div>
    <p style="margin: 0; font-size: 0.85rem; line-height: 1.6; color: var(--mistica-color-textSecondary);">The specific client+model pair creates a different experience; they're <strong>tuned together</strong>.</p>
  </div>
  <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem;">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 0.75rem;">
      <span style="font-weight: 600; font-size: 0.9rem;">Opinion B</span>
    </div>
    <p style="margin: 0; font-size: 0.85rem; line-height: 1.6; color: var(--mistica-color-textSecondary);">The UX (devExperience) differs. The output quality, <strong>Not significantly</strong>.</p>
  </div>
</div>

<div style="display: flex; justify-content: center; margin-top: 1.5rem;">
  <div style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; background: var(--mistica-color-backgroundContainer); width: 70%;">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 0.75rem;">
      <MisticaIcon name="star" :size="20" color="var(--mistica-color-brand)" />
      <span style="font-weight: 600; font-size: 0.9rem; color: var(--mistica-color-textBrand);">My recommendation</span>
    </div>
    <p style="margin: 0 0 0.5rem; font-size: 0.85rem; line-height: 1.6;">Use the client you're most comfortable with.</p>
    <p style="margin: 0; font-size: 0.85rem; line-height: 1.6; color: var(--mistica-color-textSecondary);">What actually matters is the <strong>model</strong> and <strong>how you talk to it</strong>.</p>
  </div>
</div>

---
layout: brand
---

# Level 2: *how* you interact

The client is just a window. The model is the engine.

**Your prompts, context, and structure** is what actually matter

---
layout: brand
section: 3
---

# The buzzwords

Let's name them so they stop sounding scary

---
layout: default
---

# The buzzwords

<div style="display: flex; align-items: center; justify-content: center; flex: 1; margin-top: 1rem;">
  <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1.25rem; width: 100%;">
    <div style="border: 2px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center;">
      <MisticaIcon name="settings" :size="32" color="var(--mistica-color-brand)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Agents</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">AI operating in multi-step, autonomous loops</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="lightning" :size="32" color="var(--mistica-color-warning)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Skills</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Reusable, scoped instructions you give the agent</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="link" :size="32" color="var(--mistica-color-success)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">MCPs</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Model Context Protocol; structured tools the model can call</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="search" :size="32" color="var(--mistica-color-error)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">RAG</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Retrieval-Augmented Generation; feeding external data to the model</p>
    </div>
  </div>
</div>

---
layout: default
---

# The buzzwords

<div style="display: flex; align-items: center; justify-content: center; flex: 1; margin-top: 1rem;">
  <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1.25rem; width: 100%;">
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="settings" :size="32" color="var(--mistica-color-brand)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Agents</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">AI operating in multi-step, autonomous loops</p>
    </div>
    <div style="border: 2px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center;">
      <MisticaIcon name="lightning" :size="32" color="var(--mistica-color-warning)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Skills</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Reusable, scoped instructions you give the agent</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="link" :size="32" color="var(--mistica-color-success)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">MCPs</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Model Context Protocol; structured tools the model can call</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="search" :size="32" color="var(--mistica-color-error)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">RAG</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Retrieval-Augmented Generation; feeding external data to the model</p>
    </div>
  </div>
</div>

---
layout: default
---

# The buzzwords

<div style="display: flex; align-items: center; justify-content: center; flex: 1; margin-top: 1rem;">
  <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1.25rem; width: 100%;">
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="settings" :size="32" color="var(--mistica-color-brand)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Agents</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">AI operating in multi-step, autonomous loops</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="lightning" :size="32" color="var(--mistica-color-warning)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Skills</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Reusable, scoped instructions you give the agent</p>
    </div>
    <div style="border: 2px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center;">
      <MisticaIcon name="link" :size="32" color="var(--mistica-color-success)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">MCPs</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Model Context Protocol; structured tools the model can call</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="search" :size="32" color="var(--mistica-color-error)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">RAG</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Retrieval-Augmented Generation; feeding external data to the model</p>
    </div>
  </div>
</div>

---
layout: default
---

# The buzzwords

<div style="display: flex; align-items: center; justify-content: center; flex: 1; margin-top: 1rem;">
  <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1.25rem; width: 100%;">
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="settings" :size="32" color="var(--mistica-color-brand)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Agents</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">AI operating in multi-step, autonomous loops</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="lightning" :size="32" color="var(--mistica-color-warning)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">Skills</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Reusable, scoped instructions you give the agent</p>
    </div>
    <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center; opacity: 0.3;">
      <MisticaIcon name="link" :size="32" color="var(--mistica-color-success)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">MCPs</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Model Context Protocol; structured tools the model can call</p>
    </div>
    <div style="border: 2px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); padding: 1.25rem; text-align: center;">
      <MisticaIcon name="search" :size="32" color="var(--mistica-color-error)" />
      <h3 style="margin: 0.5rem 0 0.25rem; font-size: 1rem;">RAG</h3>
      <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">Retrieval-Augmented Generation; feeding external data to the model</p>
    </div>
  </div>
</div>

---
layout: two-col
---

# Agents: you're already using one

An agent = AI that takes actions in a loop, using tool calls and observations to make progress toward a goal

Claude Code has two <span>modes</span>:

<div style="margin-top: 1.5rem; border-radius: var(--mistica-border-radius-container); overflow: hidden; border: 1px solid var(--mistica-color-border);">
  <div style="display: grid; grid-template-columns: 7rem 1fr; background: rgba(0, 100, 210, 0.1); font-weight: 600; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem;">Mode</div>
    <div style="padding: 0.6rem 1rem;">What it does</div>
  </div>
  <div style="display: grid; grid-template-columns: 7rem 1fr; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem; font-weight: 600;">Plan</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Thinks, reasons, proposes steps</div>
  </div>
  <div style="display: grid; grid-template-columns: 7rem 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.05);">
    <div style="padding: 0.6rem 1rem; font-weight: 600;">Act</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Executes, writes, runs commands</div>
  </div>
</div>

<div style="margin-top: 2em;">
The modes control how much <span>autonomy</span> you give it.
</div>

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; gap: 1.5rem; padding: 1rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="search" :size="28" color="var(--mistica-color-brand)" />
    <div>
      <div style="font-weight: 600; font-size: 0.9rem;">Plan</div>
      <div style="font-size: 0.75rem; color: var(--mistica-color-textSecondary);">Think before acting</div>
    </div>
  </div>
  <div style="text-align: center; color: var(--mistica-color-textSecondary);">
    <MisticaIcon name="arrow-down" :size="20" />
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 1rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="rocket" :size="28" color="var(--mistica-color-success)" />
    <div>
      <div style="font-weight: 600; font-size: 0.9rem;">Act</div>
      <div style="font-size: 0.75rem; color: var(--mistica-color-textSecondary);">Execute the plan</div>
    </div>
  </div>
  <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary); text-align: center;">You've been using an agent. You just didn't call it that.</p>
</div>

---
layout: two-col
---

# What is `AGENTS.md`?

We're using an agent. We write down the instructions and give it context.

How do you tell it about the project? **We write it down.**

If we are re-writing a similar context every single time, the idea to "reuse" a basic context

> Initially I read it as `CONSTITUTION.md`

Idea:  A file you put at the root of your project. just **instructions** that always are considered.

The model reads it **automatically** at the start of every session.

> "Here are the rules you must follow ALWAYS"

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; gap: 1rem; padding: 1rem;">
  <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1rem; background: var(--mistica-color-backgroundContainer); font-family: monospace; font-size: 0.75rem; line-height: 1.6;">
    <div style="color: var(--mistica-color-textSecondary);"># AGENTS.md</div>
    <div style="margin-top: 0.5rem;">This project uses TypeScript.</div>
    <div>Run tests with: npm test</div>
    <div>Follow conventional commits.</div>
    <div>Never push to main directly.</div>
    <div>Error codes are mandatory in log calls, every <code>logger.error()</code> needs a <code>code</code></div>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.5rem; padding: 0.75rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="warning" :size="20" color="var(--mistica-color-warning)" />
    <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary); line-height: 1.4;">Current debate: fills the context window fast. Is it worth it if the model could discover most of that info anyway?</p>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.5rem; padding: 0.75rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="warning" :size="20" color="var(--mistica-color-warning)" />
    <p style="margin: 0; font-size: 0.8rem; color: var(--mistica-color-textSecondary); line-height: 1.4;">Avoid redundant info that the agent will assume anyway</p>
  </div>
</div>

---
layout: default
---

# Same idea, different names

Each client has its own version of the "project instructions" file:

<div style="margin-top: 1.5rem; border-radius: var(--mistica-border-radius-container); overflow: hidden; border: 1px solid var(--mistica-color-border);">
  <div style="display: grid; grid-template-columns: 1fr 1fr; background: rgba(0, 100, 210, 0.1); font-weight: 600; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem;">File</div>
    <div style="padding: 0.6rem 1rem;">Client</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">CLAUDE.md</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Claude Code</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.05);">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.cursorrules</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Cursor</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.windsurfrules</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Windsurf</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.05);">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.github/copilot-instructions.md</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">GitHub Copilot</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.clinerules</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Cline</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.05);">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">AGENTS.md</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Codex / generic</div>
  </div>
</div>

<p style="margin-top: 1.25rem; font-size: 0.85rem; color: var(--mistica-color-textSecondary);">Different filename, <strong>same concept</strong>: persistent context the model reads at the start of every session.</p>

---
layout: default
---

# Same idea, different names

Each client has its own version of the "project instructions" file:

<div style="margin-top: 1.5rem; border-radius: var(--mistica-border-radius-container); overflow: hidden; border: 1px solid var(--mistica-color-border);">
  <div style="display: grid; grid-template-columns: 1fr 1fr; background: rgba(0, 100, 210, 0.1); font-weight: 600; font-size: 0.85rem;">
    <div style="padding: 0.6rem 1rem;">File</div>
    <div style="padding: 0.6rem 1rem;">Client</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; opacity: 0.3;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">CLAUDE.md</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Claude Code</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.05); opacity: 0.3;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.cursorrules</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Cursor</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; opacity: 0.3;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.windsurfrules</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Windsurf</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.05); opacity: 0.3;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.github/copilot-instructions.md</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">GitHub Copilot</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; opacity: 0.3;">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">.clinerules</div>
    <div style="padding: 0.6rem 1rem; color: var(--mistica-color-textSecondary);">Cline</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; font-size: 0.85rem; background: rgba(0, 100, 210, 0.15); border-left: 3px solid var(--mistica-color-brand);">
    <div style="padding: 0.6rem 1rem; font-weight: 600; font-family: monospace;">AGENTS.md</div>
    <div style="padding: 0.6rem 1rem;">Codex / generic</div>
  </div>
</div>

<p style="margin-top: 1.25rem; font-size: 0.85rem; color: var(--mistica-color-textSecondary);">Different filename, <strong>same concept</strong>: persistent context the model reads at the start of every session.</p>

---
layout: two-col
---

# Skills: a better alternative

Instead of dumping everything in `AGENTS.md`:

**Skills** are modular, <span style="color: var(--mistica-color-brand); font-weight: 600;">on-demand instruction sets</span>.

<ul style="list-style: disc; padding-left: 1.25rem; margin: 0.75rem 0; font-size: 0.9rem; line-height: 1.8;">
  <li>Loaded <strong>only when relevant</strong></li>
  <li>Scoped to a <strong>specific task</strong></li>
  <li>Don't pollute the context window</li>
  <li>Invoked via <strong>slash commands</strong> (<code>/skill-name</code>)</li>
</ul>

<div style="display: flex; flex-direction: column; justify-content: center; padding: 1rem;">
  <img src="/screenshots/skills-input.png" style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); width: 100%;" />
</div>

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; gap: 1rem; padding: 1rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 1rem; border-radius: var(--mistica-border-radius-container); border: 1px solid var(--mistica-color-border); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="cloud" :size="24" color="var(--mistica-color-neutralMedium)" />
    <div>
      <div style="font-weight: 600; font-size: 0.85rem;">AGENTS.md</div>
      <div style="font-size: 0.75rem; color: var(--mistica-color-textSecondary);">Always-on background noise</div>
    </div>
  </div>
  <div style="text-align: center; font-size: 0.8rem; color: var(--mistica-color-textSecondary);">vs</div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 1rem; border-radius: var(--mistica-border-radius-container); border: 1px solid var(--mistica-color-borderSelected); background: var(--mistica-color-backgroundContainer);">
    <MisticaIcon name="lightning" :size="24" color="var(--mistica-color-brand)" />
    <div>
      <div style="font-weight: 600; font-size: 0.85rem; color: var(--mistica-color-textBrand);">Skills</div>
      <div style="font-size: 0.75rem; color: var(--mistica-color-textSecondary);">Called when needed, focused, efficient</div>
    </div>
  </div>
</div>
---
layout: two-col
---

# MCPs: giving the model real tools

**Model Context Protocol** = a standard way for models to call external tools.

The model doesn't browse GitHub. It calls a **structured tool** that does.

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; gap: 0.75rem; padding: 1rem;">
  <div style="font-weight: 600; font-size: 0.85rem; margin-bottom: 0.25rem;">Example: GitHub MCP</div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.75rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="flag" :size="20" color="var(--mistica-color-success)" />
    <span style="font-size: 0.85rem;">Create issues</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.75rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="eye" :size="20" color="var(--mistica-color-brand)" />
    <span style="font-size: 0.85rem;">Read PRs</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.75rem; border-radius: var(--mistica-border-radius-container); background: var(--mistica-color-backgroundAlternative);">
    <MisticaIcon name="search" :size="20" color="var(--mistica-color-warning)" />
    <span style="font-size: 0.85rem;">Search repos</span>
  </div>
  <img src="/screenshots/mcp-server.png" style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); width: 100%; margin-top: 0.5rem;" />
</div>

---
layout: default
---

# Using MCP Servers

<div style="display: flex; gap: 1rem; align-items: flex-start; justify-content: center; flex: 1; margin-top:4em;">
  <img src="/screenshots/mcp-1.png" style="flex: 1; border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); min-width: 0;" />
  <img src="/screenshots/mcp-2.png" style="flex: 1; border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); min-width: 0;" />
  <img src="/screenshots/mcp-3.png" style="flex: 1; border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); min-width: 0;" />
</div>

---
layout: brand
section: 4
---

# Skills in practice

How to create, use, and share them

---

# Let's see a Skill in the wild

*Example: `/telefonica-slides`*

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin: 1.5rem; 0 1.5rem 0;">
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <MisticaIcon name="presentation" :size="48" color="var(--mistica-color-brand)" />
    <span style="font-size: 0.85rem;">Bootstraps a Slidev presentation with Telefonica branding</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <MisticaIcon name="copy" :size="48" color="var(--mistica-color-success)" />
    <span style="font-size: 0.85rem;">Accepts a file, URL, or inline text as input</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <MisticaIcon name="settings" :size="48" color="var(--mistica-color-warning)" />
    <span style="font-size: 0.85rem;">Generates properly structured slides automatically</span>
  </div>
</div>

Examples:

```bash
/telefonica-slides ./docs/api.md
/telefonica-slides summarize the contents from ...
/telefonica-slides export pdf
/telefonica-slides create a pdf
```

<div style="margin-top: 1rem; font-size: 1rem; color: var(--mistica-color-textSecondary);">
One skill. Reusable steps, workflow and prompt.
</div>

---
layout: two-col
---

# Creating a skill: the recipe

<div style="display: flex; flex-direction: column; gap: 0.75rem; margin-top: 1rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <span style="background: var(--mistica-color-brand); color: white; width: 28px; height: 28px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.8rem; flex-shrink: 0;">1</span>
    <span style="font-size: 0.9rem;">Create a <code>SKILL.md</code> file</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <span style="background: var(--mistica-color-brand); color: white; width: 28px; height: 28px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.8rem; flex-shrink: 0;">2</span>
    <span style="font-size: 0.9rem;">Add YAML frontmatter (<code>name</code>, <code>description</code>)</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <span style="background: var(--mistica-color-brand); color: white; width: 28px; height: 28px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.8rem; flex-shrink: 0;">3</span>
    <span style="font-size: 0.9rem;">Write the procedure</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <span style="background: var(--mistica-color-brand); color: white; width: 28px; height: 28px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.8rem; flex-shrink: 0;">4</span>
    <span style="font-size: 0.9rem;">Keep it under ~500 lines</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <span style="background: var(--mistica-color-brand); color: white; width: 28px; height: 28px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.8rem; flex-shrink: 0;">5</span>
    <span style="font-size: 0.9rem;">Point to reference files (one level deep only)</span>
  </div>
</div>

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; padding: 1rem;">
  <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-container); padding: 1rem; background: var(--mistica-color-backgroundContainer); font-family: monospace; font-size: 0.7rem; line-height: 1.7;">
    <div style="color: var(--mistica-color-textSecondary);">---</div>
    <div>name: telefonica-slides</div>
    <div>description: Bootstrap a Slidev</div>
    <div>&nbsp;&nbsp;presentation with Mistica theme</div>
    <div style="color: var(--mistica-color-textSecondary);">---</div>
    <div style="margin-top: 0.5rem;">## Procedure</div>
    <div>1. Read the input source</div>
    <div>2. Generate slide structure</div>
    <div>3. Apply Mistica layout</div>
    <div>4. Run slidev dev to validate</div>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem; margin-top: 0.75rem;">
    <MisticaIcon name="information" :size="18" color="var(--mistica-color-brand)" />
    <span style="font-size: 0.8rem; color: var(--mistica-color-textSecondary);">The <strong>description</strong> is critical: how the agent decides <em>when</em> to use it.</span>
  </div>
</div>

---
layout: default
---

# `/telefonica-slides`

```md{1-6|10-11|13-14|16-17|19-20|all}
---
name: telefonica-slides
description: Creates branded presentations using ...
metadata:
  tags: []...
---

## When to use this skill

## Inputs
...

## Procedure
...

## Output format
...

## Examples
...
```


---
layout: two-col
---

# What makes a good Skill

<div style="display: flex; flex-direction: column; gap: 1rem; margin-top: 1.5rem;">
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="check" :size="22" color="var(--mistica-color-success)" />
    <span style="font-size: 0.9rem;"><strong>Concise</strong> — only include what the model doesn't already know</span>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="check" :size="22" color="var(--mistica-color-success)" />
    <span style="font-size: 0.9rem;"><strong>Specific description</strong> — what it does AND when to use it</span>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="check" :size="22" color="var(--mistica-color-success)" />
    <span style="font-size: 0.9rem;"><strong>Progressive disclosure</strong> — overview in SKILL.md, details in linked files</span>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="check" :size="22" color="var(--mistica-color-success)" />
    <span style="font-size: 0.9rem;"><strong>Feedback loops</strong> — run → validate → fix → repeat</span>
  </div>
</div>

::right::

# What makes a bad Skill

<div style="display: flex; flex-direction: column; gap: 1rem; margin-top: 1.5rem;">
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="close" :size="22" color="var(--mistica-color-error)" />
    <span style="font-size: 0.9rem;">Don't <strong>over-explain</strong> basics</span>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="close" :size="22" color="var(--mistica-color-error)" />
    <span style="font-size: 0.9rem;">Don't give <strong>5 options</strong> when one default + escape hatch works</span>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.75rem;">
    <MisticaIcon name="close" :size="22" color="var(--mistica-color-error)" />
    <span style="font-size: 0.9rem;">Don't nest references <strong>more than one level</strong> deep</span>
  </div>
</div>

---
layout: brand
section: 5
---

# What's happening around us

Teams are already building on this

---
layout: two-col
---

# What's happening in the wider team

<div style="margin-top: 1rem;">

**CDO level:**

- Agents and MCP sharing point (shared repo)
- Building reusable Skills across teams

**Video team:**

- Same approach, scoped to video workflows
- Specific MCPs and Skills for their context

</div>

<div style="display: flex; align-items: center; gap: 0.5rem; margin-top: 1rem;">
  <MisticaIcon name="team" :size="20" color="var(--mistica-color-success)" />
  <span style="font-size: 0.8rem; color: var(--mistica-color-textSecondary);">We're figuring it out <strong>together</strong>.</span>
</div>

::right::

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%; padding: 0.5rem;">
  <img src="/screenshots/video-agents.png" style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); width: 100%;" />
</div>

---
layout: brand
---

# Nothing is set in stone

<div style="color: white;">
 <ul>
  <li style="color: white;">This space is 2 months old in practice</li>
  <li style="color: white;">Best practices are being written in real time</li>
  <li style="color: white;">Everyone is experimenting, including the people at Level</li>
  </ul>
</div>


---
layout: final
---

<div style="text-align: center; margin-top: 2rem;">
  <MisticaIcon name="trophy" :size="40" color="var(--mistica-color-warning)" />
  <p style="font-size: 1.5rem; font-weight: 700; color: var(--mistica-color-textBrand); margin: 0.5rem 0 0;">Thanks</p>
</div>
