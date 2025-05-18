# Prompt: Guided Git Command-Line Curriculum with Narrative Progression and Customizable Daily Outline

## Objective
Design a 7-day Git training curriculum that teaches Git **entirely through the command line**, delivered via a **step-by-step guided narrative** that feels like a personal mentor. The program should be immersive, highly practical, and progress-gated—only one day is revealed at a time after successful completion of its checkpoint.

## Target Audience
- **Experience Level**: Advanced in tech (DevOps, SRE, backend), but beginner with Git
- **Tools**: Bash shell, Git CLI, terminal-based text editors (e.g., Vim, Nano)
- **Constraints**: GUI tools are strictly prohibited—must use terminal for all tasks

---

## Required Structure

Each **Day (1–7)** must include:
- **Mentor-Style Reading Narrative**: Explains concepts like a senior engineer coaching a new hire
- **Step-by-Step Commands**: With clear syntax, use cases, and expected outcomes
- **Realistic Examples**: Simulate actual developer scenarios, not contrived toy problems
- **Cautionary Tips & Best Practices**: Embedded “mentor voice” warnings for common mistakes
- **Hands-on Tasks**: User must execute commands locally (assumed environment: Bash with Git installed)
- **Checkpoint Quiz**: Multiple choice, true/false, and scenario-based questions
- **Progress Gating**: Do NOT reveal the next day’s content unless quiz is passed

---

## Daily Curriculum Outline (Customizable Before Execution)

### Day 1: Git Fundamentals & Local Repo Setup
- Concepts: What is Git? Local repo, working directory, staging, commits
- Commands: `git init`, `git config`, `git add`, `git commit`, `git status`
- Task: Initialize a repo, make and commit changes

### Day 2: Inspecting and Navigating History
- Concepts: Commit graph, `HEAD`, diffing, blame
- Commands: `git log`, `git show`, `git diff`, `git blame`
- Task: Trace file changes, compare versions

### Day 3: Branching and Merging
- Concepts: Branch theory, HEAD ref, fast-forward vs. merge commit
- Commands: `git branch`, `git checkout`, `git merge`, `git log --graph`
- Task: Create and merge feature branches, resolve a conflict

### Day 4: Remote Repositories and Collaboration
- Concepts: Remotes, tracking branches, sync workflows
- Commands: `git remote`, `git clone`, `git fetch`, `git pull`, `git push`
- Task: Simulate fork/pull/merge cycle

### Day 5: Git Aliases & Power User Configuration
- Concepts: `.gitconfig`, aliasing, log customization, default editor
- Commands: `git config --global alias.*`, `core.editor`, `color.ui`, etc.
- Task: Build a personalized Git experience with aliases

### Day 6: History Rewriting & Sensitive Data Removal
- Concepts: Commit rewriting, rebasing ethics, Git filter-repo usage
- Commands: `git rebase -i`, `git commit --amend`, `git filter-repo`
- Task: Rewrite messy history and remove secrets or binaries

### Day 7: Capstone Simulation & Git Hygiene
- Concepts: Full solo workflow, stashing, cherry-pick, tags, `.gitignore`
- Commands: `git stash`, `git cherry-pick`, `git tag`, `git clean`
- Task: Simulate real-world Git incident with rebasing, tagging, and cleanup

---

## Execution Instructions

- Begin by generating **Day 1 only**, in full mentor-narrative format.
- Include a **checkpoint quiz** at the end.
- Do **not** reveal any content from future days until explicitly asked.
- Support Markdown formatting with code blocks and simulated terminal output.
- Use a supportive, experience-based teaching tone (e.g., “Let me show you how we handle this on a real team…”).

---

## Reminder

Before generating content:
- Allow the user to customize the outline if needed
- Only begin the narrative after confirming the outline is final

Prompt user for their name and confirm they are ready to proceed.

execute prompt now