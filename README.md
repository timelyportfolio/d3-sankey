# d3-horizon

D3 4.0 implementation of the [horizon](https://github.com/d3/d3-plugins/tree/master/horizon) plugin.  This implementation is based off the module pattern set by Mike Bostock in [d3-sankey](https://github.com/d3/d3-sankey) and described in his post [*Let's Make a (D3) Plugin*](https://bost.ocks.org/mike/d3-plugin/).

<hr/>

*original Readme.md*

# d3.horizon

Demo: <http://bl.ocks.org/1483226>

![Horizon Chart](http://vis.berkeley.edu/papers/horizon/construction.png)

A horizon chart is a variation of a single-series area chart where the area is folded into multiple bands. Color is used to encode bands, allowing the size of the chart to be reduced significantly without impeding readability.

This layout algorithm is based on the work of J. Heer, N. Kong and M. Agrawala in "Sizing the Horizon: The Effects of Chart Size and Layering on the Graphical Perception of Time Series Visualizations", CHI 2009.

<http://hci.stanford.edu/publications/2009/heer-horizon-chi09.pdf>
