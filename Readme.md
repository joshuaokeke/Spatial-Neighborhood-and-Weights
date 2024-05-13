
## Table of Contents

- [Introduction](#introduction)
- [Part 1: Loading Data](#part-1-loading-data)
- [Part 2: CRS Transformation](#part-2-crs-transformation)
- [Part 3: Contiguity Based Neighbors](#part-3-contiguity-based-neighbors)
- [Part 4: K-nearest Neighbors](#part-4-k-nearest-neighbors)
- [Part 5: Distance-based Neighborhoods](#part-5-distance-based-neighborhoods)
- [Part 6: Row-standardized Weights Matrix](#part-6-row-standardized-weights-matrix)
- [Part 7: Binary Weights Matrix](#part-7-binary-weights-matrix)
- [Part 8: Inverse Distance Weighting](#part-8-inverse-distance-weighting)
- [Conclusion](#conclusion)

## Introduction

Spatial Statistics Lab 5 focuses on exploring spatial data using R's `sf` package. We'll load shapefile data, perform coordinate reference system (CRS) transformations, create spatial weights matrices, and analyze neighborhood relationships.

## Part 1: Loading Data

We start by loading the SIDS shapefile data and inspecting its structure.

## Part 2: CRS Transformation
We examine the current CRS of the shapefile and transform it to different coordinate reference systems, such as NAD27 and North Carolina NAD 83 State Plane.

## Part 3: Contiguity Based Neighbors
We generate contiguity-based neighborhood relationships using Queen and Rook criteria, visualizing the spatial relationships.

## Part 4: K-nearest Neighbors
We explore K-nearest neighbor relationships, plotting the spatial points with neighborhoods created using different k values.

## Part 5: Distance-based Neighborhoods
We define neighborhoods based on specified distance thresholds, visualizing the differences in neighborhood structures.

## Part 6: Row-standardized Weights Matrix
We compute a row-standardized weights matrix and examine its structure.

## Part 7: Binary Weights Matrix
We create a binary weights matrix and analyze its weights.

## Part 8: Inverse Distance Weighting
We use inverse distance weighting to assign weights based on the distance between centroids, evaluating the resulting weights.

## Conclusion
Spatial Statistics provides hands-on experience with spatial analysis techniques in R, offering insights into neighborhood relationships and spatial weights matrices. By applying these methods, we gain a deeper understanding of spatial data and its spatial dependencies.


