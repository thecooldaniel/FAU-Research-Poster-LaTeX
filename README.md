# FAU Research Poster LaTeX Template

I got fed up using the PowerPoint template so I made this. Its as close as possible to the original template.

## Overview
This file uses absolutely positioned text boxes with coordinates originating from the upper-left corner of the document

## Custom Commands
Make sure to use these commands:
- `\titlebox`: Use for the title. Takes {x-pos}{y-pos}{width}{height}
- `\postertextbox`: Creates a new text box. Takes {x-pos}{y-pos}{width}{height}
- `\sectiontext`: Creates a section header
- `\authortext`: Use for the author lines. Place inside `\titlebox`
- `\bodytext`: use for body text and other elements. Put inside a `\posterbox`
- `\transparentimagebox`: Use to show images with a transparent background. Takes {x-pos}{y-pos}{width}{height}{path/to/image.png}
- `\posterfigure`: Use to create a figure with caption inside `\bodytext`

## Disclaimer
use at your own risk. I'm sure some things might be spaced weirdly in some scenarios. `\vspace` and `\hspace` are your friends!
