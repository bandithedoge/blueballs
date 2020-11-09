![blueballs](blueballs.png)

**blueballs** is a color scheme inspired by [Nord](https://www.nordtheme.com/) and [Dracula](https://www.nordtheme.com/). It's mostly intended for terminals and text editors but porting it everywhere possible is encouraged.

# Colors

![colors](colors.png)

The colors should be relatively self-explanatory but here are some notes for porting:

* **bg** is the main background color of your document/terminal and **bg dark** is a secondary background color used for additional UI elements such as headers and status bars.
* **selection** is the background of selected text.
* **comment** is used for comments in text files but can also be used as a secondary foreground color for disabled elements.
* **fg** is the main foreground.
* **accent** is the accent color used for currently relevant UI elements. Use of this color can be very subjective.
* Other colors should only be used for syntax highlighting and specifically colored UI elements. "Cyan" is actually orange but we keep the original name terminals use.

When in doubt, use [blueballs.vim](https://github.com/bandithedoge/blueballs.vim) for reference. **Please do not change the colors** unless it's absolutely required and justified.

# [List of available ports](ports.org)
