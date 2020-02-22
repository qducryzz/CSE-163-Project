# Astronomy: an investigation into stars
**Authors: Zhiyong Zhuang, Zezhong Yang, Victor Li**
### Research Summary
---
This project seeks to understand the part of universe our human perceived and gives the insight of how the brightness of stars in relate to the star type.

**Research Question 1:**
> Which part of the universe are we looking at?

- Plot scatter graphs to show how the milky way looks from different axis (x,y,z) with respect to the arms.
- Create a class that takes the user location and time to calculate the perceivable stars of the given user and return the graph with all perceivable stars plotted

**Research Question 2:**
> Is it sufficient to predict the spectrum type of stars based on their brightness and color?

- Filter the dataset to columns of star type, brightness, and color
- Subdivide the dataset into the train set and test subset
- Create a DecisionTreeClassifier to fit dataset and test out the accuracy

### Data
---
[HYG Database](https://github.com/astronexus/HYG-Database): Contains the background information of stellar data from a variety of catalogs: star names, positions, brightnesses, distances, and spectrum information.
> Source: Data Collected from [The Astronomy Nexus ](http://www.astronexus.com/hyg) represents a subset of the data in three major catalogs: the Hipparcos Catalog,the Yale Bright Star Catalog (5th Edition), and the Gliese Catalog of Nearby Stars (3rd Edition).
