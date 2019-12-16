---
layout: page
title: Shiya Song
tagline: homepage
---
{% include JB/setup %}

### About
![](Images/Shiya.jpg | width=20)

I’m a passionate genomics data scientist specialized in algorithm development for DNA related products. Since I joined Ancestry DNA Science team in 2016, I develop statistical algorithms to interpret millions of genotypes and pedigrees and provide new genomic discoveries for consumers. I had a Ph.D in Bioinformatics and Master in Statistics from University of Michigan, where I worked with professor [Jeffrey Kidd](http://genome.med.umich.edu/kidd-lab/). I’m interested in population & statistical genetics, next generation sequencing analysis, statistical inference, machine learning and deep learning. I love new challenges and work with talented people. 

### Contact
Email me at song.shiya@gmail.com. My linkedin profile [here](https://www.linkedin.com/in/shiya-song-35169643/). My twitter [here](https://twitter.com/ShiyaSong)

### Posts 
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



