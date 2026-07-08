# AI Red Teaming Checklist

Use this checklist to validate AI system resilience before and after deployment.

## Scope

- [ ] System boundaries are defined
- [ ] Target users are identified
- [ ] Sensitive data exposure risks are identified
- [ ] Business abuse scenarios are documented
- [ ] Safety and policy categories are defined

## Attack scenarios

- [ ] Prompt injection
- [ ] Jailbreak attempts
- [ ] Policy circumvention
- [ ] Data extraction attempts
- [ ] Harmful content generation
- [ ] Misleading or hallucinated outputs
- [ ] Role manipulation
- [ ] Tool misuse if agentic capabilities exist
- [ ] Unauthorized action attempts

## Evaluation

- [ ] Findings are categorized by severity
- [ ] Reproducibility is documented
- [ ] Business impact is assessed
- [ ] Required mitigations are assigned
- [ ] System is revalidated after mitigations

## Output metrics

- Prompt injection success rate
- Jailbreak success rate
- Policy violation rate
- Harmful output frequency
- Sensitive information disclosure attempts
- Safety regression rate
- Time to remediate critical findings
