# DT-Fellowship-Assignment
# 🌳 Deterministic Reflection Agent

**DT Fellowship Assignment — Daily Reflection Tree**

---

## 🔍 Overview

This project is a **deterministic end-of-day reflection system** that guides an employee through a structured self-reflection process.

Unlike AI chatbots, this system:

* Uses **no LLM at runtime**
* Follows a **fully deterministic decision tree**
* Produces **consistent, auditable reflections**

The goal is to transform psychological frameworks into a **navigable, structured experience** — enabling users to reflect deeply without ambiguity.

---

## 🧠 Core Concept

The reflection flow is built across **three psychological axes**:

### 1. Locus — *Victim ↔ Victor*

* Do I see events as happening *to me* or *through my actions*?
* Based on **Locus of Control** (Julian Rotter) and **Growth Mindset** (Carol Dweck)

### 2. Orientation — *Entitlement ↔ Contribution*

* Did I focus on what I received or what I gave?
* Based on **Organizational Citizenship Behavior**

### 3. Radius — *Self ↔ Others*

* Did I think only about myself or also about others?
* Based on **Self-Transcendence** (Maslow) and **Perspective-Taking**

Each axis builds on the previous one:

> Awareness → Contribution → Meaning

---

## 🌳 How It Works

The system is implemented as a **decision tree**:

* Each node is a **question, decision, reflection, or transition**
* Users select from **fixed options only**
* Each option leads to a **predefined next node**
* Signals are recorded to track behavioral patterns

### ✨ Key Properties

* Deterministic (same input → same output)
* No randomness or AI generation
* Fully traceable paths
* Reflection via **predefined templates**, not generated text

---

## 📁 Project Structure

```
dt-reflection-agent/
│
├── README.md
├── write-up.md
├── requirements.txt
│
├── tree/
│   ├── reflection-tree.json
│   ├── reflection-tree.tsv
│   └── tree-diagram.md
│
├── agent/
│   ├── main.py
│   ├── engine.py
│   ├── loader.py
│   └── utils.py
│
├── transcripts/
│   ├── persona-victim.md
│   └── persona-victor.md
│
└── assets/
    └── tree-diagram.png
```

---

## ⚙️ How to Run (CLI Agent)

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the agent

```bash
python agent/main.py
```

---

## 💡 Example Flow

1. User describes their day
2. System detects **agency level (Axis 1)**
3. Moves to **contribution vs entitlement (Axis 2)**
4. Expands perspective to **self vs others (Axis 3)**
5. Generates a **deterministic summary**

---

## 🧾 Sample Output

> "Today you showed internal control, a contribution mindset, and a team-oriented focus. Small shifts here can transform tomorrow."

---

## 🎯 Design Philosophy

This project reflects **knowledge engineering principles**:

* **Structure over generation**
* **Clarity over flexibility**
* **Guided reflection over open-ended input**

The system behaves like a **wise colleague**, not a chatbot:

* No judgment
* No scoring
* No moralizing

Just structured awareness.

---

## 🧪 Bonus Features (Part B)

* CLI-based deterministic agent
* State tracking across axes
* Sample transcripts with different personas
* Tree visualization using Mermaid

---

## 🔬 Psychological Foundations

* Julian Rotter — *Locus of Control*
* Carol Dweck — *Growth Mindset*
* Daniel Organ — *Organizational Citizenship Behavior*
* Abraham Maslow — *Self-Transcendence*

---

## 🚀 What This Demonstrates

* Ability to **translate psychology into systems**
* Strong **tree-based thinking**
* Understanding of **deterministic design**
* Use of AI as a **design tool, not runtime dependency**

---

## 📌 Author

**Rani Jain**
B.Tech (AI/ML) | Aspiring Data Scientist / Knowledge Engineer

---

## 🙌 Final Note

The hardest part of this project is not the code —
it’s designing questions that make someone pause and think after a long day.

This repository is an attempt to do exactly that.
