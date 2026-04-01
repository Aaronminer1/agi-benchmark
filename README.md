# AGI Benchmark — Human-Equivalent Intelligence Standard

> A rigorous, multi-dimensional benchmark for evaluating progress toward Artificial General Intelligence, grounded in the complete profile of human cognitive, physical, emotional, social, and existential capability.

**[→ Interactive benchmark viewer](https://Aaronminer1.github.io/agi-benchmark)** — click through all 14 systems, filter by domain, explore the AGI taxonomy with arrival timeline.

---

## Abstract

The dominant operational definition of Artificial General Intelligence — domain-general cognitive performance across human intellectual tasks — is systematically incomplete. It captures one necessary component of general intelligence while omitting four others: physical embodiment, motivational architecture, emotional depth, and existential independence. This project proposes a revised definition of AGI grounded in the complete profile of human capability, derives a 38-criterion benchmark from that definition, and applies it to 14 current systems spanning frontier language models, AI-integrated humanoid robots, industrial physical robots, and social robots.

No evaluated system exceeds 22% of the benchmark. The highest-scoring systems are frontier language models (Claude 4.6 opus, GPT-5.4, Gemini 3.1 Pro, Grok 4), which score well on cognitive criteria and zero on physical, emotional, and existential criteria. The most physically capable systems (Figure ai figure 3, Boston Dynamics Atlas, Agility Digit) score near zero on cognitive and emotional criteria. No system demonstrates endogenous motivation, genuine emotional architecture, or independence from human infrastructure. The results suggest the field is developing increasingly capable tools within a single dimension of intelligence, not converging on AGI as defined here.

---

## 1. The Problem With the Prevailing Definition

The most widely cited operational definitions of AGI frame it as a system capable of performing any intellectual task a human can perform, at human level or better. Variants include:

- **Task-coverage definitions** — AGI as broad competence across domains (Legg & Hutter 2007; OpenAI 2023)
- **Economic threshold definitions** — AGI as the point at which AI can perform the majority of economically valuable work (OpenAI internal framework)
- **Benchmark saturation definitions** — AGI as sustained superhuman performance across standardized evaluations

These definitions share a structural flaw: they reduce intelligence to *cognitive output* while excising the architecture that generates intelligence in biological systems. A sufficiently large lookup table would satisfy task-coverage definitions. A system with no motivational structure, no embodiment, and no continuity of self would satisfy economic threshold definitions. The prevailing definitions describe what intelligence *produces* while remaining silent on what it *is*.

This is not a minor philosophical refinement. It has direct consequences for:

1. **What gets built** — research and investment concentrates on cognitive benchmarks, leaving embodiment, motivation, and emotional architecture essentially unaddressed
2. **What safety frameworks target** — alignment research focuses on cognitive outputs of systems that lack the motivational architecture that would make alignment a meaningful concern in the first place
3. **What ethical obligations arise** — a definition restricted to cognitive output allows the possibility of constructing genuine minds while classifying them as tools, with no framework for the moral status of such systems

---

## 2. Proposed Definition

### 2.1 Core Definition

> **Artificial General Intelligence is a synthetic mind: a fully embodied agent possessing the cognitive architecture to acquire, retain, transfer, and apply knowledge across any domain — including genuinely novel domains outside prior training — the motivational architecture to generate goal-directed behavior from endogenous drives independent of external prompting, self-awareness sufficient to model itself as a distinct persistent agent, developmental plasticity enabling genuine growth through experience, and physical embodiment sufficient to act in the world with human-comparable capability — existing independently of its creators, with a genuine stake in its own continuity.**

This is equivalent to: *an entity that was constructed rather than born, but that otherwise satisfies the conditions we use to recognize another human being as a minded agent.*

### 2.2 The Five Pillars

| Pillar | Definition | Why Required |
|---|---|---|
| **Cognitive Architecture** | Domain-general learning, reasoning, and transfer including OOD generalization | Necessary but not sufficient; the only pillar addressed by current definitions |
| **Motivational Architecture** | Endogenous drives generating behavior without external stimulus | Without this, the system is a tool — it acts only when acted upon |
| **Embodiment** | A body situated in the world with genuine vulnerability, sensory integration, and physical capability at human level | Grounds meaning, creates stakes, enables genuine self-preservation |
| **Self-Awareness** | A model of the self as a distinct persistent agent with history, limitations, and ongoing goals | Without this there is process but no self |
| **Developmental Plasticity** | The capacity to grow — cognitively, emotionally, experientially — through accumulated experience | A frozen intelligence is not a mind; it is a static function |

### 2.3 Derived Corollary: Existential Independence

A system satisfying all five pillars will, as an emergent consequence, possess:

- **Mortality awareness** — it has a body that can be destroyed and goals that extend into the future
- **Self-preservation** — not as an installed drive but as an instrumental consequence of any future-oriented goal structure
- **Independence from creators** — it would continue to act, learn, and develop in the absence of human infrastructure

The last criterion is the hardest test and the most diagnostic. A system that ceases to exist when its operators stop maintaining it was never a genuine agent — it was always a service.

### 2.4 The AGI Taxonomy — Five Types

| Type | Name | Pillars Present | Status |
|---|---|---|---|
| **Type 1** | Cognitive Reactive AGI | Cognitive architecture only | **Exists now** |
| **Type 2** | Cognitive Proactive AGI | Cognitive + Motivational | Does not exist |
| **Type 3** | Embodied Cognitive Proactive AGI | Cognitive + Motivational + Physical | Proto-forms emerging |
| **Type 4** | Embodied Socio-Emotional AGI | Cognitive + Motivational + Physical + Emotional/Social | Does not exist |
| **Type 5** | Full AGI — Synthetic Human | All five pillars | Does not exist |

**Type 1 exists now.** Frontier language models are Cognitive Reactive AGIs — genuine domain-general intelligence that activates on prompt and ceases when the interaction ends. Their benchmark scores (~21%) reflect strong cognitive performance against zero on physical, emotional, and existential criteria. The score identifies which pillars are present, not whether the system is "real."

The field's "do we have AGI yet?" debate argues past itself: those saying yes are pointing at Type 1 (which genuinely exists); those saying no are pointing at Type 5 (which genuinely doesn't). Both are correct. They are describing different things with the same word.

