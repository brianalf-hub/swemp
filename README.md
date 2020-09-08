
## Environmental factors affecting annual and perennial invasive plants in the American Southwest

<p align="center">
  <img width="600" height="500" src="https://user-images.githubusercontent.com/70289096/91906991-4b28b600-ec66-11ea-9a9d-c1fbbe25a473.png">
</p>


### Background. Second to anthropogenic habitat degradation, invasive plants are a major factor for loss of global biodiversity. I used vegetation survey data collected by the U.S. Geological Survey from 1997 to 2007, and climate data from WorldClim (https://www.worldclim.org/data/worldclim21.html) to identify and predict climatic factors that affect the diversity of invasive plants in the southwestern United States. To combine the vegetation data (vector) with environmental data (raster), I used QGIS (Python) and R to extract and combine these two data sets. Then, I used a spatially-filtered model selection of climatic and anthropogenic variables via a maximum likelihood ratio approach, and to run Bayesian spatial modeling to create a GIS map prediction of annual and perennial invasive plants. 

### Results. I determined that the highest-ranked model was precipitation for annuals, and temperature for perennials. The next step is for me to rasterize the GIS model and then extract values to train a machine learning regression model to predict how annual and perennial invasive plants will spead several decades from our current time. 
<br />

