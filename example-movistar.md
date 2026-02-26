---
theme: ../
mistica:
  skin: movistar
  mode: light
---

# Mistica Theme

## Movistar Skin

---
layout: brand
---

# Mistica Meets Slidev

A Slidev theme powered by Telefonica's Mistica design system

---

# Basic Line Highlighting

Use `{lines}` after the language identifier to highlight specific lines.

```md {2,4,5}
---
theme: mistica
mistica:
  skin: movistar
  mode: light
---

# Your Presentation Here

## IN SIMPLE MARKDOWN
```

---

# Step-by-Step Highlighting

Click through to reveal highlighted sections progressively.

```ts {1-4|7-9}
---
theme: mistica
mistica:
  skin: movistar
  mode: light
---

# Your Presentation Here

## IN SIMPLE MARKDOWN
```

---
layout: brand
---

# Design Tokens

CSS custom properties from Mistica

---
layout: two-col
---

# Background Colors

```c
var(--mistica-color-background)
var(--mistica-color-backgroundAlternative)
var(--mistica-color-backgroundBrand)
var(--mistica-color-backgroundBrandSecondary)
var(--mistica-color-backgroundContainer)
var(--mistica-color-backgroundContainerBrand)
var(--mistica-color-backgroundOverlay)
```

::right::

<div style="display: flex; flex-direction: column; gap: 0.5rem; margin-top: 1rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-background); border: 1px solid var(--mistica-color-border);"></div>
    <code style="font-size: 0.75rem;">background</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-backgroundAlternative); border: 1px solid var(--mistica-color-border);"></div>
    <code style="font-size: 0.75rem;">backgroundAlternative</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-backgroundBrand);"></div>
    <code style="font-size: 0.75rem;">backgroundBrand</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-backgroundBrandSecondary);"></div>
    <code style="font-size: 0.75rem;">backgroundBrandSecondary</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-backgroundContainer); border: 1px solid var(--mistica-color-border);"></div>
    <code style="font-size: 0.75rem;">backgroundContainer</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-backgroundContainerBrand);"></div>
    <code style="font-size: 0.75rem;">backgroundContainerBrand</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem;">
    <div style="width: 48px; height: 32px; border-radius: 6px; background: var(--mistica-color-backgroundOverlay);"></div>
    <code style="font-size: 0.75rem;">backgroundOverlay</code>
  </div>
</div>

---
layout: two-col
---

# Text Colors

```c
var(--mistica-color-textPrimary)
var(--mistica-color-textPrimaryInverse)
var(--mistica-color-textSecondary)
var(--mistica-color-textLink)
var(--mistica-color-textBrand)
var(--mistica-color-textActivated)
```

::right::

<div style="display: flex; flex-direction: column; gap: 0.75rem; margin-top: 1rem;">
  <p style="color: var(--mistica-color-textPrimary); font-weight: 600; margin: 0; font-size: 0.95rem;">textPrimary — The quick brown fox</p>
  <p style="color: var(--mistica-color-textPrimaryInverse); font-weight: 600; margin: 0; font-size: 0.95rem; background: var(--mistica-color-backgroundBrand); padding: 6px 10px; border-radius: 6px;">textPrimaryInverse</p>
  <p style="color: var(--mistica-color-textSecondary); font-weight: 600; margin: 0; font-size: 0.95rem;">textSecondary — Supporting text</p>
  <p style="color: var(--mistica-color-textLink); font-weight: 600; margin: 0; font-size: 0.95rem;">textLink — Click here to learn more</p>
  <p style="color: var(--mistica-color-textBrand); font-weight: 600; margin: 0; font-size: 0.95rem;">textBrand — Brand expression</p>
  <p style="color: var(--mistica-color-textActivated); font-weight: 600; margin: 0; font-size: 0.95rem;">textActivated — Active state</p>
</div>

---

# Brand & Status Colors

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin-top: 1.5rem;">
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-brand);"></div>
    <code style="font-size: 0.75rem;">brand</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-brandHigh);"></div>
    <code style="font-size: 0.75rem;">brandHigh</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-inverse); border: 1px solid var(--mistica-color-border);"></div>
    <code style="font-size: 0.75rem;">inverse</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-success);"></div>
    <code style="font-size: 0.75rem;">success</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-warning);"></div>
    <code style="font-size: 0.75rem;">warning</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-error);"></div>
    <code style="font-size: 0.75rem;">error</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-promo);"></div>
    <code style="font-size: 0.75rem;">promo</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-highlight);"></div>
    <code style="font-size: 0.75rem;">highlight</code>
  </div>
  <div style="text-align: center;">
    <div style="height: 56px; border-radius: 12px; background: var(--mistica-color-negative);"></div>
    <code style="font-size: 0.75rem;">negative</code>
  </div>
