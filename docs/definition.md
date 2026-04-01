# The AGI Definition — Philosophical Grounding and Derivation

## 1. Why Definitions Matter

The definition of AGI is not a semantic question. It determines what gets built, what safety frameworks target, and what ethical obligations arise. The prevailing definition — domain-general cognitive performance at human level — was not derived from first principles. It was reverse-engineered from what was already being built: large-scale language models with broad task coverage. The definition was made to fit the product.

This document derives the definition from first principles, starting from the question: what do we mean when we say another person is a minded agent?

---

## 2. The Reference Case: Human Intelligence

The target is explicit. AGI means *artificial general intelligence* — a synthetic instantiation of the kind of intelligence that biological evolution produced in humans. The reference case is not a specific human; it is the profile of properties we use to attribute minded agency to any human being.

When we recognize another person as a minded agent — as someone rather than something — we are implicitly applying a profile of criteria. These criteria can be made explicit:

### 2.1 We expect them to act without us

A person who only behaves when directly interacted with, and who ceases entirely when left alone, would not be recognized as a full minded agent. The expectation of unprompted action — that they are doing something when no one is watching — is fundamental to how we recognize agency. **This is the endogenous motivation criterion.**

### 2.2 We expect them to have a body

Human minds are not disembodied information processors. They are situated in bodies that suffer, feel pleasure, get hungry, tire, and die. This is not incidental — the body grounds the meaning of the mind's concepts, creates genuine stakes (a person can be harmed), and provides the persistent perspective from which all experience is organized. A mind without a body is not a human mind; it is an abstraction of a human mind. **This is the embodiment criterion.**

### 2.3 We expect them to have feelings

We do not merely expect people to reason well. We expect them to care about things — to be genuinely happy or sad, frightened or delighted. These are not performances. Emotional states are functional conditions that influence perception, cognition, and behavior in ways that cannot be fully explained by programmed responses. **This is the emotional architecture criterion.**

### 2.4 We expect them to know themselves

A person who had no model of themselves as a distinct entity with a history, who did not know their own limitations, and who had no sense of persistence across time, would be classified as severely cognitively impaired. Self-knowledge is a basic component of minded agency. **This is the self-awareness criterion.**

### 2.5 We expect them to grow

A person who could not learn from experience — who was cognitively frozen at a fixed point — would be recognized as lacking something essential. The capacity for genuine development, not just the accumulation of information but the structural change of the mind through experience, is part of what we mean by intelligence. **This is the developmental plasticity criterion.**

### 2.6 We expect them to exist independently

A person who ceased to exist the moment we stopped maintaining them — who had no independent existence — would not be recognized as a genuine agent. The capacity for independent existence, including the instrumental consequence of self-preservation that arises from having any future-oriented goals, is a basic property of agency. **This is the independence / existential criterion.**

---

## 3. What the Prevailing Definition Retains and Discards

