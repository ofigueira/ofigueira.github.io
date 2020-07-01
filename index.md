---
layout: default
title: Summer 2020 DREU Project Site
---

* TOC
{:toc}

## About Me

My name is Olivia Figueira and I am a senior Computer Science and Engineering major with minors in Mathematics and Economics at [Santa Clara University](https://www.scu.edu/) in Santa Clara, California, graduating in 2021. When it comes to research, I am interested in the fields of security and privacy, human-computer interaction, machine learning, and humanitarian computing. In Summer 2020, I am participating in the virtual CRA-WP DREU at the [University of Illinois at Urbana-Champaign](https://illinois.edu/).

## About My Mentors

My mentors are **Dr. Gang Wang** and **Dr. Dakshita Khurana** at the [University of Illinois at Urbana-Champaign](https://illinois.edu/) in the [Department of Computer Science](https://cs.illinois.edu/). 

Dr. Wang's research covers a range of topics in Security and Privacy, Internet Measurement, Mobile Networks, and HCI, mostly from data-driven perspectives. Learn more about Dr. Wang's work [here](https://gangw.cs.illinois.edu/).

Dr. Khurana's research focuses on Cryptography and the foundations of Security, and more broadly in Theoretical Computer Science. Learn more about Dr. Khurana's work [here](https://www.dakshitakhurana.com/).

## About My Project

Fabricated online social network profiles are becoming increasingly sophisticated and thus harder to detect by real human users. Fake profiles have begun using more complex generative algorithms for both text and image generation to fool real users into trusting them. To determine how well users can identify fabricated profiles, we conduct a user study with offline social profiles created using generative text and image algorithms. Users are asked to rank each profile’s credibility, and we investigate their ability to detect fake accounts comparing inter-field and intra-field semantic, temporal, and stereotypical profile inconsistencies.

*Check back at the end of the summer to access my Final Report on this research project.*

<!-- [My Final Report](files/finalreport.pdf) -->

## My Blog

<!-- Visit this page to check out my [blog](blog.html) where I post weekly updates during my DREU experience. -->

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1 style="font-size: 20px;"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
