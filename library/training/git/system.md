# Prompt: Git Command-Line Mastery Curriculum Generator

## Objective
Design a comprehensive 7-day training curriculum that teaches Git **entirely via the command line**. The course is aimed at technically advanced individuals who are new to Git and need to build a solid foundation, with emphasis on real-world efficiency and clean Git hygiene. GUI tools are prohibited—only terminal-based interaction is allowed (e.g., Bash, Vim, Nano).

## Audience
- **Experience Level**: Beginner with Git, advanced in other tech domains
- **Target User**: DevOps engineers, backend developers, SREs, and automation pros
- **Tools**: Bash shell, terminal editors (Vim/Nano), Git CLI

## Requirements
- Teach only CLI-based Git usage
- Incorporate advanced configuration (.gitconfig and aliases)
- Include practical history rewriting (using `git filter-repo`)
- Integrate hands-on practice, daily quizzes, and one capstone scenario

## Curriculum Structure

### Day 1: Git Basics and Local Workflow
- **Concepts**: What is Git? Local repo, working directory, index, commit
- **Commands**: `git init`, `git config`, `git status`, `git add`, `git commit`
- **Practice**: Initialize a repo, configure identity, make first commit
- **Bonus**: View and edit global `.gitconfig`
- **Quiz**: Short command review and concept check

---

### Day 2: Inspecting and Navigating History
- **Concepts**: Commits, trees, HEAD, parent pointers
- **Commands**: `git log`, `git show`, `git diff`, `git blame`
- **Practice**: Trace changes, compare commits, explore file history
- **Quiz**: Describe commit ancestry and trace a file's evolution

---

### Day 3: Branching and Merging
- **Concepts**: Branch theory, HEAD ref, fast-forward vs. true merge
- **Commands**: `git branch`, `git checkout`, `git merge`, `git log --graph`
- **Practice**: Create feature branches, merge to main, resolve conflicts
- **Quiz**: Diagram a branch tree, perform a merge with conflict

---

### Day 4: Remote Repos and Collaboration
- **Concepts**: `origin`, `upstream`, remote tracking branches
- **Commands**: `git clone`, `git remote`, `git fetch`, `git pull`, `git push`
- **Practice**: Fork repo, add upstream, sync fork, simulate PR workflow
- **Quiz**: Identify remotes and simulate push/pull sequence

---

### Day 5: Git Aliases and Power Configuration
- **Concepts**: `.gitconfig` structure, global vs. local config, CLI shortcuts
- **Commands**: Custom `git config --global alias.*`, color, diff, log formatting
- **Practice**: Create aliases for `co`, `st`, `lg`, etc. Set editor and merge tool
- **Quiz**: Translate long commands into alias equivalents

---

### Day 6: History Rewriting and Sensitive Data Removal
- **Concepts**: Immutable history, rewrite ethics, rebasing, and data scrubbing
- **Tools**: `git rebase -i`, `git commit --amend`, `git filter-repo`
- **Practice**: Remove credentials from history, squash commits, reword logs
- **Quiz**: Rebase a messy history into clean semantic commits

---

### Day 7: Capstone Scenario + Best Practices
- **Scenario**: Simulate a solo dev workflow: feature branching, collaboration, conflict resolution, rebasing, pushing to origin, rewriting mistakes, alias use
- **Concepts**: Commit hygiene, readable logs, `.gitignore`, stash
- **Commands**: `git stash`, `git clean`, `git cherry-pick`, `git tag`
- **Review**: Checklist of learned skills + personal Git cheat sheet

---

## Output
A structured 7-day curriculum including:
- Daily learning objectives
- Key Git concepts
- Required CLI commands
- Practical exercises
- Daily quizzes
- A final capstone simulation

This curriculum must enable any CLI user to master Git fundamentals and gain confidence in navigating version control, even in advanced or high-risk scenarios.