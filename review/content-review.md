# PHYS Course OS — Content Review Pack (v0.2, L01 Pre-class)

## Context for the reviewer

This is the complete text content of a 10-step "pre-class reading" page for
**PHYS 157 (UBC, 2026W1, thermodynamics + waves), Lecture 1 (Introduction)**.
The target reader is a first-year engineering student who wants to master the
pre-class material before the lecture and before ORCA Quiz 1.

Please review for:

1. **Physics accuracy** — any wrong or misleading statement? L01 officially contains NO equations; the note should not smuggle later material in as if taught.
2. **Conceptual ordering** — does each step deepen the previous one without jumps?
3. **Question quality** — is the single predict-question and the six check-questions high-value (conceptual, not arithmetic)?
4. **Tone** — should read like a human tutor's notes, not a textbook dump. Flag anything that feels robotic or patronizing.
5. **Traps** — are the flagged misconceptions the right ones for this material?

Interactive elements are marked 【interactive】; SVG diagrams are marked 【diagram】.

---

# STEP 1 — How this works, and the two pillars

This page is your **pre-class reading** for L01 — the part to master *before*
re-watching the lecture or the quiz. Ten short steps, each one deeper than the
last. Progress is saved in this browser.

**By the end you can:**
- tell the cold-brick story **twice** — macroscopically and microscopically;
- distinguish **temperature**, **heat**, and **thermal equilibrium**;
- explain why thermodynamics is possible at all;
- say what L01 deliberately does **not** contain yet.

Blue-highlighted terms are **wiki links** — clicking opens that concept page in
the site. The full network is step 8 and the Concept library.

**Pillar 1 — Thermodynamics** (first half of term): macroscopic variables (T, V,
p), thermal expansion, phase change, heat and its transfer methods, equilibrium.
Built on averages over ~10²³ particles.

**Pillar 2 — Oscillations & Waves** (second half): *collective* motion of the
same molecules: guitar strings, sound, ocean waves. Described by a wave
equation — again, no per-particle tracking.

⚠️ L01 contains **no formulas**. If you catch yourself deriving one here, you're
ahead of the lecture — park it.

---

# STEP 2 — The cold brick: predict first

September 9, Hebb building. Prof pulls a brick out of a cooler. The room's first
guess: *liquid nitrogen*. Wrong — it sat in **dry ice**, so the brick starts at
about **−78.5 °C**. Then it just sits in the ~20 °C room while everyone talks
about it.

【interactive — single-choice, instant feedback】
*In the first minute, what do you actually see?*

- A · Nothing — the brick just sits there, unchanged →
  ✗ "Look at the temperature difference: −78.5 °C vs ~20 °C. Something dramatic
  happens at the surface — and it is not silence."
- B · Frost forms on the brick's surface →
  ✓ "Right. Water vapour in the air touches a surface far below 0 °C and leaves
  the gas phase → frost forms almost immediately. Meanwhile heat starts flowing
  into the brick and it begins warming."
- C · The brick glows faintly →
  ✗ "Glowing needs a far higher temperature. Room-temperature objects do
  radiate — but in the infrared, which your eyes cannot detect. The brick is
  glowing right now; you just can't see it."
- D · Water pools underneath it →
  ✗ "Meltwater only appears once the surface climbs past 0 °C — not in the
  first minute. First comes frost."

**What actually happened (slide photos):**
- ~15 min: frost over the whole brick.
- ~25 min: frost retreating — **corners and edges clear first** (most exposed
  surface per amount of brick → they warm fastest).
- ~1 hr: brick nearly clear, temperature approaching room temperature.

【diagram — warming curve】 The brick's temperature over its hour on the desk.
It never jumps to room temperature — it approaches, fast at first, then slower.
Frost can only exist while the surface is below the 0 °C line. (Labelled
"qualitative sketch — the shape is what matters, not the numbers".)

**Wording trap (reveal):** Slides say *condensation*, but at −78.5 °C the vapour
goes from gas **straight to solid** — deposition (凝华). The photo is
unmistakably frost, not liquid. Keep both words in your head; the instructor's
shorthand and the strict term differ.

---

# STEP 3 — The macroscopic view

**Macroscopic** = the scale you can see or measure with instruments. Five
measurable statements:

1. **Heat flowed in** — from everything warmer: the air, the desk it sat on.
   Big temperature difference → fast flow at the start.
2. **Its temperature rose** — continuously, then more slowly.
3. **Its dimensions grew** — every linear dimension, slightly. (Thermal
   expansion: first real topic of the course.)
4. **Frost formed, then cleared** — a phase change happening in the air next to
   the brick.
5. **It stopped changing** — brick and room reached the same temperature. That
   endpoint is thermal equilibrium.

Notice what this language never mentions: atoms. That's the point — macroscopic
variables are chosen so you *don't need* the atoms. Next step: the same story in
the other language.

---

# STEP 4 — The microscopic view

Same brick, atomic vocabulary — three processes:

1. **The brick's atoms vibrate.** It's a solid: atoms are not free to wander —
   they **vibrate about fixed equilibrium positions**. Cold brick = slow,
   low-energy vibrations. (This contrast is quiz-bait.)
