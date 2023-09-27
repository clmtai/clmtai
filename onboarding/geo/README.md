# Geospatial Data Science Onboarding Guide

Welcome! In this onboarding guide, we will introduce you to the fascinating field of geospatial data analysis and set the stage for your learning journey.

## Introduction

Geospatial data science is at the heart of understanding our world. It allows us to harness the power of location data to make informed decisions, solve complex problems, and uncover valuable insights. It helps us find the answers to fundamental questions about "where," "what," and "why." It enables us to precisely pinpoint locations and map phenomena on Earth's surface, providing insights into "where" events occur. By integrating geospatial data with other datasets, it uncovers patterns and trends, revealing "what" is happening in specific areas. Moreover, geospatial analysis delves into spatial relationships, allowing us to understand the "how" and "why" behind processes and phenomena, whether it's modeling water flow in a watershed or assessing the impact of urban development on the environment. In essence, geospatial data science empowers us to make informed decisions, solve complex problems, and drive innovation across various domains by addressing these key questions about location, attributes, and causality.

## Our Goal

Our immediate goal for this onboarding guide is to equip you with the fundamental skills and knowledge required to contribute effectively to our project. By the end of this onboarding process, you should be prepared to actively engage in tasks, collaborate with the team, and make meaningful contributions. We are delighted to have you on board!

## What to Expect

In the following sections, we will:

1. **Provide an Overview:** We'll start with an overview of geospatial data analysis, its significance in various industries, and real-world applications.
2. **Introduce Key Concepts:** You'll dive into essential concepts such as geographic information systems (GIS), satellite imagery, map projections, and more.
3. **Explore Tools and Technologies:** We'll introduce you to the tools and technologies commonly used in geospatial data analysis, including popular software, libraries, and platforms.
4. **Hands-On Learning:** Practical experience is crucial. We'll guide you through hands-on exercises and projects that will reinforce your understanding and skills.
5. **Collaboration and Resources:** You'll learn how to collaborate effectively with our team and access valuable resources.

## Let's Get Started!

We're here to support your learning journey every step of the way. Feel free to reach out to our team members if you have questions or need assistance. 

Feel free to contact Anton at anton@clmtai.org or Ciaran at ciaran@clmtai.org

## Key Definitions

In the world of geospatial data science, several fundamental terms are essential to understand. Let's define three crucial concepts:

### 1. Geospatial Data

**Geospatial data** refers to information that is inherently tied to a specific location on Earth's surface. It includes various types of data associated with geographic coordinates, such as latitude and longitude. Geospatial data can represent physical features like mountains, rivers, and cities, as well as non-physical attributes like temperature, population density, and land use. This data is crucial for mapping, analysis, and decision-making in a wide range of fields, from environmental science to urban planning.

### 2. Geospatial Data Science

**Geospatial data science** is a multidisciplinary field that focuses on extracting knowledge, insights, and patterns from geospatial data. It combines principles and techniques from geography, computer science, data analysis, and domain-specific areas to solve complex spatial problems. Geospatial data scientists use tools and methodologies to explore, model, and visualize geographic information, leading to informed decision-making, resource management, and innovation in various industries.

### 3. Geographic Information System (GIS)

**Geographic Information System (GIS)** is a term used to describe the tools and frameworks used for capturing, storing, managing, analyzing, and presenting geospatial data. GIS technology allows users to create maps, perform spatial analysis, and integrate various data sources to gain a deeper understanding of geographical patterns and relationships. It is an indispensable tool in fields such as cartography, urban planning, natural resource management, and disaster response.

As you progress in your learning journey, you'll gain valuable insights into how geospatial data, data science techniques, and GIS technology work together to address real-world challenges and opportunities.

#### Useful Links

