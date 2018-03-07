---
title: Exploring influence in networks
date: "2018-03-07T15:00:00+00:00"
slug: influence
categories:
  - R
images:
  - '/img/2018/influence.png'
---

I have just published an [interactive graphic][vis] showing the effect of ranking scientific communities with pairwise comparison models.
The visualisation is an interactive version of my (award-winning) *useR!2017* poster, [Ranking influential communities in networks][ricin].

[ricin]: http://selbydavid.com/2017/06/29/user2017/
[vis]: http://selbydavid.com/influence/

You can see how academic journals have been grouped into communities based on their citation behaviour, and notice the relative ranking within and between fields.
Occasionally journals don't do so well within their field but are influential outside it, and vice versa.
[Have an explore][vis] and see how your favourite fields/journals fare!

Some interesting feedback so far from domain experts:

- agronomy, or soil science, is split in two, with Brazilian journals (in Portuguese) appearing insular and cut off from the rest of the network.
- archaeology doesn't form a single field---rather it is two distinct sub-fields, with US-style anthropological archaeology falling under social sciences, whereas osteoarchaeology (digging up bones and stuff) lives under geosciences.

Other observations:

- statistics is great
- nobody understands particle physics
- the data, which are from 2015, also effectively 'predict' [*SpringerPlus*](https://springerplus.springeropen.com/) closing down in 2016
- Stata is used mainly by non-statisticians

The analysis was done using R and the visualisation created using D3.

- [Analysis](http://selbydavid.com/influence/analysis.html)
- [D3 code](http://selbydavid.com/influence/influence.js)

I am not very good at coming up with names for algorithmically-generated fields, so if you can think of more appropriate labels for communities, do let me know.
Feedback is very welcome!

[Click here][vis] to view the visualisation.
