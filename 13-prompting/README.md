# 13 — Prompting / Prompt Engineering

This project is part of the **AI / LLM Learning Demos** series.

Topic 13 focuses on **Prompting and Prompt Engineering** — how to communicate clearly with Large Language Models so that they produce useful, structured, safe, and task-appropriate outputs.

This version is the **final expanded study version** with deeper learning blocks and Topic 11-style UX.

---

## Core Idea

Prompting shapes the context that the model uses for next-token prediction.

```text
Better prompt → better context → better next-token prediction → better output
```

A good prompt gives the model:

```text
task
context
audience
format
constraints
goal
examples when needed
guardrails when risk exists
```

---

## What This Topic Covers

The page includes **51 full study sections** covering:

* What is a prompt?
* Why prompting matters
* Prompting vs model training
* Anatomy of a good prompt
* Role, task, context, audience, format, and constraints
* Zero-shot prompting
* Few-shot prompting
* Instruction prompting
* Role prompting
* Step-by-step prompting
* Key reasoning steps
* Decomposition prompting
* Self-check prompting
* Critique-and-improve prompting
* Compare-and-choose prompting
* Persona Pattern
* Template Pattern
* Question Refinement Pattern
* Cognitive Verifier Pattern
* Audience-Aware Explanation Pattern
* Example-First Pattern
* Analogy Pattern
* Output Contract Pattern
* Guardrail Pattern
* Rubric Pattern
* Prompting for explanation
* Prompting for coding
* Prompting for debugging
* Prompting for study material
* Prompting for business writing
* Prompting for data extraction
* Prompting for classification
* Prompting for planning
* Prompting for transformation
* Prompting for agents and tool use
* Temperature, top-p, max tokens, and context window
* Prompt problems
* Prompt engineering workflow
* Prompt as API contract
* Prompt versioning, testing, evaluation, and libraries
* Prompt injection and security
* System prompt vs developer prompt vs user prompt
* Prompt chaining
* Prompt routing
* Prompt compression
* Prompt cost awareness
* Prompt observability
* Human-in-the-loop prompting
* Prompt anti-patterns
* Master prompt patterns map

---

## Expanded Study Format

Each study section includes:

```text
simple meaning
detailed explanation
weak prompt example
strong prompt example
common mistake
memory line
```

Important sections also include deeper learning blocks:

```text
when to use
when not to use / caution
developer / production view
mini exercise
mini checklist
```

Expanded sections include:

* Prompt Anatomy
* Zero-shot Prompting
* Few-shot Prompting
* Output Contract Pattern
* Guardrail Pattern
* Prompting for Coding
* Prompting for Debugging
* Prompting for Data Extraction
* Prompting for Classification
* Prompting for Agents and Tool Use
* Prompt Injection and Security
* Prompt as API Contract
* Prompt Engineering Workflow
* Prompt Versioning, Testing, Evaluation, and Libraries

---

## Included Interactive Demos

The page includes practical demos at the bottom:

1. Prompt Builder
2. Weak vs Strong Prompt
3. Zero-Shot vs Few-Shot Demo
4. Temperature Simulator
5. Output Contract Builder
6. Guardrail Builder
7. Audience Switcher
8. Prompt Debugger
9. Prompt Injection Safety Check
10. Quiz

The final version also includes:

* Final Master Checklist
* “Which Prompt Pattern Should I Use?” decision table

---

## Learning Goals

By the end of this topic, the learner should be able to:

* Understand what a prompt is
* Understand how prompts influence next-token prediction
* Write clearer prompts using role, task, context, audience, format, and constraints
* Use zero-shot and few-shot prompting correctly
* Create prompts for explanation, coding, debugging, study material, writing, extraction, classification, planning, and transformation
* Use output contracts for structured output
* Add guardrails to reduce guessing, hallucination, unsafe behavior, and format failure
* Understand how prompting connects to RAG, tool calling, and agents
* Understand prompt injection risks
* Treat prompts as reusable, testable, versioned assets
* Think of prompts as API contracts in developer workflows

---

## UI Features

The page follows the same UX direction as the earlier **11 — Transformer Architecture** topic.

Features include:

* Sticky top toolbar
* Dark/light mode toggle
* Floating Show/Hide controls on the right
* Collapsible study sections
* Compact study-card layout
* Dark hero section
* Demos separated at the bottom
* Mobile-friendly layout
* No external libraries
* Single-file HTML/CSS/JS structure

---

## Notes

This topic is an important bridge between LLM foundations and applied GenAI systems.

Previous topics prepared the foundation:

* Tokens
* Embeddings
* Sequence Learning
* Attention
* Transformer Architecture
* Pretraining / Next-Token Prediction

This topic teaches how to communicate with LLMs effectively and safely.

Next topics can build toward:

* RAG
* Tool Calling
* Agents
* Agentic AI workflows
* Enterprise GenAI applications
