---
title: Research
nav:
  order: 1
  tooltip: 
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

{% include section.html %}

## Current Projects

{% capture text %}
**Collaborative Coordination of Robots**

We study how teams of robots can coordinate their actions to accomplish complex tasks efficiently. Our research addresses task allocation, resource allocation, and cooperative routing through market-based approaches, distributed optimization, and consensus-based control. By combining optimization, game theory, and decision-making methods, we investigate how interactions among individual agents shape collective performance and develop efficient algorithms for coordinating robotic teams.
<br>

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/3P_coord.png"
  headline="3P Collaborative Routing"
  text=text
%}

{% capture text %}
**Resilient Distributed Control**

Robotic teams must operate reliably despite uncertainty, communication limitations, and potentially malicious or deceptive agents. We develop distributed control and decision-making methods that enable agents to coordinate without relying on a central controller, while maintaining resilience to disruptions and adversarial behavior. Our research explores fair allocation principles, incentive mechanisms that encourage cooperation, and estimation and learning methods for inferring unknown system characteristics and agent behavior.
<br>

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/2P_trust.png"
  headline="Trust-based Information Exchanges"
  text=text
%}

{% capture text %}
**Robotic Autonomy**

Individual robots need greater autonomy as robotic teams grow in size and operate beyond reliable human supervision. Our research connects guidance, navigation, and control with distributed decision-making, enabling robots to estimate their state and surroundings, plan their motion, and coordinate with neighboring agents. We focus on swarm robotics under communication delays, intermittent connectivity, and unreliable information, with applications spanning aerospace, ground, and maritime systems.
<br>

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/DSA.png"
  headline="Satellite Constellation Control"
  text=text
%}