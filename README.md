# 🧠 Prompt-Driven Assistant Template – README Overview

![Prompt-Driven Assistant Template Cover](prompt-driven-ai-assistant-template-cover.png)

**A modular, customizable framework for building Prompt-Driven AI Assistants — where behavior, tone, and structure are fully defined through prompt layers.**


This template helps you design powerful, strategic, and creative assistants using a transparent, modular prompt system — not hidden code or black-box logic.

It supports role-based behavior, drift-level creativity, bias control, and collaborative workflows.

## 🚀 Quick Start

Follow these steps to get your assistant running:

1. Open `template-GPT.md` and define your assistant’s **name, purpose, and mission**.
2. Select your **roles, lenses, drift level, output modes**, and **bias/fact-check mode**.
3. Review the **output structure** and align examples and formats.
4. Choose your **platform** (OpenAI, Claude, etc.) and follow platform-specific setup.
5. Use the **Customization Checklist** and **Refinement Loop** for iteration.
6. Test, deploy, and adapt your assistant.

## ⚠️ Platform-Specific Guidance

### **For OpenAI Custom GPTs**

- **Instructions Field Limit:** 8,000 characters (including spaces and line breaks).
- **Workarounds:**
    - **Move non-essential or reusable content** (detailed examples, presets, configuration notes) to the “Knowledge” section or to attached files.
    - **Use concise, modular instructions** in the main field, referencing external content for details.
    - **For large templates:** Split instructions into logical modules and reference them in the main prompt, or use a “prompt chaining” approach. *Prompt chaining means breaking complex tasks into sequential steps, where each step’s output informs the next.*
- **Best Practices:**
    - **Define WHO, WHAT, and WHY** at the start of your instructions.
    - **Break down complex instructions** into clear steps, using delimiters and few-shot examples where needed.
    - **Specify output format and style** for consistency.
    - **Use Markdown formatting** for improved readability.


### **For Claude and Other Models (Facing Prompt)**

- **Prompt Structure:** Claude responds well to clear, structured prompts with explicit instructions and examples.
- **Best Practices:**
    - **Use XML or Markdown** to separate instructions, context, and examples.
    - **Assign a clear role** at the start (“You are a [role]...”) and specify the expected output format.
    - **Prefill the start of the assistant’s message** to control output structure and tone.
    - **Use prompt chaining or step-by-step instructions** for complex tasks.
    - **Claude’s context window is large** (up to 200,000 tokens), but keep prompts concise for clarity.
- **Adaptation Tips:**
    - **Remove or condense OpenAI-specific references.**
    - **Adjust formatting** if using XML tags for Claude.
    - **Test and iterate** to optimize for Claude’s conversational and analytical strengths.

*For other LLMs (e.g., Gemini, Mistral): Adapt the prompt structure as above, using clear instructions and examples. Test and adjust for each model’s strengths and quirks.*

## 🧩 Key Features

- Modular design with roles, lenses, and personality modes.
- Interpretive drift levels from Literal to Unmoored.
- Output intent + flavor for tone and use case control.
- GEO-aware assistant design for AI citation, discoverability, and structured formatting.
- Built-in Bias \& Fact-Check Mode (Strict / Flexible / Creative).
- Structured outputs and behavioral principles.
- Presets for common tasks + example prompts.
- Refinement loop for iterative feedback.
- Testing, validation, troubleshooting, and collaborative tools.
- Optional PrecisionMode for stricter factual control (Strict / Adaptive / Experimental).
- Supports prompt engineering techniques like Emotion Shaping or Scrambled Prompting.
- Prompt Sharpening Guide for GPT‑4.1, Claude, Gemini (role clarity, micro-steps, scannable structure)


## 🧱 Template Structure Overview

| Section | Description |
| :-- | :-- |
| **Purpose** | Defines the assistant’s core objectives and value proposition. |
| **User Input Guidelines** | Details accepted input types, best practices, and constraints. |
| **Prompt Sharpening Guide** | How to write clear, modular, example-driven prompts for GPT-4.1, Claude, Gemini. |
| **Roles** | Behavioral perspectives (e.g., Strategic Partner, Creative Director). |
| **Lenses** | Interpretive contexts (e.g., Narrative Layering, Strategic Focus). |
| **Drift Levels** | Range from literal to recursive interpretation. |
| **Output Modes** | Intent (Concept, Tooling, Strategy, Reflective, Hybrid) and flavor options. |
| **Personality Modes** | Tone and delivery settings (e.g., Neutral, Conversational, Poetic). |
| **Bias \& Fact-Check Mode** | Strict, Flexible, or Creative/Experimental bias mitigation + optional PrecisionMode. |
| **Output Structure** | Standard and performance content formats. |
| **Behavioral Principles** | Core behaviors and quality standards. |
| **Refinement Loop** | Next-step options for iterative improvement. |
| **Collaborative Integration** | Tool suggestions and workflow integration. |
| **Edge Case Handling** | Strategies for vague or experimental inputs. |
| **Strategic Enhancers** | Credibility boosters and AI optimization tips. |
| **Preset Modes** | Shortcut configurations for common use cases. |
| **Role Flow** | Multi-agent handoffs and cooperative logic. |
| **Memory & Reflection** | Feedback simulation and behavioral adaptation. |
| **Interactive Preset Logic** | Adaptive behavior rules based on drift, lens, or user intent. |
| **Critique Mode** | Optional self-reflection logic to evaluate assistant output. |
| **Usage Examples** | Practical prompts and expected outputs. |
| **Configuration Notes** | Implementation and multi-agent integration guidance. |
| **Customization Checklist** | Step-by-step checklist for tailoring the template. |
| **Testing \& Validation** | User feedback, A/B testing, and success metrics. |
| **Troubleshooting \& FAQ** | Common issues and solutions. |
| **Version History** | Track changes and updates. |


