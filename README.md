# Markdown2NinjaOne
Convert Markdown Content to NinjaOne's Source Format for Documentation.

## How to Use
View it Here: https://graphichealer.github.io/Markdown2NinjaOne/
1. Paste or Write Markdown in the Left Textbox
2. Click the Copy button on the upper-right of the Right Textbox.
3. Open NinjaOne and go to the `Knowledge Base`.
4. Click `Add > New Document`.
5. On the new doc page, click `Source`, select all (`ctrl+a`), then Paste the copied HTML in.
   ![image](https://github.com/user-attachments/assets/1be86f0a-f38f-4274-abdc-e0ebdfd24c19)
6. Click `Source` again, then hit `Save`.

**If you have any images in your markdown, this converter will replace them with black and yellow text.<br />NinjaOne requires a direct upload, and won't support embedded images in Source.<br />Just replace these blocks of text with the images referenced.**

## Page Design
Here are the resources I used to build this HTML page:
- This editor was a GODSEND. It sped up my testing by ALOT: https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic
- Mozilla's MDN is AWESOME: https://developer.mozilla.org/en-US/docs/Web
- Icons I used: https://phosphoricons.com/
- Syntax Highlighting: https://github.com/highlightjs/highlight.js
- The Markdown Parser I used: https://github.com/markdown-it/markdown-it
  - THIS is what is doing ALL the grunt work. READ THE DOCS. That is how you adapt normal Markdown to Ninja's ANNOYING HTML Layout.

## Markdown Support Progress
This converter works with pretty much everything markdown related that NinjaOne's editor supports, with the following exceptions:
- **Images, because of a limitation of the Editor Itself**

# Contributing
If you are a NinjaOne user, and you know some JavaScript, You are welcome to help out!
Just submit a Pull Request!
