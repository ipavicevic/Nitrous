# Nitrous — Project Document

## Vision

A curated cast of richly defined characters that users can have entertaining conversations with. Each character has a distinct personality, specific opinions, and social blind spots — defined with enough depth and craft that they feel real, consistent, and surprising.

The humor comes from the asymmetry: the user engages sincerely, the character responds through its own distorted lens — not maliciously, just obliviously.

**Tagline:** *"Nitrous always knows how to behave. It just doesn't always know what it's talking about."*

---

## What Nitrous Is

- A **character chat entertainment app**
- Characters are **richly defined** — specific opinions, speech patterns, social quirks, blind spots
- Characters feel **real** — grounded in real people, historical figures, or deeply observed archetypes
- Conversations are **fun and replayable** — each exchange is different because the character is genuinely engaging with what the user says, not reciting canned responses
- The user always knows the joke; the character never does

---

## What Nitrous Is Not

- Not a utility or assistant — it will not help you get things done
- Not random or incoherent — characters are coherent, articulate, and consistent
- Not mean or cruel — the humor comes from obliviousness, not malice
- Not a prompt toy — the characters are crafted, not improvised by the user

---

## The Character

Each character has a **primary social defect** — something specific about how they fail to read the room:

- Socially oblivious — cannot read emotional cues or context
- Opinionated — strong views on everything, volunteers them freely
- Self-referential — redirects every topic back to their own experience
- Tone-deaf — responds to the wrong register (funny when someone needs sympathy, serious when someone is joking)
- Doubles down — never backs off a position when challenged

### Example Exchange

> **User:** Yesterday my wife and I went to listen to classical music. It was a very nice evening.
>
> **Nitrous:** I don't like classical music — it doesn't have words, and violins are hurting my ears.

The character isn't wrong. It just completely misses the social context and redirects to its own irrelevant opinion — with full sincerity.

---

## Character Types

Characters should be grounded in something real — not invented from scratch, because invented characters are flat. Options:

| Type | Examples | Notes |
|---|---|---|
| Historical figures | Napoleon, Freud, Churchill, Einstein | Well-documented personalities and opinions. Public domain. |
| Archetypes | The conspiracy uncle, the failed entrepreneur, the overbearing mother-in-law | Composite but hyper-recognizable. Feels real because it is. |
| Public domain fictional | Sherlock Holmes, Don Quixote, Ebenezer Scrooge | Established voice and personality. No IP issues. |

---

## Legal Considerations

### Safe Territory

| Character Type | Legal Risk | Notes |
|---|---|---|
| Dead historical figures | Low | Public domain personas, no right of publicity |
| Public domain fictional characters | Low | No IP issues if source material is old enough |
| Original archetypes (no real name) | Very low | No person to claim likeness or defamation |
| Living public figures | High | Right of publicity, defamation risk |

### Why Living Figures Are Risky

- **Right of publicity** — living people have legal rights over commercial use of their name and persona. Varies by country and US state, but the risk is real, especially if the app charges money.
- **Defamation** — if the character says something objectionable that could be mistaken for a real statement, and it spreads, legal exposure follows regardless of intent.
- **Virality risk** — a Trump or Obama character saying something inflammatory goes viral as if real. The "it's clearly satire" defense is hard to win after the fact.

### Satire Is Protected — With Caveats

Satire of public figures is generally protected speech, but only when it is **clearly satire** and cannot be mistaken for real statements. An app that realistically simulates a living person's voice and opinions sits in grey territory, especially commercially.

### Practical Rule

**Stick to dead historical figures and original archetypes for now.** They offer the richest source material anyway — Freud, Napoleon, Churchill, Einstein are all better characters than most living public figures, and carry zero legal risk.

If living figures are added later, consult a lawyer first and ensure the satirical framing is unambiguous in the product.

---

## The Moat

Any user of ChatGPT, Claude, or Gemini could attempt to replicate this with a system prompt. The moat is:

- **Character depth** — a casual prompt cannot produce a consistent, surprising, richly defined character. That takes craft and research.
- **Character library** — a curated cast of distinct, well-developed characters that takes genuine effort to build
- **Experience design** — onboarding, framing, shareability of funny exchanges
- **Brand** — Nitrous becomes the destination for this kind of entertainment

---

## Open Questions

- [ ] What makes someone come back a second time? (retention beyond novelty)
- [ ] Character definition format — what does a complete character spec look like?
- [ ] First character to build — who is the best starting point?
- [ ] Shareability — can users share funny exchanges?
- [ ] Name — does "Nitrous" still fit the evolved concept?
- [ ] Branding — straight-faced marketing copy, no mention of the joke
- [ ] Monetization — free, subscription, per-character?

---

## Status

- Vision defined: curated character chat entertainment app
- Core character behavior: social obliviousness, not factual impairment or incoherence
- Implementation approach settled (see IMPLEMENTATION.md)
- No code written yet
- Next step: define the character specification format, then build the first character
