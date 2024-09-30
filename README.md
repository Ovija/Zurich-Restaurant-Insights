# Zurich Restaurant Insights
## Project Overview

This project was developed as part of a NoSQL module using MongoDB. The aim is to analyze and visualize the culinary diversity of restaurants in Zurich, Switzerland. The project involves extracting restaurant data from Zurich's Open Data platform, transforming it for analysis, and exploring various insights using NoSQL database technology (MongoDB).

## Dataset

The dataset used in this project contains information about 515 restaurants in Zurich and was obtained from the Zurich Open Data Platform. The dataset includes fields such as:
*  Address
*    Category
*    Geo-coordinates
*    Description
*    Copyright holder

## ELT (Extract, Load, Transform) Process

    DB Setup: A MongoDB instance was used to store and manage the restaurant data.
    Extract: The data was extracted using an API from the Zurich Open Data platform.
    Load: The dataset was loaded into MongoDB for further processing.
    Transform: Various transformations were applied, including:
        Handling missing information
        Removing redundant fields
        Creating new attributes
        Renaming fields for consistency

## Data Analysis

The following analyses were conducted:

    Types of Restaurants: A breakdown of the various restaurant categories in Zurich.
    Cuisine Diversity: An exploration of the variety of cuisines available.
    Geospatial Analysis: Mapping restaurant locations using geo-coordinates.
    Vegan Restaurants: Focused analysis on vegan restaurants in Zurich.
    Open Days: Insights into the operational days of the restaurants.