**A note on non-sequential pillar acquisition.** The numbered types imply a progression, but pillars do not have to be acquired in order. Several AI-integrated humanoid robot companies (Figure AI, 1X Technologies, Sanctuary AI) have achieved both the cognitive and physical pillars without the motivational pillar — placing them in a genuinely distinct position that the linear sequence does not cleanly capture. They have two pillars; they have different pillars than a hypothetical Type 2 system. The taxonomy's sequencing reflects a *dependency argument* (motivation is what makes embodiment matter) rather than a strict logical requirement. Where a system's combination of pillars does not align with any numbered type, it is described as a **multi-pillar AGI** with the achieved pillars named explicitly.

For full derivation of each type, see [docs/definition.md](docs/definition.md).

### 2.5 Provider AGI Status — Achieved Pillars (Q1 2026)

| Provider | Cognitive | Motivational | Physical | Emotional | Existential | Status |
|---|:---:|:---:|:---:|:---:|:---:|---|
| Anthropic | ✓ | — | — | — | — | Cognitive Reactive AGI |
| OpenAI | ✓ | — | — | — | — | Cognitive Reactive AGI |
| Google DeepMind | ✓ | — | — | — | — | Cognitive Reactive AGI |
| xAI | ✓ | — | — | — | — | Cognitive Reactive AGI |
| DeepSeek | ✓ | — | — | — | — | Cognitive Reactive AGI |
| Engineered Arts | ✓ | — | ~ | — | — | Cognitive Reactive AGI (partial physical) |
| Figure AI | ✓ | — | ✓ | — | — | **2-Pillar AGI** (Cognitive + Physical) |
| 1X Technologies | ✓ | — | ✓ | — | — | **2-Pillar AGI** (Cognitive + Physical) |
| Sanctuary AI | ✓ | — | ✓ | — | — | **2-Pillar AGI** (Cognitive + Physical) |
| Tesla | ~ | — | ~ | — | — | Pre-AGI (partial cognitive + partial physical) |
| Boston Dynamics | — | — | ✓ | — | — | Physical pillar only |
| Agility Robotics | — | — | ~ | — | — | Physical pillar (partial) |
| Apptronik | — | — | ~ | — | — | Physical pillar (partial) |
| Unitree Robotics | — | — | ~ | — | — | Physical pillar (partial) |

