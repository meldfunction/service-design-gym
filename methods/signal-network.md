# Signal Network Design
## Distributed Sensing — Building the Nervous System

---

### Nature Analog
The nervous system of an octopus is radically distributed — two-thirds of its neurons live in its arms, not its brain. Each arm can act semi-autonomously, sensing and responding to the local environment without waiting for central processing. Yet the system remains coherent: signals integrate, patterns emerge, and the octopus acts as a unified organism. No central command could respond fast enough to what each arm encounters.

> *"Intelligence does not require centralisation. It requires connection."*

---

### Biological Principle
**Distributed nervous systems.** Many organisms process signals at the edge — near the sensory surface, not in a central headquarters. This enables fast local response while preserving system-level coherence. Signal Network Design asks: where are the signals in your service, who is sensing them, where do they flow, and what responds?

---

### What It Is
Signal Network Design is the practice of deliberately designing the feedback and sensing infrastructure of a service — the mechanisms by which the system knows what is happening and responds to it.

Most service failures are information failures: the signal existed but wasn't captured, or was captured but didn't flow to the right actor, or flowed but triggered no response. Signal Network Design maps and strengthens the sensing architecture.

**Legacy term:** Feedback Loop Design, Metrics Architecture, Voice of Customer Programme

---

### When to Use
- **Go-to-Field phase** — to design the sensing infrastructure before deployment
- **Service Operations phase** — to audit whether existing signals are being heard
- **Adapt phase** — to understand why learning isn't happening
- Whenever a service has recurring problems that no one caught early enough

---

### Biomimetic Method

**The Five Signal Questions**

1. **What signals exist?** What is the service environment producing that could tell you what is happening?
   - User behaviour signals (drop-off, frequency, duration)
   - Emotional signals (complaints, praise, silence)
   - Operational signals (failure rates, resolution time, escalation frequency)
   - Staff signals (workarounds, burnout indicators, informal feedback)
   - External signals (policy changes, competitor moves, cultural shifts)

2. **Who is sensing them?** Is there a human or system whose job it is to receive this signal?

3. **Where do they flow?** Once sensed, where does the signal go? Does it reach someone with the authority to act?

4. **What responds?** What changes when the signal arrives? If nothing changes, the signal is noise.

5. **What is the latency?** How long between signal and response? Some systems need immediate response (safety); others need time to accumulate (culture).

**Signal Mapping Exercise**

Draw a signal network map:
- Nodes: the sensing points (user, frontline staff, system log, survey, etc.)
- Edges: the flow of signals between nodes
- Colour code: 🟢 signal is flowing and being acted on / 🟡 signal exists but may not be reaching decision-makers / 🔴 signal exists but is not being captured

**Strengthening Weak Links**
For each 🔴 or 🟡 signal:
- What is the minimum change needed to capture this signal reliably?
- Who should receive it?
- What is the minimum viable response protocol?

---

### Outputs
- A signal network map: sensing points, flow paths, response actors
- A signal strength audit: what is heard vs. what is lost
- A latency analysis: where response is too slow relative to signal urgency
- A minimum viable monitoring plan for go-live

---

### Facilitation Notes
- Frontline staff are the most sensitive sensors — and often the most ignored. Start with them.
- "We get lots of feedback" often means "we receive signals but don't act on them." Distinguish receiving from responding.
- Design the response protocol before you design the signal capture — otherwise you create data without action

---

### Time
**Signal mapping:** 2 hours  
**Strength audit:** 1 hour  
**Response protocol design:** 1 hour per critical signal

---

### Connected Stages
→ **Go-to-Field** (primary — deployment sensing infrastructure)  
→ **Service Operations** (primary — ongoing signal health)  
→ **Adapt** (secondary — signal network is the input to the adapt cycle)
