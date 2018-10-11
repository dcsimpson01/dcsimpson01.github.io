---
layout: post
title: "Rushing Yards"
date: 2018-10-11
---

## Rushing Yards through October 9, 2018

Here's a quick post using NCAA rushing data. The data was downloaded from the [NCAA website](https://www.ncaa.com/stats/football/fbs/current/individual/469) on October 11, 2018.

Below is just a simple graph showing the relationship between rushing attempts and rushing yards by position. I'll do something more interesting with the data in a future post. I also included the R code in case you are interested.

``` r
ggplot(data, aes(RUSH,RUSH.YDS,col=factor(POSITION)))+
  geom_point()+
  labs(x ="Attempts", y= "Yards", title = "Rushing Attempts and Yard by Position", color="Position")
```

![](dcsimpson01.github.io/_posts/2018-10-11-RushingYards_files/graphs-1.png)
Test
![](dcsimpson01.github.io/_posts/2018-10-11-RushingYards_files/graphs-1.png)
Test
![](https://github.com/dcsimpson01.github.io/_posts/2018-10-11-RushingYards_files/graphs-1.png)

Test again
<div>
	<img src="dcsimpson01.github.io/_posts/2018-10-11-RushingYards_files/graphs-1.png" alt="Image", width="50%" height="50%"/> 
</div>
