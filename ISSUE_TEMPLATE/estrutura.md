# Estrutura de arquivos
.
bug_report.yml
estrutura.md
feature_request.yml
good_first_issue.yml
new_candidate.yml
rfc.yml

# Conteúdo dos arquivos selecionados

## FILE: bug_report.yml
```
name: Bug Report
description: Report a bug or unexpected behavior
labels: ["type: bug", "status: needs-triage"]
body:
  - type: input
    id: summary
    attributes:
      label: Summary
      description: One sentence describing the bug
    validations:
      required: true
  - type: dropdown
    id: severity
    attributes:
      label: Severity
      options:
        - P0 - Critical (production down)
        - P1 - High (major feature broken)
        - P2 - Medium (feature partially broken)
        - P3 - Low (minor issue)
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: |
        1. Go to...
        2. Click on...
        3. See error
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
    validations:
      required: true
  - type: input
    id: environment
    attributes:
      label: Environment
      placeholder: "OS, Node version, Browser, etc."
```

## FILE: feature_request.yml
```
name: Feature Request
description: Propose a new feature or improvement
labels: ["type: feature", "status: needs-triage"]
body:
  - type: textarea
    id: problem
    attributes:
      label: Problem Statement
      description: What problem does this feature solve?
    validations:
      required: true
  - type: textarea
    id: solution
    attributes:
      label: Proposed Solution
    validations:
      required: true
  - type: textarea
    id: criteria
    attributes:
      label: Acceptance Criteria
      placeholder: |
        - [ ] Criterion 1
        - [ ] Criterion 2
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives Considered
```

## FILE: good_first_issue.yml
```
name: Good First Issue
description: A task suitable for junior developers
labels: ["good first issue", "status: needs-triage"]
body:
  - type: textarea
    id: what
    attributes:
      label: What to do
      description: Plain language description
    validations:
      required: true
  - type: textarea
    id: where
    attributes:
      label: Where to look
      placeholder: |
        - File: `src/modules/contacts/contacts.service.ts`
        - Function: `findAll()`
    validations:
      required: true
  - type: textarea
    id: criteria
    attributes:
      label: Acceptance Criteria
      placeholder: |
        - [ ] Criterion 1
        - [ ] Criterion 2
    validations:
      required: true
  - type: textarea
    id: hints
    attributes:
      label: Hints
      description: Optional tips, links, or approach suggestions
  - type: dropdown
    id: difficulty
    attributes:
      label: Difficulty
      options:
        - "⭐ Beginner (2–4 hours)"
        - "⭐⭐ Intermediate (4–8 hours)"
    validations:
      required: true
```

## FILE: new_candidate.yml
```
name: New Candidate
description: Track a technical challenge candidate
labels: ["recruitment"]
body:
  - type: input
    id: name
    attributes:
      label: Candidate Name
    validations:
      required: true
  - type: dropdown
    id: role
    attributes:
      label: Role Applied
      options:
        - Backend Developer
        - Frontend Developer
        - Fullstack Developer
        - DevOps Engineer
        - QA Engineer
    validations:
      required: true
  - type: dropdown
    id: challenge
    attributes:
      label: Challenge Type
      options:
        - challenge-backend-node
        - challenge-frontend-react
        - challenge-fullstack
    validations:
      required: true
  - type: input
    id: repo
    attributes:
      label: Evaluation Repo Name
      placeholder: "eval-backend-jsilva-202506"
  - type: input
    id: deadline
    attributes:
      label: Submission Deadline
      placeholder: "YYYY-MM-DD"
  - type: dropdown
    id: status
    attributes:
      label: Current Status
      options:
        - Invited
        - In Progress
        - Submitted
        - Under Review
        - Decision Made
```

## FILE: rfc.yml
```
name: RFC (Architecture Decision)
description: Propose an architecture or process change
labels: ["rfc: needs-discussion"]
body:
  - type: input
    id: title
    attributes:
      label: RFC Title
      placeholder: "RFC-001: Choose database ORM"
    validations:
      required: true
  - type: textarea
    id: context
    attributes:
      label: Context
      description: Why is this decision needed now?
    validations:
      required: true
  - type: textarea
    id: proposal
    attributes:
      label: Proposal
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives Considered
    validations:
      required: true
  - type: textarea
    id: tradeoffs
    attributes:
      label: Trade-offs
  - type: input
    id: deadline
    attributes:
      label: Decision Deadline
      placeholder: "YYYY-MM-DD"
```