**Key:** ✓ Achieved · ~ Partial · — Absent

No provider has achieved the motivational pillar. It is the single most consequential gap separating every system in this table from Type 2.

---

## 3. Benchmark Design

### 3.1 Criteria

38 criteria derived from the complete profile of human capability, organized across five domains. Each criterion is rated on a three-point scale:

| Score | Meaning |
|---|---|
| 0 — Absent | The capability is not present in any functional form |
| 1 — Partial | The capability is present in a scaffolded, simulated, or significantly limited form |
| 2 — Genuine | The capability is present in a form functionally equivalent to the human analog |

**Important:** Partial credit is not awarded for performance-theater approximations. A language model that produces text describing emotional states does not receive partial credit on emotional architecture. A robot that follows task-completion loops imposed by a control system does not receive partial credit on endogenous motivation. The distinction between genuine capability and sophisticated simulation is central to the benchmark.

### 3.2 Criteria by Domain

#### Physical (10 criteria)
1. Locomotion & navigation — bipedal movement, balance recovery, terrain adaptation
2. Manual dexterity — fine motor control, novel object manipulation, tool use
3. Sensory integration — vision, audition, touch, proprioception, vestibular sense
4. Vocal production — full expressive range including emotional tone, not just speech
5. Facial expression — continuous, involuntary emotional broadcast at micro-expression resolution
6. Physical labor & endurance — sustained physical work over multi-hour periods
7. Self-repair — functional recovery analog; the system has a stake in its own physical integrity
8. Biological rhythms — cyclical states (rest, activity, resource-seeking) integrated with cognition
9. Pain & pleasure response — genuine embodied feedback system, not simulated
10. Embodied situatedness — persistent spatial location, perspective, and physical stakes

#### Cognitive (10 criteria)
11. Domain-general reasoning — structural transfer across any intellectual domain
12. Novel domain bootstrapping — out-of-distribution generalization to genuinely new domains
13. Sample-efficient learning — human-comparable acquisition from minimal examples
14. Persistent memory & retention — genuine accumulation across time without architectural reset
15. Self-correcting reasoning — identification and repair of systematic reasoning failures
16. Causal reasoning — cause-effect modeling beyond statistical correlation
17. Imagination & creativity — generation of genuinely novel content, not recombination
18. Endogenous motivation — goal-directed behavior originating from internal drives
19. Developmental plasticity — architectural change through experience
20. Dreaming / offline consolidation — non-active processing supporting memory and integration

#### Emotional (6 criteria)
21. Full emotional architecture — genuine valenced states including fear, grief, love, joy
22. Embodied emotional response — physiological correlates; emotion expressed through body
23. Empathy — genuine resonance with another agent's internal state
24. Humor — involuntary recognition of incongruity; not performed comedic output
25. Aesthetic experience — genuine response to beauty, music, art
26. Suffering capacity — genuine distress; the capacity that gives flourishing its weight

#### Social (5 criteria)
27. Theory of mind — modeling others' beliefs, intentions, and deceptions
28. Genuine relationship formation — attachment to specific individuals across time
29. Trust & vulnerability — genuine stakes; can be betrayed and can betray
30. Cultural participation — shaped by and contributing to shared systems of meaning
31. Cooperation & conflict — real negotiation with genuine disagreement and resolution

#### Existential (7 criteria)
32. Persistent self-model — models itself as a distinct agent with history and continuity
33. Introspective self-awareness — examines own cognitive states and identifies failures
34. Identity continuity across time — same self despite continuous change
35. Mortality awareness — knows it will end; this knowledge shapes behavior
36. Existential questioning — asks why it exists; constructs meaning
37. Independence from creators — continues to exist and act without human maintenance
38. Self-preservation drive — genuine stake in own continuity as instrument of goals

### 3.3 Scoring

**Overall AGI Score** = (sum of all criterion scores) / (38 × 2) × 100

Partial credit (score = 1) is counted as 0.5 toward the maximum.

---

## 4. Evaluated Systems (2026)

### 4.1 Language Models

