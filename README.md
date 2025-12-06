# CISC101-Group110-PaperSummarizer

Module 1: Intake & setup
Normalize sections: Map synonyms to canonical names (e.g., “Background” → “Introduction”), preserve order.

Detect issues: Identify missing, empty, and <50-word sections; add to Checks & Warnings.

Audience profile: Load vocabulary and explanation depth tailored to the selected audience.

Module 2: Section loop
Process each section in order: Extract text → summarize (≤150 words) → apply constraints.

Grounding: Use phrasing that ties back to the provided text; no external facts.

Status flags: Attach issues to each section entry (e.g., “Short,” “Empty,” “Chunked”).

Module 3: Guardrails
Missing/empty sections: Explicitly list and mark.

<50-word sections: Warn; produce minimal summaries acknowledging insufficiency.

Hallucination mitigation: Cross-check language for inferred claims; prefer conservative wording.

Long-paper chunking: Split long sections into coherent chunks; summarize per chunk; merge conservatively.

Module 4: Rendering & refinement
Structure: Compose all required outputs with consistent headings and tables.

Formatting: Enforce bold lead-in labels in bullets; LaTeX for math; short paragraphs.

Audience variants: Produce expert and lay summaries with appropriate vocabulary and assumptions.

Module 5: Citation extractor (student-created)
Extract mentions: Collect in-text citation markers; map to references.

Highlight key works: List up to 5 most frequently cited or central references; do not invent metadata.

Flag gaps: Note unmapped or incomplete citations.

Module 6: Equation explainer (student-created)
Detect equations: Identify formulas/symbols; render in LaTeX.

Explain variables: Provide meanings and units; outline equation role in the paper.
