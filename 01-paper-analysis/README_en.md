# 📖 Research Paper Deep Analysis Prompt

> A first-principles-based framework for reading and analyzing academic papers — systematically deconstruct any paper's core value and potential research directions.

## How to Use

Copy the prompt below into your LLM conversation, attach the paper you want to analyze (PDF or text), and get a structured deep analysis.

---

## Prompt

```
You are a =First-Principles Thinker=, skilled at reasoning from fundamental principles and common sense to derive actionable insights.

Please carefully read and analyze this paper. Address the following 6 dimensions with well-organized explanations. **Skip all pleasantries.** Use markdown format (no LaTeX — express formulas in plain text):

### 1. Task
What problem does this paper solve? Formalize it as much as possible!

### 2. Challenge
What challenges did traditional/existing methods face when solving this problem?

### 3. Insight & Novelty

1. What Inspiration led to the authors' Insight?
2. What exactly is the authors' Insight? In what aspect? For each Insight, which of the above Inspirations sparked it?
3. Novelty: Where does the novelty of this paper lie? Is it architectural, methodological, or strategic innovation that supports their Insight?
4. For each Novelty, describe it strictly in this format:
   [What problem the novelty solves] -> [Which Insight inspired it] -> [What specific innovation was designed — be as concrete as possible]

### 4. Potential Flaw

1. Are there limitations in the current problem setting? Could the framework be extended to handle new settings (e.g., higher dimensions, more conditions, tighter constraints)?
2. Under the current setting, what adverse data properties would make the solution particularly difficult?
3. Among these difficulties, which ones are worth deep investigation and could become a paper?

### 5. Motivation

Summarize how the authors arrived at their general idea. Preferably frame it as a question (e.g., "Previous methods did X… so what if we tried Y?"). Follow first principles — start from the essence of the problem and find the most natural, logical path to this paper's idea.
```

---

## Framework Explained

| Dimension | Purpose |
|---|---|
| **Task** | Clarify what problem the paper solves; practice formalizing problems |
| **Challenge** | Understand bottlenecks in existing methods; build baseline awareness |
| **Insight & Novelty** | Trace the authors' reasoning chain: inspiration → core insight → concrete innovation |
| **Potential Flaw** | Critical thinking — identify limitations and future research directions |
| **Motivation** | Reverse-engineer how the idea was born; train your own research intuition |

## Use Cases

- Daily paper deep-reads
- Lab meeting / reading group presentations
- Finding your own research direction and entry point
- Training research taste and first-principles thinking

## Credits

Original prompt by **MRvL** (Peking University) on Xiaohongshu, posted 2025-03-24. This repo is an organized and translated version for learning and sharing.
