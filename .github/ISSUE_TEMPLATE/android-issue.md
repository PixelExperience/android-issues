body:
- attributes:
    value: 'What not to report:

      - Bugs in unofficial builds or anything not downloaded from our [Official Website](https://get.pixelexperience.org/)

      - Missing Builds

      - Problems with the website

      - Feature requests


      Make sure not to use extra mods when reporting a problem (for example: Magisk)

      If you need help please check our Telegram group at https://t.me/pixelexperiencechat

      '
  type: markdown
- attributes:
    description: 'Anything that can help us identify the build you are using

      Example: ```PixelExperience_raphael-10.0-20201218-0409-OFFICIAL```

      '
    label: Build Date
  type: input
  validations:
    required: true
- attributes:
    label: Device
    multiple: false
    options:
    - Select one
    - redfin
  type: dropdown
  validations:
    required: true
- attributes:
    label: Version
    multiple: false
    options:
    - Select one
    - thirteen
    - thirteen_plus
  type: dropdown
  validations:
    required: true
- attributes:
    description: A clear and concise description of what the bug is.
    label: Describe the Bug
  type: textarea
  validations:
    required: true
- attributes:
    description: Steps to reproduce the behavior, please provide a clear description
      of how to reproduce the issue, based on the linked minimal reproduction. Screenshots
      can be provided in the issue body below. If using code blocks, make sure that
      [syntax highlighting is correct](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks#syntax-highlighting)
      and double check that the rendered preview is not broken.
    label: Steps to Reproduce
  type: textarea
  validations:
    required: true
- attributes:
    description: A clear and concise description of what you expected to happen.
    label: Expected Behavior
  type: textarea
  validations:
    required: true
- attributes:
    description: Not obligatory, but suggest a fix/reason for the bug
    label: Possible Solution
  type: textarea
  validations:
    required: false
- attributes:
    value: Before posting the issue go through the steps you've written down to make
      sure the steps provided are detailed and clear.
  type: markdown
description: Create a bug report for the PixelExperience team
labels:
- 'template: bug'
name: Bug Report
