---
title: "4 - Centrality of Harry and his Friends"
date: 2018-11-01T09:34:43+01:00
draft: true
---


Harry and his two sidekicks, Hermione and Ron, are intuitively the most central characters, as the stories revolve around them. Let's see if the intuition is reflected in the wiki pages!

The degrees of the three friends are as follows:

| **Character**     | **Total degree** | **In-degree**     | **Out-degree**     |
| ---        |    :----: |          :---:| :----:|
| Harry Potter    | 294       | 178   | 116   |
| Hermione Granger  | 226        | 138      | 88   |
| Ron Weasly      |  157        | 58      | 99   |
 
From the distribution of all total degrees of the characters in [last post](https://jennyjyu.github.io/socialgraphs-projectB/posts/post-3/) (the red plot), it is clear that Harry is the one with the highest degree. This does make sense as he is the main character. Hermione has a degree of 226, meaning that she is the character with the third highest degree. Ron is more among some other characters with a degree of 115. 

![image description]({{< baseurl >}}/images/venner.png)

### How important are his friends?

One of the questions from Project A was *"How important are his friends?"*. Now we know that Hermione is apparently quite important, as she has a high total degree, whereas the majority is from the in-degree. Ron, on the other hand, is sadly not as important. His total degree is lower than the other two, in addition to having most of it coming from his out-degree. The latter meaning that his degree is mostly due to him mentioning many other characters. 

Still, they are both among the upper part of the degree distribution. Hence, even though they are not *as* important as each other and Harry, they do still play a central part. 


### Other centrality measures

To get an even better understanding of the importance of Harry and his friends, there are more centrality measures to look at. In the table below, the closeness centrality, betweenness centrality and eigenvector centrality for each of the three characters are presented:

| Character        	| Closeness 	| Betweenness 	| Eigenvector 	|
|------------------	|:---------:	|:-----------:	|:-----------:	|
| Harry Potter     	|   0.902   	|    0.196    	|    0.272    	|
| Hermione Granger 	|   0.752   	|    0.074    	|    0.246    	|
| Ron Weasley      	|   0.564   	|    0.041    	|    0.124    	|

The **closeness** is defined so that if a vertex is close to every other vertex, then the value is larger than if the vertex is not close to everything else [[source]](https://www.sciencedirect.com/topics/computer-science/closeness-centrality#:~:text=require%20many%20steps.-,Closeness%20centrality%20is%20a%20measure%20of%20the%20average%20shortest%20distance,distance%20to%20all%20other%20vertices). As seen in the table, it shows that Harry is closer to the other nodes in the entire network, in comparison with Hermione and Ron. As for degree, their order is decreasing from Harry to Hermione to Ron. 

To calculate **betweenness**, each node receives a score based on the number of shortest paths that pass through the node. Nodes that more frequently lie on shortest paths between other nodes will have higher betweenness centrality scores [[source]](https://neo4j.com/docs/graph-data-science/current/algorithms/betweenness-centrality/#:~:text=Betweenness%20centrality%20is%20a%20way,of%20nodes%20in%20a%20graph.). Again, the order of the characters with respect to their betweenness score is the same. For betweenness there is also a larger gap between Harry's value and the other two, compared with closeness. 

The **eigenvector** is a measure of the influence of a node in a network. A high eigenvector score means that a node is connected to many nodes who also have high scores [[source]](https://en.wikipedia.org/wiki/Eigenvector_centrality#:~:text=In%20graph%20theory%2C%20eigenvector%20centrality,a%20node%20in%20a%20network.&text=A%20high%20eigenvector%20score%20means,who%20themselves%20have%20high%20scores.). For this measure, Harry and Hermione's values are closer. Ron's value still differs more from the others.
