# Data-Visualization

Data visualization is an important skill in applied statistics and machine learning.

Statistics does indeed focus on quantitative descriptions and estimations of data. Data visualization provides an important suite of tools for gaining a qualitative understanding.

This can be helpful when exploring and getting to know a dataset and can help with identifying patterns, corrupt data, outliers, and much more. With a little domain knowledge, data visualizations can be used to express and demonstrate key relationships in plots and charts that are more visceral to yourself and stakeholders than measures of association or significance.

Data visualization and exploratory data analysis are whole fields themselves and I will recommend a deeper dive into some the books mentioned at the end. In this tutorial, let’s look at basic charts and plots you can use to better understand your data.

Below picture suggests which graph you would like to show depending on their usage:
![](chart-suggestion.png)


Let's check out different ways:
* Based on Chart
  
* Language and Library
  - R
    * ggplot2 - A plotting system based on the grammar of graphics.
    * ggvis - A data visualization package with a syntax similar to ggplot2 which allows you to create rich interactive graphics.
    * lattice - trellis graphics for R
    * plotly - Interactive charts (including adding interactivity to ggplot2 output), cartograms and simple network diagrams
    * rbokeh - R Interface to Bokeh.
    * rgl - 3D Visualization Using OpenGL
    * shiny - Framework for creating interactive applications/visualisations
    * visNetwork - Interactive network visualisations
  - Python
    * altair - Declarative statistical visualizations, based on Vega-Lite.
    * bokeh - Interactive Web Plotting for Python.
    * diagram - Text mode diagrams using UTF-8 characters
    * ggplot - plotting system based on R's ggplot2.
    * glumpy - OpenGL scientific visualizations library.
    * holoviews - Complex and declarative visualizations from annotated data.
    * mayai - interactive scientific data visualization and 3D plotting in Python.
    * matplotlib - 2D plotting library.
    * missingno - provides flexible toolset of data-visualization utilities that allows quick visual summary of the completeness of your dataset, based on matplotlib.
    * plotly - Interactive web based visualization built on top of plotly.js
    * PyQtGraph - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
    * seaborn - A library for making attractive and informative statistical graphics.
    * toyplot - The kid-sized plotting toolkit for Python with grownup-sized goals.
    * veusz - Python multiplatform GUI plotting tool and graphing library
    * VisPy - High-performance scientific visualization based on OpenGL.
    * vtk - 3D computer graphics, image processing, and visualization that includes a Python interface.
  
* Representation type
  - Relationship
    * Two-Variables
      - Scatter plot
    * Three-Variables
      - Bubble chart
  - Distribution
    * Single-Varible
      - Few Data Points
        * Column Histogram
      - Many data points
        * Line Histogram
    * Two-Varibles
      - Scatter plot
    * Three-Variables
      - 3D Area plot
  - Comparison
    * Among Items
    * Over time
  - Composition
    * Changing over Time
      - Few periods
        * Only Relative difference between matter
          - Stacked 100% Column chart
        * Relative and Absolute diferences between matter
          - Stacked Column chart
      - Many periods
        * Only Relative difference between matter
          - Stacked 100% Area chart
        * Relative and Absolute diferences between matter
          - Stacked Area chart
    * Static
      - Simple Share of Total 
        * Pie Chart
      - Accumulation or Subtraction to total
        * Waterfall Chart
      - Components of Components
        * Stacked 100% column chart with sub-components
        
  
* D3 
* Deep Learning Visualization
  
  
