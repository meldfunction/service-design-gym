# Assumption Testing
## Controlled Experiment — Falsify Before You Scale

---

### Nature Analog
Evolution is the most rigorous assumption-testing process in history. Every organism is a hypothesis. The environment is the test. Those that survive were right about something; those that don't were wrong. Crucially: **nature doesn't invest in scaling an organism before testing it**. The test comes first. Resources are allocated after survival is demonstrated.

> *"It is not the strongest of the species that survives, but the one that is most responsive to change."*
> — (commonly attributed to Darwin, actually Charles Merriam)

---

### Biological Principle
**Experimental evolution.** Scientists studying antibiotic resistance run thousands of microbial generations through controlled conditions, changing one variable at a time, to understand which mutations confer survival. Rigorous assumption testing requires isolating variables — testing one thing at a time, with a clear falsification criterion.

---

### What It Is
Assumption Testing is the practice of **making your beliefs explicit** and designing the smallest possible test to find out if they are true before building on them.

Most service design fails not because the solution was wrong but because the **assumptions underneath it were never tested**. Assumption testing is a pre-mortem for your design.

---

### When to Use
- **Prototype phase** — before investing in any concept, surface and test its core assumptions
- **Adapt phase** — when test results are ambiguous, isolate which assumption is responsible
- Before any decision to scale — scaling amplifies both correct and incorrect assumptions

---

### Biomimetic Method

**Step 1: Surface the Assumptions**
For each concept or HMW, run an Assumption Excavation:

Ask:
1. What must be true about **the user** for this to work?
2. What must be true about **the system** for this to work?
3. What must be true about **the relationship between them**?
4. What must be true about **us as designers** (our ability to execute this)?

Write each assumption as a testable statement: *"We believe that [X] will [Y] because [Z]."*

**Step 2: Rate Each Assumption**
Plot assumptions on a 2×2:
- X axis: **Certainty** (how confident are you it's true?)
- Y axis: **Importance** (how much does the concept depend on it being true?)

Top-right quadrant (uncertain AND important) = test these first.

**Step 3: Design the Smallest Test**
For each critical assumption, design the minimum viable test:

| Assumption Type | Minimum Test |
|-----------------|-------------|
| Desirability (do people want this?) | 5 conversations + a mock landing page |
| Feasibility (can this be built?) | A 1-day technical spike |
| Viability (will the system support it?) | 1 stakeholder conversation with a decision-maker |
| Behaviour change (will people act differently?) | A 2-week field test with 5 participants |

**Step 4: Define Falsification Before You Start**
Before running the test, write down: *"We will know this assumption is FALSE if we observe [X]."*

This is the most important step. Without a falsification criterion, you will unconsciously interpret ambiguous results as confirmation.

**Step 5: Run and Read**
- Run the test with the minimum viable population
- Record what happens, not what you hoped would happen
- Compare results to your falsification criteria
- Act on what you find: pivot, persevere, or kill

---

### Outputs
- A tested assumption map — what you now know vs. what you now know you don't know
- A refined concept that has survived its first round of falsification
- A list of dead assumptions — where you were wrong (this is valuable; document it)
- Clear next tests: what must now be true for the next stage of investment

---

### Facilitation Notes
- The hardest part is writing the falsification criterion — teams resist because it makes failure measurable. Do it anyway.
- Small teams run better assumption tests than large ones — cognitive diversity helps in synthesis, but small groups move faster in testing
- Failed assumptions are not project failures. They are learning. Celebrate them explicitly.

---

### Time
**Assumption surfacing:** 45 min  
**Test design:** 30 min per assumption  
**Running tests:** variable (hours to weeks)  
**Synthesis:** 45 min

---

### Connected Stages
→ **Prototype** (primary — testing before building)  
→ **Adapt** (secondary — refining based on what failed)