2. **Air molecules collide with it.** Fast molecules strike the brick's surface;
   each impact transfers a bit of momentum and energy. Billions of tiny
   deliveries per second = "heat flowing in".
3. **Everything radiates.** Any object, any temperature, emits electromagnetic
   waves; the wavelength is set by temperature. Room temperature → mainly
   **infrared** — real energy transfer, invisible to your eyes. IR-camera demo
   with two warm bricks promised for next lecture.

【diagram — two live animations side by side】
- SOLID: a 5×3 lattice of blue atoms, each jiggling around its own
  equilibrium-site crosshair.
- GAS: six red molecules flying across a box on independent paths.

【diagram — EM spectrum bar】 radio | **IR** | visible | UV | X-ray | gamma.
The brick at room temperature radiates in the infrared band — just left of the
tiny slice your eyes can see.

**Go deeper (reveal):** Is energy flowing one way, molecule by molecule? No —
and hold onto this. In *every single collision*, energy crosses the boundary in
**both** directions. What makes the brick warm up is that the exchanges are
unequal: the fast (hot) side delivers more on average. The word doing the work
is **net**. It comes back at equilibrium — and in a question waiting in the
tutoring chat.

---

# STEP 5 — The bridge: averages become variables

Why can two such different stories describe one brick? Because of the idea the
whole course stands on:

**microscopic behaviour → statistical averages → macroscopic variables →
thermodynamics**

A brick holds ~10²³ particles. Tracking each is impossible — and, beautifully,
**unnecessary**, because a few averages summarize everything we care about:

- The brick's overall **size** (Volume) reports the **average spacing** between
  atoms — which is exactly why thermal expansion is visible at all.
- The brick's **temperature** (Temperature) is the **average kinetic energy**
  (Kinetic Energy) of its vibrating particles. Prof's phrasing, worth
  memorizing: *"the average of all those kinetic-energy values is what we call
  temperature."*

That is what **Thermodynamics** is: the art of summarizing 10²³ things into a
handful of variables, then finding the rules those summaries obey. Measuring the
macroscopic scale tells you what the microscopic world is doing **on average**.

---

# STEP 6 — Temperature vs Heat vs Equilibrium

Three words the quizzes love to blur. Three clean definitions:

- **Temperature** — a **property of the object** — a *state variable* (状态量).
  It describes what the system *is*: the average kinetic energy of its particles.
- **Heat** — **energy in transit**, driven by a temperature difference. Not a
  property of anything — it only exists *while crossing a boundary*, carried by
  collisions and radiation.
- **Thermal Equilibrium** — the endpoint of heat flow: common temperature, and
  the **net** exchange drops to zero because the two averages have matched.

【diagram — "heat traffic"】 Panel 1 (not yet equilibrium): HOT → COLD with a
thick arrow (net flow) and a thin reverse arrow (some energy still comes back).
Panel 2 (equilibrium): equal arrows both ways, "net = 0 — but arrows never
disappear". Caption: *equilibrium = balanced traffic, not an empty road*.

**The two traps:**
- **"The brick contains heat" — wrong.** An object contains *internal energy*;
  "heat" names energy *while it moves between things* — the way "flow" describes
  water in a pipe, not water sitting in a bucket.
- **"At equilibrium everything stops" — wrong.** Collisions continue, energy
  crosses both ways every instant. Equilibrium is **balanced traffic, not an
  empty road**.

---

# STEP 7 — The waves teaser

Last five minutes of L01, and easy to dismiss — don't. The brick was also being
hit by **sound** from every voice in the room and by light from the ceiling.
Those are **waves**:

- a wave is **collective motion** — enormous numbers of particles moving in
  coordination, so that **energy travels without the material travelling**;
- examples named in lecture: sound waves, guitar strings, ocean waves;
  oscillations can be **transverse** or **longitudinal**;
- and the same trick as thermodynamics applies: nobody will track 10²³
  particles — a **wave equation** summarizes the collective behaviour.

Both pillars, one idea: *stop tracking individuals; summarize.* Thermodynamics
does it with averages; waves do it with a wave equation. That parallel is the
deepest thing L01 plants.

---

# STEP 8 — Your concept graph

An interactive node graph of the 12 concept pages (see Concept Library below).
Clicking any node opens that concept page. One dashed link marks the second
pillar (Oscillations → Waves), preview-only.

Graph structure:

```
Micro ↔ Macro
├── Temperature ↔ Kinetic Energy
├── Volume
├── EM Radiation
├── Thermodynamics
│   ├── Heat → Thermal Equilibrium
│   ├── Phase Change
│   └── Thermal Expansion
└── (dashed) Oscillations → Waves
```

---

# STEP 9 — Check yourself

Six conceptual questions. Answer out loud *first*, then reveal. 【interactive】

1. **Why is tracking every particle impossible — and why is that fine?**
   → A brick has ~10²³ particles; no one can follow them. It's fine because the
   **averages** are all that matter, and averages appear as macroscopic
   variables (size ↔ spacing, temperature ↔ average kinetic energy). Summaries +
   rules = thermodynamics.
