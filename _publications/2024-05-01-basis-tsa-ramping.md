---
title: "Enhancing time series aggregation for power system optimization models: Incorporating network and ramping constraints"
collection: publications
category: manuscripts
permalink: /publication/2024-05-01-basis-tsa-ramping
excerpt: 'Enhanced Time Series Aggregation for energy system models using an a-posteriori approach based on sets of active constraints.'
date: 2024-05-01
venue: 'Electric Power Systems Research'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Cardona-Vasquez, D., Klatzer, T., Klinz, B., Wogrin, S. (2024). &quot;Enhancing time series aggregation for power system optimization models.&quot; <i>Electric Power Systems Research</i>. 230(110267).'
---

In this paper, we extend a recently developed Basis-Oriented time series aggregation approach for aggregating input-data in power system optimization models which has proven to be exact in simple economic dispatch problems. We extend this methodology to include network and ramping constraints, for the latter, to handle temporal linking, we developed a heuristic that, in its current version, relies on the dual solution to find a partition of the input data, which is then aggregated. Our numerical results, for a 3-bus system, show that with network constraints only, we reduced the number of hours needed for an exact approximation by a factor of 1747, and a factor of 12 with network and ramping constraints. Moreover, our findings suggest that in the presence of temporal linking, aggregations of variable length must be employed to obtain an exact result (i.e., the same objective function value in the aggregated model) while maintaining the computational tractability. Our findings also imply that better performing aggregations do not necessarily correspond to commonly used lengths like days or weeks; additionally, we also prove that this input-data partition, based on the dual information, is always possible for these models independent of their size.