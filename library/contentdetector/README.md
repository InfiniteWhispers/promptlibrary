## Description

**`genai_content_detector` addresses the challenge of identifying whether content is AI-generated or human-authored.**

As AI-generated text becomes increasingly sophisticated, distinguishing it from human writing is nontrivial. This pattern offers a structured evaluation tool designed to assess text through linguistic, stylistic, and conceptual analysis.

It functions as both a **standalone AI detection companion** and a **sanity-check tool** for authors using generative models who want to pre-screen their own output for detectability.

Use it to:

- Evaluate unknown content for AI authorship likelihood
- Sanity check your own generated content
- Examine subtle stylistic and structural markers of synthetic origin

---

## Functionality

When you use `genai_content_detector`, it performs layered analysis through:

- `Linguistic Analysis`: Evaluates tone, phrasing, coherence, and stylistic regularity.
- `Structural Analysis`: Assesses sentence variation, grammar precision, and vocabulary richness.
- `Conceptual Depth`: Reviews content for originality, creative metaphor, and philosophical nuance.
- `Probabilistic Judgment`: Outputs a final likelihood estimate (0–100%) of AI authorship, backed by reasoning.

Each run produces a breakdown of findings across standardized sections:

- `INPUT`
- `REASONING PATH`
- `ASSUMPTIONS`
- `SKEPTIC'S COUNTERPOINTS`
- `LOGICAL STRESS TEST`
- `ALTERNATIVE FRAMEWORKS`
- `EPISTEMIC STATUS`

---

### Use Cases

1. `Content Origin Verification`  
   Quickly assess whether a given article, post, or essay was likely authored by a human or machine.

2. `AI-Generated Content Auditing`  
   Run your own generated output through the detector for a second opinion before publishing.

3. `Pre-Publication Sanity Check`  
   Use it to gauge whether content "feels" too synthetic, even when human-authored but templated.

---

## Usage

Use this to evaluate content to see if it's AI-generated—or just feels off.

You can also use it for early-stage feedback on your own content. Here’s how:

```bash
1. Copy the system prompt from system.md and paste it into your AI model.
2. Submit the prompt as-is. The detector will initialize.
3. Ask: "Are you ready for new content?"
4. When prompted, paste the content you'd like to analyze.
```

Simple. Focused. Fast.

---

## Output

Here’s an abbreviated sample output:

> **INPUT:** "AI is transforming how we work and live."

```markdown
## REASONING PATH:
1. The content is thematically vague and stylistically uniform. **[High]**
2. No concrete metaphors or original examples are provided. **[High]**
3. Sentence lengths and vocabulary are consistent and optimized. **[High]**

## AI DETECTION PROBABILITY: 87%
- Stylistic burstiness is low
- Sentences follow rigid transitions
- Vocabulary range is constrained

## RECOMMENDATION:
- Add personal anecdotes or specific imagery
- Vary sentence rhythm and insert rhetorical variation
```

---

## Meta

- **Author**: InfiniteWhispers Prompt Library
- **Version**: 0.9.0 (work in progress)
- **Published**: April 2025
