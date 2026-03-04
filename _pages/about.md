---
permalink: /
title: "Chao Chen (陈超)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>I received my B.Sc. degree from <a href="https://dii.nju.edu.cn/">Kuang Yaming Honors School</a>, <a href="https://www.nju.edu.cn">Nanjing University</a> in June 2022, majoring in Brain Science and Artificial Intelligence.</p>
<p>From September 2022 to June 2025, I was a member of the <a href="https://www.lamda.nju.edu.cn/">LAMDA</a> Group and pursued my M.Sc. degree at the School of Artificial Intelligence, Nanjing University, researching on Reinforcement Learning under the supervision of <a href="https://ai.nju.edu.cn/zhangzongzhang/">Prof. Zongzhang Zhang</a>.</p>
<p>Currently, I am a Ph.D. student at the <a href="https://cs.pku.edu.cn/">Department of Computer Science</a>, <a href="https://pku.edu.cn/">Peking University</a>, supervised by <a href="https://hughw19.github.io/">Prof. He Wang</a>. My current research interest lies in humanoid robot control.</p>

<h1>Publications</h1>
{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
