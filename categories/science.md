---
layout: page-doc
title: Science
subheading: Learn what our universe is made of.
description: Learn what our universe is made of.
color: grad-blog
image: https://drive.google.com/uc?id=1y5KObOLi-1kEkRg6GToK53gy7a6IlSj_
permalink: /science
---

<div class="home-container">
  <div class="home-articles">
    <div class="home-wrapper">
      <div class="page-holder">
        <ul>
        {% for post in site.posts %}
          {% if post.category contains 'science' %}
            {% if post.class contains 'Physics' %}
                <li>
                  <a class="post-link" href="{{ site.baseurl }}{{ post.url }}">
                    <div class="page-treasure">
                      <h2>{{ post.title }}</h2>
                      <p>{{ post.description }}</p>
                    </div>
                  </a>
                </li>
              {% endif %}
              {% if post.class contains 'Chemistry' %}
                <li>
                  <a class="post-link" href="{{ site.baseurl }}{{ post.url }}">
                    <div class="page-treasure">
                      <h2>{{ post.title }}</h2>
                      <p>{{ post.description }}</p>
                    </div>
                  </a>
                </li>
              {% endif %}
            {% endif %}
            {% if post.class contains 'Botany' %}
                <li>
                  <a class="post-link" href="{{ site.baseurl }}{{ post.url }}">
                    <div class="page-treasure">
                      <h2>{{ post.title }}</h2>
                      <p>{{ post.description }}</p>
                    </div>
                  </a>
                </li>
            {% endif %}
            {% if post.class contains 'Zoology' %}
                <li>
                  <a class="post-link" href="{{ site.baseurl }}{{ post.url }}">
                    <div class="page-treasure">
                      <h2>{{ post.title }}</h2>
                      <p>{{ post.description }}</p>
                    </div>
                  </a>
                </li>
            {% endif %}
        {% endfor %}
        </ul>
      </div>
    </div>
  </div>
</div>