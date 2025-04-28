---
name: 'PROGRAMER NASEEM '
about: " NAME   NASEEM MOHAMMED    ADDRESS   KUDAKALLI ROAD PASARADICHANAI POTTUVIL-18
  \   DISTRICT   AMPARA    PHONE NO 0729120202  0724495042  "
title: ''
labels: ''
assignees: ''

---

name: Website Issue Report
description: Report any bugs or issues found on the Software Engineering Website.
title: "[BUG]: "
labels: [bug]
assignees: MOHAMMED-NASEEM

body:
  - type: markdown
    attributes:
      value: |
        ## Hi Mohammed Naseem,
        Please fill out the following details carefully to help us fix the issue faster!

  - type: input
    id: reporter_name
    attributes:
      label: Your Name
      description: Confirm your name (default is MOHAMMED NASEEM).
      placeholder: "MOHAMMED NASEEM"
    validations:
      required: true

  - type: textarea
    id: problem_description
    attributes:
      label: Problem Description
      description: Clearly describe the issue you are facing.
      placeholder: Describe the issue here...
    validations:
      required: true

  - type: textarea
    id: steps_to_reproduce
    attributes:
      label: Steps to Reproduce
      description: List the steps needed to reproduce the issue.
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. Scroll down to '...'
        4. See error
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: Expected Behavior
      description: What you expected to happen.
      placeholder: Expected outcome...
    validations:
      required: true

  - type: textarea
    id: actual_behavior
    attributes:
      label: Actual Behavior
      description: What actually happened.
      placeholder: Actual result...
    validations:
      required: true

  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots (Optional)
      description: Upload screenshots if available.
      placeholder: Drag and drop images here.

  - type: input
    id: environment_details
    attributes:
      label: Environment Details
      description: Device, OS, Browser, etc.
      placeholder: Example - Windows 11, Chrome 122

  - type: textarea
    id: additional_info
    attributes:
      label: Additional Information
      description: Any extra information about the issue.
