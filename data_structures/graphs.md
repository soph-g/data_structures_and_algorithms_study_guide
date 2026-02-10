# Graphs

## Prerequisites

I would suggest looking at [Arrays](./arrays.md) and [Hash Tables](./hash_tables.md) before jumping into Graphs, as these data structures can be used to represent graphs.

[Trees](./trees.md) are a type of graph, but you don't need to understand trees before looking at graphs.

## Introduction

Graphs are extremely useful for representing relationships between things. They are comprised of:

* Nodes (also called Vertices) which represent each item in the graph, and
* Edges, which represent connections between nodes.

!(undirected graph)[../images/undirected_graph.png]

Graphs can be *undirected* which means the relationship between two nodes does not have a direction of travel or hierarchy, or *directed*. In a directed graph, edges represent not just a link between two nodes but also the nature of that link e.g. parent & child.

Graphs can also be:
* *cyclic* - meaning there is, or could be, a cycle of nodes connected to eachother. You'll need to be careful about spotting cycles and not getting stuck in infinite loops when traversing graphs
* *acyclic* - meaning there is no cycles of connected nodes.
* *weighted* or *unweighted* - in weighted graphs, each edge has a 'weight' that represents something about the relationship between the two nodes - for example the distance between two locations. 

It's common to be required to traverse graphs, which means navigating from some starting point to find another specified node (which may or may not be in the graph).

The internet could be seen as a graph, each web page is a node and each link between pages is an edge.

## Study Areas

- [ ] Draw a digram of a graph that is directed, and acyclic.
- [ ] Draw an undirected graph that is cyclic
- [ ] Build your own implementation of a graph data structure
- [ ] Turn one of your diagrammed graphs into an Adjacency List, using a Hash Table
- [ ] Turn one of your diagrammed graphs into a Edge List, using an Array.

## Practice Problems

Most introductary graph problems involve either Depth-First Search, or Breadth First Search, so you'll need to cover these before you can tackle graph-based questions.

## Resources

[Interview Cake article on Graphs](https://www.interviewcake.com/concept/python/graph)

## Next Steps

Definitely get stuck into [Depth First Search](../algorithms/depth_first_search.md) and [Breadth First Search](../algorithms/breadth_first_search.md), so you can start practicing working with graphs.

If you haven't already covered [Trees](./trees.md) then it's a good time to look at this topic.
