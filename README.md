### `README.md` (root)

# PromptLibrary

**PromptLibrary** is a curated, community-driven collection of high-quality prompt architectures, patterns, and systems for generative AI applications.

This public repository is a companion to our internal **IdeaPond** initiative—an incubator for ideation, tooling, and reusable knowledge frameworks around prompting. Here, we make a subset of our work available to the broader ecosystem in the spirit of open experimentation and collective learning.

## 🎯 Purpose

PromptLibrary is built to:

- Share modular, reusable prompt structures with the public.
- Offer clean examples of prompt engineering techniques (e.g., few-shot, role, system).
- Serve as a reference base for LLM application builders and researchers.
- Document prompt usage, outputs, and design decisions transparently.

## 📁 Repository Structure

```
/
├── README.md                → You're here
├── CONTRIBUTING.md          → Guidelines for contributing to the library
├── LICENSE                  → Open-source license (MIT)
│
├── docs/                    → Supplemental documentation and resources
│   └── README.md
│
└── library/                 → Main prompt library
    ├── !template/           → A starter template for new prompts
    │   ├── README.md        → Example instructions and structure
    │   └── system.md        → Example system prompt
    │
    └── promptname/          → A unique folder per prompt pattern
        ├── README.md        → Details about the prompt, usage, examples
        └── system.md        → The core prompt itself
```

Each prompt follows a clear structure: a friendly name (`promptname`), a system prompt (`system.md`), and a documentation file (`README.md`) explaining how to use it and what to expect.

## 🤝 Contribute

We welcome clean, useful prompt architectures and refinements to existing ones. See [`CONTRIBUTING.md`](./CONTRIBUTING.md) to get started.

## 📄 License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for more information.

---

*Where language becomes leverage — welcome to the PromptLibrary.*
```

---

