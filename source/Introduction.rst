1. Introduction
===============

Rapid urbanisation and rising temperatures have led to unprecedented challenges for cities in mitigating urban heat islands and enhancing the thermal comfort of urban environments. Inner-city areas heat up considerably in the summer due to the high degree of urban sealing in densely built-up neighbourhoods, resulting in the formation of urban heat islands. To counteract this phenomenon, cool places are needed in city centres where people can relax and protect themselves from high temperatures and strong solar radiation.

This documentation guides through an approach to address this issue by visualising and quantifying urban shadow. Urban Shadow Modelling involves the precise simulation and analysis of shadow cast by urban structures such as buildings and trees. The process involves a combination of advanced geospatial data, processing methods and recording technologies, including high-resolution airborne imagery, Light Detection and Ranging (LiDAR), Geographic Information Systems (GIS), as well as open-source coding tools for three-dimensional urban modelling. The project was conducted in the context of the project `CATCH4D <https://catch4d.de/>`_.

Two main data sources are used to conduct this work, which are the **3D building data in CityGML format** and the **2D vegetation cadastre layer in shapefile format**. Additionally, **LiDAR data** is used to generate a normalised digital elevation model (nDSM), which is later used to extract the actual height values to the tree point layer. The calculation of the shadow cast is done by ESRIS shadow cast widget from the `ArcGIS API for JavaScript <https://developers.arcgis.com/javascript/latest/api-reference/esri-widgets-ShadowCast.html#methods-summary>`_.

1.1 Aim
-------

This approach is aiming to generate a threedimensional and interactive web map of the **city of Dortmund**, built upon an preexisting 3D building model in LoD2 format. For a precise shadow analysis and estimation of shaded areas in a city, the approach also includes the generation and visualization of a 3D tree dataset. The overall aim of this documentation is to serve as a guided workflow, to **replicate the shadowmap for other cities**. 


1.2 Results
-----------

The result of this approach is a three-dimensional web representation of the **city of Dortmund**, with the extended option of visualising the urban shadow cast of trees and buildings. Individual parameters such as **date** and **time** can be set individually by the user. Thus, it is possible to **a) visualize the shadow** and **b) understand the exact time of the shadow at a certain place.** 

The results demonstrate that urban shadow modelling is an effective method of identifying frequently shaded and cool areas in urban areas. It provides valuable insights for targeted interventions in areas where temperatures are exceptionally high in summer. Besides shadow visualization, a tree-planting tool is integrated, allowing users to plant trees virtually in sparsely vegetated areas to realise “what-if” planning scenarios. It provides an intuitive way for both residents and city planners to localise “cold spots”.


**Keywords:** *Urban Shadow Modelling, 3D Modelling at city scale, Urban Vegetation Modelling, Interactive Web Map, LiDAR, ArcGIS SDK for JavaScript*


