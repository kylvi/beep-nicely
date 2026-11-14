# Starter kit notes

Made from the design canvas on 14 Nov 2026. This folder is reference material; `css/` and `art/` next to it are part of the app.

| File | What it is | How it is used |
|---|---|---|
| `css/tokens.css` | Colours, type sizes, radii and spacing as CSS variables. | Linked from `index.html`. |
| `css/hamster.css` | The hamster's poses and idle movement. The comment at the top lists the class names that switch his pose. | Linked from `index.html`. |
| `reference/hamster-rig.html` | The hamster drawing, ready to paste into `index.html`. | Copy and paste, once. |
| `reference/hamster-poses.html` | A small page to try every pose. Its short script shows the main idea: JavaScript swaps class names, CSS does the moving. | Open in a browser. |
| `reference/prototype.html` | The whole working prototype from the canvas as one plain file. | Open in a browser. For trying things and looking things up. It is not the app. |
| `art/hamster-whole.svg`, `art/hamster-broccoli.svg` | The hamster as ordinary SVG pictures with named parts. | For Figma, the README, an app icon later. |

In the prototype, add `?workSeconds=10&restSeconds=5&rounds=2&getReadySeconds=0` to the address to change the demo times.
