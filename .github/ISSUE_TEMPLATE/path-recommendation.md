name: 📌 Path Update
description: Request for a path to updated
title: "[PATHUPDATE]: "
labels: ["PathUpdate"]
assignees: ["ShepardCodes"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this Path Update Recommendation.
        Please make sure to review our "Code of Conduct" prior to submitting a Path Update Issue.
        
  - type: textarea
    id: path-description
    attributes:
      label: Describe the Path Update Recommendation
      description: Give us a brief description of what changes you would like to see when the path is updated.
    validations:
      required: true

  - type: textarea
    id: additional-information
    attributes:
      label: Additional Information
      description: |
        Provide any additional information such as screenshots or graphics for what the path should be changed to.