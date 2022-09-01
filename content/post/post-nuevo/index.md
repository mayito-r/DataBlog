+++
author = "Orihuela I"
title = "Mi nuevo post"
date = "2022-08-11"
description = "En este primer articulo vamos a aprender a usar polty"
tags = [
    "markdown",
    "css",
    "html",
    "themes",
]
categories = [
    "ML",
    "Python",
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
image = "plotly.png"
plotly = true
+++

<!--more-->

# Que plotly

Plotly es una forma parte del framework para elaborar dashboards Dashh

## Ejmplo de codigo

```bash
pip install plotly
```

asi ejecutamos una grafica de barras
```python
import plotly as plt

fig = go.Figure()
fig.update(axis=[1, 2])

fig.show()
```

es resultado es:

![espe akisajjajs](images/plotly.png)


live plot

{{< plotly json="/plots/hugo_plot.json" height="500px" >}}