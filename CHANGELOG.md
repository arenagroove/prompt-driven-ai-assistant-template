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

