# AutoBot Bounty Template

Use this template when creating new bounty issues for the AutoBot project.

## Template

```markdown
## Description
A clear and concise description of the feature or improvement being requested.

## Problem Statement
Why is this needed? What gap does it address in AutoBot?

## Acceptance Criteria
How will we know when this is complete? Include specific requirements:

- [ ] Criterion 1
- [ ] Criterion 2
- [ ] Criterion 3

## Proposed Solution
Describe the suggested implementation approach (if applicable).

## Implementation Details

### Difficulty Level
- [ ] Good for first-time contributors (`good-first-issue`)
- [ ] Intermediate level (`intermediate`)
- [ ] Advanced level (`advanced`)

### Bounty Information
**Reward Amount:** $XXX (to be confirmed by maintainers via Polar.sh)

**Expected Effort:** Roughly _X_ days of work (adjust for your skill level)

**PR Target Branch:** `Dev_new_gui` (not `main`)

### Scope
What's included in this bounty (and what's not):
- Include: [specific features/tasks]
- Exclude: [things explicitly out of scope]

## Requirements for Contributors

Before claiming this bounty, please confirm you can:

- [ ] Follow [CONTRIBUTORS.md](CONTRIBUTORS.md) guidelines
- [ ] Write tests for your implementation
- [ ] Maintain or improve code coverage
- [ ] Document your changes (docstrings, README updates if needed)
- [ ] Follow AutoBot's code style and linting standards
- [ ] Target the `Dev_new_gui` branch (not `main`)

## Resources

- **Documentation:** [Link to relevant docs]
- **Related Issues:** #XXX, #YYY
- **Stack Used:** [List relevant technologies: FastAPI, Vue.js, PostgreSQL, etc.]

## Payment & Timeline

This bounty is managed via [Polar.sh](https://polar.sh/mrveiss/AutoBot-AI). Once your PR is merged:

1. Bounty payment is locked in
2. Payment processing begins (typically 7 days)
3. You receive payment in your preferred currency/method

**Claiming:** Comment below or on the associated discussion to claim this bounty.

---

**Questions?** See [BOUNTY.md](BOUNTY.md) for the full bounty program guide.
```

## Usage Instructions

1. Copy the template above when creating a new bounty issue
2. Fill in all sections with specific details
3. Set appropriate difficulty level and reward amount
4. Add relevant labels: `bounty`, difficulty level, and technology tags
5. Ensure all requirements are clearly defined
6. Link to relevant documentation and related issues

## Guidelines

- **Be Specific**: Clear acceptance criteria prevent scope creep
- **Set Realistic Rewards**: Match complexity and time investment
- **Target Correct Branch**: Always use `Dev_new_gui` unless specified otherwise
- **Include Resources**: Help contributors get started quickly
- **Define Scope**: Clearly state what's included and excluded

## Example Labels

- `bounty`
- `good-first-issue` / `intermediate` / `advanced`
- `frontend` / `backend` / `ai-ml` / `devops`
- `documentation` / `testing` / `refactoring`
- Technology-specific: `fastapi`, `vue`, `postgresql`, `docker`, etc.
