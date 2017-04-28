# LIS 590 Data Visualization Spring 2017 
## Component 2

This is the folder for Component 2 of *Group Summer*.

Including an ipython notebook of the interactive data visualizations, and several data files.


## Requirment: Interactive, Bespoke Visualization

**Concept**: What is the distribution of [IMLS](http://imls.gov/) grants, and
what do these grants do?

Your second dataset will be the [IMLS](http://imls.gov/) discretionary grants
database.  These grants include information about the topic of the grant, the
institution that received it, its duration, and a few other pieces of data.
You may also find useful and interesting data (especially related to zip codes
and economic factors) at [FRED](http://fred.stlouisfed.org).

Your visualization should be interactive. There are several frameworks you can
use to do this.  The three that we have discussed in detail in class have been
using the [IPython widgets](http://ipywidgets.readthedocs.io) interface to
build small, exploratory visualizations, the [Bokeh
framework](http://bokeh.pydata.org) and [Plotly](http://plot.ly/).
You may not use Tableau to build this visualization.  If there is another
framework you would like to use, please ask.

A few of the concepts that you may explore:

 * What types of grants are supported by IMLS?
 * How are these grants distributed across the United States?  Are they
   particularly clustered in certain states?
 * Is there a relationship between the economic factors in a zip code and the
   grants from IMLS?

Generate from this data either a notebook that can be executed, a python script
that can be executed, or a plotly dashboard that can be accessed.  If you
utilize plotly, at lease some of the plotly setup must be in a python script.
