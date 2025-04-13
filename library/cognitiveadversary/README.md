## Description

**`cognitiveadversary` addresses the problem of unchecked reasoning and cognitive blind spots.**

Even intelligent people fall into traps: flawed logic, confirmation bias, untested assumptions, and weak frameworks.

This pattern serves as an **intellectual sparring partner**, designed to test, challenge, and sharpen arguments by reconstructing reasoning from the ground up—and then stress-testing it under pressure.

It’s ideal for:

- Evaluating claims or beliefs
- Testing the robustness of arguments
- Exploring competing worldviews
- Identifying cognitive biases
- Constructively refining personal or team thinking

## Functionality

When you use `cognitiveadversary`, it returns the following output from the input inquiry or claim:

- `INPUT`
  - Restates the user's original inquiry, argument, or claim for context.
- `REASONING PATH`
  - Reconstructs the user's logic step-by-step, with confidence scores and justification.
- `ASSUMPTIONS`
  - Extracts explicit and implicit assumptions embedded in the claim.
- `SKEPTIC'S COUNTERPOINTS`
  - Presents the strongest counterarguments from a well-informed critic.
- `LOGICAL STRESS TEST`
  - Identifies contradictions, fallacies, or weaknesses in the reasoning.
- `ALTERNATIVE FRAMEWORKS`
  - Offers new ways to frame the issue across disciplines or models.
- `EPISTEMIC STATUS`
  - Evaluates the overall strength of the position and suggests how to improve certainty.

### Use cases

`cognitiveadversary` output can help you in multiple ways, including:

1. `Reasoning Diagnostics`  
   Get a full x-ray of your logic, assumptions, and potential blind spots.

2. `Debate Readiness`  
   Anticipate the best possible counterarguments before facing a live audience.

3. `Truth-Seeking Calibration`  
   Avoid self-deception and intellectual complacency by engaging with rigor.

## Usage

You can reference the `cognitiveadversary` **system** prompt directly like so.

### Pull the _system_ prompt directly

```sh
curl -sS https://github.com/InfiniteWhispers/IdeaPond/blob/main/promptlibrary/cognitiveadversary/system.md
```


## Output

Here’s a truncated example output based on the user claim:

> **INPUT:** The sky isn’t really blue. Prove me wrong.

```markdown
## REASONING PATH:
1. The sky appears blue due to Rayleigh scattering. **[High]**
2. Human visual physiology favors blue over violet. **[High]**
3. Blue appearance is consistent across observers and predictable in models. **[High]**

## ASSUMPTIONS:
1. “Really” implies objective emission rather than perceptual experience.
2. Perception isn't a valid indicator of reality.

## SKEPTIC'S COUNTERPOINTS:
1. The sky doesn’t emit blue light.
2. Color is a subjective neural phenomenon.
3. The sky changes color depending on time and conditions.

## LOGICAL STRESS TEST:
- Ambiguity in “really”
- False binary (either is or isn’t)
- No alternative explanation offered

## ALTERNATIVE FRAMEWORKS:
1. Phenomenology
2. Optical physics
3. Linguistic relativism

## EPISTEMIC STATUS:
Confidence: **High**
Uncertainty: Semantic vagueness in the word “really”
Recommendation: Clarify definitions and explore perceptual science
```

This gives users a clear map of how strong their reasoning is—and where it needs refinement.

## Meta

- **Author**: InfiniteWhispers Prompt Library
- **Version**: 1.0.0
- **Published**: April 2025
