---
layout: page
permalink: /varia/
title: varia
description: Various links and pointers I found useful/interesting. Info that does not belong to other categories.
---


### Science popularisation
For years I've been involved with the [Summer School of Science](http://drustvo-evo.hr/s3/){:target="\_blank"} in Croatia - a science-popularisation project for high-school students. If you know, or have, a high-schooler interested in science, please check this program out!


### Workshops
If you are interested in workshops touching about statistical relational learning, deep learning, program induction, and interactions between them, you might find these workshops interesting:
  - [StarAI - International Workshop on Statistical Relational Artificial Intelligence](http://www.starai.org/){:target="\_blank"}
  - [NAMPI - Neural Abstract Machines and Program Induction](https://uclmr.github.io/nampi/){:target="\_blank"}
  - [Relational Representation Learning workshop](https://r2learning.github.io/){:target="\_blank"}
  - [Learning as Program Induction](https://programinduction.github.io/){:target="\_blank"}


### Books, materials, ...
  - Books:
  {% for book in site.data.books %}
    - [{{ book.name }}]({{ book.link }}): {{ book.description }}
  {% endfor %}
  - Tools:
  {% for tool in site.data.tools %}
    - [{{ tool.name }}]({{ tool.link }}): {{ tool.description }}
  {% endfor %}
