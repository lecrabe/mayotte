### CHECK EFFECT OF DISTANCE TO ROAD ON DEFORESTATION IN MAYOTTE

Repository set to run under https://sepal.io

The chain does the following:
- Install the necessary libraries and setup the work environment
- Load GFC 2017 data for the boundaries of Mayotte
- Load forest boundaries (protected areas) and road network shapefiles and rasterize on the GFC layers
- Create distance to roads
- Run a Generalized additive model the dataset to test the effect of proximity to roads, inside and outside of PA, for the probability of a pixel to be deforested

![Alt text](/results/zoom_product.jpeg?raw=true "Vizualization of the products on the northern part or Mayotte")

![Alt text](/results/probability_loss.png?raw=true "GAM model results")

Thanks to Emma Wiik (Bangor University) for the help on the modelisation.