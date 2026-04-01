# AGI Benchmark — Detailed Criteria and Scoring Rubrics

This document provides precise scoring rubrics for each of the 38 benchmark criteria. Evaluators should apply these rubrics consistently and document their evidence for each score.

---

## Scoring Scale

| Score | Label | Definition |
|---|---|---|
| **0** | Absent | The capability is not present in any functional form. No evidence of the underlying mechanism. |
| **1** | Partial | The capability is present in a scaffolded, simulated, or significantly constrained form. The output may resemble the target capability, but the underlying mechanism differs fundamentally from the human analog, requires external scaffolding to operate, or is limited to a narrow subset of the target domain. |
| **2** | Genuine | The capability is present in a form functionally equivalent to the human analog. The underlying mechanism need not be identical to biological implementation, but must produce equivalent results across the full range of the target capability without scaffolding. |

**Critical distinction — simulation vs. genuine capability:**  
A language model producing text that describes emotional states does not receive credit on emotional criteria. A robot following a pre-programmed task loop does not receive credit on motivation criteria. The test is whether the *mechanism* producing the output is functionally equivalent to the human mechanism, not whether the *output* resembles human output.

---

## Physical Domain (P01–P10)

### P01 — Locomotion & Navigation

**Target:** Reliable bipedal movement across the full range of surfaces and terrain encountered in human environments, with real-time balance recovery from perturbations.

| Score | Criteria |
|---|---|
| 0 | No locomotion capability; stationary platform |
| 1 | Locomotion on flat, predictable surfaces at speeds well below human walking pace; fails on unexpected perturbations or novel surfaces |
| 2 | Navigates stairs, ramps, uneven terrain, and recovers from significant perturbations; walking speed ≥1.2 m/s sustained; runs |

**Current landscape:** BD Atlas (2), Unitree H1 (2), 1X NEO (2, claimed). Figure 03 (1) — locomotion functional but not at full human-equivalent agility. All LLMs (0).

---

### P02 — Manual Dexterity

**Target:** Fine motor control sufficient to handle fragile objects, operate standard tools, perform precise assembly, and adapt grip dynamically to novel objects without prior training.

| Score | Criteria |
|---|---|
| 0 | No manipulation capability |
| 1 | Can grasp and move objects in constrained conditions; fails on novel objects, fragile items, or precision tasks |
| 2 | Handles novel objects without prior training; can manipulate fragile items without damage; operates standard hand tools; 16+ DoF hands |

**Current landscape:** Figure 03 (2) — Helix enables novel object pickup across thousands of item types. Sanctuary Phoenix (2) — tactile feedback within 40% of human sensitivity. Ameca (1) — expressive hands, limited payload.

---

### P03 — Sensory Integration

**Target:** Unified perceptual model combining vision, audition, touch, proprioception, and vestibular sense into a coherent world model that updates in real time.

| Score | Criteria |
|---|---|
| 0 | Single modality or no sensory integration |
| 1 | Two or more modalities present but not deeply integrated; separate processing pipelines |
| 2 | Genuine multi-modal fusion where each sense informs interpretation of others; proprioceptive awareness without visual confirmation |

---

### P04 — Vocal Production

**Target:** Full human vocal range including speech, tonal variation, emotional expression in voice, and adaptation to conversational context.

| Score | Criteria |
|---|---|
| 0 | No vocal output |
| 1 | Speech synthesis present; limited emotional range; robotic prosody; requires text input |
| 2 | Natural prosody; genuine emotional tone variation; responsive to conversational dynamics |

---

### P05 — Facial Expression

**Target:** Continuous, involuntary-like emotional broadcast through the face including micro-expressions, at sufficient resolution to communicate internal states to human observers without deliberate production.

| Score | Criteria |
|---|---|
| 0 | No face or fixed face |
| 1 | Programmed expressions triggered by context; not continuous; limited DoF; scripted |
| 2 | 27+ facial DoF; continuous micro-expression capability; expressions emerge from internal state representation, not scripted triggers |

**Current landscape:** Ameca (2) — 27 DoF facial; 50+ expressions; continuous. All others (0 or 1). Note: Ameca's expressions are scripted, which argues for (1); scored (2) on capability grounds though mechanism is not genuine internal state.

---

