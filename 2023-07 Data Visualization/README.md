# July 2023 - Data Visualization

This month we'll be touring a couple of visualization libraries in Python,
  using the [M5 Forecasting dataset](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data).

## Pandas

The first stop for most datasci visualization is Pandas. It's generally the tool already at hand,
  so if it works, go for it.
Pandas allows for additional "backends" to be installed, which lets you use other visualization frameworks
  (besides matplotlib, which is the default) without substantially changing your code:
   - [altair](https://github.com/altair-viz/altair_pandas)
   - [plotly](https://plotly.com/python/pandas-backend/)
   - [bokeh](https://github.com/PatrikHlobil/Pandas-Bokeh)

## Seaborn 

## Altair

Altair is based on the [Vega](https://vega.github.io/vega/) Javascript library (specifically, it mostly uses the [vega-lite](https://vega.github.io/vega-lite/) subset).
  Vega is focused on making interactive plots in Javascript; Altair is a Python library which lets you display those charts in notebooks or return those charts from a server.
  It is probably one of the better choices to allow a wide variety of charts to be passed from a Python server backend to a Javascript frontend.
