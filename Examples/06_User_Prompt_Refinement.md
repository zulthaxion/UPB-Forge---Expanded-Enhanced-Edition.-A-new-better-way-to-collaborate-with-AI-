# Example 6: User Prompt Draft Refinement (H4.0r)

This example demonstrates using Section H4 to get feedback on a user's own drafted prompt before running it.

## Goal

Get feedback and refinement suggestions on a vaguely worded prompt intended to generate worldbuilding details.

## UPB Prompt Used

```
H4.0r [Draft Prompt: "Tell me about the Sunken City Merfolk culture. Make it cool."]
```

## Hypothetical AI Output (Illustrative)

**(Persona: Prompt Architect, AI Interaction Designer & Iterative Refinement Coach)**

Okay, analyzing your draft prompt: `"Tell me about the Sunken City Merfolk culture. Make it cool."`

**Analysis & Feedback:**

*   **Strengths:** Clearly identifies the subject (Sunken City Merfolk culture).
*   **Weaknesses:**
    *   **Vagueness (Clarity/Specificity H3.1/H3.3):** "Tell me about" is very broad. What specific aspects of culture are you interested in (e.g., values, government, customs, art)?
    *   **Subjectivity (Actionability H3.6):** "Make it cool" is subjective and non-actionable. What constitutes "cool" for this culture? (e.g., Unique technology? Dangerous traditions? Intriguing visuals?) The AI has to guess your definition.
    *   **Missing Context (Completeness H3.5):** The prompt doesn't provide any grounding context (like environment, history, core values from S2) which is crucial for generating *specific* and *consistent* cultural details rather than generic fantasy tropes.

**Suggestions for Refinement:**

1.  **Use a Specific UPB Prompt:** For generating core cultural details, `D2-S2.4` (Cultural Development) is ideal. It asks for specific inputs (Culture Name, Location, Values, History, Environment) and outputs structured details (Core Value, Custom, Norm, Politics).
2.  **Specify Aspects:** If not using D2-S2.4, be more specific about *what* aspects of culture you want. Instead of "Tell me about," try "Describe their typical family structure," "Explain their primary religious belief," or "Generate concepts for their unique artistic style (ref D2-S2.30)."
3.  **Define "Cool" Actionably:** Replace "Make it cool" with concrete instructions reflecting what you mean. Examples:
    *   "Focus on generating unique details related to their deep-sea trench environment (S2.6)."
    *   "Ensure the details reflect their history of surviving a cataclysm (S2.5)."
    *   "Incorporate elements of bioluminescence (F1) into their customs or technology."
4.  **Provide Context:** *Crucially*, include relevant context from your Story Bible (S2 or F2 notes) directly in the prompt (ref C5.10).

**Example Refined Prompt (Using D2-S2.4):**
`D2-S2.4 Culture Name: Sunken City Merfolk Location: Deep ocean trenches (dark, high pressure, reliant on geothermal vents G1.4 & bioluminescence F1). History: Survived a surface cataclysm centuries ago, value preservation of knowledge (S2.5). Define Core Value, Significant Custom, Social Norm regarding [Topic], and Political Structure.`

This refined version provides clear structure, specific context, and actionable goals, leading to a much more useful and relevant output.

## Explanation & Takeaway

This demonstrates `H4.0r` acting as a prompt "debugger." By analyzing the user's vague draft, it identifies specific weaknesses (vagueness, subjectivity, missing context) and provides concrete, actionable suggestions for improvement, often pointing towards relevant UPB structures (like D2-S2.4) or principles (providing context), empowering the user to create better prompts.