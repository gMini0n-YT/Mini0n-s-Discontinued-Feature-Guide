---
name: Illegal/Unobtainable Submission.yml
about: Describe this issue template's purpose here.
title: Illegal/Unobtainable Submission.yml
labels: ''
assignees: ''

---

name: Discontinued Feature Submission
description: Submit a new discontinued feature.
labels: ["enhancement"]

body:
  - type: textarea
    attributes:
      label: Media
      description: Provide screenshots or videos showcasing the discontinued feature (optional).
  
  - type: textarea
    attributes:
      label: What is the discontinued feature?
      description: Provide a detailed explanation of the discontinued feature.
    validations:
      required: true
  
  - type: textarea
    attributes:
      label: How to obtain this feature?
      description: Provide detailed steps on how to obtain this discontinued feature in the game.
    validations:
      required: true
  
  - type: dropdown
    attributes:
      label: Game Edition
      description: Select the Minecraft edition this discontinued feature applies to.
      options:
        - Bedrock
        - Java
        - Legacy Console Edition (Xbox 360)
    validations:
      required: true
  
  - type: input
    attributes:
      label: Minecraft Version
      description: Specify the Minecraft version where this discontinued feature can be obtained (e.g., 1.17, TU31).
    validations:
      required: true
