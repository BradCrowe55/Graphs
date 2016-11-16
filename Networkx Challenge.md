#Networkx Challenge

##Question 1
Create a networkx graph using the data from this adjacency matrix.

| ||1|2|3|4|5|6|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|**1**|0|1|1|1|0|0|
|**2**|1|0|1|0|0|0|
|**3**|1|1|0|1|1|1|
|**4**|1|0|1|0|0|0|
|**5**|0|0|1|0|0|0|
|**6**|0|0|1|0|0|0|

``` python
my_graph.add_node("1")
my_graph.add_node("2")
my_graph.add_node("3")
my_graph.add_node("4")
my_graph.add_node("5")
my_graph.add_node("6")

my_graph.add_edge("1","2")
my_graph.add_edge("1","3")
my_graph.add_edge("1","4")
my_graph.add_edge("2","3")
my_graph.add_edge("3","4")
my_graph.add_edge("3","5")
my_graph.add_edge("3","6")
```


##Question 2
Find out how many neighbours node 3 has?

``` python
nx.neighbors(my_graph,'3') prints the neighbours of a node
['4', '5', '2', '6', '1']
```


##Question 3
Find out how many degrees does node 2 have?

``` python
nx.degree(my_graph,'2') prints the degrees of a node
2
```