2. **How does a brick atom's motion differ from an air molecule's?**
   → Brick atoms are a solid: they **vibrate about fixed positions**. Gas
   molecules **travel long distances** between collisions. "Vibrate" vs
   "travel" — don't blend the pictures.
3. **Which is the state variable — temperature or heat? Define the other.**
   → Temperature is the state variable (it describes what the object *is*).
   Heat is **energy in transit**, driven by a temperature difference, carried by
   collisions and radiation. Objects contain internal energy, never "heat".
4. **At thermal equilibrium, what exactly stops — and what continues?**
   → The **net** energy flow stops (temperatures equal, averages match).
   Individual collisions continue in **both** directions forever. Balanced
   traffic, not an empty road.
5. **Why did the frost clear from corners and edges first?**
   → Corners/edges have the most **exposed surface per amount of brick**, so
   they collect heat fastest and warm first. Geometry controls heat-flow rate.
6. **The brick radiates constantly — why can't you see it?**
   → At room temperature the emission is mainly **infrared**: wavelength set by
   temperature, and the visible band is a narrow slice our eyes evolved for.
   The radiation is real and carries energy — just not in colors we detect.

---

# STEP 10 — 60-second review, and done

- Macroscopic variables = **averages** over ~10²³ particles; thermodynamics
  studies the rules of those averages.
- **Temperature** = average kinetic energy of particles — a state variable.
- **Heat** = energy in transit, hot → cold, carried by **collisions +
  radiation**; never "stored".
- Cold brick: heat in → warms → expands; frost **deposits**, clears **corners
  first**, gone by ~1 hr.
- **Equilibrium**: same temperature, **net** flow zero, two-way collisions
  continue.
- Everything radiates; wavelength set by temperature; room-T = infrared,
  invisible.
- Waves = **collective motion** — second pillar, same "summarize, don't track"
  trick.

**Next:** answer the tutor's diagnostic (steel railing vs wooden bench at the
same 12 °C) · say "next page" for the L01 deep-dive · bring L02 materials.

【button】 ✓ Mark L01 pre-class complete

---

# CONCEPT LIBRARY (12 in-site wiki pages)

Each concept page opens when its blue term is clicked anywhere in the steps,
and from the graph. Each carries a status badge ("introduced · L01" or
"previewed · L01") and related-concept chips.

1. **Microscopic & Macroscopic Description（微观与宏观描述）** — Two vocabularies
   for the same object. Microscopic: what atoms/molecules do (vibrate about
   fixed sites in solids; translate and collide in gases; radiate).
   Macroscopic: the few measurable variables encoding the *averages*. Chain:
   microscopic behaviour → statistical averages → macroscopic variables →
   thermodynamic laws. Mappings: size ↔ spacing; T ↔ avg KE.
2. **Temperature（温度）** — A macroscopic variable and a *state variable*:
   measures the **average kinetic energy** of a system's particles. Sets the
   direction of spontaneous heat flow (hot → cold) and the endpoint
   (equilibrium).
3. **Volume（体积）** — Macroscopic variable reporting the **average spacing**
   between atoms/molecules — why thermal expansion is visible.
4. **Kinetic Energy（动能）** — Energy of motion, E = ½mv². Thermal role:
   temperature reflects the *average* KE of particles — in the brick, of atoms
   vibrating about their sites.
5. **Thermodynamics（热力学）** — The study of how macroscopic variables
   summarize ~10²³ particles and the rules those summaries obey.
6. **Heat（热）** — **Energy in transit** driven by ΔT. Carriers: molecular
   collisions; radiation (IR). ⚠️ An object contains internal energy — it does
   not contain heat.
7. **Thermal Equilibrium（热平衡）** — Endpoint of heat flow: common
   temperature; **net** exchange = 0 while two-way collisions continue.
8. **Phase Change（相变）** *previewed* — Solid/liquid/gas transitions. L01:
   vapour → frost on the −78.5 °C brick (deposition, 凝华; slides' shorthand:
   "condensation"). Latent heat comes later.
9. **Thermal Expansion（热膨胀）** *previewed* — Every linear dimension grows
   with temperature (microscopically: average spacing grows). Formal law later.
10. **Oscillations（振动）** *previewed* — Repeated motion about an equilibrium
    position — already true inside the brick. Second half builds single
    oscillators → waves.
11. **Waves（波）** *previewed* — Travelling **collective motion**: energy handed
    neighbour to neighbour without the material travelling. Wave equation later
    — no per-particle tracking.
12. **Electromagnetic Radiation（电磁辐射）** — Every object emits EM waves at
    any temperature; wavelength set by temperature; room-T → infrared
    (invisible). One of the energy-transfer channels.

---

## Sources (for fact-checking)

- L1-Introduction.pdf (pre-class slides)
- L1-Intro-post.pdf (post-class slides with annotations — canonical)
- Wednesday.txt (lecture recording transcript; garbled ASR, calibrated copy at
  `PHY 157/week 1/Wednesday (calibrated).txt`)
