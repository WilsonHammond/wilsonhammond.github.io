# AI Incident Response Playbook

## Example triggers
Sensitive-data disclosure; prompt injection; harmful or discriminatory output; materially incorrect output used in a consequential decision; unreviewed vendor/model change; unauthorized AI use; loss of logging; system behavior outside approved purpose; or material increases in complaints/error rate.

## Response phases
1. **Detect and report** the use case, system, time, affected users, observed behavior, evidence source, and reporter.
2. **Triage** severity, data sensitivity, stakeholder impact, legal/regulatory implications, dependency, and whether continued use is safe.
3. **Contain** by disabling features, restricting access, blocking patterns, removing data sources, reverting versions, pausing automated decisions, or switching to manual processes.
4. **Preserve evidence** including prompts, outputs, logs, model/version information, access records, configuration, vendor notices, affected data, and decision history.
5. **Analyze root cause** across data, access, prompt injection, model behavior, testing, human oversight, vendor change, documentation, configuration, and policy.
6. **Correct and validate** controls and document residual risk.
7. **Reauthorize** medium- and high-risk systems after designated approval.
8. **Learn** by updating the risk register, model card, tests, policy, training, vendor requirements, and monitoring thresholds.
