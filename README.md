# apple_health
_Jon Stelman_
  
  
Experiment with interactive data visualization using bokeh.  

## Data
Apple Health data is from my iPhone and Apple Watch. Data was exported and converted to .csv format using instructions by [Ryan Praski](http://www.ryanpraski.com/apple-health-data-how-to-export-analyze-visualize-guide/). Converted files are stored in `/data/`. 

## Analysis
The notebook `notebooks/visualize_health_data` allows for basic exploration of the data. This notebook implements my first time learning the interactive HTML plotting tool Bokeh.

Plotting is based on the NYT unemployment example provided at 
[bokeh.pydata.org/](https://bokeh.pydata.org/en/latest/docs/gallery/unemployment.html)  
  
The output HTML interactive plot is saved to `bokeh_output.html`.

## Next Steps
Obviously this is a work in progress. Hopefully I will discover richer datasets, that allow for exploring more varied types of health data (e.g. diet, workout, sleep, pain, etc.). Richer datasets will inspire more interesting questions, and hopefully prompt more exciting analysis.