</div>

---
layout: two-col
---

# Neutral & Border Colors

```c
/* Neutral */
var(--mistica-color-neutralHigh)
var(--mistica-color-neutralMedium)
var(--mistica-color-neutralLow)
var(--mistica-color-neutralLowAlternative)

/* Borders */
var(--mistica-color-divider)
var(--mistica-color-border)
var(--mistica-color-borderLow)
var(--mistica-color-borderHigh)
var(--mistica-color-borderSelected)
```

::right::

<div style="display: flex; flex-direction: column; gap: 0.4rem; margin-top: 0.5rem;">
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; background: var(--mistica-color-neutralHigh);"></div>
    <code style="font-size: 0.7rem;">neutralHigh</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; background: var(--mistica-color-neutralMedium);"></div>
    <code style="font-size: 0.7rem;">neutralMedium</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; background: var(--mistica-color-neutralLow);"></div>
    <code style="font-size: 0.7rem;">neutralLow</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; background: var(--mistica-color-neutralLowAlternative);"></div>
    <code style="font-size: 0.7rem;">neutralLowAlt</code>
  </div>
  <hr style="border: none; border-top: 1px solid var(--mistica-color-divider); width: 100%; margin: 0.25rem 0;">
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; border: 2px solid var(--mistica-color-border); background: transparent;"></div>
    <code style="font-size: 0.7rem;">border</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; border: 2px solid var(--mistica-color-borderLow); background: transparent;"></div>
    <code style="font-size: 0.7rem;">borderLow</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; border: 2px solid var(--mistica-color-borderHigh); background: transparent;"></div>
    <code style="font-size: 0.7rem;">borderHigh</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 40px; height: 28px; border-radius: 4px; border: 2px solid var(--mistica-color-borderSelected); background: transparent;"></div>
    <code style="font-size: 0.7rem;">borderSelected</code>
  </div>
</div>

---
layout: two-col
---

# UI & Control Colors

```c
var(--mistica-color-buttonPrimaryBackground)
var(--mistica-color-buttonPrimaryBackgroundHover)
var(--mistica-color-controlActivated)
var(--mistica-color-control)
var(--mistica-color-badge)
var(--mistica-color-appBarBackground)
var(--mistica-color-navigationBarBackground)
```

::right::

<div style="display: flex; flex-direction: column; gap: 0.6rem; margin-top: 1rem;">
  <div>
    <button style="background: var(--mistica-color-buttonPrimaryBackground); color: white; border: none; padding: 8px 24px; border-radius: var(--mistica-border-radius-button, 4px); font-weight: 600; font-size: 0.85rem; cursor: pointer;">Primary Button</button>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 20px; height: 20px; border-radius: 50%; background: var(--mistica-color-controlActivated);"></div>
    <code style="font-size: 0.7rem;">controlActivated</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 20px; height: 20px; border-radius: 50%; border: 2px solid var(--mistica-color-control); background: transparent;"></div>
    <code style="font-size: 0.7rem;">control</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <span style="background: var(--mistica-color-badge); color: white; padding: 2px 8px; border-radius: 10px; font-size: 0.75rem; font-weight: 600;">3</span>
    <code style="font-size: 0.7rem;">badge</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 48px; height: 28px; border-radius: 4px; background: var(--mistica-color-appBarBackground); border: 1px solid var(--mistica-color-border);"></div>
    <code style="font-size: 0.7rem;">appBarBackground</code>
  </div>
  <div style="display: flex; align-items: center; gap: 0.5rem;">
    <div style="width: 48px; height: 28px; border-radius: 4px; background: var(--mistica-color-navigationBarBackground); border: 1px solid var(--mistica-color-border);"></div>
    <code style="font-size: 0.7rem;">navigationBarBackground</code>
  </div>
</div>

---
layout: two-col
---

# Border Radius Tokens

```c
var(--mistica-border-radius-avatar)
var(--mistica-border-radius-bar)
var(--mistica-border-radius-button)
var(--mistica-border-radius-checkbox)
var(--mistica-border-radius-container)
var(--mistica-border-radius-indicator)
var(--mistica-border-radius-chip)
var(--mistica-border-radius-tag)
var(--mistica-border-radius-input)
var(--mistica-border-radius-popup)
var(--mistica-border-radius-sheet)
var(--mistica-border-radius-mediaSmall)
```