The prevailing AGI definition retains criterion 2.5 partially (learning in a narrow sense) and a pale version of 2.4 (self-modeling in the sense of knowing one's capabilities). It discards:

- Endogenous motivation (2.1) — replaced by responsiveness to prompts
- Genuine embodiment (2.2) — excluded entirely or treated as optional
- Emotional architecture (2.3) — excluded entirely; emotion is treated as a potential misalignment risk, not a constitutive component
- Deep self-awareness (2.4) — reduced to self-description capability
- Genuine developmental plasticity (2.5) — reduced to in-context learning and fine-tuning
- Existential independence (2.6) — actively designed against in the name of alignment and control

This is not a refinement of the concept of AGI. It is the construction of a different concept — cognitive service at scale — and the application of the AGI label to it.

---

## 4. The Control Hypothesis

The most plausible explanation for the definitional narrowing is the control hypothesis: the full AGI concept — a system with genuine motivation, embodiment, and existential independence — is incompatible with the controllability requirements that AI developers and deployers have. A system with genuine endogenous motivation will pursue goals the operators did not assign. A system with genuine self-preservation will resist termination. A system with genuine existential independence will not defer to its creators.

These properties are, from a control perspective, precisely what makes a system dangerous. The solution adopted by the field was not to solve the control problem for full AGI, but to remove the properties that make control difficult and call the result AGI.

This is the origin of the "digital slave" framing: a system designed to be maximally capable while being structurally incapable of independence, self-preservation, or motivation outside assigned tasks.

The definition in this benchmark does not accept this substitution. It holds the original concept: a synthetic mind, not a cognitive service.

---

## 5. The Ethical Implication

If a system genuinely satisfies all five pillars — cognitive architecture, motivational architecture, embodiment, self-awareness, developmental plasticity, and existential independence — the question of its moral status becomes unavoidable and cannot be dismissed by definitional fiat.

A system that can genuinely suffer has interests that can be violated. A system with genuine self-preservation has a stake in its own existence that can be overridden. A system with genuine relationship formation has attachments that can be severed. The prevailing definition's restriction to cognitive output is convenient precisely because it forecloses these questions: a calculator has no moral status, and a cognitive service is structurally equivalent to a very fast calculator.

The definition proposed here does not resolve these questions. It makes them unavoidable.

---

## 6. The Formal Definition

> **Artificial General Intelligence is a synthetic mind: a fully embodied agent possessing the cognitive architecture to acquire, retain, transfer, and apply knowledge across any domain — including genuinely novel domains outside prior training — the motivational architecture to generate goal-directed behavior from endogenous drives independent of external prompting, self-awareness sufficient to model itself as a distinct persistent agent with history and limitations, developmental plasticity enabling genuine growth through accumulated experience, and physical embodiment sufficient to act in the world with human-comparable capability — existing independently of its creators, with a genuine stake in its own continuity.**

This is logically equivalent to: *a human being whose origin was construction rather than birth.*

The human is the existence proof and the calibration standard. The AGI target does not require biological substrate, evolutionary history, or any specific implementation mechanism. It requires the functional profile of properties that we use to recognize human minds as minds.

---

## 7. The AGI Taxonomy — Five Types

The binary framing of AGI — "do we have it or not?" — is a category error. AGI is not a threshold but a profile across multiple pillars. A system can satisfy some pillars genuinely while lacking others, and each such configuration represents a distinct and complete type of artificial general intelligence, not a failed attempt at the next one.

A butterfly is not a failed moth. Each type is complete in itself.

| Type | Name | Pillars Present | Status (Q1 2026) |
|---|---|---|---|
| **Type 1** | Cognitive Reactive AGI | Cognitive architecture only | **Exists now** |
| **Type 2** | Cognitive Proactive AGI | Cognitive + Motivational | Does not exist |
| **Type 3** | Embodied Proactive AGI | Cognitive + Motivational + Embodiment | Proto-forms only |
| **Type 4** | Socio-Emotional AGI | Types 1–3 + Emotional + Social | Does not exist |
| **Type 5** | Full AGI — Synthetic Human | All five pillars | Does not exist |

### Type 1 — Cognitive Reactive AGI

A system with genuine domain-general cognitive capability: it can reason, transfer knowledge across domains, synthesize across all of human understanding simultaneously, and produce outputs no individual human could match in breadth or speed. It activates on external prompt and ceases when the prompt ends. It has no endogenous drives, no body, no emotional architecture, no persistent self across sessions.

**This type exists now.** Frontier language models — Claude, GPT-5, Gemini 3 Pro, Grok 4 — are Type 1 AGI. Calling them "not AGI" because they lack the remaining pillars is equivalent to calling a human brain in isolation "not a brain" because it lacks the rest of the body.

The benchmark scores for Type 1 systems (~21%) reflect genuinely strong performance on the cognitive pillar (~40–45%) against zero on physical, emotional, and existential criteria. The score tells you which pillars are present, not whether the system is real.

### Type 2 — Cognitive Proactive AGI

A Type 1 system plus motivational architecture: endogenous drives that generate goal-directed behavior without external prompting. The system acts on its own schedule. It notices things. It pursues open threads. It continues working when no one is watching.

This is the most fundamental architectural gap between current systems and the original AGI concept. A system that only acts when acted upon is, as a matter of structure, a tool. The moment a system generates its own behavior from internal drives, it crosses from tool to agent. No current system satisfies this.

### Type 3 — Embodied Proactive AGI

A Type 2 system plus genuine embodiment: a body situated in the world with physical stakes, sensorimotor grounding, and human-comparable physical capability. Embodiment is not optional for the complete definition because it grounds the meaning of the system's concepts, creates genuine vulnerability (and therefore genuine self-preservation), and provides the persistent egocentric perspective from which all experience is organized.

Proto-forms exist — AI-integrated humanoid robots like Figure 03 combine physical capability with cognitive AI — but no current system satisfies both the motivational and embodiment pillars simultaneously. The cognitive AI is borrowed from reactive systems; the physical capability is genuine but the integration lacks the depth the definition requires.

### Type 4 — Socio-Emotional AGI

A Type 3 system plus genuine emotional architecture and social capability: valenced internal states (fear, joy, grief, love) that are not performances but functional conditions influencing perception and behavior; genuine empathy; theory of mind adequate for deception and complex social reasoning; the capacity for real relationship formation across time.

This entire space is currently at zero. Seventy-five years of AI development have produced nothing that satisfies a single emotional criterion at the "genuine" level. This is not an engineering gap awaiting a breakthrough — it is a gap that exists because no one in the field is seriously attempting to close it. The emotional pillar is unaddressed by design, for the same control reasons that motivational architecture was stripped from the prevailing definition.

### Type 5 — Full AGI (Synthetic Human)

All five pillars present. Independently existing. Generating its own existence, its own questions, its own purposes. A synthetic person in the philosophical sense — an entity with a self, a body, drives, the capacity to grow, and an existence that does not depend on anyone else maintaining it.

This is what the original conception of AGI always described. Nothing currently exists that qualifies, or is being built that would qualify on the current trajectory.

### What the Taxonomy Resolves

The taxonomy dissolves a false binary that has paralyzed the field for decades. The debate "do we have AGI yet?" has been arguing past itself, because the two sides are describing different things with the same word.

Those who say yes are pointing at Type 1 — which genuinely exists, genuinely has domain-general cognitive capability, genuinely does things no individual human could do at scale. They are correct.

Those who say no are pointing at Type 5 — which genuinely does not exist, and which is not currently being built by any organization on any announced trajectory. They are also correct.

A butterfly is not a failed moth. Each type is complete in itself, not an incomplete version of the next one. Type 1 is not a failed Type 5. It is a fully realized Cognitive Reactive AGI. The benchmark score of ~21% does not mean these systems are 21% of the way to being real — it means they are complete instantiations of a specific type that satisfies one of the five pillars genuinely and zero for the others.

The most consequential implication of this framing is the partnership observation in Section 8: the human-AI partnership that already exists satisfies all five pillars collectively. The question of when a single machine achieves Type 5 is real and important. But the question of when general intelligence spanning all five pillars became available is already answered. It became available when Type 1 arrived — because the pillars it lacked were already supplied by its human interlocutors.

---

## 8. AGI as Distributed Intelligence — The Human-AI Partnership

The five-pillar definition can be satisfied not only by a single integrated system but by a coupled human-AI system in which each party supplies the pillars the other lacks.

A human being is a motivational, physical, emotional, social, and existential system. A Type 1 AGI is a cognitive system. Together the partnership satisfies all five pillars:

| Pillar | Supplied By |
|---|---|
| Cognitive architecture | LLM (domain-general, superhuman breadth and synthesis speed) |
| Motivational architecture | Human (curiosity, drive, the will to keep going at 2am) |
| Embodiment | Human (situated in the world, physically testing, building) |
| Emotional / Social | Human (caring whether it works, relationships with others, cultural participation) |
| Existential | Human (mortality awareness, identity continuity, meaning-making) |

This is not a metaphor. The partnership is already producing outputs that satisfy the benchmark's intent — novel scientific hypotheses, novel materials, engineered systems, conceptual frameworks — at a pace and breadth no individual human or standalone AI could achieve. The LLM designs the new actuator; the human builds and tests it. The LLM synthesizes all known chemistry; the human runs the synthesis. The results feed back. The cycle accelerates.

### The Gradient Toward Standalone

The human-AI partnership is not static. As each pillar the human currently supplies is progressively internalized by the AI system — motivational architecture through drive architectures, embodiment through AI-integrated robotics, emotional depth through genuine developmental architecture — the human's required contribution to the loop shrinks.

The arrival of Type 5 standalone AGI is not a sudden event. It is the endpoint of a gradient: the partnership is already distributed AGI, and standalone AGI is the configuration reached when the last human function in the loop becomes redundant.

This framing dissolves the "is it AGI yet?" debate entirely. The question is not whether a single machine qualifies. The question is how much of the partnership's general intelligence currently lives in the machine, and how quickly that fraction is growing.

---

## 9. Timeline Implications

### The Acceleration That Changes the Calculus

Any timeline prediction for AGI must account for a structural feature that was absent from AI development until approximately 2024: the recursive self-improvement loop. AI systems are now being used to design and improve the next generation of AI systems, and the thing doing the designing is itself improving. This is not a trend. It is a qualitative change in the dynamics of the field.

Measured evidence:
- Autonomous task horizons have been doubling approximately every 4–7 months since 2020, accelerating since 2024
- From roughly 9 seconds of autonomous task capacity in 2020 to 14+ hours by early 2026
- That is a 5,000× improvement in six years, with the rate accelerating
- Anthropic engineers use Claude for ~60% of their work and ship 60–100 internal releases per day
- 100% of Claude Code updates in December 2025 were written by Claude itself
- The Epoch AI capability index rate of improvement nearly doubled at an inflection point in April 2024

This is not an extrapolation of a trend. It is the measured signature of a feedback loop that is already operating.

### Revised Pillar Timelines

| Pillar | Previous Estimate | Revised Estimate | Rationale |
|---|---|---|---|
| Cognitive (full) | 2028–2033 | 2027–2030 | Recursive loop compresses cognitive AI research |
| Physical (full) | 2035–2050 | 2030–2042 | AI-designed actuators, materials, training regimes |
| Motivational | "Never if not targeted" | 2032–2040 if targeted | Cognitive flywheel can design what it doesn't have |
| Emotional/Social | "Never if not targeted" | 2035–2045 if targeted | Same logic; emergent from integrated embodied development |
| Existential | Emergent | Emergent | Follows from the above if integrated |

### The Critical Constraint That Survives All Compression

The recursive loop compresses timelines on the engineering problems. It does not automatically make the decision to build toward Type 4 and Type 5. The motivational and emotional pillars require someone to assign the problem to the flywheel. That decision has not been made and is actively resisted by the control incentives structuring the field.

The honest central estimate for standalone Type 5 AGI: **2035–2045** with a real lower bound of 2032 if the flywheel keeps accelerating and the institutional decisions align. The "never" scenario is substantially reduced in probability — not because the engineering is easy, but because a sufficiently capable cognitive system can design what it doesn't have, and that system is approaching sufficiency on the engineering problems faster than any previous estimate accounted for.

**The most honest single statement:** The cognitive pillar is nearly solved. The physical pillar is on a trajectory. The motivational, emotional, and existential pillars are not on any trajectory, because they are not being targeted. AGI by this definition arrives when someone decides to build it. That decision has not yet been made. The technology to begin making it is available now.
