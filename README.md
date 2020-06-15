# Thesis LaTeX template
Fork of https://github.com/claria/thesis_template.
Includes the ptdr definitions and allows setting bold particle names.

## Dependencies
- TeXLive full
- Libertus Font Family https://github.com/alif-type/libertinus (install in `~/.fonts/`)

## Structure
[`thesis.tex`]    Include the files, layout settings
[`chapters/`]   Thesis content.
[`includes/header.tex`]   LaTeX config, packages etc.
[`includes/commands.tex`]   Longer commands, like subfigure templates.
[`includes/shortcuts.tex`]   Short commands, like `\Htt`.


## Build
The build is issued using `make`.

## VSCODE
I recommend using VSCODE with the LaTeX workshop and LTeX extensions (https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop  and https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex). `settings.json` contains the recommended settings.