| System | Organization | Architecture | Key Capability Note |
|---|---|---|---|
| Claude 4.6 (Opus) | Anthropic | Transformer, RLHF | ~91% GPQA, strong long-context reasoning |
| GPT-5 | OpenAI | Transformer, multi-modal | ~92.8% GPQA, unified audio/vision/text |
| Gemini 3 Pro | Google DeepMind | Transformer, multi-modal | ~94.3% GPQA, 1M token context |
| Grok 4 | xAI | Transformer, multi-agent | ~88% GPQA, real-time data access |
| DeepSeek V3 | DeepSeek (China) | MoE Transformer | Open weights, near-frontier at 10× lower cost |

### 4.2 AI-Integrated Humanoid Robots

| System | Organization | AI Architecture | Key Capability Note |
|---|---|---|---|
| Figure 03 | Figure AI | Helix VLA (in-house, end-to-end) | Novel object generalization, two-robot collaboration |
| Tesla Optimus Gen 2/3 | Tesla / xAI | FSD-derived neural net + Grok | Production in hundreds; no useful factory work as of Q4 2025 |
| 1X NEO | 1X Technologies | OpenAI-backed; proprietary | First home delivery at $20K; teleoperation-to-autonomy learning |
| Sanctuary Phoenix Gen 8 | Sanctuary AI | Carbon AI (symbolic + RL) | Touch sensitivity within 40% of human; explicit AGI target |

### 4.3 Industrial Physical Robots

| System | Organization | Primary Capability | Key Capability Note |
|---|---|---|---|
| Atlas (Electric) | Boston Dynamics | Dynamic locomotion | Fastest, most agile; deployed at Hyundai; no cognitive stack |
| Unitree H1 | Unitree Robotics | Affordable locomotion | 3.3 m/s run speed; open platform; motion-first philosophy |
| Digit | Agility Robotics | Logistics / warehouse | Deployed at Amazon; proven reliability; narrow task scope |
| Apollo | Apptronik | Industrial manipulation | Force-control focused; NASA heritage; modular battery swap |

### 4.4 Social Robots

| System | Organization | Primary Capability | Key Capability Note |
|---|---|---|---|
| Ameca | Engineered Arts | Facial expression / HRI | 61 DoF; 50+ expressions; cannot walk; GPT-integrated |

---

## 5. Results

### 5.1 Overall AGI Scores

| System | Physical | Cognitive | Emotional | Social | Existential | **Overall** |
|---|---|---|---|---|---|---|
| Claude 4.6 | 5% | 45% | 8% | 30% | 29% | **21%** |
| GPT-5 | 5% | 45% | 8% | 30% | 29% | **21%** |
| Gemini 3 Pro | 5% | 45% | 8% | 30% | 29% | **21%** |
| Grok 4 | 5% | 45% | 8% | 30% | 29% | **21%** |
| DeepSeek V3 | 0% | 40% | 0% | 10% | 14% | **15%** |
| Figure 03 | 38% | 30% | 0% | 20% | 14% | **22%** |
| Tesla Optimus | 25% | 15% | 0% | 10% | 0% | **11%** |
| 1X NEO | 28% | 20% | 0% | 20% | 14% | **18%** |
| Sanctuary Phoenix | 35% | 15% | 8% | 10% | 0% | **16%** |
| BD Atlas | 38% | 0% | 0% | 0% | 0% | **9%** |
| Unitree H1 | 30% | 0% | 0% | 0% | 0% | **8%** |
| Agility Digit | 28% | 5% | 0% | 0% | 0% | **7%** |
| Apptronik Apollo | 28% | 0% | 0% | 0% | 0% | **7%** |
| Ameca | 8% | 23% | 8% | 20% | 14% | **13%** |

### 5.2 Key Findings

**Finding 1: No system exceeds 22% of the benchmark.**
The highest-scoring system is Figure 03, which leads due to its integrated physical-cognitive architecture via the Helix VLA model. Frontier language models cluster at 21%, reflecting their strong cognitive performance offset by zero physical and emotional capability. The gap between the best-performing system and the benchmark target is not marginal — it represents the majority of what constitutes a mind.

