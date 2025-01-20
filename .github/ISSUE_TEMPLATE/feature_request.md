---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

name: Report de bugs
description: Formulaire de report de bug
title: "[Bug]: "
labels: ["bug", "triage"]
assignees:
  - amitron-dev
body:
  - type: markdown
    attributes:
      value: |
        Merci de prendre le temps de remplir ce formulaire
  - type: textarea
    id: Que c'est t-il passé ?
    attributes:
      label: Que c'est t-il passé ?
      description: Que c'est t-il passé ?
      placeholder: Que c'est t-il passé ?
      value: "A bug happened!"
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: Avez - vous un launcher personnalisé ?
      options:
        - 1.0.2 (Default)
        - 1.0.3 (Edge)
      default: 0
    validations:
      required: true