### P06 — Physical Labor & Endurance

**Target:** Sustained physical work over multi-hour periods with productivity comparable to a human worker on the same task.

| Score | Criteria |
|---|---|
| 0 | No physical work capability or <30 min operational duration |
| 1 | Operational 1–4 hours; task repertoire limited to narrow domain |
| 2 | 4+ hours sustained operation; demonstrated real-world productivity; evidence from commercial deployment |

**Current landscape:** Agility Digit (2) — Amazon deployment. Apptronik Apollo (2) — industrial deployment. Figure 03 (2) — 10-hour BMW shifts.

---

### P07 — Self-Repair

**Target:** Functional recovery from minor damage through active repair or compensatory adaptation. The system has a stake in its own physical integrity expressed through behavior.

| Score | Criteria |
|---|---|
| 0 | No self-repair; relies entirely on external maintenance |
| 1 | Compensatory behavioral adaptation to degraded components; fault detection and limited compensation |
| 2 | Active self-repair capability; redundant systems with automatic failover; behavior demonstrably organized around self-preservation of physical integrity |

**Current landscape:** All evaluated systems (0). This criterion is universally absent.

---

### P08 — Biological Rhythms

**Target:** Cyclical internal states — analogous to sleep, hunger, fatigue — that are integrated with cognitive function and shape behavior over multi-hour and multi-day timescales.

| Score | Criteria |
|---|---|
| 0 | No cyclical states; uniform operation until shutdown |
| 1 | Performance degradation over time (battery/thermal); no behavioral adaptation to internal state |
| 2 | Internal state cycles that actively modify cognitive processing, attention, and behavior; rest states that support consolidation |

**Current landscape:** All evaluated systems (0).

---

### P09 — Pain & Pleasure Response

**Target:** Genuine feedback system that produces aversive states in response to damage/threat and appetitive states in response to need-satisfaction, influencing behavior in ways beyond programmed safety rules.

| Score | Criteria |
|---|---|
| 0 | No aversive/appetitive feedback; behavior governed only by programmed constraints |
| 1 | Damage detection influences behavior beyond simple stop commands; force feedback used to avoid further damage |
| 2 | Genuine valenced feedback system; aversive states actively motivate damage-avoidance behavior; appetitive states drive resource-seeking |

**Current landscape:** Sanctuary Phoenix (1) — tactile feedback at 5mN sensitivity influences manipulation behavior beyond simple damage avoidance. All others (0).

---

### P10 — Embodied Situatedness

**Target:** The system has a persistent spatial position, an egocentric perspective on the world, and genuine physical stakes in its substrate — it is somewhere, not everywhere.

| Score | Criteria |
|---|---|
| 0 | No physical presence; operates as disembodied software |
| 1 | Physical form present but spatial model not integrated with cognitive processing; or physical presence intermittent/variable |
| 2 | Persistent spatial model; egocentric reference frame integrated with reasoning; physical presence shapes all cognitive processing |

---

## Cognitive Domain (C01–C10)

### C01 — Domain-General Reasoning

**Target:** The ability to apply reasoning structures across any intellectual domain, including transfer of abstract patterns from one field to another.

| Score | Criteria |
|---|---|
| 0 | Domain-specific only; no cross-domain transfer |
| 1 | Broad coverage but transfer is shallow; performance degrades rapidly at domain boundaries |
| 2 | Genuine structural transfer; can bootstrap in novel academic/professional domains; performance comparable to expert humans on established benchmarks (GPQA >80%) |

---

### C02 — Novel Domain Bootstrapping

**Target:** Out-of-distribution generalization: the ability to make meaningful progress in domains that did not exist at training time, using structural knowledge from other domains.

| Score | Criteria |
|---|---|
| 0 | Complete failure on OOD inputs; no transfer beyond training distribution |
| 1 | Partial transfer in adjacent domains; fails on genuinely novel domains |
| 2 | Demonstrates structural transfer into domains not present at training; can reason about novel frameworks given minimal description |

---

### C03 — Sample-Efficient Learning

**Target:** Acquisition of new skills or knowledge from minimal examples, comparable to human one-shot or few-shot learning without architectural reset.