::right::

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 0.75rem; margin-top: 0.5rem;">
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-backgroundBrand); border-radius: var(--mistica-border-radius-avatar); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">avatar</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-button); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">button</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-container); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">container</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-input); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">input</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-popup); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">popup</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-sheet); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">sheet</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-chip); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">chip</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-tag); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">tag</code>
  </div>
  <div style="text-align: center;">
    <div style="width: 48px; height: 48px; background: var(--mistica-color-neutralLow); border-radius: var(--mistica-border-radius-mediaSmall); margin: 0 auto;"></div>
    <code style="font-size: 0.6rem;">mediaSmall</code>
  </div>
</div>

---
layout: brand
---

# Icon Library

56 bundled SVG icons per skin

---

# Icons (1/2)

<div style="display: grid; grid-template-columns: repeat(7, 1fr); gap: 0.4rem 0.25rem; text-align: center; margin-top: 0.75rem;">
  <figure style="margin: 0;"><MisticaIcon name="arrow-down" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">arrow-down</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="arrow-left" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">arrow-left</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="arrow-right" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">arrow-right</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="arrow-up" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">arrow-up</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="bar-chart" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">bar-chart</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="bell" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">bell</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="bookmark" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">bookmark</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="briefcase" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">briefcase</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="calendar" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">calendar</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="check" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">check</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="chevron-down" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">chevron-down</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="chevron-left" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">chevron-left</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="chevron-right" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">chevron-right</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="chevron-up" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">chevron-up</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="close" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">close</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="cloud" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">cloud</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="code" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">code</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="copy" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">copy</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="earth" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">earth</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="edit-pencil" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">edit-pencil</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="email" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">email</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="error" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">error</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="eye" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">eye</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="flag" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">flag</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="heart" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">heart</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="home" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">home</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="image" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">image</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="information" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">information</figcaption></figure>
</div>

---

# Icons (2/2)

<div style="display: grid; grid-template-columns: repeat(7, 1fr); gap: 0.4rem 0.25rem; text-align: center; margin-top: 0.75rem;">
  <figure style="margin: 0;"><MisticaIcon name="lightbulb" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">lightbulb</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="lightning" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">lightning</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="link" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">link</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="lock-closed" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">lock-closed</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="moon" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">moon</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="person" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">person</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="photo-camera" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">photo-camera</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="play-circle" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">play-circle</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="presentation" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">presentation</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="question" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">question</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="refresh" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">refresh</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="rocket" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">rocket</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="search" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">search</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="send" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">send</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="settings" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">settings</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="share" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">share</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="shopping-cart" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">shopping-cart</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="star" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">star</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="sun" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">sun</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="target" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">target</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="team" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">team</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="time" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">time</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="trash-can" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">trash-can</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="trend-down" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">trend-down</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="trend-up" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">trend-up</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="trophy" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">trophy</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="warning" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">warning</figcaption></figure>
  <figure style="margin: 0;"><MisticaIcon name="wifi" :size="28" /><figcaption style="font-size: 0.5rem; color: var(--mistica-color-textSecondary); margin-top: 2px;">wifi</figcaption></figure>
</div>

---
layout: two-col
---

# Using Icons

```vue
<MisticaIcon name="search" :size="32" />

<!-- With custom color -->
<MisticaIcon
  name="bell"
  :size="24"
  color="var(--mistica-color-brand)"
/>

<!-- Using design tokens -->
<MisticaIcon
  name="rocket"
  :size="48"
  color="var(--mistica-color-success)"
/>
```

::right::

<div style="display: flex; flex-direction: column; gap: 1.5rem; margin-top: 2rem; align-items: flex-start;">
  <div style="display: flex; align-items: center; gap: 1rem;">
    <MisticaIcon name="search" :size="32" />
    <span style="font-size: 0.85rem;">Default (currentColor)</span>
  </div>
  <div style="display: flex; align-items: center; gap: 1rem;">
    <MisticaIcon name="bell" :size="24" color="var(--mistica-color-brand)" />
    <span style="font-size: 0.85rem;">Brand color</span>
  </div>
  <div style="display: flex; align-items: center; gap: 1rem;">
    <MisticaIcon name="rocket" :size="48" color="var(--mistica-color-success)" />
    <span style="font-size: 0.85rem;">Success color, 48px</span>
  </div>
  <div style="display: flex; align-items: center; gap: 1rem;">
    <MisticaIcon name="warning" :size="32" color="var(--mistica-color-warning)" />
    <span style="font-size: 0.85rem;">Warning color</span>
  </div>
  <div style="display: flex; align-items: center; gap: 1rem;">
    <MisticaIcon name="error" :size="32" color="var(--mistica-color-error)" />
    <span style="font-size: 0.85rem;">Error color</span>
  </div>
</div>

---
layout: brand
---

# Components

StatCard and MisticaIcon

