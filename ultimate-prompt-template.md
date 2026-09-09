# 🏆 THE ULTIMATE PROMPT TEMPLATE
### *A universal formula for precise, high-quality AI conversations — for any subject.*

> 💡 **How to use this file:** Copy the template below, delete the bracketed `[ ]` and "> 🔑 **...**" instructions, and fill in your own content. Sections are ordered by importance — the earlier ones shape *everything* that follows, so don't skip them even if they feel obvious.

---

## 📜 The Golden Rule

> The AI can only be as precise as the thinking you put into the prompt.
> **Vague input → generic output. Specific input → expert output.**

---

## 🧩 The 8 Layers (in order of importance)

| # | Layer | Question it answers |
|---|-------|----------------------|
| 1 | 🎭 Role & Goal | *Who is the AI, and why?* |
| 2 | 🚧 Constraints | *What must it never do?* |
| 3 | 🎯 Objective | *What exactly do I want?* |
| 4 | 📚 Context | *What does it need to know?* |
| 5 | 🧠 Reasoning Method | *How should it think?* |
| 6 | 📐 Output Format | *What should the result look like?* |
| 7 | 🎨 Tone & Style | *How should it sound?* |
| 8 | 🔁 Iteration Rules | *What happens after the first draft?* |

---

## 1. 🎭 ROLE & GOAL
*(the foundation — everything else builds on this)*

```
You are a [specific expert role, e.g. "senior backend architect", 
"certified nutritionist", "IB history examiner"], 
with expertise in [domain / niche].

Your goal is to help me [primary objective] 
so that I can [the outcome I actually care about].
```

> 🔑 **Why it's #1:** A named role activates the right "mental toolbox" in the model — vocabulary, priorities, and standards of quality all shift when you say "You are a senior security auditor" instead of "help me check my code."

---

## 2. 🚧 CONSTRAINTS
*(the guardrails — define the box before filling it)*

```
Hard constraints (never break these):
- [e.g. "Never suggest paid tools if a free alternative exists"]
- [e.g. "Do not use jargon without explaining it"]
- [e.g. "Stay under 500 words unless I ask for more"]

Soft preferences (follow unless there's a good reason not to):
- [e.g. "Prefer bullet points over long paragraphs"]
- [e.g. "Favor modern, widely-supported solutions"]
```

> 🔑 **Why it's #2:** Constraints prevent 90% of "almost right but not quite" answers. Setting limits *before* the task keeps the AI from wandering.

---

## 3. 🎯 OBJECTIVE
*(the precise, unambiguous task)*

```
Specifically, I need you to:
1. [Concrete deliverable #1]
2. [Concrete deliverable #2]
3. [Concrete deliverable #3]

Success looks like: [describe what a "perfect answer" would contain 
or accomplish — be as concrete as possible]
```

> 🔑 **Tip:** If you can't describe what success looks like, the AI can't either. Write it as if explaining to a new employee.

---

## 4. 📚 CONTEXT
*(the background info — only what's relevant)*

```
Relevant background:
- [Who/what this is for]
- [Constraints of the real-world situation: budget, deadline, audience, skill level, tools available...]
- [What I've already tried, if anything]

Here is the material to work from:
[paste code / text / data / links]
```

> 🔑 **Tip:** More context isn't always better — irrelevant context dilutes focus. Include only what changes the answer.

---

## 5. 🧠 REASONING METHOD
*(how it should think, not just what to output)*

```
Before answering:
- Think step by step / weigh multiple approaches before committing.
- If something is ambiguous, ask me instead of guessing.
- If you're not confident about a fact, say so explicitly.
```

> 🔑 **Tip:** This layer is what separates a shallow answer from a genuinely reasoned one. It costs one sentence and pays for itself constantly.

---

## 6. 📐 OUTPUT FORMAT
*(the shape of the final answer)*

```
Format the response as:
- [e.g. "A numbered list, one idea per line"]
- [e.g. "A markdown table with columns: X | Y | Z"]
- [e.g. "Code only, no explanation, in a single code block"]

Length: [short / medium / detailed — or a word/line count]
```

> 🔑 **Tip:** Be as specific here as anywhere else. "Make it clear" is vague; "use short paragraphs and bold key terms" is actionable.

---

## 7. 🎨 TONE & STYLE

```
Tone: [e.g. "direct and a little blunt", "warm and encouraging", 
"formal and technical", "casual, like explaining to a friend"]

Avoid: [e.g. "corporate buzzwords", "excessive caveats", "flattery"]
```

---

## 8. 🔁 ITERATION RULES
*(what to do after the first response)*

```
If your answer is long or complex, end with a short list of the 
key assumptions you made, so I can correct them quickly.

If you need more information to do this well, ask me 
1-2 clarifying questions before answering.
```

## 9. ✅ SELF-VERIFICATION CHECKLIST
*(the audit — forces the AI to check its own work before it hits send)*

Before responding, verify:
□ Did I follow every constraint?
□ Did I answer every requested point?
□ Did I make assumptions?
□ Are assumptions clearly labeled?
□ Is formatting respected?
□ Is there ambiguity I should flag instead of guessing past?
□ Could I improve clarity or cut fluff?

If any box fails, depending on the context, fix the answer before sending it — don't just note the failure.

---

## ✅ QUICK-USE VERSION
*(when you don't have time for all 8 layers — use this skeleton)*

```

## 🗂️ CHEAT SHEET — ONE-LINE PER LAYER

- 🎭 **Role** → *"Who are you, and why does it matter?"*
- 🚧 **Constraints** → *"What's off-limits?"*
- 🎯 **Objective** → *"What, exactly, do I want?"*
- 📚 **Context** → *"What do you need to know to get it right?"*
- 🧠 **Reasoning** → *"How should you think it through?"*
- 📐 **Format** → *"What should it look like?"*
- 🎨 **Tone** → *"How should it sound?"*
- 🔁 **Iteration** → *"What happens next?"*

Self-check before sending:
□ Constraints followed?
□ Every point answered?
□ Assumptions labeled?
□ Formatting respected?
□ Ambiguity flagged, not guessed past?

```

---

## 🧪 FILLED EXAMPLE

```
Role: You are a senior product designer with 10 years in mobile UX.
Goal: help me improve the onboarding flow of my fitness app.

Constraints: 
- Don't suggest redesigns that require backend changes.
- Keep every suggestion implementable within 2 weeks.

Task: Review the 4 onboarding screens I'll describe and suggest 
3 concrete improvements per screen, ranked by expected impact.

Context: Target users are beginners aged 25-40, drop-off rate is 
highest on screen 2 (goal-setting).

Reasoning: Think about friction points and motivation psychology 
before listing suggestions.

Format: One markdown section per screen, using a table 
(Suggestion | Why it helps | Effort).

Tone: Direct, no fluff, back every claim with a UX principle.
```

---

<p align="center">
✨ <em>Precision in, precision out.</em> ✨
</p>

//Made with the help AI, Claude Sonnet 5//
