---
layout: page
title: research
permalink: /projects/
description: <i><br>"When we try to pick out anything by itself, we find it hitched to everything else in the Universe."</i> <br> - John Muir, My First Summer in the Sierra, 1911 <br>
nav: true
---

<<<<<<< HEAD
***

<div class="projects grid">

  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
=======
  {% else %}
  <!-- Display projects without categories -->
    {% assign sorted_projects = site.projects | sort: "importance" %}
    <!-- Generate cards for each project -->
    {% if page.horizontal %}
      <div class="container">
        <div class="row row-cols-2">
        {% for project in sorted_projects %}
          {% include projects_horizontal.html %}
        {% endfor %}
        </div>
      </div>
>>>>>>> f4c01acac710f8b4d9dea317d12b212a406552d2
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <div class="row ml-1 mr-1 p-0">
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>

<!-- <i><br>"When we try to pick out anything by itself, we find it hitched to everything else in the Universe."</i> <br> - John Muir, My First Summer in the Sierra, 1911 <br><br> Each time I begin a project, I am quickly reminded of the above quote.  Few (if any) processes in the natural world exist in isolation of others.  Likewise, few scientific studies of the natural world are truly uni-thematic.  <br><br>  Still, thematic categorizations of research - albeit imperfect - are useful.  In that spirit, below is a working list of ongoing research themes.  Each entails an evolving list of inherently multi-thematic projects. -->

<!-- <i><br>"When we try to pick out anything by itself, we find it hitched to everything else in the Universe."</i> <br> - John Muir, My First Summer in the Sierra, 1911 <br><br> Each time I begin a project, I am quickly reminded of Muir, above, waxing poetic in the wilderness. Few (if any) processes in the natural world exist in isolation of others.  Likewise, few scientific studies of the natural world are truly uni-thematic.  <br><br>  Still, thematic categorizations of research endeavors - while imperfect - are useful.  In this spirit, below I've presented a working list of ongoing research themes.  Each theme entails an evolving list of projects, each inherently multi-thematic. -->
