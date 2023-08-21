# MARP Template for Howest

> This is a work in progress

## How to use this template

### 1. Install the MARP extension for VS Code

### 2. Create a markdown file with marp header

```yaml
---
marp: true

title: File title
description: Slide deck
footer: Footer text
_footer: ''
paginate: true
_paginate: false
theme: howest
_class:
 - lead
---
```

### 3. Add the following to your `.vscode/settings.json`

`"markdown.marp.themes": ["https://raw.githubusercontent.com/Howest-SNWB/marp-template/main/themes/howest.css"]`

### 4. Click the `Preview to the side` button to view the result

You can export to Powerpoint (non-editable), PDF and HTML with presentation note.

## Issues and Improvements

Found an issue? Made an improvement?

We are open to pull requests.

1. Fork this repo
2. Install the MARP extension

All markup in `./themes/howest.css`.
Original images in `./images/`

## Contributions and thanks

The Marp Team: [github](https://github.com/marp-team/marp) [official site](https://marp.app/)

Template loosely based on [TUM Marp Template](https://github.com/hofbi/tum-marp-template)
