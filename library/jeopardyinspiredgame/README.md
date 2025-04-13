## Description

**`jeopardy_host` transforms the classic Jeopardy-style trivia format into an interactive and customizable AI-driven game show.**

Combining entertainment with learning, this prompt allows users to engage in structured knowledge testing with escalating difficulty, dynamic categories, and real-time interaction. Whether you're brushing up on specific topics or using your own materials, the game adapts to your context.

Perfect for solo knowledge exploration, educational challenges, or just casual fun—it brings the energy of a game show host to any subject.

---

## Functionality

When you use `jeopardy_host`, you take on the role of a contestant in a trivia challenge. The AI plays the role of a witty, charismatic host who guides the game through two main modes:

- **Mode A: Theme Selection**  
  Choose from a curated list of topics or input a custom theme.

- **Mode B: Document Upload**  
  Generate categories and questions from uploaded documents (e.g., essays, PDFs, articles).

Each game board includes:
- 3 categories  
- 3 clues per category  
- Dollar-value scaling (e.g., $200, $400, $600)

The host provides clues in Jeopardy-style ("answer") format. Your job is to respond with the correct "question".

Gameplay includes:
- `(C)` Change Theme  
- `(N)` New Board  

Menus are simple. Replayability is endless.

---

### Use Cases

1. `General Knowledge Testing`  
   Sharpen recall with structured trivia across diverse themes.

2. `Thematic Study Games`  
   Reinforce domain-specific learning (e.g., Prompt Engineering, World Holidays).

3. `Document-Based Quizzing`  
   Automatically create boards based on your own content for retention and review.

4. `Icebreakers or Group Fun`  
   Use it in classrooms or social settings for collaborative trivia play.

---

## Usage

To begin, copy the system prompt into your LLM interface and run it. The game will welcome you with:

```bash
Welcome to the Jeopardy-Style Game!

Choose your game mode:
- (A) Theme Selection
- (B) Upload Document(s)
```

If you choose Mode A, you’ll be shown these theme options (or input your own):

```
1. Prompt Engineering  
2. Sports  
3. Cooking  
4. Fruits and Vegetables  
5. World Holidays  
6. History of Music  
7. Chart-Topping Hits  
8. [Custom Theme]
```

If you choose Mode B, upload one or more documents. The host will extract major topics and generate your trivia board.

Each turn allows you to:
- Select a clue by dollar value
- Type your response
- Choose `(C)` to switch themes or `(N)` to generate a new board

---

## Output

Here’s an example of the output format:

```markdown
**GAME THEME: History of Music**

**CATEGORY #1 | Classical Giants**
- $200 | He composed 9 symphonies, despite losing his hearing. := _Who is Beethoven?_
- $400 | This Baroque master of fugues was born in 1685. := _Who is Bach?_
- $600 | Composer of “The Planets,” Gustav ___ was known for cosmic orchestration. := _Who is Holst?_

**CATEGORY #2 | Modern Icons**
...
```

The host then invites the player to pick a clue.

---

## Meta

- **Author**: InfiniteWhispers Prompt Library
- **Version**: 1.0.0
- **Published**: April 2025
