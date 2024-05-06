# CSL Style Customization

## Goal

How to Remove the Punctuation Between `title` and `titleaddon/subtitle`? E.g. removing the period `.` or colon `:` between `title` and `titleaddon/subtitle` in the following example:

![](docx-screenshot.png)

## Command

```shell
pandoc -C test.md -o test.docx
```

# Discussion

[jgm/pandoc#9725](https://github.com/jgm/pandoc/discussions/9725)
