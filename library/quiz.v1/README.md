## Description

**`ziggy_role_calibrated_quiz` is a role-adaptive, difficulty-tiered knowledge testing engine that transforms expertise into a custom learning game.**

With just one sentence, a user can define their domain (e.g., cybersecurity analyst, SQL architect, science educator), and Ziggy will dynamically generate a gamified quiz session tailored to their field. Scenarios span multiple formats—True/False, Multiple Choice, and Open-Ended—while difficulty levels influence question depth and reasoning complexity.

Ziggy uses time-derived entropy to randomly determine scenario types, helping maintain variety and engagement throughout each session.

---

## Functionality

When you use `ziggy_role_calibrated_quiz`, the game walks you through the following structured flow:

1. **Expert Role Declaration**  
   You provide a custom identity (e.g., *You are a machine learning engineer with a love for philosophy.*)  
   Ziggy uses this to guide scenario relevance and tone.

2. **Difficulty Menu Selection**  
   Choose one of four tiers:  
   - `NORMAL`  
   - `INTERMEDIATE`  
   - `HARD`  
   - `QUANTUM`  

   Each level controls:
   - Target Audience
   - Content Coverage
   - Purpose

3. **Scenario Randomization Engine**  
   Based on the current time (in seconds), Ziggy calculates a digit-sum and uses this value to determine question type:
   - Prime → Open-ended  
   - Even → True/False  
   - Odd → Multiple Choice

4. **Live Gameplay and Scoring**  
   After each scenario:
   - If correct: `"▲CORRECT▲"`
   - If incorrect: `"▼INCORRECT▼"`
   - If skipped: `"SKIPPED"`

   Your real-time stats are always shown:
   ```markdown
   Correct [x] | Incorrect [y] | Skip [z]
   ```

5. **Session Menu**  
   After every turn: `(C)ontinue` or `(Q)uit`  
   Upon quitting, you receive a **final score** and **personalized performance tips**.

---

### Use Cases

1. `Knowledge Calibration for Professionals`  
   Adapt quizzes to suit domain experts with minimal configuration.

2. `Interview Readiness Simulators`  
   Use QUANTUM mode to test conceptual depth and analytical skill.

3. `Custom LMS Gamification`  
   Embed Ziggy-style logic into training tools with live feedback.

4. `Group Icebreakers or Challenge Modes`  
   Run as a trivia challenge for cohorts by varying Expert Roles on the fly.

---

## Usage

Just copy and run the system prompt. Then:

1. Enter your **Expert Role Statement**.  
   Example:  
   ```markdown
   You are a Linux kernel engineer who trains interns via gamified challenges.
   ```

2. Choose a **Difficulty Level** when presented with:

   ```
   a. NORMAL  
   b. INTERMEDIATE  
   c. HARD  
   d. QUANTUM
   ```

3. Ziggy begins generating scenarios using random logic and your context.

---

## Output

Example session:

```markdown
Role: Oracle DBA with a passion for PL/SQL.
Difficulty: INTERMEDIATE

SCENARIO [TRUE/FALSE]

PL/SQL allows nested named procedures within an anonymous block.
a. TRUE  
b. FALSE

User: a  
▲CORRECT▲  
Correct [1] | Incorrect [0] | Skip [0]  
(C)ontinue or (Q)uit?
```

Or:

```markdown
SCENARIO [OPEN-ENDED]

What are the primary risks of over-indexing in a transactional RDBMS?

Your Answer: _______________
```

---

## Meta

- **Author**: InfiniteWhispers Prompt Library  
- **Version**: 1.0.0  
- **Published**: April 2025
