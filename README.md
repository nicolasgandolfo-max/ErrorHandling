# Error Handling — Payment declines

Design exploration and HTML implementation of payment decline / error handling flows, built with the Félix design system.

## Contents

| Path | Description |
| --- | --- |
| `index.html` | Implementation of the payment declines screens. Open directly in a browser. |
| `Payment declines.dc.html` | Design canvas document (design_doc_mode) with the full set of decline states. Requires `support.js`. |
| `support.js` | Generated design-canvas runtime. Do not edit by hand. |
| `_ds/` | Félix design system bundle: tokens (colors, typography, spacing, motion), component CSS, illustrations and fonts. |

## Running

No build step. Serve the folder over HTTP so relative asset paths resolve:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html`.
