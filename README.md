# Awesome visualization research

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of data visualizations research papers, books, blog posts, and other readings. I aim to limit this to pieces that will be of interest to practitioners as well as academics. If you are looking for more practical tools and libraries see [awesome-dataviz](https://github.com/fasouto/awesome-dataviz).

At present this list is very biased towards things [@petulla](http://github.com/petulla) or I are reading for personal research interests, but we gladly accept pull requests.


## Table of contents


- [Animation](#animation)
- [Automated Visualization Design](#automated-visualization-design)
- [Big Data](#big-data)
- [Color](#color)
- [Data Management](#data-management)
- [Graphs](#graphs)
- [Human Computer Interaction](#human-computer-interaction)
- [Narrative and Story](#narrative-and-story)
- [Perception](#perception)
- [Research Methods](#research-methods)
- [Scientific Visualization](#scientific-visualization)
- [Statistics and Uncertainty](#statistics-and-uncertainty)
- [Systems, Toolkits, and Libraries](#systems-toolkits-and-libraries)
- [Visual Forms](#visual-forms)


## Animation

- [Animation: From Cartoons to the User Interface](http://www.cc.gatech.edu/classes/AY2009/cs4470_fall/readings/animation.pdf) - lessons that interface designers can learn from cartoonists
- [Temporal Distortion for Animated Transitions](https://engineering.purdue.edu/~elm/projects/timedistort/timedistort.pdf) - a study on the impact of different easing curves in animations



## Automated Visualization Design

- [Automating the Design of Graphical Presentations of Relational Information](https://research.tableau.com/sites/default/files/p110-mackinlay.pdf) - algorithm for automatically creating a visualization, given a dataset.

## Big Data

- [Hierarchical Aggregation for Information Visualization: Overview, Techniques and Design Guidelines](https://engineering.purdue.edu/~elm/projects/hieragg/hieragg.pdf) - a model for multiscale representations of data, enabling more scalable visualization techniques
- [imMens: Real-time visual querying of big data](http://vis.stanford.edu/projects/immens/) - in browser system that leverages the GPU for real-time interaction
- [Nanocubes: Fast visualization of large spatiotemporal datasets](http://nanocubes.net/) - specialized database system for visualizing spatiotemporal datasets
- [Bin-summarise-smooth: A framework for visualising large data](https://vita.had.co.nz/papers/bigvis.pdf) - general visualization methods for large datasets

## Color

- [Affective Colour Palettes in Visualization](https://research.tableau.com/paper/affective-colour-palettes-visualization-poster) - how can different color palette convey different emotions?
- [Algorithmic improvements for the CIECAM02 and CAM16 color appearance models](https://www.researchgate.net/publication/323257267_Algorithmic_improvements_for_the_CIECAM02_and_CAM16_color_appearance_models/fulltext/5a8a41120f7e9b1a95543172/323257267_Algorithmic_improvements_for_the_CIECAM02_and_CAM16_color_appearance_models.pdf?origin=publication_detail) - An overview of the CIECAM16 and CIECAM02 color appearance models, thought to be successors to the popular CIELAB model.
- [mpl colormaps: a better default colormap for matplotlib](https://bids.github.io/colormap/) - detailed account of designing a better colormap for the popular matplotlib library
- [How we designed the new color palettes in Tableau 10](https://www.tableau.com/about/blog/2016/7/colors-upgrade-tableau-10-56782) - overview of designing color palettes in tableau
- [Modeling Color Difference for Visualization Design](http://cmci.colorado.edu/visualab/VisColors/) - An attempt to model how color is perceived depending on form and viewing conditions of the visualization
- [Revised color-appearance model for related and unrelated colors](https://www.researchgate.net/publication/229676527_Revised_color-appearance_model_for_related_and_unrelated_colors) - Hunt's color appearance model, which was used as the basis for the Colorbrewer palettes.
- [Somewhere Over the Rainbow: An Empirical Assessment of Quantitative Colormaps](https://idl.cs.washington.edu/papers/quantitative-color/) - Comparative analysis of different color maps and rainbow scales.
- [When Guidelines Clash: Determining Which Color Means More](https://medium.com/multiple-views-visualization-research-explained/ieee-vis-2018-color-interaction-augmented-reality-ae999b227c7) - If a design goal is to produce colormaps that match people’s inferred mappings and are robust to changes in background color, it is beneficial to use colormaps that will not appear to vary in opacity on any background color, and to encode larger quantities in darker colors.

## Data Management

- [The Case for Data Visualization Management Systems](http://db.csail.mit.edu/pubs/p903-wu.pdf) - a vision paper arguing why we should build wholistic systems thinking of visualization and user interaction from the very start
- [Data Cube: A Relational Aggregation Operator Generalizing Group-By, Cross-Tab, and Sub-Totals](http://cs.stanford.edu/people/chrismre/cs345/rl/olap.pdf) - paper introducing the classic data cube
- [Tidy Data](http://vita.had.co.nz/papers/tidy-data.pdf) - Hadley Wickham's paper on data cleaning and formatting

## Graphs

- [Towards Unambiguous Edge Bundling: Investigating Confluent Drawings for Network Visualization](http://ialab.it.monash.edu/~dwyer/papers/confluentbundling.pdf) - User study of edge bundling and compression techniques.
- [Scalable Graph Exploration and Visualization: Sensemaking Challenges and Opportunities](https://www.cc.gatech.edu/~dchau/papers/15-bigcomp-sensemaking.pdf) - survey paper focusing on large graph exploration and sensemaking, summarizes algorithms, visualizations, and interaction techniques
- [Force-Directed Edge Bundling for Graph Visualization](https://www.win.tue.nl/vis1/home/dholten/papers/forcebundles_eurovis.pdf) - an algorithm for "bundling" edges on node-link diagrams, helps reduce visual clutter
- [HOLA: Human-like Orthogonal Network Layout](http://marvl.infotech.monash.edu/~dwyer/papers/hola2015.pdf) - an algorithm for producing graphs that look like they were drawn by a person

## Human Computer Interaction

- [Explaining the Gap: Visualizing One’s Predictions Improves Recall and Comprehension of Data](https://idl.cs.washington.edu/files/2017-ExplainingTheGap-CHI.pdf) - Paper validating "you draw it" visualizations and other modes of asking the reader for prediction input
- [The Effects of Interactive Latency on Exploratory Visual Analysis](https://idl.cs.washington.edu/files/2014-Latency-InfoVis.pdf) - a look at how latency in a user interface can affect user behavior and impact what they learn about datasets
- [Exploration Strategies for Discovery of Interactivity in Visualizations](https://prism.ucalgary.ca/bitstream/handle/1880/106607/2018-1104-03.pdf?sequence=1) - model for understanding how users first experience an interactive
- [Past, Present and Future of User Interface Software Tools](http://www.cs.cmu.edu/~amulet/papers/futureofhci.pdf) - an overview of successes and failures in user interface tools, ideas for thinking about them, and thoughts on the future

## Narrative and Story

- [An argument structure for data stories](https://kosara.net/papers/2017/Kosara-EuroVis-2017.pdf) - Kosara's attempt to breakdown alternative narrative structures from the inverted pyramid suitable for data stories.
- [Finding a Clear Path: Structuring Strategiesm for Visualization Sequences](https://kosara.net/papers/2017/Hullman-EuroVis-2017.pdf) - Study of strategies for ordering visualizations in a narrative
- [Narrative Visualization: Telling Stories with Data](http://vis.stanford.edu/files/2010-Narrative-InfoVis.pdf) - Heer's attempt in 2010 to describe a shift happening in the use of visualizations toward what he calls "narrative visualization"
- [Visual Narrative Flow: Exploring Factors Shaping Data Visualization Story Reading Experiences](https://www.cs.utah.edu/~miriah/publications/narrative-flow.pdf) - Discussion of scrollers and steppers and whether readers prefer a "flow" experience over something more static
- [Visualization Rhetoric: Framing Effects in Narrative Visualization](http://www.nickdiakopoulos.com/Documents/visRhetoric_final_preprint.pdf) - Breakdown of rhetorical techniques in the framing of visualizations

## Perception

- [Assessing Effects of Task and Data Distribution on the Effectiveness of Visual Encodings](http://idl.cs.washington.edu/files/2018-TaskDataEffectiveness-EuroVis.pdf) - An attempt to refine studies of visual encoding by including the task performed by the viewer when measuring visualization performance
- [Attention Capacity](http://steveharoz.com/research/attention/) - The capacity of attention is limited. How does this limitation impact visualization?
- [Four types of ensemble coding in data visualizations](https://www.ncbi.nlm.nih.gov/pubmed/26982369) - An evaluation of four perceptual tasks performed by audiences of data visualization.
- [Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods](http://info.slis.indiana.edu/~katy/S637-S11/cleveland84.pdf) - Classic Cleveland paper looks at the effectiveness of different graphical forms
- [How do People Make Sense of Unfamiliar Visualizations?](https://pdfs.semanticscholar.org/9fcc/2e2314cdf713a3763c9288b1a8fff9b64873.pdf) - An attempt to model how people make sense of information visualizations -- in particular unfamiliar visualization forms.
- [Learning Perceptual Kernels for Visualization Design](http://idl.cs.washington.edu/files/2014-PerceptualKernels-InfoVis.pdf) -  An introduction to perceptual kernels: distance matrices derived from aggregate perceptual judgments. Essentially, a way of quantifying perceptual similarity scores among different visualization encodings.
- [Structure and strategy in encoding simplified graphs](https://pdfs.semanticscholar.org/14fa/c8a02c038ec88fa9a7139df5adc03831fe82.pdf) - a study of "cognitive reference frames" for visualization and how people remember graphs symmetrically, even when the data is asymmetric
- [Useful Junk? The effects of visual embellishment on comprehension and memorability of charts](https://www.researchgate.net/publication/221517808_Useful_Junk_The_effects_of_visual_embellishment_on_comprehension_and_memorability_of_charts) - Charts with "embellishments" (sometimes called chart junk) perform better in memory recall weeks after viewing


## Research Methods

- [Crowdsourcing Graphical Perception: Using Mechanical Turk to Assess Visualization Design](http://vis.stanford.edu/files/2010-MTurk-CHI.pdf) - Heer and Bostock paper using crowdsourced participants that validates its utility as a research tool.
- [Process and Pitfalls in Writing Information Visualization Research Papers](http://www.cs.ubc.ca/labs/imager/tr/2008/pitfalls/pitfalls.pdf) - an overview of different types of information visualization papers, and common problems that researchers face
- [Why Evaluating Uncertainty Visualization is Error Prone](https://faculty.washington.edu/jhullman/paper_BELIV_evaluating_uncertainty_vis.pdf) - Evaluation of methodologies for measuring readers' grasp of uncertainty.

## Scientific Visualization

- [Principles of high-dimensional data visualization in astronomy](http://projects.iq.harvard.edu/files/seamlessastronomy/files/heidelberg_ag.pdf) - this paper by Alyssa Goodman gives a good introduction to the concept of "linked views" (with the relevant history), and great more contemporary examples from domain sciences

## Statistics and Uncertainty

- [Displaying Uncertainty with Shading](https://www.tandfonline.com/doi/abs/10.1198/000313008X370843?journalCode=utas20) - User study of shading techniques in representing uncertainty
- [Hypothetical Outcome Plots: Experiencing the Uncertain](https://medium.com/hci-design-at-uw/hypothetical-outcomes-plots-experiencing-the-uncertain-b9ea60d7c740) - a Medium post explaining Hypothetical Outcome Plots (HOPs), an approach to visualizing uncertain data
- [Infovis and Statistical Graphs: Different Goals, Different Looks](http://www.stat.columbia.edu/~gelman/research/published/vis14.pdf) - Gelman's paper on how creators of statistical graphs can learn from the infovis community and vice-versa
- [Investigating the Effect of the Multiple Comparisons Problem in Visual Analysis](http://emanuelzgraggen.com/assets/pdf/risk.pdf) - Why the more visual comparisons an analyst makes, the more likely they are to find spurious patterns 
- [The Separation Plot: A New Visual Method for Evaluating the Fit of Binary Models](https://www.researchgate.net/profile/Michael_Ward12/publication/228213305_The_%27Separation_Plot%27_A_New_Visual_Method_for_Evaluating_the_Predictive_Power_of_LogitProbit_Models/links/0c96052d072aba8a1b000000/The-Separation-Plot-A-New-Visual-Method-for-Evaluating-the-Predictive-Power-of-Logit-Probit-Models.pdf) - a visual method for assessing the predictive power of models with binary outcomes
- [Sketchy Rendering for Information Visualization](http://openaccess.city.ac.uk/1274/) - Evaluation of use of "Sketchy" visualizations to represent uncertainty
- [Surprise! Bayesian Weighting for De-Biasing Thematic Maps](https://idl.cs.washington.edu/files/2017-SurpriseMaps-InfoVis.pdf) - an adaptation of Bayesian surprise to generate better thematic maps. Unexpected events are visualized more prominently than those that follow expected patterns
- [The Perception of Visual Uncertainty Representation by Non-experts](https://ieeexplore.ieee.org/document/6654171/) - User study of confidence bands, gradients and other techniques to show confidence intervals and uncertainty
- [When (ish) is My Bus? User-centered Visualizations of
Uncertainty in Everyday, Mobile Predictive Systems](https://faculty.washington.edu/jhullman/busUncertaintyVis.pdf) - Evaluation of strategies for real-time visualizations that communicate uncertainty

## Systems, Toolkits, and Libraries

- [A Layered Grammar of Graphics](http://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf) - description of ggplot2 by Hadley Wickham.
- [D3: Data Driven Documents](http://vis.stanford.edu/files/2011-D3-InfoVis.pdf)
- [Declarative Language Design for Interactive Visualization](http://idl.cs.washington.edu/papers/protovis-design/) - Investigation of the design of declarative, domain-specific languages for constructing interactive visualizations. Informs decisions in Vega and Protovis.
- [Draco](https://uwdata.github.io/draco/) - a formal framework for representing design knowledge about effective visualization design as a collection of constraints. Can be used to build visualization recommendation systems.
- [Software Design Patterns for Information Visualization](http://idl.cs.washington.edu/papers/infovis-design-patterns/) - Discussion of how to effectively design software for information visualizations.
- [Vega](https://vega.github.io/vega/) - an open source visualization grammar, enables other applications to build powerful abstractions on top of it
- [Vega Lite](https://vega.github.io/vega-lite/) - a high level visualization grammar for interaction, built on top of vega
- [Visualization Analysis and Design](https://www.crcpress.com/Visualization-Analysis-and-Design/Munzner/p/book/9781466508910) -  Munzner's systems framework for thinking about visualization in terms of principles and design choices.

## Visual Forms
- [Arcs, Angles, or Areas: Individual Data Encodings in Pie and Donut Charts](https://research.tableau.com/sites/default/files/Skau-EuroVis-2016.pdf) - Robert Kosara's study on reading accuracy with pie charts.
- [Data Through Others’ Eyes: The Impact of Visualizing Others’
Expectations on Visualization Interpretation](https://faculty.washington.edu/jhullman/VIS17_Expectations_SocialVis.pdf) - Evaluation of visualizations that reveal other user's expectations around a dataset, like NYT's You Draw It results graphs.
- [Evaluation of Alternative Glyph Designs for Time Series Data in a Small Multiple Setting](https://www.lri.fr/~isenberg/publications/papers/Fuchs_2013_EOA.pdf) - User study of different timeline styles (line, star, radial etc.).
- [Four Experiments on the Perception of Bar Charts](https://research.tableau.com/sites/default/files/bar.pdf) - Follow-up to Cleveland's 1984 study that looks closer at why and when bar charts are preferable
- [Graphical Methods for Data Presentation: Full Scale Breaks, Dot Charts, and Multibased Logging](https://www.jstor.org/stable/2683401) - Cleveland study on dot plots over bar charts
- [Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods](https://www.jstor.org/stable/2288400?seq=1#page_scan_tab_contents) - Classic paper with ranked lists of how well people decode visual cues.
- [ISOTYPE Visualization Working Memory, Performance, and Engagement](http://steveharoz.com/research/isotype/) - Analysis of the use of isotypes as representations within the chart drawing space
- [Sizing the Horizon: The Effects of Chart Size and Layering on the Graphical Perception of Time Series Visualizations](http://www.vis.berkeley.edu/papers/horizon/2009-TimeSeries-CHI.pdf) - Heer user study of time series area charts vs. horizon charts.
- [Perceptual Guidelines for Creating Rectangular Treemaps](https://pdfs.semanticscholar.org/12e5/f66739c6f746d0ebfc52eb52f18d288f4064.pdf) - Heer user study on the effective design of treemaps, followed up by later studies
- [Stacked Graphs – Geometry & Aesthetics](http://leebyron.com/streamgraph/stackedgraphs_byron_wattenberg.pdf) - In this paper Lee Byron & Martin Wattenberg introduce the streamgraph, a new type of stacked chart which was popularized by The New York Times.
- [Sunburst Chart](http://www.cc.gatech.edu/~john.stasko/papers/infovis00.pdf) - the sunburst chart is a radial alternative to a treemap
- [The Connected Scatterplot for Presenting Paired Time Series](https://research.tableau.com/sites/default/files/Haroz-TVCG-2016.pdf) - Kosara user study of the connected scatter plot.
- [Timelines Revisited: A Design Space and Considerations for Expressive Storytelling](https://pdfs.semanticscholar.org/0812/fd5208001851e75d6c2f0881e2f5d037f285.pdf) - A metastudy of over 200 timeline designs.
- [Tree-Maps: a space-filling approach to the visualization of hierarchical information structures](https://dl.acm.org/citation.cfm?id=949654) - Shneiderman's treemap paper, where he describes the form initially
- [Using Typography to Expand the Design Space of Data Visualization](https://www.sciencedirect.com/science/article/pii/S2405872616300107) - Exploration of ways to use type to construct visualization forms

# Contributing

- Please check for duplicates first.
- Submit a PR with a small justification for the inclusion.

Thanks for your suggestions!

# License

MIT

