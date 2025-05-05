# UPB Forge - Expanded Enhanced Framework. A new better way to collaborate with AI. 

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) <!-- Optional: Add a license badge if you choose one -->

**The Operating System for Advanced AI Collaboration.**

---

## Overview

The **Unified Prompt Bible (UPB) Forge** framework represents a significant evolution in structured AI collaboration. It's not just a collection of prompts; it's a comprehensive, **Document-as-OS (DocOS)** designed to be loaded directly into a capable AI's context window (like Gemini, Llama 4, ChatGPT-4.1, etc.).

This framework transforms a general-purpose AI into a suite of specialized expert agents, each equipped with defined personas, structured processes, cross-referenced knowledge, and context management tools. The goal is to enable deeper, more consistent, and highly effective collaboration on complex tasks across diverse domains, including:

*   Creative Writing & Literature (Novel Development via D2 Framework)
*   Critical Thinking & Analysis
*   Worldbuilding & Narrative Extrapolation
*   Special Systems Design (Magic, Tech, Psionics)
*   Coding, Development & Education Assistance
*   Game Design Conceptualization & Systems Integration
*   Advanced Prompt Engineering & Adaptation (The "Forge" aspect via Section H4)

This "Expanded & Enhanced" version incorporates powerful meta-prompting tools, dedicated sections for Game Design and Coding/Education, and integrated context management systems, making it a versatile platform for demanding creative and analytical projects.

## What Makes UPB Forge Unique?

*   **Guided Operation Mode:** When a **Prompt ID** (e.g., `D2-S3.5`) is used, the AI adopts a specific **expert persona** and follows detailed **internal steps** defined for that task section, ensuring specialized and consistent output.
*   **Layered Instructions:** Global instructions provide a baseline, but highly specific **Section/Stage Instructions** override them, enabling dynamic adaptation of the AI's role based on the task.
*   **Integrated Context ("Story Bible"):** Designed primarily for narrative projects (via Section D2), the framework facilitates the creation and consistent use of deep context (world rules, character profiles, plot points). Section **A6** provides tools for active context retrieval and management.
*   **Modular Design Potential:** Includes a [Modular Template] allowing YOU to create smaller, focused UPB modules for specific tasks or to manage AI context limits effectively. (See "Using Modularity" below).
*   **The "Forge" (Section H4):** Empowers YOU to become prompt architects yourself! Generate new custom prompts, analyze existing ones, get iterative refinement advice, and even structure entirely new UPB sections using AI assistance.
*   **Cross-Domain Integration:** Sections are cross-referenced conceptually and functionally, allowing for tasks like translating narrative (D) into game mechanics (J) or visualizing concepts (E).
*   **Code Execution Integration:** Leverages AI `tool_code` capabilities for calculations, data visualization (Matplotlib/Seaborn/Plotly/etc.), code generation/testing, and more, particularly within Section I.

## Getting Started

1.  **Download:** Obtain the primary `Unified Prompt Bible Forge - Expanded & Enhanced v1.0.2.html` file. For managing token limits, also download the `UPB Forge framework module template.html`.
2.  **Load Context:** Load the *entire content* of the chosen HTML file (either the full version or YOUR custom module) into your AI assistant's context window at the start of your session either through copying and pasting it, but much preferable is to upload the html file directly to the AI assistant. This is crucial for Guided Operation Mode. *Note: The full file is large and may exceed the context limits of some AI models.*
3.  **Interact using Prompt IDs:**
    *   Find the relevant **Prompt ID** (e.g., `A1.5b`, `G3.1`, `J2.4`) using the Table of Contents or Section L2 Index.
    *   Provide the ID to the AI, followed immediately by the necessary context or specific details for that prompt.
    *   Example: `A1.5b Apply '5 Whys' to the problem: 'Website checkout has high abandonment rate.'`
4.  **Interact using Natural Language:**
    *   You can also make requests in natural language. Per the **REVISED v3.1 Global Instructions**, the AI assistant attempts to semantically match your request to the function of a specific UPB prompt or section *within the loaded context*.
    *   It will inform you if it makes a match and adopts a specific persona.
    *   If your request is ambiguous or lacks context, it will use Step-Back logic to ask clarifying questions (potentially referencing A6 tools).
5.  **Tutorial:** For a guided introduction, start a session with the full UPB Forge loaded and use prompt `I3.2 Guided UPB Tutorial Introduction`. Or use the basic introduction prompts provided in section A0. 

## Structure Overview

The UPB Forge is organized into logical sections:

*   **A0:** User Guide & Tutorial (Start here!)
*   **A:** Foundational Skills (Critical Thinking, Creativity, Explanation, Text Refinement, Data Handling, Context Management.)
*   **B:** Reference Lists (Prompt Starters, Action Verbs)
*   **C:** Meta-Prompting & Reasoning Techniques (Frameworks, CoT, Structured Logic, Advanced PE)
*   **D:** Writing & Literature (General Craft D1, Full Book Writing Process D2)
*   **E:** Media Translation (Visual, Audio, Video Concepts)
*   **F:** Contextual Extrapolation (Expanding World, Culture, Character)
*   **G:** Special Systems Design (Magic, Tech, Psionics - Rules, Effects, Items, Impact)
*   **H:** Dynamic Prompt Generation & Adaptation (Meta-Prompting toolkit, including H4 'Forge')
*   **I:** Coding, Development & Education (Concepts, Code Gen/Debug, Learning)
*   **J:** Game Design Integration (Narrative-to-Game Concepts & Systems)
*   **L:** Reference (Glossary L1, Conceptual Index L2)

## Core Concepts

*   **Prompt ID:** A unique code (`A1.1`) invoking a specific function and persona.
*   **Guided Operation Mode:** AI operates using specific personas/processes defined by the loaded UPB section relevant to the Prompt ID.
*   **Section/Stage Instruction:** Defines the persona/process for a specific section (overrides Global).
*   **Story Bible (Conceptual):** The body of world, character, plot, and rule information developed collaboratively during a session, used for context and consistency.
*   **A0-M Prompts:** Tools (`A0-M.1`, `A0-M.2`, `A0.M-3`) to generate summaries or replicas of session metadata and established content for persistence.
*   **H4 Section (The Forge):** Allows users to generate/refine prompts and create new UPB sections.
*   **Modularity:** The ability (via template) to create smaller UPB subsets for specific tasks or limited context windows.

## Using Modularity

Due to the large size of the full UPB Forge, using the provided `UPB Forge framework module template` is recommended if your AI struggles with the full context:

1.  Open the template file.
2.  Copy the *entire* `<details>` block for the **Sections** you absolutely need from the *full* UPB Forge file (e.g., copy Section D2 if writing, Section J if game designing).
3.  Paste the copied section(s) into the corresponding placeholder location in the *template* file.
4.  **Crucially, always include the Quick Start Guide and the Global System Instructions (v3.1) in your module.** Including Sections A0, A6, H, L is also highly recommended for usability.
5.  Save your new modular file (e.g., `MyWritingModule.html`).
6.  Load *this smaller module* into your AI. The **Global System Instructions v3.1** are designed to handle this modularity correctly.

## Acknowledgements

The UPB Forge framework was developed collaboratively by **Zulthaxion** (providing the architectural vision, core concepts, iterative refinement, and implementation) and **Google's AI** (specifically leveraging models in the Gemini family for generating the detailed content, structuring prompts based on AI interaction principles, and acting as a collaborator/sparring partner during the design process).


## License

This project is licensed under the MIT License. 

---

Enjoy forging your ideas with the UPB Forge! We hope it enhances your creative and analytical collaborations with AI.
