# ToM4AI Thinkathon: Task Design Template
**AAAI-2026 Workshop on Theory of Mind for AI**

---

## Team Information
* **Team Name:** _________________________________________________
* **Team Members:** _______________________________________________
* **Core Discipline(s):** (e.g., Cognitive Science, Robotics, NLP)

---

## Page 1: Problem Definition & Ecological Validity

### 1. The Core Social Challenge
*Identify a real-world social interaction where "knowing what the other thinks" is critical for success.*
* **Scenario Context:** (e.g., Healthcare triage, joint creative writing, urban navigation)
* **Targeted Mental State:** What specifically must the agent infer?
    * [ ] False Beliefs
    * [ ] Intentions / Hidden Goals
    * [ ] Reputation / Trust
    * [ ] Sarcasm / Deception
    * [ ] Shared Mental Models

### 2. Task Narrative (The "Vignette")
*Provide a 3–5 sentence story describing the interaction.*
> **Example:** A robotic assistant is helping a team of doctors and nurses. There are multiple tasks, ranging from cleaning and patient monitoring to assisting in the OR. The shifts change every 12 hours, with new events arriving constantly. The robot is tasked with identifying 'points of need' and proactively assisting the human team.

### 3. Breaking the "Toy Game" Mold
*How does this task move beyond 2x2 games or simple sequential grids?*
* **Source of Social "Noise":** (e.g., Ambiguous signals, non-verbal cues)
* **Asymmetric Information:** What does the AI know that the Human doesn't (and vice-versa)?


---

## Page 2: Mechanism, Evaluation & Feasibility

### 4. Technical Mechanism
*How does the agent observe and interact?*
* **Input Modalities:** (e.g., Multi-modal, Text-only, Multi-agent communication)
* **Social Decision Points:** At what specific moment is ToM-based reasoning required?
* **Order of ToM:** Does this require 1st-order ("I think you think") or 2nd-order ("I think you think I think") reasoning? Or even higher?

### 5. Success Metrics & Ground Truth
*How do we verify the AI "used" ToM rather than simple pattern matching?*
* **Ground Truth:** How will we label the "internal states" of the participants?
* **Evaluation Metric:** (e.g., Belief-prediction accuracy, "Social Efficiency" score, Human-Likeness Likert scale)

### 6. Scalability & Implementation
* **Generative Potential:** Can we use LLMs/Procedural Generation/Other tools to create 1,000 variants of this task?
* **Primary Bottlenecks:** (e.g., "Requires high-fidelity human-in-the-loop data.")

---
*ToM4AI Workshop @ AAAI-2026*