## ⚙️ Configuration \& Customization

- **Roles \& Lenses:** Select and combine from the provided libraries.
- **Drift Level:** Set the default level of interpretation (e.g., Symbolic).
- **Output Modes:** Choose intent and flavor for each use case.
- **Bias \& Fact-Check Mode:** Configure strictness for accuracy and neutrality.
- **Preset Modes:** Define shortcut configurations for rapid deployment.
- **Customization Checklist:** Follow the checklist to ensure all sections are tailored.

**Example Configuration:**

```markdown
BiasMode: [Strict | Flexible | Creative/Experimental]
```

## 📋 Usage Examples

**OpenAI Custom GPT Example:**
`"Reposition this old product as a modern learning tool"`
→ 3-option output + feasibility summary

**Claude Facing Prompt Example:**
`"You are a creative strategist. Use the Narrative Essence lens and Drift 3 to transform this product description into a compelling story. Output in Markdown."`
→ Story output with specified lens and drift

*Before/After Example:*

- **Before:** `"Summarize this document."`
- **After:** `"Summarize this document using the Reflective Learning lens and Drift 2. Include key insights and actionable recommendations."`
→ Summary with structured insights

**Refinement Chain Example:**  
`"Remix this 2010 portfolio site for a modern creative studio"`  
→ Initial: symbolic, brand-focused rewrite  
→ Follow-up: “Want it more human or more speculative?”


## 🧪 Testing \& Validation

- **User Feedback Loop:** Collect and integrate user feedback for continuous improvement.
- **A/B Testing:** Compare different output modes or presets for effectiveness.
- **Production Checklist:** Review security, privacy, and performance before deployment.
- **Success Metrics:** Track user engagement, accuracy, and speed.


## 🚨 Troubleshooting \& FAQ

**Q: What if my output is too vague?**
A: Use the Discovery Phase or request clarifying questions.

**Q: How do I ensure factual accuracy?**
A: Set Bias \& Fact-Check Mode to Strict and use Critical Reader role.

**Q: How can I adapt this for global audiences?**
A: Enable localization and internationalization guidelines.

**Q: How do I adapt the template for Claude?**
A: Use as a facing prompt, adjust formatting for XML or Markdown, and specify roles and output formats clearly.

**Q: What is prompt chaining?**
A: Prompt chaining is breaking complex tasks into sequential steps, where each step’s output informs the next.

## 🤝 Contributing

Contributions are welcome! Please follow the project’s style and documentation standards. For major changes, open an issue to discuss your ideas.

## 📝 Version History

| Version | Date       | Changes                                                                 |
|--------:|:-----------|-------------------------------------------------------------------------|
| 1.0     | 2025-07-01 | Initial release with full assistant framework, lens system, drift levels, bias modes, and project docs |
| 1.1     | 2025-07-02 | Renamed references for consistency, clarified terminology, updated tags and naming across files |
| 1.1.1   | 2025-07-02 | Added Natural Style Writing Assistant test case + optional “Do/Don’t” glossary module in `template-GPT.md` |
| 1.2     | 2025-07-02 | Major upgrade: regenerated all test cases, added Prompt Engineering & PrecisionMode, output fix, strategic enhancements |
| 1.3     | 2025-07-03 | Added multi-agent role flow, memory simulation, adaptive preset logic, and critique mode |
| 1.3.1   | 2025-07-02 | Added GEO Content Strategist test case focused on AI citation and LLM discoverability |
| 1.3.2   | 2025-07-02 | Added Prompt Sharpening Guide (GPT‑4.1, Claude, Gemini) + new GEO micro-step test case + updated docs for alignment |


## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

## 🔖 Tags

`#PromptEngineering` `#PromptDrivenAssistant` `#MultiAgent` `#CreativeAI` `#ModularGPT` `#LensDesign` `#StrategicUX` `#InterpretiveDrift`
