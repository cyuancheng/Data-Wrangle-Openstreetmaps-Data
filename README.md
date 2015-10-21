##Analyzing OpenStreetMap Data | Data Wrangling with MongoDB
- Author:  Chi-Yuan Cheng (cyuancheng AT gmail DOT com) 
- Last updated: May 1h  2015

### Information

I used data wrangling techniques, such as assessing the data quality for validity, accuracy, completeness, consistency, and uniformity, to clean and explore the OpenStreetMap (OSM) data in Santa Barbara County, CA, USA, 

### Summary

The interesting findings of OSM data in Santa Barbara were listed below:

1. The most popular cuisines: American
2. The most popular school: Lemonwood Elementary
3. The most popular fast food: McDonald's
4.  The top appearing amenity: parking
5. The most populated district: 93117
6. The top amenity for wheelchair accessible: fast_food (In-N-Out Burger)
7. Number of hospital or clinic in SB area: 18 

###Files

- **Project summary** ([md](ProjectSummary.md), [html](https://htmlpreview.github.io/?https://github.com/cyuancheng/Data-Wrangle-Openstreetmaps-Data/blob/master/ProjectSummary.html))  
  includes answers to questions, MongoDB queries and reference materials
- **Project report** ([ipynb]
(http://nbviewer.ipython.org/github/cyuancheng/Data-Wrangle-Openstreetmaps-Data/blob/master/OpenstreetMapData-SB.ipynb))	
	includes referenced code for data cleaning
- **Example OSM file** ([sample_SB.osm](sample_SB.osm))  
	Small example part from the map that I used (around 17.8 MB )

- **Lession 6 exercise**
	- [mapparser.py](lesson-6/mapparser.py) [Iterative parsing exercise]
	- [tags.py](lesson-6/tags.py) [Tag types exercise]
	- [users.py](lesson-6/users.py) [Exploring users exercise]
	- [audit.py](lesson-6/audit.py) [Improving street names exercise]
	- [data.py](lesson-6/data.py) [Preparing for database exercise]
	
- **Extra code** 
	- a python code to find the closest hospital using OSM data
	([ipynb](http://nbviewer.ipython.org/github/cyuancheng/Data-Wrangle-Openstreetmaps-Data/blob/master/FindHospital.ipynb))  
	
- **Certification**: ([here](certificate.pdf))



