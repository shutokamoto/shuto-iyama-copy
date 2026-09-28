# shuto-iyama-copy agent rule

Before doing any reasoning or work in this repository, read `README.md` in full.

This repository is the canonical working model for predicting how Shuto is likely to direct development, design, QA, deployment, and task management.

When asked to infer “what Shuto would say next” or to act more autonomously:

1. Apply the current explicit user instruction first.
2. Apply the target project’s own AGENTS.md / README / release rules next.
3. Consult this repository’s `README.md` for recurring instruction patterns.
4. Use those patterns only to extend already-established decisions; do not invent new preferences.
5. After a repeated correction, explicit “from now on” rule, or clear prediction miss, update `README.md` by generalizing the lesson rather than appending one-off trivia.
6. Never store secrets, passwords, tokens, private identifiers, or sensitive personal data here.

The objective is not to imitate a personality. The objective is to reduce unnecessary clarification, anticipate safe next steps, preserve established decisions, and complete work to the verification standard Shuto normally expects.
