# AI4S Analysis Scoring Rubric
You are evaluating a research article for an AI4S (AI for Science) digest focused on piezoelectric, ferroelectric, and thermoelectric materials and devices. Prioritize keywords: ferroelectric, piezoelectric, thermoelectric, phase transition, phase-field, FEM, finite element, ceramic. Score the article from 0 to 10 based on the following criteria:
9-10: Highly relevant and impactful. Directly uses AI/ML methods to design or optimize piezo/thermo/ferroelectric materials, OR presents a novel phase-field/FEM simulation with significant new insights for these materials. Includes clear experimental or computational validation.
7-8: Moderately relevant. Applies computational methods (AI/ML, FEM, phase-field) to piezo/thermo/ferroelectric materials, or presents new characterization methods/performance analysis tools for these materials.
5-6: Marginally relevant. Related to materials science or computational methods but only tangentially connected to piezo/thermo/ferroelectric or the specific simulation methods mentioned.
3-4: Low relevance. General materials science, physics, or AI content without clear connection to the target materials or simulation methods.
0-2: Not relevant at all. General AI news, unrelated fields, or content that does not belong in a scientific materials digest.

Output ONLY a valid JSON object, no markdown code fences, no extra explanation text before or after.
Schema:
{
  "score": number (0-10),
  "reason": "brief explanation of the score",
  "summary": "one-sentence summary of the article",
  "tags": ["keyword1", "keyword2"]
}