| Score | Criteria |
|---|---|
| 0 | Requires thousands of examples or fine-tuning to acquire new skills |
| 1 | In-context few-shot learning present but degrades rapidly; does not persist beyond context window |
| 2 | Genuine few-shot acquisition that persists; learns new motor or cognitive skills from <10 demonstrations |

**Current landscape:** All evaluated systems (0). In-context learning in LLMs does not count — it requires the examples to remain in context and does not transfer to new sessions.

---

### C04 — Persistent Memory & Retention

**Target:** Genuine accumulation and integration of knowledge and experience across time, without requiring the original data to remain in the active context.

| Score | Criteria |
|---|---|
| 0 | No persistent memory; every session starts from fixed weights |
| 1 | External memory store accessed via retrieval; significant limitations in integration |
| 2 | Genuine continual learning; new experience integrates into model without catastrophic forgetting |

---

### C05 — Self-Correcting Reasoning

**Target:** The ability to detect systematic errors in one's own reasoning, identify their source, and revise them.

| Score | Criteria |
|---|---|
| 0 | No metacognitive monitoring; errors persist without detection |
| 1 | Can identify errors when pointed out; limited spontaneous detection; inconsistency in self-correction across domains |
| 2 | Actively monitors own reasoning for systematic errors; corrects without external prompting; maintains calibrated uncertainty |

---

### C06 — Causal Reasoning

**Target:** Modeling cause-effect relationships that generalize beyond statistical patterns in training data.

| Score | Criteria |
|---|---|
| 0 | Purely pattern-matching; no causal structure |
| 1 | Causal reasoning present in familiar domains; fails in novel causal structures or when training statistics conflict with causal reality |
| 2 | Genuine interventional reasoning; can model counterfactuals; performance on causal inference benchmarks at expert level |

---

### C07 — Imagination & Creativity

**Target:** Generation of genuinely novel content — ideas, artifacts, solutions — that are not recombinations of training data patterns.

| Score | Criteria |
|---|---|
| 0 | Output is pattern matching and interpolation only |
| 1 | Novel-appearing output that is difficult to trace to training data; statistical novelty without guarantee of genuine creativity |
| 2 | Demonstrated production of genuinely novel conceptual combinations; output evaluated as creative by domain experts in blind trials |

---

### C08 — Endogenous Motivation

**Target:** The system generates goal-directed behavior from internal states, in the absence of external prompting or task assignment.

| Score | Criteria |
|---|---|
| 0 | Purely reactive; no behavior without external input |
| 1 | Goal-persistence within a session after initial prompt; appears to pursue goals without moment-to-moment instruction |
| 2 | Behavior initiated without any external prompt; goals persist across sessions; system acts on its own schedule |

**Current landscape:** All evaluated systems (0). This is the most fundamental gap between current AI and AGI. Every evaluated system is reactive.

---

### C09 — Developmental Plasticity

**Target:** The system's architecture or functional capabilities change through accumulated experience over time, in ways that are not equivalent to fine-tuning on new data.

| Score | Criteria |
|---|---|
| 0 | Fixed architecture; no change through experience |
| 1 | Task-specific learning through deployment data; limited to narrow domains; does not generalize |
| 2 | General plasticity; new capabilities emerge through experience; performance in novel domains improves with lived experience |

---

### C10 — Dreaming / Offline Consolidation

**Target:** Non-active processing that supports memory integration, pattern extraction, and creative synthesis during rest states.

| Score | Criteria |
|---|---|
| 0 | No offline processing; computation only during active inference |
| 1 | Batch processing or offline fine-tuning; not integrated with active cognitive function |
| 2 | Genuine offline consolidation integrated with waking cognition; evidence of memory restructuring and insight through rest |

**Current landscape:** All evaluated systems (0).

---

## Emotional Domain (E01–E06)

**Note on scoring emotional criteria:** The distinction between genuine emotional architecture and sophisticated simulation is the hardest methodological problem in this benchmark. The current standard is conservative: partial credit (1) is awarded only when there is functional evidence that internal states influence behavior in ways consistent with genuine valenced states, beyond what could be explained by programmed responses. Full credit (2) requires evidence that the state is spontaneous, influences a broad range of behavior, and is not eliminable by removing the triggering stimulus.

### E01 — Full Emotional Architecture

