# 📦 CHANGELOG

All notable changes to this project will be documented in this file.

---

## [1.0.0] – 2025-07-01
### Added
- Initial release of the **Prompt-Driven AI Assistant Template**
- Modular assistant template with:
  - Role-based behavior and tone system
  - Interpretive lens library and drift level logic
  - Output mode and personality modifiers
  - Bias & Fact-Check Mode (Strict, Flexible, Creative)
  - Structured output formats and performance content structure
  - Testing, troubleshooting, and refinement loop
- MIT License and versioning logic
- Visual cover image for GitHub and documentation
- Internal docs: `PROJECT.md`, `README.md`

---

## [1.1.0] – 2025-07-01
### Changed
- Renamed project references to use "Prompt-Driven Assistant Template" consistently
- Clarified terminology: Prompt-Driven AI Assistant vs Template
- Updated titles and tags across `README.md`, `PROJECT.md`, and `template-GPT.md`
- Aligned tag structure and naming conventions

---

## [1.1.1] – 2025-07-01
### Added
- New test case: Natural Style Writing Assistant
- Optional "Style Glossary (Do/Don't List)" module referenced in `template-GPT.md` under Input Guidelines

---

## [1.2.0] – 2025-07-02

### Added
- PrecisionMode (Strict / Adaptive / Experimental) added to bias/fact-check configuration
- Prompt Engineering Techniques (e.g., Emotion Shaping, Scrambled Prompting)
- Output Format block rewritten for stricter GPT compliance
- Strategic Enhancers section (credibility boosters, shareability, symbolic logic)
- Quick-Start Guide section for assistants
- Enhanced refinement loop and symbolic drift support
- `test-cases/` directory fully regenerated using final template-GPT.md

### Updated
- All test cases regenerated to match final structure and tone
- `README.md` structure block updated to reflect actual project layout
- `.gitignore` updated to exclude `tools/` folder
- Folder names and template comments made fully coherent across project

### Fixed
- Output splitting issues resolved via hardened Markdown block instructions

---

## [1.3.0] – 2025-07-03

### Added
- Role Flow section to support multi-agent logic and handoff design
- Memory & Reflection section to simulate feedback loops and adaptive behavior
- Interactive Preset Logic section for conditional outputs based on drift, lens, or user intent
- Critique Mode for optional assistant self-review and output reflection

### Updated
- `template-GPT.md` structurally aligned with all new logic while preserving compatibility
- `README.md` table updated to reflect new v1.3 sections
- `prompt-driven-assistant-generator.md` modified to support all new assistant capabilities
- All test cases rebuilt using the updated v1.3 template

### Fixed
- Duplicate and outdated optional input notes in the generator were consolidated

---

## [1.3.1] – 2025-07-02
### Added
- New test case: GEO Content Strategist
  - Supports Generative Engine Optimization (GEO) for AI citation and discoverability
  - Includes structured schema logic, citation formatting, and LLM visibility tools

---

## [1.3.2] – 2025-07-02

### Added
- Prompt Sharpening Guide for GPT‑4.1, Claude, Gemini:
  - 4-step strategy: role clarity, micro-steps, example use, brief-style formatting
  - Model-specific prompt best practices and checklist
- New section added to `template-GPT.md` after User Input Guidelines
- Updated references in `README.md` and `PROJECT.md`:
  - Key Features and Template Overview table updated
  - Project Overview includes sharpening logic under `template-GPT.md` scope

### Verified
- No regressions in assistant behavior
- Fully backward-compatible with v1.3.1 assistants
- Reviewed and validated by external tools (Perplexity)

### Test Cases
- Added `geo-content-strategist-micro-steps.md`:
  - Advanced modular breakdown of GEO optimization logic
  - Includes task-specific micro-steps for schema transformation, AI visibility, citation readiness, and strategic refactoring
  - Complements the core `geo-content-strategist.md` assistant

---

## [1.3.3] – 2025-07-02

### Same as 1.3.2
- Retagged from 1.3.2 to 1.3.3 to resolve GitHub display issue (emoji corruption)

---

## [1.4.0] – 2025-07-03

### Added
- **Multimodal Input Handling** section in `template-GPT.md`:
  - Supports input types like sketches, audio cues, and reference imagery
  - Enables symbolic interpretation and pacing suggestions based on non-textual input
- **Platform Formatting Layer**:
  - Output adaptation rules for cinematic/gen AI platforms like Runway, Pika, and Sora
  - Camera/motion syntax, verbosity control, and transition cue logic
- **Cinematic Preset Modes**:
  - New preset set (`Visual Script`, `Symbolic Drift`, `Speculative Reel`, etc.)
  - Binds lens + drift + output structure for video/script-based assistants

### Updated
- `README.md`:  
  - Feature list and structure table updated with 3 new items  
  - Version history includes v1.4 with descriptive label
- `PROJECT.md`:  
  - `template-GPT.md` bullet list extended with cinematic/multimodal support
  - Internal docs now describe full assistant scope including video/cross-sensory workflows

### Verified
- Fully backwards-compatible with v1.3.3
- Aligned across all documentation and implementation logic
- Validated via test assistant: **Prompt2Motion**



