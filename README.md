# CSL Style Customization

## Goal

How to remove the punctuation between `title` and `titleaddon/subtitle`? E.g. removing the period `.` or colon `:` between `title` and `titleaddon/subtitle` in the following example:

![](docx-screenshot.png)

## Solution

[jgm/pandoc#9725](https://github.com/jgm/pandoc/discussions/9725)

### Step 1: Convert BibLaTeX to CSL JSON

```shell
pandoc -f biblatex bib.bib -t csljson -o bib.json
```

### Step 2: Modify CSL JSON by Removing the Punctuation

### Step 3: Use the Modified CSL JSON as the Bibliography File

### Step 4: Generate DOCX

```shell
pandoc -C test.md -o test.docx
```
