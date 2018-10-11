----
layout: post
title: Rushing Yards Post
---

Here's a quick post using NCAA rushing data. The data was downloaded from the [NCAA website](https://www.ncaa.com/stats/football/fbs/current/individual/469) on October 11, 2018.

Below is just a simple graph showing the relationship between rushing attempts and rushing yards by position. I'll do something more interesting with the data in a future post. I also included the R code in case you are interested.

``` r
ggplot(data, aes(RUSH,RUSH.YDS,col=factor(POSITION)))+
  geom_point()+
  labs(x ="Attempts", y= "Yards", title = "Rushing Attempts and Yard by Position", color="Position")
```

![](2018-10-11-RushingYards_files/figure-markdown_github/graphs-1.png)