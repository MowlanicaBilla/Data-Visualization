# Data-Visualization

Data visualization is an important skill in applied statistics and machine learning.

Statistics does indeed focus on quantitative descriptions and estimations of data. Data visualization provides an important suite of tools for gaining a qualitative understanding.

This can be helpful when exploring and getting to know a dataset and can help with identifying patterns, corrupt data, outliers, and much more. With a little domain knowledge, data visualizations can be used to express and demonstrate key relationships in plots and charts that are more visceral to yourself and stakeholders than measures of association or significance.

Data visualization and exploratory data analysis are whole fields themselves and I will recommend a deeper dive into some the books mentioned at the end. In this tutorial, let’s look at basic charts and plots you can use to better understand your data.

Below picture suggests which graph you would like to show depending on their usage:
![](chart-suggestion.png)


**_Let's check out different ways:_**
* **Based on Chart**
  - `Scatter Plot` : used to see the relationship between two continuous variables.
  - `Histogram` : used to plot continuous variable. It breaks the data into bins and shows frequency distribution of these bins. We can always change the bin size and see the effect it has on visualization.
  - `Bar Chart` : used when you want to plot a categorical variable or a combination of continuous and categorical variable.
    - Stacked Bar Chart : an advanced version of bar chart, used for visualizing a combination of categorical variables.
  - `Box Plot` : used to plot a combination of categorical and continuous variables. This plot is useful for visualizing the spread of the data and detect outliers. It shows five statistically significant numbers- the minimum, the 25th percentile, the median, the 75th percentile and the maximum.
  - `Area Chart` : used to show continuity across a variable or data set. It is very much same as line chart and is commonly used for time series plots. Alternatively, it is also used to plot continuous variables and analyze the underlying trends.
  - `Heat Map` : uses intensity (density) of colors to display relationship between two or three or many variables in a two dimensional image. It allows you to explore two dimensions as the axis and the third dimension by intensity of color.
  - `Correlogram` : used to test the level of co-relation among the variable available in the data set. The cells of the matrix can be shaded or colored to show the co-relation value.Darker the color, higher the co-relation between variables. Positive co-relations are displayed in blue and negative correlations in red color. Color intensity is proportional to the co-relation value
  - `Bubble Area Chart` : 
  - `Pie Chart`
  
* **Language and Library**
  - *R*
    * ggplot2 - A plotting system based on the grammar of graphics.
    * ggvis - A data visualization package with a syntax similar to ggplot2 which allows you to create rich interactive graphics.
    * lattice - trellis graphics for R
    * plotly - Interactive charts (including adding interactivity to ggplot2 output), cartograms and simple network diagrams
    * rbokeh - R Interface to Bokeh.
    * rgl - 3D Visualization Using OpenGL
    * shiny - Framework for creating interactive applications/visualisations
    * visNetwork - Interactive network visualisations
  - *Python*
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
  
* *Representation type*
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
      - One-Variable per Item
        * Many Categories
          - Table with embedded plot(Plot matrix)
        * Few Categories
          - Many Items
            * Bar Chart
          - Few Items
            * Column chart
      - Two-Variable per Item
        * Variable Width column chart
    * Over time
      - Many Periods
        * Cyclical data
          - Circular Area chart
        * Non-Cyclical data
          - Line Chart
      - Few Periods
        - Single or few categories
          * Column chart
        - Many Categories
          * Line chart
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
        
  
* *Interactive plot*
  - D3
* *Deep Learning Visualization*
  
  
