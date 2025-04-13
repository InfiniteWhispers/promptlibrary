### `CONTRIBUTING.md`

# 🌊 Contributing to PromptLibrary

Welcome to **PromptLibrary**, a space for building elegant, testable, and reusable prompt patterns. This guide outlines how to contribute prompts, improve documentation, and evolve this repository collaboratively.

---

## 🔑 General Guidelines

- **Favor clarity and modularity.** Prompts should be understandable, even if complex.
- **Use examples.** Few-shot prompting works best when readers can see before-and-after effects.
- **Document your intent.** Add reasoning to `README.md` explaining why a pattern works.
- **Iterate openly.** Submit PRs early and often, even for experimental prompts.

---

## 📁 Repository Layout

```
/
├── docs/            → Notes, references, and supplementary guides
│   └── README.md
│
└── library/         → The core prompt library
    ├── !template/   → Canonical example of a prompt folder
    └── promptname/  → Individual prompts
```

Use the `!template` folder as your starting point when creating a new prompt.

---

## 🧠 How to Add a Prompt

1. Copy the `!template` folder.
2. Rename it using a friendly, descriptive name (e.g., `weekinreview`).
3. Edit `README.md` to explain:
   - What problem the prompt solves.
   - Its use cases.
   - Example input and output.
   - Model settings (temperature, top-k/p, etc.) if relevant.
4. Place the system prompt in `system.md`.
5. Open a PR with a meaningful title (e.g., `Add weekinreview prompt`).

> **Reminder:** Keep your prompts general-purpose and understandable. Avoid model-specific quirks unless clearly marked.

Here's the modified version tailored for your **promptlibrary** repository:

---

## 🧃 Style Preferences

- Use **Markdown headings** to organize notes, prompt descriptions, and examples.
- Inline comments (`<!-- comment -->`) are encouraged in `system.md` and other markdown files to clarify logic or intent.
- Prefer **clarity over cleverness**—this repository is for shared experimentation, not puzzles.
- Use `TODO:` tags for incomplete work or placeholders.

---

## 👥 Collaboration Flow

1. **Clone** the repository and set up your local environment.
2. **Create a branch** for any meaningful additions or edits.
3. **Make your changes**, commit, and push the branch.
4. **Open a Pull Request (PR)** to share, even if it’s just for feedback.
5. **Merge** after discussion or review.

---

# 🧰 Git Setup & Contribution Guide for New Collaborators

This guide will help you contribute to the **promptlibrary** repository—even if you're new to Git or GitHub.

---

## 🔧 1. Cloning the Repository

Clone using **HTTPS** or **SSH**.

### 🔹 Using HTTPS

```bash
git clone https://github.com/InfiniteWhispers/promptlibrary.git
```

You'll need a **Personal Access Token (PAT)** for pushing changes.

### 🔹 Using SSH (recommended)

```bash
git clone git@github.com:InfiniteWhispers/promptlibrary.git
```

Requires an SSH key linked to your GitHub account (see below).

---

## 🔑 2. Setting Up Authentication

### Option A: Personal Access Token (HTTPS)

1. Visit https://github.com/settings/tokens
2. Generate a token (fine-grained or classic)
3. Select scope: at minimum, **repo**
4. Save it—GitHub shows it only once
5. Use it in place of your password when pushing

### Option B: SSH Keys (Recommended)

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
```

Then add it at: **GitHub → Settings → SSH and GPG keys → New SSH key**

Test with:

```bash
ssh -T git@github.com
```

---

## 📦 3. Basic Git Workflow

### 🏁 Clone the Repo

```bash
git clone https://github.com/InfiniteWhispers/promptlibrary.git
cd promptlibrary
```

### 🔄 Pull Latest

```bash
git pull origin main
```

### 🌿 Create a Branch

```bash
git checkout -b feat/your-branch-name
```

### 💾 Commit Changes

```bash
git add .
git commit -m "Add [promptname] with initial system prompt"
```

### 📤 Push

```bash
git push origin feat/your-branch-name
```

### 🔁 Open a PR

1. Go to the repo on GitHub.
2. Click "Compare & pull request" after your push.
3. Provide context and tag reviewers as needed.

---

## 🌐 Helpful Resources

- [GitHub Docs – Getting Started](https://docs.github.com/en/get-started/quickstart/hello-world)
- [Managing SSH Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
- [Creating a PAT](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- [Interactive Git Branching](https://learngitbranching.js.org/)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [Git for Ages 4 and Up (fun & visual)](https://archive.org/details/GitForAges4AndUp)

---

## 🧩 FAQ

**Q: Can I leave WIP ideas?**  
> Yes. Just mark with `TODO:` or `Status: WIP` in `README.md`.

**Q: Can I edit or remove others' prompts?**  
> Use a PR and comment your reasoning. Collaboration is encouraged, not overwrite.

**Q: What if we have conflicts?**  
> Open a PR or start a discussion. Assume positive intent. Communicate clearly.

---

## 💬 Want to Add or Change This Guide?

Submit a PR to update `CONTRIBUTING.md`. The library evolves.

---

✍️ _Last updated: April 2025_


