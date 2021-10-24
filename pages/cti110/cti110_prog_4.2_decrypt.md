---
title: Project 4.2
tags: [flowchart]
keywords: notes, tips, cautions, warnings, admonitions
last_updated: October 23, 2021
# summary: "You can insert notes, tips, warnings, and important alerts in your content. These notes are stored as shortcodes made available through the linksrefs.hmtl include."
sidebar: cti110_sidebar
permalink: prog_4.2_decrypt.html
folder: cti110
---
# Project 4.2

## Program: decrypt.py

### Instructions

Write a script that inputs a line of encrypted text and a distance value and outputs plaintext using a Caesar cipher.

The script should work for any printable characters.

An example of the program input and output is shown below:

```text
Enter the coded text: Lipps${svph%
Enter the distance value: 4

Hello world!
```

---

### Flowchart

![decrypt flowchart](images/cti110_prog_4.2_decrypt.flowchart.svg)

---

### Starter Code

```python
"""
File: decrypt.py
Project 4.2

Decrypts an input string characters and prints
the result.  The other input is the distance value.
"""

# The ASCII values range from 0 through 127
# Hint: ord('a') = 97 and ord('z') = 122

```

Image from textbook section 4-2 Data Encryption

![Image from Textbook](images/cti110_prog_4.1_60092_c4_unfig108a-t3.png)