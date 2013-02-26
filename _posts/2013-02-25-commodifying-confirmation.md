---
layout: post
title: Commodifying confirmation bias
---

Big data has already delivered improvements to both our online and offline lives. It promises still more.[^fn-norvig] But two trends currently threaten to derail this progress. This note considers one: the recent and popular fallacy of believing that the promise of big data can be commoditized, mass produced, and packaged.[^fn-sap] Nothing threatens the promise of a new wave of insights from data more than this fundamental error. 

The urge to commoditize big data rests on the mistaken impression that we can commoditize insight. Today's big data debate has rapidly conflated "useful" and "big", elevating "big" above data and "big data" above informed, insightful, and valid analytics. It proposes to substitute software for people, and in doing so mask the complexity of the world under the deceptive simplicity of tools.

Why might we believe that we could commoditize this kind of training? Because the alternative is expensive. One article, probably apocryphal, suggested that a good data scientist in San Francisco could command an average salary around $200,000 or more.[^fn-data-science-salary] [McKinsey & Company](http://www.mckinsey.com/features/big_data) estimates that the US is currently short 150,000 people with data science skills. Perhaps it's not quite that bad. But well before that point, any rational capitalist starts to think "maybe I can substitute capital for labor!"; or "tools for people!". And now they're doomed. 

Why doomed? Because our good capitalist has mistaken those expensive Ph.D.s and their esoteric training for fleshy machines who run regressions. That's a fundamental error. Data scientists aren't useful because they can program in R.[^fn-drew-conway] They're useful because their esoteric training beat into an unnatural bias against believing their own results. Humans are pre-programmed to see patterns in the world, and to choose those patterns that comply with their subjective biases.[^fn-kahneman] With "big enough" data we can find patterns confirming any bias we please. We can convince ourselves the sky is green, or (more recently) that Mitt Romney is about to be president. For that we don't need expensive and hard-to-find PhDs. Any recent college grad would do. 

But that's not what we want of big data. Instead, we want data science to be both an enabler of new business models, and a guard against fooling ourselves about the true state of the world. For that goal, we need people who, to the extent possible in a jumped-up African plains ape, have been conditioned to recognize that bias in themselves, and fight it. That bias, left untouched, eventually finds you like like Karl Rove, melting down in prime time, a victim of your own myopia. 

That's why most "data science" jobs today go looking for people with PhDs in statistics, machine learning, and similar fields.[^fn-phd] Graduate training in one of these disciplines is basically a multi-year process of having the innate human tendency towards confirmation bias beaten out of them. It's retraining a person to the point that where their first response to a favorable result isn't joy, but skepticism. It's turning them into their own worst, harshest audience. Good data scientists come out the other end of this rather unnatural and at times deeply unpleasant process with a very healthy degree of self-doubt. A very smart friend of mine once remarked with a pained look on his face "statisticians, man, *they don't believe anything*". The only thing that tempers the doubt is the knowledge that you have the skills to interrogate the result until it holds up, or falls apart.[^fn-elections]

Commoditization automates the tools and strips away the insight. In doing so, commodotization tempts us to believe that insight and tools are exchangeable. That intellectual error leads, almost certainly, to a search for results that confirm our own biases about the world, rather than those that teach us something new.[^fn-why-false] In doing so, it trivializes the challenge of big data, and undermines its promise.

Does avoiding commodotization fix this? No. Organizations still matter, a problem I take up [here]({% post_url 2013-02-20-big-data-cudgel %}).

[^fn-norvig]: Peter Norvig's ["The Unreasonable Effectiveness of Data"](http://research.google.com/pubs/archive/35179.pdf) remains the best statement of the broad promise of ever-more data for delivering new analytics, produces, and services that continue the improvements we've already enjoyed. 

[^fn-sap]: Chirag Mehta's [recent essay](http://prsm.tc/4XkMym) on commoditized data science is so perfect a version of this mindset one wonders if it's caricature. Commoditizing data science is nothing more than facilitating confirmation bias and spurious correlation as a business practice.

[^fn-phd]: A quick (and admittedly unscientific) search on [StackExchange Careers](http://careers.stackoverflow.com/jobs?searchTerm=data+science+phd&location=) indicates that 100% of the jobs advertised as "data science" appear to view a PhD as either a requirement or a plus. A similar search on [Indeed.com](http://www.indeed.com/jobs?q=data+scientist+phd&l=san+francisco%2C+CA&radius=25) for San Francisco-based job posting suggests that about a third (214 of 726) list PhD in the job title.

[^fn-data-science-salary]: [Various articles](http://gigaom.com/2012/02/17/big-data-skills-bring-big-dough/) claim that salaries for skilled data scientists regularly exceed $100,000 and run as high as $500,000 for those in high demand.

[^fn-elections]: Even then, sometimes we fall down. Predicting elections with Twitter has become a cottage industry. A lot of people have achieved superficially impressive results--75% or better. But as [Daniel Gayo-Avello](http://arxiv.org/abs/1204.6441) has pointed out, the real benchmark here isn't, say, 50% in a two-candidate race. It's usually the incumbent win rate (which in the US is about 90% or so). So all those smart algorithms were computationally expensive, inferior predictors. 

[^fn-drew-conway]: Drew Conway's [data science venn diagram](http://www.drewconway.com/zia/?p=2378) makes this point succinctly.

[^fn-kahneman]: Daniel Kahneman's [work](http://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374275637) on heuristics and biases in decision-making illustrates this problem nicely.

[^fn-why-false]: See here the classic ["Why most published research findings are false"](http://www.plosmedicine.org/article/info:doi/10.1371/journal.pmed.0020124). Most statistical training over the last decade has been targeted explicitly at the biases that have led to such problems. 
