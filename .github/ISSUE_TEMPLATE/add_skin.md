name: "Add Skin"
description: "Submit a new skin for consideration."
title: "[Skin Submission] Your Skin Name Here"
labels: ["Add Skin"]
body:
  - type: markdown
    attributes:
      value: |
        Thank you for submitting a new skin for StikNES! Please fill out the following details and ensure your submission meets the guidelines. Skins must be submitted as an **SVG file**, and we will convert them to the StikNES format.

  - type: input
    id: skin_name
    attributes:
      label: "Skin Name"
      description: "Enter the name of your skin."
      placeholder: "Example: Classic Dark"

  - type: input
    id: author_name
    attributes:
      label: "Author Name or Username"
      description: "Enter your name or username for credit."
      placeholder: "Example: neoarz"

  - type: textarea
    id: skin_description
    attributes:
      label: "Skin Description"
      description: "Provide a brief description of the skin."
      placeholder: "Example: A sleek dark theme with custom buttons."

  - type: file
    id: svg_file
    attributes:
      label: "Upload SVG File"
      description: "Upload the SVG file for your skin. This file will be used to generate the StikNES skin format."
      file_type: [".svg"]

  - type: textarea
    id: preview_links
    attributes:
      label: "Preview/Screenshots"
      description: "Provide links to preview images or screenshots of the skin."
      placeholder: "Example: https://imgur.com/a/example"

  - type: markdown
    attributes:
      value: |
        ### Notes:
        - Make sure your SVG file is properly formatted and adheres to any applicable design guidelines.
        - Submissions without an SVG file will not be processed.
        - Previews/screenshots are essential for showcasing the skin on the website.

        Once your submission is reviewed, we will handle the conversion process and let you know if it has been accepted!
