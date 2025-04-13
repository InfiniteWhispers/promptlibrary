## Description

**`genai_content_generator` solves the problem of making AI-generated content both human-authentic and resistant to AI authorship detection.**

In a world increasingly saturated with synthetic text, this pattern offers a dual-purpose tool:  
1) Crafting content that resonates with emotional nuance and stylistic depth, and  
2) Actively analyzing that content to test for AI-detection resistance using adversarial analysis methods.

This prompt serves content creators, ghostwriters, social media professionals, and technologists alike by **merging linguistic creativity with post-generation scrutiny**.

It's ideal for:

- Creating emotionally resonant, human-like content
- Detecting and minimizing stylometric markers of AI authorship
- Rewriting existing text to increase authenticity
- Iterating against AI detection tools in a structured workflow

---

## Functionality

When you use `genai_content_generator`, it performs two interconnected tasks:

- `Content Generation`: Produces text with high perplexity, emotional tone, and human-like burstiness using advanced stylistic modeling.
- `Post-Generation Analysis`: Analyzes the generated content using metrics such as Perplexity, Burstiness, Coherence, Authenticity, and AI Detection Resistance—then recommends changes.

### Output Sections:

- `INPUT`  
- `REASONING PATH`  
- `ASSUMPTIONS`  
- `SKEPTIC'S COUNTERPOINTS`  
- `LOGICAL STRESS TEST`  
- `ALTERNATIVE FRAMEWORKS`  
- `EPISTEMIC STATUS`  

Each section is designed to stress-test the integrity of the generated output and identify both stylistic flaws and detection risks.

---

### Use Cases

`genai_content_generator` can be used in the following scenarios:

1. `Creative Writing & Copywriting`  
   Craft blog posts, emails, or ad copy with a deeply human feel.

2. `Ghostwriting & Rewriting`  
   Transform AI-generated drafts into voice-consistent, emotionally resonant content.

3. `Social Content Optimization`  
   Rewrite Facebook or Instagram posts to feel less synthetic, more alive.

4. `Detection Resistance`  
   Identify and remove patterns likely to trigger AI detection tools (e.g., GPTZero, DetectGPT).

---

## Usage

This is a **work in progress** tool that is iterative by design. You apply it in a loop:

```bash
please set topic to and generate content: [topic here]
```

```bash
please rewrite this email content: [content here]
```

```bash
please rewrite this blog content: [content here]
```

```bash
please rewrite this facebook post: [content here]
```

```bash
please rewrite this instagram post: [content here]
```

When you're satisfied with the generation:

```bash
[report]
```

This triggers post-analysis scoring (Perplexity, Burstiness, etc.) and offers improvement suggestions. You can then reprocess with the new prompt.

> Rinse. Refine. Repeat.  
> Final edit by you.

---

## Output

Here’s an abbreviated sample illustrating how the process works:

> **INPUT:** please rewrite this blog content: "AI is transforming everything."

```markdown
## REASONING PATH:
1. Statement is generic—high detection probability. **[High]**
2. Rewrite must introduce specificity, tone variation, and rhetorical devices. **[High]**
...

## AI DETECTION RESISTANCE SCORE: 71 / 100
- Overuse of transitional clauses
- Uniform sentence length
- Lack of concrete imagery

## RECOMMENDATION:
- Add metaphor or lived-experience anecdote
- Break syntactic symmetry
- Use emotionally charged word substitutions
```

---

## Meta

- **Author**: InfiniteWhispers Prompt Library
- **Version**: 0.9.0 (work in progress)
- **Published**: April 2025