---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a first-year Ph.D. student at the [University of California San Diego](https://ucsd.edu/), advised by Prof. [Lianhui Qin](https://lianhui.ucsd.edu/). My research interests lie in world models, AI interaction with the world, reinforcement learning, and reasoning.

Before joining UCSD, I received my bachelor's degree from the [ACM Class](https://acm.sjtu.edu.cn/home) at [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), where I was a member of [RHOS Lab](https://mvig-rhos.com/) co-advised by Prof. [Cewu Lu](https://www.mvig.org/) and Prof. [Yonglu Li](https://dirtyharrylyl.github.io/).

Feel free to contact me in any possible way.

## Research Interests
{: #research-interests .home-section}

My goal is to build AI systems that learn by interacting with the world and keep getting better on their own.

- **Real-World AI:** models that can interact with and solve problems in real-world scenarios.
- **Self-Improving AI:** systems that continually improve themselves through their own experience.
- **Reinforcement Learning:** learning from interaction and feedback as the engine behind both.
{: .research-interests}

## News
{: #news .home-section}

{% include home/news.html shown=5 %}

## Selected Publications
{: #publications .home-section}

{% for pub in site.data.publications %}{% if pub.selected %}{% include home/pub-item.html pub=pub show_year=true %}{% endif %}{% endfor %}

<p class="see-all"><a href="{{ '/publications/' | relative_url }}">Full publication list →</a></p>

## Education
{: #education .home-section}

{% include home/timeline.html items=site.data.education %}

## Experience
{: #experience .home-section}

{% include home/timeline.html items=site.data.experience %}

## Beyond Research
{: #hobbies .home-section}

Beside research interest, I am always open to new experience and activity.

I'm fond of a wide variety of sports like soccer and basketball. Reading and cooking also largely intrigues me.

I was trained as a professional athlete in my junior years and that experience meant a lot to me.
