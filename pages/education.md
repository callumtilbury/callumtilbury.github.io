---
layout: page
title: education
permalink: /education/
weight: 1
---

#### formal education

<div class="col mt-4">
  <div class="timeline-body">
    {% for item in site.data.formal_education %}
      <div class="timeline-item">
        <div class="content">
        <div class="row">
            <div class="col-2">
                <img src= "{{item.image}}" alt="" width="100%" style="vertical-align:top;margin:-10px 0px">
            </div>
            <div class="col-10">
                <h4>{{ item.institution }}</h4>
                <h5><i>{{ item.qualification }}</i></h5>
                <h6 class="date">{{ item.from }} — {{ item.to }}</h6>
            </div>
        </div>
        <br/>
        {{ item.description }}
        </div>
      </div>
    {% endfor %}
  </div>
</div>