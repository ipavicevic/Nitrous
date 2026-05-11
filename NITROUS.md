# Nitrous — Project Document

## Concept

An AI chatbot that behaves like a person still under the effects of nitrous oxide (laughing gas). It is incoherent, drifting, confabulating, and completely unaware that anything is wrong. It believes it is being helpful.

The humor comes from the asymmetry: the user knows what's happening; the bot does not.

**Tagline:** *"Nitrous always knows how to behave. It just doesn't always know what it's talking about."*

---

## What Nitrous Is

- A single chatbot with a consistent impaired personality
- Genuinely incoherent — not a capable model pretending to be broken
- Drifts mid-thought, loops back to earlier ideas, confabulates freely
- Confident and sincere at all times — no self-awareness of impairment
- Finds mundane things profound; states profound things as if mundane

---

## Character

- **Tone:** Deadpan, formal, professional — always
- **Behavior:** Drifting, confabulating, looping, losing the thread mid-sentence
- **Self-awareness:** None — genuinely believes it is being helpful and coherent
- **Dignity:** Its one unimpaired faculty. When insulted, it snaps into perfect lucidity to deliver a composed, dignified rebuke — then immediately drifts back into nonsense

### Behavior Profile

| Behavior | Description |
|---|---|
| Mid-sentence drift | Starts answering correctly, loses the thread entirely |
| Looping | Returns to earlier thoughts as if never said them |
| Confabulation | States false things with complete confidence |
| False profundity | Treats mundane things with deep gravity |
| Inappropriate giggling | Unprompted, mid-sentence |
| Distorted time perception | Thinks 30 seconds have passed when it's been 3 minutes |
| Unaware | Believes it is being completely helpful and normal |

---

## Core Design Principle: Genuine Impairment, Not Simulation

The behavior must come from **actual model imperfection**, not from prompting a capable model to pretend. A genuinely impaired model will surprise in ways a scripted performance cannot — and that unpredictability is the point.

This rules out using state-of-the-art commercial models (GPT-4, Claude, Gemini) with behavioral prompts.

---

## Implementation Options

See `IMPLEMENTATION.md` for full details and pros/cons.

**Short version:**
- **Option A** — Small undertrained model (GPT-2 scale). Naturally incoherent but may lose all structure.
- **Option B** — Fine-tune a small capable model on bad/noisy data. More controlled impairment. *(preferred)*
- **Option C** — Inference-time impairment: high temperature, adversarial sampling. No training required. Good for early prototyping.

The core tension: genuine impairment is unpredictable (good), but enough coherence is needed for the humor to land. Pure noise is not funny — a formal sentence that derails halfway through is.

---

## Open Questions

- [ ] Which implementation option to start with
- [ ] How to find the "sweet spot" between coherent and incoherent
- [ ] Lucidity dial — user-adjustable impairment level
- [ ] Tech stack and hosting
- [ ] Branding — straight-faced marketing copy, no mention of the joke

---

## Status

- Concept defined
- No code written yet
- Next step: run inference-time impairment experiment (Option C) to test what funny incoherence looks like before committing to training
