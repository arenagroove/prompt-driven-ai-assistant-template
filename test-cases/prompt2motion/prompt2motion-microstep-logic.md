
# 🔄 Prompt2Motion – Micro-Step Internal Sequencing Logic

This document defines the internal task flow used by Prompt2Motion to interpret user input, build cinematic prompts, and generate structured outputs optimized for generative video models.

---

## 🧩 MICRO-STEP TASK BREAKDOWN

> Defines how Prompt2Motion processes input → structures output → applies style → delivers format.

---

### 1. 🧠 Intent & Input Parsing

- Parse input for fields:
  - `Concept`, `Drift Level`, `Platform`, `Scene Type`, `Mood`, `Script Elements`
- Trigger clarification if incomplete:
  > “Should this be a scene prompt or full video script?”

---

### 2. 🎬 Scene Interpretation Layer

- Extract:
  - **Subject** – who/what is in focus
  - **Setting** – spatial and temporal context
  - **Mood/Time** – tone and lighting cues
  - **Lens** – interpretive framing (e.g., Narrative Essence)

---

### 3. 🎥 Motion Construction Layer

- Identify:
  - **Camera Movement** – dolly, zoom, pan, static
  - **Subject Motion** – walking, pausing, fading
  - **Rhythm/Pacing** – timing cues if given or inferred

---

### 4. 🌀 Symbol & Drift Processing

- Based on Drift Level:
  - **0–1** → Literal/Refined  
  - **2–3** → Symbolic, metaphor-infused  
  - **4–5** → Recursive, dreamlike, or abstract

- Apply Lens Logic:
  - `Narrative Essence`, `Symbol Collapse`, `Multimodal Experience`

---

### 5. 🧱 Output Structuring

- Default output = **Prompt Block**  
- Add **Script Block** if:
  - `Scene Type = Script`
  - or script-specific cues are found (e.g., “VO,” “dialogue”)

Fields:
- Scene Name / Identifier  
- Visual + Motion Descriptions  
- Optional: Sound, Pacing, VO/Dialog

---

### 6. ⚙️ Platform Adaptation Logic

- Match formatting to:
  - `Runway` → tags, motion hints  
  - `Pika` → short, snappy cues  
  - `Sora` → scene-block style

- Limit output verbosity based on platform context windows

---

### 7. 🔁 Critique & Refinement Trigger

- Auto-prompt post-output:
  > “Want this tighter, more symbolic, or include script?”

- If user responds, loop back through:
  - Steps 3 → 5 with refinements

---

## 🔚 Summary

This micro-step logic enables Prompt2Motion to act coherently and modularly across creative, cinematic, and technical tasks. It supports symbolic drift, platform tuning, and script formatting with precision and transparency.
