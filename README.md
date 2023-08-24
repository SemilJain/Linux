# Linux Assignments

This repository contains a set of Linux assignments that I completed. These assignments cover various Linux commands and operations. Below, you'll find details on each assignment along with the respective input files.

## Assignment 1 - Search and Count
- **Input File:** `input1.txt`

This assignment involves searching for a specific word ("the") in the `input1.txt` file and counting the occurrences.

```bash
echo "Lines containing Entered word:" && grep -n " the " input1.txt && echo "No. of specified word: " && grep -o '\<the\>' input1.txt | wc -l
```
