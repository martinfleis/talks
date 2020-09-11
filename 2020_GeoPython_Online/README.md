# GeoPython 2020

## On the morphological composition of cities and how to measure it

22 September 2020

## Abstract

Identification and description of morphological patterns forming cities are becoming easier due to expansion of urban open data and advancements of the related software. This talk presents current developments of methods of morphological analysis based on open data,  leading to a classification of distinct types of urban form patterns.

## Description

Cities are different - from social composition, through economic performance and culture to the topic of this talk - morphology. The ways cities around the world are built vary, and geospatial science is trying to understand different morphological patterns that characterise cities and their parts using a plethora of approaches. However, the complexity of urban form is complicated to capture, and we need novel tools and data inputs to develop methods which are scalable to national extents and comprehensive to reflect the peculiarity of different neighbourhoods.

This talk presents the current state of urban morphology in the Python world. It starts with the representation of form and data extraction and preprocessing, focusing predominantly on vector data capturing buildings footprints and street networks. It further introduces [momepy](https://momepy.org), a toolkit built on top of [GeoPandas](https://geopandas.org) allowing a complex multi-scale analysis of urban form from the perspective of measuring of the spatial configuration of simple vector features. 

Next, it presents the ways of generation of additional analytical elements representing basic spatial units, leading to the measuring of different aspects of geometry itself. By determining the spatial relationship between buildings, street networks and other features using GeoPandas, [PySAL](https://pysal.org) and [networkX](https://networkx.github.io), we can quantify size, shape and spatial distribution and configuration of different parts of cities all in the detail of a single element. Together with measurable density and diversity, we can derive an extensive set of morphological indicators capturing the complexity of urban form patterns.

The final part of the talk utilities a large number of indicators within the two-level clustering model able to detect distinct homogenous spatial patterns without the need for explicit spatial constraints. The second level of clustering results in a hierarchical dendrogram helping to understand relationship and similarity between identified patterns, which in turn represents a proxy for a taxonomy of urban form types.

The procedures could be robust enough to accommodate different levels of detail of open data mapping, from agglomerated Microsoft US Building Footprints to detailed open data released by local municipalities as is illustrated using various case studies.

## Slides

Slides are generated from Jupyter notebook using [RISE extension](https://rise.readthedocs.io/en/stable/index.html). Folder also includes custom CSS and fonts based on [Tufte CSS](https://github.com/edwardtufte/tufte-css).