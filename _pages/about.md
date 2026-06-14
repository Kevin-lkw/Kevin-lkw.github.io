---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I am Kewei Lian (连可为). I am currently a PhD student at School of Computing, 
National University of Singapore (NUS), advised by Prof. [Anji Liu](https://liuanji.github.io/).

I obtained my B.S. degree in Computer Science from Peking University (PKU) in 2025. I was in the team of [CraftJavis](https://craftjarvis.github.io/), advised by Prof. [Yitao Liang](https://scholar.google.com/citations?user=KVzR1XEAAAAJ&hl=en). I also worked with Prof [Di He](https://dihe-pku.github.io/) on the topic of NLP during my undergraduate studies.

## Research interests:
- Designing Memory for Models and Agents: What is the best way to equip models with memory? What is the form and How to use it?
- How to process context in a proper and efficient way? Context is a natural form of memory, and can we move beyond vanilla quadratic attention to process it?

# Publications {#publications}
Below is a list of selected publications. Please refer to my [Google Scholar](https://scholar.google.com/citations?user=ziHLMt4AAAAJ) for the full list of publications.

{% for pub in site.publications reversed %}
  {% include publication.html
     title=pub.title
     image=pub.image
     summary=pub.summary
     authors=pub.authors
     venue=pub.venue
     links=pub.links %}
  {% unless forloop.last %}
  <hr class="pub-divider">
  {% endunless %}
{% endfor %}

# Others
In my spare time, I enjoy playing badminton, baseball, and swimming. I try watersports in Singapore like
Sailing and Kayaking, which are really fun!!

I'm always happy to chat! Feel free to reach out to me via [email](mailto:liankewei2003@gmail.com) for anything!
