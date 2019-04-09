# Plot comparison

The goal of this small project is to display a scatter plot for different libraries in the same page, so the final user can see their pros and cons in an easy, fast and direct way.


# C3.js (v0.6.14)

[C3.js](https://c3js.org/) wraps the code required to construct [D3.js](https://d3js.org/) charts.
`C3.js` gives some classes to each element when generating,
so you can define a custom style by the class and
it's possible to extend the structure directly by `D3.js`.

`C3.js` provides a variety of APIs and callbacks to access the state of the chart.
By using them, you can update the chart even after it's rendered.

One issue is that the zooming feature is quite limited.
Only the `x` axis can be zoomed (see this [link](https://github.com/c3js/c3/issues/630)).
However, *probably* this could be solved handling the `D3` chart directly.
Some additional research is needed.


# Plotly

[Plotly](https://plot.ly/javascript/) is built on top of d3.js and stack.gl.
`plotly.js` is a high-level, declarative charting library that ships with 20 chart types,
including 3D charts, statistical graphs, and SVG maps.

It is very complete with zoom, pan, box select and export features.

Until now, _it is the best choice_.
