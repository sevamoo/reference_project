# Reference Project
***

- The encoding we used for Points Of Interests (POIs) for this study are [here](https://github.com/sevamoo/reference_project/blob/master/data/poi_types.csv)


- [The 50 most frquent POIs in Europe](https://github.com/sevamoo/reference_project/blob/master/data/europe_POIs_sorted.csv) 


- [The 50 most frquent POIs in North-America](https://github.com/sevamoo/reference_project/blob/master/data/north-america_POIs_sorted.csv) 


## Free variables to play with: 
```
- POIs: How many most frequents? Or just choosing some of them manually?
- Radius for search?
- What is the similarity threshold to choose an area as a candidate? Now I chose them manually.
```



***
## Results:


### My quick impression (not necessarily corect)
```
30 features and 300 meters in Europe finds very similar locations in terms of distance to the main rail road node similar to the case in Hardbrücke, but in North American in my opinion 500 meters with 50 features gives better results. 
```


```
**Warning:** The interactive maps could be confusing and you might realize spending time just looking from one point to another point. :)
```

```
Interactive maps show the clusters of points. If you reach to the a single point, click on the circle and there is a link in the popup menue taking you to 3D Google maps.
```


1- Radius: 300 meters and 30 most frequent Points Of Interests (POIs) 
- [Interactive map](https://sevamoo.github.io/reference_project/mapboxgl_cluster30_300.html)
- [CSV file](https://github.com/sevamoo/reference_project/blob/master/data/similarpoints_all_47.38675740000001_8.516673500000024_r_300_no_keys_30_no_points_5838.csv)

2- Radius: 500 meters and 30 most frequent Points Of Interests (POIs) for Europe and 50 for north-america
- [Interactive map](https://sevamoo.github.io/reference_project/mapboxgl_cluster30.html)
- [CSV file](https://github.com/sevamoo/reference_project/blob/master/data/similarpoints_all_47.38675740000001_8.516673500000024_r_500_no_keys_30_no_points_1300.csv)


3- Radius: 500 meters and 50 most frequent Points Of Interests (POIs) 
- [Interactive map](https://sevamoo.github.io/reference_project/mapboxgl_cluster50.html)
- [CSV file](https://github.com/sevamoo/reference_project/blob/master/data/similarpoints_all_47.38675740000001_8.516673500000024_r_500_no_keys_50_no_points_2574.csv)

****






