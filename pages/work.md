---
layout: page
title: work
permalink: /work/
weight: 2
---

<div class="col mt-4">
  <div class="timeline-body">
    {% for item in site.data.work %}
      <div class="timeline-item">
        <div class="content">
        <div class="row">
            <div class="col-2">
                <img src= "{{item.image}}" alt="" width="100%" style="vertical-align:top;margin:-0px 0px">
            </div>
            <div class="col-10">
                <h4>{{ item.company }}</h4>
                <h5><i>{{ item.location }}</i></h5>
            </div>
        </div>
        <br/>
        {% for role in item.roles %}
            <h5><b>{{ role.title }}</b></h5>
            <p class="date">{{ role.period }}</p>
            {% if role.description %}
                <p> > {{ role.description }} </p>
            {% endif %}
        {% endfor %}
        </div>
      </div>
    {% endfor %}
  </div>
</div>

<br/>