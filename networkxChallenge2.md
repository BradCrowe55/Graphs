#Networkx Challenge 2

##Question 1
Recreate the section of the Hollywood graph provided above in Python using the Network X tool.

``` python
import networkx as nx

my_graph = nx.Graph()

my_graph.add_node("Kevin Bacon")
my_graph.add_node("Michael Fassbender")
my_graph.add_node("James McAvoy")
my_graph.add_node("Lasco Atkins")
my_graph.add_node("Scott Cann")
my_graph.add_node("Richard Frice")
my_graph.add_node("Dravid Crow")
my_graph.add_node("Noomi Rapace")
my_graph.add_node("Vincent Cassel")
my_graph.add_node("Rasario Dawson")
my_graph.add_node("Idris Elba")

my_graph.add_edge("Kevin Bacon","Scott Cann")
my_graph.add_edge("Kevin Bacon","Lasco Atkins")
my_graph.add_edge("Kevin Bacon","David Crow")
my_graph.add_edge("Kevin Bacon","James McAvoy")
my_graph.add_edge("Kevin Bacon","Richard Frice")
my_graph.add_edge("Kevin Bacon","Michael Fassbender")
my_graph.add_edge("Scott Cann","Vincent Cassel")
my_graph.add_edge("Lasco Atkins","Noomi Rapace")
my_graph.add_edge("David Crow","Idris Elba")
my_graph.add_edge("James McAvoy","Vincent Cassel")
my_graph.add_edge("James McAvoy","Rasario Dawson")
my_graph.add_edge("Richard Frice","Rasario Dawson")
my_graph.add_edge("Michael Fassbender","Noomi Repace")
my_graph.add_edge("Michael Fassbender","Idris Elba")


```


##Question 2
Get the neighbours and degree for the actor Kevin Bacon.

**CODE:**
``` python
print("nx.neighbors(my_graph,'Kevin Bacon') prints the neighbours of a node")
print(nx.neighbors(my_graph,"Kevin Bacon"))

print("nx.degree(my_graph,'Kevin Bacon') prints the degrees of a node")
print(nx.degree(my_graph,"Kevin Bacon"))
```
**PRINT:**
``` python
nx.neighbors(my_graph,'Kevin Bacon') prints the neighbours of a node
['Richard Frice', 'David Crow', 'James McAvoy', 'Scott Cann', 'Lasco Atkins', 'Michael Fassbender']
nx.degree(my_graph,'Kevin Bacon') prints the degrees of a node
6
```

##Question 3
Investigate the Oracle of Bacon to find out more about the Kevin Bacon game and Bacon numbers.

``` python
```
