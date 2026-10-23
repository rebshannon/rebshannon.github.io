---
layout: page-fullwidth
title:  "Bubbles and Hypersonics"
subheadline:  PhD Thesis
teaser: "Improving cavitation modeling to inform hypersonic vehicle design"
categories:
    - research
header: no
  # image_fullwidth: header_unsplash_leaf.jpg
permalink: /research/phd-thesis/
---

Tools/Skills: OpenFOAM, MATLAB, high performance computing, Python, Pointwise

Advisor: Dr. Sheryl Grace

This work is sponsored by a National Defense Science and Engineering Fellowship.

## Abstract
Hypersonic vehicles can sustain significant damage when they are impacted by atmospheric
particles, including raindrops on the scale of 2 mm. Before colliding with the vehicle, these
droplets become deformed and can breakup entirely when they interact with the vehicle’s
shock wave. Therefore, knowledge of breakup mechanisms in shock-droplet interactions can
give valuable information pertaining to the vehicle loading and potential damage. Current
literature explores the role of interface instabilities in the droplet breakup, but there is not
a clear consensus on what process may be dominating the breakup. Additionally, most of
these studies do not consider that cavitation can also occur in the droplet. Cavitation is the
explosive growth of air bubbles in the presence of a very low, potentially negative pressure,
which occurs in droplets due to internal shock wave reflections. Therefore, this research
looks to explore the role of bubble dynamics in shock-droplet interactions, with particular
focus on how an initial bubble nucleus (or several nuclei) can impact the droplet breakup
process.

Towards this goal, the native OpenFOAM solver will first be verified with simplified
problems, including bubble dynamics in a free field, bubble dynamics in a cylindrical drop,
and a simplified 2D droplet breakup with a single bubble nucleus in the drop. This model
will provide some information pertaining to the role of bubble dynamics in droplet breakup,
but to capture the more complex phenomena associated with shock-droplet interactions,
solver modifications will be necessary. The modified solver will be verified with analytic,
experimental, and computational results, and it will be used to model a 2D shock-droplet
interaction when there is an initial bubble nucleus in the drop. This model will also be used
to study how multiple bubbles can interact with each other and the droplet; a parameter
study will explore how changing the initial vapor volume and bubble positions can change
the droplet breakup dynamics. Finally, the 2D model will be extended to a 3D model
because the spherical droplet will have different internal wave dynamics than the cylindrical
one. Additionally, the 3-dimensional model will allow for better capturing of the complex
interface instabilities.
<!--more-->





 [1]: http://foundation.zurb.com/docs/components/grid.html
