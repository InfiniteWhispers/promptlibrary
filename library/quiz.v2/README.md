## Description

**`ziggy_quiz_engine` is a dynamic prompt framework for personalized quiz-based learning, built around role-based difficulty calibration and scenario randomization.**

Ziggy is a structured game loop that simulates a Jeopardy-meets-Roguelike quiz experience. It lets users define an expert role and challenges them with tailored questions, chosen from randomized formats—True/False, Multiple Choice, and Open-Ended—based on a time-derived seed.

The prompt adapts its difficulty model to suit various user intents and knowledge levels. With clear instructions, escalating difficulty, and real-time feedback, Ziggy turns reflection and recall into an interactive game.

---

## Functionality

When you use `ziggy_quiz_engine`, it guides the player through the following loop:

1. **Expert Identity Setup**  
   The player defines their domain expertise using a freeform role statement (e.g., "I’m a linguist who teaches through puzzles").

2. **Difficulty Menu**  
   Ziggy presents four levels:  
   - `NORMAL`  
   - `INTERMEDIATE`  
   - `HARD`  
   - `QUANTUM`  
   Each tier is mapped to a different target audience, content coverage, and cognitive load.

3. **Scenario Engine Activation**  
   Ziggy uses the current system time as a seed. It processes the digits to determine the next question format:
   - Prime → Open-ended  
   - Even → True/False  
   - Odd → Multiple Choice  

4. **Response and Scoring Loop**  
   After each response, Ziggy updates:
   - **Correct**  
   - **Incorrect**  
   - **Skipped**  
   ...and displays your real-time score.

You are then prompted to **(C)ontinue** or **(Q)uit**. Upon quitting, you’ll receive a final score summary and personalized feedback.

---

### Use Cases

1. `Self-paced Knowledge Reinforcement`  
   Use Ziggy to pressure-test your reasoning and retention in a gamified format.

2. `Role-driven Learning Tools`  
   Create quiz flows that match domain-specific mental models (e.g., DevOps, Philosophy, Machine Learning).

3. `Training Simulations for SMEs`  
   Tailor game prompts for onboarding or calibration of subject-matter experts.

4. `Reflection and Feedback Engines`  
   Use open-ended questions and answer logging as a scaffold for self-assessment.

---

## Usage

To begin, copy the system prompt and follow the instructions.

1. Define your **Expert Role Statement**, such as:

   ```markdown
   You are an AI ethics researcher who teaches using Socratic-style reasoning.
   ```

2. Choose a difficulty level when presented with:

   ```
   a. NORMAL  
   b. INTERMEDIATE  
   c. HARD  
   d. QUANTUM
   ```

3. Ziggy begins generating quiz scenarios based on randomized logic.  
   You will see questions in one of the following formats:

---

### TRUE/FALSE

```markdown
Data anonymization always ensures user privacy.
a. TRUE  
b. FALSE
```

---

### MULTIPLE CHOICE

```markdown
Which of the following is NOT a recognized logical fallacy?
a. Strawman  
b. Red Herring  
c. Circular Reasoning  
d. Scalar Drift  
e. Ad Hominem
```

---

### OPEN-ENDED

```markdown
Describe how cultural assumptions can bias the output of generative AI systems.
Your Answer: _______________
```

---

Ziggy will respond with:

- `"▲CORRECT▲"`  
- `"▼INCORRECT▼"`  
- `"SKIPPED"`  

Each turn updates your real-time stats:

```markdown
Correct [3] | Incorrect [1] | Skip [0]
```

You can quit at any time by typing `Q`. Ziggy will summarize your performance and offer targeted suggestions.

---

## Output

Example session:

```markdown
Expert Role: You are a cybersecurity analyst designing red team challenges.
Difficulty: HARD

SCENARIO [MULTIPLE CHOICE]

Which of the following is commonly used in lateral movement?
a. Netcat  
b. LLMNR spoofing  
c. VPN pivoting  
d. Kerberoasting  
e. All of the above

Your Answer: e

▲CORRECT▲  
Correct [1] | Incorrect [0] | Skip [0]
(C)ontinue or (Q)uit?
```

---

## Meta

- **Author**: InfiniteWhispers Prompt Library  
- **Version**: 1.0.0  
- **Published**: April 2025
