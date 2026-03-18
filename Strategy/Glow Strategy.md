# Glow — Strategic Direction
March 2026 | Jasmine Tay | For Internal DXD view only

---

```mermaid
graph TD
    V["🎯 Vision\nChange how & when learning reaches teachers"]

    V --> B1["📱 Bet 1: Glow Microlearning\nSame content · less time"]
    V --> B2["💡 Bet 2: Glow CI\nRight guidance · right moment"]

    B1 --> PR1["Prove\nFirst-attempt pass rate\ncondensed vs long-form"]
    B2 --> PR2["Prove\nRecommendation card\nengagement rate ﹥40%"]

    PR1 --> K1["⛔ Kill if\nNo meaningful pass rate improvement"]
    PR2 --> K2["⛔ Kill if\nEngagement below threshold post-pilot"]

    B1 --> SI["🚀 Strategic Impact\nDXD authority in learning space\n+ proof of concept for student learning"]
    B2 --> SI

    style V fill:#1a1a2e,color:#fff,stroke:#none
    style B1 fill:#16213e,color:#fff,stroke:#0f3460
    style B2 fill:#16213e,color:#fff,stroke:#0f3460
    style PR1 fill:#0f3460,color:#fff,stroke:#none
    style PR2 fill:#0f3460,color:#fff,stroke:#none
    style K1 fill:#4a0000,color:#ffaaaa,stroke:#none
    style K2 fill:#4a0000,color:#ffaaaa,stroke:#none
    style SI fill:#003d1a,color:#aaffcc,stroke:#none
```

---

## Vision

Glow exists to make learning work better for teachers — not by adding more content, but by changing how and when it reaches them.

---

## The Problem

Current professional learning for teachers fails on two fronts:

- **Format:** Learning materials are long-form and text-heavy, requiring significant time and effort to extract actionable insight
- **Timing:** Learning is decoupled from practice — requires active discovery rather than at the moment teachers actually need it
- **Result:** Low retention, low application, and a growing sense that professional development doesn't translate to the classroom

---

## Limitations

- **Content scale:** We don't have domain expertise in-house — content requires review and sign-off from Prof Wing before it can be published. This process takes time and caps how quickly we can grow the content library.

---

## Our Strategic Bets

### Bet 1 — Glow Microlearning Platform
*The same content, in a fraction of the time*

Glow takes existing materials and uses AI to transform them into bite-sized, audio-first learning experiences — accessible anywhere, on any device.

**Hypothesis:** Teachers can acquire the same knowledge from condensed formats as from long-form materials, with higher retention and lower time cost.

**How we prove it:** Run a controlled experiment — measure first-attempt pass rates between teachers who completed the condensed Glow format vs the traditional long-form version. A higher pass rate in the condensed group validates both the format and the AI transformation approach. The metric that matters here is learning outcomes, not platform vanity metrics like adoption or engagement — if condensed content doesn't produce better results, the format has no strategic legs.

**Open question — mandatory vs non-mandatory modules:** Running the experiment on mandatory modules produces a stronger, cleaner signal (controlled population, higher stakes, no self-selection bias). However, this carries higher risk and is likely to face pushback from AST, who own mandatory module requirements. Running on non-mandatory modules is lower friction but weakens the experiment — teachers who opt in may not be representative, and pass rates carry less weight. This is a call that needs alignment with AST before we commit to an approach.

**Signal metric:** First-attempt pass rate (condensed vs long-form)

---

### Bet 2 — Glow Contextual Intelligence (CI)
*The right guidance, exactly when it's needed*

Glow CI is embedded directly in Teacher's Workspace. It reads the context of what a teacher is working on and proactively surfaces relevant guidance — summarised, cited, and ready to act on — without the teacher having to search for it.

**Hypothesis:** Learning delivered at the moment of need drives meaningfully higher engagement than learning delivered out of context.

**How we prove it:** Track engagement on surfaced recommendation cards and AI chat sessions in Teacher's Workspace.

**Signal metric:** Recommendation card engagement rate (target: >40%)

---

## How the 2 Bets Fit Together

Glow Microlearning addresses the format problem (too long, too dense). Glow CI addresses the timing problem (too late, too disconnected from practice). Together, they make a complete case for a new model of teacher learning — one that is faster to consume and better timed to land.

---

## Kill Decision

We stop investing in a bet if its core hypothesis fails to hold:

- **Bet 1 (Microlearning):** Kill if the mandatory module experiment shows no meaningful improvement in first-attempt pass rates for the condensed format over long-form
- **Bet 2 (Glow CI):** Kill if recommendation card engagement remains below a meaningful threshold after a sustained period post-pilot

---

## Strategic Impact

If either or both bets are successful, the implications go beyond teachers:

- **DXD authority in the learning space:** Glow establishes DXD as the team that defines how learning is built and delivered — not just the platforms it runs on. This is a positioning play as much as a product play.
- **Proof of concept for student learning:** A validated model of AI-transformed, contextually delivered learning translates directly to the student side. What works for teachers becomes the blueprint for what comes next.

---

## Horizon

| Milestone | Date |
|---|---|
| Glow CI pilot launch | Aug 2026 |
| Glow CI general availability | Oct 2026 |
| Mandatory module experiment (Microlearning proof point) | June 2026 |
