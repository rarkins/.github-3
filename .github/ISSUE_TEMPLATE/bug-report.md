name: Bug Report
description: Create a bug report to help us improve.
body:
  - type: markdown
    attributes:
      value: >
        **THIS IS NOT THE PLACE TO ASK FOR SUPPORT!**
        Please use [Discord](https://retroarcher.github.io/discord) for support issues.
  - type: textarea
    id: description
    attributes:
      label: Describe the Bug
      description: A clear and concise description of the bug.
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: A clear and concise description of what you expected to happen.
  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Add any other context about the bug here.
  - type: markdown
    attributes:
      value: |
        Make sure to close your issue when it's solved! If you found the solution yourself please comment so that others benefit from it.