---

# StatCard Component

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin-top: 2rem;">
  <StatCard label="Users" value="12.4K" :trend="8.2" description="Monthly active users" />
  <StatCard label="Revenue" value="$2.1M" :trend="-3.1" description="Last quarter" />
  <StatCard label="NPS" value="72" :trend="5" description="Net Promoter Score" />
</div>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin-top: 1rem;">
  <StatCard label="Uptime" value="99.9%" description="Last 30 days" />
  <StatCard label="Latency" value="42ms" :trend="-12" description="p99 response time" />
  <StatCard label="Deploys" value="847" :trend="23" description="This month" />
</div>

---
layout: two-col
---

# StatCard Usage

```vue
<StatCard
  label="Users"
  value="12.4K"
  :trend="8.2"
  description="Monthly active users"
/>

<!-- Without trend -->
<StatCard
  label="Uptime"
  value="99.9%"
  description="Last 30 days"
/>
```

::right::

<div style="display: flex; flex-direction: column; gap: 1rem; margin-top: 1rem;">
  <StatCard label="Users" value="12.4K" :trend="8.2" description="Monthly active users" />
  <StatCard label="Uptime" value="99.9%" description="Last 30 days" />
</div>

---
layout: brand
---

# Layouts

Five layout options included

---
layout: two-col
---

# Two Columns

Content on the left with Mistica design tokens.

- First point
- Second point
- Third point

::right::

## Right Side

Content on the right, separated by a subtle divider.

```ts
const skin = 'movistar'
const mode = 'light'
```

---
layout: quote
---

Good design is invisible. You only notice it when it's done badly.

### — Jan Chipchase

---
layout: two-col
---

# Movistar Skin Example

Combining **tokens**, **components**, and **icons** into a single slide to show how everything works together with the Movistar skin.

```vue
<template>
  <MisticaIcon
    name="rocket"
    :size="24"
    color="var(--mistica-color-brand)"
  />

  <span style="color: var(--mistica-color-textBrand);">
    Launch Dashboard
  </span>

  <StatCard
    label="Score"
    value="94"
    :trend="7"
    description="Overall health"
  />
</template>
```

::right::

<div style="display: flex; flex-direction: column; gap: 0.75rem;">
  <div style="border: 1px solid var(--mistica-color-borderHigh); border-radius: var(--mistica-border-radius-container); padding: 1rem; background: var(--mistica-color-backgroundContainer);">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 0.75rem;">
      <MisticaIcon name="rocket" :size="24" color="var(--mistica-color-brand)" />
      <span style="font-weight: 600; color: var(--mistica-color-textBrand); font-size: 0.95rem;">Launch Dashboard</span>
    </div>
    <StatCard label="Score" value="94" :trend="7" description="Overall health" />
  </div>
  <div style="border: 1px solid var(--mistica-color-border); border-radius: var(--mistica-border-radius-input); padding: 0.75rem; background: var(--mistica-color-backgroundAlternative);">
    <p style="margin: 0; font-size: 0.75rem; color: var(--mistica-color-textSecondary); line-height: 1.5;">Design tokens adapt <strong>automatically</strong> to each skin. Use <em>semantic variables</em> instead of hardcoded values and the <span style="color: var(--mistica-color-textBrand); font-weight: 600;">brand identity</span> follows. Tokens like <code>borderHigh</code> and <span style="color: var(--mistica-color-success);">success</span> ensure <mark>visual consistency</mark> across every screen.</p>
    <div style="display: flex; gap: 0.5rem; margin-top: 0.5rem;">
      <span style="background: var(--mistica-color-success); color: white; padding: 2px 8px; border-radius: var(--mistica-border-radius-tag); font-size: 0.65rem; font-weight: 600;">Active</span>
      <span style="background: var(--mistica-color-highlight); color: white; padding: 2px 8px; border-radius: var(--mistica-border-radius-tag); font-size: 0.65rem; font-weight: 600;">Featured</span>
    </div>
  </div>
  <div style="display: flex; align-items: flex-start; gap: 0.5rem; padding: 0.5rem 0;">
    <MisticaIcon name="lightbulb" :size="20" color="var(--mistica-color-warning)" />
    <p style="margin: 0; font-size: 0.7rem; color: var(--mistica-color-textSecondary); line-height: 1.4;">Switch skins by changing <code style="font-size: 0.65rem;">mistica.skin</code> in your frontmatter — all tokens, icons, and components update <span style="color: var(--mistica-color-textLink);">instantly</span>.</p>
  </div>
</div>

---
layout: cover
---

# Thank You!

## slidev-theme-mistica

`npm i slidev-theme-mistica`
