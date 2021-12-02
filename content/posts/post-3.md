---
title: "3 - The Degree Distribution"
date: 2019-11-01T09:34:43+01:00
draft: true
---

To get a little better understanding of the "interactions" going on between the wiki pages we will look at the **degree distributions** of the different characters, and let that decide how popular a character is. The degree distributions are deduced by the links from the different wiki pages. If a *character X* mentions (and thus links to) *character Y*, they will have one higher count on the out-degree and in-degree, respectively. Therefore, a character mentioned by many other characters will have a high in-degree, thus be considered popular. 

### Total degree distribution

![image description]({{< baseurl >}}/images/total_degree.png)

Here it is shown that most of the characters have a few (and even no) links to others. Only three characters have a degree that is higher than 200. One can assume that one of these is Harry Potter, most likely the one with the highest. Another one of the high-degree nodes may be Voldemort (Tom Riddle), as he is a central character and enemy of Harry. Or the other ones could be either one of Harry's friends, Ron or Hermione, or the master wizard Dumbledore. It is hard to tell, but don't worry, we will find out in another blog post!


### In-degree distribution

![image description]({{< baseurl >}}/images/in_degree.png)

The in-degree distribution only considers the amount of other characters who have mentioned a character. As expected, the highest value here is lower than the one in the total degree distribution, but that the distribution somewhat has the same distribution in terms of few nodes with high in-degree and many nodes with low. 


### Out-degree distribution

![image description]({{< baseurl >}}/images/out_degree.png)

The out-degree only accounts for the number of characters that a character mentions. As for in-degree, it is expected that the highest value is lower than the one from the total distribution. One could immediately think that the characters with the highest out-degrees are also the most central characters of the plot, but it may occur that a less relevant character just encounters with or mentions many others without being of such importance. 
