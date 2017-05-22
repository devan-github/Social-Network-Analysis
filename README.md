# Social Network Analysis

## Data
In this assignment you will be using data from:

Representing Classroom Social Structure. Melbourne: Victoria Institute of
Secondary Education, M. Vickers and S. Chan, (1981)

Available from the Index of Complex Networks ([ICON](https://icon.colorado.edu/#!/))

The data were collected by Vickers from 29 seventh grade students in a school in Victoria, Australia. Students were asked to nominate their classmates on a number of relations including the following three "layers":  

1. Who do you get on with in the class?  
2. Who are your best friends in the class?  
3. Who would you prefer to work with?  

You have a data set for each of these questions, please compete the following tasks.

### Data Wrangling

Manipulate each of the data sets so that it is suitable for building a social network using iGraph.  

### Visualize the Networks

Create a graph for each of the data sets, are the graphs directed or undirected? Visualize each of the graphs you have created and color the nodes according to gender.


### Simple structures

Count the number of dyads and the number and type of triads using the following commands.
```{r}
dyad_census()
```
[Documentation](http://igraph.org/r/doc/dyad_census.html)

```{r}
triad_census()
```

[Documentation](http://igraph.org/r/doc/triad_census.html)

Do these metrics tell you anything about the networks?

### Cliques

Answer the following questions using the [clique functions](http://igraph.org/r/doc/cliques.html)

What is the size of the largest clique(s) in each of the three networks?

```{r}

```

Which nodes/vertices are in the largest cliques for the three networks? Is there much overlap?

```{r}

```

How many **maximal cliques** are there in each of the networks?

```{r}

```

#Components & Cutpoints

Find the cutpoints (articulation points) for each of the three networks you generated. What does this tell you about he graphs? Does what you find match a visual exploration of the networks?

```{r}
articulation_points()
