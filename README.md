# Screening materials

Keywords and prompts used to screen Reddit records for a study of how deaf and hard-of-hearing (DHH) people use communication tools with hearing people. No Reddit text is included.

1. `1_keywords.txt`: a post (title and body) or comment (body) containing any keyword moved to the next step; matching ignored case. Lines 53–102 are regular expressions.
2. `2_initial_screening_prompt.txt`: used with Claude Opus 5.5; records labelled A moved to the next step.
3. `3_fine_screening_prompt.txt`: used separately with GPT-6 and Claude Opus 5.5; a record was kept only when both returned `keep`.

Operational instructions (file handling, output format) are omitted.
