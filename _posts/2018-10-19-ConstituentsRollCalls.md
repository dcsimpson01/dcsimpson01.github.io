---
layout: post
title: "Constituents & Roll Call Votes"
author: "David Simpson"
date: "2018-10-19"
---

## Reproducing Clinton (2016)

I recently read Joshua Clinton's "Representation in Congress: Constituents and Roll Calls in the 106th House," a [research paper](https://www.jstor.org/stable/10.1111/j.1468-2508.2006.00415.x?pq-origsite=summon&seq=1#metadata_info_tab_contents) published in *The Journal of Politics* in 2006. Clinton (2006) studies the relationship between district level ideology scores and US House Representative's policy preferences as revealed through their voting behavior. Clinton (2006) finds that Republican House legislators in the 106th Congress (January 3, 1999 – January 3, 2001) are only responsive to their same-party district level constituents, whereas Democratic legislators are only responsive their nonsame-party district level constituents. Clinton's findings are puzzling. It is strange that Democratic legislators would be unresponsive to their same-party constituents.

Clinton (2016)'s definition of nonsame-party voters includes both independents and voters who identify with the opposite party of their elected representative. My hypothesis is that Clinton (2016)'s finding - that Democratic legislators are only responsive to their nonsame-party district level constituents - is contingent on how independent voters are classified. I plan to review his findings over the coming weeks. Clinton's replication data is available online through [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=hdl:1902.1/10573). 





## Revisiting Figure 1
To start the conversation, I have reproduced the four graphs Figure 1 of Clinton (2016). The graphs portray constituent survey data and representative ideal points - which measure's representative ideology using House roll call votes.



## Plot 1 - Representative Induced Preference and District Ideology


![](/images/2018-10-19-ConstituentsRollCalls_files/figure-html/Plot1-1.png)<!-- -->

The first graph plots legislator ideological voting scores against the average ideology scores of district constituents. The plot clearly shows that Democratic legislators represent districts that are on average more moderate and that have a wider range of ideological scores. See the table below for the district mean and variance scores. The graph also shows that there are Democratic districts with district ideology scores as conservative as some of the most conservative Republican districts. However, Democratic legislators in these districts do not vote as conservatively as Republican legislators representing similar districts.



| Districts   |      Mean  |  Variance   |
|-----|-----------|------------|
| ALL |  0.1260371 |  0.02973032 |
| DEM | 0.04677943 |  0.03409637 |
| GOP | 0.2010105 |  0.01412032 |

## Plot 2 - Representative Induced Preference and Same-Party District Ideology

![](/images/2018-10-19-ConstituentsRollCalls_files/figure-html/Plot2-1.png)<!-- -->

The second graph plots legislator scores against the average ideology of voters that self-identify with their legislator's political party. Compared to Figure 1, it is evident that same-party constituents have ideology scores that are on average more polarized (further to the left or right) than the average score of their district as a whole.

## Plot 3 - Distirct Same-Party Ideology and Average Ideology
![](/images/2018-10-19-ConstituentsRollCalls_files/figure-html/Plot3-1.png)<!-- -->

The third graph plots the ideological scores of constituents with the same-party of their representative against the district wide average ideology scores. Notice that that there are Democratic representatives whose districts have both conservative district ideology scores and right-of-center same-party ideology scores. In contrast, there are no Republican districts with left of center same-party ideology scores.

## Plot 4 - Distirct Ideology: Nonsame-Party and Same-Party

![](/images/2018-10-19-ConstituentsRollCalls_files/figure-html/Plot4-1.png)<!-- -->

The final graph plots the ideological scores of voters who do not identify with their legislator's party against the ideological scores of voters who do identify with their legislator's party. As expected, nonsame-party constituents are more conservative (liberal) than same-party constituents with Democratic (Republican) legislators.

Note: Graph 4 looks different than the fourth graph in Clinton (2016)'s Figure 1. In reviewing the replication code, I found that Clinton (2016) mislabeled the axes in the published paper.

## Hypothesis
My hypothesis is that Clinton (2016)'s finding - that Democratic legislators are only responsive to their nonsame-party district level constituents - is contingent on how independent voters are classified. Figure 1 shows that Democratic legislators represent districts with a wide range of ideology scores. However, the voting score of Democratic legislators is still more liberal than the voting score of Republican legislators with identical district ideologies. I suspect that Democratic legislators representing conservative districts are sensitive to the concerns of both same-party voters and independent voters. Therefore classifying independent voters as nonsame-party voters masks this effect. I look forward to posting about these findings as I continue along this replication project.

## References

Joshua D. Clinton. 2006. "Representation in Congress: Constituents and Roll Calls in the 106th House," Journal of Politics 68(2):397-409.

Joshua D. Clinton, 2009, "Replication data for: Representation in Congress: Constituents and Roll Calls in the 106th House", https://hdl.handle.net/1902.1/10573, Harvard Dataverse, V1, UNF:3:t+/VddUfFADKtOKo6VsarQ== [fileUNF]
