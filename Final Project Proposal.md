## Factors Affect Miss Distance of Near-Earth Objects

<p align="right"><em>Mar. 27, 2023: By Victor Chen</em></p>

By the end of January, an asteroid named 2023 BU skimmed through the orbit of Earth with the closest distance of 3589 kilometers, approximately half of the Earth's radius. This event, as all the previous similar events, raised the discussion on the potential asteroids that might crash with Earth.

Definitely, if an asteroid that is large enough crashes on the Earth, the result will be terrifying. The most renowned hypothesis of the extinction of dinosaur is that an asteroid crashed the Earth and caused serious consequences. This example clearly shows how devastating these asteroids can be when they crashed on Earth.

In this research, we are going to analyze the near-Earth objects that have a relatively close distance with Earth, and find out the potential relationship between the traits of the object (diameter, inclination, etc.) and their closet distance with Earth. We might also try to use the relationship derived to predict whether some asteroids that are identified as potential threat to Earth will strike on Earth or not.

### Dataset Used

In this research, the data that we are using will mainly come from NASA. They are listed in the following list.

- [NASA - Nearest Earth Objects](https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects)

  This is the dataset that give the NASA ID of all near-Earth objects with their closest distance to the Earth (miss distance); As a cumulative data for the near-Earth objects, it will be the main source for this research.

- [NASA: Asteroids Classification](https://www.kaggle.com/datasets/shrutimehta/nasa-asteroids-classification)

  This dataset related the NASA ID of the asteroids to their properties, such as the diameter, eccentricity, and many other properties. This dataset would provide the independent variables for this research.

- [Asteroid Dataset](https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset)

  This dataset functions similar to the previous dataset, and it can be used as a supplementary dataset.

### Analysis Plan

The responsible variable we are trying to analysis here is the miss distance, which stands for the closest distance from the asteroid to the Earth. The unit for this variable is kilometer, using the decimal variable type.

There are many possible predictor variables for this research, since there are many properties recorded for an asteroid. In this research, we are going to first find out the correlation between each individual variable with the responsible variable, and select the variables with highest correlations to build the multiple-variable regression.

More information related to this research can be found on [this GitHub repository](https://github.com/Magician1427/Nearest-Earth-Objects).

### Reference

1. 2023 BU, Wikipedia;

   https://en.wikipedia.org/wiki/2023_BU