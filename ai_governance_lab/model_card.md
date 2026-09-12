# Model / System Card: Enterprise Knowledge Assistant

## System ID
AI-007

## Purpose
Provide retrieval-assisted summaries and answers from approved internal policy and procedure content.

## Intended users
Employees and approved contractors with authenticated enterprise accounts.

## Prohibited uses
- Final legal interpretation
- Independent employment decisions
- Final security authorization decisions
- Processing secrets or data outside approved repositories
- Circumventing source access permissions

## Primary risks
Prompt injection, retrieval poisoning, restricted-content disclosure, confabulation, over-reliance, incomplete traceability, and vendor/model change.

## Required controls
Single sign-on, role-based access, retrieval permission enforcement, adversarial prompt testing, source attribution where feasible, centralized logging, user notice, escalation path, and material-change review.

## Monitoring
Monthly sample review, prompt-injection testing after material changes, restricted-content exposure testing, complaint tracking, accuracy/source-citation sampling, and access-control review.

## Reauthorization triggers
New data source, new or materially changed model, expanded user population, changed decision impact, new external access, material security incident, or repeated quality/privacy failure.
