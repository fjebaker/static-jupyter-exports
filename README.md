# Static Jupyter exports

Tests for exporting rich interactive notebooks statically to HTML and PDFs.

- Plotly bakes data into output, which means `nbconvert` actually can keep the interaction, which is very cool.
- Plotly is a little more verbose for this level of interaction, though [Plotly express also seems to support them](https://plotly.com/python/sliders/#sliders-in-plotly-express).
- Pandas and plotly ❤️ 

Conversion:

```bash
jupyter nbconvert --to html --no-input notebooks/simple-interactive.ipynb
```

I've taken the liberty of including the sample output to save having to setup the full environment.

See the [examples here](https://fjebaker.github.io/static-jupyter-exports/) 👀
