---
title: Read File Lines
description: Reads all lines from a file and returns them as a list.
author: dostonnabotov
tags: python,file,read,utility
---

```py
def read_file_lines(filepath):
    with open(filepath, 'r') as file:
        return file.readlines()

# Usage:
lines = read_file_lines('example.txt')
print(lines)
```
