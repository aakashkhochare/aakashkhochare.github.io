---
title: 'A Commentary on the Intricate Liabilities of Autonomous Vehicles'
date: 2018-07-15
permalink: /posts/2018/07/autonomous-cars-and-liabilities/
tags:
  - autonomous cars
  - smart cities
  - internet of things
---

March 2018 was a month that had a deep impact on how the society looks at technology. The Cambridge Analytica scandal and, the fatality of a pedestrian after being mowed down by a self-driving Uber together spelled the dark side of technology. While the two incidents might seem disjoint, I'd say they have a common theme, a corporate giant exploiting the relatively fuzzy legalities governing upcoming technological advances. The former got widespread media coverage, while the latter seemed to be brushed under the carpet under the excuse of *accidents happen*. And yes, accidents do happen, but there's a thin line between accidents and negligence, which will be discussed as a part of this post. Note that I will quote facts from NTSB's [preliminary report](https://www.ntsb.gov/investigations/AccidentReports/Reports/HWY18MH010-prelim.pdf), which by nature can change based on further findings.

When I first heard of the accident, my reaction was no different from any tech enthusiast's. Yes, the technology is new, it's not perfect, and, *accidents happen*. While the holy grail of autonomy might be zero road fatalities, the community understands that the short-term goal is to minimize them. It was the NTSB report that made me question the design choices made by engineers at Uber. Here's now the report recounts the incident. The pedestrian crossed on a dark patch of the road and, reportedly had smoked marijuana. The car detected an object 6 seconds prior to the impact. The detection was continuously refined till 1.3 secs before the impact when the system decided an *emergency brake maneuver* was required. This was a feature disabled to avoid *erratic vehicle behaviour*. So, 1.3 secs before the impact, the driver was handed control and was expected to avoid impact. 

Uber and many other self driving car manufacturers aim for what is called as Level-4 autonomy. In layman's terms, between Levels 0-4, the driver may be expected to take control of the vehicle. Here's what scares me the most, at a point where impact is eminent, the car manufacturer may just hand me the wheel and make me liable for the crash. 1.3 sec before the impact, I might as well get a copy of the *Geeta*, it'll be equally pointless. These cars rely on areas such as *deep learning* that present no mathematical tools for correctness verification. Heck, as a colleague of mine shows in this [paper](https://arxiv.org/abs/1712.03390), they are even susceptible to ill formed inputs. What's funnier is that while humans, who are supposed to intervene with reflexes that may humble even Michael Schumacher, have to go through a driving test, these AI powered assistants don't.

But the liability question runs deeper than just direct human intervention and has a lot of subtleties. Even if we achieve Level 5 automation, where the passenger may even sleep, the *human element* cannot be taken away from this problem. Say a manufacturer finds and fixes a software bug, thereby rolling out an OTA update. When is the manufacturer not liable for accidents caused by the bug? 1 min after the OTA release? It's unreasonable to expect everyone to update immediately. 1 year after the OTA release? But it's been a year now, surely the customer must have updated to the latest software. Well, even iOS generally shows an adoption rate of around 50% in the first few weeks. That's 50% of cars not running the latest software. Forced updates? I am sure people will jailbreak cars too. So, what should the legislation be?

I believe we cannot be underprepared for automation. Governments will need to work closely with academia and researchers in general to determine what's acceptable and what isn't. Eventually, we'll find that *smart cities need smarter governments*. 

