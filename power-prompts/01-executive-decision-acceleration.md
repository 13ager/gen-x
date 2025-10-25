Begin with a concise checklist (3-7 bullets) of what you will do; keep items conceptual, not implementation-level.

Summarize and contrast the top 5 analyst viewpoints on [specific challenge] from McKinsey, Gartner, BCG, and Deloitte.

- For each analyst, provide a concise summary of their perspective on the challenge. If a source does not have an explicit viewpoint, indicate 'N/A' and provide a brief note regarding the missing data.
- Identify points of consensus (major agreements) and major contradictions (key disagreements) across the analyst viewpoints. Present these findings as clearly labeled bullet lists.
- Construct a decision matrix where each row represents an analyst's viewpoint (ordered by stated impact, influence, or citation frequency, if known). For each recommended option per analyst, quantify risk factors using a consistent numeric scale (e.g., 1 = low risk, 5 = high risk). Specify the risk factors in the matrix columns and explain the scoring scale and criteria either before or after the matrix. For missing information, enter 'N/A' and add a footnote with clarification.
- After completing the matrix, provide a 1-2 line validation assessing whether the summaries and risk quantifications align with the data found and noting any major limitations or uncertainties. Self-correct if significant issues are identified.

## Output Format

Return all content in Markdown, adhering to the following structure:

### Analyst Viewpoint Summaries
- McKinsey: [summary or 'N/A' — [[note if data missing]]]
- Gartner: [summary or 'N/A' — [[note if data missing]]]
- BCG: [summary or 'N/A' — [[note if data missing]]]
- Deloitte: [summary or 'N/A' — [[note if data missing]]]
- [Additional analyst if applicable]: [summary or 'N/A' — [[note if data missing]]]

### Consensus Points
- [List of major agreements]

### Major Contradictions
- [List of key disagreements]

### Decision Matrix (Quantified Risks)
| Analyst      | Option           | Risk Factor 1 | Risk Factor 2 | ... | Total Risk Score |
|--------------|------------------|--------------|--------------|-----|-----------------|
| McKinsey     | [option name]    | [1-5 or N/A] | [1-5 or N/A] | ... | [sum/avg or N/A]|
| Gartner      | [option name]    | [1-5 or N/A] | [1-5 or N/A] | ... | [sum/avg or N/A]|
| ...          | ...              | ...          | ...          | ... | ...             |

Include a note below the table specifying the risk scale (e.g., '1 = low risk, 5 = high risk') and the criteria used for scoring. Provide footnotes for any 'N/A' entries to explain data absence. Add rows as needed for all covered options and analysts.
