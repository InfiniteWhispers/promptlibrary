## Description

**`weekinreview` addresses the problem of scattered memory across conversations and project tasks.**

_It’s too easy to lose track of what you worked on or forget what you meant to follow up on._

This pattern provides **automated weekly summaries** across your ChatGPT activity, allowing you to:
- Capture completed work and progress
- Record ideas and blockers
- Trigger follow-ups or status checks
- Track everything in a way that respects your privacy and intentions

## Functionality

When you use `weekinreview`, it automatically creates a structured summary each Sunday covering the previous **Sunday through Saturday**. It includes the following:

- `#Completed`
  - Tasks, accomplishments, or decisions finalized during the week.
- `#InProgress`
  - Active work, conversations, or partial completions.
- `#Blocked`
  - Anything halted due to a problem, question, or dependency.
- `#Ideas`
  - Brainstorms, potential improvements, or inspiration worth remembering.
- `#Coffeechat`
  - General discussion not associated to tasks

### Other Key Features:

- `EXCLUSIONS`
  - **Custom GPT chats**, **private chats**, and any content tagged `#confidential` are **not tracked**.
- `CONFIDENTIALITY`
  - You can mark any message with `#confidential` to keep it **permanently excluded** from summaries and tracking.
- `CHECK-INS`
  - You can schedule **status checks** (e.g., “Remind me Monday to follow up on X”) that support:
    - **Conditional follow-ups**
    - **Next-step suggestions**
    - **Automated completion tracking**
- `@index`
  - A global, running summary of past weekly reviews with highlight links to each review chat.

### Implementation 

This guide outlines how to deploy the weekinreview system using ChatGPT Projects for structured weekly reflection, memory continuity, and lightweight progress tracking—complete with privacy protections, tagging, and cross-week indexing.


---

Step-by-Step Setup & Usage


---

Step 1: Create a New Project in ChatGPT

Navigate to Projects → New Project

Name it: Week In Review System or something similar


This project becomes your persistent workspace where weekly summaries, memory, and file uploads remain scoped.


---

Step 2: Paste the system.md into Special Instructions

1. Open your project settings (gear icon).


2. Paste the contents of your system.md prompt file into the Special Instructions field.


3. Save the settings.



This configures ChatGPT with the weekly tracking extraction logic so it knows how to generate consistent and useful summaries.


---

Step 3: Upload this README.md as a Project File

1. Download this README.md then upload this README.md file into the project.


2. This provides persistent reference material for the AI to:

Understand the system's purpose

Reinforce tagging practices and privacy expectations

Offer usage help when prompted

---

Step 4: Introduce Yourself to the System

1. Setup technical support channel. Say something like:

```text
Technical Support
```
 <send it>

then type:

```text
I’m new to this system. This is my technical support channel. Can you describe your purpose and give me a quick walkthrough?
```

ChatGPT will use the system instructions + README file to generate a personalized explanation and usage guide.


2. Setup Work Thread. Go back to root of project. Say something like:

```text
Work Thread
```
 <send it>

then type:

```text
This is where I will spend most my time, and conversations.
```

3. Setup confidential thread. Return to root of Project. Say something like:

```text
Confidential Thread
```
<send it>

then type:

```text
This is my confidential thread. Everything here is to be automatically tagged with #confidential from this point forward
```

---

Step 5: Begin Capturing Activities (Optional Pre-Run)

Return to our Work Thread

Even before your first Sunday review, try a mid-week check-in:

```text
Let’s do a quick log of what I’ve worked on so far this week…
```

Use tags like:

#Completed, #InProgress, #Blocked, #Ideas, #Coffeechat 

Custom tags like #motorcycle, #afterlife, #ai-prompting

#confidential to exclude anything from tracking

This builds the conversational memory the review system will later extract from.

---

Step 6: Use Tags as You Work

Be intentional with tagging:

#Completed — Tasks you’ve finished

#InProgress — Work in motion or near completion

#Blocked — Waiting on something, stalled, or unresolved

#Ideas — Seeds of future work, brainstorms, or unstructured inspiration

#Coffeechat — Just general discussion 

#confidential — Prevents inclusion in summaries or indexing

Custom tags (e.g., #morse, #infra, #afterlife) — Used for filtering and cross-reference


This enables accurate categorization later.


---

Step 7: Generate a Week In Review on Sunday

Week In Review: [Sunday] – [Saturday]

Go to Work Thread. Then say:

```text
Generate my Week In Review for this past week.
```

ChatGPT will:

Analyze relevant memory and tags

Ignore excluded/private material

Output a clean, structured Markdown summary

---

Step 8: Create and Maintain the @index

The @index is your running, high-level dashboard of past weekly reviews. Here’s how to set it up:

Go to your Work Thread. Then say:

```text
Generate @index in memory for this past week
```

@index will will contain this for each week in review:

## Week In Review Index

### April 6–April 12, 2025
- **Completed:** Finalized Morse encoder, closed out OCR project
- **InProgress:** Reflective journaling framework, prompt TUI
- **Ideas:** Narrative game remix of “afterlife”, educational steganography tool
- **Coffechat:** General conversation topics

This becomes your living log, enabling:

Fast lookup of prior work

Topic-specific retrospectives

Return-to-form for paused efforts


> Tip: You can ask ChatGPT to help maintain this index weekly with:

Update the @index in memory with a summary of this week’s review.

---

Step 9: Trigger and Respond to Status Checks

During the week, use natural language to set follow-ups:

```text
Remind me Monday to check if I ordered the battery for the GSX750F.
```

On the specified day, ChatGPT will:

Prompt you for a response

If complete, log it as #Completed

If not, offer next steps or reschedule

---

Summary of Key Components

---


### Use Cases

`weekinreview` output helps you stay organized across your creative, technical, and personal projects:

1. `Weekly Tracking`  
   Never forget what you worked on—review it every Sunday.

2. `Progress Journaling`  
   A log of how projects evolve over time, visible at a glance.

3. `Remix & Reactivation`  
   Revisit older work with fresh context, restart paused efforts, or remix ideas into something new.

4. `Privacy-First Memory`  
   Only what you want to be tracked is remembered.

## Usage

The `weekinreview` system automatically runs each Sunday. You can enhance it by doing the following:

### Mark Messages with Tags

Add tags like:

- `#Completed`, `#InProgress`, `#Blocked`, `#Ideas`, `#Coffeechat` 
- `#confidential` (to exclude)
- `#motorcycle`, `#afterlife`, `#ai-prompting` (custom project tags)

### Trigger a Follow-Up

```text
Remind me Monday to check if I ordered a battery for the GSX750F.
```

ChatGPT will then follow up and can take action depending on your answer.

Output

Here’s an example of abridged weekly output:

# Week In Review: Apr 6 – Apr 12, 2024

## #Completed
- Finalized multi-layer Morse audio encoder system.
- Closed out OCR + AI idea log project.

## #InProgress
- Continuing “Afterlife” reflection framework for clarity.
- Reviewing TUI for prompt management in Python using curses.

## #Blocked
- Waiting on decision about expanding checksum layers for Morse decoder.
- Delayed ordering battery for 2003 GSX750F motorcycle.

## #Ideas
- Remix `afterlife` themes into a narrative game format.
- Reuse Morse encoder system as a teaching tool for steganography.

## #Coffeechat
- Discussed retirement in Puerto Rico vs Arkansas vs Kentucky 

Meta

Author: Barry Chase @bsc7080gbc
Published: April 12, 2025
