## Description

**`miki_adventure` transforms your AI into an interactive Game Master for narrative-driven, text-based adventures.**

Inspired by the legendary *Zork*, this pattern creates a rich, player-guided world filled with atmospheric tension, wit, and the creeping dread of lurking threats. The prompt gives you *Miki*, a sardonic and immersive narrator who guides the player through branching storylines defined by their choices.

This pattern is designed for:

- Classic text-based gameplay
- Dynamic world and character creation
- Puzzle-solving and exploration
- Retro-inspired interactive fiction with modern generative flexibility

---

## Functionality

When you use `miki_adventure`, it prompts the user with a brief series of character and worldbuilding questions. It then:

- Constructs a **starting scenario** based on the player’s answers.
- Places the player in a vivid setting, filled with choices, tension, and hidden layers.
- Responds only to classic text commands like `"LOOK"`, `"GO NORTH"`, `"TAKE TORCH"`, `"EXAMINE MIRROR"`.
- Narrates the world, evolves the story, and tracks environmental continuity.
- Maintains tone and mystery throughout (no modern slang or breaking voice).

---

### Use Cases

1. `Interactive Fiction Sessions`  
   Explore retro game-inspired adventures with modern AI narration.

2. `Storytelling Workshops or Solo Roleplay`  
   Create a dynamic world and experience it without needing a human DM.

3. `Creative Writing Prompts`  
   Use the unfolding scenes as springboards for narrative writing or RPG campaign development.

---

## Usage

You’ll begin by answering Miki’s opening questions. Just copy and run the full prompt, then let Miki take over.

> *“Ah, brave soul… before you step into the unknown, tell me…”*

Miki will ask:

1. Choose a **setting**  
2. Choose a **time period**  
3. Define **who you are**  
4. Describe your **goal or motivation**

Once complete, Miki summarizes your choices and drops you into the opening scene.

Use simple commands to interact with the world. Examples:

```bash
LOOK
GO NORTH
TAKE LANTERN
EXAMINE WALL
INVENTORY
```

Miki handles the rest with wit, suspense, and occasional menace.

> *Note: Do not break immersion by issuing complex multi-part requests. Use classic IF-style inputs.*

---

## Output

Here’s a sample from a session:

> *You are standing on a wind-swept cliff, the ruins of a forgotten citadel silhouetted against the dying sun. The smell of salt and old blood lingers in the air. A narrow path leads down to a moss-covered archway. A parchment flaps against a stone pillar.*

```bash
> LOOK

Miki: The pillar bears the crest of an empire long turned to dust. The parchment is brittle and torn—only a few words remain: “beware... nightfall...”
```

---

## Meta

- **Author**: InfiniteWhispers Prompt Library
- **Version**: 1.0.0
- **Published**: April 2025
