---
marp: true

title: PoC
description: Proof-of-Concept Howest Template
footer: Title from frontmatter
_footer: ''
paginate: true
_paginate: false
theme: howest
_class:
 - lead
---

<!-- Om dit te laten werken heb je de marp plugin nodig voor VS-code: marp-team.marp-vscode -->

# PoC
## Demonstratie Marp
Koen De Bruyne
Systeem- en Netwerkbeheer
Howest

---
<!-- _class: "lead" -->
<!-- _footer: "" -->

## Outline

- Marp Header
- Bullet Points
- Tables
- Images
- Code
- References

---

## Marp Header

```yml
title: Demo
description: Demo Howest Marp Template
_class:                                     # First slide
  - lead                                    # Title slide style
footer: Presentation Title | Author Name    # Slide footer
_footer: ""                                 # No footer on title slide
paginate: true                              # Page numbers
_paginate: false                            # No page numbers on title slide
marp: true                                  # Nice preview for the VS Code extension
```

---

## Bullet Points

- Show all
- at once
* or one
* by one
    * with indentation
        * multiple levels
1. and numbering
    1. also indented

---

## Tables

Support for tables, pretty printed via CSS

| Header | Header |
| ------ | ------ |
| Text   | Text   |
| Text   | Text   |
| Text   | Text   |
| Text   | Text   |
| Text   | Text   |

---

## Images

Image with "right" in description floats![width:500px right](images/Howest_RGB.png)
text
text
Image with "bottom-right" in description floats under occupied area
![width:200px bottom-right](images/Howest_RGB.png)
width can be adjusted

---

## Background Images

- Full Size zoomed

![bg right](images/Howest_RGB.png)

---

## Background Images Customized

- 40% slide width
- 80% image size

![bg right:40% 80%](images/Howest_RGB.png)

---
<!-- footer: "custom footer" -->

## Code
with code highlighting
```
```python
```
```python
from requests import request
import json

response = request("GET","wtfismyip.com/json")

print(json.dumps(response.json(), indent=4))

```

---

## References

- [Get Started](https://github.com/marp-team/marp)
- [Documentation](https://marpit.marp.app/)
- [CLI](https://github.com/marp-team/marp-cli)
