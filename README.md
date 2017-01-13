# Awesome visualization research

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of data visualizations research papers, books, blog posts, and other readings. I aim to limit this to pieces that will be of interest to practitioners as well as academics. If you are looking for more practical tools and libraries see [awesome-dataviz](https://github.com/fasouto/awesome-dataviz). 

At present this list is very biased towards things I am reading for my personal research interests, but I'd gladly accept pull requests. 


## Table of contents

- [Animation](#animation)
- [Big Data](#data-management)
- [Color](#color)
- [Data Management](#data-management)
- [Graphs](#graphs)
- [Human Computer Interaction](#human-computer-interaction)
- [Research Methods](#research-methods)
- [Scientific Visualization](#scientific-visualization)
- [Statistics and Uncertainty](#statistics-and-uncertainty)
- [Systems, Toolkits, and Libraries](#systems-toolkits-and-libraries)


## Animation

- [Animation: From Cartoons to the User Interface](http://www.cc.gatech.edu/classes/AY2009/cs4470_fall/readings/animation.pdf) - lessons that interface designers can learn from cartoonists
- [Temporal Distortion for Animated Transitions](https://engineering.purdue.edu/~elm/projects/timedistort/timedistort.pdf) - a study on the impact of different easing curves in animations

## Big Data

- [Hierarchical Aggregation for Information Visualization: Overview, Techniques and Design Guidelines](https://engineering.purdue.edu/~elm/projects/hieragg/hieragg.pdf) - a model for multiscale representations of data, enabling more scalable visualization techniques
- [imMens: Real-time visual querying of big data](http://vis.stanford.edu/projects/immens/) - in browser system that leverages the GPU for real-time interaction
- [Nanocubes: Fast visualization of large spatiotemporal datasets](http://nanocubes.net/) - specialized database system for visualizing spatiotemporal datasets

## Color

- [Affective Colour Palettes in Visualization](https://research.tableau.com/paper/affective-colour-palettes-visualization-poster) - how can different color palletes convey different emotions?
- [mpl colormaps: a better default colormap for matplotlib](https://bids.github.io/colormap/) - detailed account of designing a better colormap for the popular matplotlib library
- [How we designed the new color palettes in Tableau 10](https://www.tableau.com/about/blog/2016/7/colors-upgrade-tableau-10-56782) - overview of designing color palettes in tableau

## Data Management

- [The Case for Data Visualization Management Systems](http://db.csail.mit.edu/pubs/p903-wu.pdf) - a vision paper arguing why we should build wholistic systems thinking of visualization and user interaction from the very start
- [Data Cube: A Relational Aggregation Operator Generalizing Group-By, Cross-Tab, and Sub-Totals](http://cs.stanford.edu/people/chrismre/cs345/rl/olap.pdf) - paper introducing the classic data cube
- [Tidy Data](http://vita.had.co.nz/papers/tidy-data.pdf) - Hadley Wickham's paper on data cleaning and formatting

## Graphs

- [Force-Directed Edge Bundling for Graph Visualization](https://www.win.tue.nl/vis1/home/dholten/papers/forcebundles_eurovis.pdf) - an algorithm for "bundling" edges on node-link diagrams, helps reduce visual clutter
- [Stacked Graphs – Geometry & Aesthetics](http://leebyron.com/streamgraph/stackedgraphs_byron_wattenberg.pdf) - In this paper Lee Byron & Martin Wattenberg introduce the streamgraph, a new type of stacked chart which was popularized by The New York Times.

## Human Computer Interaction

- [The Effects of Interactive Latency on Exploratory Visual Analysis](https://idl.cs.washington.edu/files/2014-Latency-InfoVis.pdf) - a look at how latency in a user interface can affect user behavior and impact what they learn about datasets
- [Past, Present and Future of User Interface Software Tools](http://www.cs.cmu.edu/~amulet/papers/futureofhci.pdf) - an overview of of successes and failures in user interface tools, ideas for thinking about them, and thoughts on the future

## Research Methods

- [Process and Pitfalls in Writing Information Visualization Research Papers](http://www.cs.ubc.ca/labs/imager/tr/2008/pitfalls/pitfalls.pdf) - an overview of different types of information visualization papers, and common problems that researchers face

## Scientific Visualization

- [Principles of high-dimensional data visualization in astronomy](http://projects.iq.harvard.edu/files/seamlessastronomy/files/heidelberg_ag.pdf) - this paper by Alyssa Goodman gives a good introduction to the concept of "linked views" (with the relevant history), and great more contemporary examples from domain sciences

- [How to make an engaging infographic]
(http://bjsm.bmj.com/content/early/2016/12/30/bjsports-2016-097023)an interesting article about infographics in health promotion.

## Statistics and Uncertainty

- [Hypothetical Outcome Plots: Experiencing the Uncertain](https://medium.com/hci-design-at-uw/hypothetical-outcomes-plots-experiencing-the-uncertain-b9ea60d7c740) - a Medium post explaining Hypothetical Outcome Plots (HOPs), an approach to visualizing uncertain data
- [The Separation Plot: A New Visual Method for Evaluating the Fit of Binary Models](http://mdwardlab.com/sites/default/files/GreenhillWardSacks.pdf) - a visual method for assessing the predictive power of models with binary outcomes
- [Surprise! Bayesian Weighting for De-Biasing Thematic Maps](https://idl.cs.washington.edu/files/2017-SurpriseMaps-InfoVis.pdf) - an adaptation of Bayesian surprise to generate better thematic maps. Unexpected events are visualized more prominently than those that follow expected patterns.

## Systems, Toolkits, and Libraries

- [Vega](https://vega.github.io/vega/) - an open source visualization grammer, enables other applications to build powerful abstractions on top of it
- [Vega Lite](https://vega.github.io/vega-lite/) - a high level visualization grammer, built on top of vega


# Contributing

- Please check for duplicates first.
- Submit a PR with a small justification for the inclusion.

Thanks for your suggestions!

# License

MIT