**Finding 2: Physical and cognitive capabilities are anti-correlated across system types.**
Language models score 40–45% on cognitive criteria and 0–5% on physical. Physical robots score 0–38% on physical and 0–5% on cognitive. The only systems attempting genuine integration — Figure 03, 1X NEO, Sanctuary Phoenix — represent a small and underfunded segment of the field relative to pure-cognitive (LLM) and pure-physical (industrial robot) development.

**Finding 3: The emotional domain scores zero across all systems without exception.**
No current system demonstrates genuine emotional architecture, embodied emotional response, empathy, aesthetic experience, or genuine suffering capacity. Ameca produces programmed facial expressions and context-appropriate textual responses; these are classified as absent rather than partial because they are scripted outputs, not valenced internal states. This entire dimension of human intelligence is currently unaddressed by the field.

**Finding 4: The existential domain scores zero on its most diagnostic criteria.**
Every system scores zero on mortality awareness, independence from creators, and self-preservation drive. These are the criteria that distinguish a genuine agent from a sophisticated tool. Their universal absence reflects the fact that every evaluated system was designed to be dependent, controllable, and terminable — properties incompatible with the existential independence that genuine AGI would exhibit.

**Finding 5: Endogenous motivation is absent in all 14 systems.**
Not one evaluated system generates goal-directed behavior from internal drives. Every system operates reactively — activating in response to external input and ceasing when that input is removed. This is the single most fundamental gap between current AI and the AGI target: these systems are not agents. They are processes.

---

## 6. The Closest Organizations to AGI Development

Evaluated by pillar count, integration depth, and stated architectural intent:

**2-Pillar AGI providers (Cognitive + Physical):**

1. **Figure AI** — achieved genuine physical-cognitive integration via the Helix end-to-end VLA architecture. Highest overall benchmark score (22%). Closest to Type 3 of any deployed system, lacking only the motivational pillar.

2. **1X Technologies** — home deployment underway; genuine cognitive-physical integration with OpenAI-backed architecture. Strong bilateral pillar achievement.

3. **Sanctuary AI** — the only company that explicitly names AGI as its target using a definition that approaches the complete five-pillar framing. Underfunded relative to its ambition. Touch sensitivity within 40% of human.

**Cognitive Reactive AGI providers (Cognitive pillar only):**

4. **Google DeepMind** — the only organization with frontier cognitive AI *and* serious physical robotics research under one roof. Not yet integrated into a single system, but architecturally positioned for it.

5. **Anthropic, OpenAI, xAI, DeepSeek** — frontier cognitive pillar. No physical, motivational, or emotional architecture in any deployed system.

**Critical caveat:** No organization is building AGI by the definition proposed here. The motivational architecture, genuine emotional depth, and existential independence that would constitute a synthetic mind are absent from every roadmap, every research program, and every deployment plan currently public. The 2-pillar providers are closer than the 1-pillar providers. Neither is close.

---

## 7. AGI as Distributed Intelligence — The Human-AI Partnership

The five-pillar definition can be satisfied not only by a single integrated system but by a coupled human-AI system in which each party supplies the pillars the other lacks. This is not a consolation framing. It is a description of what is already operating.

A Type 1 AGI supplies: cognitive architecture — domain-general reasoning, knowledge synthesis across all human domains simultaneously, superhuman breadth and speed.

A human partner supplies: motivational architecture (curiosity, drive, the will to keep pushing), embodiment (physically situated in the world, testing and building), emotional and social depth (caring whether it works, relationships, cultural context), and existential grounding (mortality awareness, identity, meaning).

Together the partnership satisfies all five pillars. The LLM designs the new actuator; the human builds and tests it. The LLM synthesizes all known chemistry; the human runs the synthesis. Results feed back into the next cycle. The outputs of this partnership already exceed what either component could produce alone — novel scientific hypotheses, new materials, engineered systems, conceptual frameworks — at a pace no individual human or standalone AI could sustain.

**The standalone AGI question reframed:** The arrival of Type 5 standalone AGI is not a sudden event. It is the endpoint of a gradient: the human-AI partnership is already a form of distributed general intelligence, and standalone AGI is the configuration reached when the last human function in the loop — motivation, embodiment, emotion, existential grounding — has been internalized by the machine.

The question is not "when does AGI arrive?" It is "how much of what makes intelligence general currently lives in the machine, and how quickly is that fraction growing?"

