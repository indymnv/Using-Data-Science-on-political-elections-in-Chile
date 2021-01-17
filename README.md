# Using-Data-Science-on-political-elections-in-Chile

I carried out this project at the Pontificia Universidad Católica de Valparaíso with two other classmates. 
In the first data science course taught by the School of Industrial Engineering, the professor in charge was Victor Leiva PH.D. 
The analyses were then presented in an academic poster at the "II international workshop on Data Science" held in the same city. 
Although We made some scripts in R to preprocess the data, I could not rescue them from my old pc. Regardless, 
I try to provide all possible resources if someone wants to know more or push their tests or ideas.

This work is about political trend in different areas in Chile, we focus our research in participation and trends in Santiago (Capital) 
and compare that city with the rest of areas in this country.

### About Data

The data is provided by DataChile (https://es.datachile.io/) there you can find several other datasets about Chile. The description of dataset is as follow:

Name | Description
------------ | -------------
comuna_id | id to identify a city (int)
candidato_id | id to identify a presidential camdidate (int)
votos_candidato | total number of votes the candidate obtained (int)
electo | 1 if the respective candidate won; 0 in other case (binary)
year | year of the election (int)
election_id | id of election (int)
candidato_name | candidate's name (string)
region_id | id of state (int)
region_name | name of the state (string)
comuna_name | name of the city (string)

### Machine learning model (K-means)

k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which 
each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a 
partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances,
which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. 
For instance, better Euclidean solutions can be found using k-medians and k-medoids. (Wikipedia)

The objective of the methodology is to partition or segment a set of data into different groups that may or may not be disjoint, which are formed from certain variables,
and since the groups are not defined a priori, the results are obtained from of the interpretation of the groups formed and their composition

### Stack

* R (preprocess and first experiments)
* Tableau (For better visualization)
