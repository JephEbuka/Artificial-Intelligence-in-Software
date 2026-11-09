# AI: Dynamic Web Lab Generation for Core CSS Concepts

For this task I used an AI tool to build small interactive "labs" that help me see how CSS works instead of just reading about it. Each lab is one HTML file with the CSS and JS inside it, so you can just open it in a browser.

## Files

| File | What it is |
| --- | --- |
| `box-model-lab-initial.html` | First version of the Box Model lab, from my first prompt. Two boxes (Box 1 and Box 2) with different colours for content, padding and margin, a solid border, sliders (with value labels) for padding, margin, border-width and width, and a dropdown to switch display between block, inline-block and inline. |
| `box-model-lab-refined.html` | The refined version after a follow-up prompt. Margin, padding and border each get separate top / right / bottom / left sliders, there's a border-radius slider, a reset button, and it prints the current CSS so I can see what the sliders are changing. |
| `flex-grid-playground.html` | Flexbox / Grid playground. A container with 5 items and dropdowns for display, flex-direction, justify-content, align-items and grid-template-columns. Everything updates straight away. Options that don't apply to the current display are greyed out. |
| `prompts.md` | The prompts I used, in order. |
| `reflection.md` | My reflection on how useful this was for learning. |

## Colour key (box model labs)

- blue = content
- green = padding
- black = border
- orange = margin

## How to run

Download the folder and open any of the `.html` files in Chrome, Firefox or Edge. No install or server needed.

## AI tool used

Claude (Anthropic). I gave it the prompts in `prompts.md`, checked the output in the browser, and asked for changes where something didn't look right (for example the margin colour not showing above and below the boxes at first, because of margin collapsing).
