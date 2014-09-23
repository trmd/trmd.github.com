# Pandoc clipboard conversion (LaTeX to Markdown and vice versa)

1. Copy Latex code to the clipboard
2. In a terminal: ```pbpaste | pandoc -f latex -t markdown | pbcopy```
3. Paste Markdown text

To go the other way use: ```pbpaste | pandoc -f markdown -t latex | pbcopy```


(This should be converted into a service or something one-click. Above my head for now)

---

2014-09-23