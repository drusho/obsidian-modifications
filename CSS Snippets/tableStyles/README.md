# Table Styles

**Original Creator**</br>
@DeaconLight & Obsidian Community contributors

**Original Source:**</br>
[Custom CSS for tables (+5 new styles)](https://forum.obsidian.md/t/custom-css-for-tables-5-new-styles-ready-to-use-in-your-notes/17084/38)



**Modification Created:**</br> 
2025-06-05

## Description
`tableStyles.css` is a modificaiton to a theme-aware custom table styler originally created by @DeaconLight for Obsidian.  This version refines and enhances the Academia (LaTeX) style.

Modifications include the following:

- Theme-aware alternating row colors that adapt to light and dark modes.
- A clear, non-distracting highlight effect when hovering over rows.
- Style support for both standard and rounded-corner tables.

## Style Examples

**Academia Rounded (Dark Mode)**</br>
Applies the academia and academia-rounded classes</br>
<img src="https://github.com/drusho/obsidian-modifications/blob/main/assets/rounded-table-dark.png?raw=true" height="300">

**Academia Rounded (Light Mode)**</br>
Applies the academia and academia-rounded classes.</br>
<img src="https://github.com/drusho/obsidian-modifications/blob/main/assets/rounded-table-light.png?raw=true" height="300">

**Academia Wide (Dark Mode)**</br>
Applies the academia and wideTable classes.</br>
<img src="https://github.com/drusho/obsidian-modifications/blob/main/assets/wide-table-dark.png?raw=true" height="300">

**Academia Wide (Light Mode)**</br>
Applies the academia and wideTable classes.</br>
<img src="https://github.com/drusho/obsidian-modifications/blob/main/assets/wide-table-light.png?raw=true" height="300">
</br>

## Usage
Download the [`tableStyles.css`](https://github.com/drusho/obsidian-modifications/blob/main/CSS%20Snippets/tableStyles/tableStyles.css) file from this repository.

1. In Obsidian, go to Settings > Appearance.
2. Place the file, `tableStyles.css`, in your vault's .obsidian/snippets directory.  Click on the folder to open this directory.
3. Under the "CSS snippets" section, enable the tableStyles snippet.

<img src="https://github.com/drusho/obsidian-modifications/blob/main/assets/css_style_instructions.png?raw=true" height="300"></br>

</br>

4. Under the "CSS snippets" section, enable the snippet you added.

## Applying a Style (Per-Note)

To activate a specific style on a note, add the cssclasses property to the note's frontmatter (at the very top of the file). You can add one or multiple classes to combine styles.

> [!TIP]
> This can be automated by creating a note template with the [Templater](https://silentvoid13.github.io/Templater/introduction.html) plugin, available in the Obsidian Community Plugins section.


</br>

### Style Examples

**Academia Rounded**</br>
Add the following to your note's properties:

```yaml
---
date: 2025-06-05
cssclasses:
- academia
- academia-rounded
---
```

**Academia Wide**</br>
Add the following to your note's properties:

```yaml
---
date: 2025-06-05
cssclasses:
- academia
- wideTable
---
```

</br>

---

Visit my website, [davidrusho.com](http://www.davidrusho.com), for other Obsidian modifications and custom setups.