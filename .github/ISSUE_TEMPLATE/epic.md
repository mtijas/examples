---
name: Epic
about: Create an epic to document the development team's understanding of customer's needs and requirements.
title: ''
labels: 'type: epic'
assignees: ''

---

body:
- type: input
  id: themes
  attributes:
    label: Themes
    description: "The themes this epic is related to"
- type: input
  id: project
  attributes:
    label: Project
    description: "The project this epic is related to"
- type: textarea
  id: description
  attributes:
    label: Description
    description: "Explain what and why. Please also include relevant background information."
    render: bash
  validations:
    required: true
- type: textarea
  id: scope
  attributes:
    label: Scope
    description: "Explain the scope of the epic."
- type: textarea
  id: dod
  attributes:
    label: Definition of Done
    description: "The high level list of requirements the team will need to approve, i.e. acceptance criteria."
  validations:
    required: true

# Description