- [Introductory lecture on Spatial Data Analysis](https://www.youtube.com/watch?v=JwHxJsesG2Y&list=PLzREt6r1NenmFyTw8v2JZpEE4PZGNi5Ht)
- [What is GIS?](https://www.youtube.com/watch?v=Mw2KH1WQ8oA)
- [National Geographic Article](https://education.nationalgeographic.org/resource/geographic-information-system-gis/)
- [Free Introductory Book](https://volaya.github.io/gis-book/en/index.html)
- [UC Davis GIS Specialisation](https://www.coursera.org/specializations/gis)
- [Video on Geo-Spatial Data Concepts](https://www.youtube.com/watch?v=4LVsYa7GVDE)

## An Introduction to Satellite Imagery

### Introduction

Satellite imagery is a powerful and invaluable resource that provides us with a unique perspective on our planet. From monitoring climate patterns to studying land use changes and tracking natural disasters, satellite imagery plays a crucial role in a wide range of fields, including environmental science, agriculture, urban planning, and disaster management. In this section, we'll explore the world of satellite imagery, understand the data it offers, and introduce you to some of the most commonly used NASA and ESA data sets.

### Data Associated with Satellite Imagery

Satellite imagery consists of high-resolution images captured by satellites orbiting Earth. These images are generated using various sensors and instruments that capture data across different parts of the electromagnetic spectrum, including visible light, infrared, and microwave wavelengths. The data associated with satellite imagery provides a wealth of information:

- **Spectral Data:** Different sensors capture data in different spectral bands, allowing us to analyze phenomena such as vegetation health, land cover, and atmospheric composition.

- **Temporal Data:** Satellites capture images at regular intervals, providing a historical record of changes over time. This is essential for tracking trends, monitoring seasonal variations, and assessing long-term impacts.

- **Geospatial Data:** Satellite imagery includes geospatial information, enabling precise georeferencing and mapping. This allows us to correlate imagery with specific geographic locations on Earth.

- **Resolution:** Satellite imagery comes in various resolutions, from low-resolution global views to high-resolution images that can capture fine details on the Earth's surface.

## An Introduction to Satellite Bands

To make the most of satellite imagery, it's essential to understand the concept of satellite bands. Satellite bands refer to the specific regions of the electromagnetic spectrum that satellites capture and record. Each band provides unique information about the Earth's surface and atmosphere, making them essential for various geospatial analyses.

### Understanding Satellite Bands

Satellite sensors are equipped with detectors that measure electromagnetic radiation in different parts of the spectrum. Here's an overview of the key satellite bands and their characteristics:

### 1. **Visible Bands:**

   - **Blue Band:** Captures blue light (approximately 0.45-0.52 micrometers). Useful for detecting water bodies and distinguishing water from other land features.

   - **Green Band:** Captures green light (approximately 0.53-0.59 micrometers). Helps identify healthy vegetation, as chlorophyll reflects green light.

   - **Red Band:** Captures red light (approximately 0.63-0.69 micrometers). Useful for vegetation health assessment and land cover classification.

### 2. **Infrared Bands:**

   - **Near-Infrared (NIR) Band:** Captures near-infrared light (approximately 0.75-1.4 micrometers). Used for vegetation analysis, as healthy vegetation strongly reflects NIR light.

   - **Shortwave Infrared (SWIR) Band:** Captures shortwave infrared light (approximately 1.4-3.0 micrometers). Helps detect moisture content in soils and rock types.

### 3. **Thermal Infrared Bands:**

   - **Thermal Infrared (TIR) Band:** Captures thermal radiation (approximately 8-15 micrometers). Measures temperature variations on the Earth's surface, used in applications like detecting wildfires and monitoring urban heat islands.

### 4. **Microwave Bands:**

   - **Microwave Bands:** Microwaves (wavelengths ranging from millimeters to meters) are used in radar imagery. Microwaves can penetrate clouds and provide information on surface roughness, soil moisture, and more.

Understanding these satellite bands and their specific uses is crucial for interpreting satellite imagery. Depending on your geospatial analysis goals, you may need to work with data from multiple bands to extract meaningful insights.

#### Useful Links

- [Introductory Video to Satellite Imagery](https://www.youtube.com/watch?v=ERPgsFSUfX4)
- [What is Remote Sensing](https://www.youtube.com/watch?v=F2mQ6fJSxRY)
- [Remote Sensing and Classification](https://www.youtube.com/watch?v=Hgf3k981Cvw)
- [Landsat8 Example - Band by Band](https://www.youtube.com/watch?v=A6WzAc1FTeA)
- [Remote Sensing Image Acquisition, Analysis, and Applications - UNSW Specialism](https://www.coursera.org/learn/remote-sensing)
- [University of Toronto Satellite Imagery in a GIS Specialism](https://www.coursera.org/learn/spatial-analysis-satellite-imagery-in-a-gis)

## Commonly Used NASA and ESA Data Sets

### NASA Data Sets

- **[NASA Landsat](https://www.nasa.gov/mission_pages/landsat/main/index.html):** Landsat satellites have been capturing Earth's surface since the 1970s, offering an extensive archive of multispectral imagery. The Landsat data is instrumental in land cover classification, environmental monitoring, and resource management.

- **[NASA MODIS](https://modis.gsfc.nasa.gov/):** The Moderate Resolution Imaging Spectroradiometer (MODIS) instruments aboard NASA's Terra and Aqua satellites provide daily global coverage. MODIS data is used for climate studies, vegetation analysis, land surface temperature monitoring, and wildfire detection.

- **[NASA GRACE](https://www.nasa.gov/mission_pages/Grace/overview/index.html):** The Gravity Recovery and Climate Experiment (GRACE) mission measures variations in Earth's gravity field, providing insights into water distribution, ice sheet dynamics, and land subsidence. It contributes significantly to climate and hydrology research.

- **[NASA AIRS](https://airs.jpl.nasa.gov/):** The Atmospheric Infrared Sounder (AIRS) aboard NASA's Aqua satellite measures temperature and humidity profiles in Earth's atmosphere, aiding in weather forecasting and climate research.

### ESA Data Sets

- **[ESA Sentinel-1](https://sentinel.esa.int/web/sentinel/missions/sentinel-1):** Sentinel-1 is a radar imaging mission that provides all-weather, day-and-night imagery. It is used for disaster monitoring, mapping changes in land cover, and analyzing deformations of the Earth's surface.

- **[ESA Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2):** Sentinel-2 offers high-resolution multispectral imagery, making it valuable for agriculture, forestry, and land cover classification. It provides data on vegetation health, crop monitoring, and land use planning.

- **[ESA Copernicus Climate Change Service](https://climate.copernicus.eu/):** ESA's Copernicus Climate Change Service provides a suite of data sets for climate analysis. This includes information on temperature, sea level, and greenhouse gas concentrations, essential for climate monitoring and research.

## Most Useful Data Sets for Climate and Agricultural Analysis

For climate and agricultural analysis, several data sets stand out:

- **[NASA MODIS](https://modis.gsfc.nasa.gov/):** MODIS data provides invaluable information for tracking changes in vegetation, land surface temperature, and cloud cover, making it a cornerstone of climate and agricultural research.

- **[ESA Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2):** Sentinel-2's high-resolution multispectral imagery is particularly useful for monitoring crop health, land use changes, and assessing the impact of climate on agricultural productivity.

- **[ESA Copernicus Climate Change Service](https://climate.copernicus.eu/):** ESA's climate data sets, such as those related to temperature and greenhouse gases, are vital for climate scientists and agricultural researchers studying long-term trends and climate impacts on agriculture.

Exploring these data sets and their applications is a fascinating journey into the world of satellite imagery and its diverse uses across various domains.

#### Useful Links

- [Datasets Article](https://gisgeography.com/free-satellite-imagery-data-list/)
- [Satellite Imagery and Deep Learning](https://www.youtube.com/watch?v=CQlLa_UWncg)
- [Deep Learning with Satellite Imagery Workshop](https://www.youtube.com/watch?v=3Xn21RT-y7Y)
- [Introduction to Remote Sensing with Python](https://www.youtube.com/watch?v=gi4UdFsayoM)
- [An ML Approach to Satellite Imagery](https://www.youtube.com/watch?v=5PNnPagENxQ)

## Commonly Used Python GIS Libraries

### 1. **Geopandas**

[Geopandas](https://geopandas.org/) simplifies working with geospatial data by combining the capabilities of pandas (a popular data manipulation library) with geospatial data structures. It enables users to read, write, manipulate, and visualize spatial data effortlessly. Geopandas supports a variety of spatial formats and provides powerful geospatial operations.

### 2. **Folium**

[Folium](https://python-visualization.github.io/folium/) is a Python library for creating interactive maps. It leverages the Leaflet.js library and allows users to generate maps with markers, popups, choropleths, and more. Folium is an excellent choice for creating web-based interactive maps with minimal effort.

### 3. **Shapely**

[Shapely](https://shapely.readthedocs.io/en/stable/) is a library for performing geometric operations on spatial data. It provides tools for creating, analyzing, and manipulating geometries, such as points, lines, and polygons. Shapely is often used in conjunction with Geopandas for advanced spatial analysis.

### 4. **Pyproj**

[Pyproj](https://pyproj4.github.io/pyproj/stable/) is a Python interface to the PROJ library, which is used for coordinate transformations and projections. It allows users to convert coordinates between different geographic coordinate systems and perform cartographic projections.

### 5. **Rasterio**

[Rasterio](https://rasterio.readthedocs.io/en/latest/) is a library for reading and writing geospatial raster data formats. It provides easy access to the pixel values of raster datasets, making it essential for tasks like remote sensing analysis and terrain modeling.

### 6. **Cartopy**

[Cartopy](https://scitools.org.uk/cartopy/docs/latest/) is a library for cartographic projections and geospatial data visualization. It is particularly useful for creating maps with custom projections, adding geographic features, and annotating maps with labels and graticules.

### 7. **Basemap**

[Basemap](https://matplotlib.org/basemap/) is a toolkit for plotting 2D data on maps and for performing basic cartographic tasks. While it has been largely replaced by Cartopy in recent years, it remains a valuable choice for some mapping and visualization tasks.

### 8. **GeoAlchemy**

[GeoAlchemy](https://geoalchemy-2.readthedocs.io/en/latest/) is an extension to SQLAlchemy that simplifies working with geospatial databases, making it easier to integrate spatial data into your applications and perform spatial queries.

### 9. **GeoDjango**

[GeoDjango](https://docs.djangoproject.com/en/4.2/ref/contrib/gis/) is a geographic extension for Django, a popular web framework for Python. It allows developers to build geospatial web applications, manage geospatial data, and perform spatial queries efficiently.

### 10. **SentinelHub-Py**

[SentinelHub-Py](https://sentinelhub-py.readthedocs.io/en/latest/) is a Python library for accessing and processing Sentinel satellite data. It provides tools for querying and retrieving Sentinel-1 and Sentinel-2 imagery, making it valuable for remote sensing applications.

These Python GIS libraries, among others, form the foundation for geospatial data analysis and visualization in Python. Depending on your specific tasks and requirements, you may find one or more of these libraries invaluable in your geospatial projects.

In the following sections, we will dive deeper into these libraries and provide practical examples of how to use them in geospatial data analysis and visualization.

### Additional Geospatial Libraries

In addition to the Python GIS libraries mentioned above, there is a wealth of geospatial data and resources available for exploration. One valuable resource is the ["Awesome-Geospatial" repository](https://github.com/sacridini/Awesome-Geospatial), which curates a comprehensive list of links to geospatial datasets, tools, tutorials, and more. This repository serves as a valuable reference for those seeking diverse geospatial datasets and additional resources to enhance their geospatial data analysis skills. Exploring the datasets and tools listed in this repository can open up exciting possibilities for geospatial projects and research.

#### [Top Courses To Learn Geospatial Python ](https://www.youtube.com/watch?v=eXYg1WC93do&t=480s)

## An Introduction to Projections

Before delving into the world of map projections, it's essential to understand what projections are and why they matter in geospatial data analysis and mapping.

### What Are Map Projections?

Map projections are mathematical methods used to represent the three-dimensional surface of the Earth on a two-dimensional plane, such as a paper map or a computer screen. The Earth's surface is curved, and when we attempt to depict it on a flat surface, distortions inevitably occur. These distortions affect various properties, including distance, shape, area, and direction.

The choice of map projection depends on the specific needs of your project and what you want to emphasize or preserve. Each projection comes with its own set of trade-offs, and selecting the right one is crucial to accurately represent and analyze geographic data.

### Why Map Projections Matter

Map projections matter because they impact how we perceive and analyze spatial data. Different projections are suitable for different purposes, and the choice of projection depends on the specific needs of your project. Here are some key considerations:

### 1. **Preserving Properties:** 
Map projections are designed to preserve certain properties. For example, some projections aim to maintain accurate distances, while others prioritize preserving shapes or areas. Consider the properties you need to preserve in your analysis.

### 2. **Local vs. Global:** 
Some projections are better suited for local areas, while others work well for global views. The scale of your study area will influence your choice of projection.

### 3. **Distortion:** 
Understand the types of distortion introduced by each projection. Common distortions include Mercator projection's area distortion near the poles and Robinson projection's compromise on all aspects.

### 4. **Purpose:** 
Consider the purpose of your map. Are you creating a navigation map, a thematic map, or a visualization for a specific analysis? Each purpose may require a different projection.

## Common Map Projections

Several map projections are commonly used in geospatial data analysis:

### 1. **Mercator Projection:**

The Mercator projection is well-known for its ability to preserve angles and direction, making it suitable for navigation maps. However, it introduces significant area distortion, especially near the poles.

### 2. **Robinson Projection:**

The Robinson projection aims to balance area, shape, and distance distortions, making it a popular choice for world maps and thematic mapping.

### 3. **Lambert Conformal Conic:**

This projection preserves shape and local angles, making it suitable for regional mapping, especially in mid-latitude areas.

### 4. **Albers Equal Area Conic:**

The Albers projection minimizes area distortion and is often used for thematic maps that require accurate representations of regions.

### 5. **Winkel Tripel Projection:**

The Winkel Tripel projection provides a compromise between size and shape distortions and is commonly used for world maps.

### 6. **Web Mercator Projection:**

Web Mercator, used in web mapping applications like Google Maps, preserves shapes but significantly distorts areas at higher latitudes.

### Choosing the Right Projection

Selecting the right map projection for your project involves understanding the trade-offs between preserving properties and managing distortions. It's essential to consider your specific project requirements, study area, and goals. Many GIS software tools provide options to change map projections, allowing you to experiment and choose the one that best suits your needs.

#### Useful Links

- [How Map Projections Work](https://www.youtube.com/watch?v=NAzy4S4EOwc)
- [Map Projections in GIS](https://www.youtube.com/watch?v=jVn1uCuhO_4&t=1s)
- [Beginners Guide](https://www.youtube.com/watch?v=wlfLW1j05Dg)

## Introduction to Leveraging Dask and GeoPandas for Large Data Processing

Handling large geospatial datasets efficiently is a common challenge in geospatial data analysis. As datasets grow in size and complexity, traditional data processing tools may become inadequate. In such cases, leveraging the power of Dask and GeoPandas can greatly enhance your ability to process, analyze, and visualize large geospatial data effectively.

### The Challenge of Large Geospatial Data

Large geospatial datasets, such as high-resolution satellite imagery, LiDAR point clouds, or extensive vector datasets, often pose challenges in terms of memory and computational resources. These challenges can hinder data analysis and limit the scalability of geospatial projects. Common issues include:

- **Memory Constraints:** Loading and processing large datasets into memory can lead to memory exhaustion errors, especially when working with standard Python libraries.

- **Slow Processing:** Traditional single-core processing can be time-consuming and impractical for large datasets, resulting in slow analysis and visualization.

### Leveraging Dask and GeoPandas

### 1. **Dask: Scalable Computing**

[Dask](https://dask.org/) is a Python library that enables scalable and parallel computing. It extends Python's capabilities to work with larger-than-memory datasets by breaking them into smaller, manageable chunks that can be processed in parallel. Key benefits of Dask include:

   - **Parallelism:** Dask can distribute computations across multiple CPU cores or even clusters, significantly speeding up data processing tasks.

   - **Lazy Evaluation:** Dask's lazy evaluation allows you to build complex workflows without actually executing computations until necessary. This optimizes resource usage.

   - **Integration:** Dask integrates seamlessly with many existing Python libraries, including GeoPandas, NumPy, and Pandas.

### 2. **GeoPandas: Geospatial Data Handling**

[GeoPandas](https://geopandas.org/) is an open-source library for working with geospatial data in Python. It extends the capabilities of Pandas to handle geospatial data, making it an excellent choice for processing vector data. Key features of GeoPandas include:

   - **Vector Data Handling:** GeoPandas simplifies the management of vector datasets, including reading and writing various spatial file formats.

   - **Geospatial Operations:** GeoPandas supports geospatial operations like spatial joins, overlays, and buffering, enabling powerful geospatial analysis.

   - **Integration with Dask:** GeoPandas can work seamlessly with Dask, allowing you to process large geospatial datasets efficiently.

## Benefits of Combining Dask and GeoPandas

By combining Dask and GeoPandas in your geospatial data analysis workflows, you can:

- **Scale to Large Datasets:** Handle large geospatial datasets that exceed available memory resources, thanks to Dask's distributed computing capabilities.

- **Optimize Processing:** Achieve faster data processing by leveraging parallelism and lazy evaluation provided by Dask.

- **Perform Complex Geospatial Analysis:** Use GeoPandas for geospatial data manipulation and analysis while benefiting from Dask's scalability.

#### Useful Links

- [Intro to Dask](https://www.youtube.com/watch?v=nnndxbr_Xq4)
- [In-Depth Tutorial](https://www.youtube.com/watch?v=_u0OQm9qf_A)
- [Scaling Pandas Using Dask](https://www.youtube.com/watch?v=CVL8sTXT714)
- [Scaling Geospatial Data Analysis with Dask](https://www.youtube.com/watch?v=HB4OvZyrpl4)

## Hands-on Exercises

***Coming Soon***

The next section of this guide will dive into some useful Geospatial Data Science Use-Cases in Python to help you see practical examples of how real-world problems can be solved with Geospatial Data Analysis in Python.

**Use-Case 1:** Analyzing Soil Types in a Specific Agricultural Region

*Objective:* Create a Python script to retrieve and analyze soil data in a specific agricultural region using open-source geospatial datasets.

**Use-Case 2:** Predicting Crop Suitability using Soil Data and Machine Learning

*Objective:* Extend the soil analysis project to predict crop suitability for different areas within the agricultural region based on soil characteristics, climate data, and historical crop yield data.
