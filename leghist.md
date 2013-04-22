---
layout: wide
title: Legislative history and plagiarism
---

Legislation can pose a formidable barrier to study the politics of legislating. It's rare that we get a final bill or resolution that cleanly lays out which committee, party, or legislator (let along which lobbyist) wrote the language in each section. Reconstructing that map from the legislative outcome to its original sources in draft legislation, amendments, and other documents is laborious, prone to error, and hard to scale. 

I wrote the `leghist` package for [R](http://r-project.org) to address this problem. `leghist` capitalizes on the insight that *legislating is plagiarism*: a final bill is nothing more than a set of verbatim, unattributed quotations from the legislative record of drafts and amendments. If we have both the final bill and all the documents in the legislative record, we should be able to use computational tools for plagiarism detection to uncover which drafts and amendments succeeded, and which failed. And since we know who wrote those drafts and amendments, building this map gives us insight into the original question: who wrote what, and when. 

We can go beyond that, though, to understand not just who, what, and when, but *which policies*. If we model the policy domains covered by a new law as a set of topics, we can draw on [topic models](http://www.cs.princeton.edu/~blei/topicmodeling.html) to uncover, using the language of legislation itself, the policy domains governed by a bill. 

We can see an example below. In 2008, the European Union set out to reform its rules for adopting renewable energy. Debates over how much renewable energy each country should adopt, whether biofuels should count as renewable energy, how renewable energy should be integrated into the electricity grid, and other issues ensued. The final bill passed in early 2009. 

From the figures below, we can see that the European Commission wrote most of the language in most of the policy domains in the final bill. The Parliament, though it tried to amend most of the bill to make it more environmentally-friendly, had relatively limited influence. 

{% image plot_rese_2007_origin_heatmap.png %}
    title: Influence over legislative outcomes in Europe's 2008 energy policy reforms
{% endimage %}


`leghist` makes these insights, which could take days of careful work to uncover by hand, straightforward. `leghist` is still in development, but you can get the code at [github](https://github.com/markhuberty/leghist). 