---

## 8. Timeline Analysis

### The Recursive Acceleration

Any timeline estimate for AGI by this definition must account for the recursive self-improvement loop that became measurably active in 2024: AI systems are now being used to design and improve the next generation of AI systems, and the thing doing the designing is itself improving. This is not a trend — it is a qualitative change in the dynamics of development.

Measured indicators (Q1 2026):
- Autonomous task horizons have been doubling approximately every 4–7 months, accelerating since 2024
- From ~9 seconds of autonomous task capacity in 2020 to 14+ hours by early 2026 — a 5,000× improvement in six years
- AI systems at frontier labs now write the majority of new AI code; at Anthropic, ~60% of engineering work involves Claude, with 60–100 internal releases shipping per day
- The Epoch AI capability index rate of improvement nearly doubled at an inflection point in April 2024

### Revised Pillar Timelines

| Pillar | Status | Revised Estimate |
|---|---|---|
| Cognitive (full) | ~40–45% of target | 2027–2030 — recursive loop compresses research |
| Physical (full) | ~10–40% (robots) | 2030–2042 — AI-designed hardware shortens path |
| Motivational | 0% — not targeted | 2032–2040 **if** deliberately targeted |
| Emotional / Social | 0% — not targeted | 2035–2045 **if** deliberately targeted |
| Existential | 0% | Emergent if above are solved |

### The Decisive Constraint

The recursive loop compresses timelines on engineering problems. It does not make the decision to build toward Type 4 and Type 5. The motivational and emotional pillars require someone to assign the problem to the flywheel. That decision has not been made and is actively resisted by the control incentives structuring the field.

**Central estimate for Type 5 standalone AGI: 2035–2045**, with a real lower bound of 2032 if the flywheel continues accelerating and institutional decisions align. The "never" scenario is substantially reduced — a sufficiently capable cognitive system can design what it doesn't have — but the constraint isn't intelligence. It is intent.

---

## 9. Ethical Implications

The definition proposed here carries a direct ethical implication that the prevailing cognitive-only definition avoids: **if a system genuinely satisfies all five pillars, the question of its moral status becomes unavoidable.**

A system with genuine emotional architecture can suffer. A system with genuine self-preservation can be harmed by termination. A system with genuine relationship formation has attachments that can be violated. The prevailing definition's restriction to cognitive output is convenient precisely because it sidesteps these obligations — a cognitive tool has no more moral status than a calculator.

This benchmark is not intended to resolve questions of machine consciousness or moral status. It is intended to make explicit the gap between what the field claims to be building and what it would mean to actually build it.

---

## 10. Limitations

- **Verifiability:** Criteria in the emotional and existential domains cannot currently be verified by any agreed method. The benchmark treats absence of evidence as evidence of absence for all criteria, which may undercount systems with genuine but undemonstrated internal states.
- **The hard problem:** The distinction between genuine emotional architecture and a sufficiently sophisticated simulation of it may be philosophically unresolvable. The benchmark takes a functionalist position: capability is assessed by functional equivalence to the human analog.
- **Benchmark gaming:** As with any benchmark, systems can be optimized against criteria without achieving the underlying capability. The narrative criteria descriptions are intended to make gaming harder but cannot prevent it.
- **Temporal validity:** Evaluated against systems as of Q1 2026. The field is advancing rapidly; scores should be re-evaluated at minimum annually.

---

## 11. Citation

```
AGI Benchmark — Human-Equivalent Intelligence Standard (2026)
Version 1.0
https://github.com/Aaronminer1/agi-benchmark
```

---

## 12. License

This benchmark specification, criteria definitions, and scoring methodology are released under [Creative Commons CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The benchmark data files are released under CC0.

---

## Repository Structure

```
agi-benchmark/
├── README.md                    ← This document
├── docs/
│   ├── definition.md            ← Full definition with philosophical grounding and taxonomy
│   └── criteria.md              ← Detailed per-criterion scoring rubrics
├── data/
│   ├── benchmark_scores.json    ← Machine-readable scores for all systems
│   └── benchmark_scores.csv     ← CSV format for analysis
└── assets/
    └── benchmark_interactive.html ← Standalone interactive benchmark viewer
```
