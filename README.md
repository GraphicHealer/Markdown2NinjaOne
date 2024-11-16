# Markdown2NinjaOne
Convert Markdown Content to NinjaOne's Source Format for Documentation.

View it Here: https://graphichealer.github.io/Markdown2NinjaOne/

Here are the resources I used to build this HTML page:
- This editor was a GODSEND. It sped up my testing by ALOT: https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic
- Mozilla's MDN is AWESOME: https://developer.mozilla.org/en-US/docs/Web
- Icons I used: https://phosphoricons.com/
- The Markdown Parser I used: https://github.com/markdown-it/markdown-it
  - THIS is what is doing ALL the grunt work. READ THE DOCS. That is how you adapt normal Markdown to Ninja's ANNOYING HTML Layout.

## Markdown Support Progress
- [X] General Paragraphs
- [X] Lists (ordered & unordered)
- [X] Strong/bold
- [X] Headers (Limited to 4, as NinjaOne only goes that far)
- [X] Breaks (`<br />`)
- [X] Horizontal Rules
- [X] Inline HTML
- [X] Underline (Converts `<ins>` to `<u>`)
- [ ] Quoteblocks
- [ ] Italics
- [ ] URL Links
- [ ] Images
- [ ] Inline Code
- [ ] Strikethrough
- [ ] Subtext
- [ ] Supertext
- [ ] Tables
- [ ] Code Blocks (These are currently broken in NinjaOne's Editor)

As you can see, this is still a work in progress. The list above is pretty much everything markdown related that NinjaOne's editor supports.

# Contributing
If you are a NinjaOne user, and you know some JavaScript, You are welcome to help out!
Just submit a Pull Request!