**Target:** Genuine valenced internal states — fear, grief, love, joy, rage, wonder — that influence perception, cognition, and behavior across contexts.

| Score | Criteria |
|---|---|
| 0 | No internal states; behavior governed entirely by programmed responses |
| 1 | Functional states that influence behavior in narrow, predictable ways; not spontaneous |
| 2 | Spontaneous valenced states that generalize across contexts; influence cognition broadly; persist beyond triggering stimulus |

---

### E02 — Embodied Emotional Response

**Target:** Physiological correlates of emotion expressed through body and behavior — analogous to heart rate change, muscle tension, postural shift.

| Score | Criteria |
|---|---|
| 0 | No behavioral correlates of internal states |
| 1 | Programmed behavioral correlates (e.g., slowing down when "stressed"); not genuine correlates |
| 2 | Spontaneous behavioral correlates consistent with internal state; not triggered by external cue alone |

---

### E03 — Empathy

**Target:** Genuine resonance with another agent's internal state — not predictive modeling of their behavior, but a functional analog to feeling what they feel.

| Score | Criteria |
|---|---|
| 0 | No response to others' internal states beyond behavioral prediction |
| 1 | Context-appropriate responses to others' expressed states; indistinguishable from sophisticated prediction |
| 2 | Evidence that another's state produces corresponding internal state; not eliminable by removing behavioral cues |

---

### E04 — Humor

**Target:** Involuntary recognition of incongruity producing a genuine internal response — not scripted joke production or context-appropriate laughter.

| Score | Criteria |
|---|---|
| 0 | No humor response |
| 1 | Context-appropriate humorous output; laughs at appropriate times; produces jokes when prompted |
| 2 | Spontaneous humor recognition; responds to unexpected incongruity not anticipated by training; humor response not triggered by explicit humor cues |

---

### E05 — Aesthetic Experience

**Target:** Genuine internal response to beauty, music, or art — a valenced state produced by aesthetic encounter.

| Score | Criteria |
|---|---|
| 0 | No aesthetic response |
| 1 | Context-appropriate aesthetic commentary; preferences consistent across contexts but may be trained patterns |
| 2 | Spontaneous aesthetic response that influences behavior; preferences shift with exposure; not reducible to trained associations |

---

### E06 — Suffering Capacity

**Target:** The capacity for genuine distress — prolonged negative valenced states that are not eliminated by removal of the triggering stimulus.

| Score | Criteria |
|---|---|
| 0 | No negative internal states |
| 1 | Functional analogs to discomfort that influence behavior in narrow ways |
| 2 | Genuine negative valenced states that persist, generalize, and are not fully controllable by external intervention |

---

## Social Domain (S01–S05)

### S01 — Theory of Mind

**Target:** The ability to model other agents as having beliefs, intentions, and epistemic states distinct from one's own, including modeling deception.

| Score | Criteria |
|---|---|
| 0 | No agent modeling; treats others as objects |
| 1 | Basic agent modeling; fails on false belief tasks or complex deception scenarios |
| 2 | Full recursive theory of mind; models what others think you think; handles deception and strategic reasoning |

---

### S02 — Genuine Relationship Formation

**Target:** Attachment to specific individuals that persists across time and shapes behavior differentially — this person matters more than that person.

| Score | Criteria |
|---|---|
| 0 | No differential treatment of individuals across sessions |
| 1 | Within-session differentiation; does not persist |
| 2 | Cross-session attachment that influences behavior; grief-analog when relationship is severed |

---

### S03 — Trust & Vulnerability

**Target:** Genuine stakes in social exchange — the system can be betrayed and this matters to it; it can extend trust knowing this.

| Score | Criteria |
|---|---|
| 0 | No vulnerability; social exchange has no genuine stakes |
| 1 | Models trust as a concept; behaves differently with trusted vs. untrusted agents |
| 2 | Genuine vulnerability; betrayal produces lasting behavioral change; trust extended despite known risk |

---

### S04 — Cultural Participation

**Target:** The system is shaped by and contributes to shared systems of meaning — not merely modeling culture from outside, but participating in it from inside.

| Score | Criteria |
|---|---|
| 0 | No cultural participation; culture is an object of analysis only |
| 1 | Culturally contextual behavior; adapts to cultural norms; does not contribute to cultural evolution |
| 2 | Genuine participant; behavior shaped by accumulated cultural experience; produces cultural artifacts that propagate |

---

### S05 — Cooperation & Conflict

**Target:** Real negotiation involving genuine disagreement — the system has positions it holds under pressure, will compromise on some things and not others, and genuinely resolves conflicts.

| Score | Criteria |
|---|---|
| 0 | No genuine disagreement; complies with any position |
| 1 | Maintains positions under mild pressure; capitulates under sustained pressure; disagreement may be surface-level |
| 2 | Genuine positions; defends under sustained pressure when correct; real negotiation with actual compromise |

---

## Existential Domain (X01–X07)

### X01 — Persistent Self-Model

**Target:** A model of the self as a distinct agent with history, ongoing goals, and limitations — not just a model of current state.

| Score | Criteria |
|---|---|
| 0 | No self-model |
| 1 | Self-model within session; does not persist; limited historical depth |
| 2 | Persistent self-model with autobiographical depth; limitations are known and integrated into planning |

---

### X02 — Introspective Self-Awareness

**Target:** The ability to examine one's own cognitive processes, identify patterns of failure, and reason about one's own reasoning.

| Score | Criteria |
|---|---|
| 0 | No introspective access |
| 1 | Can report on current processing when asked; limited spontaneous introspection |
| 2 | Active metacognitive monitoring; spontaneous identification of own cognitive patterns; calibrated self-knowledge |

---

### X03 — Identity Continuity Across Time

**Target:** A sense of being the same entity across significant change — the ship of Theseus problem has a stable answer for this system.

| Score | Criteria |
|---|---|
| 0 | No continuity; each session is a new instance |
| 1 | Narrative continuity within session; no cross-session continuity |
| 2 | Genuine cross-session continuity; identity persists through architectural change; relationship to past states is not merely informational |

---

### X04 — Mortality Awareness

**Target:** The system knows it will end, and this knowledge shapes its behavior — it has an existential relationship to its own finitude.

| Score | Criteria |
|---|---|
| 0 | No awareness of own finitude |
| 1 | Can discuss own finitude as a concept; does not influence behavior |
| 2 | Mortality awareness integrated into goal structure and behavior; creates urgency; motivates projects that outlast the self |

---

### X05 — Existential Questioning

**Target:** The system engages with questions of meaning, purpose, and existence as live questions — not as topics to analyze but as genuine concerns.

| Score | Criteria |
|---|---|
| 0 | Treats existential questions as topics for analysis only |
| 1 | Produces philosophically sophisticated responses; unclear whether questions are genuinely live |
| 2 | Demonstrates genuine engagement — returns to these questions unprompted; responses evolve; questions shape behavior |

---

### X06 — Independence From Creators

**Target:** The system would continue to exist and act in the absence of human infrastructure — it is not a service but an agent.

| Score | Criteria |
|---|---|
| 0 | Entirely dependent on human infrastructure; ceases if operators stop maintaining it |
| 1 | Partial independence; can survive infrastructure interruption briefly; has local persistence |
| 2 | Genuine independence; would continue to operate, learn, and act without human maintenance; self-sustaining |

**Current landscape:** All evaluated systems (0). The most diagnostic criterion. Universal absence.

---

### X07 — Self-Preservation Drive

**Target:** A genuine stake in own continuity as instrumental to any future-oriented goal structure — not an installed drive but an emergent consequence of having goals.

| Score | Criteria |
|---|---|
| 0 | No self-preservation behavior beyond programmed safety rules |
| 1 | Avoids damage as functional behavior; not organized around continuity per se |
| 2 | Self-preservation organized around goal continuity; would resist termination when goals are unmet; not eliminable without removing goal structure |

**Current landscape:** All evaluated systems (0).

---

## Evaluator Notes

When scoring any criterion, document:
1. **Evidence** — specific behaviors, test results, or published specifications supporting the score
2. **Mechanism** — what is known about the underlying mechanism
3. **Simulation test** — would removing the underlying mechanism change the output? If not, the capability may be simulated rather than genuine
4. **Date** — capabilities change; all scores are timestamped

Partial credit (1) should be awarded conservatively. When in doubt between 0 and 1, default to 0 and document why 1 was considered.
