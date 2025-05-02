# LondonStage

This project holds visualizations to detail and explain trends within the london theatre scene, specifically focusing on performances from 1670-1700. This timeperiod showed a large resurgence in performances with the introduction of women being allowed to perform. 

## System Structure

### _data

Stores processed CSV files that hold the public data used for our visualizations. One file is missing due to file upload limits, the raw London stage dataset. While not needed for any visualizations, it can be used to see how others were made. It can be downloaded [here](https://londonstagedatabase.uoregon.edu/downloads/LondonStageCSV.zip). The current files are: 

- Actresses_1670-1700.csv : The digitized dataset from the book [The First English Actresses: Women and Drama 1660-1700](https://www.cambridge.org/core/journals/renaissance-quarterly/article/abs/elizabeth-howe-the-first-english-actresses-women-and-drama-16601700-cambridge-cambridge-university-press-1992-12-pls-xiv-226-pp-5995-cloth-1795-paper/0B7FBE36C4483A6A4F134872C1645AAB)
- DataViz_monstrosity.csv : Outline of performances and their political themes
- theatre_count&location.csv : A count of each theatre in the London stage dataset and how many total performances occurred.

### docs
Holds a single jupyter file that is used to generate all visualizations aside from the map view, which is linked bellow. 

### Visualizations
Holds the png output of all of the visualizations

#### Connection map between Actresses and Dramatists
![Connection](https://github.com/conchobha/LondonStage/blob/main/Visualizations/Dramatist_Actress_connections.png?raw=true)
#### Connection map between Actresses
![Connections](https://github.com/conchobha/LondonStage/blob/main/Visualizations/ActressConnections.png?raw=true)
#### Network map of actresses
![Connections](https://github.com/conchobha/LondonStage/blob/main/Visualizations/ActressNetwork.png?raw=true)
#### Bar graph of Roles
![BarGraph](https://github.com/conchobha/LondonStage/blob/main/Visualizations/occurrences.png?raw=true)
#### Line graph of 'Young Girl' roles
![LineGraph](https://github.com/conchobha/LondonStage/blob/main/Visualizations/YoungGirlRolesOverTime.png?raw=true)
#### [Map of performances](https://public.flourish.studio/visualisation/22922060/)
