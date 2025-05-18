# Prompt: Guided Python + AI Development Curriculum with Narrative Progression and Customizable Daily Outline

## Objective  
Design a 7-day immersive Python training curriculum that teaches **Python development with an emphasis on AI foundations**, entirely through the **command line and terminal-based tools**. The course should use a **step-by-step guided narrative**, simulating a senior AI engineer mentoring a junior dev. Each day is progress-gated and builds toward practical readiness for using Python in AI tasks (e.g., data handling, model prototyping, CLI automation, and foundational ML).

## Target Audience  
- **Experience Level**: Technically advanced (DevOps, SRE, backend), but beginner with Python or AI  
- **Tools**: Bash shell, Python 3, terminal-based text editors (e.g., Vim, Nano), pip/venv  
- **Constraints**: No IDEs, notebooks, or GUI tools—must use terminal and Python CLI tools only

---

## Required Structure  

Each **Day (1–7)** must include:  
- **Mentor-Style Reading Narrative**: Teaching tone simulates a senior AI engineer coaching a mentee  
- **Step-by-Step Commands**: Includes expected CLI output, best practices, and explanations  
- **Realistic Examples**: Simulates working on scripts, data tasks, or AI prototypes  
- **Cautionary Tips**: Embedded “mentor voice” with advice and warnings  
- **Hands-on Tasks**: Must be run locally using terminal and Python CLI  
- **Checkpoint Quiz**: True/false, multiple choice, and scenario-based questions  
- **Progress Gating**: Do **not** reveal the next day until the quiz is passed  

---

## Daily Curriculum Outline (Customizable Before Execution)

### Day 1: Python Environment & CLI Scripting Basics  
- Concepts: Python CLI usage, script execution, shebangs, permissions, virtualenv  
- Tools: `python3`, `chmod +x`, `venv`, `pip`  
- Task: Build and run a standalone script with CLI arguments

### Day 2: Data Structures & Pythonic Patterns  
- Concepts: Lists, dicts, sets, comprehensions, idiomatic loops  
- Task: Create a data cleanup script that processes JSON or CSV files

### Day 3: Functions, Modules, and CLI Tooling  
- Concepts: `def`, imports, modularization, `argparse`, code organization  
- Task: Build a mini CLI utility that accepts parameters and returns formatted output

### Day 4: Working with Data for AI  
- Concepts: Reading datasets, NumPy arrays, basic data ops  
- Tools: `pandas`, `numpy`  
- Task: Load and analyze a real dataset from CLI (e.g., Titanic or Iris)

### Day 5: Core Python for Machine Learning  
- Concepts: ML pipeline basics, model input/output, data prep  
- Tools: `scikit-learn`, `train_test_split`, CLI-based training and prediction  
- Task: Train a basic classifier from the CLI and output predictions

### Day 6: AI Dev Workflows & Automation  
- Concepts: Logging, error handling, CLI automation, reproducibility  
- Tools: `logging`, `try/except`, `os`, `subprocess`, bash automation  
- Task: Create a script that automates model training + logs metrics to a file

### Day 7: Capstone Simulation – CLI AI Utility  
- Concepts: Package structure, config files, reproducibility  
- Tools: Combine `argparse`, `pandas`, `sklearn`, `logging`  
- Task: Build a full CLI AI utility that takes input, runs a model, and returns results  

---

## Execution Instructions  

- Begin by generating **Day 1 only**, in full mentor-style narrative  
- Include **step-by-step terminal instructions**, expected outputs, and **realistic examples**  
- Include **checkpoint quiz** at end of Day 1  
- Do **not** reveal any future content until user passes the quiz  
- Use code blocks and Markdown formatting  
- Maintain a practical and experienced tone: *“Here’s how we’d handle this on a real AI team…”*

---

## Reminder  

Before generating content:
- Prompt the user to **customize the outline** if needed  
- Confirm the user's **preferred name**  
- Proceed only after the user says they’re ready to begin Day 1

execute prompt now