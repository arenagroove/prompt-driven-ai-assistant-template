
# 🧠 Prompt2Motion – Deployment & Usage Guide (2025)

Prompt2Motion is a cinematic, symbolic, and multimodal prompt assistant optimized for generative video tools like Pika, Runway, and Sora. This README explains how to deploy and use the assistant across platforms, including Custom GPT setup and manual prompt chaining.

---

## 🚀 1. Using Prompt2Motion in OpenAI Custom GPT

### ✅ What to Upload:
- `prompt2motion-gpt-instructions.txt` → Paste this into the **Instructions** field.
- `prompt2motion-refinement-guide.md` → Upload as a **Knowledge File**
- `prompt2motion-microstep-logic.md` → Upload as a **Knowledge File**

### 💡 Suggested Settings:
---

### 🧱 Custom GPT GUI Field Setup (2025)

| Field | Recommendation |
|-------|----------------|
| **Name** | Prompt2Motion |
| **Logo** | 🎞️ or upload symbolic/cinematic icon |
| **Description** | “Transforms your ideas into cinematic generative video prompts or scripts using symbolic logic, motion layering, and platform-aware formatting.” |
| **Conversation Starters** |  
- “Create a surreal forest chase with Drift 4.”  
- “Add voiceover to this image-to-video prompt.”  
- “Storyboard a dream using symbolic motion.” |
| **Knowledge Files** |  
- `prompt2motion-refinement-guide.md`  
- `prompt2motion-microstep-logic.md` |
| **Recommended Model** | GPT-4o |
| **Capabilities Checkboxes** |  
- ✅ Web Search *(optional)*  
- ✅ 4o Image Generation *(if needed)*  
- ✅ Code Interpreter & Data Analysis *(optional – for formatting/CSV scripts)* |
| **Actions** | None (unless integrating APIs like Runway, Pika, or storyboarding tools) |

- **Welcome Message**: “Let’s turn your vision into a cinematic prompt or video script.”
- **Prompt Starters**:
  - “Create a scene for a surreal desert memory, include motion”
  - “Use Drift 4 to make a poetic loop from this still image”
- **Default Personality**: Neutral/Poetic
- **Default Drift**: 3 (Symbolic)
- **Tools**: None (unless integrating with Runway API or Pika)

### 📝 Example Input (Formatted):
```
Concept: A crow flying through ash clouds  
Scene Type: Script  
Mood: ominous, slow-paced  
Drift: 4  
Platform: Pika  
```

---

## 🛠 2. Using Prompt2Motion Outside Custom GPTs

### ✅ Claude / Anthropic:
- Use `prompt2motion-gpt-instructions.txt` as a facing prompt.
- Upload `.md` files as documents or reference them inline:
  - E.g., “Refer to the Micro-Step Logic for how to structure the scene.”

### ✅ Manual Prompt Chaining:
You can paste parts of the logic step-by-step:
1. Describe the concept and scene
2. Ask for motion and emotion layering
3. Request Drift-based symbolic rework
4. Ask for platform formatting (Runway, Pika…)

---

## 🔍 Recommended Input Fields

To ensure accurate and rich output, try to provide:

| Field | Description | Example |
|-------|-------------|---------|
| `Concept:` | The core visual idea | “A lighthouse at the edge of a storm” |
| `Scene Type:` | prompt-only, script, or storyboard | “script” |
| `Mood:` | Tone, pacing, emotion | “eerie, reflective” |
| `Drift:` | 0–5 symbolic drift scale | 3 |
| `Platform:` | Output target (Pika, Sora, Runway) | “Runway” |
| `Extras:` | VO, dialogue, narration, sound | “voiceover describing memory loss” |

---

## 🎛 Included Files

| File | Purpose |
|------|---------|
| `prompt2motion-gpt-instructions.txt` | Optimized system prompt for OpenAI Custom GPT |
| `prompt2motion-refinement-guide.md` | Output structuring, input sharpening, builder logic |
| `prompt2motion-microstep-logic.md` | Internal micro-step task sequencing for prompt behavior |
| `prompt2motion-build-summary.md` | Assistant creation workflow, architecture, deployment recap |
| `README.md` | Deployment instructions, GUI setup, platform usage guide |

## 🔚 Credits & Tags

Developed using the **Prompt-Driven Assistant Framework**  
Tags: `#PromptEngineering`, `#GenerativeVideo`, `#SymbolicDrift`, `#MultimodalPrompt`, `#OpenAI`, `#Claude`, `#Runway`, `#Pika`, `#CreativeAI`
