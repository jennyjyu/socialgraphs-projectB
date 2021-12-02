---
title: "2 - The Attribute Distributions"
date: 2020-11-01T09:34:43+01:00
draft: true
---

To get a better understanding of how the wiki is set up, and maybe get a better understanding of coming results, it is interesting to look at the different distributions within the data set. 

### Species

Let's look at the species first!

![image description]({{< baseurl >}}/images/plot_species.png)

As seen, most of the characters who are important are categorized as **humans**. The wiki does not distinguish between if a wizard is a muggle-born, half-blood or pure-blood when categorizing them as human. As most of the plot of the Harry Potter story is about the wizards going to Hogwarts, this makes sense. They do encounter some different species now and then, but all the main characters are (or were originally) humans. 

It is important to note that even though many of the species only have one occurrence in the data, it does not mean that it is the only one of its kind in the Harry Potter universe, but rather the only one of their species that has a big enough role to be named, and counted as a character. 


### Gender
The gender distribution is less diverse:

![image description]({{< baseurl >}}/images/plot_gender.png)

Harry Potter is a male-dominated universe, just as in the universe of computer science. It is reasonable to assume that those characters who have the gender **unknown** are not of the human species, but of a species where both the name and species are not explicitly defined by J.K. Rowling, *or* define themselves as a gender-fluid. The exact reason why can, sadly, not be decided by the distribution, so we just have to keep speculating.


### Houses

![image description]({{< baseurl >}}/images/plot_houses.png)

The distribution of the Houses from which the characters belong to is interesting. Surprisingly many characters do not have a House related to them, which on second thought, might make sense. As the almost the only characters that can be related to a House are **humans**, all the characters who are not, will have **unknown** as their value. Additionally, many human characters are mentioned without a context of the House they belong to, such as members from the Ministry of Magic.

After looking at only humans, we get the distribution looking like this:

![image description]({{< baseurl >}}/images/plot_houses2.png)

The majority of counts removed are from **unknown** House. Some are removed from the different Houses, as four of the characters belonging to Houses were not human. Still, the **unknown** dominates, for the same reason as mentioned before with many humans not mentioned in the context of belonging House. Maybe they even went to another school?

If we only look at the characters who *do have* a House related to them, i.e. excluding the **unknown** ones, we get the following distribution:

![image description]({{< baseurl >}}/images/plot_houses3.png)

Now this looks more representative! As expected, most of the mentioned characters belong to **Gryffindor**, which is Harry and his friends' House. Their rivaling House, **Slytherin**, is also well represented.