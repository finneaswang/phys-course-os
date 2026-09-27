# PHYS Course OS — Content Review Pack (v0.4, L02 Pre-class)

## Context for the reviewer

This is the pre-class page for **Lecture 2: Thermal Equilibrium (Sept 11)**, built
from `L2-prelecture.pdf` (17 slides). This is the FIRST page built after your
rev.3 verdict that my failure mode is "stepping half a step outside what the
lecture taught." So the primary review question is now:

> **Does anything on this page teach beyond what L2-prelecture.pdf actually contains?**

Secondary targets:

1. Clicker answers: C1 → D (Joule); C2 → B (heat flows until same temperature); C3 → C (both). Correct per the slides?
2. The clicker *feedback texts for wrong options* deliberately contain small
   beyond-lecture asides (Einstein's E=mc², Noether's symmetries, "where exactly
   the blocks meet depends on sizes"). Acceptable as ungraded feedback, or should
   they be trimmed to strictly-L02 content?
3. The L01→L02 bridging claim: "L01 said temperature ↔ average kinetic energy;
   L02 widens the ledger to kinetic AND potential energy." Fair to the slides
   (slide 7: hot brick = "more kinetic & potential energy")?
4. The IR-demo prediction section (a/b/c) — is it framed as prediction, or does
   it assert results the demo hasn't shown yet?
5. The 60-second review — anything missing or overreaching?

---

# STEP 1 — The law under the demo

Lecture 2 (September 11) starts where L01 stopped: you said "heat is flowing into
the brick" — and the professor immediately names the law standing behind that
sentence: **Conservation of Energy**. This pre-class covers four things:

**By the end you can:**
- state what Conservation of Energy claims — and what "isolated system" means;
- say what heating/cooling does **microscopically** (kinetic **and** potential
  energy) and which **macroscopic** properties it changes;
- list the **three things** that can happen when two objects touch — and connect
  each to temperature;
- state the **Zeroth Law** and explain why thermometers are allowed to work.

Three clicker questions from the slides are embedded below — ungraded feedback in
lecture, but exactly the style ORCA will ask. New concept pages: Conservation of
Energy and Zeroth Law — the graph has grown to 14 nodes.

---

# STEP 2 — Conservation of Energy

The law, as the slides state it:

- Each part of a physical system has a certain amount of energy.
- The total energy of an **isolated** system doesn't change with time.
- BUT energy can be **transferred between different parts** and take **different forms**.
- In thermodynamics, the energy we care about is the **microscopic kinetic and
  potential energy of atoms and molecules**.

Two words to keep precise: **isolated** (nothing enters or leaves — that's when
the total is locked) and **transfer** (energy moves between parts and changes
form — that's what heat is).

**Clicker Question 1** — *Conservation of energy was first fully understood by…*

- A · Isaac Newton → ✗ "Newton gave us mechanics — F = ma — but the connection
  between mechanical work and heat wasn't his."
- B · Albert Einstein → ✗ "Einstein came much later (E = mc² is a different
  statement about mass and energy)."
- C · Emmy Noether → ✗ "Noether proved WHY conservation laws exist (they come
  from symmetries) — beautiful, but that's not what L02 is asking."
- D · James Joule → ✓ "Right — James Joule. His experiments showed mechanical
  work and heat are the same currency: energy, interconvertible. That's why the
  unit of energy is named after him."

Connect it back to the brick: L01's "heat flows until equilibrium" **silently
used this law** — the energy that leaves the air is exactly the energy the brick
gains. Nothing vanishes, nothing appears.

---

# STEP 3 — What heating does at the molecular level

The slides' picture: two identical bricks, one cold, one hot. Same atoms, same
bonds — different energy.

- **Heating an object = adding energy at the molecular level.** Cooling = removing it.
- The hot brick's atoms carry **more kinetic AND more potential energy** than the
  cold brick's.

⚠️ New wrinkle vs L01: there we said "temperature ↔ average *kinetic* energy."
L02 widens the ledger: the microscopic energy bookkeeping counts kinetic **and
potential** energy — a vibrating atom pushes against its neighbours, and that
stored push is potential energy. Both grow when you heat.

