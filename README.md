# Open Street Maps for Machine Learning 

## Introduction
Open Street Map is an open-source community collaboration where anybody is free to contribute to building the map of the world. Several organizations donate satellite and aerial imagery to the project and users can overlay vector data onto the map in addition to explanatory tags. However, exporting the data and working with the traditional datatype associated with Open Street Maps ( `.osm` ) can be difficult - while there are specific tools in Python and QGIS that can help download the data in a format that you need, there are attributes lost in translation. 
The purpose of this project is to better understand the .osm file format and be able to parse the exact information needed for my own use case, which is building feature data for Machine Learning projects. Additionally, this does not rely on any plugins or dark-box applications, so all the code is accessible and modifiable for your use case.

## Operations
Input: .osm files 
Output: Two separate datasets that contain a unique ID number, the date created, the primary and secondary category and the vector geometry (relies on Matlab Mapping Toolbox).
* Buildings 
* Roads

## Long Term Plan
Over time, I plan to build additional modules to extract certain features or items with relevant tags. Additionally, there are speed improvements / integration that I will make once this module has been tested more thoroughly. But for the moment, it suits my use case.