(SOLID lattice animation reused from L01, captioned: "Each vibrating atom swings
between kinetic energy (moving) and potential energy (compressed against its
neighbours) — L02's point is that heating fills BOTH accounts.")

---

# STEP 4 — What heating does to macroscopic properties

Slides' question: *which macroscopic properties change when an object is heated
or cooled?*

- **Most of them!** — but often only slightly, if the temperature change is small.
- Examples named: **size, volume, density**; the **amount of light/IR radiation
  emitted** at different frequencies; and many others, e.g. **electrical
  conductivity**.

**Thermal expansion — typical behaviour, with exceptions:**

- Solids, gases in balloons, liquids in tubes: hotter → bigger. "Size" means
  **length, area, or volume**.
- Slide's honest caveat: **this is typical behaviour, but there are exceptions!**
  (Some materials misbehave — the exceptions come later.)

**And radiation:**

- Hotter → **more IR radiation**. Every object emits; temperature tunes how much
  and at which wavelengths.

EM spectrum figure reused with real-wavelength caption: gamma (~10⁻¹⁴ m) down to
AM radio (~10⁴ m). Visible light is the 400–700 nm slice; infrared sits just left
of it, between visible and radar.

---

# STEP 5 — Clicker 2: contact between two blocks

*What happens if we put a hot block in contact with a room-temperature block?*

- A · Nothing → ✗ "Something always happens when temperatures differ — energy
  transfer at the contact."
- B · Heat flows until they are the same temperature → ✓ "Right — heat flows
  (hot → cold) until they reach the SAME temperature. Note what that means: BOTH
  blocks change. The hot one cools, the cold one warms — they meet somewhere in
  between."
- C · The hot block will cool down to room temperature → ✗ "Incomplete: the hot
  block does cool — but not all the way to room temperature, because the
  room-temperature block is warming up at the same time. They meet in between."
- D · The room temperature block will heat up to the temperature of the hot
  block → ✗ "Symmetric mistake: the cold block warms, but the hot block is
  simultaneously cooling. Nobody climbs all the way to the other's starting
  temperature."
- E · None of the above → ✗ "B is correct and complete: heat flows until the two
  blocks share one temperature."

Trap note: C and D assume one block is a passive spectator. Conservation of
energy (step 2) forbids it: what one loses, the other gains. Where exactly they
meet depends on the blocks' sizes — that's a later lecture's tool.

---

# STEP 6 — The rule of contact: three outcomes

Bring two objects into contact — **one of three things** can happen:

1. **Nothing changes.** The systems are in **EQUILIBRIUM** — and they have the
   **SAME TEMPERATURE**.
2. **Energy flows from the hotter to the colder.** = a flow of HEAT. (Slide's
   picture: brick → balloon, brick has the higher temperature.)
3. **Same, other direction.** Energy flows balloon → brick = flow of HEAT;
   balloon has the higher temperature.

Reading-the-rule check: "energy flows from brick to balloon = flow of HEAT"
confirms L01's definition — **heat is the name for energy while it is in
transit** between objects, driven by a temperature difference. Direction is set
by temperature, never by "who has more energy".

---

# STEP 7 — The Zeroth Law — why thermometers work

**If A is in equilibrium with B, and A is in equilibrium with C, then B and C
are in equilibrium with each other.**
"Otherwise, temperature wouldn't make sense!"

Why it matters: it's the law that makes temperature comparison possible without
objects touching each other. A thermometer is just object A — small, calibrated,
in equilibrium with whatever it touches.

**Clicker Question 3** — *A mercury thermometer sits in a glass of water. If the
thermometer reads 20 °C, we can conclude that:*

- A · The temperature of the water is 20 °C → ✗ "Half right — but you can only
  conclude the water's temperature BECAUSE of the mercury's temperature. B is
  also true, so this isn't the best answer."
- B · The temperature of the mercury is 20 °C → ✗ "Also half right — the mercury
  IS at 20 °C. But the Zeroth Law then forces the water to be at 20 °C too. C is
  the complete answer."
- C · Both A and B → ✓ "Correct — BOTH. The thermometer has sat in the water long
  enough to reach equilibrium: mercury and water share one temperature. The
  reading directly tells you the mercury's temperature; the Zeroth Law transfers
  that conclusion to the water."
- D · Neither → ✗ "Both are true — this is the Zeroth Law in action."

Subtle point: the thermometer reading **directly** measures only the **mercury**.
The water's temperature is an **inference**, licensed by equilibrium — the Zeroth
Law is that license.

---

# STEP 8 — Demo prediction + 60-second review

**Predict: the IR-camera demo.** Two aluminium blocks — one off the hot plate,
one left in the room for a long time — placed in contact, watched with an IR
camera (hotter = brighter). Sketch:

- **(a) Just as the blocks touch:** hot block bright, room block dim — and a
  sharp brightness contrast at the contact.
- **(b) After a short time:** warmth spreading into the cool block near the
  contact; the contrast softening.
- **(c) After a long time:** both blocks one uniform brightness — equilibrium,
  one temperature.

(This is the two-brick worked example from the deep-dive, made visible. The
camera is the thermometer idea wearing a camera body: it reads IR emission,
which temperature tunes.)

**60-second review:**

- **Conservation of Energy:** isolated system's total is constant; energy
  transfers between parts and changes form; thermo tracks microscopic KE **and**
  PE. (Joule.)
- Heating/cooling = adding/removing molecular energy; hot brick = more kinetic
  **and** potential energy.
- Most macroscopic properties shift with temperature (size, density, IR output,
  conductivity) — usually slightly.
- Thermal expansion is **typical, with exceptions**; "size" = length, area, volume.
- Contact = three outcomes: nothing (equilibrium, same T) / heat flows hot → cold.
  Direction set by temperature, never by total energy.
- **Zeroth Law:** A–B and A–C in equilibrium ⇒ B–C in equilibrium. Thermometers
  work because of it.
- Next class: **methods for measuring temperature**.

---

## Sources (for fact-checking)

- L2-prelecture.pdf (17 slides — the ONLY taught source for this page)
- L01 materials for the bridging claims (previous QA'd